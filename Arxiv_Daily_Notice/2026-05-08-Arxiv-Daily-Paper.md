# Showing new listings for Friday, 8 May 2026
## Keyword: SLAM
### Title:
          SLAM: Structural Linguistic Activation Marking for Language Models
 - **Authors:** Fabrice Harel-Canada, Amit Sahai
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLM watermarks must be detectable without compromising text quality, yet most existing schemes bias the next-token distribution and pay for detection with measurable quality loss. We present SLAM (Structural Linguistic Activation Marking), a novel white-box watermarking scheme that sidesteps this cost by writing the mark into structural geometry rather than token frequencies: sparse autoencoders identify residual-stream directions encoding linguistic structure (e.g., voice, tense, clause order), and we causally steer those directions at generation time, leaving lexical sampling and semantics unconstrained. On Gemma-2 2B and 9B, SLAM achieves 100% detection accuracy with a quality cost of only 1-2 reward points - compared to 7.5-11.5 for KGW, EWD, and Unigram - with naturalness and diversity preserved at near-unwatermarked levels across both models. The trade-off is a complementary robustness profile: SLAM resists word-level edits but is vulnerable to paraphrase that restructures syntax (at a quality cost), the converse of token-distribution methods.
### Title:
          GA3T: A Ground-Aerial Terrain Traversability Dataset for Heterogeneous Robot Teams in Unstructured Environments
 - **Authors:** Siwei Cai, Knut Peterson, Quan Tran, Christian Ricks, Dhanush Parthasarathy, Amir Kaidarov, Neil Deshpande, Sukaina Najm, David Han, Lifeng Zhou
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Heterogeneous air-ground robot teams combine complementary sensing modalities, mobility characteristics, and spatial viewpoints that can significantly enhance perception in complex outdoor environments. However, progress in multi-robot collaborative perception has been constrained by the lack of real-world datasets featuring overlapping multi-modal observations from platforms operating in unstructured terrain. We present GA3T (Ground-Aerial Team for Terrain Traversal), a real-world multi-robot collaborative perception dataset collected using a Clearpath Husky UGV and an Autel EVO~II UAV across diverse unstructured environments, including forest trails, rocky paths, muddy terrain, snow piles, and grass-covered fields. The ground platform provides 3D LiDAR, stereo camera, IMU, and GPS data, while the aerial platform contributes RGB imagery, thermal/infrared observations, and GPS from a complementary overhead viewpoint, allowing for rich cross-modal and cross-view perception. The dataset is collected in 4 unique environments, with over 13,000 synchronized frames across approximately 29 minutes of operation, and includes both SAM~3-based zero-shot segmentation and over 8,000 manually labeled images. A unique aspect of the dataset is its early-spring collection period, during which sparse tree canopies allow the aerial robot to partially observe the ground robot and terrain through the trees, allowing for occlusion-aware collaborative perception. Unlike prior multi-robot datasets that focus on SLAM or simulated cooperative driving, GA3T is specifically designed to support research on cross-view perception, air-ground viewpoint fusion, traversability estimation, and collaborative scene understanding in real off-road environments.
## Keyword: odometry
There is no result 
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Query2Uncertainty: Robust Uncertainty Quantification and Calibration for 3D Object Detection under Distribution Shift
 - **Authors:** Till Beemelmanns, Alexey Nekrasov, Stefan Vilceanu, Jonas Steinhaus, Timo Woopen, Bastian Leibe, Lutz Eckstein
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable uncertainty estimation for 3D object detection is critical for deploying safe autonomous systems, yet modern detectors remain poorly calibrated, especially under distribution shifts. Although post-hoc calibration methods address this issue and provide improved calibration for in-distribution tests, they fail to adapt in distribution-shifted scenarios. In this work, we address this issue and introduce a density-aware calibration method that couples post-hoc calibrators with the feature density of latent object queries from DETR-style 3D object detectors. These queries form a compact, location and class-aware feature, ideal for density estimation, allowing our approach to adjust model confidences in distribution-shift scenarios. By fitting a density estimator on these query features, our approach jointly recalibrates both classification and bounding box regression uncertainties. On both a multi-view camera and LiDAR-based detector, our approach consistently outperforms standard post-hoc methods in both in-distribution and distribution-shifted scenarios. Code available this https URL .
### Title:
          Generating Roadside LiDAR Datasets from Vehicle-Side Datasets via Novel View Synthesis
 - **Authors:** Yuhan Xia, Runxin Zhao, Hanyang Zhuang, Chunxiang Wang, Ming Yang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Intelligent Transportation Systems (ITS) require reliable environmental perception to support safe and efficient transportation. With the rapid development of Vehicle-to-everything (V2X), roadside perception has become an effective means to extend sensing coverage and improve traffic safety. However, the scarcity of large-scale annotated roadside LiDAR datasets poses a major challenge for training high-performance roadside perception models. In this paper, we introduce Vehicle-to-Roadside LiDAR Synthesis (VRS), a data synthesis framework that generates labeled roadside LiDAR datasets from vehicle-side datasets via LiDAR novel view synthesis. To mitigate the vehicle-to-roadside domain gap, VRS employs vehicle point cloud completion to compensate for missing geometry in vehicle-side observations, and introduces an occupancy-based visibility constraint to handle large viewpoint changes during cross-view rendering. The proposed framework enables flexible multi-view rendering for scalable roadside data generation. Extensive experiments on roadside 3D object detection demonstrate that the synthesized data effectively complements real roadside data, mitigates the limitations of limited real-world roadside data, and improves generalization to unseen roadside viewpoints.
### Title:
          GA3T: A Ground-Aerial Terrain Traversability Dataset for Heterogeneous Robot Teams in Unstructured Environments
 - **Authors:** Siwei Cai, Knut Peterson, Quan Tran, Christian Ricks, Dhanush Parthasarathy, Amir Kaidarov, Neil Deshpande, Sukaina Najm, David Han, Lifeng Zhou
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Heterogeneous air-ground robot teams combine complementary sensing modalities, mobility characteristics, and spatial viewpoints that can significantly enhance perception in complex outdoor environments. However, progress in multi-robot collaborative perception has been constrained by the lack of real-world datasets featuring overlapping multi-modal observations from platforms operating in unstructured terrain. We present GA3T (Ground-Aerial Team for Terrain Traversal), a real-world multi-robot collaborative perception dataset collected using a Clearpath Husky UGV and an Autel EVO~II UAV across diverse unstructured environments, including forest trails, rocky paths, muddy terrain, snow piles, and grass-covered fields. The ground platform provides 3D LiDAR, stereo camera, IMU, and GPS data, while the aerial platform contributes RGB imagery, thermal/infrared observations, and GPS from a complementary overhead viewpoint, allowing for rich cross-modal and cross-view perception. The dataset is collected in 4 unique environments, with over 13,000 synchronized frames across approximately 29 minutes of operation, and includes both SAM~3-based zero-shot segmentation and over 8,000 manually labeled images. A unique aspect of the dataset is its early-spring collection period, during which sparse tree canopies allow the aerial robot to partially observe the ground robot and terrain through the trees, allowing for occlusion-aware collaborative perception. Unlike prior multi-robot datasets that focus on SLAM or simulated cooperative driving, GA3T is specifically designed to support research on cross-view perception, air-ground viewpoint fusion, traversability estimation, and collaborative scene understanding in real off-road environments.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          Bridging Generation and Training: A Systematic Review of Quality Issues in LLMs for Code
 - **Authors:** Kaifeng He, Xiaojun Zhang, Peiliang Cai, Mingwei Liu, Yanlin Wang, Chong Wang, Kaifeng Huang, Bihuan Chen, Xin Peng, Zibin Zheng
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) frequently generate defective outputs in code generation tasks, ranging from logical bugs to security vulnerabilities. While these generation failures are often treated as model-level limitations, empirical evidence increasingly traces their root causes to imperfections within the training corpora. Yet, the specific mechanisms linking training data quality issues to generated code quality issues remain largely unmapped. This paper presents a systematic literature review of 114 primary studies to investigate how training data quality issues propagate into code generation. We establish a unified taxonomy that categorizes generated code quality issues across nine dimensions and training data quality issues into code and non-code attributes. Based on this taxonomy, we formalize a causal framework detailing 18 typical propagation mapping mechanisms. Furthermore, we synthesize state-of-the-art detection and mitigation techniques across the data, model, and generation lifecycles. The reviewed literature reveals a clear methodological shift: quality assurance is transitioning from reactive, heuristic-based post-generation filtering toward proactive, data-centric governance and closed-loop repair. Finally, we identify open challenges and outline research directions for developing reliable LLMs for code through integrated data curation and continuous evaluation. Our repository is available at this https URL.
### Title:
          egenioussBench: A New Dataset for Geospatial Visual Localisation
 - **Authors:** Phillipp Fanta-Jende, Francesco Vultaggio, Alexander Kern, Yasmin Loeper, Markus Gerke
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present egenioussBench, a visual localisation benchmark built on geospatial reference data: a city-scale airborne 3D mesh and a CityGML LoD2 model. This pairing reflects deployable mapping assets and supports true scalability beyond traditional SfM-based approaches. The query data comprise smartphone images with centimetre-accurate, map-independent ground truth obtained via PPK and GCP/CP-aided adjustment. From 2,709 images, we derive a non-co-visible subset by estimating the full co-visibility matrix from rendered depth and selecting a maximum independent set; the released data include a test split of 42 non-co-visible images with withheld ground truth and a validation split of 412 sequential images with poses, e.g. for training of pose regressors and self-validation. The benchmark features a public leaderboard evaluated with binning metrics at multiple pose-error thresholds alongside global statistics (median, RMSE, outlier ratio), ensuring fair, like-for-like comparison across mesh- and LoD2-based methods. Together, these design choices expose realistic cross-view and cross-domain challenges while providing a rigorous, scalable path for advancing large-scale visual localisation. We make the evaluation code and data availeable at this https URL and this https URL
### Title:
          An Open-Source Flow for Single-Phase, Edge-Triggered to Two-Phase, Non-Overlapping Clocking Conversion
 - **Authors:** Paolo Pedroso, Lee-Way Wang, Matthew Guthaus
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Two-phase clocking offers significant advantages in timing margin and clock flexibility, yet its adoption remains limited due to the absence of automation in modern design flows. Managing strict non-overlap and 180$^\circ$ phase separation introduces complexity in RTL implementation and timing closure, leaving two-phase clocking rare in practice. This paper presents the first fully automated two-phase clocking flow integrated into OpenROAD Flow Scripts (ORFS). Our methodology automatically transforms flip-flop-based RTL into two-phase latch-based designs using Yosys technology mapping, ABC retiming, dual clock tree synthesis, two-phase correctness validation, and full physical design from RTL-to-GDS. We implement clock-gated and recirculation mux variants, where clock-gated achieves an average 29.2\% power reduction and 50\% latch count reduction over recirculation mux. Both variants are compared against flip-flop baselines, demonstrating timing closure through time borrowing on a design that failed timing with flip-flops.
### Title:
          Leveraging Image Generators to Address Training Data Scarcity: The Gen4Regen Dataset for Forest Regeneration Mapping
 - **Authors:** Gabriel Jeanson, David-Alexandre Duclos, William Larrivée-Hardy, Noé Cochet, Matěj Boxan, Anthony Deschênes, François Pomerleau, Philippe Giguère
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sustainable forest management relies on precise species composition mapping, yet traditional ground surveys are labour-intensive and geographically constrained. While Uncrewed Aerial Vehicles (UAVs) offer scalable data collection, the transition to deep learning-based interpretation is bottlenecked by the severe scarcity of expert-annotated imagery, particularly in complex, visually heterogeneous regeneration zones. This paper addresses the dual challenges of data scarcity and extreme class imbalance in the semantic segmentation of fine-grained forest regeneration species by providing a scalable framework that reduces reliance on manual photo-interpretation for high-resolution, millimetre-level aerial imagery. Importantly, we leverage the large-scale vision-language Nano Banana Pro model to simultaneously generate high-fidelity images and their corresponding pixel-aligned semantic masks from prompts. We introduce WilDReF-Q-V2, an expansion of a natural forest dataset with 13 977 new unlabelled and 50 labelled real images, as well as the Gen4Regen dataset, featuring 2101 pairs of synthetic images and semantic masks. Our methodology integrates real-world data with AI-generated images, highlighting that AI-generated data is highly complementary to real-world data, with unified training yielding an F1 score improvement of over 15 %pt compared to purely supervised baselines. Furthermore, we demonstrate that even small quantities of prompt-generated data significantly improve performance for underrepresented species, some of which saw per-species F1 score gains of up to 30 %pt. We conclude that vision-language models can serve as agile data generators, effectively bootstrapping perception tasks for niche AI domains where expert labels are scarce or unavailable. Our datasets, source code, and models will be available at this https URL.
### Title:
          R2H-Diff: Guided Spectral Diffusion Model for RGB-to-Hyperspectral Reconstruction
 - **Authors:** Songyu Ding, Ronggiang Zhao, Mingchun Sun, Jie Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 RGB-to-hyperspectral image reconstruction is a highly ill-posed inverse problem, since multiple plausible spectral distributions may correspond to the same RGB observation. Existing regression-based methods usually learn a deterministic mapping, which limits their ability to model reconstruction uncertainty and often leads to over-smoothed spectral responses. Although diffusion models provide strong distribution modeling capability, their direct application to hyperspectral reconstruction remains challenging due to the high spectral dimensionality, strong inter-band correlations, and strict requirement for spectral fidelity. To this end, we propose R2H-Diff, an efficient diffusion-based framework tailored for RGB-to-HSI reconstruction. Specifically, R2H-Diff formulates spectral recovery as a conditional iterative refinement process, enabling progressive reconstruction under RGB guidance. We proposed a Guided Spectral Refinement Module for RGB-conditioned feature fusion and a Hyperspectral-Adaptive Transposed Attention module for efficient spatial--spectral dependency modeling. Furthermore, a normalization-free denoising backbone is adopted to preserve spectral amplitude consistency, while a task-adapted linear noise schedule enables high-quality reconstruction with only five denoising steps. Extensive experiments on NTIRE2022, CAVE, and Harvard demonstrate that R2H-Diff achieves a favorable balance between reconstruction quality and computational efficiency. Notably, on NTIRE2022, R2H-Diff obtains 35.37 dB PSNR with a sub-million-parameter model of 0.58M parameters and 12.25G FLOPs, achieving the lowest model complexity among the evaluated methods while maintaining strong reconstruction fidelity.
### Title:
          LCC-LLM: Leveraging Code-Centric Large Language Models for Malware Attribution
 - **Authors:** Christopher G. Pedraza Pohlenz, Hassan Jalil Hadi, Ali Hassan, Ali Shoker
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLMs are increasingly explored for malware analysis; however, current LLM-based malware attribution remains limited by unsupported indicators and insufficient code-level grounding for identifying malicious and vulnerable code segments. To address these limitations, this research introduces LCC-LLM, a code-centric benchmark dataset and evidence-grounded framework for malware attribution and multi-task static malware analysis. The proposed LCCD dataset contains approximately 34K PE samples processed through a large-scale reverse-engineering pipeline and represented using decompiled C code, assembly code, CFG/FCG artifacts, hexadecimal data, PE metadata, suspicious API evidence, and structural features. Beyond dataset construction, LCC-LLM integrates LangGraph-orchestrated static analysis with multi-source cybersecurity knowledge to support evidence-grounded malware reasoning. The framework employs a seven-layer retrieval-augmented generation pipeline, CoVe for IoC validation, and a multi-dimensional quality gate to improve factual reliability and analyst-oriented decision support. Curriculum-ordered instruction data is used to fine-tune DeepSeek-R1-Distill-Qwen-14B and Qwen3-Coder-30B-A3B using QLoRA. Evaluation across 43 malware-analysis task types achieves an average semantic similarity of 0.634, with the highest task-level performance in structured report generation, IoC extraction, vulnerability assessment, malware configuration extraction, and malware class detection. In a real-world case study using MalwareBazaar samples, the grounded pipeline achieves a 10/10 structured analysis pass rate, producing CFG/FCG evidence, MITRE ATT&CK mappings, detection guidance, and analyst-ready reports. These results show that code-centric representations, retrieval grounding, and verification-guided reasoning improve the reliability and operational usefulness of LLM-assisted malware attribution.
### Title:
          MoE-Hub: Taming Software Complexity for Seamless MoE Overlap with Hardware-Accelerated Communication on Multi-GPU Systems
 - **Authors:** Zhuoshan Zhou, Chen Zhang, Shuyi Zhang, Qijun Zhang, Haibo Wang, Zhe Zhou, Zhipeng Tu, Guangyu Sun, Yijia Diao, Zhigang Ji, Jingwen Leng, Guanghui He, Minyi Guo
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Mixture-of-Experts (MoE) architecture is crucial for scaling large language models, but its scalability is severely limited by inter-GPU communication bottlenecks in multi-GPU systems. Although overlapping communication with computation is a widely recognized optimization, its effective deployment still remains challenging, both in terms of performance and programmability. In this work, we identify the root cause as a fundamental abstraction mismatch between MoE's dynamic, irregular token-to-expert mapping and the static, address-centric communication model of modern GPUs, which necessitates a complex software mediation phase to resolve addresses before data transfers, limiting performance and software flexibility. To resolve this, we propose MoE-Hub, a hardware-software co-design that introduces a destination-agnostic communication paradigm. MoE-Hub decouples data transmission from address management, allowing producers to send data immediately after routing using only a logical destination, while address allocation and data-flow orchestration are handled transparently by lightweight hardware in the GPU hub. By hardware-accelerating the entire communication control plane, MoE-Hub enables seamless and transparent overlap. Our evaluation shows that MoE-Hub achieves 1.40x-3.08x per-layer and 1.21x-1.98x end-to-end speedup over state-of-the-art systems.
### Title:
          RAWild: Sensor-Agnostic RAW Object Detection via Physics-Guided Curve and Grid Modeling
 - **Authors:** Shuhong Liu, Gengjia Chang, Jun Liu, Xuangeng Chu, Yinqiang Zheng, Tatsuya Harada, Ziteng Cui
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Camera sensor RAW data offers intrinsic advantages for object detection, including deeper bit depth, preserved physical information, and freedom from image signal processor (ISP) distortions. However, varying exposure conditions, spectral sensitivities, and bit depths across devices introduce substantially larger domain gaps than sRGB, making sensor-agnostic generalization a fundamental challenge. In this study, we present \textbf{RAWild}, a physics-guided global-local tone mapping framework for sensor-agnostic RAW object detection. By factoring sensor-induced variations into a global tonal correction and a spatially adaptive local color adjustment, both driven by RAW distribution priors, our framework enables a single network to train jointly across heterogeneous sensors. To further support cross-sensor generalization, we construct a physics-based RAW simulation pipeline that synthesizes realistic sensor outputs spanning diverse spectral sensitivities, illuminants, and sensor non-idealities. Extensive experiments across multiple RAW benchmarks covering bit depths from 10 to 24 demonstrate state-of-the-art (SOTA) performance under single-dataset, mixed-dataset, and challenging robustness settings.
### Title:
          Uncertainty Estimation via Hyperspherical Confidence Mapping
 - **Authors:** Eunseo Choi, Ho-Yeon Kim, Jaewon Lee, Taeyong jo, Myungjun lee, Heejin Ahn
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Quantifying uncertainty in neural network predictions is essential for high-stakes domains such as autonomous driving, healthcare, and manufacturing. While existing approaches often depend on costly sampling or restrictive distributional assumptions, we propose Hyperspherical Confidence Mapping (HCM), a simple yet principled framework for sampling-free and distribution-free uncertainty estimation. HCM decomposes outputs into a magnitude and a normalized direction vector constrained to lie on the unit hypersphere, enabling a novel interpretation of uncertainty as the degree of violation of this geometric constraint. This yields deterministic and interpretable estimates applicable to both regression and classification. Experiments across diverse benchmarks and real-world industrial tasks demonstrate that HCM matches or surpasses ensemble and evidential approaches, with far lower inference cost and stronger confidence-error alignment. Our results highlight the power of geometric structure in uncertainty estimation and position HCM as a versatile alternative to conventional techniques.
### Title:
          FluxShard: Motion-Aware Feature Cache Reuse for Collaborative Video Analytics in Mobile Edge Computing
 - **Authors:** Xiuxian Guan, Zongyuan Zhang, Zheng Lin, Zekai Sun, Tianyang Duan, Zihan Fang, Rui Wang, Heming Cui, Wei Ni, Jun Luo, Yuanwei Liu
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Caching and reusing intermediate features across consecutive frames is a common technique to reduce redundant computation and transmission for edge-cloud video analytics in mobile edge computation. Existing methods manage the cache in a fixed or globally shifted coordinate system, treating it as an indivisible whole. Under the non-uniform motion patterns of mobile scenes, this whole-scene granularity invalidates large portions of the cache even when most content has merely shifted spatially, wasting computation and bandwidth. The root cause is a granularity mismatch: the cache is managed per scene, yet motion varies per region. In this paper, we present FluxShard, a motion-aware edge-cloud video analytics system that uses codec-level block motion vectors (MVs) to manage feature cache reuse and recomputation at the granularity of individual motion regions. By re-indexing cached features along per-block MVs, FluxShard separates spatial displacement from content changes, recovering reusable content that whole-scene methods would otherwise discard. To ensure correct reuse under heterogeneous motion, the Receptive Field Alignment Principle (RFAP) identifies, from the input-level MV field alone, the positions that must be recomputed due to inconsistent spatial composition within receptive fields. To maintain cache coherence across frames, MV-guided cache remapping warps the entire feature cache to the current coordinate system each frame, sustaining a high reuse ratio over time. A profiling-driven dispatcher routes the remaining sparse workload between edge and cloud for lower latency. Evaluation across multiple vision tasks, dynamic video benchmarks, and network conditions shows that FluxShard reduces latency by 32.6-83.8% and energy by 14.9-64.0% over all baselines under the prescribed accuracy budget.
### Title:
          SuperFace: Preference-Aligned Facial Expression Estimation Beyond Pseudo Supervision
 - **Authors:** Zejian Kang, Xuanyang Xu, Wentao Yang, Kai Zheng, Yuanchen Fei, Hongyuan Zou, Hui Shan, Shuo Yang, Xiangru Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate facial estimation is crucial for realistic digital human animation, and ARKit blendshape coefficients offer an interpretable representation by mapping facial motions to semantic animation controls. However, learning high-quality ARKit coefficient prediction remains limited by the absence of reliable ground-truth supervision. Existing methods typically rely on capture software such as Live Link Face to provide pseudo labels, which may contain noisy activations, biased coefficient magnitudes, and missing or inaccurate facial actions. Consequently, models trained with supervised learning tend to reproduce imperfect pseudo labels rather than optimize for perceptual expression fidelity. In this paper, we propose SuperFace, a preference-driven framework that moves ARKit facial expression estimation from pseudo-label imitation toward human-aligned perceptual optimization. Instead of treating software-estimated coefficients as fixed ground truth, SuperFace uses them only as an initialization and further improves coefficient prediction through human preference feedback on rendered facial expressions. By aligning the model with perceptual judgments rather than numerical pseudo labels, SuperFace enables more visually faithful and expressive facial animation. Experiments show that SuperFace improves expression fidelity over Live Link Face supervision, demonstrating the effectiveness of preference-driven optimization for semantic facial action prediction.
### Title:
          Adaptive Coordinate Transforms for Neural Operators
 - **Authors:** Chaoyu Liu, Zhonghao Li, Gaohang Chen, Zakhar Shumaylov, Zhongying Deng, Qian Zhang, Zhonghua Qiao, Carola-Bibiane Schönlieb
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural operators have achieved promising performance on partial differential equations (PDEs), but most existing models are built on fixed Eulerian coordinates. This mismatch between evolving physical structures and static coordinates creates spatial misalignment, leading to unnecessarily non-local operator mappings and reinforcing a smoothness preference near sharp transitions. Inspired by adaptive coordinate transformations in classical PDE analysis, we propose the Adaptive Coordinate Transform (ACT) block, a plug-and-play module for data-driven geometric adaptation in neural operators. ACT blocks resolve this structural limitation by learning adaptive coordinate systems within the operator learning pipeline. Specifically, given an input feature, the ACT block learns a coordinate transformation and represents the same feature under the transformed coordinates via differentiable sampling. This operation preserves the underlying signal while changing its spatial representation, equivalent to expressing the same physical quantity in different coordinate systems. By adapting the coordinate system to the data, ACT allows the network to better track evolving structures, reduce operator complexity, and dynamically focus on critical features to improve learning. We evaluate the proposed approach across diverse PDE benchmarks and multiple neural operator architectures. Experimental results demonstrate consistent and significant improvements in predictive accuracy, indicating that learning coordinate systems provides a powerful mechanism for enhancing operator learning.
### Title:
          A polar-factor retraction on the symplectic Stiefel manifold with closed-form inverse
 - **Authors:** Ralf Zimmermann
 - **Subjects:** Subjects:
Numerical Analysis (math.NA); Mathematical Physics (math-ph); Differential Geometry (math.DG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In Riemannian computing applications, it is crucial to map manifold data to a Euclidean domain, where vector space arithmetic is available, and back. Classical manifold theory guarantees the existence of such mappings, called charts and parameterizations, or, collectively, local coordinates. When computational efficiency is of the essence, practitioners usually resort to retraction maps to define local coordinates. Retractions yield first-order approximations of the Riemannian normal coordinates. This work introduces a new retraction on the symplectic Stiefel manifold that features a closed-form inverse. We expose essential features and compare the numerical performance to a selection of existing retractions. To the best of our knowledge, prior to this work, the so-called Cayley retraction was the only retraction on the symplectic Stiefel manifold with known closed-form inverse.
### Title:
          Constraint Decay: The Fragility of LLM Agents in Backend Code Generation
 - **Authors:** Francesco Dente, Dario Satriani, Paolo Papotti
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Model (LLM) agents demonstrate strong performance in autonomous code generation under loose specifications. However, production-grade software requires strict adherence to structural constraints, such as architectural patterns, databases, and object-relational mappings. Existing benchmarks often overlook these non-functional requirements, rewarding functionally correct but structurally arbitrary solutions. We present a systematic study evaluating how well agents handle structural constraints in multi-file backend generation. By fixing a unified API contract across 80 greenfield generation tasks and 20 feature-implementation tasks spanning eight web frameworks, we isolate the effect of structural complexity using a dual evaluation with end-to-end behavioral tests and static verifiers. Our findings reveal a phenomenon of constraint decay: as structural requirements accumulate, agent performance exhibits a substantial decline. Capable configurations lose 30 points on average in assertion pass rates from baseline to fully specified tasks, while some weaker configurations approach zero. Framework sensitivity analysis exposes significant performance disparities: agents succeed in minimal, explicit frameworks (e.g., Flask) but perform substantially worse on average in convention-heavy environments (e.g., FastAPI, Django). Finally, error analysis identifies data-layer defects (e.g., incorrect query composition and ORM runtime violations) as the leading root causes. This work highlights that jointly satisfying functional and structural requirements remains a key open challenge for coding agents.
### Title:
          Operator-Guided Invariance Learning for Continuous Reinforcement Learning
 - **Authors:** Zuyuan Zhang, Fei Xu Yu, Tian Lan
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reinforcement learning (RL) with continuous time and state/action spaces is often data-intensive and brittle under nuisance variability and shift, motivating methods that exploit value-preserving structures to stabilize and improve learning. Most existing approaches focus on special cases, such as prescribed symmetries and exact equivariance, without addressing how to discover more general structures that require nonlinear operators to transform and map between continuous state/action systems with isomorphic value functions. We propose \textbf{VPSD-RL} (Value-Preserving Structure Discovery for Reinforcement Learning). It models continuous RL as a controlled diffusion with value-preserving mappings defined through Lie-group actions and associated pullback operators. We show that a value-preserving structure exists exactly when pulling back the value function and pushing forward actions commute with the controlled generator and reward functional. Further, approximate value-preserving structures with rigorous guarantees can be found when the Hamilton--Jacobi--Bellman mismatch is small. This framework discovers exact and approximate value-preserving structures by searching for the associated Lie group operators. VPSD-RL fits differentiable drift, diffusion, and reward models; learns infinitesimal generators via determining-equation residual minimization; exponentiates them with ODE flows to obtain finite transformations; and integrates them into continuous RL through transition augmentation and transformation-consistency regularization. We show that bounded generator/reward mismatch implies quantitative stability of the optimal value function along approximate orbits, with sensitivity governed by the effective horizon, and observe improved data efficiency and robustness on continuous-control benchmarks.
### Title:
          Continuous Latent Diffusion Language Model
 - **Authors:** Hongcan Guo, Qinyu Zhao, Yian Zhao, Shen Nie, Rui Zhu, Qiushan Guo, Feng Wang, Tao Yang, Hengshuang Zhao, Guoqiang Wei, Yan Zeng
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models have achieved remarkable success under the autoregressive paradigm, yet high-quality text generation need not be tied to a fixed left-to-right order. Existing alternatives still struggle to jointly achieve generation efficiency, scalable representation learning, and effective global semantic modeling. We propose Cola DLM, a hierarchical latent diffusion language model that frames text generation through hierarchical information decomposition. Cola DLM first learns a stable text-to-latent mapping with a Text VAE, then models a global semantic prior in continuous latent space with a block-causal DiT, and finally generates text through conditional decoding. From a unified Markov-path perspective, its diffusion process performs latent prior transport rather than token-level observation recovery, thereby separating global semantic organization from local textual realization. This design yields a more flexible non-autoregressive inductive bias, supports semantic compression and prior fitting in continuous space, and naturally extends to other continuous modalities. Through experiments spanning 4 research questions, 8 benchmarks, strictly matched ~2B-parameter autoregressive and LLaDA baselines, and scaling curves up to about 2000 EFLOPs, we identify an effective overall configuration of Cola DLM and verify its strong scaling behavior for text generation. Taken together, the results establish hierarchical continuous latent prior modeling as a principled alternative to strictly token-level language modeling, where generation quality and scaling behavior may better reflect model capability than likelihood, while also suggesting a concrete path toward unified modeling across discrete text and continuous modalities.
## Keyword: localization
### Title:
          On Unbiased Parameter Estimation and Signal Reconstruction
 - **Authors:** Joonas Lahtinen
 - **Subjects:** Subjects:
Information Theory (cs.IT); Optimization and Control (math.OC); Probability (math.PR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we expand the theory of depth-unbiased source localization to unbiased parameter estimation and signal reconstruction of an arbitrary number of non-zero parameters to be recovered. The topic touches on the concept of exact reconstructibility, most commonly known in compressed sensing and multisource estimation in various imaging problems. The theoretical results derive upper bounds on the number of recoverable parameters in the noiseless case, and a probability measure is defined to assess the probability of obtaining all non-zero parameters with correct magnitude order. The work provides a mathematical explanation of the open question regarding the noise robustness of standardized and unbiased methods. Also, the paper reveals a trade-off between the number of sensors and the signal-to-noise ratio. Numerical experiments demonstrate the theoretical findings.
### Title:
          Tamaththul3D: High-Fidelity 3D Saudi Sign Language Avatars from Monocular Video
 - **Authors:** Eyad Alghamdi, Sattam Altuuaim, Obay Ghulam, Abdulrahman Qutah, Yousef Basoodan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Arabic Sign Language (ArSL) and its dialects serve approximately 400 million Arabic speakers worldwide, yet the community lacks high-quality 3D parametric annotations and specialized reconstruction methods for avatar generation. We address this critical gap through two key contributions: First, we introduce the first high-quality 3D parametric annotations for the Ishara-500 Saudi Sign Language dataset, providing precise SMPL-X parameters for 500 culturally authentic SSL signs. Second, we present Tamaththul3D, a specialized reconstruction pipeline designed for ArSL's unique articulation patterns. Our pipeline integrates SMPLer-X for robust body estimation, WiLoR for detailed hand refinement with automatic localization and mirroring, and MediaPipe for 2D pose supervision. Through kinematic-chain-based wrist alignment with hybrid swing-twist decomposition and 2D-supervised joint optimization, Tamaththul3D achieves state-of-the-art hand accuracy (up to 32% improvement over previous methods) while maintaining competitive body pose. Together, these 3D annotations and Tamaththul3D pipeline establish the first comprehensive framework for high-fidelity ArSL avatar reconstruction, enabling new accessibility technologies and cultural preservation efforts for the Arab Deaf community.
### Title:
          LAMP: Localization Aware Multi-camera People Tracking in Metric 3D World
 - **Authors:** Nan Yang, Julian Straub, Fan Zhang, Richard Newcombe, Jakob Engel, Lingni Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tracking 3D human motion from egocentric multi-camera headset is challenged by severe egomotion, partial visibility or occlusions and lack of training data. Existing methods designed for monocular video often require static or slowly-moving cameras and cannot efficiently leverage multi-view, calibrated and localized input. This makes them brittle and prone to fail on dynamic egocentric captures. We propose LAMP (Localization Aware Multi-camera People Tracking): a novel, simple framework to solve this via early disentanglement of observer and target motion. LAMP introduces a two-step process. First, we leverage the known device 6 DoF motion and calibration to convert detected 2D body keypoints from all cameras over a temporal window into a unified 3D world reference frame. Second, an end-to-end-trained spatio-temporal transformer fits 3D human motion directly to this 3D ray cloud. This "lift-then-fit" approach allows LAMP to learn and leverage a natural human motion prior in the world-space, as well as providing an elegant framework to flexibly incorporate information from multiple temporally asynchronous, partially observing and moving cameras. LAMP achieves state-of-the-art results on monocular benchmarks, while significantly outperforming baselines for our targeted egocentric setting.
### Title:
          Online Localized Conformal Prediction
 - **Authors:** Yuheng Lai, Garvesh Raskutti
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Conformal prediction is a framework that provides valid uncertainty quantification for general models with exchangeable data. However, in the online learning and time-series settings, exchangeability is not satisfied. Existing online conformal methods, such as adaptive conformal inference (ACI), can achieve long-run validity, yet they remain inefficient under covariate heterogeneity because they rely on global calibration. We propose \emph{Online Localized Conformal Prediction (OLCP)}, which combines online adaptation with covariate-dependent localization to better reflect heterogeneity. To reduce sensitivity to the localization bandwidth, we further develop \emph{OLCP-Hedge}, which performs bandwidth selection as an online expert aggregation problem using a constrained online convex optimization framework. Importantly, we provide coverage guarantees for both algorithms and demonstrate through simulations and real-data experiments that the proposed methods attain valid long-run coverage with narrower prediction sets than existing baselines.
### Title:
          Causal Probing for Internal Visual Representations in Multimodal Large Language Models
 - **Authors:** Zehao Deng, Tianjie Ju, Zheng Wu, Liangbo He, Jun Lan, Huijia Zhu, Weiqiang Wang, Zhuosheng Zhang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite the remarkable success of Multimodal Large Language Models (MLLMs) across diverse tasks, the internal mechanisms governing how they encode and ground distinct visual concepts remain poorly understood. To bridge this gap, we propose a causal framework based on activation steering to actively probe and manipulate internal visual representations. Through systematic intervention across four visual concept categories, our results reveal a divergence in concept encoding: entities exhibit distinct localized memorization, whereas abstract concepts are globally distributed across the network. Critically, this divergence uncovers a mechanistic driver of scaling laws: increasing model depth is indispensable for encoding distributed and complex abstract concepts, whereas entity localization remains remarkably invariant to scale. Furthermore, reverse steering uncovers that blocking explicit output triggers a surge in latent activations, exposing a compensatory mechanism between perception and generation. Finally, extending our analysis to visual reasoning, we expose a disconnect between perception and reasoning although MLLMs successfully recognize geometric relations, they treat them merely as static visual features, failing to trigger the procedural execution necessary for abstract problem-solving.
### Title:
          AffectSeek: Agentic Affective Understanding in Long Videos under Vague User Queries
 - **Authors:** Zhen Zhang, Yuhang Yang, Yunxiang Jiang, Yuhuan Lu, Haifeng Lu, Zheng Lian, Runhao Zeng, Xiping Hu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing affective understanding studies have mainly focused on recognizing emotions from images, audio signals, or pre-cliped video clips, where the affective evidence is already given. This passive and clip-centered setting does not fully reflect real-world scenarios, in which users often interact with long videos and express their needs through natural-language queries. In this paper, we study \textbf{Vague-Query-driven video Affective Understanding (VQAU)}, a new task that requires models to localize affective moments in long videos, predict their emotion categories, and generate evidence-grounded rationales under vague user queries. To support this task, we construct \textbf{VQAU-Bench}, a benchmark that integrates long videos, vague affective queries, temporal clip annotations, emotion labels, and rationale explanations into a unified evaluation framework. VQAU-Bench enables systematic assessment of semantic-temporal-affective alignment, affective moment localization, emotion classification, and rationale generation. To address the multi-step reasoning challenges of VQAU, we further propose \textbf{AffectSeek}, an agentic framework that actively seeks, verifies, and explains affective moments in long videos. AffectSeek decomposes VQAU into intent interpretation, candidate localization, clip verification, emotion reasoning, and rationale generation, and progressively aligns vague user intent with long-video evidence through role-specialized reasoning and cross-stage verification. Experiments show that VQAU remains challenging for existing affective recognition models and single-step vision-language models, while AffectSeek provides a simple yet effective framework for agentic long-video affective understanding.
### Title:
          Plug-and-Play Label Map Diffusion for Universal Goal-Oriented Navigation
 - **Authors:** Zhixuan Shen, Yijie Zeng, Shengxiang Luo, Tianrui Li, Haonan Luo
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In embodied vision, Goal-Oriented Navigation (GON) requires robots to locate a specific goal within an unexplored environment. The primary challenge of GON arises from the need to construct a Bird's-Eye-View (BEV) map to understand the environment while simultaneously localizing an unobserved goal. Existing map-based methods typically employ self-centered semantic maps, often facing challenges such as reliance on complete maps or inconsistent semantic association. To this end, we propose Plug-and-Play Label Map Diffusion (PLMD), which defines a novel map completion diffusion model based on Denoising Diffusion Probabilistic Models (DDPM). PLMD generates obstacle and semantic labels for unobserved regions through a diffusion-based completion process, thereby enabling goal localization even in partially observed environments. Moreover, it mitigates inconsistent semantic association by leveraging structural consistency between known and unknown obstacle layouts and integrating obstacle priors into the semantic denoising process. By substituting predicted labels for unobserved regions, robots can accurately localize the specified objects. Extensive experiments demonstrate that PLMD \textbf{(I)} effectively expands the region of unknown maps, \textbf{(II)} integrates seamlessly into existing navigation strategies that rely on semantic maps, \textbf{(III)} achieves state-of-the-art performance on three GON tasks.
### Title:
          Tatarstan Toponyms: A Bilingual Dataset and Hybrid RAG System for Geospatial Question Answering
 - **Authors:** Mullosharaf K. Arabov
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper addresses automatic geospatial question answering over multilingual toponymic data. An original bilingual dataset of toponyms of the Republic of Tatarstan is introduced, comprising 9,688 structured records with linguistic, etymological, administrative, and coordinate information (93.1% georeferenced). Based on this dataset, a question-answering corpus of approximately 39,000 question-context-answer triples is constructed with guaranteed answer localization. A hybrid retriever integrates dense semantic indexing (multilingual-e5-large) with geospatial filtering via KD-trees and haversine distance. On 500 test queries, the hybrid search achieves Recall@1=0.988, Recall@5=1.000, and MRR=0.994, significantly outperforming BM25 and purely spatial methods. Among tested reader architectures (RuBERT, XLM-RoBERTa-large, T5-RUS), XLM-RoBERTa-large attains the best quality: EM=0.992, F1=0.994. On raw outputs, RuBERT models fail on coordinate questions (F1=0) while XLM-RoBERTa-large reaches F1=0.984; however, simple post-processing eliminates numerical gaps and restores RuBERT accuracy to 100%. This discrepancy stems from tokenization differences and pre-training corpora composition. All resources (dataset, QA corpus, model weights, web demo) are openly published on Hugging Face. Results apply to geospatial QA services, geocoding, and digital humanities in multilingual regions.
### Title:
          Sharper Guarantees for Misspecified Kernelized Bandit Optimization
 - **Authors:** Davide Maran, Csaba Szepesvári
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Optimization and Control (math.OC); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing guarantees for misspecified kernelized bandit optimization pay for misspecification through kernel complexity: in generic offline bounds, the misspecification level $\varepsilon$ is multiplied by $\sqrt{d_\mathrm{eff}}$, where $d_\mathrm{eff}$ is the kernel effective dimension, while in online regret bounds, the corresponding penalty is $\sqrt{\gamma_n}\,n\varepsilon$, where $\gamma_n$ is the maximum information gain after $n$ rounds of interaction. In this work, we show that, for a large class of kernels, the misspecification amplification can be reduced to logarithmic or polylogarithmic growth. In the offline setting, we first prove high-probability simple-regret bounds whose misspecification term is governed by a spectral Lebesgue constant. This yields logarithmic amplification for one-dimensional monotone spectra and polylogarithmic amplification for multivariate Fourier-diagonal product kernels. In the online setting, we modify a domain-splitting algorithm and prove a cumulative regret bound of $\widetilde{\mathcal O}(\sqrt{\gamma_n n}+n\varepsilon)$ under mild localized eigendecay assumptions, removing the extra $\sqrt{\gamma_n}$ factor from the misspecification term. The common principle is localization: spectral localization controls the Lebesgue constant of the offline approximation operator, while domain splitting implements the spatial analogue of this mechanism in the online setting, preventing local misspecification errors from being amplified globally.
### Title:
          A Fine-Grained Understanding of Uniform Convergence for Halfspaces
 - **Authors:** Aryeh Kontorovich, Kasper Green Larsen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Statistics Theory (math.ST)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study the fine-grained uniform convergence behavior of halfspaces beyond worst-case VC bounds. For inhomogeneous halfspaces in $\mathbb{R}^d$ with $d\ge 2$, we show that standard first-order VC bounds are essentially tight: even consistent hypotheses can incur population error $\Theta(d\ln(n/d)/n)$, and in the agnostic setting the deviation scales as $\sqrt{\tau\ln(1/\tau)}$ at true error $\tau$. In contrast, homogeneous halfspaces in $\mathbb{R}^2$ exhibit a markedly different behavior. In the realizable case, every hypothesis consistent with the sample has error $O(1/n)$. In the agnostic case, we prove a bandwise, log-free deviation bound on each dyadic risk band via a critical-wedge localization argument. Unioning over bands incurs only a $\ln\ln n$ overhead, and we establish a matching lower bound showing this overhead is unavoidable. Together, these results give a fine-grained and nearly complete picture of uniform convergence for halfspaces, revealing sharp dimensional and structural thresholds.
### Title:
          Towards Self-Explainable Document Visual Question Answering with Chain-of-Explanation Predictions
 - **Authors:** Kjetil Indrehus, Adrian Duric, Changkyu Choi, Ali Ramezani-Kebrya
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Document Visual Question Answering (DocVQA) requires vision-language models to reason not only about what information in a document is relevant to a question, but also where the answer is grounded on the page. Existing DocVQA models entangle question-relevant evidence and answer localization and operate largely as black boxes, offering limited means to verify how predictions depend on visual evidence. We propose CoExVQA, a self-explainable DocVQA framework with a grounded reasoning process through a chain-of-explanation design. CoExVQA first identifies question-relevant evidence, then explicitly localizes the answer region, and finally decodes the answer exclusively from the grounded region. Prediction via CoExVQA's chain-of-explanation enables direct inspection and verification of the reasoning process across modalities. Empirical results show that restricting decoding to grounded evidence achieves SotA explainable DocVQA performance on PFL-DocVQA, improving ANLS by 12% over the current explainable baselines while providing transparent and verifiable predictions.
### Title:
          Navigating by Old Maps: The Pitfalls of Static Mechanistic Localization in LLM Post-Training
 - **Authors:** Hang Chen, Jiaying Zhu, Hongyang Chen, Hongxu Liu, Xinyu Yang, Wenya Wang
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The "Locate-then-Update" paradigm has become a predominant approach in the post-training of large language models (LLMs), identifying critical components via mechanistic interpretability for targeted parameter updates. However, this paradigm rests on a fundamental yet unverified assumption: can mechanisms derived from current static parameters reliably guide future dynamic parameter updates? To investigate this, we systematically track the structural evolution of Transformer circuits throughout the supervised fine-tuning (SFT) process, revealing the underlying dynamics of task mechanisms. We introduce three novel metrics-Circuit Distance, Circuit Stability, and Circuit Conflict-to analyze circuit evolution across three dimensions: neural migration, semantic stability, and cross-task interference. Our empirical results reveal that circuits inherently exhibit "Free Evolution" during parameter updates. Consequently, static mechanisms extracted from current states inevitably suffer from temporal latency, making them fundamentally inadequate for guiding future states. Moreover, by deconstructing the "illusion of effectiveness" in existing methods, this work underscores the necessity of "foresight" in mechanistic localization and proposes a predictive framework for future research.
### Title:
          SiblingRepair: Sibling-Based Multi-Hunk Repair with Large Language Models
 - **Authors:** Xinyu Liu, Jiayu Ren, Yusen Wang, Qi Xin, Xiaoyuan Xie, Jifeng Xuan
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Developers often make similar mistakes across code locations implementing related functionalities. These locations, called siblings, share similar issues and require similar fixes. Accurately identifying siblings and consistently repairing them are crucial for automated program repair. Hercules is a SOTA technique designed for sibling repair. However, it is limited by strong assumptions about sibling locations and commit-history availability, rigid AST-based sibling matching, and inflexible template-based patch generation. To address these limitations, we present SiblingRepair, a new LLM-based multi-hunk APR technique specialized for sibling repair. Starting from a suspicious location identified by spectrum-based fault localization, SiblingRepair searches for semantically related sibling candidates using token- and embedding-based code matching, without restricting discovery to failing-test coverage or commit history. It then uses an LLM to identify failure-relevant siblings and generate consistent patches through two complementary strategies: simultaneous repair, which jointly repairs siblings, and iterative repair, which progressively analyzes candidates for patch construction. SiblingRepair further preserves promising patches generated from earlier suspicious locations and combines them into generalized multi-hunk patches. We evaluate SiblingRepair on the Defects4J and GHRB benchmarks. The results show that SiblingRepair substantially outperforms SOTA multi-hunk repair techniques including Hercules. Our evaluation further demonstrates its repair efficiency, the effectiveness of its sibling detection and repair components, and limited impact of the LLM data leakage on the results. Overall, SiblingRepair advances automated sibling and general multi-hunk repair.
### Title:
          When Does $\ell_2$-Boosting Overfit Benignly? High-Dimensional Risk Asymptotics and the $\ell_1$ Implicit Bias
 - **Authors:** Ye Su, Jian Li, Yong Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Benign overfitting is well-characterized in $\ell_2$ geometries, but its behavior under the $\ell_1$ implicit bias of greedy ensembles remains challenging. The analytical barrier stems from the non-linear coupling of coordinate selection thresholds, which invalidates standard spectral resolvent tools. To isolate this algorithmic bias, we characterize the high-dimensional risk of continuous-time $\ell_2$-Boosting over $p$ features and $n$ samples. By coupling the Convex Gaussian Minimax Theorem with delicate asymptotic expansions of double-sided truncated Gaussian moments, we analytically resolve the non-smooth $\ell_1$ interpolant. Under an isotropic pure-noise model, we prove that benign overfitting fails at the linear rate: greedy selection localizes noise into sparse active sets, and the excess variance decays at a logarithmic rate $\Theta(\sigma^2/\log(p/n))$ for noise variance $\sigma^2$. We remark that while this localization mechanism should persist in the presence of signals, the exact signal-noise decomposition remains an open problem. For spiked-isotropic designs with $k^*$ head eigenvalues and $r_2 = p - k^*$ tail dimensions, the risk converges to zero when $r_{2} \gg n$, but only at a logarithmic rate $\Theta(\sigma^2/\log(r_2/n))$, which is slower than the linear decay observed in $\ell_2$ geometries. To avoid this slow convergence, we analyze the non-smooth subdifferential dynamics of the boosting flow. This yields a tuning-free early stopping rule that, under a bounded $\ell_1$-path condition, recovers the Lasso basic inequality and attains the minimax-optimal empirical prediction rate for $\ell_1$-bounded signals.
## Keyword: transformer
### Title:
          Adaptive Computation Depth via Learned Token Routing in Transformers
 - **Authors:** Ahmed Abdelmuniem Abdalla Mohammed
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Standard transformer architectures apply the same number of layers to every token regardless of contextual difficulty. We present Token-Selective Attention (TSA), a learned per-token gate on residual updates between consecutive transformer blocks. Each gate is a lightweight two-layer multi-layer perceptron (MLP) that produces a continuous halting probability, making the mechanism end-to-end differentiable with 1.7% parameter overhead and no changes to the base architecture. Notably, TSA learns difficulty-proportional routing without any explicit depth pressure: even at $\lambda=0$ (no depth regularisation), the task-loss gradient alone drives the router to skip 20% of token-layer operations. On character-level language modeling, TSA saved 14-23% of token-layer operations (TLOps) across Tiny-Shakespeare and enwik8 at <0.5% quality loss. At matched efficiency, TSA achieved 0.7% lower validation loss than early exit, and the learned routing transfers directly to inference-time sparse execution for real wall-clock speedup.
### Title:
          Structural Instability of Feature Composition
 - **Authors:** Yunpeng Zhou
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sparse Autoencoders (SAEs) have emerged as a powerful paradigm for disentangling feature superposition in transformer-based architectures, enabling precise control via activation steering. However, the theoretical foundations of compositional steering -- the simultaneous activation of distinct semantic latents -- remain under-explored. The prevailing Linear Representation Hypothesis often abstracts away non-linear interference effects that arise in overcomplete dictionaries. We present a geometric framework for analyzing the instability of feature unions. Modeling the activation space as a high-dimensional sparse cone manifold, we derive an asymptotic compositional-collapse threshold under a spherical dictionary model, characterized by the Gaussian mean width (statistical dimension) of the signal cone. We further show that, in the high-bias regime, ReLU rectification converts microscopic correlation-induced variance fluctuations into a systematic drift that accumulates under composition, yielding interference growth consistent with a ratchet effect. We validate the predicted scaling trends on structured semantic features extracted from CLEVR, where hierarchical correlations accelerate the transition relative to random baselines. Together, our results highlight geometric constraints on the scalability of union-based steering and motivate composition mechanisms that explicitly manage interference beyond naive linear superposition.
### Title:
          Dynamic Graph with Similarity-Aware Attention Graph Neural Network for Recommender Systems
 - **Authors:** Aadarsh Senapati, Neha Kujur, Vivek Yelleti
 - **Subjects:** Subjects:
Information Retrieval (cs.IR); Machine Learning (cs.LG); Social and Information Networks (cs.SI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recommender systems are essential components of modern online platforms which presents personalized content in various domain. The traditional collaborative filtering methods depends on static user-item interaction graphs and a limited subset of similarity measures which fail to capture the changing nature of preferences of an individual. Recent graph neural network (GNN) based approaches focus on user-item bipartite graphs which do not use explicit user-user relational modelling and dynamic graph evolution during training. To address these limitations, this paper proposes a Dynamic Graph SimilarityAware Attention Graph Neural Network (DG-SA-GNN) framework that integrates dynamic user similarity graph construction with multi-similarity propagation and attention-based aggregation. The proposed architecture constructs four parallel user similarity graphs using Cosine, Jaccard, Discounted Pearson Correlation Coefficient (Discount PCC), and IPIJ similarity functions, each processed by a dedicated UserGNN module. A Graph Transformer fuses the four graph views, and a CrossAttention module refines user embeddings through interaction with item embeddings. Crucially, the graphs are reconstructed at scheduled epochs during training, enabling the model to adapt to the learned embedding space constituting the dynamic graph component. Mini-batch training with hard negative sampling improves scalability and convergence. Experiments on the MovieLens100K benchmark demonstrate that DG-SA-GNN achieves a Recall@20 of 0.162 and NDCG@20 of 0.065 which is better than the LightGCN baseline in recall. The results validate that dynamic multi-similarity graph construction coupled with attention-based fusion which produce recommendation performance
### Title:
          Forecasting Green Skill Demand in the Automotive Industry: Evidence from Online Job Postings
 - **Authors:** Sabur Butt, Joshua N. Arrazola E., Hector G. Ceballos, Patricia Caratozzolo
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The global transition toward sustainable economies is reshaping labor markets, yet systematic methods for identifying and forecasting green skills remain limited. This study presents a computational framework to measure and predict green skill demand using online job postings from Mexico's automotive industry, which contributes about 4% of national GDP. We compile a dataset of job advertisements from Indeed Mexico, OCC Mundial, and LinkedIn (July 2024 to July 2025), yielding 204,373 skill records. A two-stage pipeline combining multilingual embeddings and ESCO validation identifies 274 unique green skills across 8,576 occurrences (4.22% of all skills). We benchmark 15 time series forecasting models using a rolling origin evaluation. Transformer-based models, especially FEDformer, Reformer, and Informer, achieve the best performance, with MAE around 2.5e-5 and relative RMSE below 15. We further propose a framework to classify skills by absolute and relative growth, identifying stable, emerging, and high-impact competencies. Results show current demand is concentrated in operational sustainability practices, while the fastest-growing skills relate to renewable energy, recycling, and hydrogen technologies. This pipeline supports data-driven workforce planning in the green transition.
### Title:
          Attribution-Guided Continual Learning for Large Language Models
 - **Authors:** Yazheng Liu, Yuxuan Wan, Rui Xu, Xi Zhang, Sihong Xie, Hui Xiong
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) often suffer from catastrophic forgetting in continual learning: after learning new tasks sequentially, they perform worse on earlier tasks. Existing methods mitigate catastrophic forgetting by data replay, parameter freezing, or regularization. However, these methods lack semantic awareness of internal knowledge distribution in LLMs. As a result, they cannot distinguish parameters that should be preserved or updated. We propose an attribution-guided continual fine-tuning framework for LLMs. Our method estimates task-specific, element-wise parameter importance in each Transformer layer and uses these scores to modulate gradients. Parameters important to previous tasks receive smaller updates, while less relevant ones remain plastic for learning new tasks. Experiments on continual learning benchmarks show that our method consistently outperforms baselines, achieving better retention of old tasks while maintaining competitive performance on new tasks.
### Title:
          ViTok-v2: Scaling Native Resolution Auto-Encoders to 5 Billion Parameters
 - **Authors:** Philippe Hansen-Estruch, Jiahui Chen, Vivek Ramanujan, Orr Zohar, Yan Ping, Animesh Sinha, Markos Georgopoulos, Edgar Schoenfeld, Ji Hou, Felix Juefei-Xu, Sriram Vishwanath, Ali Thabet
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformer (ViT) autoencoders have emerged as compelling tokenizers for images, offering improved reconstruction over convolutional tokenizers. However, existing ViT tokenizers cannot explore this landscape as performance degrades outside training resolutions, and reliance on adversarial losses prevents stable scaling. ViTok (Hansen-Estruch et al., 2025) found that the compression ratio r mediates a reconstruction-generation trade-off where lower r means better reconstructions but harder generations, so improving tokenizer reconstruction is key to more Pareto-optimal tokenizers. We introduce ViTok-v2, which addresses these limitations with native resolution support via NaFlex for generalization across resolutions and aspect ratios, and a novel DINOv3 perceptual loss that replaces both LPIPS and GAN objectives for stable training at any scale. ViTok-v2 is trained on about 2B images and scaled to 5B parameters, the largest image autoencoder to date. ViTok-v2 matches or exceeds state-of-the-art reconstruction at 256p and outperforms all baselines at 512p and above. In joint scaling experiments with flow matching generators, we show that scaling both the autoencoder and the generator advances the Pareto frontier of this trade-off.
### Title:
          A Multi-Head Attention Approach for SLA Compliance Monitoring in Data Centers
 - **Authors:** Omanshu Thapliyal
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Service level agreements (SLAs) in data center colocation contracts define precise thresholds for power, temperature, and humidity, with tiered violation penalties expressed as credits against monthly recurring charges. Traditional reactive monitoring detects breaches only after they occur, limiting remediation opportunities. We present a framework that encodes SLA rules as structured JSON objects to generate training data without manual annotation. We train a per-customer multi-head transformer model in which each attention head specializes in one SLA rule, learning temporal dependencies that precede violations by 30 minutes. Post-training, the inference service emits structured prediction events transformed into three role-specific views: finance schemas exposing credit liability, operations schemas surfacing risk scores and recommended interventions, and compliance schemas bundling predictions with immutable telemetry signatures for audit. By aligning model architecture directly with contractual obligations, this framework enables operators to anticipate SLA breaches, prioritize corrective actions, and minimize financial penalties.
### Title:
          LAMP: Localization Aware Multi-camera People Tracking in Metric 3D World
 - **Authors:** Nan Yang, Julian Straub, Fan Zhang, Richard Newcombe, Jakob Engel, Lingni Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tracking 3D human motion from egocentric multi-camera headset is challenged by severe egomotion, partial visibility or occlusions and lack of training data. Existing methods designed for monocular video often require static or slowly-moving cameras and cannot efficiently leverage multi-view, calibrated and localized input. This makes them brittle and prone to fail on dynamic egocentric captures. We propose LAMP (Localization Aware Multi-camera People Tracking): a novel, simple framework to solve this via early disentanglement of observer and target motion. LAMP introduces a two-step process. First, we leverage the known device 6 DoF motion and calibration to convert detected 2D body keypoints from all cameras over a temporal window into a unified 3D world reference frame. Second, an end-to-end-trained spatio-temporal transformer fits 3D human motion directly to this 3D ray cloud. This "lift-then-fit" approach allows LAMP to learn and leverage a natural human motion prior in the world-space, as well as providing an elegant framework to flexibly incorporate information from multiple temporally asynchronous, partially observing and moving cameras. LAMP achieves state-of-the-art results on monocular benchmarks, while significantly outperforming baselines for our targeted egocentric setting.
### Title:
          On Semantic Loss Fine-Tuning Approach for Preventing Model Collapse in Causal Reasoning
 - **Authors:** Pratik Deshmukh, Atirek Gupta
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Standard fine-tuning of transformer models on causal reasoning tasks leads to catastrophic model collapse, where models learn trivial solutions such as always predicting "Yes" or "No" regardless of input structure. We demonstrate that fine-tuning Gemma 270M on transitivity and d-separation tasks without semantic loss results in 100% collapse rate, with models achieving misleadingly high accuracy (73.9%) while learning no causal reasoning. We propose a semantic loss function with graph-based logical constraints and dynamic lambda scheduling that prevents this collapse. Our approach achieves 70.4% accuracy on transitivity tasks and 68.6% on d-separation tasks with stable, context-dependent predictions, representing a 42.7% improvement over collapsed baselines. Adversarial evaluation on 1,000 structural reasoning samples shows semantic models achieve 67-70% accuracy while collapsed models fail catastrophically at 43-71%. We validate our findings through comprehensive benchmarking on 200,000+ evaluation samples across five model variants, demonstrating that semantic loss is essential and not optional, for stable causal reasoning in transformers.
### Title:
          A Robust Foundation Model for Conservation Laws: Injecting Context into Flux Neural Operators via Recurrent Vision Transformers
 - **Authors:** Taeyoung Kim, Joon-Hyuk Ko
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose an architecture that augments the Flux Neural Operator (Flux NO), which combines the classical finite volume method (FVM) with neural operators, with ViT-based context injection. Our model is formulated as a hypernetwork: it extracts solution dynamics over a finite temporal window, encodes them with a recurrent Vision Transformer, and generates the parameters of a context-conditioned neural operator. This enables the model to infer and solve conservation laws without explicit access to the governing equation or PDE coefficients. Experimentally, we show that the proposed method preserves the robustness, generalization ability, and long-time prediction advantages of Flux NO over standard neural operators, while delivering reliable numerical solutions across a broad range of conservative systems, including previously unseen fluxes. Our code is available at this https URL.
### Title:
          Shortcut Solutions Learned by Transformers Impair Continual Compositional Reasoning
 - **Authors:** William T. Redman, Erik C. Johnson, Brian Robinson
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Identifying and exploiting common features across domains is at the heart of the human ability to make analogies, and is believed to be crucial for the ability to continually learn. To do this successfully, general and flexible computational strategies must be developed. While the extent to which Transformer neural network models can perform compositional reasoning has been the subject of intensive recent investigation, little work has been done to systematically understand how well these models can leverage their representations to learn new, related experiences. To address this gap, we expand the previously developed Learning Equality and Group Operations (LEGO) framework to a continual learning (CL) setting ("continual LEGO"). Using this continual LEGO experimental paradigm, we study the capability of feedforward and recurrent Transformer models to perform CL. We find that BERT, a canonical feedforward Transformer model, learns shortcut solutions that limits its ability to generalize and prevents strong forward transfer to new experiences. In contrast, we find evidence supporting the hypothesis that ALBERT, a recurrent version of BERT, learns a For loop-esque solution, which leads to better CL performance. When applying BERT and ALBERT models to a CL setting that requires composition across experiences, we find that both model families fail. Our investigation suggests that ALBERT models can have their performance drop rescued by use of training strategies that combine data across experiences, but this is not true for BERT models, where a detrimental shortcut solution becomes entrenched with initial training. Our results demonstrate that the recurrent ALBERT model may have an inductive bias better suited for CL and motivate future investigation of the interplay between Transformer architecture and computational solutions that emerge in modern models and tasks.
### Title:
          An extremely coarse feedback signal is sufficient for learning human-aligned visual representations
 - **Authors:** Yash Mehta, Michael F. Bonner
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Artificial neural networks trained on visual tasks develop internal representations resembling those of the primate visual system, a discovery that has guided a decade of computational neuroscience. Research on building brain-aligned models has progressively embraced finer-grained supervisory signals, from object classification to contrastive self-supervised objectives that maximize distinctions among individual images, yet the role of supervisory signal granularity on brain alignment remains largely unexamined. Here we systematically investigate how the coarseness of a learning signal shapes representational alignment with human vision. We parametrically vary the level of signal granularity using a data-driven approach that partitions a set of training images into varied numbers of categories (2, 4, 8, 16, ..., 64) via PCA-based splits of pretrained embeddings. We train hundreds of neural networks across convolutional and transformer architectures on these coarse classification tasks and compare their representations to macaque electrophysiology recordings and human fMRI responses. We find that networks trained to distinguish as few as 8 broad categories learn representations that match or exceed the neural alignment of models distinguishing 1,000-classes. Even more strikingly, these coarsely trained networks align more closely with human perceptual similarity judgments than all other models evaluated, including networks trained with fine-grained supervision or self-supervision as well as leading large-scale vision models. These results demonstrate that human-like visual representations emerge from remarkably coarse feedback, reframing what learning signals vision may require and opening a path toward building AI systems that are more aligned with human perception.
### Title:
          MUSE: Resolving Manifold Misalignment in Visual Tokenization via Topological Orthogonality
 - **Authors:** Panqi Yang, Haodong Jing, Jiahao Chao, Tingyan Xiang, Li Lin, Yao Hu, Yang Luo, Yongqiang Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unified visual tokenization faces a fundamental trade-off between high-fidelity pixel reconstruction (spatial equivariance) and semantic abstraction (conceptual invariance). We attribute this conflict to Manifold Misalignment: naive joint optimization induces opposing gradients, creating a zero-sum game between reconstruction and perception. To address this, we propose MUSE, a framework based on Topological Orthogonality. By treating Structure as an orthogonal bridge, MUSE decouples optimization within Transformers: structural gradients refine attention topology, while semantic gradients update feature values. This turns destructive interference into Mutual Reinforcement. Experiments show that MUSE breaks the trade-off, achieving state-of-the-art generation quality (gFID 3.08) and surpassing its teacher InternViT-300M in linear probing (85.2\% vs. 82.5\%), demonstrating that structurally aligned reconstruction can enhance semantic perception. Code is available at this https URL.
### Title:
          Large Vision-Language Models Get Lost in Attention
 - **Authors:** Gongli Xi, Ye Tian, Mengyu Yang, Huahui Yi, Liang Lin, Xiaoshuai Hao, Kun Wang, Wendong Wang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite the rapid evolution of training paradigms, the decoder backbone of large vision--language models (LVLMs) remains fundamentally rooted in the residual-connection Transformer architecture. Therefore, deciphering the distinct roles of internal modules is critical for understanding model mechanics and guiding architectural optimization. While prior statistical approaches have provided valuable attribution-based insights, they often lack a unified theoretical basis. To bridge this gap, we propose a unified framework grounded in information theory and geometry to quantify the geometric and entropic nature of residual updates. Applying this unified framework reveals a fundamental functional decoupling: Attention acts as a subspace-preserving operator focused on reconfiguration, whereas FFNs serve as subspace-expanding operators driving semantic innovation. Strikingly, further experiments demonstrate that replacing learned attention weights with predefined values (e.g., Gaussian noise) yields comparable or even superior performance across a majority of datasets relative to vanilla models. These results expose severe misallocation and redundancy in current mechanisms, suggesting that state-of-the-art LVLMs effectively ``get lost in attention'' rather than efficiently leveraging visual context.
### Title:
          CFE-PPAR: Compression-friendly encryption for privacy-preserving action recognition leveraging video transformers
 - **Authors:** Haiwei Lin, Shoko Imaizumi, Hitoshi Kiya
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Privacy-preserving action recognition (PPAR) enables machines to understand human activities in videos without revealing sensitive visual content. Among the various strategies for PPAR, encryption-based methods achieve strong privacy protection while maintaining high recognition performance. However, these methods lead to a catastrophic decrease in recognition performance and visual quality when the encrypted videos are compressed. That is, the previous methods are not compression-friendly. To address these issues, in this paper, we propose the first compression-friendly encryption method for PPAR, called CFE-PPAR. In CFE-PPAR, videos encrypted with secret keys can be directly recognized by a video transformer, which uses parameters transformed by the same keys as those used for video encryption. In experiments, it is verified that CFE-PPAR outperforms previous methods on the UCF101 and HMDB51 datasets under Motion-JPEG and H.264 compression.
### Title:
          Adaptive Physical-Facial Representation Fusion via Subject-Invariant Cross-Modal Prompt Tuning for Video-Based Emotion Recognition
 - **Authors:** Xiwen Luo, Jia Li, Rencheng Song, Yu Liu, Juan Cheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Emotion recognition from facial videos enables non-contact inference of human emotional states. Although facial expressions are widely used cues, they cannot fully reflect intrinsic affective states. Remote photoplethysmography (rPPG) provides complementary physiological information, but it is highly susceptible to noise and inter-subject variability, limiting generalization to unseen individuals. Existing multimodal methods combine facial and rPPG features, yet their fusion strategies often disrupt pretrained facial representations and lack explicit mechanisms to suppress subject-specific variations. To address these issues, we propose a subject-invariant cross-modal prompt-tuning framework for video-based emotion recognition. Specifically, rPPG waveforms are transformed into noise-robust time-frequency representations (TFRs), from which modality-complementary prompts are generated to modulate facial tokens within a frozen Vision Transformer (ViT). This design enables effective cross-modal interaction while preserving the generalizable facial representations learned by the pretrained backbone. In addition, we introduce a decoupled shared-specific adapter (DSSA) into each ViT layer to explicitly separate subject-shared and subject-specific components, thereby improving cross-subject generalization. Experiments on the MAHNOB-HCI and DEAP benchmarks demonstrate that the proposed method consistently outperforms strong baselines in both recognition accuracy and generalization ability, highlighting its effectiveness for video-based emotion recognition.
### Title:
          Budgeted Attention Allocation: Cost-Conditioned Compute Control for Efficient Transformers
 - **Authors:** Amrit Nidhi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers usually expose one inference cost per trained model, while deployed systems often need multiple cost-quality operating points. We study Budgeted Attention Allocation, a monotone head-gating mechanism conditioned on a requested attention budget. Dense warm-starting is important for stability: on a robust synthetic sequence task, one budgeted model reaches 99.7% accuracy at 0.303 estimated attention cost and 100.0% accuracy at 0.504 cost. On held-out AG News with a custom word-level transformer, hard-gate adaptation turns soft cost control into measured single-thread CPU speed, reaching 82.1% accuracy with 1.28x speedup at budget 0.50. In pretrained BERT-Mini AG News, budgeted structural pruning reaches 87.6% accuracy with 1.20x speedup at budget 0.50; a validation-ranked zero-shot dense post-hoc structural baseline reaches 86.1%, and one recovery epoch raises that per-budget specialist to 87.9%. On DBpedia14, BERT-Mini budgeted gates reach 97.4% at exact budget 0.50 versus 96.6% for dense full attention. Static fixed-budget gates and recovered dense specialists remain strong. The contribution is therefore not universal dominance, but a reproducible feasibility study of one controllable checkpoint across budgets that can trade attention cost for accuracy and be converted into measured structural speedups on small CPU benchmarks.
### Title:
          TriRelVLA: Triadic Relational Structure for Generalizable Embodied Manipulation
 - **Authors:** Hanyu Zhou, Chuanhao Ma, Gim Hee Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language-action (VLA) models perform well on training-seen robotic tasks but struggle to generalize to unseen scenes and objects. A key limitation lies in their implicit visual representations, which entangle object appearance, background, and scene layout. This makes policies sensitive to visual variations. Prior work improves transferability through structured intermediate representations that objectify visual content. However, these representations mainly capture scene semantics instead of action-relevant relations. As a result, action prediction remains tied to appearance statistics. We observe that manipulation actions depend on the object-hand-task relational structure, which governs interactions among task requirements, robot states, and object properties. Based on this observation, we propose TriRelVLA, a triadic relational VLA framework for generalizable embodied manipulation. Our approach consists of three components: 1) We construct explicit object-hand-task triadic representations from multimodal inputs as relational primitives. 2) We build a task-grounded relational graph. Task-guided cross-attention forms nodes, and a relation-aware graph transformer models interactions among them. 3) We perform relation-conditioned action generation. The relational structure is compressed into a bottleneck space and projected into the LLM for action prediction. This triadic relational bottleneck reduces reliance on appearance statistics and enables transfer across scenes, objects, and task compositions. We further introduce a real-world robotic dataset for fine-tuning. Experiments show strong performance on fine-tuned tasks and clear gains in cross-scene, cross-object, and cross-task generalization.
### Title:
          $\mathcal{B}^{3}$-Net: Controlled Posterior Bridge Learning for Multi-Task Dense Prediction
 - **Authors:** Meihua Zhou, Li Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-task dense prediction solves complementary pixel-level tasks in a unified model, such as semantic segmentation, depth estimation, surface normal estimation, and edge detection. Existing decoder-side interactions use attention, prompts, routing, diffusion, Mamba, or bridge features to exchange task evidence, but most of them organize this evidence implicitly. They usually fuse task features by similarity or affinity, without explicitly modeling that evidence reliability varies across tasks and spatial locations. As a result, unreliable evidence may contaminate the shared representation and intensify negative transfer. We propose $\mathcal{B}^{3}$-Net, a controlled posterior bridge learning framework for multi-task dense prediction. Our method decomposes decoder-side interaction into reliability estimation, posterior bridge construction, and bounded redistribution. The Precision Field Estimator estimates patch-wise evidence precision from task-reference alignment and local variation. The Posterior Bridge Operator builds a precision-weighted posterior bridge through heteroscedastic evidence fusion, yielding a shared state more reliable than uniform or heuristic mixtures. The Contractive Dispatch Operator redistributes the bridge to each task branch through a bounded update, reducing uncontrolled feature injection. Experiments on NYUD-v2, PASCAL-Context, and Cityscapes show that $\mathcal{B}^{3}$-Net achieves competitive or superior trade-offs over representative CNN-, Transformer-, diffusion-, Mamba-, and bridge-feature-based methods. Backbone-matched comparisons and extensive analyses further verify that the gains arise from controlled posterior bridge learning rather than backbone capacity or decoder scale.
### Title:
          HyperLens: Quantifying Cognitive Effort in LLMs with Fine-grained Confidence Trajectory
 - **Authors:** Chengda Lu, Xiaoyu Fan, Wei Xu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Large Language Models (LLMs) achieve strong performance across diverse tasks, their inference dynamics remain poorly understood because of the limited resolution of existing analysis tools. In this work, we identify an intrinsic magnification mechanism in transformer architectures: deeper layers inherently magnify the small changes of layer-wise confidence, providing a fine-grained confidence trajectory. Building on this insight, we introduce HyperLens, a high-resolution probe designed to trace confidence trajectories and quantify the cognitive effort during inference. Across LLMs and datasets, HyperLens reveals a consistent divergence in confidence trajectories that separates complex from simple tasks. We abstract this pattern into a quantitative cognitive effort metric. Our analysis reveals a fundamental principle: complex tasks consistently require higher cognitive effort. Finally, we provide a mechanistic diagnosis of a common side effect of standard Supervised Fine-Tuning (SFT): it can reduce cognitive effort and consequently degrade performance on in-domain tasks.
### Title:
          CircuitFormer: A Circuit Language Model for Analog Topology Design from Natural Language Prompt
 - **Authors:** Md Touhidul Islam, Sujan Kumar Saha, Farimah Farahmandi, Mark Tehranipoor
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automating analog circuit design remains a longstanding challenge in Electronic Design Automation (EDA). While Transformer-based Large Language Models (LLMs) have revolutionized software code generation, their application to analog hardware design is hindered by two critical limitations: (i) the scarcity of analog design datasets containing natural language description of a design and its corresponding netlist, and (ii) the inefficiency of general-purpose tokenizers (e.g., Byte Pair Encoding (BPE)) in capturing the inherent graph structure of circuits. To bridge this gap, first, we curate the largest annotated dataset of analog circuit netlists to date, comprising 31,341 netlist-natural language description pairs across all major circuit classes. Furthermore, we propose Circuit Tokenizer (CKT), a novel circuit graph tokenizer designed to encode netlist connectivity by explicitly mining frequent subcircuits. In terms of scalability, CKT overcomes the bottleneck of prior circuit graph serialization methods where vocabulary size scales linearly with maximum number of components in the dataset, n_max, (O(n_max)); instead, CKT decouples vocabulary growth from circuit complexity, achieving a constant O(1) complexity. Empirically, CKT outperforms standard BPE on circuit topology representation, reducing sequence length by 57% and achieving a 2.3x superior compression ratio using a compact, fixed vocabulary of size 512. Leveraging this optimized tokenization, we train a circuit-specific language model, CircuitFormer, a 511M parameter encoder-decoder transformer. Our model achieves 100% syntactic correctness and an 83% functional success rate across all major analog circuit categories, outperforming state-of-the-art open-source LLMs by 10% and 14%, respectively, while requiring 240x fewer parameters. The dataset is publicly available at this https URL.
### Title:
          Sheet as Token: A Graph-Enhanced Representation for Multi-Sheet Spreadsheet Understanding
 - **Authors:** Yiming Lei, Yiqi Wang, Yujia Zhang, Bo Guan, Depei Zhu, Chunhui Wang, Zhuonan Hao, Tianyu Shi
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Workbook-scale spreadsheet understanding is increasingly important for language-model-based data analysis agents, but remains challenging because relevant information is often distributed across multiple sheets with heterogeneous schemas, layouts, and implicit relationships. Existing retrieval-augmented approaches typically decompose spreadsheets into rows, columns, or blocks to improve scalability; however, such chunk-centric representations can fragment worksheets into isolated text spans and weaken global sheet-level semantics. We propose Sheet as Token, a graph-enhanced framework that treats each worksheet as a unified semantic unit for multi-sheet spreadsheet retrieval. Our method extracts schema-aware records from sheet names, column headers, representative values, and layout features, and encodes each worksheet into a compact dense token. Given a natural-language query, a Graph Retriever constructs a query-specific candidate graph over sheet tokens using semantic, query-conditioned, schema-consistency, and shape-compatibility relations, and composes these channels through a multi-stage graph transformer to retrieve supporting sheet sets. Experiments on a constructed multi-sheet spreadsheet corpus show that sheet-level tokenization learns stable representations, and that graph-enhanced cross-sheet reasoning improves listwise retrieval over a shallow graph baseline with limited additional graph-side computation. These results suggest that sheet-level tokenization is a promising abstraction for scalable multi-sheet spreadsheet understanding.
### Title:
          MDN: Parallelizing Stepwise Momentum for Delta Linear Attention
 - **Authors:** Yulong Huang, Xiang Liu, Hongxiang Huang, Xiaopeng Lin, Zunchang Liu, Xiaowen Chu, Zeke Xie, Bojun Cheng
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Linear Attention (LA) offers a promising paradigm for scaling large language models (LLMs) to long sequences by avoiding the quadratic complexity of self-attention. Recent LA models such as Mamba2 and GDN interpret linear recurrences as closed-form online stochastic gradient descent (SGD), but naive SGD updates suffer from rapid information decay and suboptimal convergence in optimization. While momentum-based optimizers provide a natural remedy, they pose challenges in simultaneously achieving training efficiency and effectiveness. To address this, we develop a chunkwise parallel algorithm for LA with a stepwise momentum rule by geometrically reordering the update coefficients. Further, from a dynamical systems perspective, we analyze the momentum-based recurrence as a second-order system that introduces complex conjugate eigenvalues. This analysis guides the design of stable gating constraints. The resulting model, Momentum DeltaNet (MDN), leverages Triton kernels to achieve comparable training throughput with competitive linear models such as Mamba2 and KDA. Extensive experiments on the 400M and 1.3B parameter models demonstrate consistent performance improvements over strong baselines, including Transformers, Mamba2 and GDN, across diverse downstream evaluation benchmarks. Code: this https URL .
### Title:
          Do Neural Operators Forget Geometry? The Forgetting Hypothesis in Deep Operator Learning
 - **Authors:** Yanming Xia, Angelica I. Aviles-Rivero
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural operators perform well on structured domains, yet their behaviour on irregular geometries remains poorly understood. We show that this limitation is not merely an encoding issue, but a depth-wise failure mode inherent to deep operator architectures. We formalise the Geometric Forgetting Hypothesis: due to the Markovian structure of operator layers and their reliance on global mixing mechanisms, neural operators progressively lose access to domain geometry as depth increases. Using layer-wise geometric probing, we demonstrate that both spectral and attention-based operators systematically lose geometric fidelity. We show that this geometric forgetting degrades accuracy, stability, and generalisation. To counteract it, we introduce a lightweight geometry memory injection mechanism that restores geometric constraints at intermediate depths with minimal architectural overhead. This simple intervention consistently mitigates forgetting and exposes a geometric shortcut instability in transformer-based operators, revealing that geometric retention is a structural requirement rather than a design choice.
### Title:
          Architecture-agnostic Lipschitz-constant Bayesian header and its application to resolve semantically proximal classification errors with vision transformers
 - **Authors:** Frederik Schäfer, Luis Mandl, Lars Kälber, Tim Ricken
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Label noise remains a critical bottleneck for the generalization of supervised deep learning models, particularly when errors are structured rather than random. Standard robust training methods often fail in the presence of such semantically proximal classification errors. This work presents an architecture-agnostic Lipschitz-constant Bayesian header that can be integrated into feature extractors such as vision transformers, yielding the bi-Lipschitz-constrained Bayesian Vision Transformer (LipB-ViT). In contrast to conventional Bayesian layers, our approach enforces spectral normalization on both the mean and log-variance of the variational weights, which promotes calibrated predictive uncertainty and mitigates noise amplification. We further propose a novel metric to jointly capture uncertainty and confidence across misclassification rates, as well as an adaptive arithmetic-mean fusion scheme that combines feature-space proximity with predictive uncertainty to detect corrupted labels outperforming the state of the art k-nearest neighbor based identification methods by more than 7% reaching a recall of more than 0.93 at 15% semantically misclassified labels. Although computational costs increase due to Monte Carlo sampling, the method offers plug-and-play compatibility with pre-trained backbones and consistent hyperparameters across domains, suggesting strong utility for high-stakes applications with variable annotation reliability. The stabilized confidence estimates serve as the foundation for an analysis pipeline that jointly assesses dataset quality and label noise, yielding a second novel metric for their combined quantification. Lastly, we systematically evaluate LipB-ViT under both structured (adversarial) and unstructured noise at inference time, demonstrating its robustness in realistic high-noise and attack scenarios. We compare its performance against baseline methods.
### Title:
          Backdoor Mitigation in Object Detection via Adversarial Fine-Tuning
 - **Authors:** Kealan Dunnett, Reza Arablouei, Dimity Miller, Volkan Dedeoglu, Raja Jurdak
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Backdoor attacks can implant malicious behaviours into deep models while preserving performance on clean data, posing a serious threat to safety-critical vision systems. Although backdoor mitigation has been studied extensively for image classification, defenses for object detection remain comparatively underdeveloped. Adversarial fine-tuning is a common backdoor mitigation approach in classification, but adapting it to detection is nontrivial as classification-oriented adversarial generation does not match the detection attack space, where attacks may cause object misclassification or disappearance, and standard detection losses can dilute the repair signal across many predictions. We address these challenges through a detection-aware adversarial fine-tuning framework for mitigating object-detection backdoors when the defender has access only to a compromised detector and a small clean dataset, without knowing the attack objective. For adversarial generation that does not require knowledge of the attack objective, we introduce soft-branch minimisation, which uses a soft gate to combine objectives aligned with misclassification and disappearance attacks, together with a detection-aware classification-loss maximisation. For targeted repair, we introduce a dual-objective fine-tuning loss applied to target-matched predictions, concentrating the defensive update on predictions most relevant to the backdoor behaviour. Experiments across CNN- and Transformer-based detectors show that our approach more effectively reduces attack success while preserving true detections, compared with classification-oriented baselines, and maintains competitive clean detection performance.
### Title:
          Training Transformers for KV Cache Compressibility
 - **Authors:** Yoav Gelberg, Yam Eitan, Michael Bronstein, Yarin Gal, Haggai Maron
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long-context language modeling is increasingly constrained by the Key-Value (KV) cache, whose memory and decode-time access costs scale linearly with the prefix length. This bottleneck has motivated a range of context-compression methods, from token-level summarization to recent optimization-based KV compression methods. These post-hoc methods operate on the KV cache of a fixed pretrained model, so their effectiveness is fundamentally limited by how well the model's internal representations can be compressed. In this work, we formalize the notion of KV compressibility and show that it is a property of the learned representations, rather than of the context alone. We prove that almost any sequence-to-vector function admits both highly compressible and inherently non-compressible transformer implementations, highlighting the need to guide transformers toward compressible representations during training. Motivated by this, we propose KV-Compression Aware Training (KV-CAT), a continued pretraining procedure that incentivizes the emergence of compressible representations. We introduce a train-time KV sparsification policy that masks KV slots during training. This forces the model to use fewer KV slots and encourages it to learn representations amenable to post-hoc compression. Empirically, we show that KV-CAT improves the quality-budget tradeoff of downstream compression methods across retrieval, long-context question answering, and perplexity-based evaluation of compressed-prefix continuation.
### Title:
          DiBA: Diagonal and Binary Matrix Approximation for Neural Network Weight Compression
 - **Authors:** Nobutaka Ono
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we propose DiBA (Diagonal and Binary Matrix Approximation), a compact matrix factorization for neural network weight compression. Many components of modern networks, including linear layers, $1\times1$ convolutions, attention projections, and embedding layers, have dense matrix weights. DiBA approximates $A\in\mathbb{R}^{m\times n}$ by $\widehat A=D_1B_1D_2B_2D_3$, where $D_1,D_2,D_3$ are diagonal matrices and $B_1,B_2$ are $0/1$ binary matrices. The intermediate dimension $k$ controls the trade-off between theoretical storage and approximation accuracy. For matrix-vector products, DiBA decomposes dense multiplication into three element-wise scaling operations and two binary mixing operations, reducing the floating-point multiplication count from $mn$ to $m+k+n$. For optimization, we introduce DiBA-Greedy, an alternating solver that combines closed-form least-squares updates for the diagonal factors with exact one-bit improvement tests for the binary factors. We also introduce DiBARD (DiBA with Retuning only Diagonal factors), which replaces dense-matrix layers by DiBA factors, freezes the binary matrices, and retunes only the diagonal entries on downstream data. This preserves compact binary mixing without discrete search during adaptation. On 40 dense weight matrices extracted from public pretrained models, DiBA-Greedy yields consistent SNR improvements as the theoretical storage ratio increases. After DiBA replacement in two component-replacement studies, DiBARD improves DistilBERT/WikiText masked-token accuracy from 0.4447 to 0.5210 and Speech Commands test accuracy for an Audio Spectrogram Transformer from 0.7684 to 0.9781 without reoptimizing the binary factors.
### Title:
          Does Synthetic Data Help? Empirical Evidence from Deep Learning Time Series Forecasters
 - **Authors:** Hugo Cazaux, Eyjólfur Ingi Ásgeirsson, Hlynur Stefánsson
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Synthetic data has transformed language model training, yet its role in time series forecasting remains poorly understood. We present a large-scale empirical study: nine experiment groups, 4,218 runs systematically evaluating synthetic time series augmentation across five architectures, four synthetic signals and seven datasets. The effect is sharply architecture-conditional: channel-mixing models (TimesNet, iTransformer) benefit in the majority of trials, while channel-independent models (DLinear, PatchTST) are consistently degraded. In selected low-resource settings the gains are striking: TimesNet trained on only 10\% of Weather data with synthetic augmentation surpasses the full-data baseline (4 of 16 sparsity-dataset combinations). Averaged across all architectures, augmentation hurts in 67\% of trials. We further find that only the Seasonal-Trend generator reliably helps across the tested benchmarks, and that hard curriculum switching is actively harmful (+24\% MSE degradation). These results provide concrete, actionable guidelines on how to use synthetic data: use synthetic augmentation with channel-mixing architectures, use gradual annealing schedules, and treat low-resource augmentation as architecture- and dataset-dependent. Code is available at \href{this https URL}
### Title:
          Normalized Architectures are Natively 4-Bit
 - **Authors:** Maxim Fishman, Brian Chmiel, Ron Banner, Daniel Soudry, Boris Ginsburg
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Training large language models at 4-bit precision is critical for efficiency. We show that nGPT, an architecture that constrains weights and hidden representations to the unit hypersphere, is inherently more robust to low-precision arithmetic. This removes the need for interventions-such as applying random Hadamard transforms and performing per-tensor scaling calculations-to preserve model quality, and it enables stable end-to-end NVFP4 training. We validate this approach on both a 1.2B dense model and hybrid (Mamba-Transformer) MoE models of up to 3B/30B parameters. We trace this robustness to the dot product: while quantization noise remains largely uncorrelated in both standard and normalized architectures, the signal behaves differently. In nGPT, the hypersphere constraint enhances weak positive correlations among the element-wise products, leading to a constructive accumulation of the signal across the hidden dimension while the noise continues to average out. This yields a higher effective signal-to-noise ratio and a flatter loss landscape, with the effect strengthening as the hidden dimension grows, suggesting increasing advantages at scale. A reference implementation is available at this https URL
### Title:
          Navigating by Old Maps: The Pitfalls of Static Mechanistic Localization in LLM Post-Training
 - **Authors:** Hang Chen, Jiaying Zhu, Hongyang Chen, Hongxu Liu, Xinyu Yang, Wenya Wang
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The "Locate-then-Update" paradigm has become a predominant approach in the post-training of large language models (LLMs), identifying critical components via mechanistic interpretability for targeted parameter updates. However, this paradigm rests on a fundamental yet unverified assumption: can mechanisms derived from current static parameters reliably guide future dynamic parameter updates? To investigate this, we systematically track the structural evolution of Transformer circuits throughout the supervised fine-tuning (SFT) process, revealing the underlying dynamics of task mechanisms. We introduce three novel metrics-Circuit Distance, Circuit Stability, and Circuit Conflict-to analyze circuit evolution across three dimensions: neural migration, semantic stability, and cross-task interference. Our empirical results reveal that circuits inherently exhibit "Free Evolution" during parameter updates. Consequently, static mechanisms extracted from current states inevitably suffer from temporal latency, making them fundamentally inadequate for guiding future states. Moreover, by deconstructing the "illusion of effectiveness" in existing methods, this work underscores the necessity of "foresight" in mechanistic localization and proposes a predictive framework for future research.
### Title:
          PoTAcc: A Pipeline for End-to-End Acceleration of Power-of-Two Quantized DNNs
 - **Authors:** Rappy Saha, Jude Haris, Nicolas Bohm Agostini, David Kaeli, José Cano
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Machine Learning (cs.LG); Performance (cs.PF)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Power-of-two (PoT) quantization significantly reduces the size of deep neural networks (DNNs) and replaces multiplications with bit-shift operations for inference. Prior work has shown that PoT-quantized DNNs can preserve accuracy for tasks such as image classification; however, their performance on resource-constrained edge devices remains insufficiently understood. While general-purpose edge CPUs and GPUs do not provide optimized backends for bit-shift operations, custom hardware accelerators can better exploit PoT quantization by implementing dedicated shift-based processing elements. However, deploying PoT-quantized models on such accelerators is challenging due to limited support in existing inference frameworks. In addition, the impact of different PoT quantization strategies on hardware design, performance, and energy efficiency during full inference has not been systematically explored. To address these challenges, we propose PoTAcc, an open-source end-to-end pipeline for accelerating and evaluating PoT-quantized DNNs on resource-constrained edge devices. PoTAcc enables seamless preparation and deployment of PoT-quantized models via TensorFlow Lite (TFLite) across heterogeneous platforms, including CPU-only systems and hybrid CPU-FPGA systems with custom accelerators. We design shift-based processing element (shift-PE) accelerators for three PoT quantization methods and implement them on two FPGA platforms. We evaluate accuracy, performance, energy efficiency, and resource utilization across a range of models, including CNNs and Transformer-based architectures. Results show that our CPU-accelerator design achieves up to 3.6x speedup and 78% energy reduction compared to CPU-only execution for PoT-quantized DNNs on PYNQ-Z2 and Kria boards. The code will be publicly released at this https URL
### Title:
          Metonymy in vision models undermines attention-based interpretability
 - **Authors:** Ananthu Aniraj, Cassio F. Dantas, Dino Ienco, Massimiliano Mancini, Diego Marcos
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Part-based reasoning is a classical strategy to make a computer vision model directly focus on the object parts that are relevant to the downstream task. In the context of deep learning, this also serves to improve by-design interpretability, often by using part-centric attention mechanisms on top of a latent image representation provided by a standard, black-box model. This approach is based on a locality assumption: that the latent representation of an object part encodes primarily information about the corresponding image region. In this work, we test this basic assumption, measuring intra-object leakage in vision models using part-based attribute annotations. Through a comprehensive experimental evaluation, we show that modern pretrained vision transformers violate the locality assumption and exhibit a strong intra-object leakage, in which each part encodes information from the whole object, a visual metonymy that compromises the faithfulness of attention-based interpretable-by-design methods for part-based reasoning, ultimately rendering them uninterpretable. In addition, we establish an upper bound using a two-stage approach that prevents leakage by design. We then show that this inherently disentangled feature extraction improves attribute-driven part discovery on a variety of tasks, confirming the practical impact of intra-object leakage. Our results uncover a neglected issue affecting the interpretability of part-based representations, such as those in CBMs relying on part-centric concepts, highlighting that two-stage approaches offer a promising way to mitigate it.
### Title:
          Beyond Autoregressive RTG: Conditioning via Injection Outside Sequential Modeling in Decision Transformer
 - **Authors:** Yongyi Wang, Hanyu Liu, Lingfeng Li, Bozhou Chen, Ang Li, Qirui Zheng, Xionghui Yang, Chucai Wang, Wenxin Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Decision Transformer (DT) formulates offline reinforcement learning as autoregressive sequence modeling, achieving promising results by predicting actions from a sequence of Return-to-Go (RTG), state, and action tokens. However, RTG is a scalar that summarizes future rewards, containing far less information than typical state or action vectors, yet it consumes the same computational budget per token. Worse, the self-attention cost of Transformers grows quadratically with sequence length, so including RTG as a separate token adds unnecessary overhead. We propose SlimDT, which removes RTG from the autoregressive sequence. Instead, we inject RTG information into the state representations before the sequential modeling step, allowing the Transformer to process only a compact (state, action) sequence. This reduces the sequence length by one-third, directly improving inference efficiency. On the D4RL benchmark, SlimDT surpasses standard DT across various tasks and achieves performance comparable to existing state-of-the-art methods. Decoupling a sparse conditioning signal from an information-rich sequence thus yields both computational gains and higher task performance.
### Title:
          Dynamic Pondering Sparsity-aware Mixture-of-Experts Transformer for Event Stream based Visual Object Tracking
 - **Authors:** Shiao Wang, Xiao Wang, Duoqing Yang, Wenhao Zhang, Bo Jiang, Lin Zhu, Yonghong Tian, Bin Luo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite significant progress, RGB-based trackers remain vulnerable to challenging imaging conditions, such as low illumination and fast motion. Event cameras offer a promising alternative by asynchronously capturing pixel-wise brightness changes, providing high dynamic range and high temporal resolution. However, existing event-based trackers often neglect the intrinsic spatial sparsity and temporal density of event data, while relying on a single fixed temporal-window sampling strategy that is suboptimal under varying motion dynamics. In this paper, we propose an event sparsity-aware tracking framework that explicitly models event-density variations across multiple temporal scales. Specifically, the proposed framework progressively injects sparse, medium-density, and dense event search regions into a three-stage Vision Transformer backbone, enabling hierarchical multi-density feature learning. Furthermore, we introduce a sparsity-aware Mixture-of-Experts module to encourage expert specialization under different sparsity patterns, and design a dynamic pondering strategy to adaptively adjust the inference depth according to tracking difficulty. Extensive experiments on FE240hz, COESOT, and EventVOT demonstrate that the proposed approach achieves a favorable trade-off between tracking accuracy and computational efficiency. The source code will be released on this https URL.
### Title:
          Mean Mode Screaming: Mean--Variance Split Residuals for 1000-Layer Diffusion Transformers
 - **Authors:** Pengqi Lu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scaling Diffusion Transformers (DiTs) to hundreds of layers introduces a structural vulnerability: networks can enter a silent, mean-dominated collapse state that homogenizes token representations and suppresses centered variation. Through mechanistic auditing, we isolate the trigger event of this collapse as Mean Mode Screaming (MMS). MMS can occur even when training appears stable, with a mean-coherent backward shock on residual writers that opens deep residual branches and drives the network into a mean-dominated state. We show this behavior is driven by an exact decomposition of these gradients into mean-coherent and centered components, compounded by the structural suppression of attention-logit gradients through the null space of the Softmax Jacobian once values homogenize. To address this, we propose Mean-Variance Split (MV-Split) Residuals, which combine a separately gained centered residual update with a leaky trunk-mean replacement. On a 400-layer single-stream DiT, MV-Split prevents the divergent collapse that crashes the un-stabilized baseline; it tracks close to the baseline's pre-crash trajectory while remaining substantially better than token-isotropic gating methods such as LayerScale across the full schedule. Finally, we present a 1000-layer DiT as a scale-validation run at boundary scales, establishing that the architecture remains stably trainable at extreme depth.
### Title:
          In-Context Black-Box Optimization with Unreliable Feedback
 - **Authors:** Nicolas Samuel Blumer, Julien Martinelli, Samuel Kaski
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Black-box optimization in science and engineering often comes with side information: experts, simulators, pretrained predictors, or heuristics can suggest which candidates look promising. This information can accelerate search, but it can also be biased, input-dependent, or misleading. Feedback-aware BO methods typically handle one task at a time, limiting their ability to generalize over multiple sources of feedback. In-context optimizers address cross-task adaptation, but usually assume that optimization history is the only available signal at test time. We study feedback-informed in-context black-box optimization (FICBO), where a pretrained optimizer conditions on both the observed history and cheap auxiliary feedback for the current candidate set. We introduce a structured feedback prior that models how feedback sources vary in their access, relevance, and distortion relative to the true objective, and use it to pretrain a feedback-aware transformer. At test time, the model estimates source reliability in context by comparing observed objective values with auxiliary signals, improving query selection. On synthetic and real-world tasks, FICBO effectively exploits informative feedback while remaining robust to weak or misleading sources, improving over other baselines. Empirical investigations further illustrate how the model perceives test-time sources, offering insights into its interpretability and decision-making process.
### Title:
          Federation of Experts: Communication Efficient Distributed Inference for Large Language Models
 - **Authors:** Muhammad Shahir Abdurrahman, Chun Deng, Azalia Mirhoseini, Philip Levis
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mixture of experts has emerged as the primary mechanism for making Large Language Models (LLMs) computationally efficient. However, in distributed settings, communicating token embeddings between experts is a significant bottleneck. We present the novel Federation of Experts (FoE) architecture. FoE restructures the MoE block of a transformer layer into multiple MoE clusters. Each cluster is responsible for only one of the KV heads and expert parallelism is applied between those experts. Between clusters, a sum synchronizes the post-attention residuals, which then drives routing and dispatch for the next MoE block. In a single-node setting, FoE completely eliminates all-to-all communication as all experts within a group are contained on the same GPU. In multi-node settings, FoE confines all-to-all communication to the intra-node fabric, thus significantly reducing communication overhead. An implementation of FoE finds that on LongBench, FoE significantly improves inference throughput and latency in both single-node and multi-node settings, reducing the end-to-end forward-pass latency by up to 5.2x, TTFT by 3.62x, and TBT by 1.95x. It does so while achieving comparable generation quality to a mixture of experts model of the same size and training configuration.
### Title:
          Taming the Entropy Cliff: Variable Codebook Size Quantization for Autoregressive Visual Generation
 - **Authors:** Bowen Zheng, Weijian Luo, Guang Yang, Colin Zhang, Tianyang Hu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Most discrete visual tokenizers rely on a default design: every position in the sequence shares the same codebook. Researchers try to scale the codebook size $K$ to get better reconstruction performance. Such a constant-codebook design hits a fundamental information-theoretic limit. We observe that the per-position conditional entropy of the training set decays so quickly along the sequence that, after a few positions, the conditional distribution becomes essentially deterministic. On ImageNet with $K=16384$, this happens within only 2 out of 256 positions, turning the remaining 254 into a memorization problem. We call this phenomenon the Entropy Cliff and formalize it with a simple expression: $t^{*} = \lceil \log_2 N / \log_2 K \rceil$. Interestingly, this phenomenon is not observed in language, as its natural structure keeps the effective entropy per position well below the codebook capacity. To address this, we propose Variable Codebook Size Quantization (VCQ), where the codebook size $K_t$ grows monotonically along the sequence from $K_{\min}=2$ to $K_{\max}$, leaving the loss function, parameter count, and AR training procedure unchanged. With a vanilla autoregressive Transformer and standard next-token prediction, a base version of VCQ reduces gFID w/o CFG from 27.98 to 14.80 on ImageNet $256\times256$ over the baseline. Scaled up, it reaches gFID 1.71 with 684M autoregressive parameters, without any extra training techniques such as semantic regularization or causal alignment. The extreme information bottleneck at $K_{\min}=2$ naturally induces a coarse-to-fine semantic hierarchy: a linear probe on only the first 10 tokens reaches 43.8% top-1 accuracy on ImageNet, compared to 27.1% for uniform codebooks. Ultimately, these results show that what matters is not only the total capacity of the codebook, but also how that capacity is distributed and organized.
### Title:
          Playing the network backward: A Game Theoretic Attribution Framework
 - **Authors:** Jakob Paul Zimmermann, Jim Berend, Georg Loho, Sebastian Lapuschkin, Wojciech Samek
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Attribution methods explain which input features drive a model's prediction, making them central to model debugging and mechanistic interpretability. Yet backward attribution methods, including gradients, LRP, and transformer-specific rules, lack a shared framework in which to compare the underlying backward calculations. We introduce such a framework by recasting backward attribution as a two-player game on an extended network graph, building on Gaubert and Vlassopoulos' ReLU Net Game. Gradients and the full alpha-beta-LRP family arise as integrals over game trajectories under specific equilibria, so attribution maps become projections of trajectory distributions rather than the primary object. Desired explanation properties, such as localisation focus, robustness to input noise, or stable attention routing, can be specified as game-theoretic concepts, including policy regularization, risk aversion, and extended action sets, and translate directly into novel adaptations of the well-known backward rules. On ViT-B/16, one such selected adaptation of alpha-beta-LRP outperforms prior transformer-specific backward methods across all considered localisation metrics.
### Title:
          TIDE: Every Layer Knows the Token Beneath the Context
 - **Authors:** Ajay Jaiswal, Lauren Hannah, Han-Byul Kim, Duc Hoang, Mehrdad Farajtabar, Minsik Cho
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We revisit a universally accepted but under-examined design choice in every modern LLM: a token index is looked up once at the input embedding layer and then permanently discarded. This single-injection assumption induces two structural failures: (i) the Rare Token Problem, where a Zipf-type distribution of vocabulary causes rare-token embeddings are chronically under-trained due to receiving a fraction of the cumulative gradient signal compared to common tokens; and (ii) the Contextual Collapse Problem, where limited parameters models map distributionally similar tokens to indistinguishable hidden states. As an attempt to address both, we propose TIDE, which augments the standard transformer with EmbeddingMemory: an ensemble of K independent MemoryBlocks that map token indices to context-free semantic vectors, computed once and injected into every layer through a depth-conditioned softmax router with a learnable null bank. We theoretically and empirically establish the benefits of TIDE in addressing the issues associated with single-token identity injection as well as improve performance across multiple language modeling and downstream tasks.
### Title:
          Spark3R: Asymmetric Token Reduction Makes Fast Feed-Forward 3D Reconstruction
 - **Authors:** Zecheng Tang, Jiaye Fu, Qiankun Gao, Haijie Li, Yanmin Wu, Jiaqi Zhang, Siwei Ma, Jian Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Feed-forward 3D reconstruction models based on Vision Transformers can directly estimate scene geometry and camera poses from a small set of input images, but scaling them to video inputs with hundreds or thousands of frames remains challenging due to the quadratic cost of global attention layers. Recent token-merging methods accelerate these models by compressing the token sequence within the global attention layers, but they apply a uniform reduction to query tokens and key-value tokens, ignoring their functionally distinct roles in 3D reconstruction. In this work, we identify a key property of feed-forward 3D reconstruction models: query tokens encode view-specific geometric requests and are sensitive to compression, while key-value tokens represent shared scene context and tolerate aggressive compression. Guided by this insight, we propose Spark3R, a training-free acceleration framework that decouples the compression of query tokens and key-value tokens by assigning distinct reduction factors, with intra-group token merging applied to query tokens and lightweight token pruning to key-value tokens. Additionally, Spark3R adaptively adjusts the key-value reduction factor across layers, further improving the quality-efficiency trade-off. As a plug-and-play framework requiring no retraining, Spark3R integrates directly into multiple pretrained feed-forward 3D reconstruction models, including VGGT, $\pi^3$, and Depth-Anything-3, and achieves up to $28\times$ speedup on 1,000-frame inputs while maintaining competitive reconstruction quality.
### Title:
          Attributions All the Way Down? The Metagame of Interpretability
 - **Authors:** Hubert Baniecki, Przemyslaw Biecek, Fabian Fumagalli
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce the metagame, a conceptual framework for quantifying second-order interaction effects of model explanations. For any first-order attribution $\phi(f)$ explaining a model $f$, we measure the directional influence of feature $j$ on the attribution of feature $i$, denoted as meta-attribution $\varphi_{j \to i}(f)$, by treating the attribution method itself as a cooperative game and computing its Shapley value. Theoretically, we prove that attributions hierarchically decompose into meta-attributions, and establish these as directional extensions of existing interaction indices. Empirically, we demonstrate that the metagame delivers insights across diverse interpretability applications: (i) quantifying token interactions in instruction-tuned language models, (ii) explaining cross-modal similarity in vision-language encoders, and (iii) interpreting text-to-image concepts in multimodal diffusion transformers.
### Title:
          Molecules Meet Language: Confound-Aware Representation Learning and Chemical Property Steering in Transformer-VAE Latent Spaces
 - **Authors:** Zakaria Elabid, Jan Andrzejewski, Bartosz Brzoza, Attila Cangi
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Molecular generative models often assume meaningful latent geometry, but apparent property predictability can reflect sequence-level shortcuts rather than chemical organization. We study this issue in an unsupervised autoregressive Transformer-VAE trained on SELFIES. After training, we freeze the model, fit linear probes to RDKit descriptors, and use the probe weights as candidate global steering directions. To separate chemical signal from SELFIES artifacts, we introduce a confound-aware evaluation based on residualization, confound-direction alignment analysis, and decoded-molecule traversal. This is necessary because SELFIES length, branch tokens, ring tokens, and token entropy are strongly encoded in the latent space. Under this confound-aware evaluation, we find robust monotonic steering for cLogP, FractionCSP3, HeavyAtomCount, TPSA, BertzCT, and HBA. Nonlinear probes further show that some properties admit stable global directions, while others are better described by local latent gradients. Overall, our results show that chemically meaningful steering can emerge in entangled molecular latent spaces, but only when validated through decoded molecules and controlled for representation-level confounds.
### Title:
          SMolLM: Small Language Models Learn Small Molecular Grammar
 - **Authors:** Akhil Jindal, Harang Ju
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Language models for molecular design have scaled to hundreds of millions of parameters, yet how they learn chemical grammar is poorly understood. We train SMolLM, a 53K-parameter weight-shared transformer, to generate novel SMILES with 95% validity on the ZINC-250K drug-like-molecule benchmark, outperforming a standard GPT with 10 times more parameters. Mechanistically, the same block resolves SMILES constraints across passes in a fixed order: brackets first, rings second, and valence last, as shown by error classification, linear probing, and sparse autoencoders. A systematic ablation across attention heads and passes further localizes the first bracket-matching step to a single attention head. Together, these results yield a compact, mechanistically interpretable molecular generator and a testbed for studying iterative computation in formal-language domains.
### Title:
          FedFrozen: Two-Stage Federated Optimization via Attention Kernel Freezing
 - **Authors:** Junye Du, Zhenghao Li, Yushi Feng, Long Feng
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Federated learning with heterogeneous clients remains a significant challenge for deep learning, primarily due to client drift arising from inconsistent local updates. Existing federated optimization methods typically address this issue through objective-level regularization or update-correction mechanisms. Recent studies, however, suggest that Transformer-based architectures may be inherently more robust than conventional models under heterogeneous federated training. Motivated by this observation, we investigate how different parameter components within the attention mechanism influence federated optimization. Specifically, we decompose the attention module into a query/key block, which determines the attention kernel, and a value block, which performs semantic transformation under the induced kernel. Based on this perspective, we propose FedFrozen, a two-stage federated optimization framework that first performs full-model warm-up training and then freezes the query/key block while continuing to optimize the value block. Under a linear-attention formulation, we show that the warm-up stage can be interpreted as an inexact descent procedure on a regularized kernel-profile objective, while the frozen stage reduces to a restricted value-block optimization problem under a fixed attention kernel. Our analysis further reveals an explicit trade-off that governs the choice of warm-up length. Simulations validate the predicted bias-drift behavior, and real-data experiments demonstrate that FedFrozen improves both the stability and effectiveness of Transformer models in heterogeneous federated learning.
### Title:
          MINER: Mining Multimodal Internal Representation for Efficient Retrieval
 - **Authors:** Weien Li, Rui Song, Zeyu Li, Haochen Liu, Gonghao Zhang, Difan Jiao, Zhenwei Tang, Bowei He, Haolun Wu, Xue Liu, Ye Yuan
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual document retrieval has become essential for accessing information in visually rich documents. Existing approaches fall into two camps. Late-interaction retrievers achieve strong quality through fine-grained token-level matching but store hundreds of vectors per page, incurring large index footprints and high serving costs. By contrast, dense single-vector retrievers retain storage and latency advantages but consistently lag in quality because they compress all information into a single final-layer embedding. In this work, we first conduct a layerwise diagnostic on single-vector retrievers, revealing that retrieval-relevant signal resides in internal representations. Motivated by these findings, we propose MINER (Mining Multimodal Internal RepreseNtation for Efficient Retrieval), a lightweight plug-in module that probes and fuses internal signals across transformer layers into a single compact embedding without modifying the backbone or sacrificing single-vector efficiency. The first Retrieval-Aligned Layer Probing stage attaches a lightweight probe at each layer, surfacing which dimensions carry retrieval-relevant information. The subsequent Adaptive Sparse Multi-Layer Fusion stage applies performance-adaptive neuron-level masking to the selected layers and fuses the surviving signals into the final dense vector. Across ViDoRe V1/V2/V3, MINER outperforms existing dense single-vector retrievers on the majority of benchmarks, with up to 4.5% nDCG@5 improvement over its corresponding backbone. Compared to strong late-interaction baselines, in some settings MINER substantially narrows the nDCG@$5$ gap to $0.2$ while preserving the storage and serving advantages of dense retrieval.
### Title:
          Invariant-Based Diagnostics for Graph Benchmarks
 - **Authors:** Richard von Moos, Mathieu Alain, Bastian Rieck
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Combinatorics (math.CO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Progress on graph foundation models is hindered by benchmark practices that conflate the contributions of node features and graph structure, making it hard to tell whether a model actually learns from connectivity, or whether it even needs to. We propose addressing this using graph invariants, i.e., permutation-invariant, task-agnostic structural descriptors that serve as a diagnostic framework for graph benchmarks. We show that (i) invariants are more expressive than standard GNNs, (ii) invariants characterize structural heterogeneity within and across benchmark datasets, (iii) invariants predict multi-task performance, and (iv) simple invariant-based models are competitive with, and sometimes exceed, transformer and message-passing baselines across 26 datasets. Our results suggest that expressivity is not the main driver of predictive performance, and that on tasks where structure matters, a non-trainable structural proxy often matches trained message-passing models. We thus posit that invariant baselines should become a standard for evaluating whether structure is required for a task and whether a model picks up on it, serving as a stepping stone towards graph foundation models.
### Title:
          Patch-Effect Graph Kernels for LLM Interpretability
 - **Authors:** Ruben Fernandez-Boullon, David N. Olivieri
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mechanistic interpretability aims to reverse-engineer transformer computations by identifying causal circuits through activation patching. However, scaling these interventions across diverse prompts and task families produces high-dimensional, unstructured datasets that are difficult to compare systematically. We propose a framework that reframes mechanistic analysis as a graph machine-learning problem by representing activation-patching profiles as patch-effect graphs over model components. We introduce three graph-construction methods: direct-influence via causal mediation, partial-correlation, and co-influence and apply graph kernels to analyze the resulting structures. Evaluating this approach on GPT-2 Small using Indirect Object Identification (IOI) and related tasks, we find that patch-effect graphs preserve discriminative structural signals. Specifically, localized edge-slot features provide higher classification accuracy than global graph-shape descriptors. A screened paired-patching validation suggests that CI and PC selected candidate edges correspond to stronger activation-influence effects than random or low-rank candidates. Crucially, by evaluating these representations against rigorous prompt-only and raw patch-effect controls, we make the evidential scope of the benchmark explicit: graph features compress structured patching signal, while raw tensors and surface cues define strong baselines that any circuit-level claim should address. Ultimately, our framework provides a compression and evaluation pipeline for comparing patching-derived structures under controlled baselines, separating robust slice-discriminative evidence from stronger task-general causal-circuit claims.
### Title:
          OA-WAM: Object-Addressable World Action Model for Robust Robot Manipulation
 - **Authors:** Yushan Liu, Peibo Sun, Shoujie Li, Yifan Xie, Lingfeng Zhang, Xintao Chao, Shiyuan Dong, Fang Chen, Xiao-Ping Zhang, Wenbo Ding
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World Action Models (WAMs) enhance Vision-Language-Action policies by jointly predicting scene evolution and robot actions, but existing methods usually represent the predicted world as holistic images, video tokens, or global latents. These representations are difficult for an action decoder to address when an instruction refers to a particular object, especially under scene shifts where object identity is entangled with context. We propose OA-WAM, an Object-Addressable World Action Model for robust robot manipulation. OA-WAM decomposes each frame into N+1 slot states, with one robot slot and N object slots. Each slot contains a persistent address vector and a time-varying content vector, and is fused with text, image, proprioception, and past-action tokens in a block-causal sequence. A world head predicts next-frame slot states, while a flow-matching action head decodes a 16-step continuous action chunk in the same forward pass. Addressability is enforced by routing cross-slot attention through address-only keys and resetting the address slice at every transformer layer, separating which object to act on from what that object currently is without adding extra tokens. OA-WAM matches strong VLA and WAM baselines on LIBERO (97.8%) and SimplerEnv (79.3%), reaches state-of-the-art performance on the most relevant LIBERO-Plus geometric axes, and remains competitive on the seven-axis aggregate. A causal slot-intervention test yields a swap-binding cosine of 0.87, versus at most 0.09 for holistic baselines. These results suggest that addressable object states provide an effective interface for robust world-action modeling under scene perturbations.
### Title:
          From Token Lists to Graph Motifs: Weisfeiler-Lehman Analysis of Sparse Autoencoder Features
 - **Authors:** Ruben Fernandez-Boullon, Pablo Magariños-Docampo, Javier Perez-Robles
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sparse autoencoders (SAEs) have become central to mechanistic interpretability, decomposing transformer activations into monosemantic features. Yet existing analyses characterise features almost exclusively through top-activating token lists or decoder weight vectors, leaving the higher-order co-occurrence structure shared across features largely unexamined. We introduce a graph-structured representation in which each SAE feature is modelled as a token co-occurrence graph: nodes are the tokens most frequent near strong activations, and edges connect pairs that co-occur within local context windows. A custom WL-style, frequency-binned graph kernel then provides a similarity measure over this structural space. Applied as a proof of concept to features from a large SAE trained on GPT-2 Small and probed with a synthetic mixed-domain corpus, our clustering recovers heuristic motif families (punctuation-heavy patterns, language and script clusters, and code-like templates) that are not recovered by clustering on decoder cosine similarity. A token-histogram baseline achieves higher overall purity, so the contribution of the graph view is complementary rather than dominant: it surfaces structural relationships that token-frequency and decoder-weight views alone do not capture. Cluster assignments are stable across graph-construction hyperparameters and random seeds.
### Title:
          Cubit: Token Mixer with Kernel Ridge Regression
 - **Authors:** Chuanyang Zheng, Jiankai Sun, Yihang Gao, Yuehao Wang, Liangchen Tan, Mac Schwager, Anderson Schneider, Yuriy Nevmyvaka, Xiaodong Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Since its introduction in 2017, the Transformer has become one of the most widely adopted architectures in modern deep learning. Despite extensive efforts to improve positional encoding, attention mechanisms, and feed-forward networks, the core token-mixing mechanism in Transformers remains attention. In this work, we show that the attention module in Transformers can be interpreted as performing Nadaraya-Watson regression, where it computes similarities between tokens and aggregates the corresponding values accordingly. Motivated by this perspective, we propose Cubit, a potential next-generation architecture that leverages Kernel Ridge Regression (KRR), while the vanilla Transformer relies on Nadaraya-Watson regression. Specifically, Cubit modifies the classical attention computation by incorporating the closed-form solution of KRR, combining value aggregation through kernel similarities with normalization via the inverse of the kernel matrix. To improve the training stability, we further propose the Limited-Range Rescale (LRR), which rescales the value layer within a controlled range. We argue that Cubit, as a KRR-based architecture, provides a stronger mathematical foundation than the vanilla Transformer, whose attention mechanism corresponds to Nadaraya-Watson regression. We validate this claim through comprehensive experiments. The experimental results suggest that Cubit may exhibit stronger long-sequence modeling capability. In particular, its performance gain over the Transformer appears to increase as the training sequence length grows.
### Title:
          Is One Layer Enough? Understanding Inference Dynamics in Tabular Foundation Models
 - **Authors:** Amir Rezaei Balef, Mykhailo Koshil, Katharina Eggensperger
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based tabular foundation models (TFMs) dominate small to medium tabular predictive benchmark tasks, yet their inference mechanisms remain largely unexplored. We present the first large-scale mechanistic study of layerwise dynamics in 6 state-of-the-art tabular in-context learning models. We explore how predictions emerge across depth, identify distinct stages of inference and reveal latent-space dynamics that differ from those of language models. Our findings indicate substantial depthwise redundancy across multiple models, suggesting iterative refinement with overlapping computations during inference stages. Guided by these insights, we design a proof-of-concept, looped single-layer model that uses only 20% of the original model's parameters while achieving comparable performance. The code is available at this https URL.
### Title:
          Long Context Pre-Training with Lighthouse Attention
 - **Authors:** Bowen Peng, Subho Ghosh, Jeffrey Quesnelle
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Training causal transformers at extreme sequence lengths is bottlenecked by the quadratic time and memory of scaled dot-product attention (SDPA). In this work, we propose Lighthouse Attention, a training-only symmetrical selection-based hierarchical attention algorithm that wraps around ordinary SDPA and can be easily removed towards the end of the training. Our hierarchical selection is also gradient-free, which exempts us from dealing with a complicated and potentially inefficient backward pass kernel. Our contribution is three-fold: (i) A subquadratic hierarchical pre- and post-processing step that does adaptive compression and decompression of the sequence. (ii) A symmetrical compression strategy that pools queries, keys and values at the same time, while preserving left-to-right causality, which greatly improves parallelism. (iii) A two stage training approach which we pre-train for the majority of the time with Lighthouse Attention and recover a full attention model at the end with a short training. We run preliminary small scale LLM pre-training experiments that show the effectiveness of our method compared to full attention training with all other settings matched, where we achieve a faster total training time and lower final loss after the recovery phase. Full code is available at: this https URL
### Title:
          BRICKS: Compositional Neural Markov Kernels for Zero-Shot Radiation-Matter Simulation
 - **Authors:** Richard Hildebrandt, Evangelos Kourlitis, Baran Hashemi, Manuel Bünstorf, Thierry Meyer, Nikola Boskov, Michael Kagan, Dan Rosenbaum, Sanmay Ganguly, Lukas Heinrich
 - **Subjects:** Subjects:
Machine Learning (cs.LG); High Energy Physics - Phenomenology (hep-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce a new strategy for compositional neural surrogates for radiation-matter interactions, a key task spanning domains from particle physics through nuclear and space engineering to medical physics. Exploiting the locality and the Markov nature of particle interactions, we create a \emph{next-particle prediction} kernel using hybrid discrete-continuous transformer models based on Riemannian Flow Matching on product manifolds. The model generates variable-sized typed sets of particles and radiation side effects that are the result of the interaction of an incident particle with a material volume. The resulting kernel can be composed to simulate unseen large-scale material distributions in a zero-shot manner. Unlike mechanistic simulators, our model is designed to be differentiable, provides tractable likelihoods for future downstream applications. A significant computational speed-up on GPU compared to CPU-bound mechanistic simulation is observed for single-kernel execution. We evaluate the model at the kernel level and demonstrate predictive stability over multi-round autoregressive rollouts. We additionally release a novel 20M-event radiation-matter interaction dataset for further research.
### Title:
          Weight-Decay Turns Transformer Loss Landscapes Villani: Functional-Analytic Foundations for Optimization and Generalization
 - **Authors:** Abhijit Das, Sayantan Dutta
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Weight decay is widely used as a regularizer in large language models, yet its precise role in shaping Transformer loss landscapes remains theoretically underexplored. This paper provides the first rigorous functional-analytic characterization of the standard Transformer objective--cross-entropy loss with $L^2$ regularization--by proving it satisfies Villani's criteria for coercive energy functions. Specifically, we show that the regularized loss $\mathcal{F}$ is infinitely differentiable, grows at least quadratically, has Gaussian-integrable tails, and satisfies the differential growth condition $-\Delta\mathcal{F} + \tfrac{1}{s}\|\nabla\mathcal{F}\|^{2} \to \infty$ as $\|\theta\| \to \infty$ for all $s>0$. From this structure, we derive explicit log-Sobolev and Poincaré constants $C_{\mathrm{LS}} \leq \lambda^{-1} + d/\lambda^{2}$, linking the regularization strength $\lambda$ and model dimension $d$ to finite-time convergence guarantees for noisy stochastic gradient descent and PAC-Bayesian generalization bounds that tighten with increasing $\lambda$. To validate our theory, we introduce a scalable Villani diagnostic $\Psi_s(\theta) = -\Delta \mathcal{F} + s^{-1}\|\nabla \mathcal{F}\|^2$ and estimate it efficiently using Hutchinson trace probes in models with over 100M parameters. Experiments on GPT-Neo-125M across Penn Treebank and WikiText-103 confirm the predicted quadratic growth of $\Psi_s$, spectral inflation of the Hessian, and exponential convergence behavior consistent with our log-Sobolev analysis. These results demonstrate that weight decay not only improves generalization empirically but also establishes the mathematical conditions required for fast Langevin mixing and theoretically grounded curvature-aware optimization in deep learning.
### Title:
          Transformers Efficiently Perform In-Context Logistic Regression via Normalized Gradient Descent
 - **Authors:** Chenyang Zhang, Yuan Cao
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers have demonstrated remarkable in-context learning (ICL) capabilities. The strong ICL performance of transformers is commonly believed to arise from their ability to implicitly execute certain algorithms on the context, thereby enhancing prediction and generation. In this work, we investigate how transformers with softmax attention perform in-context learning on linear classification data. We first construct a class of multi-layer transformers that can perform in-context logistic regression, with each layer exactly performing one step of normalized gradient descent on an in-context loss. Then, we show that our constructed transformer can be obtained through (i) training a single self-attention layer supervised by one-step gradient descent, and (ii) recurrently applying the trained layer to obtain a looped model. Training convergence guarantees of the self-attention layer and out-of-distribution generalization guarantees of the looped model are provided. Our results advance the theoretical understanding of ICL mechanism by showcasing how softmax transformers can effectively act as in-context learners.
### Title:
          SoftSAE: Dynamic Top-K Selection for Adaptive Sparse Autoencoders
 - **Authors:** Jakub Stępień, Marcin Mazur, Jacek Tabor, Przemysław Spurek
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sparse Autoencoders (SAEs) have become an important tool in mechanistic interpretability, helping to analyze internal representations in both Large Language Models (LLMs) and Vision Transformers (ViTs). By decomposing polysemantic activations into sparse sets of monosemantic features, SAEs aim to translate neural network computations into human-understandable concepts. However, common architectures such as TopK SAEs rely on a fixed sparsity level. They enforce the same number of active features (K) across all inputs, ignoring the varying complexity of real-world data. Natural data often lies on manifolds with varying local intrinsic dimensionality, meaning the number of relevant factors can change significantly across samples. This suggests that a fixed sparsity level is not optimal. Simple inputs may require only a few features, while more complex ones need more expressive representations. Using a constant K can therefore introduce noise in simple cases or miss important structure in more complex ones. To address this issue, we propose SoftSAE, a sparse autoencoder with a Dynamic Top-K selection mechanism. Our method uses a differentiable Soft Top-K operator to learn an input-dependent sparsity level k. This allows the model to adjust the number of active features based on the complexity of each input. As a result, the representation better matches the structure of the data, and the explanation length reflects the amount of information in the input. Experimental results confirm that SoftSAE not only finds meaningful features, but also selects the right number of features for each concept. The source code is available at: this https URL.
### Title:
          UniPool: A Globally Shared Expert Pool for Mixture-of-Experts
 - **Authors:** Minbin Huang, Han Shi, Chuanyang Zheng, Yimeng Wu, Guoxuan Chen, Xintong Yu, Yichun Yin, Hong Cheng
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern Mixture-of-Experts (MoE) architectures allocate expert capacity through a rigid per-layer rule: each transformer layer owns a separate expert set. This convention couples depth scaling with linear expert-parameter growth and assumes that every layer needs isolated expert capacity. However, recent analyses and our routing probe challenge this allocation rule: replacing a deeper layer's learned top-k router with uniform random routing drops downstream accuracy by only 1.0-1.6 points across multiple production MoE models. Motivated by this redundancy, we propose UniPool, an MoE architecture that treats expert capacity as a global architectural budget by replacing per-layer expert ownership with a single shared pool accessed by independent per-layer routers. To enable stable and balanced training under sharing, we introduce a pool-level auxiliary loss that balances expert utilization across the entire pool, and adopt NormRouter to provide sparse and scale-stable routing into the shared expert pool. Across five LLaMA-architecture model scales (182M, 469M, 650M, 830M, and 978M parameters) trained on 30B tokens from the Pile, UniPool consistently improves validation loss and perplexity over the matched vanilla MoE baselines. Across these scales, UniPool reduces validation loss by up to 0.0386 relative to vanilla MoE. Beyond raw loss improvement, our results identify pool size as an explicit depth-scaling hyperparameter: reduced-pool UniPool variants using only 41.6%-66.7% of the vanilla expert-parameter budget match or outperform layer-wise MoE at the tested scales. This shows that, under a shared-pool design, expert parameters need not grow linearly with depth; they can grow sublinearly while remaining more efficient and effective than vanilla MoE. Further analysis shows that UniPool's benefits compose with finer-grained expert decomposition.
## Keyword: autonomous driving
### Title:
          Comparative Analysis of Direct-to-Cell (D2C) and 3GPP Non-Terrestrial Networks (NTN) for Global Connectivity
 - **Authors:** Donglin Wang, Anjie Qiu, Qiuheng Zhou, Hans D. Schotten
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The quest for ubiquitous mobile coverage has catalyzed two fundamentally distinct architectural paradigms: Direct-to-Cell (D2C) and standardized 3GPP Non-Terrestrial Networks (NTN). D2C, pioneered by SpaceX Starlink and AST SpaceMobile, leverages existing terrestrial spectrum and unmodified consumer handsets to provide emergency connectivity as a market-driven overlay. In contrast, 3GPP NTN, standardized across Releases 17-19, offers a systematic satellite-native framework designed for long-term scalability, high-throughput broadband, and deep integration with terrestrial 5G/6G networks. This paper presents a comprehensive technical comparison of these approaches, analyzing their standardization trajectories, network architectures, physical-layer innovations, security postures, and operational trade-offs. We further examine their implications for emerging 6G use cases, particularly autonomous driving, where safety-critical redundancy motivates a hybrid tri-link architecture combining terrestrial 5G, NTN broadband, and D2C emergency fallback. Our analysis shows that, although D2C enables rapid market entry through legacy-device compatibility, NTN provides superior performance, security, and scalability, positioning it as the foundational framework for 6G satellite-terrestrial convergence. A hybrid model that combines the strengths of both paradigms is identified as the most practical path toward truly global connectivity.
### Title:
          Uncertainty Estimation via Hyperspherical Confidence Mapping
 - **Authors:** Eunseo Choi, Ho-Yeon Kim, Jaewon Lee, Taeyong jo, Myungjun lee, Heejin Ahn
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Quantifying uncertainty in neural network predictions is essential for high-stakes domains such as autonomous driving, healthcare, and manufacturing. While existing approaches often depend on costly sampling or restrictive distributional assumptions, we propose Hyperspherical Confidence Mapping (HCM), a simple yet principled framework for sampling-free and distribution-free uncertainty estimation. HCM decomposes outputs into a magnitude and a normalized direction vector constrained to lie on the unit hypersphere, enabling a novel interpretation of uncertainty as the degree of violation of this geometric constraint. This yields deterministic and interpretable estimates applicable to both regression and classification. Experiments across diverse benchmarks and real-world industrial tasks demonstrate that HCM matches or surpasses ensemble and evidential approaches, with far lower inference cost and stronger confidence-error alignment. Our results highlight the power of geometric structure in uncertainty estimation and position HCM as a versatile alternative to conventional techniques.
### Title:
          Adding Thermal Awareness to Visual Systems in Real-Time via Distilled Diffusion Models
 - **Authors:** Yuchen Guo, Junli Gong, Wenjun Dong, Yiuming Cheung, Weifeng Su
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Purely RGB-based vision models often fail to provide reliable cues in challenging scenarios such as nighttime and fog, leading to degraded performance and safety risks. Infrared imaging captures heat-emitting sources and provides critical complementary information, but existing high-fidelity fusion methods suffer from prohibitive latency, rendering them impractical for real-time edge deployment. To address this, we propose FusionProxy, a real-time image fusion module designed as a fully independent, plug-and-play component with diffusion level quality. FusionProxy exploits two complementary statistics of a teacher sample ensemble: per-pixel variance in raw image space, used to weight pixel-level supervision, and per-pixel variance inside frozen foundation backbones, used to route feature-level alignment spatially. Once trained, FusionProxy can be directly integrated into any visual perception system without joint optimization. Extensive experiments demonstrate that our method achieves superior performance on static recognition tasks and significantly enhances robustness in dynamic tasks, including closed-loop autonomous driving. Crucially, FusionProxy achieves real-time inference speeds on diverse platforms, from high-end GPUs to commodity hardware, providing a flexible and generalizable solution for all-day perception.
### Title:
          Can Attribution Predict Risk? From Multi-View Attribution to Planning Risk Signals in End-to-End Autonomous Driving
 - **Authors:** Le Yang, Ruoyu Chen, Haijun Liu, Jiawei Liang, ShangQuan Sun, Xiaochun Cao
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end autonomous driving models generate future trajectories from multi-view inputs, improving system integration but introducing opaque decisions and hard-to-localize risks. Existing methods either rely on auxiliary monitoring models or generate textual explanations, but are decoupled from the planning process and fail to reveal the visual evidence underlying trajectory generation. While attribution offers a direct alternative, planning differs from image classification by taking six-view camera images as input and predicting continuous multi-step trajectories, requiring attribution to capture both critical views and regions and their influence on outputs. Moreover, whether attribution maps can support risk identification remains underexplored. To address this, we propose a hierarchical attribution framework for end-to-end planning. Specifically, using L2 consistency with the original trajectory as the objective, we design a coarse-to-fine region attribution strategy that searches candidate regions across the full six-view input and refines attribution within them. We further extract three attribution statistics as predictive signals for planning risk, including attribution entropy to measure how concentrated the planner's reliance is over the joint visual space, within-camera spatial variance to characterize how spread out the attribution is within each view, and cross-camera Gini coefficient to quantify how unevenly attribution is distributed across the six cameras. Experiments on BridgeAD, UniAD, and GenAD show that these statistics correlate with planning risk, achieving Spearman correlations of $0.30 \pm 0.07$ with trajectory error and AUROC of $0.77 \pm 0.04$ for collision detection. The signal generalizes to held-out scenes with negligible degradation and remains stable under an alternative attribution baseline.
