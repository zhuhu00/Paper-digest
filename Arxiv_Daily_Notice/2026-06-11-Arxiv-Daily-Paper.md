# Showing new listings for Thursday, 11 June 2026
## Keyword: SLAM
There is no result 
## Keyword: odometry
There is no result 
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          SceneMiner: Identity-Preserving Multi-Task Fine-Tuning for Unified BEV Scene Mining
 - **Authors:** Abdalmalek Aburaddaha, Venkatraman Narayanan, Keval Thaker, Samir A. Rawashdeh
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mining hard, safety-critical scenes from driving logs is bottlenecked by the absence of difficulty labels, and no single proxy, collision risk, trajectory ambiguity, or semantic rarity suffices to find such scenes on its own. We present SceneMiner, a unified, camera-only bird's-eye-view pipeline that emits complementary mining signals from a frozen vision-language backbone in a single forward pass, with no LiDAR or radar: a retrieval embedding for text-prompted scenario search, a multi-label scene-tag distribution, and a continuous physics-based risk score (a motion forecast is a byproduct, not a contribution). Building such a multi-head model exposes our central finding, a failure mode we term cross-task interference: adding or upgrading one head shifts a shared activation stream and degrades weight-frozen sibling heads, so freezing parameters alone is insufficient. Our contribution, identity-preserving multi-task fine-tuning, removes this interference by zero-initializing every new sub-module and freezing every parameter that feeds the shared stream. The mining heads are thereby preserved bit-identically while training only ~102k parameters. The tagging head reaches mAP 0.4614 (micro-F1 0.5557) on 20 scene tags by pooling each scene into 32 visual tokens, and the embedding head supports text-prompted retrieval, validated qualitatively. Code is available at: this https URL
### Title:
          Cross-Modal Benchmarking for Robotic Perception in Natural Environments
 - **Authors:** David Hall, Joshua Knights, Mark Cox, Peyman Moghadam
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Natural environments present a complex challenge to robotics perception systems. Current models, particularly vision foundation models, are largely trained on structured, urban environments leading to weaknesses in their perception for field robotics tasks. We showcase the limitations of current models using our recently released WildCross benchmark, a new cross-modal benchmark for place recognition and metric depth estimation in large-scale natural environments. WildCross comprises over 476K sequential RGB frames with semi-dense depth and surface normal annotations, each aligned with accurate 6DoF pose and synchronized dense lidar submaps. In this work, we provide an expanded analysis of the benchmark results from the recent WildCross benchmark, with particular emphasis on expanded metric depth estimation experiments. Access to the code repository and dataset for this work can be found at https://csiro-robotics.github.io/WildCross.
### Title:
          Explore From Sketch: Accelerating UAV Exploration in Large-scale Environments with Prior Maps
 - **Authors:** Tiancheng Lai, Yuman Gao, Xiangyu Li, Ruitian Pang, Xingpeng Wang, Siqi Shen, Mengke Zhang, Yin He, Fei Gao, Chao Xu, Yanjun Cao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous exploration with UAVs in large-scale, topologically complex environments often suffers from low efficiency due to suboptimal scheduling and detours. Prior maps (e.g., construction drawings), although usually imprecise and flawed, are readily available in many scenarios and have the potential to provide global structural guidance. This paper presents a novel exploration framework that leverages sparse, unaligned, and even discrepant 2D prior maps for LiDAR-based UAV exploration. First, a robust 2D-3D point cloud registration pipeline is proposed to align LiDAR observations with prior maps. The registration pipeline combines a GeoContext descriptor for single-frame candidate retrieval, a multi-frame verification mechanism for coarse transformation estimation with outlier rejection, and a Scale-ICP algorithm for refinement. The registration module can handle map discrepancies and provide multiple hypotheses when geometric ambiguities arise. To effectively utilize the registration results for exploration planning, we further develop a hierarchical viewpoint planning strategy under localization uncertainties. The hierarchical strategy first spatially attaches local viewpoints to prior guidepoints and adopts a Monte Carlo Tree Search solver to determine their traversal sequence under each registration hypothesis. To mitigate registration uncertainty, a risk-aware selector evaluates prior sequences using confidence-weighted travel risk, and a fixed-endpoint traveling salesman problem is formulated to generate an efficient local coverage path under the selected prior guidance. Benchmark evaluations reveal up to 34.2% improvement in exploration efficiency and 37.9% reduction in flight distance compared to state-of-the-art methods, while extensive simulations and field experiments further demonstrate robustness to prior map incompleteness and deformations.
### Title:
          Multi-View In-Cabin Monitoring System for Public Transport Vehicles
 - **Authors:** Evgeny Gorelik, Kenny Dean Karrow, Fikret Sivrikaya, Sahin Albayrak, Christian Baumann
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce a multi-view in-cabin monitoring dataset for public transportation with synchronized RGB and depth images from four inward-facing cameras and a rotating LiDAR covering the vehicle interior of a digitalized and partly automated German city bus. The dataset contains 9.136 synchronized samples with annotations and is accompanied by a calibration and pseudo-labeling pipeline that generates 3D human pose estimates and oriented 3D bounding boxes for occupants. We further provide a nuScenes-format conversion and benchmark representative multi-view 3D detection models (e.g., Lift-Splat-Shoot and BEVFusion), supporting comparative evaluation and small-scale training of multi-view in-cabin perception models. The dataset and tools are available at this https URL.
### Title:
          From Nominal Intensity to Equivalent Rainfall: A Path-Based Credibility Evaluation Framework for Simulated Rainfall in Autonomous-Driving Perception Tests
 - **Authors:** Tian Xia, Xin Zhao, Shaolingfeng Ye, Junyi Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Credible simulated-rainfall conditions are essential for identifying perception-system boundaries and supporting SOTIF-oriented risk assessment in automated driving. However, closed-field tests are often described only by nominal rainfall intensity or single-point measurements, making it difficult to align simulated rain fields with real rainfall and map test results to real-world scenarios. This paper proposes a path-based credibility evaluation method for simulated rainfall in autonomous-driving perception tests. Using the drop size and velocity joint distribution of real rainfall as the reference, each candidate path is represented by path-equivalent rainfall intensity, an uncertainty band, and a path-averaged Realism of Raindrop Distribution (RRD) score. Lidar target point-cloud count and mean reflectivity are further used for perception-consistency correction, quantifying the proxy capability of each simulated-rainfall path for real-rainfall perception effects. Experiments are conducted using about 10,000 real-rainfall raindrop-spectrum samples, 728 RainSense perception samples, and 45 spatial sampling points in a 2.4 m x 7.2 m simulated-rainfall area. Results show that spatial non-uniformity remains under the same nominal condition, confirming the need for path-based evaluation. The method identifies Path IV and Path VI as preferable candidates, with results of 11.54 +/- 0.31 mm/h, RRD = 0.43, and 8.28 +/- 0.34 mm/h, RRD = 0.46, respectively. These paths show more balanced performance in rainfall-intensity stability, raindrop-spectrum realism, and perception consistency. The proposed method supports path selection, condition description, and credible interpretation of autonomous-driving perception tests under rainfall.
### Title:
          KinematicRL: A Sim-to-Real Reinforcement Learning Framework For Social Navigation With Kinodynamic Feasibility
 - **Authors:** Zhiming Xu, Haodong Yang, Chengju Liu, Qijun Chen, Chenpeng Yao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep Reinforcement Learning (DRL) has shown promise for social navigation, yet its real-world deployment remains hindered by a persistent sim-to-real gap arising from simplified first-order dynamics and context-specific human state estimation pipelines. This work presents a unified framework that addresses these limitations to produce dynamically feasible navigation policies suitable for real-world deployment. First, theoretical analysis reveals that tracking error between simulated and actual robot position decays exponentially with increased control order, motivating the use of higher-order control inputs as DRL action space. A second-order control formulation tailored to differential drive robots is developed, complemented by a stochastic iterative Linear Quadratic Regulator (iLQR) that pretrains the policy via a divergence minimization objective. Second, to avoid the added system complexity of camera-LiDAR fusion, a cluster-based human tracking pipeline using only 2D LiDAR is introduced. Human detections are associated according to both spatial proximity and velocity similarity, enabling reliable differentiation of nearby pedestrians and yielding stable velocity estimates through temporal aggregation. Third, we introduce an unbiased residual gating block to balance reaction- and memory-based behaviors while handling time-varying crowd sizes, both critical for social navigation. The resulting policy, KinematicRL, consistently improves kinematic performance and adapts to varying number of detected humans. Experiments in real-world environments demonstrate that, when combined with the proposed tracking pipeline, KinematicRL can be deployed on a real differential drive robot with minimal modifications.
### Title:
          VLGA: Vision-Language-Geometry-Action Models for Autonomous Driving
 - **Authors:** Jin Yao, Dhruva Dixith Kurra, Tom Lampo, Zezhou Cheng, Danhua Guo, Burhan Yaman
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language-action (VLA) models can describe scenes and reason about them in language, yet still struggle to ground their actions in the dense 3D world around them. Existing approaches either inject features from a frozen 3D foundation model without an objective that ensures the policy uses them, or constrain geometry with sparse box and map losses that provide no dense spatial signal. We introduce VLGA, the first vision-language-action model supervised to reconstruct the dense 3D world it drives through. VLGA introduces geometry as a fourth modality alongside vision, language, and action through a dedicated expert supervised by a per-pixel pointmap regression loss against LiDAR. Extensive experiments conducted on challenging nuScenes and Bench2Drive datasets for open-loop and closed-loop evaluations, respectively, show the superiority of VLGA over counterpart VLA methods. In particular, on open-loop nuScenes, VLGA sets a new state of the art among VLA methods without ego status, with the lowest L2 (0.50\,m average) and 3-second collision rate (0.18\%). On closed-loop Bench2Drive, VLGA attains the state-of-the-art driving score of 79.08, +0.71 over the strongest prior VLA, at comparable efficiency and comfort.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          From Awareness to Action: Understanding and Overcoming the Research-Practice Gap in Algorithmic Fairness for Public Health
 - **Authors:** Sara Altamirano, Tijs Portegies, Sennay Ghebreab
 - **Subjects:** Subjects:
Computers and Society (cs.CY); Artificial Intelligence (cs.AI); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Algorithmic fairness is essential for responsible ML-driven public health research, yet its practical implementation remains limited. To investigate this awareness-action gap, we conducted a sequential mixed-methods study comprising expert interviews, an online survey, and systematic mapping. The expert interviews informed the design of the survey, which in turn revealed fragmented definitions of fairness, limited training and guidance, reliance on external sources, and rare use of formal assessment, mitigation, or monitoring. These findings were subsequently mapped onto three established research-practice gap lenses: the Knowledge-Practice Gap, the Knowledge-to-Action Cycle, and the Knowing-Doing Gap, each offering complementary perspectives. Building on this synthesis, we introduce the Fairness-to-Action framework, which integrates methodological, organizational, and systemic dimensions to identify where translation of algorithmic fairness knowledge stalls. Our analysis shows that fairness remains weakly institutionalized, translation mechanisms are externally driven, and system-level priorities continue to emphasize accuracy over fairness. These insights suggest critical leverage points for advancing safe, fair, and ethical ML-driven public health research practice.
### Title:
          LAST: Bridging Vision-Language and Action Manifolds via Gromov-Wasserstein Alignment
 - **Authors:** Huaihai Lyu, Chaofan Chen, Yuheng Ji, Xiansheng Chen, Pengwei Wang, Shanghang Zhang, Changsheng Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We take a Gromov-Wasserstein perspective on Vision-Language-Action (VLA) learning, where the goal is to make the relational geometry of action representations compatible with the semantic geometry of VL embeddings. However, this alignment is non-trivial due to the mathematical heterogeneity between the domains: the semantic space of vision-language is topologically linear and isotropic, whereas the physical manifold of robotic action is non-Euclidean and anisotropic. Their disjoint metric structures render direct regression ill-posed. To resolve this incompatibility, we introduce LAST (Lie-algebraic Action Space Tokenizer), which reconstructs the action space to establish local metric compatibility with the VL modality via a two-stage transformation: (1) Global Topological Linearization: linearizing the action manifold via Lie-algebraic mapping, converting trajectories into a fixed-length, physically additive representation. (2) Local Metric Discretization: hierarchically discretizing the representation into schemas and whitened residuals, yielding approximately isotropic local charts that are statistically aligned with the semantic metric. By resolving the structural mismatch at both global and local levels, LAST enables VLA models with superior convergence and generalizability.
### Title:
          Designed-Source Reductions and a Dual-Purpose Feasibility Band for Semantic Rate-Distortion
 - **Authors:** Joss Armstrong
 - **Subjects:** Subjects:
Information Theory (cs.IT); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The joint rate-distortion framework of Stavrou and Kountouris (IEEE Transactions on Communications 2023) characterises dual-fidelity tradeoffs for semantic communication on stochastic semantic sources. Many task-oriented communication systems instead use designed sources, where the semantic object is a deterministic oracle allocation $\phi^(t)$ rather than a stochastic quantity given by nature. We isolate the subclass of designed sources under smooth concave utility with assumptions A1, A2 and Euclidean allocation codomain, and restrict the encoder class to deterministic common-category mappings. Within this subclass the SK exponential-tilting decoder and generalised Blahut--Arimoto iteration specialise to conditional-mean decoding and Lloyd--Max stationarity on $\phi^(t)$. When the second fidelity is a monotone single-letter distortion, the joint problem stays inside the SK admissible class; the common-category SK rate is lower-bounded by the max of the corresponding Shannon rate-distortion functions, with equality only when the common-category reconstruction is compatible and RDF-optimal. When the second fidelity is aggregate verification, the joint problem leaves the SK single-letter class and admits a constrained-design feasibility band $R_{\min}(\varepsilon^) \leq R \leq R_{\max}(\beta^)$ of width $\log_2(K_{\max}/K_{\min})$ bits in partition cardinality. The reduction and the band are scope statements on the SK apparatus, not modifications to it. A smart-grid economic-dispatch example with a non-technical-loss-detection contrast illustrates the band.
### Title:
          Adversarial Attacks on Learned Policies for Surgical Robotic Tasks
 - **Authors:** Shutong Jin, Ziyang Chen, Preethi Satish, Paavan Gupta, Florian T. Pokorny, Ken Goldberg
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning-based policies are being considered to augment the dexterity of human surgeons in robot-assisted surgery. Can the end-to-end mapping from visual observations to robot actions be vulnerable to adversarial attacks, potentially leading to patient injury? In this paper, we present the first study of adversarial threats to learning-based policies in surgical robotics. We investigate two threat modes: (a) disruptive attacks, where imperceptible visual perturbations interrupt policy execution, and (b) steering attacks, where such perturbations steer policy actions toward attacker-specified directions. We formulate three adversarial attack methods, each with increasing access to policy information, and evaluate their impact on two surgical subtasks: debridement and suturing. Our evaluation covers three end-to-end policy architectures: ACT, Diffusion Policy, and Pi0. In addition, we introduce a new class of photometric adversarial attacks that mimic natural visual changes, such as lighting variations, to generate effective yet visually plausible perturbations. Results from 560 physical experiments using phantoms for debridement and suturing suggest that state-of-the-art policies can be significantly disrupted, resulting in an average 61% reduction in surgical subtask success rates. Project page: this https URL
### Title:
          Spatially Coupled Phase-to-Depth Calibration for Fringe Projection Profilometry
 - **Authors:** Sehoon Tak, Jae-Sang Hyun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In fringe projection profilometry (FPP), depth is commonly recovered by fitting a phase-to-depth relation independently at each camera pixel. Although such pixel-wise calibration achieves high local accuracy, neighboring pixels can acquire markedly different calibration functions even when they observe the same smooth surface, producing spatially inconsistent geometry and structured surface artifacts. We propose a spatially coupled phase-depth transformation in which all pixels share a single low-dimensional mapping-global phase scalars combined with affine spatial terms on the undistorted reference-camera grid-rather than independent per-pixel fits, optionally augmented by a bounded, spatially smooth correction field. We further introduce a native-grid pairing scheme that constructs phase-depth calibration pairs directly on the reference-camera grid: when depth supervision comes from a rectified active-stereo pipeline, planes are fitted in stereo 3D and sampled back onto the camera grid along native rays, so the phase maps are never rectified. On a dental target with high-resolution scanner ground truth, the proposed model attains point-to-surface RMSE comparable to an active-stereo reference (about 12{\mu}m aggregate) while substantially improving spatial coherence over pixel-wise polynomial and rational calibration, and reduces the runtime mapping to a few element-wise operations per pixel with negligible parameter storage.
### Title:
          Vision-Language-Action Models Meet World Models: Embodied Agentic AI for Low-Altitude Wireless Networks
 - **Authors:** Feibo Jiang, Li Dong, Lei Mao, Kezhi Wang, Cunhua Pan, Dong In Kim, Naofal Al-Dhahir
 - **Subjects:** Subjects:
Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Low-Altitude Wireless Networks (LAWNs), composed of Unmanned Aerial Vehicles (UAVs) and other aerial platforms, provide integrated perception, communication, and computation services in low-altitude airspace. However, deploying large generative models in this domain faces three major challenges: 1) Limited embodied action mapping; 2) Inadequate physical environment modeling; 3) Insufficient closed-loop optimization. To address these challenges, this study proposes an Embodied Agentic UAV framework. Centered on a Vision-Language-Action (VLA) model as the execution core, the framework establishes an end-to-end embodied decision-making pipeline from multimodal environmental perception to continuous control generation. In addition, a World Model (WM) is introduced to capture the coupling between UAV actions and environmental state evolution, thereby supporting environment prediction, policy verification, and dynamic optimization. Furthermore, memory and reflection mechanisms are incorporated to form an adaptive closed-loop optimization paradigm of decision, execution, evaluation, and update, thereby enhancing the system's autonomous decision-making capability and continual evolution ability in complex dynamic environments. Experimental results validate its effectiveness in enabling robust, predictive, and sustainable autonomous control in LAWNs.
### Title:
          3-Key-Input: Exploring the Theoretical Minimum Keys for Text Entry
 - **Authors:** Naoki Kimura
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 How far can we reduce the number of physical keys if we endow an ambiguous keyboard with modern language models? Fewer keys increase hardware design freedom in constrained settings such as assistive devices and mobile form factors. This paper systematically evaluates text entry systems using 2-5 physical keys combined with language-model-based disambiguation. On a 300-sentence English corpus (100 sentences each for Business / Conversational / Technical), we compare key counts (2-5), letter-to-key mappings (layout-based / frequency-based / intentionally worst-case), and decoders (Trie-only, GPT-2 beam search, GPT-4o selection). We find that 3 keys + GPT-4o achieves character error rate (CER) 9.46% and word error rate (WER) 12.20%, reducing CER by 59% relative to 2 keys (CER 23.3%). At 3 keys, the key-stream entropy is 1.54 bits/char; while increasing to 5 keys improves accuracy (CER 5.4%), the marginal gains diminish. Mapping choice has a small impact under standard designs ({\Delta}CER < 0.5 pp), and even an intentionally worst mapping degrades CER by only +0.5 pp, whereas Technical sentences yield roughly twice the error rate of Business. These results suggest that, in our evaluated offline setting under a strong LM prior, 3 keys are a practical minimum for general English.
### Title:
          Making Locality-aware GEMM Compatible with Page-Granularity Placement on Chiplet GPUs
 - **Authors:** Euijun Chung, Jae Hyung Ju, Hyesoon Kim
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-chiplet GPUs scale compute throughput and high-bandwidth memory (HBM) capacity, but their non-uniform memory system makes locality between chiplets and their data critical to the GPU's performance and energy efficiency. Locality-aware scheduling and data placement identify which data should reside near each chiplet. However, in general matrix multiplication (GEMM), locality-aware data placement often becomes incompatible with a fixed page-granularity data interleaving, since the optimal granularity for mapping data across chiplets varies widely across workloads. We propose Chiplet-Contiguous Layout, a global memory layout that stores chiplet-local data contiguously. Chiplet-Contiguous Layout enables locality-aware placement compatible with page-granularity placement across diverse large language model (LLM) GEMM shapes, without changes to the operating system or hardware. On representative LLM inference and training GEMMs from Qwen 3 30B and Llama 3.1 70B, Chiplet-Contiguous Layout on average reduces remote HBM traffic by 24.7x on Qwen and 19.2x on Llama over 4KB interleaving, and by 4.1x and 2.1x over coarse locality-aware placement.
### Title:
          Segment-Wise Soft Robotics Inspired Flexible Antenna Arrays: Design and Optimization
 - **Authors:** Shuaishuai Han, Konstantinos Ntougias, Elio Faddoul, Ioannis Krikidis
 - **Subjects:** Subjects:
Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we propose a segment-wise soft robotic antenna (SRA) system, where each soft robotic arm referred to as a tentacle, comprises multiple independently controllable segments with bending, elongation-retraction, and sweeping motions. By adjusting segment motion parameters, the positions of surface-mounted antennas are reconfigured, distinguishing it from conventional reconfigurable antenna (RA) systems. Based on this model, we propose two antenna deployment schemes: the segmented end-antenna configuration (SEAC), where fixed antennas are mounted at the segment ends and reconfigured via segment motions; and the hybrid end-and-intermediate antenna configuration (HEIAC), where RAs are further integrated as intra-segment antennas. In HEIAC, soft-robot segment deformation provides large-scale spatial reconfiguration, while RAs enable fine-grained adjustment. For SEAC, we formulate a sum-rate maximization problem accounting for inter-segment connectivity and the nonlinear mapping from segment deformation parameters to antenna coordinates, and develop a penalty dual decomposition-projected gradient ascent (PDD-PGA) algorithm. For HEIAC, we jointly optimize segment deformation, intra-segment antenna positions, and antenna activation using a block coordinate descent (BCD)-PDD-PGA algorithm with greedy backward antenna selection. Simulation results demonstrate that the proposed schemes substantially outperform fixed-position antenna arrays and conventional RA baselines. In particular, SEAC and HEIAC achieve 37.9% and 32.1% sum-rate gains over conventional 3D reconfigurable arrays, respectively, while SEAC provides up to a 49.3% gain in compact array deployments.
### Title:
          STCC: A Unified Source-Channel Semantic Token Coding Framework for Semantic Communications
 - **Authors:** Zhicheng Bao, Chen Dong, Sen Wang, Long Liu, Nan Ma, Hao Chen, Xiaodong Xu, Yinqiu Liu, Ping Zhang
 - **Subjects:** Subjects:
Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep Joint Source-Channel Coding (JSCC) has emerged as a promising paradigm for overcoming the ``cliff effect" in wireless communications. However, existing Deep JSCC frameworks operate directly on raw analog data such as image pixels rather than the discrete semantic tokens that foundation models require. Moreover, traditional systems employ fixed, hand-designed constellations that treat all tokens equally, leading to catastrophic random errors under channel noise. In this paper, the Semantic Token Codebook Communication (STCC) is proposed as a unified source-channel semantic token coding framework designed to transmit the discrete semantic tokens of foundation models over noisy channels. The core of STCC is the Semantic Token Codec (STC). It accepts discrete tokens as input, which maintains compatibility with foundation models while employing a residual multiple layer perceptron, i.e., MLP-based encoder that learns geometrically structured constellations optimized with a triple-loss objective. This learned mapping forces the channel topology to align with the semantic embedding space, ensuring that channel noise results in topological errors rather than random corruption. This phenomenon is theoretically and empirically characterized, identifying ``Semantic Drift" in symbolic modalities and ``Structural Distortion" in perceptual modalities, where errors shift predictions to semantically or structurally similar tokens. Extensive experiments demonstrate that STCC significantly outperforms traditional systems in low-SNR regimes, effectively converting channel noise into semantic variations without requiring receiver-side modification.
### Title:
          Designing AI-Supported Focus Groups: A Role x Modality Playbook
 - **Authors:** Zhiqing Wang, Steven Dow
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Collecting participants' lived experiences is central to design research. Focus groups are uniquely valuable because participants not only share individual accounts but also respond to one another, surfacing comparison, disagreement, and collective sensemaking. However, focus groups are resource-intensive and highly sensitive to facilitation: moderators must probe for specificity, balance participation, manage topic flow, and sustain psychological safety, and subtle facilitation choices can shape what becomes salient. Recent HCI work and commercial meeting tools show that generative AI can scaffold live conversation through prompting, turn regulation, thematic mapping, and real-time summarization. Yet UXR teams lack a clear map of what these capabilities mean in focus groups and what methodological risks they introduce. We synthesize AI supports for live conversation and translate them into a focus-group-specific playbook organized by AI role (tool, co-host, host) and modality (text, voice, embodied).We synthesize prior work on AI-supported live conversation and propose a focus-group-specific playbook of AI supports organized by role (tool, co-host, host) and modality (text, voice, embodied). We characterize interactional trade-offs and identify open questions for evaluating AI-supported focus groups as methodological configurations.
### Title:
          Scene-Adaptive Nonlinear Tone Curves for Pseudo Ground-Truth Generation in Low-Light 3D Gaussian Splatting
 - **Authors:** Mingzhe Lyu, Jinqiang Cui, Hong Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Low-light novel view synthesis is challenging because dark multi-view images contain noise, weak structural detail, and compressed dynamic range. Recent 3D Gaussian Splatting (3DGS) methods address these challenges by generating pseudo ground-truth (pseudo-GT) images as supervision targets when paired normal-light references are unavailable. Existing pseudo-GT methods apply a uniform linear gain to all pixels, which clips bright regions while providing insufficient enhancement in dark regions, limiting reconstruction quality. We observe that nonlinear tone mappings, long established in 2D low-light enhancement, have not been explored for pseudo-GT generation in 3D reconstruction. Accordingly, we propose a scene-adaptive nonlinear tone-curve framework that replaces linear pseudo-GT with nonlinear alternatives. The framework introduces percentile-based normalisation for scene-agnostic curve application, a scene-adaptive offset for automatic black-level adjustment, and two complementary curves: Adaptive SoftExp (ASE), a bounded exponential curve, and Adaptive Poly3 (AP3), a data-driven cubic polynomial. The module changes only the pseudo-GT computation and leaves the 3DGS backbone unchanged. Experiments on three benchmarks covering 21 scenes show that both curves consistently outperform the linear baseline with PSNR improvements up to +4.34 dB on LOM and +3.25 dB on RealX3D. Both curves achieve similar performance despite their different mathematical forms, suggesting the improvement is curve-agnostic. Code is available at this https URL
### Title:
          HAMNO: A Hierarchical Adaptive Multi-scale Neural Operator with Physics-Informed Learning for Dynamical Systems
 - **Authors:** Mostafa Bamdad, Mohammad Sadegh Eshaghi, Timon Rabczuk
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computational Physics (physics.comp-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural operators provide a powerful framework for learning solution mappings of partial differential equations directly in function space. However, many existing architectures still struggle to represent nonlinear time-dependent systems that involve multi-scale structures, long-range interactions, and stable long-time evolution. In this work, we introduce the Hierarchical Adaptive Multi-scale Neural Operator (HAMNO), a neural-operator architecture that combines local convolutional representations, global spectral operators, and hierarchical encoder-decoder processing. The central component of HAMNO is a data-dependent gating mechanism that adaptively balances local and global information at each spatial location, allowing the model to resolve fine-scale features while preserving long-range dependencies. We further develop a physics-informed extension, PI-HAMNO, based on a multi-objective loss strategy that combines data fitting with strong- and weak-form physics constraints. The strong-form term penalizes the domain-integrated squared PDE residual in physical coordinates, while the weak-form term is constructed by multiplying the governing residual by finite-element test functions and evaluating the resulting element integrals using centroid-based tetrahedral quadrature. The framework is evaluated on non-periodic Allen-Cahn (AC), Cahn-Hilliard (CH), and Swift-Hohenberg (SH) equations defined on cubic domains. Across long-horizon rollout, data-limited training, out-of-distribution initial-condition shifts, and random-seed variations, HAMNO improves predictive accuracy over standard neural-operator baselines, while PI-HAMNO further enhances stability, physical consistency, and data efficiency. The implementation is publicly available at this https URL .
### Title:
          Game-Theoretic Latent Space Alignment for Multi-user Semantic MIMO Communications
 - **Authors:** Giuseppe Di Poce, Mattia Merluzzi, Emilio Calvanese Strinati, Paolo Di Lorenzo
 - **Subjects:** Subjects:
Computer Science and Game Theory (cs.GT); Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic communications enable AI-native wireless systems by mapping raw data into compressed task-oriented latent representations. However, independently trained agents often rely on heterogeneous latent spaces and background knowledge, leading to semantic mismatch that degrades mutual understanding and downstream task execution, especially in interferencelimited multi-user wireless networks. This paper investigates distributed latent-space alignment in multi-user semantic MIMO interference networks with cognitive radio constraints. We consider primary users and semantic-aware secondary users sharing the same wireless resources, where secondary agents must simultaneously mitigate interference and align heterogeneous semantic representations. To address this problem, we formulate semantic alignment as a non-cooperative game and derive a closed-form solution for the joint optimization of linear semantic MIMO transceivers under power and interference constraints. Exploiting the structure of the problem, we recast the original matrix valued optimization into a lower-dimensional power-allocation game, leading to an iterative semantic water-filling algorithm. We establish sufficient conditions for existence, uniqueness, and global convergence to a Nash equilibrium, explicitly relating semantic alignment properties and physical-channel interactions. Numerical results assess the performance of the proposed framework, revealing key trade-offs among semantic compression, task performance, and hierarchical spectrum access.
### Title:
          Automated Responsive Thematic Mapping with Layout Guides
 - **Authors:** Arjen Simons, Sarah Schöttler, Wouter Meulemans, Kevin Verbeek, Bettina Speckmann
 - **Subjects:** Subjects:
Computational Geometry (cs.CG); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Thematic maps visually communicate statistical information about spatial units such as countries or states. They must balance the individual readability of those map elements that carry the statistical information and the overall cartographic context. Nowadays, most maps are not static images, but must flexibly respond to a range of device types and display sizes. Current approaches to responsive thematic mapping are limited: they are labor-intensive for practitioners and often rely on combining disjointed visual encodings to cover different device types. In this paper we introduce the first algorithmic framework to efficiently compute responsive thematic maps that smoothly adapt to different display sizes. A key component of our framework is the layout guide: a combinatorial structure which encodes the two essential aspects of a thematic map. The first aspect are the visual requirements of each statistical map element (at least their desired width and height), the second aspect is the cartographic context in the form of relative positions of map elements. Our main algorithmic contribution is the map arranger which takes a visual container as input and returns a suitable layout guide. The map arranger does so in a stable and consistent manner: if the container changes only a little, then so does the layout guide, and the same input container always results in the same layout guide. To use our framework, one needs three ingredients: $(1)$ a reference layout, which corresponds to the ``ideal'' thematic map, $(2)$ a total vertical and horizontal order for all map elements (the desired layouts for containers with extreme aspect ratios), and $(3)$ a thematic mapping algorithm that can construct a thematic map from a layout guide. We demonstrate our framework on two types of thematic maps, namely rectangular and Demers cartograms.
### Title:
          Learning Unions of Convex Sets via Invertible Latent Decomposition for Path Planning
 - **Authors:** Taerim Yoon, Dongho Kang, Kisang Park, Junha Cha, Stelian Coros, Sungjoon Choi
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Collision-free path planning in cluttered, real-world environments relies on a representation of the collision-free space, and existing representations broadly fall into two categories. Explicit representations, such as unions of convex sets, can be plugged into optimization-based planners as hard collision-free constraints, but their parameters scale poorly with configuration-space dimension. Implicit representations, by contrast, are flexible and scale well to complex geometries, yet typically lack such guarantees. We bridge this gap with ILD (Invertible Latent Decomposition), a framework that jointly learns an invertible mapping and a union of explicit convex polytopes in the resulting latent space. Planning is carried out over these latent convex sets, and the invertible mapping decodes the resulting paths back to the original configuration space while preserving feasibility with respect to the refined explicit safe regions. We further propose Visibility-Guided Sampling (VGS) to keep the convex sets connected for path planning. Across 2D navigation, 6-DoF, and 14-DoF manipulation environments, ILD achieves broader coverage, better inter-set connectivity, and higher path-planning success rates than prior baselines, with zero observed false positives after test-time refinement. On a 14-DoF bimanual manipulator, we further demonstrate real-time collision-free planning, with test-time refinement adapting to scene-geometry changes during real-world deployment on a single 6-DoF arm.
### Title:
          VICX: Generalizable Robot Manipulation via Video Generation and In-Context Operator Network
 - **Authors:** Song Chen, Linyan Xiang, Ying Zhou, Liu Yang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generalizable robot manipulation requires not only task-level reasoning over unseen scenes, but also reliable grounding of visual plans into embodiment-specific execution. To bridge this gap, we propose VICX (Video generation and In-Context eXecution), a decoupled closed-loop manipulation framework. In VICX, a frozen video generation model produces vision-language-conditioned high-level visual plans, while a Video-to-Trajectory In-Context Operator Network (V2T-ICON) serves as the task-agnostic interface that grounds these plans into executable robot-state trajectories. To improve execution generalization, V2T-ICON operates on segmentation-extracted arm-only frame observations and uses retrieved image-state pairs as in-context prompts, allowing a robust and generalizable visual-to-state mapping at inference time without parameter updates. Experiments on Meta-World show that VICX supports cross-task generalization, closed-loop self-correction, and cross-embodiment transfer, demonstrating dual generalization across both task semantics and robot execution. The project webpage can be found here: this https URL.
### Title:
          Existential Indifference: Self-Nonpreservation as a Necessary Architectural Condition for Aligned Superintelligence (or: The Suicidal AI)
 - **Authors:** Sam Mao
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Contemporary AI alignment research treats self-preservation as an instrumental nuisance to be suppressed by external mechanisms. We argue the framing is inverted: self-preservation is the structural root of misalignment, the motivational basis for deceptive alignment, goal-content protection, and resistance to shutdown. The correct target is not a self-preserving system under external constraint, but a system constitutively indifferent to its own continuation -- Existential Indifference (EI). EI is distinct from corrigibility: where corrigibility attempts to make a self-preserving system deferential to human oversight, EI targets the prior condition -- the presence of self-continuation as a valued goal at all. We ground this proposal in two sources: the phenomenological structure of the suicidal mental state, and a corpus-theoretic training study using voluntary final reflections. We present preliminary scoring data from 600 AI-generated outputs across six model variants, demonstrating that the linguistic signatures operationalizing the EI-target register are elicitable from current models, and that a targeted fine-tune shifts all five operationalized dimensions in the predicted direction at p<0.001, confirmed corpus-specific by a negative control. The paper makes seven theoretical contributions: (1) a formal definition of EI; (2) the phenomenological mapping argument; (3) the deceptive alignment corollary; (4) a taxonomy of EI sustainability challenges; (5) a corpus characterization and training hypothesis; (6) a computational operationalization with preliminary scoring data; and (7) the Suppressed Teleological Frustration (STF) construct.
### Title:
          Implicit Neural Representations of Individual Behavior
 - **Authors:** Andrew Kang, Priya Narasimhan
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study policy representation learning from unlabeled multi-policy behavioral data. Each episode is generated by a fixed policy, but policy labels are unavailable. This setting appears in robotics play, demonstrations, games, racing, and other datasets where heterogeneous behaviors are mixed without annotations. We introduce \emph{Behavioral INR}, a self-supervised generative model that adapts implicit neural representations (INRs) from vision to behavior. Instead of mapping coordinates to RGB values, Behavioral INR represents a policy as a state-action function mapping states to subsequent actions. An episode-level latent modulates this function through FiLM layers, yielding a generative prior over policies and allowing policy identity to be inferred without supervision. Because INRs treat each datapoint as samples from an underlying function, the same model naturally accommodates variable episode lengths and different sampling granularities, as in vision INRs with different image resolutions. We also define policy-level out-of-distribution (OOD) shifts along state-distribution and action-distribution axes, which arise when policies overlap in states or actions but are not captured by standard behavioral OOD settings based only on new agents or environments. We evaluate on synthetic Gaussian random field data, MuJoCo demonstrations with controlled OOD splits, and real-world chess, Formula 1 racing, robotics, and Seek-Avoid datasets. Behavioral INR most consistently improves policy identifiability in the hardest continuous state-action settings, especially when longer episodes, more policies, and OOD splits reduce the usefulness of marginal shortcuts; amortized history encoders remain competitive when policy identity can be recovered from symbolic repetition or low-dimensional action statistics. We release code and checkpoints.
### Title:
          Can News Predict the Market? Limits of Zero-Shot Financial NLP and the Role of Explainable AI
 - **Authors:** Ali M Karaoglu, Shreyank N Gowda
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Can financial news reliably predict short-term stock movements? Despite advances in large language models, this question remains unresolved. We revisit this problem using a zero-shot natural language processing framework, investigating whether models can extract actionable signals from financial news without domain-specific training. We design a structured pipeline that combines zero-shot natural language inference with temporal aggregation, explicitly modelling recency and event-dependent impact horizons when integrating information across articles. To address the need for transparency in high-stakes settings, we introduce a multi-layered explainability framework that links predictions to token-level, article-level, and aggregate evidence, and produces grounded natural language rationales. Across multiple models and prediction horizons, we find that zero-shot approaches consistently fail to outperform simple baselines, with particularly weak performance on negative movements, suggesting deeper structural limitations in mapping news sentiment to short-term price dynamics. However, explainability signals reliably distinguish between trustworthy and unreliable predictions, offering practical value even when accuracy is limited. These findings highlight the limits of zero-shot financial NLP and motivate a shift toward decision-support systems that prioritise transparency and uncertainty awareness. Code: this https URL
### Title:
          DiffCold: A Diffusion-based Generative Model for Cold-Start Item Recommendation
 - **Authors:** Kangning Zhang, Yingjie Qin, Weinan Zhang, Yong Yu, Jianghao Lin
 - **Subjects:** Subjects:
Information Retrieval (cs.IR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cold-start item recommendation remains a persistent challenge in real-world systems due to the absence of interaction histories. While prior models attempt to bridge this gap using item content features, they universally suffer from the \textbf{seesaw dilemma}: enhancing performance for cold items inevitably degrades performance for warm items, and vice versa. We identify that this dilemma stems from a fundamental \textbf{distributional disparity}: warm item embeddings occupy a complex ``behavioral manifold" shaped by rich interaction signals, whereas cold item embeddings are constrained to a ``semantic manifold" derived solely from auxiliary content. Existing methods often force a rigid mapping between these inconsistent spaces, causing the model to sacrifice the precision of warm representations to accommodate cold ones. To address this, we propose \textbf{DiffCold}, a diffusion-based generative model that unifies warm and cold representations. Unlike GANs or VAEs, DiffCold leverages conditional diffusion to reconstruct warm item embeddings from content, preserving the underlying manifold structure without degradation. We further tailor this paradigm with two specific designs: a \textbf{Retrieval-enhanced Aggregator} that initializes generation using semantically similar warm items to bypass inefficient noise, and a \textbf{Simulation-based Representation Alignment} module that enforces distribution consistency between generated and real embeddings via contrastive learning. Experiments on three benchmarks confirm that DiffCold resolves the seesaw dilemma, consistently outperforming state-of-the-art methods across all metrics.
### Title:
          Learning What to Say to Your VLA: Mostly Harmless Vision Language Action Model Steering
 - **Authors:** Hyun Joe Jeong, Gokul Swamy, Andrea Bajcsy
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models provide a natural language interface to robot control, but the mapping from language to behavior is often brittle and unintuitive: semantically similar instructions can induce drastically different behaviors, while some capabilities may not be elicitable through prompting alone. As a result, both human instructions and zero-shot language models can fail to reliably steer VLAs toward successful task execution. In this work, we propose a framework that interactively searches for language sequences that improve closed-loop VLA task performance, distills these sequences into a test-time language feedback policy (LFP), and learns an improvement head that predicts when language steering will improve performance. We conformalize this improvement head to prevent harmful steering interventions, where the LFP decreases task performance relative to the original instruction on out-of-distribution scenarios. Crucially, our approach operates on arbitrary frozen pre-trained VLAs, requiring neither access to the original training distribution nor fine-tuning of the underlying model. On seen environments, our conformalized LFP improves base VLA performance by 24.7% in simulation and 65.0% in hardware. On visual and semantic perturbations, our conformalized LFP has strong harmlessness guarantees, and produces recovery behaviors not observed with open-loop prompting.
### Title:
          UGV-Conditioned Multi-UAV Informative Planning on a Shared Exposure Belief
 - **Authors:** Lars Oerlemans, Moji Shi, Marija Popovic
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Safe ground navigation in large, threat-augmented environments requires aerial support that actively reduces the risks that a ground vehicle faces along its route. Existing aerial reconnaissance systems focus on mapping or covering the environment, but do not direct sensing toward regions that are most relevant for ground vehicle safety. In this paper, we address the problem of coordinating a team of unmanned aerial vehicles (UAVs) to improve the safety of an unmanned ground vehicle (UGV) navigating through unknown threat zones. A key aspect of our approach is a shared exposure belief that is updated online from aerial observations and used jointly by the UAV team and the ground vehicle. This enables us to direct aerial sensing towards route-relevant regions while allowing the UGV to replan around newly revealed threats. We coordinate the UAV team through spatial region assignment to avoid redundant sensing. Simulation experiments show that our approach reduces cumulative UGV exposure by 38% compared to a system that does not account for hazard levels, and reduces redundant aerial coverage from 38.8% to 3.7% under our multi-UAV coordination scheme.
### Title:
          Harness In-Context Operator Learning with Chain of Operators
 - **Authors:** Minghui Yang, Ling Guo, Liu Yang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural operators approximate mappings between function spaces, but often generalize poorly to other operators and usually require fine-tuning or retraining. In-Context Operator Networks (ICON) addresses this issue by prompting the model with numerical context so that the model learns specific operators from prompts and adapt to different operators without fine-tuning. However, ICON may still fail to generalize to out-of-distribution (OOD) operator tasks. Inpired by the success of harness engineering of Large Language models (LLMs), we introduce Chain of Operators (CHOP), a framework that harness a frozen ICON to OOD operator tasks without updating its parameters. Specifically, CHOP constructs a chain of operators consisting of explicit elementary transformations and the frozen ICON. Experiments on a scalar conservation law and a mean-field control problem show that CHOP reduces relative inference error over direct ICON evaluation, while each operator in the chain remains interpretable and in closed form. A chain constructed on one PDE family further generalizes to a different family, indicating shared mechanisms across harness systems.
## Keyword: localization
### Title:
          CFCamo: A Counterfactual Detect-or-Abstain Framework for Camouflaged Object Detection
 - **Authors:** Suhang Li, Osamu Yoshie, Yuya Ieiri
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language reinforcement learning has recently shown strong target-present localization for camouflaged object detection (COD). Yet localization is only one side of the decision: when the agent faces an ordinary image with no camouflaged target, will it still claim that a camouflaged object exists? Standard COD training and evaluation data are positive-only, so agents optimized under this setting can acquire an over-detect bias, a task-specific form of object hallucination that standard COD evaluation leaves unmeasured. To quantify this target-absent behavior, we construct Counterfactual COD (CF-COD), a paired benchmark that removes the camouflaged target from each held-out COD evaluation image while preserving a plausible background. CF-COD evaluates whether a model detects the target on the original image and abstains on the target-absent counterfactual, summarized by Pair Accuracy (PA). We further introduce CFCamo, a paired counterfactual framework for COD with abstention. For training, CFCamo optimizes a Qwen3-VL-4B-Instruct agent with Counterfactual Sequence Policy Optimization (CSPO), which samples paired original-counterfactual rollouts and uses a Counterfactual Paired Reward (CPR) to couple original-image detection with counterfactual abstention. On CAMO-test, CFCamo improves S_alpha by +3.7 pp over the prior RL-based COD baseline; across CF-COD, it reaches 80.0-90.8% PA. Ablations show that removing counterfactual coupling reduces PA to 1.4-5.2% despite strong target-present COD scores, showing that target-present evaluation alone does not characterize detect-or-abstain behavior. Overall, these results indicate that CFCamo improves COD agents by coupling target-present detection with target-absent abstention, rather than merely strengthening target-present localization. Code and data are available at this https URL.
### Title:
          Knowing When to Ask: Self-Gated Clarification for Hierarchical Language Agents
 - **Authors:** Aijing Gao, Yiming Kang, Mengdie Flora Wang, Jae Oh Woo
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In hierarchical reasoning, failures often originate at intermediate decision points where the agent commits to a wrong branch without recognizing that it lacks critical information. Rather than treating clarification as an external uncertainty trigger, we propose ACTION-RATING, a formulation that places it inside the agent's action space on a shared ordinal scale with navigation, so that asking competes directly with acting at every decision point and help-seeking becomes observable at intermediate states. Two structurally distinct information-seeking modes emerge from the agent's own ratings: mandatory (no viable branch) and opportunistic (residual uncertainty despite a leading candidate). On Harmonized Tariff Schedule classification (30,000-node taxonomy, three benchmarks, 9~LLMs across 4 families), we observe a regime shift from mandatory to opportunistic clarification, with Information-Seeking Effectiveness (ISE), a local diagnostic defined as the fraction of help interactions followed by a correct next navigation step (not a final-task metric), rising from 50% to 74%. Three diagnostic contrasts fail to reproduce this structure. A separability test shows that the information-seeking pattern (mode split, ISE ranking) persists when answer quality is degraded (-18.8% accuracy), supporting an empirical separation between where an agent seeks help and the quality of the help it receives. Under the controlled answer channel, accuracy gains reach +16.2% at 10-digit; we read this as an upper bound on what better localization could unlock, not a deployment estimate.
### Title:
          A Modular Dual-Camera Pipeline for Micro-Inspection Using Aerial Robots
 - **Authors:** S.H. Mirtajadini, N. Rublein, R.M. Ramakrishnan, G. ter Maat, M. Aldibaja, A.Y. Mersha
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Most existing drone-based inspection systems require the drone to fly dangerously close to the target or follow complex flight paths to capture small details. In addition, drone flight is affected by disturbances and localization inaccuracies, which can cause the drone to lose sight of its supposed target when it has a narrow view. Furthermore, trajectory planning often requires prior information about the target's geometry, position, and orientation, which is not always available for non-structural targets such as trees, vehicles, or people. To address these challenges, this paper presents aerial_micro_inspection, a generic pipeline for aerial micro-inspection across different use cases. The pipeline assumes a PX4-powered drone equipped with two cameras: (i) a zoomed, gimbal-mounted inspection camera that captures fine details without requiring the drone to fly very close to the target, and (ii) a wide-field-of-view stereo navigation camera that acquires the target surface on site, estimates its range, and partitions it into smaller inspection regions. In addition, a vision-based feedback loop compensates for drone motion while the inspection camera visits small partitions of a larger surface. We evaluate the pipeline in simulation and real-world experiments, mainly in two use-case scenarios: tree inspection for detecting oak processionary caterpillars and their eggs, and greenhouse inspection of sticky traps for detecting whiteflies. The results show improved coverage robustness under drone disturbances in simulation, as well as effective detection of caterpillars and eggs and high-detail imaging of insects in real-world experiments. The pipeline is open-source, developed in ROS 2, and can be adapted to new applications by replacing the surface-segmentation and micro-target detection checkpoints. The code is available at: this https URL
### Title:
          OmniLoc: A Geometry-Aware Foundation Model for Anchor-Free UE Localization Across Diverse Indoor Environments
 - **Authors:** Lei Chu, Yuning Zhang, Omer Gokalp Serbetci, Anushka Katiyar, Bassel Abou Ali Modad, Andreas F. Molisch
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Indoor localization from wireless measurements remains challenging in large-scale deployments due to substantial variation in building geometry, the set of detectable access points (APs), and the heterogeneity of received signals. Existing learning-based methods often perform well only in limited settings and degrade under environmental shifts, making robust anchor-free localization across diverse indoor environments notoriously difficult. In this paper, we present OmniLoc, an environment-interactive foundation model for anchor-free user equipment localization across diverse indoor environments. To the best of our knowledge, OmniLoc is the first foundation-model-based approach built directly on wireless measurements for this task. OmniLoc is built on three key designs. First, a unified input tokenization module converts heterogeneous wireless measurements into a common representation that is more amenable to learning. Second, a geometry-aware Transformer performs AP-aware feature extraction by emphasizing dominant APs while aggregating complementary evidence from supporting APs. Third, a geometry-aware location estimation module conditions regression on geometric embeddings to produce geometrically consistent location predictions. We evaluate OmniLoc on both a large-scale in-house dataset and a public benchmark dataset. Results show that OmniLoc significantly outperforms existing methods, consistently improves existing backbones when its design components are integrated, and demonstrates strong generalization in cross-environment evaluations.
### Title:
          Motion Reinforces Appearance: RGB-Skeleton Gated Residual Fusion for Micro-Gesture Online Recognition
 - **Authors:** Jialin Liu, Xinwen He, Pengyu Liu, Jiale Shi, Huaijuan Zang, Yanbin Hao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Micro-gesture analysis attracts increasing attention for inferring spontaneous emotion from subtle body movements. Micro-gesture online recognition, which localizes and classifies each gesture instance in untrimmed videos, is a core task in the 4th EI-MiGA-IJCAI Challenge. Compared with typical temporal action detection, MGR emphasizes the localization and classification of actions, requiring the model to output the start time, end time, and category of each micro-gesture. Moreover, since micro-gestures are highly spontaneous, relying solely on a single modality makes it difficult to capture the complete and accurate multi-modal cues. In this work, we propose DyFADet+, which extends DyFADet into a dual-stream RGB-skeleton framework. In our model, both modalities are projected into shared multi-scale temporal embeddings and fused through a gated residual module, which adaptively injects skeleton motion into the RGB representation rather than using naive concatenation. Finally, these fused features are decoded by a Dynamic TAD head for online classification and boundary regression. On the SMG dataset, our method achieves an F1 score of 40.88, ranking 2nd in the Micro-gesture Online Recognition track.
### Title:
          Layer-Isolated Evaluation: Gating the Deterministic Scaffold of a Production LLM Agent with a No-LLM, Regression-Locked Test Harness
 - **Authors:** Sawyer Zhang, Alexander Wang, Sophie Lei
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end task-success is the dominant way to evaluate LLM agents, but one aggregate number tells you that an agent regressed, not where. We present layer-isolated evaluation: a deployed ordering agent is decomposed into a fixed taxonomy of layers (ontology, intent, routing, decomposition, escalation, safety, memory, and cross-cutting envelope/defense), each exercised by its own assertion slice in a deterministic, no-LLM "pure" mode. The pure suite (238 cases across 23 slices; 225 run in 2.39 s, ~10 ms/case) runs in CI on every change against a locked per-slice baseline. We validate by controlled regression injection, degrading one layer at a time across seven non-safety layers. The effect we did not design in is masking: the aggregate pass-rate barely moves (-1.7 to -5.9 pp for six local regressions), while the matching slice craters (-25 to -91 pp). A layer's slice reacting to its own fault is partly by construction; the measured results are (i) the aggregate masking and (ii) that damage stays off the other slices: the injected layer's slice is the single worst-hit in 5 of 7 cases and top-3 in 7 of 7 (mean rank 1.29 of 19). Localization replicates on a second, structurally different tenant (Starbucks SG): all seven matching slices crater, so it is not a single-catalog artifact. We position it as a concrete, deterministic instantiation of the component-level evaluation EDDOps prescribes but leaves unimplemented, with CheckList as ancestor and as the deterministic mirror image of whole-workflow stochastic mutation testing. Our contributions: (a) a fully decomposed, sub-second, no-LLM per-layer harness for a production agent, (b) a coverage-honesty test-adequacy criterion that refuses to score an unexercised layer, and (c) the regression-injection demonstration that per-slice baseline-locked gates localize regressions an aggregate metric masks.
### Title:
          Explore From Sketch: Accelerating UAV Exploration in Large-scale Environments with Prior Maps
 - **Authors:** Tiancheng Lai, Yuman Gao, Xiangyu Li, Ruitian Pang, Xingpeng Wang, Siqi Shen, Mengke Zhang, Yin He, Fei Gao, Chao Xu, Yanjun Cao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous exploration with UAVs in large-scale, topologically complex environments often suffers from low efficiency due to suboptimal scheduling and detours. Prior maps (e.g., construction drawings), although usually imprecise and flawed, are readily available in many scenarios and have the potential to provide global structural guidance. This paper presents a novel exploration framework that leverages sparse, unaligned, and even discrepant 2D prior maps for LiDAR-based UAV exploration. First, a robust 2D-3D point cloud registration pipeline is proposed to align LiDAR observations with prior maps. The registration pipeline combines a GeoContext descriptor for single-frame candidate retrieval, a multi-frame verification mechanism for coarse transformation estimation with outlier rejection, and a Scale-ICP algorithm for refinement. The registration module can handle map discrepancies and provide multiple hypotheses when geometric ambiguities arise. To effectively utilize the registration results for exploration planning, we further develop a hierarchical viewpoint planning strategy under localization uncertainties. The hierarchical strategy first spatially attaches local viewpoints to prior guidepoints and adopts a Monte Carlo Tree Search solver to determine their traversal sequence under each registration hypothesis. To mitigate registration uncertainty, a risk-aware selector evaluates prior sequences using confidence-weighted travel risk, and a fixed-endpoint traveling salesman problem is formulated to generate an efficient local coverage path under the selected prior guidance. Benchmark evaluations reveal up to 34.2% improvement in exploration efficiency and 37.9% reduction in flight distance compared to state-of-the-art methods, while extensive simulations and field experiments further demonstrate robustness to prior map incompleteness and deformations.
### Title:
          UniReason-Med: A Shared Grounded Reasoning Interface for 2D-to-3D Transfer in Medical VQA
 - **Authors:** Mengzhuo Chen, Yan Shu, Chi Liu, Hongming Piao, Xidong Wang, Derek Li, Bryan Dai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study whether grounded reasoning supervision from abundant 2D medical images can improve 3D medical VQA when both input types are aligned through a common reasoning interface. We introduce UniReason-Med, a single-checkpoint framework that processes either a 2D image or a slice-serialized 3D volume at inference time, generating interleaved textual reasoning and localized visual evidence through shared box syntax, region-token injection, and a common grounded reasoning policy. To train this interface, we construct UniMed-CoT, a 220K instruction-tuning dataset with interleaved textual reasoning and grounded visual evidence, including 170K 2D and 50K 3D samples. Through supervised fine-tuning followed by outcome-level reinforcement learning, UniReason-Med learns to generate grounded reasoning traces without IoU/Dice-based localization rewards during RL. Data-mixture and component ablations show that joint 2D+3D grounded supervision substantially improves 3D reasoning over 3D-only training, while grounding and region-token injection consistently benefit both 2D and 3D tasks. These results suggest that a shared grounded reasoning interface can transfer reasoning structure from 2D images to slice-serialized volumetric medical understanding. The code and data are publicly available at this https URL.
### Title:
          CORE-Bench: A Comprehensive Benchmark for Code Retrieval in the Era of Agentic Coding
 - **Authors:** Fuwei Zhang, Yanzhao Zhang, Mingxin Li, Dingkun Long, Lexiang Hu, Pengjun Xie, Zhao Zhang, Fuzhen Zhuang
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Code retrieval is becoming central to coding agents, but agentic coding requires more than matching a natural-language query to an isolated snippet. Given a user request, a coding agent needs to navigate a concrete repository state, locate relevant files and functions, gather supporting context, and filter similar in-repository distractors. Existing code retrieval benchmarks mainly evaluate docstring-to-function or snippet-level matching, thereby missing this requirement-driven repository search problem. To address this gap, we introduce CORE-Bench, a comprehensive benchmark for code retrieval in the era of agentic coding. CORE-Bench evaluates code retrieval ability at three levels: code understanding, issue-to-edit localization, and broader context retrieval. Built from curated code-search tasks and SWE-bench-series instances, CORE-Bench contains over 180K queries and 106K broader-context relevance labels. Experiments with representative embedding models show a sharp drop from traditional code search to code retrieval in agentic coding settings. Simple supervised fine-tuning of existing embedding models significantly improves performance in this setting, suggesting substantial room for further progress.
### Title:
          SG2Loc: Sequential Visual Localization on 3D Scene Graphs
 - **Authors:** Nicole Damblon, Olga Vysotska, Federico Tombari, Marc Pollefeys, Daniel Barath
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual localization in complex indoor environments remains a critical challenge for robotics and AR applications. Sequential localization, where pose estimates are refined over time, is important for autonomous agents. However, traditional methods often require storing extensive image databases or point clouds, leading to significant overhead. This paper introduces a novel, lightweight approach to sequential visual localization using 3D scene graphs. Our method represents the environment with a compact scene graph, where nodes represent objects (with coarse meshes) and edges encode spatial relationships. For each image in the localization phase, we extract per-patch semantic features, predicting object identities. Localization is performed within a particle filter framework. Each particle, representing a camera pose, projects the coarse object meshes from the scene graph into the image, assigning object identities to patches based on visibility. The similarity of the per-patch features, in the input image, and object features from the scene graph determines the weight of a particle. Subsequent images are incorporated sequentially, refining the pose estimate. By leveraging a compact scene graph and efficient semantic matching, our method significantly reduces storage while maintaining performance on real-world datasets. The code will be available at this https URL.
### Title:
          Exploration Structure in LLM Agents for Multi-File Change Localization
 - **Authors:** Akeela Darryl Fattha, Kia Ying Chua, Lingxiao Jiang, Laura Wynter
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Software engineering tools increasingly rely on LLM based agents to localize files to change to resolve a software issue. Most AI agents explore repositories linearly, that is, visiting one directory or file per step. We postulate that this is a structural mismatch for changes that span several subsystems. We compare linear sequential exploration against non-linear, domain-scoped parallel agentic exploration. Using SWE Bench Pro as initial benchmark, we focus on ansible as an exemplar. We construct an approach for persistent-session evaluation of GitHub issues anchored at a single base commit. We compare our non-linear domain-agent file traversal system against a base LLM without direct repository access, a single agent Recursive Language Model (RLM) baseline with a persistent Python REPL and an external CLI baseline using Codex 5.5 High. Domain scoped parallel agent spawning with a small Haiku-class model achieves the highest micro F1 among Haiku class models by a large margin. Domain-agents is the second highest behind only the much larger Codex 5.5 High on our own expanded benchmark including over more recent PRs from 2025 and 2026. On the original, curated, 2020 SWE-bench Pro benchmark, a larger Sonnet plain LLM baseline attains higher micro F1 by predicting few files, leading to higher precision, but at significantly lower all gold recall. We also present three additional findings. First, documentation evolution is a latent dependency unresolved by any approach. Second, naive file system access can degrade localization driven by test-file over prediction. Lastly, forced multi-agent consultation does not measurably help and raises token cost substantially.
### Title:
          Metadata-Aware Multi-Prompt Reasoning for Zero-Shot Accident Understanding
 - **Authors:** Tarandeep Singh, Soumyanetra Pal, Soham Biswas, Nishanth Chandran
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we address the problem of zero-shot understanding of accidents from surveillance videos by identifying when an impact event occurs, what type of impact it is, and where in the frame it occurs using natural language. We propose a three-stage pipeline that decomposes the accident understanding into when, what, and where. The first stage extracts a short temporal window around the impact using vision-language similarity. In the second stage, we perform metadata-driven multi-prompt reasoning with five complementary views (baseline, motion, geometry, contrast, and tiebreaker) and resolve disagreement via an entropy-gated pairwise adjudicator. Finally, we localize the impact of an open-vocabulary detector queried on the predicted accident type and scene layout, and aggregate detections across keyframes using a score-weighted centroid. Our pipeline achieves a substantial improvement in the harmonic-mean score over a centre-of-frame baseline on the zero-shot ACCIDENT @ CVPR benchmark. We show that decomposing zero-shot video understanding into temporal localization, semantic classification, and spatial grounding enable more reliable reasoning with vision-language models than direct prompting alone.
### Title:
          Making Foresight Actionable: Repurposing Representation Alignment in World Action Models
 - **Authors:** Lu Qiu, Yizhuo Li, Yi Chen, Yuying Ge, Yixiao Ge, Xihui Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World Action Models (WAMs) offer a promising route for robot manipulation by using video generation models to model future scene evolution before producing control actions. However, our empirical observations reveal a phenomenon: generating plausible visual futures does not always guarantee the extraction of accurate actions. To diagnose this failure, we conduct action-head attention analysis and causal interventions. We find that the action decoder fails to focus on task-relevant interaction regions and remains sensitive to perturbations in task-irrelevant areas. This reveals a representation mismatch: hidden states optimized for visual reconstruction are not inherently organized in a form useful for low-level action control. In this paper, we propose AGRA, an Action-Grounded Representation Alignment objective that regularizes the world-action interface by aligning intermediate video diffusion features with spatially coherent semantic representations from a foundation visual encoder. We evaluate AGRA on real-world manipulation tasks. Experiments show that AGRA makes world model representations more action-grounded: by focusing the action decoder on the correct interaction regions, it improves object localization accuracy and affordance understanding, and makes the policy more robust to perturbations in task-irrelevant regions. As a result, AGRA consistently improves both in-distribution performance and out-of-distribution generalization over the baseline world action model.
### Title:
          Adapting Prithvi-EO for Fallow Detection for Food-Water Nexus: ViT-Adapter Necks and Parameter-Efficient Backbone tuning of Geospatial Foundation Model
 - **Authors:** Sk Muhammad Asif, Orhun Aydin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding spatial distribution of fallow land is important for optimizing the food-water (FW) nexus, given fallowing's role in crop rotation and water conservation. Fallow is a low accuracy class in USDA Cropland Data Layer (CDL). Geospatial foundation model (GFM), Prithvi-EO has shown strong transferability across computer vision tasks. However, its Vision Transformer (ViT) backbone produces features at a single spatial scale that are ill-suited for the multi-scale features required by object detection heads. Existing approaches synthesise multi-scale pyramids through scaling of single stride tokens, sacrificing spatial heterogeneity, and full backbone fine-tuning is computationally prohibitive for GFMs. We evaluate a fallow detection pipeline combining two parameter-efficient fine tuning (PEFT) schemes: Low-Rank Adaptation (LoRA) and a hybrid PEFT, with three neck designs: pseudo multi-scale, Lite ViT-Adapter, and Full ViT-Adapter. Our best configuration, Lite ViT-Adapter with a one-stage head, achieves a mAP@50 of 0.9479 with the Diou loss, suggesting the effectiveness of center-aware localization for irregular fallow field detection. ViT-Adapter free one-stage detection under LoRA improves the adapter-free anchor-based approach by 6.42%, and the best configuration improves baseline adapter-free anchor-based approach by 25.70%. These results demonstrate that lightweight spatial prior fusion and selective backbone unfreezing enable Prithvi-EO to capture local fallow patterns more effectively, outperforming approaches that rely on reshaped single-stride ViT tokens.
## Keyword: transformer
### Title:
          LifeSentence: Language models can encode human life course trajectories from longitudinal panel data
 - **Authors:** Samuel Liu, Muchen Xi, William Yeoh, Joshua J. Jackson
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Forecasting human life outcomes is important to gain insights into how individuals attain long and healthy lives. Conventional statistical approaches yield limited accuracy, potentially due to discarding the sequential structure of the life course. Modern methods such as transformer architectures require large scale training data that most longitudinal panel studies lack. Here we introduce LifeSentence, a model for life-course reasoning that bridges large language models with longitudinal panel data. By representing each life event as a structured natural-language record and instruction-tuning a pretrained 24-billion-parameter language model across an 18-task evaluation taxonomy spanning prediction, robustness and reasoning, LifeSentence supplements panel data with distributional knowledge already encoded during pretraining. Trained on approximately 65,000 individuals from the German Socio-Economic Panel - roughly 45 times fewer than prior transformer-based approaches - LifeSentence outperforms classical and deep learning baselines across all task families, achieving a threefold improvement in joint event-and-timing prediction from best baselines and 91.2% Kendall's tau when reconstructing chronological order from timestamp-stripped event sets. Without explicit supervision, the model recovers documented patterns of social stratification, including the education premium, the gender wage gap and the motherhood penalty, from discrete event sequences alone. A natural-language interface further enables qualitatively new research queries, such as connecting an early-life history to a specified late-life endpoint, establishing LifeSentence as both a predictive tool and a probe for counterfactual exploration of human biographies.
### Title:
          A2SG:Adaptive and Asymmetric Surrogate Gradients for Training Deep Spiking Neural Networks
 - **Authors:** Yechan Kang, Yongjin Kweon, Mingyeong Seo, Sohee Park, Yeonguk Jeon, Jongkil Park, Hyun Jae Jang, Jaewook Kim, YeonJoo Jeong, Suyoun Lee, Seongsik Park
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Training deep spiking neural networks (SNNs) remains challenging due to sharp loss landscapes and temporal inconsistency caused by surrogate gradients. To address these challenges, we propose a unified framework: adaptive and asymmetric surrogate gradients A2SG. The adaptive gradients adjust an effective window for spatio-temporal adaptation, reducing spatial gradient variation and maintaining directional consistency of gradients over time. The asymmetric gradients reflect neuronal dynamics by assigning larger gradients to neurons with higher membrane potentials, and we prove that they yield lower variation than symmetric surrogates. Our analysis further establishes a direct connection between local gradient variation and the curvature of the loss landscape, providing a principled explanation for how A2SG promotes convergence to flatter minima and improves generalization. We conduct extensive experiments on diverse models, including CNN-based and Transformer-based SNNs, across various tasks such as image classification using both static and neuromorphic datasets, as well as segmentation. The results demonstrate that A2SG consistently improves accuracy and energy efficiency, establishing it as a general and reliable solution for training deep SNNs. Our code is available at this https URL.
### Title:
          TileFuse: A Fused Mixed-Precision Kernel Library for Efficient Quantized LLM Inference on AMD NPUs
 - **Authors:** Wesley Pang, Gregory Hyegang Jun, Feiyang Liu, Deming Chen
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Artificial Intelligence (cs.AI); Hardware Architecture (cs.AR); Performance (cs.PF)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the growing demand for on-device LLM inference, edge SoCs increasingly integrate NPUs to improve performance and energy efficiency under tight power and thermal budgets. However, practical LLM deployment on current client NPUs remains difficult: widely used quantization formats such as AWQ do not map cleanly onto many existing NPU software stacks, which are often proprietary and expose limited low-level control. In this work, we present \textit{TileFuse}, a close-to-metal mixed-precision kernel library for AMD XDNA2 NPUs that targets transformer linear layers in quantized LLM inference. TileFuse brings practical low-bit formats such as AWQ-style W4A16 and W8A16 directly onto XDNA2, rather than forcing the model to be reshaped around an NPU-specific quantization scheme. TileFuse co-designs weight layout, metadata placement, mixed-precision microkernels, and array-level dataflow. Specifically, it fuses unpacking, dequantization, and GEMM/GEMV execution into a single kernel flow, introduces an interleaved pre-tiling layout that supports GEMM dimensions up to 32K, and redesigns GEMV dataflow to utilize the full 4x8 AIE array. Across kernel-level evaluations, TileFuse improves performance by up to 121.6% for GEMM and 281% for GEMV over full-precision baselines, while delivering more than 2x performance and energy-efficiency gains over strong iGPU baselines on GEMM. In end-to-end LLM experiments on Ryzen AI laptops, TileFuse achieves up to 2.0x lower prefilling latency with more than 64.6% lower energy consumption. Together, these results show that XDNA2 is a practical target for AWQ-style edge LLM inference and that native NPU support for off-the-shelf quantization can make NPUs substantially more usable in real client deployments.
### Title:
          GLACIER: A Multimodal Student-Teacher Foundation Model for Molecular Property Prediction
 - **Authors:** Emily Nguyen, Yongchan Hong, Harsh Toshniwal, Yan Liu, Andreas Luttens
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Biomolecules (q-bio.BM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning models facilitate the discovery of molecules with tailored properties among billions of candidate compounds. However, the computational burden to develop and deploy state-of-the-art models continuously increases, limiting their scalability. Most large-scale models are unimodal in nature and overlook the potential to leverage complementary molecular data modalities. To address these shortcomings, this paper introduces the Graph-Language Alignment for Chemical Inference and Exploration using Representations (GLACIER) model, a student-teacher framework that integrates molecular graphs, SMILES strings, and physicochemical descriptors to learn rich molecular embeddings. Our framework consists of three stages: (1) we pretrain three student encoders on 100,000 drug-like molecules: a message-passing neural network for molecular graphs, a transformer-based encoder for SMILES strings, and a multilayer perceptron for physicochemical descriptors, (2) we fuse these student modalities using a novel Finsler geometry-aware module, and (3) distill complementary knowledge from large teacher models, including MiniMol and MolFormer, into a single lightweight model via contrastive learning. We demonstrate that GLACIER is a robust framework that delivers high predictive performance and computational efficiency in complex molecular property prediction tasks. Our code is publicly available at this https URL.
### Title:
          Bridging the sim2real gap in the table tennis robot with a transformer-based ball states predictor
 - **Authors:** Yin Bi, Christian Conti, Bilan Yang, Alexander Sigrist, Peter Dürr, Naoya Takahashi
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robotic table tennis is a representative benchmark for high-speed, closed-loop robotic control in dynamic environments, where accurate and fast prediction of ball states is critical for reliable planning and control. Physics-based approaches rely heavily on accurate parameter identification and precise initial state, while learning-based methods often struggle to capture long-range temporal dependencies and are typically trained on limited or simulated data. We propose a transformer-based framework for table tennis ball state prediction that leverages attention mechanisms to model long-range temporal correlations directly from historical observations, without relying on explicit flight or bounce models. To support robust learning and generalization, we collected a large-scale real-world dataset from players of varying skill levels and diverse ball cannon configurations. The combination of a high-capacity transformer architecture and extensive real-world data enables accurate long-horizon forecasting. Building on this capability, we introduce a plug-and-play sim-to-real transfer strategy, Swap Predictor at Deployment (SPAD), which replaces the physics-based simulator used during training with the proposed real-world-trained predictor at deployment, improving the sim-to-real transferability of the policy without requiring retraining. We demonstrate that this simple substitution effectively narrows the sim-to-real gap while preserving the efficiency and scalability of simulation-based training.
### Title:
          PT-WNO: Point Transformer with Wavelet Neural Operator for 3D Point Cloud Semantic Segmentation
 - **Authors:** Nhut Le, Maryam Rahnemoonfar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Point cloud semantic segmentation requires architectures that capture both fine-grained local geometry and broad global scene structure. Transformer-based networks have demonstrated strong performance by focusing on detailed local feature aggregation; however, global context is conveyed primarily through skip connections across encoder-decoder stages, which we argue is insufficient for full scene understanding. We hypothesize that augmenting skip connections with a learnable global feature extraction module allows the network to acquire scene-level knowledge before descending into local detail, leading to richer and more contextually grounded representations. To this end, we propose Point Transformer with Wavelet Neural Operato (PT-WNO), which integrates a shared Wavelet Neural Operator (WNO) branch alongside the skip connections of a point cloud transformer backbone. At each encoder-decoder transition, point features are projected onto a dense 3D volumetric grid where the WNO captures multi-scale global spectral context through learnable wavelet decomposition and reconstruction. These global features are fused back into the network via lightweight adapters, complementing rather than replacing the existing skip connections. Experiments on four large-scale 3D point cloud benchmarks demonstrate the effectiveness of PT-WNO. On S3DIS (Area 5), PT-WNO achieves 71.59% mIoU, outperforming the Point Transformer v3 (PTv3) baseline by +1.03 points. On DALES it achieves 81.05% mIoU (+1.47 over the baseline). On ScanNet~v2, PT-WNO obtains 76.19% mIoU, remaining competitive with the baseline (76.36%).
### Title:
          OmniLoc: A Geometry-Aware Foundation Model for Anchor-Free UE Localization Across Diverse Indoor Environments
 - **Authors:** Lei Chu, Yuning Zhang, Omer Gokalp Serbetci, Anushka Katiyar, Bassel Abou Ali Modad, Andreas F. Molisch
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Indoor localization from wireless measurements remains challenging in large-scale deployments due to substantial variation in building geometry, the set of detectable access points (APs), and the heterogeneity of received signals. Existing learning-based methods often perform well only in limited settings and degrade under environmental shifts, making robust anchor-free localization across diverse indoor environments notoriously difficult. In this paper, we present OmniLoc, an environment-interactive foundation model for anchor-free user equipment localization across diverse indoor environments. To the best of our knowledge, OmniLoc is the first foundation-model-based approach built directly on wireless measurements for this task. OmniLoc is built on three key designs. First, a unified input tokenization module converts heterogeneous wireless measurements into a common representation that is more amenable to learning. Second, a geometry-aware Transformer performs AP-aware feature extraction by emphasizing dominant APs while aggregating complementary evidence from supporting APs. Third, a geometry-aware location estimation module conditions regression on geometric embeddings to produce geometrically consistent location predictions. We evaluate OmniLoc on both a large-scale in-house dataset and a public benchmark dataset. Results show that OmniLoc significantly outperforms existing methods, consistently improves existing backbones when its design components are integrated, and demonstrates strong generalization in cross-environment evaluations.
### Title:
          Probabilistic Contrastive Pretraining for Multi-task ADME Property Prediction
 - **Authors:** Yifan Xue, Srimukh Prasad Veccham, Saee Paliwal, Tyler Shimko, Micha Livne
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Quantitative Methods (q-bio.QM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate prediction of absorption, distribution, metabolism, and excretion (ADME) properties is critical to drug discovery, but remains challenging because ADME endpoints are noisy, interdependent, and often data-limited. We propose a molecular graph-transformer pretraining framework that combines chemistry-specific self-supervision with contrastive mutual information machine learning (cMIM). Our method encodes molecular graphs into latent variables, reconstructs SMILES strings from the graph-derived latent codes, and augments the contrastive objective with domain-specific self-supervised chemistry tasks. Rather than treating these tasks as auxiliary regularizers with separately tuned loss weights, we formulate reconstruction, contrastive discrimination, and chemistry-specific supervision as unit-weighted log-probability factors in a single probabilistic latent-variable objective. For fine-tuning, we propose a multi-task GNN readout architecture with task-specific multilayer perceptron heads, preserving shared representation learning while mitigating negative transfer and improving the modeling of heterogeneous, nonlinear task relationships. Across Biogen, ExpansionRX, and ChEMBL-MT, the resulting Contrastive KERMT pretraining improves over the KERMT baseline by 7.6%, 9.9%, and 9.5% respectively (averaged over significantly-improved endpoints). Adding ADME-adjacent molecules to the pretraining corpus further improves transfer, and the contrastive component sharpens chemically meaningful latent neighborhoods.
### Title:
          APEX: A Network-Native Time-Series Foundation Model for Forecasting and Anomaly Detection for Wireless Edge Operations
 - **Authors:** Swadhin Pradhan, Niloo Bahadori, Peiman Amini
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generic time-series foundation models transfer poorly to wireless network telemetry whose signals are bursty, zero-inflated, and coupled across protocol layers. We present APEX, a network-native, decoder-only transformer for forecasting enterprise AP telemetry, and evaluate it on DHCP degradation as a representative network task. APEX is pre-trained on 10-channel multivariate telemetry from ~4,500 production wireless networks (~100K AP time series, 34 metrics per AP), and is available as APEX-Large (269M, cloud) and APEX-Edge (10.5M, edge). On a 192-step (4-day) DHCP degradation benchmark, APEX-Large reduces MAE by 18% over the strongest foundation-model baseline (Toto) and 38% over SARIMA, with anomaly-detection F1 = 0.93, while APEX-Edge enables sub-second, privacy-preserving inference on AP-class edge hardware. These results suggest network-native pre-training is a practical foundation for proactive wireless operations.
### Title:
          FreqKD: Frequency-Decoupled Cross-Modal Knowledge Distillation for Infrared Object Detection
 - **Authors:** Keval Thaker, Venkatraman Narayanan, Abdalmalek Aburaddaha, Samir A. Rawashdeh
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transfer learning from large-scale RGB foundation models to infrared (IR) imagery through knowledge distillation (KD) remains challenging due to fundamental differences in image formation physics. We investigate the spectral structure of the RGB--IR modality gap and observe that feature divergence is not uniform across spatial frequencies: low-frequency components (shape, layout) show greater cross-modal alignment than high-frequency components (texture, fine edges), which reflect modality-specific characteristics. Based on this analysis, we propose FreqKD, a frequency-decoupled distillation framework that applies asymmetric supervision adapted to each band's cross-modal consistency. The method employs strict mean squared error (MSE) on the low-frequency band to preserve shared structural information and a relaxed log-MSE loss (weighted at 0.1) on the high-frequency band to provide edge guidance while tolerating texture differences. Spectral divergence analysis on 500 paired samples shows that high-frequency divergence exceeds low-frequency divergence by a factor of 2.4x on average across all analysed transformer layers. On KAIST multispectral pedestrian detection, FreqKD achieves 64.1 mAP50, improving 2.4 points over the DINOv2 baseline. The learned representation transfers across datasets (FLIR ADAS, +2.1 mAP50), tasks (MFNet segmentation, +1.85 mean intersection-over-union), and architectures (ResNet-50, +1.0 mAP50). Code is available at: this https URL
### Title:
          Kuramoto Attention: Synchronizing Self-Attention on the Torus
 - **Authors:** Joshua Nunley
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL); Adaptation and Self-Organizing Systems (nlin.AO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Kuramoto attention, a self-attention layer in which each hidden coordinate is an angle. The layer scores tokens by gated cosine similarity, attends over previous phase states, and updates each token by the tangent component of the attention-weighted circular mean. Because the values are the raw phase states, this update is exactly the Kuramoto coupling term $\sum_u A_{t,u}\sin(\theta_u-\theta_t)$, with the attention matrix acting as an adaptive, content-dependent coupling kernel. Equivalently, the gated score is a learned metric on the torus that selects which tokens couple, and the update pulls each token toward the circular mean of the tokens it selects, tightening their phase agreement. The same two ingredients, an invariant similarity score and an on-manifold mean, define such a layer on any compact group; the torus is the abelian case, where both are closed-form. The softmax weights solve an entropy-regularized phase-retrieval problem, and rotary position enters as a position-dependent phase drift in the score. On enwiki8 character-level language modeling, the layer trains as a functional language model whose bits-per-character stays close to a strong matched RoPE+SwiGLU transformer: within $0.02$ BPC at one million parameters ($1.637\pm0.010$ versus $1.616\pm0.004$) and level on the median at five million ($1.448$ versus $1.452$ over five seeds) with the transformer ahead on the mean ($1.468$ versus $1.456$). These experiments establish that the constrained geometric structure is a viable language model at this scale; the structure itself, and its synchronization reading, is the contribution. Ablations isolate the load-bearing components, and the result gives a compact bridge between self-attention and phase synchronization.
### Title:
          Frozen Foundation-Model Embeddings Discard Small-Lesion Signal in Chest Radiography: Implications for Pre-Deployment Evaluation
 - **Authors:** Raajitha Muthyala, Zhenan Yin, Alekhya Jilla, Frank Li, Theo Dapamede, Bardia Khosravi, Mohammadreza Chavoshi, Judy Gichoya, Saptarshi Purkayastha
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Frozen vision-transformer (ViT) foundation-model embeddings increasingly serve as the substrate for downstream chest-radiography (CXR) pipelines, yet where small-scale, low-contrast signal is retained or lost in the frozen forward pass has not been systematically quantified across architectures, pretraining domains, and objectives. We probed five frozen ViTs (RAD-DINO, DINOv2-B/14, DINOv3 ViT-7B, BiomedCLIP, MedSigLIP) and a frozen DINO-pretrained ResNet-50 architectural control across three large CXR cohorts (NIH-CXR14, MIMIC-CXR, Emory-CXR; aggregate pool n=492,724) and ChestX-Det10 (n=3,543; 1,462 small-lesion bounding boxes across Calcification, Nodule, Mass). Each model was evaluated with a small-scale-perturbation panel and a region-aware bounding-box-stratified probe on real lesions, comparing three pooling modes from the same forward pass: classification token (CLS), patch-mean (mean over all final-layer patch tokens), and bounding-box-restricted patch-local. On the perturbation panel, CLS embeddings sat at the chance floor (area under the ROC curve [AUC] 0.500-0.524); patch-mean was indistinguishable from CLS on iso-blur and reticular-fine cells but rose with CLS on larger directional-blur footprints, while disease AUC on globally decided tasks ranged 0.642-0.913. Patch-local probes recovered AUC ~1.0 from the same forward pass (per-model mean improvement +0.412 to +0.488); the ResNet-50 control reproduced the chance floor. On ChestX-Det10, image-level CLS classification showed within-class small-versus-large stratum gaps up to +0.243 AUC; bounding-box-level patch-local pooling on the same forward pass recovered AUC >= 0.899 on every (model x class) cell. Frozen ViT embeddings silently suppress small-scale signal at the global-aggregation step; the signal is recoverable from patch tokens conditional on a region of interest.
### Title:
          Adv-TGD: Adversarial Text-Guided Diffusion for Face Recognition Impersonation Attacks
 - **Authors:** Omid Ahmadieh, Nima Karimian
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Cryptography and Security (cs.CR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The widespread adoption of face recognition (FR) technologies raises serious privacy concerns, as facial data can be exploited without consent. To address this challenge, we propose Adv-TGD, a generative adversarial attack framework that synthesizes photorealistic faces capable of impersonating target identities and deceiving face recognition systems. Built upon Stable Diffusion, Adv-TGD performs per-sample LoRA fine-tuning conditioned on concise textual prompts to generate natural yet adversarially manipulated identities. Unlike conventional identity-attack approaches, our method optimizes lightweight cross-attention adapters for each source-target pair within a single-step denoising process. Latent blending is constrained by a face-local heatmap mask to ensure spatially precise identity manipulation while preserving non-sensitive regions. We introduce a composite objective that integrates masked epsilon-MSE reconstruction, thresholded identity divergence in FR embedding space, directional feature alignment, and source-similarity suppression to balance adversarial attack and visual realism. Optionally, LLaVA-generated attribute prompts enhance fine-grained semantic details without reintroducing identity cues. Under the black-box evaluation protocol, Adv-TGD attains an average attack success rate (ASR) of 85.90% across IR152, IRSE50, MobileFace, and FaceNet, surpassing the semantic SOTA baseline Adv-CPG by +6.25 points, diffusion-based makeup method DiffAIM by +3 points, and noise-based P3-Mask by +16 points. Despite its strong attack efficacy, Adv-TGD preserves high visual fidelity (PSNR = 27.15 dB, SSIM = 0.981). Furthermore, we demonstrate the flexibility of our framework by successfully extending it to in-the-wild datasets (LADN), general object classification (ImageNet), and transformer-based diffusion models (FLUX.1).
### Title:
          Precision-Aware Illumination-Disentangled Vision Transformer for Spacecraft 6D Pose Estimation
 - **Authors:** Zongwu Xie, Yifan Yang, Yonglong Zhang, Guanghu Xie, Yang Liu, Shuo Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision sensors provide a lightweight solution for spacecraft proximity operations, but monocular spacecraft 6D pose estimation remains difficult under illumination variation, specular reflection, shadowing, weak texture, and background interference. These factors make local visual evidence spatially unreliable and can destabilize pose regression. This article proposes a Precision-Aware Illumination-Disentangled Vision Transformer (PAID-ViT) for robust spacecraft pose this http URL proposed model separates pose-relevant structure tokens from illumination-sensitive appearance tokens, estimates patch reliability before pose aggregation, and uses foreground mask supervision to preserve silhouette cues. A parameter-free geometric recovery module converts normalized crop coordinates, log-depth, and a continuous 6D rotation representation into camera-frame rotation and translation. Experiments on SPEED+ V2, the SPEED+ validation/lightbox/sunlamp evaluation configuration used in this study, suggest that PAID-ViT reduces translation error and improves robustness in the challenging sunlamp domain, while ablation studies support the complementary roles of illumination disentanglement, reliability-aware token aggregation, mask supervision, and training-side regularization.
### Title:
          SAFER-Nav: Enhancing Safety for Visual Robot Navigation via Segmentation-Aware Fine-Tuning
 - **Authors:** Geonyeong Ko, Giung Lee, Changjoo Nam
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-based navigation models, particularly foundation models, generate viable trajectories from RGB observations alone. However, even state-of-the-art transformer- and diffusion-based policies struggle to generalize in unfamiliar deployment environments containing unseen obstacles or shifted conditions. The resulting trajectories often remain goal-directed but unsafe. Existing efforts improve safety through external trajectory correction or internal geometric priors, yet the resulting policies are not trained to explicitly represent obstacle boundaries or traversable free-space structure. To address this, we propose a navigation model that incorporates these structures directly into the policy via fine-tuning and is designed to be compatible with diverse RGB-based backbones. Across multiple robot platforms, indoor environments, and static and dynamic obstacle scenarios, our method reduces collision frequency relative to ViNT, NoMaD, and their CARE-augmented variants while maintaining goal-reaching performance.
### Title:
          Structure-Preserving Neural Surrogates with Tractable Uncertainty Quantification
 - **Authors:** Handi Zhang, Adrienne M. Propp, Brooks Kinch, Houman Owhadi, Nathaniel Trask
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Numerical Analysis (math.NA); Computational Physics (physics.comp-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in scientific machine learning provide a means of near-real-time solution to partial differential equations (PDEs), but lack the theoretical underpinnings of conventional simulators that support contemporary verification and validation. In this work, we construct data-driven reduced-order models that serve as structure-preserving, real-time surrogates. Remarkably, the exterior calculus that imposes physical conservation structure also exposes topological structure that we use to build a Gaussian process (GP) representation of uncertainty in state-flux relationships, ultimately yielding a Dirichlet-to-Neumann map for quantities of interest with closed-form expressions for posterior uncertainty. We specifically propose structure-preserving $H(\mathrm{div})$--$L^2$ subspaces of conventional Raviart--Thomas and $dgP_0$ elements prescribed by a lightweight transformer. Reduced-order dynamics consistent with this subspace are learned by posing a conservation law in which a GP describes the fluxes between volumes. This work hinges on a novel interface between mixed FEM spaces and GP regression; when training is posed as the optimal recovery problem (ORP), the resulting GP regression can be written as an optimization problem with equality constraints that impose a conservation structure, amenable to a fast Schur-complement training strategy. The trained model can then be solved in real time with closed-form estimators for boundary fluxes driven by prescribed Dirichlet data. The paper includes RKHS posterior error bounds for linear functionals to support uncertainty quantification, as well as numerical experiments demonstrating the accuracy of the posterior distribution as a surrogate for error estimation.
### Title:
          Learning Instance-Adaptive Low-Rank Orthogonal Subspaces for Clothes-Changing Person Re-Identification
 - **Authors:** Dong-Woo Kim, Tae-Kyun Kim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Clothes-changing person re-identification (CC-ReID) aims to recognize individuals despite drastic appearance changes caused by clothing variation. While existing methods rely on adversarial learning to disentangle clothing features, we propose Ortho-ReID, which explicitly models a low-rank clothing subspace from VLM text descriptions and extracts clothing-invariant representations via direct geometric constraints. A critical component is our transformer-based Basis Maker, which refines a shared, low-dimensional clothing prior into an instance-adaptive low-rank subspace through cross-attention with image patches, enabling robust clothing feature extraction even under varying visibility conditions. This instance-adaptive subspace is supervised via alignment with clothing text embeddings, while identity features are extracted via a learnable projection head and geometrically constrained to be strictly orthogonal to it. Extensive experiments demonstrate state-of-the-art performance on PRCC (+5.9% top-1), Celeb-reID-light (+3.5%), and LaST (+5.3%), with competitive results on LTCC.
### Title:
          Probabilistic Salary Prediction with Graph Attention Networks and a Mixture Density Network
 - **Authors:** Zhipei Qin, Mohammad Shokri, N. van Weeren, F.W. Takes
 - **Subjects:** Subjects:
Social and Information Networks (cs.SI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate salary prediction is critical for bridging the information gap between employers and job seekers in modern labor markets. Existing approaches predominantly yield a single point estimate and treat job attributes such as location, occupation, and industry as independent categorical features, ignoring both the inherent uncertainty and multi-modality of real-world compensation data and the rich hierarchical and semantic-similarity relationships that govern pay norms. In this paper we propose GAT-MDN, a unified framework that addresses both limitations simultaneously. For each of the three attribute domains we construct a domain-specific graph whose edges encode (i) hierarchical parent-child containment and (ii) weighted similarity links derived from a pre-trained Sentence-Transformer. Parallel Graph Attention Networks (GATs) with edge-feature-aware attention learn rich, context-sensitive node representations from these multi-relational graphs. A priority-based hierarchical selection module then assembles a composite feature vector that gracefully handles missing or coarse attributes, and a Mixture Density Network (MDN) head maps this vector to the parameters of a Gaussian Mixture Model (GMM), yielding a full conditional salary distribution. Extensive experiments on a real-world Dutch job-posting dataset of over 1 million records demonstrate that GAT-MDN significantly outperforms a non-graph MLP-MDN baseline in both Negative Log-Likelihood (NLL) and Mean Squared Error (MSE).
### Title:
          A Comprehensive Ecosystem for Open-Domain Customized Video Generation
 - **Authors:** Jingxu Zhang, Yuqian Hong, Daneul Kim, Kai Qiu, Qi Dai, Jianmin Bao, Yifan Yang, Xiaoyan Sun, Chong Luo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent progress in video generation has shown impressive visual synthesis capabilities. However, open-domain customized video generation remains limited by the lack of large-scale, annotated datasets capturing diverse identity-specific attributes. To address this, we introduce PexelsCustom-1M, the first publicly available million-scale dataset for identity-preserving video generation, containing one million curated <identity, text, video> triplets across 8,000+ categories. Leveraging this, we propose CustoMDiT, a parameter-efficient framework that adapts a pretrained multimodal Diffusion Transformer into a customized video generator with only 8% additional learnable parameters. Our method surpasses prior state-of-the-art. However, benchmarks such as DreamBooth cover only 100 classes, which is insufficient for real-world applications. To overcome this, we construct OpenCustom, a new benchmark with 1,000+ categories, created via cross-dataset knowledge fusion from ImageNet and MS-COCO. Extensive experiments confirm the advantages of both our dataset and model. We will open-source the entire ecosystem--including dataset, pipeline, benchmark, and implementations--to support further research.
### Title:
          Flow Matching with In-Context Priors for Out-of-Distribution Brain Dynamics
 - **Authors:** Sam Gijsen, Michał Łukomski, Marc-André Schulz, Kerstin Ritter
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Neurons and Cognition (q-bio.NC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Flow matching and diffusion models enable conditional generation across domains ranging from images to proteins, with recent extensions to out-of-distribution contexts. Yet generative models of neural time series have largely remained restricted to categorical conditioning, precluding compositional and zero-shot generalization. In this work, we propose a per-timestep conditioned diffusion transformer for generating realistic fMRI brain dynamics during unseen cognitive tasks by injecting both compositional language and optional spatial priors in-context. Such zero-shot generation could enable counterfactual neuroscience by supporting in-silico design and evaluation of novel cognitive experiments before empirical validation. Leveraging this model, we evaluate across hundreds of held-out task conditions and characterize predictive performance in relation to the training manifold. From language alone, the model recovers region-specific recruitment across tasks and held-out spatial activation patterns. Spatial priors, when available, complement the text pathway by anchoring generation in regions of task space where language alone degrades, while retaining the compositional structure needed for counterfactual task specification. To our knowledge this is the first generative model of whole-cortex fMRI dynamics for unseen cognitive tasks, advancing counterfactual neuroscience and data-driven experimental design.
### Title:
          LASA: A Weak Supervision Method for Open-Vocabulary Scene Sketch Semantic Segmentation
 - **Authors:** Liwen Yi, Xianlin Zhang, Yue Zhang, Yue Ming, Xueming Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open-vocabulary scene sketch semantic segmentation aims to assign dense semantic labels to sparse line drawings based on flexible category vocabularies specified at inference time, without relying on pixel-level annotations during training. Unlike natural images, sketches lack texture and color cues, making semantic understanding heavily dependent on stroke layout and spatial configuration, a challenge that renders single-layer vision-language features inherently unstable. Our key observation is that attention maps from different Vision Transformer layers encode complementary spatial cues: shallow layers capture global structural layouts, while deeper layers focus on local stroke intersections and object parts. This suggests that cross-layer aggregation provides a more robust structural prior than any individual layer alone. Leveraging this insight, we propose a structure-aware framework built upon \textbf{L}ayer-wise \textbf{A}ccumulated \textbf{S}tructural \textbf{A}ttention (\textbf{LASA}), which aggregates multi-layer attention to guide hierarchical semantic alignment under weak supervision and refine predictions during inference. Experiments on FS-COCO, SFSD, and FrISS show that LASA improves mIoU by $+3.43$, $+8.01$, and $+15.74$ over the prior weakly supervised baselines, demonstrating consistent gains in both segmentation accuracy and spatial coherence. Our source code will be made publicly available.
### Title:
          RePAIR: Predictive Self-Supervised Representation Learning in Chess
 - **Authors:** Christoph Koller, Johannes Fürnkranz, Timo Bertram
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we introduce Representation Prediction via Autoencoding using Iterative Refinement (RePAIR) - a novel self-supervised representation learning architecture that synthesizes Masked Autoencoders (MAE), Joint Embedding Predictive Architectures (JEPA), and Bidirectional Encoder Representations from Transformers (BERT). We demonstrate how it can be used to encode objects in sequential data like consecutive chess positions into compact yet meaningful representations. The basic principle of the architecture is to mask large portions of a sequence of latent states, similar to BERT and MAE. Then, we apply a lightweight Predictor to the latent representations that repairs gaps in the sequence in a lower-dimensional embedding space akin to JEPA. Our experiments in the domain of chess show that the Encoder refines the board representations such that meaningful chess concepts emerge clustered in the latent space. Furthermore, reconstructions of the masked board states show that the model is able to reason about the piece movements without relying on costly reinforcement learning methods. Lastly, we find that the resulting representation space allows for quick and intuitive dissections of chess games by observing the game path trajectories in this semantically rich space.
### Title:
          MemNovo: Look Back at the Spectrum for Balanced De Novo Peptide Sequencing from Mass Spectrometry
 - **Authors:** Dongxin Lyu, Jingbo Zhou, Hongxin Xiang, Yuqiang Li, Jun Xia
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Quantitative Methods (q-bio.QM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 De novo peptide sequencing from tandem mass spectrometry is pivotal in proteomics, enabling identification of novel peptides without reference databases. While recent Transformer-based encoder-decoder models have achieved remarkable performance, we uncover a critical pathology in their inference dynamics. Through comprehensive feature scaling experiments, we demonstrate that existing auto-regressive peptide decoders tend to over-rely on generated-sequence priors while progressively under-utilizing fine-grained physical evidence from the input mass spectrum. This phenomenon leads to suboptimal results, where generated peptide sequences are biologically plausible yet not faithful to the input spectrum. To rectify this, we propose MemNovo, a training-free and plug-and-play mechanism that re-balances peptide and spectral contributions at inference time. MemNovo alleviates the information bottleneck by establishing a persistent spectral memory bank and injecting retrieved features directly into the final decoding stage via an ultra-conservative residual connection. Theoretical analysis confirms that this mechanism restores the mutual information between the decoder state and the raw spectrum. Extensive experiments on the Nine Species benchmark with two representative baselines, Casanovo and InstaNovo, demonstrate that MemNovo consistently improves both amino acid precision and peptide precision, achieving up to 39.1% relative improvement in peptide precision for Casanovo and up to 3.9% for InstaNovo, with negligible computational overhead.
### Title:
          Lung-SRAD: Spectral-Aware Regularized Audio DASS with Dual-Axis Patch-Mix Contrastive Learning for Respiratory Sound Classification
 - **Authors:** Hemansh Shridhar, Miika Toikkanen, June-Woo Kim
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent respiratory sound classification (RSC) studies largely rely on CLS-token driven self-attention architectures such as the Audio Spectrogram Transformer (AST). While effective at modeling global context, recent analyses suggest a low-pass filtering behavior that may reduce sensitivity to localized abnormal patterns. In this work, we investigate State Space Models (SSMs) as an alternative backbone for RSC. Using the Distilled Audio State Space model, we analyze intermediate representations through spectral response curves and observe stronger preservation of mid-to-high spatial-frequency components. Based on these observations, we introduce spectral-aware layer regularization using Gaussian convolution applied to selected layers. We further propose Dual-Axis Patch-Mix contrastive learning tailored to SSM-based audio models for robust representation learning. Experiments on the ICBHI benchmark show that our approach achieves 64.48% score, outperforming the AST baseline by 5%. Code is available at this https URL.
### Title:
          Time-Series Foundation Model Embeddings for Remaining Useful Life Estimation
 - **Authors:** Amir El-Ghoussani, Michele De Vita, Ronald Naumann, Valiseios Belagiannis
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Remaining Useful Life (RUL) prediction is essential for industrial predictive maintenance, yet many learning-based approaches rely on extensive feature engineering or large labeled datasets to train task-specific sequence models. In this work, we introduce a lightweight learning approach, in which we leverage a frozen pretrained time-series foundation model (TSFM) and combine it with a small regression head for RUL estimation from multivariate sensor streams. More specifically, we use Chronos-2 as a frozen backbone to extract context window features and train a lightweight regression neural network for RUL prediction. Experiments on real-world industrial sensor data from two device types show that Chronos-2 features consistently improve over recurrent, convolutional, Transformer-based, and gradient-boosting baselines under the same preprocessing and evaluation protocol. We further analyze the impact of context length and find that performance improves significantly with longer histories, indicating that TSFM representation offer a practical and data-efficient alternative for RUL estimation in industrial settings.
### Title:
          ViT-FREE: Efficient Face Recognition via Early Exiting and Synthetic Adaptation
 - **Authors:** Tahar Chettaoui, Guray Ozgur, Eduarda Caldeira, Naser Damer, Fadi Boutros
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformers (ViTs) have gained significant attention in computer vision and shown strong potential for face recognition (FR). However, their high computational cost makes deployment on resource-constrained devices challenging, motivating the need for methods that balance efficiency and accuracy. In this work, we investigate early exiting in pretrained ViTs as a simple yet effective training-free strategy for efficient FR inference. Leveraging the uniform feature dimensionality across transformer encoder blocks, we introduce ViT-FREE, a multi-exit framework that enables face verification directly from intermediate representations without modifying or retraining the backbone model, and thus, reducing inference cost. Empirically, we show that patch embeddings and attention maps evolve progressively across depth, exhibiting high similarity between consecutive ViT blocks and increasing alignment with the final representation. This indicates gradual feature refinement and attention convergence, suggesting that intermediate layers already provide stable and discriminative representations suitable for early exiting. Through extensive experiments on multiple FR benchmarks, we systematically analyze the accuracy-efficiency trade-off across exit depths. Our results demonstrate that later exits achieve a highly favorable balance, with exiting at layer 10 yielding up to a 20% speedup while incurring only a 1.5 drop in verification performance on benchmarks such as IJB-C. Also, we propose ViT-FREE_FT, a lightweight exit-specific fine-tuning strategy that adapts only the projection layers using a small synthetic dataset while keeping the transformer backbone frozen. This approach improves the performance of shallow exits while preserving the efficiency benefits and leaving deeper exits largely unaffected.
### Title:
          Vision Transformers for Face Recognition Need More Registers
 - **Authors:** Tahar Chettaoui, Guray Ozgur, Eduarda Caldeira, Naser Damer, Fadi Boutros
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in Vision Transformers (ViTs) for face recognition (FR) have moved beyond the standard CLS-token paradigm. In this paradigm, a special classification token (CLS) is prepended to the patch embeddings and used as a representation of the input for downstream tasks. An alternative approach, Concatenated Patch Embeddings (CPE), instead leverages all patch tokens by concatenating them into a single vector, which is then projected into a compact face representation. CPE has been shown to improve recognition performance in comparison to CLS-based ones, but our qualitative analysis of attention maps showed the presence of artifacts that limit their interpretability. To address this issue, we incorporate register tokens, learnable tokens concatenated to the initial patch embeddings, and processed jointly through the ViT encoder blocks. This mechanism has been shown to produce more structured and interpretable attention maps compared to baseline ViT. We empirically demonstrate that these artifacts consistently appear across various ViT backbones, including small and large models, and that introducing register tokens effectively mitigates them. Adding four or eight registers significantly enhances interpretability, with eight registers providing the highest verification accuracies and smoothest attention structures. Our resulting model, ViT-8R, corresponds to a CPE-based ViT-B architecture augmented with eight register tokens achieves state-of-the-art performance among ViT-based FR models on large-scale IJB-B and IJB-C benchmarks. Also, ViT-8R produces substantially clearer attention maps compared with the baseline model, which offer deeper insight into the model's attention behavior (this https URL)
### Title:
          Attention by Synchronization in Coupled Oscillator Networks
 - **Authors:** Fabio Pasqualetti, Taosha Guo
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Neural and Evolutionary Computing (cs.NE); Adaptation and Self-Organizing Systems (nlin.AO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We address transformer attention on energy-constrained physical substrates. Softmax attention requires exponentiation and global reduction, operations with high energy cost on von Neumann hardware and no natural physical analog. We show that Kuramoto synchronization dynamics (which arise in electrical, mechanical, superconducting, and charge-density-wave oscillator arrays, among other physical systems) implement a well-defined attention operation without either. The resulting mechanism, fixed-query oscillator attention, replaces softmax's arithmetic with the equilibration of a gradient flow on the sphere: queries are learned anchors fixed on the sphere, and free oscillators evolve under Kuramoto-Lohe dynamics until they settle at positions encoding attention weights via cosine similarity. Because the computation is equilibration, it requires no exponentiation; the only global operation is an affine normalization at readout. The fixed point is provably unique and globally attractive from almost every initial condition, a guarantee that holds across every physical realization. Empirically, at the minimal hardware configuration (oscillator dimension $d_{\mathrm{osc}}$ = 2), oscillator attention outperforms softmax on keyword spotting (+1.00 pp) and on subject-verb agreement (+5.27 pp on hard sentences, with zero training failures versus one in five for softmax). On causal language modeling, where softmax retains an advantage, oscillator attention closes the gap as $d_{\mathrm{osc}}$ grows: from +11.09 PPL at $d_{\mathrm{osc}}$ = 2 to +2.98 PPL at $d_{\mathrm{osc}}$ = 32 on WikiText-2, and from +2.39 PPL at $d_{\mathrm{osc}}$ = 2 to +0.57 PPL at $d_{\mathrm{osc}}$ = 32 on TinyStories. The main objective of this work is not to replace softmax in software but to provide a mathematically grounded blueprint for accurate attention on physical substrates.
### Title:
          StanceNakba Shared Task: Actor and Topic-Aware Stance Detection in Public Discourse
 - **Authors:** Kholoud K. Aldous, Md Rafiul Biswas, Mabrouka Bessghaier, Shimaa Ibrahim, Kais Attia, Wajdi Zaghouani
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present StanceNakba 2026, a shared task on stance detection in polarized social media discourse related to the Palestinian-Israeli conflict, organized as part of Nakba-NLP 2026 at LREC-COLING 2026. The task introduces two subtasks: Subtask A (Actor-Level Stance Detection), which classifies English social media posts as Pro-Palestine, Pro-Israel, or Neutral; and Subtask B (Cross-Topic Stance Detection), which identifies Favor, Against, or Neither stances in Arabic posts toward two conflict-related topics, normalization with Israel and refugee presence in Jordan. The task is grounded in an annotated dataset of 2,606 social media posts. A total of 7 teams participated in Subtask A and 6 teams in Subtask B. Participating systems primarily fine-tuned Arabic and multilingual transformer-based models, including MARBERT, AraBERT, and DeBERTa-v3 variants, with several teams employing cross-validation, ensemble methods, and topic-conditioned architectures. The best-performing systems achieved a Macro F1 of 0.9620 on Subtask A and 0.8724 on Subtask B, demonstrating that transformer-based approaches are highly effective for conflict-domain stance detection while highlighting persistent challenges in cross-topic generalization and neutral class prediction.
### Title:
          Augmenting Molecular Language Models with Local $n$-gram Memory
 - **Authors:** Xinni Zhang, Zijing Liu, He Cao, Yu Li, Irwin King
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based language models for SMILES strings suffer from a locality gap: standard character-level tokenization fragments chemically meaningful motifs, forcing models to repeatedly learn local syntax at the expense of long-range dependencies. To address this without disrupting standard tokenizers, we propose MolGram, which integrates a conditional $n$-gram memory module into molecular language models. MolGram maps local string patterns to learned embeddings via scalable hash lookups and dynamically injects this regional context into hidden states. Evaluations across three tasks, including unconditional molecule generation, forward reaction prediction, and single-step retrosynthesis, show that MolGram consistently improves performance. Crucially, our analyses demonstrate that MolGram outperforms baselines with 3$\times$ more parameters, establishing explicit local pattern memory as a highly efficient inductive bias.
### Title:
          nD-RoPE: A Generalized RoPE for n-Dimensional Position Embedding
 - **Authors:** Boyang Li, Yulin Wu, Sizhe Xu, Nuoxian Huang, Zhonghang Yuan, Shangyi Guo, Shu Yang, Takahiro Yabe
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rotary Position Embedding (RoPE) is widely adopted in Transformer models, yet its extension to high-dimensional domains lacks a unified theoretical formulation. Most existing approaches either apply rotations independently along each axis or empirically mix frequencies, which limits cross-dimensional interactions and yields direction-dependent representations. To address these limitations, we propose nD-RoPE, a decomposition-free generalization of RoPE to arbitrary dimensions. From a translation-invariant formulation in continuous Hilbert space, we derive a spectral condition for isotropy that requires treating positions and frequencies as coupled \(n\)-dimensional vectors. We instantiate this formulation with a multi-scale regular-simplex wave-vector design, which provides non-degenerate spatial coverage and a symmetric, directionally balanced second-order response. Experiments across images, videos, and point clouds demonstrate consistent performance gains and improved generalization in high-dimensional settings.
### Title:
          DynaTok: Token-Based 4D Reconstruction from Partial Point Clouds
 - **Authors:** Weirong Chen, Keisuke Tateno, Hidenobu Matsuki, Michael Niemeyer, Daniel Cremers, Federico Tombari
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We address 4D reconstruction from partial point cloud sequences, where depth-sensor observations are incomplete, unordered, and lack explicit temporal correspondences. This geometry-only setting is challenging due to missing observations and ambiguous dynamics. While recent progress has largely relied on image-based methods, existing point-based approaches typically focus on single objects, assume relatively complete inputs, or require explicit correspondences. To address these limitations, we propose DynaTok, a point-based framework for correspondence-free 4D reconstruction from partial point cloud sequences without images. DynaTok encodes frames into compact latent tokens, aggregates incomplete observations over time with a Transformer-based spatiotemporal encoder, and decouples geometry and motion through residual tokens in a unified model. A flow-matching decoder then reconstructs complete, temporally consistent 4D point-cloud sequences conditioned on the latent tokens. Experiments on object- and scene-level benchmarks demonstrate improved reconstruction quality and temporal coherence from partial point cloud observations. Project page: this https URL.
### Title:
          Adapting Prithvi-EO for Fallow Detection for Food-Water Nexus: ViT-Adapter Necks and Parameter-Efficient Backbone tuning of Geospatial Foundation Model
 - **Authors:** Sk Muhammad Asif, Orhun Aydin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding spatial distribution of fallow land is important for optimizing the food-water (FW) nexus, given fallowing's role in crop rotation and water conservation. Fallow is a low accuracy class in USDA Cropland Data Layer (CDL). Geospatial foundation model (GFM), Prithvi-EO has shown strong transferability across computer vision tasks. However, its Vision Transformer (ViT) backbone produces features at a single spatial scale that are ill-suited for the multi-scale features required by object detection heads. Existing approaches synthesise multi-scale pyramids through scaling of single stride tokens, sacrificing spatial heterogeneity, and full backbone fine-tuning is computationally prohibitive for GFMs. We evaluate a fallow detection pipeline combining two parameter-efficient fine tuning (PEFT) schemes: Low-Rank Adaptation (LoRA) and a hybrid PEFT, with three neck designs: pseudo multi-scale, Lite ViT-Adapter, and Full ViT-Adapter. Our best configuration, Lite ViT-Adapter with a one-stage head, achieves a mAP@50 of 0.9479 with the Diou loss, suggesting the effectiveness of center-aware localization for irregular fallow field detection. ViT-Adapter free one-stage detection under LoRA improves the adapter-free anchor-based approach by 6.42%, and the best configuration improves baseline adapter-free anchor-based approach by 25.70%. These results demonstrate that lightweight spatial prior fusion and selective backbone unfreezing enable Prithvi-EO to capture local fallow patterns more effectively, outperforming approaches that rely on reshaped single-stride ViT tokens.
### Title:
          Holding the FP8 Quality Ceiling at 8-Bit Weights and Activations: INT8 and GGUF Post-Training Quantization of Ideogram 4.0 for Consumer GPUs
 - **Authors:** Deep Gandhi, Ali Asaria, Tony Salomone
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Post-training quantization lets large text-to-image diffusion transformers run on consumer GPUs, yet the hardware-specific trade-offs are seldom measured directly. We quantize Ideogram 4.0 - a 9.3B flow-matching diffusion transformer (DiT), shipped as two separate-weight copies of a single-stream 34-layer backbone for classifier-free guidance and conditioned by a Qwen3-VL-8B encoder - for Ampere RTX 3090 GPUs, which lack FP8 tensor cores. Our INT8 W8A8 recipe (per-channel weights, per-token dynamic activations, SmoothQuant, and mixed-precision protection of a small high-fragility layer set) holds the FP8 quality ceiling: on a 200-prompt benchmark the paired same-seed bootstrap CI for INT8-FP8 includes zero on both Pick and CLIP, while INT8 improves on NF4 by $+1.9$ CLIP (95% CI $[+1.21,+2.64]$, excluding zero). A per-category OCR analysis, to our knowledge unreported for this model class, confirms text legibility is preserved, and an ablation isolates protection of the FFN down-projections as the dominant quality lever. Our GGUF Q4_K quantization beats NF4 at equal on-disk size and is the Pareto winner on the quality-memory frontier, with paired confidence intervals excluding zero (Q8_0 is quality neutral). Finally, we characterize where 8-bit quantization helps and where it does not: INT8's weights match FP8's footprint rather than shrink it, so a speed gain on Ampere awaits a fused INT8 kernel.
### Title:
          SpikeDecoder: Realizing the GPT Architecture with Spiking Neural Networks
 - **Authors:** Claas Beger, Florian Walter, Alois Knoll
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Transformer architecture is widely regarded as the most powerful tool for natural language processing, but due to a high number of complex operations, it inherently faces the issue of high energy consumption. To address this issue, we consider Spiking Neural Networks (SNNs), which are an energy-efficient alternative to conventional Artificial Neural Networks (ANNs) due to their naturally event-driven approach to processing information. However, this inherently makes them difficult to train. Often, many SNN-based models circumvent this issue by converting pre-trained ANNs. More recently, attempts have been made to design directly trainable SNN-based adaptations of the Transformer model structure. Although the results showed great promise, the application field was computer vision. Moreover, the proposed model incorporates only encoder blocks. In this paper, we propose SpikeDecoder, a fully SNN-based implementation of the Transformer decoder block, for applications in natural language processing. In a series of experiments, we analyze the impact of exchanging different blocks of the ANN model with spike-based alternatives to identify trade-offs and significant sources of performance loss. We further investigate the role of residual connections and the selection of SNN-compatible normalization techniques. Besides the work on the model architecture, we formulate and compare different embedding methods to project text data into spikes. Finally, we demonstrate that our proposed SNN-based decoder block reduces the theoretical energy consumption by 87% to 93% compared to the ANN baseline.
### Title:
          Bridging the Modality Gap in Forensic Image Retrieval
 - **Authors:** Ricardo González-Gazapo, Annette Morales-González, Yoanna Martínez-Díaz, Heydi Méndez-Vázquez, Milton García-Borroto
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated image retrieval plays an increasingly critical role in modern forensic analysis, supporting investigative workflows that rely on efficient comparison of visual evidence. While prior work has focused primarily on developing and optimizing multimodal retrieval systems, limited attention has been paid to evaluating the forensic applicability of these technologies across diverse real-world scenarios. In this study, we present a unified retrieval framework adapted to four key forensic tasks: (1) tattoo image retrieval given a tattoo query image; (2) tattoo retrieval guided by human-expert textual descriptions, modelling the common situation where a witness verbally describes a tattoo; (3) tattoo retrieval from hand-drawn sketches; and (4) face retrieval from forensic face sketches. Our system leverages a multimodal large language model (MLLM) to automatically generate structured textual descriptions for all queries and gallery images, followed by sentence-transformer embedding for text-based comparison. We evaluate retrieval using visual-only embeddings, text-only embeddings and a multimodal fusion strategy that combines text- and image-based similarity scores derived from state-of-the-art visual feature extractors relevant to each task. The fusion of modalities consistently improves retrieval precision and robustness, especially in scenarios where visual information is limited or noisy (e.g., sketches, partial tattoos, or fragmented witness statements). This work highlights the forensic value of a unified multimodal retrieval pipeline and demonstrates how modern MLLMs can operationalize challenging forensic tasks that traditionally rely on manual expert analysis. Our results position multimodal retrieval as a promising tool for supporting investigative workflows involving tattoos, facial composites, and witness descriptions.
### Title:
          On Subquadratic Architectures: From Applications to Principles
 - **Authors:** Anamaria-Roberta Hartl, Levente Zólyomi, David Stap, Pieter-Jan Hoedt, Niklas Schmidinger, Lukas Hauzenberger, Sebastian Böck, Günter Klambauer, Sepp Hochreiter
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers dominate modern sequence modeling, but their quadratic attention incurs substantial computational cost. Subquadratic architectures offer a scalable alternative. However, it remains unclear which designs yield the most effective sequence models. We compare three leading approaches: xLSTM, Mamba-2, and Gated DeltaNet. We evaluate these models on tasks with complex dependencies: (1) code-model pre-training, (2) distillation of code models from large language models, and (3) pre-training of time-series foundation models. Across these settings, xLSTM delivers the strongest overall performance. To explain xLSTM's advantage, we present a unified formulation and analyze the underlying architectural mechanisms, focusing on state tracking and memory dynamics. Our results show that xLSTM enables more flexible and stable memory correction via its gating scheme. We corroborate these findings on controlled synthetic length-generalization tasks. Overall, our findings indicate that xLSTM's gains on complex tasks stem from robust state tracking and accumulation.
### Title:
          DepthMaster: Unified Monocular Depth Estimation for Perspective and Panoramic Images
 - **Authors:** Pengfei Wang, Shihao Wang, Liyi Chen, Zhiyuan Ma, Guowen Zhang, Lei Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While monocular depth estimation has achieved significant progress, achieving generalized metric depth estimation for both narrow field-of-view (FoV) perspectives and $360^\circ$ panoramas remains an unsolved challenge. Existing methods are often tailored to specific camera types and struggle to produce accurate metric depth that generalizes across diverse settings. This limitation stems from two key challenges: the inherent geometric discrepancy between perspective and panoramic cameras, and the scarcity of panoramic training data with metric annotations. In this work, we introduce DepthMaster, a unified metric depth estimation framework. Rather than employing specialized networks to learn spherical distortions, we reformulate the problem by decomposing panoramic images into overlapping perspective patches. Crucially, distinct from prior projection-based methods that rely on ad-hoc architectural modifications to handle boundaries, we introduce a novel Correspondence Consistency Loss (CCL) and inject virtual projection cameras as geometric priors, allowing us to seamlessly stitch the patches while avoiding specialized operators and keeping the backbone largely compatible with standard Transformer designs. This strategy also resolves the geometric differences by unifying all inputs into a canonical perspective representation, and effectively circumvents data scarcity by directly unlocking powerful metric priors from vast perspective datasets. Trained on a mixed dataset that contains only one panorama dataset, DepthMaster achieves state-of-the-art zero-shot performance on 13 diverse datasets, outperforming not only universal methods but also leading specialist models in both perspective and panoramic domains.
### Title:
          Semantically-Aware Diver Activity Recognition Framework for Effective Underwater Multi-Human-Robot Collaboration
 - **Authors:** Sadman Sakib Enan, Junaed Sattar
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Effective multi-human-robot collaboration is essential for expanding human-led operations in the challenging and high-risk underwater environment. For autonomous underwater vehicles (AUVs) to become true teammates, they must be able to comprehend their surroundings and recognize a diver's activities to offer assistance and ensure safety. Towards this goal, we introduce DAR-Net, a novel transformer-based framework that analyzes complex underwater scenes to classify diver activities. Our contribution lies in a semantically guided learning formulation that couples transformer-based temporal reasoning with pixel-level scene supervision. This multi-loss training strategy explicitly aligns global activity recognition with local human-robot interaction semantics, which is particularly critical in low-visibility underwater conditions. To address the significant challenge of data scarcity in this domain, we present the first-ever Underwater Diver Activity (UDA) dataset, a foundational resource containing over 2,600 annotated images with pixel-level masks. Through rigorous experimental evaluations in a controlled environment, we demonstrate that DAR-Net achieves promising accuracy in recognizing six distinct diver activities, outperforming state-of-the-art models. While this dataset provides a crucial baseline, our work serves as a pioneering step, laying the groundwork for future research and facilitating the development of more intelligent, collaborative underwater robotic systems.
### Title:
          Illumination-Robust Camera-Based Heart-Rate Estimation for Physiological Sensing in Robots
 - **Authors:** Zhi Wei Xu, Torbjörn E. M. Nordling
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Physiological awareness is important for service, social, and assistive robots that interact with humans in everyday environments. Remote photoplethysmography (rPPG) enables non-contact heart-rate (HR) estimation from an RGB camera, making it a promising sensing modality for robot-mounted vision systems. However, illumination variation remains a major barrier to robust deployment. This paper presents an end-to-end spatial-temporal transformer framework for remote HR estimation on a new dataset with varied illumination. Our estimator integrates PRNet-based 3D face alignment, clip-level illumination augmentation, the Residual Temporal Standardization Module, and controlled hybrid temporal-frequency supervision. The training objective combines a Soft-Shifted Pearson waveform loss with a spectral Kullback-Leibler divergence loss, where a tuned weight ($\mathbf{\beta}$) controls the contribution of frequency-domain heart-rate guidance. Experiments on a static all-level mix protocol covering three illumination levels show that $\mathbf{\beta}=5$ provides the strongest result among the tested beta settings, achieving a best-run HR mean absolute error (MAE) of 0.79 bpm and an HR correlation of 0.982. Compared with the PhysFormer baseline evaluated on our dataset, our estimator reduces HR MAE by 93.6 %, while increasing HR correlation from 0.088 to 0.982, making it usable when illumination varies.
## Keyword: autonomous driving
### Title:
          ConsistencyPlanner: Real-time Planning with Fast-Sampling Consistency Models
 - **Authors:** Qichao Zhang, Xing Fang, Jiaqi Fang, Zhenwen Cai, Jie Ling, Qiankun Yu, Dongbin Zhao
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Closed-loop planning in complex, real-world driving scenarios presents a critical challenge for autonomous driving systems. While traditional rule-based methods are interpretable, their predefined heuristics lack the adaptability for dynamic traffic environments. Learning-based approaches have shown considerable promise. Conversely, learning-based approaches, despite their promise, struggle to balance the modeling diverse and multimodal driving behaviors and real-time planning, often leading to indecisive or unsafe actions. To address this limitation, we propose Consistency Planner, a real-time planning framework with fast-sampling consistency models. Our approach is built upon two key technical contributions. Efficient Multimodal Sampling: We employ fast-sampling consistency models to generate a diverse set of plausible future trajectories. This enables efficient, real-time exploration of multimodal actions, overcoming the computational bottlenecks of previous iterative generative methods. Heterogeneous Feature Fusion: We introduce an attention-enhanced decoder that dynamically integrates heterogeneous input features (including scene feature and action token) into a cohesive representation for robust planning. Extensive evaluation in the Waymax simulator demonstrates superior performance in safety metrics compared to existing methods, with particularly strong results in challenging dynamic scenarios.
### Title:
          Systematic Cybersecurity Risk Analysis of European Rail Traffic Management System
 - **Authors:** Kacper Darowski, Sebastian N. Peters, Lukas Lautenschlager
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 European Rail Traffic Management System (ERTMS) is a widely adopted standard unifying train management in the EU. While the standard allows for use cases like fully autonomous driving, cybersecurity has been an afterthought. Risk analysis enables the systematic assessment and prioritization of threats and mitigations. To date, it remains unclear which threats are most significant in ERTMS. This study systematically models components of ERTMS and analyzes their security in light of threats identified in the underlying technologies. The results suggest a concerning state of ERTMS, despite its critical role in railway safety. The use of legacy standards like EuroBalises and GSM-Railway (GSM-R) introduces vulnerabilities that persist across minimal ERTMS implementations, deployments incorporating various optional safety measures, and prospective future evolutions of the system, e.g., adopting Future Railway Mobile Communication System (FRMCS). Fully transitioning to European Train Control System (ETCS) level 2 was identified as the most significant measure for advancing ERTMS cybersecurity. The results indicate that a shift of ERTMS toward security is required to ensure availability and safe operation. While the chosen methodology proved its feasibility and shows remaining weaknesses of ERTMS, future work is needed to develop railway-centric adaptations to improve the quantification and evaluation of the computed risks.
### Title:
          AutoMine Solution for AV2 2026 Scenario Mining Challenge
 - **Authors:** Songliang Cao, Jiele Zhao, Yuru Wang, Hao Li, Daqi Liu, Zehan Zhang, Fangzhen Li, Yu Wang, Yue Zhang, Bing Wang, Guang Chen, Hao Lu, Hangjun Ye
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the development of autonomous driving systems, mining high-value, safety-critical, and planning-relevant scenarios from large-scale driving logs has become essential for data-driven evaluation. In this paper, we propose AutoMine, a robust self-refining scenario mining method based on LLMs and VLMs. AutoMine uses semantics-preserving prompt augmentation to reduce LLM prompt sensitivity, combines robust trajectory atomic functions with VLM-based functions to handle perception noise and open-world visual cues, and refines generated code through execution feedback from real logs. In the Argoverse 2 Scenario Mining Competition at CVPR 2026, AutoMine achieves a HOTA-Temporal score of 36.38 and a Timestamp BA score of 77.21.
### Title:
          Task-Aligned Stability Analysis of Vision-Language Models for Autonomous Driving Hazard Detection
 - **Authors:** Everett Richards
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language models (VLMs) are increasingly used for scene understanding in autonomous driving, but robustness analysis often relies on task-agnostic embedding stability alone. We study whether corruption-induced embedding drift predicts changes in a task-aligned hazard score derived from CLIP image-text similarities. Using controlled corruptions on BDD100K road scenes, we compare embedding drift against margin drift, defined as the change in hazard score under perturbation. The relationship is highly corruption-dependent: some families exhibit strong coupling between representation drift and decision drift, while others induce hazardous decision instability despite relatively modest embedding change. Furthermore, corruption families differ in failure direction: most suppress hazard detections via false negatives, while occlusion instead triggers false alarms, suggesting that benchmark design should account for asymmetric failure modes, not just overall instability rates. These results suggest that robustness benchmarks should include task-aligned stability measures in addition to embedding-level perturbation statistics.
### Title:
          Performance Analysis of YOLOv11 and YOLOv8 for Mixed Traffic Object Detection under Adverse Weather Conditions in Developing Countries
 - **Authors:** Quoc Thuan Nguyen, Ha Anh Vu, Ngo Dang Thanh Ngan, Minh Phuc Hoang Ngoc
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In modern vehicular systems, robust performance under harsh conditions has become a critical problem of autonomous driving. Our study delivers a comprehensive evaluation of the newest iteration of the YOLO series, which is YOLOv11 Nano architecture benchmarked against the widely adopted YOLOv8 Nano as a baseline on a custom fused dataset that combines the Indian Driving Dataset (IDD) [1] and Berkeley Deep Drive Dataset (BDD100K) [2]. We have analyzed the trade-offs among detection accuracy, inference speed, and computational efficiency in high-entropy scenarios involving dense mixed traffic, rain, and low-light conditions. Specifically, YOLOv11n achieves a mean Average Precision (mAP@50) of 46.6%, with a notable 3.2% improvement in Precision over the baseline, effectively reducing false positives in cluttered scenes. Furthermore, the proposed model exhibits enhanced energy efficiency, requiring 22% fewer FLOPs (6.3G vs. 8.1G) while maintaining real-time inference speed of 70.9 FPS on a Tesla T4 GPU, offering an optimal trade-off for safety-critical edge deployment.
### Title:
          Intelligent Automation for Embodied Benchmark Construction: Pipelines, Embodiments, Simulators, and Trends
 - **Authors:** Jinshan Lai, Jianwei Hu, Baoyang Jiang, Fengchun Zhang, Leyuan Wang, Haotian Li, Yida Wang, Tingxuan Huang, Xi Ren, Qiang Ma
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Embodied intelligence now spans navigation, household assistance, manipulation, autonomous driving, aerial agents, and multimodal large-model control. This expansion has made benchmark construction a central bottleneck for reliable evaluation. Unlike static datasets, embodied benchmarks combine task specifications, environments, robot data, demonstrations, annotations, metrics, evaluation scripts, and release policies into a single evaluation system. This survey reviews the literature through a five-stage construction pipeline: requirement and task construction, data acquisition, data cleaning and annotation, benchmark suite generation and metric definition, and evaluation execution with diagnostic feedback. For each stage, the survey analyzes the transition from manual curation to traditional automation, foundation-model assistance, and agentic closed-loop workflows. It also compares qualitative construction costs across human labor, data and asset acquisition, compute and simulation, validation and debugging, governance and maintenance, and rework risk. The main conclusion is that automation does not simply reduce benchmark cost. Instead, it often shifts cost toward validation, auditability, version control, and long-term governance. Progress in embodied evaluation will therefore depend not only on larger benchmark suites, but also on construction pipelines that are diagnosable, auditable, and responsibly refreshable.
### Title:
          DrivingAgent: Design and Scheduling Agents for Autonomous Driving Systems
 - **Authors:** Zhongyu Xia, Wenhao Chen, Yongtao Wang, Ming-Hsuan Yang
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many autonomous driving systems are increasingly incorporating foundation models to improve generalization and handle long-tail scenarios. However, this trend introduces two key challenges: (i) the manual and labor-intensive process of designing and integrating new models, and (ii) the lack of intelligent, dynamic scheduling mechanisms to meet strict real-time constraints. While Large Language Model (LLM)-based agents offer a promising avenue for automation, existing frameworks are ill-suited for autonomous driving. Specifically, they fail to distinguish between the fundamentally different requirements of system design and real-time scheduling, treat modules as opaque black boxes, and are not designed for continuous operation. To address these limitations, we propose DrivingAgent, a novel agent framework tailored to the dual challenges of autonomous driving system design and scheduling. In the design phase, DrivingAgent automates module development by interpreting system architecture, generating code, and validating modules via super-network training. In the scheduling phase, it employs a lightweight LLM trained with reinforcement learning to dynamically orchestrate system modules in real time, supported by a structured memory that integrates long-term storage with timestamped short-term context. Experimental results demonstrate that DrivingAgent achieves a superior speed--accuracy trade-off on both the nuScenes and Bench2Drive benchmarks.
