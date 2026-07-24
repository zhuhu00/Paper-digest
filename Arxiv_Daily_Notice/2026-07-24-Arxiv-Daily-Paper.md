# Showing new listings for Friday, 24 July 2026
## Keyword: SLAM
### Title:
          GLAM-SLAM: Real-time Gaussian Large-scale Mapping via Flow Densification and Spatial Decomposition
 - **Authors:** Panagiotis Mermigkas, Argyris Manetas, Petros Maragos
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing Gaussian-splatting-based monocular Simultaneous Localization and Mapping (SLAM) systems are either tailored to short sequences, are not real-time, or suffer from prohibitive GPU memory requirements, limiting their applicability in realistic, long-horizon scenarios. To address this, we present GLAM-SLAM, a real-time, decoupled Gaussian-splatting SLAM system designed for large-scale outdoor scenes. We ensure lightweight tracking using a robust, feature-based SLAM frontend, while for mapping, we adopt a structured, sparse anchor grid representation that ensures scalable operation and maintains scene coherence across long-term sequences. To satisfy the dense initialization requirements of 3D Gaussian Splatting (3DGS), we introduce a geometry-based flow-densification anchoring strategy using epipolar constraints. Furthermore, by treating mapping as a multi-scene problem, we propose a scene-partitioning strategy that introduces a strong spatial inductive bias via MLP initializations to generate localized Gaussians. We evaluate our system on the challenging, long-sequence KITTI Odometry, Oxford RobotCar, and M'alaga datasets. Extensive ablations and comparisons demonstrate a 15% improvement in reconstruction quality over the second-best performer, while maintaining real-time performance and the ability to scale to longer sequences. Code is publicly available for the benefit of the community.
## Keyword: odometry
### Title:
          GLAM-SLAM: Real-time Gaussian Large-scale Mapping via Flow Densification and Spatial Decomposition
 - **Authors:** Panagiotis Mermigkas, Argyris Manetas, Petros Maragos
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing Gaussian-splatting-based monocular Simultaneous Localization and Mapping (SLAM) systems are either tailored to short sequences, are not real-time, or suffer from prohibitive GPU memory requirements, limiting their applicability in realistic, long-horizon scenarios. To address this, we present GLAM-SLAM, a real-time, decoupled Gaussian-splatting SLAM system designed for large-scale outdoor scenes. We ensure lightweight tracking using a robust, feature-based SLAM frontend, while for mapping, we adopt a structured, sparse anchor grid representation that ensures scalable operation and maintains scene coherence across long-term sequences. To satisfy the dense initialization requirements of 3D Gaussian Splatting (3DGS), we introduce a geometry-based flow-densification anchoring strategy using epipolar constraints. Furthermore, by treating mapping as a multi-scene problem, we propose a scene-partitioning strategy that introduces a strong spatial inductive bias via MLP initializations to generate localized Gaussians. We evaluate our system on the challenging, long-sequence KITTI Odometry, Oxford RobotCar, and M'alaga datasets. Extensive ablations and comparisons demonstrate a 15% improvement in reconstruction quality over the second-best performer, while maintaining real-time performance and the ability to scale to longer sequences. Code is publicly available for the benefit of the community.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          DTIF: Robust Loop Closure Detection via Delaunay Triangle Topology in Complex Forests
 - **Authors:** Xin Zhao, Jianping Li, Qin Zou, Fuxun Liang, Zhen Dong, Bisheng Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate forest inventory and large-scale mapping are essential for ecosystem monitoring and sustainable forest management. Multiple low-cost edge platforms enable efficient large-area data acquisition, but merging independently constructed local maps in GNSS-denied understory environments still requires initialization-free loop closure detection and global registration. This task is challenging because low-cost LiDAR point clouds are sparse and noisy, while repetitive trunk layouts and the lack of distinctive geometric landmarks lead to severe perceptual aliasing and false correspondences. To address these issues, we propose DTIF (Delaunay Triangulation in Forests), a lightweight trunk-topology-based framework for forest loop closure detection and global registration. Tree trunks are first extracted as stable landmarks and encoded using a Delaunay topology for compact scene representation. Candidate submaps are then screened using edge-length and radius statistics, followed by edge--radius consistency verification and strong/weak vertex support aggregation to construct weighted vertex correspondences. Finally, topology-derived reliability weights are incorporated into a decoupled robust pose estimator that separately estimates yaw, horizontal translation, and elevation translation under gravity alignment. Experiments on simulated and real-world forest datasets demonstrate that DTIF achieves accurate registration with low computational overhead, providing a favorable balance among robustness, efficiency, and deployability on resource-constrained edge platforms.
### Title:
          Factorized Spatio-Temporal Convolutions for Human Pose Estimation from Planar Lidar
 - **Authors:** Simone Arreghini, Mirko Nava, Nicholas Carlotti, Antonio Paolillo, Alessandro Giusti
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Localizing nearby humans and estimating their facing direction are key capabilities for safe navigation and socially aware human-robot interaction. Many pose-estimation pipelines target cameras and 3D LiDAR or assume GPU-class compute, whereas service robots are often equipped only with omnidirectional planar LiDARs and modest onboard processors. We address omnidirectional human detection and relative 2D pose estimation from planar LiDAR sequences with a lightweight network based on Space-Time Blocks, which explicitly separate spatial processing along scan rays from temporal aggregation across scans. Our network processes 360° LiDAR sequences to output per-ray human presence, distance, and relative orientation. We train it via cross-modal self-supervision from a narrow RGB-D body tracker in the sensors' overlap region, removing the need for manual LiDAR labels. Quantitative experiments show that our approach consistently outperforms a parameter-matched baseline model, reducing errors in distance (-38%), position (-28%), and orientation (-15%). We further benchmark on the public FROG dataset, report real-time CPU inference on a service robot, and validate with in-field demonstrations, supporting its suitability for spatial perception on computationally constrained service robots.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          Recurrent Sinusoidal INRs for Efficient High-Fidelity Representation
 - **Authors:** Hyunmin Cho, Jaejun Yoo, Kyong Hwan Jin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study sinusoidal recurrence as an iterative mechanism for harmonic spectral enrichment in implicit neural representations (INRs). Our analysis reveals that sinusoidal activations induce a harmonic line spectrum, providing a spectral account of how recurrent unrolling enriches the effective spectral support. We realize this principle with a shared sinusoidal block that iteratively refines the latent representation. We empirically validate the resulting spectral behavior against feed-forward INRs, non-sinusoidal recurrent variants, and equilibrium-style sinusoidal models. Complementing this analysis, we evaluate the proposed architecture across image and 3D representation tasks. On RGB image benchmarks, our method achieves higher fidelity than feed-forward baselines with fewer parameters and fewer optimization steps, and it further transfers favorably to super-resolution, NeRF, and SDF tasks.
## Keyword: mapping
### Title:
          Component structure and percolation in block models
 - **Authors:** Riccardo Franchi, M. E. J. Newman
 - **Subjects:** Subjects:
Social and Information Networks (cs.SI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The stochastic block model is a widely studied model of community structure in networks. Here we study the component structure and percolation properties of networks generated from this model and its variants, using exact methods based on probability generating functions. In particular, we derive expressions for the size of the giant component and the distribution of small components in such networks and for the size of the percolating cluster and position of the percolation threshold for both node and edge percolation, for the original stochastic block model and for its degree-corrected versions. In passing, we also develop a mapping between generating functions for microcanonical and canonical block models that allows us to generalize results for the former to the latter with minimal effort.
### Title:
          EuroFlood: a Python library and queryable index for the CEMS satellite-derived flood-depth archive of Europe
 - **Authors:** Jürgen Hackl
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Satellite-derived observations of flood water depth support flood model validation and impact assessment, yet the only open continental-scale archive of such observations, the flood-depth maps of the Copernicus Emergency Management Service, is distributed as several thousand raster files whose sole spatial metadata is a coordinate encoded in each filename. This paper presents EuroFlood, an open-source Python library and a published spatial index that make the archive queryable. The index records which events inundated each grid cell, so discovery, recurrence, and footprint queries are answered from a small fraction of the archive volume, while depth rasters are retrieved on demand. It reproduces the archived event footprints losslessly at its grid, and a completeness audit against an independent flood-impact database shows that most documented floods co-occur with archived events. Demonstrations include continental recurrence mapping, comparison of observed with modelled flood extents, and event-based exposure assessment.
### Title:
          DTIF: Robust Loop Closure Detection via Delaunay Triangle Topology in Complex Forests
 - **Authors:** Xin Zhao, Jianping Li, Qin Zou, Fuxun Liang, Zhen Dong, Bisheng Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate forest inventory and large-scale mapping are essential for ecosystem monitoring and sustainable forest management. Multiple low-cost edge platforms enable efficient large-area data acquisition, but merging independently constructed local maps in GNSS-denied understory environments still requires initialization-free loop closure detection and global registration. This task is challenging because low-cost LiDAR point clouds are sparse and noisy, while repetitive trunk layouts and the lack of distinctive geometric landmarks lead to severe perceptual aliasing and false correspondences. To address these issues, we propose DTIF (Delaunay Triangulation in Forests), a lightweight trunk-topology-based framework for forest loop closure detection and global registration. Tree trunks are first extracted as stable landmarks and encoded using a Delaunay topology for compact scene representation. Candidate submaps are then screened using edge-length and radius statistics, followed by edge--radius consistency verification and strong/weak vertex support aggregation to construct weighted vertex correspondences. Finally, topology-derived reliability weights are incorporated into a decoupled robust pose estimator that separately estimates yaw, horizontal translation, and elevation translation under gravity alignment. Experiments on simulated and real-world forest datasets demonstrate that DTIF achieves accurate registration with low computational overhead, providing a favorable balance among robustness, efficiency, and deployability on resource-constrained edge platforms.
### Title:
          Differentiable Logic Programming to Mitigate Reasoning Shortcuts in Neurosymbolic Systems
 - **Authors:** Akihiro Takemura (National Institute of Informatics, Tokyo, Japan), Katsumi Inoue (National Institute of Informatics, Tokyo, Japan)
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Logic in Computer Science (cs.LO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neurosymbolic (NeSy) systems integrate neural networks with logical reasoning to achieve both generalization and interpretability, but recent work has shown they are susceptible to shortcut reasoning behaviors.  We propose a novel method using matrix-based differentiable logic programming to mitigate reasoning shortcuts in two phenomena: constraint satisfaction shortcuts, where constraints are satisfied without achieving the intended task, and cognition shortcuts, where biased data leads to semantically incorrect concept mappings despite logically sound inference. Building on recent matrix-based logic programming semantics, we introduce design elements to mitigate shortcuts, including a unified encoding of rules and constraints in a single matrix.  We also identify connections to fuzzy logic t-norms and empirically compare their gradient flow properties. Through carefully designed experiments on MNIST variants, we show that one-to-one grounding of neural outputs to logical atoms significantly reduces both shortcut types compared to previous methods that rely on soft probability distributions.  We then confirm that architectural choices in coupling symbolic knowledge with neural learning play a critical role in shortcut mitigation.
### Title:
          Filter Learning for Subgraphs: Algebras and Performance Risk Bounds
 - **Authors:** Purui Zhang, Feng Ji, Yanan Zhao, Bihan Wen, Wee Peng Tay
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Graph signal processing tasks that leverage spectral information typically assume access to the complete graph topology, which is often unavailable in practice. We propose a systematic framework for subgraph filter learning (SFL), where subgraph-supported operators approximate ambient graph filters under partial observations. We formulate SFL as a statistical learning problem in which optimal subgraph operators are inherently data-dependent. To address the difficulty of directly estimating such operators, we develop a subgraph filter algebra based on distance-aware Laplacian constructions, defining a structured and controllable class of filters for effective approximation. We further establish performance risk bounds under the least squares loss, quantifying how well the learned operator approximates the restricted ambient mapping. Experiments real-world datasets show that, for SFL tasks, the proposed algebraic models consistently outperform polynomial filters, distribution-agnostic operators, and direct numerical filter learning baselines that attempt to recover the underlying structure from data.
### Title:
          HGeo-TopoMap: Boosting Topological Mapping with Hierarchical Geometric Priors
 - **Authors:** Siyu Li, Kunyu Peng, Di Wen, Beiping Hou, Zhiyong Li, Kailun Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Topological maps are key outputs of autonomous driving perception systems, delivering essential road information for path planning. They identify instances such as centerlines and traffic signs, along with their connectivity relationships. Due to the lack of explicit markings for centerlines in real-world environments, the detection of centerline instances remains a significant challenge. To tackle this problem, we propose HGeo-TopoMap, which leverages an explicit prior map and implicit spatial relations to hierarchically boost topological mapping. First, a geometric adaptive learning module is designed for the road structure map obtained via inverse perspective mapping. This module discretely encodes semantic and spatial features from the map, followed by a prior-mask attention mechanism that selectively focuses on informative regions. Then, a geometric consistency learning module is devised, which leverages the geometric properties and spatial relationships of centerlines. Built on the geometry-aware decoder, it enforces spatial consistency by aligning features of centerline instances with identical geometric orientations. The proposed method is evaluated on the OpenLane-V2 dataset across the centerline, lane segment, and robustness benchmarks. Beyond substantial improvements in topological mapping accuracy, the proposed method offers the benefit of enhanced robustness, consistently outperforming baselines under both standard and challenging conditions. The source code and model weights will be made publicly available at this https URL.
### Title:
          Scaling Up Formal Representation of Clinical Trial Protocols in Ensemble Logic Using LLMs: A Preliminary Study
 - **Authors:** Yan Huang, Xubing Hao, Xiaojin Li, Rashmie Abeysinghe, Xiaoqian Jiang, Licong Cui, Guo-Qiang Zhang
 - **Subjects:** Subjects:
Logic in Computer Science (cs.LO); Artificial Intelligence (cs.AI); Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The reliance on unstructured free text for documenting clinical trial protocols creates a significant barrier to automated reasoning, cohort discovery, and trial simulation. The lack of formal structure obscures critical temporal phenotypes, such as dynamic eligibility criteria and event timing constraints. Although Temporal Ensemble Logic (TEL) offers an expressive framework for modeling these elements, manual encoding remains a prohibitive bottleneck. We introduce the CT-TEL workflow: a scalable pipeline leveraging Large Language Models (LLMs) to translate narrative clinical protocols into TEL formulas. We applied CT-TEL to generate logical models for 23 real-world trials from this http URL. We evaluated translation fidelity via a back-translation approach, using LLMs to convert TEL formulas back into natural language and measuring semantic similarity against source texts. The resulting semantic retention suggests that LLMs may offer a pathway for mapping informal protocols to computable logic, providing preliminary evidence toward scalable clinical trial emulation within the emerging "Symbolic Biomedicine" paradigm championed by the corresponding author.
### Title:
          From Static Bibliometrics to Dynamic Knowledge Graphs: An LLM-Powered Framework for Modernizing Science, Technology, and Innovation (STI) Analytics
 - **Authors:** Muhsen Hammoud
 - **Subjects:** Subjects:
Digital Libraries (cs.DL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bibliometric indicators - citation counts, h-indexes, co-authorship networks - have long anchored science, technology, and innovation (STI) analytics, yet suffer from temporal lag, semantic shallowness, and an inability to capture the non-linear dynamics of contemporary knowledge ecosystems. Dynamic knowledge graphs and large language models (LLMs) have each been proposed as remedies, but neither is sufficient alone: existing scholarly knowledge graphs remain largely static, while LLM-driven pipelines are prone to hallucination, opacity, and corpus bias without structured grounding. This paper proposes a hybrid, symbolic-first framework integrating all three traditions under explicit methodological constraint. Organized across five layers - an open scholarly data backbone, a dynamic versioned knowledge graph, a constrained LLM-assisted semantic augmentation layer, a multi-layer validation pipeline, and an analytics layer - the framework positions LLMs strictly as generators of provisional candidate enrichments. Candidates become analytically admissible only after passing structural, evidentiary, comparative, and selective expert validation, with full provenance recorded at every stage. The analytics layer supports both established bibliometric indicators and extended graph-based analyses, including trend emergence detection, science-to-technology pathway mapping, and policy-oriented gap analysis. The framework's central theoretical contribution is treating validation as the mediating principle between semantic flexibility and epistemic discipline, enabling STI analytics that is semantically richer and temporally more responsive than static bibliometrics while remaining aligned with the evidentiary standards of science-of-science research. Governance considerations addressing reproducibility, bias, and auditability are also discussed.
### Title:
          A Logic-based Temporal Cohort Discovery Engine: Algorithms, Indices, and Experimental Results on the National Sleep Research Resource
 - **Authors:** Yan Huang, Xiaojin Li, Licong Cui, Guo-Qiang Zhang
 - **Subjects:** Subjects:
Databases (cs.DB); Logic in Computer Science (cs.LO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large sleep-study repositories contain rich time-stamped physiological annotations, but cohort discovery is still commonly implemented as ad hoc scripts or scalar-index filters. We present a logic-based temporal cohort discovery engine that brings formal semantics, model checking, specialized indexing, and empirical evaluation into a unified biomedical informatics framework. We adopt Rational Ensemble Logic (QEL) as a dense-time formal foundation for sleep-data querying and represent each annotated polysomnogram as a Biomedical Event Structure Temporal Model (BEST), a finite mapping from event labels to non-overlapping rational interval ensembles. Cohort discovery is formulated as model checking of QEL formulas over BEST databases. We organize common sleep-research requirements into three reusable temporal query patterns: single-event retrieval, dual-event temporal pattern matching, and event data extraction. The prototype cohort discovery engine was implemented in Python with in-memory and MongoDB-backed execution modes and evaluated on synthetic interval datasets containing up to 90 million intervals and on real-world National Sleep Research Resource annotations from the Cleveland Children's Sleep and Health Study (CCSHS) containing 515 subjects, 202,587 intervals, 23 event labels. 2DFC constructs indexes in linear space and linear build time, reducing build time at 90 million intervals from 11,549 s with RTFC and 23,902 seconds with 2DRT to 3,655 seconds. On CCSHS, cohort-selection queries executed at sub-second latency at native scale and under 45 seconds at 1,000 times scale. This work is a part of the Symbolic Biomedicine program championed by the corresponding author.
### Title:
          GLAM-SLAM: Real-time Gaussian Large-scale Mapping via Flow Densification and Spatial Decomposition
 - **Authors:** Panagiotis Mermigkas, Argyris Manetas, Petros Maragos
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing Gaussian-splatting-based monocular Simultaneous Localization and Mapping (SLAM) systems are either tailored to short sequences, are not real-time, or suffer from prohibitive GPU memory requirements, limiting their applicability in realistic, long-horizon scenarios. To address this, we present GLAM-SLAM, a real-time, decoupled Gaussian-splatting SLAM system designed for large-scale outdoor scenes. We ensure lightweight tracking using a robust, feature-based SLAM frontend, while for mapping, we adopt a structured, sparse anchor grid representation that ensures scalable operation and maintains scene coherence across long-term sequences. To satisfy the dense initialization requirements of 3D Gaussian Splatting (3DGS), we introduce a geometry-based flow-densification anchoring strategy using epipolar constraints. Furthermore, by treating mapping as a multi-scene problem, we propose a scene-partitioning strategy that introduces a strong spatial inductive bias via MLP initializations to generate localized Gaussians. We evaluate our system on the challenging, long-sequence KITTI Odometry, Oxford RobotCar, and M'alaga datasets. Extensive ablations and comparisons demonstrate a 15% improvement in reconstruction quality over the second-best performer, while maintaining real-time performance and the ability to scale to longer sequences. Code is publicly available for the benefit of the community.
### Title:
          Agent-Guided Relational Concept Discovery: Toward Interpretable Surgical Margin Assessment
 - **Authors:** Nooshin Maghsoodi, Amoon Jamzad, Robert Policelli, Mohammad Farahmand, Dilakshan Srikanthan, Martin Kaufmann, Kevin Y. M. Ren, Shaila Merchant, Sonal Varma, Ross Walker, Doug McKay, John Rudan, Gabor Fichtinger, Parvin Mousavi
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning models can effectively use Rapid Evaporative Ionization Mass Spectrometry (REIMS) data for surgical margin assessment. However, their clinical adoption remains challenging due to limited generalization to operating room conditions. This difficulty arises because models are typically trained on labeled spectra collected from resected tissue samples, while they must operate on noisy, unlabeled data acquired directly during surgery. In addition, the black-box nature of deep learning models makes it difficult to understand and systematically improve their behavior. Concept-based learning offers a promising way to address these challenges by mapping raw measurements to human-understandable concepts. However, supervised concept-based approaches rely on concept annotations, which are difficult to obtain in complex mass spectrometry workflows. We propose Agent-Guided Concept Discovery, a framework that learns meaningful concepts directly from data without requiring predefined concept labels. During training, a reasoning agent refines semantic descriptions of the learned concepts and adaptively adjusts their weight based on diagnostic relevance. These concepts are further grounded using a biochemical knowledge graph to ensure consistency with known metabolic relationships. Across Skin and Breast Cancer datasets, our model improves balanced accuracy and sensitivity over the baseline. In a representative intraoperative case, it shows fewer false positives, indicating better generalization to surgical conditions.
### Title:
          Toward Continuous Assurance for the Democratization of AI Agent Creation in Industry
 - **Authors:** Natan Levy, Harel Berger
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Emerging Technologies (cs.ET); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI agents are increasingly created inside organizations by non-engineering users through low-code, no-code, and conversational development environments. This democratization enables rapid local innovation, but it also creates a reliability gap: agents that appear to users as simple productivity artifacts may depend on changing models, tools, retrieval sources, permissions, prompts, schedules, and external services. These dependencies can cause silent degradation long after deployment, even when no user directly modifies the agent. This paper identifies the reliability challenge created by democratized AI agent creation and proposes a lightweight continuous-assurance framework for citizen-created organizational agents. The framework combines dependency mapping, readiness contracts, scheduled checks, diagnostics, and lifecycle governance to assess whether an agent remains operationally ready under expected conditions. We also present an initial prototype auditor and scenario-based assessment showing how the proposed taxonomy can be translated into practical checks and actionable remediation guidance.
### Title:
          ElasticTTT: Prior-Preserving Test-Time Tuning for Video Editing
 - **Authors:** Yueyi Liu, Chi Zhang, Sen Cui, Miao Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Test-Time Tuning (TTT) on pretrained diffusion models has emerged as a powerful paradigm for video editing. However, there exists a foundational mismatch between the distribution-mapping nature of generative models and the single-point optimization of standard TTT. In this paper, we demonstrate that this mismatch triggers \textit{Prior Collapse}, a degenerate state where the model discards the text conditions and spatial latents, collapsing generations to the source video, or entangling the features of distinct regions. To resolve this, we propose \textbf{ElasticTTT}, a novel framework that preserves the prior generative distribution and rescues generative elasticity. Specifically, we propose \textit{Target Distribution Regularization} to prevent sharp memorization minima, \textit{Contrastive CFG} to guide inference away from source biases, and \textit{Asynchronous Noise Schedule} to preserve unedited regions. Extensive evaluations, supported by theoretical analysis, demonstrate that ElasticTTT successfully preserves the generative prior of the base model, achieving state-of-the-art performance on one-shot video editing.
### Title:
          Towards Robust Iris Recognition Through Occlusion Identification and Conditional Diffusion-Based Reconstruction
 - **Authors:** Kamrul Hasan, Mylene C.Q. Farias, Oleg V. Komogortsev
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Iris recognition is a reliable biometric approach that identifies individuals using the distinctive and stable texture of the iris. However, recognition performance can degrade when discriminative iris texture is partially occluded by eyelids, eyelashes, specular reflections, or other acquisition artifacts. Existing approaches often perform recognition directly on degraded samples or rely only on the remaining visible iris region, which may be inadequate when substantial texture is corrupted. To address this limitation, we propose an occlusion-aware iris recognition framework with three sequential modules: occlusion-type identification, diffusion-based reconstruction, and deep-learning-based recognition. First, a residual 2D CNN-based network determines whether an iris image is non-occluded or belongs to one of the controlled occlusion categories. Second, the occluded image, binary mask, and predicted occlusion type condition a denoising diffusion probabilistic model to reconstruct the corrupted region. Finally, VGG19-HPMNet, a modified VGG19 model with horizontal pyramid mapping, extracts discriminative global and part-wise local iris features for recognition. Experiments on the CASIA-Iris-Thousand dataset under a controlled synthetic-occlusion protocol show that the proposed framework improves iris recognition performance by identifying the occlusion type, reconstructing masked regions, and re-evaluating the restored iris samples.
## Keyword: localization
### Title:
          Routing Subspaces: Auditing Evaluation-to-Deployment Mismatch in Fine-Tuned Language Models
 - **Authors:** Phongsakon Mark Konrad, Toygar Tanyel, Serkan Ayvaz
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Safety evaluations often assume that behavior observed during testing reflects behavior in ordinary use, but fine-tuning can break this assumption. A checkpoint can appear fixed under evaluation-style prompts while the same behavior persists under ordinary-use prompts. Output scores reveal this mismatch but do not locate it. We investigate whether the distinction is encoded in a stable internal site and introduce an approach that fits a paired activation contrast at a path-patching-informed mid-depth window, then modifies the resulting coordinate on held-out prompts. The intervention closes the evaluation-to-deployment gap in ten of twelve model--behavior settings (six of the eight settings with $n{\geq}120$ paired questions) across four full-matrix instruction-tuned model instances; a fifth model supports localization and edit-provenance checks, and deployment-framed rates change by at most $6.1$pp. The two flat cells, both sycophancy, indicate that a single-coordinate audit is not sufficient when the installed distinction is higher-rank or missed by the depth heuristic. The audit is a diagnostic for fine-tuned checkpoints, not a training-time defense or a guarantee of deployment safety.
### Title:
          Enabling Scalable Topology Inference in Distribution Systems via Constrained Multi-Source Inference
 - **Authors:** Haoran Li, Lihao Mai, Muhao Guo, Jiaqi Wu, Yang Weng
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate distribution system topology is essential for outage localization, voltage analytics, and operation of distribution grids, yet maintaining reliable connectivity records remains challenging in practice due to heterogeneous and imperfect utility data. Existing topology identification methods often rely primarily on electrical similarity or spatial records alone, which become unreliable in dense feeders and under inconsistent metadata conditions. This paper formulates distribution topology identification as a constrained inference problem that refines a utility-provided base topology using heterogeneous evidence while enforcing spatial feasibility and physical operational constraints. Instead of reconstructing connectivity from scratch, the proposed framework detects inconsistent assignments, performs localized reconnection within constrained neighborhoods to ensure scalability, and iteratively enforces physical feasibility to produce operationally consistent topology estimates. In addition, a falsification-driven reliability metric evaluates how strongly each inferred connection is supported relative to alternative feasible assignments, enabling utilities to prioritize verification efforts while preserving system-wide observability. The framework is validated using operational data from three feeders comprising more than $8{,}000$ AMI meters in collaboration with a large U.S. utility. Results demonstrate over $95\%$ topology reconstruction accuracy while significantly reducing computational effort compared with global inference approaches. The study further shows that correlation-based methods alone produce ambiguous assignments in dense urban feeders, whereas combining electrical measurements with spatial and operational constraints enables robust and scalable topology recovery under realistic deployment conditions.
### Title:
          Rethinking Open-World Video Anomaly Detection: Diagnosing Definition Blindness
 - **Authors:** Inpyo Song, Jangwon Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open-world video anomaly detection (OWVAD) is expected to detect events that match a user-specified definition of abnormality. This requirement is stronger than generic anomaly localization: in the same video, changing the definition should change which temporal regions are scored as anomalous. We show that current OWVAD evaluation largely fails to isolate this conditional behavior. Standard VAD metrics and the dynamic-definition protocol can be dominated by target-versus-normal separation, allowing models to obtain strong scores while remaining nearly insensitive to the queried definition. We call this failure mode definition blindness. To explain why it is missed, we decompose dynamic-definition evaluation into target-versus-normal detection and target-versus-other-anomaly discrimination, and find that the former receives 7.2-26.8$\times$ more weight across common VAD benchmarks. Motivated by this diagnosis, we introduce three definition-conditioned evaluation metrics, DC-Disc, DC-Det$\Delta$, and DC-Sel$\Delta$, which progressively remove normal-frame, generic-anomaly, and multi-event selection shortcuts. Experiments on UCF-Crime, XD-Violence, and MSAD reveal that several strong VAD, OWVAD, and general vision language model baselines localize anomalous moments but exhibit weak definition following, often with near-zero definition-response margins. To validate that the failure is actionable, we further introduce DeCoS, a definition-contrastive scoring rule that subtracts anomaly evidence shared across definitions. DeCoS improves the strongest baseline by 7.3-16.0 AUROC points on DC-Disc and 15.5-28.3 points on DC-Det$\Delta$. Overall, our results argue that OWVAD should be evaluated as definition-conditioned anomaly scoring, not as anomaly detection under different prompt labels.
### Title:
          Spectrogram-Based Joint Detection, Localization, and Classification of Events in Continuously Recorded IBR Waveforms
 - **Authors:** Shivanshu Tripathi, Maziar Raissi, Hamed Mohsenian-Rad
 - **Subjects:** Subjects:
Sound (cs.SD); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Continuously recorded high-resolution waveform measurements provide rich information about fast power system dynamics. However, they require automated methods to identify events. This problem is addressed by developing a spectrogram-based framework to jointly detect, localize, and classify events in real-world continuously recorded waveforms at the terminal of an Inverter-Based Resource. We recast this problem as a temporal object detection problem on spectrogram images, as they capture the transient and harmonic signatures more explicitly than in raw waveform data. Each time-series waveform is transformed using the short-time Fourier transform, and the resulting per-channel spectrograms are stacked as a tensor for event detection. We benchmark this method against a detector operating directly on raw time-series measurements. Experiments on single-phase disturbances and three-phase faults demonstrate that the proposed spectrogram method consistently improves event detection, localization, and classification over the raw waveform baseline.
### Title:
          Auditing Provenance Sensitivity in LLM Agent Action Selection
 - **Authors:** Junchi Liao
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLM agents choose tools and arguments from context that mixes user requests, tool outputs, retrieved records, memory, and untrusted text. Evidence can be relevant without being authorized to determine a decision, so a correct action need not be grounded only in permitted evidence. We introduce a target-specific authorization audit that labels context factors separately for each tool and argument target. Its primary test holds the task, proposition, position, and policy fixed while changing only the proposition's source authority. We then test behavior when valid evidence is weakened and use context-subset interactions as a secondary localization diagnostic. Across 450 controlled next-action tasks and multiple open-weight LLM families, trusted and untrusted variants produce different actions in 5.4 percent of competing cases versus 1.7 percent of supporting cases. Under controlled degradation, unauthorized competition is retained in a full-correct, mixed-error, clean-correct pattern in 2.4 percent of comparisons, with a 95 percent confidence interval from 2.1 to 3.0 percent. These are controlled stress-set rates, not deployment prevalence. The models respond to textual source-authority cues, but this does not prevent untrusted evidence from influencing their actions.
### Title:
          Engine-Native Editable 3D World Reconstruction with Objects and Lighting
 - **Authors:** Junhao Chen, Xinghao Chen, Henghaofan Zhang, Zihao Qiao, Saining Zhang, Yongzhi Li, Ruqi Huang, Sisi Li, Yimin Sheng, Jianyi Zhu, Hao Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Editable 3D scene creation requires object instances and lights that can be inspected, moved, and imported into standard engines, yet existing single-image methods largely stop at room-scale geometry, baked/global illumination, or text-driven generation. We introduce Lumera (Light-aware Unified Engine-native Reconstruction and Assembly), a benchmark and reference pipeline for engine-native, light-aware 3D scene parsing from a single image. Lumera-2K is built from 2,513 UE5 projects and provides 3.73M components, 63M object instances, 102.6K engine-native parametric lights, and 95.1K camera views. On this data, Lumera-Box and Lumera-Light adapt VLM to parse object boxes and parametric light tuples (x,y,z,r,g,b,I), which are assembled with per-object mesh reconstruction, HDR environment estimation, and a bounded agentic refinement loop. In a sanitized box benchmark against DetAny3D, SpatialLM, N3D-VLM, and WildDet3D, Lumera-Box obtains the strongest overall detection, geometry, semantic, and layout scores (merged mAP 0.1141, IoU-B 0.2472, F-score 0.2762), while WildDet3D remains stronger on anchor recall. For lights, Lumera-Light recovers almost all non-empty scenes (recall 0.998) but remains limited at individual-light localization (F1 0.209 at 0.5 m); matched lights have median position error 0.261 m, median {\Delta}E2000 4.59, and intensity Pearson r=0.628. These results establish parametric lights as a measurable editable-scene target and expose remaining bottlenecks in relation structure, light recall/intensity, and cross-engine generalization.
### Title:
          RECO: Region-Aware Compensation for Extrinsic Perturbations in Roadside 3D Detection
 - **Authors:** Junsheng Du, Zhaocheng He, Yuhuan Lu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In intelligent transportation systems, roadside 3D object detection provides wide-area perception crucial for traffic understanding, cooperative early warning, and safe autonomous driving. However, existing methods suffer from high sensitivity to camera extrinsics; even slight deviations (whether manifesting as transient jitter or persistent drift) can be significantly amplified by projective geometry. This cascade results in severe feature misalignment and degraded localization. To mitigate this limitation, we propose RECO, a region-aware extrinsic compensation framework that corrects extrinsics using piecewise 6-DoF pose offsets. RECO predicts a learnable range boundary to partition the scene into near and far regions, estimating region-specific pose corrections. A differentiable sigmoid gate then smoothly blends the two compensated geometries to preserve continuous BEV sampling and facilitate stable optimization. To supervise the refinement of extrinsics, we introduce an auxiliary reprojection loss that compares 2D bounding boxes projected from 3D ground truth against 2D annotations, optimizing it jointly with the standard detection objective. Extensive experiments on the DAIR-V2X-I and Rope3D benchmarks under extrinsic perturbations demonstrate consistent improvements over state-of-the-art baselines across both yaw and $z$-axis deviations. RECO also generalizes from transient perturbations to persistent shifts, maintaining highly competitive performance under strict calibration uncertainty.
### Title:
          GroupVideo: Multi-Identity Customized Text-to-Video Generation
 - **Authors:** Xinyang Song, Libin Wang, Jianxin Sun, Qi Li, Dandan Zheng, JingDong Chen, Zhenan Sun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current identity customized video generation methodologies are predominantly limited to single-identity scenarios, as the lack of explicit identity separation mechanisms often leads to identity confusion in multi-identity settings. Existing multi-identity approaches, which directly extend single-identity frameworks by concatenating face images as input conditions, frequently result in unnatural facial expressions and motions, manifesting as the "copy-paste" phenomenon. To overcome these limitations, we introduce GroupVideo, a novel framework that leverages multiple individual photographs to generate identitycustomized video. Built upon Video Diffusion Transformers, GroupVideo incorporates multimodal identity alignment: visual alignment jointly encodes multiple face images to provide robust identity references, while semantic alignment introduces a semantic perceiver to enhance the naturalness of motions. An ID localization module with spatial guidance is introduced to address identity blending and enhance identity fidelity, along with bounding box constraints and mask regularization loss, to focus on facial regions and improve training efficiency. In response to the shortage of multi-ID video datasets, we have curated a comprehensive high-quality dataset of 20,000 videos, thereby establishing a crucial resource to advance future research in multi-ID video generation. Extensive experiments demonstrate that GroupVideo outperforms existing methods in generating multi-character videos with consistent identities and natural motions.
### Title:
          BasketEvent: Understanding Who Did What and When in Basketball Videos
 - **Authors:** Yu Zhang, Jiayuan Rao, Haoning Wu, Weidi Xie
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Comprehensive basketball video understanding requires resolving not only what event occurs, but also who is responsible and when the key evidence appears. However, exist- ing methods typically treat spatial perception and semantic recognition as isolated tasks, failing to ground events to individual players or pinpoint their temporal boundaries within complex collective dynamics. To bridge this gap, we introduce BasketEvent, a player- centric basketball event understanding dataset curated from real NBA broadcasts. In BasketEvent, event labels are grounded to the responsible players, and a manually an- notated subset of 1,000 samples with precise event intervals is provided to evaluate tem- poral evidence localization. Based on this data, we propose PlayNet, a player-centric reasoning framework that maps basketball videos to player-level event predictions with temporal evidence. Concretely, PlayNet tracks key entities, associates player identities, and reasons about events by modeling player-player, player-ball, and global court inter- actions, while aggregating sparse temporal evidence via gated pooling. Extensive experi- ments demonstrate that PlayNet significantly outperforms representative video-level and crop-based baselines, proving the superiority of player-centric modeling for fine-grained sports video understanding. Our data, code, and models will be made publicly available.
### Title:
          PC-Edit: Prompt-Contrastive Region Discovery and Region-Guided Editing
 - **Authors:** Jian Zhang, Zhijun Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Replacing an object with one that differs in category or shape requires complete source removal, natural target formation unconstrained by the source silhouette, and preservation of unrelated content. Existing training-free editors either localize edits from terminal predictions under source and target prompts or preserve unrelated content through spatially unselective source-feature reuse without explicit region discovery. Before reaching the terminal predictions, prompt-induced semantic differences undergo additional network transformations that may obscure their spatial localization, reducing localization precision. Spatially unselective feature reuse forces a trade-off between edit completeness and background preservation. Therefore, we propose PC-Edit, a prompt-contrastive framework for training-free MM-DiT editing. PC-Edit contrasts the image-token attention outputs under the source and target prompts, capturing prompt-induced semantic differences directly where text-conditioned information is delivered to image tokens. The same contrast identifies a source-erasure region during inversion and a target-emergence region during denoising. Their union suppresses source remnants while allowing the target object to form naturally. PC-Edit further couples region discovery and background preservation within each sampling step by estimating the current edit region from preceding attention blocks and immediately injecting cached source K/V features outside it in subsequent blocks, thereby protecting unrelated content before the latent update. Experiments on PIE-Bench and our EditRegion-Bench, with human-verified edit-region annotations for single- and multi-object addition and replacement, show that PC-Edit achieves the best editing quality and background preservation among methods without user-specified edit regions.
### Title:
          Multimodal Pretraining for Generalizable EEG Representation Learning
 - **Authors:** Targol Bakhtiarvand, Jugal Kalita, Adham Atyabi
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Electroencephalography (EEG) models used for epilepsy are often limited to specific datasets and tasks. This limited approach can make it challenging to apply these models across different datasets or in various situations. However, recent studies in foundation models and self-supervised learning suggest that an adaptable EEG backbone could support a range of EEG related tasks. In this study, we have developed a multimodal EEG foundation model that combines a raw signal encoder based on the Mamba architecture, a Vision Transformer (ViT)-style encoder for time-frequency data, and a lightweight encoder for text, all within a shared embedding space. The pretraining process relies on several innovative techniques, such as masked modeling, cross-view contrastive alignment, and temporal consistency losses. These methods are designed to create rich, seizure-relevant representations without requiring labeled data. To assess the efficacy and generalization of our pretrained model, we fine-tuned it on the canonical CHB-MIT seizure detection benchmark and additional seizure detection datasets, and conducted extensive experiments comparing different model variants. On the standard CHB-MIT split, our best single model achieved an AUROC of 0.874, and an ensemble variant reached 0.878 AUROC, representing state-of-the-art performance on this benchmark. In addition to standard train-test splits, we evaluated performance under a leave-one-subject-out (LOSO) protocol, which is rarely reported in prior EEG seizure modeling work and highlights the difficulty of patient-independent seizure detection, with a mean LOSO balanced accuracy of 0.558 across 19 subjects. Across datasets and evaluation settings, our multimodal foundation model enabled robust seizure detection and straightforward adaptation to new seizure detection scenarios, while also supporting interpretable seizure localization.
### Title:
          GLAM-SLAM: Real-time Gaussian Large-scale Mapping via Flow Densification and Spatial Decomposition
 - **Authors:** Panagiotis Mermigkas, Argyris Manetas, Petros Maragos
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing Gaussian-splatting-based monocular Simultaneous Localization and Mapping (SLAM) systems are either tailored to short sequences, are not real-time, or suffer from prohibitive GPU memory requirements, limiting their applicability in realistic, long-horizon scenarios. To address this, we present GLAM-SLAM, a real-time, decoupled Gaussian-splatting SLAM system designed for large-scale outdoor scenes. We ensure lightweight tracking using a robust, feature-based SLAM frontend, while for mapping, we adopt a structured, sparse anchor grid representation that ensures scalable operation and maintains scene coherence across long-term sequences. To satisfy the dense initialization requirements of 3D Gaussian Splatting (3DGS), we introduce a geometry-based flow-densification anchoring strategy using epipolar constraints. Furthermore, by treating mapping as a multi-scene problem, we propose a scene-partitioning strategy that introduces a strong spatial inductive bias via MLP initializations to generate localized Gaussians. We evaluate our system on the challenging, long-sequence KITTI Odometry, Oxford RobotCar, and M'alaga datasets. Extensive ablations and comparisons demonstrate a 15% improvement in reconstruction quality over the second-best performer, while maintaining real-time performance and the ability to scale to longer sequences. Code is publicly available for the benefit of the community.
### Title:
          Test-Time Scaling via Error Localization
 - **Authors:** Rajiv Shailesh Chitale, Rahul Madhavan, Taneesh Gupta, Deepanway Ghosal, Aravindan Raghuveer
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scaling inference-time computation has emerged as a reliable method to improve the performance of large language models on complex reasoning and programming tasks. However, standard approaches such as independent sampling and sequential multi-turn refinement operate without token-level credit assignment, resulting in computational inefficiency, since valid reasoning prefixes are frequently discarded. In this work, we introduce Test-Time Scaling via Error Localization (TTEL), an inference-time algorithm that utilizes fixed or environment feedback to perform token-level error localization. By comparing conditional probabilities under informed feedback against a null-context baseline, TTEL isolates the step at which an error occurred. The algorithm then truncates the trajectory and branches a new generation, maximally reusing the valid prefix. Extensive evaluations demonstrate that TTEL establishes strictly dominating Pareto frontiers across sequential reasoning domains, measured by pass-at-k vs. generated-token cost. With Qwen3-8B on LiveCodeBench, TTEL attains a pass@64 of 71.0% while generating approximately half as many tokens as independent sampling (360.4k vs. 735.0k). Generalizing to math benchmarks AIME-2025 and HMMT-2025, TTEL cleanly outperforms competing test-time baselines across both Qwen3-8B and Qwen3-4B-Thinking-2507.
### Title:
          White Box Evidence Packages for Policy Audit Reports
 - **Authors:** Seunghyun Yoo
 - **Subjects:** Subjects:
Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As AI governance moves from benchmark scores toward auditable oversight, a central question is how reviewers can tell whether an LLM-generated audit report is actually supported by evidence. This paper studies that question in passage-anchored policy audits, where a report must interpret a given policy passage and cite evidence for its claims. We introduce a controlled evaluation framework that holds the passage, rubric, and auditor model fixed while changing only the evidence interface supplied to the auditor. Across 60 AGORA policy cases, we generate 600 structured reports under ten evidence conditions, including passage-based evidence, internal model evidence, a hybrid package, and a shuffled control that preserves evidence format while breaking case relevance. Five human reviewers evaluate the primary interfaces for correctness, passage grounding, diagnostic usefulness, and evidence misuse. The results show that internal evidence changes how reports cite and reason about evidence, but more internal citations do not by themselves make a report more valid. A white-box diagnostic explains the failure mode: causal localization is narrow, while reports readily reuse broader readable labels and token directions. The hybrid interface is the most useful on average, while the shuffled control exposes a key governance risk: reports can sound substantively plausible while citing irrelevant internal evidence. This study reframes internal model access as an evidence design problem for audit workflows, rather than as a guarantee of transparency.
## Keyword: transformer
### Title:
          Knowledge Injection Exists in MoE? Exploring Expert-Aware Contrast Decoding in MoE for Mitigating LLMs'Hallucinations
 - **Authors:** Xinyue Fang, Zhiliang Tian, Zhen Huang, Ziyi Pan, Zhihua Wen, Xi Wang, Quntian Fang, Dongsheng Li
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing LLM hallucination mitigation methods, including prompt engineering and model optimization, either hardly alter models'internal knowledge or have poor cross-domain generalization. Contrastive decoding mitigates hallucinations by using layer-wise differences in LLMs. However, prior studies only explore transformer-based models (e.g., GPT), ignoring other effective frameworks like mixture-of-experts (MoE) models. Since MoE alters the traditional transformer architecture, we conduct empirical studies to investigate whether similar layer-wise differences exist in MoEs. Our results show that they do not exist in MoE with shared experts; nevertheless, across different MoEs, higher layers exhibit distinct expert activation patterns between factual and non-factual outputs. Building on these, we propose EAACD, an expert-aware adaptive contrast decoding that uses expert differences in MoE's higher layers to mitigate hallucinations on QA tasks. EAACD splits high-layer experts into a higher-reliability group and several lower-reliability groups based on their confidence and consistency. It contrasts the higher-reliability group's prediction with each lower-reliability group's prediction to calibrate the model's original predictions. To strengthen this contrast, EAACD amplifies hallucinations from lower-reliability experts via attention and masking to provide stronger negative references. EAACD outperforms all baselines on four datasets.
### Title:
          thaulab@EEUCA 2026: Who Said What to Whom? A Targeting-Aware Neural-Symbolic Pipeline for Gaming Toxicity Detection
 - **Authors:** Anmol Guragain, Marcos Estecha-Garitagoitia, Luis Fernando D'Haro Enríquez, Ricardo de Córdoba
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper describes our system for the EEUCA 2026 Shared Task on toxicity classification in gaming chat. We implement a three-stage pipeline combining an ensemble of two compact transformers (DeBERTa-v3-base, 184M; XLM-RoBERTa-base, 278M) with a Linguistically-Informed Mediator (LIM) that resolves inter-model disagreements through corpus-backed lexical normalization, class-conditional unigram scoring, multilingual profanity detection, and agentive targeting analysis grounded in speech act theory. The LIM specifically targets the minority classes (Hate \& Harassment, Threats, and Extremism), which are the most safety-critical categories in real-world gaming moderation. To address the extreme class imbalance (1{,}450:1 Non-toxic to Extremism ratio), we introduce a two-stage data augmentation strategy using only the provided training data. Our system achieves a Macro F1 of 0.6441 and accuracy of 0.9062 on the official test set, ranking 3rd in Macro F1 and 1st in accuracy among all teams. The proposed pipeline is domain-portable: adapting to other gaming platforms requires substituting only the game-specific entity lexicon. Code is publicly available at this https URL\_EEUCA.
### Title:
          ClickGuard: Detecting and Spoiling Clickbait News with Informativeness Measures and Large Language Models
 - **Authors:** Wojciech Michaluk, Tymoteusz Urban, Mateusz Kubita, Soveatin Kuntur, Anna Wróblewska
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents an AI-driven browser extension that identifies clickbait to help users avoid misleading Internet articles. Moving beyond traditional detection, the application employs a hybrid machine learning architecture that combines transformer-based embeddings with linguistically motivated features and a custom "baitness" score. After evaluating various natural language processing techniques -- from classic vectorizers to large language model (LLM) embeddings -- an XGBoost-based model was developed that achieves an F1-score of 91% on the open combined dataset. Most importantly, the tool can warn users before and after they access a clickbait article. After opening an article, the user receives a percentage score indicating the likelihood that it is clickbait. The prediction is explained based on the analyzed metrics, including those specifically developed within the proposed system. The browser extension also provides a clickbait spoiler -- a one- to two-sentence summary of the entire article. Demo video:this https URL}{this https URL
### Title:
          The Devil is in the Spectrum: Mitigating Representation Collapse in LLMs via Topologically Regularized Side-Path
 - **Authors:** Yiheng Tao, Kaiwen Cheng, Yao Lu, Chang Liu, Jie Chen
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) are fundamentally limited by representation collapse, a bottleneck that severely degrades long-context performance. We identify that existing approaches risk drifting into one of two pathological extremes: homogenization collapse (e.g., attention sinks causing rank deficiency) and isolation collapse (e.g., local attention causing context disconnection). Through spectral analysis of attention dynamics, we derive an intrinsic trade-off between mixing efficiency (spectral gap) and information capacity (effective rank) that standard mechanisms struggle to balance. To resolve this dilemma, we propose the Topologically Regularized Side-Path (TRSP), a non-invasive architectural intervention that achieves spectral balance. TRSP employs a parameter-free Triangular Box mechanism, scaled by a lightweight, length-aware gate, to regularize the token interaction topology. By integrating proximal coupling to preserve effective rank and distal propagation to support non-degenerate mixing, TRSP promotes a geometrically healthier transition operator without altering core attention. Experiments show significant improvements across general capabilities and long-context benchmarks. Notably, on NoLiMa at $8\times$ the training length, TRSP retains $83\%$ accuracy and surpasses the Differential Transformer and Gated Attention by approximately 30 and 50 percentage points, respectively. Code available at: this https URL.
### Title:
          OPTScientist: Multi-Agent Discovery of Typed Optimizer Programs for Transformer Pretraining
 - **Authors:** Zhongzheng Li, Tiancan Feng, Wenhao Li, Qingsong Ran, Shikun Feng, Xiaoyuan Zhang, Yue Wang, Xiaoguang Zhao
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Designing optimizers for modern deep learning remains a challenging scientific problem, requiring the joint consideration of optimization geometry, state dynamics, numerical stability, implementation constraints, and empirical generalization. Existing automated optimizer discovery methods typically search either over unconstrained code spaces or within narrowly parameterized optimizer families. The former is flexible but often produces invalid or uninterpretable programs, while the latter is stable but limits novelty. We introduce OPTScientist, a theory-guided multi-agent framework for optimizer discovery in a typed domain-specific language (DSL). OPTScientist formulates optimizer design as a constrained scientific search process, where candidate updates are expressed through direction, scaling, preconditioning, regularization, state, and grouping modules. Four role agents, Theorist, Designer, Engineer, and Reviewer, collaborate within a single orchestration loop to propose hypotheses, synthesize DSL candidates, compile and evaluate optimizers, and critique results. To overcome the limitations of a fixed search space, OPTScientist combines evolutionary search over optimizer programs with a second-stage mechanism that proposes small DSL extensions when repeated failures reveal representational bottlenecks. Using this framework, we discover RS-MR, a reduced-state matrix optimizer that improves transformer pretraining over strong baselines under our native evaluation protocol. Our results suggest a path toward automated optimizer science grounded in theory, typed programs, compiler validation, and closed-loop experimentation.
### Title:
          HERMES: Heterogeneous Edge-Relational Multi-Head Embedded SSM Attention for Traffic Conflict Prediction at Signalized Intersections
 - **Authors:** Md Monzurul Islam, Subasish Das
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Surrogate safety measures (SSMs) enable proactive traffic safety assessment, but many existing methods evaluate pairwise interactions independently or flatten multi-agent scenes into fixed feature vectors, limiting their ability to represent heterogeneous interaction structure and evolving scene-level risk. This study formulates traffic conflict assessment as temporal heterogeneous scene-graph classification and proposes HERMES, a heterogeneous edge-relational graph neural network with SSM-informed multi-head attention. Vehicles and pedestrians are represented as heterogeneous nodes, while vehicle-vehicle, vehicle-pedestrian, and pedestrian-pedestrian interactions are encoded as relation-specific edges with continuous kinematic and surrogate-safety descriptors. Relation-specific attention, dynamic node-edge updates, safety-aware graph pooling, and temporal sequence learning are jointly used to estimate scene-level conflict probability. HERMES was evaluated using 109,028 trajectory-derived sequences from a signalized urban intersection and tested on an independently collected comparable intersection dataset. Enhanced HERMES achieved an AUC-ROC of 0.9898 +/- 0.0013, an AUC-PR of 0.9412 +/- 0.0067, and an F1 score of 0.8449 +/- 0.0103. At a 5% false-alarm rate, it detected 95.7% of conflict sequences, outperforming the strongest Transformer baseline and XGBoost. In zero-shot external evaluation, HERMES achieved an AUC-ROC of 0.9752 and an AUC-PR of 0.7829. Joint source-target training further improved target-site performance with limited target-site data. These findings show that preserving heterogeneous interaction topology, safety-informed edge semantics, and short-term temporal evolution improves scene-level conflict classification and supports transferable roadside safety monitoring at signalized intersections.
### Title:
          Adaptive Depth in Looped Transformers: Diagnosing Learned Halting Gates and Trajectory Readouts
 - **Authors:** Andrei Cristian Popescu, Haitz Sáez de Ocáriz Borde, Pietro Liò
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Looped Transformers increase test-time computation by repeatedly applying a shared recurrent block. Learned halting objectives in looped Transformers typically use a single exit distribution both as the inference-time stopping rule and as the training-time weighting of per-depth losses. This entangles exit selection with trajectory formation: the gate not only chooses which recurrent state to use, but also determines how strongly each intermediate state is supervised. Consequently, poor adaptive-compute performance can arise from the readout, the induced trajectory, or their interaction. We study adaptive depth in looped Transformers through this trajectory--readout lens, across controlled synthetic tasks (modular arithmetic and binary parity) and large-scale Ouro-1.4B and 2.6B checkpoints. We find that fixed-prior depth supervision, which shapes the trajectory without an input-dependent halting policy, produces difficulty-aware trajectories whose intermediate states expose useful stopping signals, and that simple post-hoc confidence readouts often match or outperform learned linear and MLP gates. Fitting gates on frozen trajectories localizes the failure: it appears to stem mainly from the trajectory induced by joint gate training rather than from limited gate expressivity. The same pattern is present in Ouro evaluations, where pretrained ponder gates are competitive but not uniformly Pareto-optimal, and measured latency confirms that the resulting reductions in average exit depth translate into practical inference-time savings. Our systematic diagnostic evaluation reframes adaptive depth in looped Transformers as a joint problem of trajectory formation and exit readout, rather than gate learning alone, highlighting a distinction that prior learned-halting work has often left implicit.
### Title:
          Attention Degradation, Function Token Anchoring, and the Limits of Attention-Based Intervention in Large Language Models
 - **Authors:** Sagar Dangal, Manoj Shakya
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mean cross-positional attention degradation is widely reported in transformer interpretability, yet whether it causally limits contextual retrieval remains untested. We present six coordinated experiments across GPT-2, LLaMA-3.2-1B/3B, OPT-1.3B, and distilgpt2. We first characterise short-term (5-100 token) attention degradation, finding a universal exponential-then-plateau pattern whose rate is inversely correlated with depth, with distinct layer-wise entropy signatures per architecture. Function token anchoring proves architecture-dependent: OPT-1.3B (absolute positional encoding) shows distance-dependent preposition specificity, GPT-2 shows uniform non-specific dependence, and LLaMA (RoPE) shows reversal at long distances. Strategic comma insertion at clause boundaries causally reduces prediction degradation in the 40-80 token range, with the benefit tied to syntactic boundary alignment rather than token density. We then test the mechanism causally: Relay-Aware Attention (RAA), which biases attention logits toward function token positions, verifiably increases attention mass by 16-24% yet yields null effects on GPT-2 and LLaMA-1B, preliminary harm on LLaMA-3B, and a mixed effect on OPT-1.3B that nets to approximately zero. Multi-fact retrieval probes further show that degradation rate does not predict retrieval accuracy across models. We conclude that mean attention degradation is largely descriptive rather than prescriptive: function tokens contribute through what their hidden states compute, not through the attention they receive -- with implications for interpretability methodology and attention-score-based inference optimisations such as KV-cache eviction.
### Title:
          Codec-Gauge: Learning Compression-Friendly Gauges for Transformer KV Caches
 - **Authors:** Yitao Jiang, Yaoqing Yang, Luyang Zhao, Muhao Chen, Devin Balkcom
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long-context Transformer inference increasingly relies on KV-cache compression or quantization. Prior rotation and transform-coding results suggest that the channel basis of each key/value vector affects how faithfully a fixed backend preserves model behavior. We introduce Codec-Gauge, a post-training cache-coordinate layer that learns small orthogonal channel transforms around existing compression and quantization backends. Its frequency-distribution objective combines a token-channel DCT spectral-centroid loss with a smooth rate proxy to concentrate KV energy in low-frequency codec-facing layouts. We evaluate actual compression and decompression using measured bytes and rolling compressed-history scoring. Across six models at $3$, $4$, and $6$ bits/value, learned gauges reduce zfp KL divergence by $44.0\%$ on average relative to raw coordinates and outperform random, Hadamard, DCT, and PCA/KLT controls. The same gauges improve quality preservation for block-uniform and KIVI-style quantization. Experiments on a 27B model and long-context task prompts reproduce the quality trend, while serial storage and timing measurements validate the implemented compressed-cache paths. These results establish cache-coordinate geometry as a practical post-training variable for improving compression fidelity without changing model weights, attention semantics, or backend coding rules.
### Title:
          Thermodynamic Weight Decay: Exploring Grokking Acceleration via Attention Specific Heat
 - **Authors:** Chitraansh Pandey
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Grokking -- the delayed generalization of neural networks long after they have memorized their training data -- wastes thousands of training epochs and is notoriously unpredictable. Building on the recent result that Transformer attention is formally isomorphic to a thermodynamic system, we treat the variance of attention logits as a specific heat Cv and show that its peak reliably precedes the generalization transition. We introduce CvAdamW, a drop-in AdamW variant that monitors Cv online and injects thermal energy by dynamically scaling weight decay when a phase transition is detected. Through a strictly iterative development process we identify three failure modes -- initialization noise, mini-batch micro-ripples, and slingshot blinding -- and resolve them with a memorization gate and an exponential-moving-average shock absorber. On modular arithmetic (a+b mod 97), CvAdamW enables grokking at epoch 2802 in a 4000-epoch budget where the baseline never groks. We further propose a scale-invariant z-score reformulation that removes task-specific hyperparameters, and evaluate it across 10 paired seeds. A paired analysis shows the cold-start variant reduces mean grokking latency by 257 epochs (6.0%; median 166 epochs; Wilcoxon p=0.049, Cohen's d=0.68, bootstrap 95% CI [53,489]), improving 8 of 10 seeds; on this single task Cv peaks before grokking in all 10 seeds. Our results indicate that neural networks may expose detectable precursors of impending generalization transitions, and that a physically motivated, proportional intervention can facilitate generalization within a fixed compute budget. Code and data are public.
### Title:
          Monkey King Bang: A Unified Scientific Multimodal Foundation Model
 - **Authors:** Hesen Chen, Xinyu Su, Xiaomeng Yang, Yuetan Lin, Zixiong Yang, Junyi An, Fenglei Cao, Yifeng Jiao, Yunqi Zhang, Yuan Cheng, Zhiyu Tan, Hao Li, Libo Wu, Yuan Qi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scientific discovery is increasingly shifting from isolated disciplines to multi-domain reasoning, and AI for science faces a similar transition. Existing systems are either specialised for individual domains or unify scientific data mainly through text tokenisation and prompt-based interfaces, limiting their ability to handle diverse scientific inputs, produce modality-native outputs, and support joint understanding, reasoning, and generation across scientific domains. We introduce MKB, a unified scientific multimodal model for both understanding and generation, built around a shared Transformer backbone and modality-tailored encoders, adapters, and decoders. MKB covers six scientific branches, including DNA, RNA, proteins, small molecules, earth science, and medical images, and supports native outputs such as biological sequences, molecular strings, meteorological fields, and segmentation masks. Training follows a two-stage modality-then-language curriculum: Stage 1 aligns modality-specific components with the frozen backbone, and Stage 2 consolidates them with the language backbone using mixed scientific and general corpora. Experiments show that MKB achieves competitive scientific understanding across biological and molecular benchmarks, produces high-fidelity native outputs for weather forecasting, biological generation, and medical-image segmentation, and largely retains the general capabilities of its Qwen3-VL backbone. These results demonstrate the feasibility of the proposed paradigm, suggesting that shared-backbone models with modality-tailored components can provide a promising foundation for future cross-domain scientific multimodal exploration. The model and code are publicly available at this https URL and this https URL.
### Title:
          AI-Driven Surrogate Models for Predicting Electrode-Scale Discharge Behavior in Lithium-Ion Batteries
 - **Authors:** Mengda Xing (CRIL, UA), Jean-Marie Lagniez (CRIL, UA), Alejandro Franco (LRCS)
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Physics-based simulations are essential for understanding the electrode-scale discharge behavior of lithium-ion batteries (LIBs) but suffer from prohibitive computational costs. To address this, we introduce a novel deep learning surrogate pipeline based on the Swin3D Transformer to predict spatiotemporal discharge dynamics directly from volumetric data. Our approach integrates two key innovations: Gaussian Positional Encoding (GPE), which enhances spatial feature representation by adapting to the complex geometry of electrode microstructures, and a specialized Temporal Encoding module to capture non-linear timeseries evolution. Experimental validation on an Electrochemical Simulation (ES) dataset demonstrates that our pipeline significantly outperforms state-of-the-art point cloud baselines in prediction accuracy. Furthermore, the proposed method reduces the computational overhead by orders of magnitude, providing a scalable and efficient framework for high-throughput battery design and optimization.
### Title:
          When Does Recurrence Become an Algorithm? Convergence Selection in Weight-Tied Looped Transformers
 - **Authors:** Tong Zhang, Junhao Hu, Yun Peng, Tao Xie
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 When does a weight-tied looped transformer -- one block applied T times -- implement an actual algorithm? We answer with four findings from controlled populations on group word problems. (1) The budget law: free training installs a linear computation frontier, a mechanism that solves v positions per loop, whose speed is priced by the training contract: v ~ n_train/T_train (exponent 0.98 +/- 0.04, R^2=0.99), exactly unity under T=n training. SGD selects a frontier matching the minimum the contract demands; granting more test-time loops than ever trained rescues late positions at fixed input length, yielding a principled halting rule T* = ceil(n / v-hat). (2) Architecture prior, not expressivity, picks the algorithm: standard-depth transformers learn parallel scans on this family; weight tying flips the selection to the serial frontier, even when positional addressing for a log-depth scan is supplied. At matched depth and parameters, untied models extrapolate worst and fail to learn A5 at all. (3) The walls are not where circuit complexity says: NC1-completeness costs nothing (A5 generalizes fully), while group order does (S5's 120x120 operator deadlocks joint learning) -- and an operator-first curriculum dissolves the wall in every seed. (4) Mechanisms are portable, not mandatable: warm-starting across budget contracts transfers the algorithm in every seed, re-pricing its speed, while imposing seriality through the input schedule fails where free training succeeds. These results are invisible to standard instruments, which provably saturate at the fixed points trained loops converge to. We introduce a head instrument, the convergence-time scaling tau(n,i), validate it causally via damage cones whose slope reproduces v, and show in-distribution head measurements predict out-of-distribution fate where tail metrics do not. Results replicate on the public easy-to-hard benchmark.
### Title:
          Scaling Interpretable Transformers with Parity Bottleneck Layers
 - **Authors:** Andrew Mack, Kraig Yuheng Tou, Mark Henry, Zhengxun Wu, Lauren Greenspan
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Language models are thought to exhibit the phenomenon of superposition, representing many more features than dimensions in their residual streams. Sparse autoencoders (SAEs) are designed to recover such features post-hoc, but training models that are interpretable by construction has remained impractical, as a per-layer over-complete bottleneck is prohibitively expensive in both memory and compute. To overcome this issue, we introduce the ParityTransformer, a GPT-2-scale architecture whose intermediate representations are efficient and wide / sparse by design. At each layer, a Deep Parity Bottleneck (DPB) replaces a learned over-complete basis with a parameter-free algebraic dictionary, providing a deterministic incoherence guarantee and eliminating the memory requirements that have prevented per-layer interpretable bottlenecks at scale. A DPB is a hierarchically structured sparse bottleneck which efficiently enforces sparsity using a multi-level mixture-of-experts approach: a hardware-aware implementation that closes the cost gap between activation sparse and dense training to a manageable interpretability tax. Empirically, ParityTransformers perform at least as well as post-hoc SAEs on sparse probing tasks, while out-performing on measures of feature absorption, steering effectiveness, and fine-grained causal interventions. Because subsequent computation acts only on features that survive the sparse bottleneck, the ParityTransformer's features are native to the model's forwards pass by construction, addressing the question of whether SAEs probe features the model actually uses during computation. We see this as a step toward training models whose internal representations are interpretable by design rather than recovered post hoc.
### Title:
          Leaky Language Models: Stealing Architecture and Inference Optimizations via Per-Token Timing
 - **Authors:** Sadegh Majidi, Niloofar Mireshghallah, Kazem Taram
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work presents LeakyLMs, a set of attacks that leak proprietary model, architecture, and deployment information from production language models. LeakyLMs is the first to demonstrate that key model and deployment details can be inferred using only token generation timing, even when interacting through remote APIs. LeakyLMs introduces two core attacks. The first attack targets inference optimizations and deployment strategies. For example, our attack detects whether a provider uses speculative decoding, a widely deployed inference-time optimization, and further identifies the context length of the draft model used in the pipeline. Our measurements show that Google Gemini Flash 2.5 uses speculative decoding with a draft context window of approximately 128K tokens. The second attack recovers key architectural properties, including the number of transformer layers, hidden dimension size, and number of attention heads. To achieve this, LeakyLMs builds a detailed and accurate model of token-generation timing on modern NVIDIA GPUs, characterizing how latency scales with model configuration and hardware parameters. The attack then performs a search over the architecture space using this timing model. In experiments with Llama models, the near-correct architectural configuration appears in the top-10 guesses more than 90% of the time.
### Title:
          GaugeQuant: Online Learning of Quantization-Optimal Bases from LLM Symmetries
 - **Authors:** Miguel P. Bento, João Seabra
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers are known to have internal continuous symmetries that leave outputs invariant, while modifying quantization. GaugeQuant leverages this in-training by introducing a LogSumExp term to the loss that breaks the symmetries, thus selecting a basis that minimizes activation outliers. A stop-gradient operator ensures that only rotation matrices are updated, yielding the language modeling objective completely unaltered. Our requires no specific calibration data, no quantization simulation, and adds negligible training overhead. With the LLaMA-2 7B model under W4A4 quantization with group size 128, perplexity drops from 8.22 to 6.73, competing with post-training methods that require frozen models and calibration datasets. Under W4A16, perplexity drops from 11.16 to 5.45. Code is available at this https URL.
### Title:
          The Geometry of Personality: Activation Steering with Jungian Cognitive Functions
 - **Authors:** Liu Zai (1), Yumeng Wang (2), Junchen Fu (1), Joemon M. Jose (1) ((1) University of Glasgow, (2) Leiden University)
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Activation steering enables control and interpretation of LLMs, yet existing work primarily models personality through static trait frameworks such as the Big Five. We investigate whether personality can instead be represented and controlled as a set of cognitive processes using the eight Jungian Cognitive Functions. To this end, we introduce a framework comprising a Jungian evaluation protocol and a dataset of over 2,100 role-playing character narrations. Activation steering vector extraction and evaluation experiments on Llama-3.1-8B demonstrate effective monotonic control over all eight cognitive functions through activation steering. Beyond controllability, our analysis reveals that: 1. personality information is concentrated in middle transformer layers; 2. steering vectors exhibit structured geometric relationships consistent with distinctions between rational and irrational functions; 3. effective multi-dimensional steering directions cannot be recovered as linear combinations of single-function directions. These findings provide new insights into the representation of personality in LLM activation space and establish a framework for studying interpretable, effective, and multi-dimensional personality control.
### Title:
          MagicMakeup: A Region-Controllable Diffusion Transformer for High-Fidelity Makeup-Transfer
 - **Authors:** Ziyi Wang, Siming Zheng, Yang Yang, Shusong Xu, Hao Zhang, Bo Li, Changqing Zou, Peng-Tao Jiang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Makeup-transfer applies the reference makeup to the source face while preserving the source identity. Despite advances in full-face editing by diffusion-based methods, strong regional controllability, makeup fidelity, and identity preservation remain challenging. The reasons are (i) pixel-to-attention misalignment that causes spillover into non-target areas and weakens regional control; (ii) unclear transfer/preservation concept separation under two-image conditioning, leading to coupling between makeup attributes and identity; and (iii) the lack of a high-resolution dataset that is identity-consistent and region-labeled for fine-grained supervision. In this paper, we propose MagicMakeup, a diffusion transformer-based framework for region-controllable and high-fidelity makeup transfer, built on spatial constraints and concept disentanglement. To enable precise region-specific editing while preserving identity, we propose Token-Aligned Region Gating, which aligns pixel masks with attention and applies region-specific logit gating. To clarify the concepts of transfer and preservation, we further introduce Cross-Modal Perception Guidance, which aligns text and image features to enhance cross-modal concept perception. We also design a pipeline for the generation of 1024 x 1024 data pairs through region-specific makeup removal and establish a unified benchmark in synthetic and real settings. Extensive quantitative and qualitative experiments show that MagicMakeup improves regional controllability, makeup fidelity, and identity preservation, with strong robustness across styles, races, and poses.
### Title:
          Transformer-Assisted LLM-Based Source Code Summarisation: to Enable More Secure Software Development
 - **Authors:** Jesse Phillips, Tracy Hall, Paul Rayson, Mo El-Haj
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural Source Code Summarisation (NSCS) aims to generate natural language summaries of source code to improve developers' and maintainers' understanding of code. Source code summaries are vital during the maintenance phase of the Secure Software Development Lifecycle (SSDLC), as they improve maintainers' understanding of code and help reduce the number of bugs and vulnerabilities in a software system. However, summaries are often missing, incomplete, or outdated in many software systems. Solutions to this problem use small, task-specific Transformer models or code-aware Large Language Models (LLMs). Task-specific Transformer-generated summaries often score well across many natural language generation (NLG) metrics, but these metrics reward lexical overlap rather than summary quality. Conversely, the ability of LLMs to capture semantics and produce high-quality summaries presents an exciting solution to this problem. This is especially relevant given the increased availability of LLMs and improvements in workstation hardware in recent years, which mean that some LLMs can now be run on developers' workstations. However, because of their abstractive nature, LLM-generated code summaries often differ greatly from developer-written summaries in the words and phrases they use, resulting in low scores across NLG metrics. We show how combining these two methods, by using Transformer-generated summaries in prompt engineering, may enable LLMs to create better source code summaries and help software practitioners maintain secure systems. We prompt four LLMs using four different prompts, with a task-specific Transformer used to assist the LLMs within the prompts. We present "Transformer-Assisted LLM-Based Source Code Summarisation", a method through which we observe an improvement of 7.8% in BLEU-4 and 5%.
### Title:
          Naju: A Native Discrete State-Space Model with Independent Retention and Writing for Long-Sequence Memory
 - **Authors:** Hyuk Lim, Seunghyun Yoon
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long-sequence memory tracking places two opposing demands on a recurrent state: near-lossless retention of stored bindings over long horizons, and active overwriting of stale ones. In our diagnostic suite, the strongest efficient baselines tend to solve only one side well. Continuous-time-parameterized state-space models (SSMs) such as Mamba obtain their discrete recurrence by zero-order-hold discretization of a continuous-time system; we argue that this detour is unnecessary for memory tracking and parameterize the discrete transition directly. Naju (Native Adaptive Junction Unit) factorizes the recurrent update, schematically $x_n = f_n\odot x_{n-1} + i_n\odot(B_n u_n)$, into an explicit discrete pole (a learned forget gate $f_n$), an independent write gain $i_n$, and input-dependent write/read maps. Since the sigmoid pole satisfies $0<f_n<1$, each frozen local coordinate is Schur-stable by construction, and the full time-varying recurrence satisfies a fading-memory/BIBO bound under uniform boundedness assumptions, with no stability regularizer. We formalize the key structural limitation of coupled designs: any non-expansive complementary single-gate recurrence ties the effective retention $r$ and write gain $w$ through $|r|+w\le 1$, so near-complete retention forces weak writing; decoupling $f_n$ from $i_n$ removes this constraint. Empirically, Naju is the only evaluated model that remains strong on both retention and overwriting at 4x the training length. Beyond the diagnostic suite, we evaluate Naju on WikiText-103 language modeling, Long Range Arena, and multi-query associative recall. Across these settings, Naju consistently combines strong long-range memory with competitive or superior performance, outperforming the Mamba baselines in the principal comparisons while remaining competitive with the Transformer and preserving linear-time, linear-memory scaling.
### Title:
          GroupVideo: Multi-Identity Customized Text-to-Video Generation
 - **Authors:** Xinyang Song, Libin Wang, Jianxin Sun, Qi Li, Dandan Zheng, JingDong Chen, Zhenan Sun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current identity customized video generation methodologies are predominantly limited to single-identity scenarios, as the lack of explicit identity separation mechanisms often leads to identity confusion in multi-identity settings. Existing multi-identity approaches, which directly extend single-identity frameworks by concatenating face images as input conditions, frequently result in unnatural facial expressions and motions, manifesting as the "copy-paste" phenomenon. To overcome these limitations, we introduce GroupVideo, a novel framework that leverages multiple individual photographs to generate identitycustomized video. Built upon Video Diffusion Transformers, GroupVideo incorporates multimodal identity alignment: visual alignment jointly encodes multiple face images to provide robust identity references, while semantic alignment introduces a semantic perceiver to enhance the naturalness of motions. An ID localization module with spatial guidance is introduced to address identity blending and enhance identity fidelity, along with bounding box constraints and mask regularization loss, to focus on facial regions and improve training efficiency. In response to the shortage of multi-ID video datasets, we have curated a comprehensive high-quality dataset of 20,000 videos, thereby establishing a crucial resource to advance future research in multi-ID video generation. Extensive experiments demonstrate that GroupVideo outperforms existing methods in generating multi-character videos with consistent identities and natural motions.
### Title:
          Faster IndexTTS-2: Accelerating and Streaming Autoregressive Zero-Shot Text-to-Speech Synthesis on GPUs
 - **Authors:** Muyang Du, Shuang Yu, Junjie Lai
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autoregressive text-to-speech models achieve strong naturalness but suffer from slow inference due to sequential token generation, limiting their deployment in production applications that require low latency. IndexTTS-2 is a state-of-the-art autoregressive TTS model consisting of a GPT, a flow-matching Diffusion Transformer, and a vocoder. Despite its high synthesis quality, its inference speed barely reaches real-time without streaming or batching support. We present Faster IndexTTS-2, which accelerates all neural network components of IndexTTS-2 for production deployment on GPUs using NVIDIA TensorRT and TensorRT-LLM. Faster IndexTTS-2 also enables streaming synthesis for latency-sensitive interactive applications, and batched inference across all components to maximize GPU utilization. Experiments on the Seed-TTS benchmark for both English and Chinese demonstrate up to 5.0$\times$ speedup on the autoregressive GPT and 3.6$\times$ end-to-end, with minimal degradation in word error rate, speaker similarity, and naturalness. Our methodology provides a practical reference for efficiently accelerating similar autoregressive speech models on GPUs.
### Title:
          Human-Inspired Framework for Robotic Craniotomy: Integrating Multimodal Fusion and Adaptive Trajectory Adjustment
 - **Authors:** Renzhen Le, Xiao Zhang, Di Wu, Yuanyu Wei, Jiachen Zhu, Zhenzhi Ying, Pengfei Zhang, Liming Shu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Manual craniotomy is a high-risk, skill-dependent procedure associated with surgeon fatigue and potential dural injury. While robotic approaches have improved safety, existing open-loop systems rely solely on preoperative images and cannot compensate for intraoperative registration errors or tissue deformation. To address this, we propose a human-inspired closed-loop robotic craniotomy framework that intelligently integrates preoperative planning with intraoperative execution. An adaptive dual-contour fusion algorithm is employed to generate trajectories that conform to complex cranial geometries while maintaining a consistent tool-bone relative pose. For intraoperative perception, a multimodal two-stage cross-modal attention block (CMA)-temporal convolutional network (TCN)-Transformer network combined with an adaptive Bayesian filter fuses force and acoustic signals to achieve robust breakthrough detection under varying bone conditions. Upon detection, an in-situ projection-based trajectory adjustment strategy dynamically compensates for depth deviations, enabling safe residual bone isolation. Experiments on bovine ribs show a breakthrough prediction accuracy of 97%, a detection latency of 0.048 +/- 0.097 s, and a maximum overshoot of 0.29 mm. All four ex vivo cranial experiments were successfully completed without dural injury. These results demonstrate that the proposed cybernetic framework enables safe and autonomous craniotomy with highly effective closed-loop control.
### Title:
          Spectral Transformation for Layer-wise Global Rank Discovery in Federated LoRA for Vision Transformers
 - **Authors:** Hariharan Ramesh, Jyotikrishna Dass
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fine-tuning Vision Transformers (ViTs) with low-rank adapters (LoRA) promises better communication efficiency under federated setup, yet existing aggregation strategies face fundamental limitations. Independently averaging these LoRA factors is mathematically inconsistent, introducing cross-term aggregation error. In contrast, approaches that preserve heterogeneous client ranks by concatenating local adapters on the server substantially increase download cost and often require merging global LoRA updates into pretrained weights on the clients, causing reinitialization lag and unstable convergence. Other approaches further increase server-side overhead by reconstructing dense weight updates or training auxiliary models to refine aggregation error. In this work, we propose SpecTraL, spectral transformation for layer-wise global rank discovery, that resolves these challenges within a unified design. SpecTraL stacks local LoRA modules from clients and performs orthonormal Householder Transformation of the stacked adapters directly in the low-rank latent space, eliminating dense reconstruction of the global update and any auxiliary refinement on the server. By leveraging the Spiked Covariance Model from Random Matrix Theory, SpecTraL analytically separates the global consensus signal from non-IID noise, discovering optimal layer-wise global ranks without manual hyperparameter tuning. To match local ranks in subsequent rounds, we introduce a padding-aware initialization framework that lets clients incorporate residual LoRA dimensions without re-merging them into the pre-trained base model. Experiments on federated fine-tuning of ViT-B/16 and ViT-L/16 over DomainNet and NICO++ demonstrate improved accuracy-communication trade-offs, reduced server computation, and elimination of hyperparameter search for rank selection. Our code is available at this https URL
### Title:
          CASC: Causal Adversarial Subspace Clustering for Multivariate Spatiotemporal Data
 - **Authors:** Francis Ndikum Nji, Vandana Janeja, Jianwu Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep subspace clustering plays a critical role in applications involving multivariate spatiotemporal data, such as sea ice monitoring, disease spread analysis, and tracking neuro-degeneration over time. Despite recent advances, existing methods primarily rely on geometric self-expressiveness, assume static subspace structures, and often fail to capture causal dependencies, local spatial interactions, and long-range temporal dynamics inherent in complex spatiotemporal systems. To address these limitations, we propose a novel Causal Adversarial Subspace Clustering (CASC) framework for discovering evolving latent regimes in high-dimensional spatiotemporal data. CASC integrates a U-Net-inspired deep adversarial clustering architecture with stacked FAConvLSTM layers to preserve spatial and temporal structure while learning robust latent representations. A graph attention transformer-based self-expressive network is introduced to jointly model local spatial relationships, global dependencies, and long-range temporal interactions. Furthermore, we propose two new learning objectives: (1) a Causal Subspace Preservation Loss that aligns self-expression coefficients with latent causal relationships, encouraging clusters to reflect underlying causal processes rather than simple feature similarity, and (2) a Dynamic Temporal Subspace Evolution Loss that captures evolving subspace structures and temporal regime transitions in nonstationary environments. Together, these components transform deep subspace clustering from a correlation-driven paradigm into a causal-temporal regime discovery framework.
### Title:
          TF-MossFormer: Integrating Convolution Gated Local-Global Attentions for Enhanced Time-Frequency Domain Monaural Speech Separation
 - **Authors:** Shengkui Zhao, Zexu Pan, Haoxu Wang, Biao Tian, Bin Ma, Xiangang Li
 - **Subjects:** Subjects:
Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers with global attention capture long-range dependencies but can miss the fine-grained local continuity crucial for speech separation. We propose TF-MossFormer, a time-frequency transformer that combines local and global attention to jointly model short- and long-range contexts for monaural speech separation. At its core is a content-aware sliding-window attention mechanism that dynamically adapts receptive fields for stronger local interactions, avoiding the rigidity of static convolutions. Unlike time-domain chunk-based methods, TF-MossFormer leverages the 2D spectrogram to model structure along both time and frequency axes. Convolutional gating between attention layers further improves feature selection and information flow. TF-MossFormer achieves SI-SDRi of 22.6, 24.0, and 24.4 dB on WSJ0-2Mix with 5.9M, 16.9M, and 25.4M parameters, respectively, outperforming prior approaches.
### Title:
          Agree on the Model, Verify the Inference: GKR Protocols for HND-Based Transformer Inference
 - **Authors:** Xiaolong Liang, Juanjuan Li, Rui Qin, Yisheng Lv
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Outsourced Transformer inference exposes clients to model substitution and incomplete execution, while direct replay removes the computational benefit of delegation. We present GKR-HND, a registered-model protocol for verifying the polynomial backbone of Homomorphic--Nonhomomorphic Decomposition Transformers. The retained verifier checks the GKR transcript and registered-weight openings, but delegates expensive public evaluations to an assigned computation worker. Assuming an honest retained verifier and prover--worker non-collusion, the verifier accepts only when the worker's signed, request-bound response agrees with the proof claims. Experiments with pretrained HND models validate the proof path and the delegated public computation without dense-matrix replay.
### Title:
          DART: A Degradation-Aware Recurrent Transformer for Archival Film Restoration
 - **Authors:** Mikołaj Jastrzębski, Wojciech Kozłowski, Kamil Adamczewski
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Archival film restoration is a challenging problem because historical footage contains compound degradations such as scratches, dust, blur, noise, flicker, and photometric aging, while clean reference videos are unavailable. Existing video restoration methods largely treat these degradations implicitly, reconstructing frames without explicit knowledge of where damage occurs or how severe it is. We propose DART, a degradation-aware recurrent transformer for archival film restoration. DART predicts and propagates a soft defect mask through time, using it to guide temporal fusion and condition the restoration network on both damage location and severity. This makes the restoration process explicitly aware of film artifacts rather than relying only on reconstruction losses. Experiments on real archival benchmarks show that DART improves no-reference perceptual quality over prior restoration architectures while remaining compact and efficient, producing cleaner and more temporally consistent restorations of structured film damage.
### Title:
          A Comparative Evaluation of Embeddings and LLMs in a Greek Book Publisher Setting - The CUP Dataset
 - **Authors:** Katerina Papantoniou, Panagiotis Papadakos, Theodore Patkos, Dimitris Garefalakis, Nikos Vardakis, Dimitris Plexousakis
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present CUP, a Greek book retrieval benchmark consisting of 868 catalog records and 104 expert-annotated queries with graded relevance judgments. We evaluate sparse (BM25), dense (sentence-transformers), hybrid, and LLM-assisted retrieval methods in this book-search setting. Multilingual embeddings outperform Greek-specific models, while hybrid retrieval performs best overall. A query-level analysis shows that BM25 excels at named-entity queries, while dense and hybrid methods improve natural-language, noisy, cross-lingual, and concept queries. Field-aware prompting has model-specific effects, while LLM TOC summarization improves TOC-only retrieval and LLM post-filtering improves early-stage retrieval at a high cost. Overall, CUP enables real-world evaluation of Greek retrieval across lexical, semantic, noisy, and cross-lingual queries.
### Title:
          Adaptive Depth Sparse Framework: Similarity-Driven Resource Allocation for Pre-Trained LLMs
 - **Authors:** Yidu Wu, Xiang Wang, Kejie Zhao, Zhangchi Wang, Qinghai Guo, Xiaoying Tang
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) achieve strong generation and reasoning performance, but the Transformer architecture incurs high inference cost. Existing acceleration methods often rely on task-specific fine-tuning or training from scratch, increasing adaptation cost and limiting cross-task usability. We present an Adaptive Depth Sparse Framework (AdaDSF) that converts off-the-shelf pre-trained LLMs into depth-sparse models without full retraining. Our key insight is that layers contribute unequally to representation transformation, characterized by the cosine similarity between layer input and output hidden states. Based on this, AdaDSF assigns layer-wise token retention ratios from similarity statistics, uses a lightweight router to select informative tokens at each layer, and introduces a feature-preserving alignment objective to match intermediate and final representations between sparse and dense models. On GPT-NeoX and Qwen2.5 over language modeling and commonsense reasoning, AdaDSF substantially reduces inference FLOPs while preserving performance close to dense counterparts. Under comparable sparsity, AdaDSF consistently yields smaller accuracy degradation than strong baselines including MoD, D-LLM, and DLO.
### Title:
          SlerpFlow: Spherical Trajectory Correction for Rectified Flow Inversion
 - **Authors:** Wenbin Duan, Yan Shu, Zhuoyuan Fu, Fangmin Zhao, Yan Li, Yaru Zhao, Binyang Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rectified-flow-based diffusion transformers, particularly FLUX, have demonstrated outstanding performance in high-quality image generation. However, achieving fast and accurate inversion--transforming images back to latent noise for faithful reconstruction and editing--remains a challenging bottleneck due to the discretization errors of linear solvers. This paper introduces SlerpFlow, a straightforward yet highly effective zero-shot approach that unlocks the full potential of FLUX for high-fidelity inversion and editing. Unlike existing approaches (e.g., RF-Solver) that rely on complex numerical approximations such as high-order Taylor expansions to correct trajectory errors, we present a geometric view based on the Manifold Hypothesis: the empirically observed trajectory curvature is not a numerical artifact, but rather serves as a necessary "centripetal force" that constrains the flow to remain on the data manifold. Guided by this insight, SlerpFlow integrates Spherical Linear Interpolation (Slerp) to rectify flow velocity directions on the hypersphere, strictly adhering to the intrinsic curvature of the latent space. Crucially, by caching the corrected velocity for subsequent steps, SlerpFlow achieves high-precision inversion while maintaining the computational efficiency of a first-order Euler solver. Extensive experiments on FLUX-based reconstruction and editing tasks demonstrate that SlerpFlow improves reconstruction fidelity and achieves stronger semantic alignment in editing without requiring additional training. Code is available at this https URL.
### Title:
          Multimodal Pretraining for Generalizable EEG Representation Learning
 - **Authors:** Targol Bakhtiarvand, Jugal Kalita, Adham Atyabi
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Electroencephalography (EEG) models used for epilepsy are often limited to specific datasets and tasks. This limited approach can make it challenging to apply these models across different datasets or in various situations. However, recent studies in foundation models and self-supervised learning suggest that an adaptable EEG backbone could support a range of EEG related tasks. In this study, we have developed a multimodal EEG foundation model that combines a raw signal encoder based on the Mamba architecture, a Vision Transformer (ViT)-style encoder for time-frequency data, and a lightweight encoder for text, all within a shared embedding space. The pretraining process relies on several innovative techniques, such as masked modeling, cross-view contrastive alignment, and temporal consistency losses. These methods are designed to create rich, seizure-relevant representations without requiring labeled data. To assess the efficacy and generalization of our pretrained model, we fine-tuned it on the canonical CHB-MIT seizure detection benchmark and additional seizure detection datasets, and conducted extensive experiments comparing different model variants. On the standard CHB-MIT split, our best single model achieved an AUROC of 0.874, and an ensemble variant reached 0.878 AUROC, representing state-of-the-art performance on this benchmark. In addition to standard train-test splits, we evaluated performance under a leave-one-subject-out (LOSO) protocol, which is rarely reported in prior EEG seizure modeling work and highlights the difficulty of patient-independent seizure detection, with a mean LOSO balanced accuracy of 0.558 across 19 subjects. Across datasets and evaluation settings, our multimodal foundation model enabled robust seizure detection and straightforward adaptation to new seizure detection scenarios, while also supporting interpretable seizure localization.
### Title:
          Adaptive Identity Anchoring: Closed-Loop Keyframe Placement for Synthetic Paired Supervision in Video Face Swapping
 - **Authors:** Logan Robbins
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video face swapping has no natural paired supervision: no real footage exists of one person's face performing another person's video. The strongest current answer, DreamID-V's SyncID-Pipe, mints pairs by replacing the identity in exactly two frames of a real clip -- the first and the last -- and regenerating the rest from a pose sequence alone. Pose carries no appearance evidence of the swapped-in identity, so over long clips, occlusions, and extreme pose excursions the synthesized identity has a long unanchored span on which to drift; no published ablation examines anchor count or placement. We propose Adaptive Identity Anchoring (AIA): (i) generalize the synthesizer to arbitrary anchor sets, architecturally natural for diffusion-forcing-style transformers where conditioning on a frame is clamping its tokens to zero noise; (ii) place anchors by a closed feedback loop that scores every generated frame against the real reference identity and inserts an image-face-swapped anchor at the worst-scoring frame until the pair passes a threshold or exhausts a budget; (iii) reuse the loop's verdict as an automatic data filter. A second pathology, the beauty-filter look of over-smoothed skin, has the same root cause: micro-texture, like identity, is priced by none of the pipeline's objectives. We therefore pair AIA with Reality-Referenced Texture Restoration: matched re-graining from each real frame's non-face regions, band-split transfer of sub-identity micro-texture from the real footage, and a second, spectral acceptance channel refereed by the footage's own spectrum. Identity-anchor density, we argue, is a controllable quality dial, and we specify falsifiable experiments -- drift-versus-gap curves, uniform-versus-adaptive placement at matched budgets, student training on AIA-minted data, and texture ablations with a human beauty-filter study -- that would validate or refute the proposal.
### Title:
          KroQuant: Kronecker-Structured Block Transforms for Efficient Post-Training Quantization of Diffusion Transformers
 - **Authors:** Yann Bouquet, Alireza Khodamoradi, Kristof Denolf, Mathieu Salzmann
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Post-training quantization (PTQ) of diffusion transformers (DiTs) to W4A4 severely degrades output quality, because activations entering each linear layer contain outliers that 4-bit formats cannot represent. The standard fix applies an invertible linear transform to the activations and its inverse to the weights before quantizing both. Normalization layers between blocks force this transform to run online at every denoising step, making its inference computation cost the binding design constraint. Existing options trade quantization quality for inference cost: per-channel scaling (SmoothQuant) is computationally cheap but impacts the magnitude of the channels, which can harm quantization accuracy; fixed Hadamard transforms yield better quantization accuracy but require large block sizes that incur a high online cost; learned full-$d$ invertible transforms calibrate best but entail a prohibitive dense $d \times d$ matrix multiplication (GEMM) per layer per step. We propose KroQuant, a PTQ method that applies a learned Kronecker-structured invertible transform to each 32-element block of the activation, storing less than half the parameters of per-channel scaling. The block-local structure runs as small tensor-core GEMMs, and on an MI350 GPU the KroQuant quantizer kernel is up to $14\%$ faster than the SmoothQuant kernel. Offline LoRaQ weight calibration then absorbs the residual per-weight quantization error. On PixArt-$\Sigma$, SANA, and FLUX.1-schnell at W4A4 (MXFP4e2), KroQuant produces outputs closer to the FP reference than SVDQuant and LoRaQ on MJHQ-30K and SDCI, while preserving or improving image quality.
### Title:
          SANA-Video 2.0: Hybrid Linear Attention with Attention Residuals for Efficient Video Generation
 - **Authors:** Junsong Chen, Jincheng Yu, Yitong Li, Shuchen Xue, Haozhe Liu, Jingyu Xin, Yuyang Zhao, Tian Ye, Zhangjie Wu, Zian Wang, Daquan Zhou, Ping Luo, Song Han, Enze Xie
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce SANA-Video 2.0, a hybrid video diffusion transformer instantiated at 5B and 14B scales under a unified architecture. Designed to generate high-quality video up to 720p on a single GPU, SANA-Video 2.0 matches full-softmax video DiTs in quality while retaining the favorable long-sequence scaling of linear attention. To avoid quadratic attention throughout, Hybrid Linear-Softmax Attention combines gated linear attention for O(N)-dominated mixing with periodic gated-softmax anchors at a 3:1 ratio, restoring the full-rank token interactions that pure linear attention lacks. To propagate these refreshed representations across depth, Block Attention Residuals (AttnRes) route completed block summaries into later linear layers, enabling anchor-feature reuse and boosting deep-layer effective rank by ~12%. Through from-scratch training, SANA-Video 2.0 learns the complete hybrid directly rather than linearizing pretrained models, with reduced-resolution proxy studies establishing 25% softmax as the optimal quality-efficiency trade-off. With 40-step sampling, SANA-Video 2.0 achieves a VBench score of 84.30 in 13.2s at 480p on a single H100, remaining competitive with far larger softmax video DiTs at a fraction of the latency. Its compiled DiT forward pass is 3.2x faster than a matched full-softmax baseline at 720p/60s, a gap that expands with video duration. Furthermore, full-stack Sol-Engine optimization (kernel fusion, caching, and sparse attention) accelerates this hardware-friendly backbone by a further 3.58x, bringing the 5B pipeline to 13.06s at 720p/5s and making it 120x faster than Wan 2.2-A14B on one H100. Overall, our hybrid design recovers softmax-level expressiveness at substantially reduced cost, unlocking scalable long, high resolution video generation.
### Title:
          Self-Supervised Learning of Structured Dynamics from Videos
 - **Authors:** Lukas Knobel, Andrew Zisserman, Yuki M. Asano
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding motion in video is a fundamental challenge for visual learning, as frame-to-frame change entangles two sources of dynamics: camera motion and object motion. This decomposition has remained underexplored in representation learning, partly because these factors are tightly coupled in natural videos and difficult to supervise separately. Yet recovering it is important for learning robust motion representations that separate meaningful object dynamics from camera-induced variation. We study whether such structured motion representations can be recovered from frozen features of a pretrained image vision transformer. We propose the Structured Dynamics Model (SDM), which explicitly separates the dominant source of temporal change from residual dynamics through future-feature prediction, rather than representing video change with a single entangled latent or with unstructured, spatially dense transition tokens. Training combines self-supervised learning on real video with weak supervision of scene dynamics on synthetic Kubric data. We evaluate SDM on ProbeMotion, a new evaluation suite spanning synthetic and real videos with camera motion, object motion, and combined dynamics. SDM outperforms backbone baselines using global CLS or average-pooled features, and compares favorably to strongly supervised representations such as VGGT on several probes, despite using substantially weaker supervision. These results suggest that pretrained image models can be readily repurposed into structured video-dynamics representations, providing a useful inductive bias for learning and analyzing latent video dynamics.
### Title:
          Synthetic data generation framework for quality control automation in gravure printing
 - **Authors:** Korota Arsène Coulibaly, Mohamed Hamlich, Khalid Hmali, Andrea Trombin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Quality control in printing, particularly in rotogravure printing, still depends on slow, costly, and subjective manual inspection. Automated surface defect detection is critical for maintaining high-quality standards in rotogravure printing. Deep learning models give prospects for automation. However, training robust deep learning models, such as YOLO or Vision Transformers, is heavily hindered by the extreme scarcity of real-world industrial defects images. To overcome this limitation, this paper introduces a novel synthetic data generation framework tailored for rotogravure printing quality control. The proposed pipeline automatically generates high-fidelity images of specific printing defects (creases, streaks, misregistration, etc.) and outputs corresponding bounding boxes and annotations. To validate the framework, a synthetic dataset of 7533 images was generated and used to train the state-of-the-art object-detection model RFDETR. Experimental results demonstrate that the model trained on our synthetic data achieves a Mean Average Precision (mAP) of 80.9\% on real industrial testing samples. This framework provides a zero-cost, rapid-deployment solution for automating defect inspection in printing lines without requiring massive manual data collection.
### Title:
          Streaming Multi-Agent Autoregressive Diffusion Model with World State Registers
 - **Authors:** Sicheng Mo, Yuheng Li, Ziyang Leng, Krishna Kumar Singh, Bolei Zhou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-agent interactive world models should not only generate consistent observations, but also maintain world states that persist across agents and evolve across views. Existing autoregressive video diffusion pipelines carry forward observation history as conditioning context, which makes shared state difficult to maintain in multi-agent and multi-view settings. We present WorldWeaver (W^2), a streaming multi-agent video diffusion model that augments rollout with cross-agent world state registers: learnable tokens that store shared world information, track individual agent status, and are dynamically updated after each generated chunk. We ground these registers with supervision signals spanning individual agent status, global state views including bird's-eye views, and scene text. We further improve the architecture with a Mixture-of-Transformers design that uses separate weights for world state modeling and visual frame modeling. Extensive experiments in two-agent Minecraft video generation show that explicit world-state modeling improves logical consistency and generation quality.
## Keyword: autonomous driving
### Title:
          RECO: Region-Aware Compensation for Extrinsic Perturbations in Roadside 3D Detection
 - **Authors:** Junsheng Du, Zhaocheng He, Yuhuan Lu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In intelligent transportation systems, roadside 3D object detection provides wide-area perception crucial for traffic understanding, cooperative early warning, and safe autonomous driving. However, existing methods suffer from high sensitivity to camera extrinsics; even slight deviations (whether manifesting as transient jitter or persistent drift) can be significantly amplified by projective geometry. This cascade results in severe feature misalignment and degraded localization. To mitigate this limitation, we propose RECO, a region-aware extrinsic compensation framework that corrects extrinsics using piecewise 6-DoF pose offsets. RECO predicts a learnable range boundary to partition the scene into near and far regions, estimating region-specific pose corrections. A differentiable sigmoid gate then smoothly blends the two compensated geometries to preserve continuous BEV sampling and facilitate stable optimization. To supervise the refinement of extrinsics, we introduce an auxiliary reprojection loss that compares 2D bounding boxes projected from 3D ground truth against 2D annotations, optimizing it jointly with the standard detection objective. Extensive experiments on the DAIR-V2X-I and Rope3D benchmarks under extrinsic perturbations demonstrate consistent improvements over state-of-the-art baselines across both yaw and $z$-axis deviations. RECO also generalizes from transient perturbations to persistent shifts, maintaining highly competitive performance under strict calibration uncertainty.
### Title:
          Update the Unseen Only: Minimizing AoI for Collaborative Perception through Online Learning
 - **Authors:** Yanan Ma, Zhuoyi Zhao, Zhengru Fang, Haonan An, Xianhao Chen, Yuguang Fang
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While collaborative perception (CP) enhances the safety of autonomous driving, limited bandwidth can cause severe shared data staleness in CP systems. Existing age-of-information (AoI) minimization policies are not well-suited for CP, as they overlook the fact that a vehicle's AoI decreases not only through updates from the source (i.e., a base station) but also through the vehicle's local sensing. To address this issue, we propose a mobility-aware AoI minimization framework for CP that explicitly accounts for vehicles' dynamic sensing ranges. We first derive a closed-form expression for the long-term time average sum AoI within a considered region, accommodating an ever-changing vehicle population and their dynamic sensed areas. Based on this characterization, we develop Local-sensing-aware Max-Weight Scheduling (LocMW), an online learning algorithm designed for sensor information broadcast from a source to vehicles under unknown environmental statistics and delayed observations. We provide performance guarantees demonstrating that LocMW achieves a sublinear cumulative excess AoI compared to the optimal stationary randomized benchmark. Extensive simulations using vehicular trajectory datasets and 3D perception tasks demonstrate that our LocMW policy substantially outperforms competing baselines, reducing the time-averaged sum AoI by up to 31.6% and improving mAP detection accuracy by up to 16.3%.
### Title:
          HyWorldVLA: A Vision-Language-Action Model with Hybrid World Modeling for Autonomous Driving
 - **Authors:** Quanfu Yu, Xian Wu, Hao Xu, Liulong Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models augmented with world modeling represent a promising paradigm for end-to-end autonomous driving. While pixel-level future prediction enables fine-grained spatiotemporal reasoning, it compromises robustness in noisy driving scenarios. Conversely, latent-based world models alleviate this sensitivity but often incur limited interpretability and representational degradation due to absent pixel-level grounding. To reconcile this trade-off, we propose HyWorldVLA, a hybrid world-VLA framework that unifies pixel-level supervision and latent representation learning. In the pre-training stage, HyWorldVLA predicts video latents encoded by a pre-trained video VAE, while simultaneously reconstructing video frames to provide precise pixel-level grounding. During the subsequent co-fine-tuning phase, the model exclusively predicts latent features, which are fed into an action expert to generate trajectories. Extensive experiments on NAVSIM v1 and v2 benchmarks demonstrate that HyWorldVLA significantly outperforms both pixel-based and latent-based world model baselines. Notably, we present the first comprehensive qualitative and quantitative analysis of world model noise robustness in autonomous driving, establishing a new benchmark for evaluating future architectures.
### Title:
          HGeo-TopoMap: Boosting Topological Mapping with Hierarchical Geometric Priors
 - **Authors:** Siyu Li, Kunyu Peng, Di Wen, Beiping Hou, Zhiyong Li, Kailun Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Topological maps are key outputs of autonomous driving perception systems, delivering essential road information for path planning. They identify instances such as centerlines and traffic signs, along with their connectivity relationships. Due to the lack of explicit markings for centerlines in real-world environments, the detection of centerline instances remains a significant challenge. To tackle this problem, we propose HGeo-TopoMap, which leverages an explicit prior map and implicit spatial relations to hierarchically boost topological mapping. First, a geometric adaptive learning module is designed for the road structure map obtained via inverse perspective mapping. This module discretely encodes semantic and spatial features from the map, followed by a prior-mask attention mechanism that selectively focuses on informative regions. Then, a geometric consistency learning module is devised, which leverages the geometric properties and spatial relationships of centerlines. Built on the geometry-aware decoder, it enforces spatial consistency by aligning features of centerline instances with identical geometric orientations. The proposed method is evaluated on the OpenLane-V2 dataset across the centerline, lane segment, and robustness benchmarks. Beyond substantial improvements in topological mapping accuracy, the proposed method offers the benefit of enhanced robustness, consistently outperforming baselines under both standard and challenging conditions. The source code and model weights will be made publicly available at this https URL.
### Title:
          Boosting Robustness for All-Weather Self-Supervised Depth Estimation in Autonomous Driving
 - **Authors:** Mengshi Qi, Xiaoyang Bi, Xianlin Zhang, Huadong Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-supervised depth estimation is challenging for safe autonomous driving under various adverse weather conditions due to sensor perception degradation. These challenges arise from two main aspects. Firstly, adverse conditions can distort pixel correspondences and violate the assumptions embedded in the self-supervised loss function, leading to erroneous depth predictions. Secondly, while radar is a widely adopted sensor in adverse weather conditions, the sparse distribution of radar points in the Point of View (POV) poses challenges for self-supervised fusion. To address these issues, we introduce a novel self-training pipeline using unpaired real all-weather data through multi-teacher distillation and robust radar fusion. We propose the Uncertainty-Aware Multi-Teacher Distillation method to generate diverse teacher models with different adverse condition inputs, and then employ uncertainty modeling to weigh the knowledge distillation loss. Additionally, we design the POV-BEV Radar Fusion approach, which leverages camera-pixel ray constraints to establish connections between the camera's Point of View (POV) and the radar's Bird's-Eye View (BEV). This approach enables the utilization of denser radar points, effectively capturing the complementary perspectives of both POV and BEV. Extensive quantitative and qualitative experiments demonstrate the robustness of our proposed method on all-weather datasets, achieving state-of-the-art performance. Our code and models are available at this https URL.
