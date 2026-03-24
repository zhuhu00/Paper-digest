# Showing new listings for Tuesday, 24 March 2026
## Keyword: SLAM
### Title:
          TRGS-SLAM: IMU-Aided Gaussian Splatting SLAM for Blurry, Rolling Shutter, and Noisy Thermal Images
 - **Authors:** Spencer Carmichael, Katherine A. Skinner
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Thermal cameras offer several advantages for simultaneous localization and mapping (SLAM) with mobile robots: they provide a passive, low-power solution to operating in darkness, are invariant to rapidly changing or high dynamic range illumination, and can see through fog, dust, and smoke. However, uncooled microbolometer thermal cameras, the only practical option in most robotics applications, suffer from significant motion blur, rolling shutter distortions, and fixed pattern noise. In this paper, we present TRGS-SLAM, a 3D Gaussian Splatting (3DGS) based thermal inertial SLAM system uniquely capable of handling these degradations. To overcome the challenges of thermal data, we introduce a model-aware 3DGS rendering method and several general innovations to 3DGS SLAM, including B-spline trajectory optimization with a two-stage IMU loss, view-diversity-based opacity resetting, and pose drift correction schemes. Our system demonstrates accurate tracking on real-world, fast motion, and high-noise thermal data that causes all other tested SLAM methods to fail. Moreover, through offline refinement of our SLAM results, we demonstrate thermal image restoration competitive with prior work that required ground truth poses.
### Title:
          ToFormer: Towards Large-scale Scenario Depth Completion for Lightweight ToF Camera
 - **Authors:** Juncheng Chen, Tiancheng Lai, Xingpeng Wang, Bingxin Liao, Baozhe Zhang, Chao Xu, Yanjun Cao
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Time-of-Flight (ToF) cameras possess compact design and high measurement precision to be applied to various robot tasks. However, their limited sensing range restricts deployment in large-scale scenarios. Depth completion has emerged as a potential solution to expand the sensing range of ToF cameras, but existing research lacks dedicated datasets and struggles to generalize to ToF measurements. In this paper, we propose a full-stack framework that enables depth completion in large-scale scenarios for short-range ToF cameras. First, we construct a multi-sensor platform with a reconstruction-based pipeline to collect real-world ToF samples with dense large-scale ground truth, yielding the first LArge-ScalE scenaRio ToF depth completion dataset (LASER-ToF). Second, we propose a sensor-aware depth completion network that incorporates a novel 3D branch with a 3D-2D Joint Propagation Pooling (JPP) module and Multimodal Cross-Covariance Attention (MXCA), enabling effective modeling of long-range relationships and efficient 3D-2D fusion under non-uniform ToF depth sparsity. Moreover, our network can utilize the sparse point cloud from visual SLAM as a supplement to ToF depth to further improve prediction accuracy. Experiments show that our method achieves an 8.6% lower mean absolute error than the second-best method, while maintaining lightweight design to support onboard deployment. Finally, to verify the system's applicability on real robots, we deploy proposed method on a quadrotor at a 10Hz runtime, enabling reliable large-scale mapping and long-range planning in challenging environments for short-range ToF cameras.
### Title:
          Implementing Robust M-Estimators with Certifiable Factor Graph Optimization
 - **Authors:** Zhexin Xu, Hanna Jiamei Zhang, Helena Calatrava, Pau Closas, David M. Rosen
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Parameter estimation in robotics and computer vision faces formidable challenges from both outlier contamination and nonconvex optimization landscapes. While M-estimation addresses the problem of outliers through robust loss functions, it creates severely nonconvex problems that are difficult to solve globally. Adaptive reweighting schemes provide one particularly appealing strategy for implementing M-estimation in practice: these methods solve a sequence of simpler weighted least squares (WLS) subproblems, enabling both the use of standard least squares solvers and the recovery of higher-quality estimates than simple local search. However, adaptive reweighting still crucially relies upon solving the inner WLS problems effectively, a task that remains challenging in many robotics applications due to the intrinsic nonconvexity of many common parameter spaces (e.g. rotations and poses). In this paper, we show how one can easily implement adaptively reweighted M-estimators with certifiably correct solvers for the inner WLS subproblems using only fast local optimization over smooth manifolds. Our approach exploits recent work on certifiable factor graph optimization to provide global optimality certificates for the inner WLS subproblems while seamlessly integrating into existing factor graph-based software libraries and workflows. Experimental evaluation on pose-graph optimization and landmark SLAM tasks demonstrates that our adaptively reweighted certifiable estimation approach provides higher-quality estimates than alternative local search-based methods, while scaling tractably to realistic problem sizes.
### Title:
          SGAD-SLAM: Splatting Gaussians at Adjusted Depth for Better Radiance Fields in RGBD SLAM
 - **Authors:** Pengchong Hu, Zhizhong Han
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian Splatting (3DGS) has made remarkable progress in RGBD SLAM. Current methods usually use 3D Gaussians or view-tied 3D Gaussians to represent radiance fields in tracking and mapping. However, these Gaussians are either too flexible or too limited in movements, resulting in slow convergence or limited rendering quality. To resolve this issue, we adopt pixel-aligned Gaussians but allow each Gaussian to adjust its position along its ray to maximize the rendering quality, even if Gaussians are simplified to improve system scalability. To speed up the tracking, we model the depth distribution around each pixel as a Gaussian distribution, and then use these distributions to align each frame to the 3D scene quickly. We report our evaluations on widely used benchmarks, justify our designs, and show advantages over the latest methods in view rendering, camera tracking, runtime, and storage complexity. Please see our project page for code and videos at this https URL .
## Keyword: odometry
### Title:
          PiLoT: Neural Pixel-to-3D Registration for UAV-based Ego and Target Geo-localization
 - **Authors:** Xiaoya Cheng, Long Wang, Yan Liu, Xinyi Liu, Hanlin Tan, Yu Liu, Maojun Zhang, Shen Yan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present PiLoT, a unified framework that tackles UAV-based ego and target geo-localization. Conventional approaches rely on decoupled pipelines that fuse GNSS and Visual-Inertial Odometry (VIO) for ego-pose estimation, and active sensors like laser rangefinders for target localization. However, these methods are susceptible to failure in GNSS-denied environments and incur substantial hardware costs and complexity. PiLoT breaks this paradigm by directly registering live video stream against a geo-referenced 3D map. To achieve robust, accurate, and real-time performance, we introduce three key contributions: 1) a Dual-Thread Engine that decouples map rendering from core localization thread, ensuring both low latency while maintaining drift-free accuracy; 2) a large-scale synthetic dataset with precise geometric annotations (camera pose, depth maps). This dataset enables the training of a lightweight network that generalizes in a zero-shot manner from simulation to real data; and 3) a Joint Neural-Guided Stochastic-Gradient Optimizer (JNGO) that achieves robust convergence even under aggressive motion. Evaluations on a comprehensive set of public and newly collected benchmarks show that PiLoT outperforms state-of-the-art methods while running over 25 FPS on NVIDIA Jetson Orin platform. Our code and dataset is available at: this https URL.
### Title:
          Image-Conditioned Adaptive Parameter Tuning for Visual Odometry Frontends
 - **Authors:** Simone Nascivera, Leonard Bauersfeld, Jeff Delaune, Davide Scaramuzza
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Resource-constrained autonomous robots rely on sparse direct and semi-direct visual-(inertial)-odometry (VO) pipelines, as they provide a favorable tradeoff between accuracy, robustness, and computational cost. However, the performance of most systems depends critically on hand-tuned hyperparameters governing feature detection, tracking, and outlier rejection. These parameters are typically fixed during deployment, even though their optimal values vary with scene characteristics such as texture density, illumination, motion blur, and sensor noise, leading to brittle performance in real-world environments. We propose the first image-conditioned reinforcement learning framework for online tuning of VO frontend parameters, effectively embedding the expert into the system. Our key idea is to formulate the frontend configuration as a sequential decision-making problem and learn a policy that directly maps visual input to feature detection and tracking parameters. The policy uses a lightweight texture-aware CNN encoder and a privileged critic during training. Unlike prior RL-based approaches that rely solely on internal VO statistics, our method observes the image content and proactively adapts parameters before tracking degrades. Experiments on TartanAirV2 and TUM RGB-D show 3x longer feature tracks and 3x lower computational cost, despite training entirely in simulation.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Scene Representation using 360° Saliency Graph and its Application in Vision-based Indoor Navigation
 - **Authors:** Preeti Meena, Himanshu Kumar, Sandeep Yadav
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO); Image and Video Processing (eess.IV); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A Scene, represented visually using different formats such as RGB-D, LiDAR scan, keypoints, rectangular, spherical, multi-views, etc., contains information implicitly embedded relevant to applications such as scene indexing, vision-based navigation. Thus, these representations may not be efficient for such applications. This paper proposes a novel 360° saliency graph representation of the scenes. This rich representation explicitly encodes the relevant visual, contextual, semantic, and geometric information of the scene as nodes, edges, edge weights, and angular position in the 360° graph. Also, this representation is robust against scene view change and addresses challenges of indoor environments such as varied illumination, occlusions, and shadows as in the case of existing traditional methods. We have utilized this rich and efficient representation for vision-based navigation and compared it with existing navigation methods using 360° scenes. However, these existing methods suffer from limitations of poor scene representation, lacking scene-specific information. This work utilizes the proposed representation first to localize the query scene in the given topological map, and then facilitate 2D navigation by estimating the next required movement directions towards the target destination in the topological map by using the embedded geometric information in the 360° saliency graph. Experimental results demonstrate the efficacy of the proposed 360° saliency graph representation in enhancing both scene localization and vision-based indoor navigation.
### Title:
          LRC-WeatherNet: LiDAR, RADAR, and Camera Fusion Network for Real-time Weather-type Classification in Autonomous Driving
 - **Authors:** Nour Alhuda Albashir, Lars Pernickel, Danial Hamoud, Idriss Gouigah, Eren Erdal Aksoy
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous vehicles face major perception and navigation challenges in adverse weather such as rain, fog, and snow, which degrade the performance of LiDAR, RADAR, and RGB camera sensors. While each sensor type offers unique strengths, such as RADAR robustness in poor visibility and LiDAR precision in clear conditions, they also suffer distinct limitations when exposed to environmental obstructions. This study proposes LRC-WeatherNet, a novel multi-sensor fusion framework that integrates LiDAR, RADAR, and camera data for real-time classification of weather conditions. By employing both early fusion using a unified Bird's Eye View representation and mid-level gated fusion of modality-specific feature maps, our approach adapts to the varying reliability of each sensor under changing weather. Evaluated on the extensive MSU-4S dataset covering nine weather types, LRC-WeatherNet achieves superior classification performance and computational efficiency, significantly outperforming unimodal baselines in adverse conditions. This work is the first to combine all three modalities for robust, real-time weather classification in autonomous driving. We release our trained models and source code in this https URL.
### Title:
          MEVIUS2: Practical Open-Source Quadruped Robot with Sheet Metal Welding and Multimodal Perception
 - **Authors:** Kento Kawaharazuka, Keita Yoneda, Shintaro Inoue, Temma Suzuki, Jun Oda, Kei Okada
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Various quadruped robots have been developed to date, and thanks to reinforcement learning, they are now capable of traversing diverse types of rough terrain. In parallel, there is a growing trend of releasing these robot designs as open-source, enabling researchers to freely build and modify robots themselves. However, most existing open-source quadruped robots have been designed with 3D printing in mind, resulting in structurally fragile systems that do not scale well in size, leading to the construction of relatively small robots. Although a few open-source quadruped robots constructed with metal components exist, they still tend to be small in size and lack multimodal sensors for perception, making them less practical. In this study, we developed MEVIUS2, an open-source quadruped robot with a size comparable to Boston Dynamics' Spot, whose structural components can all be ordered through e-commerce services. By leveraging sheet metal welding and metal machining, we achieved a large, highly durable body structure while reducing the number of individual parts. Furthermore, by integrating sensors such as LiDARs and a high dynamic range camera, the robot is capable of detailed perception of its surroundings, making it more practical than previous open-source quadruped robots. We experimentally validated that MEVIUS2 can traverse various types of rough terrain and demonstrated its environmental perception capabilities. All hardware, software, and training environments can be obtained from Supplementary Materials or this https URL.
### Title:
          Benchmarking Deep Learning Models for Aerial LiDAR Point Cloud Semantic Segmentation under Real Acquisition Conditions: A Case Study in Navarre
 - **Authors:** Alex Salvatierra, José Antonio Sanz, Christian Gutiérrez, Mikel Galar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in deep learning have significantly improved 3D semantic segmentation, but most models focus on indoor or terrestrial datasets. Their behavior under real aerial acquisition conditions remains insufficiently explored, and although a few studies have addressed similar scenarios, they differ in dataset design, acquisition conditions, and model selection. To address this gap, we conduct an experimental benchmark evaluating several state-of-the-art architectures on a large-scale aerial LiDAR dataset acquired under operational flight conditions in Navarre, Spain, covering heterogeneous urban, rural, and industrial landscapes. This study compares four representative deep learning models, including KPConv, RandLA-Net, Superpoint Transformer, and Point Transformer V3, across five semantic classes commonly found in airborne surveys, such as ground, vegetation, buildings, and vehicles, highlighting the inherent challenges of class imbalance and geometric variability in aerial data. Results show that all tested models achieve high overall accuracy exceeding 93%, with KPConv attaining the highest mean IoU (78.51%) through consistent performance across classes, particularly on challenging and underrepresented categories. Point Transformer V3 demonstrates superior performance on the underrepresented vehicle class (75.11% IoU), while Superpoint Transformer and RandLA-Net trade off segmentation robustness for computational efficiency.
### Title:
          Riverine Land Cover Mapping through Semantic Segmentation of Multispectral Point Clouds
 - **Authors:** Sopitta Thurachen, Josef Taher, Matti Lehtomäki, Leena Matikainen, Linnea Blåfield, Mikel Calle Navarro, Antero Kukko, Tomi Westerlund, Harri Kaartinen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate land cover mapping in riverine environments is essential for effective river management, ecological understanding, and geomorphic change monitoring. This study explores the use of Point Transformer v2 (PTv2), an advanced deep neural network architecture designed for point cloud data, for land cover mapping through semantic segmentation of multispectral LiDAR data in real-world riverine environments. We utilize the geometric and spectral information from the 3-channel LiDAR point cloud to map land cover classes, including sand, gravel, low vegetation, high vegetation, forest floor, and water. The PTv2 model was trained and evaluated on point cloud data from the Oulanka river in northern Finland using both geometry and spectral features. To improve the model's generalization in new riverine environments, we additionally investigate multi-dataset training that adds sparsely annotated data from an additional river dataset. Results demonstrated that using the full-feature configuration resulted in performance with a mean Intersection over Union (mIoU) of 0.950, significantly outperforming the geometry baseline. Other ablation studies revealed that intensity and reflectance features were the key for accurate land cover mapping. The multi-dataset training experiment showed improved generalization performance, suggesting potential for developing more robust models despite limited high-quality annotated data. Our work demonstrates the potential of applying transformer-based architectures to multispectral point clouds in riverine environments. The approach offers new capabilities for monitoring sediment transport and other river management applications.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          Benchmarking Efficient & Effective Camera Pose Estimation Strategies for Novel View Synthesis
 - **Authors:** Jhacson Meza, Martin R. Oswald, Torsten Sattler
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Novel view synthesis (NVS) approaches such as NeRFs or 3DGS can produce photo-realistic 3D scene representation from a set of images with known extrinsic and intrinsic parameters. The necessary camera poses and calibrations are typically obtained from the images via Structure-from-Motion (SfM). Classical SfM approaches rely on local feature matches between the images to estimate both the poses and a sparse 3D model of the scene, using bundle adjustment to refine initial pose, intrinsics, and geometry estimates. In order to increase run-time efficiency, recent SfM systems forgo optimization via bundle adjustment. Instead, they train feed-forward (transformer-based) neural networks to directly regress camera parameters and the 3D structure. While orders of magnitude more efficient, such recent works produce significantly less accurate estimates. To stimulate research on developing SfM approaches that are both efficient \emph{and} effective, this paper develops a benchmark focused on SfM for novel view synthesis. Using existing datasets and two simple strategies for making the reconstruction process more efficient, we show that: (1) simply using fewer features already significantly accelerates classical SfM methods while maintaining high pose accuracy. (2) using feed-forward networks to obtain initial estimates and refining them using classical SfM techniques leads to the best efficiency-effectiveness trade-off. We will make our benchmark and code publicly available.
### Title:
          GaussianPile: A Unified Sparse Gaussian Splatting Framework for Slice-based Volumetric Reconstruction
 - **Authors:** Di Kong, Yikai Wang, Wenjie Guo, Yifan Bu, Boya Zhang, Yuexin Duan, Xiawei Yue, Wenbiao Du, Yiman Zhong, Yuwen Chen, Cheng Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Slice-based volumetric imaging is widely applied and it demands representations that compress aggressively while preserving internal structure for analysis. We introduce GaussianPile, unifying 3D Gaussian splatting with an imaging system-aware focus model to address this challenge. Our proposed method introduces three key innovations: (i) a slice-aware piling strategy that positions anisotropic 3D Gaussians to model through-slice contributions, (ii) a differentiable projection operator that encodes the finite-thickness point spread function of the imaging acquisition system, and (iii) a compact encoding and joint optimization pipeline that simultaneously reconstructs and compresses the Gaussian sets. Our CUDA-based design retains the compression and real-time rendering efficiency of Gaussian primitives while preserving high-frequency internal volumetric detail. Experiments on microscopy and ultrasound datasets demonstrate that our method reduces storage and reconstruction cost, sustains diagnostic fidelity, and enables fast 2D visualization, along with 3D voxelization. In practice, it delivers high-quality results in as few as 3 minutes, up to 11x faster than NeRF-based approaches, and achieves consistent 16x compression over voxel grids, offering a practical path to deployable compression and exploration of slice-based volumetric datasets.
### Title:
          EmoTaG: Emotion-Aware Talking Head Synthesis on Gaussian Splatting with Few-Shot Personalization
 - **Authors:** Haolan Xu, Keli Cheng, Lei Wang, Ning Bi, Xiaoming Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Audio-driven 3D talking head synthesis has advanced rapidly with Neural Radiance Fields (NeRF) and 3D Gaussian Splatting (3DGS). By leveraging rich pre-trained priors, few-shot methods enable instant personalization from just a few seconds of video. However, under expressive facial motion, existing few-shot approaches often suffer from geometric instability and audio-emotion mismatch, highlighting the need for more effective emotion-aware motion modeling. In this work, we present EmoTaG, a few-shot emotion-aware 3D talking head synthesis framework built on the Pretrain-and-Adapt paradigm. Our key insight is to reformulate motion prediction in a structured FLAME parameter space rather than directly deforming 3D Gaussians, thereby introducing explicit geometric priors that improve motion stability. Building upon this, we propose a Gated Residual Motion Network (GRMN), which captures emotional prosody from audio while supplementing head pose and upper-face cues absent from audio, enabling expressive and coherent motion generation. Extensive experiments demonstrate that EmoTaG achieves state-of-the-art performance in emotional expressiveness, lip synchronization, visual realism, and motion stability.
### Title:
          FluidGaussian: Propagating Simulation-Based Uncertainty Toward Functionally-Intelligent 3D Reconstruction
 - **Authors:** Yuqiu Liu, Jialin Song, Marissa Ramirez de Chanlatte, Rochishnu Chowdhury, Rushil Paresh Desai, Wuyang Chen, Daniel Martin, Michael Mahoney
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real objects that inhabit the physical world follow physical laws and thus behave plausibly during interaction with other physical objects. However, current methods that perform 3D reconstructions of real-world scenes from multi-view 2D images optimize primarily for visual fidelity, i.e., they train with photometric losses and reason about uncertainty in the image or representation space. This appearance-centric view overlooks body contacts and couplings, conflates function-critical regions (e.g., aerodynamic or hydrodynamic surfaces) with ornamentation, and reconstructs structures suboptimally, even when physical regularizers are added. All these can lead to unphysical and implausible interactions. To address this, we consider the question: How can 3D reconstruction become aware of real-world interactions and underlying object functionality, beyond visual cues? To answer this question, we propose FluidGaussian, a plug-and-play method that tightly couples geometry reconstruction with ubiquitous fluid-structure interactions to assess surface quality at high granularity. We define a simulation-based uncertainty metric induced by fluid simulations and integrate it with active learning to prioritize views that improve both visual and physical fidelity. In an empirical evaluation on NeRF Synthetic (Blender), Mip-NeRF 360, and DrivAerNet++, our FluidGaussian method yields up to +8.6% visual PSNR (Peak Signal-to-Noise Ratio) and -62.3% velocity divergence during fluid simulations. Our code is available at this https URL.
### Title:
          RefracGS: Novel View Synthesis Through Refractive Water Surfaces with 3D Gaussian Ray Tracing
 - **Authors:** Yiming Shao, Qiyu Dai, Chong Gao, Guanbin Li, Yeqiang Wang, He Sun, Qiong Zeng, Baoquan Chen, Wenzheng Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Novel view synthesis (NVS) through non-planar refractive surfaces presents fundamental challenges due to severe, spatially varying optical distortions. While recent representations like NeRF and 3D Gaussian Splatting (3DGS) excel at NVS, their assumption of straight-line ray propagation fails under these conditions, leading to significant artifacts. To overcome this limitation, we introduce RefracGS, a framework that jointly reconstructs the refractive water surface and the scene beneath the interface. Our key insight is to explicitly decouple the refractive boundary from the target objects: the refractive surface is modeled via a neural height field, capturing wave geometry, while the underlying scene is represented as a 3D Gaussian field. We formulate a refraction-aware Gaussian ray tracing approach that accurately computes non-linear ray trajectories using Snell's law and efficiently renders the underlying Gaussian field while backpropagating the loss gradients to the parameterized refractive surface. Through end-to-end joint optimization of both representations, our method ensures high-fidelity NVS and view-consistent surface recovery. Experiments on both synthetic and real-world scenes with complex waves demonstrate that RefracGS outperforms prior refractive methods in visual quality, while achieving 15x faster training and real-time rendering at 200 FPS. The project page for RefracGS is available at this https URL.
### Title:
          SatGeo-NeRF: Geometrically Regularized NeRF for Satellite Imagery
 - **Authors:** Valentin Wagner, Sebastian Bullinger, Michael Arens, Rainer Stiefelhagen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present SatGeo-NeRF, a geometrically regularized NeRF for satellite imagery that mitigates overfitting-induced geometric artifacts observed in current state-of-the-art models using three model-agnostic regularizers. Gravity-Aligned Planarity Regularization aligns depth-inferred, approximated surface normals with the gravity axis to promote local planarity, coupling adjacent rays via a corresponding surface approximation to facilitate cross-ray gradient flow. Granularity Regularization enforces a coarse-to-fine geometry-learning scheme, and Depth-Supervised Regularization stabilizes early training for improved geometric accuracy. On the DFC2019 satellite reconstruction benchmark, SatGeo-NeRF improves the Mean Altitude Error by 13.9% and 11.7% relative to state-of-the-art baselines such as EO-NeRF and EO-GS.
## Keyword: mapping
### Title:
          Measuring Research Convergence in Interdisciplinary Teams Using Large Language Models and Graph Analytics
 - **Authors:** Wenwen Li, Yuanyuan Tian, Sizhe Wang, Amber Wutich, Paul Westerhoff, Sarah Porter, Anais Roque, Jobayer Hossain, Patrick Thomson, Rhett Larson, Michael Hanemann
 - **Subjects:** Subjects:
Computers and Society (cs.CY); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding how interdisciplinary research teams converge on shared knowledge is a persistent challenge. This paper presents a novel, multi-layer, AI-driven analytical framework for mapping research convergence in interdisciplinary teams. The framework integrates large language models (LLMs), graph-based visualization and analytics, and human-in-the-loop evaluation to examine how research viewpoints are shared, influenced, and integrated over time. LLMs are used to extract structured viewpoints aligned with the \emph{Needs-Approach-Benefits-Competition (NABC)} framework and to infer potential viewpoint flows across presenters, forming a common semantic foundation for three complementary analyses: (1) similarity-based qualitative analysis to identify two key types of viewpoints, popular and unique, for building convergence, (2) quantitative cross-domain influence analysis using network centrality measures, and (3) temporal viewpoint flow analysis to capture convergence dynamics. To address uncertainty in LLM-based inference, the framework incorporates expert validation through structured surveys and cross-layer consistency checks. A case study on water insecurity in underserved communities as part of the Arizona Water Innovation Initiatives demonstrates increasing viewpoint convergence and domain-specific influence patterns, illustrating the value of the proposed AI-enabled approach for research convergence analysis.
### Title:
          ProMAS: Proactive Error Forecasting for Multi-Agent Systems Using Markov Transition Dynamics
 - **Authors:** Xinkui Zhao, Sai Liu, Yifan Zhang, Qingyu Ma, Guanjie Cheng, Naibo Wang, Chang Liu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The integration of Large Language Models into Multi-Agent Systems (MAS) has enabled the so-lution of complex, long-horizon tasks through collaborative reasoning. However, this collec-tive intelligence is inherently fragile, as a single logical fallacy can rapidly propagate and lead to system-wide failure. Most current research re-lies on post-hoc failure analysis, thereby hinder-ing real-time intervention. To address this, we propose PROMAS, a proactive framework utiliz-ing Markov transitions for predictive error anal-ysis. PROMAS extracts Causal Delta Features to capture semantic displacement, mapping them to a quantized Vector Markov Space to model reasoning as probabilistic transitions. By inte-grating a Proactive Prediction Head with Jump Detection, the method localizes errors via risk acceleration rather than static thresholds. On the Who&When benchmark, PROMAS achieves 22.97% step-level accuracy while processing only 27% of reasoning logs. This performance rivals reactive monitors like MASC while reducing data overhead by 73%. Although this strategy entails an accuracy trade-off compared to post-hoc meth-ods, it significantly improves intervention latency, balancing diagnostic precision with the real-time demands of autonomous reasoning.
### Title:
          The Global-Local loop: what is missing in bridging the gap between geospatial data from numerous communities?
 - **Authors:** Clément Mallet, Ana-Maria Raimond
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We face a unprecedented amount of geospatial data, describing directly or indirectly the Earth Surface at multiple spatial, temporal, and semantic scales, and stemming from numerous contributors, from satellites to citizens. The main challenge in all the geospatial-related communities lies in suitably leveraging a combination of some of the sources for either a generic or a thematic application. Certain data fusion schemes are predominantly exploited: they correspond to popular tasks with mainstream data sources, e.g., free archives of Sentinel images coupled with OpenStreetMap data under an open and widespread deep-learning backbone for land-cover mapping purposes. Most of these approaches unfortunately operate under a "master-slave" paradigm, where one source is basically integrated to help processing the "main" source, without mutual advantages (e.g., large-scale estimation of a given biophysical variable using in-situ observations) and under a specific community bias. We argue that numerous key data fusion configurations, and in particular the effort in symmetrizing the exploitation of multiple data sources, are insufficiently addressed while being highly beneficial for generic or thematic applications. Bridges and retroactions between scales, communities and their respective sources are lacking, neglecting the utmost potential of such a "global-local loop". In this paper, we propose to establish the most relevant interaction schemes through illustrative use cases. We subsequently discuss under-explored research directions that could take advantage of leveraging available data through multiples extents and communities.
### Title:
          Bounded Coupled AI Learning Dynamics in Tri-Hierarchical Drone Swarms
 - **Authors:** Oleksii Bychkov
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern autonomous multi-agent systems combine heterogeneous learning mechanisms operating at different timescales. An open question remains: can one formally guarantee that coupled dynamics of such mechanisms stay within the admissible operational regime? This paper studies a tri-hierarchical swarm learning system where three mechanisms act simultaneously: (1) local Hebbian online learning at individual agent level (fast timescale, 10-100 ms); (2) multi-agent reinforcement learning (MARL) for tactical group coordination (medium timescale, 1-10 s); (3) meta-learning (MAML) for strategic adaptation (slow timescale, 10-100 s). Four results are established. The Bounded Total Error Theorem shows that under contractual constraints on learning rates, Lipschitz continuity of inter-level mappings, and weight stabilization, total suboptimality admits a component-wise upper bound uniform in time. The Bounded Representation Drift Theorem gives a worst-case estimate of how Hebbian updates affect coordination-level embeddings during one MARL cycle. The Meta-Level Compatibility Theorem provides sufficient conditions under which strategic adaptation preserves lower-level invariants. The Non-Accumulation Theorem proves that error does not grow unboundedly over time.
### Title:
          TRGS-SLAM: IMU-Aided Gaussian Splatting SLAM for Blurry, Rolling Shutter, and Noisy Thermal Images
 - **Authors:** Spencer Carmichael, Katherine A. Skinner
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Thermal cameras offer several advantages for simultaneous localization and mapping (SLAM) with mobile robots: they provide a passive, low-power solution to operating in darkness, are invariant to rapidly changing or high dynamic range illumination, and can see through fog, dust, and smoke. However, uncooled microbolometer thermal cameras, the only practical option in most robotics applications, suffer from significant motion blur, rolling shutter distortions, and fixed pattern noise. In this paper, we present TRGS-SLAM, a 3D Gaussian Splatting (3DGS) based thermal inertial SLAM system uniquely capable of handling these degradations. To overcome the challenges of thermal data, we introduce a model-aware 3DGS rendering method and several general innovations to 3DGS SLAM, including B-spline trajectory optimization with a two-stage IMU loss, view-diversity-based opacity resetting, and pose drift correction schemes. Our system demonstrates accurate tracking on real-world, fast motion, and high-noise thermal data that causes all other tested SLAM methods to fail. Moreover, through offline refinement of our SLAM results, we demonstrate thermal image restoration competitive with prior work that required ground truth poses.
### Title:
          Inverting Neural Networks: New Methods to Generate Neural Network Inputs from Prescribed Outputs
 - **Authors:** Rebecca Pattichis, Sebastian Janampa, Constantinos S. Pattichis, Marios S. Pattichis
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural network systems describe complex mappings that can be very difficult to understand. In this paper, we study the inverse problem of determining the input images that get mapped to specific neural network classes. Ultimately, we expect that these images contain recognizable features that are associated with their corresponding class classifications. We introduce two general methods for solving the inverse problem. In our forward pass method, we develop an inverse method based on a root-finding algorithm and the Jacobian with respect to the input image. In our backward pass method, we iteratively invert each layer, at the top. During the inversion process, we add random vectors sampled from the null-space of each linear layer. We demonstrate our new methods on both transformer architectures and sequential networks based on linear layers. Unlike previous methods, we show that our new methods are able to produce random-like input images that yield near perfect classification scores in all cases, revealing vulnerabilities in the underlying networks. Hence, we conclude that the proposed methods provide a more comprehensive coverage of the input image spaces that solve the inverse mapping problem.
### Title:
          Memory Over Maps: 3D Object Localization Without Reconstruction
 - **Authors:** Rui Zhou, Xander Yap, Jianwen Cao, Allison Lau, Boyang Sun, Marc Pollefeys
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Target localization is a prerequisite for embodied tasks such as navigation and manipulation. Conventional approaches rely on constructing explicit 3D scene representations to enable target localization, such as point clouds, voxel grids, or scene graphs. While effective, these pipelines incur substantial mapping time, storage overhead, and scalability limitations. Recent advances in vision-language models suggest that rich semantic reasoning can be performed directly on 2D observations, raising a fundamental question: is a complete 3D scene reconstruction necessary for object localization? In this work, we revisit object localization and propose a map-free pipeline that stores only posed RGB-D keyframes as a lightweight visual memory--without constructing any global 3D representation of the scene. At query time, our method retrieves candidate views, re-ranks them with a vision-language model, and constructs a sparse, on-demand 3D estimate of the queried target through depth backprojection and multi-view fusion. Compared to reconstruction-based pipelines, this design drastically reduces preprocessing cost, enabling scene indexing that is over two orders of magnitude faster to build while using substantially less storage. We further validate the localized targets on downstream object-goal navigation tasks. Despite requiring no task-specific training, our approach achieves strong performance across multiple benchmarks, demonstrating that direct reasoning over image-based scene memory can effectively replace dense 3D reconstruction for object-centric robot navigation. Project page: this https URL
### Title:
          Epistemic Observability in Language Models
 - **Authors:** Tony Mason
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We find that models report highest confidence precisely when they are fabricating. Across four model families (OLMo-3, Llama-3.1, Qwen3, Mistral), self-reported confidence inversely correlates with accuracy, with AUC ranging from 0.28 to 0.36 where 0.5 is random guessing. We prove, under explicit formal assumptions, that this is not a capability gap but an observational one. Under text-only observation, where a supervisor sees only the model's output text, no monitoring system can reliably distinguish honest model outputs from plausible fabrications. We prove two results: first, that any policy conditioning only on the query cannot satisfy epistemic honesty across ambiguous world states; second, that no learning algorithm optimizing reward from a text-only supervisor can converge to honest behavior when the supervisor's observations are identical for both grounded and fabricated responses. Within our formal model, these impossibilities hold regardless of model scale or training procedure, including RLHF and instruction tuning. We construct a tensor interface that escapes the impossibility by exporting computational byproducts (per-token entropy and log-probability distributions) that are structurally coupled to correctness under standard training. Per-token entropy achieves pooled AUC 0.757, outperforming all text baselines by 2.5--3.9 percentage points at every budget level tested (10\%, 20\%, 30\%). The entropy signal generalizes across architectures (Spearman $\rho = 0.762$). The core contribution is a cost surface where the empirical mapping from verification budget (fraction of queries receiving expensive checks) to detection accuracy for each judge strategy is a practical lookup for system builders deciding how to allocate verification resources. The contribution is the map. The territory is the system you are building.
### Title:
          MINISA: Minimal Instruction Set Architecture for Next-gen Reconfigurable Inference Accelerator
 - **Authors:** Jianming Tong, Devansh Jain, Yujie Li, Charith Mendis, Tushar Krishna
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Programming Languages (cs.PL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern reconfigurable AI accelerators rely on rich mapping and data-layout flexibility to sustain high utilization across matrix multiplication, convolution, and emerging applications beyond AI. However, exposing this flexibility through fine-grained micro-control results in prohibitive control overhead of fetching configuration bits from off-chip memory. This paper presents MINISA, a minimal instruction set that programs a reconfigurable accelerator at the granularity of Virtual Neurons (VNs), the coarsest control granularity that retains flexibility of hardware and the finest granularity that avoids unnecessary control costs. First, we introduce FEATHER+, a modest refinement of FEATHER, that eliminates redundant on-chip replication needed for runtime dataflow/layout co-switching and supports dynamic cases where input and weight data are unavailable before execution for offline layout manipulation. MINISA then abstracts control of FEATHER+ into three layout-setting instructions for input, weight, and output VNs and a single mapping instruction for setting dataflow. This reduces the control and instruction footprint while preserving the legal mapping and layout space supported by the FEATHER+. Our results show that MINISA reduces geometric mean off-chip instruction traffic by factors ranging from 35x to (4x10^5)x under various sizes under 50 GEMM workloads spanning AI (GPT-oss), FHE, and ZKP. This eliminates instruction-fetch stalls that consume 96.9% of micro-instruction cycles, yielding up to 31.6x end-to-end speedup for 16x256 FEATHER+. Our code: this https URL.
### Title:
          ToFormer: Towards Large-scale Scenario Depth Completion for Lightweight ToF Camera
 - **Authors:** Juncheng Chen, Tiancheng Lai, Xingpeng Wang, Bingxin Liao, Baozhe Zhang, Chao Xu, Yanjun Cao
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Time-of-Flight (ToF) cameras possess compact design and high measurement precision to be applied to various robot tasks. However, their limited sensing range restricts deployment in large-scale scenarios. Depth completion has emerged as a potential solution to expand the sensing range of ToF cameras, but existing research lacks dedicated datasets and struggles to generalize to ToF measurements. In this paper, we propose a full-stack framework that enables depth completion in large-scale scenarios for short-range ToF cameras. First, we construct a multi-sensor platform with a reconstruction-based pipeline to collect real-world ToF samples with dense large-scale ground truth, yielding the first LArge-ScalE scenaRio ToF depth completion dataset (LASER-ToF). Second, we propose a sensor-aware depth completion network that incorporates a novel 3D branch with a 3D-2D Joint Propagation Pooling (JPP) module and Multimodal Cross-Covariance Attention (MXCA), enabling effective modeling of long-range relationships and efficient 3D-2D fusion under non-uniform ToF depth sparsity. Moreover, our network can utilize the sparse point cloud from visual SLAM as a supplement to ToF depth to further improve prediction accuracy. Experiments show that our method achieves an 8.6% lower mean absolute error than the second-best method, while maintaining lightweight design to support onboard deployment. Finally, to verify the system's applicability on real robots, we deploy proposed method on a quadrotor at a 10Hz runtime, enabling reliable large-scale mapping and long-range planning in challenging environments for short-range ToF cameras.
### Title:
          Beyond the Birkhoff Polytope: Spectral-Sphere-Constrained Hyper-Connections
 - **Authors:** Zhaoyi Liu, Haichuan Zhang, Ang Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hyper-Connections (HC) generalize residual connections into multiple streams, employing residual matrices for cross-stream feature mixing to enrich model expressivity. However, unconstrained mixing disrupts the identity mapping property intrinsic to the residual connection, causing unstable training. To address this, Manifold-Constrained Hyper-Connections (mHC) and its variant restrict these matrices to the Birkhoff polytope (doubly stochastic matrices) via Sinkhorn iterations or permutation-based parameterizations. We reveal three limitations of this polytope constraint: (1) identity degeneration, where learned matrices collapse around the identity and diminish cross-stream interactions, (2) an expressivity bottleneck, as the non-negativity constraint prevents subtractive feature disentanglement, and (3) parameterization inefficiencies, manifesting as unstable Sinkhorn iterations or the factorial-scaling overhead of permutation-based parameterizations. To overcome these flaws, we propose Spectral-Sphere-Constrained Hyper-Connections (sHC). By geometrically shifting the feasible set from a rigid polytope to a spectral norm sphere, sHC allows negative entries, unlocking subtractive interactions for selective feature diversification. This shift eliminates unstable Sinkhorn projections and factorial parameterization, enabling expressive, non-degenerate residual matrices while preserving training stability.
### Title:
          Bayesian Scattering: A Principled Baseline for Uncertainty on Image Data
 - **Authors:** Bernardo Fichera, Zarko Ivkovic, Kjell Jorner, Philipp Hennig, Viacheslav Borovitskiy
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Uncertainty quantification for image data is dominated by complex deep learning methods, yet the field lacks an interpretable, mathematically grounded baseline. We propose Bayesian scattering to fill this gap, serving as a first-step baseline akin to the role of Bayesian linear regression for tabular data. Our method couples the wavelet scattering transform-a deep, non-learned feature extractor-with a simple probabilistic head. Because scattering features are derived from geometric principles rather than learned, they avoid overfitting the training distribution. This helps provide sensible uncertainty estimates even under significant distribution shifts. We validate this on diverse tasks, including medical imaging under institution shift, wealth mapping under country-to-country shift, and Bayesian optimization of molecular properties. Our results suggest that Bayesian scattering is a solid baseline for complex uncertainty quantification methods.
### Title:
          A chaotic flux cipher based on the random cubic family $f_{c_n}(z)=z^3+c_n z$
 - **Authors:** Pouya Mehdipour, Alexandre Miranda Alves, Gerardo Honorato, Mostafa Salarinoghabi
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a symmetric stream cipher that utilizes the dynamic properties of random cubic mappings in the complex plane to generate pseudo-random key streams. The system is based on the iterations of the random cubic polynomial $f_n(z)=z^3+c_n z$, where the parameters $c_n$ are chosen randomly from a disc of radius $\delta$ and with center at the origin, aiming to improve the chaotic behaviour and, consequently, the randomness of the generated sequence. The stability of the Julia set under small parameter perturbations, when $\delta < \delta_0\simeq 0.89$, is considered to ensure key consistency in noisy environments, such as 5G networks. On the other hand, for $\delta > 3$, the system exhibits instability and chaos, ideal for generating ultra-secure keys. The Python implementation integrates secure key derivation, robust key stream generation via warmed-up iteration, and an authenticated encryption scheme using the modern cryptographic primitives (\texttt{HKDF} and\texttt{HMAC-SHA-256}), to ensure message integrity and authenticity. Statistical analyses, including chi-square test and entropy calculation, are performed on the output of the key stream generator to evaluate its randomness and distribution. In addition, a complete statistical validation, compliant with \texttt{NIST SP 800-22} standards in modern cryptography, was performed to enhance the proposed system's credibility.
### Title:
          SURF: Signature-Retained Fast Video Generation
 - **Authors:** Kaixin Ding, Xi Chen, Sihui Ji, Yuan Gao, Liang Hou, Xin Tao, Hengshuang Zhao
 - **Subjects:** Subjects:
Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The demand for high-resolution video generation is growing rapidly. However, the generation resolution is severely constrained by slow inference speeds. For instance, Wan2.1 requires over 50 minutes to generate a single 720p video. While previous works explore accelerating video generation from various aspects, most of them compromise the distinctive signatures (e.g., layout, semantic, motion) of the original model. In this work, we propose SURF, an efficient framework for generating high-resolution videos, while maximally keeping the signatures. Specifically, SURF divides video generation into two stages: First, we leverage the pretrained model to infer at optimal resolution and downsample latent to generate low-resolution previews in fast speed; then we design a Refiner to upscale the preview. In the preview stage, we identify that directly inferring a model (trained with higher resolution) on lower resolution causes severe losses in signatures. So we introduce noise reshifting, a training-free technique that mitigates this issue by conducting initial denoising steps on the original resolution and switching to low resolution in later steps. In the refine stage, we establish a mapping relationship between the preview and the high-resolution target, which significantly reduces the denoising steps. We further integrate shifting windows and carefully design the training paradigm to get a powerful and efficient Refiner. In this way, SURF enables generating high-resolution videos efficiently while maximally closer to the signatures of the given pretrained model. SURF is conceptually simple and could serve as a plug-in that is compatible with various base model and acceleration methods. For example, it achieves 12.5x speedup for generating 5-second, 16fps, 720p Wan 2.1 videos and 8.7x speedup for generating 5-second, 24fps, 720p HunyuanVideo.
### Title:
          SGAD-SLAM: Splatting Gaussians at Adjusted Depth for Better Radiance Fields in RGBD SLAM
 - **Authors:** Pengchong Hu, Zhizhong Han
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian Splatting (3DGS) has made remarkable progress in RGBD SLAM. Current methods usually use 3D Gaussians or view-tied 3D Gaussians to represent radiance fields in tracking and mapping. However, these Gaussians are either too flexible or too limited in movements, resulting in slow convergence or limited rendering quality. To resolve this issue, we adopt pixel-aligned Gaussians but allow each Gaussian to adjust its position along its ray to maximize the rendering quality, even if Gaussians are simplified to improve system scalability. To speed up the tracking, we model the depth distribution around each pixel as a Gaussian distribution, and then use these distributions to align each frame to the 3D scene quickly. We report our evaluations on widely used benchmarks, justify our designs, and show advantages over the latest methods in view rendering, camera tracking, runtime, and storage complexity. Please see our project page for code and videos at this https URL .
### Title:
          Single-Eye View: Monocular Real-time Perception Package for Autonomous Driving
 - **Authors:** Haixi Zhang, Aiyinsi Zuo, Zirui Li, Chunshu Wu, Tong Geng, Zhiyao Duan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Amidst the rapid advancement of camera-based autonomous driving technology, effectiveness is often prioritized with limited attention to computational efficiency. To address this issue, this paper introduces LRHPerception, a real-time monocular perception package for autonomous driving that uses single-view camera video to interpret the surrounding environment. The proposed system combines the computational efficiency of end-to-end learning with the rich representational detail of local mapping methodologies. With significant improvements in object tracking and prediction, road segmentation, and depth estimation integrated into a unified framework, LRHPerception processes monocular image data into a five-channel tensor consisting of RGB, road segmentation, and pixel-level depth estimation, augmented with object detection and trajectory prediction. Experimental results demonstrate strong performance, achieving real-time processing at 29 FPS on a single GPU, representing a 555% speedup over the fastest mapping-based approach.
### Title:
          AnyPro: Preference-Preserving Anycast Optimization based on Strategic AS-Path Prepending
 - **Authors:** Minyuan Zhou, Yuning Chen, Jiaqi Zheng, Yifei Xu, Pan Hu, Yongping Tang, Wendong Yin, Jie Lin, Qingyan Yu, Yuanchao Su, Guihai Chen, Wanchun Dou, Songwu Lu, Wan Du
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Operating large-scale anycast networks is challenging because client-to-site mappings often misalign with operator's expectation due to opaque inter-domain routing. We present AnyPro, the first system to unlock the full potential of AS-path prepending (ASPP), efficiently deriving globally optimal configurations to steer clients toward performance-optimal sites at scale. AnyPro first employs an efficient polling mechanism to identify all clients sensitive to ASPP. By analyzing the routing changes during the process, the system derives a set of ASPP constraints that guide client traffic toward the desired sites. We then formulate the anycast optimization problem as a constraint-based program and compute optimal ASPP configurations. Extensive evaluation on a global testbed with 20 PoPs demonstrates the effectiveness of AnyPro: it reduces the 90th percentile latency by 37.7% compared to baseline configurations without ASPP. Furthermore, we show that AnyPro can be integrated with PoP-level anycast optimization techniques to achieve additional performance gains.
### Title:
          Tucker Tensor Train Taylor Series
 - **Authors:** Nick Alger, Blake Christierson, Peng Chen, Omar Ghattas
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present methods for constructing Taylor series surrogate models for covariance preconditioned high dimensional mappings that depend implicitly on the solution of a system of nonlinear equations, e.g., the solution of a partial differential equation. Taylor series are traditionally considered intractable for such mappings because the derivative tensors are enormous, and are only accessible through ``probing'' (contraction of the tensor with vectors in all but one index). We overcome these challenges using a ``Tucker tensor train Taylor series'' (T4S) surrogate model, in which each derivative tensor is approximated by a Tucker decomposition composed with a tensor train. After an initial dimension reduction, Tucker tensor trains are fit to directionally symmetric tensor probes using Riemannian manifold optimization within a rank continuation scheme. The optimization is enabled by fast sweeping methods for applying the Riemannian Jacobian (the Jacobian for the Tucker tensor train fitting problem) and its transpose to vectors. We justify the T4S model theoretically, and provide numerical evidence for the effectiveness of the proposed methods.
### Title:
          Architecture for Multi-Unmanned Aerial Vehicles based Autonomous Precision Agriculture Systems
 - **Authors:** Ebasa Temesgen, Nathnael Minyelshowa, Lebsework Negash
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The use of unmanned aerial vehicles (UAVs) in precision agriculture has seen a huge increase recently. As such, systems that aim to apply various algorithms on the field need a structured framework of abstractions. This paper defines the various tasks of the UAVs in precision agriculture and model them into an architectural framework. The presented architecture is built on the context that there will be minimal physical intervention to do the tasks defined with multiple coordinated and cooperative UAVs. Various tasks such as image processing, path planning, communication, data acquisition, and field mapping are employed in the architecture to provide an efficient system. Besides, different limitation for applying Multi-UAVs in precision agriculture has been considered in designing the architecture. The architecture provides an autonomous end-to-end solution, starting from mission planning, data acquisition and image processing framework that is highly efficient and can enable farmers to comprehensively deploy UAVs onto their lands. Simulation and field tests shows that the architecture offers a number of advantages that include fault-tolerance, robustness, developer and user-friendliness.
### Title:
          Boundary-Aware Instance Segmentation in Microscopy Imaging
 - **Authors:** Thomas Mendelson, Joshua Francois, Galit Lahav, Tammy Riklin-Raviv
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate delineation of individual cells in microscopy videos is essential for studying cellular dynamics, yet separating touching or overlapping instances remains a persistent challenge. Although foundation-model for segmentation such as SAM have broadened the accessibility of image segmentation, they still struggle to separate nearby cell instances in dense microscopy scenes without extensive prompting. We propose a prompt-free, boundary-aware instance segmentation framework that predicts signed distance functions (SDFs) instead of binary masks, enabling smooth and geometry-consistent modeling of cell contours. A learned sigmoid mapping converts SDFs into probability maps, yielding sharp boundary localization and robust separation of adjacent instances. Training is guided by a unified Modified Hausdorff Distance (MHD) loss that integrates region- and boundary-based terms. Evaluations on both public and private high-throughput microscopy datasets demonstrate improved boundary accuracy and instance-level performance compared to recent SAM-based and foundation-model approaches. Source code is available at: this https URL
### Title:
          A Large-Scale Remote Sensing Dataset and VLM-based Algorithm for Fine-Grained Road Hierarchy Classification
 - **Authors:** Ting Han, Xiangyi Xie, Yiping Chen, Yumeng Du, Jin Ma, Aiguang Li, Jiaan Liu, Yin Gao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this work, we present SYSU-HiRoads, a large-scale hierarchical road dataset, and RoadReasoner, a vision-language-geometry framework for automatic multi-grade road mapping from remote sensing imagery. SYSU-HiRoads is built from GF-2 imagery covering 3631 km2 in Henan Province, China, and contains 1079 image tiles at 0.8 m spatial resolution. Each tile is annotated with dense road masks, vectorized centerlines, and three-level hierarchy labels, enabling the joint training and evaluation of segmentation, topology reconstruction, and hierarchy classification. Building on this dataset, RoadReasoner is designed to generate robust road surface masks, topology-preserving road networks, and semantically coherent hierarchy assignments. We strengthen road feature representation and network connectivity by explicitly enhancing frequency-sensitive cues and multi-scale context. Moreover, we perform hierarchy inference at the skeleton-segment level with geometric descriptors and geometry-aware textual prompts, queried by vision-language models to obtain linguistically interpretable grade decisions. Experiments on SYSU-HiRoads and the CHN6-CUG dataset show that RoadReasoner surpasses state-of-the-art road extraction baselines and produces accurate and semantically consistent road hierarchy maps with 72.6% OA, 64.2% F1 score, and 60.6% SegAcc. The dataset and code will be publicly released to support automated transport infrastructure mapping, road inventory updating, and broader infrastructure management applications.
### Title:
          Enhancing Brain Tumor Classification Using Vision Transformers with Colormap-Based Feature Representation on BRISC2025 Dataset
 - **Authors:** Faisal Ahmed
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate classification of brain tumors from magnetic resonance imaging (MRI) plays a critical role in early diagnosis and effective treatment planning. In this study, we propose a deep learning framework based on Vision Transformers (ViT) enhanced with colormap-based feature representation to improve multi-class brain tumor classification performance. The proposed approach leverages the ability of transformer architectures to capture long-range dependencies while incorporating color mapping techniques to emphasize important structural and intensity variations within MRI scans. Experiments are conducted on the BRISC2025 dataset, which includes four classes: glioma, meningioma, pituitary tumor, and non-tumor cases. The model is trained and evaluated using standard performance metrics such as accuracy, precision, recall, F1-score, and area under the receiver operating characteristic curve (AUC). The proposed method achieves a classification accuracy of 98.90%, outperforming baseline convolutional neural network models including ResNet50, ResNet101, and EfficientNetB2. In addition, the model demonstrates strong generalization capability with an AUC of 99.97%, indicating high discriminative performance across all classes. These results highlight the effectiveness of combining Vision Transformers with colormap-based feature enhancement for accurate and robust brain tumor classification and suggest strong potential for clinical decision support applications.
### Title:
          Graph Fusion Across Languages using Large Language Models
 - **Authors:** Kaung Myat Kyaw, Khush Agarwal, Jonathan Chan
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Combining multiple knowledge graphs (KGs) across linguistic boundaries is a persistent challenge due to semantic heterogeneity and the complexity of graph environments. We propose a framework for cross-lingual graph fusion, leveraging the in-context reasoning and multilingual semantic priors of Large Language Models (LLMs). The framework implements structural linearization by mapping triplets directly into natural language sequences (e.g., [head] [relation] [tail]), enabling the LLM to map relations and reconcile entities between an evolving fused graph ($G_{c}^{(t-1)}$) and a new candidate graph ($G_{t}$). Evaluated on the DBP15K dataset, this exploratory study demonstrates that LLMs can serve as a universal semantic bridge to resolve cross-lingual discrepancies. Results show the successful sequential agglomeration of multiple heterogeneous graphs, offering a scalable, modular solution for continuous knowledge synthesis in multi-source, multilingual environments.
### Title:
          Conspiracy Frame: a Semiotically-Driven Approach for Conspiracy Theories Detection
 - **Authors:** Heidi Campana Piva, Shaina Ashraf, Maziar Kianimoghadam Jouneghani, Arianna Longo, Rossana Damiano, Lucie Flek, Marco Antonio Stranisci
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Conspiracy theories are anti-authoritarian narratives that lead to social conflict, impacting how people perceive political information. To help in understanding this issue, we introduce the Conspiracy Frame: a fine-grained semantic representation of conspiratorial narratives derived from frame-semantics and semiotics, which spawned the Conspiracy Frames (this http URL.) dataset: a corpus of Telegram messages annotated at span-level. The Conspiracy Frame and this http URL. dataset contribute to the implementation of a more generalizable understanding and recognition of conspiracy theories. We observe the ability of LLMs to recognize this phenomenon in-domain and out-of-domain, investigating the role that frames may have in supporting this task. Results show that, while the injection of frames in an in-context approach does not lead to clear increase of performance, it has potential; the mapping of annotated spans with FrameNet shows abstract semantic patterns (e.g., `Kinship', `Ingest\_substance') that potentially pave the way for a more semantically- and semiotically-aware detection of conspiratorial narratives.
### Title:
          Sharper Generalization Bounds for Transformer
 - **Authors:** Yawen Li, Tao Hu, Zhouhui Lian, Wan Tian, Yijie Peng, Huiming Zhang, Zhongyi Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper studies generalization error bounds for Transformer models. Based on the offset Rademacher complexity, we derive sharper generalization bounds for different Transformer architectures, including single-layer single-head, single-layer multi-head, and multi-layer Transformers. We first express the excess risk of Transformers in terms of the offset Rademacher complexity. By exploiting its connection with the empirical covering numbers of the corresponding hypothesis spaces, we obtain excess risk bounds that achieve optimal convergence rates up to constant factors. We then derive refined excess risk bounds by upper bounding the covering numbers of Transformer hypothesis spaces using matrix ranks and matrix norms, leading to precise, architecture-dependent generalization bounds. Finally, we relax the boundedness assumption on feature mappings and extend our theoretical results to settings with unbounded (sub-Gaussian) features and heavy-tailed distributions.
### Title:
          Full Timescale Hierarchical MPC-MTIP Framework for Hybrid Energy Storage Management in Low-Carbon Industrial Microgrid
 - **Authors:** Daniyaer Paizulamu, Lin Cheng, Ning Qi, Zhengmao Li, Nikos D. Hatziargyriou
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Uncertainties in balancing generation and load in low-carbon industrial microgrids (IMGs) make hybrid energy storage systems (HESS) crucial for their stable and economic operation. Existing model predictive control (MPC) techniques typically enforce periodic state of charge (SOC) constraints to maintain long term stability. However, these hard constraints compromise dispatch flexibility near the end of the prediction horizon, preventing sufficient energy release during critical peaks and leading to optimization infeasibility. This paper eliminates the periodic SOC constraints of individual storage units and proposes a novel full-timescale hierarchical MPC scheduling framework. Specifically, comprehensive physical and cost models are established for the HESS composed of flywheel, battery, compressed-air, and hydrogen-methanol energy storage. The control problem is decoupled into a hierarchical MPC architecture. Furthermore, a novel adaptive feedback mechanism based on micro trajectory inverse projection (MTIP) is embedded into the scheduling process, accurately mapping the high frequency dynamic buffering capabilities of lower tier storages into the upper decision space to generate dynamic boundaries. Experiments using 14 consecutive months of second-level data from a real-world IMG validate the effectiveness of the proposed method, demonstrating its significant superiority over existing approaches. By effectively preventing limit violations and deadlocks in lower-tier storages under extreme fluctuations, it achieves a 97.4\% net load smoothing rate and a 62.2\% comprehensive cycle efficiency.
### Title:
          Rethinking Token Reduction for Large Vision-Language Models
 - **Authors:** Yi Wang, Haofei Zhang, Qihan Huang, Anda Cao, Gongfan Fang, Wei Wang, Xuan Jin, Jie Song, Mingli Song, Xinchao Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Vision-Language Models (LVLMs) excel in visual understanding and reasoning, but the excessive visual tokens lead to high inference costs. Although recent token reduction methods mitigate this issue, they mainly target single-turn Visual Question Answering (VQA), leaving the more practical multi-turn VQA (MT-VQA) scenario largely unexplored. MT-VQA introduces additional challenges, as subsequent questions are unknown beforehand and may refer to arbitrary image regions, making existing reduction strategies ineffective. Specifically, current approaches fall into two categories: prompt-dependent methods, which bias toward the initial text prompt and discard information useful for subsequent turns; prompt-agnostic ones, which, though technically applicable to multi-turn settings, rely on heuristic reduction metrics such as attention scores, leading to suboptimal performance. In this paper, we propose a learning-based prompt-agnostic method, termed MetaCompress, overcoming the limitations of heuristic designs. We begin by formulating token reduction as a learnable compression mapping, unifying existing formats such as pruning and merging into a single learning objective. Upon this formulation, we introduce a data-efficient training paradigm capable of learning optimal compression mappings with limited computational costs. Extensive experiments on MT-VQA benchmarks and across multiple LVLM architectures demonstrate that MetaCompress achieves superior efficiency-accuracy trade-offs while maintaining strong generalization across dialogue turns. Our code is available at this https URL.
### Title:
          FISformer: Replacing Self-Attention with a Fuzzy Inference System in Transformer Models for Time Series Forecasting
 - **Authors:** Bulent Haznedar, Levent Karacan
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers have achieved remarkable progress in time series forecasting, yet their reliance on deterministic dot-product attention limits their capacity to model uncertainty and nonlinear dependencies across multivariate temporal dimensions. To address this limitation, we propose FISFormer, a Fuzzy Inference System-driven Transformer that replaces conventional attention with a FIS Interaction mechanism. In this framework, each query-key pair undergoes a fuzzy inference process for every feature dimension, where learnable membership functions and rule-based reasoning estimate token-wise relational strengths. These FIS-derived interaction weights capture uncertainty and provide interpretable, continuous mappings between tokens. A softmax operation is applied along the token axis to normalize these weights, which are then combined with the corresponding value features through element-wise multiplication to yield the final context-enhanced token representations. This design fuses the interpretability and uncertainty modeling of fuzzy logic with the representational power of Transformers. Extensive experiments on multiple benchmark datasets demonstrate that FISFormer achieves superior forecasting accuracy, noise robustness, and interpretability compared to state-of-the-art Transformer variants, establishing fuzzy inference as an effective alternative to conventional attention mechanisms.
### Title:
          Memory-Efficient Boundary Map for Large-Scale Occupancy Grid Mapping
 - **Authors:** Benxu Tang, Yunfan Ren, Yixi Cai, Fanze Kong, Wenyi Liu, Fangcheng Zhu, Longji Yin, Liuyu Shi, Fu Zhang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Determining the occupancy status of locations in the environment is a fundamental task for safety-critical robotic applications. Traditional occupancy grid mapping methods subdivide the environment into a grid of voxels, each associated with one of three occupancy states: free, occupied, or unknown. These methods explicitly maintain all voxels within the mapped volume and determine the occupancy state of a location by directly querying the corresponding voxel that the location falls within. However, maintaining all grid voxels in high-resolution and large-scale scenarios requires substantial memory resources. In this paper, we introduce a novel representation that only maintains the boundary of the mapped volume. Specifically, we explicitly represent the boundary voxels, such as the occupied voxels and frontier voxels, while free and unknown voxels are automatically represented by volumes within or outside the boundary, respectively. As our representation maintains only a closed surface in two-dimensional (2D) space, instead of the entire volume in three-dimensional (3D) space, it significantly reduces memory consumption. Then, based on this 2D representation, we propose a method to determine the occupancy state of arbitrary locations in the 3D environment. We term this method as boundary map. Besides, we design a novel data structure for maintaining the boundary map, supporting efficient occupancy state queries. Theoretical analyses of the occupancy state query algorithm are also provided. Furthermore, to enable efficient construction and updates of the boundary map from the real-time sensor measurements, we propose a global-local mapping framework and corresponding update algorithms. Finally, we will make our implementation of the boundary map open-source on GitHub to benefit the community:this https URL.
### Title:
          Isogeometric analysis with $C^1$ cubic Powell-Sabin splines
 - **Authors:** Jan Grošelj, Ada Šadl Praprotnik, Hendrik Speleers
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we consider $C^1$ cubic Powell-Sabin splines for the numerical solution of boundary value problems on planar and spatial surface domains. We first review the construction and basic properties of polynomial and rational $C^1$ cubic Powell-Sabin spline representations on unstructured triangulations. Then, we discuss how these flexible representations can be exploited to create geometry mappings suited for a precise description of (classes of) surface domains. This is illustrated with several examples. Finally, the obtained domain descriptions are utilized in the isogeometric analysis framework for solving various Poisson and biharmonic problems. It is demonstrated that $C^1$ cubic Powell-Sabin splines form a powerful alternative to $C^0$ cubic Lagrange elements and bicubic NURBS.
### Title:
          Riding Brainwaves in LLM Space: Understanding Activation Patterns Using Individual Neural Signatures
 - **Authors:** Ajan Subramanian, Sumukh Bettadapura, Rohan Sathish
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Consumer-grade EEG is entering everyday devices, from earbuds to headbands, raising the question of whether language models can be adapted to individual neural responses. We test this by asking whether frozen LLM representations encode person-specific EEG signals, directions in activation space that predict one person's brain activity but not another's. Using word-level EEG from 30 participants reading naturalistic sentences (ZuCo corpus), we train a separate linear probe for each person, mapping hidden states from a frozen Qwen 2.5 7B to that individual's EEG power. Person-specific probes outperform a single population probe on every EEG feature tested; for high-gamma power, the person-specific probe achieves rho = 0.183, a ninefold improvement over the population probe (rho = 0.020, p < 10^-4). A negative control, fixation count, shows no person-specific advantage (p = 0.360); fixation count reflects word length and frequency rather than individual cognition. The individual directions are temporally stable (split-half cosine = 0.824), non-transferable across people (self rho = 0.369 vs. other rho = 0.143, p < 10^-19), and distinct from the shared population signal: person-specific probes retain predictive power after the population component is removed. The person-specific signal concentrates in the model's deep layers, rising consistently with depth and peaking at Layer 24 of 28. The results are consistent across architectures (LLaMA 3.1 8B) and survive word-level confound controls. Frozen language models contain stable, person-specific neural directions in their deep layers, providing a geometric foundation for EEG-driven personalization.
### Title:
          IGV-RRT: Prior-Real-Time Observation Fusion for Active Object Search in Changing Environments
 - **Authors:** Wei Zhang, Ping Gong, Yujie Wang, Minghui Bai, Rongfeng Ye, Yinchuan Wang, Yachao Wang, Leilei Yao, Teng Chen, Chen Sun, Chaoqun Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Object Goal Navigation (ObjectNav) in temporally changing indoor environments is challenging because object relocation can invalidate historical scene knowledge. To address this issue, we propose a probabilistic planning framework that combines uncertainty-aware scene priors with online target relevance estimates derived from a Vision Language Model (VLM). The framework contains a dual-layer semantic mapping module and a real-time planner. The mapping module includes an Information Gain Map (IGM) built from a 3D scene graph (3DSG) during prior exploration to model object co-occurrence relations and provide global guidance on likely target regions. It also maintains a VLM score map (VLM-SM) that fuses confidence-weighted semantic observations into the map for local validation of the current scene. Based on these two cues, we develop a planner that jointly exploits information gain and semantic evidence for online decision making. The planner biases tree expansion toward semantically salient regions with high prior likelihood and strong online relevance (IGV-RRT), while preserving kinematic feasibility through gradient-based analysis. Simulation and real-world experiments demonstrate that the proposed method effectively mitigates the impact of object rearrangement, achieving higher search efficiency and success rates than representative baselines in complex indoor environments.
### Title:
          SparseDVFS: Sparse-Aware DVFS for Energy-Efficient Edge Inference
 - **Authors:** Ziyang Zhang, Zheshun Wu, Jie Liu, Luca Mottola
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deploying deep neural networks (DNNs) on power-sensitive edge devices presents a formidable challenge. While Dynamic Voltage and Frequency Scaling (DVFS) is widely employed for energy optimization, traditional model-level scaling is often too coarse to capture intra-inference variations, whereas fine-grained operator-level scaling suffers from prohibitive performance degradation due to significant hardware switching latency. This paper presents SparseDVFS, a fine-grained, sparse-aware DVFS framework designed for energy-efficient edge inference. Our key insight is that operator sparsity is a primary metric for hardware frequency modulation. By distinguishing between compute-bound dense operators and memory-bound sparse operators, the system can apply specialized frequency triplets to maximize energy efficiency. To overcome switching overheads and component interference, SparseDVFS incorporates three key innovations: (1) an offline modeler that established a deterministic mapping between operator sparsity and optimal frequency triplets (CPU/GPU/EMC) via white-box timeline analysis; (2) a runtime graph partitioner that utilizes a greedy merging heuristic to aggregate operators into super-blocks, balancing scaling granularity and DVFS switching latency through a latency amortization constraint; and (3) a unified co-governor that employs a frequency unified scaling engine (FUSE) and a look-ahead instruction queue to eliminate antagonistic effects between independent controllers and hide hardware transition latencies. Extensive evaluations show that SparseDVFS achieves an average 78.17% energy efficiency gain over state-of-the-art solutions while maintaining a superior 14% cost-gain ratio.
### Title:
          A Novel Method for Enforcing Exactly Dirichlet, Neumann and Robin Conditions on Curved Domain Boundaries for Physics Informed Machine Learning
 - **Authors:** Suchuan Dong, Yuchuan Zhang
 - **Subjects:** Subjects:
Numerical Analysis (math.NA); Machine Learning (cs.LG); Computational Physics (physics.comp-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a systematic method for exactly enforcing Dirichlet, Neumann, and Robin type conditions on general quadrilateral domains with arbitrary curved boundaries. Our method is built upon exact mappings between general quadrilateral domains and the standard domain, and employs a combination of TFC (theory of functional connections) constrained expressions and transfinite interpolations. When Neumann or Robin boundaries are present, especially when two Neumann (or Robin) boundaries meet at a vertex, it is critical to enforce exactly the induced compatibility constraints at the intersection, in order to enforce exactly the imposed conditions on the joining boundaries. We analyze in detail and present constructions for handling the imposed boundary conditions and the induced compatibility constraints for two types of situations: (i) when Neumann (or Robin) boundary only intersects with Dirichlet boundaries, and (ii) when two Neumann (or Robin) boundaries intersect with each other. We describe a four-step procedure to systematically formulate the general form of functions that exactly satisfy the imposed Dirichlet, Neumann, or Robin conditions on general quadrilateral domains. The method developed herein has been implemented together with the extreme learning machine (ELM) technique we have developed recently for scientific machine learning. Ample numerical experiments are presented with several linear/nonlinear stationary/dynamic problems on a variety of two-dimensional domains with complex boundary geometries. Simulation results demonstrate that the proposed method has enforced the Dirichlet, Neumann, and Robin conditions on curved domain boundaries exactly, with the numerical boundary-condition errors at the machine accuracy.
### Title:
          GeoFlow: Real-Time Fine-Grained Cross-View Geolocalization via Iterative Flow Prediction
 - **Authors:** Ayesh Abu Lehyeh, Xiaohan Zhang, Ahmad Arrabi, Waqas Sultani, Chen Chen, Safwan Wshah
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate and fast localization is vital for safe autonomous navigation in GPS-denied areas. Fine-Grained Cross-View Geolocalization (FG-CVG) aims to estimate the precise 2-Degree-of-Freedom (2-DoF) location of a ground image relative to a satellite image. However, current methods force a difficult trade-off, with high-accuracy models being slow for real-time use. In this paper, we introduce GeoFlow, a new approach that offers a lightweight and highly efficient framework that breaks this accuracy-speed trade-off. Our technique learns a direct probabilistic mapping, predicting the displacement (in distance and direction) required to correct any given location hypothesis. This is complemented by our novel inference algorithm, Iterative Refinement Sampling (IRS). Instead of trusting a single prediction, IRS refines a population of hypotheses, allowing them to iteratively 'flow' from random starting points to a robust, converged consensus. Even its iterative nature, this approach offers flexible inference-time scaling, allowing a direct trade-off between performance and computation without any re-training. Experiments on the KITTI and VIGOR datasets show that GeoFlow achieves state-of-the-art efficiency, running at real-time speeds of 29 FPS while maintaining competitive localization accuracy. This work opens a new path for the development of practical real-time geolocalization systems.
### Title:
          VP-VLA: Visual Prompting as an Interface for Vision-Language-Action Models
 - **Authors:** Zixuan Wang, Yuxin Chen, Yuqi Liu, Jinhui Ye, Pengguang Chen, Changsheng Lu, Shu Liu, Jiaya Jia
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models typically map visual observations and linguistic instructions directly to robotic control signals. This "black-box" mapping forces a single forward pass to simultaneously handle instruction interpretation, spatial grounding, and low-level control, often leading to poor spatial precision and limited robustness in out-of-distribution scenarios. To address these limitations, we propose VP-VLA, a dual-system framework that decouples high-level reasoning and low-level execution via a structured visual prompting interface. Specifically, a "System 2 Planner" decomposes complex instructions into sub-tasks and identifies relevant target objects and goal locations. These spatial anchors are then overlaid directly onto visual observations as structured visual prompts, such as crosshairs and bounding boxes. Guided by these prompts and enhanced by a novel auxiliary visual grounding objective during training, a "System 1 Controller" reliably generates precise low-level execution motions. Experiments on the Robocasa-GR1-Tabletop benchmark and SimplerEnv simulation demonstrate that VP-VLA improves success rates by 5% and 8.3%, surpassing competitive baselines including QwenOFT and GR00T-N1.6.
### Title:
          ROBOGATE: Adaptive Failure Discovery for Safe Robot Policy Deployment via Two-Stage Boundary-Focused Sampling
 - **Authors:** Byungjin Kim
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deploying learned robot manipulation policies in industrial settings requires rigorous pre-deployment validation, yet exhaustive testing across high-dimensional parameter spaces is intractable. We present ROBOGATE, a deployment risk management framework that combines physics-based simulation with a two-stage adaptive sampling strategy to efficiently discover failure boundaries in the operational parameter space. Stage 1 employs Latin Hypercube Sampling (LHS) across an 8-dimensional parameter space to establish a coarse failure landscape from 20,000 uniformly distributed experiments. Stage 2 applies boundary-focused sampling that concentrates 10,000 additional experiments in the 30-70% success rate transition zone, enabling precise failure boundary mapping. Using NVIDIA Isaac Sim with Newton physics, we evaluate a scripted pick-and-place controller on two robot embodiments -- Franka Panda (7-DOF) and UR5e (6-DOF) -- across 30,000 total experiments. Our logistic regression risk model achieves an AUC of 0.780 on the combined dataset (vs. 0.754 for Stage 1 alone), identifies a closed-form failure boundary equation, and reveals four universal danger zones affecting both robot platforms. We further demonstrate the framework on VLA (Vision-Language-Action) model evaluation, where Octo-Small achieves 0.0% success rate on 68 adversarial scenarios versus 100% for the scripted baseline -- a 100-point gap that underscores the challenge of deploying foundation models in industrial settings. ROBOGATE is open-source and runs on a single GPU workstation.
### Title:
          Make Tracking Easy: Neural Motion Retargeting for Humanoid Whole-body Control
 - **Authors:** Qingrui Zhao, Kaiyue Yang, Xiyu Wang, Shiqi Zhao, Yi Lu, Xinfang Zhang, Wei Yin, Qiu Shen, Xiao-Xiao Long, Xun Cao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Humanoid robots require diverse motor skills to integrate into complex environments, but bridging the kinematic and dynamic embodiment gap from human data remains a major bottleneck. We demonstrate through Hessian analysis that traditional optimization-based retargeting is inherently non-convex and prone to local optima, leading to physical artifacts like joint jumps and self-penetration. To address this, we reformulate the targeting problem as learning data distribution rather than optimizing optimal solutions, where we propose NMR, a Neural Motion Retargeting framework that transforms static geometric mapping into a dynamics-aware learned process. We first propose Clustered-Expert Physics Refinement (CEPR), a hierarchical data pipeline that leverages VAE-based motion clustering to group heterogeneous movements into latent motifs. This strategy significantly reduces the computational overhead of massively parallel reinforcement learning experts, which project and repair noisy human demonstrations onto the robot's feasible motion manifold. The resulting high-fidelity data supervises a non-autoregressive CNN-Transformer architecture that reasons over global temporal context to suppress reconstruction noise and bypass geometric traps. Experiments on the Unitree G1 humanoid across diverse dynamic tasks (e.g., martial arts, dancing) show that NMR eliminates joint jumps and significantly reduces self-collisions compared to state-of-the-art baselines. Furthermore, NMR-generated references accelerate the convergence of downstream whole-body control policies, establishing a scalable path for bridging the human-robot embodiment gap.
### Title:
          Gumbel Distillation for Parallel Text Generation
 - **Authors:** Chi Zhang, Xixi Hu, Bo Liu, Qiang Liu
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The slow, sequential nature of autoregressive (AR) language models has driven the adoption of parallel decoding methods. However, these non-AR models often sacrifice generation quality as they struggle to model the complex joint distribution of token sequences. To narrow this performance gap, we introduce Gumbel Distillation, a novel distillation technique that enables parallel decoders to learn this distribution effectively. Our method leverages the Gumbel-Max trick to create a deterministic mapping from a latent Gumbel noise space to the output tokens of a high-performing AR teacher. As a model-agnostic technique, Gumbel Distillation seamlessly integrates with diverse parallel decoding architectures, including MDLM and BD3-LM. Experiments on LM1B and OpenWebText show that Gumbel Distillation substantially improves the generation quality of parallel language models, achieving a 30.0% improvement in MAUVE score and 10.5% in generative perplexity over MDLM trained on OpenWebText dataset. Code available at this https URL.
### Title:
          Riverine Land Cover Mapping through Semantic Segmentation of Multispectral Point Clouds
 - **Authors:** Sopitta Thurachen, Josef Taher, Matti Lehtomäki, Leena Matikainen, Linnea Blåfield, Mikel Calle Navarro, Antero Kukko, Tomi Westerlund, Harri Kaartinen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate land cover mapping in riverine environments is essential for effective river management, ecological understanding, and geomorphic change monitoring. This study explores the use of Point Transformer v2 (PTv2), an advanced deep neural network architecture designed for point cloud data, for land cover mapping through semantic segmentation of multispectral LiDAR data in real-world riverine environments. We utilize the geometric and spectral information from the 3-channel LiDAR point cloud to map land cover classes, including sand, gravel, low vegetation, high vegetation, forest floor, and water. The PTv2 model was trained and evaluated on point cloud data from the Oulanka river in northern Finland using both geometry and spectral features. To improve the model's generalization in new riverine environments, we additionally investigate multi-dataset training that adds sparsely annotated data from an additional river dataset. Results demonstrated that using the full-feature configuration resulted in performance with a mean Intersection over Union (mIoU) of 0.950, significantly outperforming the geometry baseline. Other ablation studies revealed that intensity and reflectance features were the key for accurate land cover mapping. The multi-dataset training experiment showed improved generalization performance, suggesting potential for developing more robust models despite limited high-quality annotated data. Our work demonstrates the potential of applying transformer-based architectures to multispectral point clouds in riverine environments. The approach offers new capabilities for monitoring sediment transport and other river management applications.
## Keyword: localization
### Title:
          ContractSkill: Repairable Contract-Based Skills for Multimodal Web Agents
 - **Authors:** Zijian Lu, Yiping Zuo, Yupeng Nie, Xin He, Weibei Fan, Chen Dai
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite rapid progress in multimodal GUI agents, reusable skill acquisition remains difficult because on-demand generated skills often leave action semantics, state assumptions, and success criteria implicit. This makes them brittle to execution errors, hard to verify, and difficult to repair. We present ContractSkill, a framework that converts a draft skill into a contracted executable artifact with explicit preconditions, step specifications, postconditions, recovery rules, and termination checks. This representation enables deterministic verification, step-level fault localization, and minimal patch-based repair, turning skill refinement into localized editing rather than full regeneration. Experiments on VisualWebArena and MiniWoB with GLM-4.6V and Qwen3.5-Plus show that ContractSkill improves self-generated skills from 9.4% and 10.9% to 28.1% and 37.5% on VisualWebArena, and from 66.5% and 60.5% to 77.5% and 81.0% on MiniWoB. Repaired artifacts also transfer across models, improving the target model's self-generated-skill baseline by up to 47.8 points and 12.8 points on the two benchmarks, respectively. These results suggest that agent skills are better treated as explicit procedural artifacts that can be verified, repaired, and shared across models.
### Title:
          Scene Representation using 360° Saliency Graph and its Application in Vision-based Indoor Navigation
 - **Authors:** Preeti Meena, Himanshu Kumar, Sandeep Yadav
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO); Image and Video Processing (eess.IV); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A Scene, represented visually using different formats such as RGB-D, LiDAR scan, keypoints, rectangular, spherical, multi-views, etc., contains information implicitly embedded relevant to applications such as scene indexing, vision-based navigation. Thus, these representations may not be efficient for such applications. This paper proposes a novel 360° saliency graph representation of the scenes. This rich representation explicitly encodes the relevant visual, contextual, semantic, and geometric information of the scene as nodes, edges, edge weights, and angular position in the 360° graph. Also, this representation is robust against scene view change and addresses challenges of indoor environments such as varied illumination, occlusions, and shadows as in the case of existing traditional methods. We have utilized this rich and efficient representation for vision-based navigation and compared it with existing navigation methods using 360° scenes. However, these existing methods suffer from limitations of poor scene representation, lacking scene-specific information. This work utilizes the proposed representation first to localize the query scene in the given topological map, and then facilitate 2D navigation by estimating the next required movement directions towards the target destination in the topological map by using the embedded geometric information in the 360° saliency graph. Experimental results demonstrate the efficacy of the proposed 360° saliency graph representation in enhancing both scene localization and vision-based indoor navigation.
### Title:
          Memory poisoning and secure multi-agent systems
 - **Authors:** Vicenç Torra, Maria Bras-Amorós
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Memory poisoning attacks for Agentic AI and multi-agent systems (MAS) have recently caught attention. It is partially due to the fact that Large Language Models (LLMs) facilitate the construction and deployment of agents. Different memory systems are being used nowadays in this context, including semantic, episodic, and short-term memory. This distinction between the different types of memory systems focuses mostly on their duration but also on their origin and their localization. It ranges from the short-term memory originated at the user's end localized in the different agents to the long-term consolidated memory localized in well established knowledge databases. In this paper, we first present the main types of memory systems, we then discuss the feasibility of memory poisoning attacks in these different types of memory systems, and we propose mitigation strategies. We review the already existing security solutions to mitigate some of the alleged attacks, and we discuss adapted solutions based on cryptography. We propose to implement local inference based on private knowledge retrieval as an example of mitigation strategy for memory poisoning for semantic memory. We also emphasize actual risks in relation to interactions between agents, which can cause memory poisoning. These latter risks are not so much studied in the literature and are difficult to formalize and solve. Thus, we contribute to the construction of agents that are secure by design.
### Title:
          A Unified Family-optimal Solution to Covariance Intersection Problems with Semidefinite Programming
 - **Authors:** Leonardo Pedroso, W. P. M. H. Heemels, Pedro Batista
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Covariance intersection (CI) methods provide a principled approach to fusing estimates with unknown cross-correlations by minimizing a worst-case measure of uncertainty that is consistent with the available information. This paper introduces a generalized CI framework, called overlapping covariance intersection (OCI), which unifies several existing CI formulations within a single optimization-based framework. This unification enables the characterization of family-optimal solutions for multiple CI variants, including standard CI and split covariance intersection (SCI), as solutions to a semidefinite program, for which efficient off-the-shelf solvers are available. When specialized to the corresponding settings, the proposed family-optimal solutions recover the state-of-the-art family-optimal solutions previously reported for CI and SCI. The resulting formulation facilitates the systematic design and real-time implementation of CI-based fusion methods in large-scale distributed estimation problems, such as cooperative localization.
### Title:
          TRGS-SLAM: IMU-Aided Gaussian Splatting SLAM for Blurry, Rolling Shutter, and Noisy Thermal Images
 - **Authors:** Spencer Carmichael, Katherine A. Skinner
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Thermal cameras offer several advantages for simultaneous localization and mapping (SLAM) with mobile robots: they provide a passive, low-power solution to operating in darkness, are invariant to rapidly changing or high dynamic range illumination, and can see through fog, dust, and smoke. However, uncooled microbolometer thermal cameras, the only practical option in most robotics applications, suffer from significant motion blur, rolling shutter distortions, and fixed pattern noise. In this paper, we present TRGS-SLAM, a 3D Gaussian Splatting (3DGS) based thermal inertial SLAM system uniquely capable of handling these degradations. To overcome the challenges of thermal data, we introduce a model-aware 3DGS rendering method and several general innovations to 3DGS SLAM, including B-spline trajectory optimization with a two-stage IMU loss, view-diversity-based opacity resetting, and pose drift correction schemes. Our system demonstrates accurate tracking on real-world, fast motion, and high-noise thermal data that causes all other tested SLAM methods to fail. Moreover, through offline refinement of our SLAM results, we demonstrate thermal image restoration competitive with prior work that required ground truth poses.
### Title:
          RISE: Real-time Image Processing for Spectral Energy Detection and Localization
 - **Authors:** Chung-Hsuan Tung, Zhenzhou Qi, Tingjun Chen
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Energy detection is widely used for spectrum sensing, but accurately localizing the time and frequency occupation of signals in real-time for efficient spectrum sharing remains challenging. To address this challenge, we present RISE, a software-based spectrum sensing system designed for real-time signal detection and localization. RISE treats time-frequency spectrum plots as images and applies adaptive thresholding, morphological operations, and connected component labeling with a multi-threaded architecture. We evaluate RISE using both synthetic data and controlled over-the-air (OTA) experiments across diverse signal types. Results show that RISE satisfies real-time latency constraints while achieving a probability of detection of 80.42% at an intersection-over-union (IoU) threshold of 0.4. RISE sustains a raw I/Q input rate of 3.2 Gbps for 100 MHz bandwidth sensing with time and frequency resolutions of 10.24 us and 97.6 kHz, respectively. Compared to Searchlight, a representative energy-based method, RISE achieves 20.51x lower latency and 22.31% higher IoU. Compared to machine learning baselines, RISE improves IoU by 56.02% over DeepRadar while meeting the real-time deadline, which a GPU-accelerated U-Net exceeds by 213.38x.
### Title:
          Memory Over Maps: 3D Object Localization Without Reconstruction
 - **Authors:** Rui Zhou, Xander Yap, Jianwen Cao, Allison Lau, Boyang Sun, Marc Pollefeys
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Target localization is a prerequisite for embodied tasks such as navigation and manipulation. Conventional approaches rely on constructing explicit 3D scene representations to enable target localization, such as point clouds, voxel grids, or scene graphs. While effective, these pipelines incur substantial mapping time, storage overhead, and scalability limitations. Recent advances in vision-language models suggest that rich semantic reasoning can be performed directly on 2D observations, raising a fundamental question: is a complete 3D scene reconstruction necessary for object localization? In this work, we revisit object localization and propose a map-free pipeline that stores only posed RGB-D keyframes as a lightweight visual memory--without constructing any global 3D representation of the scene. At query time, our method retrieves candidate views, re-ranks them with a vision-language model, and constructs a sparse, on-demand 3D estimate of the queried target through depth backprojection and multi-view fusion. Compared to reconstruction-based pipelines, this design drastically reduces preprocessing cost, enabling scene indexing that is over two orders of magnitude faster to build while using substantially less storage. We further validate the localized targets on downstream object-goal navigation tasks. Despite requiring no task-specific training, our approach achieves strong performance across multiple benchmarks, demonstrating that direct reasoning over image-based scene memory can effectively replace dense 3D reconstruction for object-centric robot navigation. Project page: this https URL
### Title:
          Clinical Cognition Alignment for Gastrointestinal Diagnosis with Multimodal LLMs
 - **Authors:** Huan Zheng, Yucheng Zhou, Tianyi Yan, Dubing Chen, Hongbo Lu, Wenlong Liao, Tao He, Pai Peng, Jianbing Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal Large Language Models (MLLMs) have demonstrated remarkable potential in medical image analysis. However, their application in gastrointestinal endoscopy is currently hindered by two critical limitations: the misalignment between general model reasoning and standardized clinical cognitive pathways, and the lack of causal association between visual features and diagnostic outcomes. In this paper, we propose a novel Clinical-Cognitive-Aligned (CogAlign) framework to address these challenges. First, we endow the model with rigorous clinical analytical capabilities by constructing the hierarchical clinical cognition dataset and employing Supervised Fine-Tuning (SFT). Unlike conventional approaches, this strategy internalizes the hierarchical diagnostic logic of experts, ranging from anatomical localization and morphological evaluation to microvascular analysis, directly into the model. Second, to eliminate visual bias, we provide a theoretical analysis demonstrating that standard supervised tuning inevitably converges to spurious background correlations. Guided by this insight, we propose a counterfactual-driven reinforcement learning strategy to enforce causal rectification. By generating counterfactual normal samples via lesion masking and optimizing through clinical-cognition-centric rewards, we constrain the model to strictly ground its diagnosis in causal lesion features. Extensive experiments demonstrate that our approach achieves State-of-the-Art (SoTA) performance across multiple benchmarks, significantly enhancing diagnostic accuracy in complex clinical scenarios. All source code and datasets will be made publicly available.
### Title:
          PiLoT: Neural Pixel-to-3D Registration for UAV-based Ego and Target Geo-localization
 - **Authors:** Xiaoya Cheng, Long Wang, Yan Liu, Xinyi Liu, Hanlin Tan, Yu Liu, Maojun Zhang, Shen Yan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present PiLoT, a unified framework that tackles UAV-based ego and target geo-localization. Conventional approaches rely on decoupled pipelines that fuse GNSS and Visual-Inertial Odometry (VIO) for ego-pose estimation, and active sensors like laser rangefinders for target localization. However, these methods are susceptible to failure in GNSS-denied environments and incur substantial hardware costs and complexity. PiLoT breaks this paradigm by directly registering live video stream against a geo-referenced 3D map. To achieve robust, accurate, and real-time performance, we introduce three key contributions: 1) a Dual-Thread Engine that decouples map rendering from core localization thread, ensuring both low latency while maintaining drift-free accuracy; 2) a large-scale synthetic dataset with precise geometric annotations (camera pose, depth maps). This dataset enables the training of a lightweight network that generalizes in a zero-shot manner from simulation to real data; and 3) a Joint Neural-Guided Stochastic-Gradient Optimizer (JNGO) that achieves robust convergence even under aggressive motion. Evaluations on a comprehensive set of public and newly collected benchmarks show that PiLoT outperforms state-of-the-art methods while running over 25 FPS on NVIDIA Jetson Orin platform. Our code and dataset is available at: this https URL.
### Title:
          The Anatomy of an Edit: Mechanism-Guided Activation Steering for Knowledge Editing
 - **Authors:** Yuan Cao, Mingyang Wang, Hinrich Schütze
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) are increasingly used as knowledge bases, but keeping them up to date requires targeted knowledge editing (KE). However, it remains unclear how edits are implemented inside the model once applied. In this work, we take a mechanistic view of KE using neuron-level knowledge attribution (NLKA). Unlike prior work that focuses on pre-edit causal tracing and localization, we use post-edit attribution -- contrasting successful and failed edits -- to isolate the computations that shift when an edit succeeds. Across representative KE methods, we find a consistent pattern: mid-to-late attention predominantly promotes the new target, while attention and FFN modules cooperate to suppress the original fact. Motivated by these findings, we propose MEGA, a MEchanism-Guided Activation steering method that performs attention-residual interventions in attribution-aligned regions without modifying model weights. On CounterFact and Popular, MEGA achieves strong editing performance across KE metrics on GPT2-XL and LLaMA2-7B. Overall, our results elevate post-edit attribution from analysis to engineering signal: by pinpointing where and how edits take hold, it powers MEGA to deliver reliable, architecture-agnostic knowledge edits.
### Title:
          PlanaReLoc: Camera Relocalization in 3D Planar Primitives via Region-Based Structure Matching
 - **Authors:** Hanqiao Ye, Yuzhou Liu, Yangdong Liu, Shuhan Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While structure-based relocalizers have long strived for point correspondences when establishing or regressing query-map associations, in this paper, we pioneer the use of planar primitives and 3D planar maps for lightweight 6-DoF camera relocalization in structured environments. Planar primitives, beyond being fundamental entities in projective geometry, also serve as region-based representations that encapsulate both structural and semantic richness. This motivates us to introduce PlanaReLoc, a streamlined plane-centric paradigm where a deep matcher associates planar primitives across the query image and the map within a learned unified embedding space, after which the 6-DoF pose is solved and refined under a robust framework. Through comprehensive experiments on the ScanNet and 12Scenes datasets across hundreds of scenes, our method demonstrates the superiority of planar primitives in facilitating reliable cross-modal structural correspondences and achieving effective camera relocalization without requiring realistically textured/colored maps, pose priors, or per-scene training. The code and data are available at this https URL .
### Title:
          Elite Lanes: Evolutionary Generation of Realistic Small-Scale Road Networks
 - **Authors:** Artur Morys-Magiera, Marek Długosz, Paweł Skruch
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a comparative study of methods for generating realistic, constrained small- to medium-scale road networks with built-in redundancy. In this research, we evaluate the proposed Evolutionary Algorithm (EA) with connectivity and redundancy constraints against the Wave Function Collapse (WFC) method - commonly used in procedural terrain generation for games - and swarm algorithms: Particle Swarm (PSO) and Gray Wolf (GWO). Our focus is on producing realistic, redundant road networks suitable for vision, localization and navigation problems. We evaluate metrics: connectivity, cycles, intersections, dead ends, graph cut-edges while enforcing physical plausibility. We propose an EA and its extended version with elitism via MAP-Elites method. We detail the implementation, constraints, metrics and provide both visual and quantitative comparisons with baselines. Results highlight how fitness function design choices affect the structural characteristics of generated networks and highlight the impact of specific constraints in practical applications. Our contribution is a method for creating realistic synthetic datasets from sparse tile definitions derived from real-world data. We demonstrate a practical application by generating realistic maps using a laboratory-collected tileset from a Duckietown city model. Our approach performs coherent geometric transformations on metadata, in this work exemplified by semantic segmentation masks of the generated road networks.
### Title:
          Deep Attention-based Sequential Ensemble Learning for BLE-Based Indoor Localization in Care Facilities
 - **Authors:** Minh Triet Pham, Quynh Chi Dang, Le Nhat Tan
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Indoor localization systems in care facilities enable optimization of staff allocation, workload management, and quality of care delivery. Traditional machine learning approaches to Bluetooth Low Energy (BLE)-based localization treat each temporal measurement as an independent observation, fundamentally limiting their performance. To address this limitation, this paper introduces Deep Attention-based Sequential Ensemble Learning (DASEL), a novel framework that reconceptualizes indoor localization as a sequential learning problem. The framework integrates frequency-based feature engineering, bidirectional GRU networks with attention mechanisms, multi-directional sliding windows, and confidence-weighted temporal smoothing to capture human movement trajectories. Evaluated on real-world data from a care facility using 4-fold temporal cross-validation, DASEL achieves a macro F1 score of 0.4438, representing a 53.1% improvement over the best traditional baseline (0.2898).
### Title:
          A Two-stage Transformer Framework for Temporal Localization of Distracted Driver Behaviors
 - **Authors:** Gia-Bao Doan, Nam-Khoa Huynh, Minh-Nhat-Huy Ho, Khanh-Thanh-Khoa Nguyen, Thanh-Hai Le
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The identification of hazardous driving behaviors from in-cabin video streams is essential for enhancing road safety and supporting the detection of traffic violations and unsafe driver actions. However, current temporal action localization techniques often struggle to balance accuracy with computational efficiency. In this work, we develop and evaluate a temporal action localization framework tailored for driver monitoring scenarios, particularly suitable for periodic inspection settings such as transportation safety checkpoints or fleet management assessment systems. Our approach follows a two-stage pipeline that combines VideoMAE-based feature extraction with an Augmented Self-Mask Attention (AMA) detector, enhanced by a Spatial Pyramid Pooling-Fast (SPPF) module to capture multi-scale temporal features. Experimental results reveal a distinct trade-off between model capacity and efficiency. At the feature extraction stage, the ViT-Giant backbone delivers higher representations with 88.09% Top-1 test accuracy, while the ViT-based variant proves to be a practical alternative, achieving 82.55% accuracy with significantly lower computational fine-tuning costs (101.85 GFLOPs/segment compared to 1584.06 GFLOPs/segment for Giant). In the downstream localization task, the integration of SPPF consistently improves performance across all configurations. Notably, the ViT-Giant + SPPF model achieves a peak mAP of 92.67%, while the lightweight ViT-based configuration maintains robust results.
### Title:
          DSCSNet: A Dynamic Sparse Compression Sensing Network for Closely-Spaced Infrared Small Target Unmixing
 - **Authors:** Zhiyang Tang, Yiming Zhu, Ruimin Huang, Meng Yang, Yong Ma, Jun Huang, Fan Fan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Due to the limitations of optical lens focal length and detector resolution, distant clustered infrared small targets often appear as mixed spots. The Close Small Object Unmixing (CSOU) task aims to recover the number, sub-pixel positions, and radiant intensities of individual targets from these spots, which is a highly ill-posed inverse problem. Existing methods struggle to balance the rigorous sparsity guarantees of model-driven approaches and the dynamic scene adaptability of data-driven methods. To address this dilemma, this paper proposes a Dynamic Sparse Compressed Sensing Network (DSCSNet), a deep-unfolded network that couples the Alternating Direction Method of Multipliers (ADMM) with learnable parameters. Specifically, we embed a strict $\ell_1$-norm sparsity constraint into the auxiliary variable update step of ADMM to replace the traditional $\ell_2$-norm smoothness-promoting terms, which effectively preserves the discrete energy peaks of small targets. We also integrate a self-attention-based dynamic thresholding mechanism into the reconstruction stage, which adaptively adjusts the sparsification intensity using the sparsity-enhanced information from the iterative process. These modules are jointly optimized end-to-end across the three iterative steps of ADMM. Retaining the physical logic of compressed sensing, DSCSNet achieves robust sparsity induction and scene adaptability, thus enhancing the unmixing accuracy and generalization in complex infrared scenarios. Extensive experiments on the synthetic infrared dataset CSIST-100K demonstrate that DSCSNet outperforms state-of-the-art methods in key metrics such as CSO-mAP and sub-pixel localization error.
### Title:
          Boundary-Aware Instance Segmentation in Microscopy Imaging
 - **Authors:** Thomas Mendelson, Joshua Francois, Galit Lahav, Tammy Riklin-Raviv
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate delineation of individual cells in microscopy videos is essential for studying cellular dynamics, yet separating touching or overlapping instances remains a persistent challenge. Although foundation-model for segmentation such as SAM have broadened the accessibility of image segmentation, they still struggle to separate nearby cell instances in dense microscopy scenes without extensive prompting. We propose a prompt-free, boundary-aware instance segmentation framework that predicts signed distance functions (SDFs) instead of binary masks, enabling smooth and geometry-consistent modeling of cell contours. A learned sigmoid mapping converts SDFs into probability maps, yielding sharp boundary localization and robust separation of adjacent instances. Training is guided by a unified Modified Hausdorff Distance (MHD) loss that integrates region- and boundary-based terms. Evaluations on both public and private high-throughput microscopy datasets demonstrate improved boundary accuracy and instance-level performance compared to recent SAM-based and foundation-model approaches. Source code is available at: this https URL
### Title:
          Focus on Background: Exploring SAM's Potential in Few-shot Medical Image Segmentation with Background-centric Prompting
 - **Authors:** Yuntian Bo, Yazhou Zhu, Piotr Koniusz, Haofeng Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Conventional few-shot medical image segmentation (FSMIS) approaches face performance bottlenecks that hinder broader clinical applicability. Although the Segment Anything Model (SAM) exhibits strong category-agnostic segmentation capabilities, its direct application to medical images often leads to over-segmentation due to ambiguous anatomical boundaries. In this paper, we reformulate SAM-based FSMIS as a prompt localization task and propose FoB (Focus on Background), a background-centric prompt generator that provides accurate background prompts to constrain SAM's over-segmentation. Specifically, FoB bridges the gap between segmentation and prompt localization by category-agnostic generation of support background prompts and localizing them directly in the query image. To address the challenge of prompt localization for novel categories, FoB models rich contextual information to capture foreground-background spatial dependencies. Moreover, inspired by the inherent structural patterns of background prompts in medical images, FoB models this structure as a constraint to progressively refine background prompt predictions. Experiments on three diverse medical image datasets demonstrate that FoB outperforms other baselines by large margins, achieving state-of-the-art performance on FSMIS, and exhibiting strong cross-domain generalization. Our code is available at this https URL.
### Title:
          Parameter-efficient Prompt Tuning and Hierarchical Textual Guidance for Few-shot Whole Slide Image Classification
 - **Authors:** Jayanie Bogahawatte, Sachith Seneviratne, Saman Halgamuge
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Whole Slide Images (WSIs) are giga-pixel in scale and are typically partitioned into small instances in WSI classification pipelines for computational feasibility. However, obtaining extensive instance level annotations is costly, making few-shot weakly supervised WSI classification (FSWC) crucial for learning from limited slide-level labels. Recently, pre-trained vision-language models (VLMs) have been adopted in FSWC, yet they exhibit several limitations. Existing prompt tuning methods in FSWC substantially increase both the number of trainable parameters and inference overhead. Moreover, current methods discard instances with low alignment to text embeddings from VLMs, potentially leading to information loss. To address these challenges, we propose two key contributions. First, we introduce a new parameter efficient prompt tuning method by scaling and shifting features in text encoder, which significantly reduces the computational cost. Second, to leverage not only the pre-trained knowledge of VLMs, but also the inherent hierarchical structure of WSIs, we introduce a WSI representation learning approach with a soft hierarchical textual guidance strategy without utilizing hard instance filtering. Comprehensive evaluations on pathology datasets covering breast, lung, and ovarian cancer types demonstrate consistent improvements up-to 10.9%, 7.8%, and 13.8% respectively, over the state-of-the-art methods in FSWC. Our method reduces the number of trainable parameters by 18.1% on both breast and lung cancer datasets, and 5.8% on the ovarian cancer dataset, while also excelling at weakly-supervised tumor localization. Code at this https URL.
### Title:
          VIGIL: Part-Grounded Structured Reasoning for Generalizable Deepfake Detection
 - **Authors:** Xinghan Li, Junhao Xu, Jingjing Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal large language models (MLLMs) offer a promising path toward interpretable deepfake detection by generating textual explanations. However, the reasoning process of current MLLM-based methods combines evidence generation and manipulation localization into a unified step. This combination blurs the boundary between faithful observations and hallucinated explanations, leading to unreliable conclusions. Building on this, we present VIGIL, a part-centric structured forensic framework inspired by expert forensic practice through a plan-then-examine pipeline: the model first plans which facial parts warrant inspection based on global visual cues, then examines each part with independently sourced forensic evidence. A stage-gated injection mechanism delivers part-level forensic evidence only during examination, ensuring that part selection remains driven by the model's own perception rather than biased by external signals. We further propose a progressive three-stage training paradigm whose reinforcement learning stage employs part-aware rewards to enforce anatomical validity and evidence--conclusion coherence. To enable rigorous generalizability evaluation, we construct OmniFake, a hierarchical 5-Level benchmark where the model, trained on only three foundational generators, is progressively tested up to in-the-wild social-media data. Extensive experiments on OmniFake and cross-dataset evaluations demonstrate that VIGIL consistently outperforms both expert detectors and concurrent MLLM-based methods across all generalizability levels.
### Title:
          PGR-Net: Prior-Guided ROI Reasoning Network for Brain Tumor MRI Segmentation
 - **Authors:** Jiacheng Lu, Hui Ding, Shiyu Zhang, Guoping Huo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Brain tumor MRI segmentation is essential for clinical diagnosis and treatment planning, enabling accurate lesion detection and radiotherapy target delineation. However, tumor lesions occupy only a small fraction of the volumetric space, resulting in severe spatial sparsity, while existing segmentation networks often overlook clinically observed spatial priors of tumor occurrence, leading to redundant feature computation over extensive background regions. To address this issue, we propose PGR-Net (Prior-Guided ROI Reasoning Network) - an explicit ROI-aware framework that incorporates a data-driven spatial prior set to capture the distribution and scale characteristics of tumor lesions, providing global guidance for more stable segmentation. Leveraging these priors, PGR-Net introduces a hierarchical Top-K ROI decision mechanism that progressively selects the most confident lesion candidate regions across encoder layers to improve localization precision. We further develop the WinGS-ROI (Windowed Gaussian-Spatial Decay ROI) module, which uses multi-window Gaussian templates with a spatial decay function to produce center-enhanced guidance maps, thus directing feature learning throughout the network. With these ROI features, a windowed RetNet backbone is adopted to enhance localization reliability. Experiments on BraTS-2019/2023 and MSD Task01 show that PGR-Net consistently outperforms existing approaches while using only 8.64M Params, achieving Dice scores of 89.02%, 91.82%, and 89.67% on the Whole Tumor region. Code is available at this https URL.
### Title:
          No Dense Tensors Needed: Fully Sparse Object Detection on Event-Camera Voxel Grids
 - **Authors:** Mohamad Yazan Sadoun, Sarah Sharif, Yaser Mike Banad
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Event cameras produce asynchronous, high-dynamic-range streams well suited for detecting small, fast-moving drones, yet most event-based detectors convert the sparse event stream into dense tensors, discarding the representational efficiency of neuromorphic sensing. We propose SparseVoxelDet, to our knowledge the first fully sparse object detector for event cameras, in which backbone feature extraction, feature pyramid fusion, and the detection head all operate exclusively on occupied voxel positions through 3D sparse convolutions; no dense feature tensor is instantiated at any stage of the pipeline. On the FRED benchmark (629,832 annotated frames), SparseVoxelDet achieves 83.38% mAP at 50 while processing only 14,900 active voxels per frame (0.23% of the T.H.W grid), compared to 409,600 pixels for the dense YOLOv11 baseline (87.68% mAP at 50). Relaxing the IoU threshold from 0.50 to 0.40 recovers mAP to 89.26%, indicating that the remaining accuracy gap is dominated by box regression precision rather than detection capability. The sparse representation yields 858 times GPU memory compression and 3,670 times storage reduction relative to the equivalent dense 3D voxel tensor, with data-structure size that scales with scene dynamics rather than sensor resolution. Error forensics across 119,459 test frames confirms that 71 percent of failures are localization near-misses rather than missed targets. These results demonstrate that native sparse processing is a viable paradigm for event-camera object detection, exploiting the structural sparsity of neuromorphic sensor data without requiring neuromorphic computing hardware, and providing a framework whose representation cost is governed by scene activity rather than pixel count, a property that becomes increasingly valuable as event cameras scale to higher resolutions.
### Title:
          HumanOmni-Speaker: Identifying Who said What and When
 - **Authors:** Detao Bai, Shimin Yao, Weixuan Chen, Xihan Wei, Zhiheng Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Omni-modal Large Language Models have made strides in joint sensory processing, they fundamentally struggle with a cornerstone of human interaction: deciphering complex, multi-person conversational dynamics to accurately answer ``Who said what and when.'' Current models suffer from an ``illusion of competence'' -- they exploit visual biases in conventional benchmarks to bypass genuine cross-modal alignment, while relying on sparse, low-frame-rate visual sampling that destroys crucial high-frequency dynamics like lip movements. To shatter this illusion, we introduce Visual-Registered Speaker Diarization and Recognition (VR-SDR) and the HumanOmni-Speaker Benchmark. By strictly eliminating visual shortcuts, this rigorous paradigm demands true end-to-end spatio-temporal identity binding using only natural language queries. To overcome the underlying architectural perception gap, we propose HumanOmni-Speaker, powered by a Visual Delta Encoder. By sampling raw video at 25 fps and explicitly compressing inter-frame motion residuals into just 6 tokens per frame, it captures fine-grained visemes and speaker trajectories without triggering a catastrophic token explosion. Ultimately, HumanOmni-Speaker demonstrates strong multimodal synergy, natively enabling end-to-end lip-reading and high-precision spatial localization without intrusive cropping, and achieving superior performance across a wide spectrum of speaker-centric tasks.
### Title:
          GeoFlow: Real-Time Fine-Grained Cross-View Geolocalization via Iterative Flow Prediction
 - **Authors:** Ayesh Abu Lehyeh, Xiaohan Zhang, Ahmad Arrabi, Waqas Sultani, Chen Chen, Safwan Wshah
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate and fast localization is vital for safe autonomous navigation in GPS-denied areas. Fine-Grained Cross-View Geolocalization (FG-CVG) aims to estimate the precise 2-Degree-of-Freedom (2-DoF) location of a ground image relative to a satellite image. However, current methods force a difficult trade-off, with high-accuracy models being slow for real-time use. In this paper, we introduce GeoFlow, a new approach that offers a lightweight and highly efficient framework that breaks this accuracy-speed trade-off. Our technique learns a direct probabilistic mapping, predicting the displacement (in distance and direction) required to correct any given location hypothesis. This is complemented by our novel inference algorithm, Iterative Refinement Sampling (IRS). Instead of trusting a single prediction, IRS refines a population of hypotheses, allowing them to iteratively 'flow' from random starting points to a robust, converged consensus. Even its iterative nature, this approach offers flexible inference-time scaling, allowing a direct trade-off between performance and computation without any re-training. Experiments on the KITTI and VIGOR datasets show that GeoFlow achieves state-of-the-art efficiency, running at real-time speeds of 29 FPS while maintaining competitive localization accuracy. This work opens a new path for the development of practical real-time geolocalization systems.
### Title:
          Beyond Matching to Tiles: Bridging Unaligned Aerial and Satellite Views for Vision-Only UAV Navigation
 - **Authors:** Kejia Liu, Haoyang Zhou, Ruoyu Xu, Peicheng Wang, Mingli Song, Haofei Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in cross-view geo-localization (CVGL) methods have shown strong potential for supporting unmanned aerial vehicle (UAV) navigation in GNSS-denied environments. However, existing work predominantly focuses on matching UAV views to onboard map tiles, which introduces an inherent trade-off between accuracy and storage overhead, and overlooks the importance of the UAV's heading during navigation. Moreover, the substantial discrepancies and varying overlaps in cross-view scenarios have been insufficiently considered, limiting their generalization to real-world scenarios. In this paper, we present Bearing-UAV, a purely vision-driven cross-view navigation method that jointly predicts UAV absolute location and heading from neighboring features, enabling accurate, lightweight, and robust navigation in the wild. Our method leverages global and local structural features and explicitly encodes relative spatial relationships, making it robust to cross-view variations, misalignment, and feature-sparse conditions. We also present Bearing-UAV-90k, a multi-city benchmark for evaluating cross-view localization and navigation. Extensive experiments show encouraging results that Bearing-UAV yields lower localization error than previous matching/retrieval paradigm across diverse terrains. Our code and dataset will be made publicly available.
### Title:
          VideoDetective: Clue Hunting via both Extrinsic Query and Intrinsic Relevance for Long Video Understanding
 - **Authors:** Ruoliu Yang, Chu Wu, Caifeng Shan, Ran He, Chaoyou Fu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long video understanding remains challenging for multimodal large language models (MLLMs) due to limited context windows, which necessitate identifying sparse query-relevant video segments. However, existing methods predominantly localize clues based solely on the query, overlooking the video's intrinsic structure and varying relevance across segments. To address this, we propose VideoDetective, a framework that integrates query-to-segment relevance and inter-segment affinity for effective clue hunting in long-video question answering. Specifically, we divide a video into various segments and represent them as a visual-temporal affinity graph built from visual similarity and temporal proximity. We then perform a Hypothesis-Verification-Refinement loop to estimate relevance scores of observed segments to the query and propagate them to unseen segments, yielding a global relevance distribution that guides the localization of the most critical segments for final answering with sparse observation. Experiments show our method consistently achieves substantial gains across a wide range of mainstream MLLMs on representative benchmarks, with accuracy improvements of up to 7.5% on VideoMME-long. Our code is available at this https URL
## Keyword: transformer
### Title:
          Linguistic Signatures for Enhanced Emotion Detection
 - **Authors:** Florian Lecourt (LIRMM | ADVANSE), Madalina Croitoru (LIRMM), Konstantin Todorov (WEB3)
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Emotion detection is a central problem in NLP, with recent progress driven by transformer-based models trained on established datasets. However, little is known about the linguistic regularities that characterize how emotions are expressed across different corpora and labels. This study examines whether linguistic features can serve as reliable interpretable signals for emotion recognition in text. We extract emotion-specific linguistic signatures from 13 English datasets and evaluate how incorporating these features into transformer models impacts performance. Our RoBERTa-based models enriched with high level linguistic features achieve consistent performance gains of up to +2.4 macro F1 on the GoEmotions benchmark, showing that explicit lexical cues can complement neural representations and improve robustness in predicting emotion categories.
### Title:
          Beyond Test-Time Compute Strategies: Advocating Energy-per-Token in LLM Inference
 - **Authors:** Patrick Wilhelm, Thorsten Wittkopp, Odej Kao
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) demonstrate exceptional performance across diverse tasks but come with substantial energy and computational costs, particularly in request-heavy scenarios. In many real-world applications, the full scale and capabilities of LLMs are often unnecessary, as Small Language Models (SLMs) can provide accurate responses for simpler text generation tasks. When enhanced with advanced reasoning strategies, such as Chain-of-Thought (CoT) prompting or Majority Voting, SLMs can approach the performance of larger models while reducing overall computational requirements. However, these strategies can also introduce additional energy costs, creating an energy-accuracy trade-off. Our analysis examines these trade-offs in test-time compute strategies for smaller models compared to larger ones, using the MMLU benchmark. Additionally, we explore the input-output token dynamics of transformer architectures, which result in nonlinear hardware energy operation curves for LLMs. To bridge AI research with its physical impact, we propose \textit{energy efficiency metrics}, including Energy-per-Token, as complements to traditional accuracy benchmarks. Beyond model selection, we propose controlled reasoning in CoT token generation, using operating curves to regulate reasoning depth dynamically. This vision integrates a energy-aware routing mechanism, ensuring that model selection and inference strategies balance accuracy for sustainable AI deployment.
### Title:
          Decoding the decoder: Contextual sequence-to-sequence modeling for intracortical speech decoding
 - **Authors:** Michal Olak, Tommaso Boccato, Matteo Ferrante
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Neural and Evolutionary Computing (cs.NE); Neurons and Cognition (q-bio.NC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Speech brain--computer interfaces require decoders that translate intracortical activity into linguistic output while remaining robust to limited data and day-to-day variability. While prior high-performing systems have largely relied on framewise phoneme decoding combined with downstream language models, it remains unclear what contextual sequence-to-sequence decoding contributes to sublexical neural readout, robustness, and interpretability. We evaluated a multitask Transformer-based sequence-to-sequence model for attempted speech decoding from area 6v intracortical recordings. The model jointly predicts phoneme sequences, word sequences, and auxiliary acoustic features. To address day-to-day nonstationarity, we introduced the Neural Hammer Scalpel (NHS) calibration module, which combines global alignment with feature-wise modulation. We further analyzed held-out-day generalization and attention patterns in the encoder and decoders. On the Willett et al. dataset, the proposed model achieved a state-of-the-art phoneme error rate of 14.3%. Word decoding reached 25.6% WER with direct decoding and 19.4% WER with candidate generation and rescoring. NHS substantially improved both phoneme and word decoding relative to linear or no day-specific transform, while held-out-day experiments showed increasing degradation on unseen days with temporal distance. Attention visualizations revealed recurring temporal chunking in encoder representations and distinct use of these segments by phoneme and word decoders. These results indicate that contextual sequence-to-sequence modeling can improve the fidelity of neural-to-phoneme readout from intracortical speech signals and suggest that attention-based analyses can generate useful hypotheses about how neural speech evidence is segmented and accumulated over time.
### Title:
          Understanding Pruning Regimes in Vision-Language Models Through Domain-Aware Layer Selection
 - **Authors:** Saeed Khaki, Nima Safaei, Kamal Ginotra
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based vision-language models (VLMs) contain substantial depth redundancy, yet the effect of removing specific decoder layers remains poorly understood, especially for domains that require tight coupling between perception and multi-step reasoning. We study structured decoder layer pruning through the lens of domain-aware activation similarity, measuring how strongly each layer transforms representations for math versus non-math inputs. This yields simple math-aware, non-math-aware, and mixed ranking criteria that identify layers whose input-output activations change least within a target domain. Across two state-of-the-art VLMs and a broad suite of math and general multimodal benchmarks, we uncover a consistent three-regime structure: at low pruning budgets, performance is highly sensitive to which layers are removed; at moderate budgets, methods converge as structural damage accumulates; and at high budgets, structural continuity dominates, favoring spacing-aware strategies. Our domain-aware rankings achieve the strongest stability in the ranking-sensitive regime, while matching or exceeding structure-aware baselines at larger budgets. These results provide a clearer picture of how depth contributes to domain-specific behavior in VLMs and offer a practical, interpretable approach to reducing model depth without sacrificing essential mathematical or general vision-language capabilities.
### Title:
          Mix-and-Match Pruning: Globally Guided Layer-Wise Sparsification of DNNs
 - **Authors:** Danial Monachan, Samira Nazari, Mahdi Taheri, Ali Azarpeyvand, Milos Krstic, Michael Huebner, Christian Herglotz
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Hardware Architecture (cs.AR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deploying deep neural networks (DNNs) on edge devices requires strong compression with minimal accuracy loss. This paper introduces Mix-and-Match Pruning, a globally guided, layer-wise sparsification framework that leverages sensitivity scores and simple architectural rules to generate diverse, high-quality pruning configurations. The framework addresses a key limitation that different layers and architectures respond differently to pruning, making single-strategy approaches suboptimal. Mix-and-Match derives architecture-aware sparsity ranges, e.g., preserving normalization layers while pruning classifiers more aggressively, and systematically samples these ranges to produce ten strategies per sensitivity signal (magnitude, gradient, or their combination). This eliminates repeated pruning runs while offering deployment-ready accuracy-sparsity trade-offs. Experiments on CNNs and Vision Transformers demonstrate Pareto-optimal results, with Mix-and-Match reducing accuracy degradation on Swin-Tiny by 40% relative to standard single-criterion pruning. These findings show that coordinating existing pruning signals enables more reliable and efficient compressed models than introducing new criteria.
### Title:
          STAC: Plug-and-Play Spatio-Temporal Aware Cache Compression for Streaming 3D Reconstruction
 - **Authors:** Runze Wang, Yuxuan Song, Youcheng Cai, Ligang Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Online 3D reconstruction from streaming inputs requires both long-term temporal consistency and efficient memory usage. Although causal VGGT transformers address this challenge through a key-value (KV) cache mechanism, the cache grows linearly with the stream length, creating a major memory bottleneck. Under limited memory budgets, early cache eviction significantly degrades reconstruction quality and temporal consistency. In this work, we observe that attention in causal transformers for 3D reconstruction exhibits intrinsic spatio-temporal sparsity. Based on this insight, we propose STAC, a Spatio-Temporally Aware Cache Compression framework for streaming 3D reconstruction with large causal transformers. STAC consists of three key components: (1) a Working Temporal Token Caching mechanism that preserves long-term informative tokens using decayed cumulative attention scores; (2) a Long-term Spatial Token Caching scheme that compresses spatially redundant tokens into voxel-aligned representations for memory-efficient storage; and (3) a Chunk-based Multi-frame Optimization strategy that jointly processes consecutive frames to improve temporal coherence and GPU efficiency. Extensive experiments show that STAC achieves state-of-the-art reconstruction quality while reducing memory consumption by nearly 10x and accelerating inference by 4x, substantially improving the scalability of real-time 3D reconstruction in streaming settings.
### Title:
          Remote Sensing Image Dehazing: A Systematic Review of Progress, Challenges, and Prospects
 - **Authors:** Heng Zhou, Xiaoxiong Liu, Zhenxi Zhang, Jieheng Yun, Chengyang Li, Yunchu Yang, Dongyi Xia, Chunna Tian, Xiao-Jun Wu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Remote sensing images (RSIs) are frequently degraded by haze, fog, and thin clouds, which obscure surface reflectance and hinder downstream applications. This study presents the first systematic and unified survey of RSIs dehazing, integrating methodological evolution, benchmark assessment, and physical consistency analysis. We categorize existing approaches into a three-stage progression: from handcrafted physical priors, to data-driven deep restoration, and finally to hybrid physical-intelligent generation, and summarize more than 30 representative methods across CNNs, GANs, Transformers, and diffusion models. To provide a reliable empirical reference, we conduct large-scale quantitative experiments on five public datasets using 12 metrics, including PSNR, SSIM, CIEDE, LPIPS, FID, SAM, ERGAS, UIQI, QNR, NIQE, and HIST. Cross-domain comparison reveals that recent Transformer- and diffusion-based models improve SSIM by 12%~18% and reduce perceptual errors by 20%~35% on average, while hybrid physics-guided designs achieve higher radiometric stability. A dedicated physical radiometric consistency experiment further demonstrates that models with explicit transmission or airlight constraints reduce color bias by up to 27%. Based on these findings, we summarize open challenges: dynamic atmospheric modeling, multimodal fusion, lightweight deployment, data scarcity, and joint degradations, and outline promising research directions for future development of trustworthy, controllable, and efficient (TCE) dehazing systems. All reviewed resources, including source code, benchmark datasets, evaluation metrics, and reproduction configurations are publicly available at this https URL.
### Title:
          Transformer-Based Predictive Maintenance for Risk-Aware Instrument Calibration
 - **Authors:** Adithya Parthasarathy, Aswathnarayan Muthukrishnan Kirubakaran, Akshay Deshpande, Ram Sekhar Bodala, Suhas Malempati, Nachiappan Chockalingam, Vinoth Punniyamoorthy, Seema Gangaiah Aarella
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate calibration is essential for instruments whose measurements must remain traceable, reliable, and compliant over long operating periods. Fixed-interval programs are easy to administer, but they ignore that instruments drift at different rates under different conditions. This paper studies calibration scheduling as a predictive maintenance problem: given recent sensor histories, estimate time-to-drift (TTD) and intervene before a violation occurs. We adapt the NASA C-MAPSS benchmark into a calibration setting by selecting drift-sensitive sensors, defining virtual calibration thresholds, and inserting synthetic reset events that emulate repeated recalibration. We then compare classical regressors, recurrent and convolutional sequence models, and a compact Transformer for TTD prediction. The Transformer provides the strongest point forecasts on the primary FD001 split and remains competitive on the harder FD002--FD004 splits, while a quantile-based uncertainty model supports conservative scheduling when drift behavior is noisier. Under a violation-aware cost model, predictive scheduling lowers cost relative to reactive and fixed policies, and uncertainty-aware triggers sharply reduce violations when point forecasts are less reliable. The results show that condition-based calibration can be framed as a joint forecasting and decision problem, and that combining sequence models with risk-aware policies is a practical route toward smarter calibration planning.
### Title:
          Reason-to-Transmit: Deliberative Adaptive Communication for Cooperative Perception
 - **Authors:** Aayam Bansal, Ishaan Gangwani
 - **Subjects:** Subjects:
Multiagent Systems (cs.MA); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cooperative perception among autonomous agents overcomes the limitations of single-agent sensing, but bandwidth constraints in vehicle-to-everything (V2X) networks require efficient communication policies. Existing approaches rely on reactive mechanisms, such as confidence maps, learned gating, or sparse masks, to decide what to transmit, without reasoning about why a message benefits the receiver. We introduce Reason-to-Transmit (R2T), a framework that equips each agent with a lightweight transformer-based module that reasons over local scene context, estimated neighbor information gaps, and bandwidth budget to make per-region transmission decisions. Trained end-to-end with a bandwidth-aware objective, R2T is evaluated against nine baselines in a multi-agent bird's-eye-view perception environment. Any communication improves performance by about 58% AP over no communication. At low bandwidth, all selective methods perform similarly, but R2T shows clear gains under high occlusion, where information asymmetry is greatest, approaching oracle performance. All methods degrade gracefully under packet drops up to 50%, showing robustness to communication failures. These results indicate that while fusion design dominates performance, deliberative communication provides additional gains in challenging scenarios. R2T introduces a reasoning-based approach to communication, enabling more efficient and context-aware information sharing in cooperative perception.
### Title:
          GraphiContact: Pose-aware Human-Scene Robust Contact Perception for Interactive Systems
 - **Authors:** Xiaojian Lin, Yaomin Shen, Junyuan Ma, Yujie Sun, Chengqing Bu, Wenxin Zhang, Zongzheng Zhang, Hao Fei, Lei Jin, Hao Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular vertex-level human-scene contact prediction is a fundamental capability for interactive systems such as assistive monitoring, embodied AI, and rehabilitation analysis. In this work, we study this task jointly with single-image 3D human mesh reconstruction, using reconstructed body geometry as a scaffold for contact reasoning. Existing approaches either focus on contact prediction without sufficiently exploiting explicit 3D human priors, or emphasize pose/mesh reconstruction without directly optimizing robust vertex-level contact inference under occlusion and perceptual noise. To address this gap, we propose GraphiContact, a pose-aware framework that transfers complementary human priors from two pretrained Transformer encoders and predicts per-vertex human-scene contact on the reconstructed mesh. To improve robustness in real-world scenarios, we further introduce a Single-Image Multi-Infer Uncertainty (SIMU) training strategy with token-level adaptive routing, which simulates occlusion and noisy observations during training while preserving efficient single-branch inference at test time. Experiments on five benchmark datasets show that GraphiContact achieves consistent gains on both contact prediction and 3D human reconstruction. Our code, based on the GraphiContact method, provides comprehensive 3D human reconstruction and interaction analysis, and will be publicly available at this https URL.
### Title:
          Toward a Multi-View Brain Network Foundation Model: Cross-View Consistency Learning Across Arbitrary Atlases
 - **Authors:** Jiaxing Xu, Jingying Ma, Xin Lin, Yuxiao Liu, Kai He, Qika Lin, Yiping Ke, Yang Li, Dinggang Shen, Mengling Feng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Brain network analysis provides an interpretable framework for characterizing brain organization and has been widely used for neurological disorder identification. Recent advances in self-supervised learning have motivated the development of brain network foundation models. However, existing approaches are often limited by atlas dependency, insufficient exploitation of multiple network views, and weak incorporation of anatomical priors. In this work, we propose MV-BrainFM, a multi-view brain network foundation model designed to learn generalizable and scalable representations from brain networks constructed with arbitrary atlases. MV-BrainFM explicitly incorporates anatomical distance information into Transformer-based modeling to guide inter-regional interactions, and introduces an unsupervised cross-view consistency learning strategy to align representations from multiple atlases of the same subject in a shared latent space. By jointly enforcing within-view robustness and cross-view alignment during pretraining, the model effectively captures complementary information across heterogeneous network views while remaining atlas-aware. In addition, MV-BrainFM adopts a unified multi-view pretraining paradigm that enables simultaneous learning from multiple datasets and atlases, significantly improving computational efficiency compared to conventional sequential training strategies. The proposed framework also demonstrates strong scalability, consistently benefiting from increasing data diversity while maintaining stable performance across unseen atlas configurations. Extensive experiments on more than 20K subjects from 17 fMRI datasets show that MV-BrainFM consistently outperforms 14 existing brain network foundation models and task-specific baselines under both single-atlas and multi-atlas settings.
### Title:
          SymCircuit: Bayesian Structure Inference for Tractable Probabilistic Circuits via Entropy-Regularized Reinforcement Learning
 - **Authors:** Y. Sungtaek Ju
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Probabilistic circuit (PC) structure learning is hampered by greedy algorithms that make irreversible, locally optimal decisions. We propose SymCircuit, which replaces greedy search with a learned generative policy trained via entropy-regularized reinforcement learning. Instantiating the RL-as-inference framework in the PC domain, we show the optimal policy is a tempered Bayesian posterior, recovering the exact posterior when the regularization temperature is set inversely proportional to the dataset size. The policy is implemented as SymFormer, a grammar-constrained autoregressive Transformer with tree-relative self-attention that guarantees valid circuits at every generation step. We introduce option-level REINFORCE, restricting gradient updates to structural decisions rather than all tokens, yielding an SNR (signal to noise ratio) improvement and >10 times sample efficiency gain on the NLTCS dataset. A three-layer uncertainty decomposition (structural via model averaging, parametric via the delta method, leaf via conjugate Dirichlet-Categorical propagation) is grounded in the multilinear polynomial structure of PC outputs. On NLTCS, SymCircuit closes 93% of the gap to LearnSPN; preliminary results on Plants (69 variables) suggest scalability.
### Title:
          KV Cache Optimization Strategies for Scalable and Efficient LLM Inference
 - **Authors:** Yichun Xu, Navjot K. Khaira, Tejinder Singh
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The key-value (KV) cache is a foundational optimization in Transformer-based large language models (LLMs), eliminating redundant recomputation of past token representations during autoregressive generation. However, its memory footprint scales linearly with context length, imposing critical bottlenecks on GPU memory capacity, memory bandwidth, and inference throughput as production LLMs push context windows from thousands to millions of tokens. Efficient KV cache management has thus become a first-order challenge for scalable LLM deployment. This paper provides a systematic review of recent KV cache optimization techniques, organizing them into five principal directions: cache eviction, cache compression, hybrid memory solutions, novel attention mechanisms, and combination strategies. For each category we analyze the underlying mechanisms, deployment trade-offs, and empirical performance across memory reduction, throughput, and model accuracy metrics. We further map techniques to seven practical deployment scenarios, including long-context single requests, high-throughput datacenter serving, edge devices, multi-turn conversations, and accuracy-critical reasoning, providing actionable guidance for practitioners selecting among competing approaches. Our analysis reveals that no single technique dominates across all settings; instead, the optimal strategy depends on context length, hardware constraints, and workload characteristics, pointing toward adaptive, multi-stage optimization pipelines as a promising direction for future research.
### Title:
          Leveraging Natural Language Processing and Machine Learning for Evidence-Based Food Security Policy Decision-Making in Data-Scarce Making
 - **Authors:** Karan Kumar Singh, Nikita Gajbhiye
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Food security policy formulation in data-scarce regions remains a critical challenge due to limited structured datasets, fragmented textual reports, and demographic bias in decision-making systems. This study proposes ZeroHungerAI, an integrated Natural Language Processing (NLP) and Machine Learning (ML) framework designed for evidence-based food security policy modeling under extreme data scarcity. The system combines structured socio-economic indicators with contextual policy text embeddings using a transfer learning based DistilBERT architecture. Experimental evaluation on a 1200-sample hybrid dataset across 25 districts demonstrates superior predictive performance, achieving 91 percent classification accuracy, 0.89 precision, 0.85 recall, and an F1 score of 0.86 under imbalanced conditions. Comparative analysis shows a 13 percent performance improvement over classical SVM and 17 percent over Logistic Regression models. Precision Recall evaluation confirms robust minority class detection (average precision around 0.88). Fairness aware optimization reduces demographic parity difference to 3 percent, ensuring equitable rural urban policy inference. The results validate that transformer based contextual learning significantly enhances policy intelligence in low resource governance environments, enabling scalable and bias aware hunger prediction systems.
### Title:
          Benchmarking Efficient & Effective Camera Pose Estimation Strategies for Novel View Synthesis
 - **Authors:** Jhacson Meza, Martin R. Oswald, Torsten Sattler
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Novel view synthesis (NVS) approaches such as NeRFs or 3DGS can produce photo-realistic 3D scene representation from a set of images with known extrinsic and intrinsic parameters. The necessary camera poses and calibrations are typically obtained from the images via Structure-from-Motion (SfM). Classical SfM approaches rely on local feature matches between the images to estimate both the poses and a sparse 3D model of the scene, using bundle adjustment to refine initial pose, intrinsics, and geometry estimates. In order to increase run-time efficiency, recent SfM systems forgo optimization via bundle adjustment. Instead, they train feed-forward (transformer-based) neural networks to directly regress camera parameters and the 3D structure. While orders of magnitude more efficient, such recent works produce significantly less accurate estimates. To stimulate research on developing SfM approaches that are both efficient \emph{and} effective, this paper develops a benchmark focused on SfM for novel view synthesis. Using existing datasets and two simple strategies for making the reconstruction process more efficient, we show that: (1) simply using fewer features already significantly accelerates classical SfM methods while maintaining high pose accuracy. (2) using feed-forward networks to obtain initial estimates and refining them using classical SfM techniques leads to the best efficiency-effectiveness trade-off. We will make our benchmark and code publicly available.
### Title:
          Detecting Neurovascular Instability from Multimodal Physiological Signals Using Wearable-Compatible Edge AI: A Responsible Computational Framework
 - **Authors:** Truong Quynh Hoa, Hoang Dinh Cuong, Truong Xuan Khanh
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose Melaguard, a multimodal ML framework (Transformer-lite, 1.2M parameters, 4-head self-attention) for detecting neurovascular instability (NVI) from wearable-compatible physiological signals prior to structural stroke pathology. The model fuses heart rate variability (HRV), peripheral perfusion index, SpO2, and bilateral phase coherence into a composite NVI Score, designed for edge inference (WCET <=4 ms on Cortex-M4). NVI - the pre-structural dysregulation of cerebrovascular autoregulation preceding overt stroke - remains undetectable by existing single-modality wearables. With 12.2 million incident strokes annually, continuous multimodal physiological monitoring offers a practical path to community-scale screening. Three-stage independent validation: (1) synthetic benchmark (n=10,000), AUC=0.88 [0.83-0.92]; (2) clinical cohort PhysioNet CVES (n=172; 84 stroke, 88 control) - Transformer-lite achieves AUC=0.755 [0.630-0.778], outperforming LSTM (0.643), Random Forest (0.665), SVM (0.472); HRV-SDNN discriminates stroke (p=0.011); (3) PPG pipeline PhysioNet BIDMC (n=53) -- pulse rate r=0.748 and HRV surrogate r=0.690 vs. ECG ground truth. Cross-modality validation on PPG-BP (n=219) confirms PPG morphology classifies cerebrovascular disease at AUC=0.923 [0.869-0.968]. Multimodal fusion consistently outperforms single-modality baselines. Code: this https URL
### Title:
          Inverting Neural Networks: New Methods to Generate Neural Network Inputs from Prescribed Outputs
 - **Authors:** Rebecca Pattichis, Sebastian Janampa, Constantinos S. Pattichis, Marios S. Pattichis
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural network systems describe complex mappings that can be very difficult to understand. In this paper, we study the inverse problem of determining the input images that get mapped to specific neural network classes. Ultimately, we expect that these images contain recognizable features that are associated with their corresponding class classifications. We introduce two general methods for solving the inverse problem. In our forward pass method, we develop an inverse method based on a root-finding algorithm and the Jacobian with respect to the input image. In our backward pass method, we iteratively invert each layer, at the top. During the inversion process, we add random vectors sampled from the null-space of each linear layer. We demonstrate our new methods on both transformer architectures and sequential networks based on linear layers. Unlike previous methods, we show that our new methods are able to produce random-like input images that yield near perfect classification scores in all cases, revealing vulnerabilities in the underlying networks. Hence, we conclude that the proposed methods provide a more comprehensive coverage of the input image spaces that solve the inverse mapping problem.
### Title:
          Delightful Distributed Policy Gradient
 - **Authors:** Ian Osband
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Optimization and Control (math.OC); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Distributed reinforcement learning trains on data from stale, buggy, or mismatched actors, producing actions with high surprisal (negative log-probability) under the learner's policy. The core difficulty is not surprising data per se, but \emph{negative learning from surprising data}. High-surprisal failures can dominate the update direction despite carrying little useful signal, while high-surprisal successes reveal opportunities the current policy would otherwise miss. The \textit{Delightful Policy Gradient} (DG) separates these cases by gating each update with delight, the product of advantage and surprisal, suppressing rare failures and amplifying rare successes without behavior probabilities. Under contaminated sampling, the cosine similarity between the standard policy gradient and the true gradient collapses, while DG's grows as the policy improves. No sign-blind reweighting, including exact importance sampling, can reproduce this effect. On MNIST with simulated staleness, DG without off-policy correction outperforms importance-weighted PG with exact behavior probabilities. On a transformer sequence task with staleness, actor bugs, reward corruption, and rare discovery, DG achieves roughly $10{\times}$ lower error. When all four frictions act simultaneously, its compute advantage is order-of-magnitude and grows with task complexity.
### Title:
          Does This Gradient Spark Joy?
 - **Authors:** Ian Osband
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Policy gradient computes a backward pass for every sample, even though the backward pass is expensive and most samples carry little learning value. The Delightful Policy Gradient (DG) provides a forward-pass signal of learning value: \emph{delight}, the product of advantage and surprisal (negative log-probability). We introduce the \emph{Kondo gate}, which compares delight against a compute price and pays for a backward pass only when the sample is worth it, thereby tracing a quality--cost Pareto frontier. In bandits, zero-price gating preserves useful gradient signal while removing perpendicular noise, and delight is a more reliable screening signal than additive combinations of value and surprise. On MNIST and transformer token reversal, the Kondo gate skips most backward passes while retaining nearly all of DG's learning quality, with gains that grow as problems get harder and backward passes become more expensive. Because the gate tolerates approximate delight, a cheap forward pass can screen samples before expensive backpropagation, suggesting a speculative-decoding-for-training paradigm.
### Title:
          RMNP: Row-Momentum Normalized Preconditioning for Scalable Matrix-Based Optimization
 - **Authors:** Shenyang Deng, Zhuoli Ouyang, Tianyu Pang, Zihang Liu, Ruochen Jin, Shuhua Yu, Yaoqing Yang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Preconditioned adaptive methods have gained significant attention for training deep neural networks, as they capture rich curvature information of the loss landscape . The central challenge in this field lies in balancing preconditioning effectiveness with computational efficiency of implementing the preconditioner. Among recent advances, \textsc{Muon} stands out by using Newton-Schulz iteration to obtain preconditioned updates without explicitly constructing the preconditioning matrix. Despite its advantages, the efficiency of \textsc{Muon} still leaves room for further improvement. In this paper, we introduce \textsc{RMNP} (Row Momentum Normalized Preconditioning), an optimizer that replaces Newton-Schulz iteration with a simple row-wise $\ell_2$ normalization operation, motivated by the empirically observed diagonal block structure of the Transformer layerwise Hessian. This substitution reduces the per-iteration computational complexity from $\mathcal{O}(mn\cdot\min(m,n))$ to $\mathcal{O}(mn)$ for an $m\times n$ weight matrix while maintaining comparable optimization performance. Theoretically, we establish convergence guarantees for \textsc{RMNP} in the non-convex setting that match recent results for \textsc{Muon} optimizers, achieving the information-theoretic minimax optimal complexity. Extensive experiments on large language model pretraining show that \textsc{RMNP} delivers competitive optimization performance compared with \textsc{Muon} while substantially reducing preconditioning wall-clock time. Our code is available at \href{this https URL}{this link}.
### Title:
          Understanding Behavior Cloning with Action Quantization
 - **Authors:** Haoqun Cao, Tengyang Xie
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Behavior cloning is a fundamental paradigm in machine learning, enabling policy learning from expert demonstrations across robotics, autonomous driving, and generative models. Autoregressive models like transformer have proven remarkably effective, from large language models (LLMs) to vision-language-action systems (VLAs). However, applying autoregressive models to continuous control requires discretizing actions through quantization, a practice widely adopted yet poorly understood theoretically. This paper provides theoretical foundations for this practice. We analyze how quantization error propagates along the horizon and interacts with statistical sample complexity. We show that behavior cloning with quantized actions and log-loss achieves optimal sample complexity, matching existing lower bounds, and incurs only polynomial horizon dependence on quantization error, provided the dynamics are stable and the policy satisfies a probabilistic smoothness condition. We further characterize when different quantization schemes satisfy or violate these requirements, and propose a model-based augmentation that provably improves the error bound without requiring policy smoothness. Finally, we establish fundamental limits that jointly capture the effects of quantization error and statistical complexity.
### Title:
          Context Cartography: Toward Structured Governance of Contextual Space in Large Language Model Systems
 - **Authors:** Zihua Wu, Georg Gartner
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The prevailing approach to improving large language model (LLM) reasoning has centered on expanding context windows, implicitly assuming that more tokens yield better performance. However, empirical evidence - including the "lost in the middle" effect and long-distance relational degradation - demonstrates that contextual space exhibits structural gradients, salience asymmetries, and entropy accumulation under transformer architectures. We introduce Context Cartography, a formal framework for the deliberate governance of contextual space. We define a tripartite zonal model partitioning the informational universe into black fog (unobserved), gray fog (stored memory), and the visible field (active reasoning surface), and formalize seven cartographic operators - reconnaissance, selection, simplification, aggregation, projection, displacement, and layering - as transformations governing information transitions between and within zones. The operators are derived from a systematic coverage analysis of all non-trivial zone transformations and are organized by transformation type (what the operator does) and zone scope (where it applies). We ground the framework in the salience geometry of transformer attention, characterizing cartographic operators as necessary compensations for linear prefix memory, append-only state, and entropy accumulation under expanding context. An analysis of four contemporary systems (Claude Code, Letta, MemOS, and OpenViking) provides interpretive evidence that these operators are converging independently across the industry. We derive testable predictions from the framework - including operator-specific ablation hypotheses - and propose a diagnostic benchmark for empirical validation.
### Title:
          Improving Diffusion Generalization with Weak-to-Strong Segmented Guidance
 - **Authors:** Liangyu Yuan, Yufei Huang, Mingkun Lei, Tong Zhao, Ruoyu Wang, Changxi Chi, Yiwei Wang, Chi Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion models generate synthetic images through an iterative refinement process. However, the misalignment between the simulation-free objective and the iterative process often causes accumulated gradient error along the sampling trajectory, which leads to unsatisfactory results and a failure to generalize. Guidance techniques like Classifier Free Guidance (CFG) and AutoGuidance (AG) alleviate this by extrapolating between the main and inferior signal for stronger generalization. Despite empirical success, the effective operational regimes of prevalent guidance methods are still under-explored, leading to ambiguity when selecting the appropriate guidance method given a precondition. In this work, we first conduct synthetic comparisons to isolate and demonstrate the effective regime of guidance methods represented by CFG and AG from the perspective of weak-to-strong principle. Based on this, we propose a hybrid instantiation called SGG under the principle, taking the benefits of both. Furthermore, we demonstrate that the W2S principle along with SGG can be migrated into the training objective, improving the generalization ability of unguided diffusion models. We validate our approach with comprehensive experiments. At inference time, evaluations on SD3 and SD3.5 confirm that SGG outperforms existing training-free guidance variants. Training-time experiments on transformer architectures demonstrate the effective migration and performance gains in both conditional and unconditional settings. Code is available at this https URL.
### Title:
          Beyond Token Eviction: Mixed-Dimension Budget Allocation for Efficient KV Cache Compression
 - **Authors:** Ruijie Miao, Zhiming Wang, Wang Li, Shiwei Wu, Shufan Liu, Yanbing Jiang, Tong Yang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Key-value (KV) caching is widely used to accelerate transformer inference, but its memory cost grows linearly with input length, limiting long-context deployment. Existing token eviction methods reduce memory by discarding less important tokens, which can be viewed as a coarse form of dimensionality reduction that assigns each token either zero or full dimension. We propose MixedDimKV, a mixed-dimension KV cache compression method that allocates dimensions to tokens at a more granular level, and MixedDimKV-H, which further integrates head-level importance information. Experiments on long-context benchmarks show that MixedDimKV outperforms prior KV cache compression methods that do not rely on head-level importance profiling. When equipped with the same head-level importance information, MixedDimKV-H consistently outperforms HeadKV. Notably, our approach achieves comparable performance to full attention on LongBench with only 6.25% of the KV cache. Furthermore, in the Needle-in-a-Haystack test, our solution maintains 100% accuracy at a 50K context length while using as little as 0.26% of the cache.
### Title:
          Weber's Law in Transformer Magnitude Representations: Efficient Coding, Representational Geometry, and Psychophysical Laws in Language Models
 - **Authors:** Jon-Paul Cacioli
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 How do transformer language models represent magnitude? Recent work disagrees: some find logarithmic spacing, others linear encoding, others per-digit circular representations. We apply the formal tools of psychophysics to resolve this. Using four converging paradigms (representational similarity analysis, behavioural discrimination, precision gradients, causal intervention) across three magnitude domains in three 7-9B instruction-tuned models spanning three architecture families (Llama, Mistral, Qwen), we report three findings. First, representational geometry is consistently log-compressive: RSA correlations with a Weber-law dissimilarity matrix ranged from .68 to .96 across all 96 model-domain-layer cells, with linear geometry never preferred. Second, this geometry is dissociated from behaviour: one model produces a human-range Weber fraction (WF = 0.20) while the other does not, and both models perform at chance on temporal and spatial discrimination despite possessing logarithmic geometry. Third, causal intervention reveals a layer dissociation: early layers are functionally implicated in magnitude processing (4.1x specificity) while later layers where geometry is strongest are not causally engaged (1.2x). Corpus analysis confirms the efficient coding precondition (alpha = 0.77). These results suggest that training data statistics alone are sufficient to produce log-compressive magnitude geometry, but geometry alone does not guarantee behavioural competence.
### Title:
          NDT: Non-Differential Transformer and Its Application to Sentiment Analysis
 - **Authors:** Soudeep Ghoshal, Himanshu Buckchash, Sarita Paudel, Rubén Ruiz-Torrubiano
 - **Subjects:** Subjects:
Information Retrieval (cs.IR); Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 From customer feedback to social media, understanding human sentiment in text is central to how machines can interact meaningfully with people. However, despite notable progress, accurately capturing sentiment remains a challenging task, which continues to motivate further research in this area. To this end, we introduce Non-Differential Transformer (NDT). It is inspired by (but in contrast to) the state-of-the-art Differential Transformer (DT) model. While standard Transformers can struggle with irrelevant context, the sota DT model uses attention map subtraction, potentially for noise cancellation. We explore an alternative motivation, hypothesizing that benefits may arise from enabling different attention components to specialize on distinct concepts within the text, similar to multiplexing information channels or mixture models, rather than primarily canceling noise via subtraction. Guided by this concept-multiplexing (ConPlex) view, the specific architecture presented in this paper employs a purely additive strategy. It uses only positive weights, learned during training, to ensure constructive combination of these specialized attention perspectives. This design choice explores positive only integration, though our broader framework also shows promise with less constrained linear combinations involving both positive and negative weights. Our model computes attention via this positively weighted sum of multiple distinct attention maps. This allows the model to constructively integrate diverse signals and potentially capture more complex contextual relationships. Competitive performance is achieved by the proposed model for Sentiment Analysis while tested on multiple datasets. We conclude by presenting our results, challenges and future research agenda in this important area of research.
### Title:
          Mamba Learns in Context: Structure-Aware Domain Generalization for Multi-Task Point Cloud Understanding
 - **Authors:** Jincen Jiang, Qianyu Zhou, Yuhang Li, Kui Su, Meili Wang, Jian Chang, Jian Jun Zhang, Xuequan Lu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While recent Transformer and Mamba architectures have advanced point cloud representation learning, they are typically developed for single-task or single-domain settings. Directly applying them to multi-task domain generalization (DG) leads to degraded performance. Transformers effectively model global dependencies but suffer from quadratic attention cost and lack explicit structural ordering, whereas Mamba offers linear-time recurrence yet often depends on coordinate-driven serialization, which is sensitive to viewpoint changes and missing regions, causing structural drift and unstable sequential modeling. In this paper, we propose Structure-Aware Domain Generalization (SADG), a Mamba-based In-Context Learning framework that preserves structural hierarchy across domains and tasks. We design structure-aware serialization (SAS) that generates transformation-invariant sequences using centroid-based topology and geodesic curvature continuity. We further devise hierarchical domain-aware modeling (HDM) that stabilizes cross-domain reasoning by consolidating intra-domain structure and fusing inter-domain relations. At test time, we introduce a lightweight spectral graph alignment (SGA) that shifts target features toward source prototypes in the spectral domain without updating model parameters, ensuring structure-preserving test-time feature shifting. In addition, we introduce MP3DObject, a real-scan object dataset for multi-task DG evaluation. Comprehensive experiments demonstrate that the proposed approach improves structural fidelity and consistently outperforms state-of-the-art methods across multiple tasks including reconstruction, denoising, and registration.
### Title:
          Memory-Efficient Fine-Tuning Diffusion Transformers via Dynamic Patch Sampling and Block Skipping
 - **Authors:** Sunghyun Park, Jeongho Kim, Hyoungwoo Park, Debasmit Das, Sungrack Yun, Munawar Hayat, Jaegul Choo, Fatih Porikli, Seokeon Choi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformers (DiTs) have significantly enhanced text-to-image (T2I) generation quality, enabling high-quality personalized content creation. However, fine-tuning these models requires substantial computational complexity and memory, limiting practical deployment under resource constraints. To tackle these challenges, we propose a memory-efficient fine-tuning framework called DiT-BlockSkip, integrating timestep-aware dynamic patch sampling and block skipping by precomputing residual features. Our dynamic patch sampling strategy adjusts patch sizes based on the diffusion timestep, then resizes the cropped patches to a fixed lower resolution. This approach reduces forward & backward memory usage while allowing the model to capture global structures at higher timesteps and fine-grained details at lower timesteps. The block skipping mechanism selectively fine-tunes essential transformer blocks and precomputes residual features for the skipped blocks, significantly reducing training memory. To identify vital blocks for personalization, we introduce a block selection strategy based on cross-attention masking. Evaluations demonstrate that our approach achieves competitive personalization performance qualitatively and quantitatively, while reducing memory usage substantially, moving toward on-device feasibility (e.g., smartphones, IoT devices) for large-scale diffusion transformers.
### Title:
          Restoring Neural Network Plasticity for Faster Transfer Learning
 - **Authors:** Xander Coetzer, Arné Schreuder, Anna Sergeevna Bosman
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transfer learning with models pretrained on ImageNet has become a standard practice in computer vision. Transfer learning refers to fine-tuning pretrained weights of a neural network on a downstream task, typically unrelated to ImageNet. However, pretrained weights can become saturated and may yield insignificant gradients, failing to adapt to the downstream task. This hinders the ability of the model to train effectively, and is commonly referred to as loss of neural plasticity. Loss of plasticity may prevent the model from fully adapting to the target domain, especially when the downstream dataset is atypical in nature. While this issue has been widely explored in continual learning, it remains relatively understudied in the context of transfer learning. In this work, we propose the use of a targeted weight re-initialization strategy to restore neural plasticity prior to fine-tuning. Our experiments show that both convolutional neural networks (CNNs) and vision transformers (ViTs) benefit from this approach, yielding higher test accuracy with faster convergence on several image classification benchmarks. Our method introduces negligible computational overhead and is compatible with common transfer learning pipelines.
### Title:
          ReLaMix: Residual Latency-Aware Mixing for Delay-Robust Financial Time-Series Forecasting
 - **Authors:** Tianyou Lai, Wentao Yue, Jiayi Zhou, Chaoyuan Hao, Lingke Chang, Qingyu Mao, Zhibo Niu, Qilei Li
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Financial time-series forecasting in real-world high-frequency markets is often hindered by delayed or partially stale observations caused by asynchronous data acquisition and transmission latency. To better reflect such practical conditions, we investigate a simulated delay setting where a portion of historical signals is corrupted by a Zero-Order Hold (ZOH) mechanism, significantly increasing forecasting difficulty through stepwise stagnation artifacts. In this paper, we propose ReLaMix (Residual Latency-Aware Mixing Network), a lightweight extension of TimeMixer that integrates learnable bottleneck compression with residual refinement for robust signal recovery under delayed observations. ReLaMix explicitly suppresses redundancy from repeated stale values while preserving informative market dynamics via residual mixing enhancement. Experiments on a large-scale second-resolution PAXGUSDT benchmark demonstrate that ReLaMix consistently achieves state-of-the-art accuracy across multiple delay ratios and prediction horizons, outperforming strong mixer and Transformer baselines with substantially fewer parameters. Moreover, additional evaluations on BTCUSDT confirm the cross-asset generalization ability of the proposed framework. These results highlight the effectiveness of residual bottleneck mixing for high-frequency financial forecasting under realistic latency-induced staleness.
### Title:
          Scene Graph-guided SegCaptioning Transformer with Fine-grained Alignment for Controllable Video Segmentation and Captioning
 - **Authors:** Xu Zhang, Jin Yuan, BinHong Yang, Xuan Liu, Qianjun Zhang, Yuyi Wang, Zhiyong Li, Hanwang Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advancements in multimodal large models have significantly bridged the representation gap between diverse modalities, catalyzing the evolution of video multimodal interpretation, which enhances users' understanding of video content by generating correlated modalities. However, most existing video multimodal interpretation methods primarily concentrate on global comprehension with limited user interaction. To address this, we propose a novel task, Controllable Video Segmentation and Captioning (SegCaptioning), which empowers users to provide specific prompts, such as a bounding box around an object of interest, to simultaneously generate correlated masks and captions that precisely embody user intent. An innovative framework Scene Graph-guided Fine-grained SegCaptioning Transformer (SG-FSCFormer) is designed that integrates a Prompt-guided Temporal Graph Former to effectively captures and represents user intent through an adaptive prompt adaptor, ensuring that the generated content well aligns with the user's requirements. Furthermore, our model introduces a Fine-grained Mask-linguistic Decoder to collaboratively predict high-quality caption-mask pairs using a Multi-entity Contrastive loss, as well as provide fine-grained alignment between each mask and its corresponding caption tokens, thereby enhancing users' comprehension of videos. Comprehensive experiments conducted on two benchmark datasets demonstrate that SG-FSCFormer achieves remarkable performance, effectively capturing user intent and generating precise multimodal outputs tailored to user specifications. Our code is available at this https URL.
### Title:
          LLM-ODE: Data-driven Discovery of Dynamical Systems with Large Language Models
 - **Authors:** Amirmohammad Ziaei Bideh, Jonathan Gryak
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Discovering the governing equations of dynamical systems is a central problem across many scientific disciplines. As experimental data become increasingly available, automated equation discovery methods offer a promising data-driven approach to accelerate scientific discovery. Among these methods, genetic programming (GP) has been widely adopted due to its flexibility and interpretability. However, GP-based approaches often suffer from inefficient exploration of the symbolic search space, leading to slow convergence and suboptimal solutions. To address these limitations, we propose LLM-ODE, a large language model-aided model discovery framework that guides symbolic evolution using patterns extracted from elite candidate equations. By leveraging the generative prior of large language models, LLM-ODE produces more informed search trajectories while preserving the exploratory strengths of evolutionary algorithms. Empirical results on 91 dynamical systems show that LLM-ODE variants consistently outperform classical GP methods in terms of search efficiency and Pareto-front quality. Overall, our results demonstrate that LLM-ODE improves both efficiency and accuracy over traditional GP-based discovery and offers greater scalability to higher-dimensional systems compared to linear and Transformer-only model discovery methods.
### Title:
          Deep Adaptive Rate Allocation in Volatile Heterogeneous Wireless Networks
 - **Authors:** Gregorio Maglione, Veselin Rakocevic, Markus Amend, Touraj Soleymani
 - **Subjects:** Subjects:
Information Theory (cs.IT); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern multi-access 5G+ networks provide mobile terminals with additional capacity, improving network stability and performance. However, in highly mobile environments such as vehicular networks, supporting multi-access connectivity remains challenging. The rapid fluctuations of wireless link quality often outpace the responsiveness of existing multipath schedulers and transport-layer protocols. This paper addresses this challenge by integrating Transformer-based path state forecasting with a new multipath splitting scheduler called Deep Adaptive Rate Allocation (DARA). The proposed scheduler employs a deep reinforcement learning engine to dynamically compute optimal congestion window fractions on available paths, determining data allocation among them. A six-component normalised reward function with weight-mediated conflict resolution drives a DQN policy that eliminates the observation-reaction lag inherent in reactive schedulers. Performance evaluation uses a Mininet-based Multipath Datagram Congestion Control Protocol testbed with traces from mobile users in vehicular environments. Experimental results demonstrate that DARA achieves better file transfer time reductions compared to learning-based schedulers under moderate-volatility traces. For buffered video streaming, resolution improvements are maintained across all tested conditions. Under controlled burst scenarios with sub-second buffer constraints, DARA achieves substantial rebuffering improvements whilst state-of-the-art schedulers exhibit near-continuous stalling.
### Title:
          Understanding Contextual Recall in Transformers: How Finetuning Enables In-Context Reasoning over Pretraining Knowledge
 - **Authors:** Bhavya Vasudeva, Puneesh Deora, Alberto Bietti, Vatsal Sharan, Christos Thrampoulidis
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based language models excel at in-context learning (ICL), where they can adapt to new tasks based on contextual examples, without parameter updates. In a specific form of ICL, which we refer to as \textit{contextual recall}, models pretrained on open-ended text leverage pairwise examples to recall specific facts in novel prompt formats. We investigate whether contextual recall emerges from pretraining alone, what finetuning is required, and what mechanisms drive the necessary representations. For this, we introduce a controlled synthetic framework where pretraining sequences consist of subject-grammar-attribute tuples, with attribute types tied to grammar statistics. We demonstrate that while such pretraining successfully yields factual knowledge, it is insufficient for contextual recall: models fail to implicitly infer attribute types when the grammar statistics are removed in ICL prompts. However, we show that finetuning on tasks requiring implicit inference, distinct from the ICL evaluation, using a subset of subjects, triggers the emergence of contextual recall across all subjects. This transition is accompanied by the formation of low-dimensional latent encodings of the shared attribute type. For mechanistic insight, we derive a construction for an attention-only transformer that replicates the transition from factual to contextual recall, corroborated by empirical validation.
### Title:
          Interpreting the Synchronization Gap: The Hidden Mechanism Inside Diffusion Transformers
 - **Authors:** Emil Albrychiewicz, Andrés Franco Valiente, Li-Ching Chen, Viola Zixin Zhao
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Disordered Systems and Neural Networks (cond-mat.dis-nn); Statistical Mechanics (cond-mat.stat-mech)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent theoretical models of diffusion processes, conceptualized as coupled Ornstein-Uhlenbeck systems, predict a hierarchy of interaction timescales, and consequently, the existence of a synchronization gap between modes that commit at different stages of the reverse process. However, because these predictions rely on continuous time and analytically tractable score functions, it remains unclear how this phenomenology manifests in the deep, discrete architectures deployed in practice. In this work, we investigate how the synchronization gap is mechanistically realized within pretrained Diffusion Transformers (DiTs). We construct an explicit architectural realization of replica coupling by embedding two generative trajectories into a joint token sequence, modulated by a symmetric cross attention gate with variable coupling strength g. Through a linearized analysis of the attention difference, we show that the replica interaction decomposes mechanistically. We empirically validate our theoretical framework on a pretrained DiT-XL/2 model by tracking commitment and per layer internal mode energies. Our results reveal that: (1) the synchronization gap is an intrinsic architectural property of DiTs that persists even when external coupling is turned off; (2) as predicted by our spatial routing bounds, the gap completely collapses under strong coupling; (3) the gap is strictly depth localized, emerging sharply only within the final layers of the Transformer; and (4) global, low frequency structures consistently commit before local, high frequency details. Ultimately, our findings provide a mechanistic interpretation of how Diffusion Transformers resolve generative ambiguity, isolating speciation transitions to the terminal layers of the network.
### Title:
          Structural Sensitivity in Compressed Transformers: Error Propagation, Lyapunov Stability, and Formally Verified Bounds
 - **Authors:** Abhinaba Basu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Logic in Computer Science (cs.LO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A single matrix out of 468 in GPT-2 Small can increase perplexity by 20,000x when compressed, revealing that transformer compression sensitivity spans five orders of magnitude. We map this sensitivity landscape across five architectures (117M-8B parameters), finding a consistent hierarchy: early-layer MLP up-projections are catastrophically sensitive while value projections compress nearly for free. This hierarchy is stable across compression levels, evaluation scales (2K-51K tokens), and datasets (WikiText-103, C4). Using Lyapunov stability theory, we show that residual connections contract compression errors by growing the hidden state faster than the error. Error contraction is necessary but not sufficient for compression tolerance: architecture-specific redundancy plays an equally important role, as demonstrated by the hybrid LFM2-2.6B degrading only 7x despite higher amplification than the fully-contracting GPT-2 Small (120x). Ten machine-checked Lean 4 theorems formalize per-matrix error bounds with no sorry markers; all bounds produce zero violations across 14,040+ configurations. We validate with downstream task evaluation (HellaSwag, ARC-Easy, Winogrande), activation-aware pruning on two architectures, and a Compression Fragility Index that rank-orders model robustness.
### Title:
          TabPFN Extensions for Interpretable Geotechnical Modelling
 - **Authors:** Taiga Saito, Yu Otake, Daijiro Mizutani, Stephen Wu
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Geotechnical site characterisation relies on sparse, heterogeneous borehole data where uncertainty quantification and model interpretability are as critical as predictive accuracy for reliable engineering decisions. This paper presents an exploratory investigation into the use of TabPFN, a transformer-based tabular foundation model using in-context learning, and its extension library tabpfn-extensions for two geotechnical inference tasks: (1) soil-type classification using N-value and shear-wave velocity data from a synthetic geotechnical dataset, and (2) iterative imputation of five missing mechanical parameters ($s_\mathrm{u}$, $E_{\mathrm{u}}$, ${\sigma'}_\mathrm{p}$, $C_\mathrm{c}$, $C_\mathrm{v}$) in benchmark problem BM/AirportSoilProperties/2/2025. We apply cosine-similarity analysis to TabPFN-derived embeddings, visualise full posterior distributions from an iterative inference procedure, and compute SHAP-based feature importance, all without model retraining. Learned embeddings clearly separate Clay and Sand samples without explicit soil-type supervision; iterative imputation improves predictions for four of five target parameters, with posterior widths that reflect physically reasonable parameter-specific uncertainty; and SHAP analysis reveals the inter-parameter dependency structure, recovering established geotechnical relationships including the Skempton compression index correlation and the inverse dependence of preconsolidation pressure on water content. These results suggest the potential of foundation-model-based tools to support interpretable, uncertainty-aware parameter inference in data-scarce geotechnical practice.
### Title:
          Cortical Policy: A Dual-Stream View Transformer for Robotic Manipulation
 - **Authors:** Xuening Zhang, Qi Lv, Xiang Deng, Miao Zhang, Xingbo Liu, Liqiang Nie
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 View transformers process multi-view observations to predict actions and have shown impressive performance in robotic manipulation. Existing methods typically extract static visual representations in a view-specific manner, leading to inadequate 3D spatial reasoning ability and a lack of dynamic adaptation. Taking inspiration from how the human brain integrates static and dynamic views to address these challenges, we propose Cortical Policy, a novel dual-stream view transformer for robotic manipulation that jointly reasons from static-view and dynamic-view streams. The static-view stream enhances spatial understanding by aligning features of geometrically consistent keypoints extracted from a pretrained 3D foundation model. The dynamic-view stream achieves adaptive adjustment through position-aware pretraining of an egocentric gaze estimation model, computationally replicating the human cortical dorsal pathway. Subsequently, the complementary view representations of both streams are integrated to determine the final actions, enabling the model to handle spatially-complex and dynamically-changing tasks under language conditions. Empirical evaluations on RLBench, the challenging COLOSSEUM benchmark, and real-world tasks demonstrate that Cortical Policy outperforms state-of-the-art baselines substantially, validating the superiority of dual-stream design for visuomotor control. Our cortex-inspired framework offers a fresh perspective for robotic manipulation and holds potential for broader application in vision-based robot control.
### Title:
          Mixture of Chapters: Scaling Learnt Memory in Transformers
 - **Authors:** Tasmay Pankaj Tibrewal, Pritish Saha, Ankit Meda, Kunal Singh, Pradeep Moturi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers lack an explicit architectural mechanism for storing and organizing knowledge acquired during training. We introduce learnable sparse memory banks: a set of latent tokens, randomly initialized and trained end-to-end, that transformer layers query via cross-attention to retrieve stored knowledge. To scale memory capacity without prohibitive attention costs, we propose chapter-based routing inspired by Mixture-of-Experts architectures, partitioning the memory bank into chapters and training a router to select relevant subsets per input. This enables scaling to 262K memory tokens while maintaining tractable computation. We evaluate our approach against standard transformers (in iso-FLOP settings) on pre-training and instruction fine-tuning across relevant benchmarks. Our models surpass iso-FLOP baselines suggesting scope for a new axis of scaling, demonstrating that explicit associative memory provides complementary capacity to what is captured implicitly in model parameters. Additionally, we observe improved knowledge retention under continued training, with robustness to forgetting when transitioning between training phases (e.g., pretraining to instruction fine-tuning).
### Title:
          Learning to Optimize Joint Source and RIS-assisted Channel Encoding for Multi-User Semantic Communication Systems
 - **Authors:** Haidong Wang, Songhan Zhao, Bo Gu, Shimin Gong, Hongyang Du, Ping Wang
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we explore a joint source and reconfigurable intelligent surface (RIS)-assisted channel encoding (JSRE) framework for multi-user semantic communications, where a deep neural network (DNN) extracts semantic features for all users and the RIS provides channel orthogonality, enabling a unified semantic encoding-decoding design. We aim to maximize the overall energy efficiency of semantic communications across all users by jointly optimizing the user scheduling, the RIS's phase shifts, and the semantic compression ratio. Although this joint optimization problem can be addressed using conventional deep reinforcement learning (DRL) methods, evaluating semantic similarity typically relies on extensive real environment interactions, which can incur heavy computational overhead during training. To address this challenge, we propose a truncated DRL (T-DRL) framework, where a DNN-based semantic similarity estimator is developed to rapidly estimate the similarity score. Moreover, the user scheduling strategy is tightly coupled with the semantic model configuration. To exploit this relationship, we further propose a semantic model caching mechanism that stores and reuses fine-tuned semantic models corresponding to different scheduling decisions. A Transformer-based actor network is employed within the DRL framework to dynamically generate action space conditioned on the current caching state. This avoids redundant retraining and further accelerates the convergence of the learning process. Numerical results demonstrate that the proposed JSRE framework significantly improves the system energy efficiency compared with the baseline methods. By training fewer semantic models, the proposed T-DRL framework significantly enhances the learning efficiency.
### Title:
          PrismWF: A Multi-Granularity Patch-Based Transformer for Robust Website Fingerprinting Attack
 - **Authors:** Yuhao Pan, Wenchao Xu, Fushuo Huo, Haozhao Wang, Xiucheng Wang, Nan Cheng
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tor is a low-latency anonymous communication network that protects user privacy by encrypting website traffic. However, recent website fingerprinting (WF) attacks have shown that encrypted traffic can still leak users' visited websites by exploiting statistical features such as packet size, direction, and inter-arrival time. Most existing WF attacks formulate the problem as a single-tab classification task, which significantly limits their effectiveness in realistic browsing scenarios where users access multiple websites concurrently, resulting in mixed traffic traces. To this end, we propose PrismWF, a multi-granularity patch-based Transformer for multi-tab WF attack. Specifically, we design a robust traffic feature representation for raw web traffic traces and extract multi-granularity features using convolutional kernels with different receptive fields. To effectively integrate information across temporal scales, the proposed model refines features through three hierarchical interaction mechanisms: inter-granularity detail supplementation from fine to coarse granularities, intra-granularity patch interaction with dedicated router tokens, and router-guided dual-level intra- and cross-granularity fusion. This design aligns with the cognitive logic of global coarse-grained reconnaissance and local fine-grained querying, enabling effective modeling of mixed traffic patterns in WF attack scenarios. Extensive experiments on various datasets and WF defenses demonstrate that our method achieves state-of-the-art performance compared to existing baselines.
### Title:
          Pretrained Video Models as Differentiable Physics Simulators for Urban Wind Flows
 - **Authors:** Janne Perini, Rafael Bischof, Moab Arar, Ayça Duran, Michael A. Kraus, Siddhartha Mishra, Bernd Bickel
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Designing urban spaces that provide pedestrian wind comfort and safety requires time-resolved Computational Fluid Dynamics (CFD) simulations, but their current computational cost makes extensive design exploration impractical. We introduce WinDiNet (Wind Diffusion Network), a pretrained video diffusion model that is repurposed as a fast, differentiable surrogate for this task. Starting from LTX-Video, a 2B-parameter latent video transformer, we fine-tune on 10,000 2D incompressible CFD simulations over procedurally generated building layouts. A systematic study of training regimes, conditioning mechanisms, and VAE adaptation strategies, including a physics-informed decoder loss, identifies a configuration that outperforms purpose-built neural PDE solvers. The resulting model generates full 112-frame rollouts in under a second. As the surrogate is end-to-end differentiable, it doubles as a physics simulator for gradient-based inverse optimization: given an urban footprint layout, we optimize building positions directly through backpropagation to improve wind safety as well as pedestrian wind comfort. Experiments on single- and multi-inlet layouts show that the optimizer discovers effective layouts even under challenging multi-objective configurations, with all improvements confirmed by ground-truth CFD simulations.
### Title:
          DepthTCM: High Efficient Depth Compression via Physics-aware Transformer-CNN Mixed Architecture
 - **Authors:** Young-Seo Chang, Yatong An, Jae-Sang Hyun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose DepthTCM, a physics-aware end-to-end framework for depth map compression. In our framework of DepthTCM, the high-bit depth map is first converted to a conventional 3-channel image representation losslessly using a method inspired by a physical sinusoidal fringe pattern based profiliometry system, then the 3-channel color image is encoded and decoded by a recently developed Transformer-CNN mixed neural network architecture. Specifically, DepthTCM maps depth to a smooth 3-channel using multiwavelength depth (MWD) encoding, then globally quantized the MWD encoded representation to 4 bits per channel to reduce entropy, and finally is compressed using a learned codec that combines convolutional and Transformer layers. Experiment results demonstrate the advantage of our proposed method. On Middlebury 2014, DepthTCM reaches 0.307 bpp while preserving 99.38% accuracy, a level of fidelity commensurate with lossless PNG. We additionally demonstrate practical efficiency and scalability, reporting average end-to-end inference times of 41.48 ms (encoder) and 47.45 ms (decoder) on the ScanNet++ iPhone RGB-D subset. Ablations validate our design choices: relative to 8-bit quantization, 4-bit quantization reduces bitrate by 66% while maintaining comparable reconstruction quality, with only a marginal 0.68 dB PSNR change and a 0.04% accuracy difference. In addition, Transformer--CNN blocks further improve PSNR by up to 0.75 dB over CNN-only architectures.
### Title:
          Enhancing Brain Tumor Classification Using Vision Transformers with Colormap-Based Feature Representation on BRISC2025 Dataset
 - **Authors:** Faisal Ahmed
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate classification of brain tumors from magnetic resonance imaging (MRI) plays a critical role in early diagnosis and effective treatment planning. In this study, we propose a deep learning framework based on Vision Transformers (ViT) enhanced with colormap-based feature representation to improve multi-class brain tumor classification performance. The proposed approach leverages the ability of transformer architectures to capture long-range dependencies while incorporating color mapping techniques to emphasize important structural and intensity variations within MRI scans. Experiments are conducted on the BRISC2025 dataset, which includes four classes: glioma, meningioma, pituitary tumor, and non-tumor cases. The model is trained and evaluated using standard performance metrics such as accuracy, precision, recall, F1-score, and area under the receiver operating characteristic curve (AUC). The proposed method achieves a classification accuracy of 98.90%, outperforming baseline convolutional neural network models including ResNet50, ResNet101, and EfficientNetB2. In addition, the model demonstrates strong generalization capability with an AUC of 99.97%, indicating high discriminative performance across all classes. These results highlight the effectiveness of combining Vision Transformers with colormap-based feature enhancement for accurate and robust brain tumor classification and suggest strong potential for clinical decision support applications.
### Title:
          LSA: A Long-Short-term Aspect Interest Transformer for Aspect-Based Recommendation
 - **Authors:** Le Liu, Junrui Liu, Yunhan Gao, Ziheng Wang, Tong Li
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Aspect-based recommendation methods extract aspect terms from reviews, such as price, to model fine-grained user preferences on items, making them a critical approach in personalized recommender systems. Existing methods utilize graphs to represent the relationships among users, items, and aspect terms, modeling user preferences based on graph neural networks. However, they overlook the dynamic nature of user interests - users may temporarily focus on aspects they previously paid little attention to - making it difficult to assign accurate weights to aspect terms for each user-item interaction. In this paper, we propose a long-short-term aspect interest Transformer (LSA) for aspect-based recommendation, which effectively captures the dynamic nature of user preferences by integrating both long-term and short-term aspect interests. Specifically, the short-term interests model the temporal changes in the importance of recently interacted aspect terms, while the long-term interests consider global behavioral patterns, including aspects that users have not interacted with recently. Finally, LSA combines long- and short-term interests to evaluate the importance of aspects within the union of user and item aspect neighbors, therefore accurately assigns aspect weights for each user-item interaction. Experiments conducted on four real-world datasets demonstrate that LSA improves MSE by 2.55% on average over the best baseline.
### Title:
          Evaluating Factor-Wise Auxiliary Dynamics Supervision for Latent Structure and Robustness in Simulated Humanoid Locomotion
 - **Authors:** Chayanin Chamachot
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We evaluate whether factor-wise auxiliary dynamics supervision produces useful latent structure or improved robustness in simulated humanoid locomotion. DynaMITE -- a transformer encoder with a factored 24-d latent trained by per-factor auxiliary losses during proximal policy optimization (PPO) -- is compared against Long Short-Term Memory (LSTM), plain Transformer, and Multilayer Perceptron (MLP) baselines on a Unitree G1 humanoid across four Isaac Lab tasks. The supervised latent shows no evidence of decodable or functionally separable factor structure: probe R^2 ~ 0 for all five dynamics factors, clamping any subspace changes reward by < 0.05, and standard disentanglement metrics (MIG, DCI, SAP) are near zero. An unsupervised LSTM hidden state achieves higher probe R^2 (up to 0.10). A 2x2 factorial ablation (n = 10 seeds) isolates the contributions of the tanh bottleneck and auxiliary losses: the auxiliary losses show no measurable effect on either in-distribution (ID) reward (+0.03, p = 0.732) or severe out-of-distribution (OOD) reward (+0.03, p = 0.669), while the bottleneck shows a small, consistent advantage in both regimes (ID: +0.16, p = 0.207; OOD: +0.10, p = 0.208). The bottleneck advantage persists under severe combined perturbation but does not amplify, indicating a training-time representation benefit rather than a robustness mechanism. LSTM achieves the best nominal reward on all four tasks (p < 0.03); DynaMITE degrades less under combined-shift stress (2.3% vs. 16.7%), but this difference is attributable to the bottleneck compression, not the auxiliary supervision. For locomotion practitioners: auxiliary dynamics supervision does not produce an interpretable estimator and does not measurably improve reward or robustness beyond what the bottleneck alone provides; recurrent baselines remain the stronger choice for nominal performance.
### Title:
          The Library Theorem: How External Organization Governs Agentic Reasoning Capacity
 - **Authors:** Zachary F. Mainen
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Data Structures and Algorithms (cs.DS); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Externalized reasoning is already exploited by transformer-based agents through chain-of-thought, but structured retrieval -- indexing over one's own reasoning state -- remains underexplored. We formalize the transformer context window as an I/O page and prove that tool-augmented agents with indexed external memory achieve exponentially lower retrieval cost than agents restricted to sequential scanning: $O(\log_b N)$ versus $\Omega(N)$ page reads per query, and $O(T \log_b T)$ versus $\Theta(T^2)$ cumulative cost over $T$ reasoning steps -- a gap that widens as deliberation deepens. We test these predictions on a controlled lookup benchmark across three content types -- random hashes, ordered integers, and encyclopedia entries -- varying store size from 50 to 5,000 items, and replicate key conditions across two model generations (GPT-4o-mini and GPT-5.4). On abstract content, the indexed agent achieves median 1 page read regardless of store size, confirming the $O(1)$ prediction. Sorted pages without an index fail to close the gap: the weaker model cannot sustain binary search at scale, and the stronger model achieves near-optimal $\log_2 N$ search but still loses to the index by $5\times$. On familiar content (encyclopedia entries), a competing failure mode emerges: the model recognizes the domain, bypasses the retrieval protocol, and generates answers from parametric memory, producing catastrophic token expenditure even when the index is sound. This parametric memory competition dissociates the two cognitive operations that indexing combines: understanding content (where language models excel) and following navigational protocols (where they fail when understanding tempts them to shortcut). The result argues for a separation of concerns: use language models for index construction, where semantic understanding helps, and deterministic algorithms for index traversal, where it hurts.
### Title:
          Fusing Memory and Attention: A study on LSTM, Transformer and Hybrid Architectures for Symbolic Music Generation
 - **Authors:** Soudeep Ghoshal, Sandipan Chakraborty, Pradipto Chowdhury, Himanshu Buckchash
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Machine learning techniques, such as Transformers and Long Short-Term Memory (LSTM) networks, play a crucial role in Symbolic Music Generation (SMG). Existing literature indicates a difference between LSTMs and Transformers regarding their ability to model local melodic continuity versus maintaining global structural coherence. However, their specific properties within the context of SMG have not been systematically studied. This paper addresses this gap by providing a fine-grained comparative analysis of LSTMs versus Transformers for SMG, examining local and global properties in detail using 17 musical quality metrics on the Deutschl dataset. We find that LSTM networks excel at capturing local patterns but fail to preserve long-range dependencies, while Transformers model global structure effectively but tend to produce irregular phrasing. Based on this analysis and leveraging their respective strengths, we propose a Hybrid architecture combining a Transformer Encoder with an LSTM Decoder and evaluate it against both baselines. We evaluated 1,000 generated melodies from each of the three architectures on the Deutschl dataset. The results show that the hybrid method achieves better local and global continuity and coherence compared to the baselines. Our work highlights the key characteristics of these models and demonstrates how their properties can be leveraged to design superior models. We also supported the experiments with ablation studies and human perceptual evaluations, which statistically support the findings and provide robust validation for this work.
### Title:
          Sonny: Breaking the Compute Wall in Medium-Range Weather Forecasting
 - **Authors:** Minjong Cheon
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Atmospheric and Oceanic Physics (physics.ao-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Weather forecasting is a fundamental problem for protecting lives and infrastructure from high-impact atmospheric events. Recently, data-driven weather forecasting methods based on deep learning have demonstrated strong performance, often reaching accuracy levels competitive with operational numerical systems. However, many existing models rely on large-scale training regimes and compute-intensive architectures, which raises the practical barrier for academic groups with limited compute resources. Here we introduce Sonny, an efficient hierarchical transformer that achieves competitive medium-range forecasting performance while remaining feasible within reasonable compute budgets. At the core of Sonny is a two-stage StepsNet design: a narrow slow path first models large-scale atmospheric dynamics, and a subsequent full-width fast path integrates thermodynamic interactions. To stabilize medium-range rollout without an additional fine-tuning stage, we apply exponential moving average (EMA) during training. On WeatherBench2, Sonny yields robust medium-range forecast skill, remains competitive with operational baselines, and demonstrates clear advantages over FastNet, particularly at extended tropical lead times. In practice, Sonny can be trained to convergence on a single NVIDIA A40 GPU in approximately 5.5 days.
### Title:
          Privacy-Preserving Federated Action Recognition via Differentially Private Selective Tuning and Efficient Communication
 - **Authors:** Idris Zakariyya, Pai Chet Ng, Kaushik Bhargav Sivangi, S. Mohammad Sheikholeslami, Konstantinos N. Plataniotis, Fani Deligianni
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Federated video action recognition enables collaborative model training without sharing raw video data, yet remains vulnerable to two key challenges: \textit{model exposure} and \textit{communication overhead}. Gradients exchanged between clients and the server can leak private motion patterns, while full-model synchronization of high-dimensional video networks causes significant bandwidth and communication costs. To address these issues, we propose \textit{Federated Differential Privacy with Selective Tuning and Efficient Communication for Action Recognition}, namely \textit{FedDP-STECAR}. Our \textit{FedDP-STECAR} framework selectively fine-tunes and perturbs only a small subset of task-relevant layers under Differential Privacy (DP), reducing the surface of information leakage while preserving temporal coherence in video features. By transmitting only the tuned layers during aggregation, communication traffic is reduced by over 99\% compared to full-model updates. Experiments on the UCF-101 dataset using the MViT-B-16x4 transformer show that \textit{FedDP-STECAR} achieves up to \textbf{70.2\% higher accuracy} under strict privacy ($\epsilon=0.65$) in centralized settings and \textbf{48\% faster training} with \textbf{73.1\% accuracy} in federated setups, enabling scalable and privacy-preserving video action recognition. Code available at this https URL
### Title:
          FluidWorld: Reaction-Diffusion Dynamics as a Predictive Substrate for World Models
 - **Authors:** Fabien Polly
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World models learn to predict future states of an environment, enabling planning and mental simulation. Current approaches default to Transformer-based predictors operating in learned latent spaces. This comes at a cost: O(N^2) computation and no explicit spatial inductive bias. This paper asks a foundational question: is self-attention necessary for predictive world modeling, or can alternative computational substrates achieve comparable or superior results? I introduce FluidWorld, a proof-of-concept world model whose predictive dynamics are governed by partial differential equations (PDEs) of reaction-diffusion type. Instead of using a separate neural network predictor, the PDE integration itself produces the future state prediction. In a strictly parameter-matched three-way ablation on unconditional UCF-101 video prediction (64x64, ~800K parameters, identical encoder, decoder, losses, and data), FluidWorld is compared against both a Transformer baseline (self-attention) and a ConvLSTM baseline (convolutional recurrence). While all three models converge to comparable single-step prediction loss, FluidWorld achieves 2x lower reconstruction error, produces representations with 10-15% higher spatial structure preservation and 18-25% more effective dimensionality, and critically maintains coherent multi-step rollouts where both baselines degrade rapidly. All experiments were conducted on a single consumer-grade PC (Intel Core i5, NVIDIA RTX 4070 Ti), without any large-scale compute. These results establish that PDE-based dynamics, which natively provide O(N) spatial complexity, adaptive computation, and global spatial coherence through diffusion, are a viable and parameter-efficient alternative to both attention and convolutional recurrence for world modeling.
### Title:
          Stream separation improves Bregman conditioning in transformers
 - **Authors:** James Clayton Kerce
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Linear methods for steering transformer representations, including probing, activation engineering, and concept erasure, implicitly assume the geometry of representation space is Euclidean. Park et al. [Park et al., 2026] showed that softmax induces a curved Bregman geometry whose metric tensor is the Hessian of the log-normalizer, $H({\lambda}) = Cov[{\gamma} | {\lambda}]$. Ignoring this curvature causes Euclidean steering to leak probability mass to unintended tokens. Their analysis applies at the output layer. We measure this Hessian at intermediate layers in a controlled 2x2 design crossing stream separation with per-layer supervision (vocabulary decoding loss at each layer), all at matched vocabulary and parameter count. In standard single-stream transformers, H is severely degenerate at intermediate layers (effective rank 8 in 516 dimensions). Stream separation improves conditioning by up to 22 in effective rank, even without auxiliary supervision. Per-layer supervision helps, but less. The cosine similarity between primal and dual concept directions predicts per-layer steering effectiveness on downstream tasks, with a threshold near 0.3. These results bear on the reliability of linear safety interventions, which depend on the geometry being well-conditioned at the layer where they are applied.
### Title:
          AutoKernel: Autonomous GPU Kernel Optimization via Iterative Agent-Driven Search
 - **Authors:** Jaber Jaber, Osama Jaber
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Performance (cs.PF)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Writing high-performance GPU kernels is among the most labor-intensive tasks in machine learning systems engineering. We present AutoKernel, an open-source framework that applies an autonomous agent loop to GPU kernel optimization for arbitrary PyTorch models. Given a model, AutoKernel profiles it to identify computational bottlenecks, ranks them by Amdahl's law impact, and iteratively refines Triton or CUDA C++ kernel implementations through hundreds of experiments without human intervention. A five-stage correctness harness covering smoke tests, shape sweeps, numerical stability, determinism verification, and edge-case coverage ensures every candidate kernel is validated before any speedup is recorded. The system comprises over 9,000 lines of Python, 18 starter kernel implementations across two backends, a six-tier optimization playbook, and integration with the KernelBench benchmark suite. AutoKernel covers nine kernel types spanning the dominant operations in modern transformer architectures. On an NVIDIA H100, our Triton kernels outperform both PyTorch eager and this http URL (max-autotune) on the majority of tested configurations: 5.29x over eager on RMSNorm, 2.82x on softmax, and 2.21x on cross-entropy, while beating this http URL by 2.83x, 3.44x, and 2.94x respectively. In community deployment, an AutoKernel-optimized kernel achieved first place on the vectorsum_v2 B200 leaderboard. The full system is available at this https URL.
### Title:
          Respiratory Status Detection with Video Transformers
 - **Authors:** Thomas Savage, Evan Madill
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recognition of respiratory distress through visual inspection is a life saving clinical skill. Clinicians can detect early signs of respiratory deterioration, creating a valuable window for earlier intervention. In this study, we evaluate whether recent advances in video transformers can enable Artificial Intelligence systems to recognize the signs of respiratory distress from video. We collected videos of healthy volunteers recovering after strenuous exercise and used the natural recovery of each participants respiratory status to create a labeled dataset for respiratory distress. Splitting the video into short clips, with earlier clips corresponding to more shortness of breath, we designed a temporal ordering challenge to assess whether an AI system can detect respiratory distress. We found a ViViT encoder augmented with Lie Relative Encodings (LieRE) and Motion Guided Masking, combined with an embedding based comparison strategy, can achieve an F1 score of 0.81 on this task. Our findings suggest that modern video transformers can recognize subtle changes in respiratory mechanics.
### Title:
          A transformer architecture alteration to incentivise externalised reasoning
 - **Authors:** Elizabeth Pavlova, Mariia Koroliuk, Karthik Viswanathan, Cameron Tice, Edward James Young, Puria Radmard
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose a new architectural change, and post-training pipeline, for making LLMs more verbose reasoners by teaching a model to truncate forward passes early. We augment an existing transformer architecture with an early-exit mechanism at intermediate layers and train the model to exit at shallower layers when the next token can be predicted without deep computation. After a calibration stage, we incentivise the model to exit as early as possible while maintaining task performance using reinforcement learning. We provide preliminary results to this effect for small reasoning models, showing that they learn to adaptively reduce computations across tokens. We predict that, applied at the right scale, our approach can minimise the amount of excess computation that reasoning models have at their disposal to perform non-myopic planning using their internal activations, reserving this only for difficult-to-predict tokens.
### Title:
          Semantic Shift: the Fundamental Challenge in Text Embedding and Retrieval
 - **Authors:** Hang Gao, Dimitris N. Metaxas
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based embedding models rely on pooling to map variable-length text into a single vector, enabling efficient similarity search but also inducing well-known geometric pathologies such as anisotropy and length-induced embedding collapse. Existing accounts largely describe \emph{what} these pathologies look like, yet provide limited insight into \emph{when} and \emph{why} they harm downstream retrieval. In this work, we argue that the missing causal factor is \emph{semantic shift}: the intrinsic, structured evolution and dispersion of semantics within a text. We first present a theoretical analysis of \emph{semantic smoothing} in Transformer embeddings: as the semantic diversity among constituent sentences increases, the pooled representation necessarily shifts away from every individual sentence embedding, yielding a smoothed and less discriminative vector. Building on this foundation, we formalize semantic shift as a computable measure integrating local semantic evolution and global semantic dispersion. Through controlled experiments across corpora and multiple embedding models, we show that semantic shift aligns closely with the severity of embedding concentration and predicts retrieval degradation, whereas text length alone does not. Overall, semantic shift offers a unified and actionable lens for understanding embedding collapse and for diagnosing when anisotropy becomes harmful.
### Title:
          ALADIN:Attribute-Language Distillation Network for Person Re-Identification
 - **Authors:** Wang Zhou, Boran Duan, Haojun Ai, Ruiqi Lan, Ziyue Zhou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent vision-language models such as CLIP provide strong cross-modal alignment, but current CLIP-guided ReID pipelines rely on global features and fixed prompts. This limits their ability to capture fine-grained attribute cues and adapt to diverse appearances. We propose ALADIN, an attribute-language distillation network that distills knowledge from a frozen CLIP teacher to a lightweight ReID student. ALADIN introduces fine-grained attribute-local alignment to establish adaptive text-visual correspondence and robust representation learning. A Scene-Aware Prompt Generator produces image-specific soft prompts to facilitate adaptive alignment. Attribute-local distillation enforces consistency between textual attributes and local visual features, significantly enhancing robustness under occlusions. Furthermore, we employ cross-modal contrastive and relation distillation to preserve the inherent structural relationships among attributes. To provide precise supervision, we leverage Multimodal LLMs to generate structured attribute descriptions, which are then converted into localized attention maps via CLIP. At inference, only the student is used. Experiments on Market-1501, DukeMTMC-reID, and MSMT17 show improvements over CNN-, Transformer-, and CLIP-based methods, with better generalization and interpretability.
### Title:
          Sharper Generalization Bounds for Transformer
 - **Authors:** Yawen Li, Tao Hu, Zhouhui Lian, Wan Tian, Yijie Peng, Huiming Zhang, Zhongyi Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper studies generalization error bounds for Transformer models. Based on the offset Rademacher complexity, we derive sharper generalization bounds for different Transformer architectures, including single-layer single-head, single-layer multi-head, and multi-layer Transformers. We first express the excess risk of Transformers in terms of the offset Rademacher complexity. By exploiting its connection with the empirical covering numbers of the corresponding hypothesis spaces, we obtain excess risk bounds that achieve optimal convergence rates up to constant factors. We then derive refined excess risk bounds by upper bounding the covering numbers of Transformer hypothesis spaces using matrix ranks and matrix norms, leading to precise, architecture-dependent generalization bounds. Finally, we relax the boundedness assumption on feature mappings and extend our theoretical results to settings with unbounded (sub-Gaussian) features and heavy-tailed distributions.
### Title:
          What Do World Models Learn in RL? Probing Latent Representations in Learned Environment Simulators
 - **Authors:** Xinyu Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World models learn to simulate environment dynamics from experience, enabling sample-efficient reinforcement learning. But what do these models actually represent internally? We apply interpretability techniques--including linear and nonlinear probing, causal interventions, and attention analysis--to two architecturally distinct world models: IRIS (discrete token transformer) and DIAMOND (continuous diffusion UNet), trained on Atari Breakout and Pong. Using linear probes, we find that both models develop linearly decodable representations of game state variables (object positions, scores), with MLP probes yielding only marginally higher R^2, confirming that these representations are approximately linear. Causal interventions--shifting hidden states along probe-derived directions--produce correlated changes in model predictions, providing evidence that representations are functionally used rather than merely correlated. Analysis of IRIS attention heads reveals spatial specialization: specific heads attend preferentially to tokens overlapping with game objects. Multi-baseline token ablation experiments consistently identify object-containing tokens as disproportionately important. Our findings provide interpretability evidence that learned world models develop structured, approximately linear internal representations of environment state across two games and two architectures.
### Title:
          Thinking Deeper, Not Longer: Depth-Recurrent Transformers for Compositional Generalization
 - **Authors:** Hung-Hsuan Chen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Standard Transformers have a fixed computational depth, fundamentally limiting their ability to generalize to tasks requiring variable-depth reasoning, such as multi-hop graph traversal or nested logic. We propose a depth-recurrent Transformer that decouples computational depth from parameter count by iteratively applying a shared-weight Transformer block in latent space -- enabling the model to trade recurrence steps for deeper reasoning at inference time. Our architecture incorporates three mechanisms to make deep recurrence (20+ steps) stable: (1) a silent thinking objective that supervises only the final output, forcing genuine multi-step reasoning rather than intermediate heuristic shortcuts; (2) LayerScale initialization to protect fragile reasoning states from untrained layer noise; and (3) an identity-biased recurrence that creates a gradient highway across many steps. We evaluate on three compositional reasoning domains with decreasing inductive biases: graph reachability (strict adjacency masking), nested boolean logic (relative positioning), and unstructured relational text (where sequence position provides no structural hints). Across all tasks, we observe a clear \emph{computational frontier} -- a boundary where performance transitions from chance to near-perfect as thinking steps scale with task complexity. Moreover, these tasks reveal qualitatively different generalization behaviors: precise but brittle (graph), approximate but robust (logic), and autonomous latent routing without structural hints (text). This progression illuminates how the interplay between a task-invariant recurrent reasoning core and task-specific perceptual interfaces shapes out-of-distribution (OOD) generalization, offering a mechanistic perspective on vertical chain-of-thought that complements the prevailing horizontal token-generation paradigm.
### Title:
          FISformer: Replacing Self-Attention with a Fuzzy Inference System in Transformer Models for Time Series Forecasting
 - **Authors:** Bulent Haznedar, Levent Karacan
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers have achieved remarkable progress in time series forecasting, yet their reliance on deterministic dot-product attention limits their capacity to model uncertainty and nonlinear dependencies across multivariate temporal dimensions. To address this limitation, we propose FISFormer, a Fuzzy Inference System-driven Transformer that replaces conventional attention with a FIS Interaction mechanism. In this framework, each query-key pair undergoes a fuzzy inference process for every feature dimension, where learnable membership functions and rule-based reasoning estimate token-wise relational strengths. These FIS-derived interaction weights capture uncertainty and provide interpretable, continuous mappings between tokens. A softmax operation is applied along the token axis to normalize these weights, which are then combined with the corresponding value features through element-wise multiplication to yield the final context-enhanced token representations. This design fuses the interpretability and uncertainty modeling of fuzzy logic with the representational power of Transformers. Extensive experiments on multiple benchmark datasets demonstrate that FISFormer achieves superior forecasting accuracy, noise robustness, and interpretability compared to state-of-the-art Transformer variants, establishing fuzzy inference as an effective alternative to conventional attention mechanisms.
### Title:
          SHARP: Spectrum-aware Highly-dynamic Adaptation for Resolution Promotion in Remote Sensing Synthesis
 - **Authors:** Bingxuan Zhao, Qing Zhou, Chuang Yang, Qi Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-to-image generation powered by Diffusion Transformers (DiTs) has made remarkable strides, yet remote sensing (RS) synthesis lags behind due to two barriers: the absence of a domain-specialized DiT prior and the prohibitive cost of training at the large resolutions that RS applications demand. Training-free resolution promotion via Rotary Position Embedding (RoPE) rescaling offers a practical remedy, but every existing method applies a static positional scaling rule throughout the denoising process. This uniform compression is particularly harmful for RS imagery, whose substantially denser medium- and high-frequency energy encodes the fine structures critical for aerial-scene realism, such as vehicles, building contours, and road markings. Addressing both challenges requires a domain-specialized generative prior coupled with a denoising-aware positional adaptation strategy. To this end, we fine-tune FLUX on over 100,000 curated RS images to build a strong domain prior (RS-FLUX), and propose Spectrum-aware Highly-dynamic Adaptation for Resolution Promotion (SHARP), a training-free method that introduces a rational fractional time schedule k_rs(t) into RoPE. SHARP applies strong positional promotion during the early layout-formation stage and progressively relaxes it during detail recovery, aligning extrapolation strength with the frequency-progressive nature of diffusion denoising. Its resolution-agnostic formulation further enables robust multi-scale generation from a single set of hyperparameters. Extensive experiments across six square and rectangular resolutions show that SHARP consistently outperforms all training-free baselines on CLIP Score, Aesthetic Score, and HPSv2, with widening margins at more aggressive extrapolation factors and negligible computational overhead. Code and weights are available at this https URL.
### Title:
          Anatomical Token Uncertainty for Transformer-Guided Active MRI Acquisition
 - **Authors:** Lev Ayzenberg, Shady Abu-Hussein, Raja Giryes, Hayit Greenspan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Full data acquisition in MRI is inherently slow, which limits clinical throughput and increases patient discomfort. Compressed Sensing MRI (CS-MRI) seeks to accelerate acquisition by reconstructing images from under-sampled k-space data, requiring both an optimal sampling trajectory and a high-fidelity reconstruction model. In this work, we propose a novel active sampling framework that leverages the inherent discrete structure of a pretrained medical image tokenizer and a latent transformer. By representing anatomy through a dictionary of quantized visual tokens, the model provides a well-defined probability distribution over the latent space. We utilize this distribution to derive a principled uncertainty measure via token entropy, which guides the active sampling process. We introduce two strategies to exploit this latent uncertainty: (1) Latent Entropy Selection (LES), projecting patch-wise token entropy into the $k$-space domain to identify informative sampling lines, and (2) Gradient-based Entropy Optimization (GEO), which identifies regions of maximum uncertainty reduction via the $k$-space gradient of a total latent entropy loss. We evaluate our framework on the fastMRI singlecoil Knee and Brain datasets at $\times 8$ and $\times 16$ acceleration. Our results demonstrate that our active policies outperform state-of-the-art baselines in perceptual metrics, and feature-based distances. Our code is available at this https URL.
### Title:
          Beyond Strict Pairing: Arbitrarily Paired Training for High-Performance Infrared and Visible Image Fusion
 - **Authors:** Yanglin Deng, Tianyang Xu, Chunyang Cheng, Hui Li, Xiao-jun Wu, Josef Kittler
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Infrared and visible image fusion(IVIF) combines complementary modalities while preserving natural textures and salient thermal signatures. Existing solutions predominantly rely on extensive sets of rigidly aligned image pairs for training. However, acquiring such data is often impractical due to the costly and labour-intensive alignment process. Besides, maintaining a rigid pairing setting during training restricts the volume of cross-modal relationships, thereby limiting generalisation performance. To this end, this work challenges the necessity of Strictly Paired Training Paradigm (SPTP) by systematically investigating UnPaired and Arbitrarily Paired Training Paradigms (UPTP and APTP) for high-performance IVIF. We establish a theoretical objective of APTP, reflecting the complementary nature between UPTP and SPTP. More importantly, we develop a practical framework capable of significantly enriching cross-modal relationships even with severely limited and unaligned training data. To validate our propositions, three end-to-end lightweight baselines, alongside a set of innovative loss functions, are designed to cover three classic frameworks (CNN, Transformer, GAN). Comprehensive experiments demonstrate that the proposed APTP and UPTP are feasible and capable of training models on a severely limited and content-inconsistent infrared and visible dataset, achieving performance comparable to that of a dataset 100$\times$ larger in SPTP. This finding fundamentally alleviates the cost and difficulty of data collection while enhancing model robustness from the data perspective, delivering a feasible solution for IVIF studies. The code is available at \href{this https URL}{\textcolor{blue}{this https URL\_unpair}}.
### Title:
          Multi-View Deformable Convolution Meets Visual Mamba for Coronary Artery Segmentation
 - **Authors:** Xiaochan Yuan, Pai Zeng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate segmentation of coronary arteries from computed tomography angiography (CTA) images is of paramount clinical importance for the diagnosis and treatment planning of cardiovascular diseases. However, coronary artery segmentation remains challenging due to the inherent multi-branching and slender tubular morphology of the vasculature, compounded by severe class imbalance between foreground vessels and background tissue. Conventional convolutional neural network (CNN)-based approaches struggle to capture long-range dependencies among spatially distant vascular structures, while Vision Transformer (ViT)-based methods incur prohibitive computational overhead that hinders deployment in resource-constrained clinical settings. Motivated by the recent success of state space models (SSMs) in efficiently modeling long-range sequential dependencies with linear complexity, we propose MDSVM-UNet, a novel two-stage coronary artery segmentation framework that synergistically integrates multidirectional snake convolution (MDSConv) with residual visual Mamba (RVM). In the encoding stage, we introduce MDSConv, a deformable convolution module that learns adaptive offsets along three orthogonal anatomical planes -- sagittal, coronal, and axial -- thereby enabling comprehensive multi-view feature fusion that faithfully captures the elongated and tortuous geometry of coronary vessels. In the decoding stage, we design an RVM-based upsampling decoder block that leverages selective state space mechanisms to model inter-slice long-range dependencies while preserving linear computational complexity. Furthermore, we propose a progressive two-stage segmentation strategy: the first stage performs coarse whole-image segmentation to guide intelligent block extraction, while the second stage conducts fine-grained block-level segmentation to recover vascular details and suppress false positives..
### Title:
          Verify Implementation Equivalence of Large Models
 - **Authors:** Qi Zhan, Xing Hu, Xin Xia, Shanping Li
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Verifying whether two implementations of the same large model are equivalent across frameworks is difficult in practice. Even when they realize the same computation, their graphs may differ substantially in operator decomposition, tensor layout, and the use of fused or opaque kernels, making manual rewrite rules hard to build and maintain. We present Emerge, a framework for checking Implementation Equivalence over computation graphs of large-model implementations. Instead of writing rules manually, Emerge represents the two implementations in an e-graph, infers candidate relations from execution values, and synthesizes rewrite rules on demand when existing rules are insufficient. Each synthesized rule is validated using the strongest applicable method, including SMT- based checking for symbolically tractable cases and constraint-aware randomized testing for opaque kernels, and then propagated through e-graph rebuilding to establish larger equivalences. Our current implementation targets inference computation graphs captured from HuggingFace Transformers and vLLM. Our evaluation shows that Emerge establishes equivalence for correct implementation pairs at practical cost, while also providing useful by-products for debugging: it detects 10 of 13 known implementation bugs and uncovers 8 previously unknown implementation issues that were later confirmed by developers. In addition, Emerge synthesizes block-level rules that compare favorably with manually authored ones.
### Title:
          FeatDistill: A Feature Distillation Enhanced Multi-Expert Ensemble Framework for Robust AI-generated Image Detection
 - **Authors:** Zhilin Tu, Kemou Li, Fengpeng Li, Jianwei Fei, Jiamin Zhang, Haiwei Wu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid iteration and widespread dissemination of deepfake technology have posed severe challenges to information security, making robust and generalizable detection of AI-generated forged images increasingly important. In this paper, we propose FeatDistill, an AI-generated image detection framework that integrates feature distillation with a multi-expert ensemble, developed for the NTIRE Challenge on Robust AI-Generated Image Detection in the Wild. The framework explicitly targets three practical bottlenecks in real-world forensics: degradation interference, insufficient feature representation, and limited generalization. Concretely, we build a four-backbone Vision Transformer (ViT) ensemble composed of CLIP and SigLIP variants to capture complementary forensic cues. To improve data coverage, we expand the training set and introduce comprehensive degradation modeling, which exposes the detector to diverse quality variations and synthesis artifacts commonly encountered in unconstrained scenarios. We further adopt a two-stage training paradigm: the model is first optimized with a standard binary classification objective, then refined by dense feature-level self-distillation for representation alignment. This design effectively mitigates overfitting and enhances semantic consistency of learned features. At inference time, the final prediction is obtained by averaging the probabilities from four independently trained experts, yielding stable and reliable decisions across unseen generators and complex degradations. Despite the ensemble design, the framework remains efficient, requiring only about 10 GB peak GPU memory. Extensive evaluations in the NTIRE challenge setting demonstrate that FeatDistill achieves strong robustness and generalization under diverse ``in-the-wild'' conditions, offering an effective and practical solution for real-world deepfake image detection.
### Title:
          GeoFusion-CAD: Structure-Aware Diffusion with Geometric State Space for Parametric 3D Design
 - **Authors:** Xiaolei Zhou, Chuangjie Fang, Jie Wu, Jingyi Yang, Boyi Lin, Jianwei Zheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Parametric Computer-Aided Design (CAD) is fundamental to modern 3D modeling, yet existing methods struggle to generate long command sequences, especially under complex geometric and topological dependencies. Transformer-based architectures dominate CAD sequence generation due to their strong dependency modeling, but their quadratic attention cost and limited context windowing hinder scalability to long programs. We propose GeoFusion-CAD, an end-to-end diffusion framework for scalable and structure-aware generation. Our proposal encodes CAD programs as hierarchical trees, jointly capturing geometry and topology within a state-space diffusion process. Specifically, a lightweight C-Mamba block models long-range structural dependencies through selective state transitions, enabling coherent generation across extended command sequences. To support long-sequence evaluation, we introduce DeepCAD-240, an extended benchmark that increases the sequence length ranging from 40 to 240 while preserving sketch-extrusion semantics from the ABC dataset. Extensive experiments demonstrate that GeoFusion-CAD achieves superior performance on both short and long command ranges, maintaining high geometric fidelity and topological consistency where Transformer-based models degrade. Our approach sets new state-of-the-art scores for long-sequence parametric CAD generation, establishing a scalable foundation for next-generation CAD modeling systems. Code and datasets are available at GitHub.
### Title:
          Speed by Simplicity: A Single-Stream Architecture for Fast Audio-Video Generative Foundation Model
 - **Authors:** SII-GAIR, Sand.ai: Ethan Chern, Hansi Teng, Hanwen Sun, Hao Wang, Hong Pan, Hongyu Jia, Jiadi Su, Jin Li, Junjie Yu, Lijie Liu, Lingzhi Li, Lyumanshan Ye, Min Hu, Qiangang Wang, Quanwei Qi, Steffi Chern, Tao Bu, Taoran Wang, Teren Xu, Tianning Zhang, Tiantian Mi, Weixian Xu, Wenqiang Zhang, Wentai Zhang, Xianping Yi, Xiaojie Cai, Xiaoyang Kang, Yan Ma, Yixiu Liu, Yunbo Zhang, Yunpeng Huang, Yutong Lin, Zewei Tao, Zhaoliang Liu, Zheng Zhang, Zhiyao Cen, Zhixuan Yu, Zhongshu Wang, Zhulin Hu, Zijin Zhou, Zinan Guo, Yue Cao, Pengfei Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present daVinci-MagiHuman, an open-source audio-video generative foundation model for human-centric generation. daVinci-MagiHuman jointly generates synchronized video and audio using a single-stream Transformer that processes text, video, and audio within a unified token sequence via self-attention only. This single-stream design avoids the complexity of multi-stream or cross-attention architectures while remaining easy to optimize with standard training and inference infrastructure. The model is particularly strong in human-centric scenarios, producing expressive facial performance, natural speech-expression coordination, realistic body motion, and precise audio-video synchronization. It supports multilingual spoken generation across Chinese (Mandarin and Cantonese), English, Japanese, Korean, German, and French. For efficient inference, we combine the single-stream backbone with model distillation, latent-space super-resolution, and a Turbo VAE decoder, enabling generation of a 5-second 256p video in 2 seconds on a single H100 GPU. In automatic evaluation, daVinci-MagiHuman achieves the highest visual quality and text alignment among leading open models, along with the lowest word error rate (14.60%) for speech intelligibility. In pairwise human evaluation, it achieves win rates of 80.0% against Ovi 1.1 and 60.9% against LTX 2.3 over 2000 comparisons. We open-source the complete model stack, including the base model, the distilled model, the super-resolution model, and the inference codebase.
### Title:
          λ-GELU: Learning Gating Hardness for Controlled ReLU-ization in Deep Networks
 - **Authors:** Cristian Pérez-Corral, Alberto Fernández-Hernández, Jose I. Mestre, Manuel F. Dolz, Enrique S. Quintana-Ortí
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Gaussian Error Linear Unit (GELU) is a widely used smooth alternative to Rectifier Linear Unit (ReLU), yet many deployment, compression, and analysis toolchains are most naturally expressed for piecewise-linear (ReLU-type) networks. We study a hardness-parameterized formulation of GELU, f(x;{\lambda})=x{\Phi}({\lambda} x), where {\Phi} is the Gaussian CDF and {\lambda} \in [1, infty) controls gate sharpness, with the goal of turning smooth gated training into a controlled path toward ReLU-compatible models. Learning {\lambda} is non-trivial: naive updates yield unstable dynamics and effective gradient attenuation, so we introduce a constrained reparameterization and an optimizer-aware update scheme. Empirically, across a diverse set of model--dataset pairs spanning MLPs, CNNs, and Transformers, we observe structured layerwise hardness profiles and assess their robustness under different initializations. We further study a deterministic ReLU-ization strategy in which the learned gates are progressively hardened toward a principled target, enabling a post-training substitution of {\lambda}-GELU by ReLU with reduced disruption. Overall, {\lambda}-GELU provides a minimal and interpretable knob to profile and control gating hardness, bridging smooth training with ReLU-centric downstream pipelines.
### Title:
          STENet: Superpixel Token Enhancing Network for RGB-D Salient Object Detection
 - **Authors:** Jianlin Chen, Gongyang Li, Zhijiang Zhang, Liang Chang, Dan Zeng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based methods for RGB-D Salient Object Detection (SOD) have gained significant interest, owing to the transformer's exceptional capacity to capture long-range pixel dependencies. Nevertheless, current RGB-D SOD methods face challenges, such as the quadratic complexity of the attention mechanism and the limited local detail extraction. To overcome these limitations, we propose a novel Superpixel Token Enhancing Network (STENet), which introduces superpixels into cross-modal interaction. STENet follows the two-stream encoder-decoder structure. Its cores are two tailored superpixel-driven cross-modal interaction modules, responsible for global and local feature enhancement. Specifically, we update the superpixel generation method by expanding the neighborhood range of each superpixel, allowing for flexible transformation between pixels and superpixels. With the updated superpixel generation method, we first propose the Superpixel Attention Global Enhancing Module to model the global pixel-to-superpixel relationship rather than the traditional global pixel-to-pixel relationship, which can capture region-level information and reduce computational complexity. We also propose the Superpixel Attention Local Refining Module, which leverages pixel similarity within superpixels to filter out a subset of pixels (i.e., local pixels) and then performs feature enhancement on these local pixels, thereby capturing concerned local details. Furthermore, we fuse the globally and locally enhanced features along with the cross-scale features to achieve comprehensive feature representation. Experiments on seven RGB-D SOD datasets reveal that our STENet achieves competitive performance compared to state-of-the-art methods. The code and results of our method are available at this https URL.
### Title:
          SegMaFormer: A Hybrid State-Space and Transformer Model for Efficient Segmentation
 - **Authors:** Duy D. Nguyen, Phat T. Tran-Truong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The advent of Transformer and Mamba-based architectures has significantly advanced 3D medical image segmentation by enabling global contextual modeling, a capability traditionally limited in Convolutional Neural Networks (CNNs). However, state-of-the-art Transformer models often entail substantial computational complexity and parameter counts, which is particularly prohibitive for volumetric data and further exacerbated by the limited availability of annotated medical imaging datasets. To address these limitations, this work introduces SegMaFormer, a lightweight hybrid architecture that synergizes Mamba and Transformer modules within a hierarchical volumetric encoder for efficient long-range dependency modeling. The model strategically employs Mamba-based layers in early, high-resolution stages to reduce computational overhead while capturing essential spatial context, and reserves self-attention mechanisms for later, lower-resolution stages to refine feature representation. This design is augmented with generalized rotary position embeddings to enhance spatial awareness. Despite its compact structure, SegMaFormer achieves competitive performance on three public benchmarks (Synapse, BraTS, and ACDC), matching the Dice coefficient of significantly larger models. Empirically, our approach reduces parameters by up to 75x and substantially decreases FLOPs compared to current state-of-the-art models, establishing an efficient and high-performing solution for 3D medical image segmentation.
### Title:
          Tuning Real-World Image Restoration at Inference: A Test-Time Scaling Paradigm for Flow Matching Models
 - **Authors:** Purui Bai, Junxian Duan, Pin Wang, Jinhua Hao, Ming Sun, Chao Zhou, Huaibo Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Although diffusion-based real-world image restoration (Real-IR) has achieved remarkable progress, efficiently leveraging ultra-large-scale pre-trained text-to-image (T2I) models and fully exploiting their potential remain significant challenges. To address this issue, we propose ResFlow-Tuner, an image restoration framework based on the state-of-the-art flow matching model, FLUX.1-dev, which integrates unified multi-modal fusion (UMMF) with test-time scaling (TTS) to achieve unprecedented restoration performance. Our approach fully leverages the advantages of the Multi-Modal Diffusion Transformer (MM-DiT) architecture by encoding multi-modal conditions into a unified sequence that guides the synthesis of high-quality images. Furthermore, we introduce a training-free test-time scaling paradigm tailored for image restoration. During inference, this technique dynamically steers the denoising direction through feedback from a reward model (RM), thereby achieving significant performance gains with controllable computational overhead. Extensive experiments demonstrate that our method achieves state-of-the-art performance across multiple standard benchmarks. This work not only validates the powerful capabilities of the flow matching model in low-level vision tasks but, more importantly, proposes a novel and efficient inference-time scaling paradigm suitable for large pre-trained models.
### Title:
          Input Convex Encoder-Only Transformer for Fast and Gradient-Stable MPC in Building Demand Response
 - **Authors:** Kaipeng Xu, Zhuo Zhi, Keyue Jiang
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning-based Model Predictive Control (MPC) has emerged as a powerful strategy for building demand response. However, its practical deployment is often hindered by the non-convex optimization problems induced by standard neural network models. These problems lead to long solver times and suboptimal solutions, making real-time control over long horizons challenging. While Input Convex Neural Networks (ICNNs), such as Input-Convex Long Short-Term Memorys (IC-LSTMs), are developed to address the convexity issue, their recurrent architectures suffer from high computational cost and gradient instability as the prediction horizon increases. To overcome these limitations, this paper introduces the Input-Convex Encoder-only Transformer (IC-EoT), a novel architecture that synergizes the parallel processing capabilities of the Transformer with the guaranteed tractability of input convexity. The IC-EoT was developed and evaluated in a high-fidelity co-simulation framework using the Energym Python library to interface with the EnergyPlus building simulator, and compared against its recurrent convex counterpart (IC-LSTM) and standard non-convex models. The results demonstrate that the IC-EoT is structurally immune to the gradient instability that affects recurrent ICNNs while maintaining comparable predictive accuracy. More critically, it substantially reduces MPC solver times; this speed advantage grows with the prediction horizon, with the IC-EoT proving 2.7 to 8.3 times faster than the IC-LSTM across horizons spanning from one to eight hours. This leap in computational efficiency makes the IC-EoT a robust and practical solution, enabling effective, real-time MPC for building energy management under realistic horizon decision-making scenarios.
### Title:
          End-to-End Differentiable Predictive Control with Guaranteed Constraint Satisfaction and feasibility for Building Demand Response
 - **Authors:** Kaipeng Xu, Zhuo Zhi, Ruixuan Zhao, Keyue Jiang
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The high energy consumption of buildings presents a critical need for advanced control strategies like Demand Response (DR). Differentiable Predictive Control (DPC) has emerged as a promising method for learning explicit control policies, yet conventional DPC frameworks are hindered by three key limitations: the use of simplistic dynamics models with limited expressiveness, a decoupled training paradigm that fails to optimize for closed-loop performance, and a lack of practical safety guarantees under realistic assumptions. To address these shortcomings, this paper proposes a novel End-to-End Differentiable Predictive Control (E2E-DPC) framework. Our approach utilizes an Encoder-Only Transformer to model the complex system dynamics and employs a unified, performance-oriented loss to jointly train the model and the control policy. Crucially, we introduce an online tube-based constraint tightening method that provides theoretical guarantees for recursive feasibility and constraint satisfaction without requiring complex offline computation of terminal sets. The framework is validated in a high-fidelity EnergyPlus simulation, controlling a multi-zone building for a DR task. The results demonstrate that the proposed method with guarantees achieves near-perfect constraint satisfaction - a reduction of over 99% in violations compared to the baseline - at the cost of only a minor increase in electricity expenditure. This work provides a deployable, performance-driven control solution for building energy management and establishes a new pathway for developing verifiable learning-based control systems under milder assumptions.
### Title:
          Mamba-VMR: Multimodal Query Augmentation via Generated Videos for Precise Temporal Grounding
 - **Authors:** Yunzhuo Sun, Xinyue Liu, Yanyang Li, Nanding Wu, Yifang Xu, Linlin Zong, Xianchao Zhang, Wenxin Liang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-driven video moment retrieval (VMR) remains challenging due to limited capture of hidden temporal dynamics in untrimmed videos, leading to imprecise grounding in long sequences. Traditional methods rely on natural language queries (NLQs) or static image augmentations, overlooking motion sequences and suffering from high computational costs in Transformer-based architectures. Existing approaches fail to integrate subtitle contexts and generated temporal priors effectively, we therefore propose a novel two-stage framework for enhanced temporal grounding. In the first stage, LLM-guided subtitle matching identifies relevant textual cues from video subtitles, fused with the query to generate auxiliary short videos via text-to-video models, capturing implicit motion information as temporal priors. In the second stage, augmented queries are processed through a multi-modal controlled Mamba network, extending text-controlled selection with video-guided gating for efficient fusion of generated priors and long sequences while filtering noise. Our framework is agnostic to base retrieval models and widely applicable for multimodal VMR. Experimental evaluations on the TVR benchmark demonstrate significant improvements over state-of-the-art methods, including reduced computational overhead and higher recall in long-sequence grounding.
### Title:
          Make Tracking Easy: Neural Motion Retargeting for Humanoid Whole-body Control
 - **Authors:** Qingrui Zhao, Kaiyue Yang, Xiyu Wang, Shiqi Zhao, Yi Lu, Xinfang Zhang, Wei Yin, Qiu Shen, Xiao-Xiao Long, Xun Cao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Humanoid robots require diverse motor skills to integrate into complex environments, but bridging the kinematic and dynamic embodiment gap from human data remains a major bottleneck. We demonstrate through Hessian analysis that traditional optimization-based retargeting is inherently non-convex and prone to local optima, leading to physical artifacts like joint jumps and self-penetration. To address this, we reformulate the targeting problem as learning data distribution rather than optimizing optimal solutions, where we propose NMR, a Neural Motion Retargeting framework that transforms static geometric mapping into a dynamics-aware learned process. We first propose Clustered-Expert Physics Refinement (CEPR), a hierarchical data pipeline that leverages VAE-based motion clustering to group heterogeneous movements into latent motifs. This strategy significantly reduces the computational overhead of massively parallel reinforcement learning experts, which project and repair noisy human demonstrations onto the robot's feasible motion manifold. The resulting high-fidelity data supervises a non-autoregressive CNN-Transformer architecture that reasons over global temporal context to suppress reconstruction noise and bypass geometric traps. Experiments on the Unitree G1 humanoid across diverse dynamic tasks (e.g., martial arts, dancing) show that NMR eliminates joint jumps and significantly reduces self-collisions compared to state-of-the-art baselines. Furthermore, NMR-generated references accelerate the convergence of downstream whole-body control policies, establishing a scalable path for bridging the human-robot embodiment gap.
### Title:
          Benchmarking Deep Learning Models for Aerial LiDAR Point Cloud Semantic Segmentation under Real Acquisition Conditions: A Case Study in Navarre
 - **Authors:** Alex Salvatierra, José Antonio Sanz, Christian Gutiérrez, Mikel Galar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in deep learning have significantly improved 3D semantic segmentation, but most models focus on indoor or terrestrial datasets. Their behavior under real aerial acquisition conditions remains insufficiently explored, and although a few studies have addressed similar scenarios, they differ in dataset design, acquisition conditions, and model selection. To address this gap, we conduct an experimental benchmark evaluating several state-of-the-art architectures on a large-scale aerial LiDAR dataset acquired under operational flight conditions in Navarre, Spain, covering heterogeneous urban, rural, and industrial landscapes. This study compares four representative deep learning models, including KPConv, RandLA-Net, Superpoint Transformer, and Point Transformer V3, across five semantic classes commonly found in airborne surveys, such as ground, vegetation, buildings, and vehicles, highlighting the inherent challenges of class imbalance and geometric variability in aerial data. Results show that all tested models achieve high overall accuracy exceeding 93%, with KPConv attaining the highest mean IoU (78.51%) through consistent performance across classes, particularly on challenging and underrepresented categories. Point Transformer V3 demonstrates superior performance on the underrepresented vehicle class (75.11% IoU), while Superpoint Transformer and RandLA-Net trade off segmentation robustness for computational efficiency.
### Title:
          Riverine Land Cover Mapping through Semantic Segmentation of Multispectral Point Clouds
 - **Authors:** Sopitta Thurachen, Josef Taher, Matti Lehtomäki, Leena Matikainen, Linnea Blåfield, Mikel Calle Navarro, Antero Kukko, Tomi Westerlund, Harri Kaartinen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate land cover mapping in riverine environments is essential for effective river management, ecological understanding, and geomorphic change monitoring. This study explores the use of Point Transformer v2 (PTv2), an advanced deep neural network architecture designed for point cloud data, for land cover mapping through semantic segmentation of multispectral LiDAR data in real-world riverine environments. We utilize the geometric and spectral information from the 3-channel LiDAR point cloud to map land cover classes, including sand, gravel, low vegetation, high vegetation, forest floor, and water. The PTv2 model was trained and evaluated on point cloud data from the Oulanka river in northern Finland using both geometry and spectral features. To improve the model's generalization in new riverine environments, we additionally investigate multi-dataset training that adds sparsely annotated data from an additional river dataset. Results demonstrated that using the full-feature configuration resulted in performance with a mean Intersection over Union (mIoU) of 0.950, significantly outperforming the geometry baseline. Other ablation studies revealed that intensity and reflectance features were the key for accurate land cover mapping. The multi-dataset training experiment showed improved generalization performance, suggesting potential for developing more robust models despite limited high-quality annotated data. Our work demonstrates the potential of applying transformer-based architectures to multispectral point clouds in riverine environments. The approach offers new capabilities for monitoring sediment transport and other river management applications.
### Title:
          WorldCache: Content-Aware Caching for Accelerated Video World Models
 - **Authors:** Umair Nawaz, Ahmed Heakl, Ufaq Khan, Abdelrahman Shaker, Salman Khan, Fahad Shahbaz Khan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformers (DiTs) power high-fidelity video world models but remain computationally expensive due to sequential denoising and costly spatio-temporal attention. Training-free feature caching accelerates inference by reusing intermediate activations across denoising steps; however, existing methods largely rely on a Zero-Order Hold assumption i.e., reusing cached features as static snapshots when global drift is small. This often leads to ghosting artifacts, blur, and motion inconsistencies in dynamic scenes. We propose \textbf{WorldCache}, a Perception-Constrained Dynamical Caching framework that improves both when and how to reuse features. WorldCache introduces motion-adaptive thresholds, saliency-weighted drift estimation, optimal approximation via blending and warping, and phase-aware threshold scheduling across diffusion steps. Our cohesive approach enables adaptive, motion-consistent feature reuse without retraining. On Cosmos-Predict2.5-2B evaluated on PAI-Bench, WorldCache achieves \textbf{2.3$\times$} inference speedup while preserving \textbf{99.4\%} of baseline quality, substantially outperforming prior training-free caching approaches. Our code can be accessed on \href{this https URL}{World-Cache}.
## Keyword: autonomous driving
### Title:
          Beyond Scalar Rewards: Distributional Reinforcement Learning with Preordered Objectives for Safe and Reliable Autonomous Driving
 - **Authors:** Ahmed Abouelazm, Jonas Michel, Daniel Bogdoll, Philip Schörner, J. Marius Zöllner
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving involves multiple, often conflicting objectives such as safety, efficiency, and comfort. In reinforcement learning (RL), these objectives are typically combined through weighted summation, which collapses their relative priorities and often yields policies that violate safety-critical constraints. To overcome this limitation, we introduce the Preordered Multi-Objective MDP (Pr-MOMDP), which augments standard MOMDPs with a preorder over reward components. This structure enables reasoning about actions with respect to a hierarchy of objectives rather than a scalar signal. To make this structure actionable, we extend distributional RL with a novel pairwise comparison metric, Quantile Dominance (QD), that evaluates action return distributions without reducing them into a single statistic. Building on QD, we propose an algorithm for extracting optimal subsets, the subset of actions that remain non-dominated under each objective, which allows precedence information to shape both decision-making and training targets. Our framework is instantiated with Implicit Quantile Networks (IQN), establishing a concrete implementation while preserving compatibility with a broad class of distributional RL methods. Experiments in Carla show improved success rates, fewer collisions and off-road events, and deliver statistically more robust policies than IQN and ensemble-IQN baselines. By ensuring policies respect rewards preorder, our work advances safer, more reliable autonomous driving systems.
### Title:
          Fusing Driver Perceived and Physical Risk for Safety Critical Scenario Screening in Autonomous Driving
 - **Authors:** Chen Xiong, Ziwen Wang, Deqi Wang, Cheng Wang, Yiyang Chen, He Zhang, Chao Gou
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving testing increasingly relies on mining safety critical scenarios from large scale naturalistic driving data, yet existing screening pipelines still depend on manual risk annotation and expensive frame by frame risk evaluation, resulting in low efficiency and weakly grounded risk quantification. To address this issue, we propose a driver risk fusion based hazardous scenario screening method for autonomous driving. During training, the method combines an improved Driver Risk Field with a dynamic cost model to generate high quality risk supervision signals, while during inference it directly predicts scenario level risk scores through fast forward passes, avoiding per frame risk computation and enabling efficient large scale ranking and retrieval. The improved Driver Risk Field introduces a new risk height function and a speed adaptive look ahead mechanism, and the dynamic cost model integrates kinetic energy, oriented bounding box constraints, and Gaussian kernel diffusion smoothing for more accurate interaction modeling. We further design a risk trajectory cross attention decoder to jointly decode risk and trajectories. Experiments on the INTERACTION and FLUID datasets show that the proposed method produces smoother and more discriminative risk estimates. On FLUID, it achieves an AUC of 0.792 and an AP of 0.825, outperforming PODAR by 9.1 percent and 5.1 percent, respectively, demonstrating its effectiveness for scalable risk labeling and hazardous scenario screening.
### Title:
          Emergency Lane-Change Simulation: A Behavioral Guidance Approach for Risky Scenario Generation
 - **Authors:** Chen Xiong, Cheng Wang, Yuhang Liu, Zirui Wu, Ye Tian
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In contemporary autonomous driving testing, virtual simulation has become an important approach due to its efficiency and cost effectiveness. However, existing methods usually rely on reinforcement learning to generate risky scenarios, making it difficult to efficiently learn realistic emergency behaviors. To address this issue, we propose a behavior guided method for generating high risk lane change scenarios. First, a behavior learning module based on an optimized sequence generative adversarial network is developed to learn emergency lane change behaviors from an extracted dataset. This design alleviates the limitations of existing datasets and improves learning from relatively few samples. Then, the opposing vehicle is modeled as an agent, and the road environment together with surrounding vehicles is incorporated into the operating environment. Based on the Recursive Proximal Policy Optimization strategy, the generated trajectories are used to guide the vehicle toward dangerous behaviors for more effective risk scenario exploration. Finally, the reference trajectory is combined with model predictive control as physical constraints to continuously optimize the strategy and ensure physical authenticity. Experimental results show that the proposed method can effectively learn high risk trajectory behaviors from limited data and generate high risk collision scenarios with better efficiency than traditional methods such as grid search and manual design.
### Title:
          Understanding Behavior Cloning with Action Quantization
 - **Authors:** Haoqun Cao, Tengyang Xie
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Behavior cloning is a fundamental paradigm in machine learning, enabling policy learning from expert demonstrations across robotics, autonomous driving, and generative models. Autoregressive models like transformer have proven remarkably effective, from large language models (LLMs) to vision-language-action systems (VLAs). However, applying autoregressive models to continuous control requires discretizing actions through quantization, a practice widely adopted yet poorly understood theoretically. This paper provides theoretical foundations for this practice. We analyze how quantization error propagates along the horizon and interacts with statistical sample complexity. We show that behavior cloning with quantized actions and log-loss achieves optimal sample complexity, matching existing lower bounds, and incurs only polynomial horizon dependence on quantization error, provided the dynamics are stable and the policy satisfies a probabilistic smoothness condition. We further characterize when different quantization schemes satisfy or violate these requirements, and propose a model-based augmentation that provably improves the error bound without requiring policy smoothness. Finally, we establish fundamental limits that jointly capture the effects of quantization error and statistical complexity.
### Title:
          GHOST: Ground-projected Hypotheses from Observed Structure-from-Motion Trajectories
 - **Authors:** Tomasz Frelek, Rohan Patil, Akshar Tumu, Henrik I. Christensen
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a scalable self-supervised approach for segmenting feasible vehicle trajectories from monocular images for autonomous driving in complex urban environments. Leveraging large-scale dashcam videos, we treat recorded ego-vehicle motion as implicit supervision and recover camera trajectories via monocular structure-from-motion, projecting them onto the ground plane to generate spatial masks of traversed regions without manual annotation. These automatically generated labels are used to train a deep segmentation network that predicts motion-conditioned path proposals from a single RGB image at run time, without explicit modeling of road or lane markings. Trained on diverse, unconstrained internet data, the model implicitly captures scene layout, lane topology, and intersection structure, and generalizes across varying camera configurations. We evaluate our approach on NuScenes, demonstrating reliable trajectory prediction, and further show transfer to an electric scooter platform through light fine-tuning. Our results indicate that large-scale ego-motion distillation yields structured and generalizable path proposals beyond the demonstrated trajectory, enabling trajectory hypothesis estimation via image segmentation.
### Title:
          OmniPatch: A Universal Adversarial Patch for ViT-CNN Cross-Architecture Transfer in Semantic Segmentation
 - **Authors:** Aarush Aggarwal, Akshat Tomar, Amritanshu Tiwari, Sargam Goyal
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust semantic segmentation is crucial for safe autonomous driving, yet deployed models remain vulnerable to black-box adversarial attacks when target weights are unknown. Most existing approaches either craft image-wide perturbations or optimize patches for a single architecture, which limits their practicality and transferability. We introduce OmniPatch, a training framework for learning a universal adversarial patch that generalizes across images and both ViT and CNN architectures without requiring access to target model parameters.
### Title:
          KLDrive: Fine-Grained 3D Scene Reasoning for Autonomous Driving based on Knowledge Graph
 - **Authors:** Ye Tian, Jingyi Zhang, Zihao Wang, Xiaoyuan Ren, Xiaofan Yu, Onat Gungor, Tajana Rosing
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving requires reliable reasoning over fine-grained 3D scene facts. Fine-grained question answering over multi-modal driving observations provides a natural way to evaluate this capability, yet existing perception pipelines and driving-oriented large language model (LLM) methods still suffer from unreliable scene facts, hallucinations, opaque reasoning, and heavy reliance on task-specific training. We present KLDrive, the first knowledge-graph-augmented LLM reasoning framework for fine-grained question answering in autonomous driving. KLDrive addresses this problem through designing two tightly coupled components: an energy-based scene fact construction module that consolidates multi-source evidence into a reliable scene knowledge graph, and an LLM agent that performs fact-grounded reasoning over a constrained action space under explicit structural constraints. By combining structured prompting with few-shot in-context exemplars, the framework adapts to diverse reasoning tasks without heavy task-specific fine-tuning. Experiments on two large-scale autonomous-driving QA benchmarks show that KLDrive outperforms prior state-of-the-art methods, achieving the best overall accuracy of 65.04% on NuScenes-QA and the best SPICE score of 42.45 on GVQA. On counting, the most challenging factual reasoning task, it improves over the strongest baseline by 46.01 percentage points, demonstrating substantially reduced hallucinations and the benefit of coupling reliable scene fact construction with explicit reasoning.
### Title:
          Single-Eye View: Monocular Real-time Perception Package for Autonomous Driving
 - **Authors:** Haixi Zhang, Aiyinsi Zuo, Zirui Li, Chunshu Wu, Tong Geng, Zhiyao Duan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Amidst the rapid advancement of camera-based autonomous driving technology, effectiveness is often prioritized with limited attention to computational efficiency. To address this issue, this paper introduces LRHPerception, a real-time monocular perception package for autonomous driving that uses single-view camera video to interpret the surrounding environment. The proposed system combines the computational efficiency of end-to-end learning with the rich representational detail of local mapping methodologies. With significant improvements in object tracking and prediction, road segmentation, and depth estimation integrated into a unified framework, LRHPerception processes monocular image data into a five-channel tensor consisting of RGB, road segmentation, and pixel-level depth estimation, augmented with object detection and trajectory prediction. Experimental results demonstrate strong performance, achieving real-time processing at 29 FPS on a single GPU, representing a 555% speedup over the fastest mapping-based approach.
### Title:
          Dynasto: Validity-Aware Dynamic-Static Parameter Optimization for Autonomous Driving Testing
 - **Authors:** Dmytro Humeniuk, Mohammad Hamdaqa, Houssem Ben Braiek, Amel Bennaceur, Foutse Khomh
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Extensive simulation-based testing is important for assuring the safety of autonomous driving systems (ADS). However, generating safety-critical traffic scenarios remains challenging because failures often arise from rare, complex interactions with surrounding vehicles. Existing automatic scenario-generation approaches frequently fail to distinguish genuine ADS faults from collisions caused by implausible or invalid adversarial behaviors, and they typically optimize either scenario initialization or agent behavior in isolation. We propose Dynasto, a two-step testing approach that jointly optimizes initial scenario parameters and dynamic adversarial behaviors to uncover realistic safety-critical failures. First, we train an adversarial agent using reinforcement learning (RL) with temporal-logic-based validity criteria and a safe-distance model inspired by ISO 34502 to promote behaviorally plausible failures. Second, a genetic algorithm (GA) searches over initial conditions while replaying the adversary's failure-inducing behaviors to reveal additional failures that the RL agent alone does not uncover. Finally, a graph-based clustering pipeline groups failures into representative modes based on semantic event sequences. Our evaluation experiments in HighwayEnv across two ADS controllers show that Dynasto finds 60%-70% more valid failures than an RL-only adversary under the same evaluation budget. With clustering, we obtain about 12 interpretable failure modes per system under test, revealing valid failures driven by weaknesses in ego-controller behavior. These results indicate that coordinated dynamic-static optimization with explicit validity constraints is effective for exposing safety-relevant failures in ADS testing.
### Title:
          Ultrafast microwave sensing and automatic recognition of dynamic objects in open world using programmable surface plasmonic neural networks
 - **Authors:** Qian Ma, Ze Gu, Zi Rui Feng, Qian Wen Wu, Yu Ming Ning, Zhi Qiao Han, Rui Si Li, Xinxin Gao, Tie Jun Cui
 - **Subjects:** Subjects:
Information Theory (cs.IT); Optics (physics.optics)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The evolution toward next-generation intelligent sensing requires microwave systems to move beyond static detection and achieve high-speed and adaptive perception of dynamic scenes. However, the existing microwave sensing systems have bottlenecks owing to their sequential digital processing chain, limiting the refresh rates to hundreds of hertz, while the existing integrated microwave processors are lack of programmable and scalable capabilities for robust and open-world deployment. To break the bottlenecks, here we report a programmable surface plasmonic neural network (P-SPNN) that enables real-time microwave sensing and automatic recognition of dynamic objects in open-world environment. With a perception latency of 25 ns and a refresh rate exceeding 10 kHz, the P-SPNN system operates more than two orders of magnitude faster than the conventional millimeter-wave sensors, while achieving an energy efficiency of 17 TOPS per W. With 288 programmable phase-modulated neurons, we demonstrate real time and robust classification of persons and cars with 91-97% accuracy in the open road scenarios. By further integrating beam-scanning function, P-SPNN enables multi-dimensional spatial temporal frequency sensing without the digital preprocessing. These results establish P-SPNN as a programmable, scalable, and low-power platform for high-speed perception tasks in realistic world, with broad implications for autonomous driving, intelligent sensing, and next-generation artificial intelligence hardware.
### Title:
          HACMatch Semi-Supervised Rotation Regression with Hardness-Aware Curriculum Pseudo Labeling
 - **Authors:** Mei Li, Huayi Zhou, Suizhi Huang, Yuxiang Lu, Yue Ding, Hongtao Lu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Regressing 3D rotations of objects from 2D images is a crucial yet challenging task, with broad applications in autonomous driving, virtual reality, and robotic control. Existing rotation regression models often rely on large amounts of labeled data for training or require additional information beyond 2D images, such as point clouds or CAD models. Therefore, exploring semi-supervised rotation regression using only a limited number of labeled 2D images is highly valuable. While recent work FisherMatch introduces semi-supervised learning to rotation regression, it suffers from rigid entropy-based pseudo-label filtering that fails to effectively distinguish between reliable and unreliable unlabeled samples. To address this limitation, we propose a hardness-aware curriculum learning framework that dynamically selects pseudo-labeled samples based on their difficulty, progressing from easy to complex examples. We introduce both multi-stage and adaptive curriculum strategies to replace fixed-threshold filtering with more flexible, hardness-aware mechanisms. Additionally, we present a novel structured data augmentation strategy specifically tailored for rotation estimation, which assembles composite images from augmented patches to introduce feature diversity while preserving critical geometric integrity. Comprehensive experiments on PASCAL3D+ and ObjectNet3D demonstrate that our method outperforms existing supervised and semi-supervised baselines, particularly in low-data regimes, validating the effectiveness of our curriculum learning framework and structured augmentation approach.
### Title:
          Cross-Scenario Deraining Adaptation with Unpaired Data: Superpixel Structural Priors and Multi-Stage Pseudo-Rain Synthesis
 - **Authors:** Kangbo Zhao, Miaoxin Guan, Xiang Chen, Yukai Shi, Jinshan Pan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Graphics (cs.GR); Machine Learning (cs.LG); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Image deraining plays a pivotal role in low-level computer vision, serving as a prerequisite for robust outdoor surveillance and autonomous driving systems. While deep learning paradigms have achieved remarkable success in firmly aligned settings, they often suffer from severe performance degradation when generalized to unseen Out-of-Distribution (OOD) scenarios. This failure stems primarily from the significant domain discrepancy between synthetic training datasets and the complex physical dynamics of real-world rain. To address these challenges, this paper proposes a pioneering cross-scenario deraining adaptation framework. Diverging from conventional approaches, our method obviates the requirements for paired rainy observations in the target domain, leveraging exclusively rain-free background images. We design a Superpixel Generation (Sup-Gen) module to extract stable structural priors from the source domain using Simple Linear Iterative Clustering. Subsequently, a Resolution-adaptive Fusion strategy is introduced to align these source structures with target backgrounds through texture similarity, ensuring the synthesis of diverse and realistic pseudo-data. Finally, we implement a pseudo-label re-Synthesize mechanism that employs multi-stage noise generation to simulate realistic rain streaks. This framework functions as a versatile plug-and-play module capable of seamless integration into arbitrary deraining architectures. Extensive experiments on state-of-the-art models demonstrate that our approach yields remarkable PSNR gains of up to 32% to 59% in OOD domains while significantly accelerating training convergence.
### Title:
          Disengagement Analysis and Field Tests of a Prototypical Open-Source Level 4 Autonomous Driving System
 - **Authors:** Marvin Seegert, Christian Oefinger, Korbinian Moller, Christoph Bank, Johannes Betz
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Proprietary Autonomous Driving Systems are typically evaluated through disengagements, unplanned manual interventions to alter vehicle behavior, as annually reported by the California Department of Motor Vehicles. However, the real-world capabilities of prototypical open-source Level 4 vehicles over substantial distances remain largely unexplored. This study evaluates a research vehicle running an Autoware-based software stack across 236 km of mixed traffic. By classifying 30 disengagements across 26 rides with a novel five-level criticality framework, we observed a spatial disengagement rate of 0.127 1/km. Interventions predominantly occurred at lower speeds near static objects and traffic lights. Perception and Planning failures accounted for 40% and 26.7% of disengagements, respectively, largely due to object-tracking losses and operational deadlocks caused by parked vehicles. Frequent, unnecessary interventions highlighted a lack of trust on the part of the safety driver. These results show that while open-source software enables extensive operations, disengagement analysis is vital for uncovering robustness issues missed by standard metrics.
### Title:
          LRC-WeatherNet: LiDAR, RADAR, and Camera Fusion Network for Real-time Weather-type Classification in Autonomous Driving
 - **Authors:** Nour Alhuda Albashir, Lars Pernickel, Danial Hamoud, Idriss Gouigah, Eren Erdal Aksoy
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous vehicles face major perception and navigation challenges in adverse weather such as rain, fog, and snow, which degrade the performance of LiDAR, RADAR, and RGB camera sensors. While each sensor type offers unique strengths, such as RADAR robustness in poor visibility and LiDAR precision in clear conditions, they also suffer distinct limitations when exposed to environmental obstructions. This study proposes LRC-WeatherNet, a novel multi-sensor fusion framework that integrates LiDAR, RADAR, and camera data for real-time classification of weather conditions. By employing both early fusion using a unified Bird's Eye View representation and mid-level gated fusion of modality-specific feature maps, our approach adapts to the varying reliability of each sensor under changing weather. Evaluated on the extensive MSU-4S dataset covering nine weather types, LRC-WeatherNet achieves superior classification performance and computational efficiency, significantly outperforming unimodal baselines in adverse conditions. This work is the first to combine all three modalities for robust, real-time weather classification in autonomous driving. We release our trained models and source code in this https URL.
