# Showing new listings for Friday, 1 May 2026
## Keyword: SLAM
### Title:
          Learning-Based Hierarchical Scene Graph Matching for Robot Localization Leveraging Prior Maps
 - **Authors:** Nimrod Millenium Ndulue, Jose Andres Millan-Romera, Matteo Giorgi, Holger Voos, Jose Luis Sanchez-Lopez
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate localization is a fundamental requirement for autonomous robots operating in indoor environments. Scene graphs encode the spatial structure of an environment as a hierarchy of semantic entities and their relationships, and can be constructed both online from robot sensor data and offline from architectural priors such as Building Information Models (BIM). Matching these two complementary representations enables drift correction in SLAM by grounding robot observations against a known structural prior. However, establishing reliable node-to-node correspondences between them remains an open challenge: existing combinatorial methods are prohibitively expensive at scale, and prior learned approaches address only flat graph matching, ignoring the multi-level semantic structure present in both representations. Here we present a learned, end-to-end differentiable pipeline that augments both graphs with semantically motivated edge types encoding intra- and inter- level relationships, explicitly exploiting this hierarchy to enable simultaneous matching from high-level room concepts down to low-level wall surfaces. Trained exclusively on floor plans, the proposed method outperforms the combinatorial baseline in F1 on real LiDAR environments while running an order of magnitude faster, demonstrating viable zero-shot generalization for BIM-assisted robot localization.
### Title:
          FreeOcc: Training-Free Embodied Open-Vocabulary Occupancy Prediction
 - **Authors:** Zeyu Jiang, Changqing Zhou, Xingxing Zuo, Changhao Chen
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing learning-based occupancy prediction methods rely on large-scale 3D annotations and generalize poorly across environments. We present FreeOcc, a training-free framework for open-vocabulary occupancy prediction from monocular or RGB-D sequences. Unlike prior approaches that require voxel-level supervision and ground-truth camera poses, FreeOcc operates without 3D annotations, pose ground truth, or any learning stage. FreeOcc incrementally builds a globally consistent occupancy map via a four-layer pipeline: a SLAM backbone estimates poses and sparse geometry; a geometrically consistent Gaussian update constructs dense 3D Gaussian maps; open-vocabulary semantics from off-the-shelf vision-language models are associated with Gaussian primitives; and a probabilistic Gaussian-to-occupancy projection produces dense voxel occupancy. Despite being entirely training-free and pose-agnostic, FreeOcc achieves over $2\times$ improvements in IoU and mIoU on EmbodiedOcc-ScanNet compared to prior self-supervised methods. We further introduce ReplicaOcc, a benchmark for indoor open-vocabulary occupancy prediction, and show that FreeOcc transfers zero-shot to novel environments, substantially outperforming both supervised and self-supervised baselines. Project page: this https URL.
## Keyword: odometry
There is no result 
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          RAY-TOLD: Ray-Based Latent Dynamics for Dense Dynamic Obstacle Avoidance with TDMPC
 - **Authors:** Seungho Han, Seokju Lee, Jeonguk Kang
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dense, dynamic crowds pose a persistent challenge for autonomous mobile robots. Purely reactive planning methods, such as Model Predictive Path Integral (MPPI) control, often fail to escape local minima in complex scenarios due to their limited prediction horizon. To bridge this gap, we propose Ray-based Task-Oriented Latent Dynamics (RAY-TOLD), a hybrid control architecture that integrates obstacle information into latent dynamics and utilizes the robustness of physics-based MPPI with the long-horizon foresight of reinforcement learning. RAY-TOLD leverages a LiDAR-centric latent dynamics model to encode high-dimensional sensor data into a compact state representation, enabling the learning of a terminal value function and a policy prior. We introduce a policy mixture sampling strategy that augments the MPPI candidate population with trajectories derived from the learned policy, effectively guiding the planner towards the goal while maintaining kinematic feasibility. Extensive tests in a stochastic environment with high-density dynamic obstacles demonstrate that our method outperforms the MPPI baseline, reducing the collision rate. The results confirm that blending short-horizon physics-based rollouts with learned long-horizon intent significantly enhances navigation reliability and safety.
### Title:
          Learning-Based Hierarchical Scene Graph Matching for Robot Localization Leveraging Prior Maps
 - **Authors:** Nimrod Millenium Ndulue, Jose Andres Millan-Romera, Matteo Giorgi, Holger Voos, Jose Luis Sanchez-Lopez
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate localization is a fundamental requirement for autonomous robots operating in indoor environments. Scene graphs encode the spatial structure of an environment as a hierarchy of semantic entities and their relationships, and can be constructed both online from robot sensor data and offline from architectural priors such as Building Information Models (BIM). Matching these two complementary representations enables drift correction in SLAM by grounding robot observations against a known structural prior. However, establishing reliable node-to-node correspondences between them remains an open challenge: existing combinatorial methods are prohibitively expensive at scale, and prior learned approaches address only flat graph matching, ignoring the multi-level semantic structure present in both representations. Here we present a learned, end-to-end differentiable pipeline that augments both graphs with semantically motivated edge types encoding intra- and inter- level relationships, explicitly exploiting this hierarchy to enable simultaneous matching from high-level room concepts down to low-level wall surfaces. Trained exclusively on floor plans, the proposed method outperforms the combinatorial baseline in F1 on real LiDAR environments while running an order of magnitude faster, demonstrating viable zero-shot generalization for BIM-assisted robot localization.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          RayFormer: Modeling Inter- and Intra-Ray Similarity for NeRF-Based Video Snapshot Compressive Imaging
 - **Authors:** Yubo Dong, Danhua Liu, Anqi Li, Zhenyuan Lin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video snapshot compressive imaging (SCI) enables the reconstruction of dynamic scenes from a single snapshot measurement. Recently, NeRF-based methods have shown promising reconstruction performance. However, such methods typically adopt random ray sampling strategies and fail to capture content structural similarities, resulting in limited reconstruction quality. To address these issues, we first propose a patch-level ray sampling strategy to enable the modeling of content structure. Then, we propose an Inter- and Intra-Ray Transformer (RayFormer) to capture the structural similarities, modeling both inter-ray similarities among spatially neighboring points at the same depth and intra-ray correlations between adjacent points along the viewing ray. Finally, benefiting from the patch-level sampling strategy, the total variation prior is incorporated into the objective function to enhance spatial smoothness and suppress artifacts. Experiments in both simulated and real-world scenes demonstrate that the proposed method achieves state-of-the-art (SOTA) reconstruction performance.
## Keyword: mapping
### Title:
          HQ-UNet: A Hybrid Quantum-Classical U-Net with a Quantum Bottleneck for Remote Sensing Image Segmentation
 - **Authors:** Md Aminur Hossain, Ayush V. Patel, Ikshwaku Vanani, Biplab Banerjee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic segmentation in remote sensing is commonly addressed using classical deep learning architectures such as U-Net, which require a large number of parameters to model complex spatial relationships. Quantum machine learning (QML) provides an alternative representation paradigm by mapping classical features into quantum states, but its direct application to high-dimensional images remains challenging under near-term quantum hardware constraints. In this work, we propose HQ-UNet, a hybrid quantum-classical U-Net architecture that integrates a compact parameterized quantum circuit at the bottleneck of a classical U-Net. The proposed design uses a non-pooling quantum convolutional module to enrich highly compressed encoder features before decoding, while keeping the quantum component shallow and parameter-efficient. Experiments on the this http URL dataset show that HQ-UNet achieves a mean IoU of 0.8050 and an overall accuracy of 94.76%, outperforming the classical U-Net baseline. These results suggest that compact quantum bottlenecks can enhance feature representation for remote sensing image segmentation under near-term quantum constraints. This highlights the potential of hybrid quantum-classical designs as a promising direction for parameter-efficient dense prediction in Earth observation.
### Title:
          Graphify: Automated Synthesis of Type-Safe Graph Backends via $O(S)$ GraphQL-to-Gremlin Transpilation
 - **Authors:** Johannes Graf
 - **Subjects:** Subjects:
Databases (cs.DB)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Graph databases offer unparalleled flexibility for managing interconnected data, yet the lack of strict schema enforcement often leads to runtime uncertainties and complex query development. This paper introduces Graphify, an end-to-end framework that enables developers to visually model graph data schemas and automatically synthesize a fully functional, type-safe backend. This paper proposes a formal mapping of GraphQL artifacts to the Gremlin traversal machine, supporting complete CRUD operations and arbitrarily nested queries. The system generates a transpiler capable of converting complex GraphQL requests into a single, optimized Gremlin query, including advanced features such as nested logical predicates, multi-key sorting, and pagination. At the core of the framework is a recursive state machine algorithm that processes GraphQL Abstract Syntax Trees (ASTs) with linear time complexity $O(S)$ relative to the number of selected fields. This paper demonstrates the practical efficiency and theoretical robustness of the approach through formal complexity analysis and empirical evaluation using the MovieLens 100k dataset. The result is a system that enables the generation of graph interfaces in minutes, bridging the gap between flexible graph storage and type-safe API consumption.
### Title:
          Towards Generalizable Mapping of Hedges and Linear Woody Features from Earth Observation Data: a national Product for Germany
 - **Authors:** Thorsten Hoeser, Verena Huber-Garcia, Sarah Asam, Ursula Gessner, Claudia Kuenzer
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hedges and other linear woody features provide valuable ecosystem services, particularly within intensively managed agricultural landscapes. They are key elements for climate adaptation and biodiversity amongst others not only due to a largely varying flora, but also as a feeding-, resting-, and nesting place for many animals and insects including valuable pollinators. Therefore, they require dedicated management, preservation, and attention. Thus, systematic and large-scale mapping of these features from Earth observation data is of high importance. However, transferable and reusable workflows for linear woody feature mapping remain a key methodological challenge, given the diversity of sensor types, spatial resolutions, data acquisition conditions, and complex landscape variability encountered across study areas. We introduce a modular workflow built around two independently optimizable components. Firstly, a flexible input data interface that consolidates heterogeneous Earth observation data into a binary woody vegetation mask, and secondly, a deep neural network trained to separate linear from non-linear shapes within these masks. We demonstrate the workflow by deriving three national-scale linear woody feature maps for all of Germany from three input sources by using a single trained model without retraining. Evaluation against refined reference data from four federal state biotope mapping campaigns and comparison with two existing linear woody feature maps demonstrate that the workflow produces competitive results across all evaluation sites on a national level. The modular design and its demonstrated applicability at national scale provide a foundation for scalable and generalizable linear woody feature mapping beyond Germany.
### Title:
          Investigating More Explainable and Partition-Free Compositionality Estimation for LLMs: A Rule-Generation Perspective
 - **Authors:** Ziyao Xu, Cong Wang, Houfeng Wang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Compositional generalization tests are often used to estimate the compositionality of LLMs. However, such tests have the following limitations: (1) they only focus on the output results without considering LLMs' understanding of sample compositionality, resulting in explainability defects; (2) they rely on dataset partition to form the test set with combinations unseen in the training set, suffering from combination leakage issues. In this work, we propose a novel rule-generation perspective for compositionality estimation for LLMs. It requires LLMs to generate a program as rules for dataset mapping and provides estimates of the compositionality of LLMs using complexity-based theory. The perspective addresses the limitations of compositional generalization tests and provides a new way to analyze the compositionality characterization of LLMs. We conduct experiments and analysis of existing advanced LLMs based on this perspective on a string-to-grid task, and find various compositionality characterizations and compositionality deficiencies exhibited by LLMs.
### Title:
          Bibliometric Mapping of AI-Supported Social Presence in Online Learning Environments: Trends, Collaboration, and Thematic Directions
 - **Authors:** Almer B. Gamboa, Erika M. Pineda, Rhiziel P. Manalese, Aileen P. De Leon, Vernon Grace M. Maniago, Jan Henry B. Sunga, Agnes R. Regala, Roque Francis B. Dianelo, John Paul P. Miranda
 - **Subjects:** Subjects:
Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This study examines the development, influence, and collaboration patterns in AI-supported social presence research within online learning environments. Utilizing 59 open-access empirical studies from Scopus, the study applies citation analysis, co-authorship mapping, institutional analysis, and keyword clustering using Python-based bibliometric tools. Findings reveal an upward trend in publications since 2020, with research focusing on engagement, AI tools, instructional design, and ethical issues. While countries such as the United States and Brazil are leading contributors, international collaboration remains limited. Ethical concerns related to trust and fairness are emerging but underexplored. The study highlights the importance of ethical integration, interdisciplinary collaboration, and learner-centered AI applications in education.
### Title:
          Judge, Then Drive: A Critic-Centric Vision Language Action Framework for Autonomous Driving
 - **Authors:** Lijin Yang, Jianing Huang, Zhongzhan Huang, Shu Liu, Hao Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in vision language action (VLA) models have shown remarkable potential for autonomous driving by directly mapping multimodal inputs to control signals. However, previous VLA-based methods have not explicitly exploited the critic capability of VLAs to refine driving decisions, even though such capability has been well demonstrated in other LLM-based domains, thereby limiting their performance in complex closed-loop scenarios. In this work, we present a theoretically inspired two-stage framework, CriticVLA, which extends the role of VLAs from acting to judging. CriticVLA first generates a rough trajectory and then refines it through multimodal evaluation and single-step optimization guided by a VLA-based critic, yielding higher-quality driving behaviors. To support this process, we construct a large-scale synthetic dataset of 12.9 million annotated trajectories covering diverse driving scenarios, which enhances the critic's reasoning and refinement abilities. Extensive closed-loop experiments on the Bench2Drive benchmark show that CriticVLA significantly surpasses state-of-the-art baselines, achieving a 73.33% total success rate and delivering about 30% improvement in challenging scenarios.
### Title:
          Why Mean Pooling Works: Quantifying Second-Order Collapse in Text Embeddings
 - **Authors:** Tomomasa Hara, Hiroto Kurita, Masaaki Imaizumi, Kentaro Inui, Sho Yokoi
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 For constructing text embeddings, mean pooling, which averages token embeddings, is the standard approach. This paper examines whether mean pooling actually works well in real models. First, we note that mean pooling can collapse information beyond the first-order statistics of the token embeddings, such as second-order statistics that capture their spatial structure, potentially mapping distinct token embedding distributions to similar text embeddings. Motivated by this concern, we propose a simple metric to quantify such a collapse induced by mean pooling. Then, using this metric, we empirically measure how often this collapse occurs in actual models and texts, and find that modern text encoders are robust to this collapse. In particular, contrastive fine-tuned text encoders tend to be less prone to the collapse than their pretrained backbone models. We also find that the robustness of these text encoders lies in the concentration of token embeddings within each text. In addition, we find that robustness to the collapse, as quantified by our proposed metric, correlates with downstream task performance. Overall, our findings offer a new perspective on why modern text encoders remain effective despite relying on seemingly coarse mean pooling.
### Title:
          RIHA: Report-Image Hierarchical Alignment for Radiology Report Generation
 - **Authors:** Yucheng Chen, Yang Yu, Yufei Shi, Conghao Xiong, Xulei Yang, Si Yong Yeo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Radiology report generation (RRG) has emerged as a promising approach to alleviate radiologists' workload and reduce human errors by automatically generating diagnostic reports from medical images. A key challenge in RRG is achieving fine-grained alignment between complex visual features and the hierarchical structure of long-form radiology reports. Although recent methods have improved image-text representation learning, they often treat reports as flat sequences, overlooking their structured sections and semantic hierarchies. This simplification hinders precise cross-modal alignment and weakens RRG accuracy. To address this challenge, we propose RIHA (Report-Image Hierarchical Alignment Transformer), a novel end-to-end framework that performs multi-level alignment between radiological images and their corresponding reports across paragraph, sentence, and word levels. This hierarchical alignment enables more precise cross-modal mapping, essential for capturing the nuanced semantics embedded in clinical narratives. Specifically, RIHA introduces a Visual Feature Pyramid (VFP) to extract multi-scale visual features and a Text Feature Pyramid (TFP) to represent multi-granularity textual structures. These components are integrated through a Cross-modal Hierarchical Alignment (CHA) module, leveraging optimal transport to effectively align visual and textual features across various levels. Furthermore, we incorporate Relative Positional Encoding (RPE) into the decoder to model spatial and semantic relationships among tokens, enhancing the token-level alignment between visual features and generated text. Extensive experiments on two benchmark chest X-ray datasets, IU-Xray and MIMIC-CXR, demonstrate that RIHA outperforms existing state-of-the-art models in both natural language generation and clinical efficacy metrics.
### Title:
          Math Education Digital Shadows for facilitating learning with LLMs: Math performance, anxiety and confidence in simulated students and AIs
 - **Authors:** Naomi Esposito, Anthony Tricarico, Luisa Porzio, Ali Aghazadeh Ardebili, Massimo Stella
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computers and Society (cs.CY); Human-Computer Interaction (cs.HC); Machine Learning (cs.LG); Social and Information Networks (cs.SI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 To enhance LLMs' impact on math education, we need data on their mathematical prowess and biases across prompts. To fill this gap, we introduce MEDS (Math Education Digital Shadows) as a dataset mapping how large language models reason about and report mathematics across human- and AI-like conditions. MEDS involves 28,000 personas from 14 LLMs (from families like Mistral, Qwen, DeepSeek, Granite, Phi and Grok) shadowing either humans or AI assistants. Each record/shadow includes a set of prompts along with psychological/sociodemographic persona metadata and four types of math tasks: (i) open math interview, (ii) three psychometric tests about math perceptions with explanations, (iii) cognitive networks capturing math attitudes, and (iv) 18 high-school math test questions together with their reasoning and confidence scores. MEDS differs from traditional score-only math benchmarks because it integrates concepts of self-efficacy, math anxiety, and cognitive network science besides math proficiency scores. Data validation shows that the sampled LLMs exhibit schema integrity and consistent personas, together with family-specific peculiarities like human-like negative math attitudes, logical fallacies, and math overconfidence. MEDS will benefit learning analytics experts, cognitive scientists, and developers of safer AI tutors in mathematics.
### Title:
          Towards an Ethical AI Curriculum: A Pan-African, Culturally Contextualized Framework for Primary and Secondary Education
 - **Authors:** Abidemi Kuburat Adedeji, Franklin Tchakounte, Sulaiman Oluwasegun Yusuff
 - **Subjects:** Subjects:
Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Artificial intelligence (AI) is now embedded in educational, civic, and economic systems worldwide. For African primary and secondary education, this creates a double imperative: to prepare a young population (over sixty per cent of Africans are under twenty-five) for AI-mediated labour markets without uncritically importing curricula designed for other linguistic, cultural, and socio-political contexts. The African Union's Continental AI Strategy (2024) and the 2025 Africa Declaration on AI have elevated these questions to the continental agenda. This paper proposes a Pan-African, culturally contextualised, and ethically grounded framework for integrating AI education into African primary and secondary schools. The paper is a structured conceptual synthesis of continental and national policy documents, peer-reviewed scholarship on AI ethics, AI literacy, decolonial pedagogy, and Ubuntu-grounded AI governance. We contribute: (i) a framework of six guiding principles, four curriculum domains, five ethical competencies, and an age-banded progression from lower primary to upper secondary; (ii) a comparative analysis of continental and national policy contexts; (iii) an explicit mapping between global AI-ethics principles and Ubuntu-informed relational ethics; (iv) a planned empirical validation programme combining a Delphi study, teacher surveys across anglophone, francophone, lusophone, and arabophone contexts, and multi-country classroom piloting; and (v) targeted recommendations for policymakers, educators, civil society, and international partners. We argue that an ethical AI curriculum can serve as a transformative tool for equity, innovation, and social justice, and outline a research agenda to embed ethics, resilience, and critical thinking at the core of Africa's digital future.
### Title:
          Feature-Centric Methodology for Analyzing Cross-Chain NFT Migration Compatibility
 - **Authors:** Mohd Sameen Chishti, Damilare Peter Oyinloye, Jingyue Li
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-chain NFT migration refers to the process of transferring digital assets along with their associated functionalities and guarantees between distinct blockchain platforms. However, architectural divergences among these platforms introduce critical challenges, often resulting in features that fail to behave as intended. While protocol-level mechanisms can coordinate data transfer, they are insufficient to resolve deeper compatibility issues arising from fundamental differences in state organization, transaction execution, and ownership representation. Thus, the critical challenge lies in predicting which NFT features can be preserved, which require redesign, and which are fundamentally incompatible, prior to undertaking costly migration attempts. To address this challenge, we first derive a tailored four-layer NFT architecture based on standard blockchain stacks, distinguishing cryptographic, state-management, transaction-processing, and ownership primitives, with explicit upward dependencies. Building on this architecture, we conceptualize an NFT as a bundle of features and define successful cross-chain NFT migration as the preservation of these features. Grounded in this model, we propose a four-phase migration analysis methodology comprising source feature specification, primitive-level dependency mapping, target platform profiling, and compatibility assessment, which classifies each feature as natively preserved, partially mismatched, or completely mismatched. We evaluate this methodology through a proof-of-concept analysis of Ethereum-to-Solana NFT migration, identifying several incompatibility issues that hinder seamless NFT migration.
### Title:
          Maximally Diverse Stable Matchings: Optimizing Arbitrary Institutional Objectives
 - **Authors:** Gergely Csáji, Zhaohong Sun
 - **Subjects:** Subjects:
Computer Science and Game Theory (cs.GT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Stable matching theory is the foundation of centralized clearinghouses worldwide, from school choice programs to medical residency allocations. However, incorporating complex distributional goals-such as multi-dimensional diversity quotas or sibling co-assignment guarantees-often compromises stability or renders the problem computationally intractable. The existing literature typically addresses this tension by weakening stability to accommodate distributional constraints. In contrast, the reverse question remains largely unexplored: if we restrict attention to stable matchings, to what extent can such distributional objectives be achieved? In this paper, we resolve this tension by introducing a general, polynomial-time algorithmic framework to optimize arbitrary institutional (or even two-sided) objectives within the set of stable matchings. We prove that for any polynomial-time computable set functions $g_i$ evaluating the assigned students at institutions $i \in I$, a stable matching minimizing either the utilitarian objective $\sum_{i\in I} g_i$ or the egalitarian objective $\max_{i\in I} g_i$ can be found efficiently. Our approach leverages the structural properties of stable matchings, mapping arbitrary set functions to linear edge weights. We apply this theorem to efficiently solve major open practical problems: finding stable matchings that minimally violate overlapping diversity quotas (under both total and maximum violations) and maximizing the number of sibling families assigned to the same institution. Even when the distributional objective is prioritized, our algorithm helps to quantify the ``price of stability'', i.e., the gap between the maximally diverse matching and the maximally diverse stable matching.
### Title:
          Learning from Disagreement: Clinician Overrides as Implicit Preference Signals for Clinical AI in Value-Based Care
 - **Authors:** Prabhjot Singh, Abhishek Gupta, Chris Betz, Abe Flansburg, Brett Ives, Sudeep Lama, Jung Hoon Son
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We reframe clinician overrides of clinical AI recommendations as implicit preference data - the same signal structure exploited by reinforcement learning from human feedback (RLHF), but richer: the annotator is a domain expert, the alternatives carry real consequences, and downstream outcomes are observable. We present a formal framework extending standard preference learning with three contributions: a five-category override taxonomy mapping override types to distinct model update targets; a preference formulation conditioned on patient state s, organizational context c, and clinician capability kappa, where kappa decomposes into execution capability kappa-exec and alignment capability kappa-align; and a dual learning architecture that jointly trains a reward model and a capability model via alternating optimization, preventing a failure mode we term suppression bias-the systematic suppression of correct-but-difficult recommendations when clinician capability falls below the execution threshold. We argue that chronic disease management under outcome-based payment contracts produces override data with uniquely favorable properties-longitudinal density, concentrated decision space, outcome labels, and natural capability variation-and that training environments combining longitudinal outcome measurement with aligned financial incentives are a necessary condition for learning a reward model aligned with patient trajectory rather than with encounter economics. This framework emerged from operational work to improve clinician capability in a live value-based care deployment.
### Title:
          Mapping the Methodological Space of Classroom Interaction Research: Scale, Duration, and Modality in an Age of AI
 - **Authors:** Dorottya Demszky, Edith Bouton, Alison Twiner, Sara Hennessy, Richard Correnti
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Research on classroom interaction has long been divided between large-scale observation and in-depth ethnographic work. We propose a framework mapping this methodological space along three dimensions--scale, duration, and modality--where a study's position shapes what it reveals and obscures. We illustrate it through contrasting studies of dialogic teaching--Howe et al. (2019) and Snell and Lefstein (2018)--and an interview with the lead researchers, organized around three questions: what can be operationalized, what mechanisms become visible, and what translates to practice. We then examine how AI is expanding this space and how the framework can guide research and tool design.
### Title:
          Beyond Code, We Are People: A Systematic Mapping of 25 Years of Literature on Soft Skills in Agile Development Teams
 - **Authors:** Israely Lima, Lucas Moura Lourenço, Márcio Ribeiro, Ivan Machado, Carla Ilane Bezerra
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Software development is a sociotechnical and human-centered endeavor in which human factors directly influence quality, productivity, and innovation capacity. In this context, career development in computing goes beyond technical mastery, requiring competencies that enable professionals to deal with continuous change and collaborative demands. Among these, non-technical skills (soft skills) stand out, encompassing social, emotional, and communicational dimensions essential to team effectiveness and the success of software projects. Despite their recognized importance, there is still a need for a systematic mapping of the most relevant soft skills over the past 25 years, a period marked by the adoption of agile approaches in industry. This gap limits the integration of human and technical aspects in software development. This study presents a systematic mapping of the literature, analyzing 97 studies published between January 2000 and May 2025 across major scientific databases. The results identify recurring competencies such as communication, adaptability, teamwork, and leadership, as well as their association with different roles in agile contexts. The main agile approaches adopted, particularly Scrum, are also identified, along with key gaps in the literature, such as the lack of studies on role specific soft skills. The findings can support researchers, educators, and practitioners in designing curricula, training strategies, and organizational practices aligned with human factors, reinforcing the importance of integrating social and technical dimensions in the development of collaborative and innovative professionals.
### Title:
          MoCapAnything V2: End-to-End Motion Capture for Arbitrary Skeletons
 - **Authors:** Kehong Gong, Zhengyu Wen, Dao Thien Phong, Mingxi Xu, Weixia He, Qi Wang, Ning Zhang, Zhengyu Li, Guanli Hou, Dongze Lian, Xiaoyu He, Mingyuan Zhang, Hanwang Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent methods for arbitrary-skeleton motion capture from monocular video follow a factorized pipeline, where a Video-to-Pose network predicts joint positions and an analytical inverse-kinematics (IK) stage recovers joint rotations. While effective, this design is inherently limited, since joint positions do not fully determine rotations and leave degrees of freedom such as bone-axis twist ambiguous, and the non-differentiable IK stage prevents the system from adapting to noisy predictions or optimizing for the final animation objective. In this work, we present the first fully end-to-end framework in which both Video-to-Pose and Pose-to-Rotation are learnable and jointly optimized. We observe that the ambiguity in pose-to-rotation mapping arises from missing coordinate system information: the same joint positions can correspond to different rotations under different rest poses and local axis conventions. To resolve this, we introduce a reference pose-rotation pair from the target asset, which, together with the rest pose, not only anchors the mapping but also defines the underlying rotation coordinate system. This formulation turns rotation prediction into a well-constrained conditional problem and enables effective learning. In addition, our model predicts joint positions directly from video without relying on mesh intermediates, improving both robustness and efficiency. Both stages share a skeleton-aware Global-Local Graph-guided Multi-Head Attention (GL-GMHA) module for joint-level local reasoning and global coordination. Experiments on Truebones Zoo and Objaverse show that our method reduces rotation error from ~17 degrees to ~10 degrees, and to 6.54 degrees on unseen skeletons, while achieving ~20x faster inference than mesh-based pipelines. Project page: this https URL
## Keyword: localization
### Title:
          From Elastic to Viscoelastic: An EEMD-Enhanced Pulse Transit Time Model for Robust Blood Pressure Estimation
 - **Authors:** Boyuan Gu, Yijin Yang, Shuaiqi Cheng, Xiaorong Ding
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cuffless blood pressure (BP) estimation based on Pulse Transit Time (PTT) has emerged as a promising solution for continuous health monitoring. However, conventional models relying on the Moens-Korteweg equation often fail during rapid hemodynamic fluctuations, as they assume arterial walls are purely elastic and neglect inherent viscoelasticity. To address this limitation, we propose a physics-informed framework introducing a viscoelastic compensation mechanism. First, raw photoplethysmogram (PPG) signals undergo high-fidelity reconstruction using Modified Akima (Makima) interpolation. Second, a robust Intersecting Tangent Method is applied for precise pulse foot localization. Crucially, we utilize Ensemble Empirical Mode Decomposition (EEMD) to isolate high-frequency Intrinsic Mode Functions (IMFs), defining a ``Viscoelastic Velocity Metric'' to quantify the vascular damping effect ($\eta \cdot \dot{\epsilon}$) typically ignored by elastic models. The framework was rigorously validated on a challenging subset of the MIMIC-II database (364 subjects, 28,525 cardiac cycles) characterized by a high prevalence of hypertension (23.4\%). Experimental results demonstrate medical-grade accuracy, yielding a Root Mean Square Error (RMSE) of 5.22 mmHg for Systolic and 3.65 mmHg for Diastolic BP, with Pearson correlation coefficients ($R > 0.97$). These findings confirm that incorporating viscoelastic features significantly enhances robustness against vascular hysteresis.
### Title:
          Decoding Scientific Experimental Images: The SPUR Benchmark for Perception, Understanding, and Reasoning
 - **Authors:** Junpeng Ding, Zichen Tang, Haihong E, Mengyuan Ji, Yang Liu, Haolin Tian, Haiyang Sun, Pengqi Sun, Yang Xu, Yichen Liu, Haocheng Gao, Zijie Xi, Ruomeng Jiang, Peizhi Zhao, Rongjin Li, Yuanze Li, Jiacheng Liu, Zhongjun Yang, Jintong Chen, Siying Lin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce SPUR, a comprehensive benchmark for scientific experimental image perception, understanding, and reasoning, comprising 4,264 question-answering (QA) pairs derived from 1,084 expert-curated images. SPUR features three key innovations: (1) Panel-Level Fine-Grained Perception: evaluating the visual perception of multimodal large language models (MLLMs) across three dimensions (numerical, morphological, and information localization) on six fine-grained panel types; (2) Cross-Panel Relation Understanding: utilizing complex images with an average of 14.3 panels per sample to evaluate MLLMs' ability to decipher intricate cross-panel relations; (3) Expert-Level Reasoning: assessment of qualitative and quantitative reasoning across five experimental paradigms to determine if models can infer conclusions from evidence as human experts do. Comprehensive evaluation of 20 MLLMs and four multimodal Chain-of-Thought (MCoT) methods reveals that current models fall significantly short of the expert-level requirements for scientific image interpretation, underscoring a critical bottleneck in AI for Science (AI4S) research.
### Title:
          Auditing Frontier Vision-Language Models for Trustworthy Medical VQA: Grounding Failures, Format Collapse, and Domain Adaptation
 - **Authors:** Xupeng Chen, Binbin Shi, Chenqian Le, Qifu Yin, Lang Lin, Haowei Ni, Ran Gong, Panfeng Li
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deploying vision-language models (VLMs) in clinical settings demands auditable behavior under realistic failure conditions, yet the failure landscape of frontier VLMs on specialized medical inputs is poorly characterized. We audit five recent frontier and grounding-aware VLMs (Gemini~2.5~Pro, GPT-5, o3, GLM-4.5V, Qwen~2.5~VL) on Medical VQA along two trust-relevant axes. Perception: all models localize anatomical and pathological targets poorly -- the best model reaches only 0.23 mean IoU and 19.1% Acc@0.5 -- and exhibit clinically dangerous laterality confusion. Pipeline integration: a self-grounding pipeline, where the same model localizes then answers, degrades VQA accuracy for every model -- driven by both inaccurate localization and format-compliance failures under the two-step prompt (parse failure rises to 70%--99% for Gemini and GPT-5 on VQA-RAD). Replacing predicted boxes with ground-truth annotations recovers and improves VQA accuracy, consistent with the failure residing in the perception module rather than in the decomposition itself. These observational findings identify grounding quality as a primary trustworthiness bottleneck in our SLAKE bounding-box setting. As a complementary fine-tuning follow-up, supervised fine-tuning of Qwen~2.5~VL on combined Med-VQA training data attains the highest reported SLAKE open-ended recall (85.5%) among comparable methods, suggesting that the VQA-level gap is tractable with domain adaptation; whether this also closes the perception/trustworthiness bottleneck is left to future work.
### Title:
          Learning-Based Hierarchical Scene Graph Matching for Robot Localization Leveraging Prior Maps
 - **Authors:** Nimrod Millenium Ndulue, Jose Andres Millan-Romera, Matteo Giorgi, Holger Voos, Jose Luis Sanchez-Lopez
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate localization is a fundamental requirement for autonomous robots operating in indoor environments. Scene graphs encode the spatial structure of an environment as a hierarchy of semantic entities and their relationships, and can be constructed both online from robot sensor data and offline from architectural priors such as Building Information Models (BIM). Matching these two complementary representations enables drift correction in SLAM by grounding robot observations against a known structural prior. However, establishing reliable node-to-node correspondences between them remains an open challenge: existing combinatorial methods are prohibitively expensive at scale, and prior learned approaches address only flat graph matching, ignoring the multi-level semantic structure present in both representations. Here we present a learned, end-to-end differentiable pipeline that augments both graphs with semantically motivated edge types encoding intra- and inter- level relationships, explicitly exploiting this hierarchy to enable simultaneous matching from high-level room concepts down to low-level wall surfaces. Trained exclusively on floor plans, the proposed method outperforms the combinatorial baseline in F1 on real LiDAR environments while running an order of magnitude faster, demonstrating viable zero-shot generalization for BIM-assisted robot localization.
### Title:
          Training-Free Tunnel Defect Inspection and Engineering Interpretation via Visual Recalibration and Entity Reconstruction
 - **Authors:** Shipeng Liu, Liang Zhao, Dengfeng Chen, Zhanping Song
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tunnel inspection requires outputs that can support defect localization, measurement, severity grading, and engineering documentation. Existing training-free foundation-model pipelines usually stop at coarse open-vocabulary proposals, which are difficult to use directly in interference-heavy tunnel scenes. We propose a training-free framework TunnelMIND. Specifically, language-guided defect proposals are not treated as final outputs; instead, their spatial support is recalibrated at inference time through dense visual consistency, so that coarse semantic anchors can be transformed into more reliable prompts under tunnel-specific hard negatives. The resulting masks are further reconstructed into structured defect entities with category, location, geometry, severity, and context attributes, which are then mapped to retrieval-grounded explanation and engineering-readable report generation under expert knowledge constraints. On visible, GPR, and road defect tasks, TunnelMIND achieves F1 scores of 0.68, 0.78, and 0.72, respectively. Overall, TunnelMIND shows that training-free tunnel inspection can move beyond coarse localization toward structured defect evidence for engineering assessment.
### Title:
          DPN-LE: Dual Personality Neuron Localization and Editing for Large Language Models
 - **Authors:** Lifan Zheng, Xue Yang, Jiawei Chen, Chenyan Wu, Jingyuan Zhang, Fanheng Kong, Xinyi Zeng, Xiang Chen, Yu Tian
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the widespread adoption of large language models (LLMs), understanding their personality representation mechanisms has become critical. As a novel paradigm in Personality Editing, most existing methods employ neuron-editing to locate and modify LLM neurons, requiring changes to numerous neurons and leading to significant performance degradation. This raises a fundamental question: Are all modified neurons directly related to personality representation? In this work, we investigate and quantify this specificity through assessments of general capability impact and representation-level patterns. We find that: 1) Current methods can change personalities but reduce overall performance. 2) Neurons are multifunctional, connecting personality traits and general knowledge. 3) Opposing personality traits demonstrate distinctly mutually exclusive representation patterns. Motivated by these findings, we propose DPN-LE (Dual Personality Neuron Localization and Editing), which identifies personality-specific neurons by contrasting MLP activations between high-trait and low-trait samples. DPN-LE constructs layer-wise steering vectors and applies dual-criterion filtering based on Cohen's $d$ effect size and activation magnitude to isolate mutually exclusive neuron subsets. Sparse linear intervention on these neurons enables precise personality control at inference time. Using only 1,000 contrastive sample pairs per trait, DPN-LE intervenes on $\sim$0.5\% of neurons while achieving competitive personality control and substantially better capability preservation across reasoning tasks. Experiments on LLaMA-3-8B-Instruct and Qwen2.5-7B-Instruct demonstrate the effectiveness and generalizability of our approach.
### Title:
          FineState-Bench: Benchmarking State-Conditioned Grounding for Fine-grained GUI State Setting
 - **Authors:** Fengxian Ji, Jingpu Yang, Zirui Song, Yuanxi Wang, Zhexuan Cui, Yuke Li, Qian Jiang, Xiuying Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Databases (cs.DB)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite the rapid progress of large vision-language models (LVLMs), fine-grained, state-conditioned GUI interaction remains challenging. Current evaluations offer limited coverage, imprecise target-state definitions, and an overreliance on final-task success, obscuring where and why agents fail. To address this gap, we introduce \textbf{FineState-Bench}, a benchmark that evaluates whether an agent can correctly ground an instruction to the intended UI control and reach the exact target state. FineState-Bench comprises 2,209 instances across desktop, web, and mobile platforms, spanning four interaction families and 23 UI component types, with each instance explicitly specifying an exact target state for fine-grained state setting. We further propose \textit{FineState-Metrics}, a four-stage diagnostic pipeline with stage-wise success rates: Localization Success Rate (SR@Loc), Interaction Success Rate (SR@Int), Exact State Success Rate at Locate (ES-SR@Loc), and Exact State Success Rate at Interact (ES-SR@Int), and a plug-and-play \textit{Visual Diagnostic Assistant} (VDA) that generates a Description and a bounding-box Localization Hint to diagnose visual grounding reason via controlled w/ vs.\ w/o comparisons. On FineState-Bench, exact goal-state success remains low: ES-SR@Int peaks at 32.8\% on Web and 22.8\% on average across platforms. With VDA localization hints, Gemini-2.5-Flash gains +14.9 ES-SR@Int points, suggesting substantial headroom from improved visual grounding, yet overall accuracy is still insufficient for reliable fine-grained state-conditioned interaction \href{this https URL}{Github.}
### Title:
          Echo-α: Large Agentic Multimodal Reasoning Model for Ultrasound Interpretation
 - **Authors:** Jing Zhang, Wentao Jiang, Tao Huang, Zhiwei Wang, Jianxin Liu, Jian Chen, Ping Ye, Gang Wang, Zengmao Wang, Bo Du, Dacheng Tao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ultrasound interpretation requires both precise lesion localization and holistic clinical reasoning, yet existing methods typically excel at only one of these capabilities: specialized detectors offer strong localization but limited reasoning, whereas multimodal large language models (MLLMs) provide flexible reasoning but weak grounding in specialized medical domains. We present Echo-{\alpha}, an agentic multimodal reasoning model for ultrasound interpretation that unifies these strengths within an invoke-and-reason framework. Echo-{\alpha} is trained to coordinate organ-specific detector outputs, integrate them with global visual context, and convert the resulting evidence into grounded diagnostic decisions beyond detector-only inference. This behavior is established through a nine-task supervised curriculum and then refined by sequential reinforcement learning under different reward trade-offs, yielding Echo-{\alpha}-Grounding for lesion anchoring and Echo-{\alpha}-Diagnosis for final diagnosis. On multi-center renal and breast ultrasound benchmarks, Echo-{\alpha} outperforms competitive baselines on both grounding and diagnosis. In particular, on cross-center test sets, Echo-{\alpha}-Grounding attains 56.73%/43.78% F1@0.5 and Echo- {\alpha}-Diagnosis reaches 74.90%/49.20% overall accuracy on renal/breast ultrasound. These results suggest that agentic multimodal reasoning can turn specialized detectors into verifiable clinical evidence, offering a practical route toward ultrasound AI systems that are more accurate, interpretable, and transferable. The repository is at this https URL.
### Title:
          Design and Characteristics of a Thin-Film ThermoMesh for the Efficient Embedded Sensing of a Spatio-Temporally Sparse Heat Source
 - **Authors:** Sajjad Boorghan Farahan, Ahmed Alajlouni, Jingzhou Zhao
 - **Subjects:** Subjects:
Robotics (cs.RO); Image and Video Processing (eess.IV); Instrumentation and Detectors (physics.ins-det)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work presents ThermoMesh, a passive thin-film thermoelectric mesh sensor designed to detect and characterize spatio-temporally sparse heat sources through conduction-based thermal imaging. The device integrates thermoelectric junctions with linear or nonlinear interlayer resistive elements to perform simultaneous sensing and in-sensor compression. We focus on the single-event (1-sparse) operation and define four performance metrics: range, efficiency, sensitivity, and accuracy. Numerical modeling shows that a linear resistive interlayer flattens the sensitivity distribution and improves minimum sensitivity by approximately tenfold for a $16\times16$ mesh. Nonlinear temperature-dependent interlayers further enhance minimum sensitivity at scale: a ceramic negative-temperature-coefficient (NTC) layer over 973--1273~K yields a $\sim14{,}500\times$ higher minimum sensitivity than the linear design at a $200\times200$ mesh, while a VO$_2$ interlayer modeled across its metal--insulator transition (MIT) over 298--373~K yields a $\sim24\times$ improvement. Using synthetic 1-sparse datasets with white boundary-channel noise at a signal-to-noise ratio of 40~dB, the VO$_2$ case achieved $98\%$ localization accuracy, a mean absolute temperature error of $0.23$~K, and a noise-equivalent temperature (NET) of $0.07$~K. For the ceramic-NTC case no localization errors were observed under the tested conditions, with a mean absolute temperature error of $1.83$~K and a NET of $1.49$~K. These results indicate that ThermoMesh could enable energy-efficient embedded thermal sensing in scenarios where conventional infrared imaging is limited, such as molten-droplet detection or hot-spot monitoring in harsh environments.
### Title:
          AEGIS: A Holistic Benchmark for Evaluating Forensic Analysis of AI-Generated Academic Images
 - **Authors:** Bo Zhang, Tzu-Yen Ma, Zichen Tang, Junpeng Ding, Zirui Wang, Yizhuo Zhao, Peilin Gao, Zijie Xi, Zixin Ding, Haiyang Sun, Haocheng Gao, Yuan Liu, Liangjia Wang, Yiling Huang, Yujie Wang, Yuyue Zhang, Ronghui Xi, Yuanze Li, Jiacheng Liu, Zhongjun Yang, Haihong E
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce AEGIS, A holistic benchmark for Evaluating forensic analysis of AI-Generated academic ImageS. Compared to existing benchmarks, AEGIS features three key advances: (1) Domain-Specific Complexity: covering seven academic categories with 39 fine-grained subtypes, exposing intrinsic forensic difficulty, where even GPT-5.1 reaches 48.80% overall performance and expert models achieve only limited localization accuracy (IoU 30.09%); (2) Diverse Forgery Simulations: modeling four prevalent academic forgery strategies across 25 generative models, with 11 yielding average forensic accuracy below 50%, showing that forensics lag behind generative advances; and (3) Multi-Dimensional Forensic Evaluation: jointly assessing detection, reasoning, and localization, revealing complementary strengths between model families, with multimodal large language models (MLLMs) at 84.74% accuracy in textual artifact recognition and expert detectors peaking at 79.54% accuracy in binary authenticity detection. By evaluating 25 leading MLLMs, nine expert models, and one unified multimodal understanding and generation model, AEGIS serves as a diagnostic testbed exposing fundamental limitations in academic image forensics.
### Title:
          Stop Holding Your Breath: CT-Informed Gaussian Splatting for Dynamic Bronchoscopy
 - **Authors:** Andrea Dunn Beltran, Daniel Rho, Aarav Mehta, Xinqi Xiong, Raúl San José Estépar, Ron Alterovitz, Marc Niethammer, Roni Sengupta
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bronchoscopic navigation relies on registering endoscopic video to a preoperative CT scan, but respiratory motion deforms the airway by 5-20 mm, creating CT-to-body divergence that limits localization accuracy. In practice, this is mitigated through breath-hold protocols, which attempt to match the intraoperative anatomy to a static CT, but are difficult to reproduce and disrupt clinical workflow. We propose to eliminate the need for breath-hold protocols by leveraging patient-specific respiratory modeling. Paired inhale-exhale CT scans, already acquired for planning, implicitly define the patient-specific deformation space of the breathing airway. By registering these scans, we reduce respiratory motion to a single scalar breathing phase per frame, constraining all reconstructions to anatomically observed configurations. We embed this representation within a mesh-anchored Gaussian splatting framework, where a lightweight estimator infers breathing phase directly from endoscopic RGB, enabling continuous, deformation-aware reconstruction throughout the respiratory cycle without breath-holds or external sensing. To enable quantitative evaluation, we introduce RESPIRE, a physically grounded bronchoscopy simulation pipeline with per-frame ground truth for geometry, pose, breathing phase, and deformation. Experiments on RESPIRE show that our approach achieves geometrically faithful reconstruction, over 20x faster training, and 1.22 mm target localization accuracy (within the 3mm clinically relevant tolerances) outperforming unconstrained single-CT baselines. Please check out our website for additional visuals: this https URL
## Keyword: transformer
### Title:
          LLM Biases
 - **Authors:** Jinhui Han, Ming Hu, Xilin Zhang
 - **Subjects:** Subjects:
Computers and Society (cs.CY); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based agentic AI is rapidly being deployed on major platforms to help users shop, watch, and navigate content with less effort. While these systems can deliver impressive performance, a key concern is whether they may be less reliable than they appear. We ask a simple but fundamental question: whether the mechanisms that make transformer-based agents effective can also induce systematic biases or distortions? We study this question through a theoretical analysis of transformer-based generative recommenders, in which the next user interaction is generated sequentially from the user history. Focusing on how the model allocates attention across historical evidence, we identify four bias channels: (i) Positional bias: stronger positional encoding shifts influence toward recent history, improving responsiveness but potentially reducing stability and long-term diversity; (ii) Popularity amplification: small frequency differences in data can be magnified into disproportionate exposure, contributing to Matthew effects and echo chambers; (iii) Latent driver bias: when important drivers of user choices are not directly observed, the model can place overly concentrated weight on a small subset of past events, creating overconfident attributions. (iv) Synthetic data bias: when users increasingly follow AI suggestions and platforms retrain on model-shaped synthetic logs, outputs can concentrate over time, and long-tail alternatives can disappear first. Our analysis highlights mechanism-level reliability risks that may not be visible in offline performance metrics. The four bias channels indicate that large-scale deployment may systematically distort exposure and choice. For managers, the immediate implication is to treat these as operational risk factors and to monitor concentration and drift over time, rather than assuming that performance gains alone guarantee reliability.
### Title:
          Learning Rate Transfer in Normalized Transformers
 - **Authors:** Boris Shigida, Boris Hanin, Andrey Gromov
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Normalized Transformer, or nGPT (arXiv:2410.01131) achieves impressive training speedups and does not require weight decay or learning rate warmup. However, despite having hyperparameters that explicitly scale with model size, we observe that nGPT does not exhibit learning rate transfer across model dimension and token horizon. To rectify this, we combine numerical experiments with a principled use of alignment exponents (arXiv:2407.05872) to revisit and modify the $\mu$P approach to hyperparameter transfer (arXiv:2011.14522). The result is a novel nGPT parameterization we call $\nu$GPT. Through extensive empirical validation, we find $\nu$GPT exhibits learning rate transfer across width, depth, and token horizon.
### Title:
          End-to-end autonomous scientific discovery on a real optical platform
 - **Authors:** Shuxing Yang, Fujia Chen, Rui Zhao, Junyao Wu, Yize Wang, Haiyao Luo, Ning Han, Qiaolu Chen, Yuze Hu, Wenhao Li, Mingzhu Li, Hongsheng Chen, Yihao Yang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Optics (physics.optics)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scientific research has long been human-led, driving new knowledge and transformative technologies through the continual revision of questions, methods and claims as evidence accumulates. Although large language model (LLM)-based agents are beginning to move beyond assisting predefined research workflows, none has yet demonstrated end-to-end autonomous discovery in a real physical system that produces a nontrivial result supported by experimental evidence. Here we introduce Qiushi Discovery Engine, an LLM-based agentic system for end-to-end autonomous scientific discovery on a real optical platform. Qiushi Engine combines nonlinear research phases, Meta-Trace memory and a dual-layer architecture to maintain adaptive and stable research trajectories across long-horizon investigations involving thousands of LLM-mediated reasoning, measurement and revision actions. It autonomously reproduces a published transmission-matrix experiment on a non-original platform and converts an abstract coherence-order theory into experimental observables, providing, to our knowledge, the first observation of this class of coherence-order structure. More importantly, in an open-ended study involving 145.9 million tokens, 3,242 LLM calls, 1,242 tool calls, 163 research notes and 44 scripts, Qiushi Engine proposes and experimentally validates optical bilinear interaction, a physical mechanism structurally analogous to a core operation in Transformer attention. This AI-discovered mechanism suggests a route towards high-speed, energy-efficient optical hardware for pairwise computation. To our knowledge, this is the first demonstration of an AI agentic system autonomously identifying and experimentally validating a nontrivial, previously unreported physical mechanism, marking a milestone for research-level autonomous agents.
### Title:
          Automated Detection of Mutual Gaze and Joint Attention in Dual-Camera Settings via Dual-Stream Transformers
 - **Authors:** Jakub Kosmydel, Paweł Gajewski, Arkadiusz Białek
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Analyzing mutual gaze (MG) and joint attention (JA) is critical in developmental psychology but traditionally relies on labor-intensive manual coding. Automating this process in multi-camera laboratory settings is computationally challenging due to complex cross-camera relational dynamics. In this paper, we propose a highly efficient dual-stream Transformer architecture for detecting MG and JA from synchronized dual-camera recordings. Our approach leverages frozen gaze-aware backbones (GazeLLE) to extract rich visual priors, combined with a custom token fusion mechanism to map the spatial and semantic relationships between interacting dyads. Evaluated on an ecologically valid dataset of caregiver-infant interactions, our model exhibits good performance, significantly outperforming both a convolutional baseline and a state-of-the-art multimodal Large Language Model (LLM). By open-sourcing our model and pre-trained weights, we provide behavioral scientists with a scalable tool that can be fine-tuned to diverse laboratory environments, effectively bridging the gap between computational modeling and applied interaction research.
### Title:
          Energy-Efficient Plant Monitoring via Knowledge Distillation
 - **Authors:** Ilyass Moummad, Reda Bensaid, Kawtar Zaher, Hervé Goëau, Jean-Christophe Lombardo, Joseph Salmon, Pierre Bonnet, Alexis Joly
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in large-scale visual representation learning have significantly improved performance in plant species and plant disease recognition tasks. However, state-of-the-art models, often based on high-capacity vision transformers or multimodal foundation models, remain computationally expensive and difficult to deploy in resource-constrained environments such as mobile or edge devices. This limitation hinders the scalability of automated biodiversity monitoring and precision agriculture systems, where efficiency is as critical as accuracy. In this work, we investigate knowledge distillation as an effective approach to transfer the representational capacity of large pretrained models into smaller, more efficient architectures. We focus on plant species and disease recognition, and conduct an extensive empirical study on two challenging benchmarks: Pl@ntNet300K-v2 and Deep-Plant-Disease. We evaluate four representative architectures, including two ConvNeXt models and two vision transformers, under multiple training regimes: from-scratch training and pretrained initialization, each with and without distillation. In total, we train and evaluate 70 models. Our results show that knowledge distillation consistently improves performance across tasks and architectures. Distilled models are able to match the performance of significantly larger models while maintaining substantially lower computational cost. These findings demonstrate the potential of knowledge distillation techniques to enable efficient and scalable deployment of plant recognition systems in real-world environmental applications.
### Title:
          AttriBE: Quantifying Attribute Expressivity in Body Embeddings for Recognition and Identification
 - **Authors:** Basudha Pal, Siyuan Huang, Anirudh Nanduri, Zhaoyang Wang, Rama Chellappa
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Person re-identification (ReID) systems that match individuals across images or video frames are essential in many real-world applications. However, existing methods are often influenced by attributes such as gender, pose, and body mass index (BMI), which vary in unconstrained settings and raise concerns related to fairness and generalization. To address this, we extend the notion of expressivity, defined as the mutual information between learned features and specific attributes, using a secondary neural network to quantify how strongly attributes are encoded. Applying this framework to three transformer-based ReID models on a large-scale visible-spectrum dataset, we find that BMI consistently shows the highest expressivity in deeper layers. Attributes in the final representation are ranked as BMI > Pitch > Gender > Yaw, and expressivity evolves across layers and training epochs, with pose peaking in intermediate layers and BMI strengthening with depth. We further extend the analysis to cross-spectral person identification across infrared modalities including short-wave, medium-wave, and long-wave infrared. In this setting, pitch becomes comparable to BMI and attribute trends increase monotonically across depth, suggesting increased reliance on structural cues when bridging modality gaps. Overall, the results show that transformer-based ReID embeddings encode a hierarchy of implicit attributes, with morphometric information persistently embedded and pose contributing more strongly under cross-spectral conditions.
### Title:
          The Inverse-Wisdom Law: Architectural Tribalism and the Consensus Paradox in Agentic Swarms
 - **Authors:** Dahlia Shehata, Ming Li
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As AI transitions toward multi-agent systems (MAS) to solve complex workflows, research paradigms operate on the axiomatic assumption that agent collaboration mirrors the "Wisdom of the Crowd". We challenge this assumption by formalizing the Consensus Paradox: a phenomenon where agentic swarms prioritize internal architectural agreement over external logical truth. Through a 36 experiments encompassing 12,804 trajectories across three state-of-the-art (SOTA) benchmarks (GAIA, Multi-Challenge, and SWE-bench), we prove the Inverse-Wisdom Law: in kinship-dominant swarms, adding logical agents increases the stability of erroneous trajectories rather than the probability of truth. The introduction of additional logical audits converges the system toward a Logic Saturation where internal entropy hits zero while factual error hits unity. By evaluating the interaction between the 3 preeminent SOTA models (Gemini 3.1 Pro, Claude Sonnet 4.6, and GPT-5.4), we establish the Architectural Tribalism Asymmetry as a mechanistic law of transformer weights. We demonstrate that terminal swarm integrity is strictly gated by the synthesizer's receptive logic, rather than aggregate agent quality. We define the Tribalism Coefficient and the Sycophantic Weight as the primary mechanistic determinants of swarm failure. Finally, we establish the Heterogeneity Mandate as a foundational safety requirement for resilient agentic architectures.
### Title:
          PINN-Cast: Exploring the Role of Continuous-Depth NODE in Transformers and Physics Informed Loss as Soft Physical Constraints in Short-term Weather Forecasting
 - **Authors:** Hira Saleem, Flora Salim, Cormac Purcell
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Operational weather prediction has long relied on physics-based numerical weather prediction (NWP), whose accuracy comes at the cost of substantial compute and complex simulation workflows. Recent transformer-based forecasters offer efficient data-driven alternatives, however transformers are physics-agnostic models. Additionally, standard transformer encoders evolve representations through discrete layer updates that may be less suited to modeling smooth latent dynamics. In this work, we propose a continuous-depth transformer encoder for weather forecasting that integrates Neural Ordinary Differential Equation (Neural ODE) dynamics within each encoder block. Specifically, we replace discrete residual updates with ODE-based updates solved using adaptive numerical integration. We also introduce a two-branch attention module that combines conventional patch-wise self-attention with an auxiliary branch that applies a derivative operator to attention logits, providing an additional change-sensitive interaction signal. To further align forecasts with governing principles, we propose a customized physics-informed training objective that enforces physical consistency as a soft constraint. We evaluate the proposed method against a standard discrete transformer baseline and an existing continuous-time Neural ODE forecasting variant, demonstrating the importance of PINN-Cast in short term weather forecasting.
### Title:
          YOSE: You Only Select Essential Tokens for Efficient DiT-based Video Object Removal
 - **Authors:** Chenyang Wu, Lina Lei, Fan Li, Chun-Le Guo, Dehong Kong, Xinran Qin, Zhixin Wang, Ming-Ming Cheng, Chongyi Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in Diffusion Transformer (DiT)-based video generation technologies have shown impressive results for video object removal. However, these methods still suffer from substantial inference latency. For instance, although MiniMax Remover achieves state-of-the-art visual quality, it operates at only around 10FPS, primarily due to dense computations over the entire spatiotemporal token space, even when only a small masked region actually requires processing. In this paper, we present YOSE, You Only Select Essential Tokens, an efficient fine-tuning framework. YOSE introduces two key components: Batch Variable-length Indexing (BVI) and Diffusion Process Simulator (DiffSim) Module. BVI is a differentiable dynamic indexing operator that adaptively selects essential tokens based on mask information, enabling variable-length token processing across samples. DiffSim provides a diffusion process approximation mechanism for unmasked tokens, which simulates the influence of unmasked regions within DiT self-attention to maintain semantic consistency for masked tokens. With these designs, YOSE achieves mask-aware acceleration, where the inference time scales approximately linearly with the masked regions, in contrast to full-token diffusion methods whose computation remains constant regardless of the mask size. Extensive experiments demonstrate that YOSE achieves up to 2.5X speedup in 70% of cases while maintaining visual quality comparable to the baseline. Code is available at: this https URL.
### Title:
          Sentiment Analysis of AI Adoption in Indonesian Higher Education Using Machine Learning and Transformer-Based Models
 - **Authors:** Happy Syahrul Ramadhan, Ahmad Sahidin Akbar, Karin Yehezkiel Sinaga, Luluk Muthoharoh, Ardika Satria, Martin C.T. Manullang
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This study analyzes Indonesian student opinions on the adoption of artificial intelligence in higher education using two approaches: TF-IDF-based machine learning and Transformer-based deep learning. The dataset consists of 2,295 labeled samples, combining 1,154 student opinions with additional lexical sentiment data. LightGBM, Random Forest, and Support Vector Machine (SVM) are evaluated as machine learning models, while DistilBERT is fine-tuned for binary sentiment classification. The results show that SVM achieves the best performance among the machine learning models with 82.14% test accuracy and F1-score, while DistilBERT performs best overall with 84.78% accuracy and 84.75% F1-score. These findings indicate that Transformer-based models better capture contextual information, although SVM remains a competitive and efficient alternative for sentiment classification.
### Title:
          Beyond the Training Distribution: Mapping Generalization Boundaries in Neural Program Synthesis
 - **Authors:** Henrik Voigt, Michael Habeck, Joachim Giesen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large-scale transformers achieve impressive results on program synthesis benchmarks, yet their true generalization capabilities remain obscured by data contamination and opaque training corpora. To rigorously assess whether models are truly generalizing or merely retrieving memorized templates, we introduce a strictly controlled program synthesis environment based on a domain-specific arithmetic grammar. By systematically enumerating and evaluating millions of unique programs, we construct interpretable syntactic and semantic metric spaces. This allows us to precisely map data distributions and sample train and test splits that isolate specific distributional shifts. Our experiments demonstrate that optimizing density generalization -- through diverse sampling over both semantic and syntactic spaces -- induces robust out-of-distribution generalization. Conversely, evaluating support generalization reveals that transformers severely struggle with extrapolation, experiencing a performance drop of over 30% when forced to generate syntactically novel programs. While steadily scaling up compute improves generalization, the gains follow a strictly log-linear relationship. We conclude that robust generalization requires maximizing training diversity across multiple manifolds, and our findings indicate the necessity for novel search-based approaches to break through current log-linear scaling bottlenecks.
### Title:
          RIHA: Report-Image Hierarchical Alignment for Radiology Report Generation
 - **Authors:** Yucheng Chen, Yang Yu, Yufei Shi, Conghao Xiong, Xulei Yang, Si Yong Yeo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Radiology report generation (RRG) has emerged as a promising approach to alleviate radiologists' workload and reduce human errors by automatically generating diagnostic reports from medical images. A key challenge in RRG is achieving fine-grained alignment between complex visual features and the hierarchical structure of long-form radiology reports. Although recent methods have improved image-text representation learning, they often treat reports as flat sequences, overlooking their structured sections and semantic hierarchies. This simplification hinders precise cross-modal alignment and weakens RRG accuracy. To address this challenge, we propose RIHA (Report-Image Hierarchical Alignment Transformer), a novel end-to-end framework that performs multi-level alignment between radiological images and their corresponding reports across paragraph, sentence, and word levels. This hierarchical alignment enables more precise cross-modal mapping, essential for capturing the nuanced semantics embedded in clinical narratives. Specifically, RIHA introduces a Visual Feature Pyramid (VFP) to extract multi-scale visual features and a Text Feature Pyramid (TFP) to represent multi-granularity textual structures. These components are integrated through a Cross-modal Hierarchical Alignment (CHA) module, leveraging optimal transport to effectively align visual and textual features across various levels. Furthermore, we incorporate Relative Positional Encoding (RPE) into the decoder to model spatial and semantic relationships among tokens, enhancing the token-level alignment between visual features and generated text. Extensive experiments on two benchmark chest X-ray datasets, IU-Xray and MIMIC-CXR, demonstrate that RIHA outperforms existing state-of-the-art models in both natural language generation and clinical efficacy metrics.
### Title:
          ClipTBP: Clip-Pair based Temporal Boundary Prediction with Boundary-Aware Learning for Moment Retrieval
 - **Authors:** Ji-Hyeon Kim, Ho-Joong Kim, Seong-Whan Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video moment retrieval is the task of retrieving specific segments of a video corresponding to a given text query. Recent studies have been conducted to improve multimodal alignment performance through visual-linguistic similarity learning at the snippet-level and transformer-based temporal boundary regression. However, existing models do not calculate similarity by considering the relationships between multiple answer segments that match the query. Therefore, existing models are easily influenced by visually similar segments in the surrounding context. Existing models calculate similarity at the snippet-level and ignore the relationships between multiple answer segments corresponding to a single query. Therefore, they struggle to exclude segments irrelevant to the query. To address this issues, we propose ClipTBP, a clip-pair temporal boundary prediction framework based on boundary-aware learning. ClipTBP introduces a clip-level alignment loss for explicitly learning the semantic relationship between answer segments. ClipTBP also predicts accurate temporal boundaries by applying both main boundary loss and auxiliary boundary loss. ClipTBP consistently improves performance when applied to various existing models and demonstrates more robust boundary prediction performance even in ambiguous query scenarios.
### Title:
          ZAYAN: Disentangled Contrastive Transformer for Tabular Remote Sensing Data
 - **Authors:** Al Zadid Sultan Bin Habib, Tanpia Tasnim, Md. Ekramul Islam, Muntasir Tabasum
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning informative representations from tabular data in remote sensing and environmental science is challenging due to heterogeneity, scarce labels, and redundancy among features. We present ZAYAN (Zero-Anchor dYnamic feAture eNcoding), a self-supervised, feature-centric contrastive framework for tabular data. ZAYAN performs contrastive learning at the feature rather than sample level, removing the need for explicit anchor selection and any reliance on class labels, while encouraging a redundancy-minimized, disentangled embedding space. The framework has two modules: ZAYAN-CL, which pretrains feature embeddings via a zero-anchor contrastive objective with dynamic perturbations and masking, and ZAYAN-T, a Transformer that conditions on these embeddings for downstream classification. Across eight datasets, including six remote-sensing tabular benchmarks and two remote-sensing-driven flood-prediction tables from satellite and GIS products, ZAYAN achieves superior accuracy, robustness, and generalization over tabular deep learning baselines, with consistent gains under label scarcity and distribution shift. These results indicate that feature-level contrastive learning and dynamic feature encoding provide an effective recipe for learning from tabular sensing data.
### Title:
          MSR:Hybrid Field Modeling for CT-MRI Rigid-Deformable Registration of the Cervical Spine with an Annotated Dataset
 - **Authors:** Bohai Zhang, Wenjie Chen, Mu Li, Kaixing Long, Xing Shen, Xinqiang Yao, Jincheng Yang, Jianting Chen, Wei Yang, Qianjin Feng, Lei Cao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate CT-MRI registration of the cervical spine is essential for preoperative planning because this region is anatomically complex,highly variable,and vulnerable to injury of the vertebral arteries and spinal cord. However,cervical CT-MRI registration remains underexplored,particularly for rigid-deformable hybrid modeling,and the lack of high-quality annotated multimodal data further limits progress. To address these challenges, we construct and release a comprehensively annotated CT-MRI dataset, R-D-Reg, and propose MSR, a rigid-deformable hybrid registration framework for complex joint structures. Specifically, MSR includes a rigid registration module for independent local rigid alignment of individual vertebrae and a deformable registration module with an MSL block that combines Mamba-based global modeling and Swin Transformer-based local modeling through adaptive gating. The rigid and deformable deformation fields are then fused to generate a hybrid field that better preserves local anatomical consistency. The code and dataset are publicly available at this https URL.
### Title:
          RayFormer: Modeling Inter- and Intra-Ray Similarity for NeRF-Based Video Snapshot Compressive Imaging
 - **Authors:** Yubo Dong, Danhua Liu, Anqi Li, Zhenyuan Lin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video snapshot compressive imaging (SCI) enables the reconstruction of dynamic scenes from a single snapshot measurement. Recently, NeRF-based methods have shown promising reconstruction performance. However, such methods typically adopt random ray sampling strategies and fail to capture content structural similarities, resulting in limited reconstruction quality. To address these issues, we first propose a patch-level ray sampling strategy to enable the modeling of content structure. Then, we propose an Inter- and Intra-Ray Transformer (RayFormer) to capture the structural similarities, modeling both inter-ray similarities among spatially neighboring points at the same depth and intra-ray correlations between adjacent points along the viewing ray. Finally, benefiting from the patch-level sampling strategy, the total variation prior is incorporated into the objective function to enhance spatial smoothness and suppress artifacts. Experiments in both simulated and real-world scenes demonstrate that the proposed method achieves state-of-the-art (SOTA) reconstruction performance.
### Title:
          MotuBrain: An Advanced World Action Model for Robot Control
 - **Authors:** MotuBrain Team, Chendong Xiang, Fan Bao, Haitian Liu, Hengkai Tan, Hongzhe Bi, James Li, Jiabao Liu, Jingrui Pang, Kiro Jing, Louis Liu, Mengchen Cai, Rongxu Cui, Ruowen Zhao, Runqing Wang, Shuhe Huang, Yao Feng, Yinze Rong, Zeyuan Wang, Jun Zhu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models achieve strong semantic generalization but often lack fine-grained modeling of world dynamics. Recent work explores video generation models as a foundation for world modeling, leading to unified World Action Models (WAMs) that jointly model visual dynamics and actions. We present MotuBrain, a unified multimodal generative model that jointly models video and action under a UniDiffuser formulation with a three-stream Mixture-of-Transformers architecture. A single model supports multiple inference modes, including policy learning, world modeling, video generation, inverse dynamics, and joint video-action prediction, while scaling to heterogeneous multimodal data such as video-only and cross-embodiment robot data. To improve real-world applicability, MotuBrain introduces a unified multiview representation, explicit language-action coupling, and an efficient inference stack, achieving over 50x speedup for real-time deployment.
### Title:
          ZipCCL: Efficient Lossless Data Compression of Communication Collectives for Accelerating LLM Training
 - **Authors:** Wenxiang Lin, Xinglin Pan, Ruibo Fan, Shaohuai Shi, Xiaowen Chu
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Communication has emerged as a critical bottleneck in the distributed training of large language models (LLMs). While numerous approaches have been proposed to reduce communication overhead, the potential of lossless compression has remained largely underexplored since compression and decompression typically consume larger overheads than the benefits of reduced communication traffic. We observe that the communication data, including activations, gradients and parameters, during training often follows a near-Gaussian distribution, which is a key feature for data compression. Thus, we introduce ZipCCL, a lossless compressed communication library of collectives for LLM training. ZipCCL is equipped with our novel techniques: (1) theoretically grounded exponent coding that exploits the Gaussian distribution of LLM tensors to accelerate compression without expensive online statistics, (2) GPU-optimized compression and decompression kernels that carefully design memory access patterns and pipeline using communication-aware data layout, and (3) adaptive communication strategies that dynamically switch collective operations based on workload patterns and system characteristics. Evaluated on a 64-GPU cluster using both mixture-of-experts and dense transformer models, ZipCCL reduces communication time by up to 1.35$\times$ and achieves end-to-end training speedups of up to 1.18$\times$ without any impact on model quality.
### Title:
          Simulating clinical interventions with a generative multimodal model of human physiology
 - **Authors:** Guy Lutsker, Gal Sapir, Jordi Merino, Smadar Shilo, Anastasia Godneva, Eli Meirom, Shie Mannor, Hagai Rossman, Gal Chechik, Eran Segal
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding how human health changes over time, and why responses to interventions vary between individuals, remains a central challenge in medicine. Here we present HealthFormer, a decoder-only transformer that models the human physiological trajectory generatively, by training on data from the Human Phenotype Project, a multi-visit cohort of over 15,000 deeply phenotyped individuals. We tokenise each participant's health trajectory across 667 measurements spanning seven domains: blood biomarkers, body composition, sleep physiology, continuous glucose monitoring, gut microbiome, wearable-derived physiology, and behaviour and medication exposure. We train HealthFormer to forecast individual physiological trajectories across these domains, and from this single generative objective a range of clinically relevant tasks can be expressed as queries on the model. We show that, without task-specific training, HealthFormer transfers to four independent cohorts and improves prediction for 27 of 30 incident-disease and mortality endpoints, exceeding established clinical risk scores in every comparison. We further show that the model can simulate interventions in silico: in a held-out personalised-nutrition trial, intervention-conditioned predictions recover individual six-month biomarker changes (e.g., Pearson r = 0.78 for diastolic blood pressure). Across 41 randomised intervention-outcome comparisons drawn from published trials, our results show that the predicted direction of effect agrees in every case, and the predicted mean falls within the reported 95% confidence interval in 30 cases. We position HealthFormer as an initial health world model, from which forecasting, risk stratification, and intervention-conditioned simulation arise as queries, providing a basis for clinical digital twins.
### Title:
          Taming the Centaur(s) with LAPITHS: a framework for a theoretically grounded interpretation of AI performances
 - **Authors:** Matteo Da Pelo, Alessio Donvito, Claudio Frongia, Pietro Salis, Antonio Lieto
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce a framework called LAPITHS (Language model Analysis through Paradigm grounded Interpretations of Theses about Human likenesS) and use it to show that several major claims advanced by models such as CENTAUR, proposed as an artificial Unified Model of Cognition, are not theoretically or empirically justified. LAPITHS provides a principled reference point for counteracting the current behaviouristic tendency in AI research to interpret the human level performances of transformer based language models as evidence of human like underlying computation and, by extension, as signs of cognitive abilities. The novelty of LAPITHS lies in making explicit the arguments grounded in two quantitative assessments: (i) the Minimal Cognitive Grid, a theoretically motivated method for estimating the cognitive plausibility of artificial systems, and (ii) a behavioural comparison showing that results similar to those reported for CENTAUR like models can be reproduced by other systems that do not satisfy the structural constraints typically associated with cognitive plausibility, and whose outputs do not provide independent explanatory insight into human cognition.
### Title:
          TripVVT: A Large-Scale Triplet Dataset and a Coarse-Mask Baseline for In-the-Wild Video Virtual Try-On
 - **Authors:** Dingbao Shao, Song Wu, Shenyi Wang, Ye Wang, Ziheng Tang, Fei Liu, Jiang Lin, Xinyu Chen, Qian Wang, Ying Tai, Jian Yang, Zili Yi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Due to the scarcity of large-scale in-the-wild triplet data and the improper use of masks, the performance of video virtual try-on models remains limited. In this paper, we first introduce **TripVVT-10K**, the largest and most diverse in-the-wild triplet dataset to date, providing explicit video-level cross-garment supervision that existing video datasets lack. Built upon this resource, we develop **TripVVT**, a Diffusion Transformer-based framework that replaces fragile garment masks with a simple, stable human-mask prior, enabling reliable background preservation while remaining robust to real-world motion, occlusion, and cluttered scenes. To support comprehensive evaluation, we further establish **TripVVT-Bench**, a 100-case benchmark covering diverse garments, complex environments, and multi-person scenarios, with metrics spanning video quality, try-on fidelity, background consistency, and temporal coherence. Compared to state-of-the-art academic and commercial systems, TripVVT achieves superior video quality and garment fidelity while markedly improving generalization to challenging in-the-wild videos. We publicly release the dataset and benchmark, which we believe provide a solid foundation for advancing controllable, realistic, and temporally stable video virtual try-on.
### Title:
          ITS-Mina: A Harris Hawks Optimization-Based All-MLP Framework with Iterative Refinement and External Attention for Multivariate Time Series Forecasting
 - **Authors:** Pourya Zamanvaziri, Amirhossein Sadr, Aida Pakniyat, Dara Rahmati
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multivariate time series forecasting plays a pivotal role in numerous real-world applications, including financial analysis, energy management, and traffic planning. While Transformer-based architectures have gained popularity for this task, recent studies reveal that simpler MLP-based models can achieve competitive or superior performance with significantly reduced computational cost. In this paper, we propose ITS-Mina, a novel all-MLP framework for multivariate time series forecasting that integrates three key innovations: (1) an iterative refinement mechanism that progressively enhances temporal representations by repeatedly applying a shared-parameter residual mixer stack, effectively deepening the model's computational capacity without multiplying the number of distinct parameters; (2) an external attention module that replaces traditional self-attention with learnable memory units, capturing cross-sample global dependencies at linear computational complexity; and (3) a Harris Hawks Optimization (HHO) algorithm for automatic dropout rate tuning, enabling adaptive regularization tailored to each dataset. Extensive experiments on six widely-used benchmark datasets demonstrate that ITS-Mina achieves state-of-the-art or highly competitive performance compared to eleven baseline models across multiple forecasting horizons.
### Title:
          PROMISE-AD: Progression-aware Multi-horizon Survival Estimation for Alzheimer's Disease Progression and Dynamic Tracking
 - **Authors:** Qing Lyu, Jeremy Hudson, Mohammad Kawas, Yuming Jiang, Chenyu You, Christopher T Whitlow
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Individualized Alzheimer's disease (AD) progression prediction requires models that use irregular visits, account for censoring, avoid diagnostic leakage, and provide calibrated horizon risks. We propose PROgression-aware MultI-horizon Survival Estimation for Alzheimer's Disease (PROMISE-AD), a leakage-safe survival framework for predicting conversion from cognitively normal (CN) to mild cognitive impairment (MCI) and from MCI to AD dementia using ADNI/TADPOLE tabular histories. PROMISE-AD converts pre-index visits into tokens with standardized measurements, missingness masks, longitudinal changes, time-normalized slopes, visit timing, and non-diagnostic categorical attributes. A temporal Transformer fuses global, attention-pooled, and latest-visit representations to estimate a progression score and latent discrete-time mixture hazards. Training combines survival likelihood, horizon-specific focal risk loss, progression ranking, hazard smoothness, and mixture-balance regularization, followed by validation-set isotonic calibration for 1-, 2-, 3-, and 5-year risks. In held-out testing across three seeds, PROMISE-AD achieved an integrated Brier score (IBS) of 0.085 $\pm$ 0.012, C-index of 0.808 $\pm$ 0.015, and mean time-dependent AUC of 0.840 $\pm$ 0.081 for CN-to-MCI conversion, yielding the lowest IBS among compared methods. For MCI-to-AD conversion, PROMISE-AD achieved the highest C-index (0.894 $\pm$ 0.018) and near-ceiling 5-year discrimination (AUROC 0.997 $\pm$ 0.003; AUPRC 0.999 $\pm$ 0.001), although some baselines had lower IBS. Ablations and interpretability supported longitudinal change features, fused temporal representations, mixture hazards, cognitive and functional measures, APOE4 status, and recent conversion-proximal visits. These findings suggest that progression-aware survival modeling can provide interpretable multi-horizon AD conversion risk estimates.
### Title:
          FiLMMeD: Feature-wise Linear Modulation for Cross-Problem Multi-Depot Vehicle Routing
 - **Authors:** Arthur Corrêa, Paulo Nascimento, Samuel Moniz
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Solving practical multi-depot vehicle routing problems (MDVRP) is a challenging optimization task central to modern logistics, increasingly driven by e-commerce. To address the MDVRP's computational complexity, neural-based combinatorial optimization methods offer a promising scalable alternative to traditional approaches. However, neural-based methods typically rely on rigid architectures and input encodings tailored to specific problem formulations. In real-world settings, heterogeneous constraints create multiple MDVRP variants, limiting the applicability of such models. While multi-task learning (MTL) has begun to accelerate the development of unified neural-based solvers, prior works focus almost exclusively on single-depot VRPs, leaving the MDVRP unaddressed. To bridge this gap, we propose Feature-wise Linear Modulation for Cross-Problem Multi-Depot Vehicle Routing (FiLMMeD), a novel unified neural-based model for 24 different MDVRP variants. We introduce three main contributions: (1) to improve the model's generalization, we augment the standard Transformer encoder with Feature-wise Linear Modulation (FiLM), which dynamically conditions learned internal representations based on the active set of constraints; (2) we provide an initial demonstration of Preference Optimization in the MTL setting, establishing it as a superior alternative to Reinforcement Learning for future MTL works; (3) to mitigate the generalization gap caused by the introduction of multi-depot constraints, we introduce a targeted curriculum learning strategy that progressively exposes the model to increasingly more complex constraint interactions. Extensive experiments on 24 MDVRP variants (including 8 novel formulations) and 16 single-depot VRPs confirm the effectiveness of FiLMMeD, which consistently outperforms state-of-the-art baselines. Our code is available at: this https URL
### Title:
          DEFault++: Automated Fault Detection, Categorization, and Diagnosis for Transformer Architectures
 - **Authors:** Sigma Jahan, Saurabh Singh Rajput, Tushar Sharma, Mohammad Masudur Rahman
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer models are widely deployed in critical AI applications, yet faults in their attention mechanisms, projections, and other internal components often degrade behavior silently without raising runtime errors. Existing fault diagnosis techniques often target generic deep neural networks and cannot identify which transformer component is responsible for an observed symptom. In this article, we present DEFault++, a hierarchical learning-based diagnostic technique that operates at three level of abstraction: it detects whether a fault is present, classifies it into one of 12 transformer-specific fault categories (covering both attention-internal mechanisms and surrounding architectural components), and identifies the underlying root cause from up to 45 mechanisms. To facilitate both training and evaluation, we construct DEFault-bench, a benchmark of 3,739 labeled instances obtained through systematic mutation testing. These instances are created across seven transformer models and nine downstream tasks using DEForm, a transformer-specific mutation technique we developed for this purpose. DEFault++ measures runtime behavior at the level of individual transformer components. It organizes these measurements through a Fault Propagation Graph (FPG) derived from the transformer architecture. It then produces an interpretable diagnosis using prototype matching combined with supervised contrastive learning. On DEFault-bench, DEFault++ exceeds an AUROC of 0.96 for detection and a Macro-F1 of 0.85 for both categorization and root-cause diagnosis on encoder and decoder architectures. In a developer study with 21 practitioners, the accuracy of choosing correct repair actions increased from 57.1% without support to 83.3% when using DEFault++.
### Title:
          Beyond Gaussian Bottlenecks: Topologically Aligned Encoding of Vision-Transformer Feature Spaces
 - **Authors:** Andrew Bond, Ilkin Umut Melanlioglu, Erkut Erdem, Aykut Erdem
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern visual world modeling systems increasingly rely on high-capacity architectures and large-scale data to produce plausible motion, yet they often fail to preserve underlying 3D geometry or physically consistent camera dynamics. A key limitation lies not only in model capacity, but in the latent representations used to encode geometric structure. We propose S$^2$VAE, a geometry-first latent learning framework that focuses on compressing and representing the latent 3D state of a scene, including camera motion, depth, and point-level structure, rather than modeling appearance alone. Building on representations from a Visual Geometry Grounded Transformer (VGGT), we introduce a novel type of variational autoencoder using a product of Power Spherical latent distributions, explicitly enforcing hyperspherical structure in the bottleneck to preserve directional and geometric semantics under strong compression. Across depth estimation, camera pose recovery, and point cloud reconstruction, we show that geometry-aligned hyperspherical latents consistently outperform conventional Gaussian bottlenecks, particularly in high-compression regimes. Our results highlight latent geometry as a first-class design choice for physically grounded visual and world models.
### Title:
          Explainable Load Forecasting with Covariate-Informed Time Series Foundation Models
 - **Authors:** Matthias Hertel, Alexandra Nikoltchovska, Sebastian Pütz, Ralf Mikut, Benjamin Schäfer, Veit Hagenmeyer
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Time Series Foundation Models (TSFMs) have recently emerged as general-purpose forecasting models and show considerable potential for applications in energy systems. However, applications in critical infrastructure like power grids require transparency to ensure trust and reliability and cannot rely on pure black-box models. To enhance the transparency of TSFMs, we propose an efficient algorithm for computing Shapley Additive Explanations (SHAP) tailored to these models. The proposed approach leverages the flexibility of TSFMs with respect to input context length and provided covariates. This property enables efficient temporal and covariate masking (selectively withholding inputs), allowing for a scalable explanation of model predictions using SHAP. We evaluate two TSFMs - Chronos-2 and TabPFN-TS - on a day-ahead load forecasting task for a transmission system operator (TSO). In a zero-shot setting, both models achieve predictive performance competitive with a Transformer model trained specifically on multiple years of TSO data. The explanations obtained through our proposed approach align with established domain knowledge, particularly as the TSFMs appropriately use weather and calendar information for load prediction. Overall, we demonstrate that TSFMs can serve as transparent and reliable tools for operational energy forecasting.
### Title:
          Action Motifs: Self-Supervised Hierarchical Representation of Human Body Movements
 - **Authors:** Genki Kinoshita, Shu Nakamura, Ryo Kawahara, Shohei Nobuhara, Yasutomo Kawanishi, Ko Nishino
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Effective human behavior modeling requires a representation of the human body movement that capitalizes on its compositionality. We propose a hierarchical representation consisting of Action Atoms that capture the atomic joint movements and Action Motifs that are formed by their temporal compositions and encode similar body movements found across different overall human actions. We derive A4Mer, a nested latent Transformer to learn this hierarchical representation from human pose data in a fully self-supervised manner. A4Mer splits a 3D pose sequence into variable-length segments and represents each segment as a single latent token (Action Atoms). Through bottom-up representation learning, temporal patterns composed of these Action Atoms, which capture meaningful temporal spans of reusable, semantic segments of body movements, naturally emerge (Action Motifs). A4Mer achieves this with a unified pretext task of masked token prediction in their respective latent spaces. We also introduce Action Motif Dataset (AMD), a large-scale dataset of multi-view human behavior videos with full SMPL annotations. We introduce a novel use of cameras by mounting them on the feet to achieve their frame-wise annotations despite frequent and heavy body occlusions. Experimental results demonstrate the effectiveness of A4Mer for extracting meaningful Action Motifs, which significantly benefit human behavior modeling tasks including action recognition, motion prediction, and motion interpolation.
### Title:
          LLM as Clinical Graph Structure Refiner: Enhancing Representation Learning in EEG Seizure Diagnosis
 - **Authors:** Lincan Li, Zheng Chen, Yushun Dong
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Electroencephalogram (EEG) signals are vital for automated seizure detection, but their inherent noise makes robust representation learning challenging. Existing graph construction methods, whether correlation-based or learning-based, often generate redundant or irrelevant edges due to the noisy nature of EEG data. This significantly impairs the quality of graph representation and limits downstream task performance. Motivated by the remarkable reasoning and contextual understanding capabilities of large language models (LLMs), we explore the idea of using LLMs as graph edge refiners. Specifically, we propose a two-stage framework: we first verify that LLM-based edge refinement can effectively identify and remove redundant connections, leading to significant improvements in seizure detection accuracy and more meaningful graph structures. Building on this insight, we further develop a robust solution where the initial graph is constructed using a Transformer-based edge predictor and multilayer perceptron, assigning probability scores to potential edges and applying a threshold to determine their existence. The LLM then acts as an edge set refiner, making informed decisions based on both textual and statistical features of node pairs to validate the remaining connections. Extensive experiments on TUSZ dataset demonstrate that our LLM-refined graph learning framework not only enhances task performance but also yields cleaner and more interpretable graph representations.
## Keyword: autonomous driving
### Title:
          Judge, Then Drive: A Critic-Centric Vision Language Action Framework for Autonomous Driving
 - **Authors:** Lijin Yang, Jianing Huang, Zhongzhan Huang, Shu Liu, Hao Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in vision language action (VLA) models have shown remarkable potential for autonomous driving by directly mapping multimodal inputs to control signals. However, previous VLA-based methods have not explicitly exploited the critic capability of VLAs to refine driving decisions, even though such capability has been well demonstrated in other LLM-based domains, thereby limiting their performance in complex closed-loop scenarios. In this work, we present a theoretically inspired two-stage framework, CriticVLA, which extends the role of VLAs from acting to judging. CriticVLA first generates a rough trajectory and then refines it through multimodal evaluation and single-step optimization guided by a VLA-based critic, yielding higher-quality driving behaviors. To support this process, we construct a large-scale synthetic dataset of 12.9 million annotated trajectories covering diverse driving scenarios, which enhances the critic's reasoning and refinement abilities. Extensive closed-loop experiments on the Bench2Drive benchmark show that CriticVLA significantly surpasses state-of-the-art baselines, achieving a 73.33% total success rate and delivering about 30% improvement in challenging scenarios.
### Title:
          Understanding Adversarial Transferability in Vision-Language Models for Autonomous Driving: A Cross-Architecture Analysis
 - **Authors:** David Fernandez, Pedram MohajerAnsari, Amir Salarpour, Mert D. Pese
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Cryptography and Security (cs.CR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language models (VLMs) are increasingly used in autonomous driving because they combine visual perception with language-based reasoning, supporting more interpretable decision-making, yet their robustness to physical adversarial attacks, especially whether such attacks transfer across different VLM architectures, is not well understood and poses a practical risk when attackers do not know which model a vehicle uses. We address this gap with a systematic cross-architecture study of adversarial transferability in VLM-based driving, evaluating three representative architectures (Dolphins, OmniDrive, and LeapVAD) using physically realizable patches placed on roadside infrastructure in both crosswalk and highway scenarios. Our transfer-matrix evaluation shows high cross-architecture effectiveness, with transfer rates of 73-91% (mean TR = 0.815 for crosswalk and 0.833 for highway) and sustained frame-level manipulation over 64.7-79.4% of the critical decision window even when patches are not optimized for the target model.
### Title:
          Towards All-Day Perception for Off-Road Driving: A Large-Scale Multispectral Dataset and Comprehensive Benchmark
 - **Authors:** Shuo Wang, Jilin Mei, Wenfei Guan, Shuai Wang, Yan Xing, Chen Min, Yu Hu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Off-road nighttime autonomous driving suffers from unreliable visible-light perception, making infrared modality crucial for accurate freespace detection. However, progress remains limited due to the scarcity of annotated infrared off-road datasets and the inter-frame inconsistencies inherent to current single-frame methods. To address these gaps, we present the IRON dataset, which, to our knowledge, is the first large-scale infrared dataset for off-road temporal freespace detection under all-day conditions, with strong support for nighttime perception. The dataset comprises 24,314 densely annotated infrared images with synchronized RGB images in diverse scenes and different light conditions. Building upon this dataset, we propose IRONet, a novel flow-free framework for temporal freespace detection that addresses inter-frame inconsistencies by aggregating historical context via a memory-attention mechanism and a carefully designed mask decoder. On our IRON dataset, IRONet achieves state-of-the-art performance, reaching 82.93%(+1.19%) IoU and 90.66%(+0.71%) F1 score at real-time inference. Remarkably, IRONet also exhibits robust generalization to RGB modalities on ORFD and Rellis datasets. Overall, our work establishes a foundation for reliable all-day off-road autonomous driving and future research in infrared temporal perception. The code and IRON dataset are available at this https URL.
### Title:
          Towards Neuro-symbolic Causal Rule Synthesis, Verification, and Evaluation Grounded in Legal and Safety Principles
 - **Authors:** Zainab Rehan, Christian Medeiros Adriano, Sona Ghahremani, Holger Giese
 - **Subjects:** Subjects:
Logic in Computer Science (cs.LO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rule-based systems remain central in safety-critical domains but often struggle with scalability, brittleness, and goal misspecification. These limitations can lead to reward hacking and failures in formal verification, as AI systems tend to optimize for narrow objectives. In previous research, we developed a neuro-symbolic causal framework that integrates first-order logic abduction trees, structural causal models, and deep reinforcement learning within a MAPE-K loop to provide explainable adaptations under distribution shifts. In this paper, we extend that framework by introducing a meta-level layer designed to mitigate goal misspecification and support scalable rule maintenance. This layer consists of a Goal/Rule Synthesizer and a Rule Verification Engine, which iteratively refine a formal rule theory from high-level natural-language goals and principles provided by human experts. The synthesis pipeline employs large language models (LLMs) to: (1) decompose goals into candidate causes, (2) consolidate semantics to remove redundancies, (3) translate them into candidate first-order rules, and (4) compose necessary and sufficient causal sets. The verification pipeline then performs (1) syntax and schema validation, (2) logical consistency analysis, and (3) safety and invariant checks before integrating verified rules into the knowledge base. We evaluated our approach with a proof-of-concept implementation in two autonomous driving scenarios. Results indicate that, given human-specified goals and principles, the pipeline can successfully derive minimal necessary and sufficient rule sets and formalize them as logical constraints. These findings suggest that the pipeline supports incremental, modular, and traceable rule synthesis grounded in established legal and safety principles.
### Title:
          GSDrive: Reinforcing Driving Policies by Multi-mode Trajectory Probing with 3D Gaussian Splatting Environment
 - **Authors:** Ziang Guo, Min Chen, Xuefeng Zhang, Yixiao Zhou, Zufeng Zhang, Dzmitry Tsetserukou
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end (E2E) autonomous driving presents a promising approach for translating perceptual inputs directly into driving actions. However, prohibitive annotation costs and temporal data quality degradation hinder long-term real-world deployment. While combining imitation learning (IL) and reinforcement learning (RL) is a common strategy for policy improvement, conventional RL training relies on delayed, event-based rewards-policies learn only from catastrophic outcomes such as collisions, leading to premature convergence to suboptimal behaviors. To address these limitations, we introduce GSDrive, a framework that exploits 3D Gaussian Splatting (3DGS) for differentiable, physics-based reward shaping in E2E driving policy improvement. Our method incorporates a flow matching-based trajectory predictor within the 3DGS simulator, enabling multi-mode trajectory probing where candidate trajectories are rolled out to assess prospective rewards. This establishes a bidirectional knowledge exchange between IL and RL by grounding reward functions in physically simulated interaction signals, offering immediate dense feedback instead of sparse catastrophic events. Evaluated on the reconstructed nuScenes dataset, our method surpasses existing simulation-based RL driving approaches in closed-loop experiments. Code is available at this https URL.
### Title:
          HERMES++: Toward a Unified Driving World Model for 3D Scene Understanding and Generation
 - **Authors:** Xin Zhou, Dingkang Liang, Xiwu Chen, Feiyang Tan, Dingyuan Zhang, Hengshuang Zhao, Xiang Bai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Driving world models serve as a pivotal technology for autonomous driving by simulating environmental dynamics. However, existing approaches predominantly focus on future scene generation, often overlooking comprehensive 3D scene understanding. Conversely, while Large Language Models (LLMs) demonstrate impressive reasoning capabilities, they lack the capacity to predict future geometric evolution, creating a significant disparity between semantic interpretation and physical simulation. To bridge this gap, we propose HERMES++, a unified driving world model that integrates 3D scene understanding and future geometry prediction within a single framework. Our approach addresses the distinct requirements of these tasks through synergistic designs. First, a BEV representation consolidates multi-view spatial information into a structure compatible with LLMs. Second, we introduce LLM-enhanced world queries to facilitate knowledge transfer from the understanding branch. Third, a Current-to-Future Link is designed to bridge the temporal gap, conditioning geometric evolution on semantic context. Finally, to enforce structural integrity, we employ a Joint Geometric Optimization strategy that integrates explicit geometric constraints with implicit latent regularization to align internal representations with geometry-aware priors. Extensive evaluations on multiple benchmarks validate the effectiveness of our method. HERMES++ achieves strong performance, outperforming specialist approaches in both future point cloud prediction and 3D scene understanding tasks. The model and code will be publicly released at this https URL.
