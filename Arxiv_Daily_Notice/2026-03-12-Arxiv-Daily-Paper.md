# Showing new listings for Thursday, 12 March 2026
## Keyword: SLAM
### Title:
          Adaptive Manipulation Potential and Haptic Estimation for Tool-Mediated Interaction
 - **Authors:** Lin Yang, Anirvan Dutta, Yuan Ji, Yanxin Zhou, Shilin Shan, Lv Chen, Etienne Burdet, Domenico Campolo
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Achieving human-level dexterity in contact-rich, tool-mediated manipulation remains a significant challenge due to visual occlusion and the underdetermined nature of haptic sensing. This paper introduces a parameterized Equilibrium Manifold (EM) as a unified representation for tool-mediated interaction, and develops a closed-loop framework that integrates haptic estimation, online planning, and adaptive stiffness control. We establish a physical-geometric duality using an adaptive manipulation potential incorporating a differentiable contact model, which induces the manifold's geometric structure and ensures that complex physical interactions are encapsulated as continuous operations on the EM. Within this framework, we reformulate haptic estimation as a manifold parameter estimation problem. Specifically, a hybrid inference strategy (haptic SLAM) is employed in which discrete object shapes are classified via particle filtering, while the continuous object pose is estimated using analytical gradients for efficient optimization. By continuously updating the parameters of the manipulation potential, the framework dynamically reshapes the induced EM to guide online trajectory replanning and implement uncertainty-aware impedance control, thereby closing the perception-action loop. The system is validated through simulation and over 260 real-world screw-loosening trials. Experimental results demonstrate robust identification and manipulation success in standard scenarios while maintaining accurate tracking. Furthermore, ablation studies confirm that haptic SLAM and uncertainty-aware stiffness modulation outperform fixed impedance baselines, effectively preventing jamming during tight tolerance interactions.
### Title:
          Semantic Landmark Particle Filter for Robot Localisation in Vineyards
 - **Authors:** Rajitha de Silva, Jonathan Cox, James R. Heselden, Marija Popović, Cesar Cadena, Riccardo Polvara
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable localisation in vineyards is hindered by row-level perceptual aliasing: parallel crop rows produce nearly identical LiDAR observations, causing geometry-only and vision-based SLAM systems to converge towards incorrect corridors, particularly during headland transitions. We present a Semantic Landmark Particle Filter (SLPF) that integrates trunk and pole landmark detections with 2D LiDAR within a probabilistic localisation framework. Detected trunks are converted into semantic walls, forming structural row boundaries embedded in the measurement model to improve discrimination between adjacent rows. GNSS is incorporated as a lightweight prior that stabilises localisation when semantic observations are sparse. Field experiments in a 10-row vineyard demonstrate consistent improvements over geometry-only (AMCL), vision-based (RTAB-Map), and GNSS baselines. Compared to AMCL, SLPF reduces Absolute Pose Error by 22% and 65% across two traversal directions; relative to a NoisyGNSS baseline, APE decreases by 65% and 61%. Row correctness improves from 0.67 to 0.73, while mean cross-track error decreases from 1.40 m to 1.26 m. These results show that embedding row-level structural semantics within the measurement model enables robust localisation in highly repetitive outdoor agricultural environments.
## Keyword: odometry
### Title:
          Degeneracy-Resilient Teach and Repeat for Geometrically Challenging Environments Using FMCW Lidar
 - **Authors:** Katya M. Papais, Wenda Zhao, Timothy D. Barfoot
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Teach and Repeat (T&R) topometric navigation enables robots to autonomously repeat previously traversed paths without relying on GPS, making it well suited for operations in GPS-denied environments such as underground mines and lunar navigation. State-of-the-art T&R systems typically rely on iterative closest point (ICP)-based estimation; however, in geometrically degenerate environments with sparsely structured terrain, ICP often becomes ill-conditioned, resulting in degraded localization and unreliable navigation performance. To address this challenge, we present a degeneracy-resilient Frequency-Modulated Continuous-Wave (FMCW) lidar T&R navigation system consisting of Doppler velocity-based odometry and degeneracy-aware scan-to-map localization. Leveraging FMCW lidar, which provides per-point radial velocity measurements via the Doppler effect, we extend a geometry-independent, correspondence-free motion estimation to include principled pose uncertainty estimation that remains stable in degenerate environments. We further propose a degeneracy-aware localization method that incorporates per-point curvature for improved data association, and unifies translational and rotational scales to enable consistent degeneracy detection. Closed-loop field experiments across three environments with varying structural richness demonstrate that the proposed system reliably completes autonomous navigation, including in a challenging flat airport test field where a conventional ICP-based system fails.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Degeneracy-Resilient Teach and Repeat for Geometrically Challenging Environments Using FMCW Lidar
 - **Authors:** Katya M. Papais, Wenda Zhao, Timothy D. Barfoot
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Teach and Repeat (T&R) topometric navigation enables robots to autonomously repeat previously traversed paths without relying on GPS, making it well suited for operations in GPS-denied environments such as underground mines and lunar navigation. State-of-the-art T&R systems typically rely on iterative closest point (ICP)-based estimation; however, in geometrically degenerate environments with sparsely structured terrain, ICP often becomes ill-conditioned, resulting in degraded localization and unreliable navigation performance. To address this challenge, we present a degeneracy-resilient Frequency-Modulated Continuous-Wave (FMCW) lidar T&R navigation system consisting of Doppler velocity-based odometry and degeneracy-aware scan-to-map localization. Leveraging FMCW lidar, which provides per-point radial velocity measurements via the Doppler effect, we extend a geometry-independent, correspondence-free motion estimation to include principled pose uncertainty estimation that remains stable in degenerate environments. We further propose a degeneracy-aware localization method that incorporates per-point curvature for improved data association, and unifies translational and rotational scales to enable consistent degeneracy detection. Closed-loop field experiments across three environments with varying structural richness demonstrate that the proposed system reliably completes autonomous navigation, including in a challenging flat airport test field where a conventional ICP-based system fails.
### Title:
          CacheSolidarity: Preventing Prefix Caching Side Channels in Multi-tenant LLM Serving Systems
 - **Authors:** Panagiotis Georgios Pennas, Konstantinos Papaioannou, Marco Guarnieri, Thaleia Dimitra Doudali
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Distributed, Parallel, and Cluster Computing (cs.DC); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) rely on optimizations like Automatic Prefix Caching (APC) to accelerate inference. APC works by reusing previously computed states for the beginning part of a request (prefix), when another request starts with the same text. While APC improves throughput, it introduces timing side channels: cache hits are faster than misses, creating observable latency differences. In multi-tenant systems, attackers can exploit these differences to infer sensitive information, e.g., by incrementally reconstructing another user's request by observing hit/miss patterns. Current defenses take a sledgehammer approach: they disable APC and cache sharing, isolating users, and sacrificing efficiency for regular users. This paper presents CacheSolidarity, a system that secures multi-tenant LLM serving systems against APC side channels without sacrificing performance and efficiency. CacheSolidarity monitors cache reuse across users, flags suspicious sharing, and selectively isolates prefixes, restricting their reuse only when necessary. Evaluation shows that CacheSolidarity enables up to 70% higher cache reuse and 30% lower inference latency compared to existing defenses that isolate users. CacheSolidarity's lightweight design demonstrates how security in LLM serving does not have to come at the cost of unnecessarily reduced performance or unbearable overheads.
### Title:
          Semantic Landmark Particle Filter for Robot Localisation in Vineyards
 - **Authors:** Rajitha de Silva, Jonathan Cox, James R. Heselden, Marija Popović, Cesar Cadena, Riccardo Polvara
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable localisation in vineyards is hindered by row-level perceptual aliasing: parallel crop rows produce nearly identical LiDAR observations, causing geometry-only and vision-based SLAM systems to converge towards incorrect corridors, particularly during headland transitions. We present a Semantic Landmark Particle Filter (SLPF) that integrates trunk and pole landmark detections with 2D LiDAR within a probabilistic localisation framework. Detected trunks are converted into semantic walls, forming structural row boundaries embedded in the measurement model to improve discrimination between adjacent rows. GNSS is incorporated as a lightweight prior that stabilises localisation when semantic observations are sparse. Field experiments in a 10-row vineyard demonstrate consistent improvements over geometry-only (AMCL), vision-based (RTAB-Map), and GNSS baselines. Compared to AMCL, SLPF reduces Absolute Pose Error by 22% and 65% across two traversal directions; relative to a NoisyGNSS baseline, APE decreases by 65% and 61%. Row correctness improves from 0.67 to 0.73, while mean cross-track error decreases from 1.40 m to 1.26 m. These results show that embedding row-level structural semantics within the measurement model enables robust localisation in highly repetitive outdoor agricultural environments.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          The DMA Streaming Framework: Kernel-Level Buffer Orchestration for High-Performance AI Data Paths
 - **Authors:** Marco Graziano
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Artificial Intelligence (cs.AI); Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI transport libraries move bytes efficiently, but they commonly assume that buffers are already correctly allocated, placed, shared, registered, and safe under completion and teardown pressure. This paper presents dmaplane, a Linux kernel module that makes this missing layer explicit as buffer orchestration. dmaplane exposes a stable kernel UAPI via /dev/dmaplane and composes ring-based command channels, DMA buffer lifecycle management, dma-buf export for cross-device sharing, a kernel-space RDMA engine, NUMA-aware allocation and verification, credit-based flow control, low-overhead observability, and GPU memory integration via PCIe BAR pinning. We evaluate orchestration sensitivity with measurements of NUMA cross-node penalties at DRAM scale, completion-safe flow control under sustained RDMA load, and GPU BAR mapping tiers versus cudaMemcpy. We also demonstrate end-to-end disaggregated inference by transferring KV-cache chunks between two machines using RDMA WRITE WITH IMMEDIATE and reconstructing tensor views on the receiver. RDMA measurements use Soft-RoCE; we distinguish measured results from provider-independent properties by construction.
### Title:
          ViDia2Std: A Parallel Corpus and Methods for Low-Resource Vietnamese Dialect-to-Standard Translation
 - **Authors:** Khoa Anh Ta, Nguyen Van Dinh, Kiet Van Nguyen
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vietnamese exhibits extensive dialectal variation, posing challenges for NLP systems trained predominantly on standard Vietnamese. Such systems often underperform on dialectal inputs, especially from underrepresented Central and Southern regions. Previous work on dialect normalization has focused narrowly on Central-to-Northern dialect transfer using synthetic data and limited dialectal diversity. These efforts exclude Southern varieties and intra-regional variants within the North. We introduce ViDia2Std, the first manually annotated parallel corpus for dialect-to-standard Vietnamese translation covering all 63 provinces. Unlike prior datasets, ViDia2Std includes diverse dialects from Central, Southern, and non-standard Northern regions often absent from existing resources, making it the most dialectally inclusive corpus to date. The dataset consists of over 13,000 sentence pairs sourced from real-world Facebook comments and annotated by native speakers across all three dialect regions. To assess annotation consistency, we define a semantic mapping agreement metric that accounts for synonymous standard mappings across annotators. Based on this criterion, we report agreement rates of 86% (North), 82% (Central), and 85% (South). We benchmark several sequence-to-sequence models on ViDia2Std. mBART-large-50 achieves the best results (BLEU 0.8166, ROUGE-L 0.9384, METEOR 0.8925), while ViT5-base offers competitive performance with fewer parameters. ViDia2Std demonstrates that dialect normalization substantially improves downstream tasks, highlighting the need for dialect-aware resources in building robust Vietnamese NLP systems.
### Title:
          Data-Driven Integration Kernels for Interpretable Nonlocal Operator Learning
 - **Authors:** Savannah L. Ferretti, Jerry Lin, Sara Shamekh, Jane W. Baldwin, Michael S. Pritchard, Tom Beucler
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Atmospheric and Oceanic Physics (physics.ao-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Machine learning models can represent climate processes that are nonlocal in horizontal space, height, and time, often by combining information across these dimensions in highly nonlinear ways. While this can improve predictive skill, it makes learned relationships difficult to interpret and prone to overfitting as the extent of nonlocal information grows. We address this challenge by introducing data-driven integration kernels, a framework that adds structure to nonlocal operator learning by explicitly separating nonlocal information aggregation from local nonlinear prediction. Each spatiotemporal predictor field is first integrated using learnable kernels (defined as continuous weighting functions over horizontal space, height, and/or time), after which a local nonlinear mapping is applied only to the resulting kernel-integrated features and any optional local inputs. This design confines nonlinear interactions to a small set of integrated features and makes each kernel directly interpretable as a weighting pattern that reveals which horizontal locations, vertical levels, and past timesteps contribute most to the prediction. We demonstrate the framework for South Asian monsoon precipitation using a hierarchy of neural network models with increasing structure, including baseline, nonparametric kernel, and parametric kernel models. Across this hierarchy, kernel-based models achieve near-baseline performance with far fewer trainable parameters, showing that much of the relevant nonlocal information can be captured through a small set of interpretable integrations when appropriate structural constraints are imposed.
### Title:
          Towards Modeling Situational Awareness Through Visual Attention in Clinical Simulations
 - **Authors:** Haoting Gao, Kapotaksha Das, Mohamed Abouelenien, Michael Cole, James Cooke, Vitaliy Popov
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Situational awareness (SA) is essential for effective team performance in time-critical clinical environments, yet its dynamic and distributed nature remains difficult to characterize. In this preliminary study, we apply Transition Network Analysis (TNA) to model visual attention in multiperson VR-based cardiac arrest simulations. Using eye-tracking data from 40 clinicians assigned to four standardized roles (Airway, CPR, Defib, TeamLead), we construct gaze transition networks between clinically meaningful areas of interest (AOIs) and extract metrics such as entropy and self-loop rate to quantify attentional structure and flow. Our findings reveal that individual and team's visual attention is dynamically and adaptively redistributed across roles and scenario phases, with those in CPR roles narrowing their focus to execution-critical tasks and those in the TeamLead role concentrating on global monitoring as clinical demands evolve. TNA thus provides a powerful lens for mapping functional differentiation of team cognition and may support the development of phase-sensitive analytics and targeted instructional interventions in acute care training.
### Title:
          Beyond Scalars: Evaluating and Understanding LLM Reasoning via Geometric Progress and Stability
 - **Authors:** Xinyan Jiang, Ninghao Liu, Di Wang, Lijie Hu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Evaluating LLM reliability via scalar probabilities often fails to capture the structural dynamics of reasoning. We introduce TRACED, a framework that assesses reasoning quality through theoretically grounded geometric kinematics. By decomposing reasoning traces into Progress (displacement) and Stability (curvature), we reveal a distinct topological divergence: correct reasoning manifests as high-progress, stable trajectories, whereas hallucinations are characterized by low-progress, unstable patterns (stalled displacement with high curvature fluctuations). Leveraging these signatures, our probabilistic framework achieves competitive performance and superior robustness across diverse benchmarks. Crucially, TRACED bridges geometry and cognition by mapping high curvature to ''Hesitation Loops'' and displacement to ''Certainty Accumulation'', offering a physical lens to decode the internal dynamics of machine thought.
### Title:
          ScanDP: Generalizable 3D Scanning with Diffusion Policy
 - **Authors:** Itsuki Hirako, Ryo Hakoda, Yubin Liu, Matthew Hwang, Yoshihiro Sato, Takeshi Oishi
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning-based 3D Scanning plays a crucial role in enabling efficient and accurate scanning of target objects. However, recent reinforcement learning-based methods often require large-scale training data and still struggle to generalize to unseen object this http URL this work, we propose a data-efficient 3D scanning framework that uses Diffusion Policy to imitate human-like scanning strategies. To enhance robustness and generalization, we adopt the Occupancy Grid Mapping instead of direct point cloud processing, offering improved noise resilience and handling of diverse object geometries. We also introduce a hybrid approach combining a sphere-based space representation with a path optimization procedure that ensures path safety and scanning efficiency. This approach addresses limitations in conventional imitation learning, such as redundant or unpredictable behavior. We evaluate our method on diverse unseen objects in both shape and scale. Ours achieves higher coverage and shorter paths than baselines, while remaining robust to sensor noise. We further confirm practical feasibility and stable operation in real-world execution.
### Title:
          Automatic End-to-End Data Integration using Large Language Models
 - **Authors:** Aaron Steiner, Christian Bizer
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Designing data integration pipelines typically requires substantial manual effort from data engineers to configure pipeline components and label training data. While LLMs have shown promise in handling individual steps of the integration process, their potential to replace all human input across end-to-end data integration pipelines has not been investigated. As a step toward exploring this potential, we present an automatic data integration pipeline that uses GPT-5.2 to generate all artifacts required to adapt the pipeline to specific use cases. These artifacts are schema mappings, value mappings for data normalization, training data for entity matching, and validation data for selecting conflict resolution heuristics in data fusion. We compare the performance of this LLM-based pipeline to the performance of human-designed pipelines along three case studies requiring the integration of video game, music, and company related data. Our experiments show that the LLM-based pipeline is able to produce similar results, for some tasks even better results, as the human-designed pipelines. End-to-end, the human and the LLM pipelines produce integrated datasets of comparable size and density. Having the LLM configure the pipelines costs approximately \$10 per case study, which represents only a small fraction of the cost of having human data engineers perform the same tasks.
### Title:
          Riemannian Geometry-Preserving Variational Autoencoder for MI-BCI Data Augmentation
 - **Authors:** Viktorija Poļaka, Ivo Pascal de Jong, Andreea Ioana Sburlea
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper addresses the challenge of generating synthetic electroencephalogram (EEG) covariance matrices for motor imagery brain-computer interface (MI-BCI) applications. Objective: We aim to develop a generative model capable of producing high-fidelity synthetic covariance matrices while preserving their symmetric positive-definite nature. Approach: We propose a Riemannian geometry-preserving variational autoencoder (RGP-VAE) integrating geometric mappings with a composite loss function combining Riemannian distance, tangent space reconstruction accuracy and generative diversity. Results: The model generates valid, representative EEG covariance matrices, while learning a subject-invariant latent space. Synthetic data proves practically useful for MI-BCI, with its impact depending on the paired classifier. Contribution: This work introduces and validates the RGP-VAE as a geometry-preserving generative model for EEG covariance matrices, highlighting its potential for signal privacy, scalability and data augmentation.
### Title:
          Does LLM Alignment Really Need Diversity? An Empirical Study of Adapting RLVR Methods for Moral Reasoning
 - **Authors:** Zhaowei Zhang, Xiaohan Liu, Xuekai Zhu, Junchao Huang, Ceyao Zhang, Zhiyuan Feng, Yaodong Yang, Xiaoyuan Yi, Xing Xie
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reinforcement learning with verifiable rewards (RLVR) has achieved remarkable success in logical reasoning tasks, yet whether large language model (LLM) alignment requires fundamentally different approaches remains unclear. Given the apparent tolerance for multiple valid responses in moral reasoning, a natural hypothesis is that alignment tasks inherently require diversity-seeking distribution-matching algorithms rather than reward-maximizing policy-based methods. We conduct the first comprehensive empirical study comparing both paradigms on MoReBench. To enable stable RLVR training, we build a rubric-grounded reward pipeline by training a Qwen3-1.7B judge model. Contrary to our hypothesis, we find that distribution-matching approaches do not demonstrate significant advantages over reward-maximizing methods as expected on alignment tasks. Through semantic visualization mapping high-reward responses to semantic space, we demonstrate that moral reasoning exhibits more concentrated high-reward distributions than mathematical reasoning, where diverse solution strategies yield similarly high rewards. This counter-intuitive finding explains why mode-seeking optimization proves equally or more effective for alignment tasks. Our results suggest that alignment tasks do not inherently require diversity-preserving algorithms, and standard reward-maximizing RLVR methods can effectively transfer to moral reasoning without explicit diversity mechanisms.
### Title:
          Recover to Predict: Progressive Retrospective Learning for Variable-Length Trajectory Prediction
 - **Authors:** Hao Zhou, Lu Qi, Jason Li, Jie Zhang, Yi Liu, Xu Yang, Mingyu Fan, Fei Luo
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Trajectory prediction is critical for autonomous driving, enabling safe and efficient planning in dense, dynamic traffic. Most existing methods optimize prediction accuracy under fixed-length observations. However, real-world driving often yields variable-length, incomplete observations, posing a challenge to these methods. A common strategy is to directly map features from incomplete observations to those from complete ones. This one-shot mapping, however, struggles to learn accurate representations for short trajectories due to significant information gaps. To address this issue, we propose a Progressive Retrospective Framework (PRF), which gradually aligns features from incomplete observations with those from complete ones via a cascade of retrospective units. Each unit consists of a Retrospective Distillation Module (RDM) and a Retrospective Prediction Module (RPM), where RDM distills features and RPM recovers previous timesteps using the distilled features. Moreover, we propose a Rolling-Start Training Strategy (RSTS) that enhances data efficiency during PRF training. PRF is plug-and-play with existing methods. Extensive experiments on datasets Argoverse 2 and Argoverse 1 demonstrate the effectiveness of PRF. Code is available at this https URL.
### Title:
          EvoSchema: Towards Text-to-SQL Robustness Against Schema Evolution
 - **Authors:** Tianshu Zhang, Kun Qian, Siddhartha Sahai, Yuan Tian, Shaddy Garg, Huan Sun, Yunyao Li
 - **Subjects:** Subjects:
Databases (cs.DB); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural text-to-SQL models, which translate natural language questions (NLQs) into SQL queries given a database schema, have achieved remarkable performance. However, database schemas frequently evolve to meet new requirements. Such schema evolution often leads to performance degradation for models trained on static schemas. Existing work either mainly focuses on simply paraphrasing some syntactic or semantic mappings among NLQ, DB and SQL, or lacks a comprehensive and controllable way to investigate the model robustness issue under the schema evolution, which is insufficient when facing the increasingly complex and rich database schema changes in reality, especially in the LLM era. To address the challenges posed by schema evolution, we present EvoSchema, a comprehensive benchmark designed to assess and enhance the robustness of text-to-SQL systems under real-world schema changes. EvoSchema introduces a novel schema evolution taxonomy, encompassing ten perturbation types across columnlevel and table-level modifications, systematically simulating the dynamic nature of database schemas. Through EvoSchema, we conduct an in-depth evaluation spanning different open source and closed-source LLMs, revealing that table-level perturbations have a significantly greater impact on model performance compared to column-level changes. Furthermore, EvoSchema inspires the development of more resilient text-to-SQL systems, in terms of both model training and database design. The models trained on EvoSchema's diverse schema designs can force the model to distinguish the schema difference for the same questions to avoid learning spurious patterns, which demonstrate remarkable robustness compared to those trained on unperturbed data on average. This benchmark offers valuable insights into model behavior and a path forward for designing systems capable of thriving in dynamic, real-world environments.
### Title:
          CUPID: A Plug-in Framework for Joint Aleatoric and Epistemic Uncertainty Estimation with a Single Model
 - **Authors:** Xinran Xu, Xiuyi Fan
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate estimation of uncertainty in deep learning is critical for deploying models in high-stakes domains such as medical diagnosis and autonomous decision-making, where overconfident predictions can lead to harmful outcomes. In practice, understanding the reason behind a model's uncertainty and the type of uncertainty it represents can support risk-aware decisions, enhance user trust, and guide additional data collection. However, many existing methods only address a single type of uncertainty or require modifications and retraining of the base model, making them difficult to adopt in real-world systems. We introduce CUPID (Comprehensive Uncertainty Plug-in estImation moDel), a general-purpose module that jointly estimates aleatoric and epistemic uncertainty without modifying or retraining the base model. CUPID can be flexibly inserted into any layer of a pretrained network. It models aleatoric uncertainty through a learned Bayesian identity mapping and captures epistemic uncertainty by analyzing the model's internal responses to structured perturbations. We evaluate CUPID across a range of tasks, including classification, regression, and out-of-distribution detection. The results show that it consistently delivers competitive performance while offering layer-wise insights into the origins of uncertainty. By making uncertainty estimation modular, interpretable, and model-agnostic, CUPID supports more transparent and trustworthy AI. Related code and data are available at this https URL.
### Title:
          Interpretable Chinese Metaphor Identification via LLM-Assisted MIPVU Rule Script Generation: A Comparative Protocol Study
 - **Authors:** Weihang Huang, Mengna Liu
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Metaphor identification is a foundational task in figurative language processing, yet most computational approaches operate as opaque classifiers offering no insight into why an expression is judged metaphorical. This interpretability gap is especially acute for Chinese, where rich figurative traditions, absent morphological cues, and limited annotated resources compound the challenge. We present an LLM-assisted pipeline that operationalises four metaphor identification protocols--MIP/MIPVU lexical analysis, CMDAG conceptual-mapping annotation, emotion-based detection, and simile-oriented identification--as executable, human-auditable rule scripts. Each protocol is a modular chain of deterministic steps interleaved with controlled LLM calls, producing structured rationales alongside every classification decision. We evaluate on seven Chinese metaphor datasets spanning token-, sentence-, and span-level annotation, establishing the first cross-protocol comparison for Chinese metaphor identification. Within-protocol evaluation shows Protocol A (MIP) achieves an F1 of 0.472 on token-level identification, while cross-protocol analysis reveals striking divergence: pairwise Cohen's kappa between Protocols A and D is merely 0.001, whereas Protocols B and C exhibit near-perfect agreement (kappa = 0.986). An interpretability audit shows all protocols achieve 100% deterministic reproducibility, with rationale correctness from 0.40 to 0.87 and editability from 0.80 to 1.00. Error analysis identifies conceptual-domain mismatch and register sensitivity as dominant failure modes. Our results demonstrate that protocol choice is the single largest source of variation in metaphor identification, exceeding model-level variation, and that rule-script architectures achieve competitive performance while maintaining full transparency.
### Title:
          6ABOS: An Open-Source Atmospheric Correction Framework for the EnMAP Hyperspectral Mission Based on 6S
 - **Authors:** Gabriel Caballero Cañas, Bárbara Alvado Arranz, Xavier Sòria-Perpinyà, Antonio Ruiz-Verdú, Jesús Delegido, José Moreno
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Environmental Mapping and Analysis Program (EnMAP) mission has opened new frontiers in the monitoring of optically complex environments. However, the accurate retrieval of surface reflectance over water bodies remains a significant challenge, as the water-leaving signal typically accounts for only a small fraction of the total radiance, being easily obscured by atmospheric scattering and surface reflection effects. This paper introduces 6ABOS (6S-based Atmospheric Background Offset Subtraction), a novel open-source Python framework designed to automate the atmospheric correction (AC) of EnMAP hyperspectral imagery. By leveraging the Second Simulation of the Satellite Signal in the Solar Spectrum (6S) radiative transfer model, 6ABOS implements a physically-based inversion scheme that accounts for Rayleigh scattering, aerosol interactions, and gaseous absorption. The framework integrates automated EnMAP metadata parsing with dynamic atmospheric parameter retrieval via the Google Earth Engine (GEE) Application Programming Interface (API). Validation was conducted over two Mediterranean inland water reservoirs with contrasting trophic states: the oligotrophic Benag{'e}ber and the hypertrophic Bell{'u}s. Results demonstrate a high degree of spectral similarity between in situ measurements and EnMAP-derived water-leaving reflectances. The Spectral Angle Mapper (SAM) values remained consistently low (SAM $<$ 10$^\circ$) across both study sites. 6ABOS is distributed via conda-forge, providing the scientific community with a scalable, transparent, and reproducible open-science tool for advancing hyperspectral aquatic research in the cloud-computing era.
### Title:
          An Extreme Multi-label Text Classification (XMTC) Library Dataset: What if we took "Use of Practical AI in Digital Libraries" seriously?
 - **Authors:** Jennifer D'Souza, Sameer Sadruddin, Maximilian Kähler, Andrea Salfinger, Luca Zaccagna, Francesca Incitti, Lauro Snidaro, Osma Suominen
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Digital Libraries (cs.DL); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Subject indexing is vital for discovery but hard to sustain at scale and across languages. We release a large bilingual (English/German) corpus of catalog records annotated with the Integrated Authority File (GND), plus a machine-actionable GND taxonomy. The resource enables ontology-aware multi-label classification, mapping text to authority terms, and agent-assisted cataloging with reproducible, authority-grounded evaluation. We provide a brief statistical profile and qualitative error analyses of three systems. We invite the community to assess not only accuracy but usefulness and transparency, toward authority-anchored AI co-pilots that amplify catalogers' work.
### Title:
          A Hybrid Knowledge-Grounded Framework for Safety and Traceability in Prescription Verification
 - **Authors:** Yichi Zhu, Kan Ling, Xu Liu, Hengrun Zhang, Huiqun Yu, Guisheng Fan
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Medication errors pose a significant threat to patient safety, making pharmacist verification (PV) a critical, yet heavily burdened, final safeguard. The direct application of Large Language Models (LLMs) to this zero-tolerance domain is untenable due to their inherent factual unreliability, lack of traceability, and weakness in complex reasoning. To address these challenges, we introduce PharmGraph-Auditor, a novel system designed for safe and evidence-grounded prescription auditing. The core of our system is a trustworthy Hybrid Pharmaceutical Knowledge Base (HPKB), implemented under the Virtual Knowledge Graph (VKG) paradigm. This architecture strategically unifies a relational component for set constraint satisfaction and a graph component for topological reasoning via a rigorous mapping layer. To construct this HPKB, we propose the Iterative Schema Refinement (ISR) algorithm, a framework that enables the co-evolution of both graph and relational schemas from medical texts. For auditing, we introduce the KB-grounded Chain of Verification (CoV), a new reasoning paradigm that transforms the LLM from an unreliable generator into a transparent reasoning engine. CoV decomposes the audit task into a sequence of verifiable queries against the HPKB, generating hybrid query plans to retrieve evidence from the most appropriate data store. Experimental results demonstrate robust knowledge extraction capabilities and show promises of using PharmGraph-Auditor to enable pharmacists to achieve safer and faster prescription verification.
### Title:
          LLM2Vec-Gen: Generative Embeddings from Large Language Models
 - **Authors:** Parishad BehnamGhader, Vaibhav Adlakha, Fabian David Schmidt, Nicolas Chapados, Marius Mosbach, Siva Reddy
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLM-based text embedders typically encode the semantic content of their input. However, embedding tasks require mapping diverse inputs to similar outputs. Typically, this input-output is addressed by training embedding models with paired data using contrastive learning. In this work, we propose a novel self-supervised approach, LLM2Vec-Gen, which adopts a different paradigm: rather than encoding the input, we learn to represent the model's potential response. Specifically, we add trainable special tokens to the LLM's vocabulary, append them to input, and optimize them to represent the LLM's response in a fixed-length sequence. Training is guided by the LLM's own completion for the query, along with an unsupervised embedding teacher that provides distillation targets. This formulation helps to bridge the input-output gap and transfers LLM capabilities such as safety alignment and reasoning to embedding tasks. Crucially, the LLM backbone remains frozen and training requires only unlabeled queries. LLM2Vec-Gen achieves state-of-the-art self-supervised performance on the Massive Text Embedding Benchmark (MTEB), improving by 9.3% over the best unsupervised embedding teacher. We also observe up to 43.2% reduction in harmful content retrieval and 29.3% improvement in reasoning capabilities for embedding tasks. Finally, the learned embeddings are interpretable and can be decoded into text to reveal their semantic content.
## Keyword: localization
### Title:
          Tureis: Transformer-based Unified Resilience for IoT Devices in Smart Homes
 - **Authors:** Alireza Borhani, Vafa Andalibi, Bahar Asgari
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Smart-home IoT systems rely on heterogeneous sensor networks whose correctness shapes application behavior and the physical environment. However, these low-cost, resource-constrained sensors are highly prone to failure under real-world stressors. Prior methods often assume single-failure, single-resident settings, offer only failure detection rather than sensor-level localization, cover limited fault types and sensor modalities, require labels and human intervention, or impose overheads hindering edge deployment. To overcome these limitations, we propose Tureis, a self-supervised, context-aware method for failure detection and faulty-sensor localization in smart homes, designed for multi-failure, multi-resident edge settings. Tureis encodes heterogeneous binary and numeric sensor streams into compact bit-level features. It then trains a lightweight BERT-style Transformer with sensor-wise masked reconstruction over short-horizon windows, capturing spatial and short-term temporal correlations without mixing unrelated events. This self-supervised objective removes the need for labels or curated semantics. Then, at run-time, Tureis converts reconstruction residuals into sensor-level failure evidence and uses an iterative isolate-and-continue loop that masks flagged sensors, allowing other failures to surface and enabling resilient, fine-grained localization. Across five datasets with up to nine residents, Tureis improves single-failure localization F1 by +7.6%, +21.0%, and +25.0% over three strong baselines. In multi-failure scenarios with up to five faulty sensors, it further boosts localization F1 by +17.6% and +35.4% over two baselines, while the third does not extend to this setting. These gains come with minute-scale localization and an edge-friendly footprint, as a sub-megabyte model that processes each minute of data in a few milliseconds with ~0.5 GB peak memory on a Raspberry Pi 5.
### Title:
          Degeneracy-Resilient Teach and Repeat for Geometrically Challenging Environments Using FMCW Lidar
 - **Authors:** Katya M. Papais, Wenda Zhao, Timothy D. Barfoot
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Teach and Repeat (T&R) topometric navigation enables robots to autonomously repeat previously traversed paths without relying on GPS, making it well suited for operations in GPS-denied environments such as underground mines and lunar navigation. State-of-the-art T&R systems typically rely on iterative closest point (ICP)-based estimation; however, in geometrically degenerate environments with sparsely structured terrain, ICP often becomes ill-conditioned, resulting in degraded localization and unreliable navigation performance. To address this challenge, we present a degeneracy-resilient Frequency-Modulated Continuous-Wave (FMCW) lidar T&R navigation system consisting of Doppler velocity-based odometry and degeneracy-aware scan-to-map localization. Leveraging FMCW lidar, which provides per-point radial velocity measurements via the Doppler effect, we extend a geometry-independent, correspondence-free motion estimation to include principled pose uncertainty estimation that remains stable in degenerate environments. We further propose a degeneracy-aware localization method that incorporates per-point curvature for improved data association, and unifies translational and rotational scales to enable consistent degeneracy detection. Closed-loop field experiments across three environments with varying structural richness demonstrate that the proposed system reliably completes autonomous navigation, including in a challenging flat airport test field where a conventional ICP-based system fails.
### Title:
          A Robust Deep Learning Framework for Bangla License Plate Recognition Using YOLO and Vision-Language OCR
 - **Authors:** Nayeb Hasin, Md. Arafath Rahman Nishat, Mainul Islam, Khandakar Shakib Al Hasan, Asif Newaz
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 An Automatic License Plate Recognition (ALPR) system constitutes a crucial element in an intelligent traffic management system. However, the detection of Bangla license plates remains challenging because of the complicated character scheme and uneven layouts. This paper presents a robust Bangla License Plate Recognition system that integrates a deep learning-based object detection model for license plate localization with Optical Character Recognition for text extraction. Multiple object detection architectures, including U-Net and several YOLO (You Only Look Once) variants, are compared for license plate localization. This study proposes a novel two-stage adaptive training strategy built upon the YOLOv8 architecture to improve localization performance. The proposed approach outperforms the established models, achieving an accuracy of 97.83% and an Intersection over Union (IoU) of 91.3%. The text recognition problem is phrased as a sequence generation problem with a VisionEncoderDecoder architecture, with a combination of encoder-decoders evaluated. It was demonstrated that the ViT + BanglaBERT model gives better results at the character level, with a Character Error Rate of 0.1323 and Word Error Rate of 0.1068. The proposed system also shows a consistent performance when tested on an external dataset that has been curated for this study purpose. The dataset offers completely different environment and lighting conditions compared to the training sample, indicating the robustness of the proposed framework. Overall, our proposed system provides a robust and reliable solution for Bangla license plate recognition and performs effectively across diverse real-world scenarios, including variations in lighting, noise, and plate styles. These strengths make it well suited for deployment in intelligent transportation applications such as automated law enforcement and access control.
### Title:
          Learning to Wander: Improving the Global Image Geolocation Ability of LMMs via Actionable Reasoning
 - **Authors:** Yushuo Zheng, Huiyu Duan, Zicheng Zhang, Xiaohong Liu, Xiongkuo Min
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Geolocation, the task of identifying the geographic location of an image, requires abundant world knowledge and complex reasoning abilities. Though advanced large multimodal models (LMMs) have shown superior aforementioned capabilities, their performance on the geolocation task remains unexplored. To this end, we introduce \textbf{WanderBench}, the first open access global geolocation benchmark designed for actionable geolocation reasoning in embodied scenarios. WanderBench contains over 32K panoramas across six continents, organized as navigable graphs that enable physical actions such as rotation and movement, transforming geolocation from static recognition into interactive exploration. Building on this foundation, we propose \textbf{GeoAoT} (Action of Thought), a \underline{Geo}location framework with \underline{A}ction of \underline{T}hough, which couples reasoning with embodied actions. Instead of generating textual reasoning chains, GeoAoT produces actionable plans such as, approaching landmarks or adjusting viewpoints, to actively reduce uncertainty. We further establish an evaluation protocol that jointly measures geolocation accuracy and difficulty-aware geolocation questioning ability. Experiments on 19 large multimodal models show that GeoAoT achieves superior fine-grained localization and stronger generalization in dynamic environments. WanderBench and GeoAoT define a new paradigm for actionable, reasoning driven geolocation in embodied visual understanding.
### Title:
          UAV-MARL: Multi-Agent Reinforcement Learning for Time-Critical and Dynamic Medical Supply Delivery
 - **Authors:** Islam Guven, Mehmet Parlak
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unmanned aerial vehicles (UAVs) are increasingly used to support time-critical medical supply delivery, providing rapid and flexible logistics during emergencies and resource shortages. However, effective deployment of UAV fleets requires coordination mechanisms capable of prioritizing medical requests, allocating limited aerial resources, and adapting delivery schedules under uncertain operational conditions. This paper presents a multi-agent reinforcement learning (MARL) framework for coordinating UAV fleets in stochastic medical delivery scenarios where requests vary in urgency, location, and delivery deadlines. The problem is formulated as a partially observable Markov decision process (POMDP) in which UAV agents maintain awareness of medical delivery demands while having limited visibility of other agents due to communication and localization constraints. The proposed framework employs Proximal Policy Optimization (PPO) as the primary learning algorithm and evaluates several variants, including asynchronous extensions, classical actor--critic methods, and architectural modifications to analyze scalability and performance trade-offs. The model is evaluated using real-world geographic data from selected clinics and hospitals extracted from the OpenStreetMap dataset. The framework provides a decision-support layer that prioritizes medical tasks, reallocates UAV resources in real time, and assists healthcare personnel in managing urgent logistics. Experimental results show that classical PPO achieves superior coordination performance compared to asynchronous and sequential learning strategies, highlighting the potential of reinforcement learning for adaptive and scalable UAV-assisted healthcare logistics.
### Title:
          Prompting with the human-touch: evaluating model-sensitivity of foundation models for musculoskeletal CT segmentation
 - **Authors:** Caroline Magg, Maaike A. ter Wee, Johannes G.G. Dobbe, Geert J. Streekstra, Leendert Blankevoort, Clara I. Sánchez, Hoel Kervadec
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Promptable Foundation Models (FMs), initially introduced for natural image segmentation, have also revolutionized medical image segmentation. The increasing number of models, along with evaluations varying in datasets, metrics, and compared models, makes direct performance comparison between models difficult and complicates the selection of the most suitable model for specific clinical tasks. In our study, 11 promptable FMs are tested using non-iterative 2D and 3D prompting strategies on a private and public dataset focusing on bone and implant segmentation in four anatomical regions (wrist, shoulder, hip and lower leg). The Pareto-optimal models are identified and further analyzed using human prompts collected through a dedicated observer study. Our findings are: 1) The segmentation performance varies a lot between FMs and prompting strategies; 2) The Pareto-optimal models in 2D are SAM and SAM2.1, in 3D nnInteractive and Med-SAM2; 3) Localization accuracy and rater consistency vary with anatomical structures, with higher consistency for simple structures (wrist bones) and lower consistency for complex structures (pelvis, tibia, implants); 4) The segmentation performance drops using human prompts, suggesting that performance reported on "ideal" prompts extracted from reference labels might overestimate the performance in a human-driven setting; 5) All models were sensitive to prompt variations. While two models demonstrated intra-rater robustness, it did not scale to inter-rater settings. We conclude that the selection of the most optimal FM for a human-driven setting remains challenging, with even high-performing FMs being sensitive to variations in human input prompts. Our code base for prompt extraction and model inference is available: this https URL
### Title:
          Towards Cognitive Defect Analysis in Active Infrared Thermography with Vision-Text Cues
 - **Authors:** Mohammed Salah, Eman Ouda, Giuseppe Dell'Avvocato, Fabrizio Sarasini, Ester D'Accardi, Jorge Dias, Davor Svetinovic, Stefano Sfarra, Yusra Abdulrahman
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Active infrared thermography (AIRT) is currently witnessing a surge of artificial intelligence (AI) methodologies being deployed for automated subsurface defect analysis of high performance carbon fiber-reinforced polymers (CFRP). Deploying AI-based AIRT methodologies for inspecting CFRPs requires the creation of time consuming and expensive datasets of CFRP inspection sequences to train neural networks. To address this challenge, this work introduces a novel language-guided framework for cognitive defect analysis in CFRPs using AIRT and vision-language models (VLMs). Unlike conventional learning-based approaches, the proposed framework does not require developing training datasets for extensive training of defect detectors, instead it relies solely on pretrained multimodal VLM encoders coupled with a lightweight adapter to enable generative zero-shot understanding and localization of subsurface defects. By leveraging pretrained multimodal encoders, the proposed system enables generative zero-shot understanding of thermographic patterns and automatic detection of subsurface defects. Given the domain gap between thermographic data and natural images used to train VLMs, an AIRT-VLM Adapter is proposed to enhance the visibility of defects while aligning the thermographic domain with the learned representations of VLMs. The proposed framework is validated using three representative VLMs; specifically, GroundingDINO, Qwen-VL-Chat, and CogVLM. Validation is performed on 25 CFRP inspection sequences with impacts introduced at different energy levels, reflecting realistic defects encountered in industrial scenarios. Experimental results demonstrate that the AIRT-VLM adapter achieves signal-to-noise ratio (SNR) gains exceeding 10 dB compared with conventional thermographic dimensionality-reduction methods, while enabling zero-shot defect detection with intersection-over-union values reaching 70%.
### Title:
          TacLoc: Global Tactile Localization on Objects from a Registration Perspective
 - **Authors:** Zirui Zhang, Boyang Zhang, Fumin Zhang, Huan Yin
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pose estimation is essential for robotic manipulation, particularly when visual perception is occluded during gripper-object interactions. Existing tactile-based methods generally rely on tactile simulation or pre-trained models, which limits their generalizability and efficiency. In this study, we propose TacLoc, a novel tactile localization framework that formulates the problem as a one-shot point cloud registration task. TacLoc introduces a graph-theoretic partial-to-full registration method, leveraging dense point clouds and surface normals from tactile sensing for efficient and accurate pose estimation. Without requiring rendered data or pre-trained models, TacLoc achieves improved performance through normal-guided graph pruning and a hypothesis-and-verification pipeline. TacLoc is evaluated extensively on the YCB dataset. We further demonstrate TacLoc on real-world objects across two different visual-tactile sensors.
### Title:
          Learning Bimanual Cloth Manipulation with Vision-based Tactile Sensing via Single Robotic Arm
 - **Authors:** Dongmyoung Lee, Wei Chen, Xiaoshuai Chen, Rui Zong, Petar Kormushev
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robotic cloth manipulation remains challenging due to the high-dimensional state space of fabrics, their deformable nature, and frequent occlusions that limit vision-based sensing. Although dual-arm systems can mitigate some of these issues, they increase hardware and control complexity. This paper presents Touch G.O.G., a compact vision-based tactile gripper and perception/control framework for single-arm bimanual cloth manipulation. The proposed framework combines three key components: (1) a novel gripper design and control strategy for in-gripper cloth sliding with a single robot arm, (2) a Vision Foundation Model-backboned Vision Transformer pipeline for cloth part classification (PC-Net) and edge pose estimation (PE-Net) using real and synthetic tactile images, and (3) an encoder-decoder synthetic data generator (SD-Net) that reduces manual annotation by producing high-fidelity tactile images. Experiments show 96% accuracy in distinguishing edges, corners, interior regions, and grasp failures, together with sub-millimeter edge localization and 4.5° orientation error. Real-world results demonstrate reliable cloth unfolding, even for crumpled fabrics, using only a single robotic arm. These results highlight Touch G.O.G. as a compact and cost-effective solution for deformable object manipulation.
### Title:
          HanMoVLM: Large Vision-Language Models for Professional Artistic Painting Evaluation
 - **Authors:** Hongji Yang, Yucheng Zhou, Wencheng Han, Songlian Li, Xiaotong Zhao, Jianbing Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Large Vision-Language Models (VLMs) demonstrate impressive general visual capabilities, they remain artistically blind and unable to offer professional evaluation of artworks within specific artistic domains like human experts. To bridge this gap, we transform VLMs into experts capable of professional-grade painting evaluation in the Chinese Artistic Domain, which is more abstract and demands extensive artistic training for evaluation. We introduce HanMo-Bench, a new dataset that features authentic auction-grade masterpieces and AI-generated works, grounded in real-world market valuations. To realize the rigorous judgment, we propose the HanMoVLM and construct a Chain-of-Thought (CoT) validated by experts. This CoT guides the model to perform expert-level reasoning: from content identification and Region of Interest (RoI) localization to professional evaluation, guided by both theme-specific evaluation and typical three-tier evaluation in Chinese paintings. Furthermore, we design a reward function to refine the reasoning process of the HanMoVLM to improve the accuracy. We demonstrate that HanMoVLM can serve as a critical backbone for Test-time Scaling in image generation. By acting as a high-quality verifier, HanMoVLM enables generative models to select the most artistically superior outputs from multiple candidates. Experimental results and human studies confirm that the proposed HanMoVLM effectively bridges the gap, achieving a high consistency with professional experts and significantly improving the quality of Chinese Painting generation.
### Title:
          Evaluating Few-Shot Pill Recognition Under Visual Domain Shift
 - **Authors:** W. I. Chu, G. Tarroni, L. Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adverse drug events are a significant source of preventable harm, which has led to the development of automated pill recognition systems to enhance medication safety. Real-world deployment of these systems is hindered by visually complex conditions, including cluttered scenes, overlapping pills, reflections, and diverse acquisition environments. This study investigates few-shot pill recognition from a deployment-oriented perspective, prioritizing generalization under realistic cross-dataset domain shifts over architectural innovation. A two-stage object detection framework is employed, involving base training followed by few-shot fine-tuning. Models are adapted to novel pill classes using one, five, or ten labeled examples per class and are evaluated on a separate deployment dataset featuring multi-object, cluttered scenes. The evaluation focuses on classification-centric and error-based metrics to address heterogeneous annotation strategies. Findings indicate that semantic pill recognition adapts rapidly with few-shot supervision, with classification performance reaching saturation even with a single labeled example. However, stress testing under overlapping and occluded conditions demonstrates a marked decline in localization and recall, despite robust semantic classification. Models trained on visually realistic, multi-pill data consistently exhibit greater robustness in low-shot scenarios, underscoring the importance of training data realism and the diagnostic utility of few-shot fine-tuning for deployment readiness.
### Title:
          UltrasoundAgents: Hierarchical Multi-Agent Evidence-Chain Reasoning for Breast Ultrasound Diagnosis
 - **Authors:** Yali Zhu, Kang Zhou, Dingbang Wu, Gaofeng Meng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Breast ultrasound diagnosis typically proceeds from global lesion localization to local sign assessment and then evidence integration to assign a BI-RADS category and determine benignity or malignancy. Many existing methods rely on end-to-end prediction or provide only weakly grounded evidence, which can miss fine-grained lesion cues and limit auditability and clinical review. To align with the clinical workflow and improve evidence traceability, we propose a hierarchical multi-agent framework, termed UltrasoundAgents. A main agent localizes the lesion in the full image and triggers a crop-and-zoom operation. A sub-agent analyzes the local view and predicts four clinically relevant attributes, namely echogenicity pattern, calcification, boundary type, and edge (margin) morphology. The main agent then integrates these structured attributes to perform evidence-based reasoning and output the BI-RADS category and the malignancy prediction, while producing reviewable intermediate evidence. Furthermore, hierarchical multi-agent training often suffers from error propagation, difficult credit assignment, and sparse rewards. To alleviate this and improve training stability, we introduce a decoupled progressive training strategy. We first train the attribute agent, then train the main agent with oracle attributes to learn robust attribute-based reasoning, and finally apply corrective trajectory self-distillation with spatial supervision to build high-quality trajectories for supervised fine-tuning, yielding a deployable end-to-end policy. Experiments show consistent gains over strong vision-language baselines in diagnostic accuracy and attribute agreement, together with structured evidence and traceable reasoning.
### Title:
          GroundCount: Grounding Vision-Language Models with Object Detection for Mitigating Counting Hallucinations
 - **Authors:** Boyuan Chen, Minghao Shao, Siddharth Garg, Ramesh Karri, Muhammad Shafique
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Language Models (VLMs) exhibit persistent hallucinations in counting tasks, with accuracy substantially lower than other visual reasoning tasks (excluding sentiment). This phenomenon persists even in state-of-the-art reasoning-capable VLMs. Conversely, CNN-based object detection models (ODMs) such as YOLO excel at spatial localization and instance counting with minimal computational overhead. We propose GroundCount, a framework that augments VLMs with explicit spatial grounding from ODMs to mitigate counting hallucinations. In the best case, our prompt-based augmentation strategy achieves 81.3% counting accuracy on the best-performing model (Ovis2.5-2B) - a 6.6pp improvement - while reducing inference time by 22% through elimination of hallucination-driven reasoning loops for stronger models. We conduct comprehensive ablation studies demonstrating that positional encoding is a critical component, being beneficial for stronger models but detrimental for weaker ones. Confidence scores, by contrast, introduce noise for most architectures and their removal improves performance in four of five evaluated models. We further evaluate feature-level fusion architectures, finding that explicit symbolic grounding via structured prompts outperforms implicit feature fusion despite sophisticated cross-attention mechanisms. Our approach yields consistent improvements across four of five evaluated VLM architectures (6.2--7.5pp), with one architecture exhibiting degraded performance due to incompatibility between its iterative reflection mechanisms and structured prompts. These results suggest that counting failures stem from fundamental spatial-semantic integration limitations rather than architecture-specific deficiencies, while highlighting the importance of architectural compatibility in augmentation strategies.
### Title:
          Neural Field Thermal Tomography: A Differentiable Physics Framework for Non-Destructive Evaluation
 - **Authors:** Tao Zhong, Yixun Hu, Dongzhe Zheng, Aditya Sood, Christine Allen-Blanchette
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Materials Science (cond-mat.mtrl-sci); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Instrumentation and Detectors (physics.ins-det)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose Neural Field Thermal Tomography (NeFTY), a differentiable physics framework for the quantitative 3D reconstruction of material properties from transient surface temperature measurements. While traditional thermography relies on pixel-wise 1D approximations that neglect lateral diffusion, and soft-constrained Physics-Informed Neural Networks (PINNs) often fail in transient diffusion scenarios due to gradient stiffness, NeFTY parameterizes the 3D diffusivity field as a continuous neural field optimized through a rigorous numerical solver. By leveraging a differentiable physics solver, our approach enforces thermodynamic laws as hard constraints while maintaining the memory efficiency required for high-resolution 3D tomography. Our discretize-then-optimize paradigm effectively mitigates the spectral bias and ill-posedness inherent in inverse heat conduction, enabling the recovery of subsurface defects at arbitrary scales. Experimental validation on synthetic data demonstrates that NeFTY significantly improves the accuracy of subsurface defect localization over baselines. Additional details at this https URL
## Keyword: transformer
### Title:
          AraModernBERT: Transtokenized Initialization and Long-Context Encoder Modeling for Arabic
 - **Authors:** Omar Elshehy, Omer Nacar, Abdelbasset Djamai, Muhammed Ragab, Khloud Al Jallad, Mona Abdelazim
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Encoder-only transformer models remain widely used for discriminative NLP tasks, yet recent architectural advances have largely focused on English. In this work, we present AraModernBERT, an adaptation of the ModernBERT encoder architecture to Arabic, and study the impact of transtokenized embedding initialization and native long-context modeling up to 8,192 tokens. We show that transtokenization is essential for Arabic language modeling, yielding dramatic improvements in masked language modeling performance compared to non-transtokenized initialization. We further demonstrate that AraModernBERT supports stable and effective long-context modeling, achieving improved intrinsic language modeling performance at extended sequence lengths. Downstream evaluations on Arabic natural language understanding tasks, including inference, offensive language detection, question-question similarity, and named entity recognition, confirm strong transfer to discriminative and sequence labeling settings. Our results highlight practical considerations for adapting modern encoder architectures to Arabic and other languages written in Arabic-derived scripts.
### Title:
          PoultryLeX-Net: Domain-Adaptive Dual-Stream Transformer Architecture for Large-Scale Poultry Stakeholder Modeling
 - **Authors:** Stephen Afrifa, Biswash Khatiwada, Kapalik Khanal, Sanjay Shah, Lingjuan Wang-Li, Ramesh Bahadur Bist
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid growth of the global poultry industry, driven by rising demand for affordable animal protein, has intensified public discourse surrounding production practices, housing, management, animal welfare, and supply-chain transparency. Social media platforms such as X (formerly Twitter) generate large volumes of unstructured textual data that capture stakeholder sentiment across the poultry industry. Extracting accurate sentiment signals from this domain-specific discourse remains challenging due to contextual ambiguity, linguistic variability, and limited domain awareness in general-purpose language models. This study presents PoultryLeX-Net, a lexicon-enhanced, domain-adaptive dual-stream transformer framework for fine-grained sentiment analysis in poultry-related text. The proposed architecture integrates sentiment classification, topic modeling, and contextual representation learning through domain-specific embeddings and gated cross-attention mechanisms. A lexicon-guided stream captures poultry-specific terminology and sentiment cues, while contextual stream models long-range semantic dependencies. Latent Dirichlet Allocation is employed to identify dominant thematic structures associated with production management and welfare-related discussions, providing complementary interpretability to sentiment predictions. PoultryLeX-Net was evaluated against multiple baseline models, including convolutional neural network and pre-trained transformer architectures such as DistilBERT and RoBERTa. PoultryLeX-Net consistently outperformed all baselines, achieving an accuracy of 97.35%, an F1 score of 96.67%, and an area under the receiver operating characteristic curve (AUC-ROC) of 99.61% across sentiment classification tasks. Overall, domain adaptation and dual-stream attention markedly improve sentiment classification, enabling scalable intelligence for poultry production decision support.
### Title:
          Adaptive Engram Memory System for Indonesian Language Model: Generative AI Based on TOBA LM for Batak and Minang Language
 - **Authors:** Hokky Situngkir, Kevin Siringoringo, Andhika Bernard Lumbantobing
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This study presents TOBA-LM, a trilingual language model based on GPT-2 architecture with 1.2 billion parameters, trained on a corpus encompassing Indonesian, Batak, and Minangkabau using syllabic-agglutinative tokenization. The architecture integrates an Engram Memory mechanism, an adaptive n-gram-based memory system with a 500,000 x 768 embedding table that captures morphological dependencies through bigram and trigram pathways. Empirical results demonstrate a training efficiency of 80%, with the loss value dropping from 6.4 to 1.7996 in only 12,973 steps -- significantly faster than the conventional transformer architecture, which required over 70,000 steps to achieve comparable convergence. These findings confirm that the integration of external statistical memory substantially reduces computational requirements for developing regional language models under limited resources.
### Title:
          Tureis: Transformer-based Unified Resilience for IoT Devices in Smart Homes
 - **Authors:** Alireza Borhani, Vafa Andalibi, Bahar Asgari
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Smart-home IoT systems rely on heterogeneous sensor networks whose correctness shapes application behavior and the physical environment. However, these low-cost, resource-constrained sensors are highly prone to failure under real-world stressors. Prior methods often assume single-failure, single-resident settings, offer only failure detection rather than sensor-level localization, cover limited fault types and sensor modalities, require labels and human intervention, or impose overheads hindering edge deployment. To overcome these limitations, we propose Tureis, a self-supervised, context-aware method for failure detection and faulty-sensor localization in smart homes, designed for multi-failure, multi-resident edge settings. Tureis encodes heterogeneous binary and numeric sensor streams into compact bit-level features. It then trains a lightweight BERT-style Transformer with sensor-wise masked reconstruction over short-horizon windows, capturing spatial and short-term temporal correlations without mixing unrelated events. This self-supervised objective removes the need for labels or curated semantics. Then, at run-time, Tureis converts reconstruction residuals into sensor-level failure evidence and uses an iterative isolate-and-continue loop that masks flagged sensors, allowing other failures to surface and enabling resilient, fine-grained localization. Across five datasets with up to nine residents, Tureis improves single-failure localization F1 by +7.6%, +21.0%, and +25.0% over three strong baselines. In multi-failure scenarios with up to five faulty sensors, it further boosts localization F1 by +17.6% and +35.4% over two baselines, while the third does not extend to this setting. These gains come with minute-scale localization and an edge-friendly footprint, as a sub-megabyte model that processes each minute of data in a few milliseconds with ~0.5 GB peak memory on a Raspberry Pi 5.
### Title:
          Cluster-Aware Attention-Based Deep Reinforcement Learning for Pickup and Delivery Problems
 - **Authors:** Wentao Wang, Lifeng Han, Guangyu Zou
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Pickup and Delivery Problem (PDP) is a fundamental and challenging variant of the Vehicle Routing Problem, characterized by tightly coupled pickup--delivery pairs, precedence constraints, and spatial layouts that often exhibit clustering. Existing deep reinforcement learning (DRL) approaches either model all nodes on a flat graph, relying on implicit learning to enforce constraints, or achieve strong performance through inference-time collaborative search at the cost of substantial latency. In this paper, we propose \emph{CAADRL} (Cluster-Aware Attention-based Deep Reinforcement Learning), a DRL framework that explicitly exploits the multi-scale structure of PDP instances via cluster-aware encoding and hierarchical decoding. The encoder builds on a Transformer and combines global self-attention with intra-cluster attention over depot, pickup, and delivery nodes, producing embeddings that are both globally informative and locally role-aware. Based on these embeddings, we introduce a Dynamic Dual-Decoder with a learnable gate that balances intra-cluster routing and inter-cluster transitions at each step. The policy is trained end-to-end with a POMO-style policy gradient scheme using multiple symmetric rollouts per instance. Experiments on synthetic clustered and uniform PDP benchmarks show that CAADRL matches or improves upon strong state-of-the-art baselines on clustered instances and remains highly competitive on uniform instances, particularly as problem size increases. Crucially, our method achieves these results with substantially lower inference time than neural collaborative-search baselines, suggesting that explicitly modeling cluster structure provides an effective and efficient inductive bias for neural PDP solvers.
### Title:
          Amnesia: Adversarial Semantic Layer Specific Activation Steering in Large Language Models
 - **Authors:** Ali Raza, Gurang Gupta, Nikolay Matyunin, Jibesh Patra
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Warning: This article includes red-teaming experiments, which contain examples of compromised LLM responses that may be offensive or upsetting. Large Language Models (LLMs) have the potential to create harmful content, such as generating sophisticated phishing emails and assisting in writing code of harmful computer viruses. Thus, it is crucial to ensure their safe and responsible response generation. To reduce the risk of generating harmful or irresponsible content, researchers have developed techniques such as reinforcement learning with human feedback to align LLM's outputs with human values and preferences. However, it is still undetermined whether such measures are sufficient to prevent LLMs from generating interesting responses. In this study, we propose Amnesia, a lightweight activation-space adversarial attack that manipulates internal transformer states to bypass existing safety mechanisms in open-weight LLMs. Through experimental analysis on state-of-the-art, open-weight LLMs, we demonstrate that our attack effectively circumvents existing safeguards, enabling the generation of harmful content without the need for any fine-tuning or additional training. Our experiments on benchmark datasets show that the proposed attack can induce various antisocial behaviors in LLMs. These findings highlight the urgent need for more robust security measures in open-weight LLMs and underscore the importance of continued research to prevent their potential misuse.
### Title:
          4DEquine: Disentangling Motion and Appearance for 4D Equine Reconstruction from Monocular Video
 - **Authors:** Jin Lyu, Liang An, Pujin Cheng, Yebin Liu, Xiaoying Tang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 4D reconstruction of equine family (e.g. horses) from monocular video is important for animal welfare. Previous mainstream 4D animal reconstruction methods require joint optimization of motion and appearance over a whole video, which is time-consuming and sensitive to incomplete observation. In this work, we propose a novel framework called 4DEquine by disentangling the 4D reconstruction problem into two sub-problems: dynamic motion reconstruction and static appearance reconstruction. For motion, we introduce a simple yet effective spatio-temporal transformer with a post-optimization stage to regress smooth and pixel-aligned pose and shape sequences from video. For appearance, we design a novel feed-forward network that reconstructs a high-fidelity, animatable 3D Gaussian avatar from as few as a single image. To assist training, we create a large-scale synthetic motion dataset, VarenPoser, which features high-quality surface motions and diverse camera trajectories, as well as a synthetic appearance dataset, VarenTex, comprising realistic multi-view images generated through multi-view diffusion. While training only on synthetic datasets, 4DEquine achieves state-of-the-art performance on real-world APT36K and AiM datasets, demonstrating the superiority of 4DEquine and our new datasets for both geometry and appearance reconstruction. Comprehensive ablation studies validate the effectiveness of both the motion and appearance reconstruction network. Project page: this https URL.
### Title:
          The Prediction-Measurement Gap: Toward Meaning Representations as Scientific Instruments
 - **Authors:** Hubert Plisiecki
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text embeddings have become central to computational social science and psychology, enabling scalable measurement of meaning and mixed-method inference. Yet most representation learning is optimized and evaluated for prediction and retrieval, yielding a prediction-measurement gap: representations that perform well as features may be poorly suited as scientific instruments. The paper argues that scientific meaning analysis motivates a distinct family of objectives - scientific usability - emphasizing geometric legibility, interpretability and traceability to linguistic evidence, robustness to non-semantic confounds, and compatibility with regression-style inference over semantic directions. Grounded in cognitive and neuro-psychological views of meaning, the paper assesses static word embeddings and contextual transformer representations against these requirements: static spaces remain attractive for transparent measurement, whereas contextual spaces offer richer semantics but entangle meaning with other signals and exhibit geometric and interpretability issues that complicate inference. The paper then outlines a course-setting agenda around (i) geometry-first design for gradients and abstraction, including hierarchy-aware spaces constrained by psychologically privileged levels; (ii) invertible post-hoc transformations that recondition embedding geometry and reduce nuisance influence; and (iii) meaning atlases and measurement-oriented evaluation protocols for reliable and traceable semantic inference. As the field debates the limits of scale-first progress, measurement-ready representations offer a principled new frontier.
### Title:
          DT-BEHRT: Disease Trajectory-aware Transformer for Interpretable Patient Representation Learning
 - **Authors:** Deyi Li, Zijun Yao, Qi Xu, Muxuan Liang, Lingyao Li, Zijian Xu, Mei Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The growing adoption of electronic health record (EHR) systems has provided unprecedented opportunities for predictive modeling to guide clinical decision making. Structured EHRs contain longitudinal observations of patients across hospital visits, where each visit is represented by a set of medical codes. While sequence-based, graph-based, and graph-enhanced sequence approaches have been developed to capture rich code interactions over time or within the same visits, they often overlook the inherent heterogeneous roles of medical codes arising from distinct clinical characteristics and contexts. To this end, in this study we propose the Disease Trajectory-aware Transformer for EHR (DT-BEHRT), a graph-enhanced sequential architecture that disentangles disease trajectories by explicitly modeling diagnosis-centric interactions within organ systems and capturing asynchronous progression patterns. To further enhance the representation robustness, we design a tailored pre-training methodology that combines trajectory-level code masking with ontology-informed ancestor prediction, promoting semantic alignment across multiple modeling modules. Extensive experiments on multiple benchmark datasets demonstrate that DT-BEHRT achieves strong predictive performance and provides interpretable patient representations that align with clinicians' disease-centered reasoning. The source code is publicly accessible at this https URL.
### Title:
          Adaptive Activation Cancellation for Hallucination Mitigation in Large Language Models
 - **Authors:** Eric Yocam, Varghese Vaidyan, Gurcan Comert, Paris Kalathas, Yong Wang, Judith L. Mwakalonge
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models frequently generate fluent but factually incorrect text. We propose Adaptive Activation Cancellation (AAC), a real-time inference-time framework that treats hallucination-associated neural activations as structured interference within the transformer residual stream, drawing an explicit analogy to classical adaptive noise cancellation from signal processing. The framework identifies Hallucination Nodes (H-Nodes) via layer-wise linear probing and suppresses them using a confidence-weighted forward hook during auto-regressive generation -- requiring no external knowledge, no fine-tuning, and no additional inference passes. Evaluated across OPT-125M, Phi-3-mini, and LLaMA 3-8B on TruthfulQA and HaluEval, the real-time hook is the only intervention that consistently improves downstream accuracy on all three scales. Critically, the method is strictly surgical: WikiText-103 perplexity and MMLU reasoning accuracy are preserved at exactly 0.0% degradation across all three model scales, a property that distinguishes AAC from interventions that trade fluency or general capability for factual improvement. On the LLaMA 3-8B scale, the hook additionally yields positive generation-level gains (MC1 +0.04; MC2 +0.003; Token-F1 +0.003) while achieving probe-space selectivity 5.94x - 3.5x higher than the ITI baseline -- demonstrating that targeted neuron-level suppression can simultaneously improve factual accuracy and preserve model capability.
### Title:
          Beyond Interleaving: Causal Attention Reformulations for Generative Recommender Systems
 - **Authors:** Hailing Cheng
 - **Subjects:** Subjects:
Information Retrieval (cs.IR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative Recommender Systems (GR) increasingly model user behavior as a sequence generation task by interleaving item and action tokens. While effective, this formulation introduces significant structural and computational inefficiencies: it doubles sequence length, incurs quadratic overhead, and relies on implicit attention to recover the causal relationship between an item and its associated action. Furthermore, interleaving heterogeneous tokens forces the Transformer to disentangle semantically incompatible signals, leading to increased attention noise and reduced representation this http URL this work, we propose a principled reformulation of generative recommendation that aligns sequence modeling with underlying causal structures and attention theory. We demonstrate that current interleaving mechanisms act as inefficient proxies for similarity-weighted action pooling. To address this, we introduce two novel architectures that eliminate interleaved dependencies to reduce sequence complexity by 50%: Attention-based Late Fusion for Actions (AttnLFA) and Attention-based Mixed Value Pooling (AttnMVP). These models explicitly encode the $i_n \rightarrow a_n$ causal dependency while preserving the expressive power of Transformer-based sequence this http URL evaluate our framework on large-scale product recommendation data from a major social network. Experimental results show that AttnLFA and AttnMVP consistently outperform interleaved baselines, achieving evaluation loss improvements of 0.29% and 0.80%, and significant gains in Normalized Entropy (NE). Crucially, these performance gains are accompanied by training time reductions of 23% and 12%, respectively. Our findings suggest that explicitly modeling item-action causality provides a superior design paradigm for scalable and efficient generative ranking.
### Title:
          Optimal Expert-Attention Allocation in Mixture-of-Experts: A Scalable Law for Dynamic Model Design
 - **Authors:** Junzhuo Li, Peijie Jiang, Changxin Tian, Jia Liu, Zhiqiang Zhang, Xuming Hu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a novel extension of neural scaling laws to Mixture-of-Experts (MoE) models, focusing on the optimal allocation of compute between expert and attention sub-layers. As MoE architectures have emerged as an efficient method for scaling model capacity without proportionally increasing computation, determining the optimal expert-attention compute ratio becomes critical. We define the ratio $r$ as the fraction of total FLOPs per token dedicated to the expert layers versus the attention layers, and explore how this ratio interacts with the overall compute budget and model sparsity. Through extensive experiments with GPT-style MoE Transformers, we empirically find that the optimal ratio $r^*$ follows a power-law relationship with total compute and varies with sparsity. Our analysis leads to an explicit formula for $r^*$, enabling precise control over the expert-attention compute allocation. We generalize the Chinchilla scaling law by incorporating this architectural parameter, providing a new framework for tuning MoE models beyond size and data. Our findings offer practical guidelines for designing efficient MoE models, optimizing performance while respecting fixed compute budgets.
### Title:
          COHORT: Hybrid RL for Collaborative Large DNN Inference on Multi-Robot Systems Under Real-Time Constraints
 - **Authors:** Mohammad Saeid Anwar, Anuradha Ravi, Indrajeet Ghosh, Gaurav Shinde, Carl Busart, Nirmalya Roy
 - **Subjects:** Subjects:
Robotics (cs.RO); Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large deep neural networks (DNNs), especially transformer-based and multimodal architectures, are computationally demanding and challenging to deploy on resource-constrained edge platforms like field robots. These challenges intensify in mission-critical scenarios (e.g., disaster response), where robots must collaborate under tight constraints on bandwidth, latency, and battery life, often without infrastructure or server support. To address these limitations, we present COHORT, a collaborative DNN inference and task-execution framework for multi-robot systems built on the Robotic Operating System (ROS). COHORT employs a hybrid offline-online reinforcement learning (RL) strategy to dynamically schedule and distribute DNN module execution across robots. Our key contributions are threefold: (a) Offline RL policy learning combined with Advantage-Weighted Regression (AWR), trained on auction-based task allocation data from heterogeneous DNN workloads across distributed robots, (b) Online policy adaptation via Multi-Agent PPO (MAPPO), initialized from the offline policy and fine-tuned in real time, and (c) comprehensive evaluation of COHORT on vision-language model (VLM) inference tasks such as CLIP and SAM, analyzing scalability with increasing robot/workload and robustness under . We benchmark COHORT against genetic algorithms and multiple RL baselines. Experimental results demonstrate that COHORT reduces battery consumption by 15.4% and increases GPU utilization by 51.67%, while satisfying frame-rate and deadline constraints 2.55 times of the time.
### Title:
          DiT4DiT: Jointly Modeling Video Dynamics and Actions for Generalizable Robot Control
 - **Authors:** Teli Ma, Jia Zheng, Zifan Wang, Chuili Jiang, Andy Cui, Junwei Liang, Shuo Yang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models have emerged as a promising paradigm for robot learning, but their representations are still largely inherited from static image-text pretraining, leaving physical dynamics to be learned from comparatively limited action data. Generative video models, by contrast, encode rich spatiotemporal structure and implicit physics, making them a compelling foundation for robotic manipulation. But their potentials are not fully explored in the literature. To bridge the gap, we introduce DiT4DiT, an end-to-end Video-Action Model that couples a video Diffusion Transformer with an action Diffusion Transformer in a unified cascaded framework. Instead of relying on reconstructed future frames, DiT4DiT extracts intermediate denoising features from the video generation process and uses them as temporally grounded conditions for action prediction. We further propose a dual flow-matching objective with decoupled timesteps and noise scales for video prediction, hidden-state extraction, and action inference, enabling coherent joint training of both modules. Across simulation and real-world benchmarks, DiT4DiT achieves state-of-the-art results, reaching average success rates of 98.6% on LIBERO and 50.8% on RoboCasa GR1 while using substantially less training data. On the Unitree G1 robot, it also delivers superior real-world performance and strong zero-shot generalization. Importantly, DiT4DiT improves sample efficiency by over 10x and speeds up convergence by up to 7x, demonstrating that video generation can serve as an effective scaling proxy for robot policy learning. We release code and models at this https URL.
### Title:
          StructDamage:A Large Scale Unified Crack and Surface Defect Dataset for Robust Structural Damage Detection
 - **Authors:** Misbah Ijaz, Saif Ur Rehman Khan, Abd Ur Rehman, Sebastian Vollmer, Andreas Dengel, Muhammad Nabeel Asim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated detection and classification of structural cracks and surface defects is a critical challenge in civil engineering, infrastructure maintenance, and heritage preservation. Recent advances in Computer Vision (CV) and Deep Learning (DL) have significantly improved automatic crack detection. However, these methods rely heavily on large, diverse, and carefully curated datasets that include various crack types across different surface materials. Many existing public crack datasets lack geographic diversity, surface types, scale, and labeling consistency, making it challenging for trained algorithms to generalize effectively in real world conditions. We provide a novel dataset, StructDamage, a curated collection of approximately 78,093 images spanning nine surface types: walls, tile, stone, road, pavement, deck, concrete, and brick. The dataset was constructed by systematically aggregating, harmonizing, and reannotating images from 32 publicly available datasets covering concrete structures, asphalt pavements, masonry walls, bridges, and historic buildings. All images are organized in a folder level classification hierarchy suitable for training Convolutional Neural Networks (CNNs) and Vision Transformers. To highlight the practical value of the dataset, we present baseline classification results using fifteen DL architectures from six model families, with twelve achieving macro F1-scores over 0.96. The best performing model DenseNet201 achieves 98.62% accuracy. The proposed dataset provides a comprehensive and versatile resource suitable for classification tasks. With thorough documentation and a standard structure, it is designed to promote reproducible research and support the development and fair evaluation of robust crack damage detection approaches.
### Title:
          Visually-Guided Controllable Medical Image Generation via Fine-Grained Semantic Disentanglement
 - **Authors:** Xin Huang, Junjie Liang, Qingshan Hou, Peng Cao, Jinzhu Yang, Xiaoli Liu, Osmar R. Zaiane
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Medical image synthesis is crucial for alleviating data scarcity and privacy constraints. However, fine-tuning general text-to-image (T2I) models remains challenging, mainly due to the significant modality gap between complex visual details and abstract clinical text. In addition, semantic entanglement persists, where coarse-grained text embeddings blur the boundary between anatomical structures and imaging styles, thus weakening controllability during generation. To address this, we propose a Visually-Guided Text Disentanglement framework. We introduce a cross-modal latent alignment mechanism that leverages visual priors to explicitly disentangle unstructured text into independent semantic representations. Subsequently, a Hybrid Feature Fusion Module (HFFM) injects these features into a Diffusion Transformer (DiT) through separated channels, enabling fine-grained structural control. Experimental results in three datasets demonstrate that our method outperforms existing approaches in terms of generation quality and significantly improves performance on downstream classification tasks. The source code is available at this https URL.
### Title:
          SCORE: Replacing Layer Stacking with Contractive Recurrent Depth
 - **Authors:** Guillaume Godin
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Residual connections are central to modern deep neural networks, enabling stable optimization and efficient information flow across depth. In this work, we propose SCORE (Skip-Connection ODE Recurrent Embedding), a discrete recurrent alternative to classical layer stacking. Instead of composing multiple independent layers, SCORE iteratively applies a single shared neural block using an ODE (Ordinary Differential Equation)-inspired contractive update: ht+1 = (1 - dt) * ht + dt * F(ht) This formulation can be interpreted as a depth-by-iteration refinement process, where the step size dt explicitly controls stability and update magnitude. Unlike continuous Neural ODE approaches, SCORE uses a fixed number of discrete iterations and standard backpropagation without requiring ODE solvers or adjoint methods. We evaluate SCORE across graph neural networks (ESOL molecular solubility), multilayer perceptrons, and Transformer-based language models (nanoGPT). Across architectures, SCORE generally improves convergence speed and often accelerates training. SCORE is reducing parameter count through shared weights. In practice, simple Euler integration provides the best trade-off between computational cost and performance, while higher-order integrators yield marginal gains at increased compute. These results suggest that controlled recurrent depth with contractive residual updates offers a lightweight and effective alternative to classical stacking in deep neural networks.
### Title:
          UniStitch: Unifying Semantic and Geometric Features for Image Stitching
 - **Authors:** Yuan Mei, Lang Nie, Kang Liao, Yunqiu Xu, Chunyu Lin, Bin Xiao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traditional image stitching methods estimate warps from hand-crafted geometric features, whereas recent learning-based solutions leverage semantic features from neural networks instead. These two lines of research have largely diverged along separate evolution, with virtually no meaningful convergence to date. In this paper, we take a pioneering step to bridge this gap by unifying semantic and geometric features with UniStitch, a unified image stitching framework from multimodal features. To align discrete geometric features (i.e., keypoint) with continuous semantic feature maps, we present a Neural Point Transformer (NPT) module, which transforms unordered, sparse 1D geometric keypoints into ordered, dense 2D semantic maps. Then, to integrate the advantages of both representations, an Adaptive Mixture of Experts (AMoE) module is designed to fuse geometric and semantic representations. It dynamically shifts focus toward more reliable features during the fusion process, allowing the model to handle complex scenes, especially when either modality might be compromised. The fused representation can be adopted into common deep stitching pipelines, delivering significant performance gains over any single feature. Experiments show that UniStitch outperforms existing state-of-the-art methods with a large margin, paving the way for a unified paradigm between traditional and learning-based image stitching.
### Title:
          Implicit Statistical Inference in Transformers: Approximating Likelihood-Ratio Tests In-Context
 - **Authors:** Faris Chaudhry, Siddhant Gadkari
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In-context learning (ICL) allows Transformers to adapt to novel tasks without weight updates, yet the underlying algorithms remain poorly understood. We adopt a statistical decision-theoretic perspective by investigating simple binary hypothesis testing, where the optimal policy is determined by the likelihood-ratio test. Notably, this setup provides a mathematically rigorous setting for mechanistic interpretability where the target algorithmic ground truth is known. By training Transformers on tasks requiring distinct geometries (linear shifted means vs. nonlinear variance estimation), we demonstrate that the models approximate the Bayes-optimal sufficient statistics from context up to some monotonic transformation, matching the performance of an ideal oracle estimator in nonlinear regimes. Leveraging this analytical ground truth, mechanistic analysis via logit lens and circuit alignment suggests that the model does not rely on a fixed kernel smoothing heuristic. Instead, it appears to adapt the point at which decisions become linearly decodable: exhibiting patterns consistent with a voting-style ensemble for linear tasks while utilizing a deeper sequential computation for nonlinear tasks. These findings suggest that ICL emerges from the construction of task-adaptive statistical estimators rather than simple similarity matching.
### Title:
          Learning Bimanual Cloth Manipulation with Vision-based Tactile Sensing via Single Robotic Arm
 - **Authors:** Dongmyoung Lee, Wei Chen, Xiaoshuai Chen, Rui Zong, Petar Kormushev
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robotic cloth manipulation remains challenging due to the high-dimensional state space of fabrics, their deformable nature, and frequent occlusions that limit vision-based sensing. Although dual-arm systems can mitigate some of these issues, they increase hardware and control complexity. This paper presents Touch G.O.G., a compact vision-based tactile gripper and perception/control framework for single-arm bimanual cloth manipulation. The proposed framework combines three key components: (1) a novel gripper design and control strategy for in-gripper cloth sliding with a single robot arm, (2) a Vision Foundation Model-backboned Vision Transformer pipeline for cloth part classification (PC-Net) and edge pose estimation (PE-Net) using real and synthetic tactile images, and (3) an encoder-decoder synthetic data generator (SD-Net) that reduces manual annotation by producing high-fidelity tactile images. Experiments show 96% accuracy in distinguishing edges, corners, interior regions, and grasp failures, together with sub-millimeter edge localization and 4.5° orientation error. Real-world results demonstrate reliable cloth unfolding, even for crumpled fabrics, using only a single robotic arm. These results highlight Touch G.O.G. as a compact and cost-effective solution for deformable object manipulation.
### Title:
          How To Embed Matters: Evaluation of EO Embedding Design Choices
 - **Authors:** Luis Gilch, Isabelle Wittmann, Maximilian Nitsche, Johannes Jakubik, Arne Ewald, Thomas Brunschwiler
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Earth observation (EO) missions produce petabytes of multispectral imagery, increasingly analyzed using large Geospatial Foundation Models (GeoFMs). Alongside end-to-end adaptation, workflows make growing use of intermediate representations as task-agnostic embeddings, enabling models to compute representations once and reuse them across downstream tasks. Consequently, when GeoFMs act as feature extractors, decisions about how representations are obtained, aggregated, and combined affect downstream performance and pipeline scalability. Understanding these trade-offs is essential for scalable embedding-based EO workflows, where compact embeddings can replace raw data while remaining broadly useful. We present a systematic analysis of embedding design in GeoFM-based EO workflows. Leveraging NeuCo-Bench, we study how backbone architecture, pretraining strategy, representation depth, spatial aggregation, and representation combination influence EO task performance. We demonstrate the usability of GeoFM embeddings by aggregating them into fixed-size representations more than 500x smaller than the raw input data. Across models, we find consistent trends: transformer backbones with mean pooling provide strong default embeddings, intermediate ResNet layers can outperform final layers, self-supervised objectives exhibit task-specific strengths, and combining embeddings from different objectives often improves robustness.
### Title:
          A$^2$-Edit: Precise Reference-Guided Image Editing of Arbitrary Objects and Ambiguous Masks
 - **Authors:** Huayu Zheng, Guangzhao Li, Baixuan Zhao, Siqi Luo, Hantao Jiang, Guangtao Zhai, Xiaohong Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose \textbf{A$^2$-Edit}, a unified inpainting framework for arbitrary object categories, which allows users to replace any target region with a reference object using only a coarse mask. To address the issues of severe homogenization and limited category coverage in existing datasets, we construct a large-scale, multi-category dataset \textbf{UniEdit-500K}, which includes 8 major categories, 209 fine-grained subcategories, and a total of 500,104 image pairs. Such rich category diversity poses new challenges for the model, requiring it to automatically learn semantic relationships and distinctions across categories. To this end, we introduce the \textbf{Mixture of Transformer} module, which performs differentiated modeling of various object categories through dynamic expert selection, and further enhances cross-category semantic transfer and generalization through collaboration among experts. In addition, we propose a \textbf{Mask Annealing Training Strategy} (MATS) that progressively relaxes mask precision during training, reducing the model's reliance on accurate masks and improving robustness across diverse editing tasks. Extensive experiments on benchmarks such as VITON-HD and AnyInsertion demonstrate that A$^2$-Edit consistently outperforms existing approaches across all metrics, providing a new and efficient solution for arbitrary object editing.
### Title:
          Contract And Conquer: How to Provably Compute Adversarial Examples for a Black-Box Model?
 - **Authors:** Anna Chistyakova, Mikhail Pautov
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Black-box adversarial attacks are widely used as tools to test the robustness of deep neural networks against malicious perturbations of input data aimed at a specific change in the output of the model. Such methods, although they remain empirically effective, usually do not guarantee that an adversarial example can be found for a particular model. In this paper, we propose Contract And Conquer (CAC), an approach to provably compute adversarial examples for neural networks in a black-box manner. The method is based on knowledge distillation of a black-box model on an expanding distillation dataset and precise contraction of the adversarial example search space. CAC is supported by the transferability guarantee: we prove that the method yields an adversarial example for the black-box model within a fixed number of algorithm iterations. Experimentally, we demonstrate that the proposed approach outperforms existing state-of-the-art black-box attack methods on ImageNet dataset for different target models, including vision transformers.
### Title:
          Just-in-Time: Training-Free Spatial Acceleration for Diffusion Transformers
 - **Authors:** Wenhao Sun, Ji Li, Zhaoqiang Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformers have established a new state-of-the-art in image synthesis, but the high computational cost of iterative sampling severely hampers their practical deployment. While existing acceleration methods often focus on the temporal domain, they overlook the substantial spatial redundancy inherent in the generative process, where global structures emerge long before fine-grained details are formed. The uniform computational treatment of all spatial regions represents a critical inefficiency. In this paper, we introduce Just-in-Time (JiT), a novel training-free framework that addresses this challenge by acceleration in the spatial domain. JiT formulates a spatially approximated generative ordinary differential equation (ODE) that drives the full latent state evolution based on computations from a dynamically selected, sparse subset of anchor tokens. To ensure seamless transitions as new tokens are incorporated to expand the dimensions of the latent state, we propose a deterministic micro-flow, a simple and effective finite-time ODE that maintains both structural coherence and statistical correctness. Extensive experiments on the state-of-the-art FLUX.1-dev model demonstrate that JiT achieves up to a 7x speedup with nearly lossless performance, significantly outperforming existing acceleration methods and establishing a new and superior trade-off between inference speed and generation fidelity.
### Title:
          Dynamics-Informed Deep Learning for Predicting Extreme Events
 - **Authors:** Eirini Katsidoniotaki, Themistoklis P. Sapsis
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Dynamical Systems (math.DS); Chaotic Dynamics (nlin.CD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Predicting extreme events in high-dimensional chaotic dynamical systems remains a fundamental challenge, as such events are rare, intermittent, and arise from transient dynamical mechanisms that are difficult to infer from limited observations. Accordingly, real-time forecasting calls for precursors that encode the mechanisms driving extremes, rather than relying solely on statistical associations. We propose a fully data-driven framework for long-lead prediction of extreme events that constructs interpretable, mechanism-aware precursors by explicitly tracking transient instabilities preceding event onset. The approach leverages a reduced-order formulation to compute finite-time Lyapunov exponent (FTLE)-like precursors directly from state snapshots, without requiring knowledge of the governing equations. To avoid the prohibitive computational cost of classical FTLE computation, instability growth is evaluated in an adaptively evolving low-dimensional subspace spanned by Optimal Time-Dependent (OTD) modes, enabling efficient identification of transiently amplifying directions. These precursors are then provided as input to a Transformer-based model, enabling forecast of extreme event observables. We demonstrate the framework on Kolmogorov flow, a canonical model of intermittent turbulence. The results show that explicitly encoding transient instability mechanisms substantially extends practical prediction horizons compared to baseline observable-based approaches.
### Title:
          Guiding Diffusion Models with Semantically Degraded Conditions
 - **Authors:** Shilong Han, Yuming Zhang, Hongxia Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Classifier-Free Guidance (CFG) is a cornerstone of modern text-to-image models, yet its reliance on a semantically vacuous null prompt ($\varnothing$) generates a guidance signal prone to geometric entanglement. This is a key factor limiting its precision, leading to well-documented failures in complex compositional tasks. We propose Condition-Degradation Guidance (CDG), a novel paradigm that replaces the null prompt with a strategically degraded condition, $\boldsymbol{c}_{\text{deg}}$. This reframes guidance from a coarse "good vs. null" contrast to a more refined "good vs. almost good" discrimination, thereby compelling the model to capture fine-grained semantic distinctions. We find that tokens in transformer text encoders split into two functional roles: content tokens encoding object semantics, and context-aggregating tokens capturing global context. By selectively degrading only the former, CDG constructs $\boldsymbol{c}_{\text{deg}}$ without external models or training. Validated across diverse architectures including Stable Diffusion 3, FLUX, and Qwen-Image, CDG markedly improves compositional accuracy and text-image alignment. As a lightweight, plug-and-play module, it achieves this with negligible computational overhead. Our work challenges the reliance on static, information-sparse negative samples and establishes a new principle for diffusion guidance: the construction of adaptive, semantically-aware negative samples is critical to achieving precise semantic control. Code is available at this https URL.
### Title:
          Backdoor Directions in Vision Transformers
 - **Authors:** Sengim Karayalcin, Marina Krcek, Pin-Yu Chen, Stjepan Picek
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper investigates how Backdoor Attacks are represented within Vision Transformers (ViTs). By assuming knowledge of the trigger, we identify a specific ``trigger direction'' in the model's activations that corresponds to the internal representation of the trigger. We confirm the causal role of this linear direction by showing that interventions in both activation and parameter space consistently modulate the model's backdoor behavior across multiple datasets and attack types. Using this direction as a diagnostic tool, we trace how backdoor features are processed across layers. Our analysis reveals distinct qualitative differences: static-patch triggers follow a different internal logic than stealthy, distributed triggers. We further examine the link between backdoors and adversarial attacks, specifically testing whether PGD-based perturbations (de-)activate the identified trigger mechanism. Finally, we propose a data-free, weight-based detection scheme for stealthy-trigger attacks. Our findings show that mechanistic interpretability offers a robust framework for diagnosing and addressing security vulnerabilities in computer vision.
### Title:
          Continuous Diffusion Transformers for Designing Synthetic Regulatory Elements
 - **Authors:** Jonathan Liu, Kia Ghods
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Genomics (q-bio.GN)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a parameter-efficient Diffusion Transformer (DiT) for generating 200bp cell-type-specific regulatory DNA sequences. By replacing the U-Net backbone of DNA-Diffusion with a transformer denoiser equipped with a 2D CNN input encoder, our model matches the U-Net's best validation loss in 13 epochs (60$\times$ fewer) and converges 39% lower, while reducing memorization from 5.3% to 1.7% of generated sequences aligning to training data via BLAT. Ablations show the CNN encoder is essential: without it, validation loss increases 70% regardless of positional embedding choice. We further apply DDPO finetuning using Enformer as a reward model, achieving a 38$\times$ improvement in predicted regulatory activity. Cross-validation against DRAKES on an independent prediction task confirms that improvements reflect genuine regulatory signal rather than reward model overfitting.
### Title:
          LookaheadKV: Fast and Accurate KV Cache Eviction by Glimpsing into the Future without Generation
 - **Authors:** Jinwoo Ahn, Ingyu Seong, Akhil Kedia, Junhan Kim, Hyemi Jang, Kangwook Lee, Yongkweon Jeon
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based large language models (LLMs) rely on key-value (KV) caching to avoid redundant computation during autoregressive inference. While this mechanism greatly improves efficiency, the cache size grows linearly with the input sequence length, quickly becoming a bottleneck for long-context tasks. Existing solutions mitigate this problem by evicting prompt KV that are deemed unimportant, guided by estimated importance scores. Notably, a recent line of work proposes to improve eviction quality by "glimpsing into the future", in which a draft generator produces a surrogate future response approximating the target model's true response, and this surrogate is subsequently used to estimate the importance of cached KV more accurately. However, these approaches rely on computationally expensive draft generation, which introduces substantial prefilling overhead and limits their practicality in real-world deployment. To address this challenge, we propose LookaheadKV, a lightweight eviction framework that leverages the strength of surrogate future response without requiring explicit draft generation. LookaheadKV augments transformer layers with parameter-efficient modules trained to predict true importance scores with high accuracy. Our design ensures negligible runtime overhead comparable to existing inexpensive heuristics, while achieving accuracy superior to more costly approximation methods. Extensive experiments on long-context understanding benchmarks, across a wide range of models, demonstrate that our method not only outperforms recent competitive baselines in various long-context understanding tasks, but also reduces the eviction cost by up to 14.5x, leading to significantly faster time-to-first-token. Our code is available at this https URL.
### Title:
          Bio-Inspired Self-Supervised Learning for Wrist-worn IMU Signals
 - **Authors:** Prithviraj Tarale, Kiet Chu, Abhishek Varghese, Kai-Chun Liu, Maxwell A Xu, Mohit Iyyer, Sunghoon I. Lee
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Wearable accelerometers have enabled large-scale health and wellness monitoring, yet learning robust human-activity representations has been constrained by the scarcity of labeled data. While self-supervised learning offers a potential remedy, existing approaches treat sensor streams as unstructured time series, overlooking the underlying biological structure of human movement, a factor we argue is critical for effective Human Activity Recognition (HAR). We introduce a novel tokenization strategy grounded in the submovement theory of motor control, which posits that continuous wrist motion is composed of superposed elementary basis functions called submovements. We define our token as the movement segment, a unit of motion composed of a finite sequence of submovements that is readily extractable from wrist accelerometer signals. By treating these segments as tokens, we pretrain a Transformer encoder via masked movement-segment reconstruction to model the temporal dependencies of movement segments, shifting the learning focus beyond local waveform morphology. Pretrained on the NHANES corpus (approximately 28k hours; approximately 11k participants; approximately 10M windows), our representations outperform strong wearable SSL baselines across six subject-disjoint HAR benchmarks. Furthermore, they demonstrate stronger data efficiency in data-scarce settings. Code and pretrained weights will be made publicly available.
### Title:
          Pointy - A Lightweight Transformer for Point Cloud Foundation Models
 - **Authors:** Konrad Szafer, Marek Kraft, Dominik Belter
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Foundation models for point cloud data have recently grown in capability, often leveraging extensive representation learning from language or vision. In this work, we take a more controlled approach by introducing a lightweight transformer-based point cloud architecture. In contrast to the heavy reliance on cross-modal supervision, our model is trained only on 39k point clouds - yet it outperforms several larger foundation models trained on over 200k training samples. Interestingly, our method approaches state-of-the-art results from models that have seen over a million point clouds, images, and text samples, demonstrating the value of a carefully curated training setup and architecture. To ensure rigorous evaluation, we conduct a comprehensive replication study that standardizes the training regime and benchmarks across multiple point cloud architectures. This unified experimental framework isolates the impact of architectural choices, allowing for transparent comparisons and highlighting the benefits of our design and other tokenizer-free architectures. Our results show that simple backbones can deliver competitive results to more complex or data-rich strategies. The implementation, including code, pre-trained models, and training protocols, is available at this https URL.
### Title:
          Contrastive learning-based video quality assessment-jointed video vision transformer for video recognition
 - **Authors:** Jian Sun, Mohammad H. Mahoor
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video quality significantly affects video classification. We found this problem when we classified Mild Cognitive Impairment well from clear videos, but worse from blurred ones. From then, we realized that referring to Video Quality Assessment (VQA) may improve video classification. This paper proposed Self-Supervised Learning-based Video Vision Transformer combined with No-reference VQA for video classification (SSL-V3) to fulfill the goal. SSL-V3 leverages Combined-SSL mechanism to join VQA into video classification and address the label shortage of VQA, which commonly occurs in video datasets, making it impossible to provide an accurate Video Quality Score. In brief, Combined-SSL takes video quality score as a factor to directly tune the feature map of the video classification. Then, the score, as an intersected point, links VQA and classification, using the supervised classification task to tune the parameters of VQA. SSL-V3 achieved robust experimental results on two datasets. For example, it reached an accuracy of 94.87% on some interview videos in the I-CONECT (a facial video-involved healthcare dataset), verifying SSL-V3's effectiveness.
### Title:
          Med-DualLoRA: Local Adaptation of Foundation Models for 3D Cardiac MRI
 - **Authors:** Joan Perramon-Llussà, Amelia Jiménez-Sánchez, Grzegorz Skorupko, Fotis Avgoustidis, Carlos Martín-Isla, Karim Lekadir, Polyxeni Gkontra
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Foundation models (FMs) show great promise for robust downstream performance across medical imaging tasks and modalities, including cardiac magnetic resonance (CMR), following task-specific adaptation. However, adaptation using single-site data may lead to suboptimal performance and increased model bias, while centralized fine-tuning on clinical data is often infeasible due to privacy constraints. Federated fine-tuning offers a privacy-preserving alternative; yet conventional approaches struggle under heterogeneous, non-IID multi-center data and incur substantial communication overhead when adapting large models. In this work, we study federated FM fine-tuning for 3D CMR disease detection and propose Med-DualLoRA, a client-aware parameter-efficient fine-tuning (PEFT) federated framework that disentangles globally shared and local low-rank adaptations (LoRA) through additive decomposition. Global and local LoRA modules are trained locally, but only the global component is shared and aggregated across sites, keeping local adapters private. This design improves personalization while significantly reducing communication cost, and experiments show that adapting only two transformer blocks preserves performance while further improving efficiency. We evaluate our method on a multi-center state-of-the-art cine 3D CMR FM fine-tuned for disease detection using ACDC and combined M\&Ms datasets, treating each vendor as a federated client. Med-DualLoRA achieves statistically significant improved performance (balanced accuracy 0.768, specificity 0.612) compared to other federated PEFT baselines, while maintaining communication efficiency. Our approach provides a scalable solution for local federated adaptation of medical FMs under realistic clinical constraints.
### Title:
          The Discrete Charm of the MLP: Binary Routing of Continuous Signals in Transformer Feed-Forward Layers
 - **Authors:** Peter Balogh
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We show that MLP layers in transformer language models perform binary routing of continuous signals: the decision of whether a token needs nonlinear processing is well-captured by binary neuron activations, even though the signals being routed are continuous. In GPT-2 Small (124M parameters), we find that specific neurons implement a consensus architecture -- seven "default-ON" neurons and one exception handler (N2123 in Layer 11) that are 93-98% mutually exclusive -- creating a binary routing switch. A cross-layer analysis reveals a developmental arc: early layers (L1-3) use single gateway neurons to route exceptions without consensus quorums; middle layers (L4-6) show diffuse processing with neither gateway nor consensus; and late layers (L7-11) crystallize full consensus/exception architectures with increasing quorum size (1 to 3 to 7 consensus neurons). Causal validation confirms the routing is functional: removing the MLP at consensus breakdown costs 43.3% perplexity, while at full consensus removing it costs only 10.1% -- exceeding a 4x difference. Comparing binary vs. continuous features for the routing decision confirms that binarization loses essentially no information (79.2% vs. 78.8% accuracy), while continuous activations carry additional magnitude information (R^2 = 0.36 vs. 0.22). This binary routing structure explains why smooth polynomial approximation fails: cross-validated polynomial fits (degrees 2-7) never exceed R^2 = 0.06 for highly nonlinear layers. We propose that the well-established piecewise-affine characterization of deep networks can be complemented by a routing characterization: along the natural data manifold, the piecewise boundaries implement binary decisions about which tokens need nonlinear processing, routing continuous signals through qualitatively different computational paths.
## Keyword: autonomous driving
### Title:
          HG-Lane: High-Fidelity Generation of Lane Scenes under Adverse Weather and Lighting Conditions without Re-annotation
 - **Authors:** Daichao Zhao, Qiupu Chen, Feng He, Xin Ning, Qiankun Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Lane detection is a crucial task in autonomous driving, as it helps ensure the safe operation of vehicles. However, existing datasets such as CULane and TuSimple contain relatively limited data under extreme weather conditions, including rain, snow, and fog. As a result, detection models trained on these datasets often become unreliable in such environments, which may lead to serious safety-critical failures on the road. To address this issue, we propose HG-Lane, a High-fidelity Generation framework for Lane Scenes under adverse weather and lighting conditions without requiring re-annotation. Based on this framework, we further construct a benchmark that includes adverse weather and lighting scenarios, containing 30,000 images. Experimental results demonstrate that our method consistently and significantly improves the performance of existing lane detection networks. For example, using the state-of-the-art CLRNet, the overall mF1 score on our benchmark increases by 20.87 percent. The F1@50 score for the overall, normal, snow, rain, fog, night, and dusk categories increases by 19.75 percent, 8.63 percent, 38.8 percent, 14.96 percent, 26.84 percent, 21.5 percent, and 12.04 percent, respectively. The code and dataset are available at: this https URL.
### Title:
          PC-Diffuser: Path-Consistent Capsule CBF Safety Filtering for Diffusion-Based Trajectory Planner
 - **Authors:** Eugene Ku, Yiwei Lyu
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving in complex traffic requires planners that generalize beyond hand-crafted rules, motivating data-driven approaches that learn behavior from expert demonstrations. Diffusion-based trajectory planners have recently shown strong closed-loop performance by iteratively denoising a full-horizon plan, but they remain difficult to certify and can fail catastrophically in rare or out-of-distribution scenarios. To address this challenge, we present PC-Diffuser, a safety augmentation framework that embeds a certifiable, path-consistent barrier-function structure directly into the denoising loop of diffusion planning. The key idea is to make safety an intrinsic part of trajectory generation rather than a post-hoc fix: we enforce forward invariance along the rollout while preserving the diffusion model's intended path geometry. Specifically, PC-Diffuser (i) evaluates collision risk using a capsule-distance barrier function that better reflects vehicle geometry and reduces unnecessary conservativeness, (ii) converts denoised waypoints into dynamically feasible motion under a kinematic bicycle model, and (iii) applies a path-consistent safety filter that eliminates residual constraint violations without geometric distortion, so the corrected plan remains close to the learned distribution. By injecting these safety-consistent corrections at every denoising step and feeding the refined trajectory back into the diffusion process, PC-Diffuser enables iterative, context-aware safeguarding instead of post-hoc repair...
### Title:
          Motion Forcing: A Decoupled Framework for Robust Video Generation in Motion Dynamics
 - **Authors:** Tianshuo Xu, Zhifei Chen, Leyi Wu, Hao Lu, Ying-cong Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The ultimate goal of video generation is to satisfy a fundamental trilemma: achieving high visual quality, maintaining rigorous physical consistency, and enabling precise controllability. While recent models can maintain this balance in simple, isolated scenarios, we observe that this equilibrium is fragile and often breaks down as scene complexity increases (e.g., involving collisions or dense traffic). To address this, we introduce \textbf{Motion Forcing}, a framework designed to stabilize this trilemma even in complex generative tasks. Our key insight is to explicitly decouple physical reasoning from visual synthesis via a hierarchical \textbf{``Point-Shape-Appearance''} paradigm. This approach decomposes generation into verifiable stages: modeling complex dynamics as sparse geometric anchors (\textbf{Point}), expanding them into dynamic depth maps that explicitly resolve 3D geometry (\textbf{Shape}), and finally rendering high-fidelity textures (\textbf{Appearance}). Furthermore, to foster robust physical understanding, we employ a \textbf{Masked Point Recovery} strategy. By randomly masking input anchors during training and enforcing the reconstruction of complete dynamic depth, the model is compelled to move beyond passive pattern matching and learn latent physical laws (e.g., inertia) to infer missing trajectories. Extensive experiments on autonomous driving benchmarks show that Motion Forcing significantly outperforms state-of-the-art baselines, maintaining trilemma stability across complex scenes. Evaluations on physics and robotics further confirm our framework's generality.
### Title:
          KnowDiffuser: A Knowledge-Guided Diffusion Planner with LM Reasoning and Prior-Informed Trajectory Initialization
 - **Authors:** Fan Ding, Xuewen Luo, Fengze Yang, Bo Yu, HwaHui Tew, Ganesh Krishnasamy, Junn Yong Loo
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advancements in Language Models (LMs) have demonstrated strong semantic reasoning capabilities, enabling their application in high-level decision-making for autonomous driving (AD). However, LMs operate over discrete token spaces and lack the ability to generate continuous, physically feasible trajectories required for motion planning. Meanwhile, diffusion models have proven effective at generating reliable and dynamically consistent trajectories, but often lack semantic interpretability and alignment with scene-level understanding. To address these limitations, we propose \textbf{KnowDiffuser}, a knowledge-guided motion planning framework that tightly integrates the semantic understanding of language models with the generative power of diffusion models. The framework employs a language model to infer context-aware meta-actions from structured scene representations, which are then mapped to prior trajectories that anchor the subsequent denoising process. A two-stage truncated denoising mechanism refines these trajectories efficiently, preserving both semantic alignment and physical feasibility. Experiments on the nuPlan benchmark demonstrate that KnowDiffuser significantly outperforms existing planners in both open-loop and closed-loop evaluations, establishing a robust and interpretable framework that effectively bridges the semantic-to-physical gap in AD systems.
### Title:
          Recover to Predict: Progressive Retrospective Learning for Variable-Length Trajectory Prediction
 - **Authors:** Hao Zhou, Lu Qi, Jason Li, Jie Zhang, Yi Liu, Xu Yang, Mingyu Fan, Fei Luo
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Trajectory prediction is critical for autonomous driving, enabling safe and efficient planning in dense, dynamic traffic. Most existing methods optimize prediction accuracy under fixed-length observations. However, real-world driving often yields variable-length, incomplete observations, posing a challenge to these methods. A common strategy is to directly map features from incomplete observations to those from complete ones. This one-shot mapping, however, struggles to learn accurate representations for short trajectories due to significant information gaps. To address this issue, we propose a Progressive Retrospective Framework (PRF), which gradually aligns features from incomplete observations with those from complete ones via a cascade of retrospective units. Each unit consists of a Retrospective Distillation Module (RDM) and a Retrospective Prediction Module (RPM), where RDM distills features and RPM recovers previous timesteps using the distilled features. Moreover, we propose a Rolling-Start Training Strategy (RSTS) that enhances data efficiency during PRF training. PRF is plug-and-play with existing methods. Extensive experiments on datasets Argoverse 2 and Argoverse 1 demonstrate the effectiveness of PRF. Code is available at this https URL.
### Title:
          Evaluating randomized smoothing as a defense against adversarial attacks in trajectory prediction
 - **Authors:** Julian F. Schumann, Eduardo Figueiredo, Frederik Baymler Mathiesen, Luca Laurenti, Jens Kober, Arkady Zgonnikov
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate and robust trajectory prediction is essential for safe and efficient autonomous driving, yet recent work has shown that even state-of-the-art prediction models are highly vulnerable to inputs being mildly perturbed by adversarial attacks. Although model vulnerabilities to such attacks have been studied, work on effective countermeasures remains limited. In this work, we develop and evaluate a new defense mechanism for trajectory prediction models based on randomized smoothing -- an approach previously applied successfully in other domains. We evaluate its ability to improve model robustness through a series of experiments that test different strategies of randomized smoothing. We show that our approach can consistently improve prediction robustness of multiple base trajectory prediction models in various datasets without compromising accuracy in non-adversarial settings. Our results demonstrate that randomized smoothing offers a simple and computationally inexpensive technique for mitigating adversarial attacks in trajectory prediction.
### Title:
          STADA: Specification-based Testing for Autonomous Driving Agents
 - **Authors:** Joy Saha, Trey Woodlief, Sebastian Elbaum, Matthew B. Dwyer
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Simulation-based testing has become a standard approach to validating autonomous driving agents prior to real-world deployment. A high-quality validation campaign will exercise an agent in diverse contexts comprised of varying static environments, e.g., lanes, intersections, signage, and dynamic elements, e.g., vehicles and pedestrians. To achieve this, existing test generation techniques rely on template-based, manually constructed, or random scenario generation. When applied to validate formally specified safety requirements, such methods either require significant human effort or run the risk of missing important behavior related to the requirement. To address this gap, we present STADA, a Specification-based Test generation framework for Autonomous Driving Agents that systematically generates the space of scenarios defined by a formal specification expressed in temporal logic (LTLf). Given a specification, STADA constructs all distinct initial scenes, a diverse space of continuations of those scenes, and simulations that reflect the behaviors of the specification. Evaluation of STADA on a variety of LTLf specifications formalized in SCENEFLOW using three complementary coverage criteria demonstrates that STADA yields more than 2x higher coverage than the best baseline on the finest criteria and a 75% increase for the coarsest criteria. Moreover, it matches the coverage of the best baseline with 6 times fewer simulations. While set in the context of autonomous driving, the approach is applicable to other domains with rich simulation environments.
