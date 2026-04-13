# Showing new listings for Monday, 13 April 2026
## Keyword: SLAM
### Title:
          Accelerating Transformer-Based Monocular SLAM via Geometric Utility Scoring
 - **Authors:** Xinmiao Xiong, Bangya Liu, Hao Wang, Dayou Li, Nuo Chen, Andrew Feng, Mingyu Ding, Suman Banerjee, Yang Zhou, Zhiwen Fan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Geometric Foundation Models (GFMs) have recently advanced monocular SLAM by providing robust, calibration-free 3D priors. However, deploying these models on dense video streams introduces significant computational redundancy. Current GFM-based SLAM systems typically rely on post hoc keyframe selection. Because of this, they must perform expensive dense geometric decoding simply to determine whether a frame contains novel geometry, resulting in late rejection and wasted computation. To mitigate this inefficiency, we propose LeanGate, a lightweight feed-forward frame-gating network. LeanGate predicts a geometric utility score to assess a frame's mapping value prior to the heavy GFM feature extraction and matching stages. As a predictive plug-and-play module, our approach bypasses over 90% of redundant frames. Evaluations on standard SLAM benchmarks demonstrate that LeanGate reduces tracking FLOPs by more than 85% and achieves a 5x end-to-end throughput speedup. Furthermore, it maintains the tracking and mapping accuracy of dense baselines.
## Keyword: odometry
### Title:
          Incremental Semantics-Aided Meshing from LiDAR-Inertial Odometry and RGB Direct Label Transfer
 - **Authors:** Muhammad Affan, Ville Lehtola, George Vosselman
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Geometric high-fidelity mesh reconstruction from LiDAR-inertial scans remains challenging in large, complex indoor environments -- such as cultural buildings -- where point cloud sparsity, geometric drift, and fixed fusion parameters produce holes, over-smoothing, and spurious surfaces at structural boundaries. We propose a modular, incremental RGB+LiDAR pipeline that generates incremental semantics-aided high-quality meshes from indoor scans through scan frame-based direct label transfer. A vision foundation model labels each incoming RGB frame; labels are incrementally projected and fused onto a LiDAR-inertial odometry map; and an incremental semantics-aware Truncated Signed Distance Function (TSDF) fusion step produces the final mesh via marching cubes. This frame-level fusion strategy preserves the geometric fidelity of LiDAR while leveraging rich visual semantics to resolve geometric ambiguities at reconstruction boundaries caused by LiDAR point-cloud sparsity and geometric drift. We demonstrate that semantic guidance improves geometric reconstruction quality; quantitative evaluation is therefore performed using geometric metrics on the Oxford Spires dataset, while results from the NTU VIRAL dataset are analyzed qualitatively. The proposed method outperforms state-of-the-art geometric baselines ImMesh and Voxblox, demonstrating the benefit of semantics-aided fusion for geometric mesh quality. The resulting semantically labelled meshes are of value when reconstructing Universal Scene Description (USD) assets, offering a path from indoor LiDAR scanning to XR and digital modeling.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Neural Distribution Prior for LiDAR Out-of-Distribution Detection
 - **Authors:** Zizhao Li, Zhengkang Xiang, Jiayang Ao, Feng Liu, Joseph West, Kourosh Khoshelham
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR-based perception is critical for autonomous driving due to its robustness to poor lighting and visibility conditions. Yet, current models operate under the closed-set assumption and often fail to recognize unexpected out-of-distribution (OOD) objects in the open world. Existing OOD scoring functions exhibit limited performance because they ignore the pronounced class imbalance inherent in LiDAR OOD detection and assume a uniform class distribution. To address this limitation, we propose the Neural Distribution Prior (NDP), a framework that models the distributional structure of network predictions and adaptively reweights OOD scores based on alignment with a learned distribution prior. NDP dynamically captures the logit distribution patterns of training data and corrects class-dependent confidence bias through an attention-based module. We further introduce a Perlin noise-based OOD synthesis strategy that generates diverse auxiliary OOD samples from input scans, enabling robust OOD training without external datasets. Extensive experiments on the SemanticKITTI and STU benchmarks demonstrate that NDP substantially improves OOD detection performance, achieving a point-level AP of 61.31\% on the STU test set, which is more than 10$\times$ higher than the previous best result. Our framework is compatible with various existing OOD scoring formulations, providing an effective solution for open-world LiDAR perception.
### Title:
          Characterizing Lidar Range-Measurement Ambiguity due to Multiple Returns
 - **Authors:** Jason H. Rife, Yifan Li
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable position and attitude sensing is critical for highly automated vehicles that operate on conventional roadways. Lidar sensors are increasingly incorporated into pose-estimation systems. Despite its great utility, lidar is a complex sensor, and its performance in roadway environments is not yet well understood. For instance, it is often assumed in lidar-localization algorithms that a lidar will always identify a unique surface along a given raypath. However, this assumption is not always true, as ample prior evidence exists to suggest that lidar units may generate measurements probabilistically when more than one scattering surface appears within the lidar's conical beam. In this paper, we analyze lidar datasets to characterize cases with probabilistic returns along particular raypaths. Our contribution is to present representative cumulative distribution functions (CDFs) for raypaths observed by two different mechanically rotating lidar units with stationary bases. In subsequent discussion, we outline a qualitative methodology to assess the effect of probabilistic multi-return cases on lidar-based localization.
### Title:
          Hierarchical Flow Decomposition for Turning Movement Prediction at Signalized Intersections
 - **Authors:** Md Atiqur Rahman Mallick, Kamrul Hasan, Pulock Das, Liang Hong, S M Shazzad Rassel
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate prediction of intersection turning movements is essential for adaptive signal control but remains difficult due to the high volatility of directional flows. This study proposes HFD-TM (Hierarchical Flow-Decomposition for Turning Movement Prediction), a hierarchical deep learning framework that predicts turning movements by first forecasting corridor through-movements and then expanding these predictions to individual turning streams. This design is motivated by empirical traffic structure, where corridor flows account for 65.1% of total volume, exhibit lower volatility than turning movements, and explain 35.5% of turning-movement variance. A physics-informed loss function enforces flow conservation to maintain structural consistency. Evaluated on six months of 15-minute interval LiDAR (Light Detection and Ranging) data from a six-intersection corridor in Nashville, Tennessee, HFD-TM achieves a mean absolute error of 2.49 vehicles per interval, reducing MAE by 5.7% compared to a Transformer and by 27.0% compared to a GRU (Gated Recurrent Unit). Ablation results show that hierarchical decomposition provides the largest performance gain, while training time is 12.8 times lower than DCRNN (Diffusion Convolutional Recurrent Neural Network), demonstrating suitability for real-time traffic applications.
### Title:
          SynFlow: Scaling Up LiDAR Scene Flow Estimation with Synthetic Data
 - **Authors:** Qingwen Zhang, Xiaomeng Zhu, Chenhan Jiang, Patric Jensfelt
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable 3D dynamic perception requires models that can anticipate motion beyond predefined categories, yet progress is hindered by the scarcity of dense, high-quality motion annotations. While self-supervision on unlabeled real data offers a path forward, empirical evidence suggests that scaling unlabeled data fails to close the performance gap due to noisy proxy signals. In this paper, we propose a shift in paradigm: learning robust real-world motion priors entirely from scalable simulation. We introduce SynFlow, a data generation pipeline that generates large-scale synthetic dataset specifically designed for LiDAR scene flow. Unlike prior works that prioritize sensor-specific realism, SynFlow employs a motion-oriented strategy to synthesize diverse kinematic patterns across 4,000 sequences ($\sim$940k frames), termed SynFlow-4k. This represents a 34x scale-up in annotated volume over existing real-world benchmarks. Our experiments demonstrate that SynFlow-4k provides a highly domain-invariant motion prior. In a zero-shot regime, models trained exclusively on our synthetic data generalize across multiple real-world benchmarks, rivaling in-domain supervised baselines on nuScenes and outperforming state-of-the-art methods on TruckScenes by 31.8%. Furthermore, SynFlow-4k serves as a label-efficient foundation: fine-tuning with only 5% of real-world labels surpasses models trained from scratch on the full available budget. We open-source the pipeline and dataset to facilitate research in generalizable 3D motion estimation. More detail can be found at this https URL.
### Title:
          Incremental Semantics-Aided Meshing from LiDAR-Inertial Odometry and RGB Direct Label Transfer
 - **Authors:** Muhammad Affan, Ville Lehtola, George Vosselman
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Geometric high-fidelity mesh reconstruction from LiDAR-inertial scans remains challenging in large, complex indoor environments -- such as cultural buildings -- where point cloud sparsity, geometric drift, and fixed fusion parameters produce holes, over-smoothing, and spurious surfaces at structural boundaries. We propose a modular, incremental RGB+LiDAR pipeline that generates incremental semantics-aided high-quality meshes from indoor scans through scan frame-based direct label transfer. A vision foundation model labels each incoming RGB frame; labels are incrementally projected and fused onto a LiDAR-inertial odometry map; and an incremental semantics-aware Truncated Signed Distance Function (TSDF) fusion step produces the final mesh via marching cubes. This frame-level fusion strategy preserves the geometric fidelity of LiDAR while leveraging rich visual semantics to resolve geometric ambiguities at reconstruction boundaries caused by LiDAR point-cloud sparsity and geometric drift. We demonstrate that semantic guidance improves geometric reconstruction quality; quantitative evaluation is therefore performed using geometric metrics on the Oxford Spires dataset, while results from the NTU VIRAL dataset are analyzed qualitatively. The proposed method outperforms state-of-the-art geometric baselines ImMesh and Voxblox, demonstrating the benefit of semantics-aided fusion for geometric mesh quality. The resulting semantically labelled meshes are of value when reconstructing Universal Scene Description (USD) assets, offering a path from indoor LiDAR scanning to XR and digital modeling.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          Accelerating Transformer-Based Monocular SLAM via Geometric Utility Scoring
 - **Authors:** Xinmiao Xiong, Bangya Liu, Hao Wang, Dayou Li, Nuo Chen, Andrew Feng, Mingyu Ding, Suman Banerjee, Yang Zhou, Zhiwen Fan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Geometric Foundation Models (GFMs) have recently advanced monocular SLAM by providing robust, calibration-free 3D priors. However, deploying these models on dense video streams introduces significant computational redundancy. Current GFM-based SLAM systems typically rely on post hoc keyframe selection. Because of this, they must perform expensive dense geometric decoding simply to determine whether a frame contains novel geometry, resulting in late rejection and wasted computation. To mitigate this inefficiency, we propose LeanGate, a lightweight feed-forward frame-gating network. LeanGate predicts a geometric utility score to assess a frame's mapping value prior to the heavy GFM feature extraction and matching stages. As a predictive plug-and-play module, our approach bypasses over 90% of redundant frames. Evaluations on standard SLAM benchmarks demonstrate that LeanGate reduces tracking FLOPs by more than 85% and achieves a 5x end-to-end throughput speedup. Furthermore, it maintains the tracking and mapping accuracy of dense baselines.
### Title:
          Dynamic Class-Aware Active Learning for Unbiased Satellite Image Segmentation
 - **Authors:** Gadi Hemanth Kumar, Athira Nambiar, Pankaj Bodani
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic segmentation of satellite imagery plays a vital role in land cover mapping and environmental monitoring. However, annotating large-scale, high-resolution satellite datasets is costly and time consuming, especially when covering vast geographic regions. Instead of randomly labeling data or exhaustively annotating entire datasets, Active Learning (AL) offers an efficient alternative by intelligently selecting the most informative samples for annotation with the help of Human-in-the-loop (HITL), thereby reducing labeling costs while maintaining high model performance. AL is particularly beneficial for large-scale or resource-constrained satellite applications, as it enables high segmentation accuracy with significantly fewer labeled samples. Despite these advantages, standard AL strategies typically rely on global uncertainty or diversity measures and lack the adaptability to target underperforming or rare classes as training progresses, leading to bias in the system. To overcome these limitations, we propose a novel adaptive acquisition function, Dynamic Class-Aware Uncertainty based Active learning (DCAU-AL) that prioritizes sample selection based on real-time class-wise performance gaps, thereby overcoming class-imbalance issue. The proposed DCAU-AL mechanism continuously tracks the performance of the segmentation per class and dynamically adjusts the sampling weights to focus on poorly performing or underrepresented classes throughout the active learning process. Extensive experiments on the OpenEarth land cover dataset show that DCAU-AL significantly outperforms existing AL methods, especially under severe class imbalance, delivering superior per-class IoU and improved annotation efficiency.
### Title:
          Towards Linguistically-informed Representations for English as a Second or Foreign Language: Review, Construction and Application
 - **Authors:** Wenxi Li, Xihao Wang, Weiwei Sun
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The widespread use of English as a Second or Foreign Language (ESFL) has sparked a paradigm shift: ESFL is not seen merely as a deviation from standard English but as a distinct linguistic system in its own right. This shift highlights the need for dedicated, knowledge-intensive representations of ESFL. In response, this paper surveys existing ESFL resources, identifies their limitations, and proposes a novel solution. Grounded in constructivist theories, the paper treats constructions as the fundamental units of analysis, allowing it to model the syntax--semantics interface of both ESFL and standard English. This design captures a wide range of ESFL phenomena by referring to syntactico-semantic mappings of English while preserving ESFL's unique characteristics, resulting a gold-standard syntactico-semantic resource comprising 1643 annotated ESFL sentences. To demonstrate the sembank's practical utility, we conduct a pilot study testing the Linguistic Niche Hypothesis, highlighting its potential as a valuable tool in Second Language Acquisition research.
### Title:
          A ROM-based BDDC solver for unfitted p-FEM level-set-based lattice structures
 - **Authors:** Gonzalo Bonilla Moreno, Giuliano Guarino, Pablo Antolin
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a domain decomposition method for the fast simulation of large lattice structures described by level set functions. The method does not rely on homogenization or multiscale techniques, and therefore avoids their underlying assumptions such as scale separation and periodicity. Individual cells are defined through level set functions and mapped into physical space using arbitrary order mappings, allowing the creation of complex graded designs with varying geometries and topologies. The discretization is based on unfitted p-FEM, where each cell is approximated by a single high order element. This choice naturally handles the implicit geometric description and provides high accuracy with a moderate number of degrees of freedom. The solver is built on the Balanced Domain Decomposition by Constraints (BDDC) method, where each cell corresponds to one subdomain. To accelerate the assembly of the cell stiffness matrices, we combine a fast assembly technique that separates the contributions of the geometric mapping from the trimmed domain with a reduced order model (ROM) based on the matrix discrete empirical interpolation method (MDEIM). The ROM surrogate is trained offline and reused for any geometric mapping, restricting the expensive quadrature on cut elements to the training stage. A stabilization term ensures the scalability of the solver when using the ROM approximation, at the cost of a small and controllable error. We validate the method through numerical experiments and demonstrate its performance on a complex 2D problem with more than 17,000 cells of varying geometry, solved in approximately 30 seconds on a standard laptop. The number of solver iterations remains bounded as the number of subdomains grows, provided the ratio between subdomain and mesh sizes is kept constant, in agreement with classical BDDC scalability properties.
### Title:
          MATCHA: Efficient Deployment of Deep Neural Networks on Multi-Accelerator Heterogeneous Edge SoCs
 - **Authors:** Enrico Russo, Mohamed Amine Hamdi, Alessandro Ottaviano, Francesco Conti, Angelo Garofalo, Daniele Jahier Pagliari, Maurizio Palesi, Luca Benini, Alessio Burrello
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Hardware Architecture (cs.AR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deploying DNNs on System-on-Chips (SoC) with multiple heterogeneous acceleration engines is challenging, and the majority of deployment frameworks cannot fully exploit heterogeneity. We present MATCHA, a unified DNN deployment framework that generates highly concurrent schedules for parallel, heterogeneous accelerators and uses constraint programming to optimize L3/L2 memory allocation and scheduling. Using pattern matching, tiling, and mapping across individual HW units enables parallel execution and high accelerator utilization. On the MLPerf Tiny benchmark, using a SoC with two heterogeneous accelerators, MATCHA improves accelerator utilization and reduces inference latency by up to 35% with respect to the the state-of-the-art MATCH compiler.
### Title:
          Few-Shot Personalized Age Estimation
 - **Authors:** Jakub Paplhám, Vojtěch Franc, Artem Moroz
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing age estimation methods treat each face as an independent sample, learning a global mapping from appearance to age. This ignores a well-documented phenomenon: individuals age at different rates due to genetics, lifestyle, and health, making the mapping from face to age identity-dependent. When reference images of the same person with known ages are available, we can exploit this context to personalize the estimate. The only existing benchmark for this task (NIST FRVT) is closed-source and limited to a single reference image. In this work, we introduce OpenPAE, the first open benchmark for $N$-shot personalized age estimation with strict evaluation protocols. We establish a hierarchy of increasingly sophisticated baselines: from arithmetic offset, through closed-form Bayesian linear regression, to a conditional attentive neural process. Our experiments show that personalization consistently improves performance, that the gains are not merely domain adaptation, and that nonlinear methods significantly outperform simpler alternatives. We release all models, code, protocols, and evaluation splits.
### Title:
          SHIFT: Sigmoid-Based Heuristic Invertible Fitness-Landscape Transformation for Accelerating SBST
 - **Authors:** Jeongjin Han, Seunghoon Sim, Jian Lee, Seongyoon Park
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Search-Based Software Testing (SBST) automates test input generation but is frequently hindered by challenging fitness landscapes characterized by numerous deceptive local optima that impede search progress, as well as extended plateaus where informative fitness signals are scarce. To address this bottleneck, we propose SHIFT (Sigmoid-Based Heuristic Invertible Fitness-Landscape Transformation for Accelerating SBST), a method designed to compress local landscapes and facilitate escape from stagnant regions without altering global semantics. By systematically contracting dense regions where search points cluster, the approach preserves mapping invertibility while enabling optimization algorithms to traverse more effectively toward global coverage with the same step size. When evaluated against established baselines, including pure hill climbing and genetic algorithms, under a normalized experimental protocol, the proposed technique yields consistent improvements in convergence speed and search efficiency. These results demonstrate that sigmoid compression constitutes a lightweight yet effective mechanism for achieving more reliable coverage discovery in complex testing environments.
### Title:
          A Domain-Theoretic Foundation for Imprecise Probability and Credal Sets
 - **Authors:** Abbas Edalat, Pietro Di Gianantonio, Amin Farjudian
 - **Subjects:** Subjects:
Logic in Computer Science (cs.LO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We develop a domain-theoretic framework for imprecise probability reasoning and inference on general topological spaces with a countably based continuous lattice of open sets. We address two distinct forms of uncertainty: partial or incomplete event descriptions, and sets of probability distributions as represented by credal sets -- as well as their combination. Within this framework, we construct a theory of conditional probability and derive novel inference rules for performing Bayesian updating in the presence of these two complementary types of imprecision. These results are extended to a theory of conditional independence for imprecise probabilistic events. We also formulate logical predicates for conditional probability, Bayesian updating, and conditional independence, and we obtain the relevant soundness and completeness results. A key contribution is the construction of a Scott-continuous mapping from any credal set to the domain of intervals, providing a domain-theoretic realisation of classical results from capacity theory and Choquet integration. Finally, we introduce and study a new family of credal sets generated by iterated function systems with imprecise probability weights, broadening the scope of computationally tractable imprecise probabilistic models. The resulting computable framework unifies logical, topological, and measure-theoretic perspectives on uncertainty, supporting robust probabilistic inference under partial and set-valued information.
### Title:
          Decision Trace Schema for Governance Evidence in Real-Time Risk Systems
 - **Authors:** Oleg Solozobov
 - **Subjects:** Subjects:
Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated decision systems produce operational data across multiple infrastructure layers, yet no single logging format captures the complete governance-relevant record of how a decision was reached. Regulatory frameworks prescribe what must be recorded without specifying a data model for how to record it -- a gap this paper terms the Fragmented Trace Problem. Following a design science methodology, the paper presents the Decision Event Schema (DES), a JSON Schema specification that bridges four infrastructure layers -- ML inference, rule/policy evaluation, cross-system coupling, and governance metadata -- within a single per-decision event structure. The schema employs degradation-aware field design: each of six top-level field groups maps to a governance evidence property and the degradation type it must resist. DES defines ten required root-level fields and introduces a tiered evidence strategy (lightweight, sampled, full) that enables organizations to match evidence completeness to decision risk and throughput. A mechanism feasibility analysis demonstrates compatibility with the highest-throughput integrity mechanisms at production-scale decision rates. Evaluation against 25+ existing formats confirms that DES is the only specification covering all four layers simultaneously. The schema offers practitioners a reference adoptable directly or adaptable through namespace extensions, and regulators a mapping from requirements to minimum evidence tiers.
### Title:
          Automated Instruction Revision (AIR): A Structured Comparison of Task Adaptation Strategies for LLM
 - **Authors:** Solomiia Bilyk, Volodymyr Getmanskyi, Taras Firman
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper studies Automated Instruction Revision (AIR), a rule-induction-based method for adapting large language models (LLMs) to downstream tasks using limited task-specific examples. We position AIR within the broader landscape of adaptation strategies, including prompt optimization, retrieval-based methods, and fine-tuning. We then compare these approaches across a diverse benchmark suite designed to stress different task requirements, such as knowledge injection, structured extraction, label remapping, and logical reasoning. The paper argues that adaptation performance is strongly task-dependent: no single method dominates across all settings. Across five benchmarks, AIR was strongest or near-best on label-remapping classification, while KNN retrieval performed best on closed-book QA, and fine-tuning dominated structured extraction and event-order reasoning. AIR is most promising when task behavior can be captured by compact, interpretable instruction rules, while retrieval and fine-tuning remain stronger in tasks dominated by source-specific knowledge or dataset-specific annotation regularities.
### Title:
          On the Representational Limits of Quantum-Inspired 1024-D Document Embeddings: An Experimental Evaluation Framework
 - **Authors:** Dario Maio
 - **Subjects:** Subjects:
Information Retrieval (cs.IR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text embeddings are central to modern information retrieval and Retrieval-Augmented Generation (RAG). While dense models derived from Large Language Models (LLMs) dominate current practice, recent work has explored quantum-inspired alternatives motivated by the geometric properties of Hilbert-like spaces and their potential to encode richer semantic structure. This paper presents an experimental framework for constructing quantum-inspired 1024-dimensional document embeddings based on overlapping windows and multi-scale aggregation. The pipeline combines semantic projections (e.g., EigAngle), circuit-inspired feature mappings, and optional teacher-student distillation, together with a fingerprinting mechanism for reproducibility and controlled evaluation. We introduce a set of diagnostic tools for hybrid retrieval, including static and dynamic interpolation between BM25 and embedding-based scores, candidate union strategies, and a conceptual alpha-oracle that provides an upper bound for score-level fusion. Experiments on controlled corpora of Italian and English documents across technical, narrative, and legal domains, using synthetic queries, show that BM25 remains a strong baseline, teacher embeddings provide stable semantic structure, and standalone quantum-inspired embeddings exhibit weak and unstable ranking signals. Distillation yields mixed effects, improving alignment in some cases but not consistently enhancing retrieval performance, while hybrid retrieval can recover competitive results when lexical and embedding-based signals are combined. Overall, the results highlight structural limitations in the geometry of quantum-inspired embeddings, including distance compression and ranking instability, and clarify their role as auxiliary components rather than standalone retrieval representations.
### Title:
          SCoRe: Clean Image Generation from Diffusion Models Trained on Noisy Images
 - **Authors:** Yuta Matsuzaki, Seiichi Uchida, Shumpei Takezaki
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion models trained on noisy datasets often reproduce high-frequency training artifacts, significantly degrading generation quality. To address this, we propose SCoRe (Spectral Cutoff Regeneration), a training-free, generation-time spectral regeneration method for clean image generation from diffusion models trained on noisy images. Leveraging the spectral bias of diffusion models, which infer high-frequency details from low-frequency cues, SCoRe suppresses corrupted high-frequency components of a generated image via a frequency cutoff and regenerates them via SDEdit. Crucially, we derive a theoretical mapping between the cutoff frequency and the SDEdit initialization timestep based on Radially Averaged Power Spectral Density (RAPSD), which prevents excessive noise injection during regeneration. Experiments on synthetic (CIFAR-10) and real-world (SIDD) noisy datasets demonstrate that SCoRe substantially outperforms post-processing and noise-robust baselines, restoring samples closer to clean image distributions without any retraining or fine-tuning.
### Title:
          Agentic Jackal: Live Execution and Semantic Value Grounding for Text-to-JQL
 - **Authors:** Vishnu Murali, Anmol Gulati, Elias Lumer, Kevin Frank, Sindy Campagna, Vamse Kumar Subbiah
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Translating natural language into Jira Query Language (JQL) requires resolving ambiguous field references, instance-specific categorical values, and complex Boolean predicates. Single-pass LLMs cannot discover which categorical values (e.g., component names or fix versions) actually exist in a given Jira instance, nor can they verify generated queries against a live data source, limiting accuracy on paraphrased or ambiguous requests. No open, execution-based benchmark exists for mapping natural language to JQL. We introduce Jackal, the first large-scale, execution-based text-to-JQL benchmark comprising 100,000 validated NL-JQL pairs on a live Jira instance with over 200,000 issues. To establish baselines on Jackal, we propose Agentic Jackal, a tool-augmented agent that equips LLMs with live query execution via the Jira MCP server and JiraAnchor, a semantic retrieval tool that resolves natural-language mentions of categorical values through embedding-based similarity search. Among 9 frontier LLMs evaluated, single-pass models average only 43.4% execution accuracy on short natural-language queries, highlighting that text-to-JQL remains an open challenge. The agentic approach improves 7 of 9 models, with a 9.0% relative gain on the most linguistically challenging variant; in a controlled ablation isolating JiraAnchor, categorical-value accuracy rises from 48.7% to 71.7%, with component-field accuracy jumping from 16.9% to 66.2%. Our analysis identifies inherent semantic ambiguities, such as issue-type disambiguation and text-field selection, as the dominant failure modes rather than value-resolution errors, pointing to concrete directions for future work. We publicly release the benchmark, all agent transcripts, and evaluation code to support reproducibility.
### Title:
          Integrated electro-optic attention nonlinearities for transformers
 - **Authors:** Luis Mickeler, Kai Lion, Alfonso Nardi, Jost Kellner, Pierre Didier, Bhavin J. Shastri, Niao He, Rachel Grange
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Optics (physics.optics)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers have emerged as the dominant neural-network architecture, achieving state-of-the-art performance in language processing and computer vision. At the core of these models lies the attention mechanism, which requires a nonlinear, non-negative mapping using the Softmax function. However, although Softmax operations account for less than 1% of the total operation count, they can disproportionately bottleneck overall inference latency. Here, we use thin-film lithium niobate (TFLN) Mach-Zehnder modulators (MZMs) as analog nonlinear computational elements to drastically reduce the latency of nonlinear computations. We implement electro-optic alternatives to digital Softmax and Sigmoid, and evaluate their performance in Vision Transformers and Large Language Models. Our system maintains highly competitive accuracy, even under aggressive 4-bit input-output quantization of the analog units. We further characterize system noise at encoding speeds up to 10 GBaud and assess model robustness under various noise conditions. Our findings suggest that TFLN modulators can serve as nonlinear function units within hybrid co-packaged hardware, enabling high-speed and energy-efficient nonlinear computation.
### Title:
          Sustaining Exascale Performance: Lessons from HPL and HPL-MxP on Aurora
 - **Authors:** Kazushige Goto, Huda Ibeid, Kalyan Kumaran, Servesh Muralidharan, Anthony-Trung Nguyen, Aditya Nishtala
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sustaining exascale performance in production requires engineering choices and operational practices that emerge only under real deployment constraints and demand coordination across system layers. This paper reports experience from three successive campaigns running HPL and HPL-MxP on Aurora, an Intel-based exascale system featuring the first large-scale deployment of Intel discrete GPUs, CPU-attached network interfaces, and the largest production Slingshot-11 interconnect. Aurora progressed from 0.585EF/s on 5,439 nodes to 1.01EF/s on 9,234 nodes in FP64 HPL, while HPL-MxP reached 11.64EF/s, an 11.5x speedup over FP64 enabled by mixed-precision arithmetic and Intel AMX acceleration. We identify and classify by role at production scale the system-level choices that sustained these results, including deterministic locality-aware resource mapping, explicit CPU-GPU pipelining, mixed-precision orchestration, and a hybrid P2P/collective resilience strategy introduced after synchronization stalls at scale. While some observations are Aurora-specific, the broader lessons are likely to apply to tightly coupled heterogeneous systems at extreme scale.
## Keyword: localization
### Title:
          Task-Aware Bimanual Affordance Prediction via VLM-Guided Semantic-Geometric Reasoning
 - **Authors:** Fabian Hahne, Vignesh Prasad, Georgia Chalvatzaki, Jan Peters, Alap Kshirsagar
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bimanual manipulation requires reasoning about where to interact with an object and which arm should perform each action, a joint affordance localization and arm allocation problem that geometry-only planners cannot resolve without semantic understanding of task intent. Existing approaches either treat affordance prediction as coarse part segmentation or rely on geometric heuristics for arm assignment, failing to jointly reason about task-relevant contact regions and arm allocation. We reframe bimanual manipulation as a joint affordance localization and arm allocation problem and propose a hierarchical framework for task-aware bimanual affordance prediction that leverages a Vision-Language Model (VLM) to generalize across object categories and task descriptions without requiring category-specific training. Our approach fuses multi-view RGB-D observations into a consistent 3D scene representation and generates global 6-DoF grasp candidates, which are then spatially and semantically filtered by querying the VLM for task-relevant affordance regions on each object, as well as for arm allocation to the individual objects, thereby ensuring geometric validity while respecting task semantics. We evaluate our method on a dual-arm platform across nine real-world manipulation tasks spanning four categories: parallel manipulation, coordinated stabilization, tool use, and human handover. Our approach achieves consistently higher task success rates than geometric and semantic baselines for task-oriented grasping, demonstrating that explicit semantic reasoning over affordances and arm allocation helps enable reliable bimanual manipulation in unstructured environments.
### Title:
          GRASP: Grounded CoT Reasoning with Dual-Stage Optimization for Multimodal Sarcasm Target Identification
 - **Authors:** Faxian Wan, Xiaocui Yang, Yifan Cao, Shi Feng, Daling Wang, Yifei Zhang
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Moving beyond the traditional binary classification paradigm of Multimodal Sarcasm Detection, Multimodal Sarcasm Target Identification (MSTI) presents a more formidable challenge, requiring precise localization of fine-grained targets such as textual phrases and visual regions. Existing approaches predominantly rely on implicit cross-modal alignment, offering limited interpretability and suboptimal fine-grained localization. To address these limitations, we propose GRASP, Grounded Chain-of-Thought ReAsoning with Dual-Stage Optimization for Multimodal Sarcasm Prediction and Target Identification, a framework that integrates visual grounding with explicit Chain-of-Thought (CoT) reasoning to move beyond black-box MSTI. Specifically, we curate MSTI-MAX, a refined dataset that mitigates class imbalance and enriches multimodal sarcasm cues. We introduce Grounded CoT reasoning, which explicitly anchors sarcasm-related visual regions within the reasoning trajectory and prompts the model to articulate rationales before predicting the final classification labels and sarcasm targets. Furthermore, we employ a dual-stage outcome-supervised joint optimization strategy: Supervised Fine-Tuning with a coordinate-aware weighted loss, followed by Fine-Grained Target Policy Optimization. Extensive experiments demonstrate that GRASP outperforms existing baselines in fine-grained sarcasm target identification across modalities, and an LLM-as-a-Judge evaluation quantitatively measures the quality of internal reasoning chains. Our dataset and source code will be released on GitHub.
### Title:
          Large-Scale Universal Defect Generation: Foundation Models and Datasets
 - **Authors:** Yuanting Fan, Jun Liu, Bin-Bin Gao, Xiaochen Chen, Yuhuan Lin, Zhewei Dai, Jiawei Zhan, Chengjie Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing defect/anomaly generation methods often rely on few-shot learning, which overfits to specific defect categories due to the lack of large-scale paired defect editing data. This issue is aggravated by substantial variations in defect scale and morphology, resulting in limited generalization, degraded realism, and category consistency. We address these challenges by introducing UDG, a large-scale dataset of 300K normal-abnormal-mask-caption quadruplets spanning diverse domains, and by presenting UniDG, a universal defect generation foundation model that supports both reference-based defect generation and text instruction-based defect editing without per-category fine-tuning. UniDG performs Defect-Context Editing via adaptive defect cropping and structured diptych input format, and fuses reference and target conditions through MM-DiT multimodal attention. A two-stage training strategy, Diversity-SFT followed by Consistency-RFT, further improves diversity while enhancing realism and reference consistency. Extensive experiments on MVTec-AD and VisA show that UniDG outperforms prior few-shot anomaly generation and image insertion/editing baselines in synthesis quality and downstream single- and multi-class anomaly detection/localization. Code will be available at this https URL.
### Title:
          TAIHRI: Task-Aware 3D Human Keypoints Localization for Close-Range Human-Robot Interaction
 - **Authors:** Ao Li, Yonggen Ling, Yiyang Lin, Yuji Wang, Yong Deng, Yansong Tang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate 3D human keypoints localization is a critical technology enabling robots to achieve natural and safe physical interaction with users. Conventional 3D human keypoints estimation methods primarily focus on the whole-body reconstruction quality relative to the root joint. However, in practical human-robot interaction (HRI) scenarios, robots are more concerned with the precise metric-scale spatial localization of task-relevant body parts under the egocentric camera 3D coordinate. We propose TAIHRI, the first Vision-Language Model (VLM) tailored for close-range HRI perception, capable of understanding users' motion commands and directing the robot's attention to the most task-relevant keypoints. By quantizing 3D keypoints into a finite interaction space, TAIHRI precisely localize the 3D spatial coordinates of critical body parts by 2D keypoint reasoning via next token prediction, and seamlessly adapt to downstream tasks such as natural language control or global space human mesh recovery. Experiments on egocentric interaction benchmarks demonstrate that TAIHRI achieves superior estimation accuracy for task-critical body parts. We believe TAIHRI opens new research avenues in the field of embodied human-robot interaction. Code is available at: this https URL.
### Title:
          How Should Video LLMs Output Time? An Analysis of Efficient Temporal Grounding Paradigms
 - **Authors:** Shengji Jin, Yuanhao Zou, Victor Zhu, Zhengping Ji, Chen Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Multimodal Large Language Models (MLLMs) have advanced Video Temporal Grounding (VTG), existing methods often couple output paradigms with different backbones, datasets, and training protocols. This makes it challenging to isolate the specific impact of the output design. Additionally, as VTG systems are increasingly considered for resource-constrained edge deployment, the trade-off between output formulation and system-level efficiency requires systematic investigation. In this paper, we present a controlled empirical study comparing three dominant VTG output paradigms: Text Numeral Generation, Temporal Token Generation, and Continuous Temporal Decoding. We evaluate these paradigms across identical compact VLMs (SmolVLM2, FastVLM, and Molmo2) using consistent datasets and LoRA fine-tuning protocols. Evaluations on Charades-STA, QVHighlights, and YouCook2 measure both localization accuracy and system efficiency, including inference latency, training throughput, and parameter overhead. Our results demonstrate that the choice of output formulation significantly affects both grounding accuracy and computational cost, independent of model scale. Specifically, the continuous distribution paradigm consistently achieves the most favorable efficiency-accuracy trade-off on the Pareto frontier, delivering robust localization with minimal latency overhead. These findings provide objective empirical guidelines for designing efficient, deployment-ready VTG systems.
### Title:
          SiMing-Bench: Evaluating Procedural Correctness from Continuous Interactions in Clinical Skill Videos
 - **Authors:** Xiyang Huang, Jiawei Lin, Keying Wu, Jiaxin Huang, Kailai Yang, Renxiong Wei, Cheng zeng, Jiayi Xiang, Ziyan Kuang, Min Peng, Qianqian Xie, Sophia Ananiadou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current video benchmarks for multimodal large language models (MLLMs) focus on event recognition, temporal ordering, and long-context recall, but overlook a harder capability required for expert procedural judgment: tracking how ongoing interactions update the procedural state and thereby determine the correctness of later actions. We introduce SiMing-Bench, the first benchmark for evaluating this capability from full-length clinical skill videos. It targets rubric-grounded process-level judgment of whether interaction-driven state updates preserve procedural correctness across an entire workflow. SiMing-Bench is instantiated with SiMing-Score, a physician-annotated dataset of real clinical skill examination videos spanning cardiopulmonary resuscitation, automated external defibrillator operation, and bag-mask ventilation, each paired with a standardized step-wise rubric and dual-expert labels. Across diverse open- and closed-source MLLMs, we observe consistently weak agreement with physician judgments. Moreover, weak performance on rubric-defined intermediate steps persists even when overall procedure-level correlation appears acceptable, suggesting that coarse global assessment substantially overestimates current models' procedural judgment ability. Additional analyses with binary step judgment and step-aligned clips indicate that the bottleneck is not merely fine-grained scoring or temporal localization, but modeling how continuous interactions update procedural state over time.
### Title:
          Towards Lifelong Aerial Autonomy: Geometric Memory Management for Continual Visual Place Recognition in Dynamic Environments
 - **Authors:** Xingyu Shao, Zhiqiang Yan, Liangzheng Sun, Mengfan He, Chao Chen, Jinhui Zhang, Chunyu Li, Ziyang Meng
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust geo-localization in changing environmental conditions is critical for long-term aerial autonomy. While visual place recognition (VPR) models perform well when airborne views match the training domain, adapting them to shifting distributions during sequential missions triggers catastrophic forgetting. Existing continual learning (CL) methods often fail here because geographic features exhibit severe intra-class variations. In this work, we formulate aerial VPR as a mission-based domain-incremental learning (DIL) problem and propose a novel heterogeneous memory framework. To respect strict onboard storage constraints, our "Learn-and-Dispose" pipeline decouples geographic knowledge into static satellite anchors (preserving global geometric priors) and a dynamic experience replay buffer (retaining domain-specific features). We introduce a spatially-constrained allocation strategy that optimizes buffer selection based on sample difficulty or feature space diversity. To facilitate systematic assessment, we provide three evaluation criteria and a comprehensive benchmark derived from 21 diverse mission sequences. Extensive experiments demonstrate that our architecture significantly boosts spatial generalization; our diversity-driven buffer selection outperforms the random baseline by 7.8% in knowledge retention. Unlike class-mean preservation methods that fail in unstructured environments, maximizing structural diversity achieves a superior plasticity-stability balance and ensures order-agnostic robustness across randomized sequences. These results prove that maintaining structural feature coverage is more critical than sample difficulty for resolving catastrophic forgetting in lifelong aerial autonomy.
### Title:
          Text-Conditioned Multi-Expert Regression Framework for Fully Automated Multi-Abutment Design
 - **Authors:** Mianjie Zheng, Xinquan Yang, Xuefen Liu, Xuguang Li, Kun Tang, He Meng, Linlin Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dental implant abutments serve as the geometric and biomechanical interface between the implant fixture and the prosthetic crown, yet their design relies heavily on manual effort and is time-consuming. Although deep neural networks have been proposed to assist dentists in designing abutments, most existing approaches remain largely manual or semi-automated, requiring substantial clinician intervention and lacking scalability in multi-abutment scenarios. To address these limitations, we propose TEMAD, a fully automated, text-conditioned multi-expert architecture for multi-abutment design. This framework integrates implant site localization and implant system, compatible abutment parameter regression into a unified pipeline. Specifically, we introduce an Implant Site Identification Network (ISIN) to automatically localize implant sites and provide this information to the subsequent multi-abutment regression network. We further design a Tooth-Conditioned Feature-wise Linear Modulation (TC-FiLM) module, which adaptively calibrates mesh representations using tooth embeddings to enable position-specific feature modulation. Additionally, a System-Prompted Mixture-of-Experts (SPMoE) mechanism leverages implant system prompts to guide expert selection, ensuring system-aware regression. Extensive experiments on a large-scale abutment design dataset show that TEMAD achieves state-of-the-art performance compared to existing methods, particularly in multi-abutment settings, validating its effectiveness for fully automated dental implant planning.
### Title:
          Off-the-shelf Vision Models Benefit Image Manipulation Localization
 - **Authors:** Zhengxuan Zhang, Keji Song, Junmin Hu, Ao Luo, Yuezun Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Multimedia (cs.MM); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Image manipulation localization (IML) and general vision tasks are typically treated as two separate research directions due to the fundamental differences between manipulation-specific and semantic features. In this paper, however, we bridge this gap by introducing a fresh perspective: these two directions are intrinsically connected, and general semantic priors can benefit IML. Building on this insight, we propose a novel trainable adapter (named ReVi) that repurposes existing off-the-shelf general-purpose vision models (e.g., image generation and segmentation networks) for IML. Inspired by robust principal component analysis, the adapter disentangles semantic redundancy from manipulation-specific information embedded in these models and selectively enhances the latter. Unlike existing IML methods that require extensive model redesign and full retraining, our method relies on the off-the-shelf vision models with frozen parameters and only fine-tunes the proposed adapter. The experimental results demonstrate the superiority of our method, showing the potential for scalable IML frameworks.
### Title:
          "Take Me Home, Wi-Fi Drone": A Drone-based Wireless System for Wilderness Search and Rescue
 - **Authors:** Weiying Hou, Luca Jiang-Tao Yu, Chenshu Wu
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Wilderness Search and Rescue (WiSAR) represents a longstanding and critical societal challenge, demanding innovative and automatic technological solutions. In this paper, we introduce Wi2SAR, a novel autonomous drone-based wireless system for long-range, through-occlusion WiSAR operations, without relying on existing infrastructure. Our basic insight is to leverage the automatic reconnection behavior of modern Wi-Fi devices to known networks. By mimicking these networks via on-drone Wi-Fi, Wi2SAR uniquely facilitates the discovery and localization of victims through their accompanying mobile devices. Translating this simple idea into a practical system poses substantial technical challenges. Wi2SAR overcomes these challenges via three distinct innovations: (1) a rapid and energy-efficient device discovery mechanism to discover and identify the target victim, (2) a novel RSS-only, long-range direction finding approach using a 3D-printed Luneburg Lens, amplifying the directional signal strength differences and significantly extending the operational range, and (3) an adaptive drone navigation scheme that guides the drone toward the target efficiently. We implement an end-to-end prototype and evaluate Wi2SAR across various mobile devices and real-world wilderness scenarios. Experimental results demonstrate Wi2SAR's high performance, efficiency, and practicality, highlighting its potential to advance autonomous WiSAR solutions. Wi2SAR is open-sourced at this https URL to facilitate further research and real-world deployment.
### Title:
          Efficient Spatial-Temporal Focal Adapter with SSM for Temporal Action Detection
 - **Authors:** Yicheng Qiu, Keiji Yanai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Temporal human action detection aims to identify and localize action segments within untrimmed videos, serving as a pivotal task in video understanding. Despite the progress achieved by prior architectures like CNN and Transformer models, these continue to struggle with feature redundancy and degraded global dependency modeling capabilities when applied to long video sequences. These limitations severely constrain their scalability in real-world video analysis. State Space Models (SSMs) offer a promising alternative with linear long-term modeling and robust global temporal reasoning capabilities. Rethinking the application of SSMs in temporal modeling, this research constructs a novel framework for video human action detection. Specifically, we introduce the Efficient Spatial-Temporal Focal (ESTF) Adapter into the pre-trained layers. This module integrates the advantages of our proposed Temporal Boundary-aware SSM(TB-SSM) for temporal feature modeling with efficient processing of spatial features. We perform comprehensive and quantitative analyses across multiple benchmarks, comparing our proposed method against previous SSM-based and other structural methods. Extensive experiments demonstrate that our improved strategy significantly enhances both localization performance and robustness, validating the effectiveness of our proposed method.
### Title:
          Characterizing Lidar Range-Measurement Ambiguity due to Multiple Returns
 - **Authors:** Jason H. Rife, Yifan Li
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable position and attitude sensing is critical for highly automated vehicles that operate on conventional roadways. Lidar sensors are increasingly incorporated into pose-estimation systems. Despite its great utility, lidar is a complex sensor, and its performance in roadway environments is not yet well understood. For instance, it is often assumed in lidar-localization algorithms that a lidar will always identify a unique surface along a given raypath. However, this assumption is not always true, as ample prior evidence exists to suggest that lidar units may generate measurements probabilistically when more than one scattering surface appears within the lidar's conical beam. In this paper, we analyze lidar datasets to characterize cases with probabilistic returns along particular raypaths. Our contribution is to present representative cumulative distribution functions (CDFs) for raypaths observed by two different mechanically rotating lidar units with stationary bases. In subsequent discussion, we outline a qualitative methodology to assess the effect of probabilistic multi-return cases on lidar-based localization.
### Title:
          Constraint-Aware Corrective Memory for Language-Based Drug Discovery Agents
 - **Authors:** Maochen Sun, Youzhi Zhang, Gaofeng Meng
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models are making autonomous drug discovery agents increasingly feasible, but reliable success in this setting is not determined by any single action or molecule. It is determined by whether the final returned set jointly satisfies protocol-level requirements such as set size, diversity, binding quality, and developability. This creates a fundamental control problem: the agent plans step by step, while task validity is decided at the level of the whole candidate set. Existing language-based drug discovery systems therefore tend to rely on long raw history and under-specified self-reflection, making failure localization imprecise and planner-facing agent states increasingly noisy. We present CACM (Constraint-Aware Corrective Memory), a language-based drug discovery framework built around precise set-level diagnosis and a concise memory write-back mechanism. CACM introduces protocol auditing and a grounded diagnostician, which jointly analyze multimodal evidence spanning task requirements, pocket context, and candidate-set evidence to localize protocol violations, generate actionable remediation hints, and bias the next action toward the most relevant correction. To keep planning context compact, CACM organizes memory into static, dynamic, and corrective channels and compresses them before write-back, thereby preserving persistent task information while exposing only the most decision-relevant failures. Our experimental results show that CACM improves the target-level success rate by 36.4% over the state-of-the-art baseline. The results show that reliable language-based drug discovery benefits not only from more powerful molecular tools, but also from more precise diagnosis and more economical agent states.
### Title:
          From Frames to Events: Rethinking Evaluation in Human-Centric Video Anomaly Detection
 - **Authors:** Narges Rashvand, Shanle Yao, Armin Danesh Pazho, Babak Rahimi Ardabili, Hamed Tabkhi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pose-based Video Anomaly Detection (VAD) has gained significant attention for its privacy-preserving nature and robustness to environmental variations. However, traditional frame-level evaluations treat video as a collection of isolated frames, fundamentally misaligned with how anomalies manifest and are acted upon in the real world. In operational surveillance systems, what matters is not the flagging of individual frames, but the reliable detection, localization, and reporting of a coherent anomalous event, a contiguous temporal episode with an identifiable onset and duration. Frame-level metrics are blind to this distinction, and as a result, they systematically overestimate model performance for any deployment that requires actionable, event-level alerts. In this work, we propose a shift toward an event-centric perspective in VAD. We first audit widely used VAD benchmarks, including SHT[19], CHAD[6], NWPUC[4], and HuVAD[25], to characterize their event structure. We then introduce two strategies for temporal event localization: a score-refinement pipeline with hierarchical Gaussian smoothing and adaptive binarization, and an end-to-end Dual-Branch Model that directly generates event-level detections. Finally, we establish the first event-based evaluation standard for VAD by adapting Temporal Action Localization metrics, including tIoU-based event matching and multi-threshold F1 evaluation. Our results quantify a substantial performance gap: while all SoTA models achieve frame-level AUC-ROC exceeding 52% on the NWPUC[4], their event-level localization precision falls below 10% even at a minimal tIoU=0.2, with an average event-level F1 of only 0.11 across all thresholds. The code base for this work is available at this https URL.
### Title:
          AsymLoc: Towards Asymmetric Feature Matching for Efficient Visual Localization
 - **Authors:** Mohammad Omama, Gabriele Berton, Eric Foxlin, Yelin Kim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Precise and real-time visual localization is critical for applications like AR/VR and robotics, especially on resource-constrained edge devices such as smart glasses, where battery life and heat dissipation can be a primary concerns. While many efficient models exist, further reducing compute without sacrificing accuracy is essential for practical deployment. To address this, we propose asymmetric visual localization: a large Teacher model processes pre-mapped database images offline, while a lightweight Student model processes the query image online. This creates a challenge in matching features from two different models without resorting to heavy, learned matchers. We introduce AsymLoc, a novel distillation framework that aligns a Student to its Teacher through a combination of a geometry-driven matching objective and a joint detector-descriptor distillation objective, enabling fast, parameter-less nearest-neighbor matching. Extensive experiments on HPatches, ScanNet, IMC2022, and Aachen show that AsymLoc achieves up to 95% of the teacher's localization accuracy using an order of magnitude smaller models, significantly outperforming existing baselines and establishing a new state-of-the-art efficiency-accuracy trade-off.
### Title:
          Physics-Informed Reinforcement Learning of Spatial Density Velocity Potentials for Map-Free Racing
 - **Authors:** Shathushan Sivashangaran, Apoorva Khairnar, Sepideh Gohari, Vihaan Dutta, Azim Eskandarian
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous racing without prebuilt maps is a grand challenge for embedded robotics that requires kinodynamic planning from instantaneous sensor data at the acceleration and tire friction limits. Out-Of-Distribution (OOD) generalization to various racetrack configurations utilizes Machine Learning (ML) to encode the mathematical relation between sensor data and vehicle actuation for end-to-end control, with implicit localization. These comprise Behavioral Cloning (BC) that is capped to human reaction times and Deep Reinforcement Learning (DRL) which requires large-scale collisions for comprehensive training that can be infeasible without simulation but is arduous to transfer to reality, thus exhibiting greater performance than BC in simulation, but actuation instability on hardware. This paper presents a DRL method that parameterizes nonlinear vehicle dynamics from the spectral distribution of depth measurements with a non-geometric, physics-informed reward, to infer vehicle time-optimal and overtaking racing controls with an Artificial Neural Network (ANN) that utilizes less than 1% of the computation of BC and model-based DRL. Slaloming from simulation to reality transfer and variance-induced conservatism are eliminated with the combination of a physics engine exploit-aware reward and the replacement of an explicit collision penalty with an implicit truncation of the value horizon. The policy outperforms human demonstrations by 12% in OOD tracks on proportionally scaled hardware, by maximizing the friction circle with tire dynamics that resemble an empirical Pacejka tire model. System identification illuminates a functional bifurcation where the first layer compresses spatial observations to extract digitized track features with higher resolution in corner apexes, and the second encodes nonlinear dynamics.
## Keyword: transformer
### Title:
          Dynamic sparsity in tree-structured feed-forward layers at scale
 - **Authors:** Reza Sedghi, Robin Schiewer, Anand Subramoney, David Kappel
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 At typical context lengths, the feed-forward MLP block accounts for a large share of a transformer's compute budget, motivating sparse alternatives to dense MLP blocks. We study sparse, tree-structured feed-forward layers as drop-in replacements for MLP blocks in deep transformer architectures, enabling conditional computation via hard hierarchical routing without a separate router network. We demonstrate for the first time that this form of tree-structured conditional sparsity can be applied for autoregressive language modeling and downstream question answering, including zero- and few-shot settings, and its scalability beyond 1B parameters. Despite activating fewer than 5% of the feed-forward block's units per token, our models match dense baselines under controlled training and fine-tuning protocols. We further analyze training dynamics and identify an emergent auto-pruning effect: the interaction of hard routing with asymmetric nonlinearities progressively deactivates unused paths, yielding partial conversion of dynamic routing into static structural sparsity. We show that simple architectural choices can modulate this behavior and recover balanced trees without auxiliary losses. Overall, our work demonstrates that tree-structured feed-forward layers provide a scalable and controllable mechanism for sparsifying large transformer models.
### Title:
          QCFuse: Query-Centric Cache Fusion for Efficient RAG Inference
 - **Authors:** Jianxin Yan, Zeheng Qian, Wangze Ni, Zhitao Shen, Zhiping Wang, Haoyang Li, Jia Zhu, Lei Chen, Kui Ren
 - **Subjects:** Subjects:
Databases (cs.DB); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cache fusion accelerates generation process of LLMs equipped with RAG through KV caching and selective token recomputation, thereby reducing computational costs and improving efficiency. However, existing methods primarily rely on local perspectives for token selection and lack global awareness from the user query. Utilizing this global awareness is challenging due to the high cost of obtaining context-aware query representations and the strict pipeline constraints required for efficient attention analysis. Thus, this demonstration introduces QCFuse, an innovative KV cache fusion system centered on the user query. QCFuse leverages semantic summary anchors to enhance query representations and selectively recomputes query-related tokens to improve accuracy, updating tokens based on the attention distribution of the most critical Transformer layer to preserve the high efficiency of the pipeline structure. Evaluations on real-world datasets demonstrate that QCFuse significantly improves the response efficiency of LLMs by 40\% while maintaining equivalent accuracy compared to current methods. Additionally, in certain scenarios, QCFuse achieves an attention denoising effect that yields higher response accuracy, demonstrating substantial potential in the optimization of LLM inference.
### Title:
          FluidFlow: a flow-matching generative model for fluid dynamics surrogates on unstructured meshes
 - **Authors:** David Ramos, Lucas Lacasa, Fermín Gutiérrez, Eusebio Valero, Gonzalo Rubio
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Fluid Dynamics (physics.flu-dyn)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Computational fluid dynamics (CFD) provides high-fidelity simulations of fluid flows but remains computationally expensive for many-query applications. In recent years deep learning (DL) has been used to construct data-driven fluid-dynamic surrogate models. In this work we consider a different learning paradigm and embrace generative modelling as a framework for constructing scalable fluid-dynamics surrogate models. We introduce FluidFlow, a generative model based on conditional flow-matching, a recent alternative to diffusion models that learns deterministic transport maps between noise and data distributions. FluidFlow is specifically designed to operate directly on CFD data defined on both structured and unstructured meshes alike, without the needs to perform any mesh interpolation pre-processing and preserving geometric fidelity. We assess the capabilities of FluidFlow using two different core neural network architectures, a U-Net and diffusion transformer (DiT), and condition their learning on physically meaningful parameters. The methodology is validated on two benchmark problems of increasing complexity: prediction of pressure coefficients along an airfoil boundary across different operating conditions, and prediction of pressure and friction coefficients over a full three-dimensional aircraft geometry discretized on a large unstructured mesh. In both cases, FluidFlow outperform strong multilayer perceptron baselines, achieving significantly lower error metrics and improved generalisation across operating conditions. Notably, the transformer-based architecture enables scalable learning on large unstructured datasets while maintaining high predictive accuracy. These results demonstrate that flow-matching generative models provide an effective and flexible framework for surrogate modelling in fluid dynamics, with potential for realistic engineering and scientific applications.
### Title:
          Detection of Hate and Threat in Digital Forensics: A Case-Driven Multimodal Approach
 - **Authors:** Ponkoj Chandra Shill
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Digital forensic investigations increasingly rely on heterogeneous evidence such as images, scanned documents, and contextual reports. These artifacts may contain explicit or implicit expressions of harm, hate, threat, violence, or intimidation, yet existing automated approaches often assume clean text input or apply vision models without forensic justification. This paper presents a case-driven multimodal approach for hate and threat detection in forensic analysis. The proposed framework explicitly determines the presence and source of textual evidence, distinguishing between embedded text, associated contextual text, and image-only evidence. Based on the identified evidence configuration, the framework selectively applies text analysis, multimodal fusion, or image-only semantic reasoning using vision language models with vision transformer backbones (ViT). By conditioning inference on evidence availability, the approach mirrors forensic decision-making, improves evidentiary traceability, and avoids unjustified modality assumptions. Experimental evaluation on forensic-style image evidence demonstrates consistent and interpretable behavior across heterogeneous evidence scenarios.
### Title:
          PRAGMA: Revolut Foundation Model
 - **Authors:** Maxim Ostroukhov, Ruslan Mikhailov, Vladimir Iashin, Artem Sokolov, Andrei Akshonov, Vitaly Protasov, Dmitrii Beloborodov, Vince Mullin, Roman Yokunda Enzmann, Georgios Kolovos, Jason Renders, Pavel Nesterov, Anton Repushko
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computational Engineering, Finance, and Science (cs.CE); Computation and Language (cs.CL); Information Retrieval (cs.IR); Computational Finance (q-fin.CP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern financial systems generate vast quantities of transactional and event-level data that encode rich economic signals. This paper presents PRAGMA, a family of foundation models for multi-source banking event sequences. Our approach pre-trains a Transformer-based architecture with masked modelling on a large-scale, heterogeneous banking event corpus using a self-supervised objective tailored to the discrete, variable-length nature of financial records. The resulting model supports a wide range of downstream tasks such as credit scoring, fraud detection, and lifetime value prediction: strong performance can be achieved by training a simple linear model on top of the extracted embeddings and can be further improved with lightweight fine-tuning. Through extensive evaluation on downstream tasks, we demonstrate that PRAGMA achieves superior performance across multiple domains directly from raw event sequences, providing a general-purpose representation layer for financial applications.
### Title:
          Deep Learning-Based Tracking and Lineage Reconstruction of Ligament Breakup
 - **Authors:** Vrushank Ahire, Vivek Kurumanghat, Mudasir Ganaie, Lipika Kabiraj
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The disintegration of liquid sheets into ligaments and droplets involves highly transient, multi-scale dynamics that are difficult to quantify from high-speed shadowgraphy images. Identifying droplets, ligaments, and blobs formed during breakup, along with tracking across frames, is essential for spray analysis. However, conventional multi-object tracking frameworks impose strict one-to-one temporal associations and cannot represent one-to-many fragmentation events. In this study, we present a two-stage deep learning framework for object detection and temporal relationship modeling across frames. The framework captures ligament deformation, fragmentation, and parent-child lineage during liquid sheet disintegration. In the first stage, a Faster R-CNN with a ResNet-50 backbone and Feature Pyramid Network detects and classifies ligaments and droplets in high-speed shadowgraphy recordings of an impinging Carbopol gel jet. A morphology-preserving synthetic data generation strategy augments the training set without introducing physically implausible configurations, achieving a held-out F1 score of up to 0.872 across fourteen original-to-synthetic configurations. In the second stage, a Transformer-augmented multilayer perceptron classifies inter-frame associations into continuation, fragmentation (one-to-many), and non-association using physics-informed geometric features. Despite severe class imbalance, the model achieves 86.1% accuracy, 93.2% precision, and perfect recall (1.00) for fragmentation events. Together, the framework enables automated reconstruction of fragmentation trees, preservation of parent-child lineage, and extraction of breakup statistics such as fragment multiplicity and droplet size distributions. By explicitly identifying children droplets formed from ligament fragmentation, the framework provides automated analysis of the primary atomization mode.
### Title:
          A Little Rank Goes a Long Way: Random Scaffolds with LoRA Adapters Are All You Need
 - **Authors:** Hananel Hazan, Yanbo Zhang, Benedikt Hartl, Michael Levin
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 How many of a neural network's parameters actually encode task-specific information? We investigate this question with LottaLoRA, a training paradigm in which every backbone weight is drawn at random and frozen; only low-rank LoRA adapters are trained. Across nine benchmarks spanning diverse architecture families from single-layer classifiers to 900M parameter Transformers low-rank adapters over frozen random backbones recover 96-100% of fully trained performance while training only 0.5-40% of the parameters. The task-specific signal therefore occupies a subspace orders of magnitude smaller than the full parameter count this http URL mechanistic findings underpin this result:(1) the frozen backbone is actively exploited when static the learned scaling~$\beta$ remains strictly positive across all architectures but when the scaffold is destabilized, the optimizer silences it and the LoRA factors absorb all task information; (2) the frozen backbone is preferable but interchangeable any random initialization works equally well, provided it remains fixed throughout training; and (3) the minimum LoRA rank at which performance saturates estimates the intrinsic dimensionality of the task, reminiscent of the number of components retained in Principal Component Analysis (PCA). The construction is formally analogous to Reservoir Computing unfolded along the depth axis of a feedforward network. Because the backbone is determined by a random seed alone, models can be distributed as adapters plus seed a footprint that grows with task complexity, not model size, so that storage and memory savings compound as architectures scale.
### Title:
          Revisiting Anisotropy in Language Transformers: The Geometry of Learning Dynamics
 - **Authors:** Raphael Bernas, Fanny Jourdan, Antonin Poché, Céline Hudelot
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Differential Geometry (math.DG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Since their introduction, Transformer architectures have dominated Natural Language Processing (NLP). However, recent research has highlighted an inherent anisotropy phenomenon in these models, presenting a significant challenge to their geometric interpretation. Previous theoretical studies on this phenomenon are rarely grounded in the underlying representation geometry. In this paper, we extend them by deriving geometric arguments for how frequency-biased sampling attenuates curvature visibility and why training preferentially amplify tangent directions. Empirically, we then use concept-based mechanistic interpretability during training, rather than only post hoc, to fit activation-derived low-rank tangent proxies and test them against ordinary backpropagated true gradients. Across encoder-style and decoder-style language models, we find that these activation-derived directions capture both unusually large gradient energy and a substantially larger share of gradient anisotropy than matched-rank normal controls, providing strong empirical support for a tangent-aligned account of anisotropy.
### Title:
          Tracing the Chain: Deep Learning for Stepping-Stone Intrusion Detection
 - **Authors:** Nate Mathews, Nicholas Hopper, Matthew Wright
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Stepping-stone intrusions (SSIs) are a prevalent network evasion technique in which attackers route sessions through chains of compromised intermediate hosts to obscure their origin. Effective SSI detection requires correlating the incoming and outgoing flows at each relay host at extremely low false positive rates -- a stringent requirement that renders classical statistical methods inadequate in operational settings. We apply ESPRESSO, a deep learning flow correlation model combining a transformer-based feature extraction network, time-aligned multi-channel interval features, and online triplet metric learning, to the problem of stepping-stone intrusion detection. To support training and evaluation, we develop a synthetic data collection tool that generates realistic stepping-stone traffic across five tunneling protocols: SSH, SOCAT, ICMP, DNS, and mixed multi-protocol chains. Across all five protocols and in both host-mode and network-mode detection scenarios, ESPRESSO substantially outperforms the state-of-the-art DeepCoFFEA baseline, achieving a true positive rate exceeding 0.99 at a false positive rate of $10^{-3}$ for standard bursty protocols in network-mode. We further demonstrate chain length prediction as a tool for distinguishing malicious from benign pivoting, and conduct a systematic robustness analysis revealing that timing-based perturbations are the primary vulnerability of correlation-based stepping-stone detectors.
### Title:
          Loom: A Scalable Analytical Neural Computer Architecture
 - **Authors:** Mehmet Kerem Turkcan
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Loom, a computer architecture that executes programs compiled from C inside a looped transformer whose weights are derived analytically. The architecture implements a 22-opcode instruction set in 8 transformer layers. Each forward pass executes one instruction; the model is applied iteratively until the program counter reaches zero. The full machine state resides in a single tensor $X \in \mathbb{R}^{d \times n}$ of fixed size, and every step has fixed cost for fixed $d$ and $n$, independent of program length or execution history. The default configuration uses $d = 155$ and $n = 1024$, yielding 4.7 million parameters and 928 instruction slots. A compact configuration at $d = 146$ and $n = 512$ suffices for a 9$\times$9 Sudoku solver (284 instructions). The weights are program-independent: programs live in the state tensor, and the same fixed-weight model executes any compiled program. We make Loom source code publicly available at this https URL.
### Title:
          Hierarchical Kernel Transformer: Multi-Scale Attention with an Information-Theoretic Approximation Analysis
 - **Authors:** Giansalvo Cirrincione
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Neural and Evolutionary Computing (cs.NE); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Hierarchical Kernel Transformer (HKT) is a multi-scale attention mechanism that processes sequences at L resolution levels via trainable causal downsampling, combining level-specific score matrices through learned convex weights. The total computational cost is bounded by 4/3 times that of standard attention, reaching 1.3125x for L = 3. Four theoretical results are established. (i) The hierarchical score matrix defines a positive semidefinite kernel under a sufficient condition on the symmetrised bilinear form (Proposition 3.1). (ii) The asymmetric score matrix decomposes uniquely into a symmetric part controlling reciprocal attention and an antisymmetric part controlling directional attention; HKT provides L independent such pairs across scales, one per resolution level (Propositions 3.5-3.6). (iii) The approximation error decomposes into three interpretable components with an explicit non-Gaussian correction and a geometric decay bound in L (Theorem 4.3, Proposition 4.4). (iv) HKT strictly subsumes single-head standard attention and causal convolution (Proposition 3.4). Experiments over 3 random seeds show consistent gains over retrained standard attention baselines: +4.77pp on synthetic ListOps (55.10+-0.29% vs 50.33+-0.12%, T = 512), +1.44pp on sequential CIFAR-10 (35.45+-0.09% vs 34.01+-0.19%, T = 1,024), and +7.47pp on IMDB character-level sentiment (70.19+-0.57% vs 62.72+-0.40%, T = 1,024), all at 1.31x overhead.
### Title:
          Uncertainty-Aware Transformers: Conformal Prediction for Language Models
 - **Authors:** Abhiram Vellore, Niraj K. Jha
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers have had a profound impact on the field of artificial intelligence, especially on large language models and their variants. However, as was the case with neural networks, their black-box nature limits trust and deployment in high-stakes settings. For models to be genuinely useful and trustworthy in critical applications, they must provide more than just predictions: they must supply users with a clear understanding of the reasoning that underpins their decisions. This article presents an uncertainty quantification framework for transformer-based language models. This framework, called CONFIDE (CONformal prediction for FIne-tuned DEep language models), applies conformal prediction to the internal embeddings of encoder-only architectures, like BERT and RoBERTa, while enabling hyperparameter tuning. CONFIDE uses either [CLS] token embeddings or flattened hidden states to construct class-conditional nonconformity scores, enabling statistically valid prediction sets with instance-level explanations. Empirically, CONFIDE improves test accuracy by up to 4.09% on BERT-tiny and achieves greater correct efficiency (i.e., the expected size of the prediction set conditioned on it containing the true label) compared to prior methods, including NM2 and VanillaNN. We show that early and intermediate transformer layers often yield better-calibrated and more semantically meaningful representations for conformal prediction. In resource-constrained models and high-stakes tasks with ambiguous labels, CONFIDE offers robustness and interpretability where softmax-based uncertainty fails. We position CONFIDE as a framework for practical diagnostic and efficiency/robustness improvement over prior conformal baselines.
### Title:
          Ge$^\text{2}$mS-T: Multi-Dimensional Grouping for Ultra-High Energy Efficiency in Spiking Transformer
 - **Authors:** Zecheng Hao, Shenghao Xie, Kang Chen, Wenxuan Liu, Zhaofei Yu, Tiejun Huang
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spiking Neural Networks (SNNs) offer superior energy efficiency over Artificial Neural Networks (ANNs). However, they encounter significant deficiencies in training and inference metrics when applied to Spiking Vision Transformers (S-ViTs). Existing paradigms including ANN-SNN Conversion and Spatial-Temporal Backpropagation (STBP) suffer from inherent limitations, precluding concurrent optimization of memory, accuracy and energy consumption. To address these issues, we propose Ge$^\text{2}$mS-T, a novel architecture implementing grouped computation across temporal, spatial and network structure dimensions. Specifically, we introduce the Grouped-Exponential-Coding-based IF (ExpG-IF) model, enabling lossless conversion with constant training overhead and precise regulation for spike patterns. Additionally, we develop Group-wise Spiking Self-Attention (GW-SSA) to reduce computational complexity via multi-scale token grouping and multiplication-free operations within a hybrid attention-convolution framework. Experiments confirm that our method can achieve superior performance with ultra-high energy efficiency on challenging benchmarks. To our best knowledge, this is the first work to systematically establish multi-dimensional grouped computation for resolving the triad of memory overhead, learning capability and energy budget in S-ViTs.
### Title:
          Neighbourhood Transformer: Switchable Attention for Monophily-Aware Graph Learning
 - **Authors:** Yi Luo, Xu Sun, Guangchun Luo, Aiguo Chen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Graph neural networks (GNNs) have been widely adopted in engineering applications such as social network analysis, chemical research and computer vision. However, their efficacy is severely compromised by the inherent homophily assumption, which fails to hold for heterophilic graphs where dissimilar nodes are frequently connected. To address this fundamental limitation in graph learning, we first draw inspiration from the recently discovered monophily property of real-world graphs, and propose Neighbourhood Transformers (NT), a novel paradigm that applies self-attention within every local neighbourhood instead of aggregating messages to the central node as in conventional message-passing GNNs. This design makes NT inherently monophily-aware and theoretically guarantees its expressiveness is no weaker than traditional message-passing frameworks. For practical engineering deployment, we further develop a neighbourhood partitioning strategy equipped with switchable attentions, which reduces the space consumption of NT by over 95% and time consumption by up to 92.67%, significantly expanding its applicability to larger graphs. Extensive experiments on 10 real-world datasets (5 heterophilic and 5 homophilic graphs) show that NT outperforms all current state-of-the-art methods on node classification tasks, demonstrating its superior performance and cross-domain adaptability. The full implementation code of this work is publicly available at this https URL to facilitate reproducibility and industrial adoption.
### Title:
          Identification and Anonymization of Named Entities in Unstructured Information Sources for Use in Social Engineering Detection
 - **Authors:** Carlos Jimeno Miguel, Raul Orduna, Francesco Zola
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This study addresses the challenge of creating datasets for cybercrime analysis while complying with the requirements of regulations such as the General Data Protection Regulation (GDPR) and Organic Law 10/1995 of the Penal Code. To this end, a system is proposed for collecting information from the Telegram platform, including text, audio, and images; the implementation of speech-to-text transcription models incorporating signal enhancement techniques; and the evaluation of different Named Entity Recognition (NER) solutions, including Microsoft Presidio and AI models designed using a transformer-based architecture. Experimental results indicate that Parakeet achieves the best performance in audio transcription, while the proposed NER solutions achieve the highest f1-score values in detecting sensitive information. In addition, anonymization metrics are presented that allow evaluation of the preservation of structural coherence in the data, while simultaneously guaranteeing the protection of personal information and supporting cybersecurity research within the current legal framework.
### Title:
          AccompGen: Hierarchical Autoregressive Vocal Accompaniment Generation with Dual-Rate Codec Tokenization
 - **Authors:** Jian Zhu, Jianwei Cui, Shihao Chen, Yubang Zhang, Cheng Luo
 - **Subjects:** Subjects:
Sound (cs.SD); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present AccompGen, a system that generates instrumental music audio to accompany input vocals. Given isolated singing voice, AccompGen produces a coherent instrumental accompaniment that can be directly mixed with the input to create complete music. We propose three key innovations over prior work: (1) a dual-rate codec tokenization scheme using HuBERT semantic tokens at 50,Hz for vocals and EnCodec acoustic tokens at 75,Hz for instrumentals, enabling time-aligned yet rate-independent modeling; (2) a three-stage hierarchical autoregressive architecture (semantic to coarse acoustic to fine acoustic) with interleaved multi-codebook prediction and classifier-free guidance; and (3) modern Transformer design choices including QK-norm, GEGLU activations, RMSNorm, and T5-style relative position bias for improved training stability and sequence generalization.
### Title:
          DeepGuard: Secure Code Generation via Multi-Layer Semantic Aggregation
 - **Authors:** Li Huang, Zhongxin Liu, Yifan Wu, Tao Yin, Dong Li, Jichao Bi, Nankun Mu, Hongyu Zhang, Meng Yan
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) for code generation can replicate insecure patterns from their training data. To mitigate this, a common strategy for security hardening is to fine-tune models using supervision derived from the final transformer layer. However, this design may suffer from a final-layer bottleneck: vulnerability-discriminative cues can be distributed across layers and become less detectable near the output representations optimized for next-token prediction. To diagnose this issue, we perform layer-wise linear probing. We observe that vulnerability-related signals are most detectable in a band of intermediate-to-upper layers yet attenuate toward the final layers. Motivated by this observation, we introduce DeepGuard, a framework that leverages distributed security-relevant cues by aggregating representations from multiple upper layers via an attention-based module. The aggregated signal powers a dedicated security analyzer within a multi-objective training objective that balances security enhancement and functional correctness, and further supports a lightweight inference-time steering strategy. Extensive experiments across five code LLMs demonstrate that DeepGuard improves the secure-and-correct generation rate by an average of 11.9% over strong baselines such as SVEN. It also preserves functional correctness while exhibiting generalization to held-out vulnerability types. Our code is public at this https URL.
### Title:
          Detecting Diffusion-generated Images via Dynamic Assembly ForestsDetecting Diffusion-generated Images via Dynamic Assembly Forests
 - **Authors:** Mengxin Fu, Yuezun Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion models are known for generating high-quality images, causing serious security concerns. To combat this, most efforts rely on deep neural networks (e.g., CNNs and Transformers), while largely overlooking the potential of traditional machine learning models. In this paper, we freshly investigate such alternatives and proposes a novel Dynamic Assembly Forest model (DAF) to detect diffusion-generated images. Built upon the deep forest paradigm, DAF addresses the inherent limitations in feature learning and scalable training, making it an effective diffusion-generated image detector. Compared to existing DNN-based methods, DAF has significantly fewer parameters, much lower computational cost, and can be deployed without GPUs, while achieving competitive performance under standard evaluation protocols. These results highlight the strong potential of the proposed method as a practical substitute for heavyweight DNN models in resource-constrained scenarios. Our code and models are available at this https URL.
### Title:
          FaceLiVTv2: An Improved Hybrid Architecture for Efficient Mobile Face Recognition
 - **Authors:** Novendra Setyawan, Chi-Chia Sun, Mao-Hsiu Hsu, Wen-Kai Kuo, Jun-Wei Hsieh
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Lightweight face recognition is increasingly important for deployment on edge and mobile devices, where strict constraints on latency, memory, and energy consumption must be met alongside reliable accuracy. Although recent hybrid CNN-Transformer architectures have advanced global context modeling, striking an effective balance between recognition performance and computational efficiency remains an open challenge. In this work, we present FaceLiVTv2, an improved version of our FaceLiVT hybrid architecture designed for efficient global--local feature interaction in mobile face recognition. At its core is Lite MHLA, a lightweight global token interaction module that replaces the original multi-layer attention design with multi-head linear token projections and affine rescale transformations, reducing redundancy while preserving representational diversity across heads. We further integrate Lite MHLA into a unified RepMix block that coordinates local and global feature interactions and adopts global depthwise convolution for adaptive spatial aggregation in the embedding stage. Under our experimental setup, results on LFW, CA-LFW, CP-LFW, CFP-FP, AgeDB-30, and IJB show that FaceLiVTv2 consistently improves the accuracy-efficiency trade-off over existing lightweight methods. Notably, FaceLiVTv2 reduces mobile inference latency by 22% relative to FaceLiVTv1, achieves speedups of up to 30.8% over GhostFaceNets on mobile devices, and delivers 20-41% latency improvements over EdgeFace and KANFace across platforms while maintaining higher recognition accuracy. These results demonstrate that FaceLiVTv2 offers a practical and deployable solution for real-time face recognition. Code is available at this https URL.
### Title:
          EquiformerV3: Scaling Efficient, Expressive, and General SE(3)-Equivariant Graph Attention Transformers
 - **Authors:** Yi-Lun Liao, Alexander J. Hoffman, Sabrina C. Shen, Alexandre Duval, Sam Walton Norwood, Tess Smidt
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computational Physics (physics.comp-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As $SE(3)$-equivariant graph neural networks mature as a core tool for 3D atomistic modeling, improving their efficiency, expressivity, and physical consistency has become a central challenge for large-scale applications. In this work, we introduce EquiformerV3, the third generation of the $SE(3)$-equivariant graph attention Transformer, designed to advance all three dimensions: efficiency, expressivity, and generality. Building on EquiformerV2, we have the following three key advances. First, we optimize the software implementation, achieving $1.75\times$ speedup. Second, we introduce simple and effective modifications to EquiformerV2, including equivariant merged layer normalization, improved feedforward network hyper-parameters, and attention with smooth radius cutoff. Third, we propose SwiGLU-$S^2$ activations to incorporate many-body interactions for better theoretical expressivity and to preserve strict equivariance while reducing the complexity of sampling $S^2$ grids. Together, SwiGLU-$S^2$ activations and smooth-cutoff attention enable accurate modeling of smoothly varying potential energy surfaces (PES), generalizing EquiformerV3 to tasks requiring energy-conserving simulations and higher-order derivatives of PES. With these improvements, EquiformerV3 trained with the auxiliary task of denoising non-equilibrium structures (DeNS) achieves state-of-the-art results on OC20, OMat24, and Matbench Discovery.
### Title:
          Strips as Tokens: Artist Mesh Generation with Native UV Segmentation
 - **Authors:** Rui Xu, Dafei Qin, Kaichun Qiao, Qiujie Dong, Huaijin Pi, Qixuan Zhang, Longwen Zhang, Lan Xu, Jingyi Yu, Wenping Wang, Taku Komura
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computational Geometry (cs.CG); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advancements in autoregressive transformers have demonstrated remarkable potential for generating artist-quality meshes. However, the token ordering strategies employed by existing methods typically fail to meet professional artist standards, where coordinate-based sorting yields inefficiently long sequences, and patch-based heuristics disrupt the continuous edge flow and structural regularity essential for high-quality modeling. To address these limitations, we propose Strips as Tokens (SATO), a novel framework with a token ordering strategy inspired by triangle strips. By constructing the sequence as a connected chain of faces that explicitly encodes UV boundaries, our method naturally preserves the organized edge flow and semantic layout characteristic of artist-created meshes. A key advantage of this formulation is its unified representation, enabling the same token sequence to be decoded into either a triangle or quadrilateral mesh. This flexibility facilitates joint training on both data types: large-scale triangle data provides fundamental structural priors, while high-quality quad data enhances the geometric regularity of the outputs. Extensive experiments demonstrate that SATO consistently outperforms prior methods in terms of geometric quality, structural coherence, and UV segmentation.
### Title:
          Benchmarking CNN- and Transformer-Based Models for Surgical Instrument Segmentation in Robotic-Assisted Surgery
 - **Authors:** Sara Ameli
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Pattern Formation and Solitons (nlin.PS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate segmentation of surgical instruments in robotic-assisted surgery is critical for enabling context-aware computer-assisted interventions, such as tool tracking, workflow analysis, and autonomous decision-making. In this study, we benchmark five deep learning architectures-UNet, UNet, DeepLabV3, Attention UNet, and SegFormer on the SAR-RARP50 dataset for multi-class semantic segmentation of surgical instruments in real-world radical prostatectomy videos. The models are trained with a compound loss function combining Cross Entropy and Dice loss to address class imbalance and capture fine object boundaries. Our experiments reveal that while convolutional models such as UNet and Attention UNet provide strong baseline performance, DeepLabV3 achieves results comparable to SegFormer, demonstrating the effectiveness of atrous convolution and multi-scale context aggregation in capturing complex surgical scenes. Transformer-based architectures like SegFormer further enhance global contextual understanding, leading to improved generalization across varying instrument appearances and surgical conditions. This work provides a comprehensive comparison and practical insights for selecting segmentation models in surgical AI applications, highlighting the trade-offs between convolutional and transformer-based approaches.
### Title:
          Efficient Spatial-Temporal Focal Adapter with SSM for Temporal Action Detection
 - **Authors:** Yicheng Qiu, Keiji Yanai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Temporal human action detection aims to identify and localize action segments within untrimmed videos, serving as a pivotal task in video understanding. Despite the progress achieved by prior architectures like CNN and Transformer models, these continue to struggle with feature redundancy and degraded global dependency modeling capabilities when applied to long video sequences. These limitations severely constrain their scalability in real-world video analysis. State Space Models (SSMs) offer a promising alternative with linear long-term modeling and robust global temporal reasoning capabilities. Rethinking the application of SSMs in temporal modeling, this research constructs a novel framework for video human action detection. Specifically, we introduce the Efficient Spatial-Temporal Focal (ESTF) Adapter into the pre-trained layers. This module integrates the advantages of our proposed Temporal Boundary-aware SSM(TB-SSM) for temporal feature modeling with efficient processing of spatial features. We perform comprehensive and quantitative analyses across multiple benchmarks, comparing our proposed method against previous SSM-based and other structural methods. Extensive experiments demonstrate that our improved strategy significantly enhances both localization performance and robustness, validating the effectiveness of our proposed method.
### Title:
          ELT: Elastic Looped Transformers for Visual Generation
 - **Authors:** Sahil Goyal, Swayam Agrawal, Gautham Govind Anil, Prateek Jain, Sujoy Paul, Aditya Kusupati
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Elastic Looped Transformers (ELT), a highly parameter-efficient class of visual generative models based on a recurrent transformer architecture. While conventional generative models rely on deep stacks of unique transformer layers, our approach employs iterative, weight-shared transformer blocks to drastically reduce parameter counts while maintaining high synthesis quality. To effectively train these models for image and video generation, we propose the idea of Intra-Loop Self Distillation (ILSD), where student configurations (intermediate loops) are distilled from the teacher configuration (maximum training loops) to ensure consistency across the model's depth in a single training step. Our framework yields a family of elastic models from a single training run, enabling Any-Time inference capability with dynamic trade-offs between computational cost and generation quality, with the same parameter count. ELT significantly shifts the efficiency frontier for visual synthesis. With $4\times$ reduction in parameter count under iso-inference-compute settings, ELT achieves a competitive FID of $2.0$ on class-conditional ImageNet $256 \times 256$ and FVD of $72.8$ on class-conditional UCF-101.
### Title:
          UniSemAlign: Text-Prototype Alignment with a Foundation Encoder for Semi-Supervised Histopathology Segmentation
 - **Authors:** Le-Van Thai, Tien Dat Nguyen, Hoai Nhan Pham, Lan Anh Dinh Thi, Duy-Dong Nguyen, Ngoc Lam Quang Bui
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semi-supervised semantic segmentation in computational pathology remains challenging due to scarce pixel-level annotations and unreliable pseudo-label supervision. We propose UniSemAlign, a dual-modal semantic alignment framework that enhances visual segmentation by injecting explicit class-level structure into pixel-wise learning. Built upon a pathology-pretrained Transformer encoder, UniSemAlign introduces complementary prototype-level and text-level alignment branches in a shared embedding space, providing structured guidance that reduces class ambiguity and stabilizes pseudo-label refinement. The aligned representations are fused with visual predictions to generate more reliable supervision for unlabeled histopathology images. The framework is trained end-to-end with supervised segmentation, cross-view consistency, and cross-modal alignment objectives. Extensive experiments on the GlaS and CRAG datasets demonstrate that UniSemAlign substantially outperforms recent semi-supervised baselines under limited supervision, achieving Dice improvements of up to 2.6% on GlaS and 8.6% on CRAG with only 10% labeled data, and strong improvements at 20% supervision. Code is available at: this https URL
### Title:
          Generalization and Scaling Laws for Mixture-of-Experts Transformers
 - **Authors:** Mansour Zoubeirou a Mayaki
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Statistics Theory (math.ST); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We develop a theory of generalization and scaling for Mixture-of-Experts (MoE) Transformers that cleanly separates \emph{active} per-input capacity from routing combinatorics. By conditioning on fixed routing patterns and union-bounding across them, we derive a sup-norm covering-number bound whose metric entropy scales with the active parameter budget and incurs a MoE-specific routing overhead. Combined with a standard ERM analysis for squared loss, this yields a generalization bound under a $d$-dimensional manifold data model and $C^\beta$ targets, showing that approximation and estimation trade off as in dense networks once active parameters are accounted for appropriately. We further prove a constructive approximation theorem for MoE architectures, showing that, under the approximation construction, error can decrease either by scaling active capacity or by increasing the number of experts, depending on the dominant bottleneck. From these results we derive neural scaling laws for model size, data size, and compute-optimal tradeoffs. Overall, our results provide a transparent statistical reference point for reasoning about MoE scaling, clarifying which behaviors are certified by worst-case theory and which must arise from data-dependent routing structure or optimization dynamics.
### Title:
          Vision Transformers for Preoperative CT-Based Prediction of Histopathologic Chemotherapy Response Score in High-Grade Serous Ovarian Carcinoma
 - **Authors:** Francesca Fati, Felipe Coutinho, Marika Reinius, Marina Rosanu, Gabriel Funingana, Luigi De Vitis, Gabriella Schivardi, Hannah Clayton, Alice Traversa, Zeyu Gao, Guilherme Penteado, Shangqi Gao, Francesco Pastori, Ramona Woitek, Maria Cristina Ghioni, Giovanni Damiano Aletti, Mercedes Jimenez-Linan, Sarah Burge, Nicoletta Colombo, Evis Sala, Maria Francesca Spadea, Timothy L. Kline, James D. Brenton, Jaime Cardoso, Francesco Multinu, Elena De Momi, Mireia Crispin-Ortuzar, Ines P. Machado
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Purpose. High-grade serous ovarian carcinoma (HGSOC) is characterized by pronounced biological and spatial heterogeneity and is frequently diagnosed at an advanced stage. Neoadjuvant chemotherapy (NACT) followed by delayed primary surgery is commonly employed in patients unsuitable for primary cytoreduction. The Chemotherapy Response Score (CRS) is a validated histopathological biomarker of response to NACT, but it is only available postoperatively. In this study, we investigate whether pre-treatment computed tomography (CT) imaging and clinical data can be used to predict CRS as an investigational decision-support adjunct to inform multidisciplinary team (MDT) discussions regarding expected treatment response. Methods. We proposed a 2.5D multimodal deep learning framework that processes lesion-dense omental slices using a pre-trained Vision Transformer encoder and integrates the resulting visual representations with clinical variables through an intermediate fusion module to predict CRS. Results. Our multimodal model, integrating imaging and clinical data, achieved a ROC-AUC of 0.95 alongside 95% accuracy and 80% precision on the internal test cohort (IEO, n=41 patients). On the external test set (OV04, n=70 patients), it achieved a ROC-AUC of 0.68, alongside 67% accuracy and 75% precision. Conclusion. These preliminary results demonstrate the feasibility of transformer-based deep learning for preoperative prediction of CRS in HGSOC using routine clinical data and CT imaging. As an investigational, pre-treatment decision-support tool, this approach may assist MDT discussions by providing early, non-invasive estimates of treatment response.
### Title:
          CT-1: Vision-Language-Camera Models Transfer Spatial Reasoning Knowledge to Camera-Controllable Video Generation
 - **Authors:** Haoyu Zhao, Zihao Zhang, Jiaxi Gu, Haoran Chen, Qingping Zheng, Pin Tang, Yeyin Jin, Yuang Zhang, Junqi Cheng, Zenghui Lu, Peng Shu, Zuxuan Wu, Yu-Gang Jiang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Camera-controllable video generation aims to synthesize videos with flexible and physically plausible camera movements. However, existing methods either provide imprecise camera control from text prompts or rely on labor-intensive manual camera trajectory parameters, limiting their use in automated scenarios. To address these issues, we propose a novel Vision-Language-Camera model, termed CT-1 (Camera Transformer 1), a specialized model designed to transfer spatial reasoning knowledge to video generation by accurately estimating camera trajectories. Built upon vision-language modules and a Diffusion Transformer model, CT-1 employs a Wavelet-based Regularization Loss in the frequency domain to effectively learn complex camera trajectory distributions. These trajectories are integrated into a video diffusion model to enable spatially aware camera control that aligns with user intentions. To facilitate the training of CT-1, we design a dedicated data curation pipeline and construct CT-200K, a large-scale dataset containing over 47M frames. Experimental results demonstrate that our framework successfully bridges the gap between spatial reasoning and video synthesis, yielding faithful and high-quality camera-controllable videos and improving camera control accuracy by 25.7% over prior methods.
### Title:
          VAGNet: Vision-based accident anticipation with global features
 - **Authors:** Vipooshan Vipulananthan, Charith D. Chitraranjan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traffic accidents are a leading cause of fatalities and injuries across the globe. Therefore, the ability to anticipate hazardous situations in advance is essential. Automated accident anticipation enables timely intervention through driver alerts and collision avoidance maneuvers, forming a key component of advanced driver assistance systems. In autonomous driving, such predictive capabilities support proactive safety behaviors, such as initiating defensive driving and human takeover when required. Using dashcam video as input offers a cost-effective solution, but it is challenging due to the complexity of real-world driving scenes. Accident anticipation systems need to operate in real-time. However, current methods involve extracting features from each detected object, which is computationally intensive. We propose VAGNet, a deep neural network that learns to predict accidents from dash-cam video using global features of traffic scenes without requiring explicit object-level features. The network consists of transformer and graph modules, and we use the vision foundation model VideoMAE-V2 for global feature extraction. Experiments on four benchmark datasets (DAD, DoTA, DADA, and Nexar) show that our method anticipates accidents with higher average precision and mean time-to-accident while being computationally more efficient compared to existing methods.
### Title:
          Hierarchical Flow Decomposition for Turning Movement Prediction at Signalized Intersections
 - **Authors:** Md Atiqur Rahman Mallick, Kamrul Hasan, Pulock Das, Liang Hong, S M Shazzad Rassel
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate prediction of intersection turning movements is essential for adaptive signal control but remains difficult due to the high volatility of directional flows. This study proposes HFD-TM (Hierarchical Flow-Decomposition for Turning Movement Prediction), a hierarchical deep learning framework that predicts turning movements by first forecasting corridor through-movements and then expanding these predictions to individual turning streams. This design is motivated by empirical traffic structure, where corridor flows account for 65.1% of total volume, exhibit lower volatility than turning movements, and explain 35.5% of turning-movement variance. A physics-informed loss function enforces flow conservation to maintain structural consistency. Evaluated on six months of 15-minute interval LiDAR (Light Detection and Ranging) data from a six-intersection corridor in Nashville, Tennessee, HFD-TM achieves a mean absolute error of 2.49 vehicles per interval, reducing MAE by 5.7% compared to a Transformer and by 27.0% compared to a GRU (Gated Recurrent Unit). Ablation results show that hierarchical decomposition provides the largest performance gain, while training time is 12.8 times lower than DCRNN (Diffusion Convolutional Recurrent Neural Network), demonstrating suitability for real-time traffic applications.
### Title:
          Is More Data Worth the Cost? Dataset Scaling Laws in a Tiny Attention-Only Decoder
 - **Authors:** Götz-Henrik Wiegand, Lorena Raichle, Rico Städeli, Tomas Hrycej, Bernhard Bermeitinger, Siegfried Handschuh
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Training Transformer language models is expensive, as performance typically improves with increasing dataset size and computational budget. Although scaling laws describe this trend at large scale, their implications in controlled, smaller-scale settings remain less explored. In this work, we isolate dataset-size effects using a strongly reduced attention-only decoder architecture. By training on progressively larger power-of-two subsets, we observe smooth performance improvements accompanied by clear diminishing returns, consistent with scaling-law behavior. Using only about 30% of the training data is sufficient to reach approximately 90% of the full-data validation token-level accuracy. These results provide actionable insights into dataset scaling in a controlled, component-isolated setting and offer practical guidance for balancing dataset size and computational cost in compute- and data-restricted environments, such as small research labs and exploratory model development.
### Title:
          Do Vision Language Models Need to Process Image Tokens?
 - **Authors:** Sambit Ghosh, R. Venkatesh Babu, Chirag Agarwal
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Language Models (VLMs) have achieved remarkable success by integrating visual encoders with large language models (LLMs). While VLMs process dense image tokens across deep transformer stacks (incurring substantial computational overhead), it remains fundamentally unclear whether sustained image-token processing is necessary for their performance or visual representations meaningfully evolve from early to later layers. In this work, we systematically investigate the functional role of image tokens in VLMs and show that visual representations rapidly converge to a bounded-complexity regime, \ie their entropy stabilizes, intrinsic dimensionality compresses, and trajectory curvature approaches a near-constant profile. In contrast, textual representations continue to undergo substantial restructuring across depth. Once stabilized, visual representations become largely interchangeable between layers, indicating limited additional transformation in deeper stages. Further, depth-wise visual truncation reveals that the necessity of visual processing is task-dependent, where single-token predictions remain comparatively robust to truncated visual depth, but multi-token generation require sustained access to visual representations. Under deterministic decoding, reducing visual depth perturbs intermediate reasoning trajectories more strongly than final outputs, suggesting that image tokens influence the structure of reasoning more than the ultimate conclusions. Collectively, these findings \textbf{question the assumption} that deeper visual processing is uniformly essential in VLMs, challenging the current paradigm of multimodal LLM architectures.
### Title:
          UIPress: Bringing Optical Token Compression to UI-to-Code Generation
 - **Authors:** Dasen Dai, Shuoqi Li, Ronghao Chen, Huacan Wang, Biao Wu, Qizhen Lan
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 UI-to-Code generation requires vision-language models (VLMs) to produce thousands of tokens of structured HTML/CSS from a single screenshot, making visual token efficiency critical. Existing compression methods either select tokens at inference time using task-agnostic heuristics, or zero out low-attention features without actually shortening the sequence -- neither truly reduces prefill latency or adapts to the non-uniform information density of UI screenshots. Meanwhile, optical (encoder-side learned) compression has shown strong results for document OCR, yet no prior work has adapted this paradigm to UI-to-Code generation. We propose UIPress, a lightweight learned compression module inserted between the frozen ViT encoder and the LLM decoder of Qwen3-VL-8B. UIPress combines depthwise-separable convolutions, element-guided spatial reweighting, and Transformer refinement to compress ${\sim}$6{,}700 visual tokens to a fixed budget of 256. Together with Low-Rank Adaptation (LoRA) on the decoder to bridge the representation gap, the entire system adds only ${\sim}$21.7M trainable parameters (0.26\% of the 8B base model). Under a fair comparison on the same base model against four baselines on Design2Code, UIPress at 256 tokens achieves a CLIP score of 0.8127, outperforming the uncompressed baseline by +7.5\% and the strongest inference-time method by +4.6\%, while delivering 9.1$\times$ time-to-first-token speedup. To the best of our knowledge, UIPress is the first encoder-side learned compression method for the UI-to-Code task.
### Title:
          Integrated electro-optic attention nonlinearities for transformers
 - **Authors:** Luis Mickeler, Kai Lion, Alfonso Nardi, Jost Kellner, Pierre Didier, Bhavin J. Shastri, Niao He, Rachel Grange
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Optics (physics.optics)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers have emerged as the dominant neural-network architecture, achieving state-of-the-art performance in language processing and computer vision. At the core of these models lies the attention mechanism, which requires a nonlinear, non-negative mapping using the Softmax function. However, although Softmax operations account for less than 1% of the total operation count, they can disproportionately bottleneck overall inference latency. Here, we use thin-film lithium niobate (TFLN) Mach-Zehnder modulators (MZMs) as analog nonlinear computational elements to drastically reduce the latency of nonlinear computations. We implement electro-optic alternatives to digital Softmax and Sigmoid, and evaluate their performance in Vision Transformers and Large Language Models. Our system maintains highly competitive accuracy, even under aggressive 4-bit input-output quantization of the analog units. We further characterize system noise at encoding speeds up to 10 GBaud and assess model robustness under various noise conditions. Our findings suggest that TFLN modulators can serve as nonlinear function units within hybrid co-packaged hardware, enabling high-speed and energy-efficient nonlinear computation.
## Keyword: autonomous driving
### Title:
          Act or Escalate? Evaluating Escalation Behavior in Automation with Language Models
 - **Authors:** Matthew DosSantos DiSorbo, Harang Ju
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Effective automation hinges on deciding when to act and when to escalate. We model this as a decision under uncertainty: an LLM forms a prediction, estimates its probability of being correct, and compares the expected costs of acting and escalating. Using this framework across five domains of recorded human decisions-demand forecasting, content recommendation, content moderation, loan approval, and autonomous driving-and across multiple model families, we find marked differences in the implicit thresholds models use to trade off these costs. These thresholds vary substantially and are not predicted by architecture or scale, while self-estimates are miscalibrated in model-specific ways. We then test interventions that target this decision process by varying cost ratios, providing accuracy signals, and training models to follow the desired escalation rule. Prompting helps mainly for reasoning models. SFT on chain-of-thought targets yields the most robust policies, which generalize across datasets, cost ratios, prompt framings, and held-out domains. These results suggest that escalation behavior is a model-specific property that should be characterized before deployment, and that robust alignment benefits from training models to reason explicitly about uncertainty and decision costs.
### Title:
          LMGenDrive: Bridging Multimodal Understanding and Generative World Modeling for End-to-End Driving
 - **Authors:** Hao Shao, Letian Wang, Yang Zhou, Yuxuan Hu, Zhuofan Zong, Steven L. Waslander, Wei Zhan, Hongsheng Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent years have seen remarkable progress in autonomous driving, yet generalization to long-tail and open-world scenarios remains a major bottleneck for large-scale deployment. To address this challenge, some works use LLMs and VLMs for vision-language understanding and reasoning, enabling vehicles to interpret rare and safety-critical situations when generating actions. Others study generative world models to capture the spatio-temporal evolution of driving scenes, allowing agents to imagine possible futures before acting. Inspired by human intelligence, which unifies understanding and imagination, we explore a unified model for autonomous driving. We present LMGenDrive, the first framework that combines LLM-based multimodal understanding with generative world models for end-to-end closed-loop driving. Given multi-view camera inputs and natural-language instructions, LMGenDrive generates both future driving videos and control signals. This design provides complementary benefits: video prediction improves spatio-temporal scene modeling, while the LLM contributes strong semantic priors and instruction grounding from large-scale pretraining. We further propose a progressive three-stage training strategy, from vision pretraining to multi-step long-horizon driving, to improve stability and performance. LMGenDrive supports both low-latency online planning and autoregressive offline video generation. Experiments show that it significantly outperforms prior methods on challenging closed-loop benchmarks, with clear gains in instruction following, spatio-temporal understanding, and robustness to rare scenarios. These results suggest that unifying multimodal understanding and generation is a promising direction for more generalizable and robust embodied decision-making systems.
### Title:
          Learning Vision-Language-Action World Models for Autonomous Driving
 - **Authors:** Guoqing Wang, Pin Tang, Xiangxuan Ren, Guodongfang Zhao, Bailan Feng, Chao Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models have recently achieved notable progress in end-to-end autonomous driving by integrating perception, reasoning, and control within a unified multimodal framework. However, they often lack explicit modeling of temporal dynamics and global world consistency, which limits their foresight and safety. In contrast, world models can simulate plausible future scenes but generally struggle to reason about or evaluate the imagined future they generate. In this work, we present VLA-World, a simple yet effective VLA world model that unifies predictive imagination with reflective reasoning to improve driving foresight. VLA-World first uses an action-derived feasible trajectory to guide the generation of the next-frame image, capturing rich spatial and temporal cues that describe how the surrounding environment evolves. The model then reasons over this self-generated future imagined frame to refine the predicted trajectory, achieving higher performance and better interpretability. To support this pipeline, we curate nuScenes-GR-20K, a generative reasoning dataset derived from nuScenes, and employ a three-stage training strategy that includes pretraining, supervised fine-tuning, and reinforcement learning. Extensive experiments demonstrate that VLA-World consistently surpasses state-of-the-art VLA and world-model baselines on both planning and future-generation benchmarks. Project page: this https URL
### Title:
          Long-SCOPE: Fully Sparse Long-Range Cooperative 3D Perception
 - **Authors:** Jiahao Wang, Zikun Xu, Yuner Zhang, Zhongwei Jiang, Chenyang Lu, Shuocheng Yang, Yuxuan Wang, Jiaru Zhong, Chuang Zhang, Shaobing Xu, Jianqiang Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cooperative 3D perception via Vehicle-to-Everything communication is a promising paradigm for enhancing autonomous driving, offering extended sensing horizons and occlusion resolution. However, the practical deployment of existing methods is hindered at long distances by two critical bottlenecks: the quadratic computational scaling of dense BEV representations and the fragility of feature association mechanisms under significant observation and alignment errors. To overcome these limitations, we introduce Long-SCOPE, a fully sparse framework designed for robust long-distance cooperative 3D perception. Our method features two novel components: a Geometry-guided Query Generation module to accurately detect small, distant objects, and a learnable Context-Aware Association module that robustly matches cooperative queries despite severe positional noise. Experiments on the V2X-Seq and Griffin datasets validate that Long-SCOPE achieves state-of-the-art performance, particularly in challenging 100-150 m long-range settings, while maintaining highly competitive computation and communication costs.
### Title:
          Neural Distribution Prior for LiDAR Out-of-Distribution Detection
 - **Authors:** Zizhao Li, Zhengkang Xiang, Jiayang Ao, Feng Liu, Joseph West, Kourosh Khoshelham
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR-based perception is critical for autonomous driving due to its robustness to poor lighting and visibility conditions. Yet, current models operate under the closed-set assumption and often fail to recognize unexpected out-of-distribution (OOD) objects in the open world. Existing OOD scoring functions exhibit limited performance because they ignore the pronounced class imbalance inherent in LiDAR OOD detection and assume a uniform class distribution. To address this limitation, we propose the Neural Distribution Prior (NDP), a framework that models the distributional structure of network predictions and adaptively reweights OOD scores based on alignment with a learned distribution prior. NDP dynamically captures the logit distribution patterns of training data and corrects class-dependent confidence bias through an attention-based module. We further introduce a Perlin noise-based OOD synthesis strategy that generates diverse auxiliary OOD samples from input scans, enabling robust OOD training without external datasets. Extensive experiments on the SemanticKITTI and STU benchmarks demonstrate that NDP substantially improves OOD detection performance, achieving a point-level AP of 61.31\% on the STU test set, which is more than 10$\times$ higher than the previous best result. Our framework is compatible with various existing OOD scoring formulations, providing an effective solution for open-world LiDAR perception.
### Title:
          VAGNet: Vision-based accident anticipation with global features
 - **Authors:** Vipooshan Vipulananthan, Charith D. Chitraranjan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traffic accidents are a leading cause of fatalities and injuries across the globe. Therefore, the ability to anticipate hazardous situations in advance is essential. Automated accident anticipation enables timely intervention through driver alerts and collision avoidance maneuvers, forming a key component of advanced driver assistance systems. In autonomous driving, such predictive capabilities support proactive safety behaviors, such as initiating defensive driving and human takeover when required. Using dashcam video as input offers a cost-effective solution, but it is challenging due to the complexity of real-world driving scenes. Accident anticipation systems need to operate in real-time. However, current methods involve extracting features from each detected object, which is computationally intensive. We propose VAGNet, a deep neural network that learns to predict accidents from dash-cam video using global features of traffic scenes without requiring explicit object-level features. The network consists of transformer and graph modules, and we use the vision foundation model VideoMAE-V2 for global feature extraction. Experiments on four benchmark datasets (DAD, DoTA, DADA, and Nexar) show that our method anticipates accidents with higher average precision and mean time-to-accident while being computationally more efficient compared to existing methods.
