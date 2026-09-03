# Showing new listings for Thursday, 3 September 2026
## Keyword: SLAM
### Title:
          TAPVid-MV: A Benchmark for Tracking Any Point in 3D Across Multiple Views
 - **Authors:** Skanda Koppula, Frano Rajic, Abdullah Faiz Ur Rahman, Yi Yang, Ignacio Rocco, Jeet Thakwani, Rishabh Kabra, Andrew Zisserman, Joao Carreira, Siyu Tang, Carl Doersch, Gabriel Brostow
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-camera systems are increasingly practical for robotics, AR/VR, and autonomous driving because complementary views reduce depth ambiguity and preserve visibility under occlusion. Existing point-tracking benchmarks, however, focus on a single video or static multi-camera rigs. None test long-term 3D point tracking across several synchronized views under camera motion. We introduce TAPVid-MV (Tracking Any Point in Video across Multiple Views), the first benchmark for this setting. It contains a curated set of 284 sequences, 1,142 calibrated camera streams, and 109,769 point tracks across seven subsets spanning indoor and outdoor domains, from robotics and human activity to driving and synthetic procedural scenes. We obtain these trajectories using dataset-specific auxiliary modalities: sensor depth, LiDAR, SLAM and SfM points, human meshes, posed object meshes, and simulation. Every sequence and trajectory is visually verified by human annotators. Across more than 30 baselines, no method comes close to solving the task. Surprisingly, existing multi-view point trackers do not consistently outperform monocular point trackers. By evaluating reconstruction and point tracking on the same datasets, TAPVid-MV helps distinguish errors in recovered geometry from errors in point correspondence. Through this joint analysis, we identify geometry recovery as a major bottleneck for accurate 3D point tracking. Beyond multi-view 3D point tracking, our released annotations support monocular 2D and 3D point tracking, future-trajectory prediction, and 4D reconstruction.
### Title:
          AutoCompass: Accurate Visual Localization on Public Maps by Learning from Weak Labels
 - **Authors:** Javier Tirado-Garín, Alan Savio Paul, Shuai Chen, Axel Barroso-Laguna, Tommaso Cavallari, Daniyar Turmukhambetov, Victor Adrian Prisacariu, Eric Brachmann
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural map matchers estimate an image's 3-DoF pose relative to a 2D map. These models are trained on large-scale datasets of geo-referenced images, whose position and heading labels often contain noise that affects the trained models. To address this, we present AutoCompass, a supervision approach for training neural map matchers from inaccurate absolute pose labels. First, we show that heading labels are unnecessary: trained from raw GPS labels, models learn to predict accurate headings, automatically. Second, defining a tolerance region around raw GPS improves positional accuracy. Third, if available, our supervision uses relative poses between training images, obtained via SLAM or SfM, which provide a more accurate training signal. Across driving and egocentric benchmarks, AutoCompass consistently outperforms counterparts trained with the usual strong reliance on absolute pose labels.
## Keyword: odometry
### Title:
          FOCUS: Foot Observation Confidence for Robust Humanoid Proprioceptive Odometry
 - **Authors:** Kaixin Feng, Angsong Li, Shaopeng Zhang, Enyu Li, Peiwen Lin, Chuang Wang, You Li, Haiyu Lan
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Foot forward kinematics (FK) is widely used to improve proprioceptive legged odometry by providing reliable velocity constraints during foot support. Existing contact-aided estimators generally rely on binary contact decisions to determine whether the FK measurements of an entire foot should be trusted. However, contact does not necessarily imply FK reliability. Dynamic locomotion often involves partial support, toe dragging, and foot slip, causing binary contact decisions to accumulate significant drift over long trajectories. To address this limitation, we propose FOCUS (Foot Observation Confidence from Unannotated Simulation), which predicts a continuous FK reliability weight for each foot instead of estimating binary foot contact. Rather than replacing the model-based estimator, the predicted reliability weights are used to blend FK velocity observations with IMU-propagated body velocity and to adapt the observation covariance of an extended Kalman filter (EKF), enabling smooth reliability-aware fusion without hard contact switching. The network is trained from automatically generated simulation signals using an FK-weighted velocity consistency loss with lightweight simulator-contact regularization, without manually annotated continuous FK-reliability labels. The deployed model relies only on IMU and joint kinematic measurements, making it suitable for hardware platforms with unreliable torque sensing. Experiments demonstrate that FOCUS reduces absolute trajectory error (ATE) by 83.7% on simulated walking episodes, preserves simulated dynamic-motion fidelity in motion scale and spectral energy, reduces ATE by 70.8% across 19 real walking segments, and reduces mean ATE by 42.7% across four real dynamic-motion routines.
### Title:
          Contact-Constrained Lower-Limb Joint-Offset Calibration for Humanoid Robots
 - **Authors:** Kaixiang Lu, Haiyu Lan, Chunxiao Qiao, You Li, Chengyuan Luo, Enyu Li, Peiwen Lin, Chuang Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate joint encoder offsets are essential for kinematic consistency in humanoid lower limbs, yet existing calibration methods typically require external motion-capture systems or fiducial targets. We present a self-contained calibration framework exploiting only onboard joint encoders and a pelvis-mounted IMU during static double-support contact. The inter-foot transform from forward kinematics must stay constant when both feet are fixed; minimizing its posture-dependent dispersion yields a nonlinear least-squares problem over the 12-dimensional offset vector. A Hessian eigenstructure analysis shows that parallel pitch axes induce a rotational coupling. Orientation residuals then observe only the pitch-offset sum, while translation and posture diversity set the remaining numerical observability. For the A3 pitch-to-roll-to-yaw ordering, hip-roll and hip-yaw excitation reduce hip-pitch coupling. A standing-posture knee prior then anchors the remaining weak pitch-chain decomposition. Simulation and real-machine injection tests show consistent recovery, and on held-out recordings calibration reduces foot-height RMS residuals from 4.26 to 2.20 mm on A3 and from 8.03 to 1.43 mm on A2. An independent LiDAR-inertial reference checks the pitch-coupled channel. Removing an injected pitch offset moves the leg-odometry vertical drift back toward the LiDAR trajectory. A few static double-support stances thus provide contact-consistent corrections for well-excited directions. Individual offsets in the weak pitch chain remain prior-dependent.
### Title:
          Do Better Imagined Rollouts Mean Better Robot Control? A Controlled Study of World-Model Evaluation Under Feedback
 - **Authors:** Dharini Raghavan, Amritpal Singh
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Predictive models are increasingly used in robotics for state estimation, planning, control, and policy evaluation, yet they are often judged by open-loop prediction accuracy over a fixed horizon. In closed-loop operation, a robot repeatedly acts, receives new measurements, updates its state estimate, and recomputes control. We study this difference in a differential-drive path-tracking task with biased odometry and intermittent landmark sensing. Six state estimators are evaluated across 24 sensing conditions using trajectory replay, a 20-step measurement-free rollout, and closed-loop tracking. Replay position RMSE correlates more strongly with closed-loop cross-track RMSE than rollout error (Spearman rho = 0.923 vs. 0.774) and selects a different estimator from the closed-loop optimum in 5/24 conditions, compared with 18/24 for the rollout metric. We then vary rollout horizon and measurement-update interval. With H=20, rank agreement decreases from rho = 0.916 with measurements at every step to rho = 0.774 with no measurements. A horizon-update grid shows that long prediction horizons remain informative when regular corrections are retained, whereas long rollouts without correction can produce rankings that differ substantially from closed-loop behavior. We also test recurrent estimators trained on longer sensing outages. This improves the EKF-anchored models under combined sensing degradation, reducing GRU-EKF cross-track RMSE from 1.72 m to 1.06 m, but the gain is not consistent across isolated outages or estimator architectures. These results show that predictive-model evaluation in robotics should specify both prediction horizon and measurement-update schedule. For models used in feedback, offline rollouts are most informative when their sensing and correction pattern reflects closed-loop operation. Code is available at this https URL
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          TAPVid-MV: A Benchmark for Tracking Any Point in 3D Across Multiple Views
 - **Authors:** Skanda Koppula, Frano Rajic, Abdullah Faiz Ur Rahman, Yi Yang, Ignacio Rocco, Jeet Thakwani, Rishabh Kabra, Andrew Zisserman, Joao Carreira, Siyu Tang, Carl Doersch, Gabriel Brostow
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-camera systems are increasingly practical for robotics, AR/VR, and autonomous driving because complementary views reduce depth ambiguity and preserve visibility under occlusion. Existing point-tracking benchmarks, however, focus on a single video or static multi-camera rigs. None test long-term 3D point tracking across several synchronized views under camera motion. We introduce TAPVid-MV (Tracking Any Point in Video across Multiple Views), the first benchmark for this setting. It contains a curated set of 284 sequences, 1,142 calibrated camera streams, and 109,769 point tracks across seven subsets spanning indoor and outdoor domains, from robotics and human activity to driving and synthetic procedural scenes. We obtain these trajectories using dataset-specific auxiliary modalities: sensor depth, LiDAR, SLAM and SfM points, human meshes, posed object meshes, and simulation. Every sequence and trajectory is visually verified by human annotators. Across more than 30 baselines, no method comes close to solving the task. Surprisingly, existing multi-view point trackers do not consistently outperform monocular point trackers. By evaluating reconstruction and point tracking on the same datasets, TAPVid-MV helps distinguish errors in recovered geometry from errors in point correspondence. Through this joint analysis, we identify geometry recovery as a major bottleneck for accurate 3D point tracking. Beyond multi-view 3D point tracking, our released annotations support monocular 2D and 3D point tracking, future-trajectory prediction, and 4D reconstruction.
### Title:
          KSG-Net: Key-Sparse and Global-Context Learning for Maritime 3D Ship Detection
 - **Authors:** Zhouyuan Huai, Meiqi Wan, Yan Yang, Minshi Chen, Xin Yuan, Wei Wang, Xiao Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate 3D ship detection in maritime environments is critical for autonomous navigation, yet remains challenging due to large-scale vessel variations, sparse point clouds of small vessels, and severe sea-clutter interference. Existing methods, primarily based on 2D features or dense representations, struggle to balance detection accuracy and computational efficiency, while sparse 3D detectors designed for road scenes generalize poorly to maritime scenarios. This paper focuses on two key challenges in maritime LiDAR perception: weak feature representation for small and sparse vessels, and insufficient global structural modeling for large vessels due to the limited receptive field of local sparse convolutions. To address these issues, we propose KSG-Net, a Key-Sparse and Global-Context learning network for maritime 3D ship detection. The core idea is to jointly enhance local discriminative features and global structural awareness within a unified fully sparse detection framework. Specifically, a Key Sparse Multi-scale Aggregation (KSMA) module is designed to enhance the representation of small and sparse vessels by selecting informative key voxels and aggregating cross-scale neighborhood features. Furthermore, a Global Context Aggregation (GCA) module is introduced to capture long-range geometric dependencies through scene-level context modeling with gated residual interactions, thereby improving the representation of large vessels. Extensive experiments on the Thames River vessel dataset and simulated datasets demonstrate that KSG-Net consistently outperforms existing methods in multi-scale vessel detection and exhibits strong robustness in complex maritime environments.
### Title:
          Contact-Constrained Lower-Limb Joint-Offset Calibration for Humanoid Robots
 - **Authors:** Kaixiang Lu, Haiyu Lan, Chunxiao Qiao, You Li, Chengyuan Luo, Enyu Li, Peiwen Lin, Chuang Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate joint encoder offsets are essential for kinematic consistency in humanoid lower limbs, yet existing calibration methods typically require external motion-capture systems or fiducial targets. We present a self-contained calibration framework exploiting only onboard joint encoders and a pelvis-mounted IMU during static double-support contact. The inter-foot transform from forward kinematics must stay constant when both feet are fixed; minimizing its posture-dependent dispersion yields a nonlinear least-squares problem over the 12-dimensional offset vector. A Hessian eigenstructure analysis shows that parallel pitch axes induce a rotational coupling. Orientation residuals then observe only the pitch-offset sum, while translation and posture diversity set the remaining numerical observability. For the A3 pitch-to-roll-to-yaw ordering, hip-roll and hip-yaw excitation reduce hip-pitch coupling. A standing-posture knee prior then anchors the remaining weak pitch-chain decomposition. Simulation and real-machine injection tests show consistent recovery, and on held-out recordings calibration reduces foot-height RMS residuals from 4.26 to 2.20 mm on A3 and from 8.03 to 1.43 mm on A2. An independent LiDAR-inertial reference checks the pitch-coupled channel. Removing an injected pitch offset moves the leg-odometry vertical drift back toward the LiDAR trajectory. A few static double-support stances thus provide contact-consistent corrections for well-excited directions. Individual offsets in the weak pitch chain remain prior-dependent.
### Title:
          Zonotope-Based Active Exposure of Stealthy Deception Attacks in Sensor-Fusion Systems
 - **Authors:** Meiqi Tian, Shuo Li, Bingzhuo Zhong
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper investigates the stealthy attack detection for sensor-fusion cyber-physical systems with unknown-but-bounded noises through the control channel. The detection framework is particularly applicable to sensor-fusion scenarios in which multiple suspicious sensors contributing to the fused estimate may be compromised simultaneously. First, we construct an admissible output set using secure sensors and an attack output set for each attack hypothesis. Then, we introduce a receding-horizon optimization framework to design exposure inputs, namely bounded auxiliary control perturbations injected through the control channel, so as to enlarge the separation between the admissible output set and the attack output sets according to the separation tendency. A sufficient detection condition is further derived, showing that set separation guarantees detectability of the compromised sensors. Moreover, an offline exposure budget guidance is developed to support budget selection before online exposure starts. Simulations on a UAV navigation system under stealthy GNSS and LiDAR attacks validate the proposed method.
### Title:
          Toward Robust LiDAR Semantic Segmentation for Real-World Deployment: Evaluation under Coarse Labels, Adverse Conditions, and Domain Shifts
 - **Authors:** Samir Abou Haidar, Alexandre Chariot, Mehdi Darouich, Cyril Joly, Jean-Emmanuel Deschaud
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR-based semantic segmentation is a core perception module for autonomous vehicles and mobile robots. Despite the strong performance of recent state-of-the-art methods on standard benchmarks, existing evaluation protocols remain focused on clean, single-domain settings and fine-grained label taxonomies, leaving deployment readiness largely unassessed. Real-world systems must handle safety-critical label semantics, degraded sensing conditions, and cross-domain variability, yet no unified protocol currently addresses all three aspects together. In this paper, we propose a structured evaluation protocol that assesses the deployment readiness of LiDAR semantic segmentation models along three complementary dimensions: (i) coarse-label evaluation aligned with autonomous driving safety priorities, revealing how label granularity affects different methods; (ii) robustness under eight types of LiDAR corruptions designed to emulate real-world atmospheric, geometric, and sensor degradations; and (iii) domain generalization across datasets without adaptation. The evaluation includes inference speed measured on an embedded Jetson AGX Orin platform, directly reflecting deployment constraints. Our results show that fine-grained benchmark rankings do not always reflect safety-relevant performance, that all methods experience substantial degradation under corruptions with architecture-dependent robustness characteristics, and that current domain generalization remains insufficient for reliable deployment. These findings expose concrete gaps between benchmark performance and deployment readiness, and provide a reference protocol for more practically grounded evaluation of LiDAR semantic segmentation.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          Automated Maize Ear Phenotyping Using 3D Reconstructions
 - **Authors:** Ritwesh A. Kumar, Som Tripathi, Peja Matthews, Srikar Reddy, Talukder Zaki Jubery, Patrick Schnable, Adarsh Krishnamurthy, Baskar Ganapathysubramanian
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Maize kernel traits such as row number, kernels per row, and kernel size vary largely for genetic reasons and are consistently associated with regions of the genome that influence yield. Manual measurement of these traits, however, cannot keep pace with the volume of maize generated in a breeding program. To address this, we developed and validated a fully automated pipeline for extracting these traits from 3D point clouds of corn ears, built on a recently developed video-to-point-cloud platform. Raw video frames are processed through COLMAP and NeRF, the ear is isolated via density-based separation, and the point cloud is distance-calibrated to physical units. The calibrated ear point cloud was Z-axis aligned via PCA and cylindrically unwrapped to a 2D image. We enhanced contrast and performed zero-fine-tuning instance segmentation using Cellpose-SAM. A triple-juxtaposed unwrap strategy was used to prevent double-counting at the seam. The pipeline achieved kernel count R^2 = 0.921 (MAPE = 10.33%) and kernel row number within +-2 rows for 95.2% of ears (MAE = 0.75 rows) on a 168-ear held-out set from the 268-ear labeled dataset. The resulting multi-trait dataset has known genotype identity for each ear, positioning it for phenotype-to-genotype association analyses.
### Title:
          Query Rewriting for Complex Object Segmentation in 4D Gaussian Representations
 - **Authors:** Thanh-Khoi Nguyen, Thien-Phuc Tran, Minh-Triet Tran
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent 4D Gaussian representation frameworks have demonstrated strong performance in language-guided dynamic scene understanding. However, these methods remain highly sensitive to verbose and narrative-style queries that contain noisy contextual information. In this paper, we investigate the impact of query rewriting for complex object segmentation in 4D Gaussian representations. Inspired by recent findings in retrieval-augmented language models and keyword-guided query reformulation, we propose a training-free reinterpretation strategy that transforms long descriptive queries into concise keyword-grounded forms. Our approach progressively reduces linguistic noise while preserving semantic anchors relevant to object-centric representations. Experiments on HyperNeRF and Neu3D demonstrate that concise rewritten queries significantly improve both temporal localization and spatial segmentation performance. In particular, our method improves average temporal accuracy from 60.92% to 92.21% and average vIoU from 20.08% to 76.94% without any additional fine-tuning. Extensive ablation studies further reveal that shorter, keyword-focused queries consistently yield stable video-feature similarity distributions and better alignment with object-centric Gaussian representations
## Keyword: mapping
### Title:
          Linear Fusion MultiDiffusion for Fast Training-Free Spherical Panorama Generation
 - **Authors:** Akio Hayakawa, Yusuke Mukuta, Tatsuya Harada
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose LF-MultiDiffusion, a training-free panorama generation method that extends MultiDiffusion to support linear projections between target and reference image spaces. Our key idea is to reformulate latent aggregation as a regularized least-squares problem and solve it efficiently with a Krylov-based iterative solver inside the denoising loop. This formulation enables denser and more natural mappings than prior training-free methods, yielding more stable generation with far fewer perspective views. As a result, LF-MultiDiffusion reduces the number of image generator evaluations during denoising and significantly improves inference efficiency. Experiments show that LF-MultiDiffusion achieves better visual quality, text alignment, and panoramic consistency than the strongest training-free baseline, while providing a 15.36$\times$ speedup. Our project page is available at: this https URL.
### Title:
          Beyond Context Windows: Persistent Discovery Context for Data-Centric Agents
 - **Authors:** Jalal Mahmud
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Data-centric agents repeatedly perform a discovery step before planning or execution: identifying the data objects relevant to a task. Yet successful discovery outcomes are typically discarded rather than reused. We introduce persistent discovery context, a lightweight memory layer that stores prior intent-to-object mappings and reuses them to augment future retrieval. Across three structured data environments, persistent discovery context consistently improves retrieval quality over metadata-only search, remains effective with automatically generated memories, and exposes a reproducible interference failure mode. In lexically sparse domains, memory-only retrieval can even outperform metadata-based retrieval. These findings suggest that discovery outcomes constitute a useful form of reusable context for data-centric agents.
### Title:
          Unified Motion Retargeting for Humanoids with Learned Point Cloud Correspondence
 - **Authors:** Hanyang Cao, Yuetong Fang, Taesoo Kwon, Runyi Yu, Ji Ma, Jing Tan, Yangchen Zhou, Baoze Du, Yi Gu, Yukang Gao, Ruoli Dai, Lei Han, Renjing Xu
 - **Subjects:** Subjects:
Robotics (cs.RO); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Humanoid learning increasingly relies on transforming vast and diverse human motion data into high-quality robot reference trajectories. However, retargeting human motion to humanoid robots is challenging due to substantial differences in morphology, degrees of freedom, joint ranges, and kinematic constraints between humans and robots. Existing retargeting methods typically address these differences by defining human-robot correspondence through hand-crafted sparse keypoints or body-part pairs. As a result, retargeting quality depends heavily on manual semantic design, limiting scalability across motion sources and robot morphologies and providing only sparse guidance for reproducing detailed poses and interactions. In this paper, we present Unified Motion Retargeting (UMR), a framework that learns dense point cloud correspondence without requiring manually designed human-robot mappings. By treating exterior point clouds as a unified interface between human motion and humanoid robots, UMR decouples retargeting from source-specific skeletal semantics and robot-specific topology. The learned dense correspondence provides fine-grained geometric anchors for constrained point cloud matching optimization, enabling surface-level pose alignment and direct transfer of interaction contacts. Experiments demonstrate that UMR unifies retargeting across heterogeneous motion sources, robot embodiments, and downstream scenarios ranging from locomotion to interaction, while achieving higher motion fidelity and plausibility than state-of-the-art methods. UMR therefore provides a scalable foundation for transforming large-scale human motion references into robot-ready training data.
### Title:
          A physics-enhanced bidirectional multi-order graph fusion network for interpretable bearing remaining useful life prediction
 - **Authors:** Haoxuan Zhang, Dinghao Yang, Kangning Zhang, Shaoyong Guo, Haisheng Li, Rui Yang, Ruijun Liu
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate prediction of bearing remaining useful life (RUL) is a key challenge for intelligent maintenance. Although deep learning-based prediction methods have showed effectiveness, existing methods still have limitations in learning nonlinear bearing degradation processes and model interpretability. Especially in engineering applications, the "black box" nature of deep learning models can easily raise concerns about their reliability. Therefore, we propose a physics-enhanced bidirectional multi-order graph fusion network for interpretable bearing RUL prediction. Our network mines complementary information from both forward and backward degradation sequences. Specifically, our network introduces a multi-order graph propagator to capture the local-global degradation dependencies. A gated cross-fusion mechanism is further designed to dynamically balance the feature contributions from both forward and backward directions. Then, our network stores representative historical degradation prototypes in dynamic memory, so that the final RUL prediction no longer depends solely on the current latent features, but is guided by reusable historical degradation knowledge. To reveal how our model learns the nonlinear degradation process, the feature mapping parts utilize the Kolmogorov-Arnold network, which allows the nonlinear mapping to be visualized using learnable functions. Finally, a physics-enhanced dynamic loss function is developed to help our network learn effective and reliable degradation representations. Extensive experiments on two public datasets show that our method achieves the lowest error while providing more conservative estimates than existing methods. Our code is available at this https URL.
### Title:
          Learning the Constitutive Behavior of Materials via Neural Operators and Causal Attention: Case Studies in Plasticity and Damage
 - **Authors:** Rishabh Arora, Lisa Scheunemann, Tim Brepols, Shahed Rezaei
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Classical constitutive modeling of path-dependent inelastic materials relies on internal state variables whose evolution equations must be postulated based on domain knowledge and calibrated against experimental data. However, in many practical settings, the relevant internal variables are typically not measurable in experiments, and the constitutive response must be inferred entirely from measured strain-stress data without any prior knowledge of the material's internal state. We propose a data-driven constitutive modeling framework based on the concept of a material operator, which treats a deforming material as a functional mapping from its entire strain history to the corresponding stress response. In contrast to traditional autoregressive or recurrent formulations, the model is trained directly on full loading paths as function-to-function mappings, predicting complete stress trajectories in a single parallel forward pass. Temporal path dependence is enforced through a causally masked attention mechanism embedded within the operator, which restricts the model's attention to past material states while preserving computational parallelizability. Spectral convolutions provide discretization-invariant representations in the frequency domain, while causal attention captures highly adaptive, non-local history dependence. Furthermore, sinusoidal activation functions are used to resolve the strong nonlinear transitions inherent in inelastic regimes. The framework is evaluated across multidimensional, rate-independent material models exhibiting complex phenomena, with an emphasis on nonlinear plasticity and ductile damage accumulation. The results demonstrate accurate and robust predictions of irreversible deformation mechanisms while simultaneously achieving resolution invariance and excellent parallel efficiency.
### Title:
          SonicCaps: Large-Scale Diverse and Fine-Grained Captioning for Improved Audio-Retrieval
 - **Authors:** Zineb Lahrichi, Marc Ferras, Gaël Richard, Geoffroy Peeters
 - **Subjects:** Subjects:
Sound (cs.SD); Computation and Language (cs.CL); Multimedia (cs.MM); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in audio-language modeling have been driven by large-scale audio captioning datasets. However, existing datasets remain limited by low semantic diversity, generic descriptions lacking acoustic details, and one-to-one audio-caption mappings that poorly reflect the inherent ambiguity of auditory perception. We introduce SonicCaps, a large-scale audio captioning dataset comprising ~15M captions paired with ~700k audio clips, generated using a multi-modal large language model (Qwen3-Omni) conditioned on both audio and text. To explicitly promote diversity, we generate around 24 captions per audio via structured prompt engineering and few- shot generation, spanning main descriptions, rephrased variants (verbosity, style) and semantic tags. Human evaluation shows that SonicCaps is rated significantly higher than existing captioning datasets, with fine-grained analyses indicating that our captions are perceived as more descriptive and precise, which strongly correlates with quality judgments. Finally, training CLAP models on SonicCaps with a multi-caption sampling strategy consistently improves audio retrieval and zero-shot classification, with stronger generalization across public and commercial benchmarks. We release both SonicCaps and two specialized CLAP models on hugging face: this https URL.
### Title:
          ProSR: Semantic-Prototype-Guided Discrete Modeling for Physically Consistent SAR Super-Resolution
 - **Authors:** Byoungwoo Kim, Munchurl Kim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-resolution Synthetic Aperture Radar (SAR) imagery is critical for precision analysis such as automatic target recognition, yet its acquisition is costly. Although generative image super-resolution (ISR) models offer a promising alternative, current smooth-approximation based diffusion frameworks often struggle to preserve the coherent scattering statistics, causing stochastic structural distortions that are less consistent with real SAR physics. To address this, we propose Semantic Prototype-Guided Super-Resolution (ProSR), reformulating SAR ISR as a semantically-guided discrete token prediction task within a quantized latent space. By mapping signal features to discrete scattering primitives, ProSR preserves the impulsive nature of SAR without over-smoothing. Furthermore, we integrate a Self-Supervised Learning backbone into SAR ISR to extract label-free semantic priors, overcoming label scarcity. Guided by these priors, we introduce Semantic-Aligned Detail Encoding to decouple high-frequency signals into discrete scattering primitives. In parallel, the Semantic Prototype Map Generator explicitly constructs semantic prototype maps, allowing Prototype-Map-Guided Attention to route the information flows within identical categories and mitigate inter-class interference. To validate our approach, we present a large-scale 0.25m resolution benchmark from the Umbra Open Dataset. Experimental results show ProSR achieves superior visual quality while preserving essential scattering characteristics required for practical SAR applications.
### Title:
          MS-MEM: Multi-Skill Manipulation-Enhanced Mapping via Uncertainty- and Disturbance-Aware Action Selection
 - **Authors:** Yitian Shi, Jesper Mücke, Nils Dengler, Sicong Pan, Rania Rayyes, Maren Bennewitz
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate scene understanding in confined, cluttered spaces such as shelves is essential for service robots, as many everyday tasks require them to locate and retrieve objects reliably. Yet, it remains challenging due to severe occlusions, restricted accessibility, and the need to avoid excessive scene changes. In this paper, we propose Multi-Skill Manipulation-Enhanced Mapping (MS-MEM), an evidential framework for uncertainty-aware mapping that integrates active viewpoint selection, object pushing, and grasping. MS-MEM combines scene-level metric-semantic evidential belief estimators with an uncertainty-aware grasp representation. This representation is learned using a novel full-evidential grasp estimator that models both grasp affordance and orientation uncertainty. In our framework, candidate perception and manipulation actions are evaluated within a unified action selection pipeline using a common information gain criterion. For manipulation actions, we further introduce a collateral disturbance constraint (CDC) that discourages excessive changes to confident regions of the scene belief. This enables MS-MEM to select actions that effectively reduce map uncertainty while limiting collateral scene changes. Experimental results show that, compared with single-skill and unconstrained baselines that ignore scene disturbance, MS-MEM achieves higher mapping accuracy while substantially reducing scene disturbance, highlighting the synergistic effects of active viewpoint selection, push, and grasp actions.
### Title:
          Blending Concepts: Benchmarking Visual Metaphor Generation in Text-to-Image Models
 - **Authors:** Chuer Chen, Zichen Wang, Yi He, Zhengxi Yu, Nan Cao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-to-image (T2I) models have achieved remarkable success at faithfully rendering specified objects and attributes, yet their ability to produce visual metaphors, images that convey abstract ideas by combining elements from two distinct domains, remains largely unexamined. To bridge this gap, we introduce VMetaphor-Bench, the first benchmark for evaluating visual metaphor generation in T2I models. It comprises 1,500 visual metaphors curated from real-world creative imagery, organized into three levels and ten categories, with each sample paired with two prompts of differing specificity. For evaluation, we develop a hybrid framework within an MLLM-as-judge paradigm, combining a multiple-choice question (MCQ) based protocol of 9,594 questions across four levels of metaphorical fidelity with a dimension-based scoring protocol along three perceptual dimensions. Extensive evaluation of 11 representative T2I models reveals that even the strongest proprietary models struggle with compositional structuring and cross-domain mapping, key aspects of metaphorical expression, highlighting visual metaphor generation as an important frontier for future T2I research.
### Title:
          RGB-to-IR image translation for infrared vehicle detection in unseen UAV domains
 - **Authors:** Thijs A. Eker, Ella P. Fokkinga, Jan Erik van Woerden, Elfi I.S. Hofmeijer, Sebastiaan P. Snel, Klamer Schutte, Friso G. Heslinga
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Synthetic training data is crucial for developing vision AI when real-world data is scarce, as in thermal infrared (IR) aerial vehicle detection. While abundant UAV RGB imagery motivates RGB-to-IR translation for data augmentation, unobservable thermal traits (e.g., engine heat) make learning transferable mappings challenging. This work investigates whether modern generative translators can overcome this cross-modal gap to improve infrared vehicle detection on unseen UAV target domains. Translators are trained on paired RGB-IR source datasets and applied to RGB training images from held-out target datasets to generate synthetic IR data. Evaluated methods include supervised GANs, ControlNet-based diffusion models, and foundation-model editing via LoRA. The resulting synthetic IR imagery is used to train RF-DETR vehicle detectors, which are evaluated on unseen IR target test splits across five aerial datasets, with Kust4K and VTUAV serving as target domains. Synthetic IR consistently outperforms RGB and grayscale baselines. Stable Diffusion 3.5 with ControlNet yields the best results, improving mAP from 50.8 to 60.1 on Kust4K and from 25.6 to 38.4 on VTUAV compared to models trained only on source-domain IR data. Increasing output diversity via multiple seeds (+1.1 mAP) and prompt variations (+3.3 mAP) provides additional gains on VTUAV. Although a performance gap to real target IR data remains, generative RGB-to-IR translation effectively mitigates IR data scarcity and improves cross-domain aerial vehicle detection.
### Title:
          LoRA-TSD: Tangent-Space Spectral Descent for LoRA via Muon-Style Updates
 - **Authors:** Dmitrii Andriianov, Andrey Veprikov, Aleksandr Beznosikov
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Low-rank adaptation (LoRA) is the standard way to fine-tune large models, yet when its two factors are trained independently, the update ignores the geometry of the low-rank weight change it induces. We introduce LoRA-TSD, an optimizer that treats every LoRA step as a tangent vector of the fixed-rank matrix manifold and takes the spectral-norm steepest-descent step of Muon inside that tangent space, mapping the result back to the factors through a retraction native to the LoRA parametrization. The step avoids expensive operations on full weight matrices, and its retraction is up to $2.8\times$ cheaper than the truncated-SVD retraction used by prior manifold methods. We prove that the Frobenius-norm version of our surrogate recovers LoRA-Pro, and we identify the tangent-projected gradient, the Riemannian gradient of the manifold, as the stationarity measure natural to LoRA training and computable from the factor gradients alone. Under this measure we give the first global convergence guarantees for both LoRA-Pro and LoRA-TSD, with rates that drive the factor-gradient norms to zero. Across six commonsense and natural-language-inference benchmarks with Llama-3.2-1B, Llama-3.1-8B and Qwen3-32B, LoRA-TSD outperforms every competing LoRA optimizer and stays robust to the adapter rank. Code is available at this https URL.
### Title:
          DiscoSign: Discourse-Aware Text to Sign Language Gloss Translation
 - **Authors:** Vasileios Baltatzis, Mert Inan, Connor Gillis, Raja Kushalnagar, Lorna Quandt, Leah Findlater, Colin Lea
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sign language processing systems have traditionally operated at the sentence level, ignoring critical discourse phenomena fundamental to sign language comprehension. We introduce DiscoSign, a computational approach for discourse-aware text to sign language gloss translation grounded in linguistic research. We address three key phenomena within our modular Large Language Model (LLM)-based translation framework: (i) spatial coreference resolution, where entities maintain consistent spatial locations throughout discourse; (ii) Question-Answer Clauses (QACs), pseudocleft structures serving specific discourse functions; and (iii) concept-gloss consistency, ensuring stable mappings between English concepts and American Sign Language (ASL) signs. Traditional translation metrics fail to capture discourse-level quality, so we introduce a suite of novel evaluation metrics designed to assess each dimension of discourse coherence addressed by our framework. Experiments on sentence-level and discourse-level datasets show that our approach for discourse-aware processing significantly improves spatial consistency and entity tracking relative to sentence-only translation, while maintaining competitive single-sentence gloss translation quality. Our work establishes the first systematic framework for discourse-level text to sign language gloss translation with corresponding evaluation methodology.
## Keyword: localization
### Title:
          Omega-N: Interpretable Structural Node Descriptors and Their Applicability Domain
 - **Authors:** Alberto Acedo
 - **Subjects:** Subjects:
Social and Information Networks (cs.SI); Machine Learning (cs.LG); Physics and Society (physics.soc-ph); Molecular Networks (q-bio.MN)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A composite structural index summarises a network in one number; for a triangle-based index it is spectrally redundant: Tr(A^3) is the third moment of the adjacency spectrum. The non-redundant content sits one level down, in diag(A^3), which depends on eigenvectors and is not spectrally determined. A corollary in the theory paper for this index family stated that, and predicted: the global scalar should tie sharpened spectral baselines rather than beat them, while the node-wise attribution should do better where the number of structural epicentres is unknown. This paper tests it. We construct Omega-N by localizing each of the four factors. The direct localization is badly conditioned; two corrections from published practice fix it, a configuration-null excess for every local factor and a personalized-PageRank neighbourhood at several scales, giving ten interpretable features per node from the graph alone, with no attributes, training or embeddings. Against a recursive feature engine at five levels of recursion, Omega-N wins on one and ties on four of six in-domain node-classification evaluations, with ten features against up to 252. Two statistics computed from the graph and labels, not from performance, partition the eight benchmarks without error, and the two they exclude are the two it loses. The strongest application is drug-target prioritisation on protein interaction networks: +0.073 to +0.144 AUPRC over a centrality battery across four constructions, replicated on an independent AP-MS network and label source, surviving three bias controls (degree-matched, ten repetitions: +0.1047 and +0.1030, both 10/10, p=0.00195). The clearest negative sits in the same application: adding Omega-N to centralities plus Node2Vec changes nothing (+0.0014, p=0.31). The claim is narrow: ten interpretable features
### Title:
          Learning Evidence Sufficiency Boundaries for Selective Answering in Grounded Multi-Hop QA
 - **Authors:** Haruto Sato, Yuki Tanaka, Ren Nakamura, Aoi Kobayashi, Mei Ito
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Grounded question answering systems should answer only when the supplied evidence supports the answer. In multi-hop QA, this requirement is difficult because partial evidence can make an unsupported answer appear plausible. We study selective answering through evidence sufficiency boundaries: for the same question, a model should abstain under unsupported or partially supported context, answer when the context first becomes sufficient, and keep the answer stable when redundant evidence is added. We introduce Evidence Sufficiency Boundary Training, a generation-native training framework that constructs ordered evidence chains and supervises the abstain-to-answer transition directly. The method combines level supervision, a boundary flip margin, post-boundary stability, and answer recall protection. We build evidence chains from HotpotQA, 2WikiMultiHopQA, and MuSiQue, then evaluate models with chain metrics, raw QA utility, and unsupported-answer rates on external non-answerable sets. With Qwen2.5-3B-Instruct and LoRA adaptation, Evidence Sufficiency Boundary Training gives the strongest boundary localization among the tested systems, with flip accuracy of 0.807 compared with 0.781 for a token-level abstention baseline. It also achieves the lowest overall unsupported-answer rate on external non-answerable evaluation, 0.095 compared with 0.101 for the same baseline, while retaining competitive raw QA F1. The results show that grounded selective answering improves when training marks the evidence level where refusal should give way to answering.
### Title:
          From Visual Cues to Spoken Narration: Rethinking Audio Description
 - **Authors:** Akshita Gupta, Aditya Arora, Federico Tombari, Marcus Rohrbach, Anna Rohrbach
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Audio Description (AD) provides spoken narration of visual events during dialogue gaps, making movies accessible to visually impaired audiences. The problem requires determining both what (which visual event) and when (position for inserting the AD) to narrate, to achieve the best user experience. Prior work has largely reduced the problem to video captioning of pre-segmented video clips, i.e., what is largely predefined and when is ignored entirely. We propose Cue2Narrate, a two-stage pipeline that jointly predicts what and when to narrate in longer untrimmed movie clips. A dual-head audio-visual localizer predicts two temporally distinct windows per AD utterance: a visual cue window and a spoken narration window. A LoRA-adapted VLM then generates concise ADs from the predicted visual evidence, trained with a Description Ranking Loss that ranks captions (negative samples) of the same frames lower than the GT AD. To benchmark this new problem statement, we introduce the LongLSMDC benchmark with up to 8-min movie clips (~6.5min on average). On LongLSMDC, Cue2Narrate outperforms video-only and audio-only localization baselines by 5--12 points in avg. mAP. Under both predicted- and GT-window evaluation, Cue2Narrate improves AD generation over the corresponding fine-tuned base VLM. These results establish the first benchmark for multi-segment AD generation on long-form clips. Data & Code: this https URL
### Title:
          From Silicon to Boot Code: Extending Automated Program Repair to Firmware-Layer Security Workarounds
 - **Authors:** Maisha Mastora, Dean Sullivan
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated program repair (APR) research has been constrained to design time. Current techniques localize and fix bugs in RTL or HLS designs before a chip reaches production. Once a hardware vulnerability surfaces post-silicon, the patch must be manually generated: existing automation addresses patch deployment but not patch synthesis. We study the feasibility of extending a dictionary-guided, localize-synthesize-validate APR methodology originally developed for RTL repair to this firmware layer. An automated commit-clustering miner surfaces recurring fix templates across the EDK II (UEFI) firmware repository's full commit history without depending on known CVE identifiers, recovering all three known CVE-fix campaigns and surfacing two additional candidate bug families. Grounded in real fix evidence, we build four independent localizers: missing speculation barriers in C (CVE-2017-5753, Spectre v1), missing bounds checks before array writes in C (a decompression library CVE), missing Return Stack Buffer stuffing in x86 assembly (CVE-2017-5715), and missing integer-overflow guards in Hand-Off Block creation code (surfaced by the miner itself). All four achieve 100% recall; precision ranges from 2.1-15.5% on the C families to 100% on the assembly and HOB families. Root-cause analysis of the C-family false positives attributes 77-90% to two intra-procedural causes, isolating the inter-procedural alias-analysis gap as a measured 15-20% rather than an estimate. A held-out test confirms Spectre v1 localization holds at 100% recall on unseen files; a fifth, independently built dictionary entry (CVE-2018-3630) shows the methodology extends to a new bug signature at low cost; and a naive syntactic baseline recalls at most 14% where our detector recalls 100%. We frame these results within a broader research agenda for a unified hardware-to-firmware correctness lifecycle.
### Title:
          Dictionary-Guided Mutation Operators for Automated HDL Repair
 - **Authors:** Maisha Mastora, Dean Sullivan
 - **Subjects:** Subjects:
Emerging Technologies (cs.ET); Artificial Intelligence (cs.AI); Hardware Architecture (cs.AR); Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated repair of Hardware Description Language (HDL) designs remains challenging due to the large search space of candidate repairs and the strict syntactic and semantic constraints imposed by HDL grammars. Generic mutation strategies overwhelmingly generate syntactically invalid candidates that waste compilation and simulation budget, while synthesis-driven and template-based approaches impose their own constraints on generality and portability. In this paper, we propose a dictionary-guided HDL repair system that combines ANTLR-derived DUT-specific mutation vocabularies with a simulation-divergence fault localization (FL) module. The mutation operator applies category-constrained token substitutions, insertions, and deletions directly to Verilog source via regex-based matching, without requiring AST manipulation or synthesis. The FL module identifies diverging output wires from a single simulation run and scores source lines by structural proximity to those signals, directing the mutation search toward high-suspicion regions. A deterministic targeted sweep exhausts all dictionary mutations on the highest-scored lines before falling back to a genetic programming (GP) search. Evaluated on the CirFix benchmark suite across six design under test (DUT) families, the proposed approach produces correct oracle-passing repairs on 14 bug variants, including a 6-edit multi-bug instance that CirFix cannot repair, and achieves an 18x speedup over CirFix on a two-edit benchmark variant. These results indicate that dictionary-constrained mutation operators, combined with lightweight simulation-divergence FL, are a practical and competitive approach to automated HDL repair for common bug classes without formal analysis or synthesis dependencies.
### Title:
          Quantum-Based k-Coverage Optimization for UAV-Aided Search and Rescue Missions
 - **Authors:** Halim Lee, Suhui Jeong, Na Young Kim, Jiwon Seo
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In large-scale disaster scenarios, rapid localization of missing persons is a critical challenge for search-and-rescue (SAR) operations. Unmanned aerial vehicles (UAVs) equipped with radio frequency (RF) receivers can support RF-based localization by collecting signals emitted from mobile devices at spatially distributed sensing locations. This paper addresses the resulting waypoint-selection problem: determining a minimum set of UAV waypoints that provides at least threefold coverage of every potential target location. We formulate this task as an extended k-coverage problem that independently defines the UAV-navigable and target regions, and derive an exact-penalty quadratic unconstrained binary optimization (QUBO) formulation with a sufficient penalty condition that preserves feasibility and minimum waypoint cardinality. The QUBO is mapped to an Ising-form cost Hamiltonian and evaluated using the quantum approximate optimization algorithm (QAOA) on both a noise-free simulator and IBM's 127-qubit Eagle processor. On the tested simulator instances, QAOA recovers the known minimum-cardinality solutions. Across the rectangular hardware test cases, the mean 3-coverage ratio exceeded 95%. In the campus-scale evaluation, ten hardware executions achieved 99.3% mean 3-coverage with a 90% feasible-run rate, while the shortest feasible flight path was up to 37.0% shorter than those of the deterministic grid-based baselines. Additional comparisons with classical optimization and learning-based baselines are provided, together with computational and quantum-resource analyses for larger generated instances. These results establish an exact QUBO representation for RF-based SAR waypoint selection and characterize its implementation on current gate-based quantum hardware.
### Title:
          GeoStore: Finding Small Storefronts in Large Scenes -- A Fine-Grained POI Localization Benchmark with Global-to-Local Asymmetric Matching
 - **Authors:** Lu Han, Xiting Sun, Hao Wang, Zhiqiang Cao, Ruihuan Du, Ziquan Zeng, Chunlong Lv
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Point-of-interest (POI) localization -- matching a user's close-up storefront photograph against large-scale geo-tagged street-view imagery -- underpins map construction, POI verification, and location-based services. Its closest existing paradigm, visual place recognition (VPR), assumes symmetric, whole-image matching of the same scene at a comparable scale; POI localization instead must match a close-up query, in which the target fills the frame, against wide references in which the same POI occupies only a small, off-center region among visually similar shops, under a substantial capture-domain gap. We introduce GeoStore, to our knowledge the first benchmark dedicated to this asymmetric, fine-grained, open-set formulation, and show that global-descriptor methods tuned for symmetric VPR are systematically limited on it, since a single global vector dilutes the small target. We further propose GLAM (Global-to-Local Asymmetric Matching), which couples a retrieval-anchoring global descriptor with an asymmetric local pathway: each reference is kept as a compact set of pooled region tokens and matched against a single query probe through a learnable soft late interaction; at inference, the same tokens enable a lightweight mutual-nearest-neighbor re-ranking. GLAM surpasses strong global and two-stage baselines on Recall@1/5/10 and mAP, with ~5x smaller re-ranking features and ~two orders of magnitude lower per-pair matching cost than prior local re-ranking. The benchmark and code will be publicly released.
### Title:
          Evidence-Guided Detection, Localization and Explanation for Text-Centric Image Forensics
 - **Authors:** Peifeng Liu, Bin Li, Qingsong Zhang, Yangxin Yu, Leqing Chen, Xiaoye Qiu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid progress of AIGC has made text-centric image manipulation increasingly accessible, creating new forensic challenges that require not only authenticity detection but also spatial grounding and evidence-based explanation. This paper presents our solution to the GenText-Forensics Challenge at ACM Multimedia 2026. We propose an evidence-guided detector-localizer-reasoner system, where an image-level detector provides a global authenticity prior, a dedicated localizer extracts tampered regions as spatial grounding evidence, and an MLLM-based reasoner generates structured forensic reports grounded in this expert forensic evidence. These modules are connected through a cascaded evidence flow: the detector gates the subsequent localization and prompting process, the localizer converts tamper responses into grounding boxes, and the reasoner is trained to synthesize the detector decision and localized evidence into the final report. As a key part of our method, we introduce iterative difficulty-aware mining to improve localization quality and apply report-mask consistency post-processing to align report grounding with predicted masks. On the official hidden test set, our system achieves a final score of 0.638 and ranks second in the challenge, validating the effectiveness of the proposed evidence-guided system. The code is available at this https URL.
### Title:
          LeakageBench: Document-Level Leakage Risk for Redacting Personally Identifiable Information in Document Images
 - **Authors:** Vishnu Prasad Vijaya Kumar, Santhosh Venkatesh, Ivan P. Yamshchikov
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-world personally identifiable information (PII) redaction often operates on document images---scans, screenshots, and PDF renderings---where OCR errors, layout structure, and visual noise determine whether sensitive information is actually removed. Existing PII benchmarks are mostly text-centric and do not measure document-level redaction risk: a page remains unsafe if even one identifier is missed. We introduce LeakageBench, a challenge set of 500 document images with 11,954 GDPR-aligned PII annotations spanning direct identifiers, linkage keys, and contextual re-identification surfaces. We evaluate generic OCR pipelines, commercial and task-adapted OCR-dependent detectors, and OCR-free vision-language models using entity-level F1, group-wise leakage, and document-level leakage metrics. Code Interpreter raises GPT-5.5 localization F1 from 0.090 to 0.249, but critical page-level leakage remains 0.968. These results show that stronger detection and tool assistance improve localization without making most pages safe for release. LeakageBench provides a diagnostic benchmark for high-recall, spatially grounded PII redaction in document images.
### Title:
          MAOL: Morphology-Aware Ordinal Learning for Fine-Grained Industrial Defect Severity Grading
 - **Authors:** Zhaoyang Wang, Haiyong Chen, Binyi Su, Kun Liu, Kun Wang, Xianen Zhou, Atik Shahariar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fine-grained defect severity grading is essential for industrial inspection, yet remains challenging due to the ordinal nature of severity labels, the strong dependence on morphology-related cues, and the train-test discrepancy between clean annotated instances and noisy predicted instances in two-stage pipelines. We propose MAOL, a Morphology-Aware Ordinal Learning framework for fine-grained industrial defect severity grading. MAOL formulates severity grading as an instance-level ordinal learning task, incorporates explicit morphological features to enhance representation learning, introduces class-conditional adaptive ordinal thresholds to model defect-specific grading boundaries, and employs prediction-aware training via localization perturbation to improve robustness to imperfect predicted instances. Extensive experiments under both clean-ROI and predicted-instance settings demonstrate that MAOL consistently outperforms rule-based methods, nominal classification models, and existing ordinal baselines, especially in the predicted-instance setting. The proposed approach ranked third in the IDA 2026 Challenge on Fine-Grained Severity Grading for High-Precision Manufacturing.
### Title:
          TempoGround: State-Aware Streaming Visual Grounding with Vision-Language Models
 - **Authors:** Leqian Ding, Junning Qiu, Manwen Yang, Yu Guo, Fei Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual grounding maps language referents to spatial targets and is central to open-vocabulary perception with vision-language models. Existing methods have made substantial progress on single-frame and video-based visual grounding, yet under streaming inputs they still suffer from identity drift, cross-frame inconsistency, and fragile localization under partial occlusion. To address these issues, we present TempoGround, a VLM-native framework that detects cross-frame object correspondence and explicitly models object presence states, thereby enabling accurate and consistent visual grounding under streaming inputs. The key is a curriculum prediction mechanism guided by state-aware cross-frame correspondence: TempoGround resolves 2D instance association, predicts whether each object newly enters, continues in, or leaves the view, decodes the 2D box, and then lifts it to a camera-frame 3D box. As token-level supervision alone cannot capture the geometric objectives of streaming grounding, we further introduce Streaming Grounding Reinforcement (SGR), which optimizes TempoGround with verifiable Grounding, Identity, and Consistency rewards, jointly reinforcing persistent localization and temporally consistent predictions. We carefully design a three-stage training strategy and train TempoGround on large-scale data. We evaluate visual grounding under causally streaming inputs on multiple challenging benchmarks: TempoGround improves F1_2D@0.5 and F1_2D@0.95 by 4.4 and 0.5 on average, and F1_3D@0.25 and AP_3D by 6.2 and 7.5, respectively. These results demonstrate that TempoGround provides a practical foundation for visual grounding under streaming inputs.
### Title:
          Diagnosing with Insights: Structured Analysis of Agent Failures via Behavioral Abstractions
 - **Authors:** Jiayi Bi, Yanjie Gao, Yuanmin Xie, Liqun Li, Tianyin Xu, Fan Yang, Mao Yang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the proliferation of LLM agents, the ability to understand and diagnose failures in agents is essential to achieving superior effectiveness and trustworthiness. As agent failures often manifest via long and complex trajectories, manually finding the needles in the haystack is untenable. However, traditional diagnosis techniques for software bugs can hardly address LLM agent failures, while completely relying on LLMs as the judge yields unreliable diagnosis results. To overcome these challenges, this paper presents AGENTSCOPE, a new neuro-symbolic approach for agent failure mode diagnosis. The key principle of AGENTSCOPE is to abstract agent behavior, based on its trajectories, into structured representations. Furthermore, AGENTSCOPE introduces the concept of neural invariants to specify agent behavior properties. AGENTSCOPE leverages LLM-guided reasoning atop the structured representation against neural invariants to pinpoint both the failure step and its type in the trajectory. We show the effectiveness of AGENTSCOPE on publicly available agent failure datasets (Who&When) and a more comprehensive dataset created by us (AgentErrata), where AGENTSCOPE significantly outperforms the current state of the art in fault localization and attribution accuracy. Our work shows that integrating structured abstractions with LLM-guided reasoning enables effective, reliable, and interpretable diagnosis for agent failures.
### Title:
          WildFab: Multi-Axis 3D Printing from Models in the Wild
 - **Authors:** Jiasheng Qu, Zhikai Shen, Chenyu Xu, Hailin Sun, Chengkai Dai, Yuhu Guo, Junpeng Wang, Yeung Yam, Guoxin Fang
 - **Subjects:** Subjects:
Graphics (cs.GR); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-axis 3D printing enables support-free fabrication and improved part quality, but robustly processing real-world geometries remains challenging. Models from design workflows or direct data acquisition often contain solid--shell combinations and non-manifold structures. Handling such models in the wild typically requires time-consuming geometry repair, which may alter the intended geometry. In this work, we present WildFab, a computational framework for multi-axis 3D printing that directly computes spatial toolpath and global collision-free motion from input models. Our pipeline builds on a hybrid query representation that combines a neural unsigned distance field (UDF) with a regularized generalized winding number field (reg-GWN). The UDF supplies differentiable surface-distance and direction queries, while the reg-GWN resolves near-surface ambiguity in the fitted UDF by providing reliable surface localization and a solid-void indicator. Based on this representation, we introduce a high-precision spatial toolpath computation algorithm that iteratively projects points between optimized guidance-field level sets and reg-GWN gradient-magnitude ridges. Subsequently, we develop an efficient and robust coarse-to-fine collision checking scheme for motion planning: UDF-based rejection first identifies potential collisions, while time-varying reg-GWN verification accurately resolves collision pairs for both solid and shell components. We validate WildFab on diverse inputs, demonstrating successful computation from non-manifold parametric surfaces, voxelized topology-optimization results, implicit models, raw scanned point clouds, and non-watertight meshes. The fabrication results highlight our method's ability to advance end-to-end design-to-3DP workflows.
### Title:
          Adapting a Foundation Model for Lunar Surface Height Estimation
 - **Authors:** Patrick Bauer, Marius Schwinning, Melanie Siegel, Andreas Weinmann, Hichem Snoussi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Digital elevation models (DEMs) can provide accurate height information, making it invaluable for analyzing the lunar surface. As the European Space Agency (ESA) prepares for future lunar missions that aim to land on the Moon, a precise method for height estimation will be essential for hazardous terrain that could endanger the landing approach. Traditional approaches to generate DEMs from imagery, such as shape from shading (SfS) and stereophotogrammetry (SPG) have been proven highly valuable for this task. However, due to advancements in machine learning, especially computer vision, the focus has shifted towards monocular depth estimation via deep learning. The lunar surface is covered by rocks and craters, and classic hazard detection methods rely solely on 2D image data. Our goal is to address this issue by developing a relative lunar surface height estimator that can provide additional information for hazard localization. In this letter, we present a methodology that builds on the well-known zero-shot relative depth estimation model Depth Anything V2 (DAV2). Other works have been using it as a state-of-the-art comparison for their proposed lunar DEM estimation method, but without adaptations to the target domain. Thus, it may underperform. Therefore, we propose a fine-tuning strategy with publicly available SPG-derived DEM data of the lunar surface. Our results demonstrate a significant improvement in performance compared to the zero-shot model, effectively transforming DAV2 into a reliable relative depth estimator of the lunar surface.
### Title:
          Learning to Track from Privileged Target Appearances
 - **Authors:** Xin Chen, Jiao Xu, Dong Wang, Huchuan Lu, Kede Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Target templates define what a visual tracker searches for, yet the templates available at inference trade off localization certainty with appearance freshness: the initial ground-truth template is exact but becomes stale, whereas recent templates better reflect the current appearance but are cropped from uncertain predictions. We quantify this bottleneck with a non-deployable oracle that supplies an exact current-frame target crop, improving AUC on LaSOT by 15.2 percentage points. This gap reveals a training-only opportunity: frame-level ground truths provide exact current- and future-frame target crops, although such crops are unavailable at deployment. We introduce Privileged Appearance Transfer for Tracking (PATT), a teacher-student training framework that transfers these privileged appearances to a deployable tracker through multi-level representation prediction. The privileged teacher observes exact target crops from past, current, and future frames, whereas the student receives only past-frame templates and learns to predict the teacher's search representations. To avoid transferring unreliable teacher signals, PATT weights this transfer by the teacher's relative localization advantage over the student and its absolute localization accuracy. After training, the teacher, latent predictor, reliability weights, and privileged crops are removed, leaving standard student-only inference. Across seven benchmarks at two model scales, PATT achieves consistent gains under both long- and short-term tracking protocols.
### Title:
          Fine-Grained Anomaly Perception in Wild UGC-Enhanced Images: A Comprehensive Dataset and Difference-Fusion Framework
 - **Authors:** Yan Zhong, Gefei Chen, Qiufang Ma, Zhen Wang, Zhiwei Fan, Lei Shi, Tingting Jiang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Image enhancement and restoration have become standard back-end operations on short-video and social media platforms to boost UGC visual experience. Yet these processes inevitably introduce visual anomalies--especially in faces, texts, and textures--that directly undermine perceptual fidelity and viewer trust. While existing IQA methods perform well on classic distortions, they target holistic quality assessment and fail to capture the specific, localized anomalies caused by enhancement algorithms in real-world UGC. To bridge this gap, we formally define a new task-quality Anomaly Perception for UGC image Enhancement (UEAP), and contribute the first UEAP benchmark dataset, named UEAP-4k, curated from the real business scenarios. It provides fine-grained annotations for anomaly categories, localization and severity levels. Furthermore, we propose a Difference-Fusion Anomaly Perception Method (DFAP-UGC) for wild UGC-enhanced images, which leverages explicit problem-reference difference fusion with dense spatial querying, regional verification, and quality-aware ranking, enabling robust anomaly identification in challenging scenarios. To handle the inherent coupling of subtasks in this new task, we propose a Locality-Aware Dynamic Task Prioritization (LADTP) training strategy that enables effective end-to-end learning and eliminates multi-stage overhead. Extensive experiments show that our method outperforms baselines adapted from classical approaches for this task, validating the value of this dataset and the superior of DFAP-UGC for robust UGC-enhanced image anomaly perception. Code and data will be public.
### Title:
          TrajMind: Chaining Role-Specialized LoRAs for Fast-and-Slow Collective Trajectory Anomaly Diagnosis
 - **Authors:** Jiahao Wu, Zhenqun Yang, Chen Jason Zhang, Qing Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diagnosing collective anomalies from urban trajectories is increasingly important for traffic governance, as it reveals what happened, who was involved, and where and when the event occurred. Existing detectors efficiently produce scores or labels, whereas vision--language pipelines provide richer semantics; neither couples verifiable diagnosis with low-latency monitoring. The central challenge is to recognize collective patterns and recover exact event details from the source trajectories without running the full diagnostic pipeline for every monitored window. We therefore separate always-on screening from on-demand diagnosis: screening raises alerts, while diagnosis releases only source-verified what--who--where--when records. We present TrajMind, a fast-and-slow framework that switches three role-specialized LoRA adapters over one frozen vision--language backbone. Its slow path, \textit{TrajMind$_{\text{slow}}$}, chains canvas-based typing, type-conditioned localization over serialized trajectories, and executable verification, yielding structured, evidence-backed diagnoses. Additionally, the fast path, \textit{TrajMind$_{\text{fast}}$}, screens each window in a single text-only pass, delivering efficient structured alerts. Extensive experiments show that, TrajMind$_{\mathrm{slow}}$ outperforms the strongest baselines by at least $15.3$ percentage points in anomaly typing and $13.8$ percentage points in localization. These gains persist under cross-city transfer, and TrajMind$_{\mathrm{fast}}$ reduces latency by $41.1\%$ and maintains binary balanced accuracy of at least $93.5\%$. Together, TrajMind delivers accurate, evidence-backed diagnoses across cities and efficient front-line monitoring.
### Title:
          From Detection to Localization: A Unified Forensics Framework for Fully Synthetic and Tampered Images
 - **Authors:** Annalisa Gallina, Marco Fiorucci, Marco Brigo, Federica Battisti, Lamberto Ballan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid advancement of generative models has significantly worsened the problem of manipulated image detection, as these methods are capable of producing highly realistic forgeries, reinforcing the importance of multimedia forensics. Conventional approaches typically frame image manipulation detection as a binary classification task (real vs. generated), which limits the capability to distinguish and localize different forms of manipulation. To address these constraints, this work extends an existing detector by introducing a unified multiclass framework (real vs. fully generated vs. tampered). In addition to classifying image authenticity, the framework incorporates a segmentation branch to enable pixel-level localization of tampered regions. The proposed approach outperforms selected recent benchmarks, offering an efficient solution with improved classification accuracy and higher IoU scores for the localization task. Find the code at this https URL.
### Title:
          Characterizing Text Branch Sensitivity in Medical Vision-Language Segmentation via Evidence Decoupling
 - **Authors:** Ziquan Liu, Zhewei Zhu, Xuyang Shi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pretrained vision-language models (VLMs) have shown promising performance in medical image segmentation by incorporating clinical text. However, it remains unclear how much textual information actually contributes to pixel-level predictions. In this work, we systematically investigate the role of text in multimodal medical image segmentation. We first analyze several commonly used fusion strategies and find that segmentation performance is largely insensitive to the choice of fusion module. To further understand modality interactions, we propose an Evidence Decoupling Decoder (EDD) based on evidential deep learning and deep supervision. EDD serves as an internal representation analysis tool that decomposes image evidence and text-modulated evidence throughout the decoding process while maintaining competitive segmentation performance. Experimental results show that the sensitivity to text perturbation varies substantially across datasets. On BUSI and BTMRI, removing text causes catastrophic performance drops, indicating strong model reliance on textual input. On ISIC and Kvasir-SEG, text exerts relatively marginal influence. We further find that text affects predictions mainly through global semantic modulation rather than independent spatial localization, and that the specific semantic components driving text sensitivity differ across datasets. These findings provide a deeper understanding of modality interaction in multimodal medical image segmentation and offer practical insights for future model design.
### Title:
          Query Rewriting for Complex Object Segmentation in 4D Gaussian Representations
 - **Authors:** Thanh-Khoi Nguyen, Thien-Phuc Tran, Minh-Triet Tran
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent 4D Gaussian representation frameworks have demonstrated strong performance in language-guided dynamic scene understanding. However, these methods remain highly sensitive to verbose and narrative-style queries that contain noisy contextual information. In this paper, we investigate the impact of query rewriting for complex object segmentation in 4D Gaussian representations. Inspired by recent findings in retrieval-augmented language models and keyword-guided query reformulation, we propose a training-free reinterpretation strategy that transforms long descriptive queries into concise keyword-grounded forms. Our approach progressively reduces linguistic noise while preserving semantic anchors relevant to object-centric representations. Experiments on HyperNeRF and Neu3D demonstrate that concise rewritten queries significantly improve both temporal localization and spatial segmentation performance. In particular, our method improves average temporal accuracy from 60.92% to 92.21% and average vIoU from 20.08% to 76.94% without any additional fine-tuning. Extensive ablation studies further reveal that shorter, keyword-focused queries consistently yield stable video-feature similarity distributions and better alignment with object-centric Gaussian representations
### Title:
          A Top-Down Framework for Metric-Scale Athlete Localization from Single Broadcast Frames
 - **Authors:** Thanh-Khoi Nguyen, Hoang-Phuc Nguyen, Linh-Huynh, Minh-Triet Tran
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate world-coordinate localization of athletes from single-frame broadcast footage is inherently challenging due to extreme scale disparities in ultra-high-resolution imagery. In this paper, we propose a top-down framework for metric-scale athlete localization from a single calibrated frame. Our approach centers on three key contributions. First, we propose Boundary-Aware Adaptive Tiling, a semantics-guided extension of standard sliced inference. By iteratively expanding tile boundaries based on coarse bounding-box predictions, it systematically ensures full object containment, effectively mitigating boundary-splitting artifacts through a lightweight pipeline adaptation without architectural modifications. By substantially mitigating recall degradation under extreme scale variance, Boundary-Aware Adaptive Tiling enables us to isolate perspective distortion as the primary source of residual localization error. Second, we adapt the RTMPose-X architecture into a specialized two-keypoint estimator (pelvis and ground projection), employing a reformulated Gated Attention Unit optimized for this geometrically coupled point pair, and then deterministically lift the 2D ground projections into world coordinates via camera-calibrated ray casting. On the public test set, our method achieves a LocSim score of 97.44 and an mAP of 0.9128, outperforming the baseline by over 21 \% and establishing a robust solution for high-resolution scale variance.
## Keyword: transformer
### Title:
          NeoMME: A Single-Tower Multimodal-Native Multilingual Foundation Encoder for Efficient Fine-Tuning and Inference
 - **Authors:** Aurélien Lac, Tony Wu
 - **Subjects:** Subjects:
Information Retrieval (cs.IR); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal models often build on architectures designed for generative vision-language modeling, typically combining separately pretrained vision encoders with causal language models. Visual document retrievers such as ColPali repurpose these models as encoders, carrying over the parameter and compute overhead of a VLM for a non-generative task. We introduce NeoMME, a family of 260M and 800M-parameter Multimodal and Multilingual bidirectional Encoders that process multilingual text and raw image patches in a single bidirectional Transformer encoder. Both models are pretrained from scratch with a masked discrete-diffusion text objective, conditioned on visible image patches for multimodal examples. Both support a 16,384-token context, enough to encode up to two standard 4K UHD images. To demonstrate its downstream capabilities, we fine-tune NeoMME with jointly trained dense and late-interaction heads. On the ViDoRe v3 benchmark, the resulting NeoMME-Retriever 260M outperforms all evaluated models strictly below 800M parameters with 0.523 nDCG@10, while NeoMME-Retriever 800M reaches 0.556. At a matched 2048x2048 image input size on an NVIDIA L40S, NeoMME-260M encodes pages with about 2x the throughput of ColModernVBERT. Hierarchical token pooling and asymmetric quantization compress late-interaction multimodal document embeddings by 255x while preserving over 95% of baseline nDCG@10. We contribute NeoMME to Hugging Face Transformers and release the pretrained backbone and retrieval-compatible checkpoints under Apache 2.0 at this https URL.
### Title:
          ZipTok3D: High-Fidelity 3D Tokenization with Compact Token Prefixes
 - **Authors:** Mingda Lin, Weijie Wang, Zeyu Zhang, Bowen Cui, Yefei He, Haoyu Zhao, Yuanyu He, Donny Y. Chen, Feng Chen, Bohan Zhuang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Compact token sequences are essential for efficient 3D generation. However, existing 3D tokenizers typically organize latent representations either over spatial regions or as fixed-size sets of global tokens, both suffering sharp reconstruction degradation when compressed to extremely low token budgets. In this paper, we present ZipTok3D, a 3D tokenizer designed for high-fidelity reconstruction from extremely short token sequences. Its key idea is to organize object geometry into progressively informative global-token prefixes and unfold these compact representations through iterative decoding. Specifically, nested dropout randomly truncates the latent sequence after encoding during training and requires each retained prefix to reconstruct the complete object, thereby prioritizing essential geometric information in the leading tokens. The decoder then repeatedly applies a parameter-shared Transformer block to recover fine-grained geometry from each prefix without a separate generative sampling stage. With the same token dimension, ZipTok3D achieves reconstruction quality comparable to the 32-token COD-VAE baseline using only one token on ShapeNet and four on TRELLIS, yielding $32\times$ and $8\times$ shorter token sequences, respectively.
### Title:
          Swin Meets EfficientNet: Lightweight Architectures for GAN-Based Face Forensics
 - **Authors:** Sejuti Basu, Ashima Sood, Vijay Kumar, Sahil Sharma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern generative models, such as GANs, diffusion architectures, and autoregressive systems, now produce facial images that are nearly indistinguishable from authentic photographs. This capability makes detecting forged images increasingly difficult, raising serious concerns about identity theft, fraud, and misinformation campaigns. Our research focuses specifically on GAN-generated synthetic faces, which underpin many face-centric deepfakes, and investigates efficient detection approaches using image analysis alone. Existing detection systems rely heavily on either convolutional neural networks (CNNs) or global vision transformers. While CNNs excel at identifying texture-based local features, they struggle with broader contextual understanding. Traditional Vision Transformer (ViT) models can capture long-range structures effectively, but demand substantial computational resources. Our work explores Swin-Transformer-based architectures across three implementations: a compact Swin Transformer trained from the ground up, ImageNet-1K pre-trained Swin-Tiny and Swin-Small models adapted for binary classification, and a novel hybrid combining EfficientNet-B0's convolutional processing with a Swin Transformer backend. We evaluated all models using the 140K Real and Fake Faces dataset, which includes StyleGAN-generated fake faces alongside authentic images from Flickr and DFDC, with balanced splits for training, validation, and testing. The EfficientNetB0+Swin hybrid achieved 99% accuracy and a 99.44% recall on 5,000 test images, outperforming both pure Swin variants and a previous CNN-only baseline on this dataset. Our results suggest that combining hierarchical CNN features with shifted-window self-attention provides an efficient and computationally lightweight method for detecting GAN-generated synthetic faces.
### Title:
          Emergence of Fibrations, Compression, and Symmetry Breaking in Artificial Neural Networks
 - **Authors:** Osvaldo M Velarde, Lucas C Parra, Alireza Hashemi, Hernan A Makse
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Artificial neural networks are often regarded as powerful yet opaque black boxes. Here, we demonstrate that learning in deep neural networks generates local symmetries known in graph theory as fibrations and coverings. We prove that covering symmetries are stable attractors of stochastic gradient descent. Consistent with this theory, we report the emergence of covering symmetries across major network architectures, including multilayer, convolutional, recurrent, and transformer networks. Exploiting these symmetries enables drastic model compression - reducing networks to 17% of their original size without sacrificing performance. Furthermore, controlled breaking of covering symmetry overcomes the loss of plasticity, achieving state-of-the-art performance in continual learning. The theoretical results provide a new foundation for AI systems based on symmetries that convert black boxes into interpretable colored graphs and enable more efficient inference and lifelong learning.
### Title:
          Ten Architectures, One Error: Shared Failure Modes in Hyperspectral Classification under Spatially Disjoint Evaluation
 - **Authors:** Ehsan Faghih, Fatemeh Ashrafi, Marguerite Moore, Zahra Saki
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hyperspectral image classification still relies heavily on random pixel splits within a single scene. The Salinas dataset, randomly split, is among the most widely used datasets for comparing different architectures. However, under a random split method, a large fraction of test pixels fall immediately adjacent to a training pixel, which inflates reported accuracy. This work introduces a leakage-free evaluation protocol linking spatial separation to the model's receptive field. Applying this protocol across ten different architectures, including classical, spectral, spectral-spatial, transformer, vision-backbone, and state-space families, shows that Macro-F1 drops by 0.147 on average and model rankings change by as many as five places. Furthermore, leakage-free evaluation limits which architectures can be tested on a given benchmark. Since each partition supports patches only within a finite radius, reporting this radius alongside the receptive field is essential for fair comparison. In addition, this study reveals that all ten architectures misclassify largely the same pixels, pointing to a spectral ambiguity in the data that none of them resolves.
### Title:
          CoViT: Instance-Correspondence Contrastive Learning for Vision Transformer
 - **Authors:** Yisen Wang, Zhirong Wu, Limin Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformers (ViT) excel in semantic understanding but fail to discriminate between object instances (e.g., identical embeddings for two dogs), limiting their use in instance-level tasks such as object detection and instance segmentation. We propose Contrastive Vision Transformer (CoViT), a self-supervised learning framework that injects instance-awareness into ViT through geometry-guided contrastive learning. CoViT uniquely coordinates ViT's attention maps and embeddings by constructing triplets: (1) Attention-guided masking: Refine multi-head attention via adaptive thresholding and morphological operations to generate instance masks, identifying foreground anchors; (2) Hardest contrastive mining: For each anchor, computing pairwise embedding similarities to select the intra-instance hardest positive (least similar patch within its mask) and inter-instance hardest negative (most similar patch from other instances), with intra-instance regions masked during negative search. These triplets drive a contrastive loss that simultaneously compresses intra-instance variance and expands inter-instance margins, forcing ViT to discern subtle geometric and appearance differences between instances. CoViT consistently achieves stable performance gains of over 2 AP points across multiple instance-level perception tasks by using ViT as backbone architecture. Notably, CoViT requires no extra decoders or labels, demonstrating that a pure ViT can learn instance-aware representations via inherent attention priors and targeted contrastive constraints. Code and models will be released.
### Title:
          Designing Versatile Samples for Learned Trajectory Scoring
 - **Authors:** Yaguang Li, Jiaru Zhang, Chuheng Wei, Can Cui, Ziran Wang
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many current end-to-end driving policies emit a pool of candidate trajectories and select one, which makes selection a separable component: a scorer can be retrained while the planner, its backbone, and its trajectory generator all stay frozen. However, many strong planners concentrate their proposals around safe mode, providing limited supervision near decision boundaries. In this work, we design a training dataset that provides more informative supervision for the scorer. In particular, we construct two generators that perturb the logged human trajectory along the two axes a vehicle can be displaced: laterally toward the drivable boundary and longitudinally toward a leading vehicle. The designed dataset produces more informative positive and negative samples than the base planner's proposal pool. We attach a transformer-based scorer to two frozen generative planners, DiffusionDrive and MeanFuser, and train it on the NAVSIM navtrain dataset. The results of the experiments show that we achieve 90.1 EPDMS on DiffusionDrive and 90.4 EPDMS on MeanFuser when using ResNet-34, with 0.4 and 0.3 EPDMS respectively, from the designed training dataset.
### Title:
          Improved Automatic Target Recognition in Synthetic Aperture Sonar Imagery Using Large Deep Neural Networks
 - **Authors:** C.J. Moore, Alex Hurt, Jordan Malof
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automatic Target Recognition (ATR) in Synthetic Aperture Sonar (SAS) is a task largely dominated by deep neural networks (DNNs). Most SAS-ATR models use convolutional neural network (CNN) architectures whereas transformer-based architectures have had much less representation in the literature despite being state of the art in general computer vision (CV) research. Additionally, researchers have had mixed results in attempting to overcome challenges presented by a scarcity of labeled training data by using methods such as data augmentation and the use of pretrained weights from a variety of imaging modalities. In this work, we compare the performance of modern CNN and transformer-based DNNs to determine which architecture and training configurations elicit the highest performance in SAS-ATR. We investigate how network size, architecture, pretraining method, data augmentation and other forms of regularization affect SAS-ATR performance with a focus on producing the highest-performing model and providing a roadmap for training state-of-the-art SAS-ATR models.
### Title:
          Looped Transformers under the Jacobian Lens: Does the Global Workspace Survive Recurrence?
 - **Authors:** Wenlong Wang, Fergal Reid
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent work identifies a mid-depth band of verbalisable, causally potent representations in a standard feedforward transformer --- a functional analogue of a global workspace. Whether the same workspace functionality emerges when depth is implemented through recurrence rather than a stack of distinct layers remains unknown. Looped and depth-recurrent transformers provide a direct test of this question because they reuse the same weights across depth. We extend the Jacobian lens to iterated architectures using a virtual-unrolling adapter. We apply the full workspace suite --- lens fitting, readout, and eleven causal experiment families --- to Ouro-2.6B (48 layers looped 4 times, deeply supervised) and Huginn-0125 (a 4-layer core recurred 16 times, trained for latent reasoning), using Qwen3.6-27B (64 untied layers) as the standard baseline. We find that a workspace forms in the iterated part of each architecture, but that recurrence changes how it can be accessed. Ouro reconstructs workspace content in every loop, and linear transport cannot carry that content across loop boundaries; writes and ablations must therefore span every remaining loop. Huginn carries content forward across all sixteen recurrences, while reads, writes, and ablations act only within a sliding window of roughly two recurrences. Whether newly injected content can be verbalised tracks explicit per-iteration supervision; whether existing content can be steered does not.
### Title:
          OR-Transformer: Scaling Real-Time Decision-Making to 1,000 Items
 - **Authors:** Shuze Daniel Liu, David Simchi-Levi, Claire Chen, Chutong Gao, Shangtong Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern supply chain operations can require coordinating replenishment across thousands of heterogeneous items under correlated stochastic demand, heterogeneous lead times, and shared fixed ordering costs, yielding observation spaces exceeding $10^4$ dimensions. At this scale, rolling-horizon stochastic mixed-integer linear programs (MILPs) become prohibitively slow, while standard reinforcement learning (RL) methods face increasingly challenging credit assignment in high-dimensional action spaces. We introduce OR-Transformer, a deep reinforcement learning framework for joint replenishment under stochastic demand, with an item-permutation-equivariant Transformer architecture and pathwise-gradient training through the inventory dynamics. Across problem sizes up to 1,024 inventory items, OR-Transformer increasingly outperforms learning-based and rolling-horizon MILP baselines as scale grows. It also reduces online decision-making time by over 4 million times relative to MILP solvers, enabling real-time, large-scale deep RL in supply chain operations.
### Title:
          Aggregating Neighbor Embedding Projection and Rank-Based Manifold Learning for Image Retrieval
 - **Authors:** Vinicius Atsushi Sato Kawai, Gustavo Rosseto Leticio, Lucas Pascotti Valem, Daniel Carlos Guimarães Pedronette
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Content-based image retrieval (CBIR) has advanced significantly with deep learning, yet effectively ranking similar images remains challenging, particularly in high-dimensional feature spaces, where pairwise distances often fail to capture contextual relationships and the semantic gap between visual features and high-level concepts persists. Manifold learning and rank-based refinement methods have emerged as complementary strategies, respectively improving feature representations and exploiting contextual information embedded in ranked lists, such as neighborhood relationships among images. However, combining these projection-based and rank-based strategies to exploit their complementary properties remains a challenging research problem. To address this, we propose a framework that combines neighbor embedding projections with rank-based manifold learning through rank aggregation. Uniform Manifold Approximation and Projection (UMAP) generates alternative low-dimensional feature representations, and ranked lists obtained from UMAP projections and rank-based re-ranking methods are combined using the Borda Count aggregation strategy. Experiments were conducted on several public datasets using deep learning features extracted from ResNet152, Swin Transformer, and DINOv2 models. Results show that the proposed approach improves retrieval effectiveness in several scenarios, particularly when the baseline representation struggles to achieve high precision. The aggregation strategy also often improves the quality of top-ranked positions, leading to competitive Mean Average Precision (MAP) and Precision values across different datasets and feature extractors. These findings suggest that combining projection-based and rank-based manifold learning strategies through rank aggregation can provide complementary contextual information for image retrieval tasks.
### Title:
          The Dynamics of Continuous Mixture Collapse in Language Models
 - **Authors:** Ali Backour
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLMs latent-state reasoning methods replace discrete intermediate tokens with continuous states, such as weighted mixtures of token embeddings, to retain multiple possible reasoning directions rather than committing to one. Yet pretrained language models often fail to preserve these mixtures. We study why through a combination of theoretical analysis and controlled empirical investigations on a variety of models. We identify three independent, distinct sources of failure. First, transformer architectures already distort mixture geometry, and training substantially amplifies this effect. Moreover, the failure can occur even if the model transports mixtures perfectly linearly: the softmax readout and autoregressive feedback form a dynamical system that either amplifies small differences until one component of the mixture dominates or contracts different mixtures until they become indistinguishable. We verify this theoretical prediction empirically: the observed transition between contraction and amplification occurs near the theoretical threshold derived by our analysis, and pretrained-model rollouts lie predominantly on the amplifying side. Finally, we generalize to mixtures of many components and show that exact preservation generally requires context-dependent correction, whose required dimensionality can grow with the number of components.
### Title:
          XMerge: Cross-Axis Selection and Reconstructive Layer Merging for LLM Depth Compression
 - **Authors:** Jundong Hu, Shekar Ramachandran
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Removing complete transformer layers preserves a standard serving architecture, but existing depth-compression methods can lose substantial quality, and the loss varies unpredictably across models. We introduce XMerge, a post-training method with two components. Cross-axis selection identifies a block with low relative-magnitude and angular hidden-state change, and local boundary reconstruction re-fits the adjacent surviving block to match the original two-block output. XMerge uses no task labels or end-to-end fine-tuning, and it introduces neither architectural changes nor additional inference-time parameters. Across seven Llama and Qwen backbones (0.5B-8B), five published baselines, and three layer-reduction levels, its advantage over baselines is largest at the most aggressive removal: at k=4 it ranks first on six of seven backbones on CORE (a 22-task aggregate) and, separately, on six of seven on MMLU (five of seven on both at once), while avoiding the large perplexity increases of several competing operators. In a task-level bootstrap, the 95% confidence intervals for the three largest CORE margins exclude zero; the remaining margins are consistent with ties. Across the 14 (model, regime) cells it is also the only evaluated operator that never collapses, ranking top-2 in both zero-shot and in-context regimes; on a first calibration probe (one backbone) it is the best-calibrated operator. Ablations show that local reconstruction provides most of the gain, while cross-axis fusion helps when the two selection axes disagree. The additional construction cost is recovered through per-token decode savings after roughly tens of thousands of requests.
### Title:
          C$^{3}$T: Counterfactual Causal Reasoning for Sentiment Shifts in Social-Media Conversation Trees
 - **Authors:** S M Rafiuddin, Atriya Sen
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sentiment in social-media threads does not only vary across posts; it shifts as users react to claims, corrections, evidence, and hostility within a branching reply tree. We study why sentiment changes in rumor-centric conversation trees by treating discourse moves (e.g., denial/correction, evidence/link, toxicity/attack) as candidate interventions and asking (i) what sentiment a reply expresses, (ii) whether the sentiment shifts relative to its parent, and (iii) which prior message most plausibly drove the reply's sentiment. To support this setting, we introduce CaSiRe, a causal sentiment reasoning layer over public rumor conversation datasets that adds post-level sentiment labels, induced parent-child shift labels, calibrated multi-label intervention tags, and explicitly annotated causal-source labels. We then propose C$^{3}$T (Counterfactual Causal Conversation Transformer), a thread-structured temporal model that jointly predicts node sentiment and shifts, learns sparse ancestor attribution, and supports counterfactual queries by forcing conversational intervention embeddings on or off to estimate potential outcomes. Under an event-level split, C$^{3}$T improves out-of-event robustness and attribution over text-only, graph-based, and temporal baselines, and yields interpretable model-based effects: denials/corrections and evidence reduce downstream negativity, while toxicity increases it. We also benchmark open-weight LLM prompting baselines and find that added conversational context helps, but attribution remains less reliable, motivating structure-aware counterfactual modeling for social-media analysis.
### Title:
          Lightweight Adaptation of General-Purpose VLMs for Multispectral and SAR Image Understanding
 - **Authors:** Shanji Liu, Kelu Yao, Junxiao Xue, Chenghui Lv, Xiangyang Miao, Yekai Huang, Yaying Chen, Chao Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 General-purpose vision-language models (VLMs) now support strong visual recognition, instruction following, and generation. However, most pretrained visual encoders are built around three-channel natural images and do not directly accommodate observations such as native multispectral measurements or synthetic aperture radar (SAR). Adapting VLMs to these sensors typically requires dedicated encoders and domain pretraining, slowing the reuse of stronger general-purpose checkpoints. We show that the multi-image interface of general-purpose VLMs offers a lightweight alternative. Our protocol renders each observation as five optical views and one SAR view, names them in the prompt, and adapts the language network and selected visual transformer blocks with LoRA. This exposes band composites, spectral indices, and radar backscatter through an existing visual interface. For land-cover recognition, structured supervision couples predicted classes with sensor evidence. We further construct preference pairs in which a true label is omitted while its supporting evidence is retained, encouraging complete predictions that remain consistent with the observations. On a balanced six-class land-cover benchmark derived from BigEarthNet-v2, the adapted Qwen3-VL reaches 0.8275 micro F1. The same input and adaptation protocol improves all four tested VLM architectures and transfers to Sen1Floods11 flood verification and this http URL captioning. Image removal and mismatch controls show that the adapted models use the supplied sensor observations. Together, these results demonstrate that VLMs can be repurposed for multispectral and SAR tasks through rendered inputs and compact LoRA adaptation, without training a new foundation model.
### Title:
          SMart: A Multi-source Multi-phase Time Series Representation Transfer Framework
 - **Authors:** Fang He, Wang-chien Lee
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Time series representation learning (TSRL) has attracted growing research interests in recent years. Two recent explorations in TSRL are: i) exploiting a transformer-based framework to learn time series; ii) instead of using only the targeted dataset, borrowing time series from other datasets to to facilitate representation transfer. While these two explorations are shown effective, the self-supervised time series recovery task in (i) and the single-source dataset used in (ii) are technically simple and thus can be enhanced with new ideas. In this work, we propose a new TSRL framework, namely multi-source multi-phase time series representation transfer (SMart), which has two novel mechanisms to address the aforementioned deficiencies: 1) a multi-phase recurrence plots recovery task, in three alternative modes, for guiding the encoder to embed time series dynamics into the time series representation; and 2) a source dataset selector to select multiple suitable source datasets to supplement the original target dataset for pre-training the TSRL encoder. Experimental results show that SMart outperforms several state-of-the-art models for time series representation learning, classification and regression on both uni-variate and multi-variate time series datasets, reducing mean absolute error up to 19.5% for time series regression, and increasing average accuracy up to 1.34\% for time series classification.
### Title:
          Fairness-Aware Multimodal Transformer Modeling for Real-Time Student Attention Estimation
 - **Authors:** Christoforos Fragkiadakis, Seyed Sahand Mohammadi Ziabari, Ali Mohammed Mansoor Alsahag
 - **Subjects:** Subjects:
Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated student-attention estimation can support learning analytics, but aggregate predictive metrics can conceal demographic disparities. This study evaluates fairness-aware multimodal temporal models on DIPSER, a naturalistic classroom dataset combining facial images, wearable-sensor measurements, attention annotations, and automatically inferred demographic metadata. Three baselines are compared across 10 training seeds: a Visual GRU, a Sensor GRU, and a Residual Fusion Transformer. The multimodal model achieves the best mean test performance (MAE 0.283, RMSE 0.363) and the lowest worst-group error among the evaluated baselines, although its gain over the Visual GRU is modest. Gender- and age-targeted MAE-gap regularization reduces disparities on validation data, but these gains do not consistently transfer to held-out subjects or repeated subject-level splits. On an NVIDIA A100-SXM4-40GB GPU, the warm end-to-end pipeline averages 50.65 ms per prediction window at a one-second stride, while the temporal model itself requires 1.02 ms. The findings show that multimodal fusion can modestly improve prediction and worst-group performance, but validation-level fairness gains should not be assumed to generalize. Robust fairness assessment therefore requires subgroup-aware evaluation, repeated subject-level validation, and larger, better balanced demographic samples.
### Title:
          If It Moves, Radar Knows: A Physics-Aware Radar Transformer for Class-Agnostic Moving-Object Detection
 - **Authors:** Yinghao Sun, Shuguang Li, Jinliang Shao, Tieshan Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Detectors trained on closed-set annotations can miss rare moving objects outside the training taxonomy. Automotive radar provides category-independent Doppler motion cues and is less affected by adverse illumination and weather, but sparse, noisy returns hinder class-aware 3D box detection. Surface location and velocity remain useful for motion reasoning and collision avoidance when full box geometry is difficult to recover. We present the Physics-Aware Radar Transformer (PART), a fully sparse radar-only detector that predicts existence confidence, a representative surface point, and 2D ground-plane velocity for each moving-object hypothesis. Doppler-Aware Query Initialization (DAQI) replaces scene-independent learned queries with input-dependent proposals by clustering radar returns in position and velocity, easing query-object assignment in sparse scenes. Physics-Guided Cross-Attention (PGCA) incorporates radial-Doppler consistency and radar cross section (RCS) into query-point association. Uncertainty-aware supervision randomly masks ground-truth objects and assigns soft existence targets to ambiguous radar-supported queries, reducing reliance on exhaustive annotations. With only 1.1 million parameters, PART achieves a class-agnostic average precision (CA-AP) of 0.8827, a mean average surface translation error (mASTE) of 0.3188 m, and a mean average velocity error (mAVE) of 0.8084 m/s on nuScenes. It attains 0.9203 recall on rare and safety-relevant categories excluded from the standard evaluation and remains effective at night, in rain, and under severe occlusion. Inspection of apparent false positives shows that some predictions correspond to moving objects absent from the nuScenes annotations. Code and pretrained model weights will be publicly available at this https URL.
### Title:
          AGI Maze Prediction Datasets: A Compact Benchmark for Learning World Dynamics with Transformers
 - **Authors:** Alexey Potapov
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World modeling requires a predictive model to maintain and update an internal state adequate for reasoning about the consequences of actions. We introduce the AGI Maze Prediction Datasets and Benchmark, a lightweight controlled testbed for studying this capability in Transformers and other predictive models. Derived from procedurally generated, stateful grid worlds, the benchmark comprises per-step transition prediction, fixed-horizon state prediction, and sequential textual-observation prediction. Source-maze-disjoint training and validation splits, together with greedy exact-match evaluation, distinguish learning transferable action-conditioned dynamics from memorizing transitions in familiar layouts. We establish from-scratch byte-level Transformer baselines and compare them with two working-memory-augmented architectures. A generic auxiliary latent-memory Transformer can fit some training sets perfectly but does not consistently improve held-out performance. In contrast, a pseudo-video spatial-memory Transformer initializes a two-dimensional latent workspace from the input map and updates it from action history without receiving intermediate maps, positions, or state labels. Under the same data, objectives, and evaluation protocol, this model reaches perfect validation accuracy on selected fixed-horizon tasks where the byte and unstructured-memory baselines do not, and substantially improves sequential text-trace prediction. These results suggest that structured, task-aligned working memory can be more useful than additional latent capacity alone. More broadly, we argue that language grounding is mediated by persistent data structures and computations over them; the benchmark offers a compact setting for testing architectures that couple textual interfaces to learned structured state.
### Title:
          GlyphAnchor: Enhancing Visual Text Rendering via Position-Anchored Glyph Priors
 - **Authors:** Qiang Xiang, Shuang Sun, Binglei Li, Yibo Chen, Xu Tang, Yao Hu, Junping Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rendering accurate text remains difficult for image generation and editing models, especially when the target contains long, complex, and densely arranged text or rare characters. Existing approaches either improve native text rendering through stronger backbones and data-centric training without explicit glyph priors, or incorporate glyph priors through specialized designs that remain insufficiently accurate and robust under challenging scenarios. We introduce GlyphAnchor, a novel text-rendering enhancement method for both text-to-image and image-editing diffusion transformer models. GlyphAnchor enhances the backbone with lightweight glyph patch conditions whose positions are anchored to the target image through the model's native positional encoding. We train this capability with staged supervised finetuning and further refine it with text-aware post-training to improve robustness. We also introduce InfoTextBench, a benchmark for evaluating text-rich visual text rendering in both generation and editing settings. Experiments across multiple backbones and benchmarks, including long, complex, and densely arranged text and rare character scenarios, show that GlyphAnchor consistently improves text fidelity while preserving overall image quality.
### Title:
          MultiGhostBench: A Multilingual Benchmark for Long-Form LLM-Generated Text Attribution under Distribution Shifts
 - **Authors:** Matteo Greco, Anudeex Shetty, Andrea Tagarelli, Jey Han Lau
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Computers and Society (cs.CY); Digital Libraries (cs.DL); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While existing work on LLM authorship attribution (AA) has made progress, available benchmarks remain limited, often focusing on English, controlled settings, or relatively outdated models, with the few multilingual studies considering only relatively short texts. We introduce MultiGhostBench, a multilingual benchmark comprising 928 books generated by five recent LLMs across six languages and three scripts, with an average length of approximately 59K words per book. The benchmark supports evaluation under domain, author, and language shifts. Evaluation of representative AA methods shows that no single method consistently performs best across settings, and performance generally degrades under distribution shifts. Transformer-based detectors can retain generator-related information across languages, although transfer effectiveness varies by language pair, whereas statistical and fingerprint-based detectors are more language-dependent. We envision MultiGhostBench as a valuable resource for the development and evaluation of robust AA methods. The dataset and code can be found at this https URL.
### Title:
          Uncertainty-Guided Adverse Weather Restoration via Gated Transformer Network
 - **Authors:** Zheke Jin, Yuning Cui, Tianle Jin, Alois Knoll, Hu Cao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Restoring images degraded by adverse weather remains challenging due to spatially heterogeneous degradations. Many existing weather-specific restoration models rely on weather-agnostic global aggregation, naive cross-scale fusion, and deterministic objectives, which struggle to handle heterogeneous degradations in all-in-one adverse-weather settings. To address these limitations, we propose an Uncertainty-guided Adverse-weather Restoration Network (UAR-Net), a weather-specific AiO framework that integrates a gated transformer with balanced multi-scale skip connections. Specifically, we employ Gated Dual-scale Transformer Blocks (GDTB) to jointly model selective global interactions and multi-scale local structures, a progressive Balanced Multi-scale Skip Connection (BMSC) for balanced multi-scale feature integration, and an Uncertainty-Aware Refinement Head (URH) that performs artifact removal, detail enhancement, and predictive uncertainty estimation. The model is supervised by a Brightness-Aware Energy Loss (BAE-Loss) to encourage accurate reconstruction with well-calibrated uncertainty. Extensive experiments demonstrate that our method achieves state-of-the-art performance across multiple adverse-weather benchmarks. The codes will open source upon acceptance.
### Title:
          When Decodability Is Not Enough: Logical Validity Representations, Behavioral Dissociation, and Causal Tests in Language Models
 - **Authors:** Smitha Muthya Sudheendra, Jaideep Srivastava
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models can look capable of logical reasoning, but correct or incorrect answers alone tell us little about what the model represents internally. We study logical verification in five open-weight transformer models using matched valid--invalid premise--claim pairs that vary across inference families, semantic domains, templates, and difficulty levels. Despite near-chance behavioral performance, logical validity is often almost perfectly decodable from hidden states and remains strongly decodable under held-out templates, domains, and inference families. Validity also remains highly decodable on behaviorally incorrect examples in the conditions where correctness-conditioned evaluation is well defined. At the same time, exhaustive leave-one-out tests reveal clear limits to this generalization, and interventions along probe-derived validity directions have only weak, nonspecific effects compared with random controls. Our results suggest that representing validity, expressing it in behavior, and using it causally are distinct. Validity related information can be strongly decodable from a model's hidden states without being reliably expressed in its output.
### Title:
          UnCapsTSR: An Unsupervised Transformer-based Image Super-Resolution Approach for Capsule Endoscopy Images
 - **Authors:** Anjali Sarvaiya, Shubh Kawa, Lalit Agrawal, Jagrit Joshi, Kishor Upla, Kiran Raja
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Wireless Capsule Endoscopy (WCE) captures and streams video while passing through a patient's Gastrointestinal (GI) tract and is used to examine its irregularities. Although advantageous over conventional endoscopy, WCE suffers from limitations related to capsule size and wireless transmission, resulting in images with coarser resolution. This work presents UnCapsTSR, an unsupervised transformer-based Generative Adversarial Network (GAN) framework for improving the spatial resolution of Low-Resolution (LR) WCE images. The proposed method accomplishes SR without explicit degradation estimation of real-world LR data and eliminates the need for true LR-HR pairs. UnCapsTSR employs a Bilateral Total Variation (BTV) loss to ensure spatial continuity in SR images. A newly curated dataset from the Kvasir Capsule dataset is also presented for training WCE SR models. Generalizability is validated on KID and GIANA datasets that are not used during training. A new non-reference metric, Endoscopy Quality Metric (EndoQM), is introduced for quantitative evaluation of domain-specific WCE data. Experiments demonstrate consistent improvement over state-of-the-art unsupervised SR approaches using NIQE, BRISQUE, PIQE, and EndoQM. Statistical evaluation shows 40 to 80 percent improvement in EndoQM from LR to SR across the evaluated datasets.
### Title:
          LightBridge: Feed-Forward Generative Relighting for 3D Gaussian Splatting
 - **Authors:** Hezhi Cao, Panhao Cheng, huangsheng du, Qibiao Li, Youcheng Cai, Ligang Liu
 - **Subjects:** Subjects:
Graphics (cs.GR); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian Splatting (3DGS) achieves high-quality, real-time novel view synthesis, but the resulting assets have baked-in illumination and cannot be easily relit. Inverse rendering methods optimize simplified reflectance and illumination models for each scene, limiting efficiency and relighting quality. Recent generative approaches leverage large diffusion models for realistic lighting edits, but applying them to 3DGS typically requires an additional per-scene optimization stage to bake the edited appearance into the representation. We present LightBridge, a feed-forward generative framework for controllable relighting of complete 3DGS assets in a single pass. To enable feed-forward training, we construct a large-scale Multi-Illumination Relighting Dataset with paired source and target observations of the same scenes. Latent Bridge Relighting Diffusion models relighting as source-to-target transport in latent space, enabling one-step extraction of 2D visual tokens without iterative diffusion sampling. A Gaussian Propagation Transformer uses a point transformer with sparse image-to-point self-attention followed by point-to-image cross-attention to efficiently propagate these cues across the complete 3DGS, while avoiding full attention over all image and Gaussian tokens. Experiments validate these designs, demonstrating competitive relighting quality and efficient single-pass prediction of complete relit 3DGS assets without scene-specific optimization. The code and dataset will be made publicly available upon acceptance.
### Title:
          oHC: Orthogonal Hyper-Connections on SO(4) via Quaternions
 - **Authors:** Haoqiang Guo, Xuyi Chen, Bo Ke, Yishu Lei, Ziyang Xu, Shikun Feng, Ximen, Wenhan Luo
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hyper-Connections (HC) replace the single residual stream of a Transformer with $n$ parallel ones, mixing them at every layer with a learned $n \times n$ residual matrix. Leaving that matrix unconstrained places no limit on the factor by which the mixing step rescales the residual streams, and that factor compounds across layers, which destabilizes training. Manifold-constrained Hyper-Connections (mHC) address this by restricting the matrix to the doubly stochastic matrices. That caps the factor at one, so the mixing can no longer amplify any direction, but nothing bounds it from below. We prove that inside this set the mixing step can reduce the norm of the residual streams only by shrinking the differences between the streams, while their mean is left unchanged; and since the reduction accumulates over layers, the streams grow more alike and their diversity is spent with depth. We therefore propose Orthogonal Hyper-Connections (oHC), restricting the residual matrix to the rotation group $SO(n)$, so that the mixing step can neither amplify nor attenuate the residual streams in any direction, which keeps training stable and no longer forces the differences between the streams to contract. Specifically, at the four streams used by recent HC models we parameterize the group in closed form by a pair of unit quaternions, which adds no parameters, replaces the iterative projection with a fixed pattern of signed additions, and can be constructed faster than mHC. We evaluate oHC across a comprehensive set of downstream tasks, where it outperforms the single-stream residual baseline, mHC and iHC, which fixes the residual matrix to the identity.
### Title:
          GaLe: memory-efficient Global Approximate and Local Exact features
 - **Authors:** Alberto Ancilotto, Elisabetta Farella
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Embedded devices typically lack the resources of GPU-equipped machines, and existing inference methods suffer from either high computational overhead (patch-based) or accuracy loss (approximation-based). We propose GaLe, a memory-efficient technique that enables the deployment of pretrained networks on constrained devices without retraining. GaLe partitions feature maps into two components: a local exact (Le) representation that preserves fine details and a global approximate (Ga) representation that retains long-range dependencies. Unlike standard tiling, GaLe supports global operations and attention mechanisms found in hybrid CNN-transformer models. Validated on ImageNet, our method matches exact-inference performance while achieving up to 65% speedup and 90% RAM reduction on a Cortex-M33 compared to patch-based inference. We further demonstrate GaLe's versatility across classification, detection, and generation tasks, highlighting its potential as a foundation for resource-efficient architecture design.
### Title:
          Trace as State: Reasoning Traces as Conditional States for Long-Context Transformers
 - **Authors:** Xu Zou, Jie Tang
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers process information causally, but long-context reasoning may depend on task state discovered only later. We formalize this mismatch through conditional state update tasks. For causal state update processors, providing the condition first can require exponentially less memory in the worst case than providing it last. Motivated by this principle, we introduce Trace as State. We use collected reasoning traces as a textual proxy for task state and place it before the long-context block on a fresh pass, allowing information derived previously to guide rereading. We conduct extensive experiments on Trace as State and Trace Append, a matched control that uses the same task state proxy but put it after the context. Across three models and three long-context datasets, Trace as State outperforms Trace Append in 26 of 27 reported combinations of model, task, and metric. On GraphWalks Parents, exact match lifts DeepSeek V4 Pro Preview from 29.2% on the initial pass and 43.0% with Trace Appendto 81.8% with Trace as State, and from 66.4% and 83.2% to 100.0% for GLM-5.2. These results show that placing traces before the context can improve long-context reasoning while retaining the causal transformer structure.
### Title:
          Efficient All-in-One Weather Restoration using Spectral Harmonization
 - **Authors:** Paula Garrido-Mellado, Daniel Feijoo, Yuning Cui, Alvaro Garcia, Marcos V. Conde
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adverse weather conditions such as rain, haze, and snow significantly degrade image quality, posing challenges for both human perception and physical AI. Existing restoration methods require large computational budgets, struggling to process high-resolution images and handle different degradations. In this paper, we present Frequency Reconstruction via Spectral Harmonization, a novel lightweight all-in-one restoration method that explicitly decomposes feature representations into high- and low-frequency components at each scale of a hierarchical encoder-decoder architecture. By combining spectral decomposition with spatial processing through Fourier-based skip connections, FReSH-IR captures complementary frequency information without sacrificing spatial detail. Our approach achieves similar restoration quality with 80% fewer parameters and operations than transformer-based models. Extensive experiments demonstrate that our method offers a great efficiency-performance trade-off, highlighting its practical applications in constrained-resource systems.
### Title:
          UE5M3 FP4 Block Scaling for Stable Language Model Pretraining
 - **Authors:** Robert Hu, Carlo Luschi, Paul Balanca
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Stable 4-bit floating-point (FP4) pretraining is difficult because the E2M1 payload represents only a narrow range of magnitudes. NVIDIA's Transformer Engine \nv{} recipe addresses this with current-tensor scaling, a randomized Hadamard transform (RHT), and bfloat16 (BF16) final layers, adding work outside the FP4 matrix multiplications. We instead pair E2M1 payloads with unsigned E5M3 (\ue{}) block scales. Their wider range permits periodic tensor scaling, while our recipe applies selective stochastic rounding to backward gradients, omits RHT, and uses FP4 in all eligible internal linears. We pretrain a Nemotron-H 8B model for nearly 190 billion tokens. Compared with Transformer Engine \nv{}, the proposed block-16 recipe finishes with lower final-window training loss and, under their respective quantized-inference policies, lower validation loss measured as held-out negative log-likelihood. Its quantized-inference downstream point estimates are also higher on all three reported aggregates. A native \nv{} execution ablation that jointly removes RHT and the BF16 final-block exemption increases measured model-body token throughput by 21.2\%. These results demonstrate end-to-end software-emulated \uefp{} pretraining with a simpler recipe and motivate native support for \ue{} block scaling.
### Title:
          Towards Trustworthy Autonomous Robots: An Explainable AI-Based Decision Framework
 - **Authors:** Cagri Temel
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous robots powered by deep learning face a fundamental auditability challenge: when incidents occur, investigators cannot reconstruct why the system made specific decisions. This paper presents TRACE (Transparent Reasoning Architecture for Credible Execution), a decision framework that ensures every autonomous action can be traced back to sensor evidence through documented causal chains. The framework organizes decision-making into four auditable layers: Semantic Perception for evidence-grounded entity recognition, Belief Reasoning for probabilistic state estimation with causal graphs, Action Synthesis for constraint-aware planning with counterfactual documentation, and Execution Verification for compliance monitoring. TRACE is model-agnostic yet designed to integrate learning-based perception modules (CNNs, transformers) while preserving decision-level auditability. We evaluate the framework using three objective metrics: Evidence Traceability (sensor-to-decision linkage), Decision Reconstructability (post-hoc analysis capability), and Temporal Continuity (audit trail completeness). Experimental evaluation on warehouse robot navigation demonstrates that TRACE achieves 98.6% evidence traceability, 99.0% temporal continuity, and 98.1% decision reconstructability across 500 simulated decision cycles. Post-hoc methods like LIME provide feature attributions but lack the artifact structure needed for decision-level reconstruction. The framework addresses EU AI Act requirements for high-risk system transparency and contributes to Explainable AI for safety-critical autonomous systems.
### Title:
          Graph Machine: Towards Better Pretraining via Edges
 - **Authors:** Lintai Hou
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce the Graph Machine (GM), an architecture that maintains an $O(n)$-sized state and accesses it through sparse, dynamic routing. Unlike methods with fixed-size states or sparse but static routing, GM preserves $O(n)$ complexity in its sparse layers without restricting the potentially accessible state size to $O(1)$. Instead, GM uses edges - pointer-like objects updated differentiably by a referral mechanism resembling pointer chasing. We replace 75% of the dense Transformer layers in Qwen3-0.6B with GM sparse layers and pretrain from scratch on 15.7B tokens. With only 2 of 4,096 tokens retrieved per KV head in each sparse layer, loss degrades only slightly; with 4, the best model marginally improves loss.
## Keyword: autonomous driving
### Title:
          DiDrive: A Risk-Aware Hierarchical Diffusion Framework for Safe Offline Reinforcement Learning in Autonomous Driving
 - **Authors:** Qisong Guo, Jingtang Chen, Zhilin Chen, Pei Xu, Mingjian Fu, Wenxi Liu, Yuanlong Yu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While diffusion models effectively capture multimodal behavioral priors for autonomous driving, offline reinforcement learning (RL) policies remain susceptible to distribution shift, heavy-tailed risk signals, out-of-distribution (OOD) action generation, and high-dimensional state redundancy. To address these challenges, we propose DiDrive, a distribution-guided offline diffusion framework featuring two synergistic components: the Risk-Aware Hierarchical Diffusion (RHDif) architecture and the 3DICE policy optimization paradigm. In the state space, RHDif utilizes a low-level risk-gated encoder and a high-level contextual modulator to filter environmental redundancy and focus on safety-critical threats. In the action space, 3DICE mitigates OOD overestimation and gradient oscillation through in-sample calibrated guidance, spatiotemporal optimization, and ensemble-based candidate ranking. Evaluations on the CARLA benchmark demonstrate DiDrive's superiority over baselines like IQL, CQL, and Diffusion-QL, particularly in complex, high-density traffic scenarios with 60 vehicles, where it achieves an 85% success rate and a 4295.68 average reward, providing a robust pathway for safe autonomous driving decision-making.
### Title:
          Beyond Textual Chain-of-Thought: A Survey on Action-Grounded Reasoning in Autonomous Driving
 - **Authors:** Zhengxu Tang, Xiaozhou Zhang, Guofeng Cui, Ziyu Gong, Zi Wang, Yunfei Shi, Ruifeng Deng, Chengzhi Qi, Ke Chen, Sachin Patil, Tianjun Xiao, Langechuan Liu, Pichao Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Chain-of-thought (CoT) reasoning powers generative models by eliciting intermediate steps before producing an answer. In autonomous driving, the answer is a continuous action. Thus its reasoning must share the same spatiotemporal structure as the physical world. This survey studies the resulting shift from textual CoT to action-grounded reasoning. Surveying 171 papers, including 130 method papers and 41 benchmarks, datasets, surveys, and analysis papers, we propose a representation-centered taxonomy that treats the form of the intermediate state as the organizing axis. We systematize the 130 methods into four categories: language-based, visual-spatial, latent-dynamic, and externalized reasoning, further divided into 13 subtypes tied to distinct regions of interests. Our synthesis shows that the open frontier of reasoning in driving agents lies in intermediate representations that can be grounded in the real world, coupled to real-time action, and verified under safety-critical systems. Project page: this https URL.
### Title:
          TAPVid-MV: A Benchmark for Tracking Any Point in 3D Across Multiple Views
 - **Authors:** Skanda Koppula, Frano Rajic, Abdullah Faiz Ur Rahman, Yi Yang, Ignacio Rocco, Jeet Thakwani, Rishabh Kabra, Andrew Zisserman, Joao Carreira, Siyu Tang, Carl Doersch, Gabriel Brostow
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-camera systems are increasingly practical for robotics, AR/VR, and autonomous driving because complementary views reduce depth ambiguity and preserve visibility under occlusion. Existing point-tracking benchmarks, however, focus on a single video or static multi-camera rigs. None test long-term 3D point tracking across several synchronized views under camera motion. We introduce TAPVid-MV (Tracking Any Point in Video across Multiple Views), the first benchmark for this setting. It contains a curated set of 284 sequences, 1,142 calibrated camera streams, and 109,769 point tracks across seven subsets spanning indoor and outdoor domains, from robotics and human activity to driving and synthetic procedural scenes. We obtain these trajectories using dataset-specific auxiliary modalities: sensor depth, LiDAR, SLAM and SfM points, human meshes, posed object meshes, and simulation. Every sequence and trajectory is visually verified by human annotators. Across more than 30 baselines, no method comes close to solving the task. Surprisingly, existing multi-view point trackers do not consistently outperform monocular point trackers. By evaluating reconstruction and point tracking on the same datasets, TAPVid-MV helps distinguish errors in recovered geometry from errors in point correspondence. Through this joint analysis, we identify geometry recovery as a major bottleneck for accurate 3D point tracking. Beyond multi-view 3D point tracking, our released annotations support monocular 2D and 3D point tracking, future-trajectory prediction, and 4D reconstruction.
### Title:
          DiffuSearch: How Hybrid Trajectory Planning Benefits from Aligned Objectives in Diffusion and Action Space
 - **Authors:** Steffen Hagedorn, Aron Distelzweig, Alexandru P. Condurache
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In trajectory planning for autonomous driving, hybrid planning architectures are often realized as a collection of disparate modules, each with its own objectives. This lack of a unifying principle can lead to inconsistencies between the initial and refined trajectory, resulting in suboptimal behavior. We address this by introducing DiffuSearch, a novel hybrid planner that uses a unified set of objectives across generation and refinement. Our model encourages all components to follow the same shared driving goals: collision avoidance, drivable area compliance, comfort, and progress. DiffuSearch employs a two-stage architecture. First, a guided diffusion model generates a scene-consistent, joint trajectory prediction, using our driving objectives as differentiable guidance functions to implicitly steer the denoising process. Second, a Monte Carlo Tree Search (MCTS) in a discretized action space performs an explicit, local refinement of this proposal, leveraging the same driving objectives as its reward function. This synergistic design leverages the diffusion model's strength in finding scene-consistent solutions combined with the explainable, constraint-aware refinement of MCTS. Experiments on nuPlan and interPlan reactive closed-loop benchmarks demonstrate that DiffuSearch achieves strong and often state-of-the-art performance, substantially reducing collisions and improving comfort, particularly in complex, interactive scenarios. Our ablation studies indicate that MCTS refinement is the main mechanism behind the gains, while sharing objectives between implicit guidance and explicit search provides further consistent improvements.
### Title:
          CrashDiffuser: VLM-Guided Collision Intent Reasoning for Fine-Grained Safety-Critical Traffic Scenario Generation
 - **Authors:** Shucheng Zhang, Yuang Zhang, Bingzhang Wang, Muhammad Monjurul Karim, Kehua Chen, Yinhai Wang
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generating safety-critical scenarios is essential for evaluating autonomous driving systems. However, existing generators primarily focus on inducing collisions and offer limited control over where contact occurs on the target vehicle. In this paper, we study fine-grained safety-critical scenario generation, where success requires both a target collision and a specified head, rear, or side contact region. We propose CrashDiffuser, a closed-loop VLM-guided diffusion framework that decouples semantic collision reasoning from continuous trajectory synthesis through a hierarchical collision-intent interface derived from the requested target contact region. At initialization, the VLM extracts reusable scene-level context; at each replanning step, it predicts a structured action tuple describing speed change, turning behavior, and collision stage. This intent conditions a diffusion model to generate executable adversarial trajectories, while collision-guided sampling, candidate selection, and short-horizon replanning adapt generation to the target vehicle's evolving behavior. On WOMD-derived closed-loop scenarios, CrashDiffuser achieves a target-collision rate of 50.33% in a single attempt and 67.98% after three attempts, together with a contact-region control success rate of 40.05% and competitive trajectory naturalness. Component ablations further support the proposed design.
### Title:
          Towards Zero-Shot Transfer Across Embodiments For Driving VLAs
 - **Authors:** Caio Azevedo, Stefano Sabatini, Sascha Hornauer, Fabien Moutarde
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action models (VLAs) have shown strong potential in autonomous driving by leveraging multimodal pretraining for instruction following, visual reasoning, and scene-level generalization. In robotic manipulation, scaling VLA fine-tuning across multiple robot setups--especially when unifying representations across embodiments--has been shown to improve in-dataset performance and cross-embodiment generalization; in autonomous driving, however, VLAs remain largely trained on individual datasets and are rarely evaluated for zero-shot transfer to unseen datasets and camera rigs; furthermore naively adding more datasets to the training data does not necessarily lead to better performance within seen embodiments. To address these problems, we study multi-dataset training for the driving task and BEV-Forcing, an auxiliary objective that transfers ground-plane object-layout information from a specialized Bird's-Eye-View model into the VLA backbone. By encouraging the model to represent object position through a shared BEV spatial interface, we show that an auxiliary task such as BEV-Forcing can improve both in-distribution and out-of-distribution performance when training on a small number of camera rigs. As the number of training embodiments increases, however, the benefits of the auxiliary task are reduced; we present this as evidence that new techniques in the literature may see their benefits diminish when simply scaling up training diversity, which motivates presenting results taking into account data scaling.
### Title:
          VIPS: Vehicle-Infrastructure Cooperative Planning Benchmark via Pseudo-Simulation
 - **Authors:** Hoonhee Cho, Jae-Young Kang, Giwon Lee, Hyemin Yang, Heejun Park, Kuk-Jin Yoon
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end autonomous driving in urban environments requires robust decision-making under partial observability and complex multi-agent interactions. Severe occlusions and dense traffic at intersections limit the perception capability of single-agent systems, motivating recent efforts on Vehicle-to-Infrastructure (V2I) cooperation for perception and planning. However, existing evaluation protocols face a fundamental trade-off: open-loop evaluation fails to capture error accumulation and recovery from deviations, while closed-loop evaluation is costly, difficult to scale, and often relies on simulated environments that may suffer from domain gaps. To bridge this gap, we propose VIPS, a benchmark for cooperative autonomous driving in V2I settings based on pseudo-simulation. VIPS extends pseudo-simulation by integrating vehicle and infrastructure observations. This enables scalable yet realistic evaluation of robustness and error propagation without full simulation. We further present CoS-V2X, a cooperative planning framework based on sparse representations. CoS-V2X models vehicle-infrastructure interactions using compact features for efficient communication and robust decision-making under heterogeneous observations. Code and dataset are available at this https URL.
### Title:
          ShallowStream: Index Shallow then Answer Deep for Streaming Video Understanding
 - **Authors:** Jitai Hao, Ke Yang, Qiang Huang, Jun Yu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Streaming video understanding is a critical capability for real-world applications, including embodied intelligence, autonomous driving, industrial monitoring, surveillance and early warning, and wearable assistants. However, processing continuous video streams with multimodal large language models (MLLMs) is computationally expensive. Existing efforts have explored reducing streaming overhead through visual token pruning, token merging, quantization, on-demand frame retrieval, and context offloading. However, most existing methods overlook the dimension of model depth. Repeatedly executing full-depth MLLM prefill over incoming frames is prohibitively expensive, incurring substantial computational overhead and causing the KV cache to grow at a rate directly proportional to the prefill depth. To address these challenges, we propose ShallowStream, a novel framework that leverages the shallow layers of an MLLM to simultaneously perform frame encoding and retrieval index building. During stream processing, ShallowStream maintains an always-on lightweight index using the KV cache of shallow layers. During query-time answering, we leverage the attention scores generated by the shallow layers to score context frames and employ a diversity-aware selection strategy to retrieve precise and comprehensive evidence. ShallowStream achieves performance on par with the strongest existing streaming methods, while reducing per-frame prefill latency and 10-second end-to-end latency by up to 52.1x and 11.9x, respectively. Our code is available at this https URL.
### Title:
          Toward Robust LiDAR Semantic Segmentation for Real-World Deployment: Evaluation under Coarse Labels, Adverse Conditions, and Domain Shifts
 - **Authors:** Samir Abou Haidar, Alexandre Chariot, Mehdi Darouich, Cyril Joly, Jean-Emmanuel Deschaud
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR-based semantic segmentation is a core perception module for autonomous vehicles and mobile robots. Despite the strong performance of recent state-of-the-art methods on standard benchmarks, existing evaluation protocols remain focused on clean, single-domain settings and fine-grained label taxonomies, leaving deployment readiness largely unassessed. Real-world systems must handle safety-critical label semantics, degraded sensing conditions, and cross-domain variability, yet no unified protocol currently addresses all three aspects together. In this paper, we propose a structured evaluation protocol that assesses the deployment readiness of LiDAR semantic segmentation models along three complementary dimensions: (i) coarse-label evaluation aligned with autonomous driving safety priorities, revealing how label granularity affects different methods; (ii) robustness under eight types of LiDAR corruptions designed to emulate real-world atmospheric, geometric, and sensor degradations; and (iii) domain generalization across datasets without adaptation. The evaluation includes inference speed measured on an embedded Jetson AGX Orin platform, directly reflecting deployment constraints. Our results show that fine-grained benchmark rankings do not always reflect safety-relevant performance, that all methods experience substantial degradation under corruptions with architecture-dependent robustness characteristics, and that current domain generalization remains insufficient for reliable deployment. These findings expose concrete gaps between benchmark performance and deployment readiness, and provide a reference protocol for more practically grounded evaluation of LiDAR semantic segmentation.
