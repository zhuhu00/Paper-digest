# Showing new listings for Thursday, 25 June 2026
## Keyword: SLAM
### Title:
          OrthoTrack: Continuous 6-DoF UAV Trajectory Estimation Anchored in Public Orthophotos
 - **Authors:** Oussema Dhaouadi, Zuria Bauer, Johannes Michael Meier, Olaf Wysocki, Marc Pollefeys, Daniel Cremers
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Continuous 6-DoF pose estimation is essential for autonomous UAV operations. Yet, existing visual odometry and SLAM methods accumulate drift and yield only relative, up-to-scale trajectories. Single-frame geo-localization, in turn, discards temporal continuity and remains too slow for real-time use. We present OrthoTrack, a training-free system that estimates continuous 6-DoF UAV trajectories using only publicly available orthophotos and surface models as a map prior. OrthoTrack matches keyframes against the orthophoto and lifts correspondences to metric 3D via the surface model. It then propagates these map-anchored correspondences to intermediate frames with optical flow, producing absolute, metrically scaled poses at every frame without GPS or post-hoc alignment. We also introduce the MovingDrone Dataset, a large-scale benchmark pairing photorealistic UAV sequences with dense 6-DoF ground truth and co-registered multi-modal geodata including multi-temporal orthophotos. On MovingDrone and real-world benchmarks, OrthoTrack runs in real time on a single GPU. It outperforms all baselines by a large margin, even those receiving oracle scale and alignment. By relying on publicly available geodata, OrthoTrack enables deployment to new regions without site-specific adaptation.
### Title:
          DSP-SLAM++: A Unified Framework for Multi-Class, High-Fidelity Object SLAM in the Wild
 - **Authors:** Ahmad Kourani, Ghina Daoud, Daniel Asmar, Imad Elhajj
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing object-aware SLAM systems force a trade-off between real-time performance, multi-class support, and the generation of high-fidelity, semantically coherent object models. To address this trade-off, we present DSP-SLAM++, which extends the DSP-SLAM framework with an asynchronous mapping pipeline for real-time performance and dedicated sensor fusion adaptations for a monocular fisheye-LiDAR suite. Experiments demonstrate that our system generates fine-grained, geometrically-complete shapes for multiple object classes while eliminating severe mapping thread bottlenecks by reducing maximum object processing latency by up to 70\% compared to the state-of-the-art baseline, enabling robust, real-time performance on a challenging 25 Hz multi-class datasets. This work makes high-fidelity, multi-class object SLAM more practical for real-world applications like autonomous driving and robotic manipulation by enabling its use on platforms with common fisheye-LiDAR sensor setups. The open-source code is available at: [this http URL].
### Title:
          RoboAtlas: Contextual Active SLAM
 - **Authors:** Alexander Schperberg, Shivam K. Panda, Abraham P. Vinod, M. K. Jawed, Stefano Di Cairano
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present RoboAtlas, a contextual Active SLAM framework that adaptively balances geometric exploration and semantic reasoning using a scalable 3D semantic mapping system, OpenRoboVox. RoboAtlas integrates frontier exploration, global semantic-map reasoning, and egocentric VLM-based reasoning through a contextual multi-armed bandit that transitions from exploration to semantically guided navigation as scene understanding improves. We evaluate the system in simulation and on a Unitree Go2 robot in large-scale real-world environments exceeding 1800 m2 with approx. 30k mapped semantic instances, achieving a 100% task success rate. On the GOAT-Bench "Val Unseen" benchmark, RoboAtlas achieves state-of-the-art performance with highest reported success rate (SR) of 90.6%, using GPT-4o, improving over the strongest prior baseline by 17.8 percentage points in SR. Using the much smaller Qwen2.5-VL-7B model, it still achieves 88.8% SR, outperforming all baselines using GPT-4o in SR, and revealing the importance of the information gained by our semantic mapping framework over simply replacing the underlying foundation model. The results demonstrate that grounding foundation models with large-scale 3D semantic maps enables robust and efficient contextual Active SLAM.
## Keyword: odometry
### Title:
          OrthoTrack: Continuous 6-DoF UAV Trajectory Estimation Anchored in Public Orthophotos
 - **Authors:** Oussema Dhaouadi, Zuria Bauer, Johannes Michael Meier, Olaf Wysocki, Marc Pollefeys, Daniel Cremers
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Continuous 6-DoF pose estimation is essential for autonomous UAV operations. Yet, existing visual odometry and SLAM methods accumulate drift and yield only relative, up-to-scale trajectories. Single-frame geo-localization, in turn, discards temporal continuity and remains too slow for real-time use. We present OrthoTrack, a training-free system that estimates continuous 6-DoF UAV trajectories using only publicly available orthophotos and surface models as a map prior. OrthoTrack matches keyframes against the orthophoto and lifts correspondences to metric 3D via the surface model. It then propagates these map-anchored correspondences to intermediate frames with optical flow, producing absolute, metrically scaled poses at every frame without GPS or post-hoc alignment. We also introduce the MovingDrone Dataset, a large-scale benchmark pairing photorealistic UAV sequences with dense 6-DoF ground truth and co-registered multi-modal geodata including multi-temporal orthophotos. On MovingDrone and real-world benchmarks, OrthoTrack runs in real time on a single GPU. It outperforms all baselines by a large margin, even those receiving oracle scale and alignment. By relying on publicly available geodata, OrthoTrack enables deployment to new regions without site-specific adaptation.
### Title:
          Delta-Position Estimation-Based IMU Odometry: A Comparison of MLP and Kolmogorov-Arnold Networks
 - **Authors:** Osman Tokluoglu, Emin Keresteci
 - **Subjects:** Subjects:
Robotics (cs.RO); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this study, the learning-based inertial odometry problem is investigated using raw IMU measurements obtained from the EuRoC MAV benchmark dataset. Instead of absolute position regression-a formulation that may lead to large constant errors-the models are trained to estimate the incremental displacement ({\Delta}p) over a fixed 50 ms sliding window, and the full trajectory is reconstructed through numerical integration. A standard Multi-Layer Perceptron (MLP) is compared with a Kolmogorov-Arnold Network (KAN) equipped with learnable B-spline activations. Although KAN has 6.9 times fewer parameters than MLP (8,444 versus 57,859), it produces a 44% lower error in terms of final cumulative drift on the test trajectory (9.61 m versus 17.23 m). In addition, KAN exhibits more stable behavior in terms of long-term error accumulation, with lower P_50 and P_90 cumulative drift values. These findings indicate that learnable B-spline-based activations have the potential to reduce error accumulation in the inertial odometry problem.
### Title:
          SA-LIVO: Efficient LiDAR-Inertial-Visual Odometry with Subspace-Aware Degeneracy Handling
 - **Authors:** Yinong Cao, Xin He, Yuwei Chen, Shijie Liu, Chunlai Li, Jianyu Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tightly coupled LiDAR-visual-inertial odometry (LIVO) fuses precise geometric depth with complementary visual measurements, yet its exteroceptive sensors face independent failure modes: LiDAR degenerates when scan geometry is under-constrained, while visual measurements degrade under adverse illumination or texture absence. Existing countermeasures, including binary degeneracy detection, covariance inflation, and scene-level quality gating, operate at the modality level and leave the direction-dependent structure of the joint information matrix unaddressed. Consequently, visual residuals enter pose directions where LiDAR is well-constrained, while in deficient directions visual compensation disperses across the full state space rather than concentrating where needed. We propose SA-LIVO, a LiDAR-inertial-visual odometry system addressing these limitations through direction-selective fusion and information-efficient processing. The Subspace-Aware Information Fusion (SAIF) framework eigendecomposes the joint LiDAR-visual information matrix and applies a linear-clamp soft gate per eigendirection, attenuating degenerate directions while preserving observable ones at full strength. LiDAR and visual residuals are then jointly optimized in one InEKF loop at a shared linearization point. Since visual information contributes only where LiDAR is deficient, photometric Jacobians are assembled once before the loop and reused across iterations, avoiding the per-iteration cost of conventional iterated filters. Experiments on 29 sequences from three benchmarks (HILTI'22, New College, Oxford Spires) and concurrent-degradation scenarios show accuracy competitive with the strongest baselines and bounded drift where competing systems diverge. SA-LIVO averages 12.3 ms per frame on a laptop CPU and 26.8 ms on an embedded ARM board without GPU, with 3.6-6.3x lower peak memory. The code will be open-sourced.
### Title:
          FAR-LIO: Enabling High-Speed Autonomy through Fast, Accurate, and Robust LiDAR-Inertial Odometry
 - **Authors:** Maximilian Leitenstern, Marcel Weinmann, Patrick Haft, Tobias Lasser, Dominik Kulmer, Markus Lienkamp
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust and accurate odometry estimation is essential in modern robotics. In environments characterized by highly dynamic motion and sensor noise, odometry estimation becomes increasingly challenging. Autonomous racing combines both factors in an unstructured setting, where minimizing odometry latency is essential for stable closed-loop control. This paper introduces FAR-LIO, a highly optimized CUDA-accelerated LiDAR-inertial odometry framework developed for Fast, Accurate, and Robust performance. Our system leverages a novel CUDA-based voxel hashmap to enable parallelized nearest-neighbor search and efficient map updates. We employ a sparsity-aware Generalized Iterative Closest Point algorithm with adaptive thresholding on top of the CUDA-based voxel hashmap with adaptive density to achieve low-latency without compromising accuracy. An Extended Kalman Filter serves as a robust backend. It utilizes an upsampling and delay compensation strategy to fuse the LiDAR odometry with high-frequency IMU data, thereby ensuring a robust and smooth odometry output. We evaluate FAR-LIO across four different sensor setups, using both public datasets and data from two autonomous racecars driving at speeds of up to 250 km/h. FAR-LIO achieves an average 6.9% reduction in the positional error and 38.4% lower runtime compared to state-of-the-art baselines on target hardware using a single parameter set. This demonstrates its computational efficiency and broad applicability. To build upon our work, our code is available open-source on this https URL.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Commerge: Communication-Efficient, Robust, and Fast LiDAR Map Merging Framework for Multi-Robot Coordination in Resource-Constrained Scenarios
 - **Authors:** Hogyun Kim, Jiwon Choi, Juwon Kim, Geonmo Yang, Seokhwan Jeong, Hyungtae Lim, Younggun Cho
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 By maintaining global consistency across robot teams, multi-robot LiDAR map merging enables faster exploration and efficient area coverage. However, map merging requires exchanging massive sensor data between the server and robots, making communication the bottleneck, especially in communication-constrained environments. Therefore, we present Commerge, a communication-efficient map merging framework that achieves bandwidth reduction through graph-theoretic selective data exchange. By doing so, our Commerge reduces inter-robot communication by up to 5,000x while maintaining alignment accuracy. Our key insight is that only a small subset of carefully selected scans is sufficient for robust map merging. We formulate this as a three-stage cascaded optimization problem on an exchange graph, where vertices represent robot keyframes and edges denote candidate inter-robot loops. Through three cascade stages, we select a sequentially overlapped, balanced-transmission-cost, and geometrically-perceptually optimal scan subset that preserves alignment quality while reducing communication. Unlike existing approaches that either transmit whole scans, which require GB-scale data exchange, or employ naive downsampling, our approach exchanges only MB-scale data while achieving comparable alignment accuracy. Extensive evaluation on five public datasets and four in-house datasets covering cave, planetary-analog, indoor, and outdoor campus environments shows up to 99.98% reduction in data exchange (e.g., from 7,000MB to 1.3MB on the HeLiPR dataset), while maintaining alignment performance across embedded to desktop platforms. The supplementary materials are available at this https URL.
### Title:
          Large-Scale Tunnel Air--Ground Collaboration With FLISP: Fast LiDAR-IMU Synchronized Path Planne
 - **Authors:** Fenghe Guo, Runjie Shen, Chenyang Sun, Junrui Zhang, Quanxi Zhan, Yongchun Wang, Junjie Zhang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hydropower tunnel inspection is critical for infrastructure integrity yet remains inefficient and hazardous using manual methods. We propose FLISP (Fast LiDAR-IMU Synchronized Path Planner), a mapless planning framework for cooperative UGV-UAV inspection. Unlike traditional map-based paradigms, FLISP features three core contributions: (1) a unified architecture where a single UGV-mounted LiDAR-IMU suite drives synchronized path generation for both platforms; (2) platform-specific solvers utilizing an enhanced Firefly Algorithm for UGV obstacle avoidance and a dynamic iterative optimizer for UAV flight; and (3) a hierarchical refinement strategy ensuring kinematic feasibility without state estimation drift. Benchmarks in a 1.2 km operational tunnel demonstrate that FLISP circumvents structural bottlenecks of map-based methods, eliminating map rasterization overhead (Fast-LIO2 + A*) and sampling instability (LIO-SAM + RRT*). FLISP achieves a 100% success rate with ~7 ms latency, representing a 7-fold speedup over grid-based and three-order-of-magnitude improvement over sampling-based baselines. Validated in operational hydropower tunnels, this approach offers a scalable solution for robotic inspection in feature-degraded linear infrastructure. A demonstration video is available at this https URL, and the code at this https URL.
### Title:
          Auto-Labelling-Based Domain Transfer for 3D Object Detection on a Bicycle-Mounted LiDAR Platform
 - **Authors:** Mario Finkbeiner, Max A. Buettner, Kanak Mazumder, Fabian B. Flohr
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable 3D perception of vulnerable road users (VRUs) such as cyclists and pedestrians is essential for their safety in urban traffic and a core requirement for autonomous driving (AD). Alongside advances in vehicle-based perception, research increasingly equips bicycles with sensors to study traffic from a perspective native to VRUs. Such platforms still rely on LiDAR detectors originally trained on vehicle data, yet annotated 3D data from a cyclist's perspective is scarce. How well these detectors generalise to this setting has not been evaluated. We present a 3D object detection benchmark of 1,027 annotated LiDAR keyframes (over 18,000 3D bounding boxes) from the FUSE-Bike platform in urban Munich. We evaluate four nuScenes-pre-trained detectors against 1,854 human-verified ground-truth (GT) boxes both in their original form and after finetuning on training labels produced by a VRU-dedicated auto-labelling pipeline that requires no manual annotation. The zero-shot domain gap is concentrated on the VRU classes. Finetuning recovers most of it, improving mean average precision (mAP) by up to 23.4 points with the largest gains on pedestrians and cyclists, and the adapted detectors even surpass the quality of the auto-labels they were trained on. The benchmark provides a reproducible baseline for VRU-centric 3D detection and shows that auto-labels are a viable substitute for manual annotation when adapting vehicle-trained detectors to a cyclist platform.
### Title:
          SA-LIVO: Efficient LiDAR-Inertial-Visual Odometry with Subspace-Aware Degeneracy Handling
 - **Authors:** Yinong Cao, Xin He, Yuwei Chen, Shijie Liu, Chunlai Li, Jianyu Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tightly coupled LiDAR-visual-inertial odometry (LIVO) fuses precise geometric depth with complementary visual measurements, yet its exteroceptive sensors face independent failure modes: LiDAR degenerates when scan geometry is under-constrained, while visual measurements degrade under adverse illumination or texture absence. Existing countermeasures, including binary degeneracy detection, covariance inflation, and scene-level quality gating, operate at the modality level and leave the direction-dependent structure of the joint information matrix unaddressed. Consequently, visual residuals enter pose directions where LiDAR is well-constrained, while in deficient directions visual compensation disperses across the full state space rather than concentrating where needed. We propose SA-LIVO, a LiDAR-inertial-visual odometry system addressing these limitations through direction-selective fusion and information-efficient processing. The Subspace-Aware Information Fusion (SAIF) framework eigendecomposes the joint LiDAR-visual information matrix and applies a linear-clamp soft gate per eigendirection, attenuating degenerate directions while preserving observable ones at full strength. LiDAR and visual residuals are then jointly optimized in one InEKF loop at a shared linearization point. Since visual information contributes only where LiDAR is deficient, photometric Jacobians are assembled once before the loop and reused across iterations, avoiding the per-iteration cost of conventional iterated filters. Experiments on 29 sequences from three benchmarks (HILTI'22, New College, Oxford Spires) and concurrent-degradation scenarios show accuracy competitive with the strongest baselines and bounded drift where competing systems diverge. SA-LIVO averages 12.3 ms per frame on a laptop CPU and 26.8 ms on an embedded ARM board without GPU, with 3.6-6.3x lower peak memory. The code will be open-sourced.
### Title:
          MIL-LC: A Robust Magnetometer-Inertial-LiDAR Fusion Multimodal Localization Framework
 - **Authors:** Qiyang Lyu, Zhenyu Wu, Wei Wang, Hongming Shen, Danwei Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Localization in challenging environments, such as GNSS-denied, geometrically repetitive, or textureless scenes commonly found in offices, hotels, and underground parking facilities, remains an open problem for reliable autonomous mobile robot (AMR) deployment. Single-modality localization methods are inherently limited by the constraints of individual sensors. Although multimodal fusion frameworks have shown improved robustness, most existing approaches still rely heavily on geometric or texture features, or on infrastructure-based beacons, which increase installation and maintenance costs while reducing deployment flexibility. Recently, ambient magnetic field (AMF)-based localization has attracted growing attention because it does not depend on geometric or texture features, nor does it require additional infrastructure, making it a promising complementary modality for AMR localization. However, existing studies have only explored such fusion in pedestrian scenarios using smartphone-mounted sensor suites, and practical solutions for AMR systems remain largely unexplored. To address this gap, this article proposes a magnetometer-inertial-LiDAR fused multimodal localization framework with a custom-designed sensor suite, termed MIL-LC, which provides reliable localization even when LiDAR suffers from geometric degeneration or when the magnetic map changes during long-term deployment. Extensive experiments in both simulation and real-world environments demonstrate that the proposed MIL-LC framework achieves robust and accurate localization performance.
### Title:
          Beyond a Shadow of a Doubt: Close Proximity Geometry Reconstruction Using FMCW Radar Shadow Effects
 - **Authors:** Felix de Trogoff du Boisguezennec, Benjamin Ramtoula, Daniele De Martini
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable perception in adverse conditions remains challenging for autonomous systems, as cameras and LiDAR degrade in poor lighting or weather. Millimetre-wave FMCW radar is robust to such conditions, but its elevation collapse limits geometric reasoning. We observe that vehicle chassis occlude radar rays and form a distinctive geometric shadow, and its consistency can enable us to infer useful information about objects whose returns intersect this shadow. Motivated by this observation, we propose a method to recover the 3D, in-plane inclination of nearby slender vertical objects from this cue. The object inclination is retrieved without assumptions about the wider scene, but through an analytical, closed-form mapping between its radar return boundaries and the opening angle. Validation in simulation and experimentation on a Navtech CTS350-X radar shows that inclinations can be estimated under practical conditions, with segmentation of the object in the radar scan emerging as the main bottleneck. This work highlights chassis shadows as a novel geometric cue, extending the role of 2D rotating radar beyond localisation and toward 3D scene reconstruction.
### Title:
          DSP-SLAM++: A Unified Framework for Multi-Class, High-Fidelity Object SLAM in the Wild
 - **Authors:** Ahmad Kourani, Ghina Daoud, Daniel Asmar, Imad Elhajj
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing object-aware SLAM systems force a trade-off between real-time performance, multi-class support, and the generation of high-fidelity, semantically coherent object models. To address this trade-off, we present DSP-SLAM++, which extends the DSP-SLAM framework with an asynchronous mapping pipeline for real-time performance and dedicated sensor fusion adaptations for a monocular fisheye-LiDAR suite. Experiments demonstrate that our system generates fine-grained, geometrically-complete shapes for multiple object classes while eliminating severe mapping thread bottlenecks by reducing maximum object processing latency by up to 70\% compared to the state-of-the-art baseline, enabling robust, real-time performance on a challenging 25 Hz multi-class datasets. This work makes high-fidelity, multi-class object SLAM more practical for real-world applications like autonomous driving and robotic manipulation by enabling its use on platforms with common fisheye-LiDAR sensor setups. The open-source code is available at: [this http URL].
### Title:
          FAR-LIO: Enabling High-Speed Autonomy through Fast, Accurate, and Robust LiDAR-Inertial Odometry
 - **Authors:** Maximilian Leitenstern, Marcel Weinmann, Patrick Haft, Tobias Lasser, Dominik Kulmer, Markus Lienkamp
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust and accurate odometry estimation is essential in modern robotics. In environments characterized by highly dynamic motion and sensor noise, odometry estimation becomes increasingly challenging. Autonomous racing combines both factors in an unstructured setting, where minimizing odometry latency is essential for stable closed-loop control. This paper introduces FAR-LIO, a highly optimized CUDA-accelerated LiDAR-inertial odometry framework developed for Fast, Accurate, and Robust performance. Our system leverages a novel CUDA-based voxel hashmap to enable parallelized nearest-neighbor search and efficient map updates. We employ a sparsity-aware Generalized Iterative Closest Point algorithm with adaptive thresholding on top of the CUDA-based voxel hashmap with adaptive density to achieve low-latency without compromising accuracy. An Extended Kalman Filter serves as a robust backend. It utilizes an upsampling and delay compensation strategy to fuse the LiDAR odometry with high-frequency IMU data, thereby ensuring a robust and smooth odometry output. We evaluate FAR-LIO across four different sensor setups, using both public datasets and data from two autonomous racecars driving at speeds of up to 250 km/h. FAR-LIO achieves an average 6.9% reduction in the positional error and 38.4% lower runtime compared to state-of-the-art baselines on target hardware using a single parameter set. This demonstrates its computational efficiency and broad applicability. To build upon our work, our code is available open-source on this https URL.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          Gastroendoscopy View Synthesis: A New Real Dataset and Evaluation
 - **Authors:** Masaki Minai, Yusuke Monno, Masatoshi Okutomi, Sho Suzuki
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Novel view synthesis (NVS) is an active research topic in computer vision, owing to the success of neural radiance field (NeRF) and 3D Gaussian splatting (3DGS) methods. While NVS opens the door to potential applications in gastroendoscopy, such as extending the field of view of endoscopic images and enabling digital twins for 3D archiving and endoscopist manipulation training, the dataset is insufficient to evaluate NVS for gastroendoscopy. In this paper, we present the first real gastroscopy dataset for NVS, namely the GastroNVS dataset, which contains a set of gastroscopic images, camera poses, and a point cloud for real gastroendoscopy inspection. To assess the suitability of the GastroNVS dataset, we evaluate several 3DGS methods and discuss the challenges for future development. The dataset is available on request from our project page.
## Keyword: mapping
### Title:
          SurveilNav: Collaborative Object Goal Navigation with Robot and Surveillance System
 - **Authors:** Ming-Ming Yu, Qunbo Wang, Rongtao Xu, Yanghong Mei, Yirong Yang, Longteng Guo, Wenjun Wu, Jing Liu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the growing deployment of surveillance systems in factories, offices, and homes, integrating them with robots offers a promising direction for collaborative and efficient task execution. However, existing approaches largely focus on single-robot scenarios and struggle with multi-view collaboration in large-scale environments. In this paper, we present a novel indoor collaborative object navigation dataset built on Habitat-Sim, featuring 206 cameras across 74 floors. The dataset enables systematic evaluation of an agent's ability to exploit multi-view surveillance information. To address the limitations of single-robot perception, we propose SurveilNav, a collaborative navigation framework that integrates active camera scheduling, joint 2D/3D mapping, VLM-based value estimation, and collaborative target verification. By synergizing the robot's dynamic local perception with the static global view of surveillance, this architecture effectively overcomes both the limited perception range of single agents and the inherent blind spots of fixed cameras, resolving inefficient exploration. Experimental results on the HM3D dataset demonstrate that SurveilNav substantially outperforms existing methods, achieving state-of-the-art performance in both exploration efficiency and navigation success rate. Moreover, the system shows strong potential for applications in large-scale search, home environments, and rescue missions.
### Title:
          fARfetch: Enabling Collocated AR-HRC in Large Visually Diverse Environments with VLM-Driven AR Content Adaptation
 - **Authors:** Christian Fronk, Hanting Ye, David Hunt, Miroslav Pajic, Maria Gorlatova
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Augmented Reality (AR) can improve collocated human-robot collaboration by making robot state and intent visible and enabling intuitive control, yet large, visually diverse environments like the outdoors challenge both interaction and content legibility, especially at long distances and beyond visual line of sight. We present fARfetch, an AR-HRC system that integrates (i) shared semantic environment mapping across an AR headset and robot that visualizes detected landmarks in AR to support landmark-grounded go-to commands, (ii) a context-aware world-in-miniature representation of the shared environment for fine-grained path authoring, and (iii) vision-language-model driven AR view management that jointly adapts virtual content color, size, and orientation to maintain legibility in large visually diverse environments. We implement fARfetch with a Meta Quest 3 headset and Unitree Go2 quadruped robot, and conduct a within-subjects user study (N=13) on a real-world large-scale (30.5m) outdoor inspection task. fARfetch yielded significantly faster completion times than a non-AR baseline (66%) and significantly lower workload in mental demand (-43%), temporal demand (-34%), and frustration (-66%). A custom legibility survey indicated fARfetch effectively maintained virtual content legibility in the large outdoor environment.
### Title:
          Reflective VLA: In-Context Action Consequences Make VLAs Generalize
 - **Authors:** Qing Lian, Kent Yu, Lei Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Most vision-language-action (VLA) models are reactive: they predict the next action from the current instruction and observation, implicitly assuming that the current observation fully specifies the action-relevant state. In embodied control, however, embodiment-specific factors such as camera-to-robot geometry, robot calibration, or systematic actuation bias are often hard to identify from a single observation. As a result, reactive policies cannot reliably disambiguate these factors in general, overfitting to training environments and generalizing poorly at deployment. We propose Reflective VLA, which conditions each decision on a context of observation-action-consequence triplets. Each triplet records not only what the robot observed and executed, but also how the scene changed afterward, exposing the deployment-specific mapping from actions to observed effects. Architecturally, Reflective VLA routes all observation modalities through the VLM under shared attention, so the action expert reasons directly over past triplets and the current observation. A block-causal mask enables parallel multi-frame training without leakage and supports KV-cached real-time inference. On standard LIBERO and SimplerEnv-Bridge, Reflective VLA preserves strong in-distribution performance. Under distribution shift on LIBERO-Plus and the harder LIBERO-Plus-Hard, it improves average success rate by 5.4 and 4.2 percentage points over a matched reactive baseline. Ablations with a matched history-only baseline further show that action consequences -- rather than additional context length alone -- are the key to cross-environment generalization. Project page: this https URL
### Title:
          Communicability-Inspired Positional Encoding (CIPE)
 - **Authors:** Yipeng Zhang, Zhongtian Sun, Pietro Liò, Kelin Xia
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Positional encodings (PEs) are essential for Transformers. Yet designing effective PEs for non-Euclidean graphs remains challenging. Such encodings should ideally induce an Attention-Compatible Geometry for self-attention: not merely describing graph structure, but defining a geometry whose inner products reflect meaningful structural relatedness. To realize this geometry, we propose Communicability-Inspired Positional Encoding (CIPE), built from communicability, a measure between pairs of nodes that aggregates contributions from paths of all lengths. By construction, CIPE inner products recover communicability, converting global multi-path connectivity into an attention-ready similarity geometry. For practical Transformer training, we introduce dimensionality alignment, mapping graph-size-dependent CIPE representations to prescribed dimensions while faithfully preserving the induced geometry. Empirically, CIPE improves structure-agnostic Transformers by 35.5% on average across seven benchmarks, outperforming representative PEs; it also consistently improves structure-biased graph Transformers, where competing PEs often yield only marginal benefits. These results position CIPE as a principled framework for attention-compatible graph positional encodings.
### Title:
          SafeGen: LLM-Driven Assertion Generation and Fault Criticality Evaluation for Functional Safety
 - **Authors:** Xuanyi Tan, Arjun Chaudhuri, Rubin Parekhji, Krishnendu Chakrabarty
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With advances in autonomous driving and electric vehicle technologies, functional safety has become a critical requirement in automotive chip design. Traditional simulation-based fault analysis is often overly conservative at the module level and fails to accurately reflect fault criticality. This paper presents SafeGen, an LLM-driven, formal-verification-assisted framework for functional-safety-oriented fault criticality assessment. SafeGen leverages large language models (LLMs) and a document-level Hyper Knowledge Graph (HyperKG) that incorporates Failure Modes, Effects, and Diagnostic Analysis (FMEDA) guidelines to extract verifiable specifications from design and safety documents and evaluate their relevance to overall system safety. The HyperKG is further enriched with register-transfer-level (RTL) information to guide the generation of Functional Safety Assertions (FSAs) that are both semantically grounded and design-aware. Each assertion is linked to its corresponding specification, enabling traceable reasoning throughout the assessment process. A gate-to-RTL fault-mapping mechanism supporting both stuck-at and bridging faults, combined with formal property verification (FPV), enables semantic-level fault criticality grading based on specification-linked assertion violations. A digital-physical co-simulation platform for a field-oriented control (FOC) system is developed to validate SafeGen. Experimental results demonstrate that SafeGen generates higher-quality assertions than existing LLM-based assertion generation frameworks while providing greater semantic interpretability in fault criticality assessment compared with traditional simulation-based approaches.
### Title:
          Hypergraph Normal World Models for Logical Visual Anomaly Detection
 - **Authors:** Weizhi Nie, Zibo Xu, Weijie Wang, Yuting Su
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual anomaly detection is often deployed with only normal training images. Most one-class detectors map test patches or features to a normal reference distribution. This works well for local structural defects. Logical anomalies are different. Each visible part may look normal, while the whole image violates a normal count, co-occurrence, or spatial relation. This paper studies whether a model can learn such a category-specific normal world from nominal images alone. We propose the Hypergraph Normal World Model, a normal-only detector that distills frozen DINOv2 patch tokens into patch, relation, and hypergraph statistics. It builds spatial hyperedges over token groups. It then scores each test image with an information quotient that separates local, relational, hyperedge, and hyperedge-relation evidence. On the available MVTec LOCO breakfast-box validation data, the full hypergraph model improves logical anomaly AUROC from 0.8434 for DINOv2 patch-kNN to 0.9279. It also improves over the non-hypergraph variant, from 0.9013 to 0.9279. Few-shot experiments show that the model remains effective with very limited normal images. We also test whether the score reflects normal-world knowledge rather than a shallow mapping. t-SNE separates logical anomalies in the learned energy space. Relation counterfactuals increase the information quotient by 83.13 on average. Random hypergraphs reduce logical AUROC, and hyperedge attribution is much larger on logical anomalies. Qualitative examples show that high scores are driven by relation-bearing terms. These results suggest that logical visual anomaly detection should model normal relations, not only normal local patches.
### Title:
          C2RM-Seg: Causal Counterfactual Reasoning with Structural-Semantic Priors for Weakly Supervised Histopathological Tissue Segmentation
 - **Authors:** Hualong Zhang, Siyang Feng, Zihan Huan, Yi Qian, Zhenbing Liu, Rushi Lan, Xipeng Pan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Histopathological tissue segmentation is essential for computer-aided diagnosis, yet weakly supervised methods often suffer from noisy pseudo-labels generated by Class Activation Mapping (CAM). Existing CAM approaches tend to focus on staining-driven appearance cues rather than true causal tissue morphology, resulting in spurious localization and poor structural consistency. To address this issue, we propose C$^2$RM-Seg, a two-stage framework that integrates causal pseudo-label refinement with structure-aware semantic enhancement. For classification, we introduce a Causal Counterfactual Reasoning Module (C$^2$RM) that decomposes features into latent factors and performs counterfactual intervention via a learned causal structure matrix, suppressing confounding context and producing morphology-aligned CAMs. For segmentation, we design a Dual-Path Structural-Semantic Architecture that combines fine-grained structural features from ResNeSt with global semantic priors from a frozen DINOV3 foundation model. A cross-path gating mechanism adaptively regulates semantic injection using local structural cues to preserve boundary fidelity. To further mitigate residual pseudo-label noise, we propose an Uncertainty-Gated Margin (UGM) loss, which dynamically balances margin enforcement and confidence learning based on prediction uncertainty. Extensive experiments on two public histopathological tissue datasets show that C$^2$RM-Seg achieves state-of-the-art performance.
### Title:
          IntentTester: Intent-Driven Multi-agent Framework for Cross-Library Test Migration
 - **Authors:** Yi Gao, Ziyuan Zhang, Xing Hu, Xiaohu Yang, Xin Xia
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unit tests capture both functional checks and domain-specific knowledge, but this knowledge remains locked within individual projects and is rarely reused across libraries with overlapping functionality. Existing migration techniques based on structural code mappings (e.g., API signatures) often break down under divergent designs or cross-language settings, resulting in non-executable migrated tests. In this paper, we present IntentTester, a multi-agent framework for intent-driven test reuse. Instead of translating raw code, IntentTester abstracts tests into a language-agnostic Test Description Language (TDL), aligns them with semantically related entities and dependencies in a repository graph, and synthesizes executable tests through LLM-guided reasoning and iterative validation. This design enables cross-library and cross-language migration without manual intervention, producing migrated tests that existing structure-mapping approaches cannot achieve. We evaluate IntentTester on nine open-source projects across three domains (JSON, HTML, and Time) and two languages (Java and Python). IntentTester generates 2,776 syntactically correct tests with 85\% correctness; in comparison, the two baselines achieve 51\% and 43\%. Among them, 2,410 tests executed successfully, yielding a 74\% effectiveness rate. Beyond higher success rates, IntentTester also surfaced previously unknown defects including stack overflows, null dereferences, and parsing inconsistencies, several of which have been acknowledged or patched by maintainers. Our results show that intent-driven migration shifts the focus from code mappings to semantic alignment, allowing practical cross-library and cross-language test reuse while improving test quality and exposing implementation flaws.
### Title:
          Operator Learning on the Data-Driven Multiscale Space for Nonlinear Flow in Random Heterogeneous Porous Media
 - **Authors:** Maria Vasilyeva, Raphael Pangilinan
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present an operator learning framework based on a coarse data-driven multiscale space for nonlinear flow in random heterogeneous porous media. The multiscale space is constructed from local representative fine-scale solution snapshots, yielding an accurate low-dimensional representation of the solution manifold. This multiscale basis serves as the trunk of a neural operator, while a branch network predicts the corresponding reduced coefficients from the input permeability field. Unlike Galerkin projection methods, the neural operator learns a global nonlinear mapping from permeability fields to solution coefficients, providing greater flexibility, improved accuracy, and eliminating the need for online nonlinear coarse-grid solves and coefficient evaluations. Numerical results show that the proposed approach achieves good accuracy and substantially lower computational cost than projection-based methods for nonlinear flow in high-contrast heterogeneous media.
### Title:
          Beyond a Shadow of a Doubt: Close Proximity Geometry Reconstruction Using FMCW Radar Shadow Effects
 - **Authors:** Felix de Trogoff du Boisguezennec, Benjamin Ramtoula, Daniele De Martini
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable perception in adverse conditions remains challenging for autonomous systems, as cameras and LiDAR degrade in poor lighting or weather. Millimetre-wave FMCW radar is robust to such conditions, but its elevation collapse limits geometric reasoning. We observe that vehicle chassis occlude radar rays and form a distinctive geometric shadow, and its consistency can enable us to infer useful information about objects whose returns intersect this shadow. Motivated by this observation, we propose a method to recover the 3D, in-plane inclination of nearby slender vertical objects from this cue. The object inclination is retrieved without assumptions about the wider scene, but through an analytical, closed-form mapping between its radar return boundaries and the opening angle. Validation in simulation and experimentation on a Navtech CTS350-X radar shows that inclinations can be estimated under practical conditions, with segmentation of the object in the radar scan emerging as the main bottleneck. This work highlights chassis shadows as a novel geometric cue, extending the role of 2D rotating radar beyond localisation and toward 3D scene reconstruction.
### Title:
          The Dependency Black Hole
 - **Authors:** Ehsan Zabardast, Bhuwan Paudel, Javier Gonzalez-Huerta
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Microservice architectures promise independent evolution through loose coupling, yet large systems often exhibit strong dependency concentration around a small set of services. In an exploratory industrial case study of a product composed of 267 microservices, we triangulated multiple dependency signals -- compile-time, run-time, and task dependencies -- and iteratively validated our interpretations with practitioners. We observed a recurring macro-structure in the dependency network that resembles a black hole: a dense core of dependency magnets, a transitional region of services increasingly entangled with the core, and an outer region of lightly connected services. Based on these observations, we propose the dependency black hole theory, mapping the network to the black hole anatomy of a singularity, an event horizon, and an accretion disk, and formulating three hypotheses about how dependency concentration emerges and evolves at scale. The theory provides an explanatory lens for reasoning about dependency growth, identifying services at risk of becoming dependency magnets, and motivating governance interventions. We outline practical implications and directions for longitudinal and multi-case validation.
### Title:
          DSP-SLAM++: A Unified Framework for Multi-Class, High-Fidelity Object SLAM in the Wild
 - **Authors:** Ahmad Kourani, Ghina Daoud, Daniel Asmar, Imad Elhajj
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing object-aware SLAM systems force a trade-off between real-time performance, multi-class support, and the generation of high-fidelity, semantically coherent object models. To address this trade-off, we present DSP-SLAM++, which extends the DSP-SLAM framework with an asynchronous mapping pipeline for real-time performance and dedicated sensor fusion adaptations for a monocular fisheye-LiDAR suite. Experiments demonstrate that our system generates fine-grained, geometrically-complete shapes for multiple object classes while eliminating severe mapping thread bottlenecks by reducing maximum object processing latency by up to 70\% compared to the state-of-the-art baseline, enabling robust, real-time performance on a challenging 25 Hz multi-class datasets. This work makes high-fidelity, multi-class object SLAM more practical for real-world applications like autonomous driving and robotic manipulation by enabling its use on platforms with common fisheye-LiDAR sensor setups. The open-source code is available at: [this http URL].
### Title:
          RoboAtlas: Contextual Active SLAM
 - **Authors:** Alexander Schperberg, Shivam K. Panda, Abraham P. Vinod, M. K. Jawed, Stefano Di Cairano
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present RoboAtlas, a contextual Active SLAM framework that adaptively balances geometric exploration and semantic reasoning using a scalable 3D semantic mapping system, OpenRoboVox. RoboAtlas integrates frontier exploration, global semantic-map reasoning, and egocentric VLM-based reasoning through a contextual multi-armed bandit that transitions from exploration to semantically guided navigation as scene understanding improves. We evaluate the system in simulation and on a Unitree Go2 robot in large-scale real-world environments exceeding 1800 m2 with approx. 30k mapped semantic instances, achieving a 100% task success rate. On the GOAT-Bench "Val Unseen" benchmark, RoboAtlas achieves state-of-the-art performance with highest reported success rate (SR) of 90.6%, using GPT-4o, improving over the strongest prior baseline by 17.8 percentage points in SR. Using the much smaller Qwen2.5-VL-7B model, it still achieves 88.8% SR, outperforming all baselines using GPT-4o in SR, and revealing the importance of the information gained by our semantic mapping framework over simply replacing the underlying foundation model. The results demonstrate that grounding foundation models with large-scale 3D semantic maps enables robust and efficient contextual Active SLAM.
## Keyword: localization
### Title:
          Toward Low-Latency Vision-Language Models with Doubly-Correct Predictions in Egocentric Visual Understanding
 - **Authors:** Qitong Wang, Fan Du, Pranav Maneriker, Jihui Jin, Christopher Rasmussen
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid rise of Vision-Language Models (VLMs) in egocentric visual understanding has made low-latency inference in human-robot collaborative (HRC) tasks increasingly critical. Weight pruning techniques developed for VLMs to shrink model size and computation can be readily applied to satisfy the efficiency demands of on-board processing and real-time interactive robotics. Moreover, safe human-robot interaction demands pruning strategies that preserve doubly-correct predictions; outputs must be both accurate and evidentially grounded to mitigate risks and ensure user trust. In this paper, we present a new study of VLM pruning through the lens of doubly-correct prediction. Our experiments surprisingly show that existing pruning methods often preserve the right evidence localization but undermine correct prediction. To address this, we propose a rationale-informed pruning strategy that better aligns evidence with decisions. Benchmark results on egocentric video datasets demonstrate that our method not only achieves the highest prediction accuracy but also outperforms existing approaches in attaining doubly-correct predictions. We aim to stimulate research on efficient and reliable VLMs, ensuring accuracy-driven advances align with the transparency, auditability, and safety required for responsible human-robot interaction and embodied intelligence.
### Title:
          OrthoTrack: Continuous 6-DoF UAV Trajectory Estimation Anchored in Public Orthophotos
 - **Authors:** Oussema Dhaouadi, Zuria Bauer, Johannes Michael Meier, Olaf Wysocki, Marc Pollefeys, Daniel Cremers
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Continuous 6-DoF pose estimation is essential for autonomous UAV operations. Yet, existing visual odometry and SLAM methods accumulate drift and yield only relative, up-to-scale trajectories. Single-frame geo-localization, in turn, discards temporal continuity and remains too slow for real-time use. We present OrthoTrack, a training-free system that estimates continuous 6-DoF UAV trajectories using only publicly available orthophotos and surface models as a map prior. OrthoTrack matches keyframes against the orthophoto and lifts correspondences to metric 3D via the surface model. It then propagates these map-anchored correspondences to intermediate frames with optical flow, producing absolute, metrically scaled poses at every frame without GPS or post-hoc alignment. We also introduce the MovingDrone Dataset, a large-scale benchmark pairing photorealistic UAV sequences with dense 6-DoF ground truth and co-registered multi-modal geodata including multi-temporal orthophotos. On MovingDrone and real-world benchmarks, OrthoTrack runs in real time on a single GPU. It outperforms all baselines by a large margin, even those receiving oracle scale and alignment. By relying on publicly available geodata, OrthoTrack enables deployment to new regions without site-specific adaptation.
### Title:
          An Integrated Hardware-Software Design for Low-Data Spatial Defect Detection in Robotic Visual Inspection with Hybrid Optoelectronic Neural Networks
 - **Authors:** Chaoqing Tang, Jiaxuan Li, Huanze Zhuang, Guiyun Tian, Chao Wang, Yihao Ouyang, Wenzhong Liu
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 To address data overload and inefficient shape-level annotation in robotic visual inspection, this paper proposes a hardware-software integrated optoelectronic architecture. A non-imaging, low-data paradigm is established to minimize annotation dependency. First, a sensor-in-the-loop strategy reconfigures a Digital Micromirror Device (DMD) as a physical optical convolutional layer, enabling photonic-domain feature extraction that unifies sensing hardware and processing software. To suppress data volume at the source, a block-based compressed sensing strategy encodes spatial information into low-dimensional temporal signals, drastically reducing redundancy. Subsequently, to bypass laborious manual defect shape annotation, natural language descriptions guide the network to align with highly generalizable features from Contrastive Language-Image Pre-training (CLIP), steering the attention maps of the optoelectronic neural network toward defect shapes. Furthermore, a Localization Accuracy for Attention (LAA) metric is proposed to quantify shape-level defect localization performance. Experiments on transparent material defect detection validate the system's effectiveness. Parametric analysis reveals how measurement matrices, compression ratios, and block sizes affect accuracy. Results show that, compared to traditional imaging, the proposed architecture maintains equivalent accuracy while reducing data volume by 90% for Vision Transformers and computational workload by 60% for Convolutional Neural Networks. This low-data paradigm offers an efficient solution for industrial automation scenarios involving massive data streams, high acquisition costs, or constrained edge resources.
### Title:
          TopoCast: A Topological Fidelity Framework for Evaluating Transformer-Based Time Series Forecasting
 - **Authors:** Sandeepa Weerasekara, Sandareka Wickramanayake
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning-based models have achieved state-of-the-art performance in Time Series Forecasting (TSF), yet their evaluation remains dominated by pointwise error metrics such as Mean Squared Error (MSE), which quantify numerical accuracy but overlook structural properties of the forecast signal, including recurrent dynamics, oscillatory behavior, and phase alignment. As a result, forecasts exhibiting over-smoothing, phase shifts, or frequency distortions may achieve favorable error scores despite substantial structural degradation. To address this limitation, we propose TopoCast, a topology-driven framework for evaluating structural fidelity in TSF. TopoCast reconstructs phase-space representations of forecast and ground-truth sequences using Takens delay embedding and applies persistent homology to characterize their intrinsic dynamics. We derive four complementary topological fidelity measures from persistence diagrams and aggregate them into a Topological Fidelity Score (TFS). We further introduce dominant cycle overlap, a novel metric that maps persistent topological features to the temporal domain to assess whether dominant oscillatory patterns occur at the correct time points. Combined with TFS, this yields the Localized Topological Fidelity Score (LTFS), a phase-aware measure that captures temporal localization errors invisible to existing evaluation metrics. Experiments on five Transformer architectures across three real-world benchmark datasets demonstrate that models with similar forecasting errors can exhibit markedly different structural fidelity profiles, revealing failure modes overlooked by conventional evaluation and highlighting the value of topology-aware forecast assessment.
### Title:
          HG-Bench: A Benchmark for Multi-Page Handwritten Answer-Region Grounding in Automated Homework Assessment
 - **Authors:** Chuangxin Zhao, Boyan Shi, Yanling Wang, Yijian LU, Canran Xiao, Jiali Chen, Jun Xia, Yan Wang, Ji Qi, Juanzi Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated homework assessment depends not only on recognizing student answers, but also on accurately locating where each answer and each intermediate reasoning step appears in noisy, multi-page handwritten work. This paper addresses the missing evaluation setting of page-aware, two-level answer-region grounding: given a sequence of homework page images, a model must localize complete answer regions and their ordered step-level subregions. We introduce HG-Bench, a benchmark of 500 human-annotated K-12 homework samples curated from a 1,489,278-image source pool, with question-level and step-level boxes linked by a hierarchical containment constraint. HG-Bench is paired with a page-aware evaluation protocol that separately measures complete-answer localization (FA) and step-level decomposition (FSm), revealing whether models truly ground the spatial structure of student reasoning rather than merely parse visible text. Across frontier closed-source APIs and competitive open-weight VLMs, no zero-shot system exceeds 55.22% on FA or 48.22% on FSm, while a GLM-4.6V 9B reference model fine-tuned on ~10k in-domain examples reaches 74.97/72.26. These results identify step-level handwritten grounding as a concrete capability gap and provide a reproducible benchmark, evaluation protocol, and trained reference point for future work on automated homework assessment.
### Title:
          C2RM-Seg: Causal Counterfactual Reasoning with Structural-Semantic Priors for Weakly Supervised Histopathological Tissue Segmentation
 - **Authors:** Hualong Zhang, Siyang Feng, Zihan Huan, Yi Qian, Zhenbing Liu, Rushi Lan, Xipeng Pan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Histopathological tissue segmentation is essential for computer-aided diagnosis, yet weakly supervised methods often suffer from noisy pseudo-labels generated by Class Activation Mapping (CAM). Existing CAM approaches tend to focus on staining-driven appearance cues rather than true causal tissue morphology, resulting in spurious localization and poor structural consistency. To address this issue, we propose C$^2$RM-Seg, a two-stage framework that integrates causal pseudo-label refinement with structure-aware semantic enhancement. For classification, we introduce a Causal Counterfactual Reasoning Module (C$^2$RM) that decomposes features into latent factors and performs counterfactual intervention via a learned causal structure matrix, suppressing confounding context and producing morphology-aligned CAMs. For segmentation, we design a Dual-Path Structural-Semantic Architecture that combines fine-grained structural features from ResNeSt with global semantic priors from a frozen DINOV3 foundation model. A cross-path gating mechanism adaptively regulates semantic injection using local structural cues to preserve boundary fidelity. To further mitigate residual pseudo-label noise, we propose an Uncertainty-Gated Margin (UGM) loss, which dynamically balances margin enforcement and confidence learning based on prediction uncertainty. Extensive experiments on two public histopathological tissue datasets show that C$^2$RM-Seg achieves state-of-the-art performance.
### Title:
          ShutterMuse: Capture-Time Photography Guidance with MLLMs
 - **Authors:** Jiayu Li, Yixiao Fang, Tianyu Hu, Wei Cheng, Ping Huang, Zheheng Fan, Gang Yu, Xingjun Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-world photography requires capture-time guidance for both camera framing and subject pose. Yet existing aesthetic cropping benchmarks mainly evaluate post-hoc crop prediction and overlook subject-side recommendations, leaving the capture-time guidance capabilities of multimodal large language models (MLLMs) underexplored. To address this gap, we introduce CaptureGuide-Bench, a benchmark with two complementary tasks: photographer-side composition decision and refinement, and subject-side scene-conditioned pose recommendation. Our evaluation reveals limitations: general-purpose MLLMs can make composition decisions but lack precise refinement localization, while specialized aesthetic cropping models localize crops effectively but are limited to refinement; neither provides actionable pose guidance. To support model development, we further construct CaptureGuide-Dataset, comprising 130K samples with textual rationales and structured visual annotations, and develop ShutterMuse, a unified MLLM trained with supervised and reinforcement fine-tuning. Experiments on CaptureGuide-Bench show that ShutterMuse achieves the best overall photographer-side performance among evaluated baselines and competitive subject-side pose recommendation with substantially lower inference cost, demonstrating the potential of MLLMs as interactive assistants for photography during image capture.
### Title:
          MIL-LC: A Robust Magnetometer-Inertial-LiDAR Fusion Multimodal Localization Framework
 - **Authors:** Qiyang Lyu, Zhenyu Wu, Wei Wang, Hongming Shen, Danwei Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Localization in challenging environments, such as GNSS-denied, geometrically repetitive, or textureless scenes commonly found in offices, hotels, and underground parking facilities, remains an open problem for reliable autonomous mobile robot (AMR) deployment. Single-modality localization methods are inherently limited by the constraints of individual sensors. Although multimodal fusion frameworks have shown improved robustness, most existing approaches still rely heavily on geometric or texture features, or on infrastructure-based beacons, which increase installation and maintenance costs while reducing deployment flexibility. Recently, ambient magnetic field (AMF)-based localization has attracted growing attention because it does not depend on geometric or texture features, nor does it require additional infrastructure, making it a promising complementary modality for AMR localization. However, existing studies have only explored such fusion in pedestrian scenarios using smartphone-mounted sensor suites, and practical solutions for AMR systems remain largely unexplored. To address this gap, this article proposes a magnetometer-inertial-LiDAR fused multimodal localization framework with a custom-designed sensor suite, termed MIL-LC, which provides reliable localization even when LiDAR suffers from geometric degeneration or when the magnetic map changes during long-term deployment. Extensive experiments in both simulation and real-world environments demonstrate that the proposed MIL-LC framework achieves robust and accurate localization performance.
### Title:
          Enhancing Brain MRI Anomaly Detection and Reasoning with ROI Rethink and Synthetic Data
 - **Authors:** Shangkun Li, Jie Xu, Yi Guo, Zeju Li, Yuanyuan Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Medical vision-language models typically generate diagnoses through single-pass inference without indicating which image regions support their conclusions. This lack of spatial grounding limits clinical utility: outputs cannot be audited, and models may hallucinate findings on normal scans. We present BrReMark (Brain Rethink via ROI Marking), a framework that introduces explicit region marking into brain MRI diagnosis. The model first generates hypotheses about potential abnormalities and grounds them through explicit bounding box marking, then verifies conclusions by re-examining the marked evidence. Training combines supervised fine-tuning on structured reasoning trajectories with reinforcement learning using a composite reward over localization accuracy and diagnostic reasoning. Furthermore, we integrate a domain randomization-based pathology synthesis augmentation strategy to improve the model's generalizability to out-of-distribution (OOD) data. On internal benchmark, BrReMark improves mAP50 from 0.74% to 37.54% compared to the base model, while achieving 21.57% Clinical F1 and 45.26% diagnostic accuracy. On NOVA OOD benchmark, it also achieves competitive overall performance with a 45.7% reduction in false positives compared to the state-of-the-art, indicating reduced hallucination on rare pathologies. These findings suggest that explicit hypothesis-verification grounding is a practical path toward trustworthy open-ended brain MRI diagnosis across both in-distribution and OOD settings.
### Title:
          TryOnCrafter: Unleashing Camera Trajectories for Realistic Video Virtual Try-on via a Renderable 4D Try-on Proxy
 - **Authors:** Hao Sun, Hao Yan, Mengting Chen, Quanjian Song, Yu Li, Juan Cao, Jinsong Lan, Xiaoyong Zhu, Bo Zheng, Sheng Tang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Video Virtual Try-on (VVT) has achieved remarkable progress in synthesizing realistic garment overlays on dynamic subjects, existing paradigms remains fundamentally constrained by a passive dependency on source camera trajectories, failing to accommodate the requisite interactive freedom for omnidirectional viewpoint exploration. To address this limitation, we define a pioneering research frontier: Camera-controllable Video Virtual Try-on (CaM-VVT). Unlike conventional VVT, CaM-VVT not only necessitates viewpoint-agnostic texture hallucination but also strict structural synchronization between non-rigid human dynamics and background contexts under arbitrary, unconstrained camera movements. To tackle these challenges, we present TryOnCrafter, the first unified DiT-based framework specifically architected for the CaM-VVT task. Departing from implicit pixel-space manipulation, we introduce a Renderable 4D Try-on Proxy that explicitly decouples the human subject from the environment. This is achieved by distilling high-fidelity 2D try-on priors into a clothed 3DGS-based avatar, which is subsequently animated via SMPL-X sequences and metric-aligned into a reconstructed background point cloud. This proxy establishes a robust structural foundation with superior texture density and motion integrity. Our Proxy-Anchored Video DiT leverages this robust structural foundation as a primary geometric anchor, ensuring that the synthesized photorealistic videos are strictly constrained by prescribed trajectories and physically plausible deformations. Benefiting from the inherent editability of the 4D proxy, TryOnCrafter facilitates diverse downstream applications, including human relocalization, ``bullet time'' effects, and $360$-degree orbital viewing.
## Keyword: transformer
### Title:
          Dense Supervision Is Not Enough: The Readout Blind Spot in Looped Language Models
 - **Authors:** Rituraj Sharma, Tu Vu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Looped language models turn hidden states into runtime state: each state is decoded for prediction and fed back into future computation. This creates a basic supervision question: which state variables does cross-entropy actually control? We show that dense per-loop cross-entropy controls the variables exposed by the readout, not every variable active in the recurrent transition. Hidden-state scale gives a concrete failure mode. Scale-invariant readouts such as RMSNorm and LayerNorm hide radial scale from the immediate cross-entropy loss, while pre-norm residual recurrence continues to carry and update that same scale. Thus per-loop loss can make early exits usable without controlling recurrent scale. In 44M and 129M looped transformers without inter-loop normalization, per-loop cross-entropy through RMSNorm readouts still drives final hidden-state norms into the thousands or tens of thousands. Scale-visible readouts and explicit norm penalties keep norms in the tens, and scale-removing recurrence is the complementary architectural fix. The resulting design rule is simple: dense supervision trains exits; recurrent scale control requires either making scale visible to a loss or removing it from the loop. Consistent with this rule, scale-controlled variants achieve lower perplexity at matched inference-depth operating points in our variable-depth benchmarks.
### Title:
          The Hitchhiker's Guide to Agentic AI: From Foundations to Systems
 - **Authors:** Haggai Roitman
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Information Retrieval (cs.IR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Hitchhiker's Guide to Agentic AI is a comprehensive practitioner's reference for building autonomous AI systems. The book covers the full stack from first principles to production deployment, organized around a central thesis: building great agentic systems requires understanding every layer of the pipeline, not just one. The book opens with the LLM substrate -- transformer architecture, GPU systems, training and fine-tuning (SFT,LoRA, MoE), model compression, and inference optimization -- treated as essential foundations rather than the primary focus. It then develops the alignment and reasoning layer: reinforcement learning from human feedback (RLHF), PPO, DPO and its variants, GRPO, reward modeling, and RL for large reasoning models including chain-of-thought and test-time scaling. The second half is devoted to agentic AI proper. Topics include agentic training and trajectory-based RL, retrieval-augmented generation (RAG and Agentic RAG), memory systems (in-context, external, episodic, and semantic), agent harness design and context management, and a taxonomy of agent design patterns. Inter-agent coordination is covered in depth: the Model Context Protocol (MCP), agent skills and tool use, the Agent-to-Agent (A2A) communication protocol, and multi-agent architectures spanning centralized, decentralized, and hierarchical topologies. The book concludes with agent development frameworks, agentic UI design, evaluation methodology for agentic tasks, and production deployment. Each chapter pairs rigorous theoretical foundations with implementation guidance, code examples, and references to the primary literature.
### Title:
          Towards Scalable Multi-Task Reinforcement Learning with Large Decision Models
 - **Authors:** Thibaut Kulak
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent progress in large-scale sequence modeling has shown that a single model can learn useful representations across highly diverse data distributions. Inspired by these advances, we investigate whether a unified transformer policy can be trained across large collections of heterogeneous reinforcement learning environments. We introduce LDM-v0, a Large Decision Model trained offline on trajectories collected from thousands of environments spanning multiple domains and modalities. LDM-v0 is a multi-task, multi-modal transformer policy conditioned on histories of observations, actions, rewards, and termination signals, and trained through supervised next-action prediction over offline trajectories. We describe the environment infrastructure, automated data generation pipeline, model architecture, and training methodology used to build LDM-v0, and evaluate its performance across diverse environments. We show that a single pretrained model matches the performance of independently trained task-specific reference policies on approximately 1,000 environments including robotics, autonomous driving, inventory management, cybersecurity, trading, and video games. These results demonstrate the feasibility of large-scale offline pretraining across heterogeneous reinforcement learning environments using a single transformer policy.
### Title:
          Project Auto-World: Towards Automated Benchmarking of Neural Relational Reasoners
 - **Authors:** Anirban Das, Joanne Boisson, Irtaza Khalid, Sumita Garai, Steven Schockaert
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reasoning about relational structures remains a significant challenge for neural models, particularly when they must systematically apply learned knowledge to problem instances that are harder than those seen in training. Progress is hampered by the difficulty of evaluating such generalization, since a priori, it is rarely clear what makes an instance hard. We study how this issue can be addressed by using large language models (LLMs) to automate benchmark generation, learning to produce increasingly challenging instances in an end-to-end manner. Concretely, given a world parametrized by Datalog rules, and an Edge Transformer as the reasoning evaluator, we use LLM-driven evolutionary search (based on FunSearch) and autonomous agentic search to discover sampling functions that yield hard problem instances. We also show that the Edge Transformer can be improved using this data such that it generalizes well to further data perturbations. Finally, we show that the same machinery can be applied to novel worlds proposed by LLMs, opening the door to autonomous research on neural relational reasoning.
### Title:
          Frequency Domain Reservoir Computing
 - **Authors:** Klaus Schertler, Xiomara Runge, Andrea Ceni, David Kappel, Claudio Gallicchio
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While the quadratic sequence-length bottleneck of transformers has fueled a resurgence in recurrent models, effectively capturing complex dynamics requires architectures that balance efficient training with highly expressive latent states. Echo State Networks (ESNs) offer a compelling approach by utilizing fixed recurrent weights to circumvent backpropagation through time, enabling a closed-form training solution. However, achieving the expressivity needed for complex tasks demands large reservoirs, exposing an $\mathcal{O}(N^2)$ state-update bottleneck that prevents ESNs from matching the scale of contemporary recurrent models. To address this limitation, we introduce Frequency Domain Reservoir Computing (FRESCO), an ESN architecture operating entirely in the frequency domain while avoiding domain-shift overheads to achieve $\mathcal{O}(N)$ complexity for dense, non-linear recurrent updates. By employing a novel dimensional zero-padding input embedding, a packed \FDh readout, and a natively applied frequency-domain non-linearity, FRESCO drastically reduces computational costs and energy consumption of training and inference. Furthermore, FRESCO matches the state-of-the-art predictive performance on memory benchmarks, sequential classification, and multivariate long-horizon forecasting, offering a scalable path forward for dense recurrent architectures.
### Title:
          Retrieval-Augmented Personalization with Foundation Models for Wearable Stress Detection
 - **Authors:** Louis Simon, Mohamed Chetouani
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Personalization in wearable-based stress detection remains challenging due to substantial inter-individual variability in physiological and behavioral responses. While traditional approaches rely on user-specific fine-tuning or costly self-supervised pre-training on large datasets, we propose a lightweight alternative based on retrieval-augmented personalization. Our method leverages frozen, out-of-domain foundation models to retrieve similar patterns from a target user's history and encode them into a compact personalized embedding that modulates representations extracted by a lightweight transformer network. We evaluate our approach on the WESAD stress detection dataset with N=15 users, comprising wrist-worn physiological (EDA, BVP, temperature) and activity (accelerometer) signals, and report gains of +3.92\% in accuracy and +4.76\% in macro F1-score over a non-personalized transformer baseline, approaching supervised fine-tuning performance without requiring any labeled user data. We further show that temporal retrieval, where only prior user samples are available, achieves performance close to full intra-user retrieval, demonstrating robustness to limited user history. Finally, we explore personalization in a cross-dataset retrieval setting, leveraging embeddings from the K-Emocon dataset to personalize representations for stress detection on the WESAD dataset.
### Title:
          Scalable Peptide Design via Memory-Efficient Equivariant Transformer
 - **Authors:** Rui Jiao, Xiangzhe Kong, Yinjun Jia, Yijia Zhang, Ziyi Yang, Yang Liu, Jianzhu Ma
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Target-specific peptide design requires sequence and structure co-design under full atom geometric constraints. Latent generative frameworks offer an effective route for this problem by compressing fine grained atomic structures into block level latent representations and performing conditional generation in a compact latent space. However, the scalability of such systems depends heavily on the geometric backbone used throughout their encoding, decoding, and denoising components. We introduce MEET (Memory Efficient Equivariant Transformer), an E(3) equivariant backbone for scalable atomistic peptide modeling. MEET maintains coupled invariant scalar and equivariant vector feature streams, while reformulating geometric computation around memory efficient attention. It initializes vector features through global coordinate aggregation, incorporates pairwise distances through augmented query and key dot products, and injects covalent bond information through sparse bond adaptation. Integrated into a VAE and latent diffusion pipeline for full atom peptide generation, \model{} achieves linear memory scaling with atom count and improves generation quality over existing peptide design methods. Experiments on large scale AFDB derived datasets further show that the proposed backbone supports systematic model and data scaling, leading to better binding affinity, physical validity, and sample diversity.
### Title:
          Multi-Stream Temporal Fusion for Financial Fraud Detection
 - **Authors:** Mohammadamin Dashti Moghaddam, Nick Sciarrilli
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Statistical Finance (q-fin.ST)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Financial fraud detection in digital banking requires reasoning over multiple heterogeneous event streams -- transactions, login sessions, risk signals -- that individually appear benign but collectively reveal fraudulent patterns. We propose the Multi-Stream Fraud Transformer (MSFT), a unified architecture that encodes each event stream with independent Transformer encoders and fuses their representations through configurable mechanisms. We conduct a systematic ablation study comparing five fusion strategies: concatenation, gated fusion, time-aware positional encoding, cross-stream attention, and a full combination. On a large-scale dataset (10M users, 1.5% fraud rate) with 85M parameter models, we demonstrate that (1) sequence models significantly outperform gradient-boosted trees operating on aggregated features (0.74 vs. 0.99 AUROC), (2) per-stream encoding is essential -- a single-stream Transformer baseline with matched parameter budget reaches only 0.82 AUROC, an 18-point gap that confirms the multi-stream inductive bias is necessary, (3) time-aware positional encoding achieves the highest discrimination (0.9961 AUROC), (4) gated fusion yields the best precision (0.989) suitable for production deployment, and (5) the risk event stream provides the strongest individual signal contribution. We further validate on proprietary production data from a digital banking platform, showing over 22% relative AUROC improvement over the XGBoost baseline.
### Title:
          Neural Scaling Universality: If Exponents Are Fixed, Time to Understand Coefficients
 - **Authors:** Yizhou Liu, Jeff Gore
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural scaling laws describe how pre-training loss decays as power laws with training time, model size, and compute. This position paper argues that the exponents of these power laws are fixed by generic mechanisms: a one-third time scaling due to the strong nonlinearity of Softmax, an inverse width scaling due to representational superposition, and an inverse depth scaling due to ensemble averaging of Transformer layers. These mechanisms are robust to a wide range of data structures and architectural details, placing current large language models in a universality class with fixed exponents. The coefficients, however, are expected to be sensitive to data and architecture details, and directly determine practical quantities such as the optimal model shape and the compute-optimal frontier. We therefore argue that understanding the coefficients is the key to near-term performance improvements, and that a closer examination of the current universality class may reveal pathways to better universality classes.
### Title:
          Emergent Capabilities Arise Randomly from Learning Sparse Attention Patterns
 - **Authors:** Vatsal Baherwani, Zixi Chen, Shikai Qiu, Andrew Gordon Wilson, Pavel Izmailov
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural scaling laws for transformer language models predict smooth improvements in pretraining loss with increasing parameters, but downstream capabilities such as in-context learning are known to emerge abruptly past a certain model scale. In this paper, we show that emergent capabilities arise stochastically throughout training, with larger models acquiring them earlier on average. We demonstrate that the emergence of capabilities such as pattern completion and indirect object identification corresponds to the abrupt learning of task-relevant attention patterns. To isolate this phenomenon, we train transformer models on synthetic linear map and cellular automata datasets, and we show that the difficulty of learning attention patterns depends on context length and pattern sparsity. Moreover, scaling the number of attention heads improves learning efficiency on our synthetic tasks, while increasing the head dimension yields diminishing returns past a minimum capacity. We additionally investigate architectures with alternative attention mechanisms, showing that MLP-Mixer outperforms a transformer on linear map tasks with complex attention patterns. Our findings provide a mechanistic insight into emergence, showing that downstream capabilities arise abruptly due to the intrinsic difficulty of learning sparse attention patterns in transformer models.
### Title:
          Wan-Streamer v0.1: End-to-end Real-time Interactive Foundation Models
 - **Authors:** Lianghua Huang, Zhifan Wu, Wei Wang, Yupeng Shi, Mengyang Feng, Junjie He, Chenwei Xie, Yu Liu, Jingren Zhou, Ang Wang, Bang Zhang, Baole Ai, Chen Liang, Cheng Yu, Chongyang Zhong, Jinwei Qi, Kai Zhu, Pandeng Li, Peng Zhang, Wenyuan Zhang, Xinhua Cheng, Yitong Huang, Yun Zheng, Zoubin Bi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Graphics (cs.GR); Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Wan-Streamer, a native-streaming, end-to-end interactive foundation model designed from the ground up for real-time, low-latency, full-duplex audio-visual interaction. Wan-Streamer seamlessly models language, audio, and video as both input and output within a single Transformer, where the sequence is represented as interleaved visual, audio, and text input tokens together with visual, audio, and text output tokens, coordinated by block-causal attention for incremental streaming. Unlike cascaded interactive systems that rely on separate VAD, ASR, language, TTS, audio-driven animation, or video-generation modules, Wan-Streamer does not rely on external language, speech, avatar, or video-generation modules: perception, reasoning, generation, response timing, turn management, and cross-modal synchronization are learned jointly within one unified model, reducing pipeline latency and error accumulation. To support natural audio-visual responsiveness, we redesign the entire stack around streamability, including causal encoders, causal decoders, block-causal attention, and low-latency multimodal token scheduling, enabling streaming units as short as 160 ms at 25 fps. Wan-Streamer achieves approximately 200 ms model-side response latency and approximately 550 ms total interaction latency when combined with 350 ms bidirectional network latency, supporting sub-second duplex audio-visual communication. These results position Wan-Streamer as a unified, end-to-end, multimodal interactive foundation model for low-latency streaming interaction.
### Title:
          Toward Next-Generation AI Data Centers: Power Delivery Architecture Shifts, Emerging Technologies, and Challenges
 - **Authors:** Sangwhee Lee, Rafal P. Wojda, Cheol-Hee Jo, Shuntaro Inoue, Pedro Ribeiro, Gui-Jia Su, Mostak Mohammad, Himel Barua, Nishanth Gadiyar, Praveen Kumar, Spencer Cochran, Subho Mukherjee, Whit Vinson, Vandana Rallabandi, Shajjad Chowdhury, Burak Ozpineci
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid growth of AI workloads is driving unprecedented increases in data center power demand, current transients, and thermal stress, exposing fundamental limitations in traditional 48 V rack architectures, low-voltage AC distribution, and line-frequency transformer interfaces. This paper reviews the three stages of architectural shifts required to support next-generation AI data centers and identifies three enabling technological building blocks: high-voltage conversion-ratio DC/DC converters, facility-level low-voltage DC distribution, and medium-voltage solid-state transformers. The advantages, technical challenges, and potential solutions associated with each building block are reviewed. Finally, future research directions and open challenges are discussed.
### Title:
          AeroCast: Probabilistic 3D Trajectory Prediction for Non-Cooperative Aerial Obstacles via Transformer-MDN Architecture
 - **Authors:** Syed Izzat Ullah, Jose Baca
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous aerial vehicles operating in shared airspace must predict the future positions of non-cooperative obstacles to plan evasive maneuvers before a collision becomes unavoidable. Unlike cooperative systems that share intent, non-cooperative obstacles such as birds, uncontrolled drones, or debris exhibit multi-modal motion that deterministic predictors cannot adequately represent. Existing methods either rely on recurrent encoders that propagate temporal information sequentially, limiting their ability to capture long-range kinematic precursors of maneuver initiation, or produce point forecasts that provide no distributional information to downstream planners. This paper presents AeroCast, a probabilistic trajectory prediction framework that combines a Transformer encoder with a Mixture Density Network output head to predict per-timestep Gaussian mixture distributions over future three-dimensional displacements. A translation-invariant consecutive displacement encoding and a calibration-oriented training objective address the input design and mode-degeneracy challenges specific to mixture-based aerial trajectory prediction. On a hybrid real-and-synthetic quadrotor corpus spanning nine motion categories, AeroCast reduces Average Displacement Error and Final Displacement Error by approximately 50% relative to the baselines over a five-second horizon, and achieves the lowest negative log-likelihood and Continuous Ranked Probability Score among all compared methods. Ablation analysis identifies velocity input and model capacity as the primary contributors to prediction quality, and positional encoding as essential for long-horizon trajectory coherence. AeroCast inference completes in 0.1ms per sample, compatible with real-time onboard deployment at 100Hz.
### Title:
          Memory Retrieval in Visuomotor Policies for Long-Horizon Robot Control
 - **Authors:** Rutav Shah, Yisu Li, Femi Bello, Yuke Zhu, Roberto Martín-Martín
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 General-purpose robots operating in partially observable environments, such as homes, require memory to support autonomy. They must recall diverse information from the past, such as where objects were placed, which tasks a human partner has completed, and when an appliance was turned on. Achieving this versatility requires a general memory retrieval mechanism. Transformer architectures that use attention over long contexts for memory retrieval provide a promising approach, as they learn retrieval from data rather than relying on task-specific or hand-designed rules. However, directly incorporating them into imitation learning from offline data introduces two key challenges: (1) the policy may learn spurious correlations between past information and predicted actions, and (2) errors accumulate in memory due to prediction inaccuracies and their compounding interactions with the environment, causing model drift and cascading failures. To address both challenges, we introduce HALO, a visuomotor policy with an attention-based memory retrieval mechanism for long-horizon control. First, to suppress spurious correlations, HALO distills vision-language model (VLM) priors into the policy. It generates memory-dependent question--answer pairs from demonstration trajectories and trains jointly with a video question--answering objective, steering retrieval toward task-relevant information. Second, to reduce the impact of accumulated errors in memory during closed-loop control, HALO uses sparse attention that restricts retrieval to only the most relevant parts of the history. Together, these components enable more reliable long-horizon control by guiding the policy to retrieve task-relevant information from up to eight minutes of past experience. Project website: this https URL
### Title:
          An iterative energy-based multimodal transformer for joint retrieval of wheat soil moisture, leaf area index, and plant height from Sentinel-1 and Sentinel-2 time series
 - **Authors:** Shubham Kumar Singh, Peilei Fan, Suraj A. Yadav, Rajendra Prasad, Prashant K Srivastava
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Field-scale retrieval of surface soil moisture (SM), leaf area index (LAI), and plant height (PH) is essential for precision agriculture, yet it remains an ill-posed inverse problem. Concurrent variations in soil moisture and canopy density generate substantial ambiguities in radar backscatter and spectral responses, which reduces the effectiveness of traditional feedforward regression models in heterogeneous smallholder cropping systems. This study presents the Iterative Energy-Based Transformer (iEBT) for the joint retrieval of coupled soil-canopy states from Sentinel-1 C-band SAR and Sentinel-2 multispectral time series. Instead of direct regression, iEBT embeds multi-modal predictors within a shared sequence, produces an initial state estimate, and iteratively updates the target [SM, LAI, PH] vector through normalized gradient descent to minimize a learned scalar compatibility energy function. Using 700 quality-controlled field measurements from Varanasi, India, iEBT achieved the highest learned-model performance on the random test split, with a four-seed mean R^2 of 0.854 \pm 0.012 (R_SM^2 = 0.841, R_LAI^2 = 0.905, R_PH^2 = 0.821). WCM and PROSAIL were retained as physically interpretable SAR and optical reference models for comparison. Modality ablations confirmed that Sentinel-1 drives SM retrieval, while Sentinel-2 dominates LAI, whereas PH relies on combined structural-phenological signatures. Crucially, the model's terminal energy functions as an uncalibrated post-retrieval quality diagnostic; screening the 10% highest-energy samples markedly reduced target level root-mean-square errors. While leave-one-campaign-out validation highlights persistent cross-season domain shift challenges due to localized management variations, compatibility-guided multimodal fusion offers a structured self-diagnostic path toward reliable biophysical parameter estimation
### Title:
          An Integrated Hardware-Software Design for Low-Data Spatial Defect Detection in Robotic Visual Inspection with Hybrid Optoelectronic Neural Networks
 - **Authors:** Chaoqing Tang, Jiaxuan Li, Huanze Zhuang, Guiyun Tian, Chao Wang, Yihao Ouyang, Wenzhong Liu
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 To address data overload and inefficient shape-level annotation in robotic visual inspection, this paper proposes a hardware-software integrated optoelectronic architecture. A non-imaging, low-data paradigm is established to minimize annotation dependency. First, a sensor-in-the-loop strategy reconfigures a Digital Micromirror Device (DMD) as a physical optical convolutional layer, enabling photonic-domain feature extraction that unifies sensing hardware and processing software. To suppress data volume at the source, a block-based compressed sensing strategy encodes spatial information into low-dimensional temporal signals, drastically reducing redundancy. Subsequently, to bypass laborious manual defect shape annotation, natural language descriptions guide the network to align with highly generalizable features from Contrastive Language-Image Pre-training (CLIP), steering the attention maps of the optoelectronic neural network toward defect shapes. Furthermore, a Localization Accuracy for Attention (LAA) metric is proposed to quantify shape-level defect localization performance. Experiments on transparent material defect detection validate the system's effectiveness. Parametric analysis reveals how measurement matrices, compression ratios, and block sizes affect accuracy. Results show that, compared to traditional imaging, the proposed architecture maintains equivalent accuracy while reducing data volume by 90% for Vision Transformers and computational workload by 60% for Convolutional Neural Networks. This low-data paradigm offers an efficient solution for industrial automation scenarios involving massive data streams, high acquisition costs, or constrained edge resources.
### Title:
          Communicability-Inspired Positional Encoding (CIPE)
 - **Authors:** Yipeng Zhang, Zhongtian Sun, Pietro Liò, Kelin Xia
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Positional encodings (PEs) are essential for Transformers. Yet designing effective PEs for non-Euclidean graphs remains challenging. Such encodings should ideally induce an Attention-Compatible Geometry for self-attention: not merely describing graph structure, but defining a geometry whose inner products reflect meaningful structural relatedness. To realize this geometry, we propose Communicability-Inspired Positional Encoding (CIPE), built from communicability, a measure between pairs of nodes that aggregates contributions from paths of all lengths. By construction, CIPE inner products recover communicability, converting global multi-path connectivity into an attention-ready similarity geometry. For practical Transformer training, we introduce dimensionality alignment, mapping graph-size-dependent CIPE representations to prescribed dimensions while faithfully preserving the induced geometry. Empirically, CIPE improves structure-agnostic Transformers by 35.5% on average across seven benchmarks, outperforming representative PEs; it also consistently improves structure-biased graph Transformers, where competing PEs often yield only marginal benefits. These results position CIPE as a principled framework for attention-compatible graph positional encodings.
### Title:
          REViT: Roto-reflection Equivariant Convolutional Vision Transformer
 - **Authors:** Sheir A. Zaheer, Alexander C. Holston, Chan Y. Park
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we propose a discrete roto-reflection group equivariant vision transformer with convolutional attention. Roto-reflection equivariant networks preserve the rotational, flip and positional symmetry in feature maps, making them useful for tasks where orientation of the inputs is relevant to the model outputs. In image classification and object detection, most of the studies on roto-reflection equivariant models have focused on using convolutional neural networks rather than vision transformers. In this paper, we examine the challenges involved in achieving equivariance in vision transformers, and we propose a simpler way to implement a discretized roto-reflection group equivariant vision transformer. The experimental results demonstrate that our approach outperforms the existing approaches for developing discrete roto-reflection group equivariant neural networks for image classification.
### Title:
          Efficient Remote Sensing Instance Segmentation with Linear-Time State Space Distilled Visual Foundation Models
 - **Authors:** Qinzhe Yang, Keyan Chen, Jia Xu, Zhenwei Shi, Zhengxia Zou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The computational complexity of Transformers scales quadratically with the number of tokens, which significantly constrains the efficiency of vision models, particularly recent ViT-based foundation models in dense prediction tasks. Instance segmentation, a typical dense visual prediction task in the remote sensing field, faces similar challenges. In this paper, inspired by the recent advances of knowledge distillation in large language models, we introduce RS4D - a new remote sensing instance segmentation method with linear computational complexity, which addresses the inefficiency of long sequence modeling through distilled state space modeling (SSM). We propose an adaptive noise and masking knowledge distillation training method for pre-training lightweight SSM backbones, which effectively compresses knowledge from the vast self-attention space into a compact, dense linear state space. We also design a remote sensing image instance segmentation architecture based on this lightweight visual encoder, where we explore variants of three different backbones and two segmentation heads. Extensive experiments are conducted on multiple benchmark datasets, including SSDD, WHU, and NWPU. Compared to ViT-based approaches, our proposed SSM backbone achieves an 8x reduction in parameters and a 9x reduction in FLOPs while maintaining comparable or superior accuracy to both ViT- and CNN-based instance segmentation methods. The implementation codes have been publicly available at this https URL.
### Title:
          Lifelong In-Context Learning with Transformers Requires Parametric Forms of Attention
 - **Authors:** Luke McDermott, Robert W. Heath jr., Rahul Parhi
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Lifelong continual learning remains an obstacle on the path to human-like intelligence. Modern transformers show sparks of intelligence with in-context learning. The quadratic nature of attention, however, prohibits transformers from performing this process on arbitrarily long sequences. In this work, we argue that extending in-context learning to lifelong settings is a practical solution for continual learning in AI agents. In particular, we argue that \emph{parametric forms of attention} are needed to understand a lifetime of context with transformers on a fixed hardware budget. These attention mechanisms learn the relationship between keys and their associated values at test-time with parametric regression. Our generalization of parametric approaches (linear attention, state-space models, fast weight programmers, and test-time training layers) contrasts with nonparametric counterparts like softmax attention. They replace the ever-growing key-value cache with an online-trainable neural network, maintaining a constant memory footprint. We highlight how parametric attention currently fall short of lifelong learning due to limited memory capacity or costly online updates. To address these issues, we pose a set of open questions with novel insights to guide the field toward long-horizon agents.
### Title:
          General Techniques for Reducing Key-Switching Overhead in Privacy-Preserving Two-Party Transformer Inference
 - **Authors:** Wenshao Yang, Zhenhua Liu, Dongdong Yao
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In secure two-party Transformer inference, linear layers are typically evaluated using Fully Homomorphic Encryption (FHE) through plaintext-ciphertext or ciphertext-ciphertext matrix multiplications, where key switching primarily occurs and dominates computational overhead in both FHE-based and hybrid FHE-MPC systems. Existing optimizations rely heavily on packing-specific algorithms, limiting their general applicability. Targeting this overhead from a packing-independent perspective, we propose a preprocessing-assisted method for secure attention computation. By decomposing attention into precomputable operations and online interactions, this method reduces online inference-phase key switching without modifying existing packing strategies. However, the first method shifting key switching offline introduces additional storage requirements. To address this, we propose storage-communication trade-off techniques that replace large precomputed ciphertexts with modest online communication, enabling flexible deployment under varying resource constraints. While ciphertext-ciphertext matrix multiplication is offloaded to the preprocessing phase in hybrid schemes and the first layer of FHE-based schemes, these operations still persist in the offline stage and subsequent FHE layers. To further optimize it, we propose a fused key-switch technique targeting the multiplication-followed-by-rotation pattern, which frequently arises in existing RNS-CKKS matrix multiplication schemes. By combining relinearization and rotation into a single procedure, this technique reduces the associated computation costs. Analytical evaluations demonstrate that our proposed techniques significantly reduce online key-switch overhead and provide flexible trade-offs between storage and communication without requiring modifications to existing packing strategies.
### Title:
          Lightweight PCGAE-Net: Parallel CrossGate Attention and Bottleneck AutoEncoder for Efficient 5G Channel Prediction
 - **Authors:** Uma Kishore Godavarti, K. Giridhar, Vanani Prince Dharmendrabhai, Anchit Panday, Madhan Raj Kanagarathinam
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate channel state information (CSI) prediction is essential for proactive beamforming and resource management in 5G massive MIMO systems, yet the deployment of high-accuracy transformer-based predictors on base-station hardware remains challenging because the most capable models carry upwards of 30\,M parameters. This paper introduces Lightweight PCGAE-Net, which addresses the efficiency problem not by post-hoc compression but by correcting two architectural flaws in the current state of the art. The first is a sequential attention ordering bias: in CS3T-UNet, group-wise temporal attention (GTA) always operates on features that have already been transformed by cross-shaped spatial attention (CSA), distorting what temporal information GTA can capture. We remove this dependency by routing both attention modules to the same layer-normalized input and combining their independent outputs through a learned per-channel sigmoid CrossGate. The second flaw is an uncompressed bottleneck: applying full self-attention at the deepest encoder stage, where channel depth reaches $4C$, is quadratically expensive and carries redundant features. A Bottleneck AutoEncoder (BAE) with $1\times1$ convolutions halves this depth and uses an auxiliary reconstruction loss to prevent information collapse. Wrapping these components inside a shallower encoder-decoder with frequency-domain dimensionality reduction ($N_f\!=\!32$, $C\!=\!48$) produces a model with just 8.54\,M parameters -- 58\% fewer than the CS3T-UNet baseline -- that outperforms it by up to 3.26\,dB at 5\,km/h and 6.0\,dB at 9\,km/h in single-step prediction on QuaDriGa dataset.
### Title:
          TopoCast: A Topological Fidelity Framework for Evaluating Transformer-Based Time Series Forecasting
 - **Authors:** Sandeepa Weerasekara, Sandareka Wickramanayake
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning-based models have achieved state-of-the-art performance in Time Series Forecasting (TSF), yet their evaluation remains dominated by pointwise error metrics such as Mean Squared Error (MSE), which quantify numerical accuracy but overlook structural properties of the forecast signal, including recurrent dynamics, oscillatory behavior, and phase alignment. As a result, forecasts exhibiting over-smoothing, phase shifts, or frequency distortions may achieve favorable error scores despite substantial structural degradation. To address this limitation, we propose TopoCast, a topology-driven framework for evaluating structural fidelity in TSF. TopoCast reconstructs phase-space representations of forecast and ground-truth sequences using Takens delay embedding and applies persistent homology to characterize their intrinsic dynamics. We derive four complementary topological fidelity measures from persistence diagrams and aggregate them into a Topological Fidelity Score (TFS). We further introduce dominant cycle overlap, a novel metric that maps persistent topological features to the temporal domain to assess whether dominant oscillatory patterns occur at the correct time points. Combined with TFS, this yields the Localized Topological Fidelity Score (LTFS), a phase-aware measure that captures temporal localization errors invisible to existing evaluation metrics. Experiments on five Transformer architectures across three real-world benchmark datasets demonstrate that models with similar forecasting errors can exhibit markedly different structural fidelity profiles, revealing failure modes overlooked by conventional evaluation and highlighting the value of topology-aware forecast assessment.
### Title:
          Optimizing Abstractive Summarization With Fine-Tuned PEGASUS
 - **Authors:** Sadiul Arefin Rafi, Naimur Rahman, Kazi Nazibul Islam, Ha-mim Ahmad, Farig Yousuf Sadeque
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Abstractive text summarization is the technique of generating a short and concise summary comprising the salient ideas of a source text without making a subset of the salient sentences from the source text. The introduction of transformer models such as BART, T5, and PEGASUS has made this sort of summarization process more efficient and accurate. The objective of this paper is to fine-tune PEGASUS on the XL-Sum English corpus to achieve a better performance compared to the baseline mT5 model. The performance of the generated summaries from the fine-tuned model is evaluated using the ROUGE metric, which basically compares the auto-generated summaries with human-created summaries. To the best of our knowledge, the results from our fine-tuned PEGASUS model give a state-of-the-art performance on the XL-Sum English Corpus. To quantify the improvement, there is a 4.04% improvement in the ROUGE-1 score, a 15.25% increase in the ROUGE-2 score, and a 3.39% improvement in the ROUGE-L score from the baseline model.
### Title:
          Causal-rCM: A Unified Teacher-Forcing and Self-Forcing Open Recipe for Autoregressive Diffusion Distillation in Streaming Video Generation and Interactive World Models
 - **Authors:** Kaiwen Zheng, Guande He, Min Zhao, Jintao Zhang, Huayu Chen, Jianfei Chen, Chen-Hsuan Lin, Ming-Yu Liu, Jun Zhu, Qianli Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autoregressive video diffusion with causal diffusion transformers has emerged as a major paradigm for real-time streaming video generation and action-conditioned interactive world models. In this work, we extend rCM, an advanced diffusion distillation framework, to autoregressive video diffusion. The core philosophy of rCM lies in the complementarity between forward and reverse divergences, represented by consistency models (CMs) and distribution matching distillation (DMD), respectively, in diffusion distillation. This philosophy naturally carries over to the autoregressive setting, where teacher-forcing (TF) provides an offline, forward-divergence causal training paradigm, while self-forcing (SF) corresponds to an on-policy, reverse-divergence refinement. Our contributions are: (1) through extensive experiments, we show that teacher-forcing CM is currently the best complement to self-forcing DMD as an initialization strategy (2) we present the first implementation of teacher-forcing-based continuous-time CMs (e.g., sCM/MeanFlow) for autoregressive video diffusion, enabled by our custom-mask FlashAttention-2 JVP kernel, achieving 10$\times$ faster convergence compared to discrete-time CMs (dCMs) (3) we introduce Causal-rCM, a leading, unified, and scalable algorithm-infrastructure open recipe for diffusion distillation and causal training (4) we achieve state-of-the-art streaming video generation performance in both frame-wise and chunk-wise settings, using only synthetic data for training. Notably, our distilled 2-step causal Wan2.1-1.3B model achieves a VBench-T2V score of 84.63 with only 1 or 2 sampling steps. We further apply Causal-rCM to Cosmos 3, an advanced omnimodal world foundation model for physical AI with action-conditioned generation capability, enabling an interactive world model.
### Title:
          Spam and Sentiment Detection in Arabic Tweets Using MARBERT Model
 - **Authors:** Abrar Alotaibi, Atta-ur Rahman, Raheel Alhaza, Wala Alkhalifa, Narjes Alhajjaj, Atheer Alharthi, Dhai Abushoumi, Maryam Alqahtani, Dania Alkhulaifi
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Saudi Telecom Company (STC) is among the most popular companies in Saudi Arabia, with many customers. Yet, there is still a big room for improvement in users' satisfaction. Social media is the most robust platform to gauge users' satisfaction and determine their sentiments and critics. Twitter is among the most popular social media platform in this regard. STC customers prefer to use Twitter to write their feedback because it's a fast way to get responses due to the STC customer services account. One way to achieve customer demands and improve customer service is using the Sentiment Analysis tool. Sentiment Analysis on Twitter is highly used because of the significant number of tweets and the different opinions. Likewise, Deep learning is the best existing Sentiment Analysis method, and it has diverse models. Bidirectional Encoder Representations from Transformers (BERT) model is one of the deep learning models which have achieved excellent results in Sentiment Analysis for Natural Language Processing (NLP). NLP is mainly investigated in the English language. However, for Arabic, there is a significant gap to be filled. This study trained the proposed model using MARBERT and measured the performance using f1-score, precision, and recall metrics. We trained the model with an Arabic dataset of 24,513 tweets, including 1,437 positive, 13,828 negative, 5,694 neutral, 1,221 sarcasm, and 2,297 indeterminate tweets. The main goal is to analyze the tweets and get the sentiment to improve STC customer service. The proposed scheme is promising in terms of accuracy in contrast to existing techniques in the literature.
### Title:
          Fault of Our Stars: Behavioral Drivers of Rating-Sentiment Incongruence
 - **Authors:** Ramanaish Abaiyan, Ruththiragayan Sutharsan, Kusal Amantha, Anusan Krishnathas, Asma Rauff, Kovindarajah Sriyathurshan, Patalee Narasinghe, Nirasha Munasinghe, Nisansa de Silva, Sandareka Wickramanayake
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 When people share experiences online, they often express thoughts in two ways: a star rating and a written review. In sentiment analysis, ratings are widely used as convenient weak labels for textual sentiment, yet whether the two actually agree is rarely questioned. This study investigates sentiment-rating incongruence, where the sentiment expressed in review text differs from the sentiment implied by the assigned star rating, in Sri Lankan tourism attraction reviews. A dataset of 16,156 reviews from 2010 to 2023 is analyzed using a transformer-based sentiment pipeline that derives textual sentiment independently of assigned ratings. Incongruence occurs in 18.6% of reviews and falls into six directional patterns, with Conservative Rater and Obligatory 5-Star behaviors accounting for the majority of mismatches. Prevalence also varies across venue types, with museums showing the highest rates. Statistical tests, logistic regression, Random Forest, and SHAP analysis identify venue type, reviewer expertise, review length, and temporal factors as contributors to rating-text divergence. Overall, this study demonstrates that star ratings are not interchangeable with textual sentiment and should be validated before being treated as ground-truth labels in NLP.
### Title:
          ScaleHP: Estimating Hand Pose in Metric Space
 - **Authors:** Ruitao Jing, Xingyu Chen, Hongyang Li, Qing Jiang, Yukai Shi, Lei Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate metric-space hand pose estimation (HPE) is essential for immersive human-computer interaction and robotics. However, most existing methods predict poses in a root-relative coordinate system and cannot estimate the hand in absolute metric scale. In this work, we observe that the intrinsic proportional relationships among human hand bones encode stable anthropometric priors that implicitly correlate with the overall metric size of the hand. Leveraging this insight, we present ScaleHP, an end-to-end one-stage hand pose estimation framework that bypasses fragile extrinsic depth modules to recover the hand in metric space. ScaleHP employs a transformer-based decoder with a novel scale token to fuse multi-scale morphological and appearance features. By solving for metric coordinates through a perspective-constrained least-squares approach, we achieve high-precision pose estimation in the camera coordinate system. ScaleHP delivers state-of-the-art performance, including 35.8 CS-MPJPE on FreiHand and 4.6/5.9 PA-MPJPE on DexYCB and HO3Dv3. These results demonstrate that internal biological constraints significantly reduce relative geometry and absolute metric errors, offering a robust solution for generalized, real-world hand tracking.
### Title:
          NEURON-Fabric: Architecture-Runtime Co-Design for Controlled Low-Bit Gradient Communication
 - **Authors:** Ziqiang Wang, Changcheng Huang, Chung-Horng Lung
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large-scale neural-network training repeatedly aggregates gradients across devices, making communication a central cost in distributed learning. Low-bit gradient aggregation can reduce this cost, but applying it as a static replacement for full-precision communication can destabilize training because safe precision depends on training phase, model structure, runtime bucketization, and the communication substrate. This paper presents NEURON-Fabric, a profile-guided runtime system for controlled low-bit gradient communication. NEURON-Fabric uses calibrated operating profiles, model-aware runtime bindings, online training-health monitoring, and reducer-capacity checks to decide when low-bit aggregation should be admitted, when execution should fall back to FP32, and which model regions are eligible for each route. The runtime preserves model semantics inside mixed DDP buckets and treats reducer admission as an architecture-runtime co-design problem rather than as a standalone compression operator. Across vision, Transformer, and autoregressive language-model workloads, NEURON-Fabric validates the path from calibration to distributed communication-hook execution. Static low-bit communication can collapse training accuracy, while profile-guided control preserves accuracy near full-precision references or calibrated targets and reduces modeled gradient-communication traffic in the evaluated settings. Transformer and billion-parameter language-model checks show that the same routing and fallback mechanisms execute across model families and multi-node deployments. Reducer-side replay and reducer-path measurements identify when compact sign-count aggregation is expected to reduce communication cost and when endpoint capacity should trigger fallback.
### Title:
          A Benchmark for Heterogeneous Stereo Deblurring with Physically- and Epipolar-constrained Cross Attention
 - **Authors:** Hoju Shin, Jiah Kim, Seung-Wook Kim, Seowon Ji
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern stereo-capable smartphones enable immersive XR content capture. However, hardware heterogeneity across camera modules often causes severe asymmetric blur artifacts. Existing methods and benchmarks largely assume homogeneous stereo setups and therefore do not explicitly address such asymmetric degradation. To bridge this gap, we present a dedicated framework for heterogeneous stereo deblurring. First, we introduce the heterogeneous stereo deblurring (HSD) dataset, constructed from real smartphone stereo captures via multi-frame integration. Second, we propose physically- and epipolar-constrained cross attention (PECA), a lightweight module that restricts cross-view matching to an epipolar search window bounded by a optics-derived disparity upper bound. By enforcing physically valid disparity constraints, PECA enables efficient and reliable cross-view feature fusion. Moreover, our confidence-weighted attention with residual fusion emphasizes cross-guided deblurring when correspondences are reliable, while naturally falling back to self-deblurring in occluded or unreliable regions. PECA is architecture-agnostic and consistently improves CNN-, Transformer-, and NAFNet-based baselines. Extensive experiments on HSD show that PECA-enhanced models achieve improved restoration performance with favorable efficiency.
### Title:
          Hierarchical Reinforcement Learning for Neural Network Compression (HiReLC): Pruning and Quantization
 - **Authors:** Kamar Hibatallah Baghdadi, Kawther Guoual Belhamidi, Sara Belhadj, Aissa Boulmerka, Nadir Farhi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present HiReLC, a hierarchical ensemble-reinforcement learning framework for automated joint quantization and structured pruning of deep neural networks. The framework decomposes the compression search across two levels of abstraction: low-level agents (LLAs) operate independently per block, selecting per-kernel configurations over a multi-discrete action space spanning bitwidth, pruning keep-ratio, quantization type, and granularity, while high-level agents (HLAs) coordinate global budget allocation via ensemble voting guided by Fisher Information-based sensitivity estimates. To mitigate the computational cost of policy evaluation, an iterative active learning loop interleaves surrogate-guided RL optimization with post-compression fine-tuning, using a lightweight MLP surrogate to amortize expensive evaluations and a logit-MSE proxy during cold-start. The surrogate is used for reward shaping rather than as a replacement for final post-compression evaluation. The controller is architecture-agnostic by design, with a modular layer abstraction decoupling the RL environment from the underlying network topology. Experiments across Vision Transformer and CNN benchmarks demonstrate effective parameter-storage compression ratios of 5.99 - 6.72$\times$ with a 3.83 % gain in one setting and 0.55 - 5.62 % accuracy drops elsewhere, supporting hierarchical policy decomposition and sensitivity-aware guidance as practical design choices for joint neural network compression.
### Title:
          Dziri Voicebot: An End-to-End Low-Resource Speech-to-Speech Conversational System for Algerian Dialect
 - **Authors:** Dihia Lanasri, Fairouz Taki, Asma Kemmoum
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automatic speech and language technologies are still heavily biased toward high-resource languages, limiting their applicability to dialectal and low-resource settings such as Algerian Dialect. This language presents additional challenges including lack of standardized orthography, frequent codeswitching with French, and scarcity of annotated speech resources. This paper addresses the problem of building a complete speech-to-speech conversational system for Algerian Dialect. We propose a modular pipeline integrating automatic speech recognition, natural language understanding, retrieval-augmented generation, and text-to-speech synthesis within a unified architecture. This work is the continuation of our previous work on Algerian dialectal conversational systems Bechiri and Lanasri [2026], extending it from text-based dialogue modeling to full speech-based interaction. We constructed dedicated datasets for ASR, NLU, and TTS in the telecom domain and fine-tune pretrained models for each component. The ASR system is built on Whisper-based adaptation, while the NLU module combines transformer-based embeddings with a task-oriented dialogue framework. A neural TTS system is trained on a newly collected dialectal corpus to enable spoken response generation. Experimental results show strong performance across all components, including low word error rate for ASR, high intent classification and entity recognition scores for NLU, and stable speech synthesis quality. The proposed system provides a reproducible baseline for end-to-end conversational modeling in Algerian Dialect.
### Title:
          Privacy Vulnerabilities of Attention Layers in Tabular Foundation Models and Protection of High-Risk Queries
 - **Authors:** Tânia Carvalho, Maxime Cordy
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tabular foundation models are commonly assumed to present limited privacy concerns as they are often pre-trained on large collections of synthetic data. However, these models leverage in-context learning, where sensitive records may be provided directly at inference time as labelled context examples. In this paper, we demonstrate that predictions generated via the attention mechanism leak sufficient information to enable effective Membership Inference Attacks (MIAs). To highlight this vulnerability, we propose AMIA (Attention-based Membership Inference Attack), a shadow-model-free attack that exploits the concentration of transformer attention patterns. Our results show that attention mechanisms reveal strong membership signals, which exceed classical confidence-based attacks, achieving an average gain of 7.7\%, specially in low false-positive regimes. To mitigate this risk, we introduce an inference-time defence inspired by $k$-anonymity principles. This approach reduces the uniqueness of context-key representations without introducing random noise or retraining the model. By targeting only high-risk queries identified through AMIA scores, the defence substantially reduces membership leakage of this attack by an average of 50\% and 25\% against confidence-based attacks, while preserving predictive utility with only 3.9\% performance degradation. Beyond showing that context examples are vulnerable, we further demonstrate that fine-tuning introduces an additional source of privacy risk. In particular, samples whose prediction confidence increases after fine-tuning become more susceptible to MIAs, indicating that fine-tuning can amplify memorisation and expose sensitive training information through confidence shifts.
## Keyword: autonomous driving
### Title:
          Towards Scalable Multi-Task Reinforcement Learning with Large Decision Models
 - **Authors:** Thibaut Kulak
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent progress in large-scale sequence modeling has shown that a single model can learn useful representations across highly diverse data distributions. Inspired by these advances, we investigate whether a unified transformer policy can be trained across large collections of heterogeneous reinforcement learning environments. We introduce LDM-v0, a Large Decision Model trained offline on trajectories collected from thousands of environments spanning multiple domains and modalities. LDM-v0 is a multi-task, multi-modal transformer policy conditioned on histories of observations, actions, rewards, and termination signals, and trained through supervised next-action prediction over offline trajectories. We describe the environment infrastructure, automated data generation pipeline, model architecture, and training methodology used to build LDM-v0, and evaluate its performance across diverse environments. We show that a single pretrained model matches the performance of independently trained task-specific reference policies on approximately 1,000 environments including robotics, autonomous driving, inventory management, cybersecurity, trading, and video games. These results demonstrate the feasibility of large-scale offline pretraining across heterogeneous reinforcement learning environments using a single transformer policy.
### Title:
          Reward-Conditioned Attention: How Reward Design Shapes What Autonomous Driving Agents See
 - **Authors:** Mohamed Benabdelouahad, Ahmed Djalal Hacini, Nadir Farhi, Aissa Boulmerka
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We investigate how reward design shapes the internal attention patterns of reinforcement learning agents trained for autonomous driving. Using three Perceiver-based agents that share identical architectures and training data but differ only in their reward configurations$\unicode{x2014}$ranging from basic violation penalties to continuous proximity penalties$\unicode{x2014}$we analyze cross-attention allocation across 50 real-world scenarios from the Waymo Open Motion Dataset. A central methodological finding is that naïve pooling of timesteps across episodes substantially underestimates the attention$\unicode{x2013}$risk relationship; within-episode correlation with Fisher z-transform aggregation is the appropriate statistic and reveals a robustly positive link between collision risk and agent-directed attention. Building on this validated methodology, we demonstrate two reward-conditioned effects: agents trained with navigation rewards allocate up to $2.0\times$ more attention to GPS-path tokens than those trained with additional proximity penalties$\unicode{x2014}$and $4.7\times$ more than agents with no navigation incentive$\unicode{x2014}$revealing that reward content directly determines which scene elements the encoder prioritizes, and continuous time-to-collision penalties create a $\textit{learned vigilance prior}$$\unicode{x2014}$elevated resting agent surveillance maintained throughout collision-free phases. In several scenarios, the complete-reward and minimal-reward models exhibit opposite attention$\unicode{x2013}$risk correlation directions, demonstrating that reward design can qualitatively reverse attentional strategy rather than merely modulating its magnitude. These results suggest that attention analysis is a practical diagnostic for verifying that a reward function produces the intended representational behaviour in safety-critical RL systems.
### Title:
          Causality-Based Parametric Control Barrier Function for Safe Multi-Vehicle Interaction
 - **Authors:** Yiwei Lyu, Caleb Chang, John M. Dolan
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Safe control has been widely studied in various safety-critical applications, for instance, autonomous driving. In order to ensure the autonomous vehicle does not collide with other vehicles, it is essential to obtain an accurate expectation of surrounding vehicles' behavior and react adaptively. Instead of assuming fully cooperative and homogeneous vehicles using the same safety-critical controllers, recent works have been exploring different data-driven approaches to model the neighboring vehicles' underlying controllers with observed data. However, existing works either suffer from 1) the inter-vehicle influence during the multi-vehicle interaction, which makes it hard to determine the causality of surrounding vehicles' behavior in controller modeling, or 2) being dominated by the worst-case analysis, which may lead to overly conservative behavior. In this paper, we extend the prior work on Parametric-Control Barrier Function (Parametric-CBF) to multi-robot interactions with embedded causality inference to explicitly reason over the inter-vehicle influence. Given the learned Causality-based Parametric-CBF, we present an adaptive safety-critical controller that allows the ego vehicle to safely react to surrounding vehicles with the learned expectation. We demonstrate that by leveraging the motion flexibility among multi-vehicle systems, task efficiency can be greatly improved in various interaction-intensive scenarios.
### Title:
          Tensor-Based Batch Fuzzing with Adaptive Perturbation Scaling for Deep Neural Networks
 - **Authors:** Guanqin Zhang, Yulei Sui
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep neural networks are increasingly deployed in safety-critical domains such as autonomous driving and medical diagnosis, yet their opaque, high-dimensional parameter spaces make it difficult to systematically assess model reliability on unseen inputs. Existing coverage-guided sequential fuzzing frameworks for DNNs inherit a one-input-per-iteration design from traditional software fuzzing and apply uniform perturbation budgets across all input dimensions, limiting both testing throughput (i.e., inputs processed per unit time) and the precision of input-space exploration. We present a new specification-aware batch fuzzing framework with adaptive perturbation scaling that addresses both limitations. Rather than relying on a fixed global perturbation radius epsilon, our approach derives mutation step sizes from specification-defined feasible ranges (the gap between lower and upper bounds) using a shared scale factor. This scaling can be applied either as a global scalar (isotropic) or as per-dimension step sizes (anisotropic), keeping perturbations consistent with the underlying constraint structure. As a result, the fuzzer can explore input spaces with heterogeneous feature scales more effectively across all specifications in the batch. We embed input constraints and output property checks directly into the network as non-trainable layers, yielding a wrapped model that processes B specification instances in a single batched iteration, substantially improving fuzzing efficiency and counterexample exploration. We evaluate our framework extensively on three benchmarks, covering six networks and over 400 specifications across TrafficSigns, Cifar100, and TinyImageNet. Our tensor-based fuzzing achieves up to 40X higher throughput and 4X more violations than the sequential baseline under the same time budget, demonstrating significantly improved effectiveness in specification-guided fuzzing.
### Title:
          SafeGen: LLM-Driven Assertion Generation and Fault Criticality Evaluation for Functional Safety
 - **Authors:** Xuanyi Tan, Arjun Chaudhuri, Rubin Parekhji, Krishnendu Chakrabarty
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With advances in autonomous driving and electric vehicle technologies, functional safety has become a critical requirement in automotive chip design. Traditional simulation-based fault analysis is often overly conservative at the module level and fails to accurately reflect fault criticality. This paper presents SafeGen, an LLM-driven, formal-verification-assisted framework for functional-safety-oriented fault criticality assessment. SafeGen leverages large language models (LLMs) and a document-level Hyper Knowledge Graph (HyperKG) that incorporates Failure Modes, Effects, and Diagnostic Analysis (FMEDA) guidelines to extract verifiable specifications from design and safety documents and evaluate their relevance to overall system safety. The HyperKG is further enriched with register-transfer-level (RTL) information to guide the generation of Functional Safety Assertions (FSAs) that are both semantically grounded and design-aware. Each assertion is linked to its corresponding specification, enabling traceable reasoning throughout the assessment process. A gate-to-RTL fault-mapping mechanism supporting both stuck-at and bridging faults, combined with formal property verification (FPV), enables semantic-level fault criticality grading based on specification-linked assertion violations. A digital-physical co-simulation platform for a field-oriented control (FOC) system is developed to validate SafeGen. Experimental results demonstrate that SafeGen generates higher-quality assertions than existing LLM-based assertion generation frameworks while providing greater semantic interpretability in fault criticality assessment compared with traditional simulation-based approaches.
### Title:
          ASSCG: Just-Right Gating over Chattering for Fast-Slow LLM Planning in Autonomous Driving
 - **Authors:** Sining Ang, Yuan Chen, Liu Haiyan, Xuanyao Mao, Jason Bao, Xuliang, Bingchuan Sun, Yan Wang
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) can improve autonomous driving planning but are costly to query online, and existing fast-slow planners often rely on hand-designed triggering rules that either over-call the slow system or call it at the wrong times. We formulate slow-system invocation as a resource-aware sequential decision problem and propose the Adaptive Slow-System Control Gate (ASSCG), which makes frame-level Query/Cache/Drop decisions to refresh, reuse, or suppress slow guidance. ASSCG uses an RWKV backbone for efficient long-horizon gating and is trained with supervised fine-tuning followed by GRPO-style compute-aware reinforcement fine-tuning. We apply ASSCG to two different fast-slow architectures: (i) AsyncDriver on nuPlan Hard20 closed-loop evaluation, where ASSCG improves score to 67.28 (+2.28) while reducing average end-to-end inference latency by 60%; and (ii) a RecogDrive-based dual system that we build by replacing its original VLM-2B module with a lightweight ViT-based fast planner and adding an LLM slow planner, evaluated on NAVSIM, where ASSCG achieves 91.4 PDMS (+0.6) and increases average speed by 25%. The project page, including video visualizations and additional results, is available at this https URL.
### Title:
          Reasonable Motion: A General ASP Foundation for Environment Constrained Movement Trajectory Computation
 - **Authors:** Julius Monsen, Jakob Suchan, Mehul Bhatt, Lars Karlsson
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Human-Computer Interaction (cs.HC); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a general answer set programming based hybrid quantitative-qualitative method for computing constrained branching trajectory modes for moving objects in real-world settings. The method performs constrained traversal of an environment graph, enumerating geometrically admissible motion behaviours as stable models, each constituting a distinct trajectory mode characterised by both domain-dependent and independent factors such as derived event sequence, map topology, and domain norms. The hybrid trajectory computation method is generally applicable across motion characteristics typically encountered in diverse dynamic domains with moving objects, e.g., autonomous driving. We demonstrate applicability and highlight how computed trajectories are traceable to their underlying stable model, thereby affording verifiable interpretability that purely learned approaches cannot provide. We also perform an empirical evaluation with Argoverse 2, a large-scale real-world autonomous driving benchmark representative of the class of dynamic domains within the scope of the proposed method.
### Title:
          Auto-Labelling-Based Domain Transfer for 3D Object Detection on a Bicycle-Mounted LiDAR Platform
 - **Authors:** Mario Finkbeiner, Max A. Buettner, Kanak Mazumder, Fabian B. Flohr
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable 3D perception of vulnerable road users (VRUs) such as cyclists and pedestrians is essential for their safety in urban traffic and a core requirement for autonomous driving (AD). Alongside advances in vehicle-based perception, research increasingly equips bicycles with sensors to study traffic from a perspective native to VRUs. Such platforms still rely on LiDAR detectors originally trained on vehicle data, yet annotated 3D data from a cyclist's perspective is scarce. How well these detectors generalise to this setting has not been evaluated. We present a 3D object detection benchmark of 1,027 annotated LiDAR keyframes (over 18,000 3D bounding boxes) from the FUSE-Bike platform in urban Munich. We evaluate four nuScenes-pre-trained detectors against 1,854 human-verified ground-truth (GT) boxes both in their original form and after finetuning on training labels produced by a VRU-dedicated auto-labelling pipeline that requires no manual annotation. The zero-shot domain gap is concentrated on the VRU classes. Finetuning recovers most of it, improving mean average precision (mAP) by up to 23.4 points with the largest gains on pedestrians and cyclists, and the adapted detectors even surpass the quality of the auto-labels they were trained on. The benchmark provides a reproducible baseline for VRU-centric 3D detection and shows that auto-labels are a viable substitute for manual annotation when adapting vehicle-trained detectors to a cyclist platform.
### Title:
          UniTeD: Unified Temporal Diffusion for Joint Perception and Planning in Autonomous Driving
 - **Authors:** Bo Zhao, Xinting Zhao, Naifan Li, Erkang Cheng, Haibin Ling
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion models have shown strong potential for multi-modal planning in end-to-end autonomous driving. However, most existing methods confine diffusion to the planning module, conditioning on fixed outputs from separate discriminative perception networks. This decoupled design propagates perception errors to the planner, increasing optimization difficulty and reducing robustness. To overcome these limitations, we propose UniTeD, a Unified Temporal Diffusion framework that jointly models perception and planning through iterative denoising in a shared generative space. By enabling bidirectional information exchange, the framework facilitates mutual refinement between tasks and improves robustness via noise-conditioned multi-task training. We further extend this unified diffusion paradigm to a streaming setting by incorporating temporal context. A Temporal Transition Module (TTM) is introduced to resolve the noise-level mismatch between historical and current frames. In addition, we propose an Anchor Refresh Strategy (ARS) to alleviate the training-inference distribution shift commonly observed in sparse diffusion-based end-to-end driving frameworks. Without bells and whistles, UniTeD achieves state-of-the-art performance across multiple benchmarks, surpassing both recent discriminative end-to-end methods and diffusion-based planning approaches.
### Title:
          DSP-SLAM++: A Unified Framework for Multi-Class, High-Fidelity Object SLAM in the Wild
 - **Authors:** Ahmad Kourani, Ghina Daoud, Daniel Asmar, Imad Elhajj
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing object-aware SLAM systems force a trade-off between real-time performance, multi-class support, and the generation of high-fidelity, semantically coherent object models. To address this trade-off, we present DSP-SLAM++, which extends the DSP-SLAM framework with an asynchronous mapping pipeline for real-time performance and dedicated sensor fusion adaptations for a monocular fisheye-LiDAR suite. Experiments demonstrate that our system generates fine-grained, geometrically-complete shapes for multiple object classes while eliminating severe mapping thread bottlenecks by reducing maximum object processing latency by up to 70\% compared to the state-of-the-art baseline, enabling robust, real-time performance on a challenging 25 Hz multi-class datasets. This work makes high-fidelity, multi-class object SLAM more practical for real-world applications like autonomous driving and robotic manipulation by enabling its use on platforms with common fisheye-LiDAR sensor setups. The open-source code is available at: [this http URL].
### Title:
          G2DP: Diffusion Planning with Spatio-Temporal Grid Guidance
 - **Authors:** Hang Yu, Ye Jin, Alessandro Canevaro, Julian Schmidt, Julian Jordan, Peizheng Li, Marc Kaufeld, Silvan Lindner, Johannes Betz, Wilhelm Stork
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In autonomous driving, diffusion-based planners have emerged as a promising paradigm for robust motion planning in dense and interactive traffic, as they can effectively model diverse driving behaviors. However, their inherent stochasticity often requires explicit guidance during denoising to ensure safety and route adherence for robust closed-loop execution. Existing guidance typically relies on sparse, entity-centric geometric queries or post-hoc refinement, yielding limited situational awareness and fragile performance in interactive scenes. To address this issue, we propose G2DP (Grid-Guided Diffusion Planning), a diffusion-based planner that directly enforces dense environmental constraints through inference-time guidance. Specifically, G2DP constructs a differentiable spatio-temporal cost volume by fusing probabilistic future occupancy distributions with a route-progress map. By formulating this volume as a continuous safety energy functional, it injects dense gradients directly into the denoising loop, actively steering trajectory generation toward collision-free and progress-optimal regions. Extensive closed-loop evaluations show that G2DP achieves state-of-the-art performance on nuPlan, outperforming the strongest imitation-learning baseline by +7.2 points in reactive score. It further maintains top scores in zero-shot transfers to interPlan and DeepScenario benchmarks, with collision avoidance improving by +10.15 over the unguided approach on interPlan. These results demonstrate that spatio-temporal cost grids serve as an effective representation for robust guidance in diffusion-based planning.
