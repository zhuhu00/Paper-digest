# Showing new listings for Wednesday, 10 June 2026
## Keyword: SLAM
### Title:
          Information-Preserving Continuous Occupancy Mapping with Variance-Weighted Submap Joining
 - **Authors:** Zhuhua Bai, Yingyu Wang, Liang Zhao, Shoudong Huang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large-scale SLAM remains challenging due to accumulated trajectory drift and the increasing computational cost of maintaining global consistency. Submap joining alleviates these issues by constructing locally consistent submaps and subsequently fusing them into a global map. However, existing occupancy-based submap joining methods operate on discrete grids, resulting in non-smooth gradients during optimization and neglecting the uncertainty associated with occupancy estimates. We propose the first continuous probabilistic submap joining framework that jointly optimizes submap poses and a global occupancy field in the latent log-odds space. The framework employs an information-preserving sparse Bayesian formulation that compresses raw occupancy observations into sufficient-statistic log-odds tuples while retaining the posterior information of the original observations. This yields closed-form predictive mean and variance estimates for occupancy mapping, which directly enable a submap joining formulation with analytical Jacobians, leading to more accurate submap joining and yielding a closed-form optimal global map upon pose convergence. Experiments on both simulated and large-scale real-world datasets demonstrate that the proposed method achieves higher pose accuracy and improved global consistency than state-of-the-art grid-based submap joining approaches, while producing more compact map representations and better-calibrated uncertainty estimates than existing continuous occupancy mapping methods.
## Keyword: odometry
There is no result 
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          WHU-Infra3D: A Full-stack Multi-modal Dataset and Benchmark for 3D Roadside Infrastructure Inventory
 - **Authors:** Chong Liu, Luxuan Fu, Xuyu Feng, Zhen Dong, Bisheng Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The paradigm of digital twin cities is shifting from coarse visual mapping toward more precise and actionable digitization of urban assets. However, existing datasets predominantly focus on coarse visual perception, lacking the strict multi-modal alignment and attribute and status diagnosis required for automated infrastructure maintenance. To bridge this gap, we introduce WHU-Infra3D, a large-scale, multi-modal benchmark dataset dedicated to roadside infrastructure inventory. Covering 53.8 km across three cities, WHU-Infra3D uniquely integrates panoramic imagery and LiDAR point clouds with rigorous 2D-3D instance association and cross-frame tracking. Comprising over 175k multi-view 2D bounding boxes alongside thousands of 3D infrastructure instances, the dataset provides over 181k detailed attribute and status annotations (e.g., rust, occlusion) to empower operational health assessment. We establish comprehensive baselines across five core tasks: 2D detection, 2D cross-view matching, 3D geo-identification, 3D point cloud segmentation, and attribute recognition. Extensive evaluations expose significant cross-city domain gaps and inherent vulnerabilities of current models on long-tailed defective statuses, establishing WHU-Infra3D as an essential testbed for advancing scalable, AI-driven urban infrastructure inventory and lifecycle management. The WHU-Infra3D dataset is available at this https URL.
### Title:
          Generalized-CVO: Fast and Correspondence-Free Local Point Cloud Registration with Second Order Riemannian Optimization
 - **Authors:** Ray Zhang, Marcus Greiff, Thomas Lew, John Subosits
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose a fast and correspondence-free local point cloud registration method that leverages geometric surface structure and reproducing kernel Hilbert space (RKHS) embeddings. The method represents point clouds as continuous functions with point-wise anisotropic kernels that encode local geometry. This formulation improves alignment along surface normals while relaxing alignment along tangential directions. To solve the resulting registration problem, we propose a second-order on-manifold optimization scheme with approximate Riemannian Hessians, achieving a speedup of up to 10x over the first-order solvers used in prior correspondence-free RKHS-based methods. We demonstrate improved frame-to-frame LiDAR and RGB-D tracking accuracy across diverse indoor and outdoor datasets. On a LiDAR tracking registration task in the driving domain, we achieve a reduction of $>55\%$ in both translational and rotational drift in challenging feature-sparse environments. On object registration benchmarks, we show improved robustness over ICP-based methods and further gains when refining global initialization, particularly under moderate misalignment.
### Title:
          Resilient Navigation for Autonomous Farm Robots by Leveraging Jerk-Augmented Models with IMU-Only Disturbance Rejection
 - **Authors:** Batu Candan, Mohammed Atallah, Simone Servadio, Saeed Arabi
 - **Subjects:** Subjects:
Robotics (cs.RO); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Precise state estimation for navigation of autonomous agricultural robots is often compromised by sensor outages (GNSS/LiDAR/Visual) and high-frequency vibrations inherent in off-road environments. This paper proposes a robust navigation algorithm based on a jerk-augmented Extended Kalman Filter (EKF) integrated with a Multiple Tuning Factor (MTF) adaptation method. Unlike standard EKF approaches that assume constant measurement noise, our method dynamically adjusts the measurement covariance matrix in real-time, allowing the system to cope with sudden disturbances and sensor outliers. We evaluate the algorithm using real-world data from a Salin247 autonomous robot. Results demonstrate that jerk-augmentation combined with MTF adaptation significantly reduces 3D position Root Mean Square Error (RMSE) compared to baseline EKF models, providing superior dead-reckoning capabilities.
### Title:
          A Distributed Multi-UGV Exploration Framework With Loop-Aware Planning and Descriptor-Aided Localization in Resource-Limited Environments
 - **Authors:** Zhiwei Li, Haiou Liu, Xijun Zhao, Ji Li, Yingze Wang, Boyang Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust and efficient cooperative exploration with multiple unmanned ground vehicles (UGVs) in unknown, GPSdenied, and bandwidth-limited environments without prior maps remains challenging, as localization drift degrades map consistency and induces redundant coverage. This paper presents a fully distributed exploration framework that couples descriptoraided inter-UGV loop closure with loop-aware hierarchical planning while enabling autonomous localization and exploration. We develop a lightweight LiDAR global descriptor with range-image prealignment to enable robust cross-UGV place recognition under large yaw and lateral variations, and use verified loop closures to maintain globally consistent trajectories and a sparse topological representation. We further introduce an uncertainty-aware crossUGV loop-closure selection module that scores candidate loop closures under pose uncertainty and retains high-utility loop closures as planning anchors for global task allocation and local route refinement. Simulations and real-UGV experiments show that the loop-closure module achieves AR@1/AR@1% of 89.9%/95.5%, distributed optimization reduces absolute trajectory error, the system substantially reduces two-way communication volume, and the overall framework reduces exploration time and travel distance by 15% and 14%, respectively, compared with an mTSP baseline.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          3D-CoS: A New 3D Reconstruction Paradigm Based on VLM Code Synthesis
 - **Authors:** Yuhao Wang, Puyi Wang, Linjie Li, Zhengyuan Yang, Kevin Qinghong Lin, Yu Cheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Most recent 3D reconstruction and editing systems operate on implicit and explicit representations such as NeRF, point clouds, or meshes. While these representations enable high-fidelity rendering, they are fundamentally low-level and hard to control programmatically. In contrast, we propose and systematically evaluate a new 3D reconstruction paradigm, 3D Code Synthesis (3D-CoS), where 3D assets are constructed as executable Blender code, a programmatic and interpretable medium. To assess how well current VLMs can use code to represent 3D objects, we evaluate representative open-source and closed-source VLMs in code-based reconstruction under a unified protocol. We further introduce a suite of structured code-synthesis workflows, including blueprint-based planning, Retrieval-Augmented Generation (RAG) over Blender API documentation, few-shot geometric demonstrations, and a component-level Agent workflow for part-wise code generation. To demonstrate the unique advantages of this representation, we further evaluate localized text-driven modifications and compare our code-based edits with a point-cloud-based 3D editing baseline. Our study shows that code as a 3D representation offers strong controllability and locality, yielding stronger edit fidelity and better preservation of unedited regions in our targeted editing evaluation. Our work also analyzes the potential of this paradigm, delineates the current capability frontier of VLMs for programmatic 3D modeling, and highlights code synthesis as a promising direction for editable 3D reconstruction.
## Keyword: mapping
### Title:
          Human-AI Coordination Zones: A Framework for Designing Human-in-the-Loop Experiences with Agentic AI
 - **Authors:** James Pierce, Vaiva Kalnikaitė, Siddharth Gupta, Brian Granger
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC); Artificial Intelligence (cs.AI); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As generative and agentic AI becomes embedded in everyday products, practitioners face a persistent challenge: how to design human-AI coordination -- the ongoing mutual adjustment between users and AI systems as mediate through interfaces-that supports usability, trust, and safety. Existing resources offer high-level principles ("be transparent," "maintain user control") or low-level UI patterns, but there is a lack of mid-level design knowledge bridging the two. Through landscape and artifact analysis of 60 commercial AI applications, we introduce a framework defining human-AI coordination as the interplay of three dimensions: salience (how prominently AI is presented), involvement (what users can do to engage AI), and activity (what AI actually does). We contribute mid-level tools including coordination zones (done-for-me, done-under-me, done-with-me, done-without-me), an input taxonomy (prompted, sparked, inferred, layered), coordination curves for mapping user journeys, and design patterns demonstrating the generative capacity of the framework. The framework can be applied generatively to design experiences, analytically to evaluate existing ones, and communicatively to articulate ideas across stakeholders.
### Title:
          ECHO: Explainable Co-editing with Human-in-the-loop Operations for Presentation Refinement
 - **Authors:** Yu Fu, Yongqi Kang, Yujia Zhou, Yong Zhao
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Authoring and refining presentation slides is a highly time-consuming core task in academic and business domains. While generative AI tools have lowered the barrier for creating initial drafts, their "black-box, one-way generation" paradigm severely deprives users of fine-grained control. Through a formative study (N=10), we identified "trial-and-error anxiety" and "inconsistent cross-page formatting" as primary bottlenecks in human-AI co-creation. Consequently, we present ECHO, an interactive system based on multimodal intent grounding and explainable operation plans. ECHO enables precise local edits via a "natural language + visual selection" paradigm, utilizing a decoupled "Plan-Confirm-Execute" loop and dynamic memory mechanisms to transform implicit AI intents into highly controllable layout co-creation. To systematically evaluate document refinement, we propose the CoEdit-Eval framework. Objective evaluations across multiple foundation models (e.g., GPT-5, GLM-4.7) demonstrate that while baselines uniformly fail in intent mapping (0% accuracy) and spatial grounding (0% Hit@1), the ECHO architecture boosts Target Hit@1 to 55%--85% depending on the base model. Furthermore, integrating Vision-Language Models (VLMs) effectively resolves spatial ambiguities -- achieving significant win rates in LLM blind evaluations -- and our Undo mechanism guarantees 100% physical file consistency (MD5 hash). Finally, a controlled study with 14 participants shows that ECHO significantly reduces cognitive workload (NASA-TLX scores dropped by 20.8%, from 82.6 to 65.4) and reveals the dynamic evolution of human control allocation across different cognitive tasks.
### Title:
          Uncertainty-aware Multi-fidelity Closure via Conditional Normalizing Flows
 - **Authors:** Jice Zeng, Shady E. Ahmed, David Barajas-Solano, Panos Stinis
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computational Physics (physics.comp-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reduced-order models (ROMs) provide an efficient surrogate for complex multiscale systems, but their predictive accuracy is often compromised by truncation errors and the inadequate representation of interactions between resolved and unresolved scales. The missing effect of truncated (unresolved) scales on ROM (resolved) scales is often denoted as the closure problem. In this work, we formulate ROM closure modeling as a multi-fidelity (MF) learning problem and propose an uncertainty-aware MF framework based on conditional normalizing flow to enhance ROM predictive accuracy. The proposed approach learns a probabilistic mapping from low-fidelity (LF) ROM coefficients to high-fidelity (HF) coefficients, thereby improving predictive fidelity while quantifying the uncertainty associated with the learned closure. Two correction strategies are investigated: direct learning, in which HF coefficients are predicted directly from LF inputs, and residual learning, which learns the discrepancy between LF and HF coefficients and uses it to recover the corrected HF solution. The framework is demonstrated on a vortex merging problem governed by the two-dimensional Navier Stokes equations. Results show that both correction strategies improve ROM accuracy over uncorrected ROM, with residual learning achieving consistently better performance than direct learning. Moreover, the two proposed deep generative model-based strategies provide uncertainty quantification for the corrected ROM coefficients, which is critical for assessing prediction confidence and supporting the reliable use of ROMs in practical applications.
### Title:
          Toward Calibrated, Fair, and accurate Deepfake Detection
 - **Authors:** Ryan Brown, Chris Russell
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Cryptography and Security (cs.CR); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deepfake detectors show large performance gaps across demographic groups. Existing fairness approaches require demographic labels, retraining, or sacrifice accuracy. We introduce Face-Fairness (FF), a plug-and-play framework for bias mitigation. Our primary contribution, Face-Feature Tuning (FFT), is the first demographic label-free fairness method demonstrated for deepfake detection: a lightweight calibrator that performs a logit remapping conditioned on frozen face embeddings. We complement FFT with two variants: FF-Max, which maximizes worst-group accuracy when demographics are available, and FF-Discover, which does the same with embedding-discovered groups. Across in-domain and cross-dataset test settings, FF consistently reduces FPR/TPR gaps and improves minimum group accuracy while maintaining (often improving) overall accuracy. The approach is detector-agnostic, adds negligible runtime overhead, and requires no access to identity attributes.
### Title:
          WHU-Infra3D: A Full-stack Multi-modal Dataset and Benchmark for 3D Roadside Infrastructure Inventory
 - **Authors:** Chong Liu, Luxuan Fu, Xuyu Feng, Zhen Dong, Bisheng Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The paradigm of digital twin cities is shifting from coarse visual mapping toward more precise and actionable digitization of urban assets. However, existing datasets predominantly focus on coarse visual perception, lacking the strict multi-modal alignment and attribute and status diagnosis required for automated infrastructure maintenance. To bridge this gap, we introduce WHU-Infra3D, a large-scale, multi-modal benchmark dataset dedicated to roadside infrastructure inventory. Covering 53.8 km across three cities, WHU-Infra3D uniquely integrates panoramic imagery and LiDAR point clouds with rigorous 2D-3D instance association and cross-frame tracking. Comprising over 175k multi-view 2D bounding boxes alongside thousands of 3D infrastructure instances, the dataset provides over 181k detailed attribute and status annotations (e.g., rust, occlusion) to empower operational health assessment. We establish comprehensive baselines across five core tasks: 2D detection, 2D cross-view matching, 3D geo-identification, 3D point cloud segmentation, and attribute recognition. Extensive evaluations expose significant cross-city domain gaps and inherent vulnerabilities of current models on long-tailed defective statuses, establishing WHU-Infra3D as an essential testbed for advancing scalable, AI-driven urban infrastructure inventory and lifecycle management. The WHU-Infra3D dataset is available at this https URL.
### Title:
          Bypassing Copyright Protection in Diffusion-based Customization via Two-Stage Latent Feature Optimization
 - **Authors:** Ziang Xu, Wenbo Yu, Hongyao Yu, Hao Fang, Jiawei Kong, Bin Chen, Hao Wu, Shu-Tao Xia, Zhiyong Wu
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the growing concerns over copyright infringement in diffusion-based customization, adversarial attacks have emerged as a prominent defense strategy to prevent malicious content forgery in personalized image generation. However, current defenses typically introduce persistent perturbations in the latent space of Latent Diffusion Models (LDMs), which remain susceptible to adaptive bypasses by adversaries. In this paper, we introduce Two-Stage Latent Feature Optimization (TS-LFO), an efficient and effective copyright-stealing attack against protected diffusion-based customization. We begin by observing that existing defenses primarily disrupt the mapping between input images and their latent representations, thereby degrading the model's ability to produce personalized outputs. To counteract this, TS-LFO restores the broken mapping through a two-stage optimization process. In the Latent Denoising Stage, we enhance semantic consistency between latent codes and input images by jointly minimizing a Latent-Image Alignment Loss and a Latent Diffusion Loss with timestep-dependent weights, effectively suppressing the high-frequency noise introduced by defenses. In the Latent Reconstruction Stage, we recover low-frequency semantic information using pixel-level constraints to refine the latent features. Extensive experiments show that TS-LFO consistently bypasses state-of-the-art (SOTA) copyright defenses and outperforms SOTA copyright attacks such as DiffPure, GrIDPure and IMPRESS across diverse settings.
### Title:
          Learning Where to Simulate: Generative Active Sampling for Online PDE Surrogate Training
 - **Authors:** Pierre Cesar (DATAMOVE), Sofya Dymchenko (DATAMOVE), Abhishek Purandare (DATAMOVE), Bruno Raffin (DATAMOVE)
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Data-driven PDE surrogates are trained with data produced by numerical PDE solvers. However, when the surrogate's goal is to generalize across a wide range of PDE configurations (e.g., initial conditions and physical coefficients), generating a representative training set is non-trivial. Uniform sampling of configuration parameters often under-represents trajectories exhibiting challenging dynamics, leading to high prediction errors and large error variance in the trained surrogate. Online training, where data generation and surrogate training are coupled, offers a natural advantage by allowing solver parameters to be steered on-the-fly. To efficiently exploit this capability, we introduce Online Generative Active Sampling (OGAS), an active learning method that reactively learns the relationship between configuration parameters and surrogate performance to control the sampling distribution. OGAS trains a fast diffusion model in parallel to the surrogate to act as a conditional sampler, mapping a surrogate-derived difficulty signal (e.g., loss or uncertainty) to configuration parameters. By actively drawing target signals from a prior biased toward high difficulty, OGAS continuously steers data generation toward challenging regimes without delaying the training workflow. We evaluate OGAS across 2D PDEs with distinct challenging dynamics (Kuramoto-Sivashinsky, Navier-Stokes, Gray-Scott) and up to 308 parameters, using multiple surrogate architectures. Across all settings, OGAS consistently improves tail statistics, yielding substantial reductions in errors above the 99th percentile and overall error dispersion compared to uniform sampling. While prioritizing challenging trajectories introduces a trade-off with average error, OGAS effectively ensures worst-case reliability of trained surrogates with negligible wall-time overhead.
### Title:
          Toward Intelligent Prefetching: A Survey on Complex Memory Access Prediction Techniques
 - **Authors:** Sheel Sindhu Manohar
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Data prefetching is a critical technique for bridging the processor-memory performance gap by predicting future memory accesses and retrieving data into on-chip caches before demand. While traditional prefetchers based on next-line, stride, and correlation heuristics perform well for regular access patterns, they are fundamentally inadequate for the irregular, data-dependent patterns prevalent in modern workloads such as graph analytics, sparse matrix computations, and pointer-intensive applications. This survey presents a systematic review of papers using a PRISMA-guided selection methodology. We propose a structured taxonomy that organizes prefetching techniques across three dimensions: locality type, including spatial and temporal locality; implementation layer, including hardware, software, and hybrid approaches; and, for the increasingly important class of ML-based prefetchers, learning paradigm, including supervised, reinforcement, and unsupervised learning, paired with training mode, including online and offline training. Through a multi-dimensional comparative analysis of ML-based prefetchers evaluated across storage overhead, accuracy, inference latency, hardware feasibility, and generalization ability, we identify three key findings: an accuracy-overhead Pareto frontier defined by model class, a natural architectural mapping between model complexity and cache hierarchy level, and a fundamental tension between runtime adaptability and model capacity that motivates hierarchical ensemble architectures.
### Title:
          TestMap: Evidence Infrastructure for Foundation-Model-Assisted Test Generation
 - **Authors:** Hunter Leary, Luke Hanuska, Chris Brown
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Foundation models (FMs) can generate plausible unit tests, but determining whether those tests are correct, useful, maintainable, and worth integrating remains difficult. Generated tests must be mapped to the code they target, inserted into real projects, built, executed, measured against the baseline suite, repaired when necessary, and compared across models and generation strategies. This validation process is fragmented across build systems, test runners, coverage tools, mutation tools, static analyzers, and experiment scripts. The problem is especially important because generated tests are both code artifacts and validation artifacts: they must themselves be validated before they can be trusted as evidence about the system under test. This paper presents TestMap, an open-source infrastructure prototype that automates evidence-backed foundation-model-assisted test generation for C#/.NET repositories. TestMap supports repository analysis, source-test mapping, baseline execution, code metric collection, test smell detection, coverage measurement, mutation testing, model-guided test generation, validation, repair, and repository-specific experiment tracking. Rather than reporting only final passing tests, TestMap records the lifecycle of each generated candidate, including failed, repaired, low-impact, and evidence positive outcomes. These intermediate outcomes can reveal model limitations, missing context, repair cost, toolchain inefficiencies, or possible faults in the system under test. Using TestMap as a design case, we describe the architecture and evidence model needed to make generated tests observable, repeatable, and comparable across repositories, models, prompts, and generation strategies. We conclude with lessons learned and open challenges, including oracle and assertion quality, metric attribution, test maintainability, flakiness, execution cost, and developer acceptance.
### Title:
          Rethinking Embodied Navigation via Relational Inductive Bias
 - **Authors:** Weitao An, Chenghao Xu, Xu Yang, Cheng Deng
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Object navigation requires an agent to locate a target in an unknown environment through visual observations. Existing methods typically rely on open-vocabulary detectors or vision-language models (VLMs) to answer where to search, but often overlook what not to trust - which semantic cues are unreliable. Open-vocabulary perception is prone to systematic misleading evidence: false positives, outdated static priors, and repeated failed exploration due to lack of embodied verification, which contaminates mapping and decision-making. Such errors are rooted in structured object relations in real-world scenes. To address this, we propose DB-Nav, a framework that reshapes the search space via dual relational biases. It factorizes target-centric relations into an Activation Bias (propagates contextual evidence) and an Inhibition Bias (suppresses unreliable regions via perceptual confusion and action-level falsification). These biases are unified into a Relational Activation-Inhibition Exploration Graph that modulates frontier exploration values using online observations and failed accesses. Experiments on ObjectNav benchmarks show that DB-Nav significantly outperforms existing methods in success rate (SR) and Success weighted by Path Length (SPL), offering a lightweight, interpretable, and robust navigation framework without costly online VLM reasoning.
### Title:
          Speech Meets ELF: Audio Conditional Continuous-Target Diffusion for Speech Recognition and Translation
 - **Authors:** Xuanchen Li, Tianrui Wang, Yuheng Lu, Zikang Huang, Yu Jiang, Chenghan Lin, Chenrui Cui, Ziyang Ma, Xingyu Ma, Chunyu Qiang, Guochen Yu, Xie Chen, Longbiao Wang, Jianwu Dang
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Speech-to-text (S2T) systems for recognition (ASR) and translation (S2TT) typically generate discrete text tokens. In contrast, continuous-target language modelling performs generation in a continuous space, yet its potential for S2T remains unexplored. To bridge this gap, we propose ELF-S2T, an audio-conditioned continuous-target generative model for S2T. Built upon the pre-trained Embedded Language Flows (ELF) backbone, ELF-S2T processes speech via a frozen Whisper encoder and a single linear projector, prepending the resulting audio condition to the noisy text latent for in-context, flow-matching denoising. To prevent the model from over-relying on its pre-trained text context, we introduce audio forcing during training, and further amplify the audio condition via classifier-free guidance at inference. Experiments on LibriSpeech and CoVoST2 show that ELF-S2T achieves competitive ASR and S2TT performance. Crucially, our error analysis reveals that, although ASR and S2TT errors look very different on the surface, both stem from the same underlying cause, a close distance confusion in the continuous latent space. This finding naturally aligns with the continuous representation generation paradigm, indicating a common semantic mapping process beneath recognition and translation. Our code and pretrained models are publicly available at this https URL.
### Title:
          SIDInspector: A Mapping-First Diagnostic Resource for Semantic-ID Tokenizers
 - **Authors:** Jiandong Ding, Heng Chang, Huijie Qin, Tianying Liu
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic-ID (\sid) tokenizers are increasingly reused as standalone artifacts in generative recommendation: an exported item-to-code mapping becomes the address space that a later sequence generator must use. These mappings rarely come with a common inspection interface, so coverage gaps, full-code aliasing, behaviorally weak prefixes, tail compression, and prefix fan-out are often found only after downstream training. We present \tool, a mapping-first diagnostic resource for \sid tokenizer artifacts. \tool defines a small adapter contract over item mappings, metadata, interactions, and optional generator traces; validates the contract; and reports mapping-level probes for utilization, aliasing, neighborhood alignment, popularity allocation, and structural cost, with hooks for temporal churn and generator traces. \tool reports inspectable artifact profiles before downstream leaderboard scores. The released resource covers four tokenizer artifact lines: a same-item GRID/RQ-KMeans-style and ReSID/GAOQ contrast on 23,742 Musical items, plus released LETTER and LC-Rec item-index artifacts. In the Musical contrast, the GRID-style feature-text export has 3,749 unique full codes and a 0.977 full-code aliasing rate, while ReSID/GAOQ is aliasing-free in its exported mapping. Yet the strongest prefix--co-occurrence alignment comes from a deterministic category-prefix control, not from either learned export row (0.447 versus 0.154 and 0.055--0.080), showing that addressability and behaviorally meaningful prefixes should be inspected separately. Cross-domain, fixed-reranker, and mechanism-probe checks support the same diagnostic direction: prefix alignment is a candidate-exposure signal, while final ranking quality remains a downstream model question.
### Title:
          Information-Preserving Continuous Occupancy Mapping with Variance-Weighted Submap Joining
 - **Authors:** Zhuhua Bai, Yingyu Wang, Liang Zhao, Shoudong Huang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large-scale SLAM remains challenging due to accumulated trajectory drift and the increasing computational cost of maintaining global consistency. Submap joining alleviates these issues by constructing locally consistent submaps and subsequently fusing them into a global map. However, existing occupancy-based submap joining methods operate on discrete grids, resulting in non-smooth gradients during optimization and neglecting the uncertainty associated with occupancy estimates. We propose the first continuous probabilistic submap joining framework that jointly optimizes submap poses and a global occupancy field in the latent log-odds space. The framework employs an information-preserving sparse Bayesian formulation that compresses raw occupancy observations into sufficient-statistic log-odds tuples while retaining the posterior information of the original observations. This yields closed-form predictive mean and variance estimates for occupancy mapping, which directly enable a submap joining formulation with analytical Jacobians, leading to more accurate submap joining and yielding a closed-form optimal global map upon pose convergence. Experiments on both simulated and large-scale real-world datasets demonstrate that the proposed method achieves higher pose accuracy and improved global consistency than state-of-the-art grid-based submap joining approaches, while producing more compact map representations and better-calibrated uncertainty estimates than existing continuous occupancy mapping methods.
### Title:
          UPLOTS: A Unified Pretrained Language Model for Constrained Time-series Generation
 - **Authors:** Du Yin, Hao Xue, Jinliang Deng, Yang Yang, Shuang Ao, Arian Prabowo, Flora Salim
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In time-series generation, existing approaches typically handcraft ortrain a separate model for each dataset, which hinders their scalability and fails to leverage shared temporal structures across domains. To address this fragmentation, we propose UPLOTS, a Unified, Prompt-guided Language model framework fOr constrained Time-Series Generation across diverse domains. Instead of building task-specific models, UPLOTS leverages a single pre-trained transformer backbone guided by learned constraint prompts, enabling on-demand generation with precise pattern control. One key innovation is our dynamic multi-dataset loss re-weighting and prompt-to-pattern mapping, which allows UPLOTS to internalize diverse temporal structures during training and conditionally generate them at inference. We evaluate UPLOTS on four real-world benchmarks and multiple constraint settings, including peak-period, calendar, load-level, and volatility patterns. Additional held-out constraint-combination and downstream forecasting experiments further demonstrate that UPLOTS generalizes beyond the original peak-pattern setting and improves data augmentation under scarce real-data regimes. Our code and baselines are available at anonymous github repo: this https URL.
### Title:
          LC-QAT: Data-Efficient 2-Bit QAT for LLMs via Linear-Constrained Vector Quantization
 - **Authors:** Haoyu Wang, Xingyu Yu, Haiyan Zhao, Fengxiang Wang, Xu Han
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Quantization-aware training (QAT) is essential for extremely low-bit large language models (LLMs). Current QAT methods are mainly based on scalar quantization (SQ), which enables efficient optimization but suffers from severe performance degradation at 2-bit precision. On the other hand, vector quantization (VQ) provides substantially higher representational capacity, but its discrete codebook lookup prevents end-to-end training. We propose LC-QAT, a 2-bit weight-only VQ-QAT framework that represents quantized weights via a learned affine mapping over discrete vectors, which yields a high-quality PTQ initialization and enables fully differentiable end-to-end optimization without explicit codebook lookup in the training forward pass. This strong post-training initialization makes LC-QAT highly data-efficient. Experiments across diverse LLMs demonstrate that LC-QAT consistently outperforms state-of-the-art QAT methods while using only 0.1%--10% of the training data. Our results establish LC-QAT as a practical and scalable solution for extreme low-bit model deployment.
### Title:
          Fast and Highly Expressive Policy Learning for Offline Reinforcement Learning via Bootstrapped Flow Q-Learning
 - **Authors:** Thanh Nguyen, Tri Ton, Hongbin Choe, Tung M. Luu, Chang D. Yoo
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion-based Q-learning has emerged as a powerful paradigm for offline reinforcement learning, but its reliance on multi-step denoising makes both training and inference computationally expensive and brittle. Recent efforts to accelerate diffusion Q-learning toward single-step action generation typically introduce auxiliary networks, policy distillation, or multi-phase training, which frequently compromise simplicity, stability, or performance. To address these limitations, we introduce Bootstrapped Flow Q-Learning (BFQ), a novel framework that enables accurate single-step action generation during both training and inference, without auxiliary networks or distillation procedures. BFQ adopts a divide-and-conquer view of the displacement vector along the flow path: it begins by learning short-range displacements that can be accurately estimated from the Flow Matching marginal velocity, and bootstraps these components to directly learn a noise-to-action mapping in a single step. This formulation eliminates multi-step denoising, resulting in a learning procedure that is substantially faster, simpler, and more robust. Extensive D4RL evaluations show that BFQ improves performance while significantly reducing computational cost compared to multi-step diffusion baselines, demonstrating that single-step action generation suffices for high-performance offline Reinforcement Learning.
### Title:
          Envision4D: Envisioning Visual Futures via Feed-forward 4D Gaussian Splatting for Autonomous Driving
 - **Authors:** Qi Song, Yifei He, Chi Zhang, Zheng Fu, Xuhe Zhao, Mengmeng Yang, Kun Jiang, Rui Huang, Diange Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Forecasting the future evolution of dynamic scenes is crucial in autonomous driving. However, existing feed-forward paradigms are primarily designed for interpolation. When extended to future extrapolation, they suffer from ghosting artifacts under large displacements and are constrained by simplified motion assumptions or strict future priors. To overcome these challenges, we propose Envision4D, a fully self-supervised feed-forward framework for pose-free future extrapolation. Specifically, we introduce a Future Pose Prediction module that infers future camera parameters via an iterative denoising process. Furthermore, to capture non-linear dynamics, we propose In-layer Temporal Attention and employ Conditioned Motion Lifting, which transforms the highly uncertain extrapolation process into robust relational mappings. Finally, a Progressive Training Strategy is utilized to stabilize unsupervised motion learning against error accumulation. Extensive experiments demonstrate that Envision4D achieves state-of-the-art performance, significantly outperforming existing methods in future view synthesis.
### Title:
          Vector Map as Language: Toward Unified Remote Sensing Vector Mapping
 - **Authors:** Yinglong Yan, Yunkai Yang, Haoyi Wang, Wei Fu, Linshan Wu, Honghu Pan, Shaobo Xia, Shanghang Zhang, Hao Chen, Leyuan Fang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Remote sensing vector mapping aims to generate structured maps of geospatial entities, such as buildings, roads, and water bodies, from remote sensing imagery. In practice, vector maps usually contain multiple category layers and heterogeneous entity structures, requiring a unified model for diverse mapping needs. However, existing methods typically represent vector objects as polygons or graphs, making them suitable only for specific categories: polygons poorly capture topological relations, while graphs often blur instance boundaries. We observe that language, as a natural medium for human communication, offers a flexible and expressive representation that can accommodate heterogeneous map elements, including geometry, semantics, and topolog. Motivated by this insight, we propose Vector Map as Language (VecLang), a unified paradigm that reformulates multiclass vector mapping as structured text generation. VecLang encodes the common elements of different geospatial entities into a GeoJSON-like vector language, enabling cross-category modeling within a shared textual format. To generate this language reliably, we design a progressive vision-language mapping framework that first localizes vectorization units and then generates structured map elements. We further introduce Hierarchical Vector Language Optimization, which uses reinforcement learning to improve syntax validity, content fidelity, and map executability. We also build VecMap-Bench with 54K images and 800K instances, supporting training and evaluation across standard and generalization settings. Extensive experiments demonstrate that VecLang handles both single-class and multiclass vector mapping while achieving strong cross-dataset and open-vocabulary generalization. The model and dataset are publicly available at this https URL.
### Title:
          Beyond APIs: Probing the Limits of MLLMs in Physical Tool Use
 - **Authors:** Zhixin Ma, Yutong Zhou, Yongqi Li, Chong-Wah Ngo, Wenjie Li
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal Large Language Models (MLLMs) excel at utilizing digital APIs and increasingly serve as the "brain" of embodied AI, instructing robots to interact with the physical world. In such embodied settings, a central capability is the use of physical tools, which underpins MLLMs' ability to assist humans in real-world tasks. Despite the importance, MLLMs' proficiency in physical tool use remains largely unexplored. To address this gap, we introduce PhysTool-Bench, the first physical tool-use benchmark designed to evaluate MLLMs' ability to comprehend real-world scenarios, identify physical tools, and plan their use. PhysTool-Bench comprises 2,510 queries over 2,678 real-world physical tools spanning diverse domains, including manufacturing, electrical work, agriculture, and healthcare. Concretely, models are evaluated along two primary dimensions: 1) recognizing all physical tools present in the scene, and 2) planning the tool selection and use sequence based on the instruction and visual context. Across 13 leading MLLMs, even the strongest model (Gemini-3.1-Pro) identifies only 58.7% of tools in a scene and completes merely 21.0% of queries end-to-end. Our analysis reveals a two-level deficit: MLLMs struggle to perceive tools in realistic scenes, and the much larger drop at the planning stage further indicates a lack of functional commonsense for mapping perceived tools onto task semantics, pinpointing a critical bottleneck for the development of practical embodied AI.
### Title:
          K-Forcing: Joint Next-K-Token Decoding via Push-Forward Language Modeling
 - **Authors:** Zhiwei Tang, Yuanyu He, Yizheng Han, Wangbo Zhao, Jiasheng Tang, Fan Wang, Bohan Zhuang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autoregressive (AR) language modeling is the dominant paradigm for text generation, yet its sequential token-by-token decoding makes inference memory-bound and inefficient. Existing acceleration approaches, such as speculative decoding and diffusion language models, can yield speedups under certain conditions but do not directly address high-load batch serving--the scenario most critical for industrial-scale deployment. We introduce K-Forcing, a push-forward language modeling paradigm for joint next-k-token decoding. K-Forcing distills an existing AR model into a conditional push-forward mapping--one that transforms independent uniform noise variables into a joint sample of multiple future tokens in a single forward pass. This design preserves fixed-length outputs, reuses the AR teacher backbone, and remains compatible with standard AR serving infrastructure. We train this mapping via progressive self-forcing distillation, which gradually expands the prediction window while enabling the student to closely match the sequence distribution of the AR teacher. We evaluate K-Forcing on LM1B and OpenWebText using a standard causal Transformer backbone. When aggressively configured to generate k = 4 tokens per forward pass, K-Forcing delivers approximately 2.4-3.5x speedup across different batch sizes, while incurring modest quality degradation relative to its AR teacher. As inference increasingly dominates the lifetime compute cost of modern LLMs, K-Forcing offers a promising route toward accelerating AR generation under real-world high-load deployment.
### Title:
          Encoding the Euler Characteristic Transform
 - **Authors:** Nello Blaser, Odin Hoff Gardaa, Lars M. Salbu, Elena Xinyi Wang, Bastian Rieck
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Algebraic Topology (math.AT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Euler Characteristic Curve (ECC) records the Euler characteristic of a linearly embedded cell complex as a function of filtration height in a given direction, and the Euler Characteristic Transform (ECT) is the injective shape descriptor obtained by collecting ECCs over many directions. How the ECT is encoded for a neural network is itself an inductive bias, conventionally fixed by discretizing each ECC. We introduce a continuous encoding: for each direction and each vertex it records the net Euler-characteristic change attributed to that vertex, producing a per-direction token sequence that a small transformer maps to a feature vector. We separate the resulting pipeline into two stages on orthogonal axes: an ECC encoder that acts within each direction, mapping its curve to a fixed-length vector, and an ECT representation that acts across directions, aggregating the per-direction vectors into one. We study six ECT representation architectures spanning a range of inductive biases, from a structure-agnostic feedforward baseline to convolutional and complex-valued models that preserve equivariance under planar rotations. Across six classification benchmarks covering point clouds, graphs, cubical complexes, and meshes, the continuous encoding improves accuracy on five of six datasets, and control experiments attribute the gain to the tokenization itself rather than to the added transformer capacity. The representation architecture matters less than the encoding, and the payoff from its inductive biases depends on the encoding: a feedforward network performs best under continuous encoding but is less robust under discretization than convolutional architectures.
### Title:
          Optimal Post-Training Quantization Scales and Where to Find Them
 - **Authors:** Juan Amboage, Pablo Monteagudo-Lago, Ian Colbert, Giuseppe Franco, Nicholas Fraser
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Post-training quantization (PTQ) compresses large language models by mapping weights to low-bit representations. The scaling factor that defines the quantization grid is typically chosen using simple, data-free heuristics. In this work, we present PiSO (Piecewise Scale Optimization), an algorithm that leverages calibration data to compute the optimal channel-wise weight scales exactly and efficiently under round-to-nearest quantization. PiSO partitions the scale search space into finitely many intervals on which the objective admits a closed-form minimizer. We extend PiSO to group-wise quantization via principled heuristics and propose effective strategies for interleaving scale optimization with error correction. Experiments on Llama and Qwen models across multiple model sizes and target weight bit-widths demonstrate consistent improvements in perplexity and downstream zero-shot accuracy, both standalone and combined with error correction. In particular, we observe increased benefits as the target bit-width narrows and quantization becomes more challenging.
### Title:
          AllDayNav: Lifelong Navigation via Real-World Reinforcement Learning
 - **Authors:** Hang Yin, Yinan Liang, Jiazhao Zhang, Jiahang Liu, Minghan Li, Zhizheng Zhang, He Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Lifelong embodied navigation in dynamic environments requires robots to form persistent scene understanding from fragmentary observations, which remains difficult for existing methods that rely on explicit maps or scene graphs and struggle to generalize beyond structured settings. We propose AllDayNav, a lifelong self-learning navigation framework that implicitly encodes scene dynamics into the billion-scale parameters of a large model via reinforcement learning, powered by a self-evolving multimodal memory that maintains and updates visual keyframes, semantic descriptions, and temporal context while autonomously generating open-vocabulary instructions, image goals, and structured rewards. Experiments in both synthetic and real-world environments across cross-room, cross-episode, and cross-task scenarios show that AllDayNav achieves success rates approaching $100\%$ and consistently surpasses strong map-based, VLM, and RL baselines in path efficiency and robustness, demonstrating implicit, memory-driven reinforcement learning as a scalable alternative to explicit mapping for reliable lifelong navigation.
### Title:
          Multi-UAV Active Sensing with Information Gain-based Planning and Belief Fusion
 - **Authors:** S. Habibi, L. Marques
 - **Subjects:** Subjects:
Robotics (cs.RO); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unmanned aerial vehicles (UAVs) are increasingly used for active sensing and information gathering in spatially distributed environments. Their performance, however, is constrained by limited flight time, sensing uncertainty, and the trade-off between spatial coverage and observation accuracy. This paper presents a real-world validation of a multi-UAV active sensing framework for probabilistic binary terrain mapping, with precision agriculture used as the application case. The environment is represented as a probabilistic belief map, where spatial dependencies are modeled through a factor-graph formulation. UAV decision making is guided by Information Gain based Informative Path Planning (IGbIPP), and the approach is compared with Random Walk and Sweep coverage path planning baselines using both synthetic terrains and real UAV-derived agricultural imagery. The study also evaluates spatial correlation weights and several probabilistic belief-fusion rules for multi-UAV information sharing. Results show that IGbIPP reduces entropy and mapping error more effectively than the baselines, while a wider field of view improves real-world coverage and map accuracy. The results further show that simple equal or biased spatial weights can be more robust than adaptive weights, and that Bayesian, log-odds, and Dempster--Shafer fusion achieve the best cooperative mapping performance. These findings highlight the importance of uncertainty-driven planning, sensing geometry, spatial modeling, and probabilistic fusion for real-world UAV-based active sensing.
### Title:
          Making Software Meaningful
 - **Authors:** Eagon Meng, Abutalib Namazov, Carmel Schare, Alcino Cunha, Daniel Jackson
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adopting a single measure can improve the usability, modularity and accountability of software: a commitment to explicit meaning. This entails constructing and agreeing upon a representation of the behavior of the software, as observed in the domain of application. The phenomena comprising this behavior become a vocabulary that grounds all discourse about the software, among all stakeholders, and for all artifacts and activities. These phenomena are individuals; actions they participate in; and facts that result from actions. They can be organized, by partitioning the set of actions, into concepts, offering larger units of meaning. Examples of exploiting meaning are given in three areas: designing for usability (by aligning user and designer on a single shared meaning); generating modular code with LLMs (by mapping units of meaning to units of code, achieving not only modularity but also legibility); and making agents accountable (by having them adhere to a code of conduct that defines their intended behavior).
### Title:
          Coset Ensemble Decoder for Quantum Error Correction with Algorithm-Hardware Co-Design
 - **Authors:** Shuang Liang, Jubo Xu, Giulio Bassanino, Qianzhou Wang, Yidong Zhou, Yuncheng Lu, Zhiwen Mo, Paul H. J. Kelly, Bo Yuan, Wayne Luk, Hongxiang Fan
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Quantum Physics (quant-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable large-scale quantum computation relies on fault-tolerant architectures, where quantum error correction (QEC) continuously extracts and decodes error syndromes in real time. A critical component in QEC is the decoder, a classical subsystem that must simultaneously deliver high logical accuracy and ultra-low latency. This paper presents a novel algorithm-hardware co-design that improves the accuracy-latency trade-off over existing approaches such as vanilla Minimum-Weight Perfect Matching (MWPM) and Union-Find (UF) decoders. At the algorithmic level, we introduce coset ensemble decoding, which improves UF decoding by explicitly exploiting logically equivalent cosets. Our method performs ensemble forest exploration to generate multiple coset-consistent candidates and aggregates them to approximate coset-level maximum-likelihood decoding. We further reduce computational and memory complexity via reverse-order elimination and lossless graph compression, without sacrificing accuracy. At the hardware level, we design a domain-specific architecture that temporally reuses resources, avoiding the code-distance-proportional resource growth in prior spatial architectures. Several optimizations, such as multi-bank memory hashing and hierarchical ID mapping, are proposed to mitigate pipeline stalls and memory conflicts under highly concurrent access patterns. Under a circuit-level depolarizing noise model, our co-design approach achieves a better accuracy-latency trade-off than prior MWPM- and UF-based decoders, while reducing FPGA LUT consumption by up to 8.2 times compared with reported UF-based decoder resources. The tunable candidate number further exposes a flexible design knob, enabling users to tailor decoding performance to the requirements of different fault-tolerant workloads. Our implementation is publicly available at this https URL.
### Title:
          Anchors that Don't Lift: Understanding Supply Chain Driven Kernel Lock-In and Governance-Mediated Mitigation Strategies in SOHO Devices
 - **Authors:** Ritwik Badola, Rajdeep Ghosh, Ashita Gupta, Chester Rebeiro, Mainack Mondal
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Small Office/Home Office (SOHO) devices are widely popular, yet often attacked due to security vulnerabilities in their firmware, affecting thousands of devices. These security vulnerabilities often stem from outdated Linux kernel versions included in SOHO device firmware. Naturally, prior work audited the extent and impact of this issue by simple Linux version extraction and version number based vulnerability mapping. However, it is unclear how many of these anticipated vulnerabilities actually exist in the heavily customized SOHO kernels and if there are any barriers towards updating Linux kernels in SOHO firmwares. To address this gap, we uncover actual kernel-related vulnerabilities found in 306 SOHO devices using a high-precision template-based CVE detection mechanism on GPL source releases of more than 900 firmwares from these devices. Next, as a first, we traced the supply chain of these vulnerable SOHO devices at scale and identify kernel lock-in as a significant security issue -- SOHO vendors are effectively locked to specific (often older) kernel versions due to the system-on-chip (SoC) SDKs they use. This kernel lock-in produces a vulnerability debt that is inherited along the supply chain from SoC vendor to firmware creators (ODM/OEM) to router/IP-camera vendor and ultimately borne by end users. All five SoC vendors in our dataset had used SDKs with Linux kernels that had reached EoL more than a year before their usage in a SOHO device. Finally, we explore the mitigation-potential of individual, regulatory and community governance by analyzing social media posts, regulations and community efforts. Our results show that regulation compliance is insufficient and only SoC vendors who engage with communities for kernel upgradation offered a viable path towards mitigation. The data and code for this work is available at this https URL
## Keyword: localization
### Title:
          Disjoint or Overlapping? Inference Windowing for Reconstruction-Based Time Series Anomaly Detection
 - **Authors:** Guillaume Coulaud (UM, IROKO), Reza Akbarinia (IROKO), Florent Masseglia (IROKO)
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reconstruction-based methods are widely used for time series anomaly detection, where models are trained to reconstruct subsequences, and anomalies are identified through reconstruction errors. However, reported results are often hard to compare due to heterogeneous evaluation practices and underspecified inference procedures. In this paper, we revisit reconstruction-based anomaly detection in the univariate offline setting and study the role of the inference stride, which controls whether subsequences are processed as disjoint windows or with overlap. We propose a unified training, tuning, and multi-seed evaluation protocol on the curated TSB-AD benchmark, and study how overlapping inference affects anomaly detection performance for a range of reconstruction models, including PCA-based baselines, DLinear, an AutoEncoder, TimesNet, and Transformer variants. The results show that across all models, overlapping windows yield consistent improvements, with average relative gain up to +28%, and can alter method rankings. We further analyze variability across datasets, random seeds, and hyperparameter configurations. Finally, we complement the benchmark study with an evaluation on the full UCR archive using localization criteria aligned with sliding-window reconstruction. Overall, our results highlight that reconstruction-based anomaly detection performance depends not only on model architecture and training, but also on inference choices, motivating a clear and reproducible protocol. Our results show that reconstructionbased baselines achieve strong performance on both TSB-AD and UCR benchmarks, supporting them as competitive and practical approaches for univariate time series anomaly detection.
### Title:
          Multi-task LLMs for Bug Classification: Efficient Inference with Auxiliary Decoding Heads
 - **Authors:** Nikolai Rozanov
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid adoption of LLM-powered code generation has dramatically accelerated software development, yet effective verification methods remain severely underdeveloped. Existing bug localization techniques are either prohibitively expensive, requiring minutes of agentic reasoning and thousands of generated tokens per file, and/or operate at coarse function-level granularity unsuitable for precise debugging. While works that focus on line-level granularity and are more light-weight are often limited in their performance or context size. We introduce a novel line-level bug localization approach that addresses these limitations through three key contributions: (1) a token alignment algorithm that overcomes fundamental tokenization challenges in previous work, (2) a lightweight multi-task LLM for bug localization (MLC) enabling efficient line-level bug classification, and (3) an optimized training recipe for multi-line prediction. Our method achieves state-of-the-art performance among similar setups on line-level bug localization with full-file context. At the same time we reach comparable performance to agentic approaches on Defects4J and PypiBugs benchmarks while reducing inference latency by orders of magnitudes, requiring only a single generated token per file. We further demonstrate strong generalization by introducing and evaluating on a small out-of-domain evaluation datasets in Python. We will open source our code, models, and datasets upon acceptance.
### Title:
          Improving PET/CT-Based Whole-Body Lesion Segmentation Using Prediction Uncertainty-Augmented Models
 - **Authors:** Bashirul Azam Biswas, Biratal Raj Wagle, Zhihan Yang, Marc A. Seltzer, Matthew E. Maeder, James B. Yu, Indrani Bhattacharya
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate lesion segmentation from whole-body Positron Emission Tomography (PET)/Computed Tomography (CT) scans is essential for cancer staging and treatment planning. PET provides functional metabolic information with different radiotracers, while CT offers anatomical localization. Lesion delineation from PET/CT imaging is clinically challenging due to subtle imaging features, confounders, and inter-reader variability. Existing deep learning approaches suffer from training-related stochasticity, inconsistent predictions, missed lesions in high tumor-burden cases, and lack uncertainty quantification, limiting their clinical reliability. Using nnU-Net as a baseline, we propose an uncertainty-aware framework for whole-body PET/CT lesion segmentation that integrates (1) Bayesian ensembling to reduce training stochasticity, (2) voxel-wise uncertainty quantification with epistemic and aleatoric decomposition, and (3) epistemic uncertainty-augmented training to improve lesion detection. Two public datasets, AutoPET-III (1,611 scans) and Deep-PSMA (200 scans), comprising FDG and PSMA studies across multiple cancer types, are used for training and evaluation. Bayesian ensembling improves robustness and performance over deterministic nnU-Net models on the unseen AutoPET-III test set. Uncertainty maps highlight regions of model disagreement and correlate with misclassifications, particularly false positives. Uncertainty-augmented training improves lesion recovery at the cost of increased FPVol, reflecting a precision-recall trade-off. A case-adaptive routing strategy further improves Dice by selecting between the base and augmented models. To our knowledge, this is the first study to systematically investigate uncertainty quantification in multi-tracer, pan-cancer PET/CT segmentation and to combine Bayesian ensembling with uncertainty-aware modeling for this task.
### Title:
          Fusing Satellite Imagery and Planimetric Maps for Cross-View Localization
 - **Authors:** Quang Long Ho Ngo, Zimin Xia, Alexandre Alahi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current cross-view localization methods predominantly rely on satellite imagery as the aerial modality. Although recent work explores planimetric maps (e.g., OpenStreetMap tiles), these approaches often lag in performance. Yet both modalities are widely available and possess complementary properties. Satellite images are closer to ground-level camera imagery, offering finer detail, whereas planimetric maps contain annotated objects (e.g., streetlamps) and remain informative in areas where the ground is occluded, such as by foliage. Despite this, only one prior work provides an end-to-end method to fuse the two modalities, and it does not demonstrate their potential within state-of-the-art methods. To combine the strengths of both modalities, we propose a new fusion module that augments standard encoders and demonstrates that integrating satellite imagery with planimetric maps improves state-of-the-art single-modality methods. The module comprises (i) cross-modal conditioning, which processes each modality's encoding with awareness of the other, and (ii) a patch-level fusion rule that controls the granularity of information exchange. We achieve state-of-the-art results, reducing the mean localization error by 30.13\%. Qualitatively, the fusion adaptively selects the more informative modality, improving overall accuracy.
### Title:
          Time-frequency localization of bird calls in dense soundscapes
 - **Authors:** Simen Hexeberg, Fanghui Tong, Hari Vishnu, Mandar Chitre
 - **Subjects:** Subjects:
Sound (cs.SD); Computer Vision and Pattern Recognition (cs.CV); Quantitative Methods (q-bio.QM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Passive acoustic monitoring enables large-scale observation of wildlife, but most bioacoustic classifiers only predict species presence in a time window without localizing vocalizations precisely in time or frequency, limiting downstream analyses. We formulate bird vocalization detection as an object detection task on spectrograms and train YOLO11 models to localize bird calls in dense tropical soundscapes from Singapore. We additionally introduce an open-source browser-based annotation tool and propose Intersection over Minimum (IoMin), an evaluation metric that better handles ambiguous acoustic boundaries than standard IoU and is better suited to the problem at hand. The best YOLO model nearly doubles baseline performance on in-distribution soundscapes from Singapore (81.8% vs. 42.1% IoMin@50 F1-score) while still outperforming the baseline on unseen out-of-distribution recordings from Hawaii (58.6% vs. 48.6%). These results suggest that object detection frameworks are a promising approach to time-frequency localization of animal vocalizations in complex soundscapes.
### Title:
          Geometric Coastline Localization using Vision-Language Models
 - **Authors:** Rafia Malik, Bernhard Pfahringer, Karin Bryan, Mark Dickson, Eibe Frank
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Coastline detection in remote sensing imagery is commonly formulated as a pixel-wise segmentation problem, where the final coastline is extracted from a predicted mask through post-processing. This formulation relegates coastline geometry, the primary representation used in coastal change analysis, to a secondary artifact rather than the learning objective. In practice, coastlines are defined by geomorphic proxies such as vegetation lines, dune toes, or cliff edges, rather than an instantaneous land-water boundary often used in pixel-based segmentation approaches. In this work, we revisit coastline extraction from a representation perspective and formulate the task as geometric boundary localization. We use the New Zealand Coastal Change Dataset (NZCCD) and high-resolution aerial imagery from Land Information New Zealand (LINZ) to develop CoastlineVLM-7B, a vision-language model (VLM) built on the GeoChat-7B/LLaVA-1.5 architecture that jointly performs coastline presence detection, proxy-type classification, and coastline grounding. The model directly predicts a coastline as a polyline rather than a dense segmentation mask. We evaluate CoastlineVLM-7B against segmentation baselines under strict one-pixel boundary supervision. Results show that geometry-based metrics are more suitable for assessing coastline localization quality than pixel-overlap metrics such as Intersection over Union (IoU). CoastlineVLM-7B improves global geometric alignment with reference coastlines, reducing Hausdorff distance from 37.74 m to 31.84 m and Earth Mover's Distance from 21.12 m to 17.32 m. These results indicate that output representation is a critical design choice in coastline extraction, and that geometry-oriented learning, combined with the semantic reasoning capabilities of vision-language models, aligns well with how coastlines are defined and evaluated in operational coastal monitoring.
### Title:
          On the Localization of Checkerboarding in Multiaxial Stress Regions under SIMP Penalization
 - **Authors:** Iulian Paunel, Jonathan Stollberg, Dominik Schillinger
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Checkerboard patterns are a well-known numerical artifact in density-based topology optimization using the Solid Isotropic Material with Penalization (SIMP) method and linear finite elements. Existing explanations based on mixed-field incompatibility or locking-induced stiffness overestimation explain the artificial stiffness of checkerboard layouts but do not clarify their characteristic spatial localization. In this work, we show that checkerboard patterns systematically emerge in multiaxial load-transfer regions, whereas predominantly uniaxial stress regions remain checkerboard-free. Through systematic numerical investigations, we demonstrate that checkerboarding originates where continuous intermediate densities are mechanically favorable for multiaxial load transfer but are suppressed by SIMP penalization. Due to the characteristic behavior of linear elements, checkerboard layouts provide an artificially stiff discrete substitute for these penalized intermediate-density regions. In contrast, uniaxial load paths naturally favor continuous solid struts, rendering checkerboards mechanically disadvantageous. Our findings provide a unified mechanical interpretation of checkerboarding as the interplay between global stress states, SIMP penalization, and element-level locking, thereby explaining both its origin and the spatial localization.
### Title:
          Globally Localizing Lunar Rover in Pixels via Graph Alignment
 - **Authors:** Mao Chen, Xu Yang, Chuankai Liu, Xiangkai Zhang, Xiaoxue Wang, Zheng Bo, Zuoyu Zhang, Zhiyong Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Precise rover localization is a prerequisite for autonomous lunar exploration, yet the absence of Global Navigation Satellite System (GNSS) signals and the cumulative drift of local localization methods severely constrain long-range missions. Cross-view localization provides a promising drift-free global solution by matching rover-view and satellite-view imagery. However, the lunar environment poses unique challenges for correspondence alignment, including inter-entity entanglement, inter-viewpoint divergence, and simulation-to-real domain shift. To address these challenges, we propose Warped Alignment of Reprojected Graphs (WARG), a framework that leverages unified graph learning and reprojected graph matching for robust cross-view alignment. Pretrained on the synthetic LuSNAR dataset, WARG achieves an average test error of 0.32 m and demonstrates robust zero-shot generalization to the synthetic lunar south pole region with an error of 3.63 m. More importantly, when validated on real-world data from the YuTu-2 rover, WARG achieves a localization error of 1.68 m within a 100 m x 100 m search area, corresponding to nearly one-pixel precision in low-resolution satellite imagery with a spatial resolution of 1.40 m/pixel. Beyond accuracy, WARG is computationally efficient, containing only 1.56M parameters, corresponding to 16.12% of previous lightweight models, and operating at 5.49 Hz on an NVIDIA RTX A6000 GPU, approaching GNSS-level update frequency. Finally, we observe that WARG naturally develops low-level spatial awareness, including semantic segmentation and structural reasoning, through cross-view localization learning, highlighting its potential as a promising paradigm for spatial intelligence with minimal annotation cost. The source code is available at this https URL.
### Title:
          Kwai Keye-VL-2.0 Technical Report
 - **Authors:** Kwai Keye Team, Bin Wen, Changyi Liu, Chengru Song, Chongling Rao, Guowang Zhang, Han Li, Haonan Fan, Hengrui Ju, Jiankang Chen, Jiapeng Chen, Jiawei Yuan, Kaixuan Yang, Kaiyu Jiang, Kun Gai, Lingzhi Zhou, Na Nie, Sen Na, Tianke Zhang, Tingting Gao, Xuanyu Zheng, Yulong Chen, Fan Yang, Haixuan Gao, Lele Yang, Mingqiao Liu, Muxi Diao, Qi Zhang, Qile Su, Wei Chen, Wentao Hong, Xingyu Lu, Yancheng Long, Yankai Yang, Yingxin Li, Yiyang Fan, Yu Xia, Yuzhe Chen, Ziliang Lai, Chuan Yi, Haonan Jia, Tianming Liang, Weixin Xu, Xiaoxiao Ma, Yang Tian, Yufei Han, Feng Han, Hang Li, Jing Wang, Jinghui Jia, Junmin Chen, Junyu Shi, Ruilin Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Kwai Keye-VL-2.0-30B-A3B, an open-source Mixture-of-Experts (MoE) multimodal foundation model designed to advance long-video understanding and agentic intelligence. To address the challenges of ultra-long contexts, information redundancy, and prohibitive computational costs inherent in hour-level videos, Keye-VL-2.0 is the first to adapt DeepSeek Sparse Attention (DSA) to GQA-based multimodal architectures, enabling lossless 256K context processing while capturing critical frames and long-range temporal dependencies. This architecture is underpinned by a highly optimized training and inference infrastructure, including scalable video I/O, heterogeneous ViT-LM parallelism, and custom DSA kernels that significantly maximize throughput and minimize computational overhead. Furthermore, to overcome the algorithmic dilemma of catastrophic forgetting during multi-task alignment, we introduce Cross-Modal Multi-Teacher On-Policy Distillation (MOPD) paired with Context-RL and Video-RL. By distilling dense token-level teacher feedback from on-policy rollouts back into the MoE backbone, which activates only 3B parameters, Keye-VL-2.0 natively empowers advanced agent collaboration across Code, Tool, and Search scenarios with multimodal self-correction. Extensive evaluations across video understanding, temporal grounding, reasoning, STEM, and agent benchmarks demonstrate that Keye-VL-2.0-30B-A3B achieves state-of-the-art performance among models of similar scale, particularly excelling in fine-grained temporal localization on TimeLens and long-video comprehension on Video-MME-v2 and LongVideoBench. We release our model checkpoints to accelerate community progress toward scalable and robust multimodal agentic applications.
### Title:
          Beyond Patches: Superpixel Token-based Transformers for Attribute-Specific Fashion Retrieval
 - **Authors:** Shuili Zhang, Hongzhang Mu, Wenyuan Zhang, Duohe Ma, Tingwen Liu
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Attribute-Specific Fashion Retrieval (ASFR) aims to improve fine-grained image retrieval by focusing on specific attributes. However, existing patch-based attention and Transformer methods often misalign with irregular attribute regions and are prone to background noise, limiting their ability to capture subtle, pixel-level microstructures. To tackle these challenges, we propose SuperFashion, the first ASFR framework that adopts superpixel tokens within a Transformer architecture. SuperFashion initially employs an attribute-guided attention mechanism to extract attribute-related features, which in turn guide the cropping of semantically meaningful image regions. Superpixel segmentation is then leveraged on these regions to generate compact, semantically coherent superpixel tokens. By incorporating modality-specific embeddings for both attribute and superpixel tokens, the superpixel token-based Transformer facilitates adaptive interaction and fusion, thereby enhancing attribute localization and discrimination. Extensive experiments on FashionAI, DARN, and DeepFashion demonstrate relative overall MAP improvements of 1.84%, 9.27%, and 9.35% over prior SOTA. SuperFashion offers a new solution for web-based image retrieval.
### Title:
          Hand-centric Human-to-Robot Trajectory Transfer from Video Demonstrations via Open-World Contact Localization
 - **Authors:** Yitian Shi, Di Wen, Zhengqi Han, Zicheng Guo, Yu Hu, Edgar Welte, Kunyu Peng, Rainer Stiefelhagen, Rania Rayyes
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning from human video demonstrations remains challenging due to noisy hand-object interactions, unseen objects with partial observation, and cross-embodiment discrepancy. To address these challenges, we present \textit{HOWTransfer} (\emph{H}and-\emph{O}bject \emph{O}pen-\emph{W}orld Transfer), a hand-centric framework that distills human demonstrations into contact-aware, taxonomy-informed, and diverse robotic trajectories. Instead of relying on object-specific descriptions, vision-language queries, or explicit object-state tracking, \emph{HOWTransfer} recovers temporally consistent 3D hand motion and localizes temporal contact intervals by reasoning over observed hand-object interaction cues. The localized contact onsets are then used to retarget human grasp intent into multi-modal parallel-jaw grasp hypotheses, which are propagated along the recovered wrist trajectory to generate robot-executable motions. Finally, a trajectory editing stage refines contact alignment and produces diverse executable variants from a single demonstration. Experiments across diverse manipulation tasks show that \emph{HOWTransfer} enables accurate contact localization and high-quality robot motion retargeting with $86\%$ success, which is preferred over teleoperated trajectories in a blinded preference study.
### Title:
          A Distributed Multi-UGV Exploration Framework With Loop-Aware Planning and Descriptor-Aided Localization in Resource-Limited Environments
 - **Authors:** Zhiwei Li, Haiou Liu, Xijun Zhao, Ji Li, Yingze Wang, Boyang Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust and efficient cooperative exploration with multiple unmanned ground vehicles (UGVs) in unknown, GPSdenied, and bandwidth-limited environments without prior maps remains challenging, as localization drift degrades map consistency and induces redundant coverage. This paper presents a fully distributed exploration framework that couples descriptoraided inter-UGV loop closure with loop-aware hierarchical planning while enabling autonomous localization and exploration. We develop a lightweight LiDAR global descriptor with range-image prealignment to enable robust cross-UGV place recognition under large yaw and lateral variations, and use verified loop closures to maintain globally consistent trajectories and a sparse topological representation. We further introduce an uncertainty-aware crossUGV loop-closure selection module that scores candidate loop closures under pose uncertainty and retains high-utility loop closures as planning anchors for global task allocation and local route refinement. Simulations and real-UGV experiments show that the loop-closure module achieves AR@1/AR@1% of 89.9%/95.5%, distributed optimization reduces absolute trajectory error, the system substantially reduces two-way communication volume, and the overall framework reduces exploration time and travel distance by 15% and 14%, respectively, compared with an mTSP baseline.
## Keyword: transformer
### Title:
          Blurry Window Attention
 - **Authors:** Axel Laborieux, Christos Sourmpis, Juan Gabriel Kostelec, Qinghai Guo
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Softmax Attention operation in Transformer language models has a quadratic complexity in the sequence length and a growing state size in the form of KV cache, which becomes a bottleneck in long context scenarios. To overcome this limitation, alternative architectures with linear complexity and finite state size have been introduced, such as State-Space Models (SSMs), Linear Attention (LA), and Attention with Bounded-memory Control (ABC). Though linear models achieve similar language perplexity as Transformers, they are still behind in tasks which require retrieval or recall of specific information. In this work, we introduce Blurry Window Attention (BLA) a novel ABC method inspired by SSMs. BLA stores a frequency window from which a blurry KV history is reconstructed via interpolation using Dirichlet kernels. BLA can be understood as a generalization of Sliding Window Attention (SWA) depending on the Dirichlet kernels resolution or as a special case of the Gated Slot Attention (GSA), where the decay factor is implemented with Dirichlet kernels. We describe in details the theory and efficient implementation of BLA. On the Multi-Query Associate Recall (MQAR) synthetic task, we show that the state efficiency of BLA is 8$\times$ better than SWA and is competitive with popular linear attention models, and in the RegBench synthetic task, only BLA and SWA improve their performance as the state size grows among the linear models we tested.
### Title:
          PatchSTG: Scalable Spatiotemporal Graph Transformers for Traffic Forecasting on Irregular Sensor Networks
 - **Authors:** Jichao Li, Xuanming Shi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traffic forecasting is a fundamental component of intelligent transportation systems, yet remains challenging in real-world settings due to irregular sensor distributions and the high computational cost of modeling large-scale spatiotemporal dependencies. In practical traffic networks, sensors are unevenly distributed across regions, leading to non-uniform spatial structures that limit the effectiveness and scalability of existing graph-based and attention-based models. To address these challenges, we propose PatchSTG, a patch-based spatiotemporal graph Transformer designed for efficient forecasting on irregular sensor networks. The key idea is to introduce a hierarchical spatial representation that partitions sensors into balanced, locality-preserving patches based on geographic information. On top of this structure, a dual attention encoder alternates between intra-patch attention for capturing local interactions and inter-patch attention for modeling global dependencies, reducing computational complexity from quadratic to near-linear scaling. We evaluate PatchSTG on real-world traffic data from Rhode Island and additional large-scale datasets. Experimental results demonstrate that the proposed model achieves stable and competitive forecasting performance across multiple horizons, while significantly improving computational efficiency. Ablation studies further validate the effectiveness of spatial partitioning and dual attention in capturing both local and long-range traffic dynamics. These results suggest that patch-based spatiotemporal modeling provides a scalable and effective framework for traffic forecasting under irregular spatial settings.
### Title:
          Disjoint or Overlapping? Inference Windowing for Reconstruction-Based Time Series Anomaly Detection
 - **Authors:** Guillaume Coulaud (UM, IROKO), Reza Akbarinia (IROKO), Florent Masseglia (IROKO)
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reconstruction-based methods are widely used for time series anomaly detection, where models are trained to reconstruct subsequences, and anomalies are identified through reconstruction errors. However, reported results are often hard to compare due to heterogeneous evaluation practices and underspecified inference procedures. In this paper, we revisit reconstruction-based anomaly detection in the univariate offline setting and study the role of the inference stride, which controls whether subsequences are processed as disjoint windows or with overlap. We propose a unified training, tuning, and multi-seed evaluation protocol on the curated TSB-AD benchmark, and study how overlapping inference affects anomaly detection performance for a range of reconstruction models, including PCA-based baselines, DLinear, an AutoEncoder, TimesNet, and Transformer variants. The results show that across all models, overlapping windows yield consistent improvements, with average relative gain up to +28%, and can alter method rankings. We further analyze variability across datasets, random seeds, and hyperparameter configurations. Finally, we complement the benchmark study with an evaluation on the full UCR archive using localization criteria aligned with sliding-window reconstruction. Overall, our results highlight that reconstruction-based anomaly detection performance depends not only on model architecture and training, but also on inference choices, motivating a clear and reproducible protocol. Our results show that reconstructionbased baselines achieve strong performance on both TSB-AD and UCR benchmarks, supporting them as competitive and practical approaches for univariate time series anomaly detection.
### Title:
          Operator Fusion for LLM Inference on the Tensix Architecture
 - **Authors:** Qingbo Wu, Ke Li, Wenzhu Wang, Jie Yu, Ruian Zhang, Lili Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This study addresses on-device inference bottlenecks of Transformer models on Tenstorrent's Tensix architecture and proposes an operator fusion strategy that enhances data locality. RMSNorm is fused with matrix multiplication in self-attention and in the FFN, enabling back-to-back execution of memory-bound and compute-bound operators in on-chip SRAM to significantly reduce DRAM reads/writes of intermediate results and scheduling overhead. To support multi-core parallelism, a NoC-based multicast mechanism is leveraged in which row/column master nodes efficiently distribute inputs and weights across the core mesh, alleviating DRAM bandwidth contention. Experiments on the Wormhole platform with Qwen2.5-0.5B, Qwen3-0.6B, and Qwen3-4B show up to 37.44% latency reduction for attention and 15.89% for MLP, with up to 7.91% reduction per decoder layer, while Pearson Correlation Coefficient (PCC) remains above 98.75%, confirming significant end-to-end efficiency gains under numerical consistency.
### Title:
          SinkRec: Mitigating Semantic State Sink in Long Sequence Recommendation with Memory-Conditioned Gated Delta Networks
 - **Authors:** Zhuang Zhuang, Zhipeng Wei, Ji Dai, Jie Chen, Fei Pan, Peng Jiang, Kun Gai
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Linear attention provides an efficient backbone for long-sequence recommendation by avoiding the quadratic cost of standard Transformers, but its compressed recurrent state can be dominated by repetitive behavior patterns. We identify this phenomenon as semantic state sink, where recurring semantics over-occupy the recurrent state and bias subsequent readouts. To mitigate semantic state sink, we propose SinkRec, a hybrid memory-transition looped architecture that decouples collaborative behavioral pattern storage from dynamic transition modeling. SinkRec externalizes recurring local patterns into a learnable conditional memory through residual vector quantization, reinjects the retrieved codes, and exposes memory key-value pairs to the attention block. It further introduces Temporal-Aware State-Relation Differential Gated DeltaNet (TDGD), which uses memory to purify recurrent writing and reading by suppressing memory-covered updates and removing memory-aligned readout responses. This design turns recurring semantics from state-competing signals into memory-retrievable patterns, allowing the recurrent state to focus on dynamic transitions and alleviating semantic state sink with linear-time efficiency. Experiments on public and industrial datasets demonstrate the effectiveness and efficiency of SinkRec.
### Title:
          A Navigable Manifold of Hypothesized Consciousness-Spectrum States in Language Model Representations
 - **Authors:** Sophie Zhao
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Across contemplative, philosophical, and psychological accounts, human consciousness is often described along a similar spectrum, ranging from reactive and self-focused patterns to more integrative and coherent ones. Understanding whether language models encode such a structured, human-interpretable consciousness spectrum in representation space is important for model guidance, evaluation and alignment. In this work, we study the geometric structure and dynamics of patterns along this spectrum in transformer embedding spaces. We show that embeddings exhibit a globally organized geometry aligned with this spectrum: sentences associated with similar states cluster into locally coherent regions, forming a structured manifold. In particular, higher-level and lower-level regions exhibit convexity-like stability, while intermediate regions form a transition corridor. Dynamically, both utility-guided and geometry-only greedy trajectories consistently traverse from lower- to higher-level regions, passing through intermediate tiers, indicating that navigability is an intrinsic property of the representation space, guided but not dictated by a global directional signal. These results suggest that embedding spaces encode structured and navigable geometry aligned with a hypothesized consciousness-spectrum taxonomy, broadly inspired by recurring structural descriptions of human consciousness across contemplative traditions, philosophy, and modern psychology, providing a representation-level perspective for analyzing and guiding model behavior.
### Title:
          One Lens, Many Worlds : A Capability-Typed Interface for World-Model Interpretability
 - **Authors:** Bhavith Chandra Challagundla, Sanskar Pandey, Param Thakkar, Rishikesh Mallagundla, Yugandhar Reddy Gogireddy, Wenhao Lu, Hindol Roy Choudhury, Shravani Challagundla, Mohamed Deraz Nasr, Spursh Deshpande
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World models are now built on substantially different computational substrates. Latent recurrent state-space models such as PlaNet and the Dreamer family compress observations into recurrent states; token-based models such as IRIS quantize observations into a learned codebook and predict autoregressively with a transformer; and joint-embedding predictive architectures such as I-JEPA predict in a learned latent space with no pixel decoder. The interpretability methods applied to these models, including probing, activation patching, sparse autoencoders, and surprise analysis, share a common set of primitives, yet they are re-implemented from scratch for each architecture because existing hook-and-cache tooling assumes a transformer language model with no notion of actions, environment steps, or imagined rollouts. We argue that this fragmentation reflects the tooling rather than the models, and that the shared structure of world models is captured by a small typed interface. We present WorldModelLens, an open-source interpretability substrate organized around a capability-typed adapter: every model implements four required methods (encode, transition, initial state, sample) and declares a set of optional heads (decode, reward, continue, actor, critic) through an explicit capability descriptor, so that reinforcement-learning and self-supervised world models are first-class without either imitating the other. A single hook and cache layer exposes time-indexed activations, imagination rollouts, and intervention replay over this interface, allowing each analysis to be written once.
### Title:
          RKSC: Reasoning-Aware KV Cache Sharing and Confident Early Exit for Multi-Step LLM Inference
 - **Authors:** Anirudh Sekar
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce RKSC (Reasoning-Aware KV Cache Sharing), a training-free inference framework that eliminates two structural redundancies in multi-branch LLM reasoning pipelines. ASKS (Attention-Similarity KV Sharing) computes the prefix KV cache once and broadcasts it to all semantically similar branches via hidden-state cosine similarity, strictly generalising the token-exact prefix caching used by vLLM and SGLang. CGEE (Confidence-Gated Early Exit) applies two complementary exit mechanisms: (1) it skips the verification forward pass entirely when generation confidence is decisive across branches, and (2) it terminates the verification pass at an intermediate layer when per-layer entropy stabilises, using lightweight hooks on the transformer backbone. RSBCM (Reasoning-Selective Block Cache Manager) prevents unbounded cache growth via attention-weighted depth-priority eviction. Across five model families (7B-10B), four benchmarks, and 1,000 evaluated problems, RKSC achieves a mean speedup of 3.008x over the No-KV baseline (peak 3.990x), a 1.66x mean improvement over vLLM-equivalent prefix caching, with a CGEE-induced error rate of only 0.37% (6 errors out of 1,616 verify calls). No fine-tuning or architecture changes are required. Code is available at this https URL.
### Title:
          Hasse Diagrams for Attention: A Partial Order Framework for Designing Transformer Masks
 - **Authors:** Chentao Li, Han Guo
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 During the training of large Transformer models, attention masks regulate the scope and direction of information flow across a sequence. Numerous mask variants exist, and operators such as FlexAttention already support arbitrary attention masks. Nevertheless, a systematic formal analysis of the information-flow structure induced by arbitrary masks has been missing. This paper develops a complete theoretical framework. We prove that, with sufficient depth, the information flow of a multi-layer Transformer converges to a Hasse diagram -- a directed acyclic graph representing a partial order. Building on this, we recast the design of parallel training tasks as the problem of finding a minimal common supergraph of Hasse diagrams, and we establish a criterion for the minimal common supergraph. This yields a constructive method to derive attention masks directly from a family of tasks. Applying the framework, we design two novel masks: a block-generation attention mask that ensures training-inference consistency (Block Two-Stream Attention), and a fully supervised bidirectional attention mask (Butterfly Attention). These results demonstrate the framework's capacity to discover new structures.
### Title:
          Does Normalization Choice Matter for Causal Large Time-Series Models?
 - **Authors:** Samy-Melwan Vilhes, Gilles Gasso, Mokhtar Z Alaya (LMAC)
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large models for time-series forecasting have been emerged as a promising paradigm for training models on heterogeneous collections of signals. These models typically rely on causal autoregressive architectures, where each observation is sequentially predicted from past. In practice, real-world time-series exhibit non-stationarities, which significantly influence predictive performance. To mitigate this, normalization is commonly employed. However, in efficient causal settings it might induce information leakage from future observations during training. Recent alternatives, including causal normalization and statistics computed from initial observations, have been proposed to address this issue, but their practical implications remain insufficiently understood. In this work, we evaluate normalization strategies for transformer-based large time-series models trained with patching and efficient causal strategy. We showcase that normalization choice significantly influences both training convergence and forecasting performance.
### Title:
          Inside the Latent Flow: Causal Deciphering of Attention Dynamics in Audio Separation Foundation Models
 - **Authors:** Yuxuan Chen, Haoyuan Xu, Peize He
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Flow-matching transformers achieve strong audio separation, yet their attention dynamics are opaque. We adapt established causal-intervention principles into a deterministic, inference-time probing protocol for SAM Audio. Orthogonal probing uncovers a dual-pathway text-conditioning mechanism: additive injections control semantic identity, while cross-attention refines acoustic structure. We observe an asynchronous layerwise convergence: stable layers build temporal scaffolds early, whereas fast layers continue resolving artifacts during sampling. The model also attenuates temporal segmentation cues to maintain continuous-flow stability. Using these insights, we propose Layer-Selective Attention Caching (LSAC), a training-free acceleration method that caches attention in stable layers. Across acoustic complexities, LSAC cuts self-attention computation by about ~25% with negligible quality loss and yields up to 6.7x higher quality retention than naive step reduction.
### Title:
          VFUSE: Virulent Feature Understanding with Sparse autoEncoders
 - **Authors:** Michael Yu, Matthew L. Olson
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Quantitative Methods (q-bio.QM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative models have shown remarkable progress in a variety of domains such as protein design, but such power enables the opaque generation of hazardous proteins. In this work, we introduce VFUSE (Virulent Feature Understanding with Sparse autoEncoders), a mechanistic interpretability approach that trains SAEs on diffusion-transformer activations to audit protein models for hazard-aware features. We apply VFUSE to RoseTTAFold3 and RFDiffusion3, popular open-weight models for protein folding and synthesis. We find that for certain blocks, linear probes detect hazardous designs significantly better when fit in the SAE latent space over the original model's representations: improving interpretability without sacrificing model performance. Furthermore, we identify monosemantic features from the SAE that fire only on hazardous designs at up to AUROC $0.84$ ($q < 10^{-13}$). To our knowledge this is the first SAE trained on an all-atom diffusion model and the first feature-level virulence audit of a protein design model, paving the way towards safe and interpretable protein design.
### Title:
          A Large Scale Open-Source Image and Video Dataset for Robust Wildfire Detection and Classification
 - **Authors:** Emadeldeen Hamdan, Yingyi Luo, B. Ugur Toreyin, Erdem Koyuncu, Adam J. Watts, Ugur Gudukbay, Ahmet Enis Cetin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Wildfire detection and monitoring are critical for mitigating fire spread and reducing environmental and infrastructural damage. In this work, we introduce GWFP (Global Wildfire Prevention Dataset), a large-scale, open-source dataset of wildfire images and videos designed to support early fire and smoke detection research. GWFP contains geographically diverse wildfire scenes, including flames, smoke, Waterdog/Fog environmental conditions, Near Infrared (NIR) imagery, Ember, and challenging negative samples collected from real-world scenarios worldwide. To evaluate dataset robustness and cross-domain generalization, we benchmark multiple convolutional and transformer-based architectures across both in-domain and cross-dataset settings. Additionally, we explore lightweight frequency--spatial feature interaction using Hadamard-enhanced residual connections (HTE-ResNet) to analyze representation robustness under domain-shift conditions. Experimental results demonstrate strong cross-dataset generalization and practical utility for real-world wildfire monitoring applications. The dataset and source code will be publicly released upon acceptance.
### Title:
          Making Time Editable in Video Diffusion Transformers
 - **Authors:** Konstantin Kuklev, Viacheslav Vasilev, Alexander Kunitsyn, Andrei Ivaniuta, Denis Dimitrov
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern Diffusion Transformers for video generation provide limited control over the progression of time and the editing of temporal dynamics. We propose a temporal-control methodology that extends a pretrained DiT with explicit time editing, allowing control over motion speed and temporal structure without redesigning the backbone. Its core implementation augments the pretrained model with a lightweight temporal module, preserving the original generative prior while expanding its controllable dynamic range.
### Title:
          Automated Pronunciation Evaluation for Korean Toddler Speech using Speech Diarization and Self-Supervised Learning
 - **Authors:** Diane Myung-kyung Woodbridge, Jee Hyun Suh
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Speech sound disorders affect approximately 44% of Korean pediatric communication disorder cases, yet automated assessment tools for Korean toddler speech remain underdeveloped. This paper presents an end-to-end pipeline for automated pronunciation evaluation of Korean toddler speech, combining neural speaker diarization with self-supervised speech representation learning. We introduce a novel IRB-approved corpus of 53 recordings from Korean-speaking children aged 2-5 years. A subset of 53 subjects was annotated by three independent reviewers, yielding 1,190 consonant and 748 vowel word-level binary correctness labels. We evaluate three diarization models, finding that NeMo SortFormer achieves 88.69% speaker count accuracy and 33.04% diarization error rate (DER) owing to its arrival-time-sorted transformer architecture, which handles the acoustic confound between young female caregivers exhibiting aegyo and toddler speech. For pronunciation scoring, we compare three self-supervised learning (SSL) backbones across multiple pooling strategies. A cross-model ensemble routing consonant prediction to HuBERT-large and vowel prediction to WavLM-large achieves balanced accuracies of 0.720 and 0.845, with a mean of 0.782.
### Title:
          Spatiotemporal Graph Transformer for 3D Neighborhood Interaction and Quality Prediction in Metal Additive Manufacturing
 - **Authors:** Joyce Karen Pelaez, Siqi Zhang, Hoo Sang Ko
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Metal additive manufacturing enables the fabrication of complex parts, but achieving consistent build quality remains challenging due to interactions induced by repeated layer-wise melting, solidification, and reheating across the 3D build. Advanced sensing provide a great opportunity to collect rich observations of the actual manufacturing process for real-time quality monitoring and control. Yet, existing methods often have limited ability to represent multi-layer interactions and quantify their contributions to quality. In this paper, we develop a novel spatiotemporal graph transformer for modeling 3D neighborhood interactions and learn their effects on build quality in metal additive manufacturing. Specifically, we first introduce a weighted network representation of the manufacturing process, where fusing locations are modeled as nodes, and their spatial- and process-dependent relationships are encoded as edge weights. This representation also enables the integration of multimodal data (e.g., geometric design, process settings, and in-situ sensing data) into a unified structure for downstream learning tasks. Building on this network, we further design a dual-attention graph transformer that captures both within-node feature dependencies and cross-node neighborhood interactions for quality representation learning. Experimental results show that the proposed framework significantly outperforms image-based, sequence-based, and graph-based models in characterizing process-quality relationships. More importantly, the incorporation of cross-layer interactions is critical for improving quality prediction performance. This framework is broadly applicable to other tasks involving network modeling and graph-based representation learning.
### Title:
          DUET -- Dual User Embedding Transformers for Offsite Conversion Prediction
 - **Authors:** Reazul Hasan Russel, Mingwei Tang, Rostam Shirani, Xinlong Liu, Navid Madani, Leo Ding, Yawen He, Xiangyu Wang, Mustafa Acar, Ashish Katiyar, Yuhai Li, Alan Yang, Metarya Ruparel, Derek Qiang Xu, Rupert Wu, Rui Yang, Liang Tao, Xinyi Zhao, Larry Zhang, Sri Reddy, Rob Malkin
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Offsite conversion rate (OCVR) prediction is an important ranking problem in computational recommendation systems. This task presents a modeling challenge: click signals are abundant and exhibit short temporal horizons, whereas conversion signals are inherently sparse, long-delayed, and frequently unattributed. Despite these statistical disparities, both signal types must inform models that operate within strict serving-latency constraints. Prior pre-training approaches address this heterogeneity with a single, undifferentiated encoder applied uniformly across both data streams. We propose DUET (Dual User Embedding Transformers), a framework that explicitly partitions user behavioral data into two domain-coherent streams -- clicks and conversions -- and pre-trains dedicated transformer encoders with architectures tailored to each stream's statistical characteristics: multi-layer self-attention for the dense click stream and interleaved cross- and self-attention for the sparse conversion stream. The resulting complementary embeddings are jointly consumed by a downstream ranker without exceeding serving-latency budgets. Evaluation demonstrates up to 0.38% normalized entropy (NE) reduction relative to the strongest baseline, and A/B test shows consistent improvements in OCVR prediction accuracy.
### Title:
          A Unified Adaptive Feature Composition Framework for Multi-Task Generalization in Wireless Foundation Models
 - **Authors:** Yuxuan Shi, Tingting Yang, Kangning Ma, Liwen Jing, Yuwei Wang, Mengfan Zheng, Li Sun
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Though wireless foundation models (WFMs) have shown strong potential in learning universal channel representations, their adaptation to various downstream tasks remains constrained by existing paradigms. Fine-tuning strategies introduces substantial computational and storage overhead, while frozen feature extraction leads to sub-optimal performance across diverse downstream tasks. To address this issue, we propose a unified adaptive feature composition framework for multitask generalization in WFMs, where the key component is the Routing Adapter for Feature Composition (RAFC). Instead of extracting only the final-layer output, this router treats the hidden states from different Transformer depths as a reusable pool of multi-level hidden features, and employs a lightweight task-driven feature composition network to generate layer-wise aggregation weights, then adaptively combine hierarchical representations through weighted summation. This design enables each downstream task to access suitable mixture of low-, mid-, and high-level wireless features without modifying the pretrained backbone. Extensive experiments on four representative wireless tasks demonstrate that RAFC consistently outperforms conventional adaptation baselines while introducing fewer than 50K additional parameters. Moreover, the learned routing weights provide interpretable evidence of task-specific layer preferences, making the proposed framework a low-complexity, scalable, and explainable interface for adapting WFMs to diverse downstream scenarios.
### Title:
          Towards Robust Arabic Speech Emotion Recognition with Deep Learning
 - **Authors:** Youcef Soufiane Gheffari, Samiya Silarbi
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Speech Emotion Recognition (SER) aims to identify a speaker's emotional state from audio signals. While recent advances in deep learning have significantly improved SER performance in Indo-European languages, Arabic SER remains underexplored and challenging due to dialectal diversity, limited annotated datasets, and the difficulty of modeling both local spectral cues and long-range temporal dependencies. To address these limitations, this study investigates whether hybrid architectures that jointly model spatial and contextual information can improve emotion recognition in Arabic speech. We propose and evaluate a comparative framework involving three architectures: a CNN-LSTM model, a CNN-Transformer model, and a fine-tuned wav2vec 2.0 model. The first two models leverage MFCC and spectrogram-based representations, while wav2vec 2.0 operates directly on raw audio through self-supervised representations. Experiments conducted on the EYASE and BAVED datasets demonstrate that the proposed CNN-Transformer architecture significantly outperforms the other models, achieving an accuracy of 98.1 percent. This result highlights the effectiveness of combining convolutional feature extraction with Transformer-based global context modeling. The main contribution of this work lies in providing a systematic comparison of hybrid and self-supervised approaches for Arabic SER, and in demonstrating that CNN-Transformer architectures offer a robust solution for capturing both spectral and long-range dependencies in low-resource and dialectally diverse settings.
### Title:
          Test-time Adversarial Takeover: A Real-time Hijacking Interface against Robotic Diffusion Policies
 - **Authors:** Zi Yin, Peilin Chai, Siyuan Huang, Zhanhao Hu
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion-based action generation has become a foundational component of embodied AI, but its reliance on visual conditioning leaves deployed visuomotor policies vulnerable to adversarial manipulation. Most prior attacks focus on disruption: they perturb the observation stream to reduce task success or induce erratic behavior. We study a stronger threat, Test-time Adversarial Takeover (TAKO), in which an attacker obtains a real-time steering interface over a frozen robot policy and turns it into a remotely piloted instrument. TAKO learns a small vocabulary of reusable universal patches through differentiable diffusion inference; at test time, the attacker switches among these patches in the camera stream to compose attacker-chosen trajectories. This works because the perturbation acts on the visual conditioning pathway, where the induced bias can persist through iterative generative inference. We further show that the natural targeted baseline, target-policy matching, fails because the victim policy cannot reliably supervise itself on out-of-distribution target shifts. Across four tasks (2D manipulation, simulated aerial delivery, simulated ground navigation, and physical-world ground navigation), two visual encoders (ResNet-18 and EfficientNet-B0 + Transformer), and three generative inference families (DDPM, DDIM, and flow matching), human operators achieve 100\% takeover success on attacker-defined objectives in every evaluated setting. The project page is available at this https URL.
### Title:
          PF-Trans: Physics-Embedded Frequency-Aware Transformer for Spectral Reconstruction
 - **Authors:** Yuzhe Gui, Tianzhu Liu, Yanfeng Gu, Xian Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Snapshot Broadband Filter Array (BFA) imaging provides high light throughput for spectral reconstruction but introduces severe spectral aliasing due to complex modulation. Current deep learning approaches, limited to spatial denoising, often fail to address the global frequency-specific degradations caused by the mask structure. To address this, we propose a Physics-embedded Frequency-aware Transformer (PF-Trans) for high-fidelity remote sensing spectral reconstruction. Our method explicitly integrates the physical sensing model through mask injection and a gray-scale consistency loss to ensure physical fidelity. Furthermore, we introduce a Dual-domain Block with a parallel Fast Fourier Transform (FFT) branch, enabling the network to perceive and suppress aliasing artifacts in the frequency domain. Extensive experiments on multiple datasets demonstrate that PF-Trans achieves state-of-the-art performance, achieving a Peak Signal-to-Noise Ratio (PSNR) of up to 48.50 dB on the GF-5 Shanghai dataset, significantly outperforming comparison methods.
### Title:
          Instruction Finetuning DeepSeek-R1-8B Model Using LoRA and NEFTune
 - **Authors:** Wu Yuerong, Mingni Luo
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Financial named-entity recognition (NER) is essential for translating unstructured financial reports and news into structured knowledge graphs. However, general-purpose large language models (LLMs) often misclassify financial entities or ignore domain-specific patterns. This paper investigates the use of DeepSeek-R1-8B, a recent open-source large language model, combined with Low-Rank Adaptation (LoRA) and Noisy Embedding Fine-Tuning (NEFTune) for financial NER. Each annotated sentence in our corpus of 1693 samples is converted into an instruction-input-output triple. We insert lightweight LoRA matrices into the Transformer layers and apply NEFTune to improve generalisation by adding uniform noise to embedding vectors during training. Experiments show that the LoRA-adapted DeepSeek-R1-8B achieves a micro-F1 of 0.901 on seven entity types (Company, Date, Location, Money, Person, Product and Quantity), and adding NEFTune further boosts the micro-F1 to 0.912, outperforming Llama3-8B, Qwen3-8B, Baichuan2-7B, T5 and BERT-Base baselines.
### Title:
          Efficient RWKV-based Representation Learning for 3D Point Clouds
 - **Authors:** Yun Liu, Xuefeng Yan, Liangliang Nan, Xianzhi Li, Peng Li, Zhe Zhu, Honghua Chen, Mingqiang Wei
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The recent receptance weighted key value (RWKV) model combines RNN-style recurrence, offering a linear-complexity alternative to Transformers' quadratic self-attention for modeling global dependencies. However, when directly applied to point clouds, RWKV, originally developed for sequential text, struggles to capture local geometric structures and model spatial dependencies effectively. To address this, we propose the \textbf{P-RWKV} block, which bridges the gap between sequence modeling and irregular 3D geometry while preserving the efficiency advantages of RWKV. It consists of a Local Perception Expansion (LPE) component to expand contextual perception along the spatio-temporal sequence and a Spatial Context Enhancement (SCE) component to strengthen spatial awareness. To validate the effectiveness of P-RWKV for point cloud understanding, we construct PointER, a single-modality self-supervised representation learning framework whose encoder is composed of stacked P-RWKV blocks. Furthermore, we extend P-RWKV to a cross-modality setting and integrate the proposed core sub-modules into multiple architectures, demonstrating strong plug-and-play flexibility and architectural generality. Extensive experiments show that the P-RWKV block and its key sub-modules achieve competitive performance across various tasks with lower computational cost and inference latency. Code will be released upon acceptance.
### Title:
          Parallel Causal Associative Fields: Gated Sparse Memory for Long-Context Language Modeling
 - **Authors:** Muhammad Ahmed
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers achieve strong language modeling performance by providing direct token-to-token communication paths, but causal self-attention scales quadratically with context length. Recurrent and state-space models reduce this cost, yet compress history into sequentially updated fixed-size states. This paper studies a third primitive: a parallel content-addressed memory over causal successor records. The proposed Parallel Causal Associative Field (PCAF) writes local records from a context window into hash buckets, retrieves a bounded candidate set for the current query, forms a sparse cache distribution over successor tokens, and mixes that cache with a parametric local language model through a learned gate. The resulting model maintains sparse long-context access while avoiding a single fixed recurrent state bottleneck. We evaluate PCAF under full autoregressive pretraining on WikiText-103 and PG-19 using a distributed Google Cloud TPU v4-32 pod. At 303M parameters and context length T = 2048, PCAF-semantic reaches 36.31 perplexity on WikiText-103 and 52.45 perplexity on PG-19, compared with 47.49 and 53.84 for a matched dense Transformer. PCAF-semantic simultaneously processes 0.61-0.62M tokens/s across the TPU pod, versus 0.43M tokens/s for dense and local attention baselines. Supporting 41M-parameter multi-seed sweeps and single-GPU component ablations show that the associative cache, retrieval capacity, and learned gate materially affect the speed-quality trade-off.
### Title:
          UPLOTS: A Unified Pretrained Language Model for Constrained Time-series Generation
 - **Authors:** Du Yin, Hao Xue, Jinliang Deng, Yang Yang, Shuang Ao, Arian Prabowo, Flora Salim
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In time-series generation, existing approaches typically handcraft ortrain a separate model for each dataset, which hinders their scalability and fails to leverage shared temporal structures across domains. To address this fragmentation, we propose UPLOTS, a Unified, Prompt-guided Language model framework fOr constrained Time-Series Generation across diverse domains. Instead of building task-specific models, UPLOTS leverages a single pre-trained transformer backbone guided by learned constraint prompts, enabling on-demand generation with precise pattern control. One key innovation is our dynamic multi-dataset loss re-weighting and prompt-to-pattern mapping, which allows UPLOTS to internalize diverse temporal structures during training and conditionally generate them at inference. We evaluate UPLOTS on four real-world benchmarks and multiple constraint settings, including peak-period, calendar, load-level, and volatility patterns. Additional held-out constraint-combination and downstream forecasting experiments further demonstrate that UPLOTS generalizes beyond the original peak-pattern setting and improves data augmentation under scarce real-data regimes. Our code and baselines are available at anonymous github repo: this https URL.
### Title:
          Machine Learning Methods for Studying Latent Neural Activity Dynamics
 - **Authors:** Shufeng Kong, Fumei Deng, Xinyi Dong, Caihua Liu, Weiwei Chen, Yingheng Wang, Daniel Cao, Azahara Oliva, Antonio Fernandez-Ruiz, Carla Gomes
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent developments in brain recording are driving a demand for machine learning tools capable of decoding the latent structure of large populations of neurons. In this paper, we provide a comprehensive survey that outlines the trajectory of Latent Variable Models (LVMs) from early state-space models to more recent deep generative models. We organize the literature into three closely related domains: (1) Single-Region Latent Dynamics, which includes models such as linear dynamical systems to more complex dynamics represented by Recurrent Neural Networks (RNNs) and Neural Ordinary Differential Equations (ODEs); (2) Multi-Region Communication, which employs probabilistic as well as subspace methods to study how information is transferred across different brain areas considering synaptic propagation delays and network connectivity; and (3) Behavior-Aligned Modeling, which seeks to disentangle neural activity related to task performance from other internal states via supervised or contrastive learning. This survey also includes large-scale neural foundation models, such as Transformers and diffusion models, that rely on large-scale pre-training for optimal performance across subjects. Finally, we conclude and discuss benchmarks, evaluation criteria, and open challenges, such as the ability to identify causal links or directionality of communication, to facilitate future research for bridging interpretable brain dynamics with reliable neural decoding.
### Title:
          Geometry-Aware Reinforcement Learning for 2D Irregular Nesting
 - **Authors:** Auguste Lehuger, Guillaume Henon-Just
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traditional heuristic solvers for the 2D irregular nesting problem share a fundamental limitation: they are blind to polygon geometry, relying on guided brute-force to navigate the continuous placement space with minimal geometrical guidance. In this paper, we argue that Reinforcement Learning is uniquely positioned to overcome this bottleneck. By pairing an optimization policy with a geometry-aware neural encoder, an agent can automatically discover rich geometric priors directly from data, utilizing these learned intuitions to strategically guide exploration. To realize this, we introduce the Polygons Transformer (PoT), a novel architecture that encodes 2D continuous vector geometries while allowing cross-polygons attention. We couple this novel architecture with a Combinatorial Optimization Reinforcement Learning (CORL) training framework to find optimal solutions. To support this paradigm, we release an open-source training dataset derived from complex geographic contours alongside a dedicated evaluation benchmark. Our empirical validation demonstrates that our trained agent achieves area utilization performance highly competitive with Sparrow, the state-of-the-art heuristic solver, proving that reinforcement learning can successfully discover and exploit geometric awareness for precise spatial tasks.
### Title:
          Dexterous Point Policy: Learning Point-based Dexterous Hand Policies from Human Demonstrations
 - **Authors:** Beomjun Kim, Seong Hyeon Park, Seunghoon Sim, Seungjun Moon, Sanghyeok Lee, Jinwoo Shin
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robotic foundation models pre-trained on human demonstration videos have shown promise, but a significant embodiment gap remains when the resulting policies are deployed on real robots. A common remedy is to fine-tune these models on robot-specific demonstrations. However, robot data collection can be prohibitively expensive and time-consuming, which is particularly acute in dexterous manipulation, e.g., teleoperating a multi-fingered hand for even a single atomic task can take days. To address this, we introduce Dexterous Point Policy, a framework that learns dexterous manipulation policies directly from human videos and requires no robot demonstrations. Our core insight is that a unified 3D keypoint representation can bridge human and robot embodiments when used for both observations and actions. Specifically, we extract 3D keypoints of task-relevant objects and human hands from raw videos, and train an autoregressive transformer over these keypoints. We observe that at the keypoint level, specifically the wrist and fingertips, human and robot behaviors closely align, enabling direct policy transfer. On a suite of real-robot tasks spanning pick-and-place and tool use, Dexterous Point Policy attains 75.0% success, whereas a state-of-the-art VLA baseline reaches only 1.0%. Furthermore, our method generalizes strongly to unseen scenarios, including multi-object environments and novel object categories.
### Title:
          One Step Closer to Ground Truth: A Multi-Scale Residual-Aware Representation Learning Pipeline for Predicting Time Series Data
 - **Authors:** Amrijit Biswas, Mustafa Kamal, Robin Krambroeckers, M. M. Lutfe Elahi, Sifat Momen, Nabeel Mohammed, Shafin Rahman
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based models have emerged as leading paradigms in time-series forecasting in recent years, employing self-attention mechanisms to capture long-range dependencies. Despite their success, these single-stage forecasting architectures exhibit persistent systematic residual biases arising from structural discrepancies, unmodeled stochastic components, or inadequate multi-scale temporal representations. This limitation persists when residuals are treated as irreducible noise, precluding adaptive correction of structured error patterns. To address this limitation, we introduce a two-stage, model-agnostic framework that explicitly decouples forecasting and residual learning into distinct stages of representation learning. A base transformer first generates the initial predictions. Subsequently, a dedicated meta-corrector dynamically models structured error patterns across multivariate channels, preserves cross-variable dependencies, and iteratively refines the residual bias of the base transformer. By formalizing this pipeline as a hypothesis space expansion, our framework addresses approximation limitations inherent in single-stage architectures, removes reliance on restrictive assumptions, and enables end-to-end learning of complex error dynamics. Evaluated on eight popular benchmark datasets using established protocols, our approach achieves state-of-the-art performance, with significant improvements in standard metrics (MSE, MAE). The results demonstrate the framework's ability to mitigate systematic biases and enhance robustness to complex temporal dynamics, advancing the practical applicability of transformer-based forecasting models.
### Title:
          Beyond Patches: Superpixel Token-based Transformers for Attribute-Specific Fashion Retrieval
 - **Authors:** Shuili Zhang, Hongzhang Mu, Wenyuan Zhang, Duohe Ma, Tingwen Liu
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Attribute-Specific Fashion Retrieval (ASFR) aims to improve fine-grained image retrieval by focusing on specific attributes. However, existing patch-based attention and Transformer methods often misalign with irregular attribute regions and are prone to background noise, limiting their ability to capture subtle, pixel-level microstructures. To tackle these challenges, we propose SuperFashion, the first ASFR framework that adopts superpixel tokens within a Transformer architecture. SuperFashion initially employs an attribute-guided attention mechanism to extract attribute-related features, which in turn guide the cropping of semantically meaningful image regions. Superpixel segmentation is then leveraged on these regions to generate compact, semantically coherent superpixel tokens. By incorporating modality-specific embeddings for both attribute and superpixel tokens, the superpixel token-based Transformer facilitates adaptive interaction and fusion, thereby enhancing attribute localization and discrimination. Extensive experiments on FashionAI, DARN, and DeepFashion demonstrate relative overall MAP improvements of 1.84%, 9.27%, and 9.35% over prior SOTA. SuperFashion offers a new solution for web-based image retrieval.
### Title:
          Transformer Based Model for Spatiotemporal Feature Learning in EEG Emotion Recognition
 - **Authors:** Xinglong Cui, Dian Gu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Electroencephalography (EEG) is a widely adopted technique for monitoring brain activity, offering valuable insights into neurological states due to its high temporal resolution and cost-effectiveness. To enhance the analysis of complex EEG data, we propose EEG-TransNet, an architecture designed to capture temporal, regional, and synchronous features of EEG signals. EEG-TransNet introduces three key modules: 1) a preprocessing and feature extraction module leveraging ResNet and wavelet-based denoising, 2) a Local Self-Attention Block for regional feature learning, and 3) a Fuzzy-Attention Synchronous Transformer (FAST) to model spatiotemporal dependencies. Through extensive experiments on three EEG datasets (BETA, SEED, and DepEEG), the proposed model consistently outperforms other methods in terms of classification accuracy and robustness across varying signal lengths. Ablation studies confirm the contribution of the Local Self-Attention Block in improving performance, and the inclusion of depthwise separable convolutions in the decoder reduces computational complexity while maintaining high accuracy. EEG-TransNet's ability to generalize across subjects with minimal performance variation highlights its potential as a robust tool for EEG-based brain activity classification and emotion recognition tasks.
### Title:
          Pre-AF 13: An Interpretable Atrial Fibrillation Risk Score Mined from Discharge Reports
 - **Authors:** Olga Shakhmatova, Dmitrii Kriukov, Daniil Larionov, Nikita Khromov, Iaroslav Bespalov, Alexander Zolotarev, Kirill Grishchenkov, Ekaterina Ivanova, Miron Kuznetsov, Ilya Sochenkov, Elizaveta Panchenko, Artem Shelmanov, Dmitry V. Dylov
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Background. Atrial fibrillation (AF) is the most prevalent cardiac arrhythmia and a major determinant of prognosis. Established AF risk scores rely on factors (older age, hypertension) nearly ubiquitous among patients with cardiovascular disease (CVD), offering limited stratification in this high-risk group. Most target long-term (5-10 year) rather than medium-term prediction. We developed interpretable ML models predicting AF risk over a 24-month and entire follow-up horizon in CVD patients using routinely collected hospital data. Methods. Single-center retrospective study of electronic health records from the National Research Cardiology Center (Russia) for patients aged >=18 with CVD but without pre-existing AF, hospitalized more than once between January 2012 and May 2019. A custom NLP pipeline transformed unstructured discharge reports into 73 structured features, combining a rule-based parser with transformer-based NER. Using LightAutoML we built a full model (73 features), a simple model (reduced subset), and a linear model for a bedside risk score. Performance was assessed by ROC AUC, compared with CHARGE-AF, C2HEST, MHS, and HAVOC, and interpreted via SHAP. Results. Of 80,576 records from 45,000 patients, 17,562 met inclusion criteria; 1,438 (8.19%) developed AF. The full model reached ROC AUC 0.735 (24-month) and 0.696 (entire follow-up); the simple model was nearly identical (0.725, 0.696). All non-linear models outperformed the four clinical risk scores (ROC AUC 0.53-0.64). The simple model uses 13 features and is named Pre-AF 13. SHAP identified age and left atrial volume as dominant predictors. A linear risk score (Pre-AF 9) stratified observed 24-month AF incidence from ~7% to 36%. Conclusion. Interpretable ML models built from routinely collected EHR data identify high-AF-risk CVD patients, outperforming established clinical risk scores.
### Title:
          miniReranker: Efficient Multimodal Reranking through Visual Cache Reuse and Interaction Sparsity
 - **Authors:** Yingqi Fan, Xuan Lu, Anhao Zhao, Junlong Tong, Ping Nie, Kai Zou, Yunpu Ma, Wei Zhang, Xiaoyu Shen
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal large language models (MLLMs) have recently shown strong potential as point-wise rerankers by directly modeling query--document relevance through next-token prediction. However, point-wise reranking suffers from substantial repeated computation across query--document pairs, while the causal structure of transformers allows only prefix segments to be reused via pre-caching. To address the misalignment of existing query-first and document-first formats with both VQA-style prompting and computation-aware reuse, we propose a \textit{vision-first} formulation that improves both cache reuse efficiency and reranking performance. However, the remaining cost is still considerable and stems from three main sources: (1) \textit{model depth}, for which we reduce active parameters via early exit; (2) \textit{cross-segment attention}, which we restrict to a narrow interaction band across a few layers; and (3) \textit{visual tokens}, where we reduce the number of tokens via embedder-guided pruning. Together, these designs form miniReranker, which reduces reranking runtime to <1% of the dense implementation under high-reuse settings for a single query, while preserving >96% of the dense model performance.
### Title:
          CITRAS-FM: Tiny Time Series Foundation Model for Covariate-Informed Zero-Shot Forecasting
 - **Authors:** Yosuke Yamaguchi, Issei Suemitsu, Yuki Kajihara, Wenpeng Wei
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pretrained time series foundation models (TSFMs) have enabled zero-shot forecasting on unseen target series. However, existing TSFMs often incur high computational cost and provide limited support for diverse variable types, often failing to account for covariates that exogenously influence target variability. To address these challenges, we propose CITRAS-FM, a tiny 7M-parameter TSFM that supports univariate, multivariate, and covariate-informed zero-shot forecasting with real-time CPU inference. Built on a patch-based, decoder-only Transformer, CITRAS-FM introduces Shifted Attention into the cross-variate module to effectively exploit known covariates accessible throughout the forecast horizon. Moreover, to enable covariate-aware pretraining despite the scarcity of covariate-rich corpora, we propose CovSynth, which synthesizes realistic covariates from decomposed components of target series. Experiments on fev-bench, spanning 100 tasks across various settings, demonstrate that CITRAS-FM achieves state-of-the-art zero-shot accuracy among sub-10M TSFMs while delivering sub-0.1-second CPU inference, offering a strong balance between forecasting accuracy and real-time deployability.
### Title:
          K-Forcing: Joint Next-K-Token Decoding via Push-Forward Language Modeling
 - **Authors:** Zhiwei Tang, Yuanyu He, Yizheng Han, Wangbo Zhao, Jiasheng Tang, Fan Wang, Bohan Zhuang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autoregressive (AR) language modeling is the dominant paradigm for text generation, yet its sequential token-by-token decoding makes inference memory-bound and inefficient. Existing acceleration approaches, such as speculative decoding and diffusion language models, can yield speedups under certain conditions but do not directly address high-load batch serving--the scenario most critical for industrial-scale deployment. We introduce K-Forcing, a push-forward language modeling paradigm for joint next-k-token decoding. K-Forcing distills an existing AR model into a conditional push-forward mapping--one that transforms independent uniform noise variables into a joint sample of multiple future tokens in a single forward pass. This design preserves fixed-length outputs, reuses the AR teacher backbone, and remains compatible with standard AR serving infrastructure. We train this mapping via progressive self-forcing distillation, which gradually expands the prediction window while enabling the student to closely match the sequence distribution of the AR teacher. We evaluate K-Forcing on LM1B and OpenWebText using a standard causal Transformer backbone. When aggressively configured to generate k = 4 tokens per forward pass, K-Forcing delivers approximately 2.4-3.5x speedup across different batch sizes, while incurring modest quality degradation relative to its AR teacher. As inference increasingly dominates the lifetime compute cost of modern LLMs, K-Forcing offers a promising route toward accelerating AR generation under real-world high-load deployment.
### Title:
          Encoding the Euler Characteristic Transform
 - **Authors:** Nello Blaser, Odin Hoff Gardaa, Lars M. Salbu, Elena Xinyi Wang, Bastian Rieck
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Algebraic Topology (math.AT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Euler Characteristic Curve (ECC) records the Euler characteristic of a linearly embedded cell complex as a function of filtration height in a given direction, and the Euler Characteristic Transform (ECT) is the injective shape descriptor obtained by collecting ECCs over many directions. How the ECT is encoded for a neural network is itself an inductive bias, conventionally fixed by discretizing each ECC. We introduce a continuous encoding: for each direction and each vertex it records the net Euler-characteristic change attributed to that vertex, producing a per-direction token sequence that a small transformer maps to a feature vector. We separate the resulting pipeline into two stages on orthogonal axes: an ECC encoder that acts within each direction, mapping its curve to a fixed-length vector, and an ECT representation that acts across directions, aggregating the per-direction vectors into one. We study six ECT representation architectures spanning a range of inductive biases, from a structure-agnostic feedforward baseline to convolutional and complex-valued models that preserve equivariance under planar rotations. Across six classification benchmarks covering point clouds, graphs, cubical complexes, and meshes, the continuous encoding improves accuracy on five of six datasets, and control experiments attribute the gain to the tokenization itself rather than to the added transformer capacity. The representation architecture matters less than the encoding, and the payoff from its inductive biases depends on the encoding: a feedforward network performs best under continuous encoding but is less robust under discretization than convolutional architectures.
### Title:
          Early Comparative Evaluation of Transformer Models for Multilingual Software Vulnerability Detection
 - **Authors:** Fiza Naseer, Javad Khan, Muhammad Yaqoob, Alexios Mylonas
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Software vulnerability detection is increasingly important as modern applications combine multiple programming languages. This paper presents an early comparative evaluation of BERT, RoBERTa, and CodeBERT for binary vulnerability detection across HTML, Python, JavaScript, and PHP using the CVEFixes dataset and language-wise three-fold stratified cross-validation. The results show clear performance differences across languages, indicating that multilingual vulnerability detection requires more language-aware and robust transformer-based modelling strategies.
### Title:
          Recoverable but Not Stationary:Local Linear Structures in Weights and Activations
 - **Authors:** Irina Piontkovskaia, Sergey Nikolenko
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Task vectors, LoRA, activation steering, and random search around pretrained weights all suggest that learned behaviour can be controlled by linear directions. We ask which linear structures actually exist and on what scale. In a synthetic multitask transformer and LoRA adapters on DistilGPT-2 / GPT-2 we find strong local low-rank task-gradient structure but reject the fixed-task-plane hypothesis: static bases miss the recovery direction, and the useful basis drifts substantially within 100 steps. However, the first recovery updates form a trajectory-prefix basis capturing 77% of the LoRA recovery displacement. We develop random search theory with a Gaussian local-linear theorem that justifies the effectiveness of random parameter search even in very high dimensions. We also study the relation between parameter perturbations and activation steering: a single gradient step produces an activation shift with 0.58 cosine to a labelled-contrast CAA steering vector, with a similar steering effect on Qwen-0.5B BoolQ statements. We validate our results with experiments on synthetic Transformers and LLMs. Our results suggest that linear structures in trained networks are not global task directions, but evolving local geometries that partially persist across parameter and activation spaces.
### Title:
          PENet+: A Lightweight Residual Transformer Framework for Efficient Image Steganalysis
 - **Authors:** Jincheol AN, Dongsu Kim, Haneol Jang, YoungJoon Yoo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Image steganalysis, the detection of hidden information embedded in digital images, is a core component of modern cybersecurity and digital forensics. Recent residual Transformer architectures, such as the Pixel-Difference-Convolution and Enhanced-Transformer-Network (PENet) [1], achieve strong detection accuracy, but their computational and memory demands hinder deployment in resource-constrained settings. We present PENet+, a lightweight steganalysis framework that preserves PENet's discriminative structure while substantially improving efficiency. Rather than redesigning or compressing the attention blocks, we retain PENet's self-attention topology for reproducibility and add a classifier-streamlining stage that progressively narrows the SPP-to-FC1 input channels (SPP: spatial pyramid pooling; FC1: first fully connected layer), yielding large reductions in parameters and FLOPs with negligible accuracy loss. We further refine the high-pass-filter (HPF) stem with an activation-aware mechanism that aggregates HPF responses early and selects a balanced SRM-Gabor top-K subset, and we replace PENet's backbone with a MobileNetV2-style inverted residual network. A balanced configuration with K=31 filters (16 Gabor + 15 SRM) matches or surpasses heavier settings at lower compute. Finally, we motivate PReLU from a steganalysis standpoint, arguing that preserving negative responses helps capture weak stego cues that ReLU suppresses. On a disjoint ALASKA2 JPEG QF90 protocol at 512x512 resolution (5,000 cover images for training, validation, and internal testing; a separate 19,000-cover evaluation set), PENet+ achieves up to 45.5% fewer parameters and about 97% fewer FLOPs than the re-evaluated PENet baseline, offering a computationally efficient direction for resource-constrained steganalysis. Device-level latency and power measurements remain future work.
### Title:
          GRAFT: Gain-Recalibrated Adapters for Transformer-Based Neural Population Activity Modeling
 - **Authors:** Xiangsheng Ge, Yang Xie
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Neurons and Cognition (q-bio.NC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural population activity models can recover rich temporal structure from binned spikes, but their read-in and readout layers often remain tied to a fixed set of recorded neurons. This coupling limits reuse in long-term brain-computer interfaces, where recorded neuron identities, counts, and response statistics can change across days. We introduce GRAFT, a Transformer-based neural population activity model that separates reusable temporal dynamics from a recalibratable neuron interface. The neuron interface controls how recorded neurons enter and leave the shared backbone, and auxiliary gain and positional mechanisms support neural activity modeling inside the Transformer. On MC Maze under the standard NLB'21 protocol, GRAFT reaches 0.3866 co-bps as an ensemble, setting a new state of the art on the primary co-bps metric among public and reported NLB'21 results. In a cross-day protocol constructed from the NLB'21 MC Maze dataset series, GRAFT recalibrates from MC Maze to the scaled MC Maze datasets (Large/Medium/Small) by updating only 9.21% of parameters, reaching 0.3749, 0.3112, and 0.3152 co-bps with restricted target-day support sets. These results show that the same interface-backbone separation supports both strong Transformer-based neural population activity modeling and data-efficient cross-day recalibration.
### Title:
          Do Transformers Actually Help Intrusion Detection? A Temporal Sequence Evaluation on CIC-IDS2017
 - **Authors:** Zach Moczkodan (1), Hany Ragab (1) ((1) Royal Military College of Canada, Kingston, Canada)
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent deep learning approaches for network intrusion detection increasingly incorporate temporal architectures such as recurrent networks and Transformers, often reporting near-perfect performance on CIC-IDS2017. However, many existing studies neither supply their temporal modules with genuine sequence inputs nor evaluate under realistic, leakage-free conditions, making it unclear whether reported gains arise from true sequence-modeling capability. In this work, we reformulate CIC-IDS2017 as a temporal intrusion-detection task by constructing ordered flow sequences from network conversations and benchmarking nine classical and deep learning architectures under a random split, two leakage-free splits, and a padding-scheme ablation. The central finding is that padding convention, not architecture, determines the Transformer's performance: on genuinely sequential (non-padded) windows the Transformer achieves the highest macro-F1 of any model in the experiment (0.89); under zero-pad+mask evaluation it drops markedly (-0.24 macro-F1), while LSTM, GRU, and 1D-CNN remain stable. Under leakage-free group evaluation the Random Forest is the most robust model (+0.009), while the Transformer's false-alarm rate grows from 0.04% to 2.7%, a 67-fold increase invisible under conventional protocols. These findings demonstrate that evaluation methodology -- specifically padding convention and split protocol -- has a larger effect on reported performance than architectural choice, and that widely used random splits with repeat-last padding can overestimate model robustness by up to 0.24 macro-F1. We advocate leakage-free splits, explicit padding disclosure, and sequence-aware benchmarking as standard practice in future IDS research. Code and implementation details are available at this https URL.
### Title:
          OncoTraj: a public benchmark for longitudinal resistance prediction in EGFR-mutant non-small-cell lung cancer on osimertinib
 - **Authors:** Abhijoy Sarkar, Aarchi Singh Thakur
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Genomics (q-bio.GN); Quantitative Methods (q-bio.QM); Applications (stat.AP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Resistance to first-line osimertinib in EGFR-mutant non-small-cell lung cancer (NSCLC) is the canonical example of predictable clonal evolution under therapeutic pressure, yet no public benchmark exists for training or evaluating computational models on the corresponding longitudinal patient trajectories. We introduce OncoTraj, a public benchmark of 813 EGFR-mutant NSCLC patients receiving first-line osimertinib, harmonized from three real-world clinical-genomic sources: MSK-CHORD (672 patients), AACR Project GENIE BPC NSCLC (34 patients), and the FLAURA molecular-resistance supplement (107 patients). OncoTraj defines three locked tasks: (A) binary classification of progression by a fixed 12-month landmark, (B) regression of time-to-first-progression in days, and (C) six-class classification of the dominant resistance mechanism. We release the harmonized dataset, patient-level train/validation/test splits with an audited no-leakage guarantee, an open-source evaluation harness, and six reference baselines spanning a majority-class predictor, logistic regression, random forest, XGBoost, an LSTM, and a multi-task transformer. With v1's single-timepoint snapshot features, no task clears chance on clean within-source evaluation: the uniformity of this ceiling across every model class localizes the limit to the input modality (single-snapshot tissue NGS rather than serial ctDNA), not the algorithm. The benchmark does recover a reproducible literature-consistent association: TP53 co-mutation raises the 12-month progression rate from 29% to 59% cohort-wide. OncoTraj establishes a reproducible, leakage-audited baseline and converts the modality limit into concrete design requirements for a serial-ctDNA-enriched v2.
## Keyword: autonomous driving
### Title:
          Isolation-aware Scheduling Framework for DNN-based End-to-End Autonomous Driving System on Tile-based Accelerators
 - **Authors:** Chenguang Zhang, Yuanpeng Zhang, Chenhao Xue, Yihan Yin, Chen Zhang, Guangyu Sun
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Level-4+ autonomous driving systems (ADS) must run dozens of heterogeneous deep neural networks (DNNs) as end-to-end (E2E) pipelines under a strict latency constraint (<=100 ms), even as execution time varies by up to 3.3x. Cost rules out dedicating isolated hardware to each function in mass-produced ADS, so these DNNs must be densely colocated on a single chip, which introduces shared-resource contention. Tile-based accelerators expose two scheduling opportunities that conventional ADS schedulers do not exploit. First, they provide a tunable degree of parallelism (DoP): assigning more tiles raises DoP and can shorten DNN execution time. Second, they provide hardware-native isolation: tiles can be physically partitioned among co-located DNNs. But using this flexibility is expensive: changing a task's DoP triggers a stop-migrate-restart reallocation of its weights and intermediate features. At ADS task rates of 10-240 Hz, these stalls accumulate along E2E chains and threaten deadlines. Reservation-based schedulers fix DoP and leave this flexibility unused; work-conserving schedulers exploit it but assume reallocation is cheap and treat deadlines as independent. We present ADS-Tile that combines configurable isolation and elastic reservation into a spatio-temporal isolation-sharing space that bounds where and when reallocation occurs; a probabilistic latency model and a DAG-aware runtime scheduler then use this space to decide task colocation and DoP under shared E2E deadlines. On an industry- and academia- derived ADS benchmark, ADS-Tile uses up to 32% fewer tiles than the work-conserving baseline in deadline-critical settings and cuts reallocation-induced wasted processing capacity from 17%-44% to below 1.2%. Controlled spatio-temporal sharing improves resource efficiency and latency predictability for tile-based ADS.
### Title:
          Envision4D: Envisioning Visual Futures via Feed-forward 4D Gaussian Splatting for Autonomous Driving
 - **Authors:** Qi Song, Yifei He, Chi Zhang, Zheng Fu, Xuhe Zhao, Mengmeng Yang, Kun Jiang, Rui Huang, Diange Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Forecasting the future evolution of dynamic scenes is crucial in autonomous driving. However, existing feed-forward paradigms are primarily designed for interpolation. When extended to future extrapolation, they suffer from ghosting artifacts under large displacements and are constrained by simplified motion assumptions or strict future priors. To overcome these challenges, we propose Envision4D, a fully self-supervised feed-forward framework for pose-free future extrapolation. Specifically, we introduce a Future Pose Prediction module that infers future camera parameters via an iterative denoising process. Furthermore, to capture non-linear dynamics, we propose In-layer Temporal Attention and employ Conditioned Motion Lifting, which transforms the highly uncertain extrapolation process into robust relational mappings. Finally, a Progressive Training Strategy is utilized to stabilize unsupervised motion learning against error accumulation. Extensive experiments demonstrate that Envision4D achieves state-of-the-art performance, significantly outperforming existing methods in future view synthesis.
### Title:
          Self-Supervised Relevance Modelling in Autonomous Driving via Counterfactual Analysis
 - **Authors:** Luca Lusvarghi, Javier Gozalvez, Pablo Urbano Hidalgo
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving relies on computationally intensive perception pipelines to continuously detect and track objects in the surrounding environment. While some objects are key to plan safe and effective maneuvers, others may not be relevant and have no impact on the autonomous vehicle's driving decisions. Focusing on relevant objects allows a more efficient usage of available computational resources, reduces processing latencies, and limits the downstream propagation of perception noise. In this work, we propose a novel self-supervised approach based on counterfactual analysis to develop a relevance model - an AI-based tool that quantifies the relevance of objects for an autonomous vehicle. To demonstrate the potential of the proposed approach, we train a relevance model on a synthetic causal dataset generated in a selected urban scenario. Results show that the relevance model is able to accurately estimate the objects' relevance with millisecond-level latency, enabling real-time relevance estimation also in high-density scenarios. We also show that the relevance model can be used to build relevance heatmaps that offer valuable insights into the autonomous vehicle's driving policy and can be used to proactively inform perception and planning tasks. We openly release both the relevance model and the causal dataset.
### Title:
          Modular2Simple: A Tool for Modular Scenario Creation Based on the OpenSCENARIO Format
 - **Authors:** Nikolai Khriapov, Mohamed Taha Drif, Renjue Li, Cas Widdershoven
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid advancement of autonomous driving systems (ADS) has introduced significant challenges, particularly in the creation of realistic and complex scenarios for testing and validation. This paper introduces Modular2Simple, a tool designed to address these challenges by simplifying and enhancing the process of creating complex ADS scenarios. Modular2Simple seamlessly integrates with the CARLA simulator and is applicable to any software that supports the OpenSCENARIO format. By leveraging existing simple scenarios in the OpenSCENARIO format, the tool enables developers to create easily customizable modular scenarios through the combination of multiple simple or modular scenarios, significantly simplifying the scenario creation process while maintaining flexibility in scenario design. This approach not only facilitates the development of complex scenarios, reducing both development time and effort, but also promotes scenario reuse and customization, which leads to a significant reduction in code complexity and enhanced efficiency in scenario design and testing compared to traditional scenario development methods.
### Title:
          An Exposure-Time-Aligned Primary-Path Architecture for Autonomous-Driving ECUs
 - **Authors:** Toru Saito, Yuki Hagura, Tatsuya Konishi, Satoru Mizusawa, Takumi Yajima
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While end-to-end (E2E) autonomous driving has become the dominant research direction, production vehicles continue to rely on modular multi-NN pipelines for a non-trivial transitional period. The subject of this paper is the design of an architecture that, during this phase, supports a modular pipeline and an E2E path side by side and embeds a path for staged migration. Transplanted to a production SoC, egalitarian late fusion is compute-inefficient and offers no natural unit for staged E2E substitution. As an alternative, we propose three design principles: (i) Primary-Path, which explicitly selects a primary perception chain and prioritizes its enclosure within a single SoC pair over the non-critical paths (ii) Exposure-Time-Aligned, which propagates the primary sensor's exposure time $\tau_{\rm exp}$ as a tag along the chain and event-drives the fusion node on matched $\tau_{\rm exp}$ rather than a fixed cycle and (iii) Co-Path Coexistence, which, building on (i) and (ii), lets an E2E output path co-run with the modular pipeline within the same $\tau_{\rm exp}$ cycle. On a Dual-SoC production AD-ECU, the implementation closes camera-shutter to planner-output latency at a mean of 296 ms within the 350 ms design budget. Under (iii), the modular pipeline is primary at production launch and the E2E path runs as shadow on real vehicles, and the E2E scope is expanded as evaluation evidence accumulates.
### Title:
          Language-Driven Cost Optimization for Autonomous Driving
 - **Authors:** Diego Martinez-Baselga, Khaled Mustafa, Javier Alonso-Mora
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The driving behavior of autonomous vehicles is typically governed by the cost function of their motion planner, which encodes objectives such as speed tracking, smoothness, lane keeping, and collision avoidance. However, tuning the parameters that shape this cost function is a challenging task that requires technical expertise, limiting the vehicle's ability to adapt to evolving traffic scenarios or end-user preferences. This work presents a language-driven framework for adaptive cost design in autonomous driving. A Large Language Model (LLM) interprets structured scenario descriptions and natural language user queries to generate the parameters applied to a risk-aware Model Predictive Path Integral (MPPI) controller. The system incorporates a human-in-the-loop validation stage in which the proposed behavioral changes are described in non-technical language and confirmed prior to deployment. Users may additionally provide feedback either before or after deployment, enabling iterative refinement of the vehicle's motion behavior. The framework is evaluated across multiple queries in realistic driving scenarios to assess its effectiveness. Simulation results demonstrate that the method successfully induces behavioral changes that align with the intended requirements in an intuitive manner, thereby bridging the gap between intelligent vehicle control systems and end users.
### Title:
          Monte Carlo Pass Search: Using Trajectory Generation for 3D Counterfactual Pass Evaluation in Football
 - **Authors:** Andrew Kang, Priya Narasimhan
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We recast pass evaluation in football (soccer) as a Monte Carlo Tree Search (MCTS)-like evaluation problem whose components mostly exist in the literature under different names: a value model (possession value), a world model (multi-agent trajectories with ball interactions), and a policy over counterfactual actions (sampling pass variants with noise). Building on the first public high-fidelity tracking dataset with 3D ball trajectories from the Bundesliga, we introduce Monte Carlo Pass Search (MCPS), which infers kick parameters for each observed pass, samples execution variants and option variants, rolls each candidate forward with a ball-conditioned world model until the next ball interaction, and scores outcomes with a learned value model to obtain a distribution over gained value. This distribution enables distribution-aware attribution with two complementary execution-surplus scores used for analysis and ranking: mean-based and percentile-based scores. To make the world model sample-efficient under limited public data, we adapt a discrete-token, autoregressive trajectory generator from autonomous driving (SMART) and show it yields strong best-of-20 forecasting accuracy compared to baselines, while supporting fully hypothetical rollouts for downstream evaluation. We have released model checkpoints and code.
