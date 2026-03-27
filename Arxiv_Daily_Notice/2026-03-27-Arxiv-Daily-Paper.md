# Showing new listings for Friday, 27 March 2026
## Keyword: SLAM
There is no result 
## Keyword: odometry
There is no result 
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Saranga: MilliWatt Ultrasound for Navigation in Visually Degraded Environments on Palm-Sized Aerial Robots
 - **Authors:** Manoj Velmurugan, Phillip Brush, Colin Balfour, Richard J. Przybyla, Nitin J. Sanket
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tiny palm-sized aerial robots possess exceptional agility and cost-effectiveness in navigating confined and cluttered environments. However, their limited payload capacity directly constrains the sensing suite on-board the robot, thereby limiting critical navigational tasks in Global Positioning System (GPS)-denied wild scenes. Common methods for obstacle avoidance use cameras and LIght Detection And Ranging (LIDAR), which become ineffective in visually degraded conditions such as low visibility, dust, fog or darkness. Other sensors, such as RAdio Detection And Ranging (RADAR), have high power consumption, making them unsuitable for tiny aerial robots. Inspired by bats, we propose Saranga, a low-power ultrasound-based perception stack that localizes obstacles using a dual sonar array. We present two key solutions to combat the low Peak Signal-to-Noise Ratio of $-4.9$ decibels: physical noise reduction and a deep learning based denoising method. Firstly, we present a practical way to block propeller induced ultrasound noise on the weak echoes. The second solution is to train a neural network to utilize the \textcolor{black}{long horizon of ultrasound echoes} for finding signal patterns under high amounts of uncorrelated noise where classical methods were insufficient. We generalize to the real world by using a synthetic data generation pipeline and limited real noise data for training. We enable a palm-sized aerial robot to navigate in visually degraded conditions of dense fog, darkness, and snow in a cluttered environment with thin and transparent obstacles using only on-board sensing and computation. We provide extensive real world results to demonstrate the efficacy of our approach.
### Title:
          Towards Practical Lossless Neural Compression for LiDAR Point Clouds
 - **Authors:** Pengpeng Yu, Haoran Li, Runqing Jiang, Dingquan Li, Jing Wang, Liang Lin, Yulan Guo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR point clouds are fundamental to various applications, yet the extreme sparsity of high-precision geometric details hinders efficient context modeling, thereby limiting the compression speed and performance of existing methods. To address this challenge, we propose a compact representation for efficient predictive lossless coding. Our framework comprises two lightweight modules. First, the Geometry Re-Densification Module iteratively densifies encoded sparse geometry, extracts features at a dense scale, and then sparsifies the features for predictive coding. This module avoids costly computation on highly sparse details while maintaining a lightweight prediction head. Second, the Cross-scale Feature Propagation Module leverages occupancy cues from multiple resolution levels to guide hierarchical feature propagation, enabling information sharing across scales and reducing redundant feature extraction. Additionally, we introduce an integer-only inference pipeline to enable bit-exact cross-platform consistency, which avoids the entropy-coding collapse observed in existing neural compression methods and further accelerates coding. Experiments demonstrate competitive compression performance at real-time speed. Code will be released upon acceptance. Code is available at this https URL.
### Title:
          V2U4Real: A Real-world Large-scale Dataset for Vehicle-to-UAV Cooperative Perception
 - **Authors:** Weijia Li, Haoen Xiang, Tianxu Wang, Shuaibing Wu, Qiming Xia, Cheng Wang, Chenglu Wen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern autonomous vehicle perception systems are often constrained by occlusions, blind spots, and limited sensing range. While existing cooperative perception paradigms, such as Vehicle-to-Vehicle (V2V) and Vehicle-to-Infrastructure (V2I), have demonstrated their effectiveness in mitigating these challenges, they remain limited to ground-level collaboration and cannot fully address large-scale occlusions or long-range perception in complex environments. To advance research in cross-view cooperative perception, we present V2U4Real, the first large-scale real-world multi-modal dataset for Vehicle-to-UAV (V2U) cooperative object perception. V2U4Real is collected by a ground vehicle and a UAV equipped with multi-view LiDARs and RGB cameras. The dataset covers urban streets, university campuses, and rural roads under diverse traffic scenarios, comprising over 56K LiDAR frames, 56K multi-view camera images, and 700K annotated 3D bounding boxes across four classes. To support a wide range of research tasks, we establish benchmarks for single-agent 3D object detection, cooperative 3D object detection, and object tracking. Comprehensive evaluations of several state-of-the-art models demonstrate the effectiveness of V2U cooperation in enhancing perception robustness and long-range awareness. The V2U4Real dataset and codebase is available at this https URL.
### Title:
          Accurate Surface and Reflectance Modelling from 3D Radar Data with Neural Radiance Fields
 - **Authors:** Judith Treffler, Vladimír Kubelka, Henrik Andreasson, Martin Magnusson
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust scene representation is essential for autonomous systems to safely operate in challenging low-visibility environments. Radar has a clear advantage over cameras and lidars in these conditions due to its resilience to environmental factors such as fog, smoke, or dust. However, radar data is inherently sparse and noisy, making reliable 3D surface reconstruction challenging. To address these challenges, we propose a neural implicit approach for 3D mapping from radar point clouds, which jointly models scene geometry and view-dependent radar intensities. Our method leverages a memory-efficient hybrid feature encoding to learn a continuous Signed Distance Field (SDF) for surface reconstruction, while also capturing radar-specific reflective properties. We show that our approach produces smoother, more accurate 3D surface reconstructions compared to existing lidar-based reconstruction methods applied to radar data, and can reconstruct view-dependent radar intensities. We also show that in general, as input point clouds get sparser, neural implicit representations render more faithful surfaces, compared to traditional explicit SDFs and meshing techniques.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          Few TensoRF: Enhance the Few-shot on Tensorial Radiance Fields
 - **Authors:** Thanh-Hai Le, Hoang-Hau Tran, Trong-Nghia Vu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents Few TensoRF, a 3D reconstruction framework that combines TensorRF's efficient tensor based representation with FreeNeRF's frequency driven few shot regularization. Using TensorRF to significantly accelerate rendering speed and introducing frequency and occlusion masks, the method improves stability and reconstruction quality under sparse input views. Experiments on the Synthesis NeRF benchmark show that Few TensoRF method improves the average PSNR from 21.45 dB (TensorRF) to 23.70 dB, with the fine tuned version reaching 24.52 dB, while maintaining TensorRF's fast \(\approx10-15\) minute training time. Experiments on the THuman 2.0 dataset further demonstrate competitive performance in human body reconstruction, achieving 27.37 - 34.00 dB with only eight input images. These results highlight Few TensoRF as an efficient and data effective solution for real-time 3D reconstruction across diverse scenes.
## Keyword: mapping
### Title:
          Formal Semantics for Agentic Tool Protocols: A Process Calculus Approach
 - **Authors:** Andreas Schlapbach
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The emergence of large language model agents capable of invoking external tools has created urgent need for formal verification of agent protocols. Two paradigms dominate this space: Schema-Guided Dialogue (SGD), a research framework for zero-shot API generalization, and the Model Context Protocol (MCP), an industry standard for agent-tool integration. While both enable dynamic service discovery through schema descriptions, their formal relationship remains unexplored. Building on prior work establishing the conceptual convergence of these paradigms, we present the first process calculus formalization of SGD and MCP, proving they are structurally bisimilar under a well-defined mapping Phi. However, we demonstrate that the reverse mapping Phi^{-1} is partial and lossy, revealing critical gaps in MCP's expressivity. Through bidirectional analysis, we identify five principles -- semantic completeness, explicit action boundaries, failure mode documentation, progressive disclosure compatibility, and inter-tool relationship declaration -- as necessary and sufficient conditions for full behavioral equivalence. We formalize these principles as type-system extensions MCP+, proving MCP+ is isomorphic to SGD. Our work provides the first formal foundation for verified agent systems and establishes schema quality as a provable safety property.
### Title:
          Characterization of Off-wafer Pulse Communication in BrainScaleS Neuromorphic System
 - **Authors:** Bernhard Vogginger, Vasilis Thanasoulis, Johannes Partzsch, Christian Mayr
 - **Subjects:** Subjects:
Emerging Technologies (cs.ET); Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neuromorphic VLSI systems take inspiration from biology to enable efficient emulation of large-scale spiking neural networks and to explore new computational paradigms. To establish large neuromorphic systems, a sophisticated routing infrastructure is needed to communicate spikes between chips and to/from the host computer. For the BrainScaleS wafer-scale neuromorphic system considered in this work, especially the stimulation with input spikes and the recording of spikes is demanding, requiring high bandwidth and temporal resolution due to the accelerated emulation of neural dynamics 10.000 faster than biological real time. Here, we present a systematic characterization of the BrainScaleS off-wafer communication infrastructure implemented around Kintex7 FPGAs. The communication flow is characterized in terms of throughput, transmission delay, jitter and pulse loss. Further, we analyze the effect of the communication distortions (like pulse loss and jitter) on a neural benchmark model with highly varying spike activity. The presented methods and techniques for communication evaluation are general applicable and provide useful insights for the mapping of network models to the hardware such as the distribution of input spikes across communication channels.
### Title:
          A Dual-Threshold Probabilistic Knowing Value Logic
 - **Authors:** Shanxia Wang
 - **Subjects:** Subjects:
Logic in Computer Science (cs.LO); Logic (math.LO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce a dual-threshold probabilistic knowing value logic for uncertain multi-agent settings. The framework captures within a single formalism both probabilistic-threshold attitudes toward propositions and high-confidence attitudes toward term values, thereby connecting probabilistic epistemic logic with classical knowing value logic. It is especially motivated by privacy-sensitive scenarios in which an attacker assigns high posterior probability to a candidate sensitive value without guaranteeing that it is the true one. The main idea is to separate the threshold domains of propositional and value-oriented operators. While $K_i^\theta$ ranges over the full rational threshold interval, the knowing-value operator $Kv_i^\eta(t)$ is restricted to $(\frac{1}{2},1]$. This high-threshold restriction has a structural effect: once $\eta>\frac{1}{2}$, two distinct values cannot both satisfy the threshold, so uniqueness becomes automatic. Over probabilistic models with countably additive measures, $Kv_i^\eta(t)$ is interpreted as non-factive high-confidence value locking. We establish sound axiomatic systems for the framework and develop a two-layer construction based on type-space distributions and assignment-configuration mappings. This resolves the joint realization problem arising from probabilistic mass allocation and value-sensitive constraints, and yields a structured weak-completeness theorem for the high-threshold fragment.
### Title:
          Nonlinear Model Order Reduction on Quadratic Manifolds via Greedy Algorithms with Dimension-Dependent Regularization
 - **Authors:** Lijie Ji, Sabrina Rashid, Yanlai Chen, Zhu Wang
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traditional projection-based reduced-order modeling approximates the full-order model by projecting it onto a linear subspace. With a fast-decaying Kolmogorov $n$-width of the solution manifold, the resulting reduced-order model (ROM) can be an efficient and accurate emulator. However, for parametric partial differential equations with slowly decaying Kolmogorov $n$-width, the dimension of the linear subspace required for a reasonable accuracy becomes very large, which undermines computational efficiency. To address this limitation, quadratic manifold methods have recently been proposed. These data-driven methods first identify a quadratic mapping by minimizing the linear projection error over a large set of snapshots, often with the aid of regularization techniques to solve the associated minimization problem, and then use this mapping to construct ROMs. In this paper, we propose and test a novel enhancement to this quadratic manifold approach by introducing a first-of-its-kind double-greedy algorithm on the regularization parameters coupled with a standard greedy algorithm on the physical parameter. Our approach balances the trade-off between the accuracy of the quadratic mapping and the stability of the resulting nonlinear ROM, leading to a highly efficient and data-sparse algorithm. Numerical experiments conducted on equations such as linear transport, acoustic wave, advection-diffusion, and Burgers' demonstrate the accuracy, efficiency, and stability of the proposed algorithm.
### Title:
          Self-Corrected Image Generation with Explainable Latent Rewards
 - **Authors:** Yinyi Luo, Hrishikesh Gokhale, Marios Savvides, Jindong Wang, Shengfeng He
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite significant progress in text-to-image generation, aligning outputs with complex prompts remains challenging, particularly for fine-grained semantics and spatial relations. This difficulty stems from the feed-forward nature of generation, which requires anticipating alignment without fully understanding the output. In contrast, evaluating generated images is more tractable. Motivated by this asymmetry, we propose xLARD, a self-correcting framework that uses multimodal large language models to guide generation through Explainable LAtent RewarDs. xLARD introduces a lightweight corrector that refines latent representations based on structured feedback from model-generated references. A key component is a differentiable mapping from latent edits to interpretable reward signals, enabling continuous latent-level guidance from non-differentiable image-level evaluations. This mechanism allows the model to understand, assess, and correct itself during generation. Experiments across diverse generation and editing tasks show that xLARD improves semantic alignment and visual fidelity while maintaining generative priors. Code is available at this https URL.
### Title:
          C2W-Tune: Cavity-to -Wall Transfer Learning for Thin Atrial Wall Segmentation in 3D Late Gadolinium-enhanced Magnetic Resonance
 - **Authors:** Yusri Al-Sanaani, Rebecca Thornhill, Sreeraman Rajan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate segmentation of the left atrial (LA) wall in 3D late gadolinium-enhanced MRI (LGE-MRI) is essential for wall thickness mapping and fibrosis quantification, yet it remains challenging due to the wall's thinness, complex anatomy, and low contrast. We propose C2W-Tune, a two-stage cavity-to-wall transfer framework that leverages a high-accuracy LA cavity model as an anatomical prior to improve thin-wall delineation. Using a 3D U-Net with a ResNeXt encoder and instance normalization, Stage 1 pre-trains the network to segment the LA cavity, learning robust atrial representations. Stage 2 transfers these weights and adapts the network to LA wall segmentation using a progressive layer-unfreezing schedule to preserve endocardial features while enabling wall-specific refinement. Experiments on the 2018 LA Segmentation Challenge dataset demonstrate substantial gains over an architecture-matched baseline trained from scratch: wall Dice improves from 0.623 to 0.814, and Surface Dice at 1 mm improves from 0.553 to 0.731. Boundary errors were substantially reduced, with the 95th-percentile Hausdorff distance (HD95) decreasing from 2.95 mm to 2.55 mm and the average symmetric surface distance (ASSD) from 0.71 mm to 0.63 mm. Furthermore, even with reduced supervision (70 training volumes sampled from the same training pool), C2W-Tune achieved a Dice score of 0.78 and an HD95 of 3.15 mm, maintaining competitive performance and exceeding multi-class benchmarks that typically report Dice values around 0.6-0.7. These results show that anatomically grounded task transfer with controlled fine-tuning improves boundary accuracy for thin LA wall segmentation in 3D LGE-MRI.
### Title:
          Efficient ML-DSA Public Key Management Method with Identity for PKI and Its Application
 - **Authors:** Penghui Liu, Yi Niu, Xiaoxiong Zhong, Jiahui Wu, Weizhe Zhang, Kaiping Xue, Bin Xiao
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the rapid evolution of the Industrial Internet of Things (IIoT), the boundaries and scale of the Internet are continuously expanding. Consequently, the limitations of traditional certificate-based Public Key Infrastructure (PKI) have become increasingly evident, particularly in scenarios requiring large-scale certificate storage, verification, and frequent transmission. These challenges are expected to be further amplified by the widespread adoption of post-quantum cryptography. In this paper, we propose a novel identity-based public key management framework for PKI based on post-quantum cryptography, termed \textit{IPK-pq}. This approach implements an identity key generation protocol leveraging NIST ML-DSA and random matrix theory. Building on the concept of the Composite Public Key (CPK), \textit{IPK-pq} addresses the linear collusion problem inherent in CPK through an enhanced identity mapping mechanism. Furthermore, it simplifies the verification of the declared public key's authenticity, effectively reducing the complexity associated with certificate-based key management. We also provide a formal security proof for \textit{IPK-pq}, covering both individual private key components and the composite private key. To validate our approach, formally, we directly implement and evaluate \textit{IPK-pq} within a typical PKI application scenario: Resource PKI (RPKI). Comparative experimental results demonstrate that an RPKI system based on \textit{IPK-pq} yields significant improvements in efficiency and scalability. These results validate the feasibility and rationality of \textit{IPK-pq}, positioning it as a strong candidate for next-generation RPKI systems capable of securely managing large-scale routing information.
### Title:
          THEMIS: Towards Holistic Evaluation of MLLMs for Scientific Paper Fraud Forensics
 - **Authors:** Tzu-Yen Ma, Bo Zhang, Zichen Tang, Junpeng Ding, Haolin Tian, Yuanze Li, Zhuodi Hao, Zixin Ding, Zirui Wang, Xinyu Yu, Shiyao Peng, Yizhuo Zhao, Ruomeng Jiang, Yiling Huang, Peizhi Zhao, Jiayuan Chen, Weisheng Tan, Haocheng Gao, Yang Liu, Jiacheng Liu, Zhongjun Yang, Jiayu Huang, Haihong E
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present THEMIS, a novel multi-task benchmark designed to comprehensively evaluate multimodal large language models (MLLMs) on visual fraud reasoning within real-world academic scenarios. Compared to existing benchmarks, THEMIS introduces three major advances. (1) Real-World Scenarios and Complexity: Our benchmark comprises over 4,000 questions spanning seven scenarios, derived from authentic retracted-paper cases and carefully curated multimodal synthetic data. With 60.47% complex-texture images, THEMIS bridges the critical gap between existing benchmarks and the complexity of real-world academic fraud. (2) Fraud-Type Diversity and Granularity: THEMIS systematically covers five challenging fraud types and introduces 16 fine-grained manipulation operations. On average, each sample undergoes multiple stacked manipulation operations, with the diversity and difficulty of these manipulations demanding a high level of visual fraud reasoning from the models. (3) Multi-Dimensional Capability Evaluation: We establish a mapping from fraud types to five core visual fraud reasoning capabilities, thereby enabling an evaluation that reveals the distinct strengths and specific weaknesses of different models across these core capabilities. Experiments on 16 leading MLLMs show that even the best-performing model, GPT-5, achieves an overall performance of only 56.15%, demonstrating that our benchmark presents a stringent test. We expect THEMIS to advance the development of MLLMs for complex, real-world fraud reasoning tasks.
### Title:
          Goodness-of-pronunciation without phoneme time alignment
 - **Authors:** Jeremy H. M. Wong, Nancy F. Chen
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Human-Computer Interaction (cs.HC); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In speech evaluation, an Automatic Speech Recognition (ASR) model often computes time boundaries and phoneme posteriors for input features. However, limited data for ASR training hinders expansion of speech evaluation to low-resource languages. Open-source weakly-supervised models are capable of ASR over many languages, but they are frame-asynchronous and not phonemic, hindering feature extraction for speech evaluation. This paper proposes to overcome incompatibilities for feature extraction with weakly-supervised models, easing expansion of speech evaluation to low-resource languages. Phoneme posteriors are computed by mapping ASR hypotheses to a phoneme confusion network. Word instead of phoneme-level speaking rate and duration are used. Phoneme and frame-level features are combined using a cross-attention architecture, obviating phoneme time alignment. This performs comparably with standard frame-synchronous features on English speechocean762 and low-resource Tamil datasets.
### Title:
          An efficient compact splitting Fourier spectral methods for computing the dynamics of rotating spin-orbit coupled spin-2 Bose-Einstein condenstates
 - **Authors:** Xin Liu, Ziqing Xie, Yongjun Yuan, Yong Zhang, Xinyi Zhao
 - **Subjects:** Subjects:
Numerical Analysis (math.NA); Quantum Gases (cond-mat.quant-gas)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper investigates the dynamics of spin-2 Bose-Einstein condensates (BECs) with rotation and spin-orbit coupling (SOC). In order to better simulate the dynamics, we present an efficient high-order compact splitting Fourier spectral method. This method splits the Hamiltonian into a linear part, which consists of the Laplace, rotation and SOC terms, and a nonlinear part that includes all the remaining terms. The wave function is well approximated by the Fourier spectral method and is numerically accessed with discrete Fast Fourier transform (FFT). For linear subproblem, the handling of rotation term and SOC term poses a major challenge. Using a function mapping based on rotation, we can integrate the linear subproblem exactly and explicitly. This mapping we propose not only helps eliminate the rotation term, but also prevents the SOC term from evolving into a time-dependent form. The nonlinear subproblem is integrated analytically in physical space. Such "compact" splitting involves only two operators and facilitates the design of high-order splitting schemes. Our method is spectrally accurate in space and high order in time. It is efficient, explicit, unconditionally stable and simple to implement. In addition, we derive some dynamical properties and carry out a systematic study, including accuracy and efficiency tests, dynamical property verification, the SOC effects and dynamics of vortex lattice.
### Title:
          Towards Controllable Low-Light Image Enhancement: A Continuous Multi-illumination Dataset and Efficient State Space Framework
 - **Authors:** Hongru Han, Tingrui Guo, Liming Zhang, Yan Su, Qiwen Xu, Zhuohua Ye
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Low-light image enhancement (LLIE) has traditionally been formulated as a deterministic mapping. However, this paradigm often struggles to account for the ill-posed nature of the task, where unknown ambient conditions and sensor parameters create a multimodal solution space. Consequently, state-of-the-art methods frequently encounter luminance discrepancies between predictions and labels, often necessitating "gt-mean" post-processing to align output luminance for evaluation. To address this fundamental limitation, we propose a transition toward Controllable Low-light Enhancement (CLE), explicitly reformulating the task as a well-posed conditional problem. To this end, we introduce CLE-RWKV, a holistic framework supported by Light100, a new benchmark featuring continuous real-world illumination transitions. To resolve the conflict between luminance control and chromatic fidelity, a noise-decoupled supervision strategy in the HVI color space is employed, effectively separating illumination modulation from texture restoration. Architecturally, to adapt efficient State Space Models (SSMs) for dense prediction, we leverage a Space-to-Depth (S2D) strategy. By folding spatial neighborhoods into channel dimensions, this design allows the model to recover local inductive biases and effectively bridge the "scanning gap" inherent in flattened visual sequences without sacrificing linear complexity. Experiments across seven benchmarks demonstrate that our approach achieves competitive performance and robust controllability, providing a real-world multi-illumination alternative that significantly reduces the reliance on gt-mean post-processing.
### Title:
          Bayesian Learning-Enhanced Navigation with Deep Smoothing for Inertial-Aided Navigation
 - **Authors:** Nadav Cohen, Itzik Klein
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate post-processing navigation is essential for applications such as survey and mapping, where the full measurement history can be exploited to refine past state estimates. Fixed-interval smoothing algorithms represent the theoretically optimal solution under Gaussian assumptions. However, loosely coupled INS/GNSS systems fundamentally inherit the systematic position bias of raw GNSS measurements, leaving a persistent accuracy gap that model-based smoothers cannot resolve. To address this limitation, we propose BLENDS, which integrates Bayesian learning with deep smoothing to enhance navigation performance. BLENDS is a a data-driven post-processing framework that augments the classical two-filter smoother with a transformer-based neural network. It learns to modify the filter covariance matrices and apply an additive correction to the smoothed error-state directly within the Bayesian framework. A novel Bayesian-consistent loss jointly supervises the smoothed mean and covariance, enforcing minimum-variance estimates while maintaining statistical consistency. BLENDS is evaluated on two real-world datasets spanning a mobile robot and a quadrotor. Across all unseen test trajectories, BLENDS achieves horizontal position improvements of up to 63% over the baseline forward EKF.
### Title:
          Accurate Surface and Reflectance Modelling from 3D Radar Data with Neural Radiance Fields
 - **Authors:** Judith Treffler, Vladimír Kubelka, Henrik Andreasson, Martin Magnusson
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust scene representation is essential for autonomous systems to safely operate in challenging low-visibility environments. Radar has a clear advantage over cameras and lidars in these conditions due to its resilience to environmental factors such as fog, smoke, or dust. However, radar data is inherently sparse and noisy, making reliable 3D surface reconstruction challenging. To address these challenges, we propose a neural implicit approach for 3D mapping from radar point clouds, which jointly models scene geometry and view-dependent radar intensities. Our method leverages a memory-efficient hybrid feature encoding to learn a continuous Signed Distance Field (SDF) for surface reconstruction, while also capturing radar-specific reflective properties. We show that our approach produces smoother, more accurate 3D surface reconstructions compared to existing lidar-based reconstruction methods applied to radar data, and can reconstruct view-dependent radar intensities. We also show that in general, as input point clouds get sparser, neural implicit representations render more faithful surfaces, compared to traditional explicit SDFs and meshing techniques.
## Keyword: localization
### Title:
          TRAJEVAL: Decomposing Code Agent Trajectories for Fine-Grained Diagnosis
 - **Authors:** Myeongsoo Kim, Dingmin Wang, Siwei Cui, Farima Farmahinifarahani, Shweta Garg, Baishakhi Ray, Terry Yue Zhuo, Rajdeep Mukherjee, Varun Kumar
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Code agents can autonomously resolve GitHub issues, yet when they fail, current evaluation provides no visibility into where or why. Metrics such as Pass@1 collapse an entire execution into a single binary outcome, making it difficult to identify where and why the agent went wrong. To address this limitation, we introduce TRAJEVAL, a diagnostic framework that decomposes agent trajectories into three interpretable stages: search (file localization), read (function comprehension), and edit (modification targeting). For each stage, we compute precision and recall by comparing against reference patches. Analyzing 16,758 trajectories across three agent architectures and seven models, we find universal inefficiencies (all agents examine approximately 22x more functions than necessary) yet distinct failure modes: GPT-5 locates relevant code but targets edits incorrectly, while Qwen-32B fails at file discovery entirely. We validate that these diagnostics are predictive, achieving model-level Pass@1 prediction within 0.87-2.1% MAE, and actionable: real-time feedback based on trajectory signals improves two state-of-the-art models by 2.2-4.6 percentage points while reducing costs by 20-31%. These results demonstrate that our framework not only provides a more fine-grained analysis of agent behavior, but also translates diagnostic signals into tangible performance gains. More broadly, TRAJEVAL transforms agent evaluation beyond outcome-based benchmarking toward mechanism-driven diagnosis of agent success and failure.
### Title:
          TIGeR: A Unified Framework for Time, Images and Geo-location Retrieval
 - **Authors:** David G. Shatwell, Sirnam Swetha, Mubarak Shah
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many real-world applications in digital forensics, urban monitoring, and environmental analysis require jointly reasoning about visual appearance, geolocation, and time. Beyond standard geo-localization and time-of-capture prediction, these applications increasingly demand more complex capabilities, such as retrieving an image captured at the same location as a query image but at a specified target time. We formalize this problem as Geo-Time Aware Image Retrieval and curate a diverse benchmark of 4.5M paired image-location-time triplets for training and 86k high-quality triplets for evaluation. We then propose TIGeR, a multi-modal-transformer-based model that maps image, geolocation, and time into a unified geo-temporal embedding space. TIGeR supports flexible input configurations (single-modality and multi-modality queries) and uses the same representation to perform (i) geo-localization, (ii) time-of-capture prediction, and (iii) geo-time-aware retrieval. By better preserving underlying location identity under large appearance changes, TIGeR enables retrieval based on where and when a scene is, rather than purely on visual similarity. Extensive experiments show that TIGeR consistently outperforms strong baselines and state-of-the-art methods by up to 16% on time-of-year, 8% time-of-day prediction, and 14% in geo-time aware retrieval recall, highlighting the benefits of unified geo-temporal modeling.
### Title:
          Generative Adversarial Perturbations with Cross-paradigm Transferability on Localized Crowd Counting
 - **Authors:** Alabi Mehzabin Anisha, Guangjing Wang, Sriram Chellappan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 State-of-the-art crowd counting and localization are primarily modeled using two paradigms: density maps and point regression. Given the field's security ramifications, there is active interest in model robustness against adversarial attacks. Recent studies have demonstrated transferability across density-map-based approaches via adversarial patches, but cross-paradigm attacks (i.e., across both density map-based models and point regression-based models) remain unexplored. We introduce a novel adversarial framework that compromises both density map and point regression architectural paradigms through a comprehensive multi-task loss optimization. For point-regression models, we employ scene-density-specific high-confidence logit suppression; for density-map approaches, we use peak-targeted density map suppression. Both are combined with model-agnostic perceptual constraints to ensure that perturbations are effective and imperceptible to the human eye. Extensive experiments demonstrate the effectiveness of our attack, achieving on average a 7X increase in Mean Absolute Error compared to clean images while maintaining competitive visual quality, and successfully transferring across seven state-of-the-art crowd models with transfer ratios ranging from 0.55 to 1.69. Our approach strikes a balance between attack effectiveness and imperceptibility compared to state-of-the-art transferable attack strategies. The source code is available at this https URL
### Title:
          OptiSAR-Net++: A Large-Scale Benchmark and Transformer-Free Framework for Cross-Domain Remote Sensing Visual Grounding
 - **Authors:** Xiaoyu Tang, Jun Dong, Jintao Cheng, Rui Fan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Remote sensing visual grounding (RSVG) aims to localize specific targets in remote sensing images using natural language expressions. However, existing methods are restricted to single-sensor domains, i.e., either optical or synthetic aperture radar (SAR), limiting their real-world applicability. In this paper, we introduce the Cross-Domain RSVG (CD-RSVG) task and construct OptSAR-RSVG, the first large-scale benchmark dataset for this setting. To tackle the challenges of cross-domain feature modeling, computational inefficiency, and fine-grained semantic discrimination, we propose OptiSAR-Net++. Our framework features a patch-level Low-Rank Adaptation Mixture of Experts (PL-MoE) for efficient cross-domain feature decoupling. To mitigate the substantial computational overhead of Transformer decoding frameworks, we adopt a CLIP-based contrastive paradigm and further incorporate dynamic adversarial negative sampling, thereby transforming generative regression into an efficient cross-modal matching process. Additionally, a text-guided dual-gate fusion module (TGDF-SSA) and a region-aware auxiliary head are introduced to enhance semantic-visual alignment and spatial modeling. Extensive experiments demonstrate that OptiSAR-Net++ achieves SOTA performance on both OptSAR-RSVG and DIOR-RSVG benchmarks, offering significant advantages in localization accuracy and efficiency. Our code and dataset will be made publicly available.
### Title:
          MobileDev-Bench: A Comprehensive Benchmark for Evaluating Language Models on Mobile Application Development
 - **Authors:** Moshood A. Fakorede, Krishna Upadhyay, A.B. Siddique, Umar Farooq
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) have shown strong performance on automated software engineering tasks, yet existing benchmarks focus primarily on general-purpose libraries or web applications, leaving mobile application development largely unexplored despite its strict platform constraints, framework-driven lifecycles, and complex platform API interactions. We introduce MobileDev-Bench, a benchmark comprising 384 real-world issue-resolution tasks collected from 18 production mobile applications spanning Android Native (Java/Kotlin), React Native (TypeScript), and Flutter (Dart). Each task pairs an authentic developer-reported issue with executable test patches, enabling fully automated validation of model-generated fixes within mobile build environments. The benchmark exhibits substantial patch complexity: fixes modify 12.5 files and 324.9 lines on average, and 35.7% of instances require coordinated changes across multiple artifact types, such as source and manifest files. Evaluation of four state-of-the-art code-capable LLMs, GPT- 5.2, Claude Sonnet 4.5, Gemini Flash 2.5, and Qwen3-Coder, yields low end-to-end resolution rates of 3.39%-5.21%, revealing significant performance gaps compared to prior benchmarks. Further analysis reveals systematic failure modes, with fault localization across multi-file and multi-artifact changes emerging as the primary bottleneck.
### Title:
          Information-Theoretic Limits of Node Localization under Hybrid Graph Positional Encodings
 - **Authors:** Zimo Yan, Zheng Xie, Chang Liu, Yiqin Lv, Runfan Duan
 - **Subjects:** Subjects:
Information Theory (cs.IT); Symbolic Computation (cs.SC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Positional encoding has become a standard component in graph learning, especially for graph Transformers and other models that must distinguish structurally similar nodes, yet its fundamental identifiability remains poorly understood. In this work, we study node localization under a hybrid positional encoding that combines anchor-distance profiles with quantized low-frequency spectral features. We cast localization as an observation-map problem whose difficulty is controlled by the number of distinct codes induced by the encoding and establish an information-theoretic converse identifying an impossibility regime jointly governed by the anchor number, spectral dimension, and quantization level. Experiments further support this picture: on random $3$-regular graphs, the empirical crossover is well organized by the predicted scaling, while on two real-world DDI graphs identifiability is strongly graph-dependent, with DrugBank remaining highly redundant under the tested encodings and the Decagon-derived graph becoming nearly injective under sufficiently rich spectral information. Overall, these results suggest that positional encoding should be understood not merely as a heuristic architectural component, but as a graph-dependent structural resolution mechanism.
### Title:
          Pixelis: Reasoning in Pixels, from Seeing to Acting
 - **Authors:** Yunpeng Zhou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Most vision-language systems are static observers: they describe pixels, do not act, and cannot safely improve under shift. This passivity limits generalizable, physically grounded visual intelligence. Learning through action, not static description, is essential beyond curated data. We present Pixelis, a pixel-space agent that operates directly on images and videos via a compact set of executable operations (zoom/crop, segment, track, OCR, temporal localization) and learns from its consequences. Pixelis trains in three phases: (1) Supervised Fine-Tuning learns a pixel-tool grammar from Chain-of-Thought-Action traces with a masked imitation loss that upweights operation/argument tokens and auxiliary heads to stabilize pixel-grounded arguments; (2) Curiosity-Coherence Reward Fine-Tuning optimizes a dual-drive objective marrying prediction-error curiosity with adjacent-step coherence and a mild efficiency prior under a KL anchor, yielding short, valid, structured toolchains; (3) Pixel Test-Time RL performs label-free adaptation by retrieving neighbors, voting over complete trajectories rather than answers, and updating toward short, high-fidelity exemplars while constraining drift with a KL-to-EMA safety control. Across six public image and video benchmarks, Pixelis yields consistent improvements: the average relative gain is +4.08% over the same 8B baseline (peaking at +6.03% on VSI-Bench), computed as (ours-baseline)/baseline, while producing shorter, auditable toolchains and maintaining in-corridor KL during test-time learning. Acting within pixels, rather than abstract tokens, grounds multimodal perception in the physical world, linking visual reasoning with actionable outcomes, and enables embodied adaptation without external feedback.
### Title:
          A Semantically Disentangled Unified Model for Multi-category 3D Anomaly Detection
 - **Authors:** SuYeon Kim, Wongyu Lee, MyeongAh Cho
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D anomaly detection targets the detection and localization of defects in 3D point clouds trained solely on normal data. While a unified model improves scalability by learning across multiple categories, it often suffers from Inter-Category Entanglement (ICE)-where latent features from different categories overlap, causing the model to adopt incorrect semantic priors during reconstruction and ultimately yielding unreliable anomaly scores. To address this issue, we propose the Semantically Disentangled Unified Model for 3D Anomaly Detection, which reconstructs features conditioned on disentangled semantic representations. Our framework consists of three key components: (i) Coarse-to-Fine Global Tokenization for forming instance-level semantic identity, (ii) Category-Conditioned Contrastive Learning for disentangling category semantics, and (iii) a Geometry-Guided Decoder for semantically consistent reconstruction. Extensive experiments on Real3D-AD and Anomaly-ShapeNet demonstrate that our method achieves state-of-the-art for both unified and category-specific models, improving object-level AUROC by 2.8% and 9.1%, respectively, while enhancing the reliability of unified 3D anomaly detection.
### Title:
          Towards Foundation Models for 3D Scene Understanding: Instance-Aware Self-Supervised Learning for Point Clouds
 - **Authors:** Bin Yang, Mohamed Abdelsamad, Miao Zhang, Alexandru Paul Condurache
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in self-supervised learning (SSL) for point clouds have substantially improved 3D scene understanding without human annotations. Existing approaches emphasize semantic awareness by enforcing feature consistency across augmented views or by masked scene modeling. However, the resulting representations transfer poorly to instance localization, and often require full finetuning for strong performance. Instance awareness is a fundamental component of 3D perception, thus bridging this gap is crucial for progressing toward true 3D foundation models that support all downstream tasks on 3D data. In this work, we introduce PointINS, an instance-oriented self-supervised framework that enriches point cloud representations through geometry-aware learning. PointINS employs an orthogonal offset branch to jointly learn high-level semantic understanding and geometric reasoning, yielding instance awareness. We identify two consistent properties essential for robust instance localization and formulate them as complementary regularization strategies, Offset Distribution Regularization (ODR), which aligns predicted offsets with empirically observed geometric priors, and Spatial Clustering Regularization (SCR), which enforces local coherence by regularizing offsets with pseudo-instance masks. Through extensive experiments across five datasets, PointINS achieves on average +3.5% mAP improvement for indoor instance segmentation and +4.1% PQ gain for outdoor panoptic segmentation, paving the way for scalable 3D foundation models.
### Title:
          Variance Based Transmitter Localization in Vessel-Like Molecular Communication Channels
 - **Authors:** Dağhan Erdönmez, H. Birkan Yilmaz
 - **Subjects:** Subjects:
Information Theory (cs.IT); Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transmitter localization in vessel-like molecular communication channels is a fundamental problem with potential applications in healthcare. Existing analytical solutions either assume knowledge of emission time or require multiple closely spaced receivers, which limits their applicability in realistic scenarios. In this letter, we propose a simple closed-form approximation that exploits the temporal variance of the received molecular signal to estimate the distance between the transmitter and the receiver without emission time information. The method is derived from a Gaussian approximation of the received signal near its peak and gives an explicit variance-distance relation. Simulation results in physically relevant capillary vessel scale show that the proposed method achieves distance prediction with error on the order of 1%.
### Title:
          Hyperspectral Trajectory Image for Multi-Month Trajectory Anomaly Detection
 - **Authors:** Md Awsafur Rahman, Chandrakanth Gudavalli, Hardik Prajapati, B. S. Manjunath
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Trajectory anomaly detection underpins applications from fraud detection to urban mobility analysis. Dense GPS methods preserve fine-grained evidence such as abnormal speeds and short-duration events, but their quadratic cost makes multi-month analysis intractable; consequently, no existing approach detects anomalies over multi-month dense GPS trajectories. The field instead relies on scalable sparse stay-point methods that discard this evidence, forcing separate architectures for each regime and preventing knowledge transfer. We argue this bottleneck is unnecessary: human trajectories, dense or sparse, share a natural two-dimensional cyclic structure along within-day and across-day axes. We therefore propose TITAnD (Trajectory Image Transformer for Anomaly Detection), which reformulates trajectory anomaly detection as a vision problem by representing trajectories as a Hyperspectral Trajectory Image (HTI): a day x time-of-day grid whose channels encode spatial, semantic, temporal, and kinematic information from either modality, unifying both under a single representation. Under this formulation, agent-level detection reduces to image classification and temporal localization to semantic segmentation. To model this representation, we introduce the Cyclic Factorized Transformer (CFT), which factorizes attention along the two temporal axes, encoding the cyclic inductive bias of human routines, while reducing attention cost by orders of magnitude and enabling dense multi-month anomaly detection for the first time. Empirically, TITAnD achieves the best AUC-PR across sparse and dense benchmarks, surpassing vision models like UNet while being 11-75x faster than the Transformer with comparable memory, demonstrating that vision reformulation and structure-aware modeling are jointly essential. Code will be made public soon.
### Title:
          FSGNet: A Frequency-Aware and Semantic Guidance Network for Infrared Small Target Detection
 - **Authors:** Yingmei Zhang, Wangtao Bao, Yong Yang, Weiguo Wan, Qin Xiao, Xueting Zou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Infrared small target detection (IRSTD) aims to identify and distinguish small targets from complex backgrounds. Leveraging the powerful multi-scale feature fusion capability of the U-Net architecture, IRSTD has achieved significant progress. However, U-Net suffers from semantic degradation when transferring high-level features from deep to shallow layers, limiting the precise localization of small targets. To address this issue, this paper proposes FSGNet, a lightweight and effective detection framework incorporating frequency-aware and semantic guidance mechanisms. Specifically, a multi-directional interactive attention module is proposed throughout the encoder to capture fine-grained and directional features, enhancing the network's sensitivity to small, low-contrast targets. To suppress background interference propagated through skip connections, a multi-scale frequency-aware module leverages Fast Fourier transform to filter out target-similar clutter while preserving salient target structures. At the deepest layer, a global pooling module captures high-level semantic information, which is subsequently upsampled and propagated to each decoder stage through the global semantic guidance flows, ensuring semantic consistency and precise localization across scales. Extensive experiments on four public IRSTD datasets demonstrate that FSGNet achieves superior detection performance and maintains high efficiency, highlighting its practical applicability and robustness. The codes will be released on this https URL.
### Title:
          Beyond Content Safety: Real-Time Monitoring for Reasoning Vulnerabilities in Large Language Models
 - **Authors:** Xunguang Wang, Yuguang Zhou, Qingyue Wang, Zongjie Li, Ruixuan Huang, Zhenlan Ji, Pingchuan Ma, Shuai Wang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) increasingly rely on explicit chain-of-thought (CoT) reasoning to solve complex tasks, yet the safety of the reasoning process itself remains largely unaddressed. Existing work on LLM safety focuses on content safety--detecting harmful, biased, or factually incorrect outputs -- and treats the reasoning chain as an opaque intermediate artifact. We identify reasoning safety as an orthogonal and equally critical security dimension: the requirement that a model's reasoning trajectory be logically consistent, computationally efficient, and resistant to adversarial manipulation. We make three contributions. First, we formally define reasoning safety and introduce a nine-category taxonomy of unsafe reasoning behaviors, covering input parsing errors, reasoning execution errors, and process management errors. Second, we conduct a large-scale prevalence study annotating 4111 reasoning chains from both natural reasoning benchmarks and four adversarial attack methods (reasoning hijacking and denial-of-service), confirming that all nine error types occur in practice and that each attack induces a mechanistically interpretable signature. Third, we propose a Reasoning Safety Monitor: an external LLM-based component that runs in parallel with the target model, inspects each reasoning step in real time via a taxonomy-embedded prompt, and dispatches an interrupt signal upon detecting unsafe behavior. Evaluation on a 450-chain static benchmark shows that our monitor achieves up to 84.88\% step-level localization accuracy and 85.37\% error-type classification accuracy, outperforming hallucination detectors and process reward model baselines by substantial margins. These results demonstrate that reasoning-level monitoring is both necessary and practically achievable, and establish reasoning safety as a foundational concern for the secure deployment of large reasoning models.
### Title:
          CLAR: CIF-Localized Alignment for Retrieval-Augmented Speech LLM-Based Contextual ASR
 - **Authors:** Shangkun Huang, Huan Shen, Wei Zou, Yunzhang Chen
 - **Subjects:** Subjects:
Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Speech LLM-based ASR often struggles with named entities and long-tail words due to strong internal language-model priors. Retrieval-augmented biasing can help, but its effectiveness depends on accurate hotword localization in full-utterance speech under weak supervision. We propose CLAR, a dual-encoder speech-text retriever that uses Continuous Integrate-and-Fire (CIF) to learn monotonic token-level alignments without timestamps. With length-aware localized matching, CLAR anchors short-entity acoustic cues and reduces representation dilution and attention drift. The retriever is trained with a multi-granularity objective combining global and local segment-level contrastive losses and a CIF quantity constraint. At inference, top-ranked hotwords are injected as contextual prompts for the Speech LLM, improving recognition without shallow fusion. Experiments show that CLAR significantly improves hotword retrieval and reduces both CER and B-WER against strong contextual ASR baselines.
### Title:
          Causal-INSIGHT: Probing Temporal Models to Extract Causal Structure
 - **Authors:** Benjamin Redden, Hui Wang, Shuyan Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding directed temporal interactions in multivariate time series is essential for interpreting complex dynamical systems and the predictive models trained on them. We present Causal-INSIGHT, a model-agnostic, post-hoc interpretation framework for extracting model-implied (predictor-dependent), directed, time-lagged influence structure from trained temporal predictors. Rather than inferring causal structure at the level of the data-generating process, Causal-INSIGHT analyzes how a fixed, pre-trained predictor responds to systematic, intervention-inspired input clamping applied at inference time. From these responses, we construct directed temporal influence signals that reflect the dependencies the predictor relies on for prediction, and introduce Qbic, a sparsity-aware graph selection criterion that balances predictive fidelity and structural complexity without requiring ground-truth graph labels. Experiments across synthetic, simulated, and realistic benchmarks show that Causal-INSIGHT generalizes across diverse backbone architectures, maintains competitive structural accuracy, and yields significant improvements in temporal delay localization when applied to existing predictors.
### Title:
          Missing-Aware Multimodal Fusion for Unified Microservice Incident Management
 - **Authors:** Wenzhuo Qian, Hailiang Zhao, Ziqi Wang, Zhipeng Gao, Jiayi Chen, Zhiwei Ling, Shuiguang Deng
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated incident management is critical for microservice reliability. While recent unified frameworks leverage multimodal data for joint optimization, they unrealistically assume perfect data completeness. In practice, network fluctuations and agent failures frequently cause missing modalities. Existing approaches relying on static placeholders introduce imputation noise that masks anomalies and degrades performance. To address this, we propose ARMOR, a robust self-supervised framework designed for missing modality scenarios. ARMOR features: (i) a modality-specific asymmetric encoder that isolates distribution disparities among metrics, logs, and traces; and (ii) a missing-aware gated fusion mechanism utilizing learnable placeholders and dynamic bias compensation to prevent cross-modal interference from incomplete inputs. By employing self-supervised auto-regression with mask-guided reconstruction, ARMOR jointly optimizes anomaly detection (AD), failure triage (FT), and root cause localization (RCL). AD and RCL require no fault labels, while FT relies solely on failure-type annotations for the downstream classifier. Extensive experiments demonstrate that ARMOR achieves state-of-the-art performance under complete data conditions and maintains robust diagnostic accuracy even with severe modality loss.
### Title:
          Towards Comprehensive Real-Time Scene Understanding in Ophthalmic Surgery through Multimodal Image Fusion
 - **Authors:** Nikolo Rohrmoser, Ghazal Ghazaei, Michael Sommersperger, Nassir Navab
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Purpose: The integration of multimodal imaging into operating rooms paves the way for comprehensive surgical scene understanding. In ophthalmic surgery, by now, two complementary imaging modalities are available: operating microscope (OPMI) imaging and real-time intraoperative optical coherence tomography (iOCT). This first work toward temporal OPMI and iOCT feature fusion demonstrates the potential of multimodal image processing for multi-head prediction through the example of precise instrument tracking in vitreoretinal surgery. Methods: We propose a multimodal, temporal, real-time capable network architecture to perform joint instrument detection, keypoint localization, and tool-tissue distance estimation. Our network design integrates a cross-attention fusion module to merge OPMI and iOCT image features, which are efficiently extracted via a YoloNAS and a CNN encoder, respectively. Furthermore, a region-based recurrent module leverages temporal coherence. Results: Our experiments demonstrate reliable instrument localization and keypoint detection (95.79% mAP50) and show that the incorporation of iOCT significantly improves tool-tissue distance estimation, while achieving real-time processing rates of 22.5 ms per frame. Especially for close distances to the retina (below 1 mm), the distance estimation accuracy improved from 284 $\mu m$ (OPMI only) to 33 $\mu m$ (multimodal). Conclusion: Feature fusion of multimodal imaging can enhance multi-task prediction accuracy compared to single-modality processing and real-time processing performance can be achieved through tailored network design. While our results demonstrate the potential of multi-modal processing for image-guided vitreoretinal surgery, they also underline key challenges that motivate future research toward more reliable, consistent, and comprehensive surgical scene understanding.
### Title:
          Is Mathematical Problem-Solving Expertise in Large Language Models Associated with Assessment Performance?
 - **Authors:** Liang Zhang, Yu Fu, Xinyi Jin
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) are increasingly used in math education not only as problem solvers but also as assessors of learners' reasoning. However, it remains unclear whether stronger math problem-solving ability is associated with stronger step-level assessment performance. This study examines that relationship using the GSM8K and MATH subsets of PROCESSBENCH, a human-annotated benchmark for identifying the earliest erroneous step in mathematical reasoning. We evaluate two LLM-based math tutor agent settings, instantiated with GPT-4 and GPT-5, in two independent tasks on the same math problems: solving the original problem and assessing a benchmark-provided solution by predicting the earliest erroneous step. Results show a consistent within-model pattern: assessment accuracy is substantially higher on math problem items the same model solved correctly than on items it solved incorrectly, with statistically significant associations across both models and datasets. At the same time, assessment remains more difficult than direct problem solving, especially on error-present solutions. These findings suggest that math problem-solving expertise supports stronger assessment performance, but reliable step-level diagnosis also requires additional capabilities such as step tracking, monitoring, and precise error localization. The results have implications for the design and evaluation of AI-supported Adaptive Instructional Systems (AISs) for formative assessment in math education.
### Title:
          Just Zoom In: Cross-View Geo-Localization via Autoregressive Zooming
 - **Authors:** Yunus Talha Erzurumlu, Jiyong Kwag, Alper Yilmaz
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-view geo-localization (CVGL) estimates a camera's location by matching a street-view image to geo-referenced overhead imagery, enabling GPS-denied localization and navigation. Existing methods almost universally formulate CVGL as an image-retrieval problem in a contrastively trained embedding space. This ties performance to large batches and hard negative mining, and it ignores both the geometric structure of maps and the coverage mismatch between street-view and overhead imagery. In particular, salient landmarks visible from the street view can fall outside a fixed satellite crop, making retrieval targets ambiguous and limiting explicit spatial inference over the map. We propose Just Zoom In, an alternative formulation that performs CVGL via autoregressive zooming over a city-scale overhead map. Starting from a coarse satellite view, the model takes a short sequence of zoom-in decisions to select a terminal satellite cell at a target resolution, without contrastive losses or hard negative mining. We further introduce a realistic benchmark with crowd-sourced street views and high-resolution satellite imagery that reflects real capture conditions. On this benchmark, Just Zoom In achieves state-of-the-art performance, improving Recall@1 within 50 m by 5.5% and Recall@1 within 100 m by 9.6% over the strongest contrastive-retrieval baseline. These results demonstrate the effectiveness of sequential coarse-to-fine spatial reasoning for cross-view geo-localization.
### Title:
          Seeing to Ground: Visual Attention for Hallucination-Resilient MDLLMs
 - **Authors:** Vishal Narnaware, Animesh Gupta, Kevin Zhai, Zhenyi Wang, Mubarak Shah
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal Diffusion Large Language Models (MDLLMs) achieve high-concurrency generation through parallel masked decoding, yet the architectures remain prone to multimodal hallucinations. This structural vulnerability stems from an algorithmic flaw: the decoder ranks candidate tokens based on textual likelihood without verifying localized visual support. We establish that this language-only ranking induces an objective mismatch, where language probability mass acts as a misspecified proxy for the intended multimodal task. Consequently, we reinterpret hallucination as a localized optimization error, a phenomenon where the decoder exploits language shortcuts to maximize a proxy score at the expense of visual grounding. To address this objective mismatch, we introduce VISAGE, a training-free decoding framework that calibrates the objective at inference time. VISAGE estimates the proxy discrepancy by quantifying the spatial entropy of cross-attention distributions. By enforcing a localization consensus across attention heads, the method penalizes spatially uniform distributions and re-ranks token commitments to favor visually grounded outcomes. We provide an analytical stability guarantee establishing that VISAGE maintains a bounded objective loss under estimation error. Evaluations across hallucination-sensitive and general-purpose benchmarks demonstrate the robustness of the framework, yielding relative gains of 8.59% on MMMU-val and 7.75% on HallusionBench.
## Keyword: transformer
### Title:
          Model2Kernel: Model-Aware Symbolic Execution For Safe CUDA Kernels
 - **Authors:** Mengting He, Shihao Xia, Haomin Jia, Wenfei Wu, Linhai Song
 - **Subjects:** Subjects:
Programming Languages (cs.PL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The widespread adoption of large language models (LLMs) has made GPU-accelerated inference a critical part of modern computing infrastructure. Production inference systems rely on CUDA kernels to implement core transformer operations, yet these kernels are highly susceptible to memory-safety bugs due to model-dependent tensor layouts, intricate memory indexing, and massive thread-level parallelism. Such bugs can corrupt model weights, crash inference services, or even enable adversarial attacks. Existing techniques either depend on unavailable hardware, incur high overhead, or fail to handle kernel inputs with variable lengths, and none can effectively detect CUDA memory bugs in LLM inference systems. This paper presents Model2Kernel, the first practical system for automatically verifying the memory safety of CUDA kernels used in LLM inference. Model2Kernel performs model-aware dynamic analysis to determine how each model invokes kernels and to classify kernel arguments as either fixed by the model architecture or controlled by model users. Using this information, Model2Kernel then applies CUDA-specialized symbolic execution, supported by new abstractions for dynamic tensor memory and thread identifiers, to accurately pinpoint memory bugs in kernels. In the evaluation on CUDA kernels and models from vLLM, Hugging Face, and recent LLM research papers, Model2Kernel discovers 353 previously unknown bugs while producing only nine false positives, demonstrating its effectiveness.
### Title:
          How unconstrained machine-learning models learn physical symmetries
 - **Authors:** Michelangelo Domina, Joseph William Abbott, Paolo Pegolo, Filippo Bigi, Michele Ceriotti
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Materials Science (cond-mat.mtrl-sci); Chemical Physics (physics.chem-ph); Computational Physics (physics.comp-ph); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The requirement of generating predictions that exactly fulfill the fundamental symmetry of the corresponding physical quantities has profoundly shaped the development of machine-learning models for physical simulations. In many cases, models are built using constrained mathematical forms that ensure that symmetries are enforced exactly. However, unconstrained models that do not obey rotational symmetries are often found to have competitive performance, and to be able to \emph{learn} to a high level of accuracy an approximate equivariant behavior with a simple data augmentation strategy. In this paper, we introduce rigorous metrics to measure the symmetry content of the learned representations in such models, and assess the accuracy by which the outputs fulfill the equivariant condition. We apply these metrics to two unconstrained, transformer-based models operating on decorated point clouds (a graph neural network for atomistic simulations and a PointNet-style architecture for particle physics) to investigate how symmetry information is processed across architectural layers and is learned during training. Based on these insights, we establish a rigorous framework for diagnosing spectral failure modes in ML models. Enabled by this analysis, we demonstrate that one can achieve superior stability and accuracy by strategically injecting the minimum required inductive biases, preserving the high expressivity and scalability of unconstrained architectures while guaranteeing physical fidelity.
### Title:
          Physics-Informed Neural Network Digital Twin for Dynamic Tray-Wise Modeling of Distillation Columns under Transient Operating Conditions
 - **Authors:** Debadutta Patra, Ayush Bardhan Tripathy, Soumya Ranjan Sahu, Sucheta Panda
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Digital twin technology, when combined with physics-informed machine learning with simulation results of Aspen, offers transformative capabilities for industrial process monitoring, control, and optimization. In this work, the proposed model presents a Physics-Informed Neural Network (PINN) digital twin framework for the dynamic, tray-wise modeling of binary distillation columns operating under transient conditions. The architecture of the proposed model embeds fundamental thermodynamic constraints, including vapor-liquid equilibrium (VLE) described by modified Raoult's law, tray-level mass and energy balances, and the McCabe-Thiele graphical methodology directly into the neural network loss function via physics residual terms. The model is trained and evaluated on a high-fidelity synthetic dataset of 961 timestamped measurements spanning 8 hours of transient operation, generated in Aspen HYSYS for a binary HX/TX distillation system comprising 16 sensor streams. An adaptive loss-weighting scheme balances the data fidelity and physics consistency objectives during training. Compared to five data-driven baselines (LSTM, vanilla MLP, GRU, Transformer, DeepONet), the proposed PINN achieves an RMSE of 0.00143 for HX mole fraction prediction (R^2 = 0.9887), representing a 44.6% reduction over the best data-only baseline, while strictly satisfying thermodynamic constraints. Tray-wise temperature and composition profiles predicted under transient perturbations demonstrate that the digital twin accurately captures column dynamics including feed tray responses, reflux ratio variations, and pressure transients. These results establish the proposed PINN digital twin as a robust foundation for real-time soft sensing, model-predictive control, and anomaly detection in industrial distillation processes.
### Title:
          From Weights to Concepts: Data-Free Interpretability of CLIP via Singular Vector Decomposition
 - **Authors:** Francesco Gentile, Nicola Dall'Asen, Francesco Tonini, Massimiliano Mancini, Lorenzo Vaquero, Elisa Ricci
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As vision-language models are deployed at scale, understanding their internal mechanisms becomes increasingly critical. Existing interpretability methods predominantly rely on activations, making them dataset-dependent, vulnerable to data bias, and often restricted to coarse head-level explanations. We introduce SITH (Semantic Inspection of Transformer Heads), a fully data-free, training-free framework that directly analyzes CLIP's vision transformer in weight space. For each attention head, we decompose its value-output matrix into singular vectors and interpret each one via COMP (Coherent Orthogonal Matching Pursuit), a new algorithm that explains them as sparse, semantically coherent combinations of human-interpretable concepts. We show that SITH yields coherent, faithful intra-head explanations, validated through reconstruction fidelity and interpretability experiments. This allows us to use SITH for precise, interpretable weight-space model edits that amplify or suppress specific concepts, improving downstream performance without retraining. Furthermore, we use SITH to study model adaptation, showing how fine-tuning primarily reweights a stable semantic basis rather than learning entirely new features.
### Title:
          ReDiPrune: Relevance-Diversity Pre-Projection Token Pruning for Efficient Multimodal LLMs
 - **Authors:** An Yu, Ting Yu Tsai, Zhenfei Zhang, Weiheng Lu, Felix X.-F. Ye, Ming-Ching Chang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent multimodal large language models are computationally expensive because Transformers must process a large number of visual tokens. We present \textbf{ReDiPrune}, a training-free token pruning method applied before the vision-language projector, where visual features remain rich and discriminative. Unlike post-projection pruning methods that operate on compressed representations, ReDiPrune selects informative tokens directly from vision encoder outputs, preserving fine-grained spatial and semantic cues. Each token is scored by a lightweight rule that jointly consider text-conditioned relevance and max-min diversity, ensuring the selected tokens are both query-relevant and non-redundant. ReDiPrune is fully plug-and-play, requiring no retraining or architectural modifications, and can be seamlessly inserted between the encoder and projector. Across four video and five image benchmarks, it consistently improves the accuracy-efficiency trade-off. For example, on EgoSchema with LLaVA-NeXT-Video-7B, retaining only 15\% of visual tokens yields a +2.0\% absolute accuracy gain while reducing computation by more than $6\times$ in TFLOPs. Code is available at this https URL.
### Title:
          KitchenTwin: Semantically and Geometrically Grounded 3D Kitchen Digital Twins
 - **Authors:** Quanyun Wu, Kyle Gao, Daniel Long, David A. Clausi, Jonathan Li, Yuhao Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Embodied AI training and evaluation require object-centric digital twin environments with accurate metric geometry and semantic grounding. Recent transformer-based feedforward reconstruction methods can efficiently predict global point clouds from sparse monocular videos, yet these geometries suffer from inherent scale ambiguity and inconsistent coordinate conventions. This mismatch prevents the reliable fusion of these dimensionless point cloud predictions with locally reconstructed object meshes. We propose a novel scale-aware 3D fusion framework that registers visually grounded object meshes with transformer-predicted global point clouds to construct metrically consistent digital twins. Our method introduces a Vision-Language Model (VLM)-guided geometric anchor mechanism that resolves this fundamental coordinate mismatch by recovering an accurate real-world metric scale. To fuse these networks, we propose a geometry-aware registration pipeline that explicitly enforces physical plausibility through gravity-aligned vertical estimation, Manhattan-world structural constraints, and collision-free local refinement. Experiments on real indoor kitchen environments demonstrate improved cross-network object alignment and geometric consistency for downstream tasks, including multi-primitive fitting and metric measurement. We additionally introduce an open-source indoor digital twin dataset with metrically scaled scenes and semantically grounded and registered object-centric mesh annotations.
### Title:
          Lookalike3D: Seeing Double in 3D
 - **Authors:** Chandan Yeshwanth, Angela Dai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D object understanding and generation methods produce impressive results, yet they often overlook a pervasive source of information in real-world scenes: repeated objects. We introduce the task of lookalike object detection in indoor scenes, which leverages repeated and complementary cues from identical and near-identical object pairs. Given an input scene, the task is to classify pairs of objects as identical, similar or different using multiview images as input. To address this, we present Lookalike3D, a multiview image transformer that effectively distinguishes such object pairs by harnessing strong semantic priors from large image foundation models. To support this task, we collected the 3DTwins dataset, containing 76k manually annotated identical, similar and different pairs of objects based on ScanNet++, and show an improvement of 104% IoU over baselines. We demonstrate how our method improves downstream tasks such as enabling joint 3D object reconstruction and part co-segmentation, turning repeated and lookalike objects into a powerful cue for consistent, high-quality 3D perception. Our code, dataset and models will be made publicly available.
### Title:
          TIGeR: A Unified Framework for Time, Images and Geo-location Retrieval
 - **Authors:** David G. Shatwell, Sirnam Swetha, Mubarak Shah
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many real-world applications in digital forensics, urban monitoring, and environmental analysis require jointly reasoning about visual appearance, geolocation, and time. Beyond standard geo-localization and time-of-capture prediction, these applications increasingly demand more complex capabilities, such as retrieving an image captured at the same location as a query image but at a specified target time. We formalize this problem as Geo-Time Aware Image Retrieval and curate a diverse benchmark of 4.5M paired image-location-time triplets for training and 86k high-quality triplets for evaluation. We then propose TIGeR, a multi-modal-transformer-based model that maps image, geolocation, and time into a unified geo-temporal embedding space. TIGeR supports flexible input configurations (single-modality and multi-modality queries) and uses the same representation to perform (i) geo-localization, (ii) time-of-capture prediction, and (iii) geo-time-aware retrieval. By better preserving underlying location identity under large appearance changes, TIGeR enables retrieval based on where and when a scene is, rather than purely on visual similarity. Extensive experiments show that TIGeR consistently outperforms strong baselines and state-of-the-art methods by up to 16% on time-of-year, 8% time-of-day prediction, and 14% in geo-time aware retrieval recall, highlighting the benefits of unified geo-temporal modeling.
### Title:
          Transformers in the Dark: Navigating Unknown Search Spaces via Bandit Feedback
 - **Authors:** Jungtaek Kim, Thomas Zeng, Ziqian Lin, Minjae Lee, Chungpa Lee, Jy-yong Sohn, Hyung Il Koo, Kangwook Lee
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Effective problem solving with Large Language Models (LLMs) can be enhanced when they are paired with external search algorithms. By viewing the space of diverse ideas and their follow-up possibilities as a tree structure, the search algorithm can navigate such a search space and guide the LLM toward better solutions more efficiently. While the search algorithm enables an effective balance between exploitation and exploration of a tree-structured space, the need for an external component can complicate the overall problem-solving process. We therefore pose the following question: Can LLMs or their underlying Transformer architectures approximate a search algorithm? To answer this question, we first introduce a simplified framework in which tree extensions and feedback signals are externally specified, allowing for controlled evaluation of search capabilities. We call this setting unknown tree search with bandit feedback. Within this setting, we show that Transformers are theoretically expressive enough to implement distinct search strategies and can be trained from scratch to approximate those strategies. Our Transformer models exhibit the possibility of generalizing to unseen conditions such as longer horizons or deeper trees. Furthermore, we demonstrate that continued task-focused training unlocks the complete capabilities of a pretrained LLM, by fine-tuning the LLM on search trajectories.
### Title:
          Calibri: Enhancing Diffusion Transformers via Parameter-Efficient Calibration
 - **Authors:** Danil Tokhchukov, Aysel Mirzoeva, Andrey Kuznetsov, Konstantin Sobolev
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we uncover the hidden potential of Diffusion Transformers (DiTs) to significantly enhance generative tasks. Through an in-depth analysis of the denoising process, we demonstrate that introducing a single learned scaling parameter can significantly improve the performance of DiT blocks. Building on this insight, we propose Calibri, a parameter-efficient approach that optimally calibrates DiT components to elevate generative quality. Calibri frames DiT calibration as a black-box reward optimization problem, which is efficiently solved using an evolutionary algorithm and modifies just ~100 parameters. Experimental results reveal that despite its lightweight design, Calibri consistently improves performance across various text-to-image models. Notably, Calibri also reduces the inference steps required for image generation, all while maintaining high-quality outputs.
### Title:
          Towards automatic smoke detector inspection: Recognition of the smoke detectors in industrial facilities and preparation for future drone integration
 - **Authors:** Lukas Kratochvila, Jakub Stefansky, Simon Bilik, Robert Rous, Tomas Zemcik, Michal Wolny, Frantisek Rusnak, Ondrej Cech, Karel Horak
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fire safety consists of a complex pipeline, and it is a very important topic of concern. One of its frontal parts are the smoke detectors, which are supposed to provide an alarm prior to a massive fire appears. As they are often difficult to reach due to high ceilings or problematic locations, an automatic inspection system would be very beneficial as it could allow faster revisions, prevent workers from dangerous work in heights, and make the whole process cheaper. In this study, we present the smoke detector recognition part of the automatic inspection system, which could easily be integrated to the drone system. As part of our research, we compare two popular convolutional-based object detectors YOLOv11 and SSD widely used on embedded devices together with the state-of-the-art transformer-based RT-DETRv2 with the backbones of different sizes. Due to a complicated way of collecting a sufficient amount of data for training in the real-world environment, we also compare several training strategies using the real and semi-synthetic data together with various augmentation methods. To achieve a robust testing, all models were evaluated on two test datasets with an expected and difficult appearance of the smoke detectors including motion blur, small resolution, or not complete objects. The best performing detector is the YOLOv11n, which reaches the average mAP@0.5 score of 0.884. Our code, pretrained models and dataset are publicly available.
### Title:
          OptiSAR-Net++: A Large-Scale Benchmark and Transformer-Free Framework for Cross-Domain Remote Sensing Visual Grounding
 - **Authors:** Xiaoyu Tang, Jun Dong, Jintao Cheng, Rui Fan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Remote sensing visual grounding (RSVG) aims to localize specific targets in remote sensing images using natural language expressions. However, existing methods are restricted to single-sensor domains, i.e., either optical or synthetic aperture radar (SAR), limiting their real-world applicability. In this paper, we introduce the Cross-Domain RSVG (CD-RSVG) task and construct OptSAR-RSVG, the first large-scale benchmark dataset for this setting. To tackle the challenges of cross-domain feature modeling, computational inefficiency, and fine-grained semantic discrimination, we propose OptiSAR-Net++. Our framework features a patch-level Low-Rank Adaptation Mixture of Experts (PL-MoE) for efficient cross-domain feature decoupling. To mitigate the substantial computational overhead of Transformer decoding frameworks, we adopt a CLIP-based contrastive paradigm and further incorporate dynamic adversarial negative sampling, thereby transforming generative regression into an efficient cross-modal matching process. Additionally, a text-guided dual-gate fusion module (TGDF-SSA) and a region-aware auxiliary head are introduced to enhance semantic-visual alignment and spatial modeling. Extensive experiments demonstrate that OptiSAR-Net++ achieves SOTA performance on both OptSAR-RSVG and DIOR-RSVG benchmarks, offering significant advantages in localization accuracy and efficiency. Our code and dataset will be made publicly available.
### Title:
          Learning to Staff: Offline Reinforcement Learning and Fine-Tuned LLMs for Warehouse Staffing Optimization
 - **Authors:** Kalle Kujanpää, Yuying Zhu, Kristina Klinkner, Shervin Malmasi
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We investigate machine learning approaches for optimizing real-time staffing decisions in semi-automated warehouse sortation systems. Operational decision-making can be supported at different levels of abstraction, with different trade-offs. We evaluate two approaches, each in a matching simulation environment. First, we train custom Transformer-based policies using offline reinforcement learning on detailed historical state representations, achieving a 2.4% throughput improvement over historical baselines in learned simulators. In high-volume warehouse operations, improvements of this size translate to significant savings. Second, we explore LLMs operating on abstracted, human-readable state descriptions. These are a natural fit for decisions that warehouse managers make using high-level operational summaries. We systematically compare prompting techniques, automatic prompt optimization, and fine-tuning strategies. While prompting alone proves insufficient, supervised fine-tuning combined with Direct Preference Optimization on simulator-generated preferences achieves performance that matches or slightly exceeds historical baselines in a hand-crafted simulator. Our findings demonstrate that both approaches offer viable paths toward AI-assisted operational decision-making. Offline RL excels with task-specific architectures. LLMs support human-readable inputs and can be combined with an iterative feedback loop that can incorporate manager preferences.
### Title:
          Decoding Market Emotions in Cryptocurrency Tweets via Predictive Statement Classification with Machine Learning and Transformers
 - **Authors:** Moein Shahiki Tash, Zahra Ahani, Mohim Tash, Mostafa Keikhay Farzaneh, Ari Y. Barrera-Animas, Olga Kolesnikova
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The growing prominence of cryptocurrencies has triggered widespread public engagement and increased speculative activity, particularly on social media platforms. This study introduces a novel classification framework for identifying predictive statements in cryptocurrency-related tweets, focusing on five popular cryptocurrencies: Cardano, Matic, Binance, Ripple, and Fantom. The classification process is divided into two stages: Task 1 involves binary classification to distinguish between Predictive and Non-Predictive statements. Tweets identified as Predictive proceed to Task 2, where they are further categorized as Incremental, Decremental, or Neutral. To build a robust dataset, we combined manual and GPT-based annotation methods and utilized SenticNet to extract emotion features corresponding to each prediction category. To address class imbalance, GPT-generated paraphrasing was employed for data augmentation. We evaluated a wide range of machine learning, deep learning, and transformer-based models across both tasks. The results show that GPT-based balancing significantly enhanced model performance, with transformer models achieving the highest F1-score in Task 1, while traditional machine learning models performed best in Task 2. Furthermore, our emotion analysis revealed distinct emotional patterns associated with each prediction category across the different cryptocurrencies.
### Title:
          CVA: Context-aware Video-text Alignment for Video Temporal Grounding
 - **Authors:** Sungho Moon, Seunghun Lee, Jiwan Seo, Sunghoon Im
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose Context-aware Video-text Alignment (CVA), a novel framework to address a significant challenge in video temporal grounding: achieving temporally sensitive video-text alignment that remains robust to irrelevant background context. Our framework is built on three key components. First, we propose Query-aware Context Diversification (QCD), a new data augmentation strategy that ensures only semantically unrelated content is mixed in. It builds a video-text similarity-based pool of replacement clips to simulate diverse contexts while preventing the ``false negative" caused by query-agnostic mixing. Second, we introduce the Context-invariant Boundary Discrimination (CBD) loss, a contrastive loss that enforces semantic consistency at challenging temporal boundaries, making their representations robust to contextual shifts and hard negatives. Third, we introduce the Context-enhanced Transformer Encoder (CTE), a hierarchical architecture that combines windowed self-attention and bidirectional cross-attention with learnable queries to capture multi-scale temporal context. Through the synergy of these data-centric and architectural enhancements, CVA achieves state-of-the-art performance on major VTG benchmarks, including QVHighlights and Charades-STA. Notably, our method achieves a significant improvement of approximately 5 points in Recall@1 (R1) scores over state-of-the-art methods, highlighting its effectiveness in mitigating false negatives.
### Title:
          MoE-GRPO: Optimizing Mixture-of-Experts via Reinforcement Learning in Vision-Language Models
 - **Authors:** Dohwan Ko, Jinyoung Park, Seoung Choi, Sanghyeok Lee, Seohyun Lee, Hyunwoo J. Kim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mixture-of-Experts (MoE) has emerged as an effective approach to reduce the computational overhead of Transformer architectures by sparsely activating a subset of parameters for each token while preserving high model capacity. This paradigm has recently been extended to Vision-Language Models (VLMs), enabling scalable multi-modal understanding with reduced computational cost. However, the widely adopted deterministic top-K routing mechanism may overlook more optimal expert combinations and lead to expert overfitting. To address this limitation and improve the diversity of expert selection, we propose MoE-GRPO, a reinforcement learning (RL)-based framework for optimizing expert routing in MoE-based VLMs. Specifically, we formulate expert selection as a sequential decision-making problem and optimize it using Group Relative Policy Optimization (GRPO), allowing the model to learn adaptive expert routing policies through exploration and reward-based feedback. Furthermore, we introduce a modality-aware router guidance that enhances training stability and efficiency by discouraging the router from exploring experts that are infrequently activated for a given modality. Extensive experiments on multi-modal image and video benchmarks show that MoE-GRPO consistently outperforms standard top-K routing and its variants by promoting more diverse expert selection, thereby mitigating expert overfitting and enabling a task-level expert specialization.
### Title:
          A Systematic Empirical Study of Grokking: Depth, Architecture, Activation, and Regularization
 - **Authors:** Shalima Binta Manir, Anamika Paul Rupa
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Grokking the delayed transition from memorization to generalization in neural networks remains poorly understood, in part because prior empirical studies confound the roles of architecture, optimization, and regularization. We present a controlled study that systematically disentangles these factors on modular addition (mod 97), with matched and carefully tuned training regimes across models. Our central finding is that grokking dynamics are not primarily determined by architecture, but by interactions between optimization stability and regularization. Specifically, we show: (1) \textbf{depth has a non-monotonic effect}, with depth-4 MLPs consistently failing to grok while depth-8 residual networks recover generalization, demonstrating that depth requires architectural stabilization; (2) \textbf{the apparent gap between Transformers and MLPs largely disappears} (1.11$\times$ delay) under matched hyperparameters, indicating that previously reported differences are largely due to optimizer and regularization confounds; (3) \textbf{activation function effects are regime-dependent}, with GELU up to 4.3$\times$ faster than ReLU only when regularization permits memorization; and (4) \textbf{weight decay is the dominant control parameter}, exhibiting a narrow ``Goldilocks'' regime in which grokking occurs, while too little or too much prevents generalization. Across 3--5 seeds per configuration, these results provide a unified empirical account of grokking as an interaction-driven phenomenon. Our findings challenge architecture-centric interpretations and clarify how optimization and regularization jointly govern delayed generalization.
### Title:
          Information-Theoretic Limits of Node Localization under Hybrid Graph Positional Encodings
 - **Authors:** Zimo Yan, Zheng Xie, Chang Liu, Yiqin Lv, Runfan Duan
 - **Subjects:** Subjects:
Information Theory (cs.IT); Symbolic Computation (cs.SC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Positional encoding has become a standard component in graph learning, especially for graph Transformers and other models that must distinguish structurally similar nodes, yet its fundamental identifiability remains poorly understood. In this work, we study node localization under a hybrid positional encoding that combines anchor-distance profiles with quantized low-frequency spectral features. We cast localization as an observation-map problem whose difficulty is controlled by the number of distinct codes induced by the encoding and establish an information-theoretic converse identifying an impossibility regime jointly governed by the anchor number, spectral dimension, and quantization level. Experiments further support this picture: on random $3$-regular graphs, the empirical crossover is well organized by the predicted scaling, while on two real-world DDI graphs identifiability is strongly graph-dependent, with DrugBank remaining highly redundant under the tested encodings and the Decagon-derived graph becoming nearly injective under sufficiently rich spectral information. Overall, these results suggest that positional encoding should be understood not merely as a heuristic architectural component, but as a graph-dependent structural resolution mechanism.
### Title:
          Z-Erase: Enabling Concept Erasure in Single-Stream Diffusion Transformers
 - **Authors:** Nanxiang Jiang, Zhaoxin Fan, Baisen Wang, Daiheng Gao, Junhang Cheng, Jifeng Guo, Yalan Qin, Yeying Jin, Hongwei Zheng, Faguo Wu, Wenjun Wu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Concept erasure serves as a vital safety mechanism for removing unwanted concepts from text-to-image (T2I) models. While extensively studied in U-Net and dual-stream architectures (e.g., Flux), this task remains under-explored in the recent emerging paradigm of single-stream diffusion transformers (e.g., Z-Image). In this new paradigm, text and image tokens are processed as a single unified sequence via shared parameters. Consequently, directly applying prior erasure methods typically leads to generation collapse. To bridge this gap, we introduce Z-Erase, the first concept erasure method tailored for single-stream T2I models. To guarantee stable image generation, Z-Erase first proposes a Stream Disentangled Concept Erasure Framework that decouples updates and enables existing methods on single-stream models. Subsequently, within this framework, we introduce Lagrangian-Guided Adaptive Erasure Modulation, a constrained algorithm that further balances the sensitive erasure-preservation trade-off. Moreover, we provide a rigorous convergence analysis proving that Z-Erase can converge to a Pareto stationary point. Experiments demonstrate that Z-Erase successfully overcomes the generation collapse issue, achieving state-of-the-art performance across a wide range of tasks.
### Title:
          MoireMix: A Formula-Based Data Augmentation for Improving Image Classification Robustness
 - **Authors:** Yuto Matsuo, Yoshihiro Fukuhara, Yuki M. Asano, Rintaro Yanagi, Hirokatsu Kataoka, Akio Nakamura
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Data augmentation is a key technique for improving the robustness of image classification models. However, many recent approaches rely on diffusion-based synthesis or complex feature mixing strategies, which introduce substantial computational overhead or require external datasets. In this work, we explore a different direction: procedural augmentation based on analytic interference patterns. Unlike conventional augmentation methods that rely on stochastic noise, feature mixing, or generative models, our approach exploits Moire interference to generate structured perturbations spanning a wide range of spatial frequencies. We propose a lightweight augmentation method that procedurally generates Moire textures on-the-fly using a closed-form mathematical formulation. The patterns are synthesized directly in memory with negligible computational cost (0.0026 seconds per image), mixed with training images during training, and immediately discarded, enabling a storage-free augmentation pipeline without external data. Extensive experiments with Vision Transformers demonstrate that the proposed method consistently improves robustness across multiple benchmarks, including ImageNet-C, ImageNet-R, and adversarial benchmarks, outperforming standard augmentation baselines and existing external-data-free augmentation approaches. These results suggest that analytic interference patterns provide a practical and efficient alternative to data-driven generative augmentation methods.
### Title:
          Vision Hopfield Memory Networks
 - **Authors:** Jianfeng Wang, Amine M'Charrak, Luk Koska, Xiangtao Wang, Daniel Petriceanu, Mykyta Smyrnov, Ruizhi Wang, Michael Bumbar, Luca Pinchetti, Thomas Lukasiewicz
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent vision and multimodal foundation backbones, such as Transformer families and state-space models like Mamba, have achieved remarkable progress, enabling unified modeling across images, text, and beyond. Despite their empirical success, these architectures remain far from the computational principles of the human brain, often demanding enormous amounts of training data while offering limited interpretability. In this work, we propose the Vision Hopfield Memory Network (V-HMN), a brain-inspired foundation backbone that integrates hierarchical memory mechanisms with iterative refinement updates. Specifically, V-HMN incorporates local Hopfield modules that provide associative memory dynamics at the image patch level, global Hopfield modules that function as episodic memory for contextual modulation, and a predictive-coding-inspired refinement rule for iterative error correction. By organizing these memory-based modules hierarchically, V-HMN captures both local and global dynamics in a unified framework. Memory retrieval exposes the relationship between inputs and stored patterns, making decisions more interpretable, while the reuse of stored patterns improves data efficiency. This brain-inspired design therefore enhances interpretability and data efficiency beyond existing self-attention- or state-space-based approaches. We conducted extensive experiments on public computer vision benchmarks, and V-HMN achieved competitive results against widely adopted backbone architectures, while offering better interpretability, higher data efficiency, and stronger biological plausibility. These findings highlight the potential of V-HMN to serve as a next-generation vision foundation model, while also providing a generalizable blueprint for multimodal backbones in domains such as text and audio, thereby bridging brain-inspired computation with large-scale machine learning.
### Title:
          AG-EgoPose: Leveraging Action-Guided Motion and Kinematic Joint Encoding for Egocentric 3D Pose Estimation
 - **Authors:** Md Mushfiqur Azam, John Quarles, Kevin Desai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Egocentric 3D human pose estimation remains challenging due to severe perspective distortion, limited body visibility, and complex camera motion inherent in first-person viewpoints. Existing methods typically rely on single-frame analysis or limited temporal fusion, which fails to effectively leverage the rich motion context available in egocentric videos. We introduce AG-EgoPose, a novel dual-stream framework that integrates short- and long-range motion context with fine-grained spatial cues for robust pose estimation from fisheye camera input. Our framework features two parallel streams: A spatial stream uses a weight-sharing ResNet-18 encoder-decoder to generate 2D joint heatmaps and corresponding joint-specific spatial feature tokens. Simultaneously, a temporal stream uses a ResNet-50 backbone to extract visual features, which are then processed by an action recognition backbone to capture the motion dynamics. These complementary representations are fused and refined in a transformer decoder with learnable joint tokens, which allows for the joint-level integration of spatial and temporal evidence while maintaining anatomical constraints. Experiments on real-world datasets demonstrate that AG-EgoPose achieves state-of-the-art performance in both quantitative and qualitative metrics. Code is available at: this https URL.
### Title:
          VolDiT: Controllable Volumetric Medical Image Synthesis with Diffusion Transformers
 - **Authors:** Marvin Seyfarth, Salman Ul Hassan Dar, Yannik Frisch, Philipp Wild, Norbert Frey, Florian André, Sandy Engelhardt
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion models have become a leading approach for high-fidelity medical image synthesis. However, most existing methods for 3D medical image generation rely on convolutional U-Net backbones within latent diffusion frameworks. While effective, these architectures impose strong locality biases and limited receptive fields, which may constrain scalability, global context integration, and flexible conditioning. In this work, we introduce VolDiT, the first purely transformer-based 3D Diffusion Transformer for volumetric medical image synthesis. Our approach extends diffusion transformers to native 3D data through volumetric patch embeddings and global self-attention operating directly over 3D tokens. To enable structured control, we propose a timestep-gated control adapter that maps segmentation masks into learnable control tokens that modulate transformer layers during denoising. This token-level conditioning mechanism allows precise spatial guidance while preserving the modeling advantages of transformer architectures. We evaluate our model on high-resolution 3D medical image synthesis tasks and compare it to state-of-the-art 3D latent diffusion models based on U-Nets. Results demonstrate improved global coherence, superior generative fidelity, and enhanced controllability. Our findings suggest that fully transformerbased diffusion models provide a flexible foundation for volumetric medical image synthesis. The code and models trained on public data are available at this https URL.
### Title:
          CardioDiT: Latent Diffusion Transformers for 4D Cardiac MRI Synthesis
 - **Authors:** Marvin Seyfarth, Sarah Kaye Müller, Arman Ghanaat, Isabelle Ayx, Fabian Fastenrath, Philipp Wild, Alexander Hertel, Theano Papavassiliu, Salman Ul Hassan Dar, Sandy Engelhardt
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Latent diffusion models (LDMs) have recently achieved strong performance in 3D medical image synthesis. However, modalities like cine cardiac MRI (CMR), representing a temporally synchronized 3D volume across the cardiac cycle, add an additional dimension that most generative approaches do not model directly. Instead, they factorize space and time or enforce temporal consistency through auxiliary mechanisms such as anatomical masks. Such strategies introduce structural biases that may limit global context integration and lead to subtle spatiotemporal discontinuities or physiologically inconsistent cardiac dynamics. We investigate whether a unified 4D generative model can learn continuous cardiac dynamics without architectural factorization. We propose CardioDiT, a fully 4D latent diffusion framework for short-axis cine CMR synthesis based on diffusion transformers. A spatiotemporal VQ-VAE encodes 2D+t slices into compact latents, which a diffusion transformer then models jointly as complete 3D+t volumes, coupling space and time throughout the generative process. We evaluate CardioDiT on public CMR datasets and a larger private cohort, comparing it to baselines with progressively stronger spatiotemporal coupling. Results show improved inter-slice consistency, temporally coherent motion, and realistic cardiac function distributions, suggesting that explicit 4D modeling with a diffusion transformer provides a principled foundation for spatiotemporal cardiac image synthesis. Code and models trained on public data are available at this https URL.
### Title:
          Free-Lunch Long Video Generation via Layer-Adaptive O.O.D Correction
 - **Authors:** Jiahao Tian, Chenxi Song, Wei Cheng, Chi Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generating long videos using pre-trained video diffusion models, which are typically trained on short clips, presents a significant challenge. Directly applying these models for long-video inference often leads to a notable degradation in visual quality. This paper identifies that this issue primarily stems from two out-of-distribution (O.O.D) problems: frame-level relative position O.O.D and context-length O.O.D. To address these challenges, we propose FreeLOC, a novel training-free, layer-adaptive framework that introduces two core techniques: Video-based Relative Position Re-encoding (VRPR) for frame-level relative position O.O.D, a multi-granularity strategy that hierarchically re-encodes temporal relative positions to align with the model's pre-trained distribution, and Tiered Sparse Attention (TSA) for context-length O.O.D, which preserves both local detail and long-range dependencies by structuring attention density across different temporal scales. Crucially, we introduce a layer-adaptive probing mechanism that identifies the sensitivity of each transformer layer to these O.O.D issues, allowing for the selective and efficient application of our methods. Extensive experiments demonstrate that our approach significantly outperforms existing training-free methods, achieving state-of-the-art results in both temporal consistency and visual quality. Code is available at this https URL.
### Title:
          A Wireless World Model for AI-Native 6G Networks
 - **Authors:** Ziqi Chen, Yi Ren, Yixuan Huang, Qi Sun, Nan Li, Yuhong Huang, Chih-Lin I, Yifan Li, Liang Xia
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI); Artificial Intelligence (cs.AI); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Integrating AI into the physical layer is a cornerstone of 6G networks. However, current data-driven approaches struggle to generalize across dynamic environments because they lack an intrinsic understanding of electromagnetic wave propagation. We introduce the Wireless World Model (WWM), a multi-modal foundation framework predicting the spatiotemporal evolution of wireless channels by internalizing the causal relationship between 3D geometry and signal dynamics. Pre-trained on a massive ray-traced multi-modal dataset, WWM overcomes the data authenticity gap, further validated under real-world measurement data. Using a joint-embedding predictive architecture with a multi-modal mixture-of-experts Transformer, WWM fuses channel state information, 3D point clouds, and user trajectories into a unified representation. Across the five key downstream tasks supported by WWM, it achieves remarkable performance in seen environments, unseen generalization scenarios, and real-world measurements, consistently outperforming SOTA uni-modal foundation models and task-specific models. This paves the way for physics-aware 6G intelligence that adapts to the physical world.
### Title:
          Offline Decision Transformers for Neural Combinatorial Optimization: Surpassing Heuristics on the Traveling Salesman Problem
 - **Authors:** Hironori Ohigashi, Shinichiro Hamada
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Combinatorial optimization problems like the Traveling Salesman Problem are critical in industry yet NP-hard. Neural Combinatorial Optimization has shown promise, but its reliance on online reinforcement learning (RL) hampers deployment and underutilizes decades of algorithmic knowledge. We address these limitations by applying the offline RL framework, Decision Transformer, to learn superior strategies directly from datasets of heuristic solutions; it aims to not only to imitate but to synthesize and outperform them. Concretely, we (i) integrate a Pointer Network to handle the instance-dependent, variable action space of node selection, and (ii) employ expectile regression for optimistic conditioning of Return-to-Go, which is crucial for instances with widely varying optimal values. Experiments show that our method consistently produces higher-quality tours than the four classical heuristics it is trained on, demonstrating the potential of offline RL to unlock and exceed the performance embedded in existing domain knowledge.
### Title:
          Hyperspectral Trajectory Image for Multi-Month Trajectory Anomaly Detection
 - **Authors:** Md Awsafur Rahman, Chandrakanth Gudavalli, Hardik Prajapati, B. S. Manjunath
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Trajectory anomaly detection underpins applications from fraud detection to urban mobility analysis. Dense GPS methods preserve fine-grained evidence such as abnormal speeds and short-duration events, but their quadratic cost makes multi-month analysis intractable; consequently, no existing approach detects anomalies over multi-month dense GPS trajectories. The field instead relies on scalable sparse stay-point methods that discard this evidence, forcing separate architectures for each regime and preventing knowledge transfer. We argue this bottleneck is unnecessary: human trajectories, dense or sparse, share a natural two-dimensional cyclic structure along within-day and across-day axes. We therefore propose TITAnD (Trajectory Image Transformer for Anomaly Detection), which reformulates trajectory anomaly detection as a vision problem by representing trajectories as a Hyperspectral Trajectory Image (HTI): a day x time-of-day grid whose channels encode spatial, semantic, temporal, and kinematic information from either modality, unifying both under a single representation. Under this formulation, agent-level detection reduces to image classification and temporal localization to semantic segmentation. To model this representation, we introduce the Cyclic Factorized Transformer (CFT), which factorizes attention along the two temporal axes, encoding the cyclic inductive bias of human routines, while reducing attention cost by orders of magnitude and enabling dense multi-month anomaly detection for the first time. Empirically, TITAnD achieves the best AUC-PR across sparse and dense benchmarks, surpassing vision models like UNet while being 11-75x faster than the Transformer with comparable memory, demonstrating that vision reformulation and structure-aware modeling are jointly essential. Code will be made public soon.
### Title:
          Probabilistic Abstract Interpretation on Neural Networks via Grids Approximation
 - **Authors:** Zhuofan Zhang, Herbert Wiklicky
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Probabilistic abstract interpretation is a theory used to extract particular properties of a computer program when it is infeasible to test every single inputs. In this paper we apply the theory on neural networks for the same purpose: to analyse density distribution flow of all possible inputs of a neural network when a network has uncountably many or countable but infinitely many inputs. We show how this theoretical framework works in neural networks and then discuss different abstract domains and corresponding Moore-Penrose pseudo-inverses together with abstract transformers used in the framework. We also present experimental examples to show how this framework helps to analyse real world problems.
### Title:
          Distribution and Clusters Approximations as Abstract Domains in Probabilistic Abstract Interpretation to Neural Network Analysis
 - **Authors:** Zhuofan Zhang, Herbert Wiklicky
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The probabilistic abstract interpretation framework of neural network analysis analyzes a neural network by analyzing its density distribution flow of all possible inputs. The grids approximation is one of abstract domains the framework uses which abstracts concrete space into grids. In this paper, we introduce two novel approximation methods: distribution approximation and clusters approximation. We show how these two methods work in theory with corresponding abstract transformers with help of illustrations of some simple examples.
### Title:
          Adaptive Learned Image Compression with Graph Neural Networks
 - **Authors:** Yunuo Chen, Bing He, Zezheng Lyu, Hongwei Hu, Qunshan Gu, Yuan Tian, Guo Lu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Efficient image compression relies on modeling both local and global redundancy. Most state-of-the-art (SOTA) learned image compression (LIC) methods are based on CNNs or Transformers, which are inherently rigid. Standard CNN kernels and window-based attention mechanisms impose fixed receptive fields and static connectivity patterns, which potentially couple non-redundant pixels simply due to their proximity in Euclidean space. This rigidity limits the model's ability to adaptively capture spatially varying redundancy across the image, particularly at the global level. To overcome these limitations, we propose a content-adaptive image compression framework based on Graph Neural Networks (GNNs). Specifically, our approach constructs dual-scale graphs that enable flexible, data-driven receptive fields. Furthermore, we introduce adaptive connectivity by dynamically adjusting the number of neighbors for each node based on local content complexity. These innovations empower our Graph-based Learned Image Compression (GLIC) model to effectively model diverse redundancy patterns across images, leading to more efficient and adaptive compression. Experiments demonstrate that GLIC achieves state-of-the-art performance, achieving BD-rate reductions of 19.29%, 21.69%, and 18.71% relative to VTM-9.1 on Kodak, Tecnick, and CLIC, respectively. Code will be released at this https URL.
### Title:
          HeSS: Head Sensitivity Score for Sparsity Redistribution in VGGT
 - **Authors:** Yongsung Kim, Wooseok Song, Jaihyun Lew, Hun Hwangbo, Jaehoon Lee, Sungroh Yoon
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual Geometry Grounded Transformer (VGGT) has advanced 3D vision, yet its global attention layers suffer from quadratic computational costs that hinder scalability. Several sparsification-based acceleration techniques have been proposed to alleviate this issue, but they often suffer from substantial accuracy degradation. We hypothesize that the accuracy degradation stems from the heterogeneity in head-wise sparsification sensitivity, as the existing methods apply a uniform sparsity pattern across all heads. Motivated by this hypothesis, we present a two-stage sparsification pipeline that effectively quantifies and exploits headwise sparsification sensitivity. In the first stage, we measure head-wise sparsification sensitivity using a novel metric, the Head Sensitivity Score (HeSS), which approximates the Hessian with respect to two distinct error terms on a small calibration set. In the inference stage, we perform HeSS-Guided Sparsification, leveraging the pre-computed HeSS to reallocate the total attention budget-assigning denser attention to sensitive heads and sparser attention to more robust ones. We demonstrate that HeSS effectively captures head-wise sparsification sensitivity and empirically confirm that attention heads in the global attention layers exhibit heterogeneous sensitivity characteristics. Extensive experiments further show that our method effectively mitigates performance degradation under high sparsity, demonstrating strong robustness across varying sparsification levels. Code is available at this https URL.
### Title:
          InstanceAnimator: Multi-Instance Sketch Video Colorization
 - **Authors:** Yinhan Zhang, Yue Ma, Bingyuan Wang, Kunyu Feng, Yeying Jin, Qifeng Chen, Anyi Rao, Zeyu Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose InstanceAnimator, a novel Diffusion Transformer framework for multi-instance sketch video colorization. Existing methods suffer from three core limitations: inflexible user control due to heavy reliance on single reference frames, poor instance controllability leading to misalignment in multi-character scenarios, and degraded detail fidelity in fine-grained regions. To address these challenges, we introduce three corresponding innovations. First, a Canvas Guidance Condition eliminates workflow fragmentation by allowing free placement of reference elements and background, enabling unprecedented user flexibility. Second, an Instance Matching Mechanism resolves misalignment by integrating instance features with the sketches, ensuring precise control over multiple characters. Third, an Adaptive Decoupled Control Module enhances detail fidelity by injecting semantic features from characters, backgrounds, and text conditions into the diffusion process. Extensive experiments demonstrate that InstanceAnimator achieves superior multi-instance colorization with enhanced user control, high visual quality, and strong instance consistency.
### Title:
          Bayesian Learning-Enhanced Navigation with Deep Smoothing for Inertial-Aided Navigation
 - **Authors:** Nadav Cohen, Itzik Klein
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate post-processing navigation is essential for applications such as survey and mapping, where the full measurement history can be exploited to refine past state estimates. Fixed-interval smoothing algorithms represent the theoretically optimal solution under Gaussian assumptions. However, loosely coupled INS/GNSS systems fundamentally inherit the systematic position bias of raw GNSS measurements, leaving a persistent accuracy gap that model-based smoothers cannot resolve. To address this limitation, we propose BLENDS, which integrates Bayesian learning with deep smoothing to enhance navigation performance. BLENDS is a a data-driven post-processing framework that augments the classical two-filter smoother with a transformer-based neural network. It learns to modify the filter covariance matrices and apply an additive correction to the smoothed error-state directly within the Bayesian framework. A novel Bayesian-consistent loss jointly supervises the smoothed mean and covariance, enforcing minimum-variance estimates while maintaining statistical consistency. BLENDS is evaluated on two real-world datasets spanning a mobile robot and a quadrotor. Across all unseen test trajectories, BLENDS achieves horizontal position improvements of up to 63% over the baseline forward EKF.
### Title:
          PMT: Plain Mask Transformer for Image and Video Segmentation with Frozen Vision Encoders
 - **Authors:** Niccolò Cavagnero, Narges Norouzi, Gijs Dubbelman, Daan de Geus
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Foundation Models (VFMs) pre-trained at scale enable a single frozen encoder to serve multiple downstream tasks simultaneously. Recent VFM-based encoder-only models for image and video segmentation, such as EoMT and VidEoMT, achieve competitive accuracy with remarkably low latency, yet they require finetuning the encoder, sacrificing the multi-task encoder sharing that makes VFMs practically attractive for large-scale deployment. To reconcile encoder-only simplicity and speed with frozen VFM features, we propose the Plain Mask Decoder (PMD), a fast Transformer-based segmentation decoder that operates on top of frozen VFM features. The resulting model, the Plain Mask Transformer (PMT), preserves the architectural simplicity and low latency of encoder-only designs while keeping the encoder representation unchanged and shareable. The design seamlessly applies to both image and video segmentation, inheriting the generality of the encoder-only framework. On standard image segmentation benchmarks, PMT matches the frozen-encoder state of the art while running up to ~3x faster. For video segmentation, it even performs on par with fully finetuned methods, while being up to 8x faster than state-of-the-art frozen-encoder models. Code: this https URL.
### Title:
          VideoWeaver: Multimodal Multi-View Video-to-Video Transfer for Embodied Agents
 - **Authors:** George Eskandar, Fengyi Shen, Mohammad Altillawi, Dong Chen, Yang Bai, Liudi Yang, Ziyuan Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent progress in video-to-video (V2V) translation has enabled realistic resimulation of embodied AI demonstrations, a capability that allows pretrained robot policies to be transferable to new environments without additional data collection. However, prior works can only operate on a single view at a time, while embodied AI tasks are commonly captured from multiple synchronized cameras to support policy learning. Naively applying single-view models independently to each camera leads to inconsistent appearance across views, and standard transformer architectures do not scale to multi-view settings due to the quadratic cost of cross-view attention. We present VideoWeaver, the first multimodal multi-view V2V translation framework. VideoWeaver is initially trained as a single-view flow-based V2V model. To achieve an extension to the multi-view regime, we propose to ground all views in a shared 4D latent space derived from a feed-forward spatial foundation model, namely, Pi3. This encourages view-consistent appearance even under wide baselines and dynamic camera motion. To scale beyond a fixed number of cameras, we train views at distinct diffusion timesteps, enabling the model to learn both joint and conditional view distributions. This in turn allows autoregressive synthesis of new viewpoints conditioned on existing ones. Experiments show superior or similar performance to the state-of-the-art on the single-view translation benchmarks and, for the first time, physically and stylistically consistent multi-view translations, including challenging egocentric and heterogeneous-camera setups central to world randomization for robot learning.
### Title:
          AdaSFormer: Adaptive Serialized Transformers for Monocular Semantic Scene Completion from Indoor Environments
 - **Authors:** Xuzhi Wang, Xinran Wu, Song Wang, Lingdong Kong, Ziping Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Indoor monocular semantic scene completion (MSSC) is notably more challenging than its outdoor counterpart due to complex spatial layouts and severe occlusions. While transformers are well suited for modeling global dependencies, their high memory cost and difficulty in reconstructing fine-grained details have limited their use in indoor MSSC. To address these limitations, we introduce AdaSFormer, a serialized transformer framework tailored for indoor MSSC. Our model features three key designs: (1) an Adaptive Serialized Transformer with learnable shifts that dynamically adjust receptive fields; (2) a Center-Relative Positional Encoding that captures spatial information richness; and (3) a Convolution-Modulated Layer Normalization that bridges heterogeneous representations between convolutional and transformer features. Extensive experiments on NYUv2 and Occ-ScanNet demonstrate that AdaSFormer achieves state-of-the-art performance. The code is publicly available at: this https URL.
### Title:
          An Experimental Comparison of the Most Popular Approaches to Fake News Detection
 - **Authors:** Pietro Dell'Oglio, Alessandro Bondielli, Francesco Marcelloni, Lucia C. Passaro
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In recent years, fake news detection has received increasing attention in public debate and scientific research. Despite advances in detection techniques, the production and spread of false information have become more sophisticated, driven by Large Language Models (LLMs) and the amplification power of social media. We present a critical assessment of 12 representative fake news detection approaches, spanning traditional machine learning, deep learning, transformers, and specialized cross-domain architectures. We evaluate these methods on 10 publicly available datasets differing in genre, source, topic, and labeling rationale. We address text-only English fake news detection as a binary classification task by harmonizing labels into "Real" and "Fake" to ensure a consistent evaluation protocol. We acknowledge that label semantics vary across datasets and that harmonization inevitably removes such semantic nuances. Each dataset is treated as a distinct domain. We conduct in-domain, multi-domain and cross-domain experiments to simulate real-world scenarios involving domain shift and out-of-distribution data. Fine-tuned models perform well in-domain but struggle to generalize. Cross-domain architectures can reduce this gap but are data-hungry, while LLMs offer a promising alternative through zero- and few-shot learning. Given inherent dataset confounds and possible pre-training exposure, results should be interpreted as robustness evaluations within this English, text-only protocol.
### Title:
          Lightweight GenAI for Network Traffic Synthesis: Fidelity, Augmentation, and Classification
 - **Authors:** Giampaolo Bovenzi, Domenico Ciuonzo, Jonatan Krolikowski, Antonio Montieri, Alfredo Nascita, Antonio Pescapè, Dario Rossi
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate Network Traffic Classification (NTC) is increasingly constrained by limited labeled data and strict privacy requirements. While Network Traffic Generation (NTG) provides an effective means to mitigate data scarcity, conventional generative methods struggle to model the complex temporal dynamics of modern traffic or/and often incur significant computational cost. In this article, we address the NTG task using lightweight Generative Artificial Intelligence (GenAI) architectures, including transformer-based, state-space, and diffusion models designed for practical deployment. We conduct a systematic evaluation along four axes: (i) (synthetic) traffic fidelity, (ii) synthetic-only training, (iii) data augmentation under low-data regimes, and (iv) computational efficiency. Experiments on two heterogeneous datasets show that lightweight GenAI models preserve both static and temporal traffic characteristics, with transformer and state-space models closely matching real distributions across a complete set of fidelity metrics. Classifiers trained solely on synthetic traffic achieve up to 87% F1-score on real data. In low-data settings, GenAI-driven augmentation improves NTC performance by up to +40%, substantially reducing the gap with full-data training. Overall, transformer-based models provide the best trade-off between fidelity and efficiency, enabling high-quality, privacy-aware traffic synthesis with modest computational overhead.
### Title:
          DeepFAN, a transformer-based deep learning model for human-artificial intelligence collaborative assessment of incidental pulmonary nodules in CT scans: a multi-reader, multi-case trial
 - **Authors:** Zhenchen Zhu, Ge Hu, Weixiong Tan, Kai Gao, Chao Sun, Zhen Zhou, Kepei Xu, Wei Han, Meixia Shang, Xiaoming Qiu, Yiqing Tan, Jinhua Wang, Zhoumeng Ying, Li Peng, Wei Song, Lan Song, Zhengyu Jin, Nan Hong, Yizhou Yu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The widespread adoption of CT has notably increased the number of detected lung nodules. However, current deep learning methods for classifying benign and malignant nodules often fail to comprehensively integrate global and local features, and most of them have not been validated through clinical trials. To address this, we developed DeepFAN, a transformer-based model trained on over 10K pathology-confirmed nodules and further conducted a multi-reader, multi-case clinical trial to evaluate its efficacy in assisting junior radiologists. DeepFAN achieved diagnostic area under the curve (AUC) of 0.939 (95% CI 0.930-0.948) on an internal test set and 0.954 (95% CI 0.934-0.973) on the clinical trial dataset involving 400 cases across three independent medical institutions. Explainability analysis indicated higher contributions from global than local features. Twelve readers' average performance significantly improved by 10.9% (95% CI 8.3%-13.5%) in AUC, 10.0% (95% CI 8.9%-11.1%) in accuracy, 7.6% (95% CI 6.1%-9.2%) in sensitivity, and 12.6% (95% CI 10.9%-14.3%) in specificity (P<0.001 for all). Nodule-level inter-reader diagnostic consistency improved from fair to moderate (overall k: 0.313 vs. 0.421; P=0.019). In conclusion, DeepFAN effectively assisted junior radiologists and may help homogenize diagnostic quality and reduce unnecessary follow-up of indeterminate pulmonary nodules. Chinese Clinical Trial Registry: ChiCTR2400084624.
### Title:
          LanteRn: Latent Visual Structured Reasoning
 - **Authors:** André G. Viveiros, Nuno Gonçalves, Matthias Lindemann, André Martins
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While language reasoning models excel in many tasks, visual reasoning remains challenging for current large multimodal models (LMMs). As a result, most LMMs default to verbalizing perceptual content into text, a strong limitation for tasks requiring fine-grained spatial and visual understanding. While recent approaches take steps toward thinking with images by invoking tools or generating intermediate images, they either rely on external modules, or incur unnecessary computation by reasoning directly in pixel space. In this paper, we introduce LanteRn, a framework that enables LMMs to interleave language with compact latent visual representations, allowing visual reasoning to occur directly in latent space. LanteRn augments a vision-language transformer with the ability to generate and attend to continuous visual thought embeddings during inference. We train the model in two stages: supervised fine-tuning to ground visual features in latent states, followed by reinforcement learning to align latent reasoning with task-level utility. We evaluate LanteRn on three perception-centric benchmarks (VisCoT, V*, and Blink), observing consistent improvements in visual grounding and fine-grained reasoning. These results suggest that internal latent representations provide a promising direction for more efficient multimodal reasoning.
### Title:
          Anchored-Branched Steady-state WInd Flow Transformer (AB-SWIFT): a metamodel for 3D atmospheric flow in urban environments
 - **Authors:** Armand de Villeroché, Rem-Sophia Mouradi, Vincent Le Guen, Sibo Cheng, Marc Bocquet, Alban Farchi, Patrick Armand, Patrick Massin
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Atmospheric and Oceanic Physics (physics.ao-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Air flow modeling at a local scale is essential for applications such as pollutant dispersion modeling or wind farm modeling. To circumvent costly Computational Fluid Dynamics (CFD) computations, deep learning surrogate models have recently emerged as promising alternatives. However, in the context of urban air flow, deep learning models struggle to adapt to the high variations of the urban geometry and to large mesh sizes. To tackle these challenges, we introduce Anchored Branched Steady-state WInd Flow Transformer (AB-SWIFT), a transformer-based model with an internal branched structure uniquely designed for atmospheric flow modeling. We train our model on a specially designed database of atmospheric simulations around randomised urban geometries and with a mixture of unstable, neutral, and stable atmospheric stratifications. Our model reaches the best accuracy on all predicted fields compared to state-of-the-art transformers and graph-based models. Our code and data is available at this https URL.
### Title:
          On Neural Scaling Laws for Weather Emulation through Continual Training
 - **Authors:** Shashank Subramanian, Alexander Kiefer, Arnur Nigmetov, Amir Gholami, Dmitriy Morozov, Michael W. Mahoney
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural scaling laws, which in some domains can predict the performance of large neural networks as a function of model, data, and compute scale, are the cornerstone of building foundation models in Natural Language Processing and Computer Vision. We study neural scaling in Scientific Machine Learning, focusing on models for weather forecasting. To analyze scaling behavior in as simple a setting as possible, we adopt a minimal, scalable, general-purpose Swin Transformer architecture, and we use continual training with constant learning rates and periodic cooldowns as an efficient training strategy. We show that models trained in this minimalist way follow predictable scaling trends and even outperform standard cosine learning rate schedules. Cooldown phases can be re-purposed to improve downstream performance, e.g., enabling accurate multi-step rollouts over longer forecast horizons as well as sharper predictions through spectral loss adjustments. We also systematically explore a wide range of model and dataset sizes under various compute budgets to construct IsoFLOP curves, and we identify compute-optimal training regimes. Extrapolating these trends to larger scales highlights potential performance limits, demonstrating that neural scaling can serve as an important diagnostic for efficient resource allocation. We open-source our code for reproducibility.
### Title:
          LEMMA: Laplacian pyramids for Efficient Marine SeMAntic Segmentation
 - **Authors:** Ishaan Gakhar, Laven Srivastava, Sankarshanaa Sagaram, Aditya Kasliwal, Ujjwal Verma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic segmentation in marine environments is crucial for the autonomous navigation of unmanned surface vessels (USVs) and coastal Earth Observation events such as oil spills. However, existing methods, often relying on deep CNNs and transformer-based architectures, face challenges in deployment due to their high computational costs and resource-intensive nature. These limitations hinder the practicality of real-time, low-cost applications in real-world marine settings. To address this, we propose LEMMA, a lightweight semantic segmentation model designed specifically for accurate remote sensing segmentation under resource constraints. The proposed architecture leverages Laplacian Pyramids to enhance edge recognition, a critical component for effective feature extraction in complex marine environments for disaster response, environmental surveillance, and coastal monitoring. By integrating edge information early in the feature extraction process, LEMMA eliminates the need for computationally expensive feature map computations in deeper network layers, drastically reducing model size, complexity and inference time. LEMMA demonstrates state-of-the-art performance across datasets captured from diverse platforms while reducing trainable parameters and computational requirements by up to 71x, GFLOPs by up to 88.5\%, and inference time by up to 84.65\%, as compared to existing models. Experimental results highlight its effectiveness and real-world applicability, including 93.42\% IoU on the Oil Spill dataset and 98.97\% mIoU on Mastr1325.
### Title:
          MegaFlow: Zero-Shot Large Displacement Optical Flow
 - **Authors:** Dingxi Zhang, Fangjinhua Wang, Marc Pollefeys, Haofei Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate estimation of large displacement optical flow remains a critical challenge. Existing methods typically rely on iterative local search or/and domain-specific fine-tuning, which severely limits their performance in large displacement and zero-shot generalization scenarios. To overcome this, we introduce MegaFlow, a simple yet powerful model for zero-shot large displacement optical flow. Rather than relying on highly complex, task-specific architectural designs, MegaFlow adapts powerful pre-trained vision priors to produce temporally consistent motion fields. In particular, we formulate flow estimation as a global matching problem by leveraging pre-trained global Vision Transformer features, which naturally capture large displacements. This is followed by a few lightweight iterative refinements to further improve the sub-pixel accuracy. Extensive experiments demonstrate that MegaFlow achieves state-of-the-art zero-shot performance across multiple optical flow benchmarks. Moreover, our model also delivers highly competitive zero-shot performance on long-range point tracking benchmarks, demonstrating its robust transferability and suggesting a unified paradigm for generalizable motion estimation. Our project page is at: this https URL.
### Title:
          RefAlign: Representation Alignment for Reference-to-Video Generation
 - **Authors:** Lei Wang, YuXin Song, Ge Wu, Haocheng Feng, Hang Zhou, Jingdong Wang, Yaxing Wang, jian Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reference-to-video (R2V) generation is a controllable video synthesis paradigm that constrains the generation process using both text prompts and reference images, enabling applications such as personalized advertising and virtual try-on. In practice, existing R2V methods typically introduce additional high-level semantic or cross-modal features alongside the VAE latent representation of the reference image and jointly feed them into the diffusion Transformer (DiT). These auxiliary representations provide semantic guidance and act as implicit alignment signals, which can partially alleviate pixel-level information leakage in the VAE latent space. However, they may still struggle to address copy--paste artifacts and multi-subject confusion caused by modality mismatch across heterogeneous encoder features. In this paper, we propose RefAlign, a representation alignment framework that explicitly aligns DiT reference-branch features to the semantic space of a visual foundation model (VFM). The core of RefAlign is a reference alignment loss that pulls the reference features and VFM features of the same subject closer to improve identity consistency, while pushing apart the corresponding features of different subjects to enhance semantic discriminability. This simple yet effective strategy is applied only during training, incurring no inference-time overhead, and achieves a better balance between text controllability and reference fidelity. Extensive experiments on the OpenS2V-Eval benchmark demonstrate that RefAlign outperforms current state-of-the-art methods in TotalScore, validating the effectiveness of explicit reference alignment for R2V tasks.
## Keyword: autonomous driving
### Title:
          TIGFlow-GRPO: Trajectory Forecasting via Interaction-Aware Flow Matching and Reward-Driven Optimization
 - **Authors:** Xuepeng Jing, Wenhuan Lu, Hao Meng, Zhizhi Yu, Jianguo Wei
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Human trajectory forecasting is important for intelligent multimedia systems operating in visually complex environments, such as autonomous driving and crowd surveillance. Although Conditional Flow Matching (CFM) has shown strong ability in modeling trajectory distributions from spatio-temporal observations, existing approaches still focus primarily on supervised fitting, which may leave social norms and scene constraints insufficiently reflected in generated trajectories. To address this issue, we propose TIGFlow-GRPO, a two-stage generative framework that aligns flow-based trajectory generation with behavioral rules. In the first stage, we build a CFM-based predictor with a Trajectory-Interaction-Graph (TIG) module to model fine-grained visual-spatial interactions and strengthen context encoding. This stage captures both agent-agent and agent-scene relations more effectively, providing more informative conditional features for subsequent alignment. In the second stage, we perform Flow-GRPO post-training,where deterministic flow rollout is reformulated as stochastic ODE-to-SDE sampling to enable trajectory exploration, and a composite reward combines view-aware social compliance with map-aware physical feasibility. By evaluating trajectories explored through SDE rollout, GRPO progressively steers multimodal predictions toward behaviorally plausible futures. Experiments on the ETH/UCY and SDD datasets show that TIGFlow-GRPO improves forecasting accuracy and long-horizon stability while generating trajectories that are more socially compliant and physically feasible. These results suggest that the proposed framework provides an effective way to connect flow-based trajectory modeling with behavior-aware alignment in dynamic multimedia environments.
### Title:
          Learning Rollout from Sampling:An R1-Style Tokenized Traffic Simulation Model
 - **Authors:** Ziyan Wang, Peng Chen, Ding Li, Chiwei Li, Qichao Zhang, Zhongpu Xia, Guizhen Yu
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning diverse and high-fidelity traffic simulations from human driving demonstrations is crucial for autonomous driving evaluation. The recent next-token prediction (NTP) paradigm, widely adopted in large language models (LLMs), has been applied to traffic simulation and achieves iterative improvements via supervised fine-tuning (SFT). However, such methods limit active exploration of potentially valuable motion tokens, particularly in suboptimal regions. Entropy patterns provide a promising perspective for enabling exploration driven by motion token uncertainty. Motivated by this insight, we propose a novel tokenized traffic simulation policy, R1Sim, which represents an initial attempt to explore reinforcement learning based on motion token entropy patterns, and systematically analyzes the impact of different motion tokens on simulation outcomes. Specifically, we introduce an entropy-guided adaptive sampling mechanism that focuses on previously overlooked motion tokens with high uncertainty yet high potential. We further optimize motion behaviors using Group Relative Policy Optimization (GRPO), guided by a safety-aware reward design. Overall, these components enable a balanced exploration-exploitation trade-off through diverse high-uncertainty sampling and group-wise comparative estimation, resulting in realistic, safe, and diverse multi-agent behaviors. Extensive experiments on the Waymo Sim Agent benchmark demonstrate that R1Sim achieves competitive performance compared to state-of-the-art methods.
### Title:
          Denoise and Align: Towards Source-Free UDA for Robust Panoramic Semantic Segmentation
 - **Authors:** Yaowen Chang, Zhen Cao, Xu Zheng, Xiaoxin Mi, Zhen Dong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Panoramic semantic segmentation is pivotal for comprehensive 360° scene understanding in critical applications like autonomous driving and virtual reality. However, progress in this domain is constrained by two key challenges: the severe geometric distortions inherent in panoramic projections and the prohibitive cost of dense annotation. While Unsupervised Domain Adaptation (UDA) from label-rich pinhole-camera datasets offers a viable alternative, many real-world tasks impose a stricter source-free (SFUDA) constraint where source data is inaccessible for privacy or proprietary reasons. This constraint significantly amplifies the core problems of domain shift, leading to unreliable pseudo-labels and dramatic performance degradation, particularly for minority classes. To overcome these limitations, we propose the DAPASS framework. DAPASS introduces two synergistic modules to robustly transfer knowledge without source data. First, our Panoramic Confidence-Guided Denoising (PCGD) module generates high-fidelity, class-balanced pseudo-labels by enforcing perturbation consistency and incorporating neighborhood-level confidence to filter noise. Second, a Contextual Resolution Adversarial Module (CRAM) explicitly addresses scale variance and distortion by adversarially aligning fine-grained details from high-resolution crops with global semantics from low-resolution contexts. DAPASS achieves state-of-the-art performances on outdoor (Cityscapes-to-DensePASS) and indoor (Stanford2D3D) benchmarks, yielding 55.04% (+2.05%) and 70.38% (+1.54%) mIoU, respectively.
### Title:
          RealRestorer: Towards Generalizable Real-World Image Restoration with Large-Scale Image Editing Models
 - **Authors:** Yufeng Yang, Xianfang Zeng, Zhangqi Jiang, Fukun Yin, Jianzhuang Liu, Wei Cheng, jinghong lan, Shiyu Liu, Yuqi Peng, Gang YU, Shifeng Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Image restoration under real-world degradations is critical for downstream tasks such as autonomous driving and object detection. However, existing restoration models are often limited by the scale and distribution of their training data, resulting in poor generalization to real-world scenarios. Recently, large-scale image editing models have shown strong generalization ability in restoration tasks, especially for closed-source models like Nano Banana Pro, which can restore images while preserving consistency. Nevertheless, achieving such performance with those large universal models requires substantial data and computational costs. To address this issue, we construct a large-scale dataset covering nine common real-world degradation types and train a state-of-the-art open-source model to narrow the gap with closed-source alternatives. Furthermore, we introduce RealIR-Bench, which contains 464 real-world degraded images and tailored evaluation metrics focusing on degradation removal and consistency preservation. Extensive experiments demonstrate our model ranks first among open-source methods, achieving state-of-the-art performance.
### Title:
          Challenges in Hyperspectral Imaging for Autonomous Driving: The HSI-Drive Case
 - **Authors:** Koldo Basterretxea, Jon Gutiérrez-Zaballa, Javier Echanobe
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The use of hyperspectral imaging (HSI) in autonomous driving (AD), while promising, faces many challenges related to the specifics and requirements of this application domain. On the one hand, non-controlled and variable lighting conditions, the wide depth-of-field ranges, and dynamic scenes with fast-moving objects. On the other hand, the requirements for real-time operation and the limited computational resources of embedded platforms. The combination of these factors determines both the criteria for selecting appropriate HSI technologies and the development of custom vision algorithms that leverage the spectral and spatial information obtained from the sensors. In this article, we analyse several techniques explored in the research of HSI-based vision systems with application to AD, using as an example results obtained from experiments using data from the most recent version of the HSI-Drive dataset.
### Title:
          Can Users Specify Driving Speed? Bench2Drive-Speed: Benchmark and Baselines for Desired-Speed Conditioned Autonomous Driving
 - **Authors:** Yuqian Shao, Xiaosong Jia, Langechuan Liu, Junchi Yan
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end autonomous driving (E2E-AD) has achieved remarkable progress. However, one practical and useful function has been long overlooked: users may wish to customize the desired speed of the policy or specify whether to allow the autonomous vehicle to overtake. To bridge this gap, we present Bench2Drive-Speed, a benchmark with metrics, dataset, and baselines for desired-speed conditioned autonomous driving. We introduce explicit inputs of users' desired target-speed and overtake/follow instructions to driving policy models. We design quantitative metrics, including Speed-Adherence Score and Overtake Score, to measure how faithfully policies follow user specifications, while remaining compatible with standard autonomous driving metrics. To enable training of speed-conditioned policies, one approach is to collect expert demonstrations that strictly follow speed requirements, an expensive and unscalable process in the real world. An alternative is to adapt existing regular driving data by treating the speed observed in future frames as the target speed for training. To investigate this, we construct CustomizedSpeedDataset, composed of 2,100 clips annotated with experts demonstrations, enabling systematic investigation of supervision strategies. Our experiments show that, under proper re-annotation, models trained on regular driving data perform comparably to on expert demonstrations, suggesting that speed supervision can be introduced without additional complex real-world data collection. Furthermore, we find that while target-speed following can be achieved without degrading regular driving performance, executing overtaking commands remains challenging due to the inherent difficulty of interactive behaviors. All code, datasets and baselines are available at this https URL
### Title:
          Drive My Way: Preference Alignment of Vision-Language-Action Model for Personalized Driving
 - **Authors:** Zehao Wang, Huaide Jiang, Shuaiwu Dong, Yuping Wang, Hang Qiu, Jiachen Li
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Human driving behavior is inherently personal, which is shaped by long-term habits and influenced by short-term intentions. Individuals differ in how they accelerate, brake, merge, yield, and overtake across diverse situations. However, existing end-to-end autonomous driving systems either optimize for generic objectives or rely on fixed driving modes, lacking the ability to adapt to individual preferences or interpret natural language intent. To address this gap, we propose Drive My Way (DMW), a personalized Vision-Language-Action (VLA) driving framework that aligns with users' long-term driving habits and adapts to real-time user instructions. DMW learns a user embedding from our personalized driving dataset collected across multiple real drivers and conditions the policy on this embedding during planning, while natural language instructions provide additional short-term guidance. Closed-loop evaluation on the Bench2Drive benchmark demonstrates that DMW improves style instruction adaptation, and user studies show that its generated behaviors are recognizable as each driver's own style, highlighting personalization as a key capability for human-centered autonomous driving. Our data and code are available at this https URL.
### Title:
          Vega: Learning to Drive with Natural Language Instructions
 - **Authors:** Sicheng Zuo, Yuxuan Li, Wenzhao Zheng, Zheng Zhu, Jie Zhou, Jiwen Lu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language-action models have reshaped autonomous driving to incorporate languages into the decision-making process. However, most existing pipelines only utilize the language modality for scene descriptions or reasoning and lack the flexibility to follow diverse user instructions for personalized driving. To address this, we first construct a large-scale driving dataset (InstructScene) containing around 100,000 scenes annotated with diverse driving instructions with the corresponding trajectories. We then propose a unified Vision-Language-World-Action model, Vega, for instruction-based generation and planning. We employ the autoregressive paradigm to process visual inputs (vision) and language instructions (language) and the diffusion paradigm to generate future predictions (world modeling) and trajectories (action). We perform joint attention to enable interactions between the modalities and use individual projection layers for different modalities for more capabilities. Extensive experiments demonstrate that our method not only achieves superior planning performance but also exhibits strong instruction-following abilities, paving the way for more intelligent and personalized driving systems.
