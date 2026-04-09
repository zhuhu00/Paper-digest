# Showing new listings for Thursday, 9 April 2026
## Keyword: SLAM
### Title:
          The Theorems of Dr. David Blackwell and Their Contributions to Artificial Intelligence
 - **Authors:** Napoleon Paxton
 - **Subjects:** Subjects:
General Literature (cs.GL); Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dr. David Blackwell was a mathematician and statistician of the first rank, whose contributions to statistical theory, game theory, and decision theory predated many of the algorithmic breakthroughs that define modern artificial intelligence. This survey examines three of his most consequential theoretical results the Rao Blackwell theorem, the Blackwell Approachability theorem, and the Blackwell Informativeness theorem (comparison of experiments) and traces their direct influence on contemporary AI and machine learning. We show that these results, developed primarily in the 1940s and 1950s, remain technically live across modern subfields including Markov Chain Monte Carlo inference, autonomous mobile robot navigation (SLAM), generative model training, no-regret online learning, reinforcement learning from human feedback (RLHF), large language model alignment, and information design. NVIDIAs 2024 decision to name their flagship GPU architecture (Blackwell) provides vivid testament to his enduring relevance. We also document an emerging frontier: explicit Rao Blackwellized variance reduction in LLM RLHF pipelines, recently proposed but not yet standard practice. Together, Blackwell theorems form a unified framework addressing information compression, sequential decision making under uncertainty, and the comparison of information sources precisely the problems at the core of modern AI.
### Title:
          Exploring 6D Object Pose Estimation with Deformation
 - **Authors:** Zhiqiang Liu, Rui Song, Duanmu Chuangqi, Jiaojiao Li, David Ferstl, Yinlin Hu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present DeSOPE, a large-scale dataset for 6DoF deformed objects. Most 6D object pose methods assume rigid or articulated objects, an assumption that fails in practice as objects deviate from their canonical shapes due to wear, impact, or deformation. To model this, we introduce the DeSOPE dataset, which features high-fidelity 3D scans of 26 common object categories, each captured in one canonical state and three deformed configurations, with accurate 3D registration to the canonical mesh. Additionally, it features an RGB-D dataset with 133K frames across diverse scenarios and 665K pose annotations produced via a semi-automatic pipeline. We begin by annotating 2D masks for each instance, then compute initial poses using an object pose method, refine them through an object-level SLAM system, and finally perform manual verification to produce the final annotations. We evaluate several object pose methods and find that performance drops sharply with increasing deformation, suggesting that robust handling of such deformations is critical for practical applications. The project page and dataset are available at this https URL}{this https URL.
### Title:
          VGGT-SLAM++
 - **Authors:** Avilasha Mandal, Rajesh Kumar, Sudarshan Sunil Harithas, Chetan Arora
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce VGGT-SLAM++, a complete visual SLAM system that leverages the geometry-rich outputs of the Visual Geometry Grounded Transformer (VGGT). The system comprises a visual odometry (front-end) fusing the VGGT feed-forward transformer and a Sim(3) solution, a Digital Elevation Map (DEM)-based graph construction module, and a back-end that jointly enable accurate large-scale mapping with bounded memory. While prior transformer-based SLAM pipelines such as VGGT-SLAM rely primarily on sparse loop closures or global Sim(3) manifold constraints - allowing short-horizon pose drift - VGGT-SLAM++ restores high-cadence local bundle adjustment (LBA) through a spatially corrective back-end. For each VGGT submap, we construct a dense planar-canonical DEM, partition it into patches, and compute their DINOv2 embeddings to integrate the submap into a covisibility graph. Spatial neighbors are retrieved using a Visual Place Recognition (VPR) module within the covisibility window, triggering frequent local optimization that stabilizes trajectories. Across standard SLAM benchmarks, VGGT-SLAM++ achieves state-of-the-art accuracy, substantially reducing short-term drift, accelerating graph convergence, and maintaining global consistency with compact DEM tiles and sublinear retrieval.
### Title:
          An RTK-SLAM Dataset for Absolute Accuracy Evaluation in GNSS-Degraded Environments
 - **Authors:** Wei Zhang, Vincent Ress, David Skuddis, Uwe Soergel, Norbert Haala
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 RTK-SLAM systems integrate simultaneous localization and mapping (SLAM) with real-time kinematic (RTK) GNSS positioning, promising both relative consistency and globally referenced coordinates for efficient georeferenced surveying. A critical and underappreciated issue is that the standard evaluation metric, Absolute Trajectory Error (ATE), first fits an optimal rigid-body transformation between the estimated trajectory and reference before computing errors. This so-called SE(3) alignment absorbs global drift and systematic errors, making trajectories appear more accurate than they are in practice, and is unsuitable for evaluating the global accuracy of RTK-SLAM. We present a geodetically referenced dataset and evaluation methodology that expose this gap. A key design principle is that the RTK receiver is used solely as a system input, while ground truth is established independently via a geodetic total station. This separation is absent from all existing datasets, where GNSS typically serves as (part of) the ground truth. The dataset is collected with a handheld RTK-SLAM device, comprising two scenes. We evaluate LiDAR-inertial, visual-inertial, and LiDAR-visual-inertial RTK-SLAM systems alongside standalone RTK, reporting direct global accuracy and SE(3)-aligned relative accuracy to make the gap explicit. Results show that SE(3) alignment can underestimate absolute positioning error by up to 76\%. RTK-SLAM achieves centimeter-level absolute accuracy in open-sky conditions and maintains decimeter-level global accuracy indoors, where standalone RTK degrades to tens of meters. The dataset, calibration files, and evaluation scripts are publicly available at this https URL.
### Title:
          RoSHI: A Versatile Robot-oriented Suit for Human Data In-the-Wild
 - **Authors:** Wenjing Margaret Mao, Jefferson Ng, Luyang Hu, Daniel Gehrig, Antonio Loquercio
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scaling up robot learning will likely require human data containing rich and long-horizon interactions in the wild. Existing approaches for collecting such data trade off portability, robustness to occlusion, and global consistency. We introduce RoSHI, a hybrid wearable that fuses low-cost sparse IMUs with the Project Aria glasses to estimate the full 3D pose and body shape of the wearer in a metric global coordinate frame from egocentric perception. This system is motivated by the complementarity of the two sensors: IMUs provide robustness to occlusions and high-speed motions, while egocentric SLAM anchors long-horizon motion and stabilizes upper body pose. We collect a dataset of agile activities to evaluate RoSHI. On this dataset, we generally outperform other egocentric baselines and perform comparably to a state-of-the-art exocentric baseline (SAM3D). Finally, we demonstrate that the motion data recorded from our system are suitable for real-world humanoid policy learning. For videos, data and more, visit the project webpage: this https URL
## Keyword: odometry
### Title:
          VGGT-SLAM++
 - **Authors:** Avilasha Mandal, Rajesh Kumar, Sudarshan Sunil Harithas, Chetan Arora
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce VGGT-SLAM++, a complete visual SLAM system that leverages the geometry-rich outputs of the Visual Geometry Grounded Transformer (VGGT). The system comprises a visual odometry (front-end) fusing the VGGT feed-forward transformer and a Sim(3) solution, a Digital Elevation Map (DEM)-based graph construction module, and a back-end that jointly enable accurate large-scale mapping with bounded memory. While prior transformer-based SLAM pipelines such as VGGT-SLAM rely primarily on sparse loop closures or global Sim(3) manifold constraints - allowing short-horizon pose drift - VGGT-SLAM++ restores high-cadence local bundle adjustment (LBA) through a spatially corrective back-end. For each VGGT submap, we construct a dense planar-canonical DEM, partition it into patches, and compute their DINOv2 embeddings to integrate the submap into a covisibility graph. Spatial neighbors are retrieved using a Visual Place Recognition (VPR) module within the covisibility window, triggering frequent local optimization that stabilizes trajectories. Across standard SLAM benchmarks, VGGT-SLAM++ achieves state-of-the-art accuracy, substantially reducing short-term drift, accelerating graph convergence, and maintaining global consistency with compact DEM tiles and sublinear retrieval.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Telescope: Learnable Hyperbolic Foveation for Ultra-Long-Range Object Detection
 - **Authors:** Parker Ewen, Dmitriy Rivkin, Mario Bijelic, Felix Heide
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous highway driving, especially for long-haul heavy trucks, requires detecting objects at long ranges beyond 500 meters to satisfy braking distance requirements at high speeds. At long distances, vehicles and other critical objects occupy only a few pixels in high-resolution images, causing state-of-the-art object detectors to fail. This challenge is compounded by the limited effective range of commercially available LiDAR sensors, which fall short of ultra-long range thresholds because of quadratic loss of resolution with distance, making image-based detection the most practically scalable solution given commercially available sensor constraints. We introduce Telescope, a two-stage detection model designed for ultra-long range autonomous driving. Alongside a powerful detection backbone, this model contains a novel re-sampling layer and image transformation to address the fundamental challenges of detecting small, distant objects. Telescope achieves $76\%$ relative improvement in mAP in ultra-long range detection compared to state-of-the-art methods (improving from an absolute mAP of 0.185 to 0.326 at distances beyond 250 meters), requires minimal computational overhead, and maintains strong performance across all detection ranges.
### Title:
          RePL: Pseudo-label Refinement for Semi-supervised LiDAR Semantic Segmentation
 - **Authors:** Donghyeon Kwon, Taegyu Park, Suha Kwak
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semi-supervised learning for LiDAR semantic segmentation often suffers from error propagation and confirmation bias caused by noisy pseudo-labels. To tackle this chronic issue, we introduce RePL, a novel framework that enhances pseudo-label quality by identifying and correcting potential errors in pseudo-labels through masked reconstruction, along with a dedicated training strategy. We also provide a theoretical analysis demonstrating the condition under which the pseudo-label refinement is beneficial, and empirically confirm that the condition is mild and clearly met by RePL. Extensive evaluations on the nuScenes-lidarseg and SemanticKITTI datasets show that RePL improves pseudo-label quality a lot and, as a result, achieves the state of the art in LiDAR semantic segmentation.
### Title:
          An RTK-SLAM Dataset for Absolute Accuracy Evaluation in GNSS-Degraded Environments
 - **Authors:** Wei Zhang, Vincent Ress, David Skuddis, Uwe Soergel, Norbert Haala
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 RTK-SLAM systems integrate simultaneous localization and mapping (SLAM) with real-time kinematic (RTK) GNSS positioning, promising both relative consistency and globally referenced coordinates for efficient georeferenced surveying. A critical and underappreciated issue is that the standard evaluation metric, Absolute Trajectory Error (ATE), first fits an optimal rigid-body transformation between the estimated trajectory and reference before computing errors. This so-called SE(3) alignment absorbs global drift and systematic errors, making trajectories appear more accurate than they are in practice, and is unsuitable for evaluating the global accuracy of RTK-SLAM. We present a geodetically referenced dataset and evaluation methodology that expose this gap. A key design principle is that the RTK receiver is used solely as a system input, while ground truth is established independently via a geodetic total station. This separation is absent from all existing datasets, where GNSS typically serves as (part of) the ground truth. The dataset is collected with a handheld RTK-SLAM device, comprising two scenes. We evaluate LiDAR-inertial, visual-inertial, and LiDAR-visual-inertial RTK-SLAM systems alongside standalone RTK, reporting direct global accuracy and SE(3)-aligned relative accuracy to make the gap explicit. Results show that SE(3) alignment can underestimate absolute positioning error by up to 76\%. RTK-SLAM achieves centimeter-level absolute accuracy in open-sky conditions and maintains decimeter-level global accuracy indoors, where standalone RTK degrades to tens of meters. The dataset, calibration files, and evaluation scripts are publicly available at this https URL.
### Title:
          Geo-EVS: Geometry-Conditioned Extrapolative View Synthesis for Autonomous Driving
 - **Authors:** Yatong Lan, Rongkui Tang, Lei He
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Extrapolative novel view synthesis can reduce camera-rig dependency in autonomous driving by generating standardized virtual views from heterogeneous sensors. Existing methods degrade outside recorded trajectories because extrapolated poses provide weak geometric support and no dense target-view supervision. The key is to explicitly expose the model to out-of-trajectory condition defects during training. We propose Geo-EVS, a geometry-conditioned framework under sparse supervision. Geo-EVS has two components. Geometry-Aware Reprojection (GAR) uses fine-tuned VGGT to reconstruct colored point clouds and reproject them to observed and virtual target poses, producing geometric condition maps. This design unifies the reprojection path between training and inference. Artifact-Guided Latent Diffusion (AGLD) injects reprojection-derived artifact masks during training so the model learns to recover structure under missing support. For evaluation, we use a LiDAR-Projected Sparse-Reference (LPSR) protocol when dense extrapolated-view ground truth is unavailable. On Waymo, Geo-EVS improves sparse-view synthesis quality and geometric accuracy, especially in high-angle and low-coverage settings. It also improves downstream 3D detection.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          EviSnap: Faithful Evidence-Cited Explanations for Cold-Start Cross-Domain Recommendation
 - **Authors:** Yingjun Dai, Ahmed El-Roby
 - **Subjects:** Subjects:
Information Retrieval (cs.IR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cold-start cross-domain recommender (CDR) systems predict a user's preferences in a target domain using only their source-domain behavior, yet existing CDR models either map opaque embeddings or rely on post-hoc or LLM-generated rationales that are hard to audit. We introduce EviSnap a lightweight CDR framework whose predictions are explained by construction with evidence-cited, faithful rationales. EviSnap distills noisy reviews into compact facet cards using an LLM offline, pairing each facet with verbatim supporting sentences. It then induces a shared, domain-agnostic concept bank by clustering facet embeddings and computes user-positive, user-negative, and item-presence concept activations via evidence-weighted pooling. A single linear concept-to-concept map transfers users across domains, and a linear scoring head yields per-concept additive contributions, enabling exact score decompositions and counterfactual 'what-if' edits grounded in the cited sentences. Experiments on the Amazon Reviews dataset across six transfers among Books, Movies, and Music show that EviSnap consistently outperforms strong mapping and review-text baselines while passing deletion- and sufficiency-based tests for explanation faithfulness.
### Title:
          Consistency-Guided Decoding with Proof-Driven Disambiguation for Three-Way Logical Question Answering
 - **Authors:** Tianyi Huang, Ming Hou, Jiaheng Su, Yutong Zhang, Ziling Zhang
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Logic in Computer Science (cs.LO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Three-way logical question answering (QA) assigns $True/False/Unknown$ to a hypothesis $H$ given a premise set $S$. While modern large language models (LLMs) can be accurate on isolated examples, we identify two recurring failure modes in 3-way logic QA: (i) negation inconsistency, where answers to $H$ and $\neg H$ violate the deterministic label mapping, and (ii) epistemic $Unknown$, where the model predicts $Unknown$ due to uncertainty or instability even when $S$ entails one side. We present CGD-PD, a lightweight test-time layer that (a) queries a single 3-way classifier on both $H$ and a mechanically negated form of $H$, (b) projects the pair onto a negation-consistent decision when possible, and (c) invokes a proof-driven disambiguation step that uses targeted binary entailment probes to selectively resolve $Unknown$ outcomes, requiring only an average of 4-5 model calls. On the FOLIO benchmark's first-order-logic fields, CGD-PD yields consistent gains across frontier LLMs, with relative improvements in accuracy of up to 16% over the base model, while also reducing $Unknown$ predictions.
### Title:
          Distributional Open-Ended Evaluation of LLM Cultural Value Alignment Based on Value Codebook
 - **Authors:** Jaehyeok Lee, Xiaoyuan Yi, Jing Yao, Hyunjin Hwang, Roy Ka-Wei Lee, Xing Xie, JinYeong Bak
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Computers and Society (cs.CY); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As LLMs are globally deployed, aligning their cultural value orientations is critical for safety and user engagement. However, existing benchmarks face the Construct-Composition-Context ($C^3$) challenge: relying on discriminative, multiple-choice formats that probe value knowledge rather than true orientations, overlook subcultural heterogeneity, and mismatch with real-world open-ended generation. We introduce DOVE, a distributional evaluation framework that directly compares human-written text distributions with LLM-generated outputs. DOVE utilizes a rate-distortion variational optimization objective to construct a compact value-codebook from 10K documents, mapping text into a structured value space to filter semantic noise. Alignment is measured using unbalanced optimal transport, capturing intra-cultural distributional structures and sub-group diversity. Experiments across 12 LLMs show that DOVE achieves superior predictive validity, attaining a 31.56% correlation with downstream tasks, while maintaining high reliability with as few as 500 samples per culture.
### Title:
          Evidence-Based Actor-Verifier Reasoning for Echocardiographic Agents
 - **Authors:** Peng Huang, Yiming Wang, Yineng Chen, Liangqiao Gui, Hui Guo, Bo Peng, Shu Hu, Xi Wu, Tsao Connie, Hongtu Zhu, Balakrishnan Prabhakaran, Xin Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Echocardiography plays an important role in the screening and diagnosis of cardiovascular diseases. However, automated intelligent analysis of echocardiographic data remains challenging due to complex cardiac dynamics and strong view heterogeneity. In recent years, visual language models (VLM) have opened a new avenue for building ultrasound understanding systems for clinical decision support. Nevertheless, most existing methods formulate this task as a direct mapping from video and question to answer, making them vulnerable to template shortcuts and spurious explanations. To address these issues, we propose EchoTrust, an evidence-driven Actor-Verifier framework for trustworthy reasoning in echocardiography VLM-based agents. EchoTrust produces a structured intermediate representation that is subsequently analyzed by distinct roles, enabling more reliable and interpretable decision-making for high-stakes clinical applications.
### Title:
          Intimate Strangers by Design: A Uses and Gratifications Analysis of AI Companionship
 - **Authors:** Dayeon Eom, Julianne Renner, Sedona Chinn
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Conversational AI companions have grown prominent in public discourse, yet scholarly understanding of user experiences remains limited, with existing research organized around evaluative poles of harm and benefit rather than examining what users seek, how affordances mediate need fulfillment, or how use evolves over time. Drawing on interviews with 20 users of AI companionship platforms and qualitative content analysis informed by Uses and Gratifications (U&G) theory, this study offers three contributions. First, participants reported gratifications mapping onto established U&G categories but qualitatively inflected by conversational AI's distinctive affordances, such as persistent availability, personalization, and absence of social judgment. Second, several gratifications, creative collaboration as relational co-production, relational simulation as interpersonal training, and sexual/romantic satisfaction as reclamation, do not map onto existing typologies, instead emerging through interactive processes in which users actively simulate experiences with AI. Third, gratifications shifted over time, moving from instrumental entry points toward emotional engagement and, in some cases, self-regulated moderation after therapeutic functions were fulfilled. These findings extend U&G by identifying gratification processes unique to interactive AI and suggest governance efforts would benefit from an empirically grounded understanding of how and why users engage with AI companions.
### Title:
          AE-ViT: Stable Long-Horizon Parametric Partial Differential Equations Modeling
 - **Authors:** Iva Mikuš, Boris Muha, Domagoj Vlah
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep Learning Reduced Order Models (ROMs) are becoming increasingly popular as surrogate models for parametric partial differential equations (PDEs) due to their ability to handle high-dimensional data, approximate highly nonlinear mappings, and utilize GPUs. Existing approaches typically learn evolution either on the full solution field, which requires capturing long-range spatial interactions at high computational cost, or on compressed latent representations obtained from autoencoders, which reduces the cost but often yields latent vectors that are difficult to evolve, since they primarily encode spatial information. Moreover, in parametric PDEs, the initial condition alone is not sufficient to determine the trajectory, and most current approaches are not evaluated on jointly predicting multiple solution components with differing magnitudes and parameter sensitivities. To address these challenges, we propose a joint model consisting of a convolutional encoder, a transformer operating on latent representations, and a decoder for reconstruction. The main novelties are joint training with multi-stage parameter injection and coordinate channel injection. Parameters are injected at multiple stages to improve conditioning. Physical coordinates are encoded to provide spatial information. This allows the model to dynamically adapt its computations to the specific PDE parameters governing each system, rather than learning a single fixed response. Experiments on the Advection-Diffusion-Reaction equation and Navier-Stokes flow around the cylinder wake demonstrate that our approach combines the efficiency of latent evolution with the fidelity of full-field models, outperforming DL-ROMs, latent transformers, and plain ViTs in multi-field prediction, reducing the relative rollout error by approximately $5$ times.
### Title:
          Hyperfastrl: Hypernetwork-based reinforcement learning for unified control of parametric chaotic PDEs
 - **Authors:** Anil Sapkota, Omer San
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spatiotemporal chaos in fluid systems exhibits severe parametric sensitivity, rendering classical adjoint-based optimal control intractable because each operating regime requires recomputing the control law. We address this bottleneck with hyperFastRL, a parameter-conditioned reinforcement learning framework that leverages Hypernetworks to shift from tuning isolated controllers per-regime to learning a unified parametric control manifold. By mapping a physical forcing parameter {\mu} directly to the weights of a spatial feedback policy, the architecture cleanly decouples parametric adaptation from spatial boundary stabilization. To overcome the extreme variance inherent to chaotic reward landscapes, we deploy a pessimistic distributional value estimation over a massively parallel environment ensemble. We evaluate three Hypernetwork functional forms, ranging from residual MLPs to periodic Fourier and Kolmogorov-Arnold (KAN) representations, on the Kuramoto-Sivashinsky equation under varying spatial forcing. All forms achieve robust stabilization. KAN yields the most consistent energy-cascade suppression and tracking across unseen parametrizations, while Fourier networks exhibit worse extrapolation variability. Furthermore, leveraging high-throughput parallelization allows us to intentionally trade a fraction of peak asymptotic reward for a 37% reduction in training wall-clock time, identifying an optimal operating regime for practical deployment in complex, parameter-varying chaotic PDEs.
### Title:
          A Semi-Lagrangian Spherical Essentially Non-Oscillatory (SENO) Scheme for Advection Equations of S2-valued Functions
 - **Authors:** Shingyu Leung
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We develop a numerical scheme for solving the advection equation of $\mathbb{S}^2$-valued functions of real variables, which models the time-evolution of a $\mathbb{S}^2$-valued mapping on the real line by a known velocity field. The idea is to extend the semi-Lagrangian method for the linear scalar advection equation. We first construct the backward flow map between two adjacent time levels and then interpolate the discrete ordered data of $\mathbb{S}^2$. To handle $\mathbb{S}^2$-functions which have kinks or sharp discontinuity in their components, we incorporate the \textit{Spherical Essentially Non-Oscillatory} (SENO) interpolation method, which effectively reduces the spurious oscillations in high-order reconstructions. We will show multiple examples to demonstrate the accuracy and effectiveness of the proposed algorithm for the partial differential equation of $\mathbb{S}^2$-functions.
### Title:
          Rhythm-consistent semi-Markov simulation of tourist mobility rhythms with probabilistic event-to-POI assignment: Hakone, Japan
 - **Authors:** Jianhao Shi, Tomio Miwa, Wanglin Yan
 - **Subjects:** Subjects:
Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding the timing and sequencing of activity participation in tourist mobility is central to travel behavior research, yet GPS trajectories are noisy, irregularly sampled, and only weakly linked to activity locations, which limits interpretation and scenario analysis. We address this by mapping each stay event to candidate points of interest (POIs) probabilistically, using explicit prior-likelihood weighting that yields a normalized compatibility distribution rather than hard matching. Using one month of high-density tourist trajectories in Hakone, Japan (November 2021), we construct semantic stay-event sequences based on observed place-category labels (MID10) and describe mobility rhythms through hour-by-category profiles, category transitions, and expected dwell patterns. Building on these rhythm signatures, we develop a rhythm-consistent semi-Markov simulator that generates synthetic stay-event sequences with time-conditioned transitions and category-dependent dwell behavior. In the observed data, hour-by-category summaries are computed by probability-weighted aggregation over soft labels; in simulation, each event is generated with a discrete category and a sampled dwell duration, enabling like-for-like comparison after aggregation. We further conduct counterfactual POI-inventory scenarios to quantify how hypothetical POI configuration changes shift stay intensity across time, categories, and space, particularly around hubs and main corridors. Observed-simulated comparisons show close agreement in temporal profiles and category distributions, indicating that probabilistic labeling and rhythm-consistent simulation preserve key mobility structure while providing an interpretable basis for transport-geography scenario evaluation.
### Title:
          Bi-Lipschitz Autoencoder With Injectivity Guarantee
 - **Authors:** Qipeng Zhan, Zhuoping Zhou, Zexuan Wang, Qi Long, Li Shen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autoencoders are widely used for dimensionality reduction, based on the assumption that high-dimensional data lies on low-dimensional manifolds. Regularized autoencoders aim to preserve manifold geometry during dimensionality reduction, but existing approaches often suffer from non-injective mappings and overly rigid constraints that limit their effectiveness and robustness. In this work, we identify encoder non-injectivity as a core bottleneck that leads to poor convergence and distorted latent representations. To ensure robustness across data distributions, we formalize the concept of admissible regularization and provide sufficient conditions for its satisfaction. In this work, we propose the Bi-Lipschitz Autoencoder (BLAE), which introduces two key innovations: (1) an injective regularization scheme based on a separation criterion to eliminate pathological local minima, and (2) a bi-Lipschitz relaxation that preserves geometry and exhibits robustness to data distribution drift. Empirical results on diverse datasets show that BLAE consistently outperforms existing methods in preserving manifold structure while remaining resilient to sampling sparsity and distribution shifts. Code is available at this https URL.
### Title:
          ARuleCon: Agentic Security Rule Conversion
 - **Authors:** Ming Xu, Hongtai Wang, Yanpei Guo, Zhengmin Yu, Weili Han, Hoon Wei Lim, Jin Song Dong, Jiaheng Zhang
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Security Information and Event Management (SIEM) systems make it possible for detecting intrusion anomalies in real-time manner by their applied security rules. However, the heterogeneity of vendor-specific rules (e.g., Splunk SPL, Microsoft KQL, IBM AQL, Google YARA-L, and RSA ESA) makes cross-platform rule reuse extremely difficult, requiring deep domain knowledge for reliable conversion. As a result, an autonomous and accurate rule conversion framework can significantly lead to effort savings, preserving the value of existing rules. In this paper, we propose ARuleCon, an agentic SIEM-rule conversion approach. Using ARuleCon, the security professionals do not need to distill the source rules' logic, the documentation of the target rules and ARuleCon can purposely convert to the target vendors without more intervention. To achieve this, ARuleCon is equipped with conversion/schema mismatches, and Python-based consistency check that running both source and target rules in controlled test environments to mitigate subtle semantic drifts. We present a comprehensive evaluation of ARuleCon ranging from textual alignment and the execution success, showcasing ARuleCon can convert rules with high fidelity, outperforming the baseline LLM model by 15% averagely. Finally, we perform case studies and interview with our industry collaborators in Singtel Singapore, which showcases that ARuleCon can significantly save expert's time on understanding cross-SIEM's documentation and remapping logic.
### Title:
          VGGT-SLAM++
 - **Authors:** Avilasha Mandal, Rajesh Kumar, Sudarshan Sunil Harithas, Chetan Arora
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce VGGT-SLAM++, a complete visual SLAM system that leverages the geometry-rich outputs of the Visual Geometry Grounded Transformer (VGGT). The system comprises a visual odometry (front-end) fusing the VGGT feed-forward transformer and a Sim(3) solution, a Digital Elevation Map (DEM)-based graph construction module, and a back-end that jointly enable accurate large-scale mapping with bounded memory. While prior transformer-based SLAM pipelines such as VGGT-SLAM rely primarily on sparse loop closures or global Sim(3) manifold constraints - allowing short-horizon pose drift - VGGT-SLAM++ restores high-cadence local bundle adjustment (LBA) through a spatially corrective back-end. For each VGGT submap, we construct a dense planar-canonical DEM, partition it into patches, and compute their DINOv2 embeddings to integrate the submap into a covisibility graph. Spatial neighbors are retrieved using a Visual Place Recognition (VPR) module within the covisibility window, triggering frequent local optimization that stabilizes trajectories. Across standard SLAM benchmarks, VGGT-SLAM++ achieves state-of-the-art accuracy, substantially reducing short-term drift, accelerating graph convergence, and maintaining global consistency with compact DEM tiles and sublinear retrieval.
### Title:
          Personalization as a Game: Equilibrium-Guided Generative Modeling for Physician Behavior in Pharmaceutical Engagement
 - **Authors:** Suyash Mishra
 - **Subjects:** Subjects:
Computer Science and Game Theory (cs.GT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present \textbf{EGPF} (Equilibrium-Guided Personalization Framework), a mathematically rigorous architecture unifying Bayesian game theory, category theory, information theory, and generative AI for hyper-personalized physician engagement in the pharmaceutical domain. Our framework models the pharma--physician interaction as an incomplete-information Bayesian game where physician behavioral types are inferred via functorial mappings from observational categories, equilibrium strategies guide content generation through large language models (LLMs), and information-theoretic feedback loops ensure adaptive recalibration. We formalize behavior composition through category-theoretic functors, natural transformations, and monoidal structures, enabling modular, composable physician archetypes that respect structural invariants under domain shift. We introduce a novel \textit{Rate-Distortion Equilibrium} (RDE) criterion that bounds the personalization--privacy tradeoff, an \textit{Evolutionary Game Dynamics} layer for population-level behavior modeling, a \textit{Mechanism Design} module for incentive-compatible engagement, and a \textit{Sheaf-Theoretic} extension for multi-scale behavioral consistency. We prove convergence of our iterative belief-update mechanism at rate $O(\frac{K\log K}{t \cdot C_{\min}})$ and establish finite-sample regret bounds. Extensive experiments on synthetic pharma datasets and a real-world HCP engagement pilot demonstrate a 34\% improvement in engagement prediction (AUC) and 28\% lift in content relevance scores compared to state-of-the-art methods.
### Title:
          Is Cross-Lingual Transfer in Bilingual Models Human-Like? A Study with Overlapping Word Forms in Dutch and English
 - **Authors:** Iza Škrjanec, Irene Elisabeth Winther, Vera Demberg, Stefan L. Frank
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bilingual speakers show cross-lingual activation during reading, especially for words with shared surface form. Cognates (friends) typically lead to facilitation, whereas interlingual homographs (false friends) cause interference or no effect. We examine whether cross-lingual activation in bilingual language models mirrors these patterns. We train Dutch-English causal Transformers under four vocabulary-sharing conditions that manipulate whether (false) friends receive shared or language-specific embeddings. Using psycholinguistic stimuli from bilingual reading studies, we evaluate the models through surprisal and embedding similarity analyses. The models largely maintain language separation, and cross-lingual effects arise primarily when embeddings are shared. In these cases, both friends and false friends show facilitation relative to controls. Regression analyses reveal that these effects are mainly driven by frequency rather than consistency in form-meaning mapping. Only when just friends share embeddings are the qualitative patterns of bilinguals reproduced. Overall, bilingual language models capture some cross-linguistic activation effects. However, their alignment with human processing seems to critically depend on how lexical overlap is encoded, possibly limiting their explanatory adequacy as models of bilingual reading.
### Title:
          Leveraging Artist Catalogs for Cold-Start Music Recommendation
 - **Authors:** Yan-Martin Tamm, Gregor Meehan, Vojtěch Nekl, Vojtěch Vančura, Rodrigo Alves, Johan Pauwels, Anna Aljanaki
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The item cold-start problem poses a fundamental challenge for music recommendation: newly added tracks lack the interaction history that collaborative filtering (CF) requires. Existing approaches often address this problem by learning mappings from content features such as audio, text, and metadata to the CF latent space. However, previous works either omit artist information or treat it as just another input modality, missing the fundamental hierarchy of artists and items. Since most new tracks come from artists with previous history available, we frame cold-start track recommendation as 'semi-cold' by leveraging the rich collaborative signal that exists at the artist level. We show that artist-aware methods can more than double Recall and NDCG compared to content-only baselines, and propose ACARec, an attention-based architecture that generates CF embeddings for new tracks by attending over the artist's existing catalog. We show that our approach has notable advantages in predicting user preferences for new tracks, especially for new artist discovery and more accurate estimation of cold item popularity.
### Title:
          Multilingual Embedding Probes Fail to Generalize Across Learner Corpora
 - **Authors:** Laurits Lyngbaek, Ross Deans Kristensen-McLachlan
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Do multilingual embedding models encode a language-general representation of proficiency? We investigate this by training linear and non-linear probes on hidden-state activations from Qwen3-Embedding (0.6B, 4B, 8B) to predict CEFR proficiency levels from learner texts across nine corpora and seven languages. We compare five probing architectures against a baseline trained on surface-level text features. Under in-distribution evaluation, probes achieve strong performance ($QWK\approx0.7$), substantially outperforming the surface baseline, with middle layers consistently yielding the best predictions. However, in cross-corpus evaluation performance collapses across all probe types and model sizes. Residual analysis reveals that out-of-distribution probes converge towards predicting uniformly distributed labels, indicating that the learned mappings capture corpus-specific distributional properties (topic, language, task type, rating methodology) rather than an abstract, transferable proficiency dimension. These results suggest that current multilingual embeddings do not straightforwardly encode language-general proficiency, with implications for representation-based approaches to proficiency-adaptive language technology.
### Title:
          Assessing the Added Value of Onboard Earth Observation Processing with the IRIDE HEO Service Segment
 - **Authors:** Parampuneet Kaur Thind, Charles Mwangi, Giovanni Varetto, Lorenzo Sarti, Andrea Papa, Andrea Taramelli
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Hardware Architecture (cs.AR); Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current operational Earth Observation (EO) services, including the Copernicus Emergency Management Service (CEMS), the European Forest Fire Information System (EFFIS), and the Copernicus Land Monitoring Service (CLMS), rely primarily on ground-based processing pipelines. While these systems provide mature large-scale information products, they remain constrained by downlink latency, bandwidth limitations, and limited capability for autonomous observation prioritisation. The International Report for an Innovative Defence of Earth (IRIDE) programme is a national Earth observation initiative led by the Italian government to support public authorities through timely, objective information derived from spaceborne data. Rather than a single constellation, IRIDE is designed as a constellation of constellations, integrating heterogeneous sensing technologies within a unified service-oriented architecture. Within this framework, Hawk for Earth Observation (HEO) enables onboard generation of data products, allowing information extraction earlier in the processing chain. This paper examines the limitations of ground-only architectures and evaluates the added value of onboard processing at the operational service level. The IRIDE burnt-area mapping service is used as a representative case study to demonstrate how onboard intelligence can support higher spatial detail (sub-three-metre ground sampling distance), smaller detectable events (minimum mapping unit of three hectares), and improved system responsiveness. Rather than replacing existing Copernicus services, the IRIDE HEO capability is positioned as a complementary layer providing image-driven pre-classification to support downstream emergency and land-management workflows. This work highlights the operational value of onboard intelligence for emerging low-latency EO service architectures.
### Title:
          An RTK-SLAM Dataset for Absolute Accuracy Evaluation in GNSS-Degraded Environments
 - **Authors:** Wei Zhang, Vincent Ress, David Skuddis, Uwe Soergel, Norbert Haala
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 RTK-SLAM systems integrate simultaneous localization and mapping (SLAM) with real-time kinematic (RTK) GNSS positioning, promising both relative consistency and globally referenced coordinates for efficient georeferenced surveying. A critical and underappreciated issue is that the standard evaluation metric, Absolute Trajectory Error (ATE), first fits an optimal rigid-body transformation between the estimated trajectory and reference before computing errors. This so-called SE(3) alignment absorbs global drift and systematic errors, making trajectories appear more accurate than they are in practice, and is unsuitable for evaluating the global accuracy of RTK-SLAM. We present a geodetically referenced dataset and evaluation methodology that expose this gap. A key design principle is that the RTK receiver is used solely as a system input, while ground truth is established independently via a geodetic total station. This separation is absent from all existing datasets, where GNSS typically serves as (part of) the ground truth. The dataset is collected with a handheld RTK-SLAM device, comprising two scenes. We evaluate LiDAR-inertial, visual-inertial, and LiDAR-visual-inertial RTK-SLAM systems alongside standalone RTK, reporting direct global accuracy and SE(3)-aligned relative accuracy to make the gap explicit. Results show that SE(3) alignment can underestimate absolute positioning error by up to 76\%. RTK-SLAM achieves centimeter-level absolute accuracy in open-sky conditions and maintains decimeter-level global accuracy indoors, where standalone RTK degrades to tens of meters. The dataset, calibration files, and evaluation scripts are publicly available at this https URL.
### Title:
          TeaLeafVision: An Explainable and Robust Deep Learning Framework for Tea Leaf Disease Classification
 - **Authors:** Rafi Ahamed, Sidratul Moon Nafsin, Md Abir Rahman, Tasnia Tarannum Roza, Munaia Jannat Easha, Abu Raihan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As the worlds second most consumed beverage after water, tea is not just a cultural staple but a global economic force of profound scale and influence. More than a mere drink, it represents a quiet negotiation between nature, culture, and the human desire for a moment of reflection. So, the precise identification and detection of tea leaf disease is crucial. With this goal, we have evaluated several Convolutional Neural Networks (CNN) models, among them three shows noticeable performance including DenseNet201, MobileNetV2, InceptionV3 on the teaLeafBD dataset. teaLeafBD dataset contains seven classes, six disease classes and one healthy class, collected under various field conditions reflecting real world challenges. Among the CNN models, DenseNet201 has achieved the highest test accuracy of 99%. In order to enhance the model reliability and interpretability, we have implemented Gradient weighted Class Activation Mapping (Grad CAM), occlusion sensitivity analysis and adversarial training techniques to increase the noise resistance of the model. Finally, we have developed a prototype in order to leverage the models capabilities on real life agriculture. This paper illustrates the deep learning models capabilities to classify the disease in real life tea leaf disease detection and management.
### Title:
          Mem3R: Streaming 3D Reconstruction with Hybrid Memory via Test-Time Training
 - **Authors:** Changkun Liu, Jiezhi Yang, Zeman Li, Yuan Deng, Jiancong Guo, Luca Ballan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Streaming 3D perception is well suited to robotics and augmented reality, where long visual streams must be processed efficiently and consistently. Recent recurrent models offer a promising solution by maintaining fixed-size states and enabling linear-time inference, but they often suffer from drift accumulation and temporal forgetting over long sequences due to the limited capacity of compressed latent memories. We propose Mem3R, a streaming 3D reconstruction model with a hybrid memory design that decouples camera tracking from geometric mapping to improve temporal consistency over long sequences. For camera tracking, Mem3R employs an implicit fast-weight memory implemented as a lightweight Multi-Layer Perceptron updated via Test-Time Training. For geometric mapping, Mem3R maintains an explicit token-based fixed-size state. Compared with CUT3R, this design not only significantly improves long-sequence performance but also reduces the model size from 793M to 644M parameters. Mem3R supports existing improved plug-and-play state update strategies developed for CUT3R. Specifically, integrating it with TTT3R decreases Absolute Trajectory Error by up to 39% over the base implementation on 500 to 1000 frame sequences. The resulting improvements also extend to other downstream tasks, including video depth estimation and 3D reconstruction, while preserving constant GPU memory usage and comparable inference throughput. Project page: this https URL
### Title:
          Are Face Embeddings Compatible Across Deep Neural Network Models?
 - **Authors:** Fizza Rubab, Yiying Tong, Arun Ross
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated face recognition has made rapid strides over the past decade due to the unprecedented rise of deep neural network (DNN) models that can be trained for domain-specific tasks. At the same time, foundation models that are pretrained on broad vision or vision-language tasks have shown impressive generalization across diverse domains, including biometrics. This raises an important question: Do different DNN models--both domain-specific and foundation models--encode facial identity in similar ways, despite being trained on different datasets, loss functions, and architectures? In this regard, we directly analyze the geometric structure of embedding spaces imputed by different DNN models. Treating embeddings of face images as point clouds, we study whether simple affine transformations can align face representations of one model with another. Our findings reveal surprising cross-model compatibility: low-capacity linear mappings substantially improve cross-model face recognition over unaligned baselines for both face identification and verification tasks. Alignment patterns generalize across datasets and vary systematically across model families, indicating representational convergence in facial identity encoding. These findings have implications for model interoperability, ensemble design, and biometric template security.
### Title:
          Symbolic Polyhedral-Based Energy Analysis for Nested Loop Programs
 - **Authors:** Avinash Mahesh Nirmala, Dominik Walter, Frank Hannig, Jürgen Teich
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work presents a symbolic approach for estimating the energy consumption for nested loop programs when mapped and scheduled on parallel processor array accelerator architectures. Instead of simulation-based evaluation, we derive a methodology for symbolic energy analysis that captures the impact of mapping and scheduling decisions of loop nests on processor arrays. We compare our approach against simulation-based results for selected benchmarks and varying sizes of the iteration spaces. Whereas the latter are not scalable, our symbolic analysis is shown to be independent of the problem size. The presented evaluation methodology can be beneficially used during the design space exploration of mapping and scheduling decisions, for studying the influence of array size variations, and for comparisons with other loop nest accelerator architectures.
## Keyword: localization
### Title:
          Occlusion Handling by Pushing for Enhanced Fruit Detection
 - **Authors:** Ege Gursoy, Dana Kulić, Andrea Cherubini
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In agricultural robotics, effective observation and localization of fruits present challenges due to occlusions caused by other parts of the tree, such as branches and leaves. These occlusions can result in false fruit localization or impede the robot from picking the fruit. The objective of this work is to push away branches that block the fruit's view to increase their visibility. Our setup consists of an RGB-D camera and a robot arm. First, we detect the occluded fruit in the RGB image and estimate its occluded part via a deep learning generative model in the depth space. The direction to push to clear the occlusions is determined using classic image processing techniques. We then introduce a 3D extension of the 2D Hough transform to detect straight line segments in the point cloud. This extension helps detect tree branches and identify the one mainly responsible for the occlusion. Finally, we clear the occlusion by pushing the branch with the robot arm. Our method uses a combination of deep learning for fruit appearance estimation, classic image processing for push direction determination, and 3D Hough transform for branch detection. We validate our perception methods through real data under different lighting conditions and various types of fruits (i.e. apple, lemon, orange), achieving improved visibility and successful occlusion clearance. We demonstrate the practical application of our approach through a real robot branch pushing demonstration.
### Title:
          Evaluating Repository-level Software Documentation via Question Answering and Feature-Driven Development
 - **Authors:** Xinchen Wang, Ruida Hu, Cuiyun Gao, Pengfei Gao, Chao Peng
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Software documentation is crucial for repository comprehension. While Large Language Models (LLMs) advance documentation generation from code snippets to entire repositories, existing benchmarks have two key limitations: (1) they lack a holistic, repository-level assessment, and (2) they rely on unreliable evaluation strategies, such as LLM-as-a-judge, which suffers from vague criteria and limited repository-level knowledge. To address these issues, we introduce SWD-Bench, a novel benchmark for evaluating repository-level software documentation. Inspired by documentation-driven development, our strategy evaluates documentation quality by assessing an LLM's ability to understand and implement functionalities using the documentation, rather than by directly scoring it. This is measured through function-driven Question Answering (QA) tasks. SWD-Bench comprises three interconnected QA tasks: (1) Functionality Detection, to determine if a functionality is described; (2) Functionality Localization, to evaluate the accuracy of locating related files; and (3) Functionality Completion, to measure the comprehensiveness of implementation details. We construct the benchmark, containing 4,170 entries, by mining high-quality Pull Requests and enriching them with repository-level context. Experiments reveal limitations in current documentation generation methods and show that source code provides complementary value. Notably, documentation from the best-performing method improves the issue-solving rate of SWE-Agent by 20.00%, which demonstrates the practical value of high-quality documentation in supporting documentation-driven development.
### Title:
          Generate, Analyze, and Refine: Training-Free Sound Source Localization via MLLM Meta-Reasoning
 - **Authors:** Subin Park, Jung Uk Kim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sound source localization task aims to identify the locations of sound-emitting objects by leveraging correlations between audio and visual modalities. Most existing SSL methods rely on contrastive learning-based feature matching, but lack explicit reasoning and verification, limiting their effectiveness in complex acoustic scenes. Inspired by human meta-cognitive processes, we propose a training-free SSL framework that exploits the intrinsic reasoning capabilities of Multimodal Large Language Models (MLLMs). Our Generation-Analysis-Refinement (GAR) pipeline consists of three stages: Generation produces initial bounding boxes and audio classifications; Analysis quantifies Audio-Visual Consistency via open-set role tagging and anchor voting; and Refinement applies adaptive gating to prevent unnecessary adjustments. Extensive experiments on single-source and multi-source benchmarks demonstrate competitive performance. The source code is available at this https URL.
### Title:
          Vision-Language Model-Guided Deep Unrolling Enables Personalized, Fast MRI
 - **Authors:** Fangmao Ju, Yuzhu He, Zhiwen Xue, Chunfeng Lian, Jianhua Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Magnetic Resonance Imaging (MRI) is a cornerstone in medicine and healthcare but suffers from long acquisition times. Traditional accelerated MRI methods optimize for generic image quality, lacking adaptability for specific clinical tasks. To address this, we introduce PASS (Personalized, Anomaly-aware Sampling and reconStruction), an intelligent MRI framework that leverages a Vision-Language Model (VLM) to guide a deep unrolling network for task-oriented, fast imaging. PASS dynamically personalizes the imaging pipeline through three core contributions: (1) a deep unrolled reconstruction network derived from a physics-based MRI model; (2) a sampling module that generates patient-specific $k$-space trajectories; and (3) an anomaly-aware prior, extracted from a pretrained VLM, which steers both sampling and reconstruction toward clinically relevant regions. By integrating the high-level clinical reasoning of a VLM with an interpretable, physics-aware network, PASS achieves superior image quality across diverse anatomies, contrasts, anomalies, and acceleration factors. This enhancement directly translates to improvements in downstream diagnostic tasks, including fine-grained anomaly detection, localization, and diagnosis.
### Title:
          What's Missing in Screen-to-Action? Towards a UI-in-the-Loop Paradigm for Multimodal GUI Reasoning
 - **Authors:** Songze Li, Xiaoke Guo, Tianqi Liu, Biao Yi, Zhaoyan Gong, Zhiqiang Liu, Huajun Chen, Wen Zhang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing Graphical User Interface (GUI) reasoning tasks remain challenging, particularly in UI understanding. Current methods typically rely on direct screen-based decision-making, which lacks interpretability and overlooks a comprehensive understanding of UI elements, ultimately leading to task failure. To enhance the understanding and interaction with UIs, we propose an innovative GUI reasoning paradigm called UI-in-the-Loop (UILoop). Our approach treats the GUI reasoning task as a cyclic Screen-UI elements-Action process. By enabling Multimodal Large Language Models (MLLMs) to explicitly learn the localization, semantic functions, and practical usage of key UI elements, UILoop achieves precise element discovery and performs interpretable reasoning. Furthermore, we introduce a more challenging UI Comprehension task centered on UI elements with three evaluation metrics. Correspondingly, we contribute a benchmark of 26K samples (UI Comprehension-Bench) to comprehensively evaluate existing methods' mastery of UI elements. Extensive experiments demonstrate that UILoop achieves state-of-the-art UI understanding performance while yielding superior results in GUI reasoning tasks.
### Title:
          ModuSeg: Decoupling Object Discovery and Semantic Retrieval for Training-Free Weakly Supervised Segmentation
 - **Authors:** Qingze He, Fagui Liu, Dengke Zhang, Qingmao Wei, Quan Tang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Weakly supervised semantic segmentation aims to achieve pixel-level predictions using image-level labels. Existing methods typically entangle semantic recognition and object localization, which often leads models to focus exclusively on sparse discriminative regions. Although foundation models show immense potential, many approaches still follow the tightly coupled optimization paradigm, struggling to effectively alleviate pseudo-label noise and often relying on time-consuming multi-stage retraining or unstable end-to-end joint optimization. To address the above challenges, we present ModuSeg, a training-free weakly supervised semantic segmentation framework centered on explicitly decoupling object discovery and semantic assignment. Specifically, we integrate a general mask proposer to extract geometric proposals with reliable boundaries, while leveraging semantic foundation models to construct an offline feature bank, transforming segmentation into a non-parametric feature retrieval process. Furthermore, we propose semantic boundary purification and soft-masked feature aggregation strategies to effectively mitigate boundary ambiguity and quantization errors, thereby extracting high-quality category prototypes. Extensive experiments demonstrate that the proposed decoupled architecture better preserves fine boundaries without parameter fine-tuning and achieves highly competitive performance on standard benchmark datasets. Code is available at this https URL.
### Title:
          KITE: Keyframe-Indexed Tokenized Evidence for VLM-Based Robot Failure Analysis
 - **Authors:** Mehdi Hosseinzadeh, King Hang Wong, Feras Dayoub
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present KITE, a training-free, keyframe-anchored, layout-grounded front-end that converts long robot-execution videos into compact, interpretable tokenized evidence for vision-language models (VLMs). KITE distills each trajectory into a small set of motion-salient keyframes with open-vocabulary detections and pairs each keyframe with a schematic bird's-eye-view (BEV) representation that encodes relative object layout, axes, timestamps, and detection confidence. These visual cues are serialized with robot-profile and scene-context tokens into a unified prompt, allowing the same front-end to support failure detection, identification, localization, explanation, and correction with an off-the-shelf VLM. On the RoboFAC benchmark, KITE with Qwen2.5-VL substantially improves over vanilla Qwen2.5-VL in the training-free setting, with especially large gains on simulation failure detection, identification, and localization, while remaining competitive with a RoboFAC-tuned baseline. A small QLoRA fine-tune further improves explanation and correction quality. We also report qualitative results on real dual-arm robots, demonstrating the practical applicability of KITE as a structured and interpretable front-end for robot failure analysis. Code and models are released on our project page: this https URL
### Title:
          An RTK-SLAM Dataset for Absolute Accuracy Evaluation in GNSS-Degraded Environments
 - **Authors:** Wei Zhang, Vincent Ress, David Skuddis, Uwe Soergel, Norbert Haala
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 RTK-SLAM systems integrate simultaneous localization and mapping (SLAM) with real-time kinematic (RTK) GNSS positioning, promising both relative consistency and globally referenced coordinates for efficient georeferenced surveying. A critical and underappreciated issue is that the standard evaluation metric, Absolute Trajectory Error (ATE), first fits an optimal rigid-body transformation between the estimated trajectory and reference before computing errors. This so-called SE(3) alignment absorbs global drift and systematic errors, making trajectories appear more accurate than they are in practice, and is unsuitable for evaluating the global accuracy of RTK-SLAM. We present a geodetically referenced dataset and evaluation methodology that expose this gap. A key design principle is that the RTK receiver is used solely as a system input, while ground truth is established independently via a geodetic total station. This separation is absent from all existing datasets, where GNSS typically serves as (part of) the ground truth. The dataset is collected with a handheld RTK-SLAM device, comprising two scenes. We evaluate LiDAR-inertial, visual-inertial, and LiDAR-visual-inertial RTK-SLAM systems alongside standalone RTK, reporting direct global accuracy and SE(3)-aligned relative accuracy to make the gap explicit. Results show that SE(3) alignment can underestimate absolute positioning error by up to 76\%. RTK-SLAM achieves centimeter-level absolute accuracy in open-sky conditions and maintains decimeter-level global accuracy indoors, where standalone RTK degrades to tens of meters. The dataset, calibration files, and evaluation scripts are publicly available at this https URL.
## Keyword: transformer
### Title:
          A Benchmark of Classical and Deep Learning Models for Agricultural Commodity Price Forecasting on A Novel Bangladeshi Market Price Dataset
 - **Authors:** Tashreef Muhammad, Tahsin Ahmed, Meherun Farzana, Md. Mahmudul Hasan, Abrar Eyasir, Md. Emon Khan, Mahafuzul Islam Shawon, Ferdous Mondol, Mahmudul Hasan, Muhammad Ibrahim
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Econometrics (econ.EM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate short-term forecasting of agricultural commodity prices is critical for food security planning and smallholder income stabilisation in developing economies, yet machine-learning-ready datasets for this purpose remain scarce in South Asia. This paper makes two contributions. First, we introduce AgriPriceBD, a benchmark dataset of 1,779 daily retail mid-prices for five Bangladeshi commodities - garlic, chickpea, green chilli, cucumber, and sweet pumpkin - spanning July 2020 to June 2025, extracted from government reports via an LLM-assisted digitisation pipeline. Second, we evaluate seven forecasting approaches spanning classical models - naïve persistence, SARIMA, and Prophet - and deep learning architectures - BiLSTM, Transformer, Time2Vec-enhanced Transformer, and Informer - with Diebold-Mariano statistical significance tests. Commodity price forecastability is fundamentally heterogeneous: naïve persistence dominates on near-random-walk commodities. Time2Vec temporal encoding provides no statistically significant advantage over fixed sinusoidal encoding and causes catastrophic degradation on green chilli (+146.1% MAE, p<0.001). Prophet fails systematically, attributable to discrete step-function price dynamics incompatible with its smooth decomposition assumptions. Informer produces erratic predictions (variance up to 50x ground-truth), confirming sparse-attention Transformers require substantially larger training sets than small agricultural datasets provide. All code, models, and data are released publicly to support replication and future forecasting research on agricultural commodity markets in Bangladesh and similar developing economies.
### Title:
          Probabilistic Language Tries: A Unified Framework for Compression, Decision Policies, and Execution Reuse
 - **Authors:** Gregory Magarshak
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Data Structures and Algorithms (cs.DS); Information Retrieval (cs.IR); Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce probabilistic language tries (PLTs), a unified representation that makes explicit the prefix structure implicitly defined by any generative model over sequences. By assigning to each outgoing edge the conditional probability of the corresponding token or action, a PLT simultaneously serves as: (i) an optimal lossless compressor via frequency-weighted interval encoding, generalizing arithmetic coding to model-conditioned distributions; (ii) a policy representation for sequential decision problems including games, search, and robotic control; and (iii) a memoization index that lets repeated inference queries be answered by structured retrieval rather than full model execution. The central technical result is a prior-guided caching theorem: under a stationary generative distribution, a PLT-guided cache achieves strictly lower expected inference cost than any empirical-frequency cache for all query counts below a threshold that grows with the concentration of the prior. This converts O(n^2) transformer attention cost into an expected cost of p_r * O(log N) + (1 - p_r) * O(n^2), where p_r is the prior-estimated reuse probability and N is the artifact store size. We further introduce a hybrid compression architecture decomposing any dataset into a PLT-covered majority and a sparse residual store, connecting arithmetic coding with Kolmogorov-style program representations and rate-distortion theory. We instantiate the framework across chess, web search, robotics, organizational workflows, and LLM inference, demonstrating that compression, decision making, and computational reuse are all derived from a single probability measure on sequence space.
### Title:
          CraterBench-R: Instance-Level Crater Retrieval for Planetary Scale
 - **Authors:** Jichao Fang, Lei Zhang, Michael Phillips, Wei Luo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Impact craters are a cornerstone of planetary surface analysis. However, while most deep learning pipelines treat craters solely as a detection problem, critical scientific workflows such as catalog deduplication, cross-observation matching, and morphological analog discovery are inherently retrieval tasks. To address this, we formulate crater analysis as an instance-level image retrieval problem and introduce CraterBench-R, a curated benchmark featuring about 25,000 crater identities with multi-scale gallery views and manually verified queries spanning diverse scales and contexts. Our baseline evaluations across various architectures reveal that self-supervised Vision Transformers (ViTs), particularly those with in-domain pretraining, dominate the task, outperforming generic models with significantly more parameters. Furthermore, we demonstrate that retaining multiple ViT patch tokens for late-interaction matching dramatically improves accuracy over standard single-vector pooling. However, storing all tokens per image is operationally inefficient at a planetary scale. To close this efficiency gap, we propose instance-token aggregation, a scalable, training-free method that selects K seed tokens, assigns the remaining tokens to these seeds via cosine similarity, and aggregates each cluster into a single representative token. This approach yields substantial gains: at K=16, aggregation improves mAP by 17.9 points over raw token selection, and at K=64, it matches the accuracy of using all 196 tokens with significantly less storage. Finally, we demonstrate that a practical two-stage pipeline, with single-vector shortlisting followed by instance-token reranking, recovers 89-94% of the full late-interaction accuracy while searching only a small candidate set. The benchmark is publicly available at this http URL.
### Title:
          SE-Enhanced ViT and BiLSTM-Based Intrusion Detection for Secure IIoT and IoMT Environments
 - **Authors:** Afrah Gueriani, Hamza Kheddar, Ahmed Cherif Mazari, Seref Sagiroglu, Onur Ceran
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the rapid growth of interconnected devices in Industrial and Medical Internet of Things (IIoT and MIoT) ecosystems, ensuring timely and accurate detection of cyber threats has become a critical challenge. This study presents an advanced intrusion detection framework based on a hybrid Squeeze-and-Excitation Attention Vision Transformer-Bidirectional Long Short-Term Memory (SE ViT-BiLSTM) architecture. In this design, the traditional multi-head attention mechanism of the Vision Transformer is replaced with Squeeze-and-Excitation attention, and integrated with BiLSTM layers to enhance detection accuracy and computational efficiency. The proposed model was trained and evaluated on two real-world benchmark datasets; EdgeIIoT and CICIoMT2024; both before and after data balancing using the Synthetic Minority Over-sampling Technique (SMOTE) and RandomOverSampler. Experimental results demonstrate that the SE ViT-BiLSTM model outperforms existing approaches across multiple metrics. Before balancing, the model achieved accuracies of 99.11% (FPR: 0.0013%, latency: 0.00032 sec/inst) on EdgeIIoT and 96.10% (FPR: 0.0036%, latency: 0.00053 sec/inst) on CICIoMT2024. After balancing, performance further improved, reaching 99.33% accuracy with 0.00035 sec/inst latency on EdgeIIoT and 98.16% accuracy with 0.00014 sec/inst latency on CICIoMT2024.
### Title:
          Attribution-Driven Explainable Intrusion Detection with Encoder-Based Large Language Models
 - **Authors:** Umesh Biswas, Shafqat Hasan, Syed Mohammed Farhan, Nisha Pillai, Charan Gudla
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Software-Defined Networking (SDN) improves network flexibility but also increases the need for reliable and interpretable intrusion detection. Large Language Models (LLMs) have recently been explored for cybersecurity tasks due to their strong representation learning capabilities; however, their lack of transparency limits their practical adoption in security-critical environments. Understanding how LLMs make decisions is therefore essential. This paper presents an attribution-driven analysis of encoder-based LLMs for network intrusion detection using flow-level traffic features. Attribution analysis demonstrates that model decisions are driven by meaningful traffic behavior patterns, improving transparency and trust in transformer-based SDN intrusion detection. These patterns align with established intrusion detection principles, indicating that LLMs learn attack behavior from traffic dynamics. This work demonstrates the value of attribution methods for validating and trusting LLM-based security analysis.
### Title:
          Weakly Supervised Distillation of Hallucination Signals into Transformer Representations
 - **Authors:** Shoaib Sadiq Salehmohamed, Jinal Prashant Thakkar, Hansika Aredla, Shaik Mohammed Omar, Shalmali Ayachit
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing hallucination detection methods for large language models (LLMs) rely on external verification at inference time, requiring gold answers, retrieval systems, or auxiliary judge models. We ask whether this external supervision can instead be distilled into the model's own representations during training, enabling hallucination detection from internal activations alone at inference time. We introduce a weak supervision framework that combines three complementary grounding signals: substring matching, sentence embedding similarity, and an LLM as a judge verdict to label generated responses as grounded or hallucinated without human annotation. Using this framework, we construct a 15000-sample dataset from SQuAD v2 (10500 train/development samples and a separate 5000-sample test set), where each example pairs a LLaMA-2-7B generated answer with its full per-layer hidden states and structured hallucination labels. We then train five probing classifiers: ProbeMLP (M0), LayerWiseMLP (M1), CrossLayerTransformer (M2), HierarchicalTransformer (M3), and CrossLayerAttentionTransformerV2 (M4), directly on these hidden states, treating external grounding signals as training-time supervision only. Our central hypothesis is that hallucination detection signals can be distilled into transformer representations, enabling internal detection without any external verification at inference time. Results support this hypothesis. Transformer-based probes achieve the strongest discrimination, with M2 performing best on 5-fold average AUC/F1, and M3 performing best on both single-fold validation and held-out test evaluation. We also benchmark inference efficiency: probe latency ranges from 0.15 to 5.62 ms (batched) and 1.55 to 6.66 ms (single sample), while end-to-end generation plus probe throughput remains approximately 0.231 queries per second, indicating negligible practical overhead.
### Title:
          BiScale-GTR: Fragment-Aware Graph Transformers for Multi-Scale Molecular Representation Learning
 - **Authors:** Yi Yang, Ovidiu Daescu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Graph Transformers have recently attracted attention for molecular property prediction by combining the inductive biases of graph neural networks (GNNs) with the global receptive field of Transformers. However, many existing hybrid architectures remain GNN-dominated, causing the resulting representations to remain heavily shaped by local message passing. Moreover, most existing methods operate at only a single structural granularity, limiting their ability to capture molecular patterns that span multiple molecular scales. We introduce BiScale-GTR, a unified framework for self-supervised molecular representation learning that combines chemically grounded fragment tokenization with adaptive multi-scale reasoning. Our method improves graph Byte Pair Encoding (BPE) tokenization to produce consistent, chemically valid, and high-coverage fragment tokens, which are used as fragment-level inputs to a parallel GNN-Transformer architecture. Architecturally, atom-level representations learned by a GNN are pooled into fragment-level embeddings and fused with fragment token embeddings before Transformer reasoning, enabling the model to jointly capture local chemical environments, substructure-level motifs, and long-range molecular dependencies. Experiments on MoleculeNet, PharmaBench, and the Long Range Graph Benchmark (LRGB) demonstrate state-of-the-art performance across both classification and regression tasks. Attribution analysis further shows that BiScale-GTR highlights chemically meaningful functional motifs, providing interpretable links between molecular structure and predicted properties. Code will be released upon acceptance.
### Title:
          Team Fusion@ SU@ BC8 SympTEMIST track: transformer-based approach for symptom recognition and linking
 - **Authors:** Georgi Grazhdanski, Sylvia Vassileva, Ivan Koychev, Svetla Boytcheva
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a transformer-based approach to solving the SympTEMIST named entity recognition (NER) and entity linking (EL) tasks. For NER, we fine-tune a RoBERTa-based (1) token-level classifier with BiLSTM and CRF layers on an augmented train set. Entity linking is performed by generating candidates using the cross-lingual SapBERT XLMR-Large (2), and calculating cosine similarity against a knowledge base. The choice of knowledge base proves to have the highest impact on model accuracy.
### Title:
          The Depth Ceiling: On the Limits of Large Language Models in Discovering Latent Planning
 - **Authors:** Yi Xu, Philipp Jettkant, Laura Ruis
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The viability of chain-of-thought (CoT) monitoring hinges on models being unable to reason effectively in their latent representations. Yet little is known about the limits of such latent reasoning in LLMs. We test these limits by studying whether models can discover multi-step planning strategies without supervision on intermediate steps and execute them latently, within a single forward pass. Using graph path-finding tasks that precisely control the number of required latent planning steps, we uncover a striking limitation unresolved by massive scaling: tiny transformers trained from scratch discover strategies requiring up to three latent steps, fine-tuned GPT-4o and Qwen3-32B reach five, and GPT-5.4 attains seven under few-shot prompting. Although the maximum latent planning depth models can learn during training is five, the discovered strategy generalizes up to eight latent steps at test-time. This reveals a dissociation between the ability to discover a latent strategy under final-answer supervision alone and the ability to execute it once discovered. If similar limits hold more broadly, strategies requiring multiple coordinated latent planning steps may need to be explicitly taught or externalized, lending credence to CoT monitoring.
### Title:
          Visual prompting reimagined: The power of the Activation Prompts
 - **Authors:** Yihua Zhang, Hongkang Li, Yuguang Yao, Aochuan Chen, Shuai Zhang, Pin-Yu Chen, Meng Wang, Sijia Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual prompting (VP) has emerged as a popular method to repurpose pretrained vision models for adaptation to downstream tasks. Unlike conventional model fine-tuning techniques, VP introduces a universal perturbation directly into the input data to facilitate task-specific fine-tuning rather than modifying model parameters. However, there exists a noticeable performance gap between VP and conventional fine-tuning methods, highlighting an unexplored realm in theory and practice to understand and advance the input-level VP to reduce its current performance gap. Towards this end, we introduce a generalized concept, termed activation prompt (AP), which extends the scope of the input-level VP by enabling universal perturbations to be applied to activation maps within the intermediate layers of the model. By using AP to revisit the problem of VP and employing it as an analytical tool, we demonstrate the intrinsic limitations of VP in both performance and efficiency, revealing why input-level prompting may lack effectiveness compared to AP, which exhibits a model-dependent layer preference. We show that AP is closely related to normalization tuning in convolutional neural networks and vision transformers, although each model type has distinct layer preferences for prompting. We also theoretically elucidate the rationale behind such a preference by analyzing global features across layers. Through extensive experiments across 29 datasets and various model architectures, we provide a comprehensive performance analysis of AP, comparing it with VP and parameter-efficient fine-tuning baselines. Our results demonstrate AP's superiority in both accuracy and efficiency, considering factors such as time, parameters, memory usage, and throughput.
### Title:
          MICA: Multivariate Infini Compressive Attention for Time Series Forecasting
 - **Authors:** Willa Potosnak, Nina Żukowska, Michał Wiliński, Dan Howarth, Ignacy Stępka, Mononito Goswami, Artur Dubrawski
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multivariate forecasting with Transformers faces a core scalability challenge: modeling cross-channel dependencies via attention compounds attention's quadratic sequence complexity with quadratic channel scaling, making full cross-channel attention impractical for high-dimensional time series. We propose Multivariate Infini Compressive Attention (MICA), an architectural design to extend channel-independent Transformers to channel-dependent forecasting. By adapting efficient attention techniques from the sequence dimension to the channel dimension, MICA adds a cross-channel attention mechanism to channel-independent backbones that scales linearly with channel count and context length. We evaluate channel-independent Transformer architectures with and without MICA across multiple forecasting benchmarks. MICA reduces forecast error over its channel-independent counterparts by 5.4% on average and up to 25.4% on individual datasets, highlighting the importance of explicit cross-channel modeling. Moreover, models with MICA rank first among deep multivariate Transformer and MLP baselines. MICA models also scale more efficiently with respect to both channel count and context length than Transformer baselines that compute attention across both the temporal and channel dimensions, establishing compressive attention as a practical solution for scalable multivariate forecasting.
### Title:
          AE-ViT: Stable Long-Horizon Parametric Partial Differential Equations Modeling
 - **Authors:** Iva Mikuš, Boris Muha, Domagoj Vlah
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep Learning Reduced Order Models (ROMs) are becoming increasingly popular as surrogate models for parametric partial differential equations (PDEs) due to their ability to handle high-dimensional data, approximate highly nonlinear mappings, and utilize GPUs. Existing approaches typically learn evolution either on the full solution field, which requires capturing long-range spatial interactions at high computational cost, or on compressed latent representations obtained from autoencoders, which reduces the cost but often yields latent vectors that are difficult to evolve, since they primarily encode spatial information. Moreover, in parametric PDEs, the initial condition alone is not sufficient to determine the trajectory, and most current approaches are not evaluated on jointly predicting multiple solution components with differing magnitudes and parameter sensitivities. To address these challenges, we propose a joint model consisting of a convolutional encoder, a transformer operating on latent representations, and a decoder for reconstruction. The main novelties are joint training with multi-stage parameter injection and coordinate channel injection. Parameters are injected at multiple stages to improve conditioning. Physical coordinates are encoded to provide spatial information. This allows the model to dynamically adapt its computations to the specific PDE parameters governing each system, rather than learning a single fixed response. Experiments on the Advection-Diffusion-Reaction equation and Navier-Stokes flow around the cylinder wake demonstrate that our approach combines the efficiency of latent evolution with the fidelity of full-field models, outperforming DL-ROMs, latent transformers, and plain ViTs in multi-field prediction, reducing the relative rollout error by approximately $5$ times.
### Title:
          DesigNet: Learning to Draw Vector Graphics as Designers Do
 - **Authors:** Tomas Guija-Valiente, Iago Suárez
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI-driven content generation has made remarkable progress in recent years. However, neural networks and human designers operate in fundamentally different ways, making collaboration between them challenging. We address this gap for Scalable Vector Graphics (SVG) by equipping neural networks with tools commonly used by designers, such as axis alignment and explicit continuity control at command junctions. We introduce DesigNet, a hierarchical Transformer-VAE that operates directly on SVG sequences with a continuous command parameterization. Our main contributions are two differentiable modules: a continuity self-refinement module that predicts $C^0$, $G^1$, and $C^1$ continuity for each curve point and enforces it by modifying Bézier control points, and an alignment self-refinement module with snapping capabilities for horizontal or vertical lines. DesigNet produces editable outlines and achieves competitive results against state-of-the-art methods, with notably higher accuracy in continuity and alignment. These properties ensure the outputs are easier to refine and integrate into professional design workflows. Source Code: this https URL.
### Title:
          Transformer See, Transformer Do: Copying as an Intermediate Step in Learning Analogical Reasoning
 - **Authors:** Philipp Hellwig, Willem Zuidema, Claire E. Stevenson, Martha Lewis
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Analogical reasoning is a hallmark of human intelligence, enabling us to solve new problems by transferring knowledge from one situation to another. Yet, developing artificial intelligence systems capable of robust human-like analogical reasoning has proven difficult. In this work, we train transformers using Meta-Learning for Compositionality (MLC) on an analogical reasoning task (letter-string analogies) and assess their generalization capabilities. We find that letter-string analogies become learnable when guiding the models to attend to the most informative problem elements induced by including copying tasks in the training data. Furthermore, generalization to new alphabets becomes better when models are trained with more heterogeneous datasets, where our 3-layer encoder-decoder model outperforms most frontier models. The MLC approach also enables some generalization to compositions of trained transformations, but not to completely novel transformations. To understand how the model operates, we identify an algorithm that approximates the model's computations. We verify this using interpretability analyses and show that the model can be steered precisely according to expectations derived from the algorithm. Finally, we discuss implications of our findings for generalization capabilities of larger models and parallels to human analogical reasoning.
### Title:
          Efficient Quantization of Mixture-of-Experts with Theoretical Generalization Guarantees
 - **Authors:** Mohammed Nowaz Rabbani Chowdhury, Kaoutar El Maghraoui, Hsinyu Tsai, Naigang Wang, Geoffrey W. Burr, Liu Liu, Meng Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sparse Mixture-of-Experts (MoE) allows scaling of language and vision models efficiently by activating only a small subset of experts per input. While this reduces computation, the large number of parameters still incurs substantial memory overhead during inference. Post-training quantization has been explored to address this issue. Because uniform quantization suffers from significant accuracy loss at low bit-widths, mixed-precision methods have been recently explored; however, they often require substantial computation for bit-width allocation and overlook the varying sensitivity of model performance to the quantization of different experts. We propose a theoretically grounded expert-wise mixed precision strategy that assigns bit-width to each expert primarily based on their change in routers l2 norm during training. Experts with smaller changes are shown to capture less frequent but critical features, and model performance is more sensitive to the quantization of these experts, thus requiring higher precision. Furthermore, to avoid allocating experts to lower precision that inject high quantization noise, experts with large maximum intra-neuron variance are also allocated higher precision. Experiments on large-scale MoE models, including Switch Transformer and Mixtral, show that our method achieves higher accuracy than existing approaches, while also reducing inference cost and incurring only negligible overhead for bit-width assignment.
### Title:
          DAE Index Reduction for Electromagnetic Transient Models
 - **Authors:** Fiona Majeau, Jose Daniel Lara, Eduardo Corona, Bri-Mathias Hodge
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Electromagnetic transient (EMT) models are index-2 differential-algebraic equations when they include certain topologies and are formulated with modified nodal analysis. Such systems are difficult to numerically integrate, a challenge that is currently addressed by applying model approximations or reformulating with index-reduction algorithms. These algorithms exist in general-purpose software tools, but their reliance on symbolic representation makes them computationally prohibitive for large network-wide EMT models. This paper derives and presents two modular index-reduced subsystem models that allow EMT models to be integrated with standard solvers, without approximations or symbolic algorithms. Both subsystems include a transformer, one isolated and one machine-coupled. We measure the computational performance of constructing EMT models with up to 1152 buses using the custom subsystem models and the symbolic algorithms. The custom approach reduces memory usage and runtime of model construction by several orders of magnitude compared to the general approach, shifting the bottleneck from construction to integration.
### Title:
          WeatherRemover: All-in-one Adverse Weather Removal with Multi-scale Feature Map Compression
 - **Authors:** Weikai Qu, Sijun Liang, Cheng Pan, Zikuan Yang, Guanchi Zhou, Xianjun Fu, Bo Liu, Changmiao Wang, Ahmed Elazab
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Photographs taken in adverse weather conditions often suffer from blurriness, occlusion, and low brightness due to interference from rain, snow, and fog. These issues can significantly hinder the performance of subsequent computer vision tasks, making the removal of weather effects a crucial step in image enhancement. Existing methods primarily target specific weather conditions, with only a few capable of handling multiple weather scenarios. However, mainstream approaches often overlook performance considerations, resulting in large parameter sizes, long inference times, and high memory costs. In this study, we introduce the WeatherRemover model, designed to enhance the restoration of images affected by various weather conditions while balancing performance. Our model adopts a UNet-like structure with a gating mechanism and a multi-scale pyramid vision Transformer. It employs channel-wise attention derived from convolutional neural networks to optimize feature extraction, while linear spatial reduction helps curtail the computational demands of attention. The gating mechanisms, strategically placed within the feed-forward and downsampling phases, refine the processing of information by selectively addressing redundancy and mitigating its influence on learning. This approach facilitates the adaptive selection of essential data, ensuring superior restoration and maximizing efficiency. Additionally, our lightweight model achieves an optimal balance between restoration quality, parameter efficiency, computational overhead, and memory usage, distinguishing it from other multi-weather models, thereby meeting practical application demands effectively. The source code is available at this https URL.
### Title:
          LiveStre4m: Feed-Forward Live Streaming of Novel Views from Unposed Multi-View Video
 - **Authors:** Pedro Quesado, Erkut Akdag, Yasaman Kashefbahrami, Willem Menu, Egor Bondarev
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Live-streaming Novel View Synthesis (NVS) from unposed multi-view video remains an open challenge in a wide range of applications. Existing methods for dynamic scene representation typically require ground-truth camera parameters and involve lengthy optimizations ($\approx 2.67$s), which makes them unsuitable for live streaming scenarios. To address this issue, we propose a novel viewpoint video live-streaming method (LiveStre4m), a feed-forward model for real-time NVS from unposed sparse multi-view inputs. LiveStre4m introduces a multi-view vision transformer for keyframe 3D scene reconstruction coupled with a diffusion-transformer interpolation module that ensures temporal consistency and stable streaming. In addition, a Camera Pose Predictor module is proposed to efficiently estimate both poses and intrinsics directly from RGB images, removing the reliance on known camera calibration information. Our approach enables temporally consistent novel-view video streaming in real-time using as few as two synchronized unposed input streams. LiveStre4m attains an average reconstruction time of $ 0.07$s per-frame at $ 1024 \times 768$ resolution, outperforming the optimization-based dynamic scene representation methods by orders of magnitude in runtime. These results demonstrate that LiveStre4m makes real-time NVS streaming feasible in practical settings, marking a substantial step toward deployable live novel-view synthesis systems. Code available at: this https URL
### Title:
          Insights from Visual Cognition: Understanding Human Action Dynamics with Overall Glance and Refined Gaze Transformer
 - **Authors:** Bohao Xing, Deng Li, Rong Gao, Xin Liu, Heikki Kälviäinen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recently, Transformer has made significant progress in various vision tasks. To balance computation and efficiency in video tasks, recent works heavily rely on factorized or window-based self-attention. However, these approaches split spatiotemporal correlations between regions of interest in videos, limiting the models' ability to capture motion and long-range dependencies. In this paper, we argue that, similar to the human visual system, the importance of temporal and spatial information varies across different time scales, and attention is allocated sparsely over time through glance and gaze behavior. Is equal consideration of time and space crucial for success in video tasks? Motivated by this understanding, we propose a dual-path network called the Overall Glance and Refined Gaze (OG-ReG) Transformer. The Glance path extracts coarse-grained overall spatiotemporal information, while the Gaze path supplements the Glance path by providing local details. Our model achieves state-of-the-art results on the Kinetics-400, Something-Something v2, and Diving-48, demonstrating its competitive performance. The code will be available at this https URL.
### Title:
          VGGT-SLAM++
 - **Authors:** Avilasha Mandal, Rajesh Kumar, Sudarshan Sunil Harithas, Chetan Arora
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce VGGT-SLAM++, a complete visual SLAM system that leverages the geometry-rich outputs of the Visual Geometry Grounded Transformer (VGGT). The system comprises a visual odometry (front-end) fusing the VGGT feed-forward transformer and a Sim(3) solution, a Digital Elevation Map (DEM)-based graph construction module, and a back-end that jointly enable accurate large-scale mapping with bounded memory. While prior transformer-based SLAM pipelines such as VGGT-SLAM rely primarily on sparse loop closures or global Sim(3) manifold constraints - allowing short-horizon pose drift - VGGT-SLAM++ restores high-cadence local bundle adjustment (LBA) through a spatially corrective back-end. For each VGGT submap, we construct a dense planar-canonical DEM, partition it into patches, and compute their DINOv2 embeddings to integrate the submap into a covisibility graph. Spatial neighbors are retrieved using a Visual Place Recognition (VPR) module within the covisibility window, triggering frequent local optimization that stabilizes trajectories. Across standard SLAM benchmarks, VGGT-SLAM++ achieves state-of-the-art accuracy, substantially reducing short-term drift, accelerating graph convergence, and maintaining global consistency with compact DEM tiles and sublinear retrieval.
### Title:
          CloudMamba: An Uncertainty-Guided Dual-Scale Mamba Network for Cloud Detection in Remote Sensing Imagery
 - **Authors:** Jiajun Yang, Keyan Chen, Zhengxia Zou, Zhenwei Shi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cloud detection in remote sensing imagery is a fundamental, critical, and highly challenging problem. Existing deep learning-based cloud detection methods generally formulate it as a single-stage pixel-wise binary segmentation task with one forward pass. However, such single-stage approaches exhibit ambiguity and uncertainty in thin-cloud regions and struggle to accurately handle fragmented clouds and boundary details. In this paper, we propose a novel deep learning framework termed CloudMamba. To address the ambiguity in thin-cloud regions, we introduce an uncertainty-guided two-stage cloud detection strategy. An embedded uncertainty estimation module is proposed to automatically quantify the confidence of thin-cloud segmentation, and a second-stage refinement segmentation is introduced to improve the accuracy in low-confidence hard regions. To better handle fragmented clouds and fine-grained boundary details, we design a dual-scale Mamba network based on a CNN-Mamba hybrid architecture. Compared with Transformer-based models with quadratic computational complexity, the proposed method maintains linear computational complexity while effectively capturing both large-scale structural characteristics and small-scale boundary details of clouds, enabling accurate delineation of overall cloud morphology and precise boundary segmentation. Extensive experiments conducted on the GF1_WHU and Levir_CS public datasets demonstrate that the proposed method outperforms existing approaches across multiple segmentation accuracy metrics, while offering high efficiency and process transparency. Our code is available at this https URL.
### Title:
          TRAPTI: Time-Resolved Analysis for SRAM Banking and Power Gating Optimization in Embedded Transformer Inference
 - **Authors:** Jan Klhufek, Alberto Marchisio, Vojtech Mrazek, Lukas Sekanina, Muhammad Shafique
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer neural networks achieve state-of-the-art accuracy across language and vision tasks, but their deployment on embedded hardware is hindered by stringent area, latency, and energy constraints. During inference, performance and efficiency are increasingly dominated by the Key--Value (KV) cache, whose memory footprint grows with sequence length, straining on-chip memory utilization. Although existing mechanisms such as Grouped-Query Attention (GQA) reduce KV cache requirements compared to Multi-Head Attention (MHA), effectively exploiting this reduction requires understanding how on-chip memory demand evolves over time. This work presents TRAPTI, a two-stage methodology that combines cycle-level inference simulation with time-resolved analysis of on-chip memory occupancy to guide design decisions. In the first stage, the framework obtains memory occupancy traces and memory access statistics from simulation. In the second stage, the framework leverages the traces to explore banked memory organizations and power-gating configurations in an offline optimization flow. We apply this methodology to GPT-2 XL and DeepSeek-R1-Distill-Qwen-1.5B under the same accelerator configuration, enabling a direct comparison of MHA and GQA memory profiles. The analysis shows that DeepSeek-R1-Distill-Qwen-1.5B exhibits a 2.72x reduction in peak on-chip memory utilization in this setting compared to GPT-2 XL, unlocking further opportunities for power-gating optimization.
### Title:
          Is Cross-Lingual Transfer in Bilingual Models Human-Like? A Study with Overlapping Word Forms in Dutch and English
 - **Authors:** Iza Škrjanec, Irene Elisabeth Winther, Vera Demberg, Stefan L. Frank
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bilingual speakers show cross-lingual activation during reading, especially for words with shared surface form. Cognates (friends) typically lead to facilitation, whereas interlingual homographs (false friends) cause interference or no effect. We examine whether cross-lingual activation in bilingual language models mirrors these patterns. We train Dutch-English causal Transformers under four vocabulary-sharing conditions that manipulate whether (false) friends receive shared or language-specific embeddings. Using psycholinguistic stimuli from bilingual reading studies, we evaluate the models through surprisal and embedding similarity analyses. The models largely maintain language separation, and cross-lingual effects arise primarily when embeddings are shared. In these cases, both friends and false friends show facilitation relative to controls. Regression analyses reveal that these effects are mainly driven by frequency rather than consistency in form-meaning mapping. Only when just friends share embeddings are the qualitative patterns of bilinguals reproduced. Overall, bilingual language models capture some cross-linguistic activation effects. However, their alignment with human processing seems to critically depend on how lexical overlap is encoded, possibly limiting their explanatory adequacy as models of bilingual reading.
### Title:
          Controller Design for Structured State-space Models via Contraction Theory
 - **Authors:** Muhammad Zakwan, Vaibhav Gupta, Alireza Karimi, Efe C. Balta, Giancarlo Ferrari-Trecate
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Machine Learning (cs.LG); Dynamical Systems (math.DS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents an indirect data-driven output feedback controller synthesis for nonlinear systems, leveraging Structured State-space Models (SSMs) as surrogate models. SSMs have emerged as a compelling alternative in modelling time-series data and dynamical systems. They can capture long-term dependencies while maintaining linear computational complexity with respect to the sequence length, in comparison to the quadratic complexity of Transformer-based architectures. The contributions of this work are threefold. We provide the first analysis of controllability and observability of SSMs, which leads to scalable control design via Linear Matrix Inequalities (LMIs) that leverage contraction theory. Moreover, a separation principle for SSMs is established, enabling the independent design of observers and state-feedback controllers while preserving the exponential stability of the closed-loop system. The effectiveness of the proposed framework is demonstrated through a numerical example, showcasing nonlinear system identification and the synthesis of an output feedback controller.
### Title:
          Self-Discovered Intention-aware Transformer for Multi-modal Vehicle Trajectory Prediction
 - **Authors:** Diyi Liu, Zihan Niu, Tu Xu, Lishan Sun
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Predicting vehicle trajectories plays an important role in autonomous driving and ITS applications. Although multiple deep learning algorithms are devised to predict vehicle trajectories, their reliant on specific graph structure (e.g., Graph Neural Network) or explicit intention labeling limit their flexibilities. In this study, we propose a pure Transformer-based network with multiple modals considering their neighboring vehicles. Two separate tracks are employed. One track focuses on predicting the trajectories while the other focuses on predicting the likelihood of each intention considering neighboring vehicles. Study finds that the two track design can increase the performance by separating spatial module from the trajectory generating module. Also, we find the the model can learn an ordered group of trajectories by predicting residual offsets among K trajectories.
### Title:
          USCNet: Transformer-Based Multimodal Fusion with Segmentation Guidance for Urolithiasis Classification
 - **Authors:** Changmiao Wang, Songqi Zhang, Yongquan Zhang, Yifei Wang, Liya Liu, Nannan Li, Xingzhi Li, Jiexin Pan, Yi Jiang, Xiang Wan, Hai Wang, Ahmed Elazab
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Kidney stone disease ranks among the most prevalent conditions in urology, and understanding the composition of these stones is essential for creating personalized treatment plans and preventing recurrence. Current methods for analyzing kidney stones depend on postoperative specimens, which prevents rapid classification before surgery. To overcome this limitation, we introduce a new approach called the Urinary Stone Segmentation and Classification Network (USCNet). This innovative method allows for precise preoperative classification of kidney stones by integrating Computed Tomography (CT) images with clinical data from Electronic Health Records (EHR). USCNet employs a Transformer-based multimodal fusion framework with CT-EHR attention and segmentation-guided attention modules for accurate classification. Moreover, a dynamic loss function is introduced to effectively balance the dual objectives of segmentation and classification. Experiments on an in-house kidney stone dataset show that USCNet demonstrates outstanding performance across all evaluation metrics, with its classification efficacy significantly surpassing existing mainstream methods. This study presents a promising solution for the precise preoperative classification of kidney stones, offering substantial clinical benefits. The source code has been made publicly available: this https URL.
## Keyword: autonomous driving
### Title:
          Telescope: Learnable Hyperbolic Foveation for Ultra-Long-Range Object Detection
 - **Authors:** Parker Ewen, Dmitriy Rivkin, Mario Bijelic, Felix Heide
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous highway driving, especially for long-haul heavy trucks, requires detecting objects at long ranges beyond 500 meters to satisfy braking distance requirements at high speeds. At long distances, vehicles and other critical objects occupy only a few pixels in high-resolution images, causing state-of-the-art object detectors to fail. This challenge is compounded by the limited effective range of commercially available LiDAR sensors, which fall short of ultra-long range thresholds because of quadratic loss of resolution with distance, making image-based detection the most practically scalable solution given commercially available sensor constraints. We introduce Telescope, a two-stage detection model designed for ultra-long range autonomous driving. Alongside a powerful detection backbone, this model contains a novel re-sampling layer and image transformation to address the fundamental challenges of detecting small, distant objects. Telescope achieves $76\%$ relative improvement in mAP in ultra-long range detection compared to state-of-the-art methods (improving from an absolute mAP of 0.185 to 0.326 at distances beyond 250 meters), requires minimal computational overhead, and maintains strong performance across all detection ranges.
### Title:
          Evolution of Video Generative Foundations
 - **Authors:** Teng Hu, Jiangning Zhang, Hongrui Huang, Ran Yi, Zihan Su, Jieyu Weng, Zhucun Xue, Lizhuang Ma, Ming-Hsuan Yang, Dacheng Tao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid advancement of Artificial Intelligence Generated Content (AIGC) has revolutionized video generation, enabling systems ranging from proprietary pioneers like OpenAI's Sora, Google's Veo3, and Bytedance's Seedance to powerful open-source contenders like Wan and HunyuanVideo to synthesize temporally coherent and semantically rich videos. These advancements pave the way for building "world models" that simulate real-world dynamics, with applications spanning entertainment, education, and virtual reality. However, existing reviews on video generation often focus on narrow technical fields, e.g., Generative Adversarial Networks (GAN) and diffusion models, or specific tasks (e. g., video editing), lacking a comprehensive perspective on the field's evolution, especially regarding Auto-Regressive (AR) models and integration of multimodal information. To address these gaps, this survey firstly provides a systematic review of the development of video generation technology, tracing its evolution from early GANs to dominant diffusion models, and further to emerging AR-based and multimodal techniques. We conduct an in-depth analysis of the foundational principles, key advancements, and comparative strengths/limitations. Then, we explore emerging trends in multimodal video generation, emphasizing the integration of diverse data types to enhance contextual awareness. Finally, by bridging historical developments and contemporary innovations, this survey offers insights to guide future research in video generation and its applications, including virtual/augmented reality, personalized education, autonomous driving simulations, digital entertainment, and advanced world models, in this rapidly evolving field. For more details, please refer to the project at this https URL.
### Title:
          VDPP: Video Depth Post-Processing for Speed and Scalability
 - **Authors:** Daewon Yoon, Injun Baek, Sangyu Han, Yearim Kim, Nojun Kwak
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video depth estimation is essential for providing 3D scene structure in applications ranging from autonomous driving to mixed reality. Current end-to-end video depth models have established state-of-the-art performance. Although current end-to-end (E2E) models have achieved state-of-the-art performance, they function as tightly coupled systems that suffer from a significant adaptation lag whenever superior single-image depth estimators are released. To mitigate this issue, post-processing methods such as NVDS offer a modular plug-and-play alternative to incorporate any evolving image depth model without retraining. However, existing post-processing methods still struggle to match the efficiency and practicality of E2E systems due to limited speed, accuracy, and RGB reliance. In this work, we revitalize the role of post-processing by proposing VDPP (Video Depth Post-Processing), a framework that improves the speed and accuracy of post-processing methods for video depth estimation. By shifting the paradigm from computationally expensive scene reconstruction to targeted geometric refinement, VDPP operates purely on geometric refinements in low-resolution space. This design achieves exceptional speed (>43.5 FPS on NVIDIA Jetson Orin Nano) while matching the temporal coherence of E2E systems, with dense residual learning driving geometric representations rather than full reconstructions. Furthermore, our VDPP's RGB-free architecture ensures true scalability, enabling immediate integration with any evolving image depth model. Our results demonstrate that VDPP provides a superior balance of speed, accuracy, and memory efficiency, making it the most practical solution for real-time edge deployment. Our project page is at this https URL
### Title:
          How Well Do Vision-Language Models Understand Sequential Driving Scenes? A Sensitivity Study
 - **Authors:** Roberto Brusnicki, Mattia Piccinini, Johannes Betz
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language Models (VLMs) are increasingly proposed for autonomous driving tasks, yet their performance on sequential driving scenes remains poorly characterized, particularly regarding how input configurations affect their capabilities. We introduce VENUSS (VLM Evaluation oN Understanding Sequential Scenes), a framework for systematic sensitivity analysis of VLM performance on sequential driving scenes, establishing baselines for future research. Building upon existing datasets, VENUSS extracts temporal sequences from driving videos, and generates structured evaluations across custom categories. By comparing 25+ existing VLMs across 2,600+ scenarios, we reveal how even top models achieve only 57% accuracy, not matching human performance in similar constraints (65%) and exposing significant capability gaps. Our analysis shows that VLMs excel with static object detection but struggle with understanding the vehicle dynamics and temporal relations. VENUSS offers the first systematic sensitivity analysis of VLMs focused on how input image configurations - resolution, frame count, temporal intervals, spatial layouts, and presentation modes - affect performance on sequential driving scenes. Supplementary material available at this https URL
### Title:
          Fast-dVLM: Efficient Block-Diffusion VLM via Direct Conversion from Autoregressive VLM
 - **Authors:** Chengyue Wu, Shiyi Lan, Yonggan Fu, Sensen Gao, Jin Wang, Jincheng Yu, Jose M. Alvarez, Pavlo Molchanov, Ping Luo, Song Han, Ligeng Zhu, Enze Xie
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language models (VLMs) predominantly rely on autoregressive decoding, which generates tokens one at a time and fundamentally limits inference throughput. This limitation is especially acute in physical AI scenarios such as robotics and autonomous driving, where VLMs are deployed on edge devices at batch size one, making AR decoding memory-bandwidth-bound and leaving hardware parallelism underutilized. While block-wise discrete diffusion has shown promise for parallel text generation, extending it to VLMs remains challenging due to the need to jointly handle continuous visual representations and discrete text tokens while preserving pretrained multimodal capabilities. We present Fast-dVLM, a block-diffusion-based VLM that enables KV-cache-compatible parallel decoding and speculative block decoding for inference acceleration. We systematically compare two AR-to-diffusion conversion strategies: a two-stage approach that first adapts the LLM backbone with text-only diffusion fine-tuning before multimodal training, and a direct approach that converts the full AR VLM in one stage. Under comparable training budgets, direct conversion proves substantially more efficient by leveraging the already multimodally aligned VLM; we therefore adopt it as our recommended recipe. We introduce a suite of multimodal diffusion adaptations, block size annealing, causal context attention, auto-truncation masking, and vision efficient concatenation, that collectively enable effective block diffusion in the VLM setting. Extensive experiments across 11 multimodal benchmarks show Fast-dVLM matches its autoregressive counterpart in generation quality. With SGLang integration and FP8 quantization, Fast-dVLM achieves over 6x end-to-end inference speedup over the AR baseline.
### Title:
          Self-Discovered Intention-aware Transformer for Multi-modal Vehicle Trajectory Prediction
 - **Authors:** Diyi Liu, Zihan Niu, Tu Xu, Lishan Sun
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Predicting vehicle trajectories plays an important role in autonomous driving and ITS applications. Although multiple deep learning algorithms are devised to predict vehicle trajectories, their reliant on specific graph structure (e.g., Graph Neural Network) or explicit intention labeling limit their flexibilities. In this study, we propose a pure Transformer-based network with multiple modals considering their neighboring vehicles. Two separate tracks are employed. One track focuses on predicting the trajectories while the other focuses on predicting the likelihood of each intention considering neighboring vehicles. Study finds that the two track design can increase the performance by separating spatial module from the trajectory generating module. Also, we find the the model can learn an ordered group of trajectories by predicting residual offsets among K trajectories.
### Title:
          Geo-EVS: Geometry-Conditioned Extrapolative View Synthesis for Autonomous Driving
 - **Authors:** Yatong Lan, Rongkui Tang, Lei He
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Extrapolative novel view synthesis can reduce camera-rig dependency in autonomous driving by generating standardized virtual views from heterogeneous sensors. Existing methods degrade outside recorded trajectories because extrapolated poses provide weak geometric support and no dense target-view supervision. The key is to explicitly expose the model to out-of-trajectory condition defects during training. We propose Geo-EVS, a geometry-conditioned framework under sparse supervision. Geo-EVS has two components. Geometry-Aware Reprojection (GAR) uses fine-tuned VGGT to reconstruct colored point clouds and reproject them to observed and virtual target poses, producing geometric condition maps. This design unifies the reprojection path between training and inference. Artifact-Guided Latent Diffusion (AGLD) injects reprojection-derived artifact masks during training so the model learns to recover structure under missing support. For evaluation, we use a LiDAR-Projected Sparse-Reference (LPSR) protocol when dense extrapolated-view ground truth is unavailable. On Waymo, Geo-EVS improves sparse-view synthesis quality and geometric accuracy, especially in high-angle and low-coverage settings. It also improves downstream 3D detection.
