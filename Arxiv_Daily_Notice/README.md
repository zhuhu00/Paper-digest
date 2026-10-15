# Showing new listings for Thursday, 15 October 2026
## Keyword: SLAM
### Title:
          RingNav: Task-Shaped Circular Memory for Visual Heading
 - **Authors:** Naitri Rajyaguru, Aryan Tajne, Stephen Jardim, Cornelia Fermuller, Yiannis Aloimonos
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tiny robots have limited computation and memory, yet visual navigation systems often maintain more state than a task requires. We ask whether persistent memory can instead be shaped by the task. We present \textbf{RingNav}, a \(10.6\)k--parameter visual heading estimator that constrains its memory to the circular manifold \(S^1\). RingNav learns only the turn between consecutive images, while heading is composed directly on the circle. On the TartanAir Visual SLAM Challenge, RingNav reduces mean absolute turn error by \(27\%\) and accumulated heading error over $4$ sec by \(15\%\) relative to a similarly sized learned-memory model. The structured update also gives exactly zero turn for identical frames and exact cancellation under sequence reversal. Without fine-tuning, RingNav transfers to real-world drone experiments and continues estimating heading under severe visual degradation. RingNav runs at $27.3$Hz on Raspberry Pi Zero 2W and can be deployed on an ultra-low power GAP8 processor at $33.4$Hz.
### Title:
          Remember, Revisit, Revise: Scaffold Memory for Long-Horizon 3D Geometry
 - **Authors:** Soumick Sarker, Mengmi Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Geometry foundation models estimate camera poses and 3D scene structure from video sequences, but maintaining consistent reconstructions over long horizons remains challenging. Feed-forward models process long sequences as independent, fixed-length frame windows and align their predictions, causing pose and reconstruction errors to accumulate across windows. Streaming models retain information from past frames to inform future predictions, but cannot revise earlier estimates when later observations reveal errors. To address this, we introduce Scaffold MemOry for Revision (SMORE), a framework equipping frozen geometry foundation models with a revisable external memory for long-horizon inference. Inspired by hippocampal associative memory in biological brains, which links spatial context with sensory experience, SMORE associates where an observer is with what it observes, enabling past observations to be stored, retrieved, verified against new evidence, and revised when inconsistencies are detected. We evaluate SMORE with eight competitive geometry models on five datasets spanning camera pose estimation, multi-view depth estimation, 3D point-cloud reconstruction, simultaneous localization and mapping (SLAM), and novel view synthesis. Across all evaluated models, SMORE consistently improves long-sequence pose estimation, reduces multi-view depth error by up to 58%, reduces Chamfer distance for 3D point-cloud reconstruction by up to 43%, and achieves average trajectory error as low as 2.9 cm in long-horizon SLAM. By retaining corrected poses and observations, SMORE further improves the fidelity and spatial consistency of large-scale 3D scene reconstruction. These results establish revisable external memory as a flexible interface for extending pretrained geometry models beyond fixed-context prediction toward iterative, error-correcting inference over long visual sequences.
### Title:
          HyperLoop: Hyperspectral-Assisted Loop Closure Detection in 3D-SLAM for Planetary Exploration
 - **Authors:** Annie Bhalla, Dennis Rotondi, Riccardo Giubilato, Kai O. Arras, Wolfgang Stuerzl
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous navigation of planetary rovers is challenged by visually repetitive, featureless terrain. SLAM systems based on 3D Gaussian Splatting (3DGS) offer dense mapping but rely on RGB appearance descriptors that degrade under perceptual aliasing - a common failure mode in extraterrestrial environments where physically distinct locations appear visually identical. This paper presents HyperLoop, the first framework integrating hyperspectral imaging (HSI) into the loop closure module of a 3DGS-based SLAM system. Hyperspectral descriptors encode material-level spectral signatures complementing RGB features, providing robustness to illumination changes and visual repetitiveness. Two HSI descriptor families are introduced: Bag-of-Spectral-Words (BoSW), encoding spectral material distributions via TF-IDF weighted histograms, and PCA-K VLAD (PCAK-VLAD), capturing first-order residual statistics of PCA-compressed spectral signatures. Both are evaluated with SIFT-VLAD and NetVLAD RGB descriptors under Strict-AND and Weighted fusion strategies on a custom dataset from the Moon-Mars Outdoor Test Site (MMOTS) at DLR, comprising synchronized RGB-D and hyperspectral sequences across four planetary analog traverses (65.5 m total). A key finding is that the sensor's Red-NIR range (600-860 nm) provides limited discriminability for rock terrain: the best HSI fusion (SIFT-VLAD + BoSW, Strict-AND) achieves 5.04 cm ATE RMSE, within 1.8% of SIFT-VLAD alone (4.95 cm). The gain over NetVLAD (8.81 cm) is attributable to SIFT-VLAD, not HSI fusion. This motivates future adoption of SWIR sensors capturing diagnostic mineral absorption features absent from the 600-860 nm range for planetary SLAM missions.
### Title:
          Smart Fusion for Adaptive Visual-IMU Weighting in cuVSLAM Sparse Bundle Adjustment
 - **Authors:** Wonju Lee, Dara Molloy, Abhilash Nand Kumar, Onias Castelo, Petar Trslic, David Adley, Conor Ferguson, Hesam Rabeti
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In cuVSLAM, visual and inertial measurement unit (IMU) residuals are fused in sparse bundle adjustment (SBA) with a weighting fixed by pre-calibrated noise covariances, leaving no mechanism to adapt the visual-inertial balance at runtime. We introduce a scalar $\alpha\geq1$ that upscales the visual information matrix relative to the IMU preintegration constraint. Across the candidate set $\{1.0,2.0,5.0,10.0,20.0\}$, the resulting trajectories form two empirical performance regimes. The IMU-TRUST regime contains $\alpha\in\{1,2\}$ near the calibrated baseline, while the VISION-TRUST regime contains $\alpha\in\{10,20\}$. The intermediate value $\alpha=5$ is treated as a transition case. Differences within each regime are small relative to those observed between the regimes. This structure motivates reducing $\alpha$-selection to a binary decision. We train a lightweight Visual Quality Estimator (VQE), implemented as a multilayer perceptron with 914 trainable parameters. It maps a 10-dimensional visual quality feature vector assembled from statistics already maintained by the tracker to a per-SBA regime prediction. The proposed method reduces mean RMSE APE by $27.7\%$ and by $14.9\%$ under leave-one-out cross-validation (LOOCV) on EuRoC MAV and TUM-VI Room, respectively.
## Keyword: odometry
### Title:
          IMU-Bench: Benchmarking Wrist IMU Representations Across Kinematic, Semantic and Clinical Tasks
 - **Authors:** Yiquan Li, Aidan Bradshaw, Chenfeng Gao, Karan Ahuja
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Wrist-worn inertial measurement units (IMUs) provide a common sensing modality for tasks ranging from activity and gesture recognition to pose estimation, inertial odometry and clinical motor assessment. Existing wearable benchmarks evaluate performance across multiple tasks, but leave open how supervision for one task affects transfer to others and whether these tasks benefit from a shared representation. We present IMU-Bench, a benchmark of ten tasks from eight datasets for studying IMU multi-task performance and cross-task transfer. We compare six self-supervised methods pretrained on unlabeled recorded and simulated wrist motion, evaluating classification, pose and velocity estimation, and IMU-language retrieval. We find that our masked autoencoder, InrtlWrist, achieves the best or joint-best frozen-probe performance on nine of ten tasks, and fine-tuning improves on training from scratch on nine of ten tasks, including full-body pose, odometry and retrieval. Across transfer and joint-training experiments, supervision that benefits one target can reduce performance on others, with supervised sources transferring within kinematic estimation while, under frozen probing, none approaches the pretrained encoder on language retrieval, and joint-training gains that come at a cost to the paired task. These findings distinguish broad downstream usefulness from complementary task supervision. Code, task cards and a leaderboard are publicly available.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Into the LidarVerse: A Real-Time Unified LiDAR World Model Across Tasks and Sensors
 - **Authors:** Henry Che, Xuanchi Ren, Sanja Fidler, Shenlong Wang, Laura Leal-Taixé, Shengyu Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present LidarVerse, a real-time unified LiDAR world model for sensor simulation across tasks and sensors. Existing LiDAR simulators largely follow one of two complementary paradigms: reconstruction-based methods preserve the geometry of a captured scene but require lengthy per-scene optimization, whereas generative methods amortize learning across data but lack the consistency needed for long-horizon rollouts. LidarVerse brings both paradigms into a single, unified conditional generative framework. A universal tokenizer maps LiDAR range sequences into a shared latent space, where a bidirectional teacher learns a common interface for conditioning on a LiDAR prefix, an HD-Map, a persistent spatial cache, and optionally, text. Varying the available scene evidence turns the same model into a generator of new worlds, a point-cloud forecaster, or a generalizable resimulator of observed scenes without per-scene optimization. We distill the teacher into a four-step autoregressive causal student and maintain both a rolling temporal K/V cache and a world-aligned spatial cache, enabling persistent long-horizon rollouts with real-time inference at 11 FPS on a single H100 GPU. LidarVerse achieves state-of-the-art performance on most reported metrics across all three evaluation protocols, while its tokenizer supports 32-, 64-, and 128-beam LiDAR and generalizes to an unseen scanning pattern. These results demonstrate that generative and reconstruction-grounded LiDAR simulation can be realized within one model, providing the core capabilities for future closed-loop sensor simulation.
### Title:
          Holi-Spatial 360: Generative Reconstruction from Sparse Panoramas for Spatial Rendering and Intelligence
 - **Authors:** Yuanyuan Gao, Zhirui Liu, Yuning Gong, Yifei Liu, Yifan Zhan, Kuixuan Jiao, Xiaolong Zhou, Yifan Yang, Hongjie Zhang, Xue Yang, Dan Xu, Zhihang Zhong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spatial intelligence requires scalable 3D environments that are both photorealistic and semantically grounded, yet existing indoor datasets are dominated by room-scale captures and costly LiDAR acquisition. Online real-estate platforms offer abundant panoramas of diverse multi-room homes, but sparse viewpoints and texture-poor regions make reconstruction severely under-constrained. We introduce Holi-Spatial 360, a generative reconstruction and data curation framework for converting these panoramas into annotated multi-room 3D environments. Because reconstruction quality bounds subsequent generation, our Correspondence-Guided Geometric Optimization converts feed-forward reconstruction priors into reliable cross-view constraints and builds a coherent 3D Gaussian Splatting representation as 3D spatial memory. Adapted single-image and video priors then restore appearance and complete continuous trajectories while preserving observed content. The reconstructed scenes support arbitrary RGB-D rendering and an automated curation pipeline that combines end-to-end 3D grounding with VLM-based verification. Holi360 contains over 1K multi-room 3DGS scenes, more than 100K instance annotations, and 2M spatial question-answer pairs. We also introduce the Holi360 benchmark to evaluate the spatial understanding of VLMs in real-world, multi-room indoor environments. Experiments demonstrate superior reconstruction and curation quality under sparse panoramic inputs, while fine-tuning VLMs on Holi360 substantially improves spatial reasoning capabilities.
### Title:
          LiFi: LiDAR Generation from Multi-View Images via Geometric and Semantic Collaborative Guidance
 - **Authors:** Sizhuo Zhou, Xiaosong Jia, Fanrui Zhang, Qifeng Li, Junjie Li, Zirui Wang, Yukang Feng, Yu Hong, Shaofeng Zhang, Wenlong Liao, Tao He, Juyong Zhang, Junchi Yan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generating LiDAR point clouds from multi-view camera images is a valuable task with applications in controllable data synthesis, cross-modal simulation and various perception tasks. However, most existing methods are not specifically designed for this task, and the quality of their generated LiDAR remains limited. Moreover, these methods typically focus only on semantic cues in images or generate LiDAR from a monocular camera image. In this work, we introduce LiFi (LiDAR From images), a dedicated framework for generating visually and geometrically aligned LiDAR scenes from multi-view camera images. LiFi guides the latent diffusion process through two complementary branches: geometry and semantics. The geometry branch constructs scene features from images through a reverse sampling algorithm and an uncertainty-aware geometric encoder combined with DepthAnything3, whereas the semantic branch provides high-level semantic representations via a cross-view interaction module. We further introduce a dual-branch balanced classifier-free guidance (CFG) strategy, which enhances the model's conditional generation capability while preserving the independent learning and collaborative controllability of the two branches. Extensive experiments demonstrate that LiFi outperforms state-of-the-art methods in generating high-fidelity LiDAR scenes. The code will be publicly available at: this https URL.
### Title:
          Tiered-Resolution Volumetric Mapping for Real-Time Simultaneous Planning and Mapping on Natural Outdoor Environments
 - **Authors:** Afonso E. Carvalho, David Portugal, Paulo Peixoto, George Kantor
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-time volumetric mapping for a planning robot is dominated by the cost of integrating and storing information at the finest resolution, yet only a small fraction of any map ever lies on or near a path the planner actually considers. We exploit this with a tiered-resolution mapping mechanism that integrates LiDAR into a single map structure at two resolutions simultaneously: fine inside a corridor around the robot's current plan, and coarse everywhere else. As opposed to traditional navigation pipelines where path planning uses the mapping result and provides no feedback, we propose a feedback loop where planning also informs mapping to dynamically integrate information at different leaf resolutions. Across two real-world teleoperated datasets, replayed and scored offline against an independent full-resolution map, the tiered maps are 13-15x smaller and require 6-8x less integration CPU time than a uniform fine map, while producing paths at a similar cost per meter as the ones generated from fine resolution maps on both scenarios. A uniform coarse map reaches the same size savings but its path quality collapses (+210% cost per meter) on the harder scenario, because it over-discretizes terrain the robot must traverse. Tiering approximates the coarse map's cheapness without its failure mode.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          MicroSDF: Microfacet-Driven Hybrid Neural SDFs for Mixed-Reflectance Surface Reconstruction
 - **Authors:** Lejia Ye, Yuhua Xu, Yulan Guo, Lian Xu, Xiaohu Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate 3D reconstruction in real-world environments remains a significant challenge due to the coexistence of reflective and non-reflective surfaces, which pose distinct modeling demands. Existing methods often treat these surface types separately, limiting their generalizability and physical plausibility. To bridge this gap, we propose MicroSDF, a novel neural implicit framework that facilitates geometry and reflectance modeling through microfacet theory. Our approach incorporates three core innovations: (i) a microfacet-guided geometry model that extracts multi-scale surface normals (macroscopic and microfacet) from a signed distance field (SDF), regularized by a proposed microfacet normal consistency loss to enforce physically plausible surface orientations; (ii) an enhanced dual-branch color model, where the specular branch leverages the microfacet normals to model high-frequency reflectance, and the vanilla branch, unlike prior works, uses reflection direction (instead of viewing direction) to better model diffuse and low-frequency specular components; and (iii) a detection-guided color blending strategy that adaptively fuses the color outputs based on reflection priors, providing more physically intuitive blending than implicitly learned blending weights. Combined with a tailored multi-stage optimization scheme, the proposed MicroSDF achieves robust and high-fidelity reconstruction across reflective and non-reflective surfaces. Extensive experiments on DTU, Shiny Blender, Ref-NeRF, and DeepVoxels datasets demonstrate state-of-the-art performance, establishing a new direction for physically grounded neural reconstruction.
### Title:
          VisibilitySplat: Ray-Traced Occlusion for Relighting with 3D Gaussian Splatting
 - **Authors:** Sven Kluge, Oliver Staadt
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We address inverse rendering with 3D Gaussian Splatting (3DGS) by introducing explicit visibility modeling for relighting as well as material and light decomposition. Our approach augments the standard rasterized 3DGS pipeline with a sparse visibility oracle that estimates transmittance-weighted occlusion for Gaussian primitives from sampled lighting directions. This oracle is implemented using a point-based ray tracer accelerated by a bounding volume hierarchy (BVH) and queried sparsely within the inverse-rendering objectives, while the original 3DGS loop is retained for training efficiency, interactive visualization, and tooling compatibility. Shading follows a physically based rendering (PBR) formulation with a principled microfacet bidirectional reflectance distribution function (BRDF) and low-resolution high-dynamic-range (HDR) environment maps. We evaluate our method on the TensoIR synthetic dataset against baselines based on neural radiance fields (NeRFs), tensor representations, and 3DGS. The results show competitive performance and improvements over several earlier baselines for novel-view synthesis (NVS), albedo reconstruction, and relighting. Ablations indicate that explicit visibility modeling is an important contributor to relighting and material-illumination disentanglement, while pure PBR supervision can favor appearance fitting in NVS. Overall, the findings suggest that sparse, point-based visibility queries effectively complement rasterized splatting for inverse rendering while preserving the practical advantages of the 3DGS ecosystem.
## Keyword: mapping
### Title:
          Lotus: Learning to Understand Time-series by Learning to Forecast
 - **Authors:** Van Dai Do, Huu Hiep Nguyen, Minh Hoang Nguyen, Manh Nguyen, Hung Le
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Time-series language models typically align numerical signals with language using labels, captions, or question-answer pairs. Although such supervision encourages linguistic representations, it does not explicitly require them to preserve information about how the underlying time-series signal evolves. We introduce forecast grounding, a pretraining principle that requires language-aligned time-series representations to remain predictive of the future evolution before they are adapted to downstream tasks. We instantiate this principle in LOTUS, which divides each time-series channel into non-overlapping patches and maps them into the LLM embedding space. It then predicts the next patch from the LLM hidden states of the time-series tokens, encouraging the learned representation to retain temporal information. To capture both temporal changes and periodic patterns, we also propose a temporal-spectral patch representation that combines each raw time-series patch with its spectral representation before mapping it into the LLM embedding space. Across three language model backbones and six downstream evaluation datasets, LOTUS achieves the best average performance with minimal trainable parameters, reaching 59.91% accuracy and outperforming the strongest matched baseline by 3.36%. Our representation analyses further show that LOTUS uses the numerical input and preserves temporal structure in its learned patch representations. These results establish forecast grounding as a promising pretraining principle, enabling compact time-series language models to outperform models 25 to 50 times their size on TSRBench.
### Title:
          MonoMIP: Multi-Height Inverse Perspective Mapping for Monocular 3D Object Detection
 - **Authors:** Emir Ulurak, Furkan Kıraç
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular 3D object detection methods increasingly rely on depth-guided transformers, but they operate entirely in the perspective image plane where spatial relationships are distorted by foreshortening. We propose MonoMIP, a dual-decoder framework that adds complementary 3D geometric reasoning through Bird's-Eye View (BEV) features constructed via Multi-Height Inverse Perspective Mapping. We perform IPM at K elevation planes spanning ground to rooftop, producing an ordered stack of height-conditioned metric BEV features that reduces above-ground misprojection and exposes depth-dependent appearance variation across planes. A BEV decoder with multi-scale deformable attention aggregates this multi-height evidence per query, while a depth-guided 3D decoder provides complementary perspective-space predictions. Without extra training data, MonoMIP attains 25.84% Moderate AP3D|R40 on KITTI val and 21.66% on the official test set for Car, outperforming recent published monocular methods on both the KITTI and Waymo benchmarks.
### Title:
          Neural Spline Flow Diffeomorphisms for Pullback Finite Element Methods on Complex Domains
 - **Authors:** Ioannis Kalogeris, Anaksagoras Spitas, Konstantinos Atzarakis, George Stavroulakis, Vissarion Papadopoulos
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose a method for solving partial differential equations on complex domains by learning smooth, invertible mappings from a fixed reference domain using Neural Spline Flows (NSFs). Monotone rational-quadratic spline coupling layers ensure a strictly positive Jacobian determinant by construction, eliminating the need for Jacobian-sign penalties. A diffeomorphic pullback transfers the weak form of the PDE to the reference domain, enabling finite element analysis on reusable structured meshes. To generalize across shapes, a shared NSF is conditioned on low-dimensional latent codes learned through an auto-decoder framework; a subsequent encoder predicts these codes for unseen geometries in a single forward pass. For a given learned map, the pullback preserves the mathematical structure of the PDE and is exactly equivalent to solving on the domain represented by that map. Because the learned domain generally approximates the target geometry, geometric mapping error remains distinct from finite element discretization and quadrature errors. Numerical benchmarks show that sufficiently accurate learned mappings yield reliable finite element solutions. By avoiding repeated generation of unstructured meshes, the method addresses a bottleneck in simulation workflows. The fixed reference mesh also creates opportunities for efficient assembly, memory-aligned data access, and precomputed quadrature. The resulting framework assigns geometric complexity to the neural network while retaining conventional finite element discretization and convergence properties on the learned domain, with overall accuracy also governed by geometric fidelity.
### Title:
          Benchmarking 3D Reconstruction for Under-Ice Robotic Perception in Arctic Environments
 - **Authors:** Klára Orbán, Ashwin Nedungadi, Ana-Ştefania Kogălniceanu, Bianca-Marcela Sava, Bastian Cieply, Raul-Alexandru Simon, Kuderna-Iulian Benţa, Stefan Lüdtke
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As the Arctic transitions toward a seasonally ice-free state, capturing the complex morphology of submerged sea ice is crucial for advancing models of ocean-ice-atmosphere heat exchange and monitoring under-ice habitats. Currently, sub-surface ice mapping is predominantly achieved through acoustic sensors such as multibeam sonar. While sonar provides robust large-scale geometry, it lacks spectral and high-resolution textural information required to record fine morphological features - a critical limitation in under-ice environments, where sparse visual features and degraded sensing conditions challenge the capture of detailed structural and optical surface properties. We present a benchmark for vision-based under-ice 3D reconstruction using real-world data from the MOSAiC expedition and synthetic data generated in an Unreal Engine-based underwater robotics simulator. The benchmark evaluates Structure-From-Motion (SfM) and monocular depth estimation, with quantitative comparison enabled through cross-modal registration to upward-looking multibeam sonar.
### Title:
          Exploring Interpretability in Deep Learning-Based Forest Classification - Separating Similar Forest Classes using Sentinel-2 Time Series
 - **Authors:** Maximilian Kirsch, Christine Preisach
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The ecological insurance theory posits that diverse forests are more resilient and better able to adapt to changing environmental conditions. Increasing drought and heat stress in Central Europe promotes mixed forests for maintaining ecosystem services. However, a diverse species distribution complicates remote sensing-based species mapping, as distinguishing pure from mixed species compositions at the pixel level remains challenging. We evaluated the potential of recurrent neural networks (RNNs) for tree-species classification from Sentinel-2 time series and investigated the spectral-temporal features underlying class discrimination, with particular emphasis on separating pure from mixed Norway spruce pixels. We compared RNN classification models with Random Forest (RF) and Extreme Gradient Boosting (XGBoost) and used Integrated Gradients (IG) to quantify feature attributions across spectral bands and time. The best-performing RNN achieved a Macro-F1 score of 0.851 on the test data, outperforming XGBoost by 0.012 and Random Forest by 0.103. Beyond classification performance, the attribution analysis revealed distinct spectral-temporal patterns associated with the separation of pure and mixed Norway spruce pixels. Attribution values increased particularly after approximately day of year (DOY) 125, while B11 showed the strongest contribution during periods of increasing spectral divergence between the two classes. These findings show that recurrent models can provide competitive classification performance while also revealing the phenological periods and spectral regions that are most relevant for distinguishing closely related forest compositions. Combining time-series classification with explainability therefore provides additional insight into the spectral-temporal mechanisms underlying tree-species discrimination and may support more detailed mapping of mixed forest structures.
### Title:
          Hopfield Networks in Non-volatile Memory
 - **Authors:** Patrick Miller, Ulya R. Karpuzcu
 - **Subjects:** Subjects:
Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many important computational workloads are bound by the performance of the memory system that supplies data to conventional processors. Compute in Memory (CiM) promises to circumvent this bottleneck by performing the processing within the memory. Neural Networks are memory-bound, and a notable example of such is the Hopfield Network. This work explores the design space of non-volatile computing-in-memory (NV-CiM) architectures using an instruction-level simulator to evaluate application mappings and workload-driven architectural adaptations. The exploration examines the resulting design trade-offs and includes theoretical comparisons with representative CPU and GPU architectures.
### Title:
          A VR Training System for Robot-Assisted Vascular Intervention with Dual-Mode Control and Model-Based Interaction Response
 - **Authors:** Yining Shang, Shuxiang Guo, Sheng Cao, Pengcheng Li, Bin Wang, Mingchao Ding
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Virtual reality training for robot-assisted vascular intervention requires accurate robotic control and effective feedback on guidewire--vessel interactions. This paper presents a VR training system combining asynchronous dual-mode command mapping with sensorless interaction estimation. The system supports velocity-controlled navigation and position-driven incremental manipulation. Guidewire deformation and a Hunt--Crossley-type contact response are combined and temporally filtered to estimate interaction intensity, while trajectory-based visualization supports post-procedure review. Tests confirmed distinct command-dispatch patterns across three velocity gears and the position mode. During hybrid-scene navigation, the estimated response remained low during straight insertion and increased as the guidewire bent within the vascular model. Trajectory analysis yielded a model-derived cumulative trauma work (CTW) value of 15.166 in normalized units and localized regions of elevated interaction. In a preliminary study with 15 novices, physical-phantom task success increased from 53.3% to 93.3% after VR training, while mean completion time decreased from 132.4 s to 96.7 s. These results demonstrate the system's dual-mode operation, deformation-sensitive feedback, and potential to improve subsequent physical-phantom task performance.
### Title:
          RDCompGS: Rate-Distortion Optimization for Compression of 3D Gaussian Splatting with Image Codecs
 - **Authors:** Huiping Ren, Shuai Wan, Luqian Bai, Zhang Chen, Fuzheng Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian Splatting (3DGS) enables high-quality, real-time novel view synthesis but requires significant storage and transmission resources. Mapping Gaussian attributes to 2D representations enables efficient compression using mature image codecs. However, Gaussian representations that achieve comparable rendering quality are generally treated similarly during optimization, despite substantial differences in coding rate, leading to limited rate-distortion (R-D) performance after compression. To address this limitation, we propose RDCompGS, a 3DGS compression method that enables overall R-D optimization of Gaussian representations with respect to subsequent coding. A differentiable estimate of the coding rate is incorporated into the R-D optimization with rendering distortion. The rate constraint adjustment model further regulates the R-D trade-off across different compression conditions. Extensive experiments on three benchmark datasets demonstrate that RDCompGS achieves average Bjøntegaard Delta Rate reductions of 37.84% and 49.31% with H.265/HEVC and JPEG XL, respectively. The estimated rate also shows a strong correlation with the actual bit-rate under different compression conditions.
### Title:
          Bridging the Topological Divide: Dual-Branch Graph Distillation with Semantic Priors for Robust Cold-Start Recommendation
 - **Authors:** Yuanfeng Qiu
 - **Subjects:** Subjects:
Information Retrieval (cs.IR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Graph Collaborative Filtering models have achieved remarkable success in recommendation systems. However, they inherently suffer from a catastrophic representation collapse in strict cold-start scenarios due to the topological isolation of unobserved items. While integrating multi-modal semantic features offers a potential remedy, directly mapping isolated semantic attributes into a globally topology-driven collaborative space frequently precipitates representation degradation and optimization conflicts. To bridge this fundamental structural divide, we propose DualGCN, an innovative Dual-Branch Graph Knowledge Distillation Framework. Operating under a decoupled two-stage training paradigm, DualGCN first constructs a robust collaborative teacher network where item representations are anchored by a topology-smoothed semantic prior, effectively reshaping the latent manifold. Subsequently, a semantic student branch employs a residual mapping mechanism and a magnitude-agnostic cosine distillation objective to achieve high-fidelity cross-modal alignment without disrupting established collaborative signals. Furthermore, we introduce a dynamic norm reconstruction mechanism to rigorously calibrate the physical scales of novel and warm items during global retrieval. Extensive experiments across three real-world benchmark datasets demonstrate that DualGCN significantly outperforms state-of-the-art baselines in strict cold-start scenarios while comprehensively preserving recommendation accuracy for highly active items.
### Title:
          A Graph-Based Analysis of Comparability, Scale, and Attribution in Private Transformer Inference
 - **Authors:** Souvik Das, Ariful Azad, Nitesh Saxena
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rising privacy concerns around large language models have accelerated research in private Transformer inference (PTI). Synthesizing the empirical claims in this line of research, however, is hindered by multi-dimensional cryptographic progress and inconsistent evaluation contracts. In this work, we systematize the field by constructing an empirical graph of 62 PTI systems, mapping system attributes to node features and evaluation compatibility to edges. A three-tiered analysis of this graph illuminates the state of private inference. Node-level attribution shows that cryptographic progress drives performance gains across most systems, yet always co-occurs with other factors (model fidelity, hardware, cost accounting). Edge-level auditing shows that only 1 of 1891 candidate system pairs is directly comparable under shared assumptions. Finally, graph-level analysis shows that the scaling frontier of private inference has plateaued at 13B parameters and projects the cost of deploying current PTI techniques on production-scale Transformers. Overall, this graph-based framework equips the community to evaluate PTI claims transparently and channel technical speedups into deployment-scale private inference.
### Title:
          Mapping Arctic Polynyas from Sea Ice Concentration Data Using Hierarchical Partitioning and Differentiated Region Growing: Sensitivity to Threshold and Product Choices
 - **Authors:** Tianyu Zhang, Haiyi Ren, Zhilun Zhang, Yang Hong, Chunlei Mi, Xiao Cheng, Fengming Hui
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurately delineating Arctic coastal polynyas from sea ice concentration data remains challenging because of complex coastal geometry and spatially heterogeneous ice conditions. We develop a daily sea ice concentration (SIC) mapping framework based on hierarchical partitioning, connected-component analysis, and differentiated region growing for polynya and open-water regions. Applied to September-May ice seasons from 2002/03 to 2024/25, the framework achieves a mean overall accuracy of 96.74% and a mean kappa coefficient of 0.93 in the 63-scene visual assessment. Sensitivity experiments reveal a consistent pattern: the absolute magnitude of SIC-defined polynya extent is strongly configuration-dependent, whereas major temporal features are comparatively more stable. Relative to a 75% upper SIC threshold, seasonal extent integrals differ by 13.48%, 32.47%, and 65.04% at thresholds of 80%, 85%, and 90%, respectively, while the broad interannual structure remains recognizable. The response is also strongly regional and seasonal, with the largest threshold sensitivity in the Central Arctic Ocean, very weak sensitivity in the Gulf of St. Lawrence, and greater pan-Arctic curve separation from January onward. At an 80% threshold, product-comparison MAPE is 68.19% between the 6.25 and 25 km products and 11.47% between the 12.5 and 25 km products under their respective comparison periods and reference definitions. Regional product disagreement is likewise heterogeneous. Together, these results show that reproducible long-term polynya monitoring requires a fixed and explicitly documented combination of SIC product, threshold, and spatial classification rules, while broad temporal patterns can remain informative even when absolute extent differs substantially.
### Title:
          Remember, Revisit, Revise: Scaffold Memory for Long-Horizon 3D Geometry
 - **Authors:** Soumick Sarker, Mengmi Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Geometry foundation models estimate camera poses and 3D scene structure from video sequences, but maintaining consistent reconstructions over long horizons remains challenging. Feed-forward models process long sequences as independent, fixed-length frame windows and align their predictions, causing pose and reconstruction errors to accumulate across windows. Streaming models retain information from past frames to inform future predictions, but cannot revise earlier estimates when later observations reveal errors. To address this, we introduce Scaffold MemOry for Revision (SMORE), a framework equipping frozen geometry foundation models with a revisable external memory for long-horizon inference. Inspired by hippocampal associative memory in biological brains, which links spatial context with sensory experience, SMORE associates where an observer is with what it observes, enabling past observations to be stored, retrieved, verified against new evidence, and revised when inconsistencies are detected. We evaluate SMORE with eight competitive geometry models on five datasets spanning camera pose estimation, multi-view depth estimation, 3D point-cloud reconstruction, simultaneous localization and mapping (SLAM), and novel view synthesis. Across all evaluated models, SMORE consistently improves long-sequence pose estimation, reduces multi-view depth error by up to 58%, reduces Chamfer distance for 3D point-cloud reconstruction by up to 43%, and achieves average trajectory error as low as 2.9 cm in long-horizon SLAM. By retaining corrected poses and observations, SMORE further improves the fidelity and spatial consistency of large-scale 3D scene reconstruction. These results establish revisable external memory as a flexible interface for extending pretrained geometry models beyond fixed-context prediction toward iterative, error-correcting inference over long visual sequences.
### Title:
          Learning Individual Scientific Taste with Privileged Hindsight Distillation
 - **Authors:** Hanwei Fan, Yanqiao Wang, Yiqi Zhu, Xuanyu Lei, Peng Li, Yang Liu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scientific taste shapes which research directions researchers pursue, and it varies across individuals. Existing work evaluates research directions along multiple evaluation criteria or models scientific taste using community feedback signals such as citations and reviews, but neither directly captures how individuals translate assessments under the same criteria into different preferences. We model scientific taste as a researcher-specific mapping from criterion-level assessments in a shared, evidence-grounded evaluation space with proposal-visible evidence, to relative preferences. A population-level mapping learned from retrospective supervision provides a cold start when individual feedback is scarce. We introduce Privileged Hindsight Distillation (PHD), which uses later-emerging scientific evidence during training to improve proposal-time criterion assessment and the population mapping, while exposing only proposal-visible information at inference. We evaluate our approach primarily in quantum research, where structured public reviews are largely unavailable, and use pairwise proposal comparison as a direct interface for observing individual taste. With only 15 comparisons per researcher, our method captures sharply different tastes, including opposing preferences over the same research-direction pairs when they trade off across evaluation criteria. In an interactive study, personalized rankings also surface proposals associated with greater subsequent user engagement, connecting learned taste to downstream research exploration.
### Title:
          HyperLoop: Hyperspectral-Assisted Loop Closure Detection in 3D-SLAM for Planetary Exploration
 - **Authors:** Annie Bhalla, Dennis Rotondi, Riccardo Giubilato, Kai O. Arras, Wolfgang Stuerzl
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous navigation of planetary rovers is challenged by visually repetitive, featureless terrain. SLAM systems based on 3D Gaussian Splatting (3DGS) offer dense mapping but rely on RGB appearance descriptors that degrade under perceptual aliasing - a common failure mode in extraterrestrial environments where physically distinct locations appear visually identical. This paper presents HyperLoop, the first framework integrating hyperspectral imaging (HSI) into the loop closure module of a 3DGS-based SLAM system. Hyperspectral descriptors encode material-level spectral signatures complementing RGB features, providing robustness to illumination changes and visual repetitiveness. Two HSI descriptor families are introduced: Bag-of-Spectral-Words (BoSW), encoding spectral material distributions via TF-IDF weighted histograms, and PCA-K VLAD (PCAK-VLAD), capturing first-order residual statistics of PCA-compressed spectral signatures. Both are evaluated with SIFT-VLAD and NetVLAD RGB descriptors under Strict-AND and Weighted fusion strategies on a custom dataset from the Moon-Mars Outdoor Test Site (MMOTS) at DLR, comprising synchronized RGB-D and hyperspectral sequences across four planetary analog traverses (65.5 m total). A key finding is that the sensor's Red-NIR range (600-860 nm) provides limited discriminability for rock terrain: the best HSI fusion (SIFT-VLAD + BoSW, Strict-AND) achieves 5.04 cm ATE RMSE, within 1.8% of SIFT-VLAD alone (4.95 cm). The gain over NetVLAD (8.81 cm) is attributable to SIFT-VLAD, not HSI fusion. This motivates future adoption of SWIR sensors capturing diagnostic mineral absorption features absent from the 600-860 nm range for planetary SLAM missions.
### Title:
          When Does the Dependency Graph Help Code-to-Architecture Mapping?
 - **Authors:** Rakhshanda Jabeen, Morgan Ericsson, Jonas Nordqvist, Anna Wingkvist
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Architectural technical debt arises when a system's implementation drifts from its inten ded modular decomposition, while the mapping between source files and architectural modu les is missing, incomplete, or costly to maintain manually. We formulate code-to-archite cture mapping as semi-supervised node classification over a directed multi-relational de pendency graph, with files as nodes, typed dependencies as edges, and lexical features d erived from code identifiers and directory layout. Starting from a small labeled sample, an iterative self-training procedure expands the mapping to the remaining files. We com pare a graph convolutional network (GCN), a graph attention network (GAT), and a graph-f ree multi-layer perceptron (MLP), using identical features and training procedures for t he learned models, against a Naive Bayes reference. Across 100 runs on ten open-source J ava and C/C++ systems, all three neural models outperform the reference on both F1 metri cs. GAT achieves the highest averages of system-level median macro and micro F1, at 83.5 and 92.2, respectively, whereas MLP remains competitive or superior on several systems. On Chrome, the largest system with 18,343 files, GAT and GCN exceed MLP by 22 and 19 ma cro-F1 points, respectively, and have substantially fewer persistently misclassified fil es. Connectivity and homophily are associated with where neural message passing helps, w hile multi-relational aggregation outperforms a single merged edge type on every system for both GCN and GAT. A follow-up study finds that several model rankings depend on the training seed, qualifying smaller advantages without removing the large graph benefit ob served on Chrome.
### Title:
          What Matters for World Modeling in Vision-Language-Action Models?
 - **Authors:** Qisen Ma, Yixiang Chen, Yuan Xu, Peiyan Li, Jiabing Yang, Kai Wang, Jianhua Yang, Jianlou Si, Jun Huang, Jing Liu, Nianfeng Liu, Yan Huang, Liang Wang
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Integrating world models into Vision-Language-Action models (VLAs) has emerged as a promising direction, enabling policies to anticipate future dynamics beyond reactive observation-to-action mapping. However, existing approaches vary simultaneously in their world representations, integration paradigms, and policy backbones, making it difficult to determine what truly matters for effective world model integration. To disentangle these factors, we categorize existing efforts into four representative paradigms, namely Implicit Future Alignment, Explicit Future Query, MoT Future Expert, and External World Predictor. We instantiate each within a unified framework and systematically evaluate these paradigms with diverse world representations and policy backbones across in-domain, out-of-domain, long-horizon, dynamic, few-shot, and real-world settings. Our study yields four main findings: 1) world representation effectiveness is paradigm-dependent, whereas 2D semantic representations offer robust, cross-paradigm gains; 2) no single paradigm is universally optimal, yet the decoupled MoT Future Expert offers competitive overall performance, particularly in OOD robustness; 3) world modeling consistently benefits policies built on standard VLMs, while decoupled designs exhibit greater compatibility with pretrained VLAs; and 4) world modeling improves performance over action-only baselines across multiple settings, with notable gains on long-horizon and dynamic tasks. Project page and video demonstrations are available at this https URL.
### Title:
          FOMI: A Force-Feedback Manipulation Interface for Teaching Contact-Rich Manipulation
 - **Authors:** Yishu Shen, Yiming Luo, Ruilin Wang, Bowen Yang, Shuai Yang, Fangyi Xu, Yujun Shen, Fu Zhang, Boyu Zhou, Yinghao Xu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robot-free collection with handheld interfaces enables scalable acquisition of human demonstrations for policy learning. However, existing handheld interfaces often provide limited intuitive force feedback, making contact-rich demonstration collection challenging for human operators. To address this, we present FOMI, a force-feedback manipulation interface with a scissor-shaped mechanism, which transmits object interaction forces directly to the operator's hands through actuation links without force sensors. This intuitive force feedback supports real-time action adjustment during robot-free collection of contact-rich demonstrations. Around FOMI, we build a demonstration collection system that integrates sensor calibration, data acquisition, and synchronization for robot-free collection. By further mapping pose changes and gripper opening of FOMI to robot end-effector poses and gripper commands, the system also supports teleoperation. Across four contact-rich tasks, FOMI improves collection efficiency by approximately 29% and 18% over the best baselines in robot-free collection and teleoperation, respectively. Demonstrations collected with FOMI in both modes enable policies to perform challenging contact-rich manipulation tasks with high success rates.
### Title:
          Sparse Transformer: a Controlled Testbed for Mechanistic Interpretability
 - **Authors:** Anton Korznikov, Alexey Dontsov, Elena Tutubalina
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mechanistic interpretability aims to decompose neural network computations into human-understandable features, yet progress is limited by the absence of ground-truth units to evaluate against. We address this with a Sparse Transformer (ST): a 5-layer language model trained on TinyStories whose wide, TopK-sparse MLP forces neuron specialization. We show that ST neurons are highly interpretable: they outperform a loss-matched dense transformer by 43% on AutoInterp, and circuits of a median of 12 neurons suffice to reproduce individual model predictions. This testbed allows us to directly compare feature learning methods: Transcoder, which approximates the MLP input-output mapping, recovers ST's neuron vectors with 52.6% higher cosine similarity than Sparse Autoencoder, which only reconstructs outputs. Furthermore, the ST enables a controlled study of polysemanticity: distilling its sparse MLP into a dense counterpart reveals how compression leads to feature superposition. These results show how a known reference basis sharpens evaluation and understanding, a role we hope the ST can serve for the field.
### Title:
          STISA: A 0.16 GOPS/W/PE Single-Shot Inference FPGA-based SNN Accelerator with Algorithm and Hardware Co-Design
 - **Authors:** Kainan Wang, Chengyi Yang, Lei Liu, Chengting Yu, Yee Sin Ang, Bo Wang, Aili Wang
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spiking neural networks (SNNs) offer great potential for low-power intelligent computing owing to their event-driven nature, yet their deployment is limited by high inference latency and inefficient hardware utilization caused by temporal dependencies. Existing accelerators struggle to balance timesteps, accuracy, and energy efficiency, while hardware-oriented timestep compression remains underexplored. To address these challenges, this work presents STISA, a unified algorithm-hardware co-design framework featuring: (i) a Temporal Splitter Compression (TSC) technique with a Temporal Split Structure (TSS) to reduce temporal redundancy while preserving network dynamics; (ii) a hardware-efficient spatiotemporal parallelism scheme, which co-optimizes dataflow and architecture through a Temporal-Prioritized Output-Stationary (TPOS) mapping and a flexible Block-Mux Streaming (BMS) architecture; and (iii) a joint TSC-TPOS-BMS co-optimization framework featuring a bandwidth-aware resource allocation strategy to achieve balanced accuracy, latency, and energy efficiency across diverse network architectures. On the algorithmic side, TSC reduces synaptic operations by 24.44%-51.71% while achieving competitive accuracies of 96.38%, 81.10%, 68.51%, and 82.40% on CIFAR-10, CIFAR-100, ImageNet, and DVS-CIFAR10, respectively. On the hardware side, FPGA prototypes deliver up to 7.99 speedup, 30.4% power reduction, and 30.1% LUT reduction. Compared with state-of-the-art SNN accelerators, STISA achieves 0.16 GOPS/W/PE, demonstrating its scalability and superior energy efficiency for real-time SNN inference under constrained hardware resources.
### Title:
          Cross-Layer Co-Design of Low-Latency Stateful Logic Adders with Printed Memristors
 - **Authors:** Fabian Seiler, Kerem Kagan Güclü, Hongrong Hu, Gabriel Cadilha Marques, Jasmin Aghassi-Hagmann, Nima TaheriNejad
 - **Subjects:** Subjects:
Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Data movement between memory and processing units remains a major bottleneck in data-centric systems. Memristive Stateful Logic (SL) addresses this problem by performing Boolean operations directly on stored resistive states. However, arithmetic efficiency depends jointly on the device-supported logic primitive set, the dependency structure of the resulting operation sequence, and its mapping to datapath architectures. While prior designs typically optimize device, logic, and architecture layers separately, we jointly consider them to co-design a stateful adder. We experimentally demonstrate a mixed MAGIC and FELIX logic primitive set on printed Electrochemical Metallization (ECM) memristors and derive a full adder sequence optimized for inter-bit carry propagation. Mapping this sequence to bit-serial, bit-parallel, and bit-pipelined datapaths reduces the latter two to 2n+6 cycles for an n-bit addition. For 32-bit addition, this requires 60-88% fewer cycles than prior SL adders. Across four representative workloads, we achieve 3.7x-16.4x speedup over prior. These results show how cross-layer co-design can translate into improved workload-level performance.
### Title:
          HM3D-M3: A Benchmark for Multi-Agent, Multi-Modal, Multi-Object Goal Navigation
 - **Authors:** Hongyu Ding, Kanyu Xu, Mingjia Chen, Zixuan Chen, Jieqi Shi, Jing Huo, Yifan Zhang, Yang Gao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rapid progress in AI agents and robotics makes it a matter of the near future that humans are served by a team of robots. Such a team will receive several goals at once, each specified in whatever form is convenient for the human, such as a category name, a photo, or a spoken description. Existing benchmarks study multi-agent, multi-modal, and multi-object goal navigation in isolation, and a benchmark that places all three in one episode is missing. To fill this gap, we introduce HM3D-M3. A team of K agents starts at distributed locations in a photorealistic indoor scene and searches for an unordered set of M object goals, each given as an open-vocabulary category, an instance image, or an instance description. HM3D-M3 provides 1,000 validation episodes over 3,926 goals from 379 open-vocabulary categories, 100K observation-assignment training samples, and two team-level metrics, goal-level SR and makespan-normalized SPL. We further contribute two baselines. HiGA is a trained hierarchical goal assigner on top of a frozen open-vocabulary navigation policy, and LaViRA-M3 is a training-free team of VLM agents with shared mapping and progress analysis. Adapted multi-robot and zero-shot methods reach 16--27% SR, while our baselines reach 38--41% with complementary strengths and distinct failure modes. Furthermore, we deploy LaViRA-M3 on a heterogeneous three-robot team. Project page: this https URL
### Title:
          OneLA: Learning Many Worlds from Latent Actions
 - **Authors:** Ziyu Zhu, Zhaoxu Sun, Fan Jiang, Chiyu Wang, Junfeng Ni, Mu Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning world models across diverse domains calls for a unified control space, yet ac- tion interfaces vary across domains and action annotations are often scarce. Latent ac- tions learned directly from videos offer a promising way to establish such a space without explicit action supervision. However, learning shared latent actions across domains re- mains challenging, as variations in appearance, embodiment, and dynamics can entangle domain-specific visual cues with transferable transition structure. To this end, we intro- duce OneLA, a simple framework that learns continuous latent actions through a shared orthogonal dictionary and a common predictive objective, without task-specific designs or cross-domain alignment losses during latent action pretraining. These latent actions pro- vide a shared conditioning interface for world models, with lightweight adapters mapping native control commands into the same space. Conditioned on latent actions and the cur- rent visual state, the world model predicts context-dependent transitions for controllable rollout. OneLA improves action readout across domains and reduces action cycle-transfer rotation error by 24.8% over the strongest evaluated baseline. A joint-training comparison further shows a 20.5% improvement in Human Preference Score v3 (HPSv3) for real- scene generation. These results suggest a path toward general-purpose world models that learn from diverse videos and support flexible control through latent action space.
### Title:
          Fast spectral methods for Volterra integral equations
 - **Authors:** Xi Chen, Kuan Xu
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We develop novel methods for the fast construction of spectral approximations to smooth linear and weakly singular Volterra integral operators and for the fast evaluation of smooth nonlinear Volterra integrals. The proposed methods employ the Duffy mapping, which transforms the original indefinite integral into a definite integral and maps the original causal triangular domain to a square, thereby avoiding any artificial extension of the kernel function. For smooth linear and weakly singular Volterra operators, the resulting approximations are almost-banded and lower-banded, respectively. The $N\times N$ principal finite section of these approximations can be constructed in $O(N)$ and $O(N^2)$ flops, respectively, via recurrence relations. For Volterra integrals with a smooth kernel that depends nonlinearly on a given function, recurrence relations lead to fast evaluation with a complexity of $O(N^2\log N)$ when the function is approximated by a degree-$N$ Chebyshev approximant. These spectral approximations and evaluation procedures give rise to fast and stable spectral methods for solving Volterra integral equations, as well as a broad class of problems involving Volterra integral operators. Extensive numerical experiments show that these spectral methods significantly outperform existing methods in terms of stability, speed, accuracy, and ease of implementation.
### Title:
          HGRP: Heterogeneous Graph Neural Network for Routability Prediction
 - **Authors:** Yule Sheng, Yue Yuan, Shan Shen, Daying Sun
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Routability prediction enables rapid evaluation of placement quality without routing, providing effective feedback for routability-driven placement optimization. Recent machine learning methods have achieved efficient routability prediction through data-driven approach. However, their prediction performance highly depends on the capability of input representations to capture essential circuit information. To address the limitations of existing circuit representations in simultaneously preserving logical topology, physical layout and routing resource information, this paper proposes HGRP, a heterogeneous graph neural network for routability prediction. HGRP models the cells, nets, and routing grids as distinct types of nodes and explicitly represents topological connectivity, spatial mapping, and grid adjacency, thereby constructing a heterogeneous graph representation that preserves multi-level circuit semantics. Based on the representation, a heterogeneous message passing mechanism is developed to enable information interaction and feature fusion among distinct types of nodes, effectively learning the complex correlations between circuit structures and routing behaviors. Experimental results on the CircuitNet dataset show that HGRP improves F1-score by 18.69\% relative improvements compared with the state-of-the-art in the congestion prediction task. The source code is publicly available at this https URL.
### Title:
          VIGOR-MPC: Vision-Guided Objective Regulation MPC
 - **Authors:** Jelena Trisovic, Rahel Rickenbach, Marek Landert, Panagiotis Minos, Melanie N. Zeilinger
 - **Subjects:** Subjects:
Robotics (cs.RO); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Controlling an agent in an environment solely perceived through onboard vision is challenging: perception yields noisy, variable-length, and partially occluded context, while onboard compute is shared between perception and control, limiting the planning horizon executable in real time. We propose VIGOR-MPC, a modular student-teacher framework, agnostic to the perception pipeline, which addresses reference tracking across navigation tasks by distilling a privileged, field-of-view-aware long-horizon MPC into a computationally lightweight short-horizon MPC whose cost parameters are determined online from vision. The teacher operates in simulation with full state knowledge and a multi-trajectory formulation that guarantees the agent can stay within its field of view. The student observes only the noisy, occluded context produced by a perception module and learns, via a multi-level recurrent mapping, to infer cost parameters that aim to recover the teacher's behavior despite missing information. We evaluate VIGOR-MPC on vision-based autonomous racing in simulation and on hardware. Using only onboard perception of the track, VIGOR-MPC generalizes to tracks unseen during training and approaches the lap times of the privileged long-horizon teacher while reducing per-step computation by over 90%.
### Title:
          Fractional is Better: Learnable Derivative Orders in Neural Operator Learning
 - **Authors:** Fares B. Mehouachi, Saif Eddin Jabari
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural operators learn mappings between function spaces, enabling fast surrogate solutions to partial differential equations. Despite remarkable architectural diversity, these methods often share a common input representation: raw coordinate-value pairs $(x, u(x))$. We ask whether inputs aligned with PDE differential structure can improve learning. Through Picard iteration on mild solutions, we show that derivatives of the input appear explicitly in the solution operator, suggesting that providing derivative features should reduce the network's implicit differentiation burden. We prove this intuition: providing derivative features improves approximation bounds from $O(W^{-(s-m)/d})$ to $O(W^{-s/d})$, where $W$ is parameter count, $s$ is input regularity, $m$ is the PDE order, and $d$ is spatial dimension. Our central finding, however, is a surprise: the optimal derivative order $\beta^*$ is strictly less than the PDE order $m$. This gap arises from a bias-variance tradeoff in spectral space that we characterize in closed form. Learning $\beta$ from data achieves automatic spectral regularization. We introduce $\partial$-NO (del-NO), for derivative-augmented neural operators, an architecture-agnostic augmentation that provides learnable fractional derivative features to any neural operator backbone. Across benchmark problems and architectures, $\partial$-NO consistently improves prediction accuracy, with learned orders that reflect a representation of known physics modulated by noise and finite-sample constraints.
### Title:
          Tiered-Resolution Volumetric Mapping for Real-Time Simultaneous Planning and Mapping on Natural Outdoor Environments
 - **Authors:** Afonso E. Carvalho, David Portugal, Paulo Peixoto, George Kantor
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-time volumetric mapping for a planning robot is dominated by the cost of integrating and storing information at the finest resolution, yet only a small fraction of any map ever lies on or near a path the planner actually considers. We exploit this with a tiered-resolution mapping mechanism that integrates LiDAR into a single map structure at two resolutions simultaneously: fine inside a corridor around the robot's current plan, and coarse everywhere else. As opposed to traditional navigation pipelines where path planning uses the mapping result and provides no feedback, we propose a feedback loop where planning also informs mapping to dynamically integrate information at different leaf resolutions. Across two real-world teleoperated datasets, replayed and scored offline against an independent full-resolution map, the tiered maps are 13-15x smaller and require 6-8x less integration CPU time than a uniform fine map, while producing paths at a similar cost per meter as the ones generated from fine resolution maps on both scenarios. A uniform coarse map reaches the same size savings but its path quality collapses (+210% cost per meter) on the harder scenario, because it over-discretizes terrain the robot must traverse. Tiering approximates the coarse map's cheapness without its failure mode.
### Title:
          Towards Certifiable State Estimation under Observability Degeneracy
 - **Authors:** Baoshan Song
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Certifiable optimization provides global optimality guarantees for non-convex state estimation in robotics. However, under severe physical sensing degeneracy, convex Semidefinite Programming relaxations solved via Interior-Point Methods suffer from rank expansion, rendering direct semidefinite solving and spectral rounding algebraically invalid. In this paper, we establish a universal candidate-driven dual certification framework that resolves this challenge without incurring rank expansion. First, from an epigraph perspective, we prove that while sensing degeneracy expands the primal optimal set into a flat equi-cost face, cost tightness and multiplier recovery remain strictly intact, enabling global verification without direct semidefinite solving. Second, we propose an observability-aware local search using solution remapping, coupled with a closed-form dual multiplier recovery scheme that executes in sub-microsecond latency. Third, we derive a model-specific adaptive dual safety threshold parameterized by the minimum non-zero eigenvalue of the observable Hessian and uneradicated residual leakage, preventing false rejections of optimal candidates under weak observability. We validate our universal framework with robust registration under degenerate measurements.
## Keyword: localization
### Title:
          Physical Layer Anomaly Detection via Adaptive Gaussian Mixture Model
 - **Authors:** Mamady Delamou, Luan Chen, Arsenia Chorti
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Physical-layer spoofing attacks pose a critical threat to wireless localization systems by manipulating channel state information (CSI). Detecting such attacks becomes particularly challenging when the attacker and the legitimate node are spatially proximate, as their CSI characteristics become increasingly similar. To address this challenge in indoor scenarios, we propose an adaptive Gaussian mixture model (GMM)-based detection framework that learns legitimate CSI patterns and detects spatial inconsistency through statistical anomaly detection. Using a massive multiple-input multiple-output (MIMO) experimental dataset with 64 uniform linear array (ULA) antenna and 5 mm spatial resolution, we evaluated our detector against CSI spoofing attacks with spatial displacements ranging from 50 mm to 450 mm. The adaptive GMM achieves 95-98% detection rate for displacements above 150 mm while maintaining 1% false alarm rate. We benchmark our approach against conventional GMM, local outlier factor (LOF), one-class support vector machine (SVM) and k-nearest neighbors (k-NN) classifiers, demonstrating overall superior detection performance of our proposed classifier.
### Title:
          More Than Seeing: Vision as Scalable Anchors in Native Multimodal Pre-Training
 - **Authors:** Haoyuan Wu, Aoqi Wu, Jiani Hu, Bei Yu
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Native multimodal pre-training trains a single model from scratch on text and multimodal data, enabling it to understand both language and visual inputs. However, how visual signals shape scaling behavior and support capabilities beyond visual understanding remains unclear. We investigate this question through controlled visual-content ablations across model sizes and training budgets. Specifically, we replace image embeddings with content-free padding token embeddings. Retaining visual content improves text prediction on image-text examples without materially changing the lowest text-only loss at a given compute budget, the optimal balance of model size and training data, or aggregate language scores. The relative multimodal loss benefit grows approximately as a power law of compute. To test benefits beyond understanding images, we evaluate spatial reasoning from text descriptions alone. Both conditions improve with model and data scaling. During training of the largest model, visual gains are most sustained in localization, navigation, and symbolic planning, which involve maintaining object configurations or composing spatial updates; gains in spatial relations, geometry, and physical commonsense are less consistent. These findings identify visual content as a scalable anchor for multimodal learning, with benefits that extend beyond visual inputs while preserving aggregate language performance.
### Title:
          HyrCap: Hybrid Rank-Calibration of Action Proposals for Temporal Event Understanding
 - **Authors:** Rui Chen, Xingyu Chen, Pengxin Xu, Kai Chen, Junzhi Yu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Temporal action detection in long untrimmed videos suffers from inaccurate localization and low-quality proposals, especially with sparse annotations and ambiguous boundaries. For open-ended video understanding and LLM-driven event analysis, reliable proposals connect temporal localization, event annotation, and semantic understanding. However, conventional temporal action detection (TAD) pipelines lack explicit modeling of proposal localization quality, cross-representation support, and inter-proposal relations. We propose Hybrid Rank-Calibration of Action Proposals (HyrCap), a proposal-centric query-based TAD framework for temporal event understanding. Hybrid combines complementary video features with different localization cues, while Rank-Calibration adjusts proposal ranking confidence to reflect localization reliability and candidate competition. HyrCap treats dense query-based predictions as an over-complete temporal event hypothesis space. Cross-Representation Consensus Calibration, Localization Quality Estimation, and Proposal Redundancy Suppression improve proposal ranking reliability, localization quality, and candidate discrimination. Inspired by LLMs' capabilities in fine-grained semantic recognition, event description, and reasoning, we introduce HyrCap for Semantic Action Understanding, using calibrated proposals for standard TAD and as inputs to LLM-based semantic understanding. We define a staged evaluation protocol to separately measure event localization, segment-level semantic understanding, and combined event understanding performance. Experiments on public benchmarks show that HyrCap achieves state-of-the-art performance across multiple metrics and provides a finer-grained paradigm and evaluation protocol for query-based event segmentation and annotation.
### Title:
          Remember, Revisit, Revise: Scaffold Memory for Long-Horizon 3D Geometry
 - **Authors:** Soumick Sarker, Mengmi Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Geometry foundation models estimate camera poses and 3D scene structure from video sequences, but maintaining consistent reconstructions over long horizons remains challenging. Feed-forward models process long sequences as independent, fixed-length frame windows and align their predictions, causing pose and reconstruction errors to accumulate across windows. Streaming models retain information from past frames to inform future predictions, but cannot revise earlier estimates when later observations reveal errors. To address this, we introduce Scaffold MemOry for Revision (SMORE), a framework equipping frozen geometry foundation models with a revisable external memory for long-horizon inference. Inspired by hippocampal associative memory in biological brains, which links spatial context with sensory experience, SMORE associates where an observer is with what it observes, enabling past observations to be stored, retrieved, verified against new evidence, and revised when inconsistencies are detected. We evaluate SMORE with eight competitive geometry models on five datasets spanning camera pose estimation, multi-view depth estimation, 3D point-cloud reconstruction, simultaneous localization and mapping (SLAM), and novel view synthesis. Across all evaluated models, SMORE consistently improves long-sequence pose estimation, reduces multi-view depth error by up to 58%, reduces Chamfer distance for 3D point-cloud reconstruction by up to 43%, and achieves average trajectory error as low as 2.9 cm in long-horizon SLAM. By retaining corrected poses and observations, SMORE further improves the fidelity and spatial consistency of large-scale 3D scene reconstruction. These results establish revisable external memory as a flexible interface for extending pretrained geometry models beyond fixed-context prediction toward iterative, error-correcting inference over long visual sequences.
### Title:
          ProtModernBERT: Compute-Efficient Protein Language Modeling
 - **Authors:** Alberto Martínez, Natalia Flechas Manrique, Llorenç Espinosa-Portalés, Luc Andrea
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Quantitative Methods (q-bio.QM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large protein language models provide a powerful framework for learning sequence-function relationships and guiding experimental design. However, architectural improvements are underexplored, especially in low-compute regimes of relevance for resource-constrained research laboratories. We show that the training cost for encoder-only transformer architectures can be reduced by leveraging modern architectural refinements, offering an encouraging performance / compute-efficiency trade-off. We introduce ProtModernBERT, a modernized BERT-style model pre-trained on amino acid sequences, and compare it with ProtBert, Amplify, and ESM2 across a set of supervised structural tasks -encompassing secondary structure prediction, disorder prediction, and subcellular localization- and ProteinGym's zero-shot functional benchmark. We find that ProtModernBERT matches or closely tracks the performance of Amplify-120M and ProtBert with up to 80-90\% reduction in pre-training FLOPs, and narrows the gap to ESM2 when controlling for pre-training. Our analysis using a cluster-based validation protocol for hyperparameter selection and randomly initialized models disentangles the contributions of architecture and data, showing that modern components provide stronger inductive biases that are more consequential than parameter count in low-compute regimes.
### Title:
          FPV-CRASH: A Dataset for Offline Crash Moment Localization in Drone First-Person-View Videos
 - **Authors:** Jifan Zhang, Tingyu Wang, Qian Liu, Zhedong Zheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Crash Moment Localization aims to localize the major physical impact that interrupts controlled flight in an onboard first-person-view (FPV) video recorded by a drone, thereby providing a temporal reference for retrospective crash analysis in aerial robotics. However, existing crash-video datasets predominantly target surveillance or dash-camera footage, and their annotation schemes and task formulations are not designed for temporal localization of the major physical impact in UAV onboard FPV videos. To address this gap, we present FPV-CRASH, a dataset and fixed-protocol reference evaluation for offline Crash Moment Localization in drone FPV videos. FPV-CRASH contains 1,052 drone FPV clips (526 Crash and 526 Normal); each Crash clip has a single-frame reference annotation for the Crash Moment, and every clip is paired with four English captions automatically generated from sampled frames and the known Crash/Normal label. Normal clips carry no timestamp target and provide training-time background supervision. The captions support an auxiliary Text-to-Video Retrieval task, whereas localization inference remains video-only. We further provide a heatmap-based reference model that estimates a continuous Crash Moment timestamp from sparsely sampled frames. Under the fixed, non-source-disjoint clip-level protocol, the reference model reduces MAE from 1.12 s for the strongest fixed timing-prior baseline to 0.56 s (a 50% relative reduction) and achieves a median absolute error (MedAE) of 0.33 s; the fraction of clips localized within 0.5 s rises from 37.14% to 65.71%. The release includes annotations, available source video identifiers and URLs, clipping metadata, fixed split lists, and preprocessing code so that the reportable portion can be reconstructed without redistributing source footage. At submission time, all source-compilation URLs remained accessible.
### Title:
          A posteriori error bounds for cumulative energy fields in irreversible gradient damage
 - **Authors:** Yubo Huang, Xiongyu Hu, Xin Lai, Cheng Lyu
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cumulative energy fields in irreversible evolution depend on the loading path, even when terminal states and global work agree. We derive a posteriori bounds for these fields in scalar gradient damage with a prescribed driving density. A perturbation estimate for the incremental obstacle map yields a continuous loading history, which is enclosed by nondecreasing residual supersolutions. A primitive identity transfers this enclosure to the cumulative field. An exact endpoint-rule defect and outward arithmetic certify the output delivered by the numerical method. The analysis separates spatial, loading, and algebraic errors and gives sufficient conditions for certificate decay. Computable realizations use splines and verified supersolutions in one dimension and on two-dimensional rectangles. The production bounds cover the independently enclosed errors of all 417 saved histories from 28 adaptive calculations and all 25 fixed-parameter controls. In a narrow-localization case, the verified relative error decreases from approximately 158.78\% to below 2.125\% at a 5\% certified target. Source-oriented marking reduces accumulated matrix--vector work by 35.9\% and 51.9\% in two comparisons. A mechanically generated two-dimensional benchmark shows how auxiliary supersolutions sharpen constant barriers and enable acceptance of both loading orders.
### Title:
          Resilient Angle-Constrained Formation Control and Localization Under DoS Attacks (Extended Version)
 - **Authors:** Nhat-Minh Le-Phan, Ziliang Lyu, Lihua Xie
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper studies resilient angle-constrained leader--follower formation control and localization of multi-agent systems under asynchronous denial-of-service (DoS) attacks, which block individual sensing and communication links. To preserve the well-posedness of angle-based localization, an all-or-nothing triangle integrity protocol (ANTIP) is proposed to convert edge-wise attacks into triangle-wise ones, and DoS attacks are classified into localizability-maintained and localizability-broken attacks. First, with relative position measurements over attack-free links, resilient formation tracking laws are designed for leaders with constant velocities and with time-varying velocities comprising translational, rotational, and scaling motions. These laws guarantee asymptotic tracking and finite-time recovery of tracking, respectively, when the duration of localizability-broken attacks is suitably bounded. Second, with only angle measurements and communications, a resilient simultaneous localization and formation control (RSLAF) scheme is developed. It combines a finite-time distributed observer, which estimates the exosystem matrices and states under asynchronous DoS attacks, with a perturbation-based localization law that prevents localization from getting stuck at degenerate configurations. The theoretical results are rigorously proved and illustrated by numerical simulations.
### Title:
          CoDy: Codec Dynamics as Complementary Priors for Unsupervised Temporal Action Localization
 - **Authors:** Tianyu Yan, Qingyi Yang, Qin Yang, Xufei Guo, Yuan Tang, Rui Wang, Yixue Hao, Long Hu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unsupervised temporal action localization (UTAL) aims to identify action categories and localize their temporal boundaries without annotation supervision. Existing methods typically derive supervision for both tasks solely from RGB and optical-flow representations, often resulting in noisy category assignments and inaccurate temporal boundaries. In this work, we reveal an overlooked property of video codecs: group-of-pictures quantization patterns preserve category-discriminative dynamics, while motion-vector and residual variations exhibit pronounced responses around action transitions. Based on this insight, we propose CoDy, a codec dynamics-guided framework that exploits the codec as complementary information to the visual view for UTAL. CoDy integrates a codec-enhanced view with RGB and flow through confidence-aware consensus clustering, producing reliable soft pseudo-labels. It further converts codec dynamics into a class-agnostic boundary prior, which supervises visual boundary learning and guides proposal initialization and iterative refinement. The codec branches are only used during the training stage and introduce no extra codec-side computation at inference. Extensive experiments on THUMOS14 and ActivityNet v1.3 demonstrate that CoDy consistently outperforms existing UTAL methods and achieves state-of-the-art localization performance. These results establish codec signals as effective annotation-free priors for jointly inferring which actions occur and when they occur.
### Title:
          VisualWorldBench: A Fine-Grained Multi-Task Benchmark for Evaluating Visual World Knowledge in MLLMs
 - **Authors:** Chen Chen, Zheming Liang, Jiaqi Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual world knowledge is a core capability of multimodal large language models (MLLMs), underpinning knowledge-intensive visual question answering and fine-grained visual reasoning. However, existing benchmarks remain limited in two key respects. First, their category coverage is narrow: most benchmarks span only a small number of categories across a few domains, falling far short of the open-ended scale of real-world visual entities. Second, their task construction is often insufficiently rigorous: models can answer correctly using coarse-grained cues, vague associations, or elimination strategies without truly mastering precise concepts, making it difficult to accurately assess their knowledge of fine-grained entities. We introduce VisualWorldBench, a taxonomy-grounded multi-task benchmark built on a hierarchical taxonomy of 21,291 leaf-node classes across 8 visual domains, with 32,541 evaluation instances whose ground-truth labels cover 15,479 categories across four complementary tasks: closed-set recognition, contrastive selection, precise localization, and open-world naming, covering different directions of knowledge retrieval and varying degrees of answer openness to comprehensively evaluate visual world knowledge. Most questions are constructed from taxonomically proximate categories, forcing precise discrimination among fine-grained entities. Experiments reveal that the strongest closed-source model achieves only 80.4% average accuracy, exposing capability gaps hidden under conventional benchmarks. We further construct VisualWorldBench-50K, a training resource covering 50K+ categories. Fine-tuning on VisualWorldBench-50K yields over 21 percentage points improvement on VisualWorldBench, with consistent transfer to public fine-grained recognition and visual knowledge benchmarks.
### Title:
          ReferFlow: Beyond Final-Target Localization for Complex Referring Expressions
 - **Authors:** Tianyi Gao, Han Fang, Xin Wei, Yaoyao Zhong, Zhaoyan Pan, Weijie Zhu, Hongbo Sun, Zhiyu Lin, Kaicheng Yang, Jinglin Xu, Ye Yuan, Hao Li, Hao Sun, Jingmin Xin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal Large Language Models have made significant progress in referring expression comprehension (REC), yet most REC benchmarks still focus on final-target localization. Complex queries often involve intermediate visual references with different dependencies on prior grounding, but final-only evaluation leaves this process unexamined. To address this gap, we formulate trajectory-level REC, in which models receive an ordered sequence of grounding steps constructed from a single complex query and localize the target regions associated with each step. We instantiate this setting in ReferFlow-Bench, which characterizes structured region transitions through four trajectory types, namely Refinement, Shift, Reset, and Mixture. Experiments show that current models struggle to consistently ground intermediate visual references across successive steps. We further propose ReferFlow, which decouples interleaved text-latent trajectory generation from coordinate decoding. Specifically, Stateful Region Latent Reasoning represents each target region as an object-indexed state composed of continuous latents, with explicit visual and spatial supervision to preserve region information for subsequent grounding. Trajectory-Aware Parallel Decoding then recovers all coordinate blocks in parallel through four geometry-constrained refinement rounds, with each block conditioned on its corresponding trajectory prefix, thereby reducing within-box sequential dependencies and eliminating cross-box autoregression. We further apply Grounding-Aware GRPO to promote consistent grounding across steps and learn adaptive trajectory generation from complex REC queries. ReferFlow achieves leading performance on general REC benchmarks and ReferFlow-Bench.
### Title:
          CoWear: Towards Collaborative Wearable Inertial Localization with Multiple Smart Devices
 - **Authors:** Zhuoyuan She, Zhanpeng Zhang, Yapeng Chen, Jiale Wang, Xin Xie, Ming Xia
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Consumer smart devices observe the same human motion from different body locations, yet existing inertial-localization benchmarks rarely provide synchronized heterogeneous wearables with device-specific motion ground truth. We present CoWear, a dataset and reference framework for collaborative inertial localization using a smartphone, smartwatch, and smart glasses. The dataset contains over 30 participants, over 300 walking sessions, and more than 30 hours and 100 km of aggregate device trajectories, with each device individually tracked by motion capture. To enable collaboration across distinct body motions, we train role-specific estimators to predict the displacement of a common reference device over synchronized temporal windows. Their predictions are transformed to the world frame using gyroscope integration and fused according to learned uncertainty. Experiments using phone, glasses, and watch as reference targets show that multi-device fusion consistently improves both displacement and trajectory rollout accuracy over individual-device estimation. CoWear provides a dataset and reproducible baseline for studying collaborative inertial localization across heterogeneous consumer wearables.
## Keyword: transformer
### Title:
          MonoMIP: Multi-Height Inverse Perspective Mapping for Monocular 3D Object Detection
 - **Authors:** Emir Ulurak, Furkan Kıraç
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular 3D object detection methods increasingly rely on depth-guided transformers, but they operate entirely in the perspective image plane where spatial relationships are distorted by foreshortening. We propose MonoMIP, a dual-decoder framework that adds complementary 3D geometric reasoning through Bird's-Eye View (BEV) features constructed via Multi-Height Inverse Perspective Mapping. We perform IPM at K elevation planes spanning ground to rooftop, producing an ordered stack of height-conditioned metric BEV features that reduces above-ground misprojection and exposes depth-dependent appearance variation across planes. A BEV decoder with multi-scale deformable attention aggregates this multi-height evidence per query, while a depth-guided 3D decoder provides complementary perspective-space predictions. Without extra training data, MonoMIP attains 25.84% Moderate AP3D|R40 on KITTI val and 21.66% on the official test set for Car, outperforming recent published monocular methods on both the KITTI and Waymo benchmarks.
### Title:
          PairIT: Autoregressive Transformers for Low-Data Molecule Optimization
 - **Authors:** Hannah Lawrence, Bodhi P. Vani, Ji Won Park, Natasa Tagasovska, Samuel Don Stanton, Andrew Martin Watkins, Michael Maser, Ewa M. Nowara
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Chemical Physics (physics.chem-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generating novel molecules with desired properties is a central challenge in drug discovery. Although foundational work focused on de novo generation, practical use cases require a more complex setting: conditioning on an initial seed molecule, optimizing multiple properties, and operating in data-sparse regimes. We introduce PairIT, a flexible training framework for autoregressive transformers over SMILES sequences that enables seeded generation by learning from pairs of structurally similar molecules. By leveraging matched pairs, the model learns to generate local, chemically meaningful edits that improve a property of the seed molecule. Prompt tokens extend this framework by specifying the target property, desired direction, and approximate magnitude of change. Multiple prompt tokens can be concatenated to enable multi-property optimization at inference time. For properties where pair supervision alone is insufficient, reinforcement learning post-training can further improve optimization, providing a tunable trade-off between proximity to the seed and the optimization objective. PairIT naturally supports pretraining on a large dataset and fine-tuning on a smaller dataset, which is critical for performance in data-sparse regimes. Surprisingly, we observe diminishing returns to the scale of the pretraining dataset. We demonstrate empirically on MoleculeNet and Therapeutics Data Commons datasets that, with appropriate paired-data curation, a standard transformer model of modest size (68M parameters) can achieve robust seeded molecular optimization in low-data regimes.
### Title:
          Collective Learning for Unified Robotic Manipulation via Predictive Dynamics Adaptation
 - **Authors:** Shaocheng Liu, Yuan Meng, Zhenshan Bing, Alois Knoll
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning a collective policy for state-based Cartesian manipulation across diverse robotic embodiments presents a fundamental challenge due to embodiment-dependent transition dynamics. Collective learning aggregates multi-robot experience to discover shared task structure, yet naive aggregation can average incompatible action modes when different embodiments realize the same Cartesian command through different transition behavior. This leads to strategy ambiguity and performance collapse on dynamically outlying embodiments. To address this, we propose PACE, a two-stage collective learning framework that separates shared task-space intent from embodiment-dependent transition dynamics. The first stage employs a representation layer pre-trained on offline trajectories to extract task-level context from collective data. The second stage introduces a decision layer equipped with a predictive dynamics adapter. By forcing the latent state to predict future transitions, this adapter acts as a latent regularizer that grounds the policy in the transition behavior of the executing robot while preserving real-time inference without online planning. Evaluations across simulated embodiments demonstrate that our method prevents performance collapse on distinct robots. It achieves over 93\% overall success and 89\% on dynamically out-of-distribution zero-shot simulated robots, outperforming the Transformer behavior cloning (82\%) and diffusion policy baselines (66\%). Physical KUKA deployment further validates the feasibility of the full state-based pipeline under zero-shot sim-to-real transfer.
### Title:
          Titan-Llama: Retrofitting Pre-trained LLMs with External Neural Memory Modules
 - **Authors:** Sarah Pan, Ali Behrouz
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers are efficient to pre-train at scale because attention permits parallel computation across sequence positions, but long-context inference requires increasingly large KV caches. Efficient recurrent alternatives reduce the asymptotic complexity of inference, but their sequential dependence limits token-wise parallelism during training, making them harder to scale. Further, the current paradigm of extending long context tasks creates competing notions of retaining information precisely and keeping long-context inference efficient. To address this gap, we introduce Titan-Llama, a post-training method for retrofitting attention-based language models with a hierarchical memory architecture that updates parameters at test-time. Titan-Llama applies a blockwise attention mask and preserves full-fidelity attention over recent tokens while compressing historical context into recurrent, fixed-size neural memory modules (NMMs). Our formulation allows pre-trained attention layers to be replaced without training a new language model from scratch. On Llama-3.2-1B-Instruct, Titan-Llama raises accuracy over segmented attention windows from 23.87\% to 40.51\% on QuALITY and from 14.50\% to 40.75\% on LongHealth. Inference benchmarks show more than 20\% faster prefill, 37\% faster decode at medium context lengths, and 24\% lower steady-state decode memory usage in the evaluated configurations. Together, these results demonstrate that incorporating memory architecture mechanisms that utilize test-time training effectively modulates long-context behavior of pre-trained models, offering a practical route to adapting pre-trained transformers for efficient long-context inference. Our code is released on Github \href{this https URL}{GitHub}
### Title:
          Decoupled Drift-Diffusion World Models for Consistent Future Frame Prediction
 - **Authors:** Anton Arapin, Aditya Singh, Yixin Wang, Jun Gao, Bernadette Bucher
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World models of visual information predict future image frames conditioned on given action sequences. This predicted scene evolution is driven by deterministic changes such as controlled motion on a robot platform, as well as stochastic changes such as rendering of manipulated objects or previously occluded regions. Our key insight is that the spatial location of these stochastic changes is itself learnable. We leverage this insight by jointly regressing both the deterministic next-state prediction and the spatial uncertainty map, then using the uncertainty map to guide a conditional diffusion process. We propose Decoupled Drift-Diffusion World Model (D3WM), which uses a transformer trained with a Gaussian negative-log-likelihood objective to produce both the deterministic next-state prediction and a spatial map of heteroscedastic aleatoric uncertainty. The learned uncertainty map then provides a structured spatial gate for a conditional diffusion model: deterministic regions are anchored to the predicted state, while uncertain regions, such as disocclusions or dynamic textures, are sampled by the diffusion process. We frame this decomposition under a variance-gated stochastic differential equation that separates deterministic drift from stochastic diffusion. D3WM shows improved results over competitive baselines in two distinct types of action spaces: robotic tabletop manipulation and camera motion.
### Title:
          Narrowing the Collaboration Gap, Probably
 - **Authors:** Mirah Shi, Marcel Hussing, Ira Globus-Harris, Natalie Collina, Aaron Roth, Surbhi Goel
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models are increasingly deployed as teams of agents that hold different private information about a shared task. How should such agents concisely communicate in a way that promotes aggregation of decision-relevant information? Communicating only proposed actions can discard decision-relevant uncertainty: two agents may prefer the same action for different reasons. We study an alternative interface in which agents communicate calibrated beliefs over actions. We first analyze a simple synthetic setting that captures the structure of multi-round reasoning under partial information. In this setting, we show theoretically and empirically that communicating unbiased probabilities can be strictly more powerful than communicating actions. We then test the same principle in a collaborative maze-solving task with trained transformers and pretrained LLM agents. Our results demonstrate that probability communication outperforms action communication when the exchanged predictions preserve calibrated uncertainty. When communicated probabilities are biased, we show that the benefits of probability communication can disappear. We give a post-hoc conversational calibration intervention that consistently improves decision-making by correcting these biases both in a toy transformer setting and when pretrained LLMs use the corrections in context. These results suggest that probabilistic communication is useful for multi-agent collaboration not merely because it transmits more information, but because calibrated uncertainty gives other agents a reliable object to update on.
### Title:
          Do Syntax Heads Influence Model Behavior?
 - **Authors:** William Timkey, Tal Linzen
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer language models develop attention heads that specialize in syntactic relations, for example, attending from verbs to their subjects. Do these heads play a causal role in the model's syntactic predictions? Evidence for such a role is mixed to negative: even when we force these heads to attend to a distractor noun other than the subject, the model's syntactic predictions are still more consistent with the subject than with the distractor. Interventions on specialized syntax heads had a significantly stronger effect on syntactic predictions than interventions on random heads, but only in one of the two measures we propose.
### Title:
          LLMs program using Reusable and Composable Abstract Representations
 - **Authors:** Casper L. Christensen, Kyle J. Ray, Dmitry Manning-Coe, Adam Shai, Paul Riechers
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Programming Languages (cs.PL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 When writing code, the same computation can be expressed in different programming languages and through different implementation strategies. We show that the activations of LLMs capture this shared structure in reusable and composable abstract representations when they generate code. These representations emerge in the middle layers, are reusable across programming languages, and afford the model an impressive amount of generalization ability when generating code under various interventions. Using activation steering, we show that function, programming language, and implementation strategy can be independently manipulated. The independent interventions on language and function can be flexibly composed to control code generation, even in cases when the prompt contains no information about language and function. We additionally find that finetuning on examples of arbitrarily defined functions in one programming language transfers to other languages, consistent with the models reusing abstract features of code generation that are shared across different examples. Finally, to study how such abstract representations come to be, we implement a minimal model of shared, reusable, and composable structure in a synthetic setting, and show that transformers trained on such data learn representations that reuse these parts flexibly across contexts.
### Title:
          Copy-Paste Language Models
 - **Authors:** Nathan Godey, Yoav Artzi
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers are intuitively considered to be efficient at copying from their inputs. We actually show that the ability of LLMs to copy in context can be improved through explicit modeling. We propose Copy-Paste Language Models (CPLMs), which add a lightweight Copy-Paste head to the conventional language modeling (LM) head. CPLMs improve training efficiency, downstream performance, and offer new operating points in long-context and retrieval setups. We validate our approach by pretraining models from 135M to 1.7B parameters, showing improvements across all scales and backbones with negligible training and inference overheads. We explain the success of CPLMs by showing that they partially mitigate the LM head gradient bottleneck through an alternative gradient path.
### Title:
          Long-horizon Video Generation with Slot Memory Addressed By Region Tokens
 - **Authors:** Eren Cetin, Julius Erbach, Vukasin Bozic, Hyojun Go, Zixiang Zhao, Nikolai Kalischek, Federico Tombari, Konrad Schindler, Dominik Narnhofer
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Memory for long-horizon video generation must satisfy two competing requirements: it must remain bounded so generation can continue indefinitely, while still recovering what was observed at a place when the camera returns, regardless of how long ago it was seen. Reconstruction-based memories provide spatial recall by caching and reprojecting explicit geometry, but require growing storage and depend on estimated 3D structure. Recurrent memories keep a constant-size state, but retention is governed by temporal recurrence, causing old observations to fade with time. We introduce SMART, a slot memory addressed by region tokens, which combines bounded storage with spatially addressed recall. SMART stores content in a constant-size slot recurrence whose writes are addressed by the observing camera and whose reads are queried by the rendering camera, without constructing an explicit 3D representation or maintaining a growing cache. Consequently, recall is conditioned on inter-view geometry rather than on recency. Each read additionally provides a confidence estimate that conditions a chunk-causal diffusion transformer, allowing it to selectively trust retrieved content while relying on its generative prior elsewhere. On long trajectories in Memory Maze and Minecraft, SMART maintains high-fidelity recall far beyond its training horizon while using constant memory and per-step cost.
### Title:
          Why don't Graph Transformers attend to the same token?
 - **Authors:** Alexandre Bismuth
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In large language models (LLMs), attention concentrates heavily on the first token. This 'attention sink' is believed to protect deep models against over-mixing. Even though graph transformers face a related pressure, we find that a SoTA graph transformer, GRIT, rarely forms sinks on molecules, and that it sinks less when trained on larger graphs, the opposite of the trend in LLMs. In principle, a graph can prevent sinks: we prove and show empirically that its symmetry and locality limit the attention any node can receive. On molecules, however, with distinguishable atoms and global attention, neither limit prevents sinks; what stops them lies in the model. We find that the attention scoring function is the main cause. Replacing GRIT's gated logit with a dot product raises its sink rate from 0.09 to 0.68 on identical graphs. In Graph Transformers using dot-product attention, removing the sink gives about the same error as removing a random node, while GRIT's most-attended nodes matter to its predictions. Attention sinks are therefore a property of dot-product attention rather than of Transformers. In our experiments, they form when dot-product scoring has a distinguishable node to concentrate on.
### Title:
          AutoPoly-HE: Autonomous Design of Polynomial Activations for Privacy-Preserving Encrypted Inference
 - **Authors:** Zeinab Elkhatib, Kamrul Hasan, Ali Sekmen, Imtiaz Ahmed, Tariqul Islam
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Privacy-preserving machine learning has become critical for deploying artificial intelligence in sensitive domains such as healthcare, finance, and infrastructure monitoring. Homomorphic encryption (HE) enables secure inference on encrypted data. Despite its advantages, HE is not compatible with nonlinear activation functions found in machine learning models. Existing methods mitigate this problem by manually designing polynomial approximations for these activation functions. However, these functions do not account for the differences in dataset characteristics or model architecture. Furthermore, these functions are also limited to the accuracies of convolutional neural network (CNN) models. In this work, we propose an autonomous framework that selects polynomial activation functions tailored to each dataset and model. Using this framework, we analyze the interdependence between polynomial activation design and model architecture by evaluating several CNN ResNet and Vision Transformer models across multiple datasets. Experimental results demonstrate that the proposed framework generalizes across multiple architectures, including ResNet-18, ResNet-34, ResNet-50, ViT-S/16, ViT-B/16, and ViT-L/16. Across all datasets, transformer-based models maintain higher accuracy under polynomial approximation, while convolutional models exhibit increased degradation as task complexity grows. In addition, latency analysis reveals that the proposed CLS token based inference pipeline significantly reduces computational overhead by eliminating depth-dependent operations, shifting the primary cost to encryption and decryption. These findings demonstrate that the proposed method not only adapts polynomial activations across architectures, but also enables efficientencrypted inference through both activation design and pipeline optimization.
### Title:
          Asymptotic Behavior of Transformers
 - **Authors:** Katy Blumer, Da-Cheng Juan, Jon Kleinberg, Ravi Kumar, Cyrus Rashtchian, Andrew Tomkins
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Statistics Theory (math.ST)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper we study the behavior of transformer networks generating text over long periods of time. We show that even a three-token, single-layer attention-only transformer can fail to converge. We then study a rich class of transformers with arbitrary finite depth, layer normalization, MLPs, RoPE encodings, and an arbitrary mix of local and global layers. Every transformer in this class has a softmax temperature threshold above which its empirical cache distribution converges to a unique limit, independent of initial conditions. We show further that, while each transformer has a temperature threshold, the supremum of this set is infinite, so there is no global minimal temperature that forces all transformers to converge.
### Title:
          VLX-Go: Robust Embodied Tracking through Multi-Stage Learning and On-Policy Refinement
 - **Authors:** Kyusong Lee, Heting Ying, Tiancheng Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Embodied visual tracking requires a robot to identify a designated target from visual observations and control its own motion to follow that target through an environment. Following an isolated person is a comparatively simple demonstration of embodied visual tracking, but following the intended person among distractors remains challenging. Existing methods exhibit a substantial drop in success from single-target to distractor tracking, motivating a focus on the shared spaces that person-following robots must navigate. We present \method{}, a vision--language waypoint policy built around the hypothesis that visual and language representations should be aligned before tracking-specific motion is learned. The policy combines complementary frozen visual encoders, multiscale temporal context, a transformer backbone, and a lightweight head for robot-centric waypoint prediction. Its training progresses through vision--language alignment, multimodal reasoning mid-training, and tracking specialization on 19,532 oracle episodes. Compared with 41.54\% distractor-tracking success for our earlier OmTrackVLA model, the complete multi-stage recipe achieves 55.80\%. We then explore on-policy refinement using filtered oracle labels for states visited by the policy. This preliminary study adds 2.42 percentage points of distractor-tracking success, reaching 58.22\%, while reducing collision rate by 1.99 pts. The final policy records the highest distractor- and ambiguous-tracking success rates among the compared methods. These results support staged multimodal learning as a promising direction for tracking among distractors and motivate further study of on-policy refinement for person following in shared spaces.
### Title:
          A Critical Review of Grid Integration Challenges and Flexibility Opportunities for Large-Scale Data Centers
 - **Authors:** Bibek Dhakal, Manohar Chamana, Biswambhar Gayen, Jatendar Kumar, S M Shams Rahman, Aaqib Peerzada, Ki Yeob Lee, Olatunji M. Adeyanju, Bhaskar Mitra, Soumya Kundu, Stephen Bayne
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid proliferation of cloud computing and artificial intelligence workloads is fundamentally reshaping the magnitude, spatial concentration, and electrical characteristics of data center power demand. Data centers differ from conventional commercial loads because they combine high rack densities, converter-dominated interfaces, thermally coupled cooling, uninterruptible power supplies, programmable workloads, and increasingly complex behind-the-meter generation and storage within a single facility. This review examines their grid integration from utility and sustainable-energy perspectives across resource planning, large-load interconnection, distribution feeders, market operation, real-time dynamics, power quality, and asset management. Particular attention is given to distribution-level issues that receive limited treatment in broader energy reviews: bidirectional operation on renewable-rich feeders, harmonic propagation and resonance, ride-through and reconnection, transformer derating, cable ampacity, neutral-conductor heating, protection, and measurement. Static, composite, physics-based dynamic, calibrated, impedance, electromagnetic transient, and hybrid load models are compared according to study purpose and data requirements, and utility coordination platforms, uninterruptible power supply and battery control, workload flexibility, renewable co-location, cogeneration, fuel cells, thermal storage, and clean firm supply are assessed. The central finding is that requested peak demand and annual energy matching alone cannot establish reliable or sustainable integration. Credible assessment must consider hourly and locational supply, network deliverability, marginal emissions, lifecycle and water impacts, backup obligations, rebound, asset health, and verified operating capability.
### Title:
          ixi-sLM: On-Device sLM for AI Call Agent Service
 - **Authors:** Han-Sang Lee, Kyuho Lee, Juneyoung Park, Seongbae Lee, Jin Kyu Park, Minjae Kim, Yuri Hong, Jinwoo Lee, Youngwook Kwon, Seongwan Kim, Seungheon Hyeon, Jaeho Lee, Kiduk Kwon
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Running an AI call agent on-device makes it private, network-independent, and free of per-query cloud cost, but shipping one as a real-world service imposes constraints a cloud deployment never faces: ~1GiB memory budget, in-call latency and thermal limits, static-integer NPU execution, Korean STT input far from sLM pretraining, and cloud-level quality expectations. We bring ixi-sLM, a 1.2B Korean sLM, to mobile NPUs through ON-DEVICE MODELING: domain-adaptive modeling trims the vocabulary by call frequency to shrink the embedding and LM head that take nearly half the model under INT4 transformer weights and refits the tokenizer to call speech (18% fewer tokens on call traffic), while task-aware quantization calibrates on real calls and assigns per-module mixed precision by activation sensitivity. A single domain-adapted model runs ixi-O's two production services, AI Call Summary and AI Call Answering, at 94% of a state-of-the-art cloud LLM's task-weighted quality; our on-device modeling carries that quality onto the NPU with only a marginal drop in overall score, in an 803MiB model (28% of FP16) at 23% of the CPU's per-call energy. The same recipe deploys across Qualcomm and Apple NPUs and serves several million ixi-O subscribers in production.
### Title:
          DeBoneDiT: Depth-Driven Conditional Bridge Diffusion Transformers for Bone Suppression in Chest X-Ray Images
 - **Authors:** Yifei Sun, Fenglei Fan, Junhao Jia, Wenming Deng, Hongxia Xu, Changmiao Wang, Ruiquan Ge
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Chest X-Ray (CXR) is a primary modality for diagnosing pulmonary diseases, yet the overlap of bony structures often obscures critical radiographic findings, increasing the risk of diagnostic uncertainty. While Dual-Energy Subtraction (DES) is the clinical benchmark for bone suppression, its widespread adoption is primarily hindered by specialized hardware requirements and increased radiation exposure. Recently, diffusion-based generative models have shown promise for this task, yet they are still constrained by reconstruction-biased latent compression, prior-induced domain gap, and a scarcity of high-quality paired datasets. To address these challenges, we propose DeBoneDiT, a depth-driven conditional bridge diffusion Transformer architecture for efficient high-resolution bone suppression. We first introduce Depth Auto-Encoder (DAE), a structure-aware vision tokenizer for latent compression. By incorporating a multi-level depth feature loss derived from the pretrained Depth Anything V2 encoder, DAE preserves both visual fidelity and structural consistency. Second, we formulate bone suppression as a source-conditioned Brownian bridge diffusion process, leveraging CXRs as both the diffusion prior and structural guidance to narrow the source-to-target domain gap and maintain anatomical plausibility. Furthermore, we have constructed and released SZCH-X-Rays, the largest publicly available high-quality paired dataset for bone suppression to date, comprising 741 pairs of CXR and DES soft tissue images. Extensive experiments and downstream evaluation demonstrate that DeBoneDiT achieves superior bone suppression performance with reduced computational overhead.
### Title:
          Digital Self-Interference Cancellation for In-Band Full-Duplex Systems Based on Transformer Neural Operators
 - **Authors:** Zhijie Su, Shiquan Zhang, Qiaolin He
 - **Subjects:** Subjects:
Information Theory (cs.IT); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Digital-domain self-interference cancellation is essential in in-band full-duplex radios after passive suppression and analog cancellation. It is particularly challenging when the desired signal is strong relative to the residual self-interference. In this regime, conventional iterative digital cancellers update their coefficients from desired-signal-contaminated received samples and may suffer substantial performance degradation. This paper reformulates digital-domain self-interference cancellation as an operator-learning problem. The proposed framework learns the temporal evolution of the residual self-interference channel from historical observations and uses the learned operator together with the known local transmit signal to reconstruct the current residual self-interference. A Transformer neural operator is used to realize this framework. The resulting method is trained in a desired-signal-free setting and then applied in the presence of a desired signal. A continuity-based analysis characterizes the sensitivity of the learned operator to the resulting input perturbation. Numerical experiments in static and time-varying channels, including time-varying SIR conditions, demonstrate stable cancellation performance over a wide range of interference levels. At 30 dB SIR, the proposed method improves the cancellation performance by 5--15 dB over the considered conventional methods.
### Title:
          Test-Time Forecasting: Recurrent Depth Enables In-Context Dynamics Prediction
 - **Authors:** Jeffrey B. Lai, John Quinn, Anthony Bao, William Gilpin
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Foundation models for dynamical systems can forecast unseen partial differential equations (PDEs), ordinary differential equations (ODEs), and time series during inference. However, it remains an open question whether these foundation models truly learn generalizable in-context forecasting strategies. We show that looped transformers are capable of emulating propagators for dynamical systems in-context by first establishing a link between linear attention and (extended) dynamic mode decomposition. We then generalize this insight into the $\textit{Test-Time Forecasting}$ (TTF) framework in which a one-step forecaster leverages iterations of gradient descent as recurrent depth. We demonstrate that lightweight TTF models trained on ODEs and PDEs generalize to out-of-distribution system dynamics during autoregressive rollout after being trained for one-step prediction. Our results reinforce TTF as a theoretically motivated framework for designing recurrent depth models capable of forecasting unseen dynamical systems at test-time.
### Title:
          Learning Visual Speech Representations via Cross-Modal Distillation and Joint Face-Lip Modeling
 - **Authors:** Jing-Xuan Zhang, Genshun Wan, Jianqing Gao, Jia Pan, Yumei Zhang, Lichen Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Lipreading remains challenging due to the inherent ambiguity of visual speech cues and their sensitivity to head pose and video resolution. In this work, we propose FLARE, a framework for robust visual speech representation learning via cross-modal distillation and joint face-lip modeling. FLARE leverages semantically rich Whisper representations as the acoustic teacher signal, converting them into discrete distillation targets through a random-projection quantizer and pretraining the model with a masked prediction objective. To capture complementary visual information, FLARE employs a dual-stream architecture that jointly processes lip region-of-interest (ROI) and full-face inputs, where the lip stream captures finegrained articulatory motion and the face stream encodes broader facial dynamics. During pretraining, auxiliary audio input is incorporated to facilitate cross-modal alignment, and modality dropout is applied to encourage robust visual-only representations. For downstream lipreading, FLARE serves as a visual encoder coupled with either a lightweight Transformer decoder or an LLM-based decoder. Evaluated on LRS2, LRS3, and the out-of-domain WildVSR benchmark, FLARE achieves strong lipreading performance, with word error rates of 11.7%, 13.2%, and 34.3%, respectively. A progressive design study confirms the contribution of each major component. Further analyses demonstrate that joint face-lip modeling improves robustness under degraded video resolution and large head pose variation, while yielding more phoneme-discriminative visual representations. Code and pretrained models are available at this https URL.
### Title:
          RoboSpan: Learning Modular Coordination Policies for High-DoF Whole-Body Mobile Manipulation with Teleoperation
 - **Authors:** Keqiang Ren, Xuecheng Ye, Hanyu Liu, Zhihua Wang, Tao Jian, Yunsheng Ma, Jiayi Wen, Xinran Li, Zhigong Song
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Whole-body mobile manipulation suffers from two fundamental challenges: inherent motion heterogeneity across locomotion, arm, and hand modules, and progressive error accumulation over long-horizon multi-stage tasks. Existing teleoperation platforms also lack integrated dexterous tactile sensing to support coordinated whole-body decision-making. This paper presents RoboSpan, a high-DoF whole-body teleoperation and demonstration platform, and the Hierarchical Modular Framework (HMF) for learning modular coordination policies. HMF functionally decouples the 29-DoF action space into fine hand manipulation, arm pose adjustment, and mobile-base spatial configuration branches, and introduces the Coordinated Modular Embodied Transformer (COMET) with inter-modular cross-attention to enable dynamic information exchange and action coordination. Vision-language model driven hierarchical task decomposition structurally suppresses temporal error propagation, while a full-palm 2D tactile representation encodes distributed contact signals for cross-module tactile empowerment. Experiments on a physical 29-DoF robot demonstrate that the proposed method achieves over 20\% higher task success rate than mainstream baselines across a range of long-horizon whole-body tasks, markedly improving stability and robustness in contact-rich manipulation.
### Title:
          Beyond Static Positional Encoding: Bayesian Time-aware Attention for Non-Stationary Long-term Time Series Forecasting
 - **Authors:** Xinjie Lan, Yunbo Mei, Leheng Zhou, Hao Qi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers have demonstrated strong performance in long-term time series forecasting (LTSF), yet modeling non-stationary temporal dependencies remains challenging. In this paper, we interpret self-attention as a Bayesian posterior over attended positions, combining a content-based prior induced by scaled dot-product similarity with a temporal-evidence likelihood induced by positional encoding. This formulation provides a probabilistic interpretation of how positional encoding shapes the temporal dependencies captured by self-attention. Building on this perspective, we derive a population-level evidence lower bound (ELBO) that characterizes the role of positional encoding in forecasting weakly stationary time series. Our analysis further highlights a limitation of static positional encoding: when temporal dependence structures vary across input windows, a fixed temporal bias must accommodate heterogeneous dynamics and can therefore be suboptimal for non-stationary forecasting. Motivated by this analysis, we propose Bayesian Time-aware Attention (BTA), which employs a mixture-of-experts (MoE) router to adaptively combine temporal kernels and generate input-conditioned, head-specific positional biases. Extensive experiments on standard LTSF benchmarks demonstrate that BTA consistently improves forecasting performance across multiple Transformer backbones and achieves competitive overall performance with modest computational overhead and stable training.
### Title:
          A Graph-Based Analysis of Comparability, Scale, and Attribution in Private Transformer Inference
 - **Authors:** Souvik Das, Ariful Azad, Nitesh Saxena
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rising privacy concerns around large language models have accelerated research in private Transformer inference (PTI). Synthesizing the empirical claims in this line of research, however, is hindered by multi-dimensional cryptographic progress and inconsistent evaluation contracts. In this work, we systematize the field by constructing an empirical graph of 62 PTI systems, mapping system attributes to node features and evaluation compatibility to edges. A three-tiered analysis of this graph illuminates the state of private inference. Node-level attribution shows that cryptographic progress drives performance gains across most systems, yet always co-occurs with other factors (model fidelity, hardware, cost accounting). Edge-level auditing shows that only 1 of 1891 candidate system pairs is directly comparable under shared assumptions. Finally, graph-level analysis shows that the scaling frontier of private inference has plateaued at 13B parameters and projects the cost of deploying current PTI techniques on production-scale Transformers. Overall, this graph-based framework equips the community to evaluate PTI claims transparently and channel technical speedups into deployment-scale private inference.
### Title:
          Divergent Paths: Learning an Outcome-Predictive Representation of LLM Agent Trajectories
 - **Authors:** Alexander Gill, Guram Gogia, Francisco Guzmán
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this work, we reframe agentic trajectories as paths through a shared embedding space of actions and environmental observations. We show that successful and failed rollouts of the same task separate in this space, with simple per-task discriminators predicting held-out rollout outcomes at up to 0.95 AUROC across three agent benchmarks and three policy models. To exploit this signal across tasks, we introduce Precog-RM, a transformer-based model that meta-learns a representation in which outcome prediction can be performed in a few-shot setting. We show that Precog-RM generalizes to unseen tasks and models, and gives confident predictions of trajectory success long before termination. Deployed as an early stopping controller for Group Relative Policy Optimization (GRPO) on Tau2-Bench, Precog-RM cuts training FLOPs by up to 47.3\% while maintaining performance comparable to baseline GRPO.
### Title:
          PolyMorph: Learning Locomotion Policy for Cross-Embodiment Adaptation
 - **Authors:** Hyunsik Oh, Seunghun Jeon, Donghoon Youm, Jungwoo Hur, Hyeongjun Kim, Jeong Hyun Lee, Moonkyu Jung, Jemin Hwangbo
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reinforcement learning has enabled robust locomotion for legged robots, but learned policies are typically tied to a specific robot morphology and require additional engineering when the number of legs, actuators, or mechanical properties change. We present PolyMorph, a morphology-conditioned framework that learns a single locomotion policy for heterogeneous legged robots. PolyMorph converts each robot's URDF into joint-link modules and combines a recurrent encoder, graph-based Transformer, and per-joint decoder to generate actions across variable leg counts and joint configurations. To improve training stability, PolyMorph uses morphology-normalized rewards, adaptive robot sampling, and URDF-derived PD-gain initialization. We evaluate PolyMorph in simulation across bipedal, tripedal, and quadrupedal robots, including unseen morphology variants and platforms, and deploy the policy on real quadruped platforms operated in multiple configurations. The results show that a single PolyMorph policy generalizes across diverse robot morphologies without per-robot policy retraining.
### Title:
          DAGFormer: Global Topology Prediction for Transformer Cross-Layer Connections
 - **Authors:** Xiaocong Yang, Yuren Hao, ChengXiang Zhai
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose DAGFormer, a Transformer language model whose cross-layer connections are planned by a jointly trained topology predictor. Beyond the residual connections in a standard Transformer, DAGFormer adds direct connections from earlier layers to later ones, and the predictor controls the strength of every connection based on input tokens. Unlike existing cross-layer routing architectures, which set each layer's connections separately, DAGFormer plans the routing of the whole model at once. On matched OLMo-2 pairs from 75M to 1B parameters, DAGFormer lowers WikiText-2 perplexity by 17% to 25% over the vanilla Transformer, and a 1B DAGFormer trained on 5B tokens outperforms the vanilla model trained on 10B. Against four routing baselines with the same data and budget, it reaches the lowest perplexity at 75M, 300M and 1B. The gain carries over to 13 commonsense, science, reading and math evaluation tasks (2.0 to 2.5 points higher mean accuracy at 300M and 1B) and to instruction finetuning (63% to 70% AlpacaEval win rate against the vanilla Transformer, leading every routing baseline), and under structured pruning DAGFormer degrades the least in five of six settings.
### Title:
          Self-Conditioning Enables Deep Sequential Reasoning in Flow Matching
 - **Authors:** Zeyang Zhang, Linxiang Gao, Meiqi Gu, Xingyan Chen, Minrui Luo, Kaifeng Lyu, Tianxing He
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent work has explored visual reasoning through image generation, where models solve visual-reasoning problems by directly generating solution images. Intuitively, iterative samplers such as flow matching are well suited to this task, since each sampling step may resemble one reasoning step. However, in this work, from a circuit complexity perspective, we show that this intuition is misleading. We prove that as long as the model outputs satisfy certain mild regularity conditions, the trajectory of the vanilla flow-matching sampler can be simulated by a constant number of sequential rounds of parallel model evaluations. Consequently, additional sampling steps cannot increase the expressive power of a constant-depth backbone model under the standard complexity-theoretic model of transformers. We then reveal that self-conditioning, which conditions the model on the previous step's estimate of the final image, plays a previously unrecognized role in removing this bottleneck. Controlled experiments on diverse visual-reasoning tasks show that flow matching with self-conditioning achieves higher accuracy and greater reasoning depth than vanilla flow matching, and its performance improves with more sampling steps. Theoretically, we prove that with self-conditioning, a constant-depth backbone can achieve expressive power equivalent to that of space-bounded Turing machines. Our study suggests a design principle for future visual reasoning research: carry more information between sampling steps, so that additional steps translate into deeper reasoning.
### Title:
          Eye, Robot: Learning Expressive Gaze Dynamics via a VLM-Guided Transformer-VAE
 - **Authors:** Yuhang Hu, Junlin Lyu, Yuan Fang, Xiaoying Shen, Lechen Zhang, Jiong Lin, Judah Goldfeder, Steven Tian, Hod Lipson
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Gaze coordinates attention in human interaction through coupled eye, head, and eyelid motion. A humanoid robot must choose where to look while generating a suitable movement toward that target; fixed tracking rules alone do not model the temporal structure of human gaze. We separate these tasks with an asynchronous vision-language model that selects a scene referent, a reactive perception module that maintains fixation, and a Realistic Gaze Transformer (RGT) that generates target-conditioned motion. RGT is a Transformer-VAE trained on markerless human recordings retargeted to the robot's 11-DoF joint space: self-supervised pretraining encodes recent full-head history, and autoregressive fine-tuning exposes the model to its own predictions during rollout. At inference, a four-dimensional binocular-eye trajectory conditions coordinated neck and eye motion; an auxiliary blink predictor triggers eyelid templates during playback. On a two-second benchmark in which all controllers receive the same ground-truth target, RGT-Base obtains the lowest reported overall seven-joint MSE, and physical demonstrations show the integrated targeting and control pipeline. The evidence establishes robot-space kinematic fidelity and real-time RGT inference; perceived naturalness and open-vocabulary target-selection accuracy remain questions for controlled evaluation.
### Title:
          ESL-former: Event Sparse Linear Transformer for FPGA-Accelerated Malware Detection
 - **Authors:** Jun Yang, Yumeng Cao, Yingxuan Xiao, Changhong Li, Shangru Zhou
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer based intrusion detection has shown strong potential for identifying unknown malware variants, but its deployment on resource constrained edge devices remains difficult due to the high computational and memory cost of self attention. This paper presents an event sparse Linear Transformer framework for malware detection on FPGA edge platforms. Instead of relying on an explicit attention matrix, the proposed method derives token and channel importance directly from the accumulated key value state of Linear Transformer. A contribution aware scoring function is introduced to measure the perturbation of each token or kernel channel to the linear attention state, allowing redundant tokens and low contribution channels to be removed without constructing quadratic attention maps. To translate sparsity into practical hardware acceleration, the proposed design further replaces conventional binary mask based execution with a Top K active token buffer and a hardware compaction unit. The selected active tokens and channels are reorganized into dense fixed length data streams, enabling downstream processing elements to execute regular multiply accumulate operations with reduced redundant memory access and control overhead. This design is suitable for low power FPGA based malware detection, where both latency and on chip resource usage are critical. Experimental evaluation demonstrates that the proposed sparse Linear Transformer can reduce hardware cost while preserving malware classification accuracy.
### Title:
          Beyond State Capacity: Why Retrieval Breaks in Mamba
 - **Authors:** Nir Yarden, Amit Ben-Artzy, Roy Schwartz
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mamba models underperform Transformers on in-context retrieval. This gap is usually attributed to Mamba's fixed-size recurrent state, which loses information as the context grows. We challenge this assumption by focusing on query-first retrieval, a setup in which the query precedes the context and state capacity should not be the binding constraint. We show that even in this setting Mamba lags substantially behind Transformers, despite its selection mechanism, which was designed to distinguish relevant content from distractors. We then demonstrate that the Mamba selection gates have sufficient control over the state updates to influence the model output: intervening on specific gates alone can swing accuracy between extremes. However, as gates are input-dependent, they require the incoming token's representation to encode its relevance to the query. We therefore probe token representations across layers, and find that the relevance signal emerges only gradually with model depth, and that the gates begin to reflect it only several layers deeper. Crucially, we find that gates in retrieval-critical layers are not yet aligned with relevance. The selection mechanism is thus expressive enough to solve the task, but it commonly operates on a relevance signal that has not yet arrived. Mamba's retrieval bottleneck therefore extends beyond state capacity: even when capacity is sufficient, the delayed emergence of relevance information across depth often prevents successful retrieval.
### Title:
          ProtModernBERT: Compute-Efficient Protein Language Modeling
 - **Authors:** Alberto Martínez, Natalia Flechas Manrique, Llorenç Espinosa-Portalés, Luc Andrea
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Quantitative Methods (q-bio.QM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large protein language models provide a powerful framework for learning sequence-function relationships and guiding experimental design. However, architectural improvements are underexplored, especially in low-compute regimes of relevance for resource-constrained research laboratories. We show that the training cost for encoder-only transformer architectures can be reduced by leveraging modern architectural refinements, offering an encouraging performance / compute-efficiency trade-off. We introduce ProtModernBERT, a modernized BERT-style model pre-trained on amino acid sequences, and compare it with ProtBert, Amplify, and ESM2 across a set of supervised structural tasks -encompassing secondary structure prediction, disorder prediction, and subcellular localization- and ProteinGym's zero-shot functional benchmark. We find that ProtModernBERT matches or closely tracks the performance of Amplify-120M and ProtBert with up to 80-90\% reduction in pre-training FLOPs, and narrows the gap to ESM2 when controlling for pre-training. Our analysis using a cluster-based validation protocol for hyperparameter selection and randomly initialized models disentangles the contributions of architecture and data, showing that modern components provide stronger inductive biases that are more consequential than parameter count in low-compute regimes.
### Title:
          Refine Actions If Needed: Adaptive Action Chunk Refinement for Robot Manipulation
 - **Authors:** Hanlin Liu, Zichen Zhou, Jiacheng Zhang, Liuyuan Na, Jin Jin, Guangyan Chen, Yufeng Yue, Gen Li, Fangqiang Ding
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Computationally lightweight manipulation policies predict executable actions with low inference latency, but prediction errors can limit task success. Iterative generative policies can achieve higher task success rates, but repeated network evaluations increase inference latency. Refining action proposals from computationally lightweight policies can combine these strengths, but the amount of refinement needed varies across states. We introduce RAIN (Refine Actions If Needed), a framework that predicts action errors at different refinement levels to decide whether and how much to refine each executable proposal, before performing any refinement. We train an ensemble to predict these errors by comparing action proposals and their refined versions with expert actions from offline demonstrations, without requiring explicit labels of refinement needs. Calibration balances uncertainty, computation, and temporal consistency. We evaluate RAIN on eight ManiSkill tasks and four real-robot tasks. In simulation, our policy achieves 66.6% success, approaching the best evaluated diffusion-policy success rate with 5.71 times lower policy latency. On the real robot, success increases from 55.0% with Action Chunking with Transformers (ACT) to 72.5%, with comparable average successful completion time. Matched controls show that dynamic routing maintains the strongest observed fixed-refinement success level with 26.6% fewer refiner evaluations. Project page: this https URL.
### Title:
          Learning to Compute Is Not Learning to Retain or Reuse in Looped Transformers
 - **Authors:** Peilong Zhou, Hongtao Zhang, Yulong Huang, Cangyuan Li, Mingyu Chen, Ying Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Looped transformers compute by applying one block repeatedly, so they can run for more loops than they were trained with. Recurrent reasoners are known to overthink: iterating past the trained depth can turn a correct answer into a wrong one. Such a late error can reflect failed computation, loss of retention, or a state that later computation cannot reuse. We separate these cases in in-context Mealy-machine execution, where a simulator supplies intermediate targets and exact counterfactuals for hidden-state interventions. Models trained to answer at loop 32 are fully correct there but keep only 22% of these answers at loop 64. Retention depends on what training asks for: supervising one randomly chosen position per example, instead of always the last, keeps 99.8%, and randomizing the number of training loops also helps; truncating gradients, as in progressive training against overthinking, does not. The computation itself is exact: position $k$ is computed at loop $k$, and swapping its loop-$k$ hidden vector for the one from another input redirects every later position to that input's exact continuation (237/237 pairs in each of ten models). Retention, however, is not reuse. Even in models that keep nearly all answers, holding each position $k$ fixed from loop $k$ drops accuracy to 4--6%, whereas holding it from loop $k+4$ is harmless. A released recurrent maze network trained to avoid overthinking behaves the same way. Learning to compute is thus not learning to retain, and avoiding overthinking does not make a state reusable when its answer first appears.
### Title:
          Q-MAGIC: Quad-only Mesh Autoregressive Generation via Singularity-Aware Circular Relative Offset Tokenization
 - **Authors:** Yuming Zhao, Zezeng Li, Weimin Wang, Xiang Wu, Na Lei
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autoregressive models have proven effective for triangular mesh generation by transforming it into predicting the next face, converting the non-differentiable connectivity prediction into a sequence of token predictions. However, generating quad-only meshes remains challenging because quad faces impose stricter topological constraints than triangles. The model must not only serialize quad faces into a valid token sequence, but also support unambiguous connectivity reconstruction during de-serialization. To address this, we propose Q-MAGIC, a novel autoregressive model for quad mesh generation. We first introduce a tailored serialization scheme for quad meshes, which requires at least two new vertices for the next face and is less flexible than triangles due to strict wiring constraints. To meet these requirements and reduce serialization length, we propose a singularity-aware serialization that prioritizes wiring from singular points, leading to more coherent traversals. Additionally, we propose a circular relative offset tokenization that encodes geometry mainly via local relative offsets. Built upon this representation, an autoregressive Transformer learns the underlying distribution of quad meshes via next-token prediction, enabling effective quad mesh generation. Extensive experiments demonstrate that Q-MAGIC produces more compact sequences while consistently improving geometric fidelity and mesh quality compared to state-of-the-art methods.
### Title:
          When Does Depth Help? Understanding Layerwise Inference in Tabular Foundation Models
 - **Authors:** Wenwen Gong, Haotian Gu, Zhen Yang, Jiaying Ma, Hanqing Zhang, Zhongshen Wang, Jingjun Wang, Shouyi Xu, Wei Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based tabular foundation models (TFMs) achieve state-of-the-art performance on small to medium-sized tabular prediction tasks while processing diverse inputs through a shared stack of layers. Recent layerwise analyses identify strong predictive performance in early TFM representations and substantial overlap in computation across layers. However, early predictive accessibility alone does not establish whether later layers are dispensable for every input, and aggregate accuracy can obscure which inputs benefit from additional computation. We study all 24 in-context-learning layers of TabPFN-3 across 272 classification datasets, combining representation geometry, prediction trajectories, truncation, and structural interventions, while also examining related representation dynamics in four additional TFMs. We uncover a pronounced expansion-compression trajectory, with stronger late dimensional contraction associated with larger increases in class-prototype separation. A targeted analysis of early-stabilizing samples shows that substantial representational changes persist after predicted classes stabilize, while locally ambiguous queries obtain larger accuracy gains from shallow to late layers than well-separated queries. Repeating a single pretrained block or perturbing layer order reduces predictive performance on average, constraining simple post-hoc substitutions in the frozen model. These findings distinguish predictive accessibility, class stability, and the benefits of continuing computation, supporting an input-dependent assessment of depthwise redundancy in TFMs.
### Title:
          Sparse Transformer: a Controlled Testbed for Mechanistic Interpretability
 - **Authors:** Anton Korznikov, Alexey Dontsov, Elena Tutubalina
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mechanistic interpretability aims to decompose neural network computations into human-understandable features, yet progress is limited by the absence of ground-truth units to evaluate against. We address this with a Sparse Transformer (ST): a 5-layer language model trained on TinyStories whose wide, TopK-sparse MLP forces neuron specialization. We show that ST neurons are highly interpretable: they outperform a loss-matched dense transformer by 43% on AutoInterp, and circuits of a median of 12 neurons suffice to reproduce individual model predictions. This testbed allows us to directly compare feature learning methods: Transcoder, which approximates the MLP input-output mapping, recovers ST's neuron vectors with 52.6% higher cosine similarity than Sparse Autoencoder, which only reconstructs outputs. Furthermore, the ST enables a controlled study of polysemanticity: distilling its sparse MLP into a dense counterpart reveals how compression leads to feature superposition. These results show how a known reference basis sharpens evaluation and understanding, a role we hope the ST can serve for the field.
### Title:
          Choosing the Number of Attention Heads from Intrinsic Dimension: A Small-Scale Study
 - **Authors:** Arjun Boya, Charan Sai Bandaru, Masthanaiah Pillimetla, Kavana Chidanandappa
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The number of attention heads in a transformer is usually set by convention or grid search. We test a simple heuristic for setting it in advance: estimate the intrinsic dimension of token representations without labels, and use roughly that many heads. We estimate intrinsic dimension with a nested-dropout VAE trained on DistilBERT embeddings of WikiText-2, choosing the KL weight at the knee of the VAE's rate-distortion curve rather than by hand. This gives $k^*=9.2$ (95% CI [8.6, 9.8]). In a small 4-layer transformer trained from scratch, 10 heads and 32 heads are statistically equivalent on SST-2 and on MRPC (paired TOST over 10 seeds, $\pm1$ point margin), with 69% fewer attention parameters for the 10-head model. Training 10 heads from the start also slightly outperforms training 32 heads and pruning to 10 (0.6 points, $p=0.008$). The evidence is narrow: two classification tasks, one small architecture, no pretrained models, and no formal link between intrinsic dimension and head count. We present the result as a practical heuristic worth testing at larger scale, not as a general principle.
### Title:
          Towards Learning-Guided Discovery of Extremal Geometric Constructions: A PatternBoost Study
 - **Authors:** Deepak Ajwani, Paula Carroll, Rishikesh Gajjala, Ananta Manoranjan, Ryan O'Connor, Rajiv Raman, Saurabh Ray, Aimen Taha
 - **Subjects:** Subjects:
Computational Geometry (cs.CG); Combinatorics (math.CO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Extremal constructions play a central role in the design and analysis of algorithms. Integrality-gap instances expose the limitations of relaxations, while hard configurations reveal structural sources of computational difficulty. Such constructions, however, are still typically discovered through a slow, manual process. This paper investigates how machine learning can accelerate their discovery to support algorithm design and analysis. We build on PatternBoost, a framework alternating local search with generation from a trained transformer, using its Axplorer implementation to investigate three problems: integrality gaps for maximum independent set of rectangles, integrality gaps for stabbing unit squares with axis-parallel lines, and hard instances for recursive guillotine cutting. By exploring candidate representations, local search operations, and surrogate models used to rank candidates before exact verification, we carefully adapt the framework to these combinatorial geometry this http URL naive representations and search strategies fail to find non-trivial instances, our tailored adaptation discovers numerous non-trivial constructions. For stabbing unit squares, the method reaches a gap of $20/13\approx 1.54$, improving on the literature's best known lower bound of $3/2$. Purely automated search converges rapidly and then plateaus, prompting the question of what is required to push the bound higher still. We find that initial instance diversity plays an important role: with modest expert input via a structured staircase construction, the system reaches an improved integrality gap of $14/9\approx 1.555$. These results demonstrate that machine learning and domain expertise can be combined to discover new extremal constructions that advance algorithmic lower bounds.
### Title:
          Empirical Boundaries of Reservoir Computing for Few-Shot Sequence Pattern Tasks
 - **Authors:** Mario Mallea, Angela Nebot, Franscisco Mugica
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Efficient sequence modeling remains a fundamental challenge in machine learning. Despite the success of Transformers, recurrent neural networks (RNNs) have recently re-emerged as efficient alternatives. Particularly, Echo State Networks (ESNs) offer a compelling framework of randomized RNNs that have been extensively studied for time-series forecasting and dynamical systems. This paper presents an empirical analysis of distributional, architectural, and optimization variants of ESNs evaluated on few-shot sequence-to-sequence (seq2seq) pattern tasks. These synthetic tasks utilize discrete symbol sequences, characterized by delays, inactive phases, and triggered markers to isolate and evaluate memory and pattern recognition capabilities. The minimality of these tasks is crucial to understand the strengths and limitations of machine learning models. Furthermore, when the input signal utilizes a one-hot encoding, ESN dynamics are governed strictly by their weight distributions, offering an ideal lens through which to study reservoir computing. Our findings map the performance boundaries of ESNs relative to state-of-the-art (SOTA) models. We show that preserving a linear state regime is vital for memory tasks, such as pattern completion or simple copy. We propose a data-dependent modulation mechanism for nonlinear input injection into the reservoir (G-ESN). G-ESN functions as a statistical filter capable of solving tasks that conventional ESNs cannot (the adding problem and bracket matching). Finally, for Deep ESNs, we evaluate a shared readout mechanism across layers that outperforms conventional concatenated readouts on structural tasks, including selective copy, sorting problem, and bracket matching.
### Title:
          Provable Transformer Context Compression for In-Context Reinforcement Learning
 - **Authors:** Yajie Zhao, Yingjun Mo, Zhiyong Wang, Bo Tang, Chao Xu, Fang Kong
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers can perform in-context reinforcement learning without parameter updates. However, existing theoretical constructions often require context sizes that grow with the number of sampled transitions, leading to increasing memory costs in large-scale problems. This raises a fundamental scalability question: how much context is intrinsically necessary to carry out such learning? We answer this question for fixed-policy TD evaluation. We show that, with a shared linear decoder, the minimum context dimension required to exactly reproduce the first $L$ TD iterates is the Krylov dimension induced by the sampled transitions. When the available context dimension $m$ falls below this threshold, exact reproduction is no longer possible. In this regime, we characterize the optimal approximation error and show that it decays as $\Theta(\gamma^m\max\{1,1/(m(1-\gamma))\})$ where $\gamma$ is the discounting factor. Moving from representation complexity to actual memory cost, we characterize the optimal retained memory for exact continuous representations as $\Theta(nk_L)$ and show experimentally that on a sampled task whose exact rank is full but whose numerical rank is small, a context accurate to $10^{-2}$ is $88.7\%$ smaller than the sparse sufficient statistics of TD. Finally, we establish the learnability of the shared executor through pretraining by proving global convergence of an auxiliary objective over effective attention parameters under suitable task diversity. Experiments across diverse TD evaluation problems validate parameter recovery and the predicted context--accuracy tradeoff.
### Title:
          GDBA-Net: A Gated Dual-Branch Adaptation of SAM2 for Robust Cross-Domain Nuclei Segmentation
 - **Authors:** Biplab Poudel, Betserai Albert Magarire, Anish Kumar Shah, Jiacheng Xie, Dong Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate nuclei segmentation underpins quantitative computational pathology, yet remains challenging due to morphological variability, weak boundaries, nuclear crowding, and pronounced domain shifts arising from differences in tissue preparation, staining, and acquisition. While deep learning and recent foundation models have improved segmentation performance under matched distributions with the original training data, their generalization across heterogeneous histopathology domains remains limited. We introduce GDBA-Net, a parameter-efficient nuclei segmentation framework built around the proposed Gated Dual-Branch Adapter (GDBA). GDBA-Net adapts a frozen SAM2 encoder by integrating pretrained semantic representations with explicit frequency-derived structural priors. The complementary representations are independently transformed through Grid MLP branches and dynamically integrated using sample-adaptive channel-wise gating, selectively emphasizing structural cues relevant to nuclear delineation. Despite using only 4.3 million trainable parameters, GDBA-Net achieves state-of-the-art in-dataset performance and consistently superior cross-dataset generalization across six diverse nuclei segmentation benchmarks under fully supervised, cross-dataset, and five-shot adaptation protocols, outperforming competing CNN-, transformer-, and foundation model based methods. Comprehensive ablations confirm that these gains arise from the coordinated design of semantic-frequency complementarity and adaptive gating rather than increased model capacity. By uniting transferable semantic representations with explicit structural priors, GDBA-Net provides a robust, annotation-efficient solution to domain variability in nuclei segmentation. this https URL
### Title:
          RTAformer: Relation-Transition-Aware Transformer for Video Scene Graph Generation
 - **Authors:** Jaeyeon Heo, Geuntaek Lim, Yukyung Choi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video scene graph generation (VidSGG) aims to capture objects and their evolving relationships in videos. This requires accounting for both the persistence of object identities and abrupt changes in relationships. Existing methods aggregate information across frames to exploit temporal context, but an emphasis on consistency can obscure these changes. As a result, a model may retain its previous prediction even after the underlying relation has changed. We refer to this failure mode as relational semantic inertia. To address this issue, we propose Relation-Transition-Aware Transformer (RTAformer), a one-stage framework that separately models entity persistence and relation changes. It injects calibrated differences between adjacent-frame relation queries to guide predicate updates, while cross-frame instance alignment during training helps reduce cross-frame representational drift. Experiments on Action Genome show improvements in recall and mean recall over existing methods, with ablation studies supporting the contributions of the proposed components and comparisons using matched backbones showing larger gains on relation-transition frames than on non-transition frames.
### Title:
          What Do Foundation Models for Market Microstructure Learn? A Controlled Study with Synthetic Limit Order Books
 - **Authors:** Fernando Acero
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autoregressive transformers trained on limit order book (LOB) message streams are increasingly proposed as foundation models for market microstructure. Because the generative process of real markets is unknown, these models can be judged only by the realism of their output, leaving open what they actually learn. We make the question answerable by inverting the setup: we train GPT-style models on order flow from simulators whose latent parameters are known, so that the Bayes-optimal predictor, the generating state, and the exact data entropy serve as references. Measured against them, next-token pretraining on order flow implements amortized Bayesian inference over market regimes. The learned predictive matches the exact Bayes optimum to within a millinat per token and approaches the oracle floor even on a nonstationary family whose latent state drifts within an episode, a regime that requires filtering. The latent regime is linearly decodable from frozen activations, well above baselines, so a frozen-model read-out calibrates simulator parameters more accurately than windowed maximum likelihood at a fraction of the cost. In our experiments these capabilities are not produced by scale: capacity and token volume saturate early, and it is the diversity of training regimes, not the token count, that determines generalization to unseen markets. On real NASDAQ data, zero-shot transfer is set by how well the simulator prior covers real flow: an enriched mixture nearly closes the gap to an in-domain baseline, and pretraining beats from-scratch training at every budget across held-out tickers. Known ground truth turns average next-token loss, which is uninformative near the entropy floor, into an exact comparison against the Bayes-optimal and oracle predictors.
### Title:
          RepForcing: Representation-Space Initialization for Autoregressive Video Distillation
 - **Authors:** Siming Fu, Zheming Fu, Lianrui Mu, Haoyang Huang, Chaojie Gu, Ruizhe He
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Distilling pretrained video diffusion models into few-step autoregressive (AR) generators typically combines student initialization with distribution matching distillation (DMD). An intermediate AR teacher can provide causally compatible targets for ODE initialization. However, causally compatible targets alone do not ensure high-quality generation under a short sampling schedule. We analyze the posterior-mean predictions favored by direct latent regression and empirically find that causal ODE initialization alleviates blur but still leaves fine detail unresolved. To address this limitation, we propose Representation Forcing, which learns few-step causal initialization through representation-space supervision rather than intermediate-teacher trajectory regression. The student is trained with teacher forcing by comparing clean predictions and training targets through normalized features of a frozen video diffusion transformer. This phase reuses the synthetic videos generated by a bidirectional model for AR teacher training and replaces both teacher training and causal ODE distillation, without generating additional causal ODE trajectories. The subsequent asymmetric DMD procedure remains unchanged. Empirical results show that, at four sampling steps, RepForcing better preserves generation quality than intermediate-teacher-based initialization before DMD. After DMD, our four-step chunk-wise model improves VBench Total from 84.04 to 84.66 (+0.62 points) and VisionReward from 6.326 to 10.074 (+59.25%) over the reported causal-ODE-based baseline.
### Title:
          Attention-Based Spatio-Temporal Approach for Fire and Smoke Detection
 - **Authors:** Alireza Mirrashid, Mohammad Khoshbin, Ali Atghaei, Hassan Shahbazi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In various industries, smoke and fire are two of the most important threats in the workplace. One of the common methods for detecting smoke and fire is the use of infrared thermal and smoke sensors, which cannot be used in outdoor applications. Therefore, the use of vision-based methods seems necessary. The problem of smoke and fire detection is spatiotemporal and requires spatiotemporal solutions. This paper presents a method that uses spatial features along with temporal-based features to detect smoke and fire in the scene. It consists of three main parts; the task of each part is to reduce the error of the previous part so that the final model has a robust performance. This method also uses transformer modules to increase the accuracy of the model. The results of our model show the proper performance of the proposed approach in solving the problem of smoke and fire detection and can be used to increase workplace safety.
### Title:
          Neural POS Tagging for the Low-Resource Saraiki
 - **Authors:** Usman Nawaz, Muhammad Junaid Iqbal, Muhammad Asaf, Mariam Munsif Mir, Faisal Rehman, Tahir Alyas, Muhammad Hasnain
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Part-of-speech tagging is a fundamental sequence labeling task and an important component for many downstream natural language processing applications. However, Saraiki, written from right to left in a Perso-Arabic script, remains an under-resourced Indo-Aryan language, despite being spoken as a mother tongue by 28,849,579 people (approximately 28.9 million) according to Pakistan 7th Population and Housing Census 2023. This paper presents a manually annotated Saraiki Universal POS tagging dataset developed from plain-text. We annotated the text with 17 POS categories. We evaluate three pretrained transformer encoders under the same fine-tuning setup: XLM-RoBERTa base, Urdu RoBERTa small, and multilingual DistilBERT. Experimental results over five random seeds show that XLM-RoBERTa base achieves the best performance, with 87.29% +/- 0.21% development accuracy and 88.60% +/- 0.21% test accuracy. Urdu RoBERTa small and multilingual DistilBERT also provide competitive results, suggesting that multilingual and related-script pretrained encoders are effective for Saraiki UPOS tagging. The dataset, evaluation setup, and baseline results introduced in this work provide a benchmark for future research on Saraiki NLP and low-resource sequence labeling.
### Title:
          Training Dynamics of Transformers on Unbounded Inputs: Attention Learning Can Lag Output Layer Learning
 - **Authors:** Yaomengxi Han, Debarghya Ghoshdastidar
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The success of transformers is attributed to several factors, including their capacity to express formal languages over variable-length inputs, and ability of the attention mechanism to focus on relevant input features. However, there is limited understanding of the training dynamics of shallow transformers, specifically how to decouple the learning of the attention and the output (feedforward) layer. A natural extension of the theory of one-step gradient feature learning in feedforward networks suggests that one could first learn the attention weights with a single gradient step, and then train the output layer. We show that this fails for a shallow transformer trained to recognize a star-free language from unbounded-length input. We prove that the transformer can be trained to recognize the language with a three-phase gradient descent: the output layer is updated first, followed by an attention update, and the output layer is fine-tuned in the third phase. In contrast, the language cannot be learned by training only the attention or output layer, or by a single attention-layer update followed by finetuning the output layer. We empirically show that ``attention learning lagging output layer learning" is beneficial in other language recognition, regression, and in-context learning tasks as well.
### Title:
          HRTF Upsampling and Personalization via Neural Operators
 - **Authors:** Meenakshi Krishnan, You Zhang, Ramani Duraiswami, C. Phillip Brown
 - **Subjects:** Subjects:
Sound (cs.SD); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Head-related transfer function (HRTF) spatial upsampling from sparse measurements is a fundamental challenge in personalized binaural audio. We formulate HRTF upsampling as an operator learning problem and introduce SPARO, a neural operator that maps sparse measurements at a set of spatial directions to the HRTF field, a continuous representation that can be queried at arbitrary positions. SPARO projects the measurements onto a learned set of spherical latent modes, processes the latent modes with Transformer blocks, and decodes the resulting representations at query directions. On SONICOM, using the LAP24 measurement configuration, SPARO attains the best log-spectral distortion (LSD) and interaural level difference (ILD) error at every sparsity level from 3 to 100 measurements (18% lower LSD and 43% lower ILD error than the strongest baseline at 100 measurements) while remaining competitive in interaural time difference (ITD) error. It reconstructs a dense HRTF 15 to 373 times faster than the leading neural-field method RANF. We further validate the approach on HUTUBS, demonstrating its effectiveness across HRTF datasets.
### Title:
          OrionMoE-v1.0: A Mixture-of-Experts Foundation Model for Tabular In-Context Learning
 - **Authors:** Mohamed Bouadi, Nassim Bouarour, Aditya Tanna, Vinay Kumar Sankarapu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tabular foundation models enable in-context learning by predicting unseen observations from a labeled support table without task-specific parameter updates. Despite recent advances, most existing approaches rely on dense architectures that apply the same transformations across features and datasets. We introduce OrionMoE-Small, a compact tabular foundation model that combines distribution-aware representations with dataset-conditioned sparse mixture-of-experts computation. Built on a dual-axis Transformer architecture, OrionMoE-Small selectively activates experts along the feature axis, with routing decisions informed by both individual feature representations and the broader dataset context. This design enables adaptive allocation of computation across heterogeneous tabular problems while retaining a shared computational pathway across tasks. OrionMoE-Small is pretrained entirely on synthetic classification tasks generated from a structured causal prior and performs downstream prediction without gradient-based adaptation. Experiments across multiple tabular benchmarks demonstrate competitive performance against substantially larger foundation models, with particularly strong results on small-context and high-dimensional datasets. Further analysis reveals favorable relative performance under class imbalance and highlights the importance of feature composition.
### Title:
          The COUNT: Counting N-grams Unlocks Scaling on Host Memory and Training-Free Adaptation
 - **Authors:** Ian Magnusson, Noah A. Smith, Pang Wei Koh
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The scaling relationship of compute and performance for language models (LMs) has been extensively studied; more recently, models are being designed to scale memory use, as well. In particular, adding embeddings for n-grams scales memory separately from compute use, because each pass only processes individual embedding rows, which are much smaller than the storage used for the whole embedding table. However, existing methods train embeddings from scratch, which needs expensive GPU memory for fast reading and writing. Meanwhile, the ordinary memory of the host system is cheap and underutilized by these training methods. To scale on host memory, we introduce COUNT (Counting Offline Unlocks N-gram Transformers), which builds n-gram embeddings without adding learned parameters by storing precomputed n-gram counts on host. We use the corpus frequencies to weight together the LM's own unembeddings of the next tokens most often following the current n-gram history. At a fixed compute budget, COUNT can be added as an additional input embedding for pretraining 1B-parameter LMs to improve validation loss as much as an LM with 57% more compute. If GPU memory is limited, using COUNT to let backbone parameters fill GPU memory gives better performance than splitting memory with additional learned n-gram embeddings. Beyond efficiency, COUNT allows switching in a different table of n-gram counts from a domain-specific corpus at inference time to adapt to a new task without any training.
### Title:
          Graph-Enhanced Disease Trajectory Discovery and Temporal Endpoint Forecasting from Longitudinal Electronic Health Records
 - **Authors:** Jin-Jia Zheng, Vincent S. Tseng
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Longitudinal electronic health records (EHRs) can reveal disease-progression structure, while useful forecasting requires leakage-controlled discovery, censor-aware outcomes, and inspectable trajectory evidence. We developed a graph-enhanced framework in MIMIC-IV v3.1 that splits patients before graph construction, learns train-only consecutive-admission transitions, and freezes endpoint-specific branching-motif policies selected on validation data. The final catalog contained 99,527 motifs, and a time-aware Transformer retrieved at most 24 patient-compatible motifs per endpoint through endpoint-specific cross-attention. Across five training seeds, micro-AUPRC increased from 0.9330 to 0.9357, while event-time MAE decreased from 676.9 to 657.7 days (reduction 19.2 days; 95% paired patient-cluster bootstrap CI, 13.8-24.8). Timing effects were heterogeneous: MAE worsened for events within 730 days but improved by 58.9 days for events occurring after 730 days. In an exploratory internal temporal split, branch conditioning reduced conditional event-time MAE by 26.9 days (95% CI, 23.0-30.8) without evidence of better micro-AUPRC. Corrected survival evaluation over the supported 0-2,555-day interval did not establish macro C-index or integrated Brier score superiority over a matched history-only discrete-hazard model. A directed, degree-matched GNN repair substantially improved unseen-edge discovery, yet replacing GNN-derived scores within fixed motif identities did not improve downstream forecasting. These results position branching motifs as structured trajectory context whose main value is long-range timing support rather than uniformly stronger endpoint discrimination, survival prediction, or causal explanation.
### Title:
          Revisiting Simple Baselines for Relational Deep Learning
 - **Authors:** Viet The Nguyen, Vijay Prakash Dwivedi, Gunther Gust
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Relational deep learning has emerged as a powerful paradigm for learning end-to-end predictive models over relational databases by representing them as temporal heterogeneous graphs. Recent advances based on graph neural networks and Transformers have achieved strong performance across diverse domains. However, the effectiveness of simpler relational baselines remains underexplored, making it difficult to assess how much architectural complexity is needed to achieve strong predictive performance. Motivated by the observation that predictive signals arise from target attributes, relational attributes, and historical labels, we revisit how effectively these signals can be exploited using simple propagation methods. We adapt fixed low-pass feature propagation to relational entity graphs and train an MLP for prediction. The resulting predictions are further refined using Correct-and-Smooth, a graph-based label propagation algorithm that incorporates historical labels over task-specific meta-graphs connecting target entities. Across classification and regression tasks on RelBench, an MLP trained on neighborhood-filtered features outperforms one using only target-entity features on most tasks and recovers a substantial portion of the performance of heterogeneous GNNs. Correct-and-Smooth provides further gains from historical labels, although applying it requires a separately constructed meta-graph because connections among target entities are not directly specified by the relational entity graph. Together, our studies revisit the effectiveness of established propagation methods as simple RDL baselines while identifying canonical meta-graph construction as a key challenge for effective label propagation.
### Title:
          Learnable Hodge-Laplacian Driven Mixture of Experts for Steady-PDE Surrogates on Coarse Unstructured Meshes
 - **Authors:** Stavros Nousias, Akis Nousias, Konstantinos Gkrispanis
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current approaches for steady partial differential equations surrogate models on unstructured meshes apply a single mixing mechanism to the whole solution. This paper proposes an architecture that partitions the solution among vanilla transformer experts, each focused on a different spectral scale. The partition is built from a discrete Hodge Laplacian $L_0=\star_0^{-1} d_0^{\top}\star_1 d_0$, that serves as a fitting layer measuring high-frequency content. A gating mechanism takes the mesh as input and produces the per-vertex weights that recombine the expert outputs. AirFRANS is a steady Reynolds-averaged Navier--Stokes (RANS) airfoil benchmark. We evaluate our approach in a reduced remeshed version of the benchmark with each unstructured mesh counting 9.6K faces and 4.9K vertices. We compare our approach with the Transolver on the same dataset and dataset slit. Our approach reduces relative $L_2$ error by 31\% and interior mean squared error by 47\%.
### Title:
          Continuum Attention
 - **Authors:** Afshin Khadangi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Continuum Attention (CA), a causal Transformer attention operator that replaces discrete key and value lookup with integration over a continuous, piecewise linear memory curve. Each query induces an exponential relevance density along the curve. Integrating the density and interpolated values yields exact normalized attention from closed form exponential moments, including half token boundary contributions. The gradients follow analytically from moments of order at most two, enabling parallel GPU implementations while retaining quadratic sequence complexity and the standard Transformer decoder. Compared with ordinary softmax and focal attention, CA reduces mean validation negative log likelihood by 0.0200 and 0.0480 nats per byte, respectively, winning all paired comparisons. An additional disjoint validation slice yields a 0.0457 nats per byte advantage over the strongest selected softmax baseline, with a paired 95% confidence interval. These findings motivate continuous integration as a promising attention alternative while leaving larger scale generalization open.
### Title:
          Your Transformer Is Secretly Elastic
 - **Authors:** Walter Simoncini, Dheeraj Varghese, Gertjan J. Burghouts, Cees G.M. Snoek
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scaling up transformers has produced models with broad capabilities, deployed across heterogeneous hardware and fluctuating workloads. Yet, model families offer only a few fixed sizes (e.g., S, B, L), forcing users to commit to a model based on hardware and latency constraints. This rigidity is often suboptimal under varying query loads. We introduce a retraining-free method that elastifies pre-trained transformers into a single model that adapts on-the-fly across a continuum of computational budgets. Our key contribution is a differentiable relaxation of the functional unit-ranking problem: unlike prior work, which optimizes a single importance weight per MLP block or attention head, we rank every individual MLP neuron and attention head jointly, on a common scale, by minimizing the model's loss under soft pruning across many sparsity targets, all at once. Across 27 vision and text transformer encoders ranging from 22M to 8B parameters, our method yields smooth degradation up to 60% sparsity and outperforms one-shot baselines under deep pruning. For example, pruning DINOv3 ViT-H+/16 to 50% sparsity removes 427M parameters while reducing ImageNet-1k linear-probing accuracy by only 0.8%, without the need for weight correction or retraining. At 60% sparsity, a pruned AugReg ViT-B/16 model achieves up to $1.80\times$ higher throughput and $1.26\times$ lower single-query latency on an A100 GPU. Elastic models are produced in minutes, with construction time scaling sub-linearly with parameter count.
### Title:
          Modeling and Understanding Neural Weights of Humanoid Policies with Diffusion
 - **Authors:** Huixuan Cheng, Bike Zhang, Shankar Sastry, Koushil Sreenath
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in robot learning have driven rapid progress in humanoid control, enabling increasingly agile behaviors in the real world. However, humanoid control networks are typically obtained through conventional training procedures, while comparatively little attention has been given to directly modeling the distribution of their learned weights and generating functional networks in weight space. In this work, we investigate whether high-performing humanoid control networks can be generatively modeled directly through their weights. We adopt a latent diffusion framework that couples a linear autoencoder with a Diffusion Transformer. The autoencoder compresses actor network parameters into a compact latent space, and the Diffusion Transformer models the distribution of these latents. Trained on networks collected from reinforcement learning for the Unitree G1 robot, our approach generates deployable networks that perform various motions in the real world, including walking, dancing, and spin kick. Beyond generation, we further study the learned weight space to better understand the structure captured by these humanoid control networks. We identify a structural principle in the first-layer weights that consistently reflects the robot's kinematic prior. Notably, this kinematic prior emerges under both Reinforcement Learning (RL) and Imitation Learning (IL) training, suggesting that it is not specific to a particular optimization process but may instead reflect common knowledge associated with humanoid embodiment. Together, these results demonstrate the feasibility of generative modeling in humanoid network weight space, while providing initial insights into the information encoded by their learned weights. Additional results are available on our project website: this https URL
### Title:
          Representation Conditioning for Generation
 - **Authors:** Saeed Razavi, Xingjian Leng, Liang Zheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Representation-alignment methods effectively accelerate the diffusion transformer training. REPA, for example, uses a pretrained vision encoder to supervise an intermediate layer through an MLP projection head which is discarded after training. It aims to import semantics from the vision encoder to the diffusion backbone. While this objective is achieved at early layers by back-propagating the alignment loss, there is no guarantee that later layers, supervised by the velocity prediction loss alone, can well access such semantics. We propose a simple solution, representation conditioning (RECON), to improve semantics in later layers. During training, we feed the pretrained vision encoder tokens into later layers; during inference, because we no longer have the clean image, we reuse the MLP head (as a proxy to the vision encoder) and project its output tokens to the later layers. Our method adds no parameters and leads to much faster convergence: RECON is $63\times$ faster than SiT and $25\times$ faster than REPA. Code is available at this https URL
### Title:
          Can Learning to Answer Spatial Questions Improve Novel-View Generation?
 - **Authors:** Jahyeok Koo, Hyeonseo Yu, Seungho Jang, Jaewoo Jung, Jiwon Kang, Seokju Cho, Seungryong Kim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generating novel views from limited observations requires preserving both the appearance and spatial structure of a scene. Although recent approaches exploit fine-grained geometric cues, they do not explicitly model high-level semantic and spatial properties such as object identity, attributes, and inter-object relationships. In this work, we investigate whether 3D language understanding can provide complementary supervision for novel-view generation. We introduce Ask4NV, built on a pretrained unified multimodal model with a Mixture-of-Transformers (MoT) architecture. Our model incorporates camera geometry into both VAE and ViT representations and leverages understanding features during generation through joint self-attention with a modality-aware attention masking strategy. Experiments demonstrate strong image quality and geometric consistency in novel-view generation, alongside competitive 3D language understanding. Further analysis shows that joint training improves cross-view correspondence in VAE representations and similarity in a 3D-aware feature space.
## Keyword: autonomous driving
### Title:
          Investigating Behavior Cloning from Few Demonstrations for Autonomous Driving based on Bird's-Eye View in Simulated Cities
 - **Authors:** Eric Aislan Antonelo, Gustavo Claudio Karl Couto, Christian Möller, Pedro Henrique Fernandes
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper investigates the use of Behavior Cloning (BC) for autonomous driving from a bird's-eye view (BEV) perspective in simulated urban environments. BC uses supervised learning to mimic expert driving behaviors. Previous works have applied BC in the CARLA simulator but did not fully address the challenges of traffic light compliance. Our approach enhances BC by integrating a kernel density estimator to adjust training sample weights based on action density, thereby improving the learning of rare but critical actions such as stopping at red lights and accelerating at green lights, specially in scenarios of scarce number of expert demonstrations. Using BEV inputs, which provide an abstract top-down view of the driving environment, our method simplifies the policy learning process. The trained convolutional neural network (CNN) outputs steering and acceleration actions based on these BEV inputs and additional state variables. Experimental results in the CARLA simulator demonstrate that our weighted BC method significantly improves driving performance, achieving higher route completion compared to standard BC. This weighted approach proved to be crucial in learning correct driving behaviors, particularly in test environments not encountered during training, highlighting its potential for enhancing autonomous vehicle navigation.
### Title:
          SafeDriveVLA: Navigation-Conditioned World Model Dreaming for Conflict-Aware End-to-End Autonomous Driving
 - **Authors:** Shaoyuan Xie, Zihan Zhang, Jingxuan Wang, Jiashu Qu, Xiaoqing Liang, Lingdong Kong, Junchi Lu, Henrik I. Christensen, Qi Alfred Chen
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models are gaining attention in autonomous driving, inheriting commonsense priors from large language models (LLMs) and widening the navigation interface from a fixed command set to free-form natural-language instructions. However, this open-ended interface exposes a new vulnerability surface: an inattentive driver may issue instructions that are unsafe given the current scene, and a malicious user may issue dangerous ones on purpose. We present the first benchmark suite that evaluates navigation following and conflict awareness together, along with adversarial robustness. Existing VLAs fall short on both: SimLingo completes no language-instructed lane change in closed loop, and all models degrade sharply under conflicting signals. We propose SafeDriveVLA, the first driving VLA that (1) explicitly predicts a three-level navigation-compliance mode to decouple conflict reasoning from action generation, and (2) uses navigation-conditioned world model dreaming to inform this prediction. Unlike prior world models that roll out expert or planned actions, ours dreams of strictly following the navigation signal, showing when following is safe. SafeDriveVLA reaches 88.16 Driving Score (DS) and 68.64% Success Rate (SR) on Bench2Drive, lifts closed-loop language following by 49.3% and reduces collisions under unsafe instructions from 60 to 38 compared to the best SimLingo variant. Video demonstrations are available on our project page.
