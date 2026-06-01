# Showing new listings for Monday, 1 June 2026
## Keyword: SLAM
### Title:
          CoMo3R-SLAM: Collaborative Monocular Dense SLAM with Learned 3D Reconstruction Priors for Outdoor Multi-Agent Systems
 - **Authors:** Zhihao Cao, Qi Shao, Shuhao Zhai, Feng Tian, Anh Nguyen, Hesheng Wang, Baoru Huang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Collaborative dense SLAM is essential for multi-robot teams to achieve scalable and consistent 3D perception across large-scale outdoor environments. Existing systems typically depend on depth sensors, incurring significant payload, power, and calibration costs. Monocular RGB cameras are a lightweight alternative, but collaborative monocular dense SLAM remains difficult due to scale ambiguity, unreliable inter-agent data association, especially in outdoor scenes where low overlap and repetitive structures make traditional feature matching unreliable, motivating robust geometric information. We propose CoMo3R-SLAM, the first collaborative monocular dense RGB SLAM system that leverages robust learned feed-forward 3D reconstruction priors for outdoor multi-agent mapping. Each agent runs a prior-guided front-end for real-time tracking and local dense fusion, while a coordinator performs dense pointmap matching for cross-agent verification, closed-form Sim(3) gauge synchronization, and GPU-accelerated global bundle adjustment with segment-level depth optimization. Requiring neither depth sensors nor parametric intrinsics, our system produces robust cross-agent constraints and globally consistent metric maps from monocular RGB alone. On Tanks and Temples and Waymo sequences, CoMo3R-SLAM achieves the best ATE on three of four Tanks and Temples scenes and competitive Waymo accuracy, matching or exceeding state-of-the-art RGB-D methods while running online at 8 FPS.
### Title:
          Exploiting Chordal Sparsity for Globally Optimal Estimation with Factor Graphs
 - **Authors:** Avinash Subramanian, Connor Holmes, Timothy D. Barfoot, Frank Dellaert, Frederike Dümbgen
 - **Subjects:** Subjects:
Robotics (cs.RO); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust and efficient state estimation is crucial for perception, navigation, and control in robotics. State estimation problems are conveniently modeled using the factor-graph framework as enabled by modern software packages such as GTSAM or g2o. However, the standard solvers included in such frameworks are local and may converge to poor local minima, posing significant safety concerns. Conversely, techniques based on convex relaxations have been shown to provide a means of globally solving or certifying many state estimation problems. However, these relaxations 1) often require substantial effort to formulate, and 2) may incur significantly higher cost compared to efficient local solvers, as they require solving a large semidefinite program (SDP). In this work, we address both shortcomings by 1) creating a new procedure within the GTSAM framework for automatically constructing convex SDP relaxations for any factor graphs with common factor and variable types, and by 2) exploiting the Bayes tree constructions native to GTSAM to decompose the SDP problem, leading to significant speedup in solver time for chordally sparse problems. We demonstrate the favorable scaling of this structure-exploiting global estimator compared to standard local solvers for two case studies: A 3D pose-graph SLAM problem with a ring factor graph and a 2D localization problem with a chain factor graph. The software framework is available at this https URL.
### Title:
          Triangle Splatting SLAM
 - **Authors:** Nicholas Fry (1 and 2), Eric Dexheimer (2), Kirill Mazur (2), Paul H. J. Kelly (1 and 2), Andrew J. Davison (2) ((1) Software Performance Optimisation Group, Imperial College London, (2) Department of Computing, Imperial College London)
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a dense RGB-D SLAM system using differentiable triangles as the 3D map representation. While 3D Gaussian Splatting has emerged as the leading method for novel-view synthesis, triangles remain the standard primitive for traditional rendering hardware, game engines, and downstream tasks requiring explicit geometry such as simulation, collision, and editing. Recent offline methods have demonstrated that an unstructured 'triangle soup' can be optimised into a photorealistic mesh via Delaunay triangulation across a set of posed images. Building upon this insight, we present the first dense SLAM system to employ Triangle Splatting to perform both tracking and mapping through online differentiable rendering of a triangle soup. The map can be converted into a connected mesh on-the-fly via restricted Delaunay triangulation, enabling new online capabilities such as mesh deformation and collision checking. On Replica and TUM-RGBD, our system outperforms baselines on 3D geometry, matches the camera-tracking accuracy, and enables online mesh-based scene editing.
### Title:
          Institutions and the transmission of upper-tail human capital: scientific lineages across a millennium
 - **Authors:** Hiroyuki Chuma, Kanji Otsuka, Yoichi Sato
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 What made useful knowledge cumulative was not discovery alone but the institutions that transmitted it. We provide the first exhaustive structural measurement of the network through which upper-tail human capital passed from master to student across a millennium. Using 470,000 mentor-student records from Wikidata (which integrates the Mathematics Genealogy Project and MacTutor Archive), and all 64 historical Fields Medalists as a fixed, ex ante tracer set, backward traversal yields a directed acyclic graph of 25.5 million paths reaching 57 generations. We document two institutional transitions. First, a 17th-century watershed concentrates lineage traffic on Leibniz: 47 of 64 lineages pass through him with a 10:1 downstream-to-upstream ratio, and seven independent attributes -- learned-society membership (a 46-fold rise per scholar), field, language, employer, institutional diversification, student production, and diffusion entropy -- re-organize coherently across the same window. This is the network signature of Mokyr's Republic of Letters, and it reframes the Newton-Leibniz priority dispute as a distinction between the possession and the transmission of upper-tail human capital: it is transmission that generates the spillovers on which growth depends. Second, 84% of lineages converge upstream on five 12th-13th-century Islamic and Byzantine scholars before terminating at an 11th-century boundary -- the ``Monastery Wall'' -- at which personal academic mentorship first becomes record-generating in Europe. Our claims are descriptive-structural, not causal. Because exhaustive traversal at this scale defeats standard tools, we also contribute a deterministic, algebraic graph-traversal instrument whose measurement bias we characterize in closed form, and report one emergent property of independent methodological interest.
## Keyword: odometry
There is no result 
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Text-guided Feature Disentanglement for Cross-modal Gait Recognition
 - **Authors:** Zhiyang Lu, Ming Cheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Gait recognition is a biometric technique that identifies individuals based on their walking patterns, offering advantages in long-range, non-intrusive scenarios. However, real-world scenarios often involve heterogeneous sensing modalities such as LiDAR and RGB cameras, making LiDAR-Camera Cross-modal Gait recognition (LCCGR) a critical yet challenging task due to the substantial modality gap between 2D videos and 3D point cloud sequences. To address this challenge, we propose TCFDNet, a Text-guided Cross-modal Feature Disentanglement Network, which leverages modality-aware textual priors as semantic anchors to guide the learning of disentangled modality-shared representations. Specifically, we construct a Gait Modality Text Dictionary (GMTD) using large language models to generate rich semantic descriptions of gait across modalities and viewpoints. A CLIP-based Multi-grained Feature Encoder then aligns visual and textual features within a unified vision-language space. Furthermore, the Text-guided Feature Disentanglement (TFD) module selects the topk matched textual descriptions to reconstruct modality-specific representations and derive modality-shared features via residual decomposition and orthogonality constraints. To mitigate the fragility of the disentangled shared features, we propose a Feature Stability Enhancement (FSE) module, which models spatial and channel-wise correlations to improve feature robustness. In addition, a cross-modal patch exchange strategy is introduced to further improve generalization. Extensive experiments on SUSTech1K and FreeGait datasets demonstrate that TCFDNet achieves new state-of-the-art results and validate the effectiveness of the proposed modules.
### Title:
          Can BEV Perception Gracefully Degrade under Sensor Failures?
 - **Authors:** Haifa Zhang, Yijing Wang, Haoyu Wang, Zheng Li, Zhiqiang Zuo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite the remarkable success of multi-modal bird's-eye view (BEV) perception in autonomous driving, current systems exhibit a critical vulnerability: existing fusion mechanisms are highly brittle to sensor corruptions, often causing catastrophic performance degradation. This vulnerability largely stems from the fact that standard fusion frameworks typically integrate multi-modal representations in a static manner, leading to a precipitous performance collapse under missing or corrupted modalities. In contrast, we show that graceful degradation is achievable through active modality reliability assessment. To this end, we present Grace-BEV, a lightweight and plug-and-play framework that enforces active reliability awareness during multi-modal fusion. Instead of relying on computationally expensive cross-modal interactions, Grace-BEV leverages the aligned BEV space to explicitly assess modality trustworthiness via a TrustGate Router and dynamically recalibrate feature integration using the FailSafe Fusion Block. Furthermore, we devise a Three-Phase Training strategy with Modality Dropout to prevent modality dominance and encourage balanced cross-modal learning under unreliable inputs. Extensive experiments on nuScenes-R and nuScenes-C show that Grace-BEV maintains robust performance across diverse corruption settings. Notably, under catastrophic LiDAR failures where standard baselines collapse to 0.0% mean Average Precision (mAP), Grace-BEV restores performance to as high as 34.7% mAP. Moreover, it improves clean accuracy by up to 1.4%, achieving a strong trade-off between robustness and efficiency.
### Title:
          Vanilla ViT for Automotive Point Cloud Semantic Segmentation
 - **Authors:** Gilles Puy, Nermin Samet, Alexandre Boulch, Spyros Gidaris, Tuan-Hung VU, Renaud Marlet
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Plain Transformers have become the de-facto architecture for processing text, audio, image, and video, offering a unified backbone for multimodal learning. However, state-of-the-art architectures for point cloud semantic segmentation remain dominated by U-Nets architectures where convolutions are interleaved with local or windowed attentions. In this work, we show how to effectively leverage vanilla, non-hierarchical ViTs for segmentation of large-scale automotive lidar scenes. We bridge the performance gap thanks to a carefully designed tokenizer, a lightweight decoder segmentation head, and tailored data augmentations. Our approach, VaViT for Vanilla ViT, matches or exceeds the performance of state-of-the-art methods while maintaining the simplicity of ViT architecture. We provide extensive evaluations on nuScenes, SemanticKITTI, and Waymo Open Dataset to validate the efficiency of our method. Code and models are available at this https URL.
### Title:
          nuReasoning: A Reasoning-Centric Dataset and Benchmark for Long-Tail Autonomous Driving
 - **Authors:** Zhiyu Huang, Johnson Liu, Rui Song, Zewei Zhou, Ruining Yang, Yun Zhang, Tianhui Cai, Hanyin Zhang, Mingxuan Gao, Valeria Xu, Jiali Chen, Yishan Shen, Yiluan Guo, Tony (Xuewei)Qi, Jiaqi Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reasoning is essential for autonomous driving (AD) in long-tail scenarios, where vehicles must apply commonsense knowledge, understand spatial relations, infer agent interactions, and make safe decisions. However, existing AD datasets and benchmarks mainly target perception, prediction, or planning, and provide limited supervision for reasoning over realistic long-tail driving scenes. We introduce nuReasoning, a large-scale real-world dataset and benchmark for reasoning-centric AD. Following the lineage of nuScenes and nuPlan, nuReasoning advances real-world AD datasets and benchmarks toward reasoning in long-tail driving scenarios. The dataset contains 20,000 clips, each 20 seconds long, collected across multiple cities, with synchronized multi-camera images, LiDAR data, HD maps, object annotations, and human-verified reasoning annotations spanning Spatial Reasoning, Decision Reasoning, and Counterfactual Reasoning. Unlike prior datasets that focus primarily on visual question answering, nuReasoning supports both reasoning evaluation and planning evaluation, enabling a direct study of how reasoning supervision affects driving performance. Experiments show that fine-tuning VLMs on nuReasoning substantially improves driving-specific question answering, while incorporating reasoning supervision into VLA training improves planning performance even when textual reasoning outputs are disabled at inference time. These results establish nuReasoning as a foundation for evaluating and improving robust, interpretable, reasoning-driven AD systems in realistic long-tail settings.
### Title:
          Joint Multi-Camera LiDAR Extrinsic Calibration via Learned Pairwise Initialization and Geometric Refinement
 - **Authors:** Aziz Al-Najjar, Marzieh Amini, James R. Green, Felix Kwamena
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Most learning-based camera-LiDAR calibration methods treat each camera-LiDAR pair independently, ignoring the rigid geometric coupling in multi-camera platforms. As a result, per-camera estimates may be individually accurate yet inconsistent at the system level. We present a two-stage framework for joint multi-camera LiDAR extrinsic calibration that combines learned pairwise matching with geometric refinement. First, CMRNext is applied independently to each camera to produce initial extrinsic estimates and dense 2D-3D correspondences. These predictions are then jointly refined through a multi-frame bundle adjustment with reprojection, per-camera prior, and relative-pose prior terms. This approach converts pairwise predictions into a globally consistent multi-camera calibration. Experiments on KITTI (in-domain for CMRNext) and Walkley (out-of-domain) datasets show improved per-camera accuracy and inter-camera consistency. On KITTI, the method achieves 0.89 cm translation error and 0.038 rotation error. On Walkley, it reduces translation error from 108.6 cm to 3.1 cm, highlighting the benefit of explicit multi-camera coupling when single-camera predictions are less reliable.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          XOResNet: Exclusive-OR Meta-Residuals Facilitate Deep Spiking Neural Networks Learning
 - **Authors:** Jianfang Wu, Junsong Wang
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spiking neural networks (SNNs) hold promise for demonstrating superior learning and representation capabilities in deep models. Given the tremendous success of ResNet in deep learning, it would naturally follow to train deep SNNs with residual learning. However, existing residual structures for constructing deep SNNs still present challenges of spike redundancy or information loss, as well as redundant learning. In the present study, we first aim to address issues of relative spike redundancy in identity mapping and information loss in non-identity mapping. To this end, we propose an OR-ADD (OA) shortcut connection to merge output spikes/currents from two branches in the residual structure. Furthermore, to mitigate redundant learning in the backbone branch of the residual structure, we introduce the concept of XOR meta-residuals, i.e., selecting pre-learning residuals using the Exclusive-OR (XOR) operation for the backbone branch. Finally, by integrating the OA shortcut and XOR meta-residuals, we devise the XOR residual block and further construct XOResNet with varying depths based on this block. Extensive experiments on four datasets, Fashion-MNIST, CIFAR-10, CIFAR-100, and miniImageNet, show that the proposed XOResNet outperforms existing state-of-the-art deep SNNs optimized via gradient descent. These results validate the effectiveness of our OA shortcut and XOR meta-residual components in overcoming fundamental limitations of residual learning in SNNs, providing new architectural insights for building high-performance neuromorphic systems.
### Title:
          Structured interactions improve distributed coordination beyond model scaling in a real-world multi-robot system
 - **Authors:** Junping Wang, Zhizhong Zhang, Yongqiang Tang, Geng Zheng, Jiaming Zhang, Shiji Song, Yanmei Li, Yushan Ma
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scaling individual robot capabilities is common but costly. Here we investigate a system-level design question in real-world multi-robot coordination: given matched hardware budgets, does restructuring communication among robots yield larger gains than increasing onboard model size? Using a representative transport-and-mapping task with 10 physical robots (5 runs per condition, 60 runs total), we find that switching from fully connected to modular hierarchical interactions improves normalised performance by 47 points (0--100), whereas doubling neural network hidden size yields at most 9 points. Nested mixed-effects model comparisons show a substantially larger improvement in model fit for topology than for scale. The pattern is confirmed in independent SMAC replications; heterogeneous benchmark reanalyses provide secondary supporting consistency checks rather than primary evidence. Performance saturation beyond 1024 hidden units is observed in simulation-calibrated extrapolation, not directly on hardware. These results indicate that interaction structure can play a dominant role within the tested system and task setting, while broader quantitative generalisation remains to be established.
### Title:
          AI Loss of Control Incident Management: Response & Resilience
 - **Authors:** Ross Gruetzemacher
 - **Subjects:** Subjects:
Computers and Society (cs.CY); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent research demonstrating AI systems exhibiting deception and shutdown resistance suggests that AI loss of control (LOC) is an urgent policy concern , yet current literature focuses almost exclusively on alignment and prevention. To address this gap, this paper introduces a foundational framework and taxonomy for managing catastrophic AI LOC incidents. The taxonomy's first level distinguishes between scenarios where regaining control is 'extremely costly' versus 'impossible'. While impossible scenarios demand immediate resilience investments to fundamentally restrict an AI's attack surface , extremely costly scenarios require active incident management via Containment and Threat Neutralization. The framework further categorizes these manageable events into accidental LOC (requiring automated circuit-breaker responses) and adversarial LOC (requiring graduated escalatory measures). By mapping three severity classes to specific scenario matrices, this paper provides a concrete, proportional guide for managing unprecedented AI risks.
### Title:
          Clustering Guided Domain-Specific Pretrained Foundation Model Very High-Resolution Arctic Remote Sensing
 - **Authors:** Amal S. Perera, Chandi Witharana, Elias Manos, Michael Pimenta, Anna K. Liljedahl
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This study introduces a novel Arctic-focused remote sensing foundation model (RSFM) by combining diversity-aware regional-scale image curation with masked autoencoder (MAE) self-supervised pretraining of a Vision Transformer (ViT) encoder for very-high-spatial-resolution (VHSR) satellite image analysis. Spectral and acquisition-metadata descriptors were used in a scalable affinity-propagation clustering workflow to select approximately 3 million chips from 267 TB of Vantor VHSR imagery This curation strategy was designed to reduce oversampling of visually repetitive or low-information areas while preserving broad scene diversity across the study domain. We pretrained a ViT-Large encoder on the curated corpus using a domain-adapted MAE reconstruction objective, producing Arctic-specific transformer weights for downstream feature mapping. The pretrained encoder was integrated into an existing location-aware detection and segmentation framework and evaluated across four hand-labeled Arctic datasets. Compared to ImageNet-initialized ViT-Large baseline, Arctic MAE pretraining produced consistent improvements in foreground mean F1 scores of 0.87, 0.72, 0.93, and 0.87, for infrastructure, IWP, RTS, and TCNs, with approximately 5-8 percentage increase. The proposed model also outperformed Prithvi-EO-2.0 in all downstream comparisons, with the smallest gain corresponding to at least a 15 percentage improvement mean F1, suggesting that domain-specific self-supervised pretraining on curated Arctic VHSR imagery provides more transferable representations for fine-scale Arctic mapping than a general-purpose Earth observation foundation model. These results demonstrate that optimizing the pretraining data distribution at regional scale, while keeping the architecture and MAE objective fixed, can produce a reusable Arctic-domain encoder for multiple VHSR remote sensing applications.
### Title:
          CoMo3R-SLAM: Collaborative Monocular Dense SLAM with Learned 3D Reconstruction Priors for Outdoor Multi-Agent Systems
 - **Authors:** Zhihao Cao, Qi Shao, Shuhao Zhai, Feng Tian, Anh Nguyen, Hesheng Wang, Baoru Huang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Collaborative dense SLAM is essential for multi-robot teams to achieve scalable and consistent 3D perception across large-scale outdoor environments. Existing systems typically depend on depth sensors, incurring significant payload, power, and calibration costs. Monocular RGB cameras are a lightweight alternative, but collaborative monocular dense SLAM remains difficult due to scale ambiguity, unreliable inter-agent data association, especially in outdoor scenes where low overlap and repetitive structures make traditional feature matching unreliable, motivating robust geometric information. We propose CoMo3R-SLAM, the first collaborative monocular dense RGB SLAM system that leverages robust learned feed-forward 3D reconstruction priors for outdoor multi-agent mapping. Each agent runs a prior-guided front-end for real-time tracking and local dense fusion, while a coordinator performs dense pointmap matching for cross-agent verification, closed-form Sim(3) gauge synchronization, and GPU-accelerated global bundle adjustment with segment-level depth optimization. Requiring neither depth sensors nor parametric intrinsics, our system produces robust cross-agent constraints and globally consistent metric maps from monocular RGB alone. On Tanks and Temples and Waymo sequences, CoMo3R-SLAM achieves the best ATE on three of four Tanks and Temples scenes and competitive Waymo accuracy, matching or exceeding state-of-the-art RGB-D methods while running online at 8 FPS.
### Title:
          Overview over the first decade of LIMITS
 - **Authors:** Maria Emine Nylund, Erik Johannes Husom, Ophelia Prillard
 - **Subjects:** Subjects:
Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Computing within limits is a promising field, that follows principles of a) questioning endless growth narrative, b) considering and preparing for models of scarcity and c) reducing energy and material consumption, while considering d) a global spatial scale and e) long time frames. With computing's environmental impact growing and ecological limits becoming increasingly pressing, the LIMITS workshop has served as a central venue for this community since its inception in 2015, but an overview of the research published there has yet to be described. This paper addresses this gap by analyzing 160 publications from the LIMITS workshop in the period 2015 to 2025 to identify its international spread, contributions and developments in relation to field's core concerns, combining programmatic analysis with a manual review. Our findings indicate that the field has increasingly mentioned degrowth and post-growth, especially in 2024-2025. It has broadened its global perspective, with a growing, but still limited, representation of work beyond the Global North. The majority of papers are positional or observational, while artifact-producing research remains relatively scarce, though solution-oriented output has grown in recent years. This paper contributes to the LIMITS community by mapping its first decade and current trends to support future research and enhance its global impact.
### Title:
          Improving Relative Representations with Learned Anchors and Whitened Inner Products
 - **Authors:** Oscar Thorsted Svendsen, Nikolaj Holst Jakobsen, Fabian Mager, Hiba Nassar
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Independently trained neural models typically converge to incompatible latent representations, creating a fundamental barrier to highly modular AI systems. While Relative Representations (RR) address this by mapping absolute coordinates to a shared space defined by similarities to common anchor points, traditional implementations rely on randomly sampled anchors and cosine similarity, which frequently fail to capture the anisotropic geometries of modern architectures like Transformers. In this work, we propose a robust framework for cross-model communication based on two improvements. We learn anchors as robust semantic prototypes and utilize a geometry-aware similarity metric which preserves discriminative magnitude information and is invariant to affine shifts. Our approach demonstrates significant gains in performance and consistency across vision and language tasks. Notably, it enables nearly lossless information transfer and stable zero-shot communication even between highly heterogeneous architectures, such as small language models of varying scales.
### Title:
          Vision-Based Localization in Dense Urban Environments: A Case Study of an Urban Village in China
 - **Authors:** Menglin Wu, Rui Cao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Urban villages, the widespread informal settlements which have emerged as a result of rapid urbanization, are now major residential hubs for migrant workers in large cities in China. The dense arrangement of buildings in these areas often leads to unreliable GPS signals, while incomplete mapping data further impairs accurate route planning and navigation. These issues not only hinder everyday mobility but also pose significant challenges for emergency response, as confusing road layouts and GPS inaccuracies can complicate evacuation efforts. To address these challenges, we propose a practical vision-based geo-localization solution tailored for dense urban environments. Our approach features a low-cost data collection pipeline utilizing a dual-camera system, comprising a panoramic camera and a smartphone camera, to capture synchronized 360-degree panoramas and query images. Using Shipai Village, a well-known densely populated urban village in Guangzhou, as a case study, we develop a specialized image geo-localization dataset. We then assess and compare the performance of existing models across various scene types to identify their strengths and weaknesses. The findings demonstrate both the potential and limitations of visual-based localization in dense urban-village environments. Our framework aims to enhance pedestrian navigation, last-mile delivery, and emergency management in areas with poor GPS coverage, ultimately supporting the vulnerable populations living within these informal settlements.
### Title:
          BijectiveRemesh: Maintaining Bijective Mappings for Data Transfer Across Remeshed Manifolds
 - **Authors:** Leyi Zhu, Michael Tao, Yixin Hu, Daniele Panozzo, Denis Zorin
 - **Subjects:** Subjects:
Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce BijectiveRemesh, a robust algorithm for maintaining a continuous, bijective mapping across complex remeshing sequences on both 2D triangle surfaces and 3D tetrahedral meshes. Unlike traditional data transfer methods that rely on interpolation or projection, our approach constructs a mathematically rigorous composite map from the input mesh to the output mesh by chaining local bijective atlases defined for each primitive remeshing operation. Our framework represents the overall mapping as a composition of local bijective atlases, one per remeshing operation. Building upon successive self-parameterization, we introduce a Shared Scaffold structure for 2D triangle meshes that enforces global bijectivity through local orientation preservation. We extend this approach to handle edge splits, edge swaps, and vertex smoothing beyond the original edge collapses. For 3D tetrahedral meshes, we generalize the local atlas construction using Steinitz's Theorem and Maxwell-Cremona lifting to ensure valid embeddings. This enables exact tracking of geometric entities, including points, curves, and surfaces, across remeshing, with applications from texture transfer to volumetric simulations.
### Title:
          Where's Waldo Library? Using Reverse IP Geolocation to Identify Library IPs
 - **Authors:** Nishant Acharya, Anyu Yang, Humaira Fasih Ahmed Hashmi, Kevin Vermeulen, Shivani Kalamadi, Jiayi Liu, Ashutosh Kshirsagar, Elizabeth Belding, David Choffnes, Alexander Gamero-Garrido
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Community anchor institutions (CAIs), such as libraries, schools, and community centers, are critical for providing Internet access to un- or under-served individuals and communities. Because many of these institutions are themselves under-provisioned, analyzing the reliability and quality of their Internet service is important. Doing so at scale requires knowing the IP addresses of these institutions so that broadband measurement and policy evaluation can occur. Unfortunately, these IPs are not systematically documented. As a first step towards widespread, scalable evaluation of CAI Internet connectivity, this paper presents Reverse IP Geolocation (RG), a new framework to infer IP addresses from physical address data. A key insight is that CAI street addresses are publicly known, which allows us to identify a candidate set of IPs from commercial geolocation that are likely serving the location associated with a CAI. In this paper, \textbf{we focus on US public libraries}, which offer both geographic diversity across thousands of locations, and some publicly available institutional records (\eg{}WHOIS registrations) that enable systematic validation of our approach. Our approach offers a novel integration of IP geolocation databases, DNS PTR records, WHOIS registrations, broadband provider data, and active measurements to identify IPs likely assigned to libraries and validate them. Based on evaluations, our approach can map a library to its IP prefix approx. half of the time, with coverage across all US states, as well as urban and rural areas. Our results highlight the feasibility of mapping CAI presence in IP space and offer a foundation for large-scale, remote broadband infrastructure evaluation.
### Title:
          Beyond 1$\to$N Decoding: Capacity-Aware Rateless Polar Codes for IR-HARQ
 - **Authors:** Huazi Zhang, Xianbin Wang, Jiajie Tong, Jun Wang, Wen Tong
 - **Subjects:** Subjects:
Information Theory (cs.IT); Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper introduces a novel framework for polar codes, designed for flexible Incremental Redundancy Hybrid Automatic Repeat Request (IR-HARQ). By generalizing the decoding order beyond the standard 1$\to$N sequence, we enable a capacity-aware scheduling strategy that prioritizes the decoding of reliable subblocks. The framework integrates nested parity-check polar construction and reverse bit-mapping to support continuous and arbitrary transmission lengths $E \in [N_{\min}, N_{\max}]$. Simulation results show that the proposed rateless codes match the coding gain of independently optimized fixed-rate codes across the entire range of rates and lengths. With a validated hardware implementation, this work provides a practical solution for next-generation wireless data channels.
### Title:
          What Makes LVLMs Hallucinate Less? Unveiling the Architectural Factors Behind Hallucination Robustness
 - **Authors:** Yusheng He, Jizhe Zhou, Xia Du, Zheng Lin, Jun Luo, Jiancheng Lv
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hallucination remains one of the key challenges undermining the reliability of Large Vision-Language Models (LVLMs). But what makes an LVLM hallucinate less? Many existing efforts focus on improving internal components of the model. We argue that hallucination fundamentally stems from how the model architecture is designed. To investigate this, we factor the architecture design into three dimensions: Linguistic Foundation (LF), Visual Representation (VR), and Semantic Alignment (SA), and categorize hallucinations into Co-occurrence, Similarity, and previously overlooked Uncertainty types. Building on this formulation, we propose CoSimUE, a benchmark that creates fine-grained hallucination scenarios through controlled textual perturbations and random perturbations, enabling mapping between design choices and hallucination behaviors. Experiments across 7 design aspects show that: 1) the widely emphasized scaling of model parameters has only limited impact on reducing all three types of hallucinations; 2) larger and better-trained language foundations can reduce co-occurrence hallucinations; 3) stronger visual encoders and higher resolutions mitigate similarity errors; 4) effective alignment strategies alleviate uncertainty hallucinations. 5) Furthermore, cross-dimensional analysis reveals that jointly enhancing visual fidelity and alignment quality yields the most comprehensive improvements. This study provides the first systematic exploration linking architecture-level design to hallucination robustness, offering practical guidance for developing reliable and efficient LVLMs.
### Title:
          Beyond Static Dialogues: Benchmarking Realistic, Heterogeneous, and Evolving Long-Term Memory
 - **Authors:** Han Zhang, Zihao Tang, Xin Yu, Xiao Liu, Yeyun Gong, Haizhen Huang, Yan Lu, Weiwei Deng, Feng Sun, Qi Zhang, Hanfang Yang
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In existing memory benchmarks for Large Language Models (LLMs), the evaluated dialogue sessions often lack long-term semantic consistency, and the underlying personas tend to be flat and static. Furthermore, in real-world scenarios, interactions between users and assistants involve more diverse, heterogeneous data streams, such as documents and emails. These shortcomings significantly limit the realism and effectiveness of current evaluations. To address these limitations, we introduce RHELM (Realistic, Heterogeneous, and Evolving Long-term Memory). Driven by meticulously crafted user profiles and a novel LOOP (pLan-rOllout-evOlve-Prune) module, we construct realistic dialogues across diverse interaction scenarios that exhibit dynamic temporal evolution and long-term coherence. Crucially, these dialogues are deeply integrated with heterogeneous external sources synchronized with the user's temporal event trajectory. The resulting benchmark encompasses challenging question-answer pairs spanning seven inquiry types, with each question mapping to at least one of 27 critical memory characteristics that we identify as essential yet underexplored in current research. Comprehensive experiments across full-context models, retrieval-augmented generation (RAG) methods, and representative memory frameworks reveal that contemporary approaches still expose critical weaknesses in complex, real-world settings, particularly in resolving multi-source aggregation and real-world contextual reasoning.
### Title:
          Accelerating NBTI Aging Evaluation via Physics-Aware Graph Attention Networks
 - **Authors:** RenJie Zheng, HengXi Liu, ShuJun Gao, Cong Li
 - **Subjects:** Subjects:
Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As semiconductor technology advances to smaller nodes, Negative Bias Temperature Instability (NBTI) under prolonged workloads has emerged as a significant bottleneck constraining reliability-aware Design-Technology Co-Optimization (DTCO). Conventional TCAD simulations incur prohibitive computational overhead when evaluating device aging characteristics, making it difficult to satisfy the demand for efficient iterative design cycles. To address this challenge, this paper proposes an aging evaluation framework based on a physics-aware graph attention network (Physics-Aware RelGAT). By losslessly mapping unstructured device meshes into attributed graphs, this framework constructs a 45-dimensional device encoding scheme that integrates interface trap distributions and macroscopic electro-thermal stresses, achieving a direct mapping from underlying physical quantities to device degradation characteristics. To overcome the challenge of predicting currents that span multiple orders of magnitude, a dual-end normalization strategy and a log-scale loss function optimization are introduced, ensuring the model possesses high-precision fitting capabilities. Experimental results demonstrate that the model achieves a mean error of only 1.27% on an independent test set, achieving an acceleration of approximately 17,000 times compared to traditional TCAD simulations. This framework provides a solution for the assessment of circuit reliability in advanced process nodes that successfully balances physical fidelity with industrial-grade efficiency.
### Title:
          Cross-Modal Clinical Knowledge Integration for Mammography Report Generation
 - **Authors:** Jiayi Zhu, Fuxiang Huang, Yu Xie, Xi Wang, Zhixuan Chen, Yuan Guo, Qingcong Kong, Zhenhui Li, Qiong Luo, Hao Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Breast cancer is a major global health concern, and mammography screening plays a central role in early detection. The large volume of screening examinations creates a substantial workload for radiologists, making accurate and consistent report generation a critical clinical challenge. Existing automated mammography report generation methods primarily focus on direct visual-to-text mapping, while overlooking the structured clinical reasoning process followed by radiologists in real-world practice. To address this limitation, we propose MammoRG, a mammography report generation framework that explicitly simulates the clinical reporting workflow by following the BI-RADS guideline and incorporating prior clinical knowledge to produce diagnostic reports. Specifically, MammoRG adopts a two-stage training framework. In the first stage, the model learns to integrate clinically relevant prior knowledge from a patient's four-view mammograms through classification-based supervision. In the second stage, a terminology-aware supervised fine-tuning strategy is introduced to model mammography-specific clinical terms as atomic semantic units, enabling the generation of high-quality reports with improved clinical consistency. To facilitate clinical efficacy evaluation of generated reports, we further develop MammoRGTool, a dedicated mammography report parsing tool that extracts structured clinical information from free-text reports. Extensive experiments demonstrate that MammoRG consistently outperforms existing methods across multiple clinical efficacy metrics, particularly in diagnosis-related BI-RADS F1, where it surpasses the second-best model by 2.73%, 2.04%, 1.90%, and 3.27% on the internal, external 1, external 2, and VinDr-Mammo datasets, respectively.
### Title:
          TabCausal: Pretraining Across Causal Environments for Tabular Causal Discovery
 - **Authors:** Zi-Rong Li, Si-Yang Liu, Tian-Zuo Wang, Han-Jia Ye
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Causal discovery aims to recover directed causal relations from observational and interventional data, providing a basis for mechanistic understanding and reliable decision-making. Causal discovery foundation models (CDFMs) seek to amortize this problem by mapping a dataset directly to a causal graph in a single forward pass, avoiding per-dataset testing, search, or optimization. However, existing CDFMs remain limited, often failing to consistently match strong classical methods, and we find that a key bottleneck is how causal pretraining tasks are constructed. Based on this observation, we propose TabCausal, a data-driven CDFM trained with broad causal pretraining over diverse graph priors, structural mechanisms, noise models, dimensions, sample sizes, and intervention regimes. A dynamic task construction strategy composes these causal environments into varied discovery tasks, enabling more transferable structural learning from observational and mixed-interventional data. On large-scale synthetic benchmarks, TabCausal achieves better macro-averaged performance than a diverse set of causal discovery baselines. To further bridge abstract synthetic generators and realistic causal reasoning scenarios, we introduce a protocol-guided and LLM-audited semantic causal environment benchmark, where domain-grounded SCMs generate interpretable observational and interventional datasets for out-of-distribution analysis. Across both synthetic and semantic environments, TabCausal demonstrates robust structure recovery, especially under interventional evidence, highlighting broad causal pretraining as a key ingredient for transferable amortized causal discovery.
### Title:
          Surface Constraint Policy for Learning Surface-Constrained and Dynamically Feasible Robot Skills
 - **Authors:** Shuai Ke, Jiexin Zhang, Huan Zhao, Zhiao Wei, Yikun Guo, Jie Pan, Han Ding
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion-based imitation learning methods have driven rapid progress in robot dexterous manipulation tasks. However, they have limitations when applied to tasks that involve complex free-form surface constraints because of their lack of explicit surface geometry constraint modeling and the dynamic feasibility issue, resulting in stochastic action generation that fails to achieve reliable surface alignment and maintain stable contact. To address these limitations, we propose a novel surface constraint policy (SCP) for generating robot actions that satisfy free-form surface constraints on the basis of human demonstrations and real-time visual observations. First, the surface geometry constraint is encoded using a two-dimensional weighted Gaussian kernel function that is derived from demonstrations. Building on the encoded surface geometry constraints, the diffusion-based policy is used to infer task-level action intentions from multimodal sensory inputs, including visual observations and robot state feedback. These intentions are further transformed into surface-constrained dynamic movement primitives (DMPs) through a similarity-based action mapping method, thereby enabling smooth and compliant motion execution. The SCP achieves generation of structured surface geometric intent and dynamically admissible actions. The proposed method is validated on multiple surface manipulation tasks and compared with existing techniques. The experimental results demonstrate superior task success rates and contact stability under surface constraints.
### Title:
          Bundesrecht: An Open Library and Corpus for German Statutory Reference Processing
 - **Authors:** Harshil Darji, Martin Heckelmann, Christina Kratsch, Gerard de Melo
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Statutory references are central to legal language understanding, but are difficult to process automatically, as they appear in compact and variable surface forms, may combine multiple targets, use special abbreviations, and often point to lower-level units. Existing tools for German focus either on parsing references from legal documents or accessing statutory text once citations are explicit. This paper introduces bundesrecht, an open resource for German statutory reference processing, consisting of a software library and a structured corpus of German federal law. The library parses, normalizes, and resolves German statutory references, mapping raw citation strings to structured objects, expanding compact references into canonical forms, and linking them to statutory provisions. The accompanying dataset preserves the internal hierarchy of statutes from laws to fine-granular subclauses. We evaluate the parser and normalizer on 2,944 annotated German legal references using strict exact-match and micro information extraction metrics. We further evaluate canonical reference deduplication and show that normalized references group real citation surface variants far more reliably than string matching. bundesrecht is the first open resource that covers German statutory reference processing as an end-to-end pipeline, from raw citation string to resolved statutory provision, and is available on PyPI.
### Title:
          SQEEZ: Energy-efficient Location Sharing for Mobile Ad Hoc Networks
 - **Authors:** Ram Ramanathan, Dmitrii Dugaev, Ryan Conyac, Alon Mor, Charlie Greenbacker
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Periodic network-wide dissemination of node location data is crucial for shared situational awareness and collaborative mapping in mobile ad hoc and mesh networks for public safety, disaster relief, and military. A key challenge is to provide maximally accurate location information with minimal energy expenditure on part of the nodes. We present SQEEZ: a mechanism for reducing the Position Location Information (PLI) load that combines two orthogonal techniques: (1) adaptive suppression of location updates; and (2) temporal and inline compression of update packets. We describe the SQEEZ suppression and compression algorithms, analyze the tradeoff between location error and energy consumption, and introduce a new metric called \textit{Error-Penalized-Energy (EPE)} that normalizes the energy metric using the error incurred. Our simulation results show that, in the range of parameters studied, SQEEZ improves the EPE-efficiency and scalability in a 30-node random waypoint scenario by up to 4.4x and 2.3x respectively; and increases the EPE-efficiency by 7.5x in a 9-node real-world network trace. Compression provides larger improvements than suppression at high mobilities and vice-versa at low mobilities.
### Title:
          The Latin Substrate: How Language Models Represent and Mediate Script Choice
 - **Authors:** Daniil Gurgurov, Alan Saji, Katharina Trinley, Josef van Genabith, Simon Ostermann
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many languages are written in multiple scripts, requiring large language models (LLMs) to generate equivalent linguistic content in distinct orthographic forms. While prior work suggests that LLMs route information through shared latent representations, how they internally mediate script variation remains poorly understood. We study this question by first examining per-layer output distributions with the logit lens, which reveals consistent latent romanization during transliteration, and then through representational and mechanistic analyses of script generation. At the representational level, we show that scripts of the same language become increasingly separable across layers and that a simple linear steering direction can flip a model's output script while largely maintaining semantic content. The vector generalizes asymmetrically to writing systems unseen during construction, flipping non-Latin output to Latin reliably, but mapping Latin output into varied non-Latin scripts. At the mechanistic level, we localize a small set of late-layer attention heads that causally mediate script choice. These heads transfer across unrelated languages and writing systems, suggesting that script routing is implemented by language-agnostic components. Across both analyses, we observe a consistent directional asymmetry: non-Latin output is produced by a compact, identifiable gate, while Latin-script output emerges from diffuse contributions across the network. Collectively, our findings hint that LLMs organize script variation around shared latent representations while exhibiting a privileged substrate toward Latin script.
### Title:
          Triangle Splatting SLAM
 - **Authors:** Nicholas Fry (1 and 2), Eric Dexheimer (2), Kirill Mazur (2), Paul H. J. Kelly (1 and 2), Andrew J. Davison (2) ((1) Software Performance Optimisation Group, Imperial College London, (2) Department of Computing, Imperial College London)
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a dense RGB-D SLAM system using differentiable triangles as the 3D map representation. While 3D Gaussian Splatting has emerged as the leading method for novel-view synthesis, triangles remain the standard primitive for traditional rendering hardware, game engines, and downstream tasks requiring explicit geometry such as simulation, collision, and editing. Recent offline methods have demonstrated that an unstructured 'triangle soup' can be optimised into a photorealistic mesh via Delaunay triangulation across a set of posed images. Building upon this insight, we present the first dense SLAM system to employ Triangle Splatting to perform both tracking and mapping through online differentiable rendering of a triangle soup. The map can be converted into a connected mesh on-the-fly via restricted Delaunay triangulation, enabling new online capabilities such as mesh deformation and collision checking. On Replica and TUM-RGBD, our system outperforms baselines on 3D geometry, matches the camera-tracking accuracy, and enables online mesh-based scene editing.
### Title:
          On Efficient Scaling of GNNs via IO-Aware Layers Implementations
 - **Authors:** Daria Fomina, Daniil Krasylnikov, Alexey Boykov, Andrey Dolgovyazov, Vyacheslav Zhdanovskiy, Fedor Velikonivtsev
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Graph Neural Networks (GNNs) are bottlenecked by sparse, irregular memory access. Popular frameworks such as DGL and PyTorch Geometric support general message passing, but complex layers often materialize edge-wise intermediates, increasing memory traffic and limiting scalability on large graphs. We take an I/O- and arithmetic-intensity--centric view and show that widely used layers fall into three kernel families: SpMM-based convolutions, reduction-based aggregations, and attention-based layers (GATv2/Graph Transformer). For each family, we develop GPU kernels that reduce data movement, improve locality, and remain robust across realistic graphs. We also study graph reordering and find that its impact depends on the kernel mapping: it benefits neighbor-parallel (gather-dominated) kernels more consistently than feature-parallel designs. Empirically, our fused attention kernels reach up to $\textbf{3.9}\times$ speedup for Graph Transformer (median $\textbf{1.6}\times$), with Tensor Core (block-sparse) variants up to $\textbf{7.3}\times$ on locally dense graphs; for GATv2 we reach up to $\textbf{8.5}\times$ speedup (median $\textbf{2.0}\times$) while reducing peak memory by up to $\textbf{76}\times$ (median $\textbf{6}\times$). Our degree-aware reduction kernels achieve up to $\textbf{10}\times$ speedup (median $\textbf{2.6}\times$). For SpMM-based layers, properly cached cuSPARSE achieves up to $\textbf{8}\times$ speedup over DGL and outperforms evaluated custom baselines in the majority of evaluations. We release our implementations as drop-in replacements to support reproducible, hardware-aware GNN acceleration.
### Title:
          Evaluating Factual Density in Multi-Source RAG: A Study in Medical AI Accuracy
 - **Authors:** Michael R. DeMarco
 - **Subjects:** Subjects:
Information Retrieval (cs.IR); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Retrieval-Augmented Generation (RAG) is the current industry standard for grounding AI in real-world facts. Traditional retrieval methods rely on keyword matching and topic proximity, ranking content based on how closely it sounds like the user's query. What they do not measure is how many verified facts the content actually contains. This structural gap, termed the Expert Blindness Effect, causes standard RAG pipelines to consistently bury high-density factual evidence in favor of lexically dominant text on the same topic. To address this gap, this paper introduces Factual Density (FD*), a novel retrieval optimization signal that measures the proportion of verified atomic claims relative to total token count. Using the NexusAgentics Ghost Audit preprocessing pipeline, raw text is scored for factual specificity using probabilistic factuality analysis to filter content before corpus ingestion. An initial formulation introduced a severe document-length confound (Pearson R = -0.8636, p = 2.27e-07). Implementing Z-score normalization within length bins resolved this bias, validating FD* as a length-independent density signal (p = 0.0749). Evaluated against the HealthFC benchmark (750 health claims labeled Supported, Refuted, or No Evidence by medical experts), FD*-optimized retrieval was the only condition to achieve 100% systematic review saturation in top-5 results, surfacing Cochrane evidence that standard cosine similarity ranked outside the top ten. Ground truth verification confirmed 25 mappings across seven HealthFC-supported claims. While full statistical validation across n=50 queries remains future work due to constraints on corpus-benchmark alignment, these findings establish factual density reranking as a low-cost, high-impact intervention for improving factual precision in health RAG architectures.
### Title:
          Personalize Your Large Vision-language Models With In-context Prompt Tuning
 - **Authors:** Yanshu Li, Jiaqian Li, Kuai Yu, Xi Xiao, Dongfang Liu, Tianyang Wang, Ruixiang Tang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large vision-language models (LVLMs) have demonstrated strong general multimodal capability and are increasingly deployed in downstream systems. This trend has driven growing interest in LVLM personalization, which aims to enable models to quickly and effectively learn out-of-distribution multimodal concepts to meet user-specific needs. However, many existing methods rely on inference-time training, which reduces efficiency. They also struggle to maintain accuracy in complex multi-image, multi-concept settings. These limitations restrict the broader deployment of LVLM-based systems. Therefore, this paper proposes in-context prompt tuning (ICPT). Specifically, ICPT employs a lightweight projection module capable of operating in complex scenarios to extract fine-grained visual semantics from multiple reference images, seamlessly transforming these features alongside identity-label mappings into continuous prompts. To maximize computational efficiency, this module adaptively determines the prompt length based on the intrinsic visual complexity of each concept. Crucially, to overcome the environmental biases and cross-concept interference prevalent in real-world applications, we introduce two novel geometric regularizations. These constraints refine prompt representations by decoupling key identities from transient environmental states and separating concepts to avoid semantic confusion. Extensive experiments show that ICPT achieves state-of-the-art personalization accuracy across diverse tasks and LVLM backbones.
### Title:
          Functional Attention: From Pairwise Affinities to Functional Correspondences
 - **Authors:** Jiefang Xiao, Maolin Gao, Simon Weber, Guandao Yang, Daniel Cremers
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning mappings between infinite-dimensional function spaces, or operator learning, is essential for many machine learning applications. Although transformer-based operators are popular, they often rely on token-wise attention. These methods treat continuous fields as discrete tokens and usually ignore the global functional structure. We introduce \emph{Functional Attention}, which reinterprets attention as a functional correspondence between adaptive bases. Inspired by geometric functional maps, our method replaces softmax affinities with structured linear operators. This yields a compact, generalizable, resolution-invariant representation that explicitly captures global dependencies. Experiments demonstrate that \emph{Functional Attention} can match state-of-the-art performance in many operator learning tasks, including solving PDEs, 3D segmentation, and regression, while remaining robust to varying discretizations. Project page is available at this https URL.
## Keyword: localization
### Title:
          VLM-GLoc: Vision-Language Model Enhanced Monte Carlo Localization for Robust Semantic Global Localization in Cluttered Quasi-Static Environments
 - **Authors:** Shivendra Agrawal, Bradley Hayes
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Global localization in geometrically aliased, quasi-static environments such as grocery stores, offices, schools, and hospitals poses a significant challenge for mobile robots. Grocery stores with parallel aisles and a long tailed distribution of products, as well as offices and labs with repetitive furniture such as chairs, desks, monitors, and doors, exemplify common indoor environments that present geometric and even semantic ambiguity. Traditional approaches rely either on distinct geometric features or on domain-specific vision pipelines that struggle with long-tail semantic distributions and transient visual clutter. We present VLM-GLoc, a method for hierarchical semantic Monte Carlo Localization (MCL) that leverages open-vocabulary Vision-Language Models (VLMs) as a unified semantic observation front-end. We hypothesize a three-fold benefit from VLMs: (1) extracting highly discriminative rich text features, (2) implicit quality filtering of blurry or dynamic objects, and (3) permanence reasoning for targeted data augmentation. We introduce an inverse semantic proposal mechanism that seeds particles via text-to-map retrieval. Evaluated across two real-world environments with different characteristics and two different platforms: a 3,500 sq. ft. grocery store with a cellphone and a 3,700 sq. ft. lab space with a quadruped, VLM-GLoc achieves 70% and 74% global localization success respectively, substantially outperforming traditional geometry-only and domain-specific baselines.
### Title:
          Exploiting Chordal Sparsity for Globally Optimal Estimation with Factor Graphs
 - **Authors:** Avinash Subramanian, Connor Holmes, Timothy D. Barfoot, Frank Dellaert, Frederike Dümbgen
 - **Subjects:** Subjects:
Robotics (cs.RO); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust and efficient state estimation is crucial for perception, navigation, and control in robotics. State estimation problems are conveniently modeled using the factor-graph framework as enabled by modern software packages such as GTSAM or g2o. However, the standard solvers included in such frameworks are local and may converge to poor local minima, posing significant safety concerns. Conversely, techniques based on convex relaxations have been shown to provide a means of globally solving or certifying many state estimation problems. However, these relaxations 1) often require substantial effort to formulate, and 2) may incur significantly higher cost compared to efficient local solvers, as they require solving a large semidefinite program (SDP). In this work, we address both shortcomings by 1) creating a new procedure within the GTSAM framework for automatically constructing convex SDP relaxations for any factor graphs with common factor and variable types, and by 2) exploiting the Bayes tree constructions native to GTSAM to decompose the SDP problem, leading to significant speedup in solver time for chordally sparse problems. We demonstrate the favorable scaling of this structure-exploiting global estimator compared to standard local solvers for two case studies: A 3D pose-graph SLAM problem with a ring factor graph and a 2D localization problem with a chain factor graph. The software framework is available at this https URL.
### Title:
          ConTrans: Learning Text-enhanced Local-global Temporal Representations for Zero-shot Temporal Action Localization
 - **Authors:** Kanchan Keisham, Thenukan Pathmanathan, Thangarajah Akilan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Zero-shot Temporal Action Localization (ZS-TAL) aims to detect and locate previously unseen actions in untrimmed videos. However, existing approaches primarily focus on modeling long-range contextual information, often neglecting the critical relative-offset-based local correlations between video frames. Furthermore, their performance is hindered by limited feature representation capabilities due to the shallow nature of their network architectures. In this paper, we address these limitations by introducing a novel local-global multi-scale feature representation module. We propose a novel multi-scale encoder architecture, termed ConTrans, that integrates convolutional (Conv) inductive biases with transformer Self-attention to jointly capture fine-grained local dependencies and long-range global context, leading to more comprehensive feature representations than existing methods. Experimental evaluations on the ActivityNet-1.3 and THUMOS14 datasets demonstrate that ConTrans significantly outperforms existing methods, establishing a new benchmark for ZS-TAL.
### Title:
          Vision-Based Localization in Dense Urban Environments: A Case Study of an Urban Village in China
 - **Authors:** Menglin Wu, Rui Cao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Urban villages, the widespread informal settlements which have emerged as a result of rapid urbanization, are now major residential hubs for migrant workers in large cities in China. The dense arrangement of buildings in these areas often leads to unreliable GPS signals, while incomplete mapping data further impairs accurate route planning and navigation. These issues not only hinder everyday mobility but also pose significant challenges for emergency response, as confusing road layouts and GPS inaccuracies can complicate evacuation efforts. To address these challenges, we propose a practical vision-based geo-localization solution tailored for dense urban environments. Our approach features a low-cost data collection pipeline utilizing a dual-camera system, comprising a panoramic camera and a smartphone camera, to capture synchronized 360-degree panoramas and query images. Using Shipai Village, a well-known densely populated urban village in Guangzhou, as a case study, we develop a specialized image geo-localization dataset. We then assess and compare the performance of existing models across various scene types to identify their strengths and weaknesses. The findings demonstrate both the potential and limitations of visual-based localization in dense urban-village environments. Our framework aims to enhance pedestrian navigation, last-mile delivery, and emergency management in areas with poor GPS coverage, ultimately supporting the vulnerable populations living within these informal settlements.
### Title:
          Beyond Agreement: Scoring Panel-Surfaced Biomedical Entity Candidates for Curator Triage
 - **Authors:** Shuheng Cao, Ruiqi Chen, Renjie Cao, Zhenhao Zhang, Siyu Zhang, Tingting Dan
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Biomedical NER is deceptively simple for modern LLMs: plausible biomedical mentions are easy to surface, but corpus-convention correctness depends on annotation conventions, span boundaries, entity granularity, and type schemas. Multi-LLM agreement is a salience signal, not corpus-convention correctness. We introduce a candidate-level panel-output benchmark for panel-surfaced candidate verification, where the unit is an aligned candidate surfaced by an explicitly defined multi-model panel rather than a standalone extractor output. The benchmark aligns eight LLMs' predictions over five public biomedical NER datasets into a candidate master table. BioConCal is an in-domain supervised scorer that instantiates this layer with inference-time gold-free agreement, mention, surface-availability, and document features for a fixed candidate stream. In domain, BioConCal improves AUROC from 0.753 for raw agreement to 0.910. At a validation-selected 0.95 precision target it selects 1,340 candidates at empirical test precision 0.939, compared with 293 for raw agreement. This corresponds to candidate-level recall 0.592 and corpus-level recall 0.523 against a within-panel row-label ceiling of 0.883. The main benefit is not recovering entities missed by every panel member, but reshaping a noisy panel stream into a higher-yield review queue. Under entity-type shift, thresholds require target-domain validation, and exact character localization remains a separate deterministic post-processing step.
### Title:
          Count Anything
 - **Authors:** Mengqi Lei, Shuokun Cheng, Wei Bao, Shaoyi Du, Jun-Hai Yong, Siqi Li, Yue Gao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Object counting remains fragmented across domain-specific datasets and task formulations, despite rapid progress in generalist vision models. Existing counting models are often tailored to scenarios such as crowds, vehicles, cells, crops, or remote-sensing objects, and thus struggle to generalize across categories, visual domains, object scales, and density distributions. In this paper, we study text-guided object counting across domains, where a model takes an image and a natural-language query as input and returns an instance-grounded set of target points whose cardinality gives the count. This formulation unifies category-conditioned counting with interpretable spatial localization. To support this setting, we construct CLOC, a Cross-domain Large-scale Object Counting dataset that reorganizes diverse public data sources into a unified benchmark. CLOC covers six visual domains: General Scene, Remote Sensing, Histopathology, Cellular Microscopy, Agriculture, and Microbiology, with about 220K images, 619 categories, and 15M object instances. Based on CLOC, we propose Count Anything, a generalist model for text-guided object counting. Unlike density-map-based methods, which dominate counting models, Count Anything adopts discrete instance points and performs dual-granularity instance enumeration. A Region-level Sparse Counter provides object-level anchors for large and sparse targets, while a Pixel-level Dense Counter handles small, crowded, and weakly bounded targets via dense point prediction. A point-centric supervision strategy enables learning from heterogeneous annotations, and Complementary Count Fusion combines both counters in a parameter-free manner. Extensive experiments show that Count Anything achieves strong accuracy and multi-domain generalization, outperforming existing open-world counting methods. Code is available at: this https URL.
### Title:
          LLM Anonymization Against Agentic Re-Identificatio
 - **Authors:** Ziwen Li, Jianing Wen, Tianshi Li
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Agentic LLMs with web search change the threat model for text anonymization: weak contextual cues can become cross-referenceable evidence for re-identification, yet those same details also carry downstream analytic value of the text. Existing defenses either remove explicit identifiers, perturb text for formal privacy, or test rewritten text against non-web inference models, leaving underexplored the operating region between resistance to agentic web-search re-identification and utility retention. We introduce AURA (\textbf{A}nonymization with \textbf{U}tility-\textbf{R}etention \textbf{A}daptation), an LLM-powered \textit{mask-reconstruct} framework that decouples privacy localization from utility-preserving reconstruction and selects candidates with adversarial privacy and utility-retention checks. We evaluate AURA on real-user interview transcripts using re-identification attacks carried out by web-search agents, along with a utility evaluation based on interviewee-profile facts, codebook facts, and the joint contextual utility grid. Our results show that AURA improves the privacy-utility frontier by using adaptive privacy scope to strengthen resistance to agentic re-identification and using a mask-reconstruct anonymization method to better preserve contextual utility under fixed privacy scope.
### Title:
          iVGR: Internalizing Visually Grounded Reasoning for MLLMs with Reinforcement Learning
 - **Authors:** Chang-Bin Zhang, Yujie Zhong, Qiang Zhang, Kai Han
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While visually grounded Chain-of-Thought (CoT) has emerged as a promising paradigm to enhance fine-grained perception in multimodal large language models (MLLMs), its efficacy during the inference phase remains underexplored. In this work, we empirically find that mandating explicit object boxes in visually grounded CoT during inference often degrades performance compared to standard textual CoT, which reasons without explicit visual grounding. We hypothesize that the visual localization capability can be internalized into the textual CoT and that the mandatory explicit grounding introduces unnecessary interference with the model's primary objective of answer prediction. To address this problem, we propose Internalizing Visually Grounded Reasoning (\textbf{iVGR}), a novel reinforcement learning framework that transfers localization capabilities into the textual reasoning process. We employ a dual-stream training strategy, where a textual stream is aligned with a high-quality visually grounded stream via a proposed consistency reward, enabling the model to localize accurately without explicit grounding during inference. Extensive experiments demonstrate that our method significantly outperforms existing baselines on fine-grained benchmarks, while maintaining the flexibility to support tool-assisted inference workflows.
### Title:
          FOCUS: Forcing In-Context Object Localization through Visual Support Constraints and Policy Optimization
 - **Authors:** Mohammed Asad Karim, Vinay Kumar Verma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In-context localization (ICL) seeks to localize a target object specified by a small set of support examples in a query image, operating on the fly without training or parameter updates. Despite rapid advances in vision-language models (VLMs), achieving category-agnostic and visually grounded ICL remains an open problem, even though it is essential for applications such as image editing, personalized visual search, and retrieval. Existing methods are fragile and rely on explicit category supervision, which not only limits applicability in realistic settings with unnamed or instance-specific objects but also introduces category bias that steers predictions toward semantic priors rather than visual evidence. We introduce a two-stage training framework that explicitly optimizes in-context attention between support bounding boxes and query images without category supervision. We further refine localization via reinforcement learning using Group Relative Policy Optimization (GRPO) to directly minimize localization error. This formulation enforces visual correspondence over semantic priors, yielding robust instance-level localization. Empirically, a 7B-parameter model trained with our objectives outperforms models up to 72B parameters, demonstrating that context-aware localization objectives can surpass scaling alone. Comprehensive ablations validate the contribution of each component.
### Title:
          ERGeoBench:A Comprehensive Benchmark for Embodied Reasoning and Geo-localization in Multimodal Large Language Models
 - **Authors:** Kaiwen Xue, Tao Wei, Guoxin Zhang, Zhonghong Ou, Kaoyan Lu, Yu Feng, Yifan Zhu, Haoran Luo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal large language models (MLLMs) have shown strong potential as embodied agents, yet embodied geo-localization remains underexplored due to the lack of fine-grained evaluation. We introduce ERGeoBench, a diagnostic benchmark for vision-driven embodied geo-localization. ERGeoBench evaluates models under three progressive settings -- single-view, panorama-view, and embodied-view -- where agents may actively acquire observations through sequential changes in yaw, pitch, and zoom. The benchmark contains 2,207 globally distributed street-view panoramas and measures four complementary capabilities: foundational perception, spatial awareness, common sense reasoning, and geo-localization reasoning. Evaluations of leading proprietary and open-source MLLMs show that current models can infer high-level geographic semantics, but still struggle with fine-grained perceptual operations, metric localization, and spatial consistency across views. We further observe that geo-localization is strongly correlated with the other capability dimensions, suggesting that accurate localization depends on integrated perception, spatial reasoning, and commonsense inference rather than isolated visual recognition. Overall, ERGeoBench provides a unified framework for diagnosing and advancing human-like embodied geo-localization. Project Page: this https URL
### Title:
          Shaft-integrated Force Sensing with Transformer-based Dynamics Compensation for Telesurgery
 - **Authors:** Shuyuan Yang, Grant Boone, Timo Markert, Sebastian Matich, Andreas Theissler, Martin Atzmueller, Zonghe Chua
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robot-Assisted Minimally Invasive Surgery (RAMIS) enhances surgeon dexterity, with newer platforms leveraging haptic feedback to further improve performance. Such force information has broader potential to inform performance assessment, tactile localization, and surgical autonomy. This motivates the need for accessible approaches to integrating force sensing into RAMIS tools. This work presents a method for integrating a six-axis commercial force sensor into the distal end of a standard cable-driven surgical instrument, enabling end-effector force measurement while preserving the original mechanical functionality of the device. The proposed design emphasizes reproducibility and accessibility for research applications, requiring no specialized manufacturing tools. A transformer neural network integrates force sensor measurements with robot state information to aid estimation of applied forces at the end-effector, compensating for internal cable forces arising from actuation. Our proposed approach achieved normalized errors below 6%, and generalized to unseen conditions better than purely proximal data-driven sensing approaches. High internal cable forces caused sensor saturation and reduced axial force observability, which can degrade performance along the tool's major axis and under higher load conditions. Given current levels of performance, the balance of system integrability and performance enables applications and research into timely topics of haptic feedback, skill assessment, and force-informed autonomy in RAMIS. Videos and code are available at this https URL force sensing.
### Title:
          SOCO: Benchmarking Semantic Object Correspondence in Vision Foundation Models
 - **Authors:** Olaf Dünkel, Basavaraj Sunagad, Haoran Wang, David T. Hoffmann, Christian Theobalt, Adam Kortylewski
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Measuring structured object understanding in vision foundation models remains challenging due to inconsistent evaluation protocols and limited part-level supervision. Semantic correspondence (SC) evaluates this capability by testing whether object parts can be matched across instances and categories under large variations in appearance, viewpoint, and geometry. To enable a systematic SC evaluation, we introduce SOCO, a new benchmark for Semantic Object Correspondence that introduces a taxonomy of correspondence types and provides consistent, functionally meaningful keypoint annotations across 100 categories and over 1M correspondence pairs. In addition, SOCO includes keypoint language descriptions, enabling the evaluation of large vision-language models (LVLMs) and their fine-grained part-level understanding. Comprehensive experiments reveal that (i) vision foundation backbones encode strong semantic structure but transfer correspondences poorly across related categories and only partially capture object-part position, (ii) LVLMs are stronger at text-prompted part localization than at visual-reference cross-image matching, exposing a gap between language-grounded localization and fine-grained visual correspondence, and (iii) correspondence performance predicts performance on dense downstream tasks, including segmentation, tracking, 3D pose estimation, and 3D detection, more strongly than ImageNet classification. Together, these findings position SOCO as a benchmark for structured, part-level representation quality in vision and multimodal foundation models.
## Keyword: transformer
### Title:
          Gait2Hip-60: A Unified Deep Learning Benchmark for Predicting Hip Muscle Forces and Joint Moments from Multi-Cadence Gait Kinematics
 - **Authors:** Jiaqi Zhang, Ji Hou, Qing Sun, Xianzhi Gao, Bo Huo
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Estimating hip muscle forces and joint moments during gait typically relies on musculoskeletal simulation, which is informative but time-consuming and difficult to apply in clinical settings. This study developed a deep learning framework to predict these hip dynamics parameters directly from lower-limb gait kinematics and compared three representative sequence models under a unified protocol. Gait data were collected from 60 healthy adults under three metronome-guided cadence conditions. Ten bilateral lower-limb joint angles were used as inputs, and OpenSim-derived hip muscle forces and hip joint moments were used as reference outputs. Three deep learning models of LSTM, Transformer, and Mamba were trained and evaluated using the same subject-level split, preprocessing pipeline, and metrics. The best model was then directly tested on an external cohort of 9 patients with osteonecrosis of the femoral head (ONFH) without retraining. In the healthy-subject benchmark, Transformer achieved the best subject-level mean performance for both hip muscle force prediction (RMSE = 1.33 N/kg, MAE = 0.57 N/kg, R2 = 0.819) and hip joint moment prediction (RMSE = 0.11 Nm/kg, MAE = 0.07 Nm/kg, R2 = 0.862), with similar advantages across walking cadences. In zero-shot external validation, Transformer retained moderate predictive ability in ONFH for hip muscle force prediction (RMSE = 1.51 N/kg, MAE = 0.70 N/kg, R2 = 0.537) and hip joint moment prediction (RMSE = 0.17 Nm/kg, MAE = 0.12 Nm/kg, R2 = 0.569). These findings support the feasibility of estimating hip dynamics from gait kinematics, identify Transformer as a strong baseline, and highlight the need for broader pathological validation and improved generalization before clinical application.
### Title:
          Lightweight SAR Ship Detection via Contrastive Distillation
 - **Authors:** Surendar Devasundaram, Saber Latibari Banafsheh, Abhijit Mahalanobis
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep convolutional and transformer-based detectors achieve strong performance for SAR ship detection but are often computationally prohibitive for real-time or onboard deployment. Lightweight models offer improved efficiency yet struggle to capture the complex structural relationships inherent in SAR backscatter. Most existing SAR knowledge-distillation approaches rely on feature or logit matching, which enforces localized activation similarity while neglecting the geometric relationships among object representations. We propose a Structured Unified Relational knowledGE distillation framework for SAR Ship detection (SURGE) that transfers relational geometry from a powerful teacher detector to a compact student detector using a contrastive InfoNCE objective in a shared projection embedding space. To the best of our knowledge, this work presents the first transformer-based SAR ship detector knowledge distillation framework in SAR domain. The framework is architecture-agnostic in the sense that it provides a common region-level distillation interface for two-stage, one-stage and transformer-based detectors without modifying their deployed architectures. Experiments on the SSDD and HRSID benchmarks demonstrate that the proposed method yields substantial improvements for two-stage detectors, achieving up to 6.2 mAP and 8.0 AP75 gains over baseline student and even surpassing teacher performance
### Title:
          When LLMs Learn to Be Consistently Wrong: A Multi-Model Study of Linear Representations of Synthetic Deception
 - **Authors:** Vahideh Zolfaghari
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deceptive alignment, in which models maintain accurate internal representations while deliberately producing false outputs, remains a central challenge in AI safety. While strategic deception is the primary long-term concern, synthetic dishonesty - induced via direct optimization on incorrect answers - provides a controlled testbed for studying the representational basis of learned deception. We introduce a multi-model paradigm in which honest and deceptive variants of five transformer models (Pythia-1.4B, Gemma-2-2B/9B, Qwen2.5-7B, Llama-3.1-8B) are fine-tuned using LoRA on the same question distribution. Linear probes trained on mean-pooled hidden states detect synthetic dishonesty with near-perfect AUC (greater than or equal to 0.99) as early as layers 1-3 in four architectures, while Pythia-1.4B reaches a peak of 0.705. Logistic regression probes consistently match or outperform MLP probes, supporting the Linear Representation Hypothesis. Probes trained on TruthfulQA generalize with near-zero loss (Delta AUC approx. 0) to held-out MMLU subjects. Late-layer representations show strong robustness to Gaussian noise, with Gemma-2 models exhibiting exceptional stability. Mechanistic analysis of Fisher Discriminant Ratio, effective rank, centroid geometry, directional stability, cross-domain alignment, and calibration (ECE) reveals two regimes: representational collapse in Pythia/Llama/Qwen versus high-dimensional preservation in Gemma-2. Across all models, the dishonesty direction consolidates progressively in deeper layers, with optimal calibration (ECE less than 0.01 except Pythia) achievable in layers 1-4. These results demonstrate that robust, domain-invariant dishonesty representations can be rapidly entrenched via modest supervised fine-tuning, with implications for activation-based monitoring.
### Title:
          SANA-Streaming: Real-time Streaming Video Editing with Hybrid Diffusion Transformer
 - **Authors:** Yuyang Zhao, Yicheng Pan, Qiyuan He, Jincheng Yu, Junsong Chen, Tian Ye, Haozhe Liu, Enze Xie, Song Han
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-time streaming video-to-video editing (V2V) is critical for interactive applications such as live broadcasting and gaming, yet it remains a formidable challenge due to the stringent requirements for temporal consistency and inference throughput. In this paper, we present SANA-Streaming, a system-algorithm co-designed framework for high-resolution, real-time streaming video editing on consumer GPUs, with the following three core designs: (1) Hybrid Diffusion Transformer architecture introduces softmax attention in part of the blocks to improve local modeling capabilities while preserving the efficiency of linear layers. (2) Cycle-Reverse Regularization is a novel training strategy that enforces semantic consistency by predicting source frames from generated content via flow matching, improving temporal consistency without requiring paired long edited videos. (3) Efficient System Co-design combines fused GDN kernels and Mixed-Precision Quantization (MPQ) optimized for the NVIDIA Blackwell (RTX 5090) architecture. By profiling real-world throughput, our MPQ maximizes Tensor Core utilization while maintaining generation quality. The resulting system achieves real-time 1280 x 704 resolution editing at 24 end-to-end FPS on a single RTX 5090 GPU, with the DiT core running at 58 FPS. Experimental results demonstrate that our co-design approach significantly outperforms existing SOTA methods in both temporal coherence and system throughput.
### Title:
          Clustering Guided Domain-Specific Pretrained Foundation Model Very High-Resolution Arctic Remote Sensing
 - **Authors:** Amal S. Perera, Chandi Witharana, Elias Manos, Michael Pimenta, Anna K. Liljedahl
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This study introduces a novel Arctic-focused remote sensing foundation model (RSFM) by combining diversity-aware regional-scale image curation with masked autoencoder (MAE) self-supervised pretraining of a Vision Transformer (ViT) encoder for very-high-spatial-resolution (VHSR) satellite image analysis. Spectral and acquisition-metadata descriptors were used in a scalable affinity-propagation clustering workflow to select approximately 3 million chips from 267 TB of Vantor VHSR imagery This curation strategy was designed to reduce oversampling of visually repetitive or low-information areas while preserving broad scene diversity across the study domain. We pretrained a ViT-Large encoder on the curated corpus using a domain-adapted MAE reconstruction objective, producing Arctic-specific transformer weights for downstream feature mapping. The pretrained encoder was integrated into an existing location-aware detection and segmentation framework and evaluated across four hand-labeled Arctic datasets. Compared to ImageNet-initialized ViT-Large baseline, Arctic MAE pretraining produced consistent improvements in foreground mean F1 scores of 0.87, 0.72, 0.93, and 0.87, for infrastructure, IWP, RTS, and TCNs, with approximately 5-8 percentage increase. The proposed model also outperformed Prithvi-EO-2.0 in all downstream comparisons, with the smallest gain corresponding to at least a 15 percentage improvement mean F1, suggesting that domain-specific self-supervised pretraining on curated Arctic VHSR imagery provides more transferable representations for fine-scale Arctic mapping than a general-purpose Earth observation foundation model. These results demonstrate that optimizing the pretraining data distribution at regional scale, while keeping the architecture and MAE objective fixed, can produce a reusable Arctic-domain encoder for multiple VHSR remote sensing applications.
### Title:
          Discovering a Zeta Map Algorithm on Dyck Paths via Mechanistic Interpretability
 - **Authors:** Xiaoyu Huang, Blake Jackson, Kyu-Hwan Lee
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Machine learning is increasingly used in mathematical discovery, but in mathematics the desired output is often not a prediction itself, but an explicit construction that can be checked independently. We study this setting through the zeta map on Dyck paths, a classical bijection in the combinatorics of the q,t-Catalan numbers. We train a deliberately small one-layer, one-head encoder-decoder transformer on this map and analyze its learned computation using mechanistic interpretability tools, including decoder cross-attention analysis, linear probing, and causal intervention. The analysis reveals a level-based mechanism: encoder representations make path levels linearly accessible, while the decoder selects and traverses input positions in a structured way. Translating these signals into combinatorics leads to the scaffolding map, an explicit peak-centered traversal algorithm for Dyck paths. We prove that this algorithm agrees with the zeta map, modulo a reversal convention in the labeling. This gives a controlled example of AI-assisted mathematical discovery in which mechanistic interpretability turns model behavior into a precise, human-verifiable combinatorial algorithm.
### Title:
          Revisiting Padded Transformer Expressivity: Which Architectural Choices Matter and Which Don't
 - **Authors:** Anej Svete, William Merrill, Ryan Cotterell, Ashish Sabharwal
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computational Complexity (cs.CC); Computation and Language (cs.CL); Formal Languages and Automata Theory (cs.FL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent work describes what transformers can and cannot compute through connections to boolean circuits, but existing results lack exact characterizations and are sensitive to modeling choices. Padded transformers -- to whose input filler symbols such as ``...'' are appended -- emerge as a useful gadget for establishing equivalences to circuit classes by providing polynomial space for adaptive parallel computation. However, only a limited set of padded transformer idealizations has been studied, leaving open how robustly these equivalences hold under changes to attention type, model width, and uniformity. We find that, under practical assumptions, padded transformers are surprisingly robust to all of these, and identify numeric precision and model depth as the main factors affecting expressivity. Concretely, we prove that polynomially padded $\text{L-uniform}$ constant-precision transformers are equivalent to $\text{L-uniform AC}^0$, while growing-precision ones achieve $\text{L-uniform TC}^0$ regardless of width. Furthermore, looping enables sequential processing analogous to circuits: $\log^d N$-looped constant-precision transformers reach $\text{FO-uniform AC}^d$, and growing-precision ones reach $\text{FO-uniform TC}^d$. Interestingly, growing width or precision beyond logarithmic does not increase expressivity, and all our results hold for both softmax and average hard attention transformers.
### Title:
          Memory-Bound but Not Bandwidth-Limited: The Physical AI Inference Gap in Batch-1 LLM Decode
 - **Authors:** Josef Chen
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Artificial Intelligence (cs.AI); Distributed, Parallel, and Cluster Computing (cs.DC); Performance (cs.PF); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Physical AI systems, including robots, autonomous vehicles, embodied agents and edge copilots, often run a different inference workload from cloud LLM serving: single-stream, batch-1 autoregressive decode, where one robot, camera feed or user session waits on the next token. This workload is usually described as memory-bandwidth-bound. Each decode step streams model weights and the active KV cache, so latency should scale with peak HBM bandwidth. We show that this account is true but incomplete. We measure batch-1 decode for three 7 to 8B-class GQA transformers across four NVIDIA GPUs: H100 SXM5, A100-80GB SXM4, L40S and L4. We evaluate context lengths from 2048 to 16384, producing 44 valid cells under a controlled bf16 SDPA setup. The achieved fraction of peak HBM bandwidth falls as peak bandwidth rises. On the headline Qwen-2.5-7B ctx=2048 cell, an L4 reaches roughly 81 percent of its analytic memory floor, while an H100 reaches only 27 percent. Physical-AI decode is memory-dominated, but faster memory does not translate into proportional latency gains. We test the missing term with a CUDA Graphs A/B experiment. On H100 at ctx=2048, CUDA Graphs improves decode latency by 1.259x across N=10 fresh sessions, with a 95 percent bootstrap confidence interval of 1.253 to 1.267. On L4, the same intervention gives only 1.028x. This isolates a launch-side overhead that becomes visible on fast GPUs but remains mostly hidden on slower, bandwidth-bound GPUs. The deployment implication is that memory savings matter only when the runtime realises them. On L4, bf16 decode sits close to the memory floor, but common quantised paths do not recover the expected 4x weight-traffic reduction: bnb-nf4 reaches 59.36 ms/step and AutoAWQ+Marlin reaches 45.24 ms/step from a 62.32 ms bf16 baseline. GPTQ+ExLlamaV2, with Ada-tuned int4 kernels, reaches 17.36 ms/step.
### Title:
          Improving Relative Representations with Learned Anchors and Whitened Inner Products
 - **Authors:** Oscar Thorsted Svendsen, Nikolaj Holst Jakobsen, Fabian Mager, Hiba Nassar
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Independently trained neural models typically converge to incompatible latent representations, creating a fundamental barrier to highly modular AI systems. While Relative Representations (RR) address this by mapping absolute coordinates to a shared space defined by similarities to common anchor points, traditional implementations rely on randomly sampled anchors and cosine similarity, which frequently fail to capture the anisotropic geometries of modern architectures like Transformers. In this work, we propose a robust framework for cross-model communication based on two improvements. We learn anchors as robust semantic prototypes and utilize a geometry-aware similarity metric which preserves discriminative magnitude information and is invariant to affine shifts. Our approach demonstrates significant gains in performance and consistency across vision and language tasks. Notably, it enables nearly lossless information transfer and stable zero-shot communication even between highly heterogeneous architectures, such as small language models of varying scales.
### Title:
          Bridging the Gap Between Natural Language and Market Dynamics via High-Dimensional Representation Learning
 - **Authors:** Yujin Jeong, Noelle Jung, Brian Y. C. Leung (Mike)
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traditional multi-modal financial forecasting often relies on scalar sentiment scores, which fail to capture the nuances of financial news. To address this information loss, this paper explores high-dimensional representation learning by replacing discrete polarity ratings with dense FinBERT embeddings within a Transformer-based forecasting architecture. We benchmarked various embedding strategies on the FNSPID dataset, including raw embeddings, attention-weighted aggregation, and a custom Siamese network. While the attention-based mechanism struggled with the low signal-to-noise ratio typical of financial data, the integration of Siamese-optimized embeddings outperformed both the scalar baseline and raw embedding approaches, demonstrating that preserving high-dimensional narrative context yields improved predictive accuracy for short-term stock price movements.
### Title:
          ConTrans: Learning Text-enhanced Local-global Temporal Representations for Zero-shot Temporal Action Localization
 - **Authors:** Kanchan Keisham, Thenukan Pathmanathan, Thangarajah Akilan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Zero-shot Temporal Action Localization (ZS-TAL) aims to detect and locate previously unseen actions in untrimmed videos. However, existing approaches primarily focus on modeling long-range contextual information, often neglecting the critical relative-offset-based local correlations between video frames. Furthermore, their performance is hindered by limited feature representation capabilities due to the shallow nature of their network architectures. In this paper, we address these limitations by introducing a novel local-global multi-scale feature representation module. We propose a novel multi-scale encoder architecture, termed ConTrans, that integrates convolutional (Conv) inductive biases with transformer Self-attention to jointly capture fine-grained local dependencies and long-range global context, leading to more comprehensive feature representations than existing methods. Experimental evaluations on the ActivityNet-1.3 and THUMOS14 datasets demonstrate that ConTrans significantly outperforms existing methods, establishing a new benchmark for ZS-TAL.
### Title:
          Kalimati Vegetable Price Index Forecasting with a Momentum Corrected Online Stacking Ensemble
 - **Authors:** Sahaj Raj Malla
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); General Economics (econ.GN); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Forecasting agricultural commodity prices in emerging economies is difficult due to high volatility, frequent supply disruptions, and strong cultural influences on demand. This study introduces the Kalimati Vegetable Price Index (KVPI), a new inverse-volatility weighted composite index that aggregates 135 daily wholesale commodities from Kathmandu over ten years (2013-2023). By creating a stable macro-level signal, the KVPI reduces the noise inherent in modelling individual crops. A rich set of 64 causally valid features was developed, including festival lead-lag effects, rolling statistics, and calendar variables. Fourteen forecasting models spanning statistical, tree-based, deep learning, hybrid, and transformer architectures were rigorously evaluated across short (7-day), medium (14- and 30-day), and long-term (90-day) horizons. Tree-based ensembles proved notably robust, while classical statistical models and complex transformers struggled with the noisy dataset. The proposed Momentum-Corrected Online Stacking Ensemble achieved the strongest performance, yielding a Root Mean Square Error (RMSE) of 1.771, an exceptionally low Mean Absolute Percentage Error (MAPE) of 0.68%, and explaining 84.5% of the variance (R-squared = 0.845) at the 90-day horizon. This open-source pipeline provides policymakers and supply chain actors in Nepal and similar markets with a practical, reliable tool for anticipating price movements and strengthening food security.
### Title:
          Chain-of-Thought and Compressed Looped Transformers: A Memory-Budget Separation
 - **Authors:** Haozhou Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Chain-of-thought prompting and looped Transformers both give a fixed model more test-time computation, but they differ in what they remember. Chain-of-thought stores intermediate state in generated tokens that remain in the context, whereas a looped Transformer carries state through recurrent hidden activations. We argue that this persistent mutable memory is a central resource for test-time reasoning. We compare three memory regimes, the compressed latent loop, the full sequence-state loop, and the chain-of-thought scratchpad. Our main result shows that a compressed loop is limited by the size of its recurrent state. Running the loop longer adds computation but does not by itself create a growing scratchpad, so a loop with a small recurrent state remains a small-space reasoner even when run for many steps. Under a standard complexity assumption, such loops cannot decide problems that are P-complete under logspace reductions, whereas polynomial-length chain-of-thought can. The separation is specific to compressed loops, as full sequence-state loops carry state at every input position and live in a memory-rich regime closer to explicit scratchpads. Controlled pointer-chasing and associative-recall sweeps illustrate this memory-budget view, with performance sensitive to whether the persistent-state budget matches the task's working-memory demand.
### Title:
          A Data-Driven Methodology for Scalable Distributed MPC in Heterogeneous Building Aggregation: From Systematic Feature Selection to Convex Optimization
 - **Authors:** Kaipeng Xu, Zhuo Zhi, Keyue Jiang
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Coordinating large-scale, heterogeneous building aggregations for demand response (DR) is impeded by a dual challenge: the computational intractability of centralized Model Predictive Control (MPC) and the inadequacy of conventional feature selection methods, which fail to address the error-compounding nature of multi-step forecasting required by MPC. This paper proposes a comprehensive, data-driven framework that first employs a systematic, MPC-aware feature selection methodology to ensure robust multi-step prediction, then models the complex building dynamics using a novel Input-Convex Encoder-Only Transformer (IC-EoT) to guarantee a convex optimization problem, and finally solves the resulting constraint-coupled problem (CCP) in a fully distributed manner using the Tracking Alternating Direction Method of Multipliers (ADMM) algorithm. The framework is validated in a high-fidelity co-simulation environment, controlling a heterogeneous aggregation of consumer and prosumer buildings based on the EnergyPlus under a dynamic time-of-use (TOU) tariff. Results demonstrate that the proposed distributed approach achieves near-identical economic optimality and superior thermal comfort compared to a theoretical centralized controller, while exhibiting exceptional computational scalability that overcomes the real-time infeasibility of the centralized approach for large aggregations.
### Title:
          LegSegNet: A Public Deep Learning System for Lower Extremity CT Tissue Segmentation and Quantification
 - **Authors:** Yuwen Chen, Yaqian Chen, Roy Colglazier, Haoyu Dong, Hanxue Gu, Maciej A. Mazurowski, Kevin W. Southerland
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Lower extremity computed tomography (CT) contains clinically relevant information for body composition analysis, sarcopenia assessment, and musculoskeletal disease monitoring, but extracting these measurements at scale requires accurate tissue segmentation and an automated quantification workflow. Existing public segmentation tools are not designed for comprehensive lower extremity CT analysis, particularly for clinically important inter/intramuscular adipose tissue, and most public methods only provide mask prediction rather than an end-to-end quantification system. To address this problem, we present LegSegNet, a deep learning system for lower extremity CT tissue segmentation and body composition quantification. Given an input CT scan, LegSegNet segments bone, skeletal muscle, subcutaneous adipose tissue, and inter/intramuscular adipose tissue. It then computes quantitative tissue measurements for downstream analysis. We developed the segmentation model using 1,302 manually annotated CT slices and evaluated it on 900 held-out test slices, with all annotations reviewed by radiologists. We benchmark LegSegNet against a broad set of 2D segmentation methods, including CNN-based models, transformer-based models, and finetuned foundation models, and further evaluate its generalization on an external public CT dataset. LegSegNet achieves the best overall segmentation performance, with an average Dice score of 89.31 on the held-out test set. To our knowledge, LegSegNet is the first publicly available end-to-end system for lower extremity CT tissue segmentation and quantification, providing a practical evaluation tool for future computer vision research in medical image analysis. The code and model weights are available at: this https URL
### Title:
          Cross-Layer Subspace Coupling for LLM Compression: A Unifying Framework and Its Empirical Limits
 - **Authors:** Snigdha Chandan Khilar
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Differential Geometry (math.DG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent SVD based compression methods for large language models like SVD LLM and Basis Sharing can be unified under one optimization problem. While mathematical proofs and tests on Pythia models show this unified approach improves weight reconstruction error by up to 46% percent it fails in practical tasks. Downstream metrics like perplexity and accuracy severely degrade compared to standard per layer SVD LLM. The authors explain this failure mechanistically. Although the bundle method mathematically couples adjacent layers the transformer residual stream actually decouples them during forward passes. Thus per layer optimality matters more than joint cross layer optimization. The paper concludes that weight space reconstruction is a flawed objective for cross layer compression and future methods must focus on per layer activation reconstruction instead.
### Title:
          Omni-Supervised Motion Editing: Balancing Change and Invariance through Positive-Negative Learning
 - **Authors:** Zhenwu Shi, Jingyu Gong, Peiwei Wang, Xingzan Wang, Tianwen Qian, Wenxi Li, Yuan Fang, Jiao Xie, Lizhuang Ma, Shaohui Lin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-based human motion editing aims to modify existing motion sequences according to natural language instructions while maintaining the consistency of the original motion. Existing diffusion-based approaches often rely on heuristic similarity cues or coarse global conditioning, leading to motion distortion and suboptimal semantic alignment. The key challenge lies in balancing change (i.e. precisely editing target regions) and invariance (i.e. preserving unedited parts). To handle such challenge, we propose an Omni-Supervised Positive-Negative Learning framework, named OmniME. Our method integrates three complementary components: (1) retrospective feature supervision that enforces coarse-to-fine consistency across transformer layers,(2) motion preservation mechanism that focuses on subtle variations according to the source-target similarity, and (3) triplet-based semantic alignment that strengthens text-motion correspondence. Together, these components form a unified supervision paradigm that balances change and invariance. Extensive experiments on the MotionFix and STANCE Adjustment datasets demonstrate that OmniME achieves state-of-the-art performance in editing alignment, validating the effectiveness of our unified learning framework. Our source codes and models have been released at: this https URL
### Title:
          BiSegMamba: Efficient Bidirectional Tri-Oriented Mamba for 3D Medical Image Segmentation
 - **Authors:** Bakht Zada, Chao Tong, Qile Su, Shuai Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate 3D medical image segmentation requires both long-range volumetric context and fine boundary preservation. CNN-based methods have limited global dependency modeling, while Transformer-based models are often computationally expensive for dense 3D inputs. Recent Mamba-based methods provide an efficient alternative, but existing volumetric designs still depend on repeated high-resolution scanning, forward-only sequential modeling, and fixed directional summation, causing high cost, scan-order bias, and suboptimal directional aggregation. We propose BiSegMamba, an efficient bidirectional tri-oriented Mamba network for 3D medical image segmentation. BiSegMamba follows a compact-to-detail design, where a progressive compacting stem (PCS) enables efficient latent-space reasoning while retaining shallow high-resolution features for reconstruction. A multi-scale spatial mixer (MSSM) captures local anatomical patterns in early stages, and the proposed bidirectional tri-oriented Ortho Mamba (Bi-ToOM) block models long-range dependencies from multiple orthogonal views using jointly processed forward and backward scan sequences. Adaptive directional fusion (ADF) learns input-dependent channel-wise weights across scan orientations, replacing fixed summation with orientation-aware fusion. Experiments on a collected carotid CTA dataset and three public benchmarks, BraTS2023, ACDC, and AMOS-CT, show that BiSegMamba generalizes well across vascular, cardiac, brain tumor, and abdominal multi-organ segmentation tasks. Compared with SegMamba-V2, BiSegMamba achieves slightly better performance on BraTS2023 and clear improvements on ACDC and the carotid dataset, while reducing computational cost by up to 77.9% FLOPs, demonstrating a strong accuracy-efficiency balance for general 3D medical image segmentation.
### Title:
          Generating Reports or Repeating Templates? Measuring and Mitigating Template Collapse in 3D CT Report Generation
 - **Authors:** Tom Maye-Lasserre, Yitong Li, Bailiang Jian, Morteza Ghahremani, Benedikt Wiestler, Christian Wachinger
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern 3D medical vision-language models (VLMs) can generate fluent radiology-style text while exhibit critically low pathology detection and output diversity, collapsing to generic templates that under-report rare yet critical findings. We identify this failure mode as Template Collapse. This failure stems from the unique constraints of 3D medical imaging, e.g., limited data, severe label imbalance, and weak signals from volumetric encoders. Under these constraints, text-generation objectives encourage shortcut learning and fluent but weakly grounded reports. We systematically diagnose the Template Collapse through clinical fidelity, output diversity, normal-template bias, and rare-finding survival. To mitigate it, we propose CLarGen, a decoupled framework that separates what to say (clinical detection) from how to say it (language synthesis). CLarGen uses (i) a Latent Query Transformer for multi-label pathology detection, (ii) pathology-guided retrieval for clinically matched exemplars, and (iii) a medical language model to synthesize the final report from detected findings and retrieved context. Across state-of-the-art 3D CT report generation baselines, CLarGen mitigates Template Collapse and substantially improves clinical accuracy (macro-F1 0.487 vs. 0.189; CRG 0.472 vs. 0.368) while maintaining fluent reporting. Our results suggest that explicit, measurable clinical grounding is essential for template-collapse-resistant 3D CT report generation. Code will be released upon acceptance.
### Title:
          HADT: A Heterogeneous Multi-Agent Differential Transformer for Autonomous Earth Observation Satellite Cluster
 - **Authors:** Mohamad A. Hady, Muhammad Anwar Masum, Siyi Hu, Mahardhika Pratama, Jimmy Cao, Ryszard Kowalczyk
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work addresses the problem of autonomous resource management in heterogeneous satellite cluster conducting Earth Observation (EO) missions including optical and Synthetic Aperture Radar (SAR) satellites. In autonomous operation mode, satellites are equipped with intelligent capabilities enabling real-time decision-making based on the latest conditions, while requiring minimal interaction with ground operators. Traditional scheduling approaches typically rely on mathematical models to represent satellite mission and resource management. Then, this problem is solved by using optimization algorithms. However, such solutions become less effective when the underlying models are not available, over complex, and inaccurate due to dynamic changes and uncertainties inherent in the space mission environment. A promising alternative is to reformulate the problem as a sequential decision-making process and apply model-free reinforcement learning techniques to enable adaptive and real-time resource management. To this end, we propose a novel transformer-based architecture tailored for heterogeneous satellite cluster autonomous EO Mission with relational observations-actions tokenization and differential attention mechanism. Our experimental results demonstrate significant performance improvements compared to the available baselines. Moreover, the proposed architecture exhibits strong adaptability and transferability with respect to varying numbers of satellite clusters.
### Title:
          SlotMemory: Object-Centric KV Memory for Streaming Long-Video Generation
 - **Authors:** Weijia Dou, Hui Li, Jiahao Cui, Lei Zhou, Jingdong Wang, Siyu Zhu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Streaming video generation models typically rely on temporal-centric memory, which organizes historical context as raw frames, chunk segments, or unclustered tokens. This organization frequently leads to identity drift and semantic inconsistency when entities exit the frame or during interactive prompt transitions. To address these limitations, we propose SlotMemory, an object-centric Key-Value memory mechanism for streaming video diffusion. Our approach shifts the memory abstraction from "when" an event occurred to "what" is being represented by decomposing the transformer's key-value manifold into discrete, reusable semantic slots. By utilizing these slots as routing addresses to index and store high-fidelity key-value tokens, we enable entity-level persistence and prompt-aware retrieval across long horizons. Evaluated on 60-second interactive narratives using the Wan2.1-T2V-1.3B backbone, SlotMemory achieves a state-of-the-art quality score of 81.61 and a 22.8 percent relative improvement in dynamic consistency over the strongest existing streaming baseline. Our results demonstrate that structured semantic representation, rather than raw temporal capacity, is the essential primitive for persistent long-form video synthesis. Our codes and checkpoints are available at this https URL.
### Title:
          Rethinking Efficient Crack Segmentation with Task-Aligned Structural-Directional Modeling
 - **Authors:** Shipeng Liu, Liang Zhao, Dengfeng Chen, Weihua Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent crack segmentation methods often follow generic semantic segmentation designs, using stronger backbones, hybrid CNN-Transformer-Mamba encoders, and auxiliary enhancement branches. Although effective, this raises whether stronger generic feature mixing is the most suitable direction for crack segmentation. We instead formulate crack segmentation as sparse structural recovery. Cracks have limited category-level semantics but strong morphological regularities, being thin, sparse, anisotropic, locally fragmented, and easily confused with textures or shadows. Thus, the key bottleneck lies in preserving weak structural evidence, recovering directional continuity, and suppressing background coupling. We propose RIFT, a compact family of morphology-aligned crack segmentation models. Rather than compressing a complex generic architecture, RIFT is simple by design, preserving local evidence, aggregating cooperative directional continuity, and restoring crack structures through lightweight multi-scale fusion. Experiments on four public benchmarks show that RIFT achieves the best or tied-best results across the 16 main metrics against reproduced representative baselines. RIFT-B gives the strongest overall accuracy, while RIFT-T provides the best deployment efficiency with only 0.47M parameters and high inference speed. Topology-aware evaluation, ablations, transfer experiments, and visualizations further verify that task-aligned simplicity can match or surpass complex hybrid architectures when its inductive bias fits crack morphology. Code: this https URL
### Title:
          LVSA: Training-Free Sparse Attention for Long Video Diffusion
 - **Authors:** Gael Glorian, Ioannis Lamprou, Zhen Zhang, Yujie Yuan, Hongsheng Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dense self-attention is the compute and quality bottleneck of long-video diffusion inference: cost grows quadratically with the sequence length, and beyond the training horizon the model converges to near-static output, that is, "frozen" repetitive video. State of the art approaches are either too costly, e.g., they require retraining, or fail to satisfy both performance and quality objectives in a scalable manner. To this end, we introduce Long Video Sparse Attention (LVSA), a training-free model-agnostic block-sparse attention for video diffusion transformers that combines a structured window pattern with rotating global anchors, thus removing the fixed-grid bias which causes long-range temporal artifacts. LVSA, combined with a FlashInfer kernel, reduces compute up to 3.17x on Wan 2.1 1.3B at a 6x horizon, 2.98x on Wan 2.1 14B at a 6x horizon, and 3.33x on HunyuanVideo 1.5 at a 1.5x horizon, compared to dense attention. Beyond reducing compute, LVSA enables HunyuanVideo 1.5 generation at a 2x horizon, which is otherwise out-of-memory on a single GPU. Moreover, LVSA provides speedups up to 2.41x compared to RIFLEx and 3.27x compared to UltraViCo on Wan 2.1 1.3B. To demonstrate applicability across diverse platforms, we apply LVSA on NPUs and achieve speedups up to 2.71x on Wan 2.2 A14B and 3.24x on Wan 2.1 1.3B compared to dense attention. To evaluate quality in a fair way, we introduce VQeval, a tool properly scoring loopy video failures, which instead are rewarded in state of the art evaluators like VBench-Long. LVSA is quality-neutral for generation at training horizon length and quality-positive at extended lengths.
### Title:
          Polyphony: Diffusion-based Dual-Hand Action Segmentation with Alternating Vision Transformer and Semantic Conditioning
 - **Authors:** Hao Zheng, Hu Wang, Tiantian Zheng, Prajjwal Bhattarai, Tuka Alhanai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dual-hand action segmentation, densely predicting actions for both hands from untrimmed videos, is essential for understanding complex bimanual activities. However, it poses several unique challenges: complex inter-hand dependencies, visual asymmetry between hands, representation conflicts where the dominant hand monopolizes gradients, and semantic ambiguity in fine-grained actions. We propose Polyphony, a three-stage method to address these challenges through: (1) an Alternating Dual-Hand Vision Transformer that alternates training between left- and right-hand mini-batches to ensure balanced gradient contributions from both hands while sharing a spatio-temporal encoder; (2) Semantic Feature Conditioning that aligns visual features with structured, compositional action descriptions to enhance discrimination of semantically similar actions; and (3) Diffusion-Based Segmentation with cross-hand feature fusion for inter-hand coordination and adaptive loss weighting for balancing performance. Polyphony achieves state-of-the-art on both dual-hand datasets (HA-ViD, ATTACH) with improvements up to 16.8 points, and on the single-stream Breakfast dataset (82.5%), outperforming the prior best method that uses a 12x larger backbone. Notably, our unified model with a single shared backbone surpasses baselines requiring separate per-hand models. Code is at this https URL.
### Title:
          QVGGT: Post-Training Quantized Visual Geometry Grounded Transformer
 - **Authors:** Zhizhen Pan, Hesong Wang, Huan Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Estimating 3D attributes directly from images has advanced rapidly with the Visual Geometry Grounded Transformer (VGGT), which predicts camera parameters, depth maps, and point clouds in a single forward pass. However, its 1.2B-parameter scale severely limits deployment on resource-constrained platforms such as UAVs and mobile AR devices. To address this limitation, we introduce QVGGT, a tailored quantization framework designed to compress VGGT. Our approach starts from the observation that transformer blocks within VGGT exhibit heterogeneous sensitivity to quantization. We thus analyze per-block quantization sensitivity and propose a selective mixed-precision strategy that allocates higher precision to the most fragile transformer blocks. To address the amplification of quantization error caused by high-variance camera and register tokens, we further introduce token filtering with camera information compensation, which removes these outliers from activation calibration and restores their geometric cues using a PCA-derived global compensation token. Finally, we develop a task-aware scale search mechanism that evaluates candidate quantization scales not only through layer reconstruction but also through multi-head supervision and cross-head geometric consistency among camera poses, depth maps, and point maps. Extensive experiments on multiple geometry perception benchmarks demonstrate that QVGGT achieves near-lossless W4A16 quantization, preserving the accuracy of all 3D prediction heads while delivering 3$\sim$4.9$\times$ memory reduction and up to 2.8$\times$ real hardware speedup over FP32. Our approach makes high-fidelity 3D perception feasible on edge devices, enabling practical deployment of feed-forward 3D reconstruction models in real-world constrained environments.
### Title:
          PolSAR Image Classification using a Hybrid Complex-Valued Network (HybridCVNet)
 - **Authors:** Mohammed Q. Alkhatib
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recently, convolutional neural networks (CNNs) have become popular for image classification due to their effectiveness in computer vision tasks. Now, researchers are exploring the potential of vision transformers (ViTs) in remote sensing and Earth observation. However, traditional Real-Valued networks often overlook important phase information in Complex-Valued (CV) data like polarimetric synthetic aperture radar (PolSAR) data. To address this, new CV deep architectures have emerged. HybridCVNet, a novel hybrid network, blends CV-CNN and CV vision transformer (CV-ViT) techniques. It efficiently combines CV 3D and 2D CNNs as feature extractors, enhancing PolSAR image classification by extracting complementary information and effectively leveraging interdependencies within the data. Experimental results from widely-used PolSAR datasets show HybridCVNet outperforms other methods, achieving an overall accuracy of 97.39% on the Flevoland dataset and showing promise even with just a 1% sampling ratio, with a Kappa value of 0.972 on the San Francisco dataset. Source code is accessible through this https URL
### Title:
          Vanilla ViT for Automotive Point Cloud Semantic Segmentation
 - **Authors:** Gilles Puy, Nermin Samet, Alexandre Boulch, Spyros Gidaris, Tuan-Hung VU, Renaud Marlet
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Plain Transformers have become the de-facto architecture for processing text, audio, image, and video, offering a unified backbone for multimodal learning. However, state-of-the-art architectures for point cloud semantic segmentation remain dominated by U-Nets architectures where convolutions are interleaved with local or windowed attentions. In this work, we show how to effectively leverage vanilla, non-hierarchical ViTs for segmentation of large-scale automotive lidar scenes. We bridge the performance gap thanks to a carefully designed tokenizer, a lightweight decoder segmentation head, and tailored data augmentations. Our approach, VaViT for Vanilla ViT, matches or exceeds the performance of state-of-the-art methods while maintaining the simplicity of ViT architecture. We provide extensive evaluations on nuScenes, SemanticKITTI, and Waymo Open Dataset to validate the efficiency of our method. Code and models are available at this https URL.
### Title:
          Probabilistic Precipitation Nowcasting with Rectified Flow Transformers
 - **Authors:** Johannes Schusterbauer, Jannik Wiese, Nick Stracke, Timy Phan, Björn Ommer
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate weather forecasts are essential across various domains and are safety-critical in extreme weather conditions. Compared to simulation-based forecasting, data-driven approaches show greater efficiency, enabling short-term, high-resolution nowcasting. In particular, diffusion models proved effective in weather nowcasting due to their strong probabilistic foundation. However, existing methods rely on deterministic compression to reduce the complexity of high-dimensional weather data, limiting their ability to capture uncertainty in the decoding process. In this work, we introduce $\textbf{FREUD}$, a $\textbf{Fr}$ame-wise $\textbf{E}$ncoder and $\textbf{U}$nited $\textbf{D}$ecoder model based on rectified flow transformers for efficient compression of spatio-temporal weather data. Frame-wise encoding enables continuous forecast updates, while the unified video decoder ensures temporal consistency. Our uncertainty-preserving first stage allows us to capture aleatoric uncertainty via ensembling, which is particularly beneficial for extreme weather events with high decoding variability. We achieve state-of-the-art performance in precipitation nowcasting with a compact latent-space rectified flow transformer on the SEVIR benchmark and show further performance gains by model and test-time scaling. Code available here: this https URL
### Title:
          Fixed-Point Masked Generative Modeling
 - **Authors:** Andrea Miele, Yiming Qin, Alba Carballo-Castro, Justin Deschenaux, Pascal Frossard
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Masked Generative Models (MGMs) enable parallel decoding and achieve strong performance across modalities, but require full-sequence bidirectional transformers at every step, making training costly and degrading quality under low sampling budgets. Existing work improves efficiency via better samplers or cheaper fixed-depth denoisers, but they still allocate a fixed amount of denoiser computation to each refinement step. We introduce Fixed-Point Masked Generative Models (FP-MGMs), which replace part of the denoiser with a fixed-point solver over shared attention layers to enable adaptive depth with fewer parameters. To make it more effective for masked generation, we first introduce a cross-step consistency loss, which aligns hidden representations at neighboring denoising steps and, second, three-state reuse (3SR) which warm-starts the solver using the previous solution by treating differently unchanged, still-masked, and newly revealed tokens respectively. Together, these components define our complete training-to-inference framework for fixed-point masked generation, \emph{CoFRe}. We also show that pre-trained MGMs can be converted into FP-MGMs with short fine-tuning, avoiding full retraining. Across modalities, CoFRe improves the quality and cost trade-off. On OpenWebText, CoFRe reduces parameters by 38.8\%, training time by 11.5\%, and VRAM by 16.9\%, while improving generative perplexity from 830.8 to 101.8 at a budget of $96$ transformer-block forward passes, compared to MDLM. In ImageNette, CoFRe reduces training time by 48.6\% and VRAM by 50.7\%, while improving FID in all sample budgets tested. Overall, CoFRe offers a practical framework for cheaper training and stronger low-budget masked generation.
### Title:
          TALON: Token-Aligned Lightweight Adapters for 6-DoF Spacecraft Pose Estimation
 - **Authors:** Abid Ali, Arunkumar Rathinam, Djamila Aouada
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular 6-DoF spacecraft pose estimation methods predominantly process individual frames, discarding the temporal information present in an image sequence acquired during spacecraft manoeuvres. Few temporal approaches require full backbone fine-tuning or auxiliary optical flow networks, risking catastrophic forgetting or increasing computational cost, respectively. We propose TALON (Token-Aligned Lightweight adapters for Orbital Navigation): spatiotemporal 3D adapters injected before the self-attention layers of a frozen ViT vision transformer, combined with a patch-token alignment loss that geometrically grounds the adapted features to keypoint structure through a prototype-conditioned KL-divergence objective. Pre-attention placement allows the frozen attention to reason over temporally enriched tokens, achieving stronger performance with a single adapter per block than post-attention alternatives. The alignment loss shapes the intermediate representations so that each keypoint induces a spatially precise activation in the token field, while the framework adds less than 5% parameters to the frozen backbone. On SPADES dataset, TALON reduces the pose error by 50% over the prior state-of-the-art, and on SwissCube dataset it surpasses the prior best by 21.8% in ADD-0.1d accuracy. Zero-shot cross-domain evaluation from sim-to-real on SPARK real data reduces pose error by 4.7x, and ablations characterise the role of adapter depth across in-domain and cross-domain settings.
### Title:
          Learning Parametric Nitrogen Fertilizer Response Curves Using Neuro Symbolic Regression
 - **Authors:** Giorgio Morales, John Sheppard
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurately modeling crop response to Nitrogen (N) fertilization is a fundamental challenge in precision agriculture, as it impacts both economic returns and environmental sustainability. Existing approaches either rely on predefined parametric forms or opaque machine learning models, limiting their ability to interpret or discover site-specific functional relationships from data. In this work, we propose a neuro symbolic regression (SR) approach to learn parametric N-response curves without assuming a predefined functional form. Our approach integrates a transformer-based Multi-Set Symbolic Skeleton Prediction strategy, enabling the discovery of shared functional structures across multiple subdomains or management zones (MZs). By constructing diverse input subsets and enforcing consistency across them, the method recovers robust symbolic skeletons that are subsequently fitted to observed data using a genetic algorithm. This framework was first evaluated on synthetic one-dimensional problems to assess its robustness under varying levels of epistemic uncertainty. The results demonstrate the ability of the proposed SR approach to recover correct expressions even in data-scarce regimes. In this work, we present the results of applying our method to real-world winter wheat data, learning distinct parametric N-response curves for different MZs within a field. The results show that the discovered expressions not only achieve lower fitting errors than traditional models such as quadratic-plateau and exponential functions, but also capture diverse functional behaviors across spatial regions. This demonstrates the potential that neuro SR has to enable the discovery of site-specific agronomic relationships and support informed decision-making in precision agriculture.
### Title:
          DeMaVLA: A Vision-Language-Action Foundation Model for Generalizable Deformable Manipulation
 - **Authors:** Taiyi Su, Jian Zhu, Tianjian Wang, Youzhang He, Zitai Huang, Jianjun Zhang, Chong Ma, Hanyang Wang, Tianjiao Zhang, Munan Yin, Weihao Ding, Yi Xu
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-world household robots require Vision-Language-Action (VLA) foundation models that can acquire reusable manipulation skills across diverse objects, task conditions, and household environments. Deformable-object folding is a representative challenge, requiring robots to handle clothing items from random initial states across varying categories, geometries, materials, and scenes. However, existing VLA systems commonly train separate policies for different object categories, while naively mixed multi-task training often suffers from task interference and degraded performance. To move beyond category-specific folding policies, we introduce DeMaVLA, a VLA foundation model for generalizable Deformable Manipulation. DeMaVLA adopts a VLM backbone with an action expert and formulates continuous action generation using flow matching. To improve efficiency, the action expert is constructed by pruning every other transformer layer while preserving layer-wise alignment with the VLM backbone, reducing training and inference cost. DeMaVLA is first pre-trained on approximately 5,000 hours of selected real-world dual-arm demonstrations to acquire general manipulation priors. It is then post-trained on mixed folding data that aggregates self-collected demonstrations and corrective trajectories from real-robot failures across multiple folding tasks through a human-in-the-loop Data Aggregation~(DAgger) pipeline. Experiments show that DeMaVLA achieves competitive performance on RoboTwin and strong real-world results on our household folding benchmark. These results highlight the value of scalable real-world data, efficient action generation, and corrective learning for general-purpose VLA policies in deformable-object manipulation.
### Title:
          Latent Space Disentanglement via Activation Steering for Interpretable Attribute Control in Symbolic Music Generation
 - **Authors:** Ioannis Prokopiou, Pantelis Vikatos, Maximos Kaliakatsos-Papakostas, Theodoros Giannakopoulos, Themos Stafylakis
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI); Information Retrieval (cs.IR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based architectures have significantly advanced the generation of complex symbolic sequences, yet a significant gap remains in achieving fine-grained, interpretable control over discrete signal attributes. This paper investigates the mechanistic interpretability of the Multitrack Music Transformer (MMT) and proposes a framework for deterministic attribute modulation without retraining to bridge this gap via inference-time activation steering. Utilizing the Difference-in-Means (DiffMean) methodology, we isolate latent directions for signal attributes, specifically Pitch and Duration, within the residual stream. We validate the Linear Representation Hypothesis in this domain, achieving high correlation between steering magnitude and attribute shift. To address the inherent feature entanglement in multi-attribute steering, we introduce a Dual Steering framework utilizing Gram-Schmidt Orthogonalization. Experimental results demonstrate that this geometric decoupling reduces conceptual interference and signal degradation compared to naive vector addition, enabling independent deterministic control even against strong autoregressive conditioning.
### Title:
          Target-Side Paraphrase Augmentation for Sign Language Translation with Large Language Models
 - **Authors:** Pedro Dal Bianco, Jean Paul Nunes Reinhold, Oscar Stanchi, Facundo Quiroga, Franco Ronchetti, Ulisses Brisolara Corrêa
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sign language translation (SLT) remains constrained by limited paired sign-video/text corpora and heavy-tailed target vocabularies. We study target-side augmentation in which GPT-4o generates controlled paraphrase variants of reference sentences while the sign input remains unchanged. A Signformer-style pose-based Transformer is trained under a two-stage schedule: pre-training on the augmented corpus followed by fine-tuning on the original references. We evaluate on three datasets spanning complementary challenges: PHOENIX14T (German Sign Language), with moderate lexical diversity; GSL (Greek Sign Language), with highly ontrolled, repetitive recordings; and LSA-T (Argentinian Sign Language), with severe long-tail sparsity. On PHOENIX14T, augmentation improves BLEU-4 from 9.56 to 10.33. The near-saturated GSL baseline and extremely sparse LSA-T setting reveal the limits of the approach. To our knowledge, this is the first study to apply LLM-generated target-side araphrases and LLM-as-a-Judge evaluation to SLT. The semantic evaluation reveals gains in fidelity that lexical overlap metrics understate.
### Title:
          Fixed Universal Transformers
 - **Authors:** Jingwen Liu, Alexandr Andoni, Daniel Hsu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce \emph{universal transformers}: fixed transformers that can simulate any transformer in a given class via a suitable input embedding. Analogous to a universal Turing machine, the input embedding encodes a description of the target model while all internal parameters remain fixed. We provide explicit sparse constructions achieving universality when the embedding dimension is sufficiently large, and further show that universality is generic: randomly initialized transformers are universal almost surely, which aligns with recent empirical results of Zhong and Andreas (2024). We empirically validate our theory on the algorithmic tasks of parenthesis balancing and multi-hop reasoning. Our results suggest that much of a transformer's expressive power may reside in its input representation rather than its learned weights.
### Title:
          Shaft-integrated Force Sensing with Transformer-based Dynamics Compensation for Telesurgery
 - **Authors:** Shuyuan Yang, Grant Boone, Timo Markert, Sebastian Matich, Andreas Theissler, Martin Atzmueller, Zonghe Chua
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robot-Assisted Minimally Invasive Surgery (RAMIS) enhances surgeon dexterity, with newer platforms leveraging haptic feedback to further improve performance. Such force information has broader potential to inform performance assessment, tactile localization, and surgical autonomy. This motivates the need for accessible approaches to integrating force sensing into RAMIS tools. This work presents a method for integrating a six-axis commercial force sensor into the distal end of a standard cable-driven surgical instrument, enabling end-effector force measurement while preserving the original mechanical functionality of the device. The proposed design emphasizes reproducibility and accessibility for research applications, requiring no specialized manufacturing tools. A transformer neural network integrates force sensor measurements with robot state information to aid estimation of applied forces at the end-effector, compensating for internal cable forces arising from actuation. Our proposed approach achieved normalized errors below 6%, and generalized to unseen conditions better than purely proximal data-driven sensing approaches. High internal cable forces caused sensor saturation and reduced axial force observability, which can degrade performance along the tool's major axis and under higher load conditions. Given current levels of performance, the balance of system integrability and performance enables applications and research into timely topics of haptic feedback, skill assessment, and force-informed autonomy in RAMIS. Videos and code are available at this https URL force sensing.
### Title:
          VolFill: Single-View Amodal 3D Scene Reconstruction with Volumetric Flow Matching
 - **Authors:** Tuan Duc Ngo, Chuang Gan, Evangelos Kalogerakis
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reconstructing the complete geometry of a scene from a single RGB image remains challenging - especially when inferring hidden structures where visual evidence is incomplete. We introduce VolFill, a generative framework that predicts the 3D structure of the complete scene rather than relying on traditional pixel-aligned regression. Our method utilizes a hybrid 3D VAE to compress sparse truncated unsigned distance function grids into a compact latent space, paired with a latent Diffusion Transformer that denoises this representation to recover the complete scene. We condition the generation on geometry foundation models, leveraging rich spatial priors for robust reasoning. Unlike existing methods limited by per-ray constraints or unstructured point-cloud queries, VolFill provides a structured representation that supports direct surface extraction and occupancy queries at scale. Extensive experiments on the SCRREAM and NRGB-D datasets demonstrate that our approach significantly outperforms current baselines, providing a robust foundation for holistic spatial understanding.
### Title:
          Assign and Add: A Mechanistic Study of Compositional Arithmetic
 - **Authors:** Brady Exoo, Alberto Bietti, John Sous
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models are able to compose skills in order to perform complex tasks, many of which might not have been seen during training. The details of how exactly this composition occurs remain elusive. In this paper, we study a mechanism for compositional generalization in transformers by considering a simple controlled setting involving variable assignment and modular addition. By partitioning our training data into disjoint sets, we observe that small transformers are able to generalize to previously unseen combinations of variables and numbers. Our mechanistic analysis shows that the same ``modular addition'' MLP module is used whether the inputs are given directly or indirectly through a separate variable assignment mechanism. We also analyze the training dynamics from an empirical lens, which reveals three phases of learning: first, modular addition is learned, then the structure required for variable assignment, and finally a refinement phase where the model generalizes to some hard sequences not seen in training. Finally, we provide a theoretical framework to explain how compositionality emerges from training dynamics. These results suggest that compositional generalization can be a natural consequence of the compositionality of internal mechanisms in~transformers.
### Title:
          On Efficient Scaling of GNNs via IO-Aware Layers Implementations
 - **Authors:** Daria Fomina, Daniil Krasylnikov, Alexey Boykov, Andrey Dolgovyazov, Vyacheslav Zhdanovskiy, Fedor Velikonivtsev
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Graph Neural Networks (GNNs) are bottlenecked by sparse, irregular memory access. Popular frameworks such as DGL and PyTorch Geometric support general message passing, but complex layers often materialize edge-wise intermediates, increasing memory traffic and limiting scalability on large graphs. We take an I/O- and arithmetic-intensity--centric view and show that widely used layers fall into three kernel families: SpMM-based convolutions, reduction-based aggregations, and attention-based layers (GATv2/Graph Transformer). For each family, we develop GPU kernels that reduce data movement, improve locality, and remain robust across realistic graphs. We also study graph reordering and find that its impact depends on the kernel mapping: it benefits neighbor-parallel (gather-dominated) kernels more consistently than feature-parallel designs. Empirically, our fused attention kernels reach up to $\textbf{3.9}\times$ speedup for Graph Transformer (median $\textbf{1.6}\times$), with Tensor Core (block-sparse) variants up to $\textbf{7.3}\times$ on locally dense graphs; for GATv2 we reach up to $\textbf{8.5}\times$ speedup (median $\textbf{2.0}\times$) while reducing peak memory by up to $\textbf{76}\times$ (median $\textbf{6}\times$). Our degree-aware reduction kernels achieve up to $\textbf{10}\times$ speedup (median $\textbf{2.6}\times$). For SpMM-based layers, properly cached cuSPARSE achieves up to $\textbf{8}\times$ speedup over DGL and outperforms evaluated custom baselines in the majority of evaluations. We release our implementations as drop-in replacements to support reproducible, hardware-aware GNN acceleration.
### Title:
          How can embedding models bind concepts?
 - **Authors:** Arnas Uselis, Darina Koishigarina, Seong Joon Oh
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Humans easily determine which color belongs to which shape in multi-object scenes, an ability known as concept binding. Vision-language embedding models such as CLIP struggle with binding: they recognize individual concepts but fail to represent which concepts form which objects. Although CLIP behaves like a bag-of-concepts model in cross-modal retrieval, object information is recoverable from its image and text embeddings separately. We study this tension through the binding function, which maps concepts to scene embeddings. We find that scene embeddings decompose additively into object representations, explaining why uni-modal probes can recover object information. However, CLIP's binding function is high-complexity, which likely prevents the image and text encoders from learning a shared binding mechanism that generalizes to unseen concept combinations. We then ask whether this limitation is fundamental. We show that it is not. In controlled transformer models trained from scratch, binding generalization emerges with sufficient data coverage. These models learn low-complexity binding functions characterized by multiplicative interactions between concepts, enabling systematic generalization. Code is publicly available at this https URL.
### Title:
          Reliable Multilingual Orthopedic Decision Support from Clinical Narratives: Language-Aware Adaptation and Verification-Guided Deferral
 - **Authors:** Danish Ali, Li Xiaojian, Sundas Iqbal, Farrukh Zaidi
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multilingual orthopedic decision support remains challenging in low-resource healthcare settings, where clinical narratives contain specialized terminology, mixed scripts, incomplete evidence, label imbalance and language-dependent documentation patterns. This article presents a reliability-oriented framework for classifying free-text orthopedic notes in English, Hindi and Punjabi. We compare task-aligned multilingual transformer encoders, a task-fine-tuned DistilBERT baseline, zero-shot instruction-tuned large language models (LLMs) and a domain-adaptive encoder, IndicBERT-HPA. IndicBERT-HPA augments IndicBERT with language-aware orthopedic adapter heads to support clinically relevant multilingual representation learning. Evaluation extends beyond aggregate accuracy to per-class performance, ROC-AUC, AUPRC, expected calibration error, cross-language stability and robustness under controlled balanced and natural-prevalence distributions. The evaluated zero-shot LLMs remain substantially less effective than task-adapted encoders for closed-set classification, with language-dependent instability. Under natural clinical prevalence, IndicBERT-HPA achieves the strongest overall performance, reaching an averaged Macro-F1 of 0.8792, Macro-AUROC of 0.894 and AUPRC of 0.902. We further implement a deterministic selective-verification layer combining confidence gating, evidence-consistency checking and language-risk screening. On a randomly selected held-out 5,000-record subset, it achieves 84.4% selective accuracy and 0.76 selective Macro-F1 at 72.3% coverage, compared with 71.5% accuracy and 0.65 Macro-F1 for accept-all prediction. These results support reliability-oriented multilingual clinical decision support with explicit deferral.
### Title:
          RayDer: Scalable Self-Supervised Novel View Synthesis from Real-World Video
 - **Authors:** Ulrich Prestel, Stefan Andreas Baumann, Nick Stracke, Björn Ommer
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-supervised novel view synthesis (NVS) remains challenging to scale, despite the abundance of video data, largely due to the brittleness of training on realistic videos and the hard-to-predict scaling behavior of multi-network system designs. We introduce RayDer, a unified, feed-forward transformer that consolidates camera estimation, scene reconstruction, and rendering into a single backbone, turning self-supervised NVS into a well-posed single-model scaling problem. A minimal dynamic state, treated as a nuisance factor, absorbs time-varying content and enables stable training on unconstrained real-world video. Importantly, RayDer keeps static-scene NVS as its target task: dynamic content is leveraged purely as scalable supervision, not reconstructed as in dynamic-scene (4D) NVS. Across multiple model sizes and orders of magnitude in data, RayDer exhibits clean power-law scaling with data and compute, and outperforms static-scene data mixtures. On a large number of benchmarks, RayDer achieves strong zero-shot open-set performance competitive with state-of-the-art supervised approaches. Project Page: this https URL
### Title:
          Positional versus Symbolic Attention Heads: Learning Dynamics, RoPE Geometry, and Length Generalization
 - **Authors:** Felipe Urrutia, Juan José Alegría, Cinthia Sanchez Macias, Jorge Salas, Cristian B. Calderon, Cristobal Rojas
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based language models are widespread in today's society. As such, understanding the mechanisms by which they solve structured tasks and predicting how they may behave in novel scenarios is of great importance for safe deployment. We study the learning dynamics of attention heads in a controlled setting by training a decoder-only Transformer (GPT-J) on two structurally equivalent multi-hop reasoning tasks: a number task requiring positional reasoning and a letter task requiring symbolic reasoning. Using a recently introduced metric that classifies attention-head behavior as positional or symbolic for a given prompt, we show that successful learning is associated with the emergence of pure heads, i.e., heads that express themselves as either positional or symbolic. Despite the tasks' structural equivalence, they impose different mechanistic demands: the number task requires both positional and symbolic heads, whereas the letter task requires only symbolic heads. We then identify the computational roles of these heads, characterize the basic functions they implement, and give theoretical constructions showing how single-layer RoPE-based attention can realize these functions through geometrically interpretable query, key, and value operations. This analysis yields a quantitative separation between positional and symbolic mechanisms in their robustness to longer sequences, formalized through a novel notion of discrepancy. We empirically validate the resulting predictions in both controlled and real-world models, showing that symbolic mechanisms extrapolate more reliably to longer sequences while positional mechanisms face sharper limitations.
### Title:
          Functional Attention: From Pairwise Affinities to Functional Correspondences
 - **Authors:** Jiefang Xiao, Maolin Gao, Simon Weber, Guandao Yang, Daniel Cremers
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning mappings between infinite-dimensional function spaces, or operator learning, is essential for many machine learning applications. Although transformer-based operators are popular, they often rely on token-wise attention. These methods treat continuous fields as discrete tokens and usually ignore the global functional structure. We introduce \emph{Functional Attention}, which reinterprets attention as a functional correspondence between adaptive bases. Inspired by geometric functional maps, our method replaces softmax affinities with structured linear operators. This yields a compact, generalizable, resolution-invariant representation that explicitly captures global dependencies. Experiments demonstrate that \emph{Functional Attention} can match state-of-the-art performance in many operator learning tasks, including solving PDEs, 3D segmentation, and regression, while remaining robust to varying discretizations. Project page is available at this https URL.
### Title:
          What Gets Unmasked First? Trajectory Analysis of Diffusion Models for Graph-to-Text Generation
 - **Authors:** Qing Wang, Jacob Devasier, Chengkai Li
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present the first systematic study of masked diffusion language models (MDLMs) for graph-to-text generation. We analyze MDLM generation trajectories -- the order in which tokens are unmasked during iterative decoding -- and find that, unlike autoregressive LLMs which generate text linearly, MDLMs naturally prioritize entities first, followed by relational and function words, with structural tokens resolved last. We further identify a previously undocumented failure mode of supervised fine-tuning: SFT disrupts this strategy by prematurely anchoring structural sentence-ending tokens early in the decoding trajectory, effectively fixing the output length which can lead to omitted or hallucinated information. To address this, we propose lambda-scaled structural decoding, a training-free inference-time modification that downweights structural token confidence and recovers +9.4 BLEU-4. Finally, we introduce Graph-LLaDA, which integrates a Graph Transformer encoder into LLaDA's decoding process to explicitly incorporate relational graph structure. Cross-dataset evaluation on LAGRANGE reveals that previous baselines overfit to dataset-specific patterns, while LLM- and MDLM-based approaches generalize significantly better.
### Title:
          Giving Sensors a Voice: Multimodal JEPA for Semantic Time-Series Embeddings
 - **Authors:** Utsav Dutta, Gerardo Pastrana, Sina Khoshfetrat Pakazad, Henrik Ohlsson
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based architectures have advanced sequence modeling in language and vision, yet general-purpose representation learning for heterogeneous multivariate time series remains underexplored. We introduce CHARM (Channel-Aware Representation Model), which incorporates channel-level textual descriptions into a Transformer encoder equivariant to channel order. CHARM is trained with a Joint Embedding Predictive Architecture (JEPA) and a novel loss promoting informative, temporally stable embeddings; latent-space prediction encourages robustness to sensor noise while description-aware gating provides interpretability through learned inter-channel relationships. Across anomaly detection, classification, and short- and long-term forecasting, the learned embeddings achieve strong performance using only a linear probe. Performance is driven primarily by the JEPA objective and conditioning architecture, with text descriptions serving as channel identifiers for cross-dataset generalization.
### Title:
          TunerDiT: Training-free Progressive Steering of Diffusion Transformer for Multi-Event Video Generation
 - **Authors:** Ruotong Liao, Guowen Huang, Qing Cheng, Guangyao Zhai, Lei Zhang, Xun Xiao, Thomas Seidl, Daniel Cremers, Volker Tresp
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-to-video (T2V) generation faces challenging questions when generating videos with long horizons containing multiple events. Inspired by the intrinsics of the diffusion process, we probe video diffusion transformers (DiTs) and uncover intrinsic turning points in the DiT denoising trajectory where conditioning text affects generation from global layout to fine-grained details. Building on this finding, we present TunerDiT, a simple yet effective progressive steering method that requires no additional training for multi-event generation. TunerDiT comprises two steering handles: (1) Event-Partitioned Masking that enforces event boundaries while allowing cross-event transition bands; (2) Cross-Event Prompt Fusion that injects neighboring event semantics for late-stage refinement. We contribute a self-curated prompt suite for benchmarking multi-event generation, i.e., Meve. TunerDiT achieves state-of-the-art performance across 8 metrics and offers a tunable trade-off between video consistency and event separation, compared with other training-free methods. The improvement in text alignment increases with the event count, indicating a scaling possibility with increasing event count.
## Keyword: autonomous driving
### Title:
          Uncertainty-Aware and Temporally Regulated Expert Advice in Reinforcement Learning for Autonomous Driving
 - **Authors:** Ahmed Abouelazm, Felix Klingebiel, Philip Schörner, J. Marius Zöllner
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Exploration in reinforcement learning for autonomous driving is inherently unsafe: agents must experience novel behaviors to learn, yet exploration can lead to collisions or off-road driving. We propose an uncertainty-aware framework that leverages expert advice to guide exploration while avoiding long-term dependence. Advice is triggered when epistemic or aleatoric uncertainty exceeds adaptive thresholds derived from rolling buffers, ensuring advice evolves with the agent's confidence. A commitment-cooldown strategy with a stochastic early-stop heuristic regulates the duration and frequency of guidance, exposing the agent to coherent maneuvers without exhausting the advice budget. Expert and agent experiences are combined in a shared replay buffer within an off-policy implicit quantile network (IQN) backbone, enabling efficient reuse of expert trajectories. Experiments in CARLA show that our method outperforms the IQN baseline, improving success by 5-7% and reducing failures, demonstrating that risk-sensitive uncertainty coupled with regulated expert integration enables safer and more efficient exploration for sensor-based RL policy learning in unsignalized intersection navigation.
### Title:
          IAF-Net: Illumination-Adaptive Fusion for Low-Light Urban Road Segmentation
 - **Authors:** Bingtao Wang, Daojie Peng, Fulong Ma, Jun Ma, Liang Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic road segmentation is important for autonomous driving, but existing methods suffer severe performance degradation under low-light conditions. Many existing multi-modal fusion methods do not explicitly adapt to illumination-dependent changes in modality reliability, which can propagate degraded RGB features into the fused representation at night. We propose IAF-Net (Illumination-Adaptive Fusion Network), an end-to-end framework with illumination-adaptive fusion for robust road segmentation across different lighting conditions. It dynamically adjusts fusion weights of RGB and geometric features via the core Illumination-Adaptive Fusion (IAF) module, and enhances low-light feature selection with a brightness-modulated attention decoder. We also construct two dedicated datasets: nuScenes Nighttime Road Segmentation (nuScenes-NRS) and CARLA Multi-Weather Road Segmentation (CARLA-MWRS). Experiments on nuScenes-NRS show state-of-the-art overall performance among the compared methods, while CARLA-MWRS further validates robustness across adverse weather conditions. Ablation studies on a 40% training subset further highlight the importance of the IAF module, which provides the largest individual gain of 0.70% in MaxF.
### Title:
          Can BEV Perception Gracefully Degrade under Sensor Failures?
 - **Authors:** Haifa Zhang, Yijing Wang, Haoyu Wang, Zheng Li, Zhiqiang Zuo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite the remarkable success of multi-modal bird's-eye view (BEV) perception in autonomous driving, current systems exhibit a critical vulnerability: existing fusion mechanisms are highly brittle to sensor corruptions, often causing catastrophic performance degradation. This vulnerability largely stems from the fact that standard fusion frameworks typically integrate multi-modal representations in a static manner, leading to a precipitous performance collapse under missing or corrupted modalities. In contrast, we show that graceful degradation is achievable through active modality reliability assessment. To this end, we present Grace-BEV, a lightweight and plug-and-play framework that enforces active reliability awareness during multi-modal fusion. Instead of relying on computationally expensive cross-modal interactions, Grace-BEV leverages the aligned BEV space to explicitly assess modality trustworthiness via a TrustGate Router and dynamically recalibrate feature integration using the FailSafe Fusion Block. Furthermore, we devise a Three-Phase Training strategy with Modality Dropout to prevent modality dominance and encourage balanced cross-modal learning under unreliable inputs. Extensive experiments on nuScenes-R and nuScenes-C show that Grace-BEV maintains robust performance across diverse corruption settings. Notably, under catastrophic LiDAR failures where standard baselines collapse to 0.0% mean Average Precision (mAP), Grace-BEV restores performance to as high as 34.7% mAP. Moreover, it improves clean accuracy by up to 1.4%, achieving a strong trade-off between robustness and efficiency.
### Title:
          Does Visual Information Play a Decisive Role in Vision-Language-Action Model Driving Behavior?
 - **Authors:** Jingtao He, Hongliang Lu, Xiaoyun Qiu, Yixuan Wang, Xinhu Zheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models have demonstrated promising capability in autonomous driving, highlighting the potential of unified multimodal architectures for jointly modeling perception and planning. However, how current VLA-based driving behavior is grounded in visual information remains poorly understood. Existing evaluation protocols mainly focus on aggregate performance metrics, lacking structured and practical diagnostics to quantify visual-behavior dependency. In this work, we introduce a structured multi-level visual perturbation framework to analyze visual-behavior dependency in VLA-based driving models systematically. The framework organizes controlled visual perturbations along three complementary dimensions: channellevel degradation, information-level disruption, and structurelevel modification. We apply it to VLA-based driving systems and evaluate behavioral responses under both open-loop trajectory prediction and interactive closed-loop safety evaluation. Experimental results reveal evaluation-dependent dependency patterns and uneven visual grounding across abstraction levels. These findings call for more structured analyses and principled design of VLA driving models to better understand how visual information shapes behavior and develop safer, more robust systems.
### Title:
          NTR: Neural Token Reconstruction for Scene Token Bottleneck in End-to-End Driving
 - **Authors:** Jiahui Li, Jiawei Sun, Zixiang Ren, Ming Liu, Jiamin Shi, Ruiteng Zhao, Zhiyang Liu, Liying Liu, Zuoguan Wang, Kaidi Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent perception-free end-to-end (E2E) autonomous driving methods bypass explicit perception outputs by compressing dense image patch tokens into compact scene tokens for downstream trajectory generation and scoring. While these scene tokens form a compact visual bottleneck for the planner, they receive supervision solely from the planning objective, providing limited constraints on the encoded visual information. To address this limitation, we introduce Neural Token Reconstruction (NTR), a representation learning framework to directly constrain the compact scene-token bottleneck in perception-free driving. NTR introduces a self-distillation masked latent reconstruction objective that reconstructs masked patch-level latent features using only compact scene tokens as reconstruction memory. This forces reconstruction gradients to pass exclusively through the scene-token bottleneck, encouraging scene tokens to preserve richer and less redundant visual representations for planning. We further introduce semantic priors derived from foundation-model annotations as a weak semantic interface biasing reconstruction targets toward driving-related structures without introducing explicit perception heads. All auxiliary reconstruction components are removed at inference time, leaving the deployed planner unchanged. NTR achieves state-of-the-art performance on three public autonomous driving benchmarks, including 8.0461 RFS on Waymo E2E and 94.1 PDMS / 90.9 EPDMS on NavSim1&2. The learned scene tokens exhibit lower pairwise redundancy and higher effective rank, indicating that effective bottleneck supervision improves both compact visual representation learning and planning performance.
### Title:
          IDOL: Inverse-Dynamics-Guided Future Prediction for End-to-End Autonomous Driving
 - **Authors:** Chenghao Zhang, Timin Li, Dongmei Li
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end autonomous driving has emerged as a compelling paradigm for learning planning directly from sensor observations, while recent world-model-based approaches further enrich this paradigm by enabling explicit reasoning about how the scene may evolve in the future. Yet future prediction alone does not guarantee better planning unless the predicted evolution can be converted into planning-relevant trajectory updates. Many current methods still forecast future scene states without explicitly decoding the motion implications hidden in state transitions. As a result, future reasoning often remains descriptively useful but only weakly coupled to executable motion generation. To address this limitation, we propose \mathbf{IDOL}, an inverse-dynamics-guided future prediction framework for world-model-based end-to-end planning in latent BEV space, where inverse dynamics serves as the key bridge between future prediction and trajectory optimization. IDOL first predicts multiple future latent scene states with a BEV world model, then applies an inverse dynamics model to adjacent latent futures to decode transition-aware trajectory features and recover planning-relevant motion deltas that explain how the latent world evolves over time. These inverse-dynamics-derived signals are used to optimize the planned trajectory, turning future forecasting from passive scene anticipation into actionable planning guidance. A lightweight closed-loop refinement module further improves long-horizon consistency by reusing the optimized trajectory for another round of future-aware reasoning. By introducing inverse dynamics into latent future reasoning, IDOL tightens the coupling between world modeling and planning. Extensive experiments on the NAVSIM v1 and NAVSIM v2 benchmarks show that IDOL achieves state-of-the-art performance among comparable methods.
### Title:
          nuReasoning: A Reasoning-Centric Dataset and Benchmark for Long-Tail Autonomous Driving
 - **Authors:** Zhiyu Huang, Johnson Liu, Rui Song, Zewei Zhou, Ruining Yang, Yun Zhang, Tianhui Cai, Hanyin Zhang, Mingxuan Gao, Valeria Xu, Jiali Chen, Yishan Shen, Yiluan Guo, Tony (Xuewei)Qi, Jiaqi Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reasoning is essential for autonomous driving (AD) in long-tail scenarios, where vehicles must apply commonsense knowledge, understand spatial relations, infer agent interactions, and make safe decisions. However, existing AD datasets and benchmarks mainly target perception, prediction, or planning, and provide limited supervision for reasoning over realistic long-tail driving scenes. We introduce nuReasoning, a large-scale real-world dataset and benchmark for reasoning-centric AD. Following the lineage of nuScenes and nuPlan, nuReasoning advances real-world AD datasets and benchmarks toward reasoning in long-tail driving scenarios. The dataset contains 20,000 clips, each 20 seconds long, collected across multiple cities, with synchronized multi-camera images, LiDAR data, HD maps, object annotations, and human-verified reasoning annotations spanning Spatial Reasoning, Decision Reasoning, and Counterfactual Reasoning. Unlike prior datasets that focus primarily on visual question answering, nuReasoning supports both reasoning evaluation and planning evaluation, enabling a direct study of how reasoning supervision affects driving performance. Experiments show that fine-tuning VLMs on nuReasoning substantially improves driving-specific question answering, while incorporating reasoning supervision into VLA training improves planning performance even when textual reasoning outputs are disabled at inference time. These results establish nuReasoning as a foundation for evaluating and improving robust, interpretable, reasoning-driven AD systems in realistic long-tail settings.
