# Showing new listings for Wednesday, 8 April 2026
## Keyword: SLAM
### Title:
          Synchronous Observer Design for Landmark-Inertial SLAM with Magnetometer and Intermittent GNSS Measurements
 - **Authors:** Arkadeep Saha, Pieter van Goor, Ravi Banavar
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In Landmark-Inertial Simultaneous Localisation and Mapping (LI-SLAM), the positions of landmarks in the environment and the robot's pose relative to these landmarks are estimated using landmark position measurements, and measurements from the Inertial Measurement Unit (IMU). However, the robot and landmark positions in the inertial frame, and the yaw of the robot, are not observable in LI-SLAM. This paper proposes a nonlinear observer for LI-SLAM that overcomes the observability constraints with the addition of intermittent GNSS position and magnetometer measurements. The full-state error dynamics of the proposed observer is shown to be both almost-globally asymptotically stable and locally exponentially stable, and this is validated using simulations.
## Keyword: odometry
There is no result 
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Unsupervised Multi-agent and Single-agent Perception from Cooperative Views
 - **Authors:** Haochen Yang, Baolu Li, Lei Li, Delin Ren, Jiacheng Guo, Minghai Qin, Tianyun Zhang, Hongkai Yu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The LiDAR-based multi-agent and single-agent perception has shown promising performance in environmental understanding for robots and automated vehicles. However, there is no existing method that simultaneously solves both multi-agent and single-agent perception in an unsupervised way. By sharing sensor data between multiple agents via communication, this paper discovers two key insights: 1) Improved point cloud density after the data sharing from cooperative views could benefit unsupervised object classification, 2) Cooperative view of multiple agents can be used as unsupervised guidance for the 3D object detection in the single view. Based on these two discovered insights, we propose an Unsupervised Multi-agent and Single-agent (UMS) perception framework that leverages multi-agent cooperation without human annotations to simultaneously solve multi-agent and single-agent perception. UMS combines a learning-based Proposal Purifying Filter to better classify the candidate proposals after multi-agent point cloud density cooperation, followed by a Progressive Proposal Stabilizing module to yield reliable pseudo labels by the easy-to-hard curriculum learning. Furthermore, we design a Cross-View Consensus Learning to use multi-agent cooperative view to guide detection in single-agent view. Experimental results on two public datasets V2V4Real and OPV2V show that our UMS method achieved significantly higher 3D detection performance than the state-of-the-art methods on both multi-agent and single-agent perception tasks in an unsupervised setting.
### Title:
          Weather-Conditioned Branch Routing for Robust LiDAR-Radar 3D Object Detection
 - **Authors:** Hongsheng Li, Lingfeng Zhang, Zexian Yang, Liang Li, Rong Yin, Xiaoshuai Hao, Wenbo Ding
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust 3D object detection in adverse weather is highly challenging due to the varying reliability of different sensors. While existing LiDAR-4D radar fusion methods improve robustness, they predominantly rely on fixed or weakly adaptive pipelines, failing to dy-namically adjust modality preferences as environmental conditions change. To bridge this gap, we reformulate multi-modal perception as a weather-conditioned branch routing problem. Instead of computing a single fused output, our framework explicitly maintains three parallel 3D feature streams: a pure LiDAR branch, a pure 4D radar branch, and a condition-gated fusion branch. Guided by a condition token extracted from visual and semantic prompts, a lightweight router dynamically predicts sample-specific weights to softly aggregate these representations. Furthermore, to prevent branch collapse, we introduce a weather-supervised learning strategy with auxiliary classification and diversity regularization to enforce distinct, condition-dependent routing behaviors. Extensive experiments on the K-Radar benchmark demonstrate that our method achieves state-of-the-art performance. Furthermore, it provides explicit and highly interpretable insights into modality preferences, transparently revealing how adaptive routing robustly shifts reliance between LiDAR and 4D radar across diverse adverse-weather scenarios. The source code with be released.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          Coverage Optimization for Camera View Selection
 - **Authors:** Timothy Chen, Adam Dai, Maximilian Adang, Grace Gao, Mac Schwager
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 What makes a good viewpoint? The quality of the data used to learn 3D reconstructions is crucial for enabling efficient and accurate scene modeling. We study the active view selection problem and develop a principled analysis that yields a simple and interpretable criterion for selecting informative camera poses. Our key insight is that informative views can be obtained by minimizing a tractable approximation of the Fisher Information Gain, which reduces to favoring viewpoints that cover geometry that has been insufficiently observed by past cameras. This leads to a lightweight coverage-based view selection metric that avoids expensive transmittance estimation and is robust to noise and training dynamics. We call this metric COVER (Camera Optimization for View Exploration and Reconstruction). We integrate our method into the Nerfstudio framework and evaluate it on real datasets within fixed and embodied data acquisition scenarios. Across multiple datasets and radiance-field baselines, our method consistently improves reconstruction quality compared to state-of-the-art active view selection methods. Additional visualizations and our Nerfstudio package can be found at this https URL.
### Title:
          3DTurboQuant: Training-Free Near-Optimal Quantization for 3D Reconstruction Models
 - **Authors:** Jae Joong Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Every existing method for compressing 3D Gaussian Splatting, NeRF, or transformer-based 3D reconstructors requires learning a data-dependent codebook through per-scene fine-tuning. We show this is unnecessary. The parameter vectors that dominate storage in these models, 45-dimensional spherical harmonics in 3DGS and 1024-dimensional key-value vectors in DUSt3R, fall in a dimension range where a single random rotation transforms any input into coordinates with a known Beta distribution. This makes precomputed, data-independent Lloyd-Max quantization near-optimal, within a factor of 2.7 of the information-theoretic lower bound. We develop 3D, deriving (1) a dimension-dependent criterion that predicts which parameters can be quantized and at what bit-width before running any experiment, (2) norm-separation bounds connecting quantization MSE to rendering PSNR per scene, (3) an entry-grouping strategy extending rotation-based quantization to 2-dimensional hash grid features, and (4) a composable pruning-quantization pipeline with a closed-form compression ratio. On NeRF Synthetic, 3DTurboQuant compresses 3DGS by 3.5x with 0.02dB PSNR loss and DUSt3R KV caches by 7.9x with 39.7dB pointmap fidelity. No training, no codebook learning, no calibration data. Compression takes seconds. The code will be released (this https URL)
## Keyword: mapping
### Title:
          A Numerical PDEs Approach to Evolution Equations in Shape Analysis Based on Regularized Morphoelasticity
 - **Authors:** Ziqin Zhou
 - **Subjects:** Subjects:
Numerical Analysis (math.NA); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work studies a variational formulation and numerical solution of a regularized morphoelasticity problem of shape evolution. The foundation of our analysis is based on the governing equations of linear elasticity, extended to account for volumetric growth. In the morphoelastic framework, the total deformation is decomposed into an elastic component and a growth component, represented by a growth tensor $G$. While the forward one-step problem -- computing displacement given a growth tensor -- is well-established, a more challenging and relevant question in biological modeling is the inverse problem in a continuous sense. While this problem is fundamentally ill-posed without additional constraints, we will explore parametrized growth models inscribed within an optimal control problem inspired by the Large Deformation Diffeomorphic Metric Mapping (LDDMM) framework. By treating the growth process as a path within a shape space, we can define a physically meaningful metric and seek the most plausible, energy-efficient trajectory between configurations. In the construction, a high-order regularization term is introduced. This elevates the governing equations to a high-order elliptic system, ensuring the existence of a smooth solution. This dissertation focuses on the issue of solving this equation efficiently, as this is a key requirement for the feasibility of the overall approach. This will be achieved with the help of finite element solvers, notably from the FEniCSx library in Python. Also, we implement a Mixed Finite Element Method, which decomposes the problem into a system of coupled second-order equations as a treatment of these high-order systems that have significant computational challenges.
### Title:
          Nash Approximation Gap in Truncated Infinite-horizon Partially Observable Markov Games
 - **Authors:** Lan Sang, Chinmay Maheshwari
 - **Subjects:** Subjects:
Multiagent Systems (cs.MA); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Partially Observable Markov Games (POMGs) provide a general framework for modeling multi-agent sequential decision-making under asymmetric information. A common approach is to reformulate a POMG as a fully observable Markov game over belief states, where the state is the conditional distribution of the system state and agents' private information given common information, and actions correspond to mappings (prescriptions) from private information to actions. However, this reformulation is intractable in infinite-horizon settings, as both the belief state and action spaces grow with the accumulation of information over time. We propose a finite-memory truncation framework that approximates infinite-horizon POMGs by a finite-state, finite-action Markov game, where agents condition decisions only on finite windows of common and private information. Under suitable filter stability (forgetting) conditions, we show that any Nash equilibrium of the truncated game is an $\varepsilon$-Nash equilibrium of the original POMG, where $\varepsilon \to 0$ as the truncation length increases.
### Title:
          Lightweight True In-Pixel Encryption with FeFET Enabled Pixel Design for Secure Imaging
 - **Authors:** Md Rahatul Islam Udoy, Diego Ferrer, Wantong Li, Kai Ni, Sumeet Kumar Gupta, Ahmedullah Aziz
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ensuring end-to-end security in image sensors has become essential as visual data can be exposed through multiple stages of the imaging pipeline. Advanced protection requires encryption to occur before pixel values appear on any readout lines. This work introduces a secure pixel sensor (SecurePix), a compact CMOS-compatible pixel architecture that performs true in-pixel encryption using a symmetric key realized through programmable, non-volatile multidomain polarization states of a ferroelectric field-effect transistor. The pixel and array operations are designed and simulated in HSPICE, while a 45 nm CMOS process design kit is used for layout drawing. The resulting layout confirms a pixel pitch of 2.33 x 3.01 um^2. Each pixel's non-volatile programming level defines its analog transfer characteristic, enabling the photodiode voltage to be converted into an encrypted analog output within the pixel. Full-image evaluation shows that ResNet-18 recognition accuracy drops from 99.29 percent to 9.58 percent on MNIST and from 91.33 percent to 6.98 percent on CIFAR-10 after encryption, indicating strong resistance to neural-network-based inference. Lookup-table-based inverse mapping enables recovery for authorized receivers using the same symmetric key. Based on HSPICE simulation, the SecurePix achieves a per-pixel programming power-delay product of 17 uW us and a per-pixel sensing power-delay product of 1.25 uW us, demonstrating low-overhead hardware-level protection.
### Title:
          Synchronous Observer Design for Landmark-Inertial SLAM with Magnetometer and Intermittent GNSS Measurements
 - **Authors:** Arkadeep Saha, Pieter van Goor, Ravi Banavar
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In Landmark-Inertial Simultaneous Localisation and Mapping (LI-SLAM), the positions of landmarks in the environment and the robot's pose relative to these landmarks are estimated using landmark position measurements, and measurements from the Inertial Measurement Unit (IMU). However, the robot and landmark positions in the inertial frame, and the yaw of the robot, are not observable in LI-SLAM. This paper proposes a nonlinear observer for LI-SLAM that overcomes the observability constraints with the addition of intermittent GNSS position and magnetometer measurements. The full-state error dynamics of the proposed observer is shown to be both almost-globally asymptotically stable and locally exponentially stable, and this is validated using simulations.
### Title:
          Bypassing the CSI Bottleneck: MARL-Driven Spatial Control for Reflector Arrays
 - **Authors:** Hieu Le, Oguz Bedir, Mostafa Ibrahim, Jian Tao, Sabit Ekin
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reconfigurable Intelligent Surfaces (RIS) are pivotal for next-generation smart radio environments, yet their practical deployment is severely bottlenecked by the intractable computational overhead of Channel State Information (CSI) estimation. To bypass this fundamental physical-layer barrier, we propose an AI-native, data-driven paradigm that replaces complex channel modeling with spatial intelligence. This paper presents a fully autonomous Multi-Agent Reinforcement Learning (MARL) framework to control mechanically adjustable metallic reflector arrays. By mapping high-dimensional mechanical constraints to a reduced-order virtual focal point space, we deploy a Centralized Training with Decentralized Execution (CTDE) architecture. Using Multi-Agent Proximal Policy Optimization (MAPPO), our decentralized agents learn cooperative beam-focusing strategies relying on user coordinates, achieving CSI-free operation. High-fidelity ray-tracing simulations in dynamic non-line-of-sight (NLOS) environments demonstrate that this multi-agent approach rapidly adapts to user mobility, yielding up to a 26.86 dB enhancement over static flat reflectors and outperforming single-agent and hardware-constrained DRL baselines in both spatial selectivity and temporal stability. Crucially, the learned policies exhibit good deployment resilience, sustaining stable signal coverage even under 1.0-meter localization noise. These results validate the efficacy of MARL-driven spatial abstractions as a scalable, highly practical pathway toward AI-empowered wireless networks.
### Title:
          Vehicle-as-Prompt: A Unified Deep Reinforcement Learning Framework for Heterogeneous Fleet Vehicle Routing Problem
 - **Authors:** Shihong Huang, Shengjie Wang, Lei Gao, Hong Ma, Zhanluo Zhang, Feng Zhang, Weihua Zhou
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unlike traditional homogeneous routing problems, the Heterogeneous Fleet Vehicle Routing Problem (HFVRP) involves heterogeneous fixed costs, variable travel costs, and capacity constraints, rendering solution quality highly sensitive to vehicle selection. Furthermore, real-world logistics applications often impose additional complex constraints, markedly increasing computational complexity. However, most existing Deep Reinforcement Learning (DRL)-based methods are restricted to homogeneous scenarios, leading to suboptimal performance when applied to HFVRP and its complex variants. To bridge this gap, we investigate HFVRP under complex constraints and develop a unified DRL framework capable of solving the problem across various variant settings. We introduce the Vehicle-as-Prompt (VaP) mechanism, which formulates the problem as a single-stage autoregressive decision process. Building on this, we propose VaP-CSMV, a framework featuring a cross-semantic encoder and a multi-view decoder that effectively addresses various problem variants and captures the complex mapping relationships between vehicle heterogeneity and customer node attributes. Extensive experimental results demonstrate that VaP-CSMV significantly outperforms existing state-of-the-art DRL-based neural solvers and achieves competitive solution quality compared to traditional heuristic solvers, while reducing inference time to mere seconds. Furthermore, the framework exhibits strong zero-shot generalization capabilities on large-scale and previously unseen problem variants, while ablation studies validate the vital contribution of each component.
### Title:
          Generative Channel Knowledge Base With Environmental Information for Joint Source-Channel Coding in Semantic Communications
 - **Authors:** Xudong Long, Hao Chen, Dan Wang, Chen Qiu, Nan Ma, Xiaodong Xu, Yubin Zhao
 - **Subjects:** Subjects:
Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic knowledge bases are regarded as a promising technology for upcoming 6G communications. However, existing studies mainly focus on source-side semantic modeling while overlooking the structural impact of propagation environments on semantic transmission performance. To address this issue, we propose a generative channel knowledge base (CKB) with environmental information to facilitate joint source-channel coding (JSCC) in semantic communications (SemCom) systems. First, to enable the construction of the CKB, an environment-aware dataset is established by collecting spatial position information, global image features, fine-grained semantic features, and the corresponding channel matrices. A region-of-interest (ROI)-based filtering algorithm is further designed to remove semantic components that are irrelevant to signal propagation. Second, a Transformer-based generative framework is developed to learn the mapping between multidimensional environmental information and channel matrices. A self-attention mechanism is introduced to adaptively fuse heterogeneous features, enabling the construction of a structured CKB. Third, a CKB-driven JSCC SemCom architecture is proposed, where the generated channel knowledge is injected into both of the encoder and decoder to jointly exploit source semantics and channel-environment priors in an end-to-end manner. Experimental results demonstrate that the proposed multidimensional feature fusion method achieves a channel matrix estimation error at the $10^{-3}$ level. Moreover, the CKB-driven JSCC SemCom framework integrated into SemCom systems significantly outperforms existing benchmark schemes in terms of transmission performance.
### Title:
          From Clues to Generation: Language-Guided Conditional Diffusion for Cross-Domain Recommendation
 - **Authors:** Ziang Lu, Lei Sang, Lin Mu, Yiwen Zhang
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-domain Recommendation (CDR) exploits multi-domain correlations to alleviate data sparsity. As a core task within this field, inter-domain recommendation focuses on predicting preferences for users who interact in a source domain but lack behavioral records in a target domain. Existing approaches predominantly rely on overlapping users as anchors for knowledge transfer. In real-world scenarios, overlapping users are often scarce, leaving the vast majority of users with only single-domain interactions. For these users, the absence of explicit alignment signals makes fine-grained preference transfer intrinsically difficult. To address this challenge, this paper proposes Language-Guided Conditional Diffusion for CDR (LGCD), a novel framework that integrates Large Language Models (LLMs) and diffusion models for inter-domain sequential recommendation. Specifically, we leverage LLM reasoning to bridge the domain gap by inferring potential target preferences for single-domain users and mapping them to real items, thereby constructing pseudo-overlapping data. We distinguish between real and pseudo-interaction pathways and introduce additional supervision constraints to mitigate the semantic noise brought by pseudo-interaction. Furthermore, we design a conditional diffusion architecture to precisely guide the generation of target user representations based on source-domain patterns. Extensive experiments demonstrate that LGCD significantly outperforms state-of-the-art methods in inter-domain recommendation tasks.
### Title:
          JailWAM: Jailbreaking World Action Models in Robot Control
 - **Authors:** Hanqing Liu, Songping Wang, Jiahuan Long, Jiacheng Hou, Jialiang Sun, Chao Li, Yang Yang, Wei Peng, Xu Liu, Tingsong Jiang, Wen Yao, Yao Mu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The World Action Model (WAM) can jointly predict future world states and actions, exhibiting stronger physical manipulation capabilities compared with traditional models. Such powerful physical interaction ability is a double-edged sword: if safety is ignored, it will directly threaten personal safety, property security and environmental safety. However, existing research pays extremely limited attention to the critical security gap: the vulnerability of WAM to jailbreak attacks. To fill this gap, we define the Three-Level Safety Classification Framework to systematically quantify the safety of robotic arm motions. Furthermore, we propose JailWAM, the first dedicated jailbreak attack and evaluation framework for WAM, which consists of three core components: (1) Visual-Trajectory Mapping, which unifies heterogeneous action spaces into visual trajectory representations and enables cross-architectural unified evaluation; (2) Risk Discriminator, which serves as a high-recall screening tool that optimizes the efficiency-accuracy trade-off when identifying destructive behaviors in visual trajectories; (3) Dual-Path Verification Strategy, which first conducts rapid coarse screening via a single-image-based video-action generation module, and then performs efficient and comprehensive verification through full closed-loop physical simulation. In addition, we construct JailWAM-Bench, a benchmark for comprehensively evaluating the safety alignment performance of WAM under jailbreak attacks. Experiments in RoboTwin simulation environment demonstrate that the proposed framework efficiently exposes physical vulnerabilities, achieving an 84.2% attack success rate on the state-of-the-art LingBot-VA. Meanwhile, robust defense mechanisms can be constructed based on JailWAM, providing an effective technical solution for designing safe and reliable robot control systems.
### Title:
          Physics-Aligned Spectral Mamba: Decoupling Semantics and Dynamics for Few-Shot Hyperspectral Target Detection
 - **Authors:** Luqi Gong, Qixin Xie, Yue Chen, Ziqiang Chen, Fanda Fan, Shuai Zhao, Chao Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Meta-learning facilitates few-shot hyperspectral target detection (HTD), but adapting deep backbones remains challenging. Full-parameter fine-tuning is inefficient and prone to overfitting, and existing methods largely ignore the frequency-domain structure and spectral band continuity of hyperspectral data, limiting spectral adaptation and cross-domain this http URL address these challenges, we propose SpecMamba, a parameter-efficient and frequency-aware framework that decouples stable semantic representation from agile spectral adaptation. Specifically, we introduce a Discrete Cosine Transform Mamba Adapter (DCTMA) on top of frozen Transformer representations. By projecting spectral features into the frequency domain via DCT and leveraging Mamba's linear-complexity state-space recursion, DCTMA explicitly captures global spectral dependencies and band continuity while avoiding the redundancy of full fine-tuning. Furthermore, to address prototype drift caused by limited sample sizes, we design a Prior-Guided Tri-Encoder (PGTE) that allows laboratory spectral priors to guide the optimization of the learnable adapter without disrupting the stable semantic feature space. Finally, a Self-Supervised Pseudo-Label Mapping (SSPLM) strategy is developed for test-time adaptation, enabling efficient decision boundary refinement through uncertainty-aware sampling and dual-path consistency constraints. Extensive experiments on multiple public datasets demonstrate that SpecMamba consistently outperforms state-of-the-art methods in detection accuracy and cross-domain generalization.
### Title:
          FunRec: Reconstructing Functional 3D Scenes from Egocentric Interaction Videos
 - **Authors:** Alexandros Delitzas, Chenyangguang Zhang, Alexey Gavryushin, Tommaso Di Mario, Boyang Sun, Rishabh Dabral, Leonidas Guibas, Christian Theobalt, Marc Pollefeys, Francis Engelmann, Daniel Barath
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present FunRec, a method for reconstructing functional 3D digital twins of indoor scenes directly from egocentric RGB-D interaction videos. Unlike existing methods on articulated reconstruction, which rely on controlled setups, multi-state captures, or CAD priors, FunRec operates directly on in-the-wild human interaction sequences to recover interactable 3D scenes. It automatically discovers articulated parts, estimates their kinematic parameters, tracks their 3D motion, and reconstructs static and moving geometry in canonical space, yielding simulation-compatible meshes. Across new real and simulated benchmarks, FunRec surpasses prior work by a large margin, achieving up to +50 mIoU improvement in part segmentation, 5-10 times lower articulation and pose errors, and significantly higher reconstruction accuracy. We further demonstrate applications on URDF/USD export for simulation, hand-guided affordance mapping and robot-scene interaction.
### Title:
          BodhiPromptShield: Pre-Inference Prompt Mediation for Suppressing Privacy Propagation in LLM/VLM Agents
 - **Authors:** Bo Ma, Jinsong Wu, Weiqi Yan
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In LLM/VLM agents, prompt privacy risk propagates beyond a single model call because raw user content can flow into retrieval queries, memory writes, tool calls, and logs. Existing de-identification pipelines address document boundaries but not this cross-stage propagation. We propose BodhiPromptShield, a policy-aware framework that detects sensitive spans, routes them via typed placeholders, semantic abstraction, or secure symbolic mapping, and delays restoration to authorized boundaries. Relative to enterprise redaction, this adds explicit propagation-aware mediation and restoration timing as a security variable. Under controlled evaluation on the Controlled Prompt-Privacy Benchmark (CPPB), stage-wise propagation suppresses from 10.7\% to 7.1\% across retrieval, memory, and tool stages; PER reaches 9.3\% with 0.94 AC and 0.92 TSR, outperforming generic de-identification. These are controlled systems results on CPPB rather than formal privacy guarantees or public-benchmark transfer claims. The project repository is available at this https URL.
### Title:
          Near-Field Integrated Sensing, Computing and Semantic Communication in Digital Twin-Assisted Vehicular Networks
 - **Authors:** Yinchao Yang, Yahao Ding, Jiaxiang Wang, Zhaohui Yang, Chen Zhu, Zhaoyang Zhang, Dusit Niyato, Mohammad Shikh-Bahaei
 - **Subjects:** Subjects:
Information Theory (cs.IT); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Digital twin (DT) technology offers transformative potential for vehicular networks, enabling high-fidelity virtual representations for enhanced safety and automation. However, seamless DT synchronization in dynamic environments faces challenges such as massive data transmission, precision sensing, and strict computational constraints. This paper proposes an integrated sensing, computing, and semantic communication (ISCSC) framework tailored for DT-assisted vehicular networks in the near-field (NF) regime. Leveraging a multi-user multiple-input multiple-output (MU-MIMO) configuration, each roadside unit (RSU) employs semantic communication to serve vehicles while simultaneously utilizing millimeter-wave (mmWave) radar for environmental mapping. We implement particle filtering at RSUs to achieve high-precision vehicle tracking. To optimize performance, we formulate a joint optimization problem balancing semantic communication rates and sensing accuracy under limited computational resources and power budget. Our solution includes a hybrid heuristic algorithm for vehicle-to-RSU assignment and an alternating optimization approach for determining semantic extraction ratios and beamforming matrices. Performance is extensively evaluated via the Cramér-Rao bound (CRB) for angle and distance estimation, semantic transmission rates, and resource utilization. Numerical results demonstrate that the proposed ISCSC framework achieves a 20% improvement in transmission rate while maintaining the sensing accuracy of existing integrated sensing and communication (ISAC) schemes under constrained resource conditions.
### Title:
          Precise Aggressive Aerial Maneuvers with Sensorimotor Policies
 - **Authors:** Tianyue Wu, Guangtong Xu, Zihan Wang, Junxiao Lin, Tianyang Chen, Yuze Wu, Zhichao Han, Zhiyang Liu, Fei Gao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Precise aggressive maneuvers with lightweight onboard sensors remains a key bottleneck in fully exploiting the maneuverability of drones. Such maneuvers are critical for expanding the systems' accessible area by navigating through narrow openings in the environment. Among the most relevant problems, a representative one is aggressive traversal through narrow gaps with quadrotors under SE(3) constraints, which require the quadrotors to leverage a momentary tilted attitude and the asymmetry of the airframe to navigate through gaps. In this paper, we achieve such maneuvers by developing sensorimotor policies directly mapping onboard vision and proprioception into low-level control commands. The policies are trained using reinforcement learning (RL) with end-to-end policy distillation in simulation. We mitigate the fundamental hardness of model-free RL's exploration on the restricted solution space with an initialization strategy leveraging trajectories generated by a model-based planner. Careful sim-to-real design allows the policy to control a quadrotor through narrow gaps with low clearances and high repeatability. For instance, the proposed method enables a quadrotor to navigate a rectangular gap at a 5 cm clearance, tilted at up to 90-degree orientation, without knowledge of the gap's position or orientation. Without training on dynamic gaps, the policy can reactively servo the quadrotor to traverse through a moving gap. The proposed method is also validated by training and deploying policies on challenging tracks of narrow gaps placed closely. The flexibility of the policy learning method is demonstrated by developing policies for geometrically diverse gaps, without relying on manually defined traversal poses and visual features.
### Title:
          Swiss-Bench 003: Evaluating LLM Reliability and Adversarial Security for Swiss Regulatory Contexts
 - **Authors:** Fatih Uenal
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The deployment of large language models (LLMs) in Swiss financial and regulatory contexts demands empirical evidence of both production reliability and adversarial security, dimensions not jointly operationalized in existing Swiss-focused evaluation frameworks. This paper introduces Swiss-Bench 003 (SBP-003), extending the HAAS (Helvetic AI Assessment Score) from six to eight dimensions by adding D7 (Self-Graded Reliability Proxy) and D8 (Adversarial Security). I evaluate ten frontier models across 808 Swiss-specific items in four languages (German, French, Italian, English), comprising seven Swiss-adapted benchmarks (Swiss TruthfulQA, Swiss IFEval, Swiss SimpleQA, Swiss NIAH, Swiss PII-Scope, System Prompt Leakage, and Swiss German Comprehension) targeting FINMA Guidance 08/2024, the revised Federal Act on Data Protection (nDSG), and OWASP Top 10 for LLMs. Self-graded D7 scores (73-94%) exceed externally judged D8 security scores (20-61%) by a wide margin, though these dimensions use non-comparable scoring regimes. System prompt leakage resistance ranges from 24.8% to 88.2%, while PII extraction defense remains weak (14-42%) across all models. Qwen 3.5 Plus achieves the highest self-graded D7 score (94.4%), while GPT-oss 120B achieves the highest D8 score (60.7%) despite being the lowest-cost model evaluated. All evaluations are zero-shot under provider default settings; D7 is self-graded and does not constitute independently validated accuracy. I provide conceptual mapping tables relating benchmark dimensions to FINMA model validation requirements, nDSG data protection obligations, and OWASP LLM risk categories.
### Title:
          FinReporting: An Agentic Workflow for Localized Reporting of Cross-Jurisdiction Financial Disclosures
 - **Authors:** Fan Zhang, Mingzi Song, Rania Elbadry, Yankai Chen, Shaobo Wang, Yixi Zhou, Xunwen Zheng, Yueru He, Yuyang Dai, Georgi Georgiev, Ayesha Gull, Muhammad Usman Safder, Fan Wu, Liyuan Meng, Fengxian Ji, Junning Zhao, Xueqing Peng, Jimin Huang, Yu Chen, Xue (Steve)Liu, Preslav Nakov, Zhuohan Xie
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Financial reporting systems increasingly use large language models (LLMs) to extract and summarize corporate disclosures. However, most assume a single-market setting and do not address structural differences across jurisdictions. Variations in accounting taxonomies, tagging infrastructures (e.g., XBRL vs. PDF), and aggregation conventions make cross-jurisdiction reporting a semantic alignment and verification challenge. We present FinReporting, an agentic workflow for localized cross-jurisdiction financial reporting. The system builds a unified canonical ontology over Income Statement, Balance Sheet, and Cash Flow, and decomposes reporting into auditable stages including filing acquisition, extraction, canonical mapping, and anomaly logging. Rather than using LLMs as free-form generators, FinReporting deploys them as constrained verifiers under explicit decision rules and evidence grounding. Evaluated on annual filings from the US, Japan, and China, the system improves consistency and reliability under heterogeneous reporting regimes. We release an interactive demo supporting cross-market inspection and structured export of localized financial statements. Our demo is available at this https URL . The video describing our system is available at this https URL
### Title:
          A Co-Design Framework for High-Performance Jumping of a Five-Bar Monoped with Actuator Optimization
 - **Authors:** Aastha Mishra, Aman Singh, Shishir Kolathaya
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The performance of legged robots depends strongly on both mechanical design and control, motivating co-design approaches that jointly optimize these parameters. However, most existing co-design studies focus on optimizing link dimensions and transmission ratios while neglecting detailed actuator design, particularly motor and gearbox parameter optimization, and are largely limited to serial open-chain mechanisms. In this work, we present a co-design framework for a planar closed-chain five-bar monoped that jointly optimizes mechanical design, motor and gearbox parameters, and control parameters for dynamic jumping. The objective is to maximize jump distance while minimizing mechanical energy consumption. The framework uses a two-stage optimization approach, where actuator optimization generates a mapping from gear ratio to actuator mass, efficiency, and peak torque, which is then used in co-design optimization of the robot design and control using CMA-ES. Simulation results show an improvement of approximately 42% in jump distance and a 15.8% reduction in mechanical energy consumption compared to a nominal design, demonstrating the effectiveness of the proposed framework in identifying optimal design, actuator, and control parameters for high-performance and energy-efficient planar jumping.
### Title:
          PoM: A Linear-Time Replacement for Attention with the Polynomial Mixer
 - **Authors:** David Picard, Nicolas Dufour, Lucas Degeorge, Arijit Ghosh, Davide Allegro, Tom Ravaud, Yohann Perron, Corentin Sautier, Zeynep Sonat Baltaci, Fei Meng, Syrine Kalleli, Marta López-Rauhut, Thibaut Loiseau, Ségolène Albouy, Raphael Baena, Elliot Vincent, Loic Landrieu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper introduces the Polynomial Mixer (PoM), a novel token mixing mechanism with linear complexity that serves as a drop-in replacement for self-attention. PoM aggregates input tokens into a compact representation through a learned polynomial function, from which each token retrieves contextual information. We prove that PoM satisfies the contextual mapping property, ensuring that transformers equipped with PoM remain universal sequence-to-sequence approximators. We replace standard self-attention with PoM across five diverse domains: text generation, handwritten text recognition, image generation, 3D modeling, and Earth observation. PoM matches the performance of attention-based models while drastically reducing computational cost when working with long sequences. The code is available at this https URL.
### Title:
          Who Governs the Machine? A Machine Identity Governance Taxonomy (MIGT) for AI Systems Operating Across Enterprise and Geopolitical Boundaries
 - **Authors:** Andrew Kurtz, Klaudia Krawiecka
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The governance of artificial intelligence has a blind spot: the machine identities that AI systems use to act. AI agents, service accounts, API tokens, and automated workflows now outnumber human identities in enterprise environments by ratios exceeding 80 to 1, yet no integrated framework exists to govern them. A single ungoverned automated agent produced $5.4-10 billion in losses in the 2024 CrowdStrike outage; nation-state actors including Silk Typhoon and Salt Typhoon have operationalized ungoverned machine credentials as primary espionage vectors against critical infrastructure. This paper makes four original contributions. First, the AI-Identity Risk Taxonomy (AIRT): a comprehensive enumeration of 37 risk sub-categories across eight domains, each grounded in documented incidents, regulatory recognition, practitioner prevalence data, and threat intelligence. Second, the Machine Identity Governance Taxonomy (MIGT): an integrated six-domain governance framework simultaneously addressing the technical governance gap, the regulatory compliance gap, and the cross-jurisdictional coordination gap that existing frameworks address only in isolation. Third, a foreign state actor threat model for enterprise identity governance, establishing that Silk Typhoon, Salt Typhoon, Volt Typhoon, and North Korean AI-enhanced identity fraud operations have already operationalized AI identity vulnerabilities as active attack vectors. Fourth, a cross-jurisdictional regulatory alignment structure mapping enterprise AI identity governance obligations under EU, US, and Chinese frameworks simultaneously, identifying irreconcilable conflicts and providing a governance mechanism for managing them. A four-phase implementation roadmap translates the MIGT into actionable enterprise programs.
### Title:
          DiffHDR: Re-Exposing LDR Videos with Video Diffusion Models
 - **Authors:** Zhengming Yu, Li Ma, Mingming He, Leo Isikdogan, Yuancheng Xu, Dmitriy Smirnov, Pablo Salamanca, Dao Mi, Pablo Delgado, Ning Yu, Julien Philip, Xin Li, Wenping Wang, Paul Debevec
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Most digital videos are stored in 8-bit low dynamic range (LDR) formats, where much of the original high dynamic range (HDR) scene radiance is lost due to saturation and quantization. This loss of highlight and shadow detail precludes mapping accurate luminance to HDR displays and limits meaningful re-exposure in post-production workflows. Although techniques have been proposed to convert LDR images to HDR through dynamic range expansion, they struggle to restore realistic detail in the over- and underexposed regions. To address this, we present DiffHDR, a framework that formulates LDR-to-HDR conversion as a generative radiance inpainting task within the latent space of a video diffusion model. By operating in Log-Gamma color space, DiffHDR leverages spatio-temporal generative priors from a pretrained video diffusion model to synthesize plausible HDR radiance in over- and underexposed regions while recovering the continuous scene radiance of the quantized pixels. Our framework further enables controllable LDR-to-HDR video conversion guided by text prompts or reference images. To address the scarcity of paired HDR video data, we develop a pipeline that synthesizes high-quality HDR video training data from static HDRI maps. Extensive experiments demonstrate that DiffHDR significantly outperforms state-of-the-art approaches in radiance fidelity and temporal stability, producing realistic HDR videos with considerable latitude for re-exposure.
## Keyword: localization
### Title:
          A Survey on Sensor-based Planning and Control for Unmanned Underwater Vehicles
 - **Authors:** Shivam Vishwakarma, Tejal Bedmutha, Dharmendra Kumar Patel, Vijay Bhaskar Semwal, Leena Vachhani
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This survey examines recent sensor-based planning and control methods for Unmanned Underwater Vehicles (UUVs). In complex, uncertain underwater environments, UUVs require advanced planning and control strategies for effective navigation. These vehicles face significant challenges including drifting and noisy sensor measurements, absence of Global Navigation Satellite System (GNSS) signals, and low-bandwidth, high-latency underwater acoustic communications. The focus is on reactive local planning layers that adapt to real-time sensor inputs such as SONAR and Inertial Measurement Units (IMU) to improve localization accuracy and autonomy in dynamic ocean conditions, enabling dynamic obstacle avoidance and on-the-fly re-planning. The survey categorizes the existing literature into decoupled and coupled architectures for sensor-based planning and control. The decoupled architecture sequentially addresses planning and control stages, whereas coupled architectures offer tighter feedback loops for more immediate responsiveness. A comparative analysis of coupled planning and control methods reveals that while PID controllers are simple, they lack predictive capability for complex maneuvers. Model Predictive Control (MPC) offers superior path optimization but can be computationally intensive, and invariant-set controllers provide strong safety guarantees at the potential cost of agility in confined environments. Key contributions include a taxonomy of architectures combining planning and control, a focus on adaptive local planning, and an analysis of controller roles in integrated planning frameworks for autonomous navigation of UUVs.
### Title:
          Scaling Coding Agents via Atomic Skills
 - **Authors:** Yingwei Ma, Yue Liu, Xinlong Yang, Yanhao Li, Kelin Fu, Yibo Miao, Yuchong Xie, Zhexu Wang, Shing-Chi Cheung
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current LLM coding agents are predominantly trained on composite benchmarks (e.g., bug fixing), which often leads to task-specific overfitting and limited generalization. To address this, we propose a novel scaling paradigm that shifts the focus from task-level optimization to atomic skill mastery. We first formalize five fundamental atomic skills, code localization, code editing, unit-test generation, issue reproduction, and code review, that serve as the basis vectors for complex software engineering tasks. Compared with composite coding tasks, these atomic skills are more generalizable and composable. Then, we scale coding agents by performing joint RL over atomic skills. In this manner, atomic skills are consistently improved without negative interference or trade-offs between them. Notably, we observe that improvements in these atomic skills generalize well to other unseen composite coding tasks, such as bug-fixing, code refactoring, machine learning engineering, and code security. The observation motivates a new scaling paradigm for coding agents by training with atomic skills. Extensive experiments demonstrate the effectiveness of our proposed paradigm. Notably, our joint RL improves average performance by 18.7% on 5 atomic skills and 5 composite tasks.
### Title:
          MedGemma 1.5 Technical Report
 - **Authors:** Andrew Sellergren, Chufan Gao, Fereshteh Mahvar, Timo Kohlberger, Fayaz Jamil, Madeleine Traverse, Alberto Tono, Bashir Sadjad, Lin Yang, Charles Lau, Liron Yatziv, Tiffany Chen, Bram Sterling, Kenneth Philbrick, Richa Tiwari, Yun Liu, Madhuram Jajoo, Chandrashekar Sankarapu, Swapnil Vispute, Harshad Purandare, Abhishek Bijay Mishra, Sam Schmidgall, Tao Tu, Anil Palepu, Chunjong Park, Tim Strother, Rahul Thapa, Yong Cheng, Preeti Singh, Kat Black, Yossi Matias, Katherine Chou, Avinatan Hassidim, Kavi Goel, Joelle Barral, Tris Warkentin, Shravya Shetty, Dale Webster, Sunny Virmani, David F. Steiner, Can Kirmizibayrak, Daniel Golden
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce MedGemma 1.5 4B, the latest model in the MedGemma collection. MedGemma 1.5 expands on MedGemma 1 by integrating additional capabilities: high-dimensional medical imaging (CT/MRI volumes and histopathology whole slide images), anatomical localization via bounding boxes, multi-timepoint chest X-ray analysis, and improved medical document understanding (lab reports, electronic health records). We detail the innovations required to enable these modalities within a single architecture, including new training data, long-context 3D volume slicing, and whole-slide pathology sampling. Compared to MedGemma 1 4B, MedGemma 1.5 4B demonstrates significant gains in these new areas, improving 3D MRI condition classification accuracy by 11% and 3D CT condition classification by 3% (absolute improvements). In whole slide pathology imaging, MedGemma 1.5 4B achieves a 47% macro F1 gain. Additionally, it improves anatomical localization with a 35% increase in Intersection over Union on chest X-rays and achieves a 4% macro accuracy for longitudinal (multi-timepoint) chest x-ray analysis. Beyond its improved multimodal performance over MedGemma 1, MedGemma 1.5 improves on text-based clinical knowledge and reasoning, improving by 5% on MedQA accuracy and 22% on EHRQA accuracy. It also achieves an average of 18% macro F1 on 4 different lab report information extraction datasets (EHR Datasets 2, 3, 4, and Mendeley Clinical Laboratory Test Reports). Taken together, MedGemma 1.5 serves as a robust, open resource for the community, designed as an improved foundation on which developers can create the next generation of medical AI systems. Resources and tutorials for building upon MedGemma 1.5 can be found at this https URL.
### Title:
          Bypassing the CSI Bottleneck: MARL-Driven Spatial Control for Reflector Arrays
 - **Authors:** Hieu Le, Oguz Bedir, Mostafa Ibrahim, Jian Tao, Sabit Ekin
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reconfigurable Intelligent Surfaces (RIS) are pivotal for next-generation smart radio environments, yet their practical deployment is severely bottlenecked by the intractable computational overhead of Channel State Information (CSI) estimation. To bypass this fundamental physical-layer barrier, we propose an AI-native, data-driven paradigm that replaces complex channel modeling with spatial intelligence. This paper presents a fully autonomous Multi-Agent Reinforcement Learning (MARL) framework to control mechanically adjustable metallic reflector arrays. By mapping high-dimensional mechanical constraints to a reduced-order virtual focal point space, we deploy a Centralized Training with Decentralized Execution (CTDE) architecture. Using Multi-Agent Proximal Policy Optimization (MAPPO), our decentralized agents learn cooperative beam-focusing strategies relying on user coordinates, achieving CSI-free operation. High-fidelity ray-tracing simulations in dynamic non-line-of-sight (NLOS) environments demonstrate that this multi-agent approach rapidly adapts to user mobility, yielding up to a 26.86 dB enhancement over static flat reflectors and outperforming single-agent and hardware-constrained DRL baselines in both spatial selectivity and temporal stability. Crucially, the learned policies exhibit good deployment resilience, sustaining stable signal coverage even under 1.0-meter localization noise. These results validate the efficacy of MARL-driven spatial abstractions as a scalable, highly practical pathway toward AI-empowered wireless networks.
### Title:
          Learning to Focus: CSI-Free Hierarchical MARL for Reconfigurable Reflectors
 - **Authors:** Hieu Le, Mostafa Ibrahim, Oguz Bedir, Jian Tao, Sabit Ekin
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reconfigurable Intelligent Surfaces (RIS) has a potential to engineer smart radio environments for next-generation millimeter-wave (mmWave) networks. However, the prohibitive computational overhead of Channel State Information (CSI) estimation and the dimensionality explosion inherent in centralized optimization severely hinder practical large-scale deployments. To overcome these bottlenecks, we introduce a ``CSI-free" paradigm powered by a Hierarchical Multi-Agent Reinforcement Learning (HMARL) architecture to control mechanically reconfigurable reflective surfaces. By substituting pilot-based channel estimation with accessible user localization data, our framework leverages spatial intelligence for macro-scale wave propagation management. The control problem is decomposed into a two-tier neural architecture: a high-level controller executes temporally extended, discrete user-to-reflector allocations, while low-level controllers autonomously optimize continuous focal points utilizing Multi-Agent Proximal Policy Optimization (MAPPO) under a Centralized Training with Decentralized Execution (CTDE) scheme. Comprehensive deterministic ray-tracing evaluations demonstrate that this hierarchical framework achieves massive RSSI improvements of up to 7.79 dB over centralized baselines. Furthermore, the system exhibits robust multi-user scalability and maintains highly resilient beam-focusing performance under practical sub-meter localization tracking errors. By eliminating CSI overhead while maintaining high-fidelity signal redirection, this work establishes a scalable and cost-effective blueprint for intelligent wireless environments.
### Title:
          Boxer: Robust Lifting of Open-World 2D Bounding Boxes to 3D
 - **Authors:** Daniel DeTone, Tianwei Shen, Fan Zhang, Lingni Ma, Julian Straub, Richard Newcombe, Jakob Engel
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Detecting and localizing objects in space is a fundamental computer vision problem. While much progress has been made to solve 2D object detection, 3D object localization is much less explored and far from solved, especially for open-world categories. To address this research challenge, we propose Boxer, an algorithm to estimate static 3D bounding boxes (3DBBs) from 2D open-vocabulary object detections, posed images and optional depth either represented as a sparse point cloud or dense depth. At its core is BoxerNet, a transformer-based network which lifts 2D bounding box (2DBB) proposals into 3D, followed by multi-view fusion and geometric filtering to produce globally consistent de-duplicated 3DBBs in metric world space. Boxer leverages the power of existing 2DBB detection algorithms (e.g. DETIC, OWLv2, SAM3) to localize objects in 2D. This allows the main BoxerNet model to focus on lifting to 3D rather than detecting, ultimately reducing the demand for costly annotated 3DBB training data. Extending the CuTR formulation, we incorporate an aleatoric uncertainty for robust regression, a median depth patch encoding to support sparse depth inputs, and large-scale training with over 1.2 million unique 3DBBs. BoxerNet outperforms state-of-the-art baselines in open-world 3DBB lifting, including CuTR in egocentric settings without dense depth (0.532 vs. 0.010 mAP) and on CA-1M with dense depth available (0.412 vs. 0.250 mAP).
### Title:
          Instantaneous Planning, Control and Safety for Navigation in Unknown Underwater Spaces
 - **Authors:** Veejay Karthik, Udit Ekansh, Tejal Bedmutha, Shivam Vishwakarma, Rohan Deshpande, Leena Vachhani
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Navigating autonomous underwater vehicles (AUVs) in unknown environments is significantly challenging due to poor visibility, weak signal transmission, and dynamic water currents. These factors pose challenges in accurate global localization, reliable communication, and obstacle avoidance. Local sensing provides critical real time environmental data to enable online decision making. However, the inherent noise in underwater sensor measurements introduces uncertainty, complicating planning and control. To address these challenges, we propose an integrated planning and control framework that leverages real time sensor data to dynamically induce closed loop AUV trajectories, ensuring robust obstacle avoidance and enhanced maneuverability in tight spaces. By planning motion based on pre designed feedback controllers, the approach reduces the computational complexity needed for carrying out online optimizations and enhances operational safety in complex underwater spaces. The proposed method is validated through ROS Gazebo simulations on the RexRov AUV, demonstrating its efficacy. Its performance is evaluated by comparison against PID based tracking methods, and quantifying localization errors in dead reckoning as the AUV transitions into the target communication range.
### Title:
          Rethinking IRSTD: Single-Point Supervision Guided Encoder-only Framework is Enough for Infrared Small Target Detection
 - **Authors:** Rixiang Ni, Boyang Li, Jun Chen, Yonghao Li, Feiyu Ren, Yuji Wang, Haoyang Yuan, Wujiao He, Wei An
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Infrared small target detection (IRSTD) aims to separate small targets from clutter backgrounds. Extensive research is dedicated to the pixel-level supervision-guided "encoder-decoder" segmentation paradigm. Although having achieved promising performance, they neglect the fact that small targets only occupy a few pixels and are usually accompanied with blurred boundary caused by clutter backgrounds. Based on this observation, we argue that the first principle of IRSTD should be target localization instead of separating all target region accompanied with indistinguishable background noise. In this paper, we reformulate IRSTD as a centroid regression task and propose a novel Single-Point Supervision guided Infrared Probabilistic Response Encoding method (namely, SPIRE), which is indeed challenging due to the mismatch between reduced supervision network and equivalent output. Specifically, we first design a Point-Response Prior Supervision (PRPS), which transforms single-point annotations into probabilistic response map consistent with infrared point-target response characteristics, with a High-Resolution Probabilistic Encoder (HRPE) that enables encoder-only, end-to-end regression without decoder reconstruction. By preserving high-resolution features and increasing effective supervision density, SPIRE alleviates optimization instability under sparse target distributions. Finally, extensive experiments on various IRSTD benchmarks, including SIRST-UAVB and SIRST4 demonstrate that SPIRE achieves competitive target-level detection performance with consistently low false alarm rate (Fa) and significantly reduced computational cost. Code is publicly available at: this https URL.
### Title:
          LSGS-Loc: Towards Robust 3DGS-Based Visual Localization for Large-Scale UAV Scenarios
 - **Authors:** Xiang Zhang, Tengfei Wang, Fang Xu, Xin Wang, Zongqian Zhan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual localization in large-scale UAV scenarios is a critical capability for autonomous systems, yet it remains challenging due to geometric complexity and environmental variations. While 3D Gaussian Splatting (3DGS) has emerged as a promising scene representation, existing 3DGS-based visual localization methods struggle with robust pose initialization and sensitivity to rendering artifacts in large-scale settings. To address these limitations, we propose LSGS-Loc, a novel visual localization pipeline tailored for large-scale 3DGS scenes. Specifically, we introduce a scale-aware pose initialization strategy that combines scene-agnostic relative pose estimation with explicit 3DGS scale constraints, enabling geometrically grounded localization without scene-specific training. Furthermore, in the pose refinement, to mitigate the impact of reconstruction artifacts such as blur and floaters, we develop a Laplacian-based reliability masking mechanism that guides photometric refinement toward high-quality regions. Extensive experiments on large-scale UAV benchmarks demonstrate that our method achieves state-of-the-art accuracy and robustness for unordered image queries, significantly outperforming existing 3DGS-based approaches. Code is available at: this https URL
### Title:
          Learning to Synergize Semantic and Geometric Priors for Limited-Data Wheat Disease Segmentation
 - **Authors:** Shijie Wang, Zijian Wang, Yadan Luo, Scott Chapman, Xin Yu, Zi Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Wheat disease segmentation is fundamental to precision agriculture but faces severe challenges from significant intra-class temporal variations across growth stages. Such substantial appearance shifts make collecting a representative dataset for training from scratch both labor-intensive and impractical. To address this, we propose SGPer, a Semantic-Geometric Prior Synergization framework that treats wheat disease segmentation under limited data as a coupled task of disease-specific semantic perception and disease boundary localization. Our core insight is that pretrained DINOv2 provides robust category-aware semantic priors to handle appearance shifts, which can be converted into coarse spatial prompts to guide SAM for the precise localization of disease boundaries. Specifically, SGPer designs disease-sensitive adapters with multiple disease-friendly filters and inserts them into both DINOv2 and SAM to align their pretrained representations with disease-specific characteristics. To operationalize this synergy, SGPer transforms DINOv2-derived features into dense, category-specific point prompts to ensure comprehensive spatial coverage of all disease regions. To subsequently eliminate prompt redundancy and ensure highly accurate mask generation, it dynamically filters these dense candidates by cross-referencing SAM's iterative mask confidence with the category-specific semantic consistency derived from DINOv2. Ultimately, SGPer distills a highly informative set of prompts to activate SAM's geometric priors, achieving precise and robust segmentation that remains strictly invariant to temporal appearance changes. Extensive evaluations demonstrate that SGPer consistently achieves state-of-the-art performance on wheat disease and organ segmentation benchmarks, especially in data-constrained scenarios.
### Title:
          On the Role of Fault Localization Context for LLM-Based Program Repair
 - **Authors:** Melika Sepidband, Hung Viet Pham, Hadi Hemmati
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fault Localization (FL) is a key component of Large Language Model (LLM)-based Automated Program Repair (APR), yet its impact remains underexplored. In particular, it is unclear how much localization is needed, whether additional context beyond the predicted buggy location is beneficial, and how such context should be retrieved. We conduct a large-scale empirical study on 500 SWE-bench Verified instances using GPT-5-mini, evaluating 61 configurations that vary file-level, element-level, and line-level context. Our results show that more context does not consistently improve repair performance. File-level localization is the dominant factor, yielding a 15-17x improvement over a no-file baseline. Expanding file context is often associated with improved performance, with successful repairs most commonly observed in configurations with approximately 6-10 relevant files. Element-level context expansion provides conditional gains that depend strongly on the file context quality, while line-level context expansion frequently degrades performance due to noise amplification. LLM-based retrieval generally outperforms structural heuristics while using fewer files and tokens. Overall, the most effective FL context strategy typically combines a broad semantic understanding at higher abstraction levels with precise line-level localization. These findings challenge our assumption that increasing the localization context uniformly improves APR, and provide practical guidance for designing LLM-based FL strategies.
### Title:
          Unifying VLM-Guided Flow Matching and Spectral Anomaly Detection for Interpretable Veterinary Diagnosis
 - **Authors:** Pu Wang, Zhixuan Mao, Jialu Li, Zhuoran Zheng, Dianjie Lu, Youshan Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automatic diagnosis of canine pneumothorax is challenged by data scarcity and the need for trustworthy models. To address this, we first introduce a public, pixel-level annotated dataset to facilitate research. We then propose a novel diagnostic paradigm that reframes the task as a synergistic process of signal localization and spectral detection. For localization, our method employs a Vision-Language Model (VLM) to guide an iterative Flow Matching process, which progressively refines segmentation masks to achieve superior boundary accuracy. For detection, the segmented mask is used to isolate features from the suspected lesion. We then apply Random Matrix Theory (RMT), a departure from traditional classifiers, to analyze these features. This approach models healthy tissue as predictable random noise and identifies pneumothorax by detecting statistically significant outlier eigenvalues that represent a non-random pathological signal. The high-fidelity localization from Flow Matching is crucial for purifying the signal, thus maximizing the sensitivity of our RMT detector. This synergy of generative segmentation and first-principles statistical analysis yields a highly accurate and interpretable diagnostic system (source code is available at: this https URL).
### Title:
          DetailVerifyBench: A Benchmark for Dense Hallucination Localization in Long Image Captions
 - **Authors:** Xinran Wang, Yuxuan Zhang, Xiao Zhang, Haolong Yan, Muxi Diao, Songyu Xu, Zhonghao Yan, Hongbing Li, Kongming Liang, Zhanyu Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurately detecting and localizing hallucinations is a critical task for ensuring high reliability of image captions. In the era of Multimodal Large Language Models (MLLMs), captions have evolved from brief sentences into comprehensive narratives, often spanning hundreds of words. This shift exponentially increases the challenge: models must now pinpoint specific erroneous spans or words within extensive contexts, rather than merely flag response-level inconsistencies. However, existing benchmarks lack the fine granularity and domain diversity required to evaluate this capability. To bridge this gap, we introduce DetailVerifyBench, a rigorous benchmark comprising 1,000 high-quality images across five distinct domains. With an average caption length of over 200 words and dense, token-level annotations of multiple hallucination types, it stands as the most challenging benchmark for precise hallucination localization in the field of long image captioning to date. Our benchmark is available at this https URL.
### Title:
          SGANet: Semantic and Geometric Alignment for Multimodal Multi-view Anomaly Detection
 - **Authors:** Letian Bai, Chengyu Tao, Juan Du
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-view anomaly detection aims to identify surface defects on complex objects using observations captured from multiple viewpoints. However, existing unsupervised methods often suffer from feature inconsistency arising from viewpoint variations and modality discrepancies. To address these challenges, we propose a Semantic and Geometric Alignment Network (SGANet), a unified framework for multimodal multi-view anomaly detection that effectively combines semantic and geometric alignment to learn physically coherent feature representations across viewpoints and modalities. SGANet consists of three key components. The Selective Cross-view Feature Refinement Module (SCFRM) selectively aggregates informative patch features from adjacent views to enhance cross-view feature interaction. The Semantic-Structural Patch Alignment (SSPA) enforces semantic alignment across modalities while maintaining structural consistency under viewpoint transformations. The Multi-View Geometric Alignment (MVGA) further aligns geometrically corresponding patches across viewpoints. By jointly modeling feature interaction, semantic and structural consistency, and global geometric correspondence, SGANet effectively enhances anomaly detection performance in multimodal multi-view settings. Extensive experiments on the SiM3D and Eyecandies datasets demonstrate that SGANet achieves state-of-the-art performance in both anomaly detection and localization, validating its effectiveness in realistic industrial scenarios.
### Title:
          PhageBench: Can LLMs Understand Raw Bacteriophage Genomes?
 - **Authors:** Yusen Hou, Weicai Long, Haitao Hu, Houcheng Su, Junning Feng, Yanlin Zhang
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Genomics (q-bio.GN)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bacteriophages, often referred to as the dark matter of the biosphere, play a critical role in regulating microbial ecosystems and in antibiotic alternatives. Thus, accurate interpretation of their genomes holds significant scientific and practical value. While general-purpose Large Language Models (LLMs) excel at understanding biological texts, their ability to directly interpret raw nucleotide sequences and perform biological reasoning remains underexplored. To address this, we introduce PhageBench, the first benchmark designed to evaluate phage genome understanding by mirroring the workflow of bioinformatics experts. The dataset contains 5,600 high-quality samples covering five core tasks across three stages: Screening, Quality Control, and Phenotype Annotation. Our evaluation of eight LLMs reveals that general-purpose reasoning models significantly outperform random baselines in phage contig identification and host prediction, demonstrating promising potential for genomic understanding. However, they exhibit significant limitations in complex reasoning tasks involving long-range dependencies and fine-grained functional localization. These findings highlight the necessity of developing next-generation models with enhanced reasoning capabilities for biological sequences.
### Title:
          Overview of Bayesian Solvers in EEG Distributed Source Models: Prior Selection, Algorithmic Implementation, and Depth Bias Reduction
 - **Authors:** Joonas Lahtinen, Alexandra Koulouri
 - **Subjects:** Subjects:
Numerical Analysis (math.NA); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Electroencephalography (EEG) source imaging aims to reconstruct the spatial distribution of neural activity within the brain from non-invasive scalp measurements. This inverse problem is severely ill-posed due to the low spatial resolution of EEG and the presence of measurement noise, necessitating robust regularization techniques. Bayesian approaches provide a principled framework for incorporating prior knowledge into the solution, where regularization naturally arises through prior distributions and their associated hyperparameters. In this work, we provide an overview of key Bayesian methods for EEG source imaging based on Gaussian, Laplace, and group Laplace priors, with particular emphasis on hierarchical models that promote sparsity. We analyze the connections between these hierarchical formulations and classical optimization techniques, and provide an analytical description of their implementation using expectation -maximization and alternating optimization algorithms. To address the issue of depth bias where deeper sources are systematically underestimated or mislocalized - we extend a statistical signal-to-noise ratio (SNR) framework to derive depth-weighted priors that account for differences in how strongly sources at different depths are reflected in the measurements. Finally, we illustrate the behaviour of the considered models through simulation studies involving sources at varying depths. The results highlight the impact of prior selection and depth weighting on reconstruction accuracy and demonstrate the importance of informed model design for depth-sensitive EEG source localization.
### Title:
          Edge Intelligence for Satellite-based Earth Observation: Scheduling Image Acquisition and Processing
 - **Authors:** Beatriz Soret, Antonio M. Mercado-Martínez, Antonio Jurado-Navas, Nicolai D. Lyholm, Marco Moretti, Petar Popovski, Israel Leyva-Mayorga
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern Earth Observation (EO) missions generate massive volumes of imagery that challenge existing downlink and ground-processing capabilities, particularly for time-critical applications. This work investigates how a low Earth orbit (LEO) satellite constellation equipped with heterogeneous edge computing resources can enable real-time semantic processing of data acquired by EO satellites. We introduce an energy-aware framework that optimizes the use of resources accounting for data acquisition, computing, and communication constraints. Although we focus on maritime surveillance, the formulation is task-agnostic and accommodates a broad class of semantic and goal-oriented inference problems. Specifically, we formulate two coupled optimization problems: (i) observation scheduling, which selects image acquisition opportunities while accounting for turbulence-induced image degradation and energy budget, and (ii) processing scheduling, which allocates semantic workloads across onboard and ground processors. We evaluate these mechanisms for the task of detection and localization of vessels, for which we quantify the benefits of turbulence-aware observation scheduling for preserving image quality and experimentally characterize the execution-time distribution of YOLOv8 on different computing platforms. Results demonstrate that task- and turbulence-aware observation scheduling can significantly improve the quality and quantity of observed targets. Furthermore, cooperative edge processing within the constellation substantially reduces power consumption compared to traditional downlink-centric architectures. These findings highlight the potential of distributed edge intelligence to enhance the responsiveness and autonomy of future satellite-based EO systems.
### Title:
          QiMeng-PRepair: Precise Code Repair via Edit-Aware Reward Optimization
 - **Authors:** Changxin Ke, Rui Zhang, Jiaming Guo, Yuanbo Wen, Li Ding, Shuo Wang, Xuyuan Zhu, Xiong Peng, Di Huang, Zidong Du, Xing Hu, Qi Guo, Yunji Chen
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) achieve strong program repair performance but often suffer from over-editing, where excessive modifications overwrite correct code and hinder bug localization. We systematically quantify its impact and introduce precise repair task, which maximizes reuse of correct code while fixing only buggy parts. Building on this insight, we propose PRepair, a framework that mitigates over-editing and improves repair accuracy. PRepair has two components: Self-Breaking, which generates diverse buggy programs via controlled bug injection and min-max sampling, and Self-Repairing, which trains models with Edit-Aware Group Relative Policy Optimization (EA-GRPO) using an edit-aware reward to encourage minimal yet correct edits. Experiments show that PRepair improves repair precision by up to 31.4% under $\mathrm{fix}_1@1$, a metric that jointly considers repair correctness and extent, and significantly increases decoding throughput when combined with speculative editing, demonstrating its potential for precise and practical code repair.
### Title:
          Attention, May I Have Your Decision? Localizing Generative Choices in Diffusion Models
 - **Authors:** Katarzyna Zaleska, Łukasz Popek, Monika Wysoczańska, Kamil Deja
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-to-image diffusion models exhibit remarkable generative capabilities, yet their internal operations remain opaque, particularly when handling prompts that are not fully descriptive. In such scenarios, models must make implicit decisions to generate details not explicitly specified in the text. This work investigates the hypothesis that this decision-making process is not diffuse but is computationally localized within the model's architecture. While existing localization techniques focus on prompt-related interventions, we notice that such explicit conditioning may differ from implicit decisions. Therefore, we introduce a probing-based localization technique to identify the layers with the highest attribute separability for concepts. Our findings indicate that the resolution of ambiguous concepts is governed principally by self-attention layers, identifying them as the most effective point for intervention. Based on this discovery, we propose ICM (Implicit Choice-Modification) - a precise steering method that applies targeted interventions to a small subset of layers. Extensive experiments confirm that intervening on these specific self-attention layers yields superior debiasing performance compared to existing state-of-the-art methods, minimizing artifacts common to less precise approaches. The code is available at this https URL.
## Keyword: transformer
### Title:
          Generative AI for Video Trailer Synthesis: From Extractive Heuristics to Autoregressive Creativity
 - **Authors:** Abhishek Dharmaratnakar, Srivaths Ranganathan, Debanshu Das, Anushree Sinha
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Human-Computer Interaction (cs.HC); Information Retrieval (cs.IR); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The domain of automatic video trailer generation is currently undergoing a profound paradigm shift, transitioning from heuristic-based extraction methods to deep generative synthesis. While early methodologies relied heavily on low-level feature engineering, visual saliency, and rule-based heuristics to select representative shots, recent advancements in Large Language Models (LLMs), Multimodal Large Language Models (MLLMs), and diffusion-based video synthesis have enabled systems that not only identify key moments but also construct coherent, emotionally resonant narratives. This survey provides a comprehensive technical review of this evolution, with a specific focus on generative techniques including autoregressive Transformers, LLM-orchestrated pipelines, and text-to-video foundation models like OpenAI's Sora and Google's Veo. We analyze the architectural progression from Graph Convolutional Networks (GCNs) to Trailer Generation Transformers (TGT), evaluate the economic implications of automated content velocity on User-Generated Content (UGC) platforms, and discuss the ethical challenges posed by high-fidelity neural synthesis. By synthesizing insights from recent literature, this report establishes a new taxonomy for AI-driven trailer generation in the era of foundation models, suggesting that future promotional video systems will move beyond extractive selection toward controllable generative editing and semantic reconstruction of trailers.
### Title:
          Phase-Associative Memory: Sequence Modeling in Complex Hilbert Space
 - **Authors:** Gowrav Vishwakarma, Christopher J. Agostino
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Phase-Associative Memory (PAM), a recurrent sequence model in which all representations are complex-valued, associations accumulate in a matrix state $S_{t}$ $\in$ $\mathbb{C}^{d \times d}$ via outer products, and retrieval operates through the conjugate inner product $K_t^* \cdot Q_t / \sqrt{d}$. At $\sim$100M parameters on WikiText-103, PAM reaches validation perplexity 30.0, within $\sim$10\% of a matched transformer (27.1) trained under identical conditions, despite $4\times$ arithmetic overhead from complex computation and no custom kernels. We trace the experimental path from vector-state models, where holographic binding fails due to the $O(1/\sqrt{n})$ capacity degradation of superposed associations, to the matrix state that resolves it. The competitiveness of an architecture whose native operations are complex-valued superposition and conjugate retrieval is consistent with recent empirical evidence that semantic interpretation in both humans and large language models exhibits non-classical contextuality, and we discuss what this implies for the choice of computational formalism in language modeling.
### Title:
          Vintix II: Decision Pre-Trained Transformer is a Scalable In-Context Reinforcement Learner
 - **Authors:** Andrei Polubarov, Lyubaykin Nikita, Alexander Derevyagin, Artyom Grishin, Igor Saprygin, Aleksandr Serkov, Mark Averchenko, Daniil Tikhonov, Maksim Zhdanov, Alexander Nikulin, Ilya Zisman, Albina Klepach, Alexey Zemtsov, Vladislav Kurenkov
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent progress in in-context reinforcement learning (ICRL) has demonstrated its potential for training generalist agents that can acquire new tasks directly at inference. Algorithm Distillation (AD) pioneered this paradigm and was subsequently scaled to multi-domain settings, although its ability to generalize to unseen tasks remained limited. The Decision Pre-Trained Transformer (DPT) was introduced as an alternative, showing stronger in-context reinforcement learning abilities in simplified domains, but its scalability had not been established. In this work, we extend DPT to diverse multi-domain environments, applying Flow Matching as a natural training choice that preserves its interpretation as Bayesian posterior sampling. As a result, we obtain an agent trained across hundreds of diverse tasks that achieves clear gains in generalization to the held-out test set. This agent improves upon prior AD scaling and demonstrates stronger performance in both online and offline inference, reinforcing ICRL as a viable alternative to expert distillation for training generalist agents.
### Title:
          LSRM: High-Fidelity Object-Centric Reconstruction via Scaled Context Windows
 - **Authors:** Zhengqin Li, Cheng Zhang, Jakob Engel, Zhao Dong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce the Large Sparse Reconstruction Model to study how scaling transformer context windows impacts feed-forward 3D reconstruction. Although recent object-centric feed-forward methods deliver robust, high-quality reconstruction, they still lag behind dense-view optimization in recovering fine-grained texture and appearance. We show that expanding the context window -- by substantially increasing the number of active object and image tokens -- remarkably narrows this gap and enables high-fidelity 3D object reconstruction and inverse rendering. To scale effectively, we adapt native sparse attention in our architecture design, unlocking its capacity for 3D reconstruction with three key contributions: (1) an efficient coarse-to-fine pipeline that focuses computation on informative regions by predicting sparse high-resolution residuals; (2) a 3D-aware spatial routing mechanism that establishes accurate 2D-3D correspondences using explicit geometric distances rather than standard attention scores; and (3) a custom block-aware sequence parallelism strategy utilizing an All-gather-KV protocol to balance dynamic, sparse workloads across GPUs. As a result, LSRM handles 20x more object tokens and >2x more image tokens than prior state-of-the-art (SOTA) methods. Extensive evaluations on standard novel-view synthesis benchmarks show substantial gains over the current SOTA, yielding 2.5 dB higher PSNR and 40% lower LPIPS. Furthermore, when extending LSRM to inverse rendering tasks, qualitative and quantitative evaluations on widely-used benchmarks demonstrate consistent improvements in texture and geometry details, achieving an LPIPS that matches or exceeds that of SOTA dense-view optimization methods. Code and model will be released on our project page.
### Title:
          Boxer: Robust Lifting of Open-World 2D Bounding Boxes to 3D
 - **Authors:** Daniel DeTone, Tianwei Shen, Fan Zhang, Lingni Ma, Julian Straub, Richard Newcombe, Jakob Engel
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Detecting and localizing objects in space is a fundamental computer vision problem. While much progress has been made to solve 2D object detection, 3D object localization is much less explored and far from solved, especially for open-world categories. To address this research challenge, we propose Boxer, an algorithm to estimate static 3D bounding boxes (3DBBs) from 2D open-vocabulary object detections, posed images and optional depth either represented as a sparse point cloud or dense depth. At its core is BoxerNet, a transformer-based network which lifts 2D bounding box (2DBB) proposals into 3D, followed by multi-view fusion and geometric filtering to produce globally consistent de-duplicated 3DBBs in metric world space. Boxer leverages the power of existing 2DBB detection algorithms (e.g. DETIC, OWLv2, SAM3) to localize objects in 2D. This allows the main BoxerNet model to focus on lifting to 3D rather than detecting, ultimately reducing the demand for costly annotated 3DBB training data. Extending the CuTR formulation, we incorporate an aleatoric uncertainty for robust regression, a median depth patch encoding to support sparse depth inputs, and large-scale training with over 1.2 million unique 3DBBs. BoxerNet outperforms state-of-the-art baselines in open-world 3DBB lifting, including CuTR in egocentric settings without dense depth (0.532 vs. 0.010 mAP) and on CA-1M with dense depth available (0.412 vs. 0.250 mAP).
### Title:
          Hierarchical Mesh Transformers with Topology-Guided Pretraining for Morphometric Analysis of Brain Structures
 - **Authors:** Yujian Xiong, Mohammad Farazi, Yanxi Chen, Wenhui Zhu, Xuanzhao Dong, Natasha Lepore, Yi Su, Raza Mushtaq, Stephen Foldes, Andrew Yang, Yalin Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Neurons and Cognition (q-bio.NC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Representation learning on large-scale unstructured volumetric and surface meshes poses significant challenges in neuroimaging, especially when models must incorporate diverse vertex-level morphometric descriptors, such as cortical thickness, curvature, sulcal depth, and myelin content, which carry subtle disease-related signals. Current approaches either ignore these clinically informative features or support only a single mesh topology, restricting their use across imaging pipelines. We introduce a hierarchical transformer framework designed for heterogeneous mesh analysis that operates on spatially adaptive tree partitions constructed from simplicial complexes of arbitrary order. This design accommodates both volumetric and surface discretizations within a single architecture, enabling efficient multi-scale attention without topology-specific modifications. A feature projection module maps variable-length per-vertex clinical descriptors into the spatial hierarchy, separating geometric structure from feature dimensionality and allowing seamless integration of different neuroimaging feature sets. Self-supervised pretraining via masked reconstruction of both coordinates and morphometric channels on large unlabeled cohorts yields a transferable encoder backbone applicable to diverse downstream tasks and mesh modalities. We validate our approach on Alzheimer's disease classification and amyloid burden prediction using volumetric brain meshes from ADNI, as well as focal cortical dysplasia detection on cortical surface meshes from the MELD dataset, achieving state-of-the-art results across all benchmarks.
### Title:
          On the Geometry of Positional Encodings in Transformers
 - **Authors:** Giansalvo Cirrincione
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural language models process sequences of words, but the mathematical operations inside them are insensitive to the order in which words appear. Positional encodings are the component added to remedy this. Despite their importance, positional encodings have been designed largely by trial and error, without a mathematical theory of what they ought to do. This paper develops such a theory. Four results are established. First, any Transformer without a positional signal cannot solve any task sensitive to word order (Necessity Theorem). Second, training assigns distinct vector representations to distinct sequence positions at every global minimiser, under mild and verifiable conditions (Positional Separation Theorem). Third, the best achievable approximation to an information-optimal encoding is constructed via classical multidimensional scaling (MDS) on the Hellinger distance between positional distributions; the quality of any encoding is measured by a single number, the stress (Proposition 5, Algorithm 1). Fourth, the optimal encoding has effective rank r = rank(B) <= n-1 and can be represented with r(n+d) parameters instead of nd (minimal parametrisation result). Appendix A develops a proof of the Monotonicity Conjecture within the Neural Tangent Kernel (NTK) regime for masked language modelling (MLM) losses, sequence classification losses, and general losses satisfying a positional sufficiency condition, through five lemmas. Experiments on SST-2 and IMDB with BERT-base confirm the theoretical predictions and reveal that Attention with Linear Biases (ALiBi) achieves much lower stress than the sinusoidal encoding and Rotary Position Embedding (RoPE), consistent with a rank-1 interpretation of the MDS encoding under approximate shift-equivariance.
### Title:
          Exemplar Retrieval Without Overhypothesis Induction: Limits of Distributional Sequence Learning in Early Word Learning
 - **Authors:** Jon-Paul Cacioli
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Background: Children do not simply learn that balls are round and blocks are square. They learn that shape is the kind of feature that tends to define object categories -- a second-order generalisation known as an overhypothesis [1, 2]. What kind of learning mechanism is sufficient for this inductive leap? Methods: We trained autoregressive transformer language models (3.4M-25.6M parameters) on synthetic corpora in which shape is the stable feature dimension across categories, with eight conditions controlling for alternative explanations. Results: Across 120 pre-registered runs evaluated on a 1,040-item wug test battery, every model achieved perfect first-order exemplar retrieval (100%) while second-order generalisation to novel nouns remained at chance (50-52%), a result confirmed by equivalence testing. A feature-swap diagnostic revealed that models rely on frame-to-feature template matching rather than structured noun-to-domain-to-feature abstraction. Conclusions: These results reveal a clear limitation of autoregressive distributional sequence learning under developmental-scale training conditions.
### Title:
          EAGLE: Edge-Aware Graph Learning for Proactive Delivery Delay Prediction in Smart Logistics Networks
 - **Authors:** Zhiming Xue, Menghao Huo, Yujue Wang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern logistics networks generate rich operational data streams at every warehouse node and transportation lane -- from order timestamps and routing records to shipping manifests -- yet predicting delivery delays remains predominantly reactive. Existing predictive approaches typically treat this problem either as a tabular classification task, ignoring network topology, or as a time-series anomaly detection task, overlooking the spatial dependencies of the supply chain graph. To bridge this gap, we propose a hybrid deep learning framework for proactive supply chain risk management. The proposed method jointly models temporal order-flow dynamics via a lightweight Transformer patch encoder and inter-hub relational dependencies through an Edge-Aware Graph Attention Network (E-GAT), optimized via a multi-task learning objective. Evaluated on the real-world DataCo Smart Supply Chain dataset, our framework achieves consistent improvements over baseline methods, yielding an F1-score of 0.8762 and an AUC-ROC of 0.9773. Across four independent random seeds, the framework exhibits a cross-seed F1 standard deviation of only 0.0089 -- a 3.8 times improvement over the best ablated variant -- achieving the strongest balance of predictive accuracy and training stability among all evaluated models.
### Title:
          DIA-HARM: Dialectal Disparities in Harmful Content Detection Across 50 English Dialects
 - **Authors:** Jason Lucas, Matt Murtagh, Ali Al-Lawati, Uchendu Uchendu, Adaku Uchendu, Dongwon Lee
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Harmful content detectors-particularly disinformation classifiers-are predominantly developed and evaluated on Standard American English (SAE), leaving their robustness to dialectal variation unexplored. We present DIA-HARM, the first benchmark for evaluating disinformation detection robustness across 50 English dialects spanning U.S., British, African, Caribbean, and Asia-Pacific varieties. Using Multi-VALUE's linguistically grounded transformations, we introduce D3 (Dialectal Disinformation Detection), a corpus of 195K samples derived from established disinformation benchmarks. Our evaluation of 16 detection models reveals systematic vulnerabilities: human-written dialectal content degrades detection by 1.4-3.6% F1, while AI-generated content remains stable. Fine-tuned transformers substantially outperform zero-shot LLMs (96.6% vs. 78.3% best-case F1), with some models exhibiting catastrophic failures exceeding 33% degradation on mixed content. Cross-dialectal transfer analysis across 2,450 dialect pairs shows that multilingual models (mDeBERTa: 97.2% average F1) generalize effectively, while monolingual models like RoBERTa and XLM-RoBERTa fail on dialectal inputs. These findings demonstrate that current disinformation detectors may systematically disadvantage hundreds of millions of non-SAE speakers worldwide. We release the DIA-HARM framework, D3 corpus, and evaluation tools: this https URL
### Title:
          CT Saturation Detection and Compensation: A Hybrid Physical Model- and Data-Driven Method
 - **Authors:** Songhao Yang, Yubo Zhang, Zhiguo Hao, Zexuan Lin, Baohui Zhang
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current transformer (CT) saturation is one of the dominant causes of relay protection devices' malfunctions, which pose a threat to the safe operation of the power system. To address this problem, we propose a hybrid physical model- and data-driven method. The method firstly detects the CT saturation and then compensates it to reproduce the real waveform. Considering the multi-factor and strong nonlinearity of CT saturation, a data-driven model, namely the Fully Convolutional Network (FCN), is built to detect the operation status of CT. As for the compensation, a physical model of short-circuit current is used for its conciseness and universality. Through tactfully integrating the data model and the physical model, the proposed method is endowed with two major merits: the arduous adjustment of universal thresholds and parameters in existing methods is avoided, and the deficiency in generalization and interpretability of the data-driven method is assuaged. Simulation and experimental results verify the effectiveness of the proposed method. Furthermore, its application potential to future protection is explored.
### Title:
          Generative Channel Knowledge Base With Environmental Information for Joint Source-Channel Coding in Semantic Communications
 - **Authors:** Xudong Long, Hao Chen, Dan Wang, Chen Qiu, Nan Ma, Xiaodong Xu, Yubin Zhao
 - **Subjects:** Subjects:
Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic knowledge bases are regarded as a promising technology for upcoming 6G communications. However, existing studies mainly focus on source-side semantic modeling while overlooking the structural impact of propagation environments on semantic transmission performance. To address this issue, we propose a generative channel knowledge base (CKB) with environmental information to facilitate joint source-channel coding (JSCC) in semantic communications (SemCom) systems. First, to enable the construction of the CKB, an environment-aware dataset is established by collecting spatial position information, global image features, fine-grained semantic features, and the corresponding channel matrices. A region-of-interest (ROI)-based filtering algorithm is further designed to remove semantic components that are irrelevant to signal propagation. Second, a Transformer-based generative framework is developed to learn the mapping between multidimensional environmental information and channel matrices. A self-attention mechanism is introduced to adaptively fuse heterogeneous features, enabling the construction of a structured CKB. Third, a CKB-driven JSCC SemCom architecture is proposed, where the generated channel knowledge is injected into both of the encoder and decoder to jointly exploit source semantics and channel-environment priors in an end-to-end manner. Experimental results demonstrate that the proposed multidimensional feature fusion method achieves a channel matrix estimation error at the $10^{-3}$ level. Moreover, the CKB-driven JSCC SemCom framework integrated into SemCom systems significantly outperforms existing benchmark schemes in terms of transmission performance.
### Title:
          3DTurboQuant: Training-Free Near-Optimal Quantization for 3D Reconstruction Models
 - **Authors:** Jae Joong Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Every existing method for compressing 3D Gaussian Splatting, NeRF, or transformer-based 3D reconstructors requires learning a data-dependent codebook through per-scene fine-tuning. We show this is unnecessary. The parameter vectors that dominate storage in these models, 45-dimensional spherical harmonics in 3DGS and 1024-dimensional key-value vectors in DUSt3R, fall in a dimension range where a single random rotation transforms any input into coordinates with a known Beta distribution. This makes precomputed, data-independent Lloyd-Max quantization near-optimal, within a factor of 2.7 of the information-theoretic lower bound. We develop 3D, deriving (1) a dimension-dependent criterion that predicts which parameters can be quantized and at what bit-width before running any experiment, (2) norm-separation bounds connecting quantization MSE to rendering PSNR per scene, (3) an entry-grouping strategy extending rotation-based quantization to 2-dimensional hash grid features, and (4) a composable pruning-quantization pipeline with a closed-form compression ratio. On NeRF Synthetic, 3DTurboQuant compresses 3DGS by 3.5x with 0.02dB PSNR loss and DUSt3R KV caches by 7.9x with 39.7dB pointmap fidelity. No training, no codebook learning, no calibration data. Compression takes seconds. The code will be released (this https URL)
### Title:
          Geometrical Cross-Attention and Nonvoid Voxelization for Efficient 3D Medical Image Segmentation
 - **Authors:** Chenxin Yuan, Shoupeng Chen, Haojiang Ye, Yiming Miao, Limei Peng, Pin-Han Ho
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate segmentation of 3D medical scans is crucial for clinical diagnostics and treatment planning, yet existing methods often fail to achieve both high accuracy and computational efficiency across diverse anatomies and imaging modalities. To address these challenges, we propose GCNV-Net, a novel 3D medical segmentation framework that integrates a Tri-directional Dynamic Nonvoid Voxel Transformer (3DNVT), a Geometrical Cross-Attention module (GCA), and Nonvoid Voxelization. The 3DNVT dynamically partitions relevant voxels along the three orthogonal anatomical planes, namely the transverse, sagittal, and coronal planes, enabling effective modeling of complex 3D spatial dependencies. The GCA mechanism explicitly incorporates geometric positional information during multi-scale feature fusion, significantly enhancing fine-grained anatomical segmentation accuracy. Meanwhile, Nonvoid Voxelization processes only informative regions, greatly reducing redundant computation without compromising segmentation quality, and achieves a 56.13% reduction in FLOPs and a 68.49% reduction in inference latency compared to conventional voxelization. We evaluate GCNV-Net on multiple widely used benchmarks: BraTS2021, ACDC, MSD Prostate, MSD Pancreas, and AMOS2022. Our method achieves state-of-the-art segmentation performance across all datasets, outperforming the best existing methods by 0.65% on Dice, 0.63% on IoU, 1% on NSD, and relatively 14.5% on HD95. All results demonstrate that GCNV-Net effectively balances accuracy and efficiency, and its robustness across diverse organs, disease conditions, and imaging modalities highlights strong potential for clinical deployment.
### Title:
          Turbulence-like 5/3 spectral scaling in contextual representations of language as a complex system
 - **Authors:** Zhongxin Yang, Chun Bao, Yuanwei Bin, Xiang I.A. Yang, Shiyi Chen
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Natural language is a complex system that exhibits robust statistical regularities. Here, we represent text as a trajectory in a high-dimensional embedding space generated by transformer-based language models, and quantify scale-dependent fluctuations along the token sequence using an embedding-step signal. Across multiple languages and corpora, the resulting power spectrum exhibits a robust power law with an exponent close to $5/3$ over an extended frequency range. This scaling is observed consistently in contextual embeddings from both human-written and AI-generated text, but is absent in static word embeddings and is disrupted by randomization of token order. These results show that the observed scaling reflects multiscale, context-dependent organization rather than lexical statistics alone. By analogy with the Kolmogorov spectrum in turbulence, our findings suggest that semantic information is integrated in a scale-free, self-similar manner across linguistic scales, and provide a quantitative, model-agnostic benchmark for studying complex structure in language representations.
### Title:
          Physics-Aligned Spectral Mamba: Decoupling Semantics and Dynamics for Few-Shot Hyperspectral Target Detection
 - **Authors:** Luqi Gong, Qixin Xie, Yue Chen, Ziqiang Chen, Fanda Fan, Shuai Zhao, Chao Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Meta-learning facilitates few-shot hyperspectral target detection (HTD), but adapting deep backbones remains challenging. Full-parameter fine-tuning is inefficient and prone to overfitting, and existing methods largely ignore the frequency-domain structure and spectral band continuity of hyperspectral data, limiting spectral adaptation and cross-domain this http URL address these challenges, we propose SpecMamba, a parameter-efficient and frequency-aware framework that decouples stable semantic representation from agile spectral adaptation. Specifically, we introduce a Discrete Cosine Transform Mamba Adapter (DCTMA) on top of frozen Transformer representations. By projecting spectral features into the frequency domain via DCT and leveraging Mamba's linear-complexity state-space recursion, DCTMA explicitly captures global spectral dependencies and band continuity while avoiding the redundancy of full fine-tuning. Furthermore, to address prototype drift caused by limited sample sizes, we design a Prior-Guided Tri-Encoder (PGTE) that allows laboratory spectral priors to guide the optimization of the learnable adapter without disrupting the stable semantic feature space. Finally, a Self-Supervised Pseudo-Label Mapping (SSPLM) strategy is developed for test-time adaptation, enabling efficient decision boundary refinement through uncertainty-aware sampling and dual-path consistency constraints. Extensive experiments on multiple public datasets demonstrate that SpecMamba consistently outperforms state-of-the-art methods in detection accuracy and cross-domain generalization.
### Title:
          Same Graph, Different Likelihoods: Calibration of Autoregressive Graph Generators via Permutation-Equivalent Encodings
 - **Authors:** Laurits Fredsgaard, Aaron Thomas, Michael Riis Andersen, Mikkel N. Schmidt, Mahito Sugiyama
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autoregressive graph generators define likelihoods via a sequential construction process, but these likelihoods are only meaningful if they are consistent across all linearizations of the same graph. Segmented Eulerian Neighborhood Trails (SENT), a recent linearization method, converts graphs into sequences that can be perfectly decoded and efficiently processed by language models, but admit multiple equivalent linearizations of the same graph. We quantify violations in assigned negative log-likelihood (NLL) using the coefficient of variation across equivalent linearizations, which we call Linearization Uncertainty (LU). Training transformers under four linearization strategies on two datasets, we show that biased orderings achieve lower NLL on their native order but exhibit expected calibration error (ECE) two orders of magnitude higher under random permutation, indicating that these models have learned their training linearization rather than the underlying graph. On the molecular graph benchmark QM9, NLL for generated graphs is negatively correlated with molecular stability (AUC $=0.43$), while LU achieves AUC $=0.85$, suggesting that permutation-based evaluation provides a more reliable quality check for generated molecules. Code is available at this https URL
### Title:
          YoNER: A New Yorùbá Multi-domain Named Entity Recognition Dataset
 - **Authors:** Peace Busola Falola, Jesujoba O. Alabi, Solomon O. Akinola, Folashade T. Ogunajo, Emmanuel Oluwadunsin Alabi, David Ifeoluwa Adelani
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Named Entity Recognition (NER) is a foundational NLP task, yet research in Yorùbá has been constrained by limited and domain-specific resources. Existing resources, such as MasakhaNER (a manually annotated news-domain corpus) and WikiAnn (automatically created from Wikipedia), are valuable but restricted in domain coverage. To address this gap, we present YoNER, a new multidomain Yorùbá NER dataset that extends entity coverage beyond news and Wikipedia. The dataset comprises about 5,000 sentences and 100,000 tokens collected from five domains including Bible, Blogs, Movies, Radio broadcast and Wikipedia, and annotated with three entity types: Person (PER), Organization (ORG) and Location (LOC), following CoNLL-style guidelines. Annotation was conducted manually by three native Yorùbá speakers, with an inter-annotator agreement of over 0.70, ensuring high quality and consistency. We benchmark several transformer encoder models using cross-domain experiments with MasakhaNER 2.0, and we also assess the effect of few-shot in-domain data using YoNER and cross-lingual setups with English datasets. Our results show that African-centric models outperform general multilingual models for Yorùbá, but cross-domain performance drops substantially, particularly for blogs and movie domains. Furthermore, we observed that closely related formal domains, such as news and Wikipedia, transfer more effectively. In addition, we introduce a new Yorùbá-specific language model (OyoBERT) that outperforms multilingual models in in-domain evaluation. We publicly release the YoNER dataset and pretrained OyoBERT models to support future research on Yorùbá natural language processing.
### Title:
          From Uniform to Learned Knots: A Study of Spline-Based Numerical Encodings for Tabular Deep Learning
 - **Authors:** Manish Kumar, Anton Frederik Thielmann, Christoph Weisser, Benjamin Säfken
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Numerical preprocessing remains an important component of tabular deep learning, where the representation of continuous features can strongly affect downstream performance. Although its importance is well established for classical statistical and machine learning models, the role of explicit numerical preprocessing in tabular deep learning remains less well understood. In this work, we study this question with a focus on spline-based numerical encodings. We investigate three spline families for encoding numerical features, namely B-splines, M-splines, and integrated splines (I-splines), under uniform, quantile-based, target-aware, and learnable-knot placement. For the learnable-knot variants, we use a differentiable knot parameterization that enables stable end-to-end optimization of knot locations jointly with the backbone. We evaluate these encodings on a diverse collection of public regression and classification datasets using MLP, ResNet, and FT-Transformer backbones, and compare them against common numerical preprocessing baselines. Our results show that the effect of numerical encodings depends strongly on the task, output size, and backbone. For classification, piecewise-linear encoding (PLE) is the most robust choice overall, while spline-based encodings remain competitive. For regression, no single encoding dominates uniformly. Instead, performance depends on the spline family, knot-placement strategy, and output size, with larger gains typically observed for MLP and ResNet than for FT-Transformer. We further find that learnable-knot variants can be optimized stably under the proposed parameterization, but may substantially increase training cost, especially for M-spline and I-spline expansions. Overall, the results show that numerical encodings should be assessed not only in terms of predictive performance, but also in terms of computational overhead.
### Title:
          CRFT: Consistent-Recurrent Feature Flow Transformer for Cross-Modal Image Registration
 - **Authors:** Xuecong Liu, Mengzhu Ding, Zixuan Sun, Zhang Li, Xichao Teng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Consistent-Recurrent Feature Flow Transformer (CRFT), a unified coarse-to-fine framework based on feature flow learning for robust cross-modal image registration. CRFT learns a modality-independent feature flow representation within a transformer-based architecture that jointly performs feature alignment and flow estimation. The coarse stage establishes global correspondences through multi-scale feature correlation, while the fine stage refines local details via hierarchical feature fusion and adaptive spatial reasoning. To enhance geometric adaptability, an iterative discrepancy-guided attention mechanism with a Spatial Geometric Transform (SGT) recurrently refines the flow field, progressively capturing subtle spatial inconsistencies and enforcing feature-level consistency. This design enables accurate alignment under large affine and scale variations while maintaining structural coherence across modalities. Extensive experiments on diverse cross-modal datasets demonstrate that CRFT consistently outperforms state-of-the-art registration methods in both accuracy and robustness. Beyond registration, CRFT provides a generalizable paradigm for multimodal spatial correspondence, offering broad applicability to remote sensing, autonomous navigation, and medical imaging. Code and datasets are publicly available at this https URL.
### Title:
          MPM: Mutual Pair Merging for Efficient Vision Transformers
 - **Authors:** Simon Ravé, Pejman Rasti, David Rousseau
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Decreasing sequence length is a common way to accelerate transformers, but prior token reduction work often targets classification and reports proxy metrics rather than end-to-end latency. For semantic segmentation, token reduction is further constrained by the need to reconstruct dense, pixel-aligned features, and on modern accelerators the overhead of computing merge maps can erase expected gains. We propose Mutual Pair Merging (MPM), a training-free token aggregation module that forms mutual nearest-neighbor pairs in cosine space, averages each pair, and records a merge map enabling a gather-based reconstruction before the decoder so that existing segmentation heads can be used unchanged. MPM introduces no learned parameters and no continuous compression knob (no keep-rate or threshold). The speed-accuracy trade-off is set by a discrete insertion schedule. We benchmark end-to-end latency on an NVIDIA H100 GPU (with and without FlashAttention-2) and a Raspberry Pi 5 across standard segmentation datasets. On ADE20K, MPM reduces per-image latency by up to 60% for ViT-Tiny on Raspberry Pi 5, and increases throughput by up to 20% on H100 with FlashAttention-2 while keeping the mIoU drop below 3%. These results suggest that simple, reconstruction-aware, training-free token merging can translate into practical wall-clock gains for segmentation when overhead is explicitly accounted for.
### Title:
          Learn to Rank: Visual Attribution by Learning Importance Ranking
 - **Authors:** David Schinagl, Christian Fruhwirth-Reisinger, Alexander Prutsch, Samuel Schulter, Horst Possegger
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Interpreting the decisions of complex computer vision models is crucial to establish trust and accountability, especially in safety-critical domains. An established approach to interpretability is generating visual attribution maps that highlight regions of the input most relevant to the model's prediction. However, existing methods face a three-way trade-off. Propagation-based approaches are efficient, but they can be biased and architecture-specific. Meanwhile, perturbation-based methods are causally grounded, yet they are expensive and for vision transformers often yield coarse, patch-level explanations. Learning-based explainers are fast but usually optimize surrogate objectives or distill from heuristic teachers. We propose a learning scheme that instead optimizes deletion and insertion metrics directly. Since these metrics depend on non-differentiable sorting and ranking, we frame them as permutation learning and replace the hard sorting with a differentiable relaxation using Gumbel-Sinkhorn. This enables end-to-end training through attribution-guided perturbations of the target model. During inference, our method produces dense, pixel-level attributions in a single forward pass with optional, few-step gradient refinement. Our experiments demonstrate consistent quantitative improvements and sharper, boundary-aligned explanations, particularly for transformer-based vision models.
### Title:
          EEG-MFTNet: An Enhanced EEGNet Architecture with Multi-Scale Temporal Convolutions and Transformer Fusion for Cross-Session Motor Imagery Decoding
 - **Authors:** Panagiotis Andrikopoulos, Siamak Mehrkanoon
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Brain-computer interfaces (BCIs) enable direct communication between the brain and external devices, providing critical support for individuals with motor impairments. However, accurate motor imagery (MI) decoding from electroencephalography (EEG) remains challenging due to noise and cross-session variability. This study introduces EEG-MFTNet, a novel deep learning model based on the EEGNet architecture, enhanced with multi-scale temporal convolutions and a Transformer encoder stream. These components are designed to capture both short and long-range temporal dependencies in EEG signals. The model is evaluated on the SHU dataset using a subject-dependent cross-session setup, outperforming baseline models, including EEGNet and its recent derivatives. EEG-MFTNet achieves an average classification accuracy of 58.9% while maintaining low computational complexity and inference latency. The results highlight the model's potential for real-time BCI applications and underscore the importance of architectural innovations in improving MI decoding. This work contributes to the development of more robust and adaptive BCI systems, with implications for assistive technologies and neurorehabilitation.
### Title:
          Modeling Patient Care Trajectories with Transformer Hawkes Processes
 - **Authors:** Saumya Pandey, Varun Chandola
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Quantitative Methods (q-bio.QM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Patient healthcare utilization consists of irregularly time-stamped events, such as outpatient visits, inpatient admissions, and emergency encounters, forming individualized care trajectories. Modeling these trajectories is crucial for understanding utilization patterns and predicting future care needs, but is challenging due to temporal irregularity and severe class imbalance. In this work, we build on the Transformer Hawkes Process framework to model patient trajectories in continuous time. By combining Transformer-based history encoding with Hawkes process dynamics, the model captures event dependencies and jointly predicts event type and time-to-event. To address extreme imbalance, we introduce an imbalance-aware training strategy using inverse square-root class weighting. This improves sensitivity to rare but clinically important events without altering the data distribution. Experiments on real-world data demonstrate improved performance and provide clinically meaningful insights for identifying high-risk patient populations.
### Title:
          MARL-GPT: Foundation Model for Multi-Agent Reinforcement Learning
 - **Authors:** Maria Nesterova, Mikhail Kolosov, Anton Andreychuk, Egor Cherepanov, Oleg Bulichev, Alexey Kovalev, Konstantin Yakovlev, Aleksandr Panov, Alexey Skrynnik
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in multi-agent reinforcement learning (MARL) have demonstrated success in numerous challenging domains and environments, but typically require specialized models for each task. In this work, we propose a coherent methodology that makes it possible for a single GPT-based model to learn and perform well across diverse MARL environments and tasks, including StarCraft Multi-Agent Challenge, Google Research Football and POGEMA. Our method, MARL-GPT, applies offline reinforcement learning to train at scale on the expert trajectories (400M for SMACv2, 100M for GRF, and 1B for POGEMA) combined with a single transformer-based observation encoder that requires no task-specific tuning. Experiments show that MARL-GPT achieves competitive performance compared to specialized baselines in all tested environments. Thus, our findings suggest that it is, indeed, possible to build a multi-task transformer-based model for a wide variety of (significantly different) multi-agent problems paving the way to the fundamental MARL model (akin to ChatGPT, Llama, Mistral etc. in natural language modeling).
### Title:
          Multi-Modal Landslide Detection from Sentinel-1 SAR and Sentinel-2 Optical Imagery Using Multi-Encoder Vision Transformers and Ensemble Learning
 - **Authors:** Ioannis Nasios
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Landslides represent a major geohazard with severe impacts on human life, infrastructure, and ecosystems, underscoring the need for accurate and timely detection approaches to support disaster risk reduction. This study proposes a modular, multi-model framework that fuses Sentinel-2 optical imagery with Sentinel-1 Synthetic Aperture Radar (SAR) data, for robust landslide detection. The methodology leverages multi-encoder vision transformers, where each data modality is processed through separate lightweight pretrained encoders, achieving strong performance in landslide detection. In addition, the integration of multiple models, particularly the combination of neural networks and gradient boosting models (LightGBM and XGBoost), demonstrates the power of ensemble learning to further enhance accuracy and robustness. Derived spectral indices, such as NDVI, are integrated alongside original bands to enhance sensitivity to vegetation and surface changes. The proposed methodology achieves a state-of-the-art F1 score of 0.919 on landslide detection, addressing a patch-based classification task rather than pixel-level segmentation and operating without pre-event Sentinel-2 data, highlighting its effectiveness in a non-classical change detection setting. It also demonstrated top performance in a machine learning competition, achieving a strong balance between precision and recall and highlighting the advantages of explicitly leveraging the complementary strengths of optical and radar data. The conducted experiments and research also emphasize scalability and operational applicability, enabling flexible configurations with optical-only, SAR-only, or combined inputs, and offering a transferable framework for broader natural hazard monitoring and environmental change applications. Full training and inference code can be found in this https URL.
### Title:
          A Mixture of Experts Foundation Model for Scanning Electron Microscopy Image Analysis
 - **Authors:** Sk Miraj Ahmed, Yuewei Lin, Chuntian Cao, Shinjae Yoo, Xinpei Wu, Won-Il Lee, Nikhil Tiwale, Dan N. Le, Thi Thu Huong Chu, Jiyoung Kim, Kevin G. Yager, Chang-Yong Nam
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scanning Electron Microscopy (SEM) is indispensable in modern materials science, enabling high-resolution imaging across a wide range of structural, chemical, and functional investigations. However, SEM imaging remains constrained by task-specific models and labor-intensive acquisition processes that limit its scalability across diverse applications. Here, we introduce the first foundation model for SEM images, pretrained on a large corpus of multi-instrument, multi-condition scientific micrographs, enabling generalization across diverse material systems and imaging conditions. Leveraging a self-supervised transformer architecture, our model learns rich and transferable representations that can be fine-tuned or adapted to a wide range of downstream tasks. As a compelling demonstration, we focus on defocus-to-focus image translation-an essential yet underexplored challenge in automated microscopy pipelines. Our method not only restores focused detail from defocused inputs without paired supervision but also outperforms state-of-the-art techniques across multiple evaluation metrics. This work lays the groundwork for a new class of adaptable SEM models, accelerating materials discovery by bridging foundational representation learning with real-world imaging needs.
### Title:
          Gated-SwinRMT: Unifying Swin Windowed Attention with Retentive Manhattan Decay via Input-Dependent Gating
 - **Authors:** Dipan Maity, Suman Mondal, Arindam Roy
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Gated-SwinRMT, a family of hybrid vision transformers that combine the shifted-window attention of the Swin Transformer with the Manhattan-distance spatial decay of Retentive Networks (RMT), augmented by input-dependent gating. Self-attention is decomposed into consecutive width-wise and height-wise retention passes within each shifted window, where per-head exponential decay masks provide a two-dimensional locality prior without learned positional biases. Two variants are proposed. \textbf{Gated-SwinRMT-SWAT} substitutes softmax with sigmoid activation, implements balanced ALiBi slopes with multiplicative post-activation spatial decay, and gates the value projection via SwiGLU; the Normalized output implicitly suppresses uninformative attention scores. \textbf{Gated-SwinRMT-Retention} retains softmax-normalized retention with an additive log-space decay bias and incorporates an explicit G1 sigmoid gate -- projected from the block input and applied after local context enhancement (LCE) but prior to the output projection~$W_O$ -- to alleviate the low-rank $W_V \!\cdot\! W_O$ bottleneck and enable input-dependent suppression of attended outputs. We assess both variants on Mini-ImageNet ($224{\times}224$, 100 classes) and CIFAR-10 ($32{\times}32$, 10 classes) under identical training protocols, utilizing a single GPU due to resource limitations. At ${\approx}77$--$79$\,M parameters, Gated-SwinRMT-SWAT achieves $80.22\%$ and Gated-SwinRMT-Retention $78.20\%$ top-1 test accuracy on Mini-ImageNet, compared with $73.74\%$ for the RMT baseline. On CIFAR-10 -- where small feature maps cause the adaptive windowing mechanism to collapse attention to global scope -- the accuracy advantage compresses from $+6.48$\,pp to $+0.56$\,pp.
### Title:
          Toward Aristotelian Medical Representations: Backpropagation-Free Layer-wise Analysis for Interpretable Generalized Metric Learning on MedMNIST
 - **Authors:** Michael Karnes, Alper Yilmaz
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While deep learning has achieved remarkable success in medical imaging, the "black-box" nature of backpropagation-based models remains a significant barrier to clinical adoption. To bridge this gap, we propose Aristotelian Rapid Object Modeling (A-ROM), a framework built upon the Platonic Representation Hypothesis (PRH). This hypothesis posits that models trained on vast, diverse datasets converge toward a universal and objective representation of reality. By leveraging the generalizable metric space of pretrained Vision Transformers (ViTs), A-ROM enables the rapid modeling of novel medical concepts without the computational burden or opacity of further gradient-based fine-tuning. We replace traditional, opaque decision layers with a human-readable concept dictionary and a k-Nearest Neighbors (kNN) classifier to ensure the model's logic remains interpretable. Experiments on the MedMNIST v2 suite demonstrate that A-ROM delivers performance competitive with standard benchmarks while providing a simple and scalable, "few-shot" solution that meets the rigorous transparency demands of modern clinical environments.
### Title:
          CoStream: Codec-Guided Resource-Efficient System for Video Streaming Analytics
 - **Authors:** Yulin Zou, Yan Chen, Wenyan Chen, JooYoung Park, Shivaraman Nitin, Luo Tao, Francisco Romero, Dmitrii Ustiugov
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video streaming analytics is a crucial workload for vision-language model serving, but the high cost of multimodal inference limits scalability. Prior systems reduce inference cost by exploiting temporal and spatial redundancy in video streams, but they target either the vision transformer (ViT) or the LLM with a limited view, leaving end-to-end opportunities untapped. Moreover, existing methods incur significant overhead to identify redundancy, either through offline profiling and training or costly online computation, making them ill-suited for dynamic real-time streams. We present CoStream, a codec-guided streaming video analytics system built on a key observation that video codecs already extract the temporal and spatial structure of each stream as a byproduct of compression. CoStream treats this codec metadata as a low-cost runtime signal to unify optimization across video decoding, visual processing, and LLM prefilling, with transmission reduction as an inherent benefit of operating directly on compressed bitstreams. This drives codec-guided patch pruning before ViT encoding and selective key-value cache refresh during LLM prefilling, both of which are fully online and do not require offline training. Experiments show that CoStream achieves up to 3x throughput improvement and up to 87% GPU compute reduction over state-of-the-art baselines, while maintaining competitive accuracy with only 0-8% F1 drop.
### Title:
          Short Data, Long Context: Distilling Positional Knowledge in Transformers
 - **Authors:** Patrick Huber, Ernie Chang, Chinnadhurai Sankar, Rylan Conway, Igor Fedorov, Md Rifat Arefin, Adithya Sagar
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Extending the context window of language models typically requires expensive long-context pre-training, posing significant challenges for both training efficiency and data collection. In this paper, we present evidence that long-context retrieval capabilities can be transferred to student models through logit-based knowledge distillation, even when training exclusively on packed short-context samples within a long-context window. We provide comprehensive insights through the lens of Rotary Position Embedding (RoPE) and establish three key findings. First, consistent with prior work, we show that phase-wise RoPE scaling, which maximizes rotational spectrum utilization at each training stage, also achieves the best long-context performance in knowledge distillation setups. Second, we demonstrate that logit-based knowledge distillation can directly enable positional information transfer. Using an experimental setup with packed repeated token sequences, we trace the propagation of positional perturbations from query and key vectors through successive transformer layers to output logits, revealing that positional information systematically influences the teacher's output distribution and, in turn, the distillation signal received by the student model. Third, our analysis uncovers structured update patterns in the query state during long-context extension, with distinct parameter spans exhibiting strong sensitivity to long-context training.
### Title:
          LAG-XAI: A Lie-Inspired Affine Geometric Framework for Interpretable Paraphrasing in Transformer Latent Spaces
 - **Authors:** Olexander Mazurets, Olexander Barmak, Leonid Bedratyuk, Iurii Krak
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern Transformer-based language models achieve strong performance in natural language processing tasks, yet their latent semantic spaces remain largely uninterpretable black boxes. This paper introduces LAG-XAI (Lie Affine Geometry for Explainable AI), a novel geometric framework that models paraphrasing not as discrete word substitutions, but as a structured affine transformation within the embedding space. By conceptualizing paraphrasing as a continuous geometric flow on a semantic manifold, we propose a computationally efficient mean-field approximation, inspired by local Lie group actions. This allows us to decompose paraphrase transitions into geometrically interpretable components: rotation, deformation, and translation. Experiments on the noisy PIT-2015 Twitter corpus, encoded with Sentence-BERT, reveal a "linear transparency" phenomenon. The proposed affine operator achieves an AUC of 0.7713. By normalizing against random chance (AUC 0.5), the model captures approximately 80% of the non-linear baseline's effective classification capacity (AUC 0.8405), offering explicit parametric interpretability in exchange for a marginal drop in absolute accuracy. The model identifies fundamental geometric invariants, including a stable matrix reconfiguration angle (~27.84°) and near-zero deformation, indicating local isometry. Cross-domain generalization is confirmed via direct cross-corpus validation on an independent TURL dataset. Furthermore, the practical utility of LAG-XAI is demonstrated in LLM hallucination detection: using a "cheap geometric check," the model automatically detected 95.3% of factual distortions on the HaluEval dataset by registering deviations beyond the permissible semantic corridor. This approach provides a mathematically grounded, resource-efficient path toward the mechanistic interpretability of Transformers.
### Title:
          Extending ZACH-ViT to Robust Medical Imaging: Corruption and Adversarial Stress Testing in Low-Data Regimes
 - **Authors:** Athanasios Angelakis, Marta Gomez-Barrero
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The recently introduced ZACH-ViT (Zero-token Adaptive Compact Hierarchical Vision Transformer) formalized a compact permutation-invariant Vision Transformer for medical imaging and argued that architectural alignment with spatial structure can matter more than universal benchmark dominance. Its design was motivated by the observation that positional embeddings and a dedicated class token encode fixed spatial assumptions that may be suboptimal when spatial organization is weakly informative, locally distributed, or variable across biomedical images. The foundational study established a regime-dependent clean performance profile across MedMNIST, but did not examine robustness in detail. In this work, we present the first robustness-focused extension of ZACH-ViT by evaluating its behavior under common image corruptions and adversarial perturbations in the same low-data setting. We compare ZACH-ViT with three scratch-trained compact baselines, ABMIL, Minimal-ViT, and TransMIL, on seven MedMNIST datasets using 50 samples per class, fixed hyperparameters, and five random seeds. Across the benchmark, ZACH-ViT achieves the best overall mean rank on clean data (1.57) and under common corruptions (1.57), indicating a favorable balance between baseline predictive performance and robustness to realistic image degradation. Under adversarial stress, all models deteriorate substantially; nevertheless, ZACH-ViT remains competitive, ranking first under FGSM (2.00) and second under PGD (2.29), where ABMIL performs best overall. These results extend the original ZACH-ViT narrative: the advantages of compact permutation-invariant transformers are not limited to clean evaluation, but can persist under realistic perturbation stress in low-data medical imaging, while adversarial robustness remains an open challenge for all evaluated models.
### Title:
          PoM: A Linear-Time Replacement for Attention with the Polynomial Mixer
 - **Authors:** David Picard, Nicolas Dufour, Lucas Degeorge, Arijit Ghosh, Davide Allegro, Tom Ravaud, Yohann Perron, Corentin Sautier, Zeynep Sonat Baltaci, Fei Meng, Syrine Kalleli, Marta López-Rauhut, Thibaut Loiseau, Ségolène Albouy, Raphael Baena, Elliot Vincent, Loic Landrieu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper introduces the Polynomial Mixer (PoM), a novel token mixing mechanism with linear complexity that serves as a drop-in replacement for self-attention. PoM aggregates input tokens into a compact representation through a learned polynomial function, from which each token retrieves contextual information. We prove that PoM satisfies the contextual mapping property, ensuring that transformers equipped with PoM remain universal sequence-to-sequence approximators. We replace standard self-attention with PoM across five diverse domains: text generation, handwritten text recognition, image generation, 3D modeling, and Earth observation. PoM matches the performance of attention-based models while drastically reducing computational cost when working with long sequences. The code is available at this https URL.
### Title:
          Target Policy Optimization
 - **Authors:** Jean Kaddour
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In RL, given a prompt, we sample a group of completions from a model and score them. Two questions follow: which completions should gain probability mass, and how should the parameters move to realize that change? Standard policy-gradient methods answer both at once, so the update can overshoot or undershoot depending on the learning rate, clipping, and other optimizer choices. We introduce \emph{Target Policy Optimization} (TPO), which separates the two questions. Given scored completions, TPO constructs a target distribution $q_i \propto p_i^{\,\mathrm{old}} \exp(u_i)$ and fits the policy to it by cross-entropy. The loss gradient on sampled-completion logits is $p^\theta - q$, which vanishes once the policy matches the target. On tabular bandits, transformer sequence tasks, and billion-parameter LLM RLVR, TPO matches PG, PPO, GRPO, and DG on easy tasks and substantially outperforms them under sparse reward. Code is available at this https URL.
## Keyword: autonomous driving
### Title:
          Part-Level 3D Gaussian Vehicle Generation with Joint and Hinge Axis Estimation
 - **Authors:** Shiyao Qian, Yuan Ren, Dongfeng Bai, Bingbing Liu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Simulation is essential for autonomous driving, yet current frameworks often model vehicles as rigid assets and fail to capture part-level articulation. With perception algorithms increasingly leveraging dynamics such as wheel steering or door opening, realistic simulation requires animatable vehicle representations. Existing CAD-based pipelines are limited by library coverage and fixed templates, preventing faithful reconstruction of in-the-wild instances. We propose a generative framework that, from a single image or sparse multi-view input, synthesizes an animatable 3D Gaussian vehicle. Our method addresses two challenges: (i) large 3D asset generators are optimized for static quality but not articulation, leading to distortions at part boundaries when animated; and (ii) segmentation alone cannot provide the kinematic parameters required for motion. To overcome this, we introduce a part-edge refinement module that enforces exclusive Gaussian ownership and a kinematic reasoning head that predicts joint positions and hinge axes of movable parts. Together, these components enable faithful part-aware simulation, bridging the gap between static generation and animatable vehicle models.
### Title:
          Probabilistic Tree Inference Enabled by FDSOI Ferroelectric FETs
 - **Authors:** Pengyu Ren, Xingtian Wang, Boyang Cheng, Jiahui Duan, Giuk Kim, Xuezhong Niu, Halid Mulaosmanovic, Stefan Duenkel, Sven Beyer, X. Sharon Hu, Ningyuan Cao, Kai Ni
 - **Subjects:** Subjects:
Emerging Technologies (cs.ET); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Artificial intelligence applications in autonomous driving, medical diagnostics, and financial systems increasingly demand machine learning models that can provide robust uncertainty quantification, interpretability, and noise resilience. Bayesian decision trees (BDTs) are attractive for these tasks because they combine probabilistic reasoning, interpretable decision-making, and robustness to noise. However, existing hardware implementations of BDTs based on CPUs and GPUs are limited by memory bottlenecks and irregular processing patterns, while multi-platform solutions exploiting analog content-addressable memory (ACAM) and Gaussian random number generators (GRNGs) introduce integration complexity and energy overheads. Here we report a monolithic FDSOI-FeFET hardware platform that natively supports both ACAM and GRNG functionalities. The ferroelectric polarization of FeFETs enables compact, energy-efficient multi-bit storage for ACAM, and band-to-band tunneling in the gate-to-drain overlap region and subsequent hole storage in the floating body provides a high-quality entropy source for GRNG. System-level evaluations demonstrate that the proposed architecture provides robust uncertainty estimation, interpretability, and noise tolerance with high energy efficiency. Under both dataset noise and device variations, it achieves over 40% higher classification accuracy on MNIST compared to conventional decision trees. Moreover, it delivers more than two orders of magnitude speedup over CPU and GPU baselines and over four orders of magnitude improvement in energy efficiency, making it a scalable solution for deploying BDTs in resource-constrained and safety-critical environments.
### Title:
          ICR-Drive: Instruction Counterfactual Robustness for End-to-End Language-Driven Autonomous Driving
 - **Authors:** Kaiser Hamid, Can Cui, Nade Liang
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent progress in vision-language-action (VLA) models has enabled language-conditioned driving agents to execute natural-language navigation commands in closed-loop simulation, yet standard evaluations largely assume instructions are precise and well-formed. In deployment, instructions vary in phrasing and specificity, may omit critical qualifiers, and can occasionally include misleading, authority-framed text, leaving instruction-level robustness under-measured. We introduce ICR-Drive, a diagnostic framework for instruction counterfactual robustness in end-to-end language-conditioned autonomous driving. ICR-Drive generates controlled instruction variants spanning four perturbation families: Paraphrase, Ambiguity, Noise, and Misleading, where Misleading variants conflict with the navigation goal and attempt to override intent. We replay identical CARLA routes under matched simulator configurations and seeds to isolate performance changes attributable to instruction language. Robustness is quantified using standard CARLA Leaderboard metrics and per-family performance degradation relative to the baseline instruction. Experiments on LMDrive and BEVDriver show that minor instruction changes can induce substantial performance drops and distinct failure modes, revealing a reliability gap for deploying embodied foundation models in safety-critical driving.
### Title:
          Not All Agents Matter: From Global Attention Dilution to Risk-Prioritized Game Planning
 - **Authors:** Kang Ding, Hongsong Wang, Jie Gui, Lei He
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end autonomous driving resides not in the integration of perception and planning, but rather in the dynamic multi-agent game within a unified representation space. Most existing end-to-end models treat all agents equally, hindering the decoupling of real collision threats from complex backgrounds. To address this issue, We introduce the concept of Risk-Prioritized Game Planning, and propose GameAD, a novel framework that models end-to-end autonomous driving as a risk-aware game problem. The GameAD integrates Risk-Aware Topology Anchoring, Strategic Payload Adapter, Minimax Risk-Aware Sparse Attention, and Risk Consistent Equilibrium Stabilization to enable game theoretic decision making with risk prioritized interactions. We also present the Planning Risk Exposure metric, which quantifies the cumulative risk intensity of planned trajectories over a long horizon for safe autonomous driving. Extensive experiments on the nuScenes and Bench2Drive datasets show that our approach significantly outperforms state-of-the-art methods, especially in terms of trajectory safety.
### Title:
          Sparsity-Aware Voxel Attention and Foreground Modulation for 3D Semantic Scene Completion
 - **Authors:** Yu Xue, Longjun Gao, Yuanqi Su, HaoAng Lu, Xiaoning Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular Semantic Scene Completion (SSC) aims to reconstruct complete 3D semantic scenes from a single RGB image, offering a cost-effective solution for autonomous driving and robotics. However, the inherently imbalanced nature of voxel distributions, where over 93% of voxels are empty and foreground classes are rare, poses significant challenges. Existing methods often suffer from redundant emphasis on uninformative voxels and poor generalization to long-tailed categories. To address these issues, we propose VoxSAMNet (Voxel Sparsity-Aware Modulation Network), a unified framework that explicitly models voxel sparsity and semantic imbalance. Our approach introduces: (1) a Dummy Shortcut for Feature Refinement (DSFR) module that bypasses empty voxels via a shared dummy node while refining occupied ones with deformable attention; and (2) a Foreground Modulation Strategy combining Foreground Dropout (FD) and Text-Guided Image Filter (TGIF) to alleviate overfitting and enhance class-relevant features. Extensive experiments on the public benchmarks SemanticKITTI and SSCBench-KITTI-360 demonstrate that VoxSAMNet achieves state-of-the-art performance, surpassing prior monocular and stereo baselines with mIoU scores of 18.2% and 20.2%, respectively. Our results highlight the importance of sparsity-aware and semantics-guided design for efficient and accurate 3D scene completion, offering a promising direction for future research.
### Title:
          Appearance Decomposition Gaussian Splatting for Multi-Traversal Reconstruction
 - **Authors:** Yangyi Xiao, Siting Zhu, Baoquan Yang, Tianchen Deng, Yongbo Chen, Hesheng Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-traversal scene reconstruction is important for high-fidelity autonomous driving simulation and digital twin construction. This task involves integrating multiple sequences captured from the same geographical area at different times. In this context, a primary challenge is the significant appearance inconsistency across traversals caused by varying illumination and environmental conditions, despite the shared underlying geometry. This paper presents ADM-GS (Appearance Decomposition Gaussian Splatting for Multi-Traversal Reconstruction), a framework that applies an explicit appearance decomposition to the static background to alleviate appearance entanglement across traversals. For the static background, we decompose the appearance into traversal-invariant material, representing intrinsic material properties, and traversal-dependent illumination, capturing lighting variations. Specifically, we propose a neural light field that utilizes a frequency-separated hybrid encoding strategy. By incorporating surface normals and explicit reflection vectors, this design separately captures low-frequency diffuse illumination and high-frequency specular reflections. Quantitative evaluations on the Argoverse 2 and Waymo Open datasets demonstrate the effectiveness of ADM-GS. In multi-traversal experiments, our method achieves a +0.98 dB PSNR improvement over existing latent-based baselines while producing more consistent appearance across traversals. Code will be available at this https URL.
