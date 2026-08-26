# Showing new listings for Wednesday, 26 August 2026
## Keyword: SLAM
There is no result 
## Keyword: odometry
### Title:
          KLTNet: Learning Sparse Feature Tracking for Robust and Accurate Monocular Visual-Inertial Odometry
 - **Authors:** Renbiao Jin, Danping Zou, Wenxian Yu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many feature-based visual-inertial odometry (VIO) systems rely on sparse feature tracking, whose accuracy and robustness directly affect state estimation. Classical KLT trackers rely primarily on local image patches and can become unreliable under rapid motion or in low-texture environments. We propose KLTNet, a lightweight learning-based, plug-and-play sparse feature tracker designed to replace classical KLT trackers in KLT-based VIO front ends. KLTNet follows a coarse-to-fine, dense-to-sparse architecture that combines low-resolution dense optical flow for robust global motion initialization with triplet-patch refinement for accurate and temporally consistent tracking. A fixed reference patch provides a stable anchor throughout each feature track and helps reduce accumulated tracking drift. In addition, KLTNet predicts anisotropic confidence weights supervised through differentiable multi-view triangulation, which can be used as observation weights in compatible VIO estimators. Experiments with VINS-Mono and OpenVINS on public benchmarks and a self-collected low-texture dataset demonstrate improved tracking and odometry accuracy over classical KLT, while maintaining real-time performance on an embedded platform.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          SIREN-Bench: Behavior-Driven Generation and Evaluation of Emergency-Vehicle Interactions
 - **Authors:** Yicheng Zhu, Tianmu Zhao, Haoxin Leng, Fan Zuo, Tao Li, Zilin Bian
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Emergency vehicles (EMVs) can reorganize surrounding traffic as civilian vehicles brake, change lanes, or form rescue corridors in response to their passage. Evaluating these safety-critical interactions requires behavior-level control over both EMV privileges and civilian responses, together with consistent sensing and ground truth. Existing datasets and simulation benchmarks do not directly provide this combination. We present \textbf{SIREN}, a behavior-driven SUMO--CARLA co-simulation platform for generating EMV--civilian interactions. SIREN couples SUMO's network-level traffic evolution and behavior logic with CARLA's continuous vehicle control and synchronized onboard sensing; depending on the active behavior, the interaction is controlled by SUMO, CARLA, or jointly. We instantiate the platform as \textbf{SIREN-Bench-v1}, comprising seven parameterized interaction templates across emergency levels L1--L3 and three behavior families, with synchronized sensor observations and simulator-native annotations. We demonstrate the benchmark through three representative tasks: 3D object detection, trajectory prediction, and vision-language risk understanding. Evaluations of nine trajectory predictors, four LiDAR-based detectors, and five vision-language models reveal behavior-dependent failure modes. Traffic-clearance interactions are hardest for detection, privileged intersection traversal is hardest for prediction, and no learned predictor outperforms the constant-velocity reference on average. Vision-language models perform substantially better on normal traffic than on near-miss and collision events. These results demonstrate the value of behavior-centered benchmarking and establish SIREN as an extensible data-generation and evaluation platform for autonomous-driving and transportation safety research.
### Title:
          The Flat Earth Error: Differential Geometry in Vehicle Dynamics
 - **Authors:** David J. N. Limebeer, Charl van de Merwe
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The widespread idealization of road surfaces as horizontal planes can introduce significant inaccuracies into vehicle dynamics simulations, a phenomenon termed the ``Flat Earth Error.'' This article provides an expository guide to the use of classical differential geometry to model vehicular motion on curved surfaces. The influence of road curvature is characterized using the metric tensor, the second fundamental form, the shape operator, and the Christoffel symbols. Reproducible MATLAB scripts using an elliptic cone as a benchmark example illustrate the construction of geodesic curves and the simulation of particle dynamics on curved surfaces. The resulting geometric structures are integrated into a single-track vehicle-and-track model within a pseudospectral optimal control framework. Trajectory optimization results over a high-density mobile LiDAR profile of Darlington Raceway are used to generate a high-fidelity road-surface model. This model is used within an hp-adaptive collocation framework to investigate minimum lap time optimal control vehicular trajectories. These computations capture the non-smooth traction saturation limits of the tyres alongside position-dependent variations in gravitational forcing. Integrating differential geometry, multibody mechanics, and optimal control is essential for high-fidelity driven and autonomous vehicle-dynamics simulations. The optimized velocity and tyre slip profiles show that real-world racing track geometries induce dynamically significant three-dimensional effects. These results are particularly relevant to performance-limited simulations on highly banked track surfaces such as NASCAR ovals.
### Title:
          CARE: Camera-Residual Reserves for First Sightings in Adaptive LiDAR Sensing
 - **Authors:** Jiachen Gong, Yun Li, Ehsan Javanmardi, Wencan Mao, Manabu Tsukada
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adaptive LiDAR scanning concentrates a limited sensing budget on regions of interest predicted from past object tracks, lowering data volume in autonomous driving while maintaining detection accuracy. However, existing scanning policies face three challenges. First, history-driven approaches depend on past tracks, so unseen objects are detected late or missed. Second, random or uniform sampling outside the predicted regions has no awareness of where new objects appear. Third, camera-guided alternatives spend budget on all camera detections, resampling objects already covered, costing recall in crowded scenes and range when budgets are scarce. This paper introduces the CAmera-REsidual reserve (CARE), a training-free allocation rule that reserves part of a fixed ray budget for the directions of current camera detections that the track forecasts cannot explain; the rest follows the base history policy, and unused reserve returns to a random floor. The paper makes three contributions. First, a leakage-free ray-budget evaluation on nuScenes (150 scenes, 4,148 events) measuring the first-sighting loss of history-driven scanning, with a strict-causal variant using the preceding keyframe. Second, CARE raises first-sighting recall by 5.2, 5.2, and 4.3 points at 10%, 20%, and 35% budgets over the history policy, with paired intervals excluding zero; the camera cue drives this gain, and the first-sighting versus overall trade-off is a budget-dependent Pareto choice. Third, a safety-bounded forgetting module that releases budget from receding or static tracks beyond a speed-dependent guard distance; at tight budgets, forgetting without the guard significantly harms near-field recall, so the guard is what keeps it safe. The pipeline runs end to end on a real vehicle and, in closed-loop simulation, detects an occluded pedestrian earlier and brakes more reliably than history-driven scanning.
### Title:
          Variance-Guided Spatial Attention Fusion for Robust End-to-End Driving under Asymmetric Sensor Degradation
 - **Authors:** Weizhi Tao, Zengwang Jin, Xiao Wang, Hailong Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end multimodal driving has progressed rapidly by fusing camera and LiDAR streams. Existing pipelines remain fragile under asymmetric sensor degradation, where either an entire modality or only a localized region is corrupted while other regions remain useful. The key difficulty is not simply to add an uncertainty head, but to obtain dense reliability supervision, calibrate this reliability against physical fault severity, and use it before unreliable features bias the planner. We propose Variance-Guided Spatial Attention Fusion (VG-SAF), in which dense heteroscedastic reliability estimates act as interpretable spatial gates. The framework couples three components. First, a physically grounded augmentor simulates representative camera and LiDAR failures and emits a continuous spatial mask, providing dense supervision without additional annotation. Second, modality-specific experts predict per-pixel reliability scales through cross-branch dense distillation in log space, enforcing a monotone severity-to-scale response. Third, calibrated reliability maps drive a hybrid attention mechanism that suppresses unreliable cells with a local spatial gate and arbitrates between modalities through a cross-modal trust softmax. A Laplace uncertainty head emits a systemic waypoint uncertainty scale that signals severe or combined sensor degradation, including severities outside the training ranges. On the CARLA Longest6 benchmark, VG-SAF consistently improves closed-loop robustness over the baselines across camera-only, LiDAR-only, and joint degradation regimes, as measured by driving score, route completion, and infraction score.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          A Hybrid Two-Stage Machine Learning Pipeline for Fault Detection and Classification in Power Transmission Systems
 - **Authors:** Sahil Manikshete, Atharva Gujarathi, Thanh Long Vu, Akhtar Hussain, Van-Hai Bui
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rapid and accurate fault detection in high-voltage transmission networks is essential for grid reliability and equipment protection. Transmission fault datasets are frequently imbalanced, and certain fault types produce electrical signatures that fall within the normal operating envelope, causing single-model classifiers to fail on safety-critical cases. This paper proposes a hybrid two-stage machine learning pipeline that decouples detection from classification. Stage 1 combines an Isolation Forest anomaly detector with an optional supervised binary detector through an OR-fusion rule; the supervised branch is allocated automatically during training for any fault class the anomaly detector cannot resolve, and is omitted when no such class exists. Stage 2 applies a Random Forest multiclass classifier only to samples flagged by Stage 1. Feature engineering is expressed as a per-measurement-point operator mapping six raw channels to eighteen features, including zero-sequence symmetrical components derived from Fortescue's theorem, yielding 18L features for L measurement points. On the TLFaultDataset, the pipeline raises Line-fault end-to-end accuracy from 31.3% to 95.8%. On an independent single-point dataset, the same framework attains 97.25% end-to-end accuracy across all classes including normal operation, exceeding the TLFed federated benchmark of 94.84% without GPU or federated infrastructure, at 0.05 ms per sample on CPU. Ablation on both datasets shows zero-sequence features resolving the three-phase versus three-phase-to-ground ambiguity, raising the F1-score of that class pair from 0.39 to 0.997. The direction of the zero-sequence signature is found to be system-dependent, motivating a learned decision boundary in place of a fixed relay threshold.
### Title:
          The Ordinal Annotation Game: How Construct Abstraction Shapes Crowdsourced Consensus
 - **Authors:** Kosmas Pinitas
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Inter-annotator disagreement in real-time affect annotation is widely treated as stochastic noise. We challenge this view by modelling ordinal annotation as an implicit game-theoretic coordination process against an internalised population prior under a post-hoc majority vote. We present the Ordinal Annotation Game, a conceptual scaffold in which the mapping from individual effort to collective consensus is governed by the semantic abstraction of the target construct. We evaluate it across two experiments sharing identical interface software and a uniform sensitivity threshold: a controlled sensory tracking study and an in-the-wild engagement study. Sensory annotation yields a consensus-dominant regime where active updates reinforce agreement, whereas engagement annotation inverts into an effort-limited regime where more labelling penalises consensus. The payoff slope reverses sign under identical processing, showing that ordinal disagreement is a structured behavioural phenomenon, not a discretisation artefact or random error.
### Title:
          ROBBIN: Rowhammer-Based Backdoor Injection during Inference
 - **Authors:** Saion K. Roy, Yufei Wang, A. Adam Ding, Yunsi Fei
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing Rowhammer-based inference-time backdoor attacks design their bit-flip strategies purely at the algorithmic level, without accounting for the bit-flips that the underlying DRAM hardware will actually produce. This disconnection between the algorithmic backdoor construction and its hardware realization leads to unreliable attack performance, as collateral bit-flips at unintended locations degrade both the attack success rate (ASR) on triggered inputs and the test accuracy (TA) for normal inputs. Consequently, the performance of such attacks varies significantly across different DRAM devices, as each device presents a unique set of exploitable bit-flip locations. This work presents ROBBIN, a hardware-aware Rowhammer-based backdoor injection attack that integrates the device-specific vulnerability into the backdoor construction process. ROBBIN first characterizes the bit-flip patterns of a target DRAM and uses this information to iteratively select DRAM \textit{page} mappings for the model weights that would maximize ASR while preserving TA under Rowhammering. By treating every hammering-induced bit-flip as an integral part of the attack design rather than first constructing a hardware-agnostic backdoor and dismissing collateral flips as side effects, ROBBIN produces backdoors that remain robust across devices. Evaluated on ResNet-20 and VGG-16 with CIFAR-10 across three commodity DDR4 chips, ROBBIN consistently achieves close to 90\% ASR while maintaining TA above 83\%, demonstrating reliable backdoor efficacy across diverse DRAM devices.
### Title:
          In-Context Inpainting for Time Series Forecasting
 - **Authors:** Thang Nguyen, Dung Nguyen, Romero Morais, Truyen Tran
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose ICI-Time, a novel framework that reframes time series forecasting as a visual inpainting task, leveraging the generalisation power of large vision models (LVMs). Unlike methods that require specialised temporal architectures and extensive domain-specific training, ICI-Time transforms time series into structured visual representations (area charts) and applies visual in-context learning, reformulating forecasting as pattern completion within a grid-structured prompt that pre-trained vision transformers can solve without fine-tuning or architectural modification. Temporal dependencies are represented through spatial layout, with a consistent, invertible mapping between numerical and visual domains. Extensive experiments across epidemiology, meteorology, and power systems demonstrate that ICI-Time performs competitively against deep learning baselines and shows promising adaptability under limited-data settings, introducing a new paradigm that bridges temporal and visual domains.
### Title:
          Interpreting Control Latents for System Identification via Conditional Flow Matching
 - **Authors:** Dingqi Zhang, Ruiqi Zhang, Mark W. Mueller
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Latent-conditioned adaptive policies can control robots across changing dynamics, but their learned latents remain internal representations of the policy rather than physical models that can be inspected, rolled out, or used by other control modules. This limits closed-loop analysis, diagnosis, and further improvement of a fixed policy. A direct mapping from latent to physical parameters is also under-specified, because multiple systems can induce similar closed-loop behavior. We therefore decode each operational latent into a distribution of quadrotor models using conditional flow matching. The decoded distribution enables two downstream uses without modifying the policy: online predictive tuning of a high-level controller around the fixed low-level policy, and robustness analysis under specified disturbances. Under perturbed actuator dynamics, decoded-model predictive tuning reduces position tracking RMSE by $23\%$ and heading RMSE by $45\%$ relative to fixed gains. Under Gaussian force disturbances, decoded-model ensembles closely predict the lateral tracking-error evolution. Together, these results show that control latents can be converted into physical model ensembles for tuning, robustness analysis, and diagnosis of frozen adaptive policies.
### Title:
          Continual Visual Learning under Evolving Semantic Concept Shift
 - **Authors:** Ismail Lamaakal, Chaymae Yahyati, Yassine Maleh, Khalid El Makkaoui, Ibrahim Ouahbi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual foundation models are commonly adapted under the assumption that the appearance of incoming data may change while the semantic meaning of the prediction task remains fixed. In long-lived visual systems, however, taxonomies, policies, and concept definitions can themselves evolve, causing the same visual evidence to require a different interpretation. We study this setting as evolving semantic concept shift and introduce SemReWrite, a framework for selectively updating obsolete visual--semantic mappings while preserving knowledge that remains valid. SemReWrite represents changes between old and revised semantic specifications, combines semantic discrepancy with sparse revised supervision to localize affected visual regions, and uses an input-dependent low-rank rewriting mechanism together with structured semantic memory, preservation, and obsolete-decision suppression. We further introduce EvoShift-Bench, spanning ImageNet, iNaturalist, CUB-200-2011, and DomainNet, with semantic transitions including class split, merge, boundary revision, insertion, partial redefinition, recurrence, and mixed semantic--appearance shift. To explicitly evaluate selective semantic revision, we introduce Rewrite Accuracy (RA) and Preservation Accuracy (PA) for affected and unaffected regions, respectively, Obsolete Retention (OR) for measuring residual outdated semantic associations, and the Selective Revision Score (SRS), which jointly summarizes rewriting and preservation performance. Experiments show that SemReWrite achieves a stronger balance between learning revised semantics and retaining unaffected knowledge than prompt replacement, conventional fine-tuning, parameter-efficient adaptation, and continual-learning strategies.
### Title:
          Quantifying System-Level Harms from AI Adoption in Complex Sociotechnical Systems
 - **Authors:** Paul Vautravers, Oliver Chalkley, Gabriel Downer, Kate S, Damian Ruck
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Artificial Intelligence (AI) is increasingly integrated into complex sociotechnical systems, including Critical National Infrastructure (CNI), where harms emerge from interactions between technical, human, and organisational elements. Yet current AI evaluation remains model-centric, offering little insight into how observed behaviours might translate into system-level risk. We propose a framework that links structured hazard analysis, component-level testing, and probabilistic system modelling to bridge this gap. By providing a traceable pathway from model behaviour to system-level outcomes, the framework enables practitioners to answer the "so what?" of AI failures, quantify their systemic impact, and move toward evidence-based and anticipatory governance of AI in complex systems. Applied to the UK's Real Time Gross Settlement (RTGS) system as an illustrative worked example, we derive AI-driven loss scenarios using Systems Theoretic Process Analysis (STPA) and examine adversarial manipulation of LLM-based trading as one such loss scenario. Component-level experiments show that simple adversarial inputs induce measurable behavioural shifts where AI recommendations are followed. Under the component-to-system mapping used here for a financial contagion model, these shifts alter system resilience, increasing bank failures and lowering the threshold at which shocks lead to cascading disruption, particularly under widespread or monopolistic AI adoption.
### Title:
          When Seeing Is Not Enough: Benchmarking Interactive Visual Grounding in LVLMs
 - **Authors:** Zhengxiang Wang, Owen Rambow
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual grounding is typically evaluated as a one-shot mapping from an informative referring expression to a visual target. This formulation misses a central property of real-world reference: target information is often incomplete, ambiguous, and established through interaction. We introduce a controlled evaluation framework for interactive visual grounding in large vision-language models (LVLMs), varying how much target information is provided upfront and how much must be acquired through dialogue. Across four human-grounded visual contexts and four interaction protocols, current LVLMs perform significantly below task-level human baselines. Interaction can help when follow-up questions refine or repair an initial target description. Performance is lowest when no initial description is provided and target information must be acquired through questions, indicating that proactive question-driven grounding remains difficult. LVLMs are also poorly calibrated, often reporting confidence that exceeds their empirical accuracy. Follow-up studies confirm these patterns across varied description sources (human versus AI), reasoning efforts, repeated interactions, description providers, and visual contexts. Overall, interactive visual grounding remains an important challenge, requiring visual matching, information seeking and synthesis.
### Title:
          Constraint-Guided Enterprise Data Mapping with Large Language Models
 - **Authors:** Sebastian Monka, Pramod Anantharam, Thien Vo Minh, Lavdim Halilaj
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Enterprise entity alignment must handle semi-structured records, implicit attributes, and unit or granularity mismatches. Manual matching is still common in practice, but does not scale as schemas and providers evolve. LLM-only matching improves semantic recall, yet can violate structural and physical invariants, producing fluent yet operationally invalid correspondences. We propose constraint-guided mapping (CGM), a neuro-symbolic method with three stages: (i) schema-grounded admissibility constraints with metadata mc = <tau_c, delta_c>, where tau_c denotes the constraint type and delta_c provides executable relation and normalization logic; (ii) constraint-restricted candidate generation with cascade relaxation to guarantee a nonempty feasible set under noise; and (iii) neural ranking with bounded LLM disambiguation restricted to that feasible set. Methodologically, constraints operate as hypothesis-space operators rather than post-hoc validators, enabling controlled degradation under relaxation and auditable, human-guidable decisions. On a controlled structural-decoy benchmark, hard admissibility shrinks the candidate space by ~480x without dropping the GT, and a layer-by-layer ablation shows this gate, not the LLM, is the decisive lift (F1 0.08 to 0.66). The benefit is model-independent and adds no extra inference cost: a small model with constraints matches a frontier LLM used without them at ~28x lower cost. The method, not a single tuned configuration, transfers across seven enterprise makes (macro F1 0.70), each under its own automatically discovered, expert-refinable constraints, and lowers expert effort by ~7x versus spreadsheet workflows. Public Valentine results add an external ranking sanity check and mark the boundary: constraints should be hard only where structural invariants are match-determining.
### Title:
          Transition Systems from Causal Reversible Bundle Event Structures
 - **Authors:** Nataliya Gribovskaya (A.P. Ershov Institute of Informatics Systems the Siberian Branch of the Russian Academy of Sciences), Irina Virbitskaite (A.P. Ershov Institute of Informatics Systems the Siberian Branch of the Russian Academy of Sciences)
 - **Subjects:** Subjects:
Computer Science and Game Theory (cs.GT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reversible computing is a novel paradigm that has recently emerged and extends traditional forwards-only computation with the capability to execute in the reverse direction, making it possible for computation to run backwards as well as forwards. Event structures are a foundational model in concurrency theory, providing a way to understand computational processes by describing the events that occur and the relationships between them. In the literature, two structurally different approaches to associating transition system semantics with event structure models have been distinguished. One approach is based on configurations, which are sets of already executed events. The other approach is based on model residuals, which are not yet executed fragments of the model. Configuration-based transition systems appear to be primarily used for semantic representations. Residual-based transition systems are actively applied to demonstrate the consistency between operational and denotational semantics of concurrent process calculi, as well as to visualize the dynamics of models. The present paper focuses on bundle event structures with causal reversibility, which are used in the study of reversible extensions of CCS- and Ï€-like systems. Mappings from the reversible event structure model to the two transition system semantics are developed, which made it possible to prove the isomorphism of the semantics. A category-theoretic characterization of the mappings is provided.
### Title:
          Equivariant Covariance Tensors: Guaranteed SPD Uncertainty for Tensor-Valued Geometric Learning
 - **Authors:** Ruihan Liu, Yu Ji, Jianbo Yu, Shifu Yan, Qingchao Jiang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tensor-valued prediction is fundamental to geometric deep learning, yet uncertainty quantification (UQ) for such outputs remains an open challenge. While E(3)-equivariant neural networks excel at point estimates, they lack rigorous confidence measures. We focus on symmetric rank-2 tensor prediction, where the target has six Kelvin--Mandel coordinates and full uncertainty is represented by a $6\times6$ covariance matrix. We introduce a framework for E(3)-equivariant UQ, modeling the full predictive distribution where both mean and covariance preserve rotational symmetry. Our approach decomposes the covariance into irreducible representations $\mathrm{Sym}^2(\rho_c) \cong 2\times(l=0) \oplus 2\times(l=2) \oplus 1\times(l=4)$. By mapping from the flat Lie algebra $\mathfrak{sym}(6)$ to the curved SPD manifold via matrix exponentiation, we strictly ensure positive-definite covariances while maintaining exact equivariance. Furthermore, we formulate a Log-Euclidean Equivariant Scoring Objective (LE-ESO)---a robust surrogate loss based on the Multivariate Laplace distribution---providing robustness to heavy-tailed errors and stable optimization. Validation on ModelNet40 inertia tensors and Materials Project dielectric tensors demonstrates that our method achieves competitive performance and provides physically consistent, symmetry-preserving uncertainty estimates with useful risk and OOD sensitivity.
### Title:
          MRI-based Deep Radiomic Phenotyping of Neuromuscular Disorders: A Topology-driven Characterization
 - **Authors:** Martyna Żur, Łukasz Piórecki, Marek Socha, Jordi Diaz-Manera, Jose Verdu Diaz, Volker Straub, Rossella Tupler, Joanna Polańska
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Quantitative assessment of muscle MRI is crucial for monitoring neuromuscular disorders (NMD). This study introduces an automated radiomic phenotyping framework based on original features engineered across five main architectural domains: quantitative morphometry, spatial distribution, geometric shape, interactions between progressive fat replacement stages, and graph-based topology. Utilizing 1184 MRI scans from the CoMPaSS-NMD project, we map the complex 3D architecture of heterogeneous intramuscular lipodegeneration into objective, morphologically interpretable biomarkers. We introduce a graph-based skeletonization of fat infiltrates to quantify muscle architectural changes, establishing a multi-dimensional extension of traditional, spatially-agnostic volume metrics by mapping topological networks across the entire 3D muscle volume. Statistical screening via non-parametric Kruskal-Wallis analysis confirmed the discriminative power of these novel descriptors across the genetic hierarchy. Notably, topological network metrics (e.g., SF1_Skel_Nodes, $\epsilon^2$ = 0.2656) and interface dynamics metrics (e.g., SF2_To_SF1_Dist_Min, $\epsilon^2$ = 0.2092) demonstrated substantial effect sizes, providing deeper structural insights than classical volumetric assessments. Post-hoc pairwise evaluations and UMAP projections further indicated the capability of these topological and 3D geometric invariants to capture disease-specific macroscopic infiltration patterns. These results demonstrate that global architectural features represent a highly promising class of biomarkers for differential diagnosis, offering new avenues for tracking longitudinal disease dynamics in neuromuscular diagnostics. The developed automated feature extraction pipeline is integrated and available within the MUSCAT (MUSCle fAt Topology) library.
### Title:
          ZODIAC: Zero-shot Octree-based Diffusion for Anatomical Completion
 - **Authors:** Miruna-Alexandra Gafencu, Vlad Bratulescu, Yordanka Velikova, Mohammad Farid Azampour, Nassir Navab
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recovering the full 3D spine anatomy from intraoperative ultrasound is an ill-posed inverse problem, as the complete structure must be inferred from incomplete and noisy observations. Acoustic occlusions and limited field of view create large unobserved regions, while view-dependent artifacts lead to variability in expert annotations of the visible anatomy. Current supervised ultrasound shape completion methods rely on synthetically generated incomplete-complete paired data to learn conditional mappings under a predefined distribution of simulated occlusions. However, real intraoperative occlusions do not necessarily follow this distribution, which can limit generalization to patient data. As a result, accurate and robust completion from noisy partial observations remains an unsolved problem. We propose a zero-shot shape completion framework that reconstructs the entire lumbar spine from partial ultrasound observations without relying on simulated training data. To accommodate unseen and irregular patterns of missing structures, we introduce blended completion, a mechanism that integrates the learned anatomical prior with incoming partial geometry at inference time. The method learns a generative diffusion prior over full anatomical shapes represented in an adaptive octree structure, enabling efficient modeling of the complete spine in a single forward pass. Validation on phantom and volunteer data shows that decoupling completion from a predefined corruption distribution improves generalisation under real occlusions, outperforming a fully supervised variant by 22% on HD95 completion error. Code and data are available at this https URL.
### Title:
          COCI: Conference Organisers and Content Identifier
 - **Authors:** Angelo Salatino, Francesco Osborne, Alexis Vizcaino, Aliaksandr Birukou, Enrico Motta
 - **Subjects:** Subjects:
Digital Libraries (cs.DL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite the critical role of grey literature in scholarly communication, artefacts such as Calls for Papers (CfPs) remain largely isolated from modern Scholarly Knowledge Graphs. The unstructured and highly heterogeneous nature of these documents has traditionally hindered their large-scale processing. In this demo paper, we present the Conference Organisers and Content Identifier (COCI), an AI-based framework designed to extract fine-grained, structured metadata from raw CfP texts. COCI employs a multi-stage pipeline that combines Large Language Models (LLMs) with semantic mapping techniques to integrate extracted entities with established knowledge bases, including OpenAlex, DBLP, TIB ConfIDent, and the AIDA Dashboard. By disambiguating authors and semantically aligning topics and conference series, COCI bridges the gap between informal scholarly dissemination and structured Semantic Web resources, laying the foundation for systematic analysis of non-publisher-based academic events.
### Title:
          Comparative Assessment of Deep Learning Architectures for Underwater Subsurface Kelp Forest Segmentation with The Kelp-o-Tron
 - **Authors:** Sundarabalan Balasubramanian, César Borja, Ana C. Murillo, Lexi N. Wilkes, Meredith L. McPherson, Kira A. Krumhansl, Jennifer A. Dijkstra, Jarrett E. K. Byrnes
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Submerged kelp forests are vital coastal ecosystems that support marine biodiversity and ecosystem dynamics, yet accurate underwater kelp segmentation remains challenging due to optical degradation, illumination variability, turbidity, overlapping vegetation, and complex benthic backgrounds. We systematically evaluated three deep learning semantic segmentation frameworks, ResNet34-U-Net, ResNet50-DeepLabV3, and a hybrid ResNet50-ASPP-Transformer architecture, for kelp detection using high-resolution underwater RGB imagery collected from northeastern U.S. coastal waters. A dataset of 3,395 SSeg assisted annotated image-mask pairs was developed for model training and validation, while geographically independent sites were used for quantitative and qualitative evaluation. All models used consistent preprocessing, augmentation, and evaluation protocols. On independent test data, ResNet50-DeepLabV3 achieved the highest Dice (0.7120) and Intersection over Union (IoU; 0.6267), followed by ResNet34 U Net (Dice 0.6868; IoU 0.5978). The hybrid ASPP Transformer achieved the highest pixel accuracy (0.8528) but lower Dice (0.6437) and IoU (0.5746). External qualitative evaluation further showed that DeepLabV3 produced more consistent segmentation across varying environmental conditions, image qualities, and benthic habitats. Overall, ResNet50-DeepLabV3, termed Kelp-O-Tron, provided the best balance of segmentation accuracy, robustness, and generalization. The dataset, annotation workflow, and comparative evaluation provide resources for advancing automated underwater habitat mapping and ecological monitoring.
### Title:
          Weakly Supervised Seafloor Segmentation for Seagrass Habitat Mapping in Side-Scan Sonar Imagery
 - **Authors:** Hayat Rajani, Nuno Gracias, Rafael Garcia
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Seagrass meadows are crucial blue-carbon habitats, and mapping their extent is a prerequisite for coastal management and carbon inventory. Optical satellite sensors cover large areas but cannot reach deep or turbid water, whereas side-scan sonar (SSS) images the seabed at high resolution and at any depth. Interpreting SSS, however, still relies on dense manual annotation, which is slow and costly. We address this by adapting a weakly supervised semantic segmentation framework to SSS benthic habitat mapping, so that pixel-level maps are learned from image-level labels alone. The framework couples a ViT-based encoder-decoder with a classification branch, extracts class activation maps, and refines them into pseudo-labels with a dense conditional random field that we tune for the noise and weak boundaries of acoustic imagery. It follows an iterative self-training scheme, together with a sampling strategy to cope with the strong class imbalance of the data. We also study the effect of different loss functions on segmentation quality, finding Lovász-Softmax loss the most effective. On a held-out transect, the refined pseudo-labels reached an mIoU of 89.3\% against the ground truth, and the segmentation branch, trained without any pixel-level labels, reached 87.6\%. Self-supervised pretraining on unlabelled SSS added a further 3\% in mean intersection-over-union. Field trials further demonstrate the generalizability of the trained model. These results show that accurate and label-efficient benthic habitat mapping from side-scan sonar is feasible at the scale needed for coast-wide seagrass monitoring.
### Title:
          Lower Bounds for Linear Hashing via Arithmetic Kakeya
 - **Authors:** Ainesh Bakshi, Alex Conway, Hanna Komlós, William Kuszmaul, Alek Westover
 - **Subjects:** Subjects:
Data Structures and Algorithms (cs.DS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Affine modular linear hashing is one of the simplest classical hash families. For a prime $p > u$, the hash function is obtained by choosing $s,t$ uniformly from $\mathbb{Z}_p$ and mapping each key $x \in \{0,\ldots,u-1\}$ to one of $n$ bins by $h(x) = [(sx+t) \bmod p] \bmod n$. Despite its simplicity, the maximum load of linear hashing remains poorly understood. For $n$ keys hashed into $n$ bins, the best known upper bound is $O((n \log n)^{1/3})$, whereas the best known lower bound is only $\Omega(\log n / \log\log n)$. We prove a lower bound of $\exp(\Omega(\log n / \log\log n))$ for universes of size $n^{1+o(1)}$. Surprisingly, there is a key set for which this load holds not just in expectation, but for every random seed. The proof is driven by two simple reductions: one transfers lower bounds from a real version of linear hashing to modular linear hashing, and the other transfers arithmetic Kakeya constructions to real hashing. We further show that, for sufficiently large $p$, the expected maximum loads in the modular and real settings are essentially the same, giving an alternative route to an $n^{1/3+o(1)}$ upper bound. Finally, we show that any uniform subpolynomial upper bound for either setting would imply a polynomial-length arithmetic Kakeya conjecture and hence the Kakeya conjecture for upper Minkowski dimension.
## Keyword: localization
### Title:
          Equivariant Cellular Sheaves for Molecular Electronic Structure: Bridging Sheaf Cohomology and E(3)-Equivariant Hamiltonian Learning
 - **Authors:** Krishna Harish
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Chemical Physics (physics.chem-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Equivariant message-passing networks are the standard model for molecular property and interatomic-potential prediction, and recent work predicts the electronic Hamiltonian itself in an E(3)-equivariant way. Separately, topological deep learning has extended graph networks to cellular sheaves. Our central observation is structural: in a localized atomic-orbital basis, the molecular single-particle Hamiltonian, after a constant shift that makes it positive semidefinite, is the Laplacian of a cellular sheaf on a regular cell complex built from the molecule. Making the restriction maps O(3)-steerable two-center kernels from bond geometry recovers the Slater-Koster form as a special case and yields an E(3)- and permutation-equivariant operator. Three consequences follow. First, the zeroth sheaf cohomology H^0 = ker L is a topological invariant equal to the non-bonding (zero-mode) orbitals, recovering the classical alternant non-bonding-orbital count as a lower bound. Second, the Hodge 1-Laplacian lets higher cells (rings) carry cycle and delocalization information through H^1. Third, the model strictly generalizes E(3)-equivariant message-passing networks and CW networks, and inherits the anti-oversmoothing of non-trivial sheaf diffusion. We prove equivariance, expressivity, and cohomological-correspondence results for the Equivariant Cellular Sheaf Networks, and validate them numerically: the Hamiltonian-to-sheaf embedding is exact to machine precision, the cohomology dimension reproduces non-bonding-orbital counts across eleven conjugated molecules, the sheaf Laplacian is O(3)-equivariant to machine precision, and the equivariant model attains lower error and rotation generalization on a directional electronic target. Our contribution is this sheaf-theoretic formalization and its invariants, not equivariant Hamiltonian prediction itself.
### Title:
          Pattern-Derived Visual Swarm Games: Multi-Scale Drone-Vision States for Interception and Sustainability Audits
 - **Authors:** Faruk Alpay, Levent Sarioglu
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Science and Game Theory (cs.GT); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We convert drone-vision annotation streams into virtual swarm-game states without controlling physical drones. VisDrone and UAVSwarm metadata are compressed into a Bloom representation; deterministic probes produce bounded capability vectors, image-space formations, finite zero-sum payoffs, and human-readable visual overlays. The audit scales from $6\times 6$ to $32\times 32$ finite games and adds a repeated Markov layer with stock, fatigue, adaptation, exposure, stress, budget, data-growth, model-improvement, and entropy-budget state variables. Local screen tuning raises robust screen security from $0.526$ to $0.593$, and the $32\times 32$ tuned screen reaches value $0.616$. A field readout audit shows that fixed-pixel rasters do not improve monotonically: $128\times 128$ accuracy is $67.2\%$ and hotspot error is $0.136$. The diagnosed error is shrinking image-plane bandwidth. A finite empirical-risk encoder over scale-normalized Gaussian bandwidths selects a scale-normalized encoder with $\lambda=1.50$, reaching $77.6\%$ accuracy at $128\times 128$ and reducing joint loss by $0.185$. A server-side audit checks $16{,}777{,}216$ target-localization states, and a 32-round repeated-game audit over $16{,}777{,}216$ trajectories selects a budget-adaptive policy with value $0.461$.
### Title:
          Ray-Traced Augmentation for Signal Strength Based Localization
 - **Authors:** Jihoon Og, Ningze Sun, Ioanis Nikolaidis, Omid Ardakanian
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Indoor localization based on Wi-Fi typically relies on extensive collection of real-world received signal strength (RSS) fingerprints, making deployment costly and time-consuming. We present a ray-tracing-based framework that reduces this reliance by generating synthetic RSS fingerprints from a building model. We first calibrate the building model using a small amount of real RSS fingerprints through Bayesian optimization, followed by per-access-point calibration to account for residual errors in simulated RSS values. The calibrated model is then used to generate a large augmented dataset of synthetic RSS fingerprints at arbitrary locations. To effectively exploit these data for localization, we introduce novel binary and multivalued representations of RSS values and a ResNet-based localization architecture that supports cross-band fusion of 2.4 and 5 GHz measurements. We evaluate our localization method on a real campus building against a diverse set of four baselines. When trained exclusively on synthetic data, the proposed method with multivalued representation and upstream cross-band fusion achieves a mean localization error of 3.05m on a real-data test set, outperforming the best baseline by 33.6%. The results demonstrate that calibrated ray-tracing-based simulation can substantially reduce the need for real RSS fingerprints while enabling accurate deep-learning-based indoor localization.
### Title:
          RefineRank: Joint Box Refinement and Ranking for Surgical Spatio-Temporal Grounding
 - **Authors:** Linzhe Jiang, Jiayuan Huang, Changhao Zhang, Chunyang Jiang, Zhehua Mao, Mobarak I. Hoque
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Surgical spatio-temporal grounding (STG) requires locating, at each video time specified by a procedural question, the object that the question asks about. Existing approaches face a trade-off: vision language models understand the question context but produce imprecise coordinates, whereas open-set detectors provide localized candidate boxes whose confidence does not reflect which box answers the question. We introduce RefineRank, which closes this gap at the candidate-box level. A compact trainable module, RefineNet, combines the language and regional features of a frozen medical vision language model with the proposals of a frozen open-set detector: it predicts a bounded coordinate correction and a quality score for every candidate box, and a fixed decoding rule returns the original or refined box with the highest score. On the MedVidBench Official Rankings (Verified), RefineRank records 0.421 STG mIoU, the highest displayed STG score, while its global multi-metric rank is 11. In a controlled evaluation on separate training and evaluation videos, coordinate correction raises the candidate oracle upper bound from 0.6772 to 0.7302, and ranking the joint pool of original and refined candidates by their RefineNet scores improves STG mIoU from 0.2719 to 0.4534, whereas separately trained selectors over the same pool reach at most 0.4186. These results show that a small box-level module can reconcile question understanding with precise localization without retraining either backbone. Code is available at [this https URL](this https URL).
### Title:
          What Guides the Agent? Adjudicating Unauthorized Behavior via Localizing Behavior-Guiding Instructions
 - **Authors:** Yichao Gao, Yumo Zhang, Yunhao Yao, Haohua Du, Puhan Luo, Ruiqi Li, Zhiqiang Wang
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLM agents integrated with external resources gain complex task capabilities, yet the unified natural-language context channel makes them vulnerable to injection attacks: untrusted external data may be dynamically parsed as behavior-guiding instructions during LLM inference, thereby subverting the agent's decision. Existing defenses focus on static detection or isolation of malicious content at the input/output level, remains insufficient for detecting such dynamic inducements that arise during model reasoning. We propose Attnlocate, a runtime framework for fine-grained localization of context spans that genuinely influence tool-calling decisions, i.e., behavior-guiding instructions. Attnlocate casts this localization problem as an object detection task, aiming to detect the distinctive activation traces induced by behavior-guiding instructions within the attention matrix. Specifically, we design a multi-head, multi-layer attention aggregation scheme to construct a token-level feature space tailored for object detection. Then, a 1-D U-Net equipped with an anchor-free detection head is deployed to detect these spans. Finally, based on the authority of the provider from which the detected behavior-guiding spans originate, Attnlocate dynamically adjudicates malicious invocation attempts. We evaluate Attnlocate across ten agent configurations from five LLM families, covering scenarios involving indirect prompt injection and tool poisoning. Attnlocate achieves a mean IoU of 0.743, an average AUROC of 0.956, and a 0.934 true-positive rate at 0.067 false-positive rate. It also transfers effectively across unseen models and supports authority policy adaptation without retraining.
### Title:
          PARTAB: Partition-Aware Reasoning with Structured Evidence for Scalable Table Understanding
 - **Authors:** Md Mahadi Hasan Nahid, Davood Rafiei
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) have shown strong capabilities in table reasoning, but their effectiveness degrades as tables grow in size and complexity due to irrelevant context and difficulty localizing the evidence required for reasoning. Existing approaches typically reason over either the full table or a single reduced view, which can still obscure important row-column relationships. We introducePARTAB (Partition-Aware Reasoning overTables), a framework that constructs a structured evidence interface between the LLM and the table. PARTAB represents query-relevant evidence as semantically coherent, row-linked table regions and performs hierarchical selection over column groups and row-level partitions before composing the selected evidence for answer generation. We evaluate PARTAB on multiple table reasoning benchmarks, covering question answering, fact verification, and numerical reasoning. PARTAB consistently improves over full-table prompting and several recent table reasoning methods, achieving strong performance on WikiTableQuestions and TabFact while remaining competitive on numerical reasoning. Additional analyses show that semantic partitioning and targeted evidence selection improve evidence localization, substantially reduce the reasoning context, and provide larger benefits on complex tables. These results demonstrate the value of structured, partition aware evidence construction for scalable table reasoning.
### Title:
          A mesh-free multiresolution deep energy method with phase-field modeling of brittle fracture
 - **Authors:** Han Zhang, Mehrisadat Makki Alamdari, Babak Shahbodagh, Mohammad Vahab, Cosmin Anitescu, Timon Rabczuk, Elena Atroshchenko
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Phase-field modeling of brittle fracture removes the need to track cracks explicitly by recasting their evolution as the minimization of an energy functional. In return it requires a discretization dense enough to resolve a localization band whose width is set by a regularization length and whose path is not known in advance. We propose a mesh-free discretization in which a single neural network represents the displacement and phase fields and is trained by minimizing the incremental energy directly. The coordinates enter the network through a multiresolution feature encoding built from $C^1$ quadratic B-spline grids, so the finest scale the representation can express is set by choice rather than reached through slow training, and the energy is estimated by stratified Monte Carlo integration on points redrawn at every optimizer iteration. This pairing proves critical, since the crack fails to advance both when the integration points are held fixed and when the encoding is too coarse to represent the band, while each ingredient tolerates a wide range of settings once the other is in place. Because the representation is globally $C^1$, the second- and the fourth-order fracture energy densities run on the identical discretization. Across six problems, from single-edge-notched tension and shear to a thick-walled ring on a single spline patch, the computed load-displacement curves follow staggered finite element references at matched regularization length, with peak loads within about 1% on the single-edge-notched tests and within 8% where the crack pattern changes topology. On a public benchmark dataset of random multi-crack configurations the method classifies the active or dormant state of 90% of the seeded cracks in twenty zero-shot runs, where the deep Ritz baseline of the dataset authors fails.
### Title:
          Syn2RealTrack: Bridging the Gap Between Synthetic and Real-World Datasets for Online Multi-View Multi-Target Tracking
 - **Authors:** Duong Nguyen-Ngoc Tran, Ngoc Doan-Minh Huynh, Cu Quoc Le, Hoang-Khang Nguyen, Long Hoang Pham, Huy-Hung Nguyen, Quoc Pham-Nam Ho, Trinh Le Ba Khanh, Chi Dai Tran, Duong Khac Vu, Son Hong Phan, Hyung-Min Jeon, Jae Wook Jeon
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-camera 3D perception systems for warehouse scenes are trained largely on synthetic data and evaluated on physically captured environments. The resulting synthetic-to-real gap, which corrupts ground-plane localization and cross-camera identity association, is usually treated as one deficiency for a single domain-adaptation module to absorb; we argue instead that it enters the pipeline at three separable points: the camera calibration, the object shape prior, and the assumption that the object census is known, each admitting a different local remedy. Our online pipeline, Syn2RealTrack, follows this decomposition: lens distortion is recovered from images alone under a calibration that provides none, detections are fused across views by a visibility-weighted part-based descriptor that abstains on occluded parts rather than guessing, person height is measured in closed form from calibration instead of copied from a synthetic prior, and a closed-world cardinality prior is paired with a causal filter that removes the phantom boxes the prior manufactures. The system therefore adapts by reallocating trust between geometry and appearance without retraining a feature extractor. On the AI City Challenge 2026 Track~1 evaluation server it reaches a 3D Higher Order Tracking Accuracy (HOTA) of 52.0118%. The code will be released at this https URL
### Title:
          FARCA: Fact-Aligned Reliability-Aware Credit Assignment for Reinforcement Learning with Factual Supervision
 - **Authors:** Qiming Xie, Wenjie Zheng, Xiangqing Shen, Rui Xia
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 To reduce the hallucination risk caused by outcome-driven rewards in large language models trained through reinforcement learning with verifiable rewards, existing mitigation approaches introduce process-level factual supervision. However, due to coarse-grained aggregation of factual signals and the lack of reliability assessment for these signals, they create a mismatch between fact verification and policy updates. We term this noisy factual credit assignment and decompose it into two aspects: credit localization ambiguity and credit reliability ambiguity. To address these issues, we propose FARCA (Fact-Aligned Reliability-Aware Credit Assignment), a policy optimization framework that transforms factual supervision into localized, reliability-weighted token-level training signals. FARCA achieves fine-grained credit localization by aligning the granularity of fact verification with that of policy updates. It further introduces counterfactual evidence attribution, which uses the dependence of a factual judgment on key evidence as an empirical proxy for verification reliability to compute reliability weights. These weights modulate factual rewards and local policy advantages, reducing the influence of potentially unreliable signals on policy optimization. Experiments across different models and multiple factual reasoning benchmarks show that FARCA significantly improves model factuality while preserving general reasoning capabilities.
### Title:
          Beyond Static Interpretability: Anticipating Post-SFT Mechanisms from Pre-SFT Parameters for Better Tuning
 - **Authors:** Hang Chen, Jiaying Zhu, Wenya Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mechanistic Localization bridges mechanistic interpretability and post-training optimization by isolating critical parameters via interpretative approaches and then guiding parameter-efficient Supervised Fine-Tuning (SFT) in a ``locating-then-tuning'' paradigm. However, due to the retrospective nature of mechanistic interpretability, directly interpreting pre-SFT models introduces misleading conclusions. Specifically for novel tasks, initially identified neurons differ drastically from those governing the final model, introducing biases that actively disrupt SFT. To address this, we propose a forward-looking localization framework that accurately estimates the post-SFT interpretability state using only pre-SFT parameters and the target dataset. Theoretically, we model SFT as a continuous parameter evolution, leveraging Taylor expansion to rigorously bridge the post-tuning mechanistic objective with the pre-SFT model's dynamic gradients. Practically, we design dual-granularity (neuron- and component-level) localization pipelines. Extensive experiments demonstrate that our approach not only provides superior SFT guidance but also exhibits robust performance and temporal scalability across increasing model sizes. This work transcends the fundamental limitation of traditional interpretability-its inability to identify task-critical mechanisms before they are trained-pioneering a predictive frontier that unites mechanistic interpretability with targeted optimization.
### Title:
          VizAnchor: Decoding Manipulation Intent from Tampering Visualizations via Dual-Anchor Reasoning
 - **Authors:** Xiaotian Zhang, Huayuan Ye, Haiyang Zhang, Chenhui Li, Changbo Wang, Sicheng Song
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Data visualizations are widely used for communicating information, but they are also vulnerable to intentional manipulations that induce misleading interpretations. Existing methods focus on locating tampered regions or recovering hidden information, without explaining how the visualization has been manipulated or why the resulting changes may mislead viewers. We propose \textbf{VizAnchor}, a framework for visualization manipulation understanding through dual-anchor evidence construction and VLM-based reasoning. In the first stage, VizAnchor constructs a semantic anchor to recover authentic chart information and a spatial anchor to localize tampered regions. In the second stage, three specialized agents decode the manipulation. The misleader grounding agent analyzes a four-panel visual prompt to predict the misleader information. The chart narrative reconstruction agent takes the original and tampered charts as inputs and reconstructs their respective visual narratives. Finally, the intent inferring agent integrates the visual evidence and misleader information to infer the misleading intent. We further construct a dataset for tampering localization and a dataset for misleading intent inferring. Evaluation shows that VizAnchor accurately localizes manipulations and produces faithful explanations of their manipulation, misleaders, and misleading intents.
## Keyword: transformer
### Title:
          Data Predictability Shapes Weibull Weight-Scale Growth in Transformer Training
 - **Authors:** Tiexin Ding
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A trained transformer's weight magnitudes can be summarized by a two-parameter Weibull distribution whose shape $k \approx 1.2$ is stable across layers and models, so the scale $\lambda$ carries most training-induced movement. What corpus property sets how much $\lambda$ grows? Using the bigram conditional entropy $D = H(\text{next} \mid \text{prev})$, a training-free statistic computed before training, we find across controlled corruption families a learning-rate-conditioned law, $\lambda^2 - \lambda_0^2 = C_0(\eta) + C_1(\eta)(H_r - D)^{0.59}$, where $H_r$ is a matched-budget shuffle baseline. The convex exponent is inherited from an independently measured data-side saturation relation rather than fitted directly to the growth curve. After removing the two per-$\eta$ coefficients, 23 runs spanning an order of magnitude in learning rate collapse onto $(H_r - D)^{0.59}$ with unit slope ($R^2 = 0.941$; direct per-$\eta$ fits are weaker, $R^2 \approx 0.82$). Because $D$ is computed before training, the law is a forward predictor: an end-to-end self-validation recovers held-out within-family weight growth with 5.7% relative error. The readout holds at model and per-layer resolutions and across two tested architectures, with the functional form preserved and only the coefficients changing. It also marks its boundary: cross-corpus prediction over-predicts code, implicating redundancy as a second axis of a broader $\Phi(D,R,A,H)$ data-to-weight framework.
### Title:
          Transformer Accelerator (TFA): A Macro-Op INT8 Hardware Chip for Transformer Inference and Machine Translation
 - **Authors:** Shashank
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present the Transformer Accelerator (TFA), a synthesizable, parameterizable INT8 memory-to-memory engine for transformer inference. One time-multiplexed datapath handles prompt processing and autoregressive generation. TFA implements matrix multiplication, softmax, RMSNorm, elementwise, and copy/gather operations through eight 512-bit macro-op descriptors. Offline-compiled programs are fetched, validated, and dispatched through AXI interfaces, supporting encoder, decoder, and encoder-decoder models. The RTL combines an output-stationary multiply-accumulate array with ping-pong buffers that overlap DMA and compute, bit-exact reciprocal-square-root and divide units, key-value-cache and embedding addressing, and an abort-safe zero-padding write engine. A UVM environment byte-compares outputs against a bit-exact golden model. Across 25 tests and 34 constrained-random runs, TFA achieved zero mismatches, 100% functional coverage, and 94.96% code coverage. We compiled the t5-small encoder-decoder pipeline for English-to-French, German, and Romanian translation. On ten multilingual proverbs, TFA executed 70,320 descriptors and matched 37.9 MB of golden-model output with zero mismatches. INT8 output matched the floating-point reference token-for-token on five sentences; the rest produced valid alternative translations. Randomized-Hadamard reparameterization recovered about 11 dB of per-tensor INT8 signal-to-noise ratio across layers. The verification configuration achieved about 20x end-to-end speedup over a 22-thread CPU, while larger designs are projected to reduce energy per token by about 1000x. After RAM inference recoding, logic area fell to 2.73 mm2, and the design completed design-rule-clean synthesis and place-and-route on SkyWater sky130. TFA demonstrates end-to-end, bit-exact execution of pretrained transformers using compact hardware and compiler-managed quantization.
### Title:
          A survey detection channel overrides the pixels in an astronomical foundation model, and biases tomographic mean redshifts
 - **Authors:** Ihor Kendiukhov
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Foundation models for astronomy are trained on survey pixels together with the catalogue products derived from those pixels. Those catalogues are incomplete at a measurable rate, and a model trained on both inherits that incompleteness as a systematic. We audit AION-1, a 39-modality transformer trained on more than 200 million objects, using causal interventions on its inputs. Holding the image tokens byte-identical and editing only the survey segmentation map changes every quantity the model reports -- flux, size, ellipticity, redshift -- by 110-4400 times a matched placebo. The mechanism is detection gating, presence at the field centre (r = 0.47), not the light the mask encloses (r = 0.30); across 322 real blends the model ignores how the pipeline partitioned the light (R = -0.006). Nor is the preference specific to that channel: contradicted catalogue photometry leaves the model nine times worse than supplying no metadata at all. The Legacy Survey pipeline leaves 3.68% of targets with no segment covering their position. Propagating that rate, with a miss represented by the fields the pipeline actually returns, shifts tomographic mean redshifts by a median 0.71 times the LSST DESC requirement over 40 assignments and exceeds it in 12; observed positional errors take the worst bin to 8.3 times. Drawing the misses by their measured magnitude dependence rather than uniformly does not change it. Spectroscopy removes the effect, withholding the detection channel removes it at no measurable cost, and the effect grows with model scale. Two further limits lie in the tokeniser: its image codec resolves 28 effective states on source patches against 934 for the spectrum codec, and the redshift readout is quantisation-limited. Sparse dictionaries are unreliable causal handles: across 15, recovery spans 26-75% and moves up to 18 points on the seed alone.
### Title:
          From Triage to Discharge: A Survey of NLP Tasks, Methods, and Open Challenges in the Emergency Department
 - **Authors:** Dipankar Srirag, Aditya Joshi, Salil Kanhere, Padmanesan Narasimhan
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Emergency departments (EDs) operate under time pressure, generating multimodal data such as clinical conversations, triage notes, and discharge documents. Recent advances in natural language processing (NLP), particularly pretrained transformers and large language models, have created new opportunities to support language and time-intensive stages of emergency care. Yet existing surveys map clinical NLP across the broader hospital workflow or focus on specific tasks. This survey analyses 46 papers spanning the three phases of ED: triage, diagnosis, and disposition, covering tasks such as triage classification, clinical summarisation, automatic diagnosis, report generation, and discharge documentation. We examine modelling paradigms, evaluation practices, and emerging benchmarks and shared tasks. Across tasks, we identify common trends, including a shift from task-specific neural architectures to pretrained language models, growing interest in interactive clinical systems, and increasing attention to clinically grounded evaluation. Finally, we detail open challenges such as limited generalisability, noisy clinical inputs, and workflow constraints that inform future ED-NLP research.
### Title:
          CRISP: Calibration-Aware Visual State Space Duality for Remote Sensing Semantic Segmentation
 - **Authors:** Kangning Wang, Haopeng Zhang, Zhiguo Jiang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 State space models, especially Visual State Space Duality (VSSD), have emerged as efficient linear-time alternatives to Transformers for dense visual tasks. However, we observe that VSSD compresses spatial context into a global aggregation that suppresses high-frequency responses, causing excessive boundary smoothing in remote sensing semantic segmentation. To address this, we propose CRISP, a calibration framework with two components. Its core, the Duality Calibration Operator (DCO), restores local contrast and boundary responses through residual injection and frequency calibration within the VSSD backbone, without altering its linear complexity. To retain the recovered detail, an Orthogonal Multi-Prototype (OMP) head assigns multiple orthogonally constrained prototypes per class to model large intra-class variance. Extensive experiments on Potsdam, Vaihingen, and LoveDA show that, with approximately 30M parameters, CRISP achieves consistent gains in mean F1 (mF) and mIoU while remaining competitive with state-of-the-art methods. Code is available at this https URL.
### Title:
          Beyond Static and Linear: What Attention Constraints Best Fit Human Reading Times?
 - **Authors:** Lanni Bu, Xiulin Yang, Christian Clark, Alex Warstadt, Ethan Gotlieb Wilcox
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based language models are widely used as models of human language processing, yet their attention mechanisms allow lossless access to the full preceding context, unlike the limited memory systems of humans. We hypothesize that installing memory constraints into transformers' attention mechanisms can improve their fit to human behavioral data. While previous work has explored individual constraints in isolation, we conduct a systematic comparison of multiple attention-based memory mechanisms across different model sizes and training corpora, evaluating both psychometric predictive power for human reading times and grammatical competence. We additionally compare static constraints, in which the constraint strength is fixed throughout training, to dynamic memory curricula. We find that constraints that are sensitive to the content of intervening tokens consistently achieve the highest alignment with human reading times, outperforming distance-based constraints. We observe a dissociation between psychometric fit and grammatical competence under dynamic memory curricula, suggesting that Transformers cannot serve as a one-size-fits-all cognitive model.
### Title:
          Predicting Radiologist Expertise from 3D Gaze Patterns During CT Interpretation
 - **Authors:** Leila Khaertdinova, Anna Anikina, Claudia Mello-Thoms, Bulat Ibragimov
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate interpretation of volumetric CT requires efficient navigation of 3D image volumes and attention to diagnostically relevant regions. While eye-tracking has been widely studied in 2D medical imaging, its use for expertise assessment in CT settings remains limited. We propose a gaze-informed transformer framework for expertise classification in thoracic CT. Using a DINOv2 backbone, radiologist fixation patterns are integrated into volumetric feature learning through (1) a learnable log-space bias in self-attention and (2) gaze-weighted pooling of patch embeddings. We trained and evaluated our approach on 182 CT reading sessions from five radiologists with varying levels of experience. On a held-out test set, the model achieves an ROC-AUC of 0.91 and F1 score of 0.86, outperforming adapted methods. These findings suggest that incorporating visual search behavior into transformers may support objective, process-based expertise assessment in radiology. Code is available via this https URL.
### Title:
          Infant Care Video Dataset for Classification of Interventions Using Transformers
 - **Authors:** Igor Bogdanov, James Green
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Healthcare documentation in the neonatal intensive care unit (NICU) presents significant challenges, with nurses spending approximately 25\% of their time on record-keeping, while up to 60\% of interventions remain undocumented. Motivated by the need to detect interventions from video automatically, we present the Infant Care Video Dataset (ICVD), a collection of 4,144 videos spanning 12 simulated intervention classes designed for developing automated documentation systems. Our manikin-based approach systematically varies conditions, such as camera angle and clinician skin tone, while ensuring privacy compliance. Using video transformer architectures (TimeSformer and MotionFormer), we establish strong baseline performance (93.97\% and 93.17\% top-1 accuracy) among the 12 infant care classes. Our ablation study comparing temporal models with a framewise approach (23.17\% accuracy) demonstrates a 70.80\% performance gap, validating the need for temporal modeling. The ICVD provides a foundation for developing automated documentation systems to reduce clinical burden in neonatal care environments and improve existing practices.
### Title:
          ShardMeter: Sharded and Geo-Distributed Training Without the Guesswork
 - **Authors:** Tim Beringer (1), Patrick Diem (1), Felix Wolf (1), Arya Mazaheri (1 and 2) ((1) Technical University of Darmstadt, (2) PanocularAI)
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Training large-scale AI models often outgrows a single data center, demanding sharded, multi-cluster, and decentralized training. However, the huge space of resource allocations makes exhaustive benchmarking and manual tuning impractical, while performance depends on tightly coupled factors like model size, GPU memory, batch size, bandwidth, and sharding strategy. We introduce ShardMeter, a lightweight analytical performance model that predicts the end-to-end runtime of transformer-based workloads across arbitrary sharded, distributed, and even decentralized training. Given a model's characteristics and a target hardware topology, ShardMeter estimates per-GPU and per-island throughput, training cost, total wall-clock time, and identifies performance bottlenecks. Our analysis reveals diminishing-return regimes as island size increases, quantifies transitions between compute- and communication-bound scaling, evaluates hyperparameter trade-offs, and models cost-throughput for large-scale decentralized training. ShardMeter exposes these insights to quickly explore the configuration space, choose near-optimal deployment plans, and avoid costly trial and error.
### Title:
          Pipeline-Native Transformers: Co-Designing Model Architecture and CPU Inference for Bandwidth-Efficient Autoregressive Decode
 - **Authors:** Tom Poperszky
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Machine Learning (cs.LG); Performance (cs.PF)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Single-token autoregressive decode on CPUs is bound by memory bandwidth, not arithmetic: a modern CPU sustains roughly 1 TFLOP/s of compute but only about 50 GB/s from main memory, and each generated token must stream every active weight once. This report argues that the most effective response is to co-design the model architecture and the inference runtime together. It presents cflow, a CPU-first streaming engine, alongside a family of pipeline-native transformer architectures whose inter-layer dependency graphs are constructed to permit a vertical, stage-major execution schedule. cflow stores weights as L2-sized tiles in compute-consumption order, reads only the top-k experts of each mixture-of-experts layer, fuses projections, and executes a delay-aware schedule from per-model dependency parameters. Across five architectures trained on TinyStories, one (arch2_4_combined) achieves a 2.00x reduction in critical-path weight bandwidth (9.00 to 4.50 MB/token) within 0.24 perplexity of the best candidate, and the tile layout incurs 7.29x fewer L1-data read misses than a row-major baseline. On a 30.9-billion-parameter pipeline-native MoE, cflow decodes at 5.94 tokens/s (tok/s) on a 32-vCPU Ice Lake server, ahead of this http URL (4.75) and the vLLM CPU backend (1.65) on comparably sized dense models. Realizing the expert-delay window as asynchronous I/O overlap on a disk-resident expert tier yields a further net win of up to 1.68x, matching the overlap model within 1%. Measurement refutes one of the eight design claims and leaves a second inconclusive; both are reported in full, with the conditions under which they would hold.
### Title:
          In-Context Inpainting for Time Series Forecasting
 - **Authors:** Thang Nguyen, Dung Nguyen, Romero Morais, Truyen Tran
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose ICI-Time, a novel framework that reframes time series forecasting as a visual inpainting task, leveraging the generalisation power of large vision models (LVMs). Unlike methods that require specialised temporal architectures and extensive domain-specific training, ICI-Time transforms time series into structured visual representations (area charts) and applies visual in-context learning, reformulating forecasting as pattern completion within a grid-structured prompt that pre-trained vision transformers can solve without fine-tuning or architectural modification. Temporal dependencies are represented through spatial layout, with a consistent, invertible mapping between numerical and visual domains. Extensive experiments across epidemiology, meteorology, and power systems demonstrate that ICI-Time performs competitively against deep learning baselines and shows promising adaptability under limited-data settings, introducing a new paradigm that bridges temporal and visual domains.
### Title:
          Gen2Physics: Grounding Generated 3D Meshes in Physics via Multi-View Material Decomposition
 - **Authors:** Mauro Comi, Jordi Serrano Berbel, Kevis-Kokitsi Maninis, Philipp Henzler, Manuel Sanchez
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While state-of-the-art generative models produce high-fidelity 3D meshes, these outputs lack the physical properties required for interactive simulation, gaming, or robotics. We introduce Gen2Physics, a unified and automated framework that grounds generated meshes in physics by automatically decomposing them into their constituent material components. Unlike prior approaches, which focus on volumetric representations incompatible with standard physics engines, Gen2Physics operates directly on meshes to produce immediately simulation-ready assets. Our pipeline integrates a fine-tuned Vision Transformer for dense material segmentation, a robust 2D-to-3D consistency projection, and a Vision-Language Model (VLM) guided refinement that leverages contextual reasoning to assign physical properties and infer internal geometry (solid vs. hollow). By converting surface patches into volumes with distinct densities, our method enables physically plausible dynamic simulations. Experimental results on the ABO-500 and PartNet-Material benchmarks demonstrate that Gen2Physics more than doubles the material segmentation accuracy of prior physics-grounding pipelines (15.6 to 48.3 mIoU), while matching the mass-estimation accuracy of volumetric methods and being the only approach to output watertight per-material sub-meshes.
### Title:
          HAP: Head-Adaptive Visual Token Pruning via Cross-Modal Alignment
 - **Authors:** Yuanhao Sun, Huawei Ji, Yuan Jin, Cheng Deng, Luoyi Fu, Xinbing Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent Vision-Language Models encode high-resolution images into long visual token sequences, incurring prohibitive prefill costs. To compress them, existing methods score each visual token by averaging text-to-visual attention uniformly across all heads, which assumes every head matches the query. However, our empirical analysis shows that misaligned heads dominate the average, amplifying background tokens and drowning out fine-grained cues. To address this, we propose PAQ (Prompt-Grounded Attention Quality), a metric quantifying how well each head aligns the prompt with image regions. Built on PAQ, our pruning proceeds in three stages. Given a target FLOPs budget, we first partition the transformer layers into groups and allocate a visual token budget to each. Within each group, we then aggregate per-head attention maps via PAQ-weighted softmax into a group-level matrix. Finally, we score visual tokens by this matrix's magnitude and retain the allocated budget per group. By weighting heads with PAQ, our method scores tokens by attention signals that more faithfully reflect prompt relevance, rather than diluting them through uniform averaging. Across 18 benchmarks, our method delivers state-of-the-art trade-offs. Specifically, on LLaVA-1.5-7B (9 tasks), retaining only \textbf{5.6\%} tokens preserves \textbf{99.1\%} of the original performance, surpassing the strongest baseline AutoPrune by 4.2 points. Code is available in this https URL.
### Title:
          MnemoDyn: Learning Resting State Dynamics from 40K FMRI sequences
 - **Authors:** Sourav Pal, Viet Luong, Hoseok Lee, Tingting Dan, Guorong Wu, Richard Davidson, Won Hwa Kim, Vikas Singh
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a dynamical-systems based model for resting-state functional magnetic resonance imaging (rs-fMRI), trained on a dataset of roughly 40K rs-fMRI sequences covering a wide variety of public and available-by-permission datasets. While most existing proposals use transformer backbones, we utilize multi-resolution temporal modeling of the dynamics across parcellated brain regions. We show that MnemoDyn is compute efficient and generalizes very well across diverse populations and scanning protocols. When benchmarked against current state-of-the-art transformer-based approaches, MnemoDyn consistently delivers superior reconstruction quality. Overall, we find that with such large-scale pre-training on (non-proprietary) rs-fMRI datasets, we get a highly performant model for various downstream tasks. Our results also provide evidence of the efficacy of the model on small sample size studies which has implications for neuroimaging studies at large where resting state fMRI is a commonly acquired imaging modality.
### Title:
          Luce: Relightable Gaussians for 3D Asset Generation
 - **Authors:** Mayank Singh, Michele Stoppa, Alvise Memo, Rui Yu, Harsha Kalli, Srimanth Gunturi, Muhammad Ahmed Riaz, Behrooz Shahsavari, Waleed Abdulla, David E. Jacobs
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-fidelity image-to-3D generation requires a 3D representation that captures both geometry and appearance. To support relighting and integration into standard rendering pipelines, the representation should include physically based rendering (PBR) modalities such as albedo, metallic-roughness, and surface normals. We propose Luce, a 3D representation that unifies geometry and PBR materials within a voxelized multimodal Gaussian cloud, using dedicated Gaussian primitives for each modality. A variational autoencoder compresses this representation into a unified material-aware latent space. A rectified-flow transformer generates this latent from a single image, conditioned on multi-layer features from a pretrained image encoder that preserve both semantic context and fine spatial detail. The latent then decodes into relightable PBR Gaussians and an optional textured mesh with a tangent-space normal map. On Toys4K, Luce achieves state-of-the-art single-image-to-3D generation, improving FID by 28% over the strongest baseline. We further introduce a benchmark of AI-generated images, on which Luce improves the CLIP image-alignment score over the best baseline (0.8519 vs. 0.8299). Luce generates relightable, geometrically accurate, and materially faithful assets that preserve fine details such as text, logos, and inscriptions.
### Title:
          Rethinking Pre-Training and Augmentation for Zero-Shot Cross-City Object Detection
 - **Authors:** Long Hoang Pham, Quoc Pham-Nam Ho, Huy-Hung Nguyen, Duong Nguyen-Ngoc Tran, Ngoc Doan-Minh Huynh, Cu Quoc Le, Hoang-Khang Nguyen, Hyung-Min Jeon, Chi Dai Tran, Son Hong Phan, Duong Khac Vu, Trinh Le Ba Khanh, Jae Wook Jeon
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-world deployment of traffic surveillance systems is bottlenecked by geographic domain shift, in which models trained in one city underperform when applied to an unseen target city. Conventional domain adaptation relies on hyperparameter-sensitive architectures or direct profiling of target data. Both are fundamentally precluded in privacy-conscious ecosystems that require completely blind training and evaluation loops. In this setting, we explore the effects of pre-training and augmentation in addressing the domain shift problem. Specifically, we propose a new modular training pipeline for object detection structured around two core orthogonal pillars: (1) a multi-dataset pre-training strategy featuring a class-agnostic objectness distillation to decouple structural vehicle geometry from semantic taxonomies, and (2) a domain-resilient augmentation stream featuring a novel Grayworld transformation that forces global attention heads to strip volatile chromatic shortcuts in favor of robust shape priors. When evaluated with the real-time transformer-based detector RF-DETR, our framework bridges cross-city distribution gaps while using limited GPU memory (16GB). Our optimized variants, RF-DETR-HR and RF-DETR-Grayworld, deliver a substantial empirical gain of +24.29 over the baseline, achieving 1st place (47.53 mAP) on the AI City Challenge Track 6 leaderboard. Code and data are available at: \href{this https URL}{SKKUAutoLab/aic26\_cross\_city}.
### Title:
          Keep-or-Drop? Adaptive Tokenizer for Compact Video Representation
 - **Authors:** Yeonkyeong Lee, Hyunsung Go, Jongmin Kim, Sewoong Lim, Donghoon Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Latent diffusion models have emerged as a dominant framework for high-fidelity image and video synthesis, operating in compact latent spaces with variational autoencoders (VAEs) to enhance computational efficiency without compromising visual quality. However, conventional VAEs are suboptimal for video data as they employ fixed compression ratios that cannot adapt to the varying complexity of spatio-temporal content. We present KATok (Keep-or-Drop? Adaptive Tokenizer for Compact Video Representation), a transformer-based VAE that incorporates an adaptive token selector which is jointly learned with latent tokens. By evaluating each token's content-richness as keep-or-drop probability, the token selector effectively discards uninformative tokens, naturally allowing data-dependent compression. Applying adaptive tokenization to diffusion models may cause spatial misalignment, as token dropping can disturb the original spatio-temporal structure. To alleviate this issue, we propose two position-prediction strategies: cascaded and joint generation, to ensure spatial consistency. We empirically show that our model achieves strong reconstruction and generation quality at a state-of-the-art compression ratio. Further analysis on video data reveals that this improvement is primarily achieved by reducing spatio-temporal redundancy and removing uninformative tokens, as supported by both quantitative and qualitative results.
### Title:
          B-MIM: Biased Masked Image Modeling for Generalizable Segmentation of Fine-Grained Anatomical Structures
 - **Authors:** Sebastián González, Karen Sanchez, José M. Saavedra, Marcelo Pizarro, Bernard Ghanem
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-supervised pretraining enables transferable representations for medical imaging, yet most CT encoders remain biased toward coarse semantic understanding, limiting their sensitivity to fine-grained anatomical structures such as vessels or small tumors. In this paper, we introduce Biased Masked Image Modeling (B-MIM), a modification of the iBOT objective that stochastically reduces global semantic alignment to prioritize local patch reconstruction. This bias encourages the encoder to capture high-frequency morphological details and structural continuity. We curate a multi-institutional CT abdominal dataset of 9,955 filtered studies from 17 public sources and pretrain a 3D Swin Transformer backbone using B-MIM. Across inter-dataset experiments on liver vessel segmentation, the proposed encoder improves topological fidelity (clDice) and achieves competitive Dice scores in tumor segmentation, compared to fully fine-tuned baselines, despite updating only a fraction of the parameters. Our results suggest that reducing global semantic pressure during pretraining enhances generalization to intricate anatomical structures.
### Title:
          MaST: Motion-aware Sparse Pipeline for Lightweight Object Tracking
 - **Authors:** Qingmao Wei, Fagui Liu, Dengke Zhang, Qingze He, Quan Tang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based object trackers are renowned for their strong performance, yet dense token processing often leads to prohibitive computational cost, limiting real-time deployment on edge devices. While recent works explore token pruning to reduce computation, they often stop short of an end-to-end sparse pipeline, as early-layer token scores can be noisy without a motion prior, and many trackers ultimately fall back to dense reshaping to feed the dense prediction head that partially negates the savings. We introduce Motion-aware Sparse Tracker (MaST), a sparse tracking framework that makes sparsity effective from tokens to boxes. First, MaST injects a lightweight motion prior to refine cross-attention-based importance scores, enabling earlier and more stable token reduction in the search region. Second, we introduce a natively sparse prediction head that operates directly on the retained unstructured tokens with a score-first, regress-once design, eliminating dense padding/reshaping and reducing redundant computation. Extensive experiments on multiple benchmarks demonstrate that MaST establishes new state of the art among lightweight trackers, where MaST-tiny attains 63.8 AUC on LaSOT and 80.1 SUC on TrackingNet, surpassing the prior best AsymTrack-S by +1.0 AUC and +2.2 SUC while running at 152 FPS on Jetson Nano, nearly twice as fast as AsymTrack-S at 88 FPS. Code is available at this https URL.
### Title:
          Shortcut Before Circuit: Document Statistics Time In-Context Conflict Resolution
 - **Authors:** Yijun Liao, Fanwei Liang
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 When a context asserts two values for one fact, a model commits to a cue -- recency, repetition, position -- but natural data rarely makes these disagree, so behavior cannot reveal which. We train 26M-parameter transformers on a synthetic language where recency and rarity are exactly coextensive, and separate them with a minimal causal edit that inverts one cue while holding the truth, token count and answer position fixed. All 75 runs reach accuracy >= 0.999, including where the trivial heuristic fails, so no held-in evaluation distinguishes them. Under intervention the per-cell readout does not replicate: 13 of 25 cells differ by more than 0.3 in sign fraction across three seeds, the largest by 0.879 against a standard error of 0.025. The construction predicts this -- coextensive rules leave the objective indifferent between them -- and the variance is ordered by how much of the optimization each comparison releases. What replicates is timing: escape from a positional shortcut with a closed-form ceiling, monotone in redundancy. Probed before that escape, attribution reverses sign in 32 of 75 runs at unchanged accuracy, and gating on circuit formation is necessary but not sufficient. The corpus fixes when a mechanism appears, not which one -- a criterion for when mechanistic attribution to data is available at all, and our construction makes the unavailable case exact.
### Title:
          Mahalanobis-Based Multi-Head Attention for Complex State Propagation
 - **Authors:** Xiaohe Li
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we propose \textbf{Mahalanobis-Based Multi-Head Attention} (MHA-CSP), a novel attention mechanism that replaces the standard dot-product with a \textbf{Mahalanobis distance-based RBF kernel}, which effectively computes attention in an infinite-dimensional feature space without increasing the parameter count. Crucially, the positive definiteness of the Mahalanobis distance enables a \textbf{direct construction of Tree Attention}: attention scores are built directly from accumulated distances, with a LogSumExp correction that rectifies the raw distance by subtracting the log-sum of edge exponentials. Moreover, the multi-head Mahalanobis distance matrices are themselves repurposed to construct an \textbf{attention meshing mechanism}, enabling cross-head kernel collaboration that simultaneously boosts accuracy and training efficiency. Extensive experiments demonstrate that MHA-CSP, with only 119K parameters and \textbf{teacher forcing applied exclusively at the final hidden state}, consistently outperforms Transformer and GCN baselines trained from scratch under identical conditions on long-sequence state tracking tasks. While these baselines rely on dense attention or graph propagation, MHA-CSP achieves robust structured reasoning via synthetic distance rectification---powered by Mahalanobis-based attention---and efficient information bypass inherited from the CSP backbone. This result highlights the effectiveness of complex-valued state propagation with collaborative multi-head rectification in capturing symbolic structures, establishing a new efficiency-performance trade-off for structured reasoning.
### Title:
          Low-Rank Ternary Adaptation for Fine-Tuning Transformers
 - **Authors:** Alexandru-Dragos Manolache, Yunqiang Li, Jan van Gemert
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ternary transformers offer extreme memory and compute efficiency, but existing low-bit LoRA-based methods cannot directly fine-tune ternary weights. Current approaches either require dequantization, restoring low-bit base weights to higher precision to merge with adaptation weight, or update only quantization parameters, preventing a merged model that remains ternary. We propose ternary multiplicative adaptation, which represents discrete updates of ternary weights such as sign flips or zeroing through a low-rank Kronecker factorization into two small ternary matrices applied element-wise to ternary weights. This design is parameter-efficient and expressive, preserves the ternary domain, and supports direct merging without dequantization. Experiments on six models across language and vision, including ternarized LLaMA-3 1B and 3B and a ternary ViT-B/16, demonstrate that our method recovers much of the performance lost to quantization and outperforms strong low-bit and ternary baselines. Code is available at this https URL.
### Title:
          SeisMamba: Low-Latency Single-Station Seismic Magnitude Estimation for Spatially Distributed Earthquake Early Warning
 - **Authors:** Quenton Yeo, Zhaoge Bi, Linghan Huang, Luke Stephen Higgins, Flora Salim, Huaming Chen
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rapid earthquake magnitude estimation is central to earthquake early warning, yet many operational systems depend on dense regional seismic networks and region-specific calibration. This creates a spatial coverage barrier for high-risk areas with sparse sensing infrastructure. Single-station learning offers a lower-cost alternative, but existing models often face an accuracy--latency trade-off and may degrade under regional distribution shift. We present SeisMamba, a lightweight Mamba-based architecture for low-latency magnitude estimation from minimally processed three-component seismic waveforms recorded at a single station. SeisMamba combines hierarchical convolutional encoding, sparse selective state-space modelling, multi-scale feature fusion, and an auxiliary temporal prediction head to support efficient long-sequence waveform analysis. On the STEAD benchmark, SeisMamba achieves the best MSE, RMSE, and $R^2$ among tested baselines while requiring only 0.55 ms for a batch of 32 waveforms on an NVIDIA T4 GPU, making it about three times faster than transformer-based baselines. We further conduct a Chile--Taiwan regional hold-out experiment as a diagnostic test of cross-region deployment, where SeisMamba retains useful performance on geographically unseen seismic regions. These results suggest that selective state-space waveform modelling provides a promising accuracy--latency backbone for spatially distributed, low-cost earthquake early warning.
### Title:
          Delayed Optimizer-State Transport Shapes Short-Horizon Training Decisions
 - **Authors:** Jinhui Guo
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computational Physics (physics.comp-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adaptive optimizers retain gradient history in moment variables, allowing a local change in loss weighting to alter later updates. We examine whether this delayed transport is large enough to change prospective short-horizon decisions. On committed future-minibatch sequences, we differentiate eight-step AdamW trajectories through the complete model--optimizer state and select exposure-matched Math--Code loss schedules before independent evaluation. Across 12 unused 0.3M Transformer histories, full transport lowers token-disjoint loss relative to an optimizer-aware immediate derivative in 10/12 histories (mean benefit $4.71\times10^{-4}$; exact one-sided sign test, $p=0.0193$). The two controllers act equally often but select different schedules in 60/96 windows. Crossed checkpoint--future-path tests attribute this reordering to the interaction between optimizer state and near-future data, while an independent Ising--CNN experiment shows that deleting moment-state transport destroys accurate response prediction. Full-transport scores also concentrate exact-rollout winners in larger candidate libraries, focusing finite-amplitude evaluation on a shortlist. On these committed short paths, optimizer memory and near-future data order are therefore actionable components of the training state, providing a mechanism-based criterion for when finite-horizon rather than one-step intervention is required.
### Title:
          Comparative Assessment of Deep Learning Architectures for Underwater Subsurface Kelp Forest Segmentation with The Kelp-o-Tron
 - **Authors:** Sundarabalan Balasubramanian, César Borja, Ana C. Murillo, Lexi N. Wilkes, Meredith L. McPherson, Kira A. Krumhansl, Jennifer A. Dijkstra, Jarrett E. K. Byrnes
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Submerged kelp forests are vital coastal ecosystems that support marine biodiversity and ecosystem dynamics, yet accurate underwater kelp segmentation remains challenging due to optical degradation, illumination variability, turbidity, overlapping vegetation, and complex benthic backgrounds. We systematically evaluated three deep learning semantic segmentation frameworks, ResNet34-U-Net, ResNet50-DeepLabV3, and a hybrid ResNet50-ASPP-Transformer architecture, for kelp detection using high-resolution underwater RGB imagery collected from northeastern U.S. coastal waters. A dataset of 3,395 SSeg assisted annotated image-mask pairs was developed for model training and validation, while geographically independent sites were used for quantitative and qualitative evaluation. All models used consistent preprocessing, augmentation, and evaluation protocols. On independent test data, ResNet50-DeepLabV3 achieved the highest Dice (0.7120) and Intersection over Union (IoU; 0.6267), followed by ResNet34 U Net (Dice 0.6868; IoU 0.5978). The hybrid ASPP Transformer achieved the highest pixel accuracy (0.8528) but lower Dice (0.6437) and IoU (0.5746). External qualitative evaluation further showed that DeepLabV3 produced more consistent segmentation across varying environmental conditions, image qualities, and benthic habitats. Overall, ResNet50-DeepLabV3, termed Kelp-O-Tron, provided the best balance of segmentation accuracy, robustness, and generalization. The dataset, annotation workflow, and comparative evaluation provide resources for advancing automated underwater habitat mapping and ecological monitoring.
### Title:
          Interpretable Fundus Image Classification via Ring-Based Retinal Vasculature Features
 - **Authors:** Xiaoyan Li, Shixin Xu, Arvind Gupta, Huaxiong Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Retinal fundus photography is widely used for screening and monitoring ocular diseases, but many modern classification pipelines rely on deep latent representations and provide limited interpretability. This study develops an interpretable fundus image classification framework based on a ring-structured representation of the retinal vasculature centered on the optic disc. The method quantifies vessel geometry, color appearance, oxygenation-related vascular appearance, and vessel--background entropy within concentric retinal regions. These physiologically motivated descriptors are derived from vessel masks, image intensities, and optical-density measurements and aggregated across rings to capture spatial variation in vascular properties. Using only quantitative vascular descriptors, the proposed method achieved strong classification performance across three public fundus datasets. On HRF, it achieved 91.1\% accuracy using automatically generated vessel masks, matching RETFound, a vision transformer pretrained on large-scale retinal fundus image data, under the same evaluation setting. Additional analyses suggest that pretrained image models are sensitive to acquisition-related spatial cues, including fundus scale and retinal position within the field of view, as well as broader non-vessel image characteristics. This framework may support interpretable disease classification, quantitative retinal phenotyping, and retinal biomarker discovery without requiring large task-specific training datasets.
### Title:
          RACE: Scalable Statistical Estimation of Functional Consistency in LLM Neurons
 - **Authors:** Runyu Wang, Bo Liu, Xiaxin Zhang, Yu Han, Jiawei Cao, Xiaoye Zhang, Zhe Zhang, Yifan Yang, Peng Ping
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Discovering stable neuron behavior across entire domains remains a challenge in mechanistic interpretability. Existing methods often rely on instance-level point estimates or computationally expensive procedures, which either obscure population-level variability or limit scalable domain-wide analysis. We present RACE (Residual Alignment for Consistency Estimation), a forward-pass statistical framework that evaluates the domain-wide functional consistency of Transformer neurons. Perturbation experiments demonstrate that RACE achieves superior domain specificity compared to gradient-based point estimates. Meanwhile, token-distribution-level results verify the association between the selected neurons and the target domain. Furthermore, its computational overhead is two orders of magnitude lower than that of gradient-based methods.
### Title:
          MoTE: Mixture of Task Experts for Multi-Task Video Understanding
 - **Authors:** Muhammad Asad Ali, Umar Khan, Nadia Robertini, Didier Stricker
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Procedural video-language models must solve heterogeneous tasks from the same visual evidence, including action recognition, forecasting, and procedure prediction. Dense transformer decoders share the same feed-forward networks across tasks, which can entangle task behavior and make controlled capability expansion difficult. Sparse Mixture-of-Experts (MoE) decoders provide conditional computation, but token-level learned routing is not naturally aligned with task-level procedural objectives. We propose MoTE (Mixture of Task Experts), a decoder architecture that converts large language model feed-forward networks into task-specific experts while keeping the multimodal backbone shared. Each example follows one sample-level task route, so active task-expert computation remains independent of the number of stored task experts. We instantiate this design as VideoLLM-MoTE and evaluate it on five COIN benchmarks using explicit task routes. The five-expert model activates ~2B LLM parameters per sample and achieves higher average top-1 accuracy than recent VideoLLM baselines. Under the same expert topology, it improves over dense all-expert activation and learned sparse-routing controls. These results show that task-structured routing provides an interpretable and compute-efficient decoder alternative for multi-task video-language learning.
### Title:
          MoE-based Feature Adapter for Prompt-free Binary Coronary Artery Segmentation in X-ray Angiography
 - **Authors:** Lin Xi, Yingliang Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate segmentation of coronary arteries in X-ray angiography videos is essential for quantitative coronary analysis and image-guided interventions. However, accurate segmentation remains challenging because coronary vessels are thin and exhibit low contrast, while the presence of catheters, guidewires, and complex anatomical background structures can further interfere with vessel delineation. Existing U-Net- and Transformer-based models provide strong baselines, but their shared feature-adaptation pathways may be insufficient for heterogeneous angiographic appearances. In this paper, we propose a prompt-free mixture-of-experts (MoE) feature adapter for binary coronary artery segmentation. Built upon parameter-efficient Vision Transformer adapters, the proposed method uses multiple lightweight experts with input-dependent top-$k$ routing to adaptively refine vessel-related features while limiting active computational cost. Experiments on MOSXAV and external evaluation on XACV show that the proposed method outperforms representative baselines and improves cross-dataset generalisation. These results suggest that MoE-based adapter learning is effective for robust coronary artery segmentation in X-ray angiography videos.
### Title:
          Auditing Return Conditioning as a Control Knob: An Offline Diagnostic for Decision Transformer Recommendation
 - **Authors:** Jingyu Wang
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Offline return-to-go (RTG) sweeps can test whether a recommender conditioned on return is controllable, but the intervention is rarely audited. Rewriting every historical RTG token creates an increasingly synthetic context, while rewriting only the current token is more local. We test this distinction in an offline setting with a fixed window. On MovieLens 25M and MyAnimeList 2020 (MAL), we evaluate a Decision Transformer using an RTG locality ladder, a control without RTG, a logged match and score reward check, and a within-trajectory shuffled RTG ablation. On MovieLens, a $K=20$ intervention that covers the full context, applied only to real context positions, shifts the share of Crime predictions by $+23.61 \pm 2.96$ percentage points from the validation 5th to 95th percentile, whereas changing only the current slot shifts it by $+1.77 \pm 1.17$ points. The shuffled RTG model largely removes this response ($+2.08 \pm 1.20$ points at $K=20$). On MAL, the same protocol does not produce a Drama response: $K=20$ changes Drama by $-0.03 \pm 0.07$ points, and $K=1$ by $-0.01 \pm 0.01$. Genre prediction accuracy is numerically close across real RTG, no RTG, and shuffled RTG, and at $K=1$ logged match rates and matched ratings change little. Because dataset and focus-genre selection were exploratory, these magnitudes are descriptive; the cross-diagnostic pattern across locality, shuffled RTG, and the null result on MAL does not establish reward control. We propose four checks: intervention locality, a no-RTG baseline, a reward check, and RTG-content ablation.
## Keyword: autonomous driving
### Title:
          CARE: Camera-Residual Reserves for First Sightings in Adaptive LiDAR Sensing
 - **Authors:** Jiachen Gong, Yun Li, Ehsan Javanmardi, Wencan Mao, Manabu Tsukada
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adaptive LiDAR scanning concentrates a limited sensing budget on regions of interest predicted from past object tracks, lowering data volume in autonomous driving while maintaining detection accuracy. However, existing scanning policies face three challenges. First, history-driven approaches depend on past tracks, so unseen objects are detected late or missed. Second, random or uniform sampling outside the predicted regions has no awareness of where new objects appear. Third, camera-guided alternatives spend budget on all camera detections, resampling objects already covered, costing recall in crowded scenes and range when budgets are scarce. This paper introduces the CAmera-REsidual reserve (CARE), a training-free allocation rule that reserves part of a fixed ray budget for the directions of current camera detections that the track forecasts cannot explain; the rest follows the base history policy, and unused reserve returns to a random floor. The paper makes three contributions. First, a leakage-free ray-budget evaluation on nuScenes (150 scenes, 4,148 events) measuring the first-sighting loss of history-driven scanning, with a strict-causal variant using the preceding keyframe. Second, CARE raises first-sighting recall by 5.2, 5.2, and 4.3 points at 10%, 20%, and 35% budgets over the history policy, with paired intervals excluding zero; the camera cue drives this gain, and the first-sighting versus overall trade-off is a budget-dependent Pareto choice. Third, a safety-bounded forgetting module that releases budget from receding or static tracks beyond a speed-dependent guard distance; at tight budgets, forgetting without the guard significantly harms near-field recall, so the guard is what keeps it safe. The pipeline runs end to end on a real vehicle and, in closed-loop simulation, detects an occluded pedestrian earlier and brakes more reliably than history-driven scanning.
