# Showing new listings for Wednesday, 11 March 2026
## Keyword: SLAM
### Title:
          Overlapping Schwarz Preconditioners for Pose-Graph SLAM in Robotics
 - **Authors:** Stephan Köhler, Oliver Rheinbach, Yue Xiang Tee, Sebastian Zug
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We investigate the application of the additive overlapping Schwarz domain decomposition method as a preconditioner for the large sparse linear systems arising in graph-based nonlinear least-squares problems, specifically the pose-graph optimization back-end in Simultaneous Localization and Mapping (SLAM) in robotics. A brief introduction to both SLAM and domain decomposition preconditioners is given, followed by a description of the nonlinear least-squares formulation, its linearization, and the resulting matrix structure, making the paper accessible to readers without prior knowledge of either field. Numerical experiments for a simple model problem demonstrate the numerical scalability of the preconditioned conjugate gradient method to solve the linear systems resulting from Gauss--Newton linearization: Using the additive overlapping Schwarz preconditioner, the number of conjugate gradient iterations remains bounded independently of the problem size. We also show that a simplified SLAM problem can be interpreted as a finite element problem using linear elastic bars, highlighting the structural analogy to PDE discretizations and motivating the use of PDE-based preconditioners such as scalable domain decomposition preconditioners.
### Title:
          Cutting the Cord: System Architecture for Low-Cost, GPU-Accelerated Bimanual Mobile Manipulation
 - **Authors:** Artemis Shaw, Chen Liu, Justin Costa, Rane Gray, Alina Skowronek, Kevin Diaz, Nam Bui, Nikolaus Correll
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a bimanual mobile manipulator built on the open-source XLeRobot with integrated onboard compute for less than \$1300. Key contributions include: (1) optimized mechanical design maximizing stiffness-to-weight ratio, (2) a Tri-Bus power topology isolating compute from motor-induced voltage transients, and (3) embedded autonomy using NVIDIA Jetson Orin Nano for untethered operation. The platform enables teleoperation, autonomous SLAM navigation, and vision-based manipulation without external dependencies, providing a low-cost alternative for research and education in robotics and robot learning.
### Title:
          X-GS: An Extensible Open Framework Unifying 3DGS Architectures with Downstream Multimodal Models
 - **Authors:** Yueen Ma, Irwin King
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian Splatting (3DGS) has emerged as a powerful technique for novel view synthesis, subsequently extending into numerous spatial AI applications. However, most existing 3DGS methods are isolated, focusing on specific domains such as online SLAM, semantic enrichment, or 3DGS for unposed images. In this paper, we introduce X-GS, an extensible open framework that unifies a broad range of techniques to enable real-time 3DGS-based online SLAM enriched with semantics, bridging the gap to downstream multimodal models. At the core of X-GS is a highly efficient pipeline called X-GS-Perceiver, capable of taking unposed RGB (or optionally RGB-D) video streams as input to co-optimize geometry and poses, and distill high-dimensional semantic features from vision foundation models into the 3D Gaussians. We achieve real-time performance through a novel online Vector Quantization (VQ) module, a GPU-accelerated grid-sampling scheme, and a highly parallelized pipeline design. The semantic 3D Gaussians can then be utilized by vision-language models within the X-GS-Thinker component, enabling downstream tasks such as object detection, zero-shot caption generation, and potentially embodied tasks. Experimental results on real-world datasets showcase the efficacy, efficiency, and newly unlocked multimodal capabilities of the X-GS framework.
### Title:
          VarSplat: Uncertainty-aware 3D Gaussian Splatting for Robust RGB-D SLAM
 - **Authors:** Anh Thuan Tran, Jana Kosecka
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Simultaneous Localization and Mapping (SLAM) with 3D Gaussian Splatting (3DGS) enables fast, differentiable rendering and high-fidelity reconstruction across diverse real-world scenes. However, existing 3DGS-SLAM approaches handle measurement reliability implicitly, making pose estimation and global alignment susceptible to drift in low-texture regions, transparent surfaces, or areas with complex reflectance properties. To this end, we introduce VarSplat, an uncertainty-aware 3DGS-SLAM system that explicitly learns per-splat appearance variance. By using the law of total variance with alpha compositing, we then render differentiable per-pixel uncertainty map via efficient, single-pass rasterization. This map guides tracking, submap registration, and loop detection toward focusing on reliable regions and contributes to more stable optimization. Experimental results on Replica (synthetic) and TUM-RGBD, ScanNet, and ScanNet++ (real-world) show that VarSplat improves robustness and achieves competitive or superior tracking, mapping, and novel view synthesis rendering compared to existing studies for dense RGB-D SLAM.
## Keyword: odometry
### Title:
          OTPL-VIO: Robust Visual-Inertial Odometry with Optimal Transport Line Association and Adaptive Uncertainty
 - **Authors:** Zikun Chen, Wentao Zhao, Yihe Niu, Tianchen Deng, Jingchuan Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust stereo visual-inertial odometry (VIO) remains challenging in low-texture scenes and under abrupt illumination changes, where point features become sparse and unstable, leading to ambiguous association and under-constrained estimation. Line structures offer complementary geometric cues, yet many efficient point-line systems still rely on point-guided line association, which can break down when point support is weak and may lead to biased constraints. We present a stereo point-line VIO system in which line segments are equipped with dedicated deep descriptors and matched using an entropy-regularized optimal transport formulation, enabling globally consistent correspondences under ambiguity, outliers, and partial observations. The proposed descriptor is training-free and is computed by sampling and pooling network feature maps. To improve estimation stability, we analyze the impact of line measurement noise and introduce reliability-adaptive weighting to regulate the influence of line constraints during optimization. Experiments on EuRoC and UMA-VI, together with real-world deployments in low-texture and illumination-challenging environments, demonstrate improved accuracy and robustness over representative baselines while maintaining real-time performance.
## Keyword: livox
### Title:
          Lightweight 3D LiDAR-Based UAV Tracking: An Adaptive Extended Kalman Filtering Approach
 - **Authors:** Nivand Khosravi, Meysam Basiri, Rodrigo Ventura
 - **Subjects:** Subjects:
Robotics (cs.RO); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate relative positioning is crucial for swarm aerial robotics, enabling coordinated flight and collision avoidance. Although vision-based tracking has been extensively studied, 3D LiDAR-based methods remain underutilized despite their robustness under varying lighting conditions. Existing systems often rely on bulky, power-intensive sensors, making them impractical for small UAVs with strict payload and energy constraints. This paper presents a lightweight LiDAR-based UAV tracking system incorporating an Adaptive Extended Kalman Filter (AEKF) framework. Our approach effectively addresses the challenges posed by sparse, noisy, and nonuniform point cloud data generated by non-repetitive scanning 3D LiDARs, ensuring reliable tracking while remaining suitable for small drones with strict payload constraints. Unlike conventional filtering techniques, the proposed method dynamically adjusts the noise covariance matrices using innovation and residual statistics, thereby enhancing tracking accuracy under real-world conditions. Additionally, a recovery mechanism ensures continuity of tracking during temporary detection failures caused by scattered LiDAR returns or occlusions. Experimental validation was performed using a Livox Mid-360 LiDAR mounted on a DJI F550 UAV in real-world flight scenarios. The proposed method demonstrated robust UAV tracking performance under sparse LiDAR returns and intermittent detections, consistently outperforming both standard Kalman filtering and particle filtering approaches during aggressive maneuvers. These results confirm that the framework enables reliable relative positioning in GPS-denied environments without the need for multi-sensor arrays or external infrastructure.
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          STONE Dataset: A Scalable Multi-Modal Surround-View 3D Traversability Dataset for Off-Road Robot Navigation
 - **Authors:** Konyul Park, Daehun Kim, Jiyong Oh, Seunghoon Yu, Junseo Park, Jaehyun Park, Hongjae Shin, Hyungchan Cho, Jungho Kim, Jun Won Choi
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable off-road navigation requires accurate estimation of traversable regions and robust perception under diverse terrain and sensing conditions. However, existing datasets lack both scalability and multi-modality, which limits progress in 3D traversability prediction. In this work, we introduce STONE, a large-scale multi-modal dataset for off-road navigation. STONE provides (1) trajectory-guided 3D traversability maps generated by a fully automated, annotation-free pipeline, and (2) comprehensive surround-view sensing with synchronized 128-channel LiDAR, six RGB cameras, and three 4D imaging radars. The dataset covers a wide range of environments and conditions, including day and night, grasslands, farmlands, construction sites, and lakes. Our auto-labeling pipeline reconstructs dense terrain surfaces from LiDAR scans, extracts geometric attributes such as slope, elevation, and roughness, and assigns traversability labels beyond the robot's trajectory using a Mahalanobis-distance-based criterion. This design enables scalable, geometry-aware ground-truth construction without manual annotation. Finally, we establish a benchmark for voxel-level 3D traversability prediction and provide strong baselines under both single-modal and multi-modal settings. STONE is available at: this https URL
### Title:
          SpaceSense-Bench: A Large-Scale Multi-Modal Benchmark for Spacecraft Perception and Pose Estimation
 - **Authors:** Aodi Wu, Jianhong Zuo, Zeyuan Zhao, Xubo Luo, Ruisuo Wang, Xue Wan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous space operations such as on-orbit servicing and active debris removal demand robust part-level semantic understanding and precise relative navigation of target spacecraft, yet collecting large-scale real data in orbit remains impractical due to cost and access constraints. Existing synthetic datasets, moreover, suffer from limited target diversity, single-modality sensing, and incomplete ground-truth annotations. We present \textbf{SpaceSense-Bench}, a large-scale multi-modal benchmark for spacecraft perception encompassing 136~satellite models with approximately 70~GB of data. Each frame provides time-synchronized 1024$\times$1024 RGB images, millimeter-precision depth maps, and 256-beam LiDAR point clouds, together with dense 7-class part-level semantic labels at both the pixel and point level as well as accurate 6-DoF pose ground truth. The dataset is generated through a high-fidelity space simulation built in Unreal Engine~5 and a fully automated pipeline covering data acquisition, multi-stage quality control, and conversion to mainstream formats. We benchmark five representative tasks (object detection, 2D semantic segmentation, RGB--LiDAR fusion-based 3D point cloud segmentation, monocular depth estimation, and orientation estimation) and identify two key findings: (i)~perceiving small-scale components (\emph{e.g.}, thrusters and omni-antennas) and generalizing to entirely unseen spacecraft in a zero-shot setting remain critical bottlenecks for current methods, and (ii)~scaling up the number of training satellites yields substantial performance gains on novel targets, underscoring the value of large-scale, diverse datasets for space perception research. The dataset, code, and toolkit are publicly available at this https URL.
### Title:
          DRIFT: Dual-Representation Inter-Fusion Transformer for Automated Driving Perception with 4D Radar Point Clouds
 - **Authors:** Siqi Pei, Andras Palffy, Dariu M. Gavrila
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 4D radars, which provide 3D point cloud data along with Doppler velocity, are attractive components of modern automated driving systems due to their low cost and robustness under adverse weather conditions. However, they provide a significantly lower point cloud density than LiDAR sensors. This makes it important to exploit not only local but also global contextual scene information. This paper proposes DRIFT, a model that effectively captures and fuses both local and global contexts through a dual-path architecture. The model incorporates a point path to aggregate fine-grained local features and a pillar path to encode coarse-grained global features. These two parallel paths are intertwined via novel feature-sharing layers at multiple stages, enabling full utilization of both representations. DRIFT is evaluated on the widely used View-of-Delft (VoD) dataset and a proprietary internal dataset. It outperforms the baselines on the tasks of object detection and/or free road estimation. For example, DRIFT achieves a mean average precision (mAP) of 52.6\% (compared to, say, 45.4\% of CenterPoint) on the VoD dataset.
### Title:
          Lightweight 3D LiDAR-Based UAV Tracking: An Adaptive Extended Kalman Filtering Approach
 - **Authors:** Nivand Khosravi, Meysam Basiri, Rodrigo Ventura
 - **Subjects:** Subjects:
Robotics (cs.RO); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate relative positioning is crucial for swarm aerial robotics, enabling coordinated flight and collision avoidance. Although vision-based tracking has been extensively studied, 3D LiDAR-based methods remain underutilized despite their robustness under varying lighting conditions. Existing systems often rely on bulky, power-intensive sensors, making them impractical for small UAVs with strict payload and energy constraints. This paper presents a lightweight LiDAR-based UAV tracking system incorporating an Adaptive Extended Kalman Filter (AEKF) framework. Our approach effectively addresses the challenges posed by sparse, noisy, and nonuniform point cloud data generated by non-repetitive scanning 3D LiDARs, ensuring reliable tracking while remaining suitable for small drones with strict payload constraints. Unlike conventional filtering techniques, the proposed method dynamically adjusts the noise covariance matrices using innovation and residual statistics, thereby enhancing tracking accuracy under real-world conditions. Additionally, a recovery mechanism ensures continuity of tracking during temporary detection failures caused by scattered LiDAR returns or occlusions. Experimental validation was performed using a Livox Mid-360 LiDAR mounted on a DJI F550 UAV in real-world flight scenarios. The proposed method demonstrated robust UAV tracking performance under sparse LiDAR returns and intermittent detections, consistently outperforming both standard Kalman filtering and particle filtering approaches during aggressive maneuvers. These results confirm that the framework enables reliable relative positioning in GPS-denied environments without the need for multi-sensor arrays or external infrastructure.
## Keyword: loop detection
### Title:
          VarSplat: Uncertainty-aware 3D Gaussian Splatting for Robust RGB-D SLAM
 - **Authors:** Anh Thuan Tran, Jana Kosecka
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Simultaneous Localization and Mapping (SLAM) with 3D Gaussian Splatting (3DGS) enables fast, differentiable rendering and high-fidelity reconstruction across diverse real-world scenes. However, existing 3DGS-SLAM approaches handle measurement reliability implicitly, making pose estimation and global alignment susceptible to drift in low-texture regions, transparent surfaces, or areas with complex reflectance properties. To this end, we introduce VarSplat, an uncertainty-aware 3DGS-SLAM system that explicitly learns per-splat appearance variance. By using the law of total variance with alpha compositing, we then render differentiable per-pixel uncertainty map via efficient, single-pass rasterization. This map guides tracking, submap registration, and loop detection toward focusing on reliable regions and contributes to more stable optimization. Experimental results on Replica (synthetic) and TUM-RGBD, ScanNet, and ScanNet++ (real-world) show that VarSplat improves robustness and achieves competitive or superior tracking, mapping, and novel view synthesis rendering compared to existing studies for dense RGB-D SLAM.
## Keyword: nerf
### Title:
          SkipGS: Post-Densification Backward Skipping for Efficient 3DGS Training
 - **Authors:** Jingxing Li, Yongjae Leeand, Deliang Fan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian Splatting (3DGS) achieves real-time novel-view synthesis by optimizing millions of anisotropic Gaussians, yet its training remains expensive, with the backward pass dominating runtime in the post-densification refinement phase. We observe substantial update redundancy in this phase: many sampled views have near-plateaued losses and provide diminishing gradient benefits, but standard training still runs full backpropagation. We propose SkipGS with a novel view-adaptive backward gating mechanism for efficient post-densification training. SkipGS always performs the forward pass to update per-view loss statistics, and selectively skips backward passes when the sampled view's loss is consistent with its recent per-view baseline, while enforcing a minimum backward budget for stable optimization. On Mip-NeRF 360, compared to 3DGS, SkipGS reduces end-to-end training time by 23.1%, driven by a 42.0% reduction in post-densification time, with comparable reconstruction quality. Because it only changes when to backpropagate -- without modifying the renderer, representation, or loss -- SkipGS is plug-and-play and compatible with other complementary efficiency strategies for additive speedups.
### Title:
          Speeding Up the Learning of 3D Gaussians with Much Shorter Gaussian Lists
 - **Authors:** Jiaqi Liu, Zhizhong Han
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian splatting (3DGS) has become a vital tool for learning a radiance field from multiple posed images. Although 3DGS shows great advantages over NeRF in terms of rendering quality and efficiency, it remains a research challenge to further improve the efficiency of learning 3D Gaussians. To overcome this challenge, we propose novel training strategies and losses to shorten each Gaussian list used to render a pixel, which speeds up the splatting by involving fewer Gaussians along a ray. Specifically, we shrink the size of each Gaussian by resetting their scales regularly, encouraging smaller Gaussians to cover fewer nearby pixels, which shortens the Gaussian lists of pixels. Additionally, we introduce an entropy constraint on the alpha blending procedure to sharpen the weight distribution of Gaussians along each ray, which drives dominant weights larger while making minor weights smaller. As a result, each Gaussian becomes more focused on the pixels where it is dominant, which reduces its impact on nearby pixels, leading to even shorter Gaussian lists. Eventually, we integrate our method into a rendering resolution scheduler which further improves efficiency through progressive resolution increase. We evaluate our method by comparing it with state-of-the-art methods on widely used benchmarks. Our results show significant advantages over others in efficiency without sacrificing rendering quality.
### Title:
          DenoiseSplat: Feed-Forward Gaussian Splatting for Noisy 3D Scene Reconstruction
 - **Authors:** Fuzhen Jiang, Zhuoran Li, Yinlin Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D scene reconstruction and novel-view synthesis are fundamental for VR, robotics, and content creation. However, most NeRF and 3D Gaussian Splatting pipelines assume clean inputs and degrade under real noise and artifacts. We therefore propose DenoiseSplat, a feed-forward 3D Gaussian splatting method for noisy multi-view images. We build a large-scale, scene-consistent noisy--clean benchmark on RE10K by injecting Gaussian, Poisson, speckle, and salt-and-pepper noise with controlled intensities. With a lightweight MVSplat-style feed-forward backbone, we train end-to-end using only clean 2D renderings as supervision and no 3D ground truth. On noisy RE10K, DenoiseSplat outperforms vanilla MVSplat and a strong two-stage baseline (IDF + MVSplat) in PSNR/SSIM and LPIPS across noise types and levels.
## Keyword: mapping
### Title:
          Data-Rate-Aware High-Speed CNN Inference on FPGAs
 - **Authors:** Tobias Habermann, Martin Kumm
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dataflow-based CNN accelerators on FPGAs achieve low latency and high throughput by mapping computations of each layer directly to corresponding hardware units. However, layers such as pooling and strided convolutions reduce the data at their output with respect to their input, strongly effecting the data rate of the following layers. This leads to underutilization in fully unrolled designs. While prior work introduced data-rate-aware layer-wise adaptation, determining the most efficient implementation remains challenging. This paper presents a data-rate-aware CNN accelerator architecture for multi-pixel processing. Building on existing analytical models, the proposed method performs design-space exploration to identify configurations that improve hardware utilization and resource efficiency while preserving continuous flow of data, keeping all hardware units busy. Experimental results show substantial reductions in arithmetic resources compared to previous designs, enabling efficient implementation of complex CNNs on a single FPGA across a wide range of data rates.
### Title:
          The Temporal Markov Transition Field
 - **Authors:** Michael Leznik
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Markov Transition Field (MTF), introduced by Wang and Oates (2015), encodes a time series as a two-dimensional image by mapping each pair of time steps to the transition probability between their quantile states, estimated from a single global transition matrix. This construction is efficient when the transition dynamics are stationary, but produces a misleading representation when the process changes regime over time: the global matrix averages across regimes and the resulting image loses all information about \emph{when} each dynamical regime was active. In this paper we introduce the \emph{Temporal Markov Transition Field} (TMTF), an extension that partitions the series into $K$ contiguous temporal chunks, estimates a separate local transition matrix for each chunk, and assembles the image so that each row reflects the dynamics local to its chunk rather than the global average. The resulting $T \times T$ image has $K$ horizontal bands of distinct texture, each encoding the transition dynamics of one temporal segment. We develop the formal definition, establish the key structural properties of the representation, work through a complete numerical example that makes the distinction from the global MTF concrete, analyse the bias--variance trade-off introduced by temporal chunking, and discuss the geometric interpretation of the local transition matrices in terms of process properties such as persistence, mean reversion, and trending behaviour. The TMTF is amplitude-agnostic and order-preserving, making it suitable as an input channel for convolutional neural networks applied to time series characterisation tasks.
### Title:
          Computer Vision-Based Vehicle Allotment System using Perspective Mapping
 - **Authors:** Prachi Nandi, Sonakshi Satapathy, Suchismita Chinara
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Smart city research envisions a future in which data-driven solutions and sustainable infrastructure work together to define urban living at the crossroads of urbanization and technology. Within this framework, smart parking systems play an important role in reducing urban congestion and supporting sustainable transportation. Automating parking solutions have considerable benefits, such as increased efficiency and less reliance on human involvement, but obstacles such as sensor limitations and integration complications remain. To overcome them, a more sophisticated car allotment system is required, particularly in heavily populated urban areas. Computer vision, with its higher accuracy and adaptability, outperforms traditional sensor-based systems for recognizing vehicles and vacant parking spaces. Unlike fixed sensor technologies, computer vision can dynamically assess a wide range of visual inputs while adjusting to changing parking layouts. This research presents a cost-effective, easy-to-implement smart parking system utilizing computer vision and object detection models like YOLOv8. Using inverse perspective mapping (IPM) to merge images from four camera views, we extract data on vacant spaces. The system simulates a 3D parking environment, representing available spots with a 3D Cartesian plot to guide users.
### Title:
          One Language, Two Scripts: Probing Script-Invariance in LLM Concept Representations
 - **Authors:** Sripad Karne
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Do the features learned by Sparse Autoencoders (SAEs) represent abstract meaning, or are they tied to how text is written? We investigate this question using Serbian digraphia as a controlled testbed: Serbian is written interchangeably in Latin and Cyrillic scripts with a near-perfect character mapping between them, enabling us to vary orthography while holding meaning exactly constant. Crucially, these scripts are tokenized completely differently, sharing no tokens whatsoever. Analyzing SAE feature activations across the Gemma model family (270M-27B parameters), we find that identical sentences in different Serbian scripts activate highly overlapping features, far exceeding random baselines. Strikingly, changing script causes less representational divergence than paraphrasing within the same script, suggesting SAE features prioritize meaning over orthographic form. Cross-script cross-paraphrase comparisons provide evidence against memorization, as these combinations rarely co-occur in training data yet still exhibit substantial feature overlap. This script invariance strengthens with model scale. Taken together, our findings suggest that SAE features can capture semantics at a level of abstraction above surface tokenization, and we propose Serbian digraphia as a general evaluation paradigm for probing the abstractness of learned representations.
### Title:
          Touching Emotions, Smelling Shapes: Exploring Tactile, Olfactory and Emotional Cross-sensory Correspondences in Preschool Aged Children
 - **Authors:** Tegan Roberts-Morgan, Min S. Li, Priscilla Lo, Zhuzhi Fan, Dan Bennett, Oussama Metatla
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The use of a wide range of sensory modalities is increasingly central to technologies for learning, communication, and affective regulation. During the preschool years, sensory integration develops rapidly, shaping how children perceive and make sense of their environments. A key component of this process is cross-sensory correspondence: the systematic ways in which perceptions in different sensory modalities influence one another. Despite its relevance, little is known about cross-sensory correspondences in preschool-aged children (2-4 years). We present a study with 26 preschoolers examining smell-touch-emotion correspondences through playful tasks. We found significant correspondences both between sensory modalities and between sensory modalities and affective judgements. Further analysis revealed association strategies underpinning these mappings. We contribute empirical insights into cross-sensory correspondences in early childhood, design guidelines that align with how preschoolers relate sensory input, and a replicable method for probing cross-sensory cognition in this age group.
### Title:
          Overlapping Schwarz Preconditioners for Pose-Graph SLAM in Robotics
 - **Authors:** Stephan Köhler, Oliver Rheinbach, Yue Xiang Tee, Sebastian Zug
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We investigate the application of the additive overlapping Schwarz domain decomposition method as a preconditioner for the large sparse linear systems arising in graph-based nonlinear least-squares problems, specifically the pose-graph optimization back-end in Simultaneous Localization and Mapping (SLAM) in robotics. A brief introduction to both SLAM and domain decomposition preconditioners is given, followed by a description of the nonlinear least-squares formulation, its linearization, and the resulting matrix structure, making the paper accessible to readers without prior knowledge of either field. Numerical experiments for a simple model problem demonstrate the numerical scalability of the preconditioned conjugate gradient method to solve the linear systems resulting from Gauss--Newton linearization: Using the additive overlapping Schwarz preconditioner, the number of conjugate gradient iterations remains bounded independently of the problem size. We also show that a simplified SLAM problem can be interpreted as a finite element problem using linear elastic bars, highlighting the structural analogy to PDE discretizations and motivating the use of PDE-based preconditioners such as scalable domain decomposition preconditioners.
### Title:
          The Spanning Ratio of the Directed $Θ_6$-Graph is 5
 - **Authors:** Prosenjit Bose, Jean-Lou De Carufel, Darryl Hill, John Stuart
 - **Subjects:** Subjects:
Computational Geometry (cs.CG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Given a finite set $P\subset\mathbb{R}^2$, the directed Theta-6 graph, denoted $\vec{\Theta}_6(P)$, is a well-studied geometric graph due to its close relationship with the Delaunay triangulation. The $\vec{\Theta}_6(P)$-graph is defined as follows: the plane around each point $u\in P$ is partitioned into $6$ equiangular cones with apex $u$, and in each cone, $u$ is joined to the point whose projection on the bisector of the cone is closest. Equivalently, the $\vec{\Theta}_6(P)$-graph contains an edge from $u$ to $v$ exactly when the interior of $\nabla_u^v$ is disjoint from $P$, where $\nabla_u^v$ is the unique equilateral triangle containing $u$ on a corner, $v$ on the opposite side, and whose sides are parallel to the cone boundaries. It was previously shown that the spanning ratio of the $\vec{\Theta}_6(P)$-graph is between $4$ and $7$ in the worst case (Akitaya, Biniaz, and Bose \emph{Comput. Geom.}, 105-106:101881, 2022). We close this gap by showing a tight spanning ratio of 5. This is the first tight bound proven for the spanning ratio of any $\vec{\Theta}_k(P)$-graph. Our lower bound models a long path by mapping it to a converging series. Our upper bound proof uses techniques novel to the area of spanners. We use linear programming to prove that among several candidate paths, there exists a path satisfying our bound.
### Title:
          Deep Tabular Research via Continual Experience-Driven Execution
 - **Authors:** Junnan Dong, Chuang Zhou, Zheng Yuan, Yifei Yu, Siyu An, Di Yin, Xing Sun, Feiyue Huang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models often struggle with complex long-horizon analytical tasks over unstructured tables, which typically feature hierarchical and bidirectional headers and non-canonical layouts. We formalize this challenge as Deep Tabular Research (DTR), requiring multi-step reasoning over interdependent table regions. To address DTR, we propose a novel agentic framework that treats tabular reasoning as a closed-loop decision-making process. We carefully design a coupled query and table comprehension for path decision making and operational execution. Specifically, (i) DTR first constructs a hierarchical meta graph to capture bidirectional semantics, mapping natural language queries into an operation-level search space; (ii) To navigate this space, we introduce an expectation-aware selection policy that prioritizes high-utility execution paths; (iii) Crucially, historical execution outcomes are synthesized into a siamese structured memory, i.e., parameterized updates and abstracted texts, enabling continual refinement. Extensive experiments on challenging unstructured tabular benchmarks verify the effectiveness and highlight the necessity of separating strategic planning from low-level execution for long-horizon tabular reasoning.
### Title:
          DataFactory: Collaborative Multi-Agent Framework for Advanced Table Question Answering
 - **Authors:** Tong Wang, Chi Jin, Yongkang Chen, Huan Deng, Xiaohui Kuang, Gang Zhao
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Databases (cs.DB); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Table Question Answering (TableQA) enables natural language interaction with structured tabular data. However, existing large language model (LLM) approaches face critical limitations: context length constraints that restrict data handling capabilities, hallucination issues that compromise answer reliability, and single-agent architectures that struggle with complex reasoning scenarios involving semantic relationships and multi-hop logic. This paper introduces DataFactory, a multi-agent framework that addresses these limitations through specialized team coordination and automated knowledge transformation. The framework comprises a Data Leader employing the ReAct paradigm for reasoning orchestration, together with dedicated Database and Knowledge Graph teams, enabling the systematic decomposition of complex queries into structured and relational reasoning tasks. We formalize automated data-to-knowledge graph transformation via the mapping function T:D x S x R -> G, and implement natural language-based consultation that - unlike fixed workflow multi-agent systems - enables flexible inter-agent deliberation and adaptive planning to improve coordination robustness. We also apply context engineering strategies that integrate historical patterns and domain knowledge to reduce hallucinations and improve query accuracy. Across TabFact, WikiTableQuestions, and FeTaQA, using eight LLMs from five providers, results show consistent gains. Our approach improves accuracy by 20.2% (TabFact) and 23.9% (WikiTQ) over baselines, with significant effects (Cohen's d > 1). Team coordination also outperforms single-team variants (+5.5% TabFact, +14.4% WikiTQ, +17.1% FeTaQA ROUGE-2). The framework offers design guidelines for multi-agent collaboration and a practical platform for enterprise data analysis through integrated structured querying and graph-based knowledge representation.
### Title:
          Distributed Convolutional Neural Networks for Object Recognition
 - **Authors:** Liang Sun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper proposes a novel loss function for training a distributed convolutional neural network (DisCNN) to recognize only a specific positive class. By mapping positive samples to a compact set in high-dimensional space and negative samples to Origin, the DisCNN extracts only the features of the positive class. An experiment is given to prove this. Thus, the features of the positive class are disentangled from those of the negative classes. The model has a lightweight architecture because only a few positive-class features need to be extracted. The model demonstrates excellent generalization on the test data and remains effective even for unseen classes. Finally, using DisCNN, object detection of positive samples embedded in a large and complex background is straightforward.
### Title:
          Flash-KMeans: Fast and Memory-Efficient Exact K-Means
 - **Authors:** Shuo Yang, Haocheng Xi, Yilong Zhao, Muyang Li, Xiaoze Fan, Jintao Zhang, Han Cai, Yujun Lin, Xiuyu Li, Kurt Keutzer, Song Han, Chenfeng Xu, Ion Stoica
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 $k$-means has historically been positioned primarily as an offline processing primitive, typically used for dataset organization or embedding preprocessing rather than as a first-class component in online systems. In this work, we revisit this classical algorithm under the lens of modern AI system design and enable $k$-means as an online primitive. We point out that existing GPU implementations of $k$-means remain fundamentally bottlenecked by low-level system constraints rather than theoretical algorithmic complexity. Specifically, the assignment stage suffers from a severe IO bottleneck due to the massive explicit materialization of the $N \times K$ distance matrix in High Bandwidth Memory (HBM). Simultaneously, the centroid update stage is heavily penalized by hardware-level atomic write contention caused by irregular, scatter-style token aggregations. To bridge this performance gap, we propose flash-kmeans, an IO-aware and contention-free $k$-means implementation for modern GPU workloads. Flash-kmeans introduces two core kernel-level innovations: (1) FlashAssign, which fuses distance computation with an online argmin to completely bypass intermediate memory materialization; (2) sort-inverse update, which explicitly constructs an inverse mapping to transform high-contention atomic scatters into high-bandwidth, segment-level localized reductions. Furthermore, we integrate algorithm-system co-designs, including chunked-stream overlap and cache-aware compile heuristics, to ensure practical deployability. Extensive evaluations on NVIDIA H200 GPUs demonstrate that flash-kmeans achieves up to 17.9$\times$ end-to-end speedup over best baselines, while outperforming industry-standard libraries like cuML and FAISS by 33$\times$ and over 200$\times$, respectively.
### Title:
          CogBlender: Towards Continuous Cognitive Intervention in Text-to-Image Generation
 - **Authors:** Shengqi Dang, Jiaying Lei, Yi He, Ziqing Qian, Nan Cao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Beyond conveying semantic information, an image can also manifest cognitive attributes that elicit specific cognitive processes from the viewer, such as memory encoding or emotional response. While modern text-to-image models excel at generating semantically coherent content, they remain limited in their ability to control such cognitive properties of images (e.g., valence, memorability), often failing to align with the specific psychological intent. To bridge this gap, we introduce CogBlender, a framework that enables continuous and multi-dimensional intervention of cognitive properties during text-to-image generation. Our approach is built upon a mapping between the Cognitive Space, representing the space of cognitive properties, and the Semantic Manifold, representing the manifold of the visual semantics. We define a set of Cognitive Anchors, serving as the boundary points for the cognitive space. Then we reformulate the velocity field within the flow-matching process by interpolating from the velocity field of different anchors. Consequently, the generative process is driven by the velocity field and dynamically steered by multi-dimensional cognitive scores, enabling precise, fine-grained, and continuous intervention. We validate the effectiveness of CogBlender across four representative cognitive dimensions: valence, arousal, dominance, and image memorability. Extensive experiments demonstrate that our method achieves effective cognitive intervention. Our work provides an effective paradigm for cognition-driven creative design.
### Title:
          Experience Report on the Adaptable Integration of Requirements Engineering Courses into Curricula for Professionals
 - **Authors:** Oleksandr Kosenkov, Konstantin Blaschke, Tony Gorschek, Michael Unterkalmsteiner, Oleksandr Adamov, Davide Fucci
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 There is a growing demand for software engineering education (SEE) for professionals because of the increasing demand, active evolution of the technological landscape, and changes in the skills required by the practice. Integrating requirements engineering (RE) courses into SEE curricula for professionals systematically and effectively is challenging. In particular, curricula for professionals have different demands, are more dynamic, and modular in nature. In this study, we report on our experience in the development of three SEE curricula for professionals and the integration of RE courses into such curricula. We suggest basic principles for such integration and describe the systematic approach focused on course content mapping that we have developed.
### Title:
          Benchmarking Dataset for Presence-Only Passive Reconnaissance in Wireless Smart-Grid Communications
 - **Authors:** Bochra Al Agha, Razane Tajeddine
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Benchmarking presence-only passive reconnaissance in smart-grid communications is challenging because the adversary is receive-only, yet nearby observers can still alter propagation through additional shadowing and multipath that reshapes channel coherence. Public smart-grid cybersecurity datasets largely target active protocol- or measurement-layer attacks and rarely provide propagation-driven observables with tiered topology context, which limits reproducible evaluation under strictly passive threat models. This paper introduces an IEEE-inspired, literature-anchored benchmark dataset generator for passive reconnaissance over a tiered Home Area Network (HAN), Neighborhood Area Network (NAN), and Wide Area Network (WAN) communication graph with heterogeneous wireless and wireline links. Node-level time series are produced through a physically consistent channel-to-metrics mapping where channel state information (CSI) is represented via measurement-realistic amplitude and phase proxies that drive inferred signal-to-noise ratio (SNR), packet error behavior, and delay dynamics. Passive attacks are modeled only as windowed excess attenuation and coherence degradation with increased channel innovation, so reliability and latency deviations emerge through the same causal mapping without labels or feature shortcuts. The release provides split-independent realizations with burn-in removal, strictly causal temporal descriptors, adjacency-weighted neighbor aggregates and deviation features, and federated-ready per-node train, validation, and test partitions with train-only normalization metadata. Baseline federated experiments highlight technology-dependent detectability and enable standardized benchmarking of graph-temporal and federated detectors for passive reconnaissance.
### Title:
          VarSplat: Uncertainty-aware 3D Gaussian Splatting for Robust RGB-D SLAM
 - **Authors:** Anh Thuan Tran, Jana Kosecka
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Simultaneous Localization and Mapping (SLAM) with 3D Gaussian Splatting (3DGS) enables fast, differentiable rendering and high-fidelity reconstruction across diverse real-world scenes. However, existing 3DGS-SLAM approaches handle measurement reliability implicitly, making pose estimation and global alignment susceptible to drift in low-texture regions, transparent surfaces, or areas with complex reflectance properties. To this end, we introduce VarSplat, an uncertainty-aware 3DGS-SLAM system that explicitly learns per-splat appearance variance. By using the law of total variance with alpha compositing, we then render differentiable per-pixel uncertainty map via efficient, single-pass rasterization. This map guides tracking, submap registration, and loop detection toward focusing on reliable regions and contributes to more stable optimization. Experimental results on Replica (synthetic) and TUM-RGBD, ScanNet, and ScanNet++ (real-world) show that VarSplat improves robustness and achieves competitive or superior tracking, mapping, and novel view synthesis rendering compared to existing studies for dense RGB-D SLAM.
### Title:
          Ensuring Data Freshness in Multi-Rate Task Chains Scheduling
 - **Authors:** José Luis Conradi Hoffmann, Antônio Augusto Fröhlich
 - **Subjects:** Subjects:
Operating Systems (cs.OS); Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In safety-critical autonomous systems, data freshness presents a fundamental design challenge. While the Logical Execution Time (LET) paradigm ensures compositional determinism, it often does so at the cost of injected latency, degrading the phase margin of high-frequency control loops. Furthermore, mapping heterogeneous, multi-rate sensor fusion requirements onto rigid task-centric schedules typically implies in resource-inefficient oversampling. This paper proposes a Task-based scheduling framework extended with data freshness constraints. Unlike traditional models, scheduling decisions are driven by the lifespan of data. We introduce task offset based on the data freshness constraint to order data production in a Just-in-Time (JIT) fashion: the completion of the production of data with strictest data freshness constraint is delayed to the instant its consumers will be ready to use it. This allows for flexible task release offsets. We introduce a formal methodology to decompose Data Dependency Graphs into Dominant Paths by tracing the strictest data freshness constraints backward from the actuators. Based on this decomposition, we propose a Consensus Offset Search algorithm that synchronizes shared producers and private predecessors. This approach enforces end-to-end data freshness without the artificial latency of LET buffering. We formally prove that this offset-based alignment preserves the 100\% schedulability capacity of Global EDF, ensuring data freshness while eliminating the computational overhead of redundant sampling.
### Title:
          Upper Generalization Bounds for Neural Oscillators
 - **Authors:** Zifeng Huang, Konstantin M. Zuev, Yong Xia, Michael Beer
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Dynamical Systems (math.DS); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural oscillators that originate from the second-order ordinary differential equations (ODEs) have shown competitive performance in learning mappings between dynamic loads and responses of complex nonlinear structural systems. Despite this empirical success, theoretically quantifying the generalization capacities of their neural network architectures remains undeveloped. In this study, the neural oscillator consisting of a second-order ODE followed by a multilayer perceptron (MLP) is considered. Its upper probably approximately correct (PAC) generalization bound for approximating causal and uniformly continuous operators between continuous temporal function spaces and that for approximating the uniformly asymptotically incrementally stable second-order dynamical systems are derived by leveraging the Rademacher complexity framework. The theoretical results show that the estimation errors grow polynomially with respect to both the MLP size and the time length, thereby avoiding the curse of parametric complexity. Furthermore, the derived error bounds demonstrate that constraining the Lipschitz constants of the MLPs via loss function regularization can improve the generalization ability of the neural oscillator. A numerical study considering a Bouc-Wen nonlinear system under stochastic seismic excitation validates the theoretically predicted power laws of the estimation errors with respect to the sample size and time length, and confirms the effectiveness of constraining MLPs' matrix and vector norms in enhancing the performance of the neural oscillator under limited training data.
### Title:
          The Richest Paradigm You're Not Using: Commercial Videogames at the Intersection of Human-Computer Interaction and Cognitive Science
 - **Authors:** Jaap Munneke, Jennifer E. Corbett
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Synthesizing from Corbett and Munneke (2025), who demonstrated that questions originating in human-computer interaction (HCI) and game design can be answered through the theoretical toolkit of cognitive science, this perspective argues that commercial videogames represent a largely underutilized research environment at the intersection of these two fields. Cognitive science has long relied on carefully controlled laboratory paradigms to study perception, attention, and executive functioning, raising persistent questions about ecological validity. HCI, by contrast, has spent decades developing methods for studying behavior in rich, complex, interactive environments, but has been less concerned with what that behavior reveals about underlying cognitive mechanisms. Commercial videogames sit precisely at this intersection. They are cognitively demanding by design, motivating by nature, and consistent enough across players to support systematic behavioral comparison. The affordance structure of a game does the work that experimental manipulations typically require of the researcher, instantiating cognitive demands that are genuine, sustained, and meaningful to the player. We argue that perception, attention, and executive functioning can be meaningfully studied within commercial games using a minimal observational toolkit of screen recording, eye tracking, and behavioral timing. We propose an affordance-cognition mapping framework as a systematic basis for game selection and research design and offer practical methodological recommendations for researchers wishing to work in this space.
### Title:
          World2Mind: Cognition Toolkit for Allocentric Spatial Reasoning in Foundation Models
 - **Authors:** Shouwei Ruan, Bin Wang, Zhenyu Wu, Qihui Zhu, Yuxiang Zhang, Hang Su, Yubin Wang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Achieving robust spatial reasoning remains a fundamental challenge for current Multimodal Foundation Models (MFMs). Existing methods either overfit statistical shortcuts via 3D grounding data or remain confined to 2D visual perception, limiting both spatial reasoning accuracy and generalization in unseen scenarios. Inspired by the spatial cognitive mapping mechanisms of biological intelligence, we propose World2Mind, a training-free spatial intelligence toolkit. At its core, World2Mind leverages 3D reconstruction and instance segmentation models to construct structured spatial cognitive maps, empowering MFMs to proactively acquire targeted spatial knowledge regarding interested landmarks and routes of interest. To provide robust geometric-topological priors, World2Mind synthesizes an Allocentric-Spatial Tree (AST) that uses elliptical parameters to model the top-down layout of landmarks accurately. To mitigate the inherent inaccuracies of 3D reconstruction, we introduce a three-stage reasoning chain comprising tool invocation assessment, modality-decoupled cue collection, and geometry-semantics interwoven reasoning. Extensive experiments demonstrate that World2Mind boosts the performance of frontier models, such as GPT-5.2, by 5%~18%. Astonishingly, relying solely on the AST-structured text, purely text-only foundation models can perform complex 3D spatial reasoning, achieving performance approaching that of advanced multimodal models.
### Title:
          One-Eval: An Agentic System for Automated and Traceable LLM Evaluation
 - **Authors:** Chengyu Shen, Yanheng Hou, Minghui Pan, Runming He, Zhen Hao Wong, Meiyi Qiang, Zhou Liu, Hao Liang, Peichao Lai, Zeang Sheng, Wentao Zhang
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable evaluation is essential for developing and deploying large language models, yet in practice it often requires substantial manual effort: practitioners must identify appropriate benchmarks, reproduce heterogeneous evaluation codebases, configure dataset schema mappings, and interpret aggregated metrics. To address these challenges, we present One-Eval, an agentic evaluation system that converts natural-language evaluation requests into executable, traceable, and customizable evaluation workflows. One-Eval integrates (i) NL2Bench for intent structuring and personalized benchmark planning, (ii) BenchResolve for benchmark resolution, automatic dataset acquisition, and schema normalization to ensure executability, and (iii) Metrics \& Reporting for task-aware metric selection and decision-oriented reporting beyond scalar scores. The system further incorporates human-in-the-loop checkpoints for review, editing, and rollback, while preserving sample evidence trails for debugging and auditability. Experiments show that One-Eval can execute end-to-end evaluations from diverse natural-language requests with minimal user effort, supporting more efficient and reproducible evaluation in industrial settings. Our framework is publicly available at this https URL.
### Title:
          The Bureaucracy of Speed: Structural Equivalence Between Memory Consistency Models and Multi-Agent Authorization Revocation
 - **Authors:** Vladyslav Parakhin
 - **Subjects:** Subjects:
Multiagent Systems (cs.MA); Cryptography and Security (cs.CR); Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The temporal assumptions underpinning conventional Identity and Access Management collapse under agentic execution regimes. A sixty-second revocation window permits on the order of $6 \times 10^3$ unauthorized API calls at 100 ops/tick; at AWS Lambda scale, the figure approaches $6 \times 10^5$. This is a coherence problem, not merely a latency problem. We define a Capability Coherence System (CCS) and construct a state-mapping $\varphi : \Sigma_{\rm MESI} \to \Sigma_{\rm auth}$ preserving transition structure under bounded-staleness semantics. A safety theorem bounds unauthorized operations for the execution-count Release Consistency-directed Coherence (RCC) strategy at $D_{\rm rcc} \leq n$, independent of agent velocity $v$ -- a qualitative departure from the $O(v \cdot \mathrm{TTL})$ scaling of time-bounded strategies. Tick-based discrete event simulation across three business-contextualised scenarios (four strategies, ten deterministic seeds each) confirms: RCC achieves a $120\times$ reduction versus TTL-based lease in the high-velocity scenario (50 vs. 6,000 unauthorized operations), and $184\times$ under anomaly-triggered revocation. Zero bound violations across all 120 runs confirm the per-capability safety guarantee. Simulation code: this https URL
### Title:
          Adaptive Clinical-Aware Latent Diffusion for Multimodal Brain Image Generation and Missing Modality Imputation
 - **Authors:** Rong Zhou, Houliang Zhou, Yao Su, Brian Y. Chen, Yu Zhang, Lifang He, Alzheimer's Disease Neuroimaging Initiative
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal neuroimaging provides complementary insights for Alzheimer's disease diagnosis, yet clinical datasets frequently suffer from missing modalities. We propose ACADiff, a framework that synthesizes missing brain imaging modalities through adaptive clinical-aware diffusion. ACADiff learns mappings between incomplete multimodal observations and target modalities by progressively denoising latent representations while attending to available imaging data and clinical metadata. The framework employs adaptive fusion that dynamically reconfigures based on input availability, coupled with semantic clinical guidance via GPT-4o-encoded prompts. Three specialized generators enable bidirectional synthesis among sMRI, FDG-PET, and AV45-PET. Evaluated on ADNI subjects, ACADiff achieves superior generation quality and maintains robust diagnostic performance even under extreme 80\% missing scenarios, outperforming all existing baselines. To promote reproducibility, code is available at this https URL
## Keyword: localization
### Title:
          NaviNote: Enabling In-situ Spatial Annotation Authoring to Support Exploration and Navigation for Blind and Low Vision People
 - **Authors:** Ruijia Chen, Yuheng Wu, Charlie Houseago, Filipe Gaspar, Filippo Aleotti, Dorian Gálvez-López, Oliver Johnston, Diego Mazala, Guillermo Garcia-Hernando, Maryam Bandukda, Gabriel Brostow, Jessica Van Brummelen
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 GPS and smartphones enable users to place location-based annotations, capturing rich environmental context. Previous research demonstrates that blind and low vision (BLV) people can use annotations to explore unfamiliar areas. However, current commercial systems allowing BLV users to create annotations have never been evaluated, and current GPS-based systems can deviate several meters. Motivated by high-accuracy visual positioning technology, we first conducted a formative study with 24 BLV participants to envision a more accurate and inclusive annotation system. Surprisingly, many participants viewed the high-accuracy technology not just as an annotation system but also as a tool for precise last-few-meters navigation. Guided by participant feedback, we developed NaviNote, which combines vision-based high-precision localization with an agentic architecture to enable voice-based annotation authoring and navigation. Evaluating NaviNote with 18 BLV participants showed that it significantly improved navigation performance and supported users in understanding and annotating their surroundings. Based on these findings, we discuss design considerations for future accessible annotation authoring systems.
### Title:
          A Lightweight Multi-Cancer Tumor Localization Framework for Deployable Digital Pathology
 - **Authors:** Brian Isett, Rebekah Dadey, Aofei Li, Ryan C. Augustin, Kate Smith, Aatur D. Singhi, Qiangqiang Gu, Riyue Bao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate localization of tumor regions from hematoxylin and eosin-stained whole-slide images is fundamental for translational research including spatial analysis, molecular profiling, and tissue architecture investigation. However, deep learning-based tumor detection trained within specific cancers may exhibit reduced robustness when applied across different tumor types. We investigated whether balanced training across cancers at modest scale can achieve high performance and generalize to unseen tumor types. A multi-cancer tumor localization model (MuCTaL) was trained on 79,984 non-overlapping tiles from four cancers (melanoma, hepatocellular carcinoma, colorectal cancer, and non-small cell lung cancer) using transfer learning with DenseNet169. The model achieved a tile-level ROC-AUC of 0.97 in validation data from the four training cancers, and 0.71 on an independent pancreatic ductal adenocarcinoma cohort. A scalable inference workflow was built to generate spatial tumor probability heatmaps compatible with existing digital pathology tools. Code and models are publicly available at this https URL.
### Title:
          Towards Visual Query Segmentation in the Wild
 - **Authors:** Bing Fan, Minghao Li, Hanzhi Zhang, Shaohua Dong, Naga Prudhvi Mareedu, Weishi Shi, Yunhe Feng, Yan Huang, Heng Fan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we introduce visual query segmentation (VQS), a new paradigm of visual query localization (VQL) that aims to segment all pixel-level occurrences of an object of interest in an untrimmed video, given an external visual query. Compared to existing VQL locating only the last appearance of a target using bounding boxes, VQS enables more comprehensive (i.e., all object occurrences) and precise (i.e., pixel-level masks) localization, making it more practical for real-world scenarios. To foster research on this task, we present VQS-4K, a large-scale benchmark dedicated to VQS. Specifically, VQS-4K contains 4,111 videos with more than 1.3 million frames and covers a diverse set of 222 object categories. Each video is paired with a visual query defined by a frame outside the search video and its target mask, and annotated with spatial-temporal masklets corresponding to the queried target. To ensure high quality, all videos in VQS-4K are manually labeled with meticulous inspection and iterative refinement. To the best of our knowledge, VQS-4K is the first benchmark specifically designed for VQS. Furthermore, to stimulate future research, we present a simple yet effective method, named VQ-SAM, which extends SAM 2 by leveraging target-specific and background distractor cues from the video to progressively evolve the memory through a novel multi-stage framework with an adaptive memory generation (AMG) module for VQS, significantly improving the performance. In our extensive experiments on VQS-4K, VQ-SAM achieves promising results and surpasses all existing approaches, demonstrating its effectiveness. With the proposed VQS-4K and VQ-SAM, we expect to go beyond the current VQL paradigm and inspire more future research and practical applications on VQS. Our benchmark, code, and results will be made publicly available.
### Title:
          Fly, Track, Land: Infrastructure-less Magnetic Localization for Heterogeneous UAV-UGV Teaming
 - **Authors:** Valerio Brunacci, Davide Plozza, Alessio De Angelis, Michele Magno, Tommaso Polonelli
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a complete infrastructure-less magneto-inductive (MI) localization system enabling a lightweight UAV to autonomously hover, track, and land with centimeter precision on a mobile quadruped robot acting as a dynamic docking pad. This work advances the vision of heterogeneous robot collaboration, where ultra-lightweight flying robots serve as mobile perception agents for ground-based Unmanned Ground Vehicles (UGVs). By extending the sensing horizon and providing complementary viewpoints, the UAVs enhance exploration efficiency and improve the quality of data collection in large-scale, unknown environments. The proposed system aims to complements traditional localization modalities with a compact, embedded, and infrastructure-less magnetic sensing approach, providing accurate short-range relative positioning to bridge the gap between coarse navigation and precise UAV docking. A single lightweight receive coil and a fully embedded estimation pipeline on the UAV deliver 20 Hz relative pose estimates in the UGV's frame, achieving a 3D position root-mean-square error (RMSE) of 5 cm. The system uses real-time estimation and a warm-started solver to estimate the 3D position, which is then fused with inertial and optical-flow measurements in the onboard extended Kalman filter. Real-world experiments validate the effectiveness of the framework, demonstrating significant improvements in UAV--UGV teaming in infrastructure-less scenarios compared to state-of-the-art methods, requiring no external anchors or global positioning. In dynamic scenarios, the UAV tracks and docks with a moving UGV while maintaining a 7.2 cm RMSE and achieving successful autonomous landings.
### Title:
          Overlapping Schwarz Preconditioners for Pose-Graph SLAM in Robotics
 - **Authors:** Stephan Köhler, Oliver Rheinbach, Yue Xiang Tee, Sebastian Zug
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We investigate the application of the additive overlapping Schwarz domain decomposition method as a preconditioner for the large sparse linear systems arising in graph-based nonlinear least-squares problems, specifically the pose-graph optimization back-end in Simultaneous Localization and Mapping (SLAM) in robotics. A brief introduction to both SLAM and domain decomposition preconditioners is given, followed by a description of the nonlinear least-squares formulation, its linearization, and the resulting matrix structure, making the paper accessible to readers without prior knowledge of either field. Numerical experiments for a simple model problem demonstrate the numerical scalability of the preconditioned conjugate gradient method to solve the linear systems resulting from Gauss--Newton linearization: Using the additive overlapping Schwarz preconditioner, the number of conjugate gradient iterations remains bounded independently of the problem size. We also show that a simplified SLAM problem can be interpreted as a finite element problem using linear elastic bars, highlighting the structural analogy to PDE discretizations and motivating the use of PDE-based preconditioners such as scalable domain decomposition preconditioners.
### Title:
          From Ideal to Real: Stable Video Object Removal under Imperfect Conditions
 - **Authors:** Jiagao Hu, Yuxuan Chen, Fuhao Li, Zepeng Wang, Fei Wang, Daiguo Zhou, Jian Luan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Removing objects from videos remains difficult in the presence of real-world imperfections such as shadows, abrupt motion, and defective masks. Existing diffusion-based video inpainting models often struggle to maintain temporal stability and visual consistency under these challenges. We propose Stable Video Object Removal (SVOR), a robust framework that achieves shadow-free, flicker-free, and mask-defect-tolerant removal through three key designs: (1) Mask Union for Stable Erasure (MUSE), a windowed union strategy applied during temporal mask downsampling to preserve all target regions observed within each window, effectively handling abrupt motion and reducing missed removals; (2) Denoising-Aware Segmentation (DA-Seg), a lightweight segmentation head on a decoupled side branch equipped with Denoising-Aware AdaLN and trained with mask degradation to provide an internal diffusion-aware localization prior without affecting content generation; and (3) Curriculum Two-Stage Training: where Stage I performs self-supervised pretraining on unpaired real-background videos with online random masks to learn realistic background and temporal priors, and Stage II refines on synthetic pairs using mask degradation and side-effect-weighted losses, jointly removing objects and their associated shadows/reflections while improving cross-domain robustness. Extensive experiments show that SVOR attains new state-of-the-art results across multiple datasets and degraded-mask benchmarks, advancing video object removal from ideal settings toward real-world applications.
### Title:
          SinGeo: Unlock Single Model's Potential for Robust Cross-View Geo-Localization
 - **Authors:** Yang Chen, Xieyuanli Chen, Junxiang Li, Jie Tang, Tao Wu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust cross-view geo-localization (CVGL) remains challenging despite the surge in recent progress. Existing methods still rely on field-of-view (FoV)-specific training paradigms, where models are optimized under a fixed FoV but collapse when tested on unseen FoVs and unknown orientations. This limitation necessitates deploying multiple models to cover diverse variations. Although studies have explored dynamic FoV training by simply randomizing FoVs, they failed to achieve robustness across diverse conditions -- implicitly assuming all FoVs are equally difficult. To address this gap, we present SinGeo, a simple yet powerful framework that enables a single model to realize robust cross-view geo-localization without additional modules or explicit transformations. SinGeo employs a dual discriminative learning architecture that enhances intra-view discriminability within both ground and satellite branches, and is the first to introduce a curriculum learning strategy to achieve robust CVGL. Extensive evaluations on four benchmark datasets reveal that SinGeo sets state-of-the-art (SOTA) results under diverse conditions, and notably outperforms methods specifically trained for extreme FoVs. Beyond superior performance, SinGeo also exhibits cross-architecture transferability. Furthermore, we propose a consistency evaluation method to quantitatively assess model stability under varying views, providing an explainable perspective for understanding and advancing robustness in future CVGL research. Codes will be available upon acceptance.
### Title:
          SurgFed: Language-guided Multi-Task Federated Learning for Surgical Video Understanding
 - **Authors:** Zheng Fang, Ziwei Niu, Ziyue Wang, Zhu Zhuo, Haofeng Liu, Shuyang Qian, Jun Xia, Yueming Jin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Surgical scene Multi-Task Federated Learning (MTFL) is essential for robot-assisted minimally invasive surgery (RAS) but remains underexplored in surgical video understanding due to two key challenges: (1) Tissue Diversity: Local models struggle to adapt to site-specific tissue features, limiting their effectiveness in heterogeneous clinical environments and leading to poor local predictions. (2) Task Diversity: Server-side aggregation, relying solely on gradient-based clustering, often produces suboptimal or incorrect parameter updates due to inter-site task heterogeneity, resulting in inaccurate localization. In light of these two issues, we propose SurgFed, a multi-task federated learning framework, enabling federated learning for surgical scene segmentation and depth estimation across diverse surgical types. SurgFed is powered by two appealing designs, i.e., Language-guided Channel Selection (LCS) and Language-guided Hyper Aggregation (LHA), to address the challenge of fully exploration on corss-site and cross-task. Technically, the LCS is first designed a lightweight personalized channel selection network that enhances site-specific adaptation using pre-defined text inputs, which optimally the local model learn the specific embeddings. We further introduce the LHA that employs a layer-wise cross-attention mechanism with pre-defined text inputs to model task interactions across sites and guide a hypernetwork for personalized parameter updates. Extensive empirical evidence shows that SurgFed yields improvements over the state-of-the-art methods in five public datasets across four surgical types. The code is available at this https URL.
### Title:
          Decoder-Free Distillation for Quantized Image Restoration
 - **Authors:** S. M. A. Sharif, Abdur Rehman, Seongwan Kim, Jaeho Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Quantization-Aware Training (QAT), combined with Knowledge Distillation (KD), holds immense promise for compressing models for edge deployment. However, joint optimization for precision-sensitive image restoration (IR) to recover visual quality from degraded images remains largely underexplored. Directly adapting QAT-KD to low-level vision reveals three critical bottlenecks: teacher-student capacity mismatch, spatial error amplification during decoder distillation, and an optimization "tug-of-war" between reconstruction and distillation losses caused by quantization noise. To tackle these, we introduce Quantization-aware Distilled Restoration (QDR), a framework for edge-deployed IR. QDR eliminates capacity mismatch via FP32 self-distillation and prevents error amplification through Decoder-Free Distillation (DFD), which corrects quantization errors strictly at the network bottleneck. To stabilize the optimization tug-of-war, we propose a Learnable Magnitude Reweighting (LMR) that dynamically balances competing gradients. Finally, we design an Edge-Friendly Model (EFM) featuring a lightweight Learnable Degradation Gating (LDG) to dynamically modulate spatial degradation localization. Extensive experiments across four IR tasks demonstrate that our Int8 model recovers 96.5% of FP32 performance, achieves 442 frames per second (FPS) on an NVIDIA Jetson Orin, and boosts downstream object detection by 16.3 mAP
### Title:
          VarSplat: Uncertainty-aware 3D Gaussian Splatting for Robust RGB-D SLAM
 - **Authors:** Anh Thuan Tran, Jana Kosecka
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Simultaneous Localization and Mapping (SLAM) with 3D Gaussian Splatting (3DGS) enables fast, differentiable rendering and high-fidelity reconstruction across diverse real-world scenes. However, existing 3DGS-SLAM approaches handle measurement reliability implicitly, making pose estimation and global alignment susceptible to drift in low-texture regions, transparent surfaces, or areas with complex reflectance properties. To this end, we introduce VarSplat, an uncertainty-aware 3DGS-SLAM system that explicitly learns per-splat appearance variance. By using the law of total variance with alpha compositing, we then render differentiable per-pixel uncertainty map via efficient, single-pass rasterization. This map guides tracking, submap registration, and loop detection toward focusing on reliable regions and contributes to more stable optimization. Experimental results on Replica (synthetic) and TUM-RGBD, ScanNet, and ScanNet++ (real-world) show that VarSplat improves robustness and achieves competitive or superior tracking, mapping, and novel view synthesis rendering compared to existing studies for dense RGB-D SLAM.
### Title:
          RA-SSU: Towards Fine-Grained Audio-Visual Learning with Region-Aware Sound Source Understanding
 - **Authors:** Muyi Sun, Yixuan Wang, Hong Wang, Chen Su, Man Zhang, Xingqun Qi, Qi Li, Zhenan Sun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Audio-Visual Learning (AVL) is one fundamental task of multi-modality learning and embodied intelligence, displaying the vital role in scene understanding and interaction. However, previous researchers mostly focus on exploring downstream tasks from a coarse-grained perspective (e.g., audio-visual correspondence, sound source localization, and audio-visual event localization). Considering providing more specific scene perception details, we newly define a fine-grained Audio-Visual Learning task, termed Region-Aware Sound Source Understanding (RA-SSU), which aims to achieve region-aware, frame-level, and high-quality sound source understanding. To support this goal, we innovatively construct two corresponding datasets, i.e. fine-grained Music (f-Music) and fine-grained Lifescene (f-Lifescene), each containing annotated sound source masks and frame-by-frame textual descriptions. The f-Music dataset includes 3,976 samples across 22 scene types related to specific application scenarios, focusing on music scenes with complex instrument mixing. The f-Lifescene dataset contains 6,156 samples across 61 types representing diverse sounding objects in life scenarios. Moreover, we propose SSUFormer, a Sound-Source Understanding TransFormer benchmark that facilitates both the sound source segmentation and sound region description with a multi-modal input and multi-modal output architecture. Specifically, we design two modules for this framework, Mask Collaboration Module (MCM) and Mixture of Hierarchical-prompted Experts (MoHE), to respectively enhance the accuracy and enrich the elaboration of the sound source description. Extensive experiments are conducted on our two datasets to verify the feasibility of the task, evaluate the availability of the datasets, and demonstrate the superiority of the SSUFormer, which achieves SOTA performance on the Sound Source Understanding benchmark.
### Title:
          VLM-Loc: Localization in Point Cloud Maps via Vision-Language Models
 - **Authors:** Shuhao Kang, Youqi Liao, Peijie Wang, Wenlong Liao, Qilin Zhang, Benjamin Busam, Xieyuanli Chen, Yun Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-to-point-cloud (T2P) localization aims to infer precise spatial positions within 3D point cloud maps from natural language descriptions, reflecting how humans perceive and communicate spatial layouts through language. However, existing methods largely rely on shallow text-point cloud correspondence without effective spatial reasoning, limiting their accuracy in complex environments. To address this limitation, we propose VLM-Loc, a framework that leverages the spatial reasoning capability of large vision-language models (VLMs) for T2P localization. Specifically, we transform point clouds into bird's-eye-view (BEV) images and scene graphs that jointly encode geometric and semantic context, providing structured inputs for the VLM to learn cross-modal representations bridging linguistic and spatial semantics. On top of these representations, we introduce a partial node assignment mechanism that explicitly associates textual cues with scene graph nodes, enabling interpretable spatial reasoning for accurate localization. To facilitate systematic evaluation across diverse scenes, we present CityLoc, a benchmark built from multi-source point clouds for fine-grained T2P localization. Experiments on CityLoc demonstrate VLM-Loc achieves superior accuracy and robustness compared to state-of-the-art methods. Our code, model, and dataset are available at \href{this https URL}{repository}.
### Title:
          SCENEBench: An Audio Understanding Benchmark Grounded in Assistive and Industrial Use Cases
 - **Authors:** Laya Iyer, Angelina Wang, Sanmi Koyejo
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Advances in large language models (LLMs) have enabled significant capabilities in audio processing, resulting in state-of-the-art models now known as Large Audio Language Models (LALMs). However, minimal work has been done to measure audio understanding beyond automatic speech recognition (ASR). This paper closes that gap by proposing a benchmark suite, SCENEBench (Spatial, Cross-lingual, Environmental, Non-speech Evaluation), that targets a broad form of audio comprehension across four real-world categories: background sound understanding, noise localization, cross-linguistic speech understanding, and vocal characterizer recognition. These four categories are selected based on understudied needs from accessibility technology and industrial noise monitoring. In addition to performance, we also measure model latency. The purpose of this benchmark suite is to assess audio beyond just what words are said - rather, how they are said and the non-speech components of the audio. Because our audio samples are synthetically constructed (e.g., by overlaying two natural audio samples), we further validate our benchmark against 20 natural audio items per task, sub-sampled from existing datasets to match our task criteria, to assess ecological validity. We assess five state-of-the-art LALMs and find critical gaps: performance varies across tasks, with some tasks performing below random chance and others achieving high accuracy. These results provide direction for targeted improvements in model capabilities.
### Title:
          Robust Cooperative Localization in Featureless Environments: A Comparative Study of DCL, StCL, CCL, CI, and Standard-CL
 - **Authors:** Nivand Khosravi, Meysam Basiri, Rodrigo Ventura
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cooperative localization (CL) enables accurate position estimation in multi-robot systems operating in GPS-denied environments. This paper presents a comparative study of five CL approaches: Centralized Cooperative Localization (CCL), Decentralized Cooperative Localization (DCL), Sequential Cooperative Localization (StCL), Covariance Intersection (CI), and Standard Cooperative Localization (Standard-CL). All methods are implemented in ROS and evaluated through Monte Carlo simulations under two conditions: weak data association and robust detection. Our analysis reveals fundamental trade-offs among the methods. StCL and Standard-CL achieve the lowest position errors but exhibit severe filter inconsistency, making them unsuitable for safety-critical applications. DCL demonstrates remarkable stability under challenging conditions due to its measurement stride mechanism, which provides implicit regularization against outliers. CI emerges as the most balanced approach, achieving near-optimal consistency while maintaining competitive accuracy. CCL provides theoretically optimal estimation but shows sensitivity to measurement outliers. These findings offer practical guidance for selecting CL algorithms based on application requirements.
### Title:
          Stepping VLMs onto the Court: Benchmarking Spatial Intelligence in Sports
 - **Authors:** Yuchen Yang, Yuqing Shao, Duxiu Huang, Linfeng Dong, Yifei Liu, Suixin Tang, Xiang Zhou, Yuanyuan Gao, Wei Wang, Yue Zhou, Xue Yang, Yanfeng Wang, Xiao Sun, Zhihang Zhong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sports have long attracted broad attention as they push the limits of human physical and cognitive capabilities. Amid growing interest in spatial intelligence for vision-language models (VLMs), sports provide a natural testbed for understanding high-intensity human motion and dynamic object interactions. To this end, we present CourtSI, the first large-scale spatial intelligence dataset tailored to sports scenarios. CourtSI contains over 1M QA pairs, organized under a holistic taxonomy that systematically covers spatial counting, distance measurement, localization, and relational reasoning, across representative net sports including badminton, tennis, and table tennis. Leveraging well-defined court geometry as metric anchors, we develop a semi-automatic data engine to reconstruct sports scenes, enabling scalable curation of CourtSI. In addition, we introduce CourtSI-Bench, a high-quality evaluation benchmark comprising 3,686 QA pairs with rigorous human verification. We evaluate 25 proprietary and open-source VLMs on CourtSI-Bench, revealing a remaining human-AI performance gap and limited generalization from existing spatial intelligence benchmarks. These findings indicate that sports scenarios expose limitations in spatial intelligence capabilities captured by existing benchmarks. Further, fine-tuning Qwen3-VL-8B on CourtSI improves accuracy on CourtSI-Bench by 23.5 percentage points. The adapted model also generalizes effectively to CourtSI-Ext, an evaluation set built on a similar but unseen sport, and demonstrates enhanced spatial-aware commentary generation. Together, these findings demonstrate that CourtSI provides a scalable pathway toward advancing spatial intelligence of VLMs in sports.
### Title:
          Emergency Locator Transmitters in the Era of More Electric Aircraft: A Comprehensive Review of Energy, Integration and Safety Challenges
 - **Authors:** Juana M. Martínez-Heredia, Adrián Portos, Marcel Štěpánek, Francisco Colodro
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The progressive electrification of aircraft systems under the more electric aircraft (MEA) paradigm is reshaping the design and qualification constraints of safety-critical avionics. Emergency locator transmitters (ELTs), which are essential for post-accident localization and search and rescue (SAR) operations, have evolved from legacy 121.5/243 MHz beacons to digitally encoded 406 MHz systems, typically retaining 121.5 MHz as a homing signal in combined units. In parallel, the modernization of the Cospas-Sarsat infrastructure, especially MEOSAR, together with multi-constellation global navigation satellite system (GNSS) integration and second-generation beacon capabilities, is reducing detection latency and enabling richer distress messaging. However, MEA platforms impose stricter constraints on available power, thermal management, wiring density, and electromagnetic compatibility (EMC). As a result, ELT performance increasingly depends not only on the device itself, but also on its installation conditions and on the aircraft's overall electrical environment. This review summarizes the ELT architectures and activation/operational cycles, outlines key technological milestones, and consolidates the main integration challenges for MEA, with emphasis on energy autonomy, battery qualification frameworks, EMC and installation practices, and survivability-driven failure modes (e.g., antenna/feedline damage, mounting, and post-impact shielding). Finally, emerging trends include ELT for distress tracking (DT), energy-based designs, advanced health monitoring, and certification-ready pathways for next-generation SAR services are discussed, highlighting research directions that can deliver demonstrable, certifiable gains in reliability, energy efficiency, and robust integration for future electrified aircraft.
## Keyword: transformer
### Title:
          AnalogToBi: Device-Level Analog Circuit Topology Generation via Bipartite Graph and Grammar Guided Decoding
 - **Authors:** Seungmin Kim, Mingun Kim, Yuna Lee, Yulhwa Kim
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automatic generation of device-level analog circuit topologies remains a fundamental challenge in analog design automation. Recent transformer-based approaches have shown promise, yet they often suffer from limited functional controllability, memorization of training data, and the generation of electrically invalid circuits. We propose AnalogToBi, a device-level analog circuit topology generation framework that addresses these limitations. AnalogToBi enables explicit functional control via a circuit type token and adopts a bipartite graph-based circuit representation that decouples positional ordering from functional semantics, encouraging structural reasoning over sequence memorization. In addition, grammar-guided decoding enforces electrical validity during generation, while apply device renaming-based data augmentation improves generalization by increasing sequence diversity without altering circuit functionality. Experimental results show that AnalogToBi achieves 97.8% validity and 92.1% novelty, resulting in 89.9% valid and novel circuits under conditional generation, without human expert involvement. We further present that generated circuits can be automatically translated into SPICE netlists, and SPICE simulations confirm that AnalogToBi discovers high-quality analog topologies that outperform prior methods. For code and supplementary materials, see this https URL
### Title:
          ChatNeuroSim: An LLM Agent Framework for Automated Compute-in-Memory Accelerator Deployment and Optimization
 - **Authors:** Ming-Yen Lee, Shimeng Yu
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Multiagent Systems (cs.MA); Performance (cs.PF)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Compute-in-Memory (CIM) architectures have been widely studied for deep neural network (DNN) acceleration by reducing data transfer overhead between the memory and computing units. In conventional CIM design flows, system-level CIM simulators (such as NeuroSim) are leveraged for design space exploration (DSE) across different hardware configurations and DNN workloads. However, CIM designers need to invest substantial effort in interpreting simulator manuals and understanding complex parameter dependencies. Moreover, extensive design-simulation iterations are often required to identify optimal CIM configurations under hardware constraints. These challenges severely prolong the DSE cycle and hinder rapid CIM deployment. To address these challenges, this work proposes ChatNeuroSim, a large language model (LLM)-based agent framework for automated CIM accelerator deployment and optimization. ChatNeuroSim automates the entire CIM workflow, including task scheduling, request parsing and adjustment, parameter dependency checking, script generation, and simulation execution. It also integrates the proposed CIM optimizer using design space pruning, enabling rapid identification of optimal configurations for different DNN workloads. ChatNeuroSim is evaluated on extensive request-level testbenches and demonstrates correct simulation and optimization behavior, validating its effectiveness in automatic request parsing and task execution. Furthermore, the proposed design space pruning technique accelerates CIM optimization process compared to no-pruning baseline. In the case study optimizing Swin Transformer Tiny under 22 nm technology, the proposed CIM optimizer achieves a 0.42$\times$-0.79$\times$ average runtime reduction compared to the same optimization algorithm without design space pruning.
### Title:
          Diagnosing FP4 inference: a layer-wise and block-wise sensitivity analysis of NVFP4 and MXFP4
 - **Authors:** Musa Cim, Burak Topcu, Mahmut Taylan Kandemir
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Quantization addresses the high resource demand for large language models (LLMs) by alleviating memory pressure and bandwidth congestion and providing significantly scaled compute power with a tolerable impact on accuracy. Four-bit floating point (FP4), the lowest-precision format that preserves essential numerical properties such as exponent and sign, has begun to be adopted in cutting-edge architectures, including Blackwell and AMD CDNA, to support LLM quantization and reduce deployment costs. Although aggressive quantization can yield efficiency gains, the quantization sensitivity of within-transformer layers and whether these sensitivities generalize across existing FP4 formats and model scales remain underexplored. To elucidate quantization sensitivity, this study conducts a systematic analysis of two FP4 formats, MXFP4 and NVFP4, across three Qwen2.5 model scales (0.5B, 7B, and 14B), using controlled component-wise and block-wise isolation methodologies. We observe that MLP up- and down-projection layers consistently dominate in terms of sensitivity, while gate and attention projections are moderately and substantially less sensitive to FP4 quantization, respectively. We further find that sensitivity does not universally localize to the final blocks, but early blocks can be highly sensitive, particularly under MXFP4. Our results provide a diagnostic characterization of the inference behavior of FP4 across components, depths, and FP4 formats.
### Title:
          EDMFormer: Genre-Specific Self-Supervised Learning for Music Structure Segmentation
 - **Authors:** Sahal Sajeer, Krish Patel, Oscar Chung, Joel Song Bae
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Music structure segmentation is a key task in audio analysis, but existing models perform poorly on Electronic Dance Music (EDM). This problem exists because most approaches rely on lyrical or harmonic similarity, which works well for pop music but not for EDM. EDM structure is instead defined by changes in energy, rhythm, and timbre, with different sections such as buildup, drop, and breakdown. We introduce EDMFormer, a transformer model that combines self-supervised audio embeddings using an EDM-specific dataset and taxonomy. We release this dataset as EDM-98: a group of 98 professionally annotated EDM tracks. EDMFormer improves boundary detection and section labelling compared to existing models, particularly for drops and buildups. The results suggest that combining learned representations with genre-specific data and structural priors is effective for EDM and could be applied to other specialized music genres or broader audio domains.
### Title:
          Are Expressive Encoders Necessary for Discrete Graph Generation?
 - **Authors:** Jay Revolinsky, Harry Shomer, Jiliang Tang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Discrete graph generation has emerged as a powerful paradigm for modeling graph data, often relying on highly expressive neural backbones such as transformers or higher-order architectures. We revisit this design choice by introducing GenGNN, a modular message-passing framework for graph generation. Diffusion models with GenGNN achieve more than 90% validity on Tree and Planar datasets, within margins of graph transformers, at 2-5x faster inference speed. For molecule generation, DiGress with a GenGNN backbone achieves 99.49% Validity. A systematic ablation study shows the benefit provided by each GenGNN component, indicating the need for residual connections to mitigate oversmoothing on complicated graph-structure. Through scaling analyses, we apply a principled metric-space view to investigate learned diffusion representations and uncover whether GNNs can be expressive neural backbones for discrete diffusion.
### Title:
          Expressivity-Efficiency Tradeoffs for Hybrid Sequence Models
 - **Authors:** John Cooper, Ilias Diakonikolas, Mingchen Ma, Frederic Sala
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hybrid sequence models--combining Transformer and state-space model layers--seek to gain the expressive versatility of attention as well as the computational efficiency of state-space model layers. Despite burgeoning interest in hybrid models, we lack a basic understanding of the settings where--and underlying mechanisms through which--they offer benefits over their constituent models. In this paper, we study this question, focusing on a broad family of core synthetic tasks. For this family of tasks, we prove the existence of fundamental limitations for non-hybrid models. Specifically, any Transformer or state-space model that solves the underlying task requires either a large number of parameters or a large working memory. On the other hand, for two prototypical tasks within this family--namely selective copying and associative recall--we construct hybrid models of small size and working memory that provably solve these tasks, thus achieving the best of both worlds. Our experimental evaluation empirically validates our theoretical findings. Importantly, going beyond the settings in our theoretical analysis, we empirically show that learned--rather than constructed--hybrids outperform non-hybrid models with up to 6x as many parameters. We additionally demonstrate that hybrid models exhibit stronger length generalization and out-of-distribution robustness than non-hybrids.
### Title:
          Uncovering a Winning Lottery Ticket with Continuously Relaxed Bernoulli Gates
 - **Authors:** Itamar Tsayag, Ofir Lindenbaum
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Over-parameterized neural networks incur prohibitive memory and computational costs for resource-constrained deployment. The Strong Lottery Ticket (SLT) hypothesis suggests that randomly initialized networks contain sparse subnetworks achieving competitive accuracy without weight training. Existing SLT methods, notably edge-popup, rely on non-differentiable score-based selection, limiting optimization efficiency and scalability. We propose using continuously relaxed Bernoulli gates to discover SLTs through fully differentiable, end-to-end optimization - training only gating parameters while keeping all network weights frozen at their initialized values. Continuous relaxation enables direct gradient-based optimization of an $\ell_0$-regularization objective, eliminating the need for non-differentiable gradient estimators or iterative pruning cycles. To our knowledge, this is the first fully differentiable approach for SLT discovery that avoids straight-through estimator approximations. Experiments across fully connected networks, CNNs (ResNet, Wide-ResNet), and Vision Transformers (ViT, Swin-T) demonstrate up to 90% sparsity with minimal accuracy loss - nearly double the sparsity achieved by edge-popup at comparable accuracy - establishing a scalable framework for pre-training network sparsification.
### Title:
          TIDE: Text-Informed Dynamic Extrapolation with Step-Aware Temperature Control for Diffusion Transformers
 - **Authors:** Yihua Liu, Fanjiang Ye, Bowen Lin, Rongyu Fang, Chengming Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformer (DiT) faces challenges when generating images with higher resolution compared at training resolution, causing especially structural degradation due to attention dilution. Previous approaches attempt to mitigate this by sharpening attention distributions, but fail to preserve fine-grained semantic details and introduce obvious artifacts. In this work, we analyze the characteristics of DiTs and propose TIDE, a training-free text-to-image (T2I) extrapolation method that enables generation with arbitrary resolution and aspect ratio without additional sampling overhead. We identify the core factor for prompt information loss, and introduce a text anchoring mechanism to correct the imbalance between text and image tokens. To further eliminate artifacts, we design a dynamic temperature control mechanism that leverages the pattern of spectral progression in the diffusion process. Extensive evaluations demonstrate that TIDE delivers high-quality resolution extrapolation capability and integrates seamlessly with existing state-of-the-art methods.
### Title:
          SVG-EAR: Parameter-Free Linear Compensation for Sparse Video Generation via Error-aware Routing
 - **Authors:** Xuanyi Zhou, Qiuyang Mang, Shuo Yang, Haocheng Xi, Jintao Zhang, Huanzhi Mao, Joseph E. Gonzalez, Kurt Keutzer, Ion Stoica, Alvin Cheung
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformers (DiTs) have become a leading backbone for video generation, yet their quadratic attention cost remains a major bottleneck. Sparse attention reduces this cost by computing only a subset of attention blocks. However, prior methods often either drop the remaining blocks, which incurs information loss, or rely on learned predictors to approximate them, introducing training overhead and potential output distribution shifting. In this paper, we show that the missing contributions can be recovered without training: after semantic clustering, keys and values within each block exhibit strong similarity and can be well summarized by a small set of cluster centroids. Based on this observation, we introduce SVG-EAR, a parameter-free linear compensation branch that uses the centroid to approximate skipped blocks and recover their contributions. While centroid compensation is accurate for most blocks, it can fail on a small subset. Standard sparsification typically selects blocks by attention scores, which indicate where the model places its attention mass, but not where the approximation error would be largest. SVG-EAR therefore performs error-aware routing: a lightweight probe estimates the compensation error for each block, and we compute exactly the blocks with the highest error-to-cost ratio while compensating for skipped blocks. We provide theoretical guarantees that relate attention reconstruction error to clustering quality, and empirically show that SVG-EAR improves the quality-efficiency trade-off and increases throughput at the same generation fidelity on video diffusion tasks. Overall, SVG-EAR establishes a clear Pareto frontier over prior approaches, achieving up to 1.77$\times$ and 1.93$\times$ speedups while maintaining PSNRs of up to 29.759 and 31.043 on Wan2.2 and HunyuanVideo, respectively.
### Title:
          Synergistic Directed Execution and LLM-Driven Analysis for Zero-Day AI-Generated Malware Detection
 - **Authors:** George Edwards, Mahdi Eslamimehr
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The weaponization of LLMs for automated malware generation poses an existential threat to conventional detection paradigms. AI-generated malware exhibits polymorphic, metamorphic, and context-aware evasion capabilities that render signature-based and shallow heuristic defenses obsolete. This paper introduces a novel hybrid analysis framework that synergistically combines \emph{concolic execution} with \emph{LLM-augmented path prioritization} and \emph{deep-learning-based vulnerability classification} to detect zero-day AI-generated malware with provable guarantees. We formalize the detection problem within a first-order temporal logic over program execution traces, define a lattice-theoretic abstraction for path constraint spaces, and prove both the \emph{soundness} and \emph{relative completeness} of our detection algorithm, assuming classifier correctness. The framework introduces three novel algorithms: (i) an LLM-guided concolic exploration strategy that reduces the average number of explored paths by 73.2\% compared to depth-first search while maintaining equivalent malicious-path coverage; (ii) a transformer-based path-constraint classifier trained on symbolic execution traces; and (iii) a feedback loop that iteratively refines the LLM's prioritization policy using reinforcement learning from detection outcomes. We provide a comprehensive implementation built upon \texttt{angr} 9.2, \texttt{Z3} 4.12, Hugging Face Transformers 4.38, and PyTorch 2.2, with configuration details enabling reproducibility. Experimental evaluation on the EMBER, Malimg, SOREL-20M, and a novel AI-Gen-Malware benchmark comprising 2{,}500 LLM-synthesized samples demonstrates that achieves 98.7\% accuracy on conventional malware and 97.5\% accuracy on AI-generated threats, outperforming ClamAV, YARA, MalConv, and EMBER-GBDT baselines by margins of 8.4--52.2 percentage points on AI-generated samples.
### Title:
          Exclusive Self Attention
 - **Authors:** Shuangfei Zhai
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce exclusive self attention (XSA), a simple modification of self attention (SA) that improves Transformer's sequence modeling performance. The key idea is to constrain attention to capture only information orthogonal to the token's own value vector (thus excluding information of self position), encouraging better context modeling. Evaluated on the standard language modeling task, XSA consistently outperforms SA across model sizes up to 2.7B parameters and shows increasingly larger gains as sequence length grows.
### Title:
          GST-VLA: Structured Gaussian Spatial Tokens for 3D Depth-Aware Vision-Language-Action Models
 - **Authors:** Md Selim Sarowar, Omer Tariq, Sungho Kim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 VLA models encode visual observations as 2D patch tokens with no intrinsic geometric structure. We introduce GST-VLA with two contributions. First, the Gaussian Spatial Tokenizer (GST) converts frozen dense depth and frozen semantic patch features into $N_g{=}128$ anisotropic 3D Gaussian primitives, each parameterized by a metric residual mean $\mu \in \mathbb{R}^3$, log-scale covariance $\log \sigma \in \mathbb{R}^3$, and learned opacity $\alpha \in (0,1)$. The covariance eigenstructure encodes local surface orientation, and opacity provides per-primitive geometric confidence, both inaccessible from scalar depth. Spatial attention pooling with learned queries concentrates the fixed token budget on geometrically salient regions rather than distributing uniformly. Second, 3D Depth-Aware Chain-of-Thought (DA-CoT) reasoning supervises four structured intermediate spatial thoughts, covering 3D object grounding, grasp affordance contact geometry, pairwise metric distances, and coarse SE(3) waypoints, as explicit generation targets in the training loss. A cross-attention sublayer at every VLM transformer block provides direct access to the raw 256-primitive Gaussian field during DA-CoT generation. A 300M-parameter flow-matching action expert with mixture-of-experts feedforward sublayers decodes 7-DoF delta action chunks via conditional ODE integration, conditioned on both VLM hidden states and DA-CoT outputs through dual cross-attention. Trained with composite $\mathcal{L}_\mathrm{flow} + \mathcal{L}_\mathrm{CoT} + \mathcal{L}_\mathrm{depth}$ across three progressive stages, GST-VLA achieves 96.4% on LIBERO (+2.0%), and 80.2% on SimplerEnv (+5.4%). Ablations isolate the contribution of each GST component, each DA-CoT thought, and each training stage, confirming independent and synergistic gains concentrated on precision demanding tasks.
### Title:
          Composed Vision-Language Retrieval for Skin Cancer Case Search via Joint Alignment of Global and Local Representations
 - **Authors:** Yuheng Wang, Yuji Lin, Dongrun Zhu, Jiayue Cai, Sunil Kalia, Harvey Lui, Chunqi Chang, Z. Jane Wang, Tim K. Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Medical image retrieval aims to identify clinically relevant lesion cases to support diagnostic decision making, education, and quality control. In practice, retrieval queries often combine a reference lesion image with textual descriptors such as dermoscopic features. We study composed vision-language retrieval for skin cancer, where each query consists of an image to text pair and the database contains biopsy-confirmed, multi-class disease cases. We propose a transformer based framework that learns hierarchical composed query representations and performs joint global-local alignment between queries and candidate images. Local alignment aggregates discriminative regions via multiple spatial attention masks, while global alignment provides holistic semantic supervision. The final similarity is computed through a convex, domain-informed weighting that emphasizes clinically salient local evidence while preserving global consistency. Experiments on the public Derm7pt dataset demonstrate consistent improvements over state-of-the-art methods. The proposed framework enables efficient access to relevant medical records and supports practical clinical deployment.
### Title:
          VIVID-Med: LLM-Supervised Structured Pretraining for Deployable Medical ViTs
 - **Authors:** Xiyao Wang, Xiaoyu Tan, Yang Dai, Yuxuan Fu, Shuo Li, Xihe Qiu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language pretraining has driven significant progress in medical image analysis. However, current methods typically supervise visual encoders using one-hot labels or free-form text, neither of which effectively captures the complex semantic relationships among clinical findings. In this study, we introduce VIVID-Med, a novel framework that leverages a frozen large language model (LLM) as a structured semantic teacher to pretrain medical vision transformers (ViTs). VIVID-Med translates clinical findings into verifiable JSON field-state pairs via a Unified Medical Schema (UMS), utilizing answerability-aware masking to focus optimization. It then employs Structured Prediction Decomposition (SPD) to partition cross-attention into orthogonality-regularized query groups, extracting complementary visual aspects. Crucially, the LLM is discarded post-training, yielding a lightweight, deployable ViT-only backbone. We evaluated VIVID-Med across multiple settings: on CheXpert linear probing, it achieves a macro-AUC of 0.8588, outperforming BiomedCLIP by +6.65 points while using 500x less data. It also demonstrates robust zero-shot cross-domain transfer to NIH ChestX-ray14 (0.7225 macro-AUC) and strong cross-modality generalization to CT, achieving 0.8413 AUC on LIDC-IDRI lung nodule classification and 0.9969 macro-AUC on OrganAMNIST 11-organ classification. VIVID-Med offers a highly efficient, scalable alternative to deploying resource-heavy vision-language models in clinical settings.
### Title:
          Transformer-Based Multi-Region Segmentation and Radiomic Analysis of HR-pQCT Imaging
 - **Authors:** Mohseu Rashid Subah, Mohammed Abdul Gani Zilani, Thomas L. Nickolas, Matthew R. Allen, Stuart J. Warden, Rachel K. Surowiec
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Osteoporosis is a skeletal disease typically diagnosed using dual-energy X-ray absorptiometry (DXA), which quantifies areal bone mineral density but overlooks bone microarchitecture and surrounding soft tissues. High-resolution peripheral quantitative computed tomography (HR-pQCT) enables three-dimensional microstructural imaging with minimal radiation. However, current analysis pipelines largely focus on mineralized bone compartments, leaving much of the acquired image data underutilized. We introduce a fully automated framework for binary osteoporosis classification using radiomics features extracted from anatomically segmented HR-pQCT images. To our knowledge, this work is the first to leverage a transformer-based segmentation architecture, i.e., the SegFormer, for fully automated multi-region HR-pQCT analysis. The SegFormer model simultaneously delineated the cortical and trabecular bone of the tibia and fibula along with surrounding soft tissues and achieved a mean F1 score of 95.36%. Soft tissues were further subdivided into skin, myotendinous, and adipose regions through post-processing. From each region, 939 radiomic features were extracted and dimensionally reduced to train six machine learning classifiers on an independent dataset comprising 20,496 images from 122 HR-pQCT scans. The best image level performance was achieved using myotendinous tissue features, yielding an accuracy of 80.08% and an area under the receiver operating characteristic curve (AUROC) of 0.85, outperforming bone-based models. At the patient level, replacing standard biological, DXA, and HR-pQCT parameters with soft tissue radiomics improved AUROC from 0.792 to 0.875. These findings demonstrate that automated, multi-region HR-pQCT segmentation enables the extraction of clinically informative signals beyond bone alone, highlighting the importance of integrated tissue assessment for osteoporosis detection.
### Title:
          GIAT: A Geologically-Informed Attention Transformer for Lithology Identification
 - **Authors:** Jie Li, Qishun Yang, Nuo Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate lithology identification from well logs is crucial for subsurface resource evaluation. Although Transformer-based models excel at sequence modeling, their "black-box" nature and lack of geological guidance limit their performance and trustworthiness. To overcome these limitations, this letter proposes the Geologically-Informed Attention Transformer (GIAT), a novel framework that deeply fuses data-driven geological priors with the Transformer's attention mechanism. The core of GIAT is a new attention-biasing mechanism. We repurpose Category-Wise Sequence Correlation (CSC) filters to generate a geologically-informed relational matrix, which is injected into the self-attention calculation to explicitly guide the model toward geologically coherent patterns. On two challenging datasets, GIAT achieves state-of-the-art performance with an accuracy of up to 95.4%, significantly outperforming existing models. More importantly, GIAT demonstrates exceptional interpretation faithfulness under input perturbations and generates geologically coherent predictions. Our work presents a new paradigm for building more accurate, reliable, and interpretable deep learning models for geoscience applications.
### Title:
          Progressive Split Mamba: Effective State Space Modelling for Image Restoration
 - **Authors:** Mohammed Hassanin, Nour Moustafa, Weijian Deng, Ibrahim Radwan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Image restoration requires simultaneously preserving fine-grained local structures and maintaining long-range spatial coherence. While convolutional networks struggle with limited receptive fields, and Transformers incur quadratic complexity for global attention, recent State Space Models (SSMs), such as Mamba, provide an appealing linear-time alternative for long-range dependency modelling. However, naively extending Mamba to 2D images exposes two intrinsic shortcomings. First, flattening 2D feature maps into 1D sequences disrupts spatial topology, leading to locality distortion that hampers precise structural recovery. Second, the stability-driven recurrent dynamics of SSMs induce long-range decay, progressively attenuating information across distant spatial positions and weakening global consistency. Together, these effects limit the effectiveness of state-space modelling in high-fidelity restoration. We propose Progressive Split-Mamba (PS-Mamba), a topology-aware hierarchical state-space framework designed to reconcile locality preservation with efficient global propagation. Instead of sequentially flattening entire feature maps, PS-Mamba performs geometry-consistent partitioning, maintaining neighbourhood integrity prior to state-space processing. A progressive split hierarchy (halves, quadrants, octants) enables structured multi-scale modelling while retaining linear complexity. To counteract long-range decay, we introduce symmetric cross-scale shortcut pathways that directly transmit low-frequency global context across hierarchical levels, stabilising information flow over large spatial extents. Extensive experiments on super-resolution, denoising, and JPEG artifact reduction show consistent improvements over recent Mamba-based and attention-based models with a clear margin.
### Title:
          The Radio-Frequency Transformer for Signal Separation
 - **Authors:** Egor Lifar, Semyon Savkin, Rachana Madhukara, Tejas Jayashankar, Yury Polyanskiy, Gregory W. Wornell
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study a problem of signal separation: estimating a signal of interest (SOI) contaminated by an unknown non-Gaussian background/interference. Given the training data consisting of examples of SOI and interference, we show how to build a fully data-driven signal separator. To that end we learn a good discrete tokenizer for SOI and then train an end-to-end transformer on a cross-entropy loss. Training with a cross-entropy shows substantial improvements over the conventional mean-squared error (MSE). Our tokenizer is a modification of Google's SoundStream, which incorporates additional transformer layers and switches from VQVAE to finite-scalar quantization (FSQ). Across real and synthetic mixtures from the MIT RF Challenge dataset, our method achieves competitive performance, including a 122x reduction in bit-error rate (BER) over prior state-of-the-art techniques for separating a QPSK signal from 5G interference. The learned representation adapts to the interference type without side information and shows zero-shot generalization to unseen mixtures at inference time, underscoring its potential beyond RF. Although we instantiate our approach on radio-frequency mixtures, we expect the same architecture to apply to gravitational-wave data (e.g., LIGO strain) and other scientific sensing problems that require data-driven modeling of background and noise.
### Title:
          Emotion is Not Just a Label: Latent Emotional Factors in LLM Processing
 - **Authors:** Benjamin Reichman, Adar Avasian, Samuel Webster, Larry Heck
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models are routinely deployed on text that varies widely in emotional tone, yet their reasoning behavior is typically evaluated without accounting for emotion as a source of representational variation. Prior work has largely treated emotion as a prediction target, for example in sentiment analysis or emotion classification. In contrast, we study emotion as a latent factor that shapes how models attend to and reason over text. We analyze how emotional tone systematically alters attention geometry in transformer models, showing that metrics such as locality, center-of-mass distance, and entropy vary across emotions and correlate with downstream question-answering performance. To facilitate controlled study of these effects, we introduce Affect-Uniform ReAding QA (AURA-QA), a question-answering dataset with emotionally balanced, human-authored context passages. Finally, an emotional regularization framework is proposed that constrains emotion-conditioned representational drift during training. Experiments across multiple QA benchmarks demonstrate that this approach improves reading comprehension in both emotionally-varying and non-emotionally varying datasets, yielding consistent gains under distribution shift and in-domain improvements on several benchmarks.
### Title:
          SPAR-K: Scheduled Periodic Alternating Early Exit for Spoken Language Models
 - **Authors:** Hsiao-Ying Huang, Cheng-Han Chiang, Hung-yi Lee
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Interleaved spoken language models (SLMs) alternately generate text and speech tokens, but decoding at full transformer depth for every step becomes costly, especially due to long speech sequences. We propose SPAR-K, a modality-aware early exit framework designed to accelerate interleaved SLM inference while preserving perceptual quality. SPAR-K introduces a speech alternating-depth schedule: most speech positions exit at a fixed intermediate layer, while periodic full-depth "refresh" steps mitigate distribution shift due to early exit. We evaluate our framework using Step-Audio-2-mini and GLM-4-Voice across four datasets spanning reasoning, factual QA, and dialogue tasks, measuring performance in terms of ASR transcription accuracy and perceptual quality. Experimental results demonstrate that SPAR-K largely preserves question-answering accuracy with a maximum accuracy drop of 0.82\% while reducing average speech decoding depth by up to 11\% on Step-Audio-2-mini and 5\% on GLM-4-Voice, both with negligible changes in MOS and WER and no auxiliary computation overhead. We further demonstrate that confidence-based early exit strategies, widely used in text LLMs, are suboptimal for SLMs, highlighting that the unique statistical nature of speech tokens necessitates a specialized early exit design.
### Title:
          LooComp: Leverage Leave-One-Out Strategy to Encoder-only Transformer for Efficient Query-aware Context Compression
 - **Authors:** Thao Do, Dinh Phu Tran, An Vo, Seon Kwon Kim, Daeyoung Kim
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Efficient context compression is crucial for improving the accuracy and scalability of question answering. For the efficiency of Retrieval Augmented Generation, context should be delivered fast, compact, and precise to ensure clue sufficiency and budget-friendly LLM reader cost. We propose a margin-based framework for query-driven context pruning, which identifies sentences that are critical for answering a query by measuring changes in clue richness when they are omitted. The model is trained with a composite ranking loss that enforces large margins for critical sentences while keeping non-critical ones near neutral. Built on a lightweight encoder-only Transformer, our approach generally achieves strong exact-match and F1 scores with high-throughput inference and lower memory requirements than those of major baselines. In addition to efficiency, our method yields effective compression ratios without degrading answering performance, demonstrating its potential as a lightweight and practical alternative for retrieval-augmented tasks.
### Title:
          RAE-NWM: Navigation World Model in Dense Visual Representation Space
 - **Authors:** Mingkun Zhang, Wangtian Shen, Fan Zhang, Haijian Qin, Zihao Pei, Ziyang Meng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual navigation requires agents to reach goals in complex environments through perception and planning. World models address this task by simulating action-conditioned state transitions to predict future observations. Current navigation world models typically learn state evolution under actions within the compressed latent space of a Variational Autoencoder, where spatial compression often discards fine-grained structural information and hinders precise control. To better understand the propagation characteristics of different representations, we conduct a linear dynamics probe and observe that dense DINOv2 features exhibit stronger linear predictability for action-conditioned transitions. Motivated by this observation, we propose the Representation Autoencoder-based Navigation World Model (RAE-NWM), which models navigation dynamics in a dense visual representation space. We employ a Conditional Diffusion Transformer with Decoupled Diffusion Transformer head (CDiT-DH) to model continuous transitions, and introduce a separate time-driven gating module for dynamics conditioning to regulate action injection strength during generation. Extensive evaluations show that modeling sequential rollouts in this space improves structural stability and action accuracy, benefiting downstream planning and navigation.
### Title:
          Towards Instance Segmentation with Polygon Detection Transformers
 - **Authors:** Jiacheng Sun, Jiaqi Lin, Wenlong Hu, Haoyang Li, Xinghong Zhou, Chenghai Mao, Yan Peng, Xiaomao Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 One of the bottlenecks for instance segmentation today lies in the conflicting requirements of high-resolution inputs and lightweight, real-time inference. To address this bottleneck, we present a Polygon Detection Transformer (Poly-DETR) to reformulate instance segmentation as sparse vertex regression via Polar Representation, thereby eliminating the reliance on dense pixel-wise mask prediction. Considering the box-to-polygon reference shift in Detection Transformers, we propose Polar Deformable Attention and Position-Aware Training Scheme to dynamically update supervision and focus attention on boundary cues. Compared with state-of-the-art polar-based methods, Poly-DETR achieves a 4.7 mAP improvement on MS COCO test-dev. Moreover, we construct a parallel mask-based counterpart to support a systematic comparison between polar and mask representations. Experimental results show that Poly-DETR is more lightweight in high-resolution scenarios, reducing memory consumption by almost half on Cityscapes dataset. Notably, on PanNuke (cell segmentation) and SpaceNet (building footprints) datasets, Poly-DETR surpasses its mask-based counterpart on all metrics, which validates its advantage on regular-shaped instances in domain-specific settings.
### Title:
          Efficient Reasoning at Fixed Test-Time Cost via Length-Aware Attention Priors and Gain-Aware Training
 - **Authors:** Rian Atri
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study efficient reasoning under tight compute. We ask how to make structured, correct decisions without increasing test time cost. We add two training only components to small and medium Transformers that also transfer to broader differentiable optimizers. First, a length aware attention prior built via fuzzy regime position alignment, RPA, yields a normalized pre softmax bias that guides attention like a structured regularizer while adding no new inference parameters. Second, a minimal gain aware controller, Guardian, nudges attention sharpness only when validation improvements warrant it, following a two timescale policy gradient view of nonconvex optimization. It is disabled at inference. A KL perspective shows softmax of z plus log pi as MAP with KL regularization, grounding the prior in a principled objective. Under strict compute parity on WikiText 2, we reduce validation cross entropy while matching baseline latency and memory. At inference, we add a precomputed, cached prior B of T as a single additive bias per head. The controller does not run. In practice, this incurs negligible overhead, a cached bias add per head, with no measurable p50 latency shift. Our results suggest that length aware priors and late phase gain control preserve scarce improvements, especially in long span, noisy logit regimes, while keeping test time costs effectively unchanged.
### Title:
          EventVGGT: Exploring Cross-Modal Distillation for Consistent Event-based Depth Estimation
 - **Authors:** Yinrui Ren, Jinjing Zhu, Kanghao Chen, Zhuoxiao Li, Jing Ou, Zidong Cao, Tongyan Hua, Peilun Shi, Yingchun Fu, Wufan Zhao, Hui Xiong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Event cameras offer superior sensitivity to high-speed motion and extreme lighting, making event-based monocular depth estimation a promising approach for robust 3D perception in challenging conditions. However, progress is severely hindered by the scarcity of dense depth annotations. While recent annotation-free approaches mitigate this by distilling knowledge from Vision Foundation Models (VFMs), a critical limitation persists: they process event streams as independent frames. By neglecting the inherent temporal continuity of event data, these methods fail to leverage the rich temporal priors encoded in VFMs, ultimately yielding temporally inconsistent and less accurate depth predictions. To address this, we introduce EventVGGT, a novel framework that explicitly models the event stream as a coherent video sequence. To the best of our knowledge, we are the first to distill spatio-temporal and multi-view geometric priors from the Visual Geometry Grounded Transformer (VGGT) into the event domain. We achieve this via a comprehensive tri-level distillation strategy: (i) Cross-Modal Feature Mixture (CMFM) bridges the modality gap at the output level by fusing RGB and event features to generate auxiliary depth predictions; (ii) Spatio-Temporal Feature Distillation (STFD) distills VGGT's powerful spatio-temporal representations at the feature level; and (iii) Temporal Consistency Distillation (TCD) enforces cross-frame coherence at the temporal level by aligning inter-frame depth changes. Extensive experiments demonstrate that EventVGGT consistently outperforms existing methods -- reducing the absolute mean depth error at 30m by over 53\% on EventScape (from 2.30 to 1.06) -- while exhibiting robust zero-shot generalization on the unseen DENSE and MVSEC datasets.
### Title:
          Reviving ConvNeXt for Efficient Convolutional Diffusion Models
 - **Authors:** Taesung Kwon, Lorenzo Bianchi, Lennart Wittke, Felix Watine, Fabio Carrara, Jong Chul Ye, Romann Weber, Vinicius Azevedo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent diffusion models increasingly favor Transformer backbones, motivated by the remarkable scalability of fully attentional architectures. Yet the locality bias, parameter efficiency, and hardware friendliness--the attributes that established ConvNets as the efficient vision backbone--have seen limited exploration in modern generative modeling. Here we introduce the fully convolutional diffusion model (FCDM), a model having a backbone similar to ConvNeXt, but designed for conditional diffusion modeling. We find that using only 50% of the FLOPs of DiT-XL/2, FCDM-XL achieves competitive performance with 7$\times$ and 7.5$\times$ fewer training steps at 256$\times$256 and 512$\times$512 resolutions, respectively. Remarkably, FCDM-XL can be trained on a 4-GPU system, highlighting the exceptional training efficiency of our architecture. Our results demonstrate that modern convolutional designs provide a competitive and highly efficient alternative for scaling diffusion models, reviving ConvNeXt as a simple yet powerful building block for efficient generative modeling.
### Title:
          RiO-DETR: DETR for Real-time Oriented Object Detection
 - **Authors:** Zhangchi Hu, Yifan Zhao, Yansong Peng, Wenzhang Sun, Xiangchen Yin, Jie Chen, Peixi Wu, Hebei Li, Xinghao Wang, Dongsheng Jiang, Xiaoyan Sun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present RiO-DETR: DETR for Real-time Oriented Object Detection, the first real-time oriented detection transformer to the best of our knowledge. Adapting DETR to oriented bounding boxes (OBBs) poses three challenges: semantics-dependent orientation, angle periodicity that breaks standard Euclidean refinement, and an enlarged search space that slows convergence. RiO-DETR resolves these issues with task-native designs while preserving real-time efficiency. First, we propose Content-Driven Angle Estimation by decoupling angle from positional queries, together with Rotation-Rectified Orthogonal Attention to capture complementary cues for reliable orientation. Second, Decoupled Periodic Refinement combines bounded coarse-to-fine updates with a Shortest-Path Periodic Loss for stable learning across angular seams. Third, Oriented Dense O2O injects angular diversity into dense supervision to speed up angle convergence at no extra cost. Extensive experiments on DOTA-1.0, DIOR-R, and FAIR-1M-2.0 demonstrate RiO-DETR establishes a new speed--accuracy trade-off for real-time oriented detection. Code will be made publicly available.
### Title:
          TrainDeeploy: Hardware-Accelerated Parameter-Efficient Fine-Tuning of Small Transformer Models at the Extreme Edge
 - **Authors:** Run Wang, Victor J.B. Jung, Philip Wiese, Francesco Conti, Alessio Burrello, Luca Benini
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 On-device tuning of deep neural networks enables long-term adaptation at the edge while preserving data privacy. However, the high computational and memory demands of backpropagation pose significant challenges for ultra-low-power, memory-constrained extreme-edge devices. These challenges are further amplified for attention-based models due to their architectural complexity and computational scale. We present TrainDeeploy, a framework that unifies efficient inference and on-device training on heterogeneous ultra-low-power System-on-Chips (SoCs). TrainDeeploy provides the first complete on-device training pipeline for extreme-edge SoCs supporting both Convolutional Neural Networks (CNNs) and Transformer models, together with multiple training strategies such as selective layer-wise fine-tuning and Low-Rank Adaptation (LoRA). On a RISC-V-based heterogeneous SoC, we demonstrate the first end-to-end on-device fine-tuning of a Compact Convolutional Transformer (CCT), achieving up to 11 trained images per second. We show that LoRA reduces dynamic memory usage by 23%, decreases the number of trainable parameters and gradients by 15x, and reduces memory transfer volume by 1.6x compared to full backpropagation. TrainDeeploy achieves up to 4.6 FLOP/cycle on CCT (0.28M parameters, 71-126M FLOPs) and up to 13.4 FLOP/cycle on Deep-AE (0.27M parameters, 0.8M FLOPs), while expanding the scope of prior frameworks to support both CNN and Transformer models with parameter-efficient tuning on extreme-edge platforms.
### Title:
          DCAU-Net: Differential Cross Attention and Channel-Spatial Feature Fusion for Medical Image Segmentation
 - **Authors:** Yanxin Li, Hui Wan, Libin Lan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate medical image segmentation requires effective modeling of both long-range dependencies and fine-grained boundary details. While transformers mitigate the issue of insufficient semantic information arising from the limited receptive field inherent in convolutional neural networks, they introduce new challenges: standard self-attention incurs quadratic computational complexity and often assigns non-negligible attention weights to irrelevant regions, diluting focus on discriminative structures and ultimately compromising segmentation accuracy. Existing attention variants, although effective in reducing computational complexity, fail to suppress redundant computation and inadvertently impair global context modeling. Furthermore, conventional fusion strategies in encoder-decoder architectures, typically based on simple concatenation or summation, can not adaptively integrate high-level semantic information with low-level spatial details. To address these limitations, we propose DCAU-Net, a novel yet efficient segmentation framework with two key ideas. First, a new Differential Cross Attention (DCA) is designed to compute the difference between two independent softmax attention maps to adaptively highlight discriminative structures. By replacing pixel-wise key and value tokens with window-level summary tokens, DCA dramatically reduces computational complexity without sacrificing precision. Second, a Channel-Spatial Feature Fusion (CSFF) strategy is introduced to adaptively recalibrate features from skip connections and up-sampling paths through using sequential channel and spatial attention, effectively suppressing redundant information and amplifying salient cues. Experiments on two public benchmarks demonstrate that DCAU-Net achieves competitive performance with enhanced segmentation accuracy and robustness.
### Title:
          An Optimal Control Approach To Transformer Training
 - **Authors:** Kağan Akman, Naci Saldı, Serdar Yüksel
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we develop a rigorous optimal control-theoretic approach to Transformer training that respects key structural constraints such as (i) realized-input-independence during execution, (ii) the ensemble control nature of the problem, and (iii) positional dependence. We model the Transformer architecture as a discrete-time controlled particle system with shared actions, exhibiting noise-free McKean-Vlasov dynamics. While the resulting dynamics is not Markovian, we show that lifting it to probability measures produces a fully-observed Markov decision process (MDP). Positional encodings are incorporated into the state space to preserve the sequence order under lifting. Using the dynamic programming principle, we establish the existence of globally optimal policies under mild assumptions of compactness. We further prove that closed-loop policies in the lifted is equivalent to an initial-distribution dependent open-loop policy, which are realized-input-independent and compatible with standard Transformer training. To train a Transformer, we propose a triply quantized training procedure for the lifted MDP by quantizing the state space, the space of probability measures, and the action space, and show that any optimal policy for the triply quantized model is near-optimal for the original training problem. Finally, we establish stability and empirical consistency properties of the lifted model by showing that the value function is continuous with respect to the perturbations of the initial empirical measures and convergence of policies as the data size increases. This approach provides a globally optimal and robust alternative to gradient-based training without requiring smoothness or convexity.
### Title:
          Routing without Forgetting
 - **Authors:** Alessio Masano, Giovanni Bellitto, Dipam Goswani, Joost Van de Weijer, Concetto Spampinato
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Continual learning in transformers is commonly addressed through parameter-efficient adaptation: prompts, adapters, or LoRA modules are specialized per task while the backbone remains frozen. Although effective in controlled multi-epoch settings, these approaches rely on gradual gradient-based specialization and struggle in Online Continual Learning (OCL), where data arrive as a non-stationary stream and each sample may be observed only once. We recast continual learning in transformers as a routing problem: under strict online constraints, the model must dynamically select the appropriate representational subspace for each input without explicit task identifiers or repeated optimization. We thus introduce Routing without Forgetting (RwF), a transformer architecture augmented with energy-based associative retrieval layers inspired by Modern Hopfield Networks. Instead of storing or merging task-specific prompts, RwF generates dynamic prompts through single-step associative retrieval over the transformer token embeddings at each layer. Retrieval corresponds to the closed-form minimization of a strictly convex free-energy functional, enabling input-conditioned routing within each forward pass, independently of iterative gradient refinement. Across challenging class-incremental benchmarks, RwF improves over existing prompt-based methods. On Split-ImageNet-R and Split-ImageNet-S, RwF outperforms prior prompt-based approaches by a large margin, even in few-shot learning regimes. These results indicate that embedding energy-based associative routing directly within the transformer backbone provides a principled and effective foundation for OCL.
### Title:
          BinaryAttention: One-Bit QK-Attention for Vision and Diffusion Transformers
 - **Authors:** Chaodong Xiao, Zhengqiang Zhang, Lei Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers have achieved widespread and remarkable success, while the computational complexity of their attention modules remains a major bottleneck for vision tasks. Existing methods mainly employ 8-bit or 4-bit quantization to balance efficiency and accuracy. In this paper, with theoretical justification, we indicate that binarization of attention preserves the essential similarity relationships, and propose BinaryAttention, an effective method for fast and accurate 1-bit qk-attention. Specifically, we retain only the sign of queries and keys in computing the attention, and replace the floating dot products with bit-wise operations, significantly reducing the computational cost. We mitigate the inherent information loss under 1-bit quantization by incorporating a learnable bias, and enable end-to-end acceleration. To maintain the accuracy of attention, we adopt quantization-aware training and self-distillation techniques, mitigating quantization errors while ensuring sign-aligned similarity. BinaryAttention is more than 2x faster than FlashAttention2 on A100 GPUs. Extensive experiments on vision transformer and diffusion transformer benchmarks demonstrate that BinaryAttention matches or even exceeds full-precision attention, validating its effectiveness. Our work provides a highly efficient and effective alternative to full-precision attention, pushing the frontier of low-bit vision and diffusion transformers. The codes and models can be found at this https URL.
### Title:
          A saccade-inspired approach to image classification using visiontransformer attention maps
 - **Authors:** Matthis Dallain, Laurent Rodriguez, Laurent Udo Perrinet, Benoît Miramond
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Human vision achieves remarkable perceptual performance while operating under strict metabolic constraints. A key ingredient is the selective attention mechanism, driven by rapid saccadic eye movements that constantly reposition the high-resolution fovea onto task-relevant locations, unlike conventional AI systems that process entire images with equal emphasis. Our work aims to draw inspiration from the human visual system to create smarter, more efficient image processing models. Using DINO, a self-supervised Vision Transformer that produces attention maps strikingly similar to human gaze patterns, we explore a saccade inspired method to focus the processing of information on key regions in visual space. To do so, we use the ImageNet dataset in a standard classification task and measure how each successive saccade affects the model's class scores. This selective-processing strategy preserves most of the full-image classification performance and can even outperform it in certain cases. By benchmarking against established saliency models built for human gaze prediction, we demonstrate that DINO provides superior fixation guidance for selecting informative regions. These findings highlight Vision Transformer attention as a promising basis for biologically inspired active vision and open new directions for efficient, neuromorphic visual processing.
### Title:
          Surgical Repair of Collapsed Attention Heads in ALiBi Transformers
 - **Authors:** Palmer Schallon
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We identify a systematic attention collapse pathology in the BLOOM family of transformer language models, where ALiBi positional encoding causes 31-44% of attention heads to attend almost entirely to the beginning-of-sequence token. The collapse follows a predictable pattern across four model scales (560M to 7.1B parameters), concentrating in head indices where ALiBi's slope schedule imposes the steepest distance penalties. We introduce surgical reinitialization: targeted Q/K/V reinitialization with zeroed output projections and gradient-masked freezing of all non-surgical parameters. Applied to BLOOM-1b7 on a single consumer GPU, the technique recovers 98.7% operational head capacity (242 to 379 of 384 heads) in two passes. A controlled comparison with C4 training data confirms that reinitialization -- not corpus content -- drives recovery, and reveals two distinct post-surgical phenomena: early global functional redistribution that improves the model, and late local degradation that accumulates under noisy training signal. An extended experiment reinitializing mostly-healthy heads alongside collapsed ones produces a model that transiently outperforms stock BLOOM-1b7 by 25% on training perplexity (12.70 vs. 16.99), suggesting that pretrained attention configurations are suboptimal local minima. Code, checkpoints, and diagnostic tools are released as open-source software.
### Title:
          Automatic Cardiac Risk Management Classification using large-context Electronic Patients Health Records
 - **Authors:** Jacopo Vitale, David Della Morte, Luca Bacco, Mario Merone, Mark de Groot, Saskia Haitjema, Leandro Pecchia, Bram van Es
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 To overcome the limitations of manual administrative coding in geriatric Cardiovascular Risk Management, this study introduces an automated classification framework leveraging unstructured Electronic Health Records (EHRs). Using a dataset of 3,482 patients, we benchmarked three distinct modeling paradigms on longitudinal Dutch clinical narratives: classical machine learning baselines, specialized deep learning architectures optimized for large-context sequences, and general-purpose generative Large Language Models (LLMs) in a zero-shot setting. Additionally, we evaluated a late fusion strategy to integrate unstructured text with structured medication embeddings and anthropometric data. Our analysis reveals that the custom Transformer architecture outperforms both traditional methods and generative \acs{llm}s, achieving the highest F1-scores and Matthews Correlation Coefficients. These findings underscore the critical role of specialized hierarchical attention mechanisms in capturing long-range dependencies within medical texts, presenting a robust, automated alternative to manual workflows for clinical risk stratification.
### Title:
          AutoViVQA: A Large-Scale Automatically Constructed Dataset for Vietnamese Visual Question Answering
 - **Authors:** Nguyen Anh Tuong, Phan Ba Duc, Nguyen Trung Quoc, Tran Dac Thinh, Dang Duy Lan, Nguyen Quoc Thinh, Tung Le
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual Question Answering (VQA) is a fundamental multimodal task that requires models to jointly understand visual and textual information. Early VQA systems relied heavily on language biases, motivating subsequent work to emphasize visual grounding and balanced datasets. With the success of large-scale pre-trained transformers for both text and vision domains -- such as PhoBERT for Vietnamese language understanding and Vision Transformers (ViT) for image representation learning -- multimodal fusion has achieved remarkable progress. For Vietnamese VQA, several datasets have been introduced to promote research in low-resource multimodal learning, including ViVQA, OpenViVQA, and the recently proposed ViTextVQA. These resources enable benchmarking of models that integrate linguistic and visual features in the Vietnamese context. Evaluation of VQA systems often employs automatic metrics originally designed for image captioning or machine translation, such as BLEU, METEOR, CIDEr, Recall, Precision, and F1-score. However, recent research suggests that large language models can further improve the alignment between automatic evaluation and human judgment in VQA tasks. In this work, we explore Vietnamese Visual Question Answering using transformer-based architectures, leveraging both textual and visual pre-training while systematically comparing automatic evaluation metrics under multilingual settings.
### Title:
          FrameDiT: Diffusion Transformer with Frame-Level Matrix Attention for Efficient Video Generation
 - **Authors:** Minh Khoa Le, Kien Do, Duc Thanh Nguyen, Truyen Tran
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-fidelity video generation remains challenging for diffusion models due to the difficulty of modeling complex spatio-temporal dynamics efficiently. Recent video diffusion methods typically represent a video as a sequence of spatio-temporal tokens which can be modeled using Diffusion Transformers (DiTs). However, this approach faces a trade-off between the strong but expensive Full 3D Attention and the efficient but temporally limited Local Factorized Attention. To resolve this trade-off, we propose Matrix Attention, a frame-level temporal attention mechanism that processes an entire frame as a matrix and generates query, key, and value matrices via matrix-native operations. By attending across frames rather than tokens, Matrix Attention effectively preserves global spatio-temporal structure and adapts to significant motion. We build FrameDiT-G, a DiT architecture based on MatrixAttention, and further introduce FrameDiT-H, which integrates Matrix Attention with Local Factorized Attention to capture both large and small motion. Extensive experiments show that FrameDiT-H achieves state-of-the-art results across multiple video generation benchmarks, offering improved temporal coherence and video quality while maintaining efficiency comparable to Local Factorized Attention.
### Title:
          LogoDiffuser: Training-Free Multilingual Logo Generation and Stylization via Letter-Aware Attention Control
 - **Authors:** Mingyu Kang, Hyein Seo, Yuna Jeong, Junhyeong Park, Yong Suk Choi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in text-to-image generation have been remarkable, but generating multilingual design logos that harmoniously integrate visual and textual elements remains a challenging task. Existing methods often distort character geometry when applying creative styles and struggle to support multilingual text generation without additional training. To address these challenges, we propose LogoDiffuser, a training-free method that synthesizes multilingual logo designs using the multimodal diffusion transformer. Instead of using textual prompts, we input the target characters as images, enabling robust character structure control regardless of language. We first analyze the joint attention mechanism to identify core tokens, which are tokens that strongly respond to textual structures. With this observation, our method integrates character structure and visual design by injecting the most informative attention maps. Furthermore, we perform layer-wise aggregation of attention maps to mitigate attention shifts across layers and obtain consistent core tokens. Extensive experiments and user studies demonstrate that our method achieves state-of-the-art performance in multilingual logo generation.
### Title:
          Quantifying the Necessity of Chain of Thought through Opaque Serial Depth
 - **Authors:** Jonah Brown-Cohen, David Lindner, Rohin Shah
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) tend to externalize their reasoning in their chain of thought, making the chain of thought a good target for monitoring. This is partially an inherent feature of the Transformer architecture: sufficiently long serial cognition must pass through the chain of thought (Korbak et al., 2025). We formalize this argument through the notion of opaque serial depth, given by the length of the longest computation that can be done without the use of interpretable intermediate steps like chain of thought. Given this formalization, we compute numeric upper bounds on the opaque serial depth of Gemma 3 models, as well as asymptotic results for additional architectures beyond standard LLMs. We also open-source an automated method that can calculate upper bounds on the opaque serial depth of arbitrary neural networks, and use it to demonstrate that Mixture-of-Experts models likely have lower depth than dense models. Overall, our results suggest that opaque serial depth is a useful tool for understanding the potential for models to do significant reasoning that is not externalized.
### Title:
          RA-SSU: Towards Fine-Grained Audio-Visual Learning with Region-Aware Sound Source Understanding
 - **Authors:** Muyi Sun, Yixuan Wang, Hong Wang, Chen Su, Man Zhang, Xingqun Qi, Qi Li, Zhenan Sun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Audio-Visual Learning (AVL) is one fundamental task of multi-modality learning and embodied intelligence, displaying the vital role in scene understanding and interaction. However, previous researchers mostly focus on exploring downstream tasks from a coarse-grained perspective (e.g., audio-visual correspondence, sound source localization, and audio-visual event localization). Considering providing more specific scene perception details, we newly define a fine-grained Audio-Visual Learning task, termed Region-Aware Sound Source Understanding (RA-SSU), which aims to achieve region-aware, frame-level, and high-quality sound source understanding. To support this goal, we innovatively construct two corresponding datasets, i.e. fine-grained Music (f-Music) and fine-grained Lifescene (f-Lifescene), each containing annotated sound source masks and frame-by-frame textual descriptions. The f-Music dataset includes 3,976 samples across 22 scene types related to specific application scenarios, focusing on music scenes with complex instrument mixing. The f-Lifescene dataset contains 6,156 samples across 61 types representing diverse sounding objects in life scenarios. Moreover, we propose SSUFormer, a Sound-Source Understanding TransFormer benchmark that facilitates both the sound source segmentation and sound region description with a multi-modal input and multi-modal output architecture. Specifically, we design two modules for this framework, Mask Collaboration Module (MCM) and Mixture of Hierarchical-prompted Experts (MoHE), to respectively enhance the accuracy and enrich the elaboration of the sound source description. Extensive experiments are conducted on our two datasets to verify the feasibility of the task, evaluate the availability of the datasets, and demonstrate the superiority of the SSUFormer, which achieves SOTA performance on the Sound Source Understanding benchmark.
### Title:
          Correction of Transformer-Based Models with Smoothing Pseudo-Projector
 - **Authors:** Vitaly Bulgakov
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The pseudo-projector is a lightweight modification that can be integrated into existing language models and other neural networks without altering their core architecture. It can be viewed as a hidden-representation corrector that reduces sensitivity to noise by suppressing directions induced by label-irrelevant input content. The design is inspired by the multigrid (MG) paradigm, originally developed to accelerate the convergence of iterative solvers for partial differential equations and boundary value problems, and later extended to more general linear systems through algebraic multigrid methods. We refer to the method as a pseudo-projector because its linear prototype corresponds to a strictly idempotent orthogonal projector, whereas the practical formulation employs learnable restriction and prolongation operators and therefore does not, in general, satisfy the properties of an exact orthogonal projection. We evaluate the proposed approach on transformer-based text classification tasks, as well as controlled synthetic benchmarks, demonstrating its effectiveness in improving training dynamics and robustness. Experimental results, together with supporting theoretical heuristics, indicate consistent improvements in training behavior across a range of settings, with no adverse effects observed otherwise. Our next step will be to extend this approach to language models.
### Title:
          N-gram-like Language Models Predict Reading Time Best
 - **Authors:** James A. Michaelov, Roger P. Levy
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent work has found that contemporary language models such as transformers can become so good at next-word prediction that the probabilities they calculate become worse for predicting reading time. In this paper, we propose that this can be explained by reading time being sensitive to simple n-gram statistics rather than the more complex statistics learned by state-of-the-art transformer language models. We demonstrate that the neural language models whose predictions are most correlated with n-gram probability are also those that calculate probabilities that are the most correlated with eye-tracking-based metrics of reading time on naturalistic text.
### Title:
          Fine-grained Motion Retrieval via Joint-Angle Motion Images and Token-Patch Late Interaction
 - **Authors:** Yao Zhang, Zhuchenyang Liu, Yanlan He, Thomas Ploetz, Yu Xiao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-motion retrieval aims to learn a semantically aligned latent space between natural language descriptions and 3D human motion skeleton sequences, enabling bidirectional search across the two modalities. Most existing methods use a dual-encoder framework that compresses motion and text into global embeddings, discarding fine-grained local correspondences, and thus reducing accuracy. Additionally, these global-embedding methods offer limited interpretability of the retrieval results. To overcome these limitations, we propose an interpretable, joint-angle-based motion representation that maps joint-level local features into a structured pseudo-image, compatible with pre-trained Vision Transformers. For text-to-motion retrieval, we employ MaxSim, a token-wise late interaction mechanism, and enhance it with Masked Language Modeling regularization to foster robust, interpretable text-motion alignment. Extensive experiments on HumanML3D and KIT-ML show that our method outperforms state-of-the-art text-motion retrieval approaches while offering interpretable fine-grained correspondences between text and motion. The code is available in the supplementary material.
### Title:
          PathMem: Toward Cognition-Aligned Memory Transformation for Pathology MLLMs
 - **Authors:** Jinyue Li, Yuci Liang, Qiankun Li, Xinheng Lyu, Jiayu Qian, Huabao Chen, Kun Wang, Zhigang Zeng, Anil Anthony Bharath, Yang Liu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Computational pathology demands both visual pattern recognition and dynamic integration of structured domain knowledge, including taxonomy, grading criteria, and clinical evidence. In practice, diagnostic reasoning requires linking morphological evidence with formal diagnostic and grading criteria. Although multimodal large language models (MLLMs) demonstrate strong vision language reasoning capabilities, they lack explicit mechanisms for structured knowledge integration and interpretable memory control. As a result, existing models struggle to consistently incorporate pathology-specific diagnostic standards during reasoning. Inspired by the hierarchical memory process of human pathologists, we propose PathMem, a memory-centric multimodal framework for pathology MLLMs. PathMem organizes structured pathology knowledge as a long-term memory (LTM) and introduces a Memory Transformer that models the dynamic transition from LTM to working memory (WM) through multimodal memory activation and context-aware knowledge grounding, enabling context-aware memory refinement for downstream reasoning. PathMem achieves SOTA performance across benchmarks, improving WSI-Bench report generation (12.8% WSI-Precision, 10.1% WSI-Relevance) and open-ended diagnosis by 9.7% and 8.9% over prior WSI-based models.
## Keyword: autonomous driving
### Title:
          Comparative Analysis of Patch Attack on VLM-Based Autonomous Driving Architectures
 - **Authors:** David Fernandez, Pedram MohajerAnsari, Amir Salarpour, Long Cheng, Abolfazl Razi, Mert D. Pesé
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language models are emerging for autonomous driving, yet their robustness to physical adversarial attacks remains unexplored. This paper presents a systematic framework for comparative adversarial evaluation across three VLM architectures: Dolphins, OmniDrive (Omni-L), and LeapVAD. Using black-box optimization with semantic homogenization for fair comparison, we evaluate physically realizable patch attacks in CARLA simulation. Results reveal severe vulnerabilities across all architectures, sustained multi-frame failures, and critical object detection degradation. Our analysis exposes distinct architectural vulnerability patterns, demonstrating that current VLM designs inadequately address adversarial threats in safety-critical autonomous driving applications.
### Title:
          Open-World Motion Forecasting
 - **Authors:** Nicolas Schischka, Nikhil Gosala, B Ravi Kiran, Senthil Yogamani, Abhinav Valada
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Motion forecasting aims to predict the future trajectories of dynamic agents in the scene, enabling autonomous vehicles to effectively reason about scene evolution. Existing approaches operate under the closed-world regime and assume fixed object taxonomy as well as access to high-quality perception. Therefore, they struggle in real-world settings where perception is imperfect and object taxonomy evolves over time. In this work, we bridge this fundamental gap by introducing open-world motion forecasting, a novel setting in which new object classes are sequentially introduced over time and future object trajectories are estimated directly from camera images. We tackle this setting by proposing the first end-to-end class-incremental motion forecasting framework to mitigate catastrophic forgetting while simultaneously learning to forecast newly introduced classes. When a new class is introduced, our framework employs a pseudo-labeling strategy to first generate motion forecasting pseudo-labels for all known classes which are then processed by a vision-language model to filter inconsistent and over-confident predictions. Parallelly, our approach further mitigates catastrophic forgetting by using a novel replay sampling strategy that leverages query feature variance to sample previous sequences with informative motion patterns. Extensive evaluation on the nuScenes and Argoverse 2 datasets demonstrates that our approach successfully resists catastrophic forgetting and maintains performance on previously learned classes while improving adaptation to novel ones. Further, we demonstrate that our approach supports zero-shot transfer to real-world driving and naturally extends to end-to-end class-incremental planning, enabling continual adaptation of the full autonomous driving system. We provide the code at this https URL .
### Title:
          Declarative Scenario-based Testing with RoadLogic
 - **Authors:** Ezio Bartocci, Alessio Gambi, Felix Gigler, Cristinel Mateis, Dejan Ničković
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI); Logic in Computer Science (cs.LO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scenario-based testing is a key method for cost-effective and safe validation of autonomous vehicles (AVs). Existing approaches rely on imperative scenario definitions, requiring developers to manually enumerate numerous variants to achieve coverage. Declarative languages, such as OpenSCENARIO DSL (OS2), raise the abstraction level but lack systematic methods for instantiating concrete, specification-compliant scenarios as simulations. To our knowledge, currently, no open-source solution provides this capability. We present RoadLogic that bridges declarative OS2 specifications and executable simulations. It uses Answer Set Programming to generate abstract plans satisfying scenario constraints, motion planning to refine the plans into feasible trajectories, and specification-based monitoring to verify correctness. We evaluate RoadLogic on instantiating representative OS2 scenarios as simulations in the CommonRoad framework. Results show that RoadLogic consistently produces realistic, specification-satisfying simulations within minutes and captures diverse behavioral variants through parameter sampling, thus opening the door to systematic scenario-based testing for autonomous driving systems.
### Title:
          EvoDriveVLA: Evolving Autonomous Driving Vision-Language-Action Model via Collaborative Perception-Planning Distillation
 - **Authors:** Jiajun Cao, Xiaoan Zhang, Xiaobao Wei, Liyuqiu Huang, Wang Zijian, Hanzhen Zhang, Zhengyu Jia, Wei Mao, Hao Wang, Xianming Liu, Shuchang Zhou Liu, Yang Wang, Shanghang Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action models have shown great promise for autonomous driving, yet they suffer from degraded perception after unfreezing the visual encoder and struggle with accumulated instability in long-term planning. To address these challenges, we propose EvoDriveVLA-a novel collaborative perception-planning distillation framework that integrates self-anchored perceptual constraints and oracle-guided trajectory optimization. Specifically, self-anchored visual distillation leverages self-anchor teacher to deliver visual anchoring constraints, regularizing student representations via trajectory-guided key-region awareness. In parallel, oracle-guided trajectory distillation employs a future-aware oracle teacher with coarse-to-fine trajectory refinement and Monte Carlo dropout sampling to produce high-quality trajectory candidates, thereby selecting the optimal trajectory to guide the student's prediction. EvoDriveVLA achieves SOTA performance in open-loop evaluation and significantly enhances performance in closed-loop evaluation. Our code is available at: this https URL.
### Title:
          StyleVLA: Driving Style-Aware Vision Language Action Model for Autonomous Driving
 - **Authors:** Yuan Gao, Dengyuan Hua, Mattia Piccinini, Finn Rasmus Schäfer, Korbinian Moller, Lin Li, Johannes Betz
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Language Models (VLMs) bridge visual perception and linguistic reasoning. In Autonomous Driving (AD), this synergy has enabled Vision Language Action (VLA) models, which translate high-level multimodal understanding into driving behaviors, typically represented as future trajectories. However, existing VLA models mainly generate generic collision-free trajectories. Beyond collision avoidance, adapting to diverse driving styles (e.g., sporty, comfortable) is essential for personalized driving. Moreover, many methods treat trajectory generation as naive token prediction, which can produce kinematically infeasible actions. To address these limitations, we present StyleVLA, a physics-informed VLA framework for generating diverse and physically plausible driving behaviors. We introduce a hybrid loss that combines a kinematic consistency constraint with a continuous regression head to improve trajectory feasibility. To train StyleVLA, built on Qwen3-VL-4B, we construct a large-scale instruction dataset with over 1.2k scenarios, 76k Bird's Eye View (BEV) samples, and 42k First Person View (FPV) samples, with ground-truth trajectories for five driving styles and natural-language instructions. Experiments show that our 4B-parameter StyleVLA significantly outperforms proprietary models (e.g., Gemini-3-Pro) and state-of-the-art VLA models. Using a composite driving score measuring success rate, physical feasibility, and style adherence, StyleVLA achieves 0.55 on BEV and 0.51 on FPV, versus 0.32 and 0.35 for Gemini-3-Pro. These results show that a specialized, physics-informed, lightweight model can surpass closed-source models on domain-specific tasks.
### Title:
          Probing the Reliability of Driving VLMs: From Inconsistent Responses to Grounded Temporal Reasoning
 - **Authors:** Chun-Peng Chang, Chen-Yu Wang, Holger Caesar, Alain Pagani
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A reliable driving assistant should provide consistent responses based on temporally grounded reasoning derived from observed information. In this work, we investigate whether Vision-Language Models (VLMs), when applied as driving assistants, can response consistantly and understand how present observations shape future outcomes, or whether their outputs merely reflect patterns memorized during training without temporally grounded reasoning. While recent efforts have integrated VLMs into autonomous driving, prior studies typically emphasize scene understanding and instruction generation, implicitly assuming that strong visual interpretation naturally enables consistant future reasoning and thus ensures reliable decision-making, a claim we critically examine. We focus on two major challenges limiting VLM reliability in this setting: response inconsistency, where minor input perturbations yield different answers or, in some cases, responses degenerate toward near-random guessing, and limited temporal reasoning, in which models fail to reason and align sequential events from current observations, often resulting in incorrect or even contradictory responses. Moreover, we find that models with strong visual understanding do not necessarily perform best on tasks requiring temporal reasoning, indicating a tendency to over-rely on pretrained patterns rather than modeling temporal dynamics. To address these issues, we adopt existing evaluation methods and introduce FutureVQA, a human-annotated benchmark dataset specifically designed to assess future scene reasoning. In addition, we propose a simple yet effective self-supervised tuning approach with chain-of-thought reasoning that improves both consistency and temporal reasoning without requiring temporal labels.
### Title:
          RESBev: Making BEV Perception More Robust
 - **Authors:** Lifeng Zhuo, Kefan Jin, Zhe Liu, Hesheng Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bird's-eye-view (BEV) perception has emerged as a cornerstone of autonomous driving systems, providing a structured, ego-centric representation critical for downstream planning and control. However, real-world deployment faces challenges from sensor degradation and adversarial attacks, which can cause severe perceptual anomalies and ultimately compromise the safety of autonomous driving systems. To address this, we propose a resilient and plug-and-play BEV perception method, RESBev, which can be easily applied to existing BEV perception methods to enhance their robustness to diverse disturbances. Specifically, we reframe perception robustness as a latent semantic prediction problem. A latent world model is constructed to extract spatiotemporal correlations across sequential BEV observations, thereby learning the underlying BEV state transitions to predict clean BEV features for reconstructing corrupted observations. The proposed framework operates at the semantic feature level of the Lift-Splat-Shoot pipeline, enabling recovery that generalizes across both natural disturbances and adversarial attacks without modifying the underlying backbone. Extensive experiments on the nuScenes dataset demonstrate that, with few-shot fine-tuning, RESBev significantly improves the robustness of existing BEV perception models against various external disturbances and adversarial attacks.
### Title:
          $M^2$-Occ: Resilient 3D Semantic Occupancy Prediction for Autonomous Driving with Incomplete Camera Inputs
 - **Authors:** Kaixin Lin, Kunyu Peng, Di Wen, Yufan Chen, Ruiping Liu, Kailun Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic occupancy prediction enables dense 3D geometric and semantic understanding for autonomous driving. However, existing camera-based approaches implicitly assume complete surround-view observations, an assumption that rarely holds in real-world deployment due to occlusion, hardware malfunction, or communication failures. We study semantic occupancy prediction under incomplete multi-camera inputs and introduce $M^2$-Occ, a framework designed to preserve geometric structure and semantic coherence when views are missing. $M^2$-Occ addresses two complementary challenges. First, a Multi-view Masked Reconstruction (MMR) module leverages the spatial overlap among neighboring cameras to recover missing-view representations directly in the feature space. Second, a Feature Memory Module (FMM) introduces a learnable memory bank that stores class-level semantic prototypes. By retrieving and integrating these global priors, the FMM refines ambiguous voxel features, ensuring semantic consistency even when observational evidence is incomplete. We introduce a systematic missing-view evaluation protocol on the nuScenes-based SurroundOcc benchmark, encompassing both deterministic single-view failures and stochastic multi-view dropout scenarios. Under the safety-critical missing back-view setting, $M^2$-Occ improves the IoU by 4.93%. As the number of missing cameras increases, the robustness gap further widens; for instance, under the setting with five missing views, our method boosts the IoU by 5.01%. These gains are achieved without compromising full-view performance. The source code will be publicly released at this https URL.
