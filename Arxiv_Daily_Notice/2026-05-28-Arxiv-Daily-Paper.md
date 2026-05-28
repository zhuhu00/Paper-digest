# Showing new listings for Thursday, 28 May 2026
## Keyword: SLAM
### Title:
          SAFEVPR: Patch-Based Conformal Verification for Safe Cross-Condition Sequence Visual Place Recognition
 - **Authors:** Ha Sier, Jiaqiang Zhang, Zhuo Zou, Xianjia Yu, Tomi Westerlund
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sequence-based visual place recognition (VPR) for SLAM and robot relocalization must decide whether the retrieved top-1 candidate is safe to accept. Conformal prediction is a natural framework for this accept/reject decision, but its finite-sample guarantees rely on exchangeability between calibration and deployment (test) data, which is violated under cross-condition deployment. We introduce SAFEVPR, a non-trainable verification-and-calibration pipeline for safe cross-condition sequence VPR. SAFEVPR replaces the standard backbone cosine similarity with a mutual-nearest-neighbour (MNN) patch-matching score computed from frozen DINOv2 ViT features, and replaces flat Learn-Then-Test calibration with Mondrian conformal LTT, fitting separate Bonferroni-corrected thresholds across score bins. Under exchangeability, these thresholds would provide finite-sample false-discovery-rate (FDR) control; under condition shift, we evaluate empirical validity per deployment. Across 23 cross-condition setups from Oxford RobotCar, NCLT, and St Lucia datasets, using three frozen VPR backbones, SAFEVPR is empirically valid on 23/23 setups at target FDR alpha = 0.10, achieving mean accepted FDR 0.014 and mean true-positive rate (TPR) 0.75. The results show that raw discrimination alone is not sufficient for conformal validity: AnyLoc-VLAD and Super-Point+LightGlue reach comparable area under the receiver operating characteristic curve (AUROC) but fail more setups under the same calibration. On textureless repetitive scenery, SAFEVPR safely abstains rather than accepting unreliable matches. Code is available at this https URL.
### Title:
          Provably Guaranteed Polytopic Uncertainty Quantification for SLAM
 - **Authors:** Guangyang Zeng, Yulong Gao, Yuan Shen, Lingpeng Chen, Haoying Li, Guodong Shi, Junfeng Wu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In safety-critical robotics applications, guaranteed and practical uncertainty quantification (UQ) in perception is vital. Many existing works either offer no formal containment guarantee, rely on restrictive modeling assumptions, or focus only on pose estimation rather than a complete SLAM pipeline. This paper presents provably guaranteed UQ algorithms for 3D-3D landmark-based SLAM. The algorithms consist of three basic UQ modules: forward UQ for mapping, backward UQ for pose tracking, and pose compound. Each module produces a certified uncertainty set; when the input uncertainty bounds are deterministic, the output sets inherit deterministic guarantees, i.e., they provably contain the true poses and landmarks. Specifically, we use polytopes to represent uncertainty sets, enabling tractable computations and a unified treatment of pose uncertainty. To enhance algorithms' practical usability, we incorporate conformal prediction to calibrate measurement uncertainty from data with prescribed probability. Simulations and experiments demonstrate that the proposed algorithms provide both strong theoretical guarantees and practical usability. The code is open-sourced at this https URL.
## Keyword: odometry
### Title:
          Trinity: Unifying Class-Agnostic Terrain and Semantic Segmentation for Unstructured Outdoor Environments by Leveraging Synthetic Data
 - **Authors:** Marcus G Müller, Wout Boerdijk, Maximilian Durner, Riccardo Giubilato, Abel Gawel, Wolfgang Stürzl, Roland Siegwart, Rudolph Triebel
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Terrain understanding is fundamental for mobile robots operating in unstructured outdoor environments. Existing vision-based traversability estimation methods rely on robot-specific annotations or semantic class mappings, limiting transferability across platforms and requiring costly re-annotation when robot capabilities change, while standard semantic segmentation methods only focus on specific predefined classes, which do not capture the variety of terrains. In this work, we propose a transformer-based architecture that jointly performs class-specific semantic segmentation and class-agnostic terrain segmentation within a unified network, called Trinity. Terrain regions are segmented based solely on visual appearance, without predefined semantic labels or robot-dependent traversability scores. This formulation enables the learning of robot-agnostic visual terrain priors that can be combined with robot-specific experience for downstream tasks such as traversability estimation, visual odometry, and mission planning. To enable large-scale training with diverse terrain appearances, we extend the OAISYS simulator and introduce RUGDSynth, a synthetic dataset inspired by RUGD with class-agnostic terrain samples. Furthermore, we present the EXTerra Dataset, providing real-world images annotated with both class-specific and class-agnostic terrain labels. Experiments demonstrate the feasibility of the proposed task and the effectiveness of our joint segmentation approach in complex outdoor environments. Code and datasets will be released with this publication (after review).
### Title:
          Design of a Real-time Asynchronous Monocular Odometry for Planetary Exploration
 - **Authors:** Benat Inigo, Florian Steidle, Wolfgang Stuerzl
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We describe our preliminary design of a real-time asynchronous event-based monocular odometry for planetary exploration. Operating under strict computational constraints, planetary rovers frequently encounter complex, unpredictable environments that demand high-speed sensing and robustness to high dynamic range (HDR) lighting. Event cameras address these needs by reporting asynchronous, pixel-wise brightness changes with microsecond resolution, significantly reducing data bandwidth while maintaining robustness in extreme lighting conditions. We propose an approach based on an Error-State Kalman Filter (ESKF) that leverages this asynchronous event stream to continuously estimate camera ego-motion. The camera state is updated with every tracked position output generated by RATE, a real-time asynchronous feature tracker.
### Title:
          Con-DSO: Learning Short-Horizon Consistency Priors for RGB-D Direct Sparse Odometry
 - **Authors:** Haolan Zhang, Thanh Nguyen Canh, Chenghao Li, Ziyan Gao, Xiongwen Jiang, Nak Young Chong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual odometry (VO) is a fundamental component in robotics and augmented reality. RGB-D direct VO benefits from metric depth measurements, but it can degrade in challenging environments, where dynamic objects, occlusions, illumination changes, and unreliable depth violate the short-horizon photometric and depth-geometric consistency assumptions used by direct alignment. Existing approaches mitigate these issues through semantic filtering, explicit occlusion reasoning, illumination adaptation, or hand-crafted geometric criteria, but often rely on external modules or fixed assumptions tailored to individual failure modes, limiting their flexibility and ability to handle diverse challenges in a unified manner. In this work, we propose Con-DSO, a consistency-aware RGB-D direct sparse odometry framework that predicts dense photometric and depth-geometric consistency uncertainty from temporally adjacent RGB-D frame pairs. The consistency network is trained using flow-guided photometric errors and projective depth-consistency errors, allowing consistency violations to be represented as pixel-level uncertainty. These pairwise uncertainty predictions are converted into a host-side quality prior for keyframe-based tracking. The prior is then applied to VO through quality-aware support-pixel selection and decoupled photometric-geometric weighting during pose estimation, enabling continuous attenuation of unreliable observations rather than hard rejection or threshold-based gating. Experiments on five public RGB-D benchmarks show substantial gains over direct RGB-D VO baselines, with over 20\% absolute trajectory error reduction on ICL-NUIM and 50\%--80\% reductions on RGB-D Scenes V2, TUM/Bonn Dynamic, and OpenLORIS sequences.
### Title:
          SA4Depth: Consistent Pose-Depth Scale Alignment for Self-Supervised Monocular Depth Estimation
 - **Authors:** Changxuan Li, Nadine Berner, Nassir Navab, Federico Tombari, Stefano Gasperini
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-supervised depth estimation from monocular sequences relies on the joint learning of a depth and a pose network. Despite abundant research done to improve the depth network, efforts on the pose remain limited. In this context, even when depth is estimated up to scale, we highlight the importance of the alignment between the scene scales estimated by the pose and depth nets. Then, we introduce SA4Depth, an approach to improve this alignment and boost the depth predictions while keeping the inference time unchanged. Our proposed method uses the depth estimated during training to reproject learnable visual features across consecutive frames and refine the pose estimates by reducing feature alignment residuals. With our method, the estimated scene scales by the separate depth and pose networks are aligned, and the prediction scale consistency is improved across different sequences. Our differentiable refinement integrates seamlessly into existing self-supervised pipelines and substantially improves their depth estimates. We demonstrate this with extensive experiments both outdoors and indoors on KITTI, Cityscapes, and NYUv2. Additionally, results on KITTI Odometry confirm the effectiveness of our pose refinement. Our code is available at this https URL .
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          IMU Propagation as Preintegration
 - **Authors:** Jianzhu Huai
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 IMU preintegration is widely used in factor-graph-based visual--inertial, lidar--inertial, and radar--inertial state estimation, yet it is often treated as a specialized implementation separate from conventional IMU propagation. This note shows that IMU preintegration and propagation are equivalent realizations of the same underlying computation. We present a convention-agnostic view in which the preintegrated measurement, bias Jacobians, and covariance can be obtained by wrapping an existing IMU propagation routine, while a preintegration module can conversely recover state-transition matrices and propagated covariances. This perspective simplifies the reuse of existing propagation code, supports translation across different error-state definitions, and provides practical consistency checks for preintegration implementations. Experiments with random IMU sequences demonstrate close agreement between an RK4-based propagation implementation and GTSAM's tangent and manifold preintegration modules in the recovered Jacobians, covariances, and transition matrices.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          CLEAR-NeRF: Collinearity and Local-region Enhanced Accurate 3D Reconstruction in Unbounded Scenes
 - **Authors:** Vladislav Polianskii, Elijs Dima, Isabel Salmerón Marazuela, Gergő László Nagy, Sigurdur Sverrisson, Volodya Grancharov
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many real-world 3D reconstruction applications demand photorealism and metric accuracy across unbounded, complex scenes with challenging lighting and imperfect captures that current Neural Radiance Field (NeRF) pipelines only partly satisfy. This study adapts NeRF-based 3D reconstruction to multi-region of interest unbounded scenes to improve robustness to lighting and pose variation while enforcing metric accuracy suitable for digital-twin applications. Our approach introduces (i) automated local region localization/detection and reconstruction to seamlessly prioritize areas of interest without proliferating submodules, (ii) collinearity-enforcing ray sampling to learn smooth planar and curved surfaces, (iii) depth-localized neighborhood point extraction to suppress surface artifacts, and (iv) geometry-relevant color aggregation to mitigate lighting- and pose-caused variations. Results indicate superior performance of the proposed pipeline over the baseline NeRF models and established Structure from Motion (SfM) - Multi-View Stereo (MVS) solutions.
## Keyword: mapping
### Title:
          IGADA-IoT: IoT Sensor Energy Optimization in Wireless Sensor Networks Driven by Automatic Data Augmentation
 - **Authors:** Mingchun Sun, Rongqiang Zhao, Muhammad Abdul Munnaf, Jie Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In wireless sensor networks (WSNs), data augmentation is a novel method to improve sampling-frequency decision performance, thereby enabling energy optimization for IoT (Internet of Things) sensors. However, existing methods rely on a single generator and empirically determined quantities, failing to establish a mapping between dynamic information gaps and multiple generators, and overlooking the heterogeneity of generated samples. Moreover, an evaluation and a closed-loop method that jointly considers the information gap and the model performance are lacking. To address these issues, we propose an information gap-guided IoT sensor automatic data augmentation framework (IGADA-IoT) with hierarchical multi-generator collaboration and scheduling over multiple rounds. Capabilities of different generators are jointly utilized to reduce the information gaps. In the IGADA-IoT, a hierarchical multi-generator collaboration and scheduling strategy (HMGCS) is proposed to enhance the targetedness and rationality of generated sample allocation. An information gap-model performance joint evaluation and closed-loop method (IGMP-EC) is proposed to enhance the accuracy of augmentation decisions, and to mitigate the risks of under-augmentation and over-augmentation. Experimental results show that the IGADA-IoT improves the average accuracy of multiple downstream models by 7.27%. Compared with advanced data augmentation methods, the average accuracy is improved by 8.67%. Compared with the individual generators, the average accuracy is improved by 7.24%. Furthermore, public IoT sensor datasets from the UCR Archive and real-world deployments demonstrate the accuracy and generalizability of the proposed method.
### Title:
          $E^3$-Agent: An Executable and Evolving Agent for Resource Management of Edge Generative Inference
 - **Authors:** Rui Bao, Yaping Sun, Zhiyong Chen, Feng Yang, Meixia Tao, Nan Li, Wenjun Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Edge deployments of generative inference increasingly face two practical realities: per-device per-model performance is often unknown at deployment time, and it is non-stationary due to user-driven semantic events, background load, and device churn. Consequently, a resource manager that is tuned offline under a fixed regime can become brittle and expensive to maintain. This paper presents $E^3$-Agent, an executable and evolving agent for edge artificial intelligence generated content (AIGC) resource management. $E^3$-Agent separates a fast-path router that makes millisecond-level dispatch decisions from a slow-path, event-driven large language model (LLM) meta-controller that mitigates regime shifts through a small, explicit control surface exposed via a tool interface, including risk gating, router configuration, and rapid performance calibration. The agent learns online from execution feedback and continuously adapts to unknown and time-varying service-time mappings. We evaluate $E^3$-Agent in a discrete-event simulator driven by MLPerf-derived device-model measurement priors, covering cold-start warmup and three dynamic regimes: semantic dynamics, device churn, and hidden drift. Across the dynamic scenarios, $E^3$-Agent reduces average latency by 65%-73% compared to the best static baseline, stays within 7%-10% of an online full-information Oracle used for evaluation, and effectively suppresses stutter rate under semantic degradation.
### Title:
          Context-aware Simopt-Power: Using structural data with simulation metadata to optimise FPGA designs
 - **Authors:** Eashan Wadhwa, Georgios Floros, Shanker Shreejith
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pre-implementation behavioural simulation routinely validates functional correctness, yet it also produces rich switching-activity traces that are typically discarded by FPGA computer-aided design (CAD) flows. Prior simulation-guided and power-aware FPGA optimisations demonstrate the promise of exploiting this metadata, but many rely on fixed thresholds, narrow decision heuristics, or limited design awareness, often incurring substantial area overhead. This paper presents Context-aware Simopt-Power, a simulator-guided optimisation framework that combines activity metadata with lightweight structural features (sequential proximity, logic-depth proxies, and fan-out estimates) to more precisely target high-impact regions of the netlist. We additionally remove empirically tuned constants, replacing them with architecture-aware parameters such as LUT size and mapping constraints, and evaluate trade-offs using power, delay, and a more useful metrics, area-delay product (AD) and power-delay product (PD). Implemented in an open-source Yosys/ABC flow and evaluated on the complex Koios deep-learning accelerator benchmarks, Context-aware Simopt-Power achieves an average 6.8% dynamic-power reduction while limiting LUT overhead to 11.2%, thus enabling a holistic design optimisation.
### Title:
          A Methodology to Assess Power Modeling in Energy-Aware Federated Learning on Heterogeneous Mobile Devices
 - **Authors:** Chaimae Jallouli, Karim Boubouh, Robert Basmadjian
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Machine Learning (cs.LG); Performance (cs.PF)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Estimating CPU power on heterogeneous ARM-based commodity devices is challenging due to limited access to CPU's voltage domains. As a result, state-of-the-art energy-aware Federated Learning (FL) frameworks typically rely on simplified approximate power models to estimate computation energy, rather than the more accurate analytical CMOS-based model. To bridge this gap, we propose a reproducible CPU power estimation methodology combined with a rail-to-cluster mapping technique to retrieve cluster-level supply voltage. We evaluate our approach on two commodity Android devices and show that the analytical model predicts CPU power with errors below 10%, whereas the approximate model incurs errors of up to 959%. Using AnycostFL, a state-of-the-art energy-aware FL framework, we show that the analytical model achieves the same 80% model accuracy while consuming 1.4x less energy than the approximate model. These results highlight that approximate models can severely misestimate computation energy and lead to suboptimal decisions. This work facilitates the use of analytical CPU power models on heterogeneous multi-cluster ARM-based mobile SoCs without additional hardware support or external power measurement tools.
### Title:
          Trinity: Unifying Class-Agnostic Terrain and Semantic Segmentation for Unstructured Outdoor Environments by Leveraging Synthetic Data
 - **Authors:** Marcus G Müller, Wout Boerdijk, Maximilian Durner, Riccardo Giubilato, Abel Gawel, Wolfgang Stürzl, Roland Siegwart, Rudolph Triebel
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Terrain understanding is fundamental for mobile robots operating in unstructured outdoor environments. Existing vision-based traversability estimation methods rely on robot-specific annotations or semantic class mappings, limiting transferability across platforms and requiring costly re-annotation when robot capabilities change, while standard semantic segmentation methods only focus on specific predefined classes, which do not capture the variety of terrains. In this work, we propose a transformer-based architecture that jointly performs class-specific semantic segmentation and class-agnostic terrain segmentation within a unified network, called Trinity. Terrain regions are segmented based solely on visual appearance, without predefined semantic labels or robot-dependent traversability scores. This formulation enables the learning of robot-agnostic visual terrain priors that can be combined with robot-specific experience for downstream tasks such as traversability estimation, visual odometry, and mission planning. To enable large-scale training with diverse terrain appearances, we extend the OAISYS simulator and introduce RUGDSynth, a synthetic dataset inspired by RUGD with class-agnostic terrain samples. Furthermore, we present the EXTerra Dataset, providing real-world images annotated with both class-specific and class-agnostic terrain labels. Experiments demonstrate the feasibility of the proposed task and the effectiveness of our joint segmentation approach in complex outdoor environments. Code and datasets will be released with this publication (after review).
### Title:
          Carbon-Aware Mapping and Scheduling for Deadline-Constrained Workflows
 - **Authors:** Dominik Schweisgut, Anne Benoit, Yves Robert, Henning Meyerhenke
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As datacenters continue to grow in scale, their energy consumption and resulting carbon footprint have become pressing concerns. With the increasing share of renewable energy in a datacenter's mixed energy supply, shifting task execution to periods of high green-power availability is a promising strategy to reduce carbon emissions. However, in heterogeneous computing environments, the power consumption of compute nodes in a datacenter can also vary. In practice, workloads submitted to datacenters are often not isolated tasks, but entire workflows consisting of interdependent tasks with precedence constraints. A further challenge arises from the fact that carbon emission reductions must typically be achieved under strict workflow deadlines. In this work, we show that the problem posed by these challenges for the scheduler is NP-hard and admits no constant-factor approximation even for the uni-processor case. Motivated by this hardness, we present a novel algorithm CWM that combines carbon-aware mapping and scheduling to construct feasible solutions. Our approach integrates dynamic programming with efficient heuristics to exploit renewable energy availability and infrastructure heterogeneity. To assess the quality of the new algorithm, we evaluate it against the state-of-the-art approach CaWoSched and show that CWM achieves significant reductions in terms of carbon emissions in experiments. In particular, we are able to achieve a median carbon cost reduction of 42% over the best version of CaWoSched when the deadline is two times the makespan of a carbon-agnostic baseline. Note that CaWoSched itself already reduces the carbon-agnostic baseline by 36%.
### Title:
          DEPART: DEcomposing PARiTy across Multilingual LLMs
 - **Authors:** Manan Uppadhyay, Prashant Kodali, Pranjal Chitale, Reshma Ramaprasad, Himanshu Beniwal, Sunayana Sitaram
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multilingual Large Language Models (mLLMs) leaderboards report per-language accuracy but rarely explain why disparities emerge, leaving systemic biases unattributed and offering practitioners no actionable levers. We first establish that these gaps are systematic rather than artifacts of sampling noise via distribution-free Friedman and Kruskal--Wallis tests, then introduce a two-step Bayesian hierarchical framework that decomposes multilingual performance variance into interpretable components. First, isolating the variance attributable to language identity, we show that observable language features (script, family, typological distance) explain $R^2_{\text{ling}} = 79\%$ of this variance on understanding tasks and $92\%$ on reasoning, with a model's internal representational similarity to English emerging as the dominant predictor across both task buckets. Second, decomposing the full (model$\times$benchmark$\times$language) cube, we find that NLU and reasoning have fundamentally divergent variance profiles: model identity dominates understanding ($66.7\%$ of variance), whereas the benchmark$\times$model interaction dominates reasoning ($46.3\%$). Together these results recast multilingual evaluation from passive performance mapping into an explainable, diagnostic framework with concrete levers for targeting the root drivers of language disparity.
### Title:
          Provably Guaranteed Polytopic Uncertainty Quantification for SLAM
 - **Authors:** Guangyang Zeng, Yulong Gao, Yuan Shen, Lingpeng Chen, Haoying Li, Guodong Shi, Junfeng Wu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In safety-critical robotics applications, guaranteed and practical uncertainty quantification (UQ) in perception is vital. Many existing works either offer no formal containment guarantee, rely on restrictive modeling assumptions, or focus only on pose estimation rather than a complete SLAM pipeline. This paper presents provably guaranteed UQ algorithms for 3D-3D landmark-based SLAM. The algorithms consist of three basic UQ modules: forward UQ for mapping, backward UQ for pose tracking, and pose compound. Each module produces a certified uncertainty set; when the input uncertainty bounds are deterministic, the output sets inherit deterministic guarantees, i.e., they provably contain the true poses and landmarks. Specifically, we use polytopes to represent uncertainty sets, enabling tractable computations and a unified treatment of pose uncertainty. To enhance algorithms' practical usability, we incorporate conformal prediction to calibrate measurement uncertainty from data with prescribed probability. Simulations and experiments demonstrate that the proposed algorithms provide both strong theoretical guarantees and practical usability. The code is open-sourced at this https URL.
### Title:
          Geometry-First Generative Spatial Single-Cell Reconstruction
 - **Authors:** Ehtesamul Azim, Muhtasim Noor Alif, Tae Hyun Hwang, Yanjie Fu, Wei Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Genomics (q-bio.GN)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Single-cell RNA sequencing (scRNA-seq) profiles large numbers of cells but loses spatial context, whereas spatial transcriptomics (ST) preserves partial spatial structure at lower resolution. Most existing integration methods either deconvolve spot mixtures or map cells onto a measured spot lattice, which ties reconstructions to a fixed grid and slide-specific coordinate systems, a limitation that is especially problematic in unpaired settings. We propose GEARS, a geometry-first framework that reconstructs an intrinsic single-cell spatial geometry guided by ST, without relying on cell-type labels, histological images, or cell-to-spot assignment. GEARS first learns a domain-invariant expression encoder that aligns ST spots and dissociated cells, and then trains a permutation-equivariant generator with a diffusion-based refiner with EDM-style preconditioning to generate local spatial geometries under pose-invariant supervision derived from ST coordinates. At inference, GEARS reconstructs geometry on many overlapping subsets of scRNA-seq cells, aggregates predicted pairwise distances across subsets, and solves a global distance-geometry problem to obtain canonical two-dimensional coordinates and a dense distance matrix. Extensive quantitative and qualitative experiments, including cross-section generalization, show that GEARS consistently improves global distance preservation, local neighborhood fidelity, and spatial distribution alignment compared to strong spatial mapping and deconvolution baselines.
### Title:
          AtomComposer: Discovering Chemical Space from First Principles with Reinforcement Learning
 - **Authors:** Bjarke Hastrup, Francois Cornet, Tejs Vegge, Arghya Bhowmik
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Materials Science (cond-mat.mtrl-sci)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Discovering novel stable molecules without training data remains a grand scientific challenge. Current molecular generative models are trained on large, pre-curated datasets, which introduce biases and limit exploration of novel chemistry. In contrast, we propose a new paradigm: autonomous, generalized agents capable of mapping vast, unknown chemical spaces without any pretraining. For the first time, we present AtomComposer, a self-guided agent that autonomously constructs valid 3D isomers under stoichiometric constraints and is trained exclusively online using reinforcement learning. Unlike existing approaches that generally overfit to a specific chemical formula, we establish a multi-composition training scheme that enables a broad generalization across diverse chemistry, guided by energy- and validity-based rewards. Our agent can discover up to an order of magnitude more valid isomers on unseen test formulas than existing single-composition reinforcement-learning baselines trained with per-step energy rewards. These results fulfill the promise of online reinforcement learning as a powerful paradigm for scalable, from-scratch exploration of chemical configuration space.
### Title:
          Bound-Constrained Sparse Representation for Electrical Impedance Tomography
 - **Authors:** Chun Zhang, Dong Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This study proposes a bound-constrained sparse representation (BC-SR) framework for electrical impedance tomography (EIT), aimed at improving conductivity estimation without explicit regularization. BC-SR adopts a representation-driven strategy, generating conductivity from low-dimensional latent variables via an implicit composite parameterization. Structural priors are embedded using a truncated graph-Laplacian basis, while a bound-preserving nonlinear mapping enforces admissible conductivity ranges and improves conditioning through implicit gradient modulation. The approach ensures robust convergence, even under noisy or incomplete data. Extensive validation on 2D/3D simulations, tank experiments, and in-vivo lung data shows that BC-SR improves physical consistency and structural fidelity, offering enhanced robustness compared to traditional methods. Additionally, BC-SR enables 3D time-difference EIT reconstruction, offering improved spatial resolution and a more coherent representation of 3D conductivity distributions, particularly for in-vivo lung data. This suggests potential for improved performance in EIT, particularly in clinical applications for respiratory monitoring.
### Title:
          Sketch2Motion: Text-driven 2D Sketch to 3D Animation via Diffusion-guided Skeleton Optimization
 - **Authors:** Gaurav Rai, Ojaswa Sharma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Animation of 2D hand-drawn sketches provides an effective medium for visual communication. However, these sketches pose challenges, particularly in handling occlusions and accurately mapping motion. While 3D animation naturally addresses these challenges, estimating 3D motion remains a very complex task. Recent approaches to converting 2D sketches to 3D animations have mainly focused on specific types of motion, such as bipedal movements and facial expressions. We propose Sketch2Motion, a diffusion-guided framework for skeleton-based motion synthesis that combines classical character animation pipelines with deep generative priors. Our method represents motion using skeletal transformations, which are propagated to mesh deformations via linear blend skinning. To guide the resulting animation toward realistic and semantically meaningful motion, we integrate a text-to-video diffusion model via motion-aware score-distillation sampling (MoSDS), enabling optimization without paired motion data. Additionally, we apply physics-inspired smoothness, topological, and contact constraints to stabilize optimization and preserve motion plausibility. Further, we integrate a spring-mass simulator to introduce secondary motion effects. The proposed framework is generalized, fully differentiable, modular, and compatible with biped, quadruped, and non-living articulated characters. Experiments demonstrate that our approach produces temporally coherent, text-aligned animations that outperform baseline motion transfer methods that lack generative priors or explicit physical constraints. We will make our code and dataset publicly available.
### Title:
          Bilinear Coordinate Alignment for Training-Free Task-Vector Transfer
 - **Authors:** Jungyong Son, Jinwook Jung, Minhee Park, Sungyong Baik
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fine-tuning large-scale pre-trained models is a recent prevalent paradigm for adapting general representations to specialized tasks. However, when a new version of a pre-trained model becomes available, expertise acquired through fine-tuning cannot be directly reused because it is tied to the parameterization of the original model, requiring another costly fine-tuning. To address this inefficiency, recent work uses task vectors, defined as the parameter difference between a fine-tuned model and its base model, to transfer expertise across models. While existing methods bridge disparate models by matching activations or gradients, a significant performance gap remains relative to direct fine-tuning, suggesting that these partial correspondences are insufficient. In this work, instead of viewing a task vector merely as a parameter offset, we revisit the formation of task vectors and show that they can be derived as accumulated bilinear interactions between input-side activations and output-side gradients. Motivated by this observation, we formulate task-vector transfer as a dual-space alignment problem and propose BiCo, a training-free framework for transferring task vectors through Bilinear Coordinate alignment. BiCo estimates orthogonal Procrustes mappings in both spaces using a single forward-backward pass on a small calibration set, without any parameter update. Across extensive computer vision and natural language processing benchmarks, BiCo consistently outperforms existing transfer methods across models that differ in width, depth, and pre-training configuration.
### Title:
          Resolution-free neural surrogates for geometric parameterization and mapping with spatially varying fields
 - **Authors:** Yanwen Huang, Lok Ming Lui, Gary P. T. Choi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many imaging problems require computing spatial transformations induced by spatially varying intensity, feature, or density fields. Canonical examples include distortion correction, deformable image registration, atlas-based segmentation, and deformation-driven image analysis. These tasks can be formulated as geometric mapping problems in which the transformation is constrained to preserve local structure, control boundary behavior, or regulate angular distortion. Such formulations typically lead to variational models, diffusion processes, or elliptic partial differential equations. However, repeatedly solving high-resolution systems becomes computationally expensive when the underlying parameter fields vary across instances. In this work, we propose a resolution-free neural surrogate for geometric parameterization and mapping problems. Given a spatially varying parameter field $p:\Omega\to\mathbb{R}^m$ and query locations $\{x_i\}_{i=1}^N\subset\Omega$, the model predicts mapped locations $\{u(x_i)\}_{i=1}^N$ on arbitrary structured or unstructured point sets. To avoid dependence on a fixed grid, we use a multi-resolution geometric encoding strategy that conditions the network on coordinate-augmented samples of the parameter field. The model is trained without labeled solution data by enforcing geometry-aware constraints derived from variational energies, diffusion-based density equalization, and quasi-conformal theory. Experimental results on quasi-conformal mapping and density-equalizing mapping problems are presented to demonstrate the effectiveness of our proposed method.
### Title:
          Position: Retire the "Positive Backdoor" Label -- Secret Alignment Requires Strict and Systematic Evaluation
 - **Authors:** Jianwei Li, Jung-Eun Kim
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This position paper argues that the AI/ML community should stop overclaiming and retire the label "positive backdoor," and instead treat trigger-activated hidden behaviors as Secret Alignment. Crucially, protective claims based on Secret Alignment should be presumed not secure by default unless supported by rigorous, standardized evaluation. The Private AI era, enabled by open-weight LLMs and accessible training/inference stacks, turns language models into privately owned digital assets, creating security concerns around unauthorized access, model theft, and behavioral misuse. Recently, a line of work framed as "positive backdoors" has been proposed to address these challenges. To ground our position in evidence, we unify these proposals as covert trigger-behavior associations for access gating, ownership attribution, and safety enforcement, and evaluate three representative applications across six core properties: effectiveness, harmlessness, persistence, efficiency, robustness, and reliability. Our results reveal substantial brittleness - especially in the confidentiality, integrity, and availability (CIA) - of trigger-behavior mappings often underrepresented by existing claims. We further relate these outcomes to behavior density and decision complexity, offering a behavioral lens for understanding deployment-time risks and motivating community-wide evaluation that makes Secret Alignment claims provable.
### Title:
          PrimitiveVLA: Learning Reusable Motion Primitives for Efficient and Generalizable Robotic Manipulation
 - **Authors:** Yutai Li, Shaohui Peng, Jiaming Guo, Di Huang, Zihao Zhang, Yuxuan Guo, Yunkai Gao, Siming Lan, Ling Li, Xing Hu, Yunji Chen
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models offer a promising paradigm for generalist robotic policies, yet their adaptation is hindered by data inefficiency and poor generalization. We argue that these bottlenecks stem from the prevailing Direct Instruction-to-Control Mapping, which forces models to memorize monolithic trajectories rather than reusable motion patterns, i.e., primitives. We propose PrimitiveVLA, a framework that shifts this paradigm toward a Primitive-Centric Disassemble & Assemble paradigm. Supported by a shared Multimodal Canonical Representation (MCR), PrimitiveVLA unifies two phases: (1) Fine-tuning-phase Disassembly, which uses an automated pipeline to disassemble demonstrations into reusable primitives; and (2) Inference-phase Assembly, which employs a VLM-based planner and an LLM-generated switch module for robust closed-loop execution. By disassembling tasks into reusable primitives, PrimitiveVLA enables VLA models to learn invariant motion patterns instead of task-specific trajectories. Extensive experiments show that our framework improves data efficiency and achieves superior zero-shot generalization across unseen and long-horizon tasks.
## Keyword: localization
### Title:
          Backdoor Attacks on Fault Detection and Localization in Cyber-Physical Systems
 - **Authors:** Abile Jean, Kuniyilh S
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cyber-Physical Systems (CPS) integrate sensing, communication, computation, and control to support critical infrastructure, including smart grids, industrial automation, and control systems. In the electrical utility domain, various controllers are used in CPS to ensure the system detects and recovers from faults, such as voltage fluctuations, and to perform load balancing in distribution systems. Machine learning- and deep learning-based fault detection and localization frameworks have recently gained significant attention in CPS for their ability to identify anomalies and operational failures in real time. However, these intelligent models are vulnerable to adversarial machine learning attacks, particularly backdoor attacks. In a backdoor attack, an adversary injects malicious patterns into the training data so that the model behaves normally most of the time but produces attacker-controlled outputs when triggered by specific patterns. This paper investigates the threat of backdoor attacks against fault detection and localization mechanisms in recent ML pipelines used in modern CPS systems. We define these threats and explore how they can be realized by designing triggers and evaluating their success in the CPS domain. Our experiments show the attack is successful even with 10\% of poisoning.
### Title:
          Can Entry-Wise Clipping Give Spectral Control of Stochastic Gradients?
 - **Authors:** Zitao Song, Cedar Site Bai, Zhe Zhang, Brian Bullins, David F. Gleich
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Training instabilities such as loss spikes are frequently the result of stochastic gradient noise. Because of rare expressions in language training data, and multiple layer composition, the noise impact is heavy-tailed and survives mini-batch averaging. Existing remedies trade off structure against cost: vector-norm clipping ignores the matrix structure of weight updates, while spectral normalization (e.g., Muon (Jordan et al., 2024)) respects it at additional cost. We show that this trade-off can be balanced. Real gradient noise appears to be similar to entry-wise heavy-tailed contamination, and a first-order perturbation analysis reveals a localization property of such noise, under which a simple entry-wise method achieves spectral control. Exploiting this, we derive a tractable surrogate for the Bayes-optimal entry-wise estimator under a Gaussian signal prior. We establish $O(\epsilon^{-4})$ convergence guarantee under Cauchy-contaminated noise. Empirically, we find that smooth shrinkage improves Adam on NanoGPT pretraining, saving ${\sim}7\%$ of training tokens. We further find that applying the entry-wise clipping before spectral normalization yields a ${\sim}2\%$ token saving on top of Muon.
### Title:
          SIGMA: Semantic-Difference Instruction-Grounding Mask Annotator for Text-Driven Image Manipulation Localization
 - **Authors:** Peiyu Zhuang, Jianquan Yang, Haodong Li, Zhuoying Cai, Ruitao Xie, Jishen Zeng, Baoying Chen, Jiwu Huang, Xiaochun Cao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-driven image editing has advanced rapidly, but reliably localizing these manipulations requires image manipulation localization (IML) models trained on large pixel-annotated datasets, and there is still no low-cost way to obtain such training data at scale. We observe that these data already exist in disguise: public editing datasets contain millions of structurally identical (original, edited) pairs to IML training samples, lacking only pixel-level masks. Recovering these masks automatically is non-trivial: pixel differencing is overwhelmed by diffusion-induced perturbations across all pixels, and instruction-only grounding localizes only what the prompt describes, missing unintended editor side-effects. We propose SIGMA (Semantic-difference Instruction-Grounding Mask Annotator), which performs semantic-feature differencing in a vision foundation backbone and injects an instruction-derived spatial prior into this visual stream via bidirectional cross-modal refinement, amplifying the difference signal at intended-edit regions when the editor faithfully realizes user intent. SIGMA is trained in two complementary stages: Stage I supervises on inpainting masks; Stage II closes the diffusion-domain shift via VAE-roundtrip noise calibration, EMA self-training, and an edit-noise disentanglement loss. SIGMA outperforms existing automatic mask generators on five benchmarks (+12.20% F1, +11.16% IoU). When applied to public editing corpora, it produces a ~1.1M IML training set that improves six diverse detectors by +18.34% F1 across five datasets, turning previously unused editing data into a model-agnostic supervisory resource for IML. We'll release the full codebase as soon as the paper is accepted.
### Title:
          Dual-branch Distilled Transformer for Efficient Asymmetric UAV Tracking
 - **Authors:** Hongtao Yang, Bineng Zhong, Qihua Liang, Yaozong Zheng, Xiantao Hu, Yuanliang Xue, Shuxiang Song
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Given the real-time demands of UAV tracking, many methods simplify the backbone to reduce computation, but this often weakens feature representation and degrades performance in complex scenarios. To alleviate this issue, we propose EATrack, an efficient and asymmetric UAV tracking framework centered around a teacher-guided dual-branch distillation strategy that enhances the feature expressiveness of the lightweight student model. Specifically, EATrack investigates two complementary perspectives of knowledge transfer: spatially focused feature-level distillation that compensates for weakened representations by guiding the student to learn strong target representations, and prediction-level distillation that enhances spatial localization by learning the teacher's capability for accurate target localization. Furthermore, to enhance robustness against appearance variations, we introduce a fine-grained target-aware distillation strategy that selectively transfers the teacher's target modeling capacity to the student. A temporal adaptation module is incorporated at inference to enhance robustness over time. Experiments on five UAV benchmarks demonstrate that EATrack achieves a favorable balance between accuracy and speed. Code: this https URL
### Title:
          MTAVG-Bench 2.0: Diagnosing Failure Modes of Cinematic Expressiveness in Multi-Talker Audio-Video Generation
 - **Authors:** Haitian Li, Yanghao Zhou, Heyan Huang, Liangji Chen, YiMing Cheng, Xu Liu, Dian Jin, Jiajun Xu, Jingyun Liao, Tian Lan, Ziqin Zhou, Yueying Liu, Yu Bai, Changsen Yuan, Jinxing Zhou, Xian-Ling Mao, Xuefeng Chen, Yousheng Feng
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Multimedia (cs.MM); Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In recent years, Multi-Talker Audio-Video Generation (MTAVG) models have shown promising performance on fundamental metrics such as lip-sync and audio-visual alignment. However, these metrics remain insufficient for assessing cinematic expressiveness in scene-level generation. In multi-character scenes, generation models must go beyond audio-visual realism to convey coherent character performance and other higher-level cinematic qualities. To fill this gap, we introduce MTAVG-Bench 2.0, a benchmark for diagnosing failure modes of cinematic expressiveness in multi-talker audio-video generation. Unlike prior settings that mainly focus on the quality of basic multi-turn dialogue, MTAVG-Bench 2.0 targets short-drama and scene-level generation, and establishes a high-level failure taxonomy spanning acting, narrative, atmosphere, and audio-visual language. Based on this taxonomy, we construct more than 10,000 question-answering evaluation instances, together with subsets for short-drama-level assessment and temporal localization of failure modes, to systematically evaluate the ability of omni large language models to diagnose high-level audio-visual failures. Experimental results show that commercial omni models such as Gemini substantially outperform other evaluators, yet even the strongest models continue to struggle with complex failures in our benchmark. These results demonstrate that MTAVG-Bench 2.0 provides a systematic benchmark for failure diagnosis in cinematic multi-talker audio-video generation.
### Title:
          SAFEVPR: Patch-Based Conformal Verification for Safe Cross-Condition Sequence Visual Place Recognition
 - **Authors:** Ha Sier, Jiaqiang Zhang, Zhuo Zou, Xianjia Yu, Tomi Westerlund
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sequence-based visual place recognition (VPR) for SLAM and robot relocalization must decide whether the retrieved top-1 candidate is safe to accept. Conformal prediction is a natural framework for this accept/reject decision, but its finite-sample guarantees rely on exchangeability between calibration and deployment (test) data, which is violated under cross-condition deployment. We introduce SAFEVPR, a non-trainable verification-and-calibration pipeline for safe cross-condition sequence VPR. SAFEVPR replaces the standard backbone cosine similarity with a mutual-nearest-neighbour (MNN) patch-matching score computed from frozen DINOv2 ViT features, and replaces flat Learn-Then-Test calibration with Mondrian conformal LTT, fitting separate Bonferroni-corrected thresholds across score bins. Under exchangeability, these thresholds would provide finite-sample false-discovery-rate (FDR) control; under condition shift, we evaluate empirical validity per deployment. Across 23 cross-condition setups from Oxford RobotCar, NCLT, and St Lucia datasets, using three frozen VPR backbones, SAFEVPR is empirically valid on 23/23 setups at target FDR alpha = 0.10, achieving mean accepted FDR 0.014 and mean true-positive rate (TPR) 0.75. The results show that raw discrimination alone is not sufficient for conformal validity: AnyLoc-VLAD and Super-Point+LightGlue reach comparable area under the receiver operating characteristic curve (AUROC) but fail more setups under the same calibration. On textureless repetitive scenery, SAFEVPR safely abstains rather than accepting unreliable matches. Code is available at this https URL.
### Title:
          VLA-Hijack: A Transferable Patch Attack against Vision-Language-Action Models via Visual Proprioception Hijacking
 - **Authors:** Jiyuan Fu, Kaixun Jiang, Jingkai Jia, Zhaoyu Chen, Xueyao Chen, Lingyi Hong, Shuyong Gao, Chenzhi Tan, Dingkang Yang, Wenqiang Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Vision-Language-Action (VLA) models have emerged as powerful generalist policies, their severe vulnerability to adversarial patches significantly hinders their deployment in safety-critical domains. Moreover, existing patch attacks primarily focus on white-box settings, heavily overfitting to the specific action output space of the target model, which results in poor cross-architecture transferability. To overcome this limitation, we propose VLA-Hijack, a unified adversarial framework that breaks the transferability bottleneck by exploiting a fundamental vulnerability identified in this work: before planning any motion, a VLA model must first use visual information to locate its own robotic arm within the environment. Targeting this shared visual self-localization process, our approach concurrently optimizes Attention-Guided Proprioceptive Suppression to inhibit the real robotic arm's features, and Multimodal Proprioceptive Injection to establish the patch as a surrogate "phantom embodiment". By alternating between semantic concept anchoring and visual prototype projection, VLA-Hijack effectively severs the semantic relationship between the agent's true embodiment and its control policy. Extensive experiments across diverse architectures (OpenVLA, UniVLA, and CronusVLA) demonstrate that VLA-Hijack achieves superior optimization efficiency in white-box settings and sets a new SOTA for cross-architecture and cross-domain black-box transferability.
### Title:
          STR Robot: Design of an Autonomous Mobile Robot from Simulation to Reality
 - **Authors:** Vinh Nguyen, Gia-Uy Le, Tien-Dat Nguyen, Tri-Tin Nguyen, Vinh-Hao Nguyen
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the rapid development of simulation tools, the development and validation of autonomous robotic systems have become more efficient before real-world deployment. This paper presents a simulation-to-real implementation of an autonomous mobile robot based on an existing mechanical platform. Instead of focusing on mechanical design, our work concentrates on the development of the onboard control, self-localization, and autonomous navigation system. The proposed robot is equipped with onboard sensing and computation to estimate its pose and navigate autonomously in the environment. The overall framework is first developed and tested in simulation, and then deployed on the real robot for experimental evaluation. The results demonstrate the feasibility of the proposed approach and show that simulation provides an effective foundation for developing reliable autonomous mobile robot systems. The source code will be released at this https URL.
### Title:
          CIVIC: End-to-End Sequence Compactness for Efficient Vision-Language Models
 - **Authors:** Fengze Yang, Bo Yu, Xuewen Luo, Cathy Liu, Chenxi Liu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language Models (VLMs) face severe memory and latency bottlenecks due to high-resolution visual tokens. While current token reduction methods theoretically save FLOPs, post-hoc pruning introduces structural overhead, failing to yield proportional wall-clock acceleration. However, enforcing a contiguous compact pathway risks geometric disorientation and loss of fine-grained localization. To overcome these barriers, this paper introduces CIVIC, a path-consistent compact visual inference framework. By maintaining compact sequence representations seamlessly across the vision encoder, projection layer, LLM prefill, and KV-cache, CIVIC avoids non-contiguous memory access and localized unmerging overheads. Evaluated on the Qwen3-VL architecture, CIVIC successfully translates sequence reductions into genuine physical hardware efficiency, shrinking KV-cache memory to approximately one-third of the baseline and reducing end-to-end inference latency. Enabled by text-aligned KL distillation and an adaptive spatial retention floor, CIVIC achieves these efficiency milestones without degrading accuracy across rigorous multimodal reasoning and visual grounding benchmarks.
### Title:
          CLEAR-NeRF: Collinearity and Local-region Enhanced Accurate 3D Reconstruction in Unbounded Scenes
 - **Authors:** Vladislav Polianskii, Elijs Dima, Isabel Salmerón Marazuela, Gergő László Nagy, Sigurdur Sverrisson, Volodya Grancharov
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many real-world 3D reconstruction applications demand photorealism and metric accuracy across unbounded, complex scenes with challenging lighting and imperfect captures that current Neural Radiance Field (NeRF) pipelines only partly satisfy. This study adapts NeRF-based 3D reconstruction to multi-region of interest unbounded scenes to improve robustness to lighting and pose variation while enforcing metric accuracy suitable for digital-twin applications. Our approach introduces (i) automated local region localization/detection and reconstruction to seamlessly prioritize areas of interest without proliferating submodules, (ii) collinearity-enforcing ray sampling to learn smooth planar and curved surfaces, (iii) depth-localized neighborhood point extraction to suppress surface artifacts, and (iv) geometry-relevant color aggregation to mitigate lighting- and pose-caused variations. Results indicate superior performance of the proposed pipeline over the baseline NeRF models and established Structure from Motion (SfM) - Multi-View Stereo (MVS) solutions.
### Title:
          Identifying Explicit Parsimonious Piece-wise Polynomial Relationships in Industrial time-series: Application to manipulator robots
 - **Authors:** Mazen Alamir, Sacha Clavel
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper addresses the problem of identifying parsimonious explicit piece-wise polynomial relationships that might involve a relatively large number of raw features. The algorithm leverages a recently proposed identification algorithm that yields parsimonious implicit relationships enabling to derive normality characterization in the context of anomaly detection and localization. The algorithm proposed in this paper goes a step further by deriving explicit piece-wise representations that are built using the set of polynomials involved in the implicit representations. The framework is illustrated on the problem of identifying parsimonious explicit representations of the inverse model of a 6-axis manipulator robot. Moreover, further experiments on a 4-axis robot are also shown which are designed to investigate the generalization capability of parsimonious models compared to state-of-the-art DNNs structures, when models face unseen contexts of use.
### Title:
          Chance-Constrained MPPI under State and Dynamic Object Prediction Uncertainty and the Evaluation of Collision Risk Calibration
 - **Authors:** Benjamin Serfling, Konrad Doll, Kati Radkhah-Lens
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Chance-constrained Model Predictive Path Integral (MPPI) control is increasingly adopted for navigation in dynamic environments to explicitly bound collision risk. However, these probabilistic guarantees implicitly assume that upstream uncertainties from localization and perception are well-calibrated. In practice, estimators are often miscalibrated, inducing characteristic closed-loop failure modes: overconfidence leads to systematic safety violations, while underconfidence triggers overly conservative freezing or probability dilution. To address this critical gap, our primary contribution is a rigorous evaluation methodology applying proper scoring rules to assess the statistical validity of predicted collision risks during closed-loop execution. Concurrently, Dual-Uncertainty Chance-Constrained Tube MPPI (DUCCT-MPPI) is proposed as a real-time, risk-aware planning architecture. DUCCT-MPPI jointly integrates localization uncertainty via a one-tube Unscented Transform (UT) approximation and dynamic obstacle prediction uncertainty via Monte Carlo aggregation. Through extensive physics-based simulations, the framework demonstrates robust failure-mitigation, seamlessly transitioning to safe, conservative maneuvering without succumbing to functional deadlocks in highly cluttered environments. In highly cluttered environments, DUCCT-MPPI achieves superior robustness, outperforming established Monte Carlo MPPI baselines by nearly 28\% in navigation success rate, while simultaneously recording the lowest travel times and minimizing induced social forces. Ultimately, these findings establish that reliable probabilistic safety in autonomous navigation dictates not only expressive risk models but statistically valid uncertainty estimates throughout the entire autonomy stack.
### Title:
          Magnet-Based Soft Robotic Skin Using a 3D-Printed Multi-Lattice Structure and CNN-Based Tactile Super-Resolution
 - **Authors:** Yunseong Bang, Joowon Park, Suan Sim, Youngjun Ryu, Sukho Park, Kyungseo Park
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a magnet-based robotic skin that integrates a multilayer soft lattice with distributed Hall-effect sensor arrays and a tactile super-resolution model. External contact forces are converted to magnetic field changes by embedded permanent magnets, and the lattice spreads these changes across the sensing domain. This gives each sensor a large, overlapping receptive field and enables a large sensing area with minimal blind spots. Lattice parameters are tunable, enabling joint adjustment of mechanical compliance and transduction characteristics. An implicit modeling workflow and selective laser sintering (SLS) 3D printing support rapid fabrication of conformal, high-complexity structures. A convolutional neural network trained on experimental measurements estimates contact location and normal force in real time. Experiments validate localization accuracy and indicate scalability to larger surfaces, suggesting applicability to whole-body robotic skin and safe human-robot interaction.
### Title:
          Tactile-Proprioceptive Sensor Fusion for Contact Wrench Estimation in Whole-Body Physical Human-Robot Interaction
 - **Authors:** Junha Min, Junghyeon Ma, Jiwung Kwon, Sunggyu Bae, Joohyung Kim, Kyungseo Park
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Direct physical guidance is a natural means of teaching and interacting with robots, and robotic skins make a key contribution by enabling sensitive contact sensing and localization. This paper presents a tactile-proprioceptive sensor fusion framework for natural physical human-robot interaction. Tactile cues from pneumatic skin pads serve as contact indicators that bypass the ambiguity between frictional residues and applied external forces, enabling highly sensitive contact detection without explicit friction identification. We fuse these cues with motor-current-based proprioception to reconstruct multi-axis contact forces on the robot surface. To maintain accuracy during motion, we employ a temporal convolutional network (TCN) to mitigate friction hysteresis during stick-slip transitions, reducing uncertainty at contact onset and yielding smooth, responsive guidance. We validate the approach on a skin-integrated robot arm: (i) multi-axis forces are reconstructed in stationary contacts, and (ii) simultaneous force estimation and kinesthetic teaching are demonstrated. Results indicate improved sensitivity and responsiveness across diverse contact conditions compared with tactile-only and proprioceptive-only baselines, supporting tactile-proprioceptive fusion as a reliable pathway to safe, intuitive physical human-robot interaction.
### Title:
          Anomaly as Non-Conformity via Training-Free Graph Laplacian Energy Minimization
 - **Authors:** Jungwook Seo, Minjeong Kim, Younkwan Lee, Seungho Shin, Sungyong Baik
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Detecting subtle visual anomalies in images remains challenging, particularly when only normal samples are available a priori. Such unsupervised anomaly detection is typically solved by measuring feature similarity of a query patch to a memory of normal patches. However, similarity alone does not reveal how strongly a query patch violates the structure of the normal feature manifold. We propose a training-free Laplacian graph energy optimization formulation, named ANoCo that scores Anomaly by the cost of Non-Conformity of a query patch to align with a fixed normal manifold. For each query patch, we construct a bipartite query to normal graph weighted by cosine affinity, explicitly removing query-query and normal-normal edges to prevent evidence dilution. We formulate anomaly scoring as a convex Laplacian energy with anchored normal nodes, and solve in closed form. In particular, we do not use the optimized features themselves-the anomaly score is the magnitude of the update required to satisfy normality constraints, reframing the graph Laplacian as a non-conformity operator rather than a smoothing prior. The proposed method introduces no learnable parameters, message passing, or sampling, and has complexity comparable to a single linear solve. Across standard benchmarks, it delivers strong image-level AUROC, stable localization maps, and improved robustness over prior methods, demonstrating the effectiveness of using optimization-induced feature drift as anomaly measure.
### Title:
          REVEAL: Reference-Grounded Reasoning for Multimodal Manipulation Detection
 - **Authors:** Jun Zhou, Bingwen Hu, Yaxiong Wang, Zhedong Zheng, Yongzhen Wang, Yuchen Zhang, Ping Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal manipulation detection aims to simultaneously identify forged image--text pairs and localize tampered regions, yet existing methods typically rely on memorizing isolated artifacts and struggle with imperceptible manipulation traces or domain shifts. Inspired by human comparative reasoning, we reformulate this task as a reference-grounded verification problem, where authenticity is assessed by comparing a query against retrieved authentic evidence. We propose REVEAL Reference-Enabled Verification for Evidence Analysis and Localization), a framework explicitly designed for this comparative paradigm. To support this paradigm, we construct a large-scale reference library comprising 170K authentic news image--text pairs featuring over 40K public figures. Technically, REVEAL employs a difference-aware fusion mechanism to capture fine-grained discrepancies between the query and retrieved evidence. Furthermore, we introduce a task-decoupled Mixture-of-Experts (MoE) architecture to jointly execute instance-level detection and fine-grained grounding, effectively mitigating optimization conflicts between these heterogeneous objectives. Extensive experiments demonstrate that REVEAL significantly outperforms state-of-the-art methods, and notably enables \emph{training-free domain adaptation} by simply updating the reference library, offering a robust and practical solution for detecting evolving misinformation. Code is available at this https URL.
### Title:
          Subtraction Gets You More: Gap-Aware Retrieval for Multimodal Multi-Hop QA
 - **Authors:** Sunah O, Jay-Yoon Lee
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In multimodal multi-hop question answering, we focus on the initial retrieval stage via two distinct tasks: (1) evidence set completion, retrieving missing evidence given context, and (2) sequential pool construction, iteratively building the top-$K$ pool from the scratch. Under these settings, we point out that conventional iterative retrieval frameworks often suffer from Semantic Anchoring, where previously fetched evidence traps the retriever and yields entity-centric redundancy. To break this trap, we propose GRAIL (Gap-aware Retrieval via Adaptive Implicit Localization), a paradigm that performs implicit query rewriting directly at the embedding level. By context-subtractive query steering, GRAIL excels at compositional cross-modal reasoning, while additive embedding updates show strength on localized information aggregation. By dynamically routing queries based on task type, our Hybrid Framework achieves a 40.3\% macro-averaged performance gain on MultimodalQA. Extensive evaluations demonstrate that sequential GRAIL retrieves in a superior, noise-resilient manner, significantly expanding the search horizon through iterative gap-aware optimization.
### Title:
          OmniVerifier-M1: Multimodal Meta-Verifier with Explicit Structured Recalibration
 - **Authors:** Xinchen Zhang, Bowei Liu, Jiale Liu, Chufan Shi, Yizhen Zhang, Junhong Liu, Youliang Zhang, Zhiheng Li, Yujiu Yang, Ling Yang
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual outcomes are increasingly central to multimodal large language models, making reliable and fine-grained verification essential for scaling generalist foundation models. In this work, we investigate multimodal meta-verification, which leverages verifier-generated rationales rather than decision-only signals, and explore how to effectively incorporate meta-verification feedback into multimodal verifier training. We identify two key findings. First, symbolic verifier outputs (e.g., bounding boxes) outperform textual explanations as meta-verification rationales, enabling efficient rule-based reinforcement learning rewards while avoiding reliance on model-based rewards from auxiliary judge models. Second, decoupling reinforcement learning objectives for binary judgment and meta-verification substantially outperforms joint reward optimization, due to intrinsic differences in output structure and learning dynamics. Based on these insights, we train OmniVerifier-M1, a generalist visual verifier leveraging symbolic meta-verification and decoupled reinforcement learning. OmniVerifier-M1 provides robust verification and fine-grained error localization, and further enables M1-TTS, a verifier-driven agentic generation system achieving dynamic region-level self-correction. This approach paves the way for more reliable, interpretable, and fine-grained multimodal verification, supporting safer and more controllable foundation model deployment.
## Keyword: transformer
### Title:
          Advancing Direct Training for Spiking Neural Networks with Circulate-Firing Neurons and Learnable Gradients
 - **Authors:** Feifan Zhou, Xiang Wei, Yang Liu, Qiang Yu
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spiking Neural Networks (SNNs) have emerged with promising energy-efficient property, yet a substantial performance gap persists compared to Artificial Neural Networks (ANNs). This gap stems from at least two key limitations: first, conventional spiking neurons offer limited information representation capacity, underutilizing the rich dynamics of membrane potentials; second, fixed surrogate gradient (SG) functions across time steps leads to imprecise gradient propagation, impeding effective direct training. To address these two challenges, we propose a new direct training algorithm with three core innovations: first, a circulate-firing spiking neuron model that enhances information representation capacity by leveraging membrane potentials more effectively; second, a time-step-wise learnable surrogate gradient function, enabling accurate gradient estimation during backpropagation; third, a positive-negative balanced loss function to achieve equilibrium between positive and negative membrane potentials and further boost SNN performance. Extensive experiments demonstrate that our methods achieve competitive performance across multiple datasets. Our methods can generalize seamlessly to advanced architectures of Transformer, consistently outperforming existing methods. Our work highlights the effectiveness of further harnessing intrinsic membrane dynamics of SNNs for performance improvement, and thus open a new avenue for advancing high-performance spiking neural architectures.
### Title:
          Generic Interpretation Approach for Transformer Models Incorporating Heterogenous Attention Structures
 - **Authors:** Yongjin Cui, Xiaohui Fan, Huajun Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer has significantly propelled the development of artificial intelligence, and certainly the development of agents as well. We categorize attention structures of Transformer into two types based on the source of the input information: homogenous and heterogenous attention structures. Heterogenous attention structures, with co-attention as a typical example, process information from different sources. Heterogenous attention structure is the foundation for Transformer models to achieve more complex functions and integrate more modal information. Whether for research purposes or policy requirements, the interpretation of Transformer models with heterogenous attention structures is an important task. The fusion of information from different sources brings new challenges. Our work mainly includes two parts: method and experimentation. In terms of method, we propose an interpretation method for Transformer models with heterogenous attention structures. In terms of experimentation, based on our experimental analysis paradigm, we interpret the operating mechanisms of representative models, conduct semantic interpretation and logical interpretation.
### Title:
          AdaMerge: Salience-Aware Adaptive Token Merging for Training-Free Acceleration of Vision Transformers
 - **Authors:** Semi Lee, Hyejin Go, Hyesong Choi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The quadratic cost of self-attention in Vision Transformers (ViTs) constitutes a fundamental bottleneck for practical deployment, motivating a vibrant line of research on token reduction. Among existing approaches, token merging (ToMe) has emerged as an elegant training-free solution; yet its design rests on an unspoken premise of token equality, which contravenes the well-documented non-uniformity of self-attention and leads to information loss in high-salience tokens under aggressive compression. We address this limitation with AdaMerge, a token-merging framework based on two complementary mechanisms. First, salience-weighted similarity leverages column-wise feature-affinity centrality as a token-importance proxy and incorporates the resulting salience scores into the bipartite matching score, ensuring that pivotal tokens contribute more strongly to the merged representation. Second, adaptive merging intensity uses pre-computed layer-wise similarity statistics to dynamically modulate the per-layer reduction count in accordance with input-specific redundancy. On ImageNet-1k with ViT-B/16, AdaMerge consistently outperforms ToMe, PiToMe, and DSM across all FLOPs-matched regimes. The accuracy gap widens monotonically with compression: at the 13.4G FLOPs operating point, AdaMerge sustains a Top-1 degradation of only -1.06%, compared to -1.45% for PiToMe and -4.62% for DSM. To our knowledge, AdaMerge is the first to combine salience-weighted similarity and adaptive per-layer reduction into a single training-free token merging framework, advancing the accuracy-FLOPs Pareto frontier of ViT acceleration.
### Title:
          Balancing Fidelity and Diversity in Diffusion Models via Symmetric Attention Decomposition: Hopfield Perspective
 - **Authors:** Hyunmin Cho, Woo Kyoung Han, Kyong Hwan Jin
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We characterize the pre-softmax attention matrix $\mathbf{QK^\top}$ in transformers as an associative memory matrix encoding pairwise associations between input features. By decomposing this matrix into its symmetric and skew-symmetric parts, we interpret the symmetric component as governing the structure of the energy landscape, and the skew-symmetric component as driving circulation on that landscape. Leveraging the energy formulation induced by the symmetric component, we derive Hopfield-style stability measures that quantify the stability of retrieved features. We observe meaningful correlations between Hopfield-style stability measures and the fidelity-diversity trade-offs in generation. Finally, we propose a controllable knob to modulate this trade-off by modifying the circulation of the underlying dynamics. Code is available at our GitHub (this https URL).
### Title:
          GenSBI: Generative Methods for Simulation-Based Inference in JAX
 - **Authors:** Aurelio Amerio
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Cosmology and Nongalactic Astrophysics (astro-ph.CO); Instrumentation and Methods for Astrophysics (astro-ph.IM); Computational Physics (physics.comp-ph); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Flow and diffusion generative models have established themselves as widely adopted density estimators for simulation-based inference (SBI), extending naturally from neural posterior estimation to likelihood and joint density estimation. Their principled optimization objectives and freedom from architectural constraints have driven rapid adoption across the natural sciences. Yet the most widely used SBI libraries remain PyTorch-based, leaving researchers who develop their forward models and analysis pipelines in JAX without a native option. We present GenSBI, an open-source library that implements flow matching, score matching, and denoising diffusion entirely in JAX. The library offers three transformer-based architectures - SimFormer, Flux1, and a novel Flux1Joint that extends gate-modulated transformer blocks to joint density estimation - all interchangeable through a unified interface that decouples generative method, neural backbone, and inference mode. GenSBI provides an end-to-end workflow from training through posterior calibration (SBC, TARP, LC2ST) and supports custom architectures with domain-specific embedding networks. We validate the framework on standard SBI benchmarks, achieving near-ideal mean C2ST scores (0.50-0.56, where 0.50 is ideal) on SBIBM tasks with minimal per-task tuning and well-calibrated posterior coverage across all tested configurations. The code is publicly available at this https URL.
### Title:
          From Centerlines to Hemodynamics: Anisotropic RBF Decoders for Coronary Arteries
 - **Authors:** Reza Akbarian Bafghi, Sukirt Thakur, Maziar Raissi
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate and rapid estimation of hemodynamic metrics, such as pressure and wall shear stress (WSS), is important for assessing the severity of Coronary Artery Disease (CAD). Existing approaches, including invasive Fractional Flow Reserve (FFR) measurements and computationally expensive Computational Fluid Dynamics (CFD) simulations, face challenges in invasiveness, cost, and speed. We present a framework for fast, non-invasive coronary hemodynamics prediction. The model encodes 1D vessel centerlines together with inlet flow rate using a transformer-based encoder, and predicts continuous wall-based fields via an anisotropic Radial Basis Function (RBF) decoder aligned with vessel morphology. To support training and evaluation, we introduce two datasets with paired steady-state OpenFOAM simulations: (i) a synthetic benchmark of 4,200 single-vessel geometries with controlled anatomical variations, and (ii) a multi-vessel dataset derived from ImageCAS including 4,800 cases spanning both right and left coronary arteries, generated by randomly introducing stenoses and varying physiologically plausible flow rates. Across both datasets, our method achieves lower pressure and WSS errors than strong neural-operator baselines (GNOT, Transolver, and ONO) at a fraction of the computational cost of CFD. On the multi-vessel dataset, using 1,024 anisotropic RBF centers our model reduces the mean relative L2 error by 52% compared to the best neural-operator baseline, while at 128 centers it requires 13.8x fewer FLOPs than GNOT and still outperforms all baselines. The single-vessel dataset is publicly available at this https URL.
### Title:
          Gradient Transformer: Learning to Generate Updates for LLMs
 - **Authors:** Binh-Nguyen Nguyen, Khang Tran, NhatHai Phan, Issa Khalil
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many organizations lack computational resources to fine-tune large language models (LLMs) on private (unshareable) data for better utility, while fine-tuning tiny language models (TinyLMs) alone performs poorly. To address this bottleneck, we propose a data-free knowledge distillation framework that generates LLM update vectors based on TinyLMs fine-tuned on private data. An update vector is a vector of parameter changes from an initial model to its fine-tuned version on a dataset, capturing the effect of cumulative gradient steps during fine-tuning. The key idea of our framework is a novel Gradient Transformer that transforms TinyLM's update vectors into LLM's update vectors. As derived from shadow datasets, Grad-Transformer captures the correlation between TinyLM and LLM update vectors, enabling third-party providers to generate LLM update vectors given the organization's TinyLM update vectors without accessing the organization's private data. The framework supports multi-organization collaboration to jointly update LLMs, improving performance and cost-efficiency. Extensive experiments across language modeling and reasoning tasks show that Grad-Transformer remarkably outperforms state-of-the-art knowledge distillation baselines, even under strict differential privacy protection.
### Title:
          Not All NVFP4 QAT Recipes Are Equal: How Architecture and Scale Shape Model Quality for Anomaly Segmentation
 - **Authors:** Zijian Du, Oleg Rybakov
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-time anomaly segmentation demands both high recall and efficient low-precision inference. We study the three-way interaction of model architecture, model scale, and FP4 quantization-aware training (QAT) recipe on a recall-critical brain tumor segmentation task, evaluating multiple architectures, scales, and QAT recipes under a unified protocol. We find that architecture choice has the largest impact on quantization robustness, with attention-based architectures showing remarkable resilience to recipe choice while CNN degrades under gradient-quantizing recipes at larger scales. At low capacity, FP4 can discretize softmax attention, but advanced QAT recipes prevent this collapse. At larger scales, advanced recipes mitigate gradient quantization noise that degrades CNN quality. Five-fold patient-level cross-validation confirms these findings are robust to data partition. Our results show that the Swin Transformer is robust to QAT recipe choice across all scales, making it the recommended architecture for FP4-quantized anomaly segmentation.
### Title:
          Trinity: Unifying Class-Agnostic Terrain and Semantic Segmentation for Unstructured Outdoor Environments by Leveraging Synthetic Data
 - **Authors:** Marcus G Müller, Wout Boerdijk, Maximilian Durner, Riccardo Giubilato, Abel Gawel, Wolfgang Stürzl, Roland Siegwart, Rudolph Triebel
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Terrain understanding is fundamental for mobile robots operating in unstructured outdoor environments. Existing vision-based traversability estimation methods rely on robot-specific annotations or semantic class mappings, limiting transferability across platforms and requiring costly re-annotation when robot capabilities change, while standard semantic segmentation methods only focus on specific predefined classes, which do not capture the variety of terrains. In this work, we propose a transformer-based architecture that jointly performs class-specific semantic segmentation and class-agnostic terrain segmentation within a unified network, called Trinity. Terrain regions are segmented based solely on visual appearance, without predefined semantic labels or robot-dependent traversability scores. This formulation enables the learning of robot-agnostic visual terrain priors that can be combined with robot-specific experience for downstream tasks such as traversability estimation, visual odometry, and mission planning. To enable large-scale training with diverse terrain appearances, we extend the OAISYS simulator and introduce RUGDSynth, a synthetic dataset inspired by RUGD with class-agnostic terrain samples. Furthermore, we present the EXTerra Dataset, providing real-world images annotated with both class-specific and class-agnostic terrain labels. Experiments demonstrate the feasibility of the proposed task and the effectiveness of our joint segmentation approach in complex outdoor environments. Code and datasets will be released with this publication (after review).
### Title:
          Tensor Memory: Fixed-Size Recurrent State for Long-Horizon Transformers
 - **Authors:** Kabir Swain, Sijie Han, Daniel Karl I. Weidele, Mauro Martino, Antonio Torralba
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers process images and videos by flattening space and time into long token sequences. While attention and KV caching preserve past features, their memory grows with sequence length and they lack an explicit, persistent spatial state, making long-horizon video understanding and occlusion-sensitive reasoning difficult. We propose Tensor Memory, a lightweight module that augments Transformer blocks with a fixed-size recurrent 3D memory tensor: tokens write into a voxel grid via a differentiable soft write that deposits content as a Gaussian-weighted volume around a predicted continuous 3D location, the memory is updated with an efficient local interaction operator and gated recurrent dynamics, and tokens read back context via continuous sampling with gated residual fusion. Because the memory tensor has a constant size, Tensor Memory decouples state capacity from input length while preserving a spatial inductive bias. We evaluate the module on standard language, image, and video benchmarks and on a controlled toy diagnostic suite designed to isolate when persistent state is beneficial; it integrates with standard Transformer training pipelines and can be attached to or removed from existing blocks without other architectural changes.
### Title:
          Worker Disagreement Reveals Sharp Directions in Local SGD
 - **Authors:** Tolga Dimlioglu, Kristi Topollai, Anna Choromanska
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep neural network training often exhibits highly anisotropic loss geometry, where a few sharp dominant Hessian directions coexist with a large flatter bulk. Gradients tend to align disproportionately with these dominant directions, although stable progress often requires movement through flatter bulk directions. Estimating the dominant subspace is therefore useful but costly with direct Hessian-based methods. We show that standard Local SGD exposes this geometry through worker disagreement. We theoretically show that the worker-average gap covariance is shaped by stochastic-gradient noise and Hessian curvature, causing workers to disagree along sharp, curvature-sensitive directions. Thus, worker-average gaps provide a cheap Hessian-free estimator of the dominant subspace. Experiments on MLPs, CNNs, and Transformers show that subspaces formed by worker-average gaps capture a substantial fraction of the gradient component lying in the dominant Hessian eigenspace.
### Title:
          Colosseum V2: Benchmarking Generalization for Vision Language Action Models
 - **Authors:** Jeremy Morgan, Prajwal Vijay, Hyeonho Oh, Jincen Song, Ashvin Arora, Alina Du, Gaurav Sukhatme, Jesse Thomason, Ishika Singh
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models demonstrate promising generalization in robotic manipulation, driven by advances in large-scale vision and language pre-training. This progress can be misleading. Despite the zero-shot perception and language capabilities of VLAs, their overall task performance often degrades under distribution shifts, revealing gaps in how these systems translate high-level understanding into robust behavior. To systematically study this gap, we introduce Colosseum V2, a large-scale simulation benchmark for evaluating VLA generalization in robot learning across diverse conditions. The benchmark comprises 28 tasks spanning 13 task categories and two robot morphologies, covering a wide range of manipulation primitives and long-horizon behaviors. Built on the ManiSkill simulator, Colosseum V2 enables fast, GPU-parallelized evaluation and supports both in-domain and out-of-domain testing at scale. We evaluate state-of-the-art methods, including Action Chunking Transformers (ACT) and Pi0.5, and reveal limitations in both base performance and generalization. We demonstrate strong correlations between simulation and real-world metrics that support the ecological validity of the benchmark. By standardizing tasks, metrics, and evaluation protocols within a unified benchmark, Colosseum V2 enables reproducible and fair comparisons, reduced evaluation overhead, and accelerated progress toward general-purpose robot policies.
### Title:
          Auditable Decision Models with Learned Abstention and Real-Time Steering
 - **Authors:** Sankaranarayanan Palamadai Chandrasekaran
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Production AI systems often operate with incomplete, conflicting, or insufficient evidence. Forced classifiers collapse such cases into action labels, while generative systems can produce outputs that are difficult to interpret as auditable execution decisions. We study operational decision control for AI systems, where uncertainty must be explicitly routable, policy-governed, and auditable rather than hidden inside forced predictions or free-form generation. We present EvaluatorDPT, a bounded decision-control model that predicts YES, NO, or TBD, where TBD is learned as a deferral outcome rather than added only as a post-hoc confidence rule. The model uses a transformer encoder with a primary bounded-decision head and structured auxiliary channels for values and emotions/sentiments. The interface is domain-agnostic in form: a deployment domain supplies evidence and policy thresholds, while the model emits a bounded distribution that can be controlled at inference time through recorded operating thresholds and, when validated, auxiliary semantic signals. For the evaluated model version, we report decision performance on held-out validation and test splits; auxiliary emotion metrics are omitted because the emotion head is disabled for this evaluation. On the held-out test split (n=44,597), the model achieves Accuracy = 0.8260 and Macro F1 = 0.8252, with per-class F1 of 0.8314 (YES), 0.8486 (NO), and 0.7956 (TBD). The evaluation record also includes calibration evidence (ECE = 0.0338 on validation), threshold-sweep outputs, multi-seed stability checks, confusion matrices, and reproducibility commands. Our main contribution is a bounded execution interface in which deferral is learned, inference-time routing remains inspectable, auxiliary signals provide a path to auditable behavior control, and evaluation evidence supports external review.
### Title:
          Fine-Tuning Dynamics of In-Context Factual Recall in Transformers
 - **Authors:** Ruomin Huang, Eshaan Nichani, Jason D. Lee, Rong Ge
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In-context learning \ -- performing tasks based on examples given in the prompt \ -- is an important capability that has emerged in large language models and has received significant attention in both theory and practice. Existing theoretical work often focuses on settings where the learning uses information purely from the prompt. However, many practical instances of in-context learning require the model to retrieve factual knowledge stored in the model's parameters, with the context serving to identify which knowledge is relevant. In this work, we study how in-context learning leverages factual knowledge recall. We formalize this behavior by introducing the \emph{in-context factual recall (IC-recall)} task, where a transformer is provided a context of (subject, answer) pairs generated from a hidden relation, along with a query subject, and must both infer this hidden relation and retrieve the corresponding answer. Factual knowledge is modeled by the transformer having access to a simple pre-constructed MLP associative memory storing (subject, relation, answer) triplets. We analyze the supervised fine-tuning dynamics of a one-layer transformer on IC-recall data and prove that the model successfully performs IC-recall by converging to a particular pairwise attention pattern. This fine-tuning stage requires a very small number of samples \ -- only polylogarithmic in the number of stored knowledge triplets. Experiments verify our theoretical predictions and show that the pairwise attention pattern emerges even when the MLP layer is pretrained instead of constructed.
### Title:
          ReSAE: Residualized Sparse Autoencoders for Multi-Layer Transformer Interventions
 - **Authors:** Prathyush Poduval, Calvin Yeung, Neel Desai, Mohsen Imani
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sparse autoencoders are usually trained one layer at a time, even though transformer residual stream activations are strongly coupled across depth. This creates a practical problem for multi-layer interventions: different layerwise dictionaries can spend capacity representing the same carried-forward information, and replacing several layers at once can produce interactions that are not predicted by single-layer behavior. We introduce Residualized Sparse Autoencoders (ReSAEs), which fit an affine map between selected layers and train each later-layer SAE on the unexplained residual rather than on the full activation. Reconstructions are mapped back into the original activation space through the fitted affine chain, so ReSAEs can be evaluated with the same intervention protocols as ordinary SAEs. On Pythia-1.4B and Gemma-2-9B, residualization reduces decoder redundancy and improves sparse probing and targeted perturbation in most tested settings. Despite reconstructing less of the raw activation variance, ReSAEs recover more transformer cross entropy under multi-layer replacement. This gain is clearest under teacher-forcing and at sufficient sparsity online, indicating that ReSAEs preserve the components of the activation most relevant to the model's downstream computation. These results suggest that removing linearly predictable cross-layer structure is a useful default for multi-layer SAE interventions.
### Title:
          Disentangling Adversarial Prompts: A Semantic-Graph Defense for Robust LLM Security
 - **Authors:** Xiang Fang, Wanlong Fang
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) are increasingly vulnerable to adversarial prompts that exploit semantic ambiguities to bypass safety mechanisms, resulting in harmful or inappropriate outputs. Such attacks, including jailbreaking and prompt injection, pose significant risks to the integrity and availability of LLMs in security-critical applications. This paper proposes the Adversarial Prompt Disentanglement (APD) framework, a novel defense mechanism that proactively identifies and neutralizes malicious components in input prompts before they are processed by the LLM. The APD framework integrates three key innovations: (1) a mutual information-based semantic decomposition method to isolate adversarial and benign prompt components, ensuring statistical independence; (2) a graph-based intent classification approach that leverages spectral analysis to detect malicious patterns in prompt semantics; and (3) a lightweight transformer-based classifier trained on real-world datasets of toxic and jailbreaking prompts, enabling efficient and accurate adversarial intent detection. Evaluated on diverse datasets containing adversarial prompts, APD demonstrates superior robustness, reducing harmful output generation by over 85\% while maintaining negligible impact on model performance. The framework's computational efficiency supports real-time deployment, making it a practical solution for securing LLMs. Our work addresses critical challenges in machine learning security on novel attacks and integrity methods for ML systems, and offers a scalable, ethically grounded defense against prompt-based adversarial threats.
### Title:
          A self-supervised learning approach to deep filter banks for texture recognition
 - **Authors:** Joao B. Florindo, Lucas O.Lyra, Antonio E. Fabris
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 An important challenge in texture recognition is the limited amount of data for training frequently found in real-world applications. In computer vision in general, a successful strategy to mitigate this issue is the use of a pretraining stage where the neural network learns to identify relations between parts of the data in a self-supervised manner. A well-established framework in this direction is masked autoencoder. Nevertheless, these models usually rely on computationally intensive architectures, such as vision transformers. In the particular case of texture images, most of the relevant information is compacted within a delimited area around each pixel, which suggests that capturing long-range dependence via the attention mechanism may be unnecessary. Based on that assumption, here we propose a framework where the pretraining model is a convolutional autoencoder. To leverage the rich information conveyed by texture patterns, we employ deep filters coupled with Fisher vector pooling. In this way, we improve the performance of texture recognition without adding significant computational burden. Our approach is compared with several state-of-the-art methods in different texture databases, confirming its potential both in terms of classification accuracy and computational complexity.
### Title:
          ClothTransformer: Unified Latent-Space Transformers for Scalable Cloth Simulation
 - **Authors:** Yu Zhang, Yidi Shao, Wenqi Ouyang, Yushi Lan, Zhexin Liang, Chengrui Wu, Xudong Xu, Xingang Pan
 - **Subjects:** Subjects:
Graphics (cs.GR); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unified and scalable Transformers have recently achieved remarkable success in modeling diverse phenomena traditionally associated with computer graphics, such as 3D visual effects, rendering processes, and motion in videos. In this work, we take a step further by investigating whether modern Transformer techniques can tackle the challenging task of cloth simulation. To this end, we present ClothTransformer, a framework that reformulates cloth simulation as autoregressive sequence modeling in a learned latent space. Existing neural cloth simulators are largely specialized to single scenarios, intrinsically coupled to the mesh discretization, and lack robust collision handling. Our approach addresses these limitations through three contributions: (1) a unified Transformer architecture that handles diverse scenarios -- body-driven garments, robotic manipulation, and free-fall collisions -- under a single model and achieves approximately $4$--$9{\times}$ lower error than prior state-of-the-art methods across all scenarios; (2) a scalable latent-space formulation that compresses arbitrary-resolution meshes into a fixed-size set of latent tokens, making temporal dynamics computation independent of mesh resolution; and (3) a diverse-scenario high-fidelity penetration-free dataset of ${\sim}$493.4k frames spanning all three settings, which enables a differentiable Continuous Collision Detection (CCD) module to suppress penetration artifacts.
### Title:
          Evaluating the Feasibility of Inferring Dietary Behavior Change Receptivity from Egocentric Images of Eating Environment
 - **Authors:** Long Li, Yuning Huang, Heather A. Eicher-Miller, J.Graham Thomas, Fengqing Zhu, Edward Sazonov
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurately assessing dietary behavior change receptivity is essential for designing effective just-in-time adaptive interventions (JITAIs) that promote healthier eating habits. However, self-report-based assessment of behavior change receptivity is sparse and delayed, limiting its practical use in continuous monitoring. To explore whether passive sensing may help address this challenge, this study conducts a pilot investigation of inferring participants' self-reported behavior change receptivity from egocentric eating images collected by a wearable camera. We use pilot data obtained from free-living eating episodes using the Automatic Ingestion Monitor v2 (AIM-2). The data included egocentric image sequences captured during eating and paired with responses to questions assessing specific dimensions of behavior change receptivity (awareness, interaction capability, and motivation). To examine whether visual information contained any relevancy to these responses, we evaluated a transfer-learning-assisted framework that combines a pre-trained Contrastive Language-Image Pre-Training (CLIP) vision encoder with a lightweight transformer classifier. The model processes eating episode image sequences to extract potential semantic and temporal cues related to behavior change receptivity. Preliminary experimental results show promising improvements over simple baseline models for behavior change receptivity indicators. These early findings suggest that egocentric eating episode images may contain cues related to dietary behavior change receptivity, and warrant further investigation with larger and more comprehensive datasets.
### Title:
          Adapting Automotive Aerodynamics Surrogates to New Vehicle Families via Transfer Learning
 - **Authors:** Seunghwan Keum, Alok Warey
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deploying Scientific Machine Learning surrogates in industrial CFD workflows requires adapting pretrained models to new vehicle families without large datasets; yet whether geometric representations learned by a geometry encoder transfer to topologically distinct shapes remains unvalidated. We address this through leave-one-family-out experiments on a 61.47M-parameter Transformer surrogate (AB-UPT) pretrained on four vehicle families (411 external aerodynamics cases) and adapted to the held-out fifth with only 20 samples. Three strategies are compared: Full Fine-Tuning (FFT), Lightweight Fine-Tuning (LFT), and Low-Rank Adaptation (LoRA). The central finding is that pretrained geometry encoders learn transferable representations, but the adaptation mechanism determines whether they can be exploited. FFT destabilizes as 61.47M unconstrained parameters overfit to 20 samples (R^2=0.40); LFT fails because the frozen encoder cannot represent unseen shapes (R^2<0). LoRA resolves both: rank-constrained adapters injected into all layers regularize the loss landscape while preserving pretrained features, achieving R^2=0.85+/-0.02 across all five families with 50% lower force RMSE than FFT and 28% lower pointwise field errors. LoRA also outperforms from-scratch training using 3x more target-family data, eliminating the need for large per-family datasets. These results recast LoRA from a memory-saving convenience into a convergence enabler for geometry transfer: a shared backbone paired with lightweight per-family adapters trainable in hours from minimal data.
### Title:
          Geometry of Human Perceptual Domains Emerges Transiently in LLM Representations
 - **Authors:** Simardeep Singh, Paras Chopra
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While large language models (LLMs) are trained purely on textual data, prior work has shown that their internal representations can exhibit rich geometric structure in embedding space. Building on this line of work, we investigate whether such structure is similar to human perceptual organisation across different domains (e.g., color, pitch, emotion, and taste). Specifically, we study the layer-wise emergence of intrinsic geometrical structure corresponding to perceptual modalities within the residual streams of multiple open-weight transformer architectures. Our results reveal three key findings. First, we observe the emergence of layer-wise geometric structure across multiple perceptual domains, despite the absence of any direct perceptual supervision during training. Second, these perceptual domains exhibit distinct emergence profiles, with both geometric structure and its alignment with human baselines following domain- and model-specific trajectories across depth. Third, this emergence follows a consistent representational trajectory: geometry is weak or diffuse in early layers, becomes progressively organised in intermediate layers, and is attenuated in later layers, suggesting that perceptual geometry arises transiently as part of the model's internal transformation pipeline. This provides new insight into how and where human-like perceptual geometry arises in LLMs, offering a principled pathway for mechanistic analysis of internal representations.
### Title:
          An Evolutionary Approach for Designing Stable and Highly Expressible Low-Immunogenicity Therapeutic mRNA Sequences
 - **Authors:** Dhawa Sang Dong, Mausam Gurung, Suraj Kandel
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Quantitative Methods (q-bio.QM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Messenger RNA (mRNA) sequences as therapeutics require optimized design to ensure efficient translation, structural stability, and minimal immunogenicity. This study presents a two-stage in-silico framework that integrates deep learning and evolutionary computation for rational mRNA optimization instead of existing state-of-the-art models. In the first stage, a pretrained CodonTransformer (BERT-like Large Language Model) generates biologically coherent mRNA sequences encoding the target antigen. In the second stage, a genetic algorithm (GA) evolves these candidate sequences through codon-aware crossover and synonymous mutation guided by human codon usage preferences. Fitness functions for evaluation combined translation-related metrics (CAI, tAI, codon-pair bias), mRNA structural stability (local and global MFE via RNAfold, GC content), and reduced immunogenicity (CpG/UpA motif frequency). Over successive generations (38th, 40th, and 42nd), the GA improved (achieved CAI values of 0.73 to 0.74 and tAI values of 0.63 to 0.64) CAI and tAI by over 6% and codon-pair bias is high and consistent (0.97 ) and improved ribosomal accessibility at the 5' end, with an unpaired_30 fraction reaching 0.87; Global Minimum Free Energy (MFE) converged to a balanced range of -346 to -356 kcal/mol, achieving approximately 84% base-paired structural stability, and reduced immune-stimulatory motifs - lowering the average immune penalty to 27.3 in the final generation. Linear Design produces hyper-stable transcripts (MFE < - 2000 kcal/mol) that risk translation inefficiency due to extreme rigidity, and BiLSTM-CRF focuses solely on high CAI (0.96 to 0.98) without structural constraints, our framework achieves an optimal translation-stability equilibrium, highlighting the proposed BERT-GA framework as an effective, data-driven approach for the design and optimization of in-silico mRNA sequences.
### Title:
          Patched-DeltaNet: Token-Level Event-Driven Memory for Linear-Time Anomaly Detection
 - **Authors:** Tae-Gyun Lee, Junyoung Park, Kyu Won Han
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Time series anomaly detection is critical for maintaining the reliability of mission-critical systems. While Transformer-based models like PatchTST have shown remarkable performance, their $\mathcal{O}(L^2)$ computational complexity severely limits deployment in resource-constrained environments. In this paper, we propose Patched-DeltaNet, a novel architecture combining time-series patching with Gated Delta Networks. By integrating these paradigms, we hypothesize and demonstrate the emergence of token-level event-driven memory, whereby the patching mechanism extracts local semantic chunks, while the error-driven DeltaNet updates its recurrent state exclusively when significant physical changes, defined as deltas, occur. This synergy effectively filters out background noise and captures sudden anomalous drifts. Our rigorous experiments on the Server Machine Dataset (SMD) benchmark demonstrate the structural superiority and sample efficiency of Patched-DeltaNet. By strictly outperforming recent architectures under unified evaluation constraints and identical compute budgets, our model yields an ROC-AUC of 0.957 and PA-F1 of 0.822, while drastically reducing computational complexity to the theoretical minimum of $\mathcal{O}(L/P)$.
### Title:
          Enhancing Ultra-low-field MRI with Segmentation-guided Adversarial Learning
 - **Authors:** James Grover, Andrew Phair, Michael Ferraro, David E.J. Waddington
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Medical Physics (physics.med-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ultra-low-field (ULF) MRI offers portable and low-cost imaging but suffers from poor image quality. To address this, we present our submission to the 2025 ULF Enhancement Challenge (ULF-EnC), where the goal is to synthesise high-field-like MRIs from 64 mT scans. Our pipeline enhances ULF MRI through a combination of anatomical conditioning and model ensembling. We first generate tissue segmentation priors using a Swin UNETR trained solely on challenge-provided data. These priors condition two independent enhancement networks - a CycleGAN and a transformer-based residual enhancement model (T-REX) - each trained to synthesise 3 T-like MRIs. Outputs from both models are combined using a weighted average. Our approach produces enhanced MRIs that were comparable to high-field scans both quantitatively and qualitatively.
### Title:
          Measure-to-measure Regression with Transformers
 - **Authors:** Matthew Vandergrift, Martha White, Yury Polyanskiy, Philippe Rigollet, Lazar Atanackovic
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many learning problems require predicting how populations evolve under an unknown transformation. A natural representation for such populations is a probability measure, with point clouds as a key example. In this work, we study the measure-to-measure (M2M) regression problem, in which one seeks to learn a map between probability measures from a finite collection of observed input-output pairs. In contrast to classical regression, where individual samples are transformed independently, M2M regression treats entire distributions as the data points. This perspective is vital in certain scientific applications, for example, cellular and molecular biology, where cells are known to evolve not as independent data points but as a collection. However, few existing approaches address the problem of M2M regression with sufficient expressivity and scalability. We present a formalization of nonlinear M2M regression and introduce two easy-to-use, expressive, and scalable approaches to learn such operators: transformers as static M2M maps and transformers as dynamic M2M velocity fields. Our approach leverages the natural measure-dependent and mean-field structure of transformers to learn nonlinear M2M maps on the space of probability distributions. We illustrate the effectiveness of our proposed method to generalize to unseen measures on synthetic experiments, interacting particle systems, and a large-scale patient-derived organoid dataset for predicting treatment response in colorectal cancer.
### Title:
          EigeNet: Geometry-Informed Multi-Modal Learning for Few-shot Novel View RIR Prediction
 - **Authors:** Chong Jing, Zitong Lan, Junan Zhang, Zhizheng Wu
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Predicting spatially varying Room Impulse Response (RIR) from sparse observations is a critical but highly challenging inverse problem for immersive spatial audio rendering. In this work, we present EIGENET, a geometry-informed multi-modal framework for few-shot novel view RIR prediction. At its core is a Cross-view Alternate-attention Transformer that iteratively refines local intra-view acoustic structures and global cross-view spatial relationships. We empirically demonstrate that this architecture is capable of making full use of the multi-view multi-modal context while performing spatial-temporal reasoning for RIR prediction. Inspired by acoustic ray tracing, we design a geometry-informed modulation block to formulate the connection between geometric features and RIR power spectrum. In the mean time, an auxiliary loss is introduced to transform the single-target waveform prediction into a multi-task learning framework. Through ablation studies, we demonstrate that this design yields consistent performance gains regardless of the underlying backbone, thereby confirming its foundational utility and architecture-agnostic generalizability for RIR prediction task. Evaluated on both simulated and real-world benchmarks, EIGENET achieves both state-of-the-art performance in few-shot novel view RIR prediction and sim-to-real generalization. Codes and checkpoints are available on this https URL.
### Title:
          Benchmarking Inductive Biases for Multivariate Time-Series Anomaly Detection with a Robust Multi-View Channel-Graph Detector
 - **Authors:** Junhao Wei, Yanxiao Li, Bidong Chen, Yifu Zhao, Haochen Li, Dexing Yao, Baili Lu, Xudong Ye, Jietian Feng, Sio-Kei Im, Yapeng Wang, Xu Yang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Science and Game Theory (cs.GT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a unified experiment, analysis, and benchmark study of multivariate time-series (MTS) anomaly detection. Ten family-representative detectors -- spanning statistical, reconstruction, association, frequency, and generic-transformer families -- are evaluated on five datasets (SMD, MSL, SMAP, PSM, and MSDS) under effectiveness, efficiency, robustness, and cross-dataset generalisation. All methods share the same windowing, scoring, hardware, and metric protocols. Effectiveness, ablation, and robustness use three random seeds; cross-dataset transfer uses seed~0 because each extra seed requires $250$ source-target evaluations. The benchmark yields three method-independent findings: no single-bias baseline dominates; absolute perturbation VUS-ROC is more informative than retention ratios; and MSDS behaves as an event-dense deployment workload rather than a sparse point-anomaly benchmark. Under this protocol we also introduce \ours{}, an adaptive detector family combining a NOTEARS-constrained directed channel-graph view with optional patch-attention and temporal-association views. \ours{} achieves the best macro-average VUS-ROC ($0.675$, $+5.1$~pt over the second-best LSTM-AE), ranks first overall, and reaches the top-3 on all five datasets. Its wins on MSL and MSDS are narrow, while its average and robustness gains are larger: under the same three-seed robustness protocol for every method, it obtains the strongest absolute VUS-ROC across noise, channel dropout, and time-shift perturbations. We release the MSDS preprocessing protocol, configurations, scripts, and seed-level metric dumps.
### Title:
          SAM-Enhanced Segmentation on Road Datasets: Balancing Critical Classes in Autonomous Driving
 - **Authors:** Toomas Tahves, Mauro Bellone, Junyi Gu, Raivo Sell
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dense semantic segmentation is essential for autonomous driving, yet many multi-modal datasets lack pixel-level annotations. The Zenseact Open Dataset (ZOD) provides rich multi-sensor data but only bounding-box labels, limiting its use for segmentation research. Our primary contribution is a Segment Anything Model (SAM)-based annotation pipeline that produces dense, pixel-level annotations for ZOD by converting bounding boxes into semantic masks. In this pilot study, we process over 100,000 frames and manually curate a 2,300-frame subset (36% acceptance rate) to establish a reliable baseline. Using these annotations, we evaluate transformer-based CLFT and CNN-based DeepLabV3+ architectures across diverse weather conditions, achieving up to 48.1% mIoU with CLFT-Hybrid. To address extreme class imbalance, where pedestrians, cyclists, and signs constitute less than 1% of pixels, we explore specialized models targeting rare classes. We further validate the pipeline on the Iseauto autonomous-vehicle platform, achieving 77.5% mIoU, and show that SAM-derived representations transfer effectively across sensor configurations via bidirectional transfer learning. All code and annotations are released to support reproducible research.
### Title:
          Nonvolatile Charge-Domain Attention with HZO Ferroelectric Capacitors: A Simulation-Based Device-to-System Evaluation
 - **Authors:** Faris Abouagour
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer decoding is constrained by both attention compute and KV-cache movement. This paper presents the Ferroelectric Charge-Domain Compute Cell (FCDC), a hafnium-zirconium-oxide (HZO) memcapacitor with an access device that stores analog state nonvolatilely and performs charge-domain VMM for attention. Two deployment modes are evaluated throughout: a full-substrate mode that runs q, k, v, o projections and both attention matmuls on FCDC, and a KV-coprocessor mode that only stores KV and executes the two attention matmuls; the projection-noise budget upper-bounds the coprocessor mode. The device-to-system model is cross-checked across ngspice, CrossSim, FiPy, and NeuroSim and anchored in recent wafer-scale 10 nm HZO measurements. Across 12 pretrained LLMs (1.1-32 B dense, plus a partial-layer Mixtral-8x22B 141 B-MoE stress test at k=75% and a 128 k-context dense-Mistral replication), all-layer noise substitution adds only +2.62% WikiText-2 perplexity on Qwen3-32B and +2.90% +/- 0.33% on Mistral-7B-v0.3 (five-seed mean). End-to-end analog attention adds at most +1.68 pp on TinyLlama-1.1B and shrinks below +/-1 pp on every >=7 B model. Downstream accuracy on HellaSwag, ARC, LAMBADA, and GSM8K stays within 5% of the digital baseline for Mistral-7B (MMLU -1.6 pp). The headline energy win is nonvolatility, no refresh, and KV-cache residency. A workload-level simulator anchored on measured INT4 decode energy delivers 18-35x lower per-served-token energy on RAG and agent loops against a single-user INT4 GPU baseline; against optimized GPU serving (batched vLLM, CPU+NVMe park, power-gate) the robust advantage shrinks to 1.36-4.69x and remains >=41x on parked sessions with multi-hour residency.
### Title:
          Accelerating Robot Path Planning via Connectivity-Preserving Region Proposal Network
 - **Authors:** Zhanzheng Ma, Cancan Zhao, Shuai Zhang, Bo Ouyang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mobile robot path planning methods are often constrained by vast search spaces, resulting in latency in samplingbased algorithms. Learning-based approaches frequently suffer from local region fragmentation and global topological inconsistency. To tackle the problem, we present the Connectivity- Preserving Region Proposal Network (CP-RPN), a segmentationguided model designed to predict compact and topologically connected candidate regions, significantly compressing the search space. Specifically, we design a segmentation model that leverages a Deformable Attention Transformer (DAT) to capture long-range dependencies for global connectivity, with a Deconvolutional decoder to preserve fine-grained spatial details. To guarantee the connectivity of the predicted mask, we design a composite loss function that combines Cross-Entropy loss for pixelwise supervision, a Connectivity-Aware loss to enhance local coherence, and a Topological Continuity loss based on persistent homology to enforce global connectivity. Building on these highconnectivity corridor-like regions, the Voronoi diagram is used to plan the path, backed by a local A* fallback mechanism to ensure robustness. Experimental results demonstrate that CPRPN reduces the candidate region size by over 60.13% compared to the MPT baseline and achieves deterministic low-latency planning (avg. 0.11s) with a 99.60% success rate, outperforming traditional sampling-based algorithms in stability.
### Title:
          Meta-Attention: Bayesian Per-Token Routing for Efficient Transformer Inference
 - **Authors:** Alan Ferrari
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Standard transformer architectures apply a single attention mechanism uniformly across all tokens and sequence positions, irrespective of local context or computational budget. We propose Meta-Attention, a framework that dynamically routes each token to the most appropriate attention strategy -- full softmax attention, linear (kernel) attention, or sliding-window local attention -- via a Bayesian Meta-Controller. Unlike prior routing approaches that use deterministic or prior-free learned routing, the Meta-Controller treats per-token mechanism selection as posterior inference under a compute-aware Dirichlet prior: routing weights are the output of an amortised variational posterior q(alpha | x_t; phi) trained with an Evidence Lower Bound (ELBO) objective that jointly encodes task performance and attention-mechanism cost. This design produces principled routing uncertainty estimates that govern the soft-to-hard routing transition, mitigates routing collapse without ad hoc load-balancing losses, and yields better compute-performance trade-offs than deterministic or prior-free learned routing at negligible overhead. Phase 1 empirical results on a Tiny LM benchmark confirm core predictions: the Bayesian controller's learned routing distribution implies a projected normalised FLOP cost of 25.1% under hard routing, vs. 59.3% for the prior-free baseline (-34.2 pp), and reduces routing entropy from 55.8% to 43.3% (-12.5 pp), demonstrating that the Dirichlet prior prevents routing collapse while the non-Bayesian model defaults to full attention. We present the Bayesian architecture, ELBO training objective, and a Phase 1 PyTorch prototype validating forward-pass correctness, posterior diversity, and a controlled ablation against a prior-free baseline. Code available at: this https URL
### Title:
          Adaptive Temporal Gating of Longitudinal Magnetic Resonance Imaging for Alzheimer's Prediction
 - **Authors:** Alireza Moayedikia, Sara Fin, Alicia Troncoso Lora, Uffe Kock Wiil
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Predicting conversion from Mild Cognitive Impairment (MCI) to Alzheimer's Disease (AD) is critical for early intervention. Current deep learning paradigms predominantly rely on cross-sectional structural MRI, neglecting prognostic value in patient-specific anatomical trajectories. We introduce the Temporal Adaptive Fusion Network (TAF-Net), a hybrid CNN-Transformer architecture that models paired longitudinal 3D MRI scans. Central to TAF-Net is a Temporal Fusion Module governed by an Adaptive Temporal Gate, which learns patient-specific weightings to synthesize three spatiotemporal representations: explicit structural change, region-to-region temporal cross-attention, and bilateral feature concatenation. Evaluated on the Alzheimer's Disease Neuroimaging Initiative cohort for three-year MCI-to-AD conversion prediction, TAF-Net achieved the highest discriminative performance among all evaluated methods using only structural MRI, significantly outperforming the strongest baseline and approaching multimodal methods requiring PET, CSF, or genetic data. The architecture exhibited exceptional data efficiency, matching baseline performance with a fraction of training data. Ablation studies demonstrate that longitudinal fusion improves discrimination while reducing predictive variance by 48% compared to single-timepoint evaluation. Interpretability analyses reveal spatial attention aligned with established AD pathology in the medial temporal lobe and ventricles, while the gating mechanism prioritizes explicit volumetric change with strong positive correlation to conversion risk.
### Title:
          Mag-VLA: Vision-Language-Action Model for Bimanual Magnetically Actuated Microrobot Manipulation
 - **Authors:** Yongchen Wang, Kangyi Lu, Lan Wei, Dandan Zhang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Magnetically actuated microrobots have been used as wireless, non-contact manipulation tools at microscales, making them promising for minimally invasive applications. However, their control remains challenging due to indirect actuation, limited sensing, and nonlinear magnetic interactions. In this work, we propose Mag-VLA, a vision-language-action (VLA) model for dexterous magnetic microrobot manipulation using two robotic arms with mounted magnets for dynamic magnetic-field construction. Bimanual coordination enables capabilities such as microrobot reorientation that are difficult or infeasible with a single arm, but it also introduces coupled control challenges, as the policy must generate coordinated trajectories for both actuators within a shared workspace. Our framework adapts a Qwen2.5-VL-7B backbone using Low-Rank Adaptation (LoRA) to process visual observations and language instructions for action prediction. To capture task progression, we introduce a motion-aware phase classifier and a phase-conditioned Action Chunking Transformer (ACT) decoder for temporally coherent multi-step control. We further construct a teleoperated magnetic microrobot manipulation dataset covering three task configurations. Ablation studies show that the ACT-based decoder substantially outperforms alternative generative action heads. In real-robot experiments, Mag-VLA achieves a 90% approach success rate across all tasks and transport success rates of 80%, 70%, and 50% as task difficulty increases. These results demonstrate that hierarchical VLA modeling provides a promising framework for magnetic microrobot manipulation.
### Title:
          DriveWAM: Video Generative Priors Enable Scalable World-Action Modeling for Autonomous Driving
 - **Authors:** Chen Shi, Jinrui Xu, Shaoshuai Shi, Kehua Sheng, Bo Zhang, Li Jiang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pretrained foundation models have become an important basis for end-to-end autonomous driving. In contrast to vision-language models pretrained primarily on static image-text pairs, video generative models capture temporal dynamics and motion priors that are naturally suited for driving. We present DriveWAM, a driving world-action model that adapts a pretrained video diffusion transformer into an autoregressive video-action policy. DriveWAM organizes video and action streams into a unified temporal token sequence and trains them under a joint flow-matching objective, preserving the pretrained video-generation architecture while adapting its large-scale video priors to action generation. To incorporate high-level scene understanding, we introduce scene-evolving driving guidance, where a frozen VLM produces chunk-specific semantic intent to guide video-action generation. To keep long-horizon rollout bounded, we further introduce selective KV memory, which maintains bounded modality-aware video and action memory pools through relevance-redundancy cache selection at inference time. Experiments on NAVSIM and the PhysicalAI-Autonomous-Vehicles benchmark show that DriveWAM achieves strong planning performance, and a data-scaling study from 4k to 100k driving clips further confirms the scaling potential of world-action modeling for end-to-end autonomous driving.
### Title:
          Refusal Before Decoding: Detecting and Exploiting Refusal Signals in Intermediate LLM Activations
 - **Authors:** Matteo Gioele Collu, Riccardo Conte, Alberto Giaretta, Denis Kleyko, Mauro Conti, Matteo Zavatteri, Roberto Confalonieri
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we investigate whether refusal behavior can be predicted from LLM intermediate activations before decoding using linear probes trained on residual stream activations at each transformer block. We find that refusal is linearly decodable well before the final layer, indicating that safety-relevant behavior is represented in intermediate activations before output generation. To test whether this signal is actionable, we introduce Mechanistic AutoDAN, a probe-guided variant of AutoDAN that replaces full-model fitness evaluation with partial forward passes and probe-based scoring inside a genetic prompt search loop. Across the evaluated models, our method achieves attack success rates competitive with vanilla AutoDAN while reducing per-iteration search time by up to 72%, and probe-guided prompts match or exceed AutoDAN's cross-model transfer in several configurations. We further find that the usefulness of probe guidance increases with model scale. Our results show that refusal is not only observable at the output level, but is encoded as a structured and actionable signal in intermediate LLM activations.
### Title:
          Transformers Provably Learn to Internalize Chain-of-Thought
 - **Authors:** Yixiao Huang, Hanlin Zhu, Zixuan Wang, Jiantao Jiao, Stuart Russell, Somayeh Sojoudi, Song Mei
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Chain-of-Thought (CoT) prompting substantially improves the sample efficiency of transformers, reducing the complexity of tasks like parity learning from exponential to polynomial in the input length. However, generating explicit reasoning steps at inference is computationally expensive. Implicit Chain-of-Thought (ICoT) has emerged as a promising empirical remedy that trains models to internalize intermediate steps within their hidden states, but its theoretical foundations remain poorly understood. We give the first theoretical analysis of ICoT, proving that an $L$-layer transformer trained under our proposed Log-ICoT curriculum learns $k$-parity with $\mathsf{poly}(n)$ samples and $L = \log_2 k$ training stages. This matches the sample efficiency of explicit CoT while eliminating its inference overhead, and extends prior one-layer parity guarantees to multi-layer architectures. Compared to standard ICoT, which removes thinking tokens one at a time, Log-ICoT removes them in geometric chunks, reducing the number of stages from linear in $k$ to logarithmic. Experiments on multi-layer transformers confirm the theory and visualize how reasoning is progressively absorbed into deeper layers.
### Title:
          The Attentional White Bear Effect in Transformer Language Models
 - **Authors:** Rebecca Ramnauth, Brian Scassellati
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Instruction-based suppression is widely used to prevent language models from generating prohibited content, yet it remains unclear whether suppression reduces internal representation or merely suppresses expression. We investigate this question through representational probing, attention analysis, and behavioral semantic leakage experiments across multiple transformer models. We find that prohibited concepts remain highly recoverable from hidden representations under suppression, continue to influence attention routing, and measurably shape downstream generations despite successful lexical avoidance. These effects persist across pooling strategies, indirect semantic controls, and multiple model families. Our results expose a fundamental gap between behavioral and representational alignment.
### Title:
          Applications of temporal graph learning for predicting the dynamics of biological systems
 - **Authors:** Manuel Dileo, Andrea Sottoriva
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Biological foundation models have shown strong performance in single-cell representation learning by applying transformer architectures directly to gene-expression matrices. However, these approaches predominantly operate in static settings and do not explicitly model the temporal evolution of developmental programs in the cell. Modeling such dynamics is important for understanding how cellular states progressively emerge, differentiate, and reorganize during development or disease progression. In this work-in-progress paper, we investigate an alternative temporal graph-based perspective in which cellular states are represented through pseudotime-resolved gene regulatory networks and modeled as evolving graph structures over persistent gene identities. Starting from single-cell transcriptomic data, we infer pseudotime trajectories, discretize cells into developmental snapshots, reconstruct one gene regulatory network per snapshot, and apply temporal graph neural networks to forecast biological states. We evaluate this framework on two publicly available mouse developmental datasets, erythroid gastrulation and pancreatic endocrinogenesis, considering three complementary tasks: gene-expression forecasting, link prediction, and out-degree centrality prediction. Our results show that graph-based models outperform well-known foundation-model such as scGPT and scFoundation, suggesting that explicitly modeling evolving regulatory structure provides useful information beyond static pretrained representations. For link prediction and centrality forecasting, temporal graph learning captures non-trivial regulatory dynamics and enables the identification of temporally important gene hubs. Overall, our findings support temporal graph learning as a promising direction for modeling dynamic biological systems and as a complementary paradigm to current foundation model approaches in single-cell biology.
### Title:
          OSP-Next: Efficient High-Quality Video Generation with Sparse Sequence Parallelism, HiF8 Quantization, and Reinforcement Learning
 - **Authors:** Yunyang Ge, Xianyi He, Zezhong Zhang, Bin Lin, Bin Zhu, Xinhua Cheng, Li Yuan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformers achieve strong video generation quality, but the quadratic cost of full attention limits efficiency. We introduce OSP-Next, an efficient text-to-video generation model that integrates sparse attention, parallelism, quantization, and reinforcement learning. OSP-Next uses a hybrid full-sparse attention architecture, where the sparse component is implemented with Skiparse-2D Attention. This fixed-pattern mechanism applies token-wise and group-wise sparse attention along spatial dimensions, leveraging locality while maintaining native compatibility with FlashAttention kernels. Based on the local equivalence of rearrangement in Skiparse-2D Attention, we further propose Sparse Sequence Parallelism (SSP), which partitions subsequences across ranks and switches sparse patterns through a single All-to-All communication. Compared with Ulysses Sequence Parallelism (SP), SSP provides a native parallel strategy for sparse attention and reduces communication volume by 75%. OSP-Next also incorporates HiF8 quantization to enable stable joint training with 8-bit quantization and sparse fine-tuning, and applies Mix-GRPO post-training to improve the performance of the sparse model. Experiments show that OSP-Next achieves a VBench total score of 83.73%, surpassing the Wan2.1 baseline. Under the 5-second 720P and 5-second 768P settings, OSP-Next achieves up to 1.64$\times$ single-GPU speedup and over 1.52$\times$ eight-GPU speedup on NVIDIA H200 GPUs. In addition, with only a 0.4% drop in VBench total score, OSP-Next-HiF8 achieves 1.69$\times$ and 2.27$\times$ speedups under the two settings on a single Ascend 950PR, demonstrating the efficiency and performance of OSP-Next across hardware platforms.
### Title:
          Understanding Generalization and Forgetting in In-Context Continual Learning
 - **Authors:** Guangyu Li, Meng Ding, Lijie Hu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In-context learning (ICL) derives its power from enabling Large Language Models to adapt to new tasks via prompt-based reasoning alone, entirely bypassing the need for parameter updates. Existing theories primarily study ICL in single-task settings, while real-world prompts often contain sequences of heterogeneous tasks, leaving a gap in understanding whether Large Language Models implicitly perform continual learning during inference. To bridge this gap, we propose the first theoretical framework for in-context continual learning, modeling how a pretrained Transformer processes multiple sequential tasks within a single prompt through shared attention mechanisms. Focusing on linear and masked linear self-attention, we derive error expressions for model predictions under sequential task prompts and analyze their generalization and forgetting behavior. Our results reveal that standard attention mechanisms inevitably induce intertask interference by uniformly or causally aggregating historical contexts, leading to systematic bias. We further provide a bias-variance-interference decomposition of prediction error, characterizing when historical in-context information yields positive transfer or provable negative transfer. This analysis exposes fundamental limits of attention-based continual inference and offers theoretical explanations for order sensitivity and performance degradation in long prompts.
### Title:
          Multi-Mixer Models: Flexible Sequence Modeling with Shared Representations
 - **Authors:** Kevin Y. Li, Asher Trockman, Ananda Theertha Suresh, Ziteng Sun
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Softmax attention is the cornerstone of modern large language models, but its memory scales linearly and compute quadratically with sequence length. Linear recurrent models, such as linear attention and state space models, have become widely studied as alternatives to attention due to their linear compute and constant memory. While these sub-quadratic token mixing methods, or mixers, achieve promising efficiency gains and competitive results on a wide range of benchmarks, current linear recurrent models still lag behind on tasks that require long-context retrieval or in-context learning. A growing body of work studies hybrid architectures that attempt to mitigate these trade-offs by statically interleaving or merging attention and recurrent blocks. In this work, we explore a new axis of developing hybrid models: across the token sequence. We propose Oryx, a hybrid model that can, throughout a sequence, flexibly switch between different mixers, for example quadratic attention for rich context utilization and linear recurrences for efficient generation. Oryx ties at least 90% of its parameters across mixers, enabling attention and recurrent modes to operate over shared internal representations. We validate our design with Mamba-2 and Gated DeltaNet variants, up to 1.4B models. Under fixed token budgets and a mixed-training strategy, Oryx achieves comparable or better performance than its single-mixer baselines. At the 1.4B scale, all instances of Oryx outperform their respective baselines by at least 0.7 percentage points on averaged language modeling tasks. On retrieval tasks, Oryx achieves performance comparable to the Transformer baseline even when processing only a tiny fraction (<10%) of the tokens in attention mode. These results suggest that attention and linear recurrent models can share internal representations, and motivate sequence-axis hybridization as a promising direction.
### Title:
          Affective Music Recommendation: A Rollout-Based World Model for Offline Preference Optimization
 - **Authors:** Audrey Chan, Aaron Labbé, Jacob Lavoie, Jordan Bannister, Arsène Fansi Tchango, Guillaume Lajoie, Laurent Charlin
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Information Retrieval (cs.IR); Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Functional music applications, from consumer focus and sleep aids to clinical interventions, share a distinctive recommendation problem: success is defined by the listener's affective state, but online experimentation on emotion is ethically constrained, particularly for clinical populations who cannot reliably skip a song or report distress. We describe AMRS, the Affective Music Recommendation System deployed on LUCID's health-and-wellness platforms, which serve clinical users (primarily older adults with neurocognitive conditions) and consumer-wellness users across energize, focus, calm, and sleep modes. AMRS is built around a rollout-based world model: a causal transformer trained on logged listening data to jointly predict engagement, binary rating, and self-reported valence and arousal. The world model serves both as an in-silico simulator for offline policy training and as a stress-testing tool before deployment. A recommender policy initialized by behaviour cloning is fine-tuned offline with Direct Preference Optimization (DPO) against a configurable multi-objective utility function. Under a strict cold-start protocol, the world model predicts both behavioural and affective signals with usable fidelity; DPO improves predicted valence and arousal over the cloned baseline while maintaining a similar diversity profile and avoiding the distributional collapse produced by greedy optimization. We position the work as an early deployed validation of a methodology for affective recommendation when online experimentation is ethically untenable.
## Keyword: autonomous driving
### Title:
          SAM-Enhanced Segmentation on Road Datasets: Balancing Critical Classes in Autonomous Driving
 - **Authors:** Toomas Tahves, Mauro Bellone, Junyi Gu, Raivo Sell
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dense semantic segmentation is essential for autonomous driving, yet many multi-modal datasets lack pixel-level annotations. The Zenseact Open Dataset (ZOD) provides rich multi-sensor data but only bounding-box labels, limiting its use for segmentation research. Our primary contribution is a Segment Anything Model (SAM)-based annotation pipeline that produces dense, pixel-level annotations for ZOD by converting bounding boxes into semantic masks. In this pilot study, we process over 100,000 frames and manually curate a 2,300-frame subset (36% acceptance rate) to establish a reliable baseline. Using these annotations, we evaluate transformer-based CLFT and CNN-based DeepLabV3+ architectures across diverse weather conditions, achieving up to 48.1% mIoU with CLFT-Hybrid. To address extreme class imbalance, where pedestrians, cyclists, and signs constitute less than 1% of pixels, we explore specialized models targeting rare classes. We further validate the pipeline on the Iseauto autonomous-vehicle platform, achieving 77.5% mIoU, and show that SAM-derived representations transfer effectively across sensor configurations via bidirectional transfer learning. All code and annotations are released to support reproducible research.
### Title:
          DriveWAM: Video Generative Priors Enable Scalable World-Action Modeling for Autonomous Driving
 - **Authors:** Chen Shi, Jinrui Xu, Shaoshuai Shi, Kehua Sheng, Bo Zhang, Li Jiang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pretrained foundation models have become an important basis for end-to-end autonomous driving. In contrast to vision-language models pretrained primarily on static image-text pairs, video generative models capture temporal dynamics and motion priors that are naturally suited for driving. We present DriveWAM, a driving world-action model that adapts a pretrained video diffusion transformer into an autoregressive video-action policy. DriveWAM organizes video and action streams into a unified temporal token sequence and trains them under a joint flow-matching objective, preserving the pretrained video-generation architecture while adapting its large-scale video priors to action generation. To incorporate high-level scene understanding, we introduce scene-evolving driving guidance, where a frozen VLM produces chunk-specific semantic intent to guide video-action generation. To keep long-horizon rollout bounded, we further introduce selective KV memory, which maintains bounded modality-aware video and action memory pools through relevance-redundancy cache selection at inference time. Experiments on NAVSIM and the PhysicalAI-Autonomous-Vehicles benchmark show that DriveWAM achieves strong planning performance, and a data-scaling study from 4k to 100k driving clips further confirms the scaling potential of world-action modeling for end-to-end autonomous driving.
### Title:
          SARAD: LLM-Based Safety-Aware Hybrid Reinforcement Learning with Collision Prediction for Autonomous Driving
 - **Authors:** Kangyu Wu, Peng Cui, Guoxi Chen, Ya Zhang
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ensuring both safety and efficiency in decision-making for autonomous driving systems remains a fundamental challenge. Traditional Deep Reinforcement Learning (DRL) suffers from unsafe random exploration and slow convergence, while Large Language Models (LLMs) demonstrate inherent latency in real-time inference operations. To address these limitations, this paper proposes SARAD, a novel safety-aware hybrid framework that synergizes LLMs and DRL for autonomous driving. SARAD substitutes the random exploration of DRL with Retrieval-Augmented Generation (RAG)-enhanced, LLM-guided decisions sourced from a dynamic expert knowledge repository. An attention discriminator is proposed to integrate the prior knowledge of LLMs into DRL policy optimization. A collision predictor module, fine-tuned with historical collision data, is further designed to improve vehicle safety. Extensive experiments show that SARAD achieves significant performance improvements in the Highway-Env simulator, validating the effectiveness of the proposed model in autonomous driving.
### Title:
          Deformable Gaussian Occupancy: Decoupling Rigid and Nonrigid Motion with Factorized Distillation
 - **Authors:** Yang Gao, Wuyang Li, Po-Chien Luan, Alexandre Alahi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding dynamic 3D environments is essential for safe autonomous driving, particularly when reasoning about human-centric, nonrigid agents. However, existing weakly supervised occupancy prediction frameworks predominantly assume rigid-body motion and rely on simple frame-to-frame offsets, limiting their ability to capture fine-grained deformations and maintain temporal coherence. To address this issue, we propose DeGO, a deformable Gaussian occupancy framework that unifies decoupled Gaussian deformation with factorized 4D foundation-model distillation. DeGO disentangles rigid and nonrigid motion, enabling each Gaussian primitive to evolve through both deformation and offset-based updates. In parallel, a factorized 4D distillation strategy transfers cross-camera and cross-frame knowledge from the VGGT foundation model, producing foundation-aligned features that enhance temporal consistency. Experiments on the Occ3D-NuScenes benchmark demonstrate that our method achieves state-of-the-art performance under weak supervision, delivering 13.5% gains on human-centric instances and 10.9% overall improvements. These results highlight the effectiveness of deformation-aware and foundation-guided occupancy modeling for dynamic scene understanding. The code is publicly available: this https URL
