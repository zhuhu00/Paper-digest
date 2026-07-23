# Showing new listings for Thursday, 23 July 2026
## Keyword: SLAM
### Title:
          HalluTruthQA: A Fine-Grained Benchmark for Hallucination Detection, Localization, and Explanation in Arabic Question Answering
 - **Authors:** Abdessalam Bouchekif, Mohammed-En-Nadhir Zighem, Salah Eddine Bekhouche, Hichem Telli, Somaya Eltanbouly, Shahd Gaben, Heba Sbahi, Samer Rashwani, Mutaz Al-Khatib, Emad Mohamed, Mohammed Ghaly, Abdenour Hadid
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) can generate fluent Arabic answers, yet factual errors remain difficult to detect, localize, explain, and verify. Existing hallucination benchmarks often provide response-level labels, with limited support for identifying the exact erroneous content, explaining why it is incorrect, or selecting the correct factual answer. We introduce \textsc{HalluTruthQA}, a fine-grained benchmark for hallucination evaluation in Arabic question answering. The benchmark contains 2,400 expert-curated examples across four knowledge-intensive domains: Islamic knowledge, history, science, and geography. Each example pairs an Arabic question and a model-generated answer with a verified reference answer, a binary hallucination label, six candidate answers for factual verification, and, for hallucinated answers, character-level erroneous spans, human-written explanations, and macro and micro hallucination types. We evaluate four open-source LLMs, \textsc{Allam}, \textsc{Falcon-H1}, \textsc{Qwen32}, and \textsc{Silma}, in a zero-shot setting across hallucination detection, span-level localization, factual verification, and explanation evaluation. Results show that these tasks capture different abilities: no single model achieves the strongest performance across all tasks, with best scores of 0.880 Macro-F1 for detection, 0.516 F1-Sp for localization, 0.852 LO-Score for factual verification, and 0.644 final score for explanation evaluation. Our taxonomy shows that hallucination evaluation should move beyond detection toward localizing, verifying, and explaining factual errors. The code, dataset, prompts, and evaluation scripts are available at this https URL.
### Title:
          DINS-IO: Learned Inertial Odometry via Differentiable INS Consistency
 - **Authors:** Hao Qiao, Yan Wang, Jian Kuang, Xiaoji Niu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The training of learned inertial odometry depends on dense, high-precision position ground truth from motion capture, visual-inertial odometry or SLAM, which is costly and hard to acquire at scale. We propose DINS-IO, which learns inertial odometry directly from raw IMU streams without position labels. Our key insight is that the strapdown INS velocity recursion is a strong, fully differentiable consistency prior: the predicted velocity, rotated into the navigation frame, must agree with the integrated specific force up to an unknown initial velocity and a constant accelerometer bias. We cast this constraint as a sliding-window least-squares problem with a globally shared bias, solve it in closed form, and use the solver residual as a self-supervised loss whose gradient flows back to the network through the analytic solution. To supply this per-sample constraint, we design a high-frequency network that emits dense body-frame velocity at the IMU rate. Since the self-supervised network learns consistent motion but its velocity is not yet metrically calibrated, we calibrate it to true metric velocity from a few labeled trajectories by directly supervising the predicted body-frame velocity and adapting only low-rank (LoRA) patches. On standard benchmarks, DINS-IO pretrained self-supervised and fine-tuned with a small fraction of labels matches or surpasses fully supervised baselines.
## Keyword: odometry
### Title:
          DINS-IO: Learned Inertial Odometry via Differentiable INS Consistency
 - **Authors:** Hao Qiao, Yan Wang, Jian Kuang, Xiaoji Niu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The training of learned inertial odometry depends on dense, high-precision position ground truth from motion capture, visual-inertial odometry or SLAM, which is costly and hard to acquire at scale. We propose DINS-IO, which learns inertial odometry directly from raw IMU streams without position labels. Our key insight is that the strapdown INS velocity recursion is a strong, fully differentiable consistency prior: the predicted velocity, rotated into the navigation frame, must agree with the integrated specific force up to an unknown initial velocity and a constant accelerometer bias. We cast this constraint as a sliding-window least-squares problem with a globally shared bias, solve it in closed form, and use the solver residual as a self-supervised loss whose gradient flows back to the network through the analytic solution. To supply this per-sample constraint, we design a high-frequency network that emits dense body-frame velocity at the IMU rate. Since the self-supervised network learns consistent motion but its velocity is not yet metrically calibrated, we calibrate it to true metric velocity from a few labeled trajectories by directly supervising the predicted body-frame velocity and adapting only low-rank (LoRA) patches. On standard benchmarks, DINS-IO pretrained self-supervised and fine-tuned with a small fraction of labels matches or surpasses fully supervised baselines.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          D3VL: Understanding Driving Scenes from 3D Time Series Data and Video with Language Models
 - **Authors:** Heesang Han, A. Lynn Abbott, Abhijit Sarkar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in Multimodal Large Language Models (MLLMs) have triggered the development of end-to-end MLLMs for autonomous driving. However, the main emphasis to date has been for MLLMs using 2D images and videos. In contrast, this paper considers MLLM effectiveness using 3D sensors, particularly LiDAR and stereo cameras. LiDAR presents unique challenges to integration within an MLLM, largely because of data sparsity and lack of a grid structure for the data. For similar reasons, fusion of camera and LiDAR data within an MLLM pipeline is also uncommon. However, most autonomous systems rely on LiDAR-based sensing, and incorporating 3D data has been proven to improve performance in traditional 3D scene perception tasks. This paper presents D3VL, a novel MLLM framework that integrates 2D and 3D time-series data in a single but simple architecture. The model aims to answer questions involving traffic scene understanding and safety. D3VL shows an 11% improvement in the KITTI Question-Answering (QA) dataset compared to baseline methods in processing 2D and 3D time-series data. This paper further introduces the Waymo QA dataset extension, which assesses models' capabilities in processing 3D and time-series data under diverse driving conditions. D3VL implementation code and WaymoQA extension can be found on our supplemental website: this https URL
### Title:
          Koopman Dreamer: Spectrally Constrained Latent Dynamics for Stable World-Model Imagination
 - **Authors:** Jiaqi Li, Xinglong Zhang, Haibin Xie, Yixing Lan, Wei Pan, Xin Xu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Latent world models improve sample efficiency in continuous control by optimizing policies over imagined latent trajectories, but common neural transitions offer limited direct control over modal persistence and error accumulation in long rollouts. We propose Koopman Dreamer, a Dreamer-style world model with a spectrally constrained deterministic latent dynamics core. Its Koopman-inspired backbone uses two-dimensional rotation--scaling blocks with bounded radii to represent damping, rotation, and near-periodic modes. Linear and low-rank bilinear action terms capture global and state-dependent control effects, while stochastic-state modulation supplies local correction information. To reduce the mismatch between posterior-conditioned training and prior-only imagination, the model combines posterior-conditioned EMA teacher targets with one-step consistency, multi-step rollout, and open-loop observation-prediction objectives. We further derive a multi-step rollout-error bound that separates amplification by the spectral backbone and bilinear interaction from the additive effects of stochastic-state mismatch and modeling residuals, clarifying the trade-off between error attenuation and long-term information retention. Experimental results on proprioceptive continuous-control tasks from the DeepMind Control Suite and UAV-LiDAR autonomous navigation demonstrate that Koopman Dreamer improves the stability of long-horizon latent rollouts and achieves stronger closed-loop control performance on tasks that rely on high-quality multi-step imagination.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          Lifted Representation Hypothesis in Language Models
 - **Authors:** Bumjin Park, Jaesik Choi
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) often answer queries by mapping individual observations to more general rule-like structures. However, it remains unclear how these structures are stored, selected, and revised. To study this process, we propose thelifted representation hypothesis: LLMs update memory through shared latent structures rather than isolated instance-level facts. This view frames lifting as an efficient use of symmetry across instances, and shattering as the refinement of coarse lifted structures into more specific subtypes. We evaluate LLMs' lifting and shattering through controlled exception-learning experiments across in-context learning, LoRA, and full fine-tuning. We find that LLMs are vulnerable to shattering failures when data are governed by nested rules and exceptions, while lifting often occurs prematurely. These results highlight the need to study the relation between data and rule structures in LLMs.
### Title:
          Euclean: Automated Geometry Problem Formalization with Unified Verification in Lean
 - **Authors:** Linbin Tang, Jingyan You, Zilin Kang, Hanzhang Liu, Sophia Zhang, Zenan Li, Chenrui Cao, Liangcheng Song, Jiaao Wu, Xian Zhang, Fan Yang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent formal reasoning systems have reached IMO-level performance, yet they leave a fragmented landscape: algebra and number theory are handled in Lean, while geometry still relies on domain-specific languages with limited formal guarantees. This split increases the trusted computing base and hinders unified model development. Existing geometry-in-Lean efforts (LeanEuclid, LeanGeo) introduce custom axiom systems incompatible with standard Mathlib, and their small scale ($<$ 1,100 problems) limits large-scale training. Native Mathlib autoformalization of geometry, however, poses distinct challenges: implicit diagrammatic assumptions (e.g., topological configuration and non-degeneracy) must be made explicit rather than deferred to external solvers, and models must adapt to Mathlib's small, rapidly evolving geometry infrastructure. We present Euclean, a four-stage framework - constraint explication, configuration anchoring, formalization mapping, and iterative repair - for automatically formalizing geometry in native Mathlib. We construct OMNI-Geometry (768 competition problems) and Numina-Geometry (177,597 problems), the largest geometry formalization dataset in Lean. Human evaluation shows 48.89% TOP1 and 73.33% TOP5 accuracy. Training Goedel v2 on our formalizations improves proof success from 13.6% to 15.1%, validating dataset quality for unified neural theorem proving. Code and datasets: this https URL.
### Title:
          Predicting Groundwater Arsenic Concentrations Using Graph Neural Networks
 - **Authors:** William Xing, Stephanie Yang, Aarush Bandemegal, Anushree Misra, Ananya Kalapatapu, Brennan Lagasse, Kevin Zhu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Arsenic contamination in groundwater presents a longstanding public health crisis in the United States, especially for households depending on private wells. Accurate and spatially informed prediction of arsenic concentration is vital to identify high-risk areas and focus mitigation efforts. However, there is a lack of generalizable models for representing continuous variation in arsenic concentrations across regions. In this work, we pose arsenic prediction as a regression task and construct a spatially integrated dataset to aggregate over 74,000 arsenic samples from the Water Quality Portal (WQP), Mineral Resources Data System (MRDS), and Gridded National Soil Survey Geographic Database (gNATSGO). Specifically, we use a variety of techniques including kNearest Neighbors (k-NN) and Geographic Information Systems (GIS) to join arsenic measurement points from across the United States by location. Building on this dataset, we evaluate a diverse suite of machine learning models, including tree-based ensemble approaches, multilayer perceptrons, and spatially aware graph neural networks (GNN). Our findings show that while gradient-boosted trees are still considered state-of-the-art in the field of tabular data, GNNs are able to further account for spatial dependence to match or outperform the results of gradient-boosted trees. These results demonstrate that graph-based and spatially informed learning can enhance environmental prediction and provide a foundation for improved groundwater risk mapping and monitoring.
### Title:
          Cross-Subject Semantic Decoding with Shared-Space Alignment for Generalized Neural Representation Learning
 - **Authors:** Ji-Hoon Heo, Aleksandra Joanna Wisniewska, Seo-Hyun Lee, Seong-Whan Lee
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generalizing across subjects remains challenging in invasive neural recordings because electrode configurations, anatomical structures, and neural signal patterns vary substantially across individuals. To investigate such inter-subject variability, we propose a cross-subject semantic decoding framework that aligns neural responses to speech perception from multiple subjects into a shared latent space and learns a mapping from the aligned neural representations to contextual embeddings. More specifically, using electrocorticography data collected during natural language comprehension, we estimate the shared space using the shared response model and train a decoder to predict contextual semantic embeddings from projected neural responses. For a held-out subject, we estimate a subject-specific projection into the predefined shared space, and directly apply the pretrained decoder without any retraining. Experimental results demonstrate that the proposed framework consistently outperforms baseline methods across evaluation settings and exhibits a reduced performance drop from source subject to held-out subject testing, indicating improved cross-subject generalization. These results suggest that aligning neural activity into a shared latent space, while decoding in a semantic embedding space, provides an effective strategy for improving cross-subject generalization by reducing subject-specific differences in neural responses while effectively capturing shared stimulus-related representations.
### Title:
          Structured Latent Space Modeling over Multi-Scale Temporal Patches for Multivariate Time Series Forecasting
 - **Authors:** Xingsheng Chen, Deyu Yi, Siu-Ming Yiu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multivariate time series encode structural patterns that unfold across multiple temporal scales, yet most forecasting backbones treat learned representations as transient byproducts of prediction, leaving the organizational geometry of these patterns underexploited. We introduce M2Patch, a CNN-based forecasting architecture that maps channel-independent multivariate observations into a structured latent space through two complementary differentiable constraints. Multi-scale patching decomposes the input into overlapping temporal granularities; depthwise separable convolutions with progressive dilation extract scale-specific features in linear time; and per-scale learned projections compress these features into a compact latent representation. The latent space is organized by an intra-scale smoothness constraint that enforces temporal continuity between adjacent patches, and an inter-scale alignment constraint, realized through learnable cross-scale mappings, that restores cross-granularity interaction within the channel-independent design, ensuring that all scales encode mutually consistent representations of the underlying dynamics. Experiments on ten real-world benchmarks show that M2Patch achieves 57 best and 34 second-best results across 40 forecasting settings, matching or exceeding representative baselines on most benchmarks while maintaining linear computational complexity and robustness to patch-level input corruption.
### Title:
          LowPowAR: Power-Constrained Tone Mapping for Augmented Reality
 - **Authors:** Weikai Lin, Sheng Zhao, Ian Ross, Carl Marshall, Sushant Kondguli, Yuhao Zhu
 - **Subjects:** Subjects:
Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Everyday-wearable Augmented Reality (AR) glasses must meet strict power limits, making displays a key target for optimization. We cast display power optimization as a power-constrained tone-mapping problem and propose a human-vision-grounded, learning-based framework that maximizes perceptual quality under a given power budget. We introduce an optimization-friendly tone-mapping operator (TMO) parameterization along with a progressive optimization strategy to effectively navigate the quality-vs-power landscape. We distill the iterative optimization into a lightweight feed-forward neural network for real-time deployment. Subjective experiments show that our method yields better perceptual quality than prior work at the same power budget. Project page: this https URL.
### Title:
          Milo, a Fully Autonomous Indoor/Outdoor Robotic Guide Dog
 - **Authors:** Florian Golemo, Joanna Wolski, Joel Ruben Antony Moniz, Christopher Pal
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many Blind and Low-Vision (BLV) people rely on guide dogs for moment-to-moment navigation, such as staying on path and avoiding obstacles and pedestrians. However, guide dogs are expensive to acquire and maintain (approximately \$50k USD plus ongoing costs), often involve long waiting lists, and have relatively short life expectancies. While robot guide dogs offer a promising alternative, existing approaches exploring this idea suffer from several drawbacks: They often lack the autonomy required for real-world deployment, relying on prior 3D scans of the environment, external computation, or limited awareness of the handler. In this work, we present Milo, the first open-source, low-cost (approximately \$2k USD) robotic guide dog platform capable of fulfilling the basic collaborative navigation role expected of a guide dog. Milo is fully autonomous, requiring no a priori knowledge of the environment, completely self-contained with all computation performed onboard, and suitable for both indoor and outdoor navigation while avoiding obstacles and pedestrians. Our system consists of a modified Unitree Go2 robot (equipped with onboard compute, sensors, and a handle), a perception stack combining voxel mapping with floor, obstacle, and pedestrian detection, and a navigation stack based on an obstacle-avoidance policy trained in a custom bird's-eye-view simulator. We evaluate Milo in real indoor and outdoor obstacle courses and compare it against a costmap-based baseline, demonstrating smoother navigation and fewer handler collisions. To maximize accessibility for BLV users, we release both the robot hardware instructions and the complete software stack as open source.
### Title:
          Combinatorial Capacity Bounds for the $q$-ary Deletion Channel
 - **Authors:** Hassan Tavakoli, Thinh Nguyen, Bella Bose
 - **Subjects:** Subjects:
Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study the \(q\)-ary deletion channel via the pattern-count scalar \(N_n(x,y)\), the number of deletion subsets mapping \(x\in\Sigma_q^n\) to \(y\in\Sigma_q^k\), which factorizes the transition probability. Two sum identities on \(N_n\) certify stochastic normalization and, under uniform input, yield an exact closed-form output entropy. These give the finite-block capacity sandwich \( (1-d)\log_2 q-h_2(d)\;\le\; C_{q,n}\;\le\;(1-d)\log_2 q. \) The exact uniform-input rate is \( \frac{1}{n}I_U(X;Y) =(1-d)\log_2 q+\frac{1}{n}H_{\mathrm{Bin}}(n,1-d)-h_2(d)+\frac{\Delta_n(d)}{n}, \) from which the simpler certified bound \( C_{q,n}\ge (1-d)\log_2 q-h_2(d)+\frac{\Delta_n(d)}{n} \) follows. The small-\(d\) bound \(C_q(d)\ge\log_2 q+d\log_2 d+O(d)\) follows for all \(q\ge 2\). Numerical experiments at \(n=3,5,10\) and \(q=2,3\) confirm all bounds.
### Title:
          End-to-End Differential Privacy in Training Deep Neural Network Classifiers
 - **Authors:** Huaiyuan Rao, Calvin Hawkins, Alexander Benvenuti, Matthew Hale
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Differentially private machine learning enables model training on sensitive data while ensuring that individual data is unlikely to be recoverable from the parameters of the resulting model. However, existing work often privatizes both training inputs and their labels, and these protections may be conservative when labels are public or can be safely made public. Therefore, in this work we propose a novel private training framework that instead privatizes training inputs while keeping labels public. We consider neural networks with softmax output layers, and thus the mapping from training inputs to the output of the softmax layer is a mapping onto the unit simplex. We randomize softmax outputs during training by applying the Dirichlet mechanism to enforce differential privacy for the training inputs, hence the ``end-to-end'' label. Because training data is reused across multiple training epochs, we use the notion of \Renyi differential privacy to formulate tight bounds on the strength of privacy provided by the Dirichlet mechanism across repeated uses. We show empirically that we attain new state-of-the-art accuracy when training from scratch on CIFAR10, MNIST, MedMNIST, FashionMNIST, and SVHN across all privacy budgets evaluated. Notably, when implementing $(\epsilon, \delta)$-differential privacy with $\delta=10^{-5}$, we improve the prior state-of-the-art accuracy from $78.37\%$ to $88.17\%$ at $\epsilon=4$ on CIFAR10, and our approach has $82.96\%$ accuracy even for $\epsilon=1$, which significantly outperforms prior work.
### Title:
          Enterprise Integration Modernization with SAP BTP
 - **Authors:** Shunmukha Sagar Puppala
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hybrid and multi cloud adoption has made enterprise integration a strategic architecture problem rather than a narrow middleware concern. Large organizations frequently operate SAP S4HANA, SAP ECC, SaaS business applications, partner portals, data lakes, and hyper scaler services across heterogeneous environments. Point-to-point interfaces and legacy enterprise service bus patterns often create tight coupling, duplicated mappings, weak observability, and security gaps. This paper proposes a Hybrid Multi Cloud Integration Modernization Framework, abbreviated as HMC-IMF, for SAP Business Technology Platform centered enterprise integration modernization. The framework combines SAP Integration Suite, API management, event driven integration, clean core extensions, runtime placement, security governance, and observability into a unified modernization model. A synthetic enterprise integration dataset is defined with 186 applications, 2,850 interfaces, 1,120 APIs, 740 event topics, 320 batch flows, five cloud environments, and 24 months of operational logs. Experimental analysis compares a legacy point-to-point baseline with the proposed BTP centered architecture. Results show a 38 percent reduction in interface complexity, a decrease in average integration latency from 420 MS to 245 MS, a reduction in mean time to recovery from 155 minutes to 54 minutes, and a decline in failed message rate from 3.8 percent to 1.1 percent. The findings suggest that SAP BTP can serve as a governed integration modernization layer when paired with explicit pattern selection, policy controls, and operational telemetry. Index Terms SAP BTP, enterprise integration, hybrid cloud, multi-cloud architecture, SAP Integration Suite, API management, event-driven architecture, clean core
### Title:
          Bridging Behavior and Implementation: Automated Java Glue Code Generation for Behavior-Driven Development
 - **Authors:** Xinyu Shi, Zhou Yang, An Ran Chen
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Behavior-Driven Development (BDD) helps technical and non-technical stakeholders share a common understanding of software requirements through natural-language scenarios. Glue code makes these scenarios executable by mapping each step to the corresponding project code. However, developing and maintaining glue code requires knowledge of both the intended behavior and the underlying codebase, making it a labor-intensive part of BDD as requirements evolve. Although large language models (LLMs) have shown strong code generation capabilities, their use for automated glue code generation remains unexplored. This task requires reasoning over underspecified behavior, related BDD artifacts, and large project codebases. We present AutoGlue, a hierarchical multi-agent framework for automated Java glue code generation. AutoGlue follows a behavior-first workflow that separates behavior interpretation, context retrieval, and code generation. A Behavior Interpreter derives the intent of a step from its scenario context, while a Developer agent retrieves relevant BDD artifacts and project code before generating the final glue code. We evaluate AutoGlue on 1,307 steps from eight open-source Java projects. Compared with few-shot prompting, AutoGlue improves API F1 by 58.7% and CodeBLEU by 43.7%. It produces directly usable glue code for 46.1% of the evaluated steps, while most partially correct outputs require only minor revisions, such as adding missing actions or refining parameters. Ablation results show that behavior interpretation and project-aware context retrieval both contribute substantially to generation quality. These findings demonstrate that LLMs can effectively connect natural-language behavior specifications with project code and support specification-driven software development.
### Title:
          A Unified Tokenization Framework for Pain Recognition using Heterogeneous 3D Modalities
 - **Authors:** Stefanos Gkikas, Christian Arzate Cruz, Valentina Becchetti, Muhammad Umar Khan, Alessandro Giuseppi, Raul Fernandez Rojas
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pain is a complex and pervasive phenomenon affecting a large percentage of the population, and accurate assessment is essential for effective clinical management and intervention. Computational pain recognition systems enable continuous monitoring, support clinical decision-making, and help mitigate pain-related distress and functional decline. This study introduces a unified tokenization framework for heterogeneous 3D modalities in pain recognition that provides a single processing pipeline across behavioral and brain-activity 3D data, without requiring separate architectures for each modality or handcrafted inductive biases. The framework preserves spatial, temporal, and time--frequency structure while mapping diverse inputs into a shared token space. Extensive experiments show that the proposed approach effectively processes facial videos and fNIRS data in both raw-signal and spectrogram-based representations. On the AI4Pain benchmark dataset, the proposed framework achieves state-of-the-art performance while maintaining high computational efficiency and enabling real-time assessment on both GPU and CPU hardware.
### Title:
          KineBench: Benchmarking Embodied World Models via IDM-Free Kinematic Grounding
 - **Authors:** Zeyu Liu, Zhangzhe Zhu, Yang Zhang, Chenyou Fan, Chenjia Bai, Xuelong Li
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Evaluating the physical consistency of embodied world models(EWMs) is a critical open challenge. While closed-loop evaluation via simulator rollouts offers a more faithful assessment of physical plausibility than open-loop alternatives, existing frameworks almost exclusively rely on Inverse Dynamics Models(IDMs) for action extraction. Due to the intricate mapping from 2D pixel space to 3D kinematic space, the learned IDMs can be brittle to data outside their training distribution, resulting in unreliable action extraction from the generated videos with novel objects and scenarios. This creates an unavoidable attribution ambiguity between world model inaccuracies and extractor errors. To reduce this ambiguity, we present KineBench, an IDM-free closed-loop benchmark for EWMs, built upon an explicit kinematic grounding pipeline. Given a generated video, KineBench employs cascaded visual foundation models to directly extract 6D end-effector poses from individual frames, which are then executed in a physics simulator for closed-loop validation. Beyond execution-based task success, KineBench incorporates two classical 3D kinematic metrics--Spectral Arc Length (SPARC) and the Maruyama Manipulability Index--to characterize trajectory smoothness and kinematic feasibility from a robot-centric perspective. Built on 20 diverse manipulation tasks in ManiSkill3, KineBench evaluates EWMs across four progressive suites: basic execution, task transfer, visual out-of-distribution generalization, and complexity-conditioned scaling. Evaluation across frontier models reveals task-complexity-bounded nonlinear scaling in embodied video generation, providing empirical guidance for future data-scaling strategies.
### Title:
          MV-Bench: Benchmarking Multimodal Large Language Models for Coordinated Multi-View Interface Construction
 - **Authors:** Yue Zhao, Hongxu Liu, Feiyu Wang, Xiaoyu Yang, Tong Ge, Zhen Yang, Chao Wang, Qiong Zeng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal large language models (MLLMs) are increasingly expected to automate visualization development by generating code directly from visual designs. However, existing evaluations mainly focus on single-chart generation and overlook coordinated multi-view interface construction, which requires joint reasoning about data semantics, view coordination, and interaction logic. Consequently, MLLM capabilities in this setting remain underexplored, and the field lacks a dedicated benchmark for systematic assessment. We introduce MV-Bench, a benchmark for evaluating MLLMs on coordinated multi-view interface construction. Instead of relying on incomplete or inconsistent open-source implementations, we use Tableau workbook files as ground truth because they explicitly encode data bindings, visual mappings, and interactions. We develop a multi-stage pipeline that converts these specifications into executable web interfaces through structured intermediate representations. The benchmark contains 92 base interfaces and 1,048 verified instances created by recombining chart types, datasets, and interaction patterns. Each instance includes executable code, a rendered interface, a dataset, and interaction annotations. We evaluate five state-of-the-art MLLMs in a single-pass setting using metrics for visual fidelity, data binding correctness, and interaction completeness. The strongest model achieves 75.45 percent accuracy in visual layout reproduction, but only 21.71 percent in data binding and 11.68 percent in interaction completeness. These results show that current MLLMs can reproduce visual appearance but remain limited in generating the data semantics and interactive logic required by coordinated multi-view interfaces. Iterative refinement improves code executability but does not substantially reduce the gap in data binding and interaction generation.
### Title:
          Toward Seasonal Guidelines for Robust Deep-Learning Sentinel-2 Building Detection in Different Area Types
 - **Authors:** Michał Romaszewski, Kamil Drejer, Katarzyna Kołodziej, Anna Zawadzka, Stanisław Lewiński, Przemysław Głomb, Marek Ruciński, Michal Krupiński, Krzysztof Gryguc Przemysław Sekułaa, Szymon Sala
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sentinel-2 imagery offers open access, global coverage, and frequent revisit times, making it attractive for practical building mapping at scale; however, its native 10m resolution makes building vs non-building classification challenging, particularly for small or sub-pixel buildings, and performance can vary with both seasonality and the heterogeneity of built-up environments. This paper introduces a Sentinel-2 building-detection framework designed to systematically quantify these effects and to support more formalised, practice-oriented model selection. We construct a dedicated multi-temporal Sentinel-2 dataset over the Warsaw region and derive binary ground-truth masks by rasterising official Polish topographic database (BDOT10k) building footprints onto the Sentinel-2 pixel grid. Using two established convolutional segmentation backbones (U-Net and DeepLabV3+), we first perform scene-specific fine-tuning to select a robust architecture and identify the best monthly models for L1C and L2A products separately. We then conduct cross-temporal inference by applying each best monthly model to all scenes, enabling an assessment of (i) which months provide favourable training and inference conditions, (ii) how performance transfers between seasons, (iii) the impact of processing level, and (iv) how these effects differ across built-up typologies. Based on these results, we provide practical guidance for routine Sentinel-2 building classification under varying acquisition periods and settlement characteristics.
### Title:
          Robots Acquire Manipulation Skills in Seconds from a Single Human Video
 - **Authors:** Guangyan Chen, Meiling Wang, Te Cui, Zichen Zhou, Qi Shao, Shalfun Li, Hang Su, Roy Gan, Hao Wang, Mengyin Fu, Yi Yang, Yufeng Yue
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The ability to acquire skills rapidly and effortlessly while retaining those already mastered is essential for robots. However, current methods still rely on a cumbersome training-time loop that is costly and slow, while eroding skills already mastered. In this paper, we introduce HOST (Human-to-robot One-Shot Skill AcquisiTion), a framework that enables a robot to acquire skills in seconds from a single human video while retaining previously mastered skills. HOST resolves skill acquisition through a cascade of self-grounded prediction. It first estimates the robot's progress within the demonstrated task, then translates the upcoming progression into the robot's own future observations, and finally derives actions from these predicted observations. This cascade is trained on targets coupled to the video demonstration, obtained by mapping the robot trajectory and the video demonstration onto a shared task progress manifold, then redefining each target to align with the future progression of the video. HOST thereby enables the robot to actively follow the demonstrated procedure and adapt it to the robot's embodiment. HOST acquires novel skills at inference time from a single human video in an average of 29 seconds and achieves a 62% average success rate. It exceeds the zero-shot baseline by 45% while retaining previously mastered skills. HOST even exceeds the baseline fine-tuned on 50 robot demonstrations per task while requiring 50 times fewer demonstrations and acquiring each skill 507 times faster. Additional information about HOST is available on the project website.
### Title:
          Two-Step Occupation Coding
 - **Authors:** Alexander M. Esser, Jens Dörpinghaus
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Occupation coding links job titles in free text to occupational taxonomies and is a core task in labor market research. Existing approaches typically address this problem in a single end-to-end step, jointly identifying job titles and assigning occupational codes. This paper presents a novel two-step approach that separates these tasks. In the first step, a domain-specific Named Entity Recognition (NER) model identifies occupational titles in continuous text, even under noise such as OCR errors. In the second step, the extracted job titles are mapped to a taxonomy, enabling the classifier to focus exclusively on this mapping. We demonstrate that this separation improves accuracy, robustness, and interpretability compared to single-step approaches. The method has been developed for German documents but is transferable to other languages. We further introduce a margin-based confidence criterion for occupation coding, replacing common absolute thresholds. To support reproducibility, we publish the source code and evaluation scripts.
### Title:
          Ascend to Science: Exploration of AI Chips for Scientific Computing
 - **Authors:** Weicheng Xue, Kai Yang, Yongxiang Liu, Baisong Xu, Dengdong Fan, Xianglin Liu, Pengxiang Xu, Yonghong Tian
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid rise of AI-oriented accelerators has reshaped compute systems around low-precision tensor engines, raising a practical question for the HPC community: under what conditions can such hardware support scientific workloads that demand numerical robustness, irregular memory access, and scalability? Using the Ascend 910 NPU series as a representative tensor-centric platform, we characterize precision, execution, and memory-hierarchy bottlenecks that hinder the direct deployment of scientific codes. We then develop and evaluate workload-specific mappings across five application studies -- HPL-MxP, LRSVD, SGEMM-cube, PQSim, and SMC-X -- combining heterogeneous execution, mixed-precision numerical formulations, precision emulation, hierarchical memory orchestration, and communication--computation overlap. These studies show that AI-native NPUs can achieve numerical robustness, competitive performance, and satisfactory scalability when numerical formulation, execution placement, and data movement are addressed in a coordinated manner. Our results provide a state-of-the-practice case study of how scientific workloads can be adapted to tensor-centric architectures, while distinguishing transferable optimization principles from Ascend-specific implementation details.
### Title:
          SRAN: Scaling Named Data Networking via Map-and-Encap
 - **Authors:** Tianyuan Yu, Sirapop Theeranantachai, Lixia Zhang
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Network routing scalability is hard to achieve when forwarding state is driven by external entities such as end users or multicast groups. Named Data Networking (NDN) faces this challenge acutely: it fetches data by name, which ties forwarding state to an unbounded number of application name prefixes. This paper presents SRAN, a scalable routing and forwarding architecture for NDN. Building on the Map-and-Encap principle, SRAN separates name-prefix reachability from topological reachability by mapping prefixes to egress routers at the network edge. Consequently, the network core routes and forwards based solely on topological connectivity. SRAN extends this mapping to support multicast by adapting Bit Index Explicit Replication (BIER), encoding prefix-to-multiple-egress mappings as a BitString to enable stateless multicast delivery. Implemented on the NDN substrate, SRAN leverages NDN's native security and dataset synchronization for secure routing and prefix-state dissemination, requiring no additional protocol. Evaluation on representative Rocketfuel topologies confirms that the network forwarding state scales with the topology rather than the application-prefix count, and adapts to prefix changes in real time with minimal dissemination overhead.
## Keyword: localization
### Title:
          An Exploratory Analysis of Pain Localization via Explainable Computational Modeling
 - **Authors:** Ioannis Kyprakis, Stefanos Gkikas, Eric Nichols, Yu Fang, Manolis Tsiknakis
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automatic pain localization, which involves identifying the anatomical origin of pain from peripheral physiological signals without patient self-report, is a clinically critical but largely unaddressed problem, particularly for non-verbal patients. This paper presents a systematic comparison of classical feature engineering and deep sequence learning for subject-independent three-class pain localization using the AI4Pain 2026 Challenge dataset, which comprises four synchronously recorded wearable modalities: electrodermal activity, blood volume pulse, respiration, and peripheral oxygen saturation recorded from 65 participants under controlled TENS-induced pain. A 115-dimensional hand-crafted feature set spanning time-domain, frequency-domain, modality-specific, and cross-modal descriptors is benchmarked against end-to-end deep architectures. Extremely Randomized Trees achieves the highest macro-F1 of 0.539, outperforming the best deep model by 7.4 percentage points, with EDA spectral features emerging as the dominant discriminators. A consistent 26-point gap between pain detection (F1\,=\,0.815) and localization (F1\,=\,0.552) across all models points to a fundamental ceiling imposed by the anatomical diffuseness of peripheral autonomic pathways at 10-second resolution.
### Title:
          Learning the Arabic Dialect Continuum as a Continuous Space: A Regression Approach to Speaker Origin Prediction
 - **Authors:** Mohamed Aziz Khadraoui, Adel Ammar, Bilel Benjdira, Zahid Khan, Skander Turki, Wadii Boulila
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Computers and Society (cs.CY); Machine Learning (cs.LG); Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a regression-based approach to Arabic dialect geolocation that models dialectal variation as a continuous geographic space rather than discrete categories. Speaker origin is predicted as continuous latitude-longitude coordinates using a hierarchical neural architecture that fuses frame-level XLS-R-300M and Whisper-large-v3 encoder representations with phonotactic descriptors through a Transformer encoder and a learnable attention-pooled query. A spherical geodesic loss directly optimizes great-circle distance on Earth's surface, avoiding distortions inherent to planar coordinate regression. Under a leakage-free 5-fold GroupKFold protocol grouped by source recording, our model attains a pooled median localization error of 481.2 km. Auxiliary country and city heads reach 64.5% and 45.2% accuracy, respectively. A permutation Mantel test on the learned latent space provides quantitative support for the Arabic dialect continuum hypothesis. To probe true generalization, we further introduce a city-masking protocol in which two cities per fold are removed from training but retained in validation. Under this zero-shot regime, the mean error rises to 1173.3 km, a 1.32x degradation relative to seen cities. Our findings establish continuous geographic modeling as a principled framework for Arabic dialect geolocation and quantify both its strengths and the substantial headroom that remains.
### Title:
          LAVIFT: Latent-Action-Guided Vision Fine-Tuning for Surgical Interaction Recognition
 - **Authors:** Jiajun Cheng, Subarna Tripathi, Sainan Liu, Xiaofan Yu, Shan Lin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding instrument-tissue interactions is essential for context-aware surgical AI and autonomous robotic surgery. Pretrained vision-language models (VLMs) and vision encoders offer an alternative to conventional interaction classifiers by transferring broad visual and semantic knowledge. However, adapting them to fine-grained surgical interactions remains challenging: (1) freezing the vision encoder depends entirely on pretrained representations that may retain noise and provide weak spatial localization, while (2) full fine-tuning can improve global semantic alignment without ensuring that the encoder learns meaningful features in the correct action region. We address these limitations by introducing LAViFiT, an end-to-end latent-action-guided framework for vision-language fine-tuning. An inverse dynamics model captures the visual changes induced by each action, while a forward world model drives the encoder to represent action-relevant regions. A patch-level SIG Regularizer further prevents local feature collapse without additional supervision, such as bounding boxes or pseudo-labels. Experiments across multiple encoders and datasets improve recognition and image-text alignment, while representation analyses show stronger grounding over the complete instrument-tissue interaction region and more spatially coherent features.
### Title:
          OffNadirLoc: Benchmark and Framework for Challenging UAV-to-Satellite Geo-Localization under Large Off-Nadir Views
 - **Authors:** Qian Qiao, Wenye Liu, Ting Liu, Jiuhe Shu, Peng Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-view geo-localization between UAV and satellite imagery remains a fundamental yet highly challenging task, especially under large off-nadir views where drastic perspective distortions, occlusions, and appearance gaps occur. Existing benchmarks and methods primarily focus on near-nadir scenarios and often overlook the importance of structural scene understanding and intra-domain relational constraints, limiting their performance in real-world deployments. In this work, we introduce OffNadirLoc, a new benchmark for large off-nadir UAV-to-satellite geo-localization. To tackle the unique challenges posed by off-nadir perspectives, we further propose ONLoc, a framework that incorporates a structure-aware contextual weighting mechanism to dynamically emphasize reliable local features while suppressing ambiguous or repetitive regions. Additionally, we design a view-coherent learning strategy, which treats one satellite image and the corresponding UAV images from multiple views as a cohesive semantic group. This set-level supervision enables the model to learn viewpoint-invariant and discriminative features, making it more effective at capturing multi-view consistency than conventional pairwise contrastive learning. Extensive experiments on the OffNadirLoc benchmark and four near-nadir datasets demonstrate that our method consistently outperforms state-of-the-art approaches while exhibiting strong zero-shot generalization to unseen datasets without additional training. The code will be released at this https URL.
### Title:
          RIM: A Retrieval-In-Matching Framework for Cross-Domain Global Visual Localization of UAVs
 - **Authors:** Xin Li, Siyuan Duan, Shang Wang, Zhimin Mao, Bingliang Hu, Geng Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Global visual localization of unmanned aerial vehicles (UAVs) using remote-sensing reference maps has attracted increasing attention. However, acquisition-time and imaging-platform differences between UAV and reference imagery induce substantial cross-domain appearance and viewpoint shifts, challenging robust six-degree-of-freedom (6-DoF) pose estimation. We address these shifts by sampling UAV-viewpoint reference views from Google 3D Tiles across locations, altitudes, and orientations. A two-stage cross-domain fine-tuning recipe adapts SALAD using pose-near positives and geographically distant hard negatives, while local geometric consistency re-ranks the Top-K candidates. We further propose Retrieval-In-Matching (RIM), which freezes the adapted DINOv2-B retriever and distils a local-descriptor decoder that reuses its token field alongside a shallow VGG19 detail stream. One query-side DINOv2-B forward thus serves both SALAD retrieval and local description, eliminating a second foundation-model backbone while preserving retrieval descriptors by construction. We evaluate RIM zero-shot on the reconstructed EPFL Urbanscape and self-collected Chang'an Park datasets, both geographically disjoint from the training data. RIM outperforms ten recent retrieval baseline families. At 25/50 m under the full 3D distance metric, it improves Recall@1 over SALAD by 8.55/13.77 percentage points on EPFL and 4.45/8.94 points on Park. At Top-K=5, the complete measured localization query, including retrieval, candidate matching, and robust geometric verification, takes 67.9 ms end-to-end: 1.8 times faster than the strongest separate sparse-matching baseline and over 40 times faster than RoMa, while achieving comparable re-ranking accuracy. These results establish an efficient and deployable pipeline for UAV global visual localization in GNSS-challenged environments.
### Title:
          HalluTruthQA: A Fine-Grained Benchmark for Hallucination Detection, Localization, and Explanation in Arabic Question Answering
 - **Authors:** Abdessalam Bouchekif, Mohammed-En-Nadhir Zighem, Salah Eddine Bekhouche, Hichem Telli, Somaya Eltanbouly, Shahd Gaben, Heba Sbahi, Samer Rashwani, Mutaz Al-Khatib, Emad Mohamed, Mohammed Ghaly, Abdenour Hadid
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) can generate fluent Arabic answers, yet factual errors remain difficult to detect, localize, explain, and verify. Existing hallucination benchmarks often provide response-level labels, with limited support for identifying the exact erroneous content, explaining why it is incorrect, or selecting the correct factual answer. We introduce \textsc{HalluTruthQA}, a fine-grained benchmark for hallucination evaluation in Arabic question answering. The benchmark contains 2,400 expert-curated examples across four knowledge-intensive domains: Islamic knowledge, history, science, and geography. Each example pairs an Arabic question and a model-generated answer with a verified reference answer, a binary hallucination label, six candidate answers for factual verification, and, for hallucinated answers, character-level erroneous spans, human-written explanations, and macro and micro hallucination types. We evaluate four open-source LLMs, \textsc{Allam}, \textsc{Falcon-H1}, \textsc{Qwen32}, and \textsc{Silma}, in a zero-shot setting across hallucination detection, span-level localization, factual verification, and explanation evaluation. Results show that these tasks capture different abilities: no single model achieves the strongest performance across all tasks, with best scores of 0.880 Macro-F1 for detection, 0.516 F1-Sp for localization, 0.852 LO-Score for factual verification, and 0.644 final score for explanation evaluation. Our taxonomy shows that hallucination evaluation should move beyond detection toward localizing, verifying, and explaining factual errors. The code, dataset, prompts, and evaluation scripts are available at this https URL.
### Title:
          Distributed Acoustic Localization Array Deployed Using a Soft Everting Vine Robot
 - **Authors:** Sebastian Lorca Godoy, Ciera McFarland, Michael Val, Antonio Alvarez Valdivia, Nathaniel Hanson, Margaret McGuinness
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Soft robot exteroception is increasingly being explored for a variety of field applications. In this work, we present a sound-based system for localizing disaster victims in confined and unstructured environments, based on a distributed acoustic sensing architecture embedded along the body of a soft everting vine robot. We propose a dynamic Steered Response Power with Phase Transform framework that supports both far-field direction-of-arrival estimation and near-field three-dimensional source localization as the robot approaches the sound source. To better understand the design and control space related to localizing sound using a soft, shape-morphing robot body, we conduct experiments measuring the accuracy of these methods for a five-microphone array attached to the robot body using three placements relative to the outer membrane of the robot (inside the pressurized body, inside the inner tail, and outside the outer wall) and in four robot configurations (linear, double linear, circular, and sinusoidal). We measure the change in accuracy as the signal-to-noise ratio, the direction of approach, and the distance of the sound source from the center of the array change. Finally, we demonstrate a vine robot growing into an arbitrary shape while carrying microphones along its outer wall, and show that a sound source located with the array's near field can be localized with high accuracy after only three microphones have everted from the robot body. These results highlight the potential of distributed acoustic sensing for reliable victim localization using soft growing robots.
## Keyword: transformer
### Title:
          AdaRoPE: Not All Attention Heads Should Rotate and Scale Equally
 - **Authors:** Shaowen Wang, Yuke Zheng, Tansheng Zhu, Shuang Chen, Shaofan Liu, Suncong Zheng, Jian Li
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rotary Position Embedding (RoPE) is widely adopted in Transformers to encode positional information, yet standard implementations enforce a uniform frequency schedule and scaling across all attention heads. Using simplified retrieval tasks and length generalization scenarios, we show -- both empirically and theoretically -- that heads with different functional roles require distinct frequency ranges and attention scaling factors to operate effectively. Ignoring this structure leads to suboptimal utilization of embedding dimensions and degraded performance, particularly under long-context settings. To address these limitations, we propose AdaRoPE, which equips each attention head with learnable rotation frequencies and attention scaling factors. Pretrained LLMs with AdaRoPE consistently outperform existing RoPE variants, including partial RoPE and NoPE baselines. For context extension, we further show that uniform frequency and attention scaling, used in methods such as YaRN, are suboptimal. By applying head-specific scaling, AdaRoPE enables better context extension while better preserving short-context performance in both the extrapolation setting and the long-context continued pretraining setting. These results highlight the importance of optimizing rotary position embedding at the level of individual attention heads.
### Title:
          Bayesian Wind Tunnels for Model Selection
 - **Authors:** Siddhartha R Dalal, Vishal Misra, Abhay Parekh
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Prior work has shown that transformers can perform exact Bayesian filtering within a fixed hypothesis class. Can they also perform Bayesian model selection -- identifying the correct hypothesis class from data? We introduce model-selection Bayesian wind tunnels: controlled environments where ground-truth posteriors over hypothesis classes are available in closed form. Using fixed-point-free involutions -- whose defining property f(f(x))=x is purely relational -- a 2.8M-parameter transformer achieves 0.01-bit entropy agreement with the Bayesian optimum (3 seeds), with both integer tokens and opaque symbols whose meanings change every episode. This extends to non-nested comparisons: involutions vs. 3-cycles (where neither class is a subset of the other) achieve class-posterior MAE under 0.001, demonstrating genuine model selection beyond simplicity/subset bias. We then identify a sharp perceptual access condition: when the discriminative statistic requires arithmetic -- modular addition (rotations) or multiplication (f(x)=cx mod p) -- model selection succeeds with integer tokens but fails completely with opaque symbols, and this boundary persists under 112x scaling (2.8M to 316M parameters). A stationarity control confirms the operative factor: opaque tokens with a fixed relabeling succeed (0.009-bit MAE), showing that stable semantics, not integer identity, enable circuit compilation. Header subtask diagnostics localize the failure to the composition of header inversion with arithmetic rather than header parsing itself. Probing frontier LLMs on the same tasks shows qualitative Bayesian behavior but a large calibration gap (~55x), measured through lossy probes and therefore directional rather than exact.
### Title:
          STN-TGAT: Top-K Portfolio Construction via Prior-Guided Graph Attention with Learnable Soft-Threshold Sparsification
 - **Authors:** Haoran Guo, Yutong Lu, Li Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper tackles the problem of stock ranking and portfolio construction under realistic investment settings by jointly modeling temporal dynamics and cross-sectional dependencies. We propose the Soft-Threshold NMI-prior Transformer Graph Attention Network (STN-TGAT), which integrates a temporal Transformer with a Graph Attention Network to capture long-horizon sequential patterns and dynamic inter-stock relationships. An NMI-based prior graph combined with a soft-threshold sparsification mechanism enhances structural robustness by mitigating noisy correlations while preserving informative connections. The portfolio formation process incorporates practical considerations, including Top-5 selection within the Top-50 $S\&P$ 500 constituents, explicit weight allocation, and transaction cost adjustment, thereby aligning the evaluation with real-world trading conditions. Empirical results on real-world data demonstrate that STN-TGAT consistently outperforms benchmark models from predictive accuracy and investment profitability measured by portfolio returns. These findings suggest that combining decision-aligned training with adaptive relational modeling provides a coherent and practically effective framework for data-driven portfolio construction.
### Title:
          LAARA: Layer-Aware Adaptive Rank Allocation for Parameter-Efficient Fine-Tuning
 - **Authors:** Ashutosh Tripathi, Surya Deep Singh, Pranab Sahoo, Sriparna Saha
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Low-Rank Adaptation is widely used for parameter-efficient fine-tuning, yet existing methods typically assign the same adapter rank to every transformer layer despite their heterogeneous adaptation requirements. In this work, we show theoretically and empirically that uniform rank allocation is fundamentally suboptimal. Motivated by this observation, we propose LAARA (Layer Aware Adaptive Rank Allocation framework), a search-free framework that dynamically allocates ranks using lightweight diagonal Fisher estimates computed during training. LAARA combines projection-wise normalization, logarithmic compression, blended adapter importance estimation, and a vote-to-change dampening mechanism to produce stable and efficient rank adaptation. Experiments on GLUE and MathInstruct benchmark demonstrate that LAARA consistently matches or outperforms popular state of the art approaches such as LoRA, AdaLoRA, DyLoRA, and Bitfit while using significantly fewer trainable parameters. Our results show that Fisher-guided rank allocation provides a principled and effective foundation for adaptive parameter-efficient fine-tuning. The code is publicly available at: this https URL
### Title:
          Opto-ViT-v2: Noise-Resilient On-Chip Fine-Tuning for Photonic Near-Sensor Vision Transformer Accelerators
 - **Authors:** Xuming Chen, Deniz Najafi, Mehrdad Morsali, Chengwei Zhou, Zahra Ghanaatianjobzari, Mahdi Nikdast, Shaahin Angizi, Gourav Datta
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Silicon-photonic (SiPh) accelerators have emerged as a promising platform for Vision Transformer (ViT) inference by performing matrix multiplications on microring-resonator (MRR) banks with high throughput and energy efficiency. Extending these platforms to support on-chip fine-tuning remains challenging because backpropagation requires large activation storage, frequent weight write-back to MRRs, and tolerance to device-level noise. We present Opto-ViT-v2, the first framework for parameter-efficient fine-tuning (PEFT) on a near-sensor SiPh ViT accelerator. Our tensorized low-rank decomposition separates pretrained optical weights from a small set of trainable electronic factors (as few as 8K parameters for ViT-Base), greatly reducing activation storage and weight updates while enabling practical on-chip training. We further introduce a gradient-accumulated sparse classifier that freezes low-importance weights through one-shot top-k gradient masking, reducing classifier training cost by about 40 percent. We also develop the first system-level noise model for photonic on-chip training, capturing the effects of MRR crosstalk, thermal drift, and laser amplitude noise during both forward and backward propagation. Calibrated using measurements from more than 200 fabricated MRR devices, the model shows that low-rank factor updates are more robust than full fine-tuning and conventional layer-wise low-rank adaptation under identical noise conditions. Experiments on VTAB-1K (19 tasks) and FGVC few-shot benchmarks demonstrate that Opto-ViT-v2 recovers within 0.3 to 0.8 percent of clean software accuracy under measured photonic noise while achieving more than 100 KFPS/W, enabling practical on-chip domain adaptation for photonic edge vision systems.
### Title:
          Adaptive Multi-Expert Graph Transformer for Interpretable EEG-Based Diagnostics
 - **Authors:** Maryam Rahimimovassagh, Md Elias Hossain, Ivan Garibay, Niloofar Yousefi
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Electroencephalographic (EEG) abnormalities arise from dynamic changes in neural synchrony across spatial and temporal scales, yet many computational approaches reduce these dynamics to static features. We present a Spatial Multi-Expert Graph Transformer that models each EEG recording as a sequence of dynamic functional connectivity graphs. Time-resolved connectivity is estimated using the weighted Phase Lag Index (wPLI), and hierarchical graph encoding aggregates information from electrode to regional and global levels. A multi-expert transformer architecture enables subtype-aware reasoning, with a gating mechanism adaptively fusing expert outputs for global abnormality prediction. Experiments on the TUAB dataset show competitive abnormal EEG detection performance and demonstrate the potential of dynamic graph modeling with adaptive expert fusion for interpretable, subtype-aware spatial--temporal analysis.
### Title:
          MoA-Structured Decode Attention DNF Derivation, KV-Cache Accumulation, GQA/MQA, and OpenACC Kernel
 - **Authors:** Lenore Mulin, Gaetan Hains
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We derive four memory-optimal inference artifacts for transformer attention using the Mathematics of Arrays (MoA), each following directly from the forward-pass Denotational Normal Form (DNF) of with the query-row index fixed to the current decode step. The artifacts are: (1)~a single-query decode DNF in which the $\psi$-reduction eliminates the $K^\top$ buffer algebraically, achieving $(d_k + nd_k+ nd_v+ d_v)\times4\,{B}$ Dynamic Random Access Memory (DRAM) traffic result numerically verified to $\|{err}\|_\leq2\times10^{-7}$; (2)~a C/OpenACC Graphics Processing Unit (GPU) kernel with Operational Normal Form (ONF) stride arithmetic and hardware-coalesced memory access, verified to $\|\mathrm{err}\|_\infty=0$ (exact IEEE-754 floating-point arithmetic); (3)~a multi-step KV-cache with $O(d_k+d_v)$ per-step append via MoA concatenation $\#$; and (4)~Grouped-Query Attention (GQA) and Multi-Query Attention (MQA) derived via $\psi$-selection, achieving a proven $\frac {h_q} { h_{kv} }$ reduction in KV traffic. All programs are verified against PyTorch scaled_dot_product_attention.
### Title:
          On the Computational Complexity of Structural Generalization
 - **Authors:** Zichao Wei
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Structural generalization has been measured repeatedly by several benchmarks, yet it has never been formally defined. We give a definition that translates the two premises (compositional structure and unbounded generalization) into mathematical language. The definition itself is neutral: a compiler that hard-codes the rules satisfies it just as well. But structural generalization becomes a scientific question only insofar as the capacity can autonomously emerge from finite data. This question pits the computational lower bound $\mathrm{NC}^1$ against the learnable ceiling $\mathrm{TC}^0$ of pure Transformers. Under a Montagovian instantiation, each compositional rule splits into two projections: a syntactic face ($F_\gamma$) and a semantic face ($G_\gamma$). Tree evaluation on the $G_\gamma$ side is an instantiation of BFVP, which is $\mathrm{NC}^1$-complete (Buss, 1987). A pure Transformer must learn both faces at once, but Kraus et al. (2026) prove that its learnable class $\subseteq \mathrm{TC}^0$. Under the standard assumption $\mathrm{TC}^0 \neq \mathrm{NC}^1$, a pure Transformer cannot learn structural generalization. Neuro-symbolic systems achieve the best benchmark scores precisely because they inject $G_\gamma$, sidestepping the genuinely hard half. Benchmark scores cannot distinguish "learned" from "given." This is what this paper sets out to make clear.
### Title:
          From Bit-Position Sensitivity to Unequal Error Protection for DNN Inference Memory
 - **Authors:** Muhammad Husnain Mubarik, Karthik Mohan Kumar, Pedro Antonio Pena, Keshavan Varadarajan, Kunal Tyagi
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We characterize per-bit-position fault sensitivity in ML inference across 16 workloads -- spanning transformer-based models and attention-free CNNs -- and across three floating-point formats. Our central empirical finding is a sharp bit-sensitivity transition: flipping any of the least-significant fraction bits up to a data-type-specific threshold, Xsafe, degrades task metrics by less than 1% under deterministic single-bit stress tests. Sensitivity rises through the upper fraction bits and spikes at the exponent-mantissa boundary, where a single-bit flip causes catastrophic collapse. Because low-order bits are largely inconsequential while high-order and exponent bits are critical, uniform SECDED protection -- which guards every bit equally at 12.5% storage overhead -- is unnecessarily conservative. We derive per-data-type Xsafe floors (FP16: 6, BF16: 4, FP32: 15) and workload-aware tiers that widen the unprotected region for resilient model classes, raising ECC savings to 37.5-62.5% without retraining. Text-conditioned diffusion models dictate the conservative floor; vision encoders, NLU models, and resilient LLMs tolerate wider bypass regions. These floors and tiers drive an Unequal Error Protection (UEP) codec with per-cacheline data-type tags and a dual-partition SRAM architecture for ML accelerators. Validation across 870+ fault-injection runs confirms selective protection holds under contiguous 2- and 3-bit upsets. The codec reduces ECC area by 27.8% relative to uniform SECDED; dual-voltage operation of the non-critical partition lowers gross BF16 read energy by about 17%, with a roughly 4% dual-partition macro-area overhead.
### Title:
          Anatomy of a Sound Neural Reasoner: One-Shot Amortization, First-Pass Poisoning, and Search Inertness in Clue-Rich Completion
 - **Authors:** Aleksey Komissarov
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural solvers are built to deduce, branch, and revise intermediate states. The Lattice Deduction Transformer (LDT) appears to do exactly that. In clue-rich Sudoku, it does not: one forward pass commits essentially the entire grid (every blank cell on standard 6x6, 94-96% on augmented 9x9), turning the iterative solver into a one-shot predictor wrapped in an exact verifier. All hard-slice failures are decided before search begins, when the first pass confidently deletes a value required by the true solution. We call this first-pass poisoning. Adding learned branching, MRV, backtracking, value exclusion, and shared nogoods (CoLT) does not change which Sudoku instances are solved; it cuts repeated invalid derivations 1,497-fold. At the frozen training budget, constraint-graph attention alone matches full-CoLT accuracy, while positional tables recover only under substantially longer training, indicating an optimization and sample-efficiency advantage rather than an absolute capacity difference. The diagnosis predicts two effective interventions. Digit-permutation augmentation raises 9x9 accuracy from below 1% to 96.5 +/- 0.3 across three training seeds on a symmetry-disjoint split. Test-time union over symmetry-transformed passes raises all three hard-slice checkpoints from 72.8-78.9% to 100% without retraining. On from-scratch graph coloring, one-shot behavior disappears and search changes accuracy. In clue-rich completion, LDT-like systems are one-shot amortized predictors rather than learned search procedures: accuracy is determined by calibration and symmetry, while search primarily removes computational waste.
### Title:
          Learning the Arabic Dialect Continuum as a Continuous Space: A Regression Approach to Speaker Origin Prediction
 - **Authors:** Mohamed Aziz Khadraoui, Adel Ammar, Bilel Benjdira, Zahid Khan, Skander Turki, Wadii Boulila
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Computers and Society (cs.CY); Machine Learning (cs.LG); Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a regression-based approach to Arabic dialect geolocation that models dialectal variation as a continuous geographic space rather than discrete categories. Speaker origin is predicted as continuous latitude-longitude coordinates using a hierarchical neural architecture that fuses frame-level XLS-R-300M and Whisper-large-v3 encoder representations with phonotactic descriptors through a Transformer encoder and a learnable attention-pooled query. A spherical geodesic loss directly optimizes great-circle distance on Earth's surface, avoiding distortions inherent to planar coordinate regression. Under a leakage-free 5-fold GroupKFold protocol grouped by source recording, our model attains a pooled median localization error of 481.2 km. Auxiliary country and city heads reach 64.5% and 45.2% accuracy, respectively. A permutation Mantel test on the learned latent space provides quantitative support for the Arabic dialect continuum hypothesis. To probe true generalization, we further introduce a city-masking protocol in which two cities per fold are removed from training but retained in validation. Under this zero-shot regime, the mean error rises to 1173.3 km, a 1.32x degradation relative to seen cities. Our findings establish continuous geographic modeling as a principled framework for Arabic dialect geolocation and quantify both its strengths and the substantial headroom that remains.
### Title:
          TriAgent: Divergence-Aware Multi-Agent Committees for Cost-Efficient Financial Sentiment Analysis
 - **Authors:** Isabel Xu (The Overlake School)Cynthia Xu (The Overlake School)Rachel Ren (Edwards Vacuum Inc.)Cong Guo (The University of Memphis)Jiacheng Ding (The University of Memphis)
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Computational Engineering, Finance, and Science (cs.CE); Databases (cs.DB); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Production LLM-based financial sentiment analysis faces a structural cost trap: most queries are trivially classifiable, yet expensive cloud reasoners process them all, and the bill scales linearly with user count. We present TriAgent, a multi-agent committee stratified by contextual granularity -- a word-level lexicon (VADER), a sentence-level domain transformer (FinBERT), and a cross-sentence reasoner (Qwen2.5, 0.5B-14B-4bit, with Mistral-7B and Phi-3.5-mini cross-family checks). A three-way Semantic Divergence Index (SDI) measures pairwise disagreement across granularities and routes each query accordingly. Our central finding is the critic plateau: when the LLM is re-tasked as a critic over the smaller agents' outputs, F1 plateaus at ~0.87 across 1.5B-7B Qwen (bootstrap 95% CIs overlap), while a same-size 3-persona vote drops to F1=0.66, which is driven by granularity-stratified diversity. Three corollaries follow from the same SDI signal: (i) a Shared Consensus Dictionary on multilingual sentence-BERT answers 95% of Chinese queries from an English cache at F1=0.99 -- cross-border canonicalization at zero marginal cost; (ii) SDI doubles as a post-hoc LLM-hallucination detector at AUC=0.90; (iii) the SDI single-stage strategy attains the best risk-adjusted return (Sharpe=3.50) on a 20-ticker back-test, dominating both always-FinBERT (1.36) and always-LLM (0.11). At 10M-user scale, TriAgent saves $9.3M/year vs. a GPT-4o-mini baseline. Code, lexicons, and the SCD are released.
### Title:
          StellarTTS: Sparse Temporal Embedding for Low-Latency and Robust Speech Synthesis
 - **Authors:** Kaicheng Luo, Xuefei Gong, Yutao Sun, Jinling He, Yujie Hou, Xiaoyang Xing, Huiyan Li, Bing Han, Yanmin Qian
 - **Subjects:** Subjects:
Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The trade-off between robustness, latency, and prosody critically challenges text-to-speech (TTS) systems. Autoregressive models, despite fidelity, are slow and error-prone; non-autoregressive (NAR) alternatives, while fast, often sacrifice prosodic naturalness via rigid alignments. This paper introduces StellarTTS, a novel mobile-optimized NAR TTS framework based on a sparse temporal embedding strategy, enabling granular control of phoneme duration, pronunciation, and prosody. Furthermore, we propose a semantic-aware codec that facilitates efficient single-stage decoding. Conditioned on the sparse temporal embedding, our 83M-parameter lightweight masked generative transformer achieves a real-time factor (RTF) of 0.08. Experiments demonstrate that StellarTTS attains lower latency and stronger robustness compared to state-of-the-art TTS systems, while maintaining competitive performance in audio quality, prosodic naturalness, and speaker similarity.
### Title:
          The Giant Hippocampus: From Structural Monoculture to a System of Systems
 - **Authors:** Jaeho Seol
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Neural and Evolutionary Computing (cs.NE); Neurons and Cognition (q-bio.NC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI researchers describe state-of-the-art models as one thing repeated at scale: the Transformer, wired identically for text, pixels, or speech. Neuroscientists describe the cortex as a mosaic - dense Layer 4 in visual cortex for spatial encoding, thick Layers 5/6 in motion cortex for temporal integration - different jobs solved by different structures. This paper argues the gap is a structural error, not a stylistic one, and is measurable. A century of cytoarchitecture, from Brodmann to single-cell Patch-seq, shows distinct cognitive functions are implemented by qualitatively different structures, not by rescaling one template. The convolutional neural network is the field's own proof: local receptive fields and hierarchical depth encoded this prior directly, reaching strong image recognition on far less data than later architectures needed. The paper traces how this lesson was discarded: the "Hardware Lottery" made the Transformer the path of least resistance, not the principled choice, and Mixture-of-Experts, often cited as diversity, in fact partitions parameters among identical experts. A functionalist analysis shows the Transformer is best understood as a functional analog of the hippocampal formation, not a general-purpose cortex - the same mistake as treating cortex as one giant Broca's area, except the field has now standardized on a giant hippocampus, applied to tasks it was never built for: audition, executive gating, working memory. The paper closes with an alternative: a Heterogeneous Topological Network, a System of Systems in which distinct modules keep the inductive bias their computation demands and communicate through standardized interfaces. This is a design discipline for AI architects, not cognitive science: specify modularity before training, using structural evidence as a design input rather than reverse-engineering architecture from a trained model's behavior.
### Title:
          STEREOFLOW: Progressive Stereo Matching with StereoDiT and Transition Flow Matching
 - **Authors:** Hao Wang, Haoran Geng, Xiaotong Yang, Jing Tang, Songlin Wei, Linlong Lang, Yeying Jin, Zheng Zhu, Zhaoxin Fan, Biao Leng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Stereo matching is a fundamental task in 3D reconstruction. Despite remarkable advances, the prevailing paradigms formulate stereo matching as a deterministic regression problem, collapsing the multimodal distribution modeling into a single-point estimation. This formulation suffers from a regression-to-mean bias, frequently struggling with ambiguous regions. In contrast, we introduce a prior-guided generative framework that integrates deterministic matching regression and generative distribution modeling within a complementary formulation. Built upon this formulation, we introduce StereoFlow through three key components: (i) a two-stage progressive cascade matching network that progressively produces multi-resolution stereo conditions with complementary matching cues; (ii) a pixel diffusion transformer (termed StereoDiT) with a frequency-decoupled architecture for modeling correspondence ambiguity; (iii) a few-step flow matching objective (termed Transition Flow Matching) for efficient optimization. In summary, \textsc{\textbf{StereoFlow}} achieves strong geometric consistency and rich fine-grained details in ill-posed, discontinuous regions and under zero-shot generalization. Extensive experiments demonstrate that the proposed StereoFlow establishes multiple state-of-the-art results across benchmarks, including Scene Flow, KITTI, ETH3D, and Middlebury.
### Title:
          SHFormer: Dynamic Spectral Filtering Convolutional Neural Network and High-pass Kernel Generation Transformer for Adaptive MRI Reconstruction
 - **Authors:** Sriprabha Ramanarayanan, Rahul G. S., Mohammad Al Fahim, Keerthi Ram, Ramesh Venkatesan, Mohanasankar Sivaprakasam
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Attention Mechanism (AM) selectively focuses on essential information for imaging tasks and captures relationships between distant pixel neighborhoods to compute feature representations. Accelerated MRI reconstruction benefits from AM, as the imaging process involves Fourier domain measurements that influence image representation non-locally. However, AM-based models are more adept at capturing low-frequency information with limited capacity for high-frequency representations, restricting models to smooth reconstruction. Additionally, AM-based models need mode-specific retraining for multimodal MRI data, as their knowledge is restricted to local contextual variations that may be inadequate to capture transferable features across heterogeneous domains. To address these challenges, we propose a neuromodulation-based discriminative multi-spectral AM for scalable MRI reconstruction that can (i) propagate context-aware high-frequency details for high-quality reconstruction, and (ii) capture features reusable across deviated unseen domains in multimodal MRI. The proposed network consists of a spectral filtering CNN to capture mode-specific transferable features and a dynamic high-pass kernel generation transformer focusing on high-frequency details. We evaluate our model on comparative studies in supervised and self-supervised learning, diffusion model-based training, closed-set and open-set generalization under heterogeneous MRI data, and interpretation-based analysis. Our method offers scalable, high-quality reconstruction with best improvement margins of ~1 dB in PSNR and ~0.01 in SSIM under unseen scenarios. Code: this https URL
### Title:
          StreamHOI: Interaction-aware Temporal Memory Adaptation for Streaming HOI Video Generation
 - **Authors:** Zejing Rao, Haoxian Zhang, Xiaoqiang Liu, Yiping Meng, Guoxin Zhang, Pengfei Wan, Fan Tang, Tong-Yee Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing human--object interaction (HOI) video generation methods are largely limited to offline short-video generation with complex driving conditions, making them unsuitable for real-time interactive applications. We present \emph{StreamHOI}, a low-latency streaming framework for long-duration HOI video generation. Instead of converting heavily conditioned HOI pipelines into streaming systems, we study how an image-to-video streaming generator should organize historical memory to preserve interactions under bounded latency. We find that the standard sink-local memory design faces a trade-off in streaming HOI generation, and different transformer blocks show different historical-memory preferences for HOI regions and surrounding regions. To match memory composition with block behavior, StreamHOI performs offline HOI-aware block profiling and applies bias-guided memory-specialized training to adapt the generator to block-specific memory layouts. We further introduce a memory distance scaling module to strengthen long-range access to early interaction states. Extensive comparisons with both long-video baselines and recent HOI generation methods demonstrate that StreamHOI achieves strong interaction plausibility, object fidelity, human quality and efficiency, reaching 17.6 FPS with 0.75s first-chunk latency.
### Title:
          OLEDLM: A Unified Language Model for OLED Molecular Design
 - **Authors:** Fukang Wen, Yuchong Tang, Jingyuan Li, Beichen Wang, Yixuan Jiang, Xiaoyi Jiang, Yaxuan Liu, Shunyu Wang, Zuoqiang Shi, Yi Zhu, Yanan Zhu, Pipi Hu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The development of organic light-emitting diode (OLED) materials faces the compounded challenges of an astronomically large chemical space, stringent quantum-chemical constraints, and a scarcity of labeled data. Although the question of OLED generation is important, few models have been trained effectively for this specific domain. We propose an inverse molecular design framework based on causal language models: given target optoelectronic properties (e.g., excitation energy, oscillator strength), our model directly generates OLED SMILES sequences satisfying the specified constraints. We employ a multi-stage strategy: first, we establish a foundational chemical language model using a LLaMA-style transformer architecture. To the best of our knowledge, this represents the first successful adaptation of LLMs specifically for the OLED domain, bridging the gap between generic molecular generation and the stringent structural requirements of optoelectronic materials. Second, we fine-tune property predictors based on a BERT model pre-trained on our large-scale OLED dataset. Then, we perform Reinforcement Learning on our fine-tuned model, leveraging our property predictor, for better SMILES generation. Finally, through DFT verification, we demonstrate that our framework can efficiently navigate the OLED chemical space, generating novel candidates with high structural validity and optimized optoelectronic properties.
### Title:
          ELSAA: Efficient Low-Rank and Sparse Attention Approximation for Training Transformers
 - **Authors:** Mahdi Heidari, Mohammad Mahdi Rahimi, Jaekyun Moon
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The quadratic $N\times N$ attention score matrix remains a central obstacle to extending Transformers to longer input lengths. Existing efficient attention methods usually reduce this bottleneck by either imposing sparsity, so that each query attends to only a small subset of keys, or by using low-rank/kernel sketches, so that global interactions are compressed into a lower-dimensional representation. We propose \emph{ELSAA}, an efficient low-rank and sparse approximation of attention. Importantly, ELSAA does \emph{not} decompose the learned projection or output matrices of the Transformer into sparse and low-rank factors. Instead, after dense projections produce $Q,K,V$, ELSAA approximates the induced attention score operator itself: a sparse branch captures selected high-similarity interactions, while a low-rank branch summarizes diffuse global interactions. Since the two branches can be normalized over supports with very different denominator mass, ELSAA introduces a denominator-aware fusion term that scales the sparse branch according to its estimated attention mass relative to the low-rank branch. This gives a practical framework for constructing low-rank and sparse attention outputs without materializing the full quadratic score matrix, aiming to enable longer-context training while preserving both sharp token-level interactions and broad contextual mixing.
### Title:
          User-Centric Modeling of Transactional Sequences with Explainable State Space Models
 - **Authors:** Ivan Palagin
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose a hybrid approach for user-centric modeling of transactional event sequences that combines contrastive representation learning (CoLES) with State Space Models (SSMs). While contrastive methods yield high-quality compressed user representations, existing encoders -- RNNs and Transformers -- suffer from vanishing gradients or quadratic complexity, respectively. Mamba, a selective SSM, efficiently handles long-range dependencies but remains underexplored for personalized user analysis. We investigate two integration strategies: (1)~initializing the Mamba hidden state with a CoLES embedding, and (2)~prepending the projected CoLES embedding as a prefix token to the input sequence. Both approaches supply the model with an informative user prior from the first step. Experiments on three public datasets -- Age (multiclass age-group prediction), MBD (multi-label product acquisition), and Taobao (binary purchase prediction) -- demonstrate consistent improvements over standalone Mamba and CoLES with a linear classifier, with the hybrid models converging 2--3$\times$ faster than the plain SSM baseline. Explainability analysis via discretization-step maps and Integrated Gradients reveals selective event filtering on behavior-rich datasets and identifies the most informative transaction features.
### Title:
          Evolving Cache Schedules for Fast Diffusion Policy Inference
 - **Authors:** Siying Wang, Kangye Ji, Di Wang, Fei Cheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion policies achieve strong visuomotor control by iteratively denoising action chunks, but repeated denoising makes real-time deployment computationally demanding. Cache-based methods reduce inference cost by reusing intermediate activations, but existing training-free schedules typically allocate computation uniformly across blocks, ignoring heterogeneous redundancy across blocks and leading to a suboptimal performance-efficiency trade-off. To bridge this gap, we introduce Evolving Cache Schedules (EVO), a training-free acceleration framework that globally schedules cache refreshes via evolutionary search. EVO represents each candidate as a complete schedule over the block-timestep lattice. Thus, redundant transformer computations during iterative denoising can be skipped through cache reuse while preserving closed-loop rollout performance. To make the search practical, EVO introduces redundancy-aware initialization, which seeds the population with promising schedules, and target-conditioned early stopping, which verifies and terminates once a desired performance target is reached. The offline-optimized schedule can be directly plugged into pretrained diffusion policies without retraining. Extensive manipulation benchmarks show that EVO preserves near-full performance while substantially reducing computation, achieving up to 8.05x action-generation speedup and reducing FLOPs from 15.77G to as low as 1.96G. Source code is available at this https URL.
### Title:
          Persian Pixel: A large-scale synthetic OCR dataset for Persian language
 - **Authors:** Pouria Mahdi, Haq Nawaz Malik
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Optical Character Recognition (OCR) for Persian remains substantially less mature than for Latin-script languages despite Persian being spoken by more than 110 million people across multiple countries. This gap arises from two fundamental challenges: the intrinsic complexity of the Perso-Arabic writing system and the limited availability of large-scale, high-quality annotated datasets. Persian script exhibits obligatory cursive connectivity, context-dependent glyph shaping, extensive ligatures, diacritic placement, and stylistic variation across writing forms such as Naskh and Nastaliq, all of which significantly complicate text recognition. At the same time, the high cost and labor-intensive nature of manual annotation have created a persistent data bottleneck, limiting the development of robust OCR systems and slowing progress in Persian document this http URL this paper, we introduce Persian Pixel, a comprehensive synthetic OCR dataset specifically designed to address these challenges. Comprising over 343,000 high-fidelity image text pairs, the dataset spans sentence, paragraph, and full-page document layouts generated from a carefully curated seven-million-word Persian corpus using the SynthOCR-Gen rendering framework. The generation pipeline faithfully models the typographic characteristics of Persian script, including contextual character joining, positional glyph variants, diacritic placement, and multiple representative Persian typefaces. To bridge the synthetic-to-real domain gap, the rendered images are further enriched with more than twenty-five stochastic degradation models that emulate realistic document acquisition artifacts, including ink bleed, paper aging, blur, illumination variation, scanner imperfections, compression artifacts, and multiple noise this http URL overcoming the long-standing scarcity of annotated Persian OCR data, Persian Pixel provides a scalable and openly available resource for training and fine-tuning modern OCR architectures, including transformer-based models such as TrOCR and Donut. The dataset establishes a strong foundation for research in Persian document analysis, historical manuscript digitization, and end-to-end document understanding, while demonstrating that programmatic synthetic data generation offers a practical, cost-effective, and scalable alternative to manual annotation for advancing OCR in low-resource and typographically complex scripts.
## Keyword: autonomous driving
### Title:
          D3VL: Understanding Driving Scenes from 3D Time Series Data and Video with Language Models
 - **Authors:** Heesang Han, A. Lynn Abbott, Abhijit Sarkar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in Multimodal Large Language Models (MLLMs) have triggered the development of end-to-end MLLMs for autonomous driving. However, the main emphasis to date has been for MLLMs using 2D images and videos. In contrast, this paper considers MLLM effectiveness using 3D sensors, particularly LiDAR and stereo cameras. LiDAR presents unique challenges to integration within an MLLM, largely because of data sparsity and lack of a grid structure for the data. For similar reasons, fusion of camera and LiDAR data within an MLLM pipeline is also uncommon. However, most autonomous systems rely on LiDAR-based sensing, and incorporating 3D data has been proven to improve performance in traditional 3D scene perception tasks. This paper presents D3VL, a novel MLLM framework that integrates 2D and 3D time-series data in a single but simple architecture. The model aims to answer questions involving traffic scene understanding and safety. D3VL shows an 11% improvement in the KITTI Question-Answering (QA) dataset compared to baseline methods in processing 2D and 3D time-series data. This paper further introduces the Waymo QA dataset extension, which assesses models' capabilities in processing 3D and time-series data under diverse driving conditions. D3VL implementation code and WaymoQA extension can be found on our supplemental website: this https URL
### Title:
          Defer to Plan: Adaptive Multi-Agent Fusion for End-to-End V2X Driving
 - **Authors:** Nuoran Li, Zhang Zhang, Yueran Zhao, Tianze Wang, Chao Sun
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vehicle-to-everything-aided autonomous driving (V2X-AD) significantly enhances driving performance through information sharing. However, existing collaborative perception methods only optimize module-level perception capabilities and fail to effectively serve the ultimate planning and control tasks. We propose an end-to-end collaborative driving system that directly optimizes planning task performance. The system employs MotionNetwork to fuse historical temporal information, utilizes attention mechanisms to efficiently compress spatial features into compact tokens, and adaptively fuses multi-agent features through an autoregressive decoder. Additionally, we introduce Mixture-of-Experts (MoE) architecture to enhance the model's representation capacity for heterogeneous features. Experiments demonstrate that our method achieves a driving score of 79.72, surpassing the state-of-the-art CoDriving baseline (77.15) by 3.33% in closed-loop evaluation while maintaining communication efficiency.
### Title:
          WASABI: Whole-graph Assignment-based Stabilizer for lAne topology By Inter-frame tracking
 - **Authors:** Tetsuhiro Uchida, Myu Sasaki, Kensho Nakajima, Yasuhiro Shimada, Toru Saito
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving requires understanding the road as a graph of drivable lanes and their connectivity, beyond the ego lane alone, to follow routes through intersections and reason about cross- and merging-traffic. Recent perception models infer such lane topology, i.e., lane segments together with their inter-lane connectivity (LCLC), from onboard sensors over a 360-degree BEV view. Due to neural perception's imperfections, their outputs retain structural instabilities such as missed detections, lost or incorrect LCLC, over-detection, and label flicker. This paper presents WASABI, a real-time post-processing pipeline that stabilizes lane topology outputs both within and across frames by treating lane segments and their LCLC connectivity as joint tracking targets, under onboard real-time constraints (10 Hz / 20 ms / up to 200 input lanes). The pipeline integrates segment tracking with connectivity, noise-robust topology-aware refinement, and a resource-constrained real-time design. On internal validation data (16 sequences), WASABI improves LCLC detection F1 from 0.834 to 0.948 (+0.114, +13.6%) and reduces centerline lateral error from 2.50 m to 0.95 m, while reducing detection false-positives by 24.6%. Temporal-stability metrics on the same data show LCLC toggle rate reduced by 63.3% and boundary-label flicker rate by 30.2%, confirming across-frame stabilization beyond per-frame accuracy.
### Title:
          LoRFT: Benchmarking Long-Range Vehicle Trajectory Reconstruction from Fixed Highway Cameras
 - **Authors:** Yufan Zhu, Kefu Yi, Xueju Zhang, Yunyang Tian, Long Chen, Zixuan Xiao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long-range vehicle trajectories provide important spatio-temporal evidence for traffic safety analysis, autonomous driving evaluation, and data-driven traffic management, yet continuously recovering them from fixed highway cameras remains difficult. As vehicles recede into distant road regions, perspective compression and scale decay often fragment or prematurely terminate automatic tracklets, even when their continuation remains identifiable from motion consistency across neighboring frames. We formulate this problem as recovering the far-range continuation of a vehicle trajectory from a reliable near-field tracklet. We introduce LoRFT, to our knowledge the first open benchmark dedicated to long-range vehicle trajectory reconstruction from fixed highway cameras. LoRFT comprises 22 expressway surveillance scenes, 366,109 video frames, 6,601 manually verified trajectories, 2,694,889 bounding boxes, road-geometry annotations, scene-level splits, and evaluation scripts. We further propose Map-RSTNet, a map-aware residual sequence-to-sequence model that reconstructs distant trajectories in a road-geometry-aligned state space and dynamically refreshes local road geometry during decoding. On LoRFT, Map-RSTNet reduces ADE, FDE, and 5-second RMSE by 11.0%, 15.4%, and 10.5%, respectively, relative to the strongest baseline. These results demonstrate that road-geometry-aware reconstruction can extend usable trajectory records from existing fixed-camera infrastructure. LoRFT provides a reproducible testbed for long-range vehicle trajectory reconstruction.
### Title:
          GaussianSeed: Hierarchical Gaussian Seeding for High-Resolution 3D Occupancy Prediction
 - **Authors:** Xinzhuo Li, Xianghui Pan, Jiayuan Du, Wei Wei, Liuyi Wang, Chengju Liu, Qijun Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-centric 3D occupancy prediction provides dense scene representations essential for autonomous driving and robotic navigation, yet existing methods struggle to scale to high voxel resolutions due to prohibitive computational costs. To address this, we introduce GaussianSeed, a progressive multi-scale Gaussian occupancy prediction framework that organizes primitives into a coarse-to-fine hierarchy. Benefiting from this hierarchical design, GaussianSeed effectively circumvents the memory bottlenecks inherent in dense representations, successfully scaling to a $0.1\text{m}$ spatial resolution while maintaining real-time inference capabilities. To comprehensively evaluate high-resolution geometric perception, we further construct TJScenes, a panoramic six-camera occupancy dataset with highly detailed $0.1\text{m}$ annotations. Extensive experiments on Occ3D-nuScenes and TJScenes demonstrate that GaussianSeed delivers the lowest latency among all evaluated methods while maintaining highly competitive accuracy, advancing the efficiency-quality frontier of high-resolution 3D occupancy prediction.
