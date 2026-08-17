# Showing new listings for Monday, 17 August 2026
## Keyword: SLAM
### Title:
          E-S2Feat:Semantic-Guided Spiking Local Feature Detection and Description for Event Cameras
 - **Authors:** Yang Yi, Juntao Hua, Jinpu Zhang, Liangwei Fan, Hui Shen, Dewen Hu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Benefiting from high temporal resolution and dynamic range, event-based local feature methods have attracted increasing attention. However, event sparsity, noise, and limited texture still hinder robust local feature learning. Deploying such methods on resource-constrained platforms such as unmanned aerial vehicles also requires balancing accuracy and energy efficiency. To address these challenges, this paper proposes \textbf{E-S2Feat}, a spiking neural network framework for event-based local feature detection and description. The framework jointly optimizes local feature learning from the perspectives of feature representation and selection. First, a module-specific spiking activation mechanism preserves fine-grained structural cues and discriminative information under low-bit, energy-efficient inference, thereby improving overall representation fidelity. Furthermore, a semantic-guided feature modulation mechanism leverages semantic priors to refine keypoint response distributions and enhance local descriptor discriminability, thereby guiding the model to extract local features with greater geometric stability and stronger discriminative capability. Experiments on the ECD and EDS datasets show that the proposed method significantly outperforms baseline methods such as SuperEvent in pose estimation accuracy. It also achieves accuracy comparable to its artificial neural network counterpart while delivering an approximately 4.8-fold improvement in theoretical computational energy efficiency. Visual-inertial odometry experiments on the TUM-VIE dataset further verify the effectiveness and practical application potential of the proposed method in complete SLAM systems.
## Keyword: odometry
### Title:
          E-S2Feat:Semantic-Guided Spiking Local Feature Detection and Description for Event Cameras
 - **Authors:** Yang Yi, Juntao Hua, Jinpu Zhang, Liangwei Fan, Hui Shen, Dewen Hu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Benefiting from high temporal resolution and dynamic range, event-based local feature methods have attracted increasing attention. However, event sparsity, noise, and limited texture still hinder robust local feature learning. Deploying such methods on resource-constrained platforms such as unmanned aerial vehicles also requires balancing accuracy and energy efficiency. To address these challenges, this paper proposes \textbf{E-S2Feat}, a spiking neural network framework for event-based local feature detection and description. The framework jointly optimizes local feature learning from the perspectives of feature representation and selection. First, a module-specific spiking activation mechanism preserves fine-grained structural cues and discriminative information under low-bit, energy-efficient inference, thereby improving overall representation fidelity. Furthermore, a semantic-guided feature modulation mechanism leverages semantic priors to refine keypoint response distributions and enhance local descriptor discriminability, thereby guiding the model to extract local features with greater geometric stability and stronger discriminative capability. Experiments on the ECD and EDS datasets show that the proposed method significantly outperforms baseline methods such as SuperEvent in pose estimation accuracy. It also achieves accuracy comparable to its artificial neural network counterpart while delivering an approximately 4.8-fold improvement in theoretical computational energy efficiency. Visual-inertial odometry experiments on the TUM-VIE dataset further verify the effectiveness and practical application potential of the proposed method in complete SLAM systems.
### Title:
          PILOT: Privileged Imitation Learning for End-to-End Motion Planning of Autonomous UAVs under Partial Observability
 - **Authors:** Qingrui Zhang, Feng Xue, Xiang Zhou, Chenghao Yu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous navigation in cluttered environments is hampered by partial observability and dynamic constraints. This paper presents PILOT, a constraint-aware privileged imitation learning framework for vision-based end-to-end UAV motion planning under partial observability. The framework distills planning strategies from a computationally intensive optimal control expert into a student policy regularized toward safety and dynamic requirements via a dual-objective loss function. To mitigate partial observability, a spatiotemporal perception fusion module using a Temporal Convolutional Network (TCN) is developed to integrate historical depth images and odometry. This module infers task-relevant latent context from historical observations, enhancing spatial awareness beyond the instantaneous FOV without maintaining persistent map memory. A trajectory parameterization layer mapping network outputs to a structured trajectory, while enabling explicit continuity, dynamic-consistency, and obstacle soft penalties during training, encouraging constraint satisfaction for unseen observations without formal guarantees. Simulations on quadrotor and fixed-wing aircraft demonstrate that PILOT achieves performance comparable to the privileged expert while reducing computational overhead by over 80\%. Successful indoor and outdoor zero-shot deployment confirms the practical feasibility and cross-domain generalization of the planner.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          MMUSV-Sim: A Perception-Oriented Simulation and Data-Generation Platform for Multi-USV Cooperative Perception
 - **Authors:** Ziao Li, Jianxiong Ye, Biao Tang, Leping Zhang, Kun Zuo, Siyu Huang, Chenqiang Gao
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cooperative perception among multiple unmanned surface vehicles (USVs) combines complementary observations to extend maritime target sensing beyond the view range and field of a single platform. Developing such systems at scale calls for a unified workflow for configurable multi-USV scenarios, multimodal acquisition, and shared annotations. We present MMUSV-Sim, a perception-oriented maritime simulation and data-generation platform built on Unreal Engine 5 and Project AirSim. It provides island, open-sea, and port environments; configurable weather, time of day, and wave conditions; a diverse vessel asset library; and spline-based multi-vessel motion. MMUSV-Sim acquires RGB, depth, semantic, LiDAR, and radar observations across multiple USVs and captures a common world state for per-agent annotation export. Experiments verify that the configured wave settings produce the intended changes in vessel heave, roll, and pitch, and evaluate the geometric consistency between projected annotations and semantic renderings. In LiDAR-based cooperative BEV vessel detection experiments on the generated multi-USV dataset, Early Fusion achieves an AP@0.5 of 72.74, compared with 45.54 using a single USV.
### Title:
          Accelerating Large-scale Bundle Adjustment for LiDAR Mapping via Parallel Computing
 - **Authors:** Yixi Cai, Rundong Li, Yuhan Xie, Qingwen Zhang, Patric Jensfelt, Fu Zhang
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR bundle adjustment is widely utilized in mapping to construct globally consistent point cloud maps. In this paper, we propose the first fully parallel computing framework to accelerate LiDAR bundle adjustment for large-scale mapping, incorporating three key techniques. First, we design an adaptive, asynchronous data loading strategy to efficiently process large-scale point cloud datasets on memory-constrained GPUs. Secondly, we present a novel bottom-up voxelization method for extracting planar features, enabling fully parallelized pre-processing. Thirdly, we build upon a majorization-minimization formulation to accelerate compute-intensive tasks in the optimization via parallel computation, including the computation of residuals, Jacobian and Hessian matrices, and a parallel increment solver. To support our design, we provide both theoretical and experimental analysis of the time complexity of our approach. Extensive benchmarking on large-scale public datasets across various computational platforms validates the robustness and adaptability of our approach, achieving up to a tenfold improvement in computational efficiency while preserving mapping accuracy comparable to state-of-the-art methods. To benefit future research, the implementation code is available on GitHub.
### Title:
          CORAL: Curriculum-Optimized Reward Adaptation for LiDAR-Based Goal-Directed Urban Driving
 - **Authors:** Anisa Saleem, Duksu Kim
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reinforcement learning is promising for autonomous urban driving, but long-horizon goal-directed navigation asks a policy to acquire several competing behaviors at once--reaching a distant goal, tracking a route, avoiding obstacles, obeying signals--and a fixed objective gives no order in which to learn them. This paper presents CORAL, which advances two schedules together: a five-stage curriculum that progressively lengthens routes and tightens behavioral constraints, and a stage-aware reward whose component weights shift emphasis from mission progress toward route following, safety, smoothness, and rule compliance as the task hardens. The policy is a multi-stream actor-critic network trained with Proximal Policy Optimization (PPO) in CARLA on a compact 99-dimensional state pairing a polar LiDAR histogram with vehicle telemetry, ego-frame route geometry, and traffic-rule indicators--no point-cloud encoder, no bird's-eye-view rasterization. Against two PPO baselines under an identical protocol, CORAL reaches the goal in all twenty evaluation episodes on the longest routes under the full set of behavioral constraints, where the baselines reach 5% and 10%; a factorial ablation shows that neither schedule alone matches their combination: removing either lowers both success and route completion, and disabling both drops success to 55%. Trained in one town, the policy transfers zero-shot to seven unseen towns, succeeding in 68-98% of episodes on routes of the same 100-150 m length, with mean lateral deviation below 0.35 m.
### Title:
          IRGNN: Efficient Invariant Radar Graph Neural Network for Radar Point Cloud Object Detection
 - **Authors:** Xiao Guo, Wanke Xia, Lili Yang, Caicong Wu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Perception is a fundamental component of autonomous driving systems. While LiDAR-based methods have achieved remarkable progress in object detection, their reliability can degrade under adverse weather conditions. Radar point clouds provide a robust alternative due to their resilience to bad weather and low-illumination scenarios. However, radar point clouds are typically sparse, unordered, and less informative than LiDAR data, making it challenging to directly apply existing LiDAR-based perception methods. To address these challenges, we propose IRGNN, an Invariant Radar Graph Neural Network for radar point cloud object detection. IRGNN first reconstructs radar point clouds into graph representations using translation- and rotation-invariant feature designs, enabling robust modeling of sparse radar measurements. It then employs an improved message passing neural network (MPNN) with residual connections and a virtual node layer to enhance local feature propagation and global context modeling. Finally, task-specific heads are applied to the learned graph representations for object classification and bounding box prediction. Experimental results on the RadarScenes dataset show that IRGNN outperforms existing radar-based object detection methods and achieves competitive performance. In addition, IRGNN significantly reduces computational cost and memory usage during inference, demonstrating its effectiveness and practical potential for efficient radar-based perception in autonomous driving.
### Title:
          GhostPoint: Self-Supervised Representation Learning by Hallucinating Occluded LiDAR Structure
 - **Authors:** Mohamed Abdelsamad, Bin Yang, Michael Ulrich, Miao Zhang, Yakov Miron, Alexandru Paul Condurache, Abhinav Valada
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D object detection from LiDAR point clouds is a core problem in autonomous driving. Recent advances in self-supervised learning (SSL) enable scalable pretraining and transfers well to per-point tasks such as semantic and panoptic segmentation, but transfer to 3D detection remains weaker. We analyze recent SSL methods and find that most objectives are defined only on measured LiDAR returns from visible surfaces, leaving occluded and unobserved regions unconstrained. This visible-surface bias can be sufficient for point-wise prediction, but 3D detection requires robustness to missing structure. To address this gap, we propose GhostPoint, an SSL framework that hallucinates latent features in local neighborhoods around discovered instances, generated via a novel instance voxel dilation. In GhostPoint, an encoder processes observed returns, and an additional predictor infers neighborhood representations from observed context. In addition to standard encoder-level supervision, we introduce a predictor-level supervision scheme on sampled voxels from generated neighborhoods. Specifically, observed (visible/masked) voxels match teacher-encoder targets, while unobserved voxels match teacher-predictor hallucinations. This design encourages the learned representation to explicitly model structure beyond observed returns. Extensive evaluations on nuScenes and Waymo demonstrate that our method achieves state-of-the-art performance, consistently improving downstream 3D detection, especially under sparse scans and limited labels.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          Owner3D: Ownership-Guided Style Writing for Training-Free Localized 3D Stylization
 - **Authors:** Suchang Tao, Kaifeng Shi, Zhiyan Liu, Zhuoyuan Jiang, Yuqi Ouyang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Localized 3D stylization aims to modify the appearance of a specified object part while preserving the remaining surfaces. In large reconstruction models (LRMs), this task is challenging because style is injected into intermediate appearance representations before rendering, while compact triplane features are shared across target and non-target surfaces, causing style leakage and boundary ambiguity. We propose Owner3D, a training-free framework for localized 3D stylization that integrates localized appearance control directly into the LRM reconstruction process. Specifically, Owner3D introduces ownership-guided style writing to restrict reference-style injection to target regions, producing a single localized stylized triplane without additional training while avoiding separate global style and appearance representations. To resolve appearance ambiguity near semantic boundaries, we further introduce boundary dual slots that maintain separate local feature sources for target and non-target regions. Finally, a surface-first texture readout hierarchically combines surface, 3D, and triplane ownership evidence to robustly recover appearance under incomplete visibility. Experiments on a benchmark constructed from Google Scanned Objects and PartNet demonstrate that Owner3D consistently outperforms existing 3D stylization methods in target-region style fidelity and non-target appearance preservation, reducing appearance leakage by 86.4% and 89.9% compared with StyleSplat and LAENeRF, respectively.
## Keyword: mapping
### Title:
          How Compliant is Sepsis Treatment? An Expert-Guided Neuro-symbolic Pipeline for Generating Clinical Compliance Insights
 - **Authors:** Himanshu Tripathi, Kaushik Roy, Subash Neupane, Shahram Rahimi
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Symbolic Computation (cs.SC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Verifying whether clinical care follows evidence-based protocols is a natural neuro-symbolic problem, yet the safety-critical setting defeats either paradigm alone. We present an expert-guided pipeline that constrains a large language model strictly to semantic normalization, mapping messy drug and microbiology strings onto a fixed clinical vocabulary, while a Sugeno fuzzy inference system reasons over the normalized events. The fuzzy layer encodes eight Surviving Sepsis Campaign bundle rules and replaces binary judgments with graded scores in [0,1]. Applied to 2,438 MIMIC-IV v3.1 sepsis episodes, it surfaces antibiotic timing as the most critical breakdown (mean 0.24, 13% within one hour), Hour-1 underperformance (mean 36.7%), a 51% elevated-lactate drop-off, and descriptive differences in ICU stay across compliance groups (3.8 versus 5.1 days).
### Title:
          Robust Dual-Model Collaborative Random Vector Functional Link Network
 - **Authors:** A. Quadir, A. Rahaman, Mushir Akhtar, M. Tanveer
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Random vector functional link (RVFL) networks are lightweight and fast neural models that offer efficient training and strong generalization through randomized hidden-layer weights and direct input-output connections. However, conventional RVFL models are sensitive to noisy labels, outliers, and imbalanced data, which limits their performance in real-world applications. To address these challenges, we propose the kernel risk-sensitive mean p-power based RVFL (KRPRVFL) model, which integrates the computational efficiency of RVFL with the robustness of the kernel risk-sensitive mean p-power (KRP) criterion. By replacing the standard least-squares objective with a KRP-based loss, KRPRVFL adaptively reduces the influence of corrupted or unreliable samples during training, resulting in improved stability and generalization. Additionally, a collaborative learning mechanism is introduced to enable adaptive interaction among model components, further enhancing robustness in complex and noisy environments. The proposed framework also leverages kernel-induced feature mapping to capture nonlinear relationships without requiring explicit hidden-layer selection, maintaining both efficiency and scalability. Extensive experiments on UCI and KEEL benchmark datasets demonstrate that KRPRVFL consistently outperforms baseline models in terms of accuracy, robustness, and statistical significance, highlighting its effectiveness as a fast, scalable, and reliable solution for challenging classification tasks.
### Title:
          EEG-PRISM: Physiologically-Grounded Interpretability of Predictions by EEG Foundation Models
 - **Authors:** Deeksha M Shama, Punnisa Amornsirikul, Archana Venkataraman
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Objective: Foundation models represent the next advancement in AI for EEG analysis; however current explainable AI techniques provide attribution scores in the time-channel input space, which is mismatched to clinical intuition about EEG. Thus, there is a critical need for a universal method that can extend the interpretability of any foundation model to alternative and physiologically relevant domains without modifying or retraining the underlying model. Methods: EEG-PRISM leverages linear transformations and established backpropagation rules to map time-channel attribution scores into alternative domains. We derive mappings to the frequency domain via an invertible DFT and to the source domain via an approximately invertible EEG generative model. We evaluate EEG-PRISM in simulated and real data, assessing recovery of ground-truth phenomena across domains with five foundation models and four AI explainers. Results: In simulation, EEG-PRISM achieves near-perfect spectral recovery and 69.2% spatial accuracy. In epilepsy, EEG-PRISM correctly determines that delta-theta activity is most salient and correctly localizes the seizure onset region with 50% accuracy. In autism, EEG-PRISM localizes the predictive delta-alpha biomarkers to frontal and temporal regions, consistent with prior work. Conclusion: EEG-PRISM is a theoretically-grounded post-hoc attribution method with accurate mapping into the spectral and spatial domains. It supports window-level analysis of transient events (e.g., seizures) and group-level identification of clinically relevant biomarkers (e.g., autism), thus advancing interpretable EEG foundation models. Significance: This work enables physiologically-grounded interpretation of EEG foundation models and supports clinically relevant insights such as event localization and biomarker identification.
### Title:
          Vaulted Passkeys: A Device-Bound Proposal for Authenticated Credential Export and Import
 - **Authors:** Pol Henarejos
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hardware authenticators deliberately resist private-key extraction, yet replacement, disaster recovery, and controlled migration create a legitimate need for portability. Existing guidance for device-bound credentials commonly reduces recovery risk by registering an additional authenticator before failure. That creates an independent credential registration and requires replacement hardware to exist in advance; it is redundancy, not a backup of the original credential. This paper addresses the resulting recovery gap by exporting protected credential state while the source is available and restoring it to hardware acquired later, without cloning a complete authenticator or exposing plaintext private keys to routine desktop software. We propose Vaulted Passkeys, a device-bound architecture in which a random 256-bit Kvault protects authenticated PKV1 credential envelopes through HKDF-separated keys and four explicit AEAD profiles. The design separates enrollment from export/import and the required vault from optional identity. We contribute a role-separated system model, wire format, threat analysis, implementation mapping, and falsifiable evaluation plan. The prototype demonstrates feasibility but is neither a formal security proof nor a proposed final standard.
### Title:
          Structural Leakage in Graph Encryption: Attacks and Defenses
 - **Authors:** Hua Shen (1), Renzhi Chen (1), Ge Wu (2), Willy Susilo (3), Jing Chen (4), Mingwu Zhang (1) ((1) Hubei University of Technology, (2) Southeast University, (3) University of Wollongong, (4) Wuhan University)
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Graph encryption schemes (GES) enable secure outsourcing of graph data while supporting efficient queries. This report provides a comprehensive analysis of structural leakage in GES for single-pair shortest path (SPSP) queries, integrating findings from two recent works. First, we analyze PathGES, a scheme designed to resist query recovery attacks through heavy-light decomposition (HLD) and canonical fragment encoding. Our analysis reveals that PathGES suffers from significant imbalances in HLD decomposition, with over 99% of token-path mappings being one-to-one on real-world datasets, enabling both the Falzon-Paterson attack and side-channel inference of path lengths. Second, we present Fragment Tree attack that exploits these structural weaknesses to recover query contents, achieving up to 10.24% exact recovery on sparse graphs. Third, we introduce BlindGES, an enhanced scheme incorporating a Merge-and-Divide mechanism and two-level multimap index that reduces one-to-one mappings to below 20%, cuts setup time by 50%, reduces storage overhead by 32%, and limits path length leakage to under 1%. This report systematically presents attack methodologies, defense mechanisms, security proofs, and experimental evaluations on seven real-world datasets.
### Title:
          Mandato: Protocol-Level Enforcement of Digitally Signed Mandates on AI Agent Actions with Cryptographically Chained Audit Trails
 - **Authors:** Giovanni Racioppi
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI agents increasingly act on external systems through standardized tool-calling protocols such as the Model Context Protocol (MCP), yet no infrastructure layer constrains their actions to what a principal has verifiably authorized: authorization logic lives in application code, is neither signed nor independently auditable, and the resulting logs lack evidentiary value. We present Mandato, a governance proxy that enforces digitally signed mandates on agent actions at the protocol level. A mandate is a machine-readable, cryptographically signed authorization artifact specifying which tools an agent may invoke, under which parameter constraints and contextual conditions, for how long, and on whose behalf; the proxy evaluates every tool call against the applicable mandate chain, blocks non-conforming calls in line, and records every decision -- permit, deny, and the evidence for each -- in an append-only, hash-chained audit log designed for evidentiary use and periodically anchored via qualified timestamps. The mandate is deliberately modeled on the civil-law institution of delegation of authority, making the artifact legible to lawyers and auditors, not only to engineers. We give the mandate model and its decision semantics, the reference architecture as an MCP-transparent proxy with separated decision and enforcement points, and a mapping of the mechanism onto EU AI Act Articles 12 and 14, GDPR accountability, NIS2, and eIDAS 2, including a roadmap to qualified attestation through Qualified Trust Service Providers (QTSPs). We describe the implementation status of the reference system and a quantitative evaluation plan covering enforcement overhead, audit completeness, and tamper-evidence verification cost.
### Title:
          PILOT: Privileged Imitation Learning for End-to-End Motion Planning of Autonomous UAVs under Partial Observability
 - **Authors:** Qingrui Zhang, Feng Xue, Xiang Zhou, Chenghao Yu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous navigation in cluttered environments is hampered by partial observability and dynamic constraints. This paper presents PILOT, a constraint-aware privileged imitation learning framework for vision-based end-to-end UAV motion planning under partial observability. The framework distills planning strategies from a computationally intensive optimal control expert into a student policy regularized toward safety and dynamic requirements via a dual-objective loss function. To mitigate partial observability, a spatiotemporal perception fusion module using a Temporal Convolutional Network (TCN) is developed to integrate historical depth images and odometry. This module infers task-relevant latent context from historical observations, enhancing spatial awareness beyond the instantaneous FOV without maintaining persistent map memory. A trajectory parameterization layer mapping network outputs to a structured trajectory, while enabling explicit continuity, dynamic-consistency, and obstacle soft penalties during training, encouraging constraint satisfaction for unseen observations without formal guarantees. Simulations on quadrotor and fixed-wing aircraft demonstrate that PILOT achieves performance comparable to the privileged expert while reducing computational overhead by over 80\%. Successful indoor and outdoor zero-shot deployment confirms the practical feasibility and cross-domain generalization of the planner.
### Title:
          LightTeaNet: A Weakly Supervised Lightweight CNN for Multi-Label Tea Leaf Disease Detection and Localization
 - **Authors:** Naif Haider Chowdhury, Md Rahim, Syed Farhan Hasan, Murad Hasan, Prithwiraj Bhattacharjee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tea is known as an important crop in many parts of South and Southeast Asia, yet the production of tea is still hampered by the multiple diseases that decrease the quantity and quality. Traditional methods of inspection, which are manual, are not consistent, labor-intensive, and depend on extensive monitoring. This paper introduces a lightweight convolutional neural network (CNN) designed for weakly supervised multi-label classification and disease localization in tea leaves called LightTeaNet. LightTeaNet learns directly from image-level labels and employs Class Activation Mapping (CAM) to localize disease-affected regions automatically, unlike conventional object detection models such as YOLO, which require extensive bounding box annotations. For Parameter efficiency, the network integrates Depthwise Separable Convolutions, and for enhanced feature discrimination, it integrates Channel Attention. LightTeaNet has achieved a Precision of 0.9615, a Recall of 0.8772, and an F1-score of 0.9179, while it shows mAP@0.50=0.1810 without any manual annotations, which delivers a competitive localization performance in the experimental results. These results validate the model as an interpretable as well as a resource-efficient framework for intelligent disease monitoring in agriculture.
### Title:
          Accelerating Large-scale Bundle Adjustment for LiDAR Mapping via Parallel Computing
 - **Authors:** Yixi Cai, Rundong Li, Yuhan Xie, Qingwen Zhang, Patric Jensfelt, Fu Zhang
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR bundle adjustment is widely utilized in mapping to construct globally consistent point cloud maps. In this paper, we propose the first fully parallel computing framework to accelerate LiDAR bundle adjustment for large-scale mapping, incorporating three key techniques. First, we design an adaptive, asynchronous data loading strategy to efficiently process large-scale point cloud datasets on memory-constrained GPUs. Secondly, we present a novel bottom-up voxelization method for extracting planar features, enabling fully parallelized pre-processing. Thirdly, we build upon a majorization-minimization formulation to accelerate compute-intensive tasks in the optimization via parallel computation, including the computation of residuals, Jacobian and Hessian matrices, and a parallel increment solver. To support our design, we provide both theoretical and experimental analysis of the time complexity of our approach. Extensive benchmarking on large-scale public datasets across various computational platforms validates the robustness and adaptability of our approach, achieving up to a tenfold improvement in computational efficiency while preserving mapping accuracy comparable to state-of-the-art methods. To benefit future research, the implementation code is available on GitHub.
### Title:
          A Hybrid LLM-Based Framework for Automated Security Annotation Generation in Business Process Models
 - **Authors:** Md Kamrul Islam, Tiphaine Henry, Mattia Salnitri, Julius Köpke, Sami Souihi
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The modelling and analysis of secure business processes require the incorporation of security annotations into process models. Although BPMN extensions, including SecBPMN2, exist for this purpose, the derivation of accurate and complete security annotations from natural-language specifications remains a manual, expert-intensive, and error-prone task. This paper presents a hybrid framework that takes a BPMN process model and a security requirements document as input and automatically generates security annotations adhering to the SecBPMN2 specification. The approach combines Large Language Model (LLM)--based semantic extraction with schema-constrained mapping, rule-based normalization, and deterministic validation. The framework is evaluated comprehensively on a curated dataset of 27 process models from various domains. The results indicate that it consistently produces structurally valid SecBPMN2 annotations with high schema completeness. Compared to human security analysts, the system achieves substantially higher precision (0.58 vs. 0.29) while maintaining comparable recall (0.52 vs. 0.50) and reduces erroneous or misplaced annotations by nearly 50%. In addition, annotation generation is significantly faster than manual annotation. These findings demonstrate that hybrid LLM- and rule-based automation can reduce modeling effort while improving consistency and reliability, thereby providing a scalable foundation for security-by-design BPM.
### Title:
          Effect of Twisted-Yarn Architecture on Pressure and Proximity Sensing Characteristics of Textile Capacitive Sensors for Robotic Skin
 - **Authors:** Ishtia Zahir, Eslam Saleh, Maryam Rezayati, Güunter Grabher, Gaffar Hossain
 - **Subjects:** Subjects:
Robotics (cs.RO); Instrumentation and Detectors (physics.ins-det)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Textile-integrated capacitive sensors offer flexible and conformable tactile sensing for wearable electronics and human-robot interaction; however, the influence of yarn-level architecture on capacitive transduction characteristics remains insufficiently quantified. This work presents a textile capacitive sensing platform based on silver-coated yarns coated with polydimethylsiloxane and assembled into one-, two-, and four-layer twisted configurations. The influence of effective electrode overlap area and inter-fiber separation on the capacitive response is systematically investigated, enabling architecture-dependent tuning of pressure and proximity sensing characteristics. Pressure was calculated using the localized single-fiber contact area, corresponding to stresses of 0.4-3.9 MPa. Increasing the layer number improved mechanical strength and sensing performance: elongation at break increased from 37.5% to 62.5% and 85.0%, while the maximum load increased from 23.3 to 42.7 and 89.7 N. Sensitivity increased with layer number and frequency, reaching 0.1331 MPa$^{-1}$ for the four-layer sensor at 100 kHz. The four-layer configuration also exhibited low hysteresis, minimal thermal drift from 25 to 90 $^\circ$C, and stable operation over 15,000 cycles. Proximity detection ranges of 60, 50, and 40 mm were obtained for the one-, two-, and four-layer sensors, respectively, revealing an architecture-dependent sensitivity-range trade-off. A 4$\times$4 textile sensing array enabled spatial contact mapping, while robotic-arm integration demonstrated real-time touch and proximity detection with an end-to-end robotic system latency (from detection to robot reaction) of 403 ms. The results establish yarn architecture as a tunable design parameter governing the measurement characteristics of textile-integrated capacitive sensing systems.
### Title:
          Uncertainty-Aware Jacobi Set Computation
 - **Authors:** Daniel Klötzl, Daniel Weiskopf
 - **Subjects:** Subjects:
Graphics (cs.GR); Computational Geometry (cs.CG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present an uncertainty-aware Jacobi set computation method. In general, Jacobi sets are topological descriptors that capture the gradient alignments of two scalar fields, as, e.g., used for multi-field visualization. We adopt and reformulate an existing computational approach that relies on an edge-based identification of Jacobi set edges on a given triangulation. Our extension to uncertainty visualization builds upon a versatile, spatially coherent uncertainty model for pairs of scalar fields based on multivariate normal distributions. We propagate the uncertainty analytically, thereby lifting the original Jacobi set computation to uncertain inputs. Furthermore, we present an overlay of visual mappings specifically designed to show the Jacobi sets along with different facets of uncertainty information. Both the uncertainty model and uncertainty-aware method are validated against a Monte Carlo approach on an analytic dataset and applied to two use cases from fluid dynamics and weather ensembles.
### Title:
          Decoding the Past: An Uncertainty-Aware Deep Learning Framework for Sex Attribution in Prehistoric Hand Stencils
 - **Authors:** Karel Becerra, Boris Mederos, Dean Snow, Ramón A. Mollineda
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Determining the biological sex of the individuals who created Upper Paleolithic hand stencils remains a challenging problem due to the absence of ground truth, population differences between contemporary and prehistoric groups, and the uncertainty introduced by image degradation. Traditional morphometric methods suffer from high structural overlap across sexes, poor cross-population generalizability, and subjective feature engineering. This study presents an uncertainty-aware deep learning framework for sex attribution in prehistoric hand stencils that explicitly models, propagates, and aggregates uncertainty throughout the analytical pipeline. The methodology combines dual image processing, dual contour extraction, structured silhouette augmentation, model architectural diversity, and ensemble-based decision aggregation. The pipeline generates twelve plausible silhouette realizations per stencil to capture boundary uncertainties, which are processed by two ensembles of ten deep neural networks each (EfficientNet-B3 and MobileViT-S) trained on 14,036 contemporary hand samples. Furthermore, a triangulated validation scheme integrates ensemble predictions with unsupervised 2D latent-space manifold mapping (UMAP + k-NN) and explainable AI spatial attributions (LayerCAM) to ensure anatomical consistency. On contemporary data, ensemble models achieve strong classification performance, with accuracies exceeding 88% in older age groups. When applied to prehistoric stencils, the framework produces both sex predictions and confidence measures of internal agreement, enabling the distinction between morphologically stable and ambiguous cases. Convergence across ensemble predictions, latent-space structure, and interpretability analyses shows that uncertainty can become a measurable component of archaeological inference, enabling robust and reproducible decoding of ancient rock art.
## Keyword: localization
### Title:
          Does a Language Server Save Tokens for Coding Agents? A Measurement Methodology and Preliminary Study
 - **Authors:** Pengcheng Xu
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Coding agents spend most of their context budget on retrieval. Lexical retrieval (grep) is universal, instant, and zero-setup, but noisy: it cannot tell a definition from a call from a comment. Semantic retrieval via the Language Server Protocol (LSP) is precise and typed, but needs a running, indexed server and pays a per-symbol round-trip. The claim that semantic retrieval is more token-efficient is, we find, asserted almost everywhere and measured almost nowhere: no public source isolates the LSP-vs-lexical token delta for an agent at equal task-success. This paper formalizes the question with one metric (tokens-to-success), specifies a five-arm ablation isolating semantic retrieval from confounds, maps three pre-stated failure modes onto measurable variables, and reports a preliminary study (Python and TypeScript repos; Claude Opus 4.8, Sonnet 4.6, Haiku 4.5). The answer is conditional and usually negative. On symbol-named localization the LSP costs tokens (+6% to +118%) and the agent ignores it when free. On reference-completeness it buys precision but not token savings and cannot raise the recall ceiling set by agent thoroughness; it saves tokens only for the weakest model. Tool choice is task-dependent: models default to grep on localization (0-6% semantic use) but reach for the LSP about half the time on reference tasks, unprompted. On edits scored by real test execution the gap is starkest: grep solves multi-file renames perfectly, a location-only LSP fails three-quarters of them by missing a call site, and even a complete, index-warmed, text-enriched LSP (each reference's line inline, as production LSP-MCP servers do) recovers most of the gap but cannot close it, since a rename must touch comments and strings that semantic references exclude. The implication is not LSP-always but an adaptive router keyed on task class, model capability, and lexical noise.
### Title:
          EEG-PRISM: Physiologically-Grounded Interpretability of Predictions by EEG Foundation Models
 - **Authors:** Deeksha M Shama, Punnisa Amornsirikul, Archana Venkataraman
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Objective: Foundation models represent the next advancement in AI for EEG analysis; however current explainable AI techniques provide attribution scores in the time-channel input space, which is mismatched to clinical intuition about EEG. Thus, there is a critical need for a universal method that can extend the interpretability of any foundation model to alternative and physiologically relevant domains without modifying or retraining the underlying model. Methods: EEG-PRISM leverages linear transformations and established backpropagation rules to map time-channel attribution scores into alternative domains. We derive mappings to the frequency domain via an invertible DFT and to the source domain via an approximately invertible EEG generative model. We evaluate EEG-PRISM in simulated and real data, assessing recovery of ground-truth phenomena across domains with five foundation models and four AI explainers. Results: In simulation, EEG-PRISM achieves near-perfect spectral recovery and 69.2% spatial accuracy. In epilepsy, EEG-PRISM correctly determines that delta-theta activity is most salient and correctly localizes the seizure onset region with 50% accuracy. In autism, EEG-PRISM localizes the predictive delta-alpha biomarkers to frontal and temporal regions, consistent with prior work. Conclusion: EEG-PRISM is a theoretically-grounded post-hoc attribution method with accurate mapping into the spectral and spatial domains. It supports window-level analysis of transient events (e.g., seizures) and group-level identification of clinically relevant biomarkers (e.g., autism), thus advancing interpretable EEG foundation models. Significance: This work enables physiologically-grounded interpretation of EEG foundation models and supports clinically relevant insights such as event localization and biomarker identification.
### Title:
          Doomed to Re-Annotate, Forever: The ImageNet Story
 - **Authors:** Illia Volkov, Nikita Kisel, Tetiana Mishkina, Klara Janouskova, Jiri Matas
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Top-1 accuracy on ImageNet-1k remains the most commonly reported metric in visual recognition. Quality issues with the dataset have been repeatedly reported, yet the original 2012 noisy labels are still predominantly used. The paper presents a comprehensive effort, which goes well beyond prior correction attempts, towards obtaining accurate and complete ImageNet-1k validation set annotations. The result, ReImageNet, includes multilabel correction, object localization, revised class definitions, and semantic attributes (text-recognition, rendition, reflection, crowd, dominant). The reannotation reveals that approximately 12% of the original ImageNet-1k labels are incorrect, 33.3% of images are multilabel and 3.8% contain no object from an ImageNet-1k class. With the new labels, top-1 accuracy increases by up to 1.2% for supervised models and by 5-6% for MLLMs. We argue that annotation at ImageNet scale cannot realistically be completed in one pass, as errors and definitional issues are discovered only through annotating, and we build our pipeline around repeated refinement and error checking. We observed that human and LLM collaboration with appropriate tooling represents the current quality ceiling for annotation at this scale. ImageNet-1k issues propagate into its derivative test sets, indicating that the problem is structural rather than specific to any single benchmark. All annotations, class definitions, guidelines, and analysis code have been publicly released. Project page: this https URL Annotations: this https URL Code: this https URL
### Title:
          Source-Agnostic Image Translation Based on Latent Aware Adaptive Masking
 - **Authors:** Tomislav Dobrički, Byung-Woo Hong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this work, we propose a source-agnostic framework that dynamically refines a binary mask throughout the reverse diffusion process by computing the discrepancies of a pretrained diffusion model's prediction for each latent time step. Rather than relying on a fixed threshold, our method introduces a time-dependent statistical thresholding scheme derived from the empirical mean and standard deviation of prediction discrepancies across the latent noisy images from the target distribution. This allows the mask to adapt to the model's varying predictive confidence at different noise levels, effectively isolating domain-specific regions while preserving global structural coherence. Experimental results on the AFHQ and Celeba-HQ datasets demonstrate that our approach outperforms state-of-the-art unsupervised Image-to-Image methods in both realism (FID, KID) and faithfulness (SSIM, LPIPS). By requiring only a pretrained model of the target domain, our approach enables precise, automated localization and seamless translation across diverse source distributions without any specialized training. The project source code is available at: this https URL
### Title:
          Rethinking Automated Program Repair: The Impact of Bug Complexity, Fault Localization, and LLM Cost-efficiency
 - **Authors:** Junchi Liu, Ali Bigdeli, Roya Daneshi, Atu Ambala, Sudipto Ghosh, Fabio Santos
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Background: Software bugs remain a critical challenge in development, necessitating effective Automated Program Repair (APR) techniques. While Large Language Model (LLM)-based APR systems have shown promise, prior studies primarily focus on overall repair effectiveness. The effects of bug complexity, fault localization, reasoning settings, and repair cost-effectiveness remain insufficiently explored. Aims: This study presents a comprehensive empirical analysis of LLM-based APR, focusing on how repair performance is shaped by bug complexity, fault localization, reasoning settings, and costs. Method: We evaluate two APR techniques (ChatRepair and CodeCorrector) using three LLMs (DeepSeek, GPT, and Llama), and examine their performance across diverse levels of bug complexity and localization strategies through a multi-dimensional empirical framework and statistical analysis. Results: Although structurally complex bugs and imprecise fault localization make repair more challenging, LLM-based APR techniques still achieve competitive repair effectiveness. Imprecise fault localization can substantially enlarge the performance gap between APR techniques. Furthermore, higher-cost LLMs and stronger reasoning settings do not consistently yield better cost-efficiency, revealing a nontrivial trade-off between repair effectiveness and computational cost. Conclusions: Over 50% of moderately complex bugs can be repaired by low-cost LLM-based APR techniques. The repair effectiveness gap between APR techniques becomes larger as fault localization becomes less precise. GPT-5 repairs 7 and 39 more complex bugs than DeepSeek-V4-pro and DeepSeek-V3.2, respectively; whereas the total repair cost of DeepSeek-V3.2 shows the best cost-efficiency performance.
### Title:
          PISA: A Pseudo-Individual Source-Domain Feature Adaptation Framework for Test-Time Open-Vocabulary Object Detection
 - **Authors:** Ziyan He, Xiongtai Yang, Tao Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open-vocabulary object detection test-time adaptation (OVOD-TTA) aims to address the performance degradation that pre-trained base models suffer when encountering image-domain shifts. Existing source-free OVOD-TTA methods rely either on refined test-time information for re-scoring or on pseudo-labels for self-training, leading to significant accuracy degradation when initial predictions are poor. Meanwhile, most conventional source-domain estimation methods recover abstract, sparse representations suitable for the classification task, but fail to capture the dense, concrete features required for detection. To address these issues, we propose PISA, a novel source-free OVOD-TTA method that can be seamlessly integrated into open-vocabulary visual backbones. The core components of our method are the Corruption-Invariant Feature Extractor (CIFE), the Feature Alignment Module (FAM), and a multi-scale alignment framework (BAA). To capture detection-suitable features, we develop CIFE to exploit the invariance of CLIP's visual features across corrupted images, ensuring robustness against various corruptions. We further develop FAM and BAA for the pre-training and adaptation to transform the corruption-invariant features into pseudo-individual source-domain features that are close to the original source-domain features. In this way, dense and concrete pseudo-individual source-domain features are used for supervision instead of unreliable pseudo-label signals. Experiments on the corrupted VOC-C, COCO-C, and LVIS-C benchmarks across three base models demonstrate that PISA substantially improves both the localization precision and the category recognition accuracy of the original models. Notably, PISA achieves state-of-the-art performance without requiring access to source-domain data, surpassing existing methods by 3.92% in AP@50% on COCO-C.
### Title:
          SCVIB: Editable State-Conditioned Visual Instance Binding forMulti-Turn Personalized Localization
 - **Authors:** Xiongtai Yang, Ziyan He, Tao Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce editable state-conditioned visual instance binding, a multi-turn localization setting in which several support-defined instances are introduced across turns and protocol-defined state events determine the final target. We instantiate this setting as SCVIB, comprising 1,050 manually verified support--query base pairs and 1,500 episodes spanning five visual domains, three difficulty levels, and four target-state dependency groups. Direct Seq-free inference reaches only 60.13\% Joint@0.5, indicating that resolving the final reference does not ensure effective use of the corresponding visual evidence for query-side localization. We address this gap with TT-VG (Transition-Tree Visual Grounding), which combines a Target-State Transition Tree (TSTT) with Visual Evidence Grounding Adaptation (VEGA). TSTT compiles the visible interaction into protocol-defined events, executes them over versioned target states, and resolves the final-query reference to the corresponding support evidence. Adapted on trajectory-derived same-instance pairs, VEGA performs support-conditioned grounding of the resolved instance using a Visual Evidence Package. TT-VG reaches 70.27\% Joint@0.5; under matched target resolution, VEGA exceeds the strongest comparison method by 16.20 points. Gains over direct inference are largest on Counter-Recency and Rollback, which require routing to non-latest or restored support evidence. Together, these results establish SCVIB as a controlled testbed and highlight the effective use of resolved support evidence for query-side same-instance localization as a central challenge in multi-turn personalized localization.
### Title:
          LightTeaNet: A Weakly Supervised Lightweight CNN for Multi-Label Tea Leaf Disease Detection and Localization
 - **Authors:** Naif Haider Chowdhury, Md Rahim, Syed Farhan Hasan, Murad Hasan, Prithwiraj Bhattacharjee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tea is known as an important crop in many parts of South and Southeast Asia, yet the production of tea is still hampered by the multiple diseases that decrease the quantity and quality. Traditional methods of inspection, which are manual, are not consistent, labor-intensive, and depend on extensive monitoring. This paper introduces a lightweight convolutional neural network (CNN) designed for weakly supervised multi-label classification and disease localization in tea leaves called LightTeaNet. LightTeaNet learns directly from image-level labels and employs Class Activation Mapping (CAM) to localize disease-affected regions automatically, unlike conventional object detection models such as YOLO, which require extensive bounding box annotations. For Parameter efficiency, the network integrates Depthwise Separable Convolutions, and for enhanced feature discrimination, it integrates Channel Attention. LightTeaNet has achieved a Precision of 0.9615, a Recall of 0.8772, and an F1-score of 0.9179, while it shows mAP@0.50=0.1810 without any manual annotations, which delivers a competitive localization performance in the experimental results. These results validate the model as an interpretable as well as a resource-efficient framework for intelligent disease monitoring in agriculture.
### Title:
          Positioning with Flexible Reflectors: Solution and Performance Analysis
 - **Authors:** Jiajun He, Han Yu, Danyan Lin, Gaofeng Pan, Hing Cheung So, Stefano Buzzi, Hien Quoc Ngo
 - **Subjects:** Subjects:
Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Flexible reflectors (FRs) have emerged as a low-cost and energy-efficient solution for reshaping electromagnetic propagation environments across a wide range of applications. This paper investigates FR-swarm-assisted target localization in scenarios where line-of-sight (LoS) paths are unavailable. By leveraging the virtual LoS paths created by the FRs, a simple yet accurate estimator is proposed for localization under severe blockage conditions. To characterize the performance limits of the proposed scheme, we derive the Cramer-Rao lower bound (CRLB) and use it to optimize the positions and orientations of the FRs. Furthermore, by accounting for random FR deployment, we characterize the CRLB distribution and reveal how different network configurations affect localization accuracy. Simulation results demonstrate that the developed scheme closely approaches the CRLB performance, while the derived analytical results provide useful guidelines for FR deployment and network design.
## Keyword: transformer
### Title:
          BCMT: Blockwise Causal Memory Transformer
 - **Authors:** Rachid Arezki
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer architectures rely on dense self-attention to model long-range dependencies, but this mechanism exhibits quadratic complexity with respect to sequence length. We introduce BCMT (Blockwise Causal Memory Transformer), an architecture for long-context language modeling that decouples local token interactions from global context propagation. Dense causal self-attention is applied independently within local blocks, while each block produces an adaptive summary aggregated through an exponential causal memory. This memory is subsequently injected back into the token representations, enabling efficient propagation of long-range contextual information without relying on explicit global attention. Unlike standard Transformers and recurrent memory architectures, BCMT maintains neither dense interactions between distant tokens nor learned memory states. Its memory mechanism is fully parallelizable and remains compatible with standard implementations of dense self-attention. Experiments on language modeling with context lengths of up to 1024 tokens show that BCMT achieves validation performance comparable to that of Dense Transformers while significantly improving training throughput and reducing memory consumption. An ablation study further confirms that these improvements arise from the proposed memory mechanism. These results demonstrate that an exponential causal memory constructed from block summaries provides an effective alternative to dense global attention mechanisms for long-context language modeling.
### Title:
          SAGE: Surrogate-gradient Adaptation via Attention-Guided Entropy for Spiking Transformers
 - **Authors:** Kiran Nair, Rodrigue Rizk, KC Santosh
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spiking neural networks (SNNs) offer an energy-efficient alternative to conventional deep neural networks by exploiting sparse event-driven computation, but their training remains challenging because the non-differentiable spike function requires surrogate gradients whose fixed shape may be suboptimal across layers and training stages. In this work, we introduce SAGE, an uncertainty-modulated surrogate-gradient mechanism for Transformer-based SNNs. SAGE estimates block-level uncertainty from normalized self-attention entropy and uses this signal to adapt the surrogate-gradient slope during training while leaving the inference model unchanged. By modulating only the training-time surrogate parameter, the proposed method preserves the original architecture and deployment cost while improving optimization flexibility. Experiments on CIFAR-10/100 demonstrate that SAGE achieves improved accuracy over fixed-surrogate baselines, with results up to 1-2\% consistent gains across multiple simulation time steps. These results highlight the potential of attention-derived uncertainty as a lightweight training signal for adaptive surrogate-gradient learning in transformer-based SNNs.
### Title:
          Architecture and Affordances of PLAUD: Performative Latents and Unsupervised DDSP
 - **Authors:** Błażej Kotowski, Frederic Font
 - **Subjects:** Subjects:
Sound (cs.SD); Human-Computer Interaction (cs.HC); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 PLAUD (Performative Latents and Unsupervised DDSP) is a neural synthesizer and Max for Live instrument for live electronic music, built on NoiseBandNet and trained on small personal sound corpora. We present its architecture, combining a variational DDSP synthesis model, latent smoothing, multi-scale spectral and adversarial losses, and an optional transformer prior, alongside a set of bending operations that intervene directly in the synthesis chain: component limiting, waveshaping, and prior feedback. The Max for Live interface exposes control generation, trajectory sampling, and modulation as primary modes of interaction. Throughout, we thread an affordance analysis arguing that the system's performative character follows from architectural decisions rather than being designed on top of them. The paper contributes both a technical account of the system and a situated affordance analysis of its role in live electronic music performance.
### Title:
          Dynamic Multi-Depot Vehicle Routing with Online Requests: Event-Driven Transformer--DRL and Rolling-Horizon Benchmarking
 - **Authors:** Faezeh Ardali, Gerald M. Knapp
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents an event-driven learning and benchmarking framework for the Dynamic Multi-Depot Vehicle Routing Problem with progressively revealed requests and evolving vehicle states. Masked MLP and Transformer policies are trained through behavior cloning and proximal policy optimization. Deterministic feasibility masking prevents invalid vehicle--request assignments, while fixed-prefix/flexible-suffix route commitments protect completed, active, and near-term decisions and separately measure vehicle reassignment and resequencing. The learned policies are compared with dynamic insertion heuristics and time-limited rolling-horizon optimization. In a 20-scenario policy benchmark, all methods completed every request without invalid actions, but nearest feasible achieved the lowest mean objective and outperformed the learned policies in routing quality, waiting time, stability, makespan, and runtime. Across five independent training runs, PPO had little average effect on the MLP and improved the Transformer on average, although with greater seed variability. Under the common protocol, nearest feasible achieved the lowest combined objective and route disruption, whereas rolling horizon achieved the lowest waiting times and makespan at substantially higher computational cost. The learned policies retained millisecond-level decisions and transferred to instances with up to 80 requests without retraining, but did not outperform the strongest heuristic. No single method was best across routing efficiency, service responsiveness, stability, and online computation.
### Title:
          Optimal Power Allocation and AI Receiver Design for Superimposed DMRS and Data Transmission
 - **Authors:** Sha Hu, Zhongwang Fu
 - **Subjects:** Subjects:
Information Theory (cs.IT); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we consider transmissions with superimposed (SI) demodulation-reference-symbol (DMRS) and data in orthogonal frequency-division multiplexing (OFDM) based multiple-input multiple-output (MIMO) systems. First, we derive an analytical framework to characterize the iterative behavior between the mean-square errors (MSEs) of channel estimation (CE) and MIMO detection (MD) within an iterative CE and detection (ICED) process. This framework is subsequently utilized to optimize power allocation and pilot patterns between the DMRS and data symbols for SI-DMRS transmission. Second, we design an artificial intelligence (AI) based receiver built upon Transformer encoders for SI-DMRS transmissions, which incorporates an iterative CE and detection (ICED) structure. Simulation results demonstrate that the proposed AI-ICED receiver, combined with SI-DMRS, effectively increases spectral efficiency (SE) compared to conventional systems using non-overlapped DMRS and data symbols.
### Title:
          Attention Capture Is Not Detection: A Two-Stage Account of How Humans Miss Localized AI Image Edits
 - **Authors:** Chiao-Chieh Deng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As AI-generated image edits proliferate, the platforms meant to curb the resulting disinformation treat detectability as a single, undifferentiated property: an edit either gets a warning or it does not. We show this is the wrong model. Across a controlled eye-tracking study ($N=59$, Latin-square design, four conditions crossing edit area and semantic plausibility), a mixed-effects analysis reveals that whether an edit is noticed and whether it is correctly judged as fake are dissociable stages, governed by different factors: edit area drives attention capture ($p<0.001$) while semantic plausibility drives judgment accuracy and look-but-fail-to-see (LBFS) error rates ($p<0.001$). This dissociation survives correction for multiple comparisons; a secondary interaction between the two factors does not. This two-stage account extends a long-standing distinction in visual attention research (between pre-attentive capture and effortful recognition) into the new domain of AI-edit detectability. We then test whether a generative eye-movement model can computationally operationalize the attention-capture stage: a Transformer trained to generate scanpaths tracks per-image attention with strong discriminative power (Pearson $r=0.77$--$0.82$ across held-out stimuli) and, on the harder task of predicting LBFS incidence, modestly outperforms a two-parameter linear baseline even without access to the plausibility label ($r=0.52$ vs. $r=0.48$). We report this comparison, our ablations, and our method's limitations (a single fixed train/validation split, not leave-one-subject-out) without inflation, consistent with responsibly communicating what a machine learning system can and cannot do to help curb AI-driven disinformation.
### Title:
          CoSA: Context-Aware Severity Assessment via Context Analysis with Large Language Models
 - **Authors:** Jinfeng Jiang, Yikun Li, Chengran Yang, Ting Zhang, Wen Bin Leow, Yide Yin, Eng Lieh Ouh, Lwin Khin Shar, David Lo
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate vulnerability severity assessment is essential for prioritizing remediation, yet manually assessing Common Vulnerability Scoring System (CVSS) base metrics remains labor-intensive. Existing automated approaches often fail to capture the repository-level evidence required for assessing many CVSS base metrics. Such repository-aware assessment is challenging because relevant evidence is scattered across the entire repository under heavy noise. To address these challenges, we present CoSA, a Context-aware vulnerability Severity Assessment approach that infers CVSS base metrics from repository artifacts. CoSA constructs a code property graph (CPG) and applies a two-stage repository-pruning strategy: lightweight static pruning to preserve structurally proximal context, followed by an agentic large language model (LLM)-guided pruning step to retain CVSS-relevant context while collecting supporting evidence. The LLM then consolidates the retrieved repository context into compact, CVSS metric-wise textual summaries, which are fed into a lightweight transformer predictor. We also construct a higher-quality repository-level dataset comprising 6,816 CVSS labeled instances spanning 90 Common Weakness Enumeration (CWE) types. Experiments on real-world vulnerabilities show that CoSA consistently outperforms function-level and pure-LLM baselines. It improves prediction accuracy by 14.4% and Macro-F1 by 15.3% over the best-performing baseline, suggesting that explicit, metric-oriented repository context retrieval is crucial for practical and reliable automated severity assessment.
### Title:
          RGBX-Next: Towards Realistic Generative Rendering from G-Buffers
 - **Authors:** Zheng Zeng, Marco Salvi, Lifan Wu, Jan Novák, Daqi Lin, Saeed Hadadan, Yichen Sheng, Robert Pottorff, Shiqiu Liu, Ravi Ramamoorthi, Ling-Qi Yan, Miloš Hašan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion models have achieved impressive results in image, video, and streaming generation. However, compared to traditional 3D rendering, they still lack precise control over the generated output. We believe a viable path forward is to use generative models as learned renderers conditioned on traditionally rendered G-buffers. We introduce RGBX-Next, a unified generative framework for forward and inverse rendering, which allows estimating G-buffers from images, videos, and streams, and rendering realistic images, videos, and streams from G-buffers. Our key contribution is a general recipe for finetuning diffusion transformer (DiT) models into generative forward and inverse renderers. We show that the resulting models achieve high quality in both realistic generative rendering and intrinsic decomposition. We will make all our models publicly available. We believe that the design principles presented in this paper will benefit future research on controllable generative forward and inverse rendering.
### Title:
          Reducing ANN-SNN Conversion Error via Residual Membrane Potential Alignment
 - **Authors:** Zirui Chen, Zihan Huang, Tong Bu, Jianhao Ding, Yiting Dong, Zhaofei Yu
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spiking Neural Networks (SNNs) serve as core architectures for neuromorphic computing thanks to event-driven operation and ultra-low power consumption. Direct SNN training is hindered by non-differentiable spikes that induce vanishing gradients and unstable optimization. ANN-SNN conversion circumvents such issues by reusing well-trained ANN weights for low-latency, energy-efficient inference. Nevertheless, existing conversion schemes suffer from severe accuracy drops at small timesteps, large inference delays and cumulative quantization errors, even with marginal performance loss at large $T$. To address these limitations, we first analyze flaws of conventional conversion pipelines from residual membrane potential statistics and propose a novel conversion strategy combining dynamic initial potential tuning and feature enhancement. We then introduce a regularization loss $\mathcal{L}_{\mathrm{RMPD}}$ to adapt initial potential of IF neurons and mitigate systematic truncation bias from boundary aggregation. A dedicated SCR-Conv2d competitive refinement layer with grouped convolution is further built to sharpen feature discrimination, eliminate redundant spikes and stabilize encoding under tiny time windows. Integrated with the state-of-the-art QCFS baseline, our approach delivers consistent low-latency performance gains and generalizes to ReLU CNNs, ANN Transformers, and multi-threshold SNN variants. Evaluations on CIFAR-10, CIFAR-100 and ImageNet verify prominent accuracy improvements at $T=2,4,8$, with negligible extra computation overhead. This work offers an effective conversion paradigm to facilitate real-world SNN deployment on neuromorphic chips.
### Title:
          PPOM: Marginalizing Patch-Grid Phase for CLIP-Based Generalizable Vision-Language Prompt Tuning
 - **Authors:** Liang Wang, Haoyang Li, Chao Wang, Guodong Long, Jing Jiang, Yan Peng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Prompt tuning adapts CLIP-based vision-language models with few trainable parameters, yet its predictions remain sensitive to the spatial sampling imposed by a frozen vision transformer. In particular, non-overlapping patch tokenization makes predictions depend on the alignment (phase) between image and the patch lattice. To reduce prediction sensitivity to patch-grid alignment, we introduce Patch-Phase Orbit Marginalization (PPOM), a training-free inference operator that treats phase shift as a nuisance variable. Given a patch stride, PPOM evaluates the identity view and reflection-padded translations, pairs opposite shifts into horizontal, vertical, and diagonal antithetic families, and assigns equal mass to these families and the identity prediction to avoid view-count bias during phase integration. In summary, PPOM provides a deterministic interface between prompt adaptation and patch-grid sensitivity. Across multiple prompt-learning hosts, PPOM improves host performance without re-training.
### Title:
          Nanbeige4.2-3B on Apple Silicon: Fixing Deployment Bugs and Decreasing Looped Transformer Memory Overhead
 - **Authors:** John T. Halloran
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Nanbeige4.2-3B is a 3B-parameter agentic model built around a Looped Transformer (LT) that reuses one stack of layers for a second forward pass, adding effective depth without additional parameters. Evaluated on Apple Silicon (MPS), we identify five independent bugs which prevent the released checkpoint from running via Hugging Face transformers out of the box (including a silently-zeroed RoPE buffer and calls to removed transformers cache APIs). Furthermore, we show that fixing these bugs is still not sufficient for agentic tasks, due to the LT's layer-reuse strategy (which effectively doubles peak attention memory) used to achieve parameter efficiency. We thus introduce a chunked-prefill strategy which alleviates the incurred memory-capacity penalty, extending allowable context width by $2.7 \times$ on 32~GiB shared memory. However, even with the reduced memory overhead, we show that patches are required to render Nanbeige4.2-3B usable; resolving both system prompt and MPS-native memory bugs finally allows reliable evaluation on standard MCP and tool-calling benchmarks. On a subset of MCPMark, the debugged model completes up to 30\% of real agentic tasks (up from the original's 0\%), while, on BFCL, it is near-perfect at single tool calls (yet fails the majority of multi-tool tests). We release the patched checkpoint, system prompt optimizer, and evaluation harnesses at this https URL.
### Title:
          Residual Dominance as a Structural Account of Last-Item Reliance in Causal Self-Attention Recommenders
 - **Authors:** Keito Kozaki, Keigo Sakurai, Ren Togo, Takahiro Ogawa, Miki Haseyama
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based sequential recommenders with causal self-attention often rely heavily on the most recent interaction at inference time, but how this behavior is structurally expressed in the representation used for prediction remains unclear. We combine prediction-time diagnostics with norm-based analysis of the full attention block. First, we show that SASRec-style models exhibit highly localized last-item reliance. We then find that, although self-attention aggregates contextual information, residual addition sharply shifts the full-block representation toward same-position contributions, which we term residual dominance. To probe this interpretation, we use inference-time residual scaling as a controlled diagnostic intervention. Changing the residual strength induces a monotonic trade-off between structural mixing and last-item reliance, while reducing residual strength recovers a subset of final-position misses for which representations at non-final positions already rank the ground-truth item correctly. Our results provide a structural account linking extreme last-item reliance to residual dominance at inference time. The code is publicly available.
### Title:
          Beyond Text Conditioning: A Systematic Study of MLLM-DiT Fusion for Video Generation
 - **Authors:** Yanbo Ding, Yijia Fan, Caihua Shan, Yifan Yang, Yifei Shen, Weijie Wang, Xirui Hu, Dongsheng Li, Lili Qiu, Yuqing Yang, Yali Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformers (DiTs) have become the dominant paradigm for high-fidelity video generation, yet their ability to perform high-level semantic planning remains limited. While hybrid architectures integrating MLLMs with diffusion backbones have shown strong advantages in image synthesis, such designs remain underexplored in video generation, where existing approaches often treat MLLMs primarily as frozen feature encoders rather than semantic generators. To fill this gap, we systematically study how an MLLM should be integrated with a DiT for video generation by answering three questions: what intermediate representation should bridge the MLLM and DiT, how the MLLM should generate it, and how the DiT should incorporate it during diffusion rendering. Our analysis reveals three key findings: (1) discrete semantic visual tokens produced by an EMA-based tokenizer provide a stable and expressive interface, (2) autoregressive causal modeling is effective for generating these tokens, and (3) explicit visual-token conditioning is more effective than prompt refinement or latent bridging. Based on these findings, we propose BiVidGen, a hybrid framework where an MLLM first generates semantic visual tokens and a DiT renders videos conditioned on both text and these tokens via multi-layer cross-attention. Extensive experiments show that BiVidGen improves semantic alignment and temporal coherence over a fine-tuned DiT baseline, achieving stronger performance on VBench-Long. These results demonstrate that explicit MLLM-based visual planning provides an effective intermediate interface for text-to-video generation beyond text-only conditioning.
### Title:
          InstructVVT: Instruction-Driven Video Virtual Try-On without Auxiliary Spatial Priors
 - **Authors:** Dingbao Shao, Song Wu, Xinyu Chen, Qian Wang, Jiahang Li, Kuai Jiang, Jiang Lin, Yuhang Liu, Ziyu Chen, Duo Li, Jiaxin Hu, Shengrong Gu, Ziheng Tang, Rongrong Liu, Yanlun Peng, Liang Li, Junlan Feng, Lujia Jin, Ting Zhang, Jian Yang, Zili Yi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video virtual try-on is a highly constrained editing task requiring the precise replacement of a target person's clothing while strictly preserving the original video's spatial structure and temporal dynamics. Existing methods heavily rely on auxiliary handcrafted spatial priors (e.g., masks, poses) for editing control. However, these priors are prone to failure in unconstrained real-world videos and often compress rich visual context into incomplete structural signals. Furthermore, standard reconstruction objectives fail to fully capture try-on-specific human preferences. To address these challenges, we propose InstructVVT, an instruction-driven and reference-guided video virtual try-on framework based on a Diffusion Transformer (DiT) that operates without inference-time spatial priors. Our core insight is to recover fine-grained control directly from the input triplet (source video, reference garment, and instruction) via a dual-level reference conditioning scheme. Specifically, an MLLM infers semantic edit tokens for target disambiguation and structural preservation, while a lightweight conditioning pathway explicitly injects fine-grained visual garment details. Finally, we design a try-on-specific reward and utilize the DiffusionNFT algorithm to align the model with human preferences. Extensive experiments on ViViD-S and TripVVT-Bench demonstrate that InstructVVT outperforms state-of-the-art open-source methods in garment fidelity, structural preservation, and temporal consistency, despite requiring fewer inference-time controls.
### Title:
          BGA: A noise-immune neural distillation framework for malicious signature extraction in high-entropy encrypted flows
 - **Authors:** Sheng Hong, Yixuan Huang, Weiwei Jiang, Junyuan Zhang, Jiacheng Wang, Ruijian Jiao
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 To mitigate attention dilution in high-entropy TLS 1.3 flows, we propose BGA, a noise-immune neural distillation framework for encrypted threat this http URL methodology first employs Analysis of Variance (ANOVA) to decouple high-discriminatory control-plane features - specifically industrial setpoints - from stochastic cryptographic noise. To resolve the extreme class imbalance within a corpus of 86,878 flow records, a Wasserstein GAN with Gradient Penalty (WGAN-GP) module, enforcing the 1-Lipschitz constraint, is integrated to synthesize high-fidelity minority samples, elevating the detection recall of rare Malicious State Command Injections(MSCI) attacks by 43.2%. At its core, the BGA architecture integrates Bidirectional Long Short-Term Memory (BiLSTM) for temporal dependency extraction and an Adaptive Gated Multi-Head Attention mechanism. This gated unit functions as a neural filter to dynamically suppress encryption artifacts while amplifying malicious signatures. Extensive evaluations on CIC-IDS-2018 and Edge-IIoT benchmarks demonstrate a performance ceiling exceeding 95.2% across all key metrics. Furthermore, noise-injection stress tests confirm BGAs superior structural resilience with a 8.57% performance margin over vanilla Transformers, while its ultra-low inference latency of 0.2820 ms (estimated 1.6920 ms via theoretical scaling for ARM) indicates a high potential for real-time feasibility on heterogeneous industrial edge gateways, providing a promising architectural baseline for future hardware implementation.
### Title:
          Revisiting Energy-based Tabular Anomaly Detection: Energy and Reconstruction are Complementary
 - **Authors:** Junichiro Niimi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tabular anomaly detection is dominated by classical density-proxy methods (Isolation Forest, OCSVM, LOF), reconstruction-based detectors (Autoencoders, VAEs), and modern non-parametric scorers (COPOD, ECOD, Deep SVDD), all of which approximate the inlier distribution only indirectly; explicit energy-based models are largely absent. Motivated by the recent revival of EBMs in deep learning (e.g., Energy-Based Transformers, JEPA), we revisit the classical Deep Boltzmann Machine (DBM) for this task and hypothesize that its mean-field energy combines more effectively with a reconstruction-based score than same-lineage pairs do. We evaluate a two-hidden-layer DBM on two tabular benchmarks spanning distinct domains (UCI Bank Marketing and NSL-KDD) against eight classical and modern baselines across twenty random seeds. The DBM mean-field energy matches the strongest baseline (the Autoencoder) on Bank Marketing and statistically beats it on NSL-KDD, while significantly outperforming the remaining seven on both datasets. When fused with the Autoencoder via rank fusion, the DBM energy yields a statistically significant improvement on both datasets (AUROC=+0.014, p<0.01 on Bank Marketing; +0.002, p<0.001 on NSL-KDD); every non-DBM-derived base model instead fails to improve or significantly degrades the AE-paired ensemble. Our position is that classical EBMs, exemplified by the DBM, deserve a place in the tabular anomaly detection toolbox as a non-redundant complementary view to the reconstruction-based scores that dominate current practice.
### Title:
          Intern-S2-Mobius: Foundation Model with Decoupled Knowledge and Reasoning
 - **Authors:** Kai Chen, Jifeng Ding, Ning Ding, Jiaye Ge, Lixin Gu, Yicheng Gu, Qipeng Guo, Ermo Hua, Haian Huang, Haozheng Hou, Jie Hou, Xiangyu Hong, Che Jiang, Minxi Jin, Cheng Liang, Dahua Lin, Dawei Liu, Kuikun Liu, Chengqi Lv, Haijun Lv, Han Lv, Ningsheng Ma, Biqing Qi, Jianmin Qian, Shiya Su, Youbang Sun, Huanze Tang, Zhongbo Tian, Hanjing Wang, Rui Wang, Ting Wang, Yi Wang, Baiting Wu, Jun Xu, Bowen Yang, Hui Wang, Weida Wang, Haochen Ye, Jiashuo Yu, Shan Yu, Xiaoyi Yu, Qirui Zeng, Qi Zhang, Ming Zhang, Wenwei Zhang, Bowen Zhou, Xinyu Zhou
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Mobius-v0, an architecture that comprises a globally shared Memory (FFN) that stores knowledge vectors and multiple Reasoners (Self-Attn) that iteratively achieve compositional reasoning. Using hidden states as cache and carrier, reasoners repeatedly query memory for required knowledge-vectors, while the knowledge is transmitted back to reasoning operators. Through this knowledge-reasoning-separation architecture, Mobius achieves better knowledge compression and reasoning efficiency. Built upon Mobius-v0 architecture: 1) Our 7B model trained-from-scratch achieves similar downstream score as a 7B Transformer baseline with 62.6% of baseline's training data. 2) Our Intern-S2-Mobius, continually-pretrained from Qwen3.5-35B, achieves similar downstream score while delivering nearly 4x end-to-end inference speedup.
### Title:
          TRIAGE: Risk-Controlled Pseudo-Label Admission for Annotation-Efficient Semi-Supervised Retinal OCT Classification
 - **Authors:** Md Ashraful Hossen Akash, Shyla Afroge, Abdullah Al Mamun, Md. Kishor Morol, Tze Hui Liew
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The advanced retinal disease diagnosing imaging modality, optical coherence tomography (OCT), encounters a lack of automation because of the high expenses for annotations performed by specialists. The use of SSL solves the problem of insufficient annotations using unlabeled B-scans; however, most of the current techniques for generating pseudo-labels are based on prediction confidence without considering the asymmetry between different types of errors. This paper proposes TRIAGE, a risk-controlled semi-supervised framework for OCT scans classification, which uses the concept of a patient-level conformal risk controller with an asymmetric cost matrix. TRIAGE unites three crucial modules: a hierarchical classifier that is capable of working with partially abnormal supervision of the disease subtypes, a patient-grouped conformal risk controller with primal-dual coverage control, and a context-aware Transformer teacher for cross-slice verification. On the dataset from Noor Eye Hospital (16,822 B-scans, 161 patients, and 554 volumes) with a test set of unseen patients, TRIAGE demonstrates 89.66% scan-level accuracy, 0.8805 macro-F1, 0.9641 macro-AUC, and an 8.34% under-grading rate when using only 20% of the labeled data. With only 5% of the labeled data, TRIAGE keeps 76.88% accuracy and a 0.1656 under-grading rate. Compared with the other six state-of-the-art semi-supervised methods, TRIAGE significantly outperforms them with ablation study demonstrating the contribution of each module in the overall framework performance (by 42.7% in terms of under-grading rate comparing to fixed threshold methods). TRIAGE demonstrates 98.00% accuracy for 3-class classification with 1% labeled data and 95.94% accuracy for 8-class classification with 10% labeled data on the OCT-C8 dataset.
### Title:
          A Four-Axis Trustworthiness Benchmark for LLM-as-Judge in Principle-Based Regulation
 - **Authors:** Dipankar Sarkar
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Computers and Society (cs.CY); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Principle-based regulation, with evaluative standards such as "fair, clear, and not misleading" or "deliver good outcomes", cannot be reduced to binary predicates, and LLM-as-judge is increasingly used as the substitute. Our position is that any such judge must be evaluated on four axes: accuracy, paraphrase robustness, adversarial robustness, and calibration. We release Principle-Bench, 168 cryptoasset financial-promotion scenarios mapped to two UK FCA principles, with paraphrase, adversarial keyword-stuffing, and boundary perturbations authored under a pre-registered rubric; the first benchmark covering all four axes for principle-based regulation. We also introduce Ceca (Calibrated Exemplar-Cluster Assessment): a calibrated, auditable assessor that emits exact per-exemplar counterfactual attributions. Across keyword counting, three sentence-transformer embedders, an open-weight LLM-judge, and a calibrated cascade, no method dominates all four axes. A 120B LLM-judge, strongest on benign inputs, loses 47 accuracy points (0.74 to 0.27) on keyword-stuffed Consumer Duty inputs: "compliance theatre." A second judge from a different model family agrees only at Cohen's kappa = 0.16 on that split, localising the failure to the model rather than the corpus. Any deployment-grade LLM-judge for principle-based regulation must report per-principle adversarial deception and post-hoc calibration alongside aggregate accuracy.
### Title:
          Non-Parametric Spatiotemporal Trajectory Prediction via State-Conditioned Transition Sampling
 - **Authors:** Michael Fore, Akshay Jain, Justin Downes, Rohan Pradhan, Duncan Botti
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a training-free method for multi-modal trajectory prediction that achieves comparable accuracy to a 57M-parameter transformer while requiring no GPU and zero learned parameters. The method builds a transition table of historical state-to-next-position pairs and retrieves neighbors using a product kernel over spatial proximity, bearing, speed, and temporal context. Two inference modes operate over this shared representation: diversity-penalized sampling produces trajectories covering distinct plausible routes, while beam search finds the highest-likelihood path. On the TrAISformer benchmark (Danish Maritime AIS), our method achieves competitive accuracy at full data availability and dramatically outperforms the transformer in data-scarce regimes---remaining stable down to 10% of training data where TrAISformer degrades catastrophically. This enables deployment in new geographic regions from an order of magnitude less historical data, and with no GPU training.
### Title:
          LLMs Don't Pay for the Jump
 - **Authors:** Paras Balani, Subhrakanta Panda
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Zahavy [2026] argues that Large Language Models, despite their capabilities in induction and deduction, cannot perform the abductive "Jump" that produced Einstein's equivalence principle, and attributes this limitation to the absence of embodied simulation. Zheng-Xin [2026] and Farmer [2026] question whether embodiment is necessary for abduction, pointing to alternative routes to General Relativity and forms of abduction that require no sensorimotor grounding. Max Planck resolved the blackbody radiation problem in 1900. Planck's move to E = h{\nu} required no embodied simulation. It was motivated by a mathematical consequence of classical theory, an infinite predicted energy for a finite measured quantity, that could not be physically accepted. We show that neither induction nor deduction could have produced the postulate and argue that its adoption required a coupling between epistemic error and physical cost. We formalize this distinction through thermodynamic coupling and show that fixed-weight transformer inference lacks such coupling, regardless of model scale. This is consistent with empirical results showing that output entropy remains nearly unchanged across tasks with sharply increasing causal difficulty, even as accuracy falls from 100% to 17%. We therefore argue that the missing ingredient in machine abduction may lie deeper than embodiment: a system must have some physical mechanism through which epistemic error becomes costly enough to force revision.
### Title:
          CRAFT: Constrained Reward via Attention Fine-Tuning for Subject Personalization without Composed Targets
 - **Authors:** Jihun Park, Kyoungmin Lee, Jongmin Gim, Hyeonseo Jo, Jaeyeul Kim, Han Zou, Zhenpeng Zhan, Yan Zhang, Sunghoon Im
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Subject-driven image personalization---generating new images that preserve the identity of one or several reference subjects in novel scenes---is a foundational capability for modern visual content creation. It is currently dominated by generalized methods that fine-tune a pretrained multimodal diffusion transformer (MMDiT) on hundreds of thousands to millions of paired \emph{(reference, composed-target)} examples, where each composed target is a synthesized image of the subject in a novel scene. Producing such targets demands a costly multi-stage curation pipeline---LLM-based prompt generation, T2I-based composed-target synthesis, reference-subject extraction, VLM-based quality filtering, and correspondence labeling---and tightly couples each method to a particular target synthesizer and curation choice. We introduce \emph{CRAFT} (Constrained Reward via Attention Fine-Tuning), a single-step ReFL framework that fine-tunes a pre-trained \emph{reference-aware} MMDiT via LoRA adapters using a compact reference-only data construction---$10$K reference images and subject masks, with no composed-target supervision. CRAFT realizes a \emph{Where to look} principle: attention-level rewards align noise- and phrase-token attention with the correct reference subject, and the resulting per-subject attention masks gate a pixel-level identity reward to keep image-space supervision consistent with the learned attention routing. Applied to FLUX.2-klein-9B, CRAFT achieves state-of-the-art performance on XVerseBench \rev{while using no composed-target supervision---only $10$K reference-only samples, whereas prior generalized methods require $150$K to over $2$M composed-target pairs}. The same recipe transfers to other reference-aware backbones, consistently improving performance. Project page: this https URL.
### Title:
          Designing Compact Neural Architectures via Neuron Gating and Mixed Activation
 - **Authors:** Abhishek Shukla, Ankur Sinha, Faiz Hamid
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural Architecture Search (NAS) is naturally formulated as a bilevel optimization problem, where the upper-level optimizes the architecture using validation performance and the lower-level trains network parameters using training loss. However, NAS is computationally expensive due to discrete architectural decisions, exponentially growing search spaces, and the high cost of training candidate architectures. This work develops a general bilevel optimization framework for NAS across diverse architectures, including MLPs, CNNs, RNNs, and Transformers, to identify compact architectures with strong predictive performance. We propose three scalable formulations that replace discrete neuron- and activation-level decisions with continuous relaxations, enabling differentiable optimization over otherwise combinatorial architecture spaces. These formulations give rise to three NAS methods: NAS based on Neuron Gating (NAS-NG), NAS based on Mixed Activation (NAS-MA), and NAS based on Neuron Gating and Mixed Activation (NAS-NGMA). Experiments on MLPs and CNNs using MNIST and CIFAR-10 show that the proposed methods consistently identify compact architectures with competitive or improved predictive performance. On MNIST, NAS-NGMA achieves 98.68% test accuracy with 7.69M MLP parameters, while NAS-NG achieves 99.63% accuracy with only 0.26M CNN parameters. On CIFAR-10, the proposed methods consistently outperform vanilla DARTS. Further experiments demonstrate that NAS-NG can optimize substantially over-parameterized and literature-optimal architectures, improving accuracy while reducing parameters. These results establish relaxed bilevel optimization as a scalable alternative to discrete NAS and provide a general framework for efficient neuron- and activation-level architecture optimization.
### Title:
          Generating Benchmark Health Data Using a Tabular Diffusion Transformer
 - **Authors:** Hao Yan, Lisa Pilgram, Dan Liu, Linglong Kong, Fida Dankar, Khaled El Emam
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-Tabular Data Generation (CTDG) seeks to learn a generative model from multiple heterogeneous tables and produce new synthetic tabular datasets. However, existing synthetic tabular data generation methods are largely restricted to single-input-table scenarios and struggle to effectively handle multiple heterogeneous tables with diverse feature sets. To address this limitation, we propose a two-stage framework for cross-tabular data generation. In the first stage, each heterogeneous raw table is transformed into a standardized statistical table with the same set of columns across all tables. Each statistical table captures the marginal distributions of the original columns and the pairwise correlations among them. In the second stage, a diffusion transformer model is trained to capture structural patterns across these homogeneous statistical tables and to generate synthetic statistical tables. Synthetic raw tables are subsequently reconstructed from the generated statistical tables via multivariate Gaussian sampling followed by an inverse probability integral transform. This two-stage CTDG framework enables the learning of a unified generative model from multiple heterogeneous tables and supports the generation of an unlimited number of realistic synthetic heterogeneous tables. Experimental results demonstrate high fidelity in the learned statistical representations and a favorable fidelity-diversity trade-off in the generated synthetic data, validating the effectiveness of the proposed approach.
### Title:
          RecipeNet: A Hierarchical Transformer for Recipe Data
 - **Authors:** Pin-Yen Huang, Sachin Chhabra, Prasanth Sai Gouripeddi, Abhinav Kumar, Baoxin Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recipe data arises in domains such as materials synthesis, pharmaceutical formulation, and industrial manufacturing, where procedures are represented as ordered sequences of steps containing heterogeneous structured fields. Existing tabular learning methods typically flatten this structure into fixed-schema representations, limiting their ability to capture hierarchical field interactions and procedural dependencies. We propose RecipeNet, a hierarchical Transformer architecture that encodes field-level interactions within each step and sequential dependencies across steps through stacked Transformer encoders. Experiments on multiple recipe datasets and tasks demonstrate that RecipeNet consistently outperforms existing tabular models, highlighting the value of hierarchical and sequential modeling for recipe representation learning.
### Title:
          Learning-to-Transition for Large-scale and High-Order MIMO Detection
 - **Authors:** Yubo Zhang, Yiyao Liu, Xiaodong Wang
 - **Subjects:** Subjects:
Information Theory (cs.IT); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-order multiple-input multiple-output (MIMO) detection requires efficient search over a large discrete symbol space while producing reliable soft information for channel decoding. This paper develops a learning-to-transition (L2T) framework that formulates MIMO detection as a stochastic sequence of complete-vector transitions. At each transition, a channel-coupled Transformer updates both the instance embedding and the sampling policy, while a blockwise autoregressive factorization captures inter-stream dependence with moderate sequential complexity. For hard-output detection, a transition network is applied recursively and trained through a residual-to-BER curriculum, which first learns the MIMO search geometry from the exact residual metric and then aligns the policy with transmitted-bit accuracy. For soft-output reception, the well-trained hard policy is cloned at the parameter level into every layer of an untied soft-input soft-output iterative detection and decoding (IDD) receiver. This tied-to-untied transfer preserves the learned zero-prior search dynamics while enabling layer- and round-specific specialization under decoder feedback. Within each IDD round, decoder priors tilt candidate generation according to Bayes' rule, and likelihood-weighted terminal hypotheses produce posterior and extrinsic log-likelihood ratios for LDPC decoding. A multi-stage training strategy further stabilizes the hard-to-soft transfer by progressively exposing the receiver to synthetic and in-loop decoder-generated priors.
## Keyword: autonomous driving
### Title:
          Coverage Aware Active Evaluation for Failure Discovery with Paired Systems
 - **Authors:** Anjali Parashar, Rachel Luo, Apoorva Sharma, Sushant Veer, Edward Schmerling, Carson Sobolewski, Mingxin Yu, Chuchu Fan, Marco Pavone
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous systems can fail in rare and heterogeneous ways, making real-world failure discovery difficult under limited testing budgets. Although cheaper proxies such as simulators, lower-fidelity systems, or related policies can be sampled extensively to find failures, proxy failures often do not transfer to the real world due to sim-to-real and system-to-system gaps. The key challenge is therefore to effectively leverage proxy system information for accurate prediction of severe target system failures. We propose an adaptive failure discovery method that combines proxy evaluations with limited target system results to guide scenario selection for target system testing. Our method learns a local predictor of target risk by correcting proxy failure signals using control-variate-inspired residual modeling. To find failures that are both likely and diverse, we combine this predictor with a support-aware mutual-information objective that favors realistic, well-supported regions while expanding coverage across failure modes. Across autonomous driving, manipulation, and quadruped velocity-tracking tasks, our method discovers up to 2$\times$ as many failures as random sampling and active-learning baselines, including severe and diverse failures missed by competing methods.
### Title:
          SSP: An Event-Matched Syn2Sim2Phy Cross-Domain Evaluation Framework for Autonomous Driving VLA Models
 - **Authors:** Haojie Feng, Peizhi Zhang, Xinrui Zhang, Zhuoren Li, Junpeng Huang, Xiurong Wang, Dongxiao Yin, Yuxiang Zhang, Junfan Zhu, Lu Xiong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language-action (VLA) models for autonomous driving jointly produce scene interpretation, language-based reasoning, and driving trajectories. Existing evaluations often use independently selected synthetic, simulated, and physical data, so measured performance gaps can be confounded by changes in scenario content rather than genuine domain sensitivity. We propose SSP (Synthetic-Simulation-Physical), an event-matched Syn2Sim2Phy evaluation framework that anchors cross-domain comparison to the same safety-critical interaction. Starting from a synthetic long-tail video, SSP builds a validated event specification that preserves road topology, participant roles, relative motion, conflict evolution, passing order, response constraints, and event phases. Platform-specific realizations are then constructed in CARLA and on a closed proving ground and are evaluated only after transfer audits confirm preservation of mandatory event properties. SSP maps heterogeneous outputs from OpenEMMA, LLaViDA, and Alpamayo-R1 into common semantic slots and a 1 s trajectory window to assess output validity, semantic accuracy, critical-interaction recognition, trajectory quality, and risk response. Across Cut-in and vulnerable-road-user crossing cases, the macro-averaged Integrated VLA Capability Scores are 0.259, 0.291, and 0.325 in the Synthetic, Simulation, and Physical domains, respectively, while the best domain varies by scenario. Alpamayo-R1, OpenEMMA, and LLaViDA obtain scores of 0.405, 0.338, and 0.131. SSP provides a reproducible scene-transfer chain and an evidence-qualified evaluation of VLA behavior without assuming that the Physical domain is universally superior.
### Title:
          IRGNN: Efficient Invariant Radar Graph Neural Network for Radar Point Cloud Object Detection
 - **Authors:** Xiao Guo, Wanke Xia, Lili Yang, Caicong Wu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Perception is a fundamental component of autonomous driving systems. While LiDAR-based methods have achieved remarkable progress in object detection, their reliability can degrade under adverse weather conditions. Radar point clouds provide a robust alternative due to their resilience to bad weather and low-illumination scenarios. However, radar point clouds are typically sparse, unordered, and less informative than LiDAR data, making it challenging to directly apply existing LiDAR-based perception methods. To address these challenges, we propose IRGNN, an Invariant Radar Graph Neural Network for radar point cloud object detection. IRGNN first reconstructs radar point clouds into graph representations using translation- and rotation-invariant feature designs, enabling robust modeling of sparse radar measurements. It then employs an improved message passing neural network (MPNN) with residual connections and a virtual node layer to enhance local feature propagation and global context modeling. Finally, task-specific heads are applied to the learned graph representations for object classification and bounding box prediction. Experimental results on the RadarScenes dataset show that IRGNN outperforms existing radar-based object detection methods and achieves competitive performance. In addition, IRGNN significantly reduces computational cost and memory usage during inference, demonstrating its effectiveness and practical potential for efficient radar-based perception in autonomous driving.
### Title:
          GhostPoint: Self-Supervised Representation Learning by Hallucinating Occluded LiDAR Structure
 - **Authors:** Mohamed Abdelsamad, Bin Yang, Michael Ulrich, Miao Zhang, Yakov Miron, Alexandru Paul Condurache, Abhinav Valada
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D object detection from LiDAR point clouds is a core problem in autonomous driving. Recent advances in self-supervised learning (SSL) enable scalable pretraining and transfers well to per-point tasks such as semantic and panoptic segmentation, but transfer to 3D detection remains weaker. We analyze recent SSL methods and find that most objectives are defined only on measured LiDAR returns from visible surfaces, leaving occluded and unobserved regions unconstrained. This visible-surface bias can be sufficient for point-wise prediction, but 3D detection requires robustness to missing structure. To address this gap, we propose GhostPoint, an SSL framework that hallucinates latent features in local neighborhoods around discovered instances, generated via a novel instance voxel dilation. In GhostPoint, an encoder processes observed returns, and an additional predictor infers neighborhood representations from observed context. In addition to standard encoder-level supervision, we introduce a predictor-level supervision scheme on sampled voxels from generated neighborhoods. Specifically, observed (visible/masked) voxels match teacher-encoder targets, while unobserved voxels match teacher-predictor hallucinations. This design encourages the learned representation to explicitly model structure beyond observed returns. Extensive evaluations on nuScenes and Waymo demonstrate that our method achieves state-of-the-art performance, consistently improving downstream 3D detection, especially under sparse scans and limited labels.
