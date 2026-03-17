# Showing new listings for Tuesday, 17 March 2026
## Keyword: SLAM
### Title:
          Semantic Aware Feature Extraction for Enhanced 3D Reconstruction
 - **Authors:** Ronald Nap, Andy Xiao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Feature matching is a fundamental problem in computer vision with wide-ranging applications, including simultaneous localization and mapping (SLAM), image stitching, and 3D reconstruction. While recent advances in deep learning have improved keypoint detection and description, most approaches focus primarily on geometric attributes and often neglect higher-level semantic information. This work proposes a semantic-aware feature extraction framework that employs multi-task learning to jointly train keypoint detection, keypoint description, and semantic segmentation. The method is benchmarked against standard feature matching techniques and evaluated in the context of 3D reconstruction. To enhance feature correspondence, a deep matching module is integrated. The system is tested using input from a single monocular fisheye camera mounted on a vehicle and evaluated within a multi-floor parking structure. The proposed approach supports semantic 3D reconstruction with altitude estimation, capturing elevation changes and enabling multi-level mapping. Experimental results demonstrate that the method produces semantically annotated 3D point clouds with improved structural detail and elevation information, underscoring the effectiveness of joint training with semantic cues for more consistent feature matching and enhanced 3D reconstruction.
### Title:
          Evaluation of Visual Place Recognition Methods for Image Pair Retrieval in 3D Vision and Robotics
 - **Authors:** Dennis Haitz, Athradi Shritish Shetty, Michael Weinmann, Markus Ulrich
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual Place Recognition (VPR) is a core component in computer vision, typically formulated as an image retrieval task for localization, mapping, and navigation. In this work, we instead study VPR as an image pair retrieval front-end for registration pipelines, where the goal is to find top-matching image pairs between two disjoint image sets for downstream tasks such as scene registration, SLAM, and Structure-from-Motion. We comparatively evaluate state-of-the-art VPR families - NetVLAD-style baselines, classification-based global descriptors (CosPlace, EigenPlaces), feature-mixing (MixVPR), and foundation-model-driven methods (AnyLoc, SALAD, MegaLoc) - on three challenging datasets: object-centric outdoor scenes (Tanks and Temples), indoor RGB-D scans (ScanNet-GS), and autonomous-driving sequences (KITTI). We show that modern global descriptor approaches are increasingly suitable as off-the-shelf image pair retrieval modules in challenging scenarios including perceptual aliasing and incomplete sequences, while exhibiting clear, domain-dependent strengths and weaknesses that are critical when choosing VPR components for robust mapping and registration.
### Title:
          eNavi: Event-based Imitation Policies for Low-Light Indoor Mobile Robot Navigation
 - **Authors:** Prithvi Jai Ramesh, Kaustav Chanda, Krishna Vinod, Joseph Raj Vishal, Yezhou Yang, Bharatesh Chakravarthi
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Event cameras provide high dynamic range and microsecond-level temporal resolution, making them well-suited for indoor robot navigation, where conventional RGB cameras degrade under fast motion or low-light conditions. Despite advances in event-based perception spanning detection, SLAM, and pose estimation, there remains limited research on end-to-end control policies that exploit the asynchronous nature of event streams. To address this gap, we introduce a real-world indoor person-following dataset collected using a TurtleBot 2 robot, featuring synchronized raw event streams, RGB frames, and expert control actions across multiple indoor maps, trajectories under both normal and low-light conditions. We further build a multimodal data preprocessing pipeline that temporally aligns event and RGB observations while reconstructing ground-truth actions from odometry to support high-quality imitation learning. Building on this dataset, we propose a late-fusion RGB-Event navigation policy that combines dual MobileNet encoders with a transformer-based fusion module trained via behavioral cloning. A systematic evaluation of RGB-only, Event-only, and RGB-Event fusion models across 12 training variations ranging from single-path imitation to general multi-path imitation shows that policies incorporating event data, particularly the fusion model, achieve improved robustness and lower action prediction error, especially in unseen low-light conditions where RGB-only models fail. We release the dataset, synchronization pipeline, and trained models at this https URL
### Title:
          Spiking Layer-Adaptive Magnitude-based Pruning
 - **Authors:** Junqiao Wang, Zhehang Ye, Yuqi Ouyang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spiking Neural Networks (SNNs) provide energy-efficient computation but their deployment is constrained by dense connectivity and high spiking operation costs. Existing magnitude-based pruning strategies, when naively applied to SNNs, fail to account for temporal accumulation, non-uniform timestep contributions, and membrane stability, often leading to severe performance degradation. This paper proposes Spiking Layer-Adaptive Magnitude-based Pruning (SLAMP), a theory-guided pruning framework that generalizes layer-adaptive magnitude pruning to temporal SNNs by explicitly controlling worst-case output distortion across layers and timesteps. SLAMP formulates sparsity allocation as a temporal distortion-constrained optimization problem, yielding time-aware layer importance scores that reduce to conventional layer-adaptive pruning in single-timestep limit. An efficient two-stage procedure is derived, combining temporal score estimation, global sparsity allocation, and magnitude pruning with retraining for stability recovery. Experiments on CIFAR10, CIFAR100, and the event-based CIFAR10-DVS datasets demonstrate that SLAMP achieves substantial connectivity and spiking operation reductions while preserving accuracy, enabling efficient and deployable SNN inference.
### Title:
          Thermal Image Refinement with Depth Estimation using Recurrent Networks for Monocular ORB-SLAM3
 - **Authors:** Hürkan Şahin, Huy Xuan Pham, Van Huyen Dang, Alper Yegenoglu, Erdal Kayacan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous navigation in GPS-denied and visually degraded environments remains challenging for unmanned aerial vehicles (UAVs). To this end, we investigate the use of a monocular thermal camera as a standalone sensor on a UAV platform for real-time depth estimation and simultaneous localization and mapping (SLAM). To extract depth information from thermal images, we propose a novel pipeline employing a lightweight supervised network with recurrent blocks (RBs) integrated to capture temporal dependencies, enabling more robust predictions. The network combines lightweight convolutional backbones with a thermal refinement network (T-RefNet) to refine raw thermal inputs and enhance feature visibility. The refined thermal images and predicted depth maps are integrated into ORB-SLAM3, enabling thermal-only localization. Unlike previous methods, the network is trained on a custom non-radiometric dataset, obviating the need for high-cost radiometric thermal cameras. Experimental results on datasets and UAV flights demonstrate competitive depth accuracy and robust SLAM performance under low-light conditions. On the radiometric VIVID++ (indoor-dark) dataset, our method achieves an absolute relative error of approximately 0.06, compared to baselines exceeding 0.11. In our non-radiometric indoor set, baseline errors remain above 0.24, whereas our approach remains below 0.10. Thermal-only ORB-SLAM3 maintains a mean trajectory error under 0.4 m.
## Keyword: odometry
### Title:
          H-RINS: Hierarchical Tightly-coupled Radar-Inertial Navigation via Smoothing and Mapping
 - **Authors:** Ali Alridha Abdulkarim, Mikhail Litvinov, Dzmitry Tsetserukou
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Millimeter-wave radar provides robust perception in visually degraded environments. However, radar-inertial state estimation is inherently susceptible to drift. Because radar yields only sparse, body-frame velocity measurements, it provides weak constraints on absolute orientation. Consequently, IMU biases remain poorly observable over the short time horizons typical of sliding-window filters. To address this fundamental observability challenge, we propose a tightly coupled, hierarchical radar-inertial factor graph framework. Our architecture decouples the estimation problem into a high-rate resetting graph and a persistent global graph. The resetting graph fuses IMU preintegration, radar velocities, and adaptive Zero-Velocity Updates (ZUPT) to generate the smooth, low-latency odometry required for real-time control. Concurrently, the persistent graph is a full-state factor graph maintaining the complete information of poses, velocities, and biases by fusing inertial data with keyframe-based geometric mapping and loop closures. Leveraging Incremental Smoothing and Mapping, the persistent graph can operate without explicit marginalization of variables, preserving their information while ensuring long-term bias observability. The cornerstone of our approach is a probabilistic tight-coupling mechanism: fully observable, optimized biases and their exact covariances are continuously injected from the persistent graph into the resetting graph's prior, effectively anchoring the high-rate estimator against integration drift. Extensive evaluations demonstrate our system achieves high accuracy with drift-reduced estimation at 27x real-time execution speeds. We release the implementation code and datasets upon the acceptance of the paper.
### Title:
          eNavi: Event-based Imitation Policies for Low-Light Indoor Mobile Robot Navigation
 - **Authors:** Prithvi Jai Ramesh, Kaustav Chanda, Krishna Vinod, Joseph Raj Vishal, Yezhou Yang, Bharatesh Chakravarthi
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Event cameras provide high dynamic range and microsecond-level temporal resolution, making them well-suited for indoor robot navigation, where conventional RGB cameras degrade under fast motion or low-light conditions. Despite advances in event-based perception spanning detection, SLAM, and pose estimation, there remains limited research on end-to-end control policies that exploit the asynchronous nature of event streams. To address this gap, we introduce a real-world indoor person-following dataset collected using a TurtleBot 2 robot, featuring synchronized raw event streams, RGB frames, and expert control actions across multiple indoor maps, trajectories under both normal and low-light conditions. We further build a multimodal data preprocessing pipeline that temporally aligns event and RGB observations while reconstructing ground-truth actions from odometry to support high-quality imitation learning. Building on this dataset, we propose a late-fusion RGB-Event navigation policy that combines dual MobileNet encoders with a transformer-based fusion module trained via behavioral cloning. A systematic evaluation of RGB-only, Event-only, and RGB-Event fusion models across 12 training variations ranging from single-path imitation to general multi-path imitation shows that policies incorporating event data, particularly the fusion model, achieve improved robustness and lower action prediction error, especially in unseen low-light conditions where RGB-only models fail. We release the dataset, synchronization pipeline, and trained models at this https URL
### Title:
          Intelligent Control of Differential Drive Robots Subject to Unmodeled Dynamics with EKF-based State Estimation
 - **Authors:** Amos Alwala, Yuchen Hu, Gabriel da Silva Lima, Wallace Moreira Bessa
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable control and state estimation of differential drive robots (DDR) operating in dynamic and uncertain environments remains a challenge, particularly when system dynamics are partially unknown and sensor measurements are prone to degradation. This work introduces a unified control and state estimation framework that combines a Lyapunov-based nonlinear controller and Adaptive Neural Networks (ANN) with Extended Kalman Filter (EKF)-based multi-sensor fusion. The proposed controller leverages the universal approximation property of neural networks to model unknown nonlinearities in real time. An online adaptation scheme updates the weights of the radial basis function (RBF), the architecture chosen for the ANN. The learned dynamics are integrated into a feedback linearization (FBL) control law, for which theoretical guarantees of closed-loop stability and asymptotic convergence in a trajectory-tracking task are established through a Lyapunov-like stability analysis. To ensure robust state estimation, the EKF fuses inertial measurement unit (IMU) and odometry from monocular, 2D-LiDAR and wheel encoders. The fused state estimate drives the intelligent controller, ensuring consistent performance even under drift, wheel slip, sensor noise and failure. Gazebo simulations and real-world experiments are done using DDR, demonstrating the effectiveness of the approach in terms of improved velocity tracking performance with reduction in linear and angular velocity errors up to $53.91\%$ and $29.0\%$ in comparison to the baseline FBL.
### Title:
          GNIO: Gated Neural Inertial Odometry
 - **Authors:** Dapeng Feng, Yizhen Yin, Zhiqiang Chen, Yuhua Qi, Hongbo Chen
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Inertial navigation using low-cost MEMS sensors is plagued by rapid drift due to sensor noise and bias instability. While recent data-driven approaches have made significant strides, they often struggle with micro-drifts during stationarity and mode fusion during complex motion transitions due to their reliance on fixed-window regression. In this work, we introduce Gated Neural Inertial Odometry (GNIO), a novel learning-based framework that explicitly models motion validity and context. We propose two key architectural innovations: \ding{182} a learnable Motion Bank that queries a global dictionary of motion patterns to provide semantic context beyond the local receptive field, and \ding{183} a Gated Prediction Head that decomposes displacement into magnitude and direction. This gating mechanism acts as a soft, differentiable Zero-Velocity Update (ZUPT), dynamically suppressing sensor noise during stationary periods while scaling predictions during dynamic motion. Extensive experiments across four public benchmarks demonstrate that GNIO significantly reduces position drift compared to state-of-the-art CNN and Transformer-based baselines. Notably, GNIO achieves a $60.21\%$ reduction in trajectory error on the OxIOD dataset and exhibits superior generalization in challenging scenarios involving frequent stops and irregular motion speeds.
### Title:
          On the Derivation of Tightly-Coupled LiDAR-Inertial Odometry with VoxelMap
 - **Authors:** Zhihao Zhan
 - **Subjects:** Subjects:
Robotics (cs.RO); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This note presents a concise mathematical formulation of tightly-coupled LiDAR-Inertial Odometry within an iterated error-state Kalman filter framework using a VoxelMap representation. Rather than proposing a new algorithm, it provides a clear and self-contained derivation that unifies the geometric modeling and probabilistic state estimation through consistent notation and explicit formulations. The document is intended to serve both as a technical reference and as an accessible entry point for a foundational understanding of the system architecture and estimation principles.
### Title:
          Perception-Aware Autonomous Exploration in Feature-Limited Environments
 - **Authors:** Moji Shi, Rajitha de Silva, Hang Yu, Riccardo Polvara, Marija Popović
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous exploration in unknown environments typically relies on onboard state estimation for localisation and mapping. Existing exploration methods primarily maximise coverage efficiency, but often overlook that visual-inertial odometry (VIO) performance strongly depends on the availability of robust visual features. As a result, exploration policies can drive a robot into feature-sparse regions where tracking degrades, leading to odometry drift, corrupted maps, and mission failure. We propose a hierarchical perception-aware exploration framework for a stereo-equipped unmanned aerial vehicle (UAV) that explicitly couples exploration progress with feature observability. Our approach (i) associates each candidate frontier with an expected feature quality using a global feature map, and prioritises visually informative subgoals, and (ii) optimises a continuous yaw trajectory along the planned motion to maintain stable feature tracks. We evaluate our method in simulation across environments with varying texture levels and in real-world indoor experiments with largely textureless walls. Compared to baselines that ignore feature quality and/or do not optimise continuous yaw, our method maintains more reliable feature tracking, reduces odometry drift, and achieves on average 30\% higher coverage before the odometry error exceeds specified thresholds.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          WaveComm: Lightweight Communication for Collaborative Perception via Wavelet Feature Distillation
 - **Authors:** Erdemt Bao, Jin Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In multi-agent collaborative sensing systems, substantial communication overhead from information exchange significantly limits scalability and real-time performance, especially in bandwidth-constrained environments. This often results in degraded performance and reduced reliability. To address this challenge, we propose WaveComm, a wavelet-based communication framework that drastically reduces transmission loads while preserving sensing performance in low-bandwidth scenarios. The core innovation of WaveComm lies in decomposing feature maps using Discrete Wavelet Transform (DWT), transmitting only compact low-frequency components to minimize communication overhead. High-frequency details are omitted, and their effects are reconstructed at the receiver side using a lightweight generator. A Multi-Scale Distillation (MSD) Loss is employed to optimize the reconstruction quality across pixel, structural, semantic, and distributional levels. Experiments on the OPV2V and DAIR-V2X datasets for LiDAR-based and camera-based perception tasks demonstrate that WaveComm maintains state-of-the-art performance even when the communication volume is reduced to 86.3% and 87.0% of the original, respectively. Compared to existing approaches, WaveComm achieves competitive improvements in both communication efficiency and perception accuracy. Ablation studies further validate the effectiveness of its key components.
### Title:
          Improving Channel Estimation via Multimodal Diffusion Models with Flow Matching
 - **Authors:** Xiaotian Fan, Xingyu Zhou, Le Liang, Xiao Li, Shi Jin
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep generative models offer a powerful alternative to conventional channel estimation by learning complex channel distributions. By integrating the rich environmental information available in modern sensing-aided networks, this paper proposes MultiCE-Flow, a multimodal channel estimation framework based on flow matching and diffusion transformer (DiT). We design a specialized multimodal perception module that fuses LiDAR, camera, and location data into a semantic condition, while treating sparse pilots as a structural condition. These conditions guide a DiT backbone to reconstruct high-fidelity channels. Unlike standard diffusion models, we employ flow matching to learn a linear trajectory from noise to data, enabling efficient one-step sampling. By leveraging environmental semantics, our method mitigates the ill-posed nature of estimation with sparse pilots. Extensive experiments demonstrate that MultiCE-Flow consistently outperforms traditional baselines and existing generative models. Notably, it exhibits superior robustness to out-of-distribution scenarios and varying pilot densities, making it suitable for environment-aware communication systems.
### Title:
          Walking Further: Semantic-aware Multimodal Gait Recognition Under Long-Range Conditions
 - **Authors:** Zhiyang Lu, Wen Jiang, Tianren Wu, Zhichao Wang, Changwang Zhang, Siqi Shen, Ming Cheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Gait recognition is an emerging biometric technology that enables non-intrusive and hard-to-spoof human identification. However, most existing methods are confined to short-range, unimodal settings and fail to generalize to long-range and cross-distance scenarios under real-world conditions. To address this gap, we present \textbf{LRGait}, the first LiDAR-Camera multimodal benchmark designed for robust long-range gait recognition across diverse outdoor distances and environments. We further propose \textbf{EMGaitNet}, an end-to-end framework tailored for long-range multimodal gait recognition. To bridge the modality gap between RGB images and point clouds, we introduce a semantic-guided fusion pipeline. A CLIP-based Semantic Mining (SeMi) module first extracts human body-part-aware semantic cues, which are then employed to align 2D and 3D features via a Semantic-Guided Alignment (SGA) module within a unified embedding space. A Symmetric Cross-Attention Fusion (SCAF) module hierarchically integrates visual contours and 3D geometric features, and a Spatio-Temporal (ST) module captures global gait dynamics. Extensive experiments on various gait datasets validate the effectiveness of our method.
### Title:
          RegFormer++: An Efficient Large-Scale 3D LiDAR Point Registration Network with Projection-Aware 2D Transformer
 - **Authors:** Jiuming Liu, Guangming Wang, Zhe Liu, Chaokang Jiang, Haoang Li, Mengmeng Liu, Tianchen Deng, Marc Pollefeys, Michael Ying Yang, Hesheng Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Although point cloud registration has achieved remarkable advances in object-level and indoor scenes, large-scale LiDAR registration methods has been rarely explored before. Challenges mainly arise from the huge point scale, complex point distribution, and numerous outliers within outdoor LiDAR scans. In addition, most existing registration works generally adopt a two-stage paradigm: They first find correspondences by extracting discriminative local descriptors and then leverage robust estimators (e.g. RANSAC) to filter outliers, which are highly dependent on well-designed descriptors and post-processing choices. To address these problems, we propose a novel end-to-end differential transformer network, termed RegFormer++, for large-scale point cloud alignment without requiring any further post-processing. Specifically, a hierarchical projection-aware 2D transformer with linear complexity is proposed to project raw LiDAR points onto a cylindrical surface and extract global point features, which can improve resilience to outliers due to long-range dependencies. Because we fill original 3D coordinates into 2D projected positions, our designed transformer can benefit from both high efficiency in 2D processing and accuracy from 3D geometric information. Furthermore, to effectively reduce wrong point matching, a Bijective Association Transformer (BAT) is designed, combining both cross attention and all-to-all point gathering. To improve training stability and robustness, a feature-transformed optimal transport module is also designed for regressing the final pose transformation. Extensive experiments on KITTI, NuScenes, and Argoverse datasets demonstrate that our model achieves state-of-the-art performance in terms of both accuracy and efficiency.
### Title:
          In-Field 3D Wheat Head Instance Segmentation From TLS Point Clouds Using Deep Learning Without Manual Labels
 - **Authors:** Tomislav Medic, Liangliang Nan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D instance segmentation for laser scanning (LiDAR) point clouds remains a challenge in many remote sensing-related domains. Successful solutions typically rely on supervised deep learning and manual annotations, and consequently focus on objects that can be well delineated through visual inspection and manual labeling of point clouds. However, for tasks with more complex and cluttered scenes, such as in-field plant phenotyping in agriculture, such approaches are often infeasible. In this study, we tackle the task of in-field wheat head instance segmentation directly from terrestrial laser scanning (TLS) point clouds. To address the problem and circumvent the need for manual annotations, we propose a novel two-stage pipeline. To obtain the initial 3D instance proposals, the first stage uses 3D-to-2D multi-view projections, the Grounded SAM pipeline for zero-shot 2D object-centric segmentation, and multi-view label fusion. The second stage uses these initial proposals as noisy pseudo-labels to train a supervised 3D panoptic-style segmentation neural network. Our results demonstrate the feasibility of the proposed approach and show performance improvementsrelative to Wheat3DGS, a recent alternative solution for in-field wheat head instance segmentation without manual 3D annotations based on multi-view RGB images and 3D Gaussian Splatting, showcasing TLS as a competitive sensing alternative. Moreover, the results show that both stages of the proposed pipeline can deliver usable 3D instance segmentation without manual annotations, indicating promising, low-effort transferability to other comparable TLS-based point cloud segmentation tasks.
### Title:
          Expanding mmWave Datasets for Human Pose Estimation with Unlabeled Data and LiDAR Datasets
 - **Authors:** Zhuoxuan Peng, Boan Zhu, Xingjian Zhang, Wenying Li, S.-H. Gary Chan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current mmWave datasets for human pose estimation (HPE) are scarce and lack diversity in both point cloud (PC) attributes and human poses, severely hampering the generalization ability of their trained models. On the other hand, unlabeled mmWave HPE data and diverse LiDAR HPE datasets are readily available. We propose EMDUL, a novel approach to expand the volume and diversity of an existing mmWave dataset using unlabeled mmWave data and a LiDAR dataset. EMDUL trains a pseudo-label estimator to annotate the unlabeled mmWave data and is able to convert, or translate, a given annotated LiDAR PC to its mmWave counterpart. Expanded with both LiDAR-converted and pseudo-labeled mmWave PCs, our mmWave dataset significantly boosts the performance and generalization ability of all our HPE models, with substantial 15.1% and 18.9% error reductions for in-domain and out-of-domain settings, respectively.
### Title:
          Seeing Where to Deploy: Metric RGB-Based Traversability Analysis for Aerial-to-Ground Hidden Space Inspection
 - **Authors:** Seoyoung Lee, Shaekh Mohammad Shithil, Durgakant Pushp, Lantao Liu, Zhangyang Wang
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Inspection of confined infrastructure such as culverts often requires accessing hidden spaces whose entrances are reachable primarily from elevated viewpoints. Aerial-ground cooperation enables a UAV to deploy a compact UGV for interior exploration, but selecting a suitable deployment region from aerial observations requires metric terrain reasoning involving scale ambiguity, reconstruction uncertainty, and terrain semantics. We present a metric RGB-based geometric-semantic reconstruction and traversability analysis framework for aerial-to-ground hidden space inspection. A feed-forward multi-view RGB reconstruction backbone produces dense geometry, while temporally consistent semantic segmentation yields a 3D semantic map. To enable deployment-relevant measurements without LiDAR-based dense mapping, we introduce an embodied motion prior that recovers metric scale by enforcing consistency between predicted camera motion and onboard platform egomotion. From the metrically grounded reconstruction, we construct a confidence-aware geometric-semantic traversability map and evaluate candidate deployment zones under explicit reachability constraints. Experiments on a tethered UAV-UGV platform demonstrate reliable deployment-zone identification in hidden space scenarios.
### Title:
          AURORA-KITTI: Any-Weather Depth Completion and Denoising in the Wild
 - **Authors:** Yiting Wang, Tim Brödermann, Hamed Haghighi, Haonan Zhao, Christos Sakaridis, Kurt Debattista, Valentina Donzella
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust depth completion is fundamental to real-world 3D scene understanding, yet existing RGB-LiDAR fusion methods degrade significantly under adverse weather, where both camera images and LiDAR measurements suffer from weather-induced corruption. In this paper, we introduce AURORA-KITTI, the first large-scale multi-modal, multi-weather benchmark for robust depth completion in the wild. We further formulate Depth Completion and Denoising (DCD) as a unified task that jointly reconstructs a dense depth map from corrupted sparse inputs while suppressing weather-induced noise. AURORA-KITTI contains over \textit{82K} weather-consistent RGBL pairs with metric depth ground truth, spanning diverse weather types, three severity levels, day and night scenes, paired clean references, lens occlusion conditions, and textual descriptions. Moreover, we introduce DDCD, an efficient distillation-based baseline that leverages depth foundation models to inject clean structural priors into in-the-wild DCD training. DDCD achieves state-of-the-art performance on AURORA-KITTI and the real-world DENSE dataset while maintaining efficiency. Notably, our results further show that weather-aware, physically consistent data contributes more to robustness than architectural modifications alone. Data and code will be released upon publication.
### Title:
          LiDAR-EVS: Enhance Extrapolated View Synthesis for 3D Gaussian Splatting with Pseudo-LiDAR Supervision
 - **Authors:** Yiming Huang, Xin Kang, Sipeng Zhang, Hongliang Ren, Weihua Zhang, Junjie Lai
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian Splatting (3DGS) has emerged as a powerful technique for real-time LiDAR and camera synthesis in autonomous driving simulation. However, simulating LiDAR with 3DGS remains challenging for extrapolated views beyond the training trajectory, as existing methods are typically trained on single-traversal sensor scans, suffer from severe overfitting and poor generalization to novel ego-vehicle paths. To enable reliable simulation of LiDAR along unseen driving trajectories without external multi-pass data, we present LiDAR-EVS, a lightweight framework for robust extrapolated-view LiDAR simulation in autonomous driving. Designed to be plug-and-play, LiDAR-EVS readily extends to diverse LiDAR sensors and neural rendering baselines with minimal modification. Our framework comprises two key components: (1) pseudo extrapolated-view point cloud supervision with multi-frame LiDAR fusion, view transformation, occlusion curling, and intensity adjustment; (2) spatially-constrained dropout regularization that promotes robustness to diverse trajectory variations encountered in real-world driving. Extensive experiments demonstrate that LiDAR-EVS achieves SOTA performance on extrapolated-view LiDAR synthesis across three datasets, making it a promising tool for data-driven simulation, closed-loop evaluation, and synthetic data generation in autonomous driving systems.
### Title:
          RadarXFormer: Robust Object Detection via Cross-Dimension Fusion of 4D Radar Spectra and Images for Autonomous Driving
 - **Authors:** Yue Sun, Yeqiang Qian, Zhe Wang, Tianhui Li, Chunxiang Wang, Ming Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable perception is essential for autonomous driving systems to operate safely under diverse real-world traffic conditions. However, camera- and LiDAR-based perception systems suffer from performance degradation under adverse weather and lighting conditions, limiting their robustness and large-scale deployment in intelligent transportation systems. Radar-vision fusion provides a promising alternative by combining the environmental robustness and cost efficiency of millimeter-wave (mmWave) radar with the rich semantic information captured by cameras. Nevertheless, conventional 3D radar measurements lack height resolution and remain highly sparse, while emerging 4D mmWave radar introduces elevation information but also brings challenges such as signal noise and large data volume. To address these issues, this paper proposes RadarXFormer, a 3D object detection framework that enables efficient cross-modal fusion between 4D radar spectra and RGB images. Instead of relying on sparse radar point clouds, RadarXFormer directly leverages raw radar spectra and constructs an efficient 3D representation that reduces data volume while preserving complete 3D spatial information. The "X" highlights the proposed cross-dimension (3D-2D) fusion mechanism, in which multi-scale 3D spherical radar feature cubes are fused with complementary 2D image feature maps. Experiments on the K-Radar dataset demonstrate improved detection accuracy and robustness under challenging conditions while maintaining real-time inference capability.
### Title:
          Intelligent Control of Differential Drive Robots Subject to Unmodeled Dynamics with EKF-based State Estimation
 - **Authors:** Amos Alwala, Yuchen Hu, Gabriel da Silva Lima, Wallace Moreira Bessa
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable control and state estimation of differential drive robots (DDR) operating in dynamic and uncertain environments remains a challenge, particularly when system dynamics are partially unknown and sensor measurements are prone to degradation. This work introduces a unified control and state estimation framework that combines a Lyapunov-based nonlinear controller and Adaptive Neural Networks (ANN) with Extended Kalman Filter (EKF)-based multi-sensor fusion. The proposed controller leverages the universal approximation property of neural networks to model unknown nonlinearities in real time. An online adaptation scheme updates the weights of the radial basis function (RBF), the architecture chosen for the ANN. The learned dynamics are integrated into a feedback linearization (FBL) control law, for which theoretical guarantees of closed-loop stability and asymptotic convergence in a trajectory-tracking task are established through a Lyapunov-like stability analysis. To ensure robust state estimation, the EKF fuses inertial measurement unit (IMU) and odometry from monocular, 2D-LiDAR and wheel encoders. The fused state estimate drives the intelligent controller, ensuring consistent performance even under drift, wheel slip, sensor noise and failure. Gazebo simulations and real-world experiments are done using DDR, demonstrating the effectiveness of the approach in terms of improved velocity tracking performance with reduction in linear and angular velocity errors up to $53.91\%$ and $29.0\%$ in comparison to the baseline FBL.
### Title:
          Voronoi-based Second-order Descriptor with Whitened Metric in LiDAR Place Recognition
 - **Authors:** Jaein Kim, Hee Bin Yoo, Dong-Sig Han, Byoung-Tak Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The pooling layer plays a vital role in aggregating local descriptors into the metrizable global descriptor in the LiDAR Place Recognition (LPR). In particular, the second-order pooling is capable of capturing higher-order interactions among local descriptors. However, its existing methods in the LPR adhere to conventional implementations and post-normalization, and incur the descriptor unsuitable for Euclidean distancing. Based on the recent interpretation that associates NetVLAD with the second-order statistics, we propose to integrate second-order pooling with the inductive bias from Voronoi cells. Our novel pooling method aggregates local descriptors to form the second-order matrix and whitens the global descriptor to implicitly measure the Mahalanobis distance while conserving the cluster property from Voronoi cells, addressing its numerical instability during learning with diverse techniques. We demonstrate its performance gains through the experiments conducted on the Oxford Robotcar and Wild-Places benchmarks and analyze the numerical effect of the proposed whitening algorithm.
### Title:
          Context-Aware Sensor Modeling for Asynchronous Multi-Sensor Tracking in Stone Soup
 - **Authors:** Martin Vonheim Larsen, Kim Mathiassen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-sensor tracking in the real world involves asynchronous sensors with partial coverage and heterogeneous detection performance. Although probabilistic tracking methods permit detection probability and clutter intensity to depend on state and sensing context, many practical frameworks enforce globally uniform observability assumptions. Under multi-rate and partially overlapping sensing, this simplification causes repeated non-detections from high-rate sensors to erode tracks visible only to low-rate sensors, potentially degrading fusion performance. We introduce DetectorContext, an abstraction for the open-source multi-target tracking framework Stone Soup. DetectorContext exposes detection probability and clutter intensity as state-dependent functions evaluated during hypothesis formation. The abstraction integrates with existing probabilistic trackers without modifying their update equations. Experiments on asynchronous radar-lidar data demonstrate that context-aware modeling restores stable fusion and significantly improves HOTA and GOSPA performance without increasing false tracks.
### Title:
          On the Derivation of Tightly-Coupled LiDAR-Inertial Odometry with VoxelMap
 - **Authors:** Zhihao Zhan
 - **Subjects:** Subjects:
Robotics (cs.RO); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This note presents a concise mathematical formulation of tightly-coupled LiDAR-Inertial Odometry within an iterated error-state Kalman filter framework using a VoxelMap representation. Rather than proposing a new algorithm, it provides a clear and self-contained derivation that unifies the geometric modeling and probabilistic state estimation through consistent notation and explicit formulations. The document is intended to serve both as a technical reference and as an accessible entry point for a foundational understanding of the system architecture and estimation principles.
## Keyword: loop detection
### Title:
          Video Detector: A Dual-Phase Vision-Based System for Real-Time Traffic Intersection Control and Intelligent Transportation Analysis
 - **Authors:** Mustafa Fatih Şen, Halûk Gümüşkaya, Şenol Pazar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Urban traffic management increasingly requires intelligent sensing systems capable of adapting to dynamic traffic conditions without costly infrastructure modifications. Vision-based vehicle detection has therefore become a key technology for modern intelligent transportation systems. This study presents Video Detector (VD), a dual-phase vision-based traffic intersection management system designed as a flexible and cost-effective alternative to traditional inductive loop detectors. The framework integrates a real-time module (VD-RT) for intersection control with an offline analytical module (VD-Offline) for detailed traffic behavior analysis. Three system configurations were implemented using SSD Inception v2, Faster R-CNN Inception v2, and CenterNet ResNet-50 V1 FPN, trained on datasets totaling 108,000 annotated images across 6-10 vehicle classes. Experimental results show detection performance of up to 90% test accuracy and 29.5 mAP@0.5, while maintaining real-time throughput of 37 FPS on HD video streams. Field deployments conducted in collaboration with Istanbul IT and Smart City Technologies Inc. (ISBAK) demonstrate stable operation under diverse environmental conditions. The system supports virtual loop detection, vehicle counting, multi-object tracking, queue estimation, speed analysis, and multiclass vehicle classification, enabling comprehensive intersection monitoring without the need for embedded road sensors. The annotated dataset and training pipeline are publicly released to support reproducibility. These results indicate that the proposed framework provides a scalable and deployable vision-based solution for intelligent transportation systems and smart-city traffic management.
## Keyword: nerf
### Title:
          4D Synchronized Fields: Motion-Language Gaussian Splatting for Temporal Scene Understanding
 - **Authors:** Mohamed Rayan Barhdadi, Samir Abdaljalil, Rasul Khanbayov, Erchin Serpedin, Hasan Kurban
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current 4D representations decouple geometry, motion, and semantics: reconstruction methods discard interpretable motion structure; language-grounded methods attach semantics after motion is learned, blind to how objects move; and motion-aware methods encode dynamics as opaque per-point residuals without object-level organization. We propose 4D Synchronized Fields, a 4D Gaussian representation that learns object-factored motion in-loop during reconstruction and synchronizes language to the resulting kinematics through a per-object conditioned field. Each Gaussian trajectory is decomposed into shared object motion plus an implicit residual, and a kinematic-conditioned ridge map predicts temporal semantic variation, yielding a single representation in which reconstruction, motion, and semantics are structurally coupled and enabling open-vocabulary temporal queries that retrieve both objects and moments. On HyperNeRF, 4D Synchronized Fields achieves 28.52 dB mean PSNR, the highest among all language-grounded and motion-aware baselines, within 1.5 dB of reconstruction-only methods. On targeted temporal-state retrieval, the kinematic-conditioned field attains 0.884 mean accuracy, 0.815 mean vIoU, and 0.733 mean tIoU, surpassing 4D LangSplat (0.620, 0.433, and 0.439 respectively) and LangSplat (0.415, 0.304, and 0.262). Ablation confirms that kinematic conditioning is the primary driver, accounting for +0.45 tIoU over a static-embedding-only baseline. 4D Synchronized Fields is the only method that jointly exposes interpretable motion primitives and temporally grounded language fields from a single trained representation. Code will be released.
### Title:
          E2EGS: Event-to-Edge Gaussian Splatting for Pose-Free 3D Reconstruction
 - **Authors:** Yunsoo Kim, Changki Sung, Dasol Hong, Hyun Myung
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The emergence of neural radiance fields (NeRF) and 3D Gaussian splatting (3DGS) has advanced novel view synthesis (NVS). These methods, however, require high-quality RGB inputs and accurate corresponding poses, limiting robustness under real-world conditions such as fast camera motion or adverse lighting. Event cameras, which capture brightness changes at each pixel with high temporal resolution and wide dynamic range, enable precise sensing of dynamic scenes and offer a promising solution. However, existing event-based NVS methods either assume known poses or rely on depth estimation models that are bounded by their initial observations, failing to generalize as the camera traverses previously unseen regions. We present E2EGS, a pose-free framework operating solely on event streams. Our key insight is that edge information provides rich structural cues essential for accurate trajectory estimation and high-quality NVS. To extract edges from noisy event streams, we exploit the distinct spatio-temporal characteristics of edges and non-edge regions. The event camera's movement induces consistent events along edges, while non-edge regions produce sparse noise. We leverage this through a patch-based temporal coherence analysis that measures local variance to extract edges while robustly suppressing noise. The extracted edges guide structure-aware Gaussian initialization and enable edge-weighted losses throughout initialization, tracking, and bundle adjustment. Extensive experiments on both synthetic and real datasets demonstrate that E2EGS achieves superior reconstruction quality and trajectory accuracy, establishing a fully pose-free paradigm for event-based 3D reconstruction.
## Keyword: mapping
### Title:
          Your Code Agent Can Grow Alongside You with Structured Memory
 - **Authors:** Yi-Xuan Deng, Xiaoqin Liu, Yi Zhang, Guo-Wei Yang, Shuojin Yang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While "Intent-oriented programming" (or "Vibe Coding") redefines software engineering, existing code agents remain tethered to static code snapshots. Consequently, they struggle to model the critical information embedded in the temporal evolution of projects, failing to leverage the "reasoning trajectories" implicit in past successful practices. This limitation results in rigid behavioral logic and a lack of autonomous adaptability, ultimately hindering their ability to tackle complex, repository-level problems. To bridge this static-dynamic mismatch, we propose MemCoder, a framework designed to enable continual human-AI co-evolution. MemCoder first structures historical human experience to distill latent intent-to-code mappings from past commits. It then employs a self-refinement mechanism driven by verification feedback to correct agent behavior in real-time. Crucially, an experience self-internalization mechanism is introduced to crystallize human-validated solutions into long-term knowledge, thereby supporting sustained evolution. Experimental results on SWE-bench Verified demonstrate that MemCoder not only achieves State-of-the-Art (SOTA) performance but also delivers a 9.4% improvement in resolved rate over the general foundation model DeepSeek-V3.2. These findings indicate that equipping agents with the capability to co-evolve with humans via project history and real-time feedback effectively unlocks the potential of general models in complex software engineering tasks.
### Title:
          DreamReader: An Interpretability Toolkit for Text-to-Image Models
 - **Authors:** Nirmalendu Prakash, Narmeen Oozeer, Michael Lan, Luka Samkharadze, Phillip Howard, Roy Ka-Wei Lee, Dhruv Nathawani, Shivam Raval, Amirali Abdullah
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite the rapid adoption of text-to-image (T2I) diffusion models, causal and representation-level analysis remains fragmented and largely limited to isolated probing techniques. To address this gap, we introduce DreamReader: a unified framework that formalizes diffusion interpretability as composable representation operators spanning activation extraction, causal patching, structured ablations, and activation steering across modules and timesteps. DreamReader provides a model-agnostic abstraction layer enabling systematic analysis and intervention across diffusion architectures. Beyond consolidating existing methods, DreamReader introduces three novel intervention primitives for diffusion models: (1) representation fine-tuning (LoReFT) for subspace-constrained internal adaptation; (2) classifier-guided gradient steering using MLP probes trained on activations; and (3) component-level cross-model mapping for systematic study of transferability of representations across modalities. These mechanisms allows us to do lightweight white-box interventions on T2I models by drawing inspiration from interpretability techniques on LLMs. We demonstrate DreamReader through controlled experiments that (i) perform activation stitching between two models, and (ii) apply LoReFT to steer multiple activation units, reliably injecting a target concept into the generated images. Experiments are specified declaratively and executed in controlled batched pipelines to enable reproducible large-scale analysis. Across multiple case studies, we show that techniques adapted from language model interpretability yield promising and controllable interventions in diffusion models. DreamReader is released as an open source toolkit for advancing research on T2I interpretability.
### Title:
          High-Fidelity Text-to-Image Generation from Pre-Trained Vision-Language Models via Distribution-Conditioned Diffusion Decoding
 - **Authors:** Ji Woo Hong, Hee Suk Yoon, Gwanhyeong Koo, Eunseop Yoon, SooHwan Eom, Qi Dai, Chong Luo, Chang D. Yoo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent large-scale vision-language models (VLMs) have shown remarkable text-to-image generation capabilities, yet their visual fidelity remains constrained by the discrete image tokenization, which poses a major challenge. Although several studies have explored continuous representation modeling to enhance visual quality, adapting pre-trained VLM models to such representations requires large-scale data and training costs comparable to the original pre-training. To circumvent this limitation, we propose a diffusion-based decoding framework that enhances image fidelity by training only a diffusion decoder on the output image-token logits of pre-trained VLMs, thereby preserving the original model intact. At its core, Logit-to-Code Distributional Mapping converts the VLM's image-token logits into continuous, distribution-weighted code vectors with uncertainty features, providing an effective conditioning signal for diffusion decoding. A lightweight Logit Calibration aligns training-time proxy logits from the VQ-VAE encoder with VLM-generated logits, mitigating the train-inference gap. Conditioned on these representations, the Distribution-Conditioned Diffusion Decoder generates high-fidelity images. Achieved solely through short training on ImageNet-1K, our method consistently improves visual fidelity for both VQ-VAE reconstructions and text-to-image generations from VLM-predicted tokens.
### Title:
          Learning Actionable Manipulation Recovery via Counterfactual Failure Synthesis
 - **Authors:** Dayou Li, Jiuzhou Lei, Hao Wang, Lulin Liu, Yunhao Yang, Zihan Wang, Bangya Liu, Minghui Zheng, Zhiwen Fan
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While recent foundation models have significantly advanced robotic manipulation, these systems still struggle to autonomously recover from execution errors. Current failure-learning paradigms rely on either costly and unsafe real-world data collection or simulator-based perturbations, which introduce a severe sim-to-real gap. Furthermore, existing visual analyzers predominantly output coarse, binary diagnoses rather than the executable, trajectory-level corrections required for actual recovery. To bridge the gap between failure diagnosis and actionable recovery, we introduce Dream2Fix, a framework that synthesizes photorealistic, counterfactual failure rollouts directly from successful real-world demonstrations. By perturbing actions within a generative world model, Dream2Fix creates paired failure-correction data without relying on simulators. To ensure the generated data is physically viable for robot learning, we implement a structured verification mechanism that strictly filters rollouts for task validity, visual coherence, and kinematic safety. This engine produces a high-fidelity dataset of over 120k paired samples. Using this dataset, we fine-tune a vision-language model to jointly predict failure types and precise recovery trajectories, mapping visual anomalies directly to corrective actions. Extensive real-world robotic experiments show our approach achieves state-of-the-art correction accuracy, improving from 19.7% to 81.3% over prior baselines, and successfully enables zero-shot closed-loop failure recovery in physical deployments.
### Title:
          Semantic Aware Feature Extraction for Enhanced 3D Reconstruction
 - **Authors:** Ronald Nap, Andy Xiao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Feature matching is a fundamental problem in computer vision with wide-ranging applications, including simultaneous localization and mapping (SLAM), image stitching, and 3D reconstruction. While recent advances in deep learning have improved keypoint detection and description, most approaches focus primarily on geometric attributes and often neglect higher-level semantic information. This work proposes a semantic-aware feature extraction framework that employs multi-task learning to jointly train keypoint detection, keypoint description, and semantic segmentation. The method is benchmarked against standard feature matching techniques and evaluated in the context of 3D reconstruction. To enhance feature correspondence, a deep matching module is integrated. The system is tested using input from a single monocular fisheye camera mounted on a vehicle and evaluated within a multi-floor parking structure. The proposed approach supports semantic 3D reconstruction with altitude estimation, capturing elevation changes and enabling multi-level mapping. Experimental results demonstrate that the method produces semantically annotated 3D point clouds with improved structural detail and elevation information, underscoring the effectiveness of joint training with semantic cues for more consistent feature matching and enhanced 3D reconstruction.
### Title:
          Analytical Logit Scaling for High-Resolution Sea Ice Topology Retrieval from Weakly Labeled SAR Imagery
 - **Authors:** Reda Elwaradi, Julien Gimenez, Stéphane Hordoir, Mehdi Ait Hamma, Adrien Chan-Hon-Tong, Flora Weissgerber
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-resolution sea ice mapping using Synthetic Aperture Radar (SAR) is crucial for Arctic navigation and climate monitoring. However, operational ice charts provide only coarse, region-level polygons (weak labels), forcing automated segmentation models to struggle with pixel-level accuracy and often yielding under-confident, blurred concentration maps. In this paper, we propose a weakly supervised deep learning pipeline that fuses Sentinel-1 SAR and AMSR-2 radiometry data using a U-Net architecture trained with a region-based loss. To overcome the severe under-confidence caused by weak labels, we introduce an Analytical Logit Scaling method applied post-inference. By dynamically calculating the temperature and bias based on the latent space percentiles (2\% and 98\%) of each scene, we force a physical binarization of the predictions. This adaptive scaling acts as a topological extractor, successfully revealing fine-grained sea ice fractures (leads) at a 40-meter resolution without requiring any manual pixel-level annotations. Our approach not only resolves local topology but also perfectly preserves regional macroscopic concentrations, achieving a 78\% accuracy on highly fragmented summer scenes, thereby bridging the gap between weakly supervised learning and high-resolution physical segmentation.
### Title:
          State Algebra for Probabilistic Logic
 - **Authors:** Dmitry Lesnik, Tobias Schäfer
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Logic in Computer Science (cs.LO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a Probabilistic State Algebra as an extension of deterministic propositional logic, providing a computational framework for constructing Markov Random Fields (MRFs) through pure linear algebra. By mapping logical states to real-valued coordinates interpreted as energy potentials, we define an energy-based model where global probability distributions emerge from coordinate-wise Hadamard products. This approach bypasses the traditional reliance on graph-traversal algorithms and compiled circuits, utilising $t$-objects and wildcards to embed logical reduction natively within matrix operations. We demonstrate that this algebra constructs formal Gibbs distributions, offering a rigorous mathematical link between symbolic constraints and statistical inference. A central application of this framework is the development of Probabilistic Rule Models (PRMs), which are uniquely capable of incorporating both probabilistic associations and deterministic logical constraints simultaneously. These models are designed to be inherently interpretable, supporting a human-in-the-loop approach to decisioning in high-stakes environments such as healthcare and finance. By representing decision logic as a modular summation of rules within a vector space, the framework ensures that complex probabilistic systems remain auditable and maintainable without compromising the rigour of the underlying configuration space.
### Title:
          Creating manufacturable blueprints for coarse-grained virtual robots
 - **Authors:** Zihan Guo, Muhan Li, Shuzhe Zhang, Sam Kriegman
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Over the past three decades, countless embodied yet virtual agents have freely evolved inside computer simulations, but vanishingly few were realized as physical robots. This is because evolution was conducted at a level of abstraction that was convenient for freeform body generation (creation, mutation, recombination) but swept away almost all of the physical details of functional body parts. The resulting designs were crude and underdetermined, requiring considerable effort and expertise to convert into a manufacturable format. Here, we automate this mapping from simplified design spaces that are readily evolvable to complete blueprints that can be directly followed by a builder. The pipeline incrementally resolves manufacturing constraints by embedding the structural and functional semantics of motors, electronics, batteries, and wiring into the abstract virtual design. In lieu of evolution, a user-defined or AI-generated ``sketch'' of a body plan can also be fed as input to the pipeline, providing a versatile framework for accelerating the design of novel robots.
### Title:
          Orla: A Library for Serving LLM-Based Multi-Agent Systems
 - **Authors:** Rana Shahout, Hayder Tirmazi, Minlan Yu, Michael Mitzenmacher
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Orla, a library for constructing and running LLM-based agentic systems. Modern agentic applications consist of workflows that combine multiple LLM inference steps, tool calls, and heterogeneous infrastructure. Today, developers typically build these systems by manually composing orchestration code with LLM serving engines and tool execution logic. Orla provides a general abstraction that separates request execution from workflow-level policy. It acts as a serving layer above existing LLM inference engines: developers define workflows composed of stages, while Orla manages how those stages are mapped, executed, and coordinated across models and backends. It provides agent-level control through three mechanisms: a stage mapper, which assigns each stage to an appropriate model and backend; a workflow orchestrator, which schedules stages and manages their resources and context; and a memory manager, which manages inference state such as the KV cache across workflow boundaries. We demonstrate Orla with a customer support workflow that exercises many of its capabilities. We evaluate Orla on two datasets, showing that stage mapping improves latency and cost compared to a single-model vLLM baseline, while workflow-level cache management reduces time-to-first-token.
### Title:
          A Grid-Based Framework for E-Scooter Demand Representation and Temporal Input Design for Deep Learning: Evidence from Austin, Texas
 - **Authors:** Mohammad Sahnoon Merkebe Getachew Demissie, Roberto Souza
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite progress in deep learning for shared micromobility demand prediction, the systematic design and statistical validation of temporal input structures remain underexplored. Temporal features are often selected heuristically, even though historical demand strongly affects model performance and generalizability. This paper introduces a reproducible data-processing pipeline and a statistically grounded method for designing temporal input structures for image-to-image demand prediction. Using large-scale e-scooter data from Austin, Texas, we build a grid-based spatiotemporal dataset by converting trip records into hourly pickup and dropoff demand images. The pipeline includes trip filtering, mapping Census Tracts to spatial locations, grid construction, demand aggregation, and creation of a global activity mask that limits evaluation to historically active areas. This representation supports consistent spatial learning while preserving demand patterns. We then introduce a combined correlation- and error-based procedure to identify informative historical inputs. Optimal temporal depth is selected through an ablation study using a baseline UNET model with paired non-parametric tests and Holm correction. The resulting temporal structures capture short-term persistence as well as daily and weekly cycles. Compared with adjacent-hour and fixed-period baselines, the proposed design reduces mean squared error by up to 37 percent for next-hour prediction and 35 percent for next-24-hour prediction. These results highlight the value of principled dataset construction and statistically validated temporal input design for spatiotemporal micromobility demand prediction.
### Title:
          Quantum-Enhanced Vision Transformer for Flood Detection using Remote Sensing Imagery
 - **Authors:** Soumyajit Maity, Behzad Ghanbarian
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable flood detection is critical for disaster management, yet classical deep learning models often struggle with the high-dimensional, nonlinear complexities inherent in remote sensing data. To mitigate these limitations, we introduced a novel Quantum-Enhanced Vision Transformer (ViT) that synergizes the global context-awareness of transformers with the expressive feature extraction capabilities of quantum computing. Using remote sensing imagery, we developed a hybrid architecture that processes inputs through parallel pathways, a ViT backbone and a quantum branch utilizing a 4-qubit parameterized quantum circuit for localized feature mapping. These distinct representations were fused to optimize binary classification. Results showed that the proposed hybrid model significantly outperformed a classical ViT baseline, increased overall accuracy from 84.48% to 94.47% and the F1-score from 0.841 to 0.944. Notably, the quantum integration substantially improved discriminative power in complex terrains for both class. These findings validate the potential of quantum-classical hybrid models to enhance precision in hydrological monitoring and earth observation applications.
### Title:
          Evaluation of Visual Place Recognition Methods for Image Pair Retrieval in 3D Vision and Robotics
 - **Authors:** Dennis Haitz, Athradi Shritish Shetty, Michael Weinmann, Markus Ulrich
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual Place Recognition (VPR) is a core component in computer vision, typically formulated as an image retrieval task for localization, mapping, and navigation. In this work, we instead study VPR as an image pair retrieval front-end for registration pipelines, where the goal is to find top-matching image pairs between two disjoint image sets for downstream tasks such as scene registration, SLAM, and Structure-from-Motion. We comparatively evaluate state-of-the-art VPR families - NetVLAD-style baselines, classification-based global descriptors (CosPlace, EigenPlaces), feature-mixing (MixVPR), and foundation-model-driven methods (AnyLoc, SALAD, MegaLoc) - on three challenging datasets: object-centric outdoor scenes (Tanks and Temples), indoor RGB-D scans (ScanNet-GS), and autonomous-driving sequences (KITTI). We show that modern global descriptor approaches are increasingly suitable as off-the-shelf image pair retrieval modules in challenging scenarios including perceptual aliasing and incomplete sequences, while exhibiting clear, domain-dependent strengths and weaknesses that are critical when choosing VPR components for robust mapping and registration.
### Title:
          Discriminative Flow Matching Via Local Generative Predictors
 - **Authors:** Om Govind Jha, Manoj Bamniya, Ayon Borthakur
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traditional discriminative computer vision relies predominantly on static projections, mapping input features to outputs in a single computational step. Although efficient, this paradigm lacks the iterative refinement and robustness inherent in biological vision and modern generative modelling. In this paper, we propose Discriminative Flow Matching, a framework that reformulates classification and object detection as a conditional transport process. By learning a vector field that continuously transports samples from a simple noise distribution toward a task-aligned target manifold -- such as class embeddings or bounding box coordinates -- we are at the interface between generative and discriminative learning. Our method attaches multiple independent flow predictors to a shared backbone. These predictors are trained using local flow matching objectives, where gradients are computed independently for each block. We formulate this approach for standard image classification and extend it to the complex task of object detection, where targets are high-dimensional and spatially distributed. This architecture provides the flexibility to update blocks either sequentially to minimise activation memory or in parallel to suit different hardware constraints. By aggregating the predictions from these independent flow predictors, our framework enables robust, generative-inspired inference across diverse architectures, including CNNs and vision transformers.
### Title:
          H-RINS: Hierarchical Tightly-coupled Radar-Inertial Navigation via Smoothing and Mapping
 - **Authors:** Ali Alridha Abdulkarim, Mikhail Litvinov, Dzmitry Tsetserukou
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Millimeter-wave radar provides robust perception in visually degraded environments. However, radar-inertial state estimation is inherently susceptible to drift. Because radar yields only sparse, body-frame velocity measurements, it provides weak constraints on absolute orientation. Consequently, IMU biases remain poorly observable over the short time horizons typical of sliding-window filters. To address this fundamental observability challenge, we propose a tightly coupled, hierarchical radar-inertial factor graph framework. Our architecture decouples the estimation problem into a high-rate resetting graph and a persistent global graph. The resetting graph fuses IMU preintegration, radar velocities, and adaptive Zero-Velocity Updates (ZUPT) to generate the smooth, low-latency odometry required for real-time control. Concurrently, the persistent graph is a full-state factor graph maintaining the complete information of poses, velocities, and biases by fusing inertial data with keyframe-based geometric mapping and loop closures. Leveraging Incremental Smoothing and Mapping, the persistent graph can operate without explicit marginalization of variables, preserving their information while ensuring long-term bias observability. The cornerstone of our approach is a probabilistic tight-coupling mechanism: fully observable, optimized biases and their exact covariances are continuously injected from the persistent graph into the resetting graph's prior, effectively anchoring the high-rate estimator against integration drift. Extensive evaluations demonstrate our system achieves high accuracy with drift-reduced estimation at 27x real-time execution speeds. We release the implementation code and datasets upon the acceptance of the paper.
### Title:
          Fair Benchmarking of Emerging One-Step Generative Models Against Multistep Diffusion and Flow Models
 - **Authors:** Advaith Ravishankar, Serena Liu, Mingyang Wang, Todd Zhou, Jeffrey Zhou, Arnav Sharma, Ziling Hu, Léopold Das, Abdulaziz Sobirov, Faizaan Siddique, Freddy Yu, Seungjoo Baek, Yan Luo, Mengyu Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 State-of-the-art text-to-image models produce high-quality images, but inference remains expensive as generation requires several sequential ODE or denoising steps. Native one-step models aim to reduce this cost by mapping noise to an image in a single step, yet fair comparisons to multi-step systems are difficult because studies use mismatched sampling steps and different classifier-free guidance (CFG) settings, where CFG can shift FID, Inception Score, and CLIP-based alignment in opposing directions. It is also unclear how well one-step models scale to multi-step inference, and there is limited standardized out-of-distribution evaluation for label-ID-conditioned generators beyond ImageNet. To address this, We benchmark eight models spanning one-step flows (MeanFlow, Improved MeanFlow, SoFlow), multi-step baselines (RAE, Scale-RAE), and established systems (SiT, Stable Diffusion 3.5, FLUX.1) under a controlled class-conditional protocol on ImageNet validation, ImageNetV2, and reLAIONet, our new proofread out-of-distribution dataset aligned to ImageNet label IDs. Using FID, Inception Score, CLIP Score, and Pick Score, we show that FID-focused model development and CFG selection can be misleading in few-step regimes, where guidance changes can improve FID while degrading text-image alignment and human preference signals and worsening perceived quality. We further show that leading one-step models benefit from step scaling and become substantially more competitive under multi-step inference, although they still exhibit characteristic local distortions. To capture these tradeoffs, we introduce MinMax Harmonic Mean (MMHM), a composite proxy over all four metrics that stabilizes hyperparameter selection across guidance and step sweeps.
### Title:
          Tracing Your Account: A Gradient-Aware Dynamic Window Graph Framework for Ethereum under Privacy-Preserving Services
 - **Authors:** Miao Shuyi, Qiu Wangjie, Tu Xiaofan, Li Yunze, Wen Yongxin, Zheng Zhiming
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the rapid advancement of Web 3.0 technologies, public blockchain platforms are witnessing the emergence of novel services designed to enhance user privacy and anonymity. However, the powerful untraceability features inherent in these services inadvertently make them attractive tools for criminals seeking to launder illicit funds. Notably, existing de-anonymization methods face three major challenges when dealing with such transactions: highly homogenized transactional semantics, limited ability to model temporal discontinuities, and insufficient consideration of structural sparsity in account association graphs. To address these, we propose GradWATCH, designed to track anonymous accounts in Ethereum privacy-preserving services. Specifically, we first design a learnable account feature mapping module to extract informative transactional semantics from raw on-chain data. We then incorporate transaction relations into the account association graph to alleviate the adverse effects of structural sparsity. To capture temporal evolution, we further propose an edge-aware sliding-window mechanism that propagates and updates gradients at three granularities. Finally, we identify accounts controlled by the same entity by measuring their embedding distances in the learned representation space. Experimental results show that even under the conditions of unbalanced labels and sparse transactions, GradWATCH still achieves significant performance gains, with relative improvements ranging from 1.62% to 15. 22% in the MRR and from 3. 85% to 7. 31% in the F_1.
### Title:
          Gamifying Compassion: Mitigating Dialect Prejudice Through An AI-Driven Serious Game
 - **Authors:** Sicheng Lu, Erick Purwanto, Hong Liu, Aini Li, Adel Chaouch-Orozco
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dialect bias is pervasive yet often unconscious, normalized, or obscured by masking. Existing HCI interventions primarily audit disparities and propose reactive fixes. We present CompassioMate, a dialect-aware serious game that nurtures perspective-taking through AI-mediated play. Players listen to audio samples to identify regional dialects, engage in simulated social interactions involving dialect discrimination, and explore branching narratives that reveal how changes in wording or stance can influence the outcomes. In a three-week field study with 20 university students, participants reported feeling comfortable when observing region-tailored dialogues; several described experiencing perspective change. We contribute: 1) a formative study identifying goals for safe action consequence modelling, 2) the design and evaluation of a serious game integrating dialect audio, region-mapping play, bias; and 3) design implications highlighting listener-side training, transparent evaluation, and narratives maintaining psychological well-being.
### Title:
          Windowed Fourier Propagator: A Frequency-Local Neural Operator for Wave Equations in Inhomogeneous Media
 - **Authors:** Yiyang Cai, Zixuan Qiu, Yunlu Shu, Jiamao Wu, Yingzhou Li, Tianyu Wang, Xi Chen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Wave equations are fundamental to describing a vast array of physical phenomena, yet their simulation in inhomogeneous media poses a computational challenge due to the highly oscillatory nature of the solutions. To overcome the high costs of traditional solvers, we propose the Windowed Fourier Propagator (WFP), a novel neural operator that efficiently learns the solution operator. The WFP's design is rooted in the physical principle of frequency locality, where wave energy scatters primarily to adjacent frequencies. By learning a set of compact, localized propagators, each mapping an input frequency to a small window of outputs, our method avoids the complexity of dense interaction models and achieves computational efficiency. Another key feature is the explicit preservation of superposition, which enables remarkable generalization from simple training data (e.g., plane waves) to arbitrary, complex wave states. We demonstrate that the WFP provides an explainable, efficient and accurate framework for data-driven wave modeling in complex media.
### Title:
          A Physically-Grounded Attack and Adaptive Defense Framework for Real-World Low-Light Image Enhancement
 - **Authors:** Tongshun Zhang, Pingping Liu, Yuqing Lei, Zixuan Zhong, Qiuzhan Zhou, Zhiyuan Zha
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Limited illumination often causes severe physical noise and detail degradation in images. Existing Low-Light Image Enhancement (LLIE) methods frequently treat the enhancement process as a blind black-box mapping, overlooking the physical noise transformation during imaging, leading to suboptimal performance. To address this, we propose a novel LLIE approach, conceptually formulated as a physics-based attack and display-adaptive defense paradigm. Specifically, on the attack side, we establish a physics-based Degradation Synthesis (PDS) pipeline. Unlike standard data augmentation, PDS explicitly models Image Signal Processor (ISP) inversion to the RAW domain, injects physically plausible photon and read noise, and re-projects the data to the sRGB domain. This generates high-fidelity training pairs with explicitly parameterized degradation vectors, effectively simulating realistic attacks on clean signals. On the defense side, we construct a dual-layer fortified system. A noise predictor estimates degradation parameters from the input sRGB image. These estimates guide a degradation-aware Mixture of Experts (DA-MoE), which dynamically routes features to experts specialized in handling specific noise intensities. Furthermore, we introduce an Adaptive Metric Defense (AMD) mechanism, dynamically calibrating the feature embedding space based on noise severity, ensuring robust representation learning under severe degradation. Extensive experiments demonstrate that our approach offers significant plug-and-play performance enhancement for existing benchmark LLIE methods, effectively suppressing real-world noise while preserving structural fidelity. The sourced code is available at this https URL.
### Title:
          Structure-Dependent Regret and Constraint Violation Bounds for Online Convex Optimization with Time-Varying Constraints
 - **Authors:** Xiufeng Liu, Qian Chen, Zhijin Wang, Ruyu Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Online convex optimization (OCO) with time-varying constraints is a critical framework for sequential decision-making in dynamic networked systems, where learners must minimize cumulative loss while satisfying regions of feasibility that shift across rounds. Existing theoretical analyses typically treat constraint variation as a monolithic adversarial process, resulting in joint regret and violation bounds that are overly conservative for real-world network dynamics. In this paper, we introduce a structured characterization of constraint variation - smooth drift, periodic cycles, and sparse switching - mapping these classes to common network phenomena such as slow channel fading, diurnal traffic patterns, and discrete maintenance windows. We derive structure-dependent joint bounds that strictly improve upon adversarial rates when the constraint process exhibits regularity. To realize these gains, we propose the Structure-Adaptive Primal-Dual (SA-PD) algorithm, which utilizes observable constraint signals to detect environmental structure online and adapt dual update strategies accordingly. Extensive experiments on synthetic benchmarks and real-world datasets - including online electricity scheduling and transformer load management - demonstrate that SA-PD reduces cumulative constraint violation by up to 53% relative to structure-agnostic baselines while maintaining competitive utility. This work serves as a comprehensive guide for exploiting temporal regularity in constrained online learning for robust network engineering.
### Title:
          AerialVLA: A Vision-Language-Action Model for UAV Navigation via Minimalist End-to-End Control
 - **Authors:** Peng Xu, Zhengnan Deng, Jiayan Deng, Zonghua Gu, Shaohua Wan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language Navigation (VLN) for Unmanned Aerial Vehicles (UAVs) demands complex visual interpretation and continuous control in dynamic 3D environments. Existing hierarchical approaches rely on dense oracle guidance or auxiliary object detectors, creating semantic gaps and limiting genuine autonomy. We propose AerialVLA, a minimalist end-to-end Vision-Language-Action framework mapping raw visual observations and fuzzy linguistic instructions directly to continuous physical control signals. First, we introduce a streamlined dual-view perception strategy that reduces visual redundancy while preserving essential cues for forward navigation and precise grounding, which additionally facilitates future simulation-to-reality transfer. To reclaim genuine autonomy, we deploy a fuzzy directional prompting mechanism derived solely from onboard sensors, completely eliminating the dependency on dense oracle guidance. Ultimately, we formulate a unified control space that integrates continuous 3-Degree-of-Freedom (3-DoF) kinematic commands with an intrinsic landing signal, freeing the agent from external object detectors for precision landing. Extensive experiments on the TravelUAV benchmark demonstrate that AerialVLA achieves state-of-the-art performance in seen environments. Furthermore, it exhibits superior generalization in unseen scenarios by achieving nearly three times the success rate of leading baselines, validating that a minimalist, autonomy-centric paradigm captures more robust visual-motor representations than complex modular systems.
### Title:
          Towards Versatile Opti-Acoustic Sensor Fusion and Volumetric Mapping
 - **Authors:** Ivana Collado-Gonzalez, John McConnell, Brendan Englot
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate 3D volumetric mapping is critical for autonomous underwater vehicles operating in obstacle-rich environments. Vision-based perception provides high-resolution data but fails in turbid conditions, while sonar is robust to lighting and turbidity but suffers from low resolution and elevation ambiguity. This paper presents a volumetric mapping framework that fuses a stereo sonar pair with a monocular camera to enable safe navigation under varying visibility conditions. Overlapping sonar fields of view resolve elevation ambiguity, producing fully defined 3D point clouds at each time step. The framework identifies regions of interest in camera images, associates them with corresponding sonar returns, and combines sonar range with camera-derived elevation cues to generate additional 3D points. Each 3D point is assigned a confidence value reflecting its reliability. These confidence-weighted points are fused using a Gaussian Process Volumetric Mapping framework that prioritizes the most reliable measurements. Experimental comparisons with other opti-acoustic and sonar-based approaches, along with field tests in a marina environment, demonstrate the method's effectiveness in capturing complex geometries and preserving critical information for robot navigation in both clear and turbid conditions. Our code is open-source to support community adoption.
### Title:
          Distilling Latent Manifolds: Resolution Extrapolation by Variational Autoencoders
 - **Authors:** Jiaming Chu, Tao Wang, Lei Jin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Variational Autoencoder (VAE) encoders play a critical role in modern generative models, yet their computational cost often motivates the use of knowledge distillation or quantification to obtain compact alternatives. Existing studies typically believe that the model work better on the samples closed to their training data distribution than unseen data distribution. In this work, we report a counter-intuitive phenomenon in VAE encoder distillation: a compact encoder distilled only at low resolutions exhibits poor reconstruction performance at its native resolution, but achieves dramatically improved results when evaluated at higher, unseen input resolutions. Despite never being trained beyond $256^2$ resolution, the distilled encoder generalizes effectively to $512^2$ resolution inputs, partially inheriting the teacher model's resolution this http URL further analyze latent distributions across resolutions and find that higher-resolution inputs produce latent representations more closely aligned with the teacher's manifold. Through extensive experiments on ImageNet-256, we show that simple resolution remapping-upsampling inputs before encoding and downsampling reconstructions for evaluation-leads to substantial gains across PSNR, MSE, SSIM, LPIPS, and rFID metrics. These findings suggest that VAE encoder distillation learns resolution-consistent latent manifolds rather than resolution-specific pixel mappings. This also means that the high training cost on memory, time and high-resolution datasets are not necessary conditions for distilling a VAE with high-resolution image reconstruction capabilities. On low resolution datasets, the distillation model still could learn the detailed knowledge of the teacher model in high-resolution image reconstruction.
### Title:
          Make it SING: Analyzing Semantic Invariants in Classifiers
 - **Authors:** Harel Yadid, Meir Yossef Levi, Roy Betser, Guy Gilboa
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 All classifiers, including state-of-the-art vision models, possess invariants, partially rooted in the geometry of their linear mappings. These invariants, which reside in the null-space of the classifier, induce equivalent sets of inputs that map to identical outputs. The semantic content of these invariants remains vague, as existing approaches struggle to provide human-interpretable information. To address this gap, we present Semantic Interpretation of the Null-space Geometry (SING), a method that constructs equivalent images, with respect to the network, and assigns semantic interpretations to the available variations. We use a mapping from network features to multi-modal vision language models. This allows us to obtain natural language descriptions and visual examples of the induced semantic shifts. SING can be applied to a single image, uncovering local invariants, or to sets of images, allowing a breadth of statistical analysis at the class and model levels. For example, our method reveals that ResNet50 leaks relevant semantic attributes to the null space, whereas DinoViT, a ViT pretrained with self-supervised DINO, is superior in maintaining class semantics across the invariant space.
### Title:
          Seeing Where to Deploy: Metric RGB-Based Traversability Analysis for Aerial-to-Ground Hidden Space Inspection
 - **Authors:** Seoyoung Lee, Shaekh Mohammad Shithil, Durgakant Pushp, Lantao Liu, Zhangyang Wang
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Inspection of confined infrastructure such as culverts often requires accessing hidden spaces whose entrances are reachable primarily from elevated viewpoints. Aerial-ground cooperation enables a UAV to deploy a compact UGV for interior exploration, but selecting a suitable deployment region from aerial observations requires metric terrain reasoning involving scale ambiguity, reconstruction uncertainty, and terrain semantics. We present a metric RGB-based geometric-semantic reconstruction and traversability analysis framework for aerial-to-ground hidden space inspection. A feed-forward multi-view RGB reconstruction backbone produces dense geometry, while temporally consistent semantic segmentation yields a 3D semantic map. To enable deployment-relevant measurements without LiDAR-based dense mapping, we introduce an embodied motion prior that recovers metric scale by enforcing consistency between predicted camera motion and onboard platform egomotion. From the metrically grounded reconstruction, we construct a confidence-aware geometric-semantic traversability map and evaluate candidate deployment zones under explicit reachability constraints. Experiments on a tethered UAV-UGV platform demonstrate reliable deployment-zone identification in hidden space scenarios.
### Title:
          Edge element DtN method for electromagnetic scattering poles of perfectly conducting obstacles
 - **Authors:** Bo Gong, Takumi Sato, Jiguang Sun, Xinming Wu
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Meromorphic continuation of the scattering operator leads to scattering poles (resonances) in the complex plane. Despite their significance, numerical investigation of scattering poles remains limited. In this paper, we propose and analyze a numerical method to compute electromagnetic poles of perfectly conducting obstacles. The unbounded domain for the scattering problem is truncated using the DtN mapping and the poles are shown to be the eigenvalues of a holomorphic Fredholm operator function related to Maxwell's equations. Edge elements are used for discretization. The convergence is proved using the abstract approximation theory for eigenvalue problems of holomorphic Fredholm operator functions. The proposed finite element DtN approach is free of non-physical poles. A spectral indicator method is then employed to compute the resulting nonlinear matrix eigenvalue problem. Numerical examples are presented to demonstrate the effectiveness of the method.
### Title:
          Learning Constituent Headedness
 - **Authors:** Zeyao Qi, Yige Chen, KyungTae Lim, Haihua Pan, Jungyeul Park
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Headedness is widely used as an organizing device in syntactic analysis, yet constituency treebanks rarely encode it explicitly and most processing pipelines recover it procedurally via percolation rules. We treat this notion of constituent headedness as an explicit representational layer and learn it as a supervised prediction task over aligned constituency and dependency annotations, inducing supervision by defining each constituent head as the dependency span head. On aligned English and Chinese data, the resulting models achieve near-ceiling intrinsic accuracy and substantially outperform Collins-style rule-based percolation. Predicted heads yield comparable parsing accuracy under head-driven binarization, consistent with the induced binary training targets being largely equivalent across head choices, while increasing the fidelity of deterministic constituency-to-dependency conversion and transferring across resources and languages under simple label-mapping interfaces.
### Title:
          LaPro-DTA: Latent Dual-View Drug Representations and Salient Protein Feature Extraction for Generalizable Drug--Target Affinity Prediction
 - **Authors:** Zihan Dun, Liuyi Xu, An-Yang Lu, Shuang Li, Yining Qian
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Drug--target affinity prediction is pivotal for accelerating drug discovery, yet existing methods suffer from significant performance degradation in realistic cold-start scenarios (unseen drugs/targets/pairs), primarily driven by overfitting to training instances and information loss from irrelevant target sequences. In this paper, we propose LaPro-DTA, a framework designed to achieve robust and generalizable DTA prediction. To tackle overfitting, we devise a latent dual-view drug representation mechanism. It synergizes an instance-level view to capture fine-grained substructures with stochastic perturbation and a distribution-level view to distill generalized chemical scaffolds via semantic remapping, thereby enforcing the model to learn transferable structural rules rather than memorizing specific samples. To mitigate information loss, we introduce a salient protein feature extraction strategy using pattern-aware top-$k$ pooling, which effectively filters background noise and isolates high-response bioactive regions. Furthermore, a cross-view multi-head attention mechanism fuses these purified features to model comprehensive interactions. Extensive experiments on benchmark datasets demonstrate that LaPro-DTA significantly outperforms state-of-the-art methods, achieving an 8\% MSE reduction on the Davis dataset in the challenging unseen-drug setting, while offering interpretable insights into binding mechanisms.
### Title:
          BiTro: Bidirectional Transfer Learning Enhances Bulk and Spatial Transcriptomics Prediction in Cancer Pathological Images
 - **Authors:** Jingkun Yu, Guangkai Shang, Changtao Li, Xun Gong, Tianrui Li, Yazhou He, Zhipeng Luo
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cancer pathological analysis requires modeling tumor heterogeneity across multiple modalities, primarily through transcriptomics and whole slide imaging (WSI), along with their spatial relations. On one hand, bulk transcriptomics and WSI images are largely available but lack spatial mapping; on the other hand, spatial transcriptomics (ST) data can offer high spatial resolution, yet facing challenges of high cost, low sequencing depth, and limited sample sizes. Therefore, the data foundation of either side is flawed and has its limit in accurately finding the mapping between the two modalities. To this end, we propose BiTro, a bidirectional transfer learning framework that can enhance bulk and spatial transcriptomics prediction from pathological images. Our contributions are twofold. First, we design a universal and transferable model architecture that works for both bulk+WSI and ST data. A major highlight is that we model WSI images on the cellular level to better capture cells' visual features, morphological phenotypes, and their spatial relations; to map cells' features to their transcriptomics measured in bulk or ST, we adopt multiple instance learning. Second, by using LoRA, our model can be efficiently transferred between bulk and ST data to exploit their complementary information. To test our framework, we conducted comprehensive experiments on five cancer datasets. Results demonstrate that 1) our base model can achieve better or competitive performance compared to existing models on bulk or spatial transcriptomics prediction, and 2) transfer learning can further improve the base model's performance.
### Title:
          Fine-tuning RoBERTa for CVE-to-CWE Classification: A 125M Parameter Model Competitive with LLMs
 - **Authors:** Nikita Mosievskiy
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a fine-tuned RoBERTa-base classifier (125M parameters) for mapping Common Vulnerabilities and Exposures (CVE) descriptions to Common Weakness Enumeration (CWE) categories. We construct a large-scale training dataset of 234,770 CVE descriptions with AI-refined CWE labels using Claude Sonnet 4.6, and agreement-filtered evaluation sets where NVD and AI labels agree. On our held-out test set (27,780 samples, 205 CWE classes), the model achieves 87.4% top-1 accuracy and 60.7% Macro F1 -- a +15.5 percentage-point Macro F1 gain over a TF-IDF baseline that already reaches 84.9% top-1, demonstrating the model's advantage on rare weakness categories. On the external CTI-Bench benchmark (NeurIPS 2024), the model achieves 75.6% strict accuracy (95% CI: 72.8-78.2%) -- statistically indistinguishable from Cisco Foundation-Sec-8B-Reasoning (75.3%, 8B parameters) at 64x fewer parameters. We release the dataset, model, and training code.
### Title:
          Thermal Image Refinement with Depth Estimation using Recurrent Networks for Monocular ORB-SLAM3
 - **Authors:** Hürkan Şahin, Huy Xuan Pham, Van Huyen Dang, Alper Yegenoglu, Erdal Kayacan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous navigation in GPS-denied and visually degraded environments remains challenging for unmanned aerial vehicles (UAVs). To this end, we investigate the use of a monocular thermal camera as a standalone sensor on a UAV platform for real-time depth estimation and simultaneous localization and mapping (SLAM). To extract depth information from thermal images, we propose a novel pipeline employing a lightweight supervised network with recurrent blocks (RBs) integrated to capture temporal dependencies, enabling more robust predictions. The network combines lightweight convolutional backbones with a thermal refinement network (T-RefNet) to refine raw thermal inputs and enhance feature visibility. The refined thermal images and predicted depth maps are integrated into ORB-SLAM3, enabling thermal-only localization. Unlike previous methods, the network is trained on a custom non-radiometric dataset, obviating the need for high-cost radiometric thermal cameras. Experimental results on datasets and UAV flights demonstrate competitive depth accuracy and robust SLAM performance under low-light conditions. On the radiometric VIVID++ (indoor-dark) dataset, our method achieves an absolute relative error of approximately 0.06, compared to baselines exceeding 0.11. In our non-radiometric indoor set, baseline errors remain above 0.24, whereas our approach remains below 0.10. Thermal-only ORB-SLAM3 maintains a mean trajectory error under 0.4 m.
### Title:
          Gaussian mixture models for model improvement
 - **Authors:** Paolo Villani, Daniel Andrés Arcones, Jörg F. Unger, Martin Weiser
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modeling complex physical systems such as they arise in civil engineering applications requires finding a trade-off between physical fidelity and practicality. Consequently, deviations of simulation from measurements are ubiquitous even after model calibration due to the model discrepancy, which may result from deliberate modeling decisions, ignorance, or lack of this http URL the mismatch between simulation and measurements are deemed unacceptable, the model has to be improved. Targeted model improvement is challenging due to a non-local impact of model discrepancies on measurements and the dependence on sensor configurations. Many approaches to model improvement, such as Bayesian calibration with additive mismatch terms, gray-box models, symbolic regression, or stochastic model updating, often lack interpretability, generalizability, physical consistency, or practical applicability. This paper introduces a non-intrusive approach to model discrepancy analysis using mixture models. Instead of directly modifying the model structure, the method maps sensor readings to clusters of physically meaningful parameters, automatically assigning sensor readings to parameter vector clusters. This mapping can reveal systematic discrepancies and model biases, guiding targeted, physics-based refinements by the modeler. The approach is formulated within a Bayesian framework, enabling the identification of parameter clusters and their assignments via the Expectation-Maximization (EM) algorithm. The methodology is demonstrated through numerical experiments, including an illustrative example and a real-world case study of heat transfer in a concrete bridge.
### Title:
          PAKAN: Pixel Adaptive Kolmogorov-Arnold Network Modules for Pansharpening
 - **Authors:** Haoyu Zhang, Haojing Chen, Zhen Zhong, Liangjian Deng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pansharpening aims to fuse high-resolution spatial details from panchromatic images with the rich spectral information of multispectral images. Existing deep neural networks for this task typically rely on static activation functions, which limit their ability to dynamically model the complex, non-linear mappings required for optimal spatial-spectral fusion. While the recently introduced Kolmogorov-Arnold Network (KAN) utilizes learnable activation functions, traditional KANs lack dynamic adaptability during inference. To address this limitation, we propose a Pixel Adaptive Kolmogorov-Arnold Network framework. Starting from KAN, we design two adaptive variants: a 2D Adaptive KAN that generates spline summation weights across spatial dimensions and a 1D Adaptive KAN that generates them across spectral channels. These two components are then assembled into PAKAN 2to1 for feature fusion and PAKAN 1to1 for feature refinement. Extensive experiments demonstrate that our proposed modules significantly enhance network performance, proving the effectiveness and superiority of pixel-adaptive activation in pansharpening tasks.
### Title:
          Point-Identification of a Robust Predictor Under Latent Shift with Imperfect Proxies
 - **Authors:** Zahra Rahiminasab, Reza Soumi, Arto Klami, Samuel Kaski
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Addressing the domain adaptation problem becomes more challenging when distribution shifts across domains stem from latent confounders that affect both covariates and outcomes. Existing proxy-based approaches that address latent shift rely on a strong completeness assumption to uniquely determine (point-identify) a robust predictor. Completeness requires that proxies have sufficient information about variations in latent confounders. For imperfect proxies the mapping from confounders to the space of proxy distributions is non-injective, and multiple latent confounder values can generate the same proxy distribution. This breaks the completeness assumption and observed data are consistent with multiple potential predictors (set-identified). To address this, we introduce latent equivalent classes (LECs). LECs are defined as groups of latent confounders that induce the same conditional proxy distribution. We show that point-identification for the robust predictor remains achievable as long as multiple domains differ sufficiently in how they mix proxy-induced LECs to form the robust predictor. This domain diversity condition is formalized as a cross-domain rank condition on the mixture weights, which is substantially weaker assumption than completeness. We introduce the Proximal Quasi-Bayesian Active learning (PQAL) framework, which actively queries a minimal set of diverse domains that satisfy this rank condition. PQAL can efficiently recover the point-identified predictor, demonstrates robustness to varying degrees of shift and outperforms previous methods on synthetic data and semi-synthetic dSprites dataset.
### Title:
          Token Coherence: Adapting MESI Cache Protocols to Minimize Synchronization Overhead in Multi-Agent LLM Systems
 - **Authors:** Vladyslav Parakhin
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-agent LLM orchestration incurs synchronization costs scaling as O(n x S x |D|) in agents, steps, and artifact size under naive broadcast -- a regime I term broadcast-induced triply-multiplicative overhead. I argue this pathology is a structural residue of full-state rebroadcast, not an inherent property of multi-agent coordination. The central claim: synchronization cost explosion in LLM multi-agent systems maps with formal precision onto the cache coherence problem in shared-memory multiprocessors, and MESI-protocol invalidation transfers to artifact synchronization under minimal structural modification. I construct the Artifact Coherence System (ACS) and prove the Token Coherence Theorem: lazy invalidation attenuates cost by at least S/(n + W(d_i)) when S > n + W(d_i), converting O(n x S x |D|) to O((n + W) x |D|). A TLA+-verified protocol enforces single-writer safety, monotonic versioning, and bounded staleness across ~2,400 explored states. Simulation across four workload configurations yields token savings of 95.0% +/- 1.3% at V=0.05, 92.3% +/- 1.4% at V=0.10, 88.3% +/- 1.5% at V=0.25, and 84.2% +/- 1.3% at V=0.50 -- each exceeding the theorem's conservative lower bounds. Savings of ~81% persist at V=0.9, contrary to the predicted collapse threshold. Contributions: (1) formal MESI-to-artifact state mapping; (2) Token Coherence Theorem as savings lower bound; (3) TLA+-verified protocol with three proven invariants; (4) characterization of conditional artifact access semantics resolving the always-read objection; (5) reference Python implementation integrating with LangGraph, CrewAI, and AutoGen via thin adapter layers.
### Title:
          SliceMapper: Intelligent Mapping of O-CU and O-DU onto O-Cloud Sites in 6G O-RAN
 - **Authors:** Mohammad Asif Habibi, Xavier Costa-Pérez, Hans D. Schotten
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we propose an rApp, named SliceMapper, to optimize the mapping process of the open centralized unit (O-CU) and open distributed unit (O-DU) of an open radio access network (O-RAN) slice subnet onto the underlying open cloud (O-Cloud) sites in sixth-generation (6G) O-RAN. To accomplish this, we first design a system model for SliceMapper and introduce its mathematical framework. Next, we formulate the mapping process addressed by SliceMapper as a sequential decision-making optimization problem. To solve this problem, we implement both on-policy and off-policy variants of the Q-learning algorithm, employing tabular representation as well as function approximation methods for each variant. To evaluate the effectiveness of these approaches, we conduct a series of simulations under various scenarios. We proceed further by performing a comparative analysis of all four variants. The results demonstrate that the on-policy function approximation method outperforms the alternative approaches in terms of stability and lower standard deviation across all random seeds. However, the on-policy and off-policy tabular representation methods achieve higher average rewards, with values of 5.42 and 5.12, respectively. Finally, we conclude the paper and introduce several directions for future research.
### Title:
          Fusian: Multi-LoRA Fusion for Fine-Grained Continuous MBTI Personality Control in Large Language Models
 - **Authors:** Zehao Chen, Rong Pan
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) have demonstrated impressive capabilities in simulating diverse human behaviors and personalities. However, existing methods for personality control, which include prompt engineering and standard Supervised Fine-Tuning (SFT), typically treat personality traits as discrete categories (e.g., "Extroverted" vs. "Introverted"), lacking the ability to precisely control the intensity of a trait on a continuous spectrum. In this paper, we introduce Fusian, a novel framework for fine-grained, continuous personality control in LLMs. Fusian operates in two stages: (1) Trajectory Collection, where we capture the dynamic evolution of personality adoption during SFT by saving a sequence of LoRA adapters, effectively mapping the continuous manifold of a trait; and (2) RL-based Dynamic Fusion, where we train a policy network using Reinforcement Learning to dynamically compute mixing weights for these frozen adapters. By sampling from a Dirichlet distribution parameterized by the policy network, Fusian fuses multiple adapters to align the model's output with a specific numerical target intensity. Experiments on the Qwen3-14B model demonstrate that Fusian achieves high precision in personality control, significantly outperforming baseline methods in aligning with user-specified trait intensities.
### Title:
          Anatomy of a Lie: A Multi-Stage Diagnostic Framework for Tracing Hallucinations in Vision-Language Models
 - **Authors:** Lexiang Xiong, Qi Li, Jingwen Ye, Xinchao Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language Models (VLMs) frequently "hallucinate" - generate plausible yet factually incorrect statements - posing a critical barrier to their trustworthy deployment. In this work, we propose a new paradigm for diagnosing hallucinations, recasting them from static output errors into dynamic pathologies of a model's computational cognition. Our framework is grounded in a normative principle of computational rationality, allowing us to model a VLM's generation as a dynamic cognitive trajectory. We design a suite of information-theoretic probes that project this trajectory onto an interpretable, low-dimensional Cognitive State Space. Our central discovery is a governing principle we term the geometric-information duality: a cognitive trajectory's geometric abnormality within this space is fundamentally equivalent to its high information-theoretic surprisal. Hallucination detection is counts as a geometric anomaly detection problem. Evaluated across diverse settings - from rigorous binary QA (POPE) and comprehensive reasoning (MME) to unconstrained open-ended captioning (MS-COCO) - our framework achieves state-of-the-art performance. Crucially, it operates with high efficiency under weak supervision and remains highly robust even when calibration data is heavily contaminated. This approach enables a causal attribution of failures, mapping observable errors to distinct pathological states: perceptual instability (measured by Perceptual Entropy), logical-causal failure (measured by Inferential Conflict), and decisional ambiguity (measured by Decision Entropy). Ultimately, this opens a path toward building AI systems whose reasoning is transparent, auditable, and diagnosable by design.
### Title:
          Fast SAM 3D Body: Accelerating SAM 3D Body for Real-Time Full-Body Human Mesh Recovery
 - **Authors:** Timing Yang, Sicheng He, Hongyi Jing, Jiawei Yang, Zhijian Liu, Chuhang Zou, Yue Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 SAM 3D Body (3DB) achieves state-of-the-art accuracy in monocular 3D human mesh recovery, yet its inference latency of several seconds per image precludes real-time application. We present Fast SAM 3D Body, a training-free acceleration framework that reformulates the 3DB inference pathway to achieve interactive rates. By decoupling serial spatial dependencies and applying architecture-aware pruning, we enable parallelized multi-crop feature extraction and streamlined transformer decoding. Moreover, to extract the joint-level kinematics (SMPL) compatible with existing humanoid control and policy learning frameworks, we replace the iterative mesh fitting with a direct feedforward mapping, accelerating this specific conversion by over 10,000x. Overall, our framework delivers up to a 10.9x end-to-end speedup while maintaining on-par reconstruction fidelity, even surpassing 3DB on benchmarks such as LSPET. We demonstrate its utility by deploying Fast SAM 3D Body in a vision-only teleoperation system that-unlike methods reliant on wearable IMUs-enables real-time humanoid control and the direct collection of manipulation policies from a single RGB stream.
### Title:
          Perception-Aware Autonomous Exploration in Feature-Limited Environments
 - **Authors:** Moji Shi, Rajitha de Silva, Hang Yu, Riccardo Polvara, Marija Popović
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous exploration in unknown environments typically relies on onboard state estimation for localisation and mapping. Existing exploration methods primarily maximise coverage efficiency, but often overlook that visual-inertial odometry (VIO) performance strongly depends on the availability of robust visual features. As a result, exploration policies can drive a robot into feature-sparse regions where tracking degrades, leading to odometry drift, corrupted maps, and mission failure. We propose a hierarchical perception-aware exploration framework for a stereo-equipped unmanned aerial vehicle (UAV) that explicitly couples exploration progress with feature observability. Our approach (i) associates each candidate frontier with an expected feature quality using a global feature map, and prioritises visually informative subgoals, and (ii) optimises a continuous yaw trajectory along the planned motion to maintain stable feature tracks. We evaluate our method in simulation across environments with varying texture levels and in real-world indoor experiments with largely textureless walls. Compared to baselines that ignore feature quality and/or do not optimise continuous yaw, our method maintains more reliable feature tracking, reduces odometry drift, and achieves on average 30\% higher coverage before the odometry error exceeds specified thresholds.
## Keyword: localization
### Title:
          Steering at the Source: Style Modulation Heads for Robust Persona Control
 - **Authors:** Yoshihiro Izawa, Gouki Minegishi, Koshi Eguchi, Sosuke Hosokawa, Kenjiro Taura
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Activation steering offers a computationally efficient mechanism for controlling Large Language Models (LLMs) without fine-tuning. While effectively controlling target traits (e.g., persona), coherency degradation remains a major obstacle to safety and practical deployment. We hypothesize that this degradation stems from intervening on the residual stream, which indiscriminately affects aggregated features and inadvertently amplifies off-target noise. In this work, we identify a sparse subset of attention heads (only three heads) that independently govern persona and style formation, which we term Style Modulation Heads. Specifically, these heads can be localized via geometric analysis of internal representations, combining layer-wise cosine similarity and head-wise contribution scores. We demonstrate that intervention targeting only these specific heads achieves robust behavioral control while significantly mitigating the coherency degradation observed in residual stream steering. More broadly, our findings show that precise, component-level localization enables safer and more precise model control.
### Title:
          SAIF: A Stability-Aware Inference Framework for Medical Image Segmentation with Segment Anything Model
 - **Authors:** Ke Wu, Shiqi Chen, Yiheng Zhong, Hengxian Liu, Yingxue Su, Yifang Wang, Junhao Jin, Guangyu Ren
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Segment Anything Model (SAM) enable scalable medical image segmentation but suffer from inference-time instability when deployed as a frozen backbone. In practice, bounding-box prompts often contain localization errors, and fixed threshold binarization introduces additional decision uncertainty. These factors jointly cause high prediction variance, especially near object boundaries, degrading reliability. We propose the Stability-Aware Inference Framework (SAIF), a training-free and plug-and-play inference framework that improves robustness by explicitly modeling prompt and threshold uncertainty. SAIF constructs a joint uncertainty space via structured box perturbations and threshold variations, evaluates each hypothesis using decision stability and boundary consistency, and introduces a stability-consistency score to filter unstable candidates and perform stability-weighted fusion in probability space. Experiments on Synapse, CVC-ClinicDB, Kvasir-SEG, and CVC-300 demonstrate that SAIF consistently improves segmentation accuracy and robustness, achieving state-of-the-art performance without retraining or architectural modification. Our anonymous code is released at this https URL.
### Title:
          Semantic Aware Feature Extraction for Enhanced 3D Reconstruction
 - **Authors:** Ronald Nap, Andy Xiao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Feature matching is a fundamental problem in computer vision with wide-ranging applications, including simultaneous localization and mapping (SLAM), image stitching, and 3D reconstruction. While recent advances in deep learning have improved keypoint detection and description, most approaches focus primarily on geometric attributes and often neglect higher-level semantic information. This work proposes a semantic-aware feature extraction framework that employs multi-task learning to jointly train keypoint detection, keypoint description, and semantic segmentation. The method is benchmarked against standard feature matching techniques and evaluated in the context of 3D reconstruction. To enhance feature correspondence, a deep matching module is integrated. The system is tested using input from a single monocular fisheye camera mounted on a vehicle and evaluated within a multi-floor parking structure. The proposed approach supports semantic 3D reconstruction with altitude estimation, capturing elevation changes and enabling multi-level mapping. Experimental results demonstrate that the method produces semantically annotated 3D point clouds with improved structural detail and elevation information, underscoring the effectiveness of joint training with semantic cues for more consistent feature matching and enhanced 3D reconstruction.
### Title:
          Design and evaluation of an agentic workflow for crisis-related synthetic tweet datasets
 - **Authors:** Roben Delos Reyes, Timothy Douglas, Asanobu Kitamoto
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG); Multiagent Systems (cs.MA); Social and Information Networks (cs.SI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Twitter (now X) has become an important source of social media data for situational awareness during crises. Crisis informatics research has widely used tweets from Twitter to develop and evaluate artificial intelligence (AI) systems for various crisis-relevant tasks, such as extracting locations and estimating damage levels from tweets to support damage assessment. However, recent changes in Twitter's data access policies have made it increasingly difficult to curate real-world tweet datasets related to crises. Moreover, existing curated tweet datasets are limited to past crisis events in specific contexts and are costly to annotate at scale. These limitations constrain the development and evaluation of AI systems used in crisis informatics. To address these limitations, we introduce an agentic workflow for generating crisis-related synthetic tweet datasets. The workflow iteratively generates synthetic tweets conditioned on prespecified target characteristics, evaluates them using predefined compliance checks, and incorporates structured feedback to refine them in subsequent iterations. As a case study, we apply the workflow to generate synthetic tweet datasets relevant to post-earthquake damage assessment. We show that the workflow can generate synthetic tweets that capture their target labels for location and damage level. We further demonstrate that the resulting synthetic tweet datasets can be used to evaluate AI systems on damage assessment tasks like geolocalization and damage level prediction. Our results indicate that the workflow offers a flexible and scalable alternative to real-world tweet data curation, enabling the systematic generation of synthetic social media data across diverse crisis events, societal contexts, and crisis informatics applications.
### Title:
          Locatability-Guided Adaptive Reasoning for Image Geo-Localization with Vision-Language Models
 - **Authors:** Bo Yu, Fengze Yang, Yiming Liu, Chao Wang, Xuewen Luo, Taozhe Li, Ruimin Ke, Xiaofan Zhou, Chenxi Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The emergence of Vision-Language Models (VLMs) has introduced new paradigms for global image geo-localization through retrieval-augmented generation (RAG) and reasoning-driven inference. However, RAG methods are constrained by retrieval database quality, while reasoning-driven approaches fail to internalize image locatability, relying on inefficient, fixed-depth reasoning paths that increase hallucinations and degrade accuracy. To overcome these limitations, we introduce an Optimized Locatability Score that quantifies an image's suitability for deep reasoning in geo-localization. Using this metric, we curate Geo-ADAPT-51K, a locatability-stratified reasoning dataset enriched with augmented reasoning trajectories for complex visual scenes. Building on this foundation, we propose a two-stage Group Relative Policy Optimization (GRPO) curriculum with customized reward functions that regulate adaptive reasoning depth, visual grounding, and hierarchical geographical accuracy. Our framework, Geo-ADAPT, learns an adaptive reasoning policy, achieves state-of-the-art performance across multiple geo-localization benchmarks, and substantially reduces hallucinations by reasoning both adaptively and efficiently.
### Title:
          SAIL: Unsupervised Spatial-Angular Interpretable Feature Learning for RF Map Synthesis
 - **Authors:** Sopan Sarkar, Marwan Krunz
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In wireless networks, radio-frequency (RF) maps are critical for tasks such as capacity planning, coverage estimation, and localization. Traditional approaches for obtaining RF maps, including site surveys and ray-tracing simulations, are labor-intensive or computationally expensive, especially at high frequencies and dense network deployments. Generative AI offers a promising alternative for RF map synthesis. However, supervised methods are often infeasible due to the lack of reliable labeled training data, while purely unsupervised methods typically lack explicit control over the synthesis process. To address these challenges, we propose SAIL (Spatial-Angular Interpretable Feature Learning), a generative adversarial network (GAN)-based framework that learns interpretable and controllable latent variables directly from unlabeled RF maps and enables targeted RF map synthesis at inference time through latent-variable manipulation. SAIL builds on the information-maximizing GAN (InfoGAN) principle to learn a structured representation comprising: (i) a categorical latent variable that captures discrete floor-plan regions associated with Tx location and (ii) a continuous latent variable that captures angular variations corresponding to the Tx boresight angle, without requiring any location or orientation supervision during training. We further adopt a Wasserstein GAN objective with a gradient penalty to improve training stability and synthesis quality. Our results using ray-tracing-based RF maps indicate that SAIL learns physically meaningful spatial-angular factors and enables fast controlled RF map synthesis, achieving an average SSIM of 0.8576 and an average PSNR of 23.33 dB relative to ray-tracing simulations.
### Title:
          Sky2Ground: A Benchmark for Site Modeling under Varying Altitude
 - **Authors:** Zengyan Wang, Sirshapan Mitra, Rajat Modi, Grace Lim, Yogesh Rawat
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Sky2Ground, a three-view dataset designed for varying altitude camera localization, correspondence learning, and reconstruction. The dataset combines structured synthetic imagery with real, in-the-wild images, providing both controlled multi-view geometry and realistic scene noise. Each of the 51 sites contains thousands of satellite, aerial, and ground images spanning wide altitude ranges and nearly orthogonal viewing angles, enabling rigorous evaluation across global-to-local contexts. We benchmark state of the art pose estimation models, including MASt3R, DUSt3R, Map Anything, and VGGT, and observe that the use of satellite imagery often degrades performance, highlighting the challenges under large altitude variations. We also examine reconstruction methods, highlighting the challenges introduced by sparse geometric overlap, varying perspectives, and the use of real imagery, which often introduces noise and reduces rendering quality. To address some of these challenges, we propose SkyNet, a model which enhances cross-view consistency when incorporating satellite imagery with a curriculum-based training strategy to progressively incorporate more satellite views. SkyNet significantly strengthens multi-view alignment and outperforms existing methods by 9.6% on RRA@5 and 18.1% on RTA@5 in terms of absolute performance. Sky2Ground and SkyNet together establish a comprehensive testbed and baseline for advancing large-scale, multi-altitude 3D perception and generalizable camera localization. Code and models will be released publicly for future research.
### Title:
          QTrack: Query-Driven Reasoning for Multi-modal MOT
 - **Authors:** Tajamul Ashraf, Tavaheed Tariq, Sonia Yadav, Abrar Ul Riyaz, Wasif Tak, Moloud Abdar, Janibul Bashir
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-object tracking (MOT) has traditionally focused on estimating trajectories of all objects in a video, without selectively reasoning about user-specified targets under semantic instructions. In this work, we introduce a query-driven tracking paradigm that formulates tracking as a spatiotemporal reasoning problem conditioned on natural language queries. Given a reference frame, a video sequence, and a textual query, the goal is to localize and track only the target(s) specified in the query while maintaining temporal coherence and identity consistency. To support this setting, we construct RMOT26, a large-scale benchmark with grounded queries and sequence-level splits to prevent identity leakage and enable robust evaluation of generalization. We further present QTrack, an end-to-end vision-language model that integrates multimodal reasoning with tracking-oriented localization. Additionally, we introduce a Temporal Perception-Aware Policy Optimization strategy with structured rewards to encourage motion-aware reasoning. Extensive experiments demonstrate the effectiveness of our approach for reasoning-centric, language-guided tracking. Code and data are available at this https URL
### Title:
          AD-Copilot: A Vision-Language Assistant for Industrial Anomaly Detection via Visual In-context Comparison
 - **Authors:** Xi Jiang, Yue Guo, Jian Li, Yong Liu, Bin-Bin Gao, Hanqiu Deng, Jun Liu, Heng Zhao, Chengjie Wang, Feng Zheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal Large Language Models (MLLMs) have achieved impressive success in natural visual understanding, yet they consistently underperform in industrial anomaly detection (IAD). This is because MLLMs trained mostly on general web data differ significantly from industrial images. Moreover, they encode each image independently and can only compare images in the language space, making them insensitive to subtle visual differences that are key to IAD. To tackle these issues, we present AD-Copilot, an interactive MLLM specialized for IAD via visual in-context comparison. We first design a novel data curation pipeline to mine inspection knowledge from sparsely labeled industrial images and generate precise samples for captioning, VQA, and defect localization, yielding a large-scale multimodal dataset Chat-AD rich in semantic signals for IAD. On this foundation, AD-Copilot incorporates a novel Comparison Encoder that employs cross-attention between paired image features to enhance multi-image fine-grained perception, and is trained with a multi-stage strategy that incorporates domain knowledge and gradually enhances IAD skills. In addition, we introduce MMAD-BBox, an extended benchmark for anomaly localization with bounding-box-based evaluation. The experiments show that AD-Copilot achieves 82.3% accuracy on the MMAD benchmark, outperforming all other models without any data leakage. In the MMAD-BBox test, it achieves a maximum improvement of $3.35\times$ over the baseline. AD-Copilot also exhibits excellent generalization of its performance gains across other specialized and general-purpose benchmarks. Remarkably, AD-Copilot surpasses human expert-level performance on several IAD tasks, demonstrating its potential as a reliable assistant for real-world industrial inspection. All datasets and models will be released for the broader benefit of the community.
### Title:
          MOGeo: Beyond One-to-One Cross-View Object Geo-localization
 - **Authors:** Bo Lv, Qingwang Zhang, Le Wu, Yuanyuan Li, Yingying Zhu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-View Object Geo-Localization (CVOGL) aims to locate an object of interest in a query image within a corresponding satellite image. Existing methods typically assume that the query image contains only a single object, which does not align with the complex, multi-object geo-localization requirements in real-world applications, making them unsuitable for practical scenarios. To bridge the gap between the realistic setting and existing task, we propose a new task, called Cross-View Multi-Object Geo-Localization (CVMOGL). To advance the CVMOGL task, we first construct a benchmark, CMLocation, which includes two datasets: CMLocation-V1 and CMLocation-V2. Furthermore, we propose a novel cross-view multi-object geo-localization method, MOGeo, and benchmark it against existing state-of-the-art methods. Extensive experiments are conducted under various application scenarios to validate the effectiveness of our method. The results demonstrate that cross-view object geo-localization in the more realistic setting remains a challenging problem, encouraging further research in this area.
### Title:
          VFM-Loc: Zero-Shot Cross-View Geo-Localization via Aligning Discriminative Visual Hierarchies
 - **Authors:** Jun Lu, Zehao Sang, Haoqi Wei, Xiangyun Liu, Kun Zhu, Haitao Guo, Zhihui Gong, Lei Ding
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-View Geo-Localization (CVGL) in remote sensing aims to locate a drone-view query by matching it to geo-tagged satellite images. Although supervised methods have achieved strong results on closeset benchmarks, they often fail to generalize to unconstrained, real-world scenarios due to severe viewpoint differences and dataset bias. To overcome these limitations, we present VFM-Loc, a training-free framework for zero-shot CVGL that leverages the generalizable visual representations from vision foundational models (VFMs). VFM-Loc identifies and matches discriminative visual clues across different viewpoints through a progressive alignment strategy. First, we design a hierarchical clue extraction mechanism using Generalized Mean pooling and Scale-Weighted RMAC to preserve distinctive visual clues across scales while maintaining hierarchical confidence. Second, we introduce a statistical manifold alignment pipeline based on domain-wise PCA and Orthogonal Procrustes analysis, linearly aligning heterogeneous feature distributions in a shared metric space. Experiments demonstrate that VFM-Loc exhibits strong zero-shot accuracy on standard benchmarks and surpasses supervised methods by over 20% in Recall@1 on the challenging LO-UCV dataset with large oblique angles. This work highlights that principled alignment of pre-trained features can effectively bridge the cross-view gap, establishing a robust and training-free paradigm for real-world CVGL. The relevant code is made available at: this https URL.
### Title:
          Multi-Modal Character Localization and Extraction for Chinese Text Recognition
 - **Authors:** Qilong Li, Chongsheng Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scene text recognition (STR) methods have demonstrated their excellent capability in English text images. However, due to the complex inner structures of Chinese and the extensive character categories, it poses challenges for recognizing Chinese text in images. Recently, studies have shown that the methods designed for English text recognition encounter an accuracy bottleneck when recognizing Chinese text images. This raises the question: Is it appropriate to apply the model developed for English to the Chinese STR task? To explore this issue, we propose a novel method named LER, which explicitly decouples each character and independently recognizes characters while taking into account the complex inner structures of Chinese. LER consists of three modules: Localization, Extraction, and Recognition. Firstly, the localization module utilizes multimodal information to determine the character's position precisely. Then, the extraction module dissociates all characters in parallel. Finally, the recognition module considers the unique inner structures of Chinese to provide the text prediction results. Extensive experiments conducted on large-scale Chinese benchmarks indicate that our method significantly outperforms existing methods. Furthermore, extensive experiments conducted on six English benchmarks and the Union14M benchmark show impressive results in English text recognition by LER. Code is available at this https URL.
### Title:
          Evaluation of Visual Place Recognition Methods for Image Pair Retrieval in 3D Vision and Robotics
 - **Authors:** Dennis Haitz, Athradi Shritish Shetty, Michael Weinmann, Markus Ulrich
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual Place Recognition (VPR) is a core component in computer vision, typically formulated as an image retrieval task for localization, mapping, and navigation. In this work, we instead study VPR as an image pair retrieval front-end for registration pipelines, where the goal is to find top-matching image pairs between two disjoint image sets for downstream tasks such as scene registration, SLAM, and Structure-from-Motion. We comparatively evaluate state-of-the-art VPR families - NetVLAD-style baselines, classification-based global descriptors (CosPlace, EigenPlaces), feature-mixing (MixVPR), and foundation-model-driven methods (AnyLoc, SALAD, MegaLoc) - on three challenging datasets: object-centric outdoor scenes (Tanks and Temples), indoor RGB-D scans (ScanNet-GS), and autonomous-driving sequences (KITTI). We show that modern global descriptor approaches are increasingly suitable as off-the-shelf image pair retrieval modules in challenging scenarios including perceptual aliasing and incomplete sequences, while exhibiting clear, domain-dependent strengths and weaknesses that are critical when choosing VPR components for robust mapping and registration.
### Title:
          USIS-PGM: Photometric Gaussian Mixtures for Underwater Salient Instance Segmentation
 - **Authors:** Lin Hong, Xiangtong Yao, Mürüvvet Bozkurt, Xin Wang, Fumin Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Underwater salient instance segmentation (USIS) is crucial for marine robotic systems, as it enables both underwater salient object detection and instance-level mask prediction for visual scene understanding. Compared with its terrestrial counterpart, USIS is more challenging due to the underwater image degradation. To address this issue, this paper proposes USIS-PGM, a single-stage framework for USIS. Specifically, the encoder enhances boundary cues through a frequency-aware module and performs content-adaptive feature reweighting via a dynamic weighting module. The decoder incorporates a Transformer-based instance activation module to better distinguish salient instances. In addition, USIS-PGM employs multi-scale Gaussian heatmaps generated from ground-truth masks through Photometric Gaussian Mixture (PGM) to supervise intermediate decoder features, thereby improving salient instance localization and producing more structurally coherent mask predictions. Experimental results demonstrate the superiority and practical applicability of the proposed USIS-PGM model.
### Title:
          Navigation beyond Wayfinding: Robots Collaborating with Visually Impaired Users for Environmental Interactions
 - **Authors:** Shaojun Cai, Nuwan Janaka, Ashwin Ram, Janidu Shehan, Yingjia Wan, Kotaro Hara, David Hsu
 - **Subjects:** Subjects:
Robotics (cs.RO); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robotic guidance systems have shown promise in supporting blind and visually impaired (BVI) individuals with wayfinding and obstacle avoidance. However, most existing systems assume a clear path and do not support a critical aspect of navigation - environmental interactions that require manipulating objects to enable movement. These interactions are challenging for a human-robot pair because they demand (i) precise localization and manipulation of interaction targets (e.g., pressing elevator buttons) and (ii) dynamic coordination between the user's and robot's movements (e.g., pulling out a chair to sit). We present a collaborative human-robot approach that combines our robotic guide dog's precise sensing and localization capabilities with the user's ability to perform physical manipulation. The system alternates between two modes: lead mode, where the robot detects and guides the user to the target, and adaptation mode, where the robot adjusts its motion as the user interacts with the environment (e.g., opening a door). Evaluation results show that our system enables navigation that is safer, smoother, and more efficient than both a traditional white cane and a non-adaptive guiding system, with the performance gap widening as tasks demand higher precision in locating interaction targets. These findings highlight the promise of human-robot collaboration in advancing assistive technologies toward more generalizable and realistic navigation support.
### Title:
          Geometry-Aware Set-Membership Multilateration: Directional Bounds and Anchor Selection
 - **Authors:** Giuseppe C. Calafiore
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we study anchor selection for range-based localization under unknown-but-bounded measurement errors. We start from the convex localization set $\X=\Xd\cap\Hset$ recently introduced in \cite{CalafioreSIAM}, where $\Xd$ is a polyhedron obtained from pairwise differences of squared-range equations between the unknown location $x$ and the anchors, and $\Hset$ is the intersection of upper-range hyperspheres. Our first goal is \emph{offline} design: we derive geometry-only E- and D-type scores from the centered scatter matrix $S(A)=AQ_mA\tran$, where $A$ collects the anchor coordinates and $Q_m=I_m-\frac{1}{m}\one\one\tran$ is the centering projector, showing that $\lambda_{\min}(S(A))$ controls worst-direction and diameter surrogates for the polyhedral certificate $\Xd$, while $\det S(A)$ controls principal-axis volume surrogates. Our second goal is \emph{online} uncertainty assessment for a selected subset of anchors: exploiting the special structure $\X=\Xd\cap\Hset$, we derive a simplex-aggregated enclosing ball for $\Hset$ and an exact support-function formula for $\Hset$, which lead to finite hybrid bounds for the actual localization set $\X$, even when the polyhedral certificate deteriorates. Numerical experiments are performed in two dimensions, showing that geometry-based subset selection is close to an oracle combinatorial search, that the D-score slightly dominates the E-score for the area-oriented metric considered here, and that the new $\Hset$-aware certificates track the realized size of the selected localization set closely.
### Title:
          Localizing and Editing Knowledge in Large Audio-Language Models
 - **Authors:** Sung Kyun Chung, Jiaheng Dong, Qiuchi Hu, Gongping Huang, Hong Jia, Ting Dang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Audio-Language Models (LALMs) have shown strong performance in speech understanding, making speech a natural interface for accessing factual information. Yet they are trained on static corpora and may encode incorrect facts. Existing model editing methods localize and update facts in text-only LLMs, but do not account for continuous speech representations, or where knowledge is stored across acoustic or language modules, or their cross-modal module. We construct the first audio benchmark for knowledge localization and editing in LALMs and propose a speech-driven locate-then-edit framework. First, we use speech-aware causal tracing to localize layers and modules that support factual retrieval and then apply editing at identified sites. Experiments show that factual knowledge is jointly encoded in audio and text modules, and that audio editing yields more effective updates than text editing or fine-tuning, enabling fine-grained knowledge control in speech AI systems.
### Title:
          Face-Guided Sentiment Boundary Enhancement for Weakly-Supervised Temporal Sentiment Localization
 - **Authors:** Cailing Han, Zhangbin Li, Jinxing Zhou, Wei Qian, Jingjing Hu, Yanghao Zhou, Zhangling Duan, Dan Guo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Point-level weakly-supervised temporal sentiment localization (P-WTSL) aims to detect sentiment-relevant segments in untrimmed multimodal videos using timestamp sentiment annotations, which greatly reduces the costly frame-level labeling. To further tackle the challenges of imprecise sentiment boundaries in P-WTSL, we propose the Face-guided Sentiment Boundary Enhancement Network (\textbf{FSENet}), a unified framework that leverages fine-grained facial features to guide sentiment localization. Specifically, our approach \textit{first} introduces the Face-guided Sentiment Discovery (FSD) module, which integrates facial features into multimodal interaction via dual-branch modeling for effective sentiment stimuli clues; We \textit{then} propose the Point-aware Sentiment Semantics Contrast (PSSC) strategy to discriminate sentiment semantics of candidate points (frame-level) near annotation points via contrastive learning, thereby enhancing the model's ability to recognize sentiment boundaries. At \textit{last}, we design the Boundary-aware Sentiment Pseudo-label Generation (BSPG) approach to convert sparse point annotations into temporally smooth supervisory pseudo-labels. Extensive experiments and visualizations on the benchmark demonstrate the effectiveness of our framework, achieving state-of-the-art performance under full supervision, video-level, and point-level weak supervision, thereby showcasing the strong generalization ability of our FSENet across different annotation settings.
### Title:
          HiMemVLN: Enhancing Reliability of Open-Source Zero-Shot Vision-and-Language Navigation with Hierarchical Memory System
 - **Authors:** Kailin Lyu, Kangyi Wu, Pengna Li, Xiuyu Hu, Qingyi Si, Cui Miao, Ning Yang, Zihang Wang, Long Xiao, Lianyu Hu, Jingyuan Sun, Ce Hao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLM-based agents have demonstrated impressive zero-shot performance in vision-language navigation (VLN) tasks. However, most zero-shot methods primarily rely on closed-source LLMs as navigators, which face challenges related to high token costs and potential data leakage risks. Recent efforts have attempted to address this by using open-source LLMs combined with a spatiotemporal CoT framework, but they still fall far short compared to closed-source models. In this work, we identify a critical issue, Navigation Amnesia, through a detailed analysis of the navigation process. This issue leads to navigation failures and amplifies the gap between open-source and closed-source methods. To address this, we propose HiMemVLN, which incorporates a Hierarchical Memory System into a multimodal large model to enhance visual perception recall and long-term localization, mitigating the amnesia issue and improving the agent's navigation performance. Extensive experiments in both simulated and real-world environments demonstrate that HiMemVLN achieves nearly twice the performance of the open-source state-of-the-art method. The code is available at this https URL.
### Title:
          Ego to World: Collaborative Spatial Reasoning in Embodied Systems via Reinforcement Learning
 - **Authors:** Heng Zhou, Li Kang, Yiran Qin, Xiufeng Song, Ao Yu, Zilu Zhang, Haoming Song, Kaixin Xu, Yuchen Fan, Dongzhan Zhou, Xiaohong Liu, Ruimao Zhang, Philip Torr, Lei Bai, Zhenfei Yin
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding the world from distributed, partial viewpoints is a fundamental challenge for embodied multi-agent systems. Each agent perceives the environment through an ego-centric view that is often limited by occlusion and ambiguity. To study this problem, we introduce the Ego-to-World (E2W) benchmark, which evaluates a vision-language model's ability to fuse heterogeneous viewpoints across three tasks: (i) global counting, (ii) relational location reasoning, and (iii) action-oriented grasping that requires predicting view-specific image coordinates. To address this setting, we propose CoRL, a two-stage framework that combines Chain-of-Thought supervised fine-tuning with reinforcement learning using Group-Relative Policy Optimization. Its core component, the Cross-View Spatial Reward (CVSR), provides dense task-aligned feedback by linking reasoning steps to visual evidence, ensuring coherent cross-view entity resolution, and guiding the model toward correct final predictions. Experiments on E2W show that CoRL consistently surpasses strong proprietary and open-source baselines on both reasoning and perception-grounding metrics, while ablations further confirm the necessity of each CVSR component. Beyond that, CoRL generalizes to external spatial reasoning benchmarks and enables effective real-world multi-robot manipulation with calibrated multi-camera rigs, demonstrating cross-view localization and successful grasp-and-place execution. Together, E2W and CoRL provide a principled foundation for learning world-centric scene understanding from distributed, ego-centric observations, advancing collaborative embodied AI.
### Title:
          From Horizontal to Rotated: Cross-View Object Geo-Localization with Orientation Awareness
 - **Authors:** Chenlin Fu, Ao Gong, Yingying Zhu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-View object geo-localization (CVOGL) aims to precisely determine the geographic coordinates of a query object from a ground or drone perspective by referencing a satellite map. Segmentation-based approaches offer high precision but require prohibitively expensive pixel-level annotations, whereas more economical detection-based methods suffer from lower accuracy. This performance disparity in detection is primarily caused by two factors: the poor geometric fit of Horizontal Bounding Boxes (HBoxes) for oriented objects and the degradation in precision due to feature map scaling. Motivated by these, we propose leveraging Rotated Bounding Boxes (RBoxes) as a natural extension of the detection-based paradigm. RBoxes provide a much tighter geometric fit to oriented objects. Building on this, we introduce OSGeo, a novel geo-localization framework, meticulously designed with a multi-scale perception module and an orientation-sensitive head to accurately regress RBoxes. To support this scheme, we also construct and release CVOGL-R, the first dataset with precise RBox annotations for CVOGL. Extensive experiments demonstrate that our OSGeo achieves state-of-the-art performance, consistently matching or even surpassing the accuracy of leading segmentation-based methods but with an annotation cost that is over an order of magnitude lower.
### Title:
          RealVLG-R1: A Large-Scale Real-World Visual-Language Grounding Benchmark for Robotic Perception and Manipulation
 - **Authors:** Linfei Li, Lin Zhang, Ying Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual-language grounding aims to establish semantic correspondences between natural language and visual entities, enabling models to accurately identify and localize target objects based on textual instructions. Existing VLG approaches focus on coarse-grained, object-level localization, while traditional robotic grasping methods rely predominantly on geometric cues and lack language guidance, which limits their applicability in language-driven manipulation scenarios. To address these limitations, we propose the RealVLG framework, which integrates the RealVLG-11B dataset and the RealVLG-R1 model to unify real-world visual-language grounding and grasping tasks. RealVLG-11B dataset provides multi-granularity annotations including bounding boxes, segmentation masks, grasp poses, contact points, and human-verified fine-grained language descriptions, covering approximately 165,000 images, over 800 object instances, 1.3 million segmentation, detection, and language annotations, and roughly 11 billion grasping examples. Building on this dataset, RealVLG-R1 employs Reinforcement Fine-tuning on pretrained large-scale vision-language models to predict bounding boxes, segmentation masks, grasp poses, and contact points in a unified manner given natural language instructions. Experimental results demonstrate that RealVLG supports zero-shot perception and manipulation in real-world unseen environments, establishing a unified semantic-visual multimodal benchmark that provides a comprehensive data and evaluation platform for language-driven robotic perception and grasping policy learning. All data and code are publicly available at this https URL.
### Title:
          Thermal Image Refinement with Depth Estimation using Recurrent Networks for Monocular ORB-SLAM3
 - **Authors:** Hürkan Şahin, Huy Xuan Pham, Van Huyen Dang, Alper Yegenoglu, Erdal Kayacan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous navigation in GPS-denied and visually degraded environments remains challenging for unmanned aerial vehicles (UAVs). To this end, we investigate the use of a monocular thermal camera as a standalone sensor on a UAV platform for real-time depth estimation and simultaneous localization and mapping (SLAM). To extract depth information from thermal images, we propose a novel pipeline employing a lightweight supervised network with recurrent blocks (RBs) integrated to capture temporal dependencies, enabling more robust predictions. The network combines lightweight convolutional backbones with a thermal refinement network (T-RefNet) to refine raw thermal inputs and enhance feature visibility. The refined thermal images and predicted depth maps are integrated into ORB-SLAM3, enabling thermal-only localization. Unlike previous methods, the network is trained on a custom non-radiometric dataset, obviating the need for high-cost radiometric thermal cameras. Experimental results on datasets and UAV flights demonstrate competitive depth accuracy and robust SLAM performance under low-light conditions. On the radiometric VIVID++ (indoor-dark) dataset, our method achieves an absolute relative error of approximately 0.06, compared to baselines exceeding 0.11. In our non-radiometric indoor set, baseline errors remain above 0.24, whereas our approach remains below 0.10. Thermal-only ORB-SLAM3 maintains a mean trajectory error under 0.4 m.
### Title:
          A Novel Camera-to-Robot Calibration Method for Vision-Based Floor Measurements
 - **Authors:** Jan Andre Rudolph, Dennis Haitz, Markus Ulrich
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A novel hand-eye calibration method for ground-observing mobile robots is proposed. While cameras on mobile robots are com- mon, they are rarely used for ground-observing measurement tasks. Laser trackers are increasingly used in robotics for precise localization. A referencing plate is designed to combine the two measurement modalities of laser-tracker 3D metrology and camera- based 2D imaging. It incorporates reflector nests for pose acquisition using a laser tracker and a camera calibration target that is observed by the robot-mounted camera. The procedure comprises estimating the plate pose, the plate-camera pose, and the robot pose, followed by computing the robot-camera transformation. Experiments indicate sub-millimeter repeatability.
### Title:
          Confusion-Aware In-Context-Learning for Vision-Language Models in Robotic Manipulation
 - **Authors:** Yayun He, Zuheng Kang, Botao Zhao, Zhouyin Wu, Junqing Peng, Jianzong Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language models (VLMs) have significantly improved the generalization capabilities of robotic manipulation. However, VLM-based systems often suffer from a lack of robustness, leading to unpredictable errors, particularly in scenarios involving confusable objects. Our preliminary analysis reveals that these failures are mainly caused by shortcut learning problem inherently in VLMs, limiting their ability to accurately distinguish between confusable features. To this end, we propose Confusion-Aware In-Context Learning (CAICL), a method that enhances VLM performance in confusable scenarios for robotic manipulation. The approach begins with confusion localization and analysis, identifying potential sources of confusion. This information is then used as a prompt for the VLM to focus on features most likely to cause misidentification. Extensive experiments on the VIMA-Bench show that CAICL effectively addresses the shortcut learning issue, achieving a 85.5\% success rate and showing good stability across tasks with different degrees of generalization.
### Title:
          Spectral Rectification for Parameter-Efficient Adaptation of Foundation Models in Colonoscopy Depth Estimation
 - **Authors:** Xiaoxian Zhang, Minghai Shi, Lei Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate monocular depth estimation is critical in colonoscopy for lesion localization and navigation. Foundation models trained on natural images fail to generalize directly to colonoscopy. We identify the core issue not as a semantic gap, but as a statistical shift in the frequency domain: colonoscopy images lack the strong high-frequency edge and texture gradients that these models rely on for geometric reasoning. To address this, we propose SpecDepth, a parameter-efficient adaptation framework that preserves the robust geometric representations of the pre-trained models while adapting to the colonoscopy domain. Its key innovation is an adaptive spectral rectification module, which uses a learnable wavelet decomposition to explicitly model and amplify the attenuated high-frequency components in feature maps. Different from conventional fine-tuning that risks distorting high-level semantic features, this targeted, low-level adjustment realigns the input signal with the original inductive bias of the foundational model. On the public C3VD and SimCol3D datasets, SpecDepth achieved state-of-the-art performance with an absolute relative error of 0.022 and 0.027, respectively. Our work demonstrates that directly addressing spectral mismatches is a highly effective strategy for adapting vision foundation models to specialized medical imaging tasks. The code will be released publicly after the manuscript is accepted for publication.
### Title:
          Matched Filter-Based Molecule Source Localization in Advection-Diffusion-Driven Pipe Networks with Known Topology
 - **Authors:** Timo Jakumeit, Bastian Heinlein, Vukašin Spasojević, Vahid Jamali, Robert Schober, Maximilian Schäfer
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Synthetic molecular communication (MC) has emerged as a powerful framework for modeling, analyzing, and designing communication systems where information is encoded into properties of molecules. Among the envisioned applications of MC is the localization of molecule sources in pipe networks (PNs) like the human cardiovascular system (CVS), sewage networks (SNs), and industrial plants. While existing algorithms mostly focus on simplified scenarios, in this paper, we propose the first framework for source localization in complex PNs with known topology, by leveraging the mixture of inverse Gaussians for hemodynamic transport (MIGHT) model as a closed-form representation for advection-diffusion-driven MC in PNs. We propose a matched filter (MF)-based approach to identify molecule sources under realistic conditions such as unknown release times, random numbers of released molecules, sensor noise, and limited sensor sampling rate. We apply the algorithm to localize a source of viral markers in a real-world SN and show that the proposed scheme outperforms randomly guessing sources even at low signal-to-noise ratios (SNRs) at the sensor and achieves error-free localization under favorable conditions, i.e., high SNRs and sampling rates. Furthermore, by identifying clusters of frequently confused sources, reliable cluster-level localization is possible at substantially lower SNRs and sampling rates.
### Title:
          Enabling mmWave Communications with VCSEL-Based Light-Emitting Reconfigurable Intelligent Surfaces
 - **Authors:** Rashid Iqbal, Dimitrios Bozanis, Dimitrios Tyrovolas, Christos K. Liaskos, Muhammad Ali Imran, George K. Karagiannidis, Hanaa Abumarshoud
 - **Subjects:** Subjects:
Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper proposes a light-emitting reconfigurable intelligent surface (LeRIS) architecture that integrates vertical cavity surface-emitting lasers (VCSELs) to jointly support user localization and mmWave communication. By leveraging the directional Gaussian beams and dual-mode diversity of VCSELs, we derive a closed-form method for estimating user position and orientation using only three VCSEL sources. These estimates are then used to configure LeRIS panels for directional mmWave beamforming, enabling optimized wave propagation in programmable wireless environments. Simulation results demonstrate that the proposed system achieves millimeter-level localization accuracy and maintains high spectral efficiency. These findings establish VCSEL-integrated LeRIS as a scalable and multifunctional solution for future 6G programmable wireless environments.
## Keyword: transformer
### Title:
          Slang Context-based Inference Enhancement via Greedy Search-Guided Chain-of-Thought Prompting
 - **Authors:** Jinghan Cao, Qingyang Ren, Xiangyun Chen, Xinjin Li, Haoxiang Gao, Yu Zhao
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Slang interpretation has been a challenging downstream task for Large Language Models (LLMs) as the expressions are inherently embedded in contextual, cultural, and linguistic frameworks. In the absence of domain-specific training data, it is difficult for LLMs to accurately interpret slang meaning based on lexical information. This paper attempts to investigate the challenges of slang inference using large LLMs and presents a greedy search-guided chain-of-thought framework for slang interpretation. Through our experiments, we conclude that the model size and temperature settings have limited impact on inference accuracy. Transformer-based models with larger active parameters do not generate higher accuracy than smaller models. Based on the results of the above empirical study, we integrate greedy search algorithms with chain-of-thought prompting for small language models to build a framework that improves the accuracy of slang interpretation. The experimental results indicate that our proposed framework demonstrates improved accuracy in slang meaning interpretation. These findings contribute to the understanding of context dependency in language models and provide a practical solution for enhancing slang comprehension through a structured reasoning prompting framework.
### Title:
          Translational Gaps in Graph Transformers for Longitudinal EHR Prediction: A Critical Appraisal of GT-BEHRT
 - **Authors:** Krish Tadigotla
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based models have improved predictive modeling on longitudinal electronic health records through large-scale self-supervised pretraining. However, most EHR transformer architectures treat each clinical encounter as an unordered collection of codes, which limits their ability to capture meaningful relationships within a visit. Graph-transformer approaches aim to address this limitation by modeling visit-level structure while retaining the ability to learn long-term temporal patterns. This paper provides a critical review of GT-BEHRT, a graph-transformer architecture evaluated on MIMIC-IV intensive care outcomes and heart failure prediction in the All of Us Research Program. We examine whether the reported performance gains reflect genuine architectural benefits and whether the evaluation methodology supports claims of robustness and clinical relevance. We analyze GT-BEHRT across seven dimensions relevant to modern machine learning systems, including representation design, pretraining strategy, cohort construction transparency, evaluation beyond discrimination, fairness assessment, reproducibility, and deployment feasibility. GT-BEHRT reports strong discrimination for heart failure prediction within 365 days, with AUROC 94.37 +/- 0.20, AUPRC 73.96 +/- 0.83, and F1 64.70 +/- 0.85. Despite these results, we identify several important gaps, including the lack of calibration analysis, incomplete fairness evaluation, sensitivity to cohort selection, limited analysis across phenotypes and prediction horizons, and limited discussion of practical deployment considerations. Overall, GT-BEHRT represents a meaningful architectural advance in EHR representation learning, but more rigorous evaluation focused on calibration, fairness, and deployment is needed before such models can reliably support clinical decision-making.
### Title:
          ICaRus: Identical Cache Reuse for Efficient Multi Model Inference
 - **Authors:** Sunghyeon Woo, Jaeeun Kil, Hoseung Kim, Minsub Kim, Joonghoon Kim, Ahreum Seo, Sungjae Lee, Minjung Jo, Jiwon Ryu, Baeseong Park, Se Jung Kwon, Dongsoo Lee
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi model inference has recently emerged as a prominent paradigm, particularly in the development of agentic AI systems. However, in such scenarios, each model must maintain its own Key-Value (KV) cache for the identical prompt, leading to substantial memory consumption. This explosive growth of KV caches forces LLM serving systems to evict previously stored caches, which in turn introduces significant recomputation overhead whenever the evicted caches are required again. Moreover, prefix caching is inherently infeasible across different models, forcing each model to recompute KV cache for the identical prompt, which leads to significant overhead. To alleviate these issues, we propose Identical Cache Reuse (ICaRus), a novel architecture that allows multiple models to share identical KV caches across all layers. ICaRus is based on the key observation that a decoder-only Transformer can be conceptually decomposed into a logical encoder, which generates KV caches, and a logical decoder, which predicts output tokens from the KV caches. ICaRus fine-tunes only the logical decoder while freezing the logical encoder, enabling multiple models to share an identical KV cache. This eliminates cache memory explosion and unexpected evictions while also allowing cross-model reuse of KV caches for new input tokens, thereby removing redundant recomputation in multi model inference achieving both efficiency and scalability. Moreover, by incorporating lightweight adapters such as LoRA, ICaRus parallelizes KV cache generation and next-token prediction during decoding. ICaRus achieves comparable accuracy to task-specific fine-tuned model across a diverse set of tasks, while allowing multiple specialized models to fully share KV caches. ICaRus achieves up to 11.1x lower P95 latency and 3.8x higher throughput in multi agent workflow with 8 different models, compared to conventional multi model system.
### Title:
          Linear Predictability of Attention Heads in Large Language Models
 - **Authors:** Khalid Shaikh, Asmit Kumar Singh, Rebecca Christopher Dsouza, Shikhar Shiromani
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language model (LLM) inference is increasingly bottlenecked by the Key-Value (KV) cache, yet the fine-grained structure of attention-head activations remains poorly understood. We show that pretrained Transformers exhibit a pervasive inter-head linear structure: for a given token, the Query, Key, and Value (QKV) vectors of an attention head can often be reconstructed as a linear combination of a small number of peer heads, typically within the same layer. Across Llama-3.1-8B, Falcon3-10B, OLMo-2-7B, and Qwen3-32B, just 2-5 reference heads recover many target heads with high fidelity (e.g., mean R^2 approx 0.76 for Keys on C4 with five references, and frequently R^2 > 0.85 on GSM8K). This predictability is learned rather than architectural: it is largely absent at random initialization, rises rapidly during pretraining as we track through OLMo-2 checkpoints, and is supported by a theoretical lower bound showing high mean-squared error for linear prediction at initialization. We further connect this emergence to increasing intra-layer alignment of Key projection subspaces. Finally, we exploit this redundancy for efficiency by caching only reference-head KV states and reconstructing the remaining heads on the fly via lightweight linear maps, achieving 2x KV-cache reduction with model-dependent accuracy trade-offs (4.5-5.5 percentage point average drop on Falcon3-10B and Qwen3-32B across five benchmarks, and larger drops on Llama-3.1-8B), and we find that reconstructing Keys is substantially less harmful than reconstructing Values.
### Title:
          Nepali Passport Question Answering: A Low-Resource Dataset for Public Service Applications
 - **Authors:** Funghang Limbu Begha, Praveen Acharya, Bal Krishna Bal
 - **Subjects:** Subjects:
Information Retrieval (cs.IR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Nepali, a low-resource language, faces significant challenges in building an effective information retrieval system due to the unavailability of annotated data and computational linguistic resources. In this study, we attempt to address this gap by preparing a pair-structured Nepali Question-Answer dataset. We focus on Frequently Asked Questions (FAQs) for passport-related services, building a data set for training and evaluation of IR models. In our study, we have fine-tuned transformer-based embedding models for semantic similarity in question-answer retrieval. The fine-tuned models were compared with the baseline BM25. In addition, we implement a hybrid retrieval approach, integrating fine-tuned models with BM25, and evaluate the performance of the hybrid retrieval. Our results show that the fine-tuned SBERT-based models outperform BM25, whereas multilingual E5 embedding-based models achieve the highest retrieval performance among all evaluated models.
### Title:
          Feature-level Interaction Explanations in Multimodal Transformers
 - **Authors:** Yeji Kim, Housam Khalifa Bashier Babiker, Mi-Young Kim, Randy Goebel
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal Transformers often produce predictions without clarifying how different modalities jointly support a decision. Most existing multimodal explainable AI (MXAI) methods extend unimodal saliency to multimodal backbones, highlighting important tokens or patches within each modality, but they rarely pinpoint which cross-modal feature pairs provide complementary evidence (synergy) or serve as reliable backups (redundancy). We present Feature-level I2MoE (FL-I2MoE), a structured Mixture-of-Experts layer that operates directly on token/patch sequences from frozen pretrained encoders and explicitly separates unique, synergistic, and redundant evidence at the feature level. We further develop an expert-wise explanation pipeline that combines attribution with top-K% masking to assess faithfulness, and we introduce Monte Carlo interaction probes to quantify pairwise behavior: the Shapley Interaction Index (SII) to score synergistic pairs and a redundancy-gap score to capture substitutable (redundant) pairs. Across three benchmarks (MMIMDb, ENRICO, and MMHS150K), FL-I2MoE yields more interactionspecific and concentrated importance patterns than a dense Transformer with the same encoders. Finally, pair-level masking shows that removing pairs ranked by SII or redundancy-gap degrades performance more than masking randomly chosen pairs under the same budget, supporting that the identified interactions are causally relevant.
### Title:
          PolyGLU: State-Conditional Activation Routing in Transformer Feed-Forward Networks
 - **Authors:** Daniel Nobrega Medeiros
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Biological neural systems employ diverse neurotransmitters -- glutamate, GABA, dopamine, acetylcholine -- to implement distinct signal-processing modalities within shared neural circuits. In contrast, modern transformers apply a single fixed activation function across all feed-forward neurons. We introduce PolyGLU (Polychromatic Gated Linear Unit), a drop-in replacement for SwiGLU that enables each FFN neuron to dynamically route among K=4 activation functions via a differentiable mechanism combining learned static preferences with input-conditioned gating, trained end-to-end with Gumbel-Softmax. We train PolychromaticLM, a 597M-parameter transformer, on ~10B tokens using a single NVIDIA A100 GPU. Our key finding is emergent routing behavior: without any explicit sparsity loss or entropy regularization, the routing mechanism converges to near-deterministic activation selections (mean dynamic entropy = 0.030% of maximum), with a striking depth-dependent specialization pattern -- early layers prefer GELU while deep layers strongly favor Tanh. Three layers maintain elevated routing entropy, suggesting computational flexibility points. The routing architecture adds only 0.23% parameter overhead (~1.4M parameters) and proves fully robust to supervised fine-tuning: routing entropy remains constant at ln(4) throughout 13,067 SFT steps. On standard benchmarks, PolychromaticLM achieves 62-89% of Qwen3-0.6B-Base performance despite training on 3,600x fewer tokens. All code, weights, and training infrastructure are released under Apache 2.0.
### Title:
          Agentic LLM Workflow for MR Spectroscopy Volume-of-Interest Placements in Brain Tumors
 - **Authors:** Sangyoon Lee, Francesca Branzoli, Małgorzata Marjańska, Patrick Bolan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Magnetic resonance spectroscopy (MRS) provides clinically valuable metabolic characterization of brain tumors, but its utility depends on accurate placement of the spectroscopy volume-of-interest (VOI). However, VOI placement typically has a broad operating window: for a given tumor there are multiple possible VOIs that would lead to high-quality MRS measurements. Thus, a VOI place-ment can be tuned for clinician preference, case-specific anatomy, and clinical pri-orities, which leads to high inter-operator variability, especially for heterogeneous tumors. We propose an agentic large language model (LLM) workflow that de-composes VOI placement into generation of diverse candidate VOIs, from which the LLM selects an optimal one based on quantitative metrics. Candidate VOIs are generated by vision transformer-based placement models trained with differ-ent objective function preferences, which allows selection from acceptable alterna-tives rather than a single deterministic placement. On 110 clinical brain tumor cas-es, the agentic workflow achieves improved solid tumor coverage and necrosis avoidance depending on the user preferences compared to the general-purpose expert placements. Overall, the proposed workflow provides a strategy to adapt VOI placement to different clinical objectives without retraining task-specific models.
### Title:
          A Hierarchical End-of-Turn Model with Primary Speaker Segmentation for Real-Time Conversational AI
 - **Authors:** Karim Helwani, Hoang Do, James Luan, Sriram Srinivasan
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a real-time front-end for voice-based conversational AI to enable natural turn-taking in two-speaker scenarios by combining primary speaker segmentation with hierarchical End-of-Turn (EOT) detection. To operate robustly in multi-speaker environments, the system continuously identifies and tracks the primary user, ensuring that downstream EOT decisions are not confounded by background conversations. The tracked activity segments are fed to a hierarchical, causal EOT model that predicts the immediate conversational state by independently analyzing per-speaker speech features from both the primary speaker and the bot. Simultaneously, the model anticipates near-future states ($t{+}10/20/30$\,ms) through probabilistic predictions that are aware of the conversation partner's speech. Task-specific knowledge distillation compresses wav2vec~2.0 representations (768\,D) into a compact MFCC-based student (32\,D) for efficient deployment. The system achieves 82\% multi-class frame-level F1 and 70.6\% F1 on Backchannel detection, with 69.3\% F1 on a binary Final vs.\ Others task. On an end-to-end turn-detection benchmark, our model reaches 87.7\% recall vs.\ 58.9\% for Smart Turn~v3 while keeping a median detection latency of 36\,ms versus 800--1300\,ms. Despite using only 1.14\,M parameters, the proposed model matches or exceeds transformer-based baselines while substantially reducing latency and memory footprint, making it suitable for edge deployment.
### Title:
          Beyond Linearity in Attention Projections: The Case for Nonlinear Queries
 - **Authors:** Marko Karbevski
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent algebraic analysis shows that in decoder-only and encoder-only transformers, the Query projection $W_Q$ may be set to identity without noticeable performance deterioration. This is possible because attention depends on $X$ only through the products $XW_Q, XW_K, XW_V$, allowing basis transformations to be absorbed by adjacent layers and propagated through the network. We replace $W_Q \in \mathbb{R}^{d \times d}$ with a nonlinear residual of the form $Q(X) = X + f_\theta(X)$, where $f_\theta$ is a bottleneck MLP with $d^2 + O(d)$ parameters. The identity term anchors the nonlinearity to a known-good prior. Experiments on GPT-3 small style models show consistent improvement over the baseline, comfortably outperforming a model with 12.5% more non-embedding parameters. These results motivate investigation at larger scales and across modalities.
### Title:
          Layout-Guided Controllable Pathology Image Generation with In-Context Diffusion Transformers
 - **Authors:** Yuntao Shou, Xiangyong Cao, Qian Zhao, Deyu Meng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Controllable pathology image synthesis requires reliable regulation of spatial layout, tissue morphology, and semantic detail. However, existing text-guided diffusion models offer only coarse global control and lack the ability to enforce fine-grained structural constraints. Progress is further limited by the absence of large datasets that pair patch-level spatial layouts with detailed diagnostic descriptions, since generating such annotations for gigapixel whole-slide images is prohibitively time-consuming for human experts. To overcome these challenges, we first develop a scalable multi-agent LVLM annotation framework that integrates image description, diagnostic step extraction, and automatic quality judgment into a coordinated pipeline, and we evaluate the reliability of the system through a human verification process. This framework enables efficient construction of fine-grained and clinically aligned supervision at scale. Building on the curated data, we propose In-Context Diffusion Transformer (IC-DiT), a layout-aware generative model that incorporates spatial layouts, textual descriptions, and visual embeddings into a unified diffusion transformer. Through hierarchical multimodal attention, IC-DiT maintains global semantic coherence while accurately preserving structural and morphological details. Extensive experiments on five histopathology datasets show that IC-DiT achieves higher fidelity, stronger spatial controllability, and better diagnostic consistency than existing methods. In addition, the generated images serve as effective data augmentation resources for downstream tasks such as cancer classification and survival analysis.
### Title:
          Combining Microscopy Data and Metadata for Reconstruction of Cellular Traction Forces Using a Hybrid Vision Transformer-U-Net
 - **Authors:** Yunfei Huang, Elena Van der Vorst, Alexander Richard, Benedikt Sabass
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traction force microscopy (TFM) is a widely used technique for quantifying the forces that cells exert on their surrounding extracellular matrix. Although deep learning methods have recently been applied to TFM data analysis, several challenges remain-particularly achieving reliable inference across multiple spatial scales and integrating additional contextual information such as cell type to improve accuracy. In this study, we propose ViT+UNet, a robust deep learning architecture that integrates a U-Net with a Vision Transformer. Our results demonstrate that this hybrid model outperforms both standalone U-Net and Vision Transformer architectures in predicting traction force fields. Furthermore, ViT+UNet exhibits superior generalization across diverse spatial scales and varying noise levels, enabling its application to TFM datasets obtained from different experimental setups and imaging systems. By appropriately structuring the input data, our approach also allows the inclusion of metadata, in our case cell-type information, to enhance prediction specificity and accuracy.
### Title:
          Distance-aware Soft Prompt Learning for Multimodal Valence-Arousal Estimation
 - **Authors:** Byeongjin Jung, Chanyeong Park, Sejoon Lim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Valence-arousal (VA) estimation is crucial for capturing the nuanced nature of human emotions in naturalistic environments. While pre-trained Vision-Language models like CLIP have shown remarkable semantic alignment capabilities, their application in continuous regression tasks is often limited by the discrete nature of text prompts. In this paper, we propose a novel multimodal framework for VA estimation that introduces Distance-aware Soft Prompt Learning to bridge the gap between semantic space and continuous dimensions. Specifically, we partition the VA space into a 3X3 grid, defining nine emotional regions, each associated with distinct textual descriptions. Rather than a hard categorization, we employ a Gaussian kernel to compute soft labels based on the Euclidean distance between the ground truth coordinates and the region centers, allowing the model to learn fine-grained emotional transitions. For multimodal integration, our architecture utilizes a CLIP image encoder and an Audio Spectrogram Transformer (AST) to extract robust spatial and acoustic features. These features are temporally modeled via Gated Recurrent Units (GRUs) and integrated through a hierarchical fusion scheme that sequentially combines cross-modal attention for alignment and gated fusion for adaptive refinement. Experimental results on the Aff-Wild2 dataset demonstrate that our proposed semantic-guided approach significantly enhances the accuracy of VA estimation, achieving competitive performance in unconstrained ``in-the-wild'' scenarios.
### Title:
          Diffusion Models Generalize but Not in the Way You Might Think
 - **Authors:** Tim Kaiser, Markus Kollmann
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Standard evaluation metrics suggest that Denoising Diffusion Models based on U-Net or Transformer architectures generalize well in practice. However, as it can be shown that an optimal Diffusion Model fully memorizes the training data, the model error determines generalization. Here, we show that although sufficiently large denoiser models show increasing memorization of the training set with increasing training time, the resulting denoising trajectories do not follow this trend. Our experiments indicate that the reason for this observation is rooted in the fact that overfitting occurs at intermediate noise levels, but the distribution of noisy training data at these noise levels has little overlap with denoising trajectories during inference. To gain more insight, we make use of a 2D toy diffusion model to show that overfitting at intermediate noise levels is largely determined by model error and the density of the data support. While the optimal denoising flow field localizes sharply around training samples, sufficient model error or dense support on the data manifold suppresses exact recall, yielding a smooth, generalizing flow field. To further support our results, we investigate how several factors, such as training time, model size, dataset size, condition granularity, and diffusion guidance, influence generalization behavior.
### Title:
          From Gradients to Riccati Geometry: Kalman World Models for Single-Pass Learning
 - **Authors:** Andrew Kiruluta
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Backpropagation dominates modern machine learning, yet it is not the only principled method for optimizing dynamical systems. We propose Kalman World Models (KWM), a class of learned state-space models trained via recursive Bayesian filtering rather than reverse-mode automatic differentiation. Instead of gradient descent updates, we replace parameter learning with Kalman-style gain adaptation. Training becomes online filtering; error signals become innovations. We further extend this framework to transformer-based large language models (LLMs), where internal activations are treated as latent dynamical states corrected via innovation terms. This yields a gradient-free training and adaptation paradigm grounded in control theory. We derive stability conditions, analyze computational complexity, and provide empirical results on sequence modeling tasks demonstrating competitive performance with improved robustness and continual adaptation properties.
### Title:
          A Deformable Attention-Based Detection Transformer with Cross-Scale Feature Fusion for Industrial Coil Spring Inspection
 - **Authors:** Matteo Rossi, Pony Matt
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated visual inspection of locomotive coil springs presents significant challenges due to the morphological diversity of surface defects, substantial scale variations, and complex industrial backgrounds. This paper proposes MSD-DETR (Multi-Scale Deformable Detection Transformer), a novel detection framework that addresses these challenges through three key innovations: (1) a structural re-parameterization strategy that decouples training-time multi-branch topology from inference-time efficiency, enhancing feature extraction while maintaining real-time performance; (2) a deformable attention mechanism that enables content-adaptive spatial sampling, allowing dynamic focus on defect-relevant regions regardless of morphological irregularity; and (3) a cross-scale feature fusion architecture incorporating GSConv modules and VoVGSCSP blocks for effective multi-resolution information aggregation. Comprehensive experiments on a real-world locomotive coil spring dataset demonstrate that MSD-DETR achieves 92.4\% mAP@0.5 at 98 FPS, outperforming state-of-the-art detectors including YOLOv8 (+3.1\% mAP) and the baseline RT-DETR (+2.8\% mAP) while maintaining comparable inference speed, establishing a new benchmark for industrial coil spring quality inspection.
### Title:
          Improving Channel Estimation via Multimodal Diffusion Models with Flow Matching
 - **Authors:** Xiaotian Fan, Xingyu Zhou, Le Liang, Xiao Li, Shi Jin
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep generative models offer a powerful alternative to conventional channel estimation by learning complex channel distributions. By integrating the rich environmental information available in modern sensing-aided networks, this paper proposes MultiCE-Flow, a multimodal channel estimation framework based on flow matching and diffusion transformer (DiT). We design a specialized multimodal perception module that fuses LiDAR, camera, and location data into a semantic condition, while treating sparse pilots as a structural condition. These conditions guide a DiT backbone to reconstruct high-fidelity channels. Unlike standard diffusion models, we employ flow matching to learn a linear trajectory from noise to data, enabling efficient one-step sampling. By leveraging environmental semantics, our method mitigates the ill-posed nature of estimation with sparse pilots. Extensive experiments demonstrate that MultiCE-Flow consistently outperforms traditional baselines and existing generative models. Notably, it exhibits superior robustness to out-of-distribution scenarios and varying pilot densities, making it suitable for environment-aware communication systems.
### Title:
          Scalable Machines with Intrinsic Higher Mental-State Dynamics
 - **Authors:** Ahsan Adeel, M. Bilal
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Drawing on recent breakthroughs in cellular neurobiology and detailed biophysical modeling linking neocortical pyramidal neurons to distinct mental-state regimes, this work introduces a mathematically grounded formulation showing how models (e.g., Transformers) can implement computational principles underlying awake imaginative thought to pre-select relevant information before attention is applied via triadic modulation loops among queries ($Q$), keys ($K$), and values ($V$).~Scalability experiments on ImageNet-1K, benchmarked against a standard Vision Transformer (ViT), demonstrate significantly faster learning with reduced computational demand (fewer heads, layers, and tokens), consistent with our prior findings in reinforcement learning and language modeling. The approach operates at approximately $\mathcal{O}(N)$ complexity with respect to the number of input tokens $N$.
### Title:
          Reconciling In-Context and In-Weight Learning via Dual Representation Space Encoding
 - **Authors:** Guanyu Chen, Ruichen Wang, Tianren Zhang, Feng Chen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In-context learning (ICL) is a valuable capability exhibited by Transformers pretrained on diverse sequence tasks. However, previous studies have observed that ICL often conflicts with the model's inherent in-weight learning (IWL) ability. By examining the representation space learned by a toy model in synthetic experiments, we identify the shared encoding space for context and samples in Transformers as a potential source of this conflict. To address this, we modify the model architecture to separately encode the context and samples into two distinct spaces: a task representation space and a sample representation space. We model these two spaces under a simple yet principled framework, assuming a linear representational structure and treating them as a pair of dual spaces. Both theoretical analysis and empirical results demonstrate the effectiveness of our proposed architecture, CoQE, in the single-value answer setting. It not only enhances ICL performance through improved representation learning, but also successfully reconciles ICL and IWL capabilities across synthetic few-shot classification and a newly designed pseudo-arithmetic task. Code: this https URL
### Title:
          The AI Fiction Paradox
 - **Authors:** Katherine Elkins
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI development has a fiction dependency problem: models are built on massive corpora of modern fiction and desperately need more of it, yet they struggle to generate it. I term this the AI-Fiction Paradox and it is particularly startling because in machine learning, training data typically determines output quality. This paper offers a theoretically precise account of why fiction resists AI generation by identifying three distinct challenges for current architectures. First, fiction depends on what I call narrative causation, a form of plot logic where events must feel both surprising in the moment and retrospectively inevitable. This temporal paradox fundamentally conflicts with the forward-generation logic of transformer architectures. Second, I identify an informational revaluation challenge: fiction systematically violates the computational assumption that informational importance aligns with statistical salience, requiring readers and models alike to retrospectively reweight the significance of narrative details in ways that current attention mechanisms cannot perform. Third, drawing on over seven years of collaborative research on sentiment arcs, I argue that compelling fiction requires multi-scale emotional architecture, the orchestration of sentiment at word, sentence, scene, and arc levels simultaneously. Together, these three challenges explain both why AI companies have risked billion-dollar lawsuits for access to modern fiction and why that fiction remains so difficult to replicate. The analysis also raises urgent questions about what happens when these challenges are overcome. Fiction concentrates uniquely powerful cognitive and emotional patterns for modeling human behavior, and mastery of these patterns by AI systems would represent not just a creative achievement but a potent vehicle for human manipulation at scale.
### Title:
          Causal Attribution via Activation Patching
 - **Authors:** Amirmohammad Izadi, Mohammadali Banayeeanzade, Alireza Mirrokni, Hosein Hasani, Mobin Bagherian, Faridoun Mehri, Mahdieh Soleymani Baghshah
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Attribution methods for Vision Transformers (ViTs) aim to identify image regions that influence model predictions, but producing faithful and well-localized attributions remains challenging. Existing gradient-based and perturbation-based techniques often fail to isolate the causal contribution of internal representations associated with individual image patches. The key challenge is that class-relevant evidence is formed through interactions between patch tokens across layers, and input-level perturbations can be poor proxies for patch importance, since they may fail to reconstruct the internal evidence actually used by the model. We propose Causal Attribution via Activation Patching (CAAP), which estimates the contribution of individual image patches to the ViT's prediction by directly intervening on internal activations rather than using learned masks or synthetic perturbation patterns. For each patch, CAAP inserts the corresponding source-image activations into a neutral target context over an intermediate range of layers and uses the resulting target-class score as the attribution signal. The resulting attribution map reflects the causal effect of patch-associated internal representations on the model's prediction. The causal intervention serves as a principled measure of patch influence by capturing class-relevant evidence after initial representation formation, while avoiding late-layer global mixing that can reduce spatial specificity. Across multiple ViT backbones and standard metrics, CAAP significantly outperforms existing methods and produces more faithful and localized attributions.
### Title:
          Privacy Preserving Topic-wise Sentiment Analysis of the Iran Israel USA Conflict Using Federated Transformer Models
 - **Authors:** Md Saiful Islam, Tanjim Taharat Aurpa, Sharad Hasan, Farzana Akter
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The recent escalation of the Iran Israel USA conflict in 2026 has triggered widespread global discussions across social media platforms. As people increasingly use these platforms for expressing opinions, analyzing public sentiment from these discussions can provide valuable insights into global public perception. This study aims to analyze global public sentiment regarding the Iran Israel USA conflict by mining user-generated comments from YouTube news channels. The work contributes to public opinion analysis by introducing a privacy preserving framework that combines topic wise sentiment analysis with modern deep learning techniques and Federated Learning. To achieve this, approximately 19,000 YouTube comments were collected from major international news channels and preprocessed to remove noise and normalize text. Sentiment labels were initially generated using the VADER sentiment analyzer and later validated through manual inspection to improve reliability. Latent Dirichlet Allocation (LDA) was applied to identify key discussion topics related to the conflict. Several transformer-based models, including BERT, RoBERTa, XLNet, DistilBERT, ModernBERT, and ELECTRA, were fine tuned for sentiment classification. The best-performing model was further integrated into a federated learning environment to enable distributed training by preserving user data privacy. Additionally, Explainable Artificial Intelligence (XAI) techniques using SHAP were applied to interpret model predictions and identify influential words affecting sentiment classification. Experimental results demonstrate that transformer models perform effectively, and among them, ELECTRA achieved the best performance with 91.32% accuracy. The federated learning also maintained strong performance while preserving privacy, achieving 89.59% accuracy in a two client configuration.
### Title:
          FMS$^2$: Unified Flow Matching for Segmentation and Synthesis of Thin Structures
 - **Authors:** Babak Asadi, Peiyang Wu, Mani Golparvar-Fard, Viraj Shah, Ramez Hajj
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Segmenting thin structures like infrastructure cracks and anatomical vessels is a task hampered by topology-sensitive geometry, high annotation costs, and poor generalization across domains. Existing methods address these challenges in isolation. We propose FMS$^2$, a flow-matching framework with two modules. (1) SegFlow is a 2.96M-parameter segmentation model built on a standard encoder-decoder backbone that recasts prediction as continuous image $\rightarrow$ mask transport. It learns a time-indexed velocity field with a flow-matching regression loss and outputs the mask via ODE integration, rather than supervising only end-state logits. This trajectory-level supervision improves thin-structure continuity and sharpness, compared with tuned topology-aware loss baselines, without auxiliary topology heads, post-processing, or multi-term loss engineering. (2) SynFlow is a mask-conditioned mask $\rightarrow$ image generator that produces pixel-aligned synthetic image-mask pairs. It injects mask geometry at multiple scales and emphasizes boundary bands via edge-aware gating, while a controllable mask generator expands sparsity, width, and branching regimes. On five crack and vessel benchmarks, SegFlow alone outperforms strong CNN, Transformer, Mamba, and generative baselines, improving the volumetric metric (mean IoU) from 0.511 to 0.599 (+17.2%) and reducing the topological metric (Betti matching error) from 82.145 to 51.524 (-37.3%). When training with limited labels, augmenting SegFlow with SynFlow-generated pairs recovers near-full performance using 25% of real annotations and improves cross-domain IoU by 0.11 on average. Unlike classical data augmentation that promotes invariance via label-preserving transforms, SynFlow provides pixel-aligned paired supervision with controllable structural shifts (e.g., sparsity, width, branching), which is particularly effective under domain shift.
### Title:
          PDE-SSM: A Spectral State Space Approach to Spatial Mixing in Diffusion Transformers
 - **Authors:** Eshed Gal, Moshe Eliasof, Siddharth Rout, Eldad Haber
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The success of vision transformers-especially for generative modeling-is limited by the quadratic cost and weak spatial inductive bias of self-attention. We propose PDE-SSM, a spatial state-space block that replaces attention with a learnable convection-diffusion-reaction partial differential equation. This operator encodes a strong spatial prior by modeling information flow via physically grounded dynamics rather than all-to-all token interactions. Solving the PDE in the Fourier domain yields global coupling with near-linear complexity of $O(N \log N)$, delivering a principled and scalable alternative to attention. We integrate PDE-SSM into a flow-matching generative model to obtain the PDE-based Diffusion Transformer PDE-SSM-DiT. Empirically, PDE-SSM-DiT matches or exceeds the performance of state-of-the-art Diffusion Transformers while substantially reducing compute. Our results show that, analogous to 1D settings where SSMs supplant attention, multi-dimensional PDE operators provide an efficient, inductive-bias-rich foundation for next-generation vision models.
### Title:
          SecDTD: Dynamic Token Drop for Secure Transformers Inference
 - **Authors:** Yifei Cai, Zhuoran Li, Yizhou Feng, Qiao Zhang, Hongyi Wu, Danella Zhao, Chunsheng Xin
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid adoption of Transformer-based AI has been driven by accessible models such as ChatGPT, which provide API-based services for developers and businesses. However, as these online inference services increasingly handle sensitive inputs, privacy concerns have emerged as a significant challenge. To address this, secure inference frameworks have been proposed, but their high computational and communication overhead often limit practical deployment. In plaintext settings, token drop is an effective technique for reducing inference cost; however, our analysis reveals that directly applying such methods to ciphertext scenarios is suboptimal due to distinct cost distributions in secure computation. We propose SecDTD, a dynamic token drop scheme tailored for secure Transformer inference. SecDTD advances token drop by shifting the dropping to earlier inference stages, effectively reducing the cost of key components such as Softmax. To support this, we introduce two core techniques. Max-Centric Normalization (MCN): A novel, Softmax-independent scoring method that enables early token drop with minimal overhead and improved normalization, supporting more aggressive dropping without accuracy loss. OMSel: A faster, oblivious median selection protocol that securely identifies the median of importance scores to support token drop. Compared to existing sorting-based methods, OMSel achieves a 16.9$\times$ speedup while maintaining security, obliviousness and randomness. We evaluate SecDTD through 48 experiments across eight GLUE datasets under various network settings using the BOLT and BumbleBee frameworks. SecDTD achieves 4.47 times end-to-end inference acceleration without degradation in accuracy.
### Title:
          Quantum-Enhanced Vision Transformer for Flood Detection using Remote Sensing Imagery
 - **Authors:** Soumyajit Maity, Behzad Ghanbarian
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable flood detection is critical for disaster management, yet classical deep learning models often struggle with the high-dimensional, nonlinear complexities inherent in remote sensing data. To mitigate these limitations, we introduced a novel Quantum-Enhanced Vision Transformer (ViT) that synergizes the global context-awareness of transformers with the expressive feature extraction capabilities of quantum computing. Using remote sensing imagery, we developed a hybrid architecture that processes inputs through parallel pathways, a ViT backbone and a quantum branch utilizing a 4-qubit parameterized quantum circuit for localized feature mapping. These distinct representations were fused to optimize binary classification. Results showed that the proposed hybrid model significantly outperformed a classical ViT baseline, increased overall accuracy from 84.48% to 94.47% and the F1-score from 0.841 to 0.944. Notably, the quantum integration substantially improved discriminative power in complex terrains for both class. These findings validate the potential of quantum-classical hybrid models to enhance precision in hydrological monitoring and earth observation applications.
### Title:
          MeTok: An Efficient Meteorological Tokenization with Hyper-Aligned Group Learning for Precipitation Nowcasting
 - **Authors:** Qizhao Jin, Xianhuang Xu, Yong Cao, Shiming Xiang, Xinyu Xiao
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recently, Transformer-based architectures have advanced meteorological prediction. However, this position-centric tokenizer conflicts with the core principle of meteorological systems, where the weather phenomena undoubtedly involve synergistic interactions among multiple elements while positional information constitutes merely a component of the boundary conditions. This paper focuses primarily on the task of precipitation nowcasting and develops an efficient distribution-centric Meteorological Tokenization (MeTok) scheme, which spatially sequences to group similar meteorological features. Based on the rearrangement, realigned group learning enhances robustness across precipitation patterns, especially extreme ones. Specifically, we introduce the Hyper-Aligned Grouping Transformer (HyAGTransformer) with two key improvements: 1) The Grouping Attention (GA) mechanism uses MeTok to enable self-aligned learning of features from different precipitation patterns; 2) The Neighborhood Feed-Forward Network (N-FFN) integrates adjacent group features, aggregating contextual information to boost patch embedding discriminability. Experiments on the ERA5 dataset for 6-hour forecasts show our method improves the IoU metric by at least 8.2% in extreme precipitation prediction compared to other methods. Additionally, it gains performance with more training data and increased parameters, demonstrating scalability, stability, and superiority over traditional methods.
### Title:
          PA-Net: Precipitation-Adaptive Mixture-of-Experts for Long-Tail Rainfall Nowcasting
 - **Authors:** Xinyu Xiao, Sen Lei, Eryun Liu, Shiming Xiang, Hao Li, Cheng Yuan, Yuan Qi, Qizhao Jin
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Precipitation nowcasting is vital for flood warning, agricultural management, and emergency response, yet two bottlenecks persist: the prohibitive cost of modeling million-scale spatiotemporal tokens from multi-variate atmospheric fields, and the extreme long-tailed rainfall distribution where heavy-to-torrential events -- those of greatest societal impact -- constitute fewer than 0.1% of all samples. We propose the Precipitation-Adaptive Network (PA-Net), a Transformer framework whose computational budget is explicitly governed by rainfall intensity. Its core component, Precipitation-Adaptive MoE (PA-MoE), dynamically scales the number of activated experts per token according to local precipitation magnitude, channeling richer representational capacity toward the rare yet critical heavy-rainfall tail. A Dual-Axis Compressed Latent Attention mechanism factorizes spatiotemporal attention with convolutional reduction to manage massive context lengths, while an intensity-aware training protocol progressively amplifies learning signals from extreme-rainfall samples. Experiment on ERA5 demonstrate consistent improvements over state-of-the-art baselines, with particularly significant gains in heavy-rain and rainstorm regimes.
### Title:
          TransDex: Pre-training Visuo-Tactile Policy with Point Cloud Reconstruction for Dexterous Manipulation of Transparent Objects
 - **Authors:** Fengguan Li, Yifan Ma, Chen Qian, Wentao Rao, Weiwei Shang
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dexterous manipulation enables complex tasks but suffers from self-occlusion, severe depth noise, and depth information loss when manipulating transparent objects. To solve this problem, this paper proposes TransDex, a 3D visuo-tactile fusion motor policy based on point cloud reconstruction pre-training. Specifically, we first propose a self-supervised point cloud reconstruction pre-training approach based on Transformer. This method accurately recovers the 3D structure of objects from interactive point clouds of dexterous hands, even when random noise and large-scale masking are added. Building on this, TransDex is constructed in which perceptual encoding adopts a fine-grained hierarchical scheme and multi-round attention mechanisms adaptively fuse features of the robotic arm and dexterous hand to enable differentiated motion prediction. Results from transparent object manipulation experiments conducted on a real robotic system demonstrate that TransDex outperforms existing baseline methods. Further analysis validates the generalization capabilities of TransDex and the effectiveness of its individual components.
### Title:
          GradMem: Learning to Write Context into Memory with Test-Time Gradient Descent
 - **Authors:** Yuri Kuratov, Matvey Kairov, Aydar Bulatov, Ivan Rodkin, Mikhail Burtsev
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many large language model applications require conditioning on long contexts. Transformers typically support this by storing a large per-layer KV-cache of past activations, which incurs substantial memory overhead. A desirable alternative is ompressive memory: read a context once, store it in a compact state, and answer many queries from that state. We study this in a context removal setting, where the model must generate an answer without access to the original context at inference time. We introduce GradMem, which writes context into memory via per-sample test-time optimization. Given a context, GradMem performs a few steps of gradient descent on a small set of prefix memory tokens while keeping model weights frozen. GradMem explicitly optimizes a model-level self-supervised context reconstruction loss, resulting in a loss-driven write operation with iterative error correction, unlike forward-only methods. On associative key--value retrieval, GradMem outperforms forward-only memory writers with the same memory size, and additional gradient steps scale capacity much more effectively than repeated forward writes. We further show that GradMem transfers beyond synthetic benchmarks: with pretrained language models, it attains competitive results on natural language tasks including bAbI and SQuAD variants, relying only on information encoded in memory.
### Title:
          Scribe Verification in Chinese manuscripts using Siamese, Triplet, and Vision Transformer Neural Networks
 - **Authors:** Dimitrios-Chrysovalantis Liakopoulos, Yanbo Zhang, Chongsheng Zhang, Constantine Kotropoulos
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The paper examines deep learning models for scribe verification in Chinese manuscripts. That is, to automatically determine whether two manuscript fragments were written by the same scribe using deep metric learning methods. Two datasets were used: the Tsinghua Bamboo Slips Dataset and a selected subset of the Multi-Attribute Chinese Calligraphy Dataset, focusing on the calligraphers with a large number of samples. Siamese and Triplet neural network architectures are implemented, including convolutional and Transformer-based models. The experimental results show that the MobileNetV3+ Custom Siamese model trained with contrastive loss achieves either the best or the second-best overall accuracy and area under the Receiver Operating Characteristic Curve on both datasets.
### Title:
          Towards Stable Self-Supervised Object Representations in Unconstrained Egocentric Video
 - **Authors:** Yuting Tan, Xilong Cheng, Yunxiao Qin, Zhengnan Li, Jingjing Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Humans develop visual intelligence through perceiving and interacting with their environment - a self-supervised learning process grounded in egocentric experience. Inspired by this, we ask how can artificial systems learn stable object representations from continuous, uncurated first-person videos without relying on manual annotations. This setting poses challenges of separating, recognizing, and persistently tracking objects amid clutter, occlusion, and ego-motion. We propose EgoViT, a unified vision Transformer framework designed to learn stable object representations from unlabeled egocentric video. EgoViT bootstraps this learning process by jointly discovering and stabilizing "proto-objects" through three synergistic mechanisms: (1) Proto-object Learning, which uses intra-frame distillation to form discriminative representations; (2) Depth Regularization, which grounds these representations in geometric structure; and (3) Teacher-Filtered Temporal Consistency, which enforces identity over time. This creates a virtuous cycle where initial object hypotheses are progressively refined into stable, persistent representations. The framework is trained end-to-end on unlabeled first-person videos and exhibits robustness to geometric priors of varied origin and quality. On standard benchmarks, EgoViT achieves +8.0% CorLoc improvement in unsupervised object discovery and +4.8% mIoU improvement in semantic segmentation, demonstrating its potential to lay a foundation for robust visual abstraction in embodied intelligence.
### Title:
          OpenCOOD-Air: Prompting Heterogeneous Ground-Air Collaborative Perception with Spatial Conversion and Offset Prediction
 - **Authors:** Xianke Wu, Songlin Bai, Chengxiang Li, Zhiyao Luo, Yulin Tian, Fenghua Zhu, Yisheng Lv, Yonglin Tian
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Vehicle-to-Vehicle (V2V) collaboration extends sensing ranges through multi-agent data sharing, its reliability remains severely constrained by ground-level occlusions and the limited perspective of chassis-mounted sensors, which often result in critical perception blind spots. We propose OpenCOOD-Air, a novel framework that integrates UAVs as extensible platforms into V2V collaborative perception to overcome these constraints. To mitigate gradient interference from ground-air domain gaps and data sparsity, we adopt a transfer learning strategy to fine-tune UAV weights from pre-trained V2V models. To prevent the spatial information loss inherent in this transition, we formulate ground-air collaborative perception as a heterogeneous integration task with explicit altitude supervision and introduce a Cross-Domain Spatial Converter (CDSC) and a Spatial Offset Prediction Transformer (SOPT). Furthermore, we present the OPV2V-Air benchmark to validate the transition from V2V to Vehicle-to-Vehicle-to-UAV. Compared to state-of-the-art methods, our approach improves 2D and 3D AP@0.7 by 4% and 7%, respectively.
### Title:
          Discriminative Flow Matching Via Local Generative Predictors
 - **Authors:** Om Govind Jha, Manoj Bamniya, Ayon Borthakur
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traditional discriminative computer vision relies predominantly on static projections, mapping input features to outputs in a single computational step. Although efficient, this paradigm lacks the iterative refinement and robustness inherent in biological vision and modern generative modelling. In this paper, we propose Discriminative Flow Matching, a framework that reformulates classification and object detection as a conditional transport process. By learning a vector field that continuously transports samples from a simple noise distribution toward a task-aligned target manifold -- such as class embeddings or bounding box coordinates -- we are at the interface between generative and discriminative learning. Our method attaches multiple independent flow predictors to a shared backbone. These predictors are trained using local flow matching objectives, where gradients are computed independently for each block. We formulate this approach for standard image classification and extend it to the complex task of object detection, where targets are high-dimensional and spatially distributed. This architecture provides the flexibility to update blocks either sequentially to minimise activation memory or in parallel to suit different hardware constraints. By aggregating the predictions from these independent flow predictors, our framework enables robust, generative-inspired inference across diverse architectures, including CNNs and vision transformers.
### Title:
          Bidirectional Cross-Attention Fusion of High-Res RGB and Low-Res HSI for Multimodal Automated Waste Sorting
 - **Authors:** Jonas V. Funk, Lukas Roming, Andreas Michel, Paul Bäcker, Georg Maier, Thomas Längle, Markus Klute
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Growing waste streams and the transition to a circular economy require efficient automated waste sorting. In industrial settings, materials move on fast conveyor belts, where reliable identification and ejection demand pixel-accurate segmentation. RGB imaging delivers high-resolution spatial detail, which is essential for accurate segmentation, but it confuses materials that look similar in the visible spectrum. Hyperspectral imaging (HSI) provides spectral signatures that separate such materials, yet its lower spatial resolution limits detail. Effective waste sorting therefore needs methods that fuse both modalities to exploit their complementary strengths. We present Bidirectional Cross-Attention Fusion (BCAF), which aligns high-resolution RGB with low-resolution HSI at their native grids via localized, bidirectional cross-attention, avoiding pre-upsampling or early spectral collapse. BCAF uses two independent backbones: a standard Swin Transformer for RGB and an HSI-adapted Swin backbone that preserves spectral structure through 3D tokenization with spectral self-attention. We also analyze trade-offs between RGB input resolution and the number of HSI spectral slices. Although our evaluation targets RGB-HSI fusion, BCAF is modality-agnostic and applies to co-registered RGB with lower-resolution, high-channel auxiliary sensors. On the benchmark SpectralWaste dataset, BCAF achieves state-of-the-art performance of 76.4% mIoU at 31 images/s and 75.4% mIoU at 55 images/s. We further evaluate a novel industrial dataset: K3I-Cycling (first RGB subset already released on Fordatis). On this dataset, BCAF reaches 62.3% mIoU for material segmentation (paper, metal, plastic, etc.) and 66.2% mIoU for plastic-type segmentation (PET, PP, HDPE, LDPE, PS, etc.).
### Title:
          USIS-PGM: Photometric Gaussian Mixtures for Underwater Salient Instance Segmentation
 - **Authors:** Lin Hong, Xiangtong Yao, Mürüvvet Bozkurt, Xin Wang, Fumin Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Underwater salient instance segmentation (USIS) is crucial for marine robotic systems, as it enables both underwater salient object detection and instance-level mask prediction for visual scene understanding. Compared with its terrestrial counterpart, USIS is more challenging due to the underwater image degradation. To address this issue, this paper proposes USIS-PGM, a single-stage framework for USIS. Specifically, the encoder enhances boundary cues through a frequency-aware module and performs content-adaptive feature reweighting via a dynamic weighting module. The decoder incorporates a Transformer-based instance activation module to better distinguish salient instances. In addition, USIS-PGM employs multi-scale Gaussian heatmaps generated from ground-truth masks through Photometric Gaussian Mixture (PGM) to supervise intermediate decoder features, thereby improving salient instance localization and producing more structurally coherent mask predictions. Experimental results demonstrate the superiority and practical applicability of the proposed USIS-PGM model.
### Title:
          Human-like Object Grouping in Self-supervised Vision Transformers
 - **Authors:** Hossein Adeli, Seoyoung Ahn, Andrew Luo, Mengmi Zhang, Nikolaus Kriegeskorte, Gregory Zelinsky
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Neurons and Cognition (q-bio.NC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision foundation models trained with self-supervised objectives achieve strong performance across diverse tasks and exhibit emergent object segmentation properties. However, their alignment with human object perception remains poorly understood. Here, we introduce a behavioral benchmark in which participants make same/different object judgments for dot pairs on naturalistic scenes, scaling up a classical psychophysics paradigm to over 1000 trials. We test a diverse set of vision models using a simple readout from their representations to predict subjects' reaction times. We observe a steady improvement across model generations, with both architecture and training objective contributing to alignment, and transformer-based models trained with the DINO self-supervised objective showing the strongest performance. To investigate the source of this improvement, we propose a novel metric to quantify the object-centric component of representations by measuring patch similarity within and between objects. Across models, stronger object-centric structure predicts human segmentation behavior more accurately. We further show that matching the Gram matrix of supervised transformer models, capturing similarity structure across image patches, with that of a self-supervised model through distillation improves their alignment with human behavior, converging with the prior finding that Gram anchoring improves DINOv3's feature quality. Together, these results demonstrate that self-supervised vision models capture object structure in a behaviorally human-like manner, and that Gram matrix structure plays a role in driving perceptual alignment.
### Title:
          Probing neural audio codecs for distinctions among English nuclear tunes
 - **Authors:** Juan Pablo Vigneaux, Jennifer Cole
 - **Subjects:** Subjects:
Sound (cs.SD); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 State-of-the-art spoken dialogue models (Défossez et al. 2024; Schalkwyk et al. 2025) use neural audio codecs to "tokenize" audio signals into a lower-frequency stream of vectorial latent representations, each quantized using a hierarchy of vector codebooks. A transformer layer allows these representations to reflect some time- and context-dependent patterns. We train probes on labeled audio data from Cole et al. (2023) to test whether the pitch trajectories that characterize English phrase-final (nuclear) intonational tunes are among these patterns. Results: Linear probes trained on the unquantized latents or some of the associated codewords yield above-chance accuracy in distinguishing eight phonologically specified nuclear tunes with monotonal pitch accents (top average test accuracy (TATA): 0.31) and the five clusters of these tunes that are robust in human speech production and perception (TATA: 0.45). Greater accuracy (TATAs: 0.74-0.89) is attained for binary distinctions between classes of rising vs. falling tunes, respectively used for questions and assertions. Information about tunes is spread among all codebooks, which calls into question a distinction between 'semantic' and 'acoustic' codebooks found in the literature. Accuracies improve with nonlinear probes, but discrimination among the five clusters remains far from human performance, suggesting a fundamental limitation of current codecs.
### Title:
          NepTam: A Nepali-Tamang Parallel Corpus and Baseline Machine Translation Experiments
 - **Authors:** Rupak Raj Ghimire, Bipesh Subedi, Balaram Prasain, Prakash Poudyal, Praveen Acharya, Nischal Karki, Rupak Tiwari, Rishikesh Kumar Sharma, Jenny Poudel, Bal Krishna Bal
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern Translation Systems heavily rely on high-quality, large parallel datasets for state-of-the-art performance. However, such resources are largely unavailable for most of the South Asian languages. Among them, Nepali and Tamang fall into such category, with Tamang being among the least digitally resourced languages in the region. This work addresses the gap by developing NepTam20K, a 20K gold standard parallel corpus, and NepTam80K, an 80K synthetic Nepali-Tamang parallel corpus, both sentence-aligned and designed to support machine translation. The datasets were created through a pipeline involving data scraping from Nepali news and online sources, pre-processing, semantic filtering, balancing for tense and polarity (in NepTam20K dataset), expert translation into Tamang by native speakers of the language, and verification by an expert Tamang linguist. The dataset covers five domains: Agriculture, Health, Education and Technology, Culture, and General Communication. To evaluate the dataset, baseline machine translation experiments were carried out using various multilingual pre-trained models: mBART, M2M-100, NLLB-200, and a vanilla Transformer model. The fine-tuning on the NLLB-200 achieved the highest sacreBLEU scores of 40.92 (Nepali-Tamang) and 45.26 (Tamang-Nepali).
### Title:
          Enhancing Mental Health Classification with Layer-Attentive Residuals and Contrastive Feature Learning
 - **Authors:** Menna Elgabry, Ali Hamdi, Khaled Shaban
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The classification of mental health is challenging for a variety of reasons. For one, there is overlap between the mental health issues. In addition, the signs of mental health issues depend on the context of the situation, making classification difficult. Although fine-tuning transformers has improved the performance for mental health classification, standard cross-entropy training tends to create entangled feature spaces and fails to utilize all the information the transformers contain. We present a new framework that focuses on representations to improve mental health classification. This is done using two methods. First, \textbf{layer-attentive residual aggregation} which works on residual connections to to weigh and fuse representations from all transformer layers while maintaining high-level semantics. Second, \textbf{supervised contrastive feature learning} uses temperature-scaled supervised contrastive learning with progressive weighting to increase the geometric margin between confusable mental health problems and decrease class overlap by restructuring the feature space. With a score of \textbf{74.36\%}, the proposed method is the best performing on the SWMH benchmark and outperforms models that are domain-specialized, such as \textit{MentalBERT} and \textit{MentalRoBERTa} by margins of (3.25\% - 2.2\%) and 2.41 recall points over the highest achieving model. These findings show that domain-adaptive pretraining for mental health text classification can be surpassed by carefully designed representation geometry and layer-aware residual integration, which also provide enhanced interpretability through learnt layer importance.
### Title:
          Understanding the Emergence of Seemingly Useless Features in Next-Token Predictors
 - **Authors:** Mark Rofin, Jalal Naghiyev, Michael Hahn
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Trained Transformers have been shown to compute abstract features that appear redundant for predicting the immediate next token. We identify which components of the gradient signal from the next-token prediction objective give rise to this phenomenon, and we propose a method to estimate the influence of those components on the emergence of specific features. After validating our approach on toy tasks, we use it to interpret the origins of the world model in OthelloGPT and syntactic features in a small language model. Finally, we apply our framework to a pretrained LLM, showing that features with extremely high or low influence on future tokens tend to be related to formal reasoning domains such as code. Overall, our work takes a step toward understanding hidden features of Transformers through the lens of their development during training.
### Title:
          The GELATO Dataset for Legislative NER
 - **Authors:** Matthew Flynn, Timothy Obiso, Sam Newman
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper introduces GELATO (Government, Executive, Legislative, and Treaty Ontology), a dataset of U.S. House and Senate bills from the 118th Congress annotated using a novel two-level named entity recognition ontology designed for U.S. legislative texts. We fine-tune transformer-based models (BERT, RoBERTa) of different architectures and sizes on this dataset for first-level prediction. We then use LLMs with optimized prompts to complete the second level prediction. The strong performance of RoBERTa and relatively weak performance of BERT models, as well as the application of LLMs as second-level predictors, support future research in legislative NER or downstream tasks using these model combinations as extraction tools.
### Title:
          DualSwinFusionSeg: Multimodal Martian Landslide Segmentation via Dual Swin Transformer with Multi-Scale Fusion and UNet++
 - **Authors:** Shahriar Kabir, Abdullah Muhammed Amimul Ehsan, Istiak Ahmmed Rifti, Md Kaykobad Reza
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated segmentation of Martian landslides, particularly in tectonically active regions such as Valles Marineris,is important for planetary geology, hazard assessment, and future robotic exploration. However, detecting landslides from planetary imagery is challenging due to the heterogeneous nature of available sensing modalities and the limited number of labeled samples. Each observation combines RGB imagery with geophysical measurements such as digital elevation models, slope maps, thermal inertia, and contextual grayscale imagery, which differ significantly in resolution and statistical properties. To address these challenges, we propose DualSwinFusionSeg, a multimodal segmentation architecture that separates modality-specific feature extraction and performs multi-scale cross-modal fusion. The model employs two parallel Swin Transformer V2 encoders to independently process RGB and auxiliary geophysical inputs, producing hierarchical feature representations. Corresponding features from the two streams are fused at multiple scales and decoded using a UNet++ decoder with dense nested skip connections to preserve fine boundary details. Extensive ablation studies evaluate modality contributions, loss functions, decoder architectures, and fusion strategies. Experiments on the MMLSv2 dataset from the PBVS 2026 Mars-LS Challenge show that modality-specific encoders and simple concatenation-based fusion improve segmentation accuracy under limited training data. The final model achieves 0.867 mIoU and 0.905 F1 on the development benchmark and 0.783 mIoU on the held-out test set, demonstrating strong performance for multimodal planetary surface segmentation.
### Title:
          TransCurriculum: Multi-Dimensional Curriculum Learning for Fast & Stable Locomotion
 - **Authors:** Prakhar Mishra, Amir Hossain Raj, Xuesu Xiao, Dinesh Manocha
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-speed legged locomotion struggles with stability and transfer losses at higher command velocities during deployment. One reason is that most curricula vary difficulty along single axis, for example increase the range of command velocities, terrain difficulty, or domain parameters (e.g. friction or payload mass) using either fixed update rule or instantaneous rewards while ignoring how the history of robot training has evolved. We propose TransCurriculum, a transformer-based multi-dimensional curriculum learning approach for agile quadrupedal locomotion. TransCurriculum adapts to 3 axes, velocity command targets, terrain difficulty, and domain randomization parameters (friction and payload mass). Rather than feeding task reward history directly into the low-level control policy, our formulation exploits it at the curriculum level. A transformer-based teacher retrieves the sequence of rewards and uses it to predict future rewards, success rate, and learning progress to guide expansion of this multidimensional curriculum towards high performing task bins. Finally we validate our approach on the Unitree Go1 robot in simulation (Isaac Gym) and deploy it zero-shot on Go1 hardware. Our TransCurriculum policy achieves a maximum velocity of 6.3 m/s in simulation and outperforms prior curriculum baselines. We tested our TransCurriculum trained policy on terrains (carpets, slopes, tiles, concrete), achieving a forward velocity of 4.1 m/s on carpet surpassing the fastest curriculum methods by 18.8% and achieves maximum zero-shot value among all tested methods. Our multi-dimensional curriculum also reduces the transfer loss to 18% from 27% for command only curriculum, demonstrating the benefits of joint training over velocity, terrain and domain randomization dimension while keeping the task success rate of 80-90% on rigid indoor and outdoor surfaces.
### Title:
          Selective Fine-Tuning of GPT Architectures for Parameter-Efficient Clinical Text Classification
 - **Authors:** Fariba Afrin Irany, Sampson Akwafuo
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid expansion of electronic health record (EHR) systems has generated large volumes of unstructured clinical narratives that contain valuable information for disease identification, patient cohort discovery, and clinical decision support. Extracting structured knowledge from these free-text documents remains challenging because clinical language is highly specialized, labeled datasets are limited, and full fine-tuning of large pretrained language models can require substantial computational resources. Efficient adaptation strategies are therefore essential for practical clinical natural language processing applications. This study proposes a parameter-efficient selective fine-tuning framework for adapting GPT-2 to clinical text classification tasks. Instead of updating the entire pretrained model, the majority of network parameters are frozen, and only the final Transformer block, the final layer normalization module, and a lightweight classification head are updated during training. This design substantially reduces the number of trainable parameters while preserving the contextual representation capabilities learned during pretraining. The proposed approach is evaluated using radiology reports from the MIMIC-IV-Note dataset with automatically derived CheXpert-style labels. Experiments on 50,000 radiology reports demonstrate that selective fine-tuning achieves approximately 91% classification accuracy while updating fewer than 6% of the model parameters. Comparative experiments with head-only training and full-model fine-tuning show that the proposed method provides a favorable balance between predictive performance and computational efficiency. These results indicate that selective fine-tuning offers an efficient and scalable framework for clinical text classification.
### Title:
          DualTSR: Unified Dual-Diffusion Transformer for Scene Text Image Super-Resolution
 - **Authors:** Axi Niu, Kang Zhang, Qingsen Yan, Hao Jin, Jinqiu Sun, Yanning Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scene Text Image Super-Resolution (STISR) aims to restore high-resolution details in low-resolution text images, which is crucial for both human readability and machine recognition. Existing methods, however, often depend on external Optical Character Recognition (OCR) models for textual priors or rely on complex multi-component architectures that are difficult to train and reproduce. In this paper, we introduce DualTSR, a unified end-to-end framework that addresses both issues. DualTSR employs a single multimodal transformer backbone trained with a dual diffusion objective. It simultaneously models the continuous distribution of high-resolution images via Conditional Flow Matching and the discrete distribution of textual content via discrete diffusion. This shared design enables visual and textual information to interact at every layer, allowing the model to infer text priors internally instead of relying on an external OCR module. Compared with prior multi-branch diffusion systems, DualTSR offers a simpler end-to-end formulation with fewer hand-crafted components. Experiments on synthetic Chinese benchmarks and a curated real-world evaluation protocol show that DualTSR achieves strong perceptual quality and text fidelity.
### Title:
          ChArtist: Generating Pictorial Charts with Unified Spatial and Subject Control
 - **Authors:** Shishi Xiao, Tongyu Zhou, David Laidlaw, Gromit Yeuk-Yin Chan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A pictorial chart is an effective medium for visual storytelling, seamlessly integrating visual elements with data charts. However, creating such images is challenging because the flexibility of visual elements often conflicts with the rigidity of chart structures. This process thus requires a creative deformation that maintains both data faithfulness and visual aesthetics. Current methods that extract dense structural cues from natural images (e.g., edge or depth maps) are ill-suited as conditioning signals for pictorial chart generation. We present ChArtist, a domain-specific diffusion model for generating pictorial charts automatically, offering two distinct types of control: 1) spatial control that aligns well with the chart structure, and 2) subject-driven control that respects the visual characteristics of a reference image. To achieve this, we introduce a skeleton-based spatial control representation. This representation encodes only the data-encoding information of the chart, allowing for the easy incorporation of reference visuals without a rigid outline constraint. We implement our method based on the Diffusion Transformer (DiT) and leverage an adaptive position encoding mechanism to manage these two controls. We further introduce Spatially Gated Attention to modulate the interaction between spatial control and subject control. To support the fine-tuning of pre-trained models for this task, we created a large-scale dataset of 30,000 triplets (skeleton, reference image, pictorial chart). We also propose a unified data accuracy metric to evaluate the data faithfulness of the generated charts. We believe this work demonstrates that current generative models can achieve data-driven visual storytelling by moving beyond general-purpose conditions to task-specific representations. Project page: this https URL.
### Title:
          A Real-Time Neuro-Symbolic Ethical Governor for Safe Decision Control in Autonomous Robotic Manipulation
 - **Authors:** Aueaphum Aueawatthanaphisut, Kuepon Aueawatthanaphisut
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ethical decision governance has become a critical requirement for autonomous robotic systems operating in human-centered and safety-sensitive environments. This paper presents a real-time neuro-symbolic ethical governor designed to enable risk-aware supervisory control in autonomous robotic manipulation tasks. The proposed framework integrates transformer-based ethical reasoning with a probabilistic ethical risk field formulation and a threshold-based override control mechanism. language-grounded ethical intent inference capability is learned from natural language task descriptions using a fine-tuned DistilBERT model trained on the ETHICS commonsense dataset. A continuous ethical risk metric is subsequently derived from predicted unsafe action probability, confidence uncertainty, and probabilistic variance to support adaptive decision filtering. The effectiveness of the proposed approach is validated through simulated autonomous robot-arm task scenarios involving varying levels of human proximity and operational hazard. Experimental results demonstrate stable model convergence, reliable ethical risk discrimination, and improved safety-aware decision outcomes without significant degradation of task execution efficiency. The proposed neuro-symbolic architecture further provides enhanced interpretability compared with purely data-driven safety filters, enabling transparent ethical reasoning in real-time control loops. The findings suggest that ethical decision governance can be effectively modeled as a dynamic supervisory risk layer for autonomous robotic systems, with potential applicability to broader cyber-physical and assistive robotics domains.
### Title:
          Agentic DAG-Orchestrated Planner Framework for Multi-Modal, Multi-Hop Question Answering in Hybrid Data Lakes
 - **Authors:** Kirushikesh D B, Manish Kesarwani, Nishtha Madaan, Sameep Mehta, Aldrin Dennis, Siddarth Ajay, Rakesh B R, Renu Rajagopal, Sudheesh Kairali
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Enterprises increasingly need natural language (NL) question answering over hybrid data lakes that combine structured tables and unstructured documents. Current deployed solutions, including RAG-based systems, typically rely on brute-force retrieval from each store and post-hoc merging. Such approaches are inefficient and leaky, and more critically, they lack explicit support for multi-hop reasoning, where a query is decomposed into successive steps (hops) that may traverse back and forth between structured and unstructured sources. We present Agentic DAG-Orchestrated Transformer (this http URL) Planner, a framework for multi-modal, multi-hop question answering, that compiles user NL queries into directed acyclic graph (DAG) execution plans spanning both structured and unstructured stores. The system decomposes queries into parallelizable sub-queries, incorporates schema-aware reasoning, and applies both structural and semantic validation before execution. The execution engine adheres to the generated DAG plan to coordinate concurrent retrieval across heterogeneous sources, route intermediate outputs to dependent sub-queries, and merge final results in strict accordance with the plan's logical dependencies. Advanced caching mechanisms, incorporating paraphrase-aware template matching, enable the system to detect equivalent queries and reuse prior DAG execution plans for rapid re-execution, while the DataOps System addresses validation feedback or execution errors. The proposed framework not only improves accuracy and latency, but also produces explicit evidence trails, enabling verification of retrieved content, tracing of data lineage, and fostering user trust in the system's outputs. On benchmark dataset, this http URL achieves 14.8% absolute gain in correctness and 10.7% in completeness over baselines.
### Title:
          DC-ViT: Modulating Spatial and Channel Interactions for Multi-Channel Images
 - **Authors:** Umar Marikkar, Syed Sameed Husain, Muhammad Awais, Sara Atito
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Training and evaluation in multi-channel imaging (MCI) remains challenging due to heterogeneous channel configurations arising from varying staining protocols, sensor types, and acquisition settings. This heterogeneity limits the applicability of fixed-channel encoders commonly used in general computer vision. Recent Multi-Channel Vision Transformers (MC-ViTs) address this by enabling flexible channel inputs, typically by jointly encoding patch tokens from all channels within a unified attention space. However, unrestricted token interactions across channels can lead to feature dilution, reducing the ability to preserve channel-specific semantics that are critical in MCI data. To address this, we propose Decoupled Vision Transformer (DC-ViT), which explicitly regulates information sharing using Decoupled Self-Attention (DSA), which decomposes token updates into two complementary pathways: spatial updates that model intra-channel structure, and channel-wise updates that adaptively integrate cross-channel information. This decoupling mitigates informational collapse while allowing selective inter-channel interaction. To further exploit these enhanced channel-specific representations, we introduce Decoupled Aggregation (DAG), which allows the model to learn task-specific channel importances. Extensive experiments across three MCI benchmarks demonstrate consistent improvements over existing MC-ViT approaches.
### Title:
          RegFormer++: An Efficient Large-Scale 3D LiDAR Point Registration Network with Projection-Aware 2D Transformer
 - **Authors:** Jiuming Liu, Guangming Wang, Zhe Liu, Chaokang Jiang, Haoang Li, Mengmeng Liu, Tianchen Deng, Marc Pollefeys, Michael Ying Yang, Hesheng Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Although point cloud registration has achieved remarkable advances in object-level and indoor scenes, large-scale LiDAR registration methods has been rarely explored before. Challenges mainly arise from the huge point scale, complex point distribution, and numerous outliers within outdoor LiDAR scans. In addition, most existing registration works generally adopt a two-stage paradigm: They first find correspondences by extracting discriminative local descriptors and then leverage robust estimators (e.g. RANSAC) to filter outliers, which are highly dependent on well-designed descriptors and post-processing choices. To address these problems, we propose a novel end-to-end differential transformer network, termed RegFormer++, for large-scale point cloud alignment without requiring any further post-processing. Specifically, a hierarchical projection-aware 2D transformer with linear complexity is proposed to project raw LiDAR points onto a cylindrical surface and extract global point features, which can improve resilience to outliers due to long-range dependencies. Because we fill original 3D coordinates into 2D projected positions, our designed transformer can benefit from both high efficiency in 2D processing and accuracy from 3D geometric information. Furthermore, to effectively reduce wrong point matching, a Bijective Association Transformer (BAT) is designed, combining both cross attention and all-to-all point gathering. To improve training stability and robustness, a feature-transformed optimal transport module is also designed for regressing the final pose transformation. Extensive experiments on KITTI, NuScenes, and Argoverse datasets demonstrate that our model achieves state-of-the-art performance in terms of both accuracy and efficiency.
### Title:
          Seeking Physics in Diffusion Noise
 - **Authors:** Chujun Tang, Lei Zhong, Fangqiang Ding
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Do video diffusion models encode signals predictive of physical plausibility? We probe intermediate denoising representations of a pretrained Diffusion Transformer (DiT) and find that physically plausible and implausible videos are partially separable in mid-layer feature space across noise levels. This separability cannot be fully attributed to visual quality or generator identity, suggesting recoverable physics-related cues in frozen DiT features. Leveraging this observation, we introduce progressive trajectory selection, an inference-time strategy that scores parallel denoising trajectories at a few intermediate checkpoints using a lightweight physics verifier trained on frozen features, and prunes low-scoring candidates early. Extensive experiments on PhyGenBench demonstrate that our method improves physical consistency while reducing inference cost, achieving comparable results to Best-of-K sampling with substantially fewer denoising steps.
### Title:
          Show Me When and Where: Towards Referring Video Object Segmentation in the Wild
 - **Authors:** Mingqi Gao, Jinyu Yang, Jingnan Luo, Xiantong Zhen, Jungong Han, Giovanni Montana, Feng Zheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Referring video object segmentation (RVOS) has recently generated great popularity in computer vision due to its widespread applications. Existing RVOS setting contains elaborately trimmed videos, with text-referred objects always appearing in all frames, which however fail to fully reflect the realistic challenges of this task. This simplified setting requires RVOS methods to only predict where objects, with no need to show when the objects appear. In this work, we introduce a new setting towards in-the-wild RVOS. To this end, we collect a new benchmark dataset using Youtube Untrimmed videos for RVOS - YoURVOS, which contains 1,120 in-the-wild videos with 7 times more duration and scenes than existing datasets. Our new benchmark challenges RVOS methods to show not only where but also when objects appear in videos. To set a baseline, we propose Object-level Multimodal TransFormers (OMFormer) to tackle the challenges, which are characterized by encoding object-level multimodal interactions for efficient and global spatial-temporal localisation. We demonstrate that previous VOS methods struggle on our YoURVOS benchmark, especially with the increase of target-absent frames, while our OMFormer consistently performs well. Our YoURVOS dataset offers an imperative benchmark, which will push forward the advancement of RVOS methods for practical applications.
### Title:
          Structure-Dependent Regret and Constraint Violation Bounds for Online Convex Optimization with Time-Varying Constraints
 - **Authors:** Xiufeng Liu, Qian Chen, Zhijin Wang, Ruyu Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Online convex optimization (OCO) with time-varying constraints is a critical framework for sequential decision-making in dynamic networked systems, where learners must minimize cumulative loss while satisfying regions of feasibility that shift across rounds. Existing theoretical analyses typically treat constraint variation as a monolithic adversarial process, resulting in joint regret and violation bounds that are overly conservative for real-world network dynamics. In this paper, we introduce a structured characterization of constraint variation - smooth drift, periodic cycles, and sparse switching - mapping these classes to common network phenomena such as slow channel fading, diurnal traffic patterns, and discrete maintenance windows. We derive structure-dependent joint bounds that strictly improve upon adversarial rates when the constraint process exhibits regularity. To realize these gains, we propose the Structure-Adaptive Primal-Dual (SA-PD) algorithm, which utilizes observable constraint signals to detect environmental structure online and adapt dual update strategies accordingly. Extensive experiments on synthetic benchmarks and real-world datasets - including online electricity scheduling and transformer load management - demonstrate that SA-PD reduces cumulative constraint violation by up to 53% relative to structure-agnostic baselines while maintaining competitive utility. This work serves as a comprehensive guide for exploiting temporal regularity in constrained online learning for robust network engineering.
### Title:
          Personalized Cell Segmentation: Benchmark and Framework for Reference-Guided Cell Type Segmentation
 - **Authors:** Bisheng Wang, Jaime S. Cardoso, Lin Wu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate cell segmentation is critical for biological and medical imaging studies. Although recent deep learning models have advanced this task, most methods are limited to generic cell segmentation, lacking the ability to differentiate specific cell types. In this work, we introduce the Personalized Cell Segmentation (PerCS) task, which aims to segment all cells of a specific type given a reference cell. To support this task, we establish a benchmark by reorganizing publicly available datasets, yielding 1,372 images and over 110,000 annotated cells. As a pioneering solution, we propose PerCS-DINO, a framework built on the DINOv2 backbone. By integrating image features and reference embeddings via a cross-attention transformer and contrastive learning, PerCS-DINO effectively segments cells matching the reference. Extensive experiments demonstrate the effectiveness of the proposed PerCS-DINO and highlight the challenges of this new task. We expect PerCS to serve as a useful testbed for advancing research in cell-based applications.
### Title:
          AvatarForcing: One-Step Streaming Talking Avatars via Local-Future Sliding-Window Denoising
 - **Authors:** Liyuan Cui, Wentao Hu, Wenyuan Zhang, Zesong Yang, Fan Shi, Xiaoqiang Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-time talking avatar generation requires low latency and minute-level temporal stability. Autoregressive (AR) forcing enables streaming inference but suffers from exposure bias, which causes errors to accumulate and become irreversible over long rollouts. In contrast, full-sequence diffusion transformers mitigate drift but remain computationally prohibitive for real-time long-form synthesis. We present AvatarForcing, a one-step streaming diffusion framework that denoises a fixed local-future window with heterogeneous noise levels and emits one clean block per step under constant per-step cost. To stabilize unbounded streams, the method introduces dual-anchor temporal forcing: a style anchor that re-indexes RoPE to maintain a fixed relative position with respect to the active window and applies anchor-audio zero-padding, and a temporal anchor that reuses recently emitted clean blocks to ensure smooth transitions. Real-time one-step inference is enabled by two-stage streaming distillation with offline ODE backfill and distribution matching. Experiments on standard benchmarks and a new 400-video long-form benchmark show strong visual quality and lip synchronization at 34 ms/frame using a 1.3B-parameter student model for realtime streaming. Our page is available at: this https URL
### Title:
          On the Nature of Attention Sink that Shapes Decoding Strategy in MLLMs
 - **Authors:** Suho Yoo, Youngjoon Jang, Joon Son Chung
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models and their multimodal extensions have achieved remarkable success across diverse tasks, yet the internal mechanisms that govern their reasoning behaviour remain partially understood. In particular, the attention sink, a token that attracts disproportionate attention mass, has been observed in transformer architectures, but its role is still unclear. Our goal is to understand what attention sinks represent and how they shape model behaviour during inference, rather than considering them as incidental artifacts. Through our analysis, we find that attention sink representations encode structured global information that influences the decoding process. Building on our findings, we introduce OutRo, a lightweight inference-time strategy that leverages the sink token to enhance contextual representations: (i) non-sink token representations are aligned with the sink representation in the feature space; and (ii) the sink token is allowed to attend beyond the causal constraint, facilitating information exchange with non-sink tokens. This design enhances the reasoning process without requiring additional forward passes or access to attention maps. Based on extensive experiments, OutRo consistently improves performance across representative MLLMs on seven video QA benchmarks and demonstrates strong generalisation, while incurring only a 1.1x decoding overhead.
### Title:
          M$^2$RNN: Non-Linear RNNs with Matrix-Valued States for Scalable Language Modeling
 - **Authors:** Mayank Mishra, Shawn Tan, Ion Stoica, Joseph Gonzalez, Tri Dao
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers are highly parallel but are limited to computations in the TC$^0$ complexity class, excluding tasks such as entity tracking and code execution that provably require greater expressive power. Motivated by this limitation, we revisit non-linear Recurrent Neural Networks (RNNs) for language modeling and introduce Matrix-to-Matrix RNN (M$^2$RNN): an architecture with matrix-valued hidden states and expressive non-linear state transitions. We demonstrate that the language modeling performance of non-linear RNNs is limited by their state size. We also demonstrate how the state size expansion mechanism enables efficient use of tensor cores. Empirically, M$^2$RNN achieves perfect state tracking generalization at sequence lengths not seen during training. These benefits also translate to large-scale language modeling. In hybrid settings that interleave recurrent layers with attention, Hybrid M$^2$RNN outperforms equivalent Gated DeltaNet hybrids by $0.4$-$0.5$ perplexity points on a 7B MoE model, while using $3\times$ smaller state sizes for the recurrent layers. Notably, replacing even a single recurrent layer with M$^2$RNN in an existing hybrid architecture yields accuracy gains comparable to Hybrid M$^2$RNN with minimal impact on training throughput. Further, the Hybrid Gated DeltaNet models with a single M$^2$RNN layer also achieve superior long-context generalization, outperforming state-of-the-art hybrid linear attention architectures by up to $8$ points on LongBench. Together, these results establish non-linear RNN layers as a compelling building block for efficient and scalable language models.
### Title:
          Representation Alignment for Just Image Transformers is not Easier than You Think
 - **Authors:** Jaeyo Shin, Jiwook Kim, Hyunjung Shim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Representation Alignment (REPA) has emerged as a simple way to accelerate Diffusion Transformers training in latent space. At the same time, pixel-space diffusion transformers such as Just image Transformers (JiT) have attracted growing attention because they remove a dependency on a pretrained tokenizer, and then avoid the reconstruction bottleneck of latent diffusion. This paper shows that the REPA can fail for JiT. REPA yields worse FID for JiT as training proceeds and collapses diversity on image subsets that are tightly clustered in the representation space of pretrained semantic encoder on ImageNet. We trace the failure to an information asymmetry: denoising occurs in the high dimensional image space, while the semantic target is strongly compressed, making direct regression a shortcut objective. We propose PixelREPA, which transforms the alignment target and constrains alignment with a Masked Transformer Adapter that combines a shallow transformer adapter with partial token masking. PixelREPA improves both training convergence and final quality. PixelREPA reduces FID from 3.66 to 3.17 for JiT-B$/16$ and improves Inception Score (IS) from 275.1 to 284.6 on ImageNet $256 \times 256$, while achieving $> 2\times$ faster convergence. Finally, PixelREPA-H$/16$ achieves FID$=1.81$ and IS$=317.2$. Our code is available at this https URL.
### Title:
          OxyGen: Unified KV Cache Management for Vision-Language-Action Models under Multi-Task Parallelism
 - **Authors:** Xiangyu Li, Huaizhi Tang, Xin Ding, Weijun Wang, Ting Cao, Yunxin Liu
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Embodied AI agents increasingly require parallel execution of multiple tasks, such as manipulation, conversation, and memory construction, from shared observations under distinct time constraints. Recent Mixture-of-Transformers (MoT) Vision-Language-Action Models (VLAs) architecturally support such heterogeneous outputs, yet existing inference systems fail to achieve efficient multi-task parallelism for on-device deployment due to redundant computation and resource contention. We identify isolated KV cache management as the root cause. To address this, we propose unified KV cache management, an inference paradigm that treats KV cache as a first-class shared resource across tasks and over time. This abstraction enables two key optimizations: cross-task KV sharing eliminates redundant prefill of shared observations, while cross-frame continuous batching decouples variable-length language decoding from fixed-rate action generation across control cycles. We implement this paradigm for $\pi_{0.5}$, the most popular MoT VLA, and evaluate under representative robotic configurations. OxyGen achieves up to 3.7$\times$ speedup over isolated execution, delivering over 200 tokens/s language throughput and 70 Hz action frequency simultaneously without action quality degradation.
### Title:
          eNavi: Event-based Imitation Policies for Low-Light Indoor Mobile Robot Navigation
 - **Authors:** Prithvi Jai Ramesh, Kaustav Chanda, Krishna Vinod, Joseph Raj Vishal, Yezhou Yang, Bharatesh Chakravarthi
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Event cameras provide high dynamic range and microsecond-level temporal resolution, making them well-suited for indoor robot navigation, where conventional RGB cameras degrade under fast motion or low-light conditions. Despite advances in event-based perception spanning detection, SLAM, and pose estimation, there remains limited research on end-to-end control policies that exploit the asynchronous nature of event streams. To address this gap, we introduce a real-world indoor person-following dataset collected using a TurtleBot 2 robot, featuring synchronized raw event streams, RGB frames, and expert control actions across multiple indoor maps, trajectories under both normal and low-light conditions. We further build a multimodal data preprocessing pipeline that temporally aligns event and RGB observations while reconstructing ground-truth actions from odometry to support high-quality imitation learning. Building on this dataset, we propose a late-fusion RGB-Event navigation policy that combines dual MobileNet encoders with a transformer-based fusion module trained via behavioral cloning. A systematic evaluation of RGB-only, Event-only, and RGB-Event fusion models across 12 training variations ranging from single-path imitation to general multi-path imitation shows that policies incorporating event data, particularly the fusion model, achieve improved robustness and lower action prediction error, especially in unseen low-light conditions where RGB-only models fail. We release the dataset, synchronization pipeline, and trained models at this https URL
### Title:
          End-to-End Spatial-Temporal Transformer for Real-time 4D HOI Reconstruction
 - **Authors:** Haoyu Zhang, Wei Zhai, Yuhang Yang, Yang Cao, Zheng-Jun Zha
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular 4D human-object interaction (HOI) reconstruction - recovering a moving human and a manipulated object from a single RGB video - remains challenging due to depth ambiguity and frequent occlusions. Existing methods often rely on multi-stage pipelines or iterative optimization, leading to high inference latency, failing to meet real-time requirements, and susceptibility to error accumulation. To address these limitations, we propose THO, an end-to-end Spatial-Temporal Transformer that predicts human motion and coordinated object motion in a forward fashion from the given video and 3D template. THO achieves this by leveraging spatial-temporal HOI tuple priors. Spatial priors exploit contact-region proximity to infer occluded object features from human cues, while temporal priors capture cross-frame kinematic correlations to refine object representations and enforce physical coherence. Extensive experiments demonstrate that THO operates at an inference speed of 31.5 FPS on a single RTX 4090 GPU, achieving a >600x speedup over prior optimization-based methods while simultaneously improving reconstruction accuracy and temporal consistency. The project page is available at: this https URL
### Title:
          Uni-MDTrack: Learning Decoupled Memory and Dynamic States for Parameter-Efficient Visual Tracking in All Modality
 - **Authors:** Wenrui Cai, Zhenyi Lu, Yuzhe Li, Yongchao Feng, Jinqing Zhang, Qingjie Liu, Yunhong Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the advent of Transformer-based one-stream trackers that possess strong capability in inter-frame relation modeling, recent research has increasingly focused on how to introduce spatio-temporal context. However, most existing methods rely on a limited number of historical frames, which not only leads to insufficient utilization of the context, but also inevitably increases the length of input and incurs prohibitive computational overhead. Methods that query an external memory bank, on the other hand, suffer from inadequate fusion between the retrieved spatio-temporal features and the backbone. Moreover, using discrete historical frames as context overlooks the rich dynamics of the target. To address the issues, we propose Uni-MDTrack, which consists of two core components: Memory-Aware Compression Prompt (MCP) module and Dynamic State Fusion (DSF) module. MCP effectively compresses rich memory features into memory-aware prompt tokens, which deeply interact with the input throughout the entire backbone, significantly enhancing the performance while maintaining a stable computational load. DSF complements the discrete memory by capturing the continuous dynamic, progressively introducing the updated dynamic state features from shallow to deep layers, while also preserving high efficiency. Uni-MDTrack also supports unified tracking across RGB, RGB-D/T/E, and RGB-Language modalities. Experiments show that in Uni-MDTrack, training only the MCP, DSF, and prediction head, keeping the proportion of trainable parameters around 30%, yields substantial performance gains, achieves state-of-the-art results on 10 datasets spanning five modalities. Furthermore, both MCP and DSF exhibit excellent generality, functioning as plug-and-play components that can boost the performance of various baseline trackers, while significantly outperforming existing parameter-efficient training approaches.
### Title:
          Disentangling Dynamical Systems: Causal Representation Learning Meets Local Sparse Attention
 - **Authors:** Markus W. Baumgartner, Anson Lei, Joe Watson, Ingmar Posner
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Parametric system identification methods estimate the parameters of explicitly defined physical systems from data. Yet, they remain constrained by the need to provide an explicit function space, typically through a predefined library of candidate functions chosen via available domain knowledge. In contrast, deep learning can demonstrably model systems of broad complexity with high fidelity, but black-box function approximation typically fails to yield explicit descriptive or disentangled representations revealing the structure of a system. We develop a novel identifiability theorem, leveraging causal representation learning, to uncover disentangled representations of system parameters without structural assumptions. We derive a graphical criterion specifying when system parameters can be uniquely disentangled from raw trajectory data, up to permutation and diffeomorphism. Crucially, our analysis demonstrates that global causal structures provide a lower bound on the disentanglement guarantees achievable when considering local state-dependent causal structures. We instantiate system parameter identification as a variational inference problem, leveraging a sparsity-regularised transformer to uncover state-dependent causal structures. We empirically validate our approach across four synthetic domains, demonstrating its ability to recover highly disentangled representations that baselines fail to recover. Corroborating our theoretical analysis, our results confirm that enforcing local causal structure is often necessary for full identifiability.
### Title:
          Learning to Forget: Sleep-Inspired Memory Consolidation for Resolving Proactive Interference in Large Language Models
 - **Authors:** Ying Xie
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) suffer from proactive interference (PI): outdated information in the context window disrupts retrieval of current values. This interference degrades retrieval accuracy log-linearly as stale associations accumulate, a bottleneck that persists regardless of context length and resists prompt-engineering mitigations. Biological brains resolve an analogous challenge through sleep-dependent memory consolidation: synaptic downscaling, selective replay, and targeted forgetting. We propose SleepGate, a biologically inspired framework that augments transformer-based LLMs with a learned sleep cycle over the key-value (KV) cache. SleepGate introduces three mechanisms: (1) a conflict-aware temporal tagger detecting when new entries supersede old ones; (2) a lightweight forgetting gate trained to selectively evict or compress stale cache entries; and (3) a consolidation module that merges surviving entries into compact summaries. These components activate periodically during inference in sleep micro-cycles, governed by an adaptive entropy-based trigger. We formalize a dual-phase training objective jointly optimizing language modeling during the wake phase and post-consolidation retrieval during the sleep phase. Theoretical analysis shows SleepGate reduces the interference horizon from O(n) to O(log n). In experiments with a small-scale transformer (4 layers, 793K parameters), SleepGate achieves 99.5% retrieval accuracy at PI depth 5 and 97.0% at depth 10, while all five baselines -- full KV cache, sliding window, H2O, StreamingLLM, and decay-only ablation -- remain below 18%. Our framework offers an architecture-level solution that prompt engineering cannot address.
### Title:
          One-Policy-Fits-All: Geometry-Aware Action Latents for Cross-Embodiment Manipulation
 - **Authors:** Juncheng Mu, Sizhe Yang, Hojin Bae, Feiyu Jia, Qingwei Ben, Boyi Li, Huazhe Xu, Jiangmiao Pang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-embodiment manipulation is crucial for enhancing the scalability of robot manipulation and reducing the high cost of data collection. However, the significant differences between embodiments, such as variations in action spaces and structural disparities, pose challenges for joint training across multiple sources of data. To address this, we propose One-Policy-Fits-All (OPFA), a framework that enables learning a single, versatile policy across multiple embodiments. We first learn a Geometry-Aware Latent Representation (GaLR), which leverages 3D convolution networks and transformers to build a shared latent action space across different embodiments. Then we design a unified latent retargeting decoder that extracts embodiment-specific actions from the latent representations, without any embodiment-specific decoder tuning. OPFA enables end-to-end co-training of data from diverse embodiments, including various grippers and dexterous hands with arbitrary degrees of freedom, significantly improving data efficiency and reducing the cost of skill transfer. We conduct extensive experiments across 11 different end-effectors. The results demonstrate that OPFA significantly improves policy performance in diverse settings by leveraging heterogeneous embodiment data. For instance, cross-embodiment co-training can improve success rates by more than 50% compared to single-source training. Moreover, by adding only a few demonstrations from a new embodiment (e.g., eight), OPFA can achieve performance comparable to that of a well-trained model with 72 demonstrations.
### Title:
          Learning to Order: Task Sequencing as In-Context Optimization
 - **Authors:** Jan Kobiolka, Christian Frey, Arlind Kadra, Gresa Shala, Josif Grabocka
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Task sequencing (TS) is one of the core open problems in Deep Learning, arising in a plethora of real-world domains, from robotic assembly lines to autonomous driving. Unfortunately, prior work has not convincingly demonstrated the generalization ability of meta-learned TS methods to solve new TS problems, given few initial demonstrations. In this paper, we demonstrate that deep neural networks can meta-learn over an infinite prior of synthetically generated TS problems and achieve a few-shot generalization. We meta-learn a transformer-based architecture over datasets of sequencing trajectories generated from a prior distribution that samples sequencing problems as paths in directed graphs. In a large-scale experiment, we provide ample empirical evidence that our meta-learned models discover optimal task sequences significantly quicker than non-meta-learned baselines.
### Title:
          JobMatchAI An Intelligent Job Matching Platform Using Knowledge Graphs, Semantic Search and Explainable AI
 - **Authors:** Mayank Vyaas, Abhijit Chakrabroty, Vivek Gupta
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recruiters and job seekers rely on search systems to navigate labor markets, making candidate matching engines critical for hiring outcomes. Most systems act as keyword filters, failing to handle skill synonyms and nonlinear careers, resulting in missed candidates and opaque match scores. We introduce JobMatchAI, a production-ready system integrating Transformer embeddings, skill knowledge graphs, and interpretable reranking. Our system optimizes utility across skill fit, experience, location, salary, and company preferences, providing factor-wise explanations through resume-driven search workflows. We release JobSearch-XS benchmark and a hybrid retrieval stack combining BM25, knowledge graph and semantic components to evaluate skill generalization. We assess system performance on JobSearch-XS across retrieval tasks, provide a demo video, a hosted website and installable package.
### Title:
          A comprehensive multimodal dataset and benchmark for ulcerative colitis scoring in endoscopy
 - **Authors:** Noha Ghatwary, Jiangbei Yue, Ahmed Elgendy, Hanna Nagdy, Ahmed Galal, Hayam Fathy, Hussein El-Amin, Venkataraman Subramanian, Noor Mohammed, Gilberto Ochoa-Ruiz, Sharib Ali
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ulcerative colitis (UC) is a chronic mucosal inflammatory condition that places patients at increased risk of colorectal cancer. Colonoscopic surveillance remains the gold standard for assessing disease activity, and reporting typically relies on standardised endoscopic scoring metrics. The most widely used is the Mayo Endoscopic Score (MES), with some centres also adopting the Ulcerative Colitis Endoscopic Index of Severity (UCEIS). Both are descriptive assessments of mucosal inflammation (MES: 0 to 3; UCEIS: 0 to 8), where higher values indicate more severe disease. However, computational methods for automatically predicting these scores remain limited, largely due to the lack of publicly available expert-annotated datasets and the absence of robust benchmarking. There is also a significant research gap in generating clinically meaningful descriptions of UC images, despite image captioning being a well-established computer vision task. Variability in endoscopic systems and procedural workflows across centres further highlights the need for multi-centre datasets to ensure algorithmic robustness and generalisability. In this work, we introduce a curated multi-centre, multi-resolution dataset that includes expert-validated MES and UCEIS labels, alongside detailed clinical descriptions. To our knowledge, this is the first comprehensive dataset that combines dual scoring metrics for classification tasks with expert-generated captions describing mucosal appearance and clinically accepted reasoning for image captioning. This resource opens new opportunities for developing clinically meaningful multimodal algorithms. In addition to the dataset, we also provide benchmarking using convolutional neural networks, vision transformers, hybrid models, and widely used multimodal vision-language captioning algorithms.
### Title:
          Parameter-Efficient Quality Estimation via Frozen Recursive Models
 - **Authors:** Umar Abubacar, Roman Bauer, Diptesh Kanojia
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tiny Recursive Models (TRM) achieve strong results on reasoning tasks through iterative refinement of a shared network. We investigate whether these recursive mechanisms transfer to Quality Estimation (QE) for low-resource languages using a three-phase methodology. Experiments on $8$ language pairs on a low-resource QE dataset reveal three findings. First, TRM's recursive mechanisms do not transfer to QE. External iteration hurts performance, and internal recursion offers only narrow benefits. Next, representation quality dominates architectural choices, and lastly, frozen pretrained embeddings match fine-tuned performance while reducing trainable parameters by 37$\times$ (7M vs 262M). TRM-QE with frozen XLM-R embeddings achieves a Spearman's correlation of 0.370, matching fine-tuned variants (0.369) and outperforming an equivalent-depth standard transformer (0.336). On Hindi and Tamil, frozen TRM-QE outperforms MonoTransQuest (560M parameters) with 80$\times$ fewer trainable parameters, suggesting that weight sharing combined with frozen embeddings enables parameter efficiency for QE. We release the code publicly for further research. Code is available at this https URL.
### Title:
          Delightful Policy Gradient
 - **Authors:** Ian Osband
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Optimization and Control (math.OC); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Standard policy gradients weight each sampled action by advantage alone, regardless of how likely that action was under the current policy. This creates two pathologies: within a single decision context (e.g. one image or prompt), a rare negative-advantage action can disproportionately distort the update direction; across many such contexts in a batch, the expected gradient over-allocates budget to contexts the policy already handles well. We introduce the \textit{Delightful Policy Gradient} (DG), which gates each term with a sigmoid of \emph{delight}, the product of advantage and action surprisal (negative log-probability). For $K$-armed bandits, DG provably improves directional accuracy in a single context and, across multiple contexts, shifts the expected gradient strictly closer to the supervised cross-entropy oracle. This second effect is not variance reduction: it persists even with infinite samples. Empirically, DG outperforms REINFORCE, PPO, and advantage-weighted baselines across MNIST, transformer sequence modeling, and continuous control, with larger gains on harder tasks.
### Title:
          A Heterogeneous Ensemble for Multi-Center COVID-19 Classification from Chest CT Scans
 - **Authors:** Aadit Nilay, Bhavesh Thapar, Anant Agrawal, Mohammad Nayeem Teli
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The COVID-19 pandemic exposed critical limitations in diagnostic workflows: RT-PCR tests suffer from slow turnaround times and high false-negative rates, while CT-based screening offers faster complementary diagnosis but requires expert radiological interpretation. Deploying automated CT analysis across multiple hospital centres introduces further challenges, as differences in scanner hardware, acquisition protocols, and patient populations cause substantial domain shift that degrades single-model performance. To address these challenges, we present a heterogeneous ensemble of nine models spanning three inference paradigms: (1) a self-supervised DINOv2 Vision Transformer with slice-level sigmoid aggregation, (2) a RadImageNet-pretrained DenseNet-121 with slice-level sigmoid averaging, and (3) seven Gated Attention Multiple Instance Learning models using EfficientNet-B3, ConvNeXt-Tiny, and EfficientNetV2-S backbones with scan-level softmax classification. Ensemble diversity is further enhanced through random-seed variation and Stochastic Weight Averaging. We address severe overfitting, reducing the validation-to-training loss ratio from 35x to less than 3x, through a combination of Focal Loss, embedding-level Mixup, and domain-aware augmentation. Model outputs are fused via score-weighted probability averaging and calibrated with per-source threshold optimization. The final ensemble achieves an average macro F1 of 0.9280 across four hospital centres, outperforming the best single model (F1=0.8969) by +0.031, demonstrating that heterogeneous architectures combined with source-aware calibration are essential for robust multi-site medical image classification.
### Title:
          EcoFair-CH-MARL: Scalable Constrained Hierarchical Multi-Agent RL with Real-Time Emission Budgets and Fairness Guarantees
 - **Authors:** Saad Alqithami
 - **Subjects:** Subjects:
Multiagent Systems (cs.MA); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Global decarbonisation targets and tightening market pressures demand maritime logistics solutions that are simultaneously efficient, sustainable, and equitable. We introduce EcoFair-CH-MARL, a constrained hierarchical multi-agent reinforcement learning framework that unifies three innovations: (i) a primal-dual budget layer that provably bounds cumulative emissions under stochastic weather and demand; (ii) a fairness-aware reward transformer with dynamically scheduled penalties that enforces max-min cost equity across heterogeneous fleets; and (iii) a two-tier policy architecture that decouples strategic routing from real-time vessel control, enabling linear scaling in agent count. New theoretical results establish O(\sqrt{T}) regret for both constraint violations and fairness loss. Experiments on a high-fidelity maritime digital twin (16 ports, 50 vessels) driven by automatic identification system traces, plus an energy-grid case study, show up to 15% lower emissions, 12% higher through-put, and a 45% fair-cost improvement over state-of-the-art hierarchical and constrained MARL baselines. In addition, EcoFair-CH-MARL achieves stronger equity (lower Gini and higher min-max welfare) than fairness-specific MARL baselines (e.g., SOTO, FEN), and its modular design is compatible with both policy- and value-based learners. EcoFair-CH-MARL therefore advances the feasibility of large-scale, regulation-compliant, and socially responsible multi-agent coordination in safety-critical domains.
### Title:
          Punctuated Equilibria in Artificial Intelligence: The Institutional Scaling Law and the Speciation of Sovereign AI
 - **Authors:** Mark Baciak, Thomas A. Cellucci, Deanna M. Falkowski
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The dominant narrative of artificial intelligence development assumes that progress is continuous and that capability scales monotonically with model size. We challenge both assumptions. Drawing on punctuated equilibrium theory from evolutionary biology, we show that AI development proceeds not through smooth advancement but through extended periods of stasis interrupted by rapid phase transitions that reorganize the competitive landscape. We identify five such eras since 1943 and four epochs within the current Generative AI Era, each initiated by a discontinuous event -- from the transformer architecture to the DeepSeek Moment -- that rendered the prior paradigm subordinate. To formalize the selection pressures driving these transitions, we develop the Institutional Fitness Manifold, a mathematical framework that evaluates AI systems along four dimensions: capability, institutional trust, affordability, and sovereign compliance. The central result is the Institutional Scaling Law, which proves that institutional fitness is non-monotonic in model scale. Beyond an environment-specific optimum, scaling further degrades fitness as trust erosion and cost penalties outweigh marginal capability gains. This directly contradicts classical scaling laws and carries a strong implication: orchestrated systems of smaller, domain-adapted models can mathematically outperform frontier generalists in most institutional deployment environments. We derive formal conditions under which this inversion holds and present supporting empirical evidence spanning frontier laboratory dynamics, post-training alignment evolution, and the rise of sovereign AI as a geopolitical selection pressure.
### Title:
          AdapterTune: Zero-Initialized Low-Rank Adapters for Frozen Vision Transformers
 - **Authors:** Salim Khazem
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Frozen-backbone transfer with Vision Transformers faces two under-addressed issues: optimization instability when adapters are naively inserted into a fixed feature extractor, and the absence of principled guidance for setting adapter capacity. We introduce AdapterTune, which augments each transformer block with a residual low-rank bottleneck whose up-projection is zero-initialized, guaranteeing that the adapted network starts exactly at the pretrained function and eliminates early-epoch representation drift. On the analytical side, we formalize adapter rank as a capacity budget for approximating downstream task shifts in feature space. The resulting excess-risk decomposition predicts monotonic but diminishing accuracy gains with increasing rank, an ``elbow'' behavior we confirm through controlled sweeps. We evaluate on 9 datasets and 3 backbone scales with multi-seed reporting throughout. On a core 5 dataset transfer suite, AdapterTune improves top-1 accuracy over head-only transfer by +14.9 points on average while training only 0.92 of the parameters required by full fine-tuning, and outperforms full fine-tuning on 10 of 15 dataset-backbone pairs. Across the full benchmark, AdapterTune improves over head-only transfer on every dataset-backbone pair tested. Ablations on rank, placement, and initialization isolate each design choice. The code is available at: this https URL
### Title:
          Training-Free Generation of Protein Sequences from Small Family Alignments via Stochastic Attention
 - **Authors:** Jeffrey D. Varner
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Most protein families have fewer than 100 known members, a regime where deep generative models overfit or collapse. We propose stochastic attention (SA), a training-free sampler that treats the modern Hopfield energy over a protein alignment as a Boltzmann distribution and draws samples via Langevin dynamics. The score function is a closed-form softmax attention operation requiring no training, no pretraining data, and no GPU, with cost linear in alignment size. Across eight Pfam families, SA generates sequences with low amino acid compositional divergence, substantial novelty, and structural plausibility confirmed by ESMFold and AlphaFold2. Generated sequences fold more faithfully to canonical family structures than natural members in six of eight families. Against profile HMMs, EvoDiff, and the MSA Transformer, which produce sequences that drift far outside the family, SA maintains 51 to 66 percent identity while remaining novel, in seconds on a laptop. The critical temperature governing generation is predicted from PCA dimensionality alone, enabling fully automatic operation. Controls confirm SA encodes correlated substitution patterns, not just per-position amino acid frequencies.
### Title:
          Automated Diabetic Screening via Anterior Segment Ocular Imaging: A Deep Learning and Explainable AI Approach
 - **Authors:** Hasaan Maqsood, Saif Ur Rehman Khan, Sebastian Vollmer, Andreas Dengel, Muhammad Nabeel Asim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diabetic retinopathy screening traditionally relies on fundus photography, requiring specialized equipment and expertise often unavailable in primary care and resource limited settings. We developed and validated a deep learning (DL) system for automated diabetic classification using anterior segment ocular imaging a readily accessible alternative utilizing standard photography equipment. The system leverages visible biomarkers in the iris, sclera, and conjunctiva that correlate with systemic diabetic status. We systematically evaluated five contemporary architectures (EfficientNet-V2-S with self-supervised learning (SSL), Vision Transformer, Swin Transformer, ConvNeXt-Base, and ResNet-50) on 2,640 clinically annotated anterior segment images spanning Normal, Controlled Diabetic, and Uncontrolled Diabetic categories. A tailored preprocessing pipeline combining specular reflection mitigation and contrast limited adaptive histogram equalization (CLAHE) was implemented to enhance subtle vascular and textural patterns critical for classification. SSL using SimCLR on domain specific ocular images substantially improved model this http URL-V2-S with SSL achieved optimal performance with an F1-score of 98.21%, precision of 97.90%, and recall of 98.55% a substantial improvement over ImageNet only initialization (94.63% F1). Notably, the model attained near perfect precision (100%) for Normal classification, critical for minimizing unnecessary clinical referrals.
### Title:
          AnyPhoto: Multi-Person Identity Preserving Image Generation with ID Adaptive Modulation on Location Canvas
 - **Authors:** Longhui Yuan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-person identity-preserving generation requires binding multiple reference faces to specified locations under a text prompt. Strong identity/layout conditions often trigger copy-paste shortcuts and weaken prompt-driven controllability. We present AnyPhoto, a diffusion-transformer finetuning framework with (i) a RoPE-aligned location canvas plus location-aligned token pruning for spatial grounding, (ii) AdaLN-style identity-adaptive modulation from face-recognition embeddings for persistent identity injection, and (iii) identity-isolated attention to prevent cross-identity interference. Training combines conditional flow matching with an embedding-space face similarity loss, together with reference-face replacement and location-canvas degradations to discourage shortcuts. On MultiID-Bench, AnyPhoto improves identity similarity while reducing copy-paste tendency, with gains increasing as the number of identities grows. AnyPhoto also supports prompt-driven stylization with accurate placement, showing great potential application value.
### Title:
          Zero-Shot Reconstruction of Animatable 3D Avatars with Cloth Dynamics from a Single Image
 - **Authors:** Joohyun Kwon, Geonhee Sim, Gyeongsik Moon
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing single-image 3D human avatar methods primarily rely on rigid joint transformations, limiting their ability to model realistic cloth dynamics. We present DynaAvatar, a zero-shot framework that reconstructs animatable 3D human avatars with motion-dependent cloth dynamics from a single image. Trained on large-scale multi-person motion datasets, DynaAvatar employs a Transformer-based feed-forward architecture that directly predicts dynamic 3D Gaussian deformations without subject-specific optimization. To overcome the scarcity of dynamic captures, we introduce a static-to-dynamic knowledge transfer strategy: a Transformer pretrained on large-scale static captures provides strong geometric and appearance priors, which are efficiently adapted to motion-dependent deformations through lightweight LoRA fine-tuning on dynamic captures. We further propose the DynaFlow loss, an optical flow-guided objective that provides reliable motion-direction geometric cues for cloth dynamics in rendered space. Finally, we reannotate the missing or noisy SMPL-X fittings in existing dynamic capture datasets, as most public dynamic capture datasets contain incomplete or unreliable fittings that are unsuitable for training high-quality 3D avatar reconstruction models. Experiments demonstrate that DynaAvatar produces visually rich and generalizable animations, outperforming prior methods.
### Title:
          M2IR: Proactive All-in-One Image Restoration via Mamba-style Modulation and Mixture-of-Experts
 - **Authors:** Shiwei Wang, Yongzhen Wang, Bingwen Hu, Liyan Zhang, Xiao-Ping Zhang, Mingqiang Wei
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Transformer-based architectures have dominated recent advances in all-in-one image restoration, they remain fundamentally reactive: propagating degradations rather than proactively suppressing them. In the absence of explicit suppression mechanisms, degraded signals interfere with feature learning, compelling the decoder to balance artifact removal and detail preservation, thereby increasing model complexity and limiting adaptability. To address these challenges, we propose M2IR, a novel restoration framework that proactively regulates degradation propagation during the encoding stage and efficiently eliminates residual degradations during decoding. Specifically, the Mamba-Style Transformer (MST) block performs pixel-wise selective state modulation to mitigate degradations while preserving structural integrity. In parallel, the Adaptive Degradation Expert Collaboration (ADEC) module utilizes degradation-specific experts guided by a DA-CLIP-driven router and complemented by a shared expert to eliminate residual degradations through targeted and cooperative restoration. By integrating the MST block and ADEC module, M2IR transitions from passive reaction to active degradation control, effectively harnessing learned representations to achieve superior generalization, enhanced adaptability, and refined recovery of fine-grained details across diverse all-in-one image restoration benchmarks. Our source codes are available at this https URL.
### Title:
          RAZOR: Ratio-Aware Layer Editing for Targeted Unlearning in Vision Transformers and Diffusion Models
 - **Authors:** Ravi Ranjan, Utkarsh Grover, Xiaomin Lin, Agoritsa Polyzou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer based diffusion and vision-language models have achieved remarkable success; yet, efficiently removing undesirable or sensitive information without retraining remains a central challenge for model safety and compliance. We introduce Ratio-Aware Zero/One-step Optimized Retentive unlearning (RAZOR), a lightweight, model-agnostic unlearning framework that generalizes forgetting updates to coordinated multi-layer and multi-head edits within transformer backbones. RAZOR identifies the most important layers and attention heads by measuring how much they contribute to forgetting the target data while preserving useful knowledge. Then, it updates these parts of the model using a carefully regularized rule to avoid harming overall performance. The set of edited components grows gradually, ensuring precise unlearning without over-editing or damaging unrelated capabilities. We evaluate RAZOR on CLIP, Stable Diffusion, and vision-language models (VLMs) using widely adopted unlearning benchmarks covering identity, style, and object erasure tasks. Our results show that RAZOR achieves highly accurate and stable forgetting, even under quantization. This approach offers stronger retention and better efficiency than prior methods. Notably, it also operates significant faster than conventional techniques. These results demonstrate that RAZOR is a practical and scalable solution for safe, adaptive unlearning in transformer-based vision models.
### Title:
          Halfway to 3D: Ensembling 2.5D and 3D Models for Robust COVID-19 CT Diagnosis
 - **Authors:** Tuan-Anh Yang, Bao V. Q. Bui, Chanh-Quang Vo-Van, Truong-Son Hy
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose a deep learning framework for COVID-19 detection and disease classification from chest CT scans that integrates both 2.5D and 3D representations to capture complementary slice-level and volumetric information. The 2.5D branch processes multi-view CT slices (axial, coronal, sagittal) using a DINOv3 vision transformer to extract robust visual features, while the 3D branch employs a ResNet-18 architecture to model volumetric context and is pretrained with Variance Risk Extrapolation (VREx) followed by supervised contrastive learning to improve cross-source robustness. Predictions from both branches are combined through logit-level ensemble inference. Experiments on the PHAROS-AIF-MIH benchmark demonstrate the effectiveness of the proposed approach: for binary COVID-19 detection, the ensemble achieves 94.48% accuracy and a 0.9426 Macro F1-score, outperforming both individual models, while for multi-class disease classification the 2.5D DINOv3 model achieves the best performance with 79.35% accuracy and a 0.7497 Macro F1-score. These results highlight the benefit of combining pretrained slice-based representations with volumetric modeling for robust multi-source medical imaging analysis. Code is available at this https URL
### Title:
          Ablate and Rescue: A Causal Analysis of Residual Stream Hyper-Connections
 - **Authors:** William Peng, Josheev Rai, Kevin Tseng, Siwei Wang, Sean Wu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-stream transformer architectures have recently been proposed as a promising direction for managing representation collapse and the vanishing gradient problem for residual connections, yet their internal mechanisms remain unexplored. In particular, the recently introduced Manifold-Constrained Hyper-Connections (mHC) architecture posits multiple residual streams with constrained interaction, but lacks in-depth mechanistic analysis. We present the first open-source mHC language model (this https URL) and analyze the multiple-stream architecture with a suite of representation-level metrics and causal interventions to probe how parallel streams encode and utilize information. Specifically, we introduce a systematic stream ablation-and-rescue framework that enables direct causal comparison of residual streams during inference. Through targeted pairwise interventions and controlled recovery experiments, we distinguish functional redundancy from asymmetric utilization and reveal how information is distributed across streams beyond what is observable from representational similarity alone.
### Title:
          AutoMoT: A Unified Vision-Language-Action Model with Asynchronous Mixture-of-Transformers for End-to-End Autonomous Driving
 - **Authors:** Wenhui Huang, Songyan Zhang, Qihang Huang, Zhidong Wang, Zhiqi Mao, Collister Chua, Zhan Chen, Long Chen, Chen Lv
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Integrating vision-language models (VLMs) into end-to-end (E2E) autonomous driving (AD) systems has shown promise in improving scene understanding. However, existing integration strategies suffer from several limitations: they either struggle to resolve distribution misalignment between reasoning and action spaces, underexploit the general reasoning capabilities of pretrained VLMs, or incur substantial inference latency during action policy generation, which degrades driving performance. To address these challenges, we propose \OURS in this work, an end-to-end AD framework that unifies reasoning and action generation within a single vision-language-action (VLA) model. Our approach leverages a mixture-of-transformer (MoT) architecture with joint attention sharing, which preserves the general reasoning capabilities of pre-trained VLMs while enabling efficient fast-slow inference through asynchronous execution at different task frequencies. Extensive experiments on multiple benchmarks, under both open- and closed-loop settings, demonstrate that \OURS achieves competitive performance compared to state-of-the-art methods. We further investigate the functional boundary of pre-trained VLMs in AD, examining when AD-tailored fine-tuning is necessary. Our results show that pre-trained VLMs can achieve competitive multi-task scene understanding performance through semantic prompting alone, while fine-tuning remains essential for action-level tasks such as decision-making and trajectory planning. We refer to \href{this https URL}{Project Page} for the demonstration videos and qualitative results.
### Title:
          Transformers As Generalizable Optimal Controllers
 - **Authors:** Turki Bin Mohaya, Maitham F. AL-Sunni, John M. Dolan, Peter Seiler
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study whether optimal state-feedback laws for a family of heterogeneous Multiple-Input, Multiple-Output (MIMO) Linear Time-Invariant (LTI) systems can be captured by a single learned controller. We train one transformer policy on LQR-generated trajectories from systems with different state and input dimensions, using a shared representation with standardization, padding, dimension encoding, and masked loss. The policy maps recent state history to control actions without requiring plant matrices at inference time. Across a broad set of systems, it achieves empirically small sub-optimality relative to Linear Quadratic Regulator (LQR), remains stabilizing under moderate parameter perturbations, and benefits from lightweight fine-tuning on unseen systems. These results support transformer policies as practical approximators of near-optimal feedback laws over structured linear-system families.
### Title:
          Directional Routing in Transformers
 - **Authors:** Kevin Taylor
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce directional routing, a lightweight mechanism that gives each transformer attention head learned suppression directions controlled by a shared router, at 3.9% parameter cost. We train a 433M-parameter model alongside an identical baseline in a single run, then trace the resulting circuits through mechanistic interpretability. Routing becomes the model's dominant computational pathway. Disabling it collapses factual recall to near-zero probability across all 8 test prompts and drops induction accuracy from 93.4% to 0.0%. Knocking out individual attention heads has negligible effect: the primary mover head's removal actually increases target probability, and induction heads retain 98.6% accuracy without their strongest member. The coordination mechanism is irreplaceable; the components it coordinates are not. The model also self-organizes, without explicit pressure, into two regimes: domain-adaptive routing in early layers and fixed syntactic pruning in late layers, where the least-varying layer is the most critical (+42.6 PPL when disabled). Routing reduces perplexity 31-56% relative to the baseline, though downstream multiple-choice benchmarks do not yet reflect these gains.
### Title:
          Masked BRep Autoencoder via Hierarchical Graph Transformer
 - **Authors:** Yifei Li, Kang Wu, Wenming Wu, Xiaoming Fu
 - **Subjects:** Subjects:
Graphics (cs.GR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce a novel self-supervised learning framework that automatically learns representations from input computer-aided design (CAD) models for downstream tasks, including part classification, modeling segmentation, and machining feature recognition. To train our network, we construct a large-scale, unlabeled dataset of boundary representation (BRep) models. The success of our algorithm relies on two keycomponents. The first is a masked graph autoencoder that reconstructs randomly masked geometries and attributes of BReps for representation learning to enhance the generalization. The second is a hierarchical graph Transformer architecture that elegantly fuses global and local learning by a cross-scale mutual attention block to model long-range geometric dependencies and a graph neural network block to aggregate local topological information. After training the autoencoder, we replace its decoder with a task-specific network trained on a small amount of labeled data for downstream tasks. We conduct experiments on various tasks and achieve high performance, even with a small amount of labeled data, demonstrating the practicality and generalizability of our model. Compared to other methods, our model performs significantly better on downstream tasks with the same amount of training data, particularly when the training data is very limited.
### Title:
          FAR-Drive: Frame-AutoRegressive Video Generation in Closed-Loop Autonomous Driving
 - **Authors:** Yaoru Li, Federico Landi, Marco Godi, Xin Jin, Ruiju Fu, Yufei Ma, Muyang Sun, Heyu Si, Qi Guo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite rapid progress in autonomous driving, reliable training and evaluation of driving systems remain fundamentally constrained by the lack of scalable and interactive simulation environments. Recent generative video models achieve remarkable visual fidelity, yet most operate in open-loop settings and fail to support fine-grained frame-level interaction between agent actions and environment evolution. Building a learning-based closed-loop simulator for autonomous driving poses three major challenges: maintaining long-horizon temporal and cross-view consistency, mitigating autoregressive degradation under iterative self-conditioning, and satisfying low-latency inference constraints. In this work, we propose FAR-Drive, a frame-level autoregressive video generation framework for autonomous driving. We introduce a multi-view diffusion transformer with fine-grained structured control, enabling geometrically consistent multi-camera generation. To address long-horizon consistency and iterative degradation, we design a two-stage training strategy consisting of adaptive reference horizon conditioning and blend-forcing autoregressive training, which progressively improves consistency and robustness under self-conditioning. To meet low-latency interaction requirements, we further integrate system-level efficiency optimizations for inference acceleration. Experiments on the nuScenes dataset demonstrate that our method achieves state-of-the-art performance among existing closed-loop autonomous driving simulation approaches, while maintaining sub-second latency on a single GPU.
### Title:
          Pretraining and Benchmarking Modern Encoders for Latvian
 - **Authors:** Arturs Znotins
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Encoder-only transformers remain essential for practical NLP tasks. While recent advances in multilingual models have improved cross-lingual capabilities, low-resource languages such as Latvian remain underrepresented in pretraining corpora, and few monolingual Latvian encoders currently exist. We address this gap by pretraining a suite of Latvian-specific encoders based on RoBERTa, DeBERTaV3, and ModernBERT architectures, including long-context variants, and evaluating them across a diverse set of Latvian diagnostic and linguistic benchmarks. Our models are competitive with existing monolingual and multilingual encoders while benefiting from recent architectural and efficiency advances. Our best model, lv-deberta-base (111M parameters), achieves the strongest overall performance, outperforming larger multilingual baselines and prior Latvian-specific encoders. We release all pretrained models and evaluation resources to support further research and practical applications in Latvian NLP.
### Title:
          Reference-Free Omnidirectional Stereo Matching via Multi-View Consistency Maximization
 - **Authors:** Lehuai Xu, Weiming Zhang, Yang Li, Sidan Du, Lin Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable omnidirectional depth estimation from multi-fisheye stereo matching is pivotal to many applications, such as embodied robotics. Existing approaches either rely on spherical sweeping with heuristic fusion strategies to build the cost columns or perform reference-centric stereo matching based on rectified views. However, these methods fail to explicitly exploit geometric relationships between multiple views, rendering them less capable of capturing the global dependencies, visibility, or scale changes. In this paper, we shift to a new perspective and propose a novel reference-free framework, dubbed FreeOmniMVS, via multi-view consistency maximization. The highlight of FreeOmniMVS is that it can aggregate pair-wise correlations into a robust, visibility-aware, and global consensus. As such, it is tolerant to occlusions, partial overlaps, and varying baselines. Specifically, to achieve global coherence, we introduce a novel View-pair Correlation Transformer (VCT) that explicitly models pairwise correlation volumes across all camera view pairs, allowing us to drop unreliable pairs caused by occlusion or out-of-focus observations. To realize scalable and visibility-aware consensus, we propose a lightweight attention mechanism that adaptively fuses the correlation vectors, eliminating the need for a designated reference view and allowing all cameras to contribute equally to the stereo matching process. Extensive experiments on diverse benchmark datasets demonstrate the superiority of our method for globally consistent, visibility-aware, and scale-aware omnidirectional depth estimation.
### Title:
          Rethinking Machine Unlearning: Models Designed to Forget via Key Deletion
 - **Authors:** Sonia Laguna, Jorge da Silva Goncalves, Moritz Vandenhirtz, Alain Ryser, Irene Cannistraci, Julia E. Vogt
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Machine unlearning is rapidly becoming a practical requirement, driven by privacy regulations, data errors, and the need to remove harmful or corrupted training samples. Despite this, most existing methods tackle the problem purely from a post-hoc perspective. They attempt to erase the influence of targeted training samples through parameter updates that typically require access to the full training data. This creates a mismatch with real deployment scenarios where unlearning requests can be anticipated, revealing a fundamental limitation of post-hoc approaches. We propose \textit{unlearning by design}, a novel paradigm in which models are directly trained to support forgetting as an inherent capability. We instantiate this idea with Machine UNlearning via KEY deletion (MUNKEY), a memory augmented transformer that decouples instance-specific memorization from model weights. Here, unlearning corresponds to removing the instance-identifying key, enabling direct zero-shot forgetting without weight updates or access to the original samples or labels. Across natural image benchmarks, fine-grained recognition, and medical datasets, MUNKEY outperforms all post-hoc baselines. Our results establish that unlearning by design enables fast, deployment-oriented unlearning while preserving predictive performance.
### Title:
          AnoleVLA: Lightweight Vision-Language-Action Model with Deep State Space Models for Mobile Manipulation
 - **Authors:** Yusuke Takagi, Motonari Kambara, Daichi Yashima, Koki Seno, Kento Tokura, Komei Sugiura
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this study, we address the problem of language-guided robotic manipulation, where a robot is required to manipulate a wide range of objects based on visual observations and natural language instructions. This task is essential for service robots that operate in human environments, and requires safety, efficiency, and task-level generality. Although Vision-Language-Action models (VLAs) have demonstrated strong performance for this task, their deployment in resource-constrained environments remains challenging because of the computational cost of standard transformer backbones. To overcome this limitation, we propose AnoleVLA, a lightweight VLA that uses a deep state space model to process multimodal sequences efficiently. The model leverages its lightweight and fast sequential state modeling to process visual and textual inputs, which allows the robot to generate trajectories efficiently. We evaluated the proposed method in both simulation and physical experiments. Notably, in real-world evaluations, AnoleVLA outperformed a representative large-scale VLA by 21 points for the task success rate while achieving an inference speed approximately three times faster.
### Title:
          A Tutorial on ALOS2 SAR Utilization: Dataset Preparation, Self-Supervised Pretraining, and Semantic Segmentation
 - **Authors:** Nevrez Imamoglu, Ali Caglayan, Toru Kouyama
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Masked auto-encoders (MAE) and related approaches have shown promise for satellite imagery, but their application to synthetic aperture radar (SAR) remains limited due to challenges in semantic labeling and high noise levels. Building on our prior work with SAR-W-MixMAE, which adds SAR-specific intensity-weighted loss to standard MixMAE for pretraining, we also introduce SAR-W-SimMIM; a weighted variant of SimMIM applied to ALOS-2 single-channel SAR imagery. This method aims to reduce the impact of speckle and extreme intensity values during self-supervised pretraining. We evaluate its effect on semantic segmentation compared to our previous trial with SAR-W-MixMAE and random initialization, observing notable improvements. In addition, pretraining and fine-tuning models on satellite imagery pose unique challenges, particularly when developing region-specific models. Imbalanced land cover distributions such as dominant water, forest, or desert areas can introduce bias, affecting both pretraining and downstream tasks like land cover segmentation. To address this, we constructed a SAR dataset using ALOS-2 single-channel (HH polarization) imagery focused on the Japan region, marking the initial phase toward a national-scale foundation model. This dataset was used to pretrain a vision transformer-based autoencoder, with the resulting encoder fine-tuned for semantic segmentation using a task-specific decoder. Initial results demonstrate significant performance improvements compared to training from scratch with random initialization. In summary, this work provides a guide to process and prepare ALOS2 observations to create dataset so that it can be taken advantage of self-supervised pretraining of models and finetuning downstream tasks such as semantic segmentation.
### Title:
          Indirect Question Answering in English, German and Bavarian: A Challenging Task for High- and Low-Resource Languages Alike
 - **Authors:** Miriam Winkler, Verena Blaschke, Barbara Plank
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Indirectness is a common feature of daily communication, yet is underexplored in NLP research for both low-resource as well as high-resource languages. Indirect Question Answering (IQA) aims at classifying the polarity of indirect answers. In this paper, we present two multilingual corpora for IQA of varying quality that both cover English, Standard German and Bavarian, a German dialect without standard orthography: InQA+, a small high-quality evaluation dataset with hand-annotated labels, and GenIQA, a larger training dataset, that contains artificial data generated by GPT-4o-mini. We find that IQA is a pragmatically hard task that comes with various challenges, based on several experiment variations with multilingual transformer models (mBERT, XLM-R and mDeBERTa). We suggest and employ recommendations to tackle these challenges. Our results reveal low performance, even for English, and severe overfitting. We analyse various factors that influence these results, including label ambiguity, label set and dataset size. We find that the IQA performance is poor in high- (English, German) and low-resource languages (Bavarian) and that it is beneficial to have a large amount of training data. Further, GPT-4o-mini does not possess enough pragmatic understanding to generate high-quality IQA data in any of our tested languages.
### Title:
          Low-light Image Enhancement with Retinex Decomposition in Latent Space
 - **Authors:** Bolun Zheng, Qingshan Lei, Quan Chen, Qianyu Zhang, Kainan Yu, Xu Jia, Lingyu Zhu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Retinex theory provides a principled foundation for low-light image enhancement, inspiring numerous learning-based methods that integrate its principles. However, existing methods exhibits limitations in accurately decomposing reflectance and illumination components. To address this, we propose a Retinex-Guided Transformer~(RGT) model, which is a two-stage model consisting of decomposition and enhancement phases. First, we propose a latent space decomposition strategy to separate reflectance and illumination components. By incorporating the log transformation and 1-pixel offset, we convert the intrinsically multiplicative relationship into an additive formulation, enhancing decomposition stability and precision. Subsequently, we construct a U-shaped component refiner incorporating the proposed guidance fusion transformer block. The component refiner refines reflectance component to preserve texture details and optimize illumination distribution, effectively transforming low-light inputs to normal-light counterparts. Experimental evaluations across four benchmark datasets validate that our method achieves competitive performance in low-light enhancement and a more stable training process.
### Title:
          WiT: Waypoint Diffusion Transformers via Trajectory Conflict Navigation
 - **Authors:** Hainuo Wang, Mingjia Li, Xiaojie Guo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While recent Flow Matching models avoid the reconstruction bottlenecks of latent autoencoders by operating directly in pixel space, the lack of semantic continuity in the pixel manifold severely intertwines optimal transport paths. This induces severe trajectory conflicts near intersections, yielding sub-optimal solutions. Rather than bypassing this issue via information-lossy latent representations, we directly untangle the pixel-space trajectories by proposing Waypoint Diffusion Transformers (WiT). WiT factorizes the continuous vector field via intermediate semantic waypoints projected from pre-trained vision models. It effectively disentangles the generation trajectories by breaking the optimal transport into prior-to-waypoint and waypoint-to-pixel segments. Specifically, during the iterative denoising process, a lightweight generator dynamically infers these intermediate waypoints from the current noisy state. They then continuously condition the primary diffusion transformer via the Just-Pixel AdaLN mechanism, steering the evolution towards the next state, ultimately yielding the final RGB pixels. Evaluated on ImageNet 256x256, WiT beats strong pixel-space baselines, accelerating JiT training convergence by 2.2x. Code will be publicly released at this https URL.
### Title:
          Vision-Language Model Based Multi-Expert Fusion for CT Image Classification
 - **Authors:** Jianfa Bai, Kejin Lu, Runtian Yuan, Qingqiu Li, Jilan Xu, Junlin Hou, Yuejie Zhang, Rui Feng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust detection of COVID-19 from chest CT remains challenging in multi-institutional settings due to substantial source shift, source imbalance, and hidden test-source identities. In this work, we propose a three-stage source-aware multi-expert framework for multi-source COVID-19 CT classification. First, we build a lung-aware 3D expert by combining original CT volumes and lung-extracted CT volumes for volumetric classification. Second, we develop two MedSigLIP-based experts: a slice-wise representation and probability learning module, and a Transformer-based inter-slice context modeling module for capturing cross-slice dependency. Third, we train a source classifier to predict the latent source identity of each test scan. By leveraging the predicted source information, we perform model fusion and voting based on different experts. On the validation set covering all four sources, the Stage 1 model achieves the best macro-F1 of 0.9711, ACC of 0.9712, and AUC of 0.9791. Stage~2a and Stage~2b achieve the best AUC scores of 0.9864 and 0.9854, respectively. Stage~3 source classifier reaches 0.9107 ACC and 0.9114 F1. These results demonstrate that source-aware expert modeling and hierarchical voting provide an effective solution for robust COVID-19 CT classification under heterogeneous multi-source conditions.
### Title:
          Question-guided Visual Compression with Memory Feedback for Long-Term Video Understanding
 - **Authors:** Sosuke Yamao, Natsuki Miyahara, Yuankai Qi, Shun Takeuchi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In the context of long-term video understanding with large multimodal models, many frameworks have been proposed. Although transformer-based visual compressors and memory-augmented approaches are often used to process long videos, they usually compress each frame independently and therefore fail to achieve strong performance on tasks that require understanding complete events, such as temporal ordering tasks in MLVU and VNBench. This motivates us to rethink the conventional one-way scheme from perception to memory, and instead establish a feedbackdriven process in which past visual contexts stored in the context memory can benefit ongoing perception. To this end, we propose Question-guided Visual Compression with Memory Feedback (QViC-MF), a framework for long-term video understanding. At its core is a Question-guided Multimodal Selective Attention (QMSA), which learns to preserve visual information related to the given question from both the current clip and the past related frames from the memory. The compressor and memory feedback work iteratively for each clip of the entire video. This simple yet effective design yields large performance gains on longterm video understanding tasks. Extensive experiments show that our method achieves significant improvement over current state-of-the-art methods by 6.1% on MLVU test, 8.3% on LVBench, 18.3% on VNBench Long, and 3.7% on VideoMME Long. The code will be released publicly.
### Title:
          Multimodal Connectome Fusion via Cross-Attention for Autism Spectrum Disorder Classification Using Graph Learning
 - **Authors:** Ansar Rahman, Hassan Shojaee-Mend, Sepideh Hatamikia
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autism spectrum disorder (ASD) is a complex neurodevelopmental condition characterized by atypical functional brain connectivity and subtle structural alterations. rs-fMRI has been widely used to identify disruptions in large-scale brain networks, while structural MRI provides complementary information about morphological organization. Despite their complementary nature, effectively integrating these heterogeneous imaging modalities within a unified framework remains challenging. This study proposes a multimodal graph learning framework that preserves the dominant role of functional connectivity while integrating structural imaging and phenotypic information for ASD classification. The proposed framework is evaluated on ABIDE-I dataset. Each subject is represented as a node within a population graph. Functional and structural features are extracted as modality-specific node attributes, while inter-subject relationships are modeled using a pairwise association encoder (PAE) based on phenotypic information. Two Edge Variational GCNs are trained to learn subject-level embeddings. To enable effective multimodal integration, we introduce a novel asymmetric transformer-based cross-attention mechanism that allows functional embeddings to selectively incorporate complementary structural information while preserving functional dominance. The fused embeddings are then passed to a MLP for ASD classification. Using stratified 10-fold cross-validation, the framework achieved an AUC of 87.3% and an accuracy of 84.4%. Under leave-one-site-out cross-validation (LOSO-CV), the model achieved an average cross-site accuracy of 82.0%, outperforming existing methods by approximately 3% under 10-fold cross-validation and 7% under LOSO-CV. The proposed framework effectively integrates heterogeneous multimodal data from the multi-site ABIDE-I dataset, improving automated ASD classification across imaging sites.
### Title:
          CATFormer: When Continual Learning Meets Spiking Transformers With Dynamic Thresholds
 - **Authors:** Vaishnavi Nagabhushana, Kartikay Agrawal, Ayon Borthakur
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Neural and Evolutionary Computing (cs.NE); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Although deep neural networks perform extremely well in controlled environments, they fail in real-world scenarios where data isn't available all at once, and the model must adapt to a new data distribution that may or may not follow the initial distribution. Previously acquired knowledge is lost during subsequent updates based on new data. a phenomenon commonly known as catastrophic forgetting. In contrast, the brain can learn without such catastrophic forgetting, irrespective of the number of tasks it encounters. Existing spiking neural networks (SNNs) for class-incremental learning (CIL) suffer a sharp performance drop as tasks accumulate. We here introduce CATFormer (Context Adaptive Threshold Transformer), a scalable framework that overcomes this limitation. We observe that the key to preventing forgetting in SNNs lies not only in synaptic plasticity but also in modulating neuronal excitability. At the core of CATFormer is the Dynamic Threshold Leaky Integrate-and-Fire (DTLIF) neuron model, which leverages context-adaptive thresholds as the primary mechanism for knowledge retention. This is paired with a Gated Dynamic Head Selection (G-DHS) mechanism for task-agnostic inference. Extensive evaluation on both static (CIFAR-10/100/Tiny-ImageNet) and neuromorphic (CIFAR10-DVS/SHD) datasets reveals that CATFormer outperforms existing rehearsal-free CIL algorithms across various task splits, establishing it as an ideal architecture for energy-efficient, true-class incremental learning.
### Title:
          Massive Redundancy in Gradient Transport Enables Sparse Online Learning
 - **Authors:** Aur Shalev Merin
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-time recurrent learning (RTRL) computes exact online gradients by propagating a Jacobian tensor forward through recurrent dynamics, but at O(n^4) cost per step. Prior work has sought structured approximations (rank-1 compression, graph-based sparsity, Kronecker factorization). We show that, in the continuous error signal regime, the recurrent Jacobian is massively redundant:propagating through a random 6% of paths (k=4 of n=64) recovers 84 +/- 6% of full RTRL's adaptation ability across five seeds, and the absolute count k=4 remains effective from n=64 to n=256 (6% to 1.6%, recovery 84 to 78%), meaning sparse RTRL becomes relatively cheaper as networks grow. In RNNs, the recovery is selection-invariant (even adversarial path selection works) and exhibits a step-function transition from zero to any nonzero propagation. Spectral analysis reveals the mechanism: the Jacobian is full-rank but near-isotropic (condition numbers 2.6-6.5), so any random subset provides a directionally representative gradient estimate. On chaotic dynamics (Lorenz attractor), sparse propagation is more numerically stable than full RTRL (CV 13% vs. 88%), as subsampling avoids amplifying pathological spectral modes. The redundancy extends to LSTMs (k=4 matches full RTRL) and to transformers via sparse gradient transport (50% head sparsity outperforms the dense reference; 33% is borderline), with higher thresholds reflecting head specialization rather than isotropy. On real primate neural data, sparse RTRL (k=4) adapts online to cross-session electrode drift (80 +/- 11% recovery, 5 seeds), where sparse propagation is again more stable than full RTRL. Without continuous error signal, Jacobian propagation accumulates numerical drift and degrades all RTRL variants, a scope condition for all forward-mode methods. Results hold with SGD (92 +/- 1% recovery), suggesting independence from optimizer choice.
### Title:
          Modeling Matches as Language: A Generative Transformer Approach for Counterfactual Player Valuation in Football
 - **Authors:** Miru Hong, Minho Lee, Geonhee Jo, Hyeokje Jo, Pascal Bauer, Sang-Ki Ko
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Evaluating football player transfers is challenging because player actions depend strongly on tactical systems, teammates, and match context. Despite this complexity, recruitment decisions often rely on static statistics and subjective expert judgment, which do not fully account for these contextual factors. This limitation stems largely from the absence of counterfactual simulation mechanisms capable of predicting outcomes in hypothetical scenarios. To address these challenges, we propose ScoutGPT, a generative model that treats football match events as sequential tokens within a language modeling framework. Utilizing a NanoGPT-based Transformer architecture trained on next-token prediction, ScoutGPT learns the dynamics of match event sequences to simulate event sequences under hypothetical lineups, demonstrating superior predictive performance compared to existing baseline models. Leveraging this capability, the model employs Monte Carlo sampling to enable counterfactual simulation, allowing for the assessment of unobserved scenarios. Experiments on K League data show that simulated player transfers lead to measurable changes in offensive progression and goal probabilities, indicating that ScoutGPT captures player-specific impact beyond traditional static metrics.
### Title:
          Towards Foundation Models for Consensus Rank Aggregation
 - **Authors:** Yijun Jin, Simon Klüttermann, Chiara Balestra, Emmanuel Müller
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Aggregating a consensus ranking from multiple input rankings is a fundamental problem with applications in recommendation systems, search engines, job recruitment, and elections. Despite decades of research in consensus ranking aggregation, minimizing the Kemeny distance remains computationally intractable. Specifically, determining an optimal aggregation of rankings with respect to the Kemeny distance is an NP-hard problem, limiting its practical application to relatively small-scale instances. We propose the Kemeny Transformer, a novel Transformer-based algorithm trained via reinforcement learning to efficiently approximate the Kemeny optimal ranking. Experimental results demonstrate that our model outperforms classical majority-heuristic and Markov-chain approaches, achieving substantially faster inference than integer linear programming solvers. Our approach thus offers a practical, scalable alternative for real-world ranking-aggregation tasks.
### Title:
          Mechanistic Foundations of Goal-Directed Control
 - **Authors:** Alma Lago
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mechanistic interpretability has transformed the analysis of transformer circuits by decomposing model behavior into competing algorithms, identifying phase transitions during training, and deriving closed-form predictions for when and why strategies shift. However, this program has remained largely confined to sequence-prediction architectures, leaving embodied control systems without comparable mechanistic accounts. Here we extend this framework to sensorimotor-cognitive development, using infant motor learning as a model system. We show that foundational inductive biases give rise to causal control circuits, with learned gating mechanisms converging toward theoretically motivated uncertainty thresholds. The resulting dynamics reveal a clean phase transition in the arbitration gate whose commitment behavior is well described by a closed-form exponential moving-average surrogate. We identify context window k as the critical parameter governing circuit formation: below a minimum threshold (k$\leq$4) the arbitration mechanism cannot form; above it (k$\geq$8), gate confidence scales asymptotically as log k. A two-dimensional phase diagram further reveals task-demand-dependent route arbitration consistent with the prediction that prospective execution becomes advantageous only when prediction error remains within the task tolerance window. Together, these results provide a mechanistic account of how reactive and prospective control strategies emerge and compete during learning. More broadly, this work sharpens mechanistic accounts of cognitive development and provides principled guidance for the design of interpretable embodied agents.
### Title:
          MoE-ACT: Scaling Multi-Task Bimanual Manipulation with Sparse Language-Conditioned Mixture-of-Experts Transformers
 - **Authors:** Kangjun Guo, Haichao Liu, Yanji Sun, Ruhan Zhao, Jinni Zhou, Jun Ma
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The ability of robots to handle multiple tasks under a unified policy is critical for deploying embodied intelligence in real-world household and industrial applications. However, out-of-distribution variation across tasks often causes severe task interference and negative transfer when training general robotic policies. To address this challenge, we propose a lightweight multi-task imitation learning framework for bimanual manipulation, termed Mixture-of-Experts-Enhanced Action Chunking Transformer (MoE-ACT), which integrates sparse Mixture-of-Experts (MoE) modules into the Transformer encoder of ACT. The MoE layer decomposes a unified task policy into independently invoked expert components. Through adaptive activation, it naturally decouples multi-task action distributions in latent space. During decoding, Feature-wise Linear Modulation (FiLM) dynamically modulates action tokens to improve consistency between action generation and task instructions. In parallel, multi-scale cross-attention enables the policy to simultaneously focus on both low-level and high-level semantic features, providing rich visual information for robotic manipulation. We further incorporate textual information, transitioning the framework from a purely vision-based model to a vision-centric, language-conditioned action generation system. Experimental validation in both simulation and a real-world dual-arm setup shows that MoE-ACT substantially improves multi-task performance. Specifically, MoE-ACT outperforms vanilla ACT by an average of 33% in success rate. These results indicate that MoE-ACT provides stronger robustness and generalization in complex multi-task bimanual manipulation environments. Our open-source project page can be found at this https URL.
### Title:
          GNIO: Gated Neural Inertial Odometry
 - **Authors:** Dapeng Feng, Yizhen Yin, Zhiqiang Chen, Yuhua Qi, Hongbo Chen
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Inertial navigation using low-cost MEMS sensors is plagued by rapid drift due to sensor noise and bias instability. While recent data-driven approaches have made significant strides, they often struggle with micro-drifts during stationarity and mode fusion during complex motion transitions due to their reliance on fixed-window regression. In this work, we introduce Gated Neural Inertial Odometry (GNIO), a novel learning-based framework that explicitly models motion validity and context. We propose two key architectural innovations: \ding{182} a learnable Motion Bank that queries a global dictionary of motion patterns to provide semantic context beyond the local receptive field, and \ding{183} a Gated Prediction Head that decomposes displacement into magnitude and direction. This gating mechanism acts as a soft, differentiable Zero-Velocity Update (ZUPT), dynamically suppressing sensor noise during stationary periods while scaling predictions during dynamic motion. Extensive experiments across four public benchmarks demonstrate that GNIO significantly reduces position drift compared to state-of-the-art CNN and Transformer-based baselines. Notably, GNIO achieves a $60.21\%$ reduction in trajectory error on the OxIOD dataset and exhibits superior generalization in challenging scenarios involving frequent stops and irregular motion speeds.
### Title:
          DOS: Dependency-Oriented Sampler for Masked Diffusion Language Models
 - **Authors:** Xueyu Zhou, Yangrong Hu, Jian Huang
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Masked diffusion language models (MDLMs) have recently emerged as a new paradigm in language modeling, offering flexible generation dynamics and enabling efficient parallel decoding. However, existing decoding strategies for pre-trained MDLMs predominantly rely on token-level uncertainty criteria, while largely overlooking sequence-level information and inter-token dependencies. To address this limitation, we propose Dependency-Oriented Sampler (DOS), a training-free decoding strategy that leverages inter-token dependencies to inform token updates during generation. Specifically, DOS exploits attention matrices from transformer blocks to approximate inter-token dependencies, emphasizing information from unmasked tokens when updating masked positions. Empirical results demonstrate that DOS consistently achieves superior performance on both code generation and mathematical reasoning tasks. Moreover, DOS can be seamlessly integrated with existing parallel sampling methods, leading to improved generation efficiency without sacrificing generation quality.
### Title:
          AnyCrowd: Instance-Isolated Identity-Pose Binding for Arbitrary Multi-Character Animation
 - **Authors:** Zhenyu Xie, Ji Xia, Michael Kampffmeyer, Panwen Hu, Zehua Ma, Yujian Zheng, Jing Wang, Zheng Chong, Xujie Zhang, Xianhang Cheng, Xiaodan Liang, Hao Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Controllable character animation has advanced rapidly in recent years, yet multi-character animation remains underexplored. As the number of characters grows, multi-character reference encoding becomes more susceptible to latent identity entanglement, resulting in identity bleeding and reduced controllability. Moreover, learning precise and spatio-temporally consistent correspondences between reference identities and driving pose sequences becomes increasingly challenging, often leading to identity-pose mis-binding and inconsistency in generated videos. To address these challenges, we propose AnyCrowd, a Diffusion Transformer (DiT)-based video generation framework capable of scaling to an arbitrary number of characters. Specifically, we first introduce an Instance-Isolated Latent Representation (IILR), which encodes character instances independently prior to DiT processing to prevent latent identity entanglement. Building on this disentangled representation, we further propose Tri-Stage Decoupled Attention (TSDA) to bind identities to driving poses by decomposing self-attention into: (i) instance-aware foreground attention, (ii) background-centric interaction, and (iii) global foreground-background coordination. Furthermore, to mitigate token ambiguity in overlapping regions, an Adaptive Gated Fusion (AGF) module is integrated within TSDA to predict identity-aware weights, effectively fusing competing token groups into identity-consistent representations...
### Title:
          ViFeEdit: A Video-Free Tuner of Your Video Diffusion Transformer
 - **Authors:** Ruonan Yu, Zhenxiong Tan, Zigeng Chen, Songhua Liu, Xinchao Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformers (DiTs) have demonstrated remarkable scalability and quality in image and video generation, prompting growing interest in extending them to controllable generation and editing tasks. However, compared to the image counterparts, progress in video control and editing remains limited, mainly due to the scarcity of paired video data and the high computational cost of training video diffusion models. To address this issue, in this paper, we propose a video-free tuning framework termed ViFeEdit for video diffusion transformers. Without requiring any forms of video training data, ViFeEdit achieves versatile video generation and editing, adapted solely with 2D images. At the core of our approach is an architectural reparameterization that decouples spatial independence from the full 3D attention in modern video diffusion transformers, which enables visually faithful editing while maintaining temporal consistency with only minimal additional parameters. Moreover, this design operates in a dual-path pipeline with separate timestep embeddings for noise scheduling, exhibiting strong adaptability to diverse conditioning signals. Extensive experiments demonstrate that our method delivers promising results of controllable video generation and editing with only minimal training on 2D image data. Codes are available this https URL.
### Title:
          Real-Time Oriented Object Detection Transformer in Remote Sensing Images
 - **Authors:** Zeyu Ding, Yong Zhou, Jiaqi Zhao, Wen-Liang Du, Xixi Li, Rui Yao, Abdulmotaleb El Saddik
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent real-time detection transformers have gained popularity due to their simplicity and efficiency. However, these detectors do not explicitly model object rotation, especially in remote sensing imagery where objects appear at arbitrary angles, leading to challenges in angle representation, matching cost, and training stability. In this paper, we propose a real-time oriented object detection transformer, the first real-time end-to-end oriented object detector to the best of our knowledge, that addresses the above issues. Specifically, angle distribution refinement is proposed to reformulate angle regression as an iterative refinement of probability distributions, thereby capturing the uncertainty of object rotation and providing a more fine-grained angle representation. Then, we incorporate a Chamfer distance cost into bipartite matching, measuring box distance via vertex sets, enabling more accurate geometric alignment and eliminating ambiguous matches. Moreover, we propose oriented contrastive denoising to stabilize training and analyze four noise modes. We observe that a ground truth can be assigned to different index queries across different decoder layers, and analyze this issue using the proposed instability metric. We design a series of model variants and experiments to validate the proposed method. Notably, our O2-DFINE-L, O2-RTDETR-R50 and O2-DEIM-R50 achieve 77.73%/78.45%/80.15% AP50 on DOTA1.0 and 132/119/119 FPS on the 2080ti GPU. Code is available at this https URL.
### Title:
          DUET: Disaggregated Hybrid Mamba-Transformer LLMs with Prefill and Decode-Specific Packages
 - **Authors:** Alish Kanani, Sangwan Lee, Han Lyu, Jiahao Lin, Jaehyun Park, Umit Y. Ogras
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models operate in distinct compute-bound prefill followed by memory bandwidth-bound decode phases. Hybrid Mamba-Transformer models inherit this asymmetry while adding state space model (SSM) recurrences and element-wise operations that map poorly to matmul-centric accelerators. This mismatch causes performance bottlenecks, showing that a homogeneous architecture cannot satisfy all requirements. We introduce DUET, a disaggregated accelerator that assigns prefill and decode phases to specialized packages. The Prefill package utilizes systolic array chiplets with off-package memory for efficient large matrix multiplications and long-sequence SSMs. The Decode package utilizes vector-unit arrays with high-bandwidth in-package memory to accelerate token-by-token SSM and vector-matrix multiplications. Both architectures are runtime-configurable to support hybrid models with mixed Mamba and attention layers. Evaluations on Nemotron-H-56B, Zamba2-7B, and Llama3-8B across four workloads show that DUET achieves 4x faster time to first token, 1.4x higher throughput, and 1.5x lower time between tokens over the B200 GPU.
### Title:
          Mamba-3: Improved Sequence Modeling using State Space Principles
 - **Authors:** Aakash Lahoti, Kevin Y. Li, Berlin Chen, Caitlin Wang, Aviv Bick, J. Zico Kolter, Tri Dao, Albert Gu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scaling inference-time compute has emerged as an important driver of LLM performance, making inference efficiency a central focus of model design alongside model quality. While the current Transformer-based models deliver strong model quality, their quadratic compute and linear memory make inference expensive. This has spurred the development of sub-quadratic models with reduced linear compute and constant memory requirements. However, many recent linear models trade off model quality and capability for algorithmic efficiency, failing on tasks such as state tracking. Moreover, their theoretically linear inference remains hardware-inefficient in practice. Guided by an inference-first perspective, we introduce three core methodological improvements inspired by the state space model (SSM) viewpoint of linear models. We combine: (1) a more expressive recurrence derived from SSM discretization, (2) a complex-valued state update rule that enables richer state tracking, and (3) a multi-input, multi-output (MIMO) formulation for better model performance without increasing decode latency. Together with architectural refinements, our Mamba-3 model achieves significant gains across retrieval, state-tracking, and downstream language modeling tasks. At the 1.5B scale, Mamba-3 improves average downstream accuracy by 0.6 percentage points compared to the next best model (Gated DeltaNet), with Mamba-3's MIMO variant further improving accuracy by another 1.2 points for a total 1.8 point gain. Across state-size experiments, Mamba-3 achieves comparable perplexity to Mamba-2 despite using half of its predecessor's state size. Our evaluations demonstrate Mamba-3's ability to advance the performance-efficiency Pareto frontier.
### Title:
          Severe Domain Shift in Skeleton-Based Action Recognition:A Study of Uncertainty Failure in Real-World Gym Environments
 - **Authors:** Aaditya Khanal, Junxiu Zhou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The practical deployment gap -- transitioning from controlled multi-view 3D skeleton capture to unconstrained monocular 2D pose estimation -- introduces a compound domain shift whose safety implications remain critically underexplored. We present a systematic study of this severe domain shift using a novel Gym2D dataset (style/viewpoint shift) and the UCF101 dataset (semantic shift). Our Skeleton Transformer achieves 63.2% cross-subject accuracy on NTU-120 but drops to 1.6% under zero-shot transfer to the Gym domain and 1.16% on UCF101. Critically, we demonstrate that high Out-Of-Distribution (OOD) detection AUROC does not guarantee safe selective classification. Standard uncertainty methods fail to detect this performance drop: the model remains confidently incorrect with 99.6% risk even at 50% coverage across both OOD datasets. While energy-based scoring (AUROC >= 0.91) and Mahalanobis distance provide reliable distributional detection signals, such high AUROC scores coexist with poor risk-coverage behavior when making decisions. A lightweight finetuned gating mechanism restores calibration and enables graceful abstention, substantially reducing the rate of confident wrong predictions. Our work challenges standard deployment assumptions, providing a principled safety analysis of both semantic and geometric skeleton recognition deployment.
### Title:
          Effective Distillation to Hybrid xLSTM Architectures
 - **Authors:** Lukas Hauzenberger, Niklas Schmidinger, Thomas Schmied, Anamaria-Roberta Hartl, David Stap, Pieter-Jan Hoedt, Maximilian Beck, Sebastian Böck, Günter Klambauer, Sepp Hochreiter
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 There have been numerous attempts to distill quadratic attention-based large language models (LLMs) into sub-quadratic linearized architectures. However, despite extensive research, such distilled models often fail to match the performance of their teacher LLMs on various downstream tasks. We set out the goal of lossless distillation, which we define in terms of tolerance-corrected Win-and-Tie rates between student and teacher on sets of tasks. To this end, we introduce an effective distillation pipeline for xLSTM-based students. We propose an additional merging stage, where individually linearized experts are combined into a single model. We show the effectiveness of this pipeline by distilling base and instruction-tuned models from the Llama, Qwen, and Olmo families. In many settings, our xLSTM-based students recover most of the teacher's performance, and even exceed it on some downstream tasks. Our contributions are an important step towards more energy-efficient and cost-effective replacements for transformer-based LLMs.
### Title:
          Fast SAM 3D Body: Accelerating SAM 3D Body for Real-Time Full-Body Human Mesh Recovery
 - **Authors:** Timing Yang, Sicheng He, Hongyi Jing, Jiawei Yang, Zhijian Liu, Chuhang Zou, Yue Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 SAM 3D Body (3DB) achieves state-of-the-art accuracy in monocular 3D human mesh recovery, yet its inference latency of several seconds per image precludes real-time application. We present Fast SAM 3D Body, a training-free acceleration framework that reformulates the 3DB inference pathway to achieve interactive rates. By decoupling serial spatial dependencies and applying architecture-aware pruning, we enable parallelized multi-crop feature extraction and streamlined transformer decoding. Moreover, to extract the joint-level kinematics (SMPL) compatible with existing humanoid control and policy learning frameworks, we replace the iterative mesh fitting with a direct feedforward mapping, accelerating this specific conversion by over 10,000x. Overall, our framework delivers up to a 10.9x end-to-end speedup while maintaining on-par reconstruction fidelity, even surpassing 3DB on benchmarks such as LSPET. We demonstrate its utility by deploying Fast SAM 3D Body in a vision-only teleoperation system that-unlike methods reliant on wearable IMUs-enables real-time humanoid control and the direct collection of manipulation policies from a single RGB stream.
### Title:
          Look Before Acting: Enhancing Vision Foundation Representations for Vision-Language-Action Models
 - **Authors:** Yulin Luo, Hao Chen, Zhuangzhe Wu, Bowen Sui, Jiaming Liu, Chenyang Gu, Zhuoyang Liu, Qiuxuan Feng, Jiale Yu, Shuo Gu, Peng Jia, Pheng-Ann Heng, Shanghang Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models have recently emerged as a promising paradigm for robotic manipulation, in which reliable action prediction critically depends on accurately interpreting and integrating visual observations conditioned on language instructions. Although recent works have sought to enhance the visual capabilities of VLA models, most approaches treat the LLM backbone as a black box, providing limited insight into how visual information is grounded into action generation. Therefore, we perform a systematic analysis of multiple VLA models across different action-generation paradigms and observe that sensitivity to visual tokens progressively decreases in deeper layers during action generation. Motivated by this observation, we propose \textbf{DeepVision-VLA}, built on a \textbf{Vision-Language Mixture-of-Transformers (VL-MoT)} framework. This framework enables shared attention between the vision foundation model and the VLA backbone, injecting multi-level visual features from the vision expert into deeper layers of the VLA backbone to enhance visual representations for precise and complex manipulation. In addition, we introduce \textbf{Action-Guided Visual Pruning (AGVP)}, which leverages shallow-layer attention to prune irrelevant visual tokens while preserving task-relevant ones, reinforcing critical visual cues for manipulation with minimal computational overhead. DeepVision-VLA outperforms prior state-of-the-art methods by 9.0\% and 7.5\% on simulated and real-world tasks, respectively, providing new insights for the design of visually enhanced VLA models.
## Keyword: autonomous driving
### Title:
          FlowAD: Ego-Scene Interactive Modeling for Autonomous Driving
 - **Authors:** Mingzhe Guo, Yixiang Yang, Chuanrong Han, Rufeng Zhang, Shirui Li, Ji Wan, Zhipeng Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Effective environment modeling is the foundation for autonomous driving, underpinning tasks from perception to planning. However, current paradigms often inadequately consider the feedback of ego motion to the observation, which leads to an incomplete understanding of the driving process and consequently limits the planning capability. To address this issue, we introduce a novel ego-scene interactive modeling paradigm. Inspired by human recognition, the paradigm represents ego-scene interaction as the scene flow relative to the ego-vehicle. This conceptualization allows for modeling ego-motion feedback within a feature learning pattern, advantageously utilizing existing log-replay datasets rather than relying on scenario simulations. We specifically propose FlowAD, a general flow-based framework for autonomous driving. Within it, an ego-guided scene partition first constructs basic flow units to quantify scene flow. The ego-vehicle's forward direction and steering velocity directly shape the partition, which reflects ego motion. Then, based on flow units, spatial and temporal flow predictions are performed to model dynamics of scene flow, encompassing both spatial displacement and temporal variation. The final task-aware enhancement exploits learned spatio-temporal flow dynamics to benefit diverse tasks through object and region-level strategies. We also propose a novel Frames before Correct Planning (FCP) metric to assess the scene understanding capability. Experiments in both open and closed-loop evaluations demonstrate FlowAD's generality and effectiveness across perception, end-to-end planning, and VLM analysis. Notably, FlowAD reduces 19% collision rate over SparseDrive with FCP improvements of 1.39 frames (60%) on nuScenes, and achieves an impressive driving score of 51.77 on Bench2Drive, proving the superiority. Code, model, and configurations will be released here.
### Title:
          Fine-tuning is Not Enough: A Parallel Framework for Collaborative Imitation and Reinforcement Learning in End-to-end Autonomous Driving
 - **Authors:** Zhexi Lian, Haoran Wang, Xuerun Yan, Weimeng Lin, Xianhong Zhang, Yongyu Chen, Jia Hu
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end autonomous driving is typically built upon imitation learning (IL), yet its performance is constrained by the quality of human demonstrations. To overcome this limitation, recent methods incorporate reinforcement learning (RL) through sequential fine-tuning. However, such a paradigm remains suboptimal: sequential RL fine-tuning can introduce policy drift and often leads to a performance ceiling due to its dependence on the pretrained IL policy. To address these issues, we propose PaIR-Drive, a general Parallel framework for collaborative Imitation and Reinforcement learning in end-to-end autonomous driving. During training, PaIR-Drive separates IL and RL into two parallel branches with conflict-free training objectives, enabling fully collaborative optimization. This design eliminates the need to retrain RL when applying a new IL policy. During inference, RL leverages the IL policy to further optimize the final plan, allowing performance beyond prior knowledge of IL. Furthermore, we introduce a tree-structured trajectory neural sampler to group relative policy optimization (GRPO) in the RL branch, which enhances exploration capability. Extensive analysis on NAVSIMv1 and v2 benchmark demonstrates that PaIR-Drive achieves Competitive performance of 91.2 PDMS and 87.9 EPDMS, building upon Transfuser and DiffusionDrive IL baselines. PaIR-Drive consistently outperforms existing RL fine-tuning methods, and could even correct human experts' suboptimal behaviors. Qualitative results further confirm that PaIR-Drive can effectively explore and generate high-quality trajectories.
### Title:
          Deconfounded Lifelong Learning for Autonomous Driving via Dynamic Knowledge Spaces
 - **Authors:** Jiayuan Du, Yuebing Song, Yiming Zhao, Xianghui Pan, Jiawei Lian, Yuchu Lu, Liuyi Wang, Chengju Liu, Qijun Chen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-End autonomous driving (E2E-AD) systems face challenges in lifelong learning, including catastrophic forgetting, difficulty in knowledge transfer across diverse scenarios, and spurious correlations between unobservable confounders and true driving intents. To address these issues, we propose DeLL, a Deconfounded Lifelong Learning framework that integrates a Dirichlet process mixture model (DPMM) with the front-door adjustment mechanism from causal inference. The DPMM is employed to construct two dynamic knowledge spaces: a trajectory knowledge space for clustering explicit driving behaviors and an implicit feature knowledge space for discovering latent driving abilities. Leveraging the non-parametric Bayesian nature of DPMM, our framework enables adaptive expansion and incremental updating of knowledge without predefining the number of clusters, thereby mitigating catastrophic forgetting. Meanwhile, the front-door adjustment mechanism utilizes the DPMM-derived knowledge as valid mediators to deconfound spurious correlations, such as those induced by sensor noise or environmental changes, and enhances the causal expressiveness of the learned representations. Additionally, we introduce an evolutionary trajectory decoder that enables non-autoregressive planning. To evaluate the lifelong learning performance of E2E-AD, we propose new evaluation protocols and metrics based on Bench2Drive. Extensive evaluations in the closed-loop CARLA simulator demonstrate that our framework significantly improves adaptability to new driving scenarios and overall driving performance, while effectively retaining previous acquired knowledge.
### Title:
          DRCC-LPVMPC: Robust Data-Driven Control for Autonomous Driving and Obstacle Avoidance
 - **Authors:** Shiming Fang, Xilin Li, Changzhi Wu, Kaiyan Yu
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Safety in obstacle avoidance is critical for autonomous driving. While model predictive control (MPC) is widely used, simplified prediction models such as linearized or single-track vehicle models introduce discrepancies between predicted and actual behavior that can compromise safety. This paper proposes a distributionally robust chance-constrained linear parameter-varying MPC (DRCC-LPVMPC) framework that explicitly accounts for such discrepancies. The single-track vehicle dynamics are represented in a quasi-linear parameter-varying (quasi-LPV) form, with model mismatches treated as additive uncertainties of unknown distribution. By constructing chance constraints from finite sampled data and employing a Wasserstein ambiguity set, the proposed method avoids restrictive assumptions on boundedness or Gaussian distributions. The resulting DRCC problem is reformulated as tractable convex constraints and solved in real time using a quadratic programming solver. Recursive feasibility of the approach is formally established. Simulation and real-world experiments demonstrate that DRCC-LPVMPC maintains safer obstacle clearance and more reliable tracking than conventional nonlinear MPC and LPVMPC controllers under significant uncertainties.
### Title:
          WorldVLM: Combining World Model Forecasting and Vision-Language Reasoning
 - **Authors:** Stefan Englmeier, Katharina Winter, Fabian B. Flohr
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving systems depend on on models that can reason about high-level scene contexts and accurately predict the dynamics of their surrounding environment. Vision- Language Models (VLMs) have recently emerged as promising tools for decision-making and scene understanding, offering strong capabilities in contextual reasoning. However, their limited spatial comprehension constrains their effectiveness as end-to-end driving models. World Models (WM) internalize environmental dynamics to predict future scene evolution. Recently explored as ego-motion predictors and foundation models for autonomous driving, they represent a promising direction for addressing key challenges in the field, particularly enhancing generalization while maintaining dynamic prediction. To leverage the complementary strengths of context-based decision making and prediction, we propose WorldVLM: A hybrid architecture that unifies VLMs and WMs. In our design, the high-level VLM generates behavior commands to guide the driving WM, enabling interpretable and context-aware actions. We evaluate conditioning strategies and provide insights into the hybrid design challenges.
### Title:
          Learning to Order: Task Sequencing as In-Context Optimization
 - **Authors:** Jan Kobiolka, Christian Frey, Arlind Kadra, Gresa Shala, Josif Grabocka
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Task sequencing (TS) is one of the core open problems in Deep Learning, arising in a plethora of real-world domains, from robotic assembly lines to autonomous driving. Unfortunately, prior work has not convincingly demonstrated the generalization ability of meta-learned TS methods to solve new TS problems, given few initial demonstrations. In this paper, we demonstrate that deep neural networks can meta-learn over an infinite prior of synthetically generated TS problems and achieve a few-shot generalization. We meta-learn a transformer-based architecture over datasets of sequencing trajectories generated from a prior distribution that samples sequencing problems as paths in directed graphs. In a large-scale experiment, we provide ample empirical evidence that our meta-learned models discover optimal task sequences significantly quicker than non-meta-learned baselines.
### Title:
          TrajMamba: An Ego-Motion-Guided Mamba Model for Pedestrian Trajectory Prediction from an Egocentric Perspective
 - **Authors:** Yusheng Peng, Gaofeng Zhang, Liping Zheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Future trajectory prediction of a tracked pedestrian from an egocentric perspective is a key task in areas such as autonomous driving and robot navigation. The challenge of this task lies in the complex dynamic relative motion between the ego-camera and the tracked pedestrian. To address this challenge, we propose an ego-motion-guided trajectory prediction network based on the Mamba model. Firstly, two Mamba models are used as encoders to extract pedestrian motion and ego-motion features from pedestrian movement and ego-vehicle movement, respectively. Then, an ego-motion guided Mamba decoder that explicitly models the relative motion between the pedestrian and the vehicle by integrating pedestrian motion features as historical context with ego-motion features as guiding cues to capture decoded features. Finally, the future trajectory is generated from the decoded features corresponding to the future timestamps. Extensive experiments demonstrate the effectiveness of the proposed model, which achieves state-of-the-art performance on the PIE and JAAD datasets.
### Title:
          LiDAR-EVS: Enhance Extrapolated View Synthesis for 3D Gaussian Splatting with Pseudo-LiDAR Supervision
 - **Authors:** Yiming Huang, Xin Kang, Sipeng Zhang, Hongliang Ren, Weihua Zhang, Junjie Lai
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian Splatting (3DGS) has emerged as a powerful technique for real-time LiDAR and camera synthesis in autonomous driving simulation. However, simulating LiDAR with 3DGS remains challenging for extrapolated views beyond the training trajectory, as existing methods are typically trained on single-traversal sensor scans, suffer from severe overfitting and poor generalization to novel ego-vehicle paths. To enable reliable simulation of LiDAR along unseen driving trajectories without external multi-pass data, we present LiDAR-EVS, a lightweight framework for robust extrapolated-view LiDAR simulation in autonomous driving. Designed to be plug-and-play, LiDAR-EVS readily extends to diverse LiDAR sensors and neural rendering baselines with minimal modification. Our framework comprises two key components: (1) pseudo extrapolated-view point cloud supervision with multi-frame LiDAR fusion, view transformation, occlusion curling, and intensity adjustment; (2) spatially-constrained dropout regularization that promotes robustness to diverse trajectory variations encountered in real-world driving. Extensive experiments demonstrate that LiDAR-EVS achieves SOTA performance on extrapolated-view LiDAR synthesis across three datasets, making it a promising tool for data-driven simulation, closed-loop evaluation, and synthetic data generation in autonomous driving systems.
### Title:
          RadarXFormer: Robust Object Detection via Cross-Dimension Fusion of 4D Radar Spectra and Images for Autonomous Driving
 - **Authors:** Yue Sun, Yeqiang Qian, Zhe Wang, Tianhui Li, Chunxiang Wang, Ming Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable perception is essential for autonomous driving systems to operate safely under diverse real-world traffic conditions. However, camera- and LiDAR-based perception systems suffer from performance degradation under adverse weather and lighting conditions, limiting their robustness and large-scale deployment in intelligent transportation systems. Radar-vision fusion provides a promising alternative by combining the environmental robustness and cost efficiency of millimeter-wave (mmWave) radar with the rich semantic information captured by cameras. Nevertheless, conventional 3D radar measurements lack height resolution and remain highly sparse, while emerging 4D mmWave radar introduces elevation information but also brings challenges such as signal noise and large data volume. To address these issues, this paper proposes RadarXFormer, a 3D object detection framework that enables efficient cross-modal fusion between 4D radar spectra and RGB images. Instead of relying on sparse radar point clouds, RadarXFormer directly leverages raw radar spectra and constructs an efficient 3D representation that reduces data volume while preserving complete 3D spatial information. The "X" highlights the proposed cross-dimension (3D-2D) fusion mechanism, in which multi-scale 3D spherical radar feature cubes are fused with complementary 2D image feature maps. Experiments on the K-Radar dataset demonstrate improved detection accuracy and robustness under challenging conditions while maintaining real-time inference capability.
### Title:
          AutoMoT: A Unified Vision-Language-Action Model with Asynchronous Mixture-of-Transformers for End-to-End Autonomous Driving
 - **Authors:** Wenhui Huang, Songyan Zhang, Qihang Huang, Zhidong Wang, Zhiqi Mao, Collister Chua, Zhan Chen, Long Chen, Chen Lv
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Integrating vision-language models (VLMs) into end-to-end (E2E) autonomous driving (AD) systems has shown promise in improving scene understanding. However, existing integration strategies suffer from several limitations: they either struggle to resolve distribution misalignment between reasoning and action spaces, underexploit the general reasoning capabilities of pretrained VLMs, or incur substantial inference latency during action policy generation, which degrades driving performance. To address these challenges, we propose \OURS in this work, an end-to-end AD framework that unifies reasoning and action generation within a single vision-language-action (VLA) model. Our approach leverages a mixture-of-transformer (MoT) architecture with joint attention sharing, which preserves the general reasoning capabilities of pre-trained VLMs while enabling efficient fast-slow inference through asynchronous execution at different task frequencies. Extensive experiments on multiple benchmarks, under both open- and closed-loop settings, demonstrate that \OURS achieves competitive performance compared to state-of-the-art methods. We further investigate the functional boundary of pre-trained VLMs in AD, examining when AD-tailored fine-tuning is necessary. Our results show that pre-trained VLMs can achieve competitive multi-task scene understanding performance through semantic prompting alone, while fine-tuning remains essential for action-level tasks such as decision-making and trajectory planning. We refer to \href{this https URL}{Project Page} for the demonstration videos and qualitative results.
### Title:
          PerlAD: Towards Enhanced Closed-loop End-to-end Autonomous Driving with Pseudo-simulation-based Reinforcement Learning
 - **Authors:** Yinfeng Gao, Qichao Zhang, Deqing Liu, Zhongpu Xia, Guang Li, Kun Ma, Guang Chen, Hangjun Ye, Long Chen, Da-Wei Ding, Dongbin Zhao
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end autonomous driving policies based on Imitation Learning (IL) often struggle in closed-loop execution due to the misalignment between inadequate open-loop training objectives and real driving requirements. While Reinforcement Learning (RL) offers a solution by directly optimizing driving goals via reward signals, the rendering-based training environments introduce the rendering gap and are inefficient due to high computational costs. To overcome these challenges, we present a novel Pseudo-simulation-based RL method for closed-loop end-to-end autonomous driving, PerlAD. Based on offline datasets, PerlAD constructs a pseudo-simulation that operates in vector space, enabling efficient, rendering-free trial-and-error training. To bridge the gap between static datasets and dynamic closed-loop environments, PerlAD introduces a prediction world model that generates reactive agent trajectories conditioned on the ego vehicle's plan. Furthermore, to facilitate efficient planning, PerlAD utilizes a hierarchical decoupled planner that combines IL for lateral path generation and RL for longitudinal speed optimization. Comprehensive experimental results demonstrate that PerlAD achieves state-of-the-art performance on the Bench2Drive benchmark, surpassing the previous E2E RL method by 10.29% in Driving Score without requiring expensive online interactions. Additional evaluations on the DOS benchmark further confirm its reliability in handling safety-critical occlusion scenarios.
### Title:
          FAR-Drive: Frame-AutoRegressive Video Generation in Closed-Loop Autonomous Driving
 - **Authors:** Yaoru Li, Federico Landi, Marco Godi, Xin Jin, Ruiju Fu, Yufei Ma, Muyang Sun, Heyu Si, Qi Guo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite rapid progress in autonomous driving, reliable training and evaluation of driving systems remain fundamentally constrained by the lack of scalable and interactive simulation environments. Recent generative video models achieve remarkable visual fidelity, yet most operate in open-loop settings and fail to support fine-grained frame-level interaction between agent actions and environment evolution. Building a learning-based closed-loop simulator for autonomous driving poses three major challenges: maintaining long-horizon temporal and cross-view consistency, mitigating autoregressive degradation under iterative self-conditioning, and satisfying low-latency inference constraints. In this work, we propose FAR-Drive, a frame-level autoregressive video generation framework for autonomous driving. We introduce a multi-view diffusion transformer with fine-grained structured control, enabling geometrically consistent multi-camera generation. To address long-horizon consistency and iterative degradation, we design a two-stage training strategy consisting of adaptive reference horizon conditioning and blend-forcing autoregressive training, which progressively improves consistency and robustness under self-conditioning. To meet low-latency interaction requirements, we further integrate system-level efficiency optimizations for inference acceleration. Experiments on the nuScenes dataset demonstrate that our method achieves state-of-the-art performance among existing closed-loop autonomous driving simulation approaches, while maintaining sub-second latency on a single GPU.
### Title:
          Bridging Scene Generation and Planning: Driving with World Model via Unifying Vision and Motion Representation
 - **Authors:** Xingtai Gui, Meijie Zhang, Tianyi Yan, Wencheng Han, Jiahao Gong, Feiyang Tan, Cheng-zhong Xu, Jianbing Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end autonomous driving aims to generate safe and plausible planning policies from raw sensor input. Driving world models have shown great potential in learning rich representations by predicting the future evolution of a driving scene. However, existing driving world models primarily focus on visual scene representation, and motion representation is not explicitly designed to be planner-shared and inheritable, leaving a schism between the optimization of visual scene generation and the requirements of precise motion planning. We present WorldDrive, a holistic framework that couples scene generation and real-time planning via unifying vision and motion representation. We first introduce a Trajectory-aware Driving World Model, which conditions on a trajectory vocabulary to enforce consistency between visual dynamics and motion intentions, enabling the generation of diverse and plausible future scenes conditioned on a specific trajectory. We transfer the vision and motion encoders to a downstream Multi-modal Planner, ensuring the driving policy operates on mature representations pre-optimized by scene generation. A simple interaction between motion representation, visual representation, and ego status can generate high-quality, multi-modal trajectories. Furthermore, to exploit the world model's foresight, we propose a Future-aware Rewarder, which distills future latent representation from the frozen world model to evaluate and select optimal trajectories in real-time. Extensive experiments on the NAVSIM, NAVSIM-v2, and nuScenes benchmarks demonstrate that WorldDrive achieves leading planning performance among vision-only methods while maintaining high-fidelity action-controlled video generation capabilities, providing strong evidence for the effectiveness of unifying vision and motion representation for robust autonomous driving.
### Title:
          Learning from Mistakes: Post-Training for Driving VLA with Takeover Data
 - **Authors:** Yinfeng Gao, Deqing Liu, Qichao Zhang, Yupeng Zheng, Haochen Tian, Guang Li, Hangjun Ye, Long Chen, Da-Wei Ding, Dongbin Zhao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current Vision-Language-Action (VLA) paradigms in end-to-end autonomous driving rely on offline training from static datasets, leaving them vulnerable to distribution shift. Recent post-training methods use takeover data to mitigate this by augmenting the dataset with high-quality expert takeover samples, yet they suffer from two key limitations: supervision restricted to the period after the takeover moments leads to policies with limited safety margins, and passive preference optimization lacks active exploration for optimal performance. In this paper, we propose TakeVLA, a novel VLA post-training framework that overcomes these shortcomings through two complementary innovations. First, we introduce pre-takeover language supervision, which allows the VLA to learn from mistakes proactively. By explicitly teaching the model about what to do in error-prone situations, we cultivate a precautionary mindset that anticipates hazards early and substantially enlarges safety margins. Second, we propose Scenario Dreaming, a reinforcement fine-tuning paradigm that operates in reconstruceted takeover scenarios, encouraging active exploration beyond mere preference fitting. Experiments on the Bench2Drive benchmark demonstrate that TakeVLA achieves state-of-the-art closed-loop performance, surpassing the strong VLA baseline SimLingo by 4.93 in driving score, with an enhanced safety margin as evidenced by an 11.76% increase in average TTC.
### Title:
          What Matters for Scalable and Robust Learning in End-to-End Driving Planners?
 - **Authors:** David Holtz, Niklas Hanselmann, Simon Doll, Marius Cordts, Bernt Schiele
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end autonomous driving has gained significant attention for its potential to learn robust behavior in interactive scenarios and scale with data. Popular architectures often build on separate modules for perception and planning connected through latent representations, such as bird's eye view feature grids, to maintain end-to-end differentiability. This paradigm emerged mostly on open-loop datasets, with evaluation focusing not only on driving performance, but also intermediate perception tasks. Unfortunately, architectural advances that excel in open-loop often fail to translate to scalable learning of robust closed-loop driving. In this paper, we systematically re-examine the impact of common architectural patterns on closed-loop performance: (1) high-resolution perceptual representations, (2) disentangled trajectory representations, and (3) generative planning. Crucially, our analysis evaluates the combined impact of these patterns, revealing both unexpected limitations as well as underexplored synergies. Building on these insights, we introduce BevAD, a novel lightweight and highly scalable end-to-end driving architecture. BevAD achieves 72.7% success rate on the Bench2Drive benchmark and demonstrates strong data-scaling behavior using pure imitation learning. Our code and models are publicly available here: this https URL
### Title:
          ADV-0: Closed-Loop Min-Max Adversarial Training for Long-Tail Robustness in Autonomous Driving
 - **Authors:** Tong Nie, Yihong Tang, Junlin He, Yuewen Mei, Jie Sun, Lijun Sun, Wei Ma, Jian Sun
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deploying autonomous driving systems requires robustness against long-tail scenarios that are rare but safety-critical. While adversarial training offers a promising solution, existing methods typically decouple scenario generation from policy optimization and rely on heuristic surrogates. This leads to objective misalignment and fails to capture the shifting failure modes of evolving policies. This paper presents ADV-0, a closed-loop min-max optimization framework that treats the interaction between driving policy (defender) and adversarial agent (attacker) as a zero-sum Markov game. By aligning the attacker's utility directly with the defender's objective, we reveal the optimal adversary distribution. To make this tractable, we cast dynamic adversary evolution as iterative preference learning, efficiently approximating this optimum and offering an algorithm-agnostic solution to the game. Theoretically, ADV-0 converges to a Nash Equilibrium and maximizes a certified lower bound on real-world performance. Experiments indicate that it effectively exposes diverse safety-critical failures and greatly enhances the generalizability of both learned policies and motion planners against unseen long-tail risks.
### Title:
          CRASH: Cognitive Reasoning Agent for Safety Hazards in Autonomous Driving
 - **Authors:** Erick Silva, Rehana Yasmin, Ali Shoker
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As AVs grow in complexity and diversity, identifying the root causes of operational failures has become increasingly complex. The heterogeneity of system architectures across manufacturers, ranging from end-to-end to modular designs, together with variations in algorithms and integration strategies, limits the standardization of incident investigations and hinders systematic safety analysis. This work examines real-world AV incidents reported in the NHTSA database. We curate a dataset of 2,168 cases reported between 2021 and 2025, representing more than 80 million miles driven. To process this data, we introduce CRASH, Cognitive Reasoning Agent for Safety Hazards, an LLM-based agent that automates reasoning over crash reports by leveraging both standardized fields and unstructured narrative descriptions. CRASH operates on a unified representation of each incident to generate concise summaries, attribute a primary cause, and assess whether the AV materially contributed to the event. Our findings show that (1) CRASH attributes 64% of incidents to perception or planning failures, underscoring the importance of reasoning-based analysis for accurate fault attribution; and (2) approximately 50% of reported incidents involve rear-end collisions, highlighting a persistent and unresolved challenge in autonomous driving deployment. We further validate CRASH with five domain experts, achieving 86% accuracy in attributing AV system failures. Overall, CRASH demonstrates strong potential as a scalable and interpretable tool for automated crash analysis, providing actionable insights to support safety research and the continued development of autonomous driving systems.
