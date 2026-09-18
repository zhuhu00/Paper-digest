# Showing new listings for Friday, 18 September 2026
## Keyword: SLAM
### Title:
          AMB3R-SLAM: Kilometer-scale SLAM with Hierarchical Backend
 - **Authors:** Hengyi Wang, Lourdes Agapito
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present AMB3R-SLAM, a real-time monocular SLAM system capable of reconstructing kilometer-scale trajectories over 10k frames on a single consumer-grade GPU. Our model couples a lightweight front-end for low-latency online tracking with a hierarchical backend that progressively enforces local, mid-level, and global consistency. By avoiding bundle adjustment that relies on the static world assumption, our system naturally handles complex dynamic scenes out of the box. Furthermore, we demonstrate that our method can be extended to leverage stereo, RGB-D, and LiDAR as additional inputs. AMB3R-SLAM achieves strong camera tracking performance across 9 datasets, reducing the absolute trajectory error (ATE) of previous state-of-the-art methods on VBR and Oxford Spires by over 70%. With additional LiDAR input, our model further reduces ATE to sub-meter level on KITTI and VBR datasets.
### Title:
          SLAMSqueezeBench: Comparing SLAM Systems under Resource Constraints
 - **Authors:** Mohamed Hefny, Karthik Dantu, Steven Y. Ko
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Simultaneous localization and mapping (SLAM) is one of the services running on an autonomous robot. It is typically run to assist other tasks such as planning, manipulation, etc. All these tasks are run on edge hardware and are subject to severe resource constraints. However, most SLAM systems are built and tested in isolation, and their performance is reported as if they are the only task running on a system. We observe that existing benchmarks lack a common mechanism for comparing SLAM systems under realistic resource constraints. To address this limitation, we have developed SLAMSqueezeBench, a framework that allows testing of SLAM systems under realistic workloads on edge hardware. It does so by imposing constraints on compute and memory resources available for the SLAM system during execution. It also simulates realistic camera frame acquisition with frame drops when a finite buffer is full. Using SLAMSqueezeBench, we compare nine SLAM systems spanning classical systems, learning-based systems, and approaches for Gaussian splatting. Our testing framework will be available for use by the community upon publication.
### Title:
          VGGT-GS SLAM: Uncalibrated Monocular Gaussian Splatting SLAM with Feed-Forward Priors
 - **Authors:** Yuhang Han, Hao Wang, Jiaxi Cao, Xingyu Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present VGGT-GS SLAM, a monocular 3D Gaussian Splatting SLAM system designed for uncalibrated videos. Starting from feed-forward VGGT pose and depth priors, our system performs submap differentiable bundle adjustment that jointly refines camera poses and a 3D Gaussian map, while optimizing submap-shared intrinsics and radial--tangential distortion through analytic calibration Jacobians. To improve global consistency, we introduce Gaussian-native alignment (GNA) for camera-anchored scale refinement between sequential submaps and verification of loop-closure candidates. Extensive experiments on standard indoor benchmarks show consistent improvements in localization accuracy and strong rendering quality under uncalibrated settings, establishing a strong baseline for uncalibrated Gaussian SLAM.
### Title:
          LapaTrack-3D: 6 DoF pre-operative shape tracking for laparoscopic surgery
 - **Authors:** Jingwei Song, Javid Hussain Jakir, Ray Zhang, Wenwei Zhang, Hao Zhou, Xiaomeng Xian, Maani Ghaffari
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work proposes a real-time 6 Degree-of-Freedom (6 DoF) tracking algorithm for monocular laparoscopic surgery. It provides alignment between intra-operative video and pre-operative data (e.g., CT). The 6 DoF tracking offers a solution for accurately locating the internal anatomy of the target organ despite the lack of tactile feedback and transparency. The ORB-SLAM2 framework is adopted and modified for prior-based 3D tracking with four major modifications. First, the primitive 3D shape is used for fast initialization of the ORB-SLAM2 monocular mode. Second, a pseudo-segmentation strategy is employed to separate the target organ from the background for tracking. Third, the 3D shape is incorporated as a geometric prior in its pose graph optimization. Fourth, the Multi-Scale Retinex with Chromaticity Preservation (MSRCP) algorithm is leveraged and modified for image enhancement in challenging illumination scenarios. In-vivo and ex-vivo experiments validate that LapaTrack-3D provides robust 3D tracking and effectively handles typical challenges such as poor illumination, fast motion, out-of-field-of-view scenarios, partial visibility, and ``organ-background'' relative motion. LapaTrack-3D achieves a processing rate of 13 Hz for 1280*720 pixel video.
### Title:
          GRF-Recon: Global Ray-Field Optimization for Long-Sequence Feed-forward Reconstruction
 - **Authors:** Enpeng Li, Yunzhou Zhang, Zhiyao Zhang, Dexuan Lyu, Chenyu Wang, Chiyuan Cui, Cheng Cheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Feed-forward 3D reconstruction provides an efficient paradigm for scene modeling from image sequences. Scaling these models to large monocular scenarios are constrained by excessive GPU memory footprint, degraded local geometry, and long-term trajectory drift. Existing chunk-based optimization strategies provide limited geometric constraints and fail to maintain global consistency over extended trajectories. We present a unified framework for stable and scalable feed-forward 3D reconstruction from long monocular sequences. Our approach builds on coarse-to-fine trajectory alignment augmented by lightweight geometric prior injection. Distilling monocular geometric cues into the feed-forward backbone via LoRA adaptation improves depth accuracy on fine structures while preserving inference efficiency. We introduce a hybrid-weight sparse ray-field optimization that leverages high-frequency geometric features to guide local point-cloud refinement and enforce consistent inter-frame ray constraints. Unlike prior chunk-based methods, this establishes strong cross-frame geometric coupling while maintaining scalability. Finally, an efficient trajectory stitching strategy with joint ray-error optimization explicitly reduces accumulated drift. Extensive experiments show that our approach achieves competitive trajectory accuracy compared with representative SLAM systems, while maintaining globally consistent 3D reconstruction in large-scale scenarios.
### Title:
          Implementation of Tightly-Coupled SLAM Fusion of GPS, IMU, and LiDAR for Autonomous Vehicles
 - **Authors:** Amr O. Elmehrath, Farah Khaled, Rana Nahas, Catherine M. Elias
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous vehicles depend entirely on Simultaneous Localization and Mapping (SLAM) to navigate safely in unknown environments. However, relying on a single sensory modality introduces critical failure points: LiDAR systems degrade in featureless corridors, Inertial Measurement Units (IMUs) accumulate mathematical drift, and GPS drops frequently in urban canyons. This paper presents the implementation of a tightly-coupled SLAM fusion architecture that integrates a Velodyne 3D LiDAR, a high-frequency IMU, and GPS to achieve continuous spatial awareness. Utilizing a phased development methodology, we establish a 2D baseline to validate hardware synchronization and transform geometries before upgrading to a full 3D architecture driven by FAST-LIO2. This advanced approach uses an Iterated Error-State Kalman Filter (IESKF) to process dense 3D laser points alongside continuous inertial data, eliminating motion blur at high speeds. To eradicate long-term drift, a GTSAM pose-graph optimization back-end executes multi-modal loop closures. Evaluated across simulated environments and physical deployments, the results demonstrate that tightly-coupled 3D fusion effectively overcomes individual sensor blind spots to generate highly detailed point clouds, providing the foundational High-Definition (HD) maps required for advanced downstream autonomous planners.
### Title:
          EliGSiR: Continual RGB-D Mapping with Gaussian Splatting under Bounded Compute
 - **Authors:** Björn Ellensohn, Elmar Rueckert, Christian Rauch
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Conventional 3D Gaussian Splatting assumes a closed set of observations and long optimization schedules. Continual RGB-D mapping in contrast poses the problem that new observations arrive online, while previously reconstructed regions must be preserved. We present EliGSiR (Evidence-guided Load-adaptive Incremental Gaussian Splatting with Image Replay), a continual Gaussian mapper that controls how the available optimization budget is used as the reconstruction evolves. Map-Guided View Scheduling filters redundant incoming views and reconsiders retained views according to the current state of the map. Load-Adaptive Fidelity adjusts supervision resolution to the current mapping load instead of following a fixed resolution schedule. Targeted Geometry Growth separates depth supervision from Gaussian creation and adds geometric capacity only where repeated RGB-D observations indicate missing or misplaced structure. Together, these mechanisms adapt which views are optimized, how much image detail is used, and where the representation grows while mapping remains active. We evaluate EliGSiR on Replica, TUM RGB-D, ScanNet++, and real RGB-D sensor sequences, considering both the final reconstruction and the map available throughout acquisition. On TUM RGB-D fr3/long_office_household, EliGSiR reaches 21.52 dB with the same ground-truth mapping poses used by the controlled baselines, compared with 19.42 dB for SplaTAM. In the tracked-pose comparison, EliGSiR with live ORB-SLAM3 poses reaches 23.02 dB in 155.5 s, compared with 20.10 dB in 230.9 s for CaRtGS using its native tracker. We further evaluate reconstruction throughout acquisition and show how EliGSiR adaptive view scheduling, supervision fidelity, and geometry growth improve the use of the available mapping budget.
### Title:
          RawSLAM: Online HDR Gaussian SLAM from Linear Radiance
 - **Authors:** Marina Orozco González, Luis Merino
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current dense visual SLAM systems rely almost exclusively on 8-bit tonemapped Low Dynamic Range (LDR) inputs, limiting their robustness in extreme lighting where shadows and highlights trigger tracking drift and mapping collapse. Conversely, existing raw and High Dynamic Range (HDR) reconstruction pipelines operate strictly offline. They depend on Structure-from-Motion preprocessing and are not suited for large inter-frame motion. We present, to the best of our knowledge, the first online Gaussian SLAM framework that tracks and maps directly on single-exposure 16-bit linear HDR imagery. Our method rests on three core components: an architecture-agnostic HDR Gaussian Splatting module featuring an MLP-free logarithmic parameterization of Gaussian color features; a Reinhard range-compressed photometric objective; and structure-guided spatial gradient weighting. Combined, these components allow our approach to outperform a direct HDR adaptation of MonoGS in both trajectory and reconstruction accuracy, while rendering natively in linear scene radiance for post-rendering processing. The same formulation runs unchanged on standard 8-bit inputs, roughly halving the MonoGS baseline error. Furthermore, our HDR Gaussian module transfers seamlessly to SplaTAM, Gaussian SLAM, and DROID-W, eliminating all tracking failures these systems suffer on challenging illumination sequences. To enable this research, we introduce RawSLAM: a dataset of 10 real-world indoor sequences featuring 16-bit RAW imagery, aligned depth, IMU measurements, and external OptiTrack poses. Code and dataset will be made publicly available soon.
### Title:
          Semantic SLAM in Precision Agriculture using Bayesian Inference
 - **Authors:** Ruben Beumer, Sander Doodeman, René van de Molengraft, Duarte Antunes
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a real-time semantic world modeling framework specialized for precision agriculture using autonomous robots. The framework combines probabilistic mapping of objects and their semantic attributes, updated through Bayesian inference, with a graph-based Simultaneous Localization and Mapping (SLAM) approach implemented using $g^2o$, a general framework for graph optimization. This integration enables accurate mapping and localization without relying solely on GPS. By leveraging semantic information such as plant type, size, and health, the robot can perform tasks while mapping and localizing itself within a field of crops. The proposed framework was validated through Gazebo simulations and physical experiments on an indoor field with artificial plants using Boston Dynamics' robot dog Spot. A YOLOv8n object detection model was trained to extract object and semantic data from depth camera observations. These simulations and experiments demonstrate that the system can successfully perform real-time mapping of up to at least 400 plants.
## Keyword: odometry
### Title:
          Dynamic-LIVO: A Dynamic-Aware LiDAR-Inertial-Visual Odometry System Using Spatio-Temporal Normals
 - **Authors:** Zhixin Zhang, Samuel Ahiwe, Matthew Hale, Liang Zhao, Pawel Ladosz
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper proposes Dynamic-LIVO, a dynamic-aware LiDAR-Inertial-Visual Odometry (LIVO) system for robust state estimation and static colored mapping in dynamic environments. Dynamic-LIVO employs Spatio-Temporal (S-T) normal analysis to identify dynamic LiDAR points and propagates the resulting classification to both LiDAR-inertial and visual-inertial updates, preventing dynamic LiDAR measurements and their associated visual observations from affecting state estimation and mapping. However, S-T normal estimation can be unreliable in newly observed and spatially sparse regions due to insufficient spatio-temporal observations. To address this issue, we introduce a time-delayed S-T normal estimation strategy that defers the classification of insufficiently constrained points and re-evaluates them as additional observations become available. This strategy improves dynamic classification reliability while preserving valid static points for map construction. Extensive experiments on public and self-collected datasets with diverse sensor configurations demonstrate that Dynamic-LIVO improves localization accuracy and produces cleaner static colored maps in challenging dynamic environments. The source code and self-collected dataset will be publicly released upon acceptance.
### Title:
          OmniCalib: Target-Free, Task-Structured Self-Calibration for Humanoid Robots
 - **Authors:** Kaixiang Lu, Haiyu Lan, Chunxiao Qiao, You Li, Enyu Li, Yehao Lu, Jiarui Yang, Peiwen Lin, Chuang Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Assembly, wear, and component replacement perturb the sensor extrinsics and joint zeros encoded by a humanoid CAD model. Existing procedures calibrate one sensor pair or require external fiducials. Using only robot-native motion and onboard sensing, we present OmniCalib, a target-free workflow that calibrates the full upper limbs---all 14 arm joint zeros and the extrinsics of both wrist and chest cameras---as well as lower limbs and the multi-camera head rig. Each module matches a robot-native task to a parameter block, checks observability, and writes only supported corrections to the CAD model. Our depth ICP method recovers all 14 arm joint zeros and calibrates all RGB-D camera extrinsics without any calibration target. Relative to CAD, the estimated extrinsic corrections are 10.56 mm and 1.74 degrees for the left wrist, 6.33 mm and 1.25 degrees for the right wrist, and 9.81 mm and 0.929 degrees for the chest RGB-D camera. ICP point-to-plane residual is 2.09 mm. On the same injected offsets, ICP and ArUco recover all 14 joint zeros below the 0.1-degree encoder-resolution reference. On an AGIBOT A3 Ultra humanoid, four static double-support stances recover all 12 lower-limb joint-zero offsets injected with an RMS error of 0.063 degrees. The head module combines multi-camera visual odometry with legged odometry and dynamic compensation through the live ROS transform tree. Using only planar walking, it attains a mean SO(3) error of 1.061 degrees across three sequences. The best sequence reaches 0.775 degrees, competitive with iKalibr at 0.902 degrees from rich 6-DOF excitation. Rig-relative angles repeat within 0.140 degrees. Injection recovery and held-out tests validate each observable block.
### Title:
          SlugTrails: An Egocentric Benchmark for Floor Plan Localization in Large Buildings
 - **Authors:** Yunqian Cheng, Roberto Manduchi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Floor-plan-based indoor visual localization enables infrastructure-free positioning, but most methods are developed and evaluated in small residential environments unlike the large public buildings of real deployment. We introduce SlugTrails, a floor plan localization benchmark for large indoor spaces under realistic egocentric sensing: $30$ Hz Aria glasses recordings across three campus buildings and six floors ($22089$ m$^2$ of floor plan outline), CAD-derived floor plans with semantic classes and circulation space masks, and trajectories aligned into the floor plan frame using laser-surveyed anchors. One protocol covers three practical ways of gathering geometry under a limited field of view -- a single walking frame, a stationary multi-view sweep, and a walking stream with odometry -- so methods designed for different regimes are compared on the same buildings and ground truth. Evaluating five representative geometric and learned systems under their native sensing configurations, we find that stock checkpoints (official released weights) are near zero on SlugTrails (at most $0.004$ R@1m30$^{\circ}$ on walking single frames), while fine-tuning on SlugTrails improves every trainable family on all three tasks (e.g., F$^3$Loc $0.0 \rightarrow 0.141$ single-frame and $0.03 \rightarrow 0.66$ sequential), with gains compounding as observations accumulate. The same fine-tuned weights also improve cross-dataset generalization on LaMAR with no LaMAR training (sequential R@1m $0.048 \rightarrow 0.143$ for F$^3$Loc and $0.063 \rightarrow 0.127$ for UnLoc), whereas train-from-scratch on SlugTrails alone stays far below fine-tuning from stock weights -- evidence that floor plan localization is currently limited by indoor data rather than by architecture. We release the dataset, protocols, and tools at this https URL.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Learning Safe Humanoid Navigation from Reduced Order Models
 - **Authors:** William D. Compton, Zachary Olkin, Ryan Bena, Aaron D. Ames
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Research in humanoid robotics has achieved rapid progress in locomotion, and recent results have pushed the boundary on autonomous navigation. We demonstrate that a standard single-stage RL navigation pipeline struggles to scale to multi-level and multi-story terrain, limited by the difficulty of complex humanoid terrain interactions such as stairs. To overcome this challenge, we decompose the navigation problem into two pieces. First, we train a policy operating on the reduced order dynamics but with full 3D LiDAR observations to navigate complex, multi-story terrain. We then utilize this navigation knowledge to kickstart a policy operating on the full-order humanoid dynamics, with a frozen locomotion policy in the loop. Additionally, we demonstrate that applying a Poisson safety filter to the navigation policy output recovers safety in the presence of out-of-distribution obstacles, without dropping navigation success rate. We demonstrate the resulting RoM-Nav policy on a Unitree G1, accomplishing mapless multi-floor navigation covering trials with over 10m of vertical displacement and over 100m of path length. Project page with videos this https URL .
### Title:
          Dynamic-LIVO: A Dynamic-Aware LiDAR-Inertial-Visual Odometry System Using Spatio-Temporal Normals
 - **Authors:** Zhixin Zhang, Samuel Ahiwe, Matthew Hale, Liang Zhao, Pawel Ladosz
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper proposes Dynamic-LIVO, a dynamic-aware LiDAR-Inertial-Visual Odometry (LIVO) system for robust state estimation and static colored mapping in dynamic environments. Dynamic-LIVO employs Spatio-Temporal (S-T) normal analysis to identify dynamic LiDAR points and propagates the resulting classification to both LiDAR-inertial and visual-inertial updates, preventing dynamic LiDAR measurements and their associated visual observations from affecting state estimation and mapping. However, S-T normal estimation can be unreliable in newly observed and spatially sparse regions due to insufficient spatio-temporal observations. To address this issue, we introduce a time-delayed S-T normal estimation strategy that defers the classification of insufficiently constrained points and re-evaluates them as additional observations become available. This strategy improves dynamic classification reliability while preserving valid static points for map construction. Extensive experiments on public and self-collected datasets with diverse sensor configurations demonstrate that Dynamic-LIVO improves localization accuracy and produces cleaner static colored maps in challenging dynamic environments. The source code and self-collected dataset will be publicly released upon acceptance.
### Title:
          Open-vocabulary 3D object detection with promptable segmentation
 - **Authors:** Ömer Faruk Deniz, Mustafa Taha Koçyiğit
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Three-dimensional object detection for autonomous driving is dominated by detectors trained on large corpora of human-annotated 3D boxes. Such a detector learns a fixed category list, and everything outside it is invisible. This paper asks whether the task can be solved training-free and open-vocabulary. A promptable segmentation model (SAM3), queried with class names as text prompts, supplies instance masks in the vehicle's six surround-view cameras, and the masks are turned into metric 3D boxes using the geometry of the scene. The core is a controlled three-stage comparison on nuScenes in which 2D detection is held fixed and only the source of 3D geometry changes. Geometry predicted from images alone reaches 0.183 mean average precision (mAP) under the official protocol; fitting boxes from raw LiDAR points inside the same masks with training-free rules reaches 0.298 mAP / 0.348 nuScenes detection score (NDS) at zero labeling cost; borrowing supervised box geometry at inference time lifts the same detections to 0.413 mAP / 0.555 NDS, which locates the pipeline's largest deficit in measurement precision rather than 2D detection, while class confusion and confidence calibration survive that substitution. Reversing the direction, a three-state camera-witness rule built from the same masks improves a supervised LiDAR-only detector from 0.596 to 0.630 mAP, roughly half the gain of fully supervised camera fusion, with no training. A coverage analysis shows that SAM3 finds 84% of in-range objects with a correctly named mask; the classes that fail in the official metric are misnamed or geometrically unforgiving, not unseen.
### Title:
          WZPlanner: Safe End-to-End Path Planning for Autonomous Driving in Work Zones
 - **Authors:** Nishad Sahu, Changzhong Qian, Guangzhou Cai, Shounak Sural, Ragunathan (Raj)Rajkumar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Work zones alter lane geometry through temporary traffic controls and closures that may be absent from on-board maps, challenging autonomous vehicle (AV) perception and planning. Generalization is also limited by scarce public datasets with structured geometric supervision. We present WorkZonePlan, a dataset comprising 149K+ synthetic and 5K+ real-world multimodal samples with 3D annotations for lane boundaries, work zone boundaries, and driving trajectory options. It also provides 76 closed-loop CARLA scenarios replayed under three weather conditions, yielding 228 Bench2Drive-format evaluation routes. We introduce WAVE (Work-zone-focused AV data generation in Virtual and rEal Environments), a semi-automated pipeline for creating the dataset, and BoundaryFormer (BF), a transformer-based model that jointly predicts lane and work zone boundary polynomials and driving trajectories. BF uses slot attention for boundary prediction. Ablations show that a separate trajectory decoder using boundary slot features substantially improves trajectory prediction over a slot-attention-only approach. Building on this finding, BF++ offers Camera and Camera+LiDAR variants with metric ground-plane encoding, typed boundary/trajectory queries, long-range point anchors, image-space curve refinement, and conservative gated LiDAR fusion. On the 211 routes common to all four models at the evaluation freeze, BF++-Camera and BF++-Camera+LiDAR achieve Driving Scores of 63.0 and 64.4, respectively, compared with 59.3 for SimLingo and 26.1 for TransFuser++ (TF++). BF++ is 40 times smaller than SimLingo and more than 10 times smaller than TF++, while achieving higher Driving Scores. These results support jointly predicting lane boundaries, work zone boundaries, and driving trajectories as a promising direction toward safer AV operation in work zones. Code and dataset: this https URL.
### Title:
          Pose-aware Legged Robot Semantic Exploration with Omnidirectional Perception in Confined Unknown Environments
 - **Authors:** Xiaoyang Zhan, Shiyu Chen, Kenji Shimada
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic exploration in confined environments requires both environment mapping and detailed observation of target objects. For ground robots, limited sensor vertical fields of view and restricted standoff distances can leave upper object surfaces unobserved from planar viewpoints. Body tilting can improve coverage, but additional observations and posture transitions increase mission time. To address this trade-off, we present POSE, a pose-aware semantic exploration system that exploits a legged robot's intrinsic body pitch and roll with omnidirectional camera-LiDAR perception. The proposed pose-aware viewpoint sampling module selects body postures from partial object maps according to expected coverage gain, while aim-aligned execution reduces unnecessary body reorientation. Further, we introduce an object-centric viewpoint pruning strategy assisted by a vision-language model (VLM), which uses persistent observation history and bird's-eye-view (BEV) maps to reduce redundant inspection visits. The resulting semantic viewpoints are combined with geometric exploration viewpoints in a global exploration planner. Simulations show that POSE improves final target-surface coverage by 8-10 percentage points over the planar planning baseline while reducing exploration time by 17-32%, and achieves the highest mean object coverage AUC among the evaluated baselines. Real-world experiments with a legged robot carrying an omnidirectional camera-LiDAR suite in a machine shop further demonstrate the system's applicability. These results support adaptive body-posture planning for improving the coverage-efficiency trade-off in legged robot semantic exploration. We plan to release the code for community benefit in the future.
### Title:
          PIVOT: Perception-aware Independent Viewpoint Online Optimization
 - **Authors:** Yuyang Chen, Shekoufeh Sadeghi, Charuvahan Adhivarahan, Elton Lemos, Chen Wang, Sanjeev J. Koppal, Karthik Dantu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A fundamental assumption in robotic perception is that the sensor's field of view (FoV) is fixed relative to the robot body. Motion-decoupled sensors, such as gimbal-mounted cameras and MEMS-based LiDARs, instead allow sensing direction to be controlled independently at runtime. This freedom creates a computational challenge: efficiently selecting useful viewing directions online in feature-dense environments. We propose PIVOT, a lightweight iterative method that optimizes sensor viewing direction along a fixed translation trajectory to maximize feature visibility. Under a conical FoV model, visibility depends only on the optical axis, yielding a two-degree-of-freedom optimization on the viewing sphere $S^2$. Coordinate-free $SO(3)$ exponential-map updates enable efficient continuous optimization without explicit angular parameterizations or exhaustive viewing-sphere search. Monte Carlo evaluations retain 98.1--99.6% of brute-force visibility with a 76--85x speedup. Photorealistic simulation and real-world experiments further demonstrate improved visual localization robustness and practical viewpoint control on a quadruped robot.
### Title:
          AMB3R-SLAM: Kilometer-scale SLAM with Hierarchical Backend
 - **Authors:** Hengyi Wang, Lourdes Agapito
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present AMB3R-SLAM, a real-time monocular SLAM system capable of reconstructing kilometer-scale trajectories over 10k frames on a single consumer-grade GPU. Our model couples a lightweight front-end for low-latency online tracking with a hierarchical backend that progressively enforces local, mid-level, and global consistency. By avoiding bundle adjustment that relies on the static world assumption, our system naturally handles complex dynamic scenes out of the box. Furthermore, we demonstrate that our method can be extended to leverage stereo, RGB-D, and LiDAR as additional inputs. AMB3R-SLAM achieves strong camera tracking performance across 9 datasets, reducing the absolute trajectory error (ATE) of previous state-of-the-art methods on VBR and Oxford Spires by over 70%. With additional LiDAR input, our model further reduces ATE to sub-meter level on KITTI and VBR datasets.
### Title:
          Learning Reliable Parking Policies via Offline Reinforcement Learning with Quantized Action Representations
 - **Authors:** Zewei Yang, Zengqi Peng, Jun Ma
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Parking is a routine yet safety-critical task for autonomous vehicles operating in urban environments. However, cluttered and weakly structured parking spaces, compounded by the interactive uncertainty from surrounding vehicles, hinder reliable maneuver generation. To address these challenges, we develop a waypoint-level offline reinforcement learning framework for interaction-aware autonomous parking. Specifically, a dedicated parking dataset is constructed from hierarchical expert rollouts with rotational waypoint augmentation, covering both non-interactive scenarios and interactive ones. The policy is then conditioned on a compact state representation, in which LiDAR-based obstacle features are adapted to the target pose via feature-wise linear modulation. A state-conditioned tokenizer further quantizes continuous waypoint sequences into discrete action tokens, over which conservative Q-learning is performed to suppress value overestimation on poorly supported actions. Extensive closed-loop experiments are conducted in the high-fidelity CARLA simulator. The proposed framework attains the highest parking success rate among all baselines and transfers reliably to unseen parking slots.
### Title:
          Needles in a Raystack: Ultra-Sparse LiDAR Occupancy Detection for Bat Tracks
 - **Authors:** Nico Klar, Pankaj Rana, Nizam Gifary, Jakob Traub, Aamir Ahmad
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monitoring flying animals is important for understanding and protecting biodiversity, but nocturnal species such as bats are difficult to observe in the field. Using LiDAR, bat movements at night result in ultra-sparse 3D spatio-temporal data in which standard reconstruction losses tend to predict only background and miss real flight paths. We study this problem as voxel-wise occupancy detection in sensor-centric LiDAR raystacks. A lightweight 3D U-Net is proposed that preserves temporal resolution, uses skip connections for spatial detail, and combines weighted binary cross-entropy with Dice loss to handle the strong class imbalance. In real LiDAR recordings of bats over open fields, cross-checked with acoustic monitoring, a reconstruction-based 3D convolutional autoencoder baseline fails to recover foreground trajectories. In contrast, the proposed U-Net recovers sparse foreground occupancy in diagnostic experiments and produces coherent occupancy patterns along bat flight trajectories, providing a practical basis for validation-scale experiments, later clustering of flight tracks, and future integration of bat activity information into biodiversity-aware turbine curtailment strategies.
### Title:
          Implementation of Tightly-Coupled SLAM Fusion of GPS, IMU, and LiDAR for Autonomous Vehicles
 - **Authors:** Amr O. Elmehrath, Farah Khaled, Rana Nahas, Catherine M. Elias
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous vehicles depend entirely on Simultaneous Localization and Mapping (SLAM) to navigate safely in unknown environments. However, relying on a single sensory modality introduces critical failure points: LiDAR systems degrade in featureless corridors, Inertial Measurement Units (IMUs) accumulate mathematical drift, and GPS drops frequently in urban canyons. This paper presents the implementation of a tightly-coupled SLAM fusion architecture that integrates a Velodyne 3D LiDAR, a high-frequency IMU, and GPS to achieve continuous spatial awareness. Utilizing a phased development methodology, we establish a 2D baseline to validate hardware synchronization and transform geometries before upgrading to a full 3D architecture driven by FAST-LIO2. This advanced approach uses an Iterated Error-State Kalman Filter (IESKF) to process dense 3D laser points alongside continuous inertial data, eliminating motion blur at high speeds. To eradicate long-term drift, a GTSAM pose-graph optimization back-end executes multi-modal loop closures. Evaluated across simulated environments and physical deployments, the results demonstrate that tightly-coupled 3D fusion effectively overcomes individual sensor blind spots to generate highly detailed point clouds, providing the foundational High-Definition (HD) maps required for advanced downstream autonomous planners.
### Title:
          Sharp Reconstruction Bounds for Autoencoders Using the Same Forward Map
 - **Authors:** Patricia Medina, Hy P. G. Lam
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Dynamical Systems (math.DS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study reconstruction in autoencoders that apply the same forward map before and after setting the observed coordinates to zero. For equal odd input and hidden dimensions $d\geq 3$, among orientation-preserving diffeomorphisms whose Jacobian singular values lie in $[m,M]$, we show that the least uniform reconstruction-derivative error is $\max\{1-M(M-m)/2,0\}$, with affine maps attaining this sharp bound at every prescribed depth. A translated radial rotation can nevertheless reconstruct any prescribed ball exactly with singular values arbitrarily close to one, motivating additional conditions for a finite-data bound. We test this prediction on a 798,452-point terrestrial LiDAR forest scan. At input scale $0.05$, the mean theoretical bound is $0.155$, about $84\%$ of the mean normalized training error $0.185$ across four spatial regions, two depths, and three seeds. At this scale, adding one hidden coordinate reduces the mean reconstruction error below $6\times10^{-6}$.
### Title:
          Integrated Guidance and Control of a Mother-Child UAV-UGV System for Cooperative Missions
 - **Authors:** Aashish Sahu, R. Prasanth Kumar (Department of Mechanical &amp; Aerospace Engineering, Indian Institute of Technology Hyderabad, Telangana, India | Department of Artificial Intelligence, Indian Institute of Technology Hyderabad, Telangana, India)
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous recovery of a small multirotor onto a hovering multirotor carrier differs from recovery onto ground or shipborne platforms because the recovery surface is itself an actively controlled, thrust-limited aerial vehicle. This paper presents a field-validated autonomy framework for a heterogeneous rover-mothership-child system executing rover supervision, mothership transit, child deployment and sortie, autonomous return, aerial recovery, and synchronized descent. The recovery stack combines jerk-bounded reference generation, disturbance-observer-augmented planar tracking, feasibility-aware vertical control, a discrete-time barrier-based safety filter for relative vertical geometry, and communication-aware carrier-state prediction. The contribution is the coordinated system-level integration of these methods for recovery onto a hovering multirotor and its full-scale outdoor validation. The framework is implemented on a PX4-ROS 2 architecture using RTK-enabled GNSS, IMU, and barometric fusion, with mothership-side 1D lidar used only as an auxiliary near-contact cue. RTK-fixed positioning was maintained throughout testing. Across 20 outdoor cooperative missions, 17 successfully completed deployment, sortie, and recovery, giving an observed mission success rate of 85%. For successful recoveries, mean terminal-alignment time was 6.3 s, mean planar alignment error at acceptance was 0.18 m, maximum terminal planar deviation was 0.32 m within a 0.40 m capture radius, and minimum logged relative vertical separation during coupled descent was 0.41 m. Mothership planar station-keeping RMS error was 0.25 m. The three unsuccessful trials occurred at different mission stages and are analyzed separately. Results demonstrate practical autonomous aerial recovery within the tested outdoor operating envelope.
### Title:
          MILER: Semantic Mid-Level Representation for Sim-to-Real Reinforcement Learning in Unstructured Autonomous Driving
 - **Authors:** Thomas Steinecker, Denis Trescher, Alexander Bienemann, Thorsten Luettel, Mirko Maehlisch
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reinforcement learning constitutes a promising approach owing to its potential for superhuman performance and self-learned policies. However, its application to real-world autonomous driving remains scarce, particularly in unstructured environments, because of the challenges associated with sim-to-real transfer for unstructured environments. In this work, we present MILER, an end-to-end policy framework with zero-shot sim-to-real transfer. During offline training, we employ a custom semantic mid-level representation (MLR) simulator and train the policy network using reinforcement learning, with its control outputs applied directly to a bicycle model. During deployment on the real vehicle, camera and LiDAR data are processed by BEVFusion to generate a semantic bird's-eye-view representation consistent with that of the MLR simulator. The actions generated by the policy network are not applied directly to the real vehicle. Instead, we employ a trajectory-alignment strategy that enables zero-shot sim-to-real transfer of both perception and control. We extensively evaluate the proposed framework on a diverse test track comprising numerous challenges, including various obstacles, hairpin curves, velocities of up to 33.6 km/h, and off-road sections. In total, we drove 17.3 km with two different vehicles on a 3.0 km test track without human intervention, thereby demonstrating the effectiveness of our approach. Furthermore, the entire software stack runs on a Jetson AGX Orin.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          DITTO: Dexterous Interface for Transparent TeleOperation
 - **Authors:** Joaquin Palacios, Katelyn Lee, Cheng Zhang, Zhanpeng He, Matei Ciocarlie
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Collecting data for manipulation with high-DOF hands is challenging, as interfaces must capture rich hand motion while rendering the contact interactions essential for precise manipulation. Existing data collection approaches face a trade-off: teleoperation ensures deployment consistency but lacks force feedback, while handheld (in-the-wild) systems provide natural force transparency but introduce a visual embodiment gap at deployment. We present DITTO, a Dexterous Interface for Transparent TeleOperation, which resolves this through the anatomically informed co-design of a dexterous 7-DOF robotic hand and a kinematically equivalent motorized exoskeleton. A 1-to-1 actuator mapping between the exoskeleton and robotic hand enables handheld (in-the-wild) data collection and bilateral teleoperation with joint-level force feedback unified in a single platform. We demonstrate that the DITTO exoskeleton spans the operator's natural index-to-thumb workspace, and showcase DITTO's dexterous capabilities via learned policies on contact-rich tasks.
### Title:
          Epic: Efficient Programming Paradigm for In-Storage Computing
 - **Authors:** Yuyue Wang, Zhenyu Zhang, Glenn Reinman, Huaicheng Li
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Programming Languages (cs.PL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In-storage computing (ISC) reduces host--storage data movement by executing computation inside computational storage devices (CSDs). For multi-stage applications, realizing these benefits requires coordinating data placement, I/O--compute overlap, and device-resident state across the workflow, yet existing interfaces lack a unified abstraction for these decisions. We present Epic, an NVMe-based ISC stack that provides this abstraction by capturing data residency and lifetime in the program: location types declare logical residency, dataflow derives lifetimes for intermediate values and operation state within an invocation, and a keep primitive extends selected state across invocations. These semantics expose the complete offloaded workflow as a located, stateful dataflow. A storage-aware compiler transforms this workflow, performs movement-aware logical mapping and fusion, and exposes I/O--compute overlap; a runtime completes the plan using execution-time information, asynchronously binding work to physical resources and managing device-resident state. Across 12 file-scanning, database, and machine learning workloads, Epic is 1.6$\times$ faster on average than the strongest of five prior ISC systems, while achieving 4.2$\times$ speedup on average and up to 16.1$\times$ over the corresponding host baselines, and reducing application-side code by up to 14$\times$ in our implementations.
### Title:
          Why Pretraining Fails to Share Cross-Lingual Knowledge
 - **Authors:** Adam Gaber, Uriel Dolev, Elisabeth Fittschen, Bobby Cheng, Yuval Marton, Leshem Choshen
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) have made remarkable progress in the processing and modeling of many languages. Yet, unlike human multilinguals, they exhibit surprisingly limited cross-lingual knowledge transfer. While this limitation is well documented, its origins during multilingual training remain unclear. We pretrain 360M- and 7B-parameter LLMs and show that poor cross-lingual knowledge generalization emerges during pretraining and persists under standard interventions. To isolate its cause, we employ a controlled bilingual pretraining setting using two copies of the same language, sharing identical text and token segmentation, but mapped to disjoint token spaces. We find that disjoint tokens alone are enough to induce knowledge compartmentalization, even between identical copies of the same language, establishing disjoint token spaces as a fundamental barrier to cross-lingual knowledge generalization. Guided by this understanding, we suggest mapping languages into a shared token space by simple word-wise translation and find it substantially improves cross-lingual knowledge generalization, recovering up to 12.6\% of native-language learning efficiency --- 14$\times$ the baseline.
### Title:
          Dynamic-LIVO: A Dynamic-Aware LiDAR-Inertial-Visual Odometry System Using Spatio-Temporal Normals
 - **Authors:** Zhixin Zhang, Samuel Ahiwe, Matthew Hale, Liang Zhao, Pawel Ladosz
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper proposes Dynamic-LIVO, a dynamic-aware LiDAR-Inertial-Visual Odometry (LIVO) system for robust state estimation and static colored mapping in dynamic environments. Dynamic-LIVO employs Spatio-Temporal (S-T) normal analysis to identify dynamic LiDAR points and propagates the resulting classification to both LiDAR-inertial and visual-inertial updates, preventing dynamic LiDAR measurements and their associated visual observations from affecting state estimation and mapping. However, S-T normal estimation can be unreliable in newly observed and spatially sparse regions due to insufficient spatio-temporal observations. To address this issue, we introduce a time-delayed S-T normal estimation strategy that defers the classification of insufficiently constrained points and re-evaluates them as additional observations become available. This strategy improves dynamic classification reliability while preserving valid static points for map construction. Extensive experiments on public and self-collected datasets with diverse sensor configurations demonstrate that Dynamic-LIVO improves localization accuracy and produces cleaner static colored maps in challenging dynamic environments. The source code and self-collected dataset will be publicly released upon acceptance.
### Title:
          Wideband Directional $\mathcal{H}^2$-Matrix Compression for the Electric Field Integral Equation with Geometry-Adaptive Cluster Trees
 - **Authors:** Joshua M. Tetzner, Simon B. Adrian
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present an efficient wideband construction of directional $\mathcal{H}^2$-matrices for the electrical field integral equation that, in contrast to existing constructions, supports not only box trees but also geometry-adaptive cluster trees. To accommodate geometry-adaptive cluster trees, we determine the number of directions from the electrical size of each cluster (instead of the level of a box tree), construct the directions using Spherical-Fibonacci points, and establish a hierarchy between the direction sets of a cluster and its children through an angular nearest-neighbor mapping. We construct the nested directional representation using the incomplete adaptive cross approximation, for which we introduce a robustified tree-mimicry pivoting strategy that prevents premature convergence for block-structured matrices arising from certain geometries and meshes. Numerical results demonstrate that the proposed approach achieves the desired accuracy, requires no more storage than the octree-based construction and substantially less when the geometry or discretization is poorly matched to octree clustering, and exhibits the expected $\mathcal{O}(N\log N)$ scaling for high-frequency problems.
### Title:
          Pose-aware Legged Robot Semantic Exploration with Omnidirectional Perception in Confined Unknown Environments
 - **Authors:** Xiaoyang Zhan, Shiyu Chen, Kenji Shimada
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic exploration in confined environments requires both environment mapping and detailed observation of target objects. For ground robots, limited sensor vertical fields of view and restricted standoff distances can leave upper object surfaces unobserved from planar viewpoints. Body tilting can improve coverage, but additional observations and posture transitions increase mission time. To address this trade-off, we present POSE, a pose-aware semantic exploration system that exploits a legged robot's intrinsic body pitch and roll with omnidirectional camera-LiDAR perception. The proposed pose-aware viewpoint sampling module selects body postures from partial object maps according to expected coverage gain, while aim-aligned execution reduces unnecessary body reorientation. Further, we introduce an object-centric viewpoint pruning strategy assisted by a vision-language model (VLM), which uses persistent observation history and bird's-eye-view (BEV) maps to reduce redundant inspection visits. The resulting semantic viewpoints are combined with geometric exploration viewpoints in a global exploration planner. Simulations show that POSE improves final target-surface coverage by 8-10 percentage points over the planar planning baseline while reducing exploration time by 17-32%, and achieves the highest mean object coverage AUC among the evaluated baselines. Real-world experiments with a legged robot carrying an omnidirectional camera-LiDAR suite in a machine shop further demonstrate the system's applicability. These results support adaptive body-posture planning for improving the coverage-efficiency trade-off in legged robot semantic exploration. We plan to release the code for community benefit in the future.
### Title:
          A Unified Evaluation Framework for Trustworthy Large Language Models, Agentic AI, and Multimodal Systems
 - **Authors:** Shaina Raza, Ahmed Y. Radwan, Imran Liaquat, Kathryn Hume
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Benchmark scores alone provide an incomplete basis for assessing the trustworthiness of modern artificial intelligence systems. Large language models (LLMs), agentic systems, and multimodal models (MLLMs) require different forms of assessment, yet their evaluation evidence must remain interpretable for development and oversight. We propose a unified framework that connects output-level, trajectory-level, and cross-modal assessment through eight trustworthiness dimensions: capability, robustness, safety, fairness, transparency, governance, oversight, and efficiency. The framework preserves system-specific metrics while mapping native measurements to common performance bands, accompanied by uncertainty estimates and traceable evidence. A meta-evaluation layer examines the validity, reliability, and reproducibility of the evaluation itself. Multidimensional profiles expose strengths and weaknesses, while safety-critical overrides prevent aggregate scores from masking critical failures. Mappings to governance frameworks, international standards, and European Union regulatory requirements connect technical assessment with oversight needs. The framework provides a structured basis for assessing both system performance and the credibility of the evidence supporting it, with empirical validation across deployment contexts remaining an essential next step.
### Title:
          SLAMSqueezeBench: Comparing SLAM Systems under Resource Constraints
 - **Authors:** Mohamed Hefny, Karthik Dantu, Steven Y. Ko
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Simultaneous localization and mapping (SLAM) is one of the services running on an autonomous robot. It is typically run to assist other tasks such as planning, manipulation, etc. All these tasks are run on edge hardware and are subject to severe resource constraints. However, most SLAM systems are built and tested in isolation, and their performance is reported as if they are the only task running on a system. We observe that existing benchmarks lack a common mechanism for comparing SLAM systems under realistic resource constraints. To address this limitation, we have developed SLAMSqueezeBench, a framework that allows testing of SLAM systems under realistic workloads on edge hardware. It does so by imposing constraints on compute and memory resources available for the SLAM system during execution. It also simulates realistic camera frame acquisition with frame drops when a finite buffer is full. Using SLAMSqueezeBench, we compare nine SLAM systems spanning classical systems, learning-based systems, and approaches for Gaussian splatting. Our testing framework will be available for use by the community upon publication.
### Title:
          PerSeM: Persistent Semantic Memory for Long-Horizon Open-Vocabulary UAV Mapping
 - **Authors:** Saurbh Singh Jamwal, Ganesh Ramakrishnan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open-vocabulary segmentation enables rich semantic perception for UAVs, but frame-wise predictions can remain temporally inconsistent across repeated observations and changing viewpoints. We present PerSeM, a training-free persistent semantic memory framework for long-horizon open-vocabulary UAV mapping. PerSeM associates frame-wise semantic observations with persistent world-space voxels and constructs a majority-based semantic memory, which is conservatively refined through history-preserving spatial refinement, trust-aware replay, and context-guided verification. Experiments on the Forest and UAVScenes benchmarks show that persistent 3D memory provides substantial gains in semantic correctness and temporal stability over frame-wise predictions. Beyond this strong persistent-memory baseline, PerSeM provides consistent additional improvements, improving both semantic accuracy and temporal stability across all five evaluated UAVScenes sequences. Analysis using regions identified independently of the final PerSeM predictions further shows that these gains are concentrated in semantically difficult and temporally unstable regions, where majority-based memory is most likely to remain uncertain. These results demonstrate that persistent 3D aggregation provides a strong foundation for long-horizon semantic mapping, while conservative refinement of uncertain memory states can provide additional improvements without retraining or additional neural-network inference.
### Title:
          A generalization of the map $χ$
 - **Authors:** Xiutao Feng, Qiang Wang, Jingyi Yu, Anpeng Zhang
 - **Subjects:** Subjects:
Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The mapping $ \chi_n:\mathbb{F}_2^n \to \mathbb{F}_2^n$ defined by $y=\chi_n(x)$ with $y_i = x_i + x_{i+1}x_{i+2} + x_{i+2}$, where the indices are computed modulo $n$, has been widely studied for its application in lightweight cryptography. In this paper, we generalize this mapping and completely characterize all these shift-invariant permutations of algebraic degree $2$.
### Title:
          Semantic Layer Induction from Raw Telemetry via Hierarchical LLM and RAG Abstraction
 - **Authors:** Yuanzhe Jia, Ali Anaissi
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Information Retrieval (cs.IR); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern applications generate massive volumes of raw telemetry data, but translating those noisy, heterogeneous event streams into actionable business insights remains a fundamental challenge. Data engineers and analysts expend substantial effort reconciling semantic discrepancies, hand-crafting parsing logics, and maintaining fragile mappings between raw data and business KPIs. In this paper, we present an end-to-end framework that fully automates the construction of a business semantic layer from application raw logs. Our approach introduces a two-stage semantic abstraction: first, high-level business features are identified via LLM inference augmented with domain-specific industry knowledge; second, fine-grained business nodes are derived through a structured pipeline comprising data refinement, hybrid retrieval, multi-stage filtering, semantic clustering, and canonical naming. Evaluation on production-scale telemetry demonstrates that our system improves human-assessed semantic quality from 50 to 80+ on a 100-point scale, reduces maintenance effort by 80%, filters out 74% of noise, and achieves 0.87 Cohen's kappa via an integrated LLM-as-Judge evaluation, enabling continuous, scalable quality assurance. Overall, our work distinguishes itself from prior work by addressing the novel problem of business semantic layer induction from raw telemetry, operating without labeled training data or manual rule engineering.
### Title:
          VAST: V2X/Dynamic Map-Aware Autonomous Driving Systems Validation Toolchain
 - **Authors:** Shunsuke Ito, Takuya Azumi
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cooperative autonomous driving in the IoT-to-Edge-to-Cloud continuum requires system-level validation across vehicles, infrastructure sensors, edge-side Dynamic Map services, and in-vehicle autonomous-driving stacks. This paper presents VAST, a V2X/Dynamic Map-aware validation toolchain that connects Scenic, Scenario Simulator v2, AWSIM, Autoware, and SIM-LDM. VAST does not introduce a new search algorithm; instead, it addresses interoperability challenges, including Lanelet2-to-Scenic mapping, ROS 2-based co-simulation through SS2, Dynamic Map object injection into Autoware, and collection of TTC, PET, collision, timeout, and performance measurements. In occluded-intersection scenarios, Lanelet2-compatible constrained sampling increases the edge-case discovery rate from 40.0% to 80.0% and reduces the average time per discovered edge case from 259.7 s to 110.4 s. Under the same generated scenario distribution, Dynamic Map availability reduces the collision rate from 78.0% to 40.0% and increases non-collision outcomes from 22.0% to 60.0%, with statistically significant TTC/PET shifts. A throughput study with 1-16 NPCs shows that sampling remains below 0.1 s, whereas AWSIM/Autoware execution and restart overhead dominate runtime. These results position VAST as a practical validation infrastructure for cooperative autonomous-driving CPSs.
### Title:
          Benchmarking MLLMs via Cognitive Expected Scene Graph for Safety-Critical Visual Negation Understanding
 - **Authors:** Zhiyun Jiang, Hanyong Wang, Binbin Liang, Yu Xie, Menglong Yang, Wei Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 True machine intelligence requires transcending passive pixel registration to master top-down functional reasoning over absent information via visual negation understanding. However, unconstrained visual negation paradigms remain overly open-ended, and pervasive affirmation bias causes both existing Multi-Modal Large Language Models (MLLMs) and evaluation metrics to fail under negative semantics. To solve these intertwined challenges systematically, we first anchor the boundaries of negation reasoning within specific cognitive goals. Specifically, by focusing on safety as a highly pragmatic and critical cognitive dimension, we define the task of \textbf{S}cene \textbf{N}egation \textbf{U}nderstanding under \textbf{S}afety Cognition (\textbf{SNUS}). Under this framework, we construct a high-fidelity negative caption dataset mapping dense assertions of localized hazards. Concurrently, we propose the Cognitive Expected Scene Graph (CESG) Score, a structure-grounded, polarity-aware evaluation metric. Extensive experiments demonstrate that while current models struggle on the task, traditional metrics completely collapse under semantic reversals. Conversely, our framework delivers a solid benchmark for SNUS, providing a rigorous foundation to advance risk-aware situational comprehension and counterfactual cognition.
### Title:
          Online Material-Labeled Environment Reconstruction via Bayesian Multipath Attribution for Low-Altitude ISAC
 - **Authors:** Meihui Liu, Shu Sun, Ruifeng Gao, Qiuming Zhu
 - **Subjects:** Subjects:
Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Environment reconstruction for low-altitude integrated sensing and communications (ISAC) has largely focused on geometry-centric maps, overlooking material-dependent propagation effects. Material-labeled reconstruction is therefore a key step toward propagation-aware mapping, enabling more physically grounded channel prediction and uncrewed aerial vehicle (UAV) networking. However, constructing such maps from wireless multipath observations is challenging in outdoor multi-building scenarios because multipath components (MPCs) from different facades are mixed, path-to-facade attribution is uncertain, and UAV measurements arrive sequentially under time-varying observation geometries. To address these challenges, we propose a unified online probabilistic framework that represents each reflecting facade as a virtual anchor (VA) and couples Bayesian VA localization, multipath attribution, and material inference. The Bayesian front end estimates facade-level geometry and computes soft MPC-to-VA attribution probabilities using a speculardiffuse likelihood model, thereby accounting for both dominant specular paths and diffuse surface-interacted components. These attribution probabilities are used to construct attribution-aware MPC representations, which are aggregated in a VA-centric manner and mapped by a material inference network to facadelevel material evidence. The resulting evidence is recursively fused through an online Bayesian update to produce stable material posteriors and material-labeled environment maps. Ray-tracing simulations in a representative urban street scenario show that the proposed method substantially outperforms a no-attribution baseline, achieves 93.75% final facade-level material accuracy on a held-out UAV trajectory, and maintains accurate VA-based facade localization.
### Title:
          Feeling Terrain Before Crossing: World Models for Off-Road Navigation
 - **Authors:** E-In Son, Dong-Wook Kim, Ji-Hoon Hwang, Kangsun Lee, Jisung Bae, Jung-Taak Kim, Seung-Woo Seo
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Navigation world models plan by foresight, predicting the future that each candidate action sequence produces and selecting the best, rather than mapping observations to actions directly. Unlike urban settings where a predicted scene is a sufficient proxy, off-road navigation hinges on the robot--terrain interaction, so the prediction must cover not only what the camera will see but what the robot will feel. However, existing scene-focused models do not predict how much the robot will slip, tilt or shake along a planned trajectory. Proprioception captures these dynamics directly and, when used as input, improves the prediction of the physical future. We present Feel-WM, the first off-road navigation world model that conditions on proprioception and predicts what the robot will feel alongside what the camera will see. The physical future takes the form of a future proprioceptive state and a failure risk, both learned from the robot's own experience without human labels. The planner rolls out the physical future alongside the scene and weighs the predicted failure risk against goal similarity in a separable score. Experiments on real off-road data and in simulation demonstrate that Feel-WM outperforms visual-only navigation world models in open-loop planning and closed-loop rough-terrain navigation across wheeled and legged platforms. Deployed on a Husky on mountain trails, Feel-WM plans onboard, predicts rough ground ahead and steers around it, completing courses that an end-to-end policy fails.
### Title:
          How Far Can Sub-3B Open Language Models Go in Zero-Shot Essay Scoring on an 8 GB Consumer GPU?
 - **Authors:** Nguyen Dung Son, Dang Quang Minh, Nguyen Huu Loi, Truong Viet Vu, Nguyen Thai Anh
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Zero-shot essay scoring with large language models is usually demonstrated with proprietary API models, yet the settings where automated scoring is most needed, such as public schools grading thousands of essays under strict privacy rules, are often those where sending student writing to a third-party API is unacceptable. We ask how much capability survives when the model must be a sub-3B open model running fully locally in FP16, with a controlled study of four instruction-tuned models from two families (Qwen2.5 at 0.5B/1.5B/3B, SmolLM2 at 1.7B) on all eight ASAP-AES prompts on a single 8 GB consumer GPU, with bootstrap confidence intervals, Holm-corrected paired tests, and deployment-realistic variants of the key design choices. Three findings emerge. (i) Rubric-decomposed prompting beats holistic prompting for every model under batch min-max aggregation (though Qwen2.5-3B drops significantly on one prompt), and under mean aggregation two unrelated families land within 0.01 at the 1.5-1.7B scale. (ii) Mapping trait scores into the prompt range is fragile to grader calibration: one model compresses traits into a narrow low band (2-4 on 0-10) and naive mean aggregation collapses, while the min-max normalization of Multi-Trait Specialization repairs it (macro QWK 0.204 to 0.388) and stays within 0.03 when its statistics are frozen on 30 held-out essays. (iii) Signed error falls with essay length in eleven of twelve configurations, opposite to the verbosity bias reported for large LLM judges; normalized rubric decomposition largely flattens this slope for well-calibrated models. We anchor results honestly: the best local configuration (0.388) remains far below both the human inter-rater ceiling (0.769) and a length-only baseline (0.523), so we position sub-3B local models strictly for formative, human-supervised feedback.
### Title:
          Implementation of Tightly-Coupled SLAM Fusion of GPS, IMU, and LiDAR for Autonomous Vehicles
 - **Authors:** Amr O. Elmehrath, Farah Khaled, Rana Nahas, Catherine M. Elias
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous vehicles depend entirely on Simultaneous Localization and Mapping (SLAM) to navigate safely in unknown environments. However, relying on a single sensory modality introduces critical failure points: LiDAR systems degrade in featureless corridors, Inertial Measurement Units (IMUs) accumulate mathematical drift, and GPS drops frequently in urban canyons. This paper presents the implementation of a tightly-coupled SLAM fusion architecture that integrates a Velodyne 3D LiDAR, a high-frequency IMU, and GPS to achieve continuous spatial awareness. Utilizing a phased development methodology, we establish a 2D baseline to validate hardware synchronization and transform geometries before upgrading to a full 3D architecture driven by FAST-LIO2. This advanced approach uses an Iterated Error-State Kalman Filter (IESKF) to process dense 3D laser points alongside continuous inertial data, eliminating motion blur at high speeds. To eradicate long-term drift, a GTSAM pose-graph optimization back-end executes multi-modal loop closures. Evaluated across simulated environments and physical deployments, the results demonstrate that tightly-coupled 3D fusion effectively overcomes individual sensor blind spots to generate highly detailed point clouds, providing the foundational High-Definition (HD) maps required for advanced downstream autonomous planners.
### Title:
          Structured Four-Stage Legal Translation: From Natural-Language Traffic Rules to PROLOG
 - **Authors:** May Myo Zin, Wachara Fungwacharakorn, Ken Satoh, Katsumi Nitta
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traffic regulations are written for human interpretation and therefore rely on shared background knowledge and flexible phrasing, which inherently introduce ambiguity, context dependence, and semantic underspecification. These linguistic characteristics conflict with the precision required by computational reasoning engines such as Prolog, which demand explicit logical structure. This study evaluates two baseline translation approaches, Natural Language to Prolog ($NL\rightarrow Prolog$) and Logical English to Prolog ($LE\rightarrow Prolog$), and introduces a new reasoning-guided translation framework called Structured Four-Stage Legal Translation ($S4L\rightarrow Prolog$). The proposed S4L framework performs semantic role extraction, scene completion, logical mapping, and Prolog rule generation within a single guided prompt, enabling direct translation of raw traffic rules into executable logic without human intervention. A benchmark consisting of twenty real-world traffic rules was used to evaluate each approach in terms of syntactic validity, semantic correctness, and logical completeness. $S4L\rightarrow Prolog$ achieves the highest accuracy, correctly formalizing 75 percent of the rules, while $NL\rightarrow Prolog$ reaches 60 percent and $LE\rightarrow Prolog$ reaches 55 percent. Qualitative analysis further shows that S4L captures implicit causal relations, deontic modality, and exception structure more reliably than the baselines. These results demonstrate that structured reasoning prompts can substantially improve the reliability of natural-language-to-logic translation for legal and safety-critical applications.
### Title:
          STR-Agent: An LLM-Driven Agent for QoS-Aware Routing in LEO Satellite Networks
 - **Authors:** Bowen Lu, Mugen Peng, Yaohua Sun, Hongyu Wang, Kerui Guo, Wenjia Xu
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LEO satellite networks feature dynamic topologies, time-varying links, and diverse service requirements, which make conventional routing schemes difficult to support fine-grained quality-of-service (QoS) provisioning. Existing studies mainly optimize routing over network states with predefined objectives, but rarely address the practical challenge of translating unstructured natural-language service requests into adaptive routing decisions. To bridge this gap, we propose STR-Agent, an LLM-driven framework for QoS-aware routing in LEO satellite networks. The key innovation of STR-Agent lies in unifying intent perception, tool-based execution, experience accumulation, and reflection-based policy adaptation within a single agent architecture. Specifically, the Perception Module converts natural-language requests into structured routing semantics, while the Reflection Module dynamically adjusts the service-to-routing-policy mapping according to real-time congestion conditions and historical routing outcomes, rather than relying on a fixed routing objective. In addition, we develop a specialized perception model, and construct a domain-specific supervised fine-tuning dataset for LEO service understanding. Simulation results in a Walker-Delta constellation show that STR-Agent significantly outperforms conventional baselines: it reduces end-to-end delay by up to 60% compared with DQ-Dijkstra, improves average intent-understanding accuracy from 45.4% to 92.45% after supervised fine-tuning, and the Reflection Module further reduces the delay by 120 ms at 600 Mbps. These results demonstrate the potential of LLM-driven agent architectures to enable service-aware and adaptive QoS routing in future LEO satellite networks.
### Title:
          EliGSiR: Continual RGB-D Mapping with Gaussian Splatting under Bounded Compute
 - **Authors:** Björn Ellensohn, Elmar Rueckert, Christian Rauch
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Conventional 3D Gaussian Splatting assumes a closed set of observations and long optimization schedules. Continual RGB-D mapping in contrast poses the problem that new observations arrive online, while previously reconstructed regions must be preserved. We present EliGSiR (Evidence-guided Load-adaptive Incremental Gaussian Splatting with Image Replay), a continual Gaussian mapper that controls how the available optimization budget is used as the reconstruction evolves. Map-Guided View Scheduling filters redundant incoming views and reconsiders retained views according to the current state of the map. Load-Adaptive Fidelity adjusts supervision resolution to the current mapping load instead of following a fixed resolution schedule. Targeted Geometry Growth separates depth supervision from Gaussian creation and adds geometric capacity only where repeated RGB-D observations indicate missing or misplaced structure. Together, these mechanisms adapt which views are optimized, how much image detail is used, and where the representation grows while mapping remains active. We evaluate EliGSiR on Replica, TUM RGB-D, ScanNet++, and real RGB-D sensor sequences, considering both the final reconstruction and the map available throughout acquisition. On TUM RGB-D fr3/long_office_household, EliGSiR reaches 21.52 dB with the same ground-truth mapping poses used by the controlled baselines, compared with 19.42 dB for SplaTAM. In the tracked-pose comparison, EliGSiR with live ORB-SLAM3 poses reaches 23.02 dB in 155.5 s, compared with 20.10 dB in 230.9 s for CaRtGS using its native tracker. We further evaluate reconstruction throughout acquisition and show how EliGSiR adaptive view scheduling, supervision fidelity, and geometry growth improve the use of the available mapping budget.
### Title:
          Welfare-Opaque Income: Taxation under AI-Agent Delegation
 - **Authors:** Yukun Zhang, Kemu Xu, Yishen Chen
 - **Subjects:** Subjects:
Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study income taxation when an AI agent implements economically relevant choices through a rule hidden from the government. Alongside unobserved productive ability, this hidden preference-to-execution mapping creates \emph{double unobservability}: the same observable tax-base response can carry different welfare consequences. We call the resulting income \emph{welfare-opaque}. Our constructions show that tax-base statistics can coincide while reform welfare effects differ, even when mechanical welfare weights are identical. We derive an optimal-tax condition that adds a response-weighted execution wedge to the familiar sufficient statistics. A higher marginal rate gains a corrective benefit under local over-execution and an additional cost under local under-execution. Observing the wedge identifies the welfare effect of a marginal reform at the prevailing schedule; bounds on it deliver bounds on that effect. A controlled laboratory compares 4,500 model runs across five AI engines. Faithful delegation selects the score maximizer in essentially all runs. Conflicted objectives produce heterogeneous responses: Claude largely preserves the score maximizer, GLM moves predominantly downward, and GPT-mini and Qwen show concentrated lower-tail increases. Qwen also makes substantial downward adjustments. Different engines locate their departures at different points and in different directions of the designed distribution. Explicit scores align model rankings; formula-based objective instructions yield more uneven agreement. Qwen shows a clear positive tax-by-objective interaction, but its direction does not generalize across engines and the pooled sign depends on its inclusion. The analysis identifies execution information as a complement to conventional tax-base statistics.
### Title:
          Spotlights: Discovering Improvement Opportunities in Software Repositories
 - **Authors:** Udi Barzelay, Ophir Azulai, Idan Friedman, Inbar Shapira, Foad Abo Dahood, Yevgeny Burshtein, Orit Prince, Michael Soloveitchik, Oshri Naparstek, Roi Pony, Tal Drory, Michael Factor
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Coding agents and evolutionary code-search systems can improve implementations once a target and evaluation criterion have been specified. Applying these methods to an existing software repository raises an earlier question: which implementation choices are worth investigating for a high-level engineering objective? We introduce \emph{optimization-opportunity discovery}, the repository-level task of identifying candidate source regions, explaining how they relate to the objective, and proposing possible changes. The task takes as input a repository, an engineering objective, and optional runtime evidence such as offline telemetry observations or profiles. It does not require the user to specify a defect, bottleneck, or code location. We present \emph{Spotlights}, a system that performs this task through logical repository mapping, successive agent reviews, and optional research linking candidates to relevant techniques. We evaluate Spotlights across model serving, document retrieval, blockchain ordering, and document processing. Across three cases, it recovers seven of nine expert-selected targets. In the reliability study, 70\% of the top ten candidates meet the stated correctness and severity thresholds. Across five repeated retrieval runs, 73.6\% of candidate occurrences have a matching source region in all five runs. Spotlights also rediscovers the target of a withheld retrieval optimization and connects it to a relevant tiling technique. In an implementation study, a discovered change reduces end-to-end page-processing runtime by 10.6\% while preserving measured output quality. These results establish optimization-opportunity discovery as a distinct and empirically evaluable step between a broad engineering objective and subsequent implementation and validation.
### Title:
          RawSLAM: Online HDR Gaussian SLAM from Linear Radiance
 - **Authors:** Marina Orozco González, Luis Merino
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current dense visual SLAM systems rely almost exclusively on 8-bit tonemapped Low Dynamic Range (LDR) inputs, limiting their robustness in extreme lighting where shadows and highlights trigger tracking drift and mapping collapse. Conversely, existing raw and High Dynamic Range (HDR) reconstruction pipelines operate strictly offline. They depend on Structure-from-Motion preprocessing and are not suited for large inter-frame motion. We present, to the best of our knowledge, the first online Gaussian SLAM framework that tracks and maps directly on single-exposure 16-bit linear HDR imagery. Our method rests on three core components: an architecture-agnostic HDR Gaussian Splatting module featuring an MLP-free logarithmic parameterization of Gaussian color features; a Reinhard range-compressed photometric objective; and structure-guided spatial gradient weighting. Combined, these components allow our approach to outperform a direct HDR adaptation of MonoGS in both trajectory and reconstruction accuracy, while rendering natively in linear scene radiance for post-rendering processing. The same formulation runs unchanged on standard 8-bit inputs, roughly halving the MonoGS baseline error. Furthermore, our HDR Gaussian module transfers seamlessly to SplaTAM, Gaussian SLAM, and DROID-W, eliminating all tracking failures these systems suffer on challenging illumination sequences. To enable this research, we introduce RawSLAM: a dataset of 10 real-world indoor sequences featuring 16-bit RAW imagery, aligned depth, IMU measurements, and external OptiTrack poses. Code and dataset will be made publicly available soon.
### Title:
          Semantic SLAM in Precision Agriculture using Bayesian Inference
 - **Authors:** Ruben Beumer, Sander Doodeman, René van de Molengraft, Duarte Antunes
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a real-time semantic world modeling framework specialized for precision agriculture using autonomous robots. The framework combines probabilistic mapping of objects and their semantic attributes, updated through Bayesian inference, with a graph-based Simultaneous Localization and Mapping (SLAM) approach implemented using $g^2o$, a general framework for graph optimization. This integration enables accurate mapping and localization without relying solely on GPS. By leveraging semantic information such as plant type, size, and health, the robot can perform tasks while mapping and localizing itself within a field of crops. The proposed framework was validated through Gazebo simulations and physical experiments on an indoor field with artificial plants using Boston Dynamics' robot dog Spot. A YOLOv8n object detection model was trained to extract object and semantic data from depth camera observations. These simulations and experiments demonstrate that the system can successfully perform real-time mapping of up to at least 400 plants.
### Title:
          Custom PX4 firmware for autonomous hybrid aerial-marine missions
 - **Authors:** Andrea Capuozzo, Fabio Ruggiero, Vincenzo Lippiello
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mapping and monitoring aquatic environments can benefit from hybrid aerial-amphibious drones able to combine flight and water-surface navigation within the same mission. This paper presents a PX4 firmware extension for such platforms, introducing manual and autonomous marine navigation modes integrated with the standard PX4 mission pipeline and QGroundControl interface. The proposed framework preserves existing flight functionalities and safety mechanisms while enabling unified planning and execution of hybrid aerial-marine missions with differentiated aerial and marine waypoints. Simulated case studies validate the implementation and demonstrate stable surface navigation under calm and wavy conditions.
### Title:
          Unifying Models of Intergroup Hostility in Online Discourse
 - **Authors:** Patrick Gerard, Julia Mendelsohn, Kristina Lerman
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Social and Information Networks (cs.SI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hostile rhetoric toward social groups can normalize exclusion and justify mistreatment, as well as contribute to rising polarization and political violence. Efforts to moderate hostile rhetoric in online speech draw on foundational theories in social and moral psychology, and political science. However, these theories were developed largely in parallel, often propose different and sometimes conflicting accounts of how hostility develops, and have rarely been tested against each other in real discourse. The result is a fragmented understanding of the rhetorical mechanisms of hostility, without a clear sense of how they appear, and relate to each other, in real-world discourse. Using 2.86 million posts from TikTok, Truth Social, and Twitter/X during the 2024 U.S. presidential election, we model the mechanisms of six foundational theories of intergroup hostility -- boundary construction, threat construction, scapegoating, negative evaluation, dehumanization, and action orientation -- within a common empirical framework to recover the broader organization of intergroup hostility rhetoric. Structurally, we find that boundary construction and threat construction anchor the system; temporally, we find that these mechanisms tend to follow a regular ordering: boundary construction, derogation, and action orientation tend to appear early; dehumanization and threat construction later; scapegoating latest. Mapping how these theoretical frameworks actually manifest in discourse bridges longstanding divisions across social science traditions and presents computational social science with a clearer empirical foundation for modeling intergroup hostility rhetoric beyond single-label detection.
## Keyword: localization
### Title:
          EvoSherlock: Towards Agentic Lifelong Evolution for Unseen Long-Tailed Security-Critical Events in Videos
 - **Authors:** Zixin Fan, Jiahong Lu, Changsheng Zheng, Yu Hong, Jingjing Wang
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing Security-oriented Video Understanding (SVU) systems assume a \emph{closed world}, \ie static category sets, abundant labels, and the premise that all event types are known upfront. Real-world security-critical events break these assumptions: they follow long-tailed distributions, new types emerge continuously, and critical security events may offer only a few samples. We formalize this gap as \textbf{Lifelong Evolving Task for Long-Tailed Security-Critical Events in Videos ({\boldmath$L^2$}-SCE)}, a new task that requires VLMs to continually classify and temporally localize newly emerging security-critical events from scarce samples without forgetting previously learned events. Furthermore, \task reveals two critical challenges: (1)~\textbf{Intra-Event Scarcity}, where extreme data scarcity may weaken both classification and temporal localization for new events, and (2)~\textbf{Inter-Event Interference}, where cross-event feature entanglement and representation drift may strengthen catastrophic forgetting. On this basis, we propose \textbf{\method}, a causal-enhanced approach orchestrated end-to-end by an \textbf{Agentic Controller} with self-reflective closed-loop control, which includes two core modules: the Intra-Event \textbf{C}ausal \textbf{V}ideo \textbf{G}eneration module (\textbf{CVG}) and the Inter-Event \textbf{C}ausal \textbf{D}ecoupling and \textbf{A}lignment module (\textbf{CDA}), to address the above two challenges, respectively. Especially, this paper constructs a \task dataset to simulate real-world incremental conditions. Extensive experiments on our benchmark demonstrate the advantages of \method over several advanced baselines. These justify the importance of the proposed \task and the effectiveness of \method in classifying and temporally localizing emerging security-critical events from scarce samples.
### Title:
          REACT: A Fully Spiking State-Space Model for Real-Time Event-Driven Temporal Perception
 - **Authors:** Geoffroy Keime, Nicolas Cuperlier, Benoit R. Cottereau
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robotic systems operating in dynamic environments require visual perception that evolves continuously with the incoming sensory stream. Event cameras provide microsecond temporal resolution and asynchronous sensing, but most learning-based methods accumulate events into frames or temporal bins, introducing an integration delay that can limit fast reaction. Here we propose REACT, a fully spiking state-space model for event-driven temporal perception that processes raw events one by one, without temporal accumulation. REACT uses a complex-valued spiking neuron, C-SiLIF, whose continuous-time dynamics are driven by the physical inter-event interval, allowing its internal state to evolve at the temporal resolution of individual events. We evaluate REACT on gesture recognition and time-to-collision (TTC) estimation from full-field event streams, without a target bounding box or localization input. On EvTTC, REACT achieves a 9.59% relative TTC error with 4.6 ms end-to-end inference latency, within 0.15 percentage points of the best learned method while requiring no target prior. At the dataset's mean approach speed, this latency corresponds to only 4 cm of vehicle motion, compared with 1 m for the fastest competing learned method. REACT further supports anytime TTC prediction, zero-shot transfer to a different driving sequence, and INT8 quantization, reducing the estimated energy consumption from 18.5 to 2.8 mJ per 32,768 events. These results show that event-driven spiking state-space dynamics can provide low-latency, continuously updated temporal perception for reactive robotic systems.
### Title:
          4D Radar Perception Algorithms for Autonomous Driving: A Review
 - **Authors:** Xumin Wu, Jun Zhou, Jilin Mei, Chen Min, Yu Hu
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Research on 4D millimeter-wave radar perception algorithms has flourished in recent years, extending from signal processing and object detection to semantic segmentation, motion estimation, occupancy prediction, and dynamic scene reconstruction. This review organizes the field according to the evolution of perception tasks and algorithms. It first introduces radar fundamentals, data representations, and quality-enhancement methods, and then reviews object-level perception, motion and localization, local and dense spatial perception, and dynamic scene understanding. Across these directions, we compare radar-only learning, multimodal fusion, and cross-modal supervision and knowledge distillation. Particular attention is paid to how elevation, Doppler measurements, and radar physical priors are exploited across tasks. We further summarize the task coverage, input data, annotations, and evaluation protocols of existing datasets, clarifying the empirical support for different research directions. Finally, we discuss the common challenges and future directions of 4D radar perception for autonomous driving. This review provides a task-oriented perspective on the transition from sparse object perception to dynamic spatial understanding.
### Title:
          RAUL: Reference-Assisted Ureteroscopy Localization for Skill Assessment
 - **Authors:** Fangjie Li, Mai Bui, Charan Mohan, Michael Miga, Matthieu Chabanas, Nicholas Kavoussi, Jie Ying Wu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Objective: Incomplete navigation of anatomy during ureteroscopic kidney stone surgeries can contribute to repeat interventions. While skilled surgeons have lower reintervention rates, there are no objective metrics to quantify scope-navigation performance to evaluate when a trainee becomes skilled. This work aims to recover ureteroscope trajectories from endoscopic video and derive navigation metrics to quantify differences in skill. Methods: We propose RAUL, a reference-assisted reconstruction framework for recovering ureteroscope trajectories from ureteroscope videos only in phantoms. For each phantom, we use a slow, high-quality reference exploration video to generate a reference reconstruction. We localize subsequent exploration videos against this reference. We evaluate localization accuracy against electromagnetically tracked scope pose. We compute navigation metrics from phantom exploration trajectories to compare surgical residents across experience levels. Results: The proposed reference-assisted framework achieves a mean translation root mean square error of $0.5 \pm 0.1$ mm across 9 phantoms. Compared to standard Structure-from-Motion (SfM), the proposed pipeline increases frame-wise localization coverage from $50.5 \pm 14.9\%$ to $86.1 \pm 7.2\%$ of all video frames. The reconstructed trajectories revealed significant differences between high- and low-experience trainees in established navigation metrics. Conclusion: RAUL enables substantially more complete recovery of ureteroscope trajectories from videos compared to standard SfM pipelines, enabling trajectory-based skill assessment without additional tracking equipment. Significance: To the best of our knowledge, this is the first use of video-only recovery of ureteroscope trajectories without external tracking sensors for skill assessment, supporting scalable automated assessment of ureteroscopy navigation skill.
### Title:
          Dynamic-LIVO: A Dynamic-Aware LiDAR-Inertial-Visual Odometry System Using Spatio-Temporal Normals
 - **Authors:** Zhixin Zhang, Samuel Ahiwe, Matthew Hale, Liang Zhao, Pawel Ladosz
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper proposes Dynamic-LIVO, a dynamic-aware LiDAR-Inertial-Visual Odometry (LIVO) system for robust state estimation and static colored mapping in dynamic environments. Dynamic-LIVO employs Spatio-Temporal (S-T) normal analysis to identify dynamic LiDAR points and propagates the resulting classification to both LiDAR-inertial and visual-inertial updates, preventing dynamic LiDAR measurements and their associated visual observations from affecting state estimation and mapping. However, S-T normal estimation can be unreliable in newly observed and spatially sparse regions due to insufficient spatio-temporal observations. To address this issue, we introduce a time-delayed S-T normal estimation strategy that defers the classification of insufficiently constrained points and re-evaluates them as additional observations become available. This strategy improves dynamic classification reliability while preserving valid static points for map construction. Extensive experiments on public and self-collected datasets with diverse sensor configurations demonstrate that Dynamic-LIVO improves localization accuracy and produces cleaner static colored maps in challenging dynamic environments. The source code and self-collected dataset will be publicly released upon acceptance.
### Title:
          PIVOT: Perception-aware Independent Viewpoint Online Optimization
 - **Authors:** Yuyang Chen, Shekoufeh Sadeghi, Charuvahan Adhivarahan, Elton Lemos, Chen Wang, Sanjeev J. Koppal, Karthik Dantu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A fundamental assumption in robotic perception is that the sensor's field of view (FoV) is fixed relative to the robot body. Motion-decoupled sensors, such as gimbal-mounted cameras and MEMS-based LiDARs, instead allow sensing direction to be controlled independently at runtime. This freedom creates a computational challenge: efficiently selecting useful viewing directions online in feature-dense environments. We propose PIVOT, a lightweight iterative method that optimizes sensor viewing direction along a fixed translation trajectory to maximize feature visibility. Under a conical FoV model, visibility depends only on the optical axis, yielding a two-degree-of-freedom optimization on the viewing sphere $S^2$. Coordinate-free $SO(3)$ exponential-map updates enable efficient continuous optimization without explicit angular parameterizations or exhaustive viewing-sphere search. Monte Carlo evaluations retain 98.1--99.6% of brute-force visibility with a 76--85x speedup. Photorealistic simulation and real-world experiments further demonstrate improved visual localization robustness and practical viewpoint control on a quadruped robot.
### Title:
          AURORA: A Natural Language-Driven Agentic Framework for Understanding, Reasoning, and Orchestrating Reliable Air-Ground Co-Simulation
 - **Authors:** Keshu Wu, Hao Zhang, Rui Gan, Xiangbo Gao, Xiaopeng Li, Zhengzhong Tu, Yang Zhou
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Air-ground transportation research increasingly relies on co-simulation, yet constructing scenarios remains labor-intensive and difficult to validate. More importantly, a generated scenario may execute successfully while failing to realize the spatial, temporal, communication, or behavioral relationships requested by the user. This paper presents AURORA, a natural-language-driven agentic framework that treats air-ground scenario generation as a process of compilation with verification. Central to AURORA is the Air-Ground Scenario Graph (AGSG), a typed intermediate representation that explicitly connects agents, aerial missions, events, communication links, success conditions, and their cross-domain dependencies. This shared representation enables simulator-grounded parsing, joint road-airspace grounding, temporal planning, pre-execution feasibility checking, trace-based runtime verification, failure localization, and bounded repair within a unified workflow. We further introduce AURORA-Bench to evaluate not only whether generated scenarios execute, but whether they faithfully realize the requested interactions. Experiments across multiple language models show that structured execution substantially improves reliability, while runtime verification exposes silent failures that completion-based evaluation overlooks. Localized repair further resolves many violations without regenerating the entire scenario. The results show that reliable scenario generation requires verifying realized behavior, not merely executable code, and demonstrate the value of explicit intermediate representations for verifiable and repairable language-driven co-simulation.
### Title:
          SLAMSqueezeBench: Comparing SLAM Systems under Resource Constraints
 - **Authors:** Mohamed Hefny, Karthik Dantu, Steven Y. Ko
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Simultaneous localization and mapping (SLAM) is one of the services running on an autonomous robot. It is typically run to assist other tasks such as planning, manipulation, etc. All these tasks are run on edge hardware and are subject to severe resource constraints. However, most SLAM systems are built and tested in isolation, and their performance is reported as if they are the only task running on a system. We observe that existing benchmarks lack a common mechanism for comparing SLAM systems under realistic resource constraints. To address this limitation, we have developed SLAMSqueezeBench, a framework that allows testing of SLAM systems under realistic workloads on edge hardware. It does so by imposing constraints on compute and memory resources available for the SLAM system during execution. It also simulates realistic camera frame acquisition with frame drops when a finite buffer is full. Using SLAMSqueezeBench, we compare nine SLAM systems spanning classical systems, learning-based systems, and approaches for Gaussian splatting. Our testing framework will be available for use by the community upon publication.
### Title:
          VABench: Measuring Embodied Spatial Intelligence through Visual Demonstrations, Active Perception, and Metric Control
 - **Authors:** Zhongbo Zhang, Jiayi Jin, Yifan Wang, Zaibin Zhang, Haiwen Diao, Lijun Wang, Huchuan Lu
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spatial intelligence requires more than describing object locations. Under incomplete observation, models must identify and acquire missing evidence, interpret it in a common spatial frame, and act on it. We introduce VA-Bench to evaluate the complete observe-reason-act-revise loop. General-purpose MLLMs learn procedural context from RGB-only demonstrations, actively select camera viewpoints, issue metric Cartesian commands, and revise them from execution feedback. Models receive no privileged object poses, oracle trajectories, or learned action heads. A fixed model-agnostic controller executes only model-specified targets. VA-Bench contains 14 base task families (11 single-arm and three dual-arm), seven held-out geometry/layout variants, and a long-horizon five-object composition track. We evaluate 12 primary model conditions in three independent runs over the same 20 physically verified seeds per base task, reporting terminal success, nine trajectory-level behavioral diagnostics, and subtask progress. First, the best-performing model scores 100.0% on target localization and 78.9% on spatial relations in the annotated run. Its three-run macro-average task success is only 53.93+/-3.17%. Second, active camera control significantly improves task success over passive multi-view observation. In one matched comparison, success rises from 27.86% to 57.50%. Third, held-out geometric transfer can reduce task success by over 30 percentage points. No model completes a strict long-horizon episode, despite substantial partial progress. VA-Bench thus tests whether general-purpose MLLMs can turn visual demonstrations and actively acquired evidence into successful embodied action.
### Title:
          Selective Cotton Boll Localization for Robotic Harvesting: Evaluation of Deep Learning Vision Models Under Field Conditions
 - **Authors:** Thevathayarajh Thayananthan, Xin Zhang, Isuru Laddusinghe Badu, Jonathan Harjono, Glen C. Rains, Beiwen Li, Leonardo M. Bastos, Nuwan K. Wijewardane, Vitor S. Martins
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This study developed and evaluated a deep-learning-based perception framework for selective robotic cotton picking. The dataset contained 1,008 annotated field images collected using three cameras under varying natural lighting and weather conditions. Object-detection models from the YOLOv8 through YOLOv13 families were evaluated using their default configurations, while segmentation performance was assessed using YOLOv8-seg, YOLOv11-seg, YOLOv12-seg, the Segment Anything Model (SAM), SAMv2.1, FastSAM, and Grounded-SAM with the Recognize Anything Model (RAM). Among the detection models, GELAN-s achieved the most favorable balance between mean average precision (mAP) and inference speed, obtaining an mAP of 86.1%, precision of 81.6%, recall of 76.6%, and an F1-score of 79.0%, with an average inference time of 42.3 ms per image. Among the direct segmentation models, YOLOv12-m-seg provided the most favorable balance between AP@0.5 and FPS, achieving a segmentation AP@0.5 of 83.7% with an inference time of 20.4 ms per image. In the detection-prompted segmentation approach, bounding-box prompts generated by GELAN-s improved the localization of cotton bolls for SAM and SAMv2.1, while SAMv2.1 Tiny consistently outperformed FastSAM and Grounded-SAM with RAM. In the area-based evaluation against manually annotated segmentation masks, YOLOv12-m-seg achieved an $R^2$ value of 0.966, compared with 0.860 for GELAN-s + SAMv2.1 Tiny. Field experiments conducted using a UR5e robotic manipulator, a custom end-effector, and a ZED2i stereo camera further validated the effectiveness of the YOLOv12-m-seg model for real-time cotton boll detection, segmentation, and selective picking under varying confidence levels. These results demonstrate that YOLOv12-m-seg provides an efficient perception model for robotic cotton harvesting and has strong potential for field deployment.
### Title:
          VGGT-GS SLAM: Uncalibrated Monocular Gaussian Splatting SLAM with Feed-Forward Priors
 - **Authors:** Yuhang Han, Hao Wang, Jiaxi Cao, Xingyu Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present VGGT-GS SLAM, a monocular 3D Gaussian Splatting SLAM system designed for uncalibrated videos. Starting from feed-forward VGGT pose and depth priors, our system performs submap differentiable bundle adjustment that jointly refines camera poses and a 3D Gaussian map, while optimizing submap-shared intrinsics and radial--tangential distortion through analytic calibration Jacobians. To improve global consistency, we introduce Gaussian-native alignment (GNA) for camera-anchored scale refinement between sequential submaps and verification of loop-closure candidates. Extensive experiments on standard indoor benchmarks show consistent improvements in localization accuracy and strong rendering quality under uncalibrated settings, establishing a strong baseline for uncalibrated Gaussian SLAM.
### Title:
          Towards Active Cross-View Object Geo-Localization
 - **Authors:** Shunyu Yao, Xiaohan Zhang, Zhuoran Yang, Haoqi Lai, Qi Ming, Xiaoxi Hu, Hui-Liang Shen, Si-Yuan Cao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-view object geo-localization (CVOGL) typically assumes a fixed query image, overlooking the ability of mobile agents to actively acquire more informative observations. To address this limitation, we introduce Active Cross-View Object Geo-Localization (ActiveGeo), where an agent sequentially selects new viewpoints and determines when to stop, aiming to improve localization with minimal observations. We further propose ActiveMoPT, an ActiveGeo framework with three-stage training. First, Multi-View Prompt-Preserving Adaptation enables the model to aggregate multiple query views while reusing the initial prompt. Second, Trajectory-Guided Policy Initialization uses supervised agent trajectories to learn viewpoint selection and initial stopping behavior. Third, Cost-Aware Policy Refinement employs GRPO with a gain-cost reward to jointly optimize localization accuracy and observation efficiency. We also construct ActiveGeo-858, a zero-shot test set containing 858 scenes and 1,716 target annotations. Experiments show that ActiveMoPT achieves state-of-the-art performance on MoP-UAV using only 1.45 query views on average, and substantially outperforms previous CVOGL approaches under zero-shot evaluation on ActiveGeo-858.
### Title:
          Region-Level Policy Optimization for Fine-grained MLLM Perception
 - **Authors:** Yuheng Shi, Xiaohuan Pei, Minjing Dong, Chang Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fine-grained visual perception in MLLMs is commonly improved by raising the resolution, but the added visual tokens inflate vision-encoding and language-model prefilling costs. We show that the two operations underlying fine-grained perception, localizing the region of interest (RoI) and recognizing its content, have different resolution requirements. In a controlled diagnostic, localization tolerates roughly 3 to 4 times stronger token compression than recognition, which motivates localizing from a coarse view and concentrating resolution on the selected evidence. Decoding coordinates with the MLLM can be trained end-to-end from answers, but costs a full model pass per query and depends on grounding ability. A lightweight proposal network distilled from the model's attention is fast, but inherits the noise of its attention targets. The RoI from the proposal network reaches the answer through a discrete region choice, so its faithfulness to the answer cannot supervise the network. We therefore optimize the proposal network with region-level reinforcement learning, which we call Vision-RL2. It treats coherent regions as actions, and a frozen MLLM reader scores each one by how its removal changes the answer likelihood. Complementary subtractive and additive objectives suppress distracting proposals and recover missing evidence, updating only the predictor without region annotations, response sampling, or reasoning trajectories. The refined proposal further enables a sparse encoding that magnifies evidence and excludes background tokens. Across six fine-grained benchmarks and four MLLM backbones, Vision-RL2 improves accuracy over the base model at every token budget and surpasses its largest-budget accuracy with about 4 times fewer visual tokens. Code is available at this https URL .
### Title:
          Sketching the Error, Not the Product: Post Hoc Fault Recovery for Half Precision GPU Matrix Multiplication
 - **Authors:** Pranav Napolean, Vikas Srivastava, Napolean Periathambi
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Silent data corruption (SDC) from defective accelerators now interrupts large scale training, yet deployed mitigations act on whole nodes. Algorithm based fault tolerance (ABFT) for a single GEMM has to be fused into the kernel or encode the operands, and it localizes at most one error per checksum. We present FP-Sketch, a verifier that runs after an unmodified tensor core GEMM whose half precision operands are accumulated and delivered at FP32. A sum sketch detects corruption on every call. Hashed first moment sketches, confirmed by independent recomputation, then localize several corrupted entries with no false positives by construction, and each fault yields a coordinate and a magnitude for fleet diagnosis. In floating point, sketch noise rather than bucket collisions limits localization. We measure that noise and find that its constant depends on the BLAS and the operand format and that the bucket count must grow as $n^{2.57}$ for a square product. Sizing the bucket count by measured noise rather than by a fitted power of $n$ raises recovery on eight transformer shapes from 0.402 to 1.000, and measuring the noise at run time adapts the bucket count to the kernel and the model. Instruction level injection with NVBit shows that upsets in a live accumulator are often only 2 to 9% of a typical entry, a population that output side injection cannot produce. Output side injection recovers every fault, while under NVBit the same engine sized for faults of typical magnitude recovers 0.550, and sizing for the measured magnitudes restores 1.000. On Llama-2-7B, guarding the MLP down projections removes 99.4% (BF16) and 99.9% (FP16) of the perplexity damage caused by 2048 bit flips, and the clean path probe costs 0.78 to 3.06 ms against GEMMs of 0.35 to 12.47 ms.
### Title:
          Online Material-Labeled Environment Reconstruction via Bayesian Multipath Attribution for Low-Altitude ISAC
 - **Authors:** Meihui Liu, Shu Sun, Ruifeng Gao, Qiuming Zhu
 - **Subjects:** Subjects:
Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Environment reconstruction for low-altitude integrated sensing and communications (ISAC) has largely focused on geometry-centric maps, overlooking material-dependent propagation effects. Material-labeled reconstruction is therefore a key step toward propagation-aware mapping, enabling more physically grounded channel prediction and uncrewed aerial vehicle (UAV) networking. However, constructing such maps from wireless multipath observations is challenging in outdoor multi-building scenarios because multipath components (MPCs) from different facades are mixed, path-to-facade attribution is uncertain, and UAV measurements arrive sequentially under time-varying observation geometries. To address these challenges, we propose a unified online probabilistic framework that represents each reflecting facade as a virtual anchor (VA) and couples Bayesian VA localization, multipath attribution, and material inference. The Bayesian front end estimates facade-level geometry and computes soft MPC-to-VA attribution probabilities using a speculardiffuse likelihood model, thereby accounting for both dominant specular paths and diffuse surface-interacted components. These attribution probabilities are used to construct attribution-aware MPC representations, which are aggregated in a VA-centric manner and mapped by a material inference network to facadelevel material evidence. The resulting evidence is recursively fused through an online Bayesian update to produce stable material posteriors and material-labeled environment maps. Ray-tracing simulations in a representative urban street scenario show that the proposed method substantially outperforms a no-attribution baseline, achieves 93.75% final facade-level material accuracy on a held-out UAV trajectory, and maintains accurate VA-based facade localization.
### Title:
          SlugTrails: An Egocentric Benchmark for Floor Plan Localization in Large Buildings
 - **Authors:** Yunqian Cheng, Roberto Manduchi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Floor-plan-based indoor visual localization enables infrastructure-free positioning, but most methods are developed and evaluated in small residential environments unlike the large public buildings of real deployment. We introduce SlugTrails, a floor plan localization benchmark for large indoor spaces under realistic egocentric sensing: $30$ Hz Aria glasses recordings across three campus buildings and six floors ($22089$ m$^2$ of floor plan outline), CAD-derived floor plans with semantic classes and circulation space masks, and trajectories aligned into the floor plan frame using laser-surveyed anchors. One protocol covers three practical ways of gathering geometry under a limited field of view -- a single walking frame, a stationary multi-view sweep, and a walking stream with odometry -- so methods designed for different regimes are compared on the same buildings and ground truth. Evaluating five representative geometric and learned systems under their native sensing configurations, we find that stock checkpoints (official released weights) are near zero on SlugTrails (at most $0.004$ R@1m30$^{\circ}$ on walking single frames), while fine-tuning on SlugTrails improves every trainable family on all three tasks (e.g., F$^3$Loc $0.0 \rightarrow 0.141$ single-frame and $0.03 \rightarrow 0.66$ sequential), with gains compounding as observations accumulate. The same fine-tuned weights also improve cross-dataset generalization on LaMAR with no LaMAR training (sequential R@1m $0.048 \rightarrow 0.143$ for F$^3$Loc and $0.063 \rightarrow 0.127$ for UnLoc), whereas train-from-scratch on SlugTrails alone stays far below fine-tuning from stock weights -- evidence that floor plan localization is currently limited by indoor data rather than by architecture. We release the dataset, protocols, and tools at this https URL.
### Title:
          Enhanced Knowledge Distillation for Detection Transformer via Teacher Prediction Refinement
 - **Authors:** Yitong Xing, Yuhao Cheng, Yanping Li, Yichao Yan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Detection Transformers (DETRs) achieve strong performance in object detection but remain challenging to deploy on edge devices due to their high computational cost. Existing DETR distillation methods mainly focus on aligning distillation points, while largely overlooking the quality of the teacher's supervision itself. We observe that due to stage-wise non-monotonic prediction behavior in DETRs, well-localized or correctly classified predictions from earlier stages may degrade in later ones, and some negative predictions become increasingly overconfident. As a result, relying solely on the current stage's predictions yields inaccurate and inconsistent supervision. To address this issue, we propose Teacher Prediction Refinement Distillation (TPRD), a plug-and-play module that refines teacher predictions before distillation by exploiting stage-wise prediction information. TPRD improves supervision quality through Positive Prediction Correction (PPC), which corrects degraded positive predictions by restoring more accurate ones from earlier stages, ensuring reliable localization and classification signals, and Negative Prediction Suppression (NPS) suppresses the influence of overconfident negatives, preventing them from providing misleading supervision to the student. To preserve informative dark knowledge, we further introduce Maximum Dark Knowledge Preservation (MDKP), which selectively refines target-class logits while retaining non-target relations. Extensive experiments on MS COCO and PASCAL VOC demonstrate the effectiveness and robustness of the proposed method. Our code is available at this https URL.
### Title:
          AVTrace: Diagnosing Audio-Visual Temporal Reasoning in Omni Models
 - **Authors:** Longyin Zhang, Parth Sakhare Mahendra, Chengwei Wei, Ning Zhang, Lim Ming Chong, Sirui He, Ai Ti Aw
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Omni models can describe video content, but can they locate events in time, preserve event order, and judge audio-visual synchronization? We introduce AVTrace (Audio-Visual Temporal Reasoning Assessment and Capability Evaluation), a silver-standard diagnostic suite spanning onset and span grounding, synchronization, next-step prediction, cross-modal localization, chain parsing, and event-conditioned comprehension. It contains 34,114 training examples and category-balanced development and test splits of 3,500 and 7,000 examples. We evaluate five open omni models under their respective input configurations using reference-blind response normalization followed by deterministic scoring. All five off-the-shelf systems score below the test split's majority-label baseline of 0.556 on synchronization verification, and obtain low scores on chain parsing and event-conditioned grounding and comprehension. Development-set perturbations reveal task-dependent sensitivity in Qwen3-Omni-30B to modality removal and changes in visual input processing, without isolating their underlying causes. Parameter-efficient temporal post-training improves Gemma4-E4B-it on several benchmark metrics. On three external image benchmarks, task metrics change modestly, including some degradations, while teacher-forcing perplexity decreases. Together, these findings show that semantic reference-text overlap should not be treated as a proxy for temporal localization, and that AVTrace can identify task-specific weaknesses while providing a testbed for temporal post-training.
### Title:
          The Missing Complement: State-Conditioned Minimal Sufficient Evidence for Coding Agents
 - **Authors:** Zhexi Feng, Ruiyi Zhang, Yongbo Yang, Pengtao Xie
 - **Subjects:** Subjects:
Information Retrieval (cs.IR); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A coding agent halfway through an issue has already read much of what a retriever ranks highest. Relevance is scored per passage, but sufficiency belongs to the set: a ranker can fill its budget with variants of one required fact and leave the decision unsupported. We formulate state-conditioned minimal sufficient evidence recovery: given a captured agent state, recover a compact evidence combination that supplies the support its next decision still lacks. SERBench measures this on 500 held-out states from 45 repositories, recording what the agent has seen and crediting only sets that cover every fact the current decision was annotated to require. MSS-Complement treats acquisition as set construction, not ranking. Three semantic calls propose a jointly sufficient set, search for what it lacks, and return 4-8 intact source units within 6,144 tokens. One configuration, fixed on calibration data, recovers a complete set for 73.0% of those states at five items and 80.6% at eight, against 61.4% and 72.4% for Qwen3 embedding with reranking. A matched control ranking by similarity alone reaches 66.6%, placing the gain in the set-level policy, not the computation. From frozen repository source with no gold-derived pool, the lead is 5.0 points. On AMA-Bench it answers from a 76.2% smaller answer prompt, with accuracy 2.08 points above that benchmark's own memory agent. Removing one required group from an otherwise complete set costs 12.3 and 11.1 points of repair-localization precision under two executors. Retrieval for agents is better posed as recovering what a decision lacks than re-ranking what an issue resembles.
### Title:
          Marginal utility, matrix factorization, and the Key-Value (KV) cache: a unified information-economic framework for sovereign geo-mining inference
 - **Authors:** Caroline Gans Combe (INSEEC)
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper builds a theoretical bridge between the economic notion of marginal utility and two machine-learning constructs, matrix factorization and the Key--Value cache of transformer language models. The singular value spectrum of a rating matrix is shown to be a diminishing marginal utility schedule for latent factors, the eigenvalue spectrum of the projected covariance operator to be the marginal utility schedule of a model's learned representation, and cache eviction and low-rank cache compression to be instances of constrained utility maximization under a memory budget. The three collapse into a single allocation rule: retain the top dimensions whose eigenvalue exceeds the shadow price of the binding constraint. The framework is applied to the automated extraction of structured information from geo-mining documents, where it motivates a multi-pass inference protocol, a layer-wise TIES model merging procedure, and a selection policy combining extraction quality, localization drift and energy, scalarized with a Conditional Value-at-Risk term on drift. Two empirical contributions are reported. An 11.2-million-parameter hierarchical classifier, trained in about five minutes on a single GPU, reaches 90.0 per cent level-1 accuracy on a held-out test set from a 973-document uranium-exploration corpus, against 92.0 per cent for a proprietary model on a fifty-document human audit of the same corpus, at a latency of 2.62 ms per card against approximately 2,000 ms for the API and at negligible cost. A diagnostic of uniform-density TIES merging exposes a reproducible degenerate mode in which the merged model returns token-identical outputs across five geographically distinct districts while declaring high confidence; re-executing the merge under layer-wise calibrated densities removes that signature on the diagnostic sample. The full-scale extraction benchmark, including LoRA fine-tuning, is reported as projected rather than measured and remains an empirical extension of this work.
### Title:
          AdaRepair-Mem: Adaptive Experience Orchestration for Repository-Level Program Repair
 - **Authors:** Z. C. Luo, J. C. Guo, W. J. He, S. Y. Wang, J. C. Yu, F. M. Zhao, Y. Chen, T. Cao, L. Q. Liu, N. Zheng, W. Xu, J. Jiang, Z. M. Zhao
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent memory-augmented repository-level program repair methods reuse historical repair experiences to improve LLM-based issue resolution. However, our analysis reveals three limitations in existing repository-level memory retrieval. First, episodic memory is highly imbalanced across repositories, leaving low-resource repositories with little effective support. Second, more memory does not monotonically lead to higher repair success, suggesting that relevance, quality, and redundancy matter more than raw memory volume. Third, memory accumulation is phase-misaligned: repositories may contain many reproduction experiences but few patch or refinement experiences. To address these problems, we propose an adaptive experience retrieval framework for repository-level program repair. Our framework introduces coverage-aware retrieval, which falls back to cross-repository or repair-type-based memories when same-repository memory is insufficient; quality-aware selection, which ranks memories by relevance, historical utility, specificity, and redundancy; and stage-aware routing, which separates and retrieves memories for reproduction, localization, patch generation, patch refinement, and validation. Evaluated on SWE-Bench-Lite and SWE-Bench-Verified, the proposed framework improves repair performance on under-covered repositories, reduces noisy memory retrieval, and better supports failed-to-fixed patch refinement. Our results show that the key to memory-augmented repair is not simply accumulating more experiences, but retrieving the right experiences for the right repair context.
### Title:
          MoSSGate: Memory-Modulated State-Space Gating for Skin Lesion Segmentation
 - **Authors:** Anum Awan, Mahnoor Buriro, Muhammad Younas Khan, Md Imam Ahasan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate skin lesion segmentation is crucial for reliable computer-aided dermatological diagnosis, yet existing convolutional and transformer-based models often struggle to jointly capture long-range spatial dependencies and fine boundary details under limited computational budgets. This trade-off between global context modeling and boundary-aware localization frequently leads to over-segmentation, fragmented predictions, or missing thin peripheral structures. To address this challenge, we propose MoSSGate, a plug-and-play module for U-Net that integrates (i) boundary-aware spatial gating to restrict long-range propagation to informative regions, (ii) an external memory modulator that provides sample-adaptive dynamic control, and (iii) parallel 2D state-space modeling for efficient global context aggregation with linear complexity. The proposed design enables adaptive, context-aware information propagation while preserving sharp and accurate lesion boundaries. Extensive experiments on the ISIC 2017 and ISIC 2018 benchmarks demonstrate state-of-the-art accuracy with strong efficiency, achieving 86.3% and 85.9% mIoU and 92.6% and 90.6% Dice, respectively, while requiring substantially fewer FLOPs than most competing CNN-based methods. These results highlight a favorable accuracy efficiency trade-off for high-resolution medical image segmentation.
### Title:
          Generative Verification: Rethinking the Uncertainty Signal for Active Learning of Object Detection
 - **Authors:** Licheng Zhang, Zheng Gong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Nearly every acquisition function for active object detection shares one arrangement, in that the model being improved is also the model being interrogated. We depart from it. In generative verification an independent generative model re-derives the label of a detection from the pixels inside its predicted box, and the disagreement between the two becomes the acquisition signal. Two properties follow from the arrangement itself rather than from any tuning. A displaced box, a box on background and a correct box carrying the wrong label all yield a crop that fails verification, so the failure modes arrive already combined in one scalar and the hand-weighted classification and localization terms of existing criteria are no longer needed. And because the verifier never observes the detector confidence, confidently wrong detections score highest, although a self-derived signal reads them as uninteresting and they are the costliest to leave unlabeled. We build the verifier as a conditional diffusion model whose diffusion target is a label representation rather than an image. Its reverse process is stochastic, so repeated generations return a distribution whose concentration reports how firmly the evidence determines the label, where a classifier returns a single point estimate. On PASCAL VOC and MS-COCO the signal outperforms output-uncertainty, feature-geometry, perturbation and ensemble criteria, gaining about one mAP50 point per round on MS-COCO, with its largest margins in the early rounds where confident detector errors are most common.
### Title:
          AgentPProf: Semantic Profiler for Long Horizon AI Agents
 - **Authors:** Yusheng Zheng, Chaokun Chang, Yu Mao, Tianyuan Wu, Yuxi Huang, Tao Ma, Wenan Mao, Shuyi Cheng, Andi Quinn, Wei Wang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI agents increasingly orchestrate long-running activities with users, tools, and system resources for days and weeks. To improve agent quality, safety, and cost efficiency, developers need to determine where failures happen, what triggers unsafe effects, and which tasks consume the most budget, then optimize those tasks. In systems software, profiling answers similar questions by aggregating resource consumption and attributing it to responsible code paths to identify hotspots. Yet existing agent observability tools focus on per-execution debugging and tracing rather than cross-run, long term profiling, making these questions difficult to answer at scale. Agent observability needs profiling, not only debugging, but profiling agents is challenging: the responsible entities are task intent like diagnose authentication, compare branches rather than code paths, and lack stable identifiers for aggregation. We propose a semantic operation stack model that adapts profiling to agent trajectories. Uniform operations represent all activities, and operation stacks replace the runtime call stack, enabling hierarchical attribution at different granularities. We observe that an agent's task occupies a contiguous span and decomposes into subtasks, so we introduce recursive operation segmentation, which recursively splits trajectories at task boundaries. AgentPProf is a profiler that aggregates agent trajectories into pprof-compatible profiles, enabling flame graph visualization and analysis. AgentPProf reaches 0.764 $B^3$ F1 against human annotations on CodeTraceBench. On three problem-localization benchmarks, the profile raises MAP by up to 56%, demonstrating that it effectively attributes resources, locates problems, and helps optimize token cost at practical profiling cost. AgentPProf is available at this https URL.
### Title:
          Diagnose, Recover, Certify: Task Readiness under Hidden Dynamics Changes
 - **Authors:** Nguyen Viet Tuan Kiet, Huynh Thi Thanh Binh
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A deployed control policy can conceal consequential dynamics changes: an actuator may lose effectiveness without affecting the current task when the policy rarely excites it, despite being critical for a future task that has not yet been specified. We introduce task readiness under dormant dynamics drift, a decision problem that unifies active change diagnosis and post-change control recovery under a limited, task-agnostic interaction budget. An agent must identify whether and where local dynamics have changed, use a small number of informative interactions to characterize the change before downstream task identity is revealed, and subsequently provide each candidate task with either a recovered policy and a calibrated lower bound on its achievable return or an abstention decision to a safe fallback. We propose Evidence-Gated Matched-Pulse Transport, an intervention-based Bayesian procedure that couples fault localization with estimation of actuator effectiveness through a shared matched-response representation, thereby preserving diagnostic reliability while converting localized evidence into recovery-relevant uncertainty. This uncertainty is propagated to task-conditioned policy selection and readiness certification, enabling deployment decisions that explicitly trade off expected performance, confidence, and fallback use. We evaluate the resulting framework on a diverse suite of dormant-actuator benchmarks spanning multiple simulators, under a protocol that separates diagnosis from capability recovery, scores deployment by readiness coverage, selective risk, and interaction cost as well as return, and identifies the fault regimes in which transported evidence is decisive.
### Title:
          Implementation of Tightly-Coupled SLAM Fusion of GPS, IMU, and LiDAR for Autonomous Vehicles
 - **Authors:** Amr O. Elmehrath, Farah Khaled, Rana Nahas, Catherine M. Elias
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous vehicles depend entirely on Simultaneous Localization and Mapping (SLAM) to navigate safely in unknown environments. However, relying on a single sensory modality introduces critical failure points: LiDAR systems degrade in featureless corridors, Inertial Measurement Units (IMUs) accumulate mathematical drift, and GPS drops frequently in urban canyons. This paper presents the implementation of a tightly-coupled SLAM fusion architecture that integrates a Velodyne 3D LiDAR, a high-frequency IMU, and GPS to achieve continuous spatial awareness. Utilizing a phased development methodology, we establish a 2D baseline to validate hardware synchronization and transform geometries before upgrading to a full 3D architecture driven by FAST-LIO2. This advanced approach uses an Iterated Error-State Kalman Filter (IESKF) to process dense 3D laser points alongside continuous inertial data, eliminating motion blur at high speeds. To eradicate long-term drift, a GTSAM pose-graph optimization back-end executes multi-modal loop closures. Evaluated across simulated environments and physical deployments, the results demonstrate that tightly-coupled 3D fusion effectively overcomes individual sensor blind spots to generate highly detailed point clouds, providing the foundational High-Definition (HD) maps required for advanced downstream autonomous planners.
### Title:
          Navi-Agent: Unlocalized Monocular Navigation Agent
 - **Authors:** Wenyuan Xie, Mengyang Hong, Yongzhong Wang, Yanbiao Ji, Yijin Zhou, Shaokai Wu, Shalayiding Sirejiding, Huayi Zhou, Yi-Chao Chen, Ma Ling, Yue Ding, Hongtao Lu
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language Navigation in Continuous Environments (VLN-CE) requires an embodied agent to execute long-horizon instructions in unknown environments. Existing zero-shot VLN-CE systems typically maintain spatial states through geometric localization or coordinate-based representations. Recent geometry-constrained navigation removes depth and globally consistent coordinates, but maintaining persistent spatial awareness for place confirmation, progress verification, and recovery remains challenging. We present Navi-Agent, a zero-shot VLN-CE agent that constructs a coordinate-free spatial state from visual observations and executed motion histories. Navi-Agent organizes this state as a navigation topology, where nodes represent visual places and edges represent motion transitions. This representation enables observation-based approximate self-localization, task progress verification, and visual revisitation-based recovery. Navi-Agent performs closed-loop navigation by decomposing instructions into sub-goals, executing local visual navigation, and verifying visited places through the constructed spatial state. Experiments on zero-shot VLN-CE benchmark and real-world robot platforms show that Navi-Agent achieves state-of-the-art performance among geometry-constrained methods while remaining competitive with approaches relying on geometric localization.
### Title:
          Training Neural Networks to Approach the Optimum Bayes Estimator in Dense Multi-Emitter Localization
 - **Authors:** Yi Sun, Mona Sharifi, Muzna Yumman
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We train neural networks on synthesized frames to approach the optimum Bayes estimator for dense emitter localization. The result justifies the future work on training neural networks to achieve high-throughput large-FOV super spatiotemporal resolution SMLM.
### Title:
          Grounded Product Understanding in Livestream Videos
 - **Authors:** Xinyu Zhang, Junjie Chen, Jiawei Ge, Qianlong Li, Libin Ma, Baokun Pan, Yahui Luo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 E-commerce livestreams have emerged as an important channel for presenting products to online consumers, containing multiple products whose information is scattered in different moments. This poses significant challenges for downstream product understanding applications, such as product-centric livestream clipping, where models need to identify the product and its relevant segments for information gathering. However, existing benchmarks for general product understanding typically evaluate product retrieval and temporal localization in isolation, leaving the critical correspondence between product identity and temporal evidence largely unassessed. To address this limitation, we introduce GPUB, a large-scale benchmark comprising 3,000 livestream instances with quality-controlled multi-moment temporal annotations and a catalog of over 31K fashion products. GPUB supports three evaluation tasks: the main task Grounded Product Understanding (GPrU) requires jointly identifying the target product and localizing its supporting moments from a livestream video and a candidate product set; Product Retrieval and Product Moment Localization serve as two complementary subtasks. Evaluation of existing multimodal models shows that GPrU remains highly challenging, with the best-performing baseline achieving only 10.13% Pair mAP@.3. To narrow the performance gap, we further develop UniPro, a unified product understanding model that derives product-aligned and temporally structured representations from shared multimodal encoding, improving Pair mAP@.3 to 21.53% while achieving 37.23% Joint R@1@.3 on GPrU.
### Title:
          Automated Goldsmith's Mark Retrieval in Silverware
 - **Authors:** Atmik Tiwari, Vincent Christlein, Mark Fichtner, Freya Gohlke, Birgit Schübel, Theresa Witting, Heike Zech, Mathias Zinnen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Digital Libraries (cs.DL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 For art historians, goldsmith marks play a critical role in the identification and dating of artifacts. In practice, experts must manually compare a query mark against hundreds of documented examples, a process that is both tedious and highly dependent on specialist knowledge. To address this, we present an AI-assisted retrieval pipeline that combines mark localization with metric-learning fine-tuning across three backbone architectures: an ImageNet-pretrained ResNet-50, a supervised ViT-S/16, and a self-supervised DINOv2 ViT-S/14. We conduct a systematic evaluation of cropping strategies, where we measure the impact of no cropping, manual ground-truth cropping, and learned detection-based cropping, and assess their interaction with each backbone. Our strongest configuration, DINOv2 ViT-S/14 with manual crop and metric-learning fine-tuning, achieves an mAP of 62.63% and a Top-1 accuracy of 73.74%. Our experiments show that self-supervised pretraining and mark localization are the two most impactful factors, with learned cropping recovering the majority of the gain from manual cropping without requiring ground-truth annotations at inference time. To enable reproducibility and adoption in the digital humanities, we release our manually annotated dataset and codebase, and deploy the system via a public web interface.
### Title:
          Semantic SLAM in Precision Agriculture using Bayesian Inference
 - **Authors:** Ruben Beumer, Sander Doodeman, René van de Molengraft, Duarte Antunes
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a real-time semantic world modeling framework specialized for precision agriculture using autonomous robots. The framework combines probabilistic mapping of objects and their semantic attributes, updated through Bayesian inference, with a graph-based Simultaneous Localization and Mapping (SLAM) approach implemented using $g^2o$, a general framework for graph optimization. This integration enables accurate mapping and localization without relying solely on GPS. By leveraging semantic information such as plant type, size, and health, the robot can perform tasks while mapping and localizing itself within a field of crops. The proposed framework was validated through Gazebo simulations and physical experiments on an indoor field with artificial plants using Boston Dynamics' robot dog Spot. A YOLOv8n object detection model was trained to extract object and semantic data from depth camera observations. These simulations and experiments demonstrate that the system can successfully perform real-time mapping of up to at least 400 plants.
### Title:
          Refinement Is Inherently Editable: Training-Free Prompt-to-Prompt Image Editing with Generative Refinement Network
 - **Authors:** Yulong Chen, Ziqian Zhang, Haoyu Zhang, Ao He, Senmao Li, Kai Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-guided image editing must introduce the requested changes while preserving unrelated source content. Diffusion-based editors rely on spatial controls whose inaccuracies can leave edits incomplete or alter unrelated regions. Causal autoregressive editors face a further constraint: their fixed decoding order limits revision of earlier decisions. We introduce RefineEdit, a training-free prompt-to-prompt image editing framework built on a Generative Refinement Network. Our key idea is to couple edit localization with content generation through the global refinement of binary image codes, allowing editing evidence to be reassessed as the image evolves. RefineEdit initializes an editing branch from an intermediate source state, reusing the emerging layout. We compare the probabilities assigned by the two branches to the same source-sampled bits, using their signed differences to select editable positions and bits. Selected bits follow editing refinement, while the remaining bits copy the evolving source state. To stabilize editing across refinement steps, adaptive spatial freezing limits unnecessary mask expansion, while finite bit locking keeps recently selected bits editable. The framework requires no additional training, external masks, or attention control. Across nine editing categories of PIE-Bench, RefineEdit achieves the best background-preservation scores in PSNR, LPIPS, MSE and SSIM, together with the highest whole-image and edited-region CLIP scores among the evaluated methods.
### Title:
          RUN-O-RAN: An O-RAN-Native Architecture Enabling Cooperative Uplink Localization
 - **Authors:** Viola Bernazzoli, Alberto Ceresoli, Ilario Filippini
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate positioning is increasingly required in indoor and dense urban environments; nonetheless, satellite-based systems are not always available, and standardized 5G localization solutions remain difficult to deploy with commercial devices. This paper presents RUN-O-RAN, an O-RAN-native framework that enables network-centric uplink localization using standard Sounding Reference Signal (SRS) transmissions from commercial 5G devices. RUN-O-RAN xApp coordinates serving and neighboring base stations, enabling non-serving base stations to retrieve SRS-based uplink timing measurements that would be unavailable in conventional RAN deployments, without modifying the UE or existing 3GPP signaling procedures. The framework combines cooperative SRS collection, first-path time-of-arrival estimation, timing-advance tracking, clock-drift compensation, and multi-anchor position estimation into a complete network-side localization service. Experimental evaluation over $150,000$ SRS transmissions validates the proposed framework, achieving meter-level localization under diverse propagation conditions while revealing the impact of anchor geometry and multipath on positioning accuracy. These findings demonstrate that cooperative SRS-based localization can be realized within the O-RAN ecosystem without modifying commercial UEs, providing a practical foundation for future network-native ISAC positioning services.
### Title:
          Earth Surface Immune System for Rapid Monitoring of Unknown Anomalies
 - **Authors:** Jingtao Li, Qian Zhu, Xinyu Wang, Deren Li, Liangpei Zhang, Yanfei Zhong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Earth surface anomalies, driven by escalating climate change, and expanding human activities, are increasing in both frequency and diversity, yet their limited historical data and unpredictability make them fundamentally different from conventional remote sensing targets. Existing methods address specific anomaly categories or stop at localization, leaving a gap between detection and actionable information. Here we present ESIA, an Earth Surface Immune System whose architecture is constrained by three principles from the biological immune system, refined over millions of years against equally diverse and uncertain threats. A non-specific innate immune stage treats anomalies as unobserved changes in time-series satellite imagery, generating binary localization maps at 14.51 km2/s without assuming any anomaly category, surpassing the strongest general baseline by 37% in F1. A specific adaptive immune stage applies negative selection to filter text prompts and matches surviving prompts with localized image patches through a multi-modal foundation model, enabling open-vocabulary recognition of unknown anomaly attributes including category, affected area, and damage severity, with recognition F1 exceeding 80%. A mutation mechanism tunes minimal embeddings at test time, adapting to each scene in 3.26s using a single reference image pair. We validate ESIA on a global-scale dataset covering 19,801.60 km2 across six anomaly categories, comparing against 22 models, and further apply it to quantify degraded farmland in the Dnipro Delta following the Kakhovka Dam collapse and assess burn severity from 2025 Palisades Fire in Los Angeles. This unprecedented flexibility in handling unknown anomalies opens new avenues for real-time disaster response and environmental surveillance.
## Keyword: transformer
### Title:
          Modality Discrepancy Transformer for Ambivalence and Hesitancy Recognition
 - **Authors:** Shiyu Luo, Yu Wang, Jiawen Huang, Zhaoxiang Xiao, Chenxi Huang, Qi Zhang, Bin Liu
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ambivalence and hesitancy (A/H) are affective states in which individuals express contradictory signals across facial, vocal, and linguistic channels. Automatically recognising A/H in clinical videos requires detecting cross-modal disagreement -- the signal that standard fusion methods suppress. Based on the conflict-aware multimodal fusion framework of Bekhouche et al., we present the Modality Discrepancy Transformer (MDT). MDT enriches the original 6-token design to a 9-token representation comprising three modality embeddings, three absolute-difference features, and three Hadamard-product discrepancy features learned through linear projections. These nine tokens undergo Transformer self-attention, with FiLM-based text-conditioned modulation and LoRA fine-tuning as core architectural components. A text-guided late fusion branch blends a text-only auxiliary head with the full multimodal output at inference. On the BAH dataset from the 3rd ABAW Challenge, MDT achieves 0.7408 Macro F1 on the labelled test split and 0.7368 on the private leaderboard, outperforming the strongest published baseline by over 10 points while training in under 20 minutes on a single GPU.
### Title:
          Subliminal Prompting Beyond Static Geometry: Causal Depth and Multi-Token Confounds
 - **Authors:** Barath Velmurugan
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Subliminal learning shows that language models can transmit a hidden trait through outputs that appear unrelated to it. One proposed explanation, token entanglement, links animal and number tokens through the model's output vocabulary. Yet existing measurements answer different questions: whether outputs co-vary, fixed output vectors align, an answer can be read from a hidden state, or that state causally controls the answer. We measure each separately in a fixed animal-number prompting protocol. From Llama-3.1-8B to 70B, fixed output-vector similarity predicts behavior less well: the paired mean correlation change is -0.080 (95% CI [-0.127, -0.035]). A fixed output-head readout shows no resolved change in normalized depth AUC. To test control, we copy the temporary answer-position state from one number prompt into another at five depths and measure which prompt the final animal score follows. Donor-control AUC rises from 0.254 to 0.540, a paired change of +0.286 (95% CI [+0.272, +0.300]), with increases for all 18 concepts. The contrast remains with exactly eight transformer blocks remaining, while specificity and identity controls remain small or exact. In two Qwen models, scoring every digit in sequence does not recover the positive one-token association. Per-token averaging instead creates a positive pooled association that disappears after controlling number width, revealing a length confound. Thus, fixed geometry, observational readability, causal timing, and multi-token measurement are distinct properties of this frozen prompting channel. They constrain token-level explanations but do not identify the mechanism of training-time trait transfer.
### Title:
          MeshKV: A Network-on-Chip KV Cache Fabric for Scalable Transformer Decoding Accelerators
 - **Authors:** Dong Liu, Yanxuan Yu
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autoregressive transformer decoding is constrained by irregular key-value (KV) cache movement on tiled accelerators. Prior compression and DRAM-placement systems still concentrate traffic on centralized memory paths that bottleneck long-context serving. We present MeshKV, a KV cache fabric that moves blocks as packetized flows over a lightweight NoC. It co-designs (i) TaKV affine striping to spread homes and cut hotspot load, (ii) Mare multicast with verified duplicate suppression, and (iii) Pad, which overlaps prefetch, tile multiply, and streaming softmax behind credit-aligned FIFOs. Together they convert bisection back-pressure into useful KV transfer. On our 8x8 FPGA implementation with LLaMA-2-7B and Mistral-7B at 8K-32K, MeshKV reduces interconnect traffic by up to 58%, improves KV bandwidth utilization by 2.1x, and delivers up to 1.9x multi-stream throughput.
### Title:
          What Do Current Systematic Generalization Tasks Miss? A Reasoning-Centered Analysis
 - **Authors:** Chengwen Qi, Deheng Ye, Yatao Bian
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Systematic generalization, the ability to solve novel problems by recombining known atomic elements, is central to human intelligence but difficult to study rigorously under controlled settings. Existing studies therefore rely on simplifications such as approximately linear action composition, productivity-based tests, and action-explicit goals, which make systematic generalization easier to study but omit some essential aspects of this capability. To characterize what these simplifications miss, we adopt a reasoning-centered lens and introduce TranSGrid, a testbed that brings deductive, inductive, and abductive reasoning together within a unified task. Experiments with seven Transformers on 4,800 TranSGrid instances show that all models perform much worse on TranSGrid than on a held-out test set: the largest model solves 79.6% of the test set, but only 55.3% of TranSGrid and 15.8% of the hardest subset. The gap remains within the training length range, showing that productivity alone is not sufficient to evaluate systematic generalization. Additionally, we reintroduce the other two simplifications into TranSGrid: one variant makes actions compose almost linearly (reducing the inductive demand), the other makes goals action-explicit (reducing the abductive one). In both, solve rates return to roughly the test set level, showing that either simplification alone is enough to reduce TranSGrid to an ordinary held-out test set. Together, our results show that existing tasks reduce either or both of the inductive and abductive demands, and that comprehensively measuring systematic generalization requires a task that involves all three forms of reasoning.
### Title:
          YNU-HPCC at SemEval-2025 Task 11: Bridging the Gap in Text-Based Emotion Using Multiple Prediction Headers
 - **Authors:** Hao Yang, Jin Wang, Xuejie Zhang
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper describes the participation of the YNU-HPCC team in subtask A of task 11, Bridging the Gap in Text-Based Emotion at SemEval-2025. Our best-performing system employs the RoBERTa (Robustly Optimized BERT Approach) model, an improved version of BERT that utilizes the Transformer encoder architecture. We enhanced the output head to allow the model to process one emotion simultaneously. We obtained the official ranking score (0.44), including results from all languages. The entire dataset was translated into English using Google Translate to facilitate subsequent processing. Through probabilistic and attention analyses, we found that (I) a single prediction head performs better than six heads predicting six emotions simultaneously, and (II) training on a uniformly translated English dataset yields better results than using the original dataset. The code is available at: this https URL.
### Title:
          Riemannian--Lorentz Fusion of Vision Transformers and State-Space Models
 - **Authors:** Badri N. Patro, Vijay S. Agneeswaran
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scaling deep learning faces critical bottlenecks: data exhaustion, exponential training costs, and resource concentration. Model merging combines pre-trained checkpoints without gradient descent, offering orders-of-magnitude savings versus retraining. Combining independently trained vision models is difficult when their architectures and parameter shapes differ. Existing weight-space merging methods generally assume aligned, shape-compatible checkpoints, whereas a Vision Transformer (ViT) and a state-space model (SSM) implement token mixing with different operators. We study a hybrid Heterogeneous merging setting that retains both architectures while aligning parameter groups by semantic role. Our proposed Riemannian--Lorentz Parameter Fusion (RLPF) method projects aligned groups to common coordinates, lifts selected coordinates to the Lorentz hyperboloid model of hyperbolic space, computes a regularized geodesic barycenter, and decodes the result into the two branches. A learned gate then combines branch logits for each input. Component groups use fixed curvature values, with normalization parameters treated as Euclidean. In the results available in this manuscript, the fine-tuned system obtains 82.37\% on CIFAR-10, 75.04\% on Oxford-IIIT Pet, and 78.58\% top-1 accuracy on ImageNet-1K; the corresponding best-parent accuracies are 76.54\%, 71.42\%, and 76.42\%. On ImageNet-1K, the reported pre-fine-tuning initialization reaches 77.80\%. These results support further study of geometry-aware heterogeneous fusion, but not a training-free single-checkpoint merge: RLPF is a two-branch hybrid whose gate and reported final models are trained.
### Title:
          WZPlanner: Safe End-to-End Path Planning for Autonomous Driving in Work Zones
 - **Authors:** Nishad Sahu, Changzhong Qian, Guangzhou Cai, Shounak Sural, Ragunathan (Raj)Rajkumar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Work zones alter lane geometry through temporary traffic controls and closures that may be absent from on-board maps, challenging autonomous vehicle (AV) perception and planning. Generalization is also limited by scarce public datasets with structured geometric supervision. We present WorkZonePlan, a dataset comprising 149K+ synthetic and 5K+ real-world multimodal samples with 3D annotations for lane boundaries, work zone boundaries, and driving trajectory options. It also provides 76 closed-loop CARLA scenarios replayed under three weather conditions, yielding 228 Bench2Drive-format evaluation routes. We introduce WAVE (Work-zone-focused AV data generation in Virtual and rEal Environments), a semi-automated pipeline for creating the dataset, and BoundaryFormer (BF), a transformer-based model that jointly predicts lane and work zone boundary polynomials and driving trajectories. BF uses slot attention for boundary prediction. Ablations show that a separate trajectory decoder using boundary slot features substantially improves trajectory prediction over a slot-attention-only approach. Building on this finding, BF++ offers Camera and Camera+LiDAR variants with metric ground-plane encoding, typed boundary/trajectory queries, long-range point anchors, image-space curve refinement, and conservative gated LiDAR fusion. On the 211 routes common to all four models at the evaluation freeze, BF++-Camera and BF++-Camera+LiDAR achieve Driving Scores of 63.0 and 64.4, respectively, compared with 59.3 for SimLingo and 26.1 for TransFuser++ (TF++). BF++ is 40 times smaller than SimLingo and more than 10 times smaller than TF++, while achieving higher Driving Scores. These results support jointly predicting lane boundaries, work zone boundaries, and driving trajectories as a promising direction toward safer AV operation in work zones. Code and dataset: this https URL.
### Title:
          Enhanced Agriculture-informed Neural Network by Domain Knowledge
 - **Authors:** Ci Lin, Futong Li, Rose Chong-Wu, Tet Yeap, Iluju Kiringa
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate prediction of nitrous oxide (N2O) emissions from agriculture is important for assessing environmental impacts and supporting sustainable farming. However, prediction remains difficult because N2O emissions result from complex interactions among soil properties, climate, biochemical processes, and management practices, while high-quality observations are limited. Deep learning models can capture nonlinear relationships but often lack physical interpretability and may generalize poorly across environmental conditions. We propose the Knowledge-enhanced Agriculture-informed Neural Network (KAINN), a hybrid neural-mechanistic framework that extends the Agriculture-informed Neural Network by incorporating domain knowledge about fertilizer diffusion, soil respiration, and water-filled porosity. We evaluate KAINN using CNN, LSTM, and Transformer architectures across multiple growing seasons and input-feature configurations. The results show that KAINN generally provides lower root mean square error and mean absolute error and higher R-squared values than purely data-driven models and the original AINN. Analysis of the learned interfaces also shows smoother and more physically consistent parameter trajectories with reduced uncertainty. These findings demonstrate that incorporating environmental knowledge into neural networks can improve the reliability, interpretability, and generalization of agricultural N2O-emission predictions.
### Title:
          LSTM-UT and Recurrent-Depth Transformers on Cellular Automata
 - **Authors:** Aras Kavuncu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recurrent-depth Transformers apply shared computation repeatedly, but differ in how they retain information across steps. We compare a Block Universal Transformer (BUT), which carries only its current hidden state; CoTFormer, which also retains an expanding attention cache; and a new LSTM Universal Transformer (LSTM-UT) with bounded gated memory. On Rule 30 cellular automata, BUT extrapolates to unseen recurrent depths more reliably than CoTFormer, although its accuracy eventually degrades. State and cache interventions show that CoTFormer's failure depends on their interaction: correcting the current state can temporarily restore accuracy, while retained history can undermine that correction. In a delayed-recall task, BUT also outperforms CoTFormer despite lacking direct access to past states; CoTFormer does not reliably select the requested cached representation. LSTM-UT improves both depth extrapolation and delayed recall over these baselines. The results support bounded gated memory as an effective inductive bias for repeated computation and later retrieval in these tasks.
### Title:
          Instance Segmentation and Fine-grained Classification for Urban Buildings with Adaptive Region Dividing and Spatially-Supervised Contrastive Learning
 - **Authors:** Weiyuan Zhang, Qi Zhang, Hui Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate instance-level and functional understanding of urban buildings in large-scale point clouds is essential for digital city modeling and urban analysis. However, the extensive spatial coverage of urban scenes leads most existing methods to rely on predefined blocks for training and evaluation, although such partitions are rarely available in real-world applications and introduce additional preprocessing while fragmenting complete building structures. To address this issue, we propose an adaptive region-dividing strategy with unified scene-level evaluation. Specifically, the 3D point cloud is projected onto a bird's-eye-view (BEV) plane, where a pretrained segmentation model is used to detect building regions. The detected bounding boxes are then back-projected to the original point cloud to construct structure-aligned adaptive training blocks, enabling semantically guided dynamic partitioning without manual design. Furthermore, beyond instance-level understanding, few methods have explored fine-grained classification for urban buildings, and thus we also put forward a fine-grained classification model for urban buildings with a spatially-supervised contrastive loss. First, for each segmented building, a point transformer classifier jointly encodes its body and local context using geometric, color, and core-context information. Then, the class-balanced weighted cross-entropy is used to alleviate severe class imbalance. The proposed spatially-supervised contrastive loss further enhances inter-class discriminability by assigning greater weight to spatially proximate, same-category buildings, encouraging compact functional representations while separating easily confused categories. Extensive experiments on UrbanBIS and STPLS3D demonstrate the advantages of the proposed method in building instance segmentation and fine-grained classification compared to existing SOTA methods.
### Title:
          Understanding and Exploiting Diagonal Attention Sparsity in Autoregressive Image Generation
 - **Authors:** Daeun Kim, Junwha Hong, Changhun Oh, Yoonsung Kim, Yoonhyeong Lee, Jongse Park
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Performance (cs.PF)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autoregressive image generation has emerged as a paradigm for multimodal AI systems due to its compatibility with transformer-based LLM serving infrastructures. However, generating thousands of visual tokens per request makes decoding increasingly bottlenecked by KV cache accesses during attention computation. Sparse attention is particularly attractive for this workload because many visual generation applications tolerate moderate quality degradation in exchange for improved performance and efficiency. While sparse attention has been extensively explored for text-based LLM inference, it remains unclear whether its sparsity assumptions generalize effectively to autoregressive image generation. We present the first systematic characterization of attention sparsity in autoregressive image generation across diverse workloads and representative open-source models. Our analysis reveals several distinguishing properties, including a pronounced prefill-decode asymmetry, strong attention concentration on prompt and local tokens, and a unique diagonal attention sparsity pattern arising from the spatial locality of visual tokens. Motivated by these observations, we propose a diagonal-aware sparse attention mechanism that selectively skips KV entries along the diagonal attention direction within a recent window. Implemented on top of a GPU-based serving system using FlexGen, FlashAttention-2, and custom kernels, our approach achieves up to 3.1x throughput and 1.19x latency improvements with less than 2% quality degradation compared to dense inference.
### Title:
          Sketching the Error, Not the Product: Post Hoc Fault Recovery for Half Precision GPU Matrix Multiplication
 - **Authors:** Pranav Napolean, Vikas Srivastava, Napolean Periathambi
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Silent data corruption (SDC) from defective accelerators now interrupts large scale training, yet deployed mitigations act on whole nodes. Algorithm based fault tolerance (ABFT) for a single GEMM has to be fused into the kernel or encode the operands, and it localizes at most one error per checksum. We present FP-Sketch, a verifier that runs after an unmodified tensor core GEMM whose half precision operands are accumulated and delivered at FP32. A sum sketch detects corruption on every call. Hashed first moment sketches, confirmed by independent recomputation, then localize several corrupted entries with no false positives by construction, and each fault yields a coordinate and a magnitude for fleet diagnosis. In floating point, sketch noise rather than bucket collisions limits localization. We measure that noise and find that its constant depends on the BLAS and the operand format and that the bucket count must grow as $n^{2.57}$ for a square product. Sizing the bucket count by measured noise rather than by a fitted power of $n$ raises recovery on eight transformer shapes from 0.402 to 1.000, and measuring the noise at run time adapts the bucket count to the kernel and the model. Instruction level injection with NVBit shows that upsets in a live accumulator are often only 2 to 9% of a typical entry, a population that output side injection cannot produce. Output side injection recovers every fault, while under NVBit the same engine sized for faults of typical magnitude recovers 0.550, and sizing for the measured magnitudes restores 1.000. On Llama-2-7B, guarding the MLP down projections removes 99.4% (BF16) and 99.9% (FP16) of the perplexity damage caused by 2048 bit flips, and the clean path probe costs 0.78 to 3.06 ms against GEMMs of 0.35 to 12.47 ms.
### Title:
          Beyond Flattened Tokens: Structure-Preserving EEG Decoding with Reusable TriDim Blocks
 - **Authors:** Shiyue Su, Song Wang, Zekai Zhan, Junjie Zeng, Ziling Lu, Zongsheng Li, Xinyuan Ye, Zhiyuan Ma, Xinke Shen, Quanying Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Effective EEG decoding requires representations that preserve organization among channels, local waveform dynamics, and long-range temporal context. Existing EEG architectures often capture these structures using separate specialized modules or collapse them into a single token sequence, making it difficult to maintain their distinct roles and coordinate their interactions throughout the backbone. We propose TriDim, a reusable block that preserves the representation shape and keeps three EEG axes explicit: channel, sample position within each patch, and patch position across the recording. These axes correspond to spatial, short-term temporal, and long-term temporal information, respectively. Each TriDim block applies feed-forward transformations along individual axes and cross-axis attention to coordinate information exchange among them. By stacking TriDim blocks with a multi-level tri-axis readout, we construct TriDimEEG, a standalone EEG decoder. Under strict cross-subject evaluation on eight datasets spanning clinical diagnosis, sleep staging, motor imagery, and emotion recognition, TriDimEEG achieves the best overall performance among fifteen evaluated models, with a 4.3% relative improvement in average accuracy over the second-best model. Replacing Transformer blocks in three EEG foundation models with TriDim blocks yields an average relative improvement of 7.4% in downstream accuracy while reducing parameter counts by 17.0% to 47.3%. These results establish TriDim as an effective and reusable building block and TriDimEEG as a strong standalone EEG decoder. Code and parameters of TriDimEEG are available at this https URL.
### Title:
          Constraint-Safe Graph-Context Scoring for Stable Point-Feature Labels Under Text-Width and Accessibility-Inspired Profiles
 - **Authors:** Taimoor Ahmad
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Point-feature label placement on interactive maps must reconcile geometric validity, display yield, local placement utility, and stability across camera motion. Accessibility and multilingual requirements further change label dimensions, yet algorithmic evaluations often collapse these concerns into overlap counts. We present LABELSENSE-Pilot, a reproducible prototype that generates eight compass candidates per feature, scores candidates with a multilayer perceptron over graph-context summaries, adds a previous-placement bonus, and selects a layout through mixed-integer optimization. The executed scorer is deliberately not described as a graph transformer. Every returned layout is checked for viewport containment, per-feature uniqueness, and pairwise clearance. Experiments use 2,500 airport coordinates and names spanning 155 countries, with country-grouped splits and generated density, camera, text-suffix, preference, and enlarged-font stressors. Across five seeds, LABELSENSE-Pilot displayed 85.62 percent of labels with 2.09 percent flicker and zero collisions. Versus a handcrafted-utility integer program, LABELSENSE-Pilot sacrificed 1.43 percentage points of display while reducing flicker by 12.04 points. Enlarged-box-aware layouts produced zero proxy violations, whereas standard geometry reevaluated at 1.5x violated 52.57 percent of selected placements. These results establish an auditable engineering trade-off, not human accessibility, multilingual usability, or preference. Official recent baselines and participant evidence remain required before submission.
### Title:
          PART: Learning 3D Part Assembly and Retrieval with Transformers
 - **Authors:** Ruchao Bao, Wenzheng Wu, Chucheng Xiang, Zhongyuan Liu, Yuan Liu, Jinxin Dong, Ligang Liu, Ziqi Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D assembly is fundamental to modern manufacturing and digital content creation. In this paper, we present PART, a unified transformer-based framework for 3D part retrieval and assembly: given a target shape and a part library, PART automatically selects the appropriate parts and predicts their 6-DoF poses to reconstruct the target. While prior work has achieved impressive progress on assembling a pre-defined set of parts, this more practical retrieval-based setting remains largely unexplored. The task faces three key challenges: (i) a combinatorially explosive search space that grows exponentially with library size; (ii) variable-length outputs, as different targets require different numbers of parts; and (iii) continuous 6-DoF pose estimation for part assembly. To address these, we formulate retrieval and assembly as a set prediction problem and design a novel transformer-based framework that retrieves parts and regresses their poses with variable-length output. Additionally, we exploit the duality between part pose estimation and target segmentation through joint training and a novel segmentation-enhanced optimization module. Finally, We curate a large-scale dataset of 80K+ shapes, and the results show that PART generalizes to scene layouts, image targets, and real-world scans. Project Page: this https URL.
### Title:
          AURA: Adaptive Uncertainty-Routed Analysis for Email Threat Detection
 - **Authors:** Omran Berjawi, Walid fahs, Rida Khatoun
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Email spam and phishing attacks remain a critical security threat. Adversaries increasingly exploit large language models to craft contextually convincing malicious messages, and existing spam detection systems often struggle to keep pace. Generalization across diverse and evolving attack scenarios is limited, which reduces effectiveness once these systems are deployed in practice. This paper introduces Adaptive Uncertainty-Routed Analysis (AURA), a multimodal email threat detection system that analyzes both the content of an email and its embedded URLs. AURA is built around two layers: the first quantifies prediction uncertainty from a URL classifier, and only ambiguous messages are escalated to a fine-tuned transformer encoder for semantic analysis. The system is evaluated on eight heterogeneous training corpora together with two held-out real-world corpora spanning a decade of adversarial campaigns. AURA reaches a macro F1-score of 0.9858 in-distribution, and on NazPhish-Eval and GuenterTrap-Eval it maintains 0.9502 and 0.9436, respectively, which is evidence of robust generalization under genuine distribution shift.
### Title:
          Generalization through Lexical Abstraction in Transformer Models: The Case of Functional Words
 - **Authors:** Giuseppe Samo, Vivi Nastase, Paola Merlo
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pronouns, adverbs and other functional words (such as they, her, somewhere, there) are often used in language to replace concrete nouns or phrases, when their properties - such as gender, grammatical number - provide sufficient information for the given context. Do pretrained transformer models encode such functional words in a manner that allows them to be used like humans do? Can language models recognize the syntactic and semantic parallelism of sentences such as "The researchers wrote the paper" and "They wrote it", which relies on such lexical abstraction? We map these linguistic questions into the embedding space of a pretrained transformer model, and compare representations of nouns, with the representations of the pronouns and adverbs that can replace these nouns, in isolation and in parallel lexicalized and functional sentences. We then probe for shared syntactic and semantic structure in the embeddings of parallel lexicalized and functional sentences. We find that functional words are located centrally compared to nouns, but are also distinct, which is congruent with their behaviour as place-holders in a wide variety of contexts. The analysis of the embeddings of parallel (lexicalized and functional) sentences show them inhabiting different subspaces of the embedding space. Experiments that distil the structural information of the sentence show that training on either type of data does not reveal the shared structure - because of the over-consistency of the vocabulary (in case of the functional data), and the too much variety (in case of the lexicalized versions). However, training with a mix of functional and lexicalized sentences, the shared structure emerges.
### Title:
          Beyond Depth Truncation: Controlled Evaluation of Depth Utilization in Recursive Language Models
 - **Authors:** Ha Van Dau, Thanh Tung Khuat, Nguyen Thanh Dung
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Depth-recurrent language models iteratively apply a small layer stack, decoupling per-token compute from distinct parameter count. To determine whether such a model genuinely utilizes its depth, both recurrence and layer-pruning literatures rely on a shared evaluation: truncating depth at inference time, plotting quality against retained depth fraction, and reading off the slope. While cheap and training-free, this metric suffers from an unexamined flaw: it extracts a single scalar from an intervention that alters multiple model properties simultaneously. Depth truncation concurrently reduces the number of block applications, decreases the volume of distinct computation performed, and pushes the readout head onto an out-of-distribution residual stream. The observed slope conflates all three factors, yet is conventionally interpreted as reflecting solely the second. We propose the Depth Control Protocol (DCP), a diagnostic suite that disentangles these three quantities. DCP comprises three positive controls that isolate each factor while varying the others, a negative control applying the identical interventions to dense transformers to ensure the effect is not an artifact of the measurement protocol, and a controlled training intervention to verify causality. The linchpin control, running the full budget of block applications while executing only a single distinct iteration, is strictly realizable only in depth-wise weight-sharing architectures, since in a dense network repeating a layer yields an entirely different model rather than the same model in an alternative configuration.
### Title:
          Enhanced Knowledge Distillation for Detection Transformer via Teacher Prediction Refinement
 - **Authors:** Yitong Xing, Yuhao Cheng, Yanping Li, Yichao Yan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Detection Transformers (DETRs) achieve strong performance in object detection but remain challenging to deploy on edge devices due to their high computational cost. Existing DETR distillation methods mainly focus on aligning distillation points, while largely overlooking the quality of the teacher's supervision itself. We observe that due to stage-wise non-monotonic prediction behavior in DETRs, well-localized or correctly classified predictions from earlier stages may degrade in later ones, and some negative predictions become increasingly overconfident. As a result, relying solely on the current stage's predictions yields inaccurate and inconsistent supervision. To address this issue, we propose Teacher Prediction Refinement Distillation (TPRD), a plug-and-play module that refines teacher predictions before distillation by exploiting stage-wise prediction information. TPRD improves supervision quality through Positive Prediction Correction (PPC), which corrects degraded positive predictions by restoring more accurate ones from earlier stages, ensuring reliable localization and classification signals, and Negative Prediction Suppression (NPS) suppresses the influence of overconfident negatives, preventing them from providing misleading supervision to the student. To preserve informative dark knowledge, we further introduce Maximum Dark Knowledge Preservation (MDKP), which selectively refines target-class logits while retaining non-target relations. Extensive experiments on MS COCO and PASCAL VOC demonstrate the effectiveness and robustness of the proposed method. Our code is available at this https URL.
### Title:
          Astronex-World 1.0: Real-Time Interactive World Model Foundation
 - **Authors:** Xin Zhou, Cong Miao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Astronex-World 1.0, an open controllable video world-model foundation. Given a text prompt (text-to-video) or an initial observation (image-to-video), the model predicts future visual states under frame-aligned camera trajectories, continuous actions, and an embodiment identifier, and accepts text events inserted at a specified position of a rollout. The family provides a bidirectional model for full-context generation and a causal model with block-causal attention and cross-block KV caching for persistent generation, both built on the Wan2.2-TI2V-5B prior. PRoPE injects camera intrinsics and extrinsics, while a 64-dimensional action stream modulates every Transformer layer. A five-stage training path develops bidirectional camera and action control, converts the backbone to block-causal generation, distills a few-step student, restores mixed-domain dynamics, and applies asymmetric DMD/DMD2 distribution matching. The causal model generates 832x480 video at 24 fps. All five training stages run on two NVIDIA L20 48 GB GPUs, and the causal model streams in real time on one. It scores 73.5 on WBench Navi and 70.0 on WBench Full. On Full, this 5B model is above the 13.6B LongCat-Video and the 14B Helios, within one point of the 22B LTX-2.3, and above YUME 1.5, which is post-trained from the same 5B prior on NVIDIA A100 GPUs. The reserved action input and output interfaces allow post-training for embodied intelligence and autonomous driving.
### Title:
          Marginal utility, matrix factorization, and the Key-Value (KV) cache: a unified information-economic framework for sovereign geo-mining inference
 - **Authors:** Caroline Gans Combe (INSEEC)
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper builds a theoretical bridge between the economic notion of marginal utility and two machine-learning constructs, matrix factorization and the Key--Value cache of transformer language models. The singular value spectrum of a rating matrix is shown to be a diminishing marginal utility schedule for latent factors, the eigenvalue spectrum of the projected covariance operator to be the marginal utility schedule of a model's learned representation, and cache eviction and low-rank cache compression to be instances of constrained utility maximization under a memory budget. The three collapse into a single allocation rule: retain the top dimensions whose eigenvalue exceeds the shadow price of the binding constraint. The framework is applied to the automated extraction of structured information from geo-mining documents, where it motivates a multi-pass inference protocol, a layer-wise TIES model merging procedure, and a selection policy combining extraction quality, localization drift and energy, scalarized with a Conditional Value-at-Risk term on drift. Two empirical contributions are reported. An 11.2-million-parameter hierarchical classifier, trained in about five minutes on a single GPU, reaches 90.0 per cent level-1 accuracy on a held-out test set from a 973-document uranium-exploration corpus, against 92.0 per cent for a proprietary model on a fifty-document human audit of the same corpus, at a latency of 2.62 ms per card against approximately 2,000 ms for the API and at negligible cost. A diagnostic of uniform-density TIES merging exposes a reproducible degenerate mode in which the merged model returns token-identical outputs across five geographically distinct districts while declaring high confidence; re-executing the merge under layer-wise calibrated densities removes that signature on the diagnostic sample. The full-scale extraction benchmark, including LoRA fine-tuning, is reported as projected rather than measured and remains an empirical extension of this work.
### Title:
          SETTer: Sparse-Encoder Transformer for Long-term Multivariate Time Series Forecasting
 - **Authors:** Abraham Ezema, Chijioke Eze, Ferdinanda Ponci, Antonello Monti
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long-term multivariate time series plays a significant role in many application areas such as power systems, trading, etc. However, their accurate prediction is quite difficult for conventional forecasting methods as they often exhibit high dimensionality and complex relationships. Recent works show that transformer-based approaches are quite effective for long-term forecasting thanks to their attention mechanism. However, in the presence of complex high-dimensional inputs, they show evidence of oversmoothing, limited capacity, and opacity. To this end, this paper introduces SETTer, a transformer-based model that addresses these challenges by incorporating novel techniques for decoupled self-attention and hybrid masking. The proposed techniques enable SETTer to effectively capture the dominant short- and long-term patterns across the temporal and channel dimensions. In addition, we enrich the model layers with simple explainable structures that indicate the discriminative pattern of SETTer. We show that with a single-layer transformer architecture, SETTer can effectively model long-term dependencies in the presence of varying data complexities. Extensive experiments on real-word benchmark datasets for long-term multivariate time series forecasting demonstrate that SETTer outperforms state-of-the-art models in 88% of the scenarios.
### Title:
          A Smaller Transformer in Your Transformer
 - **Authors:** Dhananjay Tomar, Marius Aasan, Andreas Kleppe, Adín Ramírez Rivera
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent findings indicate that Vision Transformers settle into locally similar computational phases, implying a level of depthwise computational redundancy. However, existing methods to exploit this redundancy either fail to reduce inference compute or severely degrade model expressivity. In this work, we formalise a unified view of block redundancy that decouples the geometry from specific surrogate interventions. We then introduce Transformer-Within-Transformer (TWT), a post-hoc method that fuses contiguous groups of redundant layers into a single learned surrogate layer. TWT reduces parameter count and inference compute while remaining competitive with original models using half the depth on natural images, and in several downstream histopathology settings, TWT matches or even improves on the original baseline.
### Title:
          Bridging Modalities on the Cortex: Surface-based MRI to PET Translation with a Diffusion Bridge
 - **Authors:** Yitong Li, Alexandra Samoylova, Fabian Bongratz, Timo Grimmer, Dennis M. Hedderich, Igor Yakushev, Christian Wachinger
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cortical hypometabolism measured by Fluorodeoxyglucose Positron Emission Tomography (FDG-PET) is a highly sensitive biomarker for dementia diagnosis. However, high costs, radiation exposure, and limited accessibility constrain its clinical utility. While cross-modal synthesis from Magnetic Resonance Imaging (MRI) offers a promising alternative, existing volumetric generation methods do not explicitly account for the highly folded cortical geometry, where disease-related patterns predominantly reside. To address this, we introduce a novel surface-based diffusion bridge framework DB-SUiT for MRI-to-PET translation that operates natively on the cortical manifold. A conditional Spherical U-shaped vision Transformer (SUiT) is specifically designed to model the intricate cross-modal relationships while preserving surface topology. It combines spherical convolutional encoders for multi-scale surface feature extraction with bottleneck Transformers to capture long-range spatial dependencies, while incorporating demographic and subcortical conditions to refine the synthesis. Evaluated on two datasets, including subjects with different dementia types, DB-SUiT demonstrates high-fidelity synthesis that substantially outperforms other baselines. In automated dementia classification, synthesized PET surfaces improve performance over MRI by 14.2% and PET volumes by 11.3%, approaching the performance of real PET surfaces. In a blinded reader study, synthetic PET achieved 85.5% diagnostic accuracy, compared with 75.8% for MRI and 95.2% for real PET. This further demonstrates cross-cohort and cross-pathology generalization, as the model was evaluated without retraining on an external cohort that included a dementia subtype not represented during training. Our code is available at this https URL.
### Title:
          Small Enough to Know Everything: The Fully-Enumerable Transformer as an Instrument for the Science of Delayed Generalization
 - **Authors:** Yoshiyuki Ootani
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tiny transformers trained on fully-enumerable tasks occupy an unusual position in the study of grokking: every input can be evaluated, every generalization ceiling can be computed exactly, and hundreds of seeds cost minutes. We argue this regime is a scientific instrument with four capabilities that approximate settings cannot offer: (a) exact, falsifiable generalization ceilings; (b) task surgery that manipulates one structural variable while provably fixing all others; (c) direct observation of every weight; and (d) survival-time statistics over many seeds that recast "does not grok" as a censored observation. The obvious objection is that laws characterized at 10^4 parameters may not mean anything beyond them. We answer it with a preregistered conservation study: three task-side laws established at 12K parameters -- a recoverability-ceiling law, a role-conflict delay law, and a weight-decay response law -- are re-measured under an identical from-scratch protocol at 12K, 1M, and 50M parameters (a 4,000x span; 360 runs plus a 44-run control arm). The ceiling law and the delay law are conserved (0/144 Holm-corrected ceiling violations; Spearman rho >= 0.75 at every scale, permutation p < 1e-4), while the weight-decay law deforms systematically, steepening with scale. Preregistered controls show the 50M role-conflict deficit survives learning-rate adjustment and a tripled budget. Conservation was tested against criteria frozen before data collection, and one law's deformation shows the test could have failed. These results license the fully-enumerable transformer as a model organism for the task-side laws of delayed generalization: what it measures exactly, larger models largely obey -- and where they deviate, the deviation is itself lawful and measurable.
### Title:
          MTF-Net: Multi-Modal Temporal Feature Fusion Network for Pedestrian Intention Prediction
 - **Authors:** Md Mahfuzur Rahman, Pengzhan Zhou, A. F. M. Abdun Noor, Md Imam Ahasan, Md Mustafizur Rahman, Fang Qu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurately predicting pedestrian intentions is crucial for ensuring safe and proactive interaction between autonomous vehicles and pedestrians. However, existing approaches often depend on architectures that either model temporal dependencies within individual modalities or fuse modalities only at coarse semantic levels. To address these limitations, we propose MTF-Net, a novel Multi-Modal Temporal Feature Fusion Network that jointly models kinematic, appearance, and contextual cues for pedestrian intention prediction. MTF-Net integrates four complementary modalities-bounding-box dynamics, human pose keypoints, local context, and scene-level semantics within a recurrent fusion framework enhanced by gated linear units (GLUs). These GLU-based modules adaptively regulate cross-modal information flow, enabling interpretable and efficient feature interaction across temporal scales. Through three dedicated temporal encoding branches and an attention-guided fusion head, the proposed model robustly anticipates pedestrian crossing intentions several frames before they occur. Extensive evaluations on the PIE and JAAD benchmarks demonstrate that MTF-Net surpasses recent transformer- and graph-based models, achieving up to 0.95 AUC on PIE and 0.94 AUC on JAAD, while maintaining real-time performance. The results highlight that reliable pedestrian intention prediction arises from principled multi-modal fusion rather than excessive architectural complexity.
### Title:
          MoSSGate: Memory-Modulated State-Space Gating for Skin Lesion Segmentation
 - **Authors:** Anum Awan, Mahnoor Buriro, Muhammad Younas Khan, Md Imam Ahasan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate skin lesion segmentation is crucial for reliable computer-aided dermatological diagnosis, yet existing convolutional and transformer-based models often struggle to jointly capture long-range spatial dependencies and fine boundary details under limited computational budgets. This trade-off between global context modeling and boundary-aware localization frequently leads to over-segmentation, fragmented predictions, or missing thin peripheral structures. To address this challenge, we propose MoSSGate, a plug-and-play module for U-Net that integrates (i) boundary-aware spatial gating to restrict long-range propagation to informative regions, (ii) an external memory modulator that provides sample-adaptive dynamic control, and (iii) parallel 2D state-space modeling for efficient global context aggregation with linear complexity. The proposed design enables adaptive, context-aware information propagation while preserving sharp and accurate lesion boundaries. Extensive experiments on the ISIC 2017 and ISIC 2018 benchmarks demonstrate state-of-the-art accuracy with strong efficiency, achieving 86.3% and 85.9% mIoU and 92.6% and 90.6% Dice, respectively, while requiring substantially fewer FLOPs than most competing CNN-based methods. These results highlight a favorable accuracy efficiency trade-off for high-resolution medical image segmentation.
### Title:
          Evaluating Financial Sentiment in the Age of AI
 - **Authors:** Arslan Bisharat, Oudom Hean
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Financial sentiment measures are widely used in empirical finance, but it remains unclear whether general-purpose large language models (LLMs) improve on existing finance-specific methods. This paper evaluates twelve sentiment models, including dictionary-based methods, finance-specific transformers, and open-source LLMs, using two criteria: linguistic validity and economic validity. We find that general-purpose LLMs achieve classification performance comparable to finance-specific transformer models without task-specific fine-tuning. However, higher classification accuracy does not translate into stronger economic relationships. Several models produce sentiment measures that are significantly associated with earnings surprises, but none is significantly associated with next-day stock returns. Model performance is strongest for announcements with large earnings beats or misses and substantially weaker for announcements with more moderate earnings surprises. These findings suggest that financial sentiment captures information about firms' economic performance but has limited ability to explain short-run market reactions
### Title:
          Towards a Unified Modality-Agnostic Multimodal Framework for Cognitive Workload Assessment
 - **Authors:** Stefanos Gkikas, Christian Arzate Cruz, Calvin Joseph, Giorgos Giannakakis, Raul Fernandez Rojas
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cognitive workload reflects the mental effort required during task performance and is central to the design of adaptive human-machine systems. The use of biosignals to measure cognitive workload has been extensively researched and documented; however, studies examining the effects of combining heterogeneous biosignal modalities for this purpose remain limited. To provide insight into this area, we developed a unified, modality-agnostic, hierarchical Transformer-based architecture to process heterogeneous biosignal modalities within a single model. We use this framework in a pilot study evaluating all $31$ possible combinations of five modalities: Electrocardiogram (ECG), Electrodermal Activity (EDA), Respiration (RESP), Peripheral Oxygen Saturation (SpO$_2$), and Electroencephalogram (EEG), under leave-one-subject-out validation across three cognitively distinct tasks: abstract reasoning (IQ), arithmetic problem solving (MATH), and a game task (GAME). In this pilot setting, the results suggest that: (i) EEG is the strongest single modality, ranking highest in IQ, GAME, and the pooled ALL setting, where samples from all three tasks are combined; (ii) adding more modalities does not consistently improve performance; (iii) the full five-modality combination achieves the highest \textit{Average} score of $73.02%$ on IQ and $68.08%$ when the \textit{Average} scores are averaged over the four evaluation settings: IQ, MATH, GAME, and ALL; and (iv) the proposed method reduces model size by approximately $50%$ compared with late-fusion alternatives while maintaining a lower inference time.
### Title:
          Scene-Conditioned Relation Routing for urban cellular activity forecasting
 - **Authors:** Qingzhong Li, Jingye Lin, Hui Ma, Yajun Zhang, Xinjun Pei, Ming Yan, Fei Xing
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Urban cellular activity forecasting requires jointly modeling heterogeneous spatiotemporal signals, including SMS usage, mobile network traffic, and call activity. Existing methods often separate temporal modeling, spatial relation learning, and multi-signal prediction, relying on fixed graph structures or static multi-task learning schemes, which limits their adaptability to changing urban scenes. We propose SCRR-Net, a scene-conditioned spatial relation routing framework in which urban contextual information jointly controls spatial dependency selection and cross-task knowledge transfer. SCRR-Net includes a context encoder, a spatial graph expert routing module, a temporal Transformer encoder, and a task knowledge routing module. Experiments on the Milano and Trento datasets demonstrate that SCRR-Net consistently outperforms competing methods on SMS, network traffic, and call activity forecasting, while providing interpretable routing behaviors.
### Title:
          Strategic Transformer for Resource-Constrained Multi-Object Navigation in Ultra-Large-Scale Environments
 - **Authors:** Daiki Iwata, Kanji Tanaka, Senta Hishida
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Resource-constrained multi-object navigation in vast indoor environments ($>2,000\text{ m}^2$) poses significant challenges for efficiency and strategic planning. To tackle this, we reformulate the task as a Set Orienteering Problem (SOP), providing an optimization framework under resource constraints where exploitation is governed by the SOP model and exploration is managed by a separate heuristic switcher. Conventional baselines suffer from either rigid planning or myopic behaviors. To overcome these limitations and resolve the NP-hard computational challenges of SOP for real-time navigation, we develop the Strategic Transformer. This lightweight architecture functions as a priority planner that internalizes expert combinatorial logic into a predictable $41.03\text{ ms}$ forward pass while reducing teacher-student information asymmetry. Incorporating geometric attention biases allows the network to effectively model long-range structural dependencies. By coupling the Transformer's macro-plan with a bounded iterative 2-opt local refinement on a capped candidate graph, our framework achieves a $94\times$ speedup compared to heavy meta-heuristics, ensuring bounded-latency inference suitable for onboard deployment. Experiments on ProcTHOR validate that our method successfully bridges the gap between exploration and exploitation, outperforming carefully re-implemented baselines under Progress weighted by Path Length (PPL) and establishing a new benchmark for scalable, resource-constrained navigation.
### Title:
          Placement Is Free, Composition Is Not: The Latin Square as a Provably-Balanced Construction for Heterogeneous Sequence-Mixer Stacks
 - **Authors:** Taebong Kim, Youngsik Hong, Minsik Kim, Sunyoung Choi, Jaewon Jang, Minseo Kim
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Since GPT, most Transformers have repeated the same attention mechanism at every layer. Yet this design is largely a convention rather than a tested conclusion. When multiple sequence mixers are combined in one stack, improvements may arise from mechanism choice, placement, or both, making causal attribution difficult. We introduce Aether-7B-5Attn, a 6.59B-parameter mixture-of-experts model ($\approx$2.98B active) whose 49 layers contain seven sequence-mixing mechanisms arranged as a $7\times7$ Latin square. Because each mechanism appears exactly once in every row and column, the design guarantees balanced exposure across depth while eliminating placement confounds. To evaluate this principle, we build a parameter-matched proxy with four mechanisms arranged as a $4\times4$ Latin square over sixteen layers, matched to 700.9M parameters and trained with eight seeds per arm. The results reveal a clear dissociation. Rearranging a distributed heterogeneous stack into a balanced periodic cycle changes validation loss by only 0.16\%, indicating that exact placement has little effect. In contrast, clustering the same mechanisms into contiguous depth bands incurs a 0.59\% penalty, while replacing the heterogeneous stack with a homogeneous one incurs a 1.68\% penalty. These results indicate that performance depends primarily on heterogeneous composition distributed across depth rather than on any particular permutation. We confirm this finding at 2.16$\times$ larger scale (1.514B parameters), where the homogeneous-stack penalty increases to 2.63\% and removing the SSM-family mechanism produces a 3.20\% degradation. We further report per-mechanism cost profiles, English and Korean evaluations, and a causal-safety audit of all 49 layers. We release model weights, training recipes, training code, logs, and architecture source code.
### Title:
          Labeled Incidence Structures for Native Transformer Modeling of Text, Knowledge Graphs, and Hypergraphs
 - **Authors:** Mahesh Godavarti
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text, knowledge graphs, and hypergraphs all have elements that play distinct roles within relation instances, structure that is lost when data is flattened into token sequences. We introduce labeled incidence structures (LIS), a uniform representation that encodes each endpoint as $(x_d, s, e)$: content $x_d$, a role or slot $s$, and the relation instance $e$ in which that role appears. Because every data type maps to the same $(x_d, s, e)$ representation without flattening, a single standard transformer can process them all natively, structural differences are carried entirely by the operators, not the architecture. LIS assigns a structural address to each endpoint by composing a slot operator and an instance operator, $A(s,e) = R_s R_e$. We characterize when this factorization gives every token a unique, path-independent address. When it does, the natural operator comparing endpoint $j$ to endpoint $i$ is the relative transport $P_{j\to i} = A_i^{-1} A_j$, which gives attention a role- and relation-aware inductive bias without imposing an arbitrary sequence order. Additive encodings of the form "position term plus relation term" can miss information that depends jointly on $s$ and $e$. We prove this in a controlled example family: when the journey operator is approximated by the sum of a position-only term and a relation-only term, the approximation cannot capture how position and relation combine, only their separate effects. We also analyze persistent knowledge repositories. Identifiers tied to storage locations make models sensitive to storage order, while freely learned identifiers can become harder to control as the repository size $M$ grows relative to the sample size $n$. Computing relation-instance operators from content avoids this storage-order issue and yields a capacity bound independent of $M$, under fixed architectural and Lipschitz assumptions.
### Title:
          On the Turing Completeness of Transformers and Agents
 - **Authors:** Yimu Qiao, Lijia Yu, Ruichen Qiu, Xiao-Shan Gao
 - **Subjects:** Subjects:
Computational Complexity (cs.CC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers have emerged as the dominant architecture in sequence modeling, achieving remarkable success in natural language processing and reasoning tasks. While existing literature has established the Turing completeness of transformers under bounded input length, the reasoning power of a single transformer operating on inputs of unbounded length is not fully explored. In this paper, we theoretically investigate the reasoning limitations of a single transformer and the enhanced capabilities of agent systems. We show that a single fixed finite precision transformer cannot memorize certain Turing machines with inputs of arbitrary length, such as the arithmetic; and a single fixed infinite precision transformer trained with a random algorithm is not Turing complete with probability one under reasonable conditions. To overcome the limitation of a single transformer, we define a formal agent architecture consisting of decision, execution, and memory modules and show that for any Turing machine $\mathbb{T}$, there exists an agent that can memorize $\mathbb{T}$ and is computationally the same as $\mathbb{T}$. Thus, agents are Turing complete.
### Title:
          MM-Future: Multi-Mode Joint World-Action Modeling for Autonomous Driving
 - **Authors:** Shuai Liu, Hechangle Gong, Hao Jiang, Runlin He, Junxiang Zhan, Kai Huang, Sheng Yang, Shaoqing Ren
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving involves coupled decision-making and scene evolution under multi-mode uncertainty. To capture this coupling and uncertainty, we introduce MM-Future, a world-action model that generates multiple paired scene-action hypotheses and models bidirectional interaction within each pair. Each hypothesis is initialized from a structured action prior and an independent future scene source, which are then co-evolved through a modality-aware diffusion Transformer. To support efficient multi-mode rollout, MM-Future compresses multi-view video into planning-oriented representations, dubbed MM-Tokens. Finally, a future-conditioned proposal scorer ranks trajectory candidates by shared history context and their paired predicted future. On NAVSIM navtest, MM-Future achieves 94.0 PDMS and 91.5 EPDMS, while attaining a 32.3 HD-Score in zero-shot closed-loop evaluation on HUGSIM. Ablations show consistent improvements over both single-mode and action-only variants, validating the benefit of multi-mode joint world-action modeling.
### Title:
          Relational Attention for Data-Efficient Language Modeling
 - **Authors:** Adrian Brasoveanu, Ece Takmaz, Jakub Dotlačil
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Relational BabyLM, a system submission to the BabyLM 2026 challenge that combines two cognitively motivated inductive biases in a single decoder-only Transformer. Architecturally, we replace standard self-attention with a Dual Attention Transformer (DAT), which separates the routing of object-level ("sensory") lexical features from structural/relational information (Altabaa and Lafferty, 2025; Altabaa et al., 2024; Webb et al., 2024; Kerg et al., 2022; Webb et al., 2021). Relational attention (RA) disentangled from self-attention greatly increases data efficiency and out-of-training-sample generalization on purely relational tasks, but language modeling requires object-level and relational information to be integrated as well as disentangled, and RA-based LMs have remained largely unexplored. BabyLM's data-constrained training and comprehensive evaluation is an ideal testing ground for whether that data efficiency transfers. As a training intervention, we add a Next-Latent Prediction (NextLat; Teoh et al. 2026) objective that encourages hidden states to compress history incrementally into a dense belief state. Architecture is the dominant factor for structural linguistic generalization; the objective is secondary but still significant. DAT's three relational attention types (full RA vs. the simpler RCA and DisRCA variants) are largely interchangeable at 10M words; full RA pulls ahead at 100M. We also introduce a novel symbol-retrieval mechanism (RoPE-based, as opposed to learned, relative symbols) that matches learned symbol libraries while adding no parameters. On the strict (100M-word) track, our best model ranks 6th of 55 overall and 3rd of 55 on the leaderboard's NLP-task subset at the time of writing; our two strongest models outperform the GPT-2 baseline on most benchmarks, with one attaining the highest EWoK score among strict-track entries.
### Title:
          FreqCondNorm: Towards Cross-domain Predictive Maintenance through a Frequency-Conditioned Transformer Foundation Model
 - **Authors:** Zaynab Raounak, Camille LHermine, Zhiguo Zeng
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning predictive maintenance models suffer from poor transferability across machines and operating conditions, especially when labelled data are scarce and signals span five orders of magnitude in sampling frequency (1 Hz to ~100 kHz). We propose FreqCondNorm, a Transformer-based architecture that introduces a FiLM-style frequency-conditioned normalization layer to unify heterogeneous time-series within a single model. The architecture is pretrained on five public predictive maintenance datasets (CWRU, MFPT, UOC18, PRONOSTIA, CMAPSS) using masked auto-encoding and contrastive learning with balanced domain sampling. On fault diagnosis, the model achieves 99.2% accuracy on CWRU (+6.4 pp over CNN) and 82.1% zero-shot accuracy on MFPT, demonstrating strong transfer across sampling frequencies. However, the approach does not improve remaining useful life prediction, suggesting a mismatch between pretraining and RUL objectives that warrants future investigation.
### Title:
          MoWAM: Explicit Future Motion Prediction for Efficient World Action Models
 - **Authors:** Jiayu Wang, Bin Zhu, Yue Yu, Jingjing Chen
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World Action Models (WAMs) improve robot policy learning by incorporating future dynamics, yet explicitly generating future videos at inference introduces substantial computational overhead. Removing future generation improves efficiency, but leaves future dynamics only implicitly encoded in observation features, which can limit robustness under distribution shifts. We propose MoWAM, an efficient WAM that replaces future video generation with explicit future motion prediction. Instead of reconstructing the complete future scene, MoWAM models structured robot motion as a compact abstraction of the future, capturing how the robot is expected to evolve under the current scene and interaction constraints. A Mixture-of-Transformer architecture learns future visual dynamics during training while jointly predicting motion and action, allowing video generation to be removed entirely at inference while retaining an explicit representation of the future. The compact motion representation further enables efficient inference-time scaling by sampling multiple candidates of motion and action pairs and selecting among them with a motion-aware task-progress verifier. Experiments on LIBERO, LIBERO-Plus, and real-world manipulation tasks demonstrate that MoWAM achieves strong in-distribution performance, improved out-of-distribution robustness, and higher average real-world success than representative WAM baselines. In addition, performance improves as more candidates are explored, demonstrating that explicit future motion provides an effective and efficient basis for inference-time scaling.
### Title:
          PixelFlow: Token-Level Workload Management for Efficient Distributed DiT Serving
 - **Authors:** Zhexiang Zhang, Minchen Yu, Yifan Sun, Xu Bai, Xingliang Yuan, Adel N. Toosi
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Online image generation with Diffusion Transformers (DiTs) must meet latency service-level objectives (SLOs) while using GPU resources efficiently. Existing systems improve GPU utilization by batching multiple requests for joint execution. However, request-level batching offers limited control over batch size: batches may be too small to saturate GPU compute, while larger ones may violate latency SLOs. Globally coordinated scheduling introduces further delays by requiring independently progressing GPUs to synchronize before admitting new work. We present PixelFlow, a distributed DiT serving system that addresses these limitations through token-level workload management. Its key idea is to use image tokens (the units a DiT processes to generate an image) to divide and batch request workloads at a finer granularity. This allows each GPU to take on a portion of additional work under latency constraints. By distributing these portions across GPUs, PixelFlow accommodates more concurrent requests, improving GPU utilization while reducing queueing delays. To realize this flexibility, PixelFlow provides a runtime that splits requests into variable-sized partitions and batches them efficiently on each GPU. To reduce the resulting communication overhead, it optimizes token placement to limit cross-GPU data exchange while balancing GPU workloads. It further exploits similarity across denoising steps to overlap the remaining transfers with computation. An SLO-aware scheduler groups GPUs to share compute resources among requests with compatible latency requirements. Each group progresses independently, synchronizing with others only when their combined resources are needed to admit a new request. Evaluation with Stable Diffusion 3 and FLUX.1-dev on H100 GPUs shows that PixelFlow improves SLO attainment by up to 43% and achieves up to 2.8 times the goodput of state-of-the-art DiT serving systems.
### Title:
          dQwen3.5: Hybrid-Attention Diffusion Language Models
 - **Authors:** Anton Xue, Litu Rout, Aditya Akella, Adam Klivans, Sujay Sanghavi, Sanjay Shakkottai
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adapting a pretrained autoregressive (AR) model is a cost-efficient route to a diffusion language model (DLM). While nearly all such adaptations start from a full-attention transformer, AR modeling has shifted toward hybrid architectures that interleave attention and RNN layers. This creates an obstacle for adaptation: unlike attention, RNNs are structurally causal and nontrivial to bidirectionalize. Despite this mismatch, we investigate whether such backbones can become effective DLMs by adapting Qwen3.5 at 0.8B, 2B, 4B, and 9B scales, yielding the dQwen3.5 family. We find that hybrid backbones can be efficient starting points for adaptation: against a full-attention control, the hybrid reaches a given training loss in about half the tokens. Across scales, dQwen3.5 resembles full-attention DLMs in any-order decoding behavior and performs strongly under parallel decoding.
### Title:
          FAMOS: Feed-Forward 3D Articulation Modeling from Sparse Observations
 - **Authors:** Kevin Qu, Tao Sun, Massimiliano Viola, Liyuan Zhu, Zhizhuo Zhou, Sayan Deb Sarkar, Konrad Schindler, Iro Armeni
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modeling articulated objects from sparse monocular views is challenging because each observation reveals only partial geometry and motion evidence. Most feed-forward methods infer articulation from a single observation and therefore rely heavily on learned category-level shape priors. We present FAMOS, a feed-forward model that predicts movable-part segmentation and joint parameters from a sparse, unordered set of partial point clouds. Our model jointly reasons over multiple observations and naturally supports a variable number of inputs, including a single view. To aggregate articulation cues across observations, we introduce a Multi-state Articulation Transformer with alternating state-wise and global attention. We further propose an observed articulation span objective that supervises the motion range each part exhibits across the input observations, encouraging the model to leverage the full observation set. To overcome the limited scale and diversity of existing datasets, we introduce a procedural data generator that synthesizes self-annotated assets during training. Experiments on PartNet-Mobility, ACD, and ArtiCraft-10K demonstrate consistent improvements over both feed-forward and optimization-based baselines. Project page: this https URL
## Keyword: autonomous driving
### Title:
          4D Radar Perception Algorithms for Autonomous Driving: A Review
 - **Authors:** Xumin Wu, Jun Zhou, Jilin Mei, Chen Min, Yu Hu
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Research on 4D millimeter-wave radar perception algorithms has flourished in recent years, extending from signal processing and object detection to semantic segmentation, motion estimation, occupancy prediction, and dynamic scene reconstruction. This review organizes the field according to the evolution of perception tasks and algorithms. It first introduces radar fundamentals, data representations, and quality-enhancement methods, and then reviews object-level perception, motion and localization, local and dense spatial perception, and dynamic scene understanding. Across these directions, we compare radar-only learning, multimodal fusion, and cross-modal supervision and knowledge distillation. Particular attention is paid to how elevation, Doppler measurements, and radar physical priors are exploited across tasks. We further summarize the task coverage, input data, annotations, and evaluation protocols of existing datasets, clarifying the empirical support for different research directions. Finally, we discuss the common challenges and future directions of 4D radar perception for autonomous driving. This review provides a task-oriented perspective on the transition from sparse object perception to dynamic spatial understanding.
### Title:
          Open-vocabulary 3D object detection with promptable segmentation
 - **Authors:** Ömer Faruk Deniz, Mustafa Taha Koçyiğit
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Three-dimensional object detection for autonomous driving is dominated by detectors trained on large corpora of human-annotated 3D boxes. Such a detector learns a fixed category list, and everything outside it is invisible. This paper asks whether the task can be solved training-free and open-vocabulary. A promptable segmentation model (SAM3), queried with class names as text prompts, supplies instance masks in the vehicle's six surround-view cameras, and the masks are turned into metric 3D boxes using the geometry of the scene. The core is a controlled three-stage comparison on nuScenes in which 2D detection is held fixed and only the source of 3D geometry changes. Geometry predicted from images alone reaches 0.183 mean average precision (mAP) under the official protocol; fitting boxes from raw LiDAR points inside the same masks with training-free rules reaches 0.298 mAP / 0.348 nuScenes detection score (NDS) at zero labeling cost; borrowing supervised box geometry at inference time lifts the same detections to 0.413 mAP / 0.555 NDS, which locates the pipeline's largest deficit in measurement precision rather than 2D detection, while class confusion and confidence calibration survive that substitution. Reversing the direction, a three-state camera-witness rule built from the same masks improves a supervised LiDAR-only detector from 0.596 to 0.630 mAP, roughly half the gain of fully supervised camera fusion, with no training. A coverage analysis shows that SAM3 finds 84% of in-range objects with a correctly named mask; the classes that fail in the official metric are misnamed or geometrically unforgiving, not unseen.
### Title:
          VAST: V2X/Dynamic Map-Aware Autonomous Driving Systems Validation Toolchain
 - **Authors:** Shunsuke Ito, Takuya Azumi
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cooperative autonomous driving in the IoT-to-Edge-to-Cloud continuum requires system-level validation across vehicles, infrastructure sensors, edge-side Dynamic Map services, and in-vehicle autonomous-driving stacks. This paper presents VAST, a V2X/Dynamic Map-aware validation toolchain that connects Scenic, Scenario Simulator v2, AWSIM, Autoware, and SIM-LDM. VAST does not introduce a new search algorithm; instead, it addresses interoperability challenges, including Lanelet2-to-Scenic mapping, ROS 2-based co-simulation through SS2, Dynamic Map object injection into Autoware, and collection of TTC, PET, collision, timeout, and performance measurements. In occluded-intersection scenarios, Lanelet2-compatible constrained sampling increases the edge-case discovery rate from 40.0% to 80.0% and reduces the average time per discovered edge case from 259.7 s to 110.4 s. Under the same generated scenario distribution, Dynamic Map availability reduces the collision rate from 78.0% to 40.0% and increases non-collision outcomes from 22.0% to 60.0%, with statistically significant TTC/PET shifts. A throughput study with 1-16 NPCs shows that sampling remains below 0.1 s, whereas AWSIM/Autoware execution and restart overhead dominate runtime. These results position VAST as a practical validation infrastructure for cooperative autonomous-driving CPSs.
### Title:
          Vehicle Trajectory Prediction via Neural Fusion of Multiple EKF-Based Trajectory Candidates
 - **Authors:** Seong-Jun Kim, Seung-Hyun Kong
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Predicting the future trajectories of surrounding vehicles in autonomous driving is important for collision risk assessment and safe ego-vehicle path planning. Conventional neural network-based trajectory predictors typically achieve strong prediction performance by exploiting agent history, dynamic scene graphs, and semantic maps. However, in specific motion regimes such as acceleration, deceleration, and turning, these predictors may fail to reflect physically feasible trajectories. To address this issue, this study proposes a framework that fuses the output of Trajectron++, a neural network-based trajectory predictor, with extended Kalman filter (EKF)-based multiple trajectory candidates at a late stage. On the nuScenes dataset, the proposed method reduces the average displacement error and final displacement error of the Trajectron++ robot baseline by 13.7% and 14.6%, respectively, without modifying the baseline architecture. These results indicate that EKF-based trajectory candidates can effectively complement neural trajectory prediction through learned fusion.
### Title:
          REARL: A Closed-loop Autonomous Driving Simulation Enhancement Framework with Real Traffic Data and Large Language Models
 - **Authors:** Xiaojun Bi (1), Jun Jiang (1), Yiwen Sun (2 and 3), Quanyi Ou (1), Ke Cheng (4), Mingjie Bi (3), Yexin Li (3) ((1) Minzu University of China, Beijing, China, (2) Peking University, Beijing, China, (3) BIGAI, Beijing, China, (4) Beihang University, Beijing, China)
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate simulation is crucial for autonomous driving development, yet capturing real-world traffic complexity remains challenging. Existing simulators that rely on predefined rules or static data playback struggle with dynamic traffic. CRITICAL uses real traffic data and a large language model (LLM) to adjust the initial simulation configuration, but the simulated distribution still diverges from real traffic as the rollout evolves. We propose REARL, a closed-loop simulation enhancement framework that integrates real traffic data with LLMs. Real traffic data are clustered, and each cluster center is used as a representative scenario that provides typical real-world traffic patterns for the LLM. A timed sliding-window detector then monitors discrepancies in vehicle speed distribution and mean spacing between pairs of vehicles. If a metric exceeds a threshold, the LLM adjusts vehicle decision-making; otherwise the existing controller is kept. The LLM also selects a matching real vehicle from a traffic snapshot and modulates the simulated vehicle with reference to that real action. In a controlled HighD highway setting, compared with the CRITICAL baseline and a PPO-based learning baseline, REARL reduces the Hellinger distance for speed distributions to 0.3067 and the MAPE for mean spacing to 0.8371, while achieving a time headway (THW) of 22.8575 and a lane change rate of 0.0708.
### Title:
          Astronex-World 1.0: Real-Time Interactive World Model Foundation
 - **Authors:** Xin Zhou, Cong Miao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Astronex-World 1.0, an open controllable video world-model foundation. Given a text prompt (text-to-video) or an initial observation (image-to-video), the model predicts future visual states under frame-aligned camera trajectories, continuous actions, and an embodiment identifier, and accepts text events inserted at a specified position of a rollout. The family provides a bidirectional model for full-context generation and a causal model with block-causal attention and cross-block KV caching for persistent generation, both built on the Wan2.2-TI2V-5B prior. PRoPE injects camera intrinsics and extrinsics, while a 64-dimensional action stream modulates every Transformer layer. A five-stage training path develops bidirectional camera and action control, converts the backbone to block-causal generation, distills a few-step student, restores mixed-domain dynamics, and applies asymmetric DMD/DMD2 distribution matching. The causal model generates 832x480 video at 24 fps. All five training stages run on two NVIDIA L20 48 GB GPUs, and the causal model streams in real time on one. It scores 73.5 on WBench Navi and 70.0 on WBench Full. On Full, this 5B model is above the 13.6B LongCat-Video and the 14B Helios, within one point of the 22B LTX-2.3, and above YUME 1.5, which is post-trained from the same 5B prior on NVIDIA A100 GPUs. The reserved action input and output interfaces allow post-training for embodied intelligence and autonomous driving.
### Title:
          LLM-Guided Transformation of Non-Critical Driving Scenes into Safety-Critical Scenarios Using Augmented Reality
 - **Authors:** Noura Fady, Farah Khaled, Catherine M. Elias
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Testing Autonomous Driving Systems (ADS) requires realistic safety-critical scenarios, but collecting such data from real-world driving is costly and unsafe. This paper presents an automated pipeline that transforms safe driving scenes into safety-critical scenarios by combining computer vision, Large Language Models (LLMs), and Augmented Reality (AR). The system detects and tracks road users, extracts safety features including distance, velocity, motion direction, and Time-to-Collision (TTC), and assesses scene criticality. Safe scenes are modified by an LLM, which generates realistic collision-inducing objects and behaviors that are integrated into the original scene using AR. The proposed pipeline was evaluated on the nuScenes dataset, achieving 97.52% safety classification accuracy and successfully generating realistic scenarios such as pedestrian crossings, rear overtaking vehicles, and sudden-stop events. The results demonstrate an effective and flexible approach for automated generation of safety-critical scenarios to support the testing and validation of autonomous driving systems.
### Title:
          MM-Future: Multi-Mode Joint World-Action Modeling for Autonomous Driving
 - **Authors:** Shuai Liu, Hechangle Gong, Hao Jiang, Runlin He, Junxiang Zhan, Kai Huang, Sheng Yang, Shaoqing Ren
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving involves coupled decision-making and scene evolution under multi-mode uncertainty. To capture this coupling and uncertainty, we introduce MM-Future, a world-action model that generates multiple paired scene-action hypotheses and models bidirectional interaction within each pair. Each hypothesis is initialized from a structured action prior and an independent future scene source, which are then co-evolved through a modality-aware diffusion Transformer. To support efficient multi-mode rollout, MM-Future compresses multi-view video into planning-oriented representations, dubbed MM-Tokens. Finally, a future-conditioned proposal scorer ranks trajectory candidates by shared history context and their paired predicted future. On NAVSIM navtest, MM-Future achieves 94.0 PDMS and 91.5 EPDMS, while attaining a 32.3 HD-Score in zero-shot closed-loop evaluation on HUGSIM. Ablations show consistent improvements over both single-mode and action-only variants, validating the benefit of multi-mode joint world-action modeling.
### Title:
          Worst-Case Hidden-Vehicle Trajectory Search in Spatiotemporal Occlusion Regions
 - **Authors:** Ruichen Tan, Zengxiang Lei, Satish Ukkusuri
 - **Subjects:** Subjects:
Robotics (cs.RO); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Occlusion creates fundamental uncertainty in autonomous driving. Existing methods often propagate frame-wise hypotheses or optimize ego behavior against prescribed hidden-agent predictions, leaving the worst history-consistent interaction unexplored. We introduce History-Conditioned Minimax Trajectory Search (HC-MTS), which combines temporal occlusion reasoning with response-aware search. First, HC-MTS constructs finite hidden-state modes, each certified by a backward witness satisfying multi-frame visibility, occupancy, semantic-map support, and class-specific kinematic constraints. It then solves a bilevel minimax problem: an inner finite oracle maximizes the ego driving score over destination attainment and ride comfort, while the outer search selects the legal hidden-vehicle trajectory that minimizes this best-response value. Across eight Waymo Open Motion Dataset scenarios, increasing the visibility-memory horizon from K=1 to K=20 reduces the mean per-scenario vehicle, pedestrian, and total retained hidden-seed counts by 18.12%, 21.67%, and 18.45%, respectively. HC-MTS identifies six avoidable counterexamples, while no legal collision-producing attacker is found in the remaining two scenes within the finite search budget.
### Title:
          MILER: Semantic Mid-Level Representation for Sim-to-Real Reinforcement Learning in Unstructured Autonomous Driving
 - **Authors:** Thomas Steinecker, Denis Trescher, Alexander Bienemann, Thorsten Luettel, Mirko Maehlisch
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reinforcement learning constitutes a promising approach owing to its potential for superhuman performance and self-learned policies. However, its application to real-world autonomous driving remains scarce, particularly in unstructured environments, because of the challenges associated with sim-to-real transfer for unstructured environments. In this work, we present MILER, an end-to-end policy framework with zero-shot sim-to-real transfer. During offline training, we employ a custom semantic mid-level representation (MLR) simulator and train the policy network using reinforcement learning, with its control outputs applied directly to a bicycle model. During deployment on the real vehicle, camera and LiDAR data are processed by BEVFusion to generate a semantic bird's-eye-view representation consistent with that of the MLR simulator. The actions generated by the policy network are not applied directly to the real vehicle. Instead, we employ a trajectory-alignment strategy that enables zero-shot sim-to-real transfer of both perception and control. We extensively evaluate the proposed framework on a diverse test track comprising numerous challenges, including various obstacles, hairpin curves, velocities of up to 33.6 km/h, and off-road sections. In total, we drove 17.3 km with two different vehicles on a 3.0 km test track without human intervention, thereby demonstrating the effectiveness of our approach. Furthermore, the entire software stack runs on a Jetson AGX Orin.
### Title:
          OPTED: On-Policy Fine-Tuning for End-to-End Driving using a Render-Free Teacher
 - **Authors:** Damiano Da Col, Maximilian Igl, Peter Karkus, Kashyap Chitta, Boris Ivanovic, Marco Pavone, Konrad Schindler, Christos Sakaridis
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As scaling pre-training data alone yields diminishing returns, post-training is becoming increasingly important across physical AI domains such as autonomous driving. End-to-end driving policies are pre-trained in open loop with behavior cloning on human demonstrations. However, compounding errors during closed-loop deployment can take the vehicle outside the training data distribution, increasing the risk of safety-critical incidents. Closed-loop post-training can mitigate this risk but requires costly simulation for sensor-based policies. We propose OPTED (on-policy fine-tuning for end-to-end driving) which decouples reinforcement learning from the post-training of the end-to-end policy: a privileged teacher is trained using RL on vectorized inputs (HD-map and bounding boxes). This teacher then provides supervision to the pre-trained student during closed-loop post-training. We apply OPTED to two camera-based models, TransFuser and VaVAM, and fine-tune them in AlpaSim, using neural reconstructions (3DGS) of real driving logs. Driving scores increase by factors of 1.6$\times$ and 9.5$\times$, respectively. In controlled experiments OPTED matches closed-loop performance with approximately three orders of magnitude fewer simulator interactions than direct RL post-training, while staying closer to the human prior. Project page: this https URL
