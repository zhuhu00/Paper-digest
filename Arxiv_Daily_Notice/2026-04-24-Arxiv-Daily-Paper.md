# Showing new listings for Friday, 24 April 2026
## Keyword: SLAM
### Title:
          SLAM as a Stochastic Control Problem with Partial Information: Optimal Solutions and Rigorous Approximations
 - **Authors:** Ilir Gusija, Fady Alajaji, Serdar Yüksel
 - **Subjects:** Subjects:
Robotics (cs.RO); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Simultaneous localization and mapping (SLAM) is a foundational state estimation problem in robotics in which a robot accurately constructs a map of its environment while also localizing itself within this construction. We study the active SLAM problem through the lens of optimal stochastic control, thereby recasting it as a decision-making problem under partial information. After reviewing several commonly studied models, we present a general stochastic control formulation of active SLAM together with a rigorous treatment of motion, sensing, and map representation. We introduce a new exploration stage cost that encodes the geometry of the state when evaluating information-gathering actions. This formulation, constructed as a nonstandard partially observable Markov decision process (POMDP), is then analyzed to derive rigorously justified approximate solutions that are near-optimal. To enable this analysis, the associated regularity conditions are studied under general assumptions that apply to a wide range of robotics applications. For a particular case, we conduct an extensive numerical study in which standard learning algorithms are used to learn near-optimal policies.
## Keyword: odometry
There is no result 
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Ufil: A Unified Framework for Infrastructure-based Localization
 - **Authors:** Simon Schäfer, Lucas Hegerath, Marius Molz, Massimo Marcon, Bassam Alrifaee
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Infrastructure-based localization enhances road safety and traffic management by providing state estimates of road users. Development is hindered by fragmented, application-specific stacks that tightly couple perception, tracking, and middleware. We introduce Ufil, a Unified Framework for Infrastructure-Based Localization with a standardized object model and reusable multi-object tracking components. Ufil offers interfaces and reference implementations for prediction, detection, association, state update, and track management, allowing researchers to improve components without reimplementing the pipeline. Ufil is open-source C++/ROS 2 software with documentation and executable examples. We demonstrate Ufil by integrating three heterogeneous data sources into a single localization pipeline combining (i) vehicle onboard units broadcasting ETSI ITS-G5 Cooperative Awareness Messages, (ii) a lidar-based roadside sensor node, and (iii) an in-road sensitive surface layer. The pipeline runs unchanged in the CARLA simulator and a small-scale CAV testbed, demonstrating Ufil's scale-independent execution model. In a three-lane highway scenario with 423 and 355 vehicles in simulation and testbed, respectively, the fused system achieves lane-level lateral accuracy with mean lateral position RMSEs of 0.31 m in CARLA and 0.29 m in the CPM Lab, and mean absolute orientation errors around 2.2°. Median end-to-end latencies from sensing to fused output remain below 100 ms across all modalities in both environments.
### Title:
          Cross-Modal Phantom: Coordinated Camera-LiDAR Spoofing Against Multi-Sensor Fusion in Autonomous Vehicles
 - **Authors:** Shahriar Rahman Khan, Raiful Hasan
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous Vehicles (AVs) increasingly depend on Multi-Sensor Fusion (MSF) to combine complementary modalities such as cameras and LiDAR for robust perception. While this redundancy is intended to safeguard against single-sensor failures, the fusion process itself introduces a subtle and underexplored vulnerability. In this work, we investigate whether an attacker can bypass MSF's redundancy by fabricating cross-sensor consistency, making multiple sensors agree on the same false object. We design a coordinated, data-level (early-fusion) attack that emulates the outcome of two synchronized physical spoofing sources: an infrared (IR) projection that induces a false camera detection and a LiDAR signal injection that produces a matching 3D point cluster. Rather than implementing the physical attack hardware, we simulate its sensor-level outcomes by inserting perspective-aware image patches and synthetic LiDAR point clusters aligned in 3D space. This approach preserves the perceptual effects that real IR and IEMI-based spoofing would create at the sensor output. Using 400 KITTI scenes, our large-scale evaluation shows that the coordinated spoofing deceives a state-of-the-art perception model with an 85.5% successful attack rate. These findings provide the first quantitative evidence that malicious cross-modal consistency can compromise MSF-based perception, revealing a critical vulnerability in the core data-fusion logic of modern autonomous vehicle systems.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          DualSplat: Robust 3D Gaussian Splatting via Pseudo-Mask Bootstrapping from Reconstruction Failures
 - **Authors:** Xu Wang, Zhiru Wang, Shiyun Xie, Chengwei Pan, Yisong Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While 3D Gaussian Splatting (3DGS) achieves real-time photorealistic rendering, its performance degrades significantly when training images contain transient objects that violate multi-view consistency. Existing methods face a circular dependency: accurate transient detection requires a well-reconstructed static scene, while clean reconstruction itself depends on reliable transient masks. We address this challenge with DualSplat, a Failure-to-Prior framework that converts first-pass reconstruction failures into explicit priors for a second reconstruction stage. We observe that transients, which appear in only a subset of views, often manifest as incomplete fragments during conservative initial training. We exploit these failures to construct object-level pseudo-masks by combining photometric residuals, feature mismatches, and SAM2 instance boundaries. These pseudo-masks then guide a clean second-pass 3DGS optimization, while a lightweight MLP refines them online by gradually shifting from prior supervision to self-consistency. Experiments on RobustNeRF and NeRF On-the-go show that DualSplat outperforms existing baselines, demonstrating particularly clear advantages in transient-heavy scenes and transient regions.
## Keyword: mapping
### Title:
          Ternary Memristive Logic: Hardware for Reasoning Realized via Domain Algebra
 - **Authors:** Chao Li
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Artificial Intelligence (cs.AI); Emerging Technologies (cs.ET); Logic in Computer Science (cs.LO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Memristive crossbars store numerical weights needing aggregation and decoding; a single junction means nothing alone. This paper presents a fundamentally different use: each junction stores a complete, domain-scoped logical assertion (holds/negated/undefined). Ternary resistance states encode these values directly. We establish a structure-preserving mapping from a domain algebra to crossbar topology: domains become isolated arrays, specialization becomes directed wiring, relation typing controls inheritance gates, and cross-domain links become explicit registers. The physical layout thus embodies the algebra; changing wiring changes reasoning semantics. We detail an ICD-11 respiratory disease classification chip (1,247 entities, ~136k 1T1R junctions) enabling domain scoping, three-valued logic, transitive cascade, typed inheritance, and cross-axis queries. Behavioral simulation (sigma_log=0.15, SNR=20dB) shows error-free operation across 100,000 trials per task with wide tolerance margins. Where prior work unified representation and computation in software, this work unifies them in hardware: reading one junction answers one question, without symbolic interpretation.
### Title:
          Linear Image Generation by Synthesizing Exposure Brackets
 - **Authors:** Yuekun Dai, Zhoutong Zhang, Shangchen Zhou, Nanxuan Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The life of a photo begins with photons striking the sensor, whose signals are passed through a sophisticated image signal processing (ISP) pipeline to produce a display-referred image. However, such images are no longer faithful to the incident light, being compressed in dynamic range and stylized by subjective preferences. In contrast, RAW images record direct sensor signals before non-linear tone mapping. After camera response curve correction and demosaicing, they can be converted into linear images, which are scene-referred representations that directly reflect true irradiance and are invariant to sensor-specific factors. Since image sensors have better dynamic range and bit depth, linear images contain richer information than display-referred ones, leaving users more room for editing during post-processing. Despite this advantage, current generative models mainly synthesize display-referred images, which inherently limits downstream editing. In this paper, we address the task of text-to-linear-image generation: synthesizing a high-quality, scene-referred linear image that preserves full dynamic range, conditioned on a text prompt, for professional post-processing. Generating linear images is challenging, as pre-trained VAEs in latent diffusion models struggle to simultaneously preserve extreme highlights and shadows due to the higher dynamic range and bit depth. To this end, we represent a linear image as a sequence of exposure brackets, each capturing a specific portion of the dynamic range, and propose a DiT-based flow-matching architecture for text-conditioned exposure bracket generation. We further demonstrate downstream applications including text-guided linear image editing and structure-conditioned generation via ControlNet.
### Title:
          Enabling Mixed criticality applications for the Versal AI-Engines
 - **Authors:** Vincent Sprave, Martin Wilhelm, Daniele Passaretti, Alberto Garcia-Ortiz, Thilo Pionteck
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adaptive Systems-on-Chips (SoCs) are increasingly being used in mixed criticality systems (MCSs), such as in autonomous driving, aviation and medical systems. In this context, AMD has proposed the Versal SoC, which has a heterogeneous architecture including, among other components, an Artificial Intelligence Engine (AIE), which is a 2D array of processors and memory tiles designed for AI and signal processing workloads. While this AIE offers significant potential for accelerating real-time data processing tasks, this has not yet been explored in the context of MCSs since individual tasks with different criticality levels cannot be dynamically assigned to tiles due to the static mapping of dataflow graphs and tasks. In this work, we propose a dynamic task dispatching infrastructure that enables task switching on the AIE at runtime. Based on this infrastructure, we present an MCS design that dynamically assigns tasks of different criticality to a pool of AIE tiles, depending on the criticality mode of the system. Our approach overcomes the limitations of static dataflow graph mappings and, for the first time, exploits the parallel processing capabilities of the AIE for MCSs. We also present a comprehensive timing analysis of the overhead introduced by the task dispatcher infrastructure, focusing on control logic, context switching and data copy operations. This shows that these operations have low variance and are negligible compared to the overall execution time, demonstrating that our infrastructure is suitable for MCSs. Finally, we evaluate the proposed infrastructure using an autonomous driving workload with tasks that have variable execution times and different criticality levels. In this case study, we maximized AIE utilization, reducing idle time by 65.5 %, while measuring an execution time overhead of less than 0.002 %, and doubling the throughput of low-criticality tasks.
### Title:
          Measure Twice, Click Once: Co-evolving Proposer and Visual Critic via Reinforcement Learning for GUI Grounding
 - **Authors:** Wenkai Wang, Xiyun Li, Hongcan Guo, Wenhao Yu, Tianqing Fang, Haitao Mi, Dong Yu, Shengyu Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Graphical User Interface (GUI) grounding requires mapping natural language instructions to precise pixel coordinates. However, due to visually homogeneous elements and dense layouts, models typically grasp semantic intent yet struggle with achieving precise localization. While scaling sampling attempts (Pass@k) reveals potential gains, static self-consistency strategies derived from geometric clustering often yield limited improvements, as the model's predictions tend to be spatially dispersed. In this paper, we propose replacing static consistency strategies with a learnable selection mechanism that selects the optimal target by critiquing its own proposals rendered on the screenshot. Given the significant disparity between the model's grounding and critiquing capabilities, we propose a co-evolving Propose-then-Critic framework. To jointly optimize these, we introduce a maturity-aware adaptive co-evolutionary reinforcement learning paradigm. This approach dynamically balances the training objectives of proposer and critic, where the diversity of the proposer's outputs enhances critic robustness, while the critic's maturing discrimination capability conversely unlocks the proposer's potential for extensive spatial exploration, fostering the mutual reinforcement and co-evolution of both capabilities, thereby ensuring generalizability to adapt to diverse and complex interface layouts. Extensive experiments over 6 benchmarks show that our method significantly enhances both grounding accuracy and critic reliability.
### Title:
          GeoMind: An Agentic Workflow for Lithology Classification with Reasoned Tool Invocation
 - **Authors:** Yitong Zhou, Mingyue Cheng, Jiahao Wang, Qingyang Mao, Qi Liu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Lithology classification in well logs is a fundamental geoscience data mining task that aims to infer rock types from multi dimensional geophysical sequences. Despite recent progress, existing approaches typically formulate the problem as a static, single-step discriminative mapping. This static paradigm limits evidence-based diagnostic reasoning against geological standards, often yielding predictions that are detached from geological reality due to a lack of domain priors. In this work, we propose GeoMind, a tool-augmented agentic framework that models lithology classification as a sequential reasoning process. GeoMind organizes its toolkit into perception, reasoning, and analysis modules, which respectively translate raw logs into semantic trends, infer lithology hypotheses from multi-source evidence, and verify predictions against stratigraphic constraints. A global planner adaptively coordinates these modules based on input characteristics, enabling geologically plausible and evidence-grounded decisions. To guarantee the logical consistency of GeoMind, we introduce a fine-grained process supervision strategy. Unlike standard methods that focus solely on final outcomes, our approach optimizes intermediate reasoning steps, ensuring the validity of decision trajectories and alignment to geological constraints. Experiments on four benchmark well-log datasets demonstrate that GeoMind consistently outperforms strong baselines in classification performance while providing transparent and traceable decision-making processes.
### Title:
          Positivity-Preserving and Entropy-Stable Oscillation-Eliminating DGSEM for the Compressible Euler Equations on Curvilinear Meshes with Adaptive Mesh Refinement
 - **Authors:** Jieling Yang, Guosheng Fu
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We extend the entropy-stable oscillation-eliminating discontinuous Galerkin spectral element method (ES-OEDG) on curvilinear meshes to adaptive mesh refinement (AMR) grids with nonconforming interfaces. The formulation targets two-dimensional curvilinear quadrilateral meshes under a 2:1 refinement constraint, allowing a single level of hanging nodes. Elementwise volume discretization and geometric mapping are retained, while oscillation elimination and interface coupling are adapted for nonconforming interfaces. A central contribution is the design and analysis of numerical fluxes for such interfaces. We construct an entropy-stable flux that ensures global conservation and a semi-discrete entropy inequality. However, for polynomial degree N >= 2, negative entries in nonconforming interpolation operators lead to loss of formal high-order consistency. To address this, we propose a mortar-based flux that preserves high-order accuracy by interpolating at the solution level and evaluating standard two-point fluxes on fine-side mortars, at the cost of losing provable entropy stability. We also extend the Zhang--Shu positivity-preserving framework to curvilinear AMR meshes. Under forward Euler time stepping and a suitable CFL condition, the scheme using either flux preserves positivity of cell-average density and pressure. Combined with the Zhang--Shu limiter, this yields a fully discrete scheme maintaining admissibility at all nodal points. We further incorporate shock-indicator-based AMR and a conservative, positivity-preserving data transfer procedure between successive meshes, resulting in a robust and efficient algorithm. Numerical experiments on Cartesian and curvilinear AMR grids confirm high-order accuracy and robustness.
### Title:
          WorldMark: A Unified Benchmark Suite for Interactive Video World Models
 - **Authors:** Xiaojie Xu, Zhengyuan Lin, Kang He, Yukang Feng, Xiaofeng Mao, Yuanyang Yin, Kaipeng Zhang, Yongtao Ge
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Interactive video generation models such as Genie, YUME, HY-World, and Matrix-Game are advancing rapidly, yet every model is evaluated on its own benchmark with private scenes and trajectories, making fair cross-model comparison impossible. Existing public benchmarks offer useful metrics such as trajectory error, aesthetic scores, and VLM-based judgments, but none supplies the standardized test conditions -- identical scenes, identical action sequences, and a unified control interface -- needed to make those metrics comparable across models with heterogeneous inputs. We introduce WorldMark, the first benchmark that provides such a common playing field for interactive Image-to-Video world models. WorldMark contributes: (1) a unified action-mapping layer that translates a shared WASD-style action vocabulary into each model's native control format, enabling apples-to-apples comparison across six major models on identical scenes and trajectories; (2) a hierarchical test suite of 500 evaluation cases covering first- and third-person viewpoints, photorealistic and stylized scenes, and three difficulty tiers from Easy to Hard spanning 20-60s; and (3) a modular evaluation toolkit for Visual Quality, Control Alignment, and World Consistency, designed so that researchers can reuse our standardized inputs while plugging in their own metrics as the field evolves. We will release all data, evaluation code, and model outputs to facilitate future research. Beyond offline metrics, we launch World Model Arena (this http URL), an online platform where anyone can pit leading world models against each other in side-by-side battles and watch the live leaderboard.
### Title:
          SLAM as a Stochastic Control Problem with Partial Information: Optimal Solutions and Rigorous Approximations
 - **Authors:** Ilir Gusija, Fady Alajaji, Serdar Yüksel
 - **Subjects:** Subjects:
Robotics (cs.RO); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Simultaneous localization and mapping (SLAM) is a foundational state estimation problem in robotics in which a robot accurately constructs a map of its environment while also localizing itself within this construction. We study the active SLAM problem through the lens of optimal stochastic control, thereby recasting it as a decision-making problem under partial information. After reviewing several commonly studied models, we present a general stochastic control formulation of active SLAM together with a rigorous treatment of motion, sensing, and map representation. We introduce a new exploration stage cost that encodes the geometry of the state when evaluating information-gathering actions. This formulation, constructed as a nonstandard partially observable Markov decision process (POMDP), is then analyzed to derive rigorously justified approximate solutions that are near-optimal. To enable this analysis, the associated regularity conditions are studied under general assumptions that apply to a wide range of robotics applications. For a particular case, we conduct an extensive numerical study in which standard learning algorithms are used to learn near-optimal policies.
### Title:
          TEMA: Anchor the Image, Follow the Text for Multi-Modification Composed Image Retrieval
 - **Authors:** Zixu Li, Yupeng Hu, Zhiheng Fu, Zhiwei Chen, Yongqi Li, Liqiang Nie
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Composed Image Retrieval (CIR) is an important image retrieval paradigm that enables users to retrieve a target image using a multimodal query that consists of a reference image and modification text. Although research on CIR has made significant progress, prevailing setups still rely simple modification texts that typically cover only a limited range of salient changes, which induces two limitations highly relevant to practical applications, namely Insufficient Entity Coverage and Clause-Entity Misalignment. In order to address these issues and bring CIR closer to real-world use, we construct two instruction-rich multi-modification datasets, M-FashionIQ and M-CIRR. In addition, we propose TEMA, the Text-oriented Entity Mapping Architecture, which is the first CIR framework designed for multi-modification while also accommodating simple modifications. Extensive experiments on four benchmark datasets demonstrate that TEMA's superiority in both original and multi-modification scenarios, while maintaining an optimal balance between retrieval accuracy and computational efficiency. Our codes and constructed multi-modification dataset (M-FashionIQ and M-CIRR) are available at this https URL.
### Title:
          Neuromorphic Computing Based on Parametrically-Driven Oscillators and Frequency Combs
 - **Authors:** Mahadev Sunil Kumar, Adarsh Ganesan
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE); Pattern Formation and Solitons (nlin.PS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Parametrically driven oscillators provide a natural platform for neuromorphic computation, where nonlinear mode coupling and intrinsic dynamics enable both memory and high-dimensional transformation. Here, we investigate a two-mode system exhibiting 2:1 parametric resonance and demonstrate its operation as a reservoir computer across distinct dynamical regimes, including sub-threshold, parametric resonance, and frequency-comb states. By encoding input signals into the drive amplitude and sampling the resulting temporal and spectral responses, we perform one step-ahead prediction of benchmark chaotic systems, including Mackey-Glass, Rossler, and Lorenz dynamics. We find that optimal computational performance is achieved within the parametric resonance regime, where nonlinear interactions are activated while temporal coherence is preserved. In contrast, although frequency-comb states introduce increased spectral dimensionality, their performance is not consistently good across their existence band and also degrades in the chaotic comb regime due to loss of phase coherence. Mapping prediction error over parameter space reveals a direct correspondence between computational capability and the underlying bifurcation structure, with low-error regions aligned with the parametric resonance boundary. We further show that the input modulation, the detuning from the frequency matching condition, damping ratio, and input data rate systematically control the accessible dynamical regimes and thereby the computational performance. These results establish parametric resonance as a robust operating regime for oscillator-based reservoir computing and provide design principles for tuning physical systems toward optimal neuromorphic functionality.
### Title:
          Nemobot Games: Crafting Strategic AI Gaming Agents for Interactive Learning with Large Language Models
 - **Authors:** Chee Wei Tan, Yuchen Wang, Shangxin Guo
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper introduces a new paradigm for AI game programming, leveraging large language models (LLMs) to extend and operationalize Claude Shannon's taxonomy of game-playing machines. Central to this paradigm is Nemobot, an interactive agentic engineering environment that enables users to create, customize, and deploy LLM-powered game agents while actively engaging with AI-driven strategies. The LLM-based chatbot, integrated within Nemobot, demonstrates its capabilities across four distinct classes of games. For dictionary-based games, it compresses state-action mappings into efficient, generalized models for rapid adaptability. In rigorously solvable games, it employs mathematical reasoning to compute optimal strategies and generates human-readable explanations for its decisions. For heuristic-based games, it synthesizes strategies by combining insights from classical minimax algorithms (see, e.g., shannon1950chess) with crowd-sourced data. Finally, in learning-based games, it utilizes reinforcement learning with human feedback and self-critique to iteratively refine strategies through trial-and-error and imitation learning. Nemobot amplifies this framework by offering a programmable environment where users can experiment with tool-augmented generation and fine-tuning of strategic game agents. From strategic games to role-playing games, Nemobot demonstrates how AI agents can achieve a form of self-programming by integrating crowdsourced learning and human creativity to iteratively refine their own logic. This represents a step toward the long-term goal of self-programming AI.
### Title:
          Equity Bias: An Ethical Framework for AI Design
 - **Authors:** Mary Lockwood
 - **Subjects:** Subjects:
Computers and Society (cs.CY); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Equity Bias is a philosophical and practical framework for building smarter, more equitable AI systems. Grounded in hermeneutic philosophy and epistemic injustice theory, it treats bias not as an error to eliminate but as a reflection of whose knowledge is encoded into systems. While traditional approaches aim to reduce or remove bias, Equity Bias instead makes bias transparent and contestable. In doing so, it broadens whose perspectives shape AI and provides a lens for understanding AI systems as interpretive agents. The framework introduces a three-phase AI Life Cycle methodology: 'Equity Archaeology' (mapping knowledge and assumptions), 'Co-Creating Meaning' (participatory design), and 'Ongoing Accountability' (continuous evaluation). Equity Bias guides developers, researchers, and policymakers towards AI that is ethically accountable and capable of addressing complex real-world challenges.
### Title:
          From Research Question to Scientific Workflow: Leveraging Agentic AI for Science Automation
 - **Authors:** Bartosz Balis, Michal Orzechowski, Piotr Kica, Michal Dygas, Michal Kuszewski
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scientific workflow systems automate execution -- scheduling, fault tolerance, resource management -- but not the semantic translation that precedes it. Scientists still manually convert research questions into workflow specifications, a task requiring both domain knowledge and infrastructure expertise. We propose an agentic architecture that closes this gap through three layers: an LLM interprets natural language into structured intents (semantic layer); validated generators produce reproducible workflow DAGs (deterministic layer); and domain experts author ``Skills'': markdown documents encoding vocabulary mappings, parameter constraints, and optimization strategies (knowledge layer). This decomposition confines LLM non-determinism to intent extraction: identical intents always yield identical workflows. We implement and evaluate the architecture on the 1000 Genomes population genetics workflow and Hyperflow WMS running on Kubernetes. In an ablation study on 150 queries, Skills raise full-match intent accuracy from 44% to 83%; skill-driven deferred workflow generation reduces data transfer by 92\%; and the end-to-end pipeline completes queries on Kubernetes with LLM overhead below 15 seconds and cost under $0.001 per query.
## Keyword: localization
### Title:
          StarLoc: Pinpointing Transmitting LEO Satellites from a Single Passive Array
 - **Authors:** Ishani Janveja, Jida Zhang, Emerson Sie, Deepak Vasisht
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper focuses on 3D localization of transmitting satellites in low Earth orbits (LEO). 3D localization of transmitters in low orbits is an important emerging problem for many applications such as spectrum management, orbit determination, and backup for GPS failures in orbit. We present StarLoc -- a system to geolocate transmitters in space using a combination of orbital modeling and a new interferometric 3D angle-of-arrival estimation technique. StarLoc's design relies on a unique insight -- the motion of satellites is governed by orbital dynamics and is therefore along a 2D manifold in a 3D space. This reduces the degrees of freedom in satellite motion and allows us to 3D-locate and track a satellite with just three antennas in a 2D plane. We evaluate the system using signal transmissions from 81 Starlink satellites. Our results show that StarLoc can estimate the 3D-angle of a satellite within 0.7 degrees and the orbital range within 5 km. Our dataset and implementation are available at: this https URL.
### Title:
          Reinforcing 3D Understanding in Point-VLMs via Geometric Reward Credit Assignment
 - **Authors:** Jingkun Chen, Ruoshi Xu, Mingqi Gao, Shengda Luo, Jungong Han
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Point-Vision-Language Models promise to empower embodied agents with executable spatial reasoning, yet they frequently succumb to geometric hallucination where predicted 3D structures contradict the observed 2D reality. We identify a key cause of this failure not as a representation bottleneck but as a structural misalignment in reinforcement learning, where sparse geometric tokens are drowned out by noisy and broadcasted sequence-level rewards. To resolve this causal dilution, we propose Geometric Reward Credit Assignment, a framework that disentangles holistic supervision into field-specific signals and routes them exclusively to their responsible token spans. This mechanism transforms vague feedback into precise gradient updates and effectively turns generic policy optimization into targeted structural alignment. Furthermore, we internalize physical constraints via a Reprojection-Consistency term which serves as a cross-modal verifier to penalize physically impossible geometries. Validated on a calibrated benchmark derived from ShapeNetCore, our approach bridges the reliability gap by boosting 3D KPA from 0.64 to 0.93, increasing 3D bounding box intersection over union to 0.686, and raising reprojection consistency scores to 0.852. Crucially, these gains are achieved while maintaining robust 2D localization performance, marking a meaningful step from plausible textual outputs toward physically verifiable spatial predictions.
### Title:
          Toward Efficient Membership Inference Attacks against Federated Large Language Models: A Projection Residual Approach
 - **Authors:** Guilin Deng, Silong Chen, Yuchuan Luo, Yi Liu, Songlei Wang, Zhiping Cai, Lin Liu, Xiaohua Jia, Shaojing Fu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Federated Large Language Models (FedLLMs) enable multiple parties to collaboratively fine-tune LLMs without sharing raw data, addressing challenges of limited resources and privacy concerns. Despite data localization, shared gradients can still expose sensitive information through membership inference attacks (MIAs). However, FedLLMs' unique properties, i.e. massive parameter scales, rapid convergence, and sparse, non-orthogonal gradients, render existing MIAs ineffective. To address this gap, we propose ProjRes, the first projection residuals-based passive MIA tailored for FedLLMs. ProjRes leverages hidden embedding vectors as sample representations and analyzes their projection residuals on the gradient subspace to uncover the intrinsic link between gradients and inputs. It requires no shadow models, auxiliary classifiers, or historical updates, ensuring efficiency and robustness. Experiments on four benchmarks and four LLMs show that ProjRes achieves near 100% accuracy, outperforming prior methods by up to 75.75%, and remains effective even under strong differential privacy defenses. Our findings reveal a previously overlooked privacy vulnerability in FedLLMs and call for a re-examination of their security assumptions. Our code and data are available at $\href{this https URL}{link}$.
### Title:
          Measure Twice, Click Once: Co-evolving Proposer and Visual Critic via Reinforcement Learning for GUI Grounding
 - **Authors:** Wenkai Wang, Xiyun Li, Hongcan Guo, Wenhao Yu, Tianqing Fang, Haitao Mi, Dong Yu, Shengyu Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Graphical User Interface (GUI) grounding requires mapping natural language instructions to precise pixel coordinates. However, due to visually homogeneous elements and dense layouts, models typically grasp semantic intent yet struggle with achieving precise localization. While scaling sampling attempts (Pass@k) reveals potential gains, static self-consistency strategies derived from geometric clustering often yield limited improvements, as the model's predictions tend to be spatially dispersed. In this paper, we propose replacing static consistency strategies with a learnable selection mechanism that selects the optimal target by critiquing its own proposals rendered on the screenshot. Given the significant disparity between the model's grounding and critiquing capabilities, we propose a co-evolving Propose-then-Critic framework. To jointly optimize these, we introduce a maturity-aware adaptive co-evolutionary reinforcement learning paradigm. This approach dynamically balances the training objectives of proposer and critic, where the diversity of the proposer's outputs enhances critic robustness, while the critic's maturing discrimination capability conversely unlocks the proposer's potential for extensive spatial exploration, fostering the mutual reinforcement and co-evolution of both capabilities, thereby ensuring generalizability to adapt to diverse and complex interface layouts. Extensive experiments over 6 benchmarks show that our method significantly enhances both grounding accuracy and critic reliability.
### Title:
          Ufil: A Unified Framework for Infrastructure-based Localization
 - **Authors:** Simon Schäfer, Lucas Hegerath, Marius Molz, Massimo Marcon, Bassam Alrifaee
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Infrastructure-based localization enhances road safety and traffic management by providing state estimates of road users. Development is hindered by fragmented, application-specific stacks that tightly couple perception, tracking, and middleware. We introduce Ufil, a Unified Framework for Infrastructure-Based Localization with a standardized object model and reusable multi-object tracking components. Ufil offers interfaces and reference implementations for prediction, detection, association, state update, and track management, allowing researchers to improve components without reimplementing the pipeline. Ufil is open-source C++/ROS 2 software with documentation and executable examples. We demonstrate Ufil by integrating three heterogeneous data sources into a single localization pipeline combining (i) vehicle onboard units broadcasting ETSI ITS-G5 Cooperative Awareness Messages, (ii) a lidar-based roadside sensor node, and (iii) an in-road sensitive surface layer. The pipeline runs unchanged in the CARLA simulator and a small-scale CAV testbed, demonstrating Ufil's scale-independent execution model. In a three-lane highway scenario with 423 and 355 vehicles in simulation and testbed, respectively, the fused system achieves lane-level lateral accuracy with mean lateral position RMSEs of 0.31 m in CARLA and 0.29 m in the CPM Lab, and mean absolute orientation errors around 2.2°. Median end-to-end latencies from sensing to fused output remain below 100 ms across all modalities in both environments.
### Title:
          VFM$^{4}$SDG: Unveiling the Power of VFMs for Single-Domain Generalized Object Detection
 - **Authors:** Yupeng Zhang, Ruize Han, Ningnan Guo, Wei Feng, Song Wang, Liang Wan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In real-world scenarios, continual changes in weather, illumination, and imaging conditions cause significant domain shifts, leading detectors trained on a single source domain to degrade severely in unseen environments. Existing single-domain generalized object detection (SDGOD) methods mainly rely on data augmentation or domain-invariant representation learning, but pay limited attention to detector mechanisms, leaving clear limitations under complex domain shifts. Through analytical experiments, we find that performance degradation is dominated by increasing missed detections, which fundamentally arises from reduced cross-domain stability of the detector: object-background and inter-instance relations become less stable in the encoding stage, while semantic-spatial alignment of query representations also becomes harder to maintain in the decoding stage. To this end, we propose VFM$^{4}$SDG, a dual-prior learning framework for SDGOD, which introduces a frozen vision foundation model (VFM) as a transferable cross-domain stability prior into detector representation learning and query modeling. In the encoding stage, we propose Cross-domain Stable Relational Prior Distillation to enhance the robustness of object-background and inter-instance relational modeling. In the decoding stage, we propose Semantic-Contextual Prior-based Query Enhancement, which injects category-level semantic prototypes and global visual context into queries to improve their semantic recognition and spatial localization stability in unseen domains. Extensive experiments show that the proposed method consistently outperforms existing SOTA methods on standard SDGOD benchmarks and two mainstream DETR-based detectors, demonstrating its effectiveness, robustness, and generality.
### Title:
          ADMM-Based Distributed Kalman-like Observer with Applications to Cooperative Localization
 - **Authors:** Nicola De Carli, Nicola Bastianello, Dimos V. Dimarogonas
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper addresses distributed state estimation for multi-agent systems with local and relative measurements, motivated by cooperative localization problems in which the global state dimension scales with the size of the network. We consider a Kalman-like observer in information form and introduce a sparsity-preserving prediction step based on an exponential forgetting factor, thereby avoiding the dense Riccati recursion of the standard information filter. The correction step is recast as a strongly convex quadratic program with structure induced by the sensing graph, which enables a distributed solution based on the alternating direction method of multipliers (ADMM). In the resulting scheme, each agent updates local copies of its own correction variable and those of its neighbors using only local communication, thus avoiding centralized matrix inversion and consensus over full global-state quantities. A two-time-scale stability analysis is developed for the interconnected observer: the reduced estimation-error dynamics are shown to be uniformly exponentially stable, the ADMM dynamics define an exponentially stable fast subsystem, and these properties are combined to establish uniform exponential stability of the overall distributed observer. Numerical simulations in a multi-agent cooperative localization scenario illustrate the performance of the proposed distributed observer.
### Title:
          SLAM as a Stochastic Control Problem with Partial Information: Optimal Solutions and Rigorous Approximations
 - **Authors:** Ilir Gusija, Fady Alajaji, Serdar Yüksel
 - **Subjects:** Subjects:
Robotics (cs.RO); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Simultaneous localization and mapping (SLAM) is a foundational state estimation problem in robotics in which a robot accurately constructs a map of its environment while also localizing itself within this construction. We study the active SLAM problem through the lens of optimal stochastic control, thereby recasting it as a decision-making problem under partial information. After reviewing several commonly studied models, we present a general stochastic control formulation of active SLAM together with a rigorous treatment of motion, sensing, and map representation. We introduce a new exploration stage cost that encodes the geometry of the state when evaluating information-gathering actions. This formulation, constructed as a nonstandard partially observable Markov decision process (POMDP), is then analyzed to derive rigorously justified approximate solutions that are near-optimal. To enable this analysis, the associated regularity conditions are studied under general assumptions that apply to a wide range of robotics applications. For a particular case, we conduct an extensive numerical study in which standard learning algorithms are used to learn near-optimal policies.
## Keyword: transformer
### Title:
          Absorber LLM: Harnessing Causal Synchronization for Test-Time Training
 - **Authors:** Zhixin Zhang, Shabo Zhang, Chengcan Wu, Zeming Wei, Meng Sun
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Software Engineering (cs.SE); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers suffer from a high computational cost that grows with sequence length for self-attention, making inference in long streams prohibited by memory consumption. Constant-memory alternatives such as RNNs and SSMs compress history into states with fixed size and thus lose long-tail dependencies, while methods that memorize contexts into parameters, such as Test-Time Training (TTT), are prone to overfitting token-level projection and fail to preserve the causal effect of context in pretrained LLMs. We propose Absorber LLM, which formulates long-context retention as a self-supervised causal synchronization: after absorbing historical contexts into parameters, a contextless model should match the original model with full context on future generations. We optimize this objective by synchronizing internal behaviors of the updated model with the original one, ensuring context absorption and generalization. Experiments on long-context and streaming benchmarks show that Absorber LLM reduces inference memory and improves accuracy over prior parameter-as-memory baselines.
### Title:
          AttentionBender: Manipulating Cross-Attention in Video Diffusion Transformers as a Creative Probe
 - **Authors:** Adam Cole, Mick Grierson
 - **Subjects:** Subjects:
Multimedia (cs.MM); Computer Vision and Pattern Recognition (cs.CV); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present AttentionBender, a tool that manipulates cross-attention in Video Diffusion Transformers to help artists probe the internal mechanics of black-box video generation. While generative outputs are increasingly realistic, prompt-only control limits artists' ability to build intuition for the model's material process or to work beyond its default tendencies. Using an autobiographical research-through-design approach, we built on Network Bending to design AttentionBender, which applies 2D transforms (rotation, scaling, translation, etc.) to cross-attention maps to modulate generation. We assess AttentionBender by visualizing 4,500+ video generations across prompts, operations, and layer targets. Our results suggest that cross-attention is highly entangled: targeted manipulations often resist clean, localized control, producing distributed distortions and glitch aesthetics over linear edits. AttentionBender contributes a tool that functions both as an Explainable AI style probe of transformer attention mechanisms, and as a creative technique for producing novel aesthetics beyond the model's learned representational space.
### Title:
          StyleVAR: Controllable Image Style Transfer via Visual Autoregressive Modeling
 - **Authors:** Liqi Jing, Dingming Zhang, Peinian Li, Lichen Zhu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We build on the Visual Autoregressive Modeling (VAR) framework and formulate style transfer as conditional discrete sequence modeling in a learned latent space. Images are decomposed into multi-scale representations and tokenized into discrete codes by a VQ-VAE; a transformer then autoregressively models the distribution of target tokens conditioned on style and content tokens. To inject style and content information, we introduce a blended cross-attention mechanism in which the evolving target representation attends to its own history, while style and content features act as queries that decide which aspects of this history to emphasize. A scale-dependent blending coefficient controls the relative influence of style and content at each stage, encouraging the synthesized representation to align with both the content structure and the style texture without breaking the autoregressive continuity of VAR. We train StyleVAR in two stages from a pretrained VAR checkpoint: supervised fine-tuning on a large triplet dataset of content--style--target images, followed by reinforcement fine-tuning with Group Relative Policy Optimization (GRPO) against a DreamSim-based perceptual reward, with per-action normalization weighting to rebalance credit across VAR's multi-scale hierarchy. Across three benchmarks spanning in-, near-, and out-of-distribution regimes, StyleVAR consistently outperforms an AdaIN baseline on Style Loss, Content Loss, LPIPS, SSIM, DreamSim, and CLIP similarity, and the GRPO stage yields further gains over the SFT checkpoint, most notably on the reward-aligned perceptual metrics. Qualitatively, the method transfers texture while maintaining semantic structure, especially for landscapes and architectural scenes, while a generalization gap on internet images and difficulty with human faces highlight the need for better content diversity and stronger structural priors.
### Title:
          A Hybridizable Neural Time Integrator for Stable Autoregressive Forecasting
 - **Authors:** Brooks Kinch, Xiaozhe Hu, Yilong Huang, Martine Dyring Hansen, Sunniva Meltzer, Nathaniel Donald Hamlin, David Sirajuddin, Eric C. Cyr, Nathaniel Trask
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 For autoregressive modeling of chaotic dynamical systems over long time horizons, the stability of both training and inference is a major challenge in building scientific foundation models. We present a hybrid technique in which an autoregressive transformer is embedded within a novel shooting-based mixed finite element scheme, exposing topological structure that enables provable stability. For forward problems, we prove preservation of discrete energies, while for training we prove uniform bounds on gradients, provably avoiding the exploding gradient problem. Combined with a vision transformer, this yields latent tokens admitting structure-preserving dynamics. We outperform modern foundation models with a $65\times$ reduction in model parameters and long-horizon forecasting of chaotic systems. A "mini-foundation" model of a fusion component shows that 12 simulations suffice to train a real-time surrogate, achieving a $9{,}000\times$ speedup over particle-in-cell simulation.
### Title:
          Leveraging Multimodal LLMs for Built Environment and Housing Attribute Assessment from Street-View Imagery
 - **Authors:** Siyuan Yao, Siavash Ghorbany, Kuangshi Ai, Arnav Cherukuthota, Meghan Forstchen, Alexis Korotasz, Matthew Sisk, Ming Hu, Chaoli Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a novel framework for automatically evaluating building conditions nationwide in the United States by leveraging large language models (LLMs) and Google Street View (GSV) imagery. By fine-tuning Gemma 3 27B on a modest human-labeled dataset, our approach achieves strong alignment with human mean opinion scores (MOS), outperforming even individual raters on SRCC and PLCC relative to the MOS benchmark. To enhance efficiency, we apply knowledge distillation, transferring the capabilities of Gemma 3 27B to a smaller Gemma 3 4B model that achieves comparable performance with a 3x speedup. Further, we distill the knowledge into a CNN-based model (EfficientNetV2-M) and a transformer (SwinV2-B), delivering close performance while achieving a 30x speed gain. Furthermore, we investigate LLMs' capabilities for assessing an extensive list of built environment and housing attributes through a human-AI alignment study and develop a visualization dashboard that integrates LLM assessment outcomes for downstream analysis by homeowners. Our framework offers a flexible and efficient solution for large-scale building condition assessment, enabling high accuracy with minimal human labeling effort.
### Title:
          The Recurrent Transformer: Greater Effective Depth and Efficient Decoding
 - **Authors:** Costin-Andrei Oncescu, Depen Morwani, Samy Jelassi, Alexandru Meterez, Mujin Kwun, Sham Kakade
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers process tokens in parallel but are temporally shallow: at position $t$, each layer attends to key-value pairs computed based on the previous layer, yielding a depth capped by the number of layers. Recurrent models offer unbounded temporal depth but suffer from optimization instability and historically underutilize modern accelerators. We introduce the Recurrent Transformer, a simple architectural change where each layer attends to key-value pairs computed off its own activations, yielding layerwise recurrent memory while preserving standard autoregressive decoding cost. We show that the architecture can emulate both (i) a conventional Transformer and (ii) token-to-token recurrent updates under mild assumptions, while avoiding optimization instability. Naively, prefill/training appears bandwidth-bound with effective arithmetic intensity near $1$ because keys and values are revealed sequentially; we give an exact tiling-based algorithm that preserves the mathematical computation while reducing HBM traffic from $\Theta(N^2)$ to $\Theta(N\log N)$, increasing effective arithmetic intensity to $\Theta(N/\log N)$ for sequence length $N$. On 150M and 300M parameter C4 pretraining, Recurrent Transformers improve cross-entropy over a parameter-matched Transformer baseline and achieve the improvement with fewer layers (fixed parameters), suggesting that recurrence can trade depth for width, thus reducing KV cache memory footprint and inference latency.
### Title:
          Hyperloop Transformers
 - **Authors:** Abbas Zeitoun, Lucas Torroba-Hennigen, Yoon Kim
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLM architecture research generally aims to maximize model quality subject to fixed compute/latency budgets. However, many applications of interest such as edge and on-device deployment are further constrained by the model's memory footprint, thus motivating parameter-efficient architectures for language modeling. This paper describes a simple architecture that improves the parameter-efficiency of LLMs. Our architecture makes use of looped Transformers as a core primitive, which reuse Transformer layers across depth and are thus more parameter-efficient than ordinary (depth-matched) Transformers. We organize the looped Transformer into three blocks--begin, middle, and end blocks--where each block itself consists of multiple Transformer layers, and only the middle block is applied recurrently across depth. We augment the looped middle block with hyper-connections (Xie et al., 2026), which expand the residual stream into matrix-valued residual streams. Hyper-connections are applied only after each loop, and therefore add minimal new parameters and compute cost. Across various model scales, we find that our Hyper-Connected Looped Transformer (Hyperloop Transformer) is able to outperform depth-matched Transformer and mHC Transformer baselines despite using approximately 50% fewer parameters. The outperformance persists through post-training weight quantization, thus positioning Hyperloop Transformers as an attractive architecture for memory-efficient language modeling.
### Title:
          Listen and Chant Before You Read: The Ladder of Beauty in LM Pre-Training
 - **Authors:** Yoshinori Nomura
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We show that pre-training a Transformer on music before language significantly accelerates language acquisition. Using piano performances (MAESTRO dataset), a developmental pipeline -- music $\to$ poetry $\to$ prose -- yields a $17.5\%$ perplexity improvement over random initialization ($p < 0.001$, 5 seeds), with music and poetry improving orthogonal model components (internal computation and embeddings, respectively). Convergence tests confirm that this is not a transient head start: at $d\!=\!64$, multi-seed validation (5 seeds) shows a persistent 5.5\% gap at plateau ($p = 0.017$), with the pipeline converging faster and to a lower loss in every run. Real music matches the transfer ceiling of synthetic patterns with one-third the data, and scaling experiments reveal that optimal pre-training data volume shifts with model capacity ($-3\% \to +3\% \to +6\%$ advantage of larger datasets from $d\!=\!16$ to $d\!=\!64$). Across the scales we study ($d\!\in\!\{16,32,64\}$, up to ${\sim}400$K parameters), these results suggest a capacity-dependent data curation principle and indicate that structured human creative outputs can provide an efficient pre-training substrate for small language models; stronger conclusions at modern pre-training scale will require substantially larger experiments.
### Title:
          AttDiff-GAN: A Hybrid Diffusion-GAN Framework for Facial Attribute Editing
 - **Authors:** Wenmin Huang, Weiqi Luo, Xiaochun Cao, Jiwu Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Facial attribute editing aims to modify target attributes while preserving attribute-irrelevant content and overall image fidelity. Existing GAN-based methods provide favorable controllability, but often suffer from weak alignment between style codes and attribute semantics. Diffusion-based methods can synthesize highly realistic images; however, their editing precision is limited by the entanglement of semantic directions among different attributes. In this paper, we propose AttDiff-GAN, a hybrid framework that combines GAN-based attribute manipulation with diffusion-based image generation. A key challenge in such integration lies in the inconsistency between one-step adversarial learning and multi-step diffusion denoising, which makes effective optimization difficult. To address this issue, we decouple attribute editing from image synthesis by introducing a feature-level adversarial learning scheme to learn explicit attribute manipulation, and then using the manipulated features to guide the diffusion process for image generation, while also removing the reliance on semantic direction-based editing. Moreover, we enhance style-attribute alignment by introducing PriorMapper, which incorporates facial priors into style generation, and RefineExtractor, which captures global semantic relationships through a Transformer for more precise style extraction. Experimental results on CelebA-HQ show that the proposed method achieves more accurate facial attribute editing and better preservation of non-target attributes than state-of-the-art methods in both qualitative and quantitative evaluations.
### Title:
          GraphLeap: Decoupling Graph Construction and Convolution for Vision GNN Acceleration on FPGA
 - **Authors:** Anvitha Ramachandran, Dhruv Parikh, Viktor Prasanna
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Graph Neural Networks (ViGs) represent an image as a graph of patch tokens, enabling adaptive, feature-driven neighborhoods. Unlike CNNs with fixed grid biases or Vision Transformers with global token interactions, ViGs rely on dynamic graph convolution: at each layer, a feature-dependent graph is built via k-nearest-neighbor (kNN) search on current patch features, followed by message passing. This per-layer graph construction is the main bottleneck, consuming 50--95\% of graph convolution time on CPUs and GPUs, scaling as $O(N^2)$ with the number of patches $N$, and creating a sequential dependency between graph construction and feature updates. We introduce GraphLeap, a simple reformulation that removes this dependency by decoupling graph construction from feature update across layers. GraphLeap performs the feature update at layer $\ell$ using a graph built from the previous layer's features, while simultaneously using the current layer's features to construct the graph for layer $\ell+1$. This one-layer-lookahead graph construction enables concurrent graph construction and message passing. Although using prior-layer features can introduce minor accuracy degradation, lightweight fine-tuning for a few epochs is sufficient to recover the original accuracy. Building on GraphLeap, we present the first end-to-end FPGA accelerator for Vision GNNs. Our streaming, layer-pipelined design overlaps a kNN graph construction engine with a feature update engine, exploits node- and channel-level parallelism, and enables efficient on-chip dataflow without explicit edge-feature materialization. Evaluated on isotropic and pyramidal ViG models on an Alveo U280 FPGA, GraphLeap achieves up to $95.7\times$ speedup over CPU and $8.5\times$ speedup over GPU baselines, demonstrating the feasibility of real-time Vision GNN inference.
### Title:
          an interpretable vision transformer framework for automated brain tumor classification
 - **Authors:** Chinedu Emmanuel Mbonu, Tochukwu Sunday Belonwu, Okwuchukwu Ejike Chukwuogo, Kenechukwu Sylvanus Anigbogu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Brain tumors represent one of the most critical neurological conditions, where early and accurate diagnosis is directly correlated with patient survival rates. Manual interpretation of Magnetic Resonance Imaging (MRI) scans is time-intensive, subject to inter-observer variability, and demands significant specialist expertise. This paper proposes a deep learning framework for automated four-class brain tumor classification distinguishing glioma, meningioma, pituitary tumor, and healthy brain tissue from a dataset of 7,023 MRI scans. The proposed system employs a Vision Transformer (ViT-B/16) pretrained on ImageNet-21k as the backbone, augmented with a clinically motivated preprocessing and training pipeline. Contrast Limited Adaptive Histogram Equalization (CLAHE) is applied to enhance local contrast and accentuate tumor boundaries invisible to standard normalization. A two-stage fine-tuning strategy is adopted: the classification head is warmed up with the backbone frozen, followed by full fine-tuning with discriminative learning rates. MixUp and CutMix augmentation is applied per batch to improve generalization. Exponential Moving Average (EMA) of weights and Test-Time Augmentation (TTA) further stabilize and boost performance. Attention Rollout visualization provides clinically interpretable heatmaps of the brain regions driving each prediction. The proposed model achieves a test accuracy of 99.29%, macro F1-score of 99.25%, and perfect recall on both healthy and meningioma classes, outperforming all CNN-based baselines
### Title:
          Sub-Token Routing in LoRA for Adaptation and Query-Aware KV Compression
 - **Authors:** Wei Jiang, Wei Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sub-token routing offers a finer control axis for transformer efficiency than the coarse units used in most prior work, such as tokens, pages, heads, or layers. In this paper, we study routing within a token representation itself in LoRA-adapted transformers. The motivation is that a relevant token need not be internally uniform: under a retention budget, preserved value groups are distributed unevenly both across tokens and within tokens, which suggests that KV compression need not be an all-or-nothing decision at token level. We study this fine-grained routing mechanism in two settings. For compression-aware language modeling, we introduce a query-independent design that combines routed subspace LoRA with value-group routing on the KV path. For downstream-task-preserving KV compression, we introduce a query-aware design in which a predictor-based selector allocates a global retention budget over context-token/value-group pairs using query-conditioned relevance. Experiments show that the query-independent design improves the quality-compression tradeoff for language modeling, while the query-aware design preserves downstream behavior under reduced KV budgets. We further examine the relation between token-level and sub-token-level query-aware routing, and show that they form complementary compression axes: token-level methods determine which tokens survive globally, while sub-token routing determines how the surviving tokens are compressed internally.
### Title:
          UHR-DETR: Efficient End-to-End Small Object Detection for Ultra-High-Resolution Remote Sensing Imagery
 - **Authors:** Jingfang Li, Haoran Zhu, Wen Yang, Jinrui Zhang, Fang Xu, Haijian Zhang, Gui-Song Xia
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ultra-High-Resolution (UHR) imagery has become essential for modern remote sensing, offering unprecedented spatial coverage. However, detecting small objects in such vast scenes presents a critical dilemma: retaining the original resolution for small objects causes prohibitive memory bottlenecks. Conversely, conventional compromises like image downsampling or patch cropping either erase small objects or destroy context. To break this dilemma, we propose UHR-DETR, an efficient end-to-end transformer-based detector designed for UHR imagery. First, we introduce a Coverage-Maximizing Sparse Encoder that dynamically allocates finite computational resources to informative high-resolution regions, ensuring maximum object coverage with minimal spatial redundancy. Second, we design a Global-Local Decoupled Decoder. By integrating macroscopic scene awareness with microscopic object details, this module resolves semantic ambiguities and prevents scene fragmentation. Extensive experiments on the UHR imagery datasets (e.g., STAR and SODA-A) demonstrate the superiority of UHR-DETR under strict hardware constraints (e.g., a single 24GB RTX 3090). It achieves a 2.8\% mAP improvement while delivering a 10$\times$ inference speedup compared to standard sliding-window baselines on the STAR dataset. Our codes and models will be available at this https URL.
### Title:
          VARestorer: One-Step VAR Distillation for Real-World Image Super-Resolution
 - **Authors:** Yixuan Zhu, Shilin Ma, Haolin Wang, Ao Li, Yanzhe Jing, Yansong Tang, Lei Chen, Jiwen Lu, Jie Zhou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advancements in visual autoregressive models (VAR) have demonstrated their effectiveness in image generation, highlighting their potential for real-world image super-resolution (Real-ISR). However, adapting VAR for ISR presents critical challenges. The next-scale prediction mechanism, constrained by causal attention, fails to fully exploit global low-quality (LQ) context, resulting in blurry and inconsistent high-quality (HQ) outputs. Additionally, error accumulation in the iterative prediction severely degrades coherence in ISR task. To address these issues, we propose VARestorer, a simple yet effective distillation framework that transforms a pre-trained text-to-image VAR model into a one-step ISR model. By leveraging distribution matching, our method eliminates the need for iterative refinement, significantly reducing error propagation and inference time. Furthermore, we introduce pyramid image conditioning with cross-scale attention, which enables bidirectional scale-wise interactions and fully utilizes the input image information while adapting to the autoregressive mechanism. This prevents later LQ tokens from being overlooked in the transformer. By fine-tuning only 1.2\% of the model parameters through parameter-efficient adapters, our method maintains the expressive power of the original VAR model while significantly enhancing efficiency. Extensive experiments show that VARestorer achieves state-of-the-art performance with 72.32 MUSIQ and 0.7669 CLIPIQA on DIV2K dataset, while accelerating inference by 10 times compared to conventional VAR inference.
### Title:
          Reasoning Primitives in Hybrid and Non-Hybrid LLMs
 - **Authors:** Shivam Rawat, Lucie Flek, Florian Mai, Nicholas Kluge Corrêa
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reasoning in large language models is often treated as a monolithic capability, but its observed gains may arise from more basic operations. We study reasoning through two such primitives, recall and state-tracking, and ask whether hybrid architectures that combine attention-based retrieval with recurrent state updates are better suited than attention-only models for tasks that jointly require both. Using matched Olmo3 transformer and hybrid models in instruction-tuned and reasoning-augmented variants, we evaluate these models on a set of controlled tasks involving a mixture of state-tracking and recall primitives, state-based recall. Across tasks, we notice that reasoning augmentation provides the largest overall improvement, substantially extending the range of difficulty over which models remain effective. We also notice that in certain tasks, the hybrid reasoning model remains substantially more robust as sequential dependence increases. In contrast, the transformer reasoning model degrades sharply in performance as task difficulty increases beyond a given threshold. These results suggest that reasoning tokens and architectural inductive biases contribute at different levels of the computational process: explicit reasoning can expand a model's effective operating range, but its benefit depends on how well the underlying architecture supports persistent state propagation. Given the small size of our case study, which involves a limited set of models and tasks, we present these findings as suggestive rather than conclusive and leave broader validation across model families, scales, and task variations to future work.
### Title:
          How English Print Media Frames Human-Elephant Conflicts in India
 - **Authors:** Bonala Sai Punith, Salveru Jayati, Garima Shakya, Shubham Kumar Nigam
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Human-elephant conflict (HEC) is rising across India as habitat loss and expanding human settlements force elephants into closer contact with people. While the ecological drivers of conflict are well-studied, how the news media portrays them remains largely unexplored. This work presents the first large-scale computational analysis of media framing of HEC in India, examining 1,968 full-length news articles consisting of 28,986 sentences, from a major English-language outlet published between January 2022 and September 2025. Using a multi-model sentiment framework that combines long-context transformers, large language models, and a domain-specific Negative Elephant Portrayal Lexicon, we quantify sentiment, extract rationale sentences, and identify linguistic patterns that contribute to negative portrayals of elephants. Our findings reveal a dominance of fear-inducing and aggression-related language. Since the media framing can shape public attitudes toward wildlife and conservation policy, such narratives risk reinforcing public hostility and undermining coexistence efforts. By providing a transparent, scalable methodology and releasing all resources through an anonymized repository, this study highlights how Web-scale text analysis can support responsible wildlife reporting and promote socially beneficial media practices.
### Title:
          OmniFit: Multi-modal 3D Body Fitting via Scale-agnostic Dense Landmark Prediction
 - **Authors:** Zeyu Cai, Yuliang Xiu, Renke Wang, Zhijing Shao, Xiaoben Li, Siyuan Yu, Chao Xu, Yang Liu, Baigui Sun, Jian Yang, Zhenyu Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fitting an underlying body model to 3D clothed human assets has been extensively studied, yet most approaches focus on either single-modal inputs such as point clouds or multi-view images alone, often requiring a known metric scale. This constraint is frequently impractical, especially for AI-generated assets where scale distortion is common. We propose OmniFit, a method that can seamlessly handle diverse multi-modal inputs, including full scans, partial depth observations, and image captures, while remaining scale-agnostic for both real and synthetic assets. Our key innovation is a simple yet effective conditional transformer decoder that directly maps surface points to dense body landmarks, which are then used for SMPL-X parameter fitting. In addition, an optional plug-and-play image adapter incorporates visual cues to compensate for missing geometric information. We further introduce a dedicated scale predictor that rescales subjects to canonical body proportions. OmniFit substantially outperforms state-of-the-art methods by 57.1 to 80.9 percent across daily and loose clothing scenarios. To the best of our knowledge, it is the first body fitting method to surpass multi-view optimization baselines and the first to achieve millimeter-level accuracy on the CAPE and 4D-DRESS benchmarks.
### Title:
          Sculpt4D: Generating 4D Shapes via Sparse-Attention Diffusion Transformers
 - **Authors:** Minghao Yin, Wenbo Hu, Jiale Xu, Ying Shan, Kai Han
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent breakthroughs in 3D generative modeling have yielded remarkable progress in static shape synthesis, yet high-fidelity dynamic 4D generation remains elusive, hindered by temporal artifacts and prohibitive computational demand. We present Sculpt4D, a native 4D generative framework that seamlessly integrates efficient temporal modeling into a pretrained 3D Diffusion Transformer (Hunyuan3D 2.1), thereby mitigating the scarcity of 4D training data. At its core lies a Block Sparse Attention mechanism that preserves object identity by anchoring to the initial frame while capturing rich motion dynamics via a time-decaying sparse mask. This design faithfully models complex spatiotemporal dependencies with high fidelity, while sidestepping the quadratic overhead of full attention and reducing network total computation by 56%. Consequently, Sculpt4D establishes a new state-of-the-art in temporally coherent 4D synthesis and charts a path toward efficient and scalable 4D generation.
### Title:
          A-THENA: Early Intrusion Detection for IoT with Time-Aware Hybrid Encoding and Network-Specific Augmentation
 - **Authors:** Ioannis Panopoulos, Maria Lamprini A. Bartsioka, Sokratis Nikolaidis, Stylianos I. Venieris, Dimitra I. Kaklamani, Iakovos S. Venieris
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The proliferation of Internet of Things (IoT) devices has significantly expanded attack surfaces, making IoT ecosystems particularly susceptible to sophisticated cyber threats. To address this challenge, this work introduces A-THENA, a lightweight early intrusion detection system (EIDS) that significantly extends preliminary findings on time-aware encodings. A-THENA employs an advanced Transformer-based architecture augmented with a generalized Time-Aware Hybrid Encoding (THE), integrating packet timestamps to effectively capture temporal dynamics essential for accurate and early threat detection. The proposed system further employs a Network-Specific Augmentation (NA) pipeline, which enhances model robustness and generalization. We evaluate A-THENA on three benchmark IoT intrusion detection datasets-CICIoT23-WEB, MQTT-IoT-IDS2020, and IoTID20-where it consistently achieves strong performance. Averaged across all three datasets, it improves accuracy by 6.88 percentage points over the best-performing traditional positional encoding, 3.69 points over the strongest feature-based model, 6.17 points over the leading time-aware alternatives, and 5.11 points over related models, while achieving near-zero false alarms and false negatives. To assess real-world feasibility, we deploy A-THENA on the Raspberry Pi Zero 2 W, demonstrating its ability to perform real-time intrusion detection with minimal latency and memory usage. These results establish A-THENA as an agile, practical, and highly effective solution for securing IoT networks.
### Title:
          Promoting Simple Agents: Ensemble Methods for Event-Log Prediction
 - **Authors:** Benedikt Bollig, Matthias Függer, Thomas Nowak, Paul Zeinaty
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Distributed, Parallel, and Cluster Computing (cs.DC); Formal Languages and Automata Theory (cs.FL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We compare lightweight automata-based models (n-grams) with neural architectures (LSTM, Transformer) for next-activity prediction in streaming event logs. Experiments on synthetic patterns and five real-world process mining datasets show that n-grams with appropriate context windows achieve comparable accuracy to neural models while requiring substantially fewer resources. Unlike windowed neural architectures, which show unstable performance patterns, n-grams provide stable and consistent accuracy. While we demonstrate that classical ensemble methods like voting improve n-gram performance, they require running many agents in parallel during inference, increasing memory consumption and latency. We propose an ensemble method, the promotion algorithm, that dynamically selects between two active models during inference, reducing overhead compared to classical voting schemes. On real-world datasets, these ensembles match or exceed the accuracy of non-windowed neural models with lower computational cost.
### Title:
          To See the Unseen: on the Generalization Ability of Transformers in Symbolic Reasoning
 - **Authors:** Nevena Lazić, Liam Fowl, András György, Csaba Szepesvári
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We investigate the ability of decoder-only transformer models to perform abstract symbolic reasoning; specifically solving propositional logic reasoning problems given in-context. Previous work demonstrated that models fail to generalize to problems involving variable names that were not observed during training, and it was shown that one reason behind this is the difficulty of copying (or generating) unseen tokens. We show both theoretically and empirically that a particular representational collapse also has a crucial role: the unembeddings (last-layer weights) of unseen tokens collapse to nearly the same vector during training. The collapse makes distinguishing multiple unseen variables difficult for the model (especially when the embedding and unembedding parameters are shared), and provides a mechanistic explanation for the effectiveness of existing heuristic interventions like "active forgetting", which periodically reset the token (un)embeddings. Based on these observations, we devise a combination of techniques, involving a small architecture change facilitating copying, data diversity, and freezing or resetting (un)embeddings, that achieves generalization to unseen tokens. We support our claims with extensive controlled experiments on propositional logic reasoning problems. Beyond synthetic experiments, we also observe evidence of (un)embedding collapse in the open-weight models in the Gemma 3 family, which includes 99 unused tokens reserved for downstream use. Empirically we find that the correlated embeddings of these tokens are a poor initialization for finetuning applications.
### Title:
          Geometric Monomial (GEM): a family of rational 2N-differentiable activation functions
 - **Authors:** Eylon E. Krause
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The choice of activation function plays a crucial role in the optimization and performance of deep neural networks. While the Rectified Linear Unit (ReLU) remains the dominant choice due to its simplicity and effectiveness, its lack of smoothness may hinder gradient-based optimization in deep architectures. In this work we propose a family of $C^{2N}$-smooth activation functions whose gate follows a log-logistic CDF, achieving ReLU-like performance with purely rational arithmetic. We introduce three variants: GEM (the base family), E-GEM (an $\epsilon$-parameterized generalization enabling arbitrary $L^p$-approximation of ReLU), and SE-GEM (a piecewise variant eliminating dead neurons with $C^{2N}$ junction smoothness). An $N$-ablation study establishes $N=1$ as optimal for standard-depth networks, reducing the GELU deficit on CIFAR-100 + ResNet-56 from 6.10% to 2.12%. The smoothness parameter $N$ further reveals a CNN-transformer tradeoff: $N=1$ is preferred for deep CNNs, while $N=2$ is preferred for transformers. On MNIST, E-GEM ties the best baseline (99.23%). On CIFAR-10 + ResNet-56, SE-GEM ($\epsilon=10^{-4}$) surpasses GELU (92.51% vs 92.44%) -- the first GEM-family activation to outperform GELU. On CIFAR-100 + ResNet-56, E-GEM reduces the GELU deficit from 6.10% (GEM $N=2$) to just 0.62%. On GPT-2 (124M), GEM achieves the lowest perplexity (72.57 vs 73.76 for GELU), with GEM $N=1$ also beating GELU (73.32). On BERT-small, E-GEM ($\epsilon=10$) achieves the best validation loss (6.656) across all activations. The $\epsilon$-parameterization reveals a scale-dependent optimum: small $\epsilon$ ($10^{-4}$--$10^{-6}$) for deep CNNs and larger transformers, with the special case of small transformers (BERT-small) benefiting from large $\epsilon$ ($\epsilon=10$) due to its limited depth and unconstrained gradients.
### Title:
          Sapiens2
 - **Authors:** Rawal Khirodkar, He Wen, Julieta Martinez, Yuan Dong, Su Zhaoen, Shunsuke Saito
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Sapiens2, a model family of high-resolution transformers for human-centric vision focused on generalization, versatility, and high-fidelity outputs. Our model sizes range from 0.4 to 5 billion parameters, with native 1K resolution and hierarchical variants that support 4K. Sapiens2 substantially improves over its predecessor in both pretraining and post-training. First, to learn features that capture low-level details (for dense prediction) and high-level semantics (for zero-shot or few-label settings), we combine masked image reconstruction with self-distilled contrastive objectives. Our evaluations show that this unified pretraining objective is better suited for a wider range of downstream tasks. Second, along the data axis, we pretrain on a curated dataset of 1 billion high-quality human images and improve the quality and quantity of task annotations. Third, architecturally, we incorporate advances from frontier models that enable longer training schedules with improved stability. Our 4K models adopt windowed attention to reason over longer spatial context and are pretrained with 2K output resolution. Sapiens2 sets a new state-of-the-art and improves over the first generation on pose (+4 mAP), body-part segmentation (+24.3 mIoU), normal estimation (45.6% lower angular error) and extends to new tasks such as pointmap and albedo estimation. Code: this https URL
### Title:
          Evaluating Post-hoc Explanations of the Transformer-based Genome Language Model DNABERT-2
 - **Authors:** Isabel Kurth, Paulo Yanez Sarmiento, Bernhard Y. Renard
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Explaining deep neural network predictions on genome sequences enables biological insight and hypothesis generation-often of greater interest than predictive performance alone. While explanations of convolutional neural networks (CNNs) have been shown to capture relevant patterns in genome sequences, it is unclear whether this transfers to more expressive Transformer-based genome language models (gLMs). To answer this question, we adapt AttnLRP, an extension of layer-wise relevance propagation to the attention mechanism, and apply it to the state-of-the-art gLM DNABERT-2. Thereby, we propose strategies to transfer explanations from token and nucleotide level. We evaluate the adaption of AttnLRP on genomic datasets using multiple metrics. Further, we provide an extensive comparison between the explanations of DNABERT-2 and a baseline CNN. Our results demonstrate that AttnLRP yields reliable explanations corresponding to known biological patterns. Hence, like CNNs, gLMs can also help derive biological insights. This work contributes to the explainability of gLMs and addresses the comparability of relevance attributions across different architectures.
### Title:
          Discriminative-Generative Synergy for Occlusion Robust 3D Human Mesh Recovery
 - **Authors:** Yang Liu, Zhiyong Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D human mesh recovery from monocular RGB images aims to estimate anatomically plausible 3D human models for downstream applications, but remains challenging under partial or severe occlusions. Regression-based methods are efficient yet often produce implausible or inaccurate results in unconstrained scenarios, while diffusion-based methods provide strong generative priors for occluded regions but may weaken fidelity to rare poses due to over-reliance on generation. To address these limitations, we propose a brain-inspired synergistic framework that integrates the discriminative power of vision transformers with the generative capability of conditional diffusion models. Specifically, the ViT-based pathway extracts deterministic visual cues from visible regions, while the diffusion-based pathway synthesizes structurally coherent human body representations. To effectively bridge the two pathways, we design a diverse-consistent feature learning module to align discriminative features with generative priors, and a cross-attention multi-level fusion mechanism to enable bidirectional interaction across semantic levels. Experiments on standard benchmarks demonstrate that our method achieves superior performance on key metrics and shows strong robustness in complex real-world scenarios.
### Title:
          Reshoot-Anything: A Self-Supervised Model for In-the-Wild Video Reshooting
 - **Authors:** Avinash Paliwal, Adithya Iyer, Shivin Yadav, Muhammad Ali Afridi, Midhun Harikumar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Precise camera control for reshooting dynamic videos is bottlenecked by the severe scarcity of paired multi-view data for non-rigid scenes. We overcome this limitation with a highly scalable self-supervised framework capable of leveraging internet-scale monocular videos. Our core contribution is the generation of pseudo multi-view training triplets, consisting of a source video, a geometric anchor, and a target video. We achieve this by extracting distinct smooth random-walk crop trajectories from a single input video to serve as the source and target views. The anchor is synthetically generated by forward-warping the first frame of the source with a dense tracking field, which effectively simulates the distorted point-cloud inputs expected at inference. Because our independent cropping strategy introduces spatial misalignment and artificial occlusions, the model cannot simply copy information from the current source frame. Instead, it is forced to implicitly learn 4D spatiotemporal structures by actively routing and re-projecting missing high-fidelity textures across distinct times and viewpoints from the source video to reconstruct the target. At inference, our minimally adapted diffusion transformer utilizes a 4D point-cloud derived anchor to achieve state-of-the-art temporal consistency, robust camera control, and high-fidelity novel view synthesis on complex dynamic scenes.
### Title:
          A Multi-Stage Warm-Start Deep Learning Framework for Unit Commitment
 - **Authors:** Muhy Eddin Za'ter, Anna Van Boven, Bri-Mathias Hodge, Kyri Baker
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Maintaining instantaneous balance between electricity supply and demand is critical for reliability and grid instability. System operators achieve this through solving the task of Unit Commitment (UC),ca high dimensional large-scale Mixed-integer Linear Programming (MILP) problem that is strictly and heavily governed by the grid physical constraints. As grid integrate variable renewable sources, and new technologies such as long duration storage in the grid, UC must be optimally solved for multi-day horizons and potentially with greater frequency. Therefore, traditional MILP solvers increasingly struggle to compute solutions within these tightening operational time limits. To bypass these computational bottlenecks, this paper proposes a novel framework utilizing a transformer-based architecture to predict generator commitment schedules over a 72-hour horizon. Also, because raw predictions in highly dimensional spaces often yield physically infeasible results, the pipeline integrates the self-attention network with deterministic post-processing heuristics that systematically enforce minimum up/down times and minimize excess capacity. Finally, these refined predictions are utilized as a warm start for a downstream MILP solver, while employing a confidence-based variable fixation strategy to drastically reduce the combinatorial search space. Validated on a single-bus test system, the complete multi-stage pipeline achieves 100\% feasibility and significantly accelerates computation times. Notably, in approximately 20\% of test instances, the proposed model reached a feasible operational schedule with a lower overall system cost than relying solely on the solver.
## Keyword: autonomous driving
### Title:
          Towards a Systematic Risk Assessment of Deep Neural Network Limitations in Autonomous Driving Perception
 - **Authors:** Svetlana Pavlitska, Christopher Gerking, J. Marius Zöllner
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Computers and Society (cs.CY); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Safety and security are essential for the admission and acceptance of automated and autonomous vehicles. Deep neural networks (DNNs) are widely used for perception and further components of the autonomous driving (AD) stack. However, they possess several limitations, including lack of generalization, efficiency, explainability, plausibility, and robustness. These insufficiencies can pose significant risks to autonomous driving systems. However, hazards, threats, and risks associated with DNN limitations in this domain have not been systematically studied so far. In this work, we propose a joint workflow for risk assessment combining the hazard analysis and risk assessment (HARA) following ISO 26262 and threat analysis and risk assessment (TARA) following the ISO/SAE 21434 to identify and analyze risks arising from inherent DNN limitations in AD perception.
### Title:
          Enabling Mixed criticality applications for the Versal AI-Engines
 - **Authors:** Vincent Sprave, Martin Wilhelm, Daniele Passaretti, Alberto Garcia-Ortiz, Thilo Pionteck
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adaptive Systems-on-Chips (SoCs) are increasingly being used in mixed criticality systems (MCSs), such as in autonomous driving, aviation and medical systems. In this context, AMD has proposed the Versal SoC, which has a heterogeneous architecture including, among other components, an Artificial Intelligence Engine (AIE), which is a 2D array of processors and memory tiles designed for AI and signal processing workloads. While this AIE offers significant potential for accelerating real-time data processing tasks, this has not yet been explored in the context of MCSs since individual tasks with different criticality levels cannot be dynamically assigned to tiles due to the static mapping of dataflow graphs and tasks. In this work, we propose a dynamic task dispatching infrastructure that enables task switching on the AIE at runtime. Based on this infrastructure, we present an MCS design that dynamically assigns tasks of different criticality to a pool of AIE tiles, depending on the criticality mode of the system. Our approach overcomes the limitations of static dataflow graph mappings and, for the first time, exploits the parallel processing capabilities of the AIE for MCSs. We also present a comprehensive timing analysis of the overhead introduced by the task dispatcher infrastructure, focusing on control logic, context switching and data copy operations. This shows that these operations have low variance and are negligible compared to the overall execution time, demonstrating that our infrastructure is suitable for MCSs. Finally, we evaluate the proposed infrastructure using an autonomous driving workload with tasks that have variable execution times and different criticality levels. In this case study, we maximized AIE utilization, reducing idle time by 65.5 %, while measuring an execution time overhead of less than 0.002 %, and doubling the throughput of low-criticality tasks.
### Title:
          Reasoning About Traversability: Language-Guided Off-Road 3D Trajectory Planning
 - **Authors:** Byounggun Park, Soonmin Hwang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Vision-Language Models (VLMs) enable high-level semantic reasoning for end-to-end autonomous driving, particularly in unstructured environments, existing off-road datasets suffer from language annotations that are weakly aligned with vehicle actions and terrain geometry. To address this misalignment, we propose a language refinement framework that restructures annotations into action-aligned pairs, enabling a VLM to generate refined scene descriptions and 3D future trajectories directly from a single image. To further encourage terrain-aware planning, we introduce a preference optimization strategy that constructs geometry-aware hard negatives and explicitly penalizes trajectories inconsistent with local elevation profiles. Furthermore, we propose off-road-specific metrics to quantify traversability compliance and elevation consistency, addressing the limitations of conventional on-road evaluation. Experiments on the ORAD-3D benchmark demonstrate that our approach reduces average trajectory error from 1.01m to 0.97m, improves traversability compliance from 0.621 to 0.644, and decreases elevation inconsistency from 0.428 to 0.322, highlighting the efficacy of action-aligned supervision and terrain-aware optimization for robust off-road driving.
### Title:
          Frozen LLMs as Map-Aware Spatio-Temporal Reasoners for Vehicle Trajectory Prediction
 - **Authors:** Yanjiao Liu, Jiawei Liu, Xun Gong, Zifei Nie
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) have recently demonstrated strong reasoning capabilities and attracted increasing research attention in the field of autonomous driving (AD). However, safe application of LLMs on AD perception and prediction still requires a thorough understanding of both the dynamic traffic agents and the static road infrastructure. To this end, this study introduces a framework to evaluate the capability of LLMs in understanding the behaviors of dynamic traffic agents and the topology of road networks. The framework leverages frozen LLMs as the reasoning engine, employing a traffic encoder to extract spatial-level scene features from observed trajectories of agents, while a lightweight Convolutional Neural Network (CNN) encodes the local high-definition (HD) maps. To assess the intrinsic reasoning ability of LLMs, the extracted scene features are then transformed into LLM-compatible tokens via a reprogramming adapter. By residing the prediction burden with the LLMs, a simpler linear decoder is applied to output future trajectories. The framework enables a quantitative analysis of the influence of multi-modal information, especially the impact of map semantics on trajectory prediction accuracy, and allows seamless integration of frozen LLMs with minimal adaptation, thereby demonstrating strong generalizability across diverse LLM architectures and providing a unified platform for model evaluation.
### Title:
          MISTY: High-Throughput Motion Planning via Mixer-based Single-step Drifting
 - **Authors:** Yining Xing, Zehong Ke, Yiqian Tu, Zhiyuan Liu, Wenhao Yu, Jianqiang Wang
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-modal trajectory generation is essential for safe autonomous driving, yet existing diffusion-based planners suffer from high inference latency due to iterative neural function evaluations. This paper presents MISTY (Mixer-based Inference for Single-step Trajectory-drifting Yield), a high-throughput generative motion planner that achieves state-of-the-art closed-loop performance with pure single-step inference. MISTY integrates a vectorized Sub-Graph encoder to capture environment context, a Variational Autoencoder to structure expert trajectories into a compact 32-dimensional latent manifold, and an ultra-lightweight MLP-Mixer decoder to eliminate quadratic attention complexity. Importantly, we introduce a latent-space drifting loss that shifts the complex distribution evolution entirely to the training phase. By formulating explicit attractive and repulsive forces, this mechanism empowers the model to synthesize novel, proactive maneuvers, such as active overtaking, that are virtually absent from the raw expert demonstrations. Extensive evaluations on the nuPlan benchmark demonstrate that MISTY achieves state-of-the-art results on the challenging Test14-hard split, with comprehensive scores of 80.32 and 82.21 in non-reactive and reactive settings, respectively. Operating at over 99 FPS with an end-to-end latency of 10.1 ms, MISTY offers an order-of-magnitude speedup over iterative diffusion planners while while achieving significantly robust generation.
