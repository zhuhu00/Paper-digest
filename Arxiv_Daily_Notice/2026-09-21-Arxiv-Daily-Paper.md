# Showing new listings for Monday, 21 September 2026
## Keyword: SLAM
### Title:
          Towards Effective Visual-Inertial SLAM with Passive-Only Sensors for Low-Cost Autonomous Underwater Vehicles
 - **Authors:** Grant Schwidder, David Widhalm, Junaed Sattar
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Improvements to Visual-Inertial Simultaneous Localization and Mapping (VI-SLAM) for low-cost autonomous underwater vehicles (AUVs) are critical for transitioning advanced marine robotics from specialized labs to broader research and hobbyist applications. While high-end AUVs typically rely on expensive sensor suites - such as Doppler Velocity Logs (DVLs) and Ultra-Short Baseline (USBL) systems - this work demonstrates that robust, high-quality navigation is achievable using a sub-$10, 000(USD) platform equipped only with inexpensive consumer-grade sensors. By leveraging a similarly priced, open-source AUV, we evaluate the performance of stereo cameras, Micro-electromechanical System (MEMS)-based IMUs, and depth sensors in a fully unconstrained 6-degree-of-freedom (6-DOF) underwater environment. We analyze the efficacy of off-the-shelf SLAM packages and propose optimizations for sensor fusion to mitigate the visual and physical challenges of untethered underwater operation. Our results prove that a usable SLAM solution can be accessible to the masses, providing a benchmark for expectations in demanding, real-time maritime missions without the financial barrier of industrial-grade hardware.
### Title:
          MAPLE-RF: Efficient Probabilistic RF Source Localization in Partially Explored Environments
 - **Authors:** Haozhe Lei, Sundeep Rangan
 - **Subjects:** Subjects:
Robotics (cs.RO); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Localizing a radio-frequency (RF) transmitter from received signals often requires a model of the environment to predict how obstacles block and reflect the signal. In many robotic applications, however, only a partial map is available, particularly when a robot localizes the source while exploring with simultaneous localization and mapping (SLAM). We study single-snapshot transmitter localization on such partially explored maps and compare two approaches that output a posterior over transmitter locations. The first extends a digital-twin method, which ray-traces every candidate location, to partial maps by treating unexplored space as free and training on mixed map coverage. The second, MAPLE-RF, encodes estimated path angles of arrival and signal-to-noise ratios as grid channels aligned with map knownness, occupancy, and line-of-sight visibility, and a U-Net scores all candidate positions in one pass without simulating propagation at inference. Ray-tracing simulations of indoor environments indicate that training on mixed map coverage is essential for both approaches. The digital-twin approach is more accurate on most single-snapshot metrics, while MAPLE-RF comes close at a query cost that does not depend on the propagation model and is more than two orders of magnitude below a fresh full-grid query with general-purpose ray tracing. Both outperform Gaussian and Gaussian-mixture baselines, and on exploration routes guided by its own estimates, fused MAPLE-RF posteriors place more probability near the source than the compared methods. Code and data will be released.
### Title:
          Noctif3R: Feed-Forward Monocular Real-Time SLAM for Photon-Limited Scenes on Embedded Hardware
 - **Authors:** Mihir Chauhan, Aditya Uday Abhang, Kevin Biju Mathew, Aniket Bera
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robots carrying out tasks in dark environments need to localize from a single RGB camera, in light so low that the per-pixel signal approaches the sensor's own noise, on a power-constrained onboard computer, in real time. Each of these constraints has matured pipelines, but the intersection does not. Offline low-light reconstruction now recovers structure below -4 dB but is far too slow to run in real time, while the real-time monocular systems a robot can actually carry (DROID-SLAM, DPV-SLAM, etc.) degrade or fail when SNR gets low. We measured how they fail: across the nine lowest darkness levels of our scenes, DROID-SLAM returns a full-length trajectory carrying no information about the camera's motion on all nine, VGGT-SLAM and CUT3R on eight, pi^3 on seven, and DPV-SLAM on four. We present SYS, a monocular pipeline built on a low-light feed-forward pointmap front end with an explicit match gate, which returns three tracked trajectories and no uninformative ones, at the lowest error of any method where it tracks (24-47% of the no-information ceiling against 56-73% for the strongest baseline), and at the narrowest coverage. On a real robot video take in which 86.5% of delivered frames are entirely black, every configuration of ours stops after the lit beginning, while DROID-SLAM and DPV-SLAM each emit a pose for all 1178 frames. Our method contribution is an embedded execution path for the Jetson AGX Orin: running the map, keyframes and backend at 384 pixels with tracking at 256, together with two fixes to the per-frame pose solve, is a replicated Pareto improvement, 1.28x throughput at 0.964x error on one scene and 1.42x at 0.68x on a second, with 47% less peak GPU memory and 29% less energy per pose. We evaluate on a calibrated, bit-exact regenerable noise ladder, on relabelled real-world dark exposures, and on a new dark-room video ladder recorded from a Boston Dynamics Spot robot.
### Title:
          Cube-Splat: High-Fidelity 360° Gaussian Splatting SLAM via Cubemap Factorization and Adjoint-Consistent Optimization
 - **Authors:** Xiangfei Guo, Hao Shi, Yufan Zhang, Zhonghua Yi, Yongqi Mao, Xiaoting Yin, Kaiwei Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent progress in 3D Gaussian Splatting (3DGS) has enabled dense visual SLAM with pinhole cameras, yet most pipelines are not designed for panoramic imagery. We present Cube-Splat, the first panoramic GS-SLAM framework that factorizes each 360° frame into a cubemap of four fixed-orientation virtual pinhole views sharing a single optical center. By designating the front face as the primary pose state, we accumulate gradients from all faces via an adjoint mapping, thereby enabling multi-face observations to coherently update a single state while strictly preserving cross-view geometric consistency. Concurrently, our mapping module densifies and optimizes anisotropic Gaussians using aggregated cubemap rays for high-fidelity, dense reconstruction. Furthermore, to rigorously evaluate panoramic SLAM under diverse and challenging conditions, we introduce SynPano, a highly scalable, photorealistic synthetic dataset featuring parameterized complex trajectories and multi-modal ground truth. Extensive evaluations on two public benchmarks (PALVIO and OmniBlender) and our SynPano dataset, collectively encompassing both indoor and outdoor scenes, demonstrate that Cube-Splat achieves state-of-the-art (SOTA) performance in tracking accuracy and reconstruction fidelity. Both the source code and the SynPano dataset are available at this https URL.
### Title:
          Adaptive World Memory 3D Foundation Model for Scalable 3D Mapping, Localization, and Rendering
 - **Authors:** Tianchen Deng, Guole Shen, Yilin Shen, Wenhua Wu, Yilin Fang, Ziqi Ma, Tianjun Zhang, Shenghai Yuan, Wolfram Burgard, Hesheng Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent 3D foundation models enable generalizable geometric reasoning from RGB images but remain limited in persistent memory, scalability, and renderable scene modeling. We present a memory-centric 3D foundation model for scalable robotic localization, reconstruction, and Gaussian rendering. Its core is an adaptive world memory mechanism that combines transformer-based gated updates with test-time temporal-spatial regulation. Learned gates control recurrent memory propagation, while temporal state evolution and spatial observation-state consistency regulate token-wise updates and forgetting over long image sequences. To support large-scale mapping, we organize memory into local submaps and integrate progressive mapping and tracking, loop closure, and SL(4)-based global refinement to maintain local accuracy and global consistency. A Gaussian reconstruction head decodes memory-enhanced features into renderable primitives, unifying camera pose estimation, dense point-cloud reconstruction, and photorealistic rendering within a single model. Experiments on public benchmarks and self-collected datasets from diverse robotic platforms demonstrate improved trajectory accuracy, reconstruction completeness, and rendering quality over existing 3D foundation reconstruction and SLAM baselines. These results support adaptive memory as a foundation for persistent robotic world modeling. The dataset and code will be made publicly available at \href{this https URL}{this https URL}.
### Title:
          HAT: Hypothesis-Anchored Tracking for Video Monocular Spacecraft Pose Estimation
 - **Authors:** André Lopo, Atabak Dehban, Rodrigo Ventura
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular 6-DoF pose estimation of non-cooperative targets is important for on-orbit servicing and debris removal. A single-image estimator can confuse near-symmetric spacecraft orientations, and tracking can preserve an incorrect pose. We present Hypothesis-Anchored Tracking (HAT), a causal framework that uses inter-frame motion to select among competing CAD-based pose hypotheses before alignment and fusion. Rather than independently choosing the highest-scoring hypothesis in each image, HAT retains competing orientation histories and selects a pose to anchor the relative trajectory estimated by monocular SLAM. Sparse anchors and pose fusion provide per-frame estimates after initialization without revising past outputs. The method requires only a calibrated RGB sequence, a metric CAD model, and target image regions, which can be supplied by detection or segmentation. The pretrained pose and SLAM networks require no target-specific training or fine-tuning. We evaluate two versions, Mega-HAT and Pico-HAT, using MegaPose and PicoPose, on SPARK-2024, SwissCube and SHIRT, with YCB-Video assessing performance outside the space domain. Using one temporal configuration per method, the arithmetic means of the four dataset-wise comparisons show 9.4% lower mean pose error and 3.76 times the sustained input FPS for Mega-HAT relative to independent MegaPose, and 23.9% lower mean pose error and 2.42 times the FPS for Pico-HAT relative to independent PicoPose. Mega-HAT ablations on SPARK and an offline reference examine component contributions and the effect of revising past estimates.
### Title:
          QuranicMMLU: A Cognitively-Aware Benchmark for Evaluating Generative AI Solutions on Quranic Linguistic Knowledge
 - **Authors:** Rawan El Ghali, Umm Kulsoom, Anas Madkoor, Dima Faris Alsaudi, Roaa Abdelmagid, Roaa Ibrahim, Raghad Mousa, Hamza Aljaji, Abdullah Khanafer, Abdallah Alkanani, Salah Feras Alali, Rawan Khaled Mohamed, Ehsaneddin Asgari
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce QuranicMMLU, a benchmark for evaluating generative AI on Quranic Arabic across multiple dimensions of linguistic complexity. Existing Quranic benchmarks center on general question answering and semantic retrieval, without probing specific linguistic competencies or stratifying by cognitive demand and verse difficulty. We construct a five-pillar Quranic taxonomy spanning Phonology, Morphology, Syntax, Semantics, and Pragmatics, with 31 leaves covering phenomena from tajwīd and root-and-pattern morphology to occasions of revelation and inter-surah coherence. For each leaf we generate questions stratified by Bloom's cognitive level and verse perplexity, then have LLM as a judge to independently answer and score every item and route the annotations to manual review. The resulting dataset comprises 980 human-reviewed questions, each issued in both open-ended and multiple-choice form. We benchmark 12 systems on these items and find that the Islamic-specialized model leads, yet every system scores higher on multiple-choice accuracy (average 84%) than open-ended answer quality (average 60%): the two rankings agree closely (Kendall's {\tau}=0.73), but multiple-choice scoring hides failures that surface only once answer choices are removed. QuranicMMLU thus offers a rigorous, linguistically grounded framework for evaluating Arabic NLP in the Quranic domain.
## Keyword: odometry
### Title:
          Robust Structureless Monocular Visual Inertial Initialization Exploiting Line Features and Vanishing Points
 - **Authors:** Junwan Choi, Woongrae Jo, Dong-Uk Seo, Jinwoo Jeon, Hyun Myung
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate initialization is essential for reliable visual-inertial odometry (VIO), but it is often ill-conditioned under degenerate motions. Existing methods typically require restrictive excitation motions to ensure sufficient observability or rely on computationally expensive 3D structure reconstruction, limiting efficient and practical deployment. To address these limitations, we propose SLIM-init, a structureless monocular VIO initializer that directly exploits geometric constraints from tracked 2D line features without explicit 3D landmark reconstruction. Specifically, SLIM-init leverages line-derived vanishing points (VPs) as translation-invariant orientation cues to provide robust rotation-only constraints under degenerate scenarios such as low-parallax or translation-dominant motions. It further incorporates a line epipolar residual to constrain translation and a line-normal projection residual to improve the conditioning of linear alignment, enhancing the accuracy and robustness of initial state estimation. Extensive experiments on a public benchmark and challenging custom degenerate-motion sequences demonstrate improved accuracy and robustness over state-of-the-art initialization methods. The source code is available at: this https URL.
### Title:
          NeuRIO: A Streaming Neural Estimator for Zero-Shot Sim-to-Real Multi-Robot Relative Inertial Odometry
 - **Authors:** Zhehan Li, Jiadong Lu, Shengwei Ren, Chao Xu, Yanjun Cao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present NeuRIO, a streaming neural estimator for anchor-free 6-DoF relative inertial odometry using only identified inter-robot bearings, ranges, and IMU measurements. NeuRIO canonicalizes measurements into gravity-aligned coordinates, represents robots as nodes and mutual observations as factors, and uses attention for spatial reasoning and GRUs for temporal modeling. As a graph network, NeuRIO applies shared node-wise and factor-wise operators throughout the network, enabling it to handle different team sizes and time-varying observation graphs. NeuRIO is trained on a simulator that couples various motion patterns, device-level sensor characteristics, and diverse, realistic modeled, and temporally persistent sensor corruptions. In this way, NeuRIO achieves zero-shot sim-to-real transfer. Across $24$ real-world sequences, NeuRIO achieves $14.1\,\mathrm{cm}$ position RMSE and $3.9^\circ$ rotation RMSE. More importantly, NeuRIO demonstrates strong computational scalability, maintaining an update cost below $20\,\mathrm{ms}$ with up to $400$ robots in simulation, while optimization-based methods exceed $20\,\mathrm{ms}$ at only $24$ robots. Moreover, even trained on limited team sizes, NeuRIO transfers directly to unseen larger teams without architectural or parameter changes.
### Title:
          SFVO: Decoupled Confidence-Guided Stereo-Flow Visual Odometry with Bidirectional PnP
 - **Authors:** Kai Zhang, Guoyang Zhao, Jun Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning-based visual odometry (VO) has achieved significant progress, yet most existing methods focus on a monocular approach, which suffers from scale ambiguity. Stereo VO provides real metric by its nature, but remains less studied in deep learning VO due to its high computational cost and modeling complexity. Recent advances in stereo matching and optical flow estimation have made dense visual correspondence increasingly accurate and reliable, but their complementary geometric information has not been fully exploited for VO. In this paper, we present SFVO, a correspondence-driven stereo VO framework that directly builds upon pretrained stereo matching and optical flow models. SFVO exploits pretrained stereo matching and optical flow models to estimate stereo and temporal correspondences. Instead of learning pose directly from images, SFVO maps learned correspondences into geometric constraints and predicts which points are trustworthy. To improve the reliability of visual correspondence-based geometric constraints, we introduce decoupled confidence maps for rotation and translation. This design better aligns the characteristics of visual correspondence and 6-DoF transformations. Extensive experiments on outdoor and indoor datasets demonstrate that SFVO achieves robust and accurate pose estimation with strong generalization capability. The code will be released.
### Title:
          VideoReloc: Long-Term Indoor Video Relocalization against a Kilobyte-Scale Semantic Scene Graph
 - **Authors:** Qianru Li, Xuyang Chen, Xuqin Wang, Zhenghao Zhang, Hongyi Luo, Tao Wu, Daniel Cremers, Lu Liu, Yanfeng Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Given a compact semantic scene graph, long-term indoor video relocalization estimates a map-frame trajectory after lighting and furniture changes. Visual methods rely on appearance and become unreliable under these changes; localizing one frame at a time from object classes and geometry instead leaves sparse, ambiguous evidence. We introduce VideoReloc, whose adaptive clips use odometry to gather spatial evidence until object and motion criteria are met, adapting query length to the observed scene. Its run-level decision rechecks conflicting placements using evidence accumulated across connected clips, stabilizing the trajectory beyond adjacent-clip tracking. Hypothesis-first registration proposes poses from object triplets and verifies each using clip-wide object centers and box surfaces. Orientation-aware refinement uses box faces, gravity and wall directions to resolve ambiguity in camera orientation and refine the full pose. This reframes sparse-map relocalization as verification of spatially extended video queries, moving discriminative support from stored appearance to temporal context and permitting a 100 kB map of class-labelled boxes. On RIO10 and ReplicaCAD, the all-frame localization success rate at 1 m/10$^\circ$ is 73.5% and 61.1% under causal evaluation, rising to 90.6% and 74.8% with clip closure. The evaluated per-frame scene coordinate regressors reach up to 47.6% and 49.8%, respectively, with maps of 12.6-42 MB. Project page: this https URL
### Title:
          Info3R: Information-Adaptive Test-Time Training for 3D Reconstruction
 - **Authors:** Sunghyun Baek, Hanna Bae, Minchan Kwon, Junmo Kim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based models have recently achieved strong performance on 3D reconstruction from images, and recent works extend them to process video streams in an online manner for real-world deployment. However, existing methods overlook two key signals when handling long image streams: the importance of each incoming frame and the information saturation of the model's internal state. In this paper, we propose Info3R, a novel information-adaptive test-time training method for the online 3D reconstruction. We introduce an information-aware state update that modulates the state update strength based on the redundancy and informativeness of each incoming frame. To restore the state's plasticity -- its capacity to incorporate new observations -- we propose a dynamic state reset, triggered by the cumulative magnitude of state updates and the model's prediction confidence and accompanied by an anchor-to-world alignment. Our method achieves consistent improvements on camera pose estimation, video depth estimation, and 3D reconstruction, while substantially mitigating the performance degradation in the long sequence evaluation. Notably, on KITTI Odometry, our method achieves on average 1.68x lower ATE than LongStream, demonstrating its robustness on extended outdoor sequences.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Do Spinning Radar Doppler Velocity Measurements Improve Vehicle Detection and Tracking?
 - **Authors:** Eric Xie, Daniil Lisus, Timothy D. Barfoot
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spinning frequency-modulated continuous-wave (FMCW) radars have been gaining popularity in autonomous vehicle perception on account of their robustness to adverse weather conditions and 360° field of view. Recently, scanning radars have also been shown capable of generating per-azimuth Doppler velocity. In this paper, we investigate whether these Doppler velocity measurements improve spinning radar vehicle detection and tracking performance. For detection, we estimate the ego motion and use it to undo the Doppler range distortion of the radar image before passing it to a network. For tracking, we propose a new way to estimate a per-vehicle velocity and use it as a prior for the tracker's motion model. Since Doppler-enabled spinning radar data is not available in any dataset with ground-truth dynamic object labels, our first contribution is an automatic labelling pipeline that uses an ensemble of fine-tuned off-the-shelf lidar detectors to label all 643 km of the Boreas Road Trip dataset. We then transfer detections to radar, and use over 250 km of vehicle-dense sequences as ground-truth training data. By training and evaluating two state-of-the-art detectors, we show that Doppler undistortion can improve detection accuracy by up to $2.37$ points on mean average precision. Furthermore, we show that the Doppler velocity prior can improve tracking accuracy by $13.68$ points on multi-object tracking accuracy (MOTA) versus the zero-velocity initialization baseline, while achieving $99.7\%$ of the MOTA obtained using ground-truth velocities as the prior.
### Title:
          PointLAM: Local Attentive Mamba for Efficient Point-based 3D Object Detection
 - **Authors:** Xuanming Shang, Weijia Zhang, Chao Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D object detection from LiDAR point clouds faces a fundamental dilemma: voxel-based methods achieve efficiency at the cost of geometric quantization, while point-based methods preserve fidelity but suffer from prohibitive computational bottlenecks. Specifically, point-based architectures are crippled by slow downsampling strategies (e.g., FPS) and expensive dynamic neighbor queries (e.g., k-NN) coupled with costly continuous interactions. To tackle these systemic inefficiencies, we propose PointLAM, a highly efficient and powerful point-based architecture driven by two synergistic innovations. First, to resolve the downsampling bottleneck, we develop the Laplacian Point Sampler (LPS). LPS employs an implicit discrete Laplacian high-pass filter and Doubly Sorted Sampling to achieve fast, structure-aware foreground preservation. Second, to overcome local modeling latency, we design the Local Hadamard Aggregator (LHA). LHA decouples spatial indexing from feature representation using transient grids, and replaces complex continuous interactions with a Hadamard Gating mechanism for topology-aware, attentive modulation. By coupling this local gating with Bi-Directional Mamba (BDM) layers for global sequence modeling, we formulate the Local Attentive Mamba (LAM) block. Powered by this architecture, PointLAM achieves competitive performance on nuScenes and Waymo for point-based detectors. It rivals highly optimized voxel competitors while requiring a fraction of the computational footprint, demonstrating marked superiority in detecting small instances and handling extreme sparsity. Project page: this https URL.
### Title:
          VIRGA: Virtual-Agent-Intermediated Riemannian Geometry for Active-Sensing Air-Ground Coordination
 - **Authors:** Fenghe Guo, Runjie Shen, Chenyang Sun, Junrui Zhang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Air-ground autonomy becomes harder when the unmanned aerial vehicle (UAV) must remain observable by a gimbal light detection and ranging (LiDAR) mounted on the unmanned ground vehicle (UGV). The platforms must avoid dynamic obstacles while coordinating heterogeneous motion, limited sensing, and changing task initiative within one closed loop. This paper presents VIRGA, a neural geometric coordination framework that turns dual-LiDAR observations into bounded source-specific Riemannian fields and couples them through a virtual agent with reciprocal elastic feedback. Platform-aware execution maps convert the shared coordination reference into feasible UAV, UGV, and gimbal commands while enforcing active-observation safeguards. Evaluation against three complementary baselines reveals distinct limitations. An adapted Ray-RMP controller provides the fastest Riemannian response but produces insufficient clearance in the coupled air-ground task. A dense analytical Riemannian field improves geometric avoidance, yet its high evaluation cost prevents stable field-of-view maintenance. An adapted ColAG controller achieves the lowest latency but still incurs safety and observability violations. VIRGA completes all paired warehouse conditions safely, while a long-range cave stress test without retraining demonstrates sustained coordination in irregular and confined geometry. Ablations confirm contributions from online geometric evaluation, virtual-agent mediation, and reciprocal feedback.
### Title:
          The Role of Radiometric Features in Cross-Site Leaf-Wood Segmentation of LiDAR Point Clouds
 - **Authors:** Roman Kaharlytskyi, Derek T. Robinson, Roberto Guglielmi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Leaf-wood segmentation of individual trees from LiDAR point clouds is essential for quantitative structure models (QSMs) used in non-destructive biomass estimation. Existing segmentation methods typically exclude radiometric features (e.g., intensity, return number) to maximize cross-sensor compatibility. We challenge this design choice by evaluating cross-site and cross-platform generalization: training on the public Heidelberg dataset (terrestrial TLS, 1550nm) and testing on a novel dataset from Ontario, Canada (RPA-LS, 905nm). Results show that geometry-only methods - including state-of-the-art deep learning models trained on high-density LiDAR datasets - fail to generalize to the sparse, top-down geometry of aerial scans, achieving F1 scores <= 0.56. Incorporating radiometric features (intensity, return number, number of returns) improves F1 to 0.61, but more critically, increases wood recall by 119% from 0.16 to 0.35. Furthermore, geometry-only approaches often result in fragmented stem and branch components. We find that leveraging radiometric features preserves greater structural connectivity, resulting in more coherent architectures that are better suited for QSM reconstruction. We demonstrate that while geometric patterns are view-dependent and prone to overfitting scan patterns, radiometric features encode physical material properties that generalize across disparate sensors and environments.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          The Right Tool for the Job: On the Selection of Mitigations for GenAI Privacy Threats
 - **Authors:** Jonah Bellemans, Qianying Liao, Laurens Sion, Lieven Desmet, Wouter Joosen
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative Artificial Intelligence (GenAI) has rapidly evolved from an experimental technology into a foundational component of modern software systems. However, as its adoption grows, protecting sensitive personal data becomes increasingly challenging. Specifically, GenAI systems not only amplify traditional privacy threats but also introduce new inference-based risks, such as constructing detailed user profiles from seemingly harmless inputs. In response, privacy threat modeling frameworks are beginning to capture GenAI-specific privacy threats with finer granularity. At the same time, a growing number of mitigation techniques have been proposed to address these threats. However, although knowledge of both threats and mitigations continues to mature, the problem- and solution-space have developed largely independently. This position paper argues that the primary challenge in GenAI privacy engineering is not the lack of knowledge about privacy threats or mitigation techniques, but the missing bridge between them. We decompose this gap into three sub-problems: (i) lack of fine-grained threat-to-mitigation mapping for GenAI systems, (ii) inapplicable solution-space assumptions in the GenAI context, and (iii) prioritization difficulty under GenAI constraints. We derive four recommendations for future mitigation-selection approaches, and outline a suggested approach that extends established threat-to-mitigation mapping methods to GenAI-specific threat characteristics. We propose a research agenda toward more systematic privacy mitigation selection for GenAI-based systems.
### Title:
          Backward log orthogonal functions and their approximation theory
 - **Authors:** Mahmoud A. Zaky
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce a new class of backward logarithmic orthogonal functions and generalized backward logarithmic orthogonal functions, constructed by applying a terminal-endpoint logarithmic mapping to generalized Laguerre polynomials. These functions are designed for backward spectral approximations of problems whose solutions exhibit weak singularities at the terminal endpoint. The proposed basis functions generate non-polynomial weighted approximation spaces with nodes naturally clustered near the singular endpoint, and therefore provide an effective framework for resolving algebraic and logarithmic endpoint singularities. We develop the basic approximation theory for these backward logarithmic orthogonal functions, including recurrence relations, derivative formulas, orthogonality, Sturm--Liouville characterization, mapped Laguerre--Gauss quadrature rules, weighted projection estimates, backward Lagrange interpolation estimates, inverse inequalities, and stability properties in weighted Sobolev-type spaces defined through a terminal logarithmic pseudo-derivative. A generalized version of the basis is also introduced by incorporating an algebraic scaling parameter, which improves the flexibility of the approximation space and allows singular factors to be represented more effectively. The error analysis and numerical results show that the proposed backward logarithmic basis is particularly suitable for weakly regular functions with terminal-endpoint singularities and can recover exponential or high-order convergence rates that are typically lost when usual polynomial approximations are applied directly.
### Title:
          Towards Effective Visual-Inertial SLAM with Passive-Only Sensors for Low-Cost Autonomous Underwater Vehicles
 - **Authors:** Grant Schwidder, David Widhalm, Junaed Sattar
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Improvements to Visual-Inertial Simultaneous Localization and Mapping (VI-SLAM) for low-cost autonomous underwater vehicles (AUVs) are critical for transitioning advanced marine robotics from specialized labs to broader research and hobbyist applications. While high-end AUVs typically rely on expensive sensor suites - such as Doppler Velocity Logs (DVLs) and Ultra-Short Baseline (USBL) systems - this work demonstrates that robust, high-quality navigation is achievable using a sub-$10, 000(USD) platform equipped only with inexpensive consumer-grade sensors. By leveraging a similarly priced, open-source AUV, we evaluate the performance of stereo cameras, Micro-electromechanical System (MEMS)-based IMUs, and depth sensors in a fully unconstrained 6-degree-of-freedom (6-DOF) underwater environment. We analyze the efficacy of off-the-shelf SLAM packages and propose optimizations for sensor fusion to mitigate the visual and physical challenges of untethered underwater operation. Our results prove that a usable SLAM solution can be accessible to the masses, providing a benchmark for expectations in demanding, real-time maritime missions without the financial barrier of industrial-grade hardware.
### Title:
          MAPLE-RF: Efficient Probabilistic RF Source Localization in Partially Explored Environments
 - **Authors:** Haozhe Lei, Sundeep Rangan
 - **Subjects:** Subjects:
Robotics (cs.RO); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Localizing a radio-frequency (RF) transmitter from received signals often requires a model of the environment to predict how obstacles block and reflect the signal. In many robotic applications, however, only a partial map is available, particularly when a robot localizes the source while exploring with simultaneous localization and mapping (SLAM). We study single-snapshot transmitter localization on such partially explored maps and compare two approaches that output a posterior over transmitter locations. The first extends a digital-twin method, which ray-traces every candidate location, to partial maps by treating unexplored space as free and training on mixed map coverage. The second, MAPLE-RF, encodes estimated path angles of arrival and signal-to-noise ratios as grid channels aligned with map knownness, occupancy, and line-of-sight visibility, and a U-Net scores all candidate positions in one pass without simulating propagation at inference. Ray-tracing simulations of indoor environments indicate that training on mixed map coverage is essential for both approaches. The digital-twin approach is more accurate on most single-snapshot metrics, while MAPLE-RF comes close at a query cost that does not depend on the propagation model and is more than two orders of magnitude below a fresh full-grid query with general-purpose ray tracing. Both outperform Gaussian and Gaussian-mixture baselines, and on exploration routes guided by its own estimates, fused MAPLE-RF posteriors place more probability near the source than the compared methods. Code and data will be released.
### Title:
          Dynamics-Induced Commitment in Learning-Based Robotic Penalty Kicks
 - **Authors:** Ruize Geng, Hao E. Zhang, Yisen Li, Yikai Wang, H. Eric Tseng, Ding Zhao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning in robotic games is constrained not only by strategic information but also by what the body can still execute. We study this coupling in a hierarchical humanoid-quadruped penalty system in which game-level self-play policies command fixed soccer whole-body controllers (S-WBCs). The humanoid shooting skill is initialized from self-collected motion-capture data, whereas the quadruped saving skill is learned by reinforcement learning. We introduce dynamics-induced commitment mapping (DIC-Map), a body-grounded analysis that estimates continuation capability, identifies the first persistent loss of a terminal alternative, and tests whether the remaining interaction admits a reduced zero-sum game. For symmetric terminal alternatives, the reduced game yields a closed-form bound on optimal strategy concentration determined by the responder's value of deferring. We further show that, when the responder acts through an estimator, equal response values eliminate the direct terminal-allocation gradient and leave an estimator-mediated first-order learning channel. Experiments locate commitment about 0.29 s before contact, and changing only ball speed shifts deferral coverage. Across four responder policies, replacing the estimator raises save rate from 0.240 to 0.472, whereas a comparable gain in read accuracy obtained by waiting raises it only to 0.246. Posterior analysis is used for the equilibrium comparison because the available coverage terms are observational proxies. Project website: this https URL
### Title:
          REFINEPPO: Learning Continuous Control Policies by Iterative Action Refinement
 - **Authors:** Sachini Weerasekara, Sagar Kamarthi, Jacqueline Isaacs
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep reinforcement learning (DRL) has achieved strong performance across a wide range of continuous-control problems. These continuous-control policies, however, are often defined as direct mappings from an observed state to an action or action distribution, requiring a single feed-forward network to construct an optimal control decision in one pass. While effective, this formulation leaves little opportunity for the policy to reconsider or progressively improve an action once an initial prediction has been formed. In this work, we explore an alternative approach: rather than learning only to directly predict an action, can a policy learn to iteratively improve one, and can this iterative process provide advantages during policy learning? We introduce Iterative Action Refinement (IAR), an iterative action-construction method that constructs control actions through a sequence of learned residual corrections. Starting from an initial proposal, a shared refinement network repeatedly conditions on the observed state and the current action proposal, allowing each refinement step to revise the action constructed by preceding steps. The final refined proposal is then used to determine the action executed by the agent. We integrate this iterative action-construction mechanism with Proximal Policy Optimization (PPO), yielding REFINEPPO. We evaluate REFINEPPO across 14 benchmark control tasks, complemented by controlled ablations of refinement depth and update schedules and analyses aimed at understanding why iterative refinement is effective. Across these environments, REFINEPPO matches or exceeds the performance of standard PPO while demonstrating faster convergence on several tasks.
### Title:
          OpenRoIS: A Community-Driven Open-Source Middleware Implementing the Robotic Interaction Service (RoIS) Framework for Physical Robots and Virtual Agents
 - **Authors:** Sebastian Carrera Villalobos, Christopher Nolan Arellano, Arne Hitzmann, Edilson Morais Brito, Akira Utsumi, Yukiko Horikawa, Takahiro Miyashita, Lotfi El Hafi
 - **Subjects:** Subjects:
Robotics (cs.RO); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Service applications for human-robot interaction are commonly written against the hardware-specific interfaces of one platform, so a change of hardware forces a rewrite of the application. The Robotic Interaction Service (RoIS) Framework 2.0, standardized by the Object Management Group (OMG), addresses this fragmentation by defining a platform-independent model in which Service Applications interact with Human-Robot Interaction (HRI) Engines through standardized interfaces and hardware-independent symbolic messages. A specification alone, however, does not provide the maintained implementation, Software Development Kits (SDKs), and adapters needed for practical adoption. This paper presents OpenRoIS, a community-driven open-source middleware providing a concrete implementation of the RoIS Framework 2.0. It takes the position that an openly developed, paradigm-neutral implementation is what carries the standard from specification to practice. OpenRoIS contributes a recursive engine architecture in which a single engine class realizes the main and sub HRI Engine roles, an internal five-method component contract distinct from the five external RoIS interfaces, a mapping of those interfaces onto JSON-RPC 2.0 over WebSocket, a single-source-of-truth type pipeline that generates three consistent language stacks, TypeScript and C# client SDKs that include web and Unity support, and a Python adapter SDK that includes ROS 2 support. Through the common RoIS interfaces, a Service Application can address physical robots and virtual agents over the internet. All source code, interface types, and documentation are released under the Apache-2.0 license and openly developed at this https URL.
### Title:
          Multi-viewpoint Geo-localization with Event Cameras
 - **Authors:** Adam D. Hines, Michael Milford, Tobias Fischer
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robot localization is an ongoing challenge that demands mapping and positioning systems that are tolerant to viewpoint change. Event cameras are attracting increasing interest and adoption in robotics; however, dealing with viewpoint variance is an under-investigated problem in existing event-based localizers. In addition, event-based datasets that emphasize viewpoint variance for challenging localization situations are scarce. Here, we introduce an event-based visual place recognition (VPR) system that performs robustly under viewpoint changes. We converted five large-scale geo-tagged datasets, conventionally used to train frame-based localization systems, into synthetic event streams using Image-to-Event (I2E) conversion, and used them to fine-tune a pre-trained event-based vision transformer backbone with a multi-loss function, yielding a system we call MegaEvent that learns viewpoint-robust features for place recognition. We achieved an average Recall@1 of 82% across three existing event-based localization datasets, leading the next best event-based method by 20 recall points, and frame-based VPR models applied directly to event frames by 8 to 26 recall points. We introduce a new, challenging dataset - Springfield-Event-VPR - which features a 3.7km walking route recorded in three camera orientations for a total of 11.1km, which MegaEvent outperforms the strongest baseline by 9 recall points. The code for MegaEvent is available at this https URL.
### Title:
          Programming AMD XDNA NPUs with Open-source Compiler Tools: A FlashAttention Case Study
 - **Authors:** Erwei Wang, Ephrem Wu, Victor J. B. Jung, Jiajie Li, Andre Rosti, Joseph Melber, Samuel Bayliss
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spatial NPUs such as AMD XDNA place compute tiles beside small local memories and leave data movement between them to software. Mapping a multi-stage workload onto such a device is largely a question of where the intermediate tensors live. We report what we learned making those choices for FlashAttention with the open-source IRON and MLIR-AIR flows. We compare four reference designs on XDNA 1 and XDNA 2: one runs each operator separately, two stream between operators on chip, and one fuses all three attention stages into a single kernel. The fused kernel holds the $\boldsymbol{QK}^{\mathsf T}$ scores in compute-tile local memory and reduces partial results over the cascade interconnect, so the scores never return to shared MemTile memory. On XDNA 2, it reaches 3.62 TFLOP/s over complete end-to-end execution, twice the IRON design, with 5.3 to 7.2 times the energy efficiency of the integrated GPU on the same chip at 2K tokens and above. It covers twelve LLM configurations, from BERT to DeepSeek, up to 128K tokens. Roofline analysis at each memory level explains this result and shows when to stop. XDNA 1 has lower ridge points, so streaming on chip already reaches the compute-bound regime: the same fusion that doubles throughput on XDNA 2 is nearly wasted on XDNA 1. Comparing a mapping's operational intensity against each level's ridge point predicts which case applies before writing any code. Fuse until the mapping clears that ridge point, then stop. We release the reference designs as maintained open source.
### Title:
          LOInK: Learned Optimal Inverse Kinematics via Structured Neural Surrogate Models
 - **Authors:** Michael Somerfield, Damian Abood, Ruigang Wang, Ian R. Manchester
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Learned Optimal Inverse Kinematics (LOInK), a method to generate approximately optimal solutions to an inverse kinematics problem. When trained on data consisting of sampled configurations and associated task variables and a given cost function, LOInK learns a bi-Lipschitz invertible mapping from configuration space to a decoupled task/latent space, and moreover, the latent space is structured so as to place cost-minimizing solutions at the origin. This enables efficient sampling of cost-minimizing solutions via a network-inversion algorithm based on operator splitting. We demonstrate the proposed approach on three problems: an illustrative three degree-of-freedom manipulator problem; a quadrupedal climbing robot for which LOInK can generate near-optimal solutions on average 31 times faster and up to 100 times faster than a constrained optimization approach; and a simulated soft actuator as a purely data-driven example, in which LOInK can explicitly generate high-quality solutions, unlike existing generative approaches that require diverse sampling and evaluation of candidate solutions.
### Title:
          Locating and Enumerating Anycast: a Comparison of Two Approaches
 - **Authors:** Remi Hendriks, Tim Betzer, Ben Du, Raffaele Sommese, Mattijs Jonker, Roland van Rijswijk-Deij
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Anycast allows for providing services from multiple, geographically distant Points of Presence (PoPs), using a single IP address, to, e.g., improve resilience. Due to its opaqueness, it is often unknown which addresses are provisioned using anycast and, if so, where the PoPs are located. As anycast is widely used for critical Internet infrastructures (e.g., the DNS) efforts have been made to map anycast deployments. The current state-of-the-art mapping technique, iGreedy, relies on latency-based measurements, and is adversely affected by noise caused by, e.g., network processing delays. Previous work has shown that traceroute can alternatively be used to detect anycast. As traceroute reveals the hops a packet traverses, it may also be used to locate sites using geolocation data for hops near the anycast PoPs. This paper is the first to assess the performance of the traceroute-based approach at scale, by targeting 14k prefixes from an anycast census. Using ground truth we show traceroute achieves a slight increase in enumeration and geolocation precision over iGreedy. However, it suffers from overestimating the number of PoPs and incurs a 4 times increase in probing cost, making it unattractive for anycast censuses.
### Title:
          Brain API: An Intent-Aware Control Plane for Policy-Governed Agentic Systems
 - **Authors:** Alexander Chernov
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Contemporary cloud and distributed systems expose control through resource-centric abstractions: services, deployments, network flows, execution graphs. Agentic and tool-augmented systems have meanwhile shifted application logic toward intent-driven, adaptive execution. Existing control planes, workflow engines and service meshes lack abstractions for intent-level decision governance: they cannot represent high-level goals as first-class control objects, cannot enforce policy over the mapping from intent to execution plan, and cannot produce auditable records of why one execution path was chosen over its alternatives. Control logic is therefore embedded in application code, leaving systems brittle, opaque and hard to govern. We propose Brain API, an intent-aware control plane for policy-governed agentic systems. Its central contribution is the decision artifact: a durable, versioned, auditable record of how an intent became an executable plan, capturing which policies applied, which capabilities were evaluated, which alternatives were rejected, and why. A motivating use case is agentic datasets: datasets participating as policy-governed capabilities under residency, compliance and cost constraints. We evaluate a prototype of the decision layer against two external policy corpora we did not author. On the OPA Gatekeeper constraint library it agrees with the library's own published verdicts on 42 of 42 encodable cases, 19 admit and 23 deny. On Cedar example policies, labeled by differential testing against its reference implementation, a deliberately dissimilar domain exposed three defects in our model, including a default-allow assumption that would have inverted every authorization policy. The evaluation covers policy filtering and selection; context-signal and ranking remain design claims, and decision latency under load is unquantified.
### Title:
          Cube-Splat: High-Fidelity 360° Gaussian Splatting SLAM via Cubemap Factorization and Adjoint-Consistent Optimization
 - **Authors:** Xiangfei Guo, Hao Shi, Yufan Zhang, Zhonghua Yi, Yongqi Mao, Xiaoting Yin, Kaiwei Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent progress in 3D Gaussian Splatting (3DGS) has enabled dense visual SLAM with pinhole cameras, yet most pipelines are not designed for panoramic imagery. We present Cube-Splat, the first panoramic GS-SLAM framework that factorizes each 360° frame into a cubemap of four fixed-orientation virtual pinhole views sharing a single optical center. By designating the front face as the primary pose state, we accumulate gradients from all faces via an adjoint mapping, thereby enabling multi-face observations to coherently update a single state while strictly preserving cross-view geometric consistency. Concurrently, our mapping module densifies and optimizes anisotropic Gaussians using aggregated cubemap rays for high-fidelity, dense reconstruction. Furthermore, to rigorously evaluate panoramic SLAM under diverse and challenging conditions, we introduce SynPano, a highly scalable, photorealistic synthetic dataset featuring parameterized complex trajectories and multi-modal ground truth. Extensive evaluations on two public benchmarks (PALVIO and OmniBlender) and our SynPano dataset, collectively encompassing both indoor and outdoor scenes, demonstrate that Cube-Splat achieves state-of-the-art (SOTA) performance in tracking accuracy and reconstruction fidelity. Both the source code and the SynPano dataset are available at this https URL.
### Title:
          Consistent Relexicalization of Clinical Documents using Graph-Based Approach
 - **Authors:** Dipankar Das, Atri Mandal, Sandeep Singh, Tushar Shandhilya
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Relexicalization is a pivotal technique in clinical NLP, as it facilitates robust masking of sensitive information while synthesizing datasets that retain high-fidelity, real-world characteristics. However, preserving structural integrity, relational coherence, and temporal consistency during transformation remains a significant challenge. Existing approaches frequently rely on independent entity replacement, which results in clinical inconsistencies across longitudinal records. This reduces the value of such relexicalized datasets for downstream scientific analysis. To address these limitations, we introduce G-RELIC (Graph Based Contextual Relexicalization with Improved Consistency) which combines the power of LLMs with graphs. G-RELIC implements a graph-based mapping mechanism which optimizes for one-to-one correspondence between original and surrogate entities. It also introduces a deterministic temporal repositioning algorithm to preserve temporal consistency. Empirical evaluations on diverse, real-world clinical datasets validate that G-RELIC significantly outperforms state-of-the-art baselines. G-RELIC yields a 30.4 percentage point improvement in relational integrity (62.1% to 92.5%) and 45.9 percentage point improvement in temporal coherence (46% to 91.9%) without compromising on the recognized privacy benchmarks for clinical datasets. This maximizes the analytical utility of relexicalized datasets while minimizing re-identification risk.
### Title:
          A Scene Language Model for Open-Vocabulary Scene Mapping
 - **Authors:** Adam Lilja, Fabio Hübel, Siming He, Junsheng Fu, Claire Tomlin, Lars Hammarstrand, Jitendra Malik, Jonas Frey, Marco Pavone
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open-vocabulary 3D scene mapping aims to build a persistent representation of the objects in an environment. Existing systems typically rely on engineered mapping pipelines to associate observations, merge information across views, and maintain a consistent scene representation over time. Many additionally store feature-rich object representations, such as embeddings or image crops, increasing the size and complexity of the persistent memory. We introduce SceneLM, a Scene-Language Model that directly maintains a textual scene map. The full scene is represented as a structured text list of objects, which serves as the model's only persistent memory. For each input image, the model reads the current scene state and updates the map by adding, editing, and removing objects. To learn this behavior, we introduce supervision tasks for iterative scene map maintenance together with an automatic annotation pipeline that generates training data from images without human labels. We evaluate SceneLM on both a language-grounded retrieval benchmark and a localization benchmark. Across both benchmarks, the model produces a scene map that achieves competitive performance with complete mapping systems built from dedicated perception and geometric modules while producing a scene representation that is 6-12x more compact. We further show that SceneLM can be run online on an edge device through experiments on a quadruped. These results show that a persistent open-vocabulary 3D scene map can be maintained directly by a single vision-language model using only a lightweight text representation. Training and inference code is available on this https URL.
### Title:
          Adaptive World Memory 3D Foundation Model for Scalable 3D Mapping, Localization, and Rendering
 - **Authors:** Tianchen Deng, Guole Shen, Yilin Shen, Wenhua Wu, Yilin Fang, Ziqi Ma, Tianjun Zhang, Shenghai Yuan, Wolfram Burgard, Hesheng Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent 3D foundation models enable generalizable geometric reasoning from RGB images but remain limited in persistent memory, scalability, and renderable scene modeling. We present a memory-centric 3D foundation model for scalable robotic localization, reconstruction, and Gaussian rendering. Its core is an adaptive world memory mechanism that combines transformer-based gated updates with test-time temporal-spatial regulation. Learned gates control recurrent memory propagation, while temporal state evolution and spatial observation-state consistency regulate token-wise updates and forgetting over long image sequences. To support large-scale mapping, we organize memory into local submaps and integrate progressive mapping and tracking, loop closure, and SL(4)-based global refinement to maintain local accuracy and global consistency. A Gaussian reconstruction head decodes memory-enhanced features into renderable primitives, unifying camera pose estimation, dense point-cloud reconstruction, and photorealistic rendering within a single model. Experiments on public benchmarks and self-collected datasets from diverse robotic platforms demonstrate improved trajectory accuracy, reconstruction completeness, and rendering quality over existing 3D foundation reconstruction and SLAM baselines. These results support adaptive memory as a foundation for persistent robotic world modeling. The dataset and code will be made publicly available at \href{this https URL}{this https URL}.
### Title:
          2D GauSS-MI: Efficient Active Scene Reconstruction with Balanced Visual and Geometric Quality
 - **Authors:** Yuhan Xie, Jia Pan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Active reconstruction requires efficient active view selection to achieve high-quality reconstruction within limited onboard computational resources. Existing methods face challenges in adequately balancing visual and geometric quality with the computational efficiency required for real-time operation. In this work, we present an active reconstruction framework based on 2D Gaussian Splatting (2DGS). We develop an efficient online 2DGS mapping pipeline for incremental RGB-D observations and introduce a probabilistic reliability model that characterizes the view-dependent reconstruction quality of individual 2D Gaussian splats. Building on this model, we formulate 2D Gaussian Splatting Shannon Mutual Information (2D GauSS-MI), a mutual-information-based metric that exploits the explicit surface orientation of 2DGS to evaluate the expected information gain of candidate views. The proposed metric enables active view selection to account for both visual and geometric reconstruction quality. We evaluate the proposed system against three state-of-the-art baselines on eight Replica scenes. Experimental results demonstrate that our method achieves a favorable balance between visual and geometric reconstruction quality with substantially lower computational cost and competitive model storage.
### Title:
          Open Platform Field Experiments: Expanding the Design Space of Experimental Research on Social Media
 - **Authors:** Jordi Guillem Condom-Tibau, Giovanni Puccetti, Clara Bacciu, Matteo Abrate, Stefano Cresci
 - **Subjects:** Subjects:
Computers and Society (cs.CY); Human-Computer Interaction (cs.HC); Social and Information Networks (cs.SI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite a growing demand for causal evidence about social media, independent researchers remain severely constrained in their ability to conduct experiments directly on online platforms. To cope, multiple methodological workarounds have emerged - from controlled surveys and simulations to client-side overlays and platform partnerships - each requiring distinct trade-offs between desirable experimental properties. The recent emergence of open social media platforms offers a qualitatively different methodological opportunity. Here we propose a design space of social media experimentation and discuss Open Platform Field Experiments (OPFEs). OPFEs represent a distinct class of experimental approaches that enable independent researchers to directly intervene on functional platform components - such as clients, recommendation systems, and moderation services - within live social media environments. Through a comparative analysis of experimental archetypes, we show that OPFEs occupy a previously unexplored region of the design space. We then bridge theory and practice by characterizing the architectural and governance elements that enable OPFEs, mapping them onto Bluesky and the AT Protocol, and illustrating the end-to-end lifecycle of a complete OPFE design. Overall, this work establishes OPFEs as a practical methodological paradigm for independent, transparent, and ecologically grounded experimentation on open social media.
### Title:
          A Sim-to-Real Integration Pipeline for Training and Deployment of Chunk-Based VLA Manipulation Policies
 - **Authors:** Mathilde Kappel, Clémence Grislain, Mohamed Chetouani, Olivier Sigaud, Louis Annabi, Fa\"ız Ben Amar, Stéphane Doncieux, Mahdi Khoramshahi
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models have become a prominent paradigm for mapping multimodal inputs, including semantic instructions, visual observations of the scene, and proprioceptive observations, to robot actions. Most state-of-the-art models predict actions in the end-effector pose space as sequences of action chunks. Training and evaluating these models requires large-scale collections of real-world demonstrations, pairing robot actions with the corresponding visual and proprioceptive observations. Collecting such data on real hardware typically relies on human teleoperation, making the process costly, time-consuming, and difficult to scale. We present an open-source sim-to-real experimental protocol that addresses this bottleneck: expert trajectories generated in simulation are replayed open-loop on a real Franka FR3 setup, where the corresponding real visual and proprioceptive observations are recorded and converted into a format compatible with VLA training. The same deployment stack is then reused, in closed-loop, to evaluate a trained policy on that setup, so that data collection and evaluation share an identical hardware configuration. Because each real recording is paired with the simulated trajectory that produced it, the protocol also yields a direct measurement of the sim-to-real gap. We release the collected datasets on Hugging Face together with the pipeline source code this https URL.
### Title:
          PopNavShift: Stress-Testing Social Navigation under Behavioral Population Shift
 - **Authors:** Kaizhen Tan, Diyu Zheng, Tim Guangyu Wu, ChengHe Guan
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Social-navigation algorithms are often evaluated under a fixed pedestrian-behavior distribution, despite substantial variation in pedestrian responses to robots across individuals and social contexts. We introduce PopNavShift, a matched simulation framework for stress-testing social-navigation strategies under pedestrian population shifts. PopNavShift constructs population-conditioned pedestrian motion profiles by prompting Gemini 3.7 Flash with 600 synthetic persona records from MatrAIx Persona 1M and deterministically mapping the responses into bounded motion parameters. It then compares three representative navigation strategies, reactive avoidance, early yielding, and reciprocal collision avoidance, across eight population conditions and 7,488 matched robot runs. In a matched intervention on the same 202 personas, changing only time pressure reverses 8.6% of controller rankings based on robot travel time, but 22.4% based on mean pedestrian delay and 23.9% based on worst-decile delay. Across population conditions, this sensitivity is greater for pedestrian burden than for robot travel time and increases in spatially constrained settings; the same qualitative pattern persists under a second pedestrian dynamics model. These findings support evaluating navigation strategies across behavioral populations using both robot performance and pedestrian burden.
### Title:
          Catena: A Comprehensive Software Suite for Large-Scale Connectomics
 - **Authors:** Samia Mohinta, Pedro Gómez-Gálvez, Shi Yan Lee, Daniel Franco-Barranco, Michael Clayton, Stephan Preibisch, Jan Funke, Albert Cardona
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The gold standard datasets for mapping connectomes are electron microscopy volumes of densely labeled neural tissue at nanometer resolution. Yet reconstructing and proofreading neuronal arbors and annotating all synapses requires pipelining multiple software tools that are often fragmented, inconsistently maintained, or proprietary, hindering reproducibility and automation. Here, we introduce Catena, an open-source, comprehensive, developer-centric software suite for connectomics that integrates modules for 3D neuron and organelle segmentation, synapse detection, microtubule tracking, and neurotransmitter inference. Catena organizes its modules in composable, chunk-wise processing pipelines in a completely documented, extensible, and adaptable design. We further reduce compute and ground-truth data requirements with pretrained machine learning models, facilitating fine-tuning. Catena ships fully containerized modules that encapsulate evolving dependencies for consistent execution across workstations and clusters. By consolidating open components, shareable models, and containerized runtimes, Catena delivers a reproducible and scalable approach to mapping cellular connectomes from electron microscopy volumes. Code and documentation: this https URL
## Keyword: localization
### Title:
          TAPe+ML: A Compact Structured Representation for Multi-Task Computer Vision
 - **Authors:** Sergey Kurinov (1), Alexey Upatov (1) ((1) Comexp Research Lab, TAPe + ML Project, Nizhniy Novgorod, Russia)
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present TAPe+ML v3, a compact computer vision system based on TAPe (Theory of Active Perception), a structured representation that encodes relations among perceptual elements before recognition. Instead of operating directly on pixel tensors, the system uses a shared TAPe representation and a modular recognition architecture for image classification, object detection, and instance segmentation. TAPe+ML v3 combines background and contour processing, local object localization, prototype-based classification, and a coordinator for specialized submodels. Across the reported experiments, it uses fewer than 100,000 parameters. On COCO object detection, it obtains 84.7 mAP50 and 65.3 mAP50-95. On COCO instance segmentation, it obtains 80.7 mask mAP50 and 58.4 mask mAP50-95. In classification experiments, it reaches 92 percent validation accuracy on Imagenette under an identical-training comparison with a raw-pixel baseline, and 89.9 percent Top-1 accuracy on ImageNet-Real. We also evaluate compactness in video scene detection and adaptation under distribution shift in an industrial pilot. The results suggest that shifting part of the modeling burden from network parameters to a structured input representation can support compact multi-task vision systems with reduced data, memory, and compute requirements.
### Title:
          Towards Effective Visual-Inertial SLAM with Passive-Only Sensors for Low-Cost Autonomous Underwater Vehicles
 - **Authors:** Grant Schwidder, David Widhalm, Junaed Sattar
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Improvements to Visual-Inertial Simultaneous Localization and Mapping (VI-SLAM) for low-cost autonomous underwater vehicles (AUVs) are critical for transitioning advanced marine robotics from specialized labs to broader research and hobbyist applications. While high-end AUVs typically rely on expensive sensor suites - such as Doppler Velocity Logs (DVLs) and Ultra-Short Baseline (USBL) systems - this work demonstrates that robust, high-quality navigation is achievable using a sub-$10, 000(USD) platform equipped only with inexpensive consumer-grade sensors. By leveraging a similarly priced, open-source AUV, we evaluate the performance of stereo cameras, Micro-electromechanical System (MEMS)-based IMUs, and depth sensors in a fully unconstrained 6-degree-of-freedom (6-DOF) underwater environment. We analyze the efficacy of off-the-shelf SLAM packages and propose optimizations for sensor fusion to mitigate the visual and physical challenges of untethered underwater operation. Our results prove that a usable SLAM solution can be accessible to the masses, providing a benchmark for expectations in demanding, real-time maritime missions without the financial barrier of industrial-grade hardware.
### Title:
          MAPLE-RF: Efficient Probabilistic RF Source Localization in Partially Explored Environments
 - **Authors:** Haozhe Lei, Sundeep Rangan
 - **Subjects:** Subjects:
Robotics (cs.RO); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Localizing a radio-frequency (RF) transmitter from received signals often requires a model of the environment to predict how obstacles block and reflect the signal. In many robotic applications, however, only a partial map is available, particularly when a robot localizes the source while exploring with simultaneous localization and mapping (SLAM). We study single-snapshot transmitter localization on such partially explored maps and compare two approaches that output a posterior over transmitter locations. The first extends a digital-twin method, which ray-traces every candidate location, to partial maps by treating unexplored space as free and training on mixed map coverage. The second, MAPLE-RF, encodes estimated path angles of arrival and signal-to-noise ratios as grid channels aligned with map knownness, occupancy, and line-of-sight visibility, and a U-Net scores all candidate positions in one pass without simulating propagation at inference. Ray-tracing simulations of indoor environments indicate that training on mixed map coverage is essential for both approaches. The digital-twin approach is more accurate on most single-snapshot metrics, while MAPLE-RF comes close at a query cost that does not depend on the propagation model and is more than two orders of magnitude below a fresh full-grid query with general-purpose ray tracing. Both outperform Gaussian and Gaussian-mixture baselines, and on exploration routes guided by its own estimates, fused MAPLE-RF posteriors place more probability near the source than the compared methods. Code and data will be released.
### Title:
          Visual Navigation Transformer with Pose Attention
 - **Authors:** Beiming Li, Jaime Romero, Jonathan Diller, Vijay Kumar, Alejandro Ribeiro
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learned navigation policies typically consume observations as a temporally ordered history, with positional encodings tying each observation to when it was seen, making it difficult to reuse experience from earlier traversals of an environment. Systems that do reuse such experience usually construct an explicit representation, such as a map or a topological graph, and plan on it. We propose VNT-PA (Visual Navigation Transformer with Pose Attention), a transformer planner whose context is a set of depth keyframes indexed by camera pose. With camera poses as positional encoding, attention depends on the pose differences between keyframes rather than on their temporal order. VNT-PA is trained to imitate a shortest-path planner operating on the ground-truth scene mesh, predicting actions by querying the spatial context with only its current pose and the goal position. On point-goal navigation in HM3D validation scenes, VNT-PA reaches 93.3% success and 90.4% success weighted by path length (SPL), outperforming baselines that encode the same context as a temporal sequence or treat pose as an input feature, in both navigation performance and training efficiency. Because the spatial context is a pose-indexed set, frames from different trajectories can be fused at test time. The planner also degrades more gracefully under localization noise than a conventional baseline which plans on explicit maps. These results show that pose-stamped experience can serve directly as the environment representation for a learned planner, and that making attention depend on pose differences, rather than on temporal order, speeds up training and improves long-horizon navigation.
### Title:
          Multi-viewpoint Geo-localization with Event Cameras
 - **Authors:** Adam D. Hines, Michael Milford, Tobias Fischer
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robot localization is an ongoing challenge that demands mapping and positioning systems that are tolerant to viewpoint change. Event cameras are attracting increasing interest and adoption in robotics; however, dealing with viewpoint variance is an under-investigated problem in existing event-based localizers. In addition, event-based datasets that emphasize viewpoint variance for challenging localization situations are scarce. Here, we introduce an event-based visual place recognition (VPR) system that performs robustly under viewpoint changes. We converted five large-scale geo-tagged datasets, conventionally used to train frame-based localization systems, into synthetic event streams using Image-to-Event (I2E) conversion, and used them to fine-tune a pre-trained event-based vision transformer backbone with a multi-loss function, yielding a system we call MegaEvent that learns viewpoint-robust features for place recognition. We achieved an average Recall@1 of 82% across three existing event-based localization datasets, leading the next best event-based method by 20 recall points, and frame-based VPR models applied directly to event frames by 8 to 26 recall points. We introduce a new, challenging dataset - Springfield-Event-VPR - which features a 3.7km walking route recorded in three camera orientations for a total of 11.1km, which MegaEvent outperforms the strongest baseline by 9 recall points. The code for MegaEvent is available at this https URL.
### Title:
          The EventCV Library for Event-Based Robotic Vision
 - **Authors:** Adam D. Hines, Michael Milford, Tobias Fischer
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Event cameras detect per-pixel brightness changes asynchronously on microsecond timescales, with high dynamic range and low power draw. These are desirable properties for robots that move fast or work in difficult lighting conditions. However, integrating an event camera into a real-world robotic pipeline still requires substantial effort: plug-and-play drivers do not exist, event streams are recorded in a variety of incompatible file formats, and most projects rely on custom research-grade code. Here, we present EventCV, an open-source and extensible Rust library with OpenCV-style Python bindings that lowers the entry barrier to working with event cameras. EventCV provides a wide range of features: denoising filters and geometric transforms, augmentations, corner detection and unsupervised feature learning, contrast-maximization motion estimation, a video-to-events simulator, and Open Neural Network Exchange (ONNX) inference for deployment in robotic stacks. EventCV integrates the Neuromorphic Drivers package, allowing an event camera stream to be processed directly in real time. No existing toolkit covers this range of operations in one package, and EventCV builds representations and decodes files 1.1x to 3.7x faster than the currently available libraries. We deploy EventCV on a Jetson Orin AGX and present three robotics case studies spanning object detection, on-device model inference, and localization. Project webpage: this https URL.
### Title:
          ProTracer: Proprioception-Guided Failure Diagnosis in Robot Manipulation
 - **Authors:** Chang Dong, Mehdi Hosseinzadeh, King Hang Wong, Lingqiao Liu, Francois Fraysse, Feras Dayoub, Minh Hoai Nguyen
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a comprehensive framework for robot manipulation failure analysis that includes binary failure detection, failure categorization, explanation generation, and the additional capability of failure onset localization, which aims to identify the earliest moment at which a robot execution deviates from a valid task-completion trajectory and is ultimately followed by task failure. To address these tasks, we propose ProTracer, a training-free framework that leverages existing Vision-Language Models (VLMs) together with proprioceptive signals for failure analysis. Our method uses proprioceptive dynamics to identify temporally informative action boundaries and converts richer robot-state signals into structured natural-language descriptions that can be jointly analyzed together with visual observations by the VLM. This design combines the temporal precision of proprioceptive signals with the multimodal reasoning capabilities of modern VLMs without requiring additional model training. We further introduce FailTime, a benchmark with synchronized visual and proprioceptive observations for evaluating conventional failure diagnosis tasks as well as failure onset localization. Experiments demonstrate that ProTracer achieves strong performance across both conventional failure diagnosis tasks and the newly introduced failure onset localization task, highlighting the importance of proprioceptive reasoning for fine-grained temporal failure analysis.
### Title:
          A Scene Language Model for Open-Vocabulary Scene Mapping
 - **Authors:** Adam Lilja, Fabio Hübel, Siming He, Junsheng Fu, Claire Tomlin, Lars Hammarstrand, Jitendra Malik, Jonas Frey, Marco Pavone
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open-vocabulary 3D scene mapping aims to build a persistent representation of the objects in an environment. Existing systems typically rely on engineered mapping pipelines to associate observations, merge information across views, and maintain a consistent scene representation over time. Many additionally store feature-rich object representations, such as embeddings or image crops, increasing the size and complexity of the persistent memory. We introduce SceneLM, a Scene-Language Model that directly maintains a textual scene map. The full scene is represented as a structured text list of objects, which serves as the model's only persistent memory. For each input image, the model reads the current scene state and updates the map by adding, editing, and removing objects. To learn this behavior, we introduce supervision tasks for iterative scene map maintenance together with an automatic annotation pipeline that generates training data from images without human labels. We evaluate SceneLM on both a language-grounded retrieval benchmark and a localization benchmark. Across both benchmarks, the model produces a scene map that achieves competitive performance with complete mapping systems built from dedicated perception and geometric modules while producing a scene representation that is 6-12x more compact. We further show that SceneLM can be run online on an edge device through experiments on a quadruped. These results show that a persistent open-vocabulary 3D scene map can be maintained directly by a single vision-language model using only a lightweight text representation. Training and inference code is available on this https URL.
### Title:
          SIRA: Reasoning-Aware Surgical Instrument Segmentation via Query-Anchored Alignment
 - **Authors:** Zhibo Zhang, Qijie Wang, Zengqiang Yan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Surgical instrument segmentation (SIS) plays a critical role in robotic assistance and surgical workflow analysis. However, most existing SIS methods formulate segmentation as a category-driven localization problem, limiting their ability to capture procedural context and task-dependent semantics in surgical workflows. We introduce Reasoning-Aware Surgical Instrument Segmentation (RA-SIS), a task formulation that frames segmentation as query-conditioned inference under surgical context. To benchmark this setting, we construct SurgRS, a surgical reasoning segmentation dataset consisting of 41,000 image-text pairs, which aligns instance-level masks with structured query-answer supervision to enable semantic grounding at the pixel level. Based on SurgRS, we propose Surgical Instrument Reasoning and Segmentation Assistant (SIRA), a multimodal framework that disentangles target-level and query-level semantics and integrates them with visual features through query-anchored dual alignment. By aligning query semantics with spatial features and segmentation prompts, SIRA enhances semantic-visual consistency in mask prediction. Extensive experiments on SurgRS demonstrate improvements over existing reasoning-aware baselines. Code is available at this https URL.
### Title:
          PSEE: Progressive Sensor Event Expansion for Point-Supervised Temporal Action Localization
 - **Authors:** Jiaxi Yin, Ge Wang, Han Ding, Fei Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Temporal action localization (TAL) in wearable sensor streams identifies action classes and temporal boundaries, enabling finer-grained activity understanding than conventional action recognition. However, training typically requires costly start--end annotations for every action instance. To reduce this burden, we study point-supervised TAL, where each instance is labeled with only one timestamp and its class. We propose Progressive Sensor Event Expansion (PSEE), which combines semantic activations, sensor-specific transition evidence, and adaptive temporal ownership to recover point-supervised pseudo segments. These segments supervise standard TAL detectors without modifying their inference procedures. Cross-subject experiments on four inertial-sensing benchmarks demonstrate improved pseudo-boundary quality over adapted point-supervised baselines, compatibility with different TAL detectors, and robustness to point sampling. Code is available at this https URL.
### Title:
          Adaptive World Memory 3D Foundation Model for Scalable 3D Mapping, Localization, and Rendering
 - **Authors:** Tianchen Deng, Guole Shen, Yilin Shen, Wenhua Wu, Yilin Fang, Ziqi Ma, Tianjun Zhang, Shenghai Yuan, Wolfram Burgard, Hesheng Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent 3D foundation models enable generalizable geometric reasoning from RGB images but remain limited in persistent memory, scalability, and renderable scene modeling. We present a memory-centric 3D foundation model for scalable robotic localization, reconstruction, and Gaussian rendering. Its core is an adaptive world memory mechanism that combines transformer-based gated updates with test-time temporal-spatial regulation. Learned gates control recurrent memory propagation, while temporal state evolution and spatial observation-state consistency regulate token-wise updates and forgetting over long image sequences. To support large-scale mapping, we organize memory into local submaps and integrate progressive mapping and tracking, loop closure, and SL(4)-based global refinement to maintain local accuracy and global consistency. A Gaussian reconstruction head decodes memory-enhanced features into renderable primitives, unifying camera pose estimation, dense point-cloud reconstruction, and photorealistic rendering within a single model. Experiments on public benchmarks and self-collected datasets from diverse robotic platforms demonstrate improved trajectory accuracy, reconstruction completeness, and rendering quality over existing 3D foundation reconstruction and SLAM baselines. These results support adaptive memory as a foundation for persistent robotic world modeling. The dataset and code will be made publicly available at \href{this https URL}{this https URL}.
### Title:
          World Modeling in Transformers
 - **Authors:** Pierre Beckmann, Matthieu Queloz, Andre Freitas
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Behavioral failures can make a transformer appear to lack a world model even when it has learned faithful representations of its environment. We demonstrate this in TaxiGPT, a transformer trained on random walks through Manhattan whose failures have been interpreted as evidence of an incoherent internal map. Through mechanistic analysis and causal interventions, we show that the model represents intersections and streets, tracks its position, and uses a goal compass to navigate. We trace its failures to interference between superposed intersection features, which disrupts localization within the internal map. Affordance packing, which groups representations of intersections with the same legal moves, helps limit the consequences of these errors. Finally, we propose mechanistic indicators that we use to compare models and show that world-modeling capacities emerge at different stages of training. Our findings motivate a shift from asking whether a model has a world model to mechanistically studying its world modeling: the interacting capacities through which it represents its environment and uses those representations to guide behavior.
### Title:
          AcousticDiffusion: Semantically Conditioned Audio-Guided Diffusion Policy for Search-and-Rescue Assistance
 - **Authors:** Iana Zhura, Didar Seyidov, Dmitrii Plotnikov, Hajira Amjad, Miguel Altamirano Cabrera, Dzmitry Tsetserukou
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Navigating toward human callers is an important capability for rescue robots operating where visual contact is degraded or occluded. We present AcousticDiffusion, a semantically conditioned, audio-guided diffusion policy for human-directed navigation. A frozen pretrained audio recognizer processes 10.24 s windows, with speech gating and distress-aware prioritization converting recognition outputs into source-level navigation roles. Microphone-array direction-of-arrival measurements are recursively integrated into a robot-centric Bayesian bird's-eye-view belief field. Ego-motion compensation aligns successive observations, progressively constraining source position while preserving bearing-induced range uncertainty. The semantic belief, recent acoustic observations, audio features, and robot state condition a diffusion model that generates waypoint trajectories. On a synthetic-navigation validation set using recorded audio, AcousticDiffusion achieves a mean end-point bearing error of 11.20 degrees, with 91.78% of trajectories aligned within 30 degrees of the caller. Distractor rejection ranges from 89.20% to 98.99%, and the policy favors a HELP-designated caller over a competing speaker in 91.07% of windows. Deployed online on a ZSL-1 quadruped without additional retraining, it achieves a mean bearing error of 64.9 degrees, compared with 98.2 degrees for A* and 90.4 degrees for RRT, with a mean planner compute time of 6.07 ms. Despite imperfect acoustic localization, the reported mean final source distance is reduced from 3.96 m for the classical planners using ODAS-derived (Open embedded Audition System) guidance to 2.48 m, a 37.4% improvement. These results demonstrate the framework's ability to translate uncertain acoustic observations into closer approaches to human callers.
### Title:
          VideoReloc: Long-Term Indoor Video Relocalization against a Kilobyte-Scale Semantic Scene Graph
 - **Authors:** Qianru Li, Xuyang Chen, Xuqin Wang, Zhenghao Zhang, Hongyi Luo, Tao Wu, Daniel Cremers, Lu Liu, Yanfeng Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Given a compact semantic scene graph, long-term indoor video relocalization estimates a map-frame trajectory after lighting and furniture changes. Visual methods rely on appearance and become unreliable under these changes; localizing one frame at a time from object classes and geometry instead leaves sparse, ambiguous evidence. We introduce VideoReloc, whose adaptive clips use odometry to gather spatial evidence until object and motion criteria are met, adapting query length to the observed scene. Its run-level decision rechecks conflicting placements using evidence accumulated across connected clips, stabilizing the trajectory beyond adjacent-clip tracking. Hypothesis-first registration proposes poses from object triplets and verifies each using clip-wide object centers and box surfaces. Orientation-aware refinement uses box faces, gravity and wall directions to resolve ambiguity in camera orientation and refine the full pose. This reframes sparse-map relocalization as verification of spatially extended video queries, moving discriminative support from stored appearance to temporal context and permitting a 100 kB map of class-labelled boxes. On RIO10 and ReplicaCAD, the all-frame localization success rate at 1 m/10$^\circ$ is 73.5% and 61.1% under causal evaluation, rising to 90.6% and 74.8% with clip closure. The evaluated per-frame scene coordinate regressors reach up to 47.6% and 49.8%, respectively, with maps of 12.6-42 MB. Project page: this https URL
### Title:
          Reusing Latent Speech Representations for Query-Conditioned Topic Localization in Transcripts
 - **Authors:** Steffen Freisinger, Philipp Seeberger, Thomas Ranzenberger, Tobias Bocklet, Korbinian Riedhammer
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long transcripts are costly inputs for downstream NLP systems and often contain irrelevant context. We study query-conditioned topic localization: predicting the sentence span in a transcript that best addresses a topic-title query. To improve span localization, we reuse ASR encoder states as sentence-level representations and fuse them with textual embeddings. This lets lightweight span locators exploit speech information without running a separate audio encoder. Experiments on two public datasets show consistent gains over text-only baselines, especially under strict boundary-matching criteria. Cross-dataset experiments further indicate that the benefits are strongest for structured or semi-structured speech, while gains on spontaneous speech are limited and mixed.
## Keyword: transformer
### Title:
          Reviser: Revision-Capable Text Generation via Autoregressive Cursor Actions
 - **Authors:** Sean Diab
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Revision-capable generation is appealing because it can insert or revise earlier content, but many non-autoregressive and edit-based approaches obtain this flexibility through repeated sequence-level computation. We propose Reviser, a decoder-only Transformer that generates a response as a sequence of cursor-relative actions on a mutable canvas. At each step, Reviser predicts exactly one action token: INSERT(token), MOVE($\Delta$), or STOP, and is autoregressive over edit-history actions rather than final text order. This design enables genuinely non-monotonic generation while preserving a simple next-action interface. On a continuation benchmark, Reviser is strongly preferred to SEDD and MDLM in our arena evaluations, and trajectory statistics confirm that the model performs frequent backward moves and mid-canvas insertions rather than merely emulating end-append decoding. Against size-matched autoregressive baselines, Reviser is competitive at both the 100M and 300M scales. Under our shared FLOPs convention, Reviser also requires substantially less inference compute than representative multi-pass refinement and diffusion-style baselines.
### Title:
          Composer2Vec: A Continuous Embedding Space of Composer Style Learned from Symbolic Melody Generation
 - **Authors:** Sakutaro Nishio, Osamu Ichikawa
 - **Subjects:** Subjects:
Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We analyze the composer embeddings learned by a composer-conditioned Transformer as a continuous latent space of compositional style, rather than merely as an internal representation for generation. A model that recursively predicts melody continuations was trained on melodic sequences extracted from MIDI data, conditioned on composer identity (124 composers). Principal component analysis of the learned composer embedding matrix (124x128) shows that the first principal component correlates strongly with composer birth year (r = -0.884, p < 0.001, n = 123), a stronger correlation than we obtain by applying the same PC1-birth-year analysis to existing general-purpose audio-text embeddings (CLAP, MuQ-MuLan) trained on unrelated audio-text corpora, not on symbolic melody generation. A shuffle test (2,000 permutations) confirms that the Silhouette score for stylistic-period labels is statistically significant (0.0110, p < 0.001). We further show that vector arithmetic in the embedding space captures meaningful stylistic relationships between composers. These results suggest that composer embeddings, learned without supervision beyond composer identity, form an interpretable latent space that captures musical-historical structure.
### Title:
          Do Quantum Models Scale Like LLMs?
 - **Authors:** David S. Berman, Ying-Jer Kao, Roger G. Melko, Alexander G. Stapleton
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Quantum Physics (quant-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this work, we study the neural scaling laws of RydbergGPT, an autoregressive transformer model trained on qubit projective measurement data gathered from interacting Rydberg atom arrays. The quantum system is known to exhibit a finite-size remnant of a critical point as the laser detuning parameter is varied. We find that near the critical point the transformer loss as a function of training dataset size is well described by a power-law with a loss floor correction. However, away from criticality the quality of the power-law description is substantially reduced. We then compare the statistical structure of both Rydberg measurements and natural-language corpora using an entropy-normalised, finite sample corrected mutual information "two-point" function. We find that near-critical statistics of the two point functions are closest to those observed in natural-language, whilst other qubit configurations far from the critical point have two-point functions that decay more rapidly. This supports the hypothesis that multi-scale dependence contributes to stable neural scaling, and that scaling behaviour should be viewed as a property of the model-data pair.
### Title:
          Attention-Aware Routing: Coupling Routing and Attention in MoEs
 - **Authors:** Despoina Kosmopoulou, Anastasios Tsetsilas, Efthymios Georgiou, Giannis Karamanolakis, Swastik Roy, Alexandros Potamianos
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In Mixture-of-Experts language models, the router typically selects and weights experts based on the token's hidden state, utilizing limited contextual information. We propose Attention-Aware Routing (AAR), which augments the router with temporal and spectral features extracted from a sliding window of attention weights that represent a summary of the model's contextual state, disentangled from the hidden state. Keeping the base transformer entirely frozen, we train only the routing parameters, isolating routing as the sole variable. AAR improves GSM8K by +3.37 pp over a routing-only SFT baseline on OLMoE. Beyond performance, we show that routing and attention form a coupled circuit: routing changes at layer l propagate through the residual stream to amplify attention sinks at layer l+1, reshaping attention without any direct update to the attention mechanism itself. Further, AAR reduces long diverging generation, with incorrect answers getting shorter, while correct answers remain unchanged in length. Finally, AAR is strongly depth-sensitive: applying it indiscriminately across layers can degrade factual retrieval, whereas mathematical reasoning gains persist when it is introduced deeper in the network. This sensitivity exposes a retrieval--reasoning tension across depth and makes layer-selective AAR a controlled probe of the routing-relevant information carried by attention at different layers.
### Title:
          ForeTac-VLA: A Forecasting-Based Tactile-Vision-Language-Action Model for Contact-Rich Robotic Manipulation
 - **Authors:** Zhengyu Tao, Xin Li, Xin Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language-action (VLA) models have demonstrated strong capabilities in robotic manipulation, yet their reliance on visual perception limits robustness in contact-rich environments, where critical physical interaction states may not be visually observable. Existing tactile-enhanced VLA methods improve physical grounding using observed tactile feedback, but most remain largely reactive rather than explicitly modeling how contact may evolve. Therefore, we propose ForeTac-VLA, a forecasting-based tactile-vision-language fusion model that predicts future tactile states to guide action generation. Specifically, ForeTac-VLA encodes recent tactile observations into temporal representations and integrates them with vision-language features through bidirectional cross-attention. Further, a transformer-based forecasting module predicts multi-step future tactile states, enabling the model to reason jointly over observed and anticipated contact. Finally, the fused multimodal representations and predicted future tactile states are fed into the VLA backbone to condition action generation. To stabilize training, a ground-truth-to-prediction curriculum is employed when early forecasts are unreliable. Across four real-world contact-rich manipulation tasks, ForeTac-VLA achieves an average success rate of 95%, outperforming the fine-tuned VLA model by 36.25 percentage points and state-of-the-art tactile-enhanced VLA baselines by over 22 percentage points. ForeTac-VLA also maintains strong performance under low-illumination and visually cluttered conditions. Video demonstrations can be found on this https URL
### Title:
          From Stress to Affect: Multimodal Deep Learning for Physiological Emotion Recognition Across Wearable Sensor Modalities
 - **Authors:** Desta Haileselassie Hagos, Saurav Keshari Aryal, Legand L. Burge
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Physiological emotion recognition using wearable sensors has important applications in mental health monitoring, affective computing, and human-computer interaction. However, existing studies typically evaluate a single model, sensing configuration, or dataset, limiting our understanding of how these factors influence recognition performance. We present a comparative study of temporal deep learning architectures for physiological emotion recognition using two multimodal wearable datasets: WESAD and EmoWear. Bidirectional long short-term memory (LSTM), temporal convolutional network (TCN), and Transformer models are evaluated under wrist-only, chest-only, and multimodal sensing configurations using participant-independent leave-one-subject-out cross-validation (LOSO-CV). We also investigate soft-voting ensembles, sensor ablation, sampling frequency, and gradient-based saliency. The Transformer achieved the highest multimodal accuracy on WESAD (99.02% +/- 0.51%), whereas the LSTM achieved the best multimodal accuracy on EmoWear for both arousal (91.80% +/- 1.06%) and valence (89.96% +/- 0.36%). These results show that relative architecture performance depends on dataset characteristics rather than one architecture being uniformly superior. Multimodal sensing consistently outperformed wrist-only and chest-only configurations across both datasets. Sampling-frequency analysis showed that 4 Hz provides a practical operating point, with performance comparable to higher frequencies at substantially lower training cost. These findings provide guidance for selecting architectures, sensing modalities, and sampling frequencies for wearable physiological emotion recognition.
### Title:
          MOSAIC-SR: Transformer-Guided Symbolic Regression for Scientific Equation Recovery
 - **Authors:** Peiyi Zheng, Yanming Kang, Hans De Sterck, Giang Tran
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Symbolic regression aims to recover closed-form equations from observations, providing interpretable models for scientific discovery. Existing approaches struggle to combine flexible structural search with efficient inference. Search-based methods can refine expression structure but often rely on costly combinatorial optimization with random initialization. Pretrained neural models generate formulas almost instantly, but their predictions often contain symbolic errors. We introduce MOSAIC-SR, which uses a pretrained Transformer to propose multiple initial sketches. These sketches initialize searches in several promising regions, avoiding random starts in the vast expression space. Each search jointly recovers structure and constants through scale-aware constant optimization and local symbolic repair. We evaluate MOSAIC-SR on the SRSD-Feynman dataset with and without dummy variables and on six additional benchmarks. MOSAIC-SR obtains the highest symbolic solution rate on every dataset while ranking among the top two methods in predictive accuracy. This advantage persists in the presence of irrelevant dummy inputs. The results show that learned priors can focus search on promising equation structures, and that numerical optimization and symbolic repair are important for recovery.
### Title:
          Fragment-Aware Vision Transformers for Fresco-Fragment Style Classification
 - **Authors:** Sara Miketek, Biagio Barchielli, Nadeem Iqbal Kajla, Sinem Aslan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Artistic style classification is usually studied on complete artworks, where models can exploit global composition, spatial organisation, and iconographic structure. In archaeological settings, however, artworks often survive only as fragmented remains, forcing recognition from incomplete, irregular, and context-limited visual evidence. We study fresco-fragment style classification using a progressive transformer-based framework. Starting from a ViT-B/16 baseline, we introduce foreground-guided masking to suppress background-only tokens, inpainting-based geometric regularisation to align irregular fragment supports with the ViT patch grid, and a supervised contrastive objective that operates on predictive distributions through a Kullback-Leibler similarity and consistently improves every branch. We combine the branches with a deliberately simple learnable logit ensemble. Experiments on CLEOPATRA and POMPAAF show that fragment-aware modelling improves over the standard ViT baseline, with the ensemble increasing accuracy from 0.604 to 0.656 and macro-F1 from 0.596 to 0.648 on CLEOPATRA, and outperforming the best single branch in four of six fragmentation settings on POMPAAF. We additionally evaluate a more complex graph-fusion variant and find that it matches the simple ensemble on POMPAAF while offering only a small, dataset-specific gain on CLEOPATRA, which does not justify its added complexity. Beyond these empirical gains, our contribution is twofold: a distribution-level contrastive objective that consistently sharpens single-branch recognition, and an interpretability analysis that verifies the models exploit genuine painted evidence, while quantifying that the inpainting-based branch draws part of its attribution from the synthesised surround.
### Title:
          A Lightweight Plug-in Gate for Transformer-Based Time-Series Forecasters
 - **Authors:** Hongkai Zhuang, Tao Huang, Chen Hou
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Covariate-rich time-series forecasting requires deciding how external variables enter the target forecasting path. Existing Transformer-based forecasters usually build a covariate representation and pass it to the encoder without an explicit admission stage. This paper studies pre-encoder covariate admission as an input-side interface that regulates that representation immediately before encoder processing. We implement the interface with a lightweight representation-level pre-encoder gate that assigns sigmoid scores to representation units, and we also study a usage-regularized variant that penalizes average admission. The interface is evaluated as a plug-in module for TimeXer, Inverted Transformer (iTransformer), and Patch Time Series Transformer (PatchTST) under a zero-extra-tuning protocol, where each gated model inherits the corresponding baseline configuration. Experiments on the Electricity Transformer Temperature minute-level (ETTm1 and ETTm2) datasets, Traffic, Energy, and influenza-like illness (ILI) include paired forecasting comparisons, gate-placement ablation, initialization ablation, controlled covariate-admission analysis, and a variance inflation factor (VIF)-informed permutation feature importance (PFI) diagnostic case study. In the tested settings, the gate is competitive with the corresponding baselines, and the usage penalty reduces average admission scores while keeping forecasting errors close to the unpenalized TimeXer setting.
### Title:
          How Much of a Real Workload Can LLM-Generated GPU Kernels Actually Reach?
 - **Authors:** Gaurav Agarwal, Ashish Garg, Isha Singhal
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Language models can now write GPU kernels that outperform PyTorch. We evaluate five model configurations on KernelBench level 1 and find that a frontier model produces correct kernels for 91.1% of problems and independently verified speedups on 22 of 56, including three convolutions, with a median of 1.235x. Open-weights models are far behind: the best reaches 30.4% correct with three verified speedups and solves zero convolutions. We then ask a question the literature does not: what fraction of a real model's wall clock do such kernels govern? Profiling seven workloads across three domains, we find the addressable fraction ranges from 8.9% to 58.2%. On transformers, 80-86% of runtime is spent in cuBLAS GEMM and FlashAttention, bounding realistic end-to-end improvement at roughly 1%, and the fraction shrinks with model scale. On recommenders it is 58.2%, concentrated in a single embedding kernel. We introduce DLRM-Bench, 12 recommender kernel problems in KernelBench format, and measure a 41.7% win rate at a 1.552x median there, projecting 8.63% end-to-end. Separately, we show that KernelBench's correctness check (this http URL with an absolute tolerance) is satisfied by a tensor of zeros on 4 of 60 level-1 problems. Two kernels in our own results exploited this before we detected them, including one scored at 283x that wrote 0.3% of its output buffer. We propose scale-invariant replacements and release all 879 evaluations.
### Title:
          LoRA Enhanced Contrastive Learning with SAS Vision Transformers
 - **Authors:** Dan Zimmerman, Frank E. Bobe III, Amelia L. McCormack, Matthew Cook, Gregory D. Vetaw
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automatic target recognition (ATR) with synthetic aperture sonar (SAS) supports advanced naval capabilities, but deep learning is constrained by scarce target imagery, background clutter, and human-in-the-loop assessment. We adapt DINOv3 Vision Transformer (ViT) models to underwater SAS ATR using a three-stage parameter-efficient framework. Stage 1 uses Low-Rank Adaptation (LoRA) while freezing the ViT backbone, bridging the gap between natural-image pretraining and underwater acoustic propagation. Stage 2 uses hard-negative mining to strengthen the decision boundary against acoustic mimics, including rocks and sediment formations resembling man-made targets. Stage 3 uses Supervised Contrastive Learning (SupCon) to separate target and clutter representations. We evaluate at-sea SAS data using a mission-level geographic split, compare all arms at 85 percent test recall, and repeat each comparison over three random seeds. LoRA accounts for the primary effect, increasing area under the precision-recall curve (AUPRC) from 0.300 to 0.679 +/- 0.027 using the same frozen backbone. Rank 4 achieves this result while training only 0.26 percent of weights. Neither refinement stage exceeds its matched control: hard-negative mining changes AUPRC by -0.0045 +/- 0.0119 versus an equal-size random curriculum, and SupCon changes AUPRC by +0.0002 +/- 0.0096 versus the preceding stage. These null results indicate that mining occurred on data the encoder had already fit and that supervised stages had already imposed most target-clutter geometry. One efficient adaptation stage is sufficient; stacked refinement is not.
### Title:
          Origin Is All You Need: Provenance-Aware Transformers for Structural Trust-Boundary Separation
 - **Authors:** Yuxuan Zhang, Jeff Huang, Guofei Gu
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Indirect prompt injection (IPI) remains a central safety and security challenge for large language model (LLM) systems because standard transformers lack architectural notion of source authority. Retrieved documents, user inputs, and system instructions are all processed through the same undifferentiated attention mechanism, forcing the model to infer from wording alone what should be obeyed and what should be treated as data. We propose Provenance-Aware Transformers, a provenance-aware defense that makes application-supplied source labels actionable inside the model. Each input token is assigned a ring ID encoding its origin, and the model is augmented with origin embeddings, a learnable origin attention bias, and a learnable origin scale that preserves provenance under normalization. The resulting architecture enforces a structural boundary between authoritative and non-authoritative sources during generation. To instantiate this architecture on released pretrained models, we propose a two-stage fine-tuning pipeline to teach the model origin semantics and task behavior under ring constraints. Evaluation shows that Provenance-Aware Transformers maintain robust resistance to IPI both in-distribution and out-of-distribution while preserving utility comparable to the base pretrained model. More broadly, our work shows that exposing provenance as a first-class architectural signal can shift LLM safety alignment from brittle pattern matching toward explicit trust separation.
### Title:
          Detecting Hallucination in LLMs: Tracing the Topological Signatures of Impaired Context Sharing
 - **Authors:** Amir Jalilifard, Anderson Rocha, Eric Wong, Marcos Medeiros Raimundo
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this work, we examine the topology of information flow patterns within attention graphs to effectively distinguish hallucinated from non-hallucinated responses. We analyze the Forman-Ricci curvature to identify structural patterns indicating information bottlenecks in attention graphs. We then introduce a method that captures both semi-local and global information-flow characteristics of attention heads associated with hallucinated responses. We evaluate our approach extensively across several LLMs and established benchmarks. Empirical results demonstrate that our proposed single-pass approach provides consistent improvements over existing attention-based and multi-response baselines across two hallucination-detection benchmarks, while achieving competitive performance across diverse LLM architectures. Further analysis reveals that impaired context sharing among tokens during causal generation is strongly associated with hallucination occurrences in LLMs. In particular, hallucinated responses are consistently characterized by an over-reliance on self-attention, diffused context retrieval from earlier tokens, or information over-squashing, especially in the final transformer layer.
### Title:
          Not All Irregularity Is Equal: Causally Isolating a Rare Failure Mode in Japanese Morphological Inflection
 - **Authors:** Wen Zhang
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural morphological generation systems often achieve high aggregate accuracy on benchmark datasets, yet such performance can conceal systematic errors clustered in rare morphological subclasses. We present an orthography-aware diagnosis of Japanese past-tense verb inflection, treating hiragana not merely as a transcriptional medium but as a representational system that encodes morphophonological structure. Using two character-level Transformer architectures evaluated across five random seeds, we show that although both systems exceed 97% aggregate accuracy, a single structurally specific irregular subtype, verbs whose stems end in /e/ and require gemination before the past-tense suffix and make up fewer than 1% of the data, accounts for a disproportionate 30-43% share of residual errors and contributes roughly 34-48x its prevalence to total errors. We then move from diagnosis to causal isolation: controlled ablation experiments show that removing this subtype alone produces larger accuracy gains than removing all irregular verbs combined. These findings indicate that error concentration in neural morphological learning is not driven by irregularity per se, but by the interaction between extreme low-frequency morphological patterns and specific orthographic processes. We argue that morphological evaluation should incorporate fine-grained subclass analysis, and discuss implications for data-efficient, developmentally plausible language model pretraining.
### Title:
          Visual Navigation Transformer with Pose Attention
 - **Authors:** Beiming Li, Jaime Romero, Jonathan Diller, Vijay Kumar, Alejandro Ribeiro
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learned navigation policies typically consume observations as a temporally ordered history, with positional encodings tying each observation to when it was seen, making it difficult to reuse experience from earlier traversals of an environment. Systems that do reuse such experience usually construct an explicit representation, such as a map or a topological graph, and plan on it. We propose VNT-PA (Visual Navigation Transformer with Pose Attention), a transformer planner whose context is a set of depth keyframes indexed by camera pose. With camera poses as positional encoding, attention depends on the pose differences between keyframes rather than on their temporal order. VNT-PA is trained to imitate a shortest-path planner operating on the ground-truth scene mesh, predicting actions by querying the spatial context with only its current pose and the goal position. On point-goal navigation in HM3D validation scenes, VNT-PA reaches 93.3% success and 90.4% success weighted by path length (SPL), outperforming baselines that encode the same context as a temporal sequence or treat pose as an input feature, in both navigation performance and training efficiency. Because the spatial context is a pose-indexed set, frames from different trajectories can be fused at test time. The planner also degrades more gracefully under localization noise than a conventional baseline which plans on explicit maps. These results show that pose-stamped experience can serve directly as the environment representation for a learned planner, and that making attention depend on pose differences, rather than on temporal order, speeds up training and improves long-horizon navigation.
### Title:
          Fewer Steps, Better Actions: Rethinking Flow-Matching Inference for VLA Policies
 - **Authors:** Zhipeng Tang, Xinda Chen, Weining Rao, Xiao Li, Wenting Tan, Yuning Wang, Xiao Shi, Xiaofang Zhao
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language-action (VLA) policies based on flow matching generate action chunks through repeated evaluations of an action expert. Increasing the number of integration steps raises inference cost, but does not necessarily improve closed-loop success. We propose Coda, which reallocates part of this integration budget to a single learned endpoint correction. A frozen policy first completes a few-step noise-to-action trajectory; a lightweight Transformer then predicts a demonstration-supervised residual using the candidate action, source noise, and shared observation-prefix cache. Only the corrector is trained. On 50 RoboTwin Easy tasks, five-step Coda improves success from 71.64% to 74.68% over the matched five-step baseline, while reducing forward latency by 30.2% relative to the default ten-step policy. A two-step configuration achieves 71.88% success with a 2.12$\times$ speedup. An independent 13-task control shows a 5.69-percentage-point gain at nearly equal latency, supporting correction as an effective alternative to additional integration. The same design also improves frozen official SmolVLA, raising two-step success from 60.8% to 69.4%. These results show that endpoint correction improves the quality-latency trade-off of frozen flow-matching policies.
### Title:
          Multi-viewpoint Geo-localization with Event Cameras
 - **Authors:** Adam D. Hines, Michael Milford, Tobias Fischer
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robot localization is an ongoing challenge that demands mapping and positioning systems that are tolerant to viewpoint change. Event cameras are attracting increasing interest and adoption in robotics; however, dealing with viewpoint variance is an under-investigated problem in existing event-based localizers. In addition, event-based datasets that emphasize viewpoint variance for challenging localization situations are scarce. Here, we introduce an event-based visual place recognition (VPR) system that performs robustly under viewpoint changes. We converted five large-scale geo-tagged datasets, conventionally used to train frame-based localization systems, into synthetic event streams using Image-to-Event (I2E) conversion, and used them to fine-tune a pre-trained event-based vision transformer backbone with a multi-loss function, yielding a system we call MegaEvent that learns viewpoint-robust features for place recognition. We achieved an average Recall@1 of 82% across three existing event-based localization datasets, leading the next best event-based method by 20 recall points, and frame-based VPR models applied directly to event frames by 8 to 26 recall points. We introduce a new, challenging dataset - Springfield-Event-VPR - which features a 3.7km walking route recorded in three camera orientations for a total of 11.1km, which MegaEvent outperforms the strongest baseline by 9 recall points. The code for MegaEvent is available at this https URL.
### Title:
          FairLMs: A Turnkey Library for Fairness in Language Models
 - **Authors:** Jiale Zhang, Michael Larionov, Zichong Wang, Zhipeng Yin, Wenbin Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fairness research on language models involves measuring bias, applying mitigation methods, and examining the evidence on which an evaluation rests. Existing tools offer complementary functionality through different interfaces, so combining them requires reconciling model interfaces, evidence formats, access constraints, and result types before applicability can be checked or methods compared. We introduce \textbf{FairLMs}, a Python library that connects these activities through explicit declarations of model capabilities and input requirements. It provides 33 intrinsic and extrinsic metrics, 14 mitigation components spanning four intervention categories, 14 dataset and scoring-instrument diagnostics, adapters for the three Transformer architectures and supported hosted completion APIs, and benchmark loaders. Declarations are checked before execution and results carry the configuration under which they were obtained, so that compatible components can be combined, methods compared under a common protocol, and workflows extended to new models and datasets. The source code is available at: this https URL.
### Title:
          Probabilistic Forecasting of Business Process Executions with Neural Temporal Point Processes
 - **Authors:** Jiaxin Yuan, Daniela Grigori, Han van der Aa
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Operators of service-based systems act on forecasts of how a running execution will continue, and such a forecast is actionable only if its reliability is known. Mainstream deep-learning models for this task are discriminative and deterministic: they emit a single next activity and a single remaining-time estimate, without a distribution to reason over. We instead cast the problem as generative sequence modelling with marked temporal point processes, which define a joint density over the next mark and its inter-event time and therefore deliver predictive distributions by construction. Real event logs violate the simple-point-process assumption these models rest on, since consecutive events frequently carry identical timestamps; we handle such ties explicitly and combine a transformer encoder with a mixture decoder over inter-event times, trained by exact log-likelihood. On ten public logs, the resulting model matches discriminative baselines on point accuracy, dominates them on the calibration and sharpness of remaining-time distributions, and is the cheapest at inference, since a full predictive distribution is obtained in a single forward pass without sampling.
### Title:
          Synthetic Human Mobility Data Generation: A Structured Review of Representations, Methods, and Practical Capabilities
 - **Authors:** Yanbo Pang, Chen Zhong, Song Gao, Yoshihide Sekimoto
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Human mobility data has become an increasingly important component of urban analytics. Although the range of available mobility data sources has expanded substantially, access remains highly constrained by commercial restrictions, privacy concerns, and institutional barriers. Data protection procedures also often reduce the analytical value of released datasets. Synthetic mobility data has emerged as a promising solution, but existing methods differ substantially in their underlying mechanisms, the information they preserve, the outputs they generate, and the analytical questions they can support. Their comparative strengths and trade-offs remain insufficiently understood for urban analytics. This paper presents a structured review of synthetic human mobility data generation from an urban analytics perspective. We review the literature by methodological family and index it by the mobility outputs each family generates natively and the analytical capabilities those outputs enable. We first provide a taxonomy of synthetic data products, including population and persona representations, activity schedules, trip and tour records, trajectories, and aggregate mobility patterns. We then review the major methodological families, spanning mechanistic models, survey-driven population synthesis, activity- and agent-based simulation, deep generative models, transformer-based mobility language models, and LLM-agentic systems. Building on this synthesis, we introduce a Meaning-Population-Autonomy framework that characterises these methods along three dimensions: behavioural meaning, population grounding and scale, and generation autonomy. We consider these dimensions the principal requirements for downstream urban analytics. Few methods deliver behavioural meaning, population grounding and autonomous generation at once, and fewer still with generation constrained to feasible trajectories.
### Title:
          Think Locally, Refine Globally for Memory-Efficient 3D Reconstruction
 - **Authors:** Jingke Zhou, Chenhang Ma, Zhizhou Zhong, Mingkai Liu, Zhuang Zhou, Yicheng ji, Binghua Su, Bo Cai, Xianliang Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose LoG-VGGT, a memory-efficient framework for long-sequence 3D reconstruction that balances local temporal modeling with global camera consistency. Instead of relying on full global attention, our method introduces cross-window attention at a small subset of transformer blocks, enabling effective information propagation across adjacent temporal windows while keeping memory usage bounded. To mitigate long-term pose drift, we further design a global camera consistency refinement module, where camera tokens interact with compact register tokens via cross-attention to enforce scene-level constraints across the entire sequence. This design enables joint optimization of camera representations and significantly improves long-horizon pose stability without incurring the high cost of sequence-wide attention. Extensive experiments demonstrate that LoG-VGGT achieves improved depth accuracy and robust camera pose estimation across multiple long-sequence benchmarks, while delivering competitive streaming reconstruction performance.
### Title:
          ME-Dex 1.0: Bringing Heterogeneous Tactile Sensing into World Action Modeling
 - **Authors:** Xuancheng Zhang, Xuetao Liu, Qianying Tang, Jizhe Wang, Zhijing Cheng, Bochen Lin, Haoran Wen, Ming Li, Kun Zhan, Yu Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World Action Models bring the predictive capabilities of video models into robot action generation, providing a rich foundation for modeling future visual states. Tactile sensing complements this foundation with direct measurements of physical interaction. Some existing methods use tactile features as conditioning inputs without jointly predicting future tactile states, visual observations, and actions. Our key insight is that tactile signals, like video, provide observations of the evolving world state and should be modeled as future observations alongside video. We present ME-Dex-1.0 (MachEmbodied-Dex-1.0), a unified World Action Tactile Model for joint visual, tactile, and action learning. ME-Dex-1.0 adopts a Mixture-of-Transformers architecture comprising a Video Expert, a Tactile Expert, and an Action Expert, all trained with flow matching. We use shared attention connects the experts in intermediate layers, allowing action generation to draw on learned representations of visual and tactile dynamics during joint denoising. To support multi-source heterogeneous tactile inputs, a Canonical Hand Model and a Unified Tactile Autoencoder map tactile observations from different embodiments and sensing layouts into shared spatial and latent spaces. To address the limited availability of paired visual, tactile, and action data, we develop the Agentic Tactile Data Engine, an agent-based data production platform. It supplements RoboTwin and DexJoCo with tactile data recorded directly from force sensors during trajectory replay in simulation. Experiments on the RoboTwin, DexJoCo, and ManiFeel simulation platforms, together with real robot evaluations, demonstrate improved manipulation performance using both grippers and dexterous hands equipped with tactile sensing.
### Title:
          MT-WAM: Reorienting the One-Pass Predictive Representation Toward Action Generation
 - **Authors:** Yiguang Yang, Jiankun Peng, Xiaoming Wang, Yiran Zhang, Zhibo Fang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fast-WAM shows that video-action co-training improves control without generating future video at inference, making the representation from a single video diffusion Transformer forward central to action generation. However, future-observation prediction does not explicitly prioritize the future dynamics and visual structure needed for control. We present MT-WAM, which retains the original training objectives and adds complementary supervision for future two-dimensional point trajectories and visual features. A lightweight dual-stream branch copied from the video backbone's final blocks provides target-specific processing, while a structured attention mask prevents cross-stream attention. Motion-stream tokens supply additional dynamics conditions to the action expert. Future visual-feature prediction provides supervision in a feature space that captures object and spatial structure. This supervision trains the video backbone to provide more informative visual context for action generation under changing visual conditions, without adding visual-feature-stream tokens to action conditioning. At inference, MT-WAM uses video and motion caches computed once per replan and skips future-video prediction. Without additional embodied policy pretraining, MT-WAM achieves 98.2% success on LIBERO and 73.7% on LIBERO-Plus, exceeding Fast-WAM by 23.8 percentage points on the latter. On RoboTwin 2.0 Clean2Rand, Random success increases from 6.30% to 19.40%; across four real-world tasks, average success increases from 67.0% to 77.8%.
### Title:
          Adaptive World Memory 3D Foundation Model for Scalable 3D Mapping, Localization, and Rendering
 - **Authors:** Tianchen Deng, Guole Shen, Yilin Shen, Wenhua Wu, Yilin Fang, Ziqi Ma, Tianjun Zhang, Shenghai Yuan, Wolfram Burgard, Hesheng Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent 3D foundation models enable generalizable geometric reasoning from RGB images but remain limited in persistent memory, scalability, and renderable scene modeling. We present a memory-centric 3D foundation model for scalable robotic localization, reconstruction, and Gaussian rendering. Its core is an adaptive world memory mechanism that combines transformer-based gated updates with test-time temporal-spatial regulation. Learned gates control recurrent memory propagation, while temporal state evolution and spatial observation-state consistency regulate token-wise updates and forgetting over long image sequences. To support large-scale mapping, we organize memory into local submaps and integrate progressive mapping and tracking, loop closure, and SL(4)-based global refinement to maintain local accuracy and global consistency. A Gaussian reconstruction head decodes memory-enhanced features into renderable primitives, unifying camera pose estimation, dense point-cloud reconstruction, and photorealistic rendering within a single model. Experiments on public benchmarks and self-collected datasets from diverse robotic platforms demonstrate improved trajectory accuracy, reconstruction completeness, and rendering quality over existing 3D foundation reconstruction and SLAM baselines. These results support adaptive memory as a foundation for persistent robotic world modeling. The dataset and code will be made publicly available at \href{this https URL}{this https URL}.
### Title:
          Skel-WAM: A Hand-Skeleton-Conditioned World Action Model for Human-to-Robot Manipulation Transfer
 - **Authors:** Zetao Cai, Yaping Li, Yiqun Wang, Xinyu Zhan, Yuyin Yang, Haoxiang Ma, Kailin Li, Tao Lu, Jiangmiao Pang, Linning Xu, Dahua Lin
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robot demonstrations are expensive to collect and often provide limited distributional coverage of task variations. Human videos offer a low-cost source of complementary manipulation experience, but learning from them requires bridging embodiment gaps in visual appearance and action spaces. We introduce Skel-WAM, a world action model that bridges these differences through a unified hand-skeleton motion interface. The key insight is to align human and robot motion through a common hand topology, combining skeleton overlays that ground motion in the scene with structured 2.5-D keypoints that encode explicit hand kinematics. Video and Keypoint Experts jointly learn visual and skeletal dynamics through a Mixture-of-Transformers, while a separate robot-trained Action Expert maps these predictions to executable controls. This separation enables human and robot demonstrations to directly supervise shared dynamics without requiring robot action labels for human videos. Across four real-world bimanual tasks and seven simulated tasks, Skel-WAM achieves average success rates of 79.86% and 63.29%, surpassing the strongest baseline by 22.22 and 8.28 percentage points, respectively. Human-robot cotraining more than doubles real-world success on task variations absent from robot training data, from 38.89% to 86.11%. These results demonstrate that a shared skeletal interface enables joint learning across human and robot data and expands robot task coverage through complementary human demonstrations.
### Title:
          Dual-Interest Sequential Product Recommendation With Multi-Granular SSM
 - **Authors:** Shuiying Liao, P. Y. Mok
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sequential recommendation aims to predict the next item a user will interact with based on their historical behavior. Advances in Transformers have significantly improved sequential recommendation but are still limited by cost efficiency. Although State Space Models (SSMs) have recently enabled efficient long-range modeling, most existing methods encode each item with a single static contextual role, overlooking the phenomenon of item polysemy. In fact, the same item often plays different semantic roles depending on user context, and existing methods are limited in capturing dynamic behavior across different temporal granularities. In this work, we propose DSRec, a novel dual-interest cross-SSM model that explicitly disentangles item roles across long-term and short-term semantic context. Sequential items are encoded into long-term interest embeddings that capture stable preferences via historical aggregation, and a short-term interest branch that emphasizes local session intent modulated by inter-click time intervals. These interest embeddings are processed through distinct SSM encoders: a full-sequence Mamba for long-term modeling, and a time-modulated SSM that dynamically adjusts state evolution based on temporal gaps. To enable effective cross-granularity alignment, we adopt a residual cross-fusion mechanism that exchanges contextual information between the two branches while preserving semantic independence. Experiments on public benchmarks demonstrate that DSRec outperforms other state-of-the-art methods.
### Title:
          OneBid: A Unified Auto-Bidding Foundation Model for Diverse oCPX Advertising Scenarios
 - **Authors:** Yewen Li, Peng Jiang, Yitian Li, Pengfei Lv, Xialong Liu, Peng Jiang, Qingpeng Cai
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Auto-bidding is central to computational advertising, where strategies must maximize advertisers' conversion value under economic constraints. It has evolved from rule-based controllers to reinforcement learning and generative methods such as Decision Transformer (DT). Yet these methods increasingly mismatch the prevailing optimized cost-per-X (oCPX) paradigm, which spans heterogeneous scenarios (e.g., registration, purchase), each served by a separate model, leading to fragmented pipelines and underexploring cross-scenario modeling. Inspired by foundation models like LLMs, unifying these oCPX scenarios into one model raises three challenges: multi-objective control, scalable capacity under strict latency, and safe offline policy improvement. We present OneBid, a unified auto-bidding foundation model that learns a reusable backbone from heterogeneous oCPX logs and adapts it to scenario-specific deployments via offline post-training. Building on DT, OneBid extends single Return-to-Go conditioning to two atomic signals, Return-to-Go for conversion value and Cost-to-Go for cost ratio, plus value-aware regularization on next-action prediction. To absorb distributional heterogeneity, we design a sequence-level Mixture-of-Experts architecture, where shared experts encode cross-scenario knowledge and sparsely-routed experts capture scenario-specific patterns at low latency, yielding consistent scaling with model size and data. During post-training, we align the backbone with scenario preferences via Critic-guided Relative Offline Policy optimization (CROP): a learned critic scores candidate actions group-relatively, avoiding the unsafe online exploration of GRPO-style fine-tuning while constraining policy shift to reduce OOD risk. Validated via online A/B tests and fully deployed at Kuaishou, OneBid delivers an overall +2.2% ADVV gain on oCPX Ads, peaking at +13.1% in the ROAS scenario.
### Title:
          GestureFAR: Streaming Co-Speech Gesture Generation with Flow Autoregression
 - **Authors:** Pinxin Liu, Haiyang Liu, Jiahao Luo, Junhua Huang, Chunhao Zou, Luchuan Song
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generating natural co-speech gestures from streaming speech is essential for embodied conversational agents, where motion must be produced while a user is still speaking. Recent streaming gesture systems make online generation possible by autoregressing over discrete motion tokens, but this design compresses high-dimensional continuous motion into finite codebooks and can limit the realism and diversity of generated gestures. To preserve both causality and continuous expressiveness, we propose \textbf{GestureFAR}, a flow-autoregressive framework for streaming co-speech gesture generation. First, GestureFAR autoregresses over causal continuous motion latents, using a transformer to model streaming audio-motion context and a per-token flow-matching head to sample the next latent from a continuous distribution. Second, we introduce a head-only flow distillation strategy that freezes the causal backbone and distills the multi-step per-token flow head into a single network evaluation using consistency and distribution-matching objectives. This keeps the model token-causal while removing the main latency bottleneck for live interaction. Experiments on BEAT2 show that GestureFAR significantly improves the quality--latency trade-off among streaming-capable methods, preserving strong gesture quality while enabling real-time token-causal generation. Project Page: this https URL
### Title:
          Trading Depth for Time in Recurrent Transformers
 - **Authors:** Zeyi Huang, Xuehai He, Yong Jae Lee, Yelong Shen
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recurrent Transformers increase computational depth through temporal recurrence, feeding each token's high-level hidden state into the computation of the next. This raises a natural question: is additional computation better spent on more temporal steps or greater physical depth? We investigate this question using Latent Recurrent Transformers (LRTs), which retain one backbone forward pass per vocabulary token during decoding and provide a controlled setting for comparing these two ways of adding computation. Specifically, we insert a latent thought token between consecutive vocabulary tokens. Each thought token passes through the same $L$ layers as a vocabulary token, sharing the backbone parameters and providing an additional stage of hidden-state refinement before predicting the next token. We compare this $L$-layer LRT against a $2L$-layer LRT without thought tokens. Both execute $2L$ Transformer blocks per vocabulary token during decoding, but the thought-token model uses fewer parameters. On 16- and 20-layer mixture-of-experts NanoChat backbones, one thought token brings the shallower model within 0.006 and 0.004 bits per byte of its double-depth counterpart, recovering 67% and 81% of the improvement with approximately 48% fewer total parameters. These results suggest that temporal thinking offers a parameter-efficient alternative to increasing physical depth in recurrent Transformers.
### Title:
          Towards Fine-Grained Object Manipulation: SAM3-Guided Visuomotor Policy with Persistent Memory Learning and Focused Visual Conditioning
 - **Authors:** Haolong Meng, Fangbo Qin, Mengchen Bai, Houwu Wang, Cirong Liu, Shan Yu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fine-grained object (FO) manipulation requires robots to distinguish a specified FO from visually similar objects and execute actions reliably despite scene distractors. However, scene-level visual conditioning lacks explicit object selection, while category-level guidance cannot reliably distinguish FOs within the same category. We present a SAM3-guided visuomotor framework that addresses these challenges through persistent object memory and focused visual conditioning. First, we introduce FO Memory-driven SAM3 (FOM-SAM3), which learns reusable FO memory tokens from limited multi-view registration images while keeping SAM3 fully frozen. Through one-vs-rest learning, these tokens encode persistent memories for localizing target FOs and rejecting similar alternatives, which can be stored in a memory bank. Second, we propose Focused Spatial-Appearance Encoding (FSAE), which combines in-FO local appearance features with explicit bounding-box coordinates to condition action policies including Diffusion Policy (DP) and Action Chunking with Transformers (ACT). The effectiveness of the proposed FOM-SAM3 was validated on the FO-30 dataset comprising 30 physical objects across four coarse categories. Across three real-robot FO manipulation tasks, our FOM-SAM3-guided policies demonstrated robustness against distractors, discrimination ability among similar FOs, and extendibility to new FOs.
### Title:
          Detection is solved, delineation is not: what governs tooth segmentation on panoramic radiographs
 - **Authors:** Muhammad Rehan, Moaz Amjad, Syed Danial Ahmed, Mariam Adnan, Haider Ali
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automatic tooth segmentation and FDI numbering on panoramic radiographs underpins computer-assisted dental diagnosis, yet which factors govern performance remains unclear. We assemble a corpus of 1,422 panoramic radiographs containing 42,142 expert-delineated tooth polygons across the 32-class FDI taxonomy, annotated by 30 dental practitioners and independently reviewed by two others, and use it to isolate input resolution, architecture and anatomical priors under a single evaluation protocol. First, resolution dominates: across a controlled 640/1024/1280 ablation, mask mAP50-95 rises 0.656 -> 0.710 -> 0.717 while mAP50 stays flat at ~0.982. Both gains are significant under a paired bootstrap over images (p < 0.001, p = 0.024); neither mAP50 change is distinguishable from zero. Added resolution buys boundary precision, not detection. Second, architecture is nearly irrelevant in-domain: a query-based transformer with 2.1x the parameters is statistically equivalent to a one-stage detector (95% CI [-0.0064, +0.0064]), only marginally better under domain shift, 5.5x slower on CPU and not executable under standard ONNX runtimes. Third, three targeted interventions fail: a LoRA-adapted self-supervised encoder underperforms, a promptable foundation segmenter degrades masks by 39%, and globally optimal anatomical label assignment yields +0.0007 despite correcting a constraint violated in 40% of out-of-domain predictions. Zero-shot transfer to an independent multi-centre cohort, verified overlap-free, costs 62% of mask mAP50-95 but only 18% of mAP50, reproducing the dissociation. Decomposing masks along the tooth axis localises the residual error to the apical third. Boundary precision is therefore the binding constraint, and effort is better directed at resolution and acquisition diversity than at architectural novelty.
### Title:
          Extending Decoupled Attention to Dense Prediction and Masked Training for Multi-Channel Images
 - **Authors:** Umar Marikkar, Sameed Husain, Muhammad Awais, Sara Atito
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-Channel imaging (MCI) data differs fundamentally from natural images, as each channel records a semantically distinct signal rather than a colour band. To adapt vision encoders to MCI data, Multi-Channel Vision Transformers (MC-ViTs) tokenize each channel independently and concatenate the resulting tokens into one sequence, and the channel count is no longer fixed by the architecture. Self-attention is then computed across all channel-patch tokens with no restriction on which channels attend to which, which dilutes the features of individual channels. The Decoupled Vision Transformer (DC-ViT) regulates this by separating updates computed within a channel from updates computed across channels, and by forming a representation per channel before the channels are combined. Its formulation, however, pairs tokens by spatial position, and thus requires the same visible tokens in every channel. Correspondence under independent per-channel masking is recovered by solving a linear assignment between the retained patches of each channel, which allows decoupled attention to be combined with current masked multi-channel training in its standard configuration rather than a restricted one. Across three classification and three segmentation benchmarks spanning fluorescence microscopy, imaging mass cytometry and satellite imaging, including dense prediction at high channel counts, the resulting formulation outperforms the strongest MC-ViT baseline.
### Title:
          World Modeling in Transformers
 - **Authors:** Pierre Beckmann, Matthieu Queloz, Andre Freitas
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Behavioral failures can make a transformer appear to lack a world model even when it has learned faithful representations of its environment. We demonstrate this in TaxiGPT, a transformer trained on random walks through Manhattan whose failures have been interpreted as evidence of an incoherent internal map. Through mechanistic analysis and causal interventions, we show that the model represents intersections and streets, tracks its position, and uses a goal compass to navigate. We trace its failures to interference between superposed intersection features, which disrupts localization within the internal map. Affordance packing, which groups representations of intersections with the same legal moves, helps limit the consequences of these errors. Finally, we propose mechanistic indicators that we use to compare models and show that world-modeling capacities emerge at different stages of training. Our findings motivate a shift from asking whether a model has a world model to mechanistically studying its world modeling: the interacting capacities through which it represents its environment and uses those representations to guide behavior.
### Title:
          PSR: Predictive Sensorimotor Representation Learning for Contact-Rich Manipulation
 - **Authors:** Shengbao Li, Peng Xu, Chao Tang, Hao Wei, Jiaheng Wang, Hong Yin, Jiangtao Chen, Jinxuan Zhu, Zhong Zhou, Mengfan Wang, Tingguang Li
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Contact-rich manipulation requires policies to generate precise actions by reasoning over contact forces, robot configurations, and interaction histories beyond visual observations. Existing methods passively condition on force feedback rather than actively predicting future contact dynamics, limiting their ability to generate high-precision actions. To address this problem, we introduce Predictive Sensorimotor Representation (PSR) learning, a framework that learns a hierarchy of predictive representations from multimodal sensorimotor signals and integrates them into the action stream of a visuomotor policy. Specifically, during a pretraining stage, a multimodal Transformer is trained to learn a hierarchy of predictive representations by jointly forecasting future interaction dynamics. The learned hierarchy subsequently augments the action stream, enabling the resulting policy to exploit contact-relevant cues at multiple depths. We further instantiate PSR within a Vision-Language-Action (VLA) model, resulting in PSR-VLA, and evaluate it on six real-world contact-rich manipulation tasks. Experimental results show that PSR-VLA achieves 91.7% overall success, improving over $\pi_{0.5}$, ForceVLA-$\pi_{0.5}$, and ForceVLA2-$\pi_{0.5}$ by 30.0, 22.5, and 19.2 percentage points, respectively. These results demonstrate the effectiveness of the proposed PSR for force-aware, contact-rich manipulation. Videos of the tasks and stability tests are available at this https URL.
### Title:
          The Weight Is Over - Interactive Diffusion on Consumer GPUs
 - **Authors:** Frieder Ganz, Maximilian Müller
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV); Performance (cs.PF)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 On-device inference is booming, but the momentum is almost all in language models. Diffusion pipelines are memory hungry, latency-sensitive, and require orchestrating an embedder, a transformer, a decoder, and often further postprocessing that is not as standardized as LLM inference loops are. We navigate the trade-off between performance, quality, and model footprint to reach as many client devices in the wild as possible. We make three contributions: an embedding translator that maps a small text encoder into a large encoder space to cut weight and latency; a reproducible sweep recipe for navigating the speed/quality/memory triangle in diffusion pipelines; and an interactive on-device image generation editor achieving sub-second TTFI on recent GPUs.
### Title:
          Joint Remaining Useful Life Prediction and Capacity Estimation of Lithium-Ion Batteries Using Partial-Charging Data
 - **Authors:** Khoa Tran, Ho-Si-Hung Nguyen, Phone Wai Yan Moe, Hung-Cuong Trinh, Thi-Hoang-Giang Tran
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Joint remaining useful life (RUL) prediction and capacity estimation require representations of both gradual degradation and recent battery behavior. This paper presents a cross-expert framework using partial-charging measurements without measured historical full-cycle capacity as an input. The RUL Expert encodes nominal 10-min segments from ten cycles sampled within a 30-cycle history using a pretrained gated recurrent unit (GRU) encoder, a two-dimensional convolutional neural network (2D-CNN), and a temporal GRU. The Capacity Expert processes statistical descriptors of nominal 40-min segments from ten consecutive cycles using a 2D-CNN and a Transformer. A feature-wise linear modulation module uses the short-term representation to condition the long-term representation for joint prediction. Training comprises supervised autoencoder pretraining, independent expert pretraining, and fusion training with frozen experts. On two public battery-aging datasets, the reference configuration achieves mean RUL root-mean-square errors of 143.69 and 161.10 cycles and capacity errors of 12.36 and 7.28mAh, respectively. On Dataset I, fusion reduces both mean errors relative to either standalone expert. The results demonstrate a trade-off between RUL and capacity accuracy: the proposed method attains the lowest reported RUL RMSE among the compared methods on both datasets, whereas several baselines yield lower capacity errors.
### Title:
          Info3R: Information-Adaptive Test-Time Training for 3D Reconstruction
 - **Authors:** Sunghyun Baek, Hanna Bae, Minchan Kwon, Junmo Kim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based models have recently achieved strong performance on 3D reconstruction from images, and recent works extend them to process video streams in an online manner for real-world deployment. However, existing methods overlook two key signals when handling long image streams: the importance of each incoming frame and the information saturation of the model's internal state. In this paper, we propose Info3R, a novel information-adaptive test-time training method for the online 3D reconstruction. We introduce an information-aware state update that modulates the state update strength based on the redundancy and informativeness of each incoming frame. To restore the state's plasticity -- its capacity to incorporate new observations -- we propose a dynamic state reset, triggered by the cumulative magnitude of state updates and the model's prediction confidence and accompanied by an anchor-to-world alignment. Our method achieves consistent improvements on camera pose estimation, video depth estimation, and 3D reconstruction, while substantially mitigating the performance degradation in the long sequence evaluation. Notably, on KITTI Odometry, our method achieves on average 1.68x lower ATE than LongStream, demonstrating its robustness on extended outdoor sequences.
### Title:
          SkelWAM: A Skeleton-Guided World-Action Model for Zero-Shot Cross-Embodiment Manipulation
 - **Authors:** Pengjun Niu, Yujia Xie, Rui Peng, Hang Zhao, Ke Liu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reusing manipulation experience across robot embodiments is important for scaling robot learning and reducing repeated task-specific data collection. However, changes in embodiment alter visual appearance, action dimensionality and semantics, and the whole-body configurations that can realize the same tool pose. We present SkelWAM, a skeleton-guided world-action model that couples perception and control through one explicit geometric representation for single-source cross-embodiment manipulation. Arm centerline geometry, tool-center-point (TCP) pose, and parallel-jaw commands form a shared 25-D state. The same definition underlies canonical third-person and wrist observations and future whole-body action targets. Trained with predictive visual supervision, a video-action mixture of transformers predicts canonical skeleton action chunks, which embodiment-specific constrained decoders convert into joint or continuum-robot controls. This formulation requires no one-to-one joint correspondence and uses no target-task demonstrations or target policy updates. We introduce LIBERO-Cross10, a source-only cross-embodiment transfer benchmark covering ten tasks and ten target embodiments across four morphological groups. On this benchmark, Franka-trained SkelWAM achieves 43.3% success over 1,000 episodes, exceeding the best-performing evaluated baseline by 36.2 percentage points. We further deploy a JAKA mini2-trained policy on the Feagine A03 continuum robot for three tabletop manipulation tasks, illustrating the approach's potential for real-world cross-embodiment manipulation. Project page: this http URL
### Title:
          Learning-Based Augmentation and Adaptation for Grid Sim-to-Real Model Discrepancy
 - **Authors:** Sayak Mukherjee, Kyung-Bin Kwon, Ramij R. Hossain, Marcelo Elizondo
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern power systems can encounter increased discrepancy between the operators' simulation model and the actual true dynamics of the grid, driven by uncertainties caused by integration of new inverter-based resources (IBRs), large loads, unmodeled dynamics, parameter drifts, etc., to name a few. All of these impact the control room operations, where some critical oscillations may not be captured during the transient studies. To circumvent these issues, we propose a learning-augmented hybrid approach where the operator simulation model is supplemented with artificial intelligence (AI)-learned residual models using the phasor measurement unit (PMU)/ point-on-wave (PoW) based sensed trajectory data. The physics-based operator model provides interpretability and structural consistency, while the learned residual captures discrepancies caused by non-idealities. The learned model employs advanced neural architectures and consists of a backbone encoder and multi-head decoder layers for heterogeneous grid channels. Subsequently, we formulated a continual learning-motivated adaptation framework such that the baseline residual AI model can also be updated when the underlying real grid model changes in future conditions. Extensive numerical simulations are performed on the IEEE 68-bus benchmark model with a diverse set of disturbances, and different state-of-the-art predictive architectures involving recurrent learners, latent neural ODEs, and transformers are explored to demonstrate both residual learning and adaptation capabilities.
### Title:
          COMPLEX: A Closed-Form Certified Embedding of Multiparameter Persistence Modules
 - **Authors:** Sushovan Majhi, Atish Mitra, Žiga Virk, Pramita Bagchi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Algebraic Topology (math.AT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Every multiparameter persistence vectorization we know of carries a one-sided Lipschitz upper bound and nothing below it: without a lower gauge there is no sense in which the features are faithful, and no per-prediction guarantee can be built on them. This paper supplies the missing side. COMPLEX is a closed-form, training-free embedding of multiparameter modules -- slice the module along a fixed near-diagonal net, embed each slice barcode by the certified PLACE/PALACE landmark map, concatenate. Under a checkable witnessing-slice coherence condition, holding on 100% of audited pairs on Orbit5k, a single slice carries a closed-form lower gauge: separated modules stay separated in the embedding. With the standard upper bound this gives, to our knowledge, the first two-sided distortion bound for a multiparameter feature map, making faithfulness measurable. Measuring it, we find the floor tight within a small factor of realized distances yet operationally local: an RBF-SVM reaches 91% where 1-NN reaches 78% on the same features. Local per-prediction certification therefore fails for a structural reason common to every landmark embedding whose lower gauge is witnessed by one coordinate. With no learned embedding and no held-out calibration -- only a cross-validated SVM head -- COMPLEX sets the state of the art on both Orbit benchmarks (91.95% on Orbit5k, 92.98% on Orbit100k), level with or above Euler-characteristic surfaces and above transformers and graphcode. On graphs it exceeds GRIL on all four shared molecular benchmarks with one fixed configuration, including the only multiparameter method to clear COX2's majority baseline by more than three points. Closed-form selection -- of the landmark radius, the kernel (certificate-preserving), and the bifiltration set -- buys further accuracy; gradient-shaped adaptation buys none.
## Keyword: autonomous driving
### Title:
          Talk to Me, Jarvis: An Open-Source Edge-Deployable Voice Assistant Framework for Autonomous Racecars
 - **Authors:** Daniel Henel, Frederik Werner, Alexander Langmann, Johannes Betz
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in large language models have improved their effectiveness as back-end components for voice assistants, particularly in intent understanding and context-aware input classification. However, online-hosted models introduce network dependency and variable inference latency, limiting their suitability for time-critical autonomous driving applications. In this work, we address these issues by developing Jarvis, an offline voice assistant for high-level behavioral commands of autonomous vehicles. Its architecture integrates speech recognition and synthesis with natural language command classification into a lightweight, local framework. Jarvis core component is a text-to-command classifier, built using a domain-specific fine-tuning of the Mistral 7B model, demonstrating low-latency inference. Our experimental evaluation demonstrates that our solution outperforms larger online-hosted models, achieving 97.63 % intent recognition accuracy with an average processing latency of 1.39 s, making it well-suited for operations requiring quick response times. To support further research and fine-tuning, we provide an open-source implementation.
### Title:
          Stabilizing Trajectory Outputs in End-to-End Autonomous Driving via SC-IMM Based Teacher Signals
 - **Authors:** Siewoo Kim, Seung-Hyun Kong
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-End autonomous driving models commonly predict future waypoints from sensor inputs and convert them into vehicle control commands through a downstream controller. However, conventional waypoint-based imitation learning mainly minimizes coordinate-level errors, making it difficult to capture scene-dependent path-speed changes and temporal instability across waypoint outputs. In this paper, we propose an offline teacher-signal generation and learning method for trajectory-output stabilization based on a Scene-Conditioned Interacting Multiple Model (SC-IMM) to mitigate this issue. The proposed method converts expert trajectories into path-speed states and performs IMM updates conditioned on scene cues to generate path-speed teacher labels and mode posterior probabilities. The generated signals are added to the original trajectory loss as auxiliary supervision during training, while the inference structure and waypoint controller remain unchanged. In closed-loop evaluation on 100 short routes in CARLA Town12, the proposed method improved the driving score by 28.0% and reduced Collision/km by 62.3% compared with the baseline, while also improving jerk and trajectory-variation metrics. These results demonstrate that offline teacher signals embedding scene-conditioned motion-model cues can guide trajectory-output driving models toward more stable closed-loop behavior.
### Title:
          Driving on Registers, Reasoning on Risk: Risk-Aware Occupancy for Register-Based End-to-End Autonomous Driving
 - **Authors:** Jiaxing Chen, Hengduo Zou, YuKai Qin, Yiren Zhao, Lidong Yu, Bolin Gao
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal trajectory prediction improves behavioral coverage in end-to-end autonomous driving, but existing methods remain limited by sparse scene representations. Incomplete evidence leads to low-quality candidate generation and unreliable ranking among geometrically similar trajectories. On a register-based baseline, bad and poor candidates constitute 19.74% of the candidate set, while the oracle-best candidate ranks only 33.9th on average. We propose RRDrive, which introduces risk-aware occupancy as a dense, temporally aligned, and trajectory-queryable representation. Its global structure guides high-quality multimodal generation, while candidate-conditioned risk queries support fine-grained selection. We further construct RiskOcc4D-NAVSIM with automatic risk annotations. RRDrive achieves a selected-trajectory PDMS of 0.951, representing a 1.5% relative improvement over the baseline (0.937), and improves the average candidate PDMS by 7.7%. In challenging scenes, it improves candidate PDMS by 30.2% and increases the Spearman correlation among good candidates by 0.41, from 0.26 to 0.67. To move beyond this oracle setting, we further develop an external RiskOcc predictor, a perception module that estimates risk-aware occupancy directly from sensor inputs. The competitive performance validates the representation's feasibility.
### Title:
          PRIME: Perception Feedback with Situational Memory Embeddings in VLA Models
 - **Authors:** Erik Deinzer, Naya Baslan, Luca Paparusso, Narunas Vaskevicius, Peter Knott, Luigi Palmieri
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current Vision-Language-Action (VLA) models for autonomous driving operate primarily through feedforward inference across the perception--reasoning--planning hierarchy. While modern architectures maintain temporal recurrence within the perceptual module, early perception remains blind to downstream reasoning and navigation goals, processing visual inputs agnostically without prioritizing cues informed by prior decisions. To bridge this gap, this paper introduces PRIME, a learned feedback mechanism that conditions the VLA perceptual queries on a novel Situational Memory. By aggregating latent representations of past perception, reasoning, navigation goals, and predicted behaviors across an L-step window via cross-attention, PRIME enables intent-driven perceptual attention at minimal computational cost, adding only a maximum of 29.7M parameters (0.41% of the 7.3B-parameter base model). Evaluated on the Bench2Drive closed-loop benchmark, PRIME achieves a state-of-the-art Driving Score of 82.47 (+4.73 over ORION) and a Success Rate of 60.00% (+5.38 percentage points), the highest reported Driving Score among published VLAs trained on Think2Drive demonstrations.
### Title:
          Traffic Sign Recognition for Autonomous Driving Using Branched YOLOv2 and Geometric Features
 - **Authors:** Arefeh Rezaei
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traffic sign recognition (TSR) is an important perception task for autonomous driving and advanced driver-assistance systems, where a system must both localize traffic signs and determine their semantic classes efficiently. This work presents a TSR system based on YOLOv2 for simultaneous detection and classification. Two complementary modifications are studied. First, YOLOv2 is extended with intermediate prediction layers, forming a branched architecture that can terminate inference early for easy cases and reduce computation time. Both whole-image and cell-wise branching strategies are investigated. Second, geometric information is introduced to reduce classification errors between visually similar signs. An unsupervised Bayesian image-segmentation method produces binary representations that are compared with class-specific geometric templates inside YOLOv2 bounding boxes. This information is used either during inference or as an additional signal during training. A dedicated dataset is constructed by combining GTSDB and GTSRB samples using seamless cloning and controlled image transformations. Experiments cover ten traffic-sign classes, with 3,000 training and 300 test samples. The selected branched architecture reports 0.647 s runtime and 0.680 mAP, compared with 0.6607 s and 0.680 mAP for baseline YOLOv2. Geometric verification during inference increases mAP to 0.713, while the geometric-feature training variant achieves 0.697 mAP with a reported runtime of 0.6608 s.
