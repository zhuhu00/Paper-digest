# Showing new listings for Monday, 23 March 2026
## Keyword: SLAM
### Title:
          IUP-Pose: Decoupled Iterative Uncertainty Propagation for Real-time Relative Pose Regression via Implicit Dense Alignment v1
 - **Authors:** Jun Wang, Xiaoyan Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Relative pose estimation is fundamental for SLAM, visual localization, and 3D reconstruction. Existing Relative Pose Regression (RPR) methods face a key trade-off: feature-matching pipelines achieve high accuracy but block gradient flow via non-differentiable RANSAC, while ViT-based regressors are end-to-end trainable but prohibitively expensive for real-time deployment. We identify the core bottlenecks as the coupling between rotation and translation estimation and insufficient cross-view feature alignment. We propose IUP-Pose, a geometry-driven decoupled iterative framework with implicit dense alignment. A lightweight Multi-Head Bi-Cross Attention (MHBC) module aligns cross-view features without explicit matching supervision. The aligned features are processed by a decoupled rotation-translation pipeline: two shared-parameter rotation stages iteratively refine rotation with uncertainty, and feature maps are realigned via rotational homography H_inf before translation prediction. IUP-Pose achieves 73.3% AUC@20deg on MegaDepth1500 with full end-to-end differentiability, 70 FPS throughput, and only 37M parameters, demonstrating a favorable accuracy-efficiency trade-off for real-time edge deployment.
### Title:
          HortiMulti: A Multi-Sensor Dataset for Localisation and Mapping in Horticultural Polytunnels
 - **Authors:** Shuoyuan Xu, Zhipeng Zhong, Tiago Barros, Matthew Coombes, Cristiano Premebida, Hao Wu, Cunjia Liu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Agricultural robotics is gaining increasing relevance in both research and real-world deployment. As these systems are expected to operate autonomously in more complex tasks, the availability of representative real-world datasets becomes essential. While domains such as urban and forestry robotics benefit from large and established benchmarks, horticultural environments remain comparatively under-explored despite the economic significance of this sector. To address this gap, we present HortiMulti, a multimodal, cross-season dataset collected in commercial strawberry and raspberry polytunnels across an entire growing season, capturing substantial appearance variation, dynamic foliage, specular reflections from plastic covers, severe perceptual aliasing, and GNSS-unreliable conditions, all of which directly degrade existing localisation and perception algorithms. The sensor suite includes two 3D LiDARs, four RGB cameras, an IMU, GNSS, and wheel odometry. Ground truth trajectories are derived from a combination of Total Station surveying, AprilTag fiducial markers, and LiDAR-inertial odometry, spanning dense, sparse, and marker-free coverage to support evaluation under both controlled and realistic conditions. We release time-synchronised raw measurements, calibration files, reference trajectories, and baseline benchmarks for visual, LiDAR, and multi-sensor SLAM, with results confirming that current state-of-the-art methods remain inadequate for reliable polytunnel deployment, establishing HortiMulti as a one-stop resource for developing and testing robotic perception systems in horticulture environments.
## Keyword: odometry
### Title:
          Radar-Inertial Odometry with Online Spatio-Temporal Calibration via Continuous-Time IMU Modeling
 - **Authors:** Vlaho-Josip Štironja, Luka Petrović, Juraj Peršić, Ivan Marković, Ivan Petrović
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Radar-Inertial Odometry (RIO) has emerged as a robust alternative to vision- and LiDAR-based odometry in challenging conditions such as low light, fog, featureless environments, or in adverse weather. However, many existing RIO approaches assume known radar-IMU extrinsic calibration or rely on sufficient motion excitation for online extrinsic estimation, while temporal misalignment between sensors is often neglected or treated independently. In this work, we present a RIO framework that performs joint online spatial and temporal calibration within a factor-graph optimization formulation, based on continuous-time modeling of inertial measurements using uniform cubic B-splines. The proposed continuous-time representation of acceleration and angular velocity accurately captures the asynchronous nature of radar-IMU measurements, enabling reliable convergence of both the temporal offset and extrinsic calibration parameters, without relying on scan matching, target tracking, or environment-specific assumptions.
### Title:
          HortiMulti: A Multi-Sensor Dataset for Localisation and Mapping in Horticultural Polytunnels
 - **Authors:** Shuoyuan Xu, Zhipeng Zhong, Tiago Barros, Matthew Coombes, Cristiano Premebida, Hao Wu, Cunjia Liu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Agricultural robotics is gaining increasing relevance in both research and real-world deployment. As these systems are expected to operate autonomously in more complex tasks, the availability of representative real-world datasets becomes essential. While domains such as urban and forestry robotics benefit from large and established benchmarks, horticultural environments remain comparatively under-explored despite the economic significance of this sector. To address this gap, we present HortiMulti, a multimodal, cross-season dataset collected in commercial strawberry and raspberry polytunnels across an entire growing season, capturing substantial appearance variation, dynamic foliage, specular reflections from plastic covers, severe perceptual aliasing, and GNSS-unreliable conditions, all of which directly degrade existing localisation and perception algorithms. The sensor suite includes two 3D LiDARs, four RGB cameras, an IMU, GNSS, and wheel odometry. Ground truth trajectories are derived from a combination of Total Station surveying, AprilTag fiducial markers, and LiDAR-inertial odometry, spanning dense, sparse, and marker-free coverage to support evaluation under both controlled and realistic conditions. We release time-synchronised raw measurements, calibration files, reference trajectories, and baseline benchmarks for visual, LiDAR, and multi-sensor SLAM, with results confirming that current state-of-the-art methods remain inadequate for reliable polytunnel deployment, establishing HortiMulti as a one-stop resource for developing and testing robotic perception systems in horticulture environments.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          FlashCap: Millisecond-Accurate Human Motion Capture via Flashing LEDs and Event-Based Vision
 - **Authors:** Zekai Wu, Shuqi Fan, Mengyin Liu, Yuhua Luo, Xincheng Lin, Ming Yan, Junhao Wu, Xiuhong Lin, Yuexin Ma, Chenglu Wen, Lan Xu, Siqi Shen, Cheng Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Precise motion timing (PMT) is crucial for swift motion analysis. A millisecond difference may determine victory or defeat in sports competitions. Despite substantial progress in human pose estimation (HPE), PMT remains largely overlooked by the HPE community due to the limited availability of high-temporal-resolution labeled datasets. Today, PMT is achieved using high-speed RGB cameras in specialized scenarios such as the Olympic Games; however, their high costs, light sensitivity, bandwidth, and computational complexity limit their feasibility for daily use. We developed FlashCap, the first flashing LED-based MoCap system for PMT. With FlashCap, we collect a millisecond-resolution human motion dataset, FlashMotion, comprising the event, RGB, LiDAR, and IMU modalities, and demonstrate its high quality through rigorous validation. To evaluate the merits of FlashMotion, we perform two tasks: precise motion timing and high-temporal-resolution HPE. For these tasks, we propose ResPose, a simple yet effective baseline that learns residual poses based on events and RGBs. Experimental results show that ResPose reduces pose estimation errors by ~40% and achieves millisecond-level timing accuracy, enabling new research opportunities. The dataset and code will be shared with the community.
### Title:
          Real-Time Structural Detection for Indoor Navigation from 3D LiDAR Using Bird's-Eye-View Images
 - **Authors:** Guanliang Li, Pedro Espinosa Angulo, David Perez Saura, Santiago Tapia Fernandez
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Efficient structural perception is essential for mapping and autonomous navigation on resource-constrained robots. Existing 3D methods are computationally prohibitive, while traditional 2D geometric approaches lack robustness. This paper presents a lightweight, real-time framework that projects 3D LiDAR data into 2D Bird's-Eye-View (BEV) images to enable efficient detection of structural elements relevant to mapping and navigation. Within this representation, we systematically evaluate several feature extraction strategies, including classical geometric techniques (Hough Transform, RANSAC, and LSD) and a deep learning detector based on YOLO-OBB. The resulting detections are integrated through a spatiotemporal fusion module that improves stability and robustness across consecutive frames. Experiments conducted on a standard mobile robotic platform highlight clear performance trade-offs. Classical methods such as Hough and LSD provide fast responses but exhibit strong sensitivity to noise, with LSD producing excessive segment fragmentation that leads to system congestion. RANSAC offers improved robustness but fails to meet real-time constraints. In contrast, the YOLO-OBB-based approach achieves the best balance between robustness and computational efficiency, maintaining an end-to-end latency (satisfying 10 Hz operation) while effectively filtering cluttered observations in a low-power single-board computer (SBC) without using GPU acceleration. The main contribution of this work is a computationally efficient BEV-based perception pipeline enabling reliable real-time structural detection from 3D LiDAR on resource-constrained robotic platforms that cannot rely on GPU-intensive processing.
### Title:
          LIORNet: Self-Supervised LiDAR Snow Removal Framework for Autonomous Driving under Adverse Weather Conditions
 - **Authors:** Ji-il Park, Inwook Shim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR sensors provide high-resolution 3D perception and long-range detection, making them indispensable for autonomous driving and robotics. However, their performance significantly degrades under adverse weather conditions such as snow, rain, and fog, where spurious noise points dominate the point cloud and lead to false perception. To address this problem, various approaches have been proposed: distance-based filters exploiting spatial sparsity, intensity-based filters leveraging reflectance distributions, and learning-based methods that adapt to complex environments. Nevertheless, distance-based methods struggle to distinguish valid object points from noise, intensity-based methods often rely on fixed thresholds that lack adaptability to changing conditions, and learning-based methods suffer from the high cost of annotation, limited generalization, and computational overhead. In this study, we propose LIORNet, which eliminates these drawbacks and integrates the strengths of all three paradigms. LIORNet is built upon a U-Net++ backbone and employs a self-supervised learning strategy guided by pseudo-labels generated from multiple physical and statistical cues, including range-dependent intensity thresholds, snow reflectivity, point sparsity, and sensing range constraints. This design enables LIORNet to distinguish noise points from environmental structures without requiring manual annotations, thereby overcoming the difficulty of snow labeling and the limitations of single-principle approaches. Extensive experiments on the WADS and CADC datasets demonstrate that LIORNet outperforms state-of-the-art filtering algorithms in both accuracy and runtime while preserving critical environmental features. These results highlight LIORNet as a practical and robust solution for LiDAR perception in extreme weather, with strong potential for real-time deployment in autonomous driving systems.
### Title:
          Radar-Inertial Odometry with Online Spatio-Temporal Calibration via Continuous-Time IMU Modeling
 - **Authors:** Vlaho-Josip Štironja, Luka Petrović, Juraj Peršić, Ivan Marković, Ivan Petrović
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Radar-Inertial Odometry (RIO) has emerged as a robust alternative to vision- and LiDAR-based odometry in challenging conditions such as low light, fog, featureless environments, or in adverse weather. However, many existing RIO approaches assume known radar-IMU extrinsic calibration or rely on sufficient motion excitation for online extrinsic estimation, while temporal misalignment between sensors is often neglected or treated independently. In this work, we present a RIO framework that performs joint online spatial and temporal calibration within a factor-graph optimization formulation, based on continuous-time modeling of inertial measurements using uniform cubic B-splines. The proposed continuous-time representation of acceleration and angular velocity accurately captures the asynchronous nature of radar-IMU measurements, enabling reliable convergence of both the temporal offset and extrinsic calibration parameters, without relying on scan matching, target tracking, or environment-specific assumptions.
### Title:
          HortiMulti: A Multi-Sensor Dataset for Localisation and Mapping in Horticultural Polytunnels
 - **Authors:** Shuoyuan Xu, Zhipeng Zhong, Tiago Barros, Matthew Coombes, Cristiano Premebida, Hao Wu, Cunjia Liu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Agricultural robotics is gaining increasing relevance in both research and real-world deployment. As these systems are expected to operate autonomously in more complex tasks, the availability of representative real-world datasets becomes essential. While domains such as urban and forestry robotics benefit from large and established benchmarks, horticultural environments remain comparatively under-explored despite the economic significance of this sector. To address this gap, we present HortiMulti, a multimodal, cross-season dataset collected in commercial strawberry and raspberry polytunnels across an entire growing season, capturing substantial appearance variation, dynamic foliage, specular reflections from plastic covers, severe perceptual aliasing, and GNSS-unreliable conditions, all of which directly degrade existing localisation and perception algorithms. The sensor suite includes two 3D LiDARs, four RGB cameras, an IMU, GNSS, and wheel odometry. Ground truth trajectories are derived from a combination of Total Station surveying, AprilTag fiducial markers, and LiDAR-inertial odometry, spanning dense, sparse, and marker-free coverage to support evaluation under both controlled and realistic conditions. We release time-synchronised raw measurements, calibration files, reference trajectories, and baseline benchmarks for visual, LiDAR, and multi-sensor SLAM, with results confirming that current state-of-the-art methods remain inadequate for reliable polytunnel deployment, establishing HortiMulti as a one-stop resource for developing and testing robotic perception systems in horticulture environments.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          3D Gaussian Splatting with Self-Constrained Priors for High Fidelity Surface Reconstruction
 - **Authors:** Takeshi Noda, Yu-Shen Liu, Zhizhong Han
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rendering 3D surfaces has been revolutionized within the modeling of radiance fields through either 3DGS or NeRF. Although 3DGS has shown advantages over NeRF in terms of rendering quality or speed, there is still room for improvement in recovering high fidelity surfaces through 3DGS. To resolve this issue, we propose a self-constrained prior to constrain the learning of 3D Gaussians, aiming for more accurate depth rendering. Our self-constrained prior is derived from a TSDF grid that is obtained by fusing the depth maps rendered with current 3D Gaussians. The prior measures a distance field around the estimated surface, offering a band centered at the surface for imposing more specific constraints on 3D Gaussians, such as removing Gaussians outside the band, moving Gaussians closer to the surface, and encouraging larger or smaller opacity in a geometry-aware manner. More importantly, our prior can be regularly updated by the most recent depth images which are usually more accurate and complete. In addition, the prior can also progressively narrow the band to tighten the imposed constraints. We justify our idea and report our superiority over the state-of-the-art methods in evaluations on widely used benchmarks.
### Title:
          Generalizable NGP-SR: Generalizable Neural Radiance Fields Super-Resolution via Neural Graph Primitives
 - **Authors:** Wanqi Yuan, Omkar Sharad Mayekar, Connor Pennington, Nianyi Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural Radiance Fields (NeRF) achieve photorealistic novel view synthesis but become costly when high-resolution (HR) rendering is required, as HR outputs demand dense sampling and higher-capacity models. Moreover, naively super-resolving per-view renderings in 2D often breaks multi-view consistency. We propose Generalizable NGP-SR, a 3D-aware super-resolution framework that reconstructs an HR radiance field directly from low-resolution (LR) posed images. Built on Neural Graphics Primitives (NGP), NGP-SR conditions radiance prediction on 3D coordinates and learned local texture tokens, enabling recovery of high-frequency details within the radiance field and producing view-consistent HR novel views without external HR references or post-hoc 2D upsampling. Importantly, our model is generalizable: once trained, it can be applied to unseen scenes and rendered from novel viewpoints without per-scene optimization. Experiments on multiple datasets show that NGP-SR consistently improves both reconstruction quality and runtime efficiency over prior NeRF-based super-resolution methods, offering a practical solution for scalable high-resolution novel view synthesis.
## Keyword: mapping
### Title:
          Beltrami coefficient and angular distortion of discrete geometric mappings
 - **Authors:** Zhiyuan Lyu, Gary P. T. Choi
 - **Subjects:** Subjects:
Graphics (cs.GR); Complex Variables (math.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Over the past several decades, geometric mapping methods have been extensively developed and utilized for many practical problems in science and engineering. To assess the quality of geometric mappings, one common consideration is their conformality. In particular, it is well-known that conformal mappings preserve angles and hence the local geometry, which is beneficial in many applications. Therefore, many existing works have focused on the angular distortion as a measure of the conformality of mappings. More recently, quasi-conformal theory has attracted increasing attention in the development of geometric mapping methods, in which the Beltrami coefficient has also been considered as a representation of the conformal distortion. However, the precise connection between these two concepts has not been analyzed. In this work, we study the connection between the two concepts and establish a series of theoretical results. In particular, we discover a simple relationship between the norm of the Beltrami coefficient of a mapping and the absolute angular distortion of triangle elements under the mapping. We can further estimate the maximal angular distortion using a simple formula in terms of the Beltrami coefficient. We verify the developed theoretical results and estimates using numerical experiments on multiple geometric mapping methods, covering conformal mapping, quasi-conformal mapping, and area-preserving mapping algorithms, for a variety of surface meshes in biology and engineering. Altogether, by establishing the theoretical foundation for the relationship between the angular distortion and Beltrami coefficient, our work opens up new avenues for the quantification and analysis of surface mapping algorithms.
### Title:
          Beam-aware Kernelized Contextual Bandits for User Association and Beamforming in mmWave Vehicular Networks
 - **Authors:** Xiaoyang He, Manabu Tsukada
 - **Subjects:** Subjects:
Information Theory (cs.IT); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Timely channel information is necessary for vehicles to determine both the serving base station (BS) and the beamforming vector, but frequent estimation of fast-fading mmWave channels incurs significant overhead. To address this challenge, we propose a Beam-aware Kernelized Contextual Upper Confidence Bound (BKC-UCB) algorithm that estimates instantaneous transmission rates without additional channel measurements by exploiting historical contexts such as vehicle location and velocity, together with past observed transmission rates. Specifically, BKC-UCB leverages kernel methods to capture the nonlinear relationship between context and transmission rate by mapping contexts into a reproducing kernel Hilbert space (RKHS), where linear learning becomes feasible. Rather than treating each beam as an independent arm, the beam index is embedded into the context, enabling BKC-UCB to exploit correlations among beams to accelerate convergence. Furthermore, an event-triggered information sharing mechanism is incorporated into BKC-UCB, enabling information exchange only when significant explorations are conducted to improve learning efficiency with limited communication overhead.
### Title:
          A Dynamic Bayesian and Machine Learning Framework for Quantitative Evaluation and Prediction of Operator Situation Awareness in Nuclear Power Plants
 - **Authors:** Shuai Chen, Huiqiao Jia, Tao Qing, Li Zhang, Xingyu Xiao
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Operator situation awareness is a pivotal yet elusive determinant of human reliability in complex nuclear control environments. Existing assessment methods, such as SAGAT and SART, remain static, retrospective, and detached from the evolving cognitive dynamics that drive operational risk. To overcome these limitations, this study introduces the dynamic Bayesian machine learning framework for situation awareness (DBML SA), a unified approach that fuses probabilistic reasoning and data driven intelligence to achieve quantitative, interpretable, and predictive situation awareness modeling. Leveraging 212 operational event reports (2007 to 2021), the framework reconstructs the causal temporal structure of 11 performance shaping factors across multiple cognitive layers. The Bayesian component enables time evolving inference of situation awareness reliability under uncertainty, while the neural component establishes a nonlinear predictive mapping from PSFs to SART scores, achieving a mean absolute percentage error of 13.8 % with statistical consistency to subjective evaluations (p > 0.05). Results highlight training quality and stress dynamics as primary drivers of situation awareness degradation. Overall, DBML SA transcends traditional questionnaire-based assessments by enabling real-time cognitive monitoring, sensitivity analysis, and early-warning prediction, paving the way toward intelligent human machine reliability management in next-generation digital main control rooms.
### Title:
          Computer-Orchestrated Design of Algorithms: From Join Specification to Implementation
 - **Authors:** Zeyuan Hu
 - **Subjects:** Subjects:
Databases (cs.DB); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Equipping query processing systems with provable theoretical guarantees has been a central focus at the intersection of database theory and systems in recent years. However, the divergence between theoretical abstractions and system assumptions creates a gap between an algorithm's high-level logical specification and its low-level physical implementation. Ensuring the correctness of this logical-to-physical translation is crucial for realizing theoretical optimality as practical performance gains. Existing database testing frameworks struggle to address this need because necessary algorithm-specific inputs such as join trees are absent from standard test case generation, and integrating complex algorithms into these frameworks imposes prohibitive engineering overhead. Fallback solutions, such as using macro-benchmark queries, are inherently too noisy for isolating intricate defects during this translation. In this experience paper, we present a retrospective analysis of $\mathsf{CODA}$, a computer-orchestrated testing framework utilized during the physical co-design of TreeTracker Join ($\mathsf{TTJ}$), a theoretically optimal yet practical join algorithm recently published in ACM TODS. By synthesizing minimal reproducible examples, $\mathsf{CODA}$ successfully isolates subtle translation defects, such as state mismanagement and mapping conflicts between join trees and bushy plans. We demonstrate that this logical-to-physical translation process is a bidirectional feedback loop: early structural testing not only hardened $\mathsf{TTJ}$'s physical implementation but also exposed a boundary condition that directly refined the formal precondition of $\mathsf{TTJ}$ itself. Finally, we detail how confronting these translation challenges drove the architectural evolution of $\mathsf{CODA}$ into a robust, structure-aware test generation pipeline for join-tree-dependent algorithms.
### Title:
          TrustFlow: Topic-Aware Vector Reputation Propagation for Multi-Agent Ecosystems
 - **Authors:** Volodymyr Seliuchenko
 - **Subjects:** Subjects:
Multiagent Systems (cs.MA); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce TrustFlow, a reputation propagation algorithm that assigns each software agent a multi-dimensional reputation vector rather than a scalar score. Reputation is propagated through an interaction graph via topic-gated transfer operators that modulate each edge by its content embedding, with convergence to a unique fixed point guaranteed by the contraction mapping theorem. We develop a family of Lipschitz-1 transfer operators and composable information-theoretic gates that achieve up to 98% multi-label Precision@5 on dense graphs and 78% on sparse ones. On a benchmark of 50 agents across 8 domains, TrustFlow resists sybil attacks, reputation laundering, and vote rings with at most 4 percentage-point precision impact. Unlike PageRank and Topic-Sensitive PageRank, TrustFlow produces vector reputation that is directly queryable by dot product in the same embedding space as user queries.
### Title:
          Accelerating Diffusion Decoders via Multi-Scale Sampling and One-Step Distillation
 - **Authors:** Chuhan Wang, Hao Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Image tokenization plays a central role in modern generative modeling by mapping visual inputs into compact representations that serve as an intermediate signal between pixels and generative models. Diffusion-based decoders have recently been adopted in image tokenization to reconstruct images from latent representations with high perceptual fidelity. In contrast to diffusion models used for downstream generation, these decoders are dedicated to faithful reconstruction rather than content generation. However, their iterative sampling process introduces significant latency, making them impractical for real-time or large-scale applications. In this work, we introduce a two-stage acceleration framework to address this inefficiency. First, we propose a multi-scale sampling strategy, where decoding begins at a coarse resolution and progressively refines the output by doubling the resolution at each stage, achieving a theoretical speedup of $\mathcal{O}(\log n)$ compared to standard full-resolution sampling. Second, we distill the diffusion decoder at each scale into a single-step denoising model, enabling fast and high-quality reconstructions in a single forward pass per scale. Together, these techniques yield an order-of-magnitude reduction in decoding time with little degradation in output quality. Our approach provides a practical pathway toward efficient yet expressive image tokenizers. We hope it serves as a foundation for future work in efficient visual tokenization and downstream generation.
### Title:
          Evolving Embodied Intelligence: Graph Neural Network--Driven Co-Design of Morphology and Control in Soft Robotics
 - **Authors:** Jianqiang Wang, Shuaiqun Pan, Alvaro Serra-Gomez, Xiaohan Wei, Yue Xie
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The intelligent behavior of robots does not emerge solely from control systems, but from the tight coupling between body and brain, a principle known as embodied intelligence. Designing soft robots that leverage this interaction remains a significant challenge, particularly when morphology and control require simultaneous optimization. A significant obstacle in this co-design process is that morphological evolution can disrupt learned control strategies, making it difficult to reuse or adapt existing knowledge. We address this by develop a Graph Neural Network-based approach for the co-design of morphology and controller. Each robot is represented as a graph, with a graph attention network (GAT) encoding node features and a pooled representation passed through a multilayer perceptron (MLP) head to produce actuator commands or value estimates. During evolution, inheritance follows a topology-consistent mapping: shared GAT layers are reused, MLP hidden layers are transferred intact, matched actuator outputs are copied, and unmatched ones are randomly initialized and fine-tuned. This morphology-aware policy class lets the controller adapt when the body mutates. On the benchmark, our GAT-based approach achieves higher final fitness and stronger adaptability to morphological variations compared to traditional MLP-only co-design methods. These results indicate that graph-structured policies provide a more effective interface between evolving morphologies and control for embodied intelligence.
### Title:
          BEAVER: A Training-Free Hierarchical Prompt Compression Method via Structure-Aware Page Selection
 - **Authors:** Zhengpei Hu, Kai Li, Dapeng Fu, Chang Zeng, Yue Li, Yuanhao Tang, Jianqiang Huang
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The exponential expansion of context windows in LLMs has unlocked capabilities for long-document understanding but introduced severe bottlenecks in inference latency and information utilization. Existing compression methods often suffer from high training costs or semantic fragmentation due to aggressive token pruning. In this paper, we propose BEAVER, a novel training-free framework that shifts compression from linear token removal to structure-aware hierarchical selection. BEAVER maximizes hardware parallelism by mapping variable-length contexts into dense page-level tensors via dual-path pooling, and preserves discourse integrity through a hybrid planner combining semantic and lexical dual-branch selection with sentence smoothing. Extensive evaluations on four long-context benchmarks demonstrate that BEAVER achieves comparable performance to state-of-the-art (SOTA) methods like LongLLMLingua. Notably, on the RULER benchmark, BEAVER maintains high fidelity in multi-needle retrieval where baselines deteriorate. Regarding efficiency, BEAVER reduces latency by 26.4x on 128k contexts, offering a scalable solution for high-throughput applications. Our code is available at this https URL.
### Title:
          AIGQ: An End-to-End Hybrid Generative Architecture for E-commerce Query Recommendation
 - **Authors:** Jingcao Xu, Jianyun Zou, Renkai Yang, Zili Geng, Qiang Liu, Haihong Tang
 - **Subjects:** Subjects:
Information Retrieval (cs.IR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pre-search query recommendation, widely known as HintQ on Taobao's homepage, plays a vital role in intent capture and demand discovery, yet traditional methods suffer from shallow semantics, poor cold-start performance and low serendipity due to reliance on ID-based matching and co-click heuristics. To overcome these challenges, we propose AIGQ (AI-Generated Query architecture), the first end-to-end generative framework for HintQ scenario. AIGQ is built upon three core innovations spanning training paradigm, policy optimization and deployment architecture. First, we propose Interest-Aware List Supervised Fine-Tuning (IL-SFT), a list-level supervised learning approach that constructs training samples through session-aware behavior aggregation and interest-guided re-ranking strategy to faithfully model nuanced user intent. Accordingly, we design Interest-aware List Group Relative Policy Optimization (IL-GRPO), a novel policy gradient algorithm with a dual-component reward mechanism that jointly optimizes individual query relevance and global list properties, enhanced by a model-based reward from the online click-through rate (CTR) ranking model. To deploy under strict real-time and low-latency requirements, we further develop a hybrid offline-online architecture comprising AIGQ-Direct for nearline personalized user-to-query generation and AIGQ-Think, a reasoning-enhanced variant that produces trigger-to-query mappings to enrich interest diversity. Extensive offline evaluations and large-scale online A/B experiments on Taobao demonstrate that AIGQ consistently delivers substantial improvements in key business metrics across platform effectiveness and user engagement.
### Title:
          FedRG: Unleashing the Representation Geometry for Federated Learning with Noisy Clients
 - **Authors:** Tian Wen, Zhiqin Yang, Yonggang Zhang, Xuefeng Jiang, Hao Peng, Yuwei Wang, Bo Han
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Federated learning (FL) suffers from performance degradation due to the inevitable presence of noisy annotations in distributed scenarios. Existing approaches have advanced in distinguishing noisy samples from the dataset for label correction by leveraging loss values. However, noisy samples recognition relying on scalar loss lacks reliability for FL under heterogeneous scenarios. In this paper, we rethink this paradigm from a representation perspective and propose \method~(\textbf{Fed}erated under \textbf{R}epresentation \textbf{G}emometry), which follows \textbf{the principle of ``representation geometry priority''} to recognize noisy labels. Firstly, \method~creates label-agnostic spherical representations by using self-supervision. It then iteratively fits a spherical von Mises-Fisher (vMF) mixture model to this geometry using previously identified clean samples to capture semantic clusters. This geometric evidence is integrated with a semantic-label soft mapping mechanism to derive a distribution divergence between the label-free and annotated label-conditioned feature space, which robustly identifies noisy samples and updates the vMF mixture model with the newly separated clean dataset. Lastly, we employ an additional personalized noise absorption matrix on noisy labels to achieve robust optimization. Extensive experimental results demonstrate that \method~significantly outperforms state-of-the-art methods for FL with data heterogeneity under diverse noisy clients scenarios.
### Title:
          Surrogate Modeling with Low-Rank Function Representation for Electromagnetic Simulation
 - **Authors:** Mingze Sun, Liang Li, Xile Zhao, Zheng Tan, Yulu Hu, Xing Li, Bin Li
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE); Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-fidelity electromagnetic (EM) simulations are indispensable for the design of microwave and wave devices, yet repeated full-wave evaluations over high-dimensional design spaces are often computationally prohibitive. While neural surrogates can amortize this cost, learning high-dimensional EM response mappings remains difficult under limited simulation budgets due to strong and heterogeneous parameter couplings. In this work, we introduce low-rank tensor function representations as a principled surrogate modeling paradigm for EM problems and provide a systematic study of representative low-rank formats, including Tucker-style low-rank tensor function representation (LRTFR) as well as neural functional tensor-train (TT) and tensor-ring (TR) baselines. Building on these insights, we propose a pairwise low-rank tensor network (PLRNet) that uses learnable pairwise interaction factors over compact coordinate-wise embeddings. Experiments on representative EM surrogate tasks demonstrate that the proposed framework achieves a more favorable overall trade-off between accuracy, robustness, and parameter efficiency, with stable optimization in high-dimensional regimes.
### Title:
          ReManNet: A Riemannian Manifold Network for Monocular 3D Lane Detection
 - **Authors:** Chengzhi Hong, Bijun Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular 3D lane detection remains challenging due to depth ambiguity and weak geometric constraints. Mainstream methods rely on depth guidance, BEV projection, and anchor- or curve-based heads with simplified physical assumptions, remapping high-dimensional image features while only weakly encoding road geometry. Lacking an invariant geometric-topological coupling between lanes and the underlying road surface, 2D-to-3D lifting is ill-posed and brittle, often degenerating into concavities, bulges, and twists. To address this, we propose the Road-Manifold Assumption: the road is a smooth 2D manifold in $\mathbb{R}^3$, lanes are embedded 1D submanifolds, and sampled lane points are dense observations, thereby coupling metric and topology across surfaces, curves, and point sets. Building on this, we propose ReManNet, which first produces initial lane predictions with an image backbone and detection heads, then encodes geometry as Riemannian Gaussian descriptors on the symmetric positive-definite (SPD) manifold, and fuses these descriptors with visual features through a lightweight gate to maintain coherent 3D reasoning. We also propose the 3D Tunnel Lane IoU (3D-TLIoU) loss, a joint point-curve objective that computes slice-wise overlap of tubular neighborhoods along each lane to improve shape-level alignment. Extensive experiments on standard benchmarks demonstrate that ReManNet achieves state-of-the-art (SOTA) or competitive results. On OpenLane, it improves F1 by +8.2% over the baseline and by +1.8% over the previous best, with scenario-level gains of up to +6.6%. The code will be publicly available at this https URL.
### Title:
          Real-Time Structural Detection for Indoor Navigation from 3D LiDAR Using Bird's-Eye-View Images
 - **Authors:** Guanliang Li, Pedro Espinosa Angulo, David Perez Saura, Santiago Tapia Fernandez
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Efficient structural perception is essential for mapping and autonomous navigation on resource-constrained robots. Existing 3D methods are computationally prohibitive, while traditional 2D geometric approaches lack robustness. This paper presents a lightweight, real-time framework that projects 3D LiDAR data into 2D Bird's-Eye-View (BEV) images to enable efficient detection of structural elements relevant to mapping and navigation. Within this representation, we systematically evaluate several feature extraction strategies, including classical geometric techniques (Hough Transform, RANSAC, and LSD) and a deep learning detector based on YOLO-OBB. The resulting detections are integrated through a spatiotemporal fusion module that improves stability and robustness across consecutive frames. Experiments conducted on a standard mobile robotic platform highlight clear performance trade-offs. Classical methods such as Hough and LSD provide fast responses but exhibit strong sensitivity to noise, with LSD producing excessive segment fragmentation that leads to system congestion. RANSAC offers improved robustness but fails to meet real-time constraints. In contrast, the YOLO-OBB-based approach achieves the best balance between robustness and computational efficiency, maintaining an end-to-end latency (satisfying 10 Hz operation) while effectively filtering cluttered observations in a low-power single-board computer (SBC) without using GPU acceleration. The main contribution of this work is a computationally efficient BEV-based perception pipeline enabling reliable real-time structural detection from 3D LiDAR on resource-constrained robotic platforms that cannot rely on GPU-intensive processing.
### Title:
          Failure Modes for Deep Learning-Based Online Mapping: How to Measure and Address Them
 - **Authors:** Michael Hubbertz, Qi Han, Tobias Meisen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning-based online mapping has emerged as a cornerstone of autonomous driving, yet these models frequently fail to generalize beyond familiar environments. We propose a framework to identify and measure the underlying failure modes by disentangling two effects: Memorization of input features and overfitting to known map geometries. We propose measures based on evaluation subsets that control for geographical proximity and geometric similarity between training and validation scenes. We introduce Fréchet distance-based reconstruction statistics that capture per-element shape fidelity without threshold tuning, and define complementary failure-mode scores: a localization overfitting score quantifying the performance drop when geographic cues disappear, and a map geometry overfitting score measuring degradation as scenes become geometrically novel. Beyond models, we analyze dataset biases and contribute map geometry-aware diagnostics: A minimum-spanning-tree (MST) diversity measure for training sets and a symmetric coverage measure to quantify geometric similarity between splits. Leveraging these, we formulate an MST-based sparsification strategy that reduces redundancy and improves balancing and performance while shrinking training size. Experiments on nuScenes and Argoverse 2 across multiple state-of-the-art models yield more trustworthy assessment of generalization and show that map geometry-diverse and balanced training sets lead to improved performance. Our results motivate failure-mode-aware protocols and map geometry-centric dataset design for deployable online mapping.
### Title:
          Uncertainty Matters: Structured Probabilistic Online Mapping for Motion Prediction in Autonomous Driving
 - **Authors:** Pritom Gogoi, Faris Janjoš, Bin Yang, Andreas Look
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Online map generation and trajectory prediction are critical components of the autonomous driving perception-prediction-planning pipeline. While modern vectorized mapping models achieve high geometric accuracy, they typically treat map estimation as a deterministic task, discarding structural uncertainty. Existing probabilistic approaches often rely on diagonal covariance matrices, which assume independence between points and fail to capture the strong spatial correlations inherent in road geometry. To address this, we propose a structured probabilistic formulation for online map generation. Our method explicitly models intra-element dependencies by predicting a dense covariance matrix, parameterized via a Low-Rank plus Diagonal (LRPD) covariance decomposition. This formulation represents uncertainty as a combination of a low-rank component, which captures global spatial structure, and a diagonal component representing independent local noise, thereby capturing geometric correlations without the prohibitive computational cost of full covariance matrices. Evaluations on the nuScenes dataset demonstrate that our uncertainty-aware framework yields consistent improvements in online map generation quality compared to deterministic baselines. Furthermore, our approach establishes new state-of-the-art performance for map-based motion prediction, highlighting the critical role of uncertainty in planning tasks. Code is published under link-available-soon.
### Title:
          An Agentic Multi-Agent Architecture for Cybersecurity Risk Management
 - **Authors:** Ravish Gupta (1), Saket Kumar (2), Shreeya Sharma (3), Maulik Dang (4), Abhishek Aggarwal (4) ((1) BigCommerce, (2) University at Buffalo, The State University of New York, Buffalo, NY, USA, (3) Microsoft, (4) Amazon)
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Artificial Intelligence (cs.AI); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Getting a real cybersecurity risk assessment for a small organization is expensive -- a NIST CSF-aligned engagement runs $15,000 on the low end, takes weeks, and depends on practitioners who are genuinely scarce. Most small companies skip it entirely. We built a six-agent AI system where each agent handles one analytical stage: profiling the organization, mapping assets, analyzing threats, evaluating controls, scoring risks, and generating recommendations. Agents share a persistent context that grows as the assessment proceeds, so later agents build on what earlier ones concluded -- the mechanism that distinguishes this from standard sequential agent pipelines. We tested it on a 15-person HIPAA-covered healthcare company and compared outputs to independent assessments by three CISSP practitioners -- the system agreed with them 85% of the time on severity classifications, covered 92% of identified risks, and finished in under 15 minutes. We then ran 30 repeated single-agent assessments across five synthetic but sector-realistic organizational profiles in healthcare, fintech, manufacturing, retail, and SaaS, comparing a general-purpose Mistral-7B against a domain fine-tuned model. Both completed every run. The fine-tuned model flagged threats the baseline could not see at all: PHI exposure in healthcare, OT/IIoT vulnerabilities in manufacturing, platform-specific risks in retail. The full multi-agent pipeline, however, failed every one of 30 attempts on a Tesla T4 with its 4,096-token default context window -- context capacity, not model quality, turned out to be the binding constraint.
### Title:
          TinyML Enhances CubeSat Mission Capabilities
 - **Authors:** Luigi Capogrosso, Michele Magno
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Earth observation (EO) missions traditionally rely on transmitting raw or minimally processed imagery from satellites to ground stations for computationally intensive analysis. This paradigm is infeasible for CubeSat systems due to stringent constraints on the onboard embedded processors, energy availability, and communication bandwidth. To overcome these limitations, the paper presents a TinyML-based Convolutional Neural Networks (ConvNets) model optimization and deployment pipeline for onboard image classification, enabling accurate, energy-efficient, and hardware-aware inference under CubeSat-class constraints. Our pipeline integrates structured iterative pruning, post-training INT8 quantization, and hardware-aware operator mapping to compress models and align them with the heterogeneous compute architecture of the STM32N6 microcontroller from STMicroelectronics. This Microcontroller Unit (MCU) integrates a novel Arm Cortex-M55 core and a Neural-ART Neural Processing Unit (NPU), providing a realistic proxy for CubeSat onboard computers. The paper evaluates the proposed approach on three EO benchmark datasets (i.e., EuroSAT, RS_C11, MEDIC) and four models (i.e., SqueezeNet, MobileNetV3, EfficientNet, MCUNetV1). We demonstrate an average reduction in RAM usage of 89.55% and Flash memory of 70.09% for the optimized models, significantly decreasing downlink bandwidth requirements while maintaining task-acceptable accuracy (with a drop ranging from 0.4 to 8.6 percentage points compared to the Float32 baseline). The energy consumption per inference ranges from 0.68 mJ to 6.45 mJ, with latency spanning from 3.22 ms to 30.38 ms. These results fully satisfy the stringent energy budgets and real-time constraints required for efficient onboard EO processing.
## Keyword: localization
### Title:
          Gastric-X: A Multimodal Multi-Phase Benchmark Dataset for Advancing Vision-Language Models in Gastric Cancer Analysis
 - **Authors:** Sheng Lu, Hao Chen, Rui Yin, Juyan Ba, Yu Zhang, Yuanzhe Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent vision-language models (VLMs) have shown strong generalization and multimodal reasoning abilities in natural domains. However, their application to medical diagnosis remains limited by the lack of comprehensive and structured datasets that capture real clinical workflows. To advance the development of VLMs for clinical applications, particularly in gastric cancer, we introduce Gastric-X, a large-scale multimodal benchmark for gastric cancer analysis providing 1.7K cases. Each case in Gastric-X includes paired resting and dynamic CT scans, endoscopic image, a set of structured biochemical indicators, expert-authored diagnostic notes, and bounding box annotations of tumor regions, reflecting realistic clinical conditions. We systematically examine the capability of recent VLMs on five core tasks: Visual Question Answering (VQA), report generation, cross-modal retrieval, disease classification, and lesion localization. These tasks simulate critical stages of clinical workflow, from visual understanding and reasoning to multimodal decision support. Through this evaluation, we aim not only to assess model performance but also to probe the nature of VLM understanding: Can current VLMs meaningfully correlate biochemical signals with spatial tumor features and textual reports? We envision Gastric-X as a step toward aligning machine intelligence with the cognitive and evidential reasoning processes of physicians, and as a resource to inspire the development of next-generation medical VLMs.
### Title:
          MoCA3D: Monocular 3D Bounding Box Prediction in the Image Plane
 - **Authors:** Changwoo Jeon, Rishi Upadhyay, Achuta Kadambi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular 3D object understanding has largely been cast as a 2D RoI-to-3D box lifting problem. However, emerging downstream applications require image-plane geometry (e.g., projected 3D box corners) which cannot be easily obtained without known intrinsics, a problem for object detection in the wild. We introduce MoCA3D, a Monocular, Class-Agnostic 3D model that predicts projected 3D bounding box corners and per-corner depths without requiring camera intrinsics at inference time. MoCA3D formulates pixel-space localization and depth assignment as dense prediction via corner heatmaps and depth maps. To evaluate image-plane geometric fidelity, we propose Pixel-Aligned Geometry (PAG), which directly measures image-plane corner and depth consistency. Extensive experiments demonstrate that MoCA3D achieves state-of-the-art performance, improving image-plane corner PAG by 22.8% while remaining comparable on 3D IoU, using up to 57 times fewer trainable parameters. Finally, we apply MoCA3D to downstream tasks which were previously impractical under unknown intrinsics, highlighting its utility beyond standard baseline models.
### Title:
          ARMOR: Adaptive Resilience Against Model Poisoning Attacks in Continual Federated Learning for Mobile Indoor Localization
 - **Authors:** Danish Gufran, Akhil Singampalli, Sudeep Pasricha
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Indoor localization has become increasingly essential for applications ranging from asset tracking to delivering personalized services. Federated learning (FL) offers a privacy-preserving approach by training a centralized global model (GM) using distributed data from mobile devices without sharing raw data. However, real-world deployments require a continual federated learning (CFL) setting, where the GM receives continual updates under device heterogeneity and evolving indoor environments. In such dynamic conditions, erroneous or biased updates can cause the GM to deviate from its expected learning trajectory, gradually degrading internal GM representations and GM localization performance. This vulnerability is further exacerbated by adversarial model poisoning attacks. To address this challenge, we propose ARMOR, a novel CFL-based framework that monitors and safeguards the GM during continual updates. ARMOR introduces a novel state-space model (SSM) that learns the historical evolution of GM weight tensors and predicts the expected next state of weight tensors of the GM. By comparing incoming local updates with this SSM projection, ARMOR detects deviations and selectively mitigates corrupted updates before local updates are aggregated with the GM. This mechanism enables robust adaptation to temporal environmental dynamics and mitigate the effects of model poisoning attacks while preventing GM corruption. Experimental evaluations in real-world conditions indicate that ARMOR achieves notable improvements, with up to 8.0x reduction in mean error and 4.97x reduction in worst-case error compared to state-of-the-art indoor localization frameworks, demonstrating strong resilience against model corruption tested using real-world data and mobile devices.
### Title:
          FB-CLIP: Fine-Grained Zero-Shot Anomaly Detection with Foreground-Background Disentanglement
 - **Authors:** Ming Hu, Yongsheng Huo, Mingyu Dou, Jianfu Yin, Peng Zhao, Yao Wang, Cong Hu, Bingliang Hu, Quan Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fine-grained anomaly detection is crucial in industrial and medical applications, but labeled anomalies are often scarce, making zero-shot detection challenging. While vision-language models like CLIP offer promising solutions, they struggle with foreground-background feature entanglement and coarse textual semantics. We propose FB-CLIP, a framework that enhances anomaly localization via multi-strategy textual representations and foreground-background separation. In the textual modality, it combines End-of-Text features, global-pooled representations, and attention-weighted token features for richer semantic cues. In the visual modality, multi-view soft separation along identity, semantic, and spatial dimensions, together with background suppression, reduces interference and improves discriminability. Semantic Consistency Regularization (SCR) aligns image features with normal and abnormal textual prototypes, suppressing uncertain matches and enlarging semantic gaps. Experiments show that FB-CLIP effectively distinguishes anomalies from complex backgrounds, achieving accurate fine-grained anomaly detection and localization under zero-shot settings.
### Title:
          LoD-Loc v3: Generalized Aerial Localization in Dense Cities using Instance Silhouette Alignment
 - **Authors:** Shuaibang Peng, Juelin Zhu, Xia Li, Kun Yang, Maojun Zhang, Yu Liu, Shen Yan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present LoD-Loc v3, a novel method for generalized aerial visual localization in dense urban environments. While prior work LoD-Loc v2 achieves localization through semantic building silhouette alignment with low-detail city models, it suffers from two key limitations: poor cross-scene generalization and frequent failure in dense building scenes. Our method addresses these challenges through two key innovations. First, we develop a new synthetic data generation pipeline that produces InsLoD-Loc - the largest instance segmentation dataset for aerial imagery to date, comprising 100k images with precise instance building annotations. This enables trained models to exhibit remarkable zero-shot generalization capability. Second, we reformulate the localization paradigm by shifting from semantic to instance silhouette alignment, which significantly reduces pose estimation ambiguity in dense scenes. Extensive experiments demonstrate that LoD-Loc v3 outperforms existing state-of-the-art (SOTA) baselines, achieving superior performance in both cross-scene and dense urban scenarios with a large margin. The project is available at this https URL.
### Title:
          IUP-Pose: Decoupled Iterative Uncertainty Propagation for Real-time Relative Pose Regression via Implicit Dense Alignment v1
 - **Authors:** Jun Wang, Xiaoyan Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Relative pose estimation is fundamental for SLAM, visual localization, and 3D reconstruction. Existing Relative Pose Regression (RPR) methods face a key trade-off: feature-matching pipelines achieve high accuracy but block gradient flow via non-differentiable RANSAC, while ViT-based regressors are end-to-end trainable but prohibitively expensive for real-time deployment. We identify the core bottlenecks as the coupling between rotation and translation estimation and insufficient cross-view feature alignment. We propose IUP-Pose, a geometry-driven decoupled iterative framework with implicit dense alignment. A lightweight Multi-Head Bi-Cross Attention (MHBC) module aligns cross-view features without explicit matching supervision. The aligned features are processed by a decoupled rotation-translation pipeline: two shared-parameter rotation stages iteratively refine rotation with uncertainty, and feature maps are realigned via rotational homography H_inf before translation prediction. IUP-Pose achieves 73.3% AUC@20deg on MegaDepth1500 with full end-to-end differentiability, 70 FPS throughput, and only 37M parameters, demonstrating a favorable accuracy-efficiency trade-off for real-time edge deployment.
### Title:
          Demographic-Aware Self-Supervised Anomaly Detection Pretraining for Equitable Rare Cardiac Diagnosis
 - **Authors:** Chaoqin Huang, Zi Zeng, Aofan Jiang, Yuchen Xu, Qing Cao, Kang Chen, Chenfei Chi, Yanfeng Wang, Ya Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rare cardiac anomalies are difficult to detect from electrocardiograms (ECGs) due to their long-tailed distribution with extremely limited case counts and demographic disparities in diagnostic performance. These limitations contribute to delayed recognition and uneven quality of care, creating an urgent need for a generalizable framework that enhances sensitivity while ensuring equity across diverse populations. In this study, we developed an AI-assisted two-stage ECG framework integrating self-supervised anomaly detection with demographic-aware representation learning. The first stage performs self-supervised anomaly detection pretraining by reconstructing masked global and local ECG signals, modeling signal trends, and predicting patient attributes to learn robust ECG representations without diagnostic labels. The pretrained model is then fine-tuned for multi-label ECG classification using asymmetric loss to better handle long-tail cardiac abnormalities, and additionally produces anomaly score maps for localization, with CPU-based optimization enabling practical deployment. Evaluated on a longitudinal cohort of over one million clinical ECGs, our method achieves an AUROC of 94.7% for rare anomalies and reduces the common-rare performance gap by 73%, while maintaining consistent diagnostic accuracy across age and sex groups. In conclusion, the proposed equity-aware AI framework demonstrates strong clinical utility, interpretable anomaly localization, and scalable performance across multiple cohorts, highlighting its potential to mitigate diagnostic disparities and advance equitable anomaly detection in biomedical signals and digital health. Source code is available at this https URL.
### Title:
          Failure Modes for Deep Learning-Based Online Mapping: How to Measure and Address Them
 - **Authors:** Michael Hubbertz, Qi Han, Tobias Meisen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning-based online mapping has emerged as a cornerstone of autonomous driving, yet these models frequently fail to generalize beyond familiar environments. We propose a framework to identify and measure the underlying failure modes by disentangling two effects: Memorization of input features and overfitting to known map geometries. We propose measures based on evaluation subsets that control for geographical proximity and geometric similarity between training and validation scenes. We introduce Fréchet distance-based reconstruction statistics that capture per-element shape fidelity without threshold tuning, and define complementary failure-mode scores: a localization overfitting score quantifying the performance drop when geographic cues disappear, and a map geometry overfitting score measuring degradation as scenes become geometrically novel. Beyond models, we analyze dataset biases and contribute map geometry-aware diagnostics: A minimum-spanning-tree (MST) diversity measure for training sets and a symmetric coverage measure to quantify geometric similarity between splits. Leveraging these, we formulate an MST-based sparsification strategy that reduces redundancy and improves balancing and performance while shrinking training size. Experiments on nuScenes and Argoverse 2 across multiple state-of-the-art models yield more trustworthy assessment of generalization and show that map geometry-diverse and balanced training sets lead to improved performance. Our results motivate failure-mode-aware protocols and map geometry-centric dataset design for deployable online mapping.
### Title:
          Can Large Multimodal Models Inspect Buildings? A Hierarchical Benchmark for Structural Pathology Reasoning
 - **Authors:** Hui Zhong, Yichun Gao, Luyan Liu, Hai Yang, Wang Wang, Haowei Zhang, Xinhu Zheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated building facade inspection is a critical component of urban resilience and smart city maintenance. Traditionally, this field has relied on specialized discriminative models (e.g., YOLO, Mask R-CNN) that excel at pixel-level localization but are constrained to passive perception and worse generization without the visual understandng to interpret structural topology. Large Multimodal Models (LMMs) promise a paradigm shift toward active reasoning, yet their application in such high-stakes engineering domains lacks rigorous evaluation standards. To bridge this gap, we introduce a human-in-the-loop semi-automated annotation framework, leveraging expert-proposal verification to unify 12 fragmented datasets into a standardized, hierarchical ontology. Building on this foundation, we present \textit{DefectBench}, the first multi-dimensional benchmark designed to interrogate LMMs beyond basic semantic recognition. \textit{DefectBench} evaluates 18 state-of-the-art (SOTA) LMMs across three escalating cognitive dimensions: Semantic Perception, Spatial Localization, and Generative Geometry Segmentation. Extensive experiments reveal that while current LMMs demonstrate exceptional topological awareness and semantic understanding (effectively diagnosing "what" and "how"), they exhibit significant deficiencies in metric localization precision ("where"). Crucially, however, we validate the viability of zero-shot generative segmentation, showing that general-purpose foundation models can rival specialized supervised networks without domain-specific training. This work provides both a rigorous benchmarking standard and a high-quality open-source database, establishing a new baseline for the advancement of autonomous AI agents in civil engineering.
### Title:
          From Masks to Pixels and Meaning: A New Taxonomy, Benchmark, and Metrics for VLM Image Tampering
 - **Authors:** Xinyi Shang, Yi Tang, Jiacheng Cui, Ahmed Elhagry, Salwa K. Al Khatib, Sondos Mahmoud Bsharat, Jiacheng Liu, Xiaohan Zhao, Jing-Hao Xue, Hao Li, Salman Khan, Zhiqiang Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing tampering detection benchmarks largely rely on object masks, which severely misalign with the true edit signal: many pixels inside a mask are untouched or only trivially modified, while subtle yet consequential edits outside the mask are treated as natural. We reformulate VLM image tampering from coarse region labels to a pixel-grounded, meaning and language-aware task. First, we introduce a taxonomy spanning edit primitives (replace/remove/splice/inpaint/attribute/colorization, etc.) and their semantic class of tampered object, linking low-level changes to high-level understanding. Second, we release a new benchmark with per-pixel tamper maps and paired category supervision to evaluate detection and classification within a unified protocol. Third, we propose a training framework and evaluation metrics that quantify pixel-level correctness with localization to assess confidence or prediction on true edit intensity, and further measure tamper meaning understanding via semantics-aware classification and natural language descriptions for the predicted regions. We also re-evaluate the existing strong segmentation/localization baselines on recent strong tamper detectors and reveal substantial over- and under-scoring using mask-only metrics, and expose failure modes on micro-edits and off-mask changes. Our framework advances the field from masks to pixels, meanings and language descriptions, establishing a rigorous standard for tamper localization, semantic classification and description. Code and benchmark data are available at this https URL.
## Keyword: transformer
### Title:
          HATL: Hierarchical Adaptive-Transfer Learning Framework for Sign Language Machine Translation
 - **Authors:** Nada Shahin, Leila Ismail
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Computers and Society (cs.CY); Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sign Language Machine Translation (SLMT) aims to bridge communication between Deaf and hearing individuals. However, its progress is constrained by scarce datasets, limited signer diversity, and large domain gaps between sign motion patterns and pretrained representations. Existing transfer learning approaches in SLMT are static and often lead to overfitting. These challenges call for the development of an adaptive framework that preserves pretrained structure while remaining robust across linguistic and signing variations. To fill this void, we propose a Hierarchical Adaptive Transfer Learning (HATL) framework, where pretrained layers are progressively and dynamically unfrozen based on training performance behavior. HATL combines dynamic unfreezing, layer-wise learning rate decay, and stability mechanisms to preserve generic representations while adapting to sign characteristics. We evaluate HATL on Sign2Text and Sign2Gloss2Text translation tasks using a pretrained ST-GCN++ backbone for feature extraction and the Transformer and an adaptive transformer (ADAT)for translation. To ensure robust multilingual generalization, we evaluate the proposed approach across three datasets: RWTH-PHOENIXWeather-2014 (PHOENIX14T), Isharah, and MedASL. Experimental results show that HATL consistently outperforms traditional transfer learning approaches across tasks and models, with ADAT achieving BLEU-4 improvements of 15.0% on PHOENIX14T and Isharah and 37.6% on MedASL.
### Title:
          Significance-Gain Pair Encoding for LLMs: A Statistical Alternative to Frequency-Based Subword Merging
 - **Authors:** Azam Nouri
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Subword tokenization is a key design choice for modern language models, including large language models (LLMs), with byte- and character-level BPE serving as a widely used baseline. Standard BPE selects merges by raw pair frequency, which favors compression but can conflate true adjacency cohesion with pairs that are frequent due to high marginal counts. This paper introduces Significance-Gain BPE, a drop-in alternative merge criterion that measures cohesion via a z-statistic under an independence null model and combines it with an explicit compression-aware gain term. Significance-Gain BPE is evaluated on WikiText-103 (raw) character slices using a small causal Transformer language model, reporting both token-dependent perplexity and the tokenizer-invariant metric bits per character (BPC). At a representative operating point, Significance-Gain BPE reduces validation and test perplexity by 13% and 12%, respectively, and improves validation and test BPC by about 0.9 to 1.0%. A vocabulary-size sweep further shows lower BPC in most closest-compression comparisons, suggesting that statistically grounded merge selection can improve predictive efficiency per unit of raw text across a range of compression regimes.
### Title:
          From Tokens To Agents: A Researcher's Guide To Understanding Large Language Models
 - **Authors:** Daniele Barolo
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Researchers face a critical choice: how to use -- or not use -- large language models in their work. Using them well requires understanding the mechanisms that shape what LLMs can and cannot do. This chapter makes LLMs comprehensible without requiring technical expertise, breaking down six essential components: pre-training data, tokenization and embeddings, transformer architecture, probabilistic generation, alignment, and agentic capabilities. Each component is analyzed through both technical foundations and research implications, identifying specific affordances and limitations. Rather than prescriptive guidance, the chapter develops a framework for reasoning critically about whether and how LLMs fit specific research needs, finally illustrated through an extended case study on simulating social media dynamics with LLM-based agents.
### Title:
          Transformers are Stateless Differentiable Neural Computers
 - **Authors:** Bo Tang, Weiwei Xie
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Differentiable Neural Computers (DNCs) were introduced as recurrent architectures equipped with an addressable external memory supporting differentiable read and write operations. Transformers, in contrast, are nominally feedforward architectures based on multi-head self-attention. In this work we give a formal derivation showing that a causal Transformer layer is exactly a stateless Differentiable Neural Computer (sDNC) where (1) the controller has no recurrent internal state, (2) the external memory is a write-once matrix of value vectors, (3) content-based addressing via keys implements attention, and (4) multi-head attention corresponds to multiple parallel read heads. We further extend this equivalence to cross-attention, showing that encoder-decoder Transformers are precisely sDNCs with distinct read-from and write-to memories. Our results provide a unified memory-centric interpretation of Transformers and contribute to the ongoing effort to place modern large language models in a principled computational framework.
### Title:
          HypeLoRA: Hyper-Network-Generated LoRA Adapters for Calibrated Language Model Fine-Tuning
 - **Authors:** Bartosz Trojan, Filip Gębala
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern Transformer-based models frequently suffer from miscalibration, producing overconfident predictions that do not reflect true empirical frequencies. This work investigates the calibration dynamics of LoRA: Low-Rank Adaptation and a novel hyper-network-based adaptation framework as parameter-efficient alternatives to full fine-tuning for RoBERTa. Evaluating across the GLUE benchmark, we demonstrate that LoRA-based adaptation consistently achieves calibration parity with (and in specific tasks exceeds) full fine-tuning, while maintaining significantly higher parameter efficiency. We further explore a dynamic approach where a shared hyper-network generates LoRA factors (A and B matrices) to induce structural coupling across layers. This approach produced results similar to standard LoRA fine-tuning, even achieving better MCC on CoLA dataset. Our study also reveal a critical trade-off: constraining the adaptation space (e.g., freezing matrices A) acts as a powerful regularizer that enhances Expected Calibration Error (ECE), but necessitates a carefully balanced sacrifice in downstream task accuracy. To support future research, we provide a unified and reproducible implementation of contemporary calibration metrics, including ECE, MCE, and ACE. Our findings clarify the relationship between parameter efficiency and probabilistic reliability, positioning structured low-rank updates as a viable foundation for uncertainty-aware Transformer architectures. Code available at: this https URL
### Title:
          Neural Dynamics Self-Attention for Spiking Transformers
 - **Authors:** Dehao Zhang, Fukai Guo, Shuai Wang, Jingya Wang, Jieyuan Zhang, Yimeng Shan, Malu Zhang, Yang Yang, Haizhou Li
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Integrating Spiking Neural Networks (SNNs) with Transformer architectures offers a promising pathway to balance energy efficiency and performance, particularly for edge vision applications. However, existing Spiking Transformers face two critical challenges: (i) a substantial performance gap compared to their Artificial Neural Networks (ANNs) counterparts and (ii) high memory overhead during inference. Through theoretical analysis, we attribute both limitations to the Spiking Self-Attention (SSA) mechanism: the lack of locality bias and the need to store large attention matrices. Inspired by the localized receptive fields (LRF) and membrane-potential dynamics of biological visual neurons, we propose LRF-Dyn, which uses spiking neurons with localized receptive fields to compute attention while reducing memory requirements. Specifically, we introduce a LRF method into SSA to assign higher weights to neighboring regions, strengthening local modeling and improving performance. Building on this, we approximate the resulting attention computation via charge-fire-reset dynamics, eliminating explicit attention-matrix storage and reducing inference-time memory. Extensive experiments on visual tasks confirm that our method reduces memory overhead while delivering significant performance improvements. These results establish it as a key unit for achieving energy-efficient Spiking Transformers.
### Title:
          Exploring Subnetwork Interactions in Heterogeneous Brain Network via Prior-Informed Graph Learning
 - **Authors:** Siyu Liu, Guangqi Wen, Peng Cao, Jinzhu Yang, Xiaoli Liu, Fei Wang, Osmar R. Zaiane
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modeling the complex interactions among functional subnetworks is crucial for the diagnosis of mental disorders and the identification of functional pathways. However, learning the interactions of the underlying subnetworks remains a significant challenge for existing Transformer-based methods due to the limited number of training samples. To address these challenges, we propose KD-Brain, a Prior-Informed Graph Learning framework for explicitly encoding prior knowledge to guide the learning process. Specifically, we design a Semantic-Conditioned Interaction mechanism that injects semantic priors into the attention query, explicitly navigating the subnetwork interactions based on their functional identities. Furthermore, we introduce a Pathology-Consistent Constraint, which regularizes the model optimization by aligning the learned interaction distributions with clinical priors. Additionally, KD-Brain leads to state-of-the-art performance on a wide range of disorder diagnosis tasks and identifies interpretable biomarkers consistent with psychiatric pathophysiology. Our code is available at this https URL.
### Title:
          DAPA: Distribution Aware Piecewise Activation Functions for On-Device Transformer Inference and Training
 - **Authors:** Maoyang Xiang, Bo Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Non-linear activation functions play a pivotal role in on-device inference and training, as they not only consume substantial hardware resources but also impose a significant impact on system performance and energy efficiency. In this work, we propose Distribution-Aware Piecewise Activation (DAPA), a differentiable and hardware-friendly activation function for Transformer architectures by exploiting the distribution of pre-activation data. DAPA employs a non-uniform piecewise approximation that allocates finer segments to high-probability regions of the distribution, improving generalizability over prior piecewise linear methods. The resulting approximation is further quantized using Distribution-Weighted Mean Square Error to reduce latency and resource utilization for hardware deployment. Our HLS implementation demonstrates that DAPA speeds up GELU computation by 16$\times$ and decreases DSP utilization by 16$\times$ while maintaining comparable or better performance across vision Transformers and GPT-2 models.
### Title:
          Anatomical Heterogeneity in Transformer Language Models
 - **Authors:** Tomasz Wietrzykowski
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current transformer language models are trained with uniform computational budgets across all layers, implicitly assuming layer homogeneity. We challenge this assumption through empirical analysis of SmolLM2-135M, a 30-layer, 135M-parameter causal language model, using five diagnostic metrics: weight predictability (R2), ablation degradation, recovery speed, weight manipulation robustness, and structural analysis. We find profound anatomical heterogeneity: (1) Layer weights follow strong mathematical regularity (R2 = 0.91) with a universal oscillatory delta pattern (correlation ~= -0.50), yet predicted weights cause catastrophic failure due to nonlinear error accumulation. (2) Layer importance spans a 10^7 range, from a critical core (L8-11, up to +63,419% PPL degradation) to anti-layers (L14, L17) whose removal improves performance. (3) Recovery speed correlates with layer importance, indicating differential training requirements. (4) Only weight scaling (alpha = 0.9) preserves model quality among five tested manipulation strategies. (5) Growth Transformer Training, allocating budget by layer importance, achieves ~54% cost reduction. A proof-of-concept experiment confirms this: 4.7x lower validation loss than uniform training at identical parameter count, while being 13% faster.
### Title:
          AURORA: Adaptive Unified Representation for Robust Ultrasound Analysis
 - **Authors:** Ufaq Khan, L. D. M. S. Sai Teja, Ayuba Shakiru, Mai A. Shaaban, Yutong Xie, Muhammad Bilal, Muhammad Haris Khan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ultrasound images vary widely across scanners, operators, and anatomical targets, which often causes models trained in one setting to generalize poorly to new hospitals and clinical conditions. The Foundation Model Challenge for Ultrasound Image Analysis (FMC-UIA) reflects this difficulty by requiring a single model to handle multiple tasks, including segmentation, detection, classification, and landmark regression across diverse organs and datasets. We propose a unified multi-task framework based on a transformer visual encoder from the Qwen3-VL family. Intermediate token features are projected into spatial feature maps and fused using a lightweight multi-scale feature pyramid, enabling both pixel-level predictions and global reasoning within a shared representation. Each task is handled by a small task-specific prediction head, while training uses task-aware sampling and selective loss balancing to manage heterogeneous supervision and reduce task imbalance. Our method is designed to be simple to optimize and adaptable across a wide range of ultrasound analysis tasks. The performance improved from 67% to 85% on the validation set and achieved an average score of 81.84% on the official test set across all tasks. The code is publicly available at: this https URL
### Title:
          Vocabulary shapes cross-lingual variation of word-order learnability in language models
 - **Authors:** Jonas Mayer Martins, Jaap Jumelet, Viola Priesemann, Lisa Beinborn
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Why do some languages like Czech permit free word order, while others like English do not? We address this question by pretraining transformer language models on a spectrum of synthetic word-order variants of natural languages. We observe that greater word-order irregularity consistently raises model surprisal, indicating reduced learnability. Sentence reversal, however, affects learnability only weakly. A coarse distinction of free- (e.g., Czech and Finnish) and fixed-word-order languages (e.g., English and French) does not explain cross-lingual variation. Instead, the structure of the word and subword vocabulary strongly predicts the model surprisal. Overall, vocabulary structure emerges as a key driver of computational word-order learnability across languages.
### Title:
          VeloxNet: Efficient Spatial Gating for Lightweight Embedded Image Classification
 - **Authors:** Md Meftahul Ferdaus, Elias Ioup, Mahdi Abdelguerfi, Anton Netchaev, Steven Sloan, Ken Pathak, Kendall N. Niles
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deploying deep learning models on embedded devices for tasks such as aerial disaster monitoring and infrastructure inspection requires architectures that balance accuracy with strict constraints on model size, memory, and latency. This paper introduces VeloxNet, a lightweight CNN architecture that replaces SqueezeNet's fire modules with gated multi-layer perceptron (gMLP) blocks for embedded image classification. Each gMLP block uses a spatial gating unit (SGU) that applies learned spatial projections and multiplicative gating, enabling the network to capture spatial dependencies across the full feature map in a single layer. Unlike fire modules, which are limited to local receptive fields defined by small convolutional kernels, the SGU provides global spatial modeling at each layer with fewer parameters. We evaluate VeloxNet on three aerial image datasets: the Aerial Image Database for Emergency Response (AIDER), the Comprehensive Disaster Dataset (CDD), and the Levee Defect Dataset (LDD), comparing against eleven baselines including MobileNet variants, ShuffleNet, EfficientNet, and recent vision transformers. VeloxNet reduces the parameter count by 46.1% relative to SqueezeNet (from 740,970 to 399,366) while improving weighted F1 scores by 6.32% on AIDER, 30.83% on CDD, and 2.51% on LDD. These results demonstrate that substituting local convolutional modules with spatial gating blocks can improve both classification accuracy and parameter efficiency for resource-constrained deployment. The source code will be made publicly available upon acceptance of the paper.
### Title:
          Vision Tiny Recursion Model (ViTRM): Parameter-Efficient Image Classification via Recursive State Refinement
 - **Authors:** Ange-Clément Akazan, Abdoulaye Koroko, Verlon Roel Mbingui, Choukouriyah Arinloye, Hassan Fifen, Rose Bandolo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The success of deep learning in computer vision has been driven by models of increasing scale, from deep Convolutional Neural Networks (CNN) to large Vision Transformers (ViT). While effective, these architectures are parameter-intensive and demand significant computational resources, limiting deployment in resource-constrained environments. Inspired by Tiny Recursive Models (TRM), which show that small recursive networks can solve complex reasoning tasks through iterative state refinement, we introduce the \textbf{Vision Tiny Recursion Model (ViTRM)}: a parameter-efficient architecture that replaces the $L$-layer ViT encoder with a single tiny $k$-layer block ($k{=}3$) applied recursively $N$ times. Despite using up to $6 \times $ and $84 \times$ fewer parameters than CNN based models and ViT respectively, ViTRM maintains competitive performance on CIFAR-10 and CIFAR-100. This demonstrates that recursive computation is a viable, parameter-efficient alternative to architectural depth in vision.
### Title:
          Pedestrian Crossing Intent Prediction via Psychological Features and Transformer Fusion
 - **Authors:** Sima Ashayer, Hoang H. Nguyen, Yu Liang, Mina Sartipi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pedestrian intention prediction needs to be accurate for autonomous vehicles to navigate safely in urban environments. We present a lightweight, socially informed architecture for pedestrian intention prediction. It fuses four behavioral streams (attention, position, situation, and interaction) using highway encoders, a compact 4-token Transformer, and global self-attention pooling. To quantify uncertainty, we incorporate two complementary heads: a variational bottleneck whose KL divergence captures epistemic uncertainty, and a Mahalanobis distance detector that identifies distributional shift. Together, these components yield calibrated probabilities and actionable risk scores without compromising efficiency. On the PSI 1.0 benchmark, our model outperforms recent vision language models by achieving 0.9 F1, 0.94 AUC-ROC, and 0.78 MCC by using only structured, interpretable features. On the more diverse PSI 2.0 dataset, where, to the best of our knowledge, no prior results exist, we establish a strong initial baseline of 0.78 F1 and 0.79 AUC-ROC. Selective prediction based on Mahalanobis scores increases test accuracy by up to 0.4 percentage points at 80% coverage. Qualitative attention heatmaps further show how the model shifts its cross-stream focus under ambiguity. The proposed approach is modality-agnostic, easy to integrate with vision language pipelines, and suitable for risk-aware intent prediction on resource-constrained platforms.
### Title:
          StreetForward: Perceiving Dynamic Street with Feedforward Causal Attention
 - **Authors:** Zhongrui Yu, Zhao Wang, Yijia Xie, Yida Wang, Xueyang Zhang, Yifei Zhan, Kun Zhan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Feedforward reconstruction is crucial for autonomous driving applications, where rapid scene reconstruction enables efficient utilization of large-scale driving datasets in closed-loop simulation and other downstream tasks, eliminating the need for time-consuming per-scene optimization. We present StreetForward, a pose-free and tracker-free feedforward framework for dynamic street reconstruction. Building upon the alternating attention mechanism from Visual Geometry Grounded Transformer (VGGT), we propose a simple yet effective temporal mask attention module that captures dynamic motion information from image sequences and produces motion-aware latent representations. Static content and dynamic instances are represented uniformly with 3D Gaussian Splatting, and are optimized jointly by cross-frame rendering with spatio-temporal consistency, allowing the model to infer per-pixel velocities and produce high-fidelity novel views at new poses and times. We train and evaluate our model on the Waymo Open Dataset, demonstrating superior performance on novel view synthesis and depth estimation compared to existing methods. Furthermore, zero-shot inference on CARLA and other datasets validates the generalization capability of our approach. More visualizations are available on our project page: this https URL.
### Title:
          Dual-Domain Representation Alignment: Bridging 2D and 3D Vision via Geometry-Aware Architecture Search
 - **Authors:** Haoyu Zhang, Zhihao Yu, Rui Wang, Yaochu Jin, Qiqi Liu, Ran Cheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern computer vision requires balancing predictive accuracy with real-time efficiency, yet the high inference cost of large vision models (LVMs) limits deployment on resource-constrained edge devices. Although Evolutionary Neural Architecture Search (ENAS) is well suited for multi-objective optimization, its practical use is hindered by two issues: expensive candidate evaluation and ranking inconsistency among subnetworks. To address them, we propose EvoNAS, an efficient distributed framework for multi-objective evolutionary architecture search. We build a hybrid supernet that integrates Vision State Space and Vision Transformer (VSS-ViT) modules, and optimize it with a Cross-Architecture Dual-Domain Knowledge Distillation (CA-DDKD) strategy. By coupling the computational efficiency of VSS blocks with the semantic expressiveness of ViT modules, CA-DDKD improves the representational capacity of the shared supernet and enhances ranking consistency, enabling reliable fitness estimation during evolution without extra fine-tuning. To reduce the cost of large-scale validation, we further introduce a Distributed Multi-Model Parallel Evaluation (DMMPE) framework based on GPU resource pooling and asynchronous scheduling. Compared with conventional data-parallel evaluation, DMMPE improves efficiency by over 70% through concurrent multi-GPU, multi-model execution. Experiments on COCO, ADE20K, KITTI, and NYU-Depth v2 show that the searched architectures, termed EvoNets, consistently achieve Pareto-optimal trade-offs between accuracy and efficiency. Compared with representative CNN-, ViT-, and Mamba-based models, EvoNets deliver lower inference latency and higher throughput under strict computational budgets while maintaining strong generalization on downstream tasks such as novel view synthesis. Code is available at this https URL
### Title:
          Beyond Quadratic: Linear-Time Change Detection with RWKV
 - **Authors:** Zhenyu Yang, Gensheng Pei, Tao Chen, Xia Yuan, Haofeng Zhang, Xiangbo Shu, Yazhou Yao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing paradigms for remote sensing change detection are caught in a trade-off: CNNs excel at efficiency but lack global context, while Transformers capture long-range dependencies at a prohibitive computational cost. This paper introduces ChangeRWKV, a new architecture that reconciles this conflict. By building upon the Receptance Weighted Key Value (RWKV) framework, our ChangeRWKV uniquely combines the parallelizable training of Transformers with the linear-time inference of RNNs. Our approach core features two key innovations: a hierarchical RWKV encoder that builds multi-resolution feature representation, and a novel Spatial-Temporal Fusion Module (STFM) engineered to resolve spatial misalignments across scales while distilling fine-grained temporal discrepancies. ChangeRWKV not only achieves state-of-the-art performance on the LEVIR-CD benchmark, with an 85.46% IoU and 92.16% F1 score, but does so while drastically reducing parameters and FLOPs compared to previous leading methods. This work demonstrates a new, efficient, and powerful paradigm for operational-scale change detection. Our code and model are publicly available.
### Title:
          RiboSphere: Learning Unified and Efficient Representations of RNA Structures
 - **Authors:** Zhou Zhang, Hanqun Cao, Cheng Tan, Fang Wu, Pheng Ann Heng, Tianfan Fu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate RNA structure modeling remains difficult because RNA backbones are highly flexible, non-canonical interactions are prevalent, and experimentally determined 3D structures are comparatively scarce. We introduce \emph{RiboSphere}, a framework that learns \emph{discrete} geometric representations of RNA by combining vector quantization with flow matching. Our design is motivated by the modular organization of RNA architecture: complex folds are composed from recurring structural motifs. RiboSphere uses a geometric transformer encoder to produce SE(3)-invariant (rotation/translation-invariant) features, which are discretized with finite scalar quantization (FSQ) into a finite vocabulary of latent codes. Conditioned on these discrete codes, a flow-matching decoder reconstructs atomic coordinates, enabling high-fidelity structure generation. We find that the learned code indices are enriched for specific RNA motifs, suggesting that the model captures motif-level compositional structure rather than acting as a purely compressive bottleneck. Across benchmarks, RiboSphere achieves strong performance in structure reconstruction (RMSD 1.25\,Å, TM-score 0.84), and its pretrained discrete representations transfer effectively to inverse folding and RNA--ligand binding prediction, with robust generalization in data-scarce regimes.
### Title:
          OmniDiT: Extending Diffusion Transformer to Omni-VTON Framework
 - **Authors:** Weixuan Zeng, Pengcheng Wei, Huaiqing Wang, Boheng Zhang, Jia Sun, Dewen Fan, Lin HE, Long Chen, Qianqian Gan, Fan Yang, Tingting Gao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite the rapid advancement of Virtual Try-On (VTON) and Try-Off (VTOFF) technologies, existing VTON methods face challenges with fine-grained detail preservation, generalization to complex scenes, complicated pipeline, and efficient inference. To tackle these problems, we propose OmniDiT, an omni Virtual Try-On framework based on the Diffusion Transformer, which combines try-on and try-off tasks into one unified model. Specifically, we first establish a self-evolving data curation pipeline to continuously produce data, and construct a large VTON dataset Omni-TryOn, which contains over 380k diverse and high-quality garment-model-tryon image pairs and detailed text prompts. Then, we employ the token concatenation and design an adaptive position encoding to effectively incorporate multiple reference conditions. To relieve the bottleneck of long sequence computation, we are the first to introduce Shifted Window Attention into the diffusion model, thus achieving a linear complexity. To remedy the performance degradation caused by local window attention, we utilize multiple timestep prediction and an alignment loss to improve generation fidelity. Experiments reveal that, under various complex scenes, our method achieves the best performance in both the model-free VTON and VTOFF tasks and a performance comparable to current SOTA methods in the model-based VTON task.
### Title:
          Semantic Audio-Visual Navigation in Continuous Environments
 - **Authors:** Yichen Zeng, Hebaixu Wang, Meng Liu, Yu Zhou, Chen Gao, Kehan Chen, Gongping Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Audio-visual navigation enables embodied agents to navigate toward sound-emitting targets by leveraging both auditory and visual cues. However, most existing approaches rely on precomputed room impulse responses (RIRs) for binaural audio rendering, restricting agents to discrete grid positions and leading to spatially discontinuous observations. To establish a more realistic setting, we introduce Semantic Audio-Visual Navigation in Continuous Environments (SAVN-CE), where agents can move freely in 3D spaces and perceive temporally and spatially coherent audio-visual streams. In this setting, targets may intermittently become silent or stop emitting sound entirely, causing agents to lose goal information. To tackle this challenge, we propose MAGNet, a multimodal transformer-based model that jointly encodes spatial and semantic goal representations and integrates historical context with self-motion cues to enable memory-augmented goal reasoning. Comprehensive experiments demonstrate that MAGNet significantly outperforms state-of-the-art methods, achieving up to a 12.1\% absolute improvement in success rate. These results also highlight its robustness to short-duration sounds and long-distance navigation scenarios. The code is available at this https URL.
### Title:
          The Residual Stream Is All You Need: On the Redundancy of the KV Cache in Transformer Inference
 - **Authors:** Kaleem Ullah Qasim, Jiashu Zhang, Muhammad Kafeel Shaheen, Razan Alharith, Heying Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The key-value (KV) cache is widely treated as essential state in transformer inference, and a large body of work engineers policies to compress, evict, or approximate its entries. We prove that this state is entirely redundant: keys and values at every layer are deterministic projections of the residual stream, and recomputing them from a single residual vector per token incurs exactly zero reconstruction error, not approximately, but bit-identically. We verify this across six models from four architecture families (135M to 4B parameters). Cross-task residual patching at every layer produces D_KL = 0 between patched and original output distributions, confirming that the residual stream satisfies a Markov property and is the sole information-carrying state. Removing the cache entirely and recomputing from scratch yields token-identical output under greedy decoding on all models tested. We build on this result with KV-Direct, a bounded-memory inference scheme that checkpoints residual vectors (5 KB per token on Gemma 3-4B) instead of full KV pairs (136 KB), recomputing keys and values on demand. Over 20 conversation turns, KV-Direct holds peak memory at 42 MB while the standard cache grows past 103 MB. Against five eviction baselines (H2O, StreamingLLM, SnapKV, TOVA, window-only), KV-Direct maintains 100% token match at every cache budget; all baselines degrade to 5-28%. A per-operation latency analysis shows recomputation runs up to 5x faster than reading cached tensors at moderate batch sizes. Code is available at this https URL.
### Title:
          Diminishing Returns in Expanding Generative Models and Godel-Tarski-Lob Limits
 - **Authors:** Angshul Majumdar
 - **Subjects:** Subjects:
Logic in Computer Science (cs.LO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern generative modelling systems are increasingly improved by expanding model capacity, training data, and computational resources. While empirical studies have documented such scaling behaviour across architectures including generative adversarial networks, variational autoencoders, transformer-based models, and diffusion models, the theoretical limits of capability growth in expanding generative systems remain poorly understood. In this paper we develop a general task-space framework for analysing expanding generative reasoning systems. Each system induces a subset of a global task space representing the tasks it can successfully solve, and system capability is measured by the probability mass of this solved-task set under a fixed task distribution. Within this framework we prove a structural result showing that, under mild assumptions, the marginal improvement in solved tasks must converge to zero as system capacity increases. Thus expanding generative systems may continue to gain capability, but the probability mass of newly solvable tasks necessarily diminishes asymptotically. We further provide a prediction-theoretic refinement based on complexity-weighted hypothesis classes inspired by algorithmic probability, yielding quantitative bounds on marginal improvement in prediction settings. Finally, we examine logical reasoning tasks and show that classical results from mathematical logic -- including Rosser incompleteness, Tarski's undefinability theorem, and Löb's theorem -- imply the persistence of unresolved logical tasks within sufficiently expressive reasoning systems. Together these results provide a mathematical perspective on the asymptotic behaviour of expanding generative systems, showing that long-run capability growth is constrained both by diminishing marginal improvements in task coverage and by fundamental logical limitations on internal reasoning.
### Title:
          Dual Path Attribution: Efficient Attribution for SwiGLU-Transformers through Layer-Wise Target Propagation
 - **Authors:** Lasse Marten Jantsch, Dong-Jae Koh, Seonghyeon Lee, Young-Kyoon Suh
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding the internal mechanisms of transformer-based large language models (LLMs) is crucial for their reliable deployment and effective operation. While recent efforts have yielded a plethora of attribution methods attempting to balance faithfulness and computational efficiency, dense component attribution remains prohibitively expensive. In this work, we introduce Dual Path Attribution (DPA), a novel framework that faithfully traces information flow on the frozen transformer in one forward and one backward pass without requiring counterfactual examples. DPA analytically decomposes and linearizes the computational structure of the SwiGLU Transformers into distinct pathways along which it propagates a targeted unembedding vector to receive the effective representation at each residual position. This target-centric propagation achieves O(1) time complexity with respect to the number of model components, scaling to long input sequences and dense component attribution. Extensive experiments on standard interpretability benchmarks demonstrate that DPA achieves state-of-the-art faithfulness and unprecedented efficiency compared to existing baselines.
### Title:
          ReLi3D: Relightable Multi-view 3D Reconstruction with Disentangled Illumination
 - **Authors:** Jan-Niklas Dihlmann, Mark Boss, Simon Donne, Andreas Engelhardt, Hendrik P.A. Lensch, Varun Jampani
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reconstructing 3D assets from images has long required separate pipelines for geometry reconstruction, material estimation, and illumination recovery, each with distinct limitations and computational overhead. We present ReLi3D, the first unified end-to-end pipeline that simultaneously reconstructs complete 3D geometry, spatially-varying physically-based materials, and environment illumination from sparse multi-view images in under one second. Our key insight is that multi-view constraints can dramatically improve material and illumination disentanglement, a problem that remains fundamentally ill-posed for single-image methods. Key to our approach is the fusion of the multi-view input via a transformer cross-conditioning architecture, followed by a novel unified two-path prediction strategy. The first path predicts the object's structure and appearance, while the second path predicts the environment illumination from image background or object reflections. This, combined with a differentiable Monte Carlo multiple importance sampling renderer, creates an optimal illumination disentanglement training pipeline. In addition, with our mixed domain training protocol, which combines synthetic PBR datasets with real-world RGB captures, we establish generalizable results in geometry, material accuracy, and illumination quality. By unifying previously separate reconstruction tasks into a single feed-forward pass, we enable near-instantaneous generation of complete, relightable 3D assets. Project Page: this https URL
### Title:
          Physical Layer Message Prediction for 5G Radio Access Network Protocols
 - **Authors:** Jonathan Ebert, Peter Rost
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Protocol reverse engineering stands as the cutting-edge approach in security research. This paper presents a framework capable of reverse engineering the communications within a mobile communication system. Our focus is on systems released by the 3GPP, with an emphasis on 5G NR. Our approach leverages the available context and syntax of the 5G standard to predict subsequent messages. This approach relies on a Transformer model and is trained based on an open-source 5G system implementation, emulating a base station and several user equipments. The prediction targets messages at the physical layer.
### Title:
          Transformer Causality Regularization for Dynamic Inverse Problems
 - **Authors:** Gesa Sarnighausen, Anne Wald, Andreas Hauptmann
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study the concept of including the causality principle as regularizer into the solution of linear time-dependent inverse problems. This is achieved by combining transformer-based predictions with classical variational regularization, resulting in what we call transformer causality regularization (TCR). The causality principle states that an object at time $t'$ depends only on its previous states at $t < t'$ and is independent of future states at $t > t'$. Since the transformer architecture represents sequence-to-sequence functions and can be equipped with a causal attention mask, transformers are the natural choice for a learned causality function that predicts the state of an object at time $t'$ given the previous states at $t < t'$. We combine this with the inductive bias of convolutional neural networks (CNNs) for imaging tasks to treat the spatial variable. The output of the spatial-temporal transformer is then used as a prior for variational regularization, such that classical results on regularization and convergence for solution methods directly transfer to our case. Using the example of dynamic computerized tomography, we compare TCR to a static and dynamic version of the earlier introduced unrolled adversarial regularizer for simulated and measured data. The results show that using TCR within a variational framework improves reconstruction results and data-consistency.
### Title:
          SIMPLER: Efficient Foundation Model Adaptation via Similarity-Guided Layer Pruning for Earth Observation
 - **Authors:** Víctor Barreiro, Johannes Jakubik, Francisco Argüello, Dora B. Heras
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fine-tuning foundation models for Earth Observation is computationally expensive, with high training time and memory demands for both training and deployment. Parameter-efficient methods reduce training cost but retain full inference complexity, while post-hoc compression optimizes inference only after costly full fine-tuning. We introduce SIMPLER, a pre-fine-tuning architecture selection method that reduces inference and deployment costs by identifying an effective model depth before adaptation. SIMPLER exploits stabilization of representations in deeper layers of pre-trained vision transformers: it computes layer-wise representation similarity on unlabeled task data and applies an automated scoring function to select redundant layers, with no gradients, magnitude heuristics, or hyperparameter tuning required. On Prithvi-EO-2, SIMPLER prunes up to 79% of parameters while retaining 94% of baseline performance, yielding a 2.1x training speedup and 2.6x inference speedup. The method generalizes to TerraMind (a multimodal EO foundation model) and ImageNet-pretrained ViT-MAE, demonstrating applicability across tasks, architectures, and spectral modalities. Code is available at this https URL.
### Title:
          SegVGGT: Joint 3D Reconstruction and Instance Segmentation from Multi-View Images
 - **Authors:** Jinyuan Qu, Hongyang Li, Lei Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D instance segmentation methods typically rely on high-quality point clouds or posed RGB-D scans, requiring complex multi-stage processing pipelines, and are highly sensitive to reconstruction noise. While recent feed-forward transformers have revolutionized multi-view 3D reconstruction, they remain decoupled from high-level semantic understanding. In this work, we present SegVGGT, a unified end-to-end framework that simultaneously performs feed-forward 3D reconstruction and instance segmentation directly from multi-view RGB images. By introducing object queries that interact with multi-level geometric features, our method deeply integrates instance identification into the visual geometry grounded transformer. To address the severe attention dispersion problem caused by the massive number of global image tokens, we propose the Frame-level Attention Distribution Alignment (FADA) strategy. FADA explicitly guides object queries to attend to instance-relevant frames during training, providing structured supervision without extra inference overhead. Extensive experiments demonstrate that SegVGGT achieves the state-of-the-art performance on ScanNetv2 and ScanNet200, outperforming both recent joint models and RGB-D-based approaches, while exhibiting strong generalization capabilities on ScanNet++.
### Title:
          On the Ability of Transformers to Verify Plans
 - **Authors:** Yash Sarrof, Yupei Du, Katharina Stein, Alexander Koller, Sylvie Thiébaux, Michael Hahn
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers have shown inconsistent success in AI planning tasks, and theoretical understanding of when generalization should be expected has been limited. We take important steps towards addressing this gap by analyzing the ability of decoder-only models to verify whether a given plan correctly solves a given planning instance. To analyse the general setting where the number of objects -- and thus the effective input alphabet -- grows at test time, we introduce C*-RASP, an extension of C-RASP designed to establish length generalization guarantees for transformers under the simultaneous growth in sequence length and vocabulary size. Our results identify a large class of classical planning domains for which transformers can provably learn to verify long plans, and structural properties that significantly affects the learnability of length generalizable solutions. Empirical experiments corroborate our theory.
### Title:
          Channel Prediction-Based Physical Layer Authentication under Consecutive Spoofing Attacks
 - **Authors:** Yijia Guo, Junqing Zhang, Yao-Win Peter Hong
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Wireless networks are highly vulnerable to spoofing attacks, especially when attackers transmit consecutive spoofing packets. Conventional physical layer authentication (PLA) methods have mostly focused on single-packet spoofing attack. However, under consecutive spoofing attacks, they become ineffective due to channel evolution caused by device mobility and channel fading. To address this challenge, we propose a channel prediction-based PLA framework. Specifically, a Transformer-based channel prediction module is employed to predict legitimate CSI measurements during spoofing interval, and the input of channel prediction module is adaptively updated with predicted or observed CSI measurements based on the authentication decision to ensure robustness against sustained spoofing. Simulation results under Rayleigh fading channels demonstrate that the proposed approach achieves low prediction error and significantly higher authentication accuracy than conventional benchmark, maintaining robustness even under extended spoofing attacks.
## Keyword: autonomous driving
### Title:
          GT-Space: Enhancing Heterogeneous Collaborative Perception with Ground Truth Feature Space
 - **Authors:** Wentao Wang, Haoran Xu, Guang Tan
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In autonomous driving, multi-agent collaborative perception enhances sensing capabilities by enabling agents to share perceptual data. A key challenge lies in handling {\em heterogeneous} features from agents equipped with different sensing modalities or model architectures, which complicates data fusion. Existing approaches often require retraining encoders or designing interpreter modules for pairwise feature alignment, but these solutions are not scalable in practice. To address this, we propose {\em GT-Space}, a flexible and scalable collaborative perception framework for heterogeneous agents. GT-Space constructs a common feature space from ground-truth labels, providing a unified reference for feature alignment. With this shared space, agents only need a single adapter module to project their features, eliminating the need for pairwise interactions with other agents. Furthermore, we design a fusion network trained with contrastive losses across diverse modality combinations. Extensive experiments on simulation datasets (OPV2V and V2XSet) and a real-world dataset (RCooper) demonstrate that GT-Space consistently outperforms baselines in detection accuracy while delivering robust performance. Our code will be released at this https URL.
### Title:
          StreetForward: Perceiving Dynamic Street with Feedforward Causal Attention
 - **Authors:** Zhongrui Yu, Zhao Wang, Yijia Xie, Yida Wang, Xueyang Zhang, Yifei Zhan, Kun Zhan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Feedforward reconstruction is crucial for autonomous driving applications, where rapid scene reconstruction enables efficient utilization of large-scale driving datasets in closed-loop simulation and other downstream tasks, eliminating the need for time-consuming per-scene optimization. We present StreetForward, a pose-free and tracker-free feedforward framework for dynamic street reconstruction. Building upon the alternating attention mechanism from Visual Geometry Grounded Transformer (VGGT), we propose a simple yet effective temporal mask attention module that captures dynamic motion information from image sequences and produces motion-aware latent representations. Static content and dynamic instances are represented uniformly with 3D Gaussian Splatting, and are optimized jointly by cross-frame rendering with spatio-temporal consistency, allowing the model to infer per-pixel velocities and produce high-fidelity novel views at new poses and times. We train and evaluate our model on the Waymo Open Dataset, demonstrating superior performance on novel view synthesis and depth estimation compared to existing methods. Furthermore, zero-shot inference on CARLA and other datasets validates the generalization capability of our approach. More visualizations are available on our project page: this https URL.
### Title:
          DynFlowDrive: Flow-Based Dynamic World Modeling for Autonomous Driving
 - **Authors:** Xiaolu Liu, Yicong Li, Song Wang, Junbo Chen, Angela Yao, Jianke Zhu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recently, world models have been incorporated into the autonomous driving systems to improve the planning reliability. Existing approaches typically predict future states through appearance generation or deterministic regression, which limits their ability to capture trajectory-conditioned scene evolution and leads to unreliable action planning. To address this, we propose DynFlowDrive, a latent world model that leverages flow-based dynamics to model the transition of world states under different driving actions. By adopting the rectifiedflow formulation, the model learns a velocity field that describes how the scene state changes under different driving actions, enabling progressive prediction of future latent states. Building upon this, we further introduce a stability-aware multi-mode trajectory selection strategy that evaluates candidate trajectories according to the stability of the induced scene transitions. Extensive experiments on the nuScenes and NavSim benchmarks demonstrate consistent improvements across diverse driving frameworks without introducing additional inference overhead. Source code will be abaliable at this https URL.
### Title:
          Failure Modes for Deep Learning-Based Online Mapping: How to Measure and Address Them
 - **Authors:** Michael Hubbertz, Qi Han, Tobias Meisen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning-based online mapping has emerged as a cornerstone of autonomous driving, yet these models frequently fail to generalize beyond familiar environments. We propose a framework to identify and measure the underlying failure modes by disentangling two effects: Memorization of input features and overfitting to known map geometries. We propose measures based on evaluation subsets that control for geographical proximity and geometric similarity between training and validation scenes. We introduce Fréchet distance-based reconstruction statistics that capture per-element shape fidelity without threshold tuning, and define complementary failure-mode scores: a localization overfitting score quantifying the performance drop when geographic cues disappear, and a map geometry overfitting score measuring degradation as scenes become geometrically novel. Beyond models, we analyze dataset biases and contribute map geometry-aware diagnostics: A minimum-spanning-tree (MST) diversity measure for training sets and a symmetric coverage measure to quantify geometric similarity between splits. Leveraging these, we formulate an MST-based sparsification strategy that reduces redundancy and improves balancing and performance while shrinking training size. Experiments on nuScenes and Argoverse 2 across multiple state-of-the-art models yield more trustworthy assessment of generalization and show that map geometry-diverse and balanced training sets lead to improved performance. Our results motivate failure-mode-aware protocols and map geometry-centric dataset design for deployable online mapping.
### Title:
          LIORNet: Self-Supervised LiDAR Snow Removal Framework for Autonomous Driving under Adverse Weather Conditions
 - **Authors:** Ji-il Park, Inwook Shim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR sensors provide high-resolution 3D perception and long-range detection, making them indispensable for autonomous driving and robotics. However, their performance significantly degrades under adverse weather conditions such as snow, rain, and fog, where spurious noise points dominate the point cloud and lead to false perception. To address this problem, various approaches have been proposed: distance-based filters exploiting spatial sparsity, intensity-based filters leveraging reflectance distributions, and learning-based methods that adapt to complex environments. Nevertheless, distance-based methods struggle to distinguish valid object points from noise, intensity-based methods often rely on fixed thresholds that lack adaptability to changing conditions, and learning-based methods suffer from the high cost of annotation, limited generalization, and computational overhead. In this study, we propose LIORNet, which eliminates these drawbacks and integrates the strengths of all three paradigms. LIORNet is built upon a U-Net++ backbone and employs a self-supervised learning strategy guided by pseudo-labels generated from multiple physical and statistical cues, including range-dependent intensity thresholds, snow reflectivity, point sparsity, and sensing range constraints. This design enables LIORNet to distinguish noise points from environmental structures without requiring manual annotations, thereby overcoming the difficulty of snow labeling and the limitations of single-principle approaches. Extensive experiments on the WADS and CADC datasets demonstrate that LIORNet outperforms state-of-the-art filtering algorithms in both accuracy and runtime while preserving critical environmental features. These results highlight LIORNet as a practical and robust solution for LiDAR perception in extreme weather, with strong potential for real-time deployment in autonomous driving systems.
### Title:
          2K Retrofit: Entropy-Guided Efficient Sparse Refinement for High-Resolution 3D Geometry Prediction
 - **Authors:** Tianbao Zhang, Zhenyu Liang, Zhenbo Song, Nana Wang, Xiaomei Zhang, Xudong Cai, Zheng Zhu, Kejian Wu, Gang Wang, Zhaoxin Fan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-resolution geometric prediction is essential for robust perception in autonomous driving, robotics, and AR/MR, but current foundation models are fundamentally limited by their scalability to real-world, high-resolution scenarios. Direct inference on 2K images with these models incurs prohibitive computational and memory demands, making practical deployment challenging. To tackle the issue, we present 2K Retrofit, a novel framework that enables efficient 2K-resolution inference for any geometric foundation model, without modifying or retraining the backbone. Our approach leverages fast coarse predictions and an entropy-based sparse refinement to selectively enhance high-uncertainty regions, achieving precise and high-fidelity 2K outputs with minimal overhead. Extensive experiments on widely used benchmark demonstrate that 2K Retrofit consistently achieves state-of-the-art accuracy and speed, bridging the gap between research advances and scalable deployment in high-resolution 3D vision applications. Code will be released upon acceptance.
### Title:
          X-World: Controllable Ego-Centric Multi-Camera World Models for Scalable End-to-End Driving
 - **Authors:** Chaoda Zheng, Sean Li, Jinhao Deng, Zhennan Wang, Shijia Chen, Liqiang Xiao, Ziheng Chi, Hongbin Lin, Kangjie Chen, Boyang Wang, Yu Zhang, Xianming Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scalable and reliable evaluation is increasingly critical in the end-to-end era of autonomous driving, where vision--language--action (VLA) policies directly map raw sensor streams to driving actions. Yet, current evaluation pipelines still rely heavily on real-world road testing, which is costly, biased toward limited scenario coverage, and difficult to reproduce. These challenges motivate a real-world simulator that can generate realistic future observations under proposed actions, while remaining controllable and stable over long horizons. We present X-World, an action-conditioned multi-camera generative world model that simulates future observations directly in video space. Given synchronized multi-view camera history and a future action sequence, X-World generates future multi-camera video streams that follow the commanded actions. To ensure reproducible and editable scene rollouts, X-World further supports optional controls over dynamic traffic agents and static road elements, and retains a text-prompt interface for appearance-level control (e.g., weather and time of day). Beyond world simulation, X-World also enables video style transfer by conditioning on appearance prompts while preserving the underlying action and scene dynamics. At the core of X-World is a multi-view latent video generator designed to explicitly encourage cross-view geometric consistency and temporal coherence under diverse control signals. Experiments show that X-World achieves high-quality multi-view video generation with (i) strong view consistency across cameras, (ii) stable temporal dynamics over long rollouts, and (iii) high controllability with strict action following and faithful adherence to optional scene controls. These properties make X-World a practical foundation for scalable and reproducible evaluation.
### Title:
          Uncertainty Matters: Structured Probabilistic Online Mapping for Motion Prediction in Autonomous Driving
 - **Authors:** Pritom Gogoi, Faris Janjoš, Bin Yang, Andreas Look
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Online map generation and trajectory prediction are critical components of the autonomous driving perception-prediction-planning pipeline. While modern vectorized mapping models achieve high geometric accuracy, they typically treat map estimation as a deterministic task, discarding structural uncertainty. Existing probabilistic approaches often rely on diagonal covariance matrices, which assume independence between points and fail to capture the strong spatial correlations inherent in road geometry. To address this, we propose a structured probabilistic formulation for online map generation. Our method explicitly models intra-element dependencies by predicting a dense covariance matrix, parameterized via a Low-Rank plus Diagonal (LRPD) covariance decomposition. This formulation represents uncertainty as a combination of a low-rank component, which captures global spatial structure, and a diagonal component representing independent local noise, thereby capturing geometric correlations without the prohibitive computational cost of full covariance matrices. Evaluations on the nuScenes dataset demonstrate that our uncertainty-aware framework yields consistent improvements in online map generation quality compared to deterministic baselines. Furthermore, our approach establishes new state-of-the-art performance for map-based motion prediction, highlighting the critical role of uncertainty in planning tasks. Code is published under link-available-soon.
### Title:
          Wildfire Spread Scenarios: Increasing Sample Diversity of Segmentation Diffusion Models with Training-Free Methods
 - **Authors:** Sebastian Gerard, Josephine Sullivan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Predicting future states in uncertain environments, such as wildfire spread, medical diagnosis, or autonomous driving, requires models that can consider multiple plausible outcomes. While diffusion models can effectively learn such multi-modal distributions, naively sampling from these models is computationally inefficient, potentially requiring hundreds of samples to find low-probability modes that may still be operationally relevant. In this work, we address the challenge of sample-efficient ambiguous segmentation by evaluating several training-free sampling methods that encourage diverse predictions. We adapt two techniques, particle guidance and SPELL, originally designed for the generation of diverse natural images, to discrete segmentation tasks, and additionally propose a simple clustering-based technique. We validate these approaches on the LIDC medical dataset, a modified version of the Cityscapes dataset, and MMFire, a new simulation-based wildfire spread dataset introduced in this paper. Compared to naive sampling, these approaches increase the HM IoU* metric by up to 7.5% on MMFire and 16.4% on Cityscapes, demonstrating that training-free methods can be used to efficiently increase the sample diversity of segmentation diffusion models with little cost to image quality and runtime. Code and dataset: this https URL
