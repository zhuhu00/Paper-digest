# Showing new listings for Monday, 18 May 2026
## Keyword: SLAM
### Title:
          LAPS: Improving Incremental LiDAR Mapping using Active Pooling and Sampling for Neural Distance Fields
 - **Authors:** Dongjae Lee, Wooseong Yang, Yifu Tao, Maurice Fallon, Ayoung Kim
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural distance fields offer a compact and continuous representation of 3D geometry, making them attractive for incremental LiDAR mapping. However, their online optimization is vulnerable to catastrophic forgetting, where new observations can degrade previously reconstructed geometry. Replay-based training is commonly used to address this issue, but existing methods typically rely on passive replay buffers and uniform sampling, which can waste memory on redundant observations and under-train poorly constrained regions. We propose LAPS, a replay management framework for incremental neural mapping that improves both replay retention and replay allocation during online updates. LAPS combines reliability-based active pooling to retain reliable historical samples under limited memory with uncertainty-guided active sampling to focus optimization on under-constrained regions. Experiments on synthetic and real-world benchmarks show that LAPS consistently improves reconstruction completeness while maintaining competitive geometric accuracy. On Oxford Spires, it improves recall by 4.66 pp and F1-score by 3.79 pp over PIN-SLAM on the Blenheim Palace 05 sequence. We release our open source implementation at: this https URL.
## Keyword: odometry
There is no result 
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Multimodal Object Detection Under Sparse Forest-Canopy Occlusion
 - **Authors:** Nitik Jain, Mangal Kothari
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable detection of humans beneath forest canopy remains a difficult remote-sensing challenge due to sparse, structured, and viewpoint-dependent occlusion. This paper presents a multimodal proof-of-concept pipeline that integrates three complementary approaches: (i) experimental evaluation of LiDAR returns through vegetation to assess the feasibility of active sensing, (ii) visible--thermal image fusion using a multi-scale transform and sparse-representation framework to enhance human saliency, and (iii) synthetic-aperture image formation via Airborne Optical Sectioning (AOS) to suppress canopy clutter. A YOLOv5 detector is fine-tuned on the Teledyne FLIR thermal dataset and evaluated on thermal and fused imagery. Results show that the tested terrestrial LiDAR configuration provides limited penetration for object-level detection, while visible--thermal fusion improves target visibility in low-contrast scenes and AOS enhances ground-plane detection in synthetic forest imagery. The fine-tuned YOLOv5 achieves a mean average precision of $\sim$0.83 on the top three FLIR classes. These findings establish an initial baseline for UAV-deployable search-and-rescue and surveillance systems operating in forested environments, and motivate future work on dedicated forest datasets and real-time multimodal integration.
### Title:
          LAPS: Improving Incremental LiDAR Mapping using Active Pooling and Sampling for Neural Distance Fields
 - **Authors:** Dongjae Lee, Wooseong Yang, Yifu Tao, Maurice Fallon, Ayoung Kim
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural distance fields offer a compact and continuous representation of 3D geometry, making them attractive for incremental LiDAR mapping. However, their online optimization is vulnerable to catastrophic forgetting, where new observations can degrade previously reconstructed geometry. Replay-based training is commonly used to address this issue, but existing methods typically rely on passive replay buffers and uniform sampling, which can waste memory on redundant observations and under-train poorly constrained regions. We propose LAPS, a replay management framework for incremental neural mapping that improves both replay retention and replay allocation during online updates. LAPS combines reliability-based active pooling to retain reliable historical samples under limited memory with uncertainty-guided active sampling to focus optimization on under-constrained regions. Experiments on synthetic and real-world benchmarks show that LAPS consistently improves reconstruction completeness while maintaining competitive geometric accuracy. On Oxford Spires, it improves recall by 4.66 pp and F1-score by 3.79 pp over PIN-SLAM on the Blenheim Palace 05 sequence. We release our open source implementation at: this https URL.
### Title:
          3DTMDet: A Dual-Path Synergy Network of Transformer and SSM for 3D Object Detection in Point Clouds
 - **Authors:** Bingwen Qiu, Yuan Liu, Junqi Bai, Tong Jiang, Ben Liang, Fangzhou Chen, Xiubao Sui, Qian Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A fundamental challenge in point cloud object detection lies in the conflict between the extreme sparsity of distant points and the need for remote context understanding. The existing methods typically use 1D serialization to expand the receptive field, which inevitably discards already scarce local geometric details and reduces detection of distant and small objects. To address this issue, we propose 3DTMDet, a novel detection network that synergistically combines state space models (Mamba) with Transformers. The core idea is to utilize SSM's linear complexity and advantages in long sequence modeling to effectively capture global interactions between sparse and distant points, while using Transformer modules with local attention to encode fine-grained geometric structures in local point sets, preserving accurate shape information. We propose the 3D Hybrid Mamba Transformer (3DHMT) block, which uses an SSM-Attention-SSM pipeline to balance global context understanding and local detail preservation, effectively alleviating the tension between receptive field enlargement and geometric preservation in remote detection. In addition, we introduced a voxel generation block inspired by LiDAR physics, which diffuses features along the sensor observation direction to reconstruct the complete object structure of occlusion and distant areas. Extensive experiments conducted on the KITTI and ONCE datasets have shown that 3DTMDet outperforms state-of-the-art detectors. The code is available at this https URL.
### Title:
          Reactive Robot-Centric Safety for Autonomous Navigation in Constrained and Dynamic Environments
 - **Authors:** Viswa Narayanan Sankaranarayanan, Vignesh K. Viswanathan, Akshit Saradagi, Sumeet Satpute, George Nikolakopoulos
 - **Subjects:** Subjects:
Robotics (cs.RO); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this work, we address the problem of ensuring real-time safety in autonomous robot navigation, in spatially constrained dynamic environments, by utilizing only onboard sensors. We present a real-time control architecture that integrates a 3D LIDAR perception-based composite control barrier function(CBF)-based safety filter directly into the autonomy pipeline. The proposed perception-driven framework enforces collision avoidance constraints dynamically from onboard point cloud data, thus allowing a large number of constraints to be handled at the control frequency, while remaining minimally invasive to nominal task execution. The safety region is defined as an ellipsoid in the body-frame, consistent with the geometry of the platform, which induces time-varying constraints in the world frame as the robot rotates; this effect is handled through a dedicated formulation of time-varying (CBF) for each LIDAR point. We validate the system through multiple field experiments in underground environments by utilizing a quadruped platform performing a visual inspection task, demonstrating reliable operation in the presence of dynamic obstacles, unsafe high-level references, abrupt localization anomalies, and while traversing through narrow corridors.
### Title:
          Constrained MPC-Based Motion Planning for Morphing Quadrotors in Ultra-Narrow Passages under Limited Perception
 - **Authors:** Harsh Modi, Xiao Liang, Minghui Zheng
 - **Subjects:** Subjects:
Robotics (cs.RO); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper introduces a motion planning framework to plan morphology and trajectory for morphing quadrotors under extremely constrained environments. We develop a novel obstacle avoidance cost function for nonlinear model predictive control (MPC) that enables navigation through extremely narrow gaps under limited perception from a 2D LiDAR. Classical artificial potential field-based costs typically have a high cost in narrow passages, artificially blocking the navigable path. In contrast, we propose a smooth exponential obstacle cost that preserves low traversal cost within narrow gaps while maintaining strong collision avoidance behavior. The formulation avoids hard activation thresholds and introduces a cost reduction factor to reduce the cost within narrow passages. Direct use of 2D LiDAR measurements in MPC allows navigation around arbitrarily shaped obstacles. The method is embedded within an acados-based nonlinear MPC framework. Simulation and experimental results demonstrate successful traversal of narrow corridors where typical repulsive cost functions would fail. The approach provides a computationally efficient and practical solution for navigating through tight spaces while maintaining safety from the obstacles. While we are implementing the framework on the morphing quadrotors, the cost function formulation is general-purpose for any mobile robot application, and is not limited to the morphing quadrotors. The implementation code is available at \href{this https URL}{Github Repo} and a short video is available at \href{this https URL}{Video Link}.
### Title:
          Fast Expanding Safe Circular Regions for Efficient Local Path Planning
 - **Authors:** Scott Fredriksson, Akshit Saradagi, George Nikolakopoulos
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Local navigation is one of the fundamental problems in robot navigation, and numerous approaches have been proposed over the years, including methods such as the Dynamic Window Approach, Model Predictive Control, and more recently, Control Barrier Functions and machine learning based techniques. While these methods perform well in simple environments, many of them rely on optimization or learning based procedures that can struggle in more complex scenarios. In contrast, this article proposes a more geometric algorithmic approach that enables a local navigation method with faster computation times and longer planning horizons. The proposed method is based on the computation of a sequence of circular regions from a local LiDAR scan that expand in the direction of the goal and capture free local navigable space. The proposed method was implemented in the ROS2 framework and evaluated in a simulated environment.
### Title:
          WeatherOcc3D: VLM-Assisted Adverse Weather Aware 3D Semantic Occupancy Prediction
 - **Authors:** A. Enes Doruk, Abdelaziz Hussein, Hasan F. Ates
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While multi-modal 3D semantic occupancy prediction typically enhances robustness by fusing camera and LiDAR inputs, its effectiveness is fundamentally constrained by environmental variability. Specifically, camera sensors suffer from severe low-light degradation, while LiDAR sensors encounter significant backscatter noise during heavy precipitation. These adverse conditions create a modality trust problem, as static fusion strategies fail to adaptively re-weight inputs when a specific sensor becomes unreliable. To address this, we propose a VLM-assisted framework leveraging the pre-trained CLIP latent space to guide multi-sensor integration via linguistic environmental cues. We utilize a parameter-efficient adapter to align weather-specific text embeddings with sensor features, coupled with a gating strategy that decomposes environmental uncertainty into two factors: visibility and illumination. This enables the model to dynamically modulate the fusion ratio - prioritizing semantic camera features in clear daylight and shifting to geometric LiDAR priors during rainy nights. Evaluations on the nuScenes dataset demonstrate the versatility of our approach, as implementing our proposed framework on the OccMamba and M-CONet architectures achieves mIoU scores of 26.3 and 21.1, respectively, significantly outperforming their traditional baselines.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          SDOF: Taming the Alignment Tax in Multi-Agent Orchestration with State-Constrained Dispatch
 - **Authors:** Zhantao Wang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-agent orchestration frameworks such as LangChain, LangGraph, and CrewAI route tasks through graph-based pipelines but do not enforce the stage constraints that govern real business processes. We present SDOF, a framework that treats multi-agent execution as a constrained state machine. SDOF operates through two primary defensive layers, implemented by three components: (1) an Online-RLHF Specialized Intent Router trained via Generative Reward Modeling (GRPO) and (2) a StateAwareDispatcher with GoalStage finite-automaton checks and precondition/postcondition SkillRegistry validation for auditable execution control. On a recruitment system backed by the Beisen iTalent platform (6000+ enterprises), 185 expert-curated scenarios trigger 1671 live API calls. Our GSPO-aligned 7B Intent Router achieves higher joint accuracy than zero-shot GPT-4o on this FSM-constrained adversarial routing benchmark (80.9% versus 48.9%). In end-to-end execution, SDOF reaches 86.5% task completion (95% confidence interval 80.8 to 90.7) and blocks all 22 operations in the injection, illegal HR subset. Under a broader message-level blocking audit, SDOF attains precision 100% and recall 88%, expert agreement kappa=0.94. A separate evaluation on 960 SGD-derived dialogues spanning 8 service domains surfaces 201 stage-order conflicts under our FSM mapping, 41 of which arise in the normal split. This arXiv version reports the current validated scope; extended multi-seed training comparisons and deeper workflow evaluations will be released in a subsequent update.
### Title:
          One Pass Is Not Enough: Recursive Latent Refinement for Generative Models
 - **Authors:** Mehdi Esmaeilzadeh, Alexia Jolicoeur-Martineau, Chirag Vashist, Ke Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite remarkable progress, image generation is far from solved. The dominant metric, FID, conflates sample fidelity with mode coverage and is close to being saturated. Yet a model can still exhibit mode collapse while achieving a low FID, since a handful of sharp, near-duplicate images can outscore a model that faithfully covers the full data distribution. We argue that precision and recall are essential complements to FID, and that because FID is already saturated, the more meaningful goal is to improve diversity and coverage. Achieving high recall requires a model that explicitly prioritizes mode coverage, unlike most generative models, which optimize sample fidelity. We introduce RTM, which replaces the single-pass latent mapping in style-based generators with an iterative refinement process, and show that this consistently improves both quality and diversity. Integrated with Implicit Maximum Likelihood Estimation (IMLE), which optimizes mode coverage by design, RTM achieves the highest precision and recall among current state-of-the-art approaches while maintaining competitive FID, with improvements across CIFAR-10, CelebA-HQ at 256x256, and nine few-shot benchmarks. RTM also improves StyleGAN2 and StyleGAN2-ADA on CIFAR-10 and AFHQ-v1 at 512x512, demonstrating that the benefit is not specific to IMLE. Unlike flow-matching baselines that achieve competitive FID at the expense of coverage, recursive refinement improves both quality and diversity simultaneously.
### Title:
          LAPS: Improving Incremental LiDAR Mapping using Active Pooling and Sampling for Neural Distance Fields
 - **Authors:** Dongjae Lee, Wooseong Yang, Yifu Tao, Maurice Fallon, Ayoung Kim
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural distance fields offer a compact and continuous representation of 3D geometry, making them attractive for incremental LiDAR mapping. However, their online optimization is vulnerable to catastrophic forgetting, where new observations can degrade previously reconstructed geometry. Replay-based training is commonly used to address this issue, but existing methods typically rely on passive replay buffers and uniform sampling, which can waste memory on redundant observations and under-train poorly constrained regions. We propose LAPS, a replay management framework for incremental neural mapping that improves both replay retention and replay allocation during online updates. LAPS combines reliability-based active pooling to retain reliable historical samples under limited memory with uncertainty-guided active sampling to focus optimization on under-constrained regions. Experiments on synthetic and real-world benchmarks show that LAPS consistently improves reconstruction completeness while maintaining competitive geometric accuracy. On Oxford Spires, it improves recall by 4.66 pp and F1-score by 3.79 pp over PIN-SLAM on the Blenheim Palace 05 sequence. We release our open source implementation at: this https URL.
### Title:
          IO-SVD: Input-Output Whitened SVD for Adaptive-Rank LLM Compression
 - **Authors:** Ali Abbasi, Chayne Thrash, Haoran Qin, Hamed Pirsiavash, Soheil Kolouri
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models deliver strong performance across language and reasoning tasks, but their storage and compute costs remain major barriers to deployment in resource-constrained and latency-sensitive settings. SVD-based post-training compression offers a hardware-agnostic way to reduce model size and improve inference efficiency through low-rank factorization. However, existing methods often rely on input-only whitening spaces, homogeneous rank allocation, or loss-agnostic allocation heuristics, limiting their ability to preserve model quality under aggressive compression. We propose Input-Output Whitened SVD (IO-SVD), a post-training compression method that forms a KL-aware double-sided whitening space for model weights. Using a second-order expansion of the KL loss over the top-K token probabilities, IO-SVD constructs an output-side metric that captures predictive sensitivity, while input whitening captures activation statistics. We further introduce an efficient heterogeneous rank-allocation strategy that scores whitened singular components using first-order calibration loss estimates and prunes the least sensitive components under a global budget. Inspired by prior work that combines SVD truncation with quantization, we improve hybrid SVD-quantization compression through loss-aware remapping, which selects low-rank factor rows for 8-bit quantization based on the predicted loss change incurred by quantizing them. Extensive experiments across diverse LLM and VLM families, and inference-time analysis shows that IO-SVD compresses LLMs with minimal performance degradation while delivering practical inference speedups. Code is available at this https URL
### Title:
          Endpoint-singularity-preserving spectral approximation theory for weakly singular integral equations
 - **Authors:** Mahmoud A. Zaky
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce a fractional approximation framework for functions with limited regularity near the terminal point. The proposed basis is constructed by composing classical Jacobi polynomials with an endpoint algebraic mapping, thereby incorporating the terminal singular structure directly into the approximation space. The main structural properties of the fractional polynomials are established, including orthogonality relations, derivative identities, and a singular Sturm--Liouville eigenvalue formulation. We then introduce the associated weighted Sobolev spaces and prove projection and Gauss-type interpolation error estimates in weighted norms. Inverse inequalities and weighted Sobolev embedding estimates are also derived. The resulting theory provides a rigorous foundation for high-order spectral and collocation approximations of endpoint-singular and weakly regular problems, including terminal value problems, fractional differential equations, and weakly singular Volterra integral equations.
### Title:
          Ontology for Policing: Conceptual Knowledge Learning for Semantic Understanding and Reasoning in Law Enforcement Reports
 - **Authors:** Anita Srbinovska, Jansen Orfan, Adrian Martin, Ernest Fokoué
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Logic in Computer Science (cs.LO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Law enforcement reports contain structured fields and written narratives. However, many incident facts that are needed for review, police training, and investigations are in natural language and require manual reading. We propose a framework using symbolic methods for converting narratives into evidence-linked facts. Our objective is to measure the value of narratives to recover incident details only from the unstructured text and build temporal graphs with time cues and domain axioms. We achieve this by redacting personal identifiers, semantic parsing, predicate mapping to ontology, and reasoning. We evaluate the symbolic approach on 450 property crime reports and a short human review. Of the extracted events from the system, 54.1% had a confidence score of at least 0.80 and 93.7% were mapped through the PropBank--VerbNet--WordNet semantic path. 100% agreement was reached on incident initiation, stolen items, and temporal cues and lower agreement for forced entry interpretation.
## Keyword: localization
### Title:
          Is Agentic AI Ready for Real-World Hardware Engineering? A Deep Dive with Phoenix-bench
 - **Authors:** Qingyun Zou, Feng Yu, Hongshi Tan, Bingsheng He, WengFai Wong
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Artificial Intelligence (cs.AI); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We ask whether agentic AI systems built for software engineering transfer to realistic hardware engineering. Existing hardware LLM benchmarks isolate sub-tasks but none jointly requires repository navigation, hierarchy-aware localization, Electronic Design Automation (EDA) executable verification, and maintenance-style patching. We introduce \textbf{Phoenix-bench}, a synchronized corpus of 511 verified Verilator instances from 114 GitHub repositories, each shipped with the developer patch, design-flow labels, fail-to-pass and pass-to-pass testbenches, and a Docker-pinned EDA environment so resolved-rate differences reflect agent behavior rather than toolchain availability. Using Phoenix-bench we run a uniform evaluation of four commercial agents and eight open-source agentic structures across four LLM backbones, plus two diagnostic interventions (file-level oracle localization and one round of testbench-log feedback). Three findings emerge. (i)~Software and hardware are fundamentally different engineering tasks: the same agent loses 37\% to 58\% from SWE-bench Verified to Phoenix-bench because hardware bugs propagate across parallel instantiated modules through signal flow rather than along a software-style call graph, and software-tuned agents stop at the symptom file instead of tracing back through the instantiation chain. (ii)~Failures concentrate on design control-flow / finite state machine (FSM) bugs, verification testbench bugs, and hard cases that demand cross-hierarchy signal-flow tracking and coordinated multi-file edits. (iii)~Localization granularity matters far more than localization itself: a perfect file-level oracle yields only $+1.4$\% because the agent then breaks files that did not need editing, while a single round of test case feedback lifts resolved rate by $42$\% to $45$\% because the test case tells \emph{where} the bug is and \emph{what} the fix has to look like.
### Title:
          Proposal-Guided Greedy Surrogate Refinement for PDE-Driven High-Dimensional Rare-Event Estimation
 - **Authors:** Zhiwei Gao, George Karniadakis
 - **Subjects:** Subjects:
Numerical Analysis (math.NA); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate surrogate construction for PDE-driven high-dimensional rare-event simulation is challenging when performance evaluations are expensive. Since a globally accurate surrogate may require many high-fidelity evaluations, adaptive importance sampling provides a natural localization tool: its evolving proposal distribution progressively identifies the failure-relevant region. Motivated by this observation, we propose a surrogate-assisted adaptive importance sampling framework that refines the surrogate locally along the evolving proposal, rather than over the entire input space. The surrogate combines an encoder with a neural network, providing a low-dimensional latent representation for both prediction and sample selection. At each adaptive iteration, candidates drawn from the current proposal are selected by a greedy latent-space rule balancing proximity to the estimated failure boundary and sample diversity. The selected samples are evaluated by the high-fidelity model and used to refine the surrogate, which then guides the subsequent cross-entropy-type adaptive proposal update. We establish one-step proposal stability bounds under local surrogate errors, together with surrogate-induced misclassification and finite-sample estimation error bounds. Numerical experiments on multimodal benchmarks and PDE-driven rare-event problems up to 100 dimensions show that the proposed method achieves accuracy comparable to true-model adaptive importance sampling while requiring substantially fewer high-fidelity evaluations.
### Title:
          Learning Dynamic Structural Specialization for Underwater Salient Object Detection
 - **Authors:** Lin Hong, Chenhui Wang, Linan Deng, Yuning Cui, Yu Zhang, Xin Wang, Bojian Zhang, Wenqi Ren, Xingchen Yang, Fumin Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Underwater salient object detection (USOD) has attracted increasing attention for underwater visual scene understanding and vision-guided robotic applications. However, existing USOD methods still struggle with underwater image degradations, which often lead to inaccurate object localization, fragmented salient regions, and coarse boundary prediction. To address these challenges, this paper proposes DSS-USOD, a novel RGB-based USOD method built upon dynamic structural specialization. DSS-USOD extracts a shared base representation from a single underwater image, decomposes it into boundary-sensitive and region-coherent structural features, and dynamically coordinates their contributions according to local structural context. Specifically, the extracted shared base representation is decomposed into a boundary-sensitive branch for modeling fine-grained boundary details and a region-coherent branch for capturing region-level structural consistency. A spatial coordination module is then introduced to adaptively regulate the relative contributions of the two branches according to local structural context. Moreover, cooperative structural supervision is introduced to promote branch specialization and stabilize spatial coordination, enabling DSS-USOD to better balance boundary precision and region coherence under degraded underwater conditions. Extensive experiments show that DSS-USOD achieves superior performance on benchmark datasets. Finally, real-world deployment on an underwater robot validates the practical effectiveness of DSS-USOD for underwater object inspection.
### Title:
          MI-CXR: A Benchmark for Longitudinal Reasoning over Multi-Interval Chest X-rays
 - **Authors:** Sunghwan Steve Cho, Yunseok Han, Jaeyoung Do
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Longitudinal chest X-ray (CXR) interpretation requires reasoning over disease evolution across multiple patient visits, yet most existing medical VQA benchmarks focus on single images or short-horizon image pairs. We introduce MI-CXR, a benchmark for standardized evaluation of Multi-Interval longitudinal reasoning over multi-visit CXR sequences, without requiring free-form report generation or additional clinical context. MI-CXR comprises five-way multiple-choice questions over five-visit patient timelines and instantiates three complementary task families: Temporal Event Localization, Interval-wise Change Reasoning, and Global Trajectory Summarization, which assess clinically grounded visual reasoning over time. Evaluating 14 state-of-the-art vision-language models (VLMs) shows low overall performance, with an average accuracy of 29.3%, only modestly above random guessing. Using stage-wise diagnostic probing, we find that models often produce locally plausible interval descriptions but fail to enforce temporal constraints or compose evidence into globally consistent decisions over the full timeline. These findings reveal key limitations of current VLMs and establish MI-CXR as a principled benchmark for longitudinal medical reasoning. The benchmark is available at this https URL
### Title:
          STAR: A Stage-attributed Triage and Repair framework for RCA Agents in Microservices
 - **Authors:** Junle Wang, Xingchuang Liao, Wenjun Wu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLM-based root cause analysis (RCA) agents have recently emerged as a promising paradigm for incident diagnosis in microservice AIOps. However, their reliability remains fragile: an error in early evidence collection, hypothesis formulation, or causal analysis can propagate through the reasoning trace and eventually corrupt the final diagnosis. In this paper, we present \textbf{STAR}, a \emph{Stage-attributed Triage and Repair} framework for repairing erroneous RCA traces. STAR explicitly decomposes an RCA workflow into four structured stages, namely \emph{Evidence Package} (EP), \emph{Hypothesis Set} (HS), \emph{Analysis Structure} (AS), and \emph{Decision Report} (DR), and treats agent failure as a stage-localizable reasoning bug rather than a monolithic end-to-end error. Built on top of LangGraph, STAR performs stage-wise auditing, budget-aware \emph{Fast/Slow Routing}, \emph{decisive stage localization via counterfactual candidate evaluation}, and stage-specific patch-and-replay repair. We evaluate STAR on a public large-scale benchmark and a real-world production dataset, using two RCA agent workflows and three foundation models. Experimental results show that STAR consistently improves both root cause localization and fault type classification over strong baselines. Moreover, STAR identifies the decisive faulty stage with high accuracy, repairs most initially incorrect traces within one or two replay rounds, and benefits substantially from both Fast/Slow Routing and counterfactual stage evaluation. These results suggest that explicitly modeling \emph{where} an RCA agent fails is an effective path toward reliable, debuggable, and self-repairing agentic RCA systems.
### Title:
          Reactive Robot-Centric Safety for Autonomous Navigation in Constrained and Dynamic Environments
 - **Authors:** Viswa Narayanan Sankaranarayanan, Vignesh K. Viswanathan, Akshit Saradagi, Sumeet Satpute, George Nikolakopoulos
 - **Subjects:** Subjects:
Robotics (cs.RO); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this work, we address the problem of ensuring real-time safety in autonomous robot navigation, in spatially constrained dynamic environments, by utilizing only onboard sensors. We present a real-time control architecture that integrates a 3D LIDAR perception-based composite control barrier function(CBF)-based safety filter directly into the autonomy pipeline. The proposed perception-driven framework enforces collision avoidance constraints dynamically from onboard point cloud data, thus allowing a large number of constraints to be handled at the control frequency, while remaining minimally invasive to nominal task execution. The safety region is defined as an ellipsoid in the body-frame, consistent with the geometry of the platform, which induces time-varying constraints in the world frame as the robot rotates; this effect is handled through a dedicated formulation of time-varying (CBF) for each LIDAR point. We validate the system through multiple field experiments in underground environments by utilizing a quadruped platform performing a visual inspection task, demonstrating reliable operation in the presence of dynamic obstacles, unsafe high-level references, abrupt localization anomalies, and while traversing through narrow corridors.
### Title:
          VideoSeeker: Incentivizing Instance-level Video Understanding via Native Agentic Tool Invocation
 - **Authors:** Yiming Zhao, Yu Zeng, Wenxuan Huang, Zhen Fang, Qing Miao, Qisheng Su, Jiawei Zhao, Jiayin Cai, Lin Chen, Zehui Chen, Yukun Qi, Yao Hu, Xiaolong Jiang, Feng Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Vision-Language Models (LVLMs) have shown significant progress in video understanding, yet they face substantial challenges in tasks requiring precise spatiotemporal localization at the instance level. Existing methods primarily rely on text prompts for human-model interaction, but these prompts struggle to provide precise spatial and temporal references, resulting in poor user experience. Furthermore, current approaches typically decouple visual perception from language reasoning, centering reasoning around language rather than visual content, which limits the model's ability to proactively perceive fine-grained visual evidence. To address these challenges, we propose VideoSeeker, a novel paradigm for instance-level video understanding through visual prompts. VideoSeeker seamlessly integrates agentic reasoning with instance-level video understanding tasks, enabling the model to proactively perceive and retrieve relevant video segments on demand. We construct a four-stage fully automated data synthesis pipeline to efficiently generate large-scale, high-quality instance-level video data. We internalize tool-calling and proactive perception capabilities into the model via cold-start supervision and RL training, building a powerful video understanding model. Experiments demonstrate that our model achieves an average improvement of +13.7% over baselines on instance-level video understanding tasks, surpassing powerful closed-source models such as GPT-4o and Gemini-2.5-Pro, while also showing effective transferability on general video understanding benchmarks. The relevant datasets and code will be released publicly.
## Keyword: transformer
### Title:
          Unified Simulation of Lagrangian Particle Dynamics via Transformer
 - **Authors:** Caoliwen Wang, Minghao Guo, Siyuan Chen, Heng Zhang, Mengdi Wang, Xingyu Ni, Hanson Sun, Kunyi Wang, Zherong Pan, Kui Wu, Lingjie Liu, Yin Yang, Chenfanfu Jiang, Taku Komura, Wojciech Matusik, Peter Yichen Chen
 - **Subjects:** Subjects:
Graphics (cs.GR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A unified simulator that can model diverse physical phenomena without solver-specific redesign is a long-standing goal across simulation science. We present a learning-based particle simulator built on a single transformer architecture to model cloth, elastic solds, Newtonian and non-Newtonian fluids, granular materials, and molecular dynamics. Our model follows a prediction-correction design on a shared Lagrangian particle representation. An explicit predictor first advances particles under the known external forces, producing an intermediate state that captures externally driven motion but not inter-particle interactions. A learned corrector then predicts the residual position and velocity updates through three stages: a particle tokenizer that encodes local particle-particle, particle-boundary, and topology-guided interactions; a super-token encoder that hierarchically merges particle tokens into a compact set of super tokens via alternating self-attention and token merging; and a super-token decoder that lifts these super tokens back to particle resolution through cross-attention to predict per-particle position and velocity corrections. Progressive token merging reduces the attention cost at successive encoder layers by halving the token count at each level, and the decoder communicates through the compact super-token set rather than full particle-to-particle attention. Across the six dynamics categories, the same architecture generalizes to unseen materials, boundary configurations, initial conditions, and external forces. We further demonstrate downstream interactive control, inverse design, and learning from real-world manipulation data, reducing the need for per-phenomenon solver engineering.
### Title:
          HoloMotion-1 Technical Report
 - **Authors:** Maiyue Chen, Kaihui Wang, Bo Zhang, Xihan Ma, Zhiyuan Yang, Yi Ren, Qijun Huang, Zihao Zhu, Yucheng Wang, Zhizhong Su
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this report, we present HoloMotion-1, a humanoid motion foundation model for zero-shot whole-body motion tracking. A key innovation of HoloMotion-1 is to scale control-policy training with a large-scale hybrid motion corpus, where video-reconstructed motions from in-the-wild videos provide the dominant source of motion diversity, while curated motion-capture and in-house motion data provide higher-fidelity supervision and deployment-oriented coverage. This data regime enables HoloMotion-1 to move beyond conventional MoCap-only training and exposes the policy to substantially broader behaviors, capture conditions, and motion styles. Learning from such heterogeneous data introduces new challenges, including reconstruction noise, source-domain mismatch, uneven motion quality, and the need for temporal modeling under large behavioral variation. To address these challenges, HoloMotion-1 integrates large-capacity temporal modeling, a sparsely activated Mixture-of-Experts Transformer with KV-cache inference for real-time control, and a sequence-level training strategy that improves learning efficiency on extended motion sequences. Extensive experiments on multiple unseen motion benchmarks show that HoloMotion-1 generalizes robustly across diverse motion types and capture conditions, significantly improves tracking accuracy over prior methods, and transfers directly to a real humanoid robot without task-specific fine-tuning.
### Title:
          PRB-RUPFormer: A Recursive Unified Probabilistic Transformer for Residual PRB Forecasting
 - **Authors:** Saad Masrur, Yuxuan Jiang, Matti Hiltunen, Ajay Rajkumar, Ismail Guvenc
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate forecasting of residual Physical Resource Blocks (PRBs) is critical for proactive network slice provisioning, energy-efficient operation, and spectrum-aware decision making in cellular systems, where residual PRBs serve as a practical proxy for short- and medium-term spectrum availability. Existing PRB prediction methods typically rely only on historical PRB values and are trained independently per carrier or sector, limiting their ability to capture cross-carrier dependencies and providing no measure of forecast uncertainty. Moreover, point forecasts alone are insufficient for robust spectrum-aware control under highly variable traffic conditions. This paper proposes PRB-RUPFormer, a recursive unified probabilistic Transformer for residual PRB forecasting. The proposed model jointly processes multivariate KPI time series using temporal, seasonal, and carrier-aware embeddings, preserving inter-metric temporal coupling during recursive rollout and stabilizing long-horizon forecasting. A single shared model is trained across all carriers and sectors of an eNB, enabling efficient learning of joint traffic dynamics with low computational overhead. Forecast uncertainty is captured through quantile-based prediction intervals, providing confidence-aware estimates of future PRB availability. Evaluations on six months of commercial LTE network data from multiple U.S. locations demonstrate median MAE below 0.05 and hit probabilities above 0.80 for both one-day and seven-day recursive forecasts. These probabilistic predictions directly support spectrum-aware RAN functions such as dynamic carrier activation, congestion avoidance, and proactive spectrum sharing, making the proposed framework well-suited for dynamic spectrum access scenarios.
### Title:
          Transformer Scalability Crisis: The First Comprehensive Empirical Analysis of Performance Walls in Modern Language Models
 - **Authors:** Mahdi Naser Moghadasi, Faezeh Ghaderi
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite the remarkable success of transformer architectures in natural language processing, their scalability limitations remain poorly understood through systematic empirical analysis. This paper presents the first comprehensive large-scale evaluation of 118 transformer models across seven distinct architectural categories, revealing fundamental performance walls that manifest as hard deployment constraints. Our systematic benchmarking methodology uncovers a critical scalability crisis: while 88.1% of models successfully process sequences up to 512 tokens, this drops dramatically to 44.9% at 1024 tokens, with complete failure (0%) at 2048 tokens. Through rigorous analysis of loading times, memory consumption, and computational efficiency across sequence lengths from 128 to 2048 tokens, we demonstrate that compressed models achieve superior parameter efficiency (649.2 tokens/sec/M parameters) compared to large generative models (12.5 tokens/sec/M). Our findings challenge prevailing scaling assumptions and provide the first quantitative evidence that the theoretical O(n2) attention complexity translates into measurable performance walls. This work establishes new benchmarking methodologies for transformer evaluation and provides critical insights for practical deployment decisions in production environments.
### Title:
          MR2-ByteTrack: CNN and Transformer-based Video Object Detection for AI-augmented Embedded Vision Sensor Nodes
 - **Authors:** Luca Bompani, Manuele Rusci, Luca Benini, Daniele Palossi, Francesco Conti
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern smart vision sensors need on-device intelligence to process video streams, as cloud computing is often impractical due to bandwidth, latency, and privacy constraints. However, these sensory systems typically rely on ultra-low-power microcontrollers (MCUs) with limited memory and compute, making conventional video object detection methods, which require feature storage or multi-frame buffering, unfeasible. To address this challenge, we introduce Multi-Resolution Rescored ByteTrack (MR2-ByteTrack), a Video Object Detection (VOD) method tailored for MCU-based embedded vision nodes. MR2-ByteTrack reduces computational cost by alternating between full- and low-resolution inference, while linking detections across frames via ByteTrack and correcting misclassifications through the Rescore algorithm, which applies probability union rules to aggregate detection confidence scores across frames. We apply our approach to both a CNN-based detector and a Transformer-based model, demonstrating its generality across architectures with fundamentally different spatial processing. Experiments on ImageNetVID demonstrate that MR2-ByteTrack maintains accuracy, achieving mAP scores of up to 49.0 for the CNN-based models and 48.7 for the Transformer, while reducing multiply-accumulate operations by as much as 53\% for the CNNs and 32\% for the Transformer. When deployed on GAP9, an ultra-low-power RISC-V multicore MCU, our method yields up to 55\% energy savings compared to processing only full-resolution images, enabling the first real-time Transformer-based VOD on an MCU-class embedded vision node. Code available at this https URL
### Title:
          Ghosted Layers: Unconstrained Activation Alignment for Recovering Layer-Pruned LLMs
 - **Authors:** Vincent-Daniel Yun, Junhyuk Jo, Sai Praneeth Karimireddy, Sunwoo Lee
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Performance (cs.PF)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Layer pruning removes entire Transformer decoder blocks from large language models, but introduces a mismatch between the hidden state received by the next surviving layer and the distribution it was trained to process, leading to significant performance degradation. We propose Ghosted Layers, a training-free recovery module that addresses this issue by solving a boundary activation alignment problem. Our method derives a closed-form optimal linear operator from a small calibration set to reconstruct the activation discrepancy introduced by the pruned layers. We show that this solution corresponds to the unconstrained optimum of the alignment objective, whereas existing methods are restricted to constrained solutions over limited operator subspaces. Experiments across multiple LLM backbones and pruning strategies demonstrate that our method consistently improves accuracy and perplexity over prior training-free baselines, while preserving the efficiency gains of layer pruning.
### Title:
          PrismQuant: Rate-Distortion-Optimal Vector Quantization for Gaussian-Mixture Sources
 - **Authors:** Bumsu Park, Chanho Park, Youngmok Park, Namyoon Lee
 - **Subjects:** Subjects:
Information Theory (cs.IT); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 For a Gaussian source under mean-squared error (MSE), classical transform coding is rate--distortion (RD) optimal: the Karhunen--Loeve transform (KLT) diagonalizes the covariance, reverse waterfilling allocates the bits, and scalar quantization closes the loop. This elegant story breaks down for multimodal sources, where no single covariance can capture heterogeneous local geometries, and the RD function loses its closed form. We revisit this problem through Gaussian-mixture sources and develop a constructive RD theory for them. Our key finding is that the mixture structure incurs only a component label cost. Conditioned on the active mixture component, each branch is Gaussian; the challenge is allocating bits across heterogeneous branches. We prove that the genie-aided conditional RD function is governed by a single global reverse-waterfilling level shared across all components and eigenmodes. Building on this result, we introduce PrismQuant, which transmits the component label losslessly and encodes the residual using the component-matched KLT, followed by scalar quantization, achieving a rate of H(C)/n bits per source dimension of the converse, with a vanishing asymptotic gap. We further develop a practical implementation based on EM-driven Gaussian-mixture learning, component-adaptive KLTs, and entropy-constrained scalar quantization (ECSQ). Experiments on synthetic Gaussian mixtures show that PrismQuant closely approaches the theoretical RD bound, while experiments on real-world channel-state-information (CSI) data demonstrate competitive or superior performance compared with transformer-based learned codecs at more than one order of magnitude smaller model size.
### Title:
          RoPE Distinguishes Neither Positions Nor Tokens in Long Contexts, Provably
 - **Authors:** Yufeng Du, Phillip Harris, Minyang Tian, Eliu A Huerta, Srikanth Ronanki, Subendhu Rongali, Aram Galstyan, Hao Peng
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We identify intrinsic limitations of Rotary Positional Embeddings (RoPE) in Transformer-based long-context language models. Our theoretical analysis abstracts away from the specific content of the context and depends only on its length. We prove that as context length increases, RoPE-based attention becomes unpredictable and loses two properties that are central to its effectiveness. First, it loses its locality bias: RoPE is no more likely to favor nearer positions than substantially farther ones. Second, it loses consistency in token relevance: a key vector that receives a higher attention score than an alternative at one position may receive a lower score at another. In both cases, the probability of failure approaches 0.5, no better than random guessing. We further prove that the attention score can remain unchanged when a key token is moved to a different position, or even replaced by a different token, indicating a failure to distinguish positions or tokens. Adjusting the RoPE base trades off distinguishing positions against distinguishing tokens but cannot preserve both at the same time. Increasing the RoPE base hyperparameter, a common practice in today's long-context models, helps distinguish different tokens, but inevitably sacrifices the ability to distinguish positions. Our empirical analysis shows that multi-head, multi-layer architectures are insufficient to overcome these limitations. Our findings suggest that fundamentally new mechanisms for encoding position and token order may be needed in future Transformer long-context language models.
### Title:
          Self-Prompting Diffusion Transformer for Open-Vocabulary Scene Text Editing via In-Context Learning
 - **Authors:** Hongxi Li, Tong Wang, Chengjing Wu, Tianbao Liu, Jiangtao Yao, Xiaochao Qu, Xinxiao Wu, Luoqi Liu, Ting Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scene text editing aims to modify text in a target region of an image while preserving surrounding background style and texture. Existing methods rely solely on image background information while neglecting the visual details of target regions, which discards stylistic features in the original text and essentially degrades the task to text rendering. Moreover, the conditions imposed by pre-trained glyph encoder limit the scope of editable text. To address these issues, this paper proposes a self-prompting scene text editing method that constructs style and glyph prompts directly from the original image, without introducing additional style or glyph encoders. We employ a two-stage training strategy: the diffusion transformer is first trained on large-scale self-supervised data and then refined using a small set of paired images. By leveraging the in-context learning capability of the Multi-Modal Diffusion Transformer (MM-DiT), it achieves open-vocabulary and style-consistent text editing. Experimental results on various languages demonstrate that our method achieves the state-of-the-art performance in both text accuracy and style consistency. Our project page: \href{this https URL}{this http URL}.
### Title:
          3DTMDet: A Dual-Path Synergy Network of Transformer and SSM for 3D Object Detection in Point Clouds
 - **Authors:** Bingwen Qiu, Yuan Liu, Junqi Bai, Tong Jiang, Ben Liang, Fangzhou Chen, Xiubao Sui, Qian Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A fundamental challenge in point cloud object detection lies in the conflict between the extreme sparsity of distant points and the need for remote context understanding. The existing methods typically use 1D serialization to expand the receptive field, which inevitably discards already scarce local geometric details and reduces detection of distant and small objects. To address this issue, we propose 3DTMDet, a novel detection network that synergistically combines state space models (Mamba) with Transformers. The core idea is to utilize SSM's linear complexity and advantages in long sequence modeling to effectively capture global interactions between sparse and distant points, while using Transformer modules with local attention to encode fine-grained geometric structures in local point sets, preserving accurate shape information. We propose the 3D Hybrid Mamba Transformer (3DHMT) block, which uses an SSM-Attention-SSM pipeline to balance global context understanding and local detail preservation, effectively alleviating the tension between receptive field enlargement and geometric preservation in remote detection. In addition, we introduced a voxel generation block inspired by LiDAR physics, which diffuses features along the sensor observation direction to reconstruct the complete object structure of occlusion and distant areas. Extensive experiments conducted on the KITTI and ONCE datasets have shown that 3DTMDet outperforms state-of-the-art detectors. The code is available at this https URL.
### Title:
          NavRL++: A System-Level Framework for Improving Sim-to-Real Transfer in Reinforcement Learning-Based Robot Navigation
 - **Authors:** Zhefan Xu, Hanyu Jin, Kenji Shimada
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent years have witnessed significant progress in autonomous navigation using reinforcement learning. However, existing approaches largely emphasize reinforcement learning framework design, such as input representations, action spaces, and reward functions, while providing limited analysis of sim-to-real transfer and insufficient insight into how training strategies affect real-world deployment performance. To bridge this gap, we not only introduce an effective RL framework but also present a complete training and deployment pipeline, along with a systematic empirical study that disentangles the key factors affecting sim-to-real transfer in reinforcement learning-based navigation, including sensor noise, perception failures, system latency, and control response. Building on insights from this analysis, we introduce perturbation-aware fine-tuning, a post-training adaptation strategy that improves transfer robustness by explicitly accounting for empirically identified domain discrepancies. To further mitigate perception degradation and enhance control smoothness in real-world deployment, we propose a Transformer-based temporal reasoning policy that leverages short-horizon observation for navigation control. We quantitatively evaluate how individual sim-to-real perturbations and training design choices impact navigation performance across environments. Experimental results demonstrate that the proposed training strategy and policy architecture outperform learning-based baselines in both static and dynamic environments, while achieving performance comparable to optimization-based planners in static settings. We validate our approach through real-world deployment on multiple robotic platforms, including aerial and legged robots, across navigation-centric tasks such as exploration and inspection, demonstrating zero-shot sim-to-real transfer.
### Title:
          GiLT: Augmenting Transformer Language Models with Dependency Graphs
 - **Authors:** Tianyu Huang, Yida Zhao, Chuyan Zhou, Kewei Tu
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Augmenting Transformers with linguistic structures effectively enhances the syntactic generalization performance of language models. Previous work in this direction focuses on syntactic tree structures of languages, in particular constituency tree structures. We propose Graph-Infused Layers Transformer Language Model (GiLT) which leverages dependency graphs for augmenting Transformer language models. Unlike most previous work, GiLT does not insert extra structural tokens in language modeling; instead, it injects structural information into language modeling by modulating attention weights in the Transformer with features extracted from the dependency graph that is incrementally constructed along with token prediction. In our experiments, GiLT with semantic dependency graphs achieves better syntactic generalization while maintaining competitive perplexity in comparison with Transformer language model baselines. In addition, GiLT can be finetuned from a pretrained language model to achieve improved downstream task performance. Our code is released at this https URL.
### Title:
          Response-Conditioned Parallel-to-Sequential Orchestration for Multi-Agent Systems
 - **Authors:** Nurbek Tastan, Alex Iacob, Lorenzo Sani, Meghdad Kurmanji, Nicholas D. Lane, Samuel Horvath, Karthik Nandakumar
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-agent systems can solve complex tasks through collaboration between multiple Large Language Model agents. Existing collaboration frameworks typically operate in either a parallel or a sequential mode. In the parallel mode, agents respond independently to queries followed by aggregation of responses. In contrast, sequential systems allow agents to communicate via a directed topology and refine one another step by step. However, both modes are inadequate for achieving the desired objectives of minimizing communication and latency while simultaneously maximizing the accuracy of the final response. In this work, we introduce a hybrid paradigm called Nexa, a trainable response-conditioned policy that bridges the gap between the two modes. Nexa begins with a parallel execution stage, embeds the resulting responses into a shared semantic space, and then predicts a sparse directed acyclic communication graph. If the graph is empty, the system remains purely parallel; if it is non-empty, the system performs one sequential message propagation. The policy is a lightweight transformer model, and the method avoids the need for external LLM judges or reward models, as well as hand-crafted test-time topology search. We formalize this hybrid execution problem, show that the resulting graph is acyclic by construction, and that the framework strictly subsumes pure parallel execution, and present a training procedure based on policy-gradient optimization. Results demonstrate that the response-conditioned policy learned by Nexa under one setting can be reused when the number of agents, the task, or the underlying agent changes, thus emphasizing the generalizability of the learned communication policy.
### Title:
          Gaussian Relational Graph Transformer
 - **Authors:** Zezhong Ding, Jin Li, Xugang Wang, Xike Xie
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Databases (cs.DB)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Relational graph learning models relational databases as graphs and has demonstrated superior performance on a wide range of relational predictive tasks. However, existing methods struggle to capture long-range dependencies due to information decay in their message-passing mechanisms, and recent relational graph transformers remain limited in jointly modeling structural, semantic, and temporal information. In this paper, we propose GelGT, a Gaussian relational graph transformer that explicitly addresses these challenges. GelGT introduces a structure-semantic collaborative sampling strategy to preserve structural connectivity while filtering irrelevant semantic information, and incorporates a Gaussian graph attention mechanism with a learnable Gaussian bias on the sampled subgraphs to dynamically encode temporal dependencies. Extensive experiments on various real-world datasets demonstrate that GelGT achieves state-of-the-art downstream task performance, with up to a 13.8% improvement in predictive performance.
### Title:
          Transformer-like Inference from Optimal Control
 - **Authors:** Aditya Kudre, Heng-Sheng Chang, Prashant G. Mehta
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Decoder-only transformers compute the conditional probability of the next token from a sequence of past observations. This paper derives, from first principles, inference architectures that solve the same prediction problem - and in doing so, recovers transformer-like layer operations as a consequence of optimal control theory. The framework is developed for two model classes: a nonlinear model of discrete-valued processes, directly motivated by the transformer, and a linear Gaussian model as a tractable baseline. For both model classes, the prediction objective is reformulated as an optimal control problem whose solution yields an explicit inference algorithm, the dual filter, with a layer structure that mirrors the layer structure of a decoder-only transformer. Numerical experiments provide a comparison of the optimal control to attention weights from a trained transformer. These experiments reveal that when the embedding dimension is insufficient, the transformer implicitly exploits non-Markovian structure.
### Title:
          Few-Shot Large Language Models for Actionable Triage Categorization of Online Patient Inquiries
 - **Authors:** Liqi Zhou, Jiafu Li
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG); Quantitative Methods (q-bio.QM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Online patient inquiries are often informal, incomplete, and written before professional assessment, yet they must still be routed to an appropriate level of clinical follow-up. We study this as a four-class actionable triage task -- self-care, schedule-visit, urgent-clinician-review, or emergency-referral, and ask whether prompted large language models (LLMs) can support such routing under low-resource labeling conditions. Using the public HealthCareMagic-100K corpus, we construct a 300-example human calibrated gold evaluation set, a 700-example auto-labeled silver training set, and a 40-example few-shot pool. We compare Term Frequency-Inverse Document Frequency (TF-IDF) and Bidirectional Encoder Representations from Transformers for Biomedical Text Mining (BioBERT) baselines train on silver labels against six prompted LLMs under 0-shot, 4-shot, and 12-shot conditions respectively. Accordingly, we evaluate with macro-$F_1$ alongside safety-aware metrics, including emergency-recall, under-triage rate, and severe under-triage rate. The strongest LLM (Claude Haiku 4.5, 12-shot) reaches macro-$F_1$ 0.475, exceeding the best supervised baseline (BioBERT, 0.378) on point estimate, with overlapping confidence intervals. Few-shot prompting and two-model agreement help in label-dependent ways: self-care agreement is reliable, urgent-clinician-review is not. We conclude that LLMs can support triage prioritization and selective human review, but not autonomous deployment.
### Title:
          ElasticDiT: Efficient Diffusion Transformers via Elastic Architecture and Sparse Attention for High-Resolution Image Generation on Mobile Devices
 - **Authors:** Kunpeng Du, Haizhen Xie, Sen Lu, Lei Yu, Binglei Bao, Huaao Tang, Chuntao Liu, Hao Wu, Yang Zhao, Zhicai Huang, Heyuan Gao, Zhijun Tu, Jie Hu, Xinghao Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Diffusion Transformer (DiT) architecture is the state-of-the-art paradigm for high-fidelity image generation, underpinning models like Stable Diffusion-3 and FLUX.1. However, deploying these models on resource-constrained mobile devices entails prohibitive computational and memory overhead. While efficiency-driven approaches like Linear-DiT and static pruning alleviate bottlenecks, they often incur quality degradation. Unlike cloud environments, mobile constraints require a single-model paradigm that dynamically balances fidelity and latency. We introduce ElasticDiT, which achieves this dynamic trade-off by adjusting spatial compression ratios and DiT block depths. By integrating Shift Sparse Block Attention (SSBA) and a Tiny DWT-Distilled VAE (T-DVAE), ElasticDiT reduces inference latency and memory footprint while maintaining image quality. Experiments confirm that ElasticDiT effectively covers a wide range of fidelity-latency trade-offs within a single set of parameters. By jointly adjusting compression and depth, a single ElasticDiT model can be reconfigured on-the-fly to outperform task-specific baselines. Specifically, our flex lite variant achieves an HPS of 32.87, surpassing the Flux model, while maintaining competitive quality at 84.16 percent average sparsity through SSBA. Furthermore, the plug-and-play T-DVAE provides SD3-level reconstruction with only 1/8x the computational cost of standard VAEs, and Flow-GRPO boosts semantic alignment (GenEval: 66.93 to 73.62). These results demonstrate that ElasticDiT offers a versatile, hardware-adaptive solution that eliminates the need for multiple specialized models, providing a promising path for future high-resolution image generation on mobile devices.
### Title:
          Going Beyond the Edge: Distributed Inference of Transformer Models on Ultra-Low-Power Wireless Devices
 - **Authors:** Alexander Gräfe, Ding Huo, Johannes Berger, Marco Zimmerling, Sebastian Trimpe
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer models are rapidly becoming a cornerstone of modern Internet of Things (IoT) applications, yet their computational and memory demands far exceed the capabilities of a single typical ultra-low-power IoT device. We present CATS, a framework for distributed transformer inference on ultra-low-power wireless devices, enabling multiple devices to collaboratively execute models far larger than what a single device can sustain. At its core, CATS is a communication-aware distributed transformer inference scheme co-designed across transformer partitioning, wireless communication and training. It employs SomeGather, a new pruned communication primitive that selectively broadcasts activation columns to reduce communication bandwidth and RAM usage without sacrificing model accuracy. Building on SomeGather, we design a partitioning method that exploits this primitive for efficient model parallelism. To cope with unreliable wireless communication, CATS employs message-dropout during training, which mimics packet losses and yields models that are robust to message loss during inference. In real-world experiments, we show that CATS brings distributed transformer inference to ultra-low-power wireless devices for the first time, with deployments on up to 16 devices that collaboratively execute transformer models up to 14 times larger than what a single device can run.
### Title:
          Grokking as Structural Inference: Transformers Need Bayesian Lottery Tickets
 - **Authors:** Kai Hidajat, Solden Stoll, Joseph An
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Why does a Transformer that has memorized its training set wait thousands of steps before it generalizes? Existing accounts locate this delay in norm minimization, feature emergence, or the late discovery of sparse subnetworks. These explanations capture important parts of the transition, but ignore a constraint unique to attention-based models: if attention discards an informative token, no bounded downstream computation can recover it. We formalize attention as an implicit Bayesian posterior over the task dependency graph and prove that generalization requires two separable conditions: a familiar Goldilocks bound on MLP capacity, coinciding with norm-based theories of grokking, and a novel Bayesian structural condition requiring attention to place sufficient mass on every informative token. This decoupling explains delayed generalization as delayed structural inference. Early in training, the MLP memorizes through unaligned features, drives the cross-entropy loss near zero, and thereby starves attention of structural gradient. Weight decay must then erode memorization before the missing graph becomes learnable, yielding the known inverse-weight-decay delay, which we derive as a structural waiting time. We then prove that this explaining-away delay can be bypassed by a KL-based structural intervention, yielding an inverse-intervention-strength scaling law for the grokking time. Experiments on algorithmic sequence tasks isolate structure from capacity and show that this Bayesian ticket matches or outperforms lottery-ticket transfer.
### Title:
          AOT-POT: Adaptive Operator Transformation for Large-Scale PDE Pre-training
 - **Authors:** Qitan Lv, Hong Wang, Zhongkai Hao, Wen Wu, Xuenan Xu, Bowen Zhou, Feng Wu, Chao Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pre-training neural operators on diverse partial differential equation (PDE) datasets has emerged as a promising direction for building general-purpose surrogate models in scientific machine learning. However, the inherent complexity and structural diversity of PDE solution operators make multi-PDE pre-training fundamentally challenging. Existing methods mainly address this by increasing model capacity, while leaving the target solution operators unchanged. Inspired by classical numerical analysis, we instead propose to transform complex and diverse solution operators into simpler, better-aligned forms that are easier to model jointly. Since the optimal transformation varies across PDE types, it must be adaptive and input-dependent, allowing a single neural operator to approximate an entire family of operators. We instantiate this idea as AOT-POT (adaptive operator-transformation for pre-training operator transformer), which expands hidden representations into multiple parallel streams, adaptively aggregates and redistributes them before and after each sub-layer, and mixes streams through Sinkhorn-projected doubly stochastic matrices for stable training. These mechanisms together reshape diverse solution operators into a unified form that can be effectively modeled by a single architecture. Empirically, AOT-POT achieves state-of-the-art performance on 12 PDE benchmarks with only 3\% additional parameters, reducing relative L2 error by up to 77.6\% (40.9\% on average). Fine-tuning AOT-POT further reduces L2 error by up to 92\% on in-domain PDEs and 89\% on out-of-domain PDEs (unseen types during pre-training), demonstrating that adaptive operator transformation is an effective and complementary direction for advancing PDE foundation models beyond simply scaling model capacity.
### Title:
          Not All Tasks Quantize Equally: Fisher-Guided Quantization for Visual Geometry Transformer
 - **Authors:** Yipu Zhang, Jintao Cheng, Weilun Feng, Jiehao Luo, Chuanguang Yang, Zhulin An, Yongjun Xu, Wei Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Feed-forward 3D reconstruction models, represented by Visual Geometry Grounded Transformer (VGGT), jointly predict multiple visual geometry tasks such as depth estimation, camera pose prediction, and point cloud reconstruction in a single forward pass. They have been widely adopted in 3D vision applications, but their billion-scale parameters bring substantial memory and computation overhead, posing challenges for on-device deployment. Post-Training Quantization (PTQ) is an effective technique to reduce this overhead. Existing PTQ methods for feed-forward 3D models mainly focus on handling heavy-tailed activation distributions and constructing diverse calibration datasets. However, we observe that feed-forward 3D models predict multiple geometric attributes through a shared backbone, where different transformer blocks and hidden channels contribute distinctly to each task, resulting in substantially different sensitivities to quantization errors across tasks, blocks, and channels. Consequently, treating all tasks equally over-emphasizes insensitive tasks and causes significant accuracy loss on the sensitive ones. To address this issue, we propose Fisher-Guided Quantization (FGQ) for feed-forward 3D reconstruction models. Specifically, FGQ uses the diagonal Fisher information matrix to quantify the different sensitivities across tasks, blocks, and channels, and incorporates these sensitivities into the Learnable Affine Transformation during calibration to better preserve the channels and blocks most critical to each task. Extensive experiments across camera pose estimation, point map reconstruction, and depth estimation show that FGQ consistently outperforms state-of-the-art quantization baselines on VGGT, achieving up to 39% relative improvement under the 4-bit quantization.
### Title:
          Agentic Discovery of Neural Architectures: AIRA-Compose and AIRA-Design
 - **Authors:** Alberto Pepe, Chien-Yu Lin, Despoina Magka, Bilge Acun, Yannan Nellie Wu, Anton Protopopov, Carole-Jean Wu, Yoram Bachrach
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Toward recursive self-improvement, we investigate LLM agents autonomously designing foundation models beyond standard Transformers. We introduce a dual-framework approach: AIRA-Compose for high-level architecture search, and AIRA-Design for low-level mechanistic implementation. AIRA-Compose uses 11 agents to explore fundamental computational primitives under a 24-hour budget. Agents evaluate million-parameter candidates, extrapolating top designs to 350M, 1B, and 3B scales. This yields 14 architectures across two families: AIRAformers (Transformer-based) and AIRAhybrids (Transformer-Mamba). Pre-trained at 1B scale, these consistently outperform Llama 3.2 and Composer-found baselines. On downstream tasks, AIRAformer-D and AIRAhybrid-D improve accuracy by 2.4% and 3.8% over Llama 3.2. Furthermore, AIRA-Compose finds models with highly efficient scaling frontiers: AIRAformer-C scales 54% and 71% faster than Llama 3.2 and Composer's best Transformer, while AIRAhybrid-C outscales Nemotron-2 by 23% and Composer's best hybrid by 37%. AIRA-Design tasks 20 agents with writing novel attention mechanisms for long-range dependencies and high-performing training scripts. On the Long Range Arena benchmark, agent-designed architectures reach within 2.3% and 2.6% of human state-of-the-art on document matching and text classification. On the Autoresearch benchmark, Greedy Opus 4.5 achieves 0.968 validation bits-per-byte under a fixed time budget, surpassing the published minimum. Together, these frameworks show AI agents can autonomously discover architectures and algorithmic optimizations matching or surpassing hand-designed baselines. This establishes a powerful paradigm for discovering next-generation foundation models, marking a clear step toward recursive self-improvement.
### Title:
          Linked Multi-Model Data on Russian Domestic and Foreign Policy Speeches
 - **Authors:** Daria Blinova, Gayathri Emuru, Rakesh Emuru, Kushagradheer Shridheer Srivastava, Mina Rulis, Sunita Chandrasekaran, Benjamin E. Bagozzi
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper introduces a dataset of interlinked multimodal political communications from the Russian government, addressing persistent deficiencies in the availability of social text- and image-based data for authoritarian politics contexts. The dataset comprises two large corpora of official speeches delivered by senior actors within the Kremlin and the Russian Ministry of Foreign Affairs over multiple decades. For each speech, we provide Russian- and English-language texts, associated images and captions where available, and harmonized metadata including (e.g.) dates, speakers, (geo)locations, and official government content tags. Unique identifiers link images to speeches and align Russian and English versions of the same communication texts. We further augment these linked datasets with validated topical annotations for both speech texts and speech images, which are generated via transformer-based multimodal topic modeling and refined by a Russian politics expert. The resulting data resources support multimodal, multilingual, temporal, and/or spatial analyses of (authoritarian) political communication and offer a valuable testbed for social science research and large language model (LLM) applications in political domains.
### Title:
          LoCO: Low-rank Compositional Rotation Fine-tuning
 - **Authors:** An Nguyen, Jaesik Choi, Anh Tong
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Parameter-efficient fine-tuning (PEFT) has emerged as an critical technique for adapting large-scale foundation models across natural language processing and computer vision. While existing methods such as low-rank adaptations achieve parameter efficiency via low-rank weight updates, they are limited in their ability to preserve the geometric structure of pretrained representations. We introduce Low-rank Compositional Orthogonal fine-tuning (LoCO), a novel PEFT method that constructs orthogonal transformations through low-rank skew-symmetric matrices and compositional rotation chains. We propose an approximation scheme that enables fully parallel computation of compositional rotations, making the approach practical for high-dimensional feature spaces. Our method maintains low computational complexity while maintaining orthogonality with controlled approximation error. We validate LoCO across diverse domains, including diffusion transformer fine-tuning, vision transformer adaptation, and language model adaptation. Our method demonstrates superior or competitive performance compared to both existing orthogonal and non-orthogonal methods.
### Title:
          A Retrieval-Enhanced Transformer for Multi-Step Port-of-Call Sequence Prediction in Global Liner Shipping
 - **Authors:** Yanzhao Su, Fang He, Yineng Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate multi-step port-of-call sequence prediction is vital for tactical resource orchestration and logistical efficiency. However, existing methods struggle with unreliable voyage schedules and the inability of AIS data to provide visibility beyond the immediate next port. To address this, this study proposes a Connectivity-Constrained and Retrieval-Enhanced (CCRE) deep learning framework. Inspired by Retrieval-Augmented Generation, CCRE introduces a retrieval-enhanced historical encoder that queries a global maritime database for contextually similar navigational precedents. Transforming these scenarios into candidate-level semantic representations compensates for data sparsity in long-tail routes and resolves routing ambiguities. Integrating this with a Transformer-based trajectory encoder, the architecture executes adaptive "middle fusion" via cross-attention. This dynamically shifts predictive reliance from real-time kinematics for short-term accuracy to historical context for long-term strategic stability. To ensure sequence-level coherence, forecasting is formulated as a joint sequence generation problem using an autoregressive Transformer decoder enriched with Scheduled Sampling and Gumbel-Softmax relaxation. This mitigates error accumulation, while topology masks strictly enforce maritime network reachability to eliminate operationally infeasible routes. Evaluated on a global dataset, CCRE achieves a 72.3% first-destination accuracy and a 61.4% average three-step accuracy, outperforming baselines like CatBoost and LSTM by average margins of 12.6% and 11.3%, respectively. Case studies further corroborate the model's scalability and ability to capture complex routing patterns across diverse international trade lanes.
### Title:
          Decomposed Vision-Language Alignment for Fine-Grained Open-Vocabulary Segmentation
 - **Authors:** Chenhao Wang, Yingrui Ji, Yu Meng, Yao Zhu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open-vocabulary segmentation models often struggle to generalize to unseen combinations of object categories and attributes, because fine-grained descriptions are typically encoded as holistic sentences that entangle multiple semantic units. We propose a Decomposed Vision-Language Alignment framework that explicitly factorizes textual prompts into a concept token and multiple attribute tokens, enabling separate cross-modal interactions for each semantic unit. At the feature level, we introduce a Feature-Gated Cross-Attention module that generates attribute-specific gating maps to fuse information in a multiplicative manner, effectively enforcing compositional semantics. At the scoring level, per-token similarities are aggregated in log-space, producing a stable and interpretable compositional matching. The method can be seamlessly integrated into existing transformer-based segmentation architectures and significantly improves generalization to unseen attribute-category compositions in fine-grained open-vocabulary segmentation benchmarks.
### Title:
          Learning Sim-Grounded Policies for Bimanual Rope Manipulation from Human Teleoperation Data
 - **Authors:** Gina Wigginghaus, Tim Missal, Berk Guler, Simon Manschitz, Jan Peters
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deformable Linear Objects (DLOs) such as ropes and cables are widely encountered in both household and industrial applications, yet remain challenging to manipulate due to their infinite-dimensional configuration space and frequent self-occlusion. Imitation learning from teleoperation offers a practical path to bimanual DLO manipulation, but its scalability is limited by human effort, making the choice of observation space critical for generalization from small datasets. In this study, we investigate whether the lack of generalization in egocentric visual policies for the knot-untangling task stems from the observation space itself, rather than from the policy architecture or data scale. We compare two Action Chunking with Transformers policies trained on the same bimanual teleoperation data: a vision-based policy conditioned on two egocentric RGB streams from wrist-mounted cameras, and a state-based policy conditioned on the DLO's 3D particle state, extracted from an initial observation via multi-view fusion and evolved in a particle-based eXtended Position-Based Dynamics simulation. Evaluated open-loop on an unseen rope configuration, the state-based policy outperforms its visual counterpart with a 30.8% reduction in L1 error when predicting the initial grasp-and-pull action, quantifying the observability gap between pixels and physics-consistent state, and pointing toward more data-efficient robot learning for the DLO manipulation task from limited human demonstrations.
### Title:
          Looped SSMs: Depth-Recurrence and Input Reshaping for Time Series Classification
 - **Authors:** Mónika Farsang, Ramin Hasani, Daniela Rus, Radu Grosu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 State Space Models (SSMs) are inherently recurrent along the sequence dimension, yet depth-recurrence - reusing the same block repeatedly across layers, as recently applied in looped transformers - has not been explored in this model family. We show that a looped SSM with $k$ parameters iterated $L$ times consistently closely matches or outperforms a standard SSM with $k \cdot L$ independent parameters across four architectures (LRU, S5, LinOSS, LrcSSM) and six time series classification benchmarks, despite operating within a strictly smaller hypothesis space, as we formally establish. Since the larger model contains the looped model as a special case, this dominance cannot be explained by expressivity and instead points to parameter sharing across depth as a beneficial inductive bias that simplifies optimization. These results demonstrate that depth-recurrence is orthogonal to sequence-recurrence and independently beneficial. We further show that input reshaping is an equally neglected design axis: concatenating timesteps for low-dimensional inputs, or flattening and rechunking the joint feature-time dimension for high-dimensional ones, yields accuracy gains of 1-6% across all models, confirmed over 5 random seeds. Both techniques provide standalone improvements that compound when combined, suggesting that depth and input reshaping are two independent and underexplored design axes for SSMs on time series.
### Title:
          ITGPT: Generative Pretraining on Irregular Timeseries
 - **Authors:** Antoine Honoré, Ming Xiao
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Timeseries regression models often struggle to leverage large volumes of labeled multimodal data, particularly when the data are irregularly sampled or contain missing values. This is common in domains like healthcare and predictive maintenance, where data are collected from unreliable sources, and labeling requires expert knowledge or costly equipments. Transformer-based large language models have proven effective on structured data such as text through self-supervised learning (SSL) and generative pretraining (GPT) frameworks. However, such models lack the flexibility to efficiently process irregularly sampled multimodal timeseries data. In this paper, we introduce ITGPT, an attention-based architecture designed for handling multimodal, irregularly sampled timeseries by allowing training with both SSL losses and GPT-like objectives. We evaluate its performance on a healthcare task with the TIHM dataset, and a predictive maintenance task with the CompX dataset. Our results demonstrate that ITGPT achieves state-of-the-art performance without requiring resampling, feature fusion or explicit data imputation. Furthermore, when labels are scarce, ITGPT effectively leverages unlabeled data through SSL and GPT training, outperforming the purely supervised approach. This represents an important step towards efficiently using large and unstructured timeseries datasets for practical inference tasks.
### Title:
          Towards Trustworthy and Explainable AI for Perception Models: From Concept to Prototype Vehicle Deployment
 - **Authors:** Till Beemelmanns, Shayan Sharifi, Manas Mehrotra, Ayushman Choudhuri, Lutz Eckstein
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep Neural Networks have become the dominant solution for Autonomous Driving perception, but their opacity conflicts with emerging Trustworthy AI guidelines and complicates safety assurance, debugging, and human oversight. While theoretical frameworks for safe and Explainable AI (XAI) exist, concrete implementations of Trustworthy AI for 3D scene understanding remain scarce. We address this gap by proposing a Trustworthy AI perception module that is remarkably robust, integrates faithful explainability, and calibrated uncertainty estimates. Building on a transformer-based detector, we derive explanation from the attention mechanism at inference time and validate their faithfulness using perturbation-based consistency tests. We further integrate an uncertainty estimation and calibration module, and apply robustness-enhancing training methods. Experiments show faithful saliency behavior, improved robustness, and well-calibrated uncertainty estimates. Finally, we deploy these Trustworthy AI elements in a prototype vehicle and provide an XAI Interface that visualizes documentation artifacts, model uncertainty state, and saliency maps, demonstrating the feasibility of trustworthy perception monitoring in real time. Supplementary materials are available at this https URL .
### Title:
          Attention Dispersion in Dynamic Graph Transformers: Diagnosis and a Transferable Fix
 - **Authors:** Jinhao Zhang, Kangfei Zhao, Qiuhao Zeng, Long-Kai Huang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based architectures have become the dominant paradigm for Continuous-Time Dynamic Graph (CTDG) learning, yet their performance remains limited on temporally shifted datasets. In this work, we identify attention dispersion as a shared failure mode of dynamic graph Transformers under temporal distribution shift. Through controlled ablation contrasting structurally and temporally distinguished historical neighbors against random ones, we show that prediction depends on a class of critical nodes that carry consistently more predictive signal than arbitrary neighbors. However, existing Transformers fail to focus on these nodes even when they are present in the input, as temporal shift weakens attention contrast and produces overly dispersed attention distributions. This diagnosis suggests a simple and transferable fix: replace standard attention with differential attention, which suppresses common-mode attention and amplifies distinctive token-level signals. When added to three representative CTDG Transformer baselines, differential attention consistently improves performance, with gains concentrated on high-shift datasets. Attention-level measurements further confirm the mechanism, showing reduced attention entropy and increased attention mass on critical nodes. Building on these findings, we introduce DiffDyG, a reference implementation combining differential attention with standard input encodings. Across 9 benchmarks and three negative sampling protocols, DiffDyG achieves SOTA performance, with especially large gains on the most shifted datasets.
### Title:
          Registers Matter for Pixel-Space Diffusion Transformers
 - **Authors:** Nikita Starodubcev, Ilia Sudakov, Ilya Drobyshevskiy, Artem Babenko, Dmitry Baranchuk
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformers (ViTs) are known to exhibit high-norm patch-token outliers that degrade feature map quality, a problem effectively mitigated by \textit{register tokens}. As diffusion models increasingly adopt transformer architectures and move toward pixel-space training, they become closer in form to ViTs, raising the question of whether register tokens are also useful for Diffusion Transformers (DiTs). In this work, we show that DiTs differ from ViTs in a key respect: they do not exhibit patch-token outliers. Interestingly, register tokens significantly improve convergence and generation quality of pixel-space DiTs. By analyzing intermediate representations, we find that register tokens produce cleaner feature maps at high noise levels, which may contribute to their effectiveness in pixel-space generation. We further observe that recent pixel-space DiT architectures implicitly incorporate register-like mechanisms, which may partially account for their strong empirical performance. Motivated by these insights, we investigate a parameter-efficient dual-stream architecture that specializes processing for register tokens and improves pixel-space generation quality with negligible runtime overhead.
### Title:
          Imitation learning for clinical decision support in pediatric ECMO
 - **Authors:** Fateme Golivand, Michael Skinner, Saurabh Mathur, Ameet Soni, Phillip Reeder, Kristian Kersting, Lakshmi Raman, Sriraam Natarajan
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pediatric critical care is a dynamic, high-stakes process involving constant monitoring and adjustments in life-saving treatments. Modeling these interventions is crucial for effective decision support. To address the challenges of high complexity and data scarcity in pediatric Extracorporeal Membrane Oxygenation (ECMO), we frame clinical decision-making as learning to act from trajectories, i.e., imitation learning that learns action models from observational data, with a key feature that actions are not directly observed. We consider TabPFN, a recent transformer-based approach for tabular data, and traditional baselines including XGBoost and Multi-Layer Perceptrons(MLPs) on real-world pediatric ECMO data to learn the action models. We find that the TabPFN-based approach consistently outperforms these classical baselines, supporting its use as a strong clinician-behavior baseline for pediatric ECMO decision support.
### Title:
          Layer Equivalence Is Not a Property of Layers Alone: How You Test Redundancy Changes What You Find
 - **Authors:** Gabriel Garcia
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 When researchers ask whether two transformer layers are "equivalent" for compression, they often conflate distinct tests. Replacement asks whether one layer's map can substitute for another's in place; interchange asks whether two layers approximately commute when their positions are swapped. Both are output-grounded swap-KL probes, but they need not agree: on pretrained transformers the protocol gap can change which layers look safe to prune by several-fold under the same evaluator, especially when replacement distances are high. We measure both protocols across checkpoints and architectures. On a Pythia training trajectory (410M and 1.4B), the replacement-interchange gap grows from initialization to convergence. Under one matched WikiText-2 contract at 8B scale, Qwen3-8B enters a divergent regime: interchange-guided removal is several-fold safer than replacement-guided at the same layer budgets, while Llama-3.1-8B ties the two protocols for pruning cost even though interchange KL is lower, showing metric gaps need not map one-to-one to removal. Before layer removal or merging, score both swap-KLs on the target checkpoint; the diagnostic requires only unlabeled forward passes.
### Title:
          A Generative AI Framework for Intelligent Utility Billing CO 2 Analytics and Sustainable Resource Optimisation
 - **Authors:** Pavan Manjunath, Thomas Pruefer
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Databases (cs.DB); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Distribution utilities are now expected to deliver bills that customers can actually read attach a defensible carbon number to every kWh sold and schedule load against grid stress and emissions constraints We propose an end-to-end framework that unifies four production-grade capabilities under one architectural roof a generative-AI agent that drafts each customers natural-language billing statement from structured numeric inputs under a constrained decoding policy a transformer-based forecaster that supplies the day-ahead consumption estimate with calibrated quantile bands
### Title:
          IVGT: Implicit Visual Geometry Transformer for Neural Scene Representation
 - **Authors:** Yuqi Wu, Tianyu Hu, Wenzhao Zheng, Yuanhui Huang, Haowen Sun, Jie Zhou, Jiwen Lu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reconstructing coherent 3D geometry and appearance from unposed multi-view images is a fundamental yet challenging problem in computer vision. Most existing visual geometry foundation models predict explicit geometry by regressing pixel-aligned pointmaps, often suffering from redundancy and limited geometric continuity. We propose IVGT, an Implicit Visual Geometry Transformer that implicitly models continuous and coherent geometry from pose-free multi-view images. This formulation learns a continuous neural scene representation in a canonical coordinate system and supports continuous spatial queries at any 3D positions, retrieving local features to predict signed distance (SDF) values and colors using lightweight decoders. It allows direct extraction of continuous and coherent surface geometry, enabling rendering of RGB images, depth maps, and surface normal maps from arbitrary viewpoints. We train IVGT via multi-dataset joint optimization with 2D supervision and 3D geometric regularization. IVGT demonstrates generalization across scenes and achieves strong performance on various tasks, including mesh and point cloud reconstruction, novel view synthesis, depth and surface normal estimation, and camera pose estimation.
## Keyword: autonomous driving
### Title:
          PCASim: Promptable Closed-loop Adversarial Simulation for Urban Traffic Environment
 - **Authors:** Chuancheng Zhang, Zhenhao Wang, Kaizheng Li, Yaran Lin, Qiang Guo, Bin Jiang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-world autonomous driving, particularly in urban environments with numerous corner cases, requires rigorous testing to ensure product safety and robustness. However, few studies have explored integrating adversarial scenario generation with the training of safety agents in closed-loop testing, enabling efficient co-evolution and mutual enhancement of both. To address this challenge, an adversarial behavior knowledge repository is constructed by applying rule-based filtering to an open-source dataset, combined with knowledge retrieval modules tailored for simulation environments. A large language model (LLM) is employed to integrate knowledge-, data-, and adversarial-driven approaches, generating safety-critical traffic scenarios customized to user needs. Additionally, while evaluating the generated scenarios, we employ reinforcement learning models to train the behaviors of different types of vehicles, thereby enriching scenario diversity beyond existing datasets while preserving realism. Experimental results demonstrate that the proposed framework improves the accuracy of domain-specific language generation by 12\%. Moreover, the success rate of newly generated scenario transformations increases by 8\%, while obstacle-avoidance capability is enhanced by 30\%. For the complete manuscript, please refer to: this https URL
### Title:
          Learning Context-conditioned Gaussian Overbounds for Convolution-Based Uncertainty Propagation
 - **Authors:** Ruirui Liu, Xuejie Hou, Yiping Jiang, Hui Ren
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Signal Processing (eess.SP); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Uncertainty quantification is essential in safety-critical settings--from autonomous driving to aviation, finance, and health--where decisions must rely on conservative bounds rather than point estimates. Predictor-level intervals (e.g., from quantile regression, conformal prediction, variance networks, or Bayesian models) generally do not compose: adding two per-variable intervals need not yield a valid interval for their sum or preserve coverage. In aviation, Gaussian overbounding replaces complex error distributions with a conservative Gaussian whose tails dominate the truth, so conservatism propagates through linear operations. Yet classical overbounds are global, often overly conservative, and hard to adapt to feature-conditioned errors. We propose a unified learning framework that trains neural networks to produce context-aware Gaussian overbounds--mean and scale--with provable conservatism on a finite quantile grid and, under three explicit regularity assumptions, continuous-tail conservatism on a certified interval. Our overbounding loss enforces conservativeness at selected quantiles while penalizing distributional distance with a Wasserstein-style term. The learned bounds support conservative linear-combination and convolution analysis on the enforced grid, and on the certified interval when assumptions hold, while being less redundant than traditional methods. We provide a scoped analysis of discrete-to-continuous conservatism and compact-domain objective regularity, and validate on synthetic data and real-world datasets, including multipath, ionospheric, and tropospheric residual errors. Across these settings, the method yields tighter bounds while maintaining conservatism on the enforced grid and in experiments. The framework is modality-agnostic and applicable to learning systems that require conservative, feature-conditioned uncertainty estimates in dynamic environments.
### Title:
          Towards Trustworthy and Explainable AI for Perception Models: From Concept to Prototype Vehicle Deployment
 - **Authors:** Till Beemelmanns, Shayan Sharifi, Manas Mehrotra, Ayushman Choudhuri, Lutz Eckstein
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep Neural Networks have become the dominant solution for Autonomous Driving perception, but their opacity conflicts with emerging Trustworthy AI guidelines and complicates safety assurance, debugging, and human oversight. While theoretical frameworks for safe and Explainable AI (XAI) exist, concrete implementations of Trustworthy AI for 3D scene understanding remain scarce. We address this gap by proposing a Trustworthy AI perception module that is remarkably robust, integrates faithful explainability, and calibrated uncertainty estimates. Building on a transformer-based detector, we derive explanation from the attention mechanism at inference time and validate their faithfulness using perturbation-based consistency tests. We further integrate an uncertainty estimation and calibration module, and apply robustness-enhancing training methods. Experiments show faithful saliency behavior, improved robustness, and well-calibrated uncertainty estimates. Finally, we deploy these Trustworthy AI elements in a prototype vehicle and provide an XAI Interface that visualizes documentation artifacts, model uncertainty state, and saliency maps, demonstrating the feasibility of trustworthy perception monitoring in real time. Supplementary materials are available at this https URL .
