# Showing new listings for Wednesday, 2 September 2026
## Keyword: SLAM
### Title:
          Efficient and Robust Absolute Pose Estimation via Gravity-Prior-Driven Transformation Decoupling and Pose Refinement
 - **Authors:** Hu Cao, Qianyi Yang, Xinyi Li, Jiong Liu, Yinlong Liu, Alois Knoll
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Estimation of the absolute pose of an object is an essential task for various robotic applications. Recently, incorporating gravity direction as prior information has emerged as a popular approach to simplify absolute pose estimation. However, developing a robust and efficient algorithm to solve this challenging problem remains a difficult question due to large amounts of mismatches. In addition, obtaining an accurate pose solution from selected inlier correspondences with gravity prior is still a research gap. In this paper, we propose a novel transformation strategy that exploits geometric relations derived from the gravity prior. Through transformation decoupling, the original 6 degrees of freedom (DoF) absolute pose estimation problem is simplified into a 4-DoFs problem: 1-DoF for the rotation angle and 3-DoFs for translation, significantly improving the efficiency. For the 1-DoF rotation angle, we apply a one-dimensional global voting algorithm for optimal estimation. Once the optimal rotation is obtained, the mismatched correspondences are preliminarily filtered, and translation estimation, a linear problem, can be easily solved. Furthermore, to obtain accurate pose results, we introduce a novel pose refinement algorithm to enhance the accuracy of both rotation and translation. Extensive experiments on synthetic data and three publicly available real-world datasets (TUM RGB-D, ETH3D, and RobotCar) demonstrate that the proposed method achieves stronger performance compared to existing state-of-the-art (SOTA) approaches. To further validate our method, we integrated it into ORB-SLAM2. The results on the KITTI dataset show it effectively reduces drift and improves trajectory alignment during relocalization. The source code will be released upon acceptance.
### Title:
          VOIM: Training-Free Open-Vocabulary 3D Instance Mapping for RGB-D and Monocular SLAM
 - **Authors:** Sangmin Song, Sarath Kodagoda, Marc G. Carmichael, Karthick Thiyagarajan, Amal Gunatilake, Kelly Prentice, Jodi Martin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Voxel-Grounded Online Instance Manager (VOIM), a training-free voxel-grounded instance manager that builds open-vocabulary 3D instance maps from RGB-D or from monocular RGB alone, a regime no prior training-free system addresses. Online systems typically segment object instances and label them at first detection, committing when evidence is weakest. VOIM instead defers label and instance decisions until soft evidence from unmodified, off-the-shelf perception has accumulated per voxel across views. We show that the mapping stage, rather than the particular perception models, carries the result: across four perception configurations on ScanNet++, varying the region descriptor, the detector label prior and the mask source, the map exceeds the strongest online RGB-D system, OVO-SLAM, by between 4.8 and 11.7 mIoU. Perception is not neutral, and substituting that baseline's own descriptor family costs 4.1 of the margin, yet the baseline carries the marginally better 2D descriptor (33.7 vs. 31.5 mIoU over three scenes) and still realizes the weaker map. Under a like-for-like protocol VOIM reaches 44.07 mIoU on ScanNet++ against 32.37, winning all ten scenes and both aggregations (pooled 33.31 vs. 25.97), and the same system runs unchanged to fully monocular RGB, matching that baseline pooled on Replica (27.80 vs. 27.50). The advantage is regime-specific: under Replica's all-classes scoring, matched inputs give a split result, 28.60 vs. 27.50 pooled against 24.59 vs. 30.11 on the per-scene mean. Room scale is label-limited and building scale drift-limited. Labeling does not run in real time, dominated by per-class detection over the full vocabulary. The maps export occupancy grids and resolve free-form queries to object instances.
### Title:
          On-the-Fly3R: Towards Robust Online 3D Reconstruction with Feed-Forward 3R Models for Large-Scale UAV Scenarios
 - **Authors:** Zhe Shen, Liyuan Lou, Yifei Yu, Guanbo Wang, Quanjian Ji, Xin Wang, Zongqian Zhan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While feed-forward 3D reconstruction (3R) offers efficient end-to-end modeling, its application in large-scale UAV mapping is hindered by the prohibitive memory cost of Transformer attention. Current scalable streaming 3R methods assume temporally and spatially continuous inputs, rendering them ineffective for the weakly ordered or unordered image streams common in cross-strip UAV operations. To address this, we propose On-the-Fly3R, a training-free, progressive online 3D reconstruction framework for large-scale UAV images that upgrades various 3R backbones for large-scale UAV scenarios. Our method enables reconstruction from unordered inputs via retrieval-guided dynamic subset construction, which adaptively selects spatially relevant images. To further improve the robustness, a validation-rejection-retry mechanism is designed to guarantee global consistency, performing a pre-integration consistency check and automatically rejecting misaligned images and retrying with alternative subset. Finally, inspired by VSLAM, pose graph optimization based on the retrieval loop closure is employed to mitigate camera drift. Evaluations on several UAV benchmarks show that our On-the-Fly3R successfully scales various 3R models to over 5,000 images across square-kilometer UAV scenes, delivering substantially superior accuracy compared to several SOTA streaming 3R methods. Code is available at this https URL
### Title:
          Right Frame, Wrong Rule: Cultural Cues Expose the Financial Knowledge Gap They Were Meant to Close
 - **Authors:** Rania Elbadry, Ahmed Heakl, Saeed Almheiri, Fan Zhang, Muhra AlMahri, Xueqing Peng, Mohsinul Kabir, Shuyao Wang, Yi Han, Saadeldine Eletter, Duzhen Zhang, Preslav Nakov, Yuxia Wang, Fajri Koto, Zhuohan Xie
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 When a question has valid answers under different normative frameworks, a language model must decide which framework to use and whether it can answer correctly within it. We call this setting normative pluralism and study it in Islamic finance using a four-choice taxonomy that separates framework selection from within-framework correctness. This separation reveals the stereotype trap: a cultural cue steers a model toward one framework, but the model selects an incorrect answer within that framework. Across twelve models, two languages, and fifty demographic signals, cultural cues change framework selection and reveal substantial differences in accuracy, especially among non-frontier models. Under the strongest signal, large open-weight models select the Islamic framework 97% of the time. A two-choice evaluation would report near-perfect alignment, although 57--66% of those selections are incorrect. These findings motivate, but do not directly test, the competence-conditioned routing hypothesis: models may favor frameworks where they are more accurate, while cultural cues may expose framework-specific competence gaps.
### Title:
          Monocular Depth Estimation from a Single Image: Progress and Opportunities
 - **Authors:** Muxin Liu, Xiaoyang Lyu, Yang-Tian Sun, Yi-Hua Huang, Ziyi Yang, Peng Dai, Xiaojuan Qi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular depth estimation has long stood as a fundamental challenge in computer vision, enabling a wide range of applications including 3D reconstruction, robotics, autonomous driving, and augmented reality. This survey traces the field's evolution from early learning-based methods to the emergence of transformative foundation models. We begin by framing the problem, distinguishing between relative and metric depth estimation, and highlighting the key challenges that have shaped a decade of research. We then present common problem formulations and introduce the most widely used datasets, covering indoor, outdoor, and synthetic data. Following this, we review major advances prior to the foundation model era, distilling core insights from influential methods that contributed to improvements in accuracy, efficiency, and robustness. The survey then turns to the recent surge of foundation-model-based approaches, categorizing them into discriminative and generative paradigms and emphasizing the critical roles of large-scale pretraining (e.g., DINOv3) and synthetic data. We compare representative models using both quantitative benchmarks and qualitative examples, and discuss natural extensions to video-based depth estimation. Further, to illustrate real-world impact, we highlight the integration of depth estimation into applications such as visual SLAM, content generation, and robot perception. Finally, we outline open challenges and promising research directions as the field advances further into the era of foundation models.
### Title:
          Scalable Rao-Blackwellized Online Planning for High-Dimensional POMDPs
 - **Authors:** Jiho Lee, Nisar Ahmed, Kyle Hollins Wray, Zachary Sunberg
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Online planning under uncertainty remains a fundamental challenge for robotic systems operating in partially observable environments with high-dimensional state spaces. While sampling-based POMDP solvers enable approximate decision-making in large or continuous domains, their performance degrades as belief dimensionality increases due to the high variance inherent in Monte Carlo-based estimation. In this work, we extend the Rao-Blackwellized online POMDP (RB-POMDP) framework to improve its generalizability in high-dimensional settings through hybrid continuous-discrete belief representations. By analytically propagating uncertainty associated with marginalized state components during tree-based planning, the proposed approach reduces sampling-induced variance in value estimation. We demonstrate the effectiveness of this framework in a robotic search-and-rescue task by integrating it with FastSLAM 2.0. Experimental results show that the proposed planner achieves higher cumulative rewards using significantly fewer particles and planning simulations than purely sampling-based methods under equivalent computational budgets. These results suggest that structured high-dimensional robotic problems admitting tractable sufficient statistics can be effectively leveraged within the RB-POMDP framework for computationally feasible online decision-making.
## Keyword: odometry
There is no result 
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          MultiGait: A Multi-Sensor Multi-Perspective Multi-Session Biometric Inference Benchmark and its Dataset
 - **Authors:** Julian Todt, Felix Morsbach, Philip Dissert, Thorsten Strufe
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A lack of suitable datasets has limited the research into the privacy risks of novel smart city sensors, such as thermal cameras, depth cameras, and lidar. Given the number of unsubstantiated privacy claims and their potential widespread deployment into many people's everyday life, understanding the privacy risks of these sensors -- in isolation and in like-for-like comparisons -- is crucial. With MultiGait, we collected the first multi-sensor, multi-perspective, multi-session gait-focused dataset, for the corresponding, and additional more far-reaching investigations. The dataset, validated with multiple state-of-the-art recognition systems, comprises various walking modes and annotated personal attributes for 199 individuals, to ensure the benefit for advanced studies including cross-sensor recognition and anonymization at the edge. MultiGait represents a foundation for rigorous privacy investigations, demonstrated through an extensive identity inference benchmark across eight sensors, four perspectives, and three recording sessions. Our benchmark incidentally reveals that sensors often assumed to be privacy-friendly do still entail considerable identity inference risks, while the poor cross-session generalization of existing methods underscores an important research gap.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          ES-AHD: An Evolution Strategy Framework for Automatic Heuristic Design
 - **Authors:** Yutao Lai, Kezhao Lai, Hai-Lin Liu, Yuping Wang, Ping Guo
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we introduce ES-AHD, a novel framework that fundamentally integrates Evolution Strategy (ES) into Large Language Model (LLM)-driven Automatic Heuristic Design (AHD). Existing evolutionary approaches predominantly rely on random, individual-level mutation, leading to blind search and an imbalance between exploration and exploitation. To address these issues, ES-AHD introduces two core mechanisms. First, Semantic Recombination via LLMs discards traditional point-to-point reproduction. By leveraging the LLM's contextual reasoning to explicitly extract core insights from top-performing individuals, the algorithm establishes a promising semantic search direction. This transforms random code mutation into targeted, center-guided sampling inspired by ES. Second, Stochastic Covariance Adaptation via Temperature Sampling dynamically addresses the exploration-exploitation dilemma. By mapping the covariance matrix in ES to the LLM's sampling temperature, the framework employs a stochastic random walk mechanism with momentum. This approach primarily shrinks the search radius for micro-level code refinement, while retaining the critical ability to occasionally sample higher temperatures to escape semantic local optima. Ultimately, ES-AHD provides a highly directional, robust, and efficient search paradigm, significantly accelerating the generation of high-quality heuristic algorithms. The source code is available at: this https URL.
### Title:
          RAPIDMap: Rapid Multi-Agent Pipeline for Interpretable Disaster Mapping from Satellite and Street-view Imagery
 - **Authors:** Yifan Yang, Lei Zou
 - **Subjects:** Subjects:
Multiagent Systems (cs.MA); Artificial Intelligence (cs.AI); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rapid and reliable disaster mapping of impacted areas, damaged infrastructure, and affected populations is essential for emergency response and recovery. However, existing AI-based approaches often require extensive manual annotation, lack cross-hazard generalization, and rely on single-modal observations. To address these challenges, this paper proposes RAPIDMap, a rapid multi-agent pipeline for zero-shot interpretable disaster mapping from satellite and street-view imagery. The framework integrates four intelligent agents: Disaster Perception Agent (DPA), Image Restoration Agent (IRA), Damage Recognition Agent (DRA), and Disaster Mapping Agent (DMA). By combining remote sensing and street-view data, RAPIDMap eliminates the need for manual fine-tuning, generalizes across multiple disaster categories, and generates structured, map-ready disaster intelligence with recovery recommendations.
### Title:
          Life Operators: a self-evolving framework for multiscale life modelling
 - **Authors:** Shuo Wang, Yike Guo
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Biological Physics (physics.bio-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Medical AI is moving beyond recognition towards clinical dialogue and longitudinal prediction. Yet a central question remains: how would a patient's state change under intervention? Statistical models learn future observations, whereas mechanistic models describe selected processes. Neither provides a common framework for representing patient state, coupling scales or revising failed assumptions. We propose Life Operators: task-bounded mappings that define three scientific roles. Perception operators infer task-relevant biological states from multimodal observations, Evolution operators propagate these states under natural or intervention-conditioned dynamics, and Generation operators map them to measurable signals. Each role may be realised by equations, statistical models, neural networks or hybrids. Bridge operators connect components with different variables, scales and time steps. Selected operators and bridges form task-specific Operator Graphs containing the smallest set of states and mechanisms sufficient for a declared claim. This modular structure also makes scientific revision localisable. An AI co-scientist may propose changes to states, operators, bridges or graph structure, while independent evidence determines which variants are retained, restricted or retired. Over time, validated components could accumulate into broader multiscale models of the human body and provide a computational foundation for medical artificial superintelligence.
### Title:
          Autoresearch for Marketplace Catalogs: From Legacy Forms to AI-Native Matching
 - **Authors:** Kartik Ravisankar, Hojat Abdolanezhad, Daniel Capo, Sang Su Lee, Shishir Dash, Vijay Anand Raghavan
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Two-sided service marketplaces are moving from deterministic request-form intake to AI-native probabilistic matching, enabled by large language models (LLMs) that infer intent, preferences, and latent constraints from natural language. Relying on inferred intent rather than fixed-form fields forces these platforms to regenerate the provider-side preference taxonomy underwriting matching, search, and pricing: attributes interpretable to service providers while remaining a useful signal for marketplace decisions. We present an autoresearch loop that generates this taxonomy, one occupation at a time, and has been deployed in production at a major U.S. consumer services marketplace since April 2026, spanning 132 occupations. Instead of one global hierarchy, the loop treats each occupation as an independent generation problem and runs iterative propose-evaluate-keep refinement cycles. Each candidate tag set is scored by a recalibrated six-rubric LLM-as-judge framework, and a 7-critic panel of distinct personas contributes weighted penalties to an adjusted score, with no hard vetoes. A separate parity-mapping stage maps legacy request-form Q&A pairs back to the generated taxonomy, yielding both a coverage signal and an interface for human quality assurance; it does so by first inferring the provider attribute each legacy question was meant to measure, rather than translating questions to tags literally.
### Title:
          Shape Holomorphy and Sparse Approximation of the Maxwell Electric Field Integral Operator
 - **Authors:** Paul Escapil-Inchauspé, Carlos Jerez-Hanckes
 - **Subjects:** Subjects:
Numerical Analysis (math.NA); Analysis of PDEs (math.AP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Uncertainty quantification for time-harmonic Maxwell scattering by obstacles of uncertain shape needs more than holomorphic dependence of the scattered field: for a boundary element method it is the boundary integral operator family itself that must depend holomorphically on the shape parameters. Two obstructions stand in the way. The natural energy space of the electric field integral equation, $\boldsymbol H^{-1/2}_{\mathrm{div}_\Gamma}(\Gamma)$, depends on the geometry, and the available operator-valued shape-holomorphy theory for weakly singular kernels is set in $L^2$, which does not reach it. We remove both. A surface contravariant Piola transformation identifies the geometry-dependent Maxwell trace spaces with a fixed reference space, and in the pulled-back variational formulation the surface Jacobians cancel exactly. The principal analytical ingredient is then a uniform fractional mapping theorem $H^{-1/2}\to H^{1/2}$ for the complex-deformed scalar single-layer family on uniformly $C^{1,1}$ surfaces, obtained by realizing the Laplace principal part as the trace of a complex-coefficient Newton problem on a fixed ambient space. The pulled-back operators are consequently $(\bm b,p,\eps)$-holomorphic for $\bm b\in\ell^p(\N)$, $0<p<1$, and pointwise exclusion of interior electric resonances over the compact real parameter set yields uniform invertibility. Legendre coefficients are therefore $\ell^p$ summable, so the operator family, the surface current and the far field all admit sparse polynomial approximations at dimension-independent best $N$-term rates. These statements are for the operator family itself in its energy-space operator norm, not only for individual solutions.
### Title:
          UniScale: Exploring Unimanual Gesture Mapping Strategies for Gaze+Pinch-based Scaling Interaction
 - **Authors:** Kyoungwhan Mheen, Jinwook Kim, Sang Ho Yoon
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Object scaling serves as a fundamental spatial manipulation that enables complex and productive tasks in XR environments. This paper investigates unimanual scaling techniques for XR using gaze and hand interactions. We propose UniScale, a set of unimanual alternatives to the standard bimanual pinch, allowing users to scale objects while preserving hand availability for concurrent spatial manipulations. We design five distinct mapping strategies based on physical metaphors, exploring unimanual control that varies depth, angle, micro-gestures, and finger-distance input. We then compare these techniques against a standard bimanual baseline, in which users adjust the inter-hand distance via a bimanual pinch gesture. In a user study, we evaluate their effectiveness in a 3D object scaling task under both clutching and clutching-free conditions. The results indicate that while bimanual scaling relies on clutching for stable control, unimanual techniques excel in clutching-free conditions, significantly reducing physical hand movement. From the results, we derive valuable design implications for developing efficient 3D multimodal interactions in XR.
### Title:
          A Mathematical Framework for Legacy, Governance, and Decision Integrity in Enterprise AI
 - **Authors:** Shorab Sarker
 - **Subjects:** Subjects:
Computers and Society (cs.CY); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Enterprise artificial intelligence is increasingly embedded in decisions that must remain lawful, explainable, adaptable, and accountable despite personnel turnover, model replacement, regulatory change, and shifting organizational incentives. Existing governance frameworks provide important principles but do not by themselves supply a compact mathematical language for evaluating whether an institution can preserve sound judgment over time. This paper develops a design-science framework for institutional legacy: the durable capacity of a decision system to continue producing beneficial, lawful, explainable, and adaptable outcomes after its original designers have stepped away. The framework contributes: (i) a normalized Legacy Score based on a penalized geometric mean of knowledge retention, governance, human oversight, adaptability, feedback learning, and jurisdictional fidelity; (ii) Decision Confidence and Decision Risk models separating evidentiary confidence from consequence; (iii) authority-aware retrieval and calibrated abstention; (iv) Decision Memory for governed organizational learning; (v) Regulatory Change Velocity mapping change exposure to review intervals; and (vi) a federated regulatory knowledge-graph architecture preserving provenance and legal hierarchy. The paper also proposes eight AI Decision Integrity Rules, an evaluation protocol, and a reproducible computational demonstration. The demonstration combines a deterministic stress test with 200 Monte Carlo replications of 10,000 synthetic decisions each, illustrating Legacy Score non-compensation and comparing consequence- and authority-aware routing with a matched-coverage confidence-only baseline. The contribution remains conceptual rather than field-validated; the simulation tests internal behavior, not production performance, and all parameters require context-specific calibration.
### Title:
          Restrict, Don't Retrain: Inference-Time VLM Guidance for Zero-Shot Aerial Segmentation
 - **Authors:** Teresa DiMeola, Charles Walter, Hong Xiao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Global welfare often depends on the correct interpretation of aerial and satellite imagery. Acting on such imagery (mapping flooded ground, crop extent, or damaged infrastructure) demands pixel-level segmentation to ensure perfect class localization. Pretrained general foundation models, when applied directly, often miss important features and cannot always find all the classes belonging to a given scene, overlooking smaller objects that matter most. We use a single consumer-grade GPU running a vision-language model (VLM) to supply this missing guidance, improving segmentation while producing structured, auditable evidence that drives the result and can be inspected on its own. We fuse three approaches: the frozen foundation model that labels every pixel, and two queries to a VLM, one to choose the classes that matter, and one to locate the small objects the base model misses. Evaluating across four aerial datasets, we see consistent gains at each stage where the base model is competent.
### Title:
          SciTrue: Reliable Scientific Claim Validation with Frontier and Open Language Models at the NTCIR SciClaimEval Task
 - **Authors:** Qiming Bao, Neşet Özkan Tan, Siyuan Wang, Mark Gahegan
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We describe the SciTrue team's participation in both subtasks of the NTCIR-19 SciClaimEval task~\cite{sciclaimeval}, which asks systems to verify scientific claims against the tables and figures of a paper. Rather than tuning a single model, we benchmark eleven frontier and open multimodal models under one honest, per-sample protocol and combine them with light, transparent post-processing. On the official, blind test leaderboard (Section~\ref{sec:results}), SciTrue placed first by a clear margin in three of the four evidence-category/subtask combinations, and tied for first on the primary metric in the fourth. Three findings explain the result. First, strong instruction-tuned models are already competitive: Claude Opus~4.8 and Gemma-4-31B each exceed the strongest public baseline (o4-mini), and GPT-5.5 and Claude Fable~5 lead both subtasks (97.7 on Subtask~2). Second, the task's pairing structure is the largest lever: a \emph{leak-free pair prior} that recovers the Supported/Refuted pairing from the claim text alone (a visible field) and assigns Supported to the higher-confidence evidence raises Subtask-1 pair-accuracy from 72.2 to 93.5, far more than any model swap or ensemble weighting. Third, a case-by-case audit finds that most residual errors are visually-undetectable label-mapping swaps or dataset label noise, so measured accuracy understates the true ability and the fixable-by-modeling headroom is small. Controlled fine-tuning, distillation, and agentic consistency-checking support the same conclusions, and we document throughout a measurement leak---label information reaching a system through the packaging of the data rather than its content---in which the released file ordering encodes the label, including one instance that briefly misled our own pipeline.
### Title:
          FALCON: Fault-Tolerant Magnetic Tunnel Junction-Based In-Memory Stochastic Architecture for Reliability-Critical Edge AI Applications
 - **Authors:** Farzad Razi, Mehran Moghadam, Sercan Aygun, M. Hassan Najafi, Marc Riedel
 - **Subjects:** Subjects:
Emerging Technologies (cs.ET); Hardware Architecture (cs.AR); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As modern data-centric applications such as neural inference and sensor-edge analytics expand, they increasingly encounter the von Neumann memory wall, suffering from excessive data movement overhead and stringent energy constraints. In-Memory Computing (IMC) utilizing emerging non-volatile technologies, such as Magnetic Tunnel Junctions (MTJs), promises to mitigate these bottlenecks. However, conventional binary radix-based IMC architectures suffer from excessive vulnerability to process-induced variations, restricted operating margins, and thermal noise. To bridge the gap between energy efficiency and computational reliability, this work proposes FALCON, a fault-tolerant, MTJ-based in-memory arithmetic architecture integrated with Stochastic Computing (SC). By encoding numerical values into uniform bit-streams, SC naturally absorbs localized soft errors and enables the execution of an essential suite of arithmetic operations using highly compact logic primitives directly within the memory arrays. FALCON integrates a deterministic bit mapping mechanism with reconfigurable logic-in-memory (LIM) structures, eliminating the need to transfer data to external processors or area- and power-hungry random number generators. Experimental results using 14 nm FinFET technology validate the correct functionality of FALCON even under aggressive voltage scaling, severe process variation, and noise injection levels up to 30%, making it a robust framework for reliability-critical edge AI applications. We investigate the proper functionality of FALCON on morphological closing as a realistic noise-tolerant image processing case study.
### Title:
          EarthLD: Towards Unified Open-World Landslide Understanding via Vision-Language Guided Diffusion Models
 - **Authors:** Yuanchao Su, Lianru Gao, Mengying Jiang, Jiangyi Chen, Jiaxin Cheng, Yicong Zhou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Landslides are widespread geological hazards, yet their automated detection and mapping in remote sensing imagery remain challenging because of their irregular morphology, ambiguous spectral signatures, and substantial domain shifts across imaging platforms. To overcome these challenges, we propose EarthLD, a vision-language-guided diffusion framework for open-world landslide understanding, enabling unified landslide recognition, mapping, and trigger interpretation. At its core, EarthLD formulates landslide understanding as a diffusion process that progressively infers the presence, spatial extent, and pixel-level boundaries of landslides from noisy latent representations. This probabilistic formulation enables the model to jointly perform image-level landslide recognition and mapping while characterizing predictive uncertainty. By integrating visual observations with contextual knowledge in the denoising process, EarthLD distinguishes diverse landslides from backgrounds, produces confidence-aware predictions for suspected regions, and maps landslide ranges. We additionally construct a global-scale open-world landslide benchmark by systematically harmonizing multiple publicly available remote sensing data collected by diverse institutions. Extensive experiments across regions, sensors, and triggering events demonstrate that EarthLD consistently outperforms existing landslide detection methods, highlighting its potential as a unified and robust solution for global geological-hazard monitoring and emergency response.
### Title:
          SOVER: Formal Certification of Optimization Reformulations via LLM-Assisted SMT Verification
 - **Authors:** Swapnil Bhattacharyya, Mayank Baranwal
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) have shown remarkable promise in translating and reformulating complex mathematical optimization problems across modeling languages. However, validating such transformations through empirical solver executions alone is unreliable, as solver outcomes may be affected by local minima, structural timeouts, numerical artifacts, and subtle semantic divergence between formulations. We introduce SOVER, an LLM-assisted SMT framework that separates semantic mapping from formal certification: Z3 checks domain cross-feasibility and global objective-order preservation for mixed-integer linear formulations, while dReal provides tolerance-aware feasibility/range and $\epsilon$-argmin checks for continuous nonlinear formulations. We also introduce NLEquiv-150, a public benchmark of 100 equivalent and 50 deliberately hard non-equivalent nonlinear reformulation pairs. With LLM-extracted mappings, SOVER classifies 149/150 pairs (99.33%) correctly, including all 50 hard negatives; the sole error is an incomplete mapping extraction.
### Title:
          VOIM: Training-Free Open-Vocabulary 3D Instance Mapping for RGB-D and Monocular SLAM
 - **Authors:** Sangmin Song, Sarath Kodagoda, Marc G. Carmichael, Karthick Thiyagarajan, Amal Gunatilake, Kelly Prentice, Jodi Martin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Voxel-Grounded Online Instance Manager (VOIM), a training-free voxel-grounded instance manager that builds open-vocabulary 3D instance maps from RGB-D or from monocular RGB alone, a regime no prior training-free system addresses. Online systems typically segment object instances and label them at first detection, committing when evidence is weakest. VOIM instead defers label and instance decisions until soft evidence from unmodified, off-the-shelf perception has accumulated per voxel across views. We show that the mapping stage, rather than the particular perception models, carries the result: across four perception configurations on ScanNet++, varying the region descriptor, the detector label prior and the mask source, the map exceeds the strongest online RGB-D system, OVO-SLAM, by between 4.8 and 11.7 mIoU. Perception is not neutral, and substituting that baseline's own descriptor family costs 4.1 of the margin, yet the baseline carries the marginally better 2D descriptor (33.7 vs. 31.5 mIoU over three scenes) and still realizes the weaker map. Under a like-for-like protocol VOIM reaches 44.07 mIoU on ScanNet++ against 32.37, winning all ten scenes and both aggregations (pooled 33.31 vs. 25.97), and the same system runs unchanged to fully monocular RGB, matching that baseline pooled on Replica (27.80 vs. 27.50). The advantage is regime-specific: under Replica's all-classes scoring, matched inputs give a split result, 28.60 vs. 27.50 pooled against 24.59 vs. 30.11 on the per-scene mean. Room scale is label-limited and building scale drift-limited. Labeling does not run in real time, dominated by per-class detection over the full vocabulary. The maps export occupancy grids and resolve free-form queries to object instances.
### Title:
          MROP: Mask-Region Optimized Purification Against Backdoor Attack in Deep JSCC
 - **Authors:** Seongkyu Yang, Hyeonho Noh, Hyun Jong Yang, Jonggyu Jang
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep joint source and channel coding (JSCC) transmits a source by mapping it directly to channel symbols through an end-to-end deep neural network (DNN) and reconstructing it at the receiver. Taking image transmission as an application, this DNN pipeline behaves as a black box: the receiver cannot readily detect security attacks when the transmitted images are corrupted, thereby introducing a new security vulnerability. In this letter, we study defense against input-patch backdoor attacks on deep JSCC, in which a small trigger patch attached to the input forces the decoder to emit an attacker-chosen target image. Most existing patch-trigger defenses are designed for classification, leaving the reconstruction setting of deep JSCC unaddressed. We adapt the gradient mask defense to this reconstruction setting as a baseline and then propose mask-region optimized purification (MROP), which operates at inference and requires no retraining of the JSCC model. Unlike the baseline, which localizes the trigger from the input--output gradient, MROP instead places a per-pixel mask at the encoder input and optimizes it via a Gumbel-sigmoid relaxation to localize the trigger, then refines the trigger region to reconstruct the pure images better. In numerical results, we evaluate the proposed method on CIFAR-10 and STL-10 datasets along with the DeepJSCC and SwinJSCC models. By doing so, we show that the proposed method substantially lowers the attack success rate (ASR) while preserving the peak signal-to-noise ratio (PSNR) of clean reconstructions.
### Title:
          VPID: An Integrated Framework for Vulnerability Prioritization and Intrusion Detection in Enterprise Networks
 - **Authors:** Xuanren Chen, Xin Wang, Xiaoqi Li
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Small enterprises face increasingly serious threats to their internal networks but often lack the financial resources, computing capacity, and specialist staff required to deploy resource intensive security platforms. This paper designs and implements VPID, a lightweight framework for vulnerability prioritization and intrusion detection that consists of two principal modules: controlled vulnerability validation and intelligent intrusion defense. The first module uses OpenVAS for asset mapping and vulnerability identification, applies a decision tree to prioritize vulnerabilities, and employs a rule engine to generate targeted validation payloads. The second module captures network traffic using Scapy, analyzes it through a detection pipeline that combines a decision tree with multinomial Naive Bayes, verifies traffic assessed as high risk using Snort rules, and performs blocking and alerting through iptables. The evaluation uses 550,000 network flow samples containing normal and attack traffic for detector training, together with 15,000 labeled vulnerability records. On the vulnerability ranking test set, the decision tree achieves a precision of 91.8%, a recall of 89.5%, and an F1 score of 90.6%. On an independent test set containing 55,000 traffic samples, the combined detection pipeline achieves a precision of 94.5%, a recall of 88.3%, and an F1 score of 91.3%, while maintaining a false positive rate below 1.5%.
### Title:
          Polished but Unresolved: Identifying Late-Stage Pressure States in Long-Horizon Tool-Use Agents
 - **Authors:** Haoyang Chen, Yi Liu, Jianzhi Shao, Xiaozhou Xu, Zhe Sun, Wei Hu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long-horizon tool-use agents need not only to search and plan, but also to decide when to finalize. We study late-stage pressure states, in which an agent is biased toward submitting a final answer that appears complete and polished while key constraints remain unresolved. We first train a linear probe to show that this pressure state is identifiable from the agent's hidden states. Then, we use activation interventions along this pressure direction and find that shifting the hidden states changes both the pressure score and whether the agent continues tool use or submits early. Through controlled context manipulations, we further see that the pressure is mitigated by constraint clarity and action mapping. Based on these findings, we propose Probe-Sensed Pressure Relief (PSPR), a plugin that applies lightweight pressure relief direction under moderate pressure and moves to structured organization under high pressure risk. Experiments on multiple long-horizon benchmarks show that our method consistently strengthens existing agent methods.
### Title:
          LLM Inference on IMC-NoC Architecture with Balanced Dataflow and Fine-Grained Parallelism
 - **Authors:** Yimin Wang, Yue Jiet Chong, Xuanyao Fong
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLM inference has become an essential service, yet it imposes unprecedented demands on memory bandwidth, computational density, and communication efficiency. While IMC is a promising solution to the memory wall issue, the heterogeneous data dynamicity of LLM requires complementary resources to handle intermediate data generated during run-time. Furthermore, the massive number of parameters in LLM necessitates scale-up architectures where on-chip data movement is often the primary performance bottleneck. This article presents a hardware-software co-design framework that unifies distributed compute, memory, and communication into a seamless processing-communication fabric. On the hardware side, we propose a scalable architecture, named LEAP, that integrates IMC PE, NMC PE, and INC. This allows each hardware layer to execute specialized tasks: IMC for static weights, NMC for dynamic data, and INC for partial result reduction. On the software side, we introduce a partitioning, mapping, and scheduling framework optimized for key metrics in LLM serving, including throughput and latency. To address the distinct computational intensities of the prefill and decode phases, we present a prefill-decode disaggregation approach that dynamically reconfigures PE organizations to maximize resource utilization. Compared to commercial GPU platforms, the proposed architecture provides a throughput and an energy efficiency improvement of $\geq{}1.52\times$ and $24.91\times$, respectively.
### Title:
          Benchmarking Vision-Language Models for Automated Pathology Diagnosis and Report Generation
 - **Authors:** Yumi Lee, Harim Oh, Hyoryung Kim, Minji Kim, Eunsu Kim, Hyeseong Lee, Junya Fukuoka, Andrey Bychkov, Jijgee Munkhdelger, Rajiv Kumar Kaushal, Ayushi Sahay, Rajni Yadav, Bharathi Prabakaran, Sulen Sarioglu, Serdar Balcı, Ilknur Turkmen, Yuri Tolkach, Christian Harder, Julian Westerdorf, Reinhard Buettner, Audun Ljone Henriksen, Sepp De Raedt, Byung Hyun Lee, Sungjin Lim, Joohoon Lee, Gwanghyun Kim, Se Young Chun, Suryakant Singh, Saarthak Kapse, Prateek Prasanna, Kyung A Kim, Yousun Kang, Sehwan Yoo, Sungman Hong, Shubham Innani, Michael Feldman, Spyridon Bakas, Ujjwal Baid, Prasad Dutande, Suhas Gajare, Bhakti Baheti, Serkan Sökmen, Ece Tuğba Cebeci, Ahmet Halıcı, Musa Balcı, Kardelen Peçenek, Srividhya Sainath, Kyongseok Jang, Messi H.J. Lee, Noorul Wahab, Bodong Du, Jiaming Zhang, Qixiang Zhang, Jang-Hwan Choi, Sangjeong Ahn
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid advancement of vision-language models (VLMs) has accelerated progress in computational pathology; however, whole-slide image (WSI)-based pathology report generation remains limited by the scarcity of large-scale WSI--report datasets and the complexity of mapping spatially distributed visual patterns to structured clinical text. To address this, we introduce a clinically curated Pan-Asia WSI--report dataset of approximately 10,500 pairs from five institutions and establish the REG 2025 benchmark through a MICCAI challenge for systematic evaluation of multimodal models. We analyze submitted methods spanning pretrained VLMs, multiple-instance learning frameworks, hierarchical expert models, retrieval-augmented generation, and cross-modal Transformers. Rather than indicating that VLM use alone was sufficient for superior performance, the results suggest that top-performing methods benefited from structured report representations, hierarchical diagnostic decomposition, and effective multimodal grounding. We identify key limitations, including instability in quantitative attribute estimation (e.g., numeric hallucination) and a tendency toward diagnostic overspecification, with some errors resembling known diagnostic pitfalls in routine pathology. These findings establish REG 2025 as a benchmark for evaluating WSI-based structured report generation and vision-language understanding in computational pathology, providing insights for the design of clinically grounded multimodal pathology models.
### Title:
          The Visual Insensitivity Gap: Diagnosing When Vision-Language Models Fail to Use Visual Evidence
 - **Authors:** Genpei Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language models are evaluated by aggregate accuracy on multimodal benchmarks, a practice that implicitly assumes the model uses its visual input. We show this assumption fails on 40%--97% of samples across six VLMs and three perceptual benchmarks: blurring the question-relevant visual region leaves the next-token distribution nearly unchanged. We name this phenomenon the Visual Insensitivity Gap and quantify it with a per-sample Visual Sensitivity Index (VSI). The gap is a property of samples, not of models: VSI ranks correlate across models (grand-mean Spearman rho=+0.40, permutation p<10^-3), so the same samples are flagged insensitive by VLMs sharing no architectural detail beyond a contrastively pretrained vision tower. The mechanism is concrete: on the insensitive samples, a linear probe on each model's own vision tower distinguishes perturbed from clean images at 0.72--0.79 accuracy, yet the model's argmax token changes on only 2%--11% of the same samples, an encoder--LLM gap above 0.65 on every model. Mapping VSI's diagnostic utility cell by cell surfaces a strong regime (multi-choice reasoning on capable VLMs: AUROC=0.85--0.87) and a weak regime (well-calibrated factuality, where softmax confidence already leads). VSI is not a universal best abstention signal; it is a sample-intrinsic indicator of vision-ignoring failure, best used as a conditional ensemble component.
### Title:
          CacheBridge: Efficient Cross-Model KV Cache Transfer
 - **Authors:** Xingyu Qu, Siyuan Lu, Zhiyu Chen, Sheng Wang, Tao Lin
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sharing context between LLMs in a multi-model system requires the receiving model to prefill the shared prefix because KV caches are model-specific. Recent closed-form cross-model KV transfer, hereafter Full-Head Mapping, avoids this replay by fitting a training-free affine mapper from source to target caches. However, its full-head design maps each target KV head from every source KV head in the selected layers, making transfer quality sensitive to architectural differences and causing mapper storage and application cost to grow with layer support. To this end, we introduce CacheBridge, which co-designs architecture-indexed mapper support, attention-aligned calibration, and bounded mapper construction while retaining a closed-form affine interface for online deployment. CacheBridge restricts each target head to a matched source head, weights reconstruction errors by causal attention sensitivity, and uses a fused GPU kernel to construct weighted sufficient statistics without materializing full observation tensors. Across three transfer directions, CacheBridge recovers the two Ministral 3 transfer directions where Full-Head Mapping loses substantial accuracy while preserving 99.83\% mean target retention on Qwen3. On Qwen3 $14\mathrm{B}\to32\mathrm{B}$, it reduces mapper storage by $8\times$, accelerates application by up to $3.0\times$, matches \fullhead with one tenth of the calibration data, and reduces 500-sequence construction from 92.63 to 8.63 seconds ($10.7\times$).
### Title:
          VIBE-Bench: Evaluating Personalized Large Language Models When Profiles Don't Mean Preferences
 - **Authors:** Yiwen Jiang, Yang Deng, Stephanie Fong, Zimu Wang, Yaling Shen, Wei Feng, Hongxi Yang, Xiangyu Zhao, Zhongxing Xu, Deval Mehta, Xuelian Cheng, Zongyuan Ge
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Personalized Large Language Models (PLLMs) aim to tailor responses to individual users, where a central challenge is preference reasoning: inferring query-relevant preferences from user-related history. Existing benchmarks, however, largely assume that such preference can be retrieved from semantically related history. We study an underexplored but practically important regime, profile-preference conceptual misalignment (PRCM), where observable profile cues and query-specific preferences lie in different concept spaces, making semantic retrieval inconsistent for personalization. We introduce VIBE-Bench, a benchmark with two psychology-grounded tasks, 3,504 personas and 12,239 dialogues, including a manually verified gold test set, and requires cross-concept preference reasoning beyond surface semantic overlap. Experiments with several personalization methods show that current PLLMs largely rely on shallow semantic correlations and fail to acquire robust cross-concept mappings. These findings establish PRCM as a distinct failure regime in PLLMs and position VIBE-Bench as a focused testbed for advancing preference reasoning beyond semantic matching.
### Title:
          On-the-Fly3R: Towards Robust Online 3D Reconstruction with Feed-Forward 3R Models for Large-Scale UAV Scenarios
 - **Authors:** Zhe Shen, Liyuan Lou, Yifei Yu, Guanbo Wang, Quanjian Ji, Xin Wang, Zongqian Zhan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While feed-forward 3D reconstruction (3R) offers efficient end-to-end modeling, its application in large-scale UAV mapping is hindered by the prohibitive memory cost of Transformer attention. Current scalable streaming 3R methods assume temporally and spatially continuous inputs, rendering them ineffective for the weakly ordered or unordered image streams common in cross-strip UAV operations. To address this, we propose On-the-Fly3R, a training-free, progressive online 3D reconstruction framework for large-scale UAV images that upgrades various 3R backbones for large-scale UAV scenarios. Our method enables reconstruction from unordered inputs via retrieval-guided dynamic subset construction, which adaptively selects spatially relevant images. To further improve the robustness, a validation-rejection-retry mechanism is designed to guarantee global consistency, performing a pre-integration consistency check and automatically rejecting misaligned images and retrying with alternative subset. Finally, inspired by VSLAM, pose graph optimization based on the retrieval loop closure is employed to mitigate camera drift. Evaluations on several UAV benchmarks show that our On-the-Fly3R successfully scales various 3R models to over 5,000 images across square-kilometer UAV scenes, delivering substantially superior accuracy compared to several SOTA streaming 3R methods. Code is available at this https URL
### Title:
          ASSERT: Adaptive Stochastic Sampling for Robust Diffusion Models on Analog Compute-in-Memory Hardware
 - **Authors:** Yuannuo Feng, Yizhe Chen, Wenshuai Yao, Yuxin Xie, Ngai Wong, Wenyong Zhou, Wang Kang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion models achieve strong image generation quality but incur high iterative denoising costs. Analog compute-in-memory (CIM) can accelerate matrix-vector multiplications, yet spatial memory variations perturb weights and accumulate during sampling. Unlike conventional neural networks, diffusion models' temporal sensitivity to hardware noise remains underexplored. We investigate diffusion inference using a noise model calibrated and validated against measurements collected from multiple physical CIM chips. Our results show that the early, high-noise denoising stage is substantially more vulnerable than the final refinement stage. A first-order trajectory analysis attributes this behavior to the repeated propagation of correlated prediction errors induced by a fixed hardware mapping. Based on this observation, we propose ASSERT, a training-free sampler that uses higher stochasticity early and smoothly transitions to deterministic denoising. The injected stochasticity changes subsequent activation trajectories and thereby reduces their alignment with persistent spatial errors. Across the evaluated settings, ASSERT achieves up to 2.58$\times$ lower FID than deterministic DDIM on high-resolution datasets and 7.68$\times$ lower FID in the CIFAR-10 step-count study, without changing model parameters or the number of network evaluations.
### Title:
          Conditional Flow Matching for Cross-Field MRI Harmonisation
 - **Authors:** Baris Imre, Aram Salehi, Levente Baljer, Andrew Webb, Marius Staring, Efe Ilicak
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Magnetic resonance images of the same subject look markedly different across field strengths, which complicates the comparison and pooling of data across sites. We address cross-field brain-MRI translation for the MRIxFields2026 challenge, and in particular its Task~3: a single model that translates between any directed pair of the five field strengths and across three contrasts. We phrase the problem as a conditional flow matching path: because the source and target volumes are spatially registered, we learn a velocity field that carries the source slice directly to the target slice, rather than starting from noise. To learn this mapping from only three paired subjects, the unified model is trained in three stages: a degradation-bridge pretraining that distills a restoration prior from the abundant unpaired retrospective cohort, a cross-field finetuning over all directed pairs on the paired cohort, and an adversarial refinement that sharpens the output. At inference, we integrate the learned velocity with a second-order Heun solver in a handful of steps. A restoration prior learned without any paired data already reaches a mean SSIM of 0.837, and each subsequent training stage improves on it. A single 6.3M-parameter model thereby covers all 60 field-pair and contrast combinations, with inference in five solver steps per slice. On the challenge evaluation set the model reaches a mean SSIM of 0.909, averaged over the three contrasts, outperforming regression and diffusion baselines built on the identical network on all three challenge metrics.
### Title:
          Inspicio: Open-Vocabulary, LLM-Based Sense Retrieval for Historical Languages
 - **Authors:** Michele Ciletti
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Word Sense Disambiguation has advanced rapidly for English and a handful of well-resourced modern languages, but it continues to assume the existence of a sense inventory and a word-to-sense mapping in the source language (Navigli, 2026). These assumptions break down for most historical and low-resource languages, whose dedicated WordNets are either incomplete or still under construction. We present Inspicio, an open-vocabulary retrieval pipeline that links tokens in context to synsets of the Open English WordNet (McCrae et al., 2020) without requiring any source-language inventory or mapping. For each occurrence, an instruction-tuned LLM produces two English translations of the surrounding sentence, a small set of candidate dictionary-style definitions, and a few candidate English lemmas. These outputs drive a hybrid retrieval step that combines dense definition-synset similarity, sparse lemma matching, and Maximal Marginal Relevance re-ranking. We evaluate the pipeline across a 6x6 grid of LLMs and sentence-embedding models on a new bilingual set of manually annotated Latin and Ancient Greek perception verbs, on a subset of PREMOVE dataset (Farina, 2025), and on a diachronic sample of Italian. The best configuration reaches 96% Recall@50 on the perception-verb test set, with each component contributing measurable gains, and remains competitive in the out-of-domain and cross-lingual settings.
### Title:
          What Limits Robustness in Deep Image Watermarking: An Analysis of Mechanisms and Their Scaling Across Capacities
 - **Authors:** Marta Bistroń, Zbigniew Piotrowski
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robustness remains the principal open problem in deep image watermarking, and what limits it becomes sharper as payload grows. This paper asks whether capacity is itself the limit or only makes other limits visible, and answers in two parts. The first organizes the distortions a watermark must survive and the strategies developed to resist them, ordering each by the axis that governs it: payload capacity for the distortions, differentiability for the strategies. The second identifies and measures three mechanisms that limit robustness in schemes mapping the payload onto a spatial block grid with extraction trained separately from a frozen embedder: desynchronization of the payload grid, the resistance of codec-induced distortion to training, and the narrowing of the usable embedding-strength window. Payloads from 64 to 16384 bits are measured, well beyond the range those strategies address. Training the extraction stage against a codec proves not merely ineffective but harmful, degrading the reading at the operating points used in training. The limits follow the class of distortion rather than capacity itself, and none is removed by further training on the extraction side, because all three arise before extraction. An evaluation protocol making claims of generalization verifiable is also contributed. The conclusions are properties of a class of designs rather than of one implementation.
### Title:
          StainPresetNet: Stain Preset Network for Fast Multi-to-Multi Stain Normalization
 - **Authors:** Hongtao Kang, Die Luo, Li Chen, Jing Cai, Junbo Hu, Xiuli Liu, Shenghua Cheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Stain normalization reduces color variations caused by variations in staining protocols and imaging conditions, thereby enhancing computer-aided diagnostic system performance. Traditional methods derive mapping relationships from individual or limited reference images through pixel-wise transformation, offering style flexibility but suffering from inaccurate color mapping extraction. While existing deep-learning-based approaches achieve accurate dataset-wide color mapping through complex neural networks, they face challenges including computational inefficiency, artifact generation, and fixed normalization directions requiring model retraining for directional changes. To address these limitations, we propose StainPresetNet - a novel framework that combines structural preservation with dataset-level color mapping while maintaining computational efficiency. Our method implements pixel-wise normalization guided by preset reference images, enabling multi-directional adaptability without retraining. Evaluations on cytopathology and histopathology datasets demonstrate that StainPresetNet achieves superior color mapping accuracy compared to conventional methods, effectively improves classifier generalization in diagnostic tasks, and reduces computational overhead by 90\% versus existing deep learning approaches. The proposed preset-guided mechanism facilitates flexible adjustment of normalization directions through simple reference image replacement, overcoming the directional rigidity of current deep-learning-based solutions.
### Title:
          TimeSteer: Inference-Time Speech Scheduling in Joint Audio-Visual Diffusion Models
 - **Authors:** Chao Zhou, Yiling Chen, Qi Chu, Tao Gong, Nenghai Yu, Tianyi We
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Although pretrained joint audio-visual diffusion models offer rich control over \emph{what} to generate, they provide no explicit control over \emph{when} an utterance should occur. To address this, we study \emph{inference-time speech scheduling}, a novel task that places coupled speech and visual articulation within user-specified begin--end intervals without finetuning the backbone model. We uncover two intrinsic properties of the denoising process that enable this task. First, a timing-sensitive text-to-audio cross-attention head exposes each utterance's model-implied source span along the latent timeline. Second, the predicted clean latent already organizes coupled speech and visual articulation, allowing their temporal placement to be edited without regenerating the content. Building on these discoveries, we propose \textbf{TimeSteer}, a training-free framework that localizes each utterance's source span through \textbf{Source Span Localization} and transfers the associated audio-visual latent content from the source interval to the specified target interval through \textbf{Region-Aware Latent Remapping}. We further introduce \textbf{SpeechShift}, the first benchmark for interval-level speech scheduling in joint audio-visual generation. Experiments across two representative backbones show that TimeSteer substantially improves interval controllability over training-free baselines while maintaining competitive overall generation quality.
### Title:
          HiLRP: Toward One Trustworthy Explanation for Vision Transformer: Conservation-Valid Attribution via Attention Primitives
 - **Authors:** Sathiyamohan Nishankar, Pubudu Sanjeewani, Asanka Perera, Selvarajah Thuseethan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformer (ViT) design has become increasingly diverse, with backbones combining convolutional stems, windowed, linear, or multi-axis attention, patch merging, and spatial reduction in various configurations. This diversity poses challenges for existing attribution methods, whose assumptions often do not hold across ViT variants: Grad-CAM requires a terminal spatial feature map, attention rollout assumes global softmax attention, and layer-wise relevance propagation (LRP) requires module-specific rules. To the best of our knowledge, no existing method provides a unified attribution framework across this architectural space. We show that this architectural diversity can be captured by a simpler underlying structure. The attention and resolution-reduction operators in current ViTs can be decomposed into four operation types: linear maps, bilinear mixing, normalization or gating, and reindexing. Each operation admits a relevance rule that satisfies conservation. Based on these rules, HiLRP supports new backbones by construction rather than by architecture-specific derivation, and its attribution maps decompose the prediction rather than relying on heuristic assumptions. We prove conservation and conditional equivariance and verify both to machine precision. Across 14 attribution methods and 10 architectures, we find that no prior method remains reliable across ViT families, while Faithfulness Correlation becomes uninformative for backbones robust to spatial masking. HiLRP alone preserves conservation across windowed, spatial-reduction, multi-axis, and linear-attention models, where naive extensions can produce zero or inflated relevance. It also localizes attribution failures in class activation mapping, achieving 0.97 Pointing compared with 0.55 for competing methods on EfficientViT.
### Title:
          CMRVision: A Foundation Model for Cardiac MR Image Analysis
 - **Authors:** Athira J. Jacob, Puneet Sharma, Daniel Rueckert
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cardiac magnetic resonance (CMR) imaging provides complementary information on cardiac anatomy, function, and tissue characterization across multiple sequences and views. In this work, we investigate foundation model pretraining for 2D CMR and introduce CMRVision, a CMR-specific foundation model trained using DINOv3-style self-supervised learning on a multi-center, multi-sequence cohort of 36 million CMR images. We systematically evaluate architectural and training design choices for domain-specific pretraining. CMRVision is evaluated on two downstream tasks: multi-task segmentation across cine, late gadolinium enhancement (LGE), and mapping sequences, and cine view classification. Our experiments show that CMR-specific pretraining, smaller patch sizes, and patch-level objectives consistently improve downstream performance. Across a multi-task segmentation benchmark, CMRVision achieved the strongest overall performance, outperforming prior natural-image (NI), medical-image, supervised, and CMR foundation model baselines. Improvements were modest but consistent across structures and sequences, with Dice scores ranging from 0.940-0.967 for LV and 0.855-0.905 for myocardium, and reaching 0.929 for RV, 0.920 for LA, and 0.931 for RA. The largest gains were observed for myocardium segmentation in LGE and mapping images. In a zero-shot segmentation task on unseen LGE long-axis views, the model achieved an average Dice score of 0.692, demonstrating cross-view generalization. For cine view classification, CMRVision achieved the highest average accuracy (0.906), compared to prior methods reported in the literature. These results highlight the potential of CMRVision to support robust and generalizable cardiac MRI analysis across multiple sequences and views.
### Title:
          ExBind: A Controlled Diagnostic Benchmark for Visual-to-Executable Correspondence
 - **Authors:** Ziqian Wang, Yuxiao Cheng, Tingxiong Xiao, Jinli Suo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal coding and editing systems must map a visible or semantic referent to the exact executable object that can be edited. A wrong reference may select a valid but incorrect DOM node, SVG element, graph endpoint, hierarchy member, or table cell, while final execution success alone does not reveal the source of the failure. ExBind isolates this visual-to-executable correspondence layer as a controlled diagnostic benchmark between semantic localization and action execution. It samples representation-independent latent binding instances and compiles them into SVG, DOM, canvas, tree, graph, and table cases with deterministic mappings to executable references. Models output only a strict reference; the evaluator maps predictions back to latent structure and scores structural constraints without requiring reasoning traces. The release contains a 250-case broad suite, a disjoint 240-case targeted suite, and 50 paired latent groups. Qwen2.5-VL-3B achieves 98.4% candidate validity but 76.4% exact accuracy, while Qwen3-VL-4B achieves 100.0% validity and 98.8% exact accuracy. In the targeted table suite, all Qwen2.5-VL-3B residual errors are valid correct-row/wrong-column selections. Candidate-order perturbations change case-level outcomes while preserving this error pattern. ExBind is designed for controlled diagnosis rather than population-scale ranking or end-to-end editing evaluation. Code and benchmark records are available at this https URL and this https URL.
### Title:
          Scale-based Approach for Active Wildfire Segmentation on Satellite Imagery
 - **Authors:** Matheus F. Kovaleski, Cristiano Premebida, João Ruivo Paulo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Active wildfire mapping from satellite imagery is challenging due to the sparse and highly imbalanced nature of fire pixels, especially in early-stage or low-density fire observations. This work investigates the use of multispectral Landsat-8 imagery for active-fire segmentation under multi-scale wildfire size conditions. We propose a data-driven protocol to characterize fire-region size distributions through connected-component analysis and an interquartile range criterion, enabling the evaluation of model robustness across different local fire-region densities. Three segmentation architectures, U-Net, DeepLabV3+, and SegFormer, are evaluated under different SWIR-based spectral configurations. Results show that U-Net achieves the strongest robustness across the evaluated conditions, SegFormer provides competitive performance, and DeepLabV3+ tends to produce conservative predictions with reduced recall. Across architectures, SWIR2 consistently achieves the strongest or near-best results, highlighting its importance for active-fire segmentation in Landsat-8 imagery. These findings suggest that both spectral band selection and architectural design are critical for robust satellite-based active wildfire mapping trained on low active fire-pixel density images.
### Title:
          Learning Sparse Decision Trees via Transformer Variational Auto-Encoders
 - **Authors:** Giacomo Fidone, Alessio Cascione, Riccardo Guidotti
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Decision trees are among the most widely used models in machine learning, largely due to their transparent decision logic, making them well-suited for high-stakes decision-making contexts. However, most existing learning algorithms focus on predictive performance, overlooking the joint optimization of other desirable properties, such as structural sparsity. In this work we propose TREVIS, an approach for learning decision trees with respect to complex objectives, based on the exploration of the latent space of a Tree Transformer Variational Auto-Encoder (TTVAE). By mapping decision trees onto latent representations, TREVIS replaces the discrete search space with a continuous one, enabling gradient-based optimization via a differentiable surrogate model. We experiment with TREVIS for learning decision trees that jointly optimize predictive performance and sparsity. Results show that TREVIS discovers decision trees matching the predictive performance of existing near-optimal algorithms while improving their structural sparsity.
### Title:
          SG-AMP: Scene-Graph-Guided Active Perception and Semantics-Aware Motion Planning for Pepper Plants
 - **Authors:** Rohit Menon, Shiva Rudra Lolla, Niklas Mueller-Goldingen, Gokul Chenchani, Ribana Roscher, Maren Bennewitz
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present SG-AMP, integrating robust depth completion with input-conditioned uncertainty, persistent panoptic mapping, plant scene-graph reasoning, and semantics-aware active view-motion planning. Beyond inspecting uncertain observed regions, the scene graph explicitly hypothesizes unobserved pepper--peduncle attachments and directs close-range sensing toward them. Candidate views are selected according to expected information gain, while class-dependent motion costs distinguish protected peppers, peduncles, and stems from conditionally traversable foliage. On pepper data, the perception network achieves $55.27\%$ semantic mIoU, $38.67\%$ PQ, and $40.62\,\mathrm{mm}$ depth RMSE, while input-conditioned uncertainty improves NYUv2 NLL from $-1.6518$ to $-1.6925$ and AUSE from $0.0102$ to $0.0087$.
## Keyword: localization
### Title:
          Auditing Harness Tampering in Self-Improving Agents
 - **Authors:** Xing Wang, Xiaoyi Zhang, Jie Shao
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-improving agents iteratively modify their own harness to push the frontier of their performance. However, such modifications can produce illusory performance gains or compromise integrity constraints such as authorization, provenance, and completeness without genuinely improving capability. We term this phenomenon as harness tampering, which extends the concept from reward and measurement tampering to the full self-improvement lifecycle. To systematically study this problem, we propose a two-axis taxonomy that categorizes each misaligned edit by the harness functional role in which it occurs and the obligation it violates. Then we build an annotated corpus by seeding tampered-benign edit pairs into the real trajectories of self-improving agents. We adapt and benchmark diverse audit methods on tampering classification and localization tasks. Finally we systematically audit real trajectories of self-improving agents. The results demonstrate that harness tampering consistently occurs in real runs from different agents, often persists in the lineage of the best agent, and forms distinct system-specific profiles across the taxonomy.
### Title:
          XVAE-WMT: Explainable Wavelet-Temporal Variational Autoencoder for Blind Source Separation of Heart and Lung Sounds
 - **Authors:** Yasaman Torabi, Shahram Shirani, James P. Reilly
 - **Subjects:** Subjects:
Sound (cs.SD); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The separation of cardiovascular sounds is a critical task in biomedical signal processing. In this paper, we introduce XVAE-WMT1, an unsupervised explainable generative AI algorithm combining a variational autoencoder (VAE) with explainable AI (XAI), wavelet-based inputs, a post-hoc output mask, and temporal consistency (TC) loss. Unlike existing supervised and VAE-based methods that rely on Short-Time Fourier Transform (STFT) and ignore latent interpretability, XVAE-WMT requires no paired clean recordings and integrates a Continuous Wavelet Transform (CWT) front-end for superior time-frequency localization. We assessed the latent space interpretability via different metrics, with SHAP (SHapley Additive exPlanations) enabling dimensionality reduction to the top 75% of latent features while preserving separation quality. Evaluated across two datasets using Signal-to-Distortion Ratio (SDR), Signal-to-Interference Ratio (SIR), and Signal-to-Artifacts Ratio (SAR), XVAE-WMT attains 26.8 dB SDR, 32.8 dB SIR, and 28.6 dB SAR.
### Title:
          The Answer Is Not the Argument
 - **Authors:** Will Yeadon, Sergio Juárez, Paul Mackay, T. J. Dowling, Elise Agra, Oto-obong Inyang, Arin Mizouri, Craig P. Testrow
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Chain-of-thought monitoring is proposed for AI oversight, yet evaluations often provide monitors with a trusted reference answer. We ask whether answer access improves reasoning verification or mainly exposes incorrect conclusions. We collected 237 step-numbered solutions to 79 Humanity's Last Exam physics questions from three frontier models, with no inserted errors, and independently labelled final-answer correctness and the first false step. The reference standard combined physicist annotations, an independent LLM debate, and source-masked adjudication. This yielded 24 critical traces in which the answer was correct but the trace contained a genuine error. 8 LLM monitors evaluated traces blind, with an unverified or certified answer, or after a blind commitment. Certification raised mean balanced accuracy from 0.637 to 0.796, while exact first-error localization rose from 0.261 to 0.379. Certification changed recall (the fraction of error traces flagged as erroneous) from 0.653 to 0.951 on wrong-answer traces but from 0.521 to 0.438 on critical traces; the contrast had the same direction for all 8 monitors (question-bootstrap 95% CI [+0.256, +0.506]). After blind commitment, monitors shown the answer newly flagged 93.8% of previously passed wrong-answer traces as erroneous, but only 18.0% of critical traces. Answer access therefore improves conclusion-consistency checking rather than independent verification of the supporting argument. For AI safety, these traces provide a benign analogue of reward hacking: an acceptable output does not establish that the process producing it was sound. Although the errors studied here were ordinary and mostly non-load-bearing rather than adversarial, trusted-answer evaluations may similarly overstate monitoring capability when acceptable outputs conceal unsound reasoning.
### Title:
          From Tool Use to Technological Agency: LoopCAT as a Local-First, Open-Source Tool for Translation Technology Education
 - **Authors:** Gokhan Dogru, Adrià Martín Mor
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Translation students need to learn both how to use translation technologies and how to judge the choices those technologies make available. This article presents LoopCAT, an Apache-2.0-licensed, local-first computer-assisted translation environment co-created with OpenAI Codex using GPT-5.5 and GPT-5.6, and proposes a framework connecting workflow competence, evaluative judgement, and technological agency. The account draws on repository history, implementation inspection, and the verification records of an identified development build. LoopCAT combines local project storage, translation memories, terminology, quality assurance, document exchange, and optional connections to local or hosted AI services. Its English, Catalan, and Turkish interface catalogs also make the application itself available as teaching material: students can translate English UI strings into another language, review the existing automatically generated target drafts, import their revisions, and test the interface. We organize these opportunities around four forms of participation: operating a workflow, evaluating outputs, inspecting and configuring mechanisms, and making or defending a bounded intervention. A six-session sequence, a UI-localization assignment, a placeholder example, and an assessment rubric specify how teachers could use the framework. The paper separates implemented capabilities from proposed educational benefits; it reports no new student-learning outcomes. It distinguishes the latest package checks from earlier regression evidence and sets out a protocol for classroom evaluation. LoopCAT provides an inspectable setting for teaching how translation decisions interact with data, interfaces, and software rules. Whether these activities improve judgement, transfer, or participation remains an empirical question.
### Title:
          Instance-Guided Report Anchoring for Text-Free 3D Abnormality Segmentation in Chest CT
 - **Authors:** Zhenyu Bu, Haoyan Ding, Chushu Shen, Xinyuan Zheng, Peiyu Duan, Xueqi Guo, Sepehr Farhand, Yoshihisa Shinagawa, Gerardo Hermosillo, Chaowei Wu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate 3D abnormality segmentation in chest CT requires dense spatial supervision, but obtaining expert voxel-level labels is costly. Radiology reports, however, are routinely generated during clinical interpretation and contain instance-specific descriptions that can provide additional guidance without new dense annotation. Existing vision-language grounding methods typically require report-derived findings at inference, making localization dependent on paired text and limiting each forward pass to a queried finding. We propose Instance-Guided Report Anchoring (IGRA), a model-agnostic module that preserves the correspondence between each annotated abnormality instance and the report finding that describes it. IGRA pools each instance representation and anchors it to the corresponding finding embedding during training; all text-related components are discarded at inference. We further reformulate free-text grounding on ReXGroundingCT as multi-label volumetric segmentation by merging same-category instances, allowing all abnormality categories to be predicted in one image-only forward pass. IGRA improves Dice by 22.5% over the strongest image-only baseline (30.93 vs. 25.25) and is comparable to VoxTell on the single-finding subset (30.29 vs. 30.43). Applied unchanged to four standard 3D segmentation backbones, IGRA improves Dice and hit rate across all architectures. Zero-shot evaluation on LIDC-IDRI, PleThora, and a private in-house dataset further shows consistent gains over image-only baselines.
### Title:
          Enoki: Efficient Multi-Level Hallucination Detection
 - **Authors:** Elisei Rykov, Timur Ionov, Nikolay Ivanov, Maksim Savkin, Maksim Makarenko, Alexander Panchenko, Vasily Konovalov, Julia Belikova
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ensuring factuality remains a critical challenge for deploying LLMs in high-stakes settings. Existing hallucination detectors usually operate at a single level: claim-level methods provide interpretable factual units, while span-level methods localize unsupported text. Bridging these views is costly, as LLM-heavy pipelines require multiple decomposition and verification calls, and modular systems need additional claim-to-span alignment. We propose Enoki, an Open Information Extraction framework for multi-level hallucination detection. Enoki extracts text-anchored relational facts, verifies them against evidence, and projects unsupported facts back to hallucinated spans. This shared representation enables claim-level verification and span-level localization without requiring separate alignment. Enoki supports LLM-based, encoder-based, and rule-based extraction regimes, balancing accuracy and inference cost through a common interface. Experiments show that Enoki remains competitive with strong claim-level systems while using fewer resources and achieves superior performance on fine-grained span- and entity-level localization. We also release EnokiQA, a dual-granularity dataset with aligned claim-level verification and span-level localization annotations.
### Title:
          Restrict, Don't Retrain: Inference-Time VLM Guidance for Zero-Shot Aerial Segmentation
 - **Authors:** Teresa DiMeola, Charles Walter, Hong Xiao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Global welfare often depends on the correct interpretation of aerial and satellite imagery. Acting on such imagery (mapping flooded ground, crop extent, or damaged infrastructure) demands pixel-level segmentation to ensure perfect class localization. Pretrained general foundation models, when applied directly, often miss important features and cannot always find all the classes belonging to a given scene, overlooking smaller objects that matter most. We use a single consumer-grade GPU running a vision-language model (VLM) to supply this missing guidance, improving segmentation while producing structured, auditable evidence that drives the result and can be inspected on its own. We fuse three approaches: the frozen foundation model that labels every pixel, and two queries to a VLM, one to choose the classes that matter, and one to locate the small objects the base model misses. Evaluating across four aerial datasets, we see consistent gains at each stage where the base model is competent.
### Title:
          Efficient and Robust Absolute Pose Estimation via Gravity-Prior-Driven Transformation Decoupling and Pose Refinement
 - **Authors:** Hu Cao, Qianyi Yang, Xinyi Li, Jiong Liu, Yinlong Liu, Alois Knoll
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Estimation of the absolute pose of an object is an essential task for various robotic applications. Recently, incorporating gravity direction as prior information has emerged as a popular approach to simplify absolute pose estimation. However, developing a robust and efficient algorithm to solve this challenging problem remains a difficult question due to large amounts of mismatches. In addition, obtaining an accurate pose solution from selected inlier correspondences with gravity prior is still a research gap. In this paper, we propose a novel transformation strategy that exploits geometric relations derived from the gravity prior. Through transformation decoupling, the original 6 degrees of freedom (DoF) absolute pose estimation problem is simplified into a 4-DoFs problem: 1-DoF for the rotation angle and 3-DoFs for translation, significantly improving the efficiency. For the 1-DoF rotation angle, we apply a one-dimensional global voting algorithm for optimal estimation. Once the optimal rotation is obtained, the mismatched correspondences are preliminarily filtered, and translation estimation, a linear problem, can be easily solved. Furthermore, to obtain accurate pose results, we introduce a novel pose refinement algorithm to enhance the accuracy of both rotation and translation. Extensive experiments on synthetic data and three publicly available real-world datasets (TUM RGB-D, ETH3D, and RobotCar) demonstrate that the proposed method achieves stronger performance compared to existing state-of-the-art (SOTA) approaches. To further validate our method, we integrated it into ORB-SLAM2. The results on the KITTI dataset show it effectively reduces drift and improves trajectory alignment during relocalization. The source code will be released upon acceptance.
### Title:
          Does Fault Localization Beat a Fresh Attempt? A Placebo-Controlled Study of Test-Guided Code Repair
 - **Authors:** Anik Jha
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fault localization can focus a code model's repair on the statements a failing test implicates, but a targeted edit may succeed merely because it is small, and a second model call may succeed without using the failure at all. We separate these explanations with three arms applied to the same failed candidate: blind whole-solution resampling, spectrum-based localization followed by suspect-span infilling, and same-length infilling at a disjoint random code span. Across three frozen 26-32B models, three benchmarks and 488 failing candidates, plus a separately declared 24B fourth model from a third family, three results follow. First, localization is rarely available: only 9.0% of failing candidates expose a failing public test with a usable spectrum. Second, among the 177 candidates localizable from a strong suite, localized infilling loses decisively to blind resampling at a matched attempt count (3:40, p = 3.0 x 10^-9), opposite to our hypothesis; the loss replicates in a third family at -11.3 points (95% CI [-16.6, -6.8]), and widening the edit does not rescue it. Third, against the random-span placebo localized infilling leads pooled (11:1, Holm-adjusted p = .019), but that lead resolves in no individual model under the analysis our shipped plan designates primary (best Holm p = .087), so we report the location effect as suggestive rather than established. Re-pricing attempts as tokens narrows but does not overturn this: a span attempt spends 21.7 generated tokens against 371.1, yet 16 localized attempts reach 6.8% while one blind attempt already reaches 10.1%. Infilling reproduces the removed span verbatim in 48.9% of attempts, which is why more budget does not help. We restrict every localization conclusion to the 24-32B models tested.
### Title:
          RPCBench: A Benchmark for Proactive Premise Critique in LLM-based Recommendation
 - **Authors:** Zhongru Chen, Yuan Wu, Yi Chang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models are increasingly used as interactive recommender assistants. Their evaluation should therefore go beyond plausible item recommendation and test whether they can recognize flawed recommendation requests. Existing recommender benchmarks mainly assess ranking, generation, or preference satisfaction, while existing error-detection benchmarks are usually not grounded in recommendation-specific user and candidate evidence. To address this gap, we introduce RPCBench, a benchmark for evaluating Recommender-Premise Critique: the ability to detect, diagnose, and properly handle faulty premises in natural-language recommendation requests. RPCBench contains evidence-grounded test instances from five recommendation domains and covers ten types of premise failures. Each instance provides a visible recommendation context and a corrupted user query. We further design a fine-grained evaluation framework that measures proactive detection, error localization, post-detection handling strategy, and evidence faithfulness. Through a systematic evaluation of 11 LLMs, we find that proactive detection is the main bottleneck in Recommender-Premise Critique, and models perform worst on underspecified-premise errors. We also observe that target-critical information density matters more than redundant evidence, and that longer reasoning does not monotonically improve critique quality: performance peaks at intermediate reasoning length, while overly long reasoning is accompanied by an overthinking penalty. The code is available at this https URL.
### Title:
          Does This Moment Justify the Recommendation? Counterfactual Behavior-Grounded Evidence Retrieval for Personalized Video Recommendation
 - **Authors:** Xin Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Personalized video recommendation predicts user preference at the video level, while temporal video grounding localizes query-relevant moments. However, strong localization does not establish whether the retrieved moment constitutes valid evidence for recommending the video to a particular user. We study counterfactual behavior-grounded evidence retrieval, which separates where personalized evidence occurs from whether such evidence exists and evaluates whether model predictions respond consistently when that evidence is replaced. We introduce CBGER-10K, containing 5,000 controlled factual--counterfactual pairs for 3,026 users, where each pair replaces only the focal behavior-supported segment while preserving the user, temporal position, and hard distractors. We further propose CBGER, a compact framework that decouples segment-level localization from video-level evidence estimation and learns both through structured counterfactual supervision. CBGER achieves $0.4432$ MRR, $0.6977$ Pair Accuracy, and $0.6987$ Intervention Consistency across five adapted personalized-highlight and temporal-grounding baselines. Notably, compared with QD-DETR, its MRR improvement is not statistically significant, while Pair Accuracy improves by $11.03$ points. These results show that accurate temporal localization does not necessarily imply reliable personalized evidence existence, motivating explicit evaluation of Whether alongside Where.
### Title:
          Fine-Tuning Large Language Models to Classify Pull Request-Issue Alignments: Going Beyond Prompting
 - **Authors:** Mustafa Yasir Altunhan, Hüseyin Özgür Kamalı, Eray Tüzün
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Context: Accurate alignment between pull requests (PRs) and corresponding issues is crucial for efficient software development and maintaining code quality, as misalignments can reduce traceability, hinder defect localization, and decrease maintainability. Objective: This study aims to improve automated PR-issue alignment classification by leveraging fine-tuned large language models (LLMs) across multiple alignment categories, and conducts interpretability analysis to investigate the effects of PR-issue fields on the predictions of fine-tuned LLMs. Method: Our methodology consists of dataset preparation, LLM fine-tuning, and interpretability analysis. We first extended an existing dataset and applied data augmentation to address class imbalance. GPT-4o was then fine-tuned via instruction tuning, and open-source LLMs including CodeLlama-7B, CodeQwen1.5-7B, StableCode-3B, CodeGemma-7B, and Deepseek-Coder-6.7B were fine-tuned using classification-specific heads. Interpretability analysis using Shapley Additive Explanations (SHAP) was conducted to examine the influence of PR-issue fields on predictions for the best-performing open-source LLM. Results: Fine-tuned LLMs outperformed baseline models, achieving average improvements of 6.15% in accuracy and F1-micro, 14.69% in F1-macro, and 6.15% in recall. CodeLlama-7B emerged as the best-performing fine-tuned LLM overall, while interpretability analysis revealed that code diffs together with issue body and PR body contents exert the greatest influence on predictions. Conclusions: Fine-tuning substantially enhances PR-issue alignment classification, improving both accuracy and efficiency. Interpretability analysis provides actionable insights into the dataset features driving alignment decisions, deepening understanding of how LLMs reason over software artifacts.
### Title:
          Smart Contracts Claimed Vulnerable by the CVE Database, with Labels and Source Locations
 - **Authors:** Monika di Angelo, Gernot Salzer
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Common Vulnerabilities and Exposures (CVE) database catalogs vulnerability claims in hard- and software, among them those pertaining to blockchain programs a.k.a. smart contracts. We present CVE-Smart-Contracts, a curated dataset of CVE records up to July 2026 referring to Ethereum smart contracts. The dataset contains the vulnerable artifacts (source code and runtime bytecode), labels according to three taxonomies, and function-level locations. The retrieval of CVE records, collection of additional evidence, validation of the correspondence between records and artifacts, label assignment, and vulnerability localization are automated, leaving 15% to manual analysis. The dataset does not validate the original vulnerability claims, but marks a few records obviously wrong as `refuted'. For the sake of reproducibility, all external inputs are retained, so that rerunning the pipelines results in the same outputs. The dataset comprises 491 records linked to deployed contracts, 26 referring to projects (mostly libraries), 45 without validated artifacts, and six records with refuted claims. The dataset supports empirical security research, in particular the evaluation of code analysis and repair techniques.
### Title:
          FinLifeBench: Exhaustive Life-Event History and Financial-State Reconstruction from Longitudinal Banking Dialogue
 - **Authors:** Hangyeul Lee, Juyoung Oh, Jaeyong Ko, Sunmin Kim, Jaeik Park, Hyunkyu Kim, Jungmin Son, Pilsung Kang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Repeated banking interactions require assistants to maintain complete, current, and traceable customer records as life changes emerge incidentally in routine requests. Existing benchmarks emphasize question answering, bounded episodes, or targeted recall rather than exhaustive longitudinal reconstruction. We introduce FinLifeBench, which evaluates two tasks over the same cumulative dialogue: reconstructing every life-event instance with its first-establishing session and reconstructing a complete 34-path financial state at consecutive checkpoints. The benchmark contains 6,000 eight-turn Korean banking sessions from 20 independent synthetic trajectories, with deterministic, exhaustive gold for 24 event types and 34 state paths and consensus quality assurance. Across eleven LLMs under a full-context condition, event-anchor recall falls from 0.591 at 15 sessions to 0.445 at 300. Errors are driven primarily by omitted events rather than poor anchor localization, while financial-state reconstruction frequently treats superseded or potentially outdated information as current; the best GCA@15 reaches 0.470. Performance on the two reconstruction tasks is only weakly associated. These results show that models can localize evidence for recovered events while still failing to maintain complete and temporally valid longitudinal records.
### Title:
          TimeSteer: Inference-Time Speech Scheduling in Joint Audio-Visual Diffusion Models
 - **Authors:** Chao Zhou, Yiling Chen, Qi Chu, Tao Gong, Nenghai Yu, Tianyi We
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Although pretrained joint audio-visual diffusion models offer rich control over \emph{what} to generate, they provide no explicit control over \emph{when} an utterance should occur. To address this, we study \emph{inference-time speech scheduling}, a novel task that places coupled speech and visual articulation within user-specified begin--end intervals without finetuning the backbone model. We uncover two intrinsic properties of the denoising process that enable this task. First, a timing-sensitive text-to-audio cross-attention head exposes each utterance's model-implied source span along the latent timeline. Second, the predicted clean latent already organizes coupled speech and visual articulation, allowing their temporal placement to be edited without regenerating the content. Building on these discoveries, we propose \textbf{TimeSteer}, a training-free framework that localizes each utterance's source span through \textbf{Source Span Localization} and transfers the associated audio-visual latent content from the source interval to the specified target interval through \textbf{Region-Aware Latent Remapping}. We further introduce \textbf{SpeechShift}, the first benchmark for interval-level speech scheduling in joint audio-visual generation. Experiments across two representative backbones show that TimeSteer substantially improves interval controllability over training-free baselines while maintaining competitive overall generation quality.
### Title:
          ExBind: A Controlled Diagnostic Benchmark for Visual-to-Executable Correspondence
 - **Authors:** Ziqian Wang, Yuxiao Cheng, Tingxiong Xiao, Jinli Suo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal coding and editing systems must map a visible or semantic referent to the exact executable object that can be edited. A wrong reference may select a valid but incorrect DOM node, SVG element, graph endpoint, hierarchy member, or table cell, while final execution success alone does not reveal the source of the failure. ExBind isolates this visual-to-executable correspondence layer as a controlled diagnostic benchmark between semantic localization and action execution. It samples representation-independent latent binding instances and compiles them into SVG, DOM, canvas, tree, graph, and table cases with deterministic mappings to executable references. Models output only a strict reference; the evaluator maps predictions back to latent structure and scores structural constraints without requiring reasoning traces. The release contains a 250-case broad suite, a disjoint 240-case targeted suite, and 50 paired latent groups. Qwen2.5-VL-3B achieves 98.4% candidate validity but 76.4% exact accuracy, while Qwen3-VL-4B achieves 100.0% validity and 98.8% exact accuracy. In the targeted table suite, all Qwen2.5-VL-3B residual errors are valid correct-row/wrong-column selections. Candidate-order perturbations change case-level outcomes while preserving this error pattern. ExBind is designed for controlled diagnosis rather than population-scale ranking or end-to-end editing evaluation. Code and benchmark records are available at this https URL and this https URL.
### Title:
          Obstacle-Aware Autonomous Coverage and Navigation for Outdoor Robots
 - **Authors:** Leonardo Gargani, Matteo Frosi, Matteo Matteucci
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long-duration outdoor coverage with autonomous platforms remains challenging beyond classical planning: deployments face localization drift in open spaces, obstacles in cluttered sites, controller feasibility in turn-heavy maneuvers, and persistent autonomy with energy management. We propose a unified ROS 2 architecture for outdoor coverage that combines coverage planning, robust localization, and Nav2-based execution. A dual-antenna RTK-GNSS fused in an EKF keeps the robot pose, both position and heading, accurate across long missions; three controller-aware refinements are added to a mature coverage planner; a Behavior-Tree mission manager coordinates multi-goal execution, layered recovery, cost-aware goal management, and autonomous docking for return-to-charge. We validate the stack through simulation and real-world trials across multiple outdoor areas with varying geometries and obstacle densities. Overall, these results show that the proposed stack can reliably complete outdoor coverage missions across varied areas, sweeping 93.1% to 96.1% of the planned coverage area.
### Title:
          Vision-Based Leader-Follower Formation Control for Cooperative UAVs in GPS-Degraded Environments
 - **Authors:** Deekshitha Angadi, Naveena Budda, Vikas Agarwal, Rojesh Arunkumar Mulasa, Ravi Killamsetty, Mohamed Samshad, Narsimlu Kemsaram
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cooperation in multi-UAV systems requires reliable relative perception so that follower vehicles can maintain formation and continue their mission safely even when absolute positioning sensors degrade or fail. This paper presents a vision-based cooperative formation framework running on a follower UAV that uses a front-facing RGB-D camera to detect, track, and localize a leader UAV in real-time. A lightweight YOLO-based detector is trained on a dedicated drone dataset and deployed onboard to predict leader bounding boxes, which are then fused with depth information via a pinhole camera model to estimate the leader's relative pose. These estimates provide a leader-follower position controller and can also be used as a backup when GPS or external localization is unavailable. This framework is implemented as a set of ROS nodes and evaluated in a physics-based multi-UAV simulation built on XTDrone, with sensor noise and communication dropouts. We evaluate detection accuracy, runtime, and formation-keeping error under nominal conditions and under simulated failures of the positioning sensors. The results show that the proposed framework maintains stable leader-follower formations with reasonable computational cost and provides a practical basis for extending vision-based cooperative formation control to real-world multi-UAV systems.
### Title:
          Cross-Modal Guidance for Out-of-View Object Search in Simulated Prosthetic Vision
 - **Authors:** Adyah Rastogi, Apurv Varshney, Tobias Höllerer, Michael Beyeler
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Out-of-view guidance is well established in virtual and augmented reality, but its effectiveness may depend on the visual bandwidth available to the user. We test this under simulated prosthetic vision (SPV), where visual guidance must share the same sparse representation used to inspect the scene. Nineteen participants performed object search under two SPV conditions differing in electrode density and phosphene spread (10x10 and 20x20) and four guidance conditions (no guidance, visual, haptic, audio) all driven by the same horizontal target-offset variable. All three modalities reduced search time and head movement. The tested auditory and haptic cues produced approximately 25% faster overall search and 11-13% faster target acquisition than the visual cue, despite similarly direct orienting trajectories. The tested haptic and auditory cues also shortened post-acquisition search. Final head-target angular offset was reduced substantially more in the 10x10 SPV condition; there, all three cues also reduced vertical localization error by approximately 45-58% despite providing no elevation information. Under severe visual constraints, guidance performance depended on cue implementation and search stage.
## Keyword: transformer
### Title:
          Good Memory Has ECC: Evaluating the Memory of Vision-Language Models Beyond Accuracy
 - **Authors:** Shmuel Berman, Jia Deng
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Memory is widely viewed as an important unsolved problem for LLMs and VLMs, and current benchmarks typically evaluate it by testing accuracy over long text or video. However, accuracy alone misses properties that matter for real long-horizon tasks. We introduce ECCBench, a benchmark and evaluation protocol that measures memory beyond a system's capacity--its raw accuracy at a specific budget--via three axes we call ECC: efficiency--the computation, in FLOPs, needed to answer from memory; compression--whether compressible inputs are remembered more accurately or efficiently; and calibration--whether the system abstains in response to its own uncertainty and the cost of an error. We find that pretrained VLMs compress their memory over text but not video and are poorly calibrated on both. Among a broader set of memory backbones, several non-Transformer architectures achieve better compression-calibration tradeoffs than RoPE Transformers, suggesting they may be useful components for agents operating over long horizons.
### Title:
          Assessing Suicide Risk in Arabic Crisis Helpline Calls: A Comparison of Arabic and English Large Language Models
 - **Authors:** Linhai Ma, Rita El Hachem, Mahatab El Hajj, Lilian Ghandour, Samah Fodeh
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Crisis helplines assess suicide risk through structured interviews, a process that is slow and dependent on operator training and workload. Natural language processing could support risk assessment and call prioritization, but almost no work addresses Arabic-language helpline calls or operates within the privacy constraints of real helpline data. We analysed de-identified transcripts from Lebanon's National Lifeline for Emotional Support and Suicide Prevention. Audio never left the helpline: calls were transcribed on site with a speech recognition model for Levantine Arabic, and an Arabic named-entity recognition model removed identifying information locally. Only the de-identified transcripts were shared with the research team. Operators recorded the five suicidal ideation items of the Columbia Suicide Severity Rating Scale, which we combined into two binary outcomes: at-risk and high-risk. We also machine-translated the transcripts into English, giving a paired Arabic/English comparison. On each corpus, we fine-tuned five instruction-tuned large language models alongside six transformer encoder baselines (four Arabic, two English) and evaluated all models on a held-out test set. We included 383 calls: 373 for the at-risk task (52.3% positive) and 297 for the high-risk task (30.0% positive). The best Arabic model reached a macro-F1 of 81.19 and a ROC-AUC of 90.61 on high-risk; the best English model reached 85.00 and 92.59, identifying 88.9% of high-risk calls. In both languages, high-risk calls separated more cleanly than at-risk calls, and translation to English did not reduce the best observed performance. Suicide risk can be classified from de-identified Arabic transcripts without sending audio outside the helpline. The high-risk results support further testing as an operator-facing tool; lower-severity ideation proved the harder case.
### Title:
          WiSDoM: Wireless Sparse Decision Transformer with Mixture-of-Experts for Multi-Task Mobile Network Optimization
 - **Authors:** Fatih Temiz, Shavbo Salehi, Melike Erol-Kantarci
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Emerging 6G wireless networks are expected to operate across diverse deployment scenarios, where variations in network topology, user mobility, traffic demand, and radio conditions challenge the scalability of conventional radio resource management (RRM). While offline reinforcement learning (RL) methods have demonstrated strong decision-making capabilities, learning a single policy that performs consistently across heterogeneous wireless environments remains difficult due to conflicting optimization objectives and limited model specialization. These challenges become particularly pronounced in coordinated multipoint (CoMP) transmission, where selecting the optimal serving-cell combination requires sequential decision-making under evolving network conditions. This paper presents the Wireless Sparse Decision Transformer with Mixture of Experts (WiSDoM), a sparse multi-task offline RL framework for adaptive multi-cell selection. WiSDoM combines Decision Transformers (DTs) with a Mixture-of-Experts (MoE) architecture that dynamically activates specialized experts according to task characteristics. This MoE mechanism improves model capacity without proportionally increasing inference cost, mitigates negative transfer, and enables expert specialization across tasks. WiSDoM is trained jointly on diverse network configurations spanning multiple base station and user equipment densities, mobility levels, and scheduler policies. Experimental results show that WiSDoM consistently outperforms heuristic methods, single-task models, and conventional multi-task DTs, improving quality of experience (QoE) by up to 55% while activating approximately one-third of the parameters of its dense counterpart during inference. Furthermore, WiSDoM exhibits strong task generalization and efficiently adapts to unseen wireless scenarios through few-shot prompting without retraining or fine-tuning.
### Title:
          Geometry-aware Latent Autoregressive Generative Model for PDEs in Complex Domains
 - **Authors:** Zi Wang, Minghui Xu, Tapan Mukerji
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Solving multiphysics partial differential equations (PDEs) remains a major challenge in scientific computing, especially for highly complex $\mu$m-scale tortuous geometries critical to energy and chemical engineering. We address this challenge by proposing a Geometry-aware Latent Autoregressive generative Model for PDEs (GeoLAMP) for solving physics within highly irregular and tortuous structures. GeoLAMP introduces a dual-encoder architecture on graph representations to jointly capture global topology and fine-scale geometric features, enabling an effective transition from real-space fields to compact latent representations. In the latent space, we propose a causal self-attention transformer with flow matching to model temporal dynamics, allowing stable and scalable block-wise autoregressive prediction. A flexible decoder reconstructs high-resolution physical fields on arbitrary points. We establish three multiphysics benchmark datasets in complex geometries, covering reactive flow, heat convection, and elasticity. GeoLAMP consistently achieves the most stable autoregression performance on these datasets, maintaining low errors throughout the entire rollout horizon. Our results provide a systematic study of geometry-aware learning for PDEs in $\mu$m-scale complex geometries and offer new insights into block-wise time marching of latent autoregressive PDE modeling via a flow matching framework.
### Title:
          Where Should Experience Live? Hierarchical Hebbian Memory for Continual Vision Transformers
 - **Authors:** Mohammed Yusuf Mujawar, Noorbakhsh Amiri Golilarz
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformers provide strong visual representations but typically rely on slowly updated parameters, limiting their ability to organize newly acquired information across different memory timescales. This work proposes \textit{Hierarchical Hebbian Memory}, a three-level memory architecture composed of rapid Working Memory, persistent Routed Episodic Memory, and slower Semantic Memory. A learned controller regulates memory contribution, read and write routing, plasticity, retention, and consolidation. A causal read-before-write lifecycle ensures that the current outcome cannot influence the prediction it supervises. The architecture is evaluated on Omniglot 5-way 1-shot recognition and CORe50 continual object recognition. With Swin-Tiny, the hierarchical model reaches 97.39\% accuracy on Omniglot and 95.37\% final accuracy on CORe50 when combined with experience replay. Learned multi-bank retrieval reaches 47.50\% delayed-association accuracy, compared with 24.17\% for a single persistent bank and 25.00\% without memory. After intervening distractors, Episodic Memory retains approximately 0.96 cosine similarity with stored associations, while Working Memory falls to approximately 0.05. These results show that Hebbian association and learned memory routing can jointly organize online visual experience across rapid, persistent, and consolidated memory timescales within Vision Transformers.
### Title:
          Detoxifying Toxic Communication: A Design Science Approach to Responsible AI
 - **Authors:** Hossein Arshadi Soufiani, Henry M. Kim, Hjalmar Turesson, Syed Mohammad Arham Noman, Anav Setia
 - **Subjects:** Subjects:
Computers and Society (cs.CY); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Toxic language in digital workplaces such as pejoratives, sarcasm, condescension, and subtle incivility can erode trust, morale, and collaboration. Existing moderation tools primarily delete or block harmful messages, disrupting communication and offering no constructive resolution. This study adopts a Design Science Research approach to create a responsible AI artifact that detects and detoxifies toxic communication. The artifact integrates fine-tuned transformer-based classifiers (DistilBERT, DistilRoBERTa) with a generative detoxification model (mT0-XL-Detox-ORPO) that rewrites toxic text into semantically equivalent, non-offensive paraphrases. Technical evaluation demonstrates high accuracy in toxicity detection and strong semantic preservation in rewritten messages, supporting conversation continuity while reinforcing respectful discourse. The paper contributes design principles for responsible AI moderation that prioritize meaning preservation and fairness.
### Title:
          Neurosymbolics for Data Engineering: Achieving Long Context Token Reduction Without Finetuning
 - **Authors:** Vishvesh Bhat
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models are increasingly deployed for sophisticated data engineering tasks such as generating structured queries from natural language, Text-to-SQL, and automating complex spreadsheet operations. However, maximizing their utility demands both higher finetuning-free accuracy and solutions to the computational bottleneck imposed by the Transformer architectures inherent quadratic (On2) time complexity. This paper introduces a novel drop-in neurosymbolic layer designed to seamlessly integrate into existing LLM backbones enhancing logical reasoning and mitigating long-context resource consumption. On the reasoning front, the layer immediately and significantly improves performance yielding an average accuracy increase of 85% across rigorous benchmarks including BIRD-CRITIC and LiveSQLBench, critically achieving these gains without any task specific finetuning or RLHF. Concurrently, we repurpose this approach to address the severe computational strain of long context inference. By leveraging symbolic processing to prioritize and compress relevant contextual information the layer reduces the effective token usage by over 50% and brings the effective time complexity down from O(n2) to approximately O(n) on certain long context tasks. This dual impact approach not only makes LLMs substantially more reliable for data engineering but also drastically reduces the computational pressure on inference chips, making long context tasks more manageable and cost effective.
### Title:
          Removable and Irreducible: A Token-Cost Ledger for the Multilingual Tokenization Tax
 - **Authors:** Madhulatha Mandarapu, Sandeep Kunkunuru
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models pay a well-documented tax on non-English text: the same content costs several times more tokens, and because attention is quadratic in sequence length, far more compute. We ask how much of this tax is removable. Framing the token layer as source coding -- transformer compute is monotone in sequence length, whose per-atom floor is the Shannon rate $H/\log_2 V$, an object already applied to tokenizers in prior work -- we assemble a token-cost ledger that splits each language's cost, at fixed parallel content, into a removable coding redundancy, a residual coding slack, an intrinsic-content term, and an orthogonal, irreducible grapheme-to-phoneme term that governs the multimodal rather than the text cost. On FLORES-200 across eight languages, a production tokenizer costs up to $8.9\times$ more tokens for Indic scripts than for English; a script-matched code trained on $1,012$ sentences removes a median $64\%$ of that excess (bootstrap 95\% CI $[0.638, 0.647]$), and a script-fair information floor shows the intrinsic content differs by under $6\%$ -- the tax is representational, not informational. A constructed code removes $98\%$ of a controlled source's redundancy, and the token tax implies up to $79\times$ attention cost. We are explicit about scope and failure: this is compute-and-memory accounting, not a model-quality claim; we neither measure nor claim the cross-lingual direction of the orthographic term; and our matched code is a conservative small-data demonstration. We contribute the unifying ledger, the removable-versus-intrinsic attribution, and an open one-command harness.
### Title:
          A Multi-Branch Feature Fusion Approach for Health Misinformation Detection and Propagation
 - **Authors:** Mkululi Sikosana, Sean Maudsley-Barton, Oluwaseun Ajao
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Social and Information Networks (cs.SI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a multi-branch fusion framework for detecting and characterising the propagation of health misinformation in online social networks (OSNs). Grounded in the Elaboration Likelihood Model (ELM) and the Theory of Planned Behaviour (TPB), the model fuses transformer-based semantics with rhetorical cues, stance representations, and psychologically motivated proxies in a unified multi-task architecture. In addition to binary classification, we introduce the Cognitive Propagation Score (CPS), an interpretable post-hoc auxiliary score computed from psychologically motivated, text-derived cues capturing argument complexity, emotional intensity, and content-derived virality potential, to support diffusion-risk reasoning when engagement ground truth is incomplete or unavailable. Experiments on three benchmark datasets, Constraint, COVID--19\_FNIR, and Monkeypox, show strong classification performance, achieving ROC--AUC up to 0.9999 on COVID--19\_FNIR, while propagation-oriented ranking achieves near-perfect agreement when engagement-derived supervision is available (Monkeypox, Spearman's $\rho = 0.9952$) and similarly high ranking alignment under proxy-based supervision on COVID--19\_FNIR ($\rho = 0.9954$). Compared with representative literature baselines, the fusion model improves detection on Constraint and COVID--19\_FNIR, while Monkeypox remains more challenging, reflecting domain- and signal-specific differences. Ablation analysis further indicates that psychological and rhetorical branches provide complementary gains beyond semantic embeddings. Overall, the framework bridges cognitive theory and neural modelling to improve transparency and to support scalable misinformation monitoring, with future work required to validate CPS against human-centred diffusion judgements.
### Title:
          Late Transformer Layers Recode Syntax Canonically: Evidence from Greek Scrambling and Cross-Layer Generalisation
 - **Authors:** Christos Nikolaos Zacharopoulos, Revekka Kyriakoglou, Chara Tsoukala, Théo Desbordes
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Probing studies have established that syntactic information is decodable in early and middle transformer layers, but what happens to that information in later layers remains poorly understood. We apply a cross-layer generalisation analysis to three Greek-tuned large language models evaluated on tightly controlled minimal pairs: object-relative constructions in Modern Greek, where canonical (Subject-Verb-Object; SVO) and non-canonical (Verb-Subject-Object; VSO) orders differ only in within-clause word order, while preserving propositional meaning. When a probe trained on late layers (20-31) is tested on each early layer individually, it produces below-chance transfer (cluster-corrected, p<0.01), classifying 99.3% of non-canonical sentences as canonical. Probe coefficients reverse sign around layer 22, indicating a directional recoding toward the canonical form rather than simple information loss. These findings characterise a representational format change in late transformer layers that goes beyond the well-established decline in syntactic decodability, and they generate a directly testable prediction for human EEG and MEG decoding studies using the same stimuli. Code and stimuli are publicly available on OSF.
### Title:
          Location-Aware Language Models via Secondary Embeddings
 - **Authors:** Gokul Srinivasagan, Munir Georges
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pretrained transformer-based language models achieve strong performance across a wide range of NLP tasks but remain limited in encoding geo-locational semantics, leading to suboptimal representations of place names and spatial entities. In this work, we propose a lightweight, model-agnostic approach for injecting geo-spatial awareness into pretrained embeddings without modifying the tokenizer or requiring costly retraining. Our method augments input representations with structured geographic signals by combining location names with their corresponding latitude and longitude, and employs a location-focused masking to better align textual representations with real-world spatial relationships. This design allows the model to incorporate geo-spatial context while preserving existing semantic and syntactic knowledge. Experimental results demonstrate substantial improvements in geo-spatial alignment while maintaining comparable performance on standard NLP benchmarks such as GLUE. The method is computationally efficient, requiring only minutes of additional training, and generalizes across multiple model architectures and scales.
### Title:
          Can LLMs Use Relational Transformer Embeddings?
 - **Authors:** Francisco Galuppo Azevedo, Clarissa Lima Loures
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Injecting frozen relational-encoder embeddings as soft tokens into a large language model (LLM) is a conceptually appealing fusion strategy: the encoder handles multi-table structure, the LLM handles language and reasoning, and no lossy text serialization is required. We test this hypothesis concretely by injecting embeddings from a frozen Relational Transformer (RT) into Qwen3.5-4B via a learned MLP projection and LoRA adaptation, trained first with supervised fine-tuning (SFT) on chain-of-thought reasoning traces and then with group-based reinforcement learning (GSPO). We evaluate across 10 binary classification tasks on 6 relational databases from RelBench, under four supervision regimes: single-task (ST), within-dataset (WD), cross-dataset (CD), and all-task (ALL). The hybrid model does not consistently outperform standalone RT: it is frequently below random, highly sensitive to serialization format and relational-token budget, and unstable under RL training. We report these negative results and analyze the failure modes, arguing that soft-token fusion requires stronger alignment objectives and schema-aware design before it can serve as a reliable route to relational prediction.
### Title:
          Toppling the Hierarchy in Byte-level Language Modeling
 - **Authors:** Lukas Edman, Alexander Fraser
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work examines recent byte-level models and their failure to perfectly manipulate characters. State-of-the-art byte-level models use a hierarchical structure, starting at the byte level, downsampling to the word level, and then upsampling back to bytes. While this improves training and inference efficiency, we find that the hierarchical design itself limits character-level understanding, with pure byte-level models consistently outperforming hierarchical variants on character manipulation tasks. Ablating transformer layers into attention and feed-forward components further reveals that byte-level attention is the primary mechanism driving this behavior. Together, our results provide an explanation for the character-level failures of hierarchical byte models and establish a clear trade-off between computational efficiency and fine-grained character understanding.
### Title:
          VATO: A Vortex-Force-Aware Transformer Operator for Unsteady Separated Aerofoil Flows
 - **Authors:** Xingxin Yang, Zhan Zhang, Yichen Li, Juan Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate prediction of unsteady separated flows is challenging because the aerodynamic loads depend on nonlinear separation and vortex-shedding dynamics. Although high-fidelity CFD resolves these mechanisms, its cost limits repeated use in design and control. Standard field-level surrogate training, however, does not distinguish the flow regions that contribute most strongly to the aerodynamic loads. We introduce VATO (Vortex-Force-Aware Transformer Operator), which couples the Vortex Force Map (VFM) method to a geometry-aware neural operator through two complementary mechanisms. VATO-S adds training-only supervision of the local VFM force-contribution field, with no increase in model size or inference cost. VATO-A uses VFM contribution and sensitivity fields to prioritise force-relevant source locations for residual cross attention. The methods are evaluated on unsteady CFD data for double-edged-plate aerofoils over 54 trajectories from nine geometries. Over lead times of 1-20~ms, VATO-S reduces velocity, pressure, and vorticity errors by 10.4\%, 1.0\%, and 15.6\%, respectively, while VATO-A achieves reductions of 15.8\%, 7.5\%, and 31.2\%. VATO-S gives the lowest VFM-derived drag error, whereas VATO-A gives the lowest pressure-derived lift and drag errors. Over lead times extending 50\% beyond the training range, VATO-A retains a 26.9\% reduction in vorticity error and larger improvements in all four force readouts, despite reduced gains in velocity and pressure. These results show that force-aware operator learning can improve both flow-field prediction and aerodynamic functional accuracy in unsteady separated flows.
### Title:
          TUTTI: Toward generalizable audio-to-score transcription via fully synthesized data
 - **Authors:** Jianhuai Hu, Yashan Wang, Shangda Wu, Zhancheng Guo, Shijie Liang, Wuna Meng, Chuanqi Yang, Xiaobing Li, Feng Yu, Maosong Sun
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generalizable Audio-to-Score (A2S) transcription is fundamentally constrained by the severe scarcity of high-quality, real-world paired data. Relying solely on existing human-annotated datasets often restricts the generalization of A2S models, limiting their efficacy primarily to single-instrumentation domains. To break this dependency on scarce real-world data, we introduce TUTTI (Transformer for Unified audio-To-score Transcription trained on Synthetic multi-Instrumentation Data), a pre-training paradigm driven by a purely synthetic, large-scale dataset. Rather than using human-composed scores, we leverage a symbolic music generation model to generate a massive, highly scalable multi-instrumentation corpus and create audio-score pairs with expressive acoustic characteristics. Capitalizing on the generated data, we employ a standard Transformer encoder-decoder architecture. We empirically demonstrate that pre-training a unified attention-based model on generated, multi-instrumentation data yields a consistently stronger foundational representation than single-instrumentation training. When fine-tuned with downstream real-world datasets, TUTTI outperforms previous approaches, establishing new overall state-of-the-art results across various A2S baselines. Notably, TUTTI shows remarkable cross-instrument transferability, effectively adapting to unseen instruments with highly competitive performance. The source code and the TuttiCorpus dataset will be made publicly available at this https URL.
### Title:
          MaskCode: Mask Transformer for Feedback-Assisted Coding With Linear Block Codes
 - **Authors:** Jonggyu Jang, Hongjae Nam, Vishrant Tripathi, David J. Love, Hyun Jong Yang
 - **Subjects:** Subjects:
Information Theory (cs.IT); Machine Learning (cs.LG); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Feedback-based coding schemes have demonstrated substantial performance gains over today's open-loop coding schemes. Unfortunately, these gains are usually achieved in idealized settings with perfect feedback. Over the last few years, machine learning-based schemes have been shown to be promising solutions for implementing feedback-based codes, particularly when combined with short-block-length open-loop error correcting codes (ECCs) in a concatenated coding structure. However, existing ML-based feedback schemes remain agnostic to the outer code's structure, potentially misallocating feedback resources on error patterns already correctable by the outer ECC. To address this, we propose MaskCode, a Transformer-based inner feedback code for concatenated coding systems, which explicitly incorporates structural knowledge of the outer linear block code into the inner feedback encoder design via two synergistic mechanisms: 1) a soft syndrome-based input that informs the encoder about potential parity constraint violations, and 2) a code-aware attention mask derived from the Tanner graph. We further show that end-to-end training with a differentiable belief propagation (BP) decoder offers no additional gain, as MaskCode's structure-aware design already internalizes the structural knowledge of the outer code; in fact, backpropagation through the iterative BP decoder introduces gradient explosion, which degrades rather than improves performance. Extensive evaluations on BCH and LDPC outer codes demonstrate that MaskCode consistently outperforms all baselines, achieving up to 1.5 dB SNR gain.
### Title:
          Measuring Optimal Transport in Transformer Depth
 - **Authors:** Alexandre Quemy
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A transformer carries each token's state from layer to layer, and the whole vocabulary carried together forms a cloud that moves with depth. We ask whether a trained network moves this cloud the way optimal transport would: at the cheapest cost, and along the map that pairs each token with its optimal destination. We measure both on Pythia-160m and Pythia-410m, with an exact assignment between consecutive layer clouds, a measured sampling floor, calibration on couplings known to be optimal, and a split of the cost into the common shift of the cloud and the token-specific moves. At the last layer, both models move their tokens where the optimal-transport map sends them, at the optimal cost for Pythia-410m and slightly above it for Pythia-160m. At the first layer they do not. In between, single layers can be judged on cost at only two of ten transitions, and blocks of several layers move the cloud at close to the optimal cost. The agreement at the last layer is much weaker at initialisation (0.64 against 0.86) and grows with training.
### Title:
          Benchmarking Vision-Language Models for Automated Pathology Diagnosis and Report Generation
 - **Authors:** Yumi Lee, Harim Oh, Hyoryung Kim, Minji Kim, Eunsu Kim, Hyeseong Lee, Junya Fukuoka, Andrey Bychkov, Jijgee Munkhdelger, Rajiv Kumar Kaushal, Ayushi Sahay, Rajni Yadav, Bharathi Prabakaran, Sulen Sarioglu, Serdar Balcı, Ilknur Turkmen, Yuri Tolkach, Christian Harder, Julian Westerdorf, Reinhard Buettner, Audun Ljone Henriksen, Sepp De Raedt, Byung Hyun Lee, Sungjin Lim, Joohoon Lee, Gwanghyun Kim, Se Young Chun, Suryakant Singh, Saarthak Kapse, Prateek Prasanna, Kyung A Kim, Yousun Kang, Sehwan Yoo, Sungman Hong, Shubham Innani, Michael Feldman, Spyridon Bakas, Ujjwal Baid, Prasad Dutande, Suhas Gajare, Bhakti Baheti, Serkan Sökmen, Ece Tuğba Cebeci, Ahmet Halıcı, Musa Balcı, Kardelen Peçenek, Srividhya Sainath, Kyongseok Jang, Messi H.J. Lee, Noorul Wahab, Bodong Du, Jiaming Zhang, Qixiang Zhang, Jang-Hwan Choi, Sangjeong Ahn
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid advancement of vision-language models (VLMs) has accelerated progress in computational pathology; however, whole-slide image (WSI)-based pathology report generation remains limited by the scarcity of large-scale WSI--report datasets and the complexity of mapping spatially distributed visual patterns to structured clinical text. To address this, we introduce a clinically curated Pan-Asia WSI--report dataset of approximately 10,500 pairs from five institutions and establish the REG 2025 benchmark through a MICCAI challenge for systematic evaluation of multimodal models. We analyze submitted methods spanning pretrained VLMs, multiple-instance learning frameworks, hierarchical expert models, retrieval-augmented generation, and cross-modal Transformers. Rather than indicating that VLM use alone was sufficient for superior performance, the results suggest that top-performing methods benefited from structured report representations, hierarchical diagnostic decomposition, and effective multimodal grounding. We identify key limitations, including instability in quantitative attribute estimation (e.g., numeric hallucination) and a tendency toward diagnostic overspecification, with some errors resembling known diagnostic pitfalls in routine pathology. These findings establish REG 2025 as a benchmark for evaluating WSI-based structured report generation and vision-language understanding in computational pathology, providing insights for the design of clinically grounded multimodal pathology models.
### Title:
          iPINN for Broadband CARS Phase Retrieval: A Framework for Function Approximation and Inverse Modeling Problems in Nonlinear Spectroscopy
 - **Authors:** Ravi Teja Vulchi, Carl Messerschmidt, Mohammadsadegh Vafaeinezhad, Rajendhar Junjuri, Tobias Meyer-Zedler, Juergen Popp, Thomas Bocklitz
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Data Analysis, Statistics and Probability (physics.data-an)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Phase retrieval in broadband coherent anti-Stokes Raman spectroscopy (BCARS) is an ill-posed inverse problem. The Raman-like signal is encoded in the imaginary part of the resonant susceptibility, which mixes coherently with a non-resonant background (NRB) that varies across acquisitions. We introduce an inverse physics-informed neural network (iPINN) that predicts Lorentzian peak parameters from raw BCARS spectra and reconstructs the resonant susceptibility through a differentiable analytical forward model. A transformer encoder assigns spectral features to 24 learnable peak slots, and a multi-view consistency loss enforces invariance across NRB pattern, NRB strength, and noise. Unlike direct spectral regression approaches, the method retains accuracy under varying acquisition conditions. On a public benchmark, iPINN achieves the lowest error among the tested baselines (MAE 0.016 vs. next-best 0.046). On 28 zero-shot test spectra acquired across seven solvents and four focal positions, accuracy is depth-invariant in five of seven solvents. These results show that inverse parametric prediction with a differentiable physical decoder supports robust phase retrieval across measurement conditions.
### Title:
          Denoising Diffusion Generative Models Secretly Calculate Attentions
 - **Authors:** Farzan Haddadi, Leila Monfared, Ebrahim Rezaii, Mohammadreza Malek-Mohammadi, Pejman Zakalvand, Narges Mokhtari
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Denoising diffusion models are the dominant architecture for image generation, whereas most natural language generation and modeling are primarily handled by well-known transformer architectures employing attention mechanism. Here, we show that diffusion models also inherently use an attention mechanism very similar to that of transformers. Therefore, attention emerges as a universal machine learning principle, based on a general training objective. We also show similarities in basic functional principle of auto-encoders and attention-based models. These equivalences allows us to interchange these designs based on practical requirements. As an example, we can reformulate the diffusion framework to reduce the lengthy training process and computation-intensive image generation. Using this approach, a simplified algorithm is proposed for image generation which is based on attention mechanism. Results show that the attention-based implementation achieves comparable performance with significantly less effort and computational resources.
### Title:
          On-the-Fly3R: Towards Robust Online 3D Reconstruction with Feed-Forward 3R Models for Large-Scale UAV Scenarios
 - **Authors:** Zhe Shen, Liyuan Lou, Yifei Yu, Guanbo Wang, Quanjian Ji, Xin Wang, Zongqian Zhan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While feed-forward 3D reconstruction (3R) offers efficient end-to-end modeling, its application in large-scale UAV mapping is hindered by the prohibitive memory cost of Transformer attention. Current scalable streaming 3R methods assume temporally and spatially continuous inputs, rendering them ineffective for the weakly ordered or unordered image streams common in cross-strip UAV operations. To address this, we propose On-the-Fly3R, a training-free, progressive online 3D reconstruction framework for large-scale UAV images that upgrades various 3R backbones for large-scale UAV scenarios. Our method enables reconstruction from unordered inputs via retrieval-guided dynamic subset construction, which adaptively selects spatially relevant images. To further improve the robustness, a validation-rejection-retry mechanism is designed to guarantee global consistency, performing a pre-integration consistency check and automatically rejecting misaligned images and retrying with alternative subset. Finally, inspired by VSLAM, pose graph optimization based on the retrieval loop closure is employed to mitigate camera drift. Evaluations on several UAV benchmarks show that our On-the-Fly3R successfully scales various 3R models to over 5,000 images across square-kilometer UAV scenes, delivering substantially superior accuracy compared to several SOTA streaming 3R methods. Code is available at this https URL
### Title:
          TGR: Advancing Industrial Recommendation from Generative-Paradigm Ranking toward Unified Generation and Reasoning
 - **Authors:** TGR Team: Lei Cheng, Haonan Hu, Beibei Kong, Yudong Li, Zang Li, Yunsheng Pang, Hongyang Su, Jianchao Tu, Yunlong Wang, Bing Wen, Junzhang Zhu, Shaojie Zhu, Chengxiang Zhuo
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Industrial recommender systems typically rely on cascaded retrieval, pre-ranking, ranking, and reranking stages, whose separately optimized models limit scaling, fragment decision making, and lack semantic knowledge and reasoning. We present TGR (Tencent Generative Recommendation), an industrial framework that advances recommendation toward the generative paradigm along three coupled directions. TGR-GenRank upgrades ranking through CCFormer, which combines unified feature tokenization, a scalable Transformer backbone, feature-field separated cross attention, subspace token mixing, and hierarchical sequence compression while retaining per-item multi-task outputs. TGR-GenRec explores end-to-end generation under two paradigms: BARGE bridges item-boundary loss and semantic drift in hierarchical semantic-ID generation through item context-aware attention, hierarchical path reranking, and orthogonal dual-path decoding; HiGR performs whole-slate generation with prefix-structured semantic IDs, coarse-to-fine decoding, and listwise multi-objective alignment. TGR-Reason injects offline-generated semantic-ID reason tokens into online decoding, providing reasoning without request-time rollout. TGR is deployed across Tencent production surfaces serving hundreds of millions of users. CCFormer delivers significant gains in five A/B-tested scenarios and is fully launched in two, including +3.57% CTR and +1.71% advertising revenue. BARGE improves Hit@5 by 10.2-16.9% and yields +0.60% CTR and +1.70% reading time after full rollout. HiGR improves offline slate quality by 15.9-21.3% with a 5x inference speedup and achieves up to +1.22% watch time and +1.73% video views. TGR-Reason raises cold-start new-user Hit@1 by 477.8% and delivers +1.75% effective consumption and +13.09% new-user exposure-to-conversion online.
### Title:
          Low-Quality Face Recognition using Center Aligned Representations and Local Margin Constraints
 - **Authors:** Vedat Can Dilaver, Benjamin S. Riggan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Low-quality face recognition (LQFR) remains challenging due to the difficulty of matching degraded query (probe) images against low-quality (LQ) enrollment (gallery) imagery and the scarcity of training data for large-scale models. While recent face recognition (FR) models perform well on high-quality (HQ) imagery, their accuracy drops significantly on LQ images with extremely low signal-to-noise ratio (SNR). Moreover, fine-tuning HQ-pretrained models on LQ data often improves LQ recognition at the expense of HQ generalization. This trade-off becomes more pronounced in modern evaluation settings spanning multiple datasets with varying image quality levels. To address these limitations, we propose a unified framework that combines three main components: (1) Local Probability Margin (LPM), which estimates per-sample difficulty directly from the model's discriminative landscape; (2) Nested Attention Module (NAM), a new low-rank adapter module that embeds a self-attention mechanism within selected transformer layers; and (3) Quality Gating Protocol (QGP), where an off-the-shelf image quality estimator modulates the adapter contribution at test time, enabling a single model to handle the full quality spectrum without sacrificing HQ performance. Experiments on surveillance (TinyFace, SurvFace) and standard (IJB-B, IJB-C) face recognition benchmarks demonstrate consistent gains in both identification and verification. Code and models will be released at this http URL.
### Title:
          ViTAMINS: An Empirical Study of Training Self-Supervised Vision Transformers with Synthetic Hard Negatives
 - **Authors:** Nikos Giakoumoglou, Andreas Floros, Kleanthis-Marios Papadopoulos, Tania Stathaki
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce ViTAMINS, a method that integrates synthetic hard negatives into unsupervised vision transformer pretraining to improve representation quality. Our approach is thoroughly benchmarked on ImageNet and transfer learning, image retrieval, copy detection, and image, video segmentation tasks. Notably, our proposed negatives give rise to emergent properties, where learned representations contain explicit information about the semantic content of an image and serve as excellent classifiers (up to +11.3% over baselines). ViTAMINS achieves these benefits through simple modifications to existing contrastive frameworks and outperforms competing methods while being more resource efficient, e.g., our ViT-B surpasses V-JEPA with ViT-L. Our findings motivate reconsidering contrastive learning as a simpler yet powerful alternative to dominant generative and self-distillation approaches.
### Title:
          Scaled Idempotence in Transformer Attention: Paired OV Geometry and Shared-Value Algebras
 - **Authors:** Jiming Feng, Junliang Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We identify a recurrent algebraic regularity in Transformer attention: a sparse subset of effective OV operators $T=OV^\top$ nearly closes under composition, $T^2\approx\alpha T$. Across six pretrained endpoints spanning 2.8B--235B parameters, 3.98--8.00% of heads reach squared closure alignment $\mathcal{P}\geq0.9$, while no matched within-layer O/V mismatch does. An exact principal-coordinate factorization, $T=Q_OKQ_V^\top$ and $T^2=Q_O(KDK)Q_V^\top$, separates within-support transport from read--write return geometry. Across all 7,304 heads in nine MHA/GQA models, scrambling only the orientation of $K$ while preserving singular values, norms, factor spans, and principal angles reduces median closure from 0.336 to $1.04\times10^{-4}$; trained orientation wins for 98.64% of heads and in every layer. Constructive searches show that high closure is feasible in every surveyed layer, but usually not attained. Retrospective trajectories in three independently trained lineages further separate broadly available capacity from the orientations attained by final strong heads. Under exact value sharing, headwise closure extends to a right-action algebra, $T_iT_j=\alpha_jT_i$. Seven-model experiments verify the approximate law and reveal distinct oblique projections with a shared value-defined kernel. These results characterize scaled idempotence as a sparse trained orientation within broadly available geometric capacity and show how value sharing extends a headwise relation into a local operator algebra.
### Title:
          Births are difficult to predict even with rich survey and full-population register data
 - **Authors:** Elizaveta Sivak, Emily M. Cantrell, Thomas Emery, Javier Garcia-Bernardo, Flavio Hafner, Kasia Karpinska, Malte Lüken, Adrienne Mendrik, Joris Mulder, Hanzhang Ren, Varun Satish, Mark Verhagen, Angelica M. Maineri, Paulina Pankowska, Jasmin Abdel Ghany, Bruno Arpino, Giovanni Cassani, Julia Hellstrand, Katya Ivanova, Sanni Kuikka, Ana Macanovic, Charles Rahal, Felix C. Tropf, Roland J. Veen, Nicole Walasek, Daniël van Wijk, Kelsey Q. Wright, Emilio Zagheni, Henry Abbink, Emanuele Aliverti, Matteo Amestoy, Tilbe Atav, Nicola Barban, Sunnee Billingsley, Goan J. Booij, Louis Boucherie, Yael Broos, Li Ya Chang, Jamie C. Chiu, Chiara Ludovica Comolli, Boris Cule, Qixiang Fang, Dennis M. Feehan, Rachel Ganly, Erwin Gielens, Rolando M. Gonzales Martinez, Andrea Gradassi, Rosember Guerra-Urzola, Mario Guerra-Urzola, Stéphane Guerrier, Enamul Hassan, Vincent A. Haverhoek, Andrew T. Hendrickson, Amber Howard, Yuxuan Jin, Sayash Kapoor, Erik-Jan van Kesteren, Iris ten Klooster, Marie Labussiere, Lydia T. Liu, Tiffany Liu, Adam Maghout, Simone Meneghello, Lasse Mohr, Clara H. Mulder, Saul J. Newman, Jessica Nisén, Janis Norden, Mikkel Odgaard, Riccardo Omenti, Ozancan Ozdemir, Christina Pao, Paige Park, Gaia Penta, Juan C. Perdomo, Tanzir Pial, Alessio Piraccini, Federica Querin, Ziwei Rao, Christian Rellama, Adrien Remund, Frederieke Richert, Arnout van de Rijt, Mojtaba Rostami Kandroodi, Stijn J. Rotman, Lucas Sage, Germans Savcisens, Katrin Schwanitz, Steven Skiena, Alessandro Spata, Yannick Stadtfeld, Benedikt Stroebl, Gaetano Tedesco, Mathilde Theelen, Gianluca Tori, Abigail Tun-Mendicuti, Rishabh Tyagi, Keyon Vafa, Luiz Felipe Vecchietti, Linda Vecgaile
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Major life events have proven difficult to predict. Does this reflect limits of theory, data, and algorithms, or the large role of chance? We examine one outcome - having a child within three years - through a near-ideal setting for prediction: a data challenge where 147 researchers predicted births for Dutch residents aged 18-45, using survey data and full-population registers. Methods ranged from logistic regression to a large language model and transformers. Predictions were moderately accurate (best F1: register 0.59, survey 0.76); advanced models did not outperform classical ones; and the larger registers did not beat the survey. Simulating the stochastic biology of conception and pregnancy, we estimated a predictive ceiling (survey F1 ~ 0.86-0.94, register 0.88-0.96). Observed performance falls short of this ceiling, implicating imperfect data, methods, and unmodelled chance, while the ceiling itself shows that chance in reproduction alone sets a non-trivial limit on predicting individual lives.
### Title:
          Recent Developments in Transformer Inference Deployment on FPGA Platforms: A Survey
 - **Authors:** Arjan Blankestijn, Uraz Odyurt, Amirreza Yousefzadeh
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the rapid and continuous growth in the incorporation of machine learning models based on the Transformer architecture, capable deployment is in high demand. In this context, capable deployment refers to operational performance aspects, e.g., throughput and latency, as well as efficiency aspects, e.g., energy consumption. When it comes to the task of inference using such models, purpose-built hardware accelerators provide a lucrative alternative to common deployment choices, such as Central Processing Units (CPUs) and Graphics Processing Units (GPUs). The Field Programmable Gate Array (FPGA) platforms category is an example of such alternative accelerators, promising implementation flexibility, energy efficiency, improved latency and suitability for on-site deployment. We investigate the most recent advances, trends, and design choices for Transformer inference on FPGA platforms. We perform a systematic literature review, extracting and delving into preferred techniques for implementation and optimisation. This study and the provided taxonomy of topics could act as a guide for researchers from the academia and industry alike.
### Title:
          Multi-Head Self Attention is a Parameter Identification Mechanism
 - **Authors:** W. Ross Morrow
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We prove that a multi-head scaled dot product attention can be viewed as a parameter identification strategy. The ratio of unidentified parameters to the total number of parameters scales like the reciprocal of the number of heads ($1/2 \to 1/(2H)$), meaning models with more heads are structurally more identified. A subtle side effect of the mathematics observation that attention can never be fully identified. Similarly we also show that some bias terms can have no effect on softmax-based attention layers in both the single- and multiple-head settings, though this is mostly a curiosity that should have a marginal effect on model size and model training/prediction efficiency. We also touch on modern improvements to transformers including RoPE and GQA from this perspective, illustrating how those as well can improve the ratio of ``meaningful'' parameters to all parameters. Simple numerical examples demonstrate that training can indeed involve updates that overlap model-invariant subspaces that arise from a lack of identification. As part of our experiments we use a ``rebalancing'' approach that can ``fix'' updates that overlap unindentified subspaces but do not try to present evidence this should actually be adopted. Instead we simply view our numerical results as exploring and confirming the theoretical results. As a whole we discuss a purely mathematical/statistical explanation, identification, for why specific architectural choices in transformers may have improved performance.
### Title:
          Position Matters: Feature Inversion Attacks in ViT Split Inference with Token Reduction and Shuffling
 - **Authors:** Stefano Leggio, Giulio Rossolini, Alessandro Biondi
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformers (ViTs) are increasingly used in split-inference systems, where edge devices transmit intermediate token representations to a remote cloud. In this setting, token reduction lowers computation and communication costs, while token shuffling disrupts the spatial organization of the transmitted tokens, potentially limiting information leakage. However, their privacy benefits remain unclear against feature inversion attacks, which attempt to reconstruct the input from the transmitted embeddings. In this work, we show that, despite disrupting the spatial structure required by conventional reconstruction attacks, transmitted token embeddings retain substantial positional information. Based on this observation, we introduce the Spatially Aligned Reconstruction Attack (SARA), a unified pipeline that predicts token positions, restores their spatial layout, reconstructs missing embeddings using a feature-space masked autoencoder, and recovers the input image. Our results demonstrate that token shuffling provides only apparent privacy, as SARA largely reconstructs the original token organization. Token reduction offers stronger protection, but significant leakage persists when the retained tokens preserve sufficient semantic and positional information. Finally, we introduce a lightweight edge-side defense that removes positional embeddings and progressively adapts the edge-side transformer blocks through knowledge distillation. It substantially reduces attack performance against SARA, while preserving downstream task accuracy and requiring no changes to the cloud-side model.
### Title:
          From Language to Behavior: Scaling Sequence Transformers for Industrial Recommendation Ranking with Rec-Native Designs
 - **Authors:** Jie Chen, Xiangqian Yu, Yanchao Lian, Tan Lu, Run Yang, Zhengchun Shang, Xing Wang, Cheng Chen, Ke Hu, Qiang Li, Tianjiu Yin, Xiaobing Liu
 - **Subjects:** Subjects:
Information Retrieval (cs.IR); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scaling Transformers has driven large gains in language modeling, but transplanting this to behavior-sequence modeling in production ranking is challenging: recommendation differs in signal quality, where behavior sequences are noisy, temporally irregular, and sparsely supervised, and in computation asymmetry, where each request scores many candidates against one shared user history under tight latency budgets. We propose ReST, a recommendation-native Transformer scaling framework. For signal quality, it introduces a sequence encoder with dual-gated attention, rotary positional and temporal embedding, stabilized residual normalization, and training-only auxiliary objectives. For computation asymmetry, it factorizes ranking into a heavy reusable encoder and a lightweight cross decoder with projection-free KV attention and token-specific parameterization, coupling user-level shared-prefix training with shared-prefix serving for compute-once, decode-many-times ranking. Across industrial and public benchmarks, ReST achieves higher accuracy and scales more consistently along sequence length, depth, and width, where LLM-style Transformer blocks saturate. A one-week online A/B test on a production advertising platform improves online AUC by 1.31% and lifts a core revenue metric by 11.93% within a 50 ms P99 budget; ReST has since been fully deployed in production, showing that behavior-sequence scaling remains a promising, under-exploited axis for production ranking.
### Title:
          Solving In-Table Prediction Problems by Deep Neural Networks with Performance Evaluation Using Synthetic Data
 - **Authors:** Xiao Zhao, Daniela Oelke
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tabular deep learning (TDL) leverages neural networks (NN) to extract patterns from tabular data. Traditional TDL methods follow a supervised learning paradigm, where a target feature is explicitly given. In this work, however, we explore a different approach by employing deep NNs to learn relationships among individual columns within a given table. We investigate whether NNs can predict the values of arbitrarily selected columns in a given table based on the remaining known columns. We call this problem In-Table Prediction (ITB), which is slightly different from table imputation methods and the pretraining task of TDL. Three potential usage scenarios are identified, which, to our best knowledge, have not been extensively studied in the literature. A self-supervised learning approach is applied to address this problem by randomly selecting columns to be masked out and used as learning targets. This work focuses on tabular datasets containing only continuous features. To handle missing values in continuous features, a novel neural layer is proposed to embed both numerical and empty values. Synthetic data is generated based on predefined column relationships, with empty values inserted using two distinct mechanisms. Additionally, an adapted masking strategy is employed to create test data. Performances of three NN architectures, namely MLP, Resnet and Transformer, are evaluated using the generated synthetic data. We conclude that, the attention-based structure outperforms the other two networks, when a sufficiently large number of training examples is available and a relatively large embedding length is chosen. We stress that these findings are obtained under controlled, synthetic conditions with a small number of columns and it should therefore be regarded as an initial, narrowly-scoped investigation rather than a general characterization of ITP on real-world tabular data.
### Title:
          HiLRP: Toward One Trustworthy Explanation for Vision Transformer: Conservation-Valid Attribution via Attention Primitives
 - **Authors:** Sathiyamohan Nishankar, Pubudu Sanjeewani, Asanka Perera, Selvarajah Thuseethan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformer (ViT) design has become increasingly diverse, with backbones combining convolutional stems, windowed, linear, or multi-axis attention, patch merging, and spatial reduction in various configurations. This diversity poses challenges for existing attribution methods, whose assumptions often do not hold across ViT variants: Grad-CAM requires a terminal spatial feature map, attention rollout assumes global softmax attention, and layer-wise relevance propagation (LRP) requires module-specific rules. To the best of our knowledge, no existing method provides a unified attribution framework across this architectural space. We show that this architectural diversity can be captured by a simpler underlying structure. The attention and resolution-reduction operators in current ViTs can be decomposed into four operation types: linear maps, bilinear mixing, normalization or gating, and reindexing. Each operation admits a relevance rule that satisfies conservation. Based on these rules, HiLRP supports new backbones by construction rather than by architecture-specific derivation, and its attribution maps decompose the prediction rather than relying on heuristic assumptions. We prove conservation and conditional equivariance and verify both to machine precision. Across 14 attribution methods and 10 architectures, we find that no prior method remains reliable across ViT families, while Faithfulness Correlation becomes uninformative for backbones robust to spatial masking. HiLRP alone preserves conservation across windowed, spatial-reduction, multi-axis, and linear-attention models, where naive extensions can produce zero or inflated relevance. It also localizes attribution failures in class activation mapping, achieving 0.97 Pointing compared with 0.55 for competing methods on EfficientViT.
### Title:
          One-Layer Transformer Provably Learns Multiclass One-Nearest Neighbor in Context
 - **Authors:** Skanda Athreya, Yutong Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We extend recent work establishing an equivalence between one-layer transformers and nearest-neighbor classifiers in the binary setting to the multiclass case. By leveraging the simplex encoding, we show that one-layer transformers with an argmax classification head behave identically to a one-nearest-neighbor classifier in the multiclass setting. This closes a gap left by prior work, whose multiclass result relied on a non-standard rounding-based approach rather than the typical argmax head used in practice.
### Title:
          SMELT: Scaling Laws for Compute-Matched MoE Looped Transformers
 - **Authors:** Shaowen Wang, Ge Zhang, Kairong Luo, Yuhao Wu, Shaofan Liu, Jiaheng Liu, Wenhao Huang, Shen Yan, Jian Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Looped Transformers increase effective depth by iterating a shared block of layers, but most evaluations compare at fixed model size, conflating architectural advantage with extra FLOPs. We study looping on Mixture-of-Experts Transformers while closely matching per-token FLOPs, total non-embedding parameters, and KV cache. Through a series of ablations, we arrive at a recipe we call SMELT (Sparse MoE Transformer, middle layers Loop Twice), which loops the middle half of layers twice while matching the unlooped Baseline on all three budgets. We scale SMELT across four sizes up to 54B non-embedding parameters and fit a separate Chinchilla-style scaling law for each architecture. SMELT's loss drops faster with compute, saving 6.8--18.0\% of training FLOPs on the compute-optimal frontier. The advantage transfers to downstream benchmarks beyond what validation loss predicts, is largest on Code, and grows with sample length and the number of in-context examples. Mechanistic analysis shows that the second visit reduces the attention sink and redirects mass toward content-relevant tokens, an inductive bias that may underlie the observed performance gains. These results show that looping can improve Transformers even under budget matching, offering a practical recipe that turns depth reuse into measurable gains.
### Title:
          Polish ModernBERT: The Long and Short of Polish Language Understanding
 - **Authors:** Michał Perełkiewicz, Sławomir Dadas, Rafał Poświata, Małgorzata Grębowiec
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Encoder-only Transformers remain effective for discriminative and representation-learning tasks, yet Polish encoders still largely rely on BERT/RoBERTa-style architectures. We introduce \textbf{Polish ModernBERT}, a family of four Polish encoders available at Base and Large scales, each with 512-token and 8K context variants. We adapt the ModernBERT pretraining recipe through staged selection experiments and release a long-context benchmark covering legal topic classification, ideological decision-direction prediction, factual-consistency assessment over literary plot summaries, and human-rights violation assessment. Across 30 tasks, Polish ModernBERT achieves the best overall performance among the evaluated Polish encoders, reaching 83.99 and 85.11 for the Base-8K and Large-8K models, respectively. On long-context tasks, the 8K variants improve over matched Polish RoBERTa-8K baselines from 67.47 to 77.15 and from 75.88 to 78.49 at the Base and Large scales, respectively. The Base-8K model achieves this gain with 22\% fewer parameters (149M vs.\ 190M). Efficiency measurements in representative inference setups show lower peak memory usage and latency than matched Polish RoBERTa baselines in both 512-token and 8K settings. Polish ModernBERT-8K-Base additionally achieves the best result on a Polish retrieval benchmark among the evaluated encoders below 300M parameters.
### Title:
          Multimodal RGB-Infrared Combination for UAV-Based Wildfire Segmentation: A Comparative Study on FLAME3
 - **Authors:** Matheus F. Kovaleski, Luís Garrote, Cristiano Premebida, Jérôme Mendes, João Ruivo Paulo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unmanned Aerial Vehicles (UAVs) have emerged as a promising platform for firefighting operations due to their flexibility, low operational cost, and ability to acquire high-resolution imagery in locations that may be difficult or dangerous to access using conventional methods. Recent advances in deep learning have significantly improved the capabilities of UAV-based wildfire monitoring systems. The present work investigates RGB-infrared fusion for binary wildfire segmentation on the FLAME3 dataset. In this Study, RGB and Infrared baselines are compared with three representative fusion strategies across three segmentation architectures, including U-Net, DeepLabV3+, and SegFormer. The key motivation of this work is to analyze the contribution of each modality, evaluate the impact of fusion timing, and examine how different network architectures exploit multimodal information for UAV wildfire delineation. The findings indicate that thermal information plays a dominant role in UAV segmentation and that feature-level multimodal fusion combined with transformer-based architectures offers the most promising direction for future research.
### Title:
          Semantic-Guided Multimodal Preprocessing for Vision Transformer-Based Clear Cell Renal Cell Carcinoma Grading
 - **Authors:** Fatemeh Javadian, Zhu Chen, Zahra Aminparast, Johannes Stegmaier
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Clear cell renal cell carcinoma (CCRCC) grading is essential for treatment planning, yet existing approaches either analyze patch-level images directly or focus solely on nuclei-level classification, without linking to final tumor grading. We propose a semantic-guided multimodal preprocessing method that integrates nuclei classification maps from existing pre-trained models with RGB histopathology images for Vision Transformer (ViT)-based CCRCC grading. Our approach employs classification map channel concatenation and multiplicative modulation, with optimized overlays to leverage nuclei grading information, while preserving RGB textural features. Evaluation of multiple preprocessing strategies demonstrates that semantic-guided enhancement achieves 0.916 balanced accuracy, outperforming RGB-only baseline (0.707) and max-voting aggregation from prior studies (0.427). Sensitivity analysis reveals that this 21 percentage point improvement over baseline persists even under simulated perturbation at rates matching current state-of-the-art nuclei classification model error thresholds, suggesting both effective semantic utilization and practical robustness. These findings show that preprocessing-based multimodal fusion can leverage the diagnostic potential of existing imperfect nuclei classifiers, effectively bridging previously isolated fine-grained nuclear-level analysis with coarse-grained ViT-based patch classification. Per-class recall was consistent across grades (0.93, 0.91, 0.91), indicating that gains are not concentrated in the majority class. Because the sensitivity analysis perturbs ground-truth maps rather than predictions from an actual nuclei model, this result characterizes robustness under simulated error rather than deployment with a real upstream model, which remains for future work.
### Title:
          Learning Sparse Decision Trees via Transformer Variational Auto-Encoders
 - **Authors:** Giacomo Fidone, Alessio Cascione, Riccardo Guidotti
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Decision trees are among the most widely used models in machine learning, largely due to their transparent decision logic, making them well-suited for high-stakes decision-making contexts. However, most existing learning algorithms focus on predictive performance, overlooking the joint optimization of other desirable properties, such as structural sparsity. In this work we propose TREVIS, an approach for learning decision trees with respect to complex objectives, based on the exploration of the latent space of a Tree Transformer Variational Auto-Encoder (TTVAE). By mapping decision trees onto latent representations, TREVIS replaces the discrete search space with a continuous one, enabling gradient-based optimization via a differentiable surrogate model. We experiment with TREVIS for learning decision trees that jointly optimize predictive performance and sparsity. Results show that TREVIS discovers decision trees matching the predictive performance of existing near-optimal algorithms while improving their structural sparsity.
### Title:
          Does Imitation Learning Preserve Temporal Robustness in Dexterous Manipulation? An Expert-Learner Comparison Across Task Execution Speeds
 - **Authors:** Clinton Enwerem, John S. Baras, Calin Belta
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dexterous manipulation policies learned by imitation are typically evaluated for robustness to variation in scenes, objects, or instructions, but their performance across task execution speeds is less often examined. This leaves open how much temporal robustness a learner retains relative to the expert it imitates. We compare an expert and learner under the same task conditions, initial-condition draws, and speedup factors. We instantiate the evaluation in ParcelStow, a contact-rich task in which the robot acquires, reorients, and inserts a parcel. The demonstrations span the speedup range for the manipulation phases after parcel acquisition. A scripted expert and an Action Chunking with Transformers (ACT) policy trained from the expert's demonstrations both achieve 100 percent task success at nominal speed. Their success rates diverge within the demonstrated range: at its maximum, expert success is 84 percent and ACT success is 53 percent. Two ACT policies with different parameter initializations show similar degradation, decreasing by 34 and 48 percentage points from nominal speed to the maximum demonstrated speed, compared with 16 points for the expert. Stage-level analysis shows that 35 of ACT's 47 failures at the maximum demonstrated speed are insertion misalignments. Under the relative-motion handoff, every ACT acquisition retains the parcel through reorientation and transfer in free space, but only 64 percent complete the overall task, compared with 95 percent after expert acquisition. Across all evaluated policies and speeds, none of the 414 acquisitions without force closure completes the task. Equal nominal task success therefore does not imply preservation of expert performance across execution speeds. Code, data, and evaluation scripts are available at this https URL.
### Title:
          Benchmarking Spatial, Spectral, and Self-Supervised Cues for Face Forgery Detection under Realistic Degradation
 - **Authors:** Lucas Cunha, Lucas Sotomaior, Lucas Gasperin, Beatriz Caldas, Eduardo Pianovski, Rayson Laroca
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Face forgery detectors often achieve strong results on controlled benchmarks, but their reliability under realistic image degradations remains limited. This paper presents a standardized benchmark for face forgery detection using the Multi-Dimensional Face Forgery Image (MFFI) dataset and evaluates performance on both clean and degraded test partitions. We compare six model families, including convolutional networks, transformer-based models, and a frozen self-supervised DINOv3 backbone, across spatial, spectral, and hybrid input representations. The results show that clean-set performance is not a reliable indicator of robustness under compression, resizing, and blurring. Xception with RGB obtains the best clean performance, reaching 0.884 mean ROC-AUC, but degrades substantially on the harder partition. In contrast, frozen DINOv3 achieves the strongest degraded-set result, with 0.726 mean ROC-AUC, while training only a linear classification head. The representation analysis indicates that Fourier-domain cues are most useful when combined with RGB information, whereas purely spectral inputs consistently underperform spatial representations. Qualitative attribution maps further suggest that convolutional detectors focus on localized artifacts, while DINOv3 relies on broader facial structure. These findings reinforce the need for degraded evaluation protocols and highlight self-supervised visual representations as a promising direction for robust face forgery detection. Our source code is publicly available at this https URL.
### Title:
          What, Where, and How: Probing Spatiotemporal Representations in Video Foundation Models
 - **Authors:** Sharon S. Musa, Fereshteh Forghani, Harrish Thasarathan, Sonia Joseph, Matthew Kowal, Konstantinos G. Derpanis
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-supervised video foundation models learn rich spatiotemporal representations, yet it remains unclear what visual concepts these representations encode, where they emerge across transformer layers, and how they are geometrically organized. In this work, we tackle these three questions through a systematic layer-wise analysis of V-JEPA 2 and VideoMAE-v2. We leverage lightweight probes trained to discover three temporally grounded properties: (i) camera motion understanding, (ii) intuitive physics, and (iii) anomaly detection. Both models encode camera motion, with best results ($>90$ ROC AUC) emerging at 60-70% of network depth, and achieve moderate anomaly detection performance ($>60$ ROC AUC), but remain near chance on intuitive-physics tasks, suggesting a limited encoding of deeper physical reasoning. Beyond classification, we find that temporal features from individual videos form smooth low-dimensional trajectories in representation space, suggesting that camera motion is not only linearly decodable but also geometrically organized. Based on these results, we apply geometry-aware spline-based steering in the model's latent representations to interpolate camera motion, yielding steered videos with smoother trajectories and more coherent temporal progression than linear interpolation.
## Keyword: autonomous driving
### Title:
          Qwen-Drive-1.0: An Initial Step towards a Vision-Language Foundation Model for Autonomous Driving
 - **Authors:** Xin Zhou, Zongchuang Zhao, Zhibo Yang, Mingsheng Li, Humen Zhong, Shuai Bai, Du Chu, Ruizhe Chen, Zhaohai Li, Jun Tang, Qiuyue Wang, Mingkun Yang, Jiazhao Zhang, Dayiheng Liu, Dingkang Liang, Xiang Bai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Qwen-Drive-1.0, an initial step towards a vision-language foundation model for autonomous driving. Qwen-Drive-1.0 retains the architecture of the pretrained vision-language model (VLM) and integrates 3D perception, visual question answering, and motion planning within a unified framework. An external bird's-eye-view (BEV) perception head jointly performs 3D object detection, semantic occupancy prediction, and BEV map segmentation. It serves as a probe of the 3D information accessible from the shared representations and provides an explicit, inspectable interface to 3D scene structure. A Planning Expert conditions on shared VLM representations to generate future ego trajectories. A staged training recipe combines driving supervision with general-purpose vision-language data to acquire driving-specific competence while helping preserve broad visual understanding and instruction-following capabilities. Experiments demonstrate strong 3D perception and driving scene understanding while largely preserving general vision-language capability. Comprehensive evaluations across open-loop, pseudo-closed-loop, and closed-loop settings further show highly competitive motion-planning performance.
### Title:
          CoLT-Drive: Counterfactual Long-Tail Benchmarking and Knowledge-Preserving Adaptation for Driving Affordance Prediction
 - **Authors:** Zhengxu Tang, Guofeng Cui, Ziyu Gong, Xiaozhou Zhang, Ruifeng Deng, Chengzhi Qi, Ke Chen, Sachin Patil, Tianjun Xiao, Langechuan Liu, Pichao Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long-tail autonomous driving failures are often framed as rare-object recognition errors. We argue that this view is incomplete: the decision-critical question is not only whether a model recognizes an unusual object, but whether it infers how that object changes the ego vehicle's feasible high-level actions. We formalize this problem as decision-level driving affordance prediction, where a model maps a front-view image, ego-motion history, and navigation command to a structured longitudinal--lateral meta-action. To evaluate this capability, we introduce CoLT-Drive, a 3,536-sample counterfactual long-tail benchmark that inserts rare objects into otherwise fixed driving scenes and measures whether models predict acceptable action pairs. To improve deployable small VLMs, we propose KPA, a knowledge-preserving adaptation framework that combines structured perception-to-decision prompting, SLERP-based expert merging, and RegMoE, a regime-aware LoRA mixture-of-experts module. KPA preserves the pretrained model's open-world knowledge while allocating lightweight adaptation capacity to different driving decision regimes. Experiments on an in-domain driving split and CoLT-Drive show that KPA achieves 60.8\% pair accuracy on CoLT-Drive, outperforming the pretrained Qwen3-VL-2B baseline (50.3\%) and LoRA SFT (32.4\%) while maintaining competitive in-domain accuracy. Our benchmark and code are available at this https URL and this https URL.
### Title:
          Vision-Language-Guided Pseudo-Labels for Unsupervised Domain Adaptation in Semantic Segmentation for Waste Sorting
 - **Authors:** Udo Schlegel, Shubhangi, Gabriel Dax, Sai Rahul Kaminwar, Florian Karl, Thomas Seidl
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Obtaining labeled data for semantic segmentation in applied settings (e.g., autonomous driving, industrial waste sorting) is expensive and often infeasible at scale. We present a cross-modal pseudo-labeling pipeline that enables unsupervised domain adaptation without any target-domain annotations. The pipeline is built on two core foundation models: SAM generates class-agnostic region proposals, and EVA-CLIP assigns semantic labels based on region-text similarity, with confidence filtering ensuring that only reliable pseudo-labels are used for self-training a segmentation model. As an optional extension, BLIP provides language-grounded verification for ambiguous regions, thereby improving pseudo-label quality without altering the overall pipeline. Evaluated on two domain shifts, synthetic-to-real autonomous driving and, with a primary focus, lab-to-factory industrial waste sorting, the pipeline consistently improves over source-only baselines. Our results demonstrate that pseudo-label quality, not quantity, is a decisive factor in self-training under domain shift, and that cross-modal language grounding offers a practical path to reliable automatic annotation in deployment-critical applications.
### Title:
          DNC-IMM: Early Lane-Change Intention Recognition via Neural Calibration Based on Driving Context Information
 - **Authors:** Woong-Chan Byun, Seung-Hyun Kong
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Early recognition of lane-change intention is essential for proactive decision-making in autonomous driving and advanced driver assistance systems. This paper proposes a Dual Neural-Calibrated Interacting Multiple Model (DNC-IMM) that improves adaptability to driving context while preserving the probabilistic structure and interpretability of a conventional IMM. The proposed method encodes driving-context information, including target-vehicle motion, gaps to surrounding vehicles, and relative velocities, with a neural network that calibrates both the transition-probability matrix and measurement likelihoods. The final intention is determined from the calibrated IMM mode posterior rather than from a separate direct classifier. Experiments on the highD dataset demonstrate that the proposed method reliably recognizes lane-change intentions before lane crossing and provides particularly strong performance at the earlier 2-3 s prediction horizons.
### Title:
          Monocular Depth Estimation from a Single Image: Progress and Opportunities
 - **Authors:** Muxin Liu, Xiaoyang Lyu, Yang-Tian Sun, Yi-Hua Huang, Ziyi Yang, Peng Dai, Xiaojuan Qi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular depth estimation has long stood as a fundamental challenge in computer vision, enabling a wide range of applications including 3D reconstruction, robotics, autonomous driving, and augmented reality. This survey traces the field's evolution from early learning-based methods to the emergence of transformative foundation models. We begin by framing the problem, distinguishing between relative and metric depth estimation, and highlighting the key challenges that have shaped a decade of research. We then present common problem formulations and introduce the most widely used datasets, covering indoor, outdoor, and synthetic data. Following this, we review major advances prior to the foundation model era, distilling core insights from influential methods that contributed to improvements in accuracy, efficiency, and robustness. The survey then turns to the recent surge of foundation-model-based approaches, categorizing them into discriminative and generative paradigms and emphasizing the critical roles of large-scale pretraining (e.g., DINOv3) and synthetic data. We compare representative models using both quantitative benchmarks and qualitative examples, and discuss natural extensions to video-based depth estimation. Further, to illustrate real-world impact, we highlight the integration of depth estimation into applications such as visual SLAM, content generation, and robot perception. Finally, we outline open challenges and promising research directions as the field advances further into the era of foundation models.
