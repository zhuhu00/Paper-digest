# Showing new listings for Wednesday, 15 April 2026
## Keyword: SLAM
### Title:
          ReefMapGS: Enabling Large-Scale Underwater Reconstruction by Closing the Loop Between Multimodal SLAM and Gaussian Splatting
 - **Authors:** Daniel Yang, Jungseok Hong, John J. Leonard, Yogesh Girdhar
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian Splatting is a powerful visual representation, providing high-quality and efficient 3D scene reconstruction, but it is crucially dependent on accurate camera poses typically obtained from computationally intensive processes like structure-from-motion that are unsuitable for field robot applications. However, in these domains, multimodal sensor data from acoustic, inertial, pressure, and visual sensors are available and suitable for pose-graph optimization-based SLAM methods that can estimate the vehicle's trajectory and thus our needed camera poses while providing uncertainty. We propose a 3DGS-based incremental reconstruction framework, ReefMapGS, that builds an initial model from a high certainty region and progressively expands to incorporate the whole scene. We reconstruct the scene incrementally by interleaving local tracking of new image observations with optimization of the underlying 3DGS scene. These refined poses are integrated back into the pose-graph to globally optimize the whole trajectory. We show COLMAP-free 3D reconstruction of two underwater reef sites with complex geometry as well as more accurate global pose estimation of our AUV over survey trajectories spanning up to 700 m.
### Title:
          GGD-SLAM: Monocular 3DGS SLAM Powered by Generalizable Motion Model for Dynamic Environments
 - **Authors:** Yi Liu, Haoxuan Xu, Hongbo Duan, Keyu Fan, Zhengyang Zhang, Peiyu Zhuang, Pengting Luo, Houde Liu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual SLAM algorithms achieve significant improvements through the exploration of 3D Gaussian Splatting (3DGS) representations, particularly in generating high-fidelity dense maps. However, they depend on a static environment assumption and experience significant performance degradation in dynamic environments. This paper presents GGD-SLAM, a framework that employs a generalizable motion model to address the challenges of localization and dense mapping in dynamic environments - without predefined semantic annotations or depth input. Specifically, the proposed system employs a First-In-First-Out (FIFO) queue to manage incoming frames, facilitating dynamic semantic feature extraction through a sequential attention mechanism. This is integrated with a dynamic feature enhancer to separate static and dynamic components. Additionally, to minimize dynamic distractors' impact on the static components, we devise a method to fill occluded areas via static information sampling and design a distractor-adaptive Structure Similarity Index Measure (SSIM) loss tailored for dynamic environments, significantly enhancing the system's resilience. Experiments conducted on real-world dynamic datasets demonstrate that the proposed system achieves state-of-the-art performance in camera pose estimation and dense reconstruction in dynamic scenes.
### Title:
          RMGS-SLAM: Real-time Multi-sensor Gaussian Splatting SLAM
 - **Authors:** Dongen Li, Yi Liu, Junqi Liu, Zewen Sun, Zefan Huang, Shuo Sun, Jiahui Liu, Chengran Yuan, Hongliang Guo, Francis E.H. Tay, Marcelo H. Ang Jr
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-time 3D Gaussian splatting (3DGS)-based Simultaneous Localization and Mapping (SLAM) in large-scale real-world environments remains challenging, as existing methods often struggle to jointly achieve low-latency pose estimation, 3D Gaussian reconstruction in step with incoming sensor streams, and long-term global consistency. In this paper, we present a tightly coupled LiDAR-Inertial-Visual (LIV) 3DGS-based SLAM framework for real-time pose estimation and photorealistic mapping in large-scale real-world scenes. The system executes state estimation and 3D Gaussian primitive initialization in parallel with global Gaussian optimization, thereby enabling continuous dense mapping. To improve Gaussian initialization quality and accelerate optimization convergence, we introduce a cascaded strategy that combines feed-forward predictions with voxel-based principal component analysis (voxel-PCA) geometric priors. To enhance global consistency in large scenes, we further perform loop closure directly on the optimized global Gaussian map by estimating loop constraints through Gaussian-based Generalized Iterative Closest Point (GICP) registration, followed by pose-graph optimization. In addition, we collected challenging large-scale looped outdoor SLAM sequences with hardware-synchronized LiDAR-camera-IMU and ground-truth trajectories to support realistic and comprehensive evaluation. Extensive experiments on both public datasets and our dataset demonstrate that the proposed method achieves a strong balance among real-time efficiency, localization accuracy, and rendering quality across diverse and challenging real-world scenes.
## Keyword: odometry
### Title:
          3DRO: Lidar-level SE(3) Direct Radar Odometry Using a 2D Imaging Radar and a Gyroscope
 - **Authors:** Cedric Le Gentil, Daniil Lisus, Timothy D. Barfoot
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recently, the robotics community has regained interest in radar-based perception and state estimation. A 2D imaging radar provides dense 360deg information about the environment. Despite the radar antenna's cone of emission and reception, the collected data is generally assumed to be limited to the plane orthogonal to the radar's spinning axis. Accordingly, most methods based on 2D imaging radars only perform SE(2) state estimation. This paper presents 3DRO, an extension of the SE(2) Direct Radar Odometry (DRO) framework to perform state estimation in SE(3). While still assuming planarity of the data through DRO's 2D velocity estimates, it integrates 3D gyroscope measurements over SO(3) to estimate SE(3) ego motion. While simple, this approach provides lidar-level odometry accuracy as demonstrated using 643km of data from the Boreas-RT dataset.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          3DRO: Lidar-level SE(3) Direct Radar Odometry Using a 2D Imaging Radar and a Gyroscope
 - **Authors:** Cedric Le Gentil, Daniil Lisus, Timothy D. Barfoot
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recently, the robotics community has regained interest in radar-based perception and state estimation. A 2D imaging radar provides dense 360deg information about the environment. Despite the radar antenna's cone of emission and reception, the collected data is generally assumed to be limited to the plane orthogonal to the radar's spinning axis. Accordingly, most methods based on 2D imaging radars only perform SE(2) state estimation. This paper presents 3DRO, an extension of the SE(2) Direct Radar Odometry (DRO) framework to perform state estimation in SE(3). While still assuming planarity of the data through DRO's 2D velocity estimates, it integrates 3D gyroscope measurements over SO(3) to estimate SE(3) ego motion. While simple, this approach provides lidar-level odometry accuracy as demonstrated using 643km of data from the Boreas-RT dataset.
### Title:
          Physics-Grounded Monocular Vehicle Distance Estimation Using Standardized License Plate Typography
 - **Authors:** Manognya Lokesh Reddy, Zheng Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate inter-vehicle distance estimation is a cornerstone of Advanced Driver Assistance Systems (ADAS) and autonomous driving. While LiDAR and radar provide high precision, their high cost prohibits widespread adoption in mass-market vehicles. Monocular camera-based estimation offers a low-cost alternative but suffers from fundamental scale ambiguity. Recent deep learning methods for monocular depth achieve impressive results yet require expensive supervised training, suffer from domain shift, and produce predictions that are difficult to certify for safety-critical deployment. This paper presents a framework that exploits the standardized typography of United States license plates as passive fiducial markers for metric ranging, resolving scale ambiguity through explicit geometric priors without any training data or active illumination. First, a four-method parallel plate detector achieves robust plate reading across the full automotive lighting range. Second, a three-stage state identification engine fusing OCR text matching, multi-design color scoring, and a lightweight neural network classifier provides robust identification across all ambient conditions. Third, hybrid depth fusion with inverse-variance weighting and online scale alignment, combined with a one-dimensional constant-velocity Kalman filter, delivers smoothed distance, relative velocity, and time-to-collision for collision warning. Baseline validation reproduces a 2.3% coefficient of variation in character height measurements and a 36% reduction in distance-estimate variance compared with plate-width methods from prior work. Extensive outdoor experiments confirm a mean absolute error of 2.3% at 10 m and continuous distance output during brief plate occlusions, outperforming deep learning baselines by a factor of five in relative error.
### Title:
          HyperLiDAR: Adaptive Post-Deployment LiDAR Segmentation via Hyperdimensional Computing
 - **Authors:** Ivannia Gomez Moreno, Yi Yao, Ye Tian, Xiaofan Yu, Flavio Ponzina, Michael Sullivan, Jingyi Zhang, Mingyu Yang, Hun Seok Kim, Tajana Rosing
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR semantic segmentation plays a pivotal role in 3D scene understanding for edge applications such as autonomous driving. However, significant challenges remain for real-world deployments, particularly for on-device post-deployment adaptation. Real-world environments can shift as the system navigates through different locations, leading to substantial performance degradation without effective and timely model adaptation. Furthermore, edge systems operate under strict computational and energy constraints, making it infeasible to adapt conventional segmentation models (based on large neural networks) directly on-device. To address the above challenges, we introduce HyperLiDAR, the first lightweight, post-deployment LiDAR segmentation framework based on Hyperdimensional Computing (HDC). The design of HyperLiDAR fully leverages the fast learning and high efficiency of HDC, inspired by how the human brain processes information. To further improve the adaptation efficiency, we identify the high data volume per scan as a key bottleneck and introduce a buffer selection strategy that focuses learning on the most informative points. We conduct extensive evaluations on two state-of-the-art LiDAR segmentation benchmarks and two representative devices. Our results show that HyperLiDAR outperforms or achieves comparable adaptation performance to state-of-the-art segmentation methods, while achieving up to a 13.8x speedup in retraining.
### Title:
          RACF: A Resilient Autonomous Car Framework with Object Distance Correction
 - **Authors:** Chieh Tsai, Hossein Rastgoftar, Salim Hariri
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous vehicles are increasingly deployed in safety-critical applications, where sensing failures or cyberphysical attacks can lead to unsafe operations resulting in human loss and/or severe physical damages. Reliable real-time perception is therefore critically important for their safe operations and acceptability. For example, vision-based distance estimation is vulnerable to environmental degradation and adversarial perturbations, and existing defenses are often reactive and too slow to promptly mitigate their impacts on safe operations. We present a Resilient Autonomous Car Framework (RACF) that incorporates an Object Distance Correction Algorithm (ODCA) to improve perception-layer robustness through redundancy and diversity across a depth camera, LiDAR, and physics-based kinematics. Within this framework, when obstacle distance estimation produced by depth camera is inconsistent, a cross-sensor gate activates the correction algorithm to fix the detected inconsistency. We have experiment with the proposed resilient car framework and evaluate its performance on a testbed implemented using the Quanser QCar 2 platform. The presented framework achieved up to 35% RMSE reduction under strong corruption and improves stop compliance and braking latency, while operating in real time. These results demonstrate a practical and lightweight approach to resilient perception for safety-critical autonomous driving
### Title:
          RMGS-SLAM: Real-time Multi-sensor Gaussian Splatting SLAM
 - **Authors:** Dongen Li, Yi Liu, Junqi Liu, Zewen Sun, Zefan Huang, Shuo Sun, Jiahui Liu, Chengran Yuan, Hongliang Guo, Francis E.H. Tay, Marcelo H. Ang Jr
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-time 3D Gaussian splatting (3DGS)-based Simultaneous Localization and Mapping (SLAM) in large-scale real-world environments remains challenging, as existing methods often struggle to jointly achieve low-latency pose estimation, 3D Gaussian reconstruction in step with incoming sensor streams, and long-term global consistency. In this paper, we present a tightly coupled LiDAR-Inertial-Visual (LIV) 3DGS-based SLAM framework for real-time pose estimation and photorealistic mapping in large-scale real-world scenes. The system executes state estimation and 3D Gaussian primitive initialization in parallel with global Gaussian optimization, thereby enabling continuous dense mapping. To improve Gaussian initialization quality and accelerate optimization convergence, we introduce a cascaded strategy that combines feed-forward predictions with voxel-based principal component analysis (voxel-PCA) geometric priors. To enhance global consistency in large scenes, we further perform loop closure directly on the optimized global Gaussian map by estimating loop constraints through Gaussian-based Generalized Iterative Closest Point (GICP) registration, followed by pose-graph optimization. In addition, we collected challenging large-scale looped outdoor SLAM sequences with hardware-synchronized LiDAR-camera-IMU and ground-truth trajectories to support realistic and comprehensive evaluation. Extensive experiments on both public datasets and our dataset demonstrate that the proposed method achieves a strong balance among real-time efficiency, localization accuracy, and rendering quality across diverse and challenging real-world scenes.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          A Geometric Algebra-informed NeRF Framework for Generalizable Wireless Channel Prediction
 - **Authors:** Jingzhou Shen, Luis Lago Enamorado, Shiwen Mao, Xuyu Wang
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we propose the geometric algebra-informed neural radiance fields (GAI-NeRF), a novel framework for wireless channel prediction that leverages geometric algebra attention mechanisms to capture ray-object interactions in complex propagation environments. Our approach incorporates global token representations, drawing inspiration from transformer architectures in language and vision domains, to aggregate learned spatial-electromagnetic features and enhance scene understanding. We identify limitations in conventional static ray tracing modules that hinder model generalization and address this challenge through a new ray tracing architecture. This design enables effective generalization across diverse wireless scenarios while maintaining computational efficiency. Experimental results demonstrate that GAI-NeRF achieves superior performance in channel prediction tasks by combining geometric algebra principles with neural scene representations, offering a promising direction for next-generation wireless communication systems. Moreover, GAI-NeRF greatly outperforms existing methods across multiple wireless scenarios. To ensure comprehensive assessment, we further evaluate our approach against multiple benchmarks using newly collected real-world indoor datasets tailored for single-scene downstream tasks and generalization testing, confirming its robust performance in unseen environments and establishing its high efficacy for wireless channel prediction.
## Keyword: mapping
### Title:
          EigenCoin: sassanid coins classification based on Bhattacharyya distance
 - **Authors:** Rahele Allahverdi, Mohammad Mahdi Dehshibi, Azam Bastanfard, Daryoosh Akbarzadeh
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Solving pattern recognition problems using imbalanced databases is a hot topic, which entices researchers to bring it into focus. Therefore, we consider this problem in the application of Sassanid coins classification. Our focus is not only on proposing EigenCoin manifold with Bhattacharyya distance for the classification task, but also on testing the influence of the holistic and feature-based approaches. EigenCoin consists of three main steps namely manifold construction, mapping test data, and classification. Conducted experiments show EigenCoin outperformed other observed algorithms and achieved the accuracy from 9.45% up to 21.75%, while it has the capability of handling the over-fitting problem.
### Title:
          Network Slice Embedding over Space Division Multiplexed Elastic Optical Networks
 - **Authors:** Divya Khanure, Riti Gour, Congzhou Li, Jason P. Jue
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Network slicing over space division multiplexed elastic optical networks (SDM EONs) enables efficient multiservice provisioning on a shared optical substrate. However, embedding such slices requires coordinated spectrum and compute resource management under dynamic traffic, which most existing RMCSA studies treat independently. This paper focuses on the network slice embedding problem over space division multiplexed elastic optical networks (SDM EONs), aiming to develop efficient resource allocation strategies that ensure both high utilization and reliable service performance. While prior studies have investigated routing, modulation format, core, and spectrum allocation (RMCSA), they typically consider these dimensions separately from compute placement. To address this gap, this paper proposes a Waypoint Assisted Multi Segment Slice Mapping (WMSM) scheme, which integrates compute placement with spectrum allocation in a sequential but coupled manner to enable more flexible resource placement and improved spectrum efficiency. Numerical results show that WMSM improves acceptance ratios by up to 27% under high load conditions, while achieving up to 47% lower total provisioning cost relative to the baseline strategy. These results highlight the benefits of integrated compute spectrum provisioning and provide design insights for scalable, compute aware optical slice mapping.
### Title:
          AutoSurrogate: An LLM-Driven Multi-Agent Framework for Autonomous Construction of Deep Learning Surrogate Models in Subsurface Flow
 - **Authors:** Jiale Liu, Nanzhe Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-fidelity numerical simulation of subsurface flow is computationally intensive, especially for many-query tasks such as uncertainty quantification and data assimilation. Deep learning (DL) surrogates can significantly accelerate forward simulations, yet constructing them requires substantial machine learning (ML) expertise - from architecture design to hyperparameter tuning - that most domain scientists do not possess. Furthermore, the process is predominantly manual and relies heavily on heuristic choices. This expertise gap remains a key barrier to the broader adoption of DL surrogate techniques. For this reason, we present AutoSurrogate, a large-language-model-driven multi-agent framework that enables practitioners without ML expertise to build high-quality surrogates for subsurface flow problems through natural-language instructions. Given simulation data and optional preferences, four specialized agents collaboratively execute data profiling, architecture selection from a model zoo, Bayesian hyperparameter optimization, model training, and quality assessment against user-specified thresholds. The system also handles common failure modes autonomously, including restarting training with adjusted configurations when numerical instabilities occur and switching to alternative architectures when predictive accuracy falls short of targets. In our setting, a single natural-language sentence can be sufficient to produce a deployment-ready surrogate model, with minimum human intervention required at any intermediate stage. We demonstrate the utility of AutoSurrogate on a 3D geological carbon storage modeling task, mapping permeability fields to pressure and CO$_2$ saturation fields over 31 timesteps. Without any manual tuning, AutoSurrogate is able to outperform expert-designed baselines and domain-agnostic AutoML methods, demonstrating strong potential for practical deployment.
### Title:
          Multi-Head Residual-Gated DeepONet for Coherent Nonlinear Wave Dynamics
 - **Authors:** Zhiwei Fan, Yiming Pan, Daniel Coca
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Coherent nonlinear wave dynamics are often strongly shaped by a compact set of physically meaningful descriptors of the initial state. Traditional neural operators typically treat the input-output mapping as a largely black-box high-dimensional regression problem, without explicitly exploiting this structured physical context. Common feature-integration strategies usually rely on direct concatenation or FiLM-style affine modulation in hidden latent spaces. Here we introduce a different paradigm, loosely inspired by the complementary roles of state evolution and physically meaningful observables in quantum mechanics: the wave field is learned through a standard DeepONet state pathway, while compact physical descriptors follow a parallel conditioning pathway and act as residual modulation factors on the state prediction. Based on this idea, we develop a Multi-Head Residual-Gated DeepONet (MH-RG), which combines a pre-branch residual modulator, a branch residual gate, and a trunk residual gate with a low-rank multi-head mechanism to capture multiple complementary conditioned response patterns without prohibitive parameter growth. We evaluate the framework on representative benchmarks including highly nonlinear conservative wave dynamics and dissipative trapped dynamics and further perform detailed mechanistic analyses of the learned multi-head gating behavior. Compared with feature-augmented baselines, MH-RG DeepONet achieves consistently lower error while better preserving phase coherence and the fidelity of physically relevant dynamical quantities.
### Title:
          Sample Complexity of Autoregressive Reasoning: Chain-of-Thought vs. End-to-End
 - **Authors:** Steve Hanneke, Idan Mehalel, Shay Moran
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern large language models generate text autoregressively, producing tokens one at a time. To study the learnability of such systems, Joshi et al. (COLT 2025) introduced a PAC-learning framework for next-token generators, the primitive underlying autoregressive models. In this framework, an unknown next-token generator maps a sequence of tokens to the next token and is iteratively applied for $T$ steps, producing a chain of tokens whose final token constitutes the model's output. The learning task is to learn the input-output mapping induced by this autoregressive process. Depending on the available supervision, training examples may reveal only the final output (End-to-End supervision) or the entire generated chain (Chain-of-Thought supervision). This raises two natural questions: how the sample complexity depends on the generation length $T$, and how much Chain-of-Thought supervision can reduce this dependence. In this work we give a nearly complete answer to both questions by uncovering a taxonomy of how the sample complexity scales with $T$. For End-to-End learning, we show that the landscape is remarkably rich: subject to mild conditions, essentially any growth rate $r(T)$ between constant and linear can arise as the sample complexity, and combined with the linear upper bound of Joshi et al., this yields an essentially complete characterization. In contrast, under Chain-of-Thought supervision we show that the sample complexity is independent of $T$, demonstrating that access to intermediate reasoning steps can eliminate the dependence on the generation length altogether. Our analysis introduces new combinatorial tools, and as corollaries we resolve several open questions posed by Joshi et al. regarding the dependence of learnability on the generation length and the role of Chain-of-Thought supervision.
### Title:
          Accelerating Microswimmer Simulations via a Heterogeneous Pipelined Parallel-in-Time Framework
 - **Authors:** Ruixiang Huang, Weifan Liu
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Simulating large-scale microswimmer dynamics in viscous fluid poses significant challenges due to the coupled high spatial and temporal complexity. Conventional high-performance computing (HPC) methods often address these two dimensions in isolation, leaving a critical gap for synergistic acceleration. This paper introduces a heterogeneous CPU--GPU computing framework specifically optimized for the long-time simulation of filamentous microswimmers in viscous fluid. We propose a two-level parallelization strategy: (1) high-intensity GPU kernels to resolve the quadratic spatial interactions given by the Method of Regularized Stokeslets (MRS), and (2) a distributed MPI-GPU pipelined Parareal architecture to exploit temporal concurrency. By mapping the asynchronous pipeline onto multiple GPU devices, our framework effectively overlaps coarse and fine propagators, overcoming the serial bottlenecks of traditional Parareal method. Furthermore, we employ a GPU-optimized numerical routine for computing the matrix square root arising in the numerical scheme of the filamentous microswimmer simulations. Theoretical analysis of the efficiency improvement of the pipelined Parareal is presented. Numerical experiments demonstrate that the proposed framework achieves order-of-magnitude speedups over CPU-only methods, providing a scalable pathway for simulating complex emergent behaviors in large-scale biology and physics systems.
### Title:
          INST-Align: Implicit Neural Alignment for Spatial Transcriptomics via Canonical Expression Fields
 - **Authors:** Bonian Han, Cong Qi, Przemyslaw Musialski, Zhi Wei
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spatial transcriptomics (ST) measures mRNA expression while preserving spatial organization, but multi-slice analysis faces two coupled difficulties: large non-rigid deformations across slices and inter-slice batch effects when alignment and integration are treated independently. We present INST-Align, an unsupervised pairwise framework that couples a coordinate-based deformation network with a shared Canonical Expression Field, an implicit neural representation mapping spatial coordinates to expression embeddings, for joint alignment and reconstruction. A two-phase training strategy first establishes a stable canonical embedding space and then jointly optimizes deformation and spatial-feature matching, enabling mutually constrained alignment and representation learning. Cross-slice parameter sharing of the canonical field regularizes ambiguous correspondences and absorbs batch variation. Across nine datasets, INST-Align achieves state-of-the-art mean OT Accuracy (0.702), NN Accuracy (0.719), and Chamfer distance, with Chamfer reductions of up to 94.9\% on large-deformation sections relative to the strongest baseline. The framework also yields biologically meaningful spatial embeddings and coherent 3D tissue reconstruction. The code will be released after review phase.
### Title:
          Beyond Perception Errors: Semantic Fixation in Large Vision-Language Models
 - **Authors:** Md Tanvirul Alam
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large vision-language models (VLMs) often rely on familiar semantic priors, but existing evaluations do not cleanly separate perception failures from rule-mapping failures. We study this behavior as semantic fixation: preserving a default interpretation even when the prompt specifies an alternative, equally valid mapping. To isolate this effect, we introduce VLM-Fix, a controlled benchmark over four abstract strategy games that evaluates identical terminal board states under paired standard and inverse rule formulations. Across 14 open and closed VLMs, accuracy consistently favors standard rules, revealing a robust semantic-fixation gap. Prompt interventions support this mechanism: neutral alias prompts substantially narrow the inverse-rule gap, while semantically loaded aliases reopen it. Post-training is strongly rule-aligned: training on one rule improves same-rule transfer but hurts opposite-rule transfer, while joint-rule training improves broader transfer. To test external validity beyond synthetic games, we evaluate analogous defamiliarization interventions on VLMBias and observe the same qualitative pattern. Finally, late-layer activation steering partially recovers degraded performance, indicating that semantic-fixation errors are at least partly editable in late representations. Project page, code, and dataset available at this https URL.
### Title:
          Style-Decoupled Adaptive Routing Network for Underwater Image Enhancement
 - **Authors:** Hang Xu, Chen Long, Bing Wang, Hao Chen, Zhen Dong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Underwater Image Enhancement (UIE) is essential for robust visual perception in marine applications. However, existing methods predominantly rely on uniform mapping tailored to average dataset distributions, leading to over-processing mildly degraded images or insufficient recovery for severe ones. To address this challenge, we propose a novel adaptive enhancement framework, SDAR-Net. Unlike existing uniform paradigms, it first decouples specific degradation styles from the input and subsequently modulates the enhancement process adaptively. Specifically, since underwater degradation primarily shifts the appearance while keeping the scene structure, SDAR-Net formulates image features into dynamic degradation style embeddings and static scene structural representations through a carefully designed training framework. Subsequently, we introduce an adaptive routing mechanism. By evaluating style features and adaptively predicting soft weights at different enhancement states, it guides the weighted fusion of the corresponding image representations, accurately satisfying the adaptive restoration demands of each image. Extensive experiments show that SDAR-Net achieves a new state-of-the-art (SOTA) performance with a PSNR of 25.72 dB on real-world benchmark, and demonstrates its utility in downstream vision tasks. Our code is available at this https URL.
### Title:
          DreamStereo: Towards Real-Time Stereo Inpainting for HD Videos
 - **Authors:** Yuan Huang, Sijie Zhao, Jing Cheng, Hao Xu, Shaohui Jiao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Stereo video inpainting, which aims to fill the occluded regions of warped videos with visually coherent content while maintaining temporal consistency, remains a challenging open problem. The regions to be filled are scattered along object boundaries and occupy only a small fraction of each frame, leading to two key challenges. First, existing approaches perform poorly on such tasks due to the scarcity of high-quality stereo inpainting datasets, which limits their ability to learn effective inpainting priors. Second, these methods apply equal processing to all regions of the frame, even though most pixels require no modification, resulting in substantial redundant computation. To address these issues, we introduce three interconnected components. We first propose Gradient-Aware Parallax Warping (GAPW), which leverages backward warping and the gradient of the coordinate mapping function to obtain continuous edges and smooth occlusion regions. Then, a Parallax-Based Dual Projection (PBDP) strategy is introduced, which incorporates GAPW to produce geometrically consistent stereo inpainting pairs and accurate occlusion masks without requiring stereo videos. Finally, we present Sparsity-Aware Stereo Inpainting (SASI), which reduces over 70% of redundant tokens, achieving a 10.7x speedup during diffusion inference and delivering results comparable to its full-computation counterpart, enabling real-time processing of HD (768 x 1280) videos at 25 FPS on a single A100 GPU.
### Title:
          Compiling Activation Steering into Weights via Null-Space Constraints for Stealthy Backdoors
 - **Authors:** Rui Yin, Tianxu Han, Naen Xu, Changjiang Li, Ping He, Chunyi Zhou, Jun Wang, Zhihui Fu, Tianyu Du, Jinbao Li, Shouling Ji
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Safety-aligned large language models (LLMs) are increasingly deployed in real-world pipelines, yet this deployment also enlarges the supply-chain attack surface: adversaries can distribute backdoored checkpoints that behave normally under standard evaluation but jailbreak when a hidden trigger is present. Recent post-hoc weight-editing methods offer an efficient approach to injecting such backdoors by directly modifying model weights to map a trigger to an attacker-specified response. However, existing methods typically optimize a token-level mapping that forces an affirmative prefix (e.g., ``Sure''), which does not guarantee sustained harmful output -- the model may begin with apparent agreement yet revert to safety-aligned refusal within a few decoding steps. We address this reliability gap by shifting the backdoor objective from surface tokens to internal representations. We extract a steering vector that captures the difference between compliant and refusal behaviors, and compile it into a persistent weight modification that activates only when the trigger is present. To preserve stealthiness and benign utility, we impose a null-space constraint so that the injected edit remains dormant on clean inputs. The method is efficient, requiring only a small set of examples and admitting a closed-form solution. Across multiple safety-aligned LLMs and jailbreak benchmarks, our method achieves high triggered attack success while maintaining non-triggered safety and general utility.
### Title:
          HARP: Hadamard-Domain Write-and-Verify for Noise-Robust RRAM Programming
 - **Authors:** Ilhuan Choi, Jiwon Yoo, Yoona Lee, Yewon Jeong, Jason Jaesung Lee, Woo-Seok Choi
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Write-and-verify (WV) is essential for programming multi-level RRAM weights, yet under scaled-voltage and low-SNR conditions the verify read increasingly limits mapping accuracy, convergence speed and energy. We propose a Hadamard-domain WV framework that improves verify reliability without adding analog hardware. % without introducing additional analog blocks % while leveraging the existing analog front-end \emph{HD-PV} (Hadamard-Encoded Parallel-Verify) replaces conventional one-hot verify reads with $N$ orthogonal Hadamard patterns for an $N$-cell column. Changing the read basis without increasing the column-level read count, inverse Hadamard decoding reduces uncorrelated read-noise variance by a factor of $N$ and cancels common-mode disturbances. \emph{HARP} (Hadamard-based ADC-Energy-Reduced Parallel-Verify) further exploits the fact that WV needs only ternary update decisions, not full digital codes, and replaces SAR conversions with lightweight compare-only operations. Across CIFAR-10, CIFAR-100, and keyword spotting under severe read noise, conventional WV loses over 20\,\% accuracy on CIFAR-10, while HD-PV and HARP limit the loss to 0.6\,\% and 1\,\% under the same memory footprint. Compared to conventional multi-read averaging for noise reduction, HD-PV and HARP achieve comparable accuracy with up to $6.1\times$ and $3.5\times$ lower latency and $6.2\times$ and $9.5\times$ better energy efficiency, respectively. To the best of our knowledge, this is the first application of Hadamard-encoded verification to RRAM WV.
### Title:
          Enhanced Optimal Power Flow Using a Trained Neural Network Surrogate for Distribution Grid Constraints
 - **Authors:** Savvas Panagi, Chrysovalantis Spanias, Petros Aristidou
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The growing penetration of distributed energy resources (DERs), electric vehicles (EVs), and heat pumps (HPs) in distribution networks underscores the need for secure, computationally efficient optimal power flow (OPF) solutions. Traditional OPF formulations often suffer from scalability limitations and may rely on relaxations/approximations whose exactness is not guaranteed. This paper proposes a framework in which a trained neural network (NN) surrogate is embedded directly within the OPF as a constraint replacement. Specifically, the nonlinear power-flow-to-voltage mapping is replaced by an exact mixed-integer linear encoding of the NN (i.e., the NN input-output map is represented without approximation), while all remaining OPF constraints are preserved. Using a realistic low-voltage network with integrated PV, EVs, and HPs, the proposed method achieves high voltage accuracy during post-solution AC power flow validation, with maximum deviations of less than 1.0 V in the examined test cases. The resulting NN-OPF problems are solved to global optimality within the MILP solver tolerance, and numerical results demonstrate substantially reduced computation time compared to nonlinear OPF models, with performance competitive with SOCP-based DistFlow formulations.
### Title:
          D-BDM: A Direct and Efficient Boundary-Based Occupancy Grid Mapping Framework for LiDARs
 - **Authors:** Benxu Tang, Yixi Cai, Fanze Kong, Longji Yin, Fu Zhang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Efficient and scalable 3D occupancy mapping is essential for autonomous robot applications in unknown environments. However, traditional occupancy grid representations suffer from two fundamental limitations. First, explicitly storing all voxels in three-dimensional space leads to prohibitive memory consumption. Second, exhaustive ray casting incurs high update latency. A recent representation alleviate memory demands by maintaining only the voxels on the two-dimensional boundary, yet they still rely on full ray casting updates. This work advances the boundary-based framework with a highly efficient update scheme. We introduce a truncated ray casting strategy that restricts voxel traversal to the exterior of the boundary, which dramatically reduces the number of updated voxels. In addition, we propose a direct boundary update mechanism that removes the need for an auxiliary local 3D occupancy grid, further reducing memory usage and simplifying the map update pipeline. We name our framework as D-BDM. Extensive evaluations on public datasets demonstrate that our approach achieves significantly lower update time and reduced memory consumption compared with the baseline methods, as well as the prior boundary-based approach.
### Title:
          Euler-inspired Decoupling Neural Operator for Efficient Pansharpening
 - **Authors:** Anqi Zhu, Mengting Ma, Yizhen Jiang, Xiangdong Li, Kai Zheng, Jiaxin Li, Wei Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pansharpening aims to synthesize high-resolution multispectral (HR-MS) images by fusing the spatial textures of panchromatic (PAN) images with the spectral information of low-resolution multispectral (LR-MS) images. While recent deep learning paradigms, especially diffusion-based operators, have pushed the performance boundaries, they often encounter spectral-spatial blurring and prohibitive computational costs due to their stochastic nature and iterative sampling. In this paper, we propose the Euler-inspired Decoupling Neural Operator (EDNO), a physics-inspired framework that redefines pansharpening as a continuous functional mapping in the frequency domain. Departing from conventional Cartesian feature processing, our EDNO leverages Euler's formula to transform features into a polar coordinate system, enabling a novel explicit-implicit interaction mechanism. Specifically, we develop the Euler Feature Interaction Layer (EFIL), which decouples the fusion task into two specialized modules: 1) Explicit Feature Interaction Module, utilizing a linear weighting scheme to simulate phase rotation for adaptive geometric alignment; and 2) Implicit Feature Interaction Module, employing a feed-forward network to model spectral distributions for superior color consistency. By operating in the frequency domain, EDNO inherently captures global receptive fields while maintaining discretization-invariance. Experimental results on the three datasets demonstrate that EDNO offers a superior efficiency-performance balance compared to heavyweight architectures.
### Title:
          IDEA: An Interpretable and Editable Decision-Making Framework for LLMs via Verbal-to-Numeric Calibration
 - **Authors:** Yanji He, Yuxin Jiang, Yiwen Wu, Bo Huang, Jiaheng Wei, Wei Wang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models are increasingly deployed for decision-making, yet their adoption in high-stakes domains remains limited by miscalibrated probabilities, unfaithful explanations, and inability to incorporate expert knowledge precisely. We propose IDEA, a framework that extracts LLM decision knowledge into an interpretable parametric model over semantically meaningful factors. Through joint learning of verbal-to-numerical mappings and decision parameters via EM, correlated sampling that preserves factor dependencies, and direct parameter editing with mathematical guarantees, IDEA produces calibrated probabilities while enabling quantitative human-AI collaboration. Experiments across five datasets show IDEA with Qwen-3-32B (78.6%) outperforms DeepSeek R1 (68.1%) and GPT-5.2 (77.9%), achieving perfect factor exclusion and exact calibration -- precision unattainable through prompting alone. The implementation is publicly available at this https URL.
### Title:
          Pressure-Robust Fortin-Soulie Elements of the Stokes Equation on Curved Domains
 - **Authors:** Wei Chen, Zhen Liu
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a pressure-robust and element-wise divergence-free nonconforming finite element method for the Stokes problem on curved domains. The discrete element is constructed by mapping the Fortin-Soulie element from a reference triangle using an isoparametric mapping for the geometry and a Piola transform for the function space. The inf-sup condition and the error estimate with optimal convergence rate are proved. Pressure-robustness is obtained by replacing the discrete velocity test functions with the first-order Raviart-Thomas functions. Numerical examples are provided to validate the theoretical results.
### Title:
          Actuation space reduction to facilitate insightful shape matching in a novel reconfigurable tendon driven continuum manipulator
 - **Authors:** Sabyasachi Dash, John Golden, Girish Krishnan
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In tendon driven continuum manipulators (TDCMs), reconfiguring the tendon routing enables tailored spatial deformation of the backbone. This work presents a design in which tendons can be rerouted either prior to or after actuation by actively rotating the individual spacer disks. Each disk rotation thus adds a degree of freedom to the actuation space, complicating the mapping from a desired backbone curve to the corresponding actuator inputs. However, when the backbone shape is projected into an intermediate space defined by curvature and torsion (C-T), patterns emerge that highlight which disks are most influential in achieving a global shape. This insight enables a simplified, sequential shape-matching strategy: first, the proximal and intermediate disks are rotated to approximate the global shape; then, the distal disks are adjusted to fine-tune the end-effector position with minimal impact on the overall shape. The proposed actuation framework offers a model-free alternative to conventional control approaches, bypassing the complexities of modeling reconfigurable TDCMs.
### Title:
          Image-to-Image Translation Framework Embedded with Rotation Symmetry Priors
 - **Authors:** Feiyu Tan, Heran Yang, Qihong Duan, Kai Ye, Qi Xie, Deyu Meng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Image-to-image translation (I2I) is a fundamental task in computer vision, focused on mapping an input image from a source domain to a corresponding image in a target domain while preserving domain-invariant features and adapting domain-specific attributes. Despite the remarkable success of deep learning-based I2I approaches, the lack of paired data and unsupervised learning framework still hinder their effectiveness. In this work, we address the challenge by incorporating transformation symmetry priors into image-to-image translation networks. Specifically, we introduce rotation group equivariant convolutions to achieve rotation equivariant I2I framework, a novel contribution, to the best of our knowledge, along this research direction. This design ensures the preservation of rotation symmetry, one of the most intrinsic and domain-invariant properties of natural and scientific images, throughout the network. Furthermore, we conduct a systematic study on image symmetry priors on real dataset and propose a novel transformation learnable equivariant convolutions (TL-Conv) that adaptively learns transformation groups, enhancing symmetry preservation across diverse datasets. We also provide a theoretical analysis of the equivariance error of TL-Conv, proving that it maintains exact equivariance in continuous domains and provide a bound for the error in discrete cases. Through extensive experiments across a range of I2I tasks, we validate the effectiveness and superior performance of our approach, highlighting the potential of equivariant networks in enhancing generation quality and its broad applicability. Our code is available at this https URL
### Title:
          GGD-SLAM: Monocular 3DGS SLAM Powered by Generalizable Motion Model for Dynamic Environments
 - **Authors:** Yi Liu, Haoxuan Xu, Hongbo Duan, Keyu Fan, Zhengyang Zhang, Peiyu Zhuang, Pengting Luo, Houde Liu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual SLAM algorithms achieve significant improvements through the exploration of 3D Gaussian Splatting (3DGS) representations, particularly in generating high-fidelity dense maps. However, they depend on a static environment assumption and experience significant performance degradation in dynamic environments. This paper presents GGD-SLAM, a framework that employs a generalizable motion model to address the challenges of localization and dense mapping in dynamic environments - without predefined semantic annotations or depth input. Specifically, the proposed system employs a First-In-First-Out (FIFO) queue to manage incoming frames, facilitating dynamic semantic feature extraction through a sequential attention mechanism. This is integrated with a dynamic feature enhancer to separate static and dynamic components. Additionally, to minimize dynamic distractors' impact on the static components, we devise a method to fill occluded areas via static information sampling and design a distractor-adaptive Structure Similarity Index Measure (SSIM) loss tailored for dynamic environments, significantly enhancing the system's resilience. Experiments conducted on real-world dynamic datasets demonstrate that the proposed system achieves state-of-the-art performance in camera pose estimation and dense reconstruction in dynamic scenes.
### Title:
          Towards Long-horizon Agentic Multimodal Search
 - **Authors:** Yifan Du, Zikang Liu, Jinbiao Peng, Jie Wu, Junyi Li, Jinyang Li, Wayne Xin Zhao, Ji-Rong Wen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal deep search agents have shown great potential in solving complex tasks by iteratively collecting textual and visual evidence. However, managing the heterogeneous information and high token costs associated with multimodal inputs over long horizons remains a critical challenge, as existing methods often suffer from context explosion or the loss of crucial visual signals. To address this, we propose a novel Long-horizon MultiModal deep search framework, named LMM-Searcher, centered on a file-based visual representation mechanism. By offloading visual assets to an external file system and mapping them to lightweight textual identifiers (UIDs), our approach mitigates context overhead while preserving multimodal information for future access. We equip the agent with a tailored fetch-image tool, enabling a progressive, on-demand visual loading strategy for active perception. Furthermore, we introduce a data synthesis pipeline designed to generate queries requiring complex cross-modal multi-hop reasoning. Using this pipeline, we distill 12K high-quality trajectories to fine-tune Qwen3-VL-Thinking-30A3B into a specialized multimodal deep search agent. Extensive experiments across four benchmarks demonstrate that our method successfully scales to 100-turn search horizons, achieving state-of-the-art performance among open-source models on challenging long-horizon benchmarks like MM-BrowseComp and MMSearch-Plus, while also exhibiting strong generalizability across different base models. Our code will be released in this https URL.
### Title:
          Representing 3D Faces with Learnable B-Spline Volumes
 - **Authors:** Prashanth Chandran, Daoye Wang, Timo Bolkart
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present CUBE (Control-based Unified B-spline Encoding), a new geometric representation for human faces that combines B-spline volumes with learned features, and demonstrate its use as a decoder for 3D scan registration and monocular 3D face reconstruction. Unlike existing B-spline representations with 3D control points, CUBE is parametrized by a lattice (e.g., 8 x 8 x 8) of high-dimensional control features, increasing the model's expressivity. These features define a continuous, two-stage mapping from a 3D parametric domain to 3D Euclidean space via an intermediate feature space. First, high-dimensional control features are locally blended using the B-spline bases, yielding a high-dimensional feature vector whose first three values define a 3D base mesh. A small MLP then processes this feature vector to predict a residual displacement from the base shape, yielding the final refined 3D coordinates. To reconstruct 3D surfaces in dense semantic correspondence, CUBE is queried at 3D coordinates sampled from a fixed template mesh. Crucially, CUBE retains the local support property of traditional B-spline representations, enabling local surface editing by updating individual control features. We demonstrate the strengths of this representation by training transformer-based encoders to predict CUBE's control features from unstructured point clouds and monocular images, achieving state-of-the-art scan registration results compared to recent baselines.
### Title:
          Robotic Manipulation is Vision-to-Geometry Mapping ($f(v) \rightarrow G$): Vision-Geometry Backbones over Language and Video Models
 - **Authors:** Zijian Song, Qichang Li, Jiawei Zhou, Zhenlong Yuan, Tianshui Chen, Liang Lin, Guangrun Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 At its core, robotic manipulation is a problem of vision-to-geometry mapping ($f(v) \rightarrow G$). Physical actions are fundamentally defined by geometric properties like 3D positions and spatial relationships. Consequently, we argue that the foundation for generalizable robotic control should be a vision-geometry backbone, rather than the widely adopted vision-language or video models. Conventional VLA and video-predictive models rely on backbones pretrained on large-scale 2D image-text or temporal pixel data. While effective, their representations are largely shaped by semantic concepts or 2D priors, which do not intrinsically align with the precise 3D geometric nature required for physical manipulation. Driven by this insight, we propose the Vision-Geometry-Action (VGA) model, which directly conditions action generation on pretrained native 3D representations. Specifically, VGA replaces conventional language or video backbones with a pretrained 3D world model, establishing a seamless vision-to-geometry mapping that translates visual inputs directly into physical actions. To further enhance geometric consistency, we introduce a Progressive Volumetric Modulation module and adopt a joint training strategy. Extensive experiments validate the effectiveness of our approach. In simulation benchmarks, VGA outperforms top-tier VLA baselines including $\pi_{0.5}$ and GeoVLA, demonstrating its superiority in precise manipulation. More importantly, VGA exhibits remarkable zero-shot generalization to unseen viewpoints in real-world deployments, consistently outperforming $\pi_{0.5}$. These results highlight that operating on native 3D representations-rather than translating through language or 2D video priors-is a highly promising direction for achieving generalizable physical intelligence.
### Title:
          RMGS-SLAM: Real-time Multi-sensor Gaussian Splatting SLAM
 - **Authors:** Dongen Li, Yi Liu, Junqi Liu, Zewen Sun, Zefan Huang, Shuo Sun, Jiahui Liu, Chengran Yuan, Hongliang Guo, Francis E.H. Tay, Marcelo H. Ang Jr
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-time 3D Gaussian splatting (3DGS)-based Simultaneous Localization and Mapping (SLAM) in large-scale real-world environments remains challenging, as existing methods often struggle to jointly achieve low-latency pose estimation, 3D Gaussian reconstruction in step with incoming sensor streams, and long-term global consistency. In this paper, we present a tightly coupled LiDAR-Inertial-Visual (LIV) 3DGS-based SLAM framework for real-time pose estimation and photorealistic mapping in large-scale real-world scenes. The system executes state estimation and 3D Gaussian primitive initialization in parallel with global Gaussian optimization, thereby enabling continuous dense mapping. To improve Gaussian initialization quality and accelerate optimization convergence, we introduce a cascaded strategy that combines feed-forward predictions with voxel-based principal component analysis (voxel-PCA) geometric priors. To enhance global consistency in large scenes, we further perform loop closure directly on the optimized global Gaussian map by estimating loop constraints through Gaussian-based Generalized Iterative Closest Point (GICP) registration, followed by pose-graph optimization. In addition, we collected challenging large-scale looped outdoor SLAM sequences with hardware-synchronized LiDAR-camera-IMU and ground-truth trajectories to support realistic and comprehensive evaluation. Extensive experiments on both public datasets and our dataset demonstrate that the proposed method achieves a strong balance among real-time efficiency, localization accuracy, and rendering quality across diverse and challenging real-world scenes.
### Title:
          Sparse Contrastive Learning for Content-Based Cold Item Recommendation
 - **Authors:** Gregor Meehan, Johan Pauwels
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Item cold-start is a pervasive challenge for collaborative filtering (CF) recommender systems. Existing methods often train cold-start models by mapping auxiliary item content, such as images or text descriptions, into the embedding space of a CF model. However, such approaches can be limited by the fundamental information gap between CF signals and content features. In this work, we propose to avoid this limitation with purely content-based modeling of cold items, i.e. without alignment with CF user or item embeddings. We instead frame cold-start prediction in terms of item-item similarity, training a content encoder to project into a latent space where similarity correlates with user preferences. We define our training objective as a sparse generalization of sampled softmax loss with the $\alpha$-entmax family of activation functions, which allows for sharper estimation of item relevance by zeroing gradients for uninformative negatives. We then describe how this Sampled Entmax for Cold-start (SEMCo) training regime can be extended via knowledge distillation, and show that it outperforms existing cold-start methods and standard sampled softmax in ranking accuracy. We also discuss the advantages of purely content-based modeling, particularly in terms of equity of item outcomes.
### Title:
          Learning Versatile Humanoid Manipulation with Touch Dreaming
 - **Authors:** Yaru Niu, Zhenlong Fang, Binghong Chen, Shuai Zhou, Revanth Senthilkumaran, Hao Zhang, Bingqing Chen, Chen Qiu, H. Eric Tseng, Jonathan Francis, Ding Zhao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Humanoid robots promise general-purpose assistance, yet real-world humanoid loco-manipulation remains challenging because it requires whole-body stability, dexterous hands, and contact-aware perception under frequent contact changes. In this work, we study dexterous, contact-rich humanoid loco-manipulation. We first develop an RL-based whole-body controller that provides stable lower-body and torso execution during complex manipulation. Built on this controller, we develop a whole-body humanoid data collection system that combines VR-based teleoperation with human-to-humanoid motion mapping, enabling efficient collection of real-world demonstrations. We then propose Humanoid Transformer with Touch Dreaming (HTD), a multimodal encoder--decoder Transformer that models touch as a core modality alongside multi-view vision and proprioception. HTD is trained in a single stage with behavioral cloning augmented by touch dreaming: in addition to predicting action chunks, the policy predicts future hand-joint forces and future tactile latents, encouraging the shared Transformer trunk to learn contact-aware representations for dexterous interaction. Across five contact-rich tasks, Insert-T, Book Organization, Towel Folding, Cat Litter Scooping, and Tea Serving, HTD achieves a 90.9% relative improvement in average success rate over the stronger baseline. Ablation results further show that latent-space tactile prediction is more effective than raw tactile prediction, yielding a 30% relative gain in success rate. These results demonstrate that combining robust whole-body execution, scalable humanoid data collection, and predictive touch-centered learning enables versatile, high-dexterity humanoid manipulation in the real world. Project webpage: this http URL.
## Keyword: localization
### Title:
          BIND-USBL: Bounding IMU Navigation Drift using USBL in Heterogeneous ASV-AUV Teams
 - **Authors:** Pranav Kedia, Rajini Makam, Heiko Hamann, Suresh Sundaram
 - **Subjects:** Subjects:
Robotics (cs.RO); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate and continuous localization of Autonomous Underwater Vehicles (AUVs) in GPS-denied environments is a persistent challenge in marine robotics. In the absence of external position fixes, AUVs rely on inertial dead-reckoning, which accumulates unbounded drift due to sensor bias and noise. This paper presents BIND-USBL, a cooperative localization framework in which a fleet of Autonomous Surface Vessels (ASVs) equipped with Ultra-Short Baseline (USBL) acoustic positioning systems provides intermittent fixes to bound AUV dead-reckoning error. The key insight is that long-duration navigation failure is driven not by the accuracy of individual USBL measurements, but by the temporal sparsity and geometric availability of those fixes. BIND-USBL combines a multi-ASV formation model linking survey scale and anchor placement to acoustic coverage, a conflict-graph-based TDMA uplink scheduler for shared-channel servicing, and delayed fusion of received USBL updates with drift-prone dead reckoning. The framework is evaluated in the HoloOcean simulator using heterogeneous ASV-AUV teams executing lawnmower coverage missions. The results show that localization performance is shaped by the interaction of survey scale, acoustic coverage, team composition, and ASV-formation geometry. Further, the spatial-reuse scheduler improves per-AUV fix delivery rate without violating the no-collision constraint, while maintaining low end-to-end fix latency.
### Title:
          Self-Distillation Zero: Self-Revision Turns Binary Rewards into Dense Supervision
 - **Authors:** Yinghui He, Simran Kaur, Adithya Bhaskar, Yongjin Yang, Jiarui Liu, Narutatsu Ri, Liam Fowl, Abhishek Panigrahi, Danqi Chen, Sanjeev Arora
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current post-training methods in verifiable settings fall into two categories. Reinforcement learning (RLVR) relies on binary rewards, which are broadly applicable and powerful, but provide only sparse supervision during training. Distillation provides dense token-level supervision, typically obtained from an external teacher or using high-quality demonstrations. Collecting such supervision can be costly or unavailable. We propose Self-Distillation Zero (SD-Zero), a method that is substantially more training sample-efficient than RL and does not require an external teacher or high-quality demonstrations. SD-Zero trains a single model to play two roles: a Generator, which produces an initial response, and a Reviser, which conditions on that response and its binary reward to produce an improved response. We then perform on-policy self-distillation to distill the reviser into the generator, using the reviser's token distributions conditioned on the generator's response and its reward as supervision. In effect, SD-Zero trains the model to transform binary rewards into dense token-level self-supervision. On math and code reasoning benchmarks with Qwen3-4B-Instruct and Olmo-3-7B-Instruct, SD-Zero improves performance by at least 10% over the base models and outperforms strong baselines, including Rejection Fine-Tuning (RFT), GRPO, and Self-Distillation Fine-Tuning (SDFT), under the same question set and training sample budget. Extensive ablation studies show two novel characteristics of our proposed algorithm: (a) token-level self-localization, where the reviser can identify the key tokens that need to be revised in the generator's response based on reward, and (b) iterative self-evolution, where the improving ability to revise answers can be distilled back into generation performance with regular teacher synchronization.
### Title:
          Privacy-Preserving Structureless Visual Localization via Image Obfuscation
 - **Authors:** Vojtech Panek, Patrik Beliansky, Zuzana Kukelova, Torsten Sattler
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual localization is the task of estimating the camera pose of an image relative to a scene representation. In practice, visual localization systems are often cloud-based. Naturally, this raises privacy concerns in terms of revealing private details through the images sent to the server or through the representations stored on the server. Privacy-preserving localization aims to avoid such leakage of private details. However, the resulting localization approaches are significantly more complex, slower, and less accurate than their non-privacy-preserving counterparts. In this paper, we consider structureless localization methods in the context of privacy preservation. Structureless methods represent the scene through a set of reference images with known camera poses and intrinsics. In contrast to existing methods proposing representations that are as privacy-preserving as possible, we study a simple image obfuscation approach based on common image operations, e.g., replacing RGB images with (semantic) segmentations. We show that existing structureless pipelines do not need any special adjustments, as modern feature matchers can match obfuscated images out of the box. The results are easy-to-implement pipelines that can ensure both the privacy of the query images and the scene representations. Detailed experiments on multiple datasets show that the resulting methods achieve state-of-the-art pose accuracy for privacy-preserving approaches.
### Title:
          PC-MIL: Decoupling Feature Resolution from Supervision Scale in Whole-Slide Learning
 - **Authors:** Syed Fahim Ahmed, Gnanesh Rasineni, Florian Koehler, Abu Zahid Bin Aziz, Mei Wang, Attila Gyulassy, Brian Summa, J. Quincy Brown, Valerio Pascucci, Shireen Y. Elhabian
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Whole-slide image (WSI) classification in computational pathology is commonly formulated as slide-level Multiple Instance Learning (MIL) with a single global bag representation. However, slide-level MIL is fundamentally underconstrained: optimizing only global labels encourages models to aggregate features without learning anatomically meaningful localization. This creates a mismatch between the scale of supervision and the scale of clinical reasoning. Clinicians assess tumor burden, focal lesions, and architectural patterns within millimeter-scale regions, whereas standard MIL is trained only to predict whether "somewhere in the slide there is cancer." As a result, the model's inductive bias effectively erases anatomical structure. We propose Progressive-Context MIL (PC-MIL), a framework that treats the spatial extent of supervision as a first-class design dimension. Rather than altering magnification, patch size, or introducing pixel-level segmentation, we decouple feature resolution from supervision scale. Using fixed 20x features, we vary MIL bag extent in millimeter units and anchor supervision at a clinically motivated 2mm scale to preserve comparable tumor burden and avoid confounding scale with lesion density. PC-MIL progressively mixes slide- and region-level supervision in controlled proportions, enabling explicit train-context x test-context analysis. On 1,476 prostate WSIs from five public datasets for binary cancer detection, we show that anatomical context is an independent axis of generalization in MIL, orthogonal to feature resolution: modest regional supervision improves cross-context performance, and balanced multi-context training stabilizes accuracy across slide and regional evaluation without sacrificing global performance. These results demonstrate that supervision extent shapes MIL inductive bias and support anatomically grounded WSI generalization.
### Title:
          ViLL-E: Video LLM Embeddings for Retrieval
 - **Authors:** Rohit Gupta, Jayakrishnan Unnikrishnan, Fan Fei, Sheng Liu, Son Tran, Mubarak Shah
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video Large Language Models (VideoLLMs) excel at video understanding tasks where outputs are textual, such as Video Question Answering and Video Captioning. However, they underperform specialized embedding-based models in Retrieval tasks, such as Text-toVideo Retrieval and Moment Retrieval. We introduce ViLL-E (Video-LLM-Embed), a unified VideoLLM architecture endowed with a novel embedding generation mechanism that allows the model to "think longer" for complex videos and stop early for easy ones. We train this model with a three-stage training methodology combining generative and contrastive learning: initial large-scale pre-training with video-caption pairs; followed by continual training on a smaller, detailed-caption dataset; and concluding with task-specific fine-tuning on a novel multi-task dataset covering Video QA, Temporal Localization, Video Retrieval, and Video-Text Matching. Our model significantly improves temporal localization (on avg. 7% over other VideoLLMs) and video retrieval (up to 4% over dual encoder models), achieving performance comparable to state-of-the-art specialized embedding models while remaining competitive on VideoQA tasks. Furthermore, our joint contrastive-generative training unlocks new zero-shot capabilities, significantly outperforming state-of-the-art methods in composed video retrieval (+5% over SotA) and retrieval from long text (+2% over SotA).
### Title:
          VidTAG: Temporally Aligned Video to GPS Geolocalization with Denoising Sequence Prediction at a Global Scale
 - **Authors:** Parth Parag Kulkarni, Rohit Gupta, Prakash Chandra Chhipa, Mubarak Shah
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The task of video geolocalization aims to determine the precise GPS coordinates of a video's origin and map its trajectory; with applications in forensics, social media, and exploration. Existing classification-based approaches operate at a coarse city-level granularity and fail to capture fine-grained details, while image retrieval methods are impractical on a global scale due to the need for extensive image galleries which are infeasible to compile. Comparatively, constructing a gallery of GPS coordinates is straightforward and inexpensive. We propose VidTAG, a dual-encoder framework that performs frame-to-GPS retrieval using both self-supervised and language-aligned features. To address temporal inconsistencies in video predictions, we introduce the TempGeo module, which aligns frame embeddings, and the GeoRefiner module, an encoder-decoder architecture that refines GPS features using the aligned frame embeddings. Evaluations on Mapillary (MSLS) and GAMa datasets demonstrate our model's ability to generate temporally consistent trajectories and outperform baselines, achieving a 20% improvement at the 1 km threshold over GeoCLIP. We also beat current State-of-the-Art by 25% on global coarse grained video geolocalization (CityGuessr68k). Our approach enables fine-grained video geolocalization and lays a strong foundation for future research. More details on the project webpage: this https URL
### Title:
          Bridging the Micro--Macro Gap: Frequency-Aware Semantic Alignment for Image Manipulation Localization
 - **Authors:** Xiaojie Liang, Zhimin Chen, Ziqi Sheng, Wei Lu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As generative image editing advances, image manipulation localization (IML) must handle both traditional manipulations with conspicuous forensic artifacts and diffusion-generated edits that appear locally realistic. Existing methods typically rely on either low-level forensic cues or high-level semantics alone, leading to a fundamental micro--macro gap. To bridge this gap, we propose FASA, a unified framework for localizing both traditional and diffusion-generated manipulations. Specifically, we extract manipulation-sensitive frequency cues through an adaptive dual-band DCT module and learn manipulation-aware semantic priors via patch-level contrastive alignment on frozen CLIP representations. We then inject these priors into a hierarchical frequency pathway through a semantic-frequency side adapter for multi-scale feature interaction, and employ a prototype-guided, frequency-gated mask decoder to integrate semantic consistency with boundary-aware localization for tampered region prediction. Extensive experiments on OpenSDI and multiple traditional manipulation benchmarks demonstrate state-of-the-art localization performance, strong cross-generator and cross-dataset generalization, and robust performance under common image degradations.
### Title:
          Unlocking the Potential of Grounding DINO in Videos: Parameter-Efficient Adaptation for Limited-Data Spatial-Temporal Localization
 - **Authors:** Zanyi Wang, Fan Li, Dengyang Jiang, Liuzhuozheng Li, Yunhua Zhong, Guang Dai, Mengmeng Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spatio-temporal video grounding (STVG) aims to localize queried objects within dynamic video segments. Prevailing fully-trained approaches are notoriously data-hungry. However, gathering large-scale STVG data is exceptionally challenging: dense frame-level bounding boxes and complex temporal language alignments are prohibitively expensive to annotate, especially for specialized video domains. Consequently, conventional models suffer from severe overfitting on these inherently limited datasets, while zero-shot foundational models lack the task-specific temporal awareness needed for precise localization. To resolve this small-data challenge, we introduce ST-GD, a data-efficient framework that adapts pre-trained 2D visual-language models (e.g., Grounding DINO) to video tasks. To avoid destroying pre-trained priors on small datasets, ST-GD keeps the base model frozen and strategically injects lightweight adapters (~10M trainable parameters) to instill spatio-temporal awareness, alongside a novel temporal decoder for boundary prediction. This design naturally counters data scarcity. Consequently, ST-GD excels in data-scarce scenarios, achieving highly competitive performance on the limited-scale HC-STVG v1/v2 benchmarks, while maintaining robust generalization on the VidSTG dataset. This validates ST-GD as a powerful paradigm for complex video understanding under strict small-data constraints.
### Title:
          Fundus Image-based Glaucoma Screening via Retinal Knowledge-Oriented Dynamic Multi-Level Feature Integration
 - **Authors:** Yuzhuo Zhou, Chi Liu, Sheng Shen, Zongyuan Ge, Fengshi Jing, Shiran Zhang, Yu Jiang, Anli Wang, Wenjian Liu, Feilong Yang, Tianqing Zhu, Xiaotong Han
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated diagnosis based on color fundus photography is essential for large-scale glaucoma screening. However, existing deep learning models are typically data-driven and lack explicit integration of retinal anatomical knowledge, which limits their robustness across heterogeneous clinical datasets. Moreover, pathological cues in fundus images may appear beyond predefined anatomical regions, making fixed-region feature extraction insufficient for reliable diagnosis. To address these challenges, we propose a retinal knowledge-oriented glaucoma screening framework that integrates dynamic multi-scale feature learning with domain-specific retinal priors. The framework adopts a tri-branch structure to capture complementary retinal representations, including global retinal context, structural features of the optic disc/cup, and dynamically localized pathological regions. A Dynamic Window Mechanism is devised to adaptively identify diagnostically informative regions, while a Knowledge-Enhanced Convolutional Attention Module incorporates retinal priors extracted from a pre-trained foundation model to guide attention learning. Extensive experiments on the large-scale AIROGS dataset demonstrate that the proposed method outperforms diverse baselines, achieving an AUC of 98.5% and an accuracy of 94.6%. Additional evaluations on multiple datasets from the SMDG-19 benchmark further confirm its strong cross-domain generalization capability, indicating that knowledge-guided attention combined with adaptive lesion localization can significantly improve the robustness of automated glaucoma screening systems.
### Title:
          DiffusionPrint: Learning Generative Fingerprints for Diffusion-Based Inpainting Localization
 - **Authors:** Paschalis Giakoumoglou, Symeon Papadopoulos
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern diffusion-based inpainting models pose significant challenges for image forgery localization (IFL), as their full regeneration pipelines reconstruct the entire image via a latent decoder, disrupting the camera-level noise patterns that existing forensic methods rely on. We propose DiffusionPrint, a patch-level contrastive learning framework that learns a forensic signal robust to the spectral distortions introduced by latent decoding. It exploits the fact that inpainted regions generated by the same model share a consistent generative fingerprint, using this as a self-supervisory signal. DiffusionPrint trains a convolutional backbone via a MoCo-style objective with cross-category hard negative mining and a generator-aware classification head, producing a forensic feature map that serves as a highly discriminative secondary modality in fusion-based IFL frameworks. Integrated into TruFor, MMFusion, and a lightweight fusion baseline, DiffusionPrint consistently improves localization across multiple generative models, with gains of up to +28% on mask types unseen during fine-tuning and confirmed generalization to unseen generative architectures. Code is available at this https URL
### Title:
          NaviRAG: Towards Active Knowledge Navigation for Retrieval-Augmented Generation
 - **Authors:** Jihao Dai (1 and 2), Dingjun Wu (1), Yuxuan Chen (1), Zheni Zeng (2), Yukun Yan (1), Zhenghao Liu (3), Maosong Sun (1) ((1) Tsinghua University, (2) Nanjing University, (3) Northeastern University)
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Retrieval-augmented generation (RAG) typically relies on a flat retrieval paradigm that maps queries directly to static, isolated text segments. This approach struggles with more complex tasks that require the conditional retrieval and dynamic synthesis of information across different levels of granularity (e.g., from broad concepts to specific evidence). To bridge this gap, we introduce NaviRAG, a novel framework that shifts from passive segment retrieval to active knowledge navigation. NaviRAG first structures the knowledge documents into a hierarchical form, preserving semantic relationships from coarse-grained topics to fine-grained details. Leveraging this reorganized knowledge records, a large language model (LLM) agent actively navigates the records, iteratively identifying information gaps and retrieving relevant content from the most appropriate granularity level. Extensive experiments on long-document QA benchmarks show that NaviRAG consistently improves both retrieval recall and end-to-end answer performance over conventional RAG baselines. Ablation studies confirm performance gains stem from our method's capacity for multi-granular evidence localization and dynamic retrieval planning. We further discuss efficiency, applicable scenario, and future directions of our method, hoping to make RAG systems more intelligent and autonomous.
### Title:
          DocSeeker: Structured Visual Reasoning with Evidence Grounding for Long Document Understanding
 - **Authors:** Hao Yan, Yuliang Liu, Xingchen Liu, Yuyi Zhang, Minghui Liao, Jihao Wu, Wei Chen, Xiang Bai
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing Multimodal Large Language Models (MLLMs) suffer from significant performance degradation on the long document understanding task as document length increases. This stems from two fundamental challenges: 1) a low Signal-to-Noise Ratio (SNR), with crucial evidence buried in irrelevant pages; and 2) supervision scarcity, as datasets offering only final short answers provide a weak learning signal. In this paper, we address these challenges by proposing a paradigm that requires the model to execute a structured ``\textbf{Analysis}, \textbf{Localization} and \textbf{Reasoning}'' workflow. To instill this capability, we design a two-stage training framework: we first perform Supervised Fine-Tuning on high-quality data generated via an efficient knowledge distillation strategy. Subsequently, we employ an Evidence-aware Group Relative Policy Optimization which jointly optimizes for both evidence localization and answer accuracy. Additionally, we introduce a Evidence-Guided Resolution Allocation strategy to mitigate memory constraints of training on multi-pages documents. Extensive experiments demonstrate that DocSeeker achieves superior performance on both in-domain and out-of-domain tasks. We show it robustly generalizes from short-page training to ultra-long documents and is naturally synergistic with visual Retrieval-Augmented Generation systems, serving as a solid foundation for their implementation.
### Title:
          GGD-SLAM: Monocular 3DGS SLAM Powered by Generalizable Motion Model for Dynamic Environments
 - **Authors:** Yi Liu, Haoxuan Xu, Hongbo Duan, Keyu Fan, Zhengyang Zhang, Peiyu Zhuang, Pengting Luo, Houde Liu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual SLAM algorithms achieve significant improvements through the exploration of 3D Gaussian Splatting (3DGS) representations, particularly in generating high-fidelity dense maps. However, they depend on a static environment assumption and experience significant performance degradation in dynamic environments. This paper presents GGD-SLAM, a framework that employs a generalizable motion model to address the challenges of localization and dense mapping in dynamic environments - without predefined semantic annotations or depth input. Specifically, the proposed system employs a First-In-First-Out (FIFO) queue to manage incoming frames, facilitating dynamic semantic feature extraction through a sequential attention mechanism. This is integrated with a dynamic feature enhancer to separate static and dynamic components. Additionally, to minimize dynamic distractors' impact on the static components, we devise a method to fill occluded areas via static information sampling and design a distractor-adaptive Structure Similarity Index Measure (SSIM) loss tailored for dynamic environments, significantly enhancing the system's resilience. Experiments conducted on real-world dynamic datasets demonstrate that the proposed system achieves state-of-the-art performance in camera pose estimation and dense reconstruction in dynamic scenes.
### Title:
          Pi-HOC: Pairwise 3D Human-Object Contact Estimation
 - **Authors:** Sravan Chittupalli, Ayush Jain, Dong Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Resolving real-world human-object interactions in images is a many-to-many challenge, in which disentangling fine-grained concurrent physical contact is particularly difficult. Existing semantic contact estimation methods are either limited to single-human settings or require object geometries (e.g., meshes) in addition to the input image. Current state-of-the-art leverages powerful VLM for category-level semantics but struggles with multi-human scenarios and scales poorly in inference. We introduce Pi-HOC, a single-pass, instance-aware framework for dense 3D semantic contact prediction of all human-object pairs. Pi-HOC detects instances, creates dedicated human-object (HO) tokens for each pair, and refines them using an InteractionFormer. A SAM-based decoder then predicts dense contact on SMPL human meshes for each human-object pair. On the MMHOI and DAMON datasets, Pi-HOC significantly improves accuracy and localization over state-of-the-art methods while achieving 20x higher throughput. We further demonstrate that predicted contacts improve SAM-3D image-to-mesh reconstruction via a test-time optimization algorithm and enable referential contact prediction from language queries without additional training.
### Title:
          RMGS-SLAM: Real-time Multi-sensor Gaussian Splatting SLAM
 - **Authors:** Dongen Li, Yi Liu, Junqi Liu, Zewen Sun, Zefan Huang, Shuo Sun, Jiahui Liu, Chengran Yuan, Hongliang Guo, Francis E.H. Tay, Marcelo H. Ang Jr
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-time 3D Gaussian splatting (3DGS)-based Simultaneous Localization and Mapping (SLAM) in large-scale real-world environments remains challenging, as existing methods often struggle to jointly achieve low-latency pose estimation, 3D Gaussian reconstruction in step with incoming sensor streams, and long-term global consistency. In this paper, we present a tightly coupled LiDAR-Inertial-Visual (LIV) 3DGS-based SLAM framework for real-time pose estimation and photorealistic mapping in large-scale real-world scenes. The system executes state estimation and 3D Gaussian primitive initialization in parallel with global Gaussian optimization, thereby enabling continuous dense mapping. To improve Gaussian initialization quality and accelerate optimization convergence, we introduce a cascaded strategy that combines feed-forward predictions with voxel-based principal component analysis (voxel-PCA) geometric priors. To enhance global consistency in large scenes, we further perform loop closure directly on the optimized global Gaussian map by estimating loop constraints through Gaussian-based Generalized Iterative Closest Point (GICP) registration, followed by pose-graph optimization. In addition, we collected challenging large-scale looped outdoor SLAM sequences with hardware-synchronized LiDAR-camera-IMU and ground-truth trajectories to support realistic and comprehensive evaluation. Extensive experiments on both public datasets and our dataset demonstrate that the proposed method achieves a strong balance among real-time efficiency, localization accuracy, and rendering quality across diverse and challenging real-world scenes.
### Title:
          LogicEval: A Systematic Framework for Evaluating Automated Repair Techniques for Logical Vulnerabilities in Real-World Software
 - **Authors:** Syed Md Mukit Rashid, Abdullah Al Ishtiaq, Kai Tu, Yilu Dong, Tianwei Wu, Ali Ranjbar, Tianchang Yang, Najrin Sultana, Shagufta Mehnaz, Syed Rafiul Hussain
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Logical vulnerabilities in software stem from flaws in program logic rather than memory safety, which can lead to critical security failures. Although existing automated program repair techniques primarily focus on repairing memory corruption vulnerabilities, they struggle with logical vulnerabilities because of their limited semantic understanding of the vulnerable code and its expected behavior. On the other hand, recent successes of large language models (LLMs) in understanding and repairing code are promising. However, no framework currently exists to analyze the capabilities and limitations of such techniques for logical vulnerabilities. This paper aims to systematically evaluate both traditional and LLM-based repair approaches for addressing real-world logical vulnerabilities. To facilitate our assessment, we created the first ever dataset, LogicDS, of 86 logical vulnerabilities with assigned CVEs reflecting tangible security impact. We also developed a systematic framework, LogicEval, to evaluate patches for logical vulnerabilities. Evaluations suggest that compilation and testing failures are primarily driven by prompt sensitivity, loss of code context, and difficulty in patch localization.
### Title:
          See, Point, Refine: Multi-Turn Approach to GUI Grounding with Visual Feedback
 - **Authors:** Himangi Mittal, Gaurav Mittal, Nelson Daniel Troncoso, Yu Hu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Computer Use Agents (CUAs) fundamentally rely on graphical user interface (GUI) grounding to translate language instructions into executable screen actions, but editing-level grounding in dense coding interfaces, where sub-pixel accuracy is required to interact with dense IDE elements, remains underexplored. Existing approaches typically rely on single-shot coordinate prediction, which lacks a mechanism for error correction and often fails in high-density interfaces. In this technical report, we conduct an empirical study of pixel-precise cursor localization in coding environments. Instead of a single-step execution, our agent engages in an iterative refinement process, utilizing visual feedback from previous attempts to reach the target element. This closed-loop grounding mechanism allows the agent to self-correct displacement errors and adapt to dynamic UI changes. We evaluate our approach across GPT-5.4, Claude, and Qwen on a suite of complex coding benchmarks, demonstrating that multi-turn refinement significantly outperforms state-of-the-art single-shot models in both click precision and overall task success rate. Our results suggest that iterative visual reasoning is a critical component for the next generation of reliable software engineering agents. Code: this https URL.
## Keyword: transformer
### Title:
          GRACE: A Dynamic Coreset Selection Framework for Large Language Model Optimization
 - **Authors:** Tianhao Tang, Haoyang Li, Lei Chen
 - **Subjects:** Subjects:
Databases (cs.DB); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) have demonstrated remarkable capabilities in natural language understanding and generation. However, their immense number of parameters and complex transformer-based architectures result in significant resource demands and computational complexity during training, making it challenging to optimize them efficiently on large datasets. To reduce training costs while preserving performance, researchers have investigated coreset selection techniques, which aim to identify small, representative subsets of the entire training dataset to accelerate LLM training. However, existing coreset selection methods fail to adapt to the dynamic nature of LLM training and often struggle with scalability for models of this size. To address these limitations, we propose a graph-guided adaptive and dynamic coreset selection framework for LLMs, namely GRACE. GRACE dynamically constructs and updates coresets by combining representation diversity with gradient-based importance metrics, ensuring both informativeness and efficiency. To mitigate the computational cost of frequent updates, GRACE leverages a $k$-NN graph-based propagation mechanism and selectively updates scores and embeddings, adapting to evolving training dynamics. Extensive experiments on three benchmarks demonstrate that GRACE significantly improves training efficiency and downstream performance across diverse LLMs and tasks.
### Title:
          Subcritical Signal Propagation at Initialization in Normalization-Free Transformers
 - **Authors:** Sergey Alekseev
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study signal propagation at initialization in transformers through the averaged partial Jacobian norm (APJN), a measure of gradient amplification across layers. We extend APJN analysis to transformers with bidirectional attention and permutation-symmetric input token configurations by deriving recurrence relations for activation statistics and APJNs across layers. Our theory predicts how attention modifies the asymptotic behavior of the APJN at large depth and matches APJNs measured in deep vision transformers. The criticality picture known from residual networks carries over to transformers: the pre-LayerNorm architecture exhibits power-law APJN growth, whereas transformers with LayerNorm replaced by elementwise $\tanh$-like nonlinearities have stretched-exponential APJN growth, indicating that the latter are subcritical. Applied to Dynamic Tanh (DyT) and Dynamic erf (Derf) transformers, the theory explains why these architectures can be more sensitive to initialization and optimization choices and require careful tuning for stable training.
### Title:
          How Transformers Learn to Plan via Multi-Token Prediction
 - **Authors:** Jianhao Huang, Zhanpeng Zhou, Renqiu Xia, Baharan Mirzasoleiman, Weijie Su, Wei Huang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While next-token prediction (NTP) has been the standard objective for training language models, it often struggles to capture global structure in reasoning tasks. Multi-token prediction (MTP) has recently emerged as a promising alternative, yet its underlying mechanisms remain poorly understood. In this paper, we study how MTP facilitates reasoning, with a focus on planning. Empirically, we show that MTP consistently outperforms NTP on both synthetic graph path-finding tasks and more realistic reasoning benchmarks, such as Countdown and boolean satisfiability problems. Theoretically, we analyze a simplified two-layer Transformer on a star graph task. We prove that MTP induces a two-stage reverse reasoning process: the model first attends to the end node and then reconstructs the path by tracing intermediate nodes backward. This behavior arises from a gradient decoupling property of MTP, which provides a cleaner training signal compared to NTP. Ultimately, our results highlight how multi-token objectives inherently bias optimization toward robust and interpretable reasoning circuits.
### Title:
          ResBM: Residual Bottleneck Models for Low-Bandwidth Pipeline Parallelism
 - **Authors:** Alan Aboudib, Rodrigo Lopez Portillo A., Kalei Brady, Steffen Cruz
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unlocking large-scale low-bandwidth decentralized training has the potential to utilize otherwise untapped compute resources. In centralized settings, large-scale multi-node training is primarily enabled by data and pipeline parallelism, two techniques that require ultra-high-bandwidth communication. While efficient methods now exist for decentralized data parallelism, pipeline parallelism remains the primary challenge. Recent efforts, such as Subspace Models (SM), have claimed up to 100x activation compression but rely on complex constrained optimization and diverge from true end-to-end training. In this paper, we propose a different approach, based on an architecture designed from the ground up to be native to low-bandwidth communication environments while still applicable to any standard transformer-based architecture. We call this architecture the Residual Bottleneck Model or ResBM, it introduces a residual encoder-decoder bottleneck module across pipeline boundaries that can be trained end-to-end as part of the model's parameters while preserving an explicit low-rank identity path. We show that ResBMs achieve state-of-the-art 128x activation compression without significant loss in convergence rates and without significant memory or compute overhead.
### Title:
          The Linear Centroids Hypothesis: How Deep Network Features Represent Data
 - **Authors:** Thomas Walker, Ahmed Imtiaz Humayun, Randall Balestriero, Richard Baraniuk
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Identifying and understanding the features that a deep network (DN) extracts from its inputs to produce its outputs is a focal point of interpretability research. The Linear Representation Hypothesis (LRH) identifies features in terms of the linear directions formed by the inputs in a DN's latent space. However, the LRH is limited as it abstracts away from individual components (e.g., neurons and layers), is susceptible to identifying spurious features, and cannot be applied across sub-components (e.g., multiple layers). In this paper, we introduce the Linear Centroids Hypothesis (LCH) as a new framework for identifying the features of a DN. The LCH posits that features correspond to linear directions of centroids, which are vector summarizations of the functional behavior of a DN in a local region of its input space. Interpretability studies under the LCH can leverage existing LRH tools, such as sparse autoencoders, by applying them to the DN's centroids rather than to its latent activations. We demonstrate that doing so yields sparser feature dictionaries for DINO vision transformers, which also perform better on downstream tasks. The LCH also inspires novel approaches to interpretability; for example, LCH can readily identify circuits in GPT2-Large. For code to study the LCH this https URL .
### Title:
          A Geometric Algebra-informed NeRF Framework for Generalizable Wireless Channel Prediction
 - **Authors:** Jingzhou Shen, Luis Lago Enamorado, Shiwen Mao, Xuyu Wang
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we propose the geometric algebra-informed neural radiance fields (GAI-NeRF), a novel framework for wireless channel prediction that leverages geometric algebra attention mechanisms to capture ray-object interactions in complex propagation environments. Our approach incorporates global token representations, drawing inspiration from transformer architectures in language and vision domains, to aggregate learned spatial-electromagnetic features and enhance scene understanding. We identify limitations in conventional static ray tracing modules that hinder model generalization and address this challenge through a new ray tracing architecture. This design enables effective generalization across diverse wireless scenarios while maintaining computational efficiency. Experimental results demonstrate that GAI-NeRF achieves superior performance in channel prediction tasks by combining geometric algebra principles with neural scene representations, offering a promising direction for next-generation wireless communication systems. Moreover, GAI-NeRF greatly outperforms existing methods across multiple wireless scenarios. To ensure comprehensive assessment, we further evaluate our approach against multiple benchmarks using newly collected real-world indoor datasets tailored for single-scene downstream tasks and generalization testing, confirming its robust performance in unseen environments and establishing its high efficacy for wireless channel prediction.
### Title:
          Ultra-low-light computer vision using trained photon correlations
 - **Authors:** Mandar M. Sohoni, Jérémie Laydevant, Mathieu Ouellet, Shi-Yuan Ma, Ryotatsu Yanagimoto, Benjamin A. Ash, Tatsuhiro Onodera, Tianyu Wang, Logan G. Wright, Peter L. McMahon
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Optics (physics.optics)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Illumination using correlated photon sources has been established as an approach to allowing high-fidelity images to be reconstructed from noisy camera frames by taking advantage of the knowledge that signal photons are spatially correlated whereas detector clicks due to noise are uncorrelated. However, in computer-vision tasks, the goal is often not ultimately to reconstruct an image, but to make inferences about a scene -- such as what object is present. Here we show how correlated-photon illumination can be used to gain an advantage in a hybrid optical-electronic computer-vision pipeline for object recognition. We demonstrate correlation-aware training (CAT): end-to-end optimization of a trainable correlated-photon illumination source and a Transformer backend in a way that the Transformer can learn to benefit from the correlations, using a small number (<= 100) of shots. We show a classification accuracy enhancement of up to 15 percentage points over conventional, uncorrelated-illumination-based computer vision in ultra-low-light and noisy imaging conditions, as well as an improvement over using untrained correlated-photon illumination. Our work illustrates how specializing to a computer-vision task -- object recognition -- and training the pattern of photon correlations in conjunction with a digital backend allows us to push the limits of accuracy in highly photon-budget-constrained scenarios beyond existing methods focused on image reconstruction.
### Title:
          When Self-Reference Fails to Close: Matrix-Level Dynamics in Large Language Models
 - **Authors:** Ji Ho Bae
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We investigate how self-referential inputs alter the internal matrix dynamics of large language models. Measuring 106 scalar metrics across up to 7 analysis passes on four models from three architecture families -- Qwen3-VL-8B, Llama-3.2-11B, Llama-3.3-70B, and Gemma-2-9B -- over 300 prompts in a 14-level hierarchy at three temperatures ($T \in \{0.0, 0.3, 0.7\}$), we find that self-reference alone is not destabilizing: grounded self-referential statements and meta-cognitive prompts are markedly more stable than paradoxical self-reference on key collapse-related metrics, and on several such metrics can be as stable as factual controls. Instability concentrates in prompts inducing non-closing truth recursion (NCTR) -- truth-value computations with no finite-depth resolution. NCTR prompts produce anomalously elevated attention effective rank -- indicating attention reorganization with global dispersion rather than simple concentration collapse -- and key metrics reach Cohen's $d = 3.14$ (attention effective rank) to $3.52$ (variance kurtosis) vs. stable self-reference in the 70B model; 281/397 metric-model combinations differentiate NCTR from stable self-reference after FDR correction ($q < 0.05$), 198 with $|d| > 0.8$. Per-layer SVD confirms disruption at every sampled layer ($d > +1.0$ in all three models analyzed), ruling out aggregation artifacts. A classifier achieves AUC $0.81$-$0.90$; 30 minimal pairs yield 42/387 significant combinations; 43/106 metrics replicate across all four models. We connect these observations to three classical matrix-semigroup problems and propose, as a conjecture, that NCTR forces finite-depth transformers toward dynamical regimes where these problems concentrate. NCTR prompts also produce elevated contradictory output ($+34$-$56$ percentage points vs. controls), suggesting practical relevance for understanding self-referential failure modes.
### Title:
          Distinct mechanisms underlying in-context learning in transformers
 - **Authors:** Cole Gibson, Wenping Cui, Gautam Reddy
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Disordered Systems and Neural Networks (cond-mat.dis-nn); Statistical Mechanics (cond-mat.stat-mech)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern distributed networks, notably transformers, acquire a remarkable ability (termed `in-context learning') to adapt their computation to input statistics, such that a fixed network can be applied to data from a broad range of systems. Here, we provide a complete mechanistic characterization of this behavior in transformers trained on a finite set $S$ of discrete Markov chains. The transformer displays four algorithmic phases, characterized by whether the network memorizes and generalizes, and whether it uses 1-point or 2-point statistics. We show that the four phases are implemented by multi-layer subcircuits that exemplify two qualitatively distinct mechanisms for implementing context-adaptive computations. Minimal models isolate the key features of both motifs. Memorization and generalization phases are delineated by two boundaries that depend on data diversity, $K = |S|$. The first ($K_1^\ast$) is set by a kinetic competition between subcircuits and the second ($K_2^\ast$) is set by a representational bottleneck. A symmetry-constrained theory of a transformer's training dynamics explains the sharp transition from 1-point to 2-point generalization and identifies key features of the loss landscape that allow the network to generalize. Put together, we show that transformers develop distinct subcircuits to implement in-context learning and identify conditions that favor certain mechanisms over others.
### Title:
          Nucleus-Image: Sparse MoE for Image Generation
 - **Authors:** Chandan Akiti, Ajay Modukuri, Murali Nandan Nagarapu, Gunavardhan Akiti, Haozhe Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Nucleus-Image, a text-to-image generation model that establishes a new Pareto frontier in quality-versus-efficiency by matching or exceeding leading models on GenEval, DPG-Bench, and OneIG-Bench while activating only approximately 2B parameters per forward pass. Nucleus-Image employs a sparse mixture-of-experts (MoE) diffusion transformer architecture with Expert-Choice Routing that scales total model capacity to 17B parameters across 64 routed experts per layer. We adopt a streamlined architecture optimized for inference efficiency by excluding text tokens from the transformer backbone entirely and using joint attention that enables text KV sharing across timesteps. To improve routing stability when using timestep modulation, we introduce a decoupled routing design that separates timestep-aware expert assignment from timestep-conditioned expert computation. We construct a large-scale training corpus of 1.5B high-quality training pairs spanning 700M unique images through multi-stage filtering, deduplication, aesthetic tiering, and caption curation. Training follows a progressive resolution curriculum (256 to 512 to 1024) with multi-aspect-ratio bucketing at every stage, coupled with progressive sparsification of the expert capacity factor. We adopt the Muon optimizer and share our parameter grouping recipe tailored for diffusion models with timestep modulation. Nucleus-Image demonstrates that sparse MoE scaling is a highly effective path to high-quality image generation, reaching the performance of models with significantly larger active parameter budgets at a fraction of the inference cost. These results are achieved without post-training optimization of any kind: no reinforcement learning, no direct preference optimization, and no human preference tuning. We release the training recipe, making Nucleus-Image the first fully open-source MoE diffusion model at this quality.
### Title:
          Fully Homomorphic Encryption on Llama 3 model for privacy preserving LLM inference
 - **Authors:** Anes Abdennebi, Nadjia Kara, Laaziz Lahlou
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The applications of Generative Artificial Intelligence (GenAI) and their intersections with data-driven fields, such as healthcare, finance, transportation, and information security, have led to significant improvements in service efficiency and low latency. However, this synergy raises serious concerns regarding the security of large language models (LLMs) and their potential impact on the privacy of companies and users' data. Many technology companies that incorporate LLMs in their services with a certain level of command and control bear a risk of data exposure and secret divulgence caused by insecure LLM pipelines, making them vulnerable to multiple attacks such as data poisoning, prompt injection, and model theft. Although several security techniques (input/output sanitization, decentralized learning, access control management, and encryption) were implemented to reduce this risk, there is still an imminent risk of quantum computing attacks, which are expected to break existing encryption algorithms, hence, retrieving secret keys, encrypted sensitive data, and decrypting encrypted models. In this extensive work, we integrate the Post-Quantum Cryptography (PQC) based Lattice-based Homomorphic Encryption (HE) main functions in the LLM's inference pipeline to secure some of its layers against data privacy attacks. We modify the inference pipeline of the transformer architecture for the LLAMA-3 model while injecting the main homomorphic encryption operations provided by the concrete-ml library. We demonstrate high text generation accuracies (up to 98%) with reasonable latencies (237 ms) on an i9 CPU, reaching up to 80 tokens per second, which proves the feasibility and validity of our work while running a FHE-secured LLAMA-3 inference model. Further experiments and analysis are discussed to justify models' text generation latencies and behaviours.
### Title:
          Representing expertise accelerates learning from pedagogical interaction data
 - **Authors:** Dhara Yu, Karthikeya Kaushik, Bill D. Thompson
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Work in cognitive science and artificial intelligence has suggested that exposing learning agents to traces of interaction between multiple individuals can improve performance in a variety of settings, yet it remains unknown which features of interactions contribute to this improvement. We examined the factors that support the effectiveness of interaction data, using a controlled paradigm that allowed us to precisely operationalize key distinctions between interaction and an expert acting alone. We generated synthetic datasets of simple interactions between an expert and a novice in a spatial navigation task, and then trained transformer models on those datasets, evaluating performance after exposure to different datasets. Our experiments showed that models trained on pedagogical interactions were more robust across a variety of scenarios compared to models trained only on expert demonstrations, and that having the ability to represent epistemically distinct agents led to expert-like behavior even when expert behavior was rarely observed.
### Title:
          VVGT: Visual Volume-Grounded Transformer
 - **Authors:** Yuxuan Wang, Qibiao Li, Youcheng Cai
 - **Subjects:** Subjects:
Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Volumetric visualization has long been dominated by Direct Volume Rendering (DVR), which operates on dense voxel grids and suffers from limited scalability as resolution and interactivity demands increase. Recent advances in 3D Gaussian Splatting (3DGS) offer a representation-centric alternative; however, existing volumetric extensions still depend on costly per-scene optimization, limiting scalability and interactivity. We present VVGT (Visual Volume-Grounded Transformer), a feed-forward, representation-first framework that directly maps volumetric data to a 3D Gaussian Splatting representation, advancing a new paradigm for volumetric visualization beyond DVR. Unlike prior feed-forward 3DGS methods designed for surface-centric reconstruction, VVGT explicitly accounts for volumetric rendering, where each pixel aggregates contributions along a ray. VVGT employs a dual-transformer network and introduces Volume Geometry Forcing, an epipolar cross-attention mechanism that integrates multi-view observations into distributed 3D Gaussian primitives without surface assumptions. This design eliminates per-scene optimization while enabling accurate volumetric representations. Extensive experiments show that VVGT achieves high-quality visualization with orders-of-magnitude faster conversion, improved geometric consistency, and strong zero-shot generalization across diverse datasets, enabling truly interactive and scalable volumetric visualization. The code will be publicly released upon acceptance.
### Title:
          LLM-Enhanced Log Anomaly Detection: A Comprehensive Benchmark of Large Language Models for Automated System Diagnostics
 - **Authors:** Disha Patel
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 System log anomaly detection is critical for maintaining the reliability of large-scale software systems, yet traditional methods struggle with the heterogeneous and evolving nature of modern log data. Recent advances in Large Language Models (LLMs) offer promising new approaches to log understanding, but a systematic comparison of LLM-based methods against established techniques remains lacking. In this paper, we present a comprehensive benchmark study evaluating both LLM-based and traditional approaches for log anomaly detection across four widely-used public datasets: HDFS, BGL, Thunderbird, and Spirit. We evaluate three categories of methods: (1) classical log parsers (Drain, Spell, AEL) combined with machine learning classifiers, (2) fine-tuned transformer models (BERT, RoBERTa), and (3) prompt-based LLM approaches (GPT-3.5, GPT-4, LLaMA-3) in zero-shot and few-shot settings. Our experiments reveal that while fine-tuned transformers achieve the highest F1-scores (0.96-0.99), prompt-based LLMs demonstrate remarkablezero-shot capabilities (F1: 0.82-0.91) without requiring any labeled training data -- a significant advantage for real-world deployment where labeled anomalies are scarce. We further analyze the cost-accuracy trade-offs, latency characteristics, and failure modes of each approach. Our findings provide actionable guidelines for practitioners choosing log anomaly detection methods based on their specific constraints regarding accuracy, latency, cost, and label availability. All code and experimental configurations are publicly available to facilitate reproducibility.
### Title:
          Ride the Wave: Precision-Allocated Sparse Attention for Smooth Video Generation
 - **Authors:** Wentai Zhang, Ronghui Xi, Shiyao Peng, Jiayu Huang, Haoran Luo, Zichen Tang, Haihong E
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video Diffusion Transformers have revolutionized high-fidelity video generation but suffer from the massive computational burden of self-attention. While sparse attention provides a promising acceleration solution, existing methods frequently provoke severe visual flickering caused by static sparsity patterns and deterministic block routing. To resolve these limitations, we propose Precision-Allocated Sparse Attention (PASA), a training-free framework designed for highly efficient and temporally smooth video generation. First, we implement a curvature-aware dynamic budgeting mechanism. By profiling the generation trajectory acceleration across timesteps, we elastically allocate the exact-computation budget to secure high-precision processing strictly during critical semantic transitions. Second, we replace global homogenizing estimations with hardware-aligned grouped approximations, successfully capturing fine-grained local variations while maintaining peak compute throughput. Finally, we incorporate a stochastic selection bias into the attention routing mechanism. This probabilistic approach softens rigid selection boundaries and eliminates selection oscillation, effectively eradicating the localized computational starvation that drives temporal flickering. Extensive evaluations on leading video diffusion models demonstrate that PASA achieves substantial inference acceleration while consistently producing remarkably fluid and structurally stable video sequences.
### Title:
          CoSyncDiT: Cognitive Synchronous Diffusion Transformer for Movie Dubbing
 - **Authors:** Gaoxiang Cong, Liang Li, Jiaxin Ye, Zhedong Zhang, Hongming Shan, Yuankai Qi, Qingming Huang
 - **Subjects:** Subjects:
Sound (cs.SD); Computer Vision and Pattern Recognition (cs.CV); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Movie dubbing aims to synthesize speech that preserves the vocal identity of a reference audio while synchronizing with the lip movements in a target video. Existing methods fail to achieve precise lip-sync and lack naturalness due to explicit alignment at the duration level. While implicit alignment solutions have emerged, they remain susceptible to interference from the reference audio, triggering timbre and pronunciation degradation in in-the-wild scenarios. In this paper, we propose a novel flow matching-based movie dubbing framework driven by the Cognitive Synchronous Diffusion Transformer (CoSync-DiT), inspired by the cognitive process of professional actors. This architecture progressively guides the noise-to-speech generative trajectory by executing acoustic style adapting, fine-grained visual calibrating, and time-aware context aligning. Furthermore, we design the Joint Semantic and Alignment Regularization (JSAR) mechanism to simultaneously constrain frame-level temporal consistency on the contextual outputs and semantic consistency on the flow hidden states, ensuring robust alignment. Extensive experiments on both standard benchmarks and challenging in-the-wild dubbing benchmarks demonstrate that our method achieves the state-of-the-art performance across multiple metrics.
### Title:
          Identifying and Mitigating Gender Cues in Academic Recommendation Letters: An Interpretability Case Study
 - **Authors:** Charlotte S. Alexander, Shane Storks, Souradip Pal, Sayak Chakrabarty, Arushi Sharma, Mlen-Too Wesley, Bailey Russo
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Letters of recommendation (LoRs) can carry patterns of implicitly gendered language that can inadvertently influence downstream decisions, e.g. in hiring and admissions. In this work, we investigate the extent to which Transformer-based encoder models as well as Large Language Models (LLMs) can infer the gender of applicants in academic LoRs submitted to an U.S. medical-residency program after explicit identifiers like names and pronouns are de-gendered. While using three models (DistilBERT, RoBERTa, and Llama 2) to classify the gender of anonymized and de-gendered LoRs, significant gender leakage was observed as evident from up to 68% classification accuracy. Text interpretation methods, like TF-IDF and SHAP, demonstrate that certain linguistic patterns are strong proxies for gender, e.g. "emotional'' and "humanitarian'' are commonly associated with LoRs from female applicants. As an experiment in creating truly gender-neutral LoRs, these implicit gender cues were remove resulting in a drop of up to 5.5% accuracy and 2.7% macro $F_1$ score on re-training the classifiers. However, applicant gender prediction still remains better than chance. In this case study, our findings highlight that 1) LoRs contain gender-identifying cues that are hard to remove and may activate bias in decision-making and 2) while our technical framework may be a concrete step toward fairer academic and professional evaluations, future work is needed to interrogate the role that gender plays in LoR review. Taken together, our findings motivate upstream auditing of evaluative text in real-world academic letters of recommendation as a necessary complement to model-level fairness interventions.
### Title:
          Do Transformers Use their Depth Adaptively? Evidence from a Relational Reasoning Task
 - **Authors:** Alicia Curth, Rachel Lawrence, Sushrut Karmalkar, Niranjani Prasad
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We investigate whether transformers use their depth adaptively across tasks of increasing difficulty. Using a controlled multi-hop relational reasoning task based on family stories, where difficulty is determined by the number of relationship hops that must be composed, we monitor (i) how predictions evolve across layers via early readouts (the logit lens) and (ii) how task-relevant information is integrated across tokens via causal patching. For pretrained models, we find some limited evidence for adaptive depth use: some larger models need fewer layers to arrive at plausible answers for easier tasks, and models generally use more layers to integrate information across tokens as chain length increases. For models finetuned on the task, we find clearer and more consistent evidence of adaptive depth use, with the effect being stronger for less constrained finetuning regimes that do not preserve general language modeling abilities.
### Title:
          A Hybrid Architecture for Benign-Malignant Classification of Mammography ROIs
 - **Authors:** Mohammed Asad, Mohit Bajpai, Sudhir Singh, Rahul Katarya
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate characterization of suspicious breast lesions in mammography is important for early diagnosis and treatment planning. While Convolutional Neural Networks (CNNs) are effective at extracting local visual patterns, they are less suited to modeling long-range dependencies. Vision Transformers (ViTs) address this limitation through self-attention, but their quadratic computational cost can be prohibitive. This paper presents a hybrid architecture that combines EfficientNetV2-M for local feature extraction with Vision Mamba, a State Space Model (SSM), for efficient global context modeling. The proposed model performs binary classification of abnormality-centered mammography regions of interest (ROIs) from the CBIS-DDSM dataset into benign and malignant classes. By combining a strong CNN backbone with a linear-complexity sequence model, the approach achieves strong lesion-level classification performance in an ROI-based setting.
### Title:
          CoD-Lite: Real-Time Diffusion-Based Generative Image Compression
 - **Authors:** Zhaoyang Jia, Naifu Xue, Zihan Zheng, Jiahao Li, Bin Li, Xiaoyi Zhang, Zongyu Guo, Yuan Zhang, Houqiang Li, Yan Lu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advanced diffusion methods typically derive strong generative priors by scaling diffusion transformers. However, scaling fails to generalize when adapted for real-time compression scenarios that demand lightweight models. In this paper, we explore the design of real-time and lightweight diffusion codecs by addressing two pivotal questions. First, does diffusion pre-training benefit lightweight diffusion codecs? Through systematic analysis, we find that generation-oriented pre-training is less effective at small model scales whereas compression-oriented pre-training yields consistently better performance. Second, are transformers essential? We find that while global attention is crucial for standard generation, lightweight convolutions suffice for compression-oriented diffusion when paired with distillation. Guided by these findings, we establish a one-step lightweight convolution diffusion codec that achieves real-time $60$~FPS encoding and $42$~FPS decoding at 1080p. Further enhanced by distillation and adversarial learning, the proposed codec reduces bitrate by 85\% at a comparable FID to MS-ILLM, bridging the gap between generative compression and practical real-time deployment. Codes are released at this https URL
### Title:
          MODIX: A Training-Free Multimodal Information-Driven Positional Index Scaling for Vision-Language Models
 - **Authors:** Ruoxiang Huang, Zhen Yuan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language Models (VLMs) have achieved remarkable progress in multimodal understanding, yet their positional encoding mechanisms remain suboptimal. Existing approaches uniformly assign positional indices to all tokens, overlooking variations in information density within and across modalities, which leads to inefficient attention allocation where redundant visual regions dominate while informative content is underrepresented. We identify positional granularity as an implicit resource and propose MODIX (Multimodal Information-Driven Positional IndeX Scaling), a training-free framework that dynamically adapts positional strides based on modality-specific contributions. MODIX jointly models intra-modal density via covariance-based entropy and inter-modal interaction via cross-modal alignment to derive unified scores, which rescale positional indices to allocate finer granularity to informative modalities while compressing redundant ones, without requiring any modification to model parameters or architecture. Experiments across diverse architectures and benchmarks demonstrate that MODIX consistently improves multimodal reasoning and adaptively reallocates attention according to task-dependent information distributions, suggesting that positional encoding should be treated as an adaptive resource in Transformers for multimodal sequence modeling.
### Title:
          Cross-Attentive Multiview Fusion of Vision-Language Embeddings
 - **Authors:** Tomas Berriel Martins, Martin R. Oswald, Javier Civera
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language models have been key to the development of open-vocabulary 2D semantic segmentation. Lifting these models from 2D images to 3D scenes, however, remains a challenging problem. Existing approaches typically back-project and average 2D descriptors across views, or heuristically select a single representative one, often resulting in suboptimal 3D representations. In this work, we introduce a novel multiview transformer architecture that cross-attends across vision-language descriptors from multiple viewpoints and fuses them into a unified per-3D-instance embedding. As a second contribution, we leverage multiview consistency as a self-supervision signal for this fusion, which significantly improves performance when added to a standard supervised target-class loss. Our Cross-Attentive Multiview Fusion, which we denote with its acronym CAMFusion, not only consistently outperforms naive averaging or single-view descriptor selection, but also achieves state-of-the-art results on 3D semantic and instance classification benchmarks, including zero-shot evaluations on out-of-domain datasets.
### Title:
          FABLE: Fine-grained Fact Anchoring for Unstructured Model Editing
 - **Authors:** Peng Wang, Biyu Zhou, Xuehai Tang, Jizhong Han, Songlin Hu
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unstructured model editing aims to update models with real-world text, yet existing methods often memorize text holistically without reliable fine-grained fact access. To address this, we propose FABLE, a hierarchical framework that decouples fine-grained fact injection from holistic text generation. FABLE follows a two-stage, fact-first strategy: discrete facts are anchored in shallow layers, followed by minimal updates to deeper layers to produce coherent text. This decoupling resolves the mismatch between holistic recall and fine-grained fact access, reflecting the unidirectional Transformer flow in which surface-form generation amplifies rather than corrects underlying fact representations. We also introduce UnFine, a diagnostic benchmark with fine-grained question-answer pairs and fact-level metrics for systematic evaluation. Experiments show that FABLE substantially improves fine-grained question answering while maintaining state-of-the-art holistic editing performance. Our code is publicly available at this https URL.
### Title:
          Multilingual Multi-Label Emotion Classification at Scale with Synthetic Data
 - **Authors:** Vadim Borisov
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Emotion classification in multilingual settings remains constrained by the scarcity of annotated data: existing corpora are predominantly English, single-label, and cover few languages. We address this gap by constructing a large-scale synthetic training corpus of over 1M multi-label samples (50k per language) across 23 languages: Arabic, Bengali, Dutch, English, French, German, Hindi, Indonesian, Italian, Japanese, Korean, Mandarin, Polish, Portuguese, Punjabi, Russian, Spanish, Swahili, Tamil, Turkish, Ukrainian, Urdu, and Vietnamese, covering 11 emotion categories using culturally-adapted generation and programmatic quality filtering. We train and compare six multilingual transformer encoders, from DistilBERT (135M parameters) to XLM-R-Large (560M parameters), under identical conditions. On our in-domain test set, XLM-R-Large achieves 0.868 F1-micro and 0.987 AUC-micro. To validate against human-annotated data, we evaluate all models zero-shot on GoEmotions (English) and SemEval-2018 Task 1 E-c (English, Arabic, Spanish). On threshold-free ranking metrics, XLM-R-Large matches or exceeds English-only specialist models, tying on AP-micro (0.636) and LRAP (0.804) while surpassing on AUC-micro (0.810 vs. 0.787), while natively supporting all 23 languages. The best base-sized model is publicly available at this https URL
### Title:
          Brain-DiT: A Universal Multi-state fMRI Foundation Model with Metadata-Conditioned Pretraining
 - **Authors:** Junfeng Xia, Wenhao Ye, Xuanye Pan, Xinke Shen, Mo Wang, Quanying Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Neurons and Cognition (q-bio.NC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current fMRI foundation models primarily rely on a limited range of brain states and mismatched pretraining tasks, restricting their ability to learn generalized representations across diverse brain states. We present \textit{Brain-DiT}, a universal multi-state fMRI foundation model pretrained on 349,898 sessions from 24 datasets spanning resting, task, naturalistic, disease, and sleep states. Unlike prior fMRI foundation models that rely on masked reconstruction in the raw-signal space or a latent space, \textit{Brain-DiT} adopts metadata-conditioned diffusion pretraining with a Diffusion Transformer (DiT), enabling the model to learn multi-scale representations that capture both fine-grained functional structure and global semantics. Across extensive evaluations and ablations on 7 downstream tasks, we find consistent evidence that diffusion-based generative pretraining is a stronger proxy than reconstruction or alignment, with metadata-conditioned pretraining further improving downstream performance by disentangling intrinsic neural dynamics from population-level variability. We also observe that downstream tasks exhibit distinct preferences for representational scale: ADNI classification benefits more from global semantic representations, whereas age/sex prediction comparatively relies more on fine-grained local structure. Code and parameters of Brain-DiT are available at \href{this https URL}{Link}.
### Title:
          Risk-Calibrated Learning: Minimizing Fatal Errors in Medical AI
 - **Authors:** Abolfazl Mohammadi-Seif, Ricardo Baeza-Yates
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning models often achieve expert-level accuracy in medical image classification but suffer from a critical flaw: semantic incoherence. These high-confidence mistakes that are semantically incoherent (e.g., classifying a malignant tumor as benign) fundamentally differ from acceptable errors which stem from visual ambiguity. Unlike safe, fine-grained disagreements, these fatal failures erode clinical trust. To address this, we propose Risk-Calibrated Learning, a technique that explicitly distinguishes between visual ambiguity (fine-grained errors) and catastrophic structural errors. By embedding a confusion-aware clinical severity matrix M into the optimization landscape, our method suppresses critical errors (false negatives) without requiring complex architectural changes. We validate our approach in four different imaging modalities: Brain Tumor MRI, ISIC 2018 (Dermoscopy), BreaKHis (Breast Histopathology), and SICAPv2 (Prostate Histopathology). Extensive experiments demonstrate that our Risk-Calibrated Loss consistently reduces the Critical Error Rate (CER) for all four datasets, achieving relative safety improvements ranging from 20.0% (on breast histopathology) to 92.4% (on prostate histopathology) compared to state-of-the-art baselines such as Focal Loss. These results confirm that our method offers a superior safety-accuracy trade-off across both CNN and Transformer architectures.
### Title:
          Transformer Based Machine Fault Detection From Audio Input
 - **Authors:** Kiran Voderhobli Holla
 - **Subjects:** Subjects:
Sound (cs.SD); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In recent years, Sound AI is being increasingly used to predict machine failures. By attaching a microphone to the machine of interest, one can get real time data on machine behavior from the field. Traditionally, Convolutional Neural Net (CNN) architectures have been used to analyze spectrogram images generated from the sounds captured and predict if the machine is functioning as expected. CNN architectures seem to work well empirically even though they have biases like locality and parameter-sharing which may not be completely relevant for spectrogram analysis. With the successful application of transformer-based models in the field of image processing starting with Vision Transformer (ViT) in 2020, there has been significant interest in leveraging these in the field of Sound AI. Since transformer-based architectures have significantly lower inductive biases, they are expected to perform better than CNNs at spectrogram analysis given enough data. This paper demonstrates the effectiveness of transformer-driven architectures in analyzing Sound data and compares the embeddings they generate with CNNs on the specific task of machine fault detection.
### Title:
          CLASP: Class-Adaptive Layer Fusion and Dual-Stage Pruning for Multimodal Large Language Models
 - **Authors:** Yunkai Dang, Yizhu Jiang, Yifan Jiang, Qi Fan, Yinghuan Shi, Wenbin Li, Yang Gao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal Large Language Models (MLLMs) suffer from substantial computational overhead due to the high redundancy in visual token sequences. Existing approaches typically address this issue using single-layer Vision Transformer (ViT) features and static pruning strategies. However, such fixed configurations are often brittle under diverse instructions. To overcome these limitations, we propose CLASP, a plug-and-play token reduction framework based on class-adaptive layer fusion and dual-stage pruning. Specifically, CLASP first constructs category-specific visual representations through multi-layer vision feature fusion. It then performs dual-stage pruning, allocating the token budget between attention-salient pivot tokens for relevance and redundancy-aware completion tokens for coverage. Through class-adaptive pruning, CLASP enables prompt-conditioned feature fusion and budget allocation, allowing aggressive yet robust visual token reduction. Extensive experiments demonstrate that CLASP consistently outperforms existing methods across a wide range of benchmarks, pruning ratios, and MLLM architectures. Code will be available at this https URL.
### Title:
          Efficient Adversarial Training via Criticality-Aware Fine-Tuning
 - **Authors:** Wenyun Li, Zheng Zhang, Dongmei Jiang, Yaowei Wang, Xiangyuan Lan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformer (ViT) models have achieved remarkable performance across various vision tasks, with scalability being a key advantage when applied to large datasets. This scalability enables ViT models to exhibit strong generalization capabilities. However, as the number of parameters increases, the robustness of ViT models to adversarial examples does not scale proportionally. Adversarial training (AT), one of the most effective methods for enhancing robustness, typically requires fine-tuning the entire model, leading to prohibitively high computational costs, especially for large ViT architectures. In this paper, we aim to robustly fine-tune only a small subset of parameters to achieve robustness comparable to standard AT. To accomplish this, we introduce Criticality-Aware Adversarial Training (CAAT), a novel method that adaptively allocates resources to the most robustness-critical parameters, fine-tuning only selected modules. Specifically, CAAT efficiently identifies parameters that contribute most to adversarial robustness. It then leverages parameter-efficient fine-tuning (PEFT) to robustly adjust weight matrices where the number of critical parameters exceeds a predefined threshold. CAAT exhibits favorable generalization when scaled to larger vision transformer architectures, potentially paving the way for adversarial training at scale, e.g, compared with plain adversarial training, CAAT incurs only a 4.3% decrease in adversarial robustness while tuning approximately 6% of its parameters. Extensive experiments on three widely used adversarial learning datasets demonstrate that CAAT outperforms state-of-the-art lightweight AT methods with fewer trainable parameters.
### Title:
          Understanding and Improving Continuous Adversarial Training for LLMs via In-context Learning Theory
 - **Authors:** Shaopeng Fu, Di Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Cryptography and Security (cs.CR); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adversarial training (AT) is an effective defense for large language models (LLMs) against jailbreak attacks, but performing AT on LLMs is costly. To improve the efficiency of AT for LLMs, recent studies propose continuous AT (CAT) that searches for adversarial inputs within the continuous embedding space of LLMs during AT. While CAT has achieved empirical success, its underlying mechanism, i.e., why adversarial perturbations in the embedding space can help LLMs defend against jailbreak prompts synthesized in the input token space, remains unknown. This paper presents the first theoretical analysis of CAT on LLMs based on in-context learning (ICL) theory. For linear transformers trained with adversarial examples from the embedding space on in-context linear regression tasks, we prove a robust generalization bound that has a negative correlation with the perturbation radius in the embedding space. This clearly explains why CAT can defend against jailbreak prompts from the LLM's token space. Further, the robust bound shows that the robustness of an adversarially trained LLM is closely related to the singular values of its embedding matrix. Based on this, we propose to improve LLM CAT by introducing an additional regularization term, which depends on singular values of the LLM's embedding matrix, into the objective function of CAT. Experiments on real-world LLMs demonstrate that our method can help LLMs achieve a better jailbreak robustness-utility tradeoff. The code is available at this https URL.
### Title:
          LIFE -- an energy efficient advanced continual learning agentic AI framework for frontier systems
 - **Authors:** Anne Lee, Gurudutt Hosangadi
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid advancement of AI has changed the character of HPC usage such as dimensioning, provisioning, and execution. Not only has energy demand been amplified, but existing rudimentary continual learning capabilities limit ability of AI to effectively manage HPCs. This paper reviews emerging directions beyond monolithic transformers, emphasizing agentic AI and brain inspired architectures as complementary paths toward sustainable, adaptive systems. We propose LIFE, a reasoning and Learning framework that is Incremental, Flexible, and Energy efficient that is implemented as an agent centric system rather than a single monolithic model. LIFE uniquely combines four components to realize self evolving network management and operations in HPCs. The components are an orchestrator, Agentic Context Engineering, a novel memory system, and information lattice learning. LIFE can also generalize to enable a variety of orthogonal use cases. We ground LIFE in a specific closed loop HPC operations example for detecting and mitigating latency spikes experienced by critical micro services running on a Kubernetes like cluster.
### Title:
          Representing 3D Faces with Learnable B-Spline Volumes
 - **Authors:** Prashanth Chandran, Daoye Wang, Timo Bolkart
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present CUBE (Control-based Unified B-spline Encoding), a new geometric representation for human faces that combines B-spline volumes with learned features, and demonstrate its use as a decoder for 3D scan registration and monocular 3D face reconstruction. Unlike existing B-spline representations with 3D control points, CUBE is parametrized by a lattice (e.g., 8 x 8 x 8) of high-dimensional control features, increasing the model's expressivity. These features define a continuous, two-stage mapping from a 3D parametric domain to 3D Euclidean space via an intermediate feature space. First, high-dimensional control features are locally blended using the B-spline bases, yielding a high-dimensional feature vector whose first three values define a 3D base mesh. A small MLP then processes this feature vector to predict a residual displacement from the base shape, yielding the final refined 3D coordinates. To reconstruct 3D surfaces in dense semantic correspondence, CUBE is queried at 3D coordinates sampled from a fixed template mesh. Crucially, CUBE retains the local support property of traditional B-spline representations, enabling local surface editing by updating individual control features. We demonstrate the strengths of this representation by training transformer-based encoders to predict CUBE's control features from unstructured point clouds and monocular images, achieving state-of-the-art scan registration results compared to recent baselines.
### Title:
          Parcae: Scaling Laws For Stable Looped Language Models
 - **Authors:** Hayden Prairie, Zachary Novack, Taylor Berg-Kirkpatrick, Daniel Y. Fu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traditional fixed-depth architectures scale quality by increasing training FLOPs, typically through increased parameterization, at the expense of a higher memory footprint, or data. A potential alternative is looped architectures, which instead increase FLOPs by sending activations through a block of layers in a loop. While promising, existing recipes for training looped architectures can be unstable, suffering from residual explosion and loss spikes. We address these challenges by recasting looping as a nonlinear time-variant dynamical system over the residual stream. Via a linear approximation to this system, we find that instability occurs in existing looped architectures as a result of large spectral norms in their injection parameters. To address these instability issues, we propose Parcae, a novel stable, looped architecture that constrains the spectral norm of the injection parameters via discretization of a negative diagonal parameterization. As a result, Parcae achieves up to 6.3% lower validation perplexity over prior large-scale looped models. Using our stable looped architecture, we investigate the scaling properties of looping as a medium to improve quality by increasing FLOPs in training and test-time. For training, we derive predictable power laws to scale FLOPs while keeping parameter count fixed. Our initial scaling laws suggest that looping and data should be increased in tandem, given a fixed FLOP budget. At test-time, we find that Parcae can use looping to scale compute, following a predictable, saturating exponential decay. When scaled up to 1.3B parameters, we find that Parcae improves CORE and Core-Extended quality by 2.99 and 1.18 points when compared to strong Transformer baselines under a fixed parameter and data budget, achieving a relative quality of up to 87.5% a Transformer twice the size.
### Title:
          Learning Versatile Humanoid Manipulation with Touch Dreaming
 - **Authors:** Yaru Niu, Zhenlong Fang, Binghong Chen, Shuai Zhou, Revanth Senthilkumaran, Hao Zhang, Bingqing Chen, Chen Qiu, H. Eric Tseng, Jonathan Francis, Ding Zhao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Humanoid robots promise general-purpose assistance, yet real-world humanoid loco-manipulation remains challenging because it requires whole-body stability, dexterous hands, and contact-aware perception under frequent contact changes. In this work, we study dexterous, contact-rich humanoid loco-manipulation. We first develop an RL-based whole-body controller that provides stable lower-body and torso execution during complex manipulation. Built on this controller, we develop a whole-body humanoid data collection system that combines VR-based teleoperation with human-to-humanoid motion mapping, enabling efficient collection of real-world demonstrations. We then propose Humanoid Transformer with Touch Dreaming (HTD), a multimodal encoder--decoder Transformer that models touch as a core modality alongside multi-view vision and proprioception. HTD is trained in a single stage with behavioral cloning augmented by touch dreaming: in addition to predicting action chunks, the policy predicts future hand-joint forces and future tactile latents, encouraging the shared Transformer trunk to learn contact-aware representations for dexterous interaction. Across five contact-rich tasks, Insert-T, Book Organization, Towel Folding, Cat Litter Scooping, and Tea Serving, HTD achieves a 90.9% relative improvement in average success rate over the stronger baseline. Ablation results further show that latent-space tactile prediction is more effective than raw tactile prediction, yielding a 30% relative gain in success rate. These results demonstrate that combining robust whole-body execution, scalable humanoid data collection, and predictive touch-centered learning enables versatile, high-dexterity humanoid manipulation in the real world. Project webpage: this http URL.
### Title:
          CLAD: Efficient Log Anomaly Detection Directly on Compressed Representations
 - **Authors:** Benzhao Tang, Shiyu Yang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Databases (cs.DB)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The explosive growth of system logs makes streaming compression essential, yet existing log anomaly detection (LAD) methods incur severe pre-processing overhead by requiring full decompression and parsing. We introduce CLAD, the first deep learning framework to perform LAD directly on compressed byte streams. CLAD bypasses these bottlenecks by exploiting a key insight: normal logs compress into regular byte patterns, while anomalies systematically disrupt them. To extract these multi-scale deviations from opaque bytes, we propose a purpose-built architecture integrating a dilated convolutional byte encoder, a hybrid Transformer--mLSTM, and four-way aggregation pooling. This is coupled with a two-stage training strategy of masked pre-training and focal-contrastive fine-tuning to effectively handle severe class imbalance. Evaluated across five datasets, CLAD achieves a state-of-the-art average F1-score of 0.9909 and outperforms the best baseline by 2.72 percentage points. It delivers superior accuracy while completely eliminating decompression and parsing overheads, offering a robust solution that generalizes to structured streaming compressors.
## Keyword: autonomous driving
### Title:
          MVAdapt: Zero-Shot Multi-Vehicle Adaptation for End-to-End Autonomous Driving
 - **Authors:** Haesung Oh, Jaeheung Park
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-End (E2E) autonomous driving models are usually trained and evaluated with a fixed ego-vehicle, even though their driving policy is implicitly tied to vehicle dynamics. When such a model is deployed on a vehicle with different size, mass, or drivetrain characteristics, its performance can degrade substantially; we refer to this problem as the vehicle-domain gap. To address it, we propose MVAdapt, a physics-conditioned adaptation framework for multi-vehicle E2E driving. MVAdapt combines a frozen TransFuser++ scene encoder with a lightweight physics encoder and a cross-attention module that conditions scene features on vehicle properties before waypoint decoding. In the CARLA Leaderboard 1.0 benchmark, MVAdapt improves over naive transfer and multi-embodiment adaptation baselines on both in-distribution and unseen vehicles. We further show two complementary behaviors: strong zero-shot transfer on many unseen vehicles, and data-efficient few-shot calibration for severe physical outliers. These results suggest that explicitly conditioning E2E driving policies on vehicle physics is an effective step toward more transferable autonomous driving models. All codes are available at this https URL
### Title:
          Unveiling the Surprising Efficacy of Navigation Understanding in End-to-End Autonomous Driving
 - **Authors:** Zhihua Hua, Junli Wang, Pengfei LI, Qihao Jin, Bo Zhang, Kehua Sheng, Yilun Chen, Zhongxue Gan, Wenchao Ding
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Global navigation information and local scene understanding are two crucial components of autonomous driving systems. However, our experimental results indicate that many end-to-end autonomous driving systems tend to over-rely on local scene understanding while failing to utilize global navigation information. These systems exhibit weak correlation between their planning capabilities and navigation input, and struggle to perform navigation-following in complex scenarios. To overcome this limitation, we propose the Sequential Navigation Guidance (SNG) framework, an efficient representation of global navigation information based on real-world navigation patterns. The SNG encompasses both navigation paths for constraining long-term trajectories and turn-by-turn (TBT) information for real-time decision-making logic. We constructed the SNG-QA dataset, a visual question answering (VQA) dataset based on SNG that aligns global and local planning. Additionally, we introduce an efficient model SNG-VLA that fuses local planning with global planning. The SNG-VLA achieves state-of-the-art performance through precise navigation information modeling without requiring auxiliary loss functions from perception tasks. Project page: SNG-VLA
### Title:
          Physics-Grounded Monocular Vehicle Distance Estimation Using Standardized License Plate Typography
 - **Authors:** Manognya Lokesh Reddy, Zheng Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate inter-vehicle distance estimation is a cornerstone of Advanced Driver Assistance Systems (ADAS) and autonomous driving. While LiDAR and radar provide high precision, their high cost prohibits widespread adoption in mass-market vehicles. Monocular camera-based estimation offers a low-cost alternative but suffers from fundamental scale ambiguity. Recent deep learning methods for monocular depth achieve impressive results yet require expensive supervised training, suffer from domain shift, and produce predictions that are difficult to certify for safety-critical deployment. This paper presents a framework that exploits the standardized typography of United States license plates as passive fiducial markers for metric ranging, resolving scale ambiguity through explicit geometric priors without any training data or active illumination. First, a four-method parallel plate detector achieves robust plate reading across the full automotive lighting range. Second, a three-stage state identification engine fusing OCR text matching, multi-design color scoring, and a lightweight neural network classifier provides robust identification across all ambient conditions. Third, hybrid depth fusion with inverse-variance weighting and online scale alignment, combined with a one-dimensional constant-velocity Kalman filter, delivers smoothed distance, relative velocity, and time-to-collision for collision warning. Baseline validation reproduces a 2.3% coefficient of variation in character height measurements and a 36% reduction in distance-estimate variance compared with plate-width methods from prior work. Extensive outdoor experiments confirm a mean absolute error of 2.3% at 10 m and continuous distance output during brief plate occlusions, outperforming deep learning baselines by a factor of five in relative error.
### Title:
          HyperLiDAR: Adaptive Post-Deployment LiDAR Segmentation via Hyperdimensional Computing
 - **Authors:** Ivannia Gomez Moreno, Yi Yao, Ye Tian, Xiaofan Yu, Flavio Ponzina, Michael Sullivan, Jingyi Zhang, Mingyu Yang, Hun Seok Kim, Tajana Rosing
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR semantic segmentation plays a pivotal role in 3D scene understanding for edge applications such as autonomous driving. However, significant challenges remain for real-world deployments, particularly for on-device post-deployment adaptation. Real-world environments can shift as the system navigates through different locations, leading to substantial performance degradation without effective and timely model adaptation. Furthermore, edge systems operate under strict computational and energy constraints, making it infeasible to adapt conventional segmentation models (based on large neural networks) directly on-device. To address the above challenges, we introduce HyperLiDAR, the first lightweight, post-deployment LiDAR segmentation framework based on Hyperdimensional Computing (HDC). The design of HyperLiDAR fully leverages the fast learning and high efficiency of HDC, inspired by how the human brain processes information. To further improve the adaptation efficiency, we identify the high data volume per scan as a key bottleneck and introduce a buffer selection strategy that focuses learning on the most informative points. We conduct extensive evaluations on two state-of-the-art LiDAR segmentation benchmarks and two representative devices. Our results show that HyperLiDAR outperforms or achieves comparable adaptation performance to state-of-the-art segmentation methods, while achieving up to a 13.8x speedup in retraining.
### Title:
          RACF: A Resilient Autonomous Car Framework with Object Distance Correction
 - **Authors:** Chieh Tsai, Hossein Rastgoftar, Salim Hariri
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous vehicles are increasingly deployed in safety-critical applications, where sensing failures or cyberphysical attacks can lead to unsafe operations resulting in human loss and/or severe physical damages. Reliable real-time perception is therefore critically important for their safe operations and acceptability. For example, vision-based distance estimation is vulnerable to environmental degradation and adversarial perturbations, and existing defenses are often reactive and too slow to promptly mitigate their impacts on safe operations. We present a Resilient Autonomous Car Framework (RACF) that incorporates an Object Distance Correction Algorithm (ODCA) to improve perception-layer robustness through redundancy and diversity across a depth camera, LiDAR, and physics-based kinematics. Within this framework, when obstacle distance estimation produced by depth camera is inconsistent, a cross-sensor gate activates the correction algorithm to fix the detected inconsistency. We have experiment with the proposed resilient car framework and evaluate its performance on a testbed implemented using the Quanser QCar 2 platform. The presented framework achieved up to 35% RMSE reduction under strong corruption and improves stop compliance and braking latency, while operating in real time. These results demonstrate a practical and lightweight approach to resilient perception for safety-critical autonomous driving
### Title:
          FeaXDrive: Feasibility-aware Trajectory-Centric Diffusion Planning for End-to-End Autonomous Driving
 - **Authors:** Baoyun Wang, Zhuoren Li, Ming Liu, Xinrui Zhang, Bo Leng, Lu Xiong
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end diffusion planning has shown strong potential for autonomous driving, but the physical feasibility of generated trajectories remains insufficiently addressed. In particular, generated trajectories may exhibit local geometric irregularities, violate trajectory-level kinematic constraints, or deviate from the drivable area, indicating that the commonly used noise-centric formulation in diffusion planning is not yet well aligned with the trajectory space where feasibility is more naturally characterized. To address this issue, we propose FeaXDrive, a feasibility-aware trajectory-centric diffusion planning method for end-to-end autonomous driving. The core idea is to treat the clean trajectory as the unified object for feasibility-aware modeling throughout the diffusion process. Built on this trajectory-centric formulation, FeaXDrive integrates adaptive curvature-constrained training to improve intrinsic geometric and kinematic feasibility, drivable-area guidance within reverse diffusion sampling to enhance consistency with the drivable area, and feasibility-aware GRPO post-training to further improve planning performance while balancing trajectory-space feasibility. Experiments on the NAVSIM benchmark show that FeaXDrive achieves strong closed-loop planning performance while substantially improving trajectory-space feasibility. These findings highlight the importance of explicitly modeling trajectory-space feasibility in end-to-end diffusion planning and provide a step toward more reliable and physically grounded autonomous driving planners.
### Title:
          Radar-Camera BEV Multi-Task Learning with Cross-Task Attention Bridge for Joint 3D Detection and Segmentation
 - **Authors:** Ahmet İnanç, Özgür Erkent
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bird's-eye-view (BEV) representations are the dominant paradigm for 3D perception in autonomous driving, providing a unified spatial canvas where detection and segmentation features are geometrically registered to the same physical coordinate system. However, existing radar-camera fusion methods treat these tasks in isolation, missing the opportunity to share complementary information between them: detection features encode object-level geometry that can sharpen segmentation boundaries, while segmentation features provide dense semantic context that can anchor detection. We propose \textbf{CTAB} (Cross-Task Attention Bridge), a bidirectional module that exchanges features between detection and segmentation branches via multi-scale deformable attention in shared BEV space. CTAB is integrated into a multi-task framework with an Instance Normalization-based segmentation decoder and learnable BEV upsampling to provide a more detailed BEV representation. On nuScenes, CTAB improves segmentation on 7 classes over the joint multi-task baseline at essentially neutral detection. On a 4-class subset (drivable area, pedestrian crossing, walkway, vehicle), our joint multi-task model reaches comparable mIoU on 4 classes while simultaneously providing 3D detection.
