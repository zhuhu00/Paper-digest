# Showing new listings for Thursday, 26 March 2026
## Keyword: SLAM
### Title:
          IslamicMMLU: A Benchmark for Evaluating LLMs on Islamic Knowledge
 - **Authors:** Ali Abdelaal, Mohammed Nader Al Haffar, Mahmoud Fawzi, Walid Magdy
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models are increasingly consulted for Islamic knowledge, yet no comprehensive benchmark evaluates their performance across core Islamic disciplines. We introduce IslamicMMLU, a benchmark of 10,013 multiple-choice questions spanning three tracks: Quran (2,013 questions), Hadith (4,000 questions), and Fiqh (jurisprudence, 4,000 questions). Each track is formed of multiple types of questions to examine LLMs capabilities handling different aspects of Islamic knowledge. The benchmark is used to create the IslamicMMLU public leaderboard for evaluating LLMs, and we initially evaluate 26 LLMs, where their averaged accuracy across the three tracks varied between 39.8\% to 93.8\% (by Gemini 3 Flash). The Quran track shows the widest span (99.3\% to 32.4\%), while the Fiqh track includes a novel madhab (Islamic school of jurisprudence) bias detection task revealing variable school-of-thought preferences across models. Arabic-specific models show mixed results, but they all underperform compared to frontier models. The evaluation code and leaderboard are made publicly available.
### Title:
          CVPD at QIAS 2026: RAG-Guided LLM Reasoning for Al-Mawarith Share Computation and Heir Allocation
 - **Authors:** Wassim Swaileh, Mohammed-En-Nadhir Zighem, Hichem Telli, Salah Eddine Bekhouche, Abdellah Zakaria Sellam, Fadi Dornaika, Dimitrios Kotzinos
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Islamic inheritance (Ilm al-Mawarith) is a multi-stage legal reasoning task requiring the identification of eligible heirs, resolution of blocking rules (hajb), assignment of fixed and residual shares, handling of adjustments such as awl and radd, and generation of a consistent final distribution. The task is further complicated by variations across legal schools and civil-law codifications, requiring models to operate under explicit legal configurations. We present a retrieval-augmented generation (RAG) pipeline for this setting, combining rule-grounded synthetic data generation, hybrid retrieval (dense and BM25) with cross-encoder reranking, and schema-constrained output validation. A symbolic inheritance calculator is used to generate a large high-quality synthetic corpus with full intermediate reasoning traces, ensuring legal and numerical consistency. The proposed system achieves a MIR-E score of 0.935 and ranks first on the official QIAS 2026 blind-test leaderboard. Results demonstrate that retrieval-grounded, schema-aware generation significantly improves reliability in high-precision Arabic legal reasoning tasks.
## Keyword: odometry
There is no result 
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Attack Assessment and Augmented Identity Recognition for Human Skeleton Data
 - **Authors:** Joseph G. Zalameda, Megan A. Witherow, Alexander M. Glandon, Jose Aguilera, Khan M. Iftekharuddin
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Cryptography and Security (cs.CR); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Machine learning models trained on small data sets for security applications are especially vulnerable to adversarial attacks. Person identification from LiDAR based skeleton data requires time consuming and expensive data acquisition for each subject identity. Recently, Assessment and Augmented Identity Recognition for Skeletons (AAIRS) has been used to train Hierarchical Co-occurrence Networks for Person Identification (HCN-ID) with small LiDAR based skeleton data sets. However, AAIRS does not evaluate robustness of HCN-ID to adversarial attacks or inoculate the model to defend against such attacks. Popular perturbation-based approaches to generating adversarial attacks are constrained to targeted perturbations added to real training samples, which is not ideal for inoculating models with small training sets. Thus, we propose Attack-AAIRS, a novel addition to the AAIRS framework. Attack-AAIRS leverages a small real data set and a GAN generated synthetic data set to assess and improve model robustness against unseen adversarial attacks. Rather than being constrained to perturbations of limited real training samples, the GAN learns the distribution of adversarial attack samples that exploit weaknesses in HCN-ID. Attack samples drawn from this distribution augment training for inoculation of the HCN-ID to improve robustness. Ten-fold cross validation of Attack-AAIRS yields increased robustness to unseen attacks- including FGSM, PGD, Additive Gaussian Noise, MI-FGSM, and BIM. The HCN-ID Synthetic Data Quality Score for Attack-AAIRS indicates that generated attack samples are of similar quality to the original benign synthetic samples generated by AAIRS. Furthermore, inoculated models show consistent final test accuracy with the original model trained on real data, demonstrating that our method improves robustness to adversarial attacks without reducing test performance on real data.
### Title:
          Decentralized End-to-End Multi-AAV Pursuit Using Predictive Spatio-Temporal Observation via Deep Reinforcement Learning
 - **Authors:** Yude Li, Zhexuan Zhou, Huizhe Li, Yanke Sun, Yenan Wu, Yichen Lai, Yiming Wang, Youmin Gong, Jie Mei
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Decentralized cooperative pursuit in cluttered environments is challenging for autonomous aerial swarms, especially under partial and noisy perception. Existing methods often rely on abstracted geometric features or privileged ground-truth states, and therefore sidestep perceptual uncertainty in real-world settings. We propose a decentralized end-to-end multi-agent reinforcement learning (MARL) framework that maps raw LiDAR observations directly to continuous control commands. Central to the framework is the Predictive Spatio-Temporal Observation (PSTO), an egocentric grid representation that aligns obstacle geometry with predictive adversarial intent and teammate motion in a unified, fixed-resolution projection. Built on PSTO, a single decentralized policy enables agents to navigate static obstacles, intercept dynamic targets, and maintain cooperative encirclement. Simulations demonstrate that the proposed method achieves superior capture efficiency and competitive success rates compared to state-of-the-art learning-based approaches relying on privileged obstacle information. Furthermore, the unified policy scales seamlessly across different team sizes without retraining. Finally, fully autonomous outdoor experiments validate the framework on a quadrotor swarm relying on only onboard sensing and computing.
### Title:
          VERIA: Verification-Centric Multimodal Instance Augmentation for Long-Tailed 3D Object Detection
 - **Authors:** Jumin Lee, Siyeong Lee, Namil Kim, Sung-Eui Yoon
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long-tail distributions in driving datasets pose a fundamental challenge for 3D perception, as rare classes exhibit substantial intra-class diversity yet available samples cover this variation space only sparsely. Existing instance augmentation methods based on copy-paste or asset libraries improve rare-class exposure but are often limited in fine-grained diversity and scene-context placement. We propose VERIA, an image-first multimodal augmentation framework that synthesizes synchronized RGB--LiDAR instances using off-the-shelf foundation models and curates them with sequential semantic and geometric verification. This verification-centric design tends to select instances that better match real LiDAR statistics while spanning a wider range of intra-class variation. Stage-wise yield decomposition provides a log-based diagnostic of pipeline reliability. On nuScenes and Lyft, VERIA improves rare-class 3D object detection in both LiDAR-only and multimodal settings. Our code is available at this https URL.
### Title:
          Le MuMo JEPA: Multi-Modal Self-Supervised Representation Learning with Learnable Fusion Tokens
 - **Authors:** Ciem Cornelissen, Sam Leroux, Pieter Simoens
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-supervised learning has emerged as a powerful paradigm for learning visual representations without manual annotations, yet most methods still operate on a single modality and therefore miss the complementary structure available from heterogeneous sensors. We present Le MuMo JEPA, a self-supervised framework that learns unified representations from RGB images and aligned companion modalities. In our driving experiments, the second modality is camera-aligned LiDAR depth; we also evaluate RGB-thermal training and transfer on the Teledyne FLIR ADAS benchmark. Our approach extends LeJEPA to the multi-modal setting by learning fusion tokens that act as a latent bottleneck between modality-specific patch stems inside a shared transformer. Our default model employs a pruned fusion strategy: after an initial cross-modal attention layer, modality-specific tokens are dropped, forcing cross-modal information into the shared fusion-token grid as an efficient latent bottleneck before Sketched Isotropic Gaussian Regularization (SIGReg) is applied to the joint multimodal CLS embedding. On Waymo, Le MuMo JEPA gives the strongest performance-efficiency trade-off on downstream patch probes among the from-scratch multimodal baselines, improving CenterNet detection and dense depth while remaining competitive on segmentation. Under from-scratch training on nuScenes, Le MuMo JEPA remains the strongest model, and it also gives the best FLIR results, especially after Waymo-initialized fine-tuning. It also retains the best overall accuracy-efficiency balance in our study at substantially lower compute, memory, and estimated training time.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          EndoVGGT: GNN-Enhanced Depth Estimation for Surgical 3D Reconstruction
 - **Authors:** Falong Fan, Yi Xie, Arnis Lektauers, Bo Liu, Jerzy Rozenblit
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate 3D reconstruction of deformable soft tissues is essential for surgical robotic perception. However, low-texture surfaces, specular highlights, and instrument occlusions often fragment geometric continuity, posing a challenge for existing fixed-topology approaches. To address this, we propose EndoVGGT, a geometry-centric framework equipped with a Deformation-aware Graph Attention (DeGAT) module. Rather than using static spatial neighborhoods, DeGAT dynamically constructs feature-space semantic graphs to capture long-range correlations among coherent tissue regions. This enables robust propagation of structural cues across occlusions, enforcing global consistency and improving non-rigid deformation recovery. Extensive experiments on SCARED show that our method significantly improves fidelity, increasing PSNR by 24.6% and SSIM by 9.1% over prior state-of-the-art. Crucially, EndoVGGT exhibits strong zero-shot cross-dataset generalization to the unseen SCARED and EndoNeRF domains, confirming that DeGAT learns domain-agnostic geometric priors. These results highlight the efficacy of dynamic feature-space modeling for consistent surgical 3D reconstruction.
## Keyword: mapping
### Title:
          Navigating the Concept Space of Language Models
 - **Authors:** Wilson E. Marcílio-Jr, Danilo M. Eler
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sparse autoencoders (SAEs) trained on large language model activations output thousands of features that enable mapping to human-interpretable concepts. The current practice for analyzing these features primarily relies on inspecting top-activating examples, manually browsing individual features, or performing semantic search on interested concepts, which makes exploratory discovery of concepts difficult at scale. In this paper, we present Concept Explorer, a scalable interactive system for post-hoc exploration of SAE features that organizes concept explanations using hierarchical neighborhood embeddings. Our approach constructs a multi-resolution manifold over SAE feature embeddings and enables progressive navigation from coarse concept clusters to fine-grained neighborhoods, supporting discovery, comparison, and relationship analysis among concepts. We demonstrate the utility of Concept Explorer on SAE features extracted from SmolLM2, where it reveals coherent high-level structure, meaningful subclusters, and distinctive rare concepts that are hard to identify with existing workflows.
### Title:
          StateLinFormer: Stateful Training Enhancing Long-term Memory in Navigation
 - **Authors:** Zhiyuan Chen, Yuxuan Zhong, Fan Wang, Bo Yu, Pengtao Shao, Shaoshan Liu, Ning Ding
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Effective navigation intelligence relies on long-term memory to support both immediate generalization and sustained adaptation. However, existing approaches face a dilemma: modular systems rely on explicit mapping but lack flexibility, while Transformer-based end-to-end models are constrained by fixed context windows, limiting persistent memory across extended interactions. We introduce StateLinFormer, a linear-attention navigation model trained with a stateful memory mechanism that preserves recurrent memory states across consecutive training segments instead of reinitializing them at each batch boundary. This training paradigm effectively approximates learning on infinitely long sequences, enabling the model to achieve long-horizon memory retention. Experiments across both MAZE and ProcTHOR environments demonstrate that StateLinFormer significantly outperforms its stateless linear-attention counterpart and standard Transformer baselines with fixed context windows. Notably, as interaction length increases, persistent stateful training substantially improves context-dependent adaptation, suggesting an enhancement in the model's In-Context Learning (ICL) capabilities for navigation tasks.
### Title:
          The Geometric Price of Discrete Logic: Context-driven Manifold Dynamics of Number Representations
 - **Authors:** Long Zhang, Dai-jun Lin, Wei-neng Chen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) generalize smoothly across continuous semantic spaces, yet strict logical reasoning demands the formation of discrete decision boundaries. Prevailing theories relying on linear isometric projections fail to resolve this fundamental tension. In this work, we argue that task context operates as a non-isometric dynamical operator that enforces a necessary "topological distortion." By applying Gram-Schmidt decomposition to residual-stream activations , we reveal a dual-modulation mechanism driving this process: a class-agnostic topological preservation that anchors global structure to prevent semantic collapse, and a specific algebraic divergence that directionally tears apart cross-class concepts to forge logical boundaries. We validate this geometric evolution across a gradient of tasks, from simple mapping to complex primality testing. Crucially, targeted specific vector ablation establishes a strict causal binding between this topology and model function: algebraically erasing the divergence component collapses parity classification accuracy from 100% to chance levels (38.57%). Furthermore, we uncover a three-phase layer-wise geometric dynamic and demonstrate that under social pressure prompts, models fail to generate sufficient divergence. This results in a "manifold entanglement" that geometrically explains sycophancy and hallucination. Ultimately, our findings revise the linear-isometric presumption, demonstrating that the emergence of discrete logic in LLMs is purchased at an irreducible cost of topological deformation.
### Title:
          Stochastic Ray Tracing for the Reconstruction of 3D Gaussian Splatting
 - **Authors:** Peiyu Xu, Xin Sun, Krishna Mullia, Raymond Fei, Iliyan Georgiev, Shuang Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ray-tracing-based 3D Gaussian splatting (3DGS) methods overcome the limitations of rasterization -- rigid pinhole camera assumptions, inaccurate shadows, and lack of native reflection or refraction -- but remain slower due to the cost of sorting all intersecting Gaussians along every ray. Moreover, existing ray-tracing methods still rely on rasterization-style approximations such as shadow mapping for relightable scenes, undermining the generality that ray tracing promises. We present a differentiable, sorting-free stochastic formulation for ray-traced 3DGS -- the first framework that uses stochastic ray tracing to both reconstruct and render standard and relightable 3DGS scenes. At its core is an unbiased Monte Carlo estimator for pixel-color gradients that evaluates only a small sampled subset of Gaussians per ray, bypassing the need for sorting. For standard 3DGS, our method matches the reconstruction quality and speed of rasterization-based 3DGS while substantially outperforming sorting-based ray tracing. For relightable 3DGS, the same stochastic estimator drives per-Gaussian shading with fully ray-traced shadow rays, delivering notably higher reconstruction fidelity than prior work.
### Title:
          Boost Like a (Var)Pro: Trust-Region Gradient Boosting via Variable Projection
 - **Authors:** Abhijit Chowdhary, Elizabeth Newman, Deepanshu Verma
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Numerical Analysis (math.NA); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Gradient boosting, a method of building additive ensembles from weak learners, has established itself as a practical and theoretically-motivated approach to approximate functions, especially using decision tree weak learners. Comparable methods for smooth parametric learners, such as neural networks, remain less developed in both training methodology and theory. To this end, we introduce \texttt{VPBoost} ({\bf V}ariable {\bf P}rojection {\bf Boost}ing), a gradient boosting algorithm for separable smooth approximators, i.e., models with a smooth nonlinear featurizer followed by a final linear mapping. \texttt{VPBoost} fuses variable projection, a training paradigm for separable models that enforces optimality of the linear weights, with a second-order weak learning strategy. The combination of second-order boosting, separable models, and variable projection give rise to a closed-form solution for the optimal linear weights and a natural interpretation of \VPBoost as a functional trust-region method. We thereby leverage trust-region theory to prove \VPBoost converges to a stationary point under mild geometric conditions and, under stronger assumptions, achieves a superlinear convergence rate. Comprehensive numerical experiments on synthetic data, image recognition, and scientific machine learning benchmarks demonstrate that \VPBoost learns an ensemble with improved evaluation metrics in comparison to gradient-descent-based boosting and attains competitive performance relative to an industry-standard decision tree boosting algorithm.
### Title:
          Estimating Individual Tree Height and Species from UAV Imagery
 - **Authors:** Jannik Endres, Etienne Laliberté, David Rolnick, Arthur Ouaknine
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate estimation of forest biomass, a major carbon sink, relies heavily on tree-level traits such as height and species. Unoccupied Aerial Vehicles (UAVs) capturing high-resolution imagery from a single RGB camera offer a cost-effective and scalable approach for mapping and measuring individual trees. We introduce BIRCH-Trees, the first benchmark for individual tree height and species estimation from tree-centered UAV images, spanning three datasets: temperate forests, tropical forests, and boreal plantations. We also present DINOvTree, a unified approach using a Vision Foundation Model (VFM) backbone with task-specific heads for simultaneous height and species prediction. Through extensive evaluations on BIRCH-Trees, we compare DINOvTree against commonly used vision methods, including VFMs, as well as biological allometric equations. We find that DINOvTree achieves top overall results with accurate height predictions and competitive classification accuracy while using only 54% to 58% of the parameters of the second-best approach.
### Title:
          Task-Space Singularity Avoidance for Control Affine Systems Using Control Barrier Functions
 - **Authors:** Kimia Forghani, Suraj Raval, Lamar Mair, Axel Krieger, Yancy Diaz-Mercado
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Singularities in robotic and dynamical systems arise when the mapping from control inputs to task-space motion loses rank, leading to an inability to determine inputs. This limits the system's ability to generate forces and torques in desired directions and prevents accurate trajectory tracking. This paper presents a control barrier function (CBF) framework for avoiding such singularities in control-affine systems. Singular configurations are identified through the eigenvalues of a state-dependent input-output mapping matrix, and barrier functions are constructed to maintain a safety margin from rank-deficient regions. Conditions for theoretical guarantees on safety are provided as a function of actuator dynamics. Simulations on a planar 2-link manipulator and a magnetically actuated needle demonstrate smooth trajectory tracking while avoiding singular configurations and reducing control input spikes by up to 100x compared to the nominal controller.
### Title:
          How are AI agents used? Evidence from 177,000 MCP tools
 - **Authors:** Merlin Stein
 - **Subjects:** Subjects:
Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Today's AI agents are built on large language models (LLMs) equipped with tools to access and modify external environments, such as corporate file systems, API-accessible platforms and websites. AI agents offer the promise of automating computer-based tasks across the economy. However, developers, researchers and governments lack an understanding of how AI agents are currently being used, and for what kinds of (consequential) tasks. To address this gap, we evaluated 177,436 agent tools created from 11/2024 to 02/2026 by monitoring public Model Context Protocol (MCP) server repositories, the current predominant standard for agent tools. We categorise tools according to their direct impact: perception tools to access and read data, reasoning tools to analyse data or concepts, and action tools to directly modify external environments, like file editing, sending emails or steering drones in the physical world. We use O*NET mapping to identify each tool's task domain and consequentiality. Software development accounts for 67% of all agent tools, and 90% of MCP server downloads. Notably, the share of 'action' tools rose from 27% to 65% of total usage over the 16-month period sampled. While most action tools support medium-stakes tasks like editing files, there are action tools for higher-stakes tasks like financial transactions. Using agentic financial transactions as an example, we demonstrate how governments and regulators can use this monitoring method to extend oversight beyond model outputs to the tool layer to monitor risks of agent deployment.
### Title:
          Stable High-Order Interpolation on the Grassmann Manifold by Maximum-Volume Coordinates and Arnoldi Orthogonalization
 - **Authors:** Qiang Niu, Wen Jiang, Jie Fei, Ruoyu Xiong, Yuxuan Li
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-order interpolation on the Grassmann manifold $\Gr(n, p)$ is often hindered by the computational overhead and derivative instability of SVD-based geometric mappings. To solve the challenges, we propose a stabilized framework that combines Maximum-Volume (MV) local coordinates with Arnoldi-orthogonalized polynomial bases. First, manifold data are mapped to a well-conditioned Euclidean domain via MV coordinates. The approach bypasses the costly matrix factorizations inherent to traditional Riemannian normal coordinates. Within the coordinate space, we use the Vandermonde-with-Arnoldi (V+A) method for Lagrange interpolation and its confluent extension (CV+A) for derivative-enriched Hermite interpolation. By constructing discrete orthogonal bases directly from the parameter nodes, the solution of ill-conditioned linear system is avoided. Theoretical bounds are established to verify the stability of the geometric mapping and the polynomial approximation. Extensive numerical experiments demonstrate that the proposed MV-(C)V+A framework can produce highly accurate approximation in high-degree polynomial interpolation.
### Title:
          DUPLEX: Agentic Dual-System Planning via LLM-Driven Information Extraction
 - **Authors:** Keru Hua, Ding Wang, Yaoying Gu, Xiaoguang Ma
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Large Language Models (LLMs) provide semantic flexibility for robotic task planning, their susceptibility to hallucination and logical inconsistency limits their reliability in long-horizon domains. To bridge the gap between unstructured environments and rigorous plan synthesis, we propose DUPLEX, an agentic dual-system neuro-symbolic architecture that strictly confines the LLM to schema-guided information extraction rather than end-to-end planning or code generation. In our framework, a feed-forward Fast System utilizes a lightweight LLM to extract entities, relations etc. from natural language, deterministically mapping them into a Planning Domain Definition Language (PDDL) problem file for a classical symbolic planner. To resolve complex or underspecified scenarios, a Slow System is activated exclusively upon planning failure, leveraging solver diagnostics to drive a high-capacity LLM in iterative reflection and repair. Extensive evaluations across 12 classical and household planning domains demonstrate that DUPLEX significantly outperforms existing end-to-end and hybrid LLM baselines in both success rate and reliability. These results confirm that The key is not to make the LLM plan better, but to restrict the LLM to the part it is good at - structured semantic grounding - and leave logical plan synthesis to a symbolic planner.
### Title:
          Towards Energy-aware Requirements Dependency Classification: Knowledge-Graph vs. Vector-Retrieval Augmented Inference with SLMs
 - **Authors:** Shreyas Patil, Pragati Kumari, Novarun Deb, Gouri Ginde
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The continuous evolution of system specifications necessitates frequent evaluation of conflicting requirements, a process that is traditionally labour intensive. Although large language models (LLMs) have demonstrated significant potential for automating this detection, their massive computational requirements often result in excessive energy waste. Consequently, there is a growing need to transition toward Small Language Models (SLMs) and energy aware architectures for sustainable Requirements Engineering. This study proposes and empirically evaluates an energy aware framework that compares Knowledge Graph-based Retrieval (KGR) with Vector-based Semantic Retrieval (VSR) to enhance SLM-based inference at the 7B to 8B parameter scale. By leveraging structured graph traversal and high dimensional semantic mapping, we extract candidate requirements, which are then classified as conflicting or neutral by an inference engine. We evaluate these retrieval enhanced strategies across Zero-Shot, Few-Shot, and Chain of Thoughts prompting methods. Using a three-pillar sustainability framework measuring energy consumption (Wh), latency (s), and carbon emissions (gCO2eq) alongside standard accuracy metrics (F1 Score), this research provides a first systematic empirical evaluation and trade off analysis between predictive performance and environmental impact. Our findings highlight the effectiveness of structured versus semantic retrieval in detecting requirement conflicts, offering a reproducible, sustainability aware architecture for energy efficient requirement engineering.
### Title:
          PAC-DP: Personalized Adaptive Clipping for Differentially Private Federated Learning
 - **Authors:** Hao Zhou, Siqi Cai, Hua Dai, Geng Yang, Jing Luo, Hui Cai
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Differential privacy (DP) is crucial for safeguarding sensitive client information in federated learning (FL), yet traditional DP-FL methods rely predominantly on fixed gradient clipping thresholds. Such static clipping neglects significant client heterogeneity and varying privacy sensitivities, which may lead to an unfavorable privacy-utility trade-off. In this paper, we propose PAC-DP, a Personalized Adaptive Clipping framework for federated learning under record-level local differential privacy. PAC-DP introduces a Simulation-CurveFitting approach leveraging a server-hosted public proxy dataset to learn an effective mapping between personalized privacy budgets epsilon and gradient clipping thresholds C, which is then deployed online with a lightweight round-wise schedule. This design enables budget-conditioned threshold selection while avoiding data-dependent tuning during training. We provide theoretical analyses establishing convergence guarantees under the per-example clipping and Gaussian perturbation mechanism and a reproducible privacy accounting procedure. Extensive evaluations on multiple FL benchmarks show that PAC-DP surpasses conventional fixed-threshold approaches under matched privacy budgets, improving accuracy by up to 26% and accelerating convergence by up to 45.5% in our evaluated settings.
### Title:
          Equivariant Filter Transformations for Consistent and Efficient Visual--Inertial Navigation
 - **Authors:** Chungeng Tian, Fenghua He, Ning Hao
 - **Subjects:** Subjects:
Robotics (cs.RO); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents an equivariant filter (EqF) transformation approach for visual--inertial navigation. By establishing analytical links between EqFs with different symmetries, the proposed approach enables systematic consistency design and efficient implementation. First, we formalize the mapping from the global system state to the local error-state and prove that it induces a nonsingular linear transformation between the error-states of any two EqFs. Second, we derive transformation laws for the associated linearized error-state systems and unobservable subspaces. These results yield a general consistency design principle: for any unobservable system, a consistent EqF with a state-independent unobservable subspace can be synthesized by transforming the local coordinate chart, thereby avoiding ad hoc symmetry analysis. Third, to mitigate the computational burden arising from the non-block-diagonal Jacobians required for consistency, we propose two efficient implementation strategies. These strategies exploit the Jacobians of a simpler EqF with block-diagonal structure to accelerate covariance operations while preserving consistency. Extensive Monte Carlo simulations and real-world experiments validate the proposed approach in terms of both accuracy and runtime.
### Title:
          Linear-Nonlinear Fusion Neural Operator for Partial Differential Equations
 - **Authors:** Heng Wu, Junjie Wang, Benzhuo Lu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural operator learning directly constructs the mapping relationship from the equation parameter space to the solution space, enabling efficient direct inference in practical applications without the need for repeated solution of partial differential equations (PDEs) - an advantage that is difficult to achieve with traditional numerical methods. In this work, we find that explicitly decoupling linear and nonlinear effects within such operator mappings leads to markedly improved learning efficiency. This yields a novel network structure, namely the Linear-Nonlinear Fusion Neural Operator (LNF-NO), which models operator mappings via the multiplicative fusion of a linear component and a nonlinear component, thus achieving a lightweight and interpretable representation. This linear-nonlinear decoupling enables efficient capture of complex solution features at the operator level while maintaining stability and generality. LNF-NO naturally supports multiple functional inputs and is applicable to both regular grids and irregular geometries. Across a diverse suite of PDE operator-learning benchmarks, including nonlinear Poisson-Boltzmann equations and multi-physics coupled systems, LNF-NO is typically substantially faster to train than Deep Operator Networks (DeepONet) and Fourier Neural Operators (FNO), while achieving comparable or better accuracy in most cases. On the tested 3D Poisson-Boltzmann case, LNF-NO attains the best accuracy among the compared models and trains approximately 2.7x faster than a 3D FNO baseline.
### Title:
          LightSplat: Fast and Memory-Efficient Open-Vocabulary 3D Scene Understanding in Five Seconds
 - **Authors:** Jaehun Bang, Jinhyeok Kim, Minji Kim, Seungheon Jeong, Kyungdon Joo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open-vocabulary 3D scene understanding enables users to segment novel objects in complex 3D environments through natural language. However, existing approaches remain slow, memory-intensive, and overly complex due to iterative optimization and dense per-Gaussian feature assignments. To address this, we propose LightSplat, a fast and memory-efficient training-free framework that injects compact 2-byte semantic indices into 3D representations from multi-view images. By assigning semantic indices only to salient regions and managing them with a lightweight index-feature mapping, LightSplat eliminates costly feature optimization and storage overhead. We further ensure semantic consistency and efficient inference via single-step clustering that links geometrically and semantically related masks in 3D. We evaluate our method on LERF-OVS, ScanNet, and DL3DV-OVS across complex indoor-outdoor scenes. As a result, LightSplat achieves state-of-the-art performance with up to 50-400x speedup and 64x lower memory, enabling scalable language-driven 3D understanding. For more details, visit our project page this https URL.
### Title:
          ScrollScape: Unlocking 32K Image Generation With Video Diffusion Priors
 - **Authors:** Haodong Yu, Yabo Zhang, Donglin Di, Ruyi Zhang, Wangmeng Zuo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While diffusion models excel at generating images with conventional dimensions, pushing them to synthesize ultra-high-resolution imagery at extreme aspect ratios (EAR) often triggers catastrophic structural failures, such as object repetition and spatial this http URL limitation fundamentally stems from a lack of robust spatial priors, as static text-to-image models are primarily trained on image distributions with conventional this http URL overcome this bottleneck, we present ScrollScape, a novel framework that reformulates EAR image synthesis into a continuous video generation process through two core this http URL mapping the spatial expansion of a massive canvas to the temporal evolution of video frames, ScrollScape leverages the inherent temporal consistency of video models as a powerful global constraint to ensure long-range structural this http URL, Scanning Positional Encoding (ScanPE) distributes global coordinates across frames to act as a flexible moving camera, while Scrolling Super-Resolution (ScrollSR) leverages video super-resolution priors to circumvent memory bottlenecks, efficiently scaling outputs to an unprecedented 32K resolution. Fine-tuned on a curated 3K multi-ratio image dataset, ScrollScape effectively aligns pre-trained video priors with the EAR generation task. Extensive evaluations demonstrate that it significantly outperforms existing image-diffusion baselines by eliminating severe localized artifacts. Consequently, our method overcomes inherent structural bottlenecks to ensure exceptional global coherence and visual fidelity across diverse domains at extreme scales.
### Title:
          Refining time-space traffic diagrams: A neighborhood-adaptive linear regression method
 - **Authors:** Zhihong Yao, Yi Yu, Yunxia Wu, Hao Li, Yangsheng Jiang, Zhengbing He
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The time-space (TS) traffic diagram serves as a crucial tool for characterizing the dynamic evolution of traffic flow, with its resolution directly influencing the effectiveness of traffic theory research and engineering applications. However, constrained by monitoring precision and sampling frequency, existing TS traffic diagrams commonly suffer from low resolution. To address this issue, this paper proposes a refinement method for TS traffic diagrams based on neighborhood-adaptive linear regression. Introducing the concept of neighborhood embedding into TS diagram refinement, the method leverages local pattern similarity in TS diagrams, adaptively identifies neighborhoods similar to target cells, and fits the low-to-high resolution mapping within these neighborhoods for refinement. It avoids the over-smoothing tendency of the traditional global linear model, allows the capture of unique traffic wave propagation and congestion evolution characteristics, and outperforms the traditional neighborhood embedding method in terms of local information utilization to achieve target cell refinement. Validation on two real datasets across multiple scales and upscaling factors shows that, compared to benchmark methods, the proposed method achieves improvements of 9.16%, 8.16%, 1.86%, 3.89%, and 5.83% in metrics including MAE, MAPE, CMJS, SSIM, and GMSD, respectively. Furthermore, the proposed method exhibits strong generalization and robustness in cross-day and cross-scenario validations. In summary, requiring only a minimal amount of paired high- and low-resolution training data, the proposed method features a concise formulation, providing a foundation for the low-cost, fine-grained refinement of low-sampling-rate traffic data.
### Title:
          Learning Response-Statistic Shifts and Parametric Roll Episodes from Wave--Vessel Time Series via LSTM Functional Models
 - **Authors:** Jose del Aguila Ferrandis
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computational Physics (physics.comp-ph); Data Analysis, Statistics and Probability (physics.data-an); Fluid Dynamics (physics.flu-dyn)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Parametric roll is a rare but high-consequence instability that can trigger abrupt regime changes in ship response, including pronounced shifts in roll statistics and tail risk. This paper develops a data-driven surrogate that learns the nonlinear, causal functional mapping from incident wave--motion time series to vessel motions, and demonstrates that the surrogate reproduces both (i) parametric roll episodes and (ii) the associated statistical shifts in the response. Crucially, the learning framework is data-source agnostic: the paired wave--motion time series can be obtained from controlled experiments (e.g., towing-tank or basin tests with wave probes and motion tracking) when a hull exists, or from high-fidelity simulations during design when experiments are not yet available. To provide a controlled severe-sea demonstration, we generate training data with a URANS numerical wave tank, using long-crested irregular seas synthesized from a modified Pierson--Moskowitz spectrum. The demonstration dataset comprises 49 random-phase realizations for each of three sea states, simulated at a fixed forward speed selected to yield encounter conditions under which parametric-roll episodes can occur. A stacked LSTM surrogate is trained on wave-elevation time series and evaluated on held-out realizations using time-domain accuracy and distributional fidelity metrics. In the most severe case, the model tracks the onset and growth of large-amplitude roll consistent with parametric excitation, and captures the corresponding changes in roll probability density functions (PDFs). We further compare loss-function choices (MSE, relative-entropy-based objectives, and amplitude-weighted variants) and show how they trade average error for improved tail fidelity relevant to operability and risk assessment.
### Title:
          Scaling Recurrence-aware Foundation Models for Clinical Records via Next-Visit Prediction
 - **Authors:** Haresh Rengaraj Rajamohan, Xiang Gao, Weicheng Zhu, Shih-Lun Huang, Long Chen, Gabe Schulman, Huizhen Jin, Shengduo Li, Yixuan Wang, Huidi Yang, Kyunghyun Cho, Cem M. Deniz, Narges Razavian
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While large-scale pretraining has revolutionized language modeling, its potential remains underexplored in healthcare with structured electronic health records (EHRs). We present RAVEN, a novel generative pretraining strategy for sequential EHR data based on Recurrence-Aware next-Visit EveNt prediction. Leveraging a dataset of over one million unique individuals, our model learns to autoregressively generate tokenized clinical events for the next visit conditioned on patient history. We introduce regularization on predicting repeated events and highlight a key pitfall in EHR-based foundation model evaluations: repeated event tokens can inflate performance metrics when new onsets are not distinguished from subsequent occurrences. Furthermore, we empirically investigate the scaling behaviors in a data-constrained, compute-saturated regime, showing that simply increasing model size is suboptimal without commensurate increases in data volume. We evaluate our model via zero-shot prediction for forecasting the incidence of a diverse set of diseases, where it rivals fully fine-tuned representation-based Transformer models and outperforms widely used simulation-based next-token approaches. Finally, without additional parameter updates, we show that RAVEN can generalize to an external patient cohort under lossy clinical code mappings and feature coverage gaps.
### Title:
          TAG: Target-Agnostic Guidance for Stable Object-Centric Inference in Vision-Language-Action Models
 - **Authors:** Jiaying Zhou, Zhihao Zhan, Ruifeng Zhai, Qinhan Lyu, Hao Liu, Keze Wang, Liang Lin, Guangrun Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision--Language--Action (VLA) policies have shown strong progress in mapping language instructions and visual observations to robotic actions, yet their reliability degrades in cluttered scenes with distractors. By analyzing failure cases, we find that many errors do not arise from infeasible motions, but from instance-level grounding failures: the policy often produces a plausible grasp trajectory that lands slightly off-target or even on the wrong object instance. To address this issue, we propose TAG (Target-Agnostic Guidance), a simple inference-time guidance mechanism that explicitly reduces distractor- and appearance-induced bias in VLA policies. Inspired by classifier-free guidance (CFG), TAG contrasts policy predictions under the original observation and an object-erased observation, and uses their difference as a residual steering signal that strengthens the influence of object evidence in the decision process. TAG does not require modifying the policy architecture and can be integrated with existing VLA policies with minimal training and inference changes. We evaluate TAG on standard manipulation benchmarks, including LIBERO, LIBERO-Plus, and VLABench, where it consistently improves robustness under clutter and reduces near-miss and wrong-object executions.
## Keyword: localization
### Title:
          High-Fidelity Face Content Recovery via Tamper-Resilient Versatile Watermarking
 - **Authors:** Peipeng Yu, Jinfeng Xie, Chengfu Ou, Xiaoyu Zhou, Jianwei Fei, Yunshu Dai, Zhihua Xia, Chip Hong Chang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The proliferation of AIGC-driven face manipulation and deepfakes poses severe threats to media provenance, integrity, and copyright protection. Prior versatile watermarking systems typically rely on embedding explicit localization payloads, which introduces a fidelity--functionality trade-off: larger localization signals degrade visual quality and often reduce decoding robustness under strong generative edits. Moreover, existing methods rarely support content recovery, limiting their forensic value when original evidence must be reconstructed. To address these challenges, we present VeriFi, a versatile watermarking framework that unifies copyright protection, pixel-level manipulation localization, and high-fidelity face content recovery. VeriFi makes three key contributions: (1) it embeds a compact semantic latent watermark that serves as an content-preserving prior, enabling faithful restoration even after severe manipulations; (2) it achieves fine-grained localization without embedding localization-specific artifacts by correlating image features with decoded provenance signals; and (3) it introduces an AIGC attack simulator that combines latent-space mixing with seamless blending to improve robustness to realistic deepfake pipelines. Extensive experiments on CelebA-HQ and FFHQ show that VeriFi consistently outperforms strong baselines in watermark robustness, localization accuracy, and recovery quality, providing a practical and verifiable defense for deepfake forensics.
### Title:
          SynMVCrowd: A Large Synthetic Benchmark for Multi-view Crowd Counting and Localization
 - **Authors:** Qi Zhang, Daijie Chen, Yunfei Gong, Hui Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing multi-view crowd counting and localization methods are evaluated under relatively small scenes with limited crowd numbers, camera views, and frames. This makes the evaluation and comparison of existing methods impractical, as small datasets are easily overfit by these methods. To avoid these issues, 3DROM proposes a data augmentation method. Instead, in this paper, we propose a large synthetic benchmark, SynMVCrowd, for more practical evaluation and comparison of multi-view crowd counting and localization tasks. The SynMVCrowd benchmark consists of 50 synthetic scenes with a large number of multi-view frames and camera views and a much larger crowd number (up to 1000), which is more suitable for large-scene multi-view crowd vision tasks. Besides, we propose strong multi-view crowd localization and counting baselines that outperform all comparison methods on the new SynMVCrowd benchmark. Moreover, we prove that better domain transferring multi-view and single-image counting performance could be achieved with the aid of the benchmark on novel new real scenes. As a result, the proposed benchmark could advance the research for multi-view and single-image crowd counting and localization to more practical applications. The codes and datasets are here: this https URL.
### Title:
          HyDRA: Hybrid Domain-Aware Robust Architecture for Heterogeneous Collaborative Perception
 - **Authors:** Minwoo Song, Minhee Kang, Heejin Ahn
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In collaborative perception, an agent's performance can be degraded by heterogeneity arising from differences in model architecture or training data distributions. To address this challenge, we propose HyDRA (Hybrid Domain-Aware Robust Architecture), a unified pipeline that integrates intermediate and late fusion within a domain-aware framework. We introduce a lightweight domain classifier that dynamically identifies heterogeneous agents and assigns them to the late-fusion branch. Furthermore, we propose anchor-guided pose graph optimization to mitigate localization errors inherent in late fusion, leveraging reliable detections from intermediate fusion as fixed spatial anchors. Extensive experiments demonstrate that, despite requiring no additional training, HyDRA achieves performance comparable to state-of-the-art heterogeneity-aware CP methods. Importantly, this performance is maintained as the number of collaborating agents increases, enabling zero-cost scaling without retraining.
### Title:
          Robust and Secure Near-Field Communication via Curved Caustic Beams
 - **Authors:** Shicong Liu, Xianghao Yu, Robert Schober
 - **Subjects:** Subjects:
Information Theory (cs.IT); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Near-field beamfocusing with extremely large aperture arrays can effectively enhance physical layer security. Nevertheless, even small estimation errors of the eavesdropper's location may cause a pronounced focal shift, resulting in a severe degradation of the secrecy rate. In this letter, we propose a physics-informed robust beamforming strategy that leverages the electromagnetic (EM) caustic effect for near-field physical layer security provisioning, which can be implemented via phase shifts only. Specifically, we partition the transmit array into caustic and focusing subarrays to simultaneously bypass the potential eavesdropping region and illuminate the legitimate user, thereby significantly improving the robustness against the localization error of eavesdroppers. Moreover, by leveraging the connection between the phase gradient and the EM wave departing angle, we derive the corresponding piece-wise closed-form array phase profile for the subarrays. Simulation results demonstrate that the proposed scheme achieves up to an 80% reduction of the worst-case eavesdropping rate for a localization error of 0.25 m, highlighting its superiority for providing robust and secure communication.
### Title:
          LaDy: Lagrangian-Dynamic Informed Network for Skeleton-based Action Segmentation via Spatial-Temporal Modulation
 - **Authors:** Haoyu Ji, Xueting Liu, Yu Gao, Wenze Huang, Zhihao Yang, Weihong Ren, Zhiyong Wang, Honghai Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Skeleton-based Temporal Action Segmentation (STAS) aims to densely parse untrimmed skeletal sequences into frame-level action categories. However, existing methods, while proficient at capturing spatio-temporal kinematics, neglect the underlying physical dynamics that govern human motion. This oversight limits inter-class discriminability between actions with similar kinematics but distinct dynamic intents, and hinders precise boundary localization where dynamic force profiles shift. To address these, we propose the Lagrangian-Dynamic Informed Network (LaDy), a framework integrating principles of Lagrangian dynamics into the segmentation process. Specifically, LaDy first computes generalized coordinates from joint positions and then estimates Lagrangian terms under physical constraints to explicitly synthesize the generalized forces. To further ensure physical coherence, our Energy Consistency Loss enforces the work-energy theorem, aligning kinetic energy change with the work done by the net force. The learned dynamics then drive a Spatio-Temporal Modulation module: Spatially, generalized forces are fused with spatial representations to provide more discriminative semantics. Temporally, salient dynamic signals are constructed for temporal gating, thereby significantly enhancing boundary awareness. Experiments on challenging datasets show that LaDy achieves state-of-the-art performance, validating the integration of physical dynamics for action segmentation. Code is available at this https URL.
### Title:
          Combi-CAM: A Novel Multi-Layer Approach for Explainable Image Geolocalization
 - **Authors:** David Faget (CB), José Luis Lisani, Miguel Colom (CB, CMLA)
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Planet-scale photo geolocalization involves the intricate task of estimating the geographic location depicted in an image purely based on its visual features. While deep learning models, particularly convolutional neural networks (CNNs), have significantly advanced this field, understanding the reasoning behind their predictions remains challenging. In this paper, we present Combi-CAM, a novel method that enhances the explainability of CNN-based geolocalization models by combining gradient-weighted class activation maps obtained from several layers of the network architecture, rather than using only information from the deepest layer as is typically done. This approach provides a more detailed understanding of how different image features contribute to the model's decisions, offering deeper insights than the traditional approaches.
### Title:
          Spectral Scalpel: Amplifying Adjacent Action Discrepancy via Frequency-Selective Filtering for Skeleton-Based Action Segmentation
 - **Authors:** Haoyu Ji, Bowen Chen, Zhihao Yang, Wenze Huang, Yu Gao, Xueting Liu, Weihong Ren, Zhiyong Wang, Honghai Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Skeleton-based Temporal Action Segmentation (STAS) seeks to densely segment and classify diverse actions within long, untrimmed skeletal motion sequences. However, existing STAS methodologies face challenges of limited inter-class discriminability and blurred segmentation boundaries, primarily due to insufficient distinction of spatio-temporal patterns between adjacent actions. To address these limitations, we propose Spectral Scalpel, a frequency-selective filtering framework aimed at suppressing shared frequency components between adjacent distinct actions while amplifying their action-specific frequencies, thereby enhancing inter-action discrepancies and sharpening transition boundaries. Specifically, Spectral Scalpel employs adaptive multi-scale spectral filters as scalpels to edit frequency spectra, coupled with a discrepancy loss between adjacent actions serving as the surgical objective. This design amplifies representational disparities between neighboring actions, effectively mitigating boundary localization ambiguities and inter-class confusion. Furthermore, complementing long-term temporal modeling, we introduce a frequency-aware channel mixer to strengthen channel evolution by aggregating spectra across channels. This work presents a novel paradigm for STAS that extends conventional spatio-temporal modeling by incorporating frequency-domain analysis. Extensive experiments on five public datasets demonstrate that Spectral Scalpel achieves state-of-the-art performance. Code is available at this https URL.
### Title:
          AMIF: Authorizable Medical Image Fusion Model with Built-in Authentication
 - **Authors:** Jie Song, Jun Jia, Wei Sun, Wangqiu Zhou, Tao Tan, Guangtao Zhai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal image fusion enables precise lesion localization and characterization for accurate diagnosis, thereby strengthening clinical decision-making and driving its growing prominence in medical imaging research. A powerful multimodal image fusion model relies on high-quality, clinically representative multimodal training data and a rigorously engineered model architecture. Therefore, the development of such professional radiomics models represents a collaborative achievement grounded in standardized acquisition, clinical-specific expertise, and algorithmic design proficiency, which necessitates protection of associated intellectual property rights. However, current multimodal image fusion models generate fused outputs without built-in mechanisms to safeguard intellectual property rights, inadvertently exposing proprietary model knowledge and sensitive training data through inference leakage. For example, malicious users can exploit fusion outputs and model distillation or other inference-based reverse engineering techniques to approximate the fusion performance of proprietary models. To address this issue, we propose AMIF, the first Authorizable Medical Image Fusion model with built-in authentication, which integrates authorization access control into the image fusion objective. For unauthorized usage, AMIF embeds explicit and visible copyright identifiers into fusion results. In contrast, high-quality fusion results are accessible upon successful key-based authentication.
### Title:
          Boosting Document Parsing Efficiency and Performance with Coarse-to-Fine Visual Processing
 - **Authors:** Cheng Cui, Ting Sun, Suyin Liang, Tingquan Gao, Zelun Zhang, Jiaxuan Liu, Xueqing Wang, Changda Zhou, Hongen Liu, Manhui Lin, Yue Zhang, Yubo Zhang, Jing Zhang, Jun Zhang, Xing Wei, Yi Liu, Dianhai Yu, Yanjun Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Document parsing is a fine-grained task where image resolution significantly impacts performance. While advanced research leveraging vision-language models benefits from high-resolution input to boost model performance, this often leads to a quadratic increase in the number of vision tokens and significantly raises computational costs. We attribute this inefficiency to substantial visual regions redundancy in document images, like background. To tackle this, we propose PaddleOCR-VL, a novel coarse-to-fine architecture that focuses on semantically relevant regions while suppressing redundant ones, thereby improving both efficiency and performance. Specifically, we introduce a lightweight Valid Region Focus Module (VRFM) which leverages localization and contextual relationship prediction capabilities to identify valid vision tokens. Subsequently, we design and train a compact yet powerful 0.9B vision-language model (PaddleOCR-VL-0.9B) to perform detailed recognition, guided by VRFM outputs to avoid direct processing of the entire large image. Extensive experiments demonstrate that PaddleOCR-VL achieves state-of-the-art performance in both page-level parsing and element-level recognition. It significantly outperforms existing solutions, exhibits strong competitiveness against top-tier VLMs, and delivers fast inference while utilizing substantially fewer vision tokens and parameters, highlighting the effectiveness of targeted coarse-to-fine parsing for accurate and efficient document understanding. The source code and models are publicly available at this https URL.
### Title:
          PP-OCRv5: A Specialized 5M-Parameter Model Rivaling Billion-Parameter Vision-Language Models on OCR Tasks
 - **Authors:** Cheng Cui, Yubo Zhang, Ting Sun, Xueqing Wang, Hongen Liu, Manhui Lin, Yue Zhang, Tingquan Gao, Changda Zhou, Jiaxuan Liu, Zelun Zhang, Jing Zhang, Jun Zhang, Yi Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The advent of "OCR 2.0" and large-scale vision-language models (VLMs) has set new benchmarks in text recognition. However, these unified architectures often come with significant computational demands, challenges in precise text localization within complex layouts, and a propensity for textual hallucinations. Revisiting the prevailing notion that model scale is the sole path to high accuracy, this paper introduces PP-OCRv5, a meticulously optimized, lightweight OCR system with merely 5 million parameters. We demonstrate that PP-OCRv5 achieves performance competitive with many billion-parameter VLMs on standard OCR benchmarks, while offering superior localization precision and reduced hallucinations. The cornerstone of our success lies not in architectural expansion but in a data-centric investigation. We systematically dissect the role of training data by quantifying three critical dimensions: data difficulty, data accuracy, and data diversity. Our extensive experiments reveal that with a sufficient volume of high-quality, accurately labeled, and diverse data, the performance ceiling for traditional, efficient two-stage OCR pipelines is far higher than commonly assumed. This work provides compelling evidence for the viability of lightweight, specialized models in the large-model era and offers practical insights into data curation for OCR. The source code and models are publicly available at this https URL.
### Title:
          GeoRouter: Dynamic Paradigm Routing for Worldwide Image Geolocalization
 - **Authors:** Pengyue Jia, Derong Xu, Yingyi Zhang, Xiaopeng Li, Wenlin Zhang, Yi Wen, Yuanshao Zhu, Xiangyu Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Worldwide image geolocalization aims to predict precise GPS coordinates for images captured anywhere on Earth, which is challenging due to the large visual and geographic diversity. Recent methods mainly follow two paradigms: retrieval-based approaches that match queries against a reference database, and generation-based approaches that directly predict coordinates using Large Vision-Language Models (LVLMs). However, we observe distinct error profiles between them: retrieval excels at fine-grained instance matching, while generation offers robust semantic reasoning. This complementary heterogeneity suggests that no single paradigm is universally superior. To harness this potential, we propose GeoRouter, a dynamic routing framework that adaptively assigns each query to the optimal paradigm. GeoRouter leverages an LVLM backbone to analyze visual content and provide routing decisions. To optimize GeoRouter, we introduce a distance-aware preference objective that converts the distance gap between paradigms into a continuous supervision signal, explicitly reflecting relative performance differences. Furthermore, we construct GeoRouting, the first large-scale dataset tailored for training routing policies with independent paradigm predictions. Extensive experiments on IM2GPS3k and YFCC4k demonstrate that GeoRouter significantly outperforms state-of-the-art baselines.
### Title:
          Boosting LLMs for Mutation Generation
 - **Authors:** Bo Wang, Ming Deng, Mingda Chen, Chengran Yang, Youfang Lin, Mark Harman, Mike Papadakis, Jie M. Zhang
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLM-based mutation testing is a promising testing technology, but existing approaches typically rely on a fixed set of mutations as few-shot examples or none at all. This can result in generic low-quality mutations, missed context-specific mutation patterns, substantial numbers of redundant and uncompilable mutants, and limited semantic similarity to real bugs. To overcome these limitations, we introduce SMART (Semantic Mutation with Adaptive Retrieval and Tuning). SMART integrates retrieval-augmented generation (RAG) on a vectorized dataset of real-world bugs, focused code chunking, and supervised fine-tuning using mutations coupled with real-world bugs. We conducted an extensive empirical study of SMART using 1,991 real-world Java bugs from the Defects4J and ConDefects datasets, comparing SMART to the state-of-the-art LLM-based approaches, LLMut and LLMorpheus. The results reveal that SMART substantially improves mutation validity, effectiveness, and efficiency (even enabling small-scale 7B-scale models to match or even surpass large models like GPT-4o). We also demonstrate that SMART significantly improves downstream software engineering applications, including test case prioritization and fault localization. More specifically, SMART improves validity (weighted average generation rate) from 42.89% to 65.6%. It raises the non-duplicate rate from 87.38% to 95.62%, and the compilable rate from 88.85% to 90.21%. In terms of effectiveness, it achieves a real bug detection rate of 92.61% (vs. 57.86% for LLMut) and improves the average Ochiai coefficient from 25.61% to 38.44%. For fault localization, SMART ranks 64 more bugs as Top-1 under MUSE and 57 more under Metallaxis.
## Keyword: transformer
### Title:
          Not All Pretraining are Created Equal: Threshold Tuning and Class Weighting for Imbalanced Polarization Tasks in Low-Resource Settings
 - **Authors:** Abass Oguntade
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper describes my submission to the Polarization Shared Task at SemEval-2025, which addresses polarization detection and classification in social media text. I develop Transformer-based systems for English and Swahili across three subtasks: binary polarization detection, multi-label target type classification, and multi-label manifestation identification. The approach leverages multilingual and African language-specialized models (mDeBERTa-v3-base, SwahBERT, AfriBERTa-large), class-weighted loss functions, iterative stratified data splitting, and per-label threshold tuning to handle severe class imbalance. The best configuration, mDeBERTa-v3-base, achieves 0.8032 macro-F1 on validation for binary detection, with competitive performance on multi-label tasks (up to 0.556 macro-F1). Error analysis reveals persistent challenges with implicit polarization, code-switching, and distinguishing heated political discourse from genuine polarization.
### Title:
          StateLinFormer: Stateful Training Enhancing Long-term Memory in Navigation
 - **Authors:** Zhiyuan Chen, Yuxuan Zhong, Fan Wang, Bo Yu, Pengtao Shao, Shaoshan Liu, Ning Ding
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Effective navigation intelligence relies on long-term memory to support both immediate generalization and sustained adaptation. However, existing approaches face a dilemma: modular systems rely on explicit mapping but lack flexibility, while Transformer-based end-to-end models are constrained by fixed context windows, limiting persistent memory across extended interactions. We introduce StateLinFormer, a linear-attention navigation model trained with a stateful memory mechanism that preserves recurrent memory states across consecutive training segments instead of reinitializing them at each batch boundary. This training paradigm effectively approximates learning on infinitely long sequences, enabling the model to achieve long-horizon memory retention. Experiments across both MAZE and ProcTHOR environments demonstrate that StateLinFormer significantly outperforms its stateless linear-attention counterpart and standard Transformer baselines with fixed context windows. Notably, as interaction length increases, persistent stateful training substantially improves context-dependent adaptation, suggesting an enhancement in the model's In-Context Learning (ICL) capabilities for navigation tasks.
### Title:
          M3T: Discrete Multi-Modal Motion Tokens for Sign Language Production
 - **Authors:** Alexandre Symeonidis-Herzig, Jianhe Low, Ozge Mercanoglu Sincan, Richard Bowden
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sign language production requires more than hand motion generation. Non-manual features, including mouthings, eyebrow raises, gaze, and head movements, are grammatically obligatory and cannot be recovered from manual articulators alone. Existing 3D production systems face two barriers to integrating them: the standard body model provides a facial space too low-dimensional to encode these articulations, and when richer representations are adopted, standard discrete tokenization suffers from codebook collapse, leaving most of the expression space unreachable. We propose SMPL-FX, which couples FLAME's rich expression space with the SMPL-X body, and tokenize the resulting representation with modality-specific Finite Scalar Quantization VAEs for body, hands, and face. M3T is an autoregressive transformer trained on this multi-modal motion vocabulary, with an auxiliary translation objective that encourages semantically grounded embeddings. Across three standard benchmarks (How2Sign, CSL-Daily, Phoenix14T) M3T achieves state-of-the-art sign language production quality, and on NMFs-CSL, where signs are distinguishable only by non-manual features, reaches 58.3% accuracy against 49.0% for the strongest comparable pose baseline.
### Title:
          The Diminishing Returns of Early-Exit Decoding in Modern LLMs
 - **Authors:** Rui Wei, Rui Du, Hanfei Yu, Devesh Tiwari, Jian Li, Zhaozhuo Xu, Hao Wang
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In Large Language Model (LLM) inference, early-exit refers to stopping computation at an intermediate layer once the prediction is sufficiently confident, thereby reducing latency and cost. However, recent LLMs adopt improved pretraining recipes and architectures that reduce layer redundancy, potentially limiting early-exit opportunities. We re-evaluate layer-wise early-exit in modern LLMs and analyze how intermediate representations evolve during training. We introduce a metric to quantify a model's intrinsic suitability for early-exit and propose a benchmark for researchers to explore the potential early-exit benefits on different models and workloads. Our results show a diminishing trend in early-exit effectiveness across newer model generations. We further find that dense transformers generally offer greater early-exit potential than Mixture-of-Experts and State Space Models. In addition, larger models, particularly those with more than 20 billion parameters, and base pretrained models without specialized tuning tend to exhibit higher early-exit potential.
### Title:
          Mind the Hitch: Dynamic Calibration and Articulated Perception for Autonomous Trucks
 - **Authors:** Morui Zhu, Yongqi Zhu, Song Fu, Qing Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous trucking poses unique challenges due to articulated tractor-trailer geometry, and time-varying sensor poses caused by the fifth-wheel joint and trailer flex. Existing perception and calibration methods assume static baselines or rely on high-parallax and texture-rich scenes, limiting their reliability under real-world settings. We propose dCAP (dynamic Calibration and Articulated Perception), a vision-based framework that continuously estimates the 6-DoF (degree of freedom) relative pose between tractor and trailer cameras. dCAP employs a transformer with cross-view and temporal attention to robustly aggregate spatial cues while maintaining temporal consistency, enabling accurate perception under rapid articulation and occlusion. Integrated with BEVFormer, dCAP improves 3D object detection by replacing static calibration with dynamically predicted extrinsics. To facilitate evaluation, we introduce STT4AT, a CARLA-based benchmark simulating semi-trailer trucks with synchronized multi-sensor suites and time-varying inter-rig geometry across diverse environments. Experiments demonstrate that dCAP achieves stable, accurate perception while addressing the limitations of static calibration in autonomous trucking. The dataset, development kit, and source code will be publicly released.
### Title:
          Learning Cross-Joint Attention for Generalizable Video-Based Seizure Detection
 - **Authors:** Omar Zamzam, Takfarinas Medani, Chinmay Chinara, Richard Leahy
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated seizure detection from long-term clinical videos can substantially reduce manual review time and enable real-time monitoring. However, existing video-based methods often struggle to generalize to unseen subjects due to background bias and reliance on subject-specific appearance cues. We propose a joint-centric attention model that focuses exclusively on body dynamics to improve cross-subject generalization. For each video segment, body joints are detected and joint-centered clips are extracted, suppressing background context. These joint-centered clips are tokenized using a Video Vision Transformer (ViViT), and cross-joint attention is learned to model spatial and temporal interactions between body parts, capturing coordinated movement patterns characteristic of seizure semiology. Extensive cross-subject experiments show that the proposed method consistently outperforms state-of-the-art CNN-, graph-, and transformer-based approaches on unseen subjects.
### Title:
          Latent Algorithmic Structure Precedes Grokking: A Mechanistic Study of ReLU MLPs on Modular Arithmetic
 - **Authors:** Anand Swaroop
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Grokking-the phenomenon where validation accuracy of neural networks on modular addition of two integers rises long after training data has been memorized-has been characterized in previous works as producing sinusoidal input weight distributions in transformers and multi-layer perceptrons (MLPs). We find empirically that ReLU MLPs in our experimental setting instead learn near-binary square wave input weights, where intermediate-valued weights appear exclusively near sign-change boundaries, alongside output weight distributions whose dominant Fourier phases satisfy a phase-sum relation $\phi_{\mathrm{out}} = \phi_a + \phi_b$; this relation holds even when the model is trained on noisy data and fails to grok. We extract the frequency and phase of each neuron's weights via DFT and construct an idealized MLP: Input weights are replaced by perfect binary square waves and output weights by cosines, both parametrized by the frequencies, phases, and amplitudes extracted from the dominant Fourier components of the real model weights. This idealized model achieves 95.5% accuracy when the frequencies and phases are extracted from the weights of a model trained on noisy data that itself achieves only 0.23% accuracy. This suggests that grokking does not discover the correct algorithm, but rather sharpens an algorithm substantially encoded during memorization, progressively binarizing the input weights into cleaner square waves and aligning the output weights, until generalization becomes possible.
### Title:
          Circuit Complexity of Hierarchical Knowledge Tracing and Implications for Log-Precision Transformers
 - **Authors:** Naiming Liu, Richard Baraniuk, Shashank Sonkar
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Knowledge tracing models mastery over interconnected concepts, often organized by prerequisites. We analyze hierarchical prerequisite propagation through a circuit-complexity lens to clarify what is provable about transformer-style computation on deep concept hierarchies. Using recent results that log-precision transformers lie in logspace-uniform $\mathsf{TC}^0$, we formalize prerequisite-tree tasks including recursive-majority mastery propagation. Unconditionally, recursive-majority propagation lies in $\mathsf{NC}^1$ via $O(\log n)$-depth bounded-fanin circuits, while separating it from uniform $\mathsf{TC}^0$ would require major progress on open lower bounds. Under a monotonicity restriction, we obtain an unconditional barrier: alternating ALL/ANY prerequisite trees yield a strict depth hierarchy for \emph{monotone} threshold circuits. Empirically, transformer encoders trained on recursive-majority trees converge to permutation-invariant shortcuts; explicit structure alone does not prevent this, but auxiliary supervision on intermediate subtrees elicits structure-dependent computation and achieves near-perfect accuracy at depths 3--4. These findings motivate structure-aware objectives and iterative mechanisms for prerequisite-sensitive knowledge tracing on deep hierarchies.
### Title:
          When AI output tips to bad but nobody notices: Legal implications of AI's mistakes
 - **Authors:** Dylan J. Restrepo, Nicholas J. Restrepo, Frank Y. Huo, Neil F. Johnson
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computers and Society (cs.CY); Social and Information Networks (cs.SI); Chaotic Dynamics (nlin.CD); Physics and Society (physics.soc-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The adoption of generative AI across commercial and legal professions offers dramatic efficiency gains -- yet for law in particular, it introduces a perilous failure mode in which the AI fabricates fictitious case law, statutes, and judicial holdings that appear entirely authentic. Attorneys who unknowingly file such fabrications face professional sanctions, malpractice exposure, and reputational harm, while courts confront a novel threat to the integrity of the adversarial process. This failure mode is commonly dismissed as random `hallucination', but recent physics-based analysis of the Transformer's core mechanism reveals a deterministic component: the AI's internal state can cross a calculable threshold, causing its output to flip from reliable legal reasoning to authoritative-sounding fabrication. Here we present this science in a legal-industry setting, walking through a simulated brief-drafting scenario. Our analysis suggests that fabrication risk is not an anomalous glitch but a foreseeable consequence of the technology's design, with direct implications for the evolving duty of technological competence. We propose that legal professionals, courts, and regulators replace the outdated `black box' mental model with verification protocols based on how these systems actually fail.
### Title:
          ORACLE: Orchestrate NPC Daily Activities using Contrastive Learning with Transformer-CVAE
 - **Authors:** Seong-Eun Hong, JuYeong Hwang, RyunHa Lee, HyeongYeop Kang
 - **Subjects:** Subjects:
Graphics (cs.GR); Computation and Language (cs.CL); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The integration of Non-player characters (NPCs) within digital environments has been increasingly recognized for its potential to augment user immersion and cognitive engagement. The sophisticated orchestration of their daily activities, reflecting the nuances of human daily routines, contributes significantly to the realism of digital environments. Nevertheless, conventional approaches often produce monotonous repetition, falling short of capturing the intricacies of real human activity plans. In response to this, we introduce ORACLE, a novel generative model for the synthesis of realistic indoor daily activity plans, ensuring NPCs' authentic presence in digital habitats. Exploiting the CASAS smart home dataset's 24-hour indoor activity sequences, ORACLE addresses challenges in the dataset, including its imbalanced sequential data, the scarcity of training samples, and the absence of pre-trained models encapsulating human daily activity patterns. ORACLE's training leverages the sequential data processing prowess of Transformers, the generative controllability of Conditional Variational Autoencoders (CVAE), and the discriminative refinement of contrastive learning. Our experimental results validate the superiority of generating NPC activity plans and the efficacy of our design strategies over existing methods.
### Title:
          Sparse Growing Transformer: Training-Time Sparse Depth Allocation via Progressive Attention Looping
 - **Authors:** Yao Chen, Yilong Chen, Yinqi Yang, Junyuan Shang, Zhenyu Zhang, Zefeng Zhang, Shuaiyi Nie, Shuohuan Wang, Yu Sun, Hua Wu, HaiFeng Wang, Tingwen Liu
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing approaches to increasing the effective depth of Transformers predominantly rely on parameter reuse, extending computation through recursive execution. Under this paradigm, the network structure remains static along the training timeline, and additional computational depth is uniformly assigned to entire blocks at the parameter level. This rigidity across training time and parameter space leads to substantial computational redundancy during training. In contrast, we argue that depth allocation during training should not be a static preset, but rather a progressively growing structural process. Our systematic analysis reveals a deep-to-shallow maturation trajectory across layers, where high-entropy attention heads play a crucial role in semantic integration. Motivated by this observation, we introduce the Sparse Growing Transformer (SGT). SGT is a training-time sparse depth allocation framework that progressively extends recurrence from deeper to shallower layers via targeted attention looping on informative heads. This mechanism induces structural sparsity by selectively increasing depth only for a small subset of parameters as training evolves. Extensive experiments across multiple parameter scales demonstrate that SGT consistently outperforms training-time static block-level looping baselines under comparable settings, while reducing the additional training FLOPs overhead from approximately 16--20% to only 1--3% relative to a standard Transformer backbone.
### Title:
          DB SwinT: A Dual-Branch Swin Transformer Network for Road Extraction in Optical Remote Sensing Imagery
 - **Authors:** Zongyang He, Xiangli Yang, Xian Gao, Zhiguo Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the continuous improvement in the spatial resolution of optical remote sensing imagery, accurate road extraction has become increasingly important for applications such as urban planning, traffic monitoring, and disaster management. However, road extraction in complex urban and rural environments remains challenging, as roads are often occluded by trees, buildings, and other objects, leading to fragmented structures and reduced extraction accuracy. To address this problem, this paper proposes a Dual-Branch Swin Transformer network (DB SwinT) for road extraction. The proposed framework combines the long-range dependency modeling capability of the Swin Transformer with the multi-scale feature fusion strategy of U-Net, and employs a dual-branch encoder to learn complementary local and global representations. Specifically, the local branch focuses on recovering fine structural details in occluded areas, while the global branch captures broader semantic context to preserve the overall continuity of road networks. In addition, an Attentional Feature Fusion (AFF) module is introduced to adaptively fuse features from the two branches, further enhancing the representation of occluded road segments. Experimental results on the Massachusetts and DeepGlobe datasets show that DB SwinT achieves Intersection over Union (IoU) scores of 79.35\% and 74.84\%, respectively, demonstrating its effectiveness for road extraction from optical remote sensing imagery.
### Title:
          LGEST: Dynamic Spatial-Spectral Expert Routing for Hyperspectral Image Classification
 - **Authors:** Jiawen Wen, Suixuan Qiu, Zihang Luo, Xiaofei Yang, Haotian Shi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning methods, including Convolutional Neural Networks, Transformers and Mamba, have achieved remarkable success in hyperspectral image (HSI) classification. Nevertheless, existing methods exhibit inflexible integration of local-global representations, inadequate handling of spectral-spatial scale disparities across heterogeneous bands, and susceptibility to the Hughes phenomenon under high-dimensional sample heterogeneity. To address these challenges, we propose Local-Global Expert Spatial-Spectral Transformer (LGEST), a novel framework that synergistically combines three key innovations. The LGEST first employs a Deep Spatial-Spectral Autoencoder (DSAE) to generate compact yet discriminative embeddings through hierarchical nonlinear compression, preserving 3D neighborhood coherence while mitigating information loss in high-dimensional spaces. Secondly, a Cross-Interactive Mixed Expert Feature Pyramid (CIEM-FPN) leverages cross-attention mechanisms and residual mixture-of-experts layers to dynamically fuse multi-scale features, adaptively weighting spectral discriminability and spatial saliency through learnable gating functions. Finally, a Local-Global Expert System (LGES) processes decomposed features via sparsely activated expert pairs: convolutional sub-experts capture fine-grained textures, while transformer sub-experts model long-range contextual dependencies, with a routing controller dynamically selecting experts based on real-time feature saliency. Extensive experiments on four benchmark datasets demonstrate that LGEST consistently outperforms state-of-the-art methods.
### Title:
          Beyond Semantic Priors: Mitigating Optimization Collapse for Generalizable Visual Forensics
 - **Authors:** Jipeng Liu, Haichao Shi, Siyu Xing, Rong Yin, Xiao-Yu Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Vision-Language Models (VLMs) like CLIP have emerged as a dominant paradigm for generalizable deepfake detection, a representational disconnect remains: their semantic-centric pre-training is ill-suited for capturing non-semantic artifacts inherent to hyper-realistic synthesis. In this work, we identify a failure mode termed Optimization Collapse, where detectors trained with Sharpness-Aware Minimization (SAM) degenerate to random guessing on non-semantic forgeries once the perturbation radius exceeds a narrow threshold. To theoretically formalize this collapse, we propose the Critical Optimization Radius (COR) to quantify the geometric stability of the optimization landscape, and leverage the Gradient Signal-to-Noise Ratio (GSNR) to measure generalization potential. We establish a theorem proving that COR increases monotonically with GSNR, thereby revealing that the geometric instability of SAM optimization originates from degraded intrinsic generalization potential. This result identifies the layer-wise attenuation of GSNR as the root cause of Optimization Collapse in detecting non-semantic forgeries. Although naively reducing perturbation radius yields stable convergence under SAM, it merely treats the symptom without mitigating the intrinsic generalization degradation, necessitating enhanced gradient fidelity. Building on this insight, we propose the Contrastive Regional Injection Transformer (CoRIT), which integrates a computationally efficient Contrastive Gradient Proxy (CGP) with three training-free strategies: Region Refinement Mask to suppress CGP variance, Regional Signal Injection to preserve CGP magnitude, and Hierarchical Representation Integration to attain more generalizable representations. Extensive experiments demonstrate that CoRIT mitigates optimization collapse and achieves state-of-the-art generalization across cross-domain and universal forgery benchmarks.
### Title:
          A Low Cost Discrete Digital Isolator Circuit
 - **Authors:** Thomas Conway
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work presents a fully discrete, low cost digital isolator requiring no specialized ICs and implemented entirely with general purpose transistors and a two layer PCB embedded air core transformer. The design avoids vendor lock in and long term component obsolescence risks, while providing >1 kV isolation, ~200 ns propagation delay, and validated NRZ data rates of 1 Mbps. A modified dual oscillator architecture enables inherent hardware lockout suitable for half bridge gate driver applications. Measured performance and PCB layout guidelines are provided.
### Title:
          Reservoir-Based Graph Convolutional Networks
 - **Authors:** Mayssa Soussia, Gita Ayu Salsabila, Mohamed Ali Mahjoub, Islem Rekik
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Message passing is a core mechanism in Graph Neural Networks (GNNs), enabling the iterative update of node embeddings by aggregating information from neighboring nodes. Graph Convolutional Networks (GCNs) exemplify this approach by adapting convolutional operations for graph structures, allowing features from adjacent nodes to be combined effectively. However, GCNs encounter challenges with complex or dynamic data. Capturing long-range dependencies often requires deeper layers, which not only increase computational costs but also lead to over-smoothing, where node embeddings become indistinguishable. To overcome these challenges, reservoir computing has been integrated into GNNs, leveraging iterative message-passing dynamics for stable information propagation without extensive parameter tuning. Despite its promise, existing reservoir-based models lack structured convolutional mechanisms, limiting their ability to accurately aggregate multi-hop neighborhood information. To address these limitations, we propose RGC-Net (Reservoir-based Graph Convolutional Network), which integrates reservoir dynamics with structured graph convolution. Key contributions include: (i) a reimagined convolutional framework with fixed random reservoir weights and a leaky integrator to enhance feature retention; (ii) a robust, adaptable model for graph classification; and (iii) an RGC-Net-powered transformer for graph generation with application to dynamic brain connectivity. Extensive experiments show that RGC-Net achieves state-of-the-art performance in classification and generative tasks, including brain graph evolution, with faster convergence and reduced over-smoothing. Source code is available at this https URL .
### Title:
          A visual observation on the geometry of UMAP projections of the difference vectors of antonym and synonym word pair embeddings
 - **Authors:** Rami Luisto
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Antonyms, or opposites, are sometimes defined as \emph{word pairs that have all of the same contextually relevant properties but one}. Seeing how transformer models seem to encode concepts as directions, this begs the question if one can detect ``antonymity'' in the geometry of the embedding vectors of word pairs, especially based on their difference vectors. Such geometrical studies are then naturally contrasted by comparing antonymic pairs to their opposites; synonyms. This paper started as an exploratory project on the complexity of the systems needed to detect the geometry of the embedding vectors of antonymic word pairs. What we now report is a curious ``swirl'' that appears across embedding models in a somewhat specific projection configuration.
### Title:
          Goal-Oriented Reactive Simulation for Closed-Loop Trajectory Prediction
 - **Authors:** Harsh Yadav, Tobias Meisen
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current trajectory prediction models are primarily trained in an open-loop manner, which often leads to covariate shift and compounding errors when deployed in real-world, closed-loop settings. Furthermore, relying on static datasets or non-reactive log-replay simulators severs the interactive loop, preventing the ego agent from learning to actively negotiate surrounding traffic. In this work, we propose an on-policy closed-loop training paradigm optimized for high-frequency, receding horizon ego prediction. To ground the ego prediction in a realistic representation of traffic interactions and to achieve reactive consistency, we introduce a goal-oriented, transformer-based scene decoder, resulting in an inherently reactive training simulation. By exposing the ego agent to a mixture of open-loop data and simulated, self-induced states, the model learns recovery behaviors to correct its own execution errors. Extensive evaluation demonstrates that closed-loop training significantly enhances collision avoidance capabilities at high replanning frequencies, yielding relative collision rate reductions of up to 27.0% on nuScenes and 79.5% in dense DeepScenario intersections compared to open-loop baselines. Additionally, we show that a hybrid simulation combining reactive with non-reactive surrounding agents achieves optimal balance between immediate interactivity and long-term behavioral stability.
### Title:
          IPatch: A Multi-Resolution Transformer Architecture for Robust Time-Series Forecasting
 - **Authors:** Aymane Harkati, Moncef Garouani, Olivier Teste, Julien Aligon, Mohamed Hamlich
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate forecasting of multivariate time series remains challenging due to the need to capture both short-term fluctuations and long-range temporal dependencies. Transformer-based models have emerged as a powerful approach, but their performance depends critically on the representation of temporal data. Traditional point-wise representations preserve individual time-step information, enabling fine-grained modeling, yet they tend to be computationally expensive and less effective at modeling broader contextual dependencies, limiting their scalability to long sequences. Patch-wise representations aggregate consecutive steps into compact tokens to improve efficiency and model local temporal dynamics, but they often discard fine-grained temporal details that are critical for accurate predictions in volatile or complex time series. We propose IPatch, a multi-resolution Transformer architecture that integrates both point-wise and patch-wise tokens, modeling temporal information at multiple resolutions. Experiments on 7 benchmark datasets demonstrate that IPatch consistently improves forecasting accuracy, robustness to noise, and generalization across various prediction horizons compared to single-representation baselines.
### Title:
          UniScale: Synergistic Entire Space Data and Model Scaling for Search Ranking
 - **Authors:** Liren Yu, Caiyuan Li, Feiyi Dong, Tao Zhang, Zhixuan Zhang, Dan Ou, Haihong Tang, Bo Zheng
 - **Subjects:** Subjects:
Information Retrieval (cs.IR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in Large Language Models (LLMs) have inspired a surge of scaling law research in industrial search, advertising, and recommendation systems. However, existing approaches focus mainly on architectural improvements, overlooking the critical synergy between data and architecture design. We observe that scaling model parameters alone exhibits diminishing returns, i.e., the marginal gain in performance steadily declines as model size increases, and that the performance degradation caused by complex heterogeneous data distributions is often irrecoverable through model design alone. In this paper, we propose UniScale to address these limitation, a novel co-design framework that jointly optimizes data and architecture to unlock the full potential of model scaling, which includes two core parts: (1) ES$^3$ (Entire-Space Sample System), a high-quality data scaling system that expands the training signal beyond conventional sampling strategies from both intra-domain request contexts with global supervised signal constructed by hierarchical label attribution and cross-domain samples aligning with the essence of user decision under similar content exposure environment in search domain; and (2) HHSFT (Heterogeneous Hierarchical Sample Fusion Transformer), a novel architecture designed to effectively model the complex heterogeneous distribution of scaled data and to harness the entire space user behavior data with Heterogeneous Hierarchical Feature Interaction and Entire Space User Interest Fusion, thereby surpassing the performance ceiling of structure-only model tuning. Extensive experiments on large-scale real world E-commerce search platform demonstrate that UniScale achieves significant improvements through the synergistic co-design of data and architecture and exhibits clear scaling trends, delivering substantial gains in key business metrics.
### Title:
          Accelerating Diffusion-based Video Editing via Heterogeneous Caching: Beyond Full Computing at Sampled Denoising Timestep
 - **Authors:** Tianyi Liu, Ye Lu, Linfeng Zhang, Chen Cai, Jianjun Gao, Yi Wang, Kim-Hui Yap, Lap-Pui Chau
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion-based video editing has emerged as an important paradigm for high-quality and flexible content generation. However, despite their generality and strong modeling capacity, Diffusion Transformers (DiT) remain computationally expensive due to the iterative denoising process, posing challenges for practical deployment. Existing video diffusion acceleration methods primarily exploit denoising timestep-level feature reuse, which mitigates the redundancy in denoising process, but overlooks the architectural redundancy within the DiT that many attention operations over spatio-temporal tokens are redundantly executed, offering little to no incremental contribution to the model output. This work introduces HetCache, a training-free diffusion acceleration framework designed to exploit the inherent heterogeneity in diffusion-based masked video-to-video (MV2V) generation and editing. Instead of uniformly reuse or randomly sampling tokens, HetCache assesses the contextual relevance and interaction strength among various types of tokens in designated computing steps. Guided by spatial priors, it divides the spatial-temporal tokens in DiT model into context and generative tokens, and selectively caches the context tokens that exhibit the strongest correlation and most representative semantics with generative ones. This strategy reduces redundant attention operations while maintaining editing consistency and fidelity. Experiments show that HetCache achieves a noticeable acceleration, including a 2.67$\times$ latency speedup and FLOPs reduction over commonly used foundation models, with negligible degradation in editing quality.
### Title:
          DeepDTF: Dual-Branch Transformer Fusion for Multi-Omics Anticancer Drug Response Prediction
 - **Authors:** Yuhan Zhao, Jacob Tennant, James Yang, Zhishan Guo, Young Whang, Ning Sui
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cancer drug response varies widely across tumors due to multi-layer molecular heterogeneity, motivating computational decision support for precision oncology. Despite recent progress in deep CDR models, robust alignment between high-dimensional multi-omics and chemically structured drugs remains challenging due to cross-modal misalignment and limited inductive bias. We present DeepDTF, an end-to-end dual-branch Transformer fusion framework for joint log(IC50) regression and drug sensitivity classification. The cell-line branch uses modality-specific encoders for multi-omics profiles with Transformer blocks to capture long-range dependencies, while the drug branch represents compounds as molecular graphs and encodes them with a GNN-Transformer to integrate local topology with global context. Omics and drug representations are fused by a Transformer-based module that models cross-modal interactions and mitigates feature misalignment. On public pharmacogenomic benchmarks under 5-fold cold-start cell-line evaluation, DeepDTF consistently outperforms strong baselines across omics settings, achieving up to RMSE=1.248, R^2=0.875, and AUC=0.987 with full multi-omics inputs, while reducing classification error (1-ACC) by 9.5%. Beyond accuracy, DeepDTF provides biologically grounded explanations via SHAP-based gene attributions and pathway enrichment with pre-ranked GSEA.
### Title:
          Le MuMo JEPA: Multi-Modal Self-Supervised Representation Learning with Learnable Fusion Tokens
 - **Authors:** Ciem Cornelissen, Sam Leroux, Pieter Simoens
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-supervised learning has emerged as a powerful paradigm for learning visual representations without manual annotations, yet most methods still operate on a single modality and therefore miss the complementary structure available from heterogeneous sensors. We present Le MuMo JEPA, a self-supervised framework that learns unified representations from RGB images and aligned companion modalities. In our driving experiments, the second modality is camera-aligned LiDAR depth; we also evaluate RGB-thermal training and transfer on the Teledyne FLIR ADAS benchmark. Our approach extends LeJEPA to the multi-modal setting by learning fusion tokens that act as a latent bottleneck between modality-specific patch stems inside a shared transformer. Our default model employs a pruned fusion strategy: after an initial cross-modal attention layer, modality-specific tokens are dropped, forcing cross-modal information into the shared fusion-token grid as an efficient latent bottleneck before Sketched Isotropic Gaussian Regularization (SIGReg) is applied to the joint multimodal CLS embedding. On Waymo, Le MuMo JEPA gives the strongest performance-efficiency trade-off on downstream patch probes among the from-scratch multimodal baselines, improving CenterNet detection and dense depth while remaining competitive on segmentation. Under from-scratch training on nuScenes, Le MuMo JEPA remains the strongest model, and it also gives the best FLIR results, especially after Waymo-initialized fine-tuning. It also retains the best overall accuracy-efficiency balance in our study at substantially lower compute, memory, and estimated training time.
### Title:
          The role of spatial context and multitask learning in the detection of organic and conventional farming systems based on Sentinel-2 time series
 - **Authors:** Jan Hemmerling, Marcel Schwieder, Philippe Rufin, Leon-Friedrich Thomas, Mirela Tulbure, Patrick Hostert, Stefan Erasmi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Organic farming is a key element in achieving more sustainable agriculture. For a better understanding of the development and impact of organic farming, comprehensive, spatially explicit information is needed. This study presents an approach for the discrimination of organic and conventional farming systems using intra-annual Sentinel-2 time series. In addition, it examines two factors influencing this discrimination: the joint learning of crop type information in a concurrent task and the role of spatial context. A Vision Transformer model based on the Temporo-Spatial Vision Transformer (TSViT) architecture was used to construct a classification model for the two farming systems. The model was extended for simultaneous learning of the crop type, creating a multitask learning setting. By varying the patch size presented to the model, we tested the influence of spatial context on the classification accuracy of both tasks. We show that discrimination between organic and conventional farming systems using multispectral remote sensing data is feasible. However, classification performance varies substantially across crop types. For several crops, such as winter rye, winter wheat, and winter oat, F1 scores of 0.8 or higher can be achieved. In contrast, other agricultural land use classes, such as permanent grassland, orchards, grapevines, and hops, cannot be reliably distinguished, with F1 scores for the organic management class of 0.4 or lower. Joint learning of farming system and crop type provides only limited additional benefits over single-task learning. In contrast, incorporating wider spatial context improves the performance of both farming system and crop type classification. Overall, we demonstrate that a classification of agricultural farming systems is possible in a diverse agricultural region using multispectral remote sensing data.
### Title:
          Scaling Recurrence-aware Foundation Models for Clinical Records via Next-Visit Prediction
 - **Authors:** Haresh Rengaraj Rajamohan, Xiang Gao, Weicheng Zhu, Shih-Lun Huang, Long Chen, Gabe Schulman, Huizhen Jin, Shengduo Li, Yixuan Wang, Huidi Yang, Kyunghyun Cho, Cem M. Deniz, Narges Razavian
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While large-scale pretraining has revolutionized language modeling, its potential remains underexplored in healthcare with structured electronic health records (EHRs). We present RAVEN, a novel generative pretraining strategy for sequential EHR data based on Recurrence-Aware next-Visit EveNt prediction. Leveraging a dataset of over one million unique individuals, our model learns to autoregressively generate tokenized clinical events for the next visit conditioned on patient history. We introduce regularization on predicting repeated events and highlight a key pitfall in EHR-based foundation model evaluations: repeated event tokens can inflate performance metrics when new onsets are not distinguished from subsequent occurrences. Furthermore, we empirically investigate the scaling behaviors in a data-constrained, compute-saturated regime, showing that simply increasing model size is suboptimal without commensurate increases in data volume. We evaluate our model via zero-shot prediction for forecasting the incidence of a diverse set of diseases, where it rivals fully fine-tuned representation-based Transformer models and outperforms widely used simulation-based next-token approaches. Finally, without additional parameter updates, we show that RAVEN can generalize to an external patient cohort under lossy clinical code mappings and feature coverage gaps.
### Title:
          Anti-I2V: Safeguarding your photos from malicious image-to-video generation
 - **Authors:** Duc Vu, Anh Nguyen, Chi Tran, Anh Tran
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Advances in diffusion-based video generation models, while significantly improving human animation, poses threats of misuse through the creation of fake videos from a specific person's photo and text prompts. Recent efforts have focused on adversarial attacks that introduce crafted perturbations to protect images from diffusion-based models. However, most existing approaches target image generation, while relatively few explicitly address image-to-video diffusion models (VDMs), and most primarily focus on UNet-based architectures. Hence, their effectiveness against Diffusion Transformer (DiT) models remains largely under-explored, as these models demonstrate improved feature retention, and stronger temporal consistency due to larger capacity and advanced attention mechanisms. In this work, we introduce Anti-I2V, a novel defense against malicious human image-to-video generation, applicable across diverse diffusion backbones. Instead of restricting noise updates to the RGB space, Anti-I2V operates in both the $L$*$a$*$b$* and frequency domains, improving robustness and concentrating on salient pixels. We then identify the network layers that capture the most distinct semantic features during the denoising process to design appropriate training objectives that maximize degradation of temporal coherence and generation fidelity. Through extensive validation, Anti-I2V demonstrates state-of-the-art defense performance against diverse video diffusion models, offering an effective solution to the problem.
### Title:
          Latent-WAM: Latent World Action Modeling for End-to-End Autonomous Driving
 - **Authors:** Linbo Wang, Yupeng Zheng, Qiang Chen, Shiwei Li, Yichen Zhang, Zebin Xing, Qichao Zhang, Xiang Li, Deheng Qian, Pengxuan Yang, Yihang Dong, Ce Hao, Xiaoqing Ye, Junyu han, Yifeng Pan, Dongbin Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Latent-WAM, an efficient end-to-end autonomous driving framework that achieves strong trajectory planning through spatially-aware and dynamics-informed latent world representations. Existing world-model-based planners suffer from inadequately compressed representations, limited spatial understanding, and underutilized temporal dynamics, resulting in sub-optimal planning under constrained data and compute budgets. Latent-WAM addresses these limitations with two core modules: a Spatial-Aware Compressive World Encoder (SCWE) that distills geometric knowledge from a foundation model and compresses multi-view images into compact scene tokens via learnable queries, and a Dynamic Latent World Model (DLWM) that employs a causal Transformer to autoregressively predict future world status conditioned on historical visual and motion representations. Extensive experiments on NAVSIM v2 and HUGSIM demonstrate new state-of-the-art results: 89.3 EPDMS on NAVSIM v2 and 28.9 HD-Score on HUGSIM, surpassing the best prior perception-free method by 3.2 EPDMS with significantly less training data and a compact 104M-parameter model.
## Keyword: autonomous driving
### Title:
          Off-Policy Safe Reinforcement Learning with Constrained Optimistic Exploration
 - **Authors:** Guopeng Li, Matthijs T.J. Spaan, Julian F.P. Kooij
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 When safety is formulated as a limit of cumulative cost, safe reinforcement learning (RL) aims to learn policies that maximize return subject to the cost constraint in data collection and deployment. Off-policy safe RL methods, although offering high sample efficiency, suffer from constraint violations due to cost-agnostic exploration and estimation bias in cumulative cost. To address this issue, we propose Constrained Optimistic eXploration Q-learning (COX-Q), an off-policy safe RL algorithm that integrates cost-bounded online exploration and conservative offline distributional value learning. First, we introduce a novel cost-constrained optimistic exploration strategy that resolves gradient conflicts between reward and cost in the action space and adaptively adjusts the trust region to control the training cost. Second, we adopt truncated quantile critics to stabilize the cost value learning. Quantile critics also quantify epistemic uncertainty to guide exploration. Experiments on safe velocity, safe navigation, and autonomous driving tasks demonstrate that COX-Q achieves high sample efficiency, competitive test safety performance, and controlled data collection cost. The results highlight COX-Q as a promising RL method for safety-critical applications.
### Title:
          Mitigating Object Hallucinations in LVLMs via Attention Imbalance Rectification
 - **Authors:** Han Sun, Qin Li, Peixin Wang, Min Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Object hallucination in Large Vision-Language Models (LVLMs) severely compromises their reliability in real-world applications, posing a critical barrier to their deployment in high-stakes scenarios such as autonomous driving and medical image analysis. Through systematic empirical investigation, we identify that the imbalanced attention allocation, both across modalities (i.e., vision and language) and within modalities (among individual tokens), exhibits a strong causal correlation with the occurrence of object hallucination. Leveraging this insight, we introduce a novel concept termed attention imbalance, which not only quantifies the degree of attention disparity but also visually delineates the underlying patterns (e.g., over-attentiveness to irrelevant language tokens or under-attentiveness to discriminative visual features) that drive object hallucination. To mitigate object hallucination, we further propose Attention Imbalance Rectification (AIR), a lightweight decoding-time intervention method that reallocates attention weights and adjusts attention distributions to rectify modality-wise and token-wise imbalances. Extensive evaluations on four mainstream LVLMs and three benchmarks (CHAIR, POPE, and MM-Vet) with seven baselines demonstrate that AIR consistently reduces object hallucination rates, achieving up to a 35.1% reduction compared to the baselines, while improving up to 15.9% of LVLMs' general capability across diverse vision-language tasks.
### Title:
          Toward Physically Consistent Driving Video World Models under Challenging Trajectories
 - **Authors:** Jiawei Zhou, Zhenxin Zhu, Lingyi Du, Linye Lyu, Lijun Zhou, Zhanqian Wu, Hongcheng Luo, Zhuotao Tian, Bing Wang, Guang Chen, Hangjun Ye, Haiyang Sun, Yu Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video generation models have shown strong potential as world models for autonomous driving simulation. However, existing approaches are primarily trained on real-world driving datasets, which mostly contain natural and safe driving scenarios. As a result, current models often fail when conditioned on challenging or counterfactual trajectories-such as imperfect trajectories generated by simulators or planning systems-producing videos with severe physical inconsistencies and artifacts. To address this limitation, we propose PhyGenesis, a world model designed to generate driving videos with high visual fidelity and strong physical consistency. Our framework consists of two key components: (1) a physical condition generator that transforms potentially invalid trajectory inputs into physically plausible conditions, and (2) a physics-enhanced video generator that produces high-fidelity multi-view driving videos under these conditions. To effectively train these components, we construct a large-scale, physics-rich heterogeneous dataset. Specifically, in addition to real-world driving videos, we generate diverse challenging driving scenarios using the CARLA simulator, from which we derive supervision signals that guide the model to learn physically grounded dynamics under extreme conditions. This challenging-trajectory learning strategy enables trajectory correction and promotes physically consistent video generation. Extensive experiments demonstrate that PhyGenesis consistently outperforms state-of-the-art methods, especially on challenging trajectories. Our project page is available at: this https URL.
### Title:
          Latent-WAM: Latent World Action Modeling for End-to-End Autonomous Driving
 - **Authors:** Linbo Wang, Yupeng Zheng, Qiang Chen, Shiwei Li, Yichen Zhang, Zebin Xing, Qichao Zhang, Xiang Li, Deheng Qian, Pengxuan Yang, Yihang Dong, Ce Hao, Xiaoqing Ye, Junyu han, Yifeng Pan, Dongbin Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Latent-WAM, an efficient end-to-end autonomous driving framework that achieves strong trajectory planning through spatially-aware and dynamics-informed latent world representations. Existing world-model-based planners suffer from inadequately compressed representations, limited spatial understanding, and underutilized temporal dynamics, resulting in sub-optimal planning under constrained data and compute budgets. Latent-WAM addresses these limitations with two core modules: a Spatial-Aware Compressive World Encoder (SCWE) that distills geometric knowledge from a foundation model and compresses multi-view images into compact scene tokens via learnable queries, and a Dynamic Latent World Model (DLWM) that employs a causal Transformer to autoregressively predict future world status conditioned on historical visual and motion representations. Extensive experiments on NAVSIM v2 and HUGSIM demonstrate new state-of-the-art results: 89.3 EPDMS on NAVSIM v2 and 28.9 HD-Score on HUGSIM, surpassing the best prior perception-free method by 3.2 EPDMS with significantly less training data and a compact 104M-parameter model.
### Title:
          DreamerAD: Efficient Reinforcement Learning via Latent World Model for Autonomous Driving
 - **Authors:** Pengxuan Yang, Yupeng Zheng, Deheng Qian, Zebin Xing, Qichao Zhang, Linbo Wang, Yichen Zhang, Shaoyu Guo, Zhongpu Xia, Qiang Chen, Junyu Han, Lingyun Xu, Yifeng Pan, Dongbin Zhao
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce DreamerAD, the first latent world model framework that enables efficient reinforcement learning for autonomous driving by compressing diffusion sampling from 100 steps to 1 - achieving 80x speedup while maintaining visual interpretability. Training RL policies on real-world driving data incurs prohibitive costs and safety risks. While existing pixel-level diffusion world models enable safe imagination-based training, they suffer from multi-step diffusion inference latency (2s/frame) that prevents high-frequency RL interaction. Our approach leverages denoised latent features from video generation models through three key mechanisms: (1) shortcut forcing that reduces sampling complexity via recursive multi-resolution step compression, (2) an autoregressive dense reward model operating directly on latent representations for fine-grained credit assignment, and (3) Gaussian vocabulary sampling for GRPO that constrains exploration to physically plausible trajectories. DreamerAD achieves 87.7 EPDMS on NavSim v2, establishing state-of-the-art performance and demonstrating that latent-space RL is effective for autonomous driving.
