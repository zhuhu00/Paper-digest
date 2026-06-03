# Showing new listings for Wednesday, 3 June 2026
## Keyword: SLAM
### Title:
          Autonomous Navigation System for Library Service Robot Based on Unitree Go2 Edu
 - **Authors:** Aoduo Li, Haoran Lv, Bingquan Ou, Jianfeng Li, Yingdong Li, Zimeng Li
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Libraries require autonomous robots to move quietly through narrow aisles while remaining safe around readers, chairs, bags, and carts. This paper presents a ROS 2 navigation system for a Unitree Go2 Edu quadruped equipped with a 4D LiDAR, a front depth camera, and an IMU. Rather than assuming the library is rough terrain, we target the practical mobility discontinuities of real deployments, including floor transitions, temporary clutter, and partially blocked passages where low-clearance wheeled platforms are less tolerant. RTAB-Map is used for visual-LiDAR SLAM, AMCL and EKF-based sensor fusion provide localization, and a Nav2 stack with A* and DWA supports planning and local avoidance. In a real library, the system achieves 100%, 96%, and 88% success rates in static, low-density dynamic, and high-density dynamic scenes, while map validation against surveyed control distances yields a mean metric error of 3.7 cm.
## Keyword: odometry
### Title:
          MARIO: Motion-Augmented Real-Time Multi-Sensor Inertial Odometry
 - **Authors:** Yiquan Li, Taeyoung Yeon, Chenfeng Gao, Vasco Xu, Xuanyou Liu, Karan Ahuja
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Inertial odometry (IO) using only Inertial Measurement Units (IMUs) provides a lightweight solution for human motion tracking in augmented reality (AR) and wearable devices. Recent learning-based IO methods have improved the generalizability of inertial localization through large-scale pretraining on human motion datasets. However, these approaches remain prone to drift and noise because they do not explicitly capture human motion dynamics, especially on daily activity datasets such as Nymeria. In this work, we propose to ground inertial odometry in human kinematics through a learned IMU-inferred pose prior, which promotes physically consistent motion constraints. We integrate this pose prior into existing IO architectures and reduce positional drift by up to 36% on the challenging Nymeria dataset, which is 5x larger than datasets used in prior work. We further improve long-term performance with a sensor-fusion framework that incorporates auxiliary signals from lightweight sensors already available on commercial AR glasses, including magnetometers, barometers, and secondary IMUs. With this fusion strategy, positional drift is reduced by up to 42%, improving robustness and generalization across diverse motion conditions. Together, our results introduce a new paradigm for inertial and lightweight odometry by unifying human motion kinematics with multimodal sensing, setting a new benchmark for accurate and robust camera-less human tracking. Our website is available at this https URL.
### Title:
          Semantic-weighted ICP for LiDAR Odometry: Class-Aware Residual Reweighting for Robust Scan Registration
 - **Authors:** Vasco Carvalho, Tiago Barros, Urbano J. Nunes
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR odometry is a fundamental component of autonomous robotic systems, relying on geometric registration between consecutive point clouds to estimate ego-motion. However, traditional geometric approaches often degrade in dynamic or unstructured environments due to unreliable correspondences caused by moving objects, sparse geometric features, vegetation, and semantically ambiguous structures. Existing works have shown that, some of these limitations can be addressed by introducing semantic information from the environment in the registration process. In this work, we build on this, and show that not all elements in the environment are equally relevant for registration. Hence, we propose a semantic class-weighted ICP for LiDAR odometry. Instead of strictly filtering out points belonging to specific semantic classes, the proposed approach weights the residuals of points belonging to semantic categories based on their expected geometric stability. This strategy enables informative but potentially unstable structures, to contribute to the registration process while mitigating the influence of dynamic objects. The experimental evaluation was conducted on the SemanticKITTI and RELLIS-3D datasets, which include urban, highway, rural, and off-road environments. The empirical results show that the proposed Semantic-weighted ICP improves pose estimation, especially in challenging off-road scenarios where conventional rigid features are scarce. Furthermore, the analysis reveals that the effectiveness of this weighting strategy is highly environment-dependent, influenced by the structural and semantic composition of the scene.
### Title:
          PixVOD: Pixel-Distributed Direct Visual Odometry and Depth Estimation
 - **Authors:** Shinjeong Kim, Ignacio Alzugaray, Callum Rhodes, Paul H. J. Kelly, Andrew J. Davison
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Images composed of 2D pixel arrays are the standard input to computer vision algorithms, yet many underlying computations can be distributed across pixels. Transmitting raw, redundant, and noisy pixel data off the sensor remains inefficient, motivating a shift toward focal-plane sensor-processors that perform a significant part of the computation directly within each pixel. We envision pixels synthesizing higher-level signals locally, reducing downstream load, and providing richer inputs for higher-level vision tasks. We propose a fully parallelizable form of visual odometry and depth estimation across pixels, where sensor-processors exchange information through Gaussian Belief Propagation (GBP) to achieve consensus about camera motion and infer depth from per-pixel photometric observations and a surface normal prior. To maintain geometric stability during optimization, we introduce a keyframe-like anchoring mechanism that regulates the effective baseline between frames, enabling consistent motion and depth updates. Our method is evaluated on realistic datasets, demonstrating the feasibility of GBP-based pixel-level distributed odometry and depth estimation with keyframe anchoring on-sensor. Project Page: this https URL
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Motion Planning in Dynamic Environments: A Survey from Classical to Modern Methods
 - **Authors:** Zongyuan Shen, Yaming Ou, Shalabh Gupta, Shancheng Zhao, Dehua Zhou, Gao Wang, Zhongqiang Ren, Junfeng Fan, Long Cheng
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Motion planning in dynamic environments requires robots to continuously adapt their paths in response to environmental changes for safe and uninterrupted navigation. While many surveys have reviewed planning in static settings, systematic reviews focused on dynamic environments remain limited. This paper presents a comprehensive survey of 138 works, primarily published between 2015 and 2025, spanning both classical and learning-based approaches. The motion planning methods are grouped into five categories based on the concepts of sampling, graph search, model predictive control, learning, and additional classical local planning approaches, including velocity obstacles, potential fields and dynamic windows. The learning techniques include supervised learning and reinforcement learning. We also discuss the role of dynamic perception in motion planning, covering techniques for detecting and modeling moving obstacles using cameras, LiDAR, and event-based sensors. The survey analyzes the principles, strengths, and limitations of each method, with particular attention to challenges unique to dynamic environments, such as prediction uncertainty, human-robot interaction, and the freezing robot problem. The survey provides researchers with a structured understanding of motion planning methods in dynamic environments.
### Title:
          ATLAS: A Large-Scale Evaluation Benchmark for Adversarial LiDAR Perception
 - **Authors:** Mellon M. Zhang, Siddhant Panse, Zimo Fan, Akshal Dhal, Rishit Sarkar, Glen Chou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving perception is typically evaluated on clean benchmark data, yet real-world deployment requires robustness to rare, structured, and potentially adversarial sensor anomalies. This gap is especially critical for LiDAR, where external actors can physically manipulate the sensing process to induce black-box perception failures without accessing the model. Existing LiDAR benchmarks provide little visibility into this failure mode. Prior adversarial LiDAR studies have largely centered on attack hardware, geometric and algorithmic defenses, and early-generation detectors, leaving the robustness of modern perception systems unexplored. To address this evaluation gap, we introduce ATLAS (Adversarial Temporal LiDAR Attack Suite), the first large-scale, physically grounded evaluation benchmark for LiDAR perception models under black-box sensor attacks, simulating the two primary attack modes -- point injection and point removal -- across real driving sequences. Evaluating a broad cross-section of current state-of-the-art LiDAR perception models, ATLAS reveals a surprising robustness asymmetry: models with stronger performance on standard benchmarks tend to better withstand removal attacks, yet are actually more vulnerable to injection attacks than weaker models. We trace this vulnerability to standard object database sampling augmentations, revealing how current training practices can induce architecture-agnostic robustness failures, and study initial directions for mitigating both attack modes. We release the ATLAS generation code to support extensible, reproducible evaluations as attack capabilities evolve, helping make black-box sensor robustness an explicit consideration in future LiDAR perception development.
### Title:
          The Road Ahead in Autonomous Driving: The KITScenes Multimodal Dataset
 - **Authors:** Richard Schwarzkopf, Fabian Immel, Alexander Blumberg, Jonas Merkert, Nils Rack, Kaiwen Wang, Fabian Konstantinidis, Julian Truetsch, Carlos Fernandez, Annika Bätz, Kevin Rösch, Marlon Steiner, Willi Poh, Yinzhe Shen, Royden Wagner, Felix Hauser, Dominik Strutz, Jaime Villa, Gleb Stepanov, Holger Caesar, Ömer Şahin Taş, Frank Bieder, Jan-Hendrik Pauls, Christoph Stiller
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing autonomous driving datasets have enabled major progress, but fall short in sensor fidelity, map completeness, or geographic diversity. We present KITScenes Multimodal, a European dataset built around high-fidelity sensors and maps. Our fully synchronized sensor suite combines high-resolution global-shutter cameras, long-range lidar beyond 400m, 4D imaging radar, and redundant GNSS/INS localization. Our HD maps are, to our knowledge, the most complete of any sensor dataset, validated through autonomous driving trials on open-source software. For the first time in a public dataset, all driving-relevant traffic elements, such as traffic lights, are mapped in 3D to a reprojection-accurate level with full topological connectivity. Recorded in cities with irregular street layouts and mixed traffic modes, our dataset complements existing datasets by broadening the available geographic diversity. We also introduce four benchmarks, each advancing spatial learning for embodied AI: online HD map construction, long-range depth estimation, novel view synthesis, and end-to-end driving. Project page: this https URL
### Title:
          Towards Compact Autonomous Driving Perception with Balanced Learning and Multi-sensor Fusion
 - **Authors:** Oskar Natan, Jun Miura
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a novel compact deep multi-task learning model to handle various autonomous driving perception tasks in one forward pass. The model performs multiple views of semantic segmentation, depth estimation, light detection and ranging (LiDAR) segmentation, and bird's eye view projection simultaneously without being supported by other models. We also provide an adaptive loss weighting algorithm to tackle the imbalanced learning issue that occurred due to plenty of given tasks. Through data pre-processing and intermediate sensor fusion techniques, the model can process and combine multiple input modalities retrieved from RGB cameras, dynamic vision sensors (DVS), and LiDAR placed at several positions on the ego vehicle. Therefore, a better understanding of a dynamically changing environment can be achieved. Based on the ablation study, the model variant trained with our proposed method achieves a better performance. Furthermore, a comparative study is also conducted to clarify its performance and effectiveness against the combination of some recent models. As a result, our model maintains better performance even with much fewer parameters. Hence, the model can inference faster with less GPU memory utilization. Moreover, the result tends to be consistent in 3 different CARLA simulation datasets and 1 real-world nuScenes-lidarseg dataset. To support future research, we share codes and other files publicly at this https URL.
### Title:
          Autonomous Navigation System for Library Service Robot Based on Unitree Go2 Edu
 - **Authors:** Aoduo Li, Haoran Lv, Bingquan Ou, Jianfeng Li, Yingdong Li, Zimeng Li
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Libraries require autonomous robots to move quietly through narrow aisles while remaining safe around readers, chairs, bags, and carts. This paper presents a ROS 2 navigation system for a Unitree Go2 Edu quadruped equipped with a 4D LiDAR, a front depth camera, and an IMU. Rather than assuming the library is rough terrain, we target the practical mobility discontinuities of real deployments, including floor transitions, temporary clutter, and partially blocked passages where low-clearance wheeled platforms are less tolerant. RTAB-Map is used for visual-LiDAR SLAM, AMCL and EKF-based sensor fusion provide localization, and a Nav2 stack with A* and DWA supports planning and local avoidance. In a real library, the system achieves 100%, 96%, and 88% success rates in static, low-density dynamic, and high-density dynamic scenes, while map validation against surveyed control distances yields a mean metric error of 3.7 cm.
### Title:
          Learned Non-Maximum Suppression for 3D Object Detection
 - **Authors:** Timo Osterburg, Stefan Schütte, Torsten Bertram
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Post-processing is a critical stage in LiDAR-based 3D object detection, where dense and overlapping proposals must be filtered for compact and reliable perception. This work introduces two learned filtering modules that replace heuristic non-maximum suppression (NMS) by leveraging relations among detections. D2D-Rescore employs transformer-based detection-to-detection (D2D) attention, while GossipNet3D adapts the 2D GossipNet concept to 3D through localized message passing in bird's-eye view. A metric-aware matching strategy aligned with the nuScenes evaluation protocol ensures consistent training and validation behavior, improving overall detection performance. Both approaches improve mean average precision (mAP), nuScenes detection score (NDS), and true positive quality compared to CircleNMS, particularly for small and infrequent classes, while adding minimal computational overhead. These results demonstrate that learned, detection-level filtering can enhance 3D detector reliability without modifying the base network, offering a principled alternative to heuristic suppression. Code is available at this https URL .
### Title:
          Semantic-weighted ICP for LiDAR Odometry: Class-Aware Residual Reweighting for Robust Scan Registration
 - **Authors:** Vasco Carvalho, Tiago Barros, Urbano J. Nunes
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR odometry is a fundamental component of autonomous robotic systems, relying on geometric registration between consecutive point clouds to estimate ego-motion. However, traditional geometric approaches often degrade in dynamic or unstructured environments due to unreliable correspondences caused by moving objects, sparse geometric features, vegetation, and semantically ambiguous structures. Existing works have shown that, some of these limitations can be addressed by introducing semantic information from the environment in the registration process. In this work, we build on this, and show that not all elements in the environment are equally relevant for registration. Hence, we propose a semantic class-weighted ICP for LiDAR odometry. Instead of strictly filtering out points belonging to specific semantic classes, the proposed approach weights the residuals of points belonging to semantic categories based on their expected geometric stability. This strategy enables informative but potentially unstable structures, to contribute to the registration process while mitigating the influence of dynamic objects. The experimental evaluation was conducted on the SemanticKITTI and RELLIS-3D datasets, which include urban, highway, rural, and off-road environments. The empirical results show that the proposed Semantic-weighted ICP improves pose estimation, especially in challenging off-road scenarios where conventional rigid features are scarce. Furthermore, the analysis reveals that the effectiveness of this weighting strategy is highly environment-dependent, influenced by the structural and semantic composition of the scene.
### Title:
          PatchScene: Patch-based Voxel Diffusion for Large-Scale Scene Completion
 - **Authors:** Qingdong Xu, Jiajun Zhu, Shilin Zhu, Xinjing He, Chao Lu, Huanran Wang, Jiyao Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose PatchScene, a novel diffusion-based framework for large-scale LiDAR scene completion. Unlike existing methods that rely on global latent representations or dense voxel grids, PatchScene adopts a patch-based voxel diffusion paradigm that explicitly generates fine-grained geometry within localized 3D regions. To ensure coherent reconstruction at both spatial and temporal scales, we introduce a confidence-guided spatio-temporal fusion mechanism that integrates overlapping patches and adjacent frames in a unified generative process. Furthermore, we design an Annular-Flow diffusion strategy that leverages the radial density pattern of LiDAR scans to progressively propagate high-fidelity information from near-range to far-range regions, enabling spatially unbounded scene completion. Extensive experiments on the SemanticKITTI benchmark demonstrate that PatchScene achieves state-of-the-art performance across all standard metrics, surpassing previous approaches in both geometric accuracy and temporal consistency. Remarkably, the model trained on 20 m LiDAR ranges generalizes effectively to 50 m scenes without retraining, highlighting its strong scalability and generalization capability for real-world autonomous driving applications.
### Title:
          Exploring Easy Boosts for Lidar Semantic Scene Completion
 - **Authors:** Tetiana Martyniuk, Jonathan Seele, Alexandre Boulch, Gilles Puy, Renaud Marlet, Raoul de Charette
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper investigates "free lunch" strategies to boost the performance of lidar semantic scene completion (SSC) without requiring complex architectural redesigns. We first demonstrate that endowing input point clouds with semantic pseudo-labels from off-the-shelf segmentors significantly improves the performance of existing architectures. By evaluating these models against an oracle, we establish that high-quality semantic priors are a primary driver of mIoU gains. Furthermore, we equip the input lidar scan with visibility information that distinguishes between empty and unknown spaces, which provides a secondary performance boost across the tested architectures. Using these simple enhancements, we observe that older models remain competitive with state-of-the-art systems, and can even outperform them. Our code is available at this https URL.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          KC-3DGS: Kurtosis-Constrained Gaussian Splatting for High-Fidelity View Synthesis
 - **Authors:** Vivekjyoti Banerjee, Abhay Yadav, Rama Chellappa, Aniket Roy
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian Splatting (3DGS) enables real-time novel view synthesis by representing scenes as collections of anisotropic Gaussians optimized via differentiable rasterization. However, standard pixel-space losses (L1, SSIM) constrain only aggregate reconstruction error, permitting the optimization to redistribute error across frequency scales. This leads to oversmoothing and structural artifacts, particularly in sparse-view settings where supervision is limited. We propose KC-3DGS, which augments 3DGS training with wavelet-domain supervision based on natural image statistics. Our method combines three components: (1) a multi-scale wavelet coefficient alignment loss that explicitly penalizes missing high-frequency detail, (2) a supervised kurtosis concentration loss that encourages rendered images to match the heavy-tailed frequency statistics of ground-truth images, and (3) a cross-band covariance penalty that promotes frequency specialization. We provide theoretical analysis showing that pixel-space losses admit a family of indistinguishable perturbations under wavelet redistribution, and that our joint objective excludes degenerate solutions. Experiments across MipNeRF360, Tanks&Temples, MVImgNet, DeepBlending, and WRIVA-ULTRRA demonstrate consistent improvements in perceptual quality. On the challenging WRIVA-ULTRRA outdoor dataset, KC-3DGS achieves a 9.48% improvement in DreamSim while also improving PSNR, SSIM, and LPIPS. In sparse-view settings with only 12 training images, our method improves PSNR by up to 0.5 dB on MipNeRF360 while maintaining perceptual quality. The approach integrates seamlessly into existing 3DGS pipelines as a plug-and-play regularization strategy.
## Keyword: mapping
### Title:
          Heterogeneous Mapping for Analog In-Memory Computing Accelerators: A Unified Workflow
 - **Authors:** Corey Lammie
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Analog In-Memory Computing (AIMC) accelerators execute matrix-vector multiplications directly within memory arrays, reducing data movement and improving DNN inference efficiency. Their limited effective precision motivates heterogeneous architectures that combine analog compute tiles with digital processing units. This letter classifies existing methods for partitioning DNN workloads across these resources by mapping granularity, optimization strategy, and model support, and distills them into a unified four-stage workflow. To demonstrate the workflow on a model class not yet addressed by existing methods, we apply its first two stages to GPT-2, producing the first AIMC-specific precision sensitivity profile for a decoder-only transformer. Sensitivity is dominated by 4 of 49 projections, with the first decoder block's attention output dominating by an order of magnitude. This suggests that projection-level mapping and selective digital execution of early-block and output-facing projections are important for reliable decoder-transformer deployment on AIMC hardware.
### Title:
          Qift: Shift-Friendly No-Zero W2 Post-Training Quantization for Rotated W2A4/KV4 LLM Inference
 - **Authors:** Chi-Wei Huang, Chia-Chi Tsai
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Two-bit weight quantization is attractive for memory-efficient LLM inference, but the standard W2 level set {-2,-1,0,+1} often collapses under aggressive W2A4/KV4 settings. We study the scalar level-set geometry of two-bit weights in a Hadamard-rotated quantization pipeline. Conventional asymmetric W2 substantially improves over the standard level set, indicating that W2A4 failure is not only a bit-width problem but also a reconstruction-level problem. Across all 224 linear modules in each of LLaMA-2-7B and LLaMA-3.1-8B, pretrained weights are already nearly zero-centered, while Hadamard rotation primarily Gaussianizes their standardized shape: excess kurtosis and Q-Q error drop by orders of magnitude. Based on this approximate zero-centered Gaussian-like source model, we propose Qift, a fixed no-zero W2 level set for rotated W2A4/KV4 inference. The main level set is {+/-0.5, +/-1.5}, equivalently {+/-1, +/-3} under a half-scale reparameterization; a power-of-two variant uses {+/-1, +/-4} for sign-and-shift decoded weight application. Qift redesigns the fixed two-bit code-to-level mapping and is training-free, learned-codebook-free, group-grid-free, and zero-point-free, retaining the standard per-channel scale. A scale-invariant ratio analysis identifies an effective inner/outer centroid ratio range of 0.25 to 0.33, explaining why mirror no-zero (MNZ), Lloyd, NF2, and PoT-MNZ perform well while {+/-1, +/-2} does not. On both models, the no-zero level sets consistently improve pure W2A4 perplexity, L-layer mixed W2/W4 perplexity, downstream accuracy, and GPTQ residual behavior over the standard W2 level set. At L=16 mixed precision, they substantially narrow the gap to W3A4 while keeping half of the transformer layers at two-bit precision, giving a simple, source-aware, and deployment-friendly alternative to more complex learned W2 codebooks.
### Title:
          FAF-CD: Frequency-Aware Fusion for Change Detection under Imperfect Multimodal Remote Sensing
 - **Authors:** Yufan Wang, Sokratis Makrogiannis, Chandra Kambhamettu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Remote sensing change detection for real-world monitoring often relies on imperfect heterogeneous observations, where pre- and post-event images may be asynchronous, cross-sensor, or affected by illumination, seasonal, and modality shifts. This setting is especially challenging for EO-SAR disaster mapping, where nuisance variation can resemble structural damage. We propose FAF-CD, a frequency-aware hybrid framework with a DINOv3-pretrained ConvNeXt encoder and a linear-complexity VMamba-based decoder. Its rectification-aware tri-branch fusion module combines deformable spatial alignment with Fourier and Haar-wavelet comparisons, using adaptive gating to aggregate complementary cues across scales. On BRIGHT validation, a matched heterogeneous EO-SAR adaptation improves clean and perturbed tc-mIoU/tc-mAP over NeXt2Former-CD. FAF-CD also generalizes to binary optical CD, achieving 0.924 cF1 on LEVIR-CD and 0.955 cF1 on WHU-CD, and obtains the best average perturbed cIoU/cF1 on both binary datasets among M-CD and NeXt2Former-CD under pseudo-change-aligned stress tests. It further reduces cost by approximately 24 GFLOPs relative to NeXt2Former-CD while maintaining or improving accuracy.
### Title:
          Private Embedding Lookup with Encrypted Compact Queries under Fully Homomorphic Encryption
 - **Authors:** Daehyun Jang, Jaehee Kang, Hanee Rhee, Jung Hee Cheon
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many NLP or recommendation models begin by mapping discrete client inputs to embedding vectors. Since inputs can reveal sensitive information, the embedding step must be protected in privacy-preserving inference. Fully Homomorphic Encryption (FHE) enables inference over encrypted client data, but turns embedding lookup from simple table access into homomorphic computation. To keep the embedding table server-side and avoid transmitting encrypted embedding vectors from the client, we focus on server-side lookup: the client sends only a small encrypted index. Prior ICML 2024 work first builds a one-hot vector from the encrypted index before multiplying with the embedding table, and this one-hot generation is the dominant cost. One-hot-based methods are expensive in FHE: they construct a p-dimensional selection vector via an equality test for each coordinate, requiring $O(p \log p)$ total homomorphic operations. Our key observation is that private embedding lookup only requires a linearly independent representation of the encrypted index, not the one-hot basis itself. Building on it, we propose Independent Vector Evaluation (IVE). Instead of constructing a one-hot vector, IVE evaluates a linearly independent vector built from successive powers of a single encrypted value, reducing vector-generation cost to $O(p)$. It then recovers the same embedding vector via a precomputed change of basis, instantiated with an orthogonal Discrete Cosine Transform to mitigate error amplification. Our implementation shows IVE improves amortized lookup time by up to 78.4x over prior method. We further evaluate its impact on end-to-end encrypted FastText inference, where embedding lookup is a major cost in the shallow model. On Enron-Spam dataset, replacing one-hot generation with IVE reduces the share of vector generation in encrypted inference time from 99.6% to 66.3%.
### Title:
          Multi-Agent Framework Leveraging Knowledge Graphs for Virtual Commissioning Models
 - **Authors:** Max Diekmann, Jonas Nitzler, Jan Fischer, Hans-Jürgen Pfisterer, Dirk Hartmann
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Virtual commissioning models (VCMs) of discrete manufacturing systems are used to validate automation behavior before physical deployment, but creating and maintaining them remains labor-intensive. Relevant engineering information is distributed across programmable logic controller (PLC) engineering projects, such as Siemens TIA Portal, and kinematic simulation models, such as Siemens NX Mechatronics Concept Designer (NX MCD), where it is stored in incompatible, tool-specific data structures. In practice, IEC 61131-3-based PLC programs and variables are engineered separately from rigid-body and kinematic simulation objects such as parts, joints, sensors, and actuators. As a result, understanding system behavior, generating simulation components, and mapping PLC variables to corresponding simulation objects require cross-domain expertise and remain largely manual. This paper presents a knowledge-graph-grounded multi-agent framework for semi-automated VCM development. A deterministic setup process extracts structured data from Siemens TIA Portal and Siemens NX MCD and transforms both sources into graph-based representations within a shared graph database. The framework uses a hierarchical multi-agent architecture to support three task classes in early-stage VCM development: system understanding, simulation component generation, and cross-domain signal mapping. It provides grounded natural-language access to engineering knowledge, template-guided generation of executable NX Open journal scripts, and ranked mapping suggestions between PLC variables and NX MCD simulation objects. Evaluation on a laboratory-scale discrete manufacturing system shows that the approach reduces manual cross-domain interpretation effort and makes recurring VCM engineering tasks more actionable.
### Title:
          Beyond "To whom it may concern": Tailoring Machine Translation to Audience and Intent
 - **Authors:** Raphael Merx, Ekaterina Vylomova, Trevor Cohn
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Translation quality depends on purpose: the same source text demands different translations depending on audience, tone, and communicative intent. Yet MT models and metrics treat translation as a fixed mapping from source to target. LLMs enable users to explicitly specify purpose alongside source text, yet this capability has not been evaluated at scale. We introduce a systematic evaluation of purpose-driven MT across 50 languages, 5 model sizes and 8 text domains. We find that (1) explicit instructions substantially improve translation adaptedness, with larger gains on informal domains (conversation, social media), for larger model sizes and for higher-resource languages; (2) instructions outperform semantically-matched few-shot examples and paragraph-level context; (3) traditional MT metrics fail to capture adaptation quality, often penalizing adapted translations; (4) when curated instructions are unavailable, models can self-generate them from surrounding document context, closing up to 80% of the adaptedness gap to curated instructions. Our results establish that purpose-adapted MT is a viable and measurable capability of LLMs, while highlighting the need for purpose-aware metrics.
### Title:
          Let There Be Light: Reflection, Refraction and Scattering for Neural Operators
 - **Authors:** Keke Wu, Yixuan Zhang, Jingrun Chen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural operators learn mappings between infinite-dimensional function spaces and provide a data-driven surrogate modeling paradigm for parametric partial differential equations (PDEs). Existing architectures typically obtain expressivity by parameterizing integral kernels in prescribed transform domains or by applying attention-like interactions over discretized spatial points. While these approaches have achieved substantial progress, they often face a persistent trade-off among physical interpretability, nonlocal spatial communication, mesh scalability, and computational cost. We propose a Light-inspired neural operator(LiNO), an operator-learning architecture whose latent evolution is decomposed into three mechanisms motivated by elementary light transport: reflection, refraction, and scattering. Reflection and refraction act as adaptive pointwise transformations in latent feature space, enabling local feature reorientation and anisotropic modulation, whereas scattering performs input-dependent nonlocal propagation over the physical domain. We first formulate scattering as a normalized pairwise kernel with relative positional bias, and then develop an efficient scattering variant that replaces explicit pairwise interactions with positive-feature global propagation and a local diffusion branch, reducing the dominant spatial complexity from quadratic to linear. This yields a structured neural operator that separates local feature modulation from global spatial communication while retaining a modular and interpretable latent evolution.
### Title:
          GROSS: German Rail Open-Source SUMO Scenario
 - **Authors:** Juri Penell, Damian Dailisan
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Microscopic simulation enables reproducible evaluation in intelligent transportation systems, yet most open SUMO scenarios and toolchains remain road-traffic centric, leaving rail underrepresented despite its importance for public transport and its sensitivity to network-wide disruptions. We present the German Rail Open-Source Scenario (GROSS), an open pipeline that combines OpenStreetMap railway infrastructure with GTFS schedules to generate nation-scale rail scenarios for SUMO (Simulation of Urban MObility). Existing conversions often rely on geometry-only stop-to-track matching and inconsistent platform/track assignments, which can create routing anomalies and unstable simulations dominated by teleportation artefacts. GROSS addresses this with topology-aware stop mapping via a hierarchical station model, followed by station-level routing with validation and targeted repair. Across multiple German regions, GROSS reduces average teleportations per vehicle by a factor of 1.7--76.8$\times$, shortens delays compared to the vanilla SUMO pipeline, and it enables end-to-end generation of a Germany-wide scenario with 35\,925 trips for comparisons with operator-reported delay statistics. While the remaining long delays highlight limitations in available timetable metadata and rail dispatch modeling, GROSS lowers the barrier to building scalable, fully open rail simulations and to studying delay propagation at country scale.
### Title:
          Tailoring Strictly Proper Scoring Rules for Downstream Tasks: An Application to Causal Inference
 - **Authors:** Roman Plaud, Alexandre Perez-Lebel, Antoine Saillenfest, Thomas Bonald, Marine Le Morvan, Gaël Varoquaux, Matthieu Labeau
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Probabilistic models are typically trained using task-agnostic objectives like log-loss, which can lead to significant errors in downstream estimation. This disconnect is especially critical in Inverse Probability Weighting (IPW) for causal inference, where propensity score errors near $0$ and $1$ often lead to high bias and variance. We propose a principled framework for deriving task-specific strictly proper scoring rules by matching the local curvature of the downstream error metric. We apply this to the Average Treatment Effect (ATE) estimation, deriving a closed-form loss and its corresponding canonical probability mapping that can be readily integrated with any model like a neural network or a gradient boosting algorithm. Extensive evaluations on causal inference benchmarks demonstrate that our tailored objective consistently outperforms standard likelihood-based and covariate-balancing approaches.
### Title:
          Beyond Semantics: Modeling Factual and Affective Perceptual Experiences from Vision-Language Data
 - **Authors:** Youssef Mohamed, Kenneth Ward Church, Mohamed Elhoseiny
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present P-Topics (Perception Topics) modeling, a novel problem for understanding how images are perceived affectively and across cultures. The goal is to (1) discover and model the different perception experiences in a dataset of images and captions, where each experience is defined by an objective factual and a subjective affective aspect, and (2) associate images to their relevant perception experiences. We introduce **PercepT** (**Percep**tion topic **T**ransformer), a two-stage architecture that tackles P-Topics modeling. In the formation stage, percepT discovers *P-Topics* as visual-textual clusters using an unsupervised training objective, and dynamically selects the number of clusters to match the perceptual richness of the dataset. In the mapping stage, it learns *P-Topic mapping functions* via attention pooling to associate images to their respective clusters. On ArtELingo, PercepT achieves a silhouette score of **0.97** compared to **0.37** from the closest baseline reflecting better perceptual clusters. PercepT also achieves an AUC score of **0.94** compared to **0.77** showing better mapping to perceptual clusters. Human evaluation confirms that PercepT captures semantically meaningful perception experiences and significantly outperforms existing methods. Our implementation will be made public.
### Title:
          Rain: RDMA-assisted In-Network Scheduling for Microsecond-scale Workloads
 - **Authors:** Zhihuang Ma, Xingming Cui, Xiaoliang Chen, Zuqing Zhu
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern data center applications increasingly require microsecond-scale service time with strict tail latency requirements, which can hardly be realized with existing in-network task schedulers due to their inherent limitations. Specifically, software-based schedulers struggle to balance throughput and latency, while switch-based designs either lack global coordination, rely on packet recirculation heavily, or only offer limited support for large tasks. In light of these restrictions of the state-of-the-arts (SOTAs), we, in this work, propose Rain, an RDMA-assisted in-network scheduler built atop programmable switches that maintains centralized queues while bounding worker-local queues. Rain introduces a bidirectional on-switch queuing mechanism to buffer and match tasks and worker-issued tokens directly in the switch, avoiding worker-side polling and approximating the optimal behavior of join-bounded-shortest-queue without global aggregation. A switch-driven RDMA engine pre-writes arbitrarily large tasks via one-sided WRITE multicasts, keeping only compact metadata on the switch. Slice-aware scheduling further localizes decisions to more homogeneous queues, reducing dispersion-induced head-of-line blocking. Moreover, our study reveals that real-world systems can diverge from theoretical predictions: shallower worker queues do not always improve tail latency. Leveraging this insight, Rain incorporates an adaptive scheduling strategy to optimize worker queue depths and worker-to-slice mappings at runtime. Evaluations with the real-world application RocksDB show that Rain achieves 1.75x higher throughput than the best-performing SOTA while satisfying the same tail latency requirement.
### Title:
          Physics-guided correction for operator learning under model misspecification
 - **Authors:** Lei Ma, Nicolas Boullé, Yu-Sen Yang, Hao Wu, Ling Guo
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Physics-informed operator learning provides an efficient framework for approximating solution operators of partial differential equations by combining observational data with governing physical laws. However, most existing methods implicitly assume that the prescribed governing equation is accurate. This assumption may fail in practical applications, where model simplifications, missing physical effects, parameter drift, or incomplete constitutive relations can lead to model misspecification. In this work, we propose a physics-guided operator correction framework for learning solution operators under misspecified governing equations. At the operator level, the target mapping is decomposed into a prior operator induced by an approximate physical model and a learnable correction operator that accounts for the remaining discrepancy. Although the formulation is architecture independent, we realize it using a serial DeepONet architecture, where the first DeepONet provides a prior prediction and the second DeepONet learns an additive correction conditioned on both the input function and the prior prediction. The learned correction is incorporated into the physics residual and trained together with data-consistency constraints, allowing the model to retain useful physical structure while adapting to inaccurate governing equations. Numerical experiments on diffusion-reaction, Burgers, cavity flow, and hyperelastic problems show that the proposed method substantially reduces errors induced by misspecified physics. Additional tests under sparse and noisy observations further demonstrate the robustness of the framework and its ability to provide informative uncertainty estimates through deep ensembles.
### Title:
          Testing LLM Arithmetic Reasoning Generalization with Automatic Numeric-Remapping Attacks
 - **Authors:** Malia Barker, Bishal Lakha, Edoardo Serra, Francesco Gullo
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models achieve strong performance on arithmetic reasoning benchmarks, and one common response to arithmetic brittleness is to delegate computation to code. Yet models are still often used in settings where they must reason directly from natural language, and trustworthy models should solve small-number arithmetic word problems without external tools. Prior work shows that LLMs are sensitive to numerical variation: a model may solve an original problem but fail on structurally similar variants requiring the same reasoning procedure with different numbers. We ask whether this fragility persists under a stricter setting involving small, schema-preserving numeric changes that retain the original reasoning program and avoid large-number stress tests. We introduce an automatic algorithm for generating numeric-remapping attacks on arithmetic word problems. Unlike template-based perturbation methods requiring manual schemas or constraints, our approach derives problem-specific symbolic representations, generates constrained numeric remappings, recomputes gold answers, and realizes transformed questions through deterministic edits guided by LLM-generated edit plans. Stage-wise validation and a high-confidence audit retain reliable attacks, making the pipeline scalable with limited human intervention. We evaluate DeepSeek-R1 (70B), Gemma4 (31B), and GPT-OSS (120B) on GSM8K, MAWPS, and MultiArith. On GSM8K, completed runs show conditional accuracy drops of 12.16 to 25.82 percentage points. MAWPS and MultiArith are far more stable, with most attacked accuracies near or above 98%. These results show that numeric-remapping robustness depends strongly on dataset structure: GSM8K remains sensitive even when reasoning programs are preserved and answers are recomputed, while shorter, more regular datasets are more robust.
### Title:
          Beyond Single Solution: Multi-Hypothesis Collaborative Deep Unfolding Network for Image Compressive Sensing
 - **Authors:** Wenxue Cui, Hualin Li, Yuhang Qin, Yifu Xu, Xiaopeng Fan, Debin Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent deep unfolding networks (DUNs) have advanced Compressive Sensing (CS) by effectively integrating iterative optimization with deep learning architectures. However, most CS approaches predominantly confine their inference to a single solution space, neglecting the inherent ill-posedness of CS problems that intrinsically permits multiple plausible candidate hypotheses. In this paper, a novel Multi-Hypothesis Collaborative Deep Unfolding CS Network (MHC-DUN) is proposed, which explicitly models and leverages multiple hypotheses by jointly optimizing across diverse solution spaces. Specifically, following the Proximal Gradient Descent algorithm, MHC-DUN jointly performs gradient descent and proximal mapping within this multi-hypothesis paradigm. i) For gradient descent, a well-designed AlphaNet is introduced to dynamically predict spatially varying step sizes for all hypotheses, enabling collaborative gradient updates across multiple solutions. ii) For proximal operator, a sophisticated multi-hypothesis collaborative proximal mapping module is designed, which leverages both intra-hypothesis and inter-hypothesis correlation priors to jointly refine multiple solutions. To enable end-to-end training, a novel composite loss function is designed, which balances measurement fidelity, hypothesis diversity, and reconstruction accuracy, encouraging exploration of complementary solutions while maintaining reconstruction fidelity. Experimental results reveal that the proposed CS method outperforms existing CS networks.
### Title:
          From Well-Posed Inversion to Learning Design: Physics- Informed Neural Estimation for Autonomic Regulation
 - **Authors:** Sara Nour Sadoun, Giuseppe Alessio D'Inverno, Francois Cottin, Arnaud Boutin, Taous-Meriem Laleg-Kirati
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning-based and physics-informed methods are increasingly used for inverse estimation in controlled nonlinear dynamical systems. However, in many such approaches, the theoretic requirements that make unknown-input reconstruction meaningful, namely well-posedness in the sense of Hadamard, are often disregarded or weakly addressed through generic regularization terms with no explicit guarantees. In this work, we adopt a complementary viewpoint in which these control-theoretic and structural conditions inform the estimator design and constrain its training. We thus develop a physics-informed input-state neural estimator for joint unknown-input and state estimation in nonlinear controlled systems with partial measurements. In the present work, this general framework is instantiated on a model of autonomic cardiac regulation, provides a concrete study case. The estimator is formulated as an inverse neural map conditioned on time and measured outputs, and is trained under data fidelity and dynamical consistency constraints. To ensure it complies with the same structural requirements imposed in robust estimation, we derive left-invertibility conditions by differential-algebraic elimination and embed the resulting constraints directly into the training objective. We further analyze a priori the stability of the inverse mapping to output perturbations and derive a conservative Lipschitz bound that guides the tuning of cost functional hyper-parameters. The framework is evaluated on simulated data, where ground truth data is available, and on two distinct datasets of real cardiovascular recordings. The results show that incorporating control-theoretic solvability constraints into physics-informed learning improves the reliability of inverse inference beyond forward consistency alone.
### Title:
          An AutomationML Domain Library for the Formalized Process Description
 - **Authors:** Hamied Nabizada, Rainer Drath, Felix Gehlhoff, Alexander Fay
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Databases (cs.DB)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Formalized Process Description (FPD) according to VDI/VDE 3682 provides a standardized graphical notation for describing processes across engineering domains but lacks a standardized, tool-independent data format for machine-readable model exchange. This paper presents an AutomationML (AML) domain library that formalizes the complete set of FPD language elements, their attributes, connection semantics, and graphical representation information as class libraries based on the Computer Aided Engineering Exchange (CAEX) 3.0 metamodel. The library comprises five interrelated parts: a RoleClassLib defining the semantic roles, an InterfaceClassLib for connection types, two AttributeTypeLibs for the information model and diagram interchange, and a SystemUnitClassLib providing instantiation templates. Key design decisions regarding inheritance, diagram structure, hierarchical decomposition, and the representation of graphical information are discussed along with the alternatives that were considered. A bidirectional mapping tool demonstrates the library's applicability by converting between a web-based FPD modeler and AML. The library is proposed as a candidate for Part 3 of VDI/VDE 3682. It is available together with an example and a feedback function for community input ahead of standardization at this https URL.
### Title:
          Learning finite viscoelasticity with DAVIS: A supervised framework for generalized standard materials
 - **Authors:** Simon Wiesheier, Paul Steinmann, Miguel Angel Moreno-Mateos
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work revisits the recently proposed data-adaptive viscoelasticity (DAVIS) framework, a spline-based formulation of finite viscoelasticity within the generalized standard materials setting. DAVIS enables a data-driven representation of equilibrium and non-equilibrium constitutive functions while retaining thermodynamic consistency and supporting parameter identification via finite element model updating. The present contribution focuses on improving the robustness and identifiability of non-equilibrium branches in generalized Maxwell-type models. To this end, two extensions of the original formulation are introduced. First, the spline representation is reformulated in terms of curvature-based variables, which is especially convenient to enforce monotonicity and convexity constraints by construction through a smooth parameter mapping. Second, the adaptation of interpolation domains is decoupled from the inner parameter identification by means of a staggered, block-alternating strategy: spline coefficients are optimized for fixed domain endpoints, while the endpoints are updated in an outer loop based on smooth statistics of sampled invariants. This separation alleviates an inherent scaling ambiguity between interpolation domains and spline coefficients that can impair conditioning in viscoelastic inverse problems. The underlying constitutive model remains the finite strain viscoelasticity framework of Reese and Govindjee. The proposed identification strategy is assessed for homogeneous uniaxial loading-unloading tests, which facilitates the study of identifiability and robustness of non-equilibrium branches.
### Title:
          OVO-S-Bench: A Hierarchical Benchmark for Streaming Spatial Intelligence in Multimodal LLMs
 - **Authors:** Yifei Li, Pengyiang Liu, Yuhang Zang, Zhongyue Shi, Qi Fu, Hongye Hao, Jiwen Lu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal agents in robotics, AR, and autonomous driving must reason about places and layouts from continuous egocentric streams, often using evidence outside the current view. Existing benchmarks either evaluate offline over full videos or target events rather than spatial structure. We introduce OVO-S-Bench, a fully human-annotated benchmark for streaming spatial intelligence, comprising 1,680 questions over 348 source videos. Annotation involves 12 trained annotators, each also serving as a blind cross-reviewer, across roughly 804 person-hours of multi-round quality assurance. Each question carries a query timestamp and an evidence interval, and at evaluation, the model sees only the prefix preceding the query. Questions span four levels of increasing abstraction: instantaneous egocentric perception, spatiotemporal context tracking, spatial simulation and reasoning, and allocentric mapping. Across 38 proprietary and open-source MLLMs, Gemini-3.1-Pro trails human experts by 27 points, 59.2 vs. 86.6, with allocentric mapping as the dominant bottleneck. Notably, streaming and spatially fine-tuned MLLMs underperform their own backbones. We further find that chain-of-thought reasoning amplifies spatial errors when ungrounded in the stream. By exposing these limitations, OVO-S-Bench establishes a demanding testbed for next-generation streaming spatial MLLMs.
### Title:
          Revisiting $O(n \log \log n)$ chaining for anchored edit distance
 - **Authors:** Nicola Rizzo, Ragnar Groot Koerkamp
 - **Subjects:** Subjects:
Data Structures and Algorithms (cs.DS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Colinear chaining is a classical heuristic for sequence alignment: it enables scalable genome comparison and is a main component of many state-of-the-art read mappers based on seed-chain-extend. The earliest $O(n \log \log n)$ time algorithms by Eppstein et al. (J. ACM, 1992) chained $n$ fragments between two sequences $T$ and $Q$ while minimizing a gap cost based on the diagonal distance $\Delta_{\text{diag}}$ between consecutive fragments. They also forbid fragment overlaps, which are essential in current chaining formulations: in long-read mapping, overlaps improve sensitivity and avoid restrictions on the fragment class considered. Jain, Gibney, and Thankachan (J. Comput. Biol. 2022) recently combined a $\Delta_{\text{diag}} = |\Delta_T -\Delta_Q|$ overlap cost with the classic $L_\infty = \max(\Delta_T , \Delta_Q)$ gap cost that takes the maximum between the horizontal and vertical gap between the fragments and they proved that chaining under this cost model is equivalent to the anchored edit distance. We improve the existing $O(n \log^3 n)$-time algorithm for anchored edit distance to $O(n \log \log n)$ time in $O(n)$ space, by combining the gap-cost computation of Chao and Miller (Algorithmica, 1995) with the overlap-cost computation of Baker and Giancarlo (ESA, 1998). By developing llchain, a simpler $O(n \log n)$-time implementation of our method, we show how chaining algorithms that might have been recently overlooked by the bioinformatics community scale competitively to millions of fragments and large genomes. On average, llchain is $10\times$ faster than other methods on instances with $3\,000\,000$ anchors, and over $3\times$ faster on MEMs between HiFi reads and a reference human genome.
## Keyword: localization
### Title:
          CAD-to-CT Registration of Cylindrical Objects via Ellipse-Based Axis Estimation
 - **Authors:** Aleksander Ogonowski, Mikołaj Mrozowski, Daniel Więcek, Arkadiusz Ćwiek, Konrad Klimaszewski, Rafał Możdżonek, Adam Padee, Lech Raczyński, Piotr Wasiuk, Wojciech Wiślicki, Michał Matusiak, Sławomir Wronka
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate registration of CAD models to CT scans is essential for establishing ground truth geometry in volumetric imaging. Obtaining reliable object masks is of growing importance in machine learning settings; as recent architectures grow more capable, huge datasets are required to fully utilise their capabilities. Traditional intensity-based methods fail when CT grayscale values lack calibration references, while point-based algorithms (e.g., ICP, RANSAC) require feature correspondence unavailable between idealized CAD geometry and noisy volumetric CT data. We propose a two-stage geometric registration method for cylindrical objects (ionization chambers) that takes advantage of the distinctive geometric features of the objects. First, we estimate the 3D rotation axis by detecting elliptical cross-sections across CT slices, fitting ellipses to edge-detected contours, and performing PCA on the fitted ellipse centers after RANSAC outlier removal. Second, we voxelize the CAD model, orient it along the detected axis, and maximize volumetric overlap with the CT scan through translational adjustment. This approach achieves robust registration with tilt and orientation errors below $0.1^\circ$ without intensity calibration or feature matching. Once registered, the aligned CAD model provides ground truth geometry for applications including machine learning-based object localization and automated analysis in industrial CT workflows.
### Title:
          The Road Ahead in Autonomous Driving: The KITScenes Multimodal Dataset
 - **Authors:** Richard Schwarzkopf, Fabian Immel, Alexander Blumberg, Jonas Merkert, Nils Rack, Kaiwen Wang, Fabian Konstantinidis, Julian Truetsch, Carlos Fernandez, Annika Bätz, Kevin Rösch, Marlon Steiner, Willi Poh, Yinzhe Shen, Royden Wagner, Felix Hauser, Dominik Strutz, Jaime Villa, Gleb Stepanov, Holger Caesar, Ömer Şahin Taş, Frank Bieder, Jan-Hendrik Pauls, Christoph Stiller
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing autonomous driving datasets have enabled major progress, but fall short in sensor fidelity, map completeness, or geographic diversity. We present KITScenes Multimodal, a European dataset built around high-fidelity sensors and maps. Our fully synchronized sensor suite combines high-resolution global-shutter cameras, long-range lidar beyond 400m, 4D imaging radar, and redundant GNSS/INS localization. Our HD maps are, to our knowledge, the most complete of any sensor dataset, validated through autonomous driving trials on open-source software. For the first time in a public dataset, all driving-relevant traffic elements, such as traffic lights, are mapped in 3D to a reprojection-accurate level with full topological connectivity. Recorded in cities with irregular street layouts and mixed traffic modes, our dataset complements existing datasets by broadening the available geographic diversity. We also introduce four benchmarks, each advancing spatial learning for embodied AI: online HD map construction, long-range depth estimation, novel view synthesis, and end-to-end driving. Project page: this https URL
### Title:
          MARIO: Motion-Augmented Real-Time Multi-Sensor Inertial Odometry
 - **Authors:** Yiquan Li, Taeyoung Yeon, Chenfeng Gao, Vasco Xu, Xuanyou Liu, Karan Ahuja
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Inertial odometry (IO) using only Inertial Measurement Units (IMUs) provides a lightweight solution for human motion tracking in augmented reality (AR) and wearable devices. Recent learning-based IO methods have improved the generalizability of inertial localization through large-scale pretraining on human motion datasets. However, these approaches remain prone to drift and noise because they do not explicitly capture human motion dynamics, especially on daily activity datasets such as Nymeria. In this work, we propose to ground inertial odometry in human kinematics through a learned IMU-inferred pose prior, which promotes physically consistent motion constraints. We integrate this pose prior into existing IO architectures and reduce positional drift by up to 36% on the challenging Nymeria dataset, which is 5x larger than datasets used in prior work. We further improve long-term performance with a sensor-fusion framework that incorporates auxiliary signals from lightweight sensors already available on commercial AR glasses, including magnetometers, barometers, and secondary IMUs. With this fusion strategy, positional drift is reduced by up to 42%, improving robustness and generalization across diverse motion conditions. Together, our results introduce a new paradigm for inertial and lightweight odometry by unifying human motion kinematics with multimodal sensing, setting a new benchmark for accurate and robust camera-less human tracking. Our website is available at this https URL.
### Title:
          $A^2$: Smaller Self-Supervised ViTs Localize Better than Larger Ones
 - **Authors:** Sreehari Rammohan, Huy Ha, Carl Vondrick
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust visual classification often depends on localizing the main foreground objects in an image while ignoring contextual distractors. Surprisingly, we find that the attention maps of smaller self-supervised ViTs localize foreground objects better than those of larger ViTs. However, we still need large ViTs, because they extract richer representations from each patch. To get the best of both worlds, good localization and rich representations, we propose $A^2$, a simple method that leverages this inverse scaling finding by decoupling where to look (a small attention model) from what to extract (a large embedding model): we crop around the attention peaks of a small model and embed the crops with a larger model. $A^2$ uses entirely pretrained features, requires no group labels, and does not require per-dataset attention or backbone training. Across 5 benchmarks, $A^2$ is competitive with backbone-matched loss-level methods like DFR, and outperforms end-to-end attention training under stronger distribution shifts.
### Title:
          Evidence-Aware Protein Complex Detection: Methods, Benchmarks, and Reproducibility Challenges
 - **Authors:** Sima Soltani, Mehrdad Jalali, Yahya Forghani, Reza Sheybani
 - **Subjects:** Subjects:
Social and Information Networks (cs.SI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Protein complexes are central units of cellular organization, yet their identification from protein-protein interaction (PPI) networks remains difficult because interactome maps are noisy, incomplete, context dependent, and unevenly annotated. This focused methodological review examines evidence-aware approaches that combine PPI topology with Gene Ontology (GO) annotations, expression profiles, subcellular localization, sequence or domain evidence, temporal information, and representation learning, with emphasis on post-2018 methods and selected historical baselines. The central synthesis is that transparent evidence-aware graph methods currently offer the strongest tradeoff between biological plausibility and reproducibility, while deep, hypergraph, and dynamic heterogeneous models expand biological realism but require stronger benchmark control. The central bottleneck is no longer only the lack of algorithms, but the lack of harmonized, overlap-aware, and reproducible evaluation protocols. We therefore recommend unified benchmark versions, explicit GO-circularity controls, overlap-aware metrics, uncertainty estimates, and executable software packages over isolated source-specific F-measure gains.
### Title:
          GLINT: Sparsely Gated Vision-Language Alignment for Fine-Grained Radiology Representations
 - **Authors:** Jonggwon Park, Seongeun Lee, Junhyun Park, Hannah Yun, Hyunwoong Kim, Sohyun Jeong, Hyewon Kang, Byungmu Yoon, Kyoyun Choi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language models (VLMs) for radiology have emerged as a scalable paradigm by leveraging image-report pairs naturally produced in clinical workflows. However, this pairing reveals a mismatch in scale: each finding occupies only a small region of the image, yet supervision is provided only at the global image-report level. This poses a central challenge: prior approaches spread weight densely across all patches rather than concentrating on the sparse subset relevant to a given query. To address this, we present GLINT (Gated Language-Image alignmeNT), a framework that explicitly models this sparse correspondence. On the alignment side, we introduce Sparsely Gated Alignment, a novel architecture in which a sigmoid gate over a separate gate embedding space activates only the patches relevant to each textual query, enforcing explicit sparsity. On the representation side, we add Dense Feature Regularization, which anchors the trainable encoder's intermediate features to a frozen self-supervised learning (SSL) teacher, preserving the fine-grained patch features that the gate relies on. The same recipe applies to both 2D chest X-ray (CXR) and 3D chest computed tomography (CT), built with DINOv3 and V-JEPA 2.1, respectively. GLINT enables zero-shot classification, grounding, and segmentation from free-text queries, and to our knowledge is the first to demonstrate zero-shot segmentation on 3D CT volumes without mask supervision. Notably, the most pronounced gains arise on zero-shot grounding and segmentation, where sparse, query-specific localization is required, consistent with our design intent. In downstream evaluation, GLINT outperforms both SSL encoders and medical VLMs on classification, report generation, and segmentation.
### Title:
          Wheel-Mounted/GNSS Fusion with AI-Aided Position Updates
 - **Authors:** Gal Versano, Itzik Klein
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate and robust localization remains a fundamental challenge for autonomous ground vehicles. In this work, we propose a hybrid neural inertial navigation framework that integrates a wheel-mounted inertial sensors, enforced periodic trajectories, and a simple, efficient neural network capable of regressing vehicle displacement with GNSS position updates in an error-state extended Kalman filter. The periodic trajectories increase the inertial signal-to-noise ratio, allowing the network to use only inertial readings to estimate displacement. The approach is validated through real-world experiments using multiple wheel-mounted inertial sensors. Experimental results demonstrate that the proposed method achieves a significant improvement in positioning accuracy, reducing the position root mean squared error by approximately 46 % compared to standard wheel-mounted inertial sensor fusion with GNSS updates.
### Title:
          CAPER: Clause-Aligned Process Supervision for Text-to-SQL
 - **Authors:** Lujie Ban, Jiasheng Shi, Jinyang Li, Xiaolin Han, Tsz Nam Chan, Chenhao Ma
 - **Subjects:** Subjects:
Databases (cs.DB); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-to-SQL systems are typically evaluated by query-level execution correctness, but this terminal signal provides little guidance about which intermediate SQL decision caused success or failure. Token-level dense supervision is also ill-suited: SQL tokens do not align with complete semantic decisions, can penalize execution-equivalent queries, and are difficult to label reliably at scale. We therefore propose CAPER, which automatically derives clause-level supervision via counterfactual intervention on the SQL abstract syntax tree, enabling root-cause error localization for reward modeling; the resulting data is used to train CAPER-9B, a lightweight Clause-PRM that provides clause-boundary feedback for policy optimization and candidate verification. Experiments on BIRD and Spider show that clause-aligned supervision not only improves execution accuracy, achieving up to a 15.3% relative EX improvement over GPT-5.4, but also strengthens failure-localization capability, reaching 84.53% accuracy and 90.60% MRR on held-out failures. Our project page is at this https URL.
### Title:
          Autonomous Navigation System for Library Service Robot Based on Unitree Go2 Edu
 - **Authors:** Aoduo Li, Haoran Lv, Bingquan Ou, Jianfeng Li, Yingdong Li, Zimeng Li
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Libraries require autonomous robots to move quietly through narrow aisles while remaining safe around readers, chairs, bags, and carts. This paper presents a ROS 2 navigation system for a Unitree Go2 Edu quadruped equipped with a 4D LiDAR, a front depth camera, and an IMU. Rather than assuming the library is rough terrain, we target the practical mobility discontinuities of real deployments, including floor transitions, temporary clutter, and partially blocked passages where low-clearance wheeled platforms are less tolerant. RTAB-Map is used for visual-LiDAR SLAM, AMCL and EKF-based sensor fusion provide localization, and a Nav2 stack with A* and DWA supports planning and local avoidance. In a real library, the system achieves 100%, 96%, and 88% success rates in static, low-density dynamic, and high-density dynamic scenes, while map validation against surveyed control distances yields a mean metric error of 3.7 cm.
### Title:
          Neural Change Prediction: Relating Software Changes to Their Effects and Vice Versa
 - **Authors:** Laura Plein, Souhila Zidane, Jordan Samhi, Andreas Zeller
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Much of software development revolves around understanding the relationship between software changes and their effects. If we could learn and predict those relationships, such predictions could benefit several areas of software engineering. While recent advances in artificial intelligence have shown great promise in software engineering tasks, predicting the semantics of code without executing it remains a big challenge. In this paper, we present Neural Change Prediction, a novel and fundamental technique to learn and predict associations between software changes and their dynamic effects on program behavior. Specifically, for a given program and test inputs, we automatically apply numerous mutations to the code and observe how these changes alter the program's output. From these (changes to software, changes in behavior)-pairs, we create models that: (1) for a desired change in behavior, predict where and how the code should be changed (feature localization, software evolution, and software repair); and (2) for a given code change, predict how this code change affects the output (effect prediction). We have conducted a detailed case study on CSS configuration files and an evaluation on Python programs to demonstrate the generality and wide applicability of Neural Change Prediction. While Neural Change Prediction requires numerous mutations (and thus numerous executions of the program under test), Neural Change Prediction is fully automatic and does not require any prior knowledge of the code or its semantics, making it applicable to any software artifact that can be executed and whose output can be observed.
### Title:
          SAMatcher: Co-Visibility Modeling with Segment Anything for Robust Feature Matching
 - **Authors:** Xu Pan, Qiyuan Ma, Mingyue Dong, He Chen, Wei Ji, Xianwei Zheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable correspondence estimation is a fundamental problem in image processing, underpinning applications such as Structure from Motion, visual localization, and image registration. Existing learning-based methods have significantly improved local feature representations, yet most still operate at the pixel or patch level and lack explicit modeling of regions that are jointly visible across views. We propose SAMatcher, a feature matching framework that formulates correspondence estimation through co-visibility modeling. Instead of directly matching local features, SAMatcher first predicts co-visible region masks and bounding boxes as structured priors for correspondence estimation. Built upon the Segment Anything Model (SAM), it introduces a symmetric cross-view interaction mechanism that enables bidirectional feature exchange and cross-view semantic alignment. We further develop a unified supervision scheme that jointly optimizes mask prediction and box localization through mask learning, box regression, and mask-box consistency constraints. Extensive experiments on challenging benchmarks demonstrate substantial improvements over existing matching pipelines, particularly under large viewpoint and scale variations. Our results show that foundation models originally designed for monocular segmentation can be effectively extended to multi-view correspondence reasoning through explicit co-visibility modeling, offering a new perspective on structured representation learning for image matching. Code and project page: this https URL
### Title:
          A unified multi-task framework enables interpretable chest radiograph analysis
 - **Authors:** Lijian Xu, Ziyu Ni, Xinglong Liu, Xiaosong Wang, Hongsheng Li, Shaoting Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While multimodal deep learning has advanced medical imaging analysis, existing black-box systems \textcolor{black}{may remain confined to isolated tasks, often overlooking} the trust-sensitive nature of clinical diagnosis as a multi-task process. We propose IMT-CXR (Interpretable Multi-task Transformer for Chest X-ray Analysis), a framework that emulates radiologists' diagnostic workflow through three evidence-driven stages: 1) Disease recognition; 2) Attribute characterization (e.g., size, location, severity quantification); 3) Evidence-integrated report generation with traceable decision pathways. The framework employs a unified transformer architecture optimized via medical-domain instruction tuning, sequentially executing four clinical tasks: multi-label disease classification, lesion localization, anatomical segmentation, and radiology report generation. Experimental validation demonstrates competitive performance on ten CXR benchmarks under direct inference and fine-tuning settings. In a blinded evaluation of 160 historical reports from four medical centers, three radiologists rated 66\% of AI-generated reports as comparable to or surpassing original clinical reports in diagnostic clarity, highlighting the framework's translational potential. By establishing traceable diagnostic pathways from anatomical findings to conclusions, this work bridges the gap between AI technical metrics and clinical utility, advancing trustworthy AI systems in medical imaging.
### Title:
          Structure-Guided Mixed Masked Pretraining and Spatial Continuity Regularization for Printed Circuit Board Defect Detection
 - **Authors:** Peitong Wang, Nuo Wang, Enxin Qin, Chengjin Yu, Hanyu Xuan, Yuanting Yan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Printed circuit board (PCB) defect detection is an essential part of automated optical inspection (AOI); yet it remains challenging in practice because many defects are tiny, low-contrast, and embedded in dense circuit backgrounds. To address these issues, this paper presents a two-phase PCB defect detection framework that combines structure-guided mixed masked pretraining with spatial continuity regularization. In the pretraining stage, we design a sparse convolutional masked pretraining scheme to exploit unlabeled PCB images, where structure-guided mixed masking is used to construct informative masked inputs. The sparse convolutional reconstruction pipeline suppresses invalid responses from masked regions and enables the detector backbone to infer missing PCB structures from visible conductive patterns, thereby learning PCB structural priors. In the fine-tuning stage, the pretrained backbone is transferred to the downstream defect detection task. For the task, a spatial continuity regularization term is introduced during fine-tuning. This term constrains dispersed positive predictions assigned to the same defect instance and promotes more compact localization on elongated defect regions. Experiments on the DsPCBSD+ dataset show that the proposed method achieves 85.5% mAP0.5 and 52.3% mAP0.5:0.95, outperforming several strong baseline detectors. Ablation studies and qualitative results further confirm the effectiveness of the proposed framework for robust PCB defect detection in industrial AOI scenarios.
### Title:
          \textsc{CR-Seg}: Attention-Guided and CoT-Enhanced Coarse-to-Refined Reasoning Segmentation
 - **Authors:** Yifan Cao, Xiaocui Yang, Faxian Wan, Shi Feng, Daling Wang, Yifei Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reasoning segmentation aims to segment target objects described by complex language through joint visual-textual reasoning. Existing methods typically rely on either learned semantic tokens to bridge Multimodal Large Language Models (MLLMs) and segmentation models, suffering from difficult cross-modal alignment, or explicit spatial prompts such as bounding boxes, which may lose holistic response semantics. To address these limitations, we propose Attention-Guided and CoT-Enhanced Coarse-to-Refined Reasoning Segmentation, termed CR-Seg, a two-stage framework for coarse-to-refined reasoning segmentation. Specifically, we design an Extract Attention Maps and Points (EAP) module to extract attention maps for coarse target localization and select informative points, both of which are fed into SAM for mask refinement. To alleviate reasoning--answer inconsistency, we further introduce Global-to-Local Chain-of-Thought (GLCoT), which guides the model to reason progressively from global scene context to local target details. Extensive experiments on reasoning segmentation benchmarks demonstrate the effectiveness of CR-Seg.
### Title:
          Efficient Transformer-Based Localized Patch Sampling for Choroid Plexus Segmentation in Multiple Sclerosis
 - **Authors:** Po-Jui Lu, Alessandro Cagol, Mario Ocampo-Pineda, Federico Spagnolo, Marina Mastantuono, Andreea-Alexandra Aldea, Jannis Müller, Özgür Yaldizli, Matthias Weigel, Lester Melie-Garcia, Roberta Magliozzi, Maria Pia Sormani, Ludwig Kappos, Jens Kuhle, Cristina Granziera
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Background: The lateral ventricle choroid plexus (LVCP) is gaining recognition as a key imaging biomarker for multiple sclerosis (MS) related to physical disability and neuroinflammation. Yet, manual segmentation of the LVCP is highly tedious, restricting its use in broad clinical trials and longitudinal assessments. This research aims to develop a SwinUNETR-driven pipeline that leverages targeted intra- and peri-ventricular small patch sampling to automatically segment the LVCP in MS from both standalone and multi-modal MRI inputs. Methods: We retrospectively assessed 3T MRI scans across three sets of data stemming from two separate MS-dominant cohorts (Dataset 1: n=177; Dataset 2: n=177; expanded test set: n=388). Our method employed a SwinUNETR architecture trained on 32x32x32 voxel patches, benchmarking it against the 3D UXNET model. The primary metric for evaluation was the Dice Similarity Coefficient (DSC), supplemented by computational demand (GFLOPs) and the 95th percentile Hausdorff Distance (HD95). Results: On the extended test set, the SwinUNETR model secured a mean DSC of 0.868 (95% CI: 0.863-0.872) with MPRAGE and FLAIR combined, showing a statistically significant gain over UXNET (DSC: 0.858 [95% CI: 0.853-0.862], p<0.0001). When restricted to standalone FLAIR inputs, the transformer-based approach sustained a high DSC of 0.863, while the spatial localization of UXNET worsened considerably (HD95: 1.86 vs. 3.00 mm). Importantly, the proposed framework lowered computational load by 99% (91.8 vs. 22,080 GFLOPs). By integrating localized patch sampling with a SwinUNETR architecture, this methodology offers an accurate, robust, and statistically superior alternative to current leading models for LVCP segmentation. Its vast reduction in computational cost makes it ideal for widespread implementation in clinical and research environments.
### Title:
          Expert-Aware Causal Tracing of Factual Recall in Sparse MoE Language Models
 - **Authors:** Yuetian Lu, Ali Modarressi, Yihong Liu, Hinrich Schütze
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Causal tracing of factual recall has been studied predominantly in dense transformer language models, where interventions localize information flow to layers or feed-forward modules. Sparse mixture-of-experts (MoE) language models introduce a sharper question: when a factual prediction is mediated by a routed MoE block, which routed expert contributions matter? We formulate expert-aware causal tracing for sparse MoE language models. Using CounterFact facts, we first corrupt the model's factual preference by adding noise to subject-token embeddings, and then test whether clean MoE-block outputs or clean expert-level updates restore the true-vs-foil logit contrast. For Qwen3-30B-A3B-Base, a layer sweep selects and validates layer 44, and expert-level tracing identifies L44E069 as an expert repeatedly selected in the clean run whose held-out patch outperforms other active same-layer expert patches. For Mixtral-8x7B-v0.1, layer-level tracing validates a mid-layer signal, but the signal is not localized to the selected singleton expert; a coalition check instead recovers it with routed multi-expert updates. These results suggest that MoE factual tracing can be made expert-aware, while also showing that expert-level localization is model- and protocol-dependent rather than universal.
### Title:
          BigFinanceBench: A Workflow-Grounded Benchmark for Financial-Research Agents
 - **Authors:** Alex Wang, Georg Meinhardt, Jacob Katz, Joseph H. Kim, Pratyush K. Chaudhary, Chase Blagden, Eric Xu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Financial-research answers are decision-relevant only when another analyst can audit how they were produced: which source was chosen, which period and accounting definition were used, which assumptions were made, and how the calculation was performed. Existing finance benchmarks largely evaluate isolated subskills or final answers, leaving the auditable derivation itself under-measured. We introduce BigFinanceBench, a 928-item expert-authored benchmark of open-ended financial-research tasks in which each item pairs a ground-truth reference answer with a point-weighted rubric that decomposes the derivation into independently checkable steps. BigFinanceBench is workflow-grounded in that it evaluates the full derivation rather than only the final output. Across 36,241 rubric points, the benchmark supports partial-credit evaluation and localization of failures across the analyst workflow. Evaluating ten current frontier and open-weight agents, we find substantial headroom: the best system reaches only 58.8% rubric score, final-answer accuracy is a useful but lossy proxy for derivation quality, and model capability varies non-uniformly across financial workflows.
### Title:
          Formalizing all indexed mathematics as a benchmark for general reasoning, with the example of implementing dilatations of categories
 - **Authors:** A. Mayeux
 - **Subjects:** Subjects:
Databases (cs.DB); Human-Computer Interaction (cs.HC); Category Theory (math.CT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Formal rigor distinguishes mathematics from other disciplines, in the sense that mathematical statements are derived from explicit axioms by logically verifiable steps. Interactive theorem provers support this by expressing definitions, theorems, and proofs in a fully formal language and verifying them mechanically. We consider the benchmark problem of formalizing all published mathematics as a machine verifiable and continuously updated corpus of mathematical knowledge. This viewpoint treats mathematics as a structured database of interdependent results and raises questions about scalability and organization of large formal libraries. As a case study, we present an ongoing formalization in categorical algebra, namely dilatations of categories, extending classical localizations and illustrating what such an implementation looks like in practice.
### Title:
          FLARE: Fine-Grained Diagnostic Feedback for LLM Code Refinement
 - **Authors:** Yinsheng Yao, Hongxiang Zhang, Weixi Tong, Tianyi Zhang
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models often generate code with bugs. Existing methods rely on feedback signals such as test failures and self-critiques to iteratively refine the generated code. Such signals are either too coarse-grained or too high-level, which is not sufficient to inform the model where to fix the bug. In this work, we present Flare, an iterative framework with a lightweight diagnostic model that predicts line-level suspiciousness signals for bug localization and code refinement. Given the inherent uncertainty of diagnostic predictions, Flare searches over the top-k suspicious regions and selects the best candidate according to execution outcomes. Experiments on LiveCodeBench and BigCodeBench with five base LLMs show that, even without candidate search (k=1), Flare outperforms the strongest baseline with an absolute improvement from 1.72% to 7.42%. Furthermore, searching over 10 candidates yields an average improvement of 8.50% compared with no candidate search. When evaluated in isolation, our lightweight diagnostic model achieves the best performance compared with recent fault localization methods, demonstrating that it can provide reliable fine-grained guidance for code refinement.
### Title:
          Physics-Informed Single Atom Matching Pursuit: Guided-Waves Wavenumbers and Propagation Distance Estimation for Damage Localization in Structural Health Monitoring
 - **Authors:** Sebastian Rodriguez, Borja Ferrandiz, Francisco Chinesta, Nazih Mechbal, Marc Rébillat
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Structural Health Monitoring (SHM) aims at the real-time monitoring of the integrity of engineering structures, with Guided-waves (GWs) providing high sensitivity to damage presence and to ageing effects for thin-walled components. In conventional GW-based SHM, a bonded piezoelectric transducer (PZT) emits a short tone burst that produces an Initial Wave Packet (IWP) propagating through the structure. As this packet interacts with boundaries and potential damages, additional scattered wave packets are produced. A major limitation of such approaches lies in the simultaneous excitation of multiple dispersive GW modes by a single PZT, which significantly complicates signal interpretation and damage monitoring. In this context, this work proposes the Physics-Informed Single Atom Matching Pursuit (PISAMP) method, a signal decomposition method grounded in the physical principles governing wave propagation. In contrast with purely data-driven or numerically intensive techniques, the proposed approach embeds strong physical constraints into a low-dimensional and computationally efficient signal representation. This formulation enables the direct identification of key physically meaningful features, including modal wavenumber functions and propagation distances between actuator, damage and sensors. These extracted features, especially source-damage-sensor distances, allows to subsequently perform damage location using well established Elliptical Localization techniques. The principal novelty of this study lies in integrating wave propagation physics into a compact signal decomposition framework and developing an interpretable damage localization methodology for GW-SHM applications.
## Keyword: transformer
### Title:
          IdiomX A Multilingual Benchmark for Idiom Understanding, Retrieval, and Interpretation
 - **Authors:** Ayman Ali Sharara
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Idiomatic expressions remain a persistent challenge for natural language processing because their meanings are often non-compositional, context-dependent, and difficult to align across languages. Existing idiom resources are often limited in scale, contextual diversity, or multilingual coverage, restricting their utility for modern language models. We introduce IdiomX, a large-scale multilingual benchmark for idiom understanding, retrieval, and interpretation, constructed through a reproducible multi-stage pipeline combining lexical resource extraction, large-scale normalization, controlled large language model enrichment, and structured validation. The resulting dataset contains over 190K contextualized examples spanning 12K+ idioms, with aligned English, Arabic, and French semantic representations, idiomatic and literal usage labels, and rich linguistic metadata. Building on this resource, we define a unified four-task benchmark covering idiom detection, context-to-idiom retrieval, Arabic-to-English idiom retrieval, and idiom interpretation, extending evaluation from figurative recognition to semantic grounding and explainable meaning retrieval. Experiments show that contextual transformer models substantially improve idiom detection, while hybrid retrieval and reranking architectures significantly strengthen both monolingual and cross-lingual idiom retrieval. Results further demonstrate that idiom interpretation can be effectively modeled as a semantic retrieval task, introducing interpretability as a complementary benchmark dimension. Overall, IdiomX provides a scalable benchmark for studying idiomatic language as a progression from detection to retrieval and semantic interpretation, and offers a modular framework extensible to additional languages and figurative reasoning tasks
### Title:
          Spectral Asymptotics of Neural Network Loss Landscapes: An Exact Decomposition of the Curvature Exponent
 - **Authors:** Anherutowa Calvo
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The curvature exponent $\alpha$ in $h_k \propto \sigma_k^\alpha$ -- governing how Hessian eigenvalues scale with gradient singular values -- varies systematically across layer types ($\alpha \approx 2$ for convolutions, $\approx 1$ for transformer attention, $< 1$ for MLP up-projections). Why? We prove the Spectral Alignment Decomposition: $\alpha = 2 + d\log\Phi_k / d\log\sigma_k$, where $\Phi_k$ measures alignment between Kronecker factor eigenbases and gradient singular directions. This reduces "why does $\alpha$ vary?" to a geometric question we answer for LayerNorm, residual connections, and softmax heads. The decomposition implies a spectral transfer identity $s = \alpha\gamma$ linking curvature exponent, effective gradient rank-decay $\gamma$, and Hessian decay exponent $s$. The identity is algebraic; its empirical content is that $\alpha$ and $\gamma$, fit on independent data (HVPs vs. SVD), recover $s$ to ~2% median error across 93 layers, five architectures, and three datasets -- with no free parameters. A zeta-function bound on participation ratio shows curvature concentrates onto effectively one direction per layer. As a proof of concept, we derive the architecture-adaptive preconditioner $T(\sigma;\alpha)$ and show that Spectral Newton -- implementing $T$ in the gradient singular basis -- outperforms AdamW on vision benchmarks where $\alpha \approx 2$.
### Title:
          Graph Mamba Survival Analysis Based on Topology-Aware ordering
 - **Authors:** Yuanfang Chen, Peiqiang Yan, Yuntao Shou, Qian Zhao, Xiangyong Cao
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In computational pathology, Whole Slide Images (WSIs) survival analysis is crucial for patient prognosis assessment, but it faces multiple technical challenges. Although the Transformer captures long-range dependencies through its self-attention mechanism, its $O(N^2)$ time complexity causes a severe computational bottleneck in large-scale WSIs graph structures. The Mamba model breaks through the Transformer's computational bottleneck with linear complexity. But, owing to Mamba's high sensitivity to the order of input data, traditional node sorting methods in Graph Mamba, such as those based on node degree or subgraph size, fail to adequately account for the topological connectivity of graph data. This inadequacy consequently restricts the performance of Mamba's sequential modeling. Moreover, its unidirectional architecture cannot leverage the bidirectional spatial structure of images. To address these challenges, this paper proposes a novel Graph Mamba survival analysis framework based on topology-aware ordering (TopoMamSurv) to adapt to the sequential sensitivity of Mamba. Our visualization experiments further confirmed that the nodes extracted through the topology-aware ordering (TAO) strategy indeed exhibit higher similarity. Furthermore, we designed a bidirectional Mamba module and integrated a Graph Convolutional Network (GCN) to achieve bidirectional spatial context modeling of images, forming a hierarchical feature learning architecture for "local aggregation - global capture." This framework effectively reconciles the contradiction between long-range dependency modeling, computational efficiency, and spatial structure utilization in WSIs analysis through its systematic design of TAO, bidirectional semantic modeling, and hierarchical feature fusion. This framework has been validated for its comprehensive performance advantage on five TCGA datasets.
### Title:
          Geometry-Aware Tabular Diffusion
 - **Authors:** David Turtora Zagardo
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tabular synthesis is critical for privacy-preserving sharing and augmentation, yet diffusion models rely on implicit mechanisms to capture inter-column relationships. We introduce Geometry-Aware Tabular Diffusion (GATD), which augments tabular diffusion denoisers with pairwise angles and lengths computed from column value differences and used as inputs and auxiliary targets. Our MLP instantiation achieves state-of-the-art benchmark performance while using 3.5x fewer parameters on average (up to 25x for classification tasks): on ten datasets, it wins 8/10 Shape, 7/10 Trend, and 9/10 downstream utility (F1/RMSE), reducing Shape and Trend error by 27% and 20%. Default loss weights transfer to GNN and Transformer denoisers, improving Shape on 27/30 and Trend on 25/30 architecture-dataset cells. A matched ablation shows supervision (not extra inputs or capacity) drives the gain. This shows explicit relational supervision is a portable inductive bias for tabular diffusion.
### Title:
          SegTune: Structured and Fine-Grained Control for Song Generation
 - **Authors:** Yuejiao Wang, Zihao Ji, Pengfei Cai, Xu Li, Haorui Zheng, Zewen Song, Zhongliang Liu, Chen Zhang, Pengfei Wan
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in neural song generation have enabled high-quality synthesis from lyrics and global textual prompts. However, most systems fail to model temporally varying attributes of songs, severely limiting fine-grained control over musical structure and dynamics. To address this, we propose SegTune, a Diffusion Transformer-based framework enabling structured and fine-grained controllability by allowing users or large language models (LLMs) to specify local musical descriptions aligned to song segments. These segment prompts are temporally broadcast to corresponding time windows, while global prompts ensure stylistic coherence. To support precise lyric-to-music alignment, we introduce an LLM-based duration predictor that autoregressively generates sentence-level timestamps in LyRiCs format. We further construct a large-scale data pipeline for high-quality song collection with aligned lyrics and prompts, and propose new metrics to evaluate segment alignment and vocal consistency. Experiments demonstrate that SegTune outperforms existing baselines in both musicality and controllability. Visit our project page (this https URL) for codes and more generated songs.
### Title:
          Heterogeneous Mapping for Analog In-Memory Computing Accelerators: A Unified Workflow
 - **Authors:** Corey Lammie
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Analog In-Memory Computing (AIMC) accelerators execute matrix-vector multiplications directly within memory arrays, reducing data movement and improving DNN inference efficiency. Their limited effective precision motivates heterogeneous architectures that combine analog compute tiles with digital processing units. This letter classifies existing methods for partitioning DNN workloads across these resources by mapping granularity, optimization strategy, and model support, and distills them into a unified four-stage workflow. To demonstrate the workflow on a model class not yet addressed by existing methods, we apply its first two stages to GPT-2, producing the first AIMC-specific precision sensitivity profile for a decoder-only transformer. Sensitivity is dominated by 4 of 49 projections, with the first decoder block's attention output dominating by an order of magnitude. This suggests that projection-level mapping and selective digital execution of early-block and output-facing projections are important for reliable decoder-transformer deployment on AIMC hardware.
### Title:
          MetaWorld: Scaling Multi-Agent Video World Model from Single-view Video Data
 - **Authors:** Teng Hu, Mingchun Lu, Yating Wang, Jiangning Zhang, Jinkun Hao, Ye Pan, Ran Yi, Lizhuang Ma, Dacheng Tao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video world models are a foundational generative technology for embodied AI and the Metaverse, yet existing approaches are inherently limited to a single agent observing from a single perspective. Extending these models to multi-agent settings introduces two critical challenges: data scarcity (coordinated multi-view recordings are prohibitively expensive to collect for general open-domain scenarios) and world state alignment (independently generated video streams cannot ensure that shared physical environments and events evolve consistently across views). To address these challenges, we propose MetaWorld, a novel framework that scales multi-agent video world models to open-domain environments directly from single-view videos. First, we introduce Monocular World-State Unrolling (MWSU) to explicitly decompose monocular footage into the camera operator's ego-motion and the visible subject's spatial trajectory. This camera-trajectory decomposition naturally extracts synchronized multi-agent motion data within a shared 3D space, completely bypassing the need for multi-camera setups. Second, for precise visual control, we develop the Subject-Aware World Generator to enable appearance-driven simulation conditioned on per-agent identity images. Finally, to ensure both views are grounded in the identical physical reality, we propose World-State Alignment, a per-frame inter-branch cross-attention mechanism inserted at every transformer layer of the video DiT. By jointly synchronizing the denoising process, WSA enforces both static geometric consistency and dynamic motion consistency, encouraging that the shared 3D environment and physical events remain well-aligned across both egocentric views. Extensive experiments demonstrate that MetaWorld achieves superior cross-view consistency and identity fidelity, establishing a highly scalable, physics-driven paradigm for multi-agent video world modeling.
### Title:
          From Local Training to Large-Scale Mapping: A Comparative Assessment of Machine Learning and Deep Learning for Transferable Satellite-Derived Bathymetry
 - **Authors:** Hsiao-Jou Hsu, Joachim Moortgat
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computational Physics (physics.comp-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Satellite-derived bathymetry (SDB) from multispectral imagery is cost-effective but scales poorly across regions, especially in optically complex coastal environments. We evaluate machine learning and deep learning for transferable SDB over the 0-20 m depth range using Sentinel-2 imagery. A Random Forest baseline and four CNNs (ResNet-50, ResNet-101, EfficientNet-B4, ConvNeXt-Large) are trained on Pratas Island and selected Great Barrier Reef regions, then evaluated on spatially independent intra- and cross-regional test areas. Preserving spatial continuity during training, by keeping contiguous reef blocks rather than random patches, is the single most impactful design choice; we further introduce a Smooth Weight Function (SWF)-weighted RMSE loss that emphasizes near-surface depths. With these choices, intra-regional RMSE ranges from 1.15 to 1.92 m over 0-20 m and is as low as 0.26 m for depths <= 3 m. Random Forest degrades sharply under cross-regional transfer (RMSE 1.53 m -> 2.99-3.78 m), while the deep models stay more robust (2.46-2.98 m). On the public MagicBathyNet aerial-RGB benchmark (0-16 m) the proposed networks reach 0.19-0.22 m RMSE, outperforming a U-Net baseline and a task-specific transformer architecture with substantially fewer parameters. We further exploit multi-temporal repeat imagery: training on it broadens diversity, and median-aggregating predictions across passes at inference reduces noise from changing sun angles, atmospheric conditions, water properties, and tides. We release optimized architectures and pretrained weights to enable scalable transfer to new sites.
### Title:
          Representational Capacity: Geometric Limits on Feature Representation in Transformer Language Models
 - **Authors:** Alexander Guha
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Model dimension ($d_{model}$) is a fundamental hyperparameter in transformer language models, yet its role in setting the geometric limits of feature representation remains under-explored. Grounded in the Linear Representation and Superposition Hypotheses - which propose that models encode features as near-orthogonal directions in latent space - we develop a framework for estimating how many such directions a model can support. We first establish the embedding matrix as a measurable proxy for near-orthogonality constraints across the latent space: the boundary between meaningful token relationships and incidental similarity in the pairwise cosine similarity distribution gives a concrete estimate of the model's accepted deviation $\varepsilon$ from perfect orthogonality. Applying this metric across dozens of open-source models reveals two classes: models with high $\varepsilon$ whose embeddings lack near-orthogonal structure, and models with low $\varepsilon$ that maintain it. We then show that the standard Johnson-Lindenstrauss lemma greatly underestimates the packing efficiency of trained representations, and derive an adjusted capacity formula in which the number of near-orthogonal directions depends on the ratio of vectors to dimensions ($k/d$) rather than the raw count - a single modification that cuts prediction error by two orders of magnitude with no extra parameters. Combining these results, we define representational capacity as an upper bound on the number of distinguishable directions available for features and embeddings in a model's latent space. Capacity is exponentially sensitive to $\varepsilon$, and larger models favor tighter orthogonality constraints over maximizing raw capacity - a pattern compatible with several explanations (a stability-capacity trade-off, a ceiling on usable concepts, or confounds with model scale) that we leave to future work.
### Title:
          Do Value Vectors in Deep Layers Need Context from the Residual Stream?
 - **Authors:** Muyu He, Yuchen Liu, Qingya Huang, Li Zhang
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The success of the transformer architecture as the backbone of modern LLMs is in large part due to its use of attention layers. An attention layer follows the standard neural network paradigm: it takes the residual stream as input and thereby produces context-dependent query, key, and value vectors. However, we find that model performance meaningfully improves when deeper layers learn only a context-free value vector to preserve the original token information, without drawing on any context from the residual stream. When the model has access to this context-free value vector, adding back the context-dependent component provides little additional benefit for aggregate benchmark performance. Such context-free value vectors can be stored as sparse model parameters, eliminating the need to recompute or persistently cache these values. Through systematic ablations on the key design choices for such context-free value vectors, we propose Bank of Values (BoV), a new way of computing value vectors in attention by learning a lookup table of token-specific value vectors for each of the last third of layers. Across 135M and 780M models, BoV improves validation loss over standard attention and, at 780M, the average score across 21 benchmarks, matching the previous best method that adds token information to the value vector with less compute and memory.
### Title:
          Evaluating Transformer and LSTM Frameworks for Prediction in Ungauged Basins
 - **Authors:** Taye Akinrele, James Halgren, Noorbakhsh Amiri Golilarz, Sudip Mittal, Shahram Rahimi
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Watershed networks exhibit convergent topologies in which multiple tributaries merge into downstream channels,integrating diverse upstream hydrological processes. In ungauged basins, the absence of direct observations increases uncertainty and limits the ability to anticipate extreme events. This study evaluates whether an encoder-only Transformer provides an advantage over an LSTM for upstream streamflow inference under limited hydrologic information, using retrospective simulations from the NOAA National Water Model (NWM). Across both upstream-only and combined configurations, the LSTM showed stronger overall performance than the Transformer model across the two configurations. Incorporating downstream information further boosted performance for all models, increasing median NNSE by more than 60%. Rather than treating this as a leaderboard-style comparison, we interpret the experiments as a test of architectural inductive bias for hydrologic sequence inference. The results indicate that recurrent memory remains better aligned with this upstream reconstruction task than an encoder-only Transformer, while downstream hydrologic context provides a strong auxiliary constraint that substantially improves prediction skill across architectures
### Title:
          Cosmos 3: Omnimodal World Models for Physical AI
 - **Authors:** Aditi, Niket Agarwal, Arslan Ali, Jon Allen, Martin Antolini, Adeline Aubame, Alisson Azzolini, Junjie Bai, Maciej Bala, Yogesh Balaji, Josh Bapst, Aarti Basant, Mukesh Beladiya, Mohammad Qazim Bhat, Zaid Pervaiz Bhat, Dan Blick, Vanni Brighella, Han Cai, Tiffany Cai, Eric Cameracci, Jiaxin Cao, Yulong Cao, Mark Carlson, Carlos Casanova, Ting-Yun Chang, Yan Chang, Yu-Wei Chao, Prithvijit Chattopadhyay, Roshan Chaudhari, Chieh-Yun Chen, Junyu Chen, Ke Chen, Qizhi Chen, Wenkai Chen, Xiaotong Chen, Yu Chen, An-Chieh Cheng, Click Cheng, Xiu Chia, Jeana Choi, Chaeyeon Chung, Wenyan Cong, Yin Cui, Magdalena Dadela, Nalin Dadhich, Wenliang Dai, Joyjit Daw, Alperen Degirmenci, Rodrigo Vieira Del Monte, Robert Denomme, Sameer Dharur, Marco Di Lucca, Ke Ding, Wenhao Ding, Yifan Ding, Yuzhu Dong, Nicole Drumheller, Yilun Du, Aigul Dzhumamuratova, Aleksandr Efitorov, Hamid Eghbalzadeh, Naomi Eigbe, Imad El Hanafi, Hassan Eslami, Benedikt Falk, Jiaojiao Fan, Jim Fan, Amol Fasale, Sergiy Fefilatyev, Liang Feng, Francesco Ferroni, Sanja Fidler, Xiao Fu, Vikram Fugro, Prashant Gaikwad, TJ Galda, Katelyn Gao, Yihuai Gao, Wenhang Ge, Sreyan Ghosh, Arushi Goel, Vivek Goel, Akash Gokul, Rama Govindaraju, Jinwei Gu, Miguel Guerrero, Elfie Guo, Aryaman Gupta, Siddharth Gururani, Hugo Hadfield, Song Han, Ankur Handa, Zekun Hao, Mohammad Harrim, Ali Hassani, Nathan Hayes-Roth, Yufan He, Chris Helvig, Cyrus Hogg, Madison Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Multimedia (cs.MM); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Cosmos 3, a family of omnimodal world models designed to jointly process and generate language, image, video, audio, and action sequences within a unified mixture-of-transformers architecture. By supporting highly flexible input-output configurations, Cosmos 3 seamlessly unifies critical modalities for Physical AI -- effectively subsuming vision-language models, video generators, world simulators, and world-action models into a single framework. Our evaluation demonstrates that Cosmos 3 establishes a new state-of-the-art across a diverse suite of understanding and generation tasks, demonstrating omnimodal world models as scalable, general-purpose backbones for embodied agents. Our post-trained Cosmos 3 models were ranked as the best open-source Text-to-Image and Image-to-Video models by Artificial Analysis, and the best policy model by RoboArena at the time the technical report was written. To accelerate open research and deployment in Physical AI, we make our code, model checkpoints, curated synthetic datasets, and evaluation benchmark available under the Linux Foundation's OpenMDW-1.1 this https URL License at this https URL}{this http URL and this https URL . The project website is available at this https URL .
### Title:
          Qift: Shift-Friendly No-Zero W2 Post-Training Quantization for Rotated W2A4/KV4 LLM Inference
 - **Authors:** Chi-Wei Huang, Chia-Chi Tsai
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Two-bit weight quantization is attractive for memory-efficient LLM inference, but the standard W2 level set {-2,-1,0,+1} often collapses under aggressive W2A4/KV4 settings. We study the scalar level-set geometry of two-bit weights in a Hadamard-rotated quantization pipeline. Conventional asymmetric W2 substantially improves over the standard level set, indicating that W2A4 failure is not only a bit-width problem but also a reconstruction-level problem. Across all 224 linear modules in each of LLaMA-2-7B and LLaMA-3.1-8B, pretrained weights are already nearly zero-centered, while Hadamard rotation primarily Gaussianizes their standardized shape: excess kurtosis and Q-Q error drop by orders of magnitude. Based on this approximate zero-centered Gaussian-like source model, we propose Qift, a fixed no-zero W2 level set for rotated W2A4/KV4 inference. The main level set is {+/-0.5, +/-1.5}, equivalently {+/-1, +/-3} under a half-scale reparameterization; a power-of-two variant uses {+/-1, +/-4} for sign-and-shift decoded weight application. Qift redesigns the fixed two-bit code-to-level mapping and is training-free, learned-codebook-free, group-grid-free, and zero-point-free, retaining the standard per-channel scale. A scale-invariant ratio analysis identifies an effective inner/outer centroid ratio range of 0.25 to 0.33, explaining why mirror no-zero (MNZ), Lloyd, NF2, and PoT-MNZ perform well while {+/-1, +/-2} does not. On both models, the no-zero level sets consistently improve pure W2A4 perplexity, L-layer mixed W2/W4 perplexity, downstream accuracy, and GPTQ residual behavior over the standard W2 level set. At L=16 mixed precision, they substantially narrow the gap to W3A4 while keeping half of the transformer layers at two-bit precision, giving a simple, source-aware, and deployment-friendly alternative to more complex learned W2 codebooks.
### Title:
          Principled Reflection Separation via Nonlinear Superposition and Feature Interaction
 - **Authors:** Qiming Hu, Mingjia Li, Yuntong Li, Xiaojie Guo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Single-image reflection separation is fundamentally challenged by the entanglement of transmission and reflection layers under complex image formation processes. Existing approaches largely rely on simplified assumptions or independent modeling, limiting their ability to handle real-world scenarios. In this work, we revisit the problem from a unified perspective and identify a key issue of existing approaches, i.e., the widely adopted linear composition model in the sRGB domain fails to capture the nonlinear coupling introduced by real-world image signal processing pipelines. To address this, we introduce a learnable nonlinear superposition model that more faithfully characterizes layer interactions and improves decomposition fidelity. Building upon this formulation, we propose a generalized dual-stream interactive framework that explicitly models bidirectional dependencies between transmission and reflection through feature exchange. This framework unifies activation-, gating-, and attention-based interaction mechanisms, and is compatible with both CNN and Transformer backbones. Extensive experiments on diverse real-world benchmarks demonstrate that the proposed approach achieves superior performance with strong generalization capability. More importantly, our study reveals that reflection separation is not about undoing a linear mixture, but about learning nonlinear formation and interaction}, offering new insights into the design of principled image decomposition models. Code and models are publicly available at this https URL.
### Title:
          Fast Transformer Inference on ARM-Based HMPSoCs
 - **Authors:** Hang Xu, Yixian Shen, Thanassis Giannetsos, Anuj Pathania
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer models have set new performance standards for machine learning (ML) tasks. However, their resource-intensive deployment on resource-constrained edge devices for cloud-free, on-chip transformer inference remains challenging. The ARM Compute Library (ARM-CL) framework provides low-latency CNN inference on ARM-based edge devices but lacks support for transformer inference. In this work, we implement several new transformer kernels in ARM-CL to support native transformer execution. Our extended ARM-CL achieves up to three times faster transformer inference compared to state-of-the-art CPU/GPU implementations on an ARM-based embedded board. Furthermore, heterogeneous multi-processor system-on-chips (HMPSoCs) powering edge devices provide both embedded CPUs and GPUs. We introduce cooperative CPU-GPU transformer inference, which executes memory-intensive operations on the CPU while utilizing the GPU for highly parallelizable, compute-intensive operations. This cooperative execution, implemented with minimal overhead, further reduces transformer inference latency by up to 15.72% compared to the best single-processor inference on ARM-CL.
### Title:
          RESCAST-100K: A Comprehensive Dataset for Cross-Domain Residential Load and Indoor Temperature Forecasting
 - **Authors:** Jainam Dhruva, Yousaf Raza, A.B. Siddique, Simone Silvestri
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate short-term forecasting of residential energy load and indoor temperature is essential for home energy management systems, grid-level demand response, and community energy efficiency efforts. Domain adaptation and transfer learning have shown promise for improving forecasting accuracy under data heterogeneity and scarcity commonly seen in residential settings. However, progress is limited by the lack of comprehensive residential datasets: existing benchmarks are narrow in target coverage and rarely support structured cross-domain evaluation. We introduce RESCAST-100K, a large-scale residential forecasting benchmark for studying cross-domain generalization. It provides a configuration-driven interface that instantiates source and target domains along interpretable axes, including geography, climate zone, wall construction, and heating equipment, enabling systematic evaluation of transfer learning, domain adaptation, and zero-shot generalization under controlled domain shifts. The benchmark covers approximately 100,000 EnergyPlus-simulated U.S. homes derived from ResStock, with 15-minute time series for three coupled targets per home: total load, HVAC load, and indoor temperature. These are paired with weather channels, HVAC setpoints, and over 40 static building covariates. RESCAST-100K also integrates five real-world residential datasets under a unified schema, supporting sim-to-real evaluation on the same tasks. We benchmark recurrent, attention-based, and MLP-mixer architectures for zero-shot performance across domains, missing-input conditions, and forecasting tasks. Cross-attention and MLP-mixer models consistently outperform recurrent and classical transformer baselines under domain shift. RESCAST-100K is intended to aid the machine learning and building analytics communities advance cross-domain residential forecasting at home, community, and grid scale.
### Title:
          Forgetting is Not Erasure: Recovering Latent Knowledge via Transport Keys
 - **Authors:** Archie Chaudhury
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Catastrophic forgetting is often framed as a representational problem: after sequential training, a model appears to lose the features that supported performance on earlier tasks. We challenge the stronger form of this view. Across controlled continual-learning settings, we find that a significant portion of apparent forgetting can be attributed to interface drift between internal stages rather than permanent erasure of task-relevant computation. We study this phenomenon through a stitched evaluation protocol that combines early computation from a post-update network with late computation from its predecessor, optionally mediated by a compact, task-specific transport key. We describe transport keys at a systems level as compact interface-alignment operators estimated from a small set of paired anchor activations and evaluated through model stitching. On split CIFAR-100 with a ResNet-style network, transport keys recover most of the original Task A performance after sequential training on Task B. On a compact vision transformer, we observe a similar recovery pattern. These results suggest that continual learning may require better mechanisms for indexing and re-accessing latent computations, not only methods that prevent weight change.
### Title:
          SaluNet: Enabling Total Plasticity in Normalization-Free Deep Networks
 - **Authors:** Mourad Zaied (University of Gabes, Tuisia)
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Normalization layers such as BatchNorm and LayerNorm have long been considered essential for stable training in deep networks. This work demonstrates that they can be fully replaced by a single learnable activation mechanism. We identify a plasticity suppression effect induced by standard normalization: learnable activation parameters rapidly lose adaptability when paired with normalization layers. Motivated by this observation, we introduce SALU (Saturated Adaptive Linear Unit), \[ \operatorname{SALU}(x;a,b) = \frac{a x}{\sqrt{1 + a b x^2}},\quad a>0,\; b>0 \] a bounded, learnable activation that provides intrinsic signal stabilization without relying on batch statistics or external affine parameters. Building on SALU, we propose SaluNet, a paradigm grounded in total plasticity: SALU replaces normalization layers, while SWALU and GALU replace standard activations. With ResNet-18, SaluNet-C-18 achieves 97.35\% on CIFAR-10 and 83.25\% on CIFAR-100 without normalization, maintaining 93.44\% and 76.23\% at batch size 1 where normalized architectures fail. For transformers, SaluNet-T improves over LayerNorm-GELU from 90.92\% to 91.01\% on CIFAR-10 and from 66.54\% to 68.10\% on CIFAR-100. SaluNet-C-50 reaches 78.67\% Top-1 on ImageNet-1K at $224\times224$, and $79.23\%$ at $288\times288$. These results suggest normalization layers suppress total plasticity, a property biological neurons inherently possess, enabling deep networks to learn effectively.
### Title:
          A Training-Efficient Transformer-Based Anti-Spoofing Network for Logical Access in ASVspoof 5
 - **Authors:** Sidan Yin, Bo Zhao
 - **Subjects:** Subjects:
Sound (cs.SD); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Synthetic and manipulated speech can reduce the reliability of automatic speaker verification systems, so anti-spoofing methods need to be both accurate and efficient in training and inference. This paper focuses on the ASVspoof 5 Track 1 closed condition, where standard cross-entropy training may not give enough attention to hard trials and is not directly aligned with ranking- and threshold-based evaluation metrics. We propose TFPARN, a Transformer-based focal-pairwise attentive ranking network. The system extracts log-Mel features from speech, uses a Transformer encoder to model frame-level information, applies attention pooling to obtain utterance-level representations, and is trained with a combination of focal classification loss and pairwise ranking loss. RawBoost augmentation is used during training, and test-time augmentation is applied during evaluation to improve robustness. Compared with re-implemented AASIST and RawNet2 baselines under the same protocol, TFPARN achieves the best results, with a minDCF of 0.2430 and an EER of 12.52%. Ablation experiments further show that the pairwise loss, focal loss, and attention pooling all improve performance. TFPARN also uses the lowest inference memory among the compared systems, at 1.4 GB, runs at about 0.79 ms per utterance, and reaches its best checkpoint in less training time than AASIST. These results show that TFPARN provides a good balance between detection accuracy and computational cost for logical access anti-spoofing.
### Title:
          Spike-Aware C++ INT8 Inference for Sparse Spiking Language Models on Commodity CPUs
 - **Authors:** Ting Liu
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spiking language models expose activation sparsity that dense Transformer runtimes do not directly exploit. This paper studies that property from a systems perspective. Building on the SymbolicLight V1 spike-gated language model family, we implement a C++ CPU inference runtime that treats sparse binary spike states as an execution primitive rather than only applying post-hoc weight compression. The runtime combines a manifest-driven weight loader, mixed row/column memory layout, AVX2/FMA kernels, per-channel symmetric INT8 quantization, and integer-domain accumulation for spike-conditioned sparse paths. On an AMD Ryzen 7 5800X, an early scalar FP32 baseline decodes at 9.5 tokens/s. Mixed-layout AVX2 FP32 raises this to 14.7 tokens/s, and AVX2 INT8 reaches 19.9 tokens/s on the same step-30k export while reducing the weight footprint from 3.49 GB to 1.06 GB. For the available 186k-step 874M-parameter INT8 export, the C++ runtime decodes at 22.63 tokens/s in a single-thread CPU benchmark, compared with 16.31 tokens/s for TinyLlama-1.1B Q8_0, 11.26 tokens/s for Falcon3-1B Q8_0, and 9.70 tokens/s for Qwen2.5-1.5B Q8_0 under this http URL. Thread scaling reaches 47.90 tokens/s at four CPU threads, and 512-token prefill improves from 29.86 to 94.68 tokens/s from one to eight threads. The throughput result comes with a quality cost: the SNN reports WikiText-2 perplexity 24.80, worse than the dense baselines in the same benchmark. We frame the result as an inference-systems study for sparse language runtimes, with longer-term motivation in embodied and edge agents that may benefit from local, low-core inference near sensors and actuators. Spike-aware execution can improve CPU throughput and memory behavior for sparse spiking language models, while model quality, controlled dense training baselines, embodied-task evaluation, and measured CPU energy remain open problems.
### Title:
          RelGT-AC: A Relational Graph Transformer for Autocomplete Tasks in Relational Databases
 - **Authors:** Phillip Jiang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Relational databases underpin modern enterprise, scientific, and healthcare systems, yet predictive machine learning on such data remains challenging due to their multi-table, heterogeneous, and temporal structure. Relational Deep Learning (RDL) addresses this by representing databases as heterogeneous graphs and applying graph neural networks (GNNs) directly. RelBench v2 recently introduced autocomplete tasks -- a practically motivated task type where the goal is to predict an existing column value from relational context, analogous to an intelligent form-filling assistant. We propose RelGT-AC (Relational Graph Transformer for Autocomplete), extending the RelGT architecture with three targeted contributions: (1) a column masking strategy that prevents trivial solutions by masking the target column during subgraph encoding; (2) a unified task head supporting binary classification, multiclass classification, and regression autocomplete tasks within a single model; and (3) a TF-IDF text encoder that automatically detects and encodes free-text columns, recovering strong lexical signal that categorical encoders discard. Across 7 tasks spanning 3 RelBench v2 datasets (rel-trial, rel-f1, rel-stack), RelGT-AC outperforms the GraphSAGE baseline on all 3 regression autocomplete tasks and achieves up to +10 AUROC points on text-heavy eligibility tasks via the TF-IDF encoder.
### Title:
          Sample-Size Scaling of the African Languages NLI Evaluation
 - **Authors:** Anuj Tiwari, Oluwapelumi Ogunremu, Terry Oko-odion, Jesujuwon Egbewale, Hannah Nwokocha
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 African languages have very little labelled data, and it is unclear if augmenting the quantity of annotation data reliably enhances downstream performance. The study is a systematic sample-size scaling study of natural language inference (NLI) on 16 African languages based on the AfriXNLI benchmark. Under controlled conditions, two multilingual transformer models with roughly 0.6B parameters XLM-R Large fine-tuned on XNLI and AfroXLM-R Large are tested on sample sizes of between 50 and 500 labeled examples and average their results across random subsampling runs. As opposed to the usual belief of monotonic increase with increased data, we find a strongly language sensitive and often non-monotonic scaling behavior. Some languages show early saturation or decrease in performance with sample size as well as high variance in low resource regimes. These results indicate that the volume of data is not enough to guarantee stable profits to African NLI, creating the necessity of language sensitive datasets creation and stronger multi-lingual modelling strategies.
### Title:
          PSViT: A Methodology for Structurally Pruning Spiking Vision Transformers
 - **Authors:** Rachmad Vidya Wicaksana Putra, Achyuta Muthuvelan, Alberto Marchisio, Muhammad Shafique
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spiking Vision Transformer (SViT) models are promising low-power ViT models for solving vision-based tasks with state-of-the-art performance. However, their large sizes limit their deployments for resource-constrained embedded platforms, underscoring the needs of model compression. One of prominent compression techniques is pruning, and the state-of-the-art works employ unstructured pruning techniques to compress SViT models. Such techniques require specialized hardware architectures tailored for the sparsity patterns to maximize their efficiency benefits, making this approach not scalable. To address this, we propose PSViT, a novel methodology to perform structured pruning on SViT models, hence making it possible to efficiently accelerate their inference using the existing and widely-used computing architectures. To do this, PSViT employs several key steps: uniform channel-wise filter pruning to structurally eliminate the non-significant weights, sensitivity analysis to evaluate the impact of channel-wise pruning of individual layer on accuracy and network size, as well as fine-grained channel-wise pruning based on the sensitivity analysis and the given network architecture. Experimental results show that PSViT effectively obtains 22.4% memory saving through single-shot pruning, while maintaining high accuracy within 3% (70.3% without fine-tuning and 72.8% with fine-tuning) from the original non-pruned SViT model (73.3%) on the ImageNet-1K. These results also show that the PSViT methodology advances the effort in enabling efficient SViT deployments on resource-constrained applications.
### Title:
          BA-T: An Iterative Transformer for Two-View Bundle Adjustment
 - **Authors:** Ganlin Zhang, Weirong Chen, Daniel Cremers, Xi Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Feed-forward models for 3D reconstruction have achieved strong performance using deep cross-view attention to exchange information across images. However, these approaches often depend on heavy decoder stacks and lack a structured mechanism for geometry refinement, resulting in poor multi-view consistency. We address this by drawing inspiration from classical bundle adjustment (BA), which can be viewed as an iterative information propagation process between poses and local geometry. Inspired by BA, we propose BA-T, an iterative Transformer that implements BA-style structured updates as a repeatable layer in implicit token space. Instead of relying on deep attention stacks, BA-T refines predictions based on latent residual by a single lightweight layer. Experiments demonstrate that BA-T progressively improves pose and reconstruction accuracy across iterations, achieves stronger cross-view consistency than conventional decoders, and matches or surpasses substantially larger models while using only 16% of their decoder parameters. BA-T provides a compact, efficient, and structural alternative to depth-heavy attention, enabling accurate 3D reconstruction within a lightweight architecture. The code will be made publicly at this https URL.
### Title:
          Validation-Gated Multi-Agent Governance for Online Adaptation of Thermal-Hydraulic Surrogate Models under Operating-Regime Shift
 - **Authors:** Doyeong Lim, Seungyoon Lee, In Cheol Bang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Multiagent Systems (cs.MA); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Artificial-intelligence surrogates can support second-by-second thermal-hydraulic forecasting, but models selected and frozen offline may become condition-locked once deployed outside their pretraining envelope. This study develops a guarded continual-adaptation framework for experimental thermal-hydraulic loop data in which role-separated agents - Monitor, Diagnosis, Adaptation, Safety-Auditor, and Orchestrator - diagnose error signatures, prioritize candidate model families, and review promotions, while deterministic champion-challenger gates and background shadow learning retain final authority over model replacement. Seven surrogate families were screened by blocked three-fold cross-validation, and a temporal Fourier neural operator was selected as the initial champion for 60-s-history-to-10-s-trajectory forecasting on two held-out transients, with three seeds per adaptive mode. Static deployment gave a channel-averaged MAE of 7.06 and a 56.8% warning-exceedance ratio; rule-based adaptation reduced MAE to 6.54, whereas shadow refresh alone remained close to Static. The MA-Full mode, in which the role-separated multi-agent council reviews every evaluated stream step, achieved the lowest mean error, 5.72, and 35.8% exceedance, corresponding to a 19.0% improvement over Static. Paired bootstrap intervals against Static excluded zero, although intervals among adaptive modes overlapped and the six paired units limit broad statistical claims. Validated promotions from the neural operator to Transformer and graph neural network indicate that logged, gate-controlled adaptation can support auditable surrogate evolution while deterministic gates retain deployment authority.
### Title:
          Multi-Modal Graph Neural Network with Transformer-Guided Adaptive Diffusion for Preclinical Alzheimer Classification
 - **Authors:** Jaeyoon Sim, Minjae Lee, Guorong Wu, Won Hwa Kim
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The graphical representation of the brain offers critical insights into diagnosing and prognosing neurodegenerative disease via relationships between regions of interest (ROIs). Despite recent emergence of various Graph Neural Networks (GNNs) to effectively capture the relational information, there remain inherent limitations in interpreting the brain networks. Specifically, convolutional approaches ineffectively aggregate information from distant neighborhoods, while attention-based methods exhibit deficiencies in capturing node-centric information, particularly in retaining critical characteristics from pivotal nodes. These shortcomings reveal challenges for identifying disease-specific variation from diverse features from different modalities. In this regard, we propose an integrated framework guiding diffusion process at each node by a downstream transformer where both short- and long-range properties of graphs are aggregated via diffusion-kernel and multi-head attention respectively. We demonstrate the superiority of our model by improving performance of pre-clinical Alzheimer's disease (AD) classification with various modalities. Also, our model adeptly identifies key ROIs that are closely associated with the preclinical stages of AD, marking a significant potential for early diagnosis and prevision of the disease.
### Title:
          Cross-Modality Feature Fusion Based on Structured State Space Duality for Multimodal Image Registration Network
 - **Authors:** Zhikang Li, Yan Wu, Xin Hu, Yi Dai, Ming Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In multi-modal image registration, the primary challenge lies in shared structural information extraction. Compared to Transformers, Structured State Space Duality (SSD) offers greater global structural feature extraction with higher efficiency during training and inference. Inspired by these advantages, we propose a novel algorithm for multi-modal image registration, named RegNetMamba-2. Our algorithm incorporates SSD into coarse-to-fine matching process to extract local and global structural features effectively. Firstly, SSD is applied in three different scales for multi-modal feature extraction in our network. To strengthen local representation, we pay more attention on foreground edge and structural information by feature scaling function of SSD. Secondly, for shared feature extraction of input images and multi-modal feature fusion in all scales, we propose cross-modality feature fusion model based on SSD, consisting of Cross-Modality feature Interaction (CMI) module and Multi-Scale feature Fusion (MSF) module. CMI module is designed for cross-modality feature extraction of each scale by SSD in cross form. MSF module is designed to employ a progressive upward fusion in feature-level to obtain fine features, consisting of multi-modal features in all scales. Following coarse-to-fine, the features in 1/8 scale from CMI and 1/2 scale from MSF are collected to calculate matching probability scores. Then we respectively establish matching process by correspondences of pixel-wise. Extensive experiments demonstrate that comparing with state-of-the-art deep-learning based algorithms, RegNetMamba-2 has achieved good effects in both performance and efficiency for multi-modal image registration on the following datasets: VIS-SAR (OSDataset), VIS-IR (LGHD/RoadSence) and VIS-NIR (RGB-NIR sense).
### Title:
          OpenEAI-Platform: An Open-source Embodied Artificial Intelligence Hardware-Software Unified Platform
 - **Authors:** Jinyuan Zhang, Luoyi Fan, Leiyu Wang, Yeqiang Wang, Yicheng Zhu, Cewu Lu, Nanyang Ye
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Embodied AI in the real world requires both accurate hardware and robust vision-language-action (VLA) policies. We present OpenEAI-Platform, a fully open-source platform that integrates a low-cost 6+1 degree-of-freedom (dof) robotic arm (OpenEAI-Arm) and a reproducible VLA model (OpenEAI-VLA). OpenEAI-Arm provides open-source mechanical designs for low manufacturing cost and compliant control methods for higher accuracy. OpenEAI-VLA builds on Qwen3-VL-4B and uses a Diffusion Transformer action head, and is trained in two stages with only open-source robot and multimodal datasets. Across four real-world manipulation tasks, OpenEAI-Arm outperforms two commercial 6+1-dof arms under the same policy, and OpenEAI-VLA achieves success rates comparable to the large-scale pretrained pi0 baseline with only limited pretraining data. We will release the full hardware designs, drivers, models, and training/data pipelines to support reproducible research and scalable data collection. Our codes, layouts, and models will be released after the paper is accepted.
### Title:
          Causal Evidence of Stack Representations in Modeling Counter Languages Using Transformers
 - **Authors:** Nishit Singh
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Formal languages have proven to be effective conduits to understand the inner mechanisms of transformers. Past work has shown that transformers trained on next token prediction over counter languages learn representations consistent with an underlying stack structure. Beyond representational analysis, this paper investigates the causal role of these representations. Linear probes are trained to predict the stack depth at each token from the model's hidden states, and a principal representation direction is extracted from the probe. Ablation of this direction from the model causes sequential accuracy to collapse to near 0%, providing strong empirical evidence that the stack representation is not just learned, but is causally necessary for model performance.
### Title:
          A unified multi-task framework enables interpretable chest radiograph analysis
 - **Authors:** Lijian Xu, Ziyu Ni, Xinglong Liu, Xiaosong Wang, Hongsheng Li, Shaoting Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While multimodal deep learning has advanced medical imaging analysis, existing black-box systems \textcolor{black}{may remain confined to isolated tasks, often overlooking} the trust-sensitive nature of clinical diagnosis as a multi-task process. We propose IMT-CXR (Interpretable Multi-task Transformer for Chest X-ray Analysis), a framework that emulates radiologists' diagnostic workflow through three evidence-driven stages: 1) Disease recognition; 2) Attribute characterization (e.g., size, location, severity quantification); 3) Evidence-integrated report generation with traceable decision pathways. The framework employs a unified transformer architecture optimized via medical-domain instruction tuning, sequentially executing four clinical tasks: multi-label disease classification, lesion localization, anatomical segmentation, and radiology report generation. Experimental validation demonstrates competitive performance on ten CXR benchmarks under direct inference and fine-tuning settings. In a blinded evaluation of 160 historical reports from four medical centers, three radiologists rated 66\% of AI-generated reports as comparable to or surpassing original clinical reports in diagnostic clarity, highlighting the framework's translational potential. By establishing traceable diagnostic pathways from anatomical findings to conclusions, this work bridges the gap between AI technical metrics and clinical utility, advancing trustworthy AI systems in medical imaging.
### Title:
          HonestAffinity: Leak-Aware Evaluation of Protein and Pocket Priors for Binding Affinity Prediction
 - **Authors:** Junhao Wei, Baili Lu, Zhenhong Peng, Wanyan Li, Zhirong Huang, Yanxiao Li, Yifu Zhao, Dexing Yao, Haochen Li, Xudong Ye, Sio-Kei Im, Yapeng Wang, Xu Yang
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sequence-based deep learning offers a scalable alternative to structure-based scoring for protein-ligand binding affinity prediction. However, progress is hard to interpret when architectural priors are evaluated on canonical PDBbind-style splits that leak similarity classes across folds. We present HonestAffinity, a compact 1D-input predictor to isolate two priors under a leak-aware protocol: frozen ESM-2 (650M) protein embeddings and a learned binary pocket-position marker. We evaluate a multi-scale convolutional/Transformer template in three variants: HonestAffinity-Pocket, HonestAffinity-NoPocket, and HonestAffinity-Pocket-NoESM. All three train on 11,513 LP-PDBBind complexes in ~3 GPU-hours. We benchmark against five baselines on the LP-PDBBind 3-tier no-leak hold-out, CASF-2016, and a CASF-2016 non-train subset. Our central finding is a split-conditioned reversal rather than a uniformly best prior: HonestAffinity-Pocket achieves the best mean Pearson R on validation and CASF-2016 splits, whereas HonestAffinity-Pocket-NoESM achieves the best mean Pearson R on every strict LP no-leak tier (test_cl1-cl3). Both the pocket marker and ESM-2 input improve performance on familiar splits but reduce Pearson R on strict no-leak tiers. We argue models should report paired canonical and leak-proof ablations, and that deployment-regime-matched variants better describe these reversals than a single default. Code and scripts are linked in the footnote; checkpoints will be released upon acceptance.
### Title:
          PrimeSVT: An Automated Memory-aware Pruning Framework with Prioritized Compression Policy for Spiking Vision Transformers
 - **Authors:** Rachmad Vidya Wicaksana Putra, Achyuta Muthuvelan, Alberto Marchisio, Muhammad Shafique
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The large sizes of Spiking Vision Transformers (SViTs) still hinder their embedded implementation, highlighting the need for model compression. State-of-the-art works compress SViT models through unstructured pruning, which needs specialized hardware accelerators for their specific sparsity patterns to maximize efficiency gains. Moreover, their manual approach requires a huge design time to find an appropriate pruning setting for each network, thus making this approach not scalable. To address this limitation, we propose PrimeSVT, a novel framework that performs automated memory-aware structured pruning on pre-trained SViT models, thereby maximizing their efficiency gains during inference amenable to widely-used computing architectures. To achieve this, PrimeSVT first sorts the SViT layers based on their sizes (i.e., number of parameters), identifies the targeted pruning layers based on their robustness under different pruning rates, then leverages this order for compressing the model layer-by-layer sequentially from the largest one to the smallest one (i.e., so-called prioritized compression policy), while considering the user-defined constraints (i.e., acceptable accuracy and memory saving). In each layer, PrimeSVT employs channel-wise filter pruning based on their L2-norm values to structurally remove the non-significant weights. Experimental results show that PrimeSVT saves 26.68% memory through automated single-shot pruning, while preserving accuracy within 3% (70.3% without fine-tuning and 72.9% with fine-tuning) from the original unpruned SViT model (73.3%), thus meeting the accuracy and memory constraints. These show that our PrimeSVT framework enables design automation for SViTs and their embedded implementation.
### Title:
          Rethinking the Role of Tensor Decompositions in Post-Training LLM Compression
 - **Authors:** Artur Zagitov, Alexander Miasnikov, Maxim Krutikov, Vladimir Aletov, Gleb Molodtsov, Nail Bashirov, Artem Tsedenov, Aleksandr Beznosikov
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Post-training compression is essential for deploying large language models (LLMs) under tight resource constraints. Tensor decompositions have emerged as a promising direction, offering compact parameterizations well suited to Transformer weight structures. However, existing studies evaluate these methods in narrow settings, leaving unclear whether tensorization is effective at large-scale deployment. We systematically evaluate tensor compression across dense and MoE architectures, establishing performance trade-offs grounded in both empirical analysis and theoretical analysis. We identify a fundamental mismatch between the shared subspaces assumed by tensor decompositions and the heterogeneous representations learned by modern LLMs, thereby delineating their practical limits and clarifying their viable role in large-scale deployment. The code is available at this https URL.
### Title:
          Analyzing Stream Collapse in Hyper-Connections: From Diagnosis to Mitigation
 - **Authors:** Ekaterina Alimaskina, Gleb Molodtsov, Aleksandr Beznosikov
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hyper-Connections (HC) replace the single Transformer residual stream with multiple streams, introducing a permutation symmetry over stream indices. We study how this symmetry is resolved in practice: whether streams specialize in a balanced way or exhibit dominant-stream usage. Using fine-grained diagnostics for HC-based language models, we trace how multi-stream representations are actually used. We find that after an early seeding stage, residual mixing often remains close to identity, limiting a core HC mechanism for exchanging information between streams. Moreover, both signal and interpretable features concentrate in a dominant stream, and the nominally multi-stream residual connection can underutilize its capacity, behaving closer to a single-stream residual pathway. Finally, we show that breaking symmetry at stream initialization reduces dominant behavior and improves performance across \textit{m}HC variants. Our code is publicly available.
### Title:
          TrAction: Action Recognition with Sparse Trajectories
 - **Authors:** Jan F. Meier, Felix B. Mueller, Alexander Ecker, Timo Lüddecke
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern action recognition models operate on memory- and compute-intensive dense RGB video volumes and frequently exploit appearance and background shortcuts, for example, predicting actions from objects or scenes instead of characteristic motion. We investigate an efficient alternative input modality that is largely free of such biases by construction: sparse point trajectories. To this end, we develop a simple transformer architecture for 2.5D trajectory-based recognition together with a masked-trajectory pretraining, which we show to substantially improve downstream action recognition accuracy. Despite using only a fraction of the dense RGB input, our method reaches 45% top-1 on Something-Something V2 and 54% on EPIC-Kitchens-100, and surpasses V-JEPA on time-reversal sensitivity. More importantly, we find trajectory features to be complementary to state-of-the-art appearance-based features. Fusing our pretrained model with DINOv2 and V-JEPA 2 improves top-1 accuracy on Something-Something V2 by 8.7 and 1.6 points, respectively. Code: this https URL
### Title:
          Unstable Poles Arising in AC Power Grid Subsystem Representations
 - **Authors:** Liam Hallinan, Ioannis Lestas
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent small-signal stability studies of AC grids have shifted towards analysing power systems as interconnections of subsystems and leveraging their input-output properties to derive scalable stability certificates. Two subsystem representations appear frequently in the literature: the PQ model, coupling powers to phase angle and voltage magnitude, and the IV model, coupling currents to voltages. In this paper, we derive both models without simplifying the bus or line dynamics and show that a loop transformation relates the two. One of the main results in the paper is to then show analytically that each representation may exhibit unstable poles depending primarily on the operating point (IV model) or the presence of high-frequency passive dynamics (PQ model). In particular, such unstable poles in the subsystems can occur even when the aggregate interconnection is stable and well-behaved. These effects are validated numerically, including a case study using the full-order dynamics of a synchronous generator with an exciter and transformer. Our results highlight that care must be taken when choosing a subsystem representation, as neglecting high-frequency dynamics or device operating points may obscure unstable poles that must be stabilised by the network interconnection and must be accounted for in system identification.
### Title:
          Efficient Transformer-Based Localized Patch Sampling for Choroid Plexus Segmentation in Multiple Sclerosis
 - **Authors:** Po-Jui Lu, Alessandro Cagol, Mario Ocampo-Pineda, Federico Spagnolo, Marina Mastantuono, Andreea-Alexandra Aldea, Jannis Müller, Özgür Yaldizli, Matthias Weigel, Lester Melie-Garcia, Roberta Magliozzi, Maria Pia Sormani, Ludwig Kappos, Jens Kuhle, Cristina Granziera
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Background: The lateral ventricle choroid plexus (LVCP) is gaining recognition as a key imaging biomarker for multiple sclerosis (MS) related to physical disability and neuroinflammation. Yet, manual segmentation of the LVCP is highly tedious, restricting its use in broad clinical trials and longitudinal assessments. This research aims to develop a SwinUNETR-driven pipeline that leverages targeted intra- and peri-ventricular small patch sampling to automatically segment the LVCP in MS from both standalone and multi-modal MRI inputs. Methods: We retrospectively assessed 3T MRI scans across three sets of data stemming from two separate MS-dominant cohorts (Dataset 1: n=177; Dataset 2: n=177; expanded test set: n=388). Our method employed a SwinUNETR architecture trained on 32x32x32 voxel patches, benchmarking it against the 3D UXNET model. The primary metric for evaluation was the Dice Similarity Coefficient (DSC), supplemented by computational demand (GFLOPs) and the 95th percentile Hausdorff Distance (HD95). Results: On the extended test set, the SwinUNETR model secured a mean DSC of 0.868 (95% CI: 0.863-0.872) with MPRAGE and FLAIR combined, showing a statistically significant gain over UXNET (DSC: 0.858 [95% CI: 0.853-0.862], p<0.0001). When restricted to standalone FLAIR inputs, the transformer-based approach sustained a high DSC of 0.863, while the spatial localization of UXNET worsened considerably (HD95: 1.86 vs. 3.00 mm). Importantly, the proposed framework lowered computational load by 99% (91.8 vs. 22,080 GFLOPs). By integrating localized patch sampling with a SwinUNETR architecture, this methodology offers an accurate, robust, and statistically superior alternative to current leading models for LVCP segmentation. Its vast reduction in computational cost makes it ideal for widespread implementation in clinical and research environments.
### Title:
          Learned Non-Maximum Suppression for 3D Object Detection
 - **Authors:** Timo Osterburg, Stefan Schütte, Torsten Bertram
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Post-processing is a critical stage in LiDAR-based 3D object detection, where dense and overlapping proposals must be filtered for compact and reliable perception. This work introduces two learned filtering modules that replace heuristic non-maximum suppression (NMS) by leveraging relations among detections. D2D-Rescore employs transformer-based detection-to-detection (D2D) attention, while GossipNet3D adapts the 2D GossipNet concept to 3D through localized message passing in bird's-eye view. A metric-aware matching strategy aligned with the nuScenes evaluation protocol ensures consistent training and validation behavior, improving overall detection performance. Both approaches improve mean average precision (mAP), nuScenes detection score (NDS), and true positive quality compared to CircleNMS, particularly for small and infrequent classes, while adding minimal computational overhead. These results demonstrate that learned, detection-level filtering can enhance 3D detector reliability without modifying the base network, offering a principled alternative to heuristic suppression. Code is available at this https URL .
### Title:
          A Comparison of Multirate Co-Simulation Techniques for Field-Circuit Coupled Problems
 - **Authors:** Michael Wiesheu, Sebastian Schöps, Idoia Cortes Garcia
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper compares three different multirate splitting approaches for the application on field-circuit coupled magnetoquasistatic simulations. For these methods, again three different variants for exchanging values between the field and circuit are tested, namely voltages, currents and flux correction terms. All scenarios are applied on two different benchmark problems, i.e. a coil inductor and transformer model coupled to different circuits. The convergence behavior of different time steppers (Implicit Euler and Trapezoidal Rule) is determined for all possible settings, and guidelines for practical applications are derived.
### Title:
          Text-to-Image Models Need Less from Text Encoders Than You Think
 - **Authors:** Nurit Spingarn, Noa Cohen, Tamar Rott Shaham, Tomer Michaeli
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-to-image models rely on text prompts as their primary interface to human intent. Prompts are encoded by a text encoder into embeddings that condition the image generation process. Beyond individual token meanings, text embeddings encode contextual information across the full prompt, such as compositionality and attribute binding. However, whether image models actually exploit this richer information remains underexplored. Here, we address the question: Which aspects of text representation are essential for image generation? We show that text-to-image diffusion transformer-based models commonly rely only on two relatively straightforward aspects of text representations: (i) the merging of adjacent tokens into a word representation, for words spanning multiple tokens, and (ii) word order, which is imprinted by the positional embedding of the text-encoder. To show this, we construct a new text embedding that encodes only individual word meanings and order but lacks any contextual information about the full prompt. We find that this bag of position-tagged words representation is sufficient to successfully guide image generation, achieving visual quality and text fidelity that are on par with full text embedding-guided generation. This demonstrates that, contrary to common belief, text-to-image models often do not use the rich information encoded in the text embedding beyond individual word meanings and word order. Instead, the decoding of complex linguistic structures is performed by the image model itself. Project webpage: this https URL
### Title:
          MARS: Multi-rate Aggregation of Recency Signals for Sequential Recommendation across Sparse and Dense Regimes
 - **Authors:** Zhenyu Yu, Shuigeng Zhou
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sequential recommenders weight historical interactions either through positional self-attention as in Transformers or through a single implicit decay schedule as in State-Space Models. Neither makes the multi-scale temporal structure of real user behaviour explicit. We propose MARS, an encoder-agnostic aggregation operator that consumes real timestamps and produces K summaries emphasising distinct recency scales, fused by a context-adaptive gate. MARS adds at most 6% parameters and runs in $\mathcal{O}(LdK)$ time. MARS adapts to data density by automatically selecting between two encoder instantiations: MARS-T (Transformer) for sparse data and MARS-M (Mamba) for dense data, based on the average sequence length of the training set. On five public benchmarks against ten Transformer- and Mamba-based baselines under a unified RecBole protocol, MARS attains the best HR@10 on every benchmark, with mean relative gain +19.7% over the strongest content-only Transformer baseline on sparse data (reaching +36.2% on Games) and +3.2% HR@10 / +0.9% NDCG over SIGMA on dense ML-1M at 42% fewer MFLOPs, occupying the accuracy-efficiency Pareto frontier across the data-density spectrum. A backbone-only ablation isolates the marginal contribution of MARS at +4% to +19% HR@10 on sparse data and motivates the dual-instantiation design. The code is included in the supplementary material.
### Title:
          Expert-Aware Causal Tracing of Factual Recall in Sparse MoE Language Models
 - **Authors:** Yuetian Lu, Ali Modarressi, Yihong Liu, Hinrich Schütze
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Causal tracing of factual recall has been studied predominantly in dense transformer language models, where interventions localize information flow to layers or feed-forward modules. Sparse mixture-of-experts (MoE) language models introduce a sharper question: when a factual prediction is mediated by a routed MoE block, which routed expert contributions matter? We formulate expert-aware causal tracing for sparse MoE language models. Using CounterFact facts, we first corrupt the model's factual preference by adding noise to subject-token embeddings, and then test whether clean MoE-block outputs or clean expert-level updates restore the true-vs-foil logit contrast. For Qwen3-30B-A3B-Base, a layer sweep selects and validates layer 44, and expert-level tracing identifies L44E069 as an expert repeatedly selected in the clean run whose held-out patch outperforms other active same-layer expert patches. For Mixtral-8x7B-v0.1, layer-level tracing validates a mid-layer signal, but the signal is not localized to the selected singleton expert; a coalition check instead recovers it with routed multi-expert updates. These results suggest that MoE factual tracing can be made expert-aware, while also showing that expert-level localization is model- and protocol-dependent rather than universal.
### Title:
          LiveBand: Live Accompaniment Generation in the Audio Domain
 - **Authors:** Marco Pasini, Javier Nistal, Mathias Rose Bjare, Stefan Lattner, George Fazekas
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present LiveBand, a real-time system that generates high-fidelity music accompaniments to live audio input, respecting strict causal constraints. Our method trains a causal transformer generator in the continuous latent space of a pre-trained causal audio autoencoder, using adversarial sequence-level supervision from a discriminator. At each timestep, the generator receives only the causally available mix context and Gaussian noise, and predicts accompaniment latents without access to future mix frames or ground-truth target latents. Training is performed in a single parallel forward pass under causal masking, while streaming inference proceeds autoregressively with a rolling attention state. The model's training and inference computations are matched by design, eliminating teacher forcing and the associated exposure bias. On a multi-instrument music accompaniment benchmark, LiveBand improves over prior work on objective measures of audio quality, beat alignment, and mix adherence, while enabling real-time streaming generation without lookahead into the future on consumer hardware.
### Title:
          Leveraging BART to Assess CS1 C++ Programming Assignments using Rubric-based Criteria
 - **Authors:** Kelsey Rainey, Jesse Roberts
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper investigates rubric-aware, multitask fine-tuning of transformer models for automated grading of introductory C++ programming assignments, with the goal of producing grade predictions that better reflect instructor grading behavior than general-purpose LLMs. Using multi-semester CS1 data, student submissions are paired with numeric scores, letter-grade buckets, and assignment rubrics, then preprocessed into unified sequences for transformer input. A BART encoder-decoder with LoRA adaptation is trained to jointly predict numeric grades and grade buckets, augmented with a distribution-matching term to align predicted and empirical grade distributions, an evaluation dimension often overlooked in prior work. Experiments compare single-task and multitask training, hard one-hot versus fuzzy and boundary-based soft labels, and rubric versus no-rubric conditions, with additional T5 and pairwise-pretrained variants. Results show that multitask BART with boundary-based soft labels and rubric context achieves lower mean absolute error and stronger grade-distribution alignment than single-task, hard-label, or code-only baselines. Fully fine-tuned T5 further improves distributional fidelity, while pairwise pretraining reduces numeric error at the cost of minority-class sensitivity. Collectively, the findings suggest that calibration-aware, rubric-guided training produces more instructor-like grading behavior than accuracy-optimized alternatives.
### Title:
          Dynamic Short Convolutions Improve Transformers
 - **Authors:** Oliver Sieberling, Bharat Runwal, Rameswar Panda, Yoon Kim
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers have become the dominant architecture for large language models, largely due to the scalability and flexibility of attention, feed-forward layers, residual connections, and normalization. This paper introduces dynamic short convolutions as an additional neural network primitive for improving Transformers. Unlike static short convolutions, dynamic convolutions use input-dependent filters, which preserves the locality bias of convolution while increasing expressivity. Motivating experiments show that applying dynamic short convolutions to key, query, and value representations improves performance on challenging associative recall tasks compared with static convolutional variants. Across language-modeling experiments ranging from 150M to 2B parameters, dynamic convolutions consistently outperform standard Transformers and Transformers augmented with static short convolutions. Fitting scaling laws indicates a 1.33$\times$ compute advantage over compute-matched Transformers when dynamic convolutions are applied to the key, query, and value vectors, and a 1.60$\times$ advantage when adding dynamic convolutions after every linear layer. Dynamic convolutions also offer improvements on linear RNNs (Mamba-2/Gated DeltaNet) and mixture-of-experts architectures. We make these gains practical with custom Triton kernels that enable efficient training with a manageable end-to-end slowdown. These results suggest that dynamic short convolutions are a scalable, hardware-efficient, and expressive primitive for advancing Transformer-based language models.
### Title:
          DyaPlex: Full-Duplex Speech-Motion Model for Dyadic Interaction
 - **Authors:** Koki Nagano, Hongyu Liu, Seonwook Park, Tianye Li, Amrita Mazumdar, Christian Jacobsen, Shengze Wang, Michael Stengel, Rajarshi Roy, Ka Chun Cheung, Simon See, Shalini De Mello
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present DyaPlex, a streaming, full-duplex speech-and-motion model designed for dyadic interaction. To capture the continuous and reciprocal nature of human communication, this full-duplex capability empowers the agent to simultaneously perceive and generate both speech and physical motion in a streaming fashion. At its core, our method leverages the strong priors of a foundational full-duplex speech model and integrates a novel motion pathway, thereby achieving fully synchronized multi-modal interaction. Specifically, we design a dual-tower Transformer architecture that preserves the zero-shot conversational reasoning of a frozen base speech model while constructing a deeply coupled, streaming motion pathway. By introducing a unified dyadic token interleaving mechanism and guiding cross-attention via a time-aligned speech-motion RoPE, our model effectively aligns autoregressive motions with rich latent speech features. Trained on the 4,000-hour Seamless Interaction dataset, our model effectively captures cross-speaker dependencies and establishes new state-of-the-art performance across both monadic and dyadic human interaction benchmarks.
### Title:
          An Attention-Based Denoising Model for Diffusion Weighted Imaging
 - **Authors:** Prithviraj Verma, Pawan Kumar, Chandan Deshani, Prasun Chandra Tripathi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion-weighted imaging (DWI) is used for whole-body cancer screening, but it typically requires a long acquisition time. When the scan time is reduced, the image quality often suffers, leading to increased noise in the scans. Magnitude reconstruction in DWI introduces signal-dependent Rician noise, which makes denoising more challenging for conventional convolution-based methods. To address this limitation, we propose a noise-aware attention-driven denoising framework that integrates hierarchical Swin Transformer window attention with transformer-based multi-dimensional gated refinement for DWI restoration. The model incorporates explicit noise-level conditioning and residual reconstruction to enable adaptive suppression of heteroscedastic noise across a wide range of corruption levels. Experimental evaluation on corrupted DWI scans demonstrates strong restoration performance. Our model achieves a mean PSNR of 33.69~dB and SSIM of 0.8539 across noise levels from 1\% to 15\%, while maintaining stable behavior under severe noise conditions. These results indicate that attention-guided contextual modeling combined with channel-adaptive refinement provides a robust and generalizable solution for DWI denoising.
### Title:
          Formalizing the Binding Problem
 - **Authors:** Lianghuan Huang, Yihao Li, Saeed Salehi, Yingshan Chang, Ansh Soni, Konrad P. Kording
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Neurons and Cognition (q-bio.NC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Representations of the world, arguably, contain information about features (e.g. something is blue, something is a circle) but also information about which features are part of the same object (e.g. the circle is blue), which we call binding information. Any system with the ability to understand scenes with multiple objects must be able to solve the binding problem: it needs to know which features belong together. However, despite work showing that Vision Transformers (ViTs) know which patches belong together, it is not known whether current deep learning models learn to exhibit binding information, i.e., for features. We may believe that there is not much binding information, after all misattributing features to wrong objects is a common failure of ViT-based architectures, especially in scenes with objects sharing features. Here we formalize the binding problem with an information-theoretic approach, and introduce a probing method to measure binding information in model representations. We perform experiments on ViTs, measuring binding from different components of the architecture, such as the image summary token [CLS] or the spatial tokens. We use datasets with different binding challenges, such as feature sharing, occlusion, and natural features, while comparing the performance of several pre-trained ViTs. Overall, our research demonstrates binding as a key ingredient to strong visual recognition and reasoning.
### Title:
          Humanoid-GPT: Scaling Data and Structure for Zero-Shot Motion Tracking
 - **Authors:** Zekun Qi, Xuchuan Chen, Dairu Liu, Chenghuai Lin, Yunrui Lian, Sikai Liang, Zhikai Zhang, Yu Guan, Jilong Wang, Wenyao Zhang, Xinqiang Yu, He Wang, Li Yi
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Humanoid-GPT, a GPT-style Transformer with causal attention trained on a billion-scale motion corpus for whole-body control. Unlike prior shallow MLP trackers constrained by scarce data and an agility-generalization trade-off, Humanoid-GPT is pre-trained on a 2B-frame retargeted corpus that unifies all major mocap datasets with large-scale in-house recordings. Scaling both data and model capacity yields a single generative Transformer that tracks highly dynamic behaviors while achieving unprecedented zero-shot generalization to unseen motions and control tasks. Extensive experiments and scaling analyses show that our model establishes a new performance frontier, demonstrating robust zero-shot generalization to unseen tasks while simultaneously tracking highly dynamic and complex motions.
## Keyword: autonomous driving
### Title:
          GeoDrive-Bench: Benchmarking Region-Specific Multimodal Reasoning in Autonomous Driving
 - **Authors:** Yingzi Ma, Chaowei Xiao, Ming Jiang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language models (VLMs) for autonomous driving have shown promising performance, but their ability to handle region-specific traffic rules remains underexplored, raising uncertainties about their deployment across diverse global settings. We therefore introduce GeoDrive-Bench, a novel benchmark that enables the systematic investigation of VLMs' geo-culturally grounded driving reasoning. We curated 5,053 human-validated multiple-choice QA pairs across six countries covering diverse driving cultures. Specifically, we emphasize four driving tasks: perception, prediction, planning, and region reasoning. Each question requires models to infer the correct driving behavior from visual evidence and local traffic conventions without explicit country labels. Beyond evaluation, we further design a distillation algorithm that injects region-specific traffic-rule knowledge into the internal representations of VLMs, enabling models to better align visual scene understanding with local driving policies. Experiments on nine state-of-the-art VLMs show substantial performance variations across geo-driving cultures for each task, while our proposed baseline models exhibit improved geo-cultural reasoning across regions. These results suggest that current VLMs still lack robust region-aware driving intelligence and highlight GeoDrive-Bench as a diagnostic and training-oriented testbed for deployable autonomous driving foundation models.
### Title:
          ATLAS: A Large-Scale Evaluation Benchmark for Adversarial LiDAR Perception
 - **Authors:** Mellon M. Zhang, Siddhant Panse, Zimo Fan, Akshal Dhal, Rishit Sarkar, Glen Chou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving perception is typically evaluated on clean benchmark data, yet real-world deployment requires robustness to rare, structured, and potentially adversarial sensor anomalies. This gap is especially critical for LiDAR, where external actors can physically manipulate the sensing process to induce black-box perception failures without accessing the model. Existing LiDAR benchmarks provide little visibility into this failure mode. Prior adversarial LiDAR studies have largely centered on attack hardware, geometric and algorithmic defenses, and early-generation detectors, leaving the robustness of modern perception systems unexplored. To address this evaluation gap, we introduce ATLAS (Adversarial Temporal LiDAR Attack Suite), the first large-scale, physically grounded evaluation benchmark for LiDAR perception models under black-box sensor attacks, simulating the two primary attack modes -- point injection and point removal -- across real driving sequences. Evaluating a broad cross-section of current state-of-the-art LiDAR perception models, ATLAS reveals a surprising robustness asymmetry: models with stronger performance on standard benchmarks tend to better withstand removal attacks, yet are actually more vulnerable to injection attacks than weaker models. We trace this vulnerability to standard object database sampling augmentations, revealing how current training practices can induce architecture-agnostic robustness failures, and study initial directions for mitigating both attack modes. We release the ATLAS generation code to support extensible, reproducible evaluations as attack capabilities evolve, helping make black-box sensor robustness an explicit consideration in future LiDAR perception development.
### Title:
          The Road Ahead in Autonomous Driving: The KITScenes Multimodal Dataset
 - **Authors:** Richard Schwarzkopf, Fabian Immel, Alexander Blumberg, Jonas Merkert, Nils Rack, Kaiwen Wang, Fabian Konstantinidis, Julian Truetsch, Carlos Fernandez, Annika Bätz, Kevin Rösch, Marlon Steiner, Willi Poh, Yinzhe Shen, Royden Wagner, Felix Hauser, Dominik Strutz, Jaime Villa, Gleb Stepanov, Holger Caesar, Ömer Şahin Taş, Frank Bieder, Jan-Hendrik Pauls, Christoph Stiller
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing autonomous driving datasets have enabled major progress, but fall short in sensor fidelity, map completeness, or geographic diversity. We present KITScenes Multimodal, a European dataset built around high-fidelity sensors and maps. Our fully synchronized sensor suite combines high-resolution global-shutter cameras, long-range lidar beyond 400m, 4D imaging radar, and redundant GNSS/INS localization. Our HD maps are, to our knowledge, the most complete of any sensor dataset, validated through autonomous driving trials on open-source software. For the first time in a public dataset, all driving-relevant traffic elements, such as traffic lights, are mapped in 3D to a reprojection-accurate level with full topological connectivity. Recorded in cities with irregular street layouts and mixed traffic modes, our dataset complements existing datasets by broadening the available geographic diversity. We also introduce four benchmarks, each advancing spatial learning for embodied AI: online HD map construction, long-range depth estimation, novel view synthesis, and end-to-end driving. Project page: this https URL
### Title:
          Towards Compact Autonomous Driving Perception with Balanced Learning and Multi-sensor Fusion
 - **Authors:** Oskar Natan, Jun Miura
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a novel compact deep multi-task learning model to handle various autonomous driving perception tasks in one forward pass. The model performs multiple views of semantic segmentation, depth estimation, light detection and ranging (LiDAR) segmentation, and bird's eye view projection simultaneously without being supported by other models. We also provide an adaptive loss weighting algorithm to tackle the imbalanced learning issue that occurred due to plenty of given tasks. Through data pre-processing and intermediate sensor fusion techniques, the model can process and combine multiple input modalities retrieved from RGB cameras, dynamic vision sensors (DVS), and LiDAR placed at several positions on the ego vehicle. Therefore, a better understanding of a dynamically changing environment can be achieved. Based on the ablation study, the model variant trained with our proposed method achieves a better performance. Furthermore, a comparative study is also conducted to clarify its performance and effectiveness against the combination of some recent models. As a result, our model maintains better performance even with much fewer parameters. Hence, the model can inference faster with less GPU memory utilization. Moreover, the result tends to be consistent in 3 different CARLA simulation datasets and 1 real-world nuScenes-lidarseg dataset. To support future research, we share codes and other files publicly at this https URL.
### Title:
          NVIDIA OmniDreams: Real-Time Generative World Model for Closed-Loop Autonomous Vehicle Simulation
 - **Authors:** NVIDIA: Aarti Basant, Amlan Kar, Despoina Paschalidou, Fangyin Wei, Francesco Ferroni, Guillermo Garcia Cobo, Haithem Turki, Huan Ling, Jaewoo Seo, James Lucas, Jay Zhangjie Wu, Jialiang Wang, Jonathan Lorraine, Jun Gao, Kai He, Katarina Tothova, Kevin Xie, Michał Tyszkiewicz, Qi Wu, Riccardo de Lutio, Ruilong Li, Sanja Fidler, Seung Wook Kim, Tianchang Shen, Tianshi Cao, Tobias Pfaff, William Lew, Xindi Wu, Xuanchi Ren, Yifan Lu, Yuxuan Zhang, Zan Gojcic, Zian Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As autonomous vehicle capabilities advance, the safe evaluation of driving policies in long-tail scenarios remains a critical bottleneck. In closed-loop simulation, the driving policy model actively interacts with the environment, where its actions dynamically update the simulator state and directly influence the next set of generated sensor observations. While recent reconstruction-based neural simulators offer photorealism, they are fundamentally constrained by their initial captured data and struggle to generalize to highly dynamic or novel scenes. To overcome these limitations, we introduce OmniDreams, a foundation generative world model mid- and post-trained from the Cosmos diffusion model to autoregressively generate action-conditioned videos in real time. By leveraging the rich visual priors of Cosmos and mid- and post-training on 21k hours of driving scenarios, OmniDreams synthesizes complex, unobserved phenomena that are hard for traditional simulators to capture, such as extreme weather and unpredictable dynamic agent behaviors. Crucially, it autoregressively conditions its photorealistic sensor generation on past frames, the current simulator state, and immediate driving actions. Deployed in a closed-loop system with the Alpamayo 1 policy model and AlpaSim orchestrator, OmniDreams acts as a highly responsive, reactive environment, providing a scalable and comprehensive solution for training and evaluating next-generation autonomous driving policies. We additionally show preliminary results indicating that a world-action model (WAM) post-trained from OmniDreams achieves strong performance on the Physical AI Autonomous Vehicles NuRec dataset, surpassing the VLA-based Alpamayo 1.5 research policy model while using only 1/5 the total parameters. These results highlight the potential for a real-time world model like OmniDreams to also serve as a backbone for policy architectures.
### Title:
          SRENet: Spectral Re-Entry Network for Point Cloud Action Recognition
 - **Authors:** Qiuxia Wu, Jiarui Lan, Wenxiong Kang, Zhiyong Wang, Kun Hu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recognizing human actions from point cloud sequences is critical for 3D perception driven applications such as autonomous driving and human-computer interaction. However, the irregular structure and temporal inconsistency of point clouds pose unique challenges for spatio-temporal representation learning, especially in capturing both global motion context and fine-grained temporal dynamics. We propose SRENet, a spectral-aware framework designed to explicitly learn both global context and fine-grained temporal dynamics of motion from a frequency perspective for action recognition. SRENet introduces a Spectral Decomposition Block (SDeBlock) that performs wavelet-based analysis along temporal and spatial axes, disentangling features into low- and high-frequency components with frequency-specific attention. To recover residual dynamics and re-align temporal frequency structures distorted during semantic fusion, a Spectral Re-entry Block (SReBlock) performs secondary temporal decomposition. Furthermore, a spectral-aware learning strategy is devised to enhance discriminability in both frequency subspaces via contrastive loss and a curriculum schedule that gradually shifts focus from low- to high-frequency spaces in line with coarse to detailed motion patterns. Extensive experiments on MSR-Action3D, NTU-RGBD and NTU-RGBD120 demonstrate that SRENet achieves state-of-the-art performance, validating the effectiveness of frequency modeling in point cloud-based action understanding.
### Title:
          Bridging Predictive Uncertainty and Safe Action: Sample-Conditioned Differentiable Planning for Autonomous Driving
 - **Authors:** Chengzhen Meng, Pei Liu, Zhiyu Huang, Chen Lv, Jun Ma
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Complex, dynamic, and interactive driving environments pose significant challenges for autonomous driving, primarily due to the pervasive uncertainty of surrounding traffic. A fundamental bottleneck in current systems is the disconnect between highly expressive uncertainty modeling and interpretable, safe motion planning. In this paper, we propose a novel sample-conditioned differentiable planning framework that bridges this gap by explicitly incorporating diffusion-generated future trajectories into the optimization process. Rather than compressing predictions into a single deterministic future or relying on black-box end-to-end architectures, our approach leverages a conditional diffusion model to generate a diverse set of plausible future scenarios. Crucially, these samples are directly fed into a differentiable planner, which explicitly mitigates predictive uncertainty via an empirical Conditional Value-at-Risk (CVaR) tail-risk constraint. This allows the planner to optimize a physically interpretable trajectory that is robust to rare yet safety-critical interactions. Furthermore, we introduce a directed graph representation for scene context that yields substantial improvements in both predictive effectiveness and computational efficiency. Validated through extensive open-loop and closed-loop evaluations on the Waymo Open Motion and Argoverse 2 datasets, our framework significantly outperforms state-of-the-art baselines in safety, efficiency, and ride comfort.
### Title:
          TASE: Truncation-Aware Semantic Embeddings for 3D Scene Understanding and Editing
 - **Authors:** Tim-Felix Faasch, Jochen Kall, Lucas Nunes, Jens Behley, Cyrill Stachniss
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-fidelity semantic 3D scene representations are crucial for numerous applications, including robotics, autonomous driving, and simulation. Beyond this, the ability to edit such representations enables developers to adapt these applications more easily to specific target scenarios. Current approaches provide limited support for controllable editing. We introduce TASE, a method that projects pretrained 2D semantic features into a truncation-aware embedding space to enable flexible 3D scene editing. Our method explicitly optimizes a feature space in which progressively reducing feature channels yields increasingly abstract semantic representations, while retaining more channels preserves fine-grained detail. Additionally, we improve multi-view consistency of the features using a scale- and translation-equivariance loss. The resulting truncation-aware embedding space enables text-driven edits to 3D scenes, providing explicit control over how strongly edits adhere to the original scene content and allowing more substantial modifications than prior methods. Moreover, we propose a finetuning stage for the editing diffusion model to mitigate artifacts caused by geometric changes. Experimental results demonstrate competitive performance in 3D scene editing, substantially outperforming prior methods on edits involving large geometric modifications.
### Title:
          UnsOcc: 3D Semantic Occupancy Prediction in Unstructured Scene via Rendering Fusion
 - **Authors:** Ye Wu, Ruiqi Song, Baiyong Ding, Nanxin Zeng, Junjie Cheng, Yunfeng Ai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unstructured scenes present unique challenges for autonomous driving, as irregular obstacles and sparse scene layouts undermine the effectiveness of traditional perception methods such as 3D object detection. 3D semantic occupancy prediction has emerged as a prominent focus due to its ability to provide dense spatial representations by assigning semantic labels to individual voxels in 3D space. However, directly applying 3D semantic occupancy prediction to unstructured scenes remains challenging because scene sparsity hinders effective cross-modal fusion and the more severe long-tail distribution in these scenarios further degrades prediction performance. To validate the effectiveness of our approach, we construct a dedicated dataset of unstructured scenes collected from open-pit mines. Based on this, we propose UnsOcc, a multi-modal 3D semantic occupancy prediction framework that improves robustness in unstructured environments. At its core, we introduce a rendering-based fusion module, RenderFusion, which enhances cross-modal feature alignment through bidirectional rendering supervision. Furthermore, we propose GSRefinement, a detail-aware auxiliary supervision method based on Gaussian Splatting that projects sparse 3D occupancy predictions into dense 2D semantic segmentation maps, enabling effective supervision for long-tail categories. Extensive experiments on both the open-pit mine dataset and the nuScenes dataset demonstrate that our method significantly outperforms existing state-of-the-art approaches.
### Title:
          CANMOT: Class-Aware Noise Modeling for Multi-Object Tracking in Autonomous Driving
 - **Authors:** Timo Osterburg, Stefan Schütte, Torsten Bertram
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Kalman filter (KF)-based multi-object tracking (MOT) remains a strong baseline for autonomous driving due to its strong performance, computational efficiency and interpretability. In most practical systems, the process noise and measurement noise covariances are defined globally and shared across object classes, presuming identical uncertainty characteristics across heterogeneous traffic participants. This work revisits this assumption and proposes CANMOT, a class-aware and object-aligned noise modeling framework for KF-based 3D MOT. Class-specific diagonal process and measurement covariance matrices are introduced and optionally expressed in the object coordinate frame to preserve longitudinal-lateral anisotropy. Systematic experiments on the nuScenes benchmark show that class-aware and object-aligned noise modeling improves tracking performance and substantially reduces identity switches compared to state-of-the-art (SotA). In addition, the consistency of the estimated uncertainty is analyzed using the Average Normalized Estimation Error Squared (ANEES) and $\chi^2$-based violation tests. The results reveal severe overconfidence in standard KF-based MOT baselines. While the proposed formulation improves calibration without modifying the underlying filtering framework, it still exhibits substantial inconsistency, highlighting the need for further research in this area. Code is available at this https URL.
### Title:
          EvoDrive: Pareto Evolution for Safety-Critical Autonomous Driving via Self-Improving LLM Agents
 - **Authors:** Tong Nie, Yuewen Mei, Yihong Tang, Junlin He, Jie Deng, Jian Sun, Wei Ma
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generating safety-critical scenarios is essential for validating and improving autonomous driving systems, yet it inherently requires maximizing adversariality to expose failures while preserving realism. Existing methods usually manage this trade-off with handcrafted heuristics, confining generation to known priors and overlooking underexplored patterns. While recent open-ended agentic evolution can push this limit, unconstrained general agents lack strict simulator grounding and tend to collapse the multi-objective tension into single-scalar maximization. Here we present EvoDrive, the first automated, LLM-based agentic evolution framework for multi-objective scenario generation. EvoDrive employs a simulator-grounded actor-critic architecture where a memory-driven actor iteratively proposes improvements to the generators and critics filter out implausible candidates, and a self-evolving world evaluator routes promising proposals to optimize simulation budgets. EvoDrive further maintains a Pareto archive of evaluated candidates to preserve diverse attack-realism trade-offs and guide future evolution via simulation feedback. Benchmark results on MetaDrive and CARLA show that EvoDrive not only significantly expands the Pareto frontier across various generators, but also produces valuable scenarios for policy training.
### Title:
          Face versus Body Tracking for Human-Robot Interaction: An Egocentric Dataset
 - **Authors:** Jessica Wenninger, Gabriel Skantze
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 To enable meaningful human-robot interaction (HRI), a robot must continuously assess engagement by consistently tracking users over time. State-of-the-art computer vision models, however, are heavily optimized for surveillance or autonomous driving. A social robot faces distinct egocentric challenges, such as humans bouncing, obstructing each other, or leaving the frame. Frequent identity switches (IDSW) cause the robot to lose its footing mid-conversation. To address this, we introduce a novel, custom-annotated egocentric dataset collected via the Furhat robot to capture complex social dynamics. We present a systematic evaluation isolating detection errors from tracking logic, comparing face versus body tracking, and assessing the impact of extended spatial memory and appearance re-identification (ReID). Results indicate that increasing spatial memory mitigates prolonged occlusions but fails on complex dynamic events. Integrating ReID resolves complex switches but exhibits opposing effects: it substantially improves body tracking stability, yet causes facial IDSW to spike due to profile angle sensitivity. Ultimately, our optimized pipeline reduces IDSW by 49\%, mitigating interaction breakdowns. Because standard benchmarks lack dense, close-quarter occlusions, this work highlights the critical need for natively captured social dynamics to truly validate HRI perception models.
### Title:
          OVO-S-Bench: A Hierarchical Benchmark for Streaming Spatial Intelligence in Multimodal LLMs
 - **Authors:** Yifei Li, Pengyiang Liu, Yuhang Zang, Zhongyue Shi, Qi Fu, Hongye Hao, Jiwen Lu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal agents in robotics, AR, and autonomous driving must reason about places and layouts from continuous egocentric streams, often using evidence outside the current view. Existing benchmarks either evaluate offline over full videos or target events rather than spatial structure. We introduce OVO-S-Bench, a fully human-annotated benchmark for streaming spatial intelligence, comprising 1,680 questions over 348 source videos. Annotation involves 12 trained annotators, each also serving as a blind cross-reviewer, across roughly 804 person-hours of multi-round quality assurance. Each question carries a query timestamp and an evidence interval, and at evaluation, the model sees only the prefix preceding the query. Questions span four levels of increasing abstraction: instantaneous egocentric perception, spatiotemporal context tracking, spatial simulation and reasoning, and allocentric mapping. Across 38 proprietary and open-source MLLMs, Gemini-3.1-Pro trails human experts by 27 points, 59.2 vs. 86.6, with allocentric mapping as the dominant bottleneck. Notably, streaming and spatially fine-tuned MLLMs underperform their own backbones. We further find that chain-of-thought reasoning amplifies spatial errors when ungrounded in the stream. By exposing these limitations, OVO-S-Bench establishes a demanding testbed for next-generation streaming spatial MLLMs.
### Title:
          PatchScene: Patch-based Voxel Diffusion for Large-Scale Scene Completion
 - **Authors:** Qingdong Xu, Jiajun Zhu, Shilin Zhu, Xinjing He, Chao Lu, Huanran Wang, Jiyao Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose PatchScene, a novel diffusion-based framework for large-scale LiDAR scene completion. Unlike existing methods that rely on global latent representations or dense voxel grids, PatchScene adopts a patch-based voxel diffusion paradigm that explicitly generates fine-grained geometry within localized 3D regions. To ensure coherent reconstruction at both spatial and temporal scales, we introduce a confidence-guided spatio-temporal fusion mechanism that integrates overlapping patches and adjacent frames in a unified generative process. Furthermore, we design an Annular-Flow diffusion strategy that leverages the radial density pattern of LiDAR scans to progressively propagate high-fidelity information from near-range to far-range regions, enabling spatially unbounded scene completion. Extensive experiments on the SemanticKITTI benchmark demonstrate that PatchScene achieves state-of-the-art performance across all standard metrics, surpassing previous approaches in both geometric accuracy and temporal consistency. Remarkably, the model trained on 20 m LiDAR ranges generalizes effectively to 50 m scenes without retraining, highlighting its strong scalability and generalization capability for real-world autonomous driving applications.
