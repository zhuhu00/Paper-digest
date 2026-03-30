# Showing new listings for Monday, 30 March 2026
## Keyword: SLAM
### Title:
          Massive Parallel Deep Reinforcement Learning for Active SLAM
 - **Authors:** Martín Arce Llobera, Julio A. Placed, Mariano De Paula, Pablo De Cristóforis
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in parallel computing and GPU acceleration have created new opportunities for computation-intensive learning problems such as Active SLAM -- where actions are selected to reduce uncertainty and improve joint mapping and localization. However, existing DRL-based approaches remain constrained by the lack of scalable parallel training. In this work, we address this challenge by proposing a scalable end-to-end DRL framework for Active SLAM that enables massively parallel training. Compared with the state of the art, our method significantly reduces training time, supports continuous action spaces and facilitates the exploration of more realistic scenarios. It is released as an open-source framework to promote reproducibility and community adoption.
## Keyword: odometry
There is no result 
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          BEVMAPMATCH: Multimodal BEV Neural Map Matching for Robust Re-Localization of Autonomous Vehicles
 - **Authors:** Shounak Sural, Ragunathan Rajkumar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Localization in GNSS-denied and GNSS-degraded environments is a challenge for the safe widespread deployment of autonomous vehicles. Such GNSS-challenged environments require alternative methods for robust localization. In this work, we propose BEVMapMatch, a framework for robust vehicle re-localization on a known map without the need for GNSS priors. BEVMapMatch uses a context-aware lidar+camera fusion method to generate multimodal Bird's Eye View (BEV) segmentations around the ego vehicle in both good and adverse weather conditions. Leveraging a search mechanism based on cross-attention, the generated BEV segmentation maps are then used for the retrieval of candidate map patches for map-matching purposes. Finally, BEVMapMatch uses the top retrieved candidate for finer alignment against the generated BEV segmentation, achieving accurate global localization without the need for GNSS. Multiple frames of generated BEV segmentation further improve localization accuracy. Extensive evaluations show that BEVMapMatch outperforms existing methods for re-localization in GNSS-denied and adverse environments, with a Recall@1m of 39.8%, being nearly twice as much as the best performing re-localization baseline. Our code and data will be made available at this https URL.
### Title:
          4DRaL: Bridging 4D Radar with LiDAR for Place Recognition using Knowledge Distillation
 - **Authors:** Ningyuan Huang, Zhiheng Li, Zheng Fang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Place recognition is crucial for loop closure detection and global localization in robotics. Although mainstream algorithms typically rely on cameras and LiDAR, these sensors are susceptible to adverse weather conditions. Fortunately, the recently developed 4D millimeter-wave radar (4D radar) offers a promising solution for all-weather place recognition. However, the inherent noise and sparsity in 4D radar data significantly limit its performance. Thus, in this paper, we propose a novel framework called 4DRaL that leverages knowledge distillation (KD) to enhance the place recognition performance of 4D radar. Its core is to adopt a high-performance LiDAR-to-LiDAR (L2L) place recognition model as a teacher to guide the training of a 4D radar-to-4D radar (R2R) place recognition model. 4DRaL comprises three key KD modules: a local image enhancement module to handle the sparsity of raw 4D radar points, a feature distribution distillation module that ensures the student model generates more discriminative features, and a response distillation module to maintain consistency in feature space between the teacher and student models. More importantly, 4DRaL can also be trained for 4D radar-to-LiDAR (R2L) place recognition through different module configurations. Experimental results prove that 4DRaL achieves state-of-the-art performance in both R2R and R2L tasks regardless of normal or adverse weather.
### Title:
          DRUM: Diffusion-based Raydrop-aware Unpaired Mapping for Sim2Real LiDAR Segmentation
 - **Authors:** Tomoya Miyawaki, Kazuto Nakashima, Yumi Iwashita, Ryo Kurazume
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR-based semantic segmentation is a key component for autonomous mobile robots, yet large-scale annotation of LiDAR point clouds is prohibitively expensive and time-consuming. Although simulators can provide labeled synthetic data, models trained on synthetic data often underperform on real-world data due to a data-level domain gap. To address this issue, we propose DRUM, a novel Sim2Real translation framework. We leverage a diffusion model pre-trained on unlabeled real-world data as a generative prior and translate synthetic data by reproducing two key measurement characteristics: reflectance intensity and raydrop noise. To improve sample fidelity, we introduce a raydrop-aware masked guidance mechanism that selectively enforces consistency with the input synthetic data while preserving realistic raydrop noise induced by the diffusion prior. Experimental results demonstrate that DRUM consistently improves Sim2Real performance across multiple representations of LiDAR data. The project page is available at this https URL.
### Title:
          Line-of-Sight-Constrained Multi-Robot Mapless Navigation via Polygonal Visible Regions
 - **Authors:** Ruofei Bai, Shenghai Yuan, Xinhang Xu, Xingyu Ji, Xiaowei Li, Hongliang Guo, Wei-Yun Yau, Lihua Xie
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-robot systems rely on underlying connectivity to ensure reliable communication and timely coordination. This paper studies the line-of-sight (LoS) connectivity maintenance problem in multi-robot navigation with unknown obstacles. Prior works typically assume known environment maps to formulate LoS constraints between robots, which hinders their practical deployment. To overcome this limitation, we propose an inherently distributed approach where each robot only constructs an egocentric visible region based on its real-time LiDAR scans, instead of endeavoring to build a global map online. The individual visible regions are shared through distributed communication to establish inter-robot LoS constraints, which are then incorporated into a multi-robot navigation framework to ensure LoS-connectivity. Moreover, we enhance the robustness of connectivity maintenance by proposing a more accurate LoS-distance metric, which further enables flexible topology optimization that eliminates redundant and effort-demanding connections. The proposed framework is evaluated through extensive multi-robot navigation and exploration tasks in both simulation and real-world experiments. Results show that it reliably maintains LoS-connectivity between robots in challenging environments cluttered with obstacles, even under large visible ranges and fragile minimal topologies, where existing methods consistently fail. Ablation studies also reveal that topology optimization boosts navigation efficiency by around $20\%$, demonstrating the framework's potential for efficient navigation under connectivity constraints.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          Massive Parallel Deep Reinforcement Learning for Active SLAM
 - **Authors:** Martín Arce Llobera, Julio A. Placed, Mariano De Paula, Pablo De Cristóforis
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in parallel computing and GPU acceleration have created new opportunities for computation-intensive learning problems such as Active SLAM -- where actions are selected to reduce uncertainty and improve joint mapping and localization. However, existing DRL-based approaches remain constrained by the lack of scalable parallel training. In this work, we address this challenge by proposing a scalable end-to-end DRL framework for Active SLAM that enables massively parallel training. Compared with the state of the art, our method significantly reduces training time, supports continuous action spaces and facilitates the exploration of more realistic scenarios. It is released as an open-source framework to promote reproducibility and community adoption.
### Title:
          Methods for Knowledge Graph Construction from Text Collections: Development and Applications
 - **Authors:** Vanni Zavarella
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Virtually every sector of society is experiencing a dramatic growth in the volume of unstructured textual data that is generated and published, from news and social media online interactions, through open access scholarly communications and observational data in the form of digital health records and online drug reviews. The volume and variety of data across all this range of domains has created both unprecedented opportunities and pressing challenges for extracting actionable knowledge for several application scenarios. However, the extraction of rich semantic knowledge demands the deployment of scalable and flexible automatic methods adaptable across text genres and schema specifications. Moreover, the full potential of these data can only be unlocked by coupling information extraction methods with Semantic Web techniques for the construction of full-fledged Knowledge Graphs, that are semantically transparent, explainable by design and interoperable. In this thesis, we experiment with the application of Natural Language Processing, Machine Learning and Generative AI methods, powered by Semantic Web best practices, to the automatic construction of Knowledge Graphs from large text corpora, in three use case applications: the analysis of the Digital Transformation discourse in the global news and social media platforms; the mapping and trend analysis of recent research in the Architecture, Engineering, Construction and Operations domain from a large corpus of publications; the generation of causal relation graphs of biomedical entities from electronic health records and patient-authored drug reviews. The contributions of this thesis to the research community are in terms of benchmark evaluation results, the design of customized algorithms and the creation of data resources in the form of Knowledge Graphs, together with data analysis results built on top of them.
### Title:
          Do Neurons Dream of Primitive Operators? Wake-Sleep Compression Rediscovers Schank's Event Semantics
 - **Authors:** Peter Balogh
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We show that they do. Schank's conceptual dependency theory proposed that all events decompose into primitive operations -- ATRANS, PTRANS, MTRANS, and others -- hand-coded from linguistic intuition. Can the same primitives be discovered automatically through compression pressure alone? We adapt DreamCoder's wake-sleep library learning to event state transformations. Given events as before/after world state pairs, our system finds operator compositions explaining each event (wake), then extracts recurring patterns as new operators optimized under Minimum Description Length (sleep). Starting from four generic primitives, it discovers operators mapping directly to Schank's: MOVE_PROP_has = ATRANS, CHANGE_location = PTRANS, SET_knows = MTRANS, SET_consumed = INGEST, plus compound operators ("mail" = ATRANS + PTRANS) and novel emotional state operators absent from Schank's taxonomy. We validate on synthetic events and real-world commonsense data from the ATOMIC knowledge graph. On synthetic data, discovered operators achieve Bayesian MDL within 4% of Schank's hand-coded primitives while explaining 100% of events vs. Schank's 81%. On ATOMIC, results are more dramatic: Schank's primitives explain only 10% of naturalistic events, while the discovered library explains 100%. Dominant operators are not physical-action primitives but mental and emotional state changes -- CHANGE_wants (20%), CHANGE_feels (18%), CHANGE_is (18%) -- none in Schank's original taxonomy. These results provide the first empirical evidence that event primitives can be derived from compression pressure, that Schank's core primitives are information-theoretically justified, and that the complete inventory is substantially richer than proposed -- with mental/emotional operators dominating in naturalistic data.
### Title:
          R-PGA: Robust Physical Adversarial Camouflage Generation via Relightable 3D Gaussian Splatting
 - **Authors:** Tianrui Lou, Siyuan Liang, Jiawei Liang, Yuze Gao, Xiaochun Cao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Physical adversarial camouflage poses a severe security threat to autonomous driving systems by mapping adversarial textures onto 3D objects. Nevertheless, current methods remain brittle in complex dynamic scenarios, failing to generalize across diverse geometric (e.g., viewing configurations) and radiometric (e.g., dynamic illumination, atmospheric scattering) variations. We attribute this deficiency to two fundamental limitations in simulation and optimization. First, the reliance on coarse, oversimplified simulations (e.g., via CARLA) induces a significant domain gap, confining optimization to a biased feature space. Second, standard strategies targeting average performance result in a rugged loss landscape, leaving the camouflage vulnerable to configuration this http URL bridge these gaps, we propose the Relightable Physical 3D Gaussian Splatting (3DGS) based Attack framework (R-PGA). Technically, to address the simulation fidelity issue, we leverage 3DGS to ensure photo-realistic reconstruction and augment it with physically disentangled attributes to decouple intrinsic material from lighting. Furthermore, we design a hybrid rendering pipeline that leverages precise Relightable 3DGS for foreground rendering, while employing a pre-trained image translation model to synthesize plausible relighted backgrounds that align with the relighted this http URL address the optimization robustness issue, we propose the Hard Physical Configuration Mining (HPCM) module, designed to actively mine worst-case physical configurations and suppress their corresponding loss peaks. This strategy not only diminishes the overall loss magnitude but also effectively flattens the rugged loss landscape, ensuring consistent adversarial effectiveness and robustness across varying physical configurations.
### Title:
          SWE-PRBench: Benchmarking AI Code Review Quality Against Pull Request Feedback
 - **Authors:** Deepak Kumar
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce SWE-PRBench, a benchmark of 350 pull requests with human-annotated ground truth for evaluating AI code review quality. Evaluated against an LLM-as-judge framework validated at kappa=0.75, 8 frontier models detect only 15-31% of human-flagged issues on the diff-only configuration, demonstrating that AI code review remains far below human expert performance despite strong results on code generation benchmarks. Pull requests are drawn from active open-source repositories, filtered from 700 candidates using a Repository Quality Score, and evaluated under three frozen context configurations: diff only (config_A), diff with file content (config_B), and full context (config_C), enabling systematic ablation of context provision strategies. All 8 models degrade monotonically from config_A to config_C, even when context is provided via structured semantic layers including AST-extracted function context and import graph resolution. The dominant mechanism is a collapse of Type2_Contextual issue detection at config_B, consistent with attention dilution in long contexts: a structured 2,000-token diff-with-summary prompt outperforms a 2,500-token full-context prompt enriched with execution context, behaviour mapping, and test signatures across all 8 models. The top four models are statistically indistinguishable (mean score 0.147-0.153) while a clear tier gap separates them from the remaining four (mean score <= 0.113). Dataset, contexts, annotations, and evaluation harness are released publicly.
### Title:
          Aging States Estimation and Monitoring Strategies of Li-Ion Batteries Using Incremental Capacity Analysis and Gaussian Process Regression
 - **Authors:** Moritz Landwehr, Patrick Hoher, Johannes Reuter
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing approaches for battery health forecasting often rely on extensive cycling histories and continuously monitored cells. In contrast, many real-world scenarios provide only sparse information, e.g. a single diagnostic cycle. In our study, we investigate state of health (SoH)- and remaining useful life (RUL) estimation of previously unseen lithium-ion cells, relying on cycling data from begin of life (BOL) to end of life (EOL) of multiple similar cells by using the publicly available Oxford battery aging dataset. The estimator applies incremental capacity analysis (ICA)-based feature extraction in combination with data-efficient regression methods. Particular emphasis is placed on a multi-model Gaussian process regression ensemble approach (GPRn), which also provides uncertainty quantification. Due to a rather cell invariant behaviour, the mapping of ICA features to SoH estimation is highly precise and points out a normalized mean absolute error (NMAE) of 1.3%. The more cell variant mapping to RUL estimation is challenging, reflecting in a NMAE of 5.3%. Using the estimation results, a RUL monitoring strategy is derived. The objective is to safely operate a battery cell from BOL to EOL by only taking sparse diagnostic measurements. On average, only four diagnostic measurements are required during a cell's lifetime of 3300 to 5000 cycles.
### Title:
          ClinicalAgents: Multi-Agent Orchestration for Clinical Decision Making with Dual-Memory
 - **Authors:** Zhuohan Ge, Haoyang Li, Yubo Wang, Nicole Hu, Chen Jason Zhang, Qing Li
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Large Language Models (LLMs) have demonstrated potential in healthcare, they often struggle with the complex, non-linear reasoning required for accurate clinical diagnosis. Existing methods typically rely on static, linear mappings from symptoms to diagnoses, failing to capture the iterative, hypothesis-driven reasoning inherent to human clinicians. To bridge this gap, we introduce ClinicalAgents, a novel multi-agent framework designed to simulate the cognitive workflow of expert clinicians. Unlike rigid sequential chains, ClinicalAgents employs a dynamic orchestration mechanism modeled as a Monte Carlo Tree Search (MCTS) process. This allows an Orchestrator to iteratively generate hypotheses, actively verify evidence, and trigger backtracking when critical information is missing. Central to this framework is a Dual-Memory architecture: a mutable Working Memory that maintains the evolving patient state for context-aware reasoning, and a static Experience Memory that retrieves clinical guidelines and historical cases via an active feedback loop. Extensive experiments demonstrate that ClinicalAgents achieves state-of-the-art performance, significantly enhancing both diagnostic accuracy and explainability compared to strong single-agent and multi-agent baselines.
### Title:
          DUGAE: Unified Geometry and Attribute Enhancement via Spatiotemporal Correlations for G-PCC Compressed Dynamic Point Clouds
 - **Authors:** Pan Zhao, Hui Yuan, Chang Sun, Chongzhen Tian, Raouf Hamzaoui, Sam Kwong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing post-decoding quality enhancement methods for point clouds are designed for static data and typically process each frame independently. As a result, they cannot effectively exploit the spatiotemporal correlations present in point cloud this http URL propose a unified geometry and attribute enhancement framework (DUGAE) for G-PCC compressed dynamic point clouds that explicitly exploits inter-frame spatiotemporal correlations in both geometry and attributes. First, a dynamic geometry enhancement network (DGE-Net) based on sparse convolution (SPConv) and feature-domain geometry motion compensation (GMC) aligns and aggregates spatiotemporal information. Then, a detail-aware k-nearest neighbors (DA-KNN) recoloring module maps the original attributes onto the enhanced geometry at the encoder side, improving mapping completeness and preserving attribute details. Finally, a dynamic attribute enhancement network (DAE-Net) with dedicated temporal feature extraction and feature-domain attribute motion compensation (AMC) refines attributes by modeling complex spatiotemporal correlations. On seven dynamic point clouds from the 8iVFB v2, Owlii, and MVUB datasets, DUGAE significantly enhanced the performance of the latest G-PCC geometry-based solid content test model (GeS-TM v10). For geometry (D1), it achieved an average BD-PSNR gain of 11.03 dB and a 93.95% BD-bitrate reduction. For the luma component, it achieved a 4.23 dB BD-PSNR gain with a 66.61% BD-bitrate reduction. DUGAE also improved perceptual quality (as measured by PCQM) and outperformed V-PCC. Our source code will be released on GitHub at: this https URL
### Title:
          Automating Domain-Driven Design: Experience with a Prompting Framework
 - **Authors:** Tobias Eisenreich, Husein Jusic, Stefan Wagner
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Domain-driven design (DDD) is a powerful design technique for architecting complex software systems. This paper introduces a prompting framework that automates core DDD activities through structured large language model (LLM) interactions. We decompose DDD into five sequential steps: (1) establishing an ubiquitous language, (2) simulating event storming, (3) identifying bounded contexts, (4) designing aggregates, and (5) mapping to technical architecture. In a case study, we validated the prompting framework against real-world requirements from FTAPI's enterprise platform. While the first steps consistently generate valuable and usable artifacts, later steps show how minor errors or inaccuracies can propagate and accumulate. Overall, the framework excels as a collaborative sparring partner for building actionable documentation, such as glossaries and context maps, but not for full automation. This allows the experts to concentrate their discussion on the critical trade-offs. In our evaluation, Steps 1 to 3 worked well, but the accumulated errors rendered the artifacts generated from Steps 4 and 5 impractical. Our findings show that LLMs can enhance, but not replace, architectural expertise, offering a practical tool to reduce the effort and overhead of DDD while preserving human-centric decision-making.
### Title:
          Query-Specific Pruning of RML Mappings (Extended Version)
 - **Authors:** Sitt Min Oo, Olaf Hartig
 - **Subjects:** Subjects:
Databases (cs.DB)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current approaches for knowledge graph construction with RML focus on full RDF graph materialization without considering user queries. As a result, mapping engines are inefficient in dynamic query environments, materializing large graphs even when only a small subset is needed to answer user queries. In this paper, we formally define satisfiability for SPARQL queries with respect to RDF data obtained via RML mappings and use this property to prune RML mappings for partial RDF graph materialization. Evaluation on the GTFS-Madrid benchmark shows that pruning significantly reduces materialization time, and RDF graph size while also noticeably improving querying time. Thus, enabling existing materialization engines to efficiently support generating RDF graphs in dynamic federated querying environment where user queries change frequently.
### Title:
          Word Alignment-Based Evaluation of Uniform Meaning Representations
 - **Authors:** Daniel Zeman, Federica Gamba
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Comparison and evaluation of graph-based representations of sentence meaning is a challenge because competing representations of the same sentence may have different number of nodes, and it is not obvious which nodes should be compared to each other. Existing approaches favor node mapping that maximizes $F_1$ score over node relations and attributes, regardless whether the similarity is intentional or accidental; consequently, the identified mismatches in values of node attributes are not useful for any detailed error analysis. We propose a node-matching algorithm that allows comparison of multiple Uniform Meaning Representations (UMR) of one sentence and that takes advantage of node-word alignments, inherently available in UMR. We compare it with previously used approaches, in particular smatch (the de-facto standard in AMR evaluation), and argue that sensitivity to word alignment makes the comparison of meaning representations more intuitive and interpretable, while avoiding the NP-hard search problem inherent in smatch. A script implementing the method is freely available.
### Title:
          OVI-MAP:Open-Vocabulary Instance-Semantic Mapping
 - **Authors:** Zilong Deng, Federico Tombari, Marc Pollefeys, Johanna Wald, Daniel Barath
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Incremental open-vocabulary 3D instance-semantic mapping is essential for autonomous agents operating in complex everyday environments. However, it remains challenging due to the need for robust instance segmentation, real-time processing, and flexible open-set reasoning. Existing methods often rely on the closed-set assumption or dense per-pixel language fusion, which limits scalability and temporal consistency. We introduce OVI-MAP that decouples instance reconstruction from semantic inference. We propose to build a class-agnostic 3D instance map that is incrementally constructed from RGB-D input, while semantic features are extracted only from a small set of automatically selected views using vision-language models. This design enables stable instance tracking and zero-shot semantic labeling throughout online exploration. Our system operates in real time and outperforms state-of-the-art open-vocabulary mapping baselines on standard benchmarks.
## Keyword: localization
### Title:
          Geo$^\textbf{2}$: Geometry-Guided Cross-view Geo-Localization and Image Synthesis
 - **Authors:** Yancheng Zhang, Xiaohan Zhang, Guangyu Sun, Zonglin Lyu, Safwan Wshah, Chen Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-view geo-spatial learning consists of two important tasks: Cross-View Geo-Localization (CVGL) and Cross-View Image Synthesis (CVIS), both of which rely on establishing geometric correspondences between ground and aerial views. Recent Geometric Foundation Models (GFMs) have demonstrated strong capabilities in extracting generalizable 3D geometric features from images, but their potential in cross-view geo-spatial tasks remains underexplored. In this work, we present Geo^2, a unified framework that leverages Geometric priors from GFMs (e.g., VGGT) to jointly perform geo-spatial tasks, CVGL and bidirectional CVIS. Despite the 3D reconstruction ability of GFMs, directly applying them to CVGL and CVIS remains challenging due to the large viewpoint gap between ground and aerial imagery. We propose GeoMap, which embeds ground and aerial features into a shared 3D-aware latent space, effectively reducing cross-view discrepancies for localization. This shared latent space naturally bridges cross-view image synthesis in both directions. To exploit this, we propose GeoFlow, a flow-matching model conditioned on geometry-aware latent embeddings. We further introduce a consistency loss to enforce latent alignment between the two synthesis directions, ensuring bidirectional coherence. Extensive experiments on standard benchmarks, including CVUSA, CVACT, and VIGOR, demonstrate that Geo^2 achieves state-of-the-art performance in both localization and synthesis, highlighting the effectiveness of 3D geometric priors for cross-view geo-spatial learning.
### Title:
          Massive Parallel Deep Reinforcement Learning for Active SLAM
 - **Authors:** Martín Arce Llobera, Julio A. Placed, Mariano De Paula, Pablo De Cristóforis
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in parallel computing and GPU acceleration have created new opportunities for computation-intensive learning problems such as Active SLAM -- where actions are selected to reduce uncertainty and improve joint mapping and localization. However, existing DRL-based approaches remain constrained by the lack of scalable parallel training. In this work, we address this challenge by proposing a scalable end-to-end DRL framework for Active SLAM that enables massively parallel training. Compared with the state of the art, our method significantly reduces training time, supports continuous action spaces and facilitates the exploration of more realistic scenarios. It is released as an open-source framework to promote reproducibility and community adoption.
### Title:
          BEVMAPMATCH: Multimodal BEV Neural Map Matching for Robust Re-Localization of Autonomous Vehicles
 - **Authors:** Shounak Sural, Ragunathan Rajkumar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Localization in GNSS-denied and GNSS-degraded environments is a challenge for the safe widespread deployment of autonomous vehicles. Such GNSS-challenged environments require alternative methods for robust localization. In this work, we propose BEVMapMatch, a framework for robust vehicle re-localization on a known map without the need for GNSS priors. BEVMapMatch uses a context-aware lidar+camera fusion method to generate multimodal Bird's Eye View (BEV) segmentations around the ego vehicle in both good and adverse weather conditions. Leveraging a search mechanism based on cross-attention, the generated BEV segmentation maps are then used for the retrieval of candidate map patches for map-matching purposes. Finally, BEVMapMatch uses the top retrieved candidate for finer alignment against the generated BEV segmentation, achieving accurate global localization without the need for GNSS. Multiple frames of generated BEV segmentation further improve localization accuracy. Extensive evaluations show that BEVMapMatch outperforms existing methods for re-localization in GNSS-denied and adverse environments, with a Recall@1m of 39.8%, being nearly twice as much as the best performing re-localization baseline. Our code and data will be made available at this https URL.
### Title:
          Finding Distributed Object-Centric Properties in Self-Supervised Transformers
 - **Authors:** Samyak Rawlekar, Amitabh Swain, Yujun Cai, Yiwei Wang, Ming-Hsuan Yang, Narendra Ahuja
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Machine Learning (cs.LG); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-supervised Vision Transformers (ViTs) like DINO show an emergent ability to discover objects, typically observed in [CLS] token attention maps of the final layer. However, these maps often contain spurious activations resulting in poor localization of objects. This is because the [CLS] token, trained on an image-level objective, summarizes the entire image instead of focusing on objects. This aggregation dilutes the object-centric information existing in the local, patch-level interactions. We analyze this by computing inter-patch similarity using patch-level attention components (query, key, and value) across all layers. We find that: (1) Object-centric properties are encoded in the similarity maps derived from all three components ($q, k, v$), unlike prior work that uses only key features or the [CLS] token. (2) This object-centric information is distributed across the network, not just confined to the final layer. Based on these insights, we introduce Object-DINO, a training-free method that extracts this distributed object-centric information. Object-DINO clusters attention heads across all layers based on the similarities of their patches and automatically identifies the object-centric cluster corresponding to all objects. We demonstrate Object-DINO's effectiveness on two applications: enhancing unsupervised object discovery (+3.6 to +12.4 CorLoc gains) and mitigating object hallucination in Multimodal Large Language Models by providing visual grounding. Our results demonstrate that using this distributed object-centric information improves downstream tasks without additional training.
### Title:
          GLINT: Modeling Scene-Scale Transparency via Gaussian Radiance Transport
 - **Authors:** Youngju Na, Jaeseong Yun, Soohyun Ryu, Hyunsu Kim, Sung-Eui Yoon, Suyong Yeon
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While 3D Gaussian splatting has emerged as a powerful paradigm, it fundamentally fails to model transparency such as glass panels. The core challenge lies in decoupling the intertwined radiance contributions from transparent interfaces and the transmitted geometry observed through the glass. We present GLINT, a framework that models scene-scale transparency through explicit decomposed Gaussian representation. GLINT reconstructs the primary interface and models reflected and transmitted radiance separately, enabling consistent radiance transport. During optimization, GLINT bootstraps transparency localization from geometry-separation cues induced by the decomposition, together with geometry and material priors from a pre-trained video relighting model. Extensive experiments demonstrate consistent improvements over prior methods for reconstructing complex transparent scenes.
### Title:
          4DRaL: Bridging 4D Radar with LiDAR for Place Recognition using Knowledge Distillation
 - **Authors:** Ningyuan Huang, Zhiheng Li, Zheng Fang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Place recognition is crucial for loop closure detection and global localization in robotics. Although mainstream algorithms typically rely on cameras and LiDAR, these sensors are susceptible to adverse weather conditions. Fortunately, the recently developed 4D millimeter-wave radar (4D radar) offers a promising solution for all-weather place recognition. However, the inherent noise and sparsity in 4D radar data significantly limit its performance. Thus, in this paper, we propose a novel framework called 4DRaL that leverages knowledge distillation (KD) to enhance the place recognition performance of 4D radar. Its core is to adopt a high-performance LiDAR-to-LiDAR (L2L) place recognition model as a teacher to guide the training of a 4D radar-to-4D radar (R2R) place recognition model. 4DRaL comprises three key KD modules: a local image enhancement module to handle the sparsity of raw 4D radar points, a feature distribution distillation module that ensures the student model generates more discriminative features, and a response distillation module to maintain consistency in feature space between the teacher and student models. More importantly, 4DRaL can also be trained for 4D radar-to-LiDAR (R2L) place recognition through different module configurations. Experimental results prove that 4DRaL achieves state-of-the-art performance in both R2R and R2L tasks regardless of normal or adverse weather.
### Title:
          A Benchmark for Evaluating Repository-Level Code Agents with Intermediate Reasoning on Feature Addition Task
 - **Authors:** Shuhan Liu, Zhiyi Zhao, Xing Hu, Kui Liu, Xiaohu Yang, Xin Xia
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Repository-level code agents have shown strong promise in real-world feature addition tasks, making reliable evaluation of their capabilities increasingly important. However, existing benchmarks primarily evaluate these agents as black boxes based on final test correctness, providing limited insight into how they reason and where failures arise. To address this limitation, we introduce RACE-bench, a reasoning-augmented benchmark for evaluating code agents on repository-level feature addition tasks. RACE-bench contains 528 real-world feature addition instances from 12 open-source repositories. Each instance is paired with executable patch verification and structured intermediate reasoning ground truth covering issue understanding, file localization, implementation tasks, and step decomposition. Based on this design, we introduce a dual-track evaluation framework that jointly measures patch correctness and intermediate reasoning quality. We evaluate three representative repository-level code agents on RACE-bench. On the full benchmark, Resolved Rates range from 29% to 70% across different agents. Our reasoning-level analysis further shows that while current agents perform well at understanding high-level intent, their performance degrades substantially when translating intent into concrete implementation steps. We also find that apply-success but test-fail cases exhibit lower reasoning recall (35.7% decrease) and higher over-prediction (94.1% increase) compared to successful cases. These findings highlight the importance of evaluating repository-level code agents beyond final patch correctness by examining the quality of their reasoning processes.
## Keyword: transformer
### Title:
          Relational graph-driven differential denoising and diffusion attention fusion for multimodal conversation emotion recognition
 - **Authors:** Ying Liu, Yuntao Shou, Wei Ai, Tao Meng, Keqin Li
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Sound (cs.SD); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In real-world scenarios, audio and video signals are often subject to environmental noise and limited acquisition conditions, resulting in extracted features containing excessive noise. Furthermore, there is an imbalance in data quality and information carrying capacity between different modalities. These two issues together lead to information distortion and weight bias during the fusion phase, impairing overall recognition performance. Most existing methods neglect the impact of noisy modalities and rely on implicit weighting to model modality importance, thereby failing to explicitly account for the predominant contribution of the textual modality in emotion understanding. To address these issues, we propose a relation-aware denoising and diffusion attention fusion model for MCER. Specifically, we first design a differential Transformer that explicitly computes the differences between two attention maps, thereby enhancing temporally consistent information while suppressing time-irrelevant noise, which leads to effective denoising in both audio and video modalities. Second, we construct modality-specific and cross-modality relation subgraphs to capture speaker-dependent emotional dependencies, enabling fine-grained modeling of intra- and inter-modal relationships. Finally, we introduce a text-guided cross-modal diffusion mechanism that leverages self-attention to model intra-modal dependencies and adaptively diffuses audiovisual information into the textual stream, ensuring more robust and semantically aligned multimodal fusion.
### Title:
          A-SelecT: Automatic Timestep Selection for Diffusion Transformer Representation Learning
 - **Authors:** Changyu Liu, James Chenhao Liang, Wenhao Yang, Yiming Cui, Jinghao Yang, Tianyang Wang, Qifan Wang, Dongfang Liu, Cheng Han
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion models have significantly reshaped the field of generative artificial intelligence and are now increasingly explored for their capacity in discriminative representation learning. Diffusion Transformer (DiT) has recently gained attention as a promising alternative to conventional U-Net-based diffusion models, demonstrating a promising avenue for downstream discriminative tasks via generative pre-training. However, its current training efficiency and representational capacity remain largely constrained due to the inadequate timestep searching and insufficient exploitation of DiT-specific feature representations. In light of this view, we introduce Automatically Selected Timestep (A-SelecT) that dynamically pinpoints DiT's most information-rich timestep from the selected transformer feature in a single run, eliminating the need for both computationally intensive exhaustive timestep searching and suboptimal discriminative feature selection. Extensive experiments on classification and segmentation benchmarks demonstrate that DiT, empowered by A-SelecT, surpasses all prior diffusion-based attempts efficiently and effectively.
### Title:
          A Survey of OCR Evaluation Methods and Metrics and the Invisibility of Historical Documents
 - **Authors:** Fitsum Sileshi Beyene, Christopher L. Dancy
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Digital Libraries (cs.DL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Optical character recognition (OCR) and document understanding systems increasingly rely on large vision and vision-language models, yet evaluation remains centered on modern, Western, and institutional documents. This emphasis masks system behavior in historical and marginalized archives, where layout, typography, and material degradation shape interpretation. This study examines how OCR and document understanding systems are evaluated, with particular attention to Black historical newspapers. We review OCR and document understanding papers, as well as benchmark datasets, which are published between 2006 and 2025 using the PRISMA framework. We look into how the studies report training data, benchmark design, and evaluation metrics for vision transformer and multimodal OCR systems. During the review, we found that Black newspapers and other community-produced historical documents rarely appear in reported training data or evaluation benchmarks. Most evaluations emphasize character accuracy and task success on modern layouts. They rarely capture structural failures common in historical newspapers, including column collapse, typographic errors, and hallucinated text. To put these findings into perspective, we use previous empirical studies and archival statistics from significant Black press collections to show how evaluation gaps lead to structural invisibility and representational harm. We propose that these gaps occur due to organizational (meso) and institutional (macro) behaviors and structure, shaped by benchmark incentives and data governance decisions.
### Title:
          Do All Vision Transformers Need Registers? A Cross-Architectural Reassessment
 - **Authors:** Spiros Baxevanakis, Platon Karageorgis, Ioannis Dravilas, Konrad Szewczyk
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Training Vision Transformers (ViTs) presents significant challenges, one of which is the emergence of artifacts in attention maps, hindering their interpretability. Darcet et al. (2024) investigated this phenomenon and attributed it to the need of ViTs to store global information beyond the [CLS] token. They proposed a novel solution involving the addition of empty input tokens, named registers, which successfully eliminate artifacts and improve the clarity of attention maps. In this work, we reproduce the findings of Darcet et al. (2024) and evaluate the generalizability of their claims across multiple models, including DINO, DINOv2, OpenCLIP, and DeiT3. While we confirm the validity of several of their key claims, our results reveal that some claims do not extend universally to other models. Additionally, we explore the impact of model size, extending their findings to smaller models. Finally, we untie terminology inconsistencies found in the original paper and explain their impact when generalizing to a wider range of models.
### Title:
          Fus3D: Decoding Consolidated 3D Geometry from Feed-forward Geometry Transformer Latents
 - **Authors:** Laura Fink, Linus Franke, George Kopanas, Marc Stamminger, Peter Hedman
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose a feed-forward method for dense Signed Distance Field (SDF) regression from unstructured image collections in less than three seconds, without camera calibration or post-hoc fusion. Our key insight is that the intermediate feature space of pretrained multi-view feed-forward geometry transformers already encodes a powerful joint world representation; yet, existing pipelines discard it, routing features through per-view prediction heads before assembling 3D geometry post-hoc, which discards valuable completeness information and accumulates inaccuracies. We instead perform 3D extraction directly from geometry transformer features via learned volumetric extraction: voxelized canonical embeddings that progressively absorb multi-view geometry information through interleaved cross- and self-attention into a structured volumetric latent grid. A simple convolutional decoder then maps this grid to a dense SDF. We additionally propose a scalable, validity-aware supervision scheme directly using SDFs derived from depth maps or 3D assets, tackling practical issues like non-watertight meshes. Our approach yields complete and well-defined distance values across sparse- and dense-view settings and demonstrates geometrically plausible completions. Code and further material can be found at this https URL.
### Title:
          Seeing Through Smoke: Surgical Desmoking for Improved Visual Perception
 - **Authors:** Jingpei Lu, Fengyi Jiang, Xiaorui Zhang, Lingbo Jin, Omid Mohareri
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Minimally invasive and robot-assisted surgery relies heavily on endoscopic imaging, yet surgical smoke produced by electrocautery and vessel-sealing instruments can severely degrade visual perception and hinder vision-based functionalities. We present a transformer-based surgical desmoking model with a physics-inspired desmoking head that jointly predicts smoke-free image and corresponding smoke map. To address the scarcity of paired smoky-to-smoke-free training data, we develop a synthetic data generation pipeline that blends artificial smoke patterns with real endoscopic images, yielding over 80,000 paired samples for supervised training. We further curate, to our knowledge, the largest paired surgical smoke dataset to date, comprising 5,817 image pairs captured with the da Vinci robotic surgical system, enabling benchmarking on high-resolution endoscopic images. Extensive experiments on both a public benchmark and our dataset demonstrate state-of-the-art performance in image reconstruction compared to existing dehazing and desmoking approaches. We also assess the impact of desmoking on downstream stereo depth estimation and instrument segmentation, highlighting both the potential benefits and current limitations of digital smoke removal methods.
### Title:
          Decoding Defensive Coverage Responsibilities in American Football Using Factorized Attention Based Transformer Models
 - **Authors:** Kevin Song, Evan Diewald, Ornob Siddiquee, Chris Boomhower, Keegan Abdoo, Mike Band, Amy Lee
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Defensive coverage schemes in the National Football League (NFL) represent complex tactical patterns requiring coordinated assignments among defenders who must react dynamically to the offense's passing concept. This paper presents a factorized attention-based transformer model applied to NFL multi-agent play tracking data to predict individual coverage assignments, receiver-defender matchups, and the targeted defender on every pass play. Unlike previous approaches that focus on post-hoc coverage classification at the team level, our model enables predictive modeling of individual player assignments and matchup dynamics throughout the play. The factorized attention mechanism separates temporal and agent dimensions, allowing independent modeling of player movement patterns and inter-player relationships. Trained on randomly truncated trajectories, the model generates frame-by-frame predictions that capture how defensive responsibilities evolve from pre-snap through pass arrival. Our models achieve approximately 89\%+ accuracy for all tasks, with true accuracy potentially higher given annotation ambiguity in the ground truth labels. These outputs also enable novel derivative metrics, including disguise rate and double coverage rate, which enable enhanced storytelling in TV broadcasts as well as provide actionable insights for team strategy development and player evaluation.
### Title:
          Shared Representation for 3D Pose Estimation, Action Classification, and Progress Prediction from Tactile Signals
 - **Authors:** Isaac Han, Seoyoung Lee, Sangyeon Park, Ecehan Akan, Yiyue Luo, Joseph DelPreto, Kyung-Joong Kim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Estimating human pose, classifying actions, and predicting movement progress are essential for human-robot interaction. While vision-based methods suffer from occlusion and privacy concerns in realistic environments, tactile sensing avoids these issues. However, prior tactile-based approaches handle each task separately, leading to suboptimal performance. In this study, we propose a Shared COnvolutional Transformer for Tactile Inference (SCOTTI) that learns a shared representation to simultaneously address three separate prediction tasks: 3D human pose estimation, action class categorization, and action completion progress estimation. To the best of our knowledge, this is the first work to explore action progress prediction using foot tactile signals from custom wireless insole sensors. This unified approach leverages the mutual benefits of multi-task learning, enabling the model to achieve improved performance across all three tasks compared to learning them independently. Experimental results demonstrate that SCOTTI outperforms existing approaches across all three tasks. Additionally, we introduce a novel dataset collected from 15 participants performing various activities and exercises, with 7 hours of total duration, across eight different activities.
### Title:
          Preventing Data Leakage in EEG-Based Survival Prediction: A Two-Stage Embedding and Transformer Framework
 - **Authors:** Yixin Zhou, Zhixiang Liu, Vladimir I. Zadorozhny, Jonathan Elmer
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning models have shown promise in EEG-based outcome prediction for comatose patients after cardiac arrest, but their reliability is often compromised by subtle forms of data leakage. In particular, when long EEG recordings are segmented into short windows and reused across multiple training stages, models may implicitly encode and propagate label information, leading to overly optimistic validation performance and poor generalization. In this study, we identify a previously overlooked form of data leakage in multi-stage EEG modeling pipelines. We demonstrate that violating strict patient-level separation can significantly inflate validation metrics while causing substantial degradation on independent test data. To address this issue, we propose a leakage-aware two-stage framework. In the first stage, short EEG segments are transformed into embedding representations using a convolutional neural network with an ArcFace objective. In the second stage, a Transformer-based model aggregates these embeddings to produce patient-level predictions, with strict isolation between training cohorts to eliminate leakage pathways. Experiments on a large-scale EEG dataset of post-cardiac-arrest patients show that the proposed framework achieves stable and generalizable performance under clinically relevant constraints, particularly in maintaining high sensitivity at stringent specificity thresholds. These results highlight the importance of rigorous data partitioning and provide a practical solution for reliable EEG-based outcome prediction.
### Title:
          DenseSwinV2: Channel Attentive Dual Branch CNN Transformer Learning for Cassava Leaf Disease Classification
 - **Authors:** Shah Saood (1), Saddam Hussain Khan (2) ((1) Artificial Intelligence Lab, Department of Computer Systems Engineering, University of Engineering and Applied Sciences (UEAS), Swat 19060, Pakistan (2) Interdisciplinary Research Center for Smart Mobility and Logistics (IRC-SML), King Fahd University of Petroleum and Minerals (KFUPM), Dhahran 31261, Saudi Arabia)
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work presents a new Hybrid Dense SwinV2, a two-branch framework that jointly leverages densely connected convolutional features and hierarchical customized Swin Transformer V2 (SwinV2) representations for cassava disease classification. The proposed framework captures high resolution local features through its DenseNet branch, preserving the fine structural cues and also allowing for effective gradient flow. Concurrently, the customized SwinV2 models global contextual dependencies through the idea of shifted-window self attention, which enables the capture of long range interactions critical in distinguishing between visually similar lesions. Moreover, an attention channel-squeeze module is employed for each CNN Transformer stream independently to emphasize discriminative disease related responses and suppress redundant or background driven activations. Finally, these discriminative channels are fused to achieve refined representations from the dense local and SwinV2 global correlated strengthened feature maps, respectively. The proposed Dense SwinV2 utilized a public cassava leaf disease dataset of 31000 images, comprised of five diseases, including brown streak, mosaic, green mottle, bacterial blight, and normal leaf conditions. The proposed Dense SwinV2 demonstrates a significant classification accuracy of 98.02 percent with an F1 score of 97.81 percent, outperforming well-established convolutional and transformer models. These results underline the fact that Hybrid Dense SwinV2 offers robustness and practicality in the field level diagnosis of cassava disease and real world challenges related to occlusion, noise, and complex backgrounds.
### Title:
          Can Vision Foundation Models Navigate? Zero-Shot Real-World Evaluation and Lessons Learned
 - **Authors:** Maeva Guerrier, Karthik Soma, Jana Pavlasek, Giovanni Beltrame
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual Navigation Models (VNMs) promise generalizable, robot navigation by learning from large-scale visual demonstrations. Despite growing real-world deployment, existing evaluations rely almost exclusively on success rate, whether the robot reaches its goal, which conceals trajectory quality, collision behavior, and robustness to environmental change. We present a real-world evaluation of five state-of-the-art VNMs (GNM, ViNT, NoMaD, NaviBridger, and CrossFormer) across two robot platforms and five environments spanning indoor and outdoor settings. Beyond success rate, we combine path-based metrics with vision-based goal-recognition scores and assess robustness through controlled image perturbations (motion blur, sunflare). Our analysis uncovers three systematic limitations: (a) even architecturally sophisticated diffusion and transformer-based models exhibit frequent collisions, indicating limited geometric understanding; (b) models fail to discriminate between different locations that are perceptually similar, however some semantics differences are present, causing goal prediction errors in repetitive environments; and (c) performance degrades under distribution shift. We will publicly release our evaluation codebase and dataset to facilitate reproducible benchmarking of VNMs.
### Title:
          Diffusion MRI Transformer with a Diffusion Space Rotary Positional Embedding (D-RoPE)
 - **Authors:** Gustavo Chau Loo Kung, Mohammad Abbasi, Camila Blank, Juze Zhang, Alan Q. Wang, Sophie Ostmeier, Akshay Chaudhari, Kilian Pohl, Ehsan Adeli
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Magnetic Resonance Imaging (dMRI) plays a critical role in studying microstructural changes in the brain. It is, therefore, widely used in clinical practice; yet progress in learning general-purpose representations from dMRI has been limited. A key challenge is that existing deep learning approaches are not well-suited to capture the unique properties of diffusion signals. Brain dMRI is normally composed of several brain volumes, each with different attenuation characteristics dependent on the direction and strength of the diffusion-sensitized gradients. Thus, there is a need to jointly model spatial, diffusion-weighting, and directional dependencies in dMRI. Furthermore, varying acquisition protocols (e.g., differing numbers of directions) further limit traditional models. To address these gaps, we introduce a diffusion space rotatory positional embedding (D-RoPE) plugged into our dMRI transformer to capture both the spatial structure and directional characteristics of diffusion data, enabling robust and transferable representations across diverse acquisition settings and an arbitrary number of diffusion directions. After self-supervised masked autoencoding pretraining, tests on several downstream tasks show that the learned representations and the pretrained model can provide competitive or superior performance compared to several baselines in these downstream tasks (even compared to a fully trained baseline); the finetuned features from our pretrained encoder resulted in a 6% higher accuracy in classifying mild cognitive impairment and a 0.05 increase in the correlation coefficient when predicting cognitive scores. Code is available at: this http URL.
### Title:
          FAST3DIS: Feed-forward Anchored Scene Transformer for 3D Instance Segmentation
 - **Authors:** Changyang Li, Xueqing Huang, Shin-Fang Chng, Huangying Zhan, Qingan Yan, Yi Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While recent feed-forward 3D reconstruction models provide a strong geometric foundation for scene understanding, extending them to 3D instance segmentation typically relies on a disjointed "lift-and-cluster" paradigm. Grouping dense pixel-wise embeddings via non-differentiable clustering scales poorly with the number of views and disconnects representation learning from the final segmentation objective. In this paper, we present a Feed-forward Anchored Scene Transformer for 3D Instance Segmentation (FAST3DIS), an end-to-end approach that effectively bypasses post-hoc clustering. We introduce a 3D-anchored, query-based Transformer architecture built upon a foundational depth backbone, adapted efficiently to learn instance-specific semantics while retaining its zero-shot geometric priors. We formulate a learned 3D anchor generator coupled with an anchor-sampling cross-attention mechanism for view-consistent 3D instance segmentation. By projecting 3D object queries directly into multi-view feature maps, our method samples context efficiently. Furthermore, we introduce a dual-level regularization strategy, that couples multi-view contrastive learning with a dynamically scheduled spatial overlap penalty to explicitly prevent query collisions and ensure precise instance boundaries. Experiments on complex indoor 3D datasets demonstrate that our approach achieves competitive segmentation accuracy with significantly improved memory scalability and inference speed over state-of-the-art clustering-based methods.
### Title:
          GeoReFormer: Geometry-Aware Refinement for Lane Segment Detection and Topology Reasoning
 - **Authors:** Danny Abraham, Nikhil Kamalkumar Advani, Arun Das, Nikil Dutt
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate 3D lane segment detection and topology reasoning are critical for structured online map construction in autonomous driving. Recent transformer-based approaches formulate this task as query-based set prediction, yet largely inherit decoder designs originally developed for compact object detection. However, lane segments are continuous polylines embedded in directed graphs, and generic query initialization and unconstrained refinement do not explicitly encode this geometric and relational structure. We propose GeoReFormer (Geometry-aware Refinement Transformer), a unified query-based architecture that embeds geometry- and topology-aware inductive biases directly within the transformer decoder. GeoReFormer introduces data-driven geometric priors for structured query initialization, bounded coordinate-space refinement for stable polyline deformation, and per-query gated topology propagation to selectively integrate relational context. On the OpenLane-V2 benchmark, GeoReFormer achieves state-of-the-art performance with 34.5% mAP while improving topology consistency over strong transformer baselines, demonstrating the utility of explicit geometric and relational structure encoding.
### Title:
          H-Node Attack and Defense in Large Language Models
 - **Authors:** Eric Yocam, Varghese Vaidyan, Yong Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present H-Node Adversarial Noise Cancellation (H-Node ANC), a mechanistic framework that identifies, exploits, and defends hallucination representations in transformer-based large language models (LLMs) at the level of individual hidden-state dimensions. A logistic regression probe trained on last-token hidden states localizes hallucination signal to a small set of high-variance dimensions -- termed Hallucination Nodes (H-Nodes) -- with probe AUC reaching 0.90 across four architectures. A white-box adversarial attack amplifies these dimensions at inference time via a real-time forward hook, achieving a selectivity of 3.02x with less than 10% visibility to the defender. Adaptive ANC defense suppresses H-Node excess in-pass using confidence-weighted cancellation, reducing grounded activation drift by 33-42% over static cancellation. A dynamic iterative extension that re-ranks cancellation targets across successive passes recovers up to 0.69 robustness from a single-pass baseline of 8%. All contributions are validated on OPT-125M, Phi-3-mini-4k-instruct, LLaMA-3-8B-Instruct, and Mistral-7B-Instruct-v0.3 (125M-8B parameters). Perplexity impact is surgical (<5%) and MMLU degradation is at most 3%, confirming that the defense does not impair general reasoning capability.
### Title:
          PAD-Hand: Physics-Aware Diffusion for Hand Motion Recovery
 - **Authors:** Elkhan Ismayilzada, Yufei Zhang, Zijun Cui
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Significant advancements made in reconstructing hands from images have delivered accurate single-frame estimates, yet they often lack physics consistency and provide no notion of how confidently the motion satisfies physics. In this paper, we propose a novel physics-aware conditional diffusion framework that refines noisy pose sequences into physically plausible hand motion while estimating the physics variance in motion estimates. Building on a MeshCNN-Transformer backbone, we formulate Euler-Lagrange dynamics for articulated hands. Unlike prior works that enforce zero residuals, we treat the resulting dynamic residuals as virtual observables to more effectively integrate physics. Through a last-layer Laplace approximation, our method produces per-joint, per-time variances that measure physics consistency and offers interpretable variance maps indicating where physical consistency weakens. Experiments on two well-known hand datasets show consistent gains over strong image-based initializations and competitive video-based methods. Qualitative results confirm that our variance estimations are aligned with the physical plausibility of the motion in image-based estimates.
### Title:
          MUST: Modality-Specific Representation-Aware Transformer for Diffusion-Enhanced Survival Prediction with Missing Modality
 - **Authors:** Kyungwon Kim, Dosik Hwang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate survival prediction from multimodal medical data is essential for precision oncology, yet clinical deployment faces a persistent challenge: modalities are frequently incomplete due to cost constraints, technical limitations, or retrospective data availability. While recent methods attempt to address missing modalities through feature alignment or joint distribution learning, they fundamentally lack explicit modeling of the unique contributions of each modality as opposed to the information derivable from other modalities. We propose MUST (Modality-Specific representation-aware Transformer), a novel framework that explicitly decomposes each modality's representation into modality-specific and cross-modal contextualized components through algebraic constraints in a learned low-rank shared subspace. This decomposition enables precise identification of what information is lost when a modality is absent. For the truly modality-specific information that cannot be inferred from available modalities, we employ conditional latent diffusion models to generate high-quality representations conditioned on recovered shared information and learned structural priors. Extensive experiments on five TCGA cancer datasets demonstrate that MUST achieves state-of-the-art performance with complete data while maintaining robust predictions in both missing pathology and missing genomics conditions, with clinically acceptable inference latency.
### Title:
          A Human-Inspired Decoupled Architecture for Efficient Audio Representation Learning
 - **Authors:** Harunori Kawano, Takeshi Sasaki
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While self-supervised learning (SSL) has revolutionized audio representation, the excessive parameterization and quadratic computational cost of standard Transformers limit their deployment on resource-constrained devices. To address this bottleneck, we propose HEAR (Human-inspired Efficient Audio Representation), a novel decoupled architecture. Inspired by the human cognitive ability to isolate local acoustic features from global context, HEAR splits the processing pipeline into two dedicated modules: an Acoustic Model for local feature extraction and a Task Model for global semantic integration. Coupled with an Acoustic Tokenizer trained via knowledge distillation, our approach enables robust Masked Audio Modeling (MAM). Extensive experiments demonstrate that HEAR requires only 15M parameters and 9.47 GFLOPs for inference, operating at a fraction of the computational cost of conventional foundation models (which typically require 85M-94M parameters). Despite this high efficiency, HEAR achieves highly competitive performance across diverse audio classification benchmarks. The code and pre-trained models are available at this https URL
### Title:
          DPD-Cancer: Explainable Graph-based Deep Learning for Small Molecule Anti-Cancer Activity Prediction
 - **Authors:** Magnus H. Strømme, Alex G. C. de Sá, David B. Ascher
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate drug response prediction is a critical bottleneck in computational biochemistry, limited by the challenge of modelling the interplay between molecular structure and cellular context. In cancer research, this is acute due to tumour heterogeneity and genomic variability, which hinder the identification of effective therapies. Conventional approaches often fail to capture non-linear relationships between chemical features and biological outcomes across diverse cell lines. To address this, we introduce DPD-Cancer, a deep learning method based on a Graph Attention Transformer (GAT) framework. It is designed for small molecule anti-cancer activity classification and the quantitative prediction of cell-line specific responses, specifically growth inhibition concentration (pGI50). Benchmarked against state-of-the-art methods (pdCSM-cancer, ACLPred, and MLASM), DPD-Cancer demonstrated superior performance, achieving an Area Under ROC Curve (AUC) of up to 0.87 on strictly partitioned NCI60 data and up to 0.98 on ACLPred/MLASM datasets. For pGI50 prediction across 10 cancer types and 73 cell lines, the model achieved Pearson's correlation coefficients of up to 0.72 on independent test sets. These findings confirm that attention-based mechanisms offer significant advantages in extracting meaningful molecular representations, establishing DPD-Cancer as a competitive tool for prioritising drug candidates. Furthermore, DPD-Cancer provides explainability by leveraging the attention mechanism to identify and visualise specific molecular substructures, offering actionable insights for lead optimisation. DPD-Cancer is freely available as a web server at: this https URL.
### Title:
          Finding Distributed Object-Centric Properties in Self-Supervised Transformers
 - **Authors:** Samyak Rawlekar, Amitabh Swain, Yujun Cai, Yiwei Wang, Ming-Hsuan Yang, Narendra Ahuja
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Machine Learning (cs.LG); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-supervised Vision Transformers (ViTs) like DINO show an emergent ability to discover objects, typically observed in [CLS] token attention maps of the final layer. However, these maps often contain spurious activations resulting in poor localization of objects. This is because the [CLS] token, trained on an image-level objective, summarizes the entire image instead of focusing on objects. This aggregation dilutes the object-centric information existing in the local, patch-level interactions. We analyze this by computing inter-patch similarity using patch-level attention components (query, key, and value) across all layers. We find that: (1) Object-centric properties are encoded in the similarity maps derived from all three components ($q, k, v$), unlike prior work that uses only key features or the [CLS] token. (2) This object-centric information is distributed across the network, not just confined to the final layer. Based on these insights, we introduce Object-DINO, a training-free method that extracts this distributed object-centric information. Object-DINO clusters attention heads across all layers based on the similarities of their patches and automatically identifies the object-centric cluster corresponding to all objects. We demonstrate Object-DINO's effectiveness on two applications: enhancing unsupervised object discovery (+3.6 to +12.4 CorLoc gains) and mitigating object hallucination in Multimodal Large Language Models by providing visual grounding. Our results demonstrate that using this distributed object-centric information improves downstream tasks without additional training.
### Title:
          Clash of the models: Comparing performance of BERT-based variants for generic news frame detection
 - **Authors:** Vihang Jumle
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Framing continues to remain one of the most extensively applied theories in political communication. Developments in computation, particularly with the introduction of transformer architecture and more so with large language models (LLMs), have naturally prompted scholars to explore various novel computational approaches, especially for deductive frame detection, in recent years. While many studies have shown that different transformer models outperform their preceding models that use bag-of-words features, the debate continues to evolve regarding how these models compare with each other on classification tasks. By placing itself at this juncture, this study makes three key contributions: First, it comparatively performs generic news frame detection and compares the performance of five BERT-based variants (BERT, RoBERTa, DeBERTa, DistilBERT and ALBERT) to add to the debate on best practices around employing computational text analysis for political communication studies. Second, it introduces various fine-tuned models capable of robustly performing generic news frame detection. Third, building upon numerous previous studies that work with US-centric data, this study provides the scholarly community with a labelled generic news frames dataset based on the Swiss electoral context that aids in testing the contextual robustness of these computational approaches to framing analysis.
### Title:
          Knowledge Distillation for Efficient Transformer-Based Reinforcement Learning in Hardware-Constrained Energy Management Systems
 - **Authors:** Pascal Henrich, Jonas Sievers, Maximilian Beichter, Thomas Blank, Ralf Mikut, Veit Hagenmeyer
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based reinforcement learning has emerged as a strong candidate for sequential control in residential energy management. In particular, the Decision Transformer can learn effective battery dispatch policies from historical data, thereby increasing photovoltaic self-consumption and reducing electricity costs. However, transformer models are typically too computationally demanding for deployment on resource-constrained residential controllers, where memory and latency constraints are critical. This paper investigates knowledge distillation to transfer the decision-making behaviour of high-capacity Decision Transformer policies to compact models that are more suitable for embedded deployment. Using the Ausgrid dataset, we train teacher models in an offline sequence-based Decision Transformer framework on heterogeneous multi-building data. We then distil smaller student models by matching the teachers' actions, thereby preserving control quality while reducing model size. Across a broad set of teacher-student configurations, distillation largely preserves control performance and even yields small improvements of up to 1%, while reducing the parameter count by up to 96%, the inference memory by up to 90%, and the inference time by up to 63%. Beyond these compression effects, comparable cost improvements are also observed when distilling into a student model of identical architectural capacity. Overall, our results show that knowledge distillation makes Decision Transformer control more applicable for residential energy management on resource-limited hardware.
### Title:
          ARTA: Adaptive Mixed-Resolution Token Allocation for Efficient Dense Feature Extraction
 - **Authors:** David Hagerman, Roman Naeem, Erik Brorsson, Fredrik Kahl, Lennart Svensson
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present ARTA, a mixed-resolution coarse-to-fine vision transformer for efficient dense feature extraction. Unlike models that begin with dense high-resolution (fine) tokens, ARTA starts with low-resolution (coarse) tokens and uses a lightweight allocator to predict which regions require more fine tokens. The allocator iteratively predicts a semantic (class) boundary score and allocates additional tokens to patches above a low threshold, concentrating token density near boundaries while maintaining high sensitivity to weak boundary evidence. This targeted allocation encourages tokens to represent a single semantic class rather than a mixture of classes. Mixed-resolution attention enables interaction between coarse and fine tokens, focusing computation on semantically complex areas while avoiding redundant processing in homogeneous regions. Experiments demonstrate that ARTA achieves state-of-the-art results on ADE20K and COCO-Stuff with substantially fewer FLOPs, and delivers competitive performance on Cityscapes at markedly lower compute. For example, ARTA-Base attains 54.6 mIoU on ADE20K in the ~100M-parameter class while using fewer FLOPs and less memory than comparable backbones.
### Title:
          Integration Adapter Architecture for Food Traceability Blockchain
 - **Authors:** André Romão, Francisco Faria, João R. Matos, Emanuel Nunes, Samih Eisa, Miguel L. Pardal
 - **Subjects:** Subjects:
Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Enterprise adoption of permissioned blockchains remains limited due to the complexity and cost of integrating legacy systems. We present a modular adapter architecture that bridges enterprise applications with blockchain networks, designed to support small and medium-sized enterprises with limited technical resources. The architecture provides five key modules: (1) configurable data extractors supporting diverse interfaces such as APIs and file uploads, (2) data transformers that can convert to standard formats, (3) messaging middleware to ensure operations can tolerate lack of connectivity and traffic spikes, (4) blockchain loader to commit transactions to the blockchain, and (5) status visibility to collect and expose runtime metrics that support operational transparency. We validated the adapters through a pilot deployment in a real-world fruit supply chain, involving three distinct enterprises. The pilot achieved blockchain integration with minimal workflow disruption, demonstrating the usefulness of these adapters for practical interoperability of existing systems with the blockchain.
### Title:
          From Pixels to Privacy: Temporally Consistent Video Anonymization via Token Pruning for Privacy Preserving Action Recognition
 - **Authors:** Nazia Aslam, Abhisek Ray, Joakim Bruslund Haurum, Lukas Esterle, Kamal Nasrollahi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in large-scale video models have significantly improved video understanding across domains such as surveillance, healthcare, and entertainment. However, these models also amplify privacy risks by encoding sensitive attributes, including facial identity, race, and gender. While image anonymization has been extensively studied, video anonymization remains relatively underexplored, even though modern video models can leverage spatiotemporal motion patterns as biometric identifiers. To address this challenge, we propose a novel attention-driven spatiotemporal video anonymization framework based on systematic disentanglement of utility and privacy features. Our key insight is that attention mechanisms in Vision Transformers (ViTs) can be explicitly structured to separate action-relevant information from privacy-sensitive content. Building on this insight, we introduce two task-specific classification tokens, an action CLS token and a privacy CLS token, that learn complementary representations within a shared Transformer backbone. We contrast their attention distributions to compute a utility-privacy score for each spatiotemporal tubelet, and keep the top-k tubelets with the highest scores. This selectively prunes tubelets dominated by privacy cues while preserving those most critical for action recognition. Extensive experiments demonstrate that our approach maintains action recognition performance comparable to models trained on raw videos, while substantially reducing privacy leakage. These results indicate that attention-driven spatiotemporal pruning offers an effective and principled solution for privacy-preserving video analytics.
### Title:
          MPDiT: Multi-Patch Global-to-Local Transformer Architecture For Efficient Flow Matching and Diffusion Model
 - **Authors:** Quan Dao, Dimitris Metaxas
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer architectures, particularly Diffusion Transformers (DiTs), have become widely used in diffusion and flow-matching models due to their strong performance compared to convolutional UNets. However, the isotropic design of DiTs processes the same number of patchified tokens in every block, leading to relatively heavy computation during training process. In this work, we introduce a multi-patch transformer design in which early blocks operate on larger patches to capture coarse global context, while later blocks use smaller patches to refine local details. This hierarchical design could reduces computational cost by up to 50\% in GFLOPs while achieving good generative performance. In addition, we also propose improved designs for time and class embeddings that accelerate training convergence. Extensive experiments on the ImageNet dataset demonstrate the effectiveness of our architectural choices. Code is released at \url{this https URL}
### Title:
          Switch Attention: Towards Dynamic and Fine-grained Hybrid Transformers
 - **Authors:** Yusheng Zhao, Hourun Li, Bohan Wu, Jingyang Yuan, Meng Zhang, Yichun Yin, Lifeng Shang, Ming Zhang
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The attention mechanism has been the core component in modern transformer architectures. However, the computation of standard full attention scales quadratically with the sequence length, serving as a major bottleneck in long-context language modeling. Sliding window attention restricts the context length for better efficiency at the cost of narrower receptive fields. While existing efforts attempt to take the benefits from both sides by building hybrid models, they often resort to static, heuristically designed alternating patterns that limit efficient allocation of computation in various scenarios. In this paper, we propose Switch Attention (SwiAttn), a novel hybrid transformer that enables dynamic and fine-grained routing between full attention and sliding window attention. For each token at each transformer layer, SwiAttn dynamically routes the computation to either a full-attention branch for global information aggregation or a sliding-window branch for efficient local pattern matching. An adaptive regularization objective is designed to encourage the model towards efficiency. Moreover, we adopt continual pretraining to optimize the model, transferring the full attention architecture to the hybrid one. Extensive experiments are conducted on twenty-three benchmark datasets across both regular (4K) and long (32K) context lengths, demonstrating the effectiveness of the proposed method.
### Title:
          A Boltzmann-machine-enhanced Transformer For DNA Sequence Classification
 - **Authors:** Zhixuan Cao, Yishu Xu, Xuang WU
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 DNA sequence classification requires not only high predictive accuracy but also the ability to uncover latent site interactions, combinatorial regulation, and epistasis-like higher-order dependencies. Although the standard Transformer provides strong global modeling capacity, its softmax attention is continuous, dense, and weakly constrained, making it better suited for information routing than explicit structure discovery. In this paper, we propose a Boltzmann-machine-enhanced Transformer for DNA sequence classification. Built on multi-head attention, the model introduces structured binary gating variables to represent latent query-key connections and constrains them with a Boltzmann-style energy function. Query-key similarity defines local bias terms, learnable pairwise interactions capture synergy and competition between edges, and latent hidden units model higher-order combinatorial dependencies. Since exact posterior inference over discrete gating graphs is intractable, we use mean-field variational inference to estimate edge activation probabilities and combine it with Gumbel-Softmax to progressively compress continuous probabilities into near-discrete gates while preserving end-to-end differentiability. During training, we jointly optimize classification and energy losses, encouraging the model to achieve accurate prediction while favoring low-energy, stable, and interpretable structures. We further derive the framework from the energy function and variational free energy to the mean-field fixed-point equations, Gumbel-Softmax relaxation, and the final joint objective. The proposed framework provides a unified view of integrating Boltzmann machines, differentiable discrete optimization, and Transformers for structured learning on biological sequences.
### Title:
          SPECTRA: An Efficient Spectral-Informed Neural Network for Sensor-Based Activity Recognition
 - **Authors:** Deepika Gurung, Lala Shakti Swarup Ray, Mengxi Liu, Bo Zhou, Paul Lukowicz
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real time sensor based applications in pervasive computing require edge deployable models to ensure low latency privacy and efficient interaction. A prime example is sensor based human activity recognition where models must balance accuracy with stringent resource constraints. Yet many deep learning approaches treat temporal sensor signals as black box sequences overlooking spectral temporal structure while demanding excessive computation. We present SPECTRA a deployment first co designed spectral temporal architecture that integrates short time Fourier transform STFT feature extraction depthwise separable convolutions and channel wise self attention to capture spectral temporal dependencies under real edge runtime and memory constraints. A compact bidirectional GRU with attention pooling summarizes within window dynamics at low cost reducing downstream model burden while preserving accuracy. Across five public HAR datasets SPECTRA matches or approaches larger CNN LSTM and Transformer baselines while substantially reducing parameters latency and energy. Deployments on a Google Pixel 9 smartphone and an STM32L4 microcontroller further demonstrate end to end deployable realtime private and efficient HAR.
### Title:
          Sharp Capacity Scaling of Spectral Optimizers in Learning Associative Memory
 - **Authors:** Juno Kim, Eshaan Nichani, Denny Wu, Alberto Bietti, Jason D. Lee
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spectral optimizers such as Muon have recently shown strong empirical performance in large-scale language model training, but the source and extent of their advantage remain poorly understood. We study this question through the linear associative memory problem, a tractable model for factual recall in transformer-based models. In particular, we go beyond orthogonal embeddings and consider Gaussian inputs and outputs, which allows the number of stored associations to greatly exceed the embedding dimension. Our main result sharply characterizes the recovery rates of one step of Muon and SGD on the logistic regression loss under a power law frequency distribution. We show that the storage capacity of Muon significantly exceeds that of SGD, and moreover Muon saturates at a larger critical batch size. We further analyze the multi-step dynamics under a thresholded gradient approximation and show that Muon achieves a substantially faster initial recovery rate than SGD, while both methods eventually converge to the information-theoretic limit at comparable speeds. Experiments on synthetic tasks validate the predicted scaling laws. Our analysis provides a quantitative understanding of the signal amplification of Muon and lays the groundwork for establishing scaling laws across more practical language modeling tasks and optimizers.
### Title:
          When Perplexity Lies: Generation-Focused Distillation of Hybrid Sequence Models
 - **Authors:** Juan Gabriel Kostelec, Xiang Wang, Axel Laborieux, Christos Sourmpis, Qinghai Guo
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Converting a pretrained Transformer into a more efficient hybrid model through distillation offers a promising approach to reducing inference costs. However, achieving high-quality generation in distilled models requires careful joint design of both the student architecture and the distillation process. Many prior distillation works evaluate downstream multiple-choice benchmarks by ranking candidate answers with log-likelihood rather than requiring autoregressive generation, which can obscure important differences in model quality. For example, we show that a 7B parameter distilled model that nearly matches its teacher to within 0.2\,pp under log-likelihood scoring actually falls behind by 20.8\,pp when the model must generate answers autoregressively. We propose a Hybrid Kimi Delta Attention (Hybrid-KDA) architecture paired with GenDistill, a multi-stage distillation pipeline, and use generation-based evaluation throughout to guide design decisions. Applying this approach to Qwen3-0.6B, we systematically ablate six design axes: training objective, loss masking, training duration, dataset selection, parameter freezing, and architecture choice. We find that log-likelihood-based evaluation consistently underestimates the gap between teacher and student, and can in some cases reverse the ranking of design choices, meaning that conclusions drawn from perplexity-only evaluation may be misleading. Among the factors we study, dataset selection, completion-only masking, and freezing attention layers during post-training have the largest impact on generation quality. Our best Hybrid-KDA model retains 86--90\% of teacher accuracy on knowledge benchmarks while reducing KV cache memory by up to 75\% and improving time-to-first-token by 2--4$\times$ at 128K-token contexts.
### Title:
          Meta-Adaptive Beam Search Planning for Transformer-Based Reinforcement Learning Control of UAVs with Overhead Manipulators under Flight Disturbances
 - **Authors:** Hazim Alzorgan, Sayed Pedram Haeri Boroujeni, Abolfazl Razi
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Drones equipped with overhead manipulators offer unique capabilities for inspection, maintenance, and contact-based interaction. However, the motion of the drone and its manipulator is tightly linked, and even small attitude changes caused by wind or control imperfections shift the end-effector away from its intended path. This coupling makes reliable tracking difficult and also limits the direct use of learning-based arm controllers that were originally designed for fixed-base robots. These effects appear consistently in our tests whenever the UAV body experiences drift or rapid attitude corrections. To address this behavior, we develop a reinforcement-learning (RL) framework with a transformer-based double deep Q learning (DDQN), with the core idea of using an adaptive beam-search planner that applies a short-horizon beam search over candidate control sequences using the learned critic as the forward estimator. This allows the controller to anticipate the end-effector's motion through simulated rollouts rather than executing those actions directly on the actual model, realizing a software-in-the-loop (SITL) approach. The lookahead relies on value estimates from a Transformer critic that processes short sequences of states, while a DDQN backbone provides the one-step targets needed to keep the learning process stable. Evaluated on a 3-DoF aerial manipulator under identical training conditions, the proposed meta-adaptive planner shows the strongest overall performance with a 10.2% reward increase, a substantial reduction in mean tracking error (from about 6% to 3%), and a 29.6% improvement in the combined reward-error metric relative to the DDQN baseline. Our method exhibits elevated stability in tracking target tip trajectory (by maintaining 5 cm tracking error) when the drone base exhibits drifts due to external disturbances, as opposed to the fixed-beam and Transformer-only variants.
### Title:
          Zero-Shot Depth from Defocus
 - **Authors:** Yiming Zuo, Hongyu Wen, Venkat Subramanian, Patrick Chen, Karhan Kayan, Mario Bijelic, Felix Heide, Jia Deng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Depth from Defocus (DfD) is the task of estimating a dense metric depth map from a focus stack. Unlike previous works overfitting to a certain dataset, this paper focuses on the challenging and practical setting of zero-shot generalization. We first propose a new real-world DfD benchmark ZEDD, which contains 8.3x more scenes and significantly higher quality images and ground-truth depth maps compared to previous benchmarks. We also design a novel network architecture named FOSSA. FOSSA is a Transformer-based architecture with novel designs tailored to the DfD task. The key contribution is a stack attention layer with a focus distance embedding, allowing efficient information exchange across the focus stack. Finally, we develop a new training data pipeline allowing us to utilize existing large-scale RGBD datasets to generate synthetic focus stacks. Experiment results on ZEDD and other benchmarks show a significant improvement over the baselines, reducing errors by up to 55.7%. The ZEDD benchmark is released at this https URL. The code and checkpoints are released at this https URL.
### Title:
          GaussianGPT: Towards Autoregressive 3D Gaussian Scene Generation
 - **Authors:** Nicolas von Lützow, Barbara Rössle, Katharina Schmid, Matthias Nießner
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Most recent advances in 3D generative modeling rely on diffusion or flow-matching formulations. We instead explore a fully autoregressive alternative and introduce GaussianGPT, a transformer-based model that directly generates 3D Gaussians via next-token prediction, thus facilitating full 3D scene generation. We first compress Gaussian primitives into a discrete latent grid using a sparse 3D convolutional autoencoder with vector quantization. The resulting tokens are serialized and modeled using a causal transformer with 3D rotary positional embedding, enabling sequential generation of spatial structure and appearance. Unlike diffusion-based methods that refine scenes holistically, our formulation constructs scenes step-by-step, naturally supporting completion, outpainting, controllable sampling via temperature, and flexible generation horizons. This formulation leverages the compositional inductive biases and scalability of autoregressive modeling while operating on explicit representations compatible with modern neural rendering pipelines, positioning autoregressive transformers as a complementary paradigm for controllable and context-aware 3D generation.
## Keyword: autonomous driving
### Title:
          ETA-VLA: Efficient Token Adaptation via Temporal Fusion and Intra-LLM Sparsification for Vision-Language-Action Models
 - **Authors:** Yiru Wang, Anqing Jiang, Shuo Wang, Yuwen Heng, Zichong Gu, Hao Sun
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The integration of Vision-Language-Action (VLA) models into autonomous driving systems offers a unified framework for interpreting complex scenes and executing control commands. However, the necessity to incorporate historical multi-view frames for accurate temporal reasoning imposes a severe computational burden, primarily driven by the quadratic complexity of self-attention mechanisms in Large Language Models (LLMs). To alleviate this bottleneck, we propose ETA-VLA, an Efficient Token Adaptation framework for VLA models. ETA-VLA processes the past $n$ frames of multi-view images and introduces a novel Intra-LLM Sparse Aggregator (ILSA). Drawing inspiration from human driver attention allocation, ILSA dynamically identifies and prunes redundant visual tokens guided by textual queries and temporal consistency. Specifically, we utilize a text-guided scoring mechanism alongside a diversity-preserving sparsification strategy to select a sparse subset of critical tokens, ensuring comprehensive awareness of the driving scene. Extensive experiments on the NAVSIM v2 demonstrate that ETA-VLA achieves driving performance comparable to state-of-the-art baselines while reducing computational FLOPs by approximately 32\%. Notably, our method prunes 85% of visual tokens and reduces inference FLOPs by 61\%, but still retaining 94% of the original accuracy on the NAVSIM v2 benchmark.
### Title:
          Collision-Aware Vision-Language Learning for End-to-End Driving with Multimodal Infraction Datasets
 - **Authors:** Alex Koran, Dimitrios Sinodinos, Hadi Hojjati, Takuya Nanri, Fangge Chen, Narges Armanfard
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High infraction rates remain the primary bottleneck for end-to-end (E2E) autonomous driving, as evidenced by the low driving scores on the CARLA Leaderboard. Despite collision-related infractions being the dominant failure mode in closed-loop evaluations, collision-aware representation learning has received limited attention. To address this gap, we first develop a Video-Language-Augmented Anomaly Detector (VLAAD), leveraging a Multiple Instance Learning (MIL) formulation to obtain stable, temporally localized collision signals for proactive prediction. To transition these capabilities into closed-loop simulations, we must overcome the limitations of existing simulator datasets, which lack multimodality and are frequently restricted to simple intersection scenarios. Therefore, we introduce CARLA-Collide, a large-scale multimodal dataset capturing realistic collision events across highly diverse road networks. Trained on this diverse simulator data, VLAAD serves as a collision-aware plug-in module that can be seamlessly integrated into existing E2E driving models. By integrating our module into a pretrained TransFuser++ agent, we demonstrate a 14.12% relative increase in driving score with minimal fine-tuning. Beyond closed-loop evaluation, we further assess the generalization capability of VLAAD in an open-loop setting using real-world driving data. To support this analysis, we introduce Real-Collide, a multimodal dataset of diverse dashcam videos paired with semantically rich annotations for collision detection and prediction. On this benchmark, despite containing only 0.6B parameters, VLAAD outperforms a multi-billion-parameter vision-language model, achieving a 23.3% improvement in AUC.
### Title:
          Neuro-Cognitive Reward Modeling for Human-Centered Autonomous Vehicle Control
 - **Authors:** Zhuoli Zhuang, Yu-Cheng Chang, Yu-Kai Wang, Thomas Do, Chin-Teng Lin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advancements in computer vision have accelerated the development of autonomous driving. Despite these advancements, training machines to drive in a way that aligns with human expectations remains a significant challenge. Human factors are still essential, as humans possess a sophisticated cognitive system capable of rapidly interpreting scene information and making accurate decisions. Aligning machine with human intent has been explored with Reinforcement Learning with Human Feedback (RLHF). Conventional RLHF methods rely on collecting human preference data by manually ranking generated outputs, which is time-consuming and indirect. In this work, we propose an electroencephalography (EEG)-guided decision-making framework to incorporate human cognitive insights without behaviour response interruption into reinforcement learning (RL) for autonomous driving. We collected EEG signals from 20 participants in a realistic driving simulator and analyzed event-related potentials (ERP) in response to sudden environmental changes. Our proposed framework employs a neural network to predict the strength of ERP based on the cognitive information from visual scene information. Moreover, we explore the integration of such cognitive information into the reward signal of the RL algorithm. Experimental results show that our framework can improve the collision avoidance ability of the RL algorithm, highlighting the potential of neuro-cognitive feedback in enhancing autonomous driving systems. Our project page is: this https URL.
### Title:
          GeoReFormer: Geometry-Aware Refinement for Lane Segment Detection and Topology Reasoning
 - **Authors:** Danny Abraham, Nikhil Kamalkumar Advani, Arun Das, Nikil Dutt
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate 3D lane segment detection and topology reasoning are critical for structured online map construction in autonomous driving. Recent transformer-based approaches formulate this task as query-based set prediction, yet largely inherit decoder designs originally developed for compact object detection. However, lane segments are continuous polylines embedded in directed graphs, and generic query initialization and unconstrained refinement do not explicitly encode this geometric and relational structure. We propose GeoReFormer (Geometry-aware Refinement Transformer), a unified query-based architecture that embeds geometry- and topology-aware inductive biases directly within the transformer decoder. GeoReFormer introduces data-driven geometric priors for structured query initialization, bounded coordinate-space refinement for stable polyline deformation, and per-query gated topology propagation to selectively integrate relational context. On the OpenLane-V2 benchmark, GeoReFormer achieves state-of-the-art performance with 34.5% mAP while improving topology consistency over strong transformer baselines, demonstrating the utility of explicit geometric and relational structure encoding.
### Title:
          R-PGA: Robust Physical Adversarial Camouflage Generation via Relightable 3D Gaussian Splatting
 - **Authors:** Tianrui Lou, Siyuan Liang, Jiawei Liang, Yuze Gao, Xiaochun Cao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Physical adversarial camouflage poses a severe security threat to autonomous driving systems by mapping adversarial textures onto 3D objects. Nevertheless, current methods remain brittle in complex dynamic scenarios, failing to generalize across diverse geometric (e.g., viewing configurations) and radiometric (e.g., dynamic illumination, atmospheric scattering) variations. We attribute this deficiency to two fundamental limitations in simulation and optimization. First, the reliance on coarse, oversimplified simulations (e.g., via CARLA) induces a significant domain gap, confining optimization to a biased feature space. Second, standard strategies targeting average performance result in a rugged loss landscape, leaving the camouflage vulnerable to configuration this http URL bridge these gaps, we propose the Relightable Physical 3D Gaussian Splatting (3DGS) based Attack framework (R-PGA). Technically, to address the simulation fidelity issue, we leverage 3DGS to ensure photo-realistic reconstruction and augment it with physically disentangled attributes to decouple intrinsic material from lighting. Furthermore, we design a hybrid rendering pipeline that leverages precise Relightable 3DGS for foreground rendering, while employing a pre-trained image translation model to synthesize plausible relighted backgrounds that align with the relighted this http URL address the optimization robustness issue, we propose the Hard Physical Configuration Mining (HPCM) module, designed to actively mine worst-case physical configurations and suppress their corresponding loss peaks. This strategy not only diminishes the overall loss magnitude but also effectively flattens the rugged loss landscape, ensuring consistent adversarial effectiveness and robustness across varying physical configurations.
### Title:
          DTP-Attack: A decision-based black-box adversarial attack on trajectory prediction
 - **Authors:** Jiaxiang Li, Jun Yan, Daniel Watzenig, Huilin Yin
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Trajectory prediction systems are critical for autonomous vehicle safety, yet remain vulnerable to adversarial attacks that can cause catastrophic traffic behavior misinterpretations. Existing attack methods require white-box access with gradient information and rely on rigid physical constraints, limiting real-world applicability. We propose DTP-Attack, a decision-based black-box adversarial attack framework tailored for trajectory prediction systems. Our method operates exclusively on binary decision outputs without requiring model internals or gradients, making it practical for real-world scenarios. DTP-Attack employs a novel boundary walking algorithm that navigates adversarial regions without fixed constraints, naturally maintaining trajectory realism through proximity preservation. Unlike existing approaches, our method supports both intention misclassification attacks and prediction accuracy degradation. Extensive evaluation on nuScenes and Apolloscape datasets across state-of-the-art models including Trajectron++ and Grip++ demonstrates superior performance. DTP-Attack achieves 41 - 81% attack success rates for intention misclassification attacks that manipulate perceived driving maneuvers with perturbations below 0.45 m, and increases prediction errors by 1.9 - 4.2 for accuracy degradation. Our method consistently outperforms existing black-box approaches while maintaining high controllability and reliability across diverse scenarios. These results reveal fundamental vulnerabilities in current trajectory prediction systems, highlighting urgent needs for robust defenses in safety-critical autonomous driving applications.
### Title:
          AutoWeather4D: Autonomous Driving Video Weather Conversion via G-Buffer Dual-Pass Editing
 - **Authors:** Tianyu Liu, Weitao Xiong, Kunming Luo, Manyuan Zhang, Peng Liu, Yuan Liu, Ping Tan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative video models have significantly advanced the photorealistic synthesis of adverse weather for autonomous driving; however, they consistently demand massive datasets to learn rare weather scenarios. While 3D-aware editing methods alleviate these data constraints by augmenting existing video footage, they are fundamentally bottlenecked by costly per-scene optimization and suffer from inherent geometric and illumination entanglement. In this work, we introduce AutoWeather4D, a feed-forward 3D-aware weather editing framework designed to explicitly decouple geometry and illumination. At the core of our approach is a G-buffer Dual-pass Editing mechanism. The Geometry Pass leverages explicit structural foundations to enable surface-anchored physical interactions, while the Light Pass analytically resolves light transport, accumulating the contributions of local illuminants into the global illumination to enable dynamic 3D local relighting. Extensive experiments demonstrate that AutoWeather4D achieves comparable photorealism and structural consistency to generative baselines while enabling fine-grained parametric physical control, serving as a practical data engine for autonomous driving.
