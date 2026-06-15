# Showing new listings for Monday, 15 June 2026
## Keyword: SLAM
### Title:
          Which Models Perform Better in Inheritance Reasoning?
 - **Authors:** Mohammed Amine Mouhoub, Chahinez Bouchekif
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents the participation of team PSL in the QIAS 2026 Shared Task on Arabic Islamic inheritance reasoning. The task evaluates the ability of large language models to solve inheritance cases that require legal interpretation, multi-step reasoning, and precise numerical computation. We compare \textit{commercial} and \textit{open-source} models under a unified prompting strategy to assess their effectiveness in structured legal reasoning with minimal task-specific adaptation. \\ Our results show a clear gap in reliability between the two model families. Commercial models demonstrate stronger performance in identifying eligible heirs, applying exclusion rules, and maintaining consistency across reasoning steps. In contrast, open-source models exhibit greater instability, particularly in cases involving dependent legal decisions and fractional share adjustments. The best performance is achieved by \textit{Gemini 2.5 Flash}, with an MRE of $0.989$.
### Title:
          QIAS 2026: Overview of the Shared Task on Islamic Inheritance Reasoning
 - **Authors:** Abdessalam Bouchekif, Somaya Eltanbouly, Samer Rashwani, Shahd Gaben, Mutaz Al-Khatib, Heba Sbahi, Emad Mohamed, Mohammed Ghaly
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a comprehensive overview of the QIAS 2026 shared task, organized as part of the OSACT7 Workshop and co-located with LREC 2026. The shared task was designed to evaluate the ability of large language models to perform complex reasoning in the religious and legal domain of Islamic inheritance. Unlike conventional question-answering benchmarks, QIAS 2026 focuses on end-to-end reasoning from natural language cases, requiring systems to perform the full inheritance calculation process, from identifying the eligible heirs to assigning the correct share to each beneficiary. To support this evaluation, the task was based on the MAWARITH benchmark, a dataset of $12{,}500$ Arabic inheritance cases annotated with intermediate reasoning steps and final answers. System submissions were evaluated using MIR-E, a multi-step metric that measures performance across the main stages of inheritance reasoning. A total of $16$ teams participated in the shared task, investigating a range of approaches, including prompting-based methods, retrieval-augmented generation, and fine-tuning strategies. The results show that Islamic inheritance remains a highly challenging benchmark for current language models, especially in stages that require precise legal interpretation and structured numerical reasoning. This overview summarizes the task design, dataset, evaluation framework, participating systems, and main results.
## Keyword: odometry
### Title:
          BIM-Loc: BIM-Integrated Discrepancy-Aware LiDAR-based Indoor Localization
 - **Authors:** Yinqiang Zhang, Liang Lu, Yipeng Pan, Maolin Lei, Yuhan Xie, Zhanteng Xie, Xiaowei Luo, Jia Pan
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate and robust localization is a fundamental requirement for service and inspection robots, particularly in feature-sparse indoor environments where traditional systems struggle due to a lack of distinct landmarks. While prior maps can enhance robustness, precise and compact maps capturing real-world details are often unavailable for new or frequently changing environments. This paper presents BIM-Loc, a novel discrepancy-aware LiDAR-based localization method that directly integrates Building Information Models (BIM) from the design phase. BIM-Loc simultaneously estimates trajectories aligned with the BIM coordinate system and identifies discrepancies between real-world observations and the as-designed BIM in an online fashion. Our core contributions include: (1) a novel multi-hit ray casting strategy for efficient BIM-point data association and projection of 3D observations into 2D texture space; (2) a pose graph optimization framework with BIM-integrated factors that enforces consistency among odometry, sequential scans, and BIM structures; and (3) a hierarchical Bayesian inference module that incrementally updates a continuous 2D surface representation for discrepancy detection, propagating updates from the pixel to the structure level. Extensive evaluations in both simulation and real-world applications demonstrate that BIM-Loc significantly outperforms state-of-the-art map-based methods in localization accuracy and robustness.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          BIM-Loc: BIM-Integrated Discrepancy-Aware LiDAR-based Indoor Localization
 - **Authors:** Yinqiang Zhang, Liang Lu, Yipeng Pan, Maolin Lei, Yuhan Xie, Zhanteng Xie, Xiaowei Luo, Jia Pan
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate and robust localization is a fundamental requirement for service and inspection robots, particularly in feature-sparse indoor environments where traditional systems struggle due to a lack of distinct landmarks. While prior maps can enhance robustness, precise and compact maps capturing real-world details are often unavailable for new or frequently changing environments. This paper presents BIM-Loc, a novel discrepancy-aware LiDAR-based localization method that directly integrates Building Information Models (BIM) from the design phase. BIM-Loc simultaneously estimates trajectories aligned with the BIM coordinate system and identifies discrepancies between real-world observations and the as-designed BIM in an online fashion. Our core contributions include: (1) a novel multi-hit ray casting strategy for efficient BIM-point data association and projection of 3D observations into 2D texture space; (2) a pose graph optimization framework with BIM-integrated factors that enforces consistency among odometry, sequential scans, and BIM structures; and (3) a hierarchical Bayesian inference module that incrementally updates a continuous 2D surface representation for discrepancy detection, propagating updates from the pixel to the structure level. Extensive evaluations in both simulation and real-world applications demonstrate that BIM-Loc significantly outperforms state-of-the-art map-based methods in localization accuracy and robustness.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          Efficient On-Device Diffusion LLM Inference with Mobile NPU
 - **Authors:** Tuowei Wang, Yanfan Sun, Ju Ren
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion large language models (dLLMs) accelerate generation by denoising multiple tokens in parallel, making them attractive for latency-sensitive mobile inference. However, repeated denoising introduces substantial computation on smartphones. Mobile neural processing units (NPUs) offer high-throughput dense matrix computation, but efficiently exploiting them remains challenging: token commitment shrinks per-block effective workloads, token revision complicates KV cache reuse, and limited NPU-visible address space incurs costly remapping and data transfer overheads. In this paper, we propose this http URL, the first NPU-aware inference framework for accelerating dLLMs on smartphones. this http URL aligns block-wise dLLM inference with the execution characteristics of mobile NPUs through three techniques. (1) Multi-Block Speculative Decoding fills the shrinking workload in late-stage current-block decoding with speculative future-block tokens. (2) Dual-Path Progressive Revision keeps committed tokens revisable until stable and refreshes unstable tokens through a CPU-side path without stalling dense NPU execution. (3) Swap-Optimized Memory Runtime compacts NPU-visible address layouts and overlaps data staging with NPU computation to reduce remapping and transfer overheads. We implement this http URL as an end-to-end framework and evaluate it across diverse hardware platforms and dLLM workloads. this http URL reduces LLaDA-8B generation latency by 17x-42x over the CPU baseline with prefix KV cache reuse, while preserving generation quality.
### Title:
          An integrated interpretable control effectiveness learning and nonlinear control allocation methodology for overactuated aircrafts
 - **Authors:** Umut Demir, Aamir Ahmad, Walter Fichter
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Nonlinear dynamics and the strong couplings that arise between multiple effectors undermine the assumptions behind conventional, linear control allocation techniques. When flight enters regimes where nonlinear effects dominate, linear allocators exhibit reduced accuracy due to increased model mismatch, which subsequently degrades performance and robustness of the flight control system. High fidelity onboard models and black box data driven approaches can recover accuracy across the flight envelope, but respectively impose computational burdens prohibitive for real time allocation and sacrifice the interpretability required for verification and fault diagnosis. This paper addresses these limitations by learning an explicit, physics constrained analytical model of the control effectiveness mapping from representative flight data using Sparse Identification of Nonlinear Dynamics. The resulting mapping is compact, interpretable, and admits analytical derivatives, enabling efficient computation within nonlinear solvers that additionally incorporate actuator dynamics, without requiring an onboard model. An online adaptation mechanism monitors prediction residuals and refreshes the model when significant plant changes are detected, providing graceful reconfiguration under actuator failures and varying operating conditions. The methodology is evaluated on a high fidelity nonlinear benchmark aircraft across a range of aggressive maneuvers, achieving accuracy comparable to a full nonlinear onboard model while substantially reducing computational cost relative to established baselines.
### Title:
          Price-Discovery Admissibility in Tokenized Fixed Income: Identification, Affine Characterization, and the Structure of the Token-to-Fiat Mapping
 - **Authors:** Artem Alkhamov, Boris Kriuk
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A tokenized U.S. Treasury product lives on two ledgers: an off-chain portfolio of government securities and an on-chain wrapper that claims to represent it. The foundational question is whether the on-chain series carries recoverable information about the underlying -- whether a mapping from token to fiat exists, and with what structure. We proceed in three steps. First, fixed-income measurement conventions are reconciled between the ledgers; these corrections are signed and jointly. Second, on the reconciled series we introduce a price-discovery admissibility criterion: a falsifiable test, based on serial dependence and idiosyncratic dispersion, for whether a product's series is market-informative or administratively generated. Of four products with sufficient history it admits exactly one; the rest are dominated by how net asset value is computed and republished, and treating them as spreads fits artifacts. That most of the universe is inadmissible is our principal finding. Third, for the admitted mapping we give a minimal two-factor affine characterization in which the basis enters additively and orthogonally to rates, recovering a quarterly reversion, a small positive long-run basis, and a sharp March 2026 regime change toward parity. Persistence is weakly identified; we propagate it through a profile likelihood into one consequence, a collateral haircut. The contribution is measurement and identification infrastructure for when on-chain fixed income may be treated as a quantitative object.
### Title:
          Guided Diffusion with Distilled Vision-Language Reliability for Aerial Navigation
 - **Authors:** Ivan Valuev, Iana Zhura, Valerii Serpiva, Didar Seyidov, Dzmitry Tsetserukou
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous UAV navigation is conventionally solved by pipelines that separate perception, mapping, and planning into distinct stages, which propagates errors, accumulates latency, and requires environment-specific retuning. End-to-end generative models remove these interfaces by mapping raw observations directly to trajectories, but inherit a subtle failure mode: trained on clean data, they cannot recognise when an observation is unreliable, and treat degraded regions such as glass, mirrors, and overexposed surfaces as valid evidence for planning. We present a reliability-aware diffusion planner for 3D UAV navigation. It conditions trajectory generation on the observation together with a scene-level reliability heatmap that marks where perception cannot be trusted, produced by a lightweight network that distils the open-vocabulary reasoning of a vision-language model within the real-time planning budget. To generalise to unseen environments without retraining, we steer the denoising process with a differentiable two-stage ESDF cost that treats physical obstacles from depth and virtual obstacles from highly unreliable regions on equal footing. In simulation and on a real quadrotor, our planner produces markedly safer trajectories than a state-of-the-art diffusion baseline, reducing the obstacle-violation rate from 40.3% to 9.6% and raising the mean reliability of traversed regions from 0.588 to 0.925. Ablating the reliability term alone drops mean reliability from 0.898 to 0.783, confirming it as the decisive component, while distillation runs the framework up to 2 times faster than the full vision-language model.
### Title:
          PhysVLA: Towards Physically-Grounded VLA for Embodied Robotic Manipulation
 - **Authors:** Namai Chandra, Shriram Damodaran, Lin Wang
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models excel at mapping visual inputs and natural language instructions directly to robotic control policies. However, because they are trained primarily to fit behavioural demonstration data, they do not explicitly enforce fundamental physical principles such as rigid-body dynamics or contact constraints. This exposes a critical physics gap: standard temporal smoothing applied on top of single-step or chunked VLAs trades trajectory quality for added failures that short-term memory cannot resolve. To bridge this gap, we introduce PhysVLA (Physics-VLA), a plug-and-play, inference-time framework designed to wrap any frozen VLA backbone without retraining, fine-tuning, or weight access, with less than 1 ms of overhead per control step. PhysVLA intercepts the predicted control action, captures only the simulator or system state, and applies a dual-layered correction: (i) a phase-aware finite-state machine that structures discrete task segments (approach, grasp, transport, and place), and (ii) a selective Euler-Lagrange gate that activates only when a dynamics oracle detects kinodynamic inconsistency. Evaluated across OpenVLA, OpenVLA-OFT, Force-VLA, and Generalist-VLA on LIBERO-Spatial with a 7-DoF Franka Panda, the framework delivers absolute success rate increases of up to 17% and stability increases of up to 19% with no per-task regressions, improves trajectory efficiency by up to 15% across all four backbones, and shows up to a 10x improvement in trajectory jerk robustness on a Robosuite Lift cross-simulator sweep. We further validate the framework on a real Agilex Piper arm with a pick-and-place task, confirming that PhysVLA transfers to physical hardware without retraining, with success-rate improvements of up to 50%, establishing physical awareness as a composable, backbone-agnostic runtime module.
### Title:
          SplatlessDF: Continuous Distance Field Mapping with Non-Splatting Gaussians
 - **Authors:** Monisha Mushtary Uttsha, Lan Wu, Teresa Vidal-Calleja
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent Gaussian splatting (GS) methods have shown that scenes can be represented efficiently with optimisable Gaussians for high-quality reconstruction and rendering. In this paper, building on this principle, we introduce SplatlessDF, a continuous distance field (DF) mapping framework that uses anisotropic Gaussian elements from a spatial rather than photometric perspective. SplatlessDF directly parameterises the Gaussians and optimises to recover a differentiable DF, enabling distances and gradients to be queried in the spatial domain for downstream robotic tasks such as navigation. Furthermore, SplatlessDF can be coupled with 2D Gaussian splatting (2DGS), providing a unified framework based solely on Gaussian primitives that can learn continuous DF and surface models and supports photometric rendering. We consider two settings: a standalone DF-only formulation and a joint DF-rendering formulation coupled with 2DGS. Experiments show that the standalone formulation provides efficient and accurate distance and gradient queries, while the joint formulation improves rendering geometry and simultaneously models a continuous DF. These results highlight the potential of GS-style representations not only for surface modelling and rendering but also for mapping representations suited to robotic navigation.
### Title:
          Deep Spectral Learning of Embedded Latent Transfer Operators for Stochastic Dynamical Systems
 - **Authors:** Ryogo Tanaka, Yoshinobu Kawahara
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose a spectral learning method for stochastic nonlinear dynamical systems represented with embedded latent transfer operators in deep feature spaces. We instantiate the method as Deep Spectral Encoder (DSE), an operator-based latent state-space model in which a time-invariant neural encoder implements learnable nonlinear feature maps from observations, and these features define Markovian latent states whose temporal evolution and observation mapping are described by the transfer and observation operators, respectively. Functional canonical correlation analysis in a learnable Galerkin-projected feature space provides state coordinates from past and future observations, and the two linear operators are estimated on the state coordinates as ridge-regularized closed-form solutions that coincide with Galerkin projections of the associated covariance operators. On this representation, we generalize sequential Bayesian filtering and Koopman spectral mode decomposition in feature space. Experiments on several scenarios show stable and superior performance with sequential Bayesian filtering and dynamic mode decomposition baselines even under noise and partial observability.
### Title:
          Clay-CNN Hybrids: Leveraging Geo-Foundational Models as Auxiliary Context for Landslide Detection
 - **Authors:** Huong Binh Vu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rapid post-event landslide mapping is essential for disaster response but remains difficult to automate due to extreme class imbalance. This study evaluates whether Clay v1.5, a Geo-Foundational Model (GFM), can improve pixel-level landslide segmentation on the Landslide4Sense (L4S) benchmark, which contains 3,799 training chips with 14 Sentinel-2 and terrain bands and approximately 2% positive pixels. We compare three strategies: Clay as the primary encoder with multi-scale residual terrain fusion, a U-Net backbone augmented with Clay semantic context at the bottleneck, and a standard U-Net baseline. The hybrid U-Net + Clay model with two-stage Low-Rank Adaptation (LoRA) achieved the best test F1 of 64.5 +/- 1.8% over three seeds, surpassing the Clay-only backbone (55.2 +/- 3.6%) and the U-Net baseline (59.9%). Clay as a standalone encoder underperformed the U-Net due to the absence of multi-scale skip connections, but its pretrained representations consistently improved performance when injected as auxiliary context. These findings suggest that GFMs are most effective for landslide detection when they complement spatially detailed convolutional architectures rather than replace them.
### Title:
          AFFORDANCE20Q: Evaluating Affordance Reasoning from Physical Properties
 - **Authors:** Yifan Jiang, Meige Yang, Zitong Li, Jay Pujara
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Affordance reasoning, the inference of an object's action possibilities from its physical properties (e.g., shape and material), is fundamental to human physical understanding and increasingly critical for Large Language Models (LLMs). However, existing affordance benchmarks largely expose explicit object identities in the evaluation setup, allowing models to rely on memorized object-affordance mappings rather than reasoning over physical properties. To address this gap, we introduce Affordance20Q, a novel affordance reasoning benchmark formulated as a 20-Questions game without exposing the object's identity. In each game, the model identifies a hidden object's affordance from a candidate set by asking yes/no questions about its physical properties. Affordance20Q comprises 1,009 games over 454 objects and 59 affordances, all manually filtered, refined, and annotated. We conduct comprehensive experiments with 15 state-of-the-art LLMs and find a substantial gap (~20 points) compared to human performance. A KL-based information-gain (IG) analysis further shows that models fail to ask discriminating questions as the game progresses. To close the gap, we develop KB-Anchored Rule Induction (KARI), a pipeline based on LLMs that generates affordance rules grounded in evidence from knowledge bases (KBs). KARI improves open-source LLMs by up to 15.2 points, while the limited coverage of KBs hinders further gains. We release all our code and data at this https URL
### Title:
          Optimality-Preserving Decomposition for Scalable QAOA in Natural-Language-Guided Multi-Drone Assignment
 - **Authors:** Junyeop Bang, Byongho Lee, Dohyun An, Hwangnam Kim
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As multi-drone fleets scale, zone assignment rapidly evolves into an intractable NP-hard combinatorial problem that overwhelms classical exhaustive search. While quantum optimization promises to shatter these classical bottlenecks, mapping complex spatial tasks from human intent to restricted quantum hardware remains a severe challenge. To bridge this gap, we present an end-to-end framework integrating a fine-tuned Large Language Model (LLM) front-end with a highly scalable, domain-specific quantum-classical backend. The front-end utilizes Supervised Fine-Tuning (SFT) and Direct Preference Optimization (DPO) to translate free-form natural language instructions into structurally robust Quadratic Unconstrained Binary Optimization (QUBO) constraints without false negatives. To overcome the strict qubit limits of near-term quantum devices, our framework features a novel constraint-preserving graph partitioner and a compressed separator-based dynamic programming (DP) merge. By structurally encoding constraints via W-state initialization and XY-mixers in Conditional Value-at-Risk Quantum Approximate Optimization (CVaR-QAOA), the pipeline stays highly compact. Empirical results demonstrate that this architecture circumvents classical scaling walls, recovering the global optimum on 100% of idealized oracle cases and 96.3% under real QAOA sampling, enabling natural-language-guided task allocation at previously intractable scales.
### Title:
          Transforming Shape Schemas with Composable Property-Graph Queries (Extended Version)
 - **Authors:** Philipp Seifer, Daniel Hernández, Ralf Lämmel, Steffen Staab
 - **Subjects:** Subjects:
Databases (cs.DB); Artificial Intelligence (cs.AI); Logic in Computer Science (cs.LO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Property graphs may be constrained by schemas that inform both query engines and human users about the shape of valid data, enforcing a contract between data provider and consumer. Composable property-graph queries transform input graphs into output graphs. Then, the question arises of which schema can be expected after one (or several) transformation steps. We investigate how schema constraints can be inferred given an input schema and a transforming query. Specifically, we propose a reasoning procedure that, given an input schema in ProGS and a query in G-CORE infers an output schema. Since graph updates will happen frequently, our inference procedure does not rely on graph instances, such that the computed output schema applies to all graphs originating from any input graph complying with the input schema. Related work has addressed this problem for SPARQL CONSTRUCT queries, encoding it in Description Logics (DLs) so that the output schema is entailed by axioms inferred from input schema and queries. Property graphs and their queries, however, complicate the matter, as property graphs feature label and property annotations as well as first-class edges. Thus, reification has to be used in one way or another, though available DLs lack the means to encode such features directly. We approach this novel challenge via a family of mappings for i) property graphs reified in RDF, aligned with ii) a mapping from ProGS to SHACL and iii) a mapping from G-CORE to SPARQL CONSTRUCT queries. In this manner, schema inference for property graphs becomes manageable, as we break apart the problem through the extra mapping layer and utilize efficient DL reasoners. We develop the metatheory regarding the soundness of inferred schema constraints and the semantic equivalence of mapped schemas and queries.
### Title:
          Regulating the Machine Contributor: Governance and Policy Alignment in Open Source
 - **Authors:** Jassem Manita, Aziz Amari
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI-assisted software development has moved from line-level autocomplete to agents that can plan changes, edit files, and submit pull requests with limited human supervision. Open-source software, however, evolves through a process designed for humans: contributor agreements, codes of conduct, and review norms all assume a legally accountable person who can attest to provenance and answer reviewer questions. Autonomous and semi-autonomous AI contributors strain those assumptions, and the 2025-2026 record of agent-driven incidents, AI-generated nuisance volume, and platform-level shutdowns shows that the gap is operationally consequential. Several open-source organisations have responded with contribution policies, but the result is fragmented, and its alignment with emerging AI governance frameworks (EU AI Act, NIST AI RMF with the UC Berkeley Agentic AI Profile, ISO/IEC 42001 and 23894) is unmapped at the contribution level. We compare policies across six organisations (SymPy, LLVM, matplotlib, OpenInfra, the Apache Software Foundation, and the Linux Foundation) using Most-Similar Systems Design with indicator-based coding and process tracing for SymPy and LLVM. From this we derive a six-dimensional taxonomy (disclosure, responsibility, human oversight, licensing, enforcement, maintainer workload), an ordinal Policy Maturity Score, and a mapping of documented agent incidents onto the dimensions each policy fails to govern. Aligning the dimensions with the regulatory frameworks above identifies overlapping gaps neither side currently closes, and we close by sketching the shape of a harmonised tiered framework and the empirical evaluation needed to calibrate it.
### Title:
          CottonLeafVision: An Explainable and Robust Deep Learning Framework for Cotton Leaf Disease Classification
 - **Authors:** Rafi Ahamed, Md. Abir Rahman, Tasnia Tarannum Roza, Munaia Jannat Easha, Md. Asif Khan, Sudeepta Mandal
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Globally, cotton is a highly economically beneficial crop, as the textile industry heavily depends on it. So, the precise identification and detection of cotton leaf disease is crucial for economic stability. The development goal of "CottonLeafVision" is to accurately classify and detect cotton leaf disease. With this goal, we have evaluated multiple pretrained Deep Convolutional Neural Networks, including DenseNet201, InceptionV3, and VGG19 on a publicly available cotton leaf disease image dataset. This image dataset includes seven classes, six disease classes, and one healthy class, collected under various field conditions reflecting real-world challenges. Among these pretrained models, with DenseNet201, we have achieved the highest classification accuracy of 98%. To enhance the model reliability and interpretability, we have implemented different techniques and methods such as Gradient-weighted Class Activation Mapping (Grad-CAM), occlusion sensitivity analysis and adversarial training to increase the noise resistance of the model. Finally, we have developed a prototype in order to utilize the model's capabilities on real life agriculture. This paper shows the deep learning model's capabilities to classify the disease in real-life cotton disease management situations.
## Keyword: localization
### Title:
          Scalable Dynamic Tactile Sensing Enabled by Passive and Flexible Acoustic Waveguides
 - **Authors:** Guimin Long, Changhong Linghu, Chuanping Liu, Ke Xu, Xingjian Jing
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Artificial dynamic tactile sensing requires sensitivity, robustness, and compliance, yet existing technologies face trade-offs when scaling to large-area arrays, compounded by wiring complexity and cost. Here, we report a passive distributed paradigm using deep sub-wavelength acoustic waveguides that decouples performance from structural flexibility. Elastic-membrane-capped Helmholtz resonators interconnected by spring-reinforced microtubes form an enclosed network with invariant acoustic transmission under macroscopic bending. By sparsely embedding microphones, the system achieves real-time localization (4 mm highest spatial resolution; >99% accuracy in a 4 microphones 64-node sensing array) and waveform reconstruction of low-frequency signals (<100 Hz). Fast Continuous Wavelet Transform and a lightweight neural network enable inference within 5.5 ms. We demonstrate conformable prototypes-fingertip arrays, a tactile glove, and large-area skins-detecting stimuli from single-hair contact to 5-mg particle impacts, arterial pulse waves, feather touches, and finger contact. This establishes a scalable, flexible, low-cost paradigm for next-generation human-machine interfaces.
### Title:
          Choric Masking in Ambient Release Systems: A Finite Certificate Calculus for Trace Indistinguishability under Bounded Audiences
 - **Authors:** Faruk Alpay, Taylan Alpay
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper develops a finite certificate calculus for ambient release systems, staged probabilistic environments in which a protected coordinate is not observed directly but can remain statistically readable through visible roles, timing, repeated movement, bounded attention, linked rooms, and post-release state. The security notion, choric masking, requires the trace law induced by a protected locus to lie inside or near the convex hull of admissible cover traces under the tests available to a specified audience. For finite horizons, trace laws form polytopes, audiences induce measurement operators, and masking becomes intersection in the projected measurement space. Exposure is certified by separating hyperplanes, kernel obstructions, hypothesis-testing bounds, Fano-type localization lower bounds, and support separation in downstream rooms. The calculus distinguishes trace residue from carrier localization, full-trace exposure from attention-filtered exposure, first-room masking from delayed post-release exposure, and unresolved system pressure from carrier hazard. It proves measurement-polytope equivalence for exact and approximate masks, dual separation certificates, data-processing laws for attention lenses, aperture identities for gaze-thinned observation, lower bounds for mandatory unique gestures, composition rules for linked releases, and a repeated-room debt theorem showing how unresolved pressure can broaden selection and shift cost onto cover populations without localizing the source. The result is a finite, checkable language for auditing privacy, unlinkability, side-channel leakage, and accountability in public-facing release systems.
### Title:
          Context-Guided Semantic Alignment for Feature Fusion Networks
 - **Authors:** Hyungseop Lee, Jiho Lee, Woochul Kang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Feature fusion networks are fundamental components in modern object detectors, aggregating multi-scale features to detect objects of varying sizes. However, directly fusing features from different pyramid levels often introduces semantic inconsistency due to their heterogeneous representations. In this paper, we propose Feature Interaction NEtwork (FINE), a lightweight semantic alignment module that refines low-level features via high-level contextual guidance using cross-level attention prior to fusion. To bridge the structural gap and ensure computational efficiency, we introduce an Alignment-Aware Token Sampling that aligns corresponding spatial regions across scales, reducing the attention complexity by an order of magnitude. The resulting attention weights generate a spatial-channel modulation map that is upsampled and applied to the low-level features via residual element-wise modulation. This mechanism ensures that the network selectively enhances semantically relevant pixels while preserving the sub-pixel localization accuracy necessary for dense prediction tasks. FINE is generally applicable to various detectors and consistently improves detection accuracy without compromising efficiency.
### Title:
          LLM Agents Can See Code Repositories
 - **Authors:** Dongjian Ma, Silin Chen, Yufei Yang, Yulin Shi, Yanfu yan, Xiaodong Gu
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Coding agents powered by large language models have demonstrated strong performance on software engineering tasks. Yet most agents consume repositories almost entirely as text, which differs from how human developers use visual structure such as folder hierarchies and dependency relationships to orient themselves in large codebases. With multimodal large language models (MLLMs), it is an open question whether agents can effectively benefit from visual representations of repositories. This paper presents the first systematic empirical study of visual repository representations for LLM-based agents on repository-level issue resolution. We evaluate four recent multimodal models. Our results show that a strictly vision-only setup degrades accuracy and increases token cost, because agents lack sufficient symbolic detail and compensate with repeated visual queries. In contrast, integrating visual graphs of repository structure as a supplementary modality alongside standard text interfaces helps agents understand structure more efficiently: input token consumption decreases by up to 26% while issue-resolution accuracy is maintained or improved. Visualization is most useful during fault localization and when the agent autonomously controls exploration depth. These findings point to a practical hybrid text-and-vision design for next-generation coding agents.
### Title:
          A Modular Dual-Arm Apple Harvesting Robot with Enhanced Field Performance
 - **Authors:** Keyi Zhu, Kyle Lammers, Chaaran Arunachalam, Kaixiang Zhang, Renfu Lu, Zhaojian Li
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robotic apple harvesting offers a promising solution to labor shortages in commercial orchards, but low throughput and poor performance in orchard environments hinder its commercial adoption. This paper presents a modular dual-arm apple harvesting robot that uses a vertically stacked arms to enable simultaneous operation in the upper and lower zones of a single tree, simplifying platform positioning from multi-tree lateral repositioning to single-tree stops. Compared to our prior horizontal dual-arm system, the platform integrates 5 advances: (1)a foundation-model-based perception pipeline combining Grounding-DINO and EfficientViT-SAM for robust fruit localization in unstructured outdoor environments; (2)7th-order jerk-bounded trajectory generation paired with a Control Barrier Function safety filter to achieve fast yet safe arm motions; (3)a linear sweep harvesting strategy with a 10cm approach buffer and rotational detachment that improves picking reliability; (4)a temporal-logic-based dual-arm coordination policy with vision-arm async scheduling that maximizes usage of a shared vacuum source; and (5)field validation in 2 commercial orchards covering different apple varieties and tree architectures during the 2025 harvest season. Across the 1738 arm cycles collected in these field trials, the system achieved an 80.0% per-attempt success rate and a mean per-arm cycle time of 7.53s. Fruit damage assessments confirmed that 91.2% of robotically harvested fruit retained the highest USDA grade (Extra Fancy), with bruise rates between 2.4% and 4.9%. With further improvements in the picking cycle time and handling of heavy foliage occlusions, this new modular robot design holds promise for commercial harvesting of apples.
### Title:
          FEMOT: Multi-Object Tracking using Frame and Event Cameras
 - **Authors:** Shiao Wang, Xiao Wang, Chao Wang, Yitao Li, Menghao Liu, Bo Jiang, Yaowei Wang, Yonghong Tian, Jin Tang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Conventional RGB cameras have been widely used in multi-object tracking due to their ability to capture rich appearance and semantic information. However, their performance is often degraded under complex real-world challenges, such as motion blur, low illumination, and overexposure. Bio-inspired event cameras offer high temporal resolution and high dynamic range, providing complementary cues under extreme scenarios. Nevertheless, RGB-event multi-object tracking remains underexplored due to the lack of large-scale and well-annotated datasets. To address this issue, we propose FEMOT, a large-scale RGB-event multi-object tracking dataset that covers diverse real-world scenarios and 14 challenging attributes. With both RGB and event data as well as high-quality annotations, FEMOT provides a reliable platform for systematically evaluating RGB-event multi-object tracking methods. Based on FEMOT, we retrain and evaluate over ten strong trackers, thereby establishing a comprehensive benchmark for future research. Furthermore, we propose FEMOTR, a multimodal tracking framework that decouples RGB and event features and fuses them in the frequency domain, thereby effectively exploiting their complementary characteristics for robust object localization and identity association. Extensive experiments on FEMOT and DSEC-MOT datasets demonstrate the effectiveness of the proposed method. The source code and benchmark dataset have been released on this https URL.
### Title:
          A New Multi-Domain Benchmark for Micro-Action Recognition and Detection
 - **Authors:** Yanbin Hao, Pengyu Liu, Xing Wei, Xun Yang, Dan Gu, Meng Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Micro-actions are short-duration, low-amplitude subtle body movements at the whole-body level that can reveal latent intentions, involuntary reactions, and fine-grained affective changes. Our previous MA-52 benchmark has provided an important foundation for micro-action recognition, but it remains limited in scale, scene diversity, task coverage, and evaluation protocols. To advance micro-action analysis toward more realistic and comprehensive settings, we introduce MMA-82, a large-scale multi-domain extension of MA-52. MMA-82 expands the label space from 52 to 82 fine-grained micro-action categories and covers four distinct domains, including laboratory interviews, street interviews, psychiatric patient interviews, and emotion-rich television videos, resulting in 77,856 annotated instances from 454 subjects. Built upon MMA-82, we establish two core tasks: Micro-Action Recognition and Multi-label Micro-Action Detection. For recognition, we further define in-domain and cross-domain protocols, including few-shot and zero-shot settings, to evaluate model robustness, transferability, and generalization. Extensive experiments show that current methods still struggle with realistic micro-action understanding, especially under domain shift, long-tailed category distributions, and complex temporal localization. Beyond benchmarking, we investigate the relationship between micro-actions and emotion, showing that micro-actions are strongly associated with emotional states and provide complementary cues to facial micro-expressions for improved emotion recognition. These results demonstrate that MMA-82 serves as a comprehensive and challenging benchmark for realistic micro-action analysis and a valuable resource for human-centered AI. MMA-82 is available at this https URL.
### Title:
          Spatio-Temporal Audio Language Modeling for Dynamic Sound Sources
 - **Authors:** Oh Hyun-Bin, Kazuki Shimada, Yuhta Takida, Kim Sung-Bin, Toshimitsu Uesaka, Takashi Shibuya, Kyeongyoon Lee, Tae-Hyun Oh, Yuki Mitsufuji
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sound events are entities with semantic identities, locations, and trajectories, but current audio-language models usually reason about clips as global event content. Conversely, sound event localization models track source directions over time but offer limited semantic coverage for language reasoning. To address this gap, we introduce ST-AudioQA, a spatio-temporal audio QA dataset and benchmark built from first-order ambisonic (FOA) renderings of static and moving sound sources. Each scene provides source identity, activity, direction, distance, and motion metadata, enabling dense trajectory supervision and questions about what is sounding, where it is, how it moves, and how sources relate. We further propose ST-Audio Encoder, a time-resolved FOA audio encoder that learns event semantics together with source trajectories, and ST-AudioLM, which connects the audio tokens from the encoder to an LLM for spatio-temporal audio QA. Experiments show that this representation improves the semantic-localization tradeoff and yields stronger reasoning performance than static spatial and localization-oriented baselines.
### Title:
          BIM-Loc: BIM-Integrated Discrepancy-Aware LiDAR-based Indoor Localization
 - **Authors:** Yinqiang Zhang, Liang Lu, Yipeng Pan, Maolin Lei, Yuhan Xie, Zhanteng Xie, Xiaowei Luo, Jia Pan
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate and robust localization is a fundamental requirement for service and inspection robots, particularly in feature-sparse indoor environments where traditional systems struggle due to a lack of distinct landmarks. While prior maps can enhance robustness, precise and compact maps capturing real-world details are often unavailable for new or frequently changing environments. This paper presents BIM-Loc, a novel discrepancy-aware LiDAR-based localization method that directly integrates Building Information Models (BIM) from the design phase. BIM-Loc simultaneously estimates trajectories aligned with the BIM coordinate system and identifies discrepancies between real-world observations and the as-designed BIM in an online fashion. Our core contributions include: (1) a novel multi-hit ray casting strategy for efficient BIM-point data association and projection of 3D observations into 2D texture space; (2) a pose graph optimization framework with BIM-integrated factors that enforces consistency among odometry, sequential scans, and BIM structures; and (3) a hierarchical Bayesian inference module that incrementally updates a continuous 2D surface representation for discrepancy detection, propagating updates from the pixel to the structure level. Extensive evaluations in both simulation and real-world applications demonstrate that BIM-Loc significantly outperforms state-of-the-art map-based methods in localization accuracy and robustness.
### Title:
          A Lightweight Fiducial-Based Pipeline for 3D Hyperspectral Mapping of ex-vivo Lumpectomy Specimens
 - **Authors:** Anna Bicchi, Alberto Rota, Leonardo Passoni, Nicola Ancellotti, Andrea Peroni, Lorenzo Vinco, Dario Polli, Elena De Momi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hyperspectral Imaging (HSI) is a promising modality for intraoperative assessment of resection margins in Breast-Conserving Surgery (BCS), but its clinical translation requires aligning the inherently 2D spectral information onto the 3D shape of the excised tissue so that suspicious regions can be precisely localized for targeted follow-up. We present a fully automated, calibration-free pipeline that produces a 3D hyperspectral point cloud of an ex-vivo lumpectomy specimen from a set of consumer-camera RGB images and a single top-down HSI acquisition. The 3D geometry is reconstructed with a deep-learning Structure-from-Motion backbone, stabilized in a metric reference frame by a custom bundle adjustment that enforces consistency on the corners of four ArUco markers placed around the specimen. The HSI cube is then registered to the reconstruction without recovering the HSI camera pose: the markers, visible in both modalities, define 16 corner correspondences that drive a planar homography, and 3D coordinates are recovered by lookup on an orthographically rendered depth map. Evaluated on two ex-vivo lumpectomy specimens, the pipeline achieves a median 3D registration error below 1~mm and a 2D reprojection error below 0.02 mm, with a total per-specimen processing time under 4 minutes on accelerated hardware. These results support the feasibility of integrating HSI-guided spatial localization into intraoperative margin assessment workflows for breast-conserving surgery.
### Title:
          Characterizing Cultural Localization in AI-Generated Stories
 - **Authors:** Shaily Bhatt, Supriti Vijay, Jeremiah Milbauer, Fernando Diaz
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The global use of artificial intelligence has increased interest in assessing the ability to generate culturally localized content, including stories. Cultural localization in stories often occurs through either templated localization -- the use of cultural markers (e.g., names, locations) in a generic narrative -- or holistic localization -- the variation of plots, values, and themes, in addition to cultural markers. We propose a method to measure the degree to which content was generated through templated localization. Specifically, we identify the lexical tokens that distinguish stories across nationalities and measure the similarity of the narratives that remain after removing them. In stories generated by five models on 125 topics for 193 nationalities, our method is able to detect that only a small subset (9-17%) of the vocabulary accounts for the variation across nationalities and that the narratives that remain after removing them contain repeated multi-word sequences, suggesting the presence of a shared culturally-agnostic narrative template. Finally, we characterize the cultural markers for their stereotypicality and offensiveness, finding that markers from 19 countries, mostly located in the Global South, are on average offensive.
## Keyword: transformer
### Title:
          A Deep Reinforcement Learning (DRL)-Based Transformer Method for Solving the Open Shop Scheduling Problem
 - **Authors:** Faezeh Ardali, Mwembezi A. Nyelele, Gerald M. Knapp
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The open shop scheduling problem (OSSP) arises in many industrial and service settings but remains computationally challenging as the number of jobs and machines increases. While exact methods quickly become intractable, classical dispatching rules and metaheuristics may require substantial tuning to maintain solution quality at large scales. This study develops a Transformer-based scheduling policy for OSSP using an encoder-decoder architecture with multi-head attention. The model is trained on Taillard benchmark instances (4x4, 5x5, 7x7, and 10x10) using only the processing-time matrix as input and produces feasible schedules with makespans typically within 15-30% of best-known values. To evaluate scalability, the trained policy is applied without retraining to randomly generated instances from 40x40 to 100x100 and compared against classical dispatching heuristics, including SPT, LPT, MWKR, and EST. Across these large instances, the Transformer achieved average gaps of 12.89-15.12% relative to a standard lower bound. Compared with EST, the Transformer remained competitive, typically within a modest margin, while substantially outperforming SPT and LPT. These results indicate that a Transformer policy trained on small OSSP instances can generalize to substantially larger problems and provide a feature-light, learning-based alternative to classical dispatching rules.
### Title:
          Explaining RhythmFormer: A Systematic XAI Analysis of Periodic Sparse Attention for Remote Photoplethysmography
 - **Authors:** Louis Chen, Torbjörn E. M. Nordling
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Remote photoplethysmography (rPPG) transformers achieve low heart-rate error on benchmarks, yet their decisions remain opaque--a growing concern as rPPG moves toward clinical heart rate estimation. Existing rPPG XAI is dominated by qualitative heatmap inspection without quantitative faithfulness metrics or physiology-grounded validation, leaving a gap between visual plausibility and auditable evidence. We address this gap. First, we adapt four attribution methods (raw attention, rollout, flow, Beyond Intuition) to RhythmFormer's bi-level routing attention with top-$k$ selection. Second, we introduce a skin coverage metric quantifying how much attribution mass falls on skin regions. Third, we adapt the SaCo faithfulness coefficient from its original classification setting to rPPG regression by using the MAE between original and perturbed predicted rPPG waveforms as the perturbation impact. Applying these tools, we quantify a multi-hop leakage effect under sparse top-$k$ routing: attention rollout and flow almost completely restores the connections that individual refined-attention layers explicitly set to zero. Beyond Intuition mitigates this via its value-projection-weighted rollout and gradient-supported mask, attaining the highest median refined skin coverage ($0.83$ vs. $0.57$ for vanilla rollout) and faithfulness ($F=0.92$) among the evaluated methods on UBFC-rPPG. Validation across diverse datasets and model variants is needed. A case study on a low-SaCo outlier further shows all four methods recovering consistently once an artefactual region is replaced, suggesting consistent SaCo behavior across attribution families in this illustrative case. Together, these metrics move XAI for rPPG toward auditable numerical evidence about spatial alignment and perturbation faithfulness, i.e. trustworthy rPPG XAI.
### Title:
          Natively Unlearnable Large Language Models
 - **Authors:** Gaurav R. Ghosal, Pratyush Maini, Aditi Raghunathan
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unlearning aims to remove the influence of specific training data sources, but this has proved challenging because the contributions of different sources are entangled within the model. Isolating source contributions to disjoint parameters makes removal easier, though it obstructs joint learning across sources. We propose NULLs (Natively Unlearnable LLMs), a model class that satisfies the two opposing goals of isolating source-specific contributions and learning jointly across sources, by training a set of shared backbone neurons alongside a pool of sparsely activated sinks. During training, information specific to a source naturally concentrates in its sinks while information shared across sources accumulates in the backbone. A source is then unlearned at deployment by disabling its corresponding sinks, with no gradient updates and no access to the retained data. We show that NULLs scales to Wikipedia's ~6M articles, isolating each as an independent source. Unlearning a single article removes knowledge specific to it while preserving facts shared with semantically related articles, closely matching retraining from scratch. We note that unlearning with NULLs is also robust: in a case study of unlearning the Harry Potter books, NULLs resists both adversarial extraction and relearning that reverses post-hoc unlearning. Finally, NULLs preserves general language capabilities, matching a standard transformer on downstream benchmarks. Together, these results suggest that source-level unlearning need not be an afterthought. It can be built natively into LLM training while retaining the benefits of shared representation learning.
### Title:
          How do Self-Supervised Remote Sensing Vision Models Transfer to Downstream Tasks?
 - **Authors:** Julia Romero, Qin Lv, Morteza Karimzadeh
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-supervised geospatial foundation models (GeoFMs) learn transferable representations from remote sensing data, but their downstream behavior is difficult to characterize. We study six representative GeoFMs spanning joint-embedding, reconstruction, and multimodal pretraining families, and evaluate transfer across classification, regression, and segmentation benchmarks under different label availability and downstream pipelines. We find that model rankings change across tasks and adaptation settings. Layerwise probing shows that, in most cases, task-relevant information is more accessible in intermediate transformer blocks compared to final-layer embeddings, and that GeoFMs exhibit distinct depthwise profiles. In segmentation case studies on PASTIS and Sen1Floods11, downstream adaptation settings such as decoder design and fine-tuning can be as impactful as the choice of GeoFM, and standard dense-prediction heads may be poorly aligned with how GeoFMs organize information over depth. Finally, CKA analysis on case studies shows that fine-tuning does not rewrite GeoFMs uniformly across depth, and the strongest changes are localized to the first linear layer of the MLP in ViT blocks. These results help explain why GeoFM rankings shift across benchmarks and motivate more representation-aware evaluation and adaptation strategies.
### Title:
          HiLo-Token: Input-Adaptive High-Low Frequency Token Compression for Efficient Image Editing
 - **Authors:** Haoran You, Yotam Nitzan, Lingzhi Zhang, Yifan Gong, Mang-Tik Chiu, Connelly Barnes, Yan Kang, Yuqian Zhou, Eli Shechtman, Sohrab Amirghodsi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Creative image editing tools, such as Photoshop's Remove or Generative Fill buttons, are central to everyday customer use and account for a major share of traffic in Photoshop and Lightroom. However, current generative AI models face significant latency challenges, which become even more pronounced when transitioning from convolution-based U-Nets to Diffusion Transformers (DiTs). In our evaluation on hundreds of representative image editing samples spanning a wide range of mask ratios, the DiT module alone accounts for an average of 73% of the total model latency, even after being distilled from 50 timesteps down to 8 timesteps. To tackle this challenge, we propose $\textbf{HiLo-Token}$, an input-adaptive token compression framework that allocates more token budget to high-frequency, rich-context regions while assigning fewer tokens to low-frequency areas. Specifically, for the editing region specified by the user mask, we retain all tokens within a dilated mask to preserve strong locality and contextual relevance. Outside the editing region, we introduce a simple yet effective high-frequency token selection strategy based on spatial frequency to capture important local details, while using tokens from a 16x downsampled image to represent low-frequency components and preserve the blurry but global structure. Extensive experiments on production-level evaluation data validate the effectiveness of the proposed method, achieving 3.13x, 2.59x, and 1.67x DiT speedups on A100-80GB for image editing tasks across small, medium, and large mask ratio categories with average ratios of 6.38%, 15.92%, and 35.36%, respectively, without any regression in generation quality.
### Title:
          An Attention-based Model for Robust Forecasting with Missing Modality
 - **Authors:** Zhitian Zhang, Wenjie Zi, Yunduz Rakhmangulova, Saghar Irandoust, Hossein Hajimirsadeghi, Thibaut Durand
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning with missing modalities is a fundamental challenge in multimodal robot learning, as real-world robotic systems often operate in environments with incomplete sensor data. Attention-based models are appealing for processing multimodal data because they can handle multiple modalities with a single backbone network. However, most multimodal models assume that all modalities are available during both training and inference, limiting their applicability in robotic perception and decision-making. In this paper, we introduce a multimodal model designed to handle missing modalities during both training and inference. The model is formulated as a conditional variational autoencoder (CVAE) and incorporates a transformer-based architecture that leverages attention mechanisms to learn a unified, fixed-dimensional representation, even when some modalities are missing. We show that our proposed model can be trained with missing modalities while approximating a robust representation of all modalities. We evaluate our approach on five multimodal datasets across two robot learning tasks: human trajectory prediction and robot manipulation forecasting. Experimental results demonstrate that our model effectively learns from incomplete data and is superior to prior multimodal fusion approaches.
### Title:
          ViT-Up: Faithful Feature Upsampling for Vision Transformers
 - **Authors:** Krispin Wandel, Jingchuan Wang, Hesheng Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformers (ViTs) have become a dominant architecture for visual representation learning, providing exceptionally strong and broadly reusable backbone features. However, ViTs are commonly operated on relatively small patch-token grids due to the quadratic cost of global self-attention, which creates a persistent bottleneck for dense prediction tasks such as semantic segmentation and depth estimation. This has motivated the development of task-agnostic feature upsamplers. While recent state-of-the-art methods produce visually sharp dense representations, their reliance on shallow image encoders for guided upsampling can introduce feature leakage, fragmentation, and blur. We introduce ViT-Up, an implicit feature upsampling framework that replaces external image guidance with layer-wise query construction from intermediate ViT hidden states. This enables feature prediction at arbitrary continuous image coordinates while preserving alignment with the backbone feature space. Experiments demonstrate that ViT-Up consistently outperforms state-of-the-art image-guided upsamplers across dense prediction and semantic correspondence. On DINOv3-S+, ViT-Up improves over prior methods by up to +2.07 mIoU on Cityscapes and +4.17 PCK@0.10 on SPair-71k. With the larger DINOv3-B backbone, these gains increase to +3.36 mIoU and +8.09 PCK@0.10, demonstrating that ViT-Up scales favorably with backbone capacity.
### Title:
          WAM4D: Fast 4D World Action Model via Spatial Register Tokens
 - **Authors:** Ying Li, Xiaobao Wei, Jiajun Cao, Hao Wang, Xiaowei Chi, Chengyu Bai, Qianpu Sun, Jiajun Li, Xiaojie Zhang, Jian Tang, Sirui Han, Shanghang Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World action models (WAMs) have recently shown promise in jointly modeling future observations and executable robot actions. However, most existing WAMs still operate in 2D video or latent spaces, where visually plausible rollouts miss the 3D spatial constraints and occluded contact geometry required for precise manipulation. While geometric foundation models offer strong priors for recovering dense 3D structure and motion from visual observations, forcing WAMs to predict the dense 4D representation introduces costly geometric decoding and slows down causal action generation. To address the trade-off, we present WAM4D, a fast 4D world action model that uses lightweight spatial register tokens as training-time future-depth readouts to transfer pretrained geometric priors into a causal video-action transformer, then removes the register branch for lightweight action inference. To prevent non-causal shortcuts, we further design causal mixture attention for the Mixture-of-Transformers (MoT) WAM backbone, defining modality-specific visibility among video, action, and geometry tokens. Comprehensive experiments on RoboTwin 2.0 and challenging real-world manipulation tasks show that WAM4D improves spatial consistency and achieves competitive action prediction while maintaining efficient inference.
### Title:
          ReactSim-Bench: Benchmarking Reactive Behavior World Model Simulation in Autonomous Driving
 - **Authors:** Zhiyuan Zhang, Yanlun Peng, Jianing Zhang, Xianda Guo, Zehan Huang, Haoran Liu, Qifeng Li, Shaofeng Zhang, Xiaosong Jia, Junchi Yan
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reactive capability is a key property of data-driven behavior world model simulators for autonomous driving simulation systems. With this capability, simulated world agents can respond feasibly to autonomous vehicle (AV) behaviors that differ from the log. However, existing behavior simulation benchmarks do not directly measure reactive capability. They often let the simulator jointly control the AV and surrounding agents and evaluate realism through log similarity or open-loop prediction metrics. In this work, we introduce ReactSim-Bench for evaluating the reactive capability of behavior world model simulation in autonomous driving. We decouple the control of agents and the AV, using AV behaviors that differ from the log and require agents to respond as independent AV inputs. To obtain these AV behaviors, we construct a pipeline that uses an AV planner model to generate candidate behaviors and filters the data using rules and manual verification. Collision metrics, map-based metrics, and kinematic feasibility metrics are used to evaluate the safety and rule compliance of reactive responses. We construct 2,636 test scenarios with three categories and conduct a systematic evaluation of state-of-the-art models across multiple architectures, including Transformer-based, diffusion-based, and next-token-prediction-based models. We further analyze how replan frequency affects performance and provide insights for future studies.
### Title:
          ShearFuse-UNet: Hadamard, DCT, and Shearlet Transform Fusion for Next-Day Wildfire Spread Prediction
 - **Authors:** Ene Meco, Yingyi Luo, Emadeldeen Hamdan, Adam Watts, Ahmet Enis Cetin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose ShearFuse-UNet, a lightweight and computationally efficient deep learning model for next-day wildfire spread prediction from multi-modal satellite data. The model integrates three complementary transform-domain branches inside each encoder block of a U-Net backbone: a 2D Fast Walsh-Hadamard Transform (WHT) branch, a 2D Discrete Cosine Transform (DCT) branch, and a cone-adapted digital Shearlet residual branch. The WHT and DCT branches establish orthogonal latent spaces with learnable spectral scaling and fixed soft-thresholding, while the Shearlet branch provides anisotropic, multi-directional feature decomposition that explicitly encodes the elongated edge structures characteristic of fire fronts. A learned SpectralFusion gate adaptively combines the WHT and DCT responses, and the Shearlet reconstruction is added as a residual. This three-branch design bears a loose structural analogy to transformer self-attention: the WHT and DCT branches provide complementary spectral representations that are adaptively fused, while the Shearlet branch contributes directional content through a residual pathway. Unlike self-attention, the proposed design relies on fixed mathematical transforms rather than learned projection operators, reducing parameter count and computational cost. Evaluated on the WildfireSpreadTS dataset, ShearFuse-UNet achieves an F1 score of 0.596 with only 267k parameters, outperforming a ResNet18-based U-Net (14M parameters, F1 = 0.589) and demonstrating a highly favorable accuracy-efficiency trade-off. Results on the Google Next-Day Wildfire Spread dataset further validate these findings across a different benchmark.
### Title:
          Agon: A Semi-Supervised Framework for Robust Satellite Interference Detection
 - **Authors:** Boyu Yang, Chunyu Yang, Zhe Chen, Kun Qiu, Yue Gao
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid expansion of non-geostationary orbit (NGSO) satellites alongside existing geostationary orbit (GSO) systems has intensified spectrum congestion and inter-system interference, placing stringent demands on real-time interference management to sustain reliable coexistence in next-generation communication networks. While existing machine learning (ML)-based reconstruction models have made strides, they remain constrained to an area under the curve (AUC) of 0.83 due to fixed thresholds, causing unacceptable false alarm rates that undermine critical link reliability. Additionally, their decoupled training paradigm neglects cross-domain dependencies, limiting time and frequency-domain AUCs to 0.83 and 0.71, respectively. To address these limitations, this paper introduces a semi-supervised satellite interference detection framework named Agon, employing a novel two-stage hybrid learning paradigm. Agon integrates masked autoencoder (MAE) pre-training of a dual attention transformer (DAT) with multi-task fine-tuning to optimize a direct binary classifier, effectively eliminating unstable thresholds. Furthermore, it incorporates high-order statistics (HOS)-augmented attention and wavelet regularization to bolster noise robustness and structural fidelity. Extensive validation on public NGSO-GSO dataset and a high-fidelity NGSO-NGSO dataset demonstrates that Agon achieves state-of-the-art (SOTA) detection performance, with a 25.3% improvement in AUC. Moreover, the multi-task learning (MTL) framework facilitates accurate modulation classification with accuracies exceeding 90%, while simultaneously maintaining optimal detection performance across diverse scenarios characterized by varying off-axis angles and interference-to-noise ratios (INRs).
### Title:
          Zeta: Dual Whitening for Matrix Optimization via Coordinate-Adaptive Preconditioning
 - **Authors:** Kaiwen Chen, Shuhai Zhang, Qiuwu Chen, Zimo Liu, Linxiao Li, Ying Sun, Yuchen Li, Yifan Zhang, Bo Han, Mingkui Tan
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large-scale neural network training increasingly relies on matrix-aware optimizers that exploit the structure of weight parameters beyond element-wise adaptation. However, existing matrix-aware methods such as Muon have an underappreciated vulnerability: their core operation, Newton-Schulz iteration, depends critically on input conditioning, yet the raw momentum matrices exhibit severe coordinate-wise scale heterogeneity. In this paper, we first verify this scale heterogeneity through a chi-square uniformity test, showing that intra-matrix scale imbalance is prevalent across Transformer layers and that coordinate whitening effectively corrects it. Motivated by this finding, we propose Zeta, a dual whitening optimizer that applies coordinate whitening and spectral whitening in a strictly ordered pipeline. The ordering is not a tunable choice but follows from a mathematical dependency: coordinate whitening establishes the statistical isotropy that spectral whitening requires to function reliably. We further prove that this dual pipeline strictly reduces orthogonalization error relative to pure spectral methods by improving the condition number of the input. Empirically, Zeta matches or surpasses strong baselines across language modeling (0.6B to 8B parameters), mixture-of-experts architectures, and vision tasks, demonstrating that resolving scale imbalance before orthogonalization leads to faster convergence and better generalization. Code is available at this https URL.
### Title:
          DRIVE: Distributional and Retrieval-Augmented Bidding with Value Evaluation
 - **Authors:** Miduo Cui, Haochen Wang, Shangqin Mao, Xun Yang, Qianlong Xie, Xingxing Wang, Xuri Ge, Ying Zhou, Zhiwei Xu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Auto-bidding is a core component of real-time advertising systems, where decisions must optimize long-term performance under budget and cost constraints, while online exploration is prohibitively risky. Offline reinforcement learning and, more recently, Transformer-based sequence modeling have shown promise for learning bidding policies from logged data, but their unimodal and purely parametric formulations often collapse multiple effective bidding strategies into suboptimal averaged actions and perform unreliably under sparse or long-tail traffic. To mitigate these limitations, we propose DRIVE (Distributional and Retrieval-Augmented Bidding with Value Evaluation), a unified Transformer-based framework that decouples candidate action generation from decision making for offline auto-bidding. DRIVE combines distributional action modeling, retrieval-augmented candidate generation from high-quality historical decisions, and value-based evaluation to select the most promising bid at inference time. Extensive experiments on AuctionNet and additional offline reinforcement learning benchmarks demonstrate that DRIVE consistently improves bidding performance and generalizes well across multiple Transformer-based methods.
### Title:
          HiST: A Hierarchical Sparse Transformer for Cross-Modal Spatial Transcriptomics Modeling
 - **Authors:** Weiyi Wu, Xinwen Xu, Xingjian Diao, Siting Li, Zhi Wei, Alma Andersson, Jiang Gui
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spatial transcriptomics (ST) links gene expression with tissue morphology but remains expensive and low-throughput, motivating surrogates that infer expression from routine histology. Whole-slide H&E-to-ST inference pairs a gigapixel image with gene measurements at a sparse, irregular set of locations, making multiscale modeling challenging without incurring dense-grid overhead or quadratic token mixing. We propose HiST, a hierarchical sparse transformer that treats measured locations as a lattice-indexed sparse field and builds a dyadic encoder--decoder directly on the active tissue footprint. HiST combines sparse window attention for local geometric correspondence with resolution-changing operators for rapid multiscale context integration. For a fixed window size, the dominant runtime and memory scale with the number of observed locations rather than the dense slide area. To mitigate slide-specific acquisition variation, HiST adds a bottlenecked global conditioning pathway via a \emph{slide calibration token} that summarizes slide-level context and conditions local representations. On a multi-organ benchmark spanning diverse tissues and acquisition sources, HiST improves predictive performance over recent baselines while reducing runtime and peak memory.
### Title:
          DIFF-ERO: A Conformance-Aware Loss for Deep Learning in Process Mining
 - **Authors:** Johannes De Smedt, Jari Peeperkorn, Artem Polyvyanyy, Jochen De Weerdt
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning has driven many recent advances in process analytics, especially for predictive and prescriptive monitoring. However, standard objectives such as cross-entropy optimize local next-step likelihoods and only implicitly capture control-flow structure. As a result, models can achieve high token-level accuracy while permitting imprecise global behaviour. We introduce DIFF-ERO, a conformance-aware loss function for deep learning models on process data. DIFF-ERO is a differentiable formulation of entropy-based stochastic conformance that incorporates control-flow information during training. Our approach constructs batch-level stochastic transition matrices with soft edge memberships, allowing structural precision and recall signals to directly inform backpropagation. The loss is model-agnostic and can be applied whenever the final representation parametrizes stochastic transitions. We instantiate DIFF-ERO in transformer encoder-decoder pipelines for next-activity prediction and use it jointly with cross-entropy to analyse its theoretical components with respect to convergence. Across benchmarks comparing other loss functions and targets, DIFF-ERO shows improved predictive performance where structure matters most while maintaining parity elsewhere. At the same time, the learned stochastic automaton converges towards the structural ground truth, indicating that the network internalizes process model structure.
### Title:
          Squeeze-Release: Iterative Pruning with Exact Structural Minimization
 - **Authors:** Roman Denkin, Ida Akerholm, Prashant Singh, Ida-Maria Sintorn
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unstructured pruning produces sparse weight tensors, but the standard implementation keeps tensor shapes unchanged so the deployed model is no smaller than before pruning. We present an exact structural rewrite, which we call minimization, that converts a masked network into a smaller dense network with the same forward function up to floating-point rounding. The Squeeze-Release cycle iterates pruning and minimization with an intermediate release step that re-enables the exact-zero positions inside the compacted tensors as small calibrated noise, turning otherwise wasted capacity back into trainable parameters. Successive cycles use that capacity to find structural redundancy a single pass cannot reach. We additionally introduce CompensatedLayerNorm, a function-preserving replacement for LayerNorm that extends minimization to channel reduction across LayerNorm-equipped residual streams. Squeeze-Release compresses the deployable network to 39x smaller than the unpruned model on a fully-connected model network and 14.8x smaller on modern CNN (ConvNeXt-Tiny), at comparable accuracy. In addition we prove that the rewrite can be extended to transformer architectures.
### Title:
          Can Deep Neural Networks Improve Compression of Very Large Scientific Data?
 - **Authors:** Muhannad Alhumaidi, Guozhong Li, Spiros Skiadopoulos, Panos Kalnis
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Error-bounded lossy compression is a fundamental technique for managing the rapidly growing volumes of scientific data produced by modern simulations and observational instruments. Most state-of-the-art-compressors follow a prediction-residual paradigm, where compression effectiveness depends on the quality of the predictor: more accurate predictions generate smaller residuals that are easier to compress. This observation raises a question: can modern machine learning models serve as superior predictors for scientific data compression? Answering this question directly is challenging because developing compression-specific ML predictors requires substantial resources. Instead, we leverage the climate domain where highly accurate pretrained weather forecasting foundation models already exist, making them an ideal testbed. We present a framework that integrates spatial and temporal deep learning models into a conventional error-bounded compression pipeline. The framework supports auto-regressive forecasting models and avoids error accumulation. Using ERA5 climate data as a representative large-scale scientific dataset, we evaluate three distinct ML predictors: a VAEformer-based codec (CRA5), a graph neural network forecaster (GraphCast), and a vision-transformer forecaster (Aurora), against the state-of-the-art compressor SZ3.1 under identical quantization and entropy-coding backends. Our evaluation over approximately 1.7 TB of data reveals a surprising result: although ML predictors generate more accurate predictions and can improve reconstruction quality by up to 91% while achieving up to 9.6x higher compression ratios for highly predictable variables, they do not improve overall dataset-level compression ratio. We show that prediction accuracy alone is insufficient: the spatial structure of the resulting residuals plays a decisive role in entropy coding efficiency.
### Title:
          A theoretical model for task routing in mixture-of-expert transformers
 - **Authors:** Yongli Xiang, Vinoth Nandakumar, Yunzhi Yao, Peike Li, Tongliang Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mixture-of-experts (MoE) layers enable the scaling of transformer models while keeping the inference compute fixed. While task-expert specialization has been observed in empirical studies of frontier MoE transformer models, existing theoretical work analyzes this using continuous mixture models that cannot be used to model natural language effectively. An important open question is to \textit{theoretically explain task-expert specialization in transformer MoE models using discrete models of language}. To address this, we represent structured knowledge via syntactic templates and finite key-value dictionaries, and prove formally that a single-layer MoE transformer can encode knowledge by using experts that specialize in the corresponding tasks. Our construction shows how queries are routed to unique, task-specific experts whose size depends solely on the intrinsic complexity of the given task (i.e. the combined size of its syntactic templates and factual dictionary). Our construction provides a theoretical support for empirical results on localized knowledge circuits in MoE models. We support our theoretical findings with experiments evaluating model performance under varying MoE loss functions.
### Title:
          Causal Object-Centric Models for Planning with Monte Carlo Tree Search
 - **Authors:** Rodion Vakhitov, Leonid Ugadiarov, Alexey Skrynnik, Aleksandr Panov
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce COMET (Causal Object-centric Model for Efficient Tree search), a model-based reinforcement learning algorithm that performs Monte Carlo Tree Search in a slot-structured latent space. COMET pairs a frozen unsupervised object-centric encoder with a transformer-based world model, in which actions are bound to objects through a novel action-slot fusion mechanism that is used in slot transition prediction. Policy and value heads use object-causal attention, modulating token interactions by learned per-slot relevance scores so that decision-making concentrates on task-relevant entities. COMET adds an explicit object-level inductive bias to MuZero-style latent planning. Across eight visually and dynamically diverse tasks from the Object-Centric Visual RL benchmark, ManiSkill, Robosuite, and VizDoom, COMET achieves a higher mean normalized score during the early stages of training compared to object-centric and monolithic baselines.
### Title:
          A Computational Audit of Demographic Association Encoding in ClinicalBERT Language Predictions
 - **Authors:** Kehinde Temitayo Soetan
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based clinical language models are increasingly integrated into high-stakes clinical decision support pipelines, yet the computational mechanisms through which demographic associations encoded in medical documentation propagate into model probability distributions remain empirically underspecified. We present a systematic computational audit of representational bias in ClinicalBERT (Alsentzer et al., 2019), a BERT-based model pretrained on MIMIC-III discharge summaries, employing two complementary probing methodologies: Log Probability Bias Analysis (LPBA), which quantifies demographic descriptor-induced shifts in masked token probability distributions across behavioral and evaluative semantic categories, and Masked Language Model-based analysis (MLM), which probes internal representational structure for demographic agency attribution encoding across 98 real clinical sentence templates and eight intersectional race-gender combinations. Corpus frequency analysis operationalizes the distinction between statistical disparity and bias amplification by benchmarking model outputs against empirical term frequencies in the MIMIC-III training corpus. Of 32 statistically significant findings, 65.6% contradict observed corpus distributions, rising to 80% for Black patients and 87.5% for agency attribution under MLM probing, providing direct empirical evidence that representational bias in ClinicalBERT operates predominantly through model-internal amplification rather than training data inheritance. Keywords: natural language processing, clinical documentation, algorithmic auditing, representational bias, health equity 1
### Title:
          NEST3D: A High-Resolution Multimodal Dataset of Sociable Weaver Tree Nests
 - **Authors:** Constanza A. Molina Catricheo, Simon Boeder, Ting-Jia Guo, Giacomo May, Clément Berthelot, Devis Tuia, Friedrich Fedor Reinhard, Fabio Remondino, Benjamin Risse
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sociable weaver nests function as complex ecological structures offering thermoregulatory microhabitats and sustaining diverse species; however, datasets used in prior studies lack fine-grained 3D structural detail. Producing usable and accurate 3D weaver nest data is challenging due to their irregular geometry and integration with complex host vegetation. We bridge this gap with an open-access, 1.4 TB multimodal drone dataset of 104 nest-bearing trees, comprising 27,945 RGB images, 111,780 multispectral images, approximately 781 million 3D points, and expert-annotated semantic segmentation labels. We benchmark semantic segmentation using KPConv, RandLA-Net, and Point Transformer V3, with PT-v3 achieving an mIoU of 86.35% on the test set. While the results demonstrate strong performance for transformer-based and point-wise methods, they also highlight architecture-dependent challenges, particularly for convolution-based approaches such as KPConv. By uniquely combining spectral, spatial, and structural information, the presented dataset advances 3D reconstruction, segmentation, and classification algorithms, enabling ecological applications from nest volume estimation to species conservation, and serves as a demanding benchmark that exposes architecture-dependent performance under extreme class imbalance.
### Title:
          Zero-shot generalization of transformer neural operators to larger domains
 - **Authors:** Armand de Villeroché, Sibo Cheng, Vincent Le Guen, Marc Bocquet, Rem-Sophia Mouradi, Patrick Armand, Alban Farchi, Patrick Massin
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based neural operators have shown remarkable performance for approximating solution operators of partial differential equations on complex geometries. However, existing approaches implicitly assume a fixed domain size, which limits their ability to generalize at inference. In this work, we investigate domain extension, namely zero-shot inference on spatial domains that are significantly larger than those encountered during training. We argue that this setting fundamentally requires spatial locality and translation equivariance. We propose to implement this locality via a decomposable bias in the attention logits computation, enabling finely controllable locality while remaining fully decomposable into query-key inner products and directly compatible with optimized attention kernels. Combined with rotary positional embeddings, it enables expressive embeddings with controllable spatial support without altering the transformer architecture. We empirically show that our approach substantially improves zero-shot generalization to larger domains across two PDE benchmarks and a 3D industrial atmospheric flow application. Our code and datasets are available at this https URL.
### Title:
          Realizing Native INT8 Compute for Diffusion Transformers on Consumer GPUs: A Fused INT8 GEMM Kernel for Ideogram 4.0
 - **Authors:** Ali Asaria, Tony Salomone, Deep Gandhi
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Post-training INT8 (W8A8) quantization of diffusion transformers is widely deployed as a speed optimization, yet on consumer Ampere GPUs it is frequently slower than the FP8 and NF4 alternatives it is meant to beat. We trace this to a software artifact: the production "INT8" forward quantizes weights and activations only to immediately dequantize them back to bf16 and run a bf16 matrix multiply, never engaging the GPU's INT8 tensor cores, so the hardware's compute advantage is left entirely unrealized. We close this gap with a single fused Triton INT8 GEMM (int8xint8->int32 on Ampere tensor cores, with per-token x per-channel dequantization and bias folded into the epilogue, autotuned per GEMM shape) dropped into the Ideogram 4.0 diffusion transformer's linear layers in place of the dequantize-to-bf16 path. In the kernel, the int8xint8->int32 accumulation is bit-exact against torch._int_mm and the dequantized output matches the reference at cosine similarity 1.0 with no NaNs, running 2.8-4.2x faster than bf16 per GEMM. End to end it delivers a ~1.1x (~9-10%) speedup at 768px, and at 1024px it generates an image in 156.5 s on a single RTX 3090, faster than the single-card NF4 (164.5 s) and FP8 (172.9 s) baselines, at no measurable quality cost on these point estimates (PickScore/CLIPScore). INT8 thus goes from the slowest variant to the fastest, and 1024px becomes single-GPU feasible. The primary speed criterion (beat FP8, by ~9.5%) is comfortably met; the NF4 margin (~4.9%, single-run n=4) is within run-to-run variance we did not quantify and is best read as consistent with meeting the stretch target. We close with an honest deployment map: the win is specific to consumer Ampere, and on A100 and B200 the same kernel loses to those cards' fast native bf16/FP8 paths.
### Title:
          A Comparative Study of Deep Learning Architectures for Multi-Horizon Behavioural Forecasting for Mobile Health
 - **Authors:** Pavlos Nicolaou, Kleanthis Malialis, Artemis Kontou, Panayiotis Kolios
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Wearable devices and smartphones generate rich behavioural time series that can support proactive health interventions, yet systematic comparisons of modern forecasting architectures for these data are lacking. In particular, it remains unclear how models generalise across populations, how different architectures respond to participant-level fine-tuning and how forecasting accuracy degrades across multi-day horizons. We benchmark six deep learning architectures, two zero-shot Foundation Models (FM) and statistical baselines on three public datasets encompassing over 800 participants, reporting per-feature metrics for step counts, screen time and sleep duration across 1-8 day horizons. We further conduct a per-feature personalisation study across all six architectures and assess FM transferability across dataset sizes and temporal granularities. Our key findings are: (i) no single architecture dominates, PatchTST leads among trained models while the three runners-up (TCN, MLP, Transformer) show no meaningful performance difference; (ii) the FM TimesFM matches or exceeds trained models zero-shot, especially in low-data regimes and (iii) participant-level fine-tuning reduces per-feature RMSE by 16-60\%, with sleep benefiting most and step counts least. These results provide practical guidance on architecture selection, FM applicability and personalisation strategies for mobile health forecasting. To the best of our knowledge, this is the first study to jointly evaluate modern deep learning, FMs and personalisation for multi-horizon behavioural forecasting from wearables.
### Title:
          SED:Lightweight Saliency prediction for Event-based data via Distillation
 - **Authors:** Romaric Mazna, Jean Martinet, Michele Magno
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Event-based saliency prediction has gained attention recently, as combining event cameras with saliency estimation can act as an upstream stage that naturally improves the efficiency of downstream eventbased perception at the edge. However, current approaches are either neuromorphic, underperforming on event-based saliency benchmarks, or too heavy for resource-constrained edge applications due to their reliance on transformers or 3D convolutions. Drawing inspiration from efficient convolutional modules, SED and aiming to exploit the temporal information in event data, we propose a lightweight network, trained through knowledge distillation, built on a Depthwise Spatio-Temporal Block (DSTconv) -- a factorization of the 3D depthwise separable convolution. Relative to its teacher, our model reduces the model size from 180 MB to 0.32 MB (562x) and the parameter count from 45M to 81k (554x), while matching or outperforming it on the N-DHF1K and N-UCF Sports datasets. Moreover, it generalizes strongly beyond its training distribution, transferring from synthetic to real event data where a model trained from scratch fails.
### Title:
          Listening with Attention: Entropy-Guided Explainability for Transformer-Based Audio Models
 - **Authors:** Ravi Ranjan, Utkarsh Grover, Xiaomin Lin, Agoritsa Polyzou
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based automatic speech recognition (ASR) models such as Whisper are highly accurate, but their predictions remain difficult to interpret. Existing explainable AI (XAI) methods often lack faithfulness and precise temporal grounding. We propose Listening with Entropy-guided Attention for Faithful explainability (LEAF-X), a model-intrinsic XAI framework for transformer-based ASR. LEAF-X combines entropy-guided attention weighting, multi-layer attention rollout, and optional causal ablations to identify low-entropy, high-impact heads and layers, producing sparse token-to-frame attributions. Unlike perturbation-based explainers or raw attention maps, LEAF-X exploits the internal structure of encoder-decoder and speech-augmented decoder-only models to generate explanations that better reflect model computation. Results show 32% improved faithfulness, 35-39% stronger locality/sparsity, and the most stable attributions, supporting more transparent and auditable ASR.
### Title:
          HumP-KD: A Hybrid Uncertainty-Aware Multi-Stage Progressive Knowledge Distillation Framework for Efficient Fire Classification
 - **Authors:** Mohammed Arif Mainuddin, Najifa Tabassum, Omar Ibne Shahid, Riasat Khan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-time fire classification systems require models that are simultaneously accurate, computationally efficient, and deployable on resource-constrained hardware. This work proposes \textbf{HumP-KD}, a Hybrid Uncertainty-aware Multi-stage Progressive Knowledge Distillation framework for efficient fire classification. Two datasets, FlameVision and Dataset-II, containing 8,600 and 31,309 images, are used. Various CNN and transformer baselines are applied under standard preprocessing, online augmentation, Gaussian noise and motion blur robustness conditions. The proposed HumP-KD model distills knowledge from two frozen heterogeneous transformer teachers, Swin-Tiny and ViT-Base, along with their Meta-MLP ensemble, into a lightweight MobileViT-S student via three tightly integrated components. Hierarchical Progressive Knowledge Distillation employs a Hierarchical Feature Builder. It generates a fused spatial attention mask to guide distillation toward discriminative regions selectively. Multi-Stage Knowledge Distillation progressively activates three distillation stages across training. On Dataset-II, HumP-KD achieves a mean F1 score of $0.9876 \pm 0.0063$ across 10 independent trials, significantly outperforming the MobileViT-S baseline trained without distillation ($0.9537 \pm 0.0351$), with statistical significance confirmed by both independent t-test ($p = 0.0195$) and Wilcoxon signed-rank test ($W = 1$, $p = 0.0039$). The proposed method also demonstrates strong generalization across datasets and robustness under degraded visual conditions. The student model retains only 4.94M parameters and 19.01Mb model size, representing a $5.7\times$ parameter reduction over Swin-Tiny and a $17.5\times$ reduction over ViT-Base, while achieving 37.72 CPU FPS, making it suitable for real-time deployment.
### Title:
          RepFusion: Leveraging Multimodal Priors for Denoising in Representation Space
 - **Authors:** Xichen Pan, Aashu Singh, Satya Narayan Shukla, Xiangjun Fan, Shlok Kumar Mishra, Saining Xie
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) are widely used in text-to-image (T2I) systems, but they are typically limited to text encoding, while denoising is handled by newly trained generative backbones. The emergence of representation autoencoders (RAEs) shifts the generation target toward semantically structured visual representations, creating a latent space that is more compatible with pretrained LLM priors. Inspired by multimodal LLMs (MLLMs), where an MLP projector is sufficient to align clean visual representations with a pretrained LLM, we repurpose the MLLM itself as a noisy representation encoder, extending this mechanism from clean to noisy inputs. We present RepFusion, which uses the resulting MLLM outputs as the conditioning signal for a diffusion transformer. In controlled comparisons at similar inference budgets, RepFusion outperforms baselines that devote comparable capacity to newly initialized denoisers. These results demonstrate that MLLMs provide strong priors for denoising visual representations and that, by conditioning on evolving noisy representations, test-time compute can be productively spent on repeated MLLM conditioning in modern T2I systems.
### Title:
          RATS! Patches Talk Through Registers: Emergent Parts in Register Attention Transformers
 - **Authors:** Timing Yang, Predrag Neskovic, Jansen Seheult, Wenchao Han, Anand Bhattad, Alan Yuille, Feng Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 When humans see a bird, they recognize far more than just "bird" -- they see a head, wings, and talons, a structured assembly of reusable parts that can be identified across every bird they have ever seen. We ask whether a self-supervised visual model can discover the same compositional structure on its own. To this end, we propose RATS (Register Attention Transformers), which decomposes the classification token into N learnable register tokens that route patch information through an L->N->N->L bottleneck via a three-step compress-communicate-broadcast attention. The N registers are partitioned across the H attention heads, so that registers assigned to different heads do not interact with each other. Without auxiliary losses or part annotations, each register spontaneously specializes into a proto-semantic region whose emerging structure resembles object parts. RATS surpasses all baselines by +12 mIoU on average across five segmentation benchmarks, with consistent gains on ADE20K (+1.11 mIoU) and COCO (+0.2 AP^m). Its register dictionary further exhibits part-level consistency and semantic proximity across related categories. Our results suggest that RATS may provide a useful architectural prior for structured and interpretable visual representation learning.
## Keyword: autonomous driving
### Title:
          Multi-Agent Embodied Autonomous Driving: From V2X Information Exchange to Shared World Models
 - **Authors:** Senkang Hu, Zhengru Fang, Yihang Tao, Zihan Fang, Sam Tak Wu Kwong, Yuguang Fang
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving is shifting from isolated vehicle intelligence toward multi-agent embodied systems that share perception, infer intent, and coordinate action under uncertainty. This survey examines this transition through the lens of Shared World Models (SWMs): predictive cross-agent representations maintained across vehicles, infrastructure, and other traffic participants. We review more than 380 publications spanning vehicle-to-everything (V2X) communication, collaborative perception, inter-agent cognition, cooperative planning, end-to-end cooperative driving, and simulation and data engines for closed-loop validation. The organizing question is how exchanged observations become aligned state, intent-aware interaction, and coordinated downstream action. Across the surveyed literature, evaluation remains concentrated in simulation, curated benchmarks, and offline protocols. Foundation-model-based coordination also lacks verified real-time safety guarantees in open traffic. These gaps motivate key research priorities for multi-agent embodied autonomous driving (MAEAD): verifiable shared-state maintenance, robust intent and plan alignment, and safe coordinated action under communication, latency, and deployment constraints.
### Title:
          RT-VLA: Real-Time Vision-Language-Action Models via Knowledge Distillation
 - **Authors:** Xiangyu Huang, Zhenlin Hua, Han Zhou, Shounak Sural, Ragunathan Rajkumar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models have shown strong potential for end-to-end autonomous driving by jointly modeling visual perception, language reasoning, explainability and action prediction. However, their large vision-language backbones and reasoning modules introduce substantial inference latency and thereby prevent their deployment in the unforgiving reality of the road networks. We propose RT-VLA, a lightweight, distilled VLA model that transfers the driving and reasoning capabilities of the state-of-the-art SimLingo model into a compact student through multi-level supervised distillation. RT-VLA preserves language-based reasoning and supports post-hoc explanation through offline language analysis of safety-critical driving moments without adding latency to real-time control. Compared to the SimLingo teacher, RT-VLA maintains competitive closed-loop driving and language reasoning performance while reducing inference time by 44.8X in vision-only mode and 7.9X in vision+language mode. These results suggest that supervised distillation is a practical approach for building real-time, explainable VLA-style autonomous driving models.
### Title:
          From Attacks to Curricula: Learnability-Guided Adversarial Training for Safe Autonomous Driving
 - **Authors:** Yuewen Mei, Tong Nie, Jie Sun, Haotian Shi, Wei Ma, Jian Sun
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Closed-loop adversarial training improves autonomous driving safety by exposing policies to rare safety-critical scenarios. Standard pipelines first generate adversarial scenarios and then sample them for policy optimization. However, most existing frameworks remain attack-oriented: collision-driven generators often synthesize unsolvable extreme situations, which can degrade learning, while heuristic samplers ignore the evolving capability of the driving policy, causing sample inefficiency and delayed convergence. We propose AlignADV, a learnability-guided closed-loop adversarial training framework that converts adversarial scenarios into resolvable and capability-aligned curricula. First, we reformulate adversarial scenario generation as a preference alignment problem and employ direct preference optimization to guide the generator toward critical yet resolvable scenarios. Second, we introduce behavioral fingerprints to capture the intrinsic characteristics of the evolving policy and construct a multi-modal capability prediction model that estimates policy performance without expensive closed-loop simulations. By combining resolvability-aligned scenarios with capability predictions, AlignADV develops a dynamic curriculum sampling mechanism that prioritizes scenarios targeting the current policy's vulnerabilities. Experiments on the Waymo Open Motion Dataset demonstrate that AlignADV improves convergence efficiency and final performance, reducing training steps by up to 40.6 percent compared with baseline methods while lowering collision rate and improving route completion under both normal and adversarial traffic conditions. These results highlight a shift from attack-oriented scenario generation to learnability-guided policy improvement, offering a principled direction for safer and more efficient autonomous driving training. Project page: this https URL.
### Title:
          ReactSim-Bench: Benchmarking Reactive Behavior World Model Simulation in Autonomous Driving
 - **Authors:** Zhiyuan Zhang, Yanlun Peng, Jianing Zhang, Xianda Guo, Zehan Huang, Haoran Liu, Qifeng Li, Shaofeng Zhang, Xiaosong Jia, Junchi Yan
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reactive capability is a key property of data-driven behavior world model simulators for autonomous driving simulation systems. With this capability, simulated world agents can respond feasibly to autonomous vehicle (AV) behaviors that differ from the log. However, existing behavior simulation benchmarks do not directly measure reactive capability. They often let the simulator jointly control the AV and surrounding agents and evaluate realism through log similarity or open-loop prediction metrics. In this work, we introduce ReactSim-Bench for evaluating the reactive capability of behavior world model simulation in autonomous driving. We decouple the control of agents and the AV, using AV behaviors that differ from the log and require agents to respond as independent AV inputs. To obtain these AV behaviors, we construct a pipeline that uses an AV planner model to generate candidate behaviors and filters the data using rules and manual verification. Collision metrics, map-based metrics, and kinematic feasibility metrics are used to evaluate the safety and rule compliance of reactive responses. We construct 2,636 test scenarios with three categories and conduct a systematic evaluation of state-of-the-art models across multiple architectures, including Transformer-based, diffusion-based, and next-token-prediction-based models. We further analyze how replan frequency affects performance and provide insights for future studies.
