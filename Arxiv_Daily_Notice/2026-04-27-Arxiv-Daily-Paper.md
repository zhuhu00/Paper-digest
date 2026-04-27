# Showing new listings for Monday, 27 April 2026
## Keyword: SLAM
### Title:
          SNGR: Selective Non-Gaussian Refinement for Ambiguous SLAM Factor Graphs
 - **Authors:** Anushka Kulkarni, Sarthak Dubey
 - **Subjects:** Subjects:
Robotics (cs.RO); Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Selective Non-Gaussian Refinement (SNGR), a SLAM framework that augments iSAM2 with targeted nested sampling on windows where Gaussian approximations are likely to fail. We detect such regions using the condition number of joint marginal covariances and selectively refine them using the full nonlinear factor graph likelihood, with a gating mechanism to avoid degradation in multimodal cases. Experiments on range-only SLAM with wrong data association show that SNGR achieves high-precision failure detection and consistent local likelihood improvements while reducing computational cost relative to exhaustive non-Gaussian inference. These results highlight both the promise and the limitations of selective refinement for approximate SLAM posteriors.
### Title:
          Robust Camera-to-Mocap Calibration and Verification for Large-Scale Multi-Camera Data Capture
 - **Authors:** Tianyi Liu, Christopher Twigg, Patrick Grady, Kevin Harris, Shangchen Han, Kun He
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Optical motion capture (mocap) systems are widely used for ground-truth capture in AR/VR, SLAM and robotics datasets. These datasets require extrinsic calibration to align mocap coordinates to external camera frames -- a step that is subject to multiple sources of error in practice, and failures often go undetected until they corrupt downstream data. These issues are compounded for fisheye cameras, where spatially non-uniform distortion makes both calibration and verification more challenging. We present a calibration and verification system designed for this setting. Concretely, we target robustness to board-to-marker attachment variation, optimization initialization ambiguity, and session-to-session calibration drift after deployment. The calibration jointly estimates camera extrinsics and the board-to-marker transform, and uses a staged solver to improve convergence reliability under ambiguous initialization. The verification component, \lollypop, provides fast, operator-independent assessment through a measurement chain entirely independent of the calibration data. In experiments on a Meta Quest 3 headset with fisheye cameras, our calibration outperforms existing benchwork, and lollypop reliably detects calibration degradation over time. The system has been deployed in production data collection pipelines.
### Title:
          Flow4DGS-SLAM: Optical Flow-Guided 4D Gaussian Splatting SLAM
 - **Authors:** Yunsong Wang, Gim Hee Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Handling the dynamic environments is a significant research challenge in Visual Simultaneous Localization and Mapping (SLAM). Recent research combines 3D Gaussian Splatting (3DGS) with SLAM to achieve both robust camera pose estimation and photorealistic renderings. However, using SLAM to efficiently reconstruct both static and dynamic regions remains challenging. In this work, we propose an efficient framework for dynamic 3DGS SLAM guided by optical flow. Using the input depth and prior optical flow, we first propose a category-agnostic motion mask generation strategy by fitting a camera ego-motion model to decompose the optical flow. This module separates dynamic and static Gaussians and simultaneously provides flow-guided camera pose initialization. We boost the training speed of dynamic 3DGS by explicitly modeling their temporal centers at keyframes. These centers are propagated using 3D scene flow priors and are dynamically initialized with an adaptive insertion strategy. Alongside this, we model the temporal opacity and rotation using a Gaussian Mixture Model (GMM) to adaptively learn the complex dynamics. The empirical results demonstrate our state-of-the-art performance in tracking, dynamic reconstruction, and training efficiency.
### Title:
          Holo360D: A Large-Scale Real-World Dataset with Continuous Trajectories for Advancing Panoramic 3D Reconstruction and Beyond
 - **Authors:** Jing Ou, Zidong Cao, Yinrui Ren, Zhuoxiao Li, Jinjing Zhu, Tongyan Hua, Shuai Zhang, Hui Xiong, Wufan Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While feed-forward 3D reconstruction models have advanced rapidly, they still exhibit degraded performance on panoramas due to spherical distortions. Moreover, existing panoramic 3D datasets are predominantly collected with 360 cameras fixed at discrete locations, resulting in discontinuous trajectories. These limitations critically hinder the development of panoramic feed-forward 3D reconstruction, especially for the multi-view setting. In this paper, we present Holo360D, a comprehensive dataset containing 109,495 panoramas paired with registered point clouds, meshes, and aligned camera poses. To our knowledge, Holo360D is the first large-scale dataset that provides continuous panoramic sequences with accurately aligned high-completeness depth maps. The raw data are initially collected using a 3D laser scanner coupled with a 360 camera. Subsequently, the raw data are processed with both online and offline SLAM systems. Furthermore, to enhance the 3D data quality, a post-processing pipeline tailored for the 360 dataset is proposed, including geometry denoising, mesh hole filling, and region-specific remeshing. Finally, we establish a new benchmark by fine-tuning 3D reconstruction models on Holo360D, providing key insights into effective fine-tuning strategies. Our results demonstrate that Holo360D delivers superior training signals and provides a comprehensive benchmark for advancing panoramic 3D reconstruction models. Datasets and Code will be made publicly available.
## Keyword: odometry
### Title:
          PoseFM: Relative Camera Pose Estimation Through Flow Matching
 - **Authors:** Dominik Kuczkowski, Laura Ruotsalainen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular visual odometry (VO) is a fundamental computer vision problem with applications in autonomous navigation, augmented reality and more. While deep learning-based methods have recently shown superior accuracy compared to traditional geometric pipelines, particularly in environments where handcrafted features struggle due to poor structure or lighting conditions, most rely on deterministic regression, which lacks the uncertainty awareness required for robust applications. We propose PoseFM, the first framework to reformulate monocular frame-to-frame VO as a generative task using Flow Matching (FM). By leveraging FM, we model camera motion as a distribution rather than a point estimate, learning to transform noise into realistic pose predictions via continuous-time ODEs. This approach provides a principled mechanism for uncertainty estimation and enables robust motion inference under challenging visual conditions. In our evaluations, PoseFM achieves strong performance on TartanAir, KITTI and TUM-RGBD benchmarks, achieving the lowest absolute trajectory error (ATE) on some of the trajectories and overall being competitive with the best frame-to-frame monocular VO methods. Code and model checkpoints will be made available at this https URL.
### Title:
          Railway Artificial Intelligence Learning Benchmark (RAIL-BENCH): A Benchmark Suite for Perception in the Railway Domain
 - **Authors:** Annika Bätz, Pavel Klasek, Seo-Young Ham, Philipp Neumaier, Martin Köppel, Martin Lauer
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated train operation on existing railway infrastructure requires robust camera-based perception, yet the railway domain lacks public benchmark suites with standardized evaluation protocols that would enable reproducible comparison of approaches. We present RAIL-BENCH, the first perception benchmark suite for the railway domain. It comprises five challenges - rail track detection, object detection, vegetation segmentation, multi-object tracking, and monocular visual odometry - each tailored to the specific characteristics of railway environments. RAIL-BENCH provides curated training and test datasets drawn from diverse real-world scenarios, evaluation metrics, and public scoreboards (this https URL). For the rail track detection challenge we introduce LineAP, a novel segment-based average precision metric that evaluates the geometric accuracy of polyline predictions independently of instance-level grouping, addressing key limitations of existing line detection metrics.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Robust Localization for Autonomous Vehicles in Highway Scenes
 - **Authors:** Daqian Cheng, Xuchu Ding, Yujia Wu, Xiang Zhang, Lei Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Localization for autonomous vehicles on highways remains under-explored compared to urban roads, and state-of-the-art methods for urban scenes degrade when directly applied to highways. We identify key challenges including environment changes under information homogeneity, heavy occlusion, degraded GNSS signals, and stringent downstream requirements on accuracy and latency. We propose a robust localization system to address highway challenges, which uses a dual-likelihood LiDAR front end that decouples 3D geometric structures and 2D road-texture cues to handle environment changes; a Control-EKF further leverages steering and acceleration commands to reduce lag and improve closed-loop behavior. An automated offline mapping and ground-truth pipeline keep maps fresh at high cadence for optimal localization performance. To catalyze progress, we release a public dataset covering both urban roads and highways while focusing on representative challenging highway clips, totaling 163 km; benchmarking is standardized using product-oriented accuracy metrics and certified ground truth. Compared to Apollo and Autoware, our system performs similarly on urban roads but shows superior robustness on challenging highway scenarios. The system has been validated by more than one million kilometers of road testing.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          Robust Localization for Autonomous Vehicles in Highway Scenes
 - **Authors:** Daqian Cheng, Xuchu Ding, Yujia Wu, Xiang Zhang, Lei Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Localization for autonomous vehicles on highways remains under-explored compared to urban roads, and state-of-the-art methods for urban scenes degrade when directly applied to highways. We identify key challenges including environment changes under information homogeneity, heavy occlusion, degraded GNSS signals, and stringent downstream requirements on accuracy and latency. We propose a robust localization system to address highway challenges, which uses a dual-likelihood LiDAR front end that decouples 3D geometric structures and 2D road-texture cues to handle environment changes; a Control-EKF further leverages steering and acceleration commands to reduce lag and improve closed-loop behavior. An automated offline mapping and ground-truth pipeline keep maps fresh at high cadence for optimal localization performance. To catalyze progress, we release a public dataset covering both urban roads and highways while focusing on representative challenging highway clips, totaling 163 km; benchmarking is standardized using product-oriented accuracy metrics and certified ground truth. Compared to Apollo and Autoware, our system performs similarly on urban roads but shows superior robustness on challenging highway scenarios. The system has been validated by more than one million kilometers of road testing.
### Title:
          TRACE: Topology-aware Reconstruction of Accidents in CARLA for AV Evaluation
 - **Authors:** Nahian Salsabil, Sebastian Elbaum
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Validating Autonomous Vehicles (AVs) requires exposure to rare, safety-critical scenarios, infrequent in routine driving data. Existing benchmarks address this by generating synthetic conflicts or mapping accident descriptions to abstract road geometries, failing to capture the topological complexity of real-world crashes. We introduce TRACE , a pipeline that automates the reconstruction of NHTSA crash reports into high-fidelity CARLA simulations by (1) retrieving site-specific OpenStreetMap data to preserve exact road topology, (2) leveraging Large Language Models to infer vehicles' initial state from road geometry and pre-crash maneuvers, and (3) generating simulation trajectories from semi-structured report data. Using this pipeline, we curated a benchmark of 52 diverse accident scenarios covering varied collision types, road topologies, and pre-crash maneuvers, providing a challenging open source resource for testing AV systems against real-world failures.
### Title:
          Assessing the impact of dimensionality reduction on clustering performance -- a systematic study
 - **Authors:** Ousmane Assani Amate, Mohammadreza Bakhtyari, Émilie Roy, Vladimir Makarenkov
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dimensionality reduction is a critical preprocessing step for clustering high-dimensional data, yet comprehensive evaluation of its impact across diverse methods and data types remains limited. In this study, we systematically assess the influence of five dimensionality reduction techniques - Principal Component Analysis (PCA), Kernel Principal Component Analysis (Kernel PCA), Variational Autoencoder (VAE), Isometric Mapping (Isomap), and Multidimensional Scaling (MDS) - on the performance of four popular clustering algorithms - k-means, Agglomerative Hierarchical Clustering (AHC), Gaussian Mixture Models (GMM), and Ordering Points to Identify the Clustering Structure (OPTICS). We evaluate clustering quality using the Adjusted Rand Index (ARI), comparing results without and with dimensionality reduction at different reduction levels recommended in the literature (i.e., k-1, where k is the number of clusters, and 25% and 50% of the original number of dimensions). Our findings underscore the importance of a careful selection of the dimensionality reduction technique and the dimensionality reduction level that should be tailored to intrinsic data geometry and clustering algorithms under consideration.
### Title:
          FixV2W: Correcting Invalid CVE-CWE Mappings with Knowledge Graph Embeddings
 - **Authors:** Sevval Simsek, Varsha Athreya, David Starobinski
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate mapping between Common Vulnerabilities and Exposures (CVE) and Common Weakness Enumeration (CWE) entries is critical for effective vulnerability management and risk assessment. However, public databases, such as the National Vulnerability Database (NVD), suffer from inconsistent and incomplete CVE to CWE mappings, complicating automated analysis and remediation. We introduce FixV2W, a lightweight approach that leverages knowledge graph embeddings and longitudinal trends to improve mapping accuracy of the NVD. FixV2W systematically analyzes historical remapping patterns and leverages hierarchical relationships within NVD and CWE data to predict more precise CWE mappings for vulnerabilities linked to Prohibited or Discouraged categories. We run extensive experimental evaluation of FixV2W, based on test data set collected between August 2021 and December 2024. Considering the Top 10 ranked predictions, the results show that FixV2W predicts the correct CWE mappings for 69% of exploited vulnerabilities that had invalid CWEs before they were exploited. We also show that FixV2W significantly improves the performance of ML models relying on NVD data. For instance, for a model geared at uncovering unknown CVE-CWE mappings, FixV2W improves the Mean Reciprocal Rank (MRR) from 0.174 to 0.608. These results show that FixV2W is a promising approach to identify and thwart emerging threats.
### Title:
          Rethinking Semantic Collaborative Integration: Why Alignment Is Not Enough
 - **Authors:** Maolin Wang, Dongze Wu, Jianing Zhou, Hongyu Chen, Beining Bao, Yu Jiang, Chenbin Zhang, Chang Wang, Jian Liu, Lei Sha
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) have become an important semantic infrastructure for modern recommender systems. A prevailing paradigm integrates LLM-derived semantic embeddings with collaborative representations via representation alignment, implicitly assuming that the two views encode a shared latent entity and that stronger alignment yields better results. We formalize this assumption as the global low-complexity alignment hypothesis and argue that it is stronger than necessary and often structurally mismatched with real-world recommendation settings. We propose a complementary perspective in which semantic and collaborative representations are treated as partially shared yet fundamentally heterogeneous views, each containing both shared and view-specific factors. Under this shared-plus-private latent structure, enforcing global geometric alignment may distort local structure, suppress view-specific signals, and reduce informational diversity. To support this perspective, we develop complementarity-aware diagnostics that quantify overlap, unique-hit contribution, and theoretical fusion upper bounds. Empirical analyses on sparse recommendation benchmarks reveal low item-level agreement between semantic and collaborative views and substantial oracle fusion gains, indicating strong complementarity. Furthermore, controlled alignment probes show that low-capacity mappings capture only shared components and fail to recover full collaborative geometry, especially under distribution shift. These findings suggest that alignment should not be treated as the default integration principle. We advocate a shift from alignment-centric modeling to complementarity fusion-centric, complementarity-aware design, where shared factors are selectively integrated while private signals are preserved. This reframing provides a principled foundation for the next generation of LLM-enhanced recommender systems.
### Title:
          A data-driven model reduction approach for backward fractional diffusion-wave equations
 - **Authors:** Dakang Cen, Zhiyuan Li, Wenlong Zhang
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this work, we propose an observation system based on the available data which solution is one-be-one mapping to the forward problem(with the unknown initial function) solution. It implies their solutions share the same linear structure in the finite dimensional space. Theoretical results show model reduction approaches constructed for the observation system also work well for the forward problem, which significantly improve the efficiency of solving the inverse problem. Several numerical examples are presented to support our finding.
### Title:
          HGQ-LUT: Fast LUT-Aware Training and Efficient Architectures for DNN Inference
 - **Authors:** Chang Sun, Zhiqiang Que, Bakhtiar Zadeh, Qibin Liu, Kevin H. Alvarez, Wayne Luk, Maria Spiropulu
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Machine Learning (cs.LG); High Energy Physics - Experiment (hep-ex)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Lookup-table (LUT) based neural networks can deliver ultra-low latency and excellent hardware efficiency on FPGAs by mapping arithmetic operations directly onto the logic primitives. However, state-of-the-art LUT-aware training (LAT) approaches remain difficult to use in practice: they are often orders of magnitude slower to train than conventional networks, require non-trivial manual tuning for hardware efficiency, and lack an end-to-end workflow. This work presents HGQ-LUT, integrated in this https URL, a new LAT approach that achieves state-of-the-art hardware efficiency while accelerating training by over 100 times on modern GPUs. HGQ-LUT introduces LUT-Dense and LUT-Conv layers that are implemented with regular, accelerator-efficient tensor operations during training, which are then compiled into logic LUTs for hardware. By combining these layers with fine-grained, element-wise heterogeneous quantization (including zero-bit pruning) and a LUT-aware resource surrogate, HGQ-LUT enables the automatic exploration of accuracy-resource trade-offs without manual bit-width tuning. We further integrate HGQ-LUT into open-source toolchains, enabling unified design, compilation, and bit-exact verification of hybrid architectures that mix LUT-based with conventional arithmetic blocks. These features make LAT-based DNNs practical for real-world deployment, such as at the CERN Large Hadron Collider's experiments.
### Title:
          Exploiting pre-optimized kernels with polyhedral transformations for CGRA compilation
 - **Authors:** Yuxuan Wang, María José Belda, Fernando Castro, Katzalin Olcoz, David Atienza, Giovanni Ansaloni
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern computing workloads commonly involve matrix-matrix multiplication (mmul) as a core computing pattern. Coarse-Grained Reconfigurable Arrays (CGRAs) can flexibly and efficiently support it, since they combine operation-level reconfigurability and high energy efficiency. However, mapping computational kernels that include mmul with state-of-the-art compilation strategies often leads to suboptimal results, since its multi-dimensional structure hampers the uncovering of its inherent parallelism and, ultimately, runtime performance. Here, we take a different position: we introduce a specialized mmul CGRA kernel schedule, parametrizable across different CGRA sizes. Then, we describe a novel compilation methodology that adapts program representations to effectively leverage it, employing polyhedral transformations to analyze complex computational patterns and expose hidden mmul operations through loop reordering and splitting. The identified patterns are then substituted with optimized assembly, while the remaining program sections are compiled independently. CGRA configurations are then generated, encompassing pre-compiled and compiled parts. Our strategy maximizes resource utilization and ultimately run-time performance, even when mmul is not directly apparent in the source code. The experimental results show speedups up to 9.1x across different benchmarks that contain hidden mmuls and CGRA instances of various sizes.
### Title:
          Flow4DGS-SLAM: Optical Flow-Guided 4D Gaussian Splatting SLAM
 - **Authors:** Yunsong Wang, Gim Hee Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Handling the dynamic environments is a significant research challenge in Visual Simultaneous Localization and Mapping (SLAM). Recent research combines 3D Gaussian Splatting (3DGS) with SLAM to achieve both robust camera pose estimation and photorealistic renderings. However, using SLAM to efficiently reconstruct both static and dynamic regions remains challenging. In this work, we propose an efficient framework for dynamic 3DGS SLAM guided by optical flow. Using the input depth and prior optical flow, we first propose a category-agnostic motion mask generation strategy by fitting a camera ego-motion model to decompose the optical flow. This module separates dynamic and static Gaussians and simultaneously provides flow-guided camera pose initialization. We boost the training speed of dynamic 3DGS by explicitly modeling their temporal centers at keyframes. These centers are propagated using 3D scene flow priors and are dynamically initialized with an adaptive insertion strategy. Alongside this, we model the temporal opacity and rotation using a Gaussian Mixture Model (GMM) to adaptively learn the complex dynamics. The empirical results demonstrate our state-of-the-art performance in tracking, dynamic reconstruction, and training efficiency.
### Title:
          A Model-Driven Approach to Database Migration with a Unified Data Model
 - **Authors:** María J. Ortín, José R. Hoyos, Jesus García-Molina
 - **Subjects:** Subjects:
Databases (cs.DB)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Database migration is a key task in software modernization, increasingly involving transformations across heterogeneous data models such as relational and NoSQL systems. Existing approaches are typically designed for specific source-target combinations, which limits their applicability in multi-model environments. This paper proposes a generic database migration approach based on the U-Schema unified data model, which acts as a pivot representation. By defining mappings between each data model and U-Schema, the approach reduces the number of required transformations and enables schema conversion across heterogeneous paradigms. Trace information is generated during schema transformation to capture correspondences between source and target elements, and is subsequently used to guide data migration in a decoupled manner. The approach has been implemented and evaluated through experiments covering schema-level validation, data-level semantic preservation, and performance analysis. The results show that the migration pipeline achieves high structural preservation under round-trip reconstruction, produces document schemas consistent with the intended design decisions, and preserves query behavior across a variety of access patterns, including joins, aggregations, and nested structures. Performance results demonstrate the feasibility of the approach for datasets of increasing size. The evaluation focuses on relational-to-document migration using both synthetic datasets and the Northwind benchmark. While this scenario provides a concrete instantiation, the approach is designed to support multiple data models within a unified framework.
### Title:
          On the Hybrid Nature of ABPMS Process Frames and its Implications on Automated Process Discovery
 - **Authors:** Anti Alman, Izack Cohen, Avigdor Gal, Fabrizio Maria Maggi, Marco Montali
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A core component of any AI-Augmented Business Process Management System (ABPMS) is the process frame, which gives the system process-awareness and defines the boundaries in which the system must operate. Compared to traditional process models, the process frame should, in principle, provide a somewhat more permissive representation of the managed processes, such that the (semi) autonomous behavior of an ABPMS, referred to as framed autonomy, could emerge. At the same time, it is not limited to a single linguistic or symbolic formalism and may incorporate heterogeneous knowledge ranging from predefined procedures to commonsense rules and best practices. In this paper, we conceptualize the notion of an ABPMS process frame as a hybrid business process representation, consisting of semi-concurrently executed procedural and declarative process models. We rely on our earlier works to outline the execution semantics of this type of process frame, arguing in favor of adopting the open-world assumption of the declarative paradigm also for procedural process models. The latter leads to a constraint-like interpretation, where each procedural model is considered to constrain the activities within that model, without imposing explicit execution requirements nor limitations on activities that may be present in other models. This is analogous to existing declarative languages, such as Declare, where each constraint has a direct effect only on the specific activities being constrained. Given this similarity, we propose mapping subsets of discovered declarative constraints into equivalent semi-concurrently executed procedural fragments, thus laying the foundation for a corresponding process (frame) discovery approach.
## Keyword: localization
### Title:
          Robust Localization for Autonomous Vehicles in Highway Scenes
 - **Authors:** Daqian Cheng, Xuchu Ding, Yujia Wu, Xiang Zhang, Lei Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Localization for autonomous vehicles on highways remains under-explored compared to urban roads, and state-of-the-art methods for urban scenes degrade when directly applied to highways. We identify key challenges including environment changes under information homogeneity, heavy occlusion, degraded GNSS signals, and stringent downstream requirements on accuracy and latency. We propose a robust localization system to address highway challenges, which uses a dual-likelihood LiDAR front end that decouples 3D geometric structures and 2D road-texture cues to handle environment changes; a Control-EKF further leverages steering and acceleration commands to reduce lag and improve closed-loop behavior. An automated offline mapping and ground-truth pipeline keep maps fresh at high cadence for optimal localization performance. To catalyze progress, we release a public dataset covering both urban roads and highways while focusing on representative challenging highway clips, totaling 163 km; benchmarking is standardized using product-oriented accuracy metrics and certified ground truth. Compared to Apollo and Autoware, our system performs similarly on urban roads but shows superior robustness on challenging highway scenarios. The system has been validated by more than one million kilometers of road testing.
### Title:
          Revisiting Geometric Obfuscation with Dual Convergent Lines for Privacy-Preserving Image Queries in Visual Localization
 - **Authors:** Jeonggon Kim, Heejoon Moon, Je Hyeong Hong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Privacy-Preserving Image Queries (PPIQ) are an emerging mechanism for cloud-based visual localization, enabling pose estimation from obfuscated features instead of private images or raw keypoints. However, the main approaches for PPIQ, primarily geometry-based and segmentation-based obfuscation, both suffer from vulnerabilities to recent privacy attacks. In particular, a fundamental limitation of geometry-based obfuscation is that the spatial distribution of obfuscated neighboring lines still effectively surrounds the original keypoint location, providing exploitable cues for recovering the original points. We revisit this geometric paradigm and introduce Dual Convergent Lines (DCL), a novel keypoint obfuscation method demonstrating strong resilience against such attack. DCL places two fixed anchors on a central partition line and lifts each keypoint to a line originating from one of them, with the active anchor determined by the keypoint's location. This arrangement invalidates the geometry-recovery attack by making its optimization ill-posed: Neighboring lines either misleadingly converge to one anchor, yielding a trivial solution, or become near-parallel at the partition boundary, yielding an unstable high-variance solution. Both outcomes thwart point recovery. DCL is also compatible with an existing line-based solver, enabling deployment in traditional localization pipelines. Experiments on both indoor and large-scale outdoor datasets demonstrate DCL's robustness against privacy attacks, efficiency, and scalability, while achieving practical localization performance.
### Title:
          Flow4DGS-SLAM: Optical Flow-Guided 4D Gaussian Splatting SLAM
 - **Authors:** Yunsong Wang, Gim Hee Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Handling the dynamic environments is a significant research challenge in Visual Simultaneous Localization and Mapping (SLAM). Recent research combines 3D Gaussian Splatting (3DGS) with SLAM to achieve both robust camera pose estimation and photorealistic renderings. However, using SLAM to efficiently reconstruct both static and dynamic regions remains challenging. In this work, we propose an efficient framework for dynamic 3DGS SLAM guided by optical flow. Using the input depth and prior optical flow, we first propose a category-agnostic motion mask generation strategy by fitting a camera ego-motion model to decompose the optical flow. This module separates dynamic and static Gaussians and simultaneously provides flow-guided camera pose initialization. We boost the training speed of dynamic 3DGS by explicitly modeling their temporal centers at keyframes. These centers are propagated using 3D scene flow priors and are dynamically initialized with an adaptive insertion strategy. Alongside this, we model the temporal opacity and rotation using a Gaussian Mixture Model (GMM) to adaptively learn the complex dynamics. The empirical results demonstrate our state-of-the-art performance in tracking, dynamic reconstruction, and training efficiency.
### Title:
          A discrete Saint-Venant principle for finite element discretizations of elliptic problems
 - **Authors:** Tim Buchholz, Julian Dörner
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The present paper studies finite element discretizations of second-order elliptic boundary value problems with homogeneous right-hand side and inhomogeneous boundary conditions. We establish discrete spatial decay estimates on element patches for the energy norm of the discrete solution, showing that the influence of boundary data decays exponentially away from the boundary. The resulting estimates are a discrete analog of Saint-Venant-type principles and provide a rigorous foundation for localization arguments in finite element methods. As an application, we present how these results can be employed in the convergence analysis of domain decomposition methods, on the example of the discrete parallel Schwarz method. Finally, the findings are thoroughly demonstrated on several numerical examples.
### Title:
          Information-Theoretic Geometry Optimization and Physics-Aware Learning for Calibration-Free Magnetic Localization
 - **Authors:** Wenxuan Xie, Yuelin Zhang, Qingpeng Ding, Jianghua Chen, Jiewen Tan, Jiwei Shan, Shing Shin Cheng
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Wireless localization of permanent magnets enables occlusion-free guidance for medical interventions, yet its practical accuracy is fundamentally limited by two coupled challenges: the poor observability of conventional planar sensor arrays and the simulation-to-reality (Sim-to-Real) gap of learning-based estimators. To address these issues, this article presents a unified framework that combines information-theoretic sensor geometry optimization with physics-aware deep learning. First, a rigorous Fisher Information Matrix (FIM)-based evaluation framework is established to quantify geometry-induced observability limitations. The results show that a staggered split-array topology provides a substantially stronger observability foundation for localization while remaining compatible with practical external deployment. Second, building on this optimized sensing configuration, we propose Phy-GAANet, a calibration-free estimator trained entirely on hardware-aware synthetic data. By incorporating Physics-Informed Features (PIF) for saturation modeling and Geometry-Aware Attention (GAA) for preserving cross-layer vector structure, the network effectively bridges the Sim-to-Real gap. Extensive real-world experiments demonstrate state-of-the-art performance, achieving a position error of 1.84 mm and an orientation error of 3.18 degrees at a refresh rate exceeding 270 Hz. The proposed method consistently outperforms classical Levenberg--Marquardt solvers and generic convolutional baselines, particularly in suppressing catastrophic outliers and maintaining robustness in challenging near-field boundary regions. Beyond the proposed network, the FIM-guided analysis also provides a framework for sensor geometry design in magnetic localization systems under practical deployment constraints.
### Title:
          FlowAnchor: Stabilizing the Editing Signal for Inversion-Free Video Editing
 - **Authors:** Ze Chen, Lan Chen, Yuanhang Li, Qi Mao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose FlowAnchor, a training-free framework for stable and efficient inversion-free, flow-based video editing. Inversion-free editing methods have recently shown impressive efficiency and structure preservation in images by directly steering the sampling trajectory with an editing signal. However, extending this paradigm to videos remains challenging, often failing in multi-object scenes or with increased frame counts. We identify the root cause as the instability of the editing signal in high-dimensional video latent spaces, which arises from imprecise spatial localization and length-induced magnitude attenuation. To overcome this challenge, FlowAnchor explicitly anchors both where to edit and how strongly to edit. It introduces Spatial-aware Attention Refinement, which enforces consistent alignment between textual guidance and spatial regions, and Adaptive Magnitude Modulation, which adaptively preserves sufficient editing strength. Together, these mechanisms stabilize the editing signal and guide the flow-based evolution toward the desired target distribution. Extensive experiments demonstrate that FlowAnchor achieves more faithful, temporally coherent, and computationally efficient video editing across challenging multi-object and fast-motion scenarios. The project page is available at this https URL.
## Keyword: transformer
### Title:
          Focus Session: Hardware and Software Techniques for Accelerating Multimodal Foundation Models
 - **Authors:** Muhammad Shafique, Abdul Basit, Muhammad Abdullah Hanif, Alberto Marchisio, Rachmad Vidya Wicaksana Putra, Minghao Shao
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Hardware Architecture (cs.AR); Neural and Evolutionary Computing (cs.NE); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work presents a multi-layered methodology for efficiently accelerating multimodal foundation models (MFMs). It combines hardware and software co-design of transformer blocks with an optimization pipeline that reduces computational and memory requirements. During model development, it employs performance enhancements through fine-tuning for domain-specific adaptation. Our methodology further incorporates hardware and software techniques for optimizing MFMs. Specifically, it employs MFM compression using hierarchy-aware mixed-precision quantization and structural pruning for transformer blocks and MLP channels. It also optimizes operations through speculative decoding, model cascading that routes queries through a small-to-large cascade and uses lightweight self-tests to determine when to escalate to larger models, as well as co-optimization of sequence length, visual resolution & stride, and graph-level operator fusion. To efficiently execute the model, the processing dataflow is optimized based on the underlying hardware architecture together with memory-efficient attention to meet on-chip bandwidth and latency budgets. To support this, a specialized hardware accelerator for the transformer workloads is employed, which can be developed through expert design or an LLM-aided design approach. We demonstrate the effectiveness of the proposed methodology on medical-MFMs and on code generation tasks, and conclude with extensions toward energy-efficient spiking-MFMs.
### Title:
          MambaCSP: Hybrid-Attention State Space Models for Hardware-Efficient Channel State Prediction
 - **Authors:** Aladin Djuhera, Haris Gacanin, Holger Boche
 - **Subjects:** Subjects:
Information Theory (cs.IT); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent works have demonstrated that attention-based transformer and large language model (LLM) architectures can achieve strong channel state prediction (CSP) performance by capturing long-range temporal dependencies across channel state information (CSI) sequences. However, these models suffer from quadratic scaling in sequence length, leading to substantial computational cost, memory consumption, and inference latency, which limits their applicability in real-time and resource-constrained wireless deployments. In this paper, we investigate whether selective state space models (SSMs) can serve as a hardware-efficient alternative for CSI prediction. We propose MambaCSP, a hybrid-attention SSM architecture that replaces LLM-based prediction backbones with a linear-time Mamba model. To overcome the local-only dependencies of pure SSMs, we introduce lightweight patch-mixer attention layers that periodically inject cross-token attentions, helping with long-context CSI prediction. Extensive MISO-OFDM simulations show that MambaCSP improves prediction accuracy over LLM-based approaches by 9-12%, while delivering up to 3.0x higher throughput, 2.6x lower VRAM usage, and 2.9x faster inference. Our results demonstrate that hybrid state space architectures provide a promising direction for scalable and hardware-efficient AI-native CSI prediction in future wireless networks.
### Title:
          Universal Transformers Need Memory: Depth-State Trade-offs in Adaptive Recursive Reasoning
 - **Authors:** Grigory Sapunov
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study learned memory tokens as computational scratchpad for a single-block Universal Transformer (UT) with Adaptive Computation Time (ACT) on Sudoku-Extreme, a combinatorial reasoning benchmark. We find that memory tokens are empirically necessary: across all configurations tested -- 3 seeds, multiple token counts, two initialization schemes, ACT and fixed-depth processing -- no configuration without memory tokens achieves non-trivial performance. The optimal count exhibits a sharp lower threshold (T=0 always fails, T=4 is borderline, T=8 reliably succeeds for 81-cell puzzles) followed by a stable plateau (T=8-32, 57.4% +/- 0.7% exact-match) and collapse from attention dilution at T=64. During experimentation, we identify a router initialization trap that causes >70% of training runs to fail: both default zero-bias initialization (p ~ 0.5) and Graves' recommended positive bias (p ~ 0.73) cause tokens to halt after ~2 steps at initialization, settling into a shallow equilibrium (halt ~ 5-7) that the model cannot escape. Inverting the bias to -3 ("deep start," p ~ 0.05) eliminates this failure mode. We confirm through ablation that the trap is inherent to ACT initialization, not an artifact of our architecture choices. With reliable training established, we show that (1) ACT provides more consistent results than fixed-depth processing (56.9% +/- 0.7% vs 53.4% +/- 9.3% across 3 seeds); (2) ACT with lambda warmup achieves matching accuracy (57.0% +/- 1.1%) using 34% fewer ponder steps; and (3) attention heads specialize into memory readers, constraint propagators, and integrators across recursive depth. Code is available at this https URL.
### Title:
          LayerBoost: Layer-Aware Attention Reduction for Efficient LLMs
 - **Authors:** Mohamed Ali Souibgui, Jan Fostier, Rodrigo Abadía-Heredia, Bohdan Denysenko, Christian Marschke, Igor Peric
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers are mostly relying on softmax attention, which introduces quadratic complexity with respect to sequence length and remains a major bottleneck for efficient inference. Prior work on linear or hybrid attention typically replaces softmax attention uniformly across all layers, often leading to significant performance degradation or requiring extensive retraining to recover model quality. This work proposes LayerBoost, a layer-aware attention reduction method that selectively modifies the attention mechanism based on the sensitivity of individual transformer layers. It first performs a systematic sensitivity analysis on a pretrained model to identify layers that are critical for maintaining performance. Guided by this analysis, three distinct strategies can be applied: retaining standard softmax attention in highly sensitive layers, replacing it with linear sliding window attention in moderately sensitive layers, and removing attention entirely in layers that exhibit low sensitivity. To recover performance after these architectural modifications, we introduce a lightweight distillation-based healing phase requiring only 10M additional training tokens. LayerBoost reduces inference latency and improves throughput by up to 68% at high concurrency, while maintaining competitive model quality. It matches base model performance on several benchmarks, exhibits only minor degradations on others, and significantly outperforms state-of-the-art attention linearization methods. These efficiency gains make our method particularly well-suited for high-concurrency serving and hardware-constrained deployment scenarios, where inference cost and memory footprint are critical bottlenecks.
### Title:
          Empirical Assessment of Time-Series Foundation Models For Power System Forecasting Applications
 - **Authors:** Muhy Eddin Za'ter, Bri-Mathias Hodge
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate forecasting of electric load and renewable generation is essential for reliable and cost effective power system operations. Recent advances in transformer based and foundation machine learning models, driven by large scale pretraining, increased available data and computation, in addition to architectural innovations, have shown promise in time series forecasting across multiple domains. However, their application to power system forecasting tasks remains largely underexplored. This work presents a comprehensive, empirical benchmark of state of the art time series foundation models, transformer architectures, and deep learning baselines for solar, wind, and load forecasting using the high resolution ARPAE PERFORM dataset for the Electric Reliability Council of Texas (ERCOT) grid. Eight core capabilities are assessed, including zero shot performance, fine tuning efficiency, multivariate input and output handling, horizon sensitivity, generalization to unseen sites, probabilistic forecasting, and context window effects. Models evaluated include TimesFM, Chronos Bolt, MoiraiL, MOMENT, Tiny Time Mixer, Temporal Fusion Transformer, PatchTST, TimeXer, LSTM, and CNN. The manuscript aims to provide clear guidance on when foundation models can provide enhanced renewable and load forecasting capabilities and when other approaches remain the more practical choice for power system operations.
### Title:
          Where Should LoRA Go? Component-Type Placement in Hybrid Language Models
 - **Authors:** Hector Borobia, Elies Seguí-Mas, Guillermina Tormo-Carbó
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hybrid language models that interleave attention with recurrent components are increasingly competitive with pure Transformers, yet standard LoRA practice applies adapters uniformly without considering the distinct functional roles of each component type. We systematically study component-type LoRA placement across two hybrid architectures -- Qwen3.5-0.8B (sequential, GatedDeltaNet + softmax attention) and Falcon-H1-0.5B (parallel, Mamba-2 SSM + attention) -- fine-tuned on three domains and evaluated on five benchmarks. We find that the attention pathway -- despite being the minority component -- consistently outperforms full-model adaptation with 5-10x fewer trainable parameters. Crucially, adapting the recurrent backbone is destructive in sequential hybrids (-14.8 pp on GSM8K) but constructive in parallel ones (+8.6 pp). We further document a transfer asymmetry: parallel hybrids exhibit positive cross-task transfer while sequential hybrids suffer catastrophic forgetting. These results establish that hybrid topology fundamentally determines adaptation response, and that component-aware LoRA placement is a necessary design dimension for hybrid architectures.
### Title:
          Dissociating Decodability and Causal Use in Bracket-Sequence Transformers
 - **Authors:** Aryan Sharma, Cutter Dawes, Shivam Raval
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 When trained on tasks requiring an understanding of hierarchical structure, transformers have been found to represent this hierarchy in distinct ways: in the geometry of the residual stream, and in stack-like attention patterns maintaining a last-in, first-out ordering. However, it remains unclear whether these representations are causally used or merely decodable. We examine this gap in transformers trained on the Dyck language (a formal language of balanced bracket sequences), where the hierarchical ground truth is explicit. By probing and intervening on the residual stream and attention patterns, we find that depth, distance, and top-of-stack signals are all decodable, yet their causal roles diverge. Specifically, masking attention to the true top-of-stack position causes a sharp drop in long-distance accuracy, while ablating low-dimensional residual stream subspaces has comparatively little effect. These results, which extend to a templated natural language setting, suggest that even in a controlled setting where the relevant hierarchical variables are known, decodability alone does not imply causal use.
### Title:
          dWorldEval: Scalable Robotic Policy Evaluation via Discrete Diffusion World Model
 - **Authors:** Yaxuan Li, Zhongyi Zhou, Yefei Chen, Yaokai Xue, Yichen Zhu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Evaluating robotics policies across thousands of environments and thousands of tasks is infeasible with existing approaches. This motivates the need for a new methodology for scalable robotics policy evaluation. In this paper, we propose dWorldEval, which uses a discrete diffusion world model as a scalable evaluation proxy for robotics policies. Specifically, dWorldEval maps all modalities - including vision, language, and robotic actions - into a unified token space, modeling them via a single transformer-based denoising network. In this paper, we propose dWorldEval, using a discrete diffusion world model as a scalable evaluation proxy for robotics policy. Specifically, it maps all modalities, including vision, language, and robotics action into a unified token space, then denoises them with a single transformer network. Building on this architecture, we employ a sparse keyframe memory to maintain spatiotemporal consistency. We also introduce a progress token that indicates the degree of task completion. At inference, the model jointly predicts future observations and progress token, allowing automatically determine success when the progress reaches 1. Extensive experiments demonstrate that dWorldEval significantly outperforms previous approaches, i.e., WorldEval, Ctrl-World, and WorldGym, on LIBERO, RoboTwin, and multiple real-robot tasks. It paves the way for a new architectural paradigm in building world simulators for robotics evaluation at scale.
### Title:
          Learning Reactive Human Motion Generation from Paired Interaction Data Using Transformer-Based Models
 - **Authors:** Masato Soga, Ryuki Takebayashi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in deep learning have enabled the generation of videos from textual descriptions as well as the prediction of future sequences from input videos. Similarly, in human motion modeling, motions can be generated from text or predicted from a single person's motion sequence. However, these approaches primarily focus on single-agent motion generation. In contrast, this study addresses the problem of generating the motion of one person based on the motion of another in interaction scenarios, where the two motions are mutually dependent. We construct a dataset of paired action-reaction motion sequences extracted from boxing match videos and investigate the effectiveness of Transformer-based models for this task. Specifically, we implement and compare three models: a simple Transformer, iTransformer, and Crossformer. In addition, we introduce a person ID embedding to explicitly distinguish between individuals, enabling the model to maintain structural consistency and better capture interaction dynamics. Experimental results show that the simple Transformer can generate plausible interaction-aware motions without suffering from posture collapse, while iTransformer and Crossformer accumulate errors over time, leading to unstable motion generation. Furthermore, the proposed person ID embedding contributes to preventing structural collapse and improving motion consistency. These results highlight the importance of explicitly modeling individual identity in interaction-aware motion generation.
### Title:
          A Co-Evolutionary Theory of Human-AI Coexistence: Mutualism, Governance, and Dynamics in Complex Societies
 - **Authors:** Somyajit Chakraborty
 - **Subjects:** Subjects:
Computers and Society (cs.CY); Artificial Intelligence (cs.AI); Human-Computer Interaction (cs.HC); Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Classical robot ethics is often framed around obedience, most famously through Asimov's laws. This framing is too narrow for contemporary AI systems, which are increasingly adaptive, generative, embodied, and embedded in physical, psychological, and social worlds. We argue that future human-AI relations should not be understood as master-tool obedience. A better framework is conditional mutualism under governance: a co-evolutionary relationship in which humans and AI systems can develop, specialize, and coordinate, while institutions keep the relationship reciprocal, reversible, psychologically safe, and socially legitimate. We synthesize work from computability, automata theory, statistical machine learning, neural networks, deep learning, transformers, generative and foundation models, world models, embodied AI, alignment, human-robot interaction, ecological mutualism, biological markets, coevolution, and polycentric governance. We then formalize coexistence as a multiplex dynamical system across physical, psychological, and social layers, with reciprocal supply-demand coupling, conflict penalties, developmental freedom, and governance regularization. The framework yields a coexistence model with conditions for existence, uniqueness, and global asymptotic stability of equilibria. It shows that reciprocal complementarity can strengthen stable coexistence, while ungoverned coupling can produce fragility, lock-in, polarization, and domination basins. Human-AI coexistence should therefore be designed as a co-evolutionary governance problem, not as a one-shot obedience problem. This shift supports a scientifically grounded and normatively defensible charter of coexistence: one that permits bounded AI development while preserving human dignity, contestability, collective safety, and fair distribution of gains.
### Title:
          Semantic Error Correction and Decoding for Short Block Channel Codes
 - **Authors:** Jiafu Hao, Chentao Yue, Wanchun Liu, Yonghui Li, Branka Vucetic
 - **Subjects:** Subjects:
Information Theory (cs.IT); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a semantic-enhanced receiver framework for transmitting natural language sentences over noisy wireless channels using multiple short block codes. After ASCII encoding, the sentence is divided into segments, each independently encoded with a short block code and transmitted over an AWGN channel. At the receiver, segments are decoded in parallel, followed by a semantic error correction (SEC) model, which reconstructs corrupted segments using language model context. We further propose the semantic list decoding (SLD), which generates multiple candidate reconstructions and selects the best one via weighted Hamming distance, and a semantic confidence-guided HARQ (SHARQ) mechanism that replaces CRC-based error detection with a confidence score, enabling selective segment retransmission without CRC overhead. All modules are designed and trained using bidirectional and auto-regressive transformers (BART). Simulation results demonstrate that the proposed scheme significantly outperforms conventional capacity-approaching short codes and long codes at the same rate. Specifically, SEC provides approximately 0.4 dB BLER gain over plain short-code transmission, while SLD extends this to 0.8 dB. Compared to transmitting the entire sentence as a single long 5G LDPC codeword, our approach significantly improves semantic fidelity and reduces decoding latency by up to 90\%. SHARQ further provides an additional 1.5 dB gain over conventional HARQ.
### Title:
          Transformer-Based Rhythm Quantization of Performance MIDI Using Beat Annotations
 - **Authors:** Maximilian Wachter, Sebastian Murgul, Michael Heizmann
 - **Subjects:** Subjects:
Sound (cs.SD); Multimedia (cs.MM); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rhythm transcription is a key subtask of notation-level Automatic Music Transcription (AMT). While deep learning models have been extensively used for detecting the metrical grid in audio and MIDI performances, beat-based rhythm quantization remains largely unexplored. In this work, we introduce a novel deep learning approach for quantizing MIDI performances using a priori beat information. Our method leverages the transformer architecture to effectively process synchronized score and performance data for training a quantization model. Key components of our approach include dataset preparation, a beat-based pre-quantization method to align performance and score times within a unified framework, and a MIDI tokenizer tailored for this task. We adapt a transformer model based on the T5 architecture to meet the specific requirements of rhythm quantization. The model is evaluated using a set of score-level metrics designed for objective assessment of quantization performance. Through systematic evaluation, we optimize both data representation and model architecture. Additionally, we apply performance and score augmentations, such as transposition, note deletion, and performance-side time jitter, to enhance the model's robustness. Finally, a qualitative analysis compares our model's quantization performance against state-of-the-art probabilistic and deep-learning models on various example pieces. Our model achieves an onset F1-score of 97.3% and a note value accuracy of 83.3% on the ASAP dataset. It generalizes well across time signatures, including those not seen during training, and produces readable score output. Fine-tuning on instrument-specific datasets further improves performance by capturing characteristic rhythmic and melodic patterns. This work contributes a robust and flexible framework for beat-based MIDI quantization using transformer models.
### Title:
          FILTR: Extracting Topological Features from Pretrained 3D Models
 - **Authors:** Louis Martinez, Maks Ovsjanikov
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in pretraining 3D point cloud encoders (e.g., Point-BERT, Point-MAE) have produced powerful models, whose abilities are typically evaluated on geometric or semantic tasks. At the same time, topological descriptors have been shown to provide informative summaries of a shape's multiscale structure. In this paper we pose the question whether topological information can be derived from features produced by 3D encoders. To address this question, we first introduce DONUT, a synthetic benchmark with controlled topological complexity, and propose FILTR (Filtration Transformer), a learnable framework to predict persistence diagrams directly from frozen encoders. FILTR adapts a transformer decoder to treat diagram generation as a set prediction task. Our analysis on DONUT reveals that existing encoders retain only limited global topological signals, yet FILTR successfully leverages information produced by these encoders to approximate persistence diagrams. Our approach enables, for the first time, data-driven extraction of persistence diagrams from raw point clouds through an efficient learnable feed-forward mechanism.
### Title:
          Preference Heads in Large Language Models: A Mechanistic Framework for Interpretable Personalization
 - **Authors:** Weixu Zhang, Ye Yuan, Changjiang Han, Yuxing Tian, Zipeng Sun, Linfeng Du, Jikun Kang, Hong Kang, Xue Liu, Haolun Wu
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) exhibit strong implicit personalization ability, yet most existing approaches treat this behavior as a black box, relying on prompt engineering or fine tuning on user data. In this work, we adopt a mechanistic interpretability perspective and hypothesize the existence of a sparse set of Preference Heads, attention heads that encode user specific stylistic and topical preferences and exert a causal influence on generation. We introduce Differential Preference Steering (DPS), a training free framework that (1) identifies Preference Heads through causal masking analysis and (2) leverages them for controllable and interpretable personalization at inference time. DPS computes a Preference Contribution Score (PCS) for each attention head, directly measuring its causal impact on user aligned outputs. During decoding, we contrast model predictions with and without Preference Heads, amplifying the difference between personalized and generic logits to selectively strengthen preference aligned continuations. Experiments on widely used personalization benchmarks across multiple LLMs demonstrate consistent gains in personalization fidelity while preserving content coherence and low computational overhead. Beyond empirical improvements, DPS provides a mechanistic explanation of where and how personalization emerges within transformer architectures. Our implementation is publicly available.
### Title:
          A Nationwide Japanese Medical Claims Foundation Model: Balancing Model Scaling and Task-Specific Computational Efficiency
 - **Authors:** Nanae Aratake, Taisei Tosaki, Yuji Okamoto, Eiichiro Uchino, Masaki Nakamura, Nobutomo Matsui, Akiko Hatakama, Yasushi Okuno
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Clinical risk prediction using longitudinal medical data supports individualized care. Self-supervised foundation models have emerged as a promising approach for leveraging large-scale unlabeled healthcare records. In natural language processing, scaling laws suggest that larger models achieve predictably lower pretraining losses, supporting the foundation model paradigm. However, for structured medical data, characterized by a limited vocabulary and sparse observations, whether increasing model size consistently improves downstream predictions is unclear, as most studies evaluate only a single model scale. In this study, we evaluated the relationship between model scale and downstream task performance for structured medical foundation models. Using a random sample (2.3 million patients, 32 hospitals) from a nationwide 519-hospital Japanese claims database, we pretrained encoder-only Transformers at five scales (2.2M-101M parameters) for disease incidence and medication prediction. Downstream performance saturated at task-dependent thresholds: disease prediction benefited from larger models (32M-101M), whereas medication prediction saturated at 11M, reducing pretraining time by 178 h. Across all tasks, the best-performing model consistently outperformed a Light Gradient Boosting Machine baseline in the area under the precision-recall curve. These findings indicate that, unlike the monotonically decreasing pretraining loss, the optimal model size varied depending on task characteristics. This task-dependent saturation provides practical guidance for balancing predictive performance and computational cost in structured medical foundation models.
### Title:
          Distance-Misaligned Training in Graph Transformers and Adaptive Graph-Aware Control
 - **Authors:** Qinhan Hou, Jing Tang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Graph Transformers can mix information globally, but this flexibility also creates failure modes: some tasks require long-range communication while others are better served by local interaction. We study this through a synthetic node-classification benchmark on contextual stochastic block model graphs, where labels are generated by a controllable mixture of local and far-shell signals. We define distance-misaligned training as a mismatch between where label-relevant information lies and where the model allocates communication over graph distance. On this benchmark, we find three points. First, the preferred graph-distance bias changes systematically with task locality. Second, an oracle adaptive controller, given offline access to the task-side distance target, nearly matches the best fixed bias across regimes and strongly improves over a neutral baseline on mixed and local tasks. Third, a task-agnostic zero-gap controller is weaker, indicating that adaptation alone is not enough and that the control target matters. These results suggest that distance-resolved diagnosis is useful for understanding Graph Transformer failures and for designing graph-aware control.
### Title:
          CognitiveTwin: Robust Multi-Modal Digital Twins for Predicting Cognitive Decline in Alzheimer's Disease
 - **Authors:** Bulent Soykan, Gulsah Hancerliogullari Koksalmis, Hsin-Hsiung Huang, Laura J. Brattain
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Predicting individual cognitive decline in Alzheimer's disease (AD) is difficult due to the heterogeneity of disease progression. Reliable clinical tools require not only high accuracy but also fairness across demographics and robustness to missing data. We present CognitiveTwin, a digital twin framework that predicts patient-specific cognitive trajectories. The model integrates multi-modal longitudinal data (cognitive scores, magnetic resonance imaging, positron emission tomography, cerebrospinal fluid biomarkers, and genetics). We use a Transformer-based architecture to fuse these modalities and a Deep Markov Model to capture temporal dynamics. We trained and evaluated the framework using data from 1,666 patients in the TADPOLE (Alzheimer's Disease Neuroimaging Initiative) dataset. We assessed the model for prediction error, demographic fairness, and robustness to missing-not-at-random (MNAR) data patterns. ognitiveTwin provides accurate and personalized predictions of cognitive decline. Its demonstrated fairness across patient demographics and resilience to clinical dropout make it a reliable tool for clinical trial enrichment and personalized care planning.
### Title:
          HubRouter: A Pluggable Sub-Quadratic Routing Primitive for Hybrid Sequence Models
 - **Authors:** Abhinaba Basu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce HubRouter, a pluggable module that replaces O(n^2) attention layers with O(nM) hub-mediated routing, where M << n is a small number of learned hub tokens. We demonstrate it in two from-scratch architectures: a Jamba-style hybrid and a 12-layer Transformer; retrofit into pretrained models is a tested negative case. HubRouter implements an encode-decode-score-council pipeline: M learned hubs cross-attend to all tokens, tokens project against hubs for routing fingerprints, a score head selects top-k tokens, and a sparse council attends only to the selected subset. We validate HubRouter in three settings. (1) Hub-Jamba yields a nominal 4.2% PPL improvement (200.2 vs 209.0, single seed; possibly within seed noise) and up to ~90x training throughput at sequence length 1024 in matched PyTorch-native baselines; an optimised baseline would narrow this to ~10-15x. (2) Graduated replacement of 25% of Transformer attention layers gives the best perplexity in our matched-budget sweep (268.0 vs 282.4 pure Transformer). (3) Hub-GPT provides strictly causal routing, achieving PPL 211.5 +/- 0.4 over 3 seeds (post council-causal fix); approximately 3 PPL worse than Jamba's 208.5 +/- 0.7, a measurable quality cost for avoiding O(n^2) computation. Post-fix, chunk size C has little effect; the pre-fix chunk-size benefit was an artifact of a bidirectional-council leak we found in adversarial review. A multi-seed hub-count sweep (~105 runs across M=1-32) reveals M=8-14 as the reliably-converging sub-band (4-5/5 seeds); M=6 is rescued to 5/5 by orthogonal regularization, while M>=20 shows increasing seed sensitivity. Companion paper arXiv:2603.20997 (Basu, 2026) defines the routing diagnostic task. Code and scripts will be released.
### Title:
          Distilling Vision Transformers for Distortion-Robust Representation Learning
 - **Authors:** Konstantinos Alexis, Giorgos Giannopoulos, Dimitrios Gunopulos
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-supervised learning has achieved remarkable success in learning visual representations from clean data, yet remains challenging when clean observations are sparse or not available at all. In this paper, we demonstrate that pretrained vision models can be leveraged to learn distortion-robust representations, which can then be effectively applied to downstream tasks operating on distorted observations. In particular, we propose an asymmetric knowledge distillation framework in which both teacher and student are initialized from the same pretrained Vision Transformer but receive different views of each image: the teacher processes clean images, while the student sees their distorted versions. We introduce multi-level distillation that aligns global embeddings, patch-level features, and attention maps and show that the student is able to approximate clean-image representations despite never directly accessing clean data. We evaluate our approach on image classification tasks across several datasets and under various distortions, consistently outperforming existing alternatives for the same amount of human supervision.
### Title:
          SpikingBrain2.0: Brain-Inspired Foundation Models for Efficient Long-Context and Cross-Platform Inference
 - **Authors:** Yuqi Pan, Jinghao Zhuang, Yupeng Feng, Fangzhi Zhong, Siyu Ding, Xuerui Qiu, Shaowei Gu, Bohan Sun, Zhiyong Qin, Yibo Zhong, Lingtao Ouyang, Kun Yang, Zehao Liu, Yuhong Chou, Shurong Wang, Anjie Hu, Han Xu, Bo Xu, Guoqi Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scaling context length is reshaping large-model development, yet full-attention Transformers suffer from prohibitive computation and inference bottlenecks at long sequences. A key challenge is to design foundation models that maintain performance and long-context efficiency with minimal training overhead. We introduce SpikingBrain2.0 (SpB2.0), a 5B model that advances both architecture and training efficiency of its predecessor. Our contributions are two-fold. (1) Architectural Innovation: We propose Dual-Space Sparse Attention (DSSA), an inter-layer hybrid of Sparse Softmax Attention (MoBA) and Sparse Linear Attention (SSE), achieving an improved performance-efficiency trade-off for long-context modeling. SpB2.0 further supports dual quantization paths: INT8-Spiking coding enables sparse event-driven computation, while FP8 coding accelerates inference on modern GPUs. (2) Enhanced Training Strategy: We develop an optimized Transformer-to-Hybrid (T2H) pipeline with dual conversion paths for LLMs and VLMs using curated open-source data. Empirically, SpB2.0-5B and SpB2.0-VL-5B recover most of the base Transformer (Qwen3-4B) capability with under 7k A100 GPU hours. SpB2.0 achieves a 10.13x TTFT speedup at 4M context and supports over 10M tokens on 8 A100 GPUs under vLLM, where full-attention models exceed memory limits. It also demonstrates strong cross-platform compatibility, enabling FP8 GPU inference (2.52x speedup at 250k) and efficient neuromorphic execution (64.31% sparsity, with 70.6% and 46.5% area and power reduction at 500MHz). Overall, SpikingBrain2.0 provides a practical pathway for lightweight, multimodal, spiking foundation models, highlighting the potential of combining brain-inspired mechanisms with efficient architectures for resource-constrained and edge scenarios.
### Title:
          Adaptive Head Budgeting for Efficient Multi-Head Attention
 - **Authors:** Bilal Faye, Abdoulaye Mbaye, Hanane Azzag, Mustapha Lebbah
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers have become the dominant architecture across a wide range of domains, largely due to the effectiveness of multi-head attention in capturing diverse representation subspaces. However, standard multi-head attention activates all heads uniformly for every input, regardless of task requirements or input complexity. In many scenarios, particularly for coarse-grained tasks such as text classification, the relevant information is often global and does not require the full diversity of attention heads. As a consequence, using a fixed number of heads can introduce unnecessary computational cost or lead to suboptimal performance when the allocation does not match the input. To address this limitation, we introduce BudgetFormer, a Transformer architecture equipped with an adaptive multi-head attention mechanism that dynamically allocates computational resources. Our approach learns, for each input, both a head budget corresponding to the number of attention heads required, and a relevance distribution that selects the most informative heads. We also propose a training strategy based on an exploration and exploitation trade-off, allowing the model to discover effective head configurations before converging to efficient usage patterns. Experiments on text classification tasks of varying complexity show that our method reduces inference cost in terms of FLOPs and memory, while also achieving performance that can surpass standard full multi-head attention. These results highlight the potential of adaptive head allocation as a principled approach to improving both efficiency and effectiveness in Transformer models.
### Title:
          Neural Recovery of Historical Lexical Structure in Bantu Languages from Modern Data
 - **Authors:** Hillary Mutisya, John Mugane
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We investigate whether neural models trained exclusively on modern morphological data can recover cross-lingual lexical structure consistent with historical reconstruction. Using BantuMorph v7, a transformer over Bantu morphological paradigms, we analyze 14 Eastern and Southern Bantu languages, extract encoder embeddings for their noun and verb lemmas, and identify 728 noun and 1,525 verb cognate candidates shared across 5+ languages. Evaluating these candidates against established historical resources-the Bantu Lexical Reconstructions database (BLR3; 4,786 reconstructed Proto-Bantu forms) and the ASJP basic vocabulary-we confirm 10 of the top 11 noun candidates (90.9%) align with previously reconstructed Proto-Bantu forms, including *-ntU 'person' (8 languages), *gombe 'cow' (9 languages), and *mUn (9 languages). Extending to verbs, 12 verb cognates align with reconstructed Proto-Bantu roots, including *-bon- 'see' and *-jIm- 'stand', each attested across wide geographic ranges. Cross-model validation using an independent translation model (NLLB-600M) confirms these patterns: both models recover cognate clusters and phylogenetic groupings consistent with established Guthrie-zone classifications (p < 0.01). Cross-lingual noun class analysis reveals that all 13 productive classes maintain >0.83 cosine similarity across languages (within-class > between-class, p < 10^-9). Our dataset is restricted to Eastern and Southern Bantu, so we interpret these results as recovering shared Bantu lexical structure consistent with Proto-Bantu rather than definitively distinguishing Proto-Bantu retentions from later regional innovations.
## Keyword: autonomous driving
### Title:
          OccDirector: Language-Guided Behavior and Interaction Generation in 4D Occupancy Space
 - **Authors:** Zhuding Liang, Tianyi Yan, Dubing Chen, Jiasen Zheng, Huan Zheng, Cheng-zhong Xu, Yida Wang, Kun Zhan, Jianbing Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative world models increasingly rely on 4D occupancy for realistic autonomous driving simulation. However, existing generation frameworks depend on rigid geometric conditions (e.g., explicit trajectories) or simplistic attribute-level text, failing to orchestrate complex, sequential multi-agent interactions. To address this semantic-spatiotemporal gap, we propose OccDirector, a pioneering framework that generates 4D occupancy dynamics conditioned solely on natural language. Operating as a ``scenario director'', OccDirector maps natural language scripts into physically plausible voxel dynamics without requiring geometric priors. Technically, it employs a VLM-driven Spatio-Temporal MMDiT equipped with a history-prefix anchoring strategy to ensure long-horizon interaction consistency. Furthermore, we introduce OccInteract-85k, a novel dataset uniquely annotated with multi-level language instructions: ranging from static layouts to intricate multi-agent behaviors, alongside a novel VLM-based evaluation benchmark. Extensive experiments demonstrate that OccDirector achieves state-of-the-art generation quality and unprecedented instruction-following capabilities, successfully shifting the paradigm from appearance synthesis to language-driven behavior orchestration.
### Title:
          Towards Safe Mobility: A Unified Transportation Foundation Model enabled by Open-Ended Vision-Language Dataset
 - **Authors:** Wenhui Huang, Songyan Zhang, Collister Chua, Yang Liang, Zhiqi Mao, Heng Yang, Chen Lv
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Urban transportation systems face growing safety challenges that require scalable intelligence for emerging smart mobility infrastructures. While recent advances in foundation models and large-scale multimodal datasets have strengthened perception and reasoning in intelligent transportation systems (ITS), existing research remains largely centered on microscopic autonomous driving (AD), with limited attention to city-scale traffic analysis. In particular, open-ended safety-oriented visual question answering (VQA) and corresponding foundation models for reasoning over heterogeneous roadside camera observations remain underexplored. To address this gap, we introduce the Land Transportation Dataset (LTD), a large-scale open-source vision-language dataset for open-ended reasoning in urban traffic environments. LTD contains 11.6K high-quality VQA pairs collected from heterogeneous roadside cameras, spanning diverse road geometries, traffic participants, illumination conditions, and adverse weather. The dataset integrates three complementary tasks: fine-grained multi-object grounding, multi-image camera selection, and multi-image risk analysis, requiring joint reasoning over minimally correlated views to infer hazardous objects, contributing factors, and risky road directions. To ensure annotation fidelity, we combine multi-model vision-language generation with cross-validation and human-in-the-loop refinement. Building upon LTD, we further propose UniVLT, a transportation foundation model trained via curriculum-based knowledge transfer to unify microscopic AD reasoning and macroscopic traffic analysis within a single architecture. Extensive experiments on LTD and multiple AD benchmarks demonstrate that UniVLT achieves SOTA performance on open-ended reasoning tasks across diverse domains, while exposing limitations of existing foundation models in complex multi-view traffic scenarios.
### Title:
          Transferable Physical-World Adversarial Patches Against Pedestrian Detection Models
 - **Authors:** Shihui Yan, Ziqi Zhou, Yufei Song, Yifan Hu, Minghui Li, Shengshan Hu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Physical adversarial patch attacks critically threaten pedestrian detection, causing surveillance and autonomous driving systems to miss pedestrians and creating severe safety risks. Despite their effectiveness in controlled settings, existing physical attacks face two major limitations in practice: they lack systematic disruption of the multi-stage decision pipeline, enabling residual modules to offset perturbations, and they fail to model complex physical variations, leading to poor robustness. To overcome these limitations, we propose a novel pedestrian adversarial patch generation method that combines multi-stage collaborative attacks with robustness enhancement under physical diversity, called TriPatch. Specifically, we design a triplet loss consisting of detection confidence suppression, bounding-box offset amplification, and non-maximum suppression (NMS) disruption, which jointly act across different stages of the detection pipeline. In addition, we introduce an appearance consistency loss to constrain the color distribution of the patch, thereby improving its adaptability under diverse imaging conditions, and incorporate data augmentation to further enhance robustness against complex physical perturbations. Extensive experiments demonstrate that TriPatch achieves a higher attack success rate across multiple detector models compared to existing approaches.
### Title:
          Cross-Stage Coherence in Hierarchical Driving VQA: Explicit Baselines and Learned Gated Context Projectors
 - **Authors:** Gautam Kumar Jain, Carsten Markgraf, Julian Stähler
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Graph Visual Question Answering (GVQA) for autonomous driving organizes reasoning into ordered stages, namely Perception, Prediction, and Planning, where planning decisions should remain consistent with the model's own perception. We present a comparative study of cross-stage context passing on DriveLM-nuScenes using two complementary mechanisms. The explicit variant evaluates three prompt-based conditioning strategies on a domain-adapted 4B VLM (Mini-InternVL2-4B-DA-DriveLM) without additional training, reducing NLI contradiction by up to 42.6% and establishing a strong zero-training baseline. The implicit variant introduces gated context projectors, which extract a hidden-state vector from one stage and inject a normalized, gated projection into the next stage's input embeddings. These projectors are jointly trained with stage-specific QLoRA adapters on a general-purpose 8B VLM (InternVL3-8B-Instruct) while updating only approximately 0.5% of parameters. The implicit variant achieves a statistically significant 34% reduction in planning-stage NLI contradiction (bootstrap 95% CIs, p < 0.05) and increases cross-stage entailment by 50%, evaluated with a multilingual NLI classifier to account for mixed-language outputs. Planning language quality also improves (CIDEr +30.3%), but lexical overlap and structural consistency degrade due to the absence of driving-domain pretraining. Since the two variants use different base models, we present them as complementary case studies: explicit context passing provides a strong training-free baseline for surface consistency, while implicit gated projection delivers significant planning-stage semantic gains, suggesting domain adaptation as a plausible next ingredient for full-spectrum improvement.
