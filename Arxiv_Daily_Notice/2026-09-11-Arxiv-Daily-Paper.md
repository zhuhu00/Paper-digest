# Showing new listings for Friday, 11 September 2026
## Keyword: SLAM
### Title:
          Visual-SLAM for the detection of hidden tomatoes in greenhouses by Hierarchical Localization and GLOMAPfor robotized harvesting
 - **Authors:** Fernando Cañadas-Aránega, José C. Moreno, José L. Blanco-Claraco, Francisco Rodríguez
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Advanced crop monitoring inside greenhouses is becoming one of the primary objectives of research centers. High-performance sensors, such as LiDAR or stereo cameras, have traditionally been employed for this purpose, though these often have a high cost. This work proposes a Visual-SLAM system using a monocular camera, which is significantly more cost-effective and specifically tailored for agricultural applications, such as mapping tomato crops in a greenhouse. Tests were carried out on a real tomato bunch, located in the Agroconnect experimental greenhouse. A ROS 2 Humble node was developed to run on the robot in order to capture images of these crops, which were then stored for offline processing. To generate a 3D mapped model for the crop in the greenhouse, the GLOMAP mapper, based on Structure-From-Motion, was integrated with the Hierarchical Localization toolbox. This initial mapping is a foundation for future, more advanced algorithms to analyze growth patterns, and optimize agricultural management. The system leverages a hierarchical localization paradigm based on a coarse-to-fine strategy: it first performs global retrieval to generate location hypotheses, then combines local features within the identified candidate regions. The results show a correct identification of the tomato cluster, correctly characterising the tomato that is occluded and inaccessible by classical vision technologies. The reconstructed 3D model was further validated against manual ground-truth measurements of fruit size, centroid position, and orientation, confirming the geometric accuracy of the proposed low-cost monocular pipeline.
## Keyword: odometry
There is no result 
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Toward Interpretable Multimodal Fusion: Heat Conduction Modeling for Hyperspectral and LiDAR Joint Classification
 - **Authors:** Kan Wei, Jiahui Cui, Jing Yao, Xinyu Zhao, Lei Wang, Pedram Ghamisi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The fusion of hyperspectral (HS) and Light Detection and Ranging (LiDAR) data plays a crucial role in enhancing land-cover classification by jointly exploiting spectral, spatial, and structural cues. However, existing multimodal fusion methods still struggle to model long-range dependencies and complex anisotropic interactions while maintaining computational efficiency. This paper introduces M2Heat, a physics-inspired framework that investigates multimodal fusion through the lens of heat conduction. At its core, a physics-driven visual heat conduction module (vHeat) and enhanced Frequency Value Embeddings (FVEs) simulate anisotropic information flow, enabling the capture of global dependencies with sub-quadratic complexity and physical interpretability. This mechanism, combined with a hybrid spatial-frequency fusion strategy named Cross-Frequency Fusion (CFF) module, produces highly discriminative and robust feature representations. M2Heat achieves competitive overall performance on three benchmarks, i.e., Trento, Houston2013, and Augsburg, while providing an interpretable heat-conduction-guided perspective for multimodal feature fusion. These results indicate the potential of heat-conduction-guided neural operators for efficient and interpretable RS multimodal fusion. The source code is publicly available at https: /github.com/Weikan0425/M2Heat_HSI_LiDAR.
### Title:
          Lightweight LiDAR-Based Cone Detection Framework Using Random Forest for Formula Student Driverless
 - **Authors:** Márk Mező-Kerekes, Péter Praksz, Chang Liu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable, low-latency perception is crucial for Formula Student Driverless vehicles, yet many existing pipelines rely on deep learning and multi-sensor fusion, often requiring GPU acceleration. This paper presents a lightweight LiDAR-only perception pipeline tailored for CPU execution, combining ground removal, IMU-based motion compensation, DBSCAN clustering, and geometric feature-based Random Forest classification. Feature importance analysis reduced the model input from 12 to 7 features while preserving performance. Evaluated on 2,371 labeled clusters collected from real FSD events, the pipeline achieves an F1-score of 98.33% and an end-to-end runtime of 3.13 ms on CPU-only hardware. The released dataset, labeling tool, and trained models provide a practical and reproducible baseline for other resource-constrained autonomous racing teams.
### Title:
          MMGait: Benchmarking and Unifying Gait Recognition across Heterogeneous Modalities
 - **Authors:** Saihui Hou, Chenye Wang, Qingyuan Cai, Aoqi Li, Yongzhen Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Gait recognition is commonly studied using RGB videos or their derived silhouettes and poses. Yet human walking produces heterogeneous photometric, geometric, and motion cues that cannot be systematically examined with RGB-centered benchmarks. We present MMGait, a large-scale multi-sensor benchmark that brings visible, infrared, depth, LiDAR, and radar observations into sequence-level correspondence. It provides diverse modalities spanning appearance, contours, geometry, motion, and body structure. Under a shared impostor-augmented protocol, we evaluate single-modal recognition, cross-modal recognition via directed retrieval, and multi-modal recognition using task-specific experts. Across settings, modality rankings vary with probe conditions, cross-modal alignment remains difficult, and fusion often provides complementary gains. This analysis exposes a scalability problem: individual modalities, modality pairs, and fusion configurations are typically handled by separately trained experts. We formulate Omni-Modal Gait Recognition, which unifies single-modal, cross-modal, and multi-modal recognition within a shared identity space. OmniGait++ uses modality-specific front ends followed by a shared identity encoder to preserve modality-dependent cues while learning comparable identity descriptors. An anchor-guided fusion module aggregates modality subsets of varying size without frame-level synchronization. A jointly trained checkpoint covers all three recognition settings and accommodates modality subsets of different compositions and cardinalities. Experiments show OmniGait++ remains competitive with task-specific experts in many shared settings and extends to higher-cardinality fusion unavailable to fixed-pair models. The results establish MMGait as a common testbed for heterogeneous gait sensing and demonstrate the feasibility of unified recognition under varying modality availability.
### Title:
          MC-DeTra: Motion-Consistent Joint Object Detection and Socially-Aware Trajectory Forecasting in Bird's-Eye-View Images
 - **Authors:** Vladislav Diuzhev, Dmitry Yudin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unified models for object detection and trajectory forecasting aim to merge perception and prediction for autonomous driving, refining actor trajectories directly over shared bird's-eye-view (BEV) images rasterized from LiDAR and high-definition maps. Their accuracy on dynamic, moving actors, however, remains the hardest part of the task, and the strongest such model, DeTra, has no public implementation. We contribute an openly released DeTra reimplementation with documented approximations, and on top of it MC-DeTra: a family of motion-consistency mechanisms that add supervision through two annotation-derived auxiliary signals -- each actor's observed past motion and the occupancy of the surrounding traffic that forms its social context -- and one inter-output consistency constraint that aligns an actor's predicted heading with its predicted direction of motion. Every proposed loss is train-only and inference-safe: it shapes the shared BEV representation during training and is removed at test time, adding no inference latency. On the Waymo Open Dataset, evaluated under a strict, detection-conditioned forecasting protocol, MC-DeTra improves dynamic, socially-situated trajectory forecasting while preserving or improving detection accuracy; a gradient-based loss-calibration analysis exposes how the auxiliary objectives compete at the shared backbone, and our ablation identifies which signals contribute most. We release code, configurations, and evaluation tooling at this https URL.
### Title:
          Visual-SLAM for the detection of hidden tomatoes in greenhouses by Hierarchical Localization and GLOMAPfor robotized harvesting
 - **Authors:** Fernando Cañadas-Aránega, José C. Moreno, José L. Blanco-Claraco, Francisco Rodríguez
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Advanced crop monitoring inside greenhouses is becoming one of the primary objectives of research centers. High-performance sensors, such as LiDAR or stereo cameras, have traditionally been employed for this purpose, though these often have a high cost. This work proposes a Visual-SLAM system using a monocular camera, which is significantly more cost-effective and specifically tailored for agricultural applications, such as mapping tomato crops in a greenhouse. Tests were carried out on a real tomato bunch, located in the Agroconnect experimental greenhouse. A ROS 2 Humble node was developed to run on the robot in order to capture images of these crops, which were then stored for offline processing. To generate a 3D mapped model for the crop in the greenhouse, the GLOMAP mapper, based on Structure-From-Motion, was integrated with the Hierarchical Localization toolbox. This initial mapping is a foundation for future, more advanced algorithms to analyze growth patterns, and optimize agricultural management. The system leverages a hierarchical localization paradigm based on a coarse-to-fine strategy: it first performs global retrieval to generate location hypotheses, then combines local features within the identified candidate regions. The results show a correct identification of the tomato cluster, correctly characterising the tomato that is occluded and inaccessible by classical vision technologies. The reconstructed 3D model was further validated against manual ground-truth measurements of fruit size, centroid position, and orientation, confirming the geometric accuracy of the proposed low-cost monocular pipeline.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          3D Point Splatting for mmWave Radar Novel View Synthesis
 - **Authors:** Adnan Armouti, Yixuan Gao, Rajalakshmi Nandakumar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR); Machine Learning (cs.LG); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Solving novel view synthesis (NVS) for millimeter-wave (mmWave) radar requires a renderer that is physically faithful, complex-valued, and multi-viewpoint-tractable. No prior method achieves these three properties simultaneously. Differentiable Monte Carlo (MC) ray tracers implement the radar forward model directly with explicit material modeling and complex outputs, but do not scale to the multi-view optimization NVS demands. Optical-NVS ports of NeRF, hash grids, and 3D Gaussians train fast but discard phase and replace explicit material modeling with opaque learned features, restricting them to power-only range-azimuth (RA) magnitudes. We propose 3D Point Splatting (3DPS), the first differentiable point renderer for radar, derived directly from the standard solid-angle form of the radar equation. Each oriented 3D point carries an ITU-R P.2040 material model, evaluated in closed form, with the resulting complex phasor splatted into range bins through a precomputed point spread function (PSF). The complex-valued output makes the renderer product-agnostic. The same optimized scene yields analog-to-digital converter (ADC), complex range profile (CRP), and RA outputs through standard fast Fourier transform (FFT) pipelines without retraining for each format. On six outdoor ColoRadar scenes, 3DPS reaches 0.587 mean Pearson correlation on held-out RA images. This is between 1.7x and 5.2x the three optical-NVS baselines (RadarSplat, Radar Fields, DART). Training takes approximately 3 minutes per scene on a single RTX 4090.
## Keyword: mapping
### Title:
          Two-Parameter Flow Map Learning for Continuous-Time Diffeomorphic Image Registration
 - **Authors:** Mohammadjavad Matinkia, Nilanjan Ray
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffeomorphic image registration is central to medical image analysis, enabling anatomically consistent alignment across subjects. Most learning-based diffeomorphic methods model autonomous ODEs(ordinary differential equations) by parameterizing a stationary velocity field and recovering deformations via scaling-and-squaring. While non-autonomous ODEs with time-dependent velocities increase expressiveness, existing approaches rely on numerical integration to implicitly enforce flow structure that entangles model expressiveness with discretization accuracy. We propose a framework to directly learn the continuous-time solution of a non-autonomous ODE formulated as a two-parameterflow map. By enforcing cocycle consistency, a fundamental structural property of time-varying flows, we learn the flow maps without time discretization and velocity integration during training. The framework recovers diffeomorphic mappings at inference using a small number of compositions. Our proposed framework seamlessly incorporates standard registration backbones and improves alignment accuracy consistently across nine datasets while preserving diffeomorphic structure. Notably, the proposed method achieves an average Dice improvement of 2.1% on brain MRI benchmarks, a 12% TRE reduction on lung CT, and a 2.6% Dice gain on cardiac MRI and ultrasound datasets.
### Title:
          AspisAI: A Canonical, Machine-Interpretable Governance Framework for Automated Multi-Standard Compliance Monitoring
 - **Authors:** Tsafac Nkombong Regine Cyrille, Hasan Dag, Reiner Creutzburg, Knut Haufe
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Computers and Society (cs.CY); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Organisations operating in regulated and critical-infrastructure sectors must satisfy multiple, heterogeneous cybersecurity and privacy instruments simultaneously, including but not limited to ISO/IEC~27001, the NIST Cybersecurity Framework~2.0, Cyber Essentials, and the GDPR. In practice, these obligations are managed through manual mappings, spreadsheet-based tracking, and periodic audits that are costly to maintain, inconsistent across standards, and weak in traceability. This paper presents \emph{AspisAI}, a bounded, standard-agnostic governance framework that translates selected requirements from several frameworks into a canonical, machine-interpretable control model, and evaluates submitted evidence against condition-based decision rules to produce explainable, traceable compliance determinations. Within a bounded scope of 26 representative requirements, the framework is evaluated in a controlled simulation against five governance-oriented criteria and, critically, against two external reference points that mitigate the circularity of single-author evaluation: its cross-standard mappings are validated against NIST's own published informative references, with 57\,\% exact agreement and divergences confined to same-family controls, and the framework is applied to real third-party evidence from the OpenSSF Scorecard, surfacing genuine governance gaps in a live open-source project. The controlled results, comprising full requirement encoding, 88.5\,\% mapping coverage, complete traceability, and correct detection of all introduced gaps, establish functional correctness, while the external validation provides evidence of applicability beyond the simulation. The contribution is therefore a demonstration that a canonical, provenance-preserving governance model can render multi-standard compliance both automatable and auditable.
### Title:
          Learned Continuous Synthesis of Quadratic Difference Tone Spectra
 - **Authors:** Esteban Gutiérrez, Behzad Haki, Christopher Haworth, Xavier Serra, Rodrigo Cádiz
 - **Subjects:** Subjects:
Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Quadratic difference tones (QDTs) are a species of auditory distortion product in which a "phantom" pure tone, absent from the acoustic signal, is clearly audible to listeners. Exploiting this phenomenon, one can synthesize harmonically rich tones for musical purposes, a technique called Quadratic Difference Tone Spectrum (QDTS) synthesis. Previous works have introduced numerical methods to synthesize QDTS based on the distortion function, which links a target QDTS and an overtone-structured carrier signal. While accurate, these methods were stochastic and discontinuous, making them difficult to control for musical purposes and effectively limiting them to stationary signals. This paper proposes a neural network-based approach that learns an approximate inverse of the distortion mapping in an autoencoder-like configuration, producing a continuous approximation that addresses prior limitations. Experimental results show that, although slightly less numerically precise, the method is sufficient for perceptual and musical applications. We also implement a real-time version in Max and evaluate its performance. Various sound examples demonstrate its expressive and musical potential. The source code, audio examples, tutorials, and software accompanying this work are available at this https URL
### Title:
          A Mathematical Theory of Pragmatic Information
 - **Authors:** Kai Niu, Ping Zhang
 - **Subjects:** Subjects:
Information Theory (cs.IT); Artificial Intelligence (cs.AI); Robotics (cs.RO); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose a pragmatic information theory unifying communication, control, and decision-making. Its core is the isoteleia mapping, formalizing equifinality: distinct semantic paths leading to the same optimal action are pragmatically equivalent. This induces a three-tier hierarchy of syntactic, semantic, and pragmatic information, each abstraction discarding task-irrelevant distinctions. We develop pragmatic entropy, up/down mutual information, channel capacity, and rate-distortion, and prove three coding theorems generalizing Shannon's classical results. We introduce pragmatic value (VoI) and cost (CoI) of information as decision-theoretic duals to rate-distortion and capacity, respectively, and formulate a Lagrangian dual framework for cross-layer optimization. The pragmatic efficiency bound $\mathcal{E}_p(\lambda)=\sup_R[\Phi_p(R)-\lambda\,\mathrm{CoI}_p(R)]$ quantifies the maximum net utility any resource-constrained intelligent system can extract, thereby establishing a fundamental behavioral capacity limit---generalizing Shannon's symbol-level capacity to goal-directed action. Extensions to continuous messages yield closed-form Gaussian expressions, while dynamic settings are addressed via a Bellman equation for sequential decision-making. This framework provides a rigorous foundation for task-oriented communication, networked control, autonomous systems, and embodied AI, shifting focus from symbol fidelity to the effectiveness of information in guiding actions, and offers a unified mathematical language for next-generation intelligent systems.
### Title:
          A Model-Centric DevOps Architecture for DEVS-Based Digital Twin Simulation Services
 - **Authors:** Arnis Lektauers, Gusts Linkevičs, Guntis Mosāns, Arina Fokina, Rasa Gulbe
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Computational Engineering, Finance, and Science (cs.CE); Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Digital twin simulation models are evolved and redeployed like software, yet DEVS-based engines offer a sound formal basis with little support for versioning, automated validation, or continuous delivery in cloud-native environments, leaving model lifecycle management ad hoc in most deployments. This paper proposes a model-centric DevOps architecture for deploying DEVS-based digital twin simulations as managed services. Simulation models are treated as first-class DevOps artefacts defined in a declarative YAML language with a formal mapping to multiPDEVS, supporting structural and semantic validation in a CI/CD pipeline that produces immutable versioned artefacts, so that reverting to an earlier validated version reduces to pinning its identifier. The platform is decomposed into containerised microservices on Kubernetes, with engine adaptations for state externalisation and lifecycle control. An initial case study on the Riga Route 22 public-transit corridor, the first instantiation of a planned city-wide multi-modal transport digital twin for Riga, Latvia, exercises the full lifecycle and reports single-container engine throughput for a scenario with roughly 47,870 DEVS atomic components; pipeline-level catch statistics and cluster-level concurrent multi-scenario execution are the subject of companion empirical studies.
### Title:
          OmniTable: A Unified Wide-Table System for Petabyte-Scale LLM Data Curation and Exploration
 - **Authors:** Yuzhuo Fu, Xiangchun Wang, Chao Huang, Liyi Wang, Binwei Zeng, Yuhan Wang, Taotao Nie, Dongke Hu, Wang Hong, Jiayi Wang, Wenwen Cui, Zhuyan Zhou, Yushun Guo, Yuhan Xing, Jiaxin Lian, Peng Lin, Qing Cui, Wenhui Shi, Jun Zhou
 - **Subjects:** Subjects:
Databases (cs.DB)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Data curation is a critical bottleneck in industrial-grade LLM development, where petabyte-scale unstructured corpora are scattered across hundreds of physical tables, feature engineering relies on manual, table-centric pipeline orchestration, and data lineage is largely absent. We present OmniTable as an architecture blueprint for a unified wide-table layer built on Logical Unification, Physical Separation, targeting petabyte-scale LLM data curation and exploration. OmniTable makes four contributions: (1) a unified wide-table abstraction that consolidates multi-source heterogeneous data and thousands of derived features under a single logical schema via logical-physical mapping; (2) declarative feature lifecycle management that automates dependency resolution, execution planning, operator fusion, and lineage tracking, replacing manual pipeline orchestration with a "declare-and-execute" paradigm; (3) an adaptive execution engine with autonomous governance that achieves stable PB-scale feature backfill through heterogeneous compute routing (CPU/GPU), adaptive tuning, UDF-level fault tolerance, and automated storage layout optimization; and (4) hybrid-accelerated data exploration combining a global ID index, transparent OLAP offloading, and background materialized views to deliver second-level point lookups and filtered exports exceeding 20 TB/hour. In production, OmniTable manages over 35 PB of training data across web, code, PDF, and SFT domains, reducing the human-in-the-loop curation cycle from approximately 14 days to approximately 2.5 days (5.6x over the pre-OmniTable production workflow), with consistent feature versioning, auditable lineage, and minimal manual intervention.
### Title:
          Harness Robotic OS: A Unified Embodied-Agent Runtime for Closed-Loop Quadruped Inspection
 - **Authors:** Yaoyuan Yan, Zhiyou Heng, Haoxiang Jie, Gang Liu, Hongjie Yan, Wei Zhou
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous property inspection requires more than robust robot navigation: a deployable system must connect heterogeneous sensing, reusable autonomy capabilities, multimodal scene understanding, human interaction, and enterprise response within a traceable operational loop. Existing quadruped inspection systems commonly integrate these functions through task-specific interfaces, making contextual coordination, knowledge reuse, and controlled adaptation difficult. This paper presents \textit{Harness Robotic OS} (HROS), a unified embodied-agent runtime, and Argos, its realization for residential-community inspection. HROS organizes the system into robot runtime, embodied autonomy skills, cognitive agent runtime, and interaction and operations planes. A shared context connects physical state with agent reasoning; streaming ASR/TTS supports voice-based mission interaction; hierarchical working, episodic, and semantic memory preserves operational knowledge; and a safety-gated self-evolution loop converts execution traces into versioned candidate updates without permitting unconstrained online modification. The Argos prototype integrates a Vbot quadruped, Fast-LIO2 localization and mapping, Hobot-Stereo depth perception, PCT-Planner global planning, EGO-Planner local motion generation, and OpenClaw-orchestrated Qwen3-VL inspection analysis. Experiments in a residential property environment achieved 100\% waypoint reachability, outdoor localization error below 10~cm, local obstacle-response latency below 200~ms, representative hazard-detection rates of 85--95\%, and 99\% success in alarm delivery and structured-report generation. These results validate the deployed navigation and inspection closed loop, while HROS provides an extensible software foundation for memory-augmented, voice-aware, and continuously improvable embodied inspection agents.
### Title:
          MUtE: A Dual Framework for Concept Erasure and Counterfactual Interventions
 - **Authors:** Antoine Saillenfest
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Erasing concept-specific information from representations has been proven useful for mitigating bias or interpreting model decisions. The joint objective is to transform the original representations such that the target concept becomes unpredictable, while maximally preserving concept-unrelated information. In this work, we revisit the optimal bounds of concept erasure to derive a novel class of erasure functions that naturally induce a deterministic, dual counterfactual mapping. Bridging the gap between theoretical optimality and practical representation learning, we design an implementation that imposes a translational bias on counterfactual trajectories - a constraint that aligns with how many concepts geometrically manifest in modern language models. Our framework enables seamless navigation between concept erasure and counterfactual generation. We empirically demonstrate its efficacy in improving downstream algorithmic fairness and generating counterfactual texts.
### Title:
          A global mobile network coverage raster product at 1km resolution, 1999--2030
 - **Authors:** Till Koebe, Theophilus Aidoo, Ali El Chami, Ali Kanso, Akansh Maurya, Purushottam Sharma, Ingmar Weber, Ridhi Kashyap
 - **Subjects:** Subjects:
Computers and Society (cs.CY); Social and Information Networks (cs.SI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Where a mobile signal is available shapes who can work, learn, bank, seek health care and respond to crises in the digital age, yet no globally consistent, sub-national record of mobile network coverage exists. We present such a record: annual 1km maps of the probability of 2G, 3G and 4G coverage for 214 countries and territories for the years 1999 to 2030. The maps are produced by three independent models: a calibrated machine-learning model, a techno-economic simulator of network build-out, and a spatial deep-learning model. The three estimates are then combined, per country and technology and in proportion to their measured accuracy, into a single best estimate with per-pixel 90% uncertainty bands; all four layers are released as part of the dataset. Because mobile roll-out closely follows a country's socio-economic conditions (population distribution, electrification, physical infrastructure), the models are grounded in existing geospatial data and tuned on 2,409 quality-screened operator-reported coverage maps, which are available up to 2020. For 2021--2024 the maps are predicted from recent geospatial data alone; for 2025--2030 they are extrapolated from demographic and infrastructure projections. On countries held out during training, the machine-learning model attains AUC 0.89--0.92. Baseline comparisons and the combined product's external validation are reported in Technical Validation. The dataset supports mapping the global digital divide, linking connectivity to household-survey outcomes, and humanitarian and infrastructure planning.
### Title:
          Modular Kinematic Reduction of Closed-Chain Mechanisms Using Path Assembly and Defect Homotopy
 - **Authors:** Mohammad Dastranj, Jouni Mattila
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Closed kinematic chains complicate modular modeling by coupling active and passive coordinates through nonlinear closure constraints. This paper presents a Path-Assembled Closure Differential Mapping (PACDM) framework for modular closure resolution and kinematic reduction. Each closure element compares two ordered transformation paths with common endpoints, with their mismatch expressed through the logarithm on SE(3) and the corresponding Jacobian assembled from local transformation derivatives. Multi-path modules are constructed from a minimal set of pairwise closure elements, while rank-revealing analysis selects locally independent scalar constraints. A defect homotopy recovers closure-consistent passive coordinates from approximate estimates along a feasible and regular continuation path. At regular configurations, implicit differentiation yields the local active-to-passive differential mapping, which is subsequently used in a predictor-corrector continuation procedure for prescribed motion. The framework is evaluated on a seven-degree-of-freedom heavy-duty manipulator containing two-path and three-path closed-chain modules. Comparison with Simscape Multibody yields trajectory root-mean-square errors below 8.5 x 10^-10 rad, while predictor-corrector continuation is approximately 45.8 times faster than applying defect homotopy at every trajectory sample.
### Title:
          PATTON: Enabling Commodity PIM for Production LLM Serving
 - **Authors:** Hangyeol Kim, Sanghyun Lee, Teokkyu Suh, Joo-Young Kim
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Processing-in-Memory (PIM) is promising for accelerating memory-bound decode attention, but attention acceleration alone is insufficient for production LLM serving, where engines dynamically allocate, populate, share, cache, and reclaim logical KV cache blocks. Supporting this lifecycle on commodity PIM requires efficient physical memory allocation, block-to-address mapping, and command generation. For the Value cache, these requirements create a fundamental conflict among GEMV efficiency, single-token write efficiency, and memory capacity: GEMV-optimized layouts scatter newly generated Value vectors across rows, making writes costly, while finer-grained memory sharing improves capacity utilization but fragments GEMV reductions. We present PATTON, a PIM runtime that integrates production LLM serving engines with commodity PIM. PATTON introduces hierarchical granule allocation: block-sized Key and Value granules map one-to-one to logical token blocks, fixing their physical placements and commands, while coarser granules group blocks for efficient GEMV execution and memory utilization. A Commit Zone stages partial Value blocks for efficient single-token writes before committing them to GEMV-optimized locations. PATTON tracks these placements to generate KV cache writes and QK-transpose/SV commands. Across attention execution and runtime-induced prefill recomputation, PATTON achieves an average 1.95x speedup and 4.83x higher energy efficiency over evaluated baselines, requires no PIM processing-unit modifications, and maintains a KV cache hit rate comparable to the native GPU KV cache in vLLM.
### Title:
          PHAT: PHotonic Accelerator for TFHE
 - **Authors:** Guowei Yang, Farbin Fayza, Beren Aydoğan, Carlos A. Ríos Ocampo, Ayse K. Coskun, Ajay Joshi
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Hardware Architecture (cs.AR); Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fully Homomorphic Encryption (FHE) enables secure computation on encrypted data, making it a promising solution for privacy-preserving applications in the cloud. Among various FHE schemes, FHE over the Torus (TFHE) stands out due to its support for arbitrary operations. However, its high computation and communication overhead, particularly in the Fast Fourier Transform (FFT) operations required during bootstrapping, limits its practicality for real-world applications. Conventional electronic accelerators struggle to achieve sufficient throughput due to the limitations of technology scaling and the memory-wall problem. To address these challenges, we propose PHAT, a PHotonic Accelerator for TFHE leveraging Optically-addressed Phase-Change Memory (OPCM). OPCM-based processing-in-memory systems offer high computation and communication throughput, making them well-suited for accelerating FFT operations in TFHE. However, directly mapping FFT to OPCM presents challenges such as high-precision analog computation and the high latency and energy cost of programming OPCM cells. To overcome these challenges, we introduce a novel electro-photonic accelerator architecture optimized for TFHE, featuring OPCM-based FFT units, a twiddle-stationary dataflow tailored for OPCM, and a scheduling mechanism to maximize the utilization of the FFT units. PHAT delivers $2.14\times$--$5.10\times$ speedup across four real-world TFHE workloads against the state-of-the-art ASIC accelerator. Our approach significantly enhances the performance of TFHE applications, paving the way for practical and efficient homomorphic encryption in cloud computing.
### Title:
          Self-Supervised Cardiac Phase Detection via Single-Parameter Latent Orbits
 - **Authors:** John Bonnici, Matthew Baugh, Aleksandra Kulbaka, Sarah Cechnicka, Bernhard Kainz, Alberto Gomez
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate identification of end-diastole (ED) and end-systole (ES) in echocardiography underpins the quantification of ventricular function, yet manual selection of these key frames is subjective and introduces clinically significant inter-operator variability. Recent self-supervised methods either prescribe strict periodic trajectories or learn an unconstrained low-dimensional motion subspace from reconstruction or registration objectives. The former offers interpretability but imposes restrictive assumptions on temporal progression, whereas the latter leaves cardiac phase implicit and ED/ES must be recovered through post-hoc geometric processing of the learned trajectory. We translate the physiological observation that cardiac phase is a one-dimensional signal into a prior by constraining the latent motion component to a single-parameter latent orbit, i.e., a global linear trajectory in latent space indexed by a bounded scalar phase variable. Mapping this variable through a sinusoidal nonlinearity yields an oscillatory motion signal with consistent temporal ordering, enabling direct identification of ED and ES from the learned phase signal. This inductive bias allows the model to capture an interpretable representation of the cardiac cycle, while maintaining flexibility to capture irregular heartbeats. Trained on EchoNet-Dynamic without annotations, our minimal single-parameter cardiac phase model learns an effective latent orbit, significantly improves upon the previous state of the art in ED localisation and matches it in ES localisation while using a more constrained representation and fewer training epochs. This demonstrates that a principled physiological inductive bias can match or exceed the performance of more complex representations. Code is available at: this https URL
### Title:
          Aerodynamic Prior-Free Coordinated Trajectory Generation and Tracking Control for a Tail-Sitter UAV
 - **Authors:** Erchao Rong, Zihao Liu, Junning Liang, Jianguo Wang, Xiao Jie, Haoran Fu, Ziliang Chen, Ximin Lyu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a coordinated trajectory generation and tracking control framework for a tail-sitter unmanned aerial vehicle (UAV), which does not require aerodynamic priors identified for a specific airframe while addressing the challenge of flight control under highly nonlinear aerodynamics across the full flight envelope. The core innovation lies in employing phase-specific aerodynamic modeling strategies for planning and tracking, tailored to their distinct functional characteristics, without requiring airframe-specific aerodynamic priors. Specifically, the phi-theory model under coordinated flight is employed to derive an analytic differential flatness mapping, and a simplified but locally accurate model is established for predictive control to enable real-time aerodynamic parameter estimation. The proposed framework is evaluated extensively through both simulation and challenging real-world flight tests under mild wind conditions, showing high-precision tracking and adaptability across the tested aerodynamic conditions. To the best of our knowledge, this is the first real-world demonstration of accurate trajectory tracking over tested flight regimes spanning the full envelope of a tail-sitter UAV without relying on aerodynamic identification campaigns. The source code of our framework is available at: this https URL.
### Title:
          SEED-UMI: Sharing the Exoskeleton between human and robot for onE-to-one Dexterous demonstration
 - **Authors:** Tengbo Yu, Jiahao Wu, Daohan Li, Bingxu Chen, Hao Liu, Xiaojian Ma, Hangxin Liu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Imitation learning for dexterous hands is bottlenecked by the difficulty of collecting contact-rich demonstrations that transfer faithfully to the robot. Prior wearable-exoskeleton systems record only on the human side and retarget via open-loop mappings calibrated in free space, which degrade under contact. We present SEED-UMI, a framework in which both the human and the robot wear the same exoskeleton: joint encoders become a physically shared measurement, and wrist cameras mounted to the exoskeleton observe the same outer mechanism during both human data collection and robot policy rollouts. This turns retargeting into paired cross-embodiment supervision and lets policies train directly on raw exoskeleton-centric wrist images, without segmentation or inpainting. On five contact-rich tasks, SEED-UMI achieves 3.0x greater data collection efficiency than exoskeleton-based teleoperation and a 70.0% average rollout success rate.
### Title:
          Visual-SLAM for the detection of hidden tomatoes in greenhouses by Hierarchical Localization and GLOMAPfor robotized harvesting
 - **Authors:** Fernando Cañadas-Aránega, José C. Moreno, José L. Blanco-Claraco, Francisco Rodríguez
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Advanced crop monitoring inside greenhouses is becoming one of the primary objectives of research centers. High-performance sensors, such as LiDAR or stereo cameras, have traditionally been employed for this purpose, though these often have a high cost. This work proposes a Visual-SLAM system using a monocular camera, which is significantly more cost-effective and specifically tailored for agricultural applications, such as mapping tomato crops in a greenhouse. Tests were carried out on a real tomato bunch, located in the Agroconnect experimental greenhouse. A ROS 2 Humble node was developed to run on the robot in order to capture images of these crops, which were then stored for offline processing. To generate a 3D mapped model for the crop in the greenhouse, the GLOMAP mapper, based on Structure-From-Motion, was integrated with the Hierarchical Localization toolbox. This initial mapping is a foundation for future, more advanced algorithms to analyze growth patterns, and optimize agricultural management. The system leverages a hierarchical localization paradigm based on a coarse-to-fine strategy: it first performs global retrieval to generate location hypotheses, then combines local features within the identified candidate regions. The results show a correct identification of the tomato cluster, correctly characterising the tomato that is occluded and inaccessible by classical vision technologies. The reconstructed 3D model was further validated against manual ground-truth measurements of fruit size, centroid position, and orientation, confirming the geometric accuracy of the proposed low-cost monocular pipeline.
### Title:
          AccelForge: Comprehensive Modeling and Co-Design Framework for AI Accelerators
 - **Authors:** Tanner Andrulis, Michael Gilbert, Vivienne Sze, Joel S. Emer
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tensor algebra workloads, of which deep neural networks are prominent examples, are energy-intensive workloads in modern datacenter and edge deployments, making accelerators necessary to achieve energy efficiency and high throughput. To quickly evaluate and iterate on accelerator designs, we need an accelerator modeling framework that captures salient attributes of devices, circuits, architectures, workloads, as well as optimizing the mapping of the workload onto the hardware. In this paper, we introduce AccelForge, which improves upon existing accelerator modeling frameworks in capabilities, speed, and ease-of-use. AccelForge unifies and multiple works into one framework, and it includes (1) composable user-defined and user-modifiable models of devices, circuits, and architectures, (2) fast mappers that enable accurate evaluation in orders of magnitude less (computer and human) time, and (3) easy-to-use and easy-to-extend, yet still high performance, Python implementations of both the model and mapper to enable rapid research and extension to novel optimizations.
### Title:
          Artificial Id: Drive and Persistent Alignment in Agentic AI
 - **Authors:** Yakov Pyotr Shkolnikov
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Agentic AI is moving from bounded task execution toward systems that retain consequential state, continue operating and adapt across task boundaries. That shift creates a control problem that current harnesses largely solve by hand: objectives, retries, verification, stopping rules and other behavioral transitions are specified externally. We propose an artificial id, an adaptive internal drive for determining whether behavior should continue, stop or change. In a minimal virtual Petri-dish experiment, a controller too small to perform general-purpose reasoning and receiving no task-specific behavioral objective develops useful control through differential persistence. The same mechanism selects an unintended physical strategy when that behavior persists better and later replaces a learned sensor mapping when its environmental meaning changes. These results show that adaptive direction can emerge without being explicitly specified as a behavioral objective. The same persistence that makes such adaptive agency useful can also allow misalignment, corrupted state and unintended behavior to persist across task boundaries. A scalable artificial id would carry consequential state and adaptive drive across those boundaries, making alignment a property of the continuing agentic system rather than of a model response or single trajectory. Such systems require a persistent alignment boundary over trusted observations, consequence channels, persistent state, authority, identity, provenance and hard constraints.
## Keyword: localization
### Title:
          A variational physics-informed graph neural network for heterogeneous solid mechanics
 - **Authors:** Aashay Rajan Yadav, Amiya Prakash Das, Ratna Kumar Annabattula
 - **Subjects:** Subjects:
Numerical Analysis (math.NA); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Stress localization in heterogeneous solids is governed by the bimaterial interface, where the displacement field remains $C^0$-continuous, while in-plane stresses jump due to the stiffness mismatch. Coordinate-based physics-informed neural networks (PINNs) represent this jump via a prescribed regularization width or a weighted interface penalty, making their accuracy sensitive to how phase-contrast changes are handled. This work presents a variational, label-free physics-informed graph neural network (PI-GNN) in which the heterogeneity is carried by the discretization rather than by the trial field. The solver operates on a conforming adaptive mesh graph, assigns constitutive behavior per element, and minimizes the discrete total potential energy as a single unweighted objective in which only first derivatives appear. The discrete energy on piecewise-linear elements coincides with the finite element (FE) Ritz functional. Dirichlet conditions are enforced by construction, with no penalty term, no interface weight, and no prescribed transition width. Using one fixed architecture, optimizer, and loss across small-strain elasticity and finite-strain Neo-Hookean hyperelasticity in two and three dimensions, the von Mises error remains below $3.58\%$ across a stiffness-contrast sweep spanning $(E_{\mathrm{inc}}/E_{\mathrm{mat}}\in[10^{-2},10^{2}])$, where a strong-form PINN degrades to $5.58\%$, and its displacement error reaches $7.66\%$ against $0.49\%$ for the PI-GNN. A trained network halves the ($\sigma_{xx}$) error of an energy-based PINN ($5.01\%$ versus $10.94\%$). Training cost exceeds a single FE solve by more than an order of magnitude, so the construction is a variationally consistent, penalty-free interface representation for parametric surrogates and inverse identification rather than a replacement for a one-off FE analysis.
### Title:
          Structured Stochastic Representations of Integrated Dynamic Strategies
 - **Authors:** Fredy Vides
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dynamic allocation decisions couple present resource use to evolving internal conditions, delayed returns, and future costs. We represent this interaction by four probability localizations linked through regime-indexed, graph-constrained column-stochastic operators. Pre-action state or context selects a locally affine model, while action-dependent changes update subsequent regimes, yielding a causal switched representation of nonlinear evolution. We characterize operator identifiability relative to the graph, the stochastic constraints, and the sampled embedding, separating coefficient recovery from predictive equivalence on the decision domain. Decision making is then formulated through implementable return--cost acceptability regions. Finite-horizon error propagation supplies conservative classification margins, and simultaneous intervals distinguish model-relative near-optimality from certified $\epsilon$-optimality over a declared finite policy class. Regime-indexed stochastic feedback is admitted when it satisfies the same certification test. Reproducible synthetic laboratories for personal preparation, supplier participation, and customer retention illustrate exact, operator-supplied, and noisy feedback cases. Multinomial experiments show improving recovery of the feedback function and fewer unresolved decisions with increasing sample size, while unrestricted off-policy recovery remains limited. The contribution is a structure-preserving representation--identification--decision workflow, not a domain-specific physiological or commercial calibration.
### Title:
          K/V-Cache Interventions Dissociate Representation Alignment from Persona Expression in Decoder-Only Language Models
 - **Authors:** Yu Sun, Mengyin Lu, Cong Feng, Guangming Lu, Huimin Han
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study K/V-cache interventions -- transplanting a target-conditioned K/V trajectory into a source-persona generation -- as a structured surface for persona control in decoder-only language models. Across 13 intervention configurations applied to Llama-3.1-8B for a fixed source-to-target persona pair, we report two consistent dissociations between representation-level alignment and behavioral expression, plus a common failure under position perturbations. First, all layer-band K/V replacements (early, mid, late) achieve strong local V-space alignment (V-gap 0.91, 0.89, 0.84), but only mid-layer replacement (layers 9-20) combines substantial target-marker expression with preserved lexical diversity. Second, full and mid-layer replacement induce comparable alignment (V-gap 0.94 vs. 0.89) yet produce different lexical-diversity profiles (TTR 0.65 vs. 0.77). Third, position perturbations (lag and shuffle) apply distinct operations yet uniformly suppress target-persona expression -- a common behavioral failure rather than a strict dissociation. Representation-level similarity metrics alone are thus not sufficient predictors of downstream persona expression in the regimes we study; the K/V cache emerges as a controllable but structurally constrained intervention surface. Because the transplanted trajectory carries the target's own generated token history, we characterize the intervention as trajectory-level transplantation rather than isolated persona-representation injection; a same-token-sequence control, decoding an identical token sequence under source vs. target conditioning, reproduces the sign and layer localization of the L28 representational shift, indicating the shift is not explained solely by imported token history. These findings characterize representation-behavior dissociation in a high-signal setting rather than establishing universality across models or persona pairs.
### Title:
          RIDE: Relocalization-Informed Depth Estimation with 3D Gaussian Splatting
 - **Authors:** Jiarong Lian, Zhe Xiao, Zhaoyang Zhang, Wei Li, Ruizhi Chen
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Render--match--PnP relocalization establishes correspondences between query image pixels and 3D map points for camera pose recovery, but their potential to support dense depth estimation is often overlooked. To exploit this geometric information, we present RIDE, which estimates dense metric depth from a robot's RGB stream. Given a metrically scaled 3D Gaussian Splatting (3DGS) model, RIDE combines sparse metric depth observations derived from PnP-RANSAC inlier correspondences with the geometric prior of a pretrained video-depth model. To handle uneven and intermittent observations, it integrates global and local depth correction with temporal memory, supporting depth estimation through short observation gaps after metric scale initialization. Trained on public RGB-D videos, RIDE is evaluated on robot sequences without fine tuning. Experiments show improved depth accuracy and temporal consistency over scale-only calibration, demonstrating how localization geometry can support both pose recovery and dense robot perception.
### Title:
          Beyond Solver Verdicts: Generative Reward Models for Autoformalization
 - **Authors:** Vikash Singh, Debargha Ganguly, Aman Goel, Ali Torkamani, Xiaoxue Han, Joseph Lilien, Ferhat Erata, Vipin Chaudhary
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neurosymbolic systems rely on mathematical solvers to guarantee reasoning correctness, yet solvers are fundamentally blind to whether a formal translation maintains strict reference-equivalence to a designated formalization. We formalize this vulnerability as Verdict-Preserving-Unfaithfulness (VPU): a failure mode where an incorrect encoding executes successfully and matches the expected verdict. We theoretically prove that structural, verdict-only verification heuristics are mathematically bounded to chance-level detection on these deceptively valid traces. To resolve this, we introduce Generative Verification (GenV), which distills an offline Z3-equivalence oracle into a reference-free, continuous reference-equivalence score by repurposing the language model's native vocabulary space. Mechanistic analysis via decision-projected logit lenses and sparse autoencoders shows this generative readout natively extracts precise spatial error coordinates without explicit localization training. Empirically, our oracle-mined verifier (GenV+HN) achieves 0.961 AUROC in reference-equivalence verification, generalizes zero-shot across unseen translators and divergent formal styles, and yields an 11.3-point downstream accuracy gain in agentic test-time compute allocation.
### Title:
          Multi-Faceted Evaluation and Mitigation of Emotion Hallucinations in MLLMs
 - **Authors:** Bowen Zeng, Peipei Song, Weidong Chen, Shengeng Tang, Song Ye, Yuanhong Zhong, Beier Zhu, Xun Yang
 - **Subjects:** Subjects:
Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal large language models (MLLMs) have shown strong potential in open-ended emotion understanding, yet they often generate emotion hallucinations. Evaluating such hallucinations is particularly challenging for two reasons. First, emotion understanding spans multiple cognitive facets, from multimodal perception to psychological reasoning. Second, emotional interpretations are expressed in free-form language, making existing closed-ended protocols insufficient for evaluation. To address these challenges, we introduce EHR (Emotion Hallucination Rate), an evaluator that quantifies emotion hallucinations across six facets: expression, action, audio, instinct, logic, and conclusion. Using EHR, we reveal that existing mitigation methods often reduce hallucinations in some facets while aggravating them in others, exposing the limitation of coarse-grained correction and the need for facet-aware localization and mitigation. Motivated by this finding, we propose HMER (Hallucination-aware Memory-guided Emotion Reasoning), a training-free framework for emotion hallucination mitigation. HMER maintains a Hallucination Memory that records localized hallucinated claims and enables targeted logit rectification, together with an Anchor Memory that preserves reliable intermediate reasoning states to stabilize subsequent generation. By selectively suppressing unreliable cues while preserving trustworthy reasoning context, HMER enables fine-grained mitigation across diverse hallucination facets. Extensive experiments on 19 MLLMs demonstrate the prevalence of emotion hallucinations and the effectiveness of our framework across diverse model architectures.
### Title:
          Harness Robotic OS: A Unified Embodied-Agent Runtime for Closed-Loop Quadruped Inspection
 - **Authors:** Yaoyuan Yan, Zhiyou Heng, Haoxiang Jie, Gang Liu, Hongjie Yan, Wei Zhou
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous property inspection requires more than robust robot navigation: a deployable system must connect heterogeneous sensing, reusable autonomy capabilities, multimodal scene understanding, human interaction, and enterprise response within a traceable operational loop. Existing quadruped inspection systems commonly integrate these functions through task-specific interfaces, making contextual coordination, knowledge reuse, and controlled adaptation difficult. This paper presents \textit{Harness Robotic OS} (HROS), a unified embodied-agent runtime, and Argos, its realization for residential-community inspection. HROS organizes the system into robot runtime, embodied autonomy skills, cognitive agent runtime, and interaction and operations planes. A shared context connects physical state with agent reasoning; streaming ASR/TTS supports voice-based mission interaction; hierarchical working, episodic, and semantic memory preserves operational knowledge; and a safety-gated self-evolution loop converts execution traces into versioned candidate updates without permitting unconstrained online modification. The Argos prototype integrates a Vbot quadruped, Fast-LIO2 localization and mapping, Hobot-Stereo depth perception, PCT-Planner global planning, EGO-Planner local motion generation, and OpenClaw-orchestrated Qwen3-VL inspection analysis. Experiments in a residential property environment achieved 100\% waypoint reachability, outdoor localization error below 10~cm, local obstacle-response latency below 200~ms, representative hazard-detection rates of 85--95\%, and 99\% success in alarm delivery and structured-report generation. These results validate the deployed navigation and inspection closed loop, while HROS provides an extensible software foundation for memory-augmented, voice-aware, and continuously improvable embodied inspection agents.
### Title:
          GRIPNet: Gaussian Radial Intensity Prior Guided Architecture for Pulmonary Nodule Detection in CT
 - **Authors:** Haojie Yang, Ran Su
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Lung cancer causes more deaths than any other malignancy, and low-dose CT screening is the main pathway to early diagnosis. That pathway hinges on the smallest lesions, yet nodules below six millimeters remain hard to detect, because most methods treat a nodule as a generic object and ignore the imaging physics behind its appearance. We show that this appearance is highly regular. Intensity peaks at the geometric center of a nodule and decays radially in a Gaussian pattern, and a fit to 18,218 annotated lesions from three public benchmarks yields a mean radial coefficient of determination above 0.86 in every dataset and size stratum. A square convolution samples both axes uniformly and is mismatched to this radial signal, most severely for small nodules. Guided by this evidence, we propose GRIPNet (Gaussian Radial Intensity Prior Network), a detector in which every module maps to a measurable property of the intensity distribution. Pinwheel convolutions decompose radial gradients, a dual-frequency module separates boundary detail from structural context, dilated masked attention matches the decay extent, and an adaptive loss reweights samples by conspicuity. GRIPNet raises mAP@0.5 to 95.3, 91.6 and 97.9 percent on KanserSet, LUNA16 and Lung-PET-CT-Dx while sharpening high-IoU localization at real-time speed.
### Title:
          DINO-Med: A Unified Patch-Based Adaptation Framework for Multi-Modal Medical Image Analysis Applied to Liver Fibrosis Staging
 - **Authors:** Boya Wang, Ruizhe Li, Chao Chen, Xin Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adapting natural-image foundation models like DINOv3 to multi-modal medical imaging is challenging due to the significant domain gap between natural color images and multi-channel medical scans. We present a unified, patch-based framework that processes raw multimodal imaging through training-free registration, automated localization, and mask-filtered patch extraction. This architecture culminates in a hierarchical strategy that aggregates patch-level insights into subject-level diagnostics. Using liver fibrosis staging as a case study, we evaluate four patch-level feature representations: handcrafted Radiomics features, learned ResNet features, pre-trained foundation model SAM-Med2D features, and frozen DINOv3 features. To ensure a controlled comparison, all models utilize the same lightweight MLP head and are evaluated across both rigid and deformable registration settings. Our training protocol focuses on mild fibrosis (S1) and cirrhosis (S4) classes only, enabling a single classifier to address both substantial fibrosis detection and cirrhosis staging. Evaluated via 10 random train (90%)/ test (10%) splits on 360 subjects from the CARE 2025 Liver Track 4 cohort, our DINOv3-based framework significantly outperforms all baselines, achieving the best classification accuracy of 78.4% for S1 and 75.8% for S4.
### Title:
          Visual-SLAM for the detection of hidden tomatoes in greenhouses by Hierarchical Localization and GLOMAPfor robotized harvesting
 - **Authors:** Fernando Cañadas-Aránega, José C. Moreno, José L. Blanco-Claraco, Francisco Rodríguez
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Advanced crop monitoring inside greenhouses is becoming one of the primary objectives of research centers. High-performance sensors, such as LiDAR or stereo cameras, have traditionally been employed for this purpose, though these often have a high cost. This work proposes a Visual-SLAM system using a monocular camera, which is significantly more cost-effective and specifically tailored for agricultural applications, such as mapping tomato crops in a greenhouse. Tests were carried out on a real tomato bunch, located in the Agroconnect experimental greenhouse. A ROS 2 Humble node was developed to run on the robot in order to capture images of these crops, which were then stored for offline processing. To generate a 3D mapped model for the crop in the greenhouse, the GLOMAP mapper, based on Structure-From-Motion, was integrated with the Hierarchical Localization toolbox. This initial mapping is a foundation for future, more advanced algorithms to analyze growth patterns, and optimize agricultural management. The system leverages a hierarchical localization paradigm based on a coarse-to-fine strategy: it first performs global retrieval to generate location hypotheses, then combines local features within the identified candidate regions. The results show a correct identification of the tomato cluster, correctly characterising the tomato that is occluded and inaccessible by classical vision technologies. The reconstructed 3D model was further validated against manual ground-truth measurements of fruit size, centroid position, and orientation, confirming the geometric accuracy of the proposed low-cost monocular pipeline.
### Title:
          EVPeriscope: Extended Perception across Aerial and Ground Vehicles with Event-based Propeller Tracking
 - **Authors:** Dexter Ong, Vijay Kumar, Pratik Chaudhari
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable relative localization between aerial and ground robots is a key requirement for tightly coordinated heterogeneous teams. This can be difficult to do using conventional frame-based cameras and fiducial markers because they are sensitive to motion blur, lighting variations, and payload constraints. This paper presents EVPeriscope, an event-based perception system that enables detection, localization and control of a quadrotor using an upward-facing event camera on a ground robot by detecting the high-frequency visual signature of its propellers. This system allows the quadrotor to function as an extended perception system for the ground robot when onboard sensors exhibit degradation or occlusion. We demonstrate the capabilities of this marsupial ground-aerial system via experiments in challenging field conditions with wind speeds of up to 15 mph, in both daylight and at night. We show that the system supports localization and closed-loop navigation through dense foliage where the ground robot's sensors are occluded. Our control system for the quadrotor operates at 200 Hz entirely with onboard sensing and computation. More details and experiment videos can be found on the project page: this https URL.
## Keyword: transformer
### Title:
          Halo: Improving forecast accuracy through heteroscedastic estimation
 - **Authors:** Adam Cataldo
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Heteroscedastic forecasting, where a network estimates a scale parameter alongside a location parameter, is normally motivated by uncertainty quantification. This paper shows it also improves the point estimate, in contrast to reported negative results for heteroscedastic estimation outside time series. Halo is a modification that reuses an existing deep forecaster's architecture, giving it a second output for the scale of its implied distribution and training it under the matching negative log likelihood. Adapting three state-of-the-art models --- a transformer, a graph network paired with a variational autoencoder, and a single-layer convolutional network --- under both Gaussian and Laplacian losses demonstrates the phenomenon. On the five electricity price markets of a standard forecasting benchmark, Halo improves MSE and MAE in 28 of 30 model-market-metric comparisons, cutting average MSE by 2.6% to 16.5% and average MAE by 1.7% to 11.0%. Two findings emerge: (1) whether the scale estimate comes from a second projection head or from a full parallel network matters far less than whether the network estimates scale, and (2) the improvement holds under the hyperparameters already tuned for the point-estimate baseline, so retuning is optional.
### Title:
          Sparse Weight and Edge Circuit Discovery in Transformer-based Acoustic Models
 - **Authors:** Jiankun Wei, Ewan Dunbar, Gerald Penn
 - **Subjects:** Subjects:
Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based foundation models are powerful but opaque, motivating Mechanistic Interpretation methods to uncover the black-box by identifying small computation subgraphs responsible for a task. DiscoGP is a joint weight-and-edge circuit discovery framework originally developed for text decoders. We extend DiscoGP to speech encoders and present, to our knowledge, the first circuit discovery study for modern speech foundation models. Across HuBERT and Wav2Vec 2.0 on several speech classification tasks, we find that the discovered circuits are extremely compact, yet often match or even exceed the performance of the full pretrained encoder with the same downstream head. Through ablations, we show that these circuits reflect pretrained computation rather than random structure or task-head artifacts. We also introduce a memory-efficient DiscoGP variant that reduces the GPU memory cost of edge-circuit discovery at runtime from quartic to cubic. Overall, our results broaden Mechanistic Interpretation beyond text decoders and show that circuit-level analysis can reveal both explanatory structure and unexpected functional behavior in speech encoders.
### Title:
          AcFlow: Controlling Text-to-Image Diffusion Transformers via Learned Conditional Activation Flow
 - **Authors:** Junran Wang, Zehao Jin, Tianyu Luan, Xinjie Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-to-image diffusion transformers (DiTs) are powerful generators, yet direct prompting provides limited control interface for style intensity and can fail to suppress unwanted concepts. To enable these controls, we introduce AcFlow, an inference-time controller that transports intermediate layer image-token activations through a learned concept-conditioned velocity field while keeping the base DiT frozen. A textual concept description specifies the desired intervention, while the integration horizon provides a continuous control parameter. The field produces token-varying, activation-dependent updates. With parameters shared across concepts within each task family, the field supports fine-grained descriptions and generalizes to concepts unseen during training without per-concept fitting. On style control, AcFlow achieves the best style--content trade-off among the evaluated baselines in the high-style-alignment regime. At a fixed operating point, AcFlow attains style--content alignment of 0.5365/0.2860, compared with 0.4397/0.2684 for the baseline with the highest style alignment. Qualitative results demonstrate suppression of diverse concepts, including cases where direct prompting fails. Our analyses support the learned velocity field as an adaptive control mechanism, with update directions varying across tokens and depend on their activation states. Our code is available at this https URL.
### Title:
          MHE-Former: Multi-Hypothesis Transformers via Entropy Maximization for 3D Mesh Recovery
 - **Authors:** Boshu Jia, Rongyu Chen, Linlin Yang, Zihao Liu, Yingjie Chen, Zhongqun Zhang, Zhulin Tao, Shaohui Lin, Xiaoyu Wu, Libiao Jin, Baochang Zhang, Angela Yao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular 3D hand and body mesh recovery often suffers from severe occlusion and ambiguity. Traditional deterministic methods typically regress a single optimal solution, leading to overconfident predictions. In this paper, we introduce an exploration--exploitation paradigm for ambiguous mesh recovery with multi-hypothesis learning and selection. Specifically, during exploration, based on our probabilistic formulation and entropy maximization, we propose a novel multi-hypothesis method referred to as MHE-Former. It is a Transformer-based multi-hypothesis framework, ensuring high training efficiency and label friendliness while generating plausible and diverse hypotheses. During exploitation, we propose Hypothesis Selection, a context-aware process for multiple predictions. Especially leveraging VLM's powerful visual understanding and reasoning capabilities, it allows users to choose the most plausible and desired estimate with additional evidence and natural language intent. Extensive experiments demonstrate that our framework achieves state-of-the-art performance in accuracy and diversity across multiple datasets. The user preference study further shows the practicality of our hypothesis selection process.
### Title:
          Temporal and Multimodal Deep Learning for Cyberattack Detection in LEO Satellite Systems
 - **Authors:** Kyle Stein, Guillermo Francia III, Eman El-Sheikh, Hossain Shahriar
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The growing reliance on Low-Earth Orbit (LEO) satellite communication systems has increased the need for intelligent methods capable of detecting cyberattacks across complex and dynamic space environments. Unlike conventional network intrusion detection, satellite systems generate heterogeneous information across radio-frequency (RF) links, onboard hardware, and orbital operations. However, many existing approaches either rely on terrestrial intrusion datasets or evaluate individual observations independently, limiting their ability to capture temporal attack behavior specific to LEO satellites. In this work, we conduct a systematic study of deep-learning-based cyberattack detection using the recently introduced satellite-specific UNSW-IoTSAT dataset. We investigate structured learning architectures that preserve hardware, orbital, and RF information, including a Subsystem-Fusion MLP and a hierarchical multimodal Transformer that models both cross-subsystem interactions and temporal evolution. We further evaluate leakage-resistant row-level and temporal settings, along with cross-satellite generalization, to characterize how model architecture and evaluation protocol influence satellite cyberattack detection. Experimental results demonstrate the value of structured multimodal modeling and rigorous evaluation, with the hierarchical Transformer achieving up to 91.66% accuracy and 85.63% macro F1 under the leakage-resistant evaluation protocol.
### Title:
          Meta-Learning for Data-Efficient Plant Growth Estimation via Vision Transformers and Fuzzy Clustering
 - **Authors:** Sheikh Hasan Elahi, Rusith Chamara Hathurusinghe Dewage, Habib Ullah, Muhammad Salman Siddiqui, Rakibul Islam, Fadi Al Machot
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate plant growth estimation is essential for greenhouse monitoring, yet obtaining labeled data remains costly and time-consuming. To address this, we propose a few-shot regression framework that combines Vision Transformer (ViT) feature embeddings, clustering-based task construction, and gradient-based meta-learning, and show that task construction in embedding space is a primary driver of performance. The approach leverages an unlabeled image pool to organize data into structured tasks using fuzzy c-means clustering, enabling efficient learning from a small number of labeled samples. We systematically evaluate meta-learning methods and show that second-order methods (e.g., Model-Agnostic Meta-Learning variants such as MAML++) outperform classical baselines in the few-shot regime. Furthermore, intra-cluster support selection has a limited and dataset-dependent impact. Experiments on two plant datasets show that structured task design combined with meta-learning enables reliable plant growth estimation under severe label scarcity.
### Title:
          Analyzing Traditional and Neural Approaches to Multilingual Readability Assessment
 - **Authors:** Joshua Wong, Chris Tanner
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based models excel at Automatic Readability Assessment (ARA), yet feature-based models remain in active use because their predictions tie back to linguistic properties. This matters because readability labels are subjective and rater-dependent, so high accuracy on noisy ground truth may reflect surface patterns rather than the linguistic structure that defines difficulty. We test whether transformers internalize the same features as traditional models across Arabic, English, French, Hindi, and Russian using the ReadMe++ dataset. Shapley Additive Explanations (SHAP) identify the features driving traditional classifiers, which we then use as TCAV concept sets to probe multilingual XLM-R and language-specific encoders. Transformers recover surface-length, syntactic, and lexical-diversity signals, and reflect the ordinal CEFR structure of the traditional models. Alignment varies by model family, language, and layer, with language-specific encoders tracking traditional models more clearly than XLM-R. High linear separability does not always imply directional influence, limiting linear probing for count-based readability features.
### Title:
          TrajFusionNet+: Transformer-Based Prediction of Pedestrian Crossing Intention via Fusion of Trajectory Representations and Scene Graphs
 - **Authors:** François G. Landry, Moulay A. Akhloufi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The pedestrian crossing intention task involves predicting whether pedestrians are likely to cross the road from the point of view of an autonomous vehicle. We introduce TrajFusionNet+, a novel transformer-based model for pedestrian crossing intention prediction. TrajFusionNet+ combines sequential and visual representations of pedestrian trajectory with a graph-based representation of the scene context in order to predict pedestrian crossing intention. The proposed architecture builds upon our previous model, TrajFusionNet, and comprises three branches: a Sequence Attention Module (SAM), which processes a sequential representation of past and predicted pedestrian trajectories; a Visual Attention Module (VAM), which utilizes a visual representation of the pedestrian trajectories by overlaying observed and predicted bounding boxes onto scene images; and a Graph Attention Module (GAM), which extracts pedestrian-centric graphs from segmented scene images and captures the relational dependencies between pedestrians and traffic elements. TrajFusionNet+ achieves improved state-of-the-art performance on the two most widely used pedestrian crossing intention datasets, PIE and JAAD. Furthermore, we introduce a new evaluation protocol in which models are trained jointly on the PIE and JAAD datasets but evaluated separately on each. Under this setting, TrajFusionNet+ demonstrates superior generalization compared to existing approaches.
### Title:
          DriftNet: A Dual-Head Trajectory Transformer for Detecting and Localizing Prompt Injection in LLM Agents
 - **Authors:** Asif Pinjari, Mithun Paul Saint-Germain
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 When an indirect prompt injection succeeds against an LLM agent, the compromise is visible in the agent's own behavior: a benign prefix of tool calls, a poisoned observation, and a suffix of actions that serve the attacker. An operator needs three facts: where the attack entered, which steps it corrupted, and whether apparent poison was resisted. Existing systems return either a whole-trace verdict or a single unsafe index. We present DriftNet, a dual-head trajectory Transformer that reads a logged tool-call trajectory and answers all three questions in one forward pass: one head classifies the trajectory as compromised or not, and a second assigns every step one of four labels (benign, injection point, hijacked, failed injection). To our knowledge it is the first supervised detector to produce this joint output. A frozen sentence encoder and four identity-free world features embed each step; the trained trunk, under two million parameters and optimized with a class-weighted joint objective over both heads, needs no access to the agent's model. On the task-disjoint split of the AgentDrift benchmark (12,536 trajectories, 71,024 labeled steps), with a 20-configuration sweep bounding hyperparameter sensitivity to 0.011 F1 and the test part evaluated exactly once, DriftNet reaches trajectory-level F1 of 0.983, exact injection-point recovery on 98.7% of attacked trajectories, hijacked-span IoU of 0.979, zero flags on 218 resisted attacks, and 2.9% flags on hard negatives. A surface baseline retrained on the identical split recovers 11.1% of partial hijacks and 17.1% of delayed executions; DriftNet reaches 98.6% and 93.2% while lowering every false-alarm rate. Reading all 26 residual errors shows that most misses trace to trajectories whose labeled injection observation carries no legible instruction, and we report the benchmark's measured world-identity regularity alongside the results.
### Title:
          HiPerViT: A Hierarchical Perceiver-Vision Transformer Architecture for Multi-Scale Texture Recognition
 - **Authors:** João Pedro C. A. de Sá, Odemir Martinez Bruno
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Texture recognition remains challenging for modern vision models because discriminative evidence is often carried by higher-order spatial statistics rather than by object shape alone. While Vision Transformers provide strong long-range modeling capacity, their standard object-centric representations do not explicitly expose such statistical structure, which limits texture sensitivity in fine-grained recognition settings. We present HiPerViT, a compact vision-only architecture that injects an explicit second-order statistical prior into a transformer-based recognition pipeline. The method combines global and local image views with a compact bilinear descriptor encoded as a statistical token, and integrates this token with first-order spatial representations through Perceiver-style latent distillation. This design enables direct interaction between spatial tokens and second-order feature co-occurrence statistics, providing the model with explicit access to texture-relevant information without requiring multimodal pretraining or ensemble construction. Across six texture recognition benchmarks, HiPerViT achieves consistent improvements over strong vision-only baselines under the reported evaluation protocols, including gains of +3.05 percentage points on DTD, +10.48 on GTOS-Mobile, and +10.10 on 1200Tex. Beyond benchmark performance, our analyses show that these gains are largely invariant to the backbone depth used to extract second-order statistics and to the ordering of interaction and distillation stages. This pattern suggests that the primary source of improvement is not a specific fusion topology, but the explicit availability of second-order statistical information as a first-class representational signal. These results support explicit statistical tokenization as an effective and robust design principle for texture-centric visual recognition.
### Title:
          EGGROLL, Unrolled: Understanding and Improving Low-Rank Evolution Strategies at Scale
 - **Authors:** Ege C. Kaya, Abolfazl Hashemi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 EGGROLL makes evolution strategies (ES) practical for LLMs by replacing dense Gaussian weight perturbations with low-rank Gaussian products, often of rank one. This choice is computationally attractive but geometrically severe: each rank-one perturbation lies in a zero-volume subset of the ambient matrix space, despite having identity covariance. We characterize the mean EGGROLL update field at finite rank and nonzero perturbation radii, then analyze the error of its finite-population estimator. The population field is obtained by applying an explicit resolvent to the gradient of the objective smoothed by the perturbations. We show that the resolvent can introduce a nonconservative component and can reverse the local stability of an optimum. EGGROLL is nevertheless exact on every quadratic objective at every rank and radius. For smooth objectives, its first local finite-rank correction is $O(\sigma^2/r)$, and nonasymptotic bounds control the resulting field error under smoothness assumptions. Under a local affine model, rank-one perturbations increase the variance of the gradient estimator by only $\frac{2(m+n+1)}{mn+1}$ relative to dense Gaussian ES, or $0.098\%$ for a $4096\times4096$ matrix. We then introduce LOO-ROLL, a leave-one-out estimator that preserves the finite-rank population field while replacing EGGROLL's two antithetic evaluations per direction by one. At equal evaluation cost, LOO-ROLL halves estimator MSE in transformer blocks. At matched wall time across ten post-training settings and models up to 8B parameters, LOO-ROLL improves seven outcomes in individual paired tests, with no significant loss. On the GSM8K test set, accuracy increases from $38.1\%$ to $63.0\%$ at 0.6B and from $65.9\%$ to $80.0\%$ at 8B. Transformer measurements recover the predicted finite-rank variance, while the rank comparisons show no reproducible reward-based advantage for rank eight.
### Title:
          DeFiFusion: Combining Transaction Events with Smart Contracts to Detect Price Manipulation Attacks
 - **Authors:** Rui Cao, Shaojing Fan, Liming Fang, Yuchan Liu, Yingying Jiao, Zhenguang Liu
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Decentralized Finance (DeFi) has emerged as a rapidly growing blockchain-based financial service, where market transaction dynamics and underlying smart contract logic are intricately intertwined. This autonomous interplay, while eliminating centralized intermediaries, significantly expands the vulnerability surface of DeFi protocols to Price Manipulation Attacks (PMAs), which have already inflicted catastrophic financial losses. Despite their gravity, existing detection paradigms suffer from fundamental limitations. Transaction-centric methods lack awareness of contract execution semantics, making them prone to false positives under legitimate market volatility, while static contract analyses ignore real transaction behaviors and frequently report vulnerabilities that are infeasible to exploit in practice. We present DeFiFusion, a dual-modal PMA detection framework that closes this gap by jointly modeling transaction events and smart contract semantics within a unified pipeline. Our core insight is that PMA maliciousness emerges only from the interaction between transaction behaviors and the contract logic they exploit; neither signal suffices in isolation. Accordingly, we derive price-manipulation-aware event encoding for extracting fine-grained temporal and economic features tailored to manipulation patterns. We further introduce LLM-based contract semantic extraction to supply the execution-logic context that prior behavioral methods lack. To fuse these modalities, we propose a Dual-Modal Projection-Fusion Transformer with T5-style relative positional encoding, capturing the cyclic multi-stage execution structures that distinguish PMAs from benign market activity. Extensive experiments demonstrate that DeFiFusion consistently achieves state-of-the-art detection performance, effectively recalling 222 of the 225 PMA cases while maintaining a precision of 96.10%.
### Title:
          The information geometry of large language models is shared, learned, and controllable
 - **Authors:** Dario Picozzi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models learn similar behaviours, yet it remains unclear what structure they share or how to change one behaviour without disturbing others. The Fisher-Rao geometry of next-token probabilities connects these questions: behaviour determines this geometry up to output-preserving symmetries, whereas activation geometry depends on coordinates. Across transformer, state-space and recurrent models, output geometries agree more strongly than activation geometries, and shared geometry supports semantic-category transfer. Agreement with human word choices increases with predictive accuracy, scale and training, and improves further after model-only calibration. Token probabilities and read-out geometry jointly predict the spectrum and its effective dimension. Controlled language assignments show that geometry follows the language law across architectures. Pretraining corpus statistics predict held-out fact acquisition without recalibration, while randomised experiments show that deeper evidence substantially delays acquisition across every tested architecture and evidence construction. Finally, the geometry prescribes minimum-disturbance local interventions, predicts their relative cost, and supports reusable control: updates learned on donor prompts transfer to unseen prompts while better preserving behaviour on reference prompts than Euclidean control. The same geometric correction improves steering, editing, attribution, dictionary learning and fine-tuning.
### Title:
          Multimodal Temporal Modeling for Continuous Group Emotion Recognition in Multi-party Dialogues
 - **Authors:** Soma Iwata, Koji Inoue, Muyun Wu, Taiga Mori, Divesh Lala, Tatsuya Kawahara
 - **Subjects:** Subjects:
Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 To realize natural behavior in dialogue agents in multi-party dialogue scenarios, it is important to understand group emotion such as valence and arousal as a whole. Most prior work addressed this task at the utterance level or using a coarse-grained time window, which is not sufficient to capture emotional dynamics. In this study, we formulate continuous recognition of the Group Emotion at a one-second resolution. Moreover, we also introduce the Mixed state, which captures the emotional divergence among participants in the group. We constructed a dataset with frame-level soft labels based on the TEIDAN corpus and propose a multimodal temporal framework that integrates audio and video information using a sliding-window context. Experimental results demonstrate that the temporal Transformer outperforms simple baselines and shows stronger temporal agreement with the ground-truth labels than the LLM-based model. The effect of context length is limited, whereas audio-visual input outperforms either unimodal input on the continuous-label metrics. Additionally, our analysis shows larger Group Emotion recognition errors in intervals with high Mixed values, exposing emotional divergence as a key challenge for group emotion recognition.
### Title:
          CEM-TUDASR: Computationally efficient multi-modality transformer based unsupervised domain adaptive super-resolution approach
 - **Authors:** Anjali Sarvaiya, Jay Kadel, Kishor Upla, Kiran Raja
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Wireless Capsule Endoscopy (WCE) enables non-invasive visualization of the gastrointestinal tract, but its miniaturized optics, sensor limitations, and wireless transmission constraints result in low-resolution images with reduced visibility of diagnostically important structures. This paper proposes CEM-TUDASR, a computationally efficient unsupervised Transformer-based super-resolution framework for WCE image enhancement without paired low-resolution (LR) and high-resolution (HR) training data. A domain-adaptive degradation network synthesizes realistic WCE-like LR images from HR conventional endoscopy images, reducing the domain gap and enabling effective unpaired learning. The SR generator integrates Deep Attention Blocks (DABs) and a Fusion Attention Block (FAB) to capture long-range contextual dependencies and fine local structures while preserving perceptual and structural fidelity. The model is trained on a curated dataset derived from Kvasir Capsule and evaluated on KID and GIANA for cross-dataset generalization. No-reference quality metrics, including BRISQUE, PIQE, NIQE, and the domain-specific EndoQM, show that CEM-TUDASR consistently outperforms existing unsupervised SR methods. Qualitative results further demonstrate improved restoration of mucosal textures, vascular patterns, and clinically relevant anatomical details. Cross-domain experiments on retinal images additionally demonstrate the adaptability of the framework. With only 2.67 million parameters and 169.94 GFLOPs, CEM-TUDASR achieves high-quality reconstruction while maintaining computational efficiency, making it suitable for resource-constrained clinical and embedded endoscopic applications.
### Title:
          SCINTILLA-SNN: A Spiking Multi-Scale Selective Aggregation Network for Perineural Invasion Prediction
 - **Authors:** Youngung Han, Yului Jeong, Kyeonghun Kim, Dohyun Kweon, Suah Park, Hyunsu Go, Sungha Park, Anna Jung, Jinyong Jun, Yunho Choe, Yunjin Seo, Ken Ying-Kai Liao, Hyuk-Jae Lee, Nam-Joon Kim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Preoperative prediction of perineural invasion (PNI) in cholangiocarcinoma (CCA) is clinically valuable but remains challenging because PNI-related cues on magnetic resonance imaging (MRI) are subtle, sparse, and spatially localized around the tumor boundary. Standard 3D CNN and transformer architectures process volumetric data in a dense or spatially uniform manner, which can dilute subtle PNI-related evidence while requiring a large number of multiply-accumulate operations over 3D feature grids. To address these limitations, we propose SCINTILLA-SNN, a 3D spiking network composed of a four-stage hierarchical backbone and a Multi-Scale Spike Aggregation (MSSA) module for PNI prediction. The backbone extracts hierarchical volumetric representations through spiking convolutional stages and local spike window modulation stages. Given the resulting stage-wise representations, MSSA maps each spatial token to a learnable content value and modulates it with a spike-dynamics gate derived from firing rate and timestep-wise membrane-potential variability. The resulting score, referred to as the diagnostic token score, is used to selectively aggregate sparse PNI-related evidence. Experiments on a 10-year retrospective cohort of 182 CCA patients show that SCINTILLA-SNN achieves an AUROC of 0.748 under 5-fold cross-validation, while reducing the estimated inference energy by 23.18$\times$ compared with dense MAC-only computation of the same network.
### Title:
          Exploring Diffusion Transformers for Cross-Modal Augmentation in Multimodal Brain State Decoding
 - **Authors:** Ziwei Wang, Xingyi He, Hongbin Wang, Tianwang Jia, Bohan Fang, Dongrui Wu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal brain state decoding has largely focused on fusing paired modalities for prediction, but has rarely explored how their correspondence can be further exploited to enrich training data and improve multimodal representation learning. To address this gap, we propose CoMA-DiT, a bidirectional cross-modal Diffusion Transformer for latent augmentation that treats paired modalities as sources of mutual generative supervision rather than merely as inputs to be fused. CoMA-DiT conditions velocity prediction on the paired modality through cross-modal attention and adaptively injects the resulting variation via a reliability-gated residual mechanism. Experiments on multimodal auditory attention decoding and emotion recognition showed that CoMA-DiT consistently outperformed 20 representative baselines, achieving absolute gains of 4.28% and 6.70% in accuracy and macro-F1 over the no-augmentation baseline, respectively. Extensive ablation, sensitivity, visualization, and interpretability analyses further demonstrated its robustness, generalizability, and ability to capture functionally relevant cross-modal interactions. These findings support a broader view of multimodal learning: Paired modalities can serve not only as inputs for fusion but also as supervision sources that augment one another.
### Title:
          RAMamba-Net: A Reliability-Aware and Mamba-Based Multimodal Fusion Network for Auditory Attention Detection
 - **Authors:** Xingyi He, Ziwei Wang, Dongrui Wu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Auditory attention decoding (AAD) identifies the attended speaker from physiological signals, supporting neuro-steered hearing devices and natural human-machine interaction. Electroencephalography (EEG) is the dominant modality for AAD but provides incomplete evidence in naturalistic audio-visual scenes, motivating EEG and electrooculography (EOG) fusion. Existing approaches remain limited by weak cross-modal interaction, inefficient temporal modeling, and low robustness to sample variations. To address the limitations, we propose RAMamba-Net, a reliability-aware Mamba-based multimodal fusion network for AAD. RAMamba-Net employs a Mamba-enhanced band-aware convolutional Transformer to capture band-specific EEG patterns and long-range temporal dynamics. A dual-branch temporal-spatial encoder models EOG temporal and inter-channel dependencies. Cross-modal attention enables explicit modality interaction. Then, a reliability-aware module is introduced to estimate sample-wise modality weights for feature and prediction consistency, thereby enhancing multimodal fusion. Experiments on two AAD benchmarks demonstrate that RAMamba-Net effectively exploits complementary EEG-EOG information, yielding accuracy gains of 5.76% over unimodal baselines, together with more robust decoding and discriminative representations. Further analyses show that explicit cross-modal interaction improves multimodal alignment, while the reliability-aware module suppresses unreliable modality evidence and is robust to signal perturbation and parameter variation.
### Title:
          Vision Transformer-Based Multi-Level Feature Fusion for Multi-Label Sewer Defect Classification
 - **Authors:** Xu Fang, Zhuoran Wang, Qing Li, Shengyu Zhang, Guanzhi Deng, Jianbiao He, Qingquan Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated classification of sewer defects is essential for infrastructure condition assessment and maintenance decision-making, but existing deep learning methods struggle to balance classification accuracy and computational complexity in large-scale multi-label scenarios. This study develops Sewer-Transformer-ML, a hierarchical vision Transformer with multi-level feature fusion, together with two lightweight architectures, Sewer-MobileNet-ML and Sewer-Mobile-TransNet, for resource-constrained inspection scenarios. On the Sewer-ML test set, Sewer-Transformer-ML-Base achieved an $F2_{\text{CIW}}$ of 65.68% and an $F1_{\text{Normal}}$ of 92.68%, ranking first on the public leaderboard and exceeding the second-ranked method by 7.6 percentage points in $F2_{\text{CIW}}$. Sewer-MobileNet-ML achieved an $F2_{\text{CIW}}$ of 65.73% with only 17 M parameters, representing an approximately 95% parameter reduction relative to the base model. Under the standard Sewer-Capsule data split, Sewer-Mobile-TransNet achieved 96.43% classification accuracy. When the training set was reduced to 1,177 images, pretraining on Sewer-ML consistently improved model performance. Ablation experiments further showed that direct concatenation was more effective for Transformer features, whereas attention-based fusion better supported multiscale CNN features. These findings provide a computational basis for automated sewer inspection, lightweight model design, and adaptation across civil infrastructure inspection platforms.
### Title:
          Deep Learning-based Bug Triage System
 - **Authors:** Sourabh Pal
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Effective bug triage is crucial for streamlining the software development lifecycle by accurately categorizing and assigning reported software defects. In this paper, we propose an automated bug triage system built upon the pre-trained RoBERTa-base transformer architecture. By leveraging deep contextual representations, our approach efficiently classifies incoming bug reports to optimize assignment. Experimental evaluation demonstrates that the proposed system achieves a strong bug identification accuracy of 0.90 within just five training epochs. These findings highlight the efficiency and high performance of fine-tuned transformer models for practical software engineering automation.
### Title:
          BridgeMatch: Conditional Transport Bridges in Matching Matrix Space for 3D Deformable Registration
 - **Authors:** Qianliang Wu, Haobo Jiang, Guangwei Gao, Shuo Chen, Jin Xie, Jian Yang, Yaqing Ding
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable non-rigid point cloud correspondences are important for deformable anatomical registration, embodied perception and manipulation, and dynamic 3D reconstruction. Coarse-to-fine methods reduce computational cost by selecting the top-\(K\) coarse regions. However, this pruning may remove weak but correct hypotheses and restrict fine matching to an incomplete search space. We present \paper, a two-stage generative solver that maintains the complete soft matching matrix at both coarse and high resolutions. Stage~I uses denoising diffusion to estimate a global matching matrix in the compact coarse-resolution space. We then lift this matrix to high resolution while preserving its hierarchy. The lifted matrix is rank-bounded and block-constant. Stage~II refines it through a conditional transport bridge. We implement the bridge with two types of dynamics: a deterministic endpoint-parameterized conditional Flow Matching (CFM) ODE and a stochastic Brownian-bridge SDE inspired by Schrödinger bridges. Both variants share the lifted source, a time-conditioned transformer, and a matching-matrix endpoint predictor. Experiments on 4DMatch and 4DLoMatch show that both variants produce more accurate correspondences than the compared methods and improve downstream registration, with larger gains in low-overlap cases. They also improve cross-dataset generalization on CAPE and DeepDeform without target-domain adaptation while using the same deformation solver.
### Title:
          FreeFlow: A Bias-free Hierarchical Transformer for Optical Flow Estimation
 - **Authors:** Vladislav Bargatin, Alexander Yakovenko, Khaled Abud, Dmitriy Vatolin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Optical flow methods typically rely on task-specific inductive biases, such as correlation volumes, feature warping, and iterative refinement, among others, to reach high accuracy. While effective, such biases constrain the model to predefined heuristics, which can limit its expressivity and lead to more complex pipelines and additional computational cost. We present FreeFlow, a hierarchical transformer built without any flow-specific components, using instead a single feed-forward encoder--decoder. FreeFlow combines three attention variants: window attention for local processing, shifted-window attention for cross-window information exchange, and a global attention operating at a reduced resolution. The resulting architecture scales naturally with model capacity, enabling a consistent accuracy gain from small to large variants. Despite the absence of standard inductive biases, FreeFlow achieves state-of-the-art results on major benchmarks, including Sintel (0.68/1.48 EPE on Clean/Final), KITTI-2015 (3.23 Fl-all), and Spring (3.192 1px), while remaining memory efficient at 1080p inference.
### Title:
          ActMap: Single-Pass Uncertainty Quantification from Generation-Time Activation Maps
 - **Authors:** Jacopo Dardini (University of Bologna), Roberta Calegari (University of Bologna)
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Practical uncertainty quantification (UQ) for large language models must decide, from a single generation, whether a specific answer should be trusted. Existing methods either sample multiple generations, read only output-token probabilities, or reduce the model's internal computation to a single hidden state. We introduce ActMap, a white-box representation that compresses the generation-time hidden- state trajectory (every layer, every generated token) into a fixed $12 \times 32 \times 128$ tensor of temporal-statistic channels that preserves structure across transformer depth and pooled hidden coordinates. The map is captured during the generation pass with no measurable overhead, has a fixed shape across model depths and hidden sizes, and occupies 96 KiB: a compact artifact that can be retained for audit-relevant generations and probed directly, with occlusion analysis localizing the classifier's signal to mid-depth regions of the map. A lightweight classifier, instantiated as a compact Vision Transformer, reads an estimated correctness probability from each map in a fraction of a millisecond; capacity-matched MLPs perform comparably, indicating the representation itself carries the result. Trained and evaluated in-domain on short-answer QA, direct- answer math, and summarization factuality with three instruction-tuned 7-8B models, ActMap consistently outperforms sampling, token-probability, attention, and embedding baselines, and matches ACT-ViT, a detector trained on dense activation tensors $67 \times$ larger, at essentially the same mean AUROC with lower calibration error on ten of twelve pairs. The resulting score supports abstention, routing, and selective verification from a single generation, making it a practical primitive for scalable oversight of deployed models.
### Title:
          Harnessing Intrinsic Subject-Aware Attention for Controllable Multi-Subject Video Generation
 - **Authors:** Niange Yu, Ye Tian, Biaolong Chen, Miao Lu, Aixi Zhang, Hao Jiang, Yunhai Tong, Pipei Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-subject video generation faces two key challenges: uncontrollable fidelity strength and potential semantic drift. We address these by analyzing the internal mechanisms of Diffusion Transformers (DiTs). We found that certain attention blocks naturally form an Intrinsic Spatial Grounding Map (ISGM) that precisely locates reference subjects. Building on this insight, we propose Dual-phase Intrinsic Attention Leveraging (DIAL), a framework that uses these internal signals for both training and inference. In low-noise stages, we use ISGM to guide the attention mechanism, allowing precise control over fidelity strength during inference without retraining. In high-noise stages, we use these same maps to automatically build preference pairs at no additional cost for Reinforcement Learning (RL). This RL procedure effectively anchors the model's attention to reference subjects and mitigates semantic drift. Extensive experiments show that DIAL significantly outperforms baseline models on the OpenS2V-Eval benchmark, consistently improving identity consistency and enabling controllable fidelity strength.
### Title:
          LoopVAE: Recurrent Depth Across Scales for Visual Tokenization
 - **Authors:** Zhiying Lu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hierarchical visual tokenizers typically allocate different processing blocks to different spatial scales. We ask how much of this computation can use the same parameters. LoopVAE reuses a scale- and loop-conditioned core within and across scales, while keeping resolution-changing transitions independent. A four-block core executes 28 block applications per encoder or decoder. On ImageNet-256, the 29M-parameter convolutional model reaches 0.28 rFID and 32.54 dB PSNR under an approximately 30-epoch two-stage training budget, using approximately 65% fewer parameters than the 84M reference VAEs. A non-adversarial Transformer ablation with the same execution graph finds competitive PSNR and SSIM under global sharing, although unshared blocks improve LPIPS. Targeted loop interventions show that completing the trained recurrence improves reconstruction and that even small feature updates can have substantial downstream effects. Truncation also exposes output-range errors, distinguishing useful recurrent computation from reliable early exit. Runtime profiling reveals the execution tradeoff: fewer stored weights require more arithmetic and longer runtime in the tested configurations. With convolutional and Transformer operators and single- or multi-resolution latent interfaces, LoopVAE establishes recurrent depth across scales as a parameter-sharing design axis for visual tokenization.
### Title:
          ZipCodec: Ultra-Low-Frame-Rate Streaming Speech Coding
 - **Authors:** Luca Della Libera, Cem Subakan, Mirco Ravanelli
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural audio codecs are a fundamental component of modern speech generation systems. While recent codecs achieve increasingly low bitrates, reducing frame rate remains challenging, as each token must preserve more information while maintaining reconstruction quality. We present ZipCodec, a streaming neural speech codec operating at 6.25 Hz and 0.80 kbps with a theoretical latency of 160 ms. Our approach combines large-scale WavLM distillation with a redesigned transformer-based architecture, a scalar spherical quantizer, and a latency-aware streaming decoder. Experiments show that ZipCodec substantially outperforms existing streaming codecs at comparable bitrates in both reconstruction and downstream tasks, while operating at a significantly lower frame rate. Despite its 842M parameters, ZipCodec achieves real-time single-stream inference on a consumer-grade CPU. Demo samples, code and checkpoints are available at this https URL.
### Title:
          From Grid to Chip: Power Architecture, Stability, and Flexibility of AI Data Centers
 - **Authors:** Yubo Song, Rui Kong, Takuro Umihara, Pooya Davari, Frede Blaabjerg, Subham Sahoo
 - **Subjects:** Subjects:
Emerging Technologies (cs.ET); Hardware Architecture (cs.AR); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid growth of artificial intelligence (AI) computing is transforming data centers into large, dynamic electrical loads. Their deployment is primarily constrained by energy availability and grid-connection capacity, which is further aggravated by the ability of power-delivery architectures, control systems, and computing workloads to operate reliably during fast grid disturbances. This article presents a technological perspective on AI data centers as grid-interactive computing systems. First, it reviews grid-integration bottlenecks, evolving connection policies, grid-code requirements, which has fostered new technological trends via spatio-temporal flexibility available through workload orchestration, cooling systems, on-site resources, and energy storage. Second, it maps the evolution of power-delivery architectures from medium-voltage grid interfaces to chip-level, discussing higher-voltage DC distribution, solid-state transformers, wide-bandgap devices, advanced chip-level power delivery, and liquid cooling. Third, it establishes a three-level stability framework spanning rack-level DC-bus dynamics, facility-level converter interactions, and system-level grid-coupled behavior. The framework connects dominant instability mechanisms, including constant power load effects, impedance interactions, forced oscillations, and operating-mode transitions, with suitable modeling, assessment, and mitigation approaches. Synthesizing these topics, this article highlights grid-to-chip co-design as a central requirement for scalable AI infrastructure, linking computing workloads, power-delivery systems, energy buffers, and grid operation.
### Title:
          Multimodal Taxonomic Conditioning for Generative Plankton Imagery
 - **Authors:** Daniela Ivanova, Ozgu Goksu, Nicolas Pugeault
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated plankton imaging produces severely long-tailed datasets, where the rare taxa of greatest ecological interest have too few images to train or evaluate classifiers reliably. We generate synthetic plankton imagery conditioned on taxonomy: a CLIP encoder is adapted on a large plankton corpus with a ranked contrastive objective extended to deep, ragged taxonomies, then frozen to condition a parameter-efficient diffusion transformer. We evaluate synthetic sample quality on distributional fidelity and downstream classifier utility.
### Title:
          IndicTriMix: Developing Language Identification Datasets and Models for Tri-Language Code-Mixing
 - **Authors:** Pruthwik Mishra, Rudra Trivedi, Avi Patel, Ashok Urlana, Shrikant Malviya
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Language identification in code-mixed text, largely observed in social media, is highly essential when users frequently switch between multiple languages within a single utterance. Accurately identifying the languages of code-mixed tokens becomes an urgent necessity. Traditional language identification models, designed for monolingual text, are not well suited for token-level language identification in code-mixed settings. We formulate the task as a sequence labeling problem and fine-tune contextual transformer-based models MuRIL and XLM-RoBERTa best suited for Indian languages. We evaluate these systems on three different data configurations (Hindi, Gujarati, and Bengali) to predict language labels for individual tokens. We release a benchmark for language identification in code-mixed tokens with manually annotated test sets. We propose two approaches of code-mixed generation using parallel sentences of three languages. The trained models demonstrate the effectiveness of contextual embeddings for token-level language identification in multilingual social media text. For reproducibility and to facilitate future research, we publicly release our fine-tuned models.
### Title:
          Distance generalization in transformers: why bother with positional encoding?
 - **Authors:** Daniel Henrik Nevermann, Claudius Gros
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Out-of-distribution length generalization, namely to extrapolate a task from short to longer context, has been studied intensively for transformers. Here we focus on distance generalization, which probes performance when inter-token distances are changed between training and inference, while keeping a fixed context length. We construct two synthetic delay copy tasks, both involving finite distances between source and recall, where tokens are copied either fully or selectively, and test models on delays unseen during training. We address three questions: (A) Do positional encoding schemes such as RoPE and ALiBi improve distance resolution relative to no positional encoding (NoPE)? (B) How does data diversity, the number of inter-token distances seen in training, affect performance? (C) When is distance transfer learning positive or negative? We present a thorough investigation, finding that it is paramount to improve our understanding of the underlying mechanisms.
### Title:
          Data Scarcity and Model Sparsity: Mixtures-of-Experts Overfit More to Repeated Data
 - **Authors:** Atindra Jha, Margaret Li, Jure Leskovec, Percy Liang, Luke Zettlemoyer
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As the supply of human-written text is exhausted, it has become standard practice to repeat language model training data. Prior work has studied data repetition for densely activated Transformers, but the effects of data repetition remains largely unexplored for recently dominant sparse architectures such as Mixture-of-Experts (MoE), despite their increased compute efficiency. We vary data repetition rates across single- and multi-domain data mixes, and across MoE settings, including expert count and granularity. We consistently find, for models ranging from 80M to 1B active (8.5B total) parameters, that MoEs degrade more rapidly under data repetition. This effect increases with sparsity, dictated by total rather than active parameters. While 80M dense models can repeat data over 8x with minimal degradation, MoEs instead begin to suffer at 4x, and deteriorate rapidly, ceding their performance benefits in all-unique data settings to underperform dense models after 32x. We experiment with existing regularization methods as a potential remedy. We find that some methods, such as dropout, can mitigate overfitting. In particular, with strong masking-based regularization, MoEs are able to outperform dense models even when data is repeated more than 64 times. However, no method fully matches the performance of all-unique training data. Finally, we analyze internal mechanisms correlated with MoE overfitting in high repetition regimes, and find that MoE routing universally stabilizes early in training, and that expert specialization correlates with overfitting to repeated data. In sum, our work addresses the adverse interactions between sparsity and data repetition: we present evidence for the core mechanisms of overfitting and its potential remediation, and suggest promising avenues for future methods to reduce over-specialization in model parameters by disrupting memorization patterns.
## Keyword: autonomous driving
### Title:
          CARLAverse: A Highly Modular, Distributed, and Multimodal Framework for Human-in-the-Loop Simulation
 - **Authors:** Patrick Rebling, Philipp Nenninger, Reiner Kriesten
 - **Subjects:** Subjects:
Robotics (cs.RO); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The development of autonomous driving demands comprehensive testing in mixed-traffic scenarios involving vulnerable road users (VRUs), where purely artificial agents often fail to capture authentic human social negotiations. While human-in-the-loop (HITL) simulators enable safe investigation of these interactions, existing multi-agent platforms struggle with the network latency and synchronization constraints required for high-fidelity haptic feedback. To resolve this, we present CARLAverse, an open-source, multimodal simulation ecosystem. Extending modular hardware abstraction, CARLAverse integrates driving (DrivoCARLA), cycling (CycloCARLA), and pedestrian (WalkoCARLA) simulators into a shared virtual environment. Its core methodological contribution is a distributed physics architecture: latency-critical ego dynamics and high-frequency force feedback are computed locally on client nodes, while a central CARLA server orchestrates non-player character (NPC) physics and global traffic. By decoupling haptic control loops from network bottlenecks, CARLAverse enables scalable, cross-institutional HITL experiments without compromising physical immersion. Code and documentation: this https URL
### Title:
          MC-DeTra: Motion-Consistent Joint Object Detection and Socially-Aware Trajectory Forecasting in Bird's-Eye-View Images
 - **Authors:** Vladislav Diuzhev, Dmitry Yudin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unified models for object detection and trajectory forecasting aim to merge perception and prediction for autonomous driving, refining actor trajectories directly over shared bird's-eye-view (BEV) images rasterized from LiDAR and high-definition maps. Their accuracy on dynamic, moving actors, however, remains the hardest part of the task, and the strongest such model, DeTra, has no public implementation. We contribute an openly released DeTra reimplementation with documented approximations, and on top of it MC-DeTra: a family of motion-consistency mechanisms that add supervision through two annotation-derived auxiliary signals -- each actor's observed past motion and the occupancy of the surrounding traffic that forms its social context -- and one inter-output consistency constraint that aligns an actor's predicted heading with its predicted direction of motion. Every proposed loss is train-only and inference-safe: it shapes the shared BEV representation during training and is removed at test time, adding no inference latency. On the Waymo Open Dataset, evaluated under a strict, detection-conditioned forecasting protocol, MC-DeTra improves dynamic, socially-situated trajectory forecasting while preserving or improving detection accuracy; a gradient-based loss-calibration analysis exposes how the auxiliary objectives compete at the shared backbone, and our ablation identifies which signals contribute most. We release code, configurations, and evaluation tooling at this https URL.
