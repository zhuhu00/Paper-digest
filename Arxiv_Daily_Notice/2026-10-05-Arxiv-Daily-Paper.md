# Showing new listings for Monday, 5 October 2026
## Keyword: SLAM
There is no result 
## Keyword: odometry
### Title:
          Real-time Event-camera Stereo Visual Odometry via Keytime Gaussian Process Regression
 - **Authors:** Nikan Nobari, Jonathan D. Gammell
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Event cameras have microsecond-level temporal resolution and high dynamic range which make them more resilient to motion blur and poor illumination than standard frame-based cameras. Event-camera visual odometry (VO) pipelines maximize these benefits when they process the asynchronous event stream at the native temporal resolution. Continuous-time Gaussian process (GP) regression and a white-noise-on-acceleration (WNOA) prior can handle asynchronous measurements but result in a prohibitively large estimation state when applied naively. This paper presents a continuous-time event-camera stereo VO pipeline that maintains the native measurement times of asynchronous events while also running in real time. It reduces the estimation states to keytimes while maintaining full temporal resolution by interpolating measurements to their exact timestamps with a physically founded WNOA prior. This decouples the state size from the dense number of measurements without discarding their asynchronous nature. The real-time continuous-time VO pipeline is evaluated on the MVSEC and DSEC datasets. It provides estimates in real time that are more accurate than ES-PTAM, a state-of-the-art discrete estimator, in all but one of the tested sequences. The pipeline respectively provides estimates at 22 Hz and 6 Hz on MVSEC and DSEC and RMS relative errors of 0.46 cm and 0.038 degrees across all valid sequences, which were 11 and 15 times better than ES-PTAM, respectively.
### Title:
          Who Went Where When on the Lunar Surface: Forensic Trajectory Analysis to Identify Byzantine Rovers
 - **Authors:** Lachlan Holden, Feras Dayoub, Melissa de Zwart, David Harvey, Tat-Jun Chin
 - **Subjects:** Subjects:
Robotics (cs.RO); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Future planetary surface missions are likely to involve multiple independently operated rovers sharing the same deployment region, raising the need to verify compliance with operational constraints such as Lunar Safety Zones. Because continuous in-situ observability is rarely available, such verification requires post-hoc reconstruction of rover trajectories from sparse telemetry, including odometry, pose priors, and relative inter-rover detections. We introduce the problem of forensic trajectory analysis for non-cooperative planetary rovers in the presence of Byzantine agents: rovers that provide miscalibrated or deliberately falsified measurements to support an incorrect trajectory. We show that standard outlier-robust pose graph optimisation methods are vulnerable in this setting, because Byzantine rovers can generate measurements that are internally consistent and numerous enough to make truthful incriminating measurements appear as outliers. To address this, we propose an attribution-aware trajectory estimation method that reasons over rover credibility rather than individual measurement validity. The method evaluates candidate credible rover subsets by comparing the statistical consistency of their internal and boundary relative detections against provided priors, and then estimates trajectories using only measurements attributed to credible agents. Across synthetic simulations and real planetary-analogue trajectory data, the proposed method identifies Byzantine rovers and produces significantly more accurate trajectory estimates than existing robust pose graph optimisation baselines.
### Title:
          HexVIO: Towards All-Day Stereo-Inertial Tracking Through Commodity DSPs
 - **Authors:** Patrick Wolf, Mateo de Mayo, Daniel Cremers
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The ability of a device to localize itself within its surroundings is a fundamental prerequisite for spatial computing. Visual-inertial odometry (VIO) has proven to be a cost-effective and accurate solution for this task. Robots, wearables, XR devices, and drones can benefit significantly from efficient implementations of VIO since they allow for cooler, lighter, and cheaper devices with longer battery life and a better user experience. In this work, we propose to enhance the efficiency of a VIO system by leveraging the Hexagon DSP, a commodity co-processor present in many modern smartphones and XR devices. Our approach offloads the visual frontend of a stereo-inertial odometry system to the DSP while keeping the backend on the main CPU. By optimizing the implementation for the DSP architecture, we achieve significant reductions in power consumption and latency compared to CPU-only execution. Our system, HexVIO, demonstrates a 67% reduction in power consumption or an 86% increase in throughput on a commodity smartphone, with the ability to sustain long-term real-time 30 fps tracking for 0.83 W, corresponding to ~18 hours of tracking on the testing device. These results highlight the potential of commodity DSPs for enabling all-day visual-inertial tracking in robotics and mobile devices.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Kinematics-Induced Multimodal 3D Human Pose Estimation with Subject-Level Privacy
 - **Authors:** Kaushik Bhargav Sivangi, Fani Deligianni
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal 3D Human Pose Estimation (3D HPE) combines complementary information from RGB, LiDAR, and mmWave radar, but models trained on correlated observations from the same individuals, raise privacy risks overlooked by record level analysis. We present a unified framework for multimodal 3D HPE that couples kinematics-induced sensor fusion with subject level privacy auditing and private training. First, our multimodal model aligns modality specific joint representation, injects skeletal structure and adaptively aggregates complementary sensor evidence for accurate pose prediction. Second, we formulate a black-box subject membership inference attack for 3D HPE, complemented by an empirical pointwise maximal leakage analysis, which characterizes how individual attack score outcomes change inference about the membership outcome. Third, we instantiate user-level differential privacy via Action Temporal Stratification, a population weighted within-subject sampling strategy that enforces action and temporal coverage. We evaluate our framework on the MM-Fi dataset across three diverse experimental protocols. Source-code will be released upon acceptance.
### Title:
          DR-IPC: Disturbance-Resilient Integrated Planning and Control for LiDAR-Based Quadrotor Navigation
 - **Authors:** Peng Liu, Jingyan Wang, Qipeng Ye, Wen Li, Jinya Su, Zuo Wang, Shihua Li, Yunda Yan
 - **Subjects:** Subjects:
Robotics (cs.RO); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR-based quadrotor navigation in cluttered environments remains challenging under external disturbances, particularly when obstacle-aware motion generation and disturbance-rejection control are handled in separate layers. This article presents disturbance-resilient integrated planning and control (DR-IPC), which combines lightweight path guidance with nonlinear model predictive control (NMPC) to directly generate angular velocity and thrust. An interconnected extended Kalman filter and nonlinear disturbance observer jointly provide filtered state estimates and reconstructed disturbances for NMPC prediction. The resulting formulation unifies nonlinear quadrotor dynamics, actuator constraints, local motion generation, and penalised safe-flight-corridor residuals without requiring a separate trajectory-optimization stage. Gazebo and MARSIM simulations, together with indoor and outdoor experiments, validate DR-IPC under wind, suspended payloads, narrow passages, ball impacts and reactive avoidance of a dynamic obstacle. In multi-goal navigation with disturbances, DR-IPC increases the number of completed missions from 1/10 to 9/10 in Gazebo and reduces the altitude RMSE from 0.34 to 0.01 m in experiments. The complete system operates onboard at 100 Hz. Supplementary videos are available on the project page this https URL, and the source code will be released.
### Title:
          A Secure dToF LiDAR SoC with Dual-Domain Fingerprinting and Event-Driven AFE Circuit Achieving Sensor-Level Attack Resilience
 - **Authors:** Risa Nonaka, Ryoya Matsuno, Shota Nagai, Satomi Miyagi, Yuki Hayakawa, Ryo Suzuki, Kazuma Ikeda, Ozora Sako, Rokuto Nagata, Ryo Yoshida, Shimpei Ando, Wenlun Zhang, Kentaro Yoshioka
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent studies have shown that most commercial direct time-of-flight (dToF) LiDARs can be spoofed by injecting high-frequency laser pulses into the receiver, which can erase pedestrians from the point cloud. This paper presents the first dToF LiDAR system-on-chip (SoC) with integrated sensor-level hardware security against spoofing attacks. We propose Dual-Domain Fingerprinting (DDF), which emits laser pulse pairs whose time interval and amplitude ratio are both randomized and authenticates received echoes in this two-dimensional space, so that spoofed signals are rejected before they corrupt the ranging result. An Event-Driven AFE (ED-AFE) activates the ADC only around pulse peaks: it digitizes three samples around each peak with a triggered ADC at 1-GHz sampling and applies parabolic interpolation, achieving 1-cm distance resolution with a 99% reduction in ADC power. A time-modulated laser driver controls the laser amplitude from 10% to 100% by modulating the charge time of a laser capacitor, providing the microsecond-order amplitude modulation required by DDF. A LiDAR system with a 16-channel 65-nm CMOS prototype SoC demonstrates up to 120-m ranging and an AFE power of 3.1 mW per channel, 60% lower than prior art. In a proof-of-concept experiment in which the dual-domain authentication is applied to measured sensor data, 73% of the point cloud is protected under spoofing attack, compared with 0% without DDF.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          PocketSplat: Mobile Gaussian Reconstruction via World-Space Latent Allocatio
 - **Authors:** Wenzhi Guo, Xianda Chen, Dongxuan Chen, Guangchi Fang, Bing Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mobile Gaussian reconstruction must satisfy two requirements: the reconstruction model must execute within a device resource envelope, and the resulting Gaussian asset must expose a representation size suited to downstream mobile use. Existing feed-forward Gaussian reconstructors commonly decode dense, image-aligned candidates whose final cardinality is implicitly determined by the input resolution and number of views. We present PocketSplat, a feed-forward framework for budgeted mobile Gaussian asset construction. Given a prescribed output budget, PocketSplat organizes dense geometry-aware latent candidates in predicted world space, allocates exact integer capacity across local latent cells, and decodes complete Gaussian attributes only for retained candidates. Cell-conditioned latent fusion aggregates repeated multi-view evidence before decoding, while spatial responsibility decoding adapts Gaussian support after local sparsification. Experiments on DL3DV and out-of-distribution benchmarks establish a strong quality--budget trade-off against feed-forward Gaussian reconstruction baselines. On Mip-NeRF 360, PocketSplat executes directly on a target iPhone and constructs compact, higher-quality Gaussian assets substantially faster than a deployable streamed MVSplat variant; native MVSplat and DepthSplat exceed the device memory budget.
## Keyword: mapping
### Title:
          A Bifurcation-Based Domain Decomposition Method with Neural Operators for Blood Flow Simulation
 - **Authors:** Yuzhou Zhao, Han Zhang, J. Matias Di Martino, Jean-Michel Morel, Guillermo Sapiro
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE); Computational Physics (physics.comp-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fast and accurate simulation of hemodynamic behavior within vascular networks is essential for numerous clinical applications. However, obtaining high-quality and computationally efficient flow measurements across complex vascular networks remains challenging. To address this, we first decompose the vascular network into a set of bifurcation units and then develop an operator network capable of mapping unit-specific parameters to the local solution fields of each bifurcation unit. By lumping the Windkessel-model outlet parameters and incorporating inlet boundary conditions from the solution of parent units, the flow and pressure fields can be rapidly approximated. Subsequently, operator-network-driven Schwarz waveform relaxation is applied across bifurcation units to correct discontinuities and improve numerical accuracy. On 7-segment and 55-segment arterial tree models, the proposed method achieves $13\times$ to $17\times$ wall-clock speedups over conventional 1D numerical simulation, with relative $L^2$ errors of 1% in both pressure and velocity. The resulting pulse wave velocity biomarkers agree with the conventional reference to within 1--2%, and the same trained operator generalizes to different tree-like 1D vascular network topologies.
### Title:
          SoTa: Soft Tactile Skins for Dexterous Manipulation
 - **Authors:** Jingyun Yang, Baiyu Shi, Timothy Yu, Haitian Liu, Alberta Longhini, Weichen Wang, Rika Antonova, Zhenan Bao, Jeannette Bohg
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A growing body of work suggests that tactile sensing gives robot policies contact information that complements vision in dexterous manipulation. However, visuo-tactile robot data remains scarce: dexterous demonstrations require teleoperating robots, which limits dataset scale. Human demonstrations are far cheaper to collect and offer a path to scale this data, but only if human and robot hands carry tactile sensors with corresponding signals. This requires sensors that conform to different hand geometries, cover the full hand, and share a common layout across embodiments. We present SoTa, a low-cost capacitive tactile skin that provides full-hand coverage on humans and robots while preserving a shared layout of 202 taxels across corresponding finger and palm regions. Our multilayer design with fabric electrodes enables in-house fabrication of thin, soft skins with customizable geometry for under $10 in materials per skin. The sensor retains over 97% of its initial response span after 10,000 loading-unloading cycles with traces retaining continuity through 1,280 tight-fist folding cycles. The shared taxel layout supports human-robot co-training with a common tactile encoder and no learned cross-sensor mapping. Across three contact-rich manipulation tasks, tactile observations improve in-distribution success over vision-only policies. With a fixed robot demonstration budget, adding human demonstrations more than doubles mean success across eight evaluation conditions, from 22.8% to 45.9%, improving success in all five out-of-distribution conditions. We plan to open-source the resources needed to fabricate and operate these skins.
### Title:
          A Simulation-Grounded Agentic VLM Framework for Wildfire Monitoring and Reporting
 - **Authors:** Duowen Chen, Yuchen Sun, Zhiqi Li, Yuxuan Liao, Sinan Wang, Bart van Bloemen Waanders, Bo Zhu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Effective wildfire monitoring requires relating visual evidence to physical fire dynamics, yet real videos with synchronized physical annotations are scarce and high-fidelity 3D simulation is costly. We present a simulation-grounded vision-language model (VLM) framework that automatically converts 2D wildfire simulations into labeled video episodes. A fixed Blender mapping produces low-detail 3D proxies aligned with simulator terrain, fuel layout, fire activity, and wind cues; controllable video generation supplies richer appearance. The proxies are intermediate representations rather than finely rendered final scenes. Generated videos and simulator labels form reusable multimodal memory for a training-free multi-agent VLM system that retrieves reference episodes, reconciles visual and memory-based predictions, and produces structured wildfire reports. On held-out generated episodes, video memory achieves 51.5% exact four-tag accuracy, compared with 22.6% for direct VLM querying and 16-17% for text-only memory; the complete system achieves 77.3% accuracy on six simulator-derived report fields. Component ablations, cross-generator tests, and three real-UAV evaluations assess retrieval, reporting, generator changes, and observable monitoring tasks. The framework connects automatic simulation-to-proxy conversion with memory-based VLM reasoning under scarce real-world physical annotations.
### Title:
          DISSOLVR: An Interpretable and Fast Framework for Aqueous and Organic Solubility Prediction
 - **Authors:** Vansh Ramani, Har Ashish Arora, Dhairya Kuchhal, Sayan Ranu, Tarak Karmakar
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Chemical Physics (physics.chem-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-fidelity solubility prediction is fundamental to pharmaceutical development and environmental partitioning, where accurate modeling must couple molecular structure with thermodynamic behavior across diverse chemical environments. However, recent advancements have been dominated by deep learning architectures that often sacrifice physical interpretability for predictive power. We challenge this trend by showing that state-of-the-art performance does not require such non-transparent architectures. To address this, we introduce DISSOLVR, a transparent framework for molecular solubility prediction. In addition, we perform a comprehensive literature review and a benchmarking study against various methods. We show that DISSOLVR approaches the aleatoric limit of experimental uncertainty and achieves OOD generalization through structural invariance, derived by mapping molecules to physically-grounded descriptors. Then, we present an LLM-assisted post-hoc explanation pipeline that bridges the gap between symbolic model artifacts and chemically grounded narratives. Finally, a comparative benchmark of a survey involving 22 expert chemists reveals that expert evaluators provide deep insights.
### Title:
          Annotation-Driven Migration of CUDA Programs to Tenstorrent Blackhole
 - **Authors:** Ayumi Ohno, Shinya Takamaeda-Yamazaki
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tenstorrent Blackhole combines distributed local memories, explicit inter-core communication, and Tensix cores decoupling data movement from computation. CUDA offers a substantial HPC software base but leaves physical data placement and scheduling largely implicit. Migrating CUDA HPC kernels to Blackhole requires spatial mapping across cores and per-core coordination of compute and data-movement kernels. We present an MLIR-based compiler deriving data placement, inter-core communication, and tile computation from a statically shaped affine CUDA subset. Declarative annotations express choices not fixed by the source, including compute/DM operation placement and streaming granularity. We evaluate it on Gaussian elimination, five-point stencil, and symmetric rank-k update. Relative to our compiler's default realizations, the best measured configurations achieve a 4.2x speedup for BF16 Gaussian and 2.1-2.2x for FP32 Gaussian and Jacobi. A choice's performance impact can reverse with surrounding policies, precision, and loop schedule, motivating comparison of alternative per-core realizations rather than independent policy selection.
### Title:
          Self-Supervised Scaling of Terminal Environments for Scientific Domains
 - **Authors:** Zhongzhi Li, Yucheng Shi, Zongxia Li, Junyao Yang, Ruhan Wang, Yu Wang, Jingyuan Huang, Jichao Yu, Ninghao Liu, Haitao Mi, Leowei Liang
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Terminal agents are increasingly deployed beyond software engineering in science and other specialized domains. Constructing training environments requires executable reference behavior and a domain-specific verifier that distinguishes semantic correctness from superficially plausible artifacts. Authoring these components for each task requires repeated engineering and limits reuse. We introduce software-in-the-loop reconstruction, a self-supervised framework that obtains reference outputs and verification targets from existing software workflows, executable programs mapping structured inputs to outputs. For each workflow, we execute multiple input configurations and partition cases into public observations and hidden evaluations. Given the instruction, input schema, and public input--output observations, an agent constructs an editable program without access to the source workflow. The candidate is evaluated on hidden configurations against workflow outputs. A hierarchical verifier combines domain-specific semantic comparison, structural validity, and anti-shortcut checks, while public feedback supports iterative revision. The construction admits additional workflows and configurations without authoring a reference solution for each task. We instantiate SWR with 500 workflows and 46 software families across six domains. Across three attempts per task, Qwen3.8-Max solves 838 tasks and produces 1,422 verified trajectories, which we oversample to 3,000 reconstruction-only training examples. Supervised fine-tuning of Qwen3.8-27B improves mean Terminal-Bench 2 performance from 47.94% to 53.56% across three seeds and achieves the highest mean among four matched-token corpus controls on all four reported evaluations. These results indicate that existing scientific software can provide scalable, behaviorally verified supervision for terminal agents.
### Title:
          A Two-Stage Cascade for Near-Real-Time Forest Anomaly Detection from Sentinel-1 SAR Time Series
 - **Authors:** Pann Thinzar Seint, Subas Chhatkuli, Bryan Atwood
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tropical forest monitoring is essential for global climate stability and biodiversity preservation. To address the urgent need for rapid, reliable detection of forest loss which is essential for timely intervention against illegal logging, supply chain transparency, land-use governance and carbon market standards, we introduce a two-stage statistics-encoder cascade for near-real-time anomaly detection using Sentinel-1 time series. Our system is designed to overcome two fundamental challenges in remote sensing: the cloud-cover limitations that restrict optical monitoring and seasonal backscatter variation that causes SAR systems to mistake natural moisture changes for forest loss. The architecture integrates two distinct analytical engines to ensure high-fidelity detection: (1) an adaptive, robust-statistics z-score test on co-registered Sentinel-1 VH backscatter, same-season historical baseline and (2) a learned confirmation gate based on the latent-space structural similarity (SSIM) of a convolutional autoencoder trained on stable-forest patches. A candidate disturbance is confirmed as an alert only when both stages agree, and is assigned a confidence score and a Low/Medium/High risk tier from its repeat-occurrence history. The system produces per-alert auditable confidence scores and area-in-hectares estimates directly compatible with Monitoring, Reporting and Verification (MRV) workflows, sustainable forestry management, operational field checks and environmental risk assessments. Beyond its primary application, the model's flexibility allows for critical environmental applications ranging from selective logging to large-scale agricultural encroachment mapping, flood mapping and so on.
### Title:
          Mission-Centric Requirements Analysis of Model Predictive Control in Spacecraft Rendezvous and Proximity Operations
 - **Authors:** Nils Maier, Torbjørn Cunis, Tam W. Nguyen
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rendezvous and proximity operations (RPO) missions are commonly designed as a sequence of distinct phases each governed by its own sample time, constraint set, and cost structure, with the translation from mission-level requirements to model predictive control (MPC) design parameters typically performed ad hoc. This report takes a first step toward a systematic, traceable mapping between mission requirements and MPC design choices, using the ADRIOS / ClearSpace-1 active debris removal mission as a case study across three sequential operations. Its central hypothesis is that Economic MPC (EMPC), in which the stage cost reflects propellant consumption directly, is structurally better suited to proximity operations than fixed-point regulation or reference tracking, because it can exploit the natural, fuel-free relative-orbital-motion trajectories admitted by the Clohessy-Wiltshire-Hill (CWH) dynamics instead of fighting them. We show that a pure-fuel stage cost is fundamentally degenerate for this class of problem as the closed-loop optimum is not strictly dissipative with respect to any single target state or orbit, and analyse, operation by operation, which terminal ingredient (a terminal region, a terminal cost, a terminal equality, or a stage-cost regularisation) is required to repair this degeneracy, at what fuel and time cost, and under what formal guarantee. Across all three operations the economic controllers cut fuel consumption by roughly 40-99% relative to standard quadratic-tracking MPC, at the cost of longer manoeuvre times, and we synthesise the results into a cross-scenario table of mission requirements, MPC ingredients, and their residual limitations.
### Title:
          Muon Learns Facts Better: Understanding the Role of Spectral Orthogonalization
 - **Authors:** Xuheng Li, Qiwei Di, Yuan Cao, Quanquan Gu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Optimization and Control (math.OC); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Muon optimizer applies spectral orthogonalization to matrix-valued updates and has shown strong performance in large-scale neural network training, yet the mechanisms of this transformation in feature learning remain poorly understood. In this work, we investigate this question through a tractable factual-recall model, where a fact maps each subject-relation pair to an answer, and a linear transformer learns the subject- and relation-dependent information required to recover this mapping. The transformer is optimized with gradient flow (GF), spectral GF, or Sign GF, which are continuous-time limits of gradient descent, Muon, and Adam, respectively. Prior studies (Nichani et al., 2025) have shown that when the number of subjects exceeds the number of relations, GF learns relation-dependent information before subject-dependent information, producing a feature-separation phase during training. We characterize this separation with the learning times when the subject- and relation-dependent components of the prediction reach a target accuracy. With $S$ subjects and $R$ relations, GF has a learning-time ratio of $\widetilde{\Theta}(\sqrt{S/R})$, whereas Spectral GF reduces this ratio to $\widetilde{\Theta}(1)$. In addition, for fixed $S$ and $R$, the subject- and relation-dependent errors decay as $1/(T\log T)$ in training time $T$ under GF, but as $\exp(-\mathrm{poly}(T))$ under spectral GF. Finally, we show that GF and spectral GF are equivariant under orthogonal transformations of the token embeddings, whereas Sign GF is not: Different orthonormal embeddings can potentially produce no feature separation, a large feature-separation phase, or even a reversed learning order. These results provide a mechanistic view of how spectral orthogonalization can fundamentally reshape feature-learning dynamics.
### Title:
          FUSEye: Training-Light Fisheye Detection with Overlapping Views and Zero-Initialized Adapters
 - **Authors:** Wenya Su, Kai Luo, Di Wen, Ruiping Liu, Yufan Chen, Junwei Zheng, Kunyu Peng, Kailun Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fisheye cameras give mobile robots a single-sensor, low-cost view of their surroundings, yet the COCO-pretrained detectors that practitioners routinely reuse fail on them: strong radial distortion warps local image structure, while boundary compression shrinks objects to near-invisible sizes. Full fine-tuning closes much of the gap but requires abundant fisheye labels and compute. We present FUSEye, a training-light framework that turns a frozen-backbone COCO-pretrained extra-large YOLO26 detector (YOLO26-x) into a fisheye detector. FUSEye adds roughly 227k new parameters while updating the inserted modules and the pretrained detection head. It addresses the transfer gap at three causally linked levels. At the input level, overlapping grid view generation and box remapping (GridViews) enlarge compressed boundary regions. At the feature level, zero-initialized residual adapters (Z-Adapters) correct distortion-induced feature misalignment. At the decision level, learned cross-projection agreement fusion (AgreeFusion) promotes low-confidence detections only when they are supported by consistent evidence across multiple views. On the WoodScape surround-view fisheye benchmark, FUSEye raises YOLO26-x from 0.148 to 0.266 mAP50 and retains 84.3% fully fine-tuned accuracy. Moreover, randomly using only 25% of the labeled training images, FUSEye achieves 0.2597 mAP50, retaining 97.6% of its full-label performance. FUSEye also consistently improves YOLOv8-11 detectors, showing that the recipe is architecture-agnostic. Source code will be available at this https URL.
### Title:
          FARM: Fundamental Agentic Reward Model For Multi-task Wireless Network Optimization
 - **Authors:** Feiran You, Changxu Ni, Haozhe Ma, Jun Li, Hongyang Du
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Future wireless networks require learning agents to adapt across heterogeneous channel conditions, traffic patterns, quality-of-service (QoS) requirements, objectives, and operational constraints. Reusing decision knowledge across such tasks is challenging because conventional multi-task and transfer reinforcement learning methods primarily share or transfer policies, coupling transferable knowledge with task-dependent action mappings. This paper proposes FARM (Fundamental Agentic Reward Model for Multi-task Wireless Network Optimization), a reward-space transfer framework that shifts cross-task knowledge reuse from policy space to trajectory-level decision evaluation. FARM introduces an Agentic Reward Model (ARM) that learns a task-conditioned reward prior from heterogeneous source-task trajectories and provides auxiliary guidance for task-specific policy optimization. In Stage I, ARM jointly models task conditions, temporal trajectory dependencies, and objective-dependent reward structures while each source task retains its own controller. In Stage II, the learned reward prior is frozen and reused to guide the adaptation of a target-specific controller for previously unseen tasks, without transferring source-task policies. Experiments on heterogeneous multi-access edge computing (MEC) tasks show that FARM achieves a mean late-stage gain of 29.8% over Single-task SAC on unseen Rate-Latency targets, compared with 16.1% for CRA Transfer, and reaches a 46.2% gain on the moderate-OOD FAR-M case. Further analysis shows that both Mamba and Transformer trajectory encoders support Reward-Space Transfer, while Mamba provides improved robustness as longer history dependencies are introduced.
### Title:
          Digital Twin-Assisted Mapping of ICS Telemetry to ATT&CK for ICS with Evidence-Driven Dependency Reasoning
 - **Authors:** Konstantinos E. Kampourakis, Vyron Kampourakis, Vasileios Gkioulos, Sokratis Katsikas
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reconstructing adversarial behavior from Industrial Control System (ICS) telemetry is difficult because process observations reveal physical changes more directly than the actions that produced them. This paper presents a Digital Twin (DT)-assisted framework that extracts synchronized state changes, converts them into evidence-preserving descriptions, maps them to ATT&CK for ICS through retrieval-augmented Large Language Model (LLM) reasoning, and constructs a typed dependency graph. Evaluation comprises a four-configuration ablation on nine held-out SWaT scenarios containing ten telemetry-evaluable ground-truth episodes, three independent generations of the principal mapping configurations, and external evaluation on BATADAL and WADI. Across the three SWaT generations, DT-enriched mapping produces fewer annotation-relative False Positive (FP) episodes in every run, with a mean per-run reduction of 34.1%. Both configurations obtain a mean recall of 0.633, although recall varies between 0.50 and 0.70 and DT enrichment does not improve F1 in every run. These observations are descriptive: the primary-run paired comparisons do not reach statistical significance, and the mapping advantage does not transfer to either external dataset. An exploratory positive-only dependency benchmark recovers eight of nine documented Co-occurrence relationships with DT context. A separate end-to-end benchmark containing one positive pair and 25 negative controls exposes propagation of mapping errors into unsupported edges. The findings identify both the potential and limitations of DT context for semantic security interpretation, without establishing reliable autonomous attribution, general causal reconstruction, or practical analyst benefit.
### Title:
          Predictor-Guided Latent Space Codon Optimization for Maximizing Protein Expression
 - **Authors:** Alberto Caron, Tianyu Cui, Dmytro S. Lituiev, Mangal Prakash, Artem Moskalev, Amina Mollaysa, Bo Zhai, Hirsh Nanda, Daniel M. Poole, Zhongyin Liu, Iman Farasat, Robert Davidson, Nikolay V. Manyakov, Tommaso Mansi, Scott Oloff, Rui Liao
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Codon optimization, the process of selecting synonymous codons to improve mRNA translation efficiency and protein expression, is central to therapeutic protein production and mRNA vaccines, yet it remains a hard problem. The design space is discrete and combinatorially large, precluding gradient-based methods, and existing tools rely on heuristic proxies (e.g., Codon Adaptation Index or GC-content) that poorly capture true expression. We introduce Latent-Space Codon Optimization (LSCO), which recasts this discrete problem as a continuous one by mapping sequences into the latent space of a pretrained mRNA language model, enabling efficient gradient-based search. LSCO combines four components: a data-driven expression objective from an uncertainty-aware predictor, a Minimum-Free-Energy regularizer for structural stability, a naturalness prior from a protein-to-codon back-translation model, and constrained decoding for protein fidelity. On a real-world, wet-lab antibody expression dataset, LSCO outperforms simple frequency-based, as well as modern deep generative baselines in predicted expression, while retaining suitable biophysical properties.
### Title:
          Emergent Structure in the Marginal Attention Space of Language Models
 - **Authors:** Valentino Maiorca, Walter Nelson, Francesco Locatello
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While representation similarity across independently trained language models is well-documented, how internal mechanics such as attention behave across models remains far less characterized. Inspired by this gap, we examine the structure of post-softmax attention weights by marginalizing over query positions, mapping them into a joint token-head "marginal attention space". Evaluating across 60+ diverse LLMs, we find that different properties emerge when reducing this space along its token and head axes. When reduced token-wise, marginal attention yields a text-intrinsic signal robustly conserved across models. To explain this property, we empirically connect marginal attention to the input-output Jacobian of the network, and prove theoretically that under a smoothness assumption, models with similar next-token distributions are guaranteed to have similar input-output Jacobian statistics. When reduced head-wise, it forms a model-private signature conserved across documents. Practically, this provides a natural way to estimate a per-head budget for key-value (KV) cache eviction, effectively decoupling model-specific budget allocation from text-intrinsic token scoring. On standard eviction benchmarks, a per-head budget precomputed offline on pretraining text, combined with a training-free token score, shows competitive performance with methods that recompute the budget on every document or train it per target. Code available at this https URL
### Title:
          Data-Free Weak-Form Staggered Neural Operators for Magneto-Mechanical Coupling in Finite-Strain Elastomers
 - **Authors:** Alireza Yazdandousthamedani, Ahmad Moeineddin, Reza Najian Asl, Shahed Rezaei, Michael Kaliske
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Magneto-active elastomers, as a class of smart materials, exhibit strongly coupled magnetic and mechanical behavior at finite strains. Considering variations in microstructure, material properties, and geometry can lead to computationally expensive analyses. Building on the finite operator learning (FOL) framework, this study develops a data-free, physics-informed operator-learning framework for families of coupled finite-strain magneto-mechanical boundary-value problems. The governing magnetostatic and mechanical equations are enforced through finite-element weak-form residuals, allowing the neural operators to be trained without labeled finite-element solution data. The main contribution of this study is the development of a weak-form staggered neural operator (WSNO) framework for strongly coupled magneto-mechanical saddle-point problems. Separate magnetic and mechanical neural operators are trained alternately using a staggered optimization strategy, while their physical coupling is retained through the constitutive relations and residual evaluations. The resulting framework learns mappings from parameterized material and geometric descriptions to the corresponding coupled magnetic and mechanical solution fields. The proposed framework is investigated across several settings, including heterogeneous random-inclusion microstructures, varying magnetic phase contrast, area-fraction-dependent geometries, strongly out-of-distribution material morphologies, and three-dimensional geometry-parametric problems. In addition, the learned operator is combined with a neural-initialized Newton strategy, in which the nonlinear finite-element solver is initialized using the neural prediction. The results demonstrate that the proposed operator-learning framework can accurately capture coupled magneto-mechanical responses across a broad range of parametric problem settings.
### Title:
          Implementation of Hybrid QoS-Aware Data Radio Bearer in 5G Networks
 - **Authors:** Padmapriya Patil, Abhishek Bhattacharyya, Gudepu Venkateswarlu, Andrea Fumagalli, Koteswararao Kondepu
 - **Subjects:** Subjects:
Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In Fifth-Generation (5G) wireless networks, Quality of Service (QoS) flow management supports diverse applications with heterogeneous QoS requirements, including latency-sensitive and high-throughput services. 5G architectures adopt a flow based QoS framework, where QoS flows are mapped to Data Radio Bearers (DRBs) to achieve the desired radio resource allocation. Existing mapping strategies typically rely on static one-to-one QoS-to-DRB mappings per PDU session, leading to inefficient spectrum utilization or inadequate support for delay sensitive traffic. This work presents a hybrid QoS-aware DRB mapping mechanism based on standardized 5G QoS Identifier (5QI) characteristics. The proposed framework incorporates multiple QoS flows within a single PDU session, supporting both many-to-one and one-to-one mapping strategies. The hybrid framework improves radio resource utilization and reduced bearer overhead by enabling flexible DRB utilization, where compatible non critical flows share DRBs while delay-critical flows are assigned dedicated DRBs to ensure strict QoS guarantees. The proposed hybrid QoS-aware DRB mapping is implemented using the open-source OpenAirInterface (OAI) mobile stack platform to demonstrate the integration of the proposed features within the existing 5G framework.
### Title:
          Kernel Singular Value Decomposition with Extension to Multiple Data Sources
 - **Authors:** Xinjie Zeng, Qinghua Tao, Johan Suykens
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Kernel Singular Value Decomposition (KSVD) learns a pair of singular vectors w.r.t. an asymmetric kernel matrix, which can be induced by two data sources, e.g., the queries and keys in self-attention or the rows and columns of a given matrix. In this work, we extend KSVD to multiple data sources, namely eKSVD, which conducts joint nonlinear feature learning upon asymmetric kernels. In the primal formulation, the projections associated with each data source are jointly learned to capture maximal information, while incorporating pair-wise couplings. With the Lagrangian and its Karush-Kuhn-Tucker (KKT) conditions, the optimization in the dual leads to a generalization of the shifted eigenvalue problem in Lanczos decomposition theorem of KSVD. Further, a covariance-based framework is derived together with using neural networks (NNs) for explicit feature mappings, complementary to the kernel-based interpretation and optimization. Numerical experiments verify the effectiveness of our eKSVD compared to methods based on Mercer kernels for tackling multiple data sources, and our innovation of deploying NNs demonstrates great flexibility for kernel methods.
### Title:
          DexJoCo-X: Benchmarking Action Representations for Multi-Hand Dexterous Manipulation
 - **Authors:** Xiangwei Jiang, Yao Mu, Lixin Duan, Wen Li
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As dexterous hands proliferate, collecting data and training policies separately for every morphology becomes increasingly impractical. Scalable cross-embodiment learning therefore requires a unified representation that captures shared manipulation structure while preserving morphology-specific control. Differences in hands, tasks, datasets, and control interfaces prevent existing studies from isolating the effects of representation, pretraining, and architecture. We introduce DexJoCo-X, a benchmark and toolkit for controlled comparison across seven representative dexterous hands, six single-arm and bimanual tasks, and 2,100 balanced demonstrations. DexJoCo-X provides a matched multi-hand, multi-task protocol with common scenes, success criteria, and execution interfaces, redesigned glove-to-hand mappings, and an automated pipeline that expands reviewed demonstrations across randomized scenes. Using $\pi_{0.5}$, Ego-Pi, and Being-H0.5, we examine whether a shared action interface is sufficient for multi-hand learning. Expanding $\pi_{0.5}$ to an 80-dimensional bimanual output yields near-zero success. Ego-Pi preserves the pretrained action head through interleaved prediction and supports per-hand multi-task learning, but remains ineffective for seven-hand joint training. By contrast, Being-H0.5 combines cross-embodiment pretraining, a unified action space, and embodiment-aware experts, enabling one policy to control all seven hands. Within this architecture, function-aligned action slots achieve 47.7% mean success, compared with 47.0% for native coordinates and 33.1% for DexLatent. These results show that cross-embodiment representation depends on the entire learning system: action coordinates, pretraining, and architecture must jointly separate shared manipulation structure from embodiment-specific control.
### Title:
          MobiAgent: Dual-Loop Recursive Policy Self-Improvement for Long-Horizon Mobile Manipulation
 - **Authors:** Chenzhi Liu, Yue Zhang, Jiehong Lin, Jianan Wang, Bo Wang, Zhongrui Wang, Xiaojuan Qi
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long-horizon mobile manipulation presents significant challenges due to compounding execution errors and capacity interference between locomotion and arm control. While recent Vision-Language-Action models excel at short-horizon tasks, they lack the hierarchical reasoning required for multi-stage objectives. Furthermore, existing hierarchical agents suffer from rigid sub-task mapping, inflexible replanning, and a lack of continuous learning. To address these limitations, we introduce MobiAgent, a dual-loop agentic framework that bridges robust deployment execution and recursive policy self-improvement. During deployment, the Inner Loop decouples high-level reasoning from low-level control through highly composable atomic skills. It employs Vision-Language models for receding-horizon planning and visual reflection, dynamically composing skills to ensure robust error recovery. These skills are executed by specialized flow-matching experts that share a unified VLM backbone, maximizing reusability while mitigating capacity interference. Concurrently, the Outer Loop drives automated lifelong learning by autonomously segmenting and verifying deployment rollouts, clustering them to discover atomic skills, and continuously fine-tuning the skill library without human annotations. Evaluations on RoboCasa, BEHAVIOR-1K, and real-world tasks demonstrate the effectiveness of MobiAgent. It outperforms $\pi_{0.5}$-TA by 22.5 percentage points on BEHAVIOR-1K and enables robust recovery from execution failures. Through autonomous data recycling, success improves from 7.50% to 27.50% on RoboCasa and from 32.5% to 57.5% on Astribot S1.
### Title:
          PrivDev: Mapping Static-Analysis Data Types to DPV
 - **Authors:** Simon Bernbeck, Ricardo Ramalho, Matheus Amendoeira, Juliana Alves Pereira
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Static-analysis scanners can identify personal-data types in source code, but they lack mechanisms to connect these findings to standardized privacy vocabularies. PrivDev maps 122 Bearer CLI data types to Data Privacy Vocabulary Personal Data (DPV-PD) categories and links them to potentially relevant GDPR provisions. Our approach combines deterministic mapping for 43 exact-label matches with a retrieval-grounded Large Language Model (LLM) to resolve the remaining 79 non-trivial mappings. The resulting RDF knowledge graph contains 118 ODRL policy resources that were structurally validated using SHACL. The artifact passed five complementary validation gates that cover structural correctness, query consistency, retrieval quality, LLM-based assessment, and human evaluation. In human evaluation, nine annotators produced 711 judgments, yielding a raw agreement of 0.72, Gwet's AC1 of 0.68, and Gwet's AC2 of 0.88. Our results indicate that the proposed mappings are plausible and reproducible, while also revealing ambiguities in scanner-defined data-type labels and coverage gaps in DPV-PD.
## Keyword: localization
### Title:
          Approximation Property of Dropout Neural Networks: Sobolev Rates and Confidence Bounds
 - **Authors:** Jia-He Yao
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The universal approximation property of dropout neural networks does not by itself describe the network size required for an accurate random realization. In this work, we study approximation of the unit ball of $W^{n,\infty}([0,1]^d)$ by ReLU networks whose edges are retained independently with probability $p$. The approximation error is measured uniformly over the input domain, and the guarantee holds with probability at least $1-\delta$ for a single sampled network. We construct networks of constant depth and size $\widetilde O_{n,d}(p^{-9}\varepsilon^{-\max\{d/n,2\}} \log(1/\delta))$. The construction combines bounded local subnetworks, localization on a successful approximation event, and a multiscale Taylor decomposition. Conversely, Sobolev capacity imposes a lower bound on the number of surviving edges, while approximation of a fixed affine function requires an output-layer cost of order $((1-p)/p)\varepsilon^{-2}\log(1/\delta)$ at sufficiently high confidence. For fixed $p\in(0,1)$ and $\delta<\min\{1/2,1-p\}$, the upper and lower bounds match in the accuracy exponent under a fixed or logarithmic depth budget. When $d\leq2n$, they also match in confidence up to logarithms of accuracy. We extend the lower bounds to $W^{n,r}$ targets with $L^s$ error, and distinguish this extension from the upper bound for $W^{n,\infty}$. The optimal retention dependence and logarithmic factors remain open.
### Title:
          An AI-Based Multi-Stage Approach for Androgenetic Alopecia Assessment from Low-Magnification Scalp Images
 - **Authors:** Mahmoud Raslan, Nada Omar, Omar Khaled, Tarek Waleed, Mohamed Hazem, Rania Mounir, Solwan Elsamanoudy, Ahmed Mourad, Noura Adel, Muhammad Rushdi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Androgenetic alopecia (AGA) is characterized by patterned follicular miniaturization, increased single-hair follicular units, and altered hair-shaft diameter. We present an automated quantitative scalp-analysis and clinical decision-support framework combining FU localization, ordinal visible-shaft counting, calibrated shaft-width estimation, regional aggregation, and an interpretable rule layer. The clinical cohort comprised 243 patients (127 AGA, 116 non-AGA), while the computer-vision experiments used 160 expert-annotated patients, 2,400 trichoscopic images, and approximately 158,000 FU annotations. Under patientdisjoint evaluation, YOLOv8m achieved test mAP@0.5=0.920 and recall=0.860; EfficientNet-B5 with a support-map channel achieved 87.0% expert-box count accuracy (macro F1=0.85). A separate 500-image set was processed end-to-end with detector-generated boxes, yielding MAE of 6.56 for follicle detection and 16.59 for follicle classification relative to human-expert annotations. The system is intended to assist, rather than replace, dermatologist interpretation.
### Title:
          From Fragments to Global Maps: Learning Vectorized Map Aggregation with Large Language Models
 - **Authors:** Ziwei Li, Yi-Tang Chen, Xiaoqi Wang, Wenbin He, Han-Wei Shen, Liu Ren
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large-scale vectorized HD maps provide structured road information that is essential for perception, localization, and planning in autonomous driving. Constructing such maps requires aggregating noisy, fragmented, and overlapping local predictions collected along a vehicle trajectory into a coherent global map. Existing aggregation methods typically rely on hand-crafted rules for fragment association and refinement. However, a fixed set of thresholds cannot effectively handle variations in road structures and prediction errors, often requiring detector-specific tuning or manual adjustment. To address this limitation, we propose MapMergeLLM, a data-driven framework that formulates vectorized map aggregation as conditional sequence generation with a large language model. Given serialized local vectorized maps, our model directly predicts the aggregated global map polylines. To reduce dependence on any particular upstream detector, we train the model on synthetic local maps generated from clean vector maps using corruptions that simulate representative prediction errors. We further introduce a coordinate tokenizer with geometry-aware pretraining to precisely represent map coordinates. In addition, we propose a line-level association loss that explicitly supervises correspondences between local observations of the same map element. Experiments on Argoverse2 and nuScenes using multiple recent upstream detectors demonstrate that MapMergeLLM substantially outperforms heuristic and optimization-based aggregation baselines without detector-specific retraining.
### Title:
          Nearly Optimal Fixed-Confidence Best-Arm Identification with 1-Bit Feedback
 - **Authors:** Khang Luong, Dinh Thai Son, Hoang Ta, Hung The Tran, Tuan Quang Dam
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study fixed-confidence best-arm identification under strict 1-bit feedback constraints. At each round, the learner selects an arm and a query set, and receives only a single bit indicating whether the sampled reward belongs to that set. We consider a distribution-free finite-variance setting with arm-wise localization, where direct empirical mean estimation is no longer available and clipping becomes unavoidable. We first formulate a time-uniform 1-bit mean-estimation primitive based on randomized threshold queries and a clipped tail-integral identity. We then embed this primitive into candidate-challenger best-arm identification algorithms. A fixed-clipping algorithm gives a simple anytime $(\epsilon,\delta)$-PAC guarantee, while a phased adaptive-clipping algorithm matches the clipping level to the current resolution and yields a gap-adaptive sample complexity. We also prove a $K$-arm worst-case information-theoretic lower bound showing that the logarithmic penalty caused by finite-variance 1-bit feedback is intrinsic. This bound matches the leading dependence of the phased algorithm up to lower-order $\log\log$ factors.
### Title:
          BISCEPTER: Probability-Driven Bisection for Large-Scale System Software
 - **Authors:** Mingyan Gao, Celine Wüst, Zuming Jiang, Zhendong Su
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Identifying the bug-inducing commit (BIC) is a fundamental step in regression debugging and a key input to emerging BIC-aware fault-localization pipelines. In practice, BICs are commonly obtained with bisection. Standard bisection selects the median commit of the remaining good-bad interval, thereby balancing commit count. This strategy is optimal under the assumption that each commit is equally likely to be the BIC. This paper shows that this assumption does not match real-world BIC histories. We construct a dataset of 8,172 bug reports from GCC, the Linux kernel, and MariaDB. We find a strong temporal skew: across the studied systems, 50% of BICs lie within the most recent 0.69% of the report-time commit history. Motivated by this observation, we introduce BISCEPTER, a probability-driven bisection approach that uses historical BIC latency as a lightweight prior. Instead of selecting pivots that split the number of remaining commits, BISCEPTER selects weighted-median pivots that split estimated BIC probability mass, while preserving the same good-bad oracle and interface as standard bisection. We evaluate BISCEPTER on three large-scale systems. The evaluation results show that BISCEPTER reduces bisection iterations by 25.75% on average (up to 55.55%) compared with standard median bisection, while improving over the baseline in 91.26% of test cases. Robustness experiments further demonstrate that the benefit remains stable under noisy historical data. We expect that our research can effectively save effort in debugging software in practice and, more broadly, benefit future software engineering research by bringing insights about BIC distribution.
### Title:
          Rethinking Fixed Temporal Grids: Frequency-Disentangled Motion Generation
 - **Authors:** Yunjiao Zhou, Junlang Qian, Gen Li, Xinying Guo, Lihua Xie, Jianfei Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Most human motion generation methods encode motion as tokens on a uniform temporal grid, where every token spans the same fixed time window. Human motion, however, is temporally heterogeneous: slowly evolving global trajectories coexist with rapid transient events such as foot contacts and joint impulses. Forcing such multi-scale dynamics onto tokens of identical temporal resolution entangles motion frequencies, leaving slow regions redundant while smoothing out the rapid details that distinguish realistic motion. We propose \textbf{FreqMo}, a scale-adaptive motion representation that decomposes motion into wavelet frequency bands, separating dynamics across temporal scales while preserving temporal localization and exact reconstruction. Unified Frequency Residual Quantization (UFRQ) then encodes all bands within a single shared codebook, compressing the token sequence threefold and enabling stable single-stage generation. Experiments show FreqMo attains SOTA fidelity with substantially improved high-frequency preservation, and the same decomposition transfers to continuous diffusion backbones.
### Title:
          Where to Look Is Not How to Fix: Pre-Denoising Diagnostics and Modality-Dependent Control in Diffusion Composition
 - **Authors:** Fangzheng Wu, Brian Summa
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding compositional failures in text-to-image diffusion requires identifying both where stress is detectable and how intervention changes the output. We study these questions through a controlled anchor--stress protocol that jointly evaluates text-encoder diagnostics and denoiser interventions. We introduce a text-only Compositional Stress Index (CSI), which separates common from rare compositions across SD1.5, SDXL, and the SD3 text path and provides an upstream diagnostic coordinate. A matched six-prompt localization study links intervention location to distinct outcomes: residual-minimizing embedding adapters improve representation fit, while downstream cross-attention intervention increases color hit rate (CHR) by 0.0272. Across SD1.5 and SDXL denoiser blocks, the largest positive signed diagnostic-accessibility mean occurs at the deep encoder, whereas selective boost has its largest positive mean CHR response at decoder blocks. Selective subtraction and broad ablation reveal further modality- and architecture-dependent responses, including a substantial CHR decrease when SDXL decoder cross-attention is broadly ablated. We find a diagnosis-control dissociation under our controlled attribute-object composition setting: compositional defects are diagnosable before denoising, but the representation coordinate that exposes risk is not necessarily the coordinate or modality that improves generation.
### Title:
          Geometry-Aligned Semantic Matching for Cross-Modal Planar Image Registration
 - **Authors:** Zhiwei Wang, Defeng He, Yuxing Li, Meilu Zhu, Edmund Y. Lam
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-modal image matching establishes stable and accurate geometric correspondences across modalities for planar registration. Existing semantic representations provide cross-modal consistency, but semantic similarity does not necessarily imply geometric correspondence. Meanwhile, fine-grained CNN features provide accurate local details but lack global cross-modal semantic guidance for stable refinement. To address these issues, we propose CDPM, which first establishes geometrically consistent semantic representations and then preserves their dominant role in correspondence estimation during fine-grained localization. Specifically, we progressively adapt DINOv3 using geometrically consistent cross-modal patch pairs, enabling feature similarity to better reflect true cross-modal spatial correspondences. We then construct a DINO-Centric Feature Pyramid, where multi-scale DINO representations maintain stable cross-modal correspondences, while a lightweight CNN branch provides auxiliary structural details for precise local refinement. Extensive experiments on three cross-modal datasets demonstrate the superior performance of CDPM. On VIS-IR, compared with the dense matcher RoMa, CDPM improves AUC@3/5/10/20 by 7.36, 13.40, 13.75, and 10.42 percentage points, respectively, and reduces mACE from 5.83 to 2.78 pixels. It also outperforms RoMa v2 across all metrics while requiring 45.6% fewer FLOPs. The online demo and dataset are available, and the code will be released on our project page at this https URL.
### Title:
          Evidence-Guided Repository-Level RTL Repair
 - **Authors:** Yuxin Du, Juxin Niu, Zhe Jiang, Nan Guan
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Repository-level RTL repair must localize a failure that spans files, modules, and clock cycles, then propagate the fix consistently. Existing methods reason over source code, which reveals possible behaviors but not the failed execution, and cannot tell whether a local fix was propagated consistently. We therefore present an evidence-guided framework with three modules. Failure grounding converts a problem statement into a reproduced failing run and a failure anchor. Waveform-guided localization uses a localization toolbox to narrow the observed violation into a candidate mechanism and an evidence trail. Consistency-aware repair and validation then expand that seed into a coordinated patch and replay the same scenario to check that the violation disappears. We conducted experiments on HWE-Bench and achieved better performance than the baseline.
### Title:
          Lightweight, Rubric-Guided Trajectory Evaluation for Production AI Agents
 - **Authors:** Linh-An Phan, MingXue Wang, Guangyu Wu, Feng Pan, Zhaoyu Pang, Yanbin Zhang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Trajectory evaluation is essential for improving the reliability of LLM-based agents, but production use makes it expensive to run repeatedly. Modern agents generate long traces containing tool calls, observations, retries, and external outputs, while not all raw tokens are equally useful for diagnosis. We present \textit{LiteTrajEval}, a lightweight architecture for budget-bounded trajectory evaluation. LiteTrajEval derives compact domain-specific rule profiles offline, then preprocesses each trajectory online, marks heuristic failure signals, serializes it under a fixed global budget, and invokes a single rubric-guided LLM judge to produce structured diagnostic reports. Evaluated on public Magentic-One-style and $\tau$-bench-style trajectory datasets, LiteTrajEval improves failure-localization alignment with human annotations by roughly 20--35 percentage points on Magentic-One and up to 23 percentage points on $\tau$-retail compared with AgentRx, while reducing cost by about 6$\times$ and evaluation time by more than 8$\times$. This solution has also been deployed in our enterprise agentic platform.
### Title:
          Reformulating plastic instabilities within a damage-like variational framework
 - **Authors:** Baptiste Reyne
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE); Materials Science (cond-mat.mtrl-sci)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Yield point phenomena in metals, anticracks in soils and snows, or planewise collapses in lattice metamaterials, are different manifestations of plastic instabilities characterized by stress softening and strain localization. Several independent constitutive descriptions exist and suffer from similar challenges: experimental difficulties to link local events to global measurements, and computational lack of convergence, spurious localization and mesh sensitivity. This work proposes a minimal field-agnostic constitutive framework where plastic softening is represented by a damage-like internal variable which explicitly separates stable hardening behavior from unstable softening. The resulting formulation admits a variational structure and can leverage regularization tools originally developed by the ductile fracture community. The framework aims at emphasizing similarities within plastic instability phenomena and establishing a bridge with continuum damage mechanics, to open a path towards regularized variational formulations of localized plastic flows.
### Title:
          Beyond Entropy: Self-Diagnostic Multi-Role Token Optimization for Video Reasoning
 - **Authors:** Yudong Han, Yong Wang, Zaiquan Yang, Liang Lin, Chongyang Tao, Xiangxiang Chu, Liyuan Pan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reinforcement learning with verifiable rewards has substantially advanced multimodal reasoning, yet it remains fundamentally limited by ambiguous token-level credit assignment. While high-entropy token heuristics encourage possibility exploration, naively extending them to video reasoning tends to induce lengthy reasoning, as the model becomes overly reliant on high-entropy visual activations. Alternative approaches that rely on counterfactual-based visual token localization for credit assignment also tend to over-prioritize visual exploration at the expense of decisive reasoning cues for answer derivation, thereby exacerbating the interference from spurious visual nuances. Moreover, these methods employ static counterfactual strategies that fail to co-evolve with the policy during training. In this paper, we introduce DyCPO, a co-evolutionary framework that jointly optimizes reliable token selection and adaptive counterfactual intervention. It constructs a multi-role dependence metric to balance visual exploration and answer-relevance mining in token-wise contrastive learning, while suppressing exploration-only filler tokens and spurious visual noise. Rather than relying on static counterfactual priors, DyCPO dynamically derives counterfactual signals from the model's own successful and failed rollouts, enabling self-diagnostic analysis and co-evolution of the optimization objective with the policy. Extensive experiments on complex video reasoning and general video understanding benchmarks demonstrate consistent performance improvements, establishing DyCPO as a robust token-level credit assignment paradigm for multimodal reinforcement learning.
### Title:
          Less Decoder is More Encoder: Geometric Representation Learning from Novel View Synthesis
 - **Authors:** Keerthi Kaashyap, Dennis Anthony, Akshay Krishnan, Nhi Ngoc Nguyen, Jeremy Collins, James Hays, Shreyas Kousik, Animesh Garg
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper examines the role of Novel View Synthesis (NVS) in geometric representation learning. In principle, NVS should reason about 3D scene structure, thereby enabling transferable multi-view geometric representations. Yet, existing encoder-based NVS methods yield poor representations. This is not because of a lack of supervisory signal, but rather due to inconspicuous architectural choices: \textit{spatially expressive decoders} that dilute representational capabilities of the scene encoder, and \textit{low-level pixel-space targets} that hinder feature learning. We present SNAP, a self-supervised encoder-decoder transformer that addresses both through a pose-conditioned local decoder and a latent-space reconstruction objective. SNAP is task agnostic, and we show that it is competitive with special-purpose geometry-supervised methods. SNAP also performs competitively against self-supervised representations across five tasks: visual localization, pose estimation, point correspondence, depth estimation, and robot manipulation. Remarkably, SNAP's patch features exhibit emergent viewpoint invariance that approaches heavily supervised models despite lower compute and data budgets. Under camera shifts where standard 2D representations collapse, SNAP degrades more gracefully, revealing that restricting decoder expressivity actively prevents the suppression of transferable geometric structure. this https URL
## Keyword: transformer
### Title:
          Effects of interpulse-interval variation on deep-learning classification of bat vocalizations
 - **Authors:** Welmoed R. Eversteijn, Burooj Ghani, A. Leonie Baier, Dan Stowell
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Temporal context may aid automated bat-species classification, but the contribution of specific features remains unclear. We investigated whether variation in the interpulse interval (IPI)-the time between consecutive call onsets-provides species-discriminative information and whether transformer-based models are more sensitive to this information than convolutional neural networks. We created two matched datasets from European bat recordings: a natural-IPI condition retaining the original call timing and a normalized-IPI condition in which call onsets were spaced at 50-ms intervals. EfficientNet-B0 and PaSST were fine-tuned and evaluated within each condition. In an additional experiment, each architecture was trained separately on natural-IPI and normalized-IPI recordings, and evaluated on the same natural-IPI test set. Finally, the pretrained classifiers BatDetect2 and BAT were evaluated on both conditions. Within-condition IPI normalization had model-dependent effects. PaSST accuracy differed little between the natural-IPI ($71 \pm 2.3\%$) and normalized-IPI ($70 \pm 6.3\%$) conditions, whereas EfficientNet accuracy increased from $47 \pm 4.7\%$ to $57 \pm 3.9\%$. PaSST exceeded EfficientNet under both conditions. In the cross-condition evaluation, models trained on natural-IPI recordings outperformed those trained on normalized-IPI recordings on the natural-IPI test set: accuracy decreased from 54% to 50% for EfficientNet and from 65% to 57% for PaSST. BatDetect2 and BAT differed little between IPI conditions. Overall, we found limited support for the hypotheses that natural IPI variation contributes substantially to bat-species classification and that it is used more effectively by transformer-based than CNN-based models. Nevertheless, the cross-condition performance decrease shows that results obtained under normalized conditions may not transfer fully to natural recordings.
### Title:
          AdaptViT: Runtime-Adaptive Vision Transformer Deployment on Custom RISC-V
 - **Authors:** Vishnu PS, Ajay Kumar M, Yike Li, Robert Bogdan Staszewski, Deepu John (University College Dublin, Ireland)
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deploying Vision Transformers (ViTs) on low-power edge devices is challenging due to high computational demands. Conventional pruning frameworks require a separate compiled binary for each sparsity level, increasing storage overhead and limiting runtime adaptability. This paper presents an end-to-end deployment pipeline that transforms pretrained ViTs into a single runtime-configurable binary, enabling dynamic compute-budget switching on embedded CPUs. This is achieved by restructuring generated C kernels with modified loop bounds and binary-mask control logic, allowing execution to switch across discrete sparsity levels via compact external configuration files. Compared to multi-binary deployment, the proposed runtime-adaptive approach reduces on-device storage by up to 4.86x, requiring only 163 MB for ViT-Base instead of nearly 800 MB. To maximize pruning efficiency, we introduce a hardware-aligned block pruning strategy for Multi-Layer Perceptron (MLP) layers. In addition, a custom ISA extension is proposed to exploit input-reuse patterns in linear projection kernels. On a Synopsys TRV32P3FX RISC-V processor, the full system achieves up to 2.8x speedup at 65% MLP and 50% attention-head pruning for ViT-Base. The ISA extension alone provides a 1.56x speedup and 33% lower inference energy, with a 24.7% area overhead in a TSMC 28 nm implementation.
### Title:
          Drive vs. Decay: On the Training Dynamics of Joint-Embedding Predictive Architectures
 - **Authors:** José Lucas De Melo Costa, Seong Woo Ahn, Fabrice Popineau, Arpad Rimmel, Bich-Liên Doan
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Joint-Embedding Predictive Architectures (JEPAs) are prone to representation collapse, typically mitigated through empirical heuristics. We develop an early-training stability theory that unifies these heuristics. Linearising the coupled JEPA gradient flow around the trivial fixed point reveals two competing effects: a driving force ($\gamma$) and a decay effect ($\sigma$). Under approximate spectral decoupling, a per-mode stability ratio $\mu_i = \gamma_i / \sigma_i$ factorises into independent data-side and predictor-side terms and the count of unstable modes tracks the rank of representations that can emerge. The framework predicts a phase boundary, which we confirm empirically across more than 800 Tabular-JEPA configurations. It also unifies predictor scaling, masking ratio, and EMA as distinct mechanisms for shifting $\mu$. Guided by this analysis, we introduce ResidualPred, a transformer predictor whose attention is biased toward the identity at initialisation; it improves both effective rank and downstream accuracy on tabular benchmarks and in I-JEPA pretraining on CIFAR-10, CIFAR-100, STL-10, and ImageNet. Our framework connects empirical collapse-avoidance heuristics to an explicit dynamical picture, yielding theory-driven stabilizers. Code is available at this https URL.
### Title:
          Lexicographic Multi-Objective On-Policy Distillation
 - **Authors:** Doseok Jang, Jon Ander Campos, Youran Qi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reinforcement learning from verifiable rewards (RLVR) usually optimizes answer correctness, yet useful language-model behavior also requires high-quality reasoning and concise responses. Existing multi-reward post-training methods typically scalarize rewards or combine specialists without explicitly protecting a reward priority order. This is problematic when trade-offs are asymmetric: conciseness, for example, should not improve at the cost of correctness. We introduce Lexicographic Multi-Objective On-Policy Distillation (LMOPD), a multi-teacher method for integrating reward-specialized policies under explicit priorities. For each student rollout, LMOPD selects the specialist for the first objective whose gate detects a deficiency, then locally projects its centered log-policy correction to remove components that oppose higher-priority specialists. We evaluate 30B-A3B mixture-of-experts transformer models in two- and four-expert settings on three math benchmarks, measuring retained specialist gains. With two experts, LMOPD's point estimates fully retain the accuracy and reasoning-quality gains while acquiring $46.9\%$ of the conciseness gain. With four experts, it retains $\approx90\%$ of both the accuracy gain and reasoning-correctness gain, compared to only $\approx57\%$ by the next best evaluated baseline. Matched four-expertablations show that lexicographic routing outperforms random routing and that projection further strengthens both top-priority capabilities. Across both scales, LMOPD preserves the highest-priority capabilities more effectively than the existing baselines we evaluate, demonstrating the value of explicit priorities for specialist integration.
### Title:
          THPL: A Vision-to-Language Decision Support Framework for Rainbow Trout Feeding Management in RAS
 - **Authors:** Meng Liang, Guanbo Feng, Haozhuang Chi, Shilong Zhao, Zhixin Xiong, Yuhang He, Wenfeng Han, Tianhao Zhao, Zhihong Ma, Ying Liu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In Recirculating Aquaculture Systems (RAS), precision feeding is critical for minimizing costs and improving fish welfare. However, existing methods lack cognitive alignment between fish behaviors and management knowledge, impeding translation into executable, interpretable feeding decisions. To address this, we propose THPL, a generative feeding decision framework tailored for rainbow trout (Oncorhynchus mykiss) in RAS. First, Fishsort extracts trajectories to establish an Activity Coefficient (AC) quantifying feeding intensity. Second, a Hierarchical Behavior Encoder (HBE) models individual temporal progression and collective dynamics using Temporal and Set Transformers, transforming trajectory tensors into dual-evidence representations of explicit physical and implicit soft tokens. Finally, these tokens are integrated with environmental parameters, metadata, and expert rules to fine-tune an LLM via LoRA, followed by counterfactual multimodal Direct Preference Optimization (mDPO) to reinforce causal reasoning. Results show that AC exhibits a statistically significant monotonic positive correlation with expert-annotated feeding intensity (Spearman $\rho = 0.925$, $p < 0.001$). Ablations indicate that decision accuracy improves from 33.33% (text-only baseline) to 93.33% with dual-evidence tokens, confirming that continuous spatiotemporal tokens provide necessary physical grounding for LLMs. Compared with standard LoRA, counterfactual mDPO elevates decision accuracy from 93.33% to 96.67%, advances METEOR from 58.10% to 85.30%, reduces Self-BLEU-2 from 58.79% to 52.88%, and increases Distinct-3 from 6.68% to 7.81%, suppressing templating and actuation biases while reinforcing causal consistency and operational safety. Overall, by integrating continuous kinematics with LLM reasoning, this study provides a novel decision support paradigm for precision aquaculture.
### Title:
          The Surprising Effectiveness of Shared Memory in Looped Transformers
 - **Authors:** Giovanni Monea, Keshav Ramji, Yousef El-Kurdi, Luis A. Lastras, Yoav Artzi, Nathan Godey, Ramón Fernandez Astudillo
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Looped Transformers apply the same layers several times per token, adding compute to improve quality without more parameters. Each recursion, however, writes its own key-value cache, so memory still grows with compute. Inference-time techniques can shrink this cache at a cost in quality. We pretrain looped language models to share memory: only the first recursion writes a cache, and later recursions read it while keeping a short window of their own. Surprisingly, we find that sharing memory does not cost quality and instead improves it. At 150M-1B parameters, our Looped Prediction Transformer (LPT) and its hybrid variant set a new quality-memory frontier for looped models: with five recursions, the hybrid lowers validation perplexity on FineWeb-Edu by 1.12-1.82 relative to a same-size standard Transformer while using 76-79% less context memory. Through an extensive analysis, we investigate why memory sharing helps. Shared and local memory develop different representations, and later recursions attend mostly to the shared memory, which also acts as a gradient highway to the first recursion.
### Title:
          From Retrieval to Typed Decisions: Calibrated System One Models from Biomedical Sentence Encoders
 - **Authors:** Pritam Deka
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Typed decision models answer schema-constrained questions about a text in one forward pass and return probabilities meant to be thresholded. We ask whether biomedical sentence encoders trained for retrieval are good starting points for such models. We present SBERT2S1, which converts Sentence-Transformers encoders into bi-encoder, cross-head (C) and prior-fused residual (PFR) decision models, together with BIODECIDE, a biomedical typed-decision suite, and MEDLINE-S1, 243k training decisions derived from NLM indexing. Across six parent-retriever pairs, retrieval training improves zero-shot matching of content-bearing options. After fine-tuning, its effect depends on the head: across five pairs and three training-set sizes, retrieval training significantly helps PFR, which keeps the retrieval prior, in 10 of 15 comparisons, but helps C in one and hurts it in five. A matched grid of two heads and five training objectives shows that C outperforms PFR under every objective, and that the released RLCD recipe of open System One models trails cross-entropy by 2.5-3.0 points. The deficit stems mainly from its reward normalisation, which inflates the noisy score-function term 3.6-15-fold; an unbiased leave-one-out estimator recovers most of the gap. After temperature scaling, no objective is clearly better calibrated than cross-entropy. We release the code, the MEDLINE-S1 labels and a model.
### Title:
          LiteEMG-FM: An Efficient and Deployable Foundation Model for Robust EMG Sensing
 - **Authors:** Tianhao Wu, Xu Wu, Amirmohammad Radmehr, Jiawei Yu, Yi Wu, Phuc Nguyen, Jian Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Electromyography (EMG) signals vary substantially across individuals, body regions, recording sessions, and sensing hardware, limiting the generalization of models for assistive devices and human-computer interaction. Existing time-series foundation models are also computationally expensive for real-time wearable deployment and often fail to capture EMG-specific time-frequency characteristics. We present LiteEMG-FM, an efficient hybrid CNN-Transformer foundation model for practical EMG sensing. Pretrained on 16 diverse upper- and lower-limb EMG datasets, LiteEMG-FM learns representations that generalize across users and datasets. For resource-constrained deployment, we implement a hierarchical wake-up architecture in which a lightweight, always-on 1D-CNN filters rest and non-target activity and activates LiteEMG-FM only for valid gestures. We evaluate full inference offloading, split inference, and full on-device processing, characterizing their trade-offs in latency, power consumption, and memory footprint. Across diverse evaluation settings, LiteEMG-FM outperforms state-of-the-art time-series foundation models and supervised baselines, particularly under zero-calibration cross-participant and data-scarce conditions. These results demonstrate that LiteEMG-FM is an effective, efficient, and deployable foundation model for EMG applications.
### Title:
          Autoregressive Differentiable Method for Integer Programming
 - **Authors:** Ouns El Harzli, Yudong Cao
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce an autoregressive differentiable method to solve 0-1 integer programs. We fix an arbitrary order of the binary variables and we train a transformer to predict the next bit while remaining in the feasible set. Our method is first trained on feasible incumbents provided by any solver, thus allowing us to initialize the transformer in the feasible set. Our procedure then implements a Lagrangian penalty to penalize infeasible solutions, and the transformer is further trained to explore the feasible set using Gumbel-softmax activations on the relaxed objective. We have tested our method on non-convex instances of quadratic knapsack problem and demonstrated consistent improvement upon state-of-the-art open-source solvers for dense problems up to 10,000 binary variables. In particular, we empirically demonstrate a phenomenon akin to a tunneling effect where the effective change of variables from binary variable to the continuous weights of the transformer that the method implements enables crossing barriers in the relaxed objective landscape.
### Title:
          A generative-informed neuro-symbolic framework for syntactic ambiguity resolution: Evidence from Arabic DPs
 - **Authors:** Mohammed Damom, Muneef Y. Alshawsh, Ashraf A. Naji, Mustafa Ali Alhamzi, Fawwaz An-Nashef, Jameel Ahmed Elayah, Mohammed Q. Shormani, Noman AL-Sayadi
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Syntactic ambiguity poses a persistent challenge for Arabic NLP, particularly in morphologically rich nominal constructions where multiple structu6ral interpretations may be compatible with the same surface sequence. This study proposes a generatively informed neuro-symbolic framework for resolving structural ambiguity in Modern Standard Arabic (MSA) DPs. The framework integrates generative syntactic notions with AraBERT by representing ambiguity as a candidate-based decision task in which linguistically motivated alternatives are explicitly constructed and evaluated through candidate-conditioned input representations. Findings indicate that the model achieved 96.88% accuracy, 95.92% macro-F1, 96.83% weighted F1, and 93.94% binary F1 on the unseen evaluation set. Class-level analysis revealed asymmetric performance, with recall of 99.71% for High/VP Attachment (N1) and 89.26% for Low/NP/Embedded Attachment (N2), indicating greater difficulty in recovering the embedded interpretation. The study concludes that formal syntactic representations can be operationalized within Transformer-based NLP as an explicit interface between linguistic structure and contextual neural modeling, providing a controlled and interpretable approach to Arabic syntactic ambiguity resolution and beyond.
### Title:
          DAGS: Disentangled Appearance-and-Geometry Steering of a Frozen Image DiT for Temporally Stabilized Generative Rendering
 - **Authors:** Karthik Mohan Kumar, Damian Andrysiak, Pedro Antonio Pena, Kunal Tyagi, Rama Harihara
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Graphics (cs.GR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion transformers (DiTs) generate high-fidelity images from text and image conditions, but their outputs carry large variance and their faithfulness to a desired target depends heavily on how the condition is supplied. We present DAGS, a lightweight, attention-free, disentangled appearance and geometry conditioning scheme that steers a frozen image DiT to produce high-fidelity, highly faithful, and independently controllable renders. Two small convolutional encoders compute conditioning features once per frame and inject them as a learned, per-layer, element-wise residual into the image tokens, avoiding the quadratic cost of stacking conditions through attention. Because control and temporal handling live outside the frozen backbone, we retain its vast pretrained prior and eliminate backbone-overfitting risk. We further add a small recurrent lighting stabilizer and a training-free temporal guidance term that, coupled with our conditioning, elevate a per-frame image model into a streaming renderer. DAGS produces controllable, high-quality renders at a fraction of the compute of path tracing; it is not real-time, trading compute for controllability and quality. On a matched 1-spp + G-buffer input, per-frame DAGS reconstructs +8.6 dB / +10.1 dB PSNR over the real-time denoiser Intel OIDN and the diffusion renderer RGB<->X while being 2.5-8x more temporally stable perceptually (temporal-LPIPS flicker).
### Title:
          Distributed Learning with Selective State Space Models: Architecture-Aware Convergence Analysis
 - **Authors:** Adam Piaseczny, Md Kamran Chowdhury Shisher, Shiqiang Wang, Christopher G. Brinton
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern state space models (SSMs), such as Mamba2, provide a compelling alternative to transformers by combining linear-time sequence modeling with recurrent state-space dynamics. However, the behavior of SSMs in distributed learning settings remains poorly understood. In particular, the existing standard federated learning methods are largely architecture-agnostic, and do not account for the stability, selectivity, and state-space parameterization that characterize modern selective SSMs. To address this, we derive architecture-aware gradient and smoothness bounds for single- and multi-layer selective SSMs, and convergence bounds for FedAvg and FedProx, characterizing how recurrent stability, input-dependent discretization, and state projection norms affect federated optimization. We then numerically validate the single-layer bounds on sequences generated by a teacher SSM, using a learner that follows the analyzed recurrence. We use this analysis to formulate expectations about the effects of local training and client heterogeneity, and examine these expectations by comparing nine federated learning algorithms on Mamba2 language modeling across six text domains. These experiments illustrate how SSM-specific bounds can provide a basis for interpreting the behavior of practical federated learning algorithms.
### Title:
          SpectralCache: Accelerating Diffusion-Based World Models via Spectral Feature Caching
 - **Authors:** Zhendong Mi, Pu Zhao, Ziyu Hu, Xiaodong Yu, Yanzhi Wang, Grace Li Zhang, Shaoyi Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion-based world models enable high-quality interactive environment generation but suffer from substantial inference overhead due to repeated Transformer evaluations during denoising. Existing caching methods mainly exploit temporal redundancy at the feature or token level, leaving the underlying mathematical structure of diffusion features largely unexplored. In this work, we reveal that world-model features exhibit highly stable singular subspaces across nearby denoising steps, while their singular values follow predictable evolution patterns. Building on this observation, we propose SpectralCache, a training-free spectral caching framework that reuses stable singular subspaces and estimates only low-dimensional singular values through linear extrapolation. We further exploit the spectral consistency between neighboring full-computation features to skip selected expensive backbone evaluations via singular value scaling. Extensive experiments on representative world models demonstrate that SpectralCache consistently improves inference efficiency while preserving generation quality. On HunyuanWorld-Voyager-13B, SpectralCache achieves 5.22x acceleration while maintaining a WorldScore of 65.90 for static scenes, substantially outperforming existing training-free caching methods in inference efficiency.
### Title:
          AIGS: Adaptive Incremental Gating System for Online Representation Learning in Non-Stationary Data Streams
 - **Authors:** SiRui He, Kai Liang Lew, Chui Zi Ong, Chean Khim Toa
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-time data streams in Web of Things (WoT) and edge computing environments often evolve through latent regime changes. For online representation learning under strict computational constraints, the central problem is resolving the stability-plasticity dilemma: keeping useful historical knowledge while rapidly reacting to concept drift. Existing methods employ fixed update schedules or rolling windows. However, they suffer from parameter ossification during sudden shifts and waste computational resources when the stream remains stable. This paper proposes the Adaptive Incremental Gating System (AIGS), a lightweight closed-loop state-aware adaptation framework. AIGS introduces the Shock Ratio, an endogenous residual feedback mechanism that normalizes current reconstruction error against recent variation. This signal drives a Continuous Plasticity Controller that smoothly interpolates between learning plasticity and memory retention. By treating representation learning as a closed-loop control mechanism, AIGS avoids catastrophic forgetting and maintains a strictly linear $\mathcal{O}\left(k\cdot d\right)$ per-step complexity suitable for latency-sensitive edge devices. Experiments on real-world smart city dynamic streams-spanning traffic networks, meteorological systems, and industrial infrastructure-demonstrate distinct domain-dependent advantages. On Electricity Transformer Temperature datasets, AIGS achieves preventative early-warning lead times of 8.31 (ETTm1) and 9.88 (ETTm2) steps under gradual degradation. On Performance Measurement System traffic datasets, it shows significantly faster post-shift recovery after abrupt mutations. On the highly noisy Weather dataset, it improves anomaly recall while resisting stochastic noise overfitting. These findings establish AIGS as a practical, plug-and-play adapter for resource-constrained edge monitoring systems.
### Title:
          Inferring constitutive forces from noisy Allen-Cahn movies with moment equations
 - **Authors:** Soobeen Jung, Hyunju Kim
 - **Subjects:** Subjects:
Numerical Analysis (math.NA); Mathematical Physics (math-ph); Pattern Formation and Solitons (nlin.PS); Fluid Dynamics (physics.flu-dyn)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Inferring an Allen-Cahn constitutive force from images requires more than an accurate optimizer: nonlinear observation noise alters the mean of force features, shared noise couples instruments to the response, and a temporal balance borrowed from another solver can remain biased even on clean data. We develop observation-aware, noise-adjusted moment equations that address these effects before inversion. The surface-tension-calibrated constitutive transformer (SCCT) couples the resulting moments to a positive Bernstein inverse and can adapt its prior and precision from images and moments. A conditional stability bound separates moment residuals from prior error. Synthetic tests show that correcting the estimating equation matters more than increasing regularizer flexibility; the benefit of learned adaptation is smaller and depends on the training comparison. Forces inferred from planar movies predict unseen planar and three-dimensional evolutions. A ring-cage breakup shows why diffuse-interface accuracy distinguishes forces even when their topological predictions agree, while external surface tension sets the energy scale separately.
### Title:
          Conditional Capacity and Routing in Mixture-of-Experts Particle Transformers
 - **Authors:** Kaushik Pendiyala, Haris Zia, Trevin Lee, Timothy Legge, Alejandro J. De Leon, Zihan Zhao, Aaron Wang, Abhijith Gandrakota, Jennifer Ngadiuba, Richard Cavanaugh, Javier Duarte
 - **Subjects:** Subjects:
Machine Learning (cs.LG); High Energy Physics - Experiment (hep-ex)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mixture-of-Experts (MoE) models can increase parameter capacity without proportionally increasing active computation, but it is unclear how this trade-off behaves in particle-physics transformers. We study dense and MoE Particle Transformers on 188-class JetClass-II, varying expert count, routing capacity, top-K, and auxiliary loss. We find that, when token dropping is avoided, top-1 MoE models improve over the dense baseline at nearly unchanged nominal forward compute, while further increasing the number of stored experts produces little additional accuracy gain. Activating multiple experts per token yields additional predictive improvements at higher computational cost. Routing analyses show that expert assignments become more strongly associated with particle identity and kinematics in some configurations, but this structure does not increase monotonically with classification performance. These results highlight the need to distinguish stored parameter capacity, active computation, routing capacity, and routing organization when evaluating sparse expert models for jet classification. Code and experiment configurations are available at this https URL.
### Title:
          On the Chain-of-Thought Monitorability of Looped Language Models
 - **Authors:** Han Wang, Ishwar B Balappanawar, Huan Zhang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Chain-of-thought (CoT) monitoring provides a promising approach for detecting undesirable model behavior. Looped language models (LoopLMs) repeatedly apply shared transformer layers, increasing effective computational depth and enabling additional latent computation without increasing model size. However, the effect of looped architectures on CoT monitorability remains largely unexplored. In this work, we provide the first systematic evaluation of CoT monitorability in LoopLMs. We study two complementary settings: (1) varying the loop depth within the same LoopLM family to isolate the effect of additional recurrent computation, and (2) comparing LoopLMs with non-looped language models matched by parameter size, transformer-layer count, or effective depth to study whether LoopLMs are less monitorable. Across eight tasks from MonitorBench and both standard and stress-test settings, we observe task-dependent reductions in CoT monitorability under stress tests on specific Logic/Science/Engineering \texttt{Cue Answer} tasks, while other tasks exhibit weaker or qualitatively different trends. Our diagnosis suggests that these declines are not fully explained by task difficulty, verification pass rate, or generated token length; qualitative examples further suggest changes in how deeper-loop models explicitly use or attribute provided cues. Our cross-model comparison finds no evidence that LoopLMs are systematically less monitorable than non-looped language models matched on size or depth. Overall, our results suggest that deeper loop depth can reduce CoT monitorability in some tasks under stress tests, but looped transformer architecture alone does not necessarily imply lower monitorability.
### Title:
          Proprioceptive Sketches as Long-Horizon Intent for Generative Action Policies
 - **Authors:** Fangyuan Wang, Songhao Huang, Haoxiang Sun, Shipeng Lyu, Chengyang He, Anqing Duan, Peng Zhou, David Navarro-Alarcon
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative robot policies predict short action chunks but lack explicit long-horizon intent. Recent methods expose longer-horizon structure through language plans, subgoal images, or video forecasts, which are costly to generate and still need to be translated into robot motion. Predicting future robot motions avoids this translation, but a dense, time-indexed trajectory requires numerous parameters to cover the full remaining task, and over a short horizon it largely repeats the action chunk and adds little guidance for action generation. We propose Proprioceptive Action Models (PAM), which jointly generate a compact, timing-free sketch of the robot's remaining joint-space path and a dense executable action chunk within a single transformer denoiser. The sketch parameterizes the path by arc length rather than time, capturing geometric intent invariant to execution timing. Block-causal attention and a staggered denoising schedule maintain directed sketch-to-action dependence, ensuring the action tokens condition on a progressively cleaner sketch throughout sampling. In simulation, PAM improves over its action-only counterparts on Push-T and LIBERO-Long; on four real-world bimanual tasks, it raises success from 47.5% to 75.0%. Project page: this https URL
### Title:
          Muon Learns Facts Better: Understanding the Role of Spectral Orthogonalization
 - **Authors:** Xuheng Li, Qiwei Di, Yuan Cao, Quanquan Gu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Optimization and Control (math.OC); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Muon optimizer applies spectral orthogonalization to matrix-valued updates and has shown strong performance in large-scale neural network training, yet the mechanisms of this transformation in feature learning remain poorly understood. In this work, we investigate this question through a tractable factual-recall model, where a fact maps each subject-relation pair to an answer, and a linear transformer learns the subject- and relation-dependent information required to recover this mapping. The transformer is optimized with gradient flow (GF), spectral GF, or Sign GF, which are continuous-time limits of gradient descent, Muon, and Adam, respectively. Prior studies (Nichani et al., 2025) have shown that when the number of subjects exceeds the number of relations, GF learns relation-dependent information before subject-dependent information, producing a feature-separation phase during training. We characterize this separation with the learning times when the subject- and relation-dependent components of the prediction reach a target accuracy. With $S$ subjects and $R$ relations, GF has a learning-time ratio of $\widetilde{\Theta}(\sqrt{S/R})$, whereas Spectral GF reduces this ratio to $\widetilde{\Theta}(1)$. In addition, for fixed $S$ and $R$, the subject- and relation-dependent errors decay as $1/(T\log T)$ in training time $T$ under GF, but as $\exp(-\mathrm{poly}(T))$ under spectral GF. Finally, we show that GF and spectral GF are equivariant under orthogonal transformations of the token embeddings, whereas Sign GF is not: Different orthonormal embeddings can potentially produce no feature separation, a large feature-separation phase, or even a reversed learning order. These results provide a mechanistic view of how spectral orthogonalization can fundamentally reshape feature-learning dynamics.
### Title:
          How Far Back Should a Transformer Look? Repetition and Copying in Music Sequence Models
 - **Authors:** Amir Fathi
 - **Subjects:** Subjects:
Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We investigate how predictive performance depends on the maximum context available to an autoregressive model of symbolic music, and what information long-context models exploit. A small causal Transformer is trained separately at each context length T in {6, 18, 48, 96, 192, 336} and evaluated on the same target positions, both over raw tokens and over non-overlapping binary latent codes. On Nottingham folk tunes, the token predictor's test NLL decreases by 71% (0.986 bits per token) between 6 and 336 tokens, and by 71% on the O'Neill's tunes long enough for the same sweep (129 of 302 test tunes). Most of the long-context gain is explained by exact copying: the improvement appears when an earlier occurrence of the target's 16-token history enters the available context; overwriting that occurrence removes the gain, whereas equally large unrelated corruption does not; and a simple copy baseline recovers 94% of the reduction. A trained 336-token model likewise loses most of this gain when its history is restricted to recent tokens at test time. Because many repeats arise from written repeat signs expanded in the score, this result pertains specifically to these rendered score representations. By contrast, on MAESTRO performances and MusicNet scores, where exact repeats are substantially less frequent, the reduction is smaller (9% and 18%) and is largely attained by 96 tokens. Finally, an audit of an earlier draft that reported saturation at 16 tokens identified split leakage, overlapping latent receptive fields, an averaging predictor, and a per-file tempo grid; we present these as methodological checks for context-length measurements.
### Title:
          Permutation Robustness Is Not Enough: Action Collapse in Multi-Agent Transformer Policies
 - **Authors:** Amit Thakur, Mukesh Singhal
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer policies are attractive for multi-agent robot learning because self-attention can model interactions among agents. However, multi-agent teams are unordered, while transformers typically process agents as ordered token sequences. We study how this mismatch affects cooperative navigation policies under agent-order permutations. Our results show that low permutation error alone can be misleading: policies may appear robust simply because all agents choose the same action. We therefore evaluate policies using both permutation-consistency metrics and action-collapse diagnostics, including action diversity, same-action fraction, and maximum action frequency. A PPO-ID baseline yields non-collapsed behavior but remains order-sensitive, while strong equivariance regularization can still induce homogeneous behavior. A weak equivariance penalty improves the robustness while preserving more diverse actions for teams with \(N=3\) agents, whereas teams with \(N=4\) agents require substantially smaller regularization weights. These findings suggest that multi-agent transformer policies should be evaluated not only by return and permutation robustness, but also by whether they maintain non-collapsed, differentiated multi-agent behavior.
### Title:
          Learning Jazz Pianist Style with Cross-Attention Conditioning
 - **Authors:** Drew Edwards, Akira Maezawa, Simon Dixon
 - **Subjects:** Subjects:
Sound (cs.SD); Machine Learning (cs.LG); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Jazz pianists develop distinctive traits that experienced listeners can often identify within seconds, yet the features underlying this recognition resist formal description. We study jazz pianist style through the lens of a pretrained symbolic music transformer, showing that its learned representations already encode pianist identity well enough for highly accurate classification across two benchmarks. We then augment the transformer with cross-attention over learned pianist identity embeddings, enabling it to generate music conditioned on a specific artist's style. Two evaluation protocols confirm that the generator captures meaningful stylistic structure: a sliding-window classifier consistently attributes conditioned continuations to the correct artist, far above unconditioned baselines; and a classifier trained entirely on synthetic generations identifies real pianists across 12 classes with 87% chunk-level and 95% song-level accuracy. Finally, we repurpose the classifier to locate the most characteristic moments within a performance, surfacing the specific musical gestures that distinguish each pianist's voice.
### Title:
          FARM: Fundamental Agentic Reward Model For Multi-task Wireless Network Optimization
 - **Authors:** Feiran You, Changxu Ni, Haozhe Ma, Jun Li, Hongyang Du
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Future wireless networks require learning agents to adapt across heterogeneous channel conditions, traffic patterns, quality-of-service (QoS) requirements, objectives, and operational constraints. Reusing decision knowledge across such tasks is challenging because conventional multi-task and transfer reinforcement learning methods primarily share or transfer policies, coupling transferable knowledge with task-dependent action mappings. This paper proposes FARM (Fundamental Agentic Reward Model for Multi-task Wireless Network Optimization), a reward-space transfer framework that shifts cross-task knowledge reuse from policy space to trajectory-level decision evaluation. FARM introduces an Agentic Reward Model (ARM) that learns a task-conditioned reward prior from heterogeneous source-task trajectories and provides auxiliary guidance for task-specific policy optimization. In Stage I, ARM jointly models task conditions, temporal trajectory dependencies, and objective-dependent reward structures while each source task retains its own controller. In Stage II, the learned reward prior is frozen and reused to guide the adaptation of a target-specific controller for previously unseen tasks, without transferring source-task policies. Experiments on heterogeneous multi-access edge computing (MEC) tasks show that FARM achieves a mean late-stage gain of 29.8% over Single-task SAC on unseen Rate-Latency targets, compared with 16.1% for CRA Transfer, and reaches a 46.2% gain on the moderate-OOD FAR-M case. Further analysis shows that both Mamba and Transformer trajectory encoders support Reward-Space Transfer, while Mamba provides improved robustness as longer history dependencies are introduced.
### Title:
          When Does Synthetic Relational Data Teach Models to Use Relations? Tracing Predictive Structure from Pretraining Data to Model Behavior
 - **Authors:** Shivam Dubey, Mohamed Bouadi, Nassim Bouarour, Varun Kulkarni, Aditya Tanna, Vinay Kumar Sankarapu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Relational foundation models are increasingly pretrained on synthetic databases, yet downstream benchmarks reveal little about why one synthetic corpus produces a better model than another. In particular, strong performance may arise from realistic row-level statistics without the model ever learning to use relational structure. We study this as a data-attribution problem: which property of synthetic pretraining data induces relational computation? Using four Relational Transformer checkpoints trained with the same architecture, initialization, objective, and compute budget on corpora produced by four relational data generators, we trace a measurable property of the data to learned computation and downstream behavior. We hypothesize that relational mechanisms emerge when cross-table information is predictively necessary for the masked-cell pretraining objective. RelDiff exhibits by far the largest predictive gain from foreign-key-linked parents, and its corresponding model is uniquely sensitive to foreign-key interventions on unseen databases. This dependence survives a random-initialization control, grows monotonically with the fraction of corrupted links, and localizes to a serial cross-table pathway. Finally, disrupting the same mechanism during downstream inference removes RelDiff's advantage on relational tasks while leaving structure-insensitive models nearly unchanged. These results connect a property of synthetic training data to a learned mechanism and, through intervention, to downstream behavior.
### Title:
          Does Physics Live in the Activations? Localizing Physical Quantities in Video Diffusion Models
 - **Authors:** Jonas Kneifl, Jakub Skalski, Bartłomiej Twardowski, Kamil Deja
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video generation models produce strikingly realistic sequences and are increasingly proposed as world models, yet recent benchmarks reveal pronounced deficits in their physical reasoning. This raises the question of whether these models internalize physical principles or merely reproduce familiar motion patterns. We address this by probing internal representations of video Diffusion Transformers (DiTs) for simulator-derived ground-truth physical quantities spanning kinematic motion and rigid-body dynamics under gravity and contact. We find that these quantities are linearly decodable with high accuracy early in the denoising process, substantially outperforming a baseline decoded directly from the model's own noised latents, indicating that the relevant physical information is actively constructed during denoising rather than already present in the input. Additionally, we show that activations at on-object tokens carry the relevant physical information and that quantities defined over multiple frames are readable from single latent frames. Hence, information is sharply localized within the token sequence and is computed globally but stored locally. The probes further show partial extrapolation, transferring to scene variations and object configurations outside their training regime, so what they read is not simply a correlate of the scenes they were fit on. When fitted directly in the full-resolution activation space, the probing directions can serve as steering vectors to change the model's output.
### Title:
          COSMI: COmpositional Synthesis of Multi-object Interactions
 - **Authors:** Daniel Eskandar, Ilya A. Petrov, Gerard Pons-Moll
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative models of human-object interaction are bounded by the data that exists: everyday activities involve several objects, but most captured datasets record one at a time, as multi-object capture is combinatorially expensive. Our observation is that interactions are local, so single-object captures already contain the parts of multi-object activities. We compose them: contact-consistent clips of single interactions, mirrored to balance the hands, transfer between bodies, and a language model and geometric checks admit only the pairings that are plausible, semantically and physically. Therefore, the dataset grows combinatorially with the clips rather than recording time. The COSMI dataset holds 222k sequences and 275 hours with up to five objects, nearly thirty times the largest multi-object capture, and can be extended by adding datasets or even hand-object recordings. On this data we train the COSMI method, a text-to-interaction diffusion transformer that follows how the data is built: weight-shared object slots generate a variable number of objects, predicted relative to the body parts that move them. On a benchmark with an unseen object and unseen interaction combinations, models trained on the dataset generalize to the unseen combinations. COSMI outperforms baselines in text alignment and contact accuracy, where its margin is largest on the unseen object. Code, models, and the dataset pipeline will be released on the project page: this https URL.
### Title:
          PEACE: Joint Embeddings of DSP Effects Code and Audio
 - **Authors:** David Braun, Adam Finkelstein
 - **Subjects:** Subjects:
Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper introduces PEACE, the first joint embedding of audio effect code and output audio. Building on SLAP's multimodal objective, we pair an AFx-Rep audio encoder with two code encoders for Faust, a functional language for audio signal processing. First, we evaluate a fine-tuned T5 transformer over Faust source code. Second, we evaluate a message-passing graph neural network over an intermediate representation of the Faust compiler, capturing both topology and UI parameters. We evaluate on audio-to-code retrieval, where masking UI parameters at inference yields embeddings that encode effect chain topology alone. When parameters are visible, the two code encoders tie on retrieval of mixed-length chains but have tradeoffs on single-effect galleries. With parameters fully masked, PEACE recovers ordered chain topology far above chance without the limitations of supervised methods. PEACE outperforms pretrained models on an out-of-distribution reverb retrieval benchmark and can improve frozen audio-only representations. Its dual understanding of topology and parameters lays the groundwork for music information retrieval systems that search, generate, and condition on DSP code.
### Title:
          I2CD: Direct Image-to-Convex Decomposition for Simulation-Ready Collision Geometry
 - **Authors:** Qian Wang, Liam Merz Hoffmeister, Brian Scassellati, Daniel Rakita
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Physics simulators and motion planners require convex collision geometry, yet image-to-3D generative models output dense, frequently non-manifold visual meshes. Bridging the two today takes a slow, brittle reconstruct-then-decompose pipeline of repair, decimation, and approximate convex decomposition. We present I2CD, which predicts a convex decomposition directly from a single RGB image. Rather than train a new image-to-3D model, I2CD freezes the pretrained Hunyuan3D-2 image-conditioned diffusion transformer and shape decoder and trains only a lightweight cross-attention head (38M parameters, under ten GPU-hours) whose learned "convex-slot" tokens emit the halfplane parameters of $K$ convex polytopes. The output is compact, convex by construction, and loads into physics engines without any post-processing, in ${\sim}0.5$s per image. On $227$ held-out OmniObject3D and Google Scanned Objects instances, I2CD attains the highest volumetric IoU among eight reconstruct-then-decompose pipelines while running $6$-$37\times$ faster end-to-end. In a cross-simulator study in MuJoCo, PyBullet, Genesis, and Isaac Sim, every engine uses I2CD geometry as delivered, whereas raw generated meshes "load" everywhere but are silently replaced by a different collision shape in most cases or need seconds to minutes of per-object preprocessing. On a physical xArm7, I2CD produces planner-ready geometry for a $20$-object cluttered scene in $11$s versus $328$s for the strongest baseline, at comparable pick-and-place execution success ($85$ vs. $90$ of $100$ trials).
### Title:
          Certified Mechanistic Edits: Behavioral Guarantees for Skill Removal and Preservation
 - **Authors:** Md Sazid Uddin, Md. Khairul Alam Mazumder, M. F. Mridha
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mechanistic edits (ablations, weight edits, activation steering) are the standard tools for unlearning a harmful capability from a neural network while preserving useful ones. Current approaches validate their effects only by testing, which can never cover an entire continuous region of inputs. Prior work at the interpretability-verification boundary certifies descriptions of a model: what a circuit computes, or whether it faithfully explains the whole. We instead certify the behavioral effect of an edit: that disabling a circuit removes one skill and provably preserves another, for every input in a region; a feature non-interference guarantee in the information-flow-security sense. We demonstrate such certified edits from toy ReLU networks up to a standard softmax + LayerNorm transformer, proving removal and preservation over continuous embedding-space regions and reaching roughly 9x the input-perturbation dimension an exact solver can handle by switching to sound bound propagation. Furthermore, we prove that no finite deterministic black-box test can certify removal, exhibiting an edit that passes exhaustive testing yet provably fails on a survivor pocket that can be made arbitrarily small. Guarantees hold on small, standard-architecture networks and, like any removal claim, presuppose that the target skill admits a decidable specification, a property which real-world harms may not have.
### Title:
          XGenAct: Geometry-Enhanced World Action Models through Cross-Task Generation
 - **Authors:** Tingting Du, Ziyao Wang, Guoheng Sun, Ang Li
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World action models (WAMs) have advanced robot control by predicting how observations and actions evolve over time. Despite this progress, RGB and action based future prediction does not explicitly address the spatial understanding needed for robot manipulation. Existing efforts often add a limited set of spatial prediction tasks through specialized heads or branches, leaving both the range of spatial supervision and the model architecture fragmented. We introduce XGenAct, a world action model that represents RGB observations, robot actions, metric depth, surface normals, and functional role segmentation as RGB videos through deterministic codecs. By sampling perception and action tasks during training, XGenAct uses one video diffusion transformer and one objective to learn temporal prediction across these spaces without modality specific learned heads. On held out RLBench tasks, structured perception training improves average closed loop success over RGB only training, and XGenAct achieves 52% success in the five task external comparison, versus 26% for the strongest evaluated baselines. It also predicts future depth and segmentation more accurately than the evaluated pipelines that generate RGB first and then apply a frozen perception expert.
### Title:
          Learning to Assess Heartbeat Observability for mmWave Heart-Rate Sensing
 - **Authors:** Yuxuan Hu, Shilin Shan, Jianfei Yang, Feng Xu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Contactless heart-rate sensing with millimeter-wave (mmWave) radar requires assessing whether individual measurements support reliable estimation. We study learning to assess heartbeat observability, defined as the readability of the heartbeat component in an acquired phase spectrum, for selective heart-rate estimation. Coherent superposition of scatterer returns can suppress this component even under similar macroscopic observation geometry, motivating assessment directly from acquired measurements. To obtain training supervision across different observability conditions, we develop a controllable multi-scatterer frequency-modulated continuous-wave (FMCW) simulator. Agreement between the dominant heartbeat-band peak and the known heart rate provides an automatic observability label for each simulated measurement. We propose HEAR (Heartbeat Estimation with Assessed Reliability), a compact dual-task Transformer that jointly predicts an observability score and heart rate. Its input combines spectral magnitudes with frequencies relative to the respiration fundamental, providing context for respiratory harmonics. Trained solely on simulated observations, HEAR transfers zero-shot to two public real-world datasets collected at 60 and 120 GHz from 134 subjects. The same learned score supports selective prediction with both HEAR's own heart-rate head and multiple existing estimators. On the 120 GHz dataset, score-based selection reduces the HR head's mean absolute error from 17.9 BPM at full coverage to 1.6 BPM at 50% coverage. The complete pipeline achieves an end-to-end processing latency of 50.8 ms on an edge device. Project page: this https URL.
### Title:
          Rethinking What to Cache in Few-Step Diffusion Transformers: Solver-Aware Target Selection
 - **Authors:** Shuo Yang, Lihao Fang, Yi Zhang, Haixiang Wang, Xincheng Ye, Shufan Chen, Jipeng Guo, Youqing Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformers (DiTs) can generate high-quality images and videos, but generating each sample requires multiple costly DiT forward passes. Two common ways to accelerate DiT sampling are step distillation, which reduces the number of sampling steps, and caching, which skips some DiT evaluations by reusing a tensor computed at an earlier step. Most caching methods decide in advance which tensor to reuse. After distillation, adjacent sampling steps are farther apart. Reusing a tensor across this larger gap introduces more error, so choosing what to cache becomes especially important. We therefore introduce AutoTarget, a method that chooses the cached tensor for a given model, solver, and reuse schedule. AutoTarget uses a small set of runs without cache reuse to measure the error caused by reusing each candidate tensor, then selects the candidate with the lowest error. We also analyze how an error at one reuse step affects the final sample. For Euler sampling, we identify cache targets that produce the same trajectory and show why a stored solver update may not. Experiments on distilled image and video DiTs show that the best cache target changes with the model, image resolution, and solver. AutoTarget reduces DiT evaluations and retained cache storage. Generation quality remains close to the corresponding uncached run. On the tested PixArt-LCM and FLUX.1-schnell settings, its calibration ranking matches the ranking from held-out cached runs. To help others reproduce the method, we provide its core implementation on GitHub at this https URL.
### Title:
          Decoding the Functional Roles of Register and High-Norm Patch Tokens in Vision Transformers
 - **Authors:** Neel Varma, Andrew Rufail, Dipika Khullar, Vasu Sharma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-supervised Vision Transformers (ViTs), such as DINOv2, learn rich visual representations, but the functions of their internal tokens remain poorly understood. Recent architectures introduce dedicated register tokens to reduce high-norm out- lier patch tokens that emerge in background re- gions, yet the semantic and functional roles of both token types have not been fully established. In this paper, we analyze these roles by training sparse autoencoders (SAEs) on register-token and outlier-token activations in DINOv2. Using an automated interpretability pipeline, UMAP clus- tering, and CLIP-space cross-checks, we find that register-token features are more strongly associ- ated with high-level semantic concepts. Outlier- token features, by contrast, are more often associ- ated with lower-level structural, background, and texture-dominant patterns. Causal ablations fur- ther reveal a substantial functional asymmetry: disrupting top-activating register-derived features produces a 48.17% drop in representation cosine similarity, whereas disrupting outlier-derived fea- tures produces only a 0.31% drop. Together, our results provide evidence for token specialization in self-supervised ViTs.
### Title:
          Less Decoder is More Encoder: Geometric Representation Learning from Novel View Synthesis
 - **Authors:** Keerthi Kaashyap, Dennis Anthony, Akshay Krishnan, Nhi Ngoc Nguyen, Jeremy Collins, James Hays, Shreyas Kousik, Animesh Garg
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper examines the role of Novel View Synthesis (NVS) in geometric representation learning. In principle, NVS should reason about 3D scene structure, thereby enabling transferable multi-view geometric representations. Yet, existing encoder-based NVS methods yield poor representations. This is not because of a lack of supervisory signal, but rather due to inconspicuous architectural choices: \textit{spatially expressive decoders} that dilute representational capabilities of the scene encoder, and \textit{low-level pixel-space targets} that hinder feature learning. We present SNAP, a self-supervised encoder-decoder transformer that addresses both through a pose-conditioned local decoder and a latent-space reconstruction objective. SNAP is task agnostic, and we show that it is competitive with special-purpose geometry-supervised methods. SNAP also performs competitively against self-supervised representations across five tasks: visual localization, pose estimation, point correspondence, depth estimation, and robot manipulation. Remarkably, SNAP's patch features exhibit emergent viewpoint invariance that approaches heavily supervised models despite lower compute and data budgets. Under camera shifts where standard 2D representations collapse, SNAP degrades more gracefully, revealing that restricting decoder expressivity actively prevents the suppression of transferable geometric structure. this https URL
## Keyword: autonomous driving
### Title:
          LLM-Based Semantic Modeling and Cooperative Evolutionary Fuzzing for Traffic Violation Scenario Generation
 - **Authors:** Yangyang Liu, Xinyu Li, Yan Xiao, Miao Zhang, Pengcheng Zhang
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ensuring the safety of autonomous driving systems (ADS) in a cost-effective and efficient manner remains a critical challenge. Existing law-guided scenario generation approaches are typically limited to a narrow subset of legal rules, resulting in insufficient scenario diversity, and search-based methods often struggle with large and sparse search spaces. To address these limitations, we propose SLaFE (Semantic Law Modeling and Fuzzing based on Cooperative Evolution), a novel traffic violation scenario generation framework designed to systematically evaluate the safety of ADS. SLaFE harnesses the reasoning capabilities of large language models (LLMs) to convert traffic laws into structured scenario constraints. These scenarios are then optimized via a cooperative evolutionary fuzzing algorithm that explores the parameter space to identify boundary cases likely to trigger abnormal ADS behaviors. We evaluate SLaFE on the Apollo platform within the LGSVL simulator using ten real-world traffic regulations. Experimental results show that SLaFE successfully triggered all 10 types of traffic law violations (10/10), outperforming the best existing method, VioHawk (9/10), while others detected no more than 3. Moreover, SLaFE achieved an average triggering time of 5.1 minutes per law type, significantly faster than VioHawk (9.0 minutes) and other baselines. These results highlight SLaFE's effectiveness in discovering diverse and critical law-violating scenarios for ADS testing.
### Title:
          From Fragments to Global Maps: Learning Vectorized Map Aggregation with Large Language Models
 - **Authors:** Ziwei Li, Yi-Tang Chen, Xiaoqi Wang, Wenbin He, Han-Wei Shen, Liu Ren
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large-scale vectorized HD maps provide structured road information that is essential for perception, localization, and planning in autonomous driving. Constructing such maps requires aggregating noisy, fragmented, and overlapping local predictions collected along a vehicle trajectory into a coherent global map. Existing aggregation methods typically rely on hand-crafted rules for fragment association and refinement. However, a fixed set of thresholds cannot effectively handle variations in road structures and prediction errors, often requiring detector-specific tuning or manual adjustment. To address this limitation, we propose MapMergeLLM, a data-driven framework that formulates vectorized map aggregation as conditional sequence generation with a large language model. Given serialized local vectorized maps, our model directly predicts the aggregated global map polylines. To reduce dependence on any particular upstream detector, we train the model on synthetic local maps generated from clean vector maps using corruptions that simulate representative prediction errors. We further introduce a coordinate tokenizer with geometry-aware pretraining to precisely represent map coordinates. In addition, we propose a line-level association loss that explicitly supervises correspondences between local observations of the same map element. Experiments on Argoverse2 and nuScenes using multiple recent upstream detectors demonstrate that MapMergeLLM substantially outperforms heuristic and optimization-based aggregation baselines without detector-specific retraining.
### Title:
          Localized Conformal Safety Monitoring with Vision-Language Models for Autonomous Driving
 - **Authors:** Luís Marques, Rong Fang, Disha Kamale, Dmitry Berenson
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monitoring planned driving trajectories requires accurately estimating the collision likelihood with actors whose motion is itself impacted by the ego motion. Existing classical approaches are often limited by the quality of their forecasting model. Vision-language models (VLMs) have shown promise in reasoning about the consequences of high-level actions, yet their approximate predictions are unsuitable for safety-critical applications such as autonomous driving. Conformal prediction (CP) has emerged as a data-driven framework for quantifying the uncertainty of black-box model predictions. We propose Split Label-Localized Conformal Prediction (SLLCP), a post-hoc calibration layer over frozen VLMs that transforms their unreliable predictions into probabilistically calibrated safety prediction sets. We consider how the ability to estimate safety can depend on the observed driving scene and introduce a localized procedure that upweights relevant past experience when calculating uncertainty thresholds. We provide label-conditional finite-sample distribution-free coverage under exchangeability. Evaluated over 15k CARLA trajectories from unseen scenarios, SLLCP correctly flags 89.6% of collision-causing trajectories with a Qwen backbone and 88.4% with a Cosmos backbone, while the base VLMs only flagged 4.6% and 39.1% of the collision-causing trajectories, respectively. These results indicate that local, label-conditional calibration can reduce missed unsafe trajectories.
