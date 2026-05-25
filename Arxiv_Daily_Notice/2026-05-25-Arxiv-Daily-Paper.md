# Showing new listings for Monday, 25 May 2026
## Keyword: SLAM
There is no result 
## Keyword: odometry
### Title:
          Extending Deep Event Visual Odometry with Sparse Point-Cloud Export
 - **Authors:** Alireza Safdari, Sajad Ashraf
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Event cameras are well suited for visual odometry under high-speed motion and challenging lighting conditions due to their low latency, high temporal resolution, and high dynamic range. Deep Event Visual Odometry (DEVO) demonstrated that monocular event-only odometry can achieve strong performance by combining sparse patch tracking, learned patch selection, recurrent correspondence refinement, and differentiable bundle adjustment. In this project, we extend DEVO with a sparse point-cloud export pipeline. Rather than modifying the core odometry formulation, our approach exposes the internal 3D structure already estimated by DEVO and converts it into an explicit point-cloud representation for visualization and further processing. In addition, we implement a practical workflow for data export, format conversion, and point-cloud cleanup. The resulting system preserves the original visual odometry pipeline while enabling sparse geometric scene output. Experiments on the BOARD SLOW sequence show that the exported sparse cloud is locally consistent with EMVS reconstructions, achieving high precision at a 5 cm threshold, while also highlighting the expected limitations in density, completeness, and sensitivity to accumulated odometry noise.
### Title:
          Four Simple Proprioceptive Estimators for Legged Robots
 - **Authors:** Frank Dellaert, Chiyun Noh, Varun Agrawal, Ayoung Kim
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Legged robots carry an IMU, but the inertial solution drifts because consumer-grade IMUs are noisy. However, the feet create intermittent contacts with the environment that can be used to mitigate that drift. This report develops a sequence of increasingly expressive legged robot state estimators that leverage this. In all cases, the floating-base state comprises attitude, position, velocity, and IMU biases. To model foot contacts, we start from the contact-aided invariant EKF of Hartley et al., albeit at a reduced contact update rate. This is then augmented by replacing the measurement update by a small factor graph. Finally, we turn the same factors into a fixed-lag smoother with contact-episode footholds, with and without an evolving IMU bias. To facilitate reproducibility and further research in proprioceptive legged odometry, all four variants are available in GTSAM (Dellaert et. al), and we additionally provide a ROS2-compatible implementation.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          The Geometry of Cooperative Game Solutions: Stratified Egalitarian Shapley Values
 - **Authors:** Frank M. V. Feys
 - **Subjects:** Subjects:
Computer Science and Game Theory (cs.GT); Theoretical Economics (econ.TH); Combinatorics (math.CO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The space L of linear value maps on a finite-player cooperative game G^N is finite-dimensional, and admits a canonical inner product induced by the Harsanyi-dividend decomposition of G^N. We show that this inner product is intrinsic: the same value arises from any orthonormal basis of G^N with respect to the Harsanyi inner product. Within this geometry, the subspace L^{ESL} of efficient, symmetric, linear value maps admits a clean structure theorem. The induced orthogonal stratification of L by coalition size yields a canonical linear isomorphism L^{ESL} = R^{n-1}, under which every efficient symmetric linear value map decomposes uniquely into n-1 stratified epsilons, one per coalition size. The classical egalitarian Shapley family of Joosten (1996) is precisely the diagonal slice of this R^{n-1}. The orthogonal projection of any Psi in L^{ESL} onto this diagonal yields an optimal parameter eps*(Psi) equal to the weighted mean of the stratified epsilons under an explicit probability distribution {w_a} over coalition sizes, and the goodness-of-fit R^2(Psi) equals one minus the relative weighted variance of those epsilons. The framework is a literal regression-statistics analogue of the coefficient of determination. At n=4 it produces a clean three-way classification of the standard alternatives to the Shapley value: the Banzhaf value is nearly orthogonal to the egalitarian Shapley axis (R^2 ~ 1%); the equal-surplus-division value is moderately aligned (R^2 ~ 38%); the solidarity value is almost entirely aligned (R^2 ~ 99.6%). Asymptotically R^2(ESD) -> 1, R^2(So) -> 1, and R^2(Bz) -> 1/2, the last reflecting a structural identity between the efficiency defect and the egalitarian-Shapley deviation of the Banzhaf value at every coalition size.
### Title:
          FusionSense: Tri-Stage Near-Sensor Learning for Runtime-Adaptive Multimodal Edge Intelligence
 - **Authors:** Sanggeon Yun, Ryozo Masukawa, Minhyoung Na, Hyunwoo Oh, Yoshiki Yamaguchi, Wenjun Huang, SungHeon Jeong, Mohsen Imani
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous systems and smart-industry deployments increasingly split computation across near-sensor, edge, and cloud resources, where tight energy, latency, and reliability budgets demand run-time adaptivity. In practice, deciding what to compute and transmit at each point is pivotal; yet as multimodal sensor suites (cameras, LiDAR/depth, etc.) proliferate at the edge, most prior approaches either (i) fuse modalities on powerful servers or (ii) apply uni-modal near-sensor filters that ignore cross-modal dependencies, leading to redundant transmissions or missed events. We present FusionSense, a fusion-aware intelligent sensing framework for energy-constrained autonomous edge systems. Lightweight near-sensor classifiers are trained via a three-step procedure: (i) a server-side fusion model learns the downstream task, (ii) filter-out-safe (FoS) labels quantify each modality's necessity relative to the fused decision, and (iii) an edge-side fusion model is compacted by injecting near-sensor predictions as auxiliary signals. The result is a run-time decision layer that jointly reduces compute and communication while scaling linearly with sensor count. On a dual-modality (RGB+Depth/LiDAR) setup with SynDrone, FusionSense sustains task quality at substantially higher data-reduction rates than uni-modal filters and delivers large end-to-end gains: up to 33x lower energy at 1% FoI prevalence, 11x at 10%, a 92.3% reduction in quality loss at a fixed 30% data reduction, and roughly 1.5x higher energy savings than the best prior filtering baseline.
### Title:
          AraHopeCorpus: Annotation Guidelines and Dataset for Hope Speech in Arabic Social Media Crisis Discourse
 - **Authors:** Esra'a Sharqawi, Wajdi Zaghouani
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Social media has become a crucial arena for shaping public narratives during armed conflicts, providing space for both harmful and constructive communication. While hate speech and misinformation have been widely studied, expressions that promote resilience, solidarity, and optimism remain underexplored, particularly in Arabic contexts. This paper introduces AraHopeCorpus, the first annotated dataset of Arabic hope speech collected from ten thousand YouTube comments related to the war on Gaza between 2023 and 2024. Using a detailed annotation framework, comments were classified into three categories: hope speech, no hope speech, and neutral or unclear discourse. The dataset shows that hopeful language dominates, accounting for more than sixty four percent of all comments. These expressions of hope appear mainly as religious encouragement, collective solidarity, and optimism for endurance and justice. No hope speech, representing about thirteen percent, reflects despair and disillusionment, while the rest of the comments contain neutral or mixed content. Inter-Annotator Agreement reached substantial levels (Cohen's Kappa equals 0.71), though dialectal variation, sarcasm, and implicit meaning posed annotation challenges. A comparative analysis between human annotators and ChatGPT revealed that large language models can support annotation but remain limited in handling dialectal and culturally embedded expressions. AraHopeCorpus will be released for research purposes under an open and non commercial license. It provides a valuable resource for studying constructive digital discourse, enabling further research on hope speech detection, crisis communication, and resilience in Arabic social media.
### Title:
          Joint Target-Less Intrinsic and Extrinsic Camera-LiDAR Calibration using Deep Point Correspondences
 - **Authors:** Simon Bultmann, Daniele Cattaneo, Abhinav Valada
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate camera-LiDAR calibration is a prerequisite for robust multi-modal perception in robotics. Recent target-less approaches based on deep point correspondences achieve remarkable performance for extrinsic calibration but assume rectified images with known intrinsics. In this work, we overcome this limitation and present the first fully target-less pipeline that jointly estimates camera intrinsics (pinhole model with radial-tangential distortion) and camera-LiDAR extrinsics with deep pixel-point correspondences. Our approach extends deep correspondence-based calibration by (i) automatic intrinsic initialization via structure-from-motion, (ii) generalizing camera-LiDAR matching to raw images with unknown intrinsics including distortion, and (iii) tightly coupling correspondence estimation with joint nonlinear optimization over both intrinsics and extrinsics. We evaluate our method on the KITTI dataset with unseen camera-LiDAR pairs and demonstrate that joint calibration achieves improved extrinsic accuracy while additionally recovering accurate intrinsics.
### Title:
          RS2AD-LiDAR: End-to-End Autonomous Driving LiDAR Data Generation from Roadside Sensor Observations
 - **Authors:** Runyi Huang, Ni Ding, Ruidan Xing, Yuheng Shi, Lei He, Keqiang Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end autonomous driving solutions, which directly process multimodal sensory data and output fine-grained control commands, have gradually become a mainstream direction with the development of autonomous driving technology. However, current methods in this category rely on single-vehicle data collection for model training and optimization, which suffers from high acquisition and annotation costs, scarcity of valuable scenarios, and data silos. To address these challenges, we propose RS2AD-LiDAR, a novel framework for reconstructing and generating vehicle-mounted LiDAR data from roadside sensor observations. Since no public dataset currently provides highly overlapping perception coverage between roadside and vehicle-mounted LiDAR sensors, which is essential for studying roadside-to-vehicle data generation, we constructed a dedicated dataset named R2V-LiDAR which is used solely for evaluation in this work. Specifically, our method transforms roadside LiDAR point clouds into the vehicle-mounted LiDAR coordinate system, and synthesizes high-fidelity vehicle-mounted data via virtual LiDAR modeling and point cloud resampling techniques. To the best of our knowledge, this is the first approach to reconstruct vehicle-mounted LiDAR data from roadside sensor inputs. Extensive experimental comparisons demonstrate the semantic similarity between the generated data and real data. Furthermore, object detection experiments show that incorporating the generated data into real data for model training improves both Bird's Eye View (BEV) and 3D detection accuracy, thereby validating the effectiveness of the proposed method.
### Title:
          Calibration-Informative Region Selection for Online LiDAR--Camera Calibration in Agricultural Environments
 - **Authors:** Rajitha de Silva, Grzegorz Cielniak
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable multi-modal calibration requires identifying which observations truly constrain the extrinsic parameters and which ones mainly add noise or ambiguity. In this paper, we propose a support-map-driven approach to multi-modal calibration that decouples four functional blocks: initial calibration, cross-modal residual extraction, support-map estimation, and support-aware refinement. We instantiate this formulation for online LiDAR--camera calibration using MDPCalib, a target-less LiDAR--camera calibration method based on motion and deep point correspondences, and CMRNext, a dense LiDAR--camera matching model that predicts optical-flow-like image-plane residuals. The key contribution is a dense calibration support map that aggregates cross-modal agreement over aligned observations and highlights where calibration evidence is consistently reliable. Across the Bacchus Long-Term (BLT) dataset and KITTI, we show that calibration evidence is spatially and semantically non-uniform, indicating that some semantic regions provide stronger cues for calibration than others. On KITTI, support-guided refinement improves the calibration performance with better translation accuracy while rotational gains remain limited.
### Title:
          SFG-ROS: A Resource-Aware Framework for Dense Multi-Agent Perception
 - **Authors:** Constantin Blessing, Elias Geiger, Jakob Häringer, Dennis Grewe, Markus Enzweiler
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deploying heterogeneous multi-agent robot fleets for collaborative perception requires robust data exchange and scalable software architectures. However, standard ROS 2 implementations often suffer from network saturation, namespace collisions, and severe computational overhead when distributing dense sensor streams across devices. To address these bottlenecks, we present SFG-ROS, a resource-aware multi-agent software framework designed for dynamic fleet deployments. SFG-ROS addresses these challenges through three primary contributions. First, schema-driven traffic routing isolates high-frequency intra-agent traffic from the global network using a programmatic fully qualified name schema and targeted Fast DDS routing. Second, an on-demand centralized decoding pipeline automatically offloads high-bandwidth sensor data decompression, eliminating redundant processing across local consumer nodes. Finally, a hardware-agnostic container pipeline dynamically adapts to heterogeneous accelerators, seamlessly bridging development environments with zero-touch, field-ready execution. We evaluate the framework using a fleet of wheeled and legged robots equipped with LiDAR and stereo depth cameras. Experimental results show SFG-ROS bounds network traffic to $\mathcal{O}(1)$ and, by replacing redundant decompression with lightweight IPC, reduces the per-subscriber CPU scaling penalty by 72.3\% versus standard ROS 2, all while maintaining low latency. Finally, we publish SFG-ROS under a permissive license, available via \href{this https URL}{this http URL}.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          KPI2KVI: A Multi Agent Workflow for Calculating Key Value Indicators from Service Descriptions
 - **Authors:** Masoud Shokrnezhad, Tarik Taleb, Yan Chen, Qize Guo
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Artificial Intelligence (cs.AI); Emerging Technologies (cs.ET); Performance (cs.PF)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Key Value Indicators (KVIs) provide a decision oriented view of a service by summarizing how operational performance translates into stakeholder value, risk, and outcomes. However, in many domains KVIs are difficult to compute in practice because they require selecting relevant KVI categories, defining measurable Key Performance Indicators (KPIs), collecting KPI values, and applying consistent calculation logic, all of which is typically performed manually and inconsistently from unstructured service documentation. This paper presents KPI2KVI, a tool that transforms a natural language service description into computed KVI estimates by orchestrating a deterministic multi agent workflow powered by Large Language Models (LLMs) that (i) elicits missing service context, (ii) extracts and finalizes relevant KVI categories from a taxonomy, (iii) generates service specific KPIs with units and descriptions, (iv) collects KPI values through an interactive dialogue and also supports intelligent estimation for KPI values that are unavailable, and (v) computes interval valued KVI outputs (minimum, exact, maximum) with traceable explanations for each KVI code. Simulations with representative service descriptions demonstrate that KPI2KVI consistently produces a complete end to end mapping from description to KVI intervals and provides transparent calculation narratives that support post hoc auditing and interactive advisory queries.
### Title:
          NeuroNL2LTL: A Neurosymbolic Framework for Natural Language Translation of Linear Temporal Logic
 - **Authors:** Paapa Kwesi Quansah, Ernest Bonnah
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Logic in Computer Science (cs.LO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Effectively translating between natural language (NL) and formal logics like Linear Temporal Logic (LTL) requires expertise that limits formal verification's reach in safety-critical development. Template-based approaches sacrifice expressiveness for reliability; neural methods achieve fluency but provide no correctness guarantees. We present NeuroNL2LTL, a neurosymbolic architecture unifying learned translation with formal verification. NeuroNL2LTL routes translation through an intermediate representation whose mapping to LTL is structure-preserving by construction. Generated specifications undergo satisfiability and non-triviality checking; a minimal-edit repair mechanism corrects near-miss outputs before they reach downstream tools. The central innovation is verifier-in-the-loop training: verification outcomes serve as reward signals for reinforcement learning, producing neural components that optimize directly for formal correctness. On 200,000+ requirements spanning aerospace, robotics, autonomous vehicles, and ten additional domains, NeuroNL2LTL achieves 28\% semantic equivalence with reference specifications while ensuring 86\% of outputs are verified satisfiable. The system also generates contextually grounded explanations from LTL, enabling domain experts to validate specifications without specialized training. This work demonstrates that formal verification can function as both training objective and runtime filter for neural specification systems, allowing us to build neural-based tools whose reliability derives from logical guarantees rather than statistical confidence.
### Title:
          Energy per Successful Goal: Goal-Level Energy Accounting for Agentic AI Systems
 - **Authors:** Deepak Panigrahy, Aakash Tyagi
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Performance (cs.PF)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current AI energy benchmarks measure consumption at the granularity of a single model invocation or training run. For classical single-turn workloads this unit remains coherent. For agentic systems - where a single user goal may trigger multi-step orchestration, tool calls, retries, and failure-recovery cycles - the invocation count is an implementation artifact rather than a task property, and inference-level normalization misrepresents the energy cost of goal completion. We present A-LEMS (Agentic LLM Energy Measurement System), a cross-layer measurement framework that redefines the unit of AI energy accounting from energy per inference to Energy per Successful Goal (EpG). EpG aggregates total workflow energy across all execution attempts, including failures and retries, normalized by successfully completed goals. A-LEMS formalizes energy attribution through a temporal boundary model, a five-layer observation pipeline mapping RAPL signals to workflow-level energy, and a reproducibility protocol binding every measurement to hardware and runtime configuration. Building on EpG, we define the Orchestration Overhead Index (OOI), isolating the energy cost of orchestration relative to linear execution under identical task criteria. Across five reasoning and three tool-augmented task families, agentic workflows consume 4.33x higher mean energy per successful goal than linear baselines (888.1 J vs 205.3 J). This overhead is driven by orchestration structure, not inference compute. For tool-augmented tasks, OOI inverts below 1.0x: agentic execution is cheaper than linear, confirming the metric captures orchestration structure rather than a fixed upward bias. These findings establish that energy-per-inference is insufficient for agentic AI. EpG and OOI provide the measurement foundation for accurate benchmarking, where orchestration structure is the primary determinant of energy cost.
### Title:
          Can AI Guess What You Know? Performance Comparison of Large Language Models for Human Domain Knowledge Estimation From Communication Logs
 - **Authors:** Ko Watanabe, Shoya Ishimaru
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Employees often struggle to identify ``who knows what,'' leading to organizational productivity losses. We investigate whether Large Language Models (LLMs) can infer individual domain knowledge directly from long-term Slack logs. Analyzing 27,188 messages from 43 users, we evaluated seven models (including Gemini, Claude, and GPT families) by comparing their zero-shot estimates against self-reported skill ratings from 27 participants. Gemini 2.5 Flash achieved the lowest error (MAE 21.13%), while GPT models showed significantly larger discrepancies. Notably, estimation accuracy depended only weakly on message volume, indicating that more text alone does not guarantee better inference. These findings demonstrate the feasibility and current limits of automated expertise mapping, highlighting the need for privacy-preserving deployments and richer, structure-aware representations of human knowledge.
### Title:
          Scene Reconstruction as Mapping Priors for 3D Detection
 - **Authors:** Yang Fu, Yuliang Zou, Hao Xiang, Xin Huang, Yijing Bai, Chen Song, Weijing Shi, Govind Thattai, Dragomir Anguelov, Mingxing Tan, Yingwei Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In autonomous driving, mapping is critical for motion planning but remains an under-utilized resource for perception tasks such as 3D object detection. Maps can provide robust structural priors of the static environment, helping resolve ambiguities and correct for sensor data sparsity or noise, especially for distant objects or under adverse weather conditions. However, conventional High-Definition (HD) maps are resource-intensive to obtain and maintain, which presents a challenge for efficient, large-scale deployment. In this paper, we propose a scalable solution to systematically leverage mapping to improve 3D detection by overcoming two primary challenges. First, we introduce a pipeline to automatically build dense mapping priors from aggregated sensor data, eliminating the need for human labeling. Second, we design a novel Mapping Priors Augmented 3D Detection (MPA3D) framework to effectively integrate mapping priors with different sensor modalities. Extensive experiments on the Waymo Open Dataset demonstrate that our approach achieves new state-of-the-art results, proving the effectiveness of scalable reconstructed scene priors for enhancing 3D detection.
### Title:
          Semantic-Aware Guided Drone Exploration for Language-Conditioned 3D Indoor Mapping
 - **Authors:** Nitin Vegesna, Avideh Zakhor
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Semantic-Aware Guided Exploration, SAGE, a system for open-vocabulary exploration in unknown 3D indoor environments that preserves coverage-oriented behavior while allowing semantic cues to reprioritize frontier selection. Building on the FALCON volumetric explorer, SAGE integrates Contrastive Language-Image Pre-training (CLIP) via four key components: object-centric embedding storage, a temporal cache that projects recent observations onto the free-unknown boundary, object frontiers for high-similarity detections, and a unified semantic-geometric planning cost. This cost function bounds semantic reweighting influence, ensuring frontiers are prioritized without sacrificing total coverage. In Matterport3D-based simulations, SAGE outperforms FALCON and a semantic-only ablation in object discovery across map-query pairs. Compared to Finding Things in the Unknown (FTU), SAGE completes exploration 9.0 to 25.9 times faster across the nine shared map-query pairs, achieving a mean speedup of 13.7. Furthermore, SAGE achieves substantially higher volumetric throughput than FTU. Finally, we deploy SAGE in five real-world flights in two environments on a Modal AI Starling 2 quadrotor with onboard sensing and planning, and offboard CLIP inference. Comparing SAGE and FALCON, we find that while FALCON results in faster exploration and shorter mapping trajectories, SAGE outperforms FALCON in terms of object discovery.
### Title:
          SolarChain: Bridging Physical Law, Verifiable Trust, and Sustainable Markets for Urban Energy Resilience
 - **Authors:** Shilin Ou, Yifan Xu, Zhenshan Zhang, Luyao Zhang, Ming-Chun Huang
 - **Subjects:** Subjects:
Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Urban decarbonization requires scaling rooftop solar across millions of fragmented producers, yet cities face a fundamental tension: energy data is easily manipulated, and economic incentives often reward speculation rather than actual infrastructure deployment. We present SolarChain, a platform that resolves both problems by anchoring digital accountability to the thermodynamic limits of solar energy conversion. Using real-time meteorological data, geospatial coordinates, and first-principles calculations of solar yield, the system establishes a hard physical boundary for every panel's maximum possible output; any reported generation exceeding this limit is automatically rejected before entering the shared ledger. This trustless verification enables a peer-to-peer marketplace with programmatic reward structures that continuously reinvest value into equipment maintenance and market liquidity, preventing the speculative hoarding that typically destabilizes blockchain-based marketplaces. When electricity is consumed, the corresponding digital credits are permanently retired in direct proportion to physical energy dissipation, creating an auditable one-to-one mapping between urban consumption and carbon accounting. Deployed across heterogeneous city nodes, the prototype demonstrates resilience against data injection attacks while lowering capital barriers for community-level solar expansion. Beyond energy, the framework offers a general model for coordinating economic activity with physical law in any domain where distributed infrastructure demands both data integrity and sustainable investment. We release the data and code as open-access on GitHub.
### Title:
          Lipschitz Optimization for Formal Verification of Homographies
 - **Authors:** Jean-Guillaume Durand, Panagiotis Kouvaros, Maxime Gariel, Alessio Lomuscio
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The adoption of vision neural networks in regulated industries requires formal robustness guarantees, especially in safety-critical domains such as healthcare, autonomous vehicles, and aerospace. However, current approaches are confined to incomplete statistical verification or robustness to $\ell_p$-norm and affine transforms, which cover only a narrow subset of perturbations to the image formation process. In particular, robustness to camera motion remains an open problem despite being key to deploy many vision applications. We present a formal verification approach that targets robustness against 3D motion perturbations of the capturing camera. We first establish a closed-form mapping from camera pose to pixel values. By analyzing the continuity properties of the resulting homographies, we show that recent work on Lipschitz optimization and piecewise continuity can be extended to derive tight linear bounds on perturbed pixel values. Our approach applies to scenes with predominantly planar structure, such as ground planes in augmented reality, road markings and traffic signs in autonomous driving, or planar workspaces in robotic manipulation. This enables the first formal verification of projective geometry transforms, without complex simulation, surrogate networks, or explicit image-formation models. We validate our implementation and show up to 89% speedup and 7% tighter bounds over prior work. We then evaluate our method on the VNN-COMP benchmark and reveal systematic weaknesses to projective perturbations. Finally, we demonstrate a real-world case study on a safety-critical runway classifier, highlighting practical vulnerabilities to camera motion, and addressing a key challenge in the certification of learned models. Data and code are publicly available at this https URL .
### Title:
          SCOPE: Simulating Cross-game Operations in Playable Environments for FPS World Models
 - **Authors:** Zizhao Tong, Hongfeng Lai, Zeqing Wang, Zhaohu Xing, Kexu Cheng, Haoran Xu, Zhao Pu, Shangwen Zhu, Ruili Feng, Jian Zhao, Yan Zhang, Hao Tang, Yeying Jin, Ling Shao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Interactive world models for first-person shooter (FPS) games must resolve high-frequency overlapping control signals at every frame without disrupting unaffected regions. Existing methods inject actions globally and train on single titles, failing under dense FPS inputs. We observe that FPS actions are spatially selective: discrete events such as firing or reloading affect only a localized region around the weapon (the scope), while continuous camera and movement signals govern stable surroundings. We propose SCOPE, which inserts a conditioning module into each transformer block of a pretrained video diffusion model. It reshapes features into per-pixel temporal sequences so that each position computes its action response from local visual content. This separates in-scope effects from out-of-scope generation without segmentation labels. We also introduce CrossFPS, the first multi-game FPS dataset with frame-aligned action telemetry. It comprises 69K clips from 7 titles with 10-DoF controller signals, curated to remove gameplay bias. The model learns general visual-to-action mappings rather than game-specific patterns, enabling zero-shot transfer to unseen scenes. Experiments confirm strong action responsiveness, precise scope separation, and effective cross-game generalization.
### Title:
          Multi-Floor Exploration for Ground Robots via an Incremental Reachable Graph and Structural Priors
 - **Authors:** Zhiwen Zhu, Jiaqi Chen, Xiangyi Huang, Meiqi Hu, Boyu Zhou
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous exploration of multi-floor buildings remains challenging for ground robots because conventional 2D and 2.5D maps cannot represent overlapping traversable surfaces such as stairs, ramps, and multiple reachable elevations. This letter presents a multi-floor exploration framework based on an incremental reachable graph. Built as a sparse graph over reachable support surfaces, the graph preserves potentially valid connectivity through tentative graph elements under sparse observations and enables stable, physically reachable frontier detection. To guide exploration beyond the currently mapped floor, we project task-zone priors from an explored floor to initialize a hypothetical graph on the target floor and reconcile it incrementally with incoming observations. A hierarchical planner then jointly reasons over confirmed and hypothetical structures for global guidance. In simulation, the proposed method demonstrates improved exploration efficiency and mapping completeness compared to evaluated baselines. Furthermore, onboard real-world experiments validate its practical feasibility and real-time performance.
### Title:
          Parametric Prior Mapping Framework for Non-stationary Probabilistic Time Series Forecasting
 - **Authors:** Jinglin Li, Jun Tan, QI Fang, Ning Gui
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Effectively modeling non-stationary dynamics in probabilistic multivariate time series(MTS) forecasting requires balancing expressiveness with robustness. Existing parametric approaches benefit from strong inductive biases but lack flexibility, whereas deep generative models struggle to capture complex temporal dependencies without extensive data and computation. We introduce Parametric Prior Mapping (PPM), a framework that injects parametric structural priors into a generative modeling process. Specifically, PPM utilizes a parametric estimator to derive a dynamic, adaptive prior that guides the learning of a complex predictive distribution via a learnable mapping. This design allows the model to retain the efficiency of parametric methods while exploiting the expressive power of generative models. Trained with a hybrid objective, PPM yields precise forecasts with well-calibrated uncertainty estimates. Empirical results show that PPM outperforms existing baselines in handling non-stationary data, offering a superior trade-off between accuracy and computational efficiency. The code is available at this https URL.
### Title:
          Key challenges and bridges among convergence analysis techniques for polytopal methods
 - **Authors:** Lourenço Beirão da Veiga, Daniele Antonio Di Pietro, Jérôme Droniou
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Polytopal methods provide a flexible framework for the numerical approximation of partial differential equations on general meshes. Their convergence analysis raises specific challenges due to their inherently non-conforming nature and, in many cases, the fully discrete nature of their solution. Two main techniques are considered: the virtual-function approach, used, e.g., in the context of Virtual Element Methods, and the fully discrete approach, which underlies, e.g., the Discrete de Rham method. We introduce here a novel framework based on the notion of conforming liftings, namely bounded and consistent mappings from the discrete space into the continuous space. This approach bridges the virtual and fully discrete viewpoints, clarifies the role of norm equivalence for virtual functions, and leads to a decomposition of the consistency error usable for polytopal methods. The three approaches are demonstrated on a model problem, which provides the opportunity to discuss relevant technical points. Bridges with the convergence properties of discrete differential complexes are also built.
### Title:
          MISRust: Mapping MISRA-C++ Coding Guidelines to the Rust Programming Language
 - **Authors:** Marius Molz, Niels Schneider, Sven Lechner, Stefan Kowalewski, Alexandru Kampmann
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Rust programming language is increasingly being considered for safety-critical system development. However, established safety standards such as ISO 26262 require the use of coding guidelines that do not yet exist for Rust. This paper systematically examines each of the 179 MISRA C++ 2023 coding guidelines and classifies them into 6 categories based on their applicability to Rust. Our approach analyzes the rationale behind each MISRA rule to determine whether it remains valid in the Rust programming context. We find that 47.75% of the 111 as-is applicable MISRA rules are automatically enforced by Rust's language design, eliminating the need for explicit guideline enforcement. Furthermore, our analysis explicitly distinguishes between safe and unsafe Rust. We find that 69 guidelines are still relevant and still require either direct application or adaptation for Rust. Importantly, 36 of these rules are automatically satisfied when only using the safe subset of the Rust language. However, they are required again if unsafe Rust features are introduced. We also identify specific areas where new Rust-specific guidelines are needed. Where a guideline does not directly translate, we propose Rust-specific adaptations that preserve its intent. All mapping results and supporting artifacts are publicly available as open-source materials at this https URL.
### Title:
          Tracking a Decade of Research at the University of Nigeria, Nsukka: A Scientometric Analysis (2014-2023)
 - **Authors:** Muneer Ahmad, Joseph U Igligli
 - **Subjects:** Subjects:
Digital Libraries (cs.DL); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This study employs scientometric methods to assess the research output and performance of the University of Nigeria from 2014 to 2023. By analyzing publication trends, citation patterns, and collaboration networks, the research aims to comprehensively evaluate the university's research productivity, impact, and disciplinary focus. These research endeavors are characterized by innovation, interdisciplinary collaboration, and commitment to excellence, making the University of Nigeria a significant hub for cutting-edge research in Nigeria and beyond. The present study has been undertaken to determine the impact of the university's research and publication trends from 2014 to 2023. The study focuses on year-wise research output, citation impact at local and global levels, prominent authors and their total output, top journals, collaborating countries, and the most contributing departments of the University of Nigeria. The university's ten years of publication data indicate that 6,353 papers were published from 2014 to 2023, receiving 86,202 citations with an h-index of 39. In addition to this, the stenographical mapping of data is presented through graphs using the VOSviewer software mapping technique. The findings of this study will contribute to understanding the university's research strengths, weaknesses, and potential areas for improvement. Additionally, the results will inform evidence-based decision-making for enhancing research strategies and policies at the University of Nigeria
### Title:
          LLMs as Noisy Channels: A Shannon Perspective on Model Capacity and Scaling Laws
 - **Authors:** Xu Ouyang, Deyi Liu, Yuhang Cai, Jing Liu, Yuan Yang, Chen Zheng, Thomas Hartvigsen, Yiyuan Ma
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing scaling laws for Large Language Models (LLMs), predominantly monotonic power laws, fail to explain emerging non-monotonic phenomena such as catastrophic overtraining and quantization-induced degradation, where performance deteriorates despite increased compute. We propose the Shannon Scaling Law, a unified theoretical framework that models LLM training as information transmission over a noisy channel, grounded in the Shannon-Hartley theorem. By mapping model parameters to channel bandwidth and training tokens to signal power, our formulation explicitly captures the interaction between learning signal and intrinsic noise. This perspective reveals a fundamental Shannon capacity for LLMs: scaling model size or data without preserving a sufficient signal-to-noise ratio (SNR) inevitably amplifies noise, inducing a transition from monotonic improvement to U-shaped performance degradation. We validate our theory through experiments on Pythia and OLMo2 under perturbations, including Gaussian noise, quantization and supervised fine-tuning on math, QA and code tasks. The Shannon Scaling Law consistently outperforms classical scaling laws and recent perturbation-aware laws, achieving strong $R^2$ scores and accurately capturing loss basins missed by prior approaches. It also extrapolates: fitted on $\leq$6.9B Pythia models with $\leq$180B tokens, it predicts the unseen 12B model up to 307B tokens at pooled $R^2{=}0.847$, while monotonic baselines collapse.
## Keyword: localization
### Title:
          Inconsistency-aware Multimodal Schrödinger Bridge for Deepfake Localization
 - **Authors:** Jiayu Xiong, Jing Wang, Qi Zhang, Wanlong Wang, Jun Xue
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Audio-visual deepfake localization demands interval-level outputs that serve as temporal evidence. Despite recent progress, symmetric fusion under single-sided or asynchronous forgeries propagates cross-modal noise, degrading high-precision localization. We present IaMSB, an inconsistency-aware multimodal Schrödinger Bridge (SB) that jointly estimates cross-modal consistency and performs interval-level localization. Unlike diffusion models, SB minimizes path-distribution discrepancy and yields consistency scores without explicit noise injection or denoising. With the Schrödinger Bridge (SB), IaMSB unifies consistency estimation, cross-modal information selection, and bridge-step scheduling in one framework. Specifically, a lightweight coarse bridge first proposes candidate intervals and estimates cross-modal consistency; these statistics select cross-modal witness signals and allocate bridge steps asymmetrically across modalities. A refinement bridge then performs step-tuned fusion and outputs refined, time-aligned intervals. IaMSB anticipates single-sided and asynchronous forgeries and, using bottlenecked cross-modal interaction with step allocation, suppresses noise transfer, avoids unnecessary iterations. Across benchmarks, IaMSB stabilizes strict-IoU boundary precision, raising AP@0.95 by 3%~10%, and yields improved high-precision localization, particularly for single-sided forgeries.
### Title:
          IntentionNav: A Benchmark for Intent-Driven Object Navigation from Implicit Human Instruction
 - **Authors:** Lin Qian, Shijie Li, Sihao Lin, Xuan Zhang, Bangya Liu, Yanran Li, Hujun Yin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing object navigation benchmarks usually tell an embodied agent which object category to find, such as microwave or chair. Human-facing embodied AI is often asked something less direct: "I need something to warm this food" or "the room feels stuffy." The agent must infer the object that can satisfy the need, find a scene-grounded instance, and decide whether the goal has been reached. We study this setting as intent-driven object navigation and introduce IntentionNav, a diagnostic benchmark for active object search from implicit human instructions. Each episode provides a free-text intent, RGB-D observations, and pose, but withholds the target object name. IntentionNav contains 500 intents over 176 Isaac Sim scenes and 64 target categories. Each intent is rewritten in four controlled instruction styles and annotated with one of four intent modes, separating surface phrasing from semantic cue type under matched geometry. This paired design supports analysis of target inference, language robustness, neighborhood reachability, and terminal success rather than only aggregate success. We evaluated three VLMs using a fixed active-navigation agent. Models identify the intended target in 48.3 percent of episodes and enter its 2 m neighborhood in 68.7 percent, but terminate successfully in only 24.9 percent and achieve grounded 1 m success in 5.5 percent. Success is highest for event-script intents (28.7 percent) and lower for physical-state and affordance intents (19.2 percent and 18.5 percent), showing that indirect human intent remains a bottleneck for target selection, visual verification, and terminal localization in active embodied search.
### Title:
          Occlusion-Aware Physics-Semantic Keyframe Selection for Robust Video Editing
 - **Authors:** Lin Liu, Zhihan Xiao, Haohang Xu, Rong Cong, Zhibo Zhang, Xiaopeng Zhang, Qi Tian
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video editing has recently achieved remarkable progress with diffusion-based generative models, enabling diverse object-level manipulations from natural language instructions. However, existing methods often struggle under occlusion, viewpoint changes, and fast object motion, where unreliable visual observations lead to inaccurate localization, temporal flickering, and inconsistent edits. In this work, we identify the absence of reliable visual anchors as a fundamental bottleneck in occlusion-robust video editing. To address this issue, we propose an occlusion-aware physics-semantic keyframe selection framework that automatically identifies an optimal anchor frame for downstream editing. Specifically, our method evaluates candidate frames from three complementary perspectives: structural completeness for avoiding truncated observations, cycle-consistent tracking stability for measuring physical reliability, and vision-language-based attribute visibility for ensuring semantic clarity. The selected keyframe is then propagated through bidirectional tracking to generate dense spatiotemporal masks, which are used as auxiliary supervision for a diffusion-based video editing backbone. By transforming occlusion handling from explicit reconstruction into reliable anchor selection, our framework enables precise and temporally consistent editing without requiring manual annotations. Extensive experiments on challenging video editing benchmarks demonstrate the effectiveness and high-quality performance of our method.
### Title:
          Assessing Predictive Models for Fairness Based on Movement Patterns
 - **Authors:** Francesco Lettich, Mario A. Nascimento, Chiara Pugliese, Chiara Renso
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Assessing the spatial fairness of predictive models involves establishing whether they are statistically penalizing (favoring) individuals associated with certain geographical locations. Literature on this topic makes the fundamental assumption that each individual is assigned to a single geographical location (e.g., place of residence). However, fairness with respect to the set of locations where one has been, i.e., their movement patterns over different regions, also matters when fairness is considered. Consequently, we argue that it is necessary to generalize the notion of spatial fairness to also include movement patterns, leading to the novel problem of assessing predictive models for fairness relative to the movements of individuals. To deal with this problem, we propose an approach that first associates the movements of individuals to certain geographic regions, considering multiple spatial partitions with different resolutions and alignments, and then employs a suitable spatial scan statistic to assess whether a predictive model is fair based on movement patterns. In the experimental evaluation, we study the performance of our approach over thousands of synthetic unfair datasets, showing that it is effective at detecting this new type of unfairness and at retrieving the set of objects treated unfairly, while localization performance exhibits a consistent multi-resolution trade-off.
### Title:
          Decoupling Spatio-Temporal Adapter for Fine-Grained Badminton Action Localization
 - **Authors:** Tianyu Wang (1), Junjie Wu (1 and 2), Jingquan Gao (1), Shishuo Li (1) ((1) School of Economics and Management, Beihang University, Beijing 100191, China (2) Key Laboratory of Data Intelligence and Management, Beihang University, Ministry of Industry and Information Technology, Beijing 100191, China)
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Temporal Action Localization (TAL) has been extensively studied in generic video understanding, while fine-grained sports scenarios, such as professional badminton, remain underexplored due to their complex and subtle spatio-temporal dynamics. In this paper, we focus on fine-grained TAL in professional badminton videos and introduce a new benchmark dataset, Fine-Badminton, which consists of 31 matches with 29 fine-grained stroke categories, covering 2104 rallies and 27597 annotated actions. To effectively capture the intricate motion patterns in such scenarios, we propose a Decoupling Spatio-Temporal Adapter (DSTA), which enables efficient modeling of spatio-temporal features within a parameter-efficient framework. Specifically, DSTA decomposes motion representation into three parallel branches, capturing temporal dynamics as well as vertical and horizontal spatial variations. The design allows the model to better distinguish subtle differences among fine-grained actions. Extensive experiments on both the Fine-Badminton dataset and the ShuttleSet benchmark demonstrate that the proposed method achieves state-of-the-art performance while introducing only a marginal increase in computational and parameter cost. These results validate the effectiveness and efficiency of the proposed approach for fine-grained temporal action localization.
### Title:
          Hybrid Quantum-Classical Corrective Diffusion Modeling for Meteorological Downscaling
 - **Authors:** Rui Wang, Edoardo Pasetto, Amer Delilbasic, Morris Riedel, Kristel Michielsen, Gabriele Cavallaro
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Atmospheric and Oceanic Physics (physics.ao-ph); Quantum Physics (quant-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Statistical downscaling is a crucial component of the weather modeling field, where high-resolution outputs must be reconstructed from coarse-resolution inputs with the full cost of dynamical refinement. In this work, we investigate a hybrid quantum-classical corrective diffusion model for probabilistic statistical downscaling of weather fields. The proposed model inserts variational quantum circuit layers into the most compressed bottleneck of the diffusion UNet while leaving the regression branch fully classical. This placement tests whether quantum circuits can act as compact nonlinear feature maps for latent-channel mixing. We evaluate intra-channel and cross-channel ansätze on 10m wind components. On the 2020 validation set, the hybrid models remain stable, preserve the large-scale spatial organization of the generated wind fields, and improve both MAE and CRPS relative to a classical corrective diffusion model in several configurations. Structural diagnostics further show that the hybrid variants preserve kinetic-energy spectra and windspeed distributions similar to its classical counterpart while producing controlled changes in tail behavior, extreme-windspeed localization, and joint wind field components structure. Backend studies on the 2020 validation set show negligible impact from simulated device noise at the tested circuit scale, whereas real-hardware deployment remains limited by qubit availability and execution fidelity. The 2021 out-of-distribution test shows that these in-distribution gains do not transfer uniformly under temporal shift, revealing a generalization gap that motivates future mitigation through stabilization and regularization. These results show that bottleneck-level quantum hybridization can make a nontrivial contribution to weather statistical downscaling, while also highlighting that circuit scale and hardware deployment remain key limiting factors.
### Title:
          PathNavigate: A Training-Free Pathology Agent with Surprise-Guided Scan and Shared Slide Memory for Whole-Slide Image VQA
 - **Authors:** Chunze Yang, Qidong Liu, Wenjie Zhao, Yue Tang, Jiusong Ge, Di Zhang, Jiashuai Liu, Lei Wu, Junbo Lu, Ni Zhang, Xian Wu, Zeyu Gao, Chen Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Whole-slide image visual question answering (WSI-VQA) frames pathology as an extreme-context search problem: to answer a free-form clinical query, a system must first navigate a gigapixel slide under a strict inspection budget to locate sparse, high-resolution evidence. Existing approaches largely fall into two paradigms: i) supervised pathology multimodal large language models (MLLMs) and agents can absorb localization and reasoning into learned modules, but they often couple navigation to task-specific supervision and retraining, limiting their practicality; ii) training-free pathology agents avoid this cost by keeping core models frozen, but often follow a question-first design, constructing the initial candidate set mainly from query-conditioned relevance. This can miss decisive morphology that is not named in the question, and force heavier inference-time scaffolding. To address this challenge, we introduce PathNavigate, a training-free pathology agent built around a scan-search-readout routine. Before question matching, PathNavigate scans the current slide at low magnification with a shared online memory module over frozen pathology features, producing a slide-specific surprise field that marks an abnormal-region pool. It then applies question-conditioned PLIP relevance only within this pool to select high-magnification search targets. Finally, it extracts local high-magnification evidence and answers with a frozen perceptor-adjudicator stack, using the same online memory as slide-level context. Experiments on WSI-VQA and SlideBench-BCNB show that the proposed scan-search-readout design improves answer accuracy and yields more interpretable evidence-selection trajectories with higher this http URL code is available online.
### Title:
          Swarical: An Integrated Hierarchical Approach to Localizing Flying Light Specks
 - **Authors:** Hamed Alimohammadzadeh, Shahram Ghandeharizadeh
 - **Subjects:** Subjects:
Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Swarical, a Swarm-based hierarchical localization technique, enables miniature drones, known as Flying Light Specks (FLSs), to accurately and efficiently localize and illuminate complex 2D and 3D shapes. Its accuracy depends on the physical hardware (sensors) of FLSs, which are used to track neighboring FLSs in order to localize themselves. It uses the hardware specification to convert mesh files into point clouds that enable a swarm of FLSs to localize at the highest accuracy afforded by their hardware. Swarical considers a heterogeneous mix of FLSs with different orientations for their tracking sensors, ensuring a line of sight between a localizing FLS and its anchor FLS. We present an implementation using Raspberry cameras and ArUco markers. A comparison of Swarical with a state of the art decentralized localization technique shows that it is as accurate and more than 2x faster.
### Title:
          From Activation to Causality: Discovery of Causal Visual Representations in the Human Brain
 - **Authors:** Yuval Golbari, Navve Wasserman, Matias Cosarinsky, Roman Beliy, Aude Oliva, Antonio Torralba, Michal Irani, Tamar Rott Shaham
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Identifying which brain regions represent a visual concept in the human brain is a central challenge in neuroscience. Existing approaches have localized coarse functional regions (e.g., faces, places) through activation maximization, identifying regions that activate strongly for a target concept relative to other concepts. Yet strong activation alone does not establish that a region represents the concept itself, as responses may instead be driven by correlated visual or semantic cues. We introduce BrainCause, an automated framework that combines generative and brain models to synthesize controlled stimuli and validate neural representations through targeted causal testing. Given a query specifying a concept of interest, our framework constructs targeted stimulus sets comprising concept images, counterfactual edits that remove the target concept while preserving other image content, and images with candidate correlated distractors. It then uses an image-to-fMRI encoding model to predict brain responses and searches for representations that respond specifically to the target concept over correlated alternatives. BrainCause returns validated candidate representations and proposes follow-up fMRI experiments to further test or extend its discoveries. Our approach successfully recovers known functional localizations and identifies new candidate representations across dozens of concepts, validated on both predicted and measured fMRI data. Critically, we show that without causal validation, a large fraction of localizations would be false positives, confirming that activation alone is insufficient evidence of representation.
## Keyword: transformer
### Title:
          Tensor Cache: Eviction-conditioned Associative Memory for Transformers
 - **Authors:** Kabir Swain, Sijie Han, Daniel Karl I. Weidele, Mauro Martino, Antonio Torralba
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autoregressive Transformer KV caches grow linearly with context length; sliding-window caching bounds memory but discards evicted tokens entirely, so relevant evidence outside the window becomes inaccessible. We introduce \emph{Tensor Cache}, a two-level cache that pairs sliding-window softmax attention as a first-level cache (L1) with a fixed-size outer-product fast-weight memory as a second-level cache (L2) fed by KV pairs evicted from the window. Recent tokens remain in exact local attention; evicted pairs are compressed into a per-layer matrix $A$ and read by future queries through a single matrix multiplication, exploiting the linear-attention identity $q_t(k_i \otimes v_i)=\langle q_t,k_i\rangle v_i$. A learned scalar gate fuses the L1 and L2 outputs, and per-head decay and write-rate parameters are trained end-to-end. The outer-product memory and the read identity are well-known; our contribution is their use as an L2 cache fed exclusively by sliding-window evictions, plus identifying that the common chunked-mean training shortcut $A\!\leftarrow\!\lambda A\!+\!\eta(\bar k\!\otimes\!\bar v)$ silently introduces $C^2{-}C$ spurious cross-token outer products per chunk, and closing the gap with a parallel weighted-sum scan equivalent to per-token writes within float32 epsilon. Across systems scaling, controlled associative recall, long-context language modeling, and memory-capacity diagnostics, Tensor Cache improves the memory--quality frontier over bounded-state baselines.
### Title:
          SCRIPT: Scalable Diffusion Policy with Multi-stage Training for Language-driven Physics-Based Humanoid Control
 - **Authors:** Jingyan Zhang, Han Liang, Ruichi Zhang, Bin Li, Juze Zhang, Xin Chen, Jingya Wang, Lan Xu, Jingyi Yu
 - **Subjects:** Subjects:
Graphics (cs.GR); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Controlling physics-based humanoids from natural-language instructions is a critical step toward general-purpose embodied agents. However, existing methods remain constrained by a tension between semantic expressiveness and physical feasibility, often failing to jointly achieve faithful instruction following, high-quality motion, and stable long-horizon control. We propose SCRIPT, a scalable diffusion policy with a multi-stage training framework for language-driven physics-based humanoid control. The core of SCRIPT is a Joint Action-State-Text Diffusion Transformer (JAST-DiT), which represents actions, physical states, and text as dedicated token streams and couples them through joint attention, enabling direct interaction between language semantics and control dynamics. To stabilize autoregressive control, we introduce a nonlinear history conditioning mechanism, which preserves the dense recent context and samples increasingly sparse cues from long-term history. Beyond supervised imitation pre-training, we propose a post-training stage, further improving the performance using Reinforcement Learning with Hybrid Rewards (RLHR). By injecting learnable noise into the flow-sampling process, RLHR effectively improves motion quality and instruction following within closed-loop simulations using hybrid physical feedback and text rewards. Quantitative evaluations demonstrate that SCRIPT outperforms prior state-of-the-art methods, with gains across text alignment, motion quality, and physical realism metrics. Furthermore, scaling studies on the 1200-hour MotionMillion dataset demonstrate consistent performance gains with model scaling, highlighting SCRIPT's robust scalability for large-scale pre-training. Our code will be publicly available for future research.
### Title:
          ACALSim: A Scalable Parallel Simulation Framework for High-Performance System Design Space Exploration
 - **Authors:** Wei-Fen Lin, Jen-Chien Chang, Yen-Po Chen, Zi-Yi Tai, Yu-Cheng Chang, Chia-Pao Chiang, Yu-Yang Lee, Yu-Jie Wan
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Performance (cs.PF)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Architectural simulation has become the critical bottleneck limiting design space exploration for high-performance computing systems. Modern GPUs and AI accelerators -- with hundreds to thousands of tightly-coupled components -- demand simulation frameworks that deliver efficient parallelism and scalable single-node execution. Existing frameworks fall short: SST focuses on multi-node MPI scalability but struggles with intra-node scaling, while GPGPU-Sim remains largely single-threaded. Critically, none expose a mechanism for users to optimize threading for their specific workloads. We introduce ACALSim, a scalable parallel simulation framework providing infrastructure and APIs for building high-performance simulators -- timing-model accuracy remains the responsibility of simulator developers. Its key innovation is a pluggable thread-management architecture that lets developers implement custom scheduling strategies tailored to specific simulation patterns, absent in existing frameworks. Complementing it are (1) event-driven execution with fast-forward to eliminate idle-cycle overhead, (2) a shared-memory data model enabling zero-copy communication, and (3) a two-phase parallel execution model for deterministic thread scaling. We demonstrate ACALSim through HPCSim, a GPU simulator targeting A100-class architectures. Against an SST implementation using identical shared timing cores to isolate framework overhead, ACALSim achieves over 14x speedup with 41% lower memory footprint; hardware validation confirms 0.72--1.22x cycle-count correlation with A100 measurements. While SST fails to complete 256+ thread-block workloads within practical time limits, ACALSim simulates full LLaMA transformer layers (single block) in 17.7 minutes for LLaMA-7B and 30.4 minutes for LLaMA-13B -- enabling design space exploration that SST cannot achieve.
### Title:
          Improved Vision-to-Chart Buoy Association with Learned World-to-Image Projection
 - **Authors:** Borja Carrillo-Perez (Arquimea Research Center)
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This report presents a lightweight modification to the DETR-based fusion transformer baseline for the MaCVi 2026 Vision-to-Chart data association challenge. The challenge baseline decoder receives per-buoy queries encoding world-space distance and bearing, forcing the transformer to implicitly learn the complex geometric projection from world coordinates to image pixels. Instead, this work trains an additional dedicated MLP, QueryMLP, to explicitly predict the buoy's waterline contact point in the image from chart measurements and IMU orientation data. The predicted pixel coordinates are appended to the baseline decoder query vector, providing a direct spatial prior per buoy and reducing the geometric reasoning burden on the transformer decoder. On the challenge leaderboard, the presented approach achieves an Overall score of 0.7386, with F1 = 0.8055 and mIoU = 0.6718, on the held-out test set, placing second among all submissions.
### Title:
          Certification from Examples is Hard for Circuits and Transformers under Minimal Overparametrization
 - **Authors:** Artur Back de Luca, Kimon Fountoulakis
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As state-of-the-art neural networks are deployed on reasoning and algorithmic tasks, exactness guarantees become increasingly important. However, high average-case accuracy can still mask inconsistent behaviors. This motivates exact certification, which asks for the smallest set of labeled examples needed to certify that a learned hypothesis equals the target. We show that while some hypotheses are easy to certify, even minimal overparametrization can make certification exponentially hard across several hypothesis classes. For threshold circuits of depth $\ge 2$, adding a single extra gate can force certificate sizes exponential in the input dimension. We show an analogous hardness result for log-precision Transformers with only constant architectural overhead. We also characterize approximate certification, showing that allowing only polynomially many mistakes still requires exponentially large certificates, whereas constant relative-error guarantees can hide exponentially many mistakes. Empirically, we study certification for constructed circuits and trained Transformers for recognizing binary addition. While the constructed circuits instantiate the exponential barrier for certification, the trained Transformer analysis shows that imperfect models can evade detection by large uniformly sampled certificate candidates.
### Title:
          CoMoGen: COntrollable MOtion Dynamics and Interactions with Mask-Guided Video GENeration
 - **Authors:** Adil Meric, Lin Geng Foo, Mert Kiray, Benjamin Busam, Rishabh Dabral, Christian Theobalt
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present CoMoGen, a controllable video generation framework that generates realistic interactive dynamics from a single binary mask sequence conditioned on an input image. CoMoGen introduces a lightweight MaskAdapter that encodes binary mask sequences into a latent residual signal, injected into the Multi Modal Diffusion Transformer (MMDiT) model through a cosine-weighted schedule. Unlike the hierarchical coarse-to-fine design of UNet architectures, MMDiT operates as a sequence of uniform transformer blocks, making it difficult to identify which layers are responsible for the motion generation. Therefore, we propose a novel way to determine "Motion Layers" operating in the attention space of MMDiT. We fine-tune the model by using Low-Rank Adaptation (LoRA) to the Motion Layers, without requiring any architecture change in the MMDiT. This selective adaptation enables our method to focus on motion-critical components, yielding reduced computational cost. Despite its simplicity, CoMoGen enables precise subject motion and plausible interactions with surrounding humans, objects, and scenes. Comprehensive experiments on different datasets show that CoMoGen consistently outperforms prior controllable video generation methods and achieves state-of-the-art performance in motion fidelity and perceptual realism. Project page: this http URL.
### Title:
          The Deterministic Horizon: Impossibility Results as Design Specifications for Trustworthy AI Systems
 - **Authors:** Dongxin Guo
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computational Complexity (cs.CC); Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models now write software, draft legal documents, and produce clinical notes, yet fundamental limits, from Turing and Arrow to the No Free Lunch theorems, shape what computation can do. This thesis turns such impossibility results from curiosities into design rules. Its flagship result proves an accuracy ceiling set by architecture alone: past a critical reasoning depth, no amount of training moves it, at any adapter rank, sample size, or loss function. Computable before deployment from layer count and embedding width, this Deterministic Horizon is measured between nineteen and thirty-one across twelve transformer architectures, and fine-tuning on optimal-length traces recovers under four percentage points. The mechanism is a capacity invariant of the residual stream, and an information-theoretic conversion yields super-exponential accuracy decay past the horizon. An unconditional circuit-complexity lower bound for modular exponentiation against constant-depth prime-modulus circuits complements this result. The same argument recasts across subfields: preference learning under any misspecified model jumps discontinuously in sample complexity; multi-stage retrieval pipelines require at least as many independent metrics as stages; standard truthful auctions fail for agents with prompt-dependent valuations; and zero-knowledge verification of neural inference pays a measured overhead of one hundred ten to one hundred ninety times per non-linear activation. Together these form a catalogue of sixteen specifications, each pairing a computable boundary, a quantified violation cost, and a constructive design rule: two compositions are proved, one pairing is an honest obstruction, and four remain open. The impossibility-specification methodology is offered for the generative research programme that trustworthy AI may need. Every fundamental limit of AI is also a design rule.
### Title:
          World Machine: Towards Generative World Modeling for Time-Series
 - **Authors:** Elton Cardoso do Nascimento, Alexandre da Silva Simões, Esther Luna Colombini, Ricardo Ribeiro Gudwin, Paula Dornhofer Paro Costa
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World models represent a paradigm shift in generative AI, pursuing predictive understanding and controllable simulation of environments in a structured and generalizable way. We present World Machine, a generative world-modeling architecture for time series. It is a transformer-based architecture with latent states that enables adaptation to different amounts of observed data and contexts. This shows an improvement over traditional transformers, which have a computational and memory cost that scales quadratically with the context. Experiments on a proposed synthetic dataset, Toy1D, validate the approach's feasibility, demonstrate capabilities not found in conventional transformers, and highlight the contributions of each component of the training protocol.
### Title:
          DFKI-MLT at SemEval-2026 TASK 7: Steering Multilingual Models Towards Cultural Knowledge
 - **Authors:** Yusser Al Ghussin, Daniil Gurgurov, Yasser Hamidullah, Josef van Genabith, Cristina España-Bonet, Simon Ostermann
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) are increasingly used across diverse linguistic and cultural contexts, yet their cultural knowledge remains uneven across regions and languages. We present the DFKI-MLT system for SemEval-2026 Task 7 on cultural awareness, where we apply activation steering to multilingual LLMs using language vectors extracted from parallel FLORES data. Our method performs inference-time adaptation by adding language-specific steering vectors to the residual stream at a selected transformer layer, without any parameter updates. We participated in both the short-answer (SAQ) and multiple-choice (MCQ) tracks; however, only our MCQ submission received an official score. In the official MCQ track, we achieved 86.96% accuracy, ranking 7th out of 17 teams. To better understand system behavior, we conduct post-hoc analyses on the shared-task MCQ and SAQ settings. These analyses show that activation steering yields modest and heterogeneous improvements on cultural reasoning: gains are strongly layer-sensitive, vary substantially across language-region pairs, with some configurations even degrading performance, and interact with prompt formulation, comparing generic and culturally conditioned prompts. Our findings suggest that prompt design and activation steering should be jointly optimized for culturally aware multilingual inference.
### Title:
          CALAD: Channel-Aware contrastive Learning for multivariate time series Anomaly Detection
 - **Authors:** Jaehyeop Hong, Youngbum Hur
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multivariate time series anomaly detection has become increasingly important in real-world applications, where labeled data are often scarce. Many existing approaches rely on unsupervised learning to model normal patterns, but they often treat all channels equally. This design can dilute anomaly-relevant signals, since not all channels contribute equally to anomaly detection. In this paper, we propose CALAD, a channel-aware contrastive learning framework for multivariate time series anomaly detection. CALAD governs the construction of contrastive samples using estimated channel relevance, allowing the learning process to reflect anomaly semantics rather than generic similarity. Channel relevance is estimated from reconstruction errors of a transformer-based autoencoder and is used to distinguish channels that are more influential to anomalous behaviors. Using this information, we design a channel-wise augmentation strategy in which positive and negative samples are constructed based on whether anomaly-relevant channels are preserved or perturbed. This encourages invariance to changes in irrelevant channels while being sensitive to changes in anomaly-relevant channels. Furthermore, CALAD combines contrastive learning and an auxiliary reconstruction head, allowing the model to learn discriminative representations while retaining normal structures. Experiments on multiple real-world datasets shows that CALAD consistently outperforms existing methods, particularly under distribution shift scenarios. We provide the code for reproducibility at this https URL
### Title:
          Composing People Together: Iterative Pose-Image Generation for Multi-Person Interaction Scenes
 - **Authors:** Wenxuan Peng, Bharath Hariharan, Hadar Averbuch-Elor
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite recent progress, text-to-image models still struggle to generate semantically diverse and compositionally accurate multi-person interaction scenes, often collapsing to repetitive layouts, stereotypical poses, and poorly grounded interactions. In this work, we bridge this gap by introducing a dual pose-image representation that brings person-centric structural priors into pretrained diffusion transformers. Our model jointly predicts a 2D pose visualization image and its corresponding RGB image, enabling structure and appearance to co-evolve during learning. At its core, a cross-modal alignment scheme binds text, pose, and image representations, ensuring consistent grounding across modalities. Furthermore, we design an iterative scene construction scheme, progressively generating complex multi-human interactions while effectively decomposing the overall generation complexity. Extensive experiments demonstrate that our method substantially improves prompt alignment and scene diversity in multi-person image generation.
### Title:
          SpikingMoE: SDPrompt-Guided Dynamic Expert Fusion in Spiking Neural Networks
 - **Authors:** Yukai Yang, Chenxi Qin, Jungang Li, Xin Zhang, Wenwei Shao, Liqun Chen
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spiking Neural Networks (SNNs) provide an energy-efficient paradigm for visual recognition. We present SpikingMoE, which integrates a spike-driven Transformer with a Mixture-of-Experts (MoE) framework for dynamic computation. Inspired by the lateral geniculate nucleus (LGN), a spike-driven prompt (SDprompt) enables input-dependent expert routing in a biologically plausible manner. By replacing standard MLPs with spike-compatible expert modules and enforcing binary spike communication, SpikingMoE is designed for neuromorphic hardware. Experiments on CIFAR-10 and CIFAR-100 achieve 94.09% and 74.54% top-1 accuracy, showing that modular expert routing can be incorporated while retaining reasonable performance. To our knowledge, SpikingMoE is the first open-source SNN framework that integrates MoE into a spike-driven Transformer with LGN-inspired routing.
### Title:
          Scalable Heterogeneous Graph Foundation Models for Data-Driven Optimal Power Flow in Smart Grids
 - **Authors:** Massimiliano Lupo Pasini, Yijiang Li, Kibaek Kim, Teja Kuruganti
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fast and reliable optimal power flow (OPF) approximation is essential for reliable smart-grid operation, yet many learning-based surrogates either flatten the native heterogeneous structure of power networks, target a limited set of grid topologies, or lack scalable infrastructure for graph foundation model (GFM) training. This paper presents a scalable heterogeneous graph neural network (GNN) workflow, built on HydraGNN, for data-driven OPF surrogate modeling and OPF-GFM development. The workflow preserves the distinct node and edge types of power grids -- buses, generators, loads, shunts, AC lines, transformers, and device-to-bus couplings -- and supports distributed preprocessing, training, hyperparameter optimization (HPO), and downstream fine-tuning on leadership-class supercomputers. Using three million heterogeneous graph instances spanning ten PGLib-OPF cases, from 14 to 13,659 buses, we conduct DeepHyper-driven HPO on the ORNL Frontier supercomputer. The campaign identifies compact models ($\sim$1.6--1.7M parameters) with the lowest validation losses. Downstream experiments on feasibility classification and N-1 contingency regression show that fine-tuning pretrained OPF GFM improves low-data accuracy, stabilizes training, accelerates convergence, and reduces adaptation cost when partial or head-only fine-tuning is used.
### Title:
          FastKernels: Benchmarking GPU Kernel Generation in Production
 - **Authors:** Gabriele Oliaro, Yichao Fu, May Jiang, Owen Lu, Junli Wang, Zhihao Jia, Hao Zhang, Samyam Rajbhandari
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLM-based agents for GPU kernel generation are advancing rapidly, yet their progress is fundamentally constrained by the benchmarks they optimize against. Existing benchmarks are poorly aligned with production inference frameworks: they evaluate kernels on a single GPU with synthetic inputs, ignore the surrounding compilation stack, and reward replicating known optimizations rather than discovering new ones. The resulting reward signals are misleading: agents learn to generate kernels that score well in sandboxes but introduce interface incompatibilities, compilation-stack conflicts, and silent correctness degradation when integrated into real systems. We introduce FastKernels, a kernel benchmark built around a minimal set of 46 representative architectures spanning 8 categories, whose kernels collectively subsume those of 96.2% (409/425) of HuggingFace Transformers architectures. FastKernels doubles as a minimalistic, production-grade inference framework that runs at parity with hardened systems such as vLLM and SGLang on mainstream LLM serving and substantially exceeds upstream references on under-served architectures; each task's interface mirrors the corresponding module in the state-of-the-art library for its architecture family, enabling direct deployment of optimized kernels into production codebases. Evaluating state-of-the-art kernel agents on FastKernels, we find that even the strongest agent achieves only 0.94$\times$ aggregate speedup over production baselines, with weaker agents at $0.78\times$ and $0.53\times$ -- confirming that benchmark-production misalignment is a critical bottleneck for the field. We release FastKernels as a stepping stone toward kernel agents whose benchmark gains translate directly into production throughput improvements. Code is available at this https URL
### Title:
          SCOPE: Simulating Cross-game Operations in Playable Environments for FPS World Models
 - **Authors:** Zizhao Tong, Hongfeng Lai, Zeqing Wang, Zhaohu Xing, Kexu Cheng, Haoran Xu, Zhao Pu, Shangwen Zhu, Ruili Feng, Jian Zhao, Yan Zhang, Hao Tang, Yeying Jin, Ling Shao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Interactive world models for first-person shooter (FPS) games must resolve high-frequency overlapping control signals at every frame without disrupting unaffected regions. Existing methods inject actions globally and train on single titles, failing under dense FPS inputs. We observe that FPS actions are spatially selective: discrete events such as firing or reloading affect only a localized region around the weapon (the scope), while continuous camera and movement signals govern stable surroundings. We propose SCOPE, which inserts a conditioning module into each transformer block of a pretrained video diffusion model. It reshapes features into per-pixel temporal sequences so that each position computes its action response from local visual content. This separates in-scope effects from out-of-scope generation without segmentation labels. We also introduce CrossFPS, the first multi-game FPS dataset with frame-aligned action telemetry. It comprises 69K clips from 7 titles with 10-DoF controller signals, curated to remove gameplay bias. The model learns general visual-to-action mappings rather than game-specific patterns, enabling zero-shot transfer to unseen scenes. Experiments confirm strong action responsiveness, precise scope separation, and effective cross-game generalization.
### Title:
          Every Component is a Lookup: Token Attribution and Composition from a Single Decomposition
 - **Authors:** Po-Kai Chen, Niki van Stein, Aske Plaat
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mechanistic interpretability of transformers requires identifying not just which components matter but how they compose into the computational route that produced a prediction. Both attention and MLP follow a shared key-value template $\phi(S)U$. We exploit this structure to develop Unpack, a backward recursion that decomposes credit through both sublayers, producing interaction strengths between any two components, named end-to-end paths with K/Q/V composition labels, and per-token attribution from a single forward pass, without intervention, gradients, or auxiliary training. We evaluate on the indirect object identification task. On GPT-2 small, the method recovers all three composition connections described by Wang et al. (2023), including the mode-specific routing of each connection (K, Q, or V). To test token-level attribution beyond trivial copying, we compare two occurrences of the same name in the same decomposition: the first mention retains strong credit while the duplicate-detection position is suppressed, a pattern absent in matched control prompts. Across the Pythia family from 160M to 6.9B parameters, this suppression pattern is consistently recovered at every scale, demonstrating that the method tracks mechanistic structure without ground-truth circuit labels. Code is available at this https URL.
### Title:
          FAST-ME: Foundation-aware Adaptive Stopping for Motion Estimation for Efficient IoT Video Analysis
 - **Authors:** Kakia Panagidi, Stathes Hadjieftymiadis
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In modern multimedia systems, efficient video processing is critical, especially in resource-constrained environments such as IoT-based camera networks, autonomous platforms, and wireless sensor multimedia systems. A key bottleneck in video compression and understanding is block motion estimation (ME), a process that remains computationally expensive despite the development of fast search techniques. This work introduces an Optimal Stopping Theory (OST) algorithm for block motion estimation based on the assessment of spatiotemporal differences within and across video frames. It also proposes a semantic-aware motion estimation framework that integrates Foundation Models (FMs) with the OST-based decision process. By leveraging pretrained visual models such as Vision Transformers (ViT) and the Segment Anything Model (SAM), the framework extracts semantic attention scores that indicate the importance of motion within specific spatial regions. These scores are fused with traditional distortion-based metrics, such as the Sum of Absolute Differences (SAD), to guide a hybrid stopping criterion that jointly considers motion magnitude and semantic relevance. The resulting adaptive algorithm stops early in redundant regions while continuing the search in areas where motion is semantically significant. Experiments compare the proposed solution with widely used approaches from the literature on benchmark and multimodal video datasets. The proposed method achieves a significant reduction in computation with minimal accuracy loss and improved semantic coverage. The results highlight the benefits of bridging low-level motion analysis with high-level semantic reasoning, offering a promising direction for efficient multimodal video understanding in next-generation smart systems.
### Title:
          DFSAttn: Dynamic Fine-grained Sparse Attention for Efficient Video Generation
 - **Authors:** Jie Hu, Zixiang Gao, Yutong He, Kun Yuan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion transformers have achieved remarkable success in high-quality video generation, yet their reliance on spatiotemporal 3D full attention incurs prohibitive computational cost due to the quadratic complexity of attention. Block sparse attention is a common approach to mitigate this by focusing computation on important regions. However, attention maps in DiTs exhibit inherently dynamic and fine-grained sparsity, which causes existing block sparse attention methods to degrade significantly in quality, especially at high sparsity ratios. In this paper, we revisit block sparse attention and derive a theoretical lower bound on attention recall to characterize the key factors governing its effectiveness. Guided by these insights, we propose DFSAttn, a training-free sparse attention framework that enables dynamic, fine-grained sparsification efficiently. DFSAttn incorporates three core designs: Hilbert curve-based token reordering to achieve fine-grained sparsity while preserving efficient GPU execution, hierarchical block scoring for accurate block importance estimation, and sparse mask caching with adaptive ratios to balance accuracy and efficiency. Experimental results demonstrate that DFSAttn consistently outperforms prior methods under high sparsity, achieving up to 2.1$\times$ end-to-end speedup while maintaining high generation quality. Our code is open-sourced and available at this https URL.
### Title:
          Weisfeiler-Leman Is Incomplete on Simple Spectrum Graphs, so Canonicalize Them
 - **Authors:** Snir Hordan, Nadav Dym, Tim Seppelt
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Combinatorics (math.CO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Graphs with a simple spectrum admit cubic-time isomorphism testing, yet we prove that for every natural number $k$, the $k$-Weisfeiler-Leman ($k$-WL) test cannot distinguish all non-isomorphic graphs with a simple spectrum. As the WL hierarchy upper-bounds the distinguishing power of widely-used Graph Neural Networks (GNNs), this incompleteness applies to all such GNNs, ruling out completeness for every $k$-WL-aligned GNN family. To close this gap, we introduce PRiSM (Partition, Refine, Solve, Match), the first provably complete canonicalization of simple-spectrum eigendecompositions. PRiSM obtains the completeness guarantee that prior canonicalizations provably lack, and resolves the open problem of achieving complete expressivity on simple-spectrum graphs. When composed with DeepSets or a Transformer, PRiSM achieves universal approximation on simple-spectrum graphs, justifying the use of canonicalized Laplacian positional encodings. Empirically, PRiSM performs comparably to or outperforms existing spectral canonicalizations on graph regression, classification, and expressivity
### Title:
          Class-Dependent Hybrid Data Augmentation for Multiclass Migraine Classification under Severe Class Imbalance
 - **Authors:** Elvin Somón, Miguel A. Gutiérrez-Naranjo
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We conducted a reproducibility-oriented re-evaluation of prior migraine classification studies, correcting for data leakage and metric bias. We then introduced (i) a clinically motivated aggregation of two hemiplegic subtypes following ICHD-3 §1.2.3, (ii) a class-dependent hybrid augmentation strategy that assigns generation methods based on per-class sample size, and (iii) the concept of fidelity asymmetry, motivating proportionally constrained growth as an alternative to full class balance. Experiments were performed on a dataset of 400 patients across seven migraine subtypes under a two-stage protocol, including the six-class configuration described above. Models were evaluated using stratified 5-fold cross-validation with macro-averaged F1 as the primary metric. Correcting methodological flaws reduces previously inflated performance estimates, with the corrected macro-F1 baseline standing at 0.71. The proposed framework consistently outperformed individual augmenters in macro-F1 averaged across the eight evaluated classifiers (0.862 vs. 0.836 for Gaussian Copula, 0.815 for CTGAN, and 0.801 for the no-augmentation baseline), and achieved its peak result of 0.914 with FT-Transformer under proportional augmentation. The no-augmentation FT-Transformer baseline (0.896) shows that, at the per-classifier ceiling, clinically motivated class aggregation accounts for most of the absolute improvement; the framework's principal measurable contribution is the gain in average robustness across classifiers, highlighting the dominant role of problem formulation.
### Title:
          OptiQU: Coordinated Multi-Level Voltage and Reactive Power Control for Enhanced Voltage Quality and Secure Grid Operation
 - **Authors:** Irene Hammermeister, Eric Tönges, Nils Bornhorst, Johannes Heid, Gabriela Fritzler, Timo Rehwald, Andrea Schoen, Ronald Halbauer, Jan Meschede, Michael Kramer, Julia Holl, Sina Straußberger, Andrey Luzhbin, Maximilian Niedhammer, Mischa Geiger, Aaron Eicker, Maurice Raetsch, Alfio Spina, Johannes Dieplinger, Christian Mayer, Josef Bayer, Thorsten Reske, Dominik Hilbrich
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern low-voltage (LV) distribution grids face rising shares of photovoltaic generation and high-power loads such as heat pumps and electric vehicle charging stations. Due to high simultaneity, voltage constraints often become binding before thermal limits, triggering costly conventional grid reinforcement measures. Existing voltage and reactive power control in LV grids - e.g., fixed cos($\phi$) or Q(V) control of distributed generators, on-load tap-changing distribution transformers, and line voltage regulators - is typically applied locally and independently, leaving reactive power flexibility potential unused. This paper presents OptiQU, a coordinated voltage and reactive power control concept for medium-voltage (MV) and LV distribution grids, combining centralised optimisation with decentralised local control and fallback strategies. The approach coordinates operational targets and setpoints across MV and LV (e.g., DER reactive power and substation equipment) to mitigate voltage violations and curtailment and to increase hosting capacity, while enabling robust operation under limited communication. The concepts are being evaluated using representative MV/LV models in simulation and lab environments and will be validated in field tests with two German DSOs. Based on existing research, the coordinated approach is expected to increase the exploitable flexibility for upstream voltage and reactive power control. The planned evaluation will quantify this potential and investigate trade-offs between performance, communication effort, and resilience.
### Title:
          MDS-DETR: DETR with Masked Duplicate Suppressor
 - **Authors:** Chanho Lee, Seunghee Koh, Yunho Jeon, Junmo Kim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The DEtection TRansformer (DETR) is a powerful end-to-end object detector, yet its one-to-one matching strategy suffers from slow convergence and low recall. A common approach to address this issue is to use one-to-many label assignment to provide more positive samples. However, existing methods that use one-to-many matching as an auxiliary objective lead to increased training costs, with their auxiliary decoders discarded during inference. To address this limitation, we propose MDS-DETR, which leverages both one-to-one and one-to-many supervision within a single decoder. Specifically, we introduce a Masked Duplicate Suppressor (MDS) that injects asymmetry into self-attention via confidence-based causal masking. MDS filters out the duplicates generated by the one-to-many supervised layer, enables explainable, duplicate-free predictions in a fully end-to-end framework. MDS-DETR outperforms existing one-to-many DETR variants such as MS-DETR, this http URL and Relation-DETR, without relying on any additional queries or auxiliary decoders. Under a 12-epoch training schedule on MS COCO with a ResNet-50 backbone, MDS-DETR achieves a +2.8 mAP improvement over Deformable-DETR with only a 5\% increase in training time, and outperforms the state-of-the-art this http URL by +0.3 mAP while being even 20\% faster in training. Our code and models are available at \href{this https URL}{this https URL}.
### Title:
          Multi-Factor Trust-Driven Secure Communication Model for Cloud-Based Digital Twins
 - **Authors:** Deepika Saxena, Ashutosh Kumar Singh
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cloud-based Digital Twin (DT) platforms enable real-time monitoring, simulation, and collaborative decision-making across distributed clients. However, ensuring secure and trustworthy communication remains a critical challenge due to heterogeneous client behavior, resource contention, and evolving adversarial threats. This paper proposes the Multi-Factor Trust-Driven Secure Communication (MT-SeCom) framework to enforce resilient and intelligent collaboration in DT-enabled cloud environments. MT-SeCom operates through four coordinated phases: (i) Multi-Factor Trust Monitoring, capturing temporal, contextual, and federated trust signals; (ii) Adaptive Trust Evaluation, adjusting trust weights based on network dynamics and threat intensity; (iii) Transformer-Based Trusted Client Classification, combining anomaly detection with supervised learning to accurately identify malicious or unreliable nodes; and (iv) Resilient Communication Management, optimizing routing, isolating compromised clients, and ensuring service continuity. A real-world testbed and comprehensive experiments demonstrate that MT-SeCom significantly enhances secure communication, mitigates cascading adversarial effects, and maintains high resilience under fluctuating attack conditions. MT-SeCom achieves an average 18.7% improvement in threat detection accuracy and a 24.3% reduction in anomaly occurrences compared to existing methods, confirming its robustness, scalability, and practical suitability for heterogeneous cloud-based DT ecosystems.
### Title:
          Preisach Attention: A Hysteretic Model of Sequential Memory
 - **Authors:** Piotr Frydrych
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Disordered Systems and Neural Networks (cond-mat.dis-nn); Artificial Intelligence (cs.AI); Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce the Preisach Attention Layer (PAL), a novel sequence modelling architecture grounded in the classical Preisach hysteresis operator from mathematical physics. PAL replaces the softmax attention mechanism with a binary relay operator parameterised by learned activation and deactivation thresholds, maintaining a stack of local extrema as its internal state. A single-layer PAL-Transformer with O(1) depth is Turing-complete under arbitrary precision arithmetic, achievable through simulation of a two-stack pushdown automaton -- in contrast to the O(log n) depth required by standard hard-attention transformers. Second, we prove that the function classes computable by PAL and by the transformer are incomparable: PAL computes historical range statistics in O(1) layers that require O(log n) layers for transformers, while transformers support random-access retrieval that PAL cannot perform without auxiliary state. The separating property is rate-independence -- PAL responds only to the sequence of local extrema, not to absolute token positions or temporal spacing. Third, we show that the extremum stack constitutes a minimal sufficient statistic of the input history for all rate-independent functionals, providing a formal analogue of the wiping property in classical hysteresis theory. PAL is thus an efficient architecture for tasks with long episodic memory and weak positional dependence, with O(n log n) total inference cost versus O(n^2) for standard attention.
### Title:
          Kernel-Based ReLU Approximation for Homomorphic Encryption-Compatible Privacy-preserving Deep Learning Models
 - **Authors:** Dimitrios Sygletos, Dimitra Papatsaroucha, Marios Choudetsanakis, Ilias Politis, Evangelos K. Markakis
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As privacy concerns in AI technologies continue to grow, Homomorphic Encryption (HE) offers a way to perform computations on encrypted data without the need of decryption during operations. However, HE is limited to addition and multiplication, making non-linear functions incompatible in their original form. This limitation has become more critical with the widespread use of Large Language Models (LLMs), where the non-linearity of activation functions such as the Rectified Linear Unit (ReLU) poses challenges for deployment in privacy-preserving Natural Language Processing (NLP) settings. This paper proposes a kernel-based approximation of ReLU, enabling its use within HE-constrained settings and thus contributing a critical step toward supporting privacy-preserving LLMs. A smooth kernel-based function, mimicking ReLU, is approximated using a second-degree polynomial, inspired by Jackson's theorem, to achieve low multiplicative depth. The proposed method is trained and assessed directly on token embeddings from pre-trained LLMs and evaluated in various scenarios, from simulated and tokenized data to deep learning and transformer models. Results show improved approximation fidelity, supporting the method's suitability for secure and privacy-preserving inference in various tasks.
### Title:
          Recursive Block-Diagonal Coupling for Resource-Efficient Training of Vision Models
 - **Authors:** Maxim Henry, Adrien Deliège, Sébastien Piérard, Marc Van Droogenbroeck
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Training high-capacity vision models from scratch requires substantial computational resources. To improve training efficiency of a wide target model, existing growth methods often assume the availability of narrower models, obscuring the true computational cost of the entire pipeline. We propose an efficient training protocol, RBDC, that builds wide models by coupling in a parameter-free block-diagonal way narrower, independently trained models in a recursive way. This allows a flexible allocation of the training budget available across all the models involved. Evaluated with vision transformers (DeiT) and convolutional networks (ResNet) on ImageNet, our RBDC training protocol shows a much better efficiency than models trained from scratch with the standard protocol, yielding 30% FLOPs reduction at similar test accuracies. It also achieves higher performances at same training FLOPs than training protocols from the model growth literature. Finally, we show that our models can serve as better backbones than their original counterparts for downstream object detection and instance segmentation tasks.
### Title:
          Metadata Predictability Is Not Evidence Dependence: An Intervention-Based Audit for Weak-Label Benchmarks
 - **Authors:** Kan Shao
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study a protocol-level test for weak-label benchmarks: whether benchmark outputs change when the provided evidence is intervened on. Metadata-only shortcut checks answer a different question, namely whether outputs are predictable from metadata priors. We therefore combine a metadata statistic, the Metadata Prior Dominance Score (MPDS), with an evidence-intervention statistic, {\Delta}Evi, measuring sensitivity to evidence identity under cross-item shuffling. Synthetic HotpotQA gives a constructed counterexample to metadata-only screening: MPDS is only moderate (0.643), yet {\Delta}Evi is zero. Stronger-reader reruns show why calibration belongs in the test procedure: SNLI shows a calibration reversal, reconstructed HotpotQA occupies a question-dominant warning region, and FEVER is a strongly evidence-sensitive positive control across four transformers. The practical lesson is simple: benchmark audits should report metadata-only screening, evidence intervention, and reader-strength calibration together.
### Title:
          Weierstrass Positional Encoding for Vision Transformers
 - **Authors:** Zhihang Xin, Rui Wang, Xitong Hu, Xiaojun Wu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformers have achieved remarkable success in computer vision, but their common use of learnable one-dimensional positional encodings weakens the inherent two-dimensional spatial structure of images after patch flattening. Existing positional encodings often lack geometric constraints and do not preserve a monotonic relationship between Euclidean spatial distances and sequential index distances, limiting ViTs' ability to exploit spatial proximity priors. Motivated by the usefulness of periodicity in positional encoding, we propose Weierstrass elliptic Positional Encoding (WePE), a mathematically grounded method for encoding two-dimensional coordinates in the complex domain. WePE maps normalized 2D patch coordinates onto the complex plane and constructs compact four-dimensional positional features using the Weierstrass elliptic function and its derivative. The double periodicity provides a principled representation of 2D positions, and its intrinsic lattice structure naturally matches the regular geometry of image patch grids. Its nonlinear geometric properties help model spatial distance relationships more faithfully, while the algebraic addition formula enables relative positional information between arbitrary patch pairs to be derived directly from their absolute encodings. WePE is plug-and-play and resolution-agnostic, allowing seamless integration into existing ViTs. Extensive experiments show that WePE brings consistent performance gains in most settings. With precomputed lookup tables, these improvements introduce no noticeable computational or memory overhead. Additional analyses and ablation studies further validate the effectiveness of the proposed method.
### Title:
          Revitalizing Dense Material Segmentation: Stabilized Vision Transformers and the Generalization Paradox
 - **Authors:** Allan Kazakov, Duygu Cakir, Hilal Kurt İrfanoğlu, Yavuz İrfanoğlu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Material segmentation, the pixel-wise classification of physical surface properties, remains a challenging problem in computer vision, requiring physicochemical understanding distinct from object-centric parsing. Despite the introduction of the rigorous Apple Dense Material Segmentation (DMS) dataset, the benchmark has suffered from attrition and stagnation, increasingly overshadowed by geometry-biased foundation models. In this paper, we revive the Apple-DMS benchmark to establish a modern Vision Transformer baseline. We conduct an exhaustive evaluation of SegFormer and Mask2Former architectures, revealing that standard training paradigms fail on amorphous texture fields due to high-variance gradients. To address this, we introduce a stabilized training recipe featuring High-Fidelity Logit Projection, Query Entropy Regularization, and a domain-specific, physics-compliant augmentation pipeline. Our optimized SegFormer-B5 achieves a new State-of-the-Art (SOTA) of 0.4572 mIoU on the original dataset split, significantly surpassing the prior convolutional baseline. Furthermore, we identify a critical "Generalization Paradox": while re-partitioning the dataset into a data-rich 80/10/10 split inflates the metric to 0.5276 mIoU, expert qualitative analysis reveals this induces distributional homogenization, severely degrading real-world, out-of-distribution performance. By releasing our recovered dataset index and robust training framework, we demonstrate that material perception is far from solved and urge the community to leverage the rigorous original split to drive genuine progress in physically grounded artificial intelligence.
### Title:
          Exploring deep learning for Event-Based Saliency Prediction with a Transformer-based model
 - **Authors:** Romaric Mazna, Jean Martinet, Sai Deepesh Pokala
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Saliency prediction has been extensively studied in RGB images and videos as a computational model of human visual attention. In contrast, predicting saliency from event-based data remains largely unexplored, despite the biological inspiration and favorable sensing properties of event cameras. Two obstacles have held this direction back: the absence of large-scale event saliency datasets, and the lack of a strong baseline. In this paper, we introduce SEST (Swin Event-based Saliency Transformer), a transformer-based model for saliency prediction from event data, bridging the data scarcity barrier through event-native pretraining and synthetic supervision. SEST leverages a self-supervised pretrained event-based Swin Transformer backbone combined with a lightweight CNN decoder to produce dynamic saliency maps. To address the scarcity of annotated event-based saliency data, we introduce two new benchmark datasets, N-DHF1K and N-UCF Sports, generated from large-scale RGB saliency benchmarks. Experimental results show that SEST clearly outperforms existing event-based saliency methods and narrows the performance gap with state-of-the-art RGB models. Zero-shot evaluation on a real event camera dataset further demonstrates that our model trained on synthetic data remains transferable on real event streams. To the best of our knowledge, this work is the first to apply deep learning to event-based saliency prediction, opening a new research direction at the intersection of event-based vision and neuromorphic visual attention.
### Title:
          Point Tracking Improves World Action Models
 - **Authors:** Jiarui Guan, Wenshuai Zhao, Yue Pei, Ziliang Chen, Arno Solin, Juho Kannala
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robot policy learning benefits from world-action models that capture environment dynamics, but pixel-level prediction entangles dynamics with nuisance factors such as lighting and texture, making learned representations vulnerable to task-irrelevant visual variation. We propose JOPAT, a JOint Pixel-And-Track World-Action Model that predicts latent visual observations, 2D point tracks with visibility, and actions in a single denoising diffusion transformer. The key insight is that tracks provide an explicit representation of motion that captures long-horizon dynamics and remains robust under occlusion or partial out-of-frame motion, offering greater utility than modeling pixel appearance alone. On LIBERO and real-world LeRobot tasks, JOPAT improves over pixel-based baselines, with the largest gains on long-horizon tasks involving occlusion, object interaction, and off-screen motion.
### Title:
          Vision Transformers Need Better Token Interaction
 - **Authors:** Linxiang Su
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformers (ViTs) can learn strong image-level representations while their patch representations become less effective for dense prediction during prolonged training. We revisit this dense degradation phenomenon and argue that it is not fully explained by high-norm artifacts alone. Instead, we characterize \emph{semantic diffusion}: an optimization shortcut in which global semantic information spreads through patch tokens beyond what is locally justified. Our analysis shows that dense representation quality is not captured by locality alone: shallow features can remain better aligned with foreground regions yet underperform deeper features, and \texttt{[CLS]} features remain complementary for dense prediction. These observations suggest that the goal should not be to remove global context, but to make token interactions more selective. We therefore study sparse attention as a minimal intervention, replacing softmax attention with entmax-1.5 while preserving global token connectivity. On DINOv1 ViT-S/16 trained for 200 epochs on ImageNet-1K, this change preserves ImageNet linear probing accuracy and substantially improves semantic segmentation performance: VOC mIoU increases from 42.80 to 48.78, ADE20K from 19.85 to 21.97, and Cityscapes from 36.79 to 37.87. These results suggest that selective token mixing is a simple and effective bias for improving dense ViT representations.
### Title:
          Training-Free Looped Transformers
 - **Authors:** Lizhang Chen, Jonathan Li, Chen Liang, Ni Lao, Qiang Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Numerical Analysis (math.NA); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce training-free looped transformers, in which a lightweight inference-time wrapper loops a contiguous mid-stack block of layers of a frozen checkpoint without additional fine-tuning, continued training, or architectural changes. Unlike prior looped transformer methods that train with the looped structure end-to-end, we retrofit recurrence onto pretrained models at test time. We show that naive block reapplication usually degrades performance, highlighting the importance of the loop application strategy. Motivated by viewing a pre-norm transformer block as a forward Euler step on an ODE, we instead treat looping as a refinement of the same approximation, replacing one large update with smaller damped sub-steps. Across seven dense, sparse MoE, and MLA+MoE model families, our method improves Qwen3-4B-Instruct by +2.64 pp on MMLU-Pro, Qwen3-30B-A3B-Instruct by +1.14 pp on CommonsenseQA, and Moonlight-16B-A3B-Instruct by +1.20 pp on OpenBookQA.
### Title:
          HorizonStream: Long-Horizon Attention for Streaming 3D Reconstruction
 - **Authors:** Chong Cheng, Peilin Tao, Nanjie Yao, Guanzhi Ding, Xianda Chen, Yuansen Du, Xiaoyang Guo, Wei Yin, Weiqiang Ren, Qian Zhang, Zhengqing Chen, Hao Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Online 3D reconstruction requires estimating camera pose and scene geometry under strict causal and bounded-memory constraints. Existing methods often suffer from drift, jitter, or collapse on long sequences. We trace these failures to a fundamental mismatch. Streaming geometry is inherently temporally heterogeneous, with evidence ranging from short-lived correspondences to persistent global scale. However, current architectures impose uniform and pathological influence patterns. For example, sliding windows enforce hard cutoffs, while ungated recurrence and causal attention cause cache saturation and spike-like attention sinks. To resolve this, we formalize geometric propagation as an \emph{evidence influence kernel} and propose HorizonStream, a long-horizon Transformer that explicitly factorizes this kernel. For the long-range temporal factor, Geometric Linear Attention learns channel-wise decay rates to enable bounded, multi-timescale propagation of geometric evidence. For the short-range spatial factor, Geometric Local Attention with Spatiotemporal RoPE performs reliable 3D matching while suppressing attention sinks. Finally, Metric Readout Tokens recover stable scale and rigid pose directly from the persistent geometric state. Extensive experiments show that HorizonStream, trained on only 48-frame clips, generalizes stably to sequences exceeding 10,000\ frames with constant memory and linear time, achieving state-of-the-art streaming 3D reconstruction performance. Project Page: this https URL
### Title:
          Good Token Hunting: A Hitchhiker's Guide to Token Selection for Visual Geometry Transformers
 - **Authors:** Shuhong Zheng, Michael Oechsle, Erik Sandström, Marie-Julie Rakotosaona, Federico Tombari, Igor Gilitschenski
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Graphics (cs.GR); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual geometry transformers have become powerful architectures for multi-view 3D reconstruction, enabling joint prediction of multiple 3D attributes in a feed-forward manner. However, their computational cost grows quadratically with the input sequence length due to the global attention layers inside these models. This limits both their scalability and efficiency. In this work, we address this challenge with a simple yet general strategy: restricting the number of key/value tokens that each query interacts with during global attention. To achieve effective token selection, we introduce a two-stage framework. First, an inter-frame selection step operates at the frame level to identify frames that should be preserved. Second, an intra-frame selection step further discards more redundant tokens within the selected frames. Our analysis highlights the advantage of a diversity-based strategy for inter-frame selection, which ensures broad coverage of the scene. For intra-frame selection, we show that layer-aware sparsification is necessary, with the selection process guided by the entropy of the global attention pattern. Our approach offers a superior speed-accuracy trade-off compared to existing solutions. Extensive experiments show that it accelerates visual geometry transformers by over 85% for scenes with 500 images while maintaining, or even improving, baseline performance, which hints that how our token selection strategy can play a crucial role in future applications of visual geometry transformers. Our project website is available at this https URL.
### Title:
          Complete-muE: Optimal Hyperparameter Transfer and Scaling for MoE Models
 - **Authors:** Hongwu Peng, Ohiremen Dibua, Yuanjun Xiong, Yifan Gong, Jianming Zhang, Yan Kang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose Complete-muE, a framework which targets hyperparameter transfer across dense FFN and any Mixture-of-Experts (MoE) setups in transformer blocks. Existing tools such as $\mu$P (requires fixed architectue) or SDE (requires fixed per-step token count) cannot directly solve the hyperparameter transfer problem in MoE setups because Dense to MoE transfer or MoE total experts scaling changes both architecture and tokens per expert. Complete-muE solves this challenge with a two-bridge system: Bridge~I maps between dense FFN and Dense MoE by active-width $\mu$P with a normalized router scale. Bridge~II maps between Dense MoE and sparse MoE by activated-expert scaling, where the first-order SDE LR/WD correction cancels while a bounded residual $\sigma_0$ shift remains. The resulting transfer rule, which we term as Complete muE, covers changes in activated experts, total capacity, granularity, and shared/group-balanced hybrids for MoE models as well as network width/depth, batch size, and duration changes for general Transformer models. Extensive language model and diffusion model pretraining experiments confirm that complete-muE yields relatively stable hyperparameter optima across model architectures and parameter counts -- with only minor drift consistent with the non-strict SDE behavior of Bridge~II. In practice this drift is small enough that hyperparameters tuned on a single dense reference transfer near-optimally to all MoE configurations -- \emph{tune dense once, transfer to all} is the practical recipe at the core of Complete-muE. This enables MoE models to achieve accelerated convergence speedup over dense models when scaling model capacity without costly hyperparameter search.
## Keyword: autonomous driving
### Title:
          Scene Reconstruction as Mapping Priors for 3D Detection
 - **Authors:** Yang Fu, Yuliang Zou, Hao Xiang, Xin Huang, Yijing Bai, Chen Song, Weijing Shi, Govind Thattai, Dragomir Anguelov, Mingxing Tan, Yingwei Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In autonomous driving, mapping is critical for motion planning but remains an under-utilized resource for perception tasks such as 3D object detection. Maps can provide robust structural priors of the static environment, helping resolve ambiguities and correct for sensor data sparsity or noise, especially for distant objects or under adverse weather conditions. However, conventional High-Definition (HD) maps are resource-intensive to obtain and maintain, which presents a challenge for efficient, large-scale deployment. In this paper, we propose a scalable solution to systematically leverage mapping to improve 3D detection by overcoming two primary challenges. First, we introduce a pipeline to automatically build dense mapping priors from aggregated sensor data, eliminating the need for human labeling. Second, we design a novel Mapping Priors Augmented 3D Detection (MPA3D) framework to effectively integrate mapping priors with different sensor modalities. Extensive experiments on the Waymo Open Dataset demonstrate that our approach achieves new state-of-the-art results, proving the effectiveness of scalable reconstructed scene priors for enhancing 3D detection.
### Title:
          Fast-dDrive: Efficient Block-Diffusion VLM for Autonomous Driving
 - **Authors:** Kewei Zhang, Jin Wang, Sensen Gao, Chengyue Wu, Yulong Cao, Songyang Han, Boris Ivanovic, Langechuan Liu, Marco Pavone, Song Han, Daquan Zhou, Enze Xie
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end autonomous driving via Vision-Language-Action (VLA) models demands a precarious balance between high-fidelity trajectory planning and efficient inference. Existing paradigms typically fall short: autoregressive (AR) VLAs are memory-bandwidth-bound on edge hardware and prone to exposure-bias drift, while full-sequence diffusion models preclude KV-cache reuse and suffer from "logical leakage" that violates the fundamental perceive-then-plan causality. We present Fast-dDrive, a block-diffusion VLA that performs bidirectional refinement within semantic units while enforcing strict causal ordering across them. Leveraging the observation that driving VLAs often emit structured JSON-like outputs, Fast-dDrive freezes structural tokens into a section scaffold and employs a section-aware training recipe that prioritizes safety-critical planning. We further introduce Scaffold Speculative Decoding to achieve AR-equivalent quality at significantly higher throughput. Finally, we propose a low-overhead test-time scaling scheme: by forking $N$ stochastic trajectory rollouts from a single shared-prefix KV cache and averaging them, we effectively suppress prediction variance at a fractional computational cost. Empirical results demonstrate that Fast-dDrive redefines the speed-accuracy frontier for driving agents. On the WOD-E2E test set, Fast-dDrive achieves SOTA ADE@3s and ADE@5s, alongside the highest RFS among diffusion-based VLAs; on nuScenes, it reduces average L2 error to $0.32$m (a $22\%$ improvement). When integrated with SGLang, our framework delivers $12\times$ throughput speedup over the AR baseline, narrowing the gap between high-capacity VLAs and the efficiency demands of real-time on-vehicle deployment.
### Title:
          DRIVESPATIAL: A Benchmark for Spatiotemporal Intelligence in VLMs for Autonomous Driving
 - **Authors:** Hao Vo, Khoa Vo, Phu Loc Nguyen, Sieu Tran, Duc Minh Nguyen, Ngo Xuan Cuong, Gladys Gawugah, Sreevenkata Anjani Tishita Godavarthi, Chase Rainwater, Nghi D. Q. Bui, Anh Nguyen, Duy Minh Ho Nguyen, Ngan Le
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spatiotemporal intelligence in autonomous driving (AD) requires an agent to integrate multi-view observations into a coherent scene representation, maintain object continuity across viewpoints and time, and reason about spatial relations, interactions, and future dynamics. However, existing AD vision-language benchmarks largely focus on single-view, static, ego-centric, or single-source question answering, leaving it unclear whether current Vision-Language Models (VLMs) can truly construct and reason over dynamic driving scenes. We introduce DriveSpatial, a benchmark of 15.6K human-verified QA pairs across 20 tasks from five large-scale AD datasets. DriveSpatial evaluates four abilities: Cognitive Scene Construction, Multi-view Relational Understanding, Temporal Reasoning, and Generalization. Unlike prior benchmarks, DriveSpatial is generated from a dynamic multi-relational scene graph that encodes object states, spatial relations, interactions, camera visibility, and temporal correspondences, enabling QA pairs that enforce genuine cross-view and spatiotemporal reasoning. Evaluating 15 representative VLMs reveals a substantial human-model gap: the strongest model trails humans by 28.4 points, with Cognitive Scene Construction emerging as the key bottleneck. Further diagnostics show that language-only prompting is insufficient, while explicit BEV grounding consistently improves performance. These results suggest that current VLMs lack the scene-construction ability needed for reliable spatiotemporal driving intelligence. DriveSpatial and its construction pipeline will be released to support future research.
### Title:
          Lipschitz Optimization for Formal Verification of Homographies
 - **Authors:** Jean-Guillaume Durand, Panagiotis Kouvaros, Maxime Gariel, Alessio Lomuscio
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The adoption of vision neural networks in regulated industries requires formal robustness guarantees, especially in safety-critical domains such as healthcare, autonomous vehicles, and aerospace. However, current approaches are confined to incomplete statistical verification or robustness to $\ell_p$-norm and affine transforms, which cover only a narrow subset of perturbations to the image formation process. In particular, robustness to camera motion remains an open problem despite being key to deploy many vision applications. We present a formal verification approach that targets robustness against 3D motion perturbations of the capturing camera. We first establish a closed-form mapping from camera pose to pixel values. By analyzing the continuity properties of the resulting homographies, we show that recent work on Lipschitz optimization and piecewise continuity can be extended to derive tight linear bounds on perturbed pixel values. Our approach applies to scenes with predominantly planar structure, such as ground planes in augmented reality, road markings and traffic signs in autonomous driving, or planar workspaces in robotic manipulation. This enables the first formal verification of projective geometry transforms, without complex simulation, surrogate networks, or explicit image-formation models. We validate our implementation and show up to 89% speedup and 7% tighter bounds over prior work. We then evaluate our method on the VNN-COMP benchmark and reveal systematic weaknesses to projective perturbations. Finally, we demonstrate a real-world case study on a safety-critical runway classifier, highlighting practical vulnerabilities to camera motion, and addressing a key challenge in the certification of learned models. Data and code are publicly available at this https URL .
### Title:
          ChainFlow-VLA: Causal Flow Planning with Vision-Language Models
 - **Authors:** Xiyang Wang, Xinlin Wang, Tingguang Zhou, Gong Chen, Xingtai Gui, Zhi Xu, Xiaolei Wu, Feiyang Tan, Hangning Zhou, Mu Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current end-to-end autonomous driving systems are fundamentally limited by a mismatch between temporal causal reasoning and global trajectory consistency. Autoregressive (AR) models capture interaction-aware temporal dependencies via causal factorization, but their step-wise decoding leads to error accumulation and suboptimal global structure. In contrast, diffusion models optimize trajectories globally but lack explicit causal constraints, making them unreliable in interactive and safety-critical scenarios. This dichotomy reveals a deeper issue: existing methods treat causal modeling and global optimization as separate paradigms, without a principled way to unify them within a single trajectory distribution. To address this, we propose ChainFlow-VLA, which unifies causal generation and global refinement within a unified probabilistic framework. We formulate planning as a mixture over AR-induced modes and learn Vision-Language Model (VLM)-conditioned residual distributions over these modes. An autoregressive generator (Chain) produces a discrete set of causal trajectory modes, followed by a diffusion-based refiner (Flow) that leverages VLM hidden states as semantic priors to perform mode-conditioned correction in residual space while preserving causal structure. This straightforward conditioning seamlessly injects high-level scene understanding into fine-grained trajectory adjustments. Experiments demonstrate that ChainFlow-VLA achieves robust planning in ambiguous and long-tail scenarios, achieving a state-of-the-art score of 94.85 on the NAVSIM v1 leaderboard, matching human-level performance (94.8). Code will be available at this https URL.
### Title:
          GFSR: Geometric Fidelity and Spatial Refinement for Reliable Lane Detection
 - **Authors:** Tiancheng Wang, Zhaolu Ding, Richeng Xu, Tianhui Zheng, Hui Liu, Hanyu Xuan, Zhiliang Wu, Guanghui Yue
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Lane detection stands as a crucial perception task in autonomous driving and advanced driver assistance systems. However, existing methods still degrade in complex real scenarios due to two major limitations. First, classification confidence only characterizes the categorical existence of lane candidates and has no strong correlation with geometric quality. If threshold filtering and NMS are conducted merely based on this confidence, the model tends to retain lane priors with high confidence while eliminating those with lower confidence but superior geometric representation. Secondly, existing regression modules weaken correlations among sampling points, hindering fine-grained optimization of distant, high-curvature and complex-topology lanes and causing underfitting. To address these issues, we propose Geometric Fidelity and Spatial Refinement (GFSR), a framework consisting of LaneIoU-guided Confidence Calibration (LCC) and Adaptive Gated Location Refinement (AGLR). Specifically, LCC adopts LaneIoU as soft supervision to explicitly estimate geometric fidelity of lane priors, which is further fused with classification confidence to construct the collaborative reliability index (CRI). This index guides threshold filtering and NMS, effectively retaining lane priors with high classification confidence and favorable geometric quality. Meanwhile, cooperating with regression heads in each refinement stage, AGLR predicts sampling point lateral offsets and adopts a gating mechanism to adaptively regulate correction magnitude, strengthen inter-point correlations and boost model adaptability as well as robustness toward complex lane scenarios. Extensive experiments on CULane and CurveLanes demonstrate that our GFSR achieves state-of-the-art performance on CULane, with F1@50 and F1@75 scores of 81.46% and 65.01%, and reaches 87.35% F1@50 on CurveLanes.
### Title:
          RS2AD-LiDAR: End-to-End Autonomous Driving LiDAR Data Generation from Roadside Sensor Observations
 - **Authors:** Runyi Huang, Ni Ding, Ruidan Xing, Yuheng Shi, Lei He, Keqiang Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end autonomous driving solutions, which directly process multimodal sensory data and output fine-grained control commands, have gradually become a mainstream direction with the development of autonomous driving technology. However, current methods in this category rely on single-vehicle data collection for model training and optimization, which suffers from high acquisition and annotation costs, scarcity of valuable scenarios, and data silos. To address these challenges, we propose RS2AD-LiDAR, a novel framework for reconstructing and generating vehicle-mounted LiDAR data from roadside sensor observations. Since no public dataset currently provides highly overlapping perception coverage between roadside and vehicle-mounted LiDAR sensors, which is essential for studying roadside-to-vehicle data generation, we constructed a dedicated dataset named R2V-LiDAR which is used solely for evaluation in this work. Specifically, our method transforms roadside LiDAR point clouds into the vehicle-mounted LiDAR coordinate system, and synthesizes high-fidelity vehicle-mounted data via virtual LiDAR modeling and point cloud resampling techniques. To the best of our knowledge, this is the first approach to reconstruct vehicle-mounted LiDAR data from roadside sensor inputs. Extensive experimental comparisons demonstrate the semantic similarity between the generated data and real data. Furthermore, object detection experiments show that incorporating the generated data into real data for model training improves both Bird's Eye View (BEV) and 3D detection accuracy, thereby validating the effectiveness of the proposed method.
### Title:
          To Overlay or to Customize? Revisiting Architectural Choices in Heterogeneous Systems
 - **Authors:** Xingzhen Chen, Shixin Ji, Zheng Dong, Peipei Zhou
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this work, we present a systematic study of this trade-off from a deployment-centric perspective, focusing on an autonomous driving scenario. Instead of treating overlay and customized acceleration as isolated design points, we analyze when each approach is preferable under practical conditions, including workload variation, architectural design, reconfiguration latency, and switching frequency. Our analysis shows that overlay-based architecture is more suitable for highly frequent model switching under the state-of-the-art architecture. However, as bitstream reload overhead continues to reduce, customized architectures may become increasingly attractive, especially for workloads with efficiency requirements. Conversely, if overlay architectures become more capable and flexible, they may further expand their advantage over customized architectures. These observations provide design insights for future architectural design, and the optimal deployment strategy will be flipped according to the technique development.
