# Showing new listings for Wednesday, 13 May 2026
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
          SB-BEVFusion: Enhancing the Robustness against Sensor Malfunction and Corruptions
 - **Authors:** Markus Essl, Marta Moscati, Mubashir Noman, Muhammad Zaigham Zaheer, Usman Naseem, Shah Nawaz, Markus Schedl
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal sensor fusion has demonstrated remarkable performance improvements over unimodal approaches in 3D object detection for autonomous vehicles. Typically, existing methods transform multimodal data from independent sensors, such as camera and LiDAR, into a unified bird's-eye view (BEV) representation for fusion. Although effective in ideal conditions, this strategy suffers from substantial performance deterioration when camera or LiDAR data are missing, corrupted, or noisy. To address this vulnerability, we develop a framework-agnostic fusion module for camera and LiDAR data that allows for handling cases when one of the two modalities is missing or corrupted. To demonstrate the effectiveness of our module, we instantiate it in BEVFusion [1], a well-established framework to combine camera and LiDAR data for 3D object detection. By means of quantitative experiments on the MultiCorrupt dataset, we demonstrate that our module achieves favorable performance improvements under scenarios of missing and corrupted modalities, substantially outperforming existing unified representation approaches across a wide range of sensor deterioration scenarios and reaching state-of-the-art performance in scenarios of corrupted modality due to extreme weather conditions and sensor failure.
### Title:
          TriBand-BEV: Real-Time LiDAR-Only 3D Pedestrian Detection via Height-Aware BEV and High-Resolution Feature Fusion
 - **Authors:** Mohammad Khoshkdahan, Alexey Vinel
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Safe autonomous agents and mobile robots need fast real time 3D perception, especially for vulnerable road users (VRUs) such as pedestrians. We introduce a new bird's eye view (BEV) encoding, which maps the full 3D LiDAR point cloud into a light-weight 2D BEV tensor with three height bands. We explicitly reformulate 3D detection as a 2D detection problem and then reconstruct 3D boxes from the BEV outputs. A single network detects cars, pedestrians, and cyclists in one pass. The backbone uses area attention at deep stages, a hierarchical bidirectional neck over P1 to P4 fuses context and detail, and the head predicts oriented boxes with distribution focal learning for side offsets and a rotated IoU loss. Training applies a small vertical re bin and a mild reflectance jitter in channel space to resist memorization. We use an interquartile range (IQR) filter to remove noisy and outlier LiDAR points during 3D reconstruction. On KITTI dataset, TriBand-BEV attains 58.7/52.6/47.2 pedestrian BEV AP(%) for easy, moderate, and hard at 49 FPS on a single consumer GPU, surpassing Complex-YOLO, with gains of +12.6%, +7.5%, and +3.1%. Qualitative scenes show stable detection under occlusion. The pipeline is compact and ready for real time robotic deployment. Our source code is publicly available on GitHub.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          3D Gaussian Splatting for Efficient Retrospective Dynamic Scene Novel View Synthesis with a Standardized Benchmark
 - **Authors:** Yunxiao Zhang, Suryansh Kumar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Retrospective novel view synthesis (NVS) of dynamic scenes is fundamental to applications such as sports. Recent dynamic 3D Gaussian Splatting (3DGS) approaches introduce temporally coupled formulations to enforce motion coherence across time. In this paper, we argue that, in a synchronized multi-view (MV) setting typical of sports, the dynamic scene at each time step is already strongly geometrically constrained. We posit that the availability of calibrated, synchronized viewpoints provides sufficient spatial consistency, and therefore, explicit temporal coupling, or complex multi-body constraints seems unnecessary for retrospective NVS. To this end, we propose an approach tailored for synchronized MV dynamic scene. By initializing the SfM-derived point cloud at the start time and propagating optimized Gaussians over time, we show that efficient retrospective NVS can be achieved without imposing a temporal deformation constraint. Complementing our methodological contribution, we introduce a Dynamic MV dataset framework built on Blender for reproducible NeRF and 3DGS research. The framework generates high-quality, synchronized camera rigs and exports training-ready datasets in standard formats, eliminating inconsistencies in coordinate conventions and data pipelines. Using the framework, we construct a dynamic benchmark suite and evaluate representative NeRF and 3DGS approaches under controlled conditions. Together, we show that, under a synchronized MV setup, efficient retrospective dynamic scene NVS can be achieved using 3DGS. At the same time, the dataset-generation framework enables reproducible and principled benchmarking of dynamic NVS methods.
## Keyword: mapping
### Title:
          Annotation-Free Indoor Radio Mapping via Physics-Informed Trajectory Inference
 - **Authors:** Zheng Xing, Mengru Wu, Yi Zhang, Guanghui Zhang, Jun Gao, Weibing Zhao, Xuhui Zhang, Jinke Ren, Shuguang Cui
 - **Subjects:** Subjects:
Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Constructing indoor radio maps traditionally requires extensive site surveys with precise user-location labels, making the calibration process costly and time-consuming. Existing calibration-reduction methods either depend on partial location annotations or exploit inertial measurement units (IMUs) to provide relative motion cues; however, IMU-assisted solutions are constrained by hardware availability, device-level access restrictions, and accumulated sensor drift. In this paper, we study a location-label-free indoor radio mapping problem under known access-point deployment geometry and a known walkable spatial domain. We propose a physics-informed trajectory inference framework that uses only Channel State Information (CSI), without relying on user-location labels or IMU measurements. The key idea is to recover the latent spatial coordinates of CSI measurements by exploiting the local spatial continuity of multipath propagation. To this end, we construct a Power-Angle-Delay Profile (PADP) feature distance from MIMO-OFDM CSI and show that, within a local neighborhood and under quasi-static multipath conditions, this distance provides a physically meaningful proxy for small spatial displacements. We then incorporate the PADP-based continuity constraint into a spatially regularized Bayesian inference model for joint trajectory recovery and propagation-parameter estimation. Experiments on a real-world industrial CSI dataset demonstrate that the proposed framework achieves an average localization error of 0.88 m and a relative beam map construction error of 6.68%, improving upon representative channel-embedding and IMU-assisted baselines.
### Title:
          HiDream-O1-Image: A Natively Unified Image Generative Foundation Model with Pixel-level Unified Transformer
 - **Authors:** Qi Cai, Jingwen Chen, Chengmin Gao, Zijian Gong, Yehao Li, Yingwei Pan, Yi Peng, Zhaofan Qiu, Kai Yu, Yiheng Zhang, Hao Ai, Siying Bai, Yang Chen, Zhihui Chen, Fengbin Gao, Ying Guo, Dong Li, Zhen Shen, Leilei Shi, Jing Wang, Siyu Wang, Yimeng Wang, Rui Zheng, Ting Yao, Tao Mei
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The evolution of visual generative models has long been constrained by fragmented architectures relying on disjoint text encoders and external VAEs. In this report, we present HiDream-O1-Image, a natively unified generative foundation model via pixel-space Diffusion Transformer, that pioneers a paradigm shift from modular architectures to an end-to-end in-context visual generation engine. By mapping raw image pixels, text tokens, and task-specific conditions into a single shared token space, HiDream-O1-Image achieves a structural unification of multimodal inputs within an Unified Transformer (UiT) architecture. This native encoding paradigm eliminates the need for separate VAEs or disjoint pre-trained text encoders, allowing the model to treat diverse generation and editing tasks as a consistent in-context reasoning process. Extensive experiments show that HiDream-O1-Image excels across various generation tasks, including text-to-image generation, instruction-based editing, and subject-driven personalization. Notably, with only 8B parameters, HiDream-O1-Image (8B) achieves performance parity with or even surpasses established state-of-the-art models with significantly larger parameters (e.g., 27B Qwen-Image). Crucially, to validate the immense scalability of this paradigm, we successfully scale the architecture up to over 200B parameters. Experimental results demonstrate that this massive-scale version HiDream-O1-Image-Pro (200B+) unlocks unprecedented generative capabilities and superior performance, establishing new state-of-the-art benchmarks. Ultimately, HiDream-O1-Image highlights the immense potential of natively unified architectures and charts a highly scalable path toward next-generation multimodal AI.
### Title:
          CORE: Cyclic Orthotope Relation Embedding for Knowledge Graph Completion
 - **Authors:** Yingqi Zeng, Luying Wang, Huiling Zhu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Knowledge graph completion (KGC) aims to automatically infer missing facts in multi-relational data by mapping entities and relations into continuous representation spaces. Recent region-based embedding models have shown great promise in capturing complex logical patterns by representing relations as geometric regions. However, these models inevitably suffer from absolute boundary constraints during optimization. Conversely, without such constraints, relation regions expand indefinitely. To address the limitation, we propose \textbf{CORE} (Cyclic Orthotope Relation Embedding), a novel KGC model that embeds entities and relations onto a boundary-less torus this http URL represents relations as cyclic orthotopes on the torus manifold, allowing regions to seamlessly wrap around spatial boundaries to ensure smooth gradient conduction. Furthermore, an adaptive width regularization is introduced to prevent unconditional region expansion. Theoretical analysis proves that CORE can capture various complex relation patterns such as subsumption and intersection. Extensive experiments on four benchmark datasets demonstrate that CORE achieves highly competitive performance, significantly improving link prediction accuracy in dense semantic environments.
### Title:
          FeatMap: Understanding image manipulation in the feature space and its implications for feature space geometry
 - **Authors:** Elias B. Krey, Nils Neukirch, Nils Strodthoff
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Intermediate feature representations represent the backbone for the expressivity and adaptability of deep neural networks. However, their geometric structure remains poorly understood. In this submission, we provide indirect insights into this matter by applying a broad selection of manipulations in input space, ranging from geometric and photometric transformations to local masking and semantic manipulations using generative image editing models, and assess the feasibility of learning a mapping in the feature space, mapping from the original to the manipulated feature map. To this end, we devise different types of mappings, from linear to non-linear and local to global mappings and assess both the reconstruction quality of the mapping as well as the semantic content of the mapped representations. We demonstrate the feasibility of learning such mappings for all considered transformations. While global (transformer) models that operate on the full feature map often achieve best results, we show that the same can be achieved with a shared linear model operating on a single feature vector typically with very little degradation in reconstruction quality, even for highly non-trivial semantic manipulations. We analyze the corresponding mappings across different feature layers and characterize them according to dominance of weight vs. bias and the effective rank of the linear transformations. These results provide hints for the hypothesis that the feature space is to a first degree of approximation organized in linear structures. From a broader perspective, the study demonstrates that generative image editing models might open the door to a deeper understanding of the feature space through input manipulation.
### Title:
          Support-Proximity Augmented Diffusion Estimation for Offline Black-Box Optimization
 - **Authors:** Yonghan Yang, Ye Yuan, Zipeng Sun, Linfeng Du, Bowei He, Haolun Wu, Can Chen, Xue Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Offline black-box optimization aims to discover novel designs with high property scores using only a static dataset, a task fundamentally challenged by the out-of-distribution (OOD) extrapolation problem. Existing approaches typically bifurcate into inverse methods, which struggle with the ill-posed nature of mapping scores to designs, and forward methods, which often lack the distributional expressivity to quantify uncertainty effectively. In this work, we propose SPADE (Support-Proximity Augmented Diffusion Estimation), a novel framework that reimagines forward surrogate modeling through the lens of conditional generative modeling. SPADE models the forward likelihood p(y|x) using a diffusion model, but with two critical enhancements to tailor it for optimization: (1) a Calibrated Diffusion Estimation module that enforces global consistency in statistical moments and pairwise rankings, and (2) a Support-Proximity Regularization mechanism that implicitly internalizes the data manifold constraint p(x) via kNN-based density estimation. Theoretically, we prove that our regularization is first-order equivalent to maximizing a Bayesian posterior with a valid design prior. Empirically, SPADE achieves state-of-the-art performance across Design-Bench tasks and an LLM data mixture optimization benchmark.
### Title:
          Real-Scale Island Area and Coastline Estimation using Only its Place Name or Coordinates
 - **Authors:** Quanyun Wu, Kyle Gao, Wentao Sun, Hongjie He, Yuhao Chen, David A. Clausi, Jonathan Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate measurement of island area and coastline length is crucial for coastal zone monitoring and oceanographic analysis. However, traditional measurement and mapping methods usually rely heavily on orthophotos, expensive airborne depth sensors, or dense ground control points, which face serious limitations of high labor costs, time-consuming efforts, and low operational efficiency in vast and inaccessible open sea environments. To overcome these challenges and break away from the reliance on manual field exploration, this paper proposes a geometrically consistent, real-scale island measurement framework based on pure monocular vision. This project significantly reduces the mapping cost through a fully automated process and achieves high-efficiency measurement without prior GIS data. In our system pipeline, only the geographical coordinates or names of the target area need to be input to obtain a low-altitude surrounding image sequence. After obtaining the point clouds, a lightweight trajectory alignment algorithm (Umeyama) is used to restore the global physical scale, and the scaled model is orthorectified, enabling high-precision area and perimeter extraction directly on the 2D rasterized plane. We have fully verified this pipeline on four islands with different terrain features (covering natural landform islands and islands with complex artificial facilities). The experimental results show that the final measurement error of the system is stable at around 10\%, demonstrating excellent accuracy and robustness. Moreover, this framework has outstanding inference speed, requiring only 70 ms to process a single high-resolution image and generate point clouds, providing a highly practical new paradigm for large-scale marine and coastline
### Title:
          FERMI: Exploiting Relations for Membership Inference Against Tabular Diffusion Models
 - **Authors:** Abtin Mahyar, Masoumeh Shafieinejad, Yuhan Liu, Xi He
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Cryptography and Security (cs.CR); Databases (cs.DB)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion models are the leading approach for tabular data synthesis and are increasingly used to share sensitive records. Whether they actually protect privacy has become a pressing question. Membership inference attacks are the standard tool for this purpose, yet existing attacks assume a single-table setting and ignore the multi-relational structure of real sensitive data. A core challenge in assessing privacy risks from membership inference attacks in multi-table settings is how to leverage auxiliary information from relations associated with the target table, such as its parent tables. Particularly, we study a practical setting in which such auxiliary information is available only when training the attack model. At inference time, the attacker observes only the attribute values of the target record from the target table. We propose FERMI (FEature-mapping for Relational Membership Inference), which resolves this gap by enriching single-table features with relational membership signal. Across three tabular diffusion architectures and three real-world relational datasets, FERMI consistently improves attack performance over single-table baselines, with TPR@$0.1$FPR rising by up to 53% over the single-table baseline in the white-box setting and 22% in the black-box setting.
### Title:
          ToF ReSTIR: Time-of-Flight Rendering with Spatio-temporal Reservoir Resampling
 - **Authors:** Juhyeon Kim, Wojciech Jarosz, Adithya Pediredla
 - **Subjects:** Subjects:
Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a novel spatio-temporal reuse framework for time-resolved light transport, enabling efficient Monte Carlo rendering of time-of-flight (ToF) phenomena such as time-gated imaging and transient light capture. Existing ToF rendering methods are computationally expensive, scale poorly to complex dynamic scenes, and are therefore unsuitable for applications with strict latency constraints. To address this limitation, we draw inspiration from ReSTIR, a reuse-based technique for steady-state real-time rendering, and adapt its core principles to interactive-rate ToF simulation. However, naively applying existing ReSTIR methods to ToF rendering leads to severe inefficiency, as reused paths frequently violate optical path-length constraints and thus contribute little or no signal. We overcome this challenge by introducing a path reuse formulation that explicitly enforces physically valid optical path lengths. The key idea is path-length-aware shift mapping, a geometric transformation based on Newton's method that adjusts reused light paths to satisfy temporal gating constraints, inspired by specular manifold exploration in steady-state caustics rendering. The resulting framework substantially improves the efficiency of ToF rendering across a wide range of scenarios, including complex scenes with glossy or specular materials and dynamic motion. Our method supports both time-gated and transient rendering at interactive frame rates, enabling simulation under practical latency constraints. We demonstrate the effectiveness of our approach through two downstream applications, including shape reconstruction and navigation.
### Title:
          PRISM: A Geometric Risk Bound that Decomposes Drift into Scale, Shape, and Head
 - **Authors:** Chieh-Yen Lin, Shao-Hua Sun
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Comparing post-training LLM variants, such as quantized, LoRA-adapted, and distilled models, requires a diagnostic that identifies how a variant has drifted, not only whether it has degraded. Existing similarity scores such as CKA and SVCCA can flag degradation, but they do not directly link representation drift to risk or mechanism. We propose PRISM, Proxy Risk Inference via Structural Mapping, which exploits the linear output head of LLMs and the empirically near-isometric structure of their backbones to derive a closed-form upper bound on the cross-entropy risk gap between a target model and a post-training variant. The bound is calibrated for variant ranking and decomposes drift into three independently measurable axes: scale mismatch, shape mismatch, and head divergence. Each axis corresponds to a distinct failure mode, including shape distortion under low-bit quantization, scale separability under LoRA forgetting, and head divergence under GGUF k-quantization. As a result, the dominant axis suggests a remediation direction rather than merely raising a degradation flag. Because the shape term is differentiable, the same geometry can also serve as a training-time regularizer against catastrophic forgetting. Across two model families and five benchmarks, PRISM ranks variants with mean Spearman correlations of 0.820 for post-training quantization and 0.831 for LoRA forgetting, and its axis-guided shape regularizer outperforms experience replay in aggregate at mitigating downstream forgetting.
### Title:
          RNA-FM: Flow-Matching Generative Model for Genome-wide RNA-Seq Prediction
 - **Authors:** Yaxuan Song, Jianan Fan, Tianyi Wang, Qiuyue Hu, Hang Chang, Heng Huang, Weidong Cai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Histopathology whole-slide images (WSIs) are routinely acquired in clinical practice and contain rich tissue morphology but lack direct molecular architecture and functional programs defining pathological states, whereas RNA sequencing (RNA-seq) provides genome-wide transcriptional profiles at substantial cost, thereby motivating WSI-based genome-wide transcriptomic prediction. Existing approaches for predicting gene expression from WSIs predominantly rely on deterministic regression with one-to-one mapping, limiting their ability to capture biological heterogeneity and predictive uncertainty. We propose RNA-FM, a flow-matching generative framework for genome-wide bulk RNA-seq prediction from WSIs. RNA-FM formulates transcriptomic prediction as a continuous-time conditional transport problem, learning a velocity field that maps a simple prior to the target gene expression distribution conditioned on morphologies. By integrating pathway-level structure, RNA-FM enables scalable and biologically interpretable genome-wide gene expression imputation. Extensive experiments demonstrate that RNA-FM consistently outperforms state-of-the-art approaches while maintaining biological meaningfulness. Code is available at this https URL.
### Title:
          GeomHerd: A Forward-looking Herding Quantification via Ricci Flow Geometry on Agent Interactive Simulations
 - **Authors:** Lake Yang, Junwei Su, Jingfeng Zeng, Wenhao Lu, Xingzhi Qian, Weitong Zhang, Chuan Wu, Dunhong Jin
 - **Subjects:** Subjects:
Multiagent Systems (cs.MA); Machine Learning (cs.LG); Statistical Finance (q-fin.ST)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Herding -- where agents align their behaviors and act collectively -- is a central driver of market fragility and systemic risk. Existing approaches to quantify herding rely on price-correlation statistics, which inherently lag because they only detect coordination after it has already moved realised returns. We propose GeomHerd, a forward-looking geometric framework that bypasses this observability lag by quantifying coordination directly on upstream agent-interaction graphs. To generate these graphs, we treat a heterogeneous LLM-driven multi-agent simulator -- each financial trader instantiated by a persona-conditioned LLM call -- as a forecastable world, and evaluate the geometric pipeline on the Cividino--Sornette continuous-spin agent-based substrate as our headline financial testbed. By tracking the discrete Ollivier--Ricci curvature of these action graphs, GeomHerd captures the structural topology of emerging coordination. Theoretically, we establish a mean-field bridge mapping our graph-theoretic metric to CSAD, the classical macroscopic herding statistic, linking GeomHerd to downstream price-dispersion measurement. Empirically, GeomHerd anticipates herding long before aggregate market baselines: on the continuous-spin substrate, our primary detector fires a median of 272 steps before order-parameter onset; a contagion detector ($\beta_{-}$) recalls 65% of critical trajectories 318 steps early; and on co-firing trajectories the agent-graph signal precedes price-correlation-graph baselines by 40 steps. As a complementary indicator, the effective vocabulary of agent actions contracts during cascades. The geometric signature transfers out-of-domain to the Vicsek self-driven-particle model, and a curvature-conditioned forecasting head reduces cascade-window log-return MAE over detector-conditioned and price-only baselines.
### Title:
          GRAFT: Graph-Tokenized LLMs for Tool Planning
 - **Authors:** Xinyi Gao, Xinyu Ren, Junliang Yu, Tong Chen, Quoc Viet Hung Nguyen, Hongzhi Yin
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) are increasingly used to complete complex tasks by selecting and coordinating external tools across multiple steps. This requires aligning tool choices with subtask intent while satisfying directional execution dependencies among tools. To do this, existing methods model these dependencies as tool graphs and incorporate the graphs with LLMs through retrieval, serialization, or prompt-level injection. However, these external graph-use strategies all follow a matching paradigm, which often fails to align tool choices with the underlying subtask structure, producing semantically plausible plans that violate graph constraints. This issue is further exacerbated by error accumulation, where an early incorrect tool selection shifts the plan into an invalid graph state and causes subsequent predictions to drift away from the valid execution path. To address these challenges, we propose GRAFT, a graph-tokenized language model framework for dependency-aware tool planning. GRAFT internalizes the tool graph by mapping each tool node to a dedicated special token and learning directed tool dependencies within the representation space. It further introduces on-policy tool context distillation, training the model on its own sampled trajectories while distilling stepwise planning signals. Experiments show that GRAFT achieves state-of-the-art performance in exact sequence matching and dependency legality, supporting more reliable LLM tool planning in complex workflows.
### Title:
          A nonlinear extension of parametric model embedding for dimensionality reduction in parametric shape design
 - **Authors:** Andrea Serani, Giorgio Palma, Matteo Diez
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE); Machine Learning (cs.LG); Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dimensionality reduction is essential in simulation-based shape design, where high-dimensional parameterizations hinder optimization, surrogate modeling, and systematic design-space exploration. Parametric Model Embedding (PME) addresses this issue by constructing reduced variables from geometric information while preserving an explicit backmapping to the original design parameters. However, PME is intrinsically linear and may become inefficient when the sampled design space is governed by nonlinear geometric variability. This paper introduces a nonlinear extension of PME, denoted NLPME. The proposed framework preserves the defining principle of PME -- geometry-driven latent variables and parameter-mediated reconstruction -- while replacing the linear reduced subspace with a nonlinear latent representation. Geometry is not reconstructed directly from the latent variables; instead, the latent representation is decoded into admissible design parameters, and the corresponding geometry is recovered through a forward parametric map. The method is assessed on a bio-inspired autonomous underwater glider with a 32-dimensional parametric shape description and a CAD-based geometry-generation process. NLPME reaches a 5\% reconstruction-error threshold with \(N=5\) latent variables, compared with \(N=8\) for linear PME, and a 1\% threshold with \(N=9\), compared with \(N=15\) for PME. Comparison with a deep autoencoder shows that most of the nonlinear compression gain can be retained while preserving an explicit backmapping to the original design variables. The results establish NLPME as a compact, admissible, and engineering-compatible nonlinear reduced representation for parametric shape design spaces.
### Title:
          Dynamics of the Longest-Edge Altitude Bisection Algorithm
 - **Authors:** Jérôme Michaud, Sergey Korotov
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study a longest-edge based refinement scheme for triangulations, termed the longest-edge altitude bisection (LEAB), in which each triangle is subdivided by dropping the altitude from the vertex opposite to its longest edge. Using the normalized shape space of triangles introduced by Perdomo and Plaza in: Properties of triangulations obtained by the longest-edge bisection. \emph{Cent. Eur. J. Math.}, 12(12) (2014), 1796-1810, we show that LEAB admits a simple geometric description: the normalized left and right children of a triangle in focus are obtained by intersecting the geodesic of right triangles with rays issued from the endpoints of the longest edge and explicit formulas for the mappings are derived. This characterization implies an interesting observation that the associated refinement dynamics collapse the entire shape space onto the right-triangle geodesic in a single step and that every point on this geodesic is fixed. Two-sided bounds for the contraction of the mesh size (discretization parameter) are derived. Also, applications and limitations of the method are briefly discussed.
### Title:
          Improving the Performance and Learning Stability of Parallelizable RNNs Designed for Ultra-Low Power Applications
 - **Authors:** Julien Brandoit, Arthur Fyon, Damien Ernst, Guillaume Drion
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sequence learning is dominated by Transformers and parallelizable recurrent neural networks (RNNs) such as state-space models, yet learning long-term dependencies remains challenging, and state-of-the-art designs trade power consumption for performance. The Bistable Memory Recurrent Unit (BMRU) was introduced to enable hardware-software co-design of ultra-low power RNNs: quantized states with hysteresis provide persistent memory while mapping directly to analog primitives. However, BMRU performance lags behind parallelizable RNNs on complex sequential tasks. In this paper, we identify gradient blocking during state updates as a key limitation and propose a cumulative update formulation that restores gradient flow while preserving persistent memory, creating skip-connections through time. This leads to the Cumulative Memory Recurrent Unit (CMRU) and its relaxed variant, the $\alpha$CMRU. Experiments show that the cumulative formulation dramatically improves convergence stability and reduces initialization sensitivity. The CMRU and $\alpha$CMRU match or outperform Linear Recurrent Units (LRUs) and minimal Gated Recurrent Units (minGRUs) across diverse benchmarks at small model sizes, with particular advantages on tasks requiring discrete long-range retention, while the CMRU retains quantized states, persistent memory, and noise-resilient dynamics essential for analog implementation.
### Title:
          When Brains Disagree: Biological Ambiguity Underlies the Challenge of Amyloid PET Synthesis from Structural MRI
 - **Authors:** Louise E.G. Baron, Ross Callaghan, David M. Cash, Philip S. Weston, Hojjat Azadbakht, Hui Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Structural MRI-to-amyloid PET synthesis has been proposed as a non-invasive alternative for amyloid assessment in Alzheimer's disease (AD). However, reported performance of identical models varies widely across studies, and increasingly complex architectures have not led to consistent gains. This inconsistency is thought to be caused by a fundamental biological ambiguity: MRI captures neurodegeneration, while PET measures amyloid pathology - two processes that are often temporally decoupled in AD. As a result, similar MRI patterns may correspond to different amyloid states, creating ambiguous one-to-many mappings. MRI-to-amyloid PET synthesis may therefore be intrinsically ill-posed; however, this idea has yet to be tested scientifically. The aim of this work is to test this hypothesis through two controlled experiments. We first control the training distribution by stratifying paired MRI-PET data by amyloid and neurodegeneration status. Using two standard synthesis models under a controlled design, we show that biologically unambiguous mappings are learnable in isolation, but performance collapses when data ambiguity is introduced. This demonstrates that ambiguity in the data distribution, rather than architectural capacity, constrains performance. Second, we show that introducing orthogonal biological information in the form of plasma biomarkers resolves this ambiguity. When multimodal inputs are incorporated, performance improves and stability is restored. Together, these findings suggest that limited and inconsistent performance in MRI-to-amyloid PET synthesis is explained by intrinsic biological ambiguity, and that stable, meaningful progress requires multimodal integration rather than architectural complexity.
### Title:
          Cluster-Aware Neural Collapse Prompt Tuning for Long-Tailed Generalization of Vision-Language Models
 - **Authors:** Boyang Guo, Liang Li, Lin Peng, Yuhan Gao, Xichun Sheng, Chenggang Yan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Prompt learning has emerged as an efficient alternative to fine-tuning pre-trained vision-language models (VLMs). Despite its promise, current methods still struggle to maintain tail-class discriminability when adapting to class-imbalanced datasets. In this work, we propose cluster-aware neural collapse prompt tuning (CPT), which enhances the discriminability of tail classes in prompt-tuned VLMs without sacrificing their overall generalization. First, we design a cluster-invariant space by mining semantic assignments from the pre-trained VLM and mapping them to prompt-tuned features. This computes cluster-level boundaries and restricts the constraints to local neighborhoods, which reduces interference with the global semantic structure of the pre-trained VLM. Second, we introduce neural-collapse-driven discriminability optimization with three losses: textual Equiangular Tight Frame (ETF) separation loss, class-wise convergence loss, and rotation stabilization loss. These losses work together to shape intra-cluster geometry for better inter-class separation and intra-class alignment. Extensive experiments on 11 diverse datasets demonstrate that CPT outperforms SOTA methods, with stronger performance on long-tail classes and good generalization to unseen classes.
### Title:
          NOFE -- Neural Operator Function Embedding
 - **Authors:** Lars Uebbing, Harald L. Joakimsen, Siyan Chen, Georgios Leontidis, Kristoffer K. Wickstrøm, Michael C. Kampffmeyer, Sébastien Lefèvre, Arnt-Børre Salberg, Robert Jenssen
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Most dimensionality reduction methods treat data as discrete point clouds, ignoring the continuous domain structure inherent to many real-world processes. To bridge this gap, we introduce Neural Operator Function Embedding (NOFE), a domain-aware framework for continuous dimensionality reduction. NOFE learns function-to-function mappings via a Graph Kernel Operator, enabling mesh-free evaluation at arbitrary query locations independent of input discretization. We establish NOFE as approximation of sheaf-to-sheaf mappings, generalizing Sheaf Neural Networks to continuous domains. We evaluate NOFE across different datasets, comparing it against PCA, t-SNE, and UMAP. Our results demonstrate that NOFE significantly outperforms baselines in local structure preservation, achieving a local Stress of 0.111 compared to 0.398 for PCA, 0.773 for t-SNE, and 0.791 for UMAP for the ERA5 climate reanalysis dataset. NOFE also exhibits robust sampling independence, reducing the Patch Stitching Error by up to $20.0\times$ relative to UMAP (59.0 vs. 267.6 under regional normalization) and ensuring consistency across disjoint domain patches. While maintaining competitive global structure preservation (Stress-1: 0.379 vs. PCA's 0.268), NOFE resolves fine-grained structures and produces smooth, consistent embeddings that generalize across varying sample densities, addressing key limitations of discrete reduction methods.
### Title:
          EDGER: EDge-Guided with HEatmap Refinement for Generalizable Image Forgery Localization
 - **Authors:** Minh-Khoa Le-Phan, Minh-Hoang Le, Minh-Triet Tran, Trong-Le Do
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-guided inpainting has made image forgery increasingly realistic, challenging both SID and IFL. However, existing methods often struggle to point out suspicious signals across domains. To address this problem, we propose EDGER, a patch-based, dual-branch framework that localizes manipulated regions in arbitrary resolution images without sacrificing native resolution. The first branch, Edge-Guided Segmentation, introduces a Frequency-based Edge Detector to emphasize high-frequency inconsistencies at manipulation boundaries, and fine-tunes a SegFormer to fuse RGB and edge features for pixel-level masks. Since edge evidence is most informative only when patches contain both authentic and manipulated pixels, we complement Edge-Guided Segmentation with a Synthetic Heatmapping branch, a classification-based localizer that fine-tunes a CLIP-ViT image encoder with LoRA to flag fully synthetic patches. Together, Synthetic Heatmapping provides coarse, patch-level synthetic priors, while Edge-Guided Segmentation sharpens boundaries within partially manipulated patches, yielding comprehensive localization. Evaluated in the MediaEval 2025, SynthIM challenge, Manipulated Region Localization Task's setting, our approach scales to multi-megapixel imagery and exhibits strong cross-domain generalization. Extensive ablations highlight the complementary roles of frequency-based edge cues and patch-level synthetic priors in driving accurate, resolution-agnostic localization.
### Title:
          A geometry-aligned multi-fidelity framework for uncertainty quantification of wildfire spread
 - **Authors:** Konstantinos Vogiatzoglou, Costas Papadimitriou, Vasilis Bontozoglou, Petros Koumoutsakos, Han Gao
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE); Computational Physics (physics.comp-ph); Data Analysis, Statistics and Probability (physics.data-an)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Forward propagation of input uncertainties in physics-based wildfire models is computationally prohibitive, limiting the use of high-fidelity simulators in risk assessment workflows. This work introduces a geometry-aligned bi-fidelity surrogate framework that addresses the convection-dominated nature of wildfire spread by mapping low- and high-fidelity solution snapshots onto a common reference domain prior to basis selection and reconstruction. Unlike conventional bi-fidelity schemes, which combine spatially shifted snapshots and thus suffer from oscillations and excess basis requirements near sharp fronts, the proposed mapping aligns the dominant front geometry through per-variable shift/stretch transforms in 1D and an activity indicator-based affine alignment in 2D, so that reduced bases compare physically corresponding structures rather than displaced ones. Building on the ADfiRe physics-based simulator, we demonstrate the method on 1D and 2D test cases in which low- and high-fidelity models differ in mesh resolution and physical completeness. Across both settings, the geometry-aligned surrogate reproduces full-field temperature and fuel composition with substantially lower error than its unmapped counterpart, eliminates Gibbs-type oscillations near steep gradients, and recovers high-fidelity probability density functions for key quantities of interest (e.g., maximum temperature, evaporated moisture, and burned area). After offline training, online predictions are roughly three orders of magnitude cheaper than direct high-fidelity evaluation, making the framework a practical building block for many-query uncertainty quantification once the offline cost is amortized over enough queries. We discuss the conditions under which the geometric alignment is most effective, its limitations for non-convex or topologically complex fronts, and the path toward validation against real data.
### Title:
          FAME: Feature Activation Map Explanation on Image Classification and Face Recognition
 - **Authors:** Xinyi Zhang, Manuel Günther
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep Learning has revolutionized machine learning, reaching unprecedented levels of accuracy, but at the cost of reduced interpretability. Especially in image processing systems, deep networks transform local pixel information into more global concepts in a highly obscured manner. Explainable AI methods for image processing try to shed light on this issue by highlighting the regions of the image that are important for the prediction task. Among these, Class Activation Mapping (CAM) and its gradient-based variants compute attributions based on the feature map and upscale them to the image resolution, assuming that feature map locations are influenced only by underlying regions. Perturbation-based methods, such as CorrRISE, on the other hand, try to provide pixel-level attributions by perturbing the input with fixed patches and checking how the output of the network changes. In this work, we propose Feature Activation Map Explanation (FAME), which combines both worlds by using network gradients to compute changes to the input image, manipulating it in a gradient-driven way rather than using fixed patches. We apply this technique on two common tasks, image classification and face recognition, and show that CAM's above-mentioned assumption does not hold for deeper networks. We qualitatively and quantitively show that FAME produces attribution maps that are competitive state-of-the-art systems. Our code is available: {\footnotesize this https URL.}
### Title:
          Approximation Theory of Laplacian-Based Neural Operators for Reaction-Diffusion System
 - **Authors:** Takashi Furuya, Ryo Ozawa, Jenn-Nan Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural operators provide a framework for learning solution operators of partial differential equations (PDEs), enabling efficient surrogate modeling for complex systems. While universal approximation results are now well understood, approximation analysis specific to nonlinear reaction-diffusion systems remains limited. In this paper, we study neural operators applied to the solution mapping from initial conditions to time-dependent solutions of a generalized Gierer-Meinhardt reaction-diffusion system, a prototypical model of nonlinear pattern formation. Our main results establish explicit approximation error bounds in terms of network depth, width, and spectral rank by exploiting the Laplacian spectral representation of the Green's function underlying the PDE. We show that the required parameter complexity grows at most polynomially with respect to the target accuracy, demonstrating that Laplacian eigenfunction-based neural operator architectures alleviate the curse of parametric complexity encountered in generic operator learning. Numerical experiments on the Gierer-Meinhardt system support the theoretical findings.
### Title:
          Hölder Policy Optimisation
 - **Authors:** Yuxiang Chen, Dingli Liang, Yihang Chen, Ziqin Gong, Chenyang Le, Zhaokai Wang, Jiachen Zhu, Lingyu Yang, Jianghao Lin, Weinan Zhang, Jun Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Group Relative Policy Optimisation (GRPO) enhances large language models by estimating advantages across a group of sampled trajectories. However, mapping these trajectory-level advantages to policy updates requires aggregating token-level probabilities within each sequence. Relying on a fixed aggregation mechanism for this step fundamentally limits the algorithm's adaptability. Empirically, we observe a critical trade-off: certain fixed aggregations frequently suffer from training collapse, while others fail to yield satisfactory performance. To resolve this, we propose \textbf{HölderPO}, a generalised policy optimisation framework unifying token-level probability aggregation via the Hölder mean. By explicitly modulating the parameter $p$, our framework provides continuous control over the trade-off between gradient concentration and variance bounds. Theoretically, we prove that a larger $p$ concentrates the gradient to amplify sparse learning signals, whereas a smaller $p$ strictly bounds gradient variance. Because no static configuration can universally resolve this concentration-stability trade-off, we instantiate the framework with a dynamic annealing algorithm that progressively schedules $p$ across the training lifecycle. Extensive evaluations demonstrate superior stability and convergence over existing baselines. Specifically, our approach achieves a state-of-the-art average accuracy of $54.9\%$ across multiple mathematical benchmarks, yielding a substantial $7.2\%$ relative gain over standard GRPO and secures an exceptional $93.8\%$ success rate on ALFWorld.
### Title:
          World Action Models: The Next Frontier in Embodied AI
 - **Authors:** Siyin Wang, Junhao Shi, Zhaoyang Fu, Xinzhe He, Feihong Liu, Chenchen Yang, Yikang Zhou, Zhaoye Fei, Jingjing Gong, Jinlan Fu, Mike Zheng Shou, Xuanjing Huang, Xipeng Qiu, Yu-Gang Jiang
 - **Subjects:** Subjects:
Robotics (cs.RO); Computation and Language (cs.CL); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models have achieved strong semantic generalization for embodied policy learning, yet they learn reactive observation-to-action mappings without explicitly modeling how the physical world evolves under intervention. A growing body of work addresses this limitation by integrating world models, predictive models of environment dynamics, into the action generation pipeline. We term this emerging paradigm World Action Models (WAMs): embodied foundation models that unify predictive state modeling with action generation, targeting a joint distribution over future states and actions rather than actions alone. However, the literature remains fragmented across architectures, learning objectives, and application scenarios, lacking a unified conceptual framework. We formally define WAMs and disambiguate them from related concepts, and trace the foundations and early integration of VLA and world model research that gave rise to this paradigm. We organize existing methods into a structured taxonomy of Cascaded and Joint WAMs, with further subdivision by generation modality, conditioning mechanism, and action decoding strategy. We systematically analyze the data ecosystem fueling WAMs development, spanning robot teleoperation, portable human demonstrations, simulation, and internet-scale egocentric video, and synthesize emerging evaluation protocols organized around visual fidelity, physical commonsense, and action plausibility. Overall, this survey provides the first systematic account of the WAMs landscape, clarifies key architectural paradigms and their trade-offs, and identifies open challenges and future opportunities for this rapidly evolving field.
### Title:
          Unlocking Crowdsourcing for Ontology Matching Validation
 - **Authors:** Zhangcheng Qiang
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in large language models (LLMs) pose new challenges for ontology matching (OM). While OM systems built on LLMs have shown remarkable capabilities in discovering more mappings, traditional OM validation that relies on domain experts has become overwhelming. In this study, we explore the use of crowdsourcing for OM validation and introduce a novel crowdsourcing system. We propose three domain-specific mechanisms, namely differential trustworthiness, coherence pre-filling, and time-dependent beliefs, to ensure the quality of crowdsourcing for OM validation. We demonstrate that our crowdsourcing system can be integrated with state-of-the-art OM systems to enable human-in-the-loop validation. Two real-world use cases illustrate the effectiveness of our crowdsourcing system.
### Title:
          SI-Diff: A Framework for Learning Search and High-Precision Insertion with a Force-Domain Diffusion Policy
 - **Authors:** Yibo Liu, Stanko Oparnica, Simon Shewchun-Jakaitis, Guoyi Fu, Jie Wang, Jun Yang, Anand Jagannathan, Tony Hong-Yau Lo
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Contact-rich assembly is fundamental in robotics but poses significant challenges due to uncertainties in relative poses, such as misalignments and small clearances in peg-in-hole tasks. Existing approaches typically address search and high-precision insertion separately, because these tasks involve distinct action patterns. However, supporting both tasks within a single model, without switching models or weights, is desirable for intelligent assembly systems. In this work, we propose SI-Diff, a framework that learns both search and high-precision insertion through a force-domain diffusion policy. To this end, we introduce a new mode-conditioning mechanism that enables the policy to capture distinct action behaviors under a single framework. Moreover, we develop a new search teacher policy that can generate diverse trajectories. By training on successful and efficient demonstrations provided by the teacher policy, the model learns the mapping from tactile and end-effector velocity observations to effective action behaviors. We conduct thorough experiments to show that SI-Diff extends the tolerance to x-y misalignments from 2 mm to 5 mm compared to the state-of-the-art baseline, TacDiffusion, while also demonstrating strong zero-shot transferability to unseen shapes.
### Title:
          Approximation of Maximally Monotone Operators : A Graph Convergence Perspective
 - **Authors:** Takashi Furuya, Yury Korolev, Takaharu Yaguchi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Statistics Theory (math.ST)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Operator learning has been highly successful for continuous mappings between infinite-dimensional spaces, such as PDE solution operators. However, many operators of interest-including differential operators-are discontinuous or set-valued, and lie outside classical approximation frameworks. We propose a paradigm shift by formulating approximation via graph convergence (Painlevé-Kuratowski convergence), which is well-suited for closed operators. We show that uniform and $L^p$ approximation are fundamentally inadequate in this setting. Focusing on maximally monotone operators, we prove that any such operator can be approximated in the sense of local graph convergence by continuous encoder-decoder architectures, and further construct structure-preserving approximations that retain maximal monotonicity via resolvent-based parameterizations.
### Title:
          Geometric Factual Recall in Transformers
 - **Authors:** Shauli Ravfogel, Gilad Yehudai, Joan Bruna, Alberto Bietti
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 How do transformer language models memorize factual associations? A common view casts internal weight matrices as associative memories over pairs of embeddings, requiring parameter counts that scale linearly with the number of facts. We develop a theoretical and empirical account of an alternative, \emph{geometric} form of memorization in which learned embeddings encode relational structure directly, and the MLP plays a qualitatively different role. In a controlled setting where a single-layer transformer must memorize random bijections from subjects to a shared attribute set, we prove that a logarithmic embedding dimension suffices: subject embeddings encode \emph{linear superpositions} of their associated attribute vectors, and a small MLP acts as a relation-conditioned selector that extracts the relevant attribute via ReLU gating, and not as an associative key-value mapping. We extend these results to the multi-hop setting -- chains of relational queries such as ``Who is the mother of the wife of $x$?'' -- providing constructions with and without chain-of-thought that exhibit a provable capacity-depth tradeoff, complemented by a matching information-theoretic lower bound. Empirically, gradient descent discovers solutions with precisely the predicted structure. Once trained, the MLP transfers zero-shot to entirely new bijections when subject embeddings are appropriately re-initialized, revealing that it has learned a generic selection mechanism rather than memorized any particular set of facts.
## Keyword: localization
### Title:
          Seeing the Needle in the Haystack: Towards Weakly-Supervised Log Instance Anomaly Localization via Counterfactual Perturbation
 - **Authors:** Yutszyuk Wong, Wentai Wu, Yuen-Ying Yeung, Weiwei Lin
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Log anomaly detection is a critical task for system operations and security assurance. However, in networked systems at scale, log data are generated at massive scale while instance-level annotations are prohibitively expensive, posing great difficulties to fine-grained anomaly localization. To address this challenge, we propose LogMILP (Log anomaly localization based on Multi-Instance Learning enhanced by prototypes and Perturbation), a weakly supervised framework that enables both bag-level anomaly detection and instance-level anomaly localization using only bag-level labels. Our method guides the model to pinpoint the critical log entries using prototype-guided structural modeling with counterfactual perturbation consistency regularization, thereby improving localization reliability and interpretability under coarse-grained supervision. Experimental results on three public datasets demonstrate that LogMILP achieves competitive detection performance while yielding significantly more reliable instance-level localization. Our code is open-sourced at this https URL.
### Title:
          Skill Drift Is Contract Violation: Proactive Maintenance for LLM Agent Skill Libraries
 - **Authors:** Linfeng Fan, Yuan Tian, Ziwei Li, Zhiwu Lu
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLM agents increasingly rely on reusable skill libraries, but these skills silently decay as the external services, packages, APIs, and configurations they reference evolve. Existing monitors detect such changes at the wrong granularity: they observe values, not the role those values play in a skill. A version string in a comment is noise; the same string in a pinned dependency is an operational obligation. We formulate skill drift as contract violation and introduce \sgname{}, which extracts executable environment contracts from skill documents and validates only those role-bearing assumptions against known or live conditions. This distinction turns noisy monitoring into a precision-first maintenance signal. Contract-free CI probes produce 40\% false positives, while \sgname{} raises zero false alarms over 599 no-drift and hard-negative cases (Wilson 95\% CI $[0,0.6]\%$). In known-drift verification, \sgname{} achieves 100\% precision and 76\% recall with the strongest backbone; in a pre-registered study over 49 real skills, it discovers live drift with 86\% conservative precision. Violated contracts also make repair actionable, improving one-round success from 10\% without localization to 78\%. We release \dbname{}, an 880-pair benchmark for skill degradation.
### Title:
          DCVD: Dual-Channel Cross-Modal Fusion for Joint Vulnerability Detection and Localization
 - **Authors:** Wenxin Tang, Wenbin Li, Junliang Liu, Jingyu Xiao, Xi Xiao, Mingzhe Liu, Jinlong Yang, Xuan Liu, Yuehe Ma, Wang Luo, Qing Li, Lei Wang, Peng Xiangli
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Software vulnerability detection plays a critical role in ensuring system security, where real-world auditing requires not only determining whether a function is vulnerable but also pinpointing the specific lines responsible. However, existing approaches either rely on a single information source -- sequential, structural, or semantic -- failing to jointly exploit the complementary strengths across modalities, or treat statement-level localization merely as a byproduct of function-level detection without explicit line-level supervision. To address these limitations, we propose DCVD (Dual-Channel Cross-Modal Vulnerability Detection), a unified framework that performs joint function-level detection and statement-level localization. DCVD extracts control-dependency and semantic features through two parallel branches and integrates them via contrastive alignment coupled with bidirectional cross-attention, effectively bridging the cross-modal representation gap. It further introduces explicit supervision signals at both the function and statement levels, enabling collaborative optimization across the two granularities. Extensive experiments on a large-scale real-world vulnerability benchmark demonstrate that DCVD consistently outperforms state-of-the-art methods on both function-level detection and statement-level localization. Our code is available at this https URL.
### Title:
          Annotation-Free Indoor Radio Mapping via Physics-Informed Trajectory Inference
 - **Authors:** Zheng Xing, Mengru Wu, Yi Zhang, Guanghui Zhang, Jun Gao, Weibing Zhao, Xuhui Zhang, Jinke Ren, Shuguang Cui
 - **Subjects:** Subjects:
Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Constructing indoor radio maps traditionally requires extensive site surveys with precise user-location labels, making the calibration process costly and time-consuming. Existing calibration-reduction methods either depend on partial location annotations or exploit inertial measurement units (IMUs) to provide relative motion cues; however, IMU-assisted solutions are constrained by hardware availability, device-level access restrictions, and accumulated sensor drift. In this paper, we study a location-label-free indoor radio mapping problem under known access-point deployment geometry and a known walkable spatial domain. We propose a physics-informed trajectory inference framework that uses only Channel State Information (CSI), without relying on user-location labels or IMU measurements. The key idea is to recover the latent spatial coordinates of CSI measurements by exploiting the local spatial continuity of multipath propagation. To this end, we construct a Power-Angle-Delay Profile (PADP) feature distance from MIMO-OFDM CSI and show that, within a local neighborhood and under quasi-static multipath conditions, this distance provides a physically meaningful proxy for small spatial displacements. We then incorporate the PADP-based continuity constraint into a spatially regularized Bayesian inference model for joint trajectory recovery and propagation-parameter estimation. Experiments on a real-world industrial CSI dataset demonstrate that the proposed framework achieves an average localization error of 0.88 m and a relative beam map construction error of 6.68%, improving upon representative channel-embedding and IMU-assisted baselines.
### Title:
          Survey-Free Radio Map Construction via HMM-Based Coarse-to-Fine Inference
 - **Authors:** Zheng Xing, Weibing Zhao, Guanghui Zhang, Guangjin Pan, Xuhui Zhang, Jinke Ren, Henk Wymeersch, Yuan Wu, Shuguang Cui
 - **Subjects:** Subjects:
Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traditional radio map construction methods mandate labor-intensive data collection and precise location labeling. To address these limitations, we propose a novel survey-free approach for radio map construction that relies solely on unlabeled Received Signal Strength (RSS) measurements, thereby obviating the need for manual site surveys or auxiliary Inertial Measurement Units (IMUs). The key idea involves embedding multiple unlabeled RSS sequences into a known indoor layout, specifically targeting corridor-guided environments with a dominant unidirectional pedestrian flow. However, aligning the embedded coordinates with the RSS collection locations remains challenging due to the random fluctuations inherent in RSS data. To tackle this, we introduce a Hidden Markov Model (HMM)- based Coarse-to-Fine Inference (HCFI) framework. At the coarse level, we employ an HMM-based region label inference algorithm to partition RSS sequences and align the RSS segments with specific physical regions using graph-based inference. At the fine level, we develop an HMM-based location label inference technique to estimate RSS collection coordinates by leveraging RSS propagation principles while incorporating sequential spatio-temporal mobility probability. Empirical results from an office environment demonstrate that the proposed method achieves a radio map construction Mean Absolute Error (MAE) of 8.96 dB. Furthermore, based on the estimated radio map, k-Nearest Neighbor (KNN) localization yields an average positioning error of approximately 3.33 meters, offering a highly viable, survey-free solution for radio map construction under sequential topological assumptions.
### Title:
          ForceFlow: Learning to Feel and Act via Contact-Driven Flow Matching
 - **Authors:** Shuoheng Zhang, Yifu Yuan, Hongyao Tang, Yan Zheng, Qiaojun Yu, Pengyi Li, Guowei Huang, Helong Huang, Xingyue Quan, Jianye Hao
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing imitation learning methods enable robots to interact autonomously with the physical environment. However, contact-rich manipulation tasks remain a significant challenge due to complex contact dynamics that demand high-precision force feedback and control. Although recent efforts have attempted to integrate force/torque sensing into policies, how to build a simple yet effective framework that achieves robust generalization under multimodal observations remains an open question. In this paper, we propose ForceFlow, a force-aware reactive framework built upon flow matching. For contact-stage policy design, we investigate force signal fusion mechanisms and adopt an asymmetric multimodal fusion architecture that treats force as a global regulatory signal, combined with a joint prediction paradigm that enhances the policy's understanding of instantaneous force and historical information, thereby achieving deep coupling between force and motion. For task-level hierarchical decomposition, we divide manipulation into a vision-dominant approach stage (VLM-based pointing for target localization) and a touch-dominant interaction stage (force-driven contact execution), with a Vision-to-Force (V2F) handover mechanism that explicitly decouples spatial generalization from contact regulation. Experimental results across six real-world contact-rich tasks demonstrate that ForceFlow achieves a 37% success rate improvement over the strong baseline ForceVLA while maintaining significantly lower cost. Moreover, ForceFlow exhibits accurate force signal prediction and demonstrates superior performance in contact force self-regulation and zero-shot out-of-distribution (OOD) generalization.
### Title:
          USEMA: a Scalable Efficient Mamba Like Attention for Medical Image Segmentation
 - **Authors:** Elisha Dayag, Nhat Thanh Tran, Jack Xin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate medical image segmentation is an integral part of the medical image analysis pipeline that requires the ability to merge local and global information. While vision transformers are able to capture global interactions using vanilla self-attention, their quadratic computational complexity in the input size remains a struggle for medical image segmentation tasks. Motivated by the dispersion property of vanilla self-attention and recent development of Mamba form of attention, Scalable and Efficient Mamba like Attention (SEMA) utilizes token localization via local window attention to avoid dispersion and maintain focusing, complemented by theoretically consistent arithmetic averaging to capture global aspect of attention. In this work, we present USEMA, a hybrid UNet architecture that merges the local feature extraction ability of convolutional neural networks (CNNs) with SEMA attention. We conduct experiments with USEMA across a variety of modalities and image sizes, demonstrating improved computational efficiency compared to transformer based models using full self-attention, and superior segmentation performance relative to purely convolution and Mamba-based models.
### Title:
          Localization Boosting for Growth Markets: Mitigating Cross-Locale Behavioral Bias in Learning-to-Rank
 - **Authors:** Suryaa Veerabathiran Seran, Ashwin Naresh Kumar, Tracy Holloway King, Jing Zheng
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adobe Express is expanding internationally, but the US has a disproportionately large content supply and interaction volume. Learning-to-rank (LTR) models trained primarily on behavioral feedback inherit this imbalance: templates popular in US are over-served in non-US locales. This cross-locale exposure bias suppresses local content discoverability and degrades ranking quality in growth locales. We show that click-only training suppresses semantically informative localization features. Adding vision-language model (VLM) graded relevance labels as auxiliary supervision alongside clicks improves semantic alignment but does not preserve local content visibility. We propose a multi-objective framework combining behavioral supervision, VLM-derived relevance signals, and locale-aware boosting. Across five locales, the resulting model improves relevance while restoring stable localization, demonstrating the importance of disentangling exposure from semantic supervision.
### Title:
          Grounding by Remembering: Cross-Scene and In-Scene Memory for 3D Functional Affordances
 - **Authors:** Qirui Wang, Jingyi He, Yining Pan, Xulei Yang, Shijie Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Functional affordance grounding requires more than recognizing an object: an agent must localize the specific region that supports an interaction, such as the handle to pull or the button to press. This is difficult for training-free vision-language pipelines because actionable regions are often small, visually ambiguous, and repeated across multiple same-category instances in a scene. We propose AFFORDMEM, a framework that grounds 3D functional affordances by remembering geometry at two levels. The first is cross-scene affordance memory: the agent maintains a category-level memory bank of RGB images with affordance regions rendered as overlays, and recalls the most informative examples at query time to guide a frozen VLM toward small operable subregions that text-only prompting consistently misses. The second is in-scene spatial memory: as the agent processes the scene, it organizes candidate instances and their 3D spatial relations into a structured scene graph, enabling the language model to resolve references over distant or currently unobserved candidates such as "the second handle from the top." AFFORDMEM requires no model fine-tuning and no target-scene annotation, using a reusable memory bank built from source scenes. On SceneFun3D, our method improves AP50 over the prior training-free state of the art by 3.23 on Split 0 and 3.7 on Split 1. Ablation studies support complementary benefits: cross-scene affordance memory improves fine-grained localization, while in-scene spatial memory provides the larger gain on spatially qualified queries. The project homepage is available at the project page.
### Title:
          Weather-Robust Cross-View Geo-Localization via Prototype-Based Semantic Part Discovery
 - **Authors:** Chi-Nguyen Tran, Dao Sy Duy Minh, Huynh Trung Kiet, Nguyen Lam Phu Quy, Phu-Hoa Pham, Long Tran-Thanh
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-view geo-localization (CVGL), which matches an oblique drone view to a geo-referenced satellite tile, has emerged as a key alternative for autonomous drone navigation when GNSS signals are jammed, spoofed, or unavailable. Despite strong recent progress, three limitations persist: (1) global-descriptor designs compress the patch grid into a single vector without separating layout from texture across the view gap; (2) altitude-related scale variation is retained in the learned embedding rather than marginalized; and (3) multi-objective training relies on hand-tuned scalars over losses on incompatible gradient scales. We propose SkyPart, a lightweight swappable head for patch-based vision transformers (ViTs) that institutes explicit part grouping over the patch grid. SkyPart has four theory-grounded components: (i) learnable prototypes competing for patch tokens via single-pass cosine assignment; (ii) altitude-conditioned linear modulation applied only during training, making the retrieval embedding altitude-free at inference; (iii) a graph-attention readout over active prototypes; and (iv) a Kendall uncertainty-weighted multi-objective loss whose stationary points are Pareto-stationary. At 26.95M parameters and 22.14 GFLOPs, SkyPart is the smallest among top-performing methods and sets a new state of the art on SUES-200, University-1652, and DenseUAV under a single-pass, no-re-ranking, no-TTA protocol. Its advantage over the strongest baseline widens under the ten-condition WeatherPrompt corruption benchmark.
### Title:
          CaC: Advancing Video Reward Models via Hierarchical Spatiotemporal Concentrating
 - **Authors:** Jiyuan Wang, Huan Ouyang, Jiuzhou Lin, Chunyu Lin, Dewen Fan, Boheng Zhang, Haonan Fan, Fei Zuo, Jia Sun, Huaiqing Wang, Honglie Wang, Yiyang Fan, Zhenlong Yuan, Zijun Li, Yongrui Heng, Guosheng Lin, Fan Yang, Tingting Gao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we propose Concentrate and Concentrate (CaC), a coarse-to-fine anomaly reward model based on Vision-Language Models. During inference, it first conducts a global temporal scan to anchor anomalous time windows, then performs fine-grained spatial grounding within the localized interval, and finally derives robust judgments via structured spatiotemporal Chain-of-Thought reasoning. To equip the model with these capabilities, we construct the first large-scale generated video anomaly dataset with per-frame bounding-box annotations, temporal anomaly windows, and fine-grained attribution labels. Building on this dataset, we design a three-stage progressive training paradigm. The model initially learns spatial and temporal anchoring through single- and multi-frame supervised fine-tuning, and then is optimized by a reinforcement learning strategy based on two-turn Group Relative Policy Optimization (GRPO). Beyond conventional accuracy rewards, we introduce Temporal and Spatial IoU rewards to supervise the intermediate localization process, effectively guiding the model toward more grounded and interpretable spatiotemporal reasoning. Extensive experiments demonstrate that CaC can stably concentrate on subtle anomalies, achieving a 25.7% accuracy improvement on fine-grained anomaly benchmarks and, when used as a reward signal, CaC reduces generated-video anomalies by 11.7% while improving overall video quality.
### Title:
          OptArgus: A Multi-Agent System to Detect Hallucinations in LLM-based Optimization Modeling
 - **Authors:** Zhong Li, Zihan Guo, Xiaohan Lu, Juntao Wang, Jie Song, Chao Shen, Jiageng Wu, Mingyang Sun
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) are increasingly used to translate natural-language optimization problems into mathematical formulations and solver code, but matching the reference objective value is not a reliable test of correctness: an artifact may agree numerically while still changing the underlying optimization semantics. We formulate this issue as \emph{optimization-modeling hallucination detection}, namely structural consistency auditing over the problem description, symbolic model, and solver implementation. We develop, to our knowledge, the first fine-grained hallucination taxonomy specifically for optimization modeling, spanning objective, variable, constraint, and implementation failures. We use this taxonomy to design OptArgus, a multi-agent detector with conductor routing, specialist auditors, and evidence consolidation. To evaluate this setting, we introduce a three-part benchmark suite with $484$ clean artifacts, $1266$ controlled injected artifacts, and $6292$ natural LLM-generated artifacts. Against a matched single-agent baseline, OptArgus produces fewer false alarms on clean artifacts, more accurate top-ranked localization on controlled single-error cases, and stronger detection on natural model outputs. Together, these contributions turn optimization-modeling hallucination detection into a concrete empirical problem and suggest that modular, taxonomy-grounded auditing is a practical route to more reliable optimization modeling.
### Title:
          WorldComp2D: Spatio-semantic Representations of Object Identity and Location from Local Views
 - **Authors:** SeongMin Jin, Doo Seok Jeong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning latent representations that capture both semantic and spatial information is central to efficient spatio-semantic reasoning. However, many existing approaches rely on implicit latent structures combined with dense feature maps or task-specific heads, limiting computational efficiency and flexibility. We propose WorldComp2D, a novel lightweight representation learning framework that explicitly structures latent space geometry according to object identity and spatial proximity using multiscale local receptive fields. This framework consists of (i) a proximity-dependent encoder that maps a given observation into a spatio-semantic latent space and (ii) a localizer that infers the coordinates of objects in the input from the resulting spatio-semantic representation. Using facial landmark localization as a proof-of-concept, we show that, compared to SoTA lightweight models, WorldComp2D reduces the numbers of parameters and FLOPs by up to 4.0X and 2.2X, respectively, while maintaining real-time performance on CPU. These results demonstrate that explicitly structured latent spaces provide an efficient and general foundation for spatio-semantic reasoning. This framework is open-sourced at this https URL.
### Title:
          BronchoLumen: Analysis of recent YOLO-based architectures for real-time bronchial orifice detection in video bronchoscopy
 - **Authors:** Yongchao Li, Marian Himstedt
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bronchoscopy is routinely conducted in pulmonary clinics and intensive care units, but navigating the complex branching of the respiratory tract remains challenging. This paper introduces BronchoLumen, a real-time YOLO-based system for detecting bronchial orifices in video bronchoscopy, aiming to assist navigation and CAD systems. The paper investigates if bronchial orifices can be robustly detected across image domains using state-of-the-art object detection and a limited set of public image data. The study includes the description and comparison of YOLOv8, a widely adopted architecture, and YOLOv12, a more recent architecture integrating attention-based modules to improve spatial reasoning. Both models are trained and tested solely on publicly available datasets comprising different image domains. A comparison of both models is conducted based on the common metrics mAP@0.5 and mAP@0.5:0.9 with the latter emphasizing localization accuracy. For YOLOv8 we obtained a mAP@0.5 of 0.91 on an in-domain and 0.68 on a cross-domain test set. YOLOv12 achieved 0.84 and 0.68 respectively with slightly better localization accuracy with mAP@0.5:0.9 of 0.48 and 0.26 compared to YOLOv8 with 0.45 and 0.25. Challenges like motion blur and low contrast occasionally entailed uncertainties but the system demonstrated overall robustness in most scenarios. BronchoLumen is an open-weight, YOLO-based solution for bronchial orifice detection offering high accuracy and efficiency across multiple image domains. While the more recent YOLOv12 achieves better localization accuracy, we observed a slightly worse precision. The models have been made publicly available to foster further research in bronchoscopy navigation.
### Title:
          An Extensive Replication Study of the ABLoTS Approach for Bug Localization
 - **Authors:** Feifei Niu, Enshuo Zhang, Christoph Mayr-Dorn, Wesley Klewerton Guez Assunção, Liguo Huang, Jidong Ge, Bin Luo, Alexander Egyed
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bug localization is the task of recommending source code locations (typically files) that contain the cause of a bug and hence need to be changed to fix the bug. Along these lines, information retrieval-based bug localization (IRBL) approaches have been adopted, which identify the most bug-prone files from the source code space. In current practice, a series of state-of-the-art IRBL techniques leverage the combination of different components (e.g., similar reports, version history, and code structure) to achieve better performance. ABLoTS is a recently proposed approach with the core component, TraceScore, that utilizes requirements and traceability information between different issue reports (i.e., feature requests and bug reports) to identify buggy source code snippets with promising results. To evaluate the accuracy of these results and obtain additional insights into the practical applicability of ABLoTS, we conducted a replication study of this approach with the original dataset and also on two extended datasets (i.e., additional Java dataset and Python dataset). The original dataset consists of 11 open source Java projects with 8,494 bug reports. The extended Java dataset includes 16 more projects comprising 25,893 bug reports and corresponding source code commits. The extended Python dataset consists of 12 projects with 1,289 bug reports. While we find that the TraceScore component, which is the core of ABLoTS, produces comparable or even better results with the extended datasets, we also find that we cannot reproduce the ABLoTS results, as reported in its original paper, due to an overlooked side effect of incorrectly choosing a cut-off date that led to test data leaking into training data with significant effects on performance.
### Title:
          EDGER: EDge-Guided with HEatmap Refinement for Generalizable Image Forgery Localization
 - **Authors:** Minh-Khoa Le-Phan, Minh-Hoang Le, Minh-Triet Tran, Trong-Le Do
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-guided inpainting has made image forgery increasingly realistic, challenging both SID and IFL. However, existing methods often struggle to point out suspicious signals across domains. To address this problem, we propose EDGER, a patch-based, dual-branch framework that localizes manipulated regions in arbitrary resolution images without sacrificing native resolution. The first branch, Edge-Guided Segmentation, introduces a Frequency-based Edge Detector to emphasize high-frequency inconsistencies at manipulation boundaries, and fine-tunes a SegFormer to fuse RGB and edge features for pixel-level masks. Since edge evidence is most informative only when patches contain both authentic and manipulated pixels, we complement Edge-Guided Segmentation with a Synthetic Heatmapping branch, a classification-based localizer that fine-tunes a CLIP-ViT image encoder with LoRA to flag fully synthetic patches. Together, Synthetic Heatmapping provides coarse, patch-level synthetic priors, while Edge-Guided Segmentation sharpens boundaries within partially manipulated patches, yielding comprehensive localization. Evaluated in the MediaEval 2025, SynthIM challenge, Manipulated Region Localization Task's setting, our approach scales to multi-megapixel imagery and exhibits strong cross-domain generalization. Extensive ablations highlight the complementary roles of frequency-based edge cues and patch-level synthetic priors in driving accurate, resolution-agnostic localization.
### Title:
          What-Where Transformer: A Slot-Centric Visual Backbone for Concurrent Representation and Localization
 - **Authors:** Ryota Yoshihashi, Masahiro Kada, Satoshi Ikehata, Rei Kawakami, Ikuro Sato
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many image understanding tasks involve identifying what is present and where it appears. However, tasks that address where, such as object discovery, detection, and segmentation, are often considerably more complex than image classification, which primarily focuses on what. One possible reason is that classification-oriented backbones tend to emphasize semantic information about what, while implicitly entangling or suppressing information about where. In this work, we focus on an inductive bias termed what-where separation, which encourages models to represent object appearance and spatial location in a decomposed manner. To incorporate this bias throughout an attentive backbone in the style of Vision Transformer (ViT), we propose the What-Where Transformer (WWT). Our method introduces two key novel designs: (1) it treats tokens as representations of what and attention maps as representations of where, and processes them in concurrent feed-forward modules via a multi-stream, slot-based architecture; (2) it reuses both the final-layer tokens and attention maps for downstream tasks, and directly exposes them to gradients derived from task losses, thereby facilitating more effective and explicit learning of localization. We demonstrate that even under standard single-label classification-based supervision on ImageNet, WWT exhibits emergent multiple object discovery directly from raw attention maps, rather than via additional postprocessing such as token clustering. Furthermore, WWT achieves superior performance compared to ViT-based methods on zero-shot object discovery and weakly supervised semantic segmentation, and it is transferable to various localization setups with minimal modifications. Code will be published after acceptance.
### Title:
          BARISTA: A Multi-Task Egocentric Benchmark for Compositional Visual Understanding
 - **Authors:** Patrick Knab, Orgest Xhelili, Inis Buzi, Drago Andres Guggiana Nilo, Mohd Saquib Khan, Lorenz Kolb, Manuel Scherzer, Kerem Yildirir, Christian Bartelt, Philipp Johannes Schubert
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scene understanding is central to general physical intelligence, and video is a primary modality for capturing both state and temporal dynamics of a scene. Yet understanding physical processes remains difficult, as models must combine object localization, hand-object interactions, relational parsing, temporal reasoning, and step-level procedural inference. Existing benchmarks usually evaluate these capabilities separately, limiting diagnosis of why models fail on procedural tasks. We introduce BARISTA, a densely annotated egocentric dataset and benchmark of 185 real-world coffee-preparation videos covering fully automatic, portafilter-based, and capsule-based workflows. BARISTA provides verified per-frame scene graphs linking persistent object identities to masks, tracks, boxes, attributes, typed relations, hand-object interactions, activities, and process steps. From these graphs, we derive zero-shot language-based tasks spanning phrase grounding, hand-object interaction recognition, referring, activity recognition, relation extraction, and temporal visual question answering. Experiments reveal strong variation across task families and no consistently dominant model family, positioning BARISTA as a challenging diagnostic benchmark for procedural video understanding. Code and dataset available at this https URL.
### Title:
          PoseCompass: Intelligent Synthetic Pose Selection for Visual Localization
 - **Authors:** Yanan Zhou, Zhaoyan Qian, Yanli Li, Nan Yang, Zhongliang Guo, Dong Yuan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In visual localization, Absolute Pose Regression (APR) enables real-time 6-DoF camera pose inference from single images, yet critically depends on fine-tuning data quality and coverage. While recent methods leverage 3D Gaussian Splatting (3DGS) for novel view synthesis-based data augmentation, random sampling generates redundant views and noisy samples from poorly reconstructed regions. To mitigate this research gap, we propose PoseCompass, an intelligent pose selection pipeline for 3DGS-based APR. PoseCompass formulates synthetic pose selection and derives a value-based pose ranking mechanism to identify informative poses. The ranking integrates three dimensions: Localization Difficulty, favoring challenging regions; Coverage Novelty, exploring under-sampled areas; and Rendering Observability, filtering artifacts and noise. PoseCompass then generates trajectory-constrained candidates, selects the top-K ranked poses, and synthesizes views using 3DGS with lightweight diffusion-based alignment. Finally, the pose regressor is fine-tuned on mixed real and synthetic data. We evaluate PoseCompass on 7-Scenes, where it reduces adaptation time from 15.2 to 5.1 minutes, a 3x speedup, while cutting median pose errors by 53.8 percent and significantly outperforming random baselines.
### Title:
          Cross-Modal-Domain Generalization Through Semantically Aligned Discrete Representations
 - **Authors:** Souptik Sen, Raneen Younis, Zahra Ahmadi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal learning seeks to integrate information across diverse sensory sources, yet current approaches struggle to balance cross-modal generalizability with modality-specific structure. Continuous (implicit) methods preserve fine-grained priors but render generalization challenging, while discrete (explicit) approaches enforce shared prototypes at the expense of modality specificity. We introduce CoDAAR (Cross-modal Discrete Alignment And Reconstruction), a novel framework that resolves this long-standing trade-off by establishing semantic consensus across modality-specific codebooks through index-level alignment. This design uniquely allows CoDAAR to preserve modality-unique structures while achieving generalizable cross-modal representations within a unified discrete space. CoDAAR combines two complementary mechanisms: Discrete Temporal Alignment (DTA), which enables fine-grained temporal quantization, and Cascading Semantic Alignment (CSA), which promotes progressive cross-modal semantic agreement. Together, they establish a competition-free unified representation space. Trained with self-supervised reconstruction objectives on paired multimodal sequences, CoDAAR demonstrates robust cross-modal and cross-domain generalization. Across Cross-Modal Generalization benchmarks, including event classification, localization, video segmentation, and cross-dataset transfer, CoDAAR achieves state-of-the-art performance, establishing a new paradigm for discrete and generalizable multimodal representation learning.
### Title:
          From Image Hashing to Scene Change Detection
 - **Authors:** Anh-Kiet Duong, Marie-Claire Iatrides, Petra Gomez-Krämer, Jean-Michel Carozza
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Image hashing provides compact representations for efficient storage and retrieval but is inherently limited to global comparison and cannot reason about where changes occur. This limitation prevents hashing from being directly applicable to scene change detection, where spatial localization is essential. In this work, we revisit hashing from a scene change detection perspective and propose HashSCD, a patch-wise hashing framework that enables both efficient global change detection and localized change identification. HashSCD encodes spatially aligned patches into compact hash codes and aggregates them through an XOR-like operation, allowing change detection and localization to be performed directly in the Hamming space without repeated inference on previous images. The model is trained in an unsupervised manner using contrastive learning at both patch and global levels. Experiments demonstrate that HashSCD achieves competitive performance compared to state-of-the-art unsupervised hashing and scene change detection methods, while significantly reducing computational cost and storage requirements.
### Title:
          Characterizing the Failure Modes of LLMs in Resolving Real-World GitHub Issues
 - **Authors:** Yanjie Jiang, Yian Huang, Guancheng Wang, Junjie Chen, Hui Liu, Lionel Briand
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) are increasingly deployed to resolve real-world GitHub issues. However, despite their potential, the specific failure modes of these models in complex repair tasks remain poorly understood. To characterize how LLM behavior diverges from human developer practices, this paper evaluates three state-of-the-art models, i.e., Claude 4.5 Sonnet, Gemini 3 Pro, and GPT-5, on the SWE-bench Verified dataset. We conduct a rigorous manual analysis of the symptoms and root causes underlying 243 failed attempts across 900 total trials. Our investigation first yields a unified failure taxonomy encompassing five distinct stages of the repair pipeline, within which we categorize typical failure symptoms and their prevalence. Secondly, our findings reveal that for all evaluated LLMs, strategy formulation and logic synthesis constitutes the most error-prone stage, followed by problem understanding, whereas localization exhibits the lowest failure rate. This suggests that LLMs may excel at fault localization, a task traditionally regarded as one of the most formidable challenges in automated program repair. Furthermore, we observe that robustness and operational costs (particularly in failure scenarios) vary significantly across different models. Finally, we uncover the root causes of these failures and propose actionable strategies to mitigate them. A particularly notable finding is that existing evaluation harnesses occasionally misjudge correct patches due to superficial discrepancies or hidden constraints. Collectively, our insights may provide promising directions for enhancing the effectiveness and reliability of LLM-based issue resolution.
### Title:
          Large-Small Model Collaboration for Farmland Semantic Change Detection
 - **Authors:** Xinjia Li, Rui Wang, Qiurong Peng, Lingfei Ye, Dengrong Zhang, Haoyu Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Farmland Semantic Change Detection (SCD) is essential for cultivated land protection, yet existing benchmarks and models remain insufficient for fine-grained farmland conversion monitoring. Current datasets often lack dedicated "from-to" annotations, while visual change detection models are easily disturbed by phenology-induced pseudo-changes caused by crop rotation, seasonal variation, and illumination differences. To address these challenges, we construct HZNU-FCD, a large-scale fine-grained farmland SCD benchmark with a unified five-class farmland-to-non-farmland annotation protocol. It contains 4,588 bitemporal image pairs with pixel-level labels for practical farmland protection. Based on this benchmark, we propose a large-small collaborative SCD framework that integrates a task-driven small visual model with a frozen large vision-language model. The small model, Fine-grained Difference-aware Mamba (FD-Mamba), learns dense change representations for boundary preservation and small-region localization. The large-model pathway, Cross-modal Logical Arbitration (CMLA), introduces CLIP-based textual priors for prompt-guided semantic arbitration and pseudo-change suppression. To enable effective collaboration, we design a hard-region co-training strategy that supervises the CMLA semantic score map only on low-confidence pixels. Experiments show that our method achieves 97.63% F1, 96.32% IoU, and 96.35% SCD_IoU_mean on HZNU-FCD with only 6.65M trainable parameters. Compared with the multimodal ChangeCLIP-ViT, which leverages vision-language information for change detection, our method improves F1 by 10.19 percentage points on HZNU-FCD. It also achieves 91.43% F1 and 84.21% IoU on LEVIR-CD, and 93.85% F1 and 88.41% IoU on WHU-CD, demonstrating strong robustness and generalization. The code is available at this https URL.
### Title:
          From Model Uncertainty to Human Attention: Localization-Aware Visual Cues for Scalable Annotation Review
 - **Authors:** Moussa Kassem Sbeyti, Joshua Holstein, Philipp Spitzer, Nadja Klein, Gerhard Satzger
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-quality labeled data is essential for training robust machine learning models, yet obtaining annotations at scale remains expensive. AI-assisted annotation has therefore become standard in large-scale labeling workflows. However, in tasks where model predictions carry two independent components, a class label and spatial boundaries, a model may classify an object with high confidence while mislocalizing it. Existing AI-assisted workflows offer annotators no signal about where spatial errors are most likely. Without such guidance, humans may systematically underinspect subtly misplaced boxes. We address this by studying the effect of visualizing spatial uncertainty via a purpose-built interface. In a controlled study with 120 participants, those receiving uncertainty cues achieve higher label quality while being faster overall. A box-level analysis confirms that the cues redirect annotator effort toward high-uncertainty predictions and away from well-localized boxes. These findings establish localization uncertainty as a lever to improve human-in-the-loop annotation. Code is available at this https URL.
### Title:
          TextSeal: A Localized LLM Watermark for Provenance & Distillation Protection
 - **Authors:** Tom Sander, Hongyan Chang, Tomáš Souček, Tuan Tran, Valeriu Lacatusu, Sylvestre-Alvise Rebuffi, Alexandre Mourachko, Surya Parimi, Christophe Ropers, Rashel Moritz, Vanessa Stark, Hady Elsahar, Pierre Fernandez
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce TextSeal, a state-of-the-art watermark for large language models. Building on Gumbel-max sampling, TextSeal introduces dual-key generation to restore output diversity, along with entropy-weighted scoring and multi-region localization for improved detection. It supports serving optimizations such as speculative decoding and multi-token prediction, and does not add any inference overhead. TextSeal strictly dominates baselines like SynthID-text in detection strength and is robust to dilution, maintaining confident localized detection even in heavily mixed human/AI documents. The scheme is theoretically distortion-free, and evaluation across reasoning benchmarks confirms that it preserves downstream performance; while a multilingual human evaluation (6000 A/B comparisons, 5 languages) shows no perceptible quality difference. Beyond its use for provenance detection, TextSeal is also ``radioactive'': its watermark signal transfers through model distillation, enabling detection of unauthorized use.
## Keyword: transformer
### Title:
          Vertex-Softmax: Tight Transformer Verification via Exact Softmax Optimization
 - **Authors:** Navid Rezazadeh, Arash Gholami Davoodi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Certified verification of transformer attention requires bounding the softmax function over interval constraints on the pre-softmax scores. Existing verifiers relax softmax ndependently of the downstream objective, leaving avoidable slack. We prove that the exact optimum of this score-box problem is attained at a vertex of the constraint box, and establish a threshold structure theorem showing that, after sorting the objective coefficients, the optimum lies among only linearly many candidates, yielding the Vertex-Softmax primitive with log-linear complexity in the sequence length. We further prove a formal optimality result showing that Vertex-Softmax is the tightest sound bound obtainable from score intervals alone, characterizing precisely what additional structure (score correlations, score-value coupling) is needed for further improvement. Integrated into a CROWN Convex Relaxation based Optimization for Worst-case Neurons)-style verifier with a formal soundness guarantee, Vertex-Softmax significantly improves certified rates and substantially tightens lower bounds across MNIST, Fashion-MNIST, and CIFAR-10 attention models, while consistently matching or outperforming alpha-CROWN and branch-and-bound baselines at a fraction of their cost.
### Title:
          RT-Transformer: The Transformer Block as a Spherical State Estimator
 - **Authors:** Peter Racioppo
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We show that the core components of the Transformer block -- attention, residual connections, and normalization -- arise naturally from a single geometric estimation problem. Modeling the latent state as a direction on the hypersphere, with noise defined in the tangent plane at the current estimate, yields a precision-weighted directional inference procedure in which attention aggregates evidence, residual connections implement incremental state updates, and normalization retracts the updated state back onto the hypersphere. Together, these components follow from the geometry of the estimation problem rather than being introduced as independent architectural choices.
### Title:
          ACSAC: Adaptive Chunk Size Actor-Critic with Causal Transformer Q-Network
 - **Authors:** Qian Chen, Junqiao Zhao, Hongtu Zhou, Hang Yu, Yanping Zhao, Chen Ye, Guang Chen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long-horizon, sparse-reward tasks pose a fundamental challenge for reinforcement learning, since single-step TD learning suffers from bootstrapping error accumulation across successive Bellman updates. Actor-critic methods with action chunking address this by operating over temporally extended actions, which reduce the effective horizon, enable fast value backups, and support temporally consistent exploration. However, existing methods rely on a fixed chunk size and therefore cannot adaptively balance reactivity against temporal consistency. A large fixed chunk size reduces responsiveness to new observations, while a small one produces incoherent motions, forcing task-specific tuning of the chunk size. To address this limitation, we propose Adaptive Chunk Size Actor-Critic (ACSAC). ACSAC leverages a causal Transformer critic to evaluate expected returns for action chunks of different sizes. At each chunk boundary, it adaptively selects the chunk size that maximizes the expected return, supporting flexible, state-dependent chunk sizes without task-specific tuning. We prove that the ACSAC Bellman operator is a contraction whose unique fixed point is the action-value function of the adaptive policy. Experiments on OGBench demonstrate that ACSAC achieves state-of-the-art performance on long-horizon, sparse-reward manipulation tasks across both offline RL and offline-to-online RL settings.
### Title:
          HiDream-O1-Image: A Natively Unified Image Generative Foundation Model with Pixel-level Unified Transformer
 - **Authors:** Qi Cai, Jingwen Chen, Chengmin Gao, Zijian Gong, Yehao Li, Yingwei Pan, Yi Peng, Zhaofan Qiu, Kai Yu, Yiheng Zhang, Hao Ai, Siying Bai, Yang Chen, Zhihui Chen, Fengbin Gao, Ying Guo, Dong Li, Zhen Shen, Leilei Shi, Jing Wang, Siyu Wang, Yimeng Wang, Rui Zheng, Ting Yao, Tao Mei
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The evolution of visual generative models has long been constrained by fragmented architectures relying on disjoint text encoders and external VAEs. In this report, we present HiDream-O1-Image, a natively unified generative foundation model via pixel-space Diffusion Transformer, that pioneers a paradigm shift from modular architectures to an end-to-end in-context visual generation engine. By mapping raw image pixels, text tokens, and task-specific conditions into a single shared token space, HiDream-O1-Image achieves a structural unification of multimodal inputs within an Unified Transformer (UiT) architecture. This native encoding paradigm eliminates the need for separate VAEs or disjoint pre-trained text encoders, allowing the model to treat diverse generation and editing tasks as a consistent in-context reasoning process. Extensive experiments show that HiDream-O1-Image excels across various generation tasks, including text-to-image generation, instruction-based editing, and subject-driven personalization. Notably, with only 8B parameters, HiDream-O1-Image (8B) achieves performance parity with or even surpasses established state-of-the-art models with significantly larger parameters (e.g., 27B Qwen-Image). Crucially, to validate the immense scalability of this paradigm, we successfully scale the architecture up to over 200B parameters. Experimental results demonstrate that this massive-scale version HiDream-O1-Image-Pro (200B+) unlocks unprecedented generative capabilities and superior performance, establishing new state-of-the-art benchmarks. Ultimately, HiDream-O1-Image highlights the immense potential of natively unified architectures and charts a highly scalable path toward next-generation multimodal AI.
### Title:
          ASD-Bench: A Four-Axis Comprehensive Benchmark of AI Models for Autism Spectrum Disorder
 - **Authors:** Shubhankit Singh, Hassan Shaikh, Kuldeep Raghuwanshi, Keshav Bulia
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated ASD screening tools remain limited by single-architecture evaluations, axis-restricted assessment, and near-exclusive focus on adult cohorts, obscuring age-specific diagnostic patterns critical for early intervention. We introduce ASD-Bench, a systematic tabular benchmark evaluating ML, deep learning, and foundation model configurations across three age cohorts (children 1-11 yr, adolescents 12-16 yr, adults 17-64 yr) on four axes: predictive performance, calibration, interpretability, and adversarial robustness. Applied to a curated v3 dataset of 4,068 AQ-10 records, our benchmark spans classical models (XGBoost, AdaBoost, Random Forest, Logistic Regression), neural networks (MLP), deep tabular transformers (TabNet, TabTransformer, FT-Transformer), and TabPFN v2. We introduce the Heuristic Aggregate Penalty (HAP): a cost-sensitive metric penalising false negatives more heavily and incorporating cross-validation variance for deployment stability. Adult classification yields high performance (10/17 models achieve perfect F1 and AUC), while adolescents present a harder task (F1 ceiling 0.837 vs. 0.915 for children). Feature hierarchies shift across cohorts: A9 (social motivation) dominates for children, A5 (pattern recognition) leads for adolescents, and adults exhibit a flatter importance profile consistent with developmental social masking. Accuracy and calibration are dissociated: AdaBoost achieves F1=1.000 on adults with ECE=0.302, confirming single-metric evaluation is insufficient for clinical AI. Cohort-specific deployment recommendations are provided. All findings should be interpreted as proof-of-concept evidence on questionnaire-derived labels rather than clinically validated diagnostic performance.
### Title:
          HEPA: A Self-Supervised Horizon-Conditioned Event Predictive Architecture for Time Series
 - **Authors:** Jonas Petersen (1 and 2), Gian-Alessandro Lombardi (2), Riccardo Maggioni (2), Camilla Mazzoleni (2), Federico Martelli (1 and 2), Philipp Petersen (3) ((1) ETH Zurich, (2) Forgis, (3) University of Vienna)
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Critical events in multivariate time series, from turbine failures to cardiac arrhythmias, demand accurate prediction, yet labeled data is scarce because such events are rare and costly to annotate. We introduce HEPA (Horizon-conditioned Event Predictive Architecture), built on two key principles. First, a causal Transformer encoder is pretrained via a Joint-Embedding Predictive Architecture (JEPA): a horizon-conditioned predictor learns to forecast future representations rather than future values, forcing the encoder to capture predictable temporal dynamics from unlabeled data alone. Second, we freeze the encoder and finetune only the predictor toward the target event, producing a monotonic survival cumulative distribution function (CDF) over horizons. With fixed architecture and optimiser hyperparameters across all benchmarks, HEPA handles water contamination, cyberattack detection, volatility regimes, and eight further event types across 11 domains, exceeding leading time-series architectures including PatchTST, iTransformer, MAE, and Chronos-2 on at least 10 of 14 benchmarks, with an order of magnitude fewer tuned parameters and, on lifecycle datasets, an order of magnitude less labeled data.
### Title:
          USEMA: a Scalable Efficient Mamba Like Attention for Medical Image Segmentation
 - **Authors:** Elisha Dayag, Nhat Thanh Tran, Jack Xin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate medical image segmentation is an integral part of the medical image analysis pipeline that requires the ability to merge local and global information. While vision transformers are able to capture global interactions using vanilla self-attention, their quadratic computational complexity in the input size remains a struggle for medical image segmentation tasks. Motivated by the dispersion property of vanilla self-attention and recent development of Mamba form of attention, Scalable and Efficient Mamba like Attention (SEMA) utilizes token localization via local window attention to avoid dispersion and maintain focusing, complemented by theoretically consistent arithmetic averaging to capture global aspect of attention. In this work, we present USEMA, a hybrid UNet architecture that merges the local feature extraction ability of convolutional neural networks (CNNs) with SEMA attention. We conduct experiments with USEMA across a variety of modalities and image sizes, demonstrating improved computational efficiency compared to transformer based models using full self-attention, and superior segmentation performance relative to purely convolution and Mamba-based models.
### Title:
          FeatMap: Understanding image manipulation in the feature space and its implications for feature space geometry
 - **Authors:** Elias B. Krey, Nils Neukirch, Nils Strodthoff
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Intermediate feature representations represent the backbone for the expressivity and adaptability of deep neural networks. However, their geometric structure remains poorly understood. In this submission, we provide indirect insights into this matter by applying a broad selection of manipulations in input space, ranging from geometric and photometric transformations to local masking and semantic manipulations using generative image editing models, and assess the feasibility of learning a mapping in the feature space, mapping from the original to the manipulated feature map. To this end, we devise different types of mappings, from linear to non-linear and local to global mappings and assess both the reconstruction quality of the mapping as well as the semantic content of the mapped representations. We demonstrate the feasibility of learning such mappings for all considered transformations. While global (transformer) models that operate on the full feature map often achieve best results, we show that the same can be achieved with a shared linear model operating on a single feature vector typically with very little degradation in reconstruction quality, even for highly non-trivial semantic manipulations. We analyze the corresponding mappings across different feature layers and characterize them according to dominance of weight vs. bias and the effective rank of the linear transformations. These results provide hints for the hypothesis that the feature space is to a first degree of approximation organized in linear structures. From a broader perspective, the study demonstrates that generative image editing models might open the door to a deeper understanding of the feature space through input manipulation.
### Title:
          Latent Chain-of-Thought Improves Structured-Data Transformers
 - **Authors:** Carson Dudley, Samet Oymak
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Chain-of-thought and more broadly test-time compute are known to augment the expressive capabilities of language models and have led to major innovations in reasoning. Motivated by this success, this paper explores latent chain-of-thought as well as the impact of depth and looping for time-series and tabular data. We propose a recurrent scheme in which a structured-data transformer, after an initial forward pass, compresses its query-position hidden states into feedback tokens that are appended to the input and processed again, allowing multiple rounds of latent computation before prediction. We compare CoT models against a same-depth no-CoT baseline, a deeper baseline matched to the CoT model in effective depth, and a looped transformer with weight-tied recurrence but no additional chain-of-thought tokens. Across 36 datasets in time-series forecasting and tabular prediction, latent chain-of-thought improves over the baseline on 8/9 time-series datasets (+10.99\% average gain) and 22/27 tabular datasets (+5.31\% average gain). Across both settings, the CoT models perform the best on average. These results demonstrate that chain-of-thought is a useful axis for scaling test-time compute for structured data.
### Title:
          Beyond Similarity: Temporal Operator Attention for Time Series Analysis
 - **Authors:** Jevon Twitty, Vinh Pham, Nitiwith Rotchanarak, Viresh Pati, Yubin Kim, Shihao Yang, Jiecheng Lu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A persistent paradox in time-series forecasting is that structurally simple MLP and linear models often outperform high-capacity Transformers. We argue that this gap arises from a mismatch in the sequence-modeling primitive: while many time-series dynamics are governed by global temporal operators (e.g., filtering and harmonic structure), standard attention forms each output as a convex combination of inputs. This restricts its ability to represent signed and oscillatory transformations that are fundamental to temporal signal processing. We formalize this limitation as a simplex-constrained mixing bottleneck in softmax attention, which becomes especially restrictive for operator-driven time-series tasks. To address this, we propose $\textbf{Temporal Operator Attention (TOA)}$, a framework that augments attention with explicit, learnable sequence-space operators, enabling direct signed mixing across time while preserving input-dependent adaptivity. To make dense $N \times N$ operators practical, we introduce Stochastic Operator Regularization, a high-variance dropout mechanism that stabilizes training and prevents trivial memorization. Across forecasting, anomaly detection, and classification benchmarks, TOA consistently improves performance when integrated into standard backbones such as PatchTST and iTransformer, with particularly strong gains in reconstruction-heavy tasks. These results suggest that explicit operator learning is a key ingredient for effective time-series modeling.
### Title:
          ChunkFlow: Communication-Aware Chunked Prefetching for Layerwise Offloading in Distributed Diffusion Transformer Inference
 - **Authors:** Han Meng (University of California, Merced), Danny Willow Liu (University of Chicago), Dong Li (University of California, Merced and Yotta Labs)
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Layerwise offloading reduces the GPU memory footprint of large diffusion transformer (DiT) inference by prefetching upcoming layers from host memory, but its effectiveness hinges on hiding prefetch latency behind per-layer computation. This assumption breaks down when the per-GPU compute workload is small. Moreover, on PCIe-only nodes, prefetch and inter-GPU collective communications such as all-reduce and all-to-all contend on the shared PCIe path, exposing prefetch latency even when compute would otherwise hide it. We revisit layerwise offloading as a co-scheduling problem between prefetch and communication, guided by a first-order analytical model that predicts when prefetch can be hidden by computation. Building on this model, we design ChunkFlow, a communication-aware, chunk-granular offloading runtime that adaptively yields to collective communication and smoothly trades GPU memory for prefetch volume. On three representative diffusion transformers running on two H100 GPUs over PCIe with Ulysses sequence parallelism, ChunkFlow delivers up to 1.28x step-time speedup over SGLang's existing layerwise offloading, reduces peak GPU memory by up to 49% over the no-offload baseline at near-identical step time once the workload is large enough, and exposes a tunable memory-latency tradeoff that recovers near-zero step-time overhead in the small-workload regime.
### Title:
          Lite3R: A Model-Agnostic Framework for Efficient Feed-Forward 3D Reconstruction
 - **Authors:** Haoyu Zhang, Zeyu Zhang, Zedong Zhou, Yang Zhao, Hao Tang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based 3D reconstruction has emerged as a powerful paradigm for recovering geometry and appearance from multi-view observations, offering strong performance across challenging visual conditions. As these models scale to larger backbones and higher-resolution inputs, improving their efficiency becomes increasingly important for practical deployment. However, modern 3D transformer pipelines face two coupled challenges: dense multi-view attention creates substantial token-mixing overhead, and low-precision execution can destabilize geometry-sensitive representations and degrade depth, pose, and 3D consistency. To address the first challenge, we propose Lite3R, a model-agnostic teacher-student framework that replaces dense attention with Sparse Linear Attention to preserve important geometric interactions while reducing attention cost. To address the second challenge, we introduce a parameter-efficient FP8-aware quantization-aware training (FP8-aware QAT) strategy with partial attention distillation, which freezes the vast majority of pretrained backbone parameters and trains only lightweight linear-branch projection layers, enabling stable low-precision deployment while retaining pretrained geometric priors. We further evaluate Lite3R on two representative backbones, VGGT and DA3-Large, over BlendedMVS and DTU64, showing that it substantially reduces latency (1.7-2.0x) and memory usage (1.9-2.4x) while preserving competitive reconstruction quality overall. These results demonstrate that Lite3R provides an effective algorithm-system co-design approach for practical transformer-based 3D reconstruction. Code: this https URL. Website: this https URL.
### Title:
          gym-invmgmt: An Open Benchmarking Framework for Inventory Management Methods
 - **Authors:** Reza Barati, Qinmin Vivian Hu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Inventory-policy comparisons are often difficult to interpret because performance depends on the evaluation contract as much as on the policy itself. Differences in topology, demand regime, information access, feasibility constraints, shortage treatment, and Key Performance Indicator (KPI) definitions can change method rankings. We present gym-invmgmt, a Gymnasium-compatible extension of the OR-Gym inventory-management lineage for auditable cross-paradigm evaluation. The benchmark evaluates optimization, heuristic, and learned controllers under a shared CoreEnv transition, reward, action-bound, and KPI contract, while varying stress conditions through a 22-scenario core grid plus four supplemental MARL-mode rows. Within these released scenarios, informed stochastic programming provides the strongest non-oracle reference, reflecting the value of scenario hedging under forecast access, but at substantially higher online computational cost. Among learned controllers, the Proximal Policy Optimization Transformer variant (PPO-Transformer) achieves the strongest learned-policy quality at fast inference, while Residual Reinforcement Learning (Residual RL) provides competitive hybrid performance. The graph neural network variant (PPO-GNN) is highly competitive on the default divergent topology but less robust on the serial topology. Imitation learning performs well in stationary regimes but degrades under demand shift, and the bounded Large Language Model (LLM) policy-parameter baseline is best interpreted as a diagnostic controller rather than an autonomous inventory optimizer. Overall, the benchmark identifies scenario-conditioned leaders while showing that performance depends jointly on information access, demand shift, topology, and policy representation.
### Title:
          Transformer Interpretability from Perspective of Attention and Gradient
 - **Authors:** Yongjin Cui, Xiaohui Fan, Huajun Chen
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Although researchers' attention is more focused on the performance of Transformer models, the interpretation of Transformer can never be ignored. Gradient is widely utilized in Transformer interpretation. From the perspective of attention and gradient, we conduct an in-depth study of Transformer interpretation and propose a method to achieve it by guiding the gradient direction, or more precisely, the attention direction. The method enables more comprehensive interpretation of feature regions, offers detail interpretation, and helps to better understand Transformer mechanism. Leveraging the difference in how Vision Transformer (ViT) and humans perceive images, we alter the class of an image in a way that is almost imperceptible to the human eye. This class rewriting phenomenon may potentially pose security risks in certain scenarios.
### Title:
          STRIDE: Training-Free Diversity Guidance via PCA-Directed Feature Perturbation in Single-Step Diffusion Models
 - **Authors:** Ankit Yadav, Arpit Garg, Ta Duc Huy, Lingqiao Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Distilled one-step (T=1) or few-step (T$\leq$4) diffusion models enable real-time image generation but often exhibit reduced sample diversity compared to their multi-step counterparts. In multi-step diffusion, diversity can be introduced through schedules, trajectories, or iterative optimization; however, these mechanisms are unavailable in the few-step or single-step setting, limiting the effectiveness of existing diversity-enhancing methods. A natural alternative is to perturb intermediate features, but naive feature perturbation is often ineffective, either yielding limited diversity gains or degrading generation quality. We argue that effective diversity injection in few-step models requires perturbations that respect the model's learned feature geometry. Based on this insight, we propose STRIDE, a training-free and optimization-free method that operates in a single forward pass. STRIDE injects spatially coherent (pink) noise into intermediate transformer features, projected onto the principal components of the model's own activations, ensuring that perturbations lie on the learned feature manifold. This design enables controlled variation along meaningful directions in the representation space. Extensive experiments on FLUX.1-schnell and SD3.5 Turbo across COCO, DrawBench, PartiPrompts, and GenEval show that STRIDE consistently improves diversity while maintaining strong text alignment. In particular, STRIDE reduces intra-batch similarity with minimal impact on CLIP score, and Pareto-dominates existing training-free baselines on the diversity-fidelity frontier. These results highlight that, in the absence of iterative refinement, improving diversity in few-step and one-step diffusion depends not on increasing perturbation strength, but on aligning perturbations with the model's internal representation structure.
### Title:
          Weather-Robust Cross-View Geo-Localization via Prototype-Based Semantic Part Discovery
 - **Authors:** Chi-Nguyen Tran, Dao Sy Duy Minh, Huynh Trung Kiet, Nguyen Lam Phu Quy, Phu-Hoa Pham, Long Tran-Thanh
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-view geo-localization (CVGL), which matches an oblique drone view to a geo-referenced satellite tile, has emerged as a key alternative for autonomous drone navigation when GNSS signals are jammed, spoofed, or unavailable. Despite strong recent progress, three limitations persist: (1) global-descriptor designs compress the patch grid into a single vector without separating layout from texture across the view gap; (2) altitude-related scale variation is retained in the learned embedding rather than marginalized; and (3) multi-objective training relies on hand-tuned scalars over losses on incompatible gradient scales. We propose SkyPart, a lightweight swappable head for patch-based vision transformers (ViTs) that institutes explicit part grouping over the patch grid. SkyPart has four theory-grounded components: (i) learnable prototypes competing for patch tokens via single-pass cosine assignment; (ii) altitude-conditioned linear modulation applied only during training, making the retrieval embedding altitude-free at inference; (iii) a graph-attention readout over active prototypes; and (iv) a Kendall uncertainty-weighted multi-objective loss whose stationary points are Pareto-stationary. At 26.95M parameters and 22.14 GFLOPs, SkyPart is the smallest among top-performing methods and sets a new state of the art on SUES-200, University-1652, and DenseUAV under a single-pass, no-re-ranking, no-TTA protocol. Its advantage over the strongest baseline widens under the ten-condition WeatherPrompt corruption benchmark.
### Title:
          DORA: Dynamic Online Reinforcement Agent for Token Merging in Vision Transformers
 - **Authors:** Kaixuan He, Song Chen, Yi Kang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformers (ViTs) incur significant computational overhead due to the quadratic complexity of self-attention relative to the token sequence length. While existing token reduction methods mitigate this issue, they predominantly rely on fixed heuristic metrics, predefined ratios, or static offline masks, which lack the adaptability to capture input-dependent redundancy during inference. In this paper, we propose DORA (Dynamic Online Reinforcement Agent), the first reinforcement learning (RL)-driven online inference framework for dynamic token merging in ViTs. We formulate the merging process as a sequential Markov Decision Process (MDP), where a lightweight RL agent determines the merging strategy for each Transformer block based on the current feature state and layer-specific context. To balance computational efficiency and feature fidelity, the agent is optimized via a dense reward function incorporating a non-linear distillation-based penalty. We implement an asymmetric Actor-Critic architecture that utilizes a high-capacity Critic for stable offline training while retaining a minimal Actor head for low-computation online inference. Evaluations across multiple ViT scales (Tiny to Large) demonstrate that DORA improves the accuracy-efficiency Pareto front compared to current baselines. Under strict negligible accuracy-drop constraints (<= 0.05%), DORA achieves up to a 12.66% token merging rate, and delivers up to a 569.7% relative improvement over the most efficient baseline. On ImageNet-1K, under aligned accuracy constraints, DORA achieves up to a 76% relative improvement in computational savings compared to state-of-the-art methods. Furthermore, on out-of-distribution (OOD) benchmarks such as ImageNet-A and ImageNet-C, DORA attains a relative efficiency advantage of over 430%.
### Title:
          Unlocking Compositional Generalization in Continual Few-Shot Learning
 - **Authors:** Phu-Quy Nguyen-Lam, Phu-Hoa Pham, Dao Sy Duy Minh, Chi-Nguyen Tran, Huynh Trung Kiet, Long Tran-Thanh
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Object-centric representations promise a key property for few-shot learning: Rather than treating a scene as a single unit, a model can decompose it into individual object-level parts that can be matched and compared across different concepts. In practice, this potential is rarely realized. Continual learners either collapse scenes into global embeddings, or train with part-level matching objectives that tie representations too closely to seen patterns, leaving them unable to generalize to truly novel concepts. In this paper, we identify this fundamental structural conflict and pioneer a new paradigm that strictly decouples representation learning from compositional inference. Leveraging the inherent patch-level semantic geometry of self-supervised Vision Transformers (ViTs), our framework employs a dual-phase strategy. During training, slot representations are optimized entirely toward holistic class identity, preserving highly generalizable, object-level geometries. At inference, preserved slots are dynamically composed to match novel scenes. We demonstrate that this paradigm offers dual structural benefits: The frozen backbone naturally prevents representation drift, while our lightweight, holistic optimization preserves the features' capacity for novel-concept transfer. Extensive experiments validate this approach, achieving state-of-the-art unseen-concept generalization and minimal forgetting across standard continual learning benchmarks.
### Title:
          Toward Stable Value Alignment: Introducing Independent Modules for Consistent Value Guidance
 - **Authors:** Wenhao Chen, Sirui Sun, Shengyuan Bai, Guojie Song
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Aligning large language models (LLMs) with human values typically relies on post-training or inference-time steering that directly manipulates the backbone's parameters or representation space. However, a critical gap exists: the model's residual stream is highly dynamic, in which values exist as fragile, low-dimensional properties, inherently incompatible with the stability required for consistent value expression. In this paper, we propose the Stable Value Guidance Transformer (SVGT), which addresses this gap through an independent value module incorporating two key designs: (1) independent value modeling, maintaining normative representations in a dedicated value space isolated from the backbone, and (2) explicit behavioral guidance, transducing these stable signals into learnable latent Bridge Tokens. These tokens serve as dynamic value anchors to explicitly steer the generative trajectory, ensuring robust adherence across diverse contexts without disrupting the backbone's internal representations. Experiments across multiple backbones and safety benchmarks show that SVGT generally reduces harmful scores by over 70% while maintaining generation fluency, demonstrating the efficacy of architecturally grounded value modeling. Our code is available at this https URL.
### Title:
          Training-Inference Consistent Segmented Execution for Long-Context LLMs
 - **Authors:** Xianpeng Shang, Jiang Li, Zehua Duo, Qianyi Cai, Xiangdong Su
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based large language models face severe scalability challenges in long-context generation due to the computational and memory costs of full-context attention. Under practical computation and memory constraints, many inference-efficient long-context methods improve efficiency by adopting bounded-context or segment-level execution only during inference, while continuing to train models under full-context attention, resulting in a mismatch between training and inference execution and state-transition semantics. Based on this insight, we propose a training-inference consistent segment-level generation framework, in which training and inference follow the same segment-level forward execution semantics. During training, consistency with inference is enforced by restricting gradient propagation to KV states carried over from the immediately preceding segment, while permitting head-specific access to past KV states during the forward pass without involving them in gradient propagation. Across long-context benchmarks, our approach achieves performance comparable to full-context attention, while achieving competitive latency-memory trade-offs against strong inference-efficient baselines, and substantially improving scalability at very long context lengths (e.g., approximately 6x lower peak prefill memory at 128K compared to full-context attention with FlashAttention).
### Title:
          Towards Visually Grounded Multimodal Summarization via Cross-Modal Transformer and Gated Attention
 - **Authors:** Abid Ali, Diego Molla-Aliod, Usman Naseem
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal summarization requires models to jointly understand textual and visual inputs to generate concise, semantically coherent summaries. Existing methods often inject shallow visual features into deep language models, leading to representational mismatches and weak cross-modal grounding. We propose a unified framework that jointly performs text summarization and representative image selection. Our system, SPeCTrA-Sum (Sampler Perceiver with Cross-modal Transformer and gated Attention for Summarization), introduces two key innovations. First, a Deep Visual Processor (DVP) aligns the visual encoder with the language model at corresponding depths, enabling hierarchical, layer-wise fusion that preserves semantic consistency. Second, a lightweight Visual Relevance Predictor (VRP) selects salient and diverse images by distilling soft labels from a Determinantal Point Processes (DPP) teacher. SPeCTrA-Sum is trained using a multi-objective loss that combines autoregressive summarization, cross-modal alignment, and DPP-based distillation. Experiments show that our system produces more accurate, visually grounded summaries and selects more representative images, demonstrating the benefits of depth-aware fusion and principled image selection for multimodal summarization.
### Title:
          Learning Action Manifold with Multi-view Latent Priors for Robotic Manipulation
 - **Authors:** Junjin Xiao, Dongyang Li, Yandan Yang, Shuang Zeng, Tong Lin, Xinyuan Chang, Feng Xiong, Mu Xu, Xing Wei, Zhiheng Ma, Qing Zhang, Wei-Shi Zheng
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper tackles spatial perception and manipulation challenges in Vision-Language-Action (VLA) models. To address depth ambiguity from monocular input, we leverage a pre-trained multi-view diffusion model to synthesize latent novel views and propose a Geometry-Guided Gated Transformer (G3T) that aligns multi-view features under 3D geometric guidance while adaptively filtering occlusion noise. To improve action learning efficiency, we introduce Action Manifold Learning (AML), which directly predicts actions on the valid action manifold, bypassing inefficient regression of unstructured targets like noise or velocity. Experiments on LIBERO, RoboTwin 2.0, and real-robot tasks show our method achieves superior success rate and robustness over SOTA baselines. Project page: this https URL.
### Title:
          Improving the Performance and Learning Stability of Parallelizable RNNs Designed for Ultra-Low Power Applications
 - **Authors:** Julien Brandoit, Arthur Fyon, Damien Ernst, Guillaume Drion
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sequence learning is dominated by Transformers and parallelizable recurrent neural networks (RNNs) such as state-space models, yet learning long-term dependencies remains challenging, and state-of-the-art designs trade power consumption for performance. The Bistable Memory Recurrent Unit (BMRU) was introduced to enable hardware-software co-design of ultra-low power RNNs: quantized states with hysteresis provide persistent memory while mapping directly to analog primitives. However, BMRU performance lags behind parallelizable RNNs on complex sequential tasks. In this paper, we identify gradient blocking during state updates as a key limitation and propose a cumulative update formulation that restores gradient flow while preserving persistent memory, creating skip-connections through time. This leads to the Cumulative Memory Recurrent Unit (CMRU) and its relaxed variant, the $\alpha$CMRU. Experiments show that the cumulative formulation dramatically improves convergence stability and reduces initialization sensitivity. The CMRU and $\alpha$CMRU match or outperform Linear Recurrent Units (LRUs) and minimal Gated Recurrent Units (minGRUs) across diverse benchmarks at small model sizes, with particular advantages on tasks requiring discrete long-range retention, while the CMRU retains quantized states, persistent memory, and noise-resilient dynamics essential for analog implementation.
### Title:
          FIS-DiT: Breaking the Few-Step Video Inference Barrier via Training-Free Frame Interleaved Sparsity
 - **Authors:** Jian Tang, Jiawei Fan, Qingbin Liu, Zheng Wei
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While the overall inference latency of Video Diffusion Transformers (DiTs) can be substantially reduced through model distillation, per-step inference latency remains a critical bottleneck. Existing acceleration paradigms primarily exploit redundancy across the denoising trajectory; however, we identify a limitation where these step-wise strategies encounter diminishing returns in few-step regimes. In such scenarios, the scarcity of temporal states prevents effective feature reuse or predictive modeling, creating a formidable barrier to further acceleration. To overcome this, we propose Frame Interleaved Sparsity DiT (FIS-DiT), a training-free and operator-agnostic framework that shifts the optimization focus from the temporal trajectory to the latent frame dimension. Our approach is motivated by an intrinsic duality within this dimension: the existence of frame-wise sparsity that permits reduced computation, coupled with a structural consistency where each frame position remains equally vital to the global spatiotemporal context. Leveraging this insight, we implement Frame Interleaved Sparsity (FIS) as an execution strategy that manipulates frame subsets across the model hierarchy, refreshing all latent positions without requiring full-scale block computation. Empirical evaluations on Wan 2.2 and HunyuanVideo 1.5 demonstrate that FIS-DiT consistently achieves 2.11--2.41$\times$ speedup with negligible degradation across VBench-Q and CLIP metrics, providing a scalable and robust pathway toward real-time high-definition video generation.
### Title:
          From Clever Hans to Scientific Discovery: Interpreting EEG Foundational Transformers with LRP
 - **Authors:** Justus Meyer zu Bexten, Nico Scherf, Bogdan Franczyk, Simon M. Hofmann
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Emerging foundation models (FMs) in electroencephalography (EEG) promise a path to scale deep learning in diagnostics and brain-computer interfaces despite data scarcity, yet their opaque nature remains a barrier to wider adoption. We investigate attention-aware Layer-wise relevance propagation (LRP) as a post-hoc attribution method for EEG-FMs, extending LRP's use on convolutional neural network (CNN)-based EEG models to the Transformer architectures that current FMs are based on. We find that LRP can both verify EEG-FM decisions and surface novel, biologically plausible hypotheses from them. In motor imagery, it unmasks 'Clever Hans' behavior where models prioritize task correlated ocular signals over the intended motor correlates. In a naturalistic paradigm for affect prediction, it reveals a recurring reliance on a central electrode cluster, suggesting a candidate sensorimotor signature of arousal. Though heatmap interpretation remains ambiguous in this complex domain, the results position LRP as a tool for both verification and exploration of EEG-FMs, a role that will grow in both importance and discovery potential as the underlying models mature.
### Title:
          Rethinking Positional Encoding for Neural Vehicle Routing
 - **Authors:** Chuanbo Hua, Federico Berto, Andre Hottung, Nayeli Gast Zepeda, Yining Ma, Zihan Ma, Paula Wong-Chung, Changhyun Kwon, Cathy Wu, Kevin Tierney, Jinkyoo Park
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based models have become the dominant paradigm for neural combinatorial optimization (NCO) of vehicle routing problems (VRPs), yet the role of positional encoding (PE) in these architectures remains largely unexplored. Unlike natural language, where tokens are uniformly spaced on a line, routing solutions exhibit several properties that render standard NLP positional encodings inadequate. In this work, we formalize three such structural properties that a routing-aware PE should respect, namely anisometric node distances, cyclic and direction-aware topology, and hierarchical depot-anchored global multi-route structure, combining them with a unifying design principle of geometric grounding. Guided by these criteria, we analyze and compare PE methods spanning NLP, graph-transformer, and routing-specific families, and propose a hierarchical anisometric PE that combines a distance-indexed, circularly consistent in-route encoding with a depot-anchored angular cross-route encoding. Extensive experiments across diverse VRP variants demonstrate that geometry-grounded PE consistently outperforms index-based alternatives, with gains that transfer across problem variants, model architectures, and distribution shifts.
### Title:
          KIND: A Kalman-Inspired Adaptive Estimator for SRF Cavity Detuning
 - **Authors:** Andrei Maalberg (1), Axel Neumann (1), Pablo Echevarria (1), Andriy Ushakov (1), Jens Knobloch (1 and 2) ((1) Helmholtz-Zentrum Berlin, (2) University of Siegen)
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Superconducting radio frequency cavities with a high quality factor enable energy-efficient accelerator operation but are very sensitive to mechanical disturbances that detune their resonance. Accurate detuning estimation is therefore essential for efficient resonance control and stable beam conditions. This paper introduces Kalman-Inspired Neural Decomposition (KIND), a data-driven estimator that fuses a Dynamic Mode Decomposition model for stationary modal behavior with a Transformer-based predictor for transient dynamics. KIND further outputs learned uncertainty signals that indicate regime changes, enabling anomaly detection. Using operational cavity data, we compare KIND with a classical Kalman filtering baseline and discuss its potential as a foundation for future uncertainty-aware, forecast-based control.
### Title:
          From Trajectories to Phenotypes: Disease Progression as Structural Priors for Multi-organ Imaging Representation Learning
 - **Authors:** Zian Wang, Lizhen Lan, Guangming Wang, Haosen Zhang, Minxuan Xu, Qing Li, Tianxing He, Mo Yang, Wenyue Mao, Yajing Zhang, Yan Li, Chengyan Wang
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Imaging-derived phenotypes (IDPs) summarize multi-organ physiology but provide only static snapshots of diseases that evolve over time. In contrast, longitudinal electronic health records encode disease trajectories through temporal dependencies among past diagnosis events and comorbidity structure. We hypothesize that IDPs and disease trajectories contain partially shared disease-relevant structure. We propose a trajectory-aware distillation framework that transfers structural knowledge from a generative disease trajectory Transformer into an organ-wise IDP encoder. A population-scale trajectory model trained on longitudinal diagnosis sequences produces subject-level embeddings that supervise IDP representation learning via geometry-preserving alignment. During downstream prediction, trajectory and imaging representations can also be fused via cross-attention. Across 159 diseases in the UK Biobank cohort, trajectory-aware pretraining consistently improves both discrimination (AUC) and time-to-onset prediction (MAE), with the largest gains for low-prevalence diseases. Similarity relationships in IDP embedding space also align with those in trajectory space, providing supportive evidence for partially aligned representation geometry. These results suggest that population-scale generative disease models can serve as structural priors for data-limited imaging modalities, improving robustness under realistic cohort constraints.
### Title:
          A microservices-based endpoint monitoring platform with predictive NLP models for real-time security and hate-speech risk alerting
 - **Authors:** Darlan Noetzold, Anubis Graciela De Moraes Rossetto, Juan Francisco De Paz Santana, Valderi Reis Quietinho Leithard
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Organizations increasingly depend on endpoint devices and corporate communication channels, yet they still face critical risks such as sensitive data leakage, suspicious user behavior, and the circulation of hateful or harmful language in workplace contexts. Current solutions frequently address these issues in isolation (e.g., productivity tracking, data loss prevention, or hate-speech detection), limiting correlation across signals and delaying incident response. This work proposes a unified, microservices-based platform that collects endpoint telemetry and applies predictive natural language processing models to support real-time security and compliance alerting. The architecture is modular and scalable, relying on RabbitMQ for event ingestion and routing and Redis for low-latency data access and alert delivery. For text classification, transformer-based models such as BERT are evaluated for hate-speech risk detection, achieving an average accuracy of 87\%. Experimental results indicate that the proposed platform can promptly surface indicators of data exfiltration and policy violations while centralizing alert management, providing an integrated framework that combines monitoring, security analytics, and predictive capabilities.
### Title:
          Efficient and Adaptive Human Activity Recognition via LLM Backbones
 - **Authors:** Aleksandr Bredikhin, Philippe Lalanda, German Vega
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Human Activity Recognition (HAR) is a core task in pervasive computing systems, where models must operate under strict computational constraints while remaining robust to heterogeneous and evolving deployment conditions. Recent advances based on Transformer architectures have significantly improved recognition performance, but typically rely on task-specific models trained from scratch, resulting in high training cost, large data requirements, and limited adaptability to domain shifts. In this paper, we propose a paradigm shift that reuses large pretrained language models (LLMs) as generic temporal backbones for sensor-based HAR, instead of designing domain-specific Transformers. To bridge the modality gap between inertial time series and language models, we introduce a structured convolutional projection that maps multivariate accelerometer and gyroscope signals into the latent space of the LLM. The pretrained backbone is kept frozen and adapted using parameter-efficient Low-Rank Adaptation (LoRA), drastically reducing the number of trainable parameters and the overall training cost. Through extensive experiments on standard HAR benchmarks, we show that this approach enables rapid convergence, strong data efficiency, and robust cross-dataset transfer, particularly in low-data and few-shot settings. At the same time, our results highlight the complementary roles of convolutional frontends and LLMs, where local invariances are handled at the signal level while long-range temporal dependencies are captured by the pretrained backbone. Overall, this work demonstrates that LLMs can serve as a practical, frugal, and scalable foundation for adaptive HAR systems, opening new directions for reusing foundation models beyond their original language domain.
### Title:
          What-Where Transformer: A Slot-Centric Visual Backbone for Concurrent Representation and Localization
 - **Authors:** Ryota Yoshihashi, Masahiro Kada, Satoshi Ikehata, Rei Kawakami, Ikuro Sato
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many image understanding tasks involve identifying what is present and where it appears. However, tasks that address where, such as object discovery, detection, and segmentation, are often considerably more complex than image classification, which primarily focuses on what. One possible reason is that classification-oriented backbones tend to emphasize semantic information about what, while implicitly entangling or suppressing information about where. In this work, we focus on an inductive bias termed what-where separation, which encourages models to represent object appearance and spatial location in a decomposed manner. To incorporate this bias throughout an attentive backbone in the style of Vision Transformer (ViT), we propose the What-Where Transformer (WWT). Our method introduces two key novel designs: (1) it treats tokens as representations of what and attention maps as representations of where, and processes them in concurrent feed-forward modules via a multi-stream, slot-based architecture; (2) it reuses both the final-layer tokens and attention maps for downstream tasks, and directly exposes them to gradients derived from task losses, thereby facilitating more effective and explicit learning of localization. We demonstrate that even under standard single-label classification-based supervision on ImageNet, WWT exhibits emergent multiple object discovery directly from raw attention maps, rather than via additional postprocessing such as token clustering. Furthermore, WWT achieves superior performance compared to ViT-based methods on zero-shot object discovery and weakly supervised semantic segmentation, and it is transferable to various localization setups with minimal modifications. Code will be published after acceptance.
### Title:
          Spectral Vision Transformer for Efficient Tokenization with Limited Data
 - **Authors:** Alexandra G. Roberts, Maneesh John, Jinwei Zhang, Dominick Romano, Mert Sisman, Ki Sueng Choi, Heejong Kim, Mert R. Sabuncu, Thanh D. Nguyen, Alexey V. Dimov, Pascal Spincemaille, Brian H. Kopell, Yi Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose a novel spectral vision transformer architecture for efficient tokenization in limited data, with an emphasis on medical imaging. We outline convenient theoretical properties arising from the choice of basis including spatial invariance and optimal signal-to-noise ratio. We show reduced complexity arising from the spectral projection compared to spatial vision transformers. We show equitable or superior performance with a reduced number of parameters as compared to a variety of models including compact and standard vision transformers, convolutional neural networks with attention, shifted window transformers, multi-layer perceptrons, and logistic regression. We include simulated, public, and clinical data in our analysis and release our code at: \verb+this http URL.
### Title:
          Resilient Vision-Tabular Multimodal Learning under Modality Missingness
 - **Authors:** Camillo Maria Caruso, Valerio Guarrasi, Paolo Soda
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal deep learning has shown strong potential in medical applications by integrating heterogeneous data sources such as medical images and structured clinical variables. However, most existing approaches implicitly assume complete modality availability, an assumption that rarely holds in real-world clinical settings where entire modalities and individual features are frequently missing. In this work, we propose a multimodal transformer framework for joint vision-tabular learning explicitly designed to operate under pervasive modality missingness, without relying on imputation or heuristic model switching. The architecture integrates three components: a vision, a tabular, and a multimodal fusion encoder. Unimodal representations are weighted through learnable modality tokens and fused via intermediate fusion with masked self-attention, which excludes missing tokens and modalities from information aggregation and gradient propagation. To further enhance resilience, we introduce a modality-dropout regularization strategy that stochastically removes available modalities during training, encouraging the model to exploit complementary information under partial data availability. We evaluate our approach on the MIMIC-CXR dataset paired with structured clinical data from MIMIC-IV for multilabel classification of 14 diagnostic findings with incomplete annotations. Two parallel systematic stress-test protocols progressively increase training and inference missingness in each modality separately, spanning fully multimodal to fully unimodal scenarios. Across all missingness regimes, the proposed method consistently outperforms representative baselines, showing smoother performance degradation and improved robustness. Ablation studies further demonstrate that attention-level masking and intermediate fusion with joint fine-tuning are key to resilient multimodal inference.
### Title:
          Self-Consistent Latent Reasoning: Long Latent Sequence Reasoning for Vision-Language Model
 - **Authors:** Chenfeng Wang, Wei He, Xuhan Zhu, Chunpeng Zhou, Qizhen Li, Song Yan, Yufei Zheng, Chengjun Yu, Fan Lu, Wei Zhai, Yang Cao, Pengfei Yu, Zheng-Jun Zha
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In language reasoning, longer chains of thought consistently yield better performance, which naturally suggests that visual latent reasoning may likewise benefit from longer latent sequences. However, we discover a counterintuitive phenomenon: the performance of existing latent visual reasoning methods systematically degrades as the latent sequence grows longer. We reveal the root cause: Information Gain Collapse -- autoregressive generation makes each step highly dependent on prior outputs, so subsequent tokens can barely introduce new information. We further identify that heavily pooled ($\geq 128\times$) image embeddings used as supervision targets provide no more signal than meaningless placeholders. Motivated by these insights, we propose SCOLAR (Self-COnsistent LAtent Reasoning), which introduces a lightweight detransformer that leverages the LLM's full-sequence hidden states to generate auxiliary visual tokens in a single shot, with each token independently anchored to the original visual space. Combined with three-stage SFT and ALPO reinforcement learning, SCOLAR extends acceptable latent CoT length by over $30\times$, achieves state-of-the-art among open-source models on real-world reasoning benchmarks (+14.12% over backbone), and demonstrates strong out-of-distribution generalization.
### Title:
          On What We Can Learn from Low-Resolution Data
 - **Authors:** Theresa Dahl Frehr, Niels Henrik Pontoppidan, Hiba Nassar, Tommy Sonne Alstrøm
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Artificial intelligence systems typically rely on large, centrally collected datasets, a premise that does not hold in many real-world domains such as healthcare and public institutions. In these settings, data sharing is often constrained by storage, privacy, or resource limitations. For example, small wearable devices may lack the bandwidth or energy capacity needed to store and transmit high-resolution data, leading to aggregation during data collection and thus a loss of information. As a result, datasets collected from different sources may consist of a mixture of high- and low-resolution samples. Despite the prevalence of this setting, it remains unclear how informative low-resolution data is when models are ultimately evaluated on high-resolution inputs. We provide a theoretical analysis based on the Kullback-Leibler divergence that characterises how the influence of a datapoint changes with resolution, and derive bounds that relate the relative contribution of high- and low-resolution observations to the information lost under downsampling. To support this analysis, we empirically demonstrate, using both a vision transformer and a convolutional neural network, that adding low-resolution data to the training set consistently improves performance when high-resolution data is scarce.
### Title:
          Mechanistic Interpretability of ASR models using Sparse Autoencoders
 - **Authors:** Dan Pluth, Zachary Nicholas Houghton, Yu Zhou, Vijay K. Gurbani
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding the internal machinations of deep Transformer-based NLP models is more crucial than ever as these models see widespread use in various domains that affect the public at large, such as industry, academia, finance, health. While these models have advanced rapidly, their internal mechanisms remain largely a mystery. Techniques such as Sparse Autoencoders (SAE) have emerged to understand these mechanisms by projecting dense representations into a sparse vector. While existing research has demonstrated the viability of the SAE in interpreting text-based Large Language Models (LLMs), there are no equivalent studies that demonstrate the application of a SAE to audio processing models like Automatic Speech Recognizers (ASRs). In this work, a SAE is applied to Whisper, a Transformer-based ASR, training a high-dimensional sparse latent space on frame-level embeddings extracted from the Whisper encoder. Our work uncovers diverse monosemantic features across linguistic and non-linguistic boundaries, and demonstrates cross-lingual feature steering. This work establishes the viability of a SAE model and demonstrates that Whisper encodes a rich amount of linguistic information.
### Title:
          H3D-MarNet: Wavelet-Guided Dual-Path Learning for Metal Artifact Suppression and CT Modality Transformation for Radiotherapy Workflows
 - **Authors:** Mubashara Rehman, Niki Martinel, Michele Avanzo, Riccardo Spizzo, Christian Micheloni
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Metal artifacts in computed tomography (CT) severely degrade image quality, compromising diagnostic accuracy and radiotherapy planning, especially in cancer patients with high-density implants. We propose H3D-MarNet, a two-stage framework for artifact-aware CT domain transformation from kilo-voltage CT (kVCT) to mega-voltage CT (MVCT). In the first stage, a wavelet-based preprocessing module suppresses metal-induced artifacts through frequency-aware denoising while preserving anatomical structures. In second stage, Domain-TransNet performs kVCT-to-MVCT domain transformation using a hybrid volumetric learning architecture. Domain-TransNet integrates a CNN-based encoder to capture fine-grained local anatomical details and a transformer-based encoder to model long-range volumetric dependencies. The complementary representations are fused through an attention-based feature fusion mechanism to ensure spatial and contextual coherence across slices. A multi-stage, attention-guided decoder, supported by deep supervision, progressively reconstructs artifact-suppressed MVCT volumes. Extensive experiments demonstrate that H3D-MarNet achieves 28.14 dB PSNR and 0.717 SSIM on artifact-affected slices from full dataset, indicating effective metal artifact suppression and anatomical preservation, highlighting its potential for reliable CT modality transformation in clinical radiotherapy workflows.
### Title:
          Hypernetworks for Dynamic Feature Selection
 - **Authors:** Javier Fumanal-Idocin, Raquel Fernandez-Peralta, Javier Andreu-Perez
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dynamic feature selection (DFS) is a machine learning framework in which features are acquired sequentially for individual samples under budget constraints. The exponential growth in the number of possible feature acquisition paths forces a DFS model to balance fitting specific scenarios against maintaining general performance, even when the feature space is moderate in size. In this paper, we study the structural limitations of existing DFS approaches to achieve an optimal solution. Then, we propose \textsc{Hyper-DFS}, a hypernetwork-based DFS approach that generates feature subset-specific classifier parameters on demand. We show that the use of hypernetworks compared to mask-embedding methods results in a smaller structural complexity bound. We also use a Set Transformer encoding to create a smooth conditioning space for the hypernetwork, so that functionally similar tasks are also geometrically close. In our benchmarks, \textsc{Hyper-DFS} outperforms all state-of-the-art approaches on synthetic and real-life tabular data. It is also competitive or superior across all image datasets tested, and shows substantially stronger zero-shot generalisation to feature subsets never seen during training than existing DFS approaches.
### Title:
          Images in Sentences: Scaling Interleaved Instructions for Unified Visual Generation
 - **Authors:** Yabo Zhang, Kunchang Li, Dewei Zhou, Xinyu Huang, Xun Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While recent advancements in multimodal language models have enabled image generation from expressive multi-image instructions, existing methods struggle to maintain performance under complex interleaved instructions. This limitation stems from the structural separation of images and text in current paradigms, which forces models to bridge difficult long-range dependencies to match descriptions with visual targets. To address these challenges, we propose \texttt{I}mages i\texttt{N} \texttt{SE}n\texttt{T}ences (\textit{a.k.a}, INSET), a unified generation model that seamlessly embeds images as native vocabulary within textual instructions. By positioning visual features directly at their corresponding semantic slots, INSET leverages the contextual locality of transformers for precise object binding, effectively treating images as dense, expressive language tokens. Furthermore, we introduce a scalable data engine that synthesizes 15M high-quality interleaved samples from standard image and video datasets, utilizing VLMs and LLMs to construct rich, long-horizon sequences. Evaluation results on InterleaveBench demonstrate that INSET significantly outperforms state-of-the-art methods in multi-image consistency and text alignment, with performance gaps widening as input complexity increases. Beyond standard generation, our approach inherently extends to multimodal image editing, integrating visual content as part of the instruction to facilitate highly expressive and creative visual manipulations.
### Title:
          EHR-RAGp: Retrieval-Augmented Prototype-Guided Foundation Model for Electronic Health Records
 - **Authors:** Saeed Shurrab, Mariam Al-Omari, Dana El Samad, Farah E. Shamout
 - **Subjects:** Subjects:
Information Retrieval (cs.IR); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Electronic Health Records (EHR) contain rich longitudinal patient information and are widely used in predictive modeling applications. However, effectively leveraging historical data remains challenging due to long trajectories, heterogeneous events, temporal irregularity, and the varying relevance of past clinical context. Existing approaches often rely on fixed windows or uniform aggregation, which can obscure clinically important signals. In this work, we introduce EHR-RAGp, a retrieval-augmented foundation model that dynamically integrates the most relevant patient history across diverse clinical event types. We propose a prototype-guided retrieval module that acts as an alignment mechanism and estimates the relevance of retrieved historical chunks with respect to a given prediction task, guiding the model towards the most informative context. Across multiple clinical prediction tasks, EHR-RAGp consistently outperforms state-of-the-art EHR foundation models and transformer-based baselines. Furthermore, integrating EHR-RAGp with existing clinical foundation models yields substantial performance gains. Overall, EHR-RAGp provides a scalable and efficient framework for leveraging long-range clinical context to improve downstream performance.
### Title:
          Geometric Factual Recall in Transformers
 - **Authors:** Shauli Ravfogel, Gilad Yehudai, Joan Bruna, Alberto Bietti
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 How do transformer language models memorize factual associations? A common view casts internal weight matrices as associative memories over pairs of embeddings, requiring parameter counts that scale linearly with the number of facts. We develop a theoretical and empirical account of an alternative, \emph{geometric} form of memorization in which learned embeddings encode relational structure directly, and the MLP plays a qualitatively different role. In a controlled setting where a single-layer transformer must memorize random bijections from subjects to a shared attribute set, we prove that a logarithmic embedding dimension suffices: subject embeddings encode \emph{linear superpositions} of their associated attribute vectors, and a small MLP acts as a relation-conditioned selector that extracts the relevant attribute via ReLU gating, and not as an associative key-value mapping. We extend these results to the multi-hop setting -- chains of relational queries such as ``Who is the mother of the wife of $x$?'' -- providing constructions with and without chain-of-thought that exhibit a provable capacity-depth tradeoff, complemented by a matching information-theoretic lower bound. Empirically, gradient descent discovers solutions with precisely the predicted structure. Once trained, the MLP transfers zero-shot to entirely new bijections when subject embeddings are appropriately re-initialized, revealing that it has learned a generic selection mechanism rather than memorized any particular set of facts.
### Title:
          AOI-SSL: Self-Supervised Framework for Efficient Segmentation of Wire-bonded Semiconductors In Optical Inspection
 - **Authors:** Joaquín Figueira, Rob Van Gastel, Giacomo D'Amicantonio, Zhuoran Liu, Ioan Gabriel Bucur, Faysal Boughorbel, Egor Bondarev
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Segmentation models in automated optical inspection of wire-bonded semiconductors are typically device-specific and must be re-trained when new devices or distribution shifts appear. We introduce AOI-SSL, a training-efficient framework for semantic segmentation of wire-bonded semiconductors by combining small-domain self-supervised pre-training of vision transformers with in-context inference that minimizes the need of labeled examples. We pre-train SOTA self-supervised algorithms in a small industrial inspection dataset and find that Masked Autoencoders are the most effective in this small-data setting, improving downstream segmentation while reducing the labeled fine-tuning effort. We further introduce in-context, patch-level retrieval methods that predict masks directly from dense encoder embeddings with negligible additional training. We show that, in this setting, simple similarity-based retrieval performs on par with more complex attention-based aggregation used currently in the literature. Furthermore, our experiments demonstrate that self-supervised pre-training significantly improves segmentation quality compared to training from scratch and to ImageNet pre-trained backbones under a fixed fine-tuning computational budget. Finally, the results reveal that retrieval based segmentation outperforms fine-tuning when targeting single device images, allowing for near-instant adaptation to difficult samples.
### Title:
          A Causal Language Modeling Detour Improves Encoder Continued Pretraining
 - **Authors:** Rian Touchent, Eric de la Clergerie
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 When adapting an encoder to a new domain, the standard approach is to continue training with Masked Language Modeling (MLM). We show that temporarily switching to Causal Language Modeling (CLM) followed by a short MLM decay improves downstream performance. On biomedical texts with ModernBERT, this CLM detour outperforms MLM baselines trained on identical data and compute across 8 French and 11 English biomedical tasks, by +1.2-2.8pp and +0.3-0.8pp respectively, depending on model size. We investigate the reasons for these gains. We find that CLM's dense supervision impacts low transformer layers (0-7) far more than MLM does. Freezing low layers during CLM eliminates the downstream benefit; freezing mid layers preserves it. The representational changes persist through the MLM decay phase, even when it matches the CLM phase in length, and they scale with model capacity. We release ModernCamemBERT-bio and ModernBERT-bio as state-of-the-art biomedical encoders in Base and Large sizes.
### Title:
          Solve the Loop: Attractor Models for Language and Reasoning
 - **Authors:** Jacob Fein-Ashley, Paria Rashidinejad
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Looped Transformers offer a promising alternative to purely feed-forward computation by iteratively refining latent representations, improving language modeling and reasoning. Yet recurrent architectures remain unstable to train, costly to optimize and deploy, and constrained to small, fixed recurrence depths. We introduce Attractor Models, in which a backbone module first proposes output embeddings, then an attractor module refines them by solving for the fixed point, with gradients obtained through implicit differentiation. Thus, training memory remains constant in effective depth, and iterations are chosen adaptively by convergence. Empirically, Attractor Models outperform existing models across two regimes, large-scale language-model pretraining and reasoning with tiny models. In language modeling, Attractor Models deliver a Pareto improvement over standard Transformers and stable looped models across sizes, improving perplexity by up to 46.6% and downstream accuracy by up to 19.7% while reducing training cost. Notably, a 770M Attractor Model outperforms a 1.3B Transformer trained on twice as many tokens. On challenging reasoning tasks, we show that our model with only 27M parameters and approximately 1000 examples achieves 91.4% accuracy on Sudoku-Extreme and 93.1% on Maze-Hard, scaling favorably where frontier models like Claude and GPT o3, fail completely, and specialized recursive reasoners collapse at larger sizes. Lastly, we show that Attractor Models exhibit a novel phenomenon, which we call equilibrium internalization: fixed-point training places the model's initial output embedding near equilibrium, allowing the solver to be removed at inference time with little degradation. Together, these results suggest that Attractor Models make iterative refinement scalable by turning recurrence into a computation the model can learn to internalize.
### Title:
          KV-Fold: One-Step KV-Cache Recurrence for Long-Context Inference
 - **Authors:** Alireza Nadali, Patrick Cooper, Ashutosh Trivedi, Alvaro Velasquez
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce KV-Fold, a simple, training-free long-context inference protocol that treats the key-value (KV) cache as the accumulator in a left fold over sequence chunks. At each step, the model processes the next chunk conditioned on the accumulated cache, appends the newly produced keys and values, and passes the enlarged cache forward; the same one-step update is applied repeatedly, analogous to foldl in functional programming. Building on the KV cache concatenation primitive introduced for latent multi-agent communication, we repurpose it as a chunk-to-chunk recurrence for long-context inference. When processing chunk t, the model attends to the KV cache carried from earlier chunks as a prefix, reusing its internal state across segments without modifying or retraining the model. Despite its simplicity, the induced recurrence is stable: per-step drift rises briefly and then saturates into a flat plateau that persists across deep chains. This plateau is insensitive to a 10,000x change in numerical precision, robust across chunk sizes, and consistent across model families. At the task level, KV-Fold preserves exact information over long distances. On a needle-in-a-haystack benchmark, it achieves 100% exact-match retrieval across 152 trials spanning contexts from 16K to 128K tokens and chain depths up to 511 on Llama-3.1-8B, while remaining within the memory limits of a single 40GB GPU. Compared to streaming methods, which trade fidelity for bounded memory, KV-Fold maintains long-range retrieval while operating as a sequence of tractable forward passes. Overall, our results show that frozen pretrained transformers already support a stable form of KV-cache recurrence, providing a practical route to long-context inference without architectural changes or training.
### Title:
          Elastic Attention Cores for Scalable Vision Transformers
 - **Authors:** Alan Z. Song, Yinjie Chen, Mu Nan, Rui Zhang, Jiahang Cao, Weijian Mai, Muquan Yu, Hossein Adeli, Deva Ramanan, Michael J. Tarr, Andrew F. Luo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformers (ViTs) achieve strong data-driven scaling by leveraging all-to-all self-attention. However, this flexibility incurs a computational cost that scales quadratically with image resolution, limiting ViTs in high-resolution domains. Underlying this approach is the assumption that pairwise token interactions are necessary for learning rich visual-semantic representations. In this work, we challenge this assumption, demonstrating that effective visual representations can be learned without any direct patch-to-patch interaction. We propose VECA (Visual Elastic Core Attention), a vision transformer architecture that uses efficient linear-time core-periphery structured attention enabled by a small set of learned cores. In VECA, these cores act as a communication interface: patch tokens exchange information exclusively through the core tokens, which are initialized from scratch and propagated across layers. Because the $N$ image patches only directly interact with a resolution invariant set of $C$ learned "core" embeddings, this yields linear complexity $O(N)$ for predetermined $C$, which bypasses quadratic scaling. Compared to prior cross-attention architectures, VECA maintains and iteratively updates the full set of $N$ input tokens, avoiding a small $C$-way bottleneck. Combined with nested training along the core axis, our model can elastically trade off compute and accuracy during inference. Across classification and dense tasks, VECA achieves performance competitive with the latest vision foundation models while reducing computational cost. Our results establish elastic core-periphery attention as a scalable alternative building block for Vision Transformers.
### Title:
          EgoForce: Forearm-Guided Camera-Space 3D Hand Pose from a Monocular Egocentric Camera
 - **Authors:** Christen Millerdurai, Shaoxiang Wang, Yaxu Xie, Vladislav Golyanik, Didier Stricker, Alain Pagani
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reconstructing the absolute 3D pose and shape of the hands from the user's viewpoint using a single head-mounted camera is crucial for practical egocentric interaction in AR/VR, telepresence, and hand-centric manipulation tasks, where sensing must remain compact and unobtrusive. While monocular RGB methods have made progress, they remain constrained by depth-scale ambiguity and struggle to generalize across the diverse optical configurations of head-mounted devices. As a result, models typically require extensive training on device-specific datasets, which are costly and laborious to acquire. This paper addresses these challenges by introducing EgoForce, a monocular 3D hand reconstruction framework that recovers robust, absolute 3D hand pose and its position from the user's (camera-space) viewpoint. EgoForce operates across fisheye, perspective, and distorted wide-FOV camera models using a single unified network. Our approach combines a differentiable forearm representation that stabilizes hand pose, a unified arm-hand transformer that predicts both hand and forearm geometry from a single egocentric view, mitigating depth-scale ambiguity, and a ray space closed-form solver that enables absolute 3D pose recovery across diverse head-mounted camera models. Experiments on three egocentric benchmarks show that EgoForce achieves state-of-the-art 3D accuracy, reducing camera-space MPJPE by up to 28% on the HOT3D dataset compared to prior methods and maintaining consistent performance across camera configurations. For more details, visit the project page at this https URL.
## Keyword: autonomous driving
### Title:
          PointGS: Semantic-Consistent Unsupervised 3D Point Cloud Segmentation with 3D Gaussian Splatting
 - **Authors:** Yixiao Song, Qingyong Li, Wen Wang, Zhicheng Yan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unsupervised point cloud segmentation is critical for embodied artificial intelligence and autonomous driving, as it mitigates the prohibitive cost of dense point-level annotations required by fully supervised methods. While integrating 2D pre-trained models such as the Segment Anything Model (SAM) to supplement semantic information is a natural choice, this approach faces a fundamental mismatch between discrete 3D points and continuous 2D images. This mismatch leads to inevitable projection overlap and complex modality alignment, resulting in compromised semantic consistency across 2D-3D transfer. To address these limitations, this paper proposes PointGS, a simple yet effective pipeline for unsupervised 3D point cloud segmentation. PointGS leverages 3D Gaussian Splatting as a unified intermediate representation to bridge the discrete-continuous domain gap. Input sparse point clouds are first reconstructed into dense 3D Gaussian spaces via multi-view observations, filling spatial gaps and encoding occlusion relationships to eliminate projection-induced semantic conflation. Multi-view dense images are rendered from the Gaussian space, with 2D semantic masks extracted via SAM, and semantics are distilled to 3D Gaussian primitives through contrastive learning to ensure consistent semantic assignments across different views. The Gaussian space is aligned with the original point cloud via two-step registration, and point semantics are assigned through nearest-neighbor search on labeled Gaussians. Experiments demonstrate that PointGS outperforms state-of-the-art unsupervised methods, achieving +0.9% mIoU on ScanNet-V2 and +2.8% mIoU on S3DIS.
### Title:
          XWOD: A Real-World Benchmark for Object Detection under Extreme Weather Conditions
 - **Authors:** Chih-Hsin Chen, Yu-Tung Liu, Amar Fadillah, Kuan-Ting Lai, Dong Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving and intelligent transportation systems remain vulnerable under extreme weather. The U.S. Federal Highway Administration reports that roughly 745,000 crashes and 3,800 fatalities per year are weather-related, and recent regulatory investigations have examined failures of Level-2/3 driving systems under reduced-visibility conditions. However, datasets commonly used to evaluate weather robustness remain limited in scale, diversity, and realism. In this paper, we introduce XWOD (Extreme Weather Object Detection), a large-scale real-world traffic-object detection benchmark containing 10,010 images and 42,924 bounding boxes across seven extreme weather conditions: rain, snow, fog, haze/sand/dust, flooding, tornado, and wildfire. The dataset covers six traffic-object categories, including car, person, truck, motorcycle, bicycle, and bus. XWOD extends the weather taxonomy from one to seven conditions, and is the first to cover the emerging class of climate-amplified hazards, such as flooding, tornado, and wildfire. To evaluate the quality of our data, we train standard YOLO-family detectors on XWOD and test them zero-shot on external weather benchmarks, achieving mAP$_{50}$ scores of 63.00% on RTTS, 59.94% on DAWN, and 61.12% on WEDGE, compared with the corresponding published YOLO-based baselines of 40.37%, 32.75%, and 45.41%, respectively, representing relative improvements of 56%, 83%, and 35%. These cross-dataset results show that XWOD provides a strong source domain for learning weather-robust traffic perception. We release the dataset, splits, baseline weights, and reproducible evaluation code under a research-use license.
### Title:
          The DAWN of World-Action Interactive Models
 - **Authors:** Hongbo Lu, Liang Yao, Chenghao He, Haoyu Wang, Xiang Gu, Xianfei Li, Wenlong Liao, Tao He, Pai Peng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A plausible scene evolution depends on the maneuver being considered, while a good maneuver depends on how the scene may evolve. Existing World Action Models (WAMs) largely miss this reciprocity, treating world prediction and action generation as either isolated parallel branches or rigid predict-then-plan pipelines. We formalize this perspective as World-Action Interactive Models (WAIMs), and instantiate it in autonomous driving with \textbf{DAWN} (\textbf{D}enoising \textbf{A}ctions and \textbf{W}orld i\textbf{N}teractive model), a simple yet strong latent generative baseline. DAWN operates in a compact semantic latent space and couples a \emph{World Predictor} with a \emph{World-Conditioned Action Denoiser}: the predicted world hypothesis conditions action denoising, while the denoised action hypothesis is fed back to update the world prediction, so that both are recursively refined during inference. Rather than eliminating test-time world evolution altogether or rolling out the full future in pixel space, DAWN performs a short explicit latent rollout that is sufficient to support long-horizon trajectory generation in complex interactive scenes. Experiments show that DAWN achieves strong planning performance and favorable safety-related results across multiple autonomous driving benchmarks. More broadly, our results suggest that interactive world-action generation is a principled path toward truly actionable world models.
### Title:
          PointForward: Feedforward Driving Reconstruction through Point-Aligned Representations
 - **Authors:** Cheng Chi, Xianqi Wang, Hongcheng Luo, Mingfei Tu, Gangwei Xu, Zehan Zhang, Bing Wang, Guang Chen, Hangjun Ye, Sida Peng, Xin Yang, Haiyang Sun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-fidelity reconstruction of driving scenes is crucial for autonomous driving. While recent feedforward 3D Gaussian Splatting (3DGS) methods enable fast reconstruction, their per-pixel Gaussian prediction paradigm often suffers from multi-view inconsistency and layering artifacts. Moreover, existing methods often model dynamic instances via dense flow prediction, which lacks explicit cross-view correspondence and instance-level consistency. In this paper, we propose PointForward, a feedforward driving reconstruction framework through point-aligned representations. Unlike pixel-aligned methods, we initialize sparse 3D queries in world space and aggregate multi-view image information via spatial-temporal fusion onto these queries, enforcing explicit cross-view consistency in a single feedforward pass. To handle scene dynamics, we introduce scene graphs that explicitly organize moving instances during reconstruction. By leveraging 3D bounding boxes, our method enables instance-level motion propagation and temporally consistent dynamic representations. Extensive experiments demonstrate that PointForward achieves state-of-the-art performance on large-scale driving benchmarks. The code will be available upon the publication of the paper.
### Title:
          OOM-Free Alpamayo via CPU-GPU Memory Swapping for Vision-Language-Action Models
 - **Authors:** Seungwoo Roh, Huiyeong Kim, Jong-Chan Kim
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end Vision-Language-Action (VLA) models for autonomous driving unify perception, reasoning, and control in a single neural network, achieving strong driving performance but requiring 20-60GB of GPU memory-far exceeding the 12-16GB available on commodity GPUs. We present a framework, which enables memory-efficient VLA inference on VRAM-constrained GPUs through system-level optimization alone, without model modification. Our work proceeds in three stages: (1) Sequential Demand Layering reduces VRAM usage from model-level to layer-level granularity; (2) Pipelined Demand Layering hides parameter transfer time within layer execution time via transfer--compute overlap; and (3) a GPU-Resident Layer Decision Policy, informed by per-module residency benefit analysis, eliminates the residual transfer overhead that pipelining cannot hide. We further propose a performance prediction model that determines the optimal configuration-both the number and placement of resident layers-from a single profiling run with less than 1.3% prediction error across all configurations. Applied to NVIDIA's Alpamayo-R1-10B (21.52GB) on an RTX 5070Ti (16GB), our work achieves up to 3.55x speedup over Accelerate offloading while maintaining full BF16 precision.
### Title:
          Random-Set Graph Neural Networks
 - **Authors:** Tommy Woodley, Shireen Kudukkil Manchingal, Matteo Tolloso, Davide Bacciu, Fabio Cuzzolin
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Applications (stat.AP); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Uncertainty quantification has become an important factor in understanding the data representations produced by Graph Neural Networks (GNNs). Despite their predictive capabilities being ever useful across industrial workspaces, the inherent uncertainty induced by the nature of the data is a huge mitigating factor to GNN performance. While aleatoric uncertainty is the result of noisy and incomplete stochastic data such as missing edges or over-smoothing, epistemic uncertainty arises from lack of knowledge about a system or model (e.g., a graph's topology or node feature representation), which can be reduced by gathering more data and information. In this paper, we propose an original new framework in which node-level epistemic uncertainty is modelled in a belief function (finite random set) formalism. The resulting Random-Set Graph Neural Networks have a belief-function head predicting a random set over the list of classes, from which both a precise probability prediction and a measure of epistemic uncertainty can be obtained. Extensive experiments on 9 different graph learning datasets, including real-world autonomous driving benchmarks as such Nuscene and ROAD, demonstrate RS-GNN's superior uncertainty quantification capabilities
