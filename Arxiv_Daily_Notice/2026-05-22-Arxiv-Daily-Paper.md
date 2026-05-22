# Showing new listings for Friday, 22 May 2026
## Keyword: SLAM
### Title:
          FRED: A Multi-Modal Autonomous Driving Dataset for Flooded Road Environments
 - **Authors:** Connor Malone, Sebastien Demmel, Sebastien Glaser
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Flooded Road Environments Dataset (FRED) is, to our knowledge, the first multi-modal autonomous driving dataset specifically targeting the collection of data from scenarios involving water hazards on the road. The dataset contains images from a 2.3 MP FLIR Blackfly USB3 camera, 64-beam 360$^\circ$ point clouds from an Ouster OS1-64 LiDAR, and data from an iXblue ATLANS-C IMU corrected by a Geoflex RTK GNSS, from five separate locations captured both during and after flooding events. The data has been released in two formats: a KITTI-style format for easy integration with existing data tools, and the RTMaps format for direct replay of the vehicle's data capture. We provide semantic labels to enable the training and evaluation of both single-sensor and sensor-fusion methods for water hazard detection. Position and velocity, as well as data captured under dry conditions, are provided to enable the development of location-based detection methods that may incorporate maps, and to evaluate other tasks such as localisation and SLAM.
## Keyword: odometry
### Title:
          OCELOT: Odometry and Contact Estimation for Legged Robots
 - **Authors:** Emre Girgin, Cagri Kilic
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 One of the significant challenges in legged robotics is achieving accurate odometry using only onboard proprioceptive sensors. In this study, we present a complete leg odometry pipeline based on an Error-State EKF (ESEKF) that relies exclusively on proprioceptive data: a body fixed IMU, joint encoders, and force sensors, where filter's state is corrected by feet determined to be in a stationary stance. The core of our contribution is fused contact detection and an uncertainty quantification module designed to explicitly identify and reject slippage. This module runs two detectors in parallel for each foot, 1) a debounced, force-based Gaussian Mixture Model (GMM) guided Finite State Machine (FSM) to confirm physical contact, and 2) a kinematic-based Generalized Likelihood Ratio Test (GLRT) on the estimated velocity of the foot. The continuous quality scores from both estimators are fused to detect if the foot is both physically loaded and kinematically stationary and served as an uncertainty signal for each contact. To validate our approach, we collected a multi-modal dataset of 29 sequences spanning diverse indoor and outdoor terrains (e.g., concrete, grass, pebble, and rock) total of 2.4 km long. We benchmarked our approach against both proprioceptive and exteroceptive methods. The results demonstrate our method's efficacy in providing accurate odometry estimates, robustly handling slippage-prone environments. We also share our code and real-time ROS2 package as open-source.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Improving 3D Labeling in Self-Driving by Inferring Vehicle Information using Vision Language Models
 - **Authors:** Steven Chen, Shivesh Khaitan, Nemanja Djuric
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present an approach to improve 3D vehicle labeling in self-driving applications through zero-shot inference of vehicle information, leveraging Vehicle Make and Model Recognition (VMMR) methods. The proposed approach utilizes a Vision Language Model (VLM) to both infer a vehicle's make, model, and generation from image crops, and output accurate 3D bounding box dimensions to seed manual labeling. We evaluate the impact of iterative prompt engineering and the choice of different VLMs on both vehicle bounding box inference and make/model/generation recognition. When compared to strong baselines, the proposed approach not only shows high accuracy, but also excels in mitigating specific failure modes where VLMs provide better dimensions than initial lidar-aided human annotated labels (e.g., in cases of significant vehicle occlusion). Experiments on both public and proprietary data strongly suggest that our conclusions are generalizable across different labelers and datasets. The results demonstrate that integrating VLMs into the labeling process can reduce manual labeling time while increasing label quality.
### Title:
          FRED: A Multi-Modal Autonomous Driving Dataset for Flooded Road Environments
 - **Authors:** Connor Malone, Sebastien Demmel, Sebastien Glaser
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Flooded Road Environments Dataset (FRED) is, to our knowledge, the first multi-modal autonomous driving dataset specifically targeting the collection of data from scenarios involving water hazards on the road. The dataset contains images from a 2.3 MP FLIR Blackfly USB3 camera, 64-beam 360$^\circ$ point clouds from an Ouster OS1-64 LiDAR, and data from an iXblue ATLANS-C IMU corrected by a Geoflex RTK GNSS, from five separate locations captured both during and after flooding events. The data has been released in two formats: a KITTI-style format for easy integration with existing data tools, and the RTMaps format for direct replay of the vehicle's data capture. We provide semantic labels to enable the training and evaluation of both single-sensor and sensor-fusion methods for water hazard detection. Position and velocity, as well as data captured under dry conditions, are provided to enable the development of location-based detection methods that may incorporate maps, and to evaluate other tasks such as localisation and SLAM.
### Title:
          3D LULC classification using multispectral LiDAR and deep learning: current and prospective schemes
 - **Authors:** Narges Takhtkeshha, Aldino Rizaldy, Markus Hollaus, Juha Hyyppä, Fabio Remondino, Gottfried Mandlburger
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Land Use Land Cover (LULC) classification is essential for national 3D mapping, geospatial analysis, and sustainable planning. Multispectral (MS) LiDAR provides synchronized spatial-spectral information, and deep learning (DL) enables 3D point cloud semantic segmentation; however, adoption is limited by the lack of publicly available urban and suburban MS LiDAR datasets aligned with National Mapping and Cadastral Agencies (NMCAs) classification schemes. This study addresses these gaps by introducing L1 and L2 NMCA-aligned LULC classification schemes and a new benchmark MS LiDAR dataset. We evaluate seven state-of-the-art DL models and perform spectral ablation studies at both levels of detail. Results show that Point Transformer V3 achieves the best performance, with mIoU of 79.4% (L1, 8 classes) and 58.9% (L2, 20 classes) using a dual-wavelength LiDAR system (532 nm and 1064 nm). Ablation results show that multispectral information improves performance over geometry-only inputs, with gains of 1.1 percentage points at L1 and 7.8 points at L2. These results highlight the value of LiDAR reflectance for fine-grained material discrimination and support the evolution of NMCA LULC schemes toward higher semantic detail. The Loosdorf-MSL dataset contributes a new benchmark for consistent national and international LULC mapping.
### Title:
          Sensor2Sensor: Cross-Embodiment Sensor Conversion for Autonomous Driving
 - **Authors:** Jiahao Wang, Bo Sun, Yijing Bai, Vincent Casser, Songyou Peng, Zehao Zhu, Meng-Li Shih, Xander Masotto, Shih-Yang Su, Kanaad V Parvate, Tiancheng Ge, Linn Bieske, Dragomir Anguelov, Mingxing Tan, Chiyu Max Jiang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust training and validation of Autonomous Driving Systems (ADS) require massive, diverse datasets. Proprietary data collected by Autonomous Vehicle (AV) fleets, while high-fidelity, are limited in scale, diversity of sensor configurations, as well as geographic and long-tail-behavioral coverage. In contrast, in-the-wild data from sources like dashcams offers immense scale and diversity, capturing critical long-tail scenarios and novel environments. However, this unstructured, in-the-wild video data is incompatible with ADS expecting structured, multi-modal sensor inputs for validation and training. To bridge this data gap, we propose Sensor2Sensor, a novel generative modeling paradigm that translates in-the-wild monocular dashcam videos into a high-fidelity, multi-modal sensor suite (AV logs) comprising multi-view camera images and LiDAR point clouds. A core challenge is the lack of paired training data. We address this by converting real AV logs into dashcam-style videos via 4D Gaussian Splatting (4DGS) reconstruction and novel-view rendering. Sensor2Sensor then utilizes a diffusion architecture to perform the generative conversion. We perform comprehensive quantitative evaluations on the fidelity and realism of the generated sensor data. We demonstrate Sensor2Sensor's practical utility by converting challenging in-the-wild internet and dashcam footage into realistic, multi-modal data formats, further unlocking vast external data sources for AV development.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          TWINGS: Thin Plate Splines Warp-aligned Initialization for Sparse-View Gaussian Splatting
 - **Authors:** Hyeseong Kim, Geonhui Son, Deukhee Lee, Dosik Hwang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Novel view synthesis from sparse-view inputs poses a significant challenge in 3D computer vision, particularly for achieving high-quality scene reconstructions with limited viewpoints. We introduce TWINGS, a framework that enhances 3D Gaussian Splatting (3DGS) by directly addressing point sparsity. We employ Thin Plate Splines (TPS), a smooth non-rigid deformation model that minimizes bending energy to estimate a globally coherent warp from control-point correspondences, to align backprojected points from estimated depth with triangulated 3D control points, yielding calibrated backprojected points. By sampling these calibrated points near the control points, TWINGS provides a fast and geometrically accurate initialization for 3DGS, ultimately improving structural detail preservation and color fidelity in reconstructed scenes. Extensive experiments on DTU, LLFF, and Mip-NeRF360 demonstrate that TWINGS consistently outperforms existing methods, delivering detailed and accurate reconstructions under sparse-view scenarios.
## Keyword: mapping
### Title:
          X-Token: Projection-Guided Cross-Tokenizer Knowledge Distillation
 - **Authors:** Sharath Turuvekere Sreenivas, Adithyakrishna Venkatesh Hanasoge, Mingyu Yang, Ali Taghibakhshi, Saurav Muralidharan, Ashwath Aithal, Pavlo Molchanov
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-tokenizer knowledge distillation allows a student model to learn from teachers with incompatible vocabularies. Prior work operates on hidden states or logits; the latter is preferred as a drop-in replacement requiring no auxiliary components. Logit-based methods either use only the correct-token probability, missing the full 'dark knowledge' in the teacher's distribution, or operate on the full output distribution, relying on strict token partitioning and/or unprincipled heuristic ranking. We identify two key shortcomings of full-distribution, logit-based methods: (i) an uncommon-token failure, where critical tokens fall into the unmatched subset (e.g., Llama's 1100 multi-digit numerals under digit-splitting Qwen supervision) and are suppressed during training, reducing GSM8k from 12.89 to 2.56 compared to same-tokenizer KD from a weaker teacher; and (ii) over-conservative matching, where strict 1-to-1 matching excludes near-equivalent tokens across surface forms. These failures require distinct remedies: eliminating the partition when critical tokens are misaligned, and refining it when alignment is reliable. We propose X-Token, an approach with two complementary loss formulations targeting these issues. P-KL removes partitioning and aligns the student's distribution with the teacher's via a sparse projection matrix W (initialized from tokenizer-level string rules) to address the uncommon-token failure. H-KL retains the hybrid form while relaxing matching to align each student token with its top-ranked teacher mapping under W. Both objectives share W and extend naturally to multiple teachers. Empirically, on Llama-3.2-1B, X-Token outperforms the current state of the art GOLD by +3.82 average points with a Qwen3-4B teacher and by +0.5 with a Phi-4-Mini teacher. Further, a two-teacher setup (Phi-4-mini + Llama-3B) improves over single-teacher distillation by +1.3 points.
### Title:
          What Counts as AI Sycophancy? A Taxonomy and Expert Survey of a Fragmented Construct
 - **Authors:** Meryl Ye, Lujain Ibrahim, Jessica Y. Bo, Myra Cheng, Ida Mattsson, Daniel Vennemeyer, Robert Kraut, Steve Rathje
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI sycophancy has become a prominent concern in large language model (LLM) research. Yet the term lacks a consistent definition and has been applied to behaviors ranging from agreeing with a user's false claim to excessively praising the user to withholding corrective feedback. When researchers, companies, and policymakers use the same term to describe different behaviors, evaluation results become difficult to compare, mitigation strategies fail to transfer, and systems that are resistant to one form of sycophancy continue exhibiting other forms. To address this, we make two contributions. First, we reviewed 70 papers on AI sycophancy to develop a taxonomy of how the behavior has been defined and measured. The taxonomy distinguishes (1) whether a model is sycophantic toward a user's positions and beliefs, or toward the user's broader personal traits and emotions, and (2) whether this occurs through explicit, direct language or more implicit, subtle behaviors such as framing, omission, or tone. Mapping existing literature to our taxonomy reveals that current research has focused on overt forms of sycophancy toward users' beliefs, leaving more subtle and person-directed behaviors relatively understudied. Second, we surveyed 106 experts in AI sycophancy and related fields to examine whether researchers agree on which model behaviors are sycophantic. While experts are nearly unanimous in believing that sycophancy is a significant problem in current AI systems (94.3% agree), they disagree substantially on which specific behaviors qualify. Together, these findings demonstrate that AI sycophancy is a broad family of behaviors with different measurement challenges, intervention requirements, and governance implications. Our taxonomy provides a shared vocabulary for understanding and addressing these behaviors.
### Title:
          Graph Structure of Chebyshev Permutation Polynomials over Binary and Ternary Adic Rings
 - **Authors:** Xiaoxiong Lu, Yuling Dai, Chengqing Li
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding the functional graph of a nonlinear map over a finite domain is crucial for analyzing its dynamical complexity and potential applications in cryptography and pseudorandom generation. In this paper, we investigate the graph structure of Chebyshev permutation polynomials over the ring $\mathbb{Z}_{2^{k_1}3^{k_2}}$, where $k_1$ and $k_2$ are positive integers and $0\in\{k_1, k_2\}$. Each element of the ring is regarded as a vertex, and the mapping relation defined by the polynomial corresponds to a directed edge. Building on new properties of Chebyshev polynomials modulo powers of $2$ and $3$, we provide an explicit characterization of path lengths and cycle structures in the functional graph. We show that, despite the complexities introduced by the binary and ternary components, the graph exhibits strong regularities, including a constant number of cycles of a given length and predictable branching patterns as $k_1$ and $k_2$ increase. Our results extend previous studies over prime-power rings, offering insights into the emergence of complexity in digital nonlinear maps and supporting the security analysis of their cryptographic applications.
### Title:
          The Illusion of Reasoning: Exposing Evasive Data Contamination in LLMs via Zero-CoT Truncation
 - **Authors:** Yifan Lan, Yuanpu Cao, Hanyu Wang, Lu Lin, Jinghui Chen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) have demonstrated impressive reasoning abilities across a wide range of tasks, but data contamination undermines the objective evaluation of these capabilities. This problem is further exacerbated by malicious model publishers who use evasive, or indirect, contamination strategies, such as paraphrasing benchmark data to evade existing detection methods and artificially boost leaderboard performance. Current approaches struggle to reliably detect such stealthy contamination. In this work, we uncover a critical phenomenon: a model's generated reasoning steps actively mask its underlying memorization. Inspired by this, we propose the Zero-CoT Probe (ZCP), a novel black-box detection method that deliberately truncates the entire Chain-of-Thought (CoT) process to expose latent shortcut mappings. To further isolate memorization from the model's intrinsic problem-solving capabilities, ZCP compares the model's zero-CoT performance on the original benchmark against an isomorphically perturbed reference dataset. Furthermore, we introduce Contamination Confidence, a metric that quantifies both the likelihood and severity of contamination, moving beyond simple binary classifications. Extensive experiments on both previously identified contaminated models and specially fine-tuned contaminated models demonstrate that ZCP robustly detects both direct and evasive data contamination. The code for ZCP is accessible at this https URL.
### Title:
          Learning to Evolve: Multi-modal Interactive Fields for Robust Humanoid Navigation in Dynamic Environments
 - **Authors:** Peifeng Jiang, Hong Liu, Jin Jin, Wenshuai Wang, Xia Li
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Safe manipulation-oriented navigation for humanoid robots requires scene memory that remains reliable under locomotion-induced perceptual distortion, environmental changes, and interaction-level geometric safety constraints. Existing semantic mapping and scene-graph systems are difficult to deploy directly in this setting because they often assume stable camera trajectories, static environments, or coarse object geometry. We introduce the Multi-modal Interactive Field (MIF), a humanoid-oriented system that integrates confidence-aware semantic 3D Gaussian Splatting, discrepancy-triggered spatial memory updates, and task-driven geometric reconstruction within a closed-loop perception-adaptation pipeline. MIF couples three fields: an uncertainty-aware 3DGS Appearance Field that suppresses gait-induced blur, a Spatial Field that maintains topological memory, and a Geometry Field that supports Interaction Pose Safety (IPS) before manipulation. A discrepancy detection score is introduced to separate locomotion-induced false-positive changes from persistent changes and updates only locally inconsistent regions. On a Unitree-G1 humanoid in a real dynamic office, MIF improves relocation success in non-static environments from 12% to 94% compared with static scene-graph memory, while reducing semantic memory footprint by 91.4% through feature distillation for practical online operation. Project page and code: this https URL
### Title:
          NasZip: Software and Hardware Co-Design to Accelerate Approximate Nearest Neighbor Search with DIMM-Based Near-Data Processing
 - **Authors:** Cheng Zou, Shuo Yang, Chen Nie, Yu Zou, Yu He, Chao Jiang, Limin Xiao, Weifeng Zhang, Zhezhi He
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Databases (cs.DB); Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As large language models (LLMs) continue to advance, retrieval-augmented generation (RAG) has become the key mechanism for expanding model knowledge and reducing hallucinations. Central to RAG is approximate nearest neighbor search (ANNS), which retrieves database vectors most similar to a given query. However, distance calculation over high-dimensional vectors is inherently memory-bound, causing retrieval performance to be constrained by I/O bandwidth on mainstream platforms such as CPUs and GPUs. Although many prior early exiting (EE) techniques attempt to reduce memory accesses by only computing partial dimensions, the partial distance converges too slowly to the EE threshold, which ultimately limits their performance gains. To address these challenges, we propose NASZIP, a hardware-software co-designed framework that integrates near data processing (NDP) with a novel feature-level early exiting guided by statistics-based principal component analysis (PCA). Instead of relying solely on partial distances, NASZIP incorporates estimation and correction parameters to approximate full dimensional distances accurately, enabling earlier exiting without compromising accuracy. We further introduce a bit-level NDP-aware dynamic-float scheme that significantly reduces memory access for vector data. On the hardware side, we develop a data aware neighbor list mapping strategy that reduces neighbor retrieval latency and inter-channel communication overhead, complemented by a dedicated cache that exploits data locality and enhances prefetch efficiency. With these co-optimized techniques, NASZIP delivers speedups of up to $8.4\times$ / $1.4\times$ over CPU baseline and state-of-the-art GPU implementation at equal accuracy. Relative to the state-of-the-art NDP ANNS accelerator ANSMET, NASZIP achieves $1.69\times$ performance improvement.
### Title:
          Prototype-Guided Classification Sub-Task Decoupling Framework: Enhancing Generalization and Interpretability for Multivariate Time Series
 - **Authors:** Xianhao Song, Yuang Zhang, Yuqi She, Liping Wang, Xuemin Lin
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Time Series Classification (TSC) is a long-standing research problem that has gained increasing attention in recent years with the rapid growth of large-scale temporal data. Despite substantial progress enabled by deep learning, designing TSC models that are both accurate and interpretable remains a challenging task. Many existing approaches adopt a direct feature-to-label classification paradigm, by collapsing high-dimensional temporal embeddings into class logits via a single linear projection (often after global pooling), the paradigm conflates feature extraction and decision logic into an inseparable mapping. To address these limitations, we propose PDFTime, a prototype-guided framework that reformulates time series classification as a multi-stage decision process. Instead of direct feature-to-label mapping, PDFTime leverages learned prototypes to approximate class-conditional feature distributions in the latent space, enabling progressive discrimination through classification sub-tasks of varying granularity. To our knowledge, PDFTime is the first framework to reformulate time series classification as a decoupled, multi-stage similarity-based reasoning process, breaking the long-standing paradigm of direct, black-box feature-to-label mapping. Extensive evaluations demonstrate that PDFTime achieves state-of-the-art (SOTA) performance across UEA and UCR benchmarks. Notably, it secures the top-$1$ accuracy on 80 out of 128 datasets in the UCR archive, significantly outperforming recent strong baselines in both consistency and generalization.
### Title:
          Cross-domain benchmarks reveal when coordinated AI agents improve scientific inference from partial evidence
 - **Authors:** Fiona Y. Wong, Markus J. Buehler
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scientific evidence often spans instruments, databases, and disciplines, so no single source records the full phenomenon. This makes it difficult to determine when coordinated AI agents add value over simpler scientific workflows. We evaluate this question with a cross-domain benchmark spanning four scientific tasks: mapping molecular structure into musical representations, detecting historical paradigm shifts in science, identifying vector-borne disease emergence, and vetting transiting-exoplanet candidates. Each case uses a frozen evaluation panel, predefined scoring protocols, explicit baselines, ablations or null controls, and stated limitations. The results define three operating regimes. When different disciplines each capture only part of the phenomenon, cross-channel composites improve over single-channel baselines: climate-vector emergence reaches AUROC 0.944 and exoplanet vetting reaches AUROC 0.955. However, the exoplanet workflow is effectively tied with a strong combined-summary baseline, showing that decomposition does not always improve top-line performance. When one signal dominates, as in paradigm-shift detection, coordination mainly improves interpretation and traceability. For molecular sonification, the gain is representational rather than predictive. ScienceClaw x Infinite provides the auditable artifact and provenance layer for this evaluation. The benchmark therefore assigns value to coordination only when the corresponding performance, provenance, or representation claim is supported by explicit comparators.
### Title:
          3D LULC classification using multispectral LiDAR and deep learning: current and prospective schemes
 - **Authors:** Narges Takhtkeshha, Aldino Rizaldy, Markus Hollaus, Juha Hyyppä, Fabio Remondino, Gottfried Mandlburger
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Land Use Land Cover (LULC) classification is essential for national 3D mapping, geospatial analysis, and sustainable planning. Multispectral (MS) LiDAR provides synchronized spatial-spectral information, and deep learning (DL) enables 3D point cloud semantic segmentation; however, adoption is limited by the lack of publicly available urban and suburban MS LiDAR datasets aligned with National Mapping and Cadastral Agencies (NMCAs) classification schemes. This study addresses these gaps by introducing L1 and L2 NMCA-aligned LULC classification schemes and a new benchmark MS LiDAR dataset. We evaluate seven state-of-the-art DL models and perform spectral ablation studies at both levels of detail. Results show that Point Transformer V3 achieves the best performance, with mIoU of 79.4% (L1, 8 classes) and 58.9% (L2, 20 classes) using a dual-wavelength LiDAR system (532 nm and 1064 nm). Ablation results show that multispectral information improves performance over geometry-only inputs, with gains of 1.1 percentage points at L1 and 7.8 points at L2. These results highlight the value of LiDAR reflectance for fine-grained material discrimination and support the evolution of NMCA LULC schemes toward higher semantic detail. The Loosdorf-MSL dataset contributes a new benchmark for consistent national and international LULC mapping.
### Title:
          Riemannian geometry meets fMRI: the advantages of modeling correlation manifolds and eigenvector subspaces
 - **Authors:** Mario Severino, Manuela Moretto, Robert A. McCutcheon, Mattia Veronese
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Correlation matrices are fundamental summaries of functional brain networks, yet standard analyses often treat entries independently, ignoring the curved geometry of correlation space. Existing geometric methods frequently lack closed-form operations or depend on arbitrary region ordering, limiting scalability. We introduce a scalable geometric framework with two components: (i) the Off-log metric, a smooth transformation mapping correlation matrices to symmetric zero-diagonal matrices. This enables closed-form expressions for distances, Frechet means, and linear models, allowing standard statistical modeling without complex manifold optimization. (ii) Grassmannian subspace discrimination, which compares subjects via principal-angle distances between eigenvector subspaces, resolving inherent sign and basis ambiguities. Both components integrate into standard machine-learning workflows for inference, regression, and classification. Validated across two clinical cohorts (Parkinson's and psychosis) and three ageing fMRI datasets, the Off-log metric increased sensitivity in permutation tests and matched or exceeded Riemannian and Euclidean baselines in classification. Brain-age prediction performance was comparable, with Riemannian metrics excelling in two of three cohorts. The Grassmannian method consistently outperformed Euclidean baselines, highlighting disease-relevant networks. Overall, geometry-aware representations improve sensitivity and predictive performance while remaining straightforward to deploy at scale.
### Title:
          TransitLM: A Large-Scale Dataset and Benchmark for Map-Free Transit Route Generation
 - **Authors:** Hanyu Guo, Jiedong Yang, Chao Chen, Longfei Xu, Kaikui Liu, Xiangxiang Chu
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Public transit route planning traditionally depends on structured map infrastructure and complex routing engines, and no existing dataset supports training models to bypass this dependency. We present TransitLM, a large-scale dataset of over 13 million transit route planning records from four Chinese cities covering 120,845 stations and 13,666 lines, released as a continual pre-training corpus and benchmark data for three evaluation tasks with complementary metrics. Experiments show that an LLM trained on TransitLM produces structurally valid routes at high accuracy and implicitly grounds arbitrary GPS coordinates to appropriate stations without any explicit mapping. These results demonstrate that transit route planning can be learned entirely from data, enabling end-to-end, map-free route generation directly from origin-destination information. The dataset and benchmark are available at this https URL, with evaluation code at this https URL.
### Title:
          Translating Signals to Languages for sEMG-Based Activity Recognition
 - **Authors:** Ming Wang, Haoxuan Qu, Qiuhong Ke, Wei Zhou, Hossein Rahmani, Jun Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Surface electromyography (sEMG) signal-based activity recognition has attracted increasing research attention in recent years. To develop accurate sEMG signal-based activity recognizers, numerous approaches have been proposed. Some studies focus on designing larger and more expressive model architectures to enhance the representational capacity of sEMG signals, while others aim to enrich model priors through large-scale pretraining, thereby improving recognition performance. Recently, large language models (LLMs) have shown remarkable generalization and reasoning capabilities in natural language processing, whose implicit knowledge, learned from extensive linguistic descriptions of actions, opens new possibilities for interpreting sEMG signals and inferring activity intentions. Motivated by this, we propose LLM-sEMG, a novel framework that leverages LLMs as sEMG activity recognizers. Within this framework, we design a language-oriented mapping mechanism that converts continuous sEMG sequences into sEMG language, integrating several strategies to further facilitate the signal-to-language mapping process. Extensive experiments demonstrate that the proposed framework achieves highly accurate sEMG signal-based activity recognition using large language models.
### Title:
          Towards Clinically Interpretable Ophthalmic VQA via Spatially-Grounded Lesion Evidence
 - **Authors:** Xingyue Wang, Bo Liu, Meng Wang, Zhixuan Zhang, Chengcheng Zhu, Huazhu Fu, Jiang Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual Question Answering (VQA) holds great promise for clinical support, particularly in ophthalmology, where retinal fundus photography is essential for diagnosis. However, ophthalmic VQA benchmarks primarily emphasize answer accuracy, neglecting the explicit visual evidence necessary for clinical interpretability. In this work, we introduce FundusGround, a new benchmark for clinically interpretable ophthalmic VQA with spatially-grounded lesion evidence. Specifically, we propose a three-stage pipeline that collects 10,719 fundus images with 15,595 image-level meticulously annotated lesions. To ensure anatomical consistency and clinical validity, all lesions are spatially localized using the Early Treatment Diabetic Retinopathy Study (ETDRS) grid, enabling standardized mapping to nine clinically meaningful retinal regions. Built upon this structured lesion evidence, 72,706 questions are then generated spanning four formats: open-ended, closed-ended, single-choice, and multiple-choice. We further benchmark multiple general- and medical- large vision-language models using dual metrics for answer accuracy and lesion-level reasoning. The experiments demonstrate that incorporating lesion-level visual evidence consistently improves model performance and transparency, highlighting the necessity of explicit spatial grounding for reliable and explainable ophthalmic VQA.
### Title:
          Supervised Classification Heads as Semantic Prototypes: Unlocking Vision-Language Alignment via Weight Recycling
 - **Authors:** David Méndez, Roberto Confalonieri, Natalia Díaz Rodríguez
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language Models (VLMs) excel at tasks like zero-shot classification and cross-modal retrieval by mapping images and text to a shared space, but this requires expensive end-to-end training with massive paired datasets. Current post-hoc alignment methods reduce computational costs by connecting pretrained encoders through lightweight mappings, yet still demand substantial paired data. In this work, we investigate the potential of repurposing the classification heads of pretrained vision models as semantic prototypes. The recycling of these weights, typically discarded after pretraining, unlocks two distinct capabilities: it enables zero-shot alignment by using weights as semantic anchors, and serves as a robust data augmentation strategy by mixing these prototypes with real image-text pairs. We demonstrate that integrating our approach with several state-of-the-art post-hoc alignment techniques consistently boosts accuracy in cross-modal retrieval, zero- and few-shot classification tasks.
### Title:
          Beyond Chamfer Distance: Granular Order-aware Evaluation Metric For Online Mapping
 - **Authors:** Chouaib Bencheikh Lehocine, Adam Lilja, Junsheng Fu, Lars Hammarstrand
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Online map estimation is a crucial component of autonomous driving systems that reduces the reliance on costly high-definition maps. State-of-the-art (SOTA) methods commonly predict map elements as ordered sequences of points that form polylines and polygons. The evaluation of these methods relies predominantly on mean average precision (mAP) based on thresholded Chamfer distance (CD). This framework lacks sensitivity to point ordering and provides limited granularity in assessing geometric quality, making it difficult to distinguish which methods truly excel over others. In this work, we address these limitations on two fronts. For the single-instance similarity measure, we introduce sequence optimal sub-pattern assignment (SOSPA), an order-aware metric that enables fine-grained evaluation of individual geometries while satisfying all metric axioms. For the multi-instance evaluation framework, we propose polyline localisation and detection (PLD), a soft metric that jointly captures detection quality and geometric accuracy, replacing the hard thresholding of mAP with a principled soft assignment. Through evaluations on nuScenes, we demonstrate that PLD effectively ranks SOTA online mapping methods (MapTRv2, StreamMapNet, MapTracker) while providing a decomposed error analysis. This analysis identifies detection capability as the dominant bottleneck in current methods, revealing a performance trend that mAP fails to capture. Code for evaluation using our metrics will be released.
### Title:
          Plug-in Losses for Evidential Deep Learning: A Simplified Framework for Uncertainty Estimation that Includes the Softmax Classifier
 - **Authors:** Berk Hayta, Hannah Laus, Simon Mittermaier, Felix Krahmer
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Audio and Speech Processing (eess.AS); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-world sensor-based learning systems require uncertainty estimation that is both reliable and computationally efficient. Evidential Deep Learning (EDL) provides single-pass uncertainty estimation by modeling the class probabilities via Dirichlet distributions, where the Dirichlet parameters are predicted by a learned neural network mapping. However, this approach can lead to computational challenges, as Dirichlet expected objectives are more complex than standard supervised learning losses, complicating their analysis and implementation. We address this issue by approximating the objective of the first-order empirical risk minimization problem induced by EDL with a plug-in loss evaluated at the Dirichlet mean and show that, under mild assumptions, the approximation error decays with growing evidence for a broad class of loss functions, including mean-squared error and cross-entropy loss. As a special case, our analysis provides justification for the use of softmax in the context of uncertainty estimation, since under a particular evidence-to-Dirichlet mapping, our framework includes the standard softmax classifier. We validate the proposed simplified objectives on the Google Speech Commands dataset and show that they achieve predictive accuracy and selective prediction performance comparable to classical EDL, while being simpler to implement using standard deep learning losses and training pipelines. To the best of our knowledge, this empirical analysis is the first to obtain coverage-accuracy trade-offs for speech recognition tasks through EDL.
### Title:
          Remember to be Curious: Episodic Context and Persistent Worlds for 3D Exploration
 - **Authors:** Lily Goli, Justin Kerr, Daniele Reda, Alec Jacobson, Andrea Tagliasacchi, Angjoo Kanazawa
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Exploration is a prerequisite for learning useful behaviors in sparse-reward, long-horizon tasks, particularly within 3D environments. Curiosity-driven reinforcement learning addresses this via intrinsic rewards derived from the mismatch between the agent's predictive model of the world and reality. However, translating this intrinsic motivation to complex, photorealistic environments remains difficult, as agents can become trapped in local loops and receive fresh rewards for revisiting forgotten states. In this work, we demonstrate that this failure stems from a lack of spatial persistence and episodic context. We show that effective curiosity requires a model of the world that is persistent and continuously updated, paired with an agent that maintains an episodic trajectory history to navigate toward novel regions. We achieve this using an online 3D reconstruction as a persistent model of the world, while the agent policy is parameterized as a sequence model over RGB observations to maintain episodic context. This design enables effective exploration during training while allowing the agent to navigate using solely RGB frames at deployment. Trained purely via curiosity on HM3D, our agent outperforms RL-based active mapping baselines and generalizes zero-shot to Gibson and AI-generated worlds. Our end-to-end policy enables efficient adaptation to downstream tasks, such as apple picking and image-goal navigation, outperforming from-scratch baselines. Please see video results at this https URL.
## Keyword: localization
### Title:
          PeakFocus: Bridging Peak Localization and Intensity Regression via a Unified Multi-Scale Framework for Electricity Load Forecasting
 - **Authors:** Wangzhi Yu, Peng Zhu, Qing Zhao, Yiwen Jiang, Dawei Cheng
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Electricity load peak forecasting (ELPF), simultaneously predicting peak timing and intensity, is a prerequisite for effective grid scheduling and risk management. However, existing methods face three limitations. First, they adopt a two-stage predict-then-locate paradigm, which severs the link between temporal localization and intensity regression. Second, they still struggle with the multi-scale representation conflict, leading to peak misjudgment and timing misalignment. Third, the lack of explicit peak timing context during intensity regression causes intensity smoothing because predictions are dominated by global smoothing trends. To address these limitations, we propose PeakFocus, a unified framework for ELPF. (i) A Unified Peak-Aware Pipeline (UPAP) utilizes a triple hybrid loss to jointly supervise temporal localization and intensity regression, alongside a tolerance-based evaluation protocol. (ii) A Multi-Scale Mixing Peak Locator (MSM-PL) exploits coarse-grained features to mitigate peak misjudgment caused by local fluctuations, and injects them into fine-grained features via a cascade mechanism to resolve timing misalignment. (iii) A Location-Aware Decoder (LAD) injects peak timing context into the intensity regression process, providing explicit guidance to counteract intensity smoothing and improve peak intensity estimation. Extensive experiments on the public Electricity (ELC) dataset and our industrial-scale World Large-scale Electricity Load (WLEL) dataset show that PeakFocus outperforms baselines in both timing precision and intensity estimation.
### Title:
          $\textit{BlockFormer}$ : Transformer-based inference from interaction maps
 - **Authors:** Eloïse Touron, Pedro L. C. Rodrigues, Julyan Arbel, Nelle Varoquaux, Michael Arbel
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Quantitative Methods (q-bio.QM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Inference from interaction maps, such as centromere identification from genome-wide chromosome conformation capture techniques -- notably Hi-C -- can be formulated as a generic inverse problem: infer a set of parameters given a map summarizing pairwise interactions between entities through blocks of variable numbers and sizes. In this work, we introduce a data-driven approach that leverages shared structure between these maps, such as global alignment between localized patterns, while handling the variability in number and size of entities arising in real-world data. Our approach relies on a transformer architecture capable of handling such variability and a custom simulator to generate abundant, yet computationally cheap synthetic data for training. Applied to the problem of centromere localization, the method accurately recovers their genomic positions across a wide range of species of various genome sizes.
### Title:
          Flat-Pack Bench: Evaluating Spatio-Temporal Understanding in Large Vision-Language Models through Furniture Assembly
 - **Authors:** Aditya Chetan, Eric Cai, Peeyush Kushwaha, Bharath Raj Nagoor Kani, Utkarsh Mall, Qianqian Wang, Noah Snavely, Bharath Hariharan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The emergence of Large Vision-Language Models (LVLMs) has significantly advanced video understanding capabilities. However, existing benchmarks focus predominantly on coarse-grained tasks such as action segmentation, classification, captioning, and retrieval. Furthermore, these benchmarks often rely on entities that can be easily identified verbally, like household objects, animals, human subjects, etc., limiting their applicability to complex, in-the-wild video scenarios. But, many applications such as furniture assembly, cooking, etc., require step-by-step fine-grained spatio-temporal understanding of the video, which is not sufficiently evaluated in current benchmarks. To address this gap, we introduce Flat-Pack Bench, a novel benchmark centered on furniture assembly tasks. Our benchmark evaluates LVLMs on nuanced tasks, including temporal ordering of assembly actions, temporal localization of assembly state, understanding part mating, and tracking, using multiple-choice questions paired with visual prompts highlighting relevant parts as references for fine-grained questions. Our experiments reveal that state-of-the-art LVLMs struggle significantly with fine-grained spatio-temporal reasoning, highlighting their limitations in effectively leveraging temporal information from videos, limited tracking ability, and understanding of spatial interactions like physical contact.
### Title:
          Look-Closer-Then-Diagnose: Confidence-Aware Ultrasound VQA via Active Zooming
 - **Authors:** Yue Zhou, Erxuan Wu, Yikang Sun, Hongjoo Lee, Yuan Bi, Huixiong Xu, Zhongliang Jiang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language Models (VLMs) have significantly advanced medical visual question answering, yet their performance in ultrasound remains suboptimal. In clinical practice, sonographers explicitly focus on lesion regions to formulate reports, though diagnostic interpretations sometimes vary due to inherent subjectivity. However, existing VLMs are not explicitly structured to interactively zoom into lesions prior to diagnosis; moreover, they typically treat annotations as unbiased ground truths, failing to account for their inherent subjectivity and ambiguity. In this paper, we propose a framework specifically designed to consider the sonographer's cognitive workflow. We first introduce a structured Zoom-then-Diagnose paradigm, which replicates the interactive search process to enable lesion-focused reasoning. Furthermore, within the Group Relative Policy Optimization (GRPO) framework, we introduce an uncertainty-aware reward derived from stochastic group-wise rollouts to estimate prediction consistency as a proxy for model confidence. Together, these two components encourage the model to reinforce accurate predictions on clear cases while remaining cautious under ambiguity. Experiments across liver, breast, and thyroid datasets show that our framework improves lesion localization by 39.3\%, demonstrating that our model has learned the ability to actively look closer and diagnose.
### Title:
          FuzzingBrain V2: A Multi-Agent LLM System for Automated Vulnerability Discovery and Reproduction
 - **Authors:** Ze Sheng, Zhicheng Chen, Qingxiao Xu, Kewen Zhu, Jeff Huang
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Software vulnerabilities pose critical security threats, with nearly 50,000 CVEs reported in 2025. While Large Language Models (LLMs) show promise for automated vulnerability detection, three key challenges remain. First, LLM-generated vulnerability reports suffer from high false positive rates and lack reproducible verification. Second, existing LLM-based approaches use suboptimal granularities for vulnerability localization: function-level analysis overlooks bugs when context becomes extensive, while line-level analysis lacks sufficient context. Third, existing approaches have difficulty reasoning about vulnerabilities with complex cross-function dependencies and triggering conditions. We present FuzzingBrain V2, a multi-agent system that addresses these gaps through four key contributions: (1) fully automated vulnerability analysis built on Google's OSS-Fuzz, ensuring all reported vulnerabilities are fuzzer-reproducible; (2) Suspicious Point, a novel control-flow-based abstraction for precise vulnerability localization at the optimal granularity; (3) logic-driven hierarchical function analysis with dual-layer fuzzing enhancing function coverage under resource constraints; (4) MCP-based static and dynamic analysis tools with context engineering enhancing complex vulnerability reasoning. On the AIxCC 2025 Final Competition C/C++ dataset, FuzzingBrain V2 achieved 90% detection rate (36 of 40 vulnerabilities). In real-world deployment, FuzzingBrain V2 discovered 29 zero-day vulnerabilities across 12 open-source projects, all confirmed and fixed by maintainers, with 2 assigned CVE IDs.
### Title:
          MM-Conv: A Multimodal Dataset and Benchmark for Context-Aware Grounding in 3D Dialogue
 - **Authors:** Anna Deichler, Jim O'Regan, Fethiye Irmak Dogan, Lubos Marcinek, Anna Klezovich, Iolanda Leite, Jonas Beskow
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Grounding language in the physical world requires AI systems to interpret references that emerge dynamically during conversation. While current vision-language models (VLMs) excel at static image tasks, they struggle to resolve ambiguous expressions in spontaneous, multi-turn dialogue. We address this gap by introducing (1) a benchmark for referential communication in dynamic 3D environments, built from 6.7 hours of egocentric VR interaction with synchronized speech, motion, gaze, and 3D scene geometry, and (2) a two-stage grounding pipeline that explicitly resolves conversational ambiguity before visual localization. The benchmark includes over 4,200 manually verified referring expressions spanning full, partitive, and pronominal types. Our contextual rewriting approach improves grounding performance by 11-22 percentage points on average, with a pure detector (GroundingDINO) reaching 56.7% on pronominals after rewriting, nearly double the best end-to-end baseline. Results demonstrate that decoupling linguistic reasoning from visual perception is more effective than end-to-end approaches for conversational grounding.
### Title:
          Near-Field User Location Inference From Far-Field Power Measurements
 - **Authors:** Shima Mashhadi, Tiep M. Hoang, Alireza Vahid
 - **Subjects:** Subjects:
Information Theory (cs.IT); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Near-field beamfocusing enabled by extremely large-aperture arrays (ELAA) is a promising 6G technique for massive connectivity and high spectrum efficiency. While beamfocusing concentrates energy at an intended user, the radiated field outside the focal point exhibits a structured leakage that varies with the focal-point coordinates. This paper shows that this leakage enables a new form of passive user localization in which distributed far-field sensors measuring only received power can infer the user's location by exploiting this location-dependent power signature. Using the induced noncentral chi-square statistics, we derive a Bayesian Cramér-Rao lower bound (BCRLB) that establishes the fundamental limits of this inference problem. We then evaluate a model-based grid-search estimator and an attention-based permutation-invariant deep learning regressor (DeepSet). Results under both line-of-sight (LoS) and multipath propagation confirm that reliable location inference is feasible, with accuracy improving as more sensors and snapshots are used.
### Title:
          Seizure-Semiology-Suite (S3): A Clinically Multimodal Dataset, Benchmark, and Models for Seizure Semiology Understanding
 - **Authors:** Lina Zhang, Tonmoy Monsoor, Peizheng Li, Jiarui Cui, Xinyi Peng, Chong Han, Prateik Sinha, Siyuan Dai, Jessica Nichole Pasqua, Colin M McCrimmon, Weiting Liu, Hailey Marie Miranda, Bing Hu, Xiangting Wu, Tengyou Xu, Chunhan Li, Jiaye Tian, Jiarui Tang, Detao Ma, Lingye Kong, Junnan Lyu, Jungang Li, Yan Zan, Junhua Huang, Rajarshi Mazumder, Vwani Roychowdhury
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Multimodal Large Language Models (MLLMs) have demonstrated remarkable proficiency in general video understanding, their capacity to interpret involuntary, and spatio-temporally evolving pathologic motor behaviors such as seizure semiology remains largely untested. To address this gap, we introduce Seizure-Semiology-Suite, a clinically grounded dataset and benchmark for fine-grained, structured seizure semiology understanding. The dataset includes 438 seizure videos annotated with over 35,000 dense labels covering 20 ILAE-defined semiological features. Building on this dataset, we propose a seven-task hierarchical benchmark that systematically evaluates MLLMs from low-level visual perception to temporal sequencing, narrative report generation, and seizure diagnosis. To enable clinically meaningful evaluation of generated reports, we further introduce the Report Quality Index for Seizure Semiology (Seizure-RQI). Extensive baselines across 11 open-weight MLLMs reveal systematic weaknesses in laterality reasoning, temporal localization, symptom sequencing, and clinically faithful reporting. We show that seizure-specific fine-tuning substantially improves performance across tasks, and that a two-stage neuro-symbolic framework achieves an F1 score of 0.96 on epileptic versus non-epileptic seizure classification. Seizure-Semiology-Suite establishes a rigorous benchmark for evaluating multimodal models in safety-critical medical video understanding and guides the development of clinically reliable, domain-adaptive multimodal intelligence.
### Title:
          PITMuS: A Tool for Automated Bug Dataset Generation via Source-Level Mutant Reconstruction
 - **Authors:** Tasfia Tasnim, Soneya Binta Hossain
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLM-based software engineering increasingly depends on executable, context-rich bug artifacts: paired correct and buggy code, methods under test (MUTs), documentation, and metadata. These artifacts support the training and evaluation of automated bug localization and repair techniques, testing and test oracle generation methods, and documentation-driven automation. Although curated benchmarks (e.g., Defects4J) remain valuable, they are static and increasingly vulnerable to contamination as code models are trained on large public corpora. A complementary strategy is to generate fresh, cutoff-aware datasets by selecting real system versions and injecting controlled bugs at the source level. Mutation testing is a natural basis for this strategy: it applies predefined mutation operators to programs and records whether the existing test suite detects each injected change. PIT is a state-of-the-practice mutation testing tool for Java that performs mutation at the bytecode level. This design makes mutation testing fast and practical, but PITMuS reports mutants primarily through XML, making them difficult to inspect, replay, or reuse as structured source-level dataset records. To address this gap, we present PITMuS, which combines PITMuS XML metadata with debug information from compiled Java class files to localize and reconstruct the source edit corresponding to each mutant. PITMuS then automatically produces structured datasets containing source-level buggy and fixed code pairs, documentation context, and metadata for downstream training and evaluation. Although we evaluate PITMuS on eight open-source Java systems, it can be applied to any Java system where PITMuS can be integrated.
### Title:
          EvoVid: Temporal-Centric Self-Evolution for Video Large Language Models
 - **Authors:** Shiqi Huang, Ziyue Wang, Zhongrong Zuo, Han Qiu, Qi She, Bihan Wen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent Video Large Language Models (Video-LLMs) have demonstrated strong capabilities in video reasoning through reinforcement learning (RL). However, existing RL pipelines rely heavily on human-annotated tasks and solutions, making them costly to scale and fundamentally constrained by human expertise. Self-evolving frameworks have recently emerged as a promising alternative through autonomous Questioner-Solver self-play. Unfortunately, these approaches are primarily designed for static modalities such as text and images, fundamentally failing to capture the temporal dynamics that are central to video reasoning. In this work, we propose $\textbf{EvoVid}$, a temporal-centric self-evolving framework that enables Video-LLMs to improve directly from raw, unannotated videos. Specifically, we introduce two complementary temporal-centric rewards: a temporal-aware Questioner reward that encourages temporally dependent question generation through temporal perturbation sensitivity, and a temporal-grounded Solver reward that provides automatic temporal supervision via inherent video segment localization. Extensive experiments across four base models and six benchmarks demonstrate consistent improvements over both base models and existing self-evolving baselines, achieving competitive performance with supervised methods. These results highlight temporal-centric self-evolution as an effective and scalable paradigm for video understanding and reasoning.
### Title:
          AgroVG: A Large-Scale Multi-Source Benchmark for Agricultural Visual Grounding
 - **Authors:** Haocheng Li, Juepeng Zheng, Zenghao Yang, Kaiqi Du, Guilong Xiao, Gengmeng Pu, Haohuan Fu, Jianxi Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual grounding, the task of localizing objects described by natural-language expressions, is a foundational capability for agricultural AI systems, enabling applications such as selective weeding, disease monitoring, and targeted harvesting. Reliable evaluation of agricultural visual grounding remains challenging because agricultural targets are often small, repetitive, occluded, or irregularly shaped, and instructions may refer to one, many, or no objects in an image. Evaluating this capability therefore requires jointly testing localization accuracy, target-set completeness, and existence-aware abstention. To address these challenges, we introduce \textbf{AgroVG}, a multi-source benchmark that formulates agricultural grounding as generalized set prediction: given an image and a referring expression, a model must return all matching target instances or abstain when no target is present. AgroVG contains 10{,}071 annotation-grounded image-query pairs from ten source datasets across six target families: crop/weed, fruit, wheat head, pest, plant disease, and tree canopy. It supports bounding-box grounding (T1) across all six families and instance-mask grounding (T2) on sources with reliable instance-level pixel annotations, with queries covering single-target, multi-target, and target-absent regimes. AgroVG further provides task-specific protocols for box-set matching and query-level mask coverage. Zero-shot evaluation of 26 model configurations spanning closed-source MLLMs, open-source VLMs, and specialized grounding systems reveals persistent gaps: the best multi-target Set-$F_1$ reaches only 0.35, and the best positive-query mask success rate at IoU@0.75 remains below 0.17. Data and code are available at this https URL .
### Title:
          Physiology and Anatomy Aware Inverse Inference of Myocardial Infarction for Cardiac Digital Twin
 - **Authors:** Mengxiao Wang, Yilin Lyu, Julia Camps, Ching Hui Sia, Mark Yan-Yee Chan, Yanrui Jin, Shuzhi Sam Ge, Chengliang Liu, Lei Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate localization of myocardial infarction is essential for risk stratification. While LGE-MRI remains the gold standard, it is resource-intensive. Integrating cine MRI with ECG enables a more detailed representation of infarct properties. Existing inverse MI inference methods overlook realistic scar morphology and cardiac repolarization, reducing sensitivity to subtle ECG variations and interpretability of infarct-induced electrophysiological changes. In this paper, we propose a novel framework for noninvasive MI localization using cardiac digital twins. To bridge the domain gap between simulation and reality, we introduce an anatomy-aware stochastic infarct synthesis strategy to synthesize realistic, irregular scars with border zones, mimicking ischemic transmural progression. We then construct a virtual cohort to simulate QRS-T waveforms, capturing both depolarization and repolarization dynamics. Furthermore, we design a Physiology and Anatomy Aware Network (PAA-Net) that jointly encodes 3D myocardial geometry and multi-lead ECGs to infer infarct areas with varying localizations, sizes, spatial extents, and transmuralities. Experimental results demonstrate that our framework significantly outperforms existing methods in inverse inference, achieving Dice scores of 0.7391 and 0.5503 for scar and border zone segmentation, respectively, while further enhancing the interpretability of the ECG-infarct relationship. Our code will be released upon acceptance.
### Title:
          Zero-Shot Temporal Action Localization Through Textual Guidance
 - **Authors:** Benedetta Liberatori, Alessandro Conti, Lorenzo Vaquero, Paolo Rota, Yiming Wang, Elisa Ricci
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Zero-shot temporal action localization (ZS-TAL) consists of classifying and localizing actions in untrimmed videos, where action classes are unseen at training time. Existing work uses Vision and Language Models (VLMs), taking advantage of their strong zero-shot transfer capabilities. Yet, these models face evident challenges with fine-grained action classification, making it difficult to directly use them to distinguish between the presence and absence of an action. Most current methods for ZS-TAL address these challenges by training models on large-scale video datasets, which require annotated data and often result in limited generalization performance. Recently, approaches discarding the use of labeled data have emerged as an alternative. Following this direction, we propose a novel approach, ``Textual Guidance for finer localization of actions in videos'' (TEGU), that compensates for the lack of supervision from training data by exploiting rich textual information derived from large language models and structured text extracted from captions. This additional linguistic context can improve fine-grained discrimination by providing richer cues about fine-grained action differences within videos. We validate the effectiveness of the proposed method by conducting experiments on the THUMOS14 and the ActivityNet-v1.3 datasets. Our results show that, by exploiting rich textual information for improved action localization, TEGU outperforms state-of-the-art ZS-TAL approaches that do not involve training
### Title:
          GALAR-TemporalNet v2: Anatomy-Guided Dual-Branch Temporal Classification with Bidirectional Mamba and Dual-Graph GCN for Video Capsule Endoscopy -- after competition results
 - **Authors:** Jiye Won (1), Seangmin Lee (1), Soon Ki Jung (1) ((1) Kyungpook National University)
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video Capsule Endoscopy (VCE) poses a challenging multi-label temporal classification problem, requiring simultaneous localization of 8 anatomical regions and detection of 9 pathological findings across tens of thousands of frames. We present GALAR-TemporalNet v2, a hierarchical temporal model that addresses three core challenges: extreme class imbalance, long-range temporal dependencies, and pathology--anatomy entanglement. Our architecture combines windowed self-attention for local modeling, a Dual-Graph GCN for global frame relationships, and Bidirectional Mamba for selective boundary context encoding. A novel anatomy prototype residual pathway decouples pathological deviation signals from normal organ appearance, and a frame-level GCN skip connection stabilizes training of visually confusable rare classes. The competition version, GALAR-TemporalNet, achieved an overall mAP@0.5 of 0.2644 and mAP@0.95 of 0.2353 on the RARE-VISION test set. Following the competition, the redesigned GALAR-TemporalNet v2 -- incorporating a restructured pathology branch, refined loss functions, and extended post-processing -- improved these results to mAP@0.5 of 0.3409 and mAP@0.95 of 0.3333.
### Title:
          Can Transformers Learn to Verify During Backtracking Search?
 - **Authors:** Yin Jun Phua, Tony Ribeiro, Tuan Nguyen, Katsumi Inoue
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Logic in Computer Science (cs.LO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Backtracking search underlies classical constraint solvers, planners, and theorem provers. Recent transformer-based reasoning systems explore search trees over their own intermediate steps. A common training recipe fits an autoregressive next-token loss on offline solver traces. The model's input at each step is a cumulative trace of all prior decisions. The optimal continue-or-backtrack predictor depends only on the current search state, since two trajectories reaching the same state admit the same viable continuations. We show that decoder-only transformers trained on cumulative traces fail this requirement in two ways: the trace can scatter state features across many positions (scattered retrieval), and the predictor can condition on the trajectory rather than the state (history entanglement). We address scattered retrieval with localization, a trace-level fix that rewrites each decision block to expose state features locally. We address history entanglement with Selective State Attention (SSA), a fixed attention mask that enforces state-based decisions structurally without modifying training data, objective, or parameters. We focus on reactive verification, after propagation has exposed a contradiction. We test SSA on 3-SAT, graph coloring, Blocks World, and backtracking parsing. On same-state pairs that differ only in prior history, SSA emits identical decisions while a cumulative-trained causal baseline does not. Our contribution is a diagnostic of transformer behavior on serialized trajectory data, paired with a structural fix. Pretrained language models that search over their own reasoning steps may face the same failure. Our analysis opens up inference-time context clearing as a candidate way to apply the same isolation without retraining.
### Title:
          Spatial Memory for Out-of-Vision Manipulation in Vision-Language-Action
 - **Authors:** Pengteng Li, Weiyu Guo, He Zhang, Tiefu Cai, Xiao He, Yandong Guo, Hui Xiong
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce SOMA, the Spatial Memory framework for Out-of-Vision Manipulation in Vision-Language-Action (VLA) models. Most existing VLAs implicitly assume that task-relevant objects are always visible, leading to brittle and reactive behaviors when targets fall outside the camera's field of view. SOMA addresses this limitation by equipping VLAs with a persistent spatial memory constructed from multi-view observations acquired via a movable head camera, enabling reasoning beyond the current visual frustum. The framework consists of three components: Spatial Memory Construction, which aggregates angular-wise observations into a unified spatial-semantic representation through scanning; Dynamic Memory Refinement, which maintains global consistency over time; and Contextual Memory Retrieval, which activates instruction-relevant spatial cues during manipulation. We evaluate SOMA on five challenging real-world out-of-vision manipulation tasks, including multi-step and dual-arm scenarios where target objects are initially invisible. Experimental results show that SOMA not only improves task success rates, but also induces qualitatively different manipulation behaviors, with faster target localization, reduced viewpoint search, and near one-shot grasping under partial observability. Additional experiments on RoboCasa GR1 and SimplerEnv further validate the effectiveness of SOMA's memory design under conventional fully observable settings. Code will be released soon.
### Title:
          Robustness of breast lesion segmentation under MRI undersampling improves with k-space-aware deep learning
 - **Authors:** Lukas T. Rotkopf, Marco Schlimbach, Julius C. Holzschuh, Heinz-Peter Schlemmer, Jens Kleesiek, Moritz Rempe
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Medical Physics (physics.med-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Purpose: To assess whether breast lesion segmentation can be learned directly from acquired MRI k-space, and whether doing so improves robustness when data are accelerated or noisy. Materials and Methods: This retrospective study used public breast dynamic contrast-enhanced MRI (DCE-MRI) datasets with acquired and synthetic k-space, together with a within-dataset synthetic control. We compared four 3D U-Net variants: a hybrid k-space-to-image model, a native k-space model, and magnitude and complex image-space baselines. Models were evaluated under increasing undersampling and added complex Gaussian k-space noise. The primary outcome was patient-level Dice similarity coefficient under cross-validation, with the hybrid model prespecified as the main comparison against the magnitude image-space baseline. Results: At full sampling, the hybrid and image-space models performed similarly. As acceleration increased, the hybrid model retained substantially more segmentation accuracy and significantly outperformed the magnitude image-space baseline across moderate to high undersampling levels. The same pattern was observed when noise was added directly to k-space: the hybrid model degraded more slowly, whereas the image-space baseline failed under heavier noise. This advantage was reproduced in the within-dataset synthetic control. Feature analysis suggested that the k-space stage and image-space stage played complementary roles, with frequency-domain filtering concentrated before image-domain lesion localization. Conclusion: K-space-aware deep learning improves the robustness of breast lesion segmentation under MRI undersampling and k-space noise, while matching image-space methods at full sampling.
### Title:
          FastTab: A Fast Table Recognizer with a Tiny Recursive Module and 1D Transformers
 - **Authors:** Laziz Hamdi, Amine Tamasna, Pascal Boisson, Thierry Paquet
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Table structure recognition (TSR) requires both table-level coherence (row/column counts, headers, spanning cells) and precise separator localization. We introduce FastTab, a grid-centric TSR model that avoids autoregressive HTML decoding by combining (i) a lightweight Tiny Recursive Module (TRM) for global reasoning and (ii) axial 1D Transformer encoders that capture long-range dependencies along rows and columns. The model predicts row/column counts, header rows, and separators to construct a grid, then infers rowspan/colspan using ROI-aligned cell features. Across four benchmarks (PubTabNet, FinTabNet, PubTables-1M, and SciTSR), FastTab achieves competitive structure recovery performance while operating at low-latency inference. We further study robustness under pixel-level anonymisation and show an extension to curved separators for camera-captured documents. The source code will be made publicly available at this https URL .
### Title:
          Training-Free Fine-Grained Semantic Segmentations in Low Data Regimes: A FungiTastic Baseline
 - **Authors:** Sebastian Cavada, Francesco Pelosin, Lapo Faggi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fine-grained semantic segmentation requires both precise localization and discrimination between visually similar classes. In FungiTastic, this problem is further complicated by a long-tailed distribution and strong variation in image acquisition conditions. We propose a training-free two-stage framework that decouples segmentation from classification. SAM3 first produces class-agnostic mushroom masks using macro-taxonomic prompts, and DINOv3 then assigns fine-grained labels through prototype matching in the embedding space. To improve this stage, we apply a simple transformation of the DINOv3 feature space that improves prototype-based classification. Compared with class-specific prompting, our approach is more scalable and keeps the segmentation cost low. We report results from one-shot to few-hundred-shot regimes, providing, to the best of our knowledge, the first baseline for fine-grained semantic segmentation in low-data settings.
### Title:
          SceneAligner: 3D-Grounded Floorplan Localization in the Wild
 - **Authors:** Junhyeong Cho, Ruojin Cai, Hadar Averbuch-Elor
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many public buildings provide floorplans with a "you are here" indicator to help visitors orient themselves. Floorplan localization seeks to computationally replicate this capability by determining where visual observations were captured within a floorplan. However, existing methods typically assume controlled small-scale environments and precise vectorized floorplans, limiting their ability to operate in large-scale buildings and rasterized floorplans. In this work, we present an approach for performing floorplan localization in the wild by grounding the task in a reconstructed 3D representation of the scene. Given an unconstrained image collection, our method reconstructs a gravity-aligned 3D scene and projects it into a 2D density map that serves as a floorplan proxy. Floorplan localization is then formulated as aligning this proxy with the input floorplan via a 2D similarity transform. To bridge the appearance gap between density maps and architectural floorplans, we adapt a 2D foundation model to learn cross-modal correspondences, introducing a fine-tuning scheme that encourages semantically aligned matches while preserving structural consistency. Extensive experiments demonstrate substantial improvements over prior methods, including in extremely sparse settings with as little as a single input image. Our code and data will be publicly available.
### Title:
          GLeVE: Graph-Guided Lesion Grounding with Proposal Verification in 3D CT
 - **Authors:** Shuo Jiang, Yuhao Hong, Chunbo Jiang, Weihong Chen, Huangwei Chen, Shenghao Zhu, Beining Wu, Mingxuan Liu, Zhu Zhu, Feiwei Qin, Min Tan, Yifei Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Grounding radiology report descriptions to 3D CT volumes is essential for verifiable clinical interpretation, yet remains challenging due to the semantic-spatial gap between free-text narratives and volumetric anatomy. Existing report-assisted and vision-language grounding methods typically rely on phrase-level alignment or dense pixel supervision, resulting in limited lesion-wise correspondence and suboptimal localization accuracy. We propose GLeVE, a graph-guided lesion grounding framework with anatomical prior verification and octree-based autoregressive refinement. GLeVE treats each lesion description as an atomic semantic unit and encodes organ attribution, attributes, and inter-lesion relations through relation-aware graph reasoning to produce discriminative lesion-wise queries. Anatomy-aware proposal generation with region-level verification enforces one-to-one text-lesion alignment, while hierarchical octree refinement progressively improves boundary delineation. Experiments on AbdomenAtlas 3.0 demonstrate consistent gains over classical multimodal foundation models and report-supervised baselines in both segmentation accuracy and lesion-level localization.
### Title:
          Summarizing Time-Varying Digital Image Correlation Strain Fields Using Sankey Diagrams
 - **Authors:** Victor Persson, Christofer Boo, Mohit Sharma, Ingrid Hotz
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC); Materials Science (cond-mat.mtrl-sci)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Digital Image Correlation (DIC) enables dense, time-resolved measurement of surface strain in deforming materials, providing insight into strain localization and failure mechanisms. However, the resulting strain fields are typically explored frame-by-frame through spatial visualizations, making global temporal patterns difficult to discern. We present a visual summarization approach that represents the evolution of high-strain regions as a single Sankey diagram constructed from superlevel sets of the von Mises equivalent strain field. By tracking connected components over time via spatial overlap, the diagram encodes the birth, persistence, merging, and disappearance of strain concentrations. Applied to four tensile test datasets with varying notch geometries, the approach compactly captures differences in deformation regimes and qualitative precursors to failure, complementing traditional spatial strain visualizations with a global temporal overview.
### Title:
          SegCompass: Exploring Interpretable Alignment with Sparse Autoencoders for Enhanced Reasoning Segmentation
 - **Authors:** Zhenyu Lu, Liupeng Li, Jinpeng Wang, Haoqian Kang, Yan Feng, Ke Chen, Yaowei Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Multimedia (cs.MM); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While large language models provide strong compositional reasoning, existing reasoning segmentation pipelines fail to transparently connect this reasoning to visual perception. Current methods, such as latent query alignment, are end-to-end yet opaque "black boxes". Conversely, textual localization readout is merely readable, not truly interpretable, often functioning as an unconstrained post-hoc step. To bridge this interpretability gap, we propose SegCompass, an end-to-end model that leverages a Sparse Autoencoder (SAE) to forge an explicit, interpretable, and differentiable alignment pathway. Given an image-instruction pair, SegCompass first generates a chain-of-thought (CoT) trace. The core of our method is an SAE that maps both the CoT and visual tokens into a shared, high-dimensional sparse concept space. A query codebook selects salient concepts from this space, which are then spatially grounded by a slot mapper into a multi-slot heatmap that guides the final mask decoder. The entire model is trained jointly, unifying reinforcement learning for the reasoning path with standard segmentation supervision. This SAE-driven interface provides a "white-box" connection that is significantly more traceable than latent queries and more coherent than textual readouts. Extensive experiments on five challenging benchmarks demonstrate that SegCompass matches or surpasses state-of-the-art performance. Crucially, our visual and quantitative analyses show a strong correlation between the quality of the learned sparse concepts and final mask accuracy, confirming that SegCompass achieves superior results through its enhanced and inspectable alignment. Code is available at this https URL.
## Keyword: transformer
### Title:
          Temporal Contrastive Transformer for Financial Crime Detection: Self-Supervised Sequence Embeddings via Predictive Contrastive Coding
 - **Authors:** Danny Butvinik (NICE Actimize), Yonit Marcus (NICE Actimize), Nitzan Tal (NICE Actimize), Gabrielle Azoulay (NICE Actimize)
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce the Temporal Contrastive Transformer (TCT), a representation learning framework designed to capture contextual temporal dynamics in sequences of financial transactions. The model is trained using a self-supervised contrastive objective to produce embeddings that encode behavioral patterns over time, with the goal of supporting downstream fraud detection tasks. We evaluate TCT in a realistic setting by using the learned embeddings as input features to a gradient boosting classifier. Experimental results show that embeddings alone achieve meaningful predictive performance (AUC 0.8644), indicating that the model captures non-trivial temporal structure. However, when combined with domain-engineered features, no measurable improvement is observed over the baseline (AUC 0.9205 vs. 0.9245), suggesting that the learned representations largely overlap with existing feature abstractions. These findings position TCT as a promising representation learning approach that captures relevant behavioral signal, while highlighting the challenges of achieving additive value over strong domain features. The results reflect an intermediate stage in the development of temporal representation learning for financial crime detection and motivate further research on model architecture, training objectives, and integration strategies. At this early stage, achieving performance comparable to a strong feature-engineered baseline is itself a meaningful outcome, indicating that learned representations approximate domain-specific features without manual engineering. While not yet production-ready, these results point to a promising direction for reducing reliance on feature engineering in financial crime detection.
### Title:
          TONIC: Token-Centric Semantic Communication for Task-Oriented Wireless Systems
 - **Authors:** Sige Liu, Kezhi Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Information Theory (cs.IT); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tokens are becoming the basic units through which foundation models represent and process information for understanding and inference. However, traditional wireless communication, centered on bit-level fidelity, faces a mismatch between what is transmitted reliably and what downstream models actually consume. This mismatch calls for a communication design that directly accounts for token-level task relevance and downstream model requirements, rather than treating all transmitted bits as equally important. In this paper, we propose TONIC, a token-centric semantic communication framework for task-oriented wireless systems. The transmitter converts each source sample into a sequence of tokens, estimates token-level task relevance, and allocates protection through utility-aware unequal error protection under a fixed channel-use budget. At the receiver, token-level confidence is used to gate unreliable decisions, turning harmful substitutions into recoverable erasures before a Transformer-based completion model restores the masked tokens for final task inference. Our framework combines transmitter-side semantic-aware protection with receiver-side confidence-aware gating in a modular and interpretable architecture, rather than relying solely on fully black-box end-to-end learning. We further establish a utility-aware Bayes-risk interpretation for the receiver-side gating rule and study its interaction with unequal protection and completion. Experimental results on image classification show that TONIC consistently outperforms separation-based schemes, the pixel-domain DeepJSCC baseline, and token-domain baselines under matched communication budgets over AWGN, Rayleigh, and Rician channels.
### Title:
          $\textit{BlockFormer}$ : Transformer-based inference from interaction maps
 - **Authors:** Eloïse Touron, Pedro L. C. Rodrigues, Julyan Arbel, Nelle Varoquaux, Michael Arbel
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Quantitative Methods (q-bio.QM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Inference from interaction maps, such as centromere identification from genome-wide chromosome conformation capture techniques -- notably Hi-C -- can be formulated as a generic inverse problem: infer a set of parameters given a map summarizing pairwise interactions between entities through blocks of variable numbers and sizes. In this work, we introduce a data-driven approach that leverages shared structure between these maps, such as global alignment between localized patterns, while handling the variability in number and size of entities arising in real-world data. Our approach relies on a transformer architecture capable of handling such variability and a custom simulator to generate abundant, yet computationally cheap synthetic data for training. Applied to the problem of centromere localization, the method accurately recovers their genomic positions across a wide range of species of various genome sizes.
### Title:
          Dropout Universality: Scaling Laws and Optimal Scheduling at the Edge-of-Chaos
 - **Authors:** Lucas Fernandez Sarmiento
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Disordered Systems and Neural Networks (cond-mat.dis-nn); Neural and Evolutionary Computing (cs.NE); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We develop a mean-field theory of dropout as a perturbation of critical signal propagation at the edge of chaos. Dropout shifts the perfect-alignment fixed point, making the depth scale for information propagation finite even at critical initialization. We derive critical and crossover scaling laws for correlation decay and establish that smooth activations and kinked, ReLU-like activations constitute distinct universality classes, with different critical exponents and a universal two-parameter scaling collapse in detuning and dropout strength. The distinction traces to the analytic structure of the correlation map: smooth activations admit a Taylor expansion near perfect alignment, while kinked activations develop a branch point with universal non-analyticity. As a corollary, the framework yields saturated dropout profiles under fixed budget; a rank-flow tie-breaker then selects front-loaded schedules, substantially reducing held-out test loss at no extra computational cost, with accuracy gains as a consistent secondary effect. We test the predictions in MLPs and Vision Transformers and discuss CNN/ResNet extensions.
### Title:
          Value-Gradient Hypothesis of RL for LLMs
 - **Authors:** Arip Asadulaev, Daniil Ognev, Karim Salta, Martin Takac
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reinforcement learning substantially improves pretrained language models, but it remains understudied why critic-free methods such as PPO and GRPO work as well as they do, and when they should provide the largest gains. We develop a value-gradient perspective of critic-free RL for LLM post-training. First, under a differentiable rollout and additive-noise parameterization, we show that the actor update is value-gradient-like in expectation: the backward pass propagates costates whose conditional expectation equals the value gradient. Second, for discrete transformer policies, we show that autodifferentiation through attention produces empirical costates that approximate this value signal, with an error controlled by the sampling gap and policy entropy. These results motivate a decomposition of RL impact into value gradient signal and reachable reward headroom, yielding a criterion for when RL should be most effective along a pretraining trajectory.
### Title:
          Same Architecture, Different Capacity: Optimizer-Induced Spectral Scaling Laws
 - **Authors:** Nandan Kumar Jha, Brandon Reagen
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scaling laws have made language-model performance predictable from model size, data, and compute, but they typically treat the optimizer as a fixed training detail. We show that this assumption misses a fundamental axis of representation scaling: how effectively the optimizer converts added FFN width into utilized spectral capacity. Using eigenspectra of feed-forward network representations, measured through soft and hard spectral-ranks, we find that \emph{the same Transformer architecture realizes markedly different spectral scaling laws when trained with different optimizers}. Holding architecture and width schedule fixed, AdamW exhibits weak hard-rank scaling ($\beta$=0.44) on rare-token (TAIL) representations where learning is known to be hardest, whereas Muon achieves linear scaling ($\beta$=1.02) in the same regimes, a $2.3\times$ increase in the scaling exponent. This difference is not reducible to validation loss: AdamW configurations can match low-rank Dion variants in perplexity, under extended training, while exhibiting sharply different spectral geometry, demonstrating that matched loss does not imply matched representation structure. Hard--soft rank asymmetry further reveals that optimizers differ not only in how much capacity is realized, but also in how that capacity is structured across eigenmodes. To disentangle optimizer effects from architectural ones, we compare against architectural interventions (e.g., attention rank and positional encoding), and find that optimizer-induced spectral shifts often exceed the architectural effects. These results suggest optimization as a first-class axis of representation scaling, motivating optimizer--architecture co-design.
### Title:
          Energy-Gated Attention: Spectral Salience as an Inductive Bias for Transformer Attention
 - **Authors:** Athanasios Zeris
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Standard transformer attention computes pairwise similarity between queries and keys, treating all tokens as equally salient regardless of their intrinsic informational content. In turbulent fluid dynamics, coherent structures -- the energetically dominant, spatially organized patterns that persist amid background chaos -- carry a disproportionate fraction of total energy and govern all transport. We propose that tokens play an analogous role in transformer attention: informationally dense positions (morphological boundaries, syntactic heads, discourse markers) concentrate spectral energy and should attract proportionally more attention than background tokens (function words, repeated patterns, low-information filler). We propose Energy-Gated Attention (EGA): a simple modification that gates value aggregation by the spectral energy of key token embeddings, computed by a single learned linear projection that discovers the dominant spectral mode of the embedding field. On TinyShakespeare, EGA achieves +0.103 validation loss improvement with only 12,480 additional parameters (<0.26% overhead) and no measurable computational cost. The result is consistent on Penn Treebank (+0.101), demonstrating dataset independence. A systematic ablation across three wavelet families (fixed Morlet, Daubechies db2/db4, and a parametric Morlet) establishes that fixed structured bases are suboptimal -- the optimal energy direction is data-adaptive and non-sinusoidal -- while identifying learned wavelet packets as a promising open direction. The learned energy threshold converges to tau ~= 0.35 independently of initialization, corresponding to the fraction (~36%) of tokens carrying above-average spectral energy in English text, a stable linguistic property consistent with the fraction of content words in running English text.
### Title:
          AdaPTwin: Adaptive Multi-Fidelity Predictive Digital Twin for Proactive Radio Resource Management in Vehicular Networks
 - **Authors:** Armin Makvandi, Md. Zoheb Hassan, Md. Jahangir Hossain
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The highly dynamic nature of vehicular networks necessitates proactive and site-specific radio resource management (RRM) to achieve ultra-reliable low-latency communications. While Network Digital Twins (NDTs) have emerged as a promising enabler, ray-tracing remains time-consuming, challenging accurate RRM under latency constraints. We propose AdaPTwin, an adaptive multi-fidelity predictive NDT for proactive and latency-aware RRM in vehicular networks. Unlike single- and multi-fidelity NDTs with fixed fidelity levels, AdaPTwin dynamically adjusts NDT fidelity based on network conditions. The framework adopts a hierarchical cloud-edge architecture, where computationally intensive fidelity selection is performed periodically in the cloud, and the proactive RRM loop operates in real-time at the edge. The edge-based proactive RRM task consists of channel prediction between vehicles and roadside units (RSUs) via trajectory forecasting and look-ahead ray tracing, followed by RRM execution. A transformer model enhanced with continual and transfer learning enables vehicular trajectory prediction while adapting to new environments and traffic patterns. Ray-tracing is performed using NVIDIA Sionna by exploiting a dynamically updated virtual environment to ensure realistic radio propagation within the NDT. Furthermore, a joint RSU beamforming and vehicle-RSU association problem is formulated to maximize proportionally fair sum-rate, and it is efficiently solved using a scalable multi-start iterative coordinate descent algorithm. Comparisons against reactive, single-fidelity, and non-adaptive predictive NDTs under realistic vehicular conditions confirm that AdaPTwin successfully adapts to diverse scenarios where other frameworks fail. Ultimately, AdaPTwin achieves up to 90% sum-rate gain and 80% outage probability reduction compared to non-adaptive NDTs, while maintaining real-time performance.
### Title:
          Auction-Consensus Algorithm with Learned Bidding Scheme for Multi-Robot Systems
 - **Authors:** Jose Rodriguez, Constantine Tarawneh, Sven Koenig, Wenjie Dong, Qi Lu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-Robot Task Allocation (MRTA) is a central challenge in decentralized multi-agent systems, where teams of robots must cooperatively assign and execute tasks under limited communication while optimizing global performance objectives. Auction-consensus algorithms, such as the Consensus-Based Bundle Algorithm (CBBA), provide scalable decentralized coordination with provable convergence, but rely on hand-crafted greedy scoring functions that often lead to suboptimal task allocations. This paper proposes a learning-enhanced auction-consensus framework in which CBBA's deterministic bidding mechanism is replaced by a neural bidding policy trained using reinforcement learning. Under a centralized training and decentralized execution paradigm, agents learn to compute task bids from partial local observations while retaining the standard auction and consensus phases for decentralized coordination. The learned bidding policy is trained using Proximal Policy Optimization with rewards shaped by proximity to globally optimal solutions obtained via mixed-integer linear programming. Multiple neural architectures are evaluated, including a Neural Additive Model, the Long Short-Term Memory (LSTM) model, and the Set Transformer Model. Experimental results across varying swarm sizes demonstrate that learned bidding policies can improve solution quality over classical CBBA while preserving decentralized execution. The proposed approach highlights the effectiveness of integrating reinforcement learning with classical distributed coordination algorithms, offering a scalable pathway toward higher-quality decentralized multi-robot task allocation.
### Title:
          RiT: Vanilla Diffusion Transformers Suffice in Representation Space
 - **Authors:** Le Zhang, Ning Mang, Aishwarya Agrawal
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Flow matching with $x$-prediction -- regressing the clean data point rather than the ambient velocity -- is known to exploit low-dimensional manifold structure effectively in pixel space \cite{li2025back}. We ask whether a pretrained representation space, while containing a low-dimensional data manifold of comparable intrinsic dimensionality, offers a distribution more favorable for flow-matching learning. Comparing pixel, SD-VAE, and DINOv2 features along four geometric axes, we find that pixel and DINOv2 share nearly identical intrinsic dimensionalities (both $\hat{d}\!\approx\!33$) yet DINOv2 exhibits $7.3\times$ higher effective rank, $35\times$ better covariance conditioning, $11.5\times$ lower excess kurtosis, and $1.7\times$ lower on-manifold interpolation error; SD-VAE latents are consistently intermediate, indicating that the advantage stems from representation-learning objectives rather than mere compression. These statistical properties render the flow-matching regression well-conditioned and remove the need for the specialized prediction heads or Riemannian transport used by prior DINOv2 diffusion methods. We propose the \emph{Representation Image Transformer} (RiT): a vanilla Diffusion Transformer trained by $x$-prediction on frozen DINOv2 features, augmented only by a dimension-aware noise schedule and joint \texttt{[CLS]}-patch modeling. On ImageNet $256{\times}256$, RiT attains FID 1.45 without guidance and 1.14 with classifier-free guidance, outperforming DiT$^\text{DH}$-XL with $19\%$ fewer parameters (676M vs.\ 839M). The resulting ODE is efficiently solvable at coarse discretizations: with classifier-free guidance, $5$ Heun steps already reach FID 2.0 and $10$ steps reach 1.25, without distillation or consistency training. Code at this https URL.
### Title:
          From TF-IDF to Transformers: A Comparative and Ensemble Approach to Sentiment Classification
 - **Authors:** Dip Biswas Shanto, Mitali Yadav, Prajwal Panth, Suresh Chandra Satapathy
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Information Retrieval (cs.IR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sentiment analysis, also referred to as opinion mining, primarily tries to extract opinion from any text-based data. In the context of movie reviews and critics, sentimental analysis can be a helpful tool to predict whether a movie review is generally positive or negative. It can be difficult for the ML models to understand the context or metaphysical sentiment accurately, as ML models rely largely on statistical word representations. The objective of this paper is to examine and categorise movie reviews into positive and negative sentiments. Diverse machine learning models are considered in doing so, and Natural Language Processing (NLP) methodologies are employed for data preprocessing and model assessment. The IMDb dataset is used. Specifically, Naive Bayes, Logistic Regression, Support Vector Machines (SVM), LightGBM, LSTM, and transformer-based models such as RoBERTa and DistilBERT were evaluated. After a lot of testing with accuracy, precision, recall, F1-score, and ROC-AUC, RoBERTa performed better than all the other models, with an accuracy of 93.02%. A soft voting ensemble that combined all the models also improved classification performance, showing that model ensembling works well for sentiment analysis.
### Title:
          Check Your LLM's Secret Dictionary! Five Lines of Code Reveal What Your LLM Learned (Including What It Shouldn't Have)
 - **Authors:** Hisashi Miyashita
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We show that singular value decomposition of the lm_head} weight matrix of a transformer-based large language model -- requiring only five lines of PyTorch and no model inference -- reveals interpretable semantic subspaces directly from the model weights. Each left singular vector identifies the vocabulary tokens most readily selected when the hidden state aligns with the corresponding singular direction; inspecting these clusters exposes the model's training data composition and curation philosophy. Analysing GPT-OSS-120B, Gemma-2-2B, and Qwen2.5-1.5B, we find that singular value spectra and vocabulary cluster structures differ systematically across models: GPT exhibits a graduated hierarchy of functionally differentiated subspaces; Gemma is dominated by pre-nineteenth-century English orthography, forming a stepwise clustering structure that may contribute to high output controllability; and Qwen exhibits broad multilingual coverage alongside subspaces whose vocabulary the authors have determined to be ethically inappropriate for direct publication. Base-instruct comparison reveals that ethically concerning subspaces originate in pretraining and are not removed by post-training alignment. We introduce the Vocabulary Cluster Score (VCS) to quantify subspace coherence, and the Weighted Projection Score (WPS) as a static glitch token detector; applying WPS to GPT-OSS-120B recovers shokubutsu-hyakka-tsu (ID 137606), a well-known glitch token widely reported in the CJK language community, without any model inference. We propose a taxonomy of root causes for problematic vocabulary content and call for lm_head} SVD analysis to be adopted as a standard pre-release safety auditing step. Our findings further suggest directions toward SVD-guided tokenizer optimisation and more controllable LLM design.
### Title:
          Rethinking Token Reduction for Diffusion Models via Output-Similarity-Awareness
 - **Authors:** Hangyeol Lee, Hyojeong Lee, Joo-Young Kim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformers (DiTs) achieve superior image generation quality but suffer from quadratic computational complexity relative to token count. While various token reduction (TR) methods have been proposed to mitigate this cost, they overlook the primary objective of generative models: minimizing recovery error, which requires reflecting output token similarity. They rely solely on input token similarity inherited from reduction-only ViT paradigms, leading to a fundamental misalignment with this objective. To bridge this gap, we propose DiTo, a novel TR paradigm that shifts the focus toward output-centric token reduction. Based on the observation that output token similarity is consistently preserved across adjacent timesteps, DiTo utilizes prior-step similarities as an effective proxy to establish token correspondences at a Matching timestep, which are then reused across multiple subsequent Reduction timesteps. To optimize this interleaved scheduling, we propose Pair Match Ratio (PMR)-guided Interval Scheduling to determine the optimal matching frequency. Furthermore, to mitigate localized approximation errors and resulting blocking artifacts caused by repeated reuse, we propose Frequency-aware Token Matching by incorporating a selection-frequency penalty. Extensive experiments demonstrate that DiTo consistently outperforms existing TR methods with 1.6-3.9 dB higher PSNR at comparable speedups, achieving a superior Pareto frontier.
### Title:
          ORBIS: Output-Guided Token Reduction with Distribution-Aware Matching for Video Diffusion Acceleration
 - **Authors:** Hangyeol Lee, Joo-Young Kim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformer (DiT) has emerged as a powerful model architecture for generating high-quality images and videos. In the case of video DiT, 3D Spatio-Temporal Attention increases token length in proportion to the number of frames, sharply increasing computational cost. Token reduction methods mitigate this cost by exploiting spatial redundancy, but existing approaches rely on inaccurate similarity estimates and lightweight matching algorithms, resulting in poor matching quality and only marginal acceleration. To overcome these limitations, we propose ORBIS, an SW-HW co-designed accelerator for video DiT. ORBIS leverages the output activation from the previous timestep to obtain more accurate inter-token similarity, substantially improving matching quality and enabling a higher token reduction ratio. We further introduce a Distribution-Aware Token Matching (DATM) algorithm that captures global token distribution and explicitly minimizes token-pair loss for additional gains. To fully hide DATM latency, we design specialized, deeply pipelined hardware and minimize its hardware cost through quantization, occupying only 2.4% of total area with negligible accuracy loss. Extensive experiments show that ORBIS achieves about 2x higher token reduction ratio than the state-of-the-art approach, AsymRnR, while delivering up to 4.5x speedup and 79.3% energy reduction compared to an NVIDIA A100 GPU.
### Title:
          SO-Mamba: State-Ownership Mamba for Unrolled MRI Reconstruction
 - **Authors:** Pengcheng Fang, Hongli Chen, Fangfang Tang, Feng Liu, Xiaohao Cai, Shanshan Shan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accelerated MRI reconstruction requires recovering missing details while preserving anatomically coherent structures across large spatial regions. State-space models such as Mamba provide efficient long-range modeling, making them attractive learned regularizers for unrolled reconstruction. However, in a data-consistency-coupled unrolled solver, different stages operate on different reconstruction iterates, where the resident carrier should preserve coherent reconstruction content across stages while stage-dependent non-resident evidence is tied to the current update. Treating these roles uniformly can place persistent resident-carrier evidence and update-dependent non-resident evidence into the same recurrent content route. We therefore propose SO-Mamba, a state-ownership Mamba regularizer that assigns reconstruction evidence within each Mamba stage to recurrent residency, state-interface access, and non-state output correction. SO-Mamba implements this ownership rule with a State-Ownership Router (SOR), which constructs a resident carrier for recurrent content and routes non-resident evidence to affine modulation of the B/C state interfaces and an output correction outlet. The resident carrier supplies the Mamba content route, while the non-resident evidence stream adapts the state interfaces and contributes through the output outlet without entering the recurrent content route. We further introduce a two-level outer-band leakage diagnostic that separates hidden-state storage from readout expression by measuring outer-band energy in the selective-scan state trajectory and the post-scan Mamba readout. Experiments on five public MRI reconstruction benchmarks spanning diverse anatomies, sampling patterns, and coil configurations show that SO-Mamba consistently improves over CNN-, Transformer-, and Mamba-based baselines with competitive computational efficiency.
### Title:
          CoRMA: Contrastive RMA for Contact-Rich Meta-Adaptation
 - **Authors:** Wentian Wang, Chutong Wen, Hongxu Ma, Wuhao Wang, Zhexiong Xue, Abdul Haseeb Nizamani, Dandi Zhou, Xinhai Sun, Jianqiao Zhu
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present CoRMA(Contrastive Robotic Motor Adaptation), a context-based meta-adaptation framework that modifies RMA for force-dominant assembly. CoRMA replaces raw simulator-parameter adaptation with a compact 6D simulator-only semantic contact context describing contact onset, lateral engagement, guided transition, contact direction, and jamming. A deployable causal Transformer adapter infers this context online from force, proprioceptive, and action histories using semantic regression and a force-regime contrastive objective. At deployment, oracle context is removed and replaced by the inferred context, enabling within-episode adaptation without demonstrations, privileged inputs, or gradient updates. We evaluate CoRMA on PegInsert, GearMesh, and NutThread in Isaac Lab / Isaac Sim~5.0 and on a real Marvin arm. Compared with FORGE baselines that achieve high simulation success but degrade substantially on hardware, CoRMA retains higher verified real success under controlled target-pose noise. These results support semantic contact inference as a reusable adaptation interface within a related assembly task family, while broader unseen-task generalization and Real2Sim calibration remain future work.
### Title:
          Accelerating Vision Foundation Models with Drop-in Depthwise Convolution
 - **Authors:** Carmelo Scribano, Mohammad Mahdi, Nedyalko Prisadnikov, Yuqian Fu, Giorgia Franchini, Danda Pani Paudel, Marko Bertogna, Luc Van Gool
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pretrained vision foundation models deliver strong performance across tasks with limited fine-tuning. However, their Vision Transformer (ViT) backbones impose high inference costs, limiting deployment on resource-constrained devices. In this work, we accelerate large-scale pretrained ViTs while preserving their feature extraction capabilities by exploiting the intrinsic convolution-like behavior of some attention heads. Specifically, we introduce an efficient depthwise convolution-based layer that serves as a drop-in replacement for these heads. Additionally, we propose simple strategies to identify which heads can be replaced and introduce a fine-tuning procedure that recovers downstream task performance. Across both image classification and segmentation tasks, our method achieves 17-20\% percent inference speedup with minimal performance degradation. We validate the approach through detailed derivations, extensive experiments, and efficiency benchmarks. The reference implementation is publicly available.
### Title:
          Short-Term-to-Long-Term Memory Transfer for Knowledge Graphs under Partial Observability
 - **Authors:** Taewoon Kim, Vincent François-Lavet, Michael Cochez
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reinforcement learning under partial observability requires deciding what information to retain, yet most memory-based approaches do not explicitly model short-term-to-long-term transfer of symbolic observations. We study this transfer process in a temporal knowledge-graph memory setting and cast it as a neuro-symbolic value-based decision problem: for each observed triple, the agent chooses whether to keep or drop it before long-term insertion. To handle variable-sized short-term buffers, we use a per-item Q-learning design with shared parameters and a practical temporal-difference update over matched items across consecutive steps. On the RoomKG benchmark at long-term memory capacity 128, learned transfer decisions outperform symbolic and neural baselines, including symbolic baselines with temporal annotations and history-based LSTM/Transformer baselines. Across transfer-policy ablations, a lightweight local short-term-only variant performs best, and step-level behavior shows that the policy keeps navigation- and query-relevant facts while discarding lower-value candidate facts, supporting explicit and interpretable memory decisions under memory constraints.
### Title:
          Balancing Uncertainty and Diversity of Samples: Leveraging Diversity of Least, High Confidence Samples for Effective Active Learning
 - **Authors:** Vipul Arya, S.H. Shabbeer Basha, Srikrishna U N, Sunainha Vijay, Snehasis Mukherjee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning models, including Convolutional Neural Networks (CNNs) and Vision Transformers (ViTs), have achieved state-of-the-art performance on various computer vision tasks such as object classification, detection, segmentation, generation, and many more. However, these models are data-hungry as they require more training data to learn millions or billions of parameters. Especially for supervised learning tasks, curating a large number of labeled samples for model training is an expensive and time-consuming task. Active Learning (AL) has been used to address this problem for many years. Existing active learning methods aim at choosing the samples for annotation from a pool of unlabeled samples that are either diverse or uncertain. Choosing such samples may hinder the model's performance as we pool based on one dimension, i.e., either diverse or uncertain. In this paper, we propose four novel hybrid sampling methods for pooling both easy and hard samples, which are also diverse. To verify the efficacy of the proposed methods, extensive experiments are conducted using high and low-confidence samples separately. We observe from our experiments that the proposed hybrid sampling method, Least Confident and Diverse (LCD), consistently performs better compared to state-of-the-art methods. It is observed that selecting uncertain and diverse instances helps the model learn more distinct features. The codes related to this study will be available at this https URL.
### Title:
          Can Transformers Learn to Verify During Backtracking Search?
 - **Authors:** Yin Jun Phua, Tony Ribeiro, Tuan Nguyen, Katsumi Inoue
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Logic in Computer Science (cs.LO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Backtracking search underlies classical constraint solvers, planners, and theorem provers. Recent transformer-based reasoning systems explore search trees over their own intermediate steps. A common training recipe fits an autoregressive next-token loss on offline solver traces. The model's input at each step is a cumulative trace of all prior decisions. The optimal continue-or-backtrack predictor depends only on the current search state, since two trajectories reaching the same state admit the same viable continuations. We show that decoder-only transformers trained on cumulative traces fail this requirement in two ways: the trace can scatter state features across many positions (scattered retrieval), and the predictor can condition on the trajectory rather than the state (history entanglement). We address scattered retrieval with localization, a trace-level fix that rewrites each decision block to expose state features locally. We address history entanglement with Selective State Attention (SSA), a fixed attention mask that enforces state-based decisions structurally without modifying training data, objective, or parameters. We focus on reactive verification, after propagation has exposed a contradiction. We test SSA on 3-SAT, graph coloring, Blocks World, and backtracking parsing. On same-state pairs that differ only in prior history, SSA emits identical decisions while a cumulative-trained causal baseline does not. Our contribution is a diagnostic of transformer behavior on serialized trajectory data, paired with a structural fix. Pretrained language models that search over their own reasoning steps may face the same failure. Our analysis opens up inference-time context clearing as a candidate way to apply the same isolation without retraining.
### Title:
          How Many Different Outputs Can a Transformer Generate?
 - **Authors:** Maxime Meyer, Mario Michelessa, Caroline Chaux, Vincent Y. F. Tan
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study how we can leverage only a handful of characteristics of a transformer's architecture to closely predict the number of different sequences it can output, both qualitatively and quantitatively. We provide an upper bound depending on the length of the prompt, which we show empirically to be tight up to a factor less than 10, across architectures and model sizes. Our analysis also provides a theoretical explanation for previously observed empirical failures of transformers on simple sequence tasks, such as copying and cramming. Formally, we prove that (i) the maximal length of accessible sequences (those that the transformer can output for some prompt) grows linearly with the prompt length, (ii) beyond a critical threshold, the proportion of accessible sequences decays exponentially with sequence length, and (iii) the linear coefficient relating prompt length to accessible sequence length admits a theoretical upper bound. Notably, these results hold even with unbounded context and computation time.
### Title:
          REACH: Hand Pose Estimation from Room Corners
 - **Authors:** Shu Nakamura, Ryo Kawahara, Genki Kinoshita, Ryosuke Hirai, Yasutomo Kawanishi, Shohei Nobuhara, Ko Nishino
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce a novel 3D hand pose estimator that can accurately recover the shape and pose of people's hands in a room from afar, typically from fixed cameras at room corners, in extremely low-resolution and frequently occluded views. Our key idea is to fully leverage hand-body coordination, its temporal progression, and multiview observations. We achieve this with a novel Transformer-based model, in which hand and body configurations are modeled through correlations between their visual features expressed as per-view tokens, and their temporal coordination is exploited in an autoregressive manner. We introduce a novel dataset, which we refer to as REACH, Room-Environment dataset Annotated with Chest cameras for Hand pose estimation, to train and test our method. REACH is a first-of-its-kind large-scale hand pose dataset that captures accurate hand movements of 50 participants across a wide variety of daily activities. In order to avoid interfering with natural movements while annotating the hands with accurate shape and pose, we leverage concealed chest cameras. Through extensive experiments, including comparative studies with existing methods, we show that our model, REACH-Net, achieves highly accurate 3D hand pose estimation from afar. These results broaden the horizon of 3D hand pose estimation, especially towards "in-the-wild" continuous human behavior analysis.
### Title:
          Direct content-based retrieval from music scores images
 - **Authors:** Noelia Luna-Barahona, Antonio Ríos-Vila, David Rizo, Jorge Calvo-Zaragoza
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The digitization of musical scores plays a crucial role in their preservation and accessibility, yet information retrieval still depends mainly on metadata searches, such as by title or composer. Content based search in music score images remains underexplored compared to text documents, despite its potential value for musicians, musicologists, and educators. This work contributes to the field by first studying which characteristics of a score are most relevant for search and by defining a systematic method to build query datasets from any annotated corpus. We also consider diverse methods for content-based search on music score images, ranging from transcription-based approaches relying on Optical Music Recognition (OMR), to a transcription-free Transformer model trained to recognize queries directly from score images, and a text-prompted Large Language Model. Our experiments evaluate these models on four corpora exhibiting diverse characteristics in terms of dataset size, image quality, and typesetting mechanisms. Overall, each method excels under different conditions: OMR-based pipelines achieve higher in-domain retrieval, whereas transcription-free models handle domain variability more effectively.
### Title:
          One LR Doesn't Fit All: Heavy-Tail Guided Layerwise Learning Rates for LLMs
 - **Authors:** Di He, Songjun Tu, Keyu Wang, Lu Yin, Shiwei Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning rate configuration is a fundamental aspect of modern deep learning. The prevailing practice of applying a uniform learning rate across all layers overlooks the structural heterogeneity of Transformers, potentially limiting their effectiveness as the backbone of Large Language Models (LLMs). In this paper, we introduce Layerwise Learning Rate (LLR), an adaptive scheme that assigns distinct learning rates to individual Transformer layers. Our method is grounded in Heavy-Tailed Self-Regularization (HT-SR) theory, which characterizes the empirical spectral density (ESD) of weight correlation matrices to quantify heavy-tailedness. Layers with weaker heavy-tailedness are assigned larger learning rates to accelerate their training, while layers with stronger heavy-tailedness receive smaller learning rates. By tailoring learning rates in this manner, LLR promotes balanced training across layers, leading to faster convergence and improved generalization. Extensive experiments across architectures (from LLaMA to GPT-nano), optimizers (AdamW and Muon), and parameter scales (60M-1B) demonstrate that LLR achieves up to 1.5x training speedup and outperforms baselines, notably raising average zero-shot accuracy from 47.09% to 49.02%. A key advantage of LLR is its low tuning overhead: it transfers nearly optimal LR settings directly from the uniform baseline. Code is available at this https URL.
### Title:
          3D LULC classification using multispectral LiDAR and deep learning: current and prospective schemes
 - **Authors:** Narges Takhtkeshha, Aldino Rizaldy, Markus Hollaus, Juha Hyyppä, Fabio Remondino, Gottfried Mandlburger
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Land Use Land Cover (LULC) classification is essential for national 3D mapping, geospatial analysis, and sustainable planning. Multispectral (MS) LiDAR provides synchronized spatial-spectral information, and deep learning (DL) enables 3D point cloud semantic segmentation; however, adoption is limited by the lack of publicly available urban and suburban MS LiDAR datasets aligned with National Mapping and Cadastral Agencies (NMCAs) classification schemes. This study addresses these gaps by introducing L1 and L2 NMCA-aligned LULC classification schemes and a new benchmark MS LiDAR dataset. We evaluate seven state-of-the-art DL models and perform spectral ablation studies at both levels of detail. Results show that Point Transformer V3 achieves the best performance, with mIoU of 79.4% (L1, 8 classes) and 58.9% (L2, 20 classes) using a dual-wavelength LiDAR system (532 nm and 1064 nm). Ablation results show that multispectral information improves performance over geometry-only inputs, with gains of 1.1 percentage points at L1 and 7.8 points at L2. These results highlight the value of LiDAR reflectance for fine-grained material discrimination and support the evolution of NMCA LULC schemes toward higher semantic detail. The Loosdorf-MSL dataset contributes a new benchmark for consistent national and international LULC mapping.
### Title:
          QuantSR+: Pushing the Limit of Quantized Image Super-Resolution Networks
 - **Authors:** Haotong Qin, Xudong Ma, Xianglong Liu, Jie Luo, Jinyang Guo, Michele Magno, Yulun Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Low-bit quantization is widely used to compress super-resolution (SR) models and reduce storage and computation costs for deployment on resource-limited devices. However, when SR models are pushed to ultra-low precision (2-4 bits), performance can drop sharply due to diminished representational capacity and the detail-sensitive nature of SR. To address these issues, we propose QuantSR+, a unified framework that improves quantization operators, network design, and training optimization, achieving better trade-offs between accuracy and efficiency than prior low-bit SR methods. QuantSR+ mainly relies on three technical contributions: (1) Redistribution-driven Bit Determination (RBD), which reshapes quantization distributions in both forward and backward passes to preserve representation fidelity; (2) Quantized Slimmable Architecture (QSA), which begins with an over-parameterized model and progressively prunes less critical blocks to meet efficiency budgets while pushing the accuracy performance; and (3) Slimming-guided Function-localized Distillation (SFD), which enforces block-aware feature alignment via a direct loss and a progressive, function-local training schedule to capture quantization effects better and speed up convergence. Extensive experiments show that QuantSR+ achieves state-of-the-art performance against both specialized quantized SR methods and generic quantization approaches. For SwinIR-S on Urban100 (x4), it improves PSNR by 0.29 dB over the 2-bit SOTA baseline. Meanwhile, it delivers strong efficiency gains at 2-bit, reducing operations by up to 87.9% and storage by 89.4%. QuantSR+ is effective for both convolutional and transformer-based SR models, indicating broad applicability.
### Title:
          Modeling Pathology-Like Behavioral Patterns in Language Models Through Behavioral Fine-Tuning
 - **Authors:** Nicola Milano, Davide Marocco
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models are increasingly used as computational tools for modeling human-like behavior. We introduce a behavioral induction framework that modifies model policies through fine-tuning on structured decision-making tasks: using synthetic datasets inspired by maladaptive behavioral patterns, including depression and paranoia, we train transformer-based language models to consistently select specific classes of actions across diverse contexts. We then test whether this behavioral optimization produces systematic changes in generative distributions. Across two architectures, fine-tuned models show stable, context-general shifts in next-token probability distributions, including increased probability assigned to negative and threat-related interpretations in open-ended language tasks. These effects generalize beyond training contexts and are detectable in qualitative completions, psychometric-style evaluations, and quantitative distributional metrics such as Jensen-Shannon divergence. Induced behavioral profiles also show partial specificity. Models optimized for different behavioral patterns exhibit dissociable response tendencies across evaluation probes, suggesting that structured behavioral training produces differentiated policy-level biases rather than generic distributional skew. We interpret these findings as evidence that consistent behavioral optimization in LLMs can generate stable behavioral and distributional patterns consistent with altered latent priors, linking action selection and language generation. More broadly, the results support a view of LLMs as policy-based systems in which behavioral constraints shape emergent representational structure, highlighting their potential as controlled testbeds for studying the relationship between behavior, interpretation, and generative language in computational models of cognition.
### Title:
          ASAP: Attention Sink Anchored Pruning
 - **Authors:** Jaehyuk Lee, Hanyoung Kim, Yanggee Kim, Donghun Lee
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformers (ViTs) face severe computational bottlenecks due to the quadratic complexity of self-attention at high resolutions. Existing token reduction methods rely on local metrics - such as single-layer attention scores - that are inherently vulnerable to the attention sink phenomenon, where uninformative tokens are paradoxically preserved over salient foreground objects. We propose ASAP (Attention Sink Anchored Pruning), a training-free framework that recasts this sink as a feature. Modeling ViT information flow as a Lazy Random Walk, ASAP identifies the sink as a dominant accumulator of probability mass. By computing the diffusion distance to the sink within the cumulative transition matrix, ASAP partitions tokens via Radial Diffusion Clustering and compresses background redundancy through Transition Weight Pooling in a single shot. Extensive experiments across image, video, and vision-language tasks demonstrate ASAP outperforms state-of-the-art methods, accelerating throughput by up to 48% while maintaining - or even exceeding - baseline accuracy.
### Title:
          Towards Explainability of SLMs by investigating Token Level Activation
 - **Authors:** Sayantani Ghosh, Rajashik Datta, Amit Kumar Das, Amlan Chakrabarti
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based language models such as BERT having 110M+ parameters have revolutionized natural language understanding, yet their internal mechanisms remain largely opaque to researchers and practitioners. Traditional attention-based interpretability methods often emphasize structurally important but semantically weak tokens such as punctuation marks rather than meaningful semantic relationships. This work introduces a lightweight and model-agnostic framework for quantifying token-level representational importance using hidden-state activation strengths at Layer 8 of BERT. The proposed Activation Flow Network (AFN) framework computes Token Activation Strength using the L2 norm of Layer-8 hidden representations, enabling direct ranking of semantically salient tokens. The study further introduces a threshold-based activation bucket formulation that partitions tokens into HIGH-activation and LOW-activation groups using an empirical upper-quartile activation boundary. Experimental observations demonstrate that semantically meaningful content words consistently occupy the HIGH-activation bucket and dominate representational activation shifts, while structurally supportive tokens contribute comparatively less. The results suggest that Layer 8 acts as a critical semantic consolidation zone balancing structural and semantic information processing. By revealing how activation magnitudes concentrate around semantically informative tokens, this work provides an interpretable and computationally efficient alternative to attentioncentric analysis, contributing toward transforming BERT from a "black box" into a more transparent "glass box" model for natural language understanding.
### Title:
          FastTab: A Fast Table Recognizer with a Tiny Recursive Module and 1D Transformers
 - **Authors:** Laziz Hamdi, Amine Tamasna, Pascal Boisson, Thierry Paquet
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Table structure recognition (TSR) requires both table-level coherence (row/column counts, headers, spanning cells) and precise separator localization. We introduce FastTab, a grid-centric TSR model that avoids autoregressive HTML decoding by combining (i) a lightweight Tiny Recursive Module (TRM) for global reasoning and (ii) axial 1D Transformer encoders that capture long-range dependencies along rows and columns. The model predicts row/column counts, header rows, and separators to construct a grid, then infers rowspan/colspan using ROI-aligned cell features. Across four benchmarks (PubTabNet, FinTabNet, PubTables-1M, and SciTSR), FastTab achieves competitive structure recovery performance while operating at low-latency inference. We further study robustness under pixel-level anonymisation and show an extension to curved separators for camera-captured documents. The source code will be made publicly available at this https URL .
### Title:
          From Correlation to Cause: A Five-Stage Methodology for Feature Analysis in Transformer Language Models
 - **Authors:** Caleb Munigety
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose a five-stage methodology for causal feature analysis in transformer language models (probe design, feature extraction, causal validation, robustness testing, and deployment integration) and demonstrate it end-to-end on GPT-2 small performing the Indirect Object Identification (IOI) task. Activation patching recovers the canonical IOI circuit (layer-9 head 9 alone gives recovery +1.02). A sparse autoencoder recovers per-name selective features with effect sizes of 30 to 50 activation units. Causal validation finds these features specifically but only partially causal: ablating fifteen of them leaves the model accurate on 98% of prompts. Two NLA-inspired evaluations strengthen this picture: the fifteen selective features explain only 31% of activation variance versus the SAE's 99.7%, and selectivity ratio anticorrelates with causal force (r = -0.56). Robustness testing under three distribution shifts finds that the circuit transfers cleanly but feature ablation effects degrade substantially, exposing a gap between detection robustness and causal robustness. A cost-based deployment evaluation (assumed $50/FN, $0.42/FP, 2% error rate) finds an optimal monitor configuration yielding $8.96 per 1000 queries against a $1000 baseline, a 99.1% saving. Optimal composition strategy varies with cost ratio and base rate. The conjunction of stages produces findings no single stage would.
### Title:
          Lost in Tokenization: Fundamental Trade-offs in Graph Tokenization for Transformers
 - **Authors:** Maya Bechler-Speicher, Gilad Yehudai, Gil Harari, Clayton Sanford, Amir Globerson, Joan Bruna
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers have become a central architecture for graph learning, but their application to graphs requires first choosing a tokenization: a graph-to-token map that determines which structural information is exposed at the input. In this work, we show that this choice is a fundamental component of transformer expressivity. We examine three tokenizations that serve as building blocks for many existing graph tokenizations: spectral, random-walk, and adjacency tokenizations. We prove that different tokenizations induce distinct depth regimes: the same graph computation may be realizable by a shallow transformer under one tokenization, while requiring substantially larger depth under another. For example, we prove that random-walk tokenization is lossy for any walk length, making it impossible in general to recover the graph from it, and that while spectral tokenization is lossless, it is ill-conditioned for local tasks. We further show that although both random-walk and spectral tokenizations are derived from adjacency information, it is impossible for a limited-depth transformer to convert between tokenization families in general. In particular, we establish lower bounds and impossibility results showing that unfavorable tokenizations may preclude the efficient recovery of more suitable structural representations. Finally, we complement our theory with controlled experiments on synthetic and real-world tasks, validating the predicted separations and showing that different tasks favor different structural views, and combining complementary tokenizations allows the transformer to leverage distinct signals from each representation.
### Title:
          Winner-Take-All bottlenecks enforce disentangled symbolic representations in multi-task learning
 - **Authors:** Julian Gutheil (1), Simon Hitzginger (1), Robert Legenstein (1) ((1) Graz University of Technology)
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Winner-take-all (WTA) networks constitute a central circuit motif in cortical networks of the brain. In addition, WTA-like activations are abundant in modern deep learning models in the form of the softmax activation for example in attention layers of transformers. While their role in the extraction of latent factors has been studied for relatively simple generative models, their role in the context of highly non-linearly entangled latent factors has remained elusive. In this article, we show that a WTA bottleneck within a deep neural network can enforce under certain well-defined conditions the extraction of categorical latent factors of the data in a multi-task learning setup. In particular, we prove that the representation that emerges in the WTA bottleneck is highly symbolic, where a single neuron or a population of neurons encodes the presence of a single abstract feature such as a specific object, color, or position. We furthermore show empirically on two datasets, that this also holds for architectures and setups that do not fully comply with the assumptions of our theorem and demonstrate the advantages of the acquired symbolic representation for generalization. Our proposed model provides insights into the generalization capabilities of deep neural networks with WTA-like components and may serve as an interface between symbolic and subsymbolic AI systems.
### Title:
          Structured-Sparse Attention for Entity Tracking with Subquadratic Sequence Complexity
 - **Authors:** Hangyue Zhao, Paul Caillon, Erwan Fagnou, Alexandre Allauzen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Entity tracking requires maintaining and updating latent states for entities and attributes over long sequences. Recent task-specific attention operators can compress deep Transformer stacks into a few layers by performing multi-hop state propagation within a single layer, but their dense evaluation remains expensive. We show that in this setting, learned attention is strongly structured: most mass concentrates in local block-diagonal neighborhoods with a light cross-block residue. Exploiting this, we derive a blockwise evaluation of a resolvent-style operator that keeps within-block interactions exact and routes cross-block interactions through a reduced system. The resulting evaluation is subquadratic in sequence length $O(n^{4/3}d)$ (and $O(n^{7/3})$ when $d\approx n$). On controlled tracking benchmarks, our method matches the dense operator's accuracy while reducing wall-clock time by $12-29\%$ under a standardized measurement protocol, and is up to $2.4 \times$ faster than a compact dense Transformer at comparable exact-match accuracy. We further provide ablations over block size and model capacity, and identify a limitation: performance collapses when the number of simultaneously evolving properties exceeds the number of attention heads.
### Title:
          Represented Is Not Computed: A Causal Test of Candidate Algorithmic Intermediates in a Transformer
 - **Authors:** Ishita Darade, Sushrut Thorat
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Structured prompts require integrating components according to task-relevant relations. How a network implements this integration is often hard to judge in language or vision, where those relations are rarely specified precisely enough to define a candidate internal algorithm. Arithmetic offers a cleaner setting. We study a Transformer trained on base-digit extraction: given $N$, $B$, and $D$, it must report the coefficient of $B^D$ in the base-$B$ expansion of $N$. The closed-form solution, $\lfloor N/B^D \rfloor \bmod B$, provides explicit candidate algorithmic intermediates. Across three seeds, the model reaches 99.83% exact-answer accuracy on held-out number-base intersections, establishing reliable task competence. Linear probes decode the intermediates, making staged arithmetic computation plausible. Causal tests then separate representation from use: within the localized route from the stream with $D$ as input to the output positions, behavior depends on early $D$-selective communication, independent of $N$ and $B$. Relatedly, a sparse circuit search finds mostly separate $N$, $B$, and $D$ routes that combine late rather than the staged route suggested by the probes. Thus, the model represents the intermediates that make the closed-form solution plausible, but the identified localized causal route does not transmit them to the output stream. This case shows that probe-based conclusions can diverge sharply from causal observations, even when explicit algorithmic hypotheses are available.
### Title:
          MOTOR: A Multimodal Dataset for Two-Wheeler Rider Behavior Understanding
 - **Authors:** Varun A. Paturkar, Shankar Gangisetty, C.V. Jawahar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Two-wheelers account for a disproportionately high share of road fatalities in the Global South. Research on two-wheeler rider behavior, however, lags far behind four-wheelers, where multimodal datasets have driven major advances in Advanced Driver Assistance Systems (ADAS). To address this gap, we present the MOtorized TwO-wheeler Rider (MOTOR) dataset, the first large-scale, multi-view, multimodal resource dedicated to two-wheelers in dense, unstructured traffic. MOTOR comprises 1,629 sequences (25+ hours of video data) collected from 16 riders and integrates synchronized front, rear, and helmet videos, rider eye-gaze from wearable trackers, on-road audio, and telemetry (GPS, accelerometer, gyroscope). Rich annotations capture traffic context, rider state, 12 riding maneuvers spanning conventional and unconventional behaviors, and legality labels (Legal, Illegal, Unspecified). We benchmark rider behavior recognition and maneuver legality classification using state-of-the-art video action recognition backbones (CNN and Transformer-based), extended with multimodal fusion, and find that combining RGB, gaze, and telemetry consistently yields the best performance. MOTOR thus provides a unique foundation for advancing safety-critical understanding of two-wheeler riding. It offers the research community a benchmark to develop and evaluate models for behavior analysis, legality-aware prediction, and intelligent transportation systems. Dataset and code is available at https: //varuniiith.this http URL
### Title:
          Beyond Temperature: Hyperfitting as a Late-Stage Geometric Expansion
 - **Authors:** Meimingwei Li, Yuanhao Ding, Esteban Garces Arias, Christian Heumann
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent work has identified a counterintuitive phenomenon termed "Hyperfitting", where fine-tuning Large Language Models (LLMs) to near-zero training loss on small datasets surprisingly enhances open-ended generation quality and mitigates repetition in greedy decoding. While effective, the underlying mechanism remains poorly understood, with the extremely low-entropy output distributions suggesting a potential equivalence to simple temperature scaling. In this work, we demonstrate that this phenomenon is fundamentally distinct from distribution sharpening; entropy-matched control experiments reveal that temperature scaling fails to replicate the diversity gains of hyperfitting. Furthermore, we falsify the hypothesis of static vocabulary reweighting, showing through ablation studies that hyperfitting relies on a dynamic, context-dependent rank reordering mechanism. Layer-wise analysis localizes this effect to a "Terminal Expansion" in the final transformer block, where a substantial geometric expansion of the feature space (Delta Dim approx +80.8) facilitates the promotion of deep-tail tokens. Additionally, we introduce Late-Stage LoRA, a targeted fine-tuning strategy that updates only the final 5 layers, yielding robust generation with minimal parameter updates
### Title:
          H-Flow: Self-supervised Human Scene Flow via Physics-inspired Joint Multi-modal Learning
 - **Authors:** Zhanbo Huang, Xiaoming Liu, Yu Kong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Parametric human models capture global pose but cannot represent the non-rigid surface dynamics of clothing and soft tissue. Generic scene flow estimates dense motion but breaks down on articulated bodies, where pixel-level supervision is also intractable to acquire. We introduce H-Flow, a dense human scene flow that captures both skeletal kinematics and surface deformation. A unified multi-head transformer estimates flow from monocular video, jointly predicting pose and depth as companion outputs. The challenge lies in the lack of supervision. In place of unattainable labels, we anchor the network in the physics of human motion, encoding geometric, structural, and biomechanical priors as cross-modal training objectives. We further introduce DynAct4D, a high-fidelity synthetic benchmark providing dense flow annotations across diverse subjects, garments, and motions. On standard benchmarks, H-Flow outperforms scene-flow and parametric baselines, and generalizes zero-shot to in-the-wild video. Code, models, and the DynAct4D benchmark will be released upon publication
### Title:
          SEGA: Spectral-Energy Guided Attention for Resolution Extrapolation in Diffusion Transformers
 - **Authors:** Javad Rajabi, Kimia Shaban, Koorosh Roohi, David B. Lindell, Babak Taati
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion transformers (DiTs) have emerged as a dominant architecture for text-to-image generation, yet their performance drops when generating at resolutions beyond their training range. Existing training-free approaches mitigate this by modifying inference-time attention behavior, often through Rotary Position Embeddings (RoPE) extrapolation combined with attention scaling. However, these strategies apply a uniform and content-agnostic scaling across RoPE components with distinct frequency characteristics, inducing a trade-off between preserving global structure and recovering fine detail. We introduce SEGA, a training-free method that dynamically scales attention across RoPE components according to the latent's spatial-frequency structure at each denoising step. This adaptive scaling improves both structural coherence and fine-detail fidelity. Experiments show that SEGA consistently improves high-resolution synthesis across multiple target resolutions, outperforming state-of-the-art training-free baselines.
### Title:
          Slimmable ConvNeXt: Width-Adaptive Inference for Efficient Multi-Device Deployment
 - **Authors:** Janek Haberer, Jon Eike Wilhelm, Olaf Landsiedel
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deploying vision models across devices with varying resource constraints, or even on a single device where available compute fluctuates due to battery state, thermal throttling, or latency deadlines, typically requires training and maintaining separate models. Width-adaptive inference addresses this by training a single set of shared weights containing multiple nested subnetworks of increasing capacity, but prior CNN-based approaches required switchable batch normalization, while recent scalable methods have focused on Vision Transformers. We present Slimmable ConvNeXt, which shows that ConvNeXt's modern design, specifically LayerNorm and inverted bottlenecks, makes it particularly suited for channel-width slimming, eliminating the normalization overhead of classical slimmable networks and producing a simpler training pipeline than both prior CNN and ViT approaches. On ImageNet-1k, Slimmable ConvNeXt-T with 3 subnetworks achieves 80.8% top-1 accuracy at 4.5 GMACs and 77.4% at 1.2 GMACs, trained from scratch for 600 epochs. At comparable compute, this exceeds HydraViT's 6-head subnetwork (78.4% at 4.6 GMACs) by 2.4 percentage points and its 3-head configuration (73.0% at 1.3 GMACs) by 4.4 percentage points, while also outperforming MatFormer-S (78.6%) and SortedNet-S (78.2%) at the same GMACs. Scaling to Slimmable ConvNeXt-B further improves maximum accuracy to 82.8% at 15.35 GMACs.
### Title:
          MambaGaze: Bidirectional Mamba with Explicit Missing Data Modeling for Cognitive Load Assessment from Eye-Gaze Tracking Data
 - **Authors:** Amir Mousavi, Mohammad Sadegh Sirjani, Erfan Nourbakhsh, Mimi Xie, Rocky Slavin, Leslie Neely, John Davis, John Quarles
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-time cognitive load assessment from eye-tracking signals could potentially enable adaptive human-centered-AI such as safety-critical applications such as driver vigilance monitoring or automated flight deck assistance, yet two challenges persist: handling frequent data missingness from blinks and tracking failures, and efficiently modeling long-range temporal dependencies. We propose MambaGaze, a framework that addresses these challenges through 1) XMD encoding, which augments raw features with observation masks and time-deltas to explicitly model data uncertainty, and 2) bidirectional Mamba-2, which captures temporal dependencies with linear computational complexity. Experiments on CLARE and CL-Drive datasets under leave-one-subject-out evaluation show that MambaGaze achieves 76.8% and 73.1% accuracy, respectively, outperforming CNN, Transformer, ResNet, and VGG baselines by 4-12 percentage points. Edge deployment benchmarks on NVIDIA Jetson platforms demonstrate real-time inference at 43-68 FPS with power consumption below 7.5W, confirming feasibility for wearable cognitive load monitoring.
### Title:
          LCGuard: Latent Communication Guard for Safe KV Sharing in Multi-Agent Systems
 - **Authors:** Sadia Asif, Mohammad Mohammadi Amiri, Momin Abbas, Prasanna Sattigeri, Karthikeyan Natesan Ramamurthy
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Emerging Technologies (cs.ET); Machine Learning (cs.LG); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language model (LLM)-based multi-agent systems increasingly rely on intermediate communication to coordinate complex tasks. While most existing systems communicate through natural language, recent work shows that latent communication, particularly through transformer key-value (KV) caches, can improve efficiency and preserve richer task-relevant information. However, KV caches also encode contextual inputs, intermediate reasoning states, and agent-specific information, creating an opaque channel through which sensitive content may propagate across agents without explicit textual disclosure. To address this, we introduce \textbf{LCGuard} (Latent Communication Guard), a framework for safe KV-based latent communication in multi-agent LLM systems. LCGuard treats shared KV caches as latent working memory and learns representation-level transformations before cache artifacts are transmitted across agents. We formalize representation-level sensitive information leakage operationally through reconstruction: a shared cache artifact is unsafe if an adversarial decoder can recover agent-specific sensitive inputs from it. This leads to an adversarial training formulation in which the adversary learns to reconstruct sensitive inputs, while LCGuard learns transformations that preserve task-relevant semantics and reduce reconstructable information. Empirical evaluations across multiple model families and multi-agent benchmarks show that LCGuard consistently reduces reconstruction-based leakage and attack success rates while maintaining competitive task performance compared to standard KV-sharing baselines.
## Keyword: autonomous driving
### Title:
          FRED: A Multi-Modal Autonomous Driving Dataset for Flooded Road Environments
 - **Authors:** Connor Malone, Sebastien Demmel, Sebastien Glaser
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Flooded Road Environments Dataset (FRED) is, to our knowledge, the first multi-modal autonomous driving dataset specifically targeting the collection of data from scenarios involving water hazards on the road. The dataset contains images from a 2.3 MP FLIR Blackfly USB3 camera, 64-beam 360$^\circ$ point clouds from an Ouster OS1-64 LiDAR, and data from an iXblue ATLANS-C IMU corrected by a Geoflex RTK GNSS, from five separate locations captured both during and after flooding events. The data has been released in two formats: a KITTI-style format for easy integration with existing data tools, and the RTMaps format for direct replay of the vehicle's data capture. We provide semantic labels to enable the training and evaluation of both single-sensor and sensor-fusion methods for water hazard detection. Position and velocity, as well as data captured under dry conditions, are provided to enable the development of location-based detection methods that may incorporate maps, and to evaluate other tasks such as localisation and SLAM.
### Title:
          LVDrive: Latent Visual Representation Enhanced Vision-Language-Action Autonomous Driving Model
 - **Authors:** Xiaodong Mei, Diankun Zhang, Hongwei Xie, Guang Chen, Hangjun Ye, Dan Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models have emerged as a promising framework for end-to-end autonomous driving. However, existing VLAs typically rely on sparse action supervision, which underutilizes their powerful scene understanding and reasoning capabilities. Recent attempts to incorporate dense visual supervision via world modeling often overemphasize pixel-level image reconstruction, neglecting semantically meaningful scene representation learning. In this work, we propose LVDrive, a Latent Visual representation enhanced VLA framework for autonomous driving. LVDrive introduces a future scene prediction task into the VLA paradigm, where future representations are learned entirely in a high-level latent space under auxiliary supervision from a pretrained vision backbone. Departing from inefficient autoregressive generation, we jointly model future scene and motion prediction within a unified embedding space, processed in a single forward pass to conduct the future-aware reasoning. We further design a two-stage trajectory decoding strategy that explicitly leverages the learned latent future representations to refine trajectory generation. Extensive experiments on the challenging Bench2Drive benchmark demonstrate that LVDrive achieves significant improvements in closed-loop driving performance, outperforming both action supervised methods and image-reconstruction-based world model approaches.
### Title:
          Learning A Unified Risk Map for Autonomous Driving in Partially Observable Environments
 - **Authors:** Jie Jia, Yaofeng Su, Zeyu Bao, Yun Hong, Bingzhao Gao, Zhongxue Gan, Wenchao Ding
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Occlusion-aware prediction remains a critical challenge in autonomous driving due to the inherent uncertainty of unobserved regions. Existing approaches either overestimate risk based on reachable states or struggle to predict accurate trajectories under high occlusion uncertainty. To address these limitations, we propose a unified risk map modeling and learning framework for partially observable environments. Our method integrates traffic flow risk and collision risk through spatiotemporal modeling, enabling fine-grained assessment of occlusion-induced hazards. To address the scarcity of scenarios involving occluded interactions, we introduce a diffusion-based scenario generation framework that produces realistic yet adversarial scenarios. We integrate the modeling and learning of a unified risk map into a framework that supports risk-aware planning under partial observability. Experiments on the Waymo Open Motion Dataset show that our method significantly outperforms the state-of-the-art occlusion-aware baseline, improving minimum time-to-collision by 0.78 times and average time-to-collision by 1.67 times. The proposed framework offers a comprehensive and practical solution for risk-aware planning in partially observable environments.
### Title:
          Diffusion-guided Generalizable Enhancer for Urban Scene Reconstruction
 - **Authors:** Henry Che, Jingkang Wang, Yun Chen, Ze Yang, Sivabalan Manivasagam, Raquel Urtasun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Urban scene reconstruction from real-world observations has emerged as a powerful tool for self-driving development and testing. While current neural rendering approaches achieve high-fidelity rendering along the recorded trajectories, their quality degrades significantly under large viewpoint shifts, limiting the applicability for closed-loop simulation. Recent works have shown promising results in using diffusion models to enhance quality at these challenging viewpoints and distill improvements back into 3D representations. However, they often require costly per-scene optimization, and the distilled representations remain fragile and fail to generalize beyond limited synthesized views. To address these limitations, we propose GenRe, a novel diffusion-guided generalizable enhancer for urban scene reconstruction. GenRe takes as input any pretrained 3D Gaussian representation and fixes the deficiencies within a few minutes. By learning to distill generative priors across diverse scenes, GenRe produces robust and high-fidelity representation efficiently that generalizes reliably to challenging unseen viewpoints (e.g., lane change). Experiments show that GenRe outperforms existing methods in both quality and efficiency and benefits various downstream tasks, enabling robust and scalable sensor simulation for autonomous driving.
### Title:
          Making the Discrete Continuous: Synthetic RAW Augmentations for Fine-Grained Evaluation of Person Detection Performance in Low Light
 - **Authors:** Valeria Pais, Malena Mendilaharzu, Daniele Faccio, Luis Oala, Christoph Clausen, Bruno Sanguinetti
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Optics (physics.optics)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-world deployment of AI vision models is both fueled and limited by the data available for training and testing. Real datasets are sparse and uneven: long-tailed or unbalanced distributions hinder generalization, and the low number of samples in low density regions makes it hard to run evaluations. Synthetic data can fill these gaps, providing us with a way to sample the input space more continuously and improve data coverage for benchmarks. Focusing on the autonomous driving safety-critical case of pedestrian detection in the dark, we show how synthetic low-light samples can be used to better characterize the performance of a state-of-the-art object detection model as a function of the scene illumination. We use a synthetic RAW image augmentation technique to generate low-light samples that match the noise model of the camera sensor. Performance metrics on real and synthetic low-light data are similar, indicating that the AI model finds it hard to distinguish between them.
### Title:
          Beyond Chamfer Distance: Granular Order-aware Evaluation Metric For Online Mapping
 - **Authors:** Chouaib Bencheikh Lehocine, Adam Lilja, Junsheng Fu, Lars Hammarstrand
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Online map estimation is a crucial component of autonomous driving systems that reduces the reliance on costly high-definition maps. State-of-the-art (SOTA) methods commonly predict map elements as ordered sequences of points that form polylines and polygons. The evaluation of these methods relies predominantly on mean average precision (mAP) based on thresholded Chamfer distance (CD). This framework lacks sensitivity to point ordering and provides limited granularity in assessing geometric quality, making it difficult to distinguish which methods truly excel over others. In this work, we address these limitations on two fronts. For the single-instance similarity measure, we introduce sequence optimal sub-pattern assignment (SOSPA), an order-aware metric that enables fine-grained evaluation of individual geometries while satisfying all metric axioms. For the multi-instance evaluation framework, we propose polyline localisation and detection (PLD), a soft metric that jointly captures detection quality and geometric accuracy, replacing the hard thresholding of mAP with a principled soft assignment. Through evaluations on nuScenes, we demonstrate that PLD effectively ranks SOTA online mapping methods (MapTRv2, StreamMapNet, MapTracker) while providing a decomposed error analysis. This analysis identifies detection capability as the dominant bottleneck in current methods, revealing a performance trend that mAP fails to capture. Code for evaluation using our metrics will be released.
### Title:
          Branch-Stochastic Model Predictive Control for Motion Planning under Multi-Modal Uncertainty with Scenario Clustering
 - **Authors:** Zekun Xing, Ramkrishna Chaudhari, Marion Leibold, Dirk Wollherr, Martin Buss
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Motion planning for autonomous driving must account for multi-modal uncertainty in both the intentions and trajectories of surrounding vehicles. Handling uncertainty in a worst-case manner guarantees robustness but often leads to excessive conservatism. Stochastic Model Predictive Control (SMPC) reduces trajectory-level conservatism through chance constraints, yet remains conservative with respect to intention uncertainty since constraints must hold across all intentions. We present a novel combination of SMPC and the branching structure, enabling the planner to generate distinct trajectories for different possible intentions while maintaining safety under trajectory uncertainty. A novel scenario clustering is proposed to merge prediction scenarios based on high-level decision similarity, thereby ensuring real-time tractability. Furthermore, an adaptive branching-time computation postpones commitment to separate plans until intention uncertainty is sufficiently reduced. Simulation studies in challenging highway scenarios demonstrate that the proposed method improves safety, reduces conservatism, and achieves real-time computational performance.
### Title:
          Sensor2Sensor: Cross-Embodiment Sensor Conversion for Autonomous Driving
 - **Authors:** Jiahao Wang, Bo Sun, Yijing Bai, Vincent Casser, Songyou Peng, Zehao Zhu, Meng-Li Shih, Xander Masotto, Shih-Yang Su, Kanaad V Parvate, Tiancheng Ge, Linn Bieske, Dragomir Anguelov, Mingxing Tan, Chiyu Max Jiang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust training and validation of Autonomous Driving Systems (ADS) require massive, diverse datasets. Proprietary data collected by Autonomous Vehicle (AV) fleets, while high-fidelity, are limited in scale, diversity of sensor configurations, as well as geographic and long-tail-behavioral coverage. In contrast, in-the-wild data from sources like dashcams offers immense scale and diversity, capturing critical long-tail scenarios and novel environments. However, this unstructured, in-the-wild video data is incompatible with ADS expecting structured, multi-modal sensor inputs for validation and training. To bridge this data gap, we propose Sensor2Sensor, a novel generative modeling paradigm that translates in-the-wild monocular dashcam videos into a high-fidelity, multi-modal sensor suite (AV logs) comprising multi-view camera images and LiDAR point clouds. A core challenge is the lack of paired training data. We address this by converting real AV logs into dashcam-style videos via 4D Gaussian Splatting (4DGS) reconstruction and novel-view rendering. Sensor2Sensor then utilizes a diffusion architecture to perform the generative conversion. We perform comprehensive quantitative evaluations on the fidelity and realism of the generated sensor data. We demonstrate Sensor2Sensor's practical utility by converting challenging in-the-wild internet and dashcam footage into realistic, multi-modal data formats, further unlocking vast external data sources for AV development.
