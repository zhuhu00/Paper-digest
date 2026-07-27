# Showing new listings for Monday, 27 July 2026
## Keyword: SLAM
### Title:
          Mag4D-SLAM Dataset: A Repeated-Traversal Multi-Modal 4D Geomagnetic Dataset for Localization and Mapping
 - **Authors:** Bibhutibhusan Nayak, Hyoseok Ju, Giseop Kim
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Geomagnetic sensing offers an infrastructure-free, absolute orientation reference that is robust to GNSS denial and visual degradation, yet no large-scale outdoor robotics dataset supports its systematic study in SLAM. Existing magnetic datasets are confined to small-scale indoor environments and lack the synchronized multi-modal sensing, repeated-traversal structure, and high-precision 6-DoF ground truth required for geomagnetic SLAM research. We present Mag4D-SLAM, the first large-scale outdoor geomagnetic SLAM dataset. It comprises 14 sequences totaling over 18 km of synchronized LiDAR, camera, IMU, tri-axis magnetometer, and GNSS measurements with SE(3) ground-truth poses, collected along structured campus trajectories under paired day/night conditions in both forward and reverse directions. Through repeated-traversal experiments, we analyze three core properties: magnetic field repeatability across different recording sessions (daytime and nighttime), drift-free global heading estimation, and location-discriminative magnetic signatures for cross-session place recognition. Mag4D-SLAM is designed to support research on yaw drift mitigation, magnetic loop closure, and long-term localization and to open new research questions on how geomagnetic sensing can complement visual and LiDAR modalities or provide a fallback cue under illumination changes, structural repetition, and GNSS-denied long-term operation.
## Keyword: odometry
### Title:
          ACME: A Multi-Cultural, Multi-Embodiment Social-Navigation Dataset
 - **Authors:** Shashank Rao Marpally, Allan Wang, Atharva Ghotavadekar, Renato Alexandre Ribeiro, Nhat Le, Pilar Bachiller-Burgos, Pranav Goyal, Subham Agrawal, Yasuhiro Nitta, Howard Ziyu Han, Daeun Song, Masaki Kuribayashi, Kohei Uehara, Xiyue Wang, Yangzhe Kong, Duc M. Nguyen, Amirreza Payandeh, Gerardo Pérez-González, Alejandro Torrejón-Harto, Jeeho Ahn, Tisha Jain, Andrew Stratton, Elvin Yang, Jorge de Heuvel, Nico Ostermann-Myrau, Sai Anudeep Sajja, Mithilya Raj, Daisuke Sato, Gaston Rouquette, Nikolas Martelaro, Maki Sugimoto, Hironobu Takagi, Chieko Asakawa, Maren Bennewitz, Aaron Steinfeld, Xuesu Xiao, Christoforos Mavrogiannis, Harold Soh
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding how robots and humans move in shared spaces is essential for designing effective social robot navigation policies and predicting human behavior. However, existing datasets often lack the diversity needed to capture differences in culture, geography, and human-robot interaction-factors that strongly shape appropriate social behavior. To address this gap, we introduce ACME: A Cross-cultural, Multi-Embodiment dataset for social navigation. A large-scale data collection effort across 8 sites in 5 countries, using 7 robot embodiments, ACME is a large and diverse multi-modal dataset aimed at advancing social navigation research, providing 29.35 hours of onboard robot data and 43.5 hours of overhead pedestrian tracking data. Unlike prior datasets, it focuses on capturing goal-driven social navigation behavior in complex social scenarios with explicit robot-crowd interaction through robot speech. To facilitate learning navigation policies and predicting pedestrian trajectories, ACME provides 3D and 2D scene features, odometry, interaction information, and human-annotated pedestrian trajectory labels. We make ACME easy to use by providing both human-readable data for each sensor modality as well as raw binary data. Our qualitative and quantitative analyses show that our dataset captures more challenging scenarios and a broader distribution of pedestrian behavior than previous datasets.
### Title:
          DB-VIO: Dual-Branch Visual Inertial Odometry with Enhanced Visual-Inertial Representation
 - **Authors:** Ziyu Wan, Lin Zhao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual inertial odometry (VIO) is essential for accurate 6-DoF motion estimation in mobile robotic systems. Recent learning-based VIO methods have shown promising progress, but they often rely on unified visual--inertial representations and a single temporal model for full-pose estimation, limiting their ability to capture the heterogeneous dynamics of rotation and translation. Moreover, monocular visual features often lack explicit geometric structure, while raw inertial encoding leaves the underlying rotational kinematics implicit, weakening the rotation-related cues in IMU features. To address these issues, we propose DB-VIO, a dual-branch visual inertial odometry framework with enhanced visual--inertial representation. DB-VIO incorporates depth cues to improve monocular visual perception, injects an explicit integrated-attitude prior to strengthen rotation-aware inertial representation, and decouples pose estimation into dedicated rotational and translational branches for motion-specific temporal modeling. Experiments on autonomous driving and aerial robot benchmarks show that DB-VIO achieves state-of-the-art performance, improving the corresponding baselines by 20\% on KITTI and 33\% on EuRoC. Notably, under the more agile motion patterns of EuRoC, DB-VIO improves the rotational metric by 65.7\% over prior methods. These results demonstrate the effectiveness and generalization of DB-VIO across different platforms and motion scenarios.
### Title:
          Flight-Ready LiDAR-Inertial Odometry for Embedded Drone Platforms
 - **Authors:** Alvaro J. Gaona, David Perez-Saura, Francisco J. Anguita, Pascual Campoy
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open-source LiDAR-inertial odometry (LIO) systems have achieved remarkable benchmark accuracy, yet current state-of-the-art implementations are primarily optimized for evaluation performance rather than the requirements of real-time closed-loop aerial control. When deployed onboard UAVs, this can introduce limitations that degrade flight performance. In this work, we identify five architectural deficiencies in a representative tightly coupled IESKF-based LIO implementation: odometry publishing tied to the LiDAR rate (10 Hz instead of the IMU's 200 Hz), missing velocity outputs, execution bottlenecks that block IMU processing, mutex contention, and synchronization race conditions. We introduce corresponding modifications including IMU-rate forward propagation, direct body-frame velocity publishing, SLERP-based smoothing, dual-executor isolation, and explicit synchronization protection. The resulting system increases odometry output from ~10 Hz to a stable 200 Hz, provides a complete Twist state at every IMU sample, and preserves continuity during transient LiDAR loss. Experiments on a Livox Mid-360 / Pixhawk 4 Mini autonomous UAV with motion-capture ground truth validate the approach. Since the underlying estimator (IESKF + ikd-Tree) remains unchanged, the proposed improvements can be directly applied to FAST-LIO2-derived implementations.
## Keyword: livox
### Title:
          Flight-Ready LiDAR-Inertial Odometry for Embedded Drone Platforms
 - **Authors:** Alvaro J. Gaona, David Perez-Saura, Francisco J. Anguita, Pascual Campoy
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open-source LiDAR-inertial odometry (LIO) systems have achieved remarkable benchmark accuracy, yet current state-of-the-art implementations are primarily optimized for evaluation performance rather than the requirements of real-time closed-loop aerial control. When deployed onboard UAVs, this can introduce limitations that degrade flight performance. In this work, we identify five architectural deficiencies in a representative tightly coupled IESKF-based LIO implementation: odometry publishing tied to the LiDAR rate (10 Hz instead of the IMU's 200 Hz), missing velocity outputs, execution bottlenecks that block IMU processing, mutex contention, and synchronization race conditions. We introduce corresponding modifications including IMU-rate forward propagation, direct body-frame velocity publishing, SLERP-based smoothing, dual-executor isolation, and explicit synchronization protection. The resulting system increases odometry output from ~10 Hz to a stable 200 Hz, provides a complete Twist state at every IMU sample, and preserves continuity during transient LiDAR loss. Experiments on a Livox Mid-360 / Pixhawk 4 Mini autonomous UAV with motion-capture ground truth validate the approach. Since the underlying estimator (IESKF + ikd-Tree) remains unchanged, the proposed improvements can be directly applied to FAST-LIO2-derived implementations.
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Mag4D-SLAM Dataset: A Repeated-Traversal Multi-Modal 4D Geomagnetic Dataset for Localization and Mapping
 - **Authors:** Bibhutibhusan Nayak, Hyoseok Ju, Giseop Kim
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Geomagnetic sensing offers an infrastructure-free, absolute orientation reference that is robust to GNSS denial and visual degradation, yet no large-scale outdoor robotics dataset supports its systematic study in SLAM. Existing magnetic datasets are confined to small-scale indoor environments and lack the synchronized multi-modal sensing, repeated-traversal structure, and high-precision 6-DoF ground truth required for geomagnetic SLAM research. We present Mag4D-SLAM, the first large-scale outdoor geomagnetic SLAM dataset. It comprises 14 sequences totaling over 18 km of synchronized LiDAR, camera, IMU, tri-axis magnetometer, and GNSS measurements with SE(3) ground-truth poses, collected along structured campus trajectories under paired day/night conditions in both forward and reverse directions. Through repeated-traversal experiments, we analyze three core properties: magnetic field repeatability across different recording sessions (daytime and nighttime), drift-free global heading estimation, and location-discriminative magnetic signatures for cross-session place recognition. Mag4D-SLAM is designed to support research on yaw drift mitigation, magnetic loop closure, and long-term localization and to open new research questions on how geomagnetic sensing can complement visual and LiDAR modalities or provide a fallback cue under illumination changes, structural repetition, and GNSS-denied long-term operation.
### Title:
          CommandLM: Data driven behavior level descriptor for ego vehicles
 - **Authors:** Boris Tokic, Constantin Selzer, Fabian B. Flohr
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As autonomous driving systems move toward real-world deployment, interpretable, behavior-level decision-making is essential for safety, trust, and regulation. We introduce CommandLM, a multimodal large language model that generates concise, human-readable behavior descriptions for ego vehicles from fused multi-sensor data. Our model processes temporally fused bird's-eye view representations from LiDAR and multi-camera inputs via a Q-Former adapter connected to a quantized, LoRA-fine-tuned large language model. Trained on our CommandLM-nuScenes dataset, CommandLM produces intent-aware, interpretable captions suitable for planner supervision and safety auditing. Experiments demonstrate strong linguistic and behavioral alignment, achieving CIDEr 0.67, and BERT-F1 0.88, substantially outperforming the BLIP-2 baseline (CIDEr 0.52, BERT-F1 0.86). In human evaluation, 58% of the generated descriptions were rated accurate, efficient and rule-compliant, confirming their real-world plausibility. While the remaining descriptions may not always select the most efficient, goal-oriented behavior, CommandLM's interpretable outputs enable downstream validation systems to identify and correct such cases, making it an effective tool for transparent behavior auditing. These results show that integrating multimodal fusion with language reasoning yields efficient and transparent behavior-level understanding for autonomous driving. We release our code and dataset at: this https URL
### Title:
          Flight-Ready LiDAR-Inertial Odometry for Embedded Drone Platforms
 - **Authors:** Alvaro J. Gaona, David Perez-Saura, Francisco J. Anguita, Pascual Campoy
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open-source LiDAR-inertial odometry (LIO) systems have achieved remarkable benchmark accuracy, yet current state-of-the-art implementations are primarily optimized for evaluation performance rather than the requirements of real-time closed-loop aerial control. When deployed onboard UAVs, this can introduce limitations that degrade flight performance. In this work, we identify five architectural deficiencies in a representative tightly coupled IESKF-based LIO implementation: odometry publishing tied to the LiDAR rate (10 Hz instead of the IMU's 200 Hz), missing velocity outputs, execution bottlenecks that block IMU processing, mutex contention, and synchronization race conditions. We introduce corresponding modifications including IMU-rate forward propagation, direct body-frame velocity publishing, SLERP-based smoothing, dual-executor isolation, and explicit synchronization protection. The resulting system increases odometry output from ~10 Hz to a stable 200 Hz, provides a complete Twist state at every IMU sample, and preserves continuity during transient LiDAR loss. Experiments on a Livox Mid-360 / Pixhawk 4 Mini autonomous UAV with motion-capture ground truth validate the approach. Since the underlying estimator (IESKF + ikd-Tree) remains unchanged, the proposed improvements can be directly applied to FAST-LIO2-derived implementations.
### Title:
          Visual Relocalization from Sparse Views in Aliased and Low-Texture Environments via Novel View Synthesis
 - **Authors:** Maria Peribañez, Javier Civera, Rudolph Triebel, Riccardo Giubilato
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual localization becomes extremely challenging in planetary-like terrains characterized by low texture, perceptual aliasing, harsh illumination, and sparse, weakly overlapping viewpoints induced by forward rover motion and unconstrained driving directions. Under these conditions, state-of-the-art image-to-image and image-to-map matching pipelines suffer significant performance degradation. In this work, we propose a visual relocalization method that departs from classical correspondence-based pipelines by directly estimating camera poses against a differentiable map representation built with 3D Gaussian Splatting (3DGS). Our key contribution is a geometry-aware training strategy that combines photometric and geometric losses, where the geometric supervision is provided for the first time by combining multi-view stereo (MVS) and LiDAR depths. We show that this joint optimization produces a 3DGS model that better fits the underlying scene geometry, leading to improved photometric and geometric consistency and more robust, accurate single-image 6-DoF pose estimation. Extensive experiments on data acquired in planetary-analog environments validate the effectiveness of our approach, showing substantial gains in relocalization accuracy under challenging conditions. Code is available at this https URL.
### Title:
          JustDepth: Real-Time Radar-Camera Depth Estimation with Single-Scan LiDAR Supervision
 - **Authors:** Wooyung Yun, Dongwook Kim, Soomok Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate yet low-latency depth is essential for radar-camera perception in autonomous systems. Cameras provide rich appearance but lack metric scale, whereas automotive radar offers metric range but is sparse and noisy. Many pipelines are multi-stage or depend on auxiliary annotations, increasing latency and limiting portability. We introduce JustDepth, a single-stage radar-camera depth estimator trained only with radar, camera, and single-scan LiDAR. All radar returns are aggregated into a fixed-width 1D representation, decoupling runtime from point count. A Height Fusion Block fuses modalities, a lightweight GNN propagates depth globally, and a training-only confidence decoder stabilizes learning with zero test-time cost. We mitigate stripe artifacts via simple augmentations and quantify them using the Vertical-Horizontal Gradient Ratio (VHGR). On nuScenes, compared to recent state-of-the-art methods, JustDepth maintains accuracy while reducing inference time by 39.7x and stripe artifacts by 66% as measured by VHGR.
### Title:
          Offline Vision-Language Navigation with Geometric Goal Localization for Outdoor Environments
 - **Authors:** Ali Salmasi, Xianjia Yu, Tomi Westerlund
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Foundation-model-based vision-language navigation (VLN) has advanced autonomous robot navigation by enabling robots to interpret natural-language instructions, identify semantic goals, and follow user-specified behavioral rules. However, existing VLN systems rely heavily on cloud-hosted foundation models for language understanding and semantic grounding, limiting their applicability where network connectivity is unavailable and reliable metric goal localization is required. Although recent small language models (SLMs) enable fully onboard inference, their suitability for navigation instruction decomposition has not been systematically evaluated. This paper makes three contributions toward fully onboard VLN for outdoor environments. First, we present the first systematic benchmark of 17 edge-deployable SLMs against 4 online APIs for robotic navigation instruction decomposition, evaluating accuracy and latency on human-annotated instructions across three computing platforms and providing practical guidance for selecting onboard language models. Second, we propose a lightweight hybrid semantic-geometric goal localization framework that combines open-vocabulary object detection, prompted segmentation, and LiDAR geometry to estimate metric goals, while maintaining visual bearing guidance when reliable geometric observations are unavailable. Third, we integrate these advances into Edge-BehAV, a fully onboard extension of the BehAV architecture that enables cloud-independent behavior-guided navigation. Experimental results show that the best offline SLM matches the instruction decomposition performance of the strongest cloud API while running approximately 9x faster and without network connectivity. The proposed goal localization framework reduces mean goal-distance error from 2.05 m to 0.20 m at lower computational cost, and the complete system succeeds in 31 of 32 closed-loop outdoor trials.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          SiPhy: Single-Image Physical Property Reasoning
 - **Authors:** Hoang Le, Joonwoo Kwon, Elkhan Ismayilzada, Yufei Zhang, Zijun Cui
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Inferring physical properties such as mass, stiffness, and elasticity from a single image is essential for simulation and embodied AI, yet most existing approaches rely on multi-view reconstruction or physics-based supervision. We introduce SiPhy, a unified framework for single-image physical property reasoning that aligns 3D-aware visual cues, depth with language-based material knowledge. From one RGB image, SiPhy samples pseudo-voxel points, extracts CLIP features, and grounds them to material candidates proposed by a VLM. A part-based contrastive aggregator enforces region consistency, while a heaviness-aware refinement improves thickness and volume estimation for dense objects. Across ABO-500, MVImgNet-100, and PhysXNet-100, SiPhy achieves state-of-the-art single-image performance, surpassing multi-view reconstruction methods by improving mass MnRE by up to 93% (vs. PUGS), reducing density MAE by 35.5% (vs. NeRF2Physics), and lowering Young's modulus error by 23.5%. We further validate SiPhy on real hand-object interaction datasets, demonstrating its potential as a data annotation engine for physical understanding from single-view imagery.
## Keyword: mapping
### Title:
          From Obligation to Specification: A Survey on Validating EU AI Act Requirements in RE
 - **Authors:** T.Y. Emmy Lai, Sven Giesselbach, Matthias Koch, Héctor Allende-Cid
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the EU AI Act entering into force, organizations developing or operating AI systems face new obligations on transparency, risk management, and traceability. For Requirements Engineering (RE), these obligations must be translated into testable, auditable requirements and verifiable evidence. However, many organizations currently lack systematic processes to achieve this. We hypothesize that LLM-based agentic validation tools can support this translation, thereby helping to close this gap. We present a mixed-method exploratory study with expert interviews (N=10) and an online survey (N=15) to assess organizational preparedness for EU AI Act-oriented RE and perceptions of LLM-based, agentic closed-loop validation tools, with participants spanning RE, data science, development, and compliance roles. Our results show that, although the EU AI Act is viewed as highly relevant, structured mechanisms to capture regulatory obligations, propagate updates into projects, and maintain lifecycle-wide traceability and evidence are often missing. Participants see LLM-based tools as promising for mapping obligations to requirements, assessing coverage, and organizing evidence, but express strong concerns about full automation and stress the need for safeguards. Based on these findings, we outline minimum requirements for an EU AI Act-ready closed-loop approach.
### Title:
          Vibe Coding in Software Development: A Multivocal Literature Review
 - **Authors:** Shahbaz Siddeeq, Muhammad Waseem, Kai-Kristian Kemell, Mika Saari, Jussi Rasku, Pekka Abrahamsson
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vibe coding is a software development practice in which developers state intent in natural language and large language models generate code. It is often framed as one-shot prompting, but the evidence describes an intent-driven, iterative workflow whose outcomes depend on how generated code is evaluated and governed. Knowledge of how vibe coding is defined, practiced, and governed is scattered across academic and practitioner sources, and, to our knowledge, existing reviews have not yet integrated both evidence streams. We conducted a multivocal literature review of peer-reviewed and grey literature following established guidelines. Searches spanned 2022 to October 2025. After screening, credibility assessment, and snowballing, 47 sources were retained (28 peer-reviewed and 19 grey) and analyzed through descriptive mapping and thematic synthesis across eight research questions. Vibe coding is consistently described as an iterative generation-evaluation-revision loop rather than a one-shot activity, and developer work shifts from writing code towards specification, supervision, and validation. Short-term productivity and time-to-prototype gains are reported in 21 of 47 sources (45%), while evidence on maintainability, long-term quality, and safeguard effectiveness remains limited. Evidence is strongest for prototyping and user-interface work and weakest for production, data-intensive, and safety-critical use, and tool visibility does not imply effectiveness. This is one of the first reviews to integrate peer-reviewed and grey literature on vibe coding under a single documented protocol. Future work should evaluate safeguard effectiveness, study session-level dynamics and long-term maintainability, and test vibe coding in production, data-intensive, and safety-critical settings.
### Title:
          Farmland Extent and Visible Boundary Mapping from 1 m NAIP Imagery Using Residual U-Net and Text-Prompted SAM 3 Refinement
 - **Authors:** Mohammadreza Narimani, Vikram Anand, Parastoo Farajpoor
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Agricultural field maps are often proprietary, incomplete, or outdated, yet they provide the spatial framework for crop monitoring, production accounting, and land-conversion analysis. This study presents a reproducible workflow for mapping farmland extent and visible boundaries from 1 m NAIP RGB imagery. Thirty-seven scenes spanning open cropland, peri-urban interfaces, semi-arid irrigation geometries, and fragmented mosaics were annotated in CVAT and converted to binary masks. Non-overlapping 256 x 256 patches yielded 5,698 samples, split by source scene into 3,850 training, 770 validation, and 1,078 test patches. A residual U-Net (ResUNet) trained with a Dice-dominant loss, L = 2.5(1 - Dice) + BCE, achieved test accuracy 0.8808, IoU 0.8605, Dice 0.9234, precision 0.8766, and recall 0.9794. A frozen SAM 3 branch prompted with "agricultural farmland field" was fused with ResUNet by logical OR. On selected difficult patches, Dice improved from 0.858 to 0.955 (orchard rows) and from 0.804 to 0.903 (fragmented parcels). Sliding-window stitching produced coherent regional masks (example tile Dice 0.898 and 0.919). The product is a semantic farmland-extent layer, not a cadastral parcel map, and supports agricultural monitoring where current field layers are unavailable.
### Title:
          PIML-OFEM: A New Large-Scale Structural Analysis Method Based on Problem-Independent Machine Learning and Overlapping Finite Element Technique
 - **Authors:** Yilin Guo, Chang Liu, Zongliang Du, Jin Liu, Jingyu Feng, Xinyang Zhang, Yang Li, Tianxing Yang, Changyu Shen, Xu Guo
 - **Subjects:** Subjects:
Numerical Analysis (math.NA); Computational Physics (physics.comp-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-resolution analysis and design of large-scale heterogeneous structures require accurate reduced-order models and efficient online computation. Existing multiscale methods must repeatedly construct local basis functions for different material distributions, whereas substructure-based problem-independent machine learning (PIML) methods can be limited by prescribed boundary displacement interpolation. We propose PIML-OFEM, an overlapping finite element method accelerated by problem-independent machine learning. Each substructure retains only its corner-node degrees of freedom. Oversampled numerical basis functions are constructed by solving local elasticity problems on extended domains and restricting the solutions to the target substructure, eliminating prescribed displacement interpolation on its boundary. Independently constructed local bases are blended through a partition-of-unity overlapping formulation to obtain a globally continuous displacement field. A U-Net learns the mapping from local Young's modulus distributions to numerical basis functions, replacing repeated online local solves and allowing the model to be reused across load cases and global boundary conditions. Numerical examples show close agreement with fine-scale finite element results in displacement and elemental strain energy. PIML-OFEM reduces online computational cost relative to direct finite element analysis and improves accuracy over PIML substructure models based on linear boundary interpolation. In topology optimization, the method supports stable high-resolution iterations with small filter radii and preserves fine-scale features, including local patterns resembling rank-2 microstructures. The framework provides an efficient physics-data approach for large-scale heterogeneous structural analysis and high-resolution topology optimization.
### Title:
          Transforming Keystroke Noise to Text: Self-Supervised Acoustic Eavesdropping Attacks on Keyboards
 - **Authors:** Atsunori Okada, Akira Ito, Rei Ueno, Yuichi Hayashi, Naofumi Homma
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a self-supervised acoustic eavesdropping attack that reconstructs typed text solely from keystroke sounds, without requiring labeled data for the target device. The proposed attack enables stealthy eavesdropping in two real-world scenarios-physical spaces (public and semi-public) and online meetings. Our method combines unsupervised acoustic clustering with Transformer-based language model inference and iterative self-training, enabling stable character inference under highly uncertain acoustic-to-character mappings. We demonstrate that the proposed method achieves over 99% reconstruction accuracy with only 100-150 observed keystrokes under a close-proximity recording setup using a smartphone placed near the target device, significantly outperforming prior unsupervised baselines in low-data regimes. We further evaluate robustness across multiple laptop platforms and in realistic acquisition channels, including distance recording from approximately 3 meters away on the same desk, through-the-wall eavesdropping with a contact microphone, and background keyboard noise in online conferencing systems. Across these scenarios, the proposed method achieves high reconstruction accuracy (often exceeding 90%) with approximately 150-250 observed keystrokes. These results indicate that accurate text reconstruction from keystroke sounds is feasible in practice under an audio-only setting, even with limited observed keystrokes and without requiring device-specific labeled data, highlighting a realistic and previously underestimated privacy risk.
### Title:
          MEUSLI: a Multilingual Projector for LLM-based ASR and Beyond
 - **Authors:** Lorenzo Concina, Seraphina Fong, Marco Matassoni, Alessio Brutti
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Lightweight projectors are an established way to connect pre-trained speech encoders with large language models (LLMs), mapping acoustic features into token-level embeddings for tasks like ASR and spoken question answering. Existing systems, however, typically only support a few languages and are often limited to English. We introduce MEUSLI, the first open-science multilingual projector family that links a Whisper encoder with open-source multilingual LLMs, enabling fully open-source end-to-end ASR in 28 European languages. MEUSLI extends prior monolingual pipelines, delivering strong results across high- and low-resource languages. Using proper continual leaning techniques, MEUSLI can be easily extended to other languages not seen in training. We further demonstrate that the MEUSLI projector can be leveraged beyond ASR, enabling multilingual speech translation and topic identification with only a few hours of task specific supervision per language. Overall, MEUSLI provides a solid foundation for multilingual speech understanding tasks, supporting scalable and inclu- sive open-source SpeechLLM
### Title:
          Latent PDE mapping for efficient physics-informed learning across geometries with limited data
 - **Authors:** Ingvild Askim Adde, Mary M. Maleckar, Gabriel Balaban
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computational Physics (physics.comp-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this study, we introduce latent PDE mapping, a broadly applicable physics-informed learning technique designed to enable efficient geometric generalization with sparse training data. Latent PDE mapping pulls back geometry-specific PDE residuals and boundary conditions to a predefined latent geometry via the deformation gradient, thereby enabling the automated calculation of geometry-consistent shape gradients that are missing in conventional physics-informed machine learning formulations. We demonstrate the utility of latent PDE mapping in solving the anisotropic Aliev-Panfilov PDE of cardiac electrophysiology using both physics-informed neural networks and physics-informed deep operator networks. The Aliev-Panfilov PDE serves as a challenging exemplar: a nonlinear, time-dependent PDE benchmark with sharp gradients that are expensive to capture using traditional numerical solvers. To represent the limited data regime, we train the networks using just fifteen geometric samples drawn from parameterized distributions in two and three spatial dimensions. While modest improvements appear for geometries parameterized by affine and shear deformations, latent PDE mapping demonstrates significant benefits on select geometric families, achieving a factor ~4-6 reduction in mean relative L2 error. Furthermore, our results show that the computational cost of applying latent PDE mapping was modest during network training, and negligible at inference. Taken together, our study highlights how latent PDE mapping facilitates the creation of generalizable physics-informed machine learning models from limited sets of training geometries.
### Title:
          Agentic CPU-GPU Scheduling for Heterogeneous AI Workloads
 - **Authors:** Tianxi Lu, Sherief Reda
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Agentic AI systems compose heterogeneous tool workloads on shared GPU/CPU infrastructure, yet existing frameworks assign all GPU-capable tools to the GPU by default. We profile 19 AI tools across GPU and CPU and find that 11 are GPU-preferred, 4 are ambiguous, 1 is CPU-preferred due to PCIe transfer dominance, and 3 are device-neutral, establishing that blanket GPU-first scheduling is suboptimal. We formulate device scheduling as assigning each tool to one of three options: immediate GPU execution, queued GPU execution, or CPU offload, under a VRAM budget, and identify two runtime factors that cause end-to-end latency to diverge from static profiles: GPU utilization contention and VRAM capacity contention. We present an agentic scheduler that pairs an LLM agent with an algorithmic runtime monitor, where the monitor expands what the LLM can observe via running averages, symmetric reprobing, swap reprobing, and exploration hints, without ever prescribing which mapping to adopt. Across 13 scenarios spanning serial execution, parallel contention, and memory-constrained execution, the agentic scheduler reaches the brute-force optimal mapping in all 13 scenarios, matching the best classical baseline on mapping accuracy while avoiding bandit-style exploration over complete mappings, and outperforming HEFT, StarPU, and the all-GPU policy while requiring zero offline training.
### Title:
          Agentic Root Cause Analysis through Evidence-Grounded Reasoning
 - **Authors:** Amaury Wei, Olga Fink
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diagnosing the root cause of anomalies is essential for safe industrial operation. Despite extensive sensor instrumentation, formulating hypotheses and gathering evidence remains a manual process, creating a major operational bottleneck. While existing data-driven approaches aim to automate this, two critical limitations restrict their deployment: their operate as black boxes unable to justify their diagnosis, and they require scarce labeled examples of faulty operation. To address this gap, we introduce AgentRCA, a zero-shot agentic framework for evidence-grounded root cause analysis. Rather than learning fault-specific mappings, AgentRCA performs inference-time reasoning by combining a data-driven digital twin (modeling normal system dynamics) with a tool-augmented large language model. The agent iteratively gathers statistical evidence, evaluates competing hypotheses, and identifies the physical fault that best explains the observed behavior. Evaluated on a real-world multiphase-flow facility and a large-scale chemical plant, AgentRCA achieves diagnostic performance competitive with fully supervised baselines without relying on fault-specific training. Crucially, it produces transparent reasoning traces that explicitly link observed symptoms to their underlying physical causes. These results establish autonomous hypothesis-driven reasoning as a practical foundation for scalable industrial root cause analysis.
### Title:
          LunarFM: A Shared Multimodal Representation of the Moon's Surface
 - **Authors:** Marc Girona-Mata, Jakob Gawlikowski, Sumit Goski, Gautier Bardi de Fourtou, Valentin T. Bickel, Ben Moseley, Abigail Calzada-Diaz, Sylvester Kaczmarek, Raúl Ramos-Pollán
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The renewed global focus on lunar exploration, driven by the prospect of in-situ resource utilization and a sustained human presence on the Moon, has created growing demand for accurate, large-scale characterization of the lunar surface. Although vast quantities of orbital remote-sensing data have been collected, scientific analysis and resource mapping remain fragmented by heterogeneous multiinstrument observations, sparse labels, and bespoke task-specific modelling workflows. Here we introduce LunarFM, a multimodal foundation model that learns a general representation of the lunar surface from diverse orbital measurements. LunarFM assimilates observations from six instruments across three lunar missions, mapping 18 input channels to a shared embedding space. We demonstrate that this embedding space supports a diverse range of downstream applications, including similarity search, few-shot resource mapping, mineral abundance regression, and geological unit classification, enabling efficient scientific investigation and resource-oriented analysis. We provide a machine-learning-ready dataset of co-registered multimodal observations spanning latitudes from 70°S to 70°N, a pretrained multimodal masked autoencoder, and a companion embedding dataset providing a joint 768-dimensional representation of lunar surface properties. All code and data are available at this https URL
### Title:
          Robot Learning to Communicate through Projected Visual Abstractions
 - **Authors:** Danyang Yan, Boyuan Wang, Jiaxun Liu, Boyuan Chen
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Humans routinely communicate through abstractions of their bodies, including shadows, silhouettes, and reflections. Yet robots remain largely confined to expressing themselves through their physical morphology. Enabling robots to communicate through such projected visual abstractions requires reasoning not only about bodily motion but also about how that motion is transformed into an external representation perceived by an observer. Among these abstractions, shadows provide a particularly compelling example because they emerge directly from the robot's embodiment while remaining visually distinct from the body itself. Here, we present a robotic system capable of dynamic shadow expression using a 21-degree-of-freedom dexterous hand with compliant soft skin and a learned shadow self-model. The soft-skinned embodiment reduces light leakage to produce visually continuous silhouettes, while the differentiable self-model learns the mapping between hand configurations and projected shadow appearance through task-agnostic self-exploration. Given a target shadow image or video, the robot optimizes its hand configurations through gradient-based search over 1 the learned self-model and refines the solution through collision-aware simulation to obtain physically feasible motions. For dynamic shadow performance, we further introduce expressive-region objectives, temporal smoothness regularization, and keyframe-based optimization to preserve visually important motion cues while reducing optimization complexity. We demonstrate robotic shadow expression across sign-language gestures, hand-shadow puppetry, and animal motion imitation in both simulation and physical experiments. These results establish a framework for enabling robots to manipulate projected visual abstractions of themselves for communication and visual storytelling.
## Keyword: localization
### Title:
          Output Format x Model Identity: Interaction Effects in Single-Round Coding Agent Performance
 - **Authors:** Yang Yang
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Output format is not a neutral implementation detail -- it can reorder model rankings, amplify or suppress individual model differences, and determine whether a coding agent succeeds or fails. We conducted a controlled single-round experiment with 3 models (DeepSeek V4, Doubao 2.0 Pro, Qwen 3.7 Max) x 3 output formats (full file, JSON Patch, unified diff) x 6 tasks x 20 repetitions, totaling 4,013 runs across 4 open-source projects. Only one project (tqdm) yielded non-zero success rates: dotenv, requests, and jsoup yielded zero successes in 2,551 runs. Our central finding is a format x model interaction with no universally optimal format. Doubao achieves 94% success with JSON Patch (Cohen's h = 1.57, p < 0.001), DeepSeek excels at unified diff (66%, h = 0.63), and Qwen shows a small but significant full-file preference (50%, h = 0.29, p < 0.05). Beyond these headline results, we identify a distinct failure mechanism -- format misuse -- where agents correctly diagnose a problem but execute it with excessive scope, most vividly when a one-line fix is applied as a full-file replacement. We propose a model-specific output strategy, a tool-design principle that constrains format semantics to the agent's own localization step, and release all data and templates for reproducibility. All experimental data are available at this https URL.
### Title:
          VisionPulse: A Virtual Reality System Enabling Accessible Discovery and Navigation for Blind and Low Vision Users
 - **Authors:** Samuel Martin, Pooyan Fazli, Hasti Seifi
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Free exploration is an important aspect of many engaging virtual reality (VR) experiences, yet remains largely inaccessible to blind and low vision (BLV) users due to its reliance on visual feedback. Existing approaches support BLV navigation through prebuilt menus of environment and audio beacons, but offer limited support for free-form discovery. We present VisionPulse, an accessible VR system that enables BLV users to explore virtual environments through natural head and hand movements, combined with auditory, haptic, and text-to-speech feedback. VisionPulse introduces a discovery-driven approach that allows users to progressively uncover regions and objects, alongside navigation support through waypoint guidance and object localization via responsive audio and orientation-based haptics. A study with 12 BLV participants showed a strong preference for VisionPulse's discovery-based exploration and multimodal feedback, without negatively impacting task performance or perceived workload. Our findings underscore the importance of accessible, free-form VR experiences, and contribute insights for inclusive VR design.
### Title:
          Mag4D-SLAM Dataset: A Repeated-Traversal Multi-Modal 4D Geomagnetic Dataset for Localization and Mapping
 - **Authors:** Bibhutibhusan Nayak, Hyoseok Ju, Giseop Kim
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Geomagnetic sensing offers an infrastructure-free, absolute orientation reference that is robust to GNSS denial and visual degradation, yet no large-scale outdoor robotics dataset supports its systematic study in SLAM. Existing magnetic datasets are confined to small-scale indoor environments and lack the synchronized multi-modal sensing, repeated-traversal structure, and high-precision 6-DoF ground truth required for geomagnetic SLAM research. We present Mag4D-SLAM, the first large-scale outdoor geomagnetic SLAM dataset. It comprises 14 sequences totaling over 18 km of synchronized LiDAR, camera, IMU, tri-axis magnetometer, and GNSS measurements with SE(3) ground-truth poses, collected along structured campus trajectories under paired day/night conditions in both forward and reverse directions. Through repeated-traversal experiments, we analyze three core properties: magnetic field repeatability across different recording sessions (daytime and nighttime), drift-free global heading estimation, and location-discriminative magnetic signatures for cross-session place recognition. Mag4D-SLAM is designed to support research on yaw drift mitigation, magnetic loop closure, and long-term localization and to open new research questions on how geomagnetic sensing can complement visual and LiDAR modalities or provide a fallback cue under illumination changes, structural repetition, and GNSS-denied long-term operation.
### Title:
          A Smooth Phase-Separation Model for Weak-Boundary Segmentation of Homogeneous Structures
 - **Authors:** Zihan Li, Jiebao Sun, Fanghui Song, Zhichang Guo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Mathematical Physics (math-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Segmentation of adjacent structures with similar intensity distributions remains a challenging problem in image analysis, particularly when object boundaries are weak or ambiguous. Under such conditions, classical variational models may suffer from degenerated image-driven forces, leading to boundary leakage or undesired merging of neighboring regions. To address these limitations, we propose a smooth phase-separation variational model based on the Cahn--Hilliard equation for weak-boundary segmentation of homogeneous-appearance structures. The proposed framework integrates softmax-based region fitting with Cahn--Hilliard phase-field regularization to maintain interface discrimination under weak image-driven forces. We further introduce a mixed $L^2-H^{-1}$ gradient flow, which preserves higher-order interfacial regularization while allowing adaptive changes of phase masses, establish the continuous energy dissipation law, and prove the existence and uniqueness of weak solutions in the natural solution class. For numerical computation, we develop a stabilized scalar auxiliary variable (SAV) scheme that is linear, FFT-based, and satisfies a modified discrete energy dissipation law. Numerical experiments on synthetic and medical images demonstrate that the proposed method effectively separates adjacent homogeneous structures across weak boundaries and achieves competitive segmentation accuracy and improved boundary localization compared with representative variational, phase-field, and deep learning methods.
### Title:
          Visual Relocalization from Sparse Views in Aliased and Low-Texture Environments via Novel View Synthesis
 - **Authors:** Maria Peribañez, Javier Civera, Rudolph Triebel, Riccardo Giubilato
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual localization becomes extremely challenging in planetary-like terrains characterized by low texture, perceptual aliasing, harsh illumination, and sparse, weakly overlapping viewpoints induced by forward rover motion and unconstrained driving directions. Under these conditions, state-of-the-art image-to-image and image-to-map matching pipelines suffer significant performance degradation. In this work, we propose a visual relocalization method that departs from classical correspondence-based pipelines by directly estimating camera poses against a differentiable map representation built with 3D Gaussian Splatting (3DGS). Our key contribution is a geometry-aware training strategy that combines photometric and geometric losses, where the geometric supervision is provided for the first time by combining multi-view stereo (MVS) and LiDAR depths. We show that this joint optimization produces a 3DGS model that better fits the underlying scene geometry, leading to improved photometric and geometric consistency and more robust, accurate single-image 6-DoF pose estimation. Extensive experiments on data acquired in planetary-analog environments validate the effectiveness of our approach, showing substantial gains in relocalization accuracy under challenging conditions. Code is available at this https URL.
### Title:
          Bowel Obstruction Detection and Localization on Abdominal CT with Deep Learning
 - **Authors:** Moritz Vandenhirtz, Andrea Agostini, Dana Belde, Mélanie Roschewitz, Ismaiel Chikh Bakri, Tilo Niemann, André Euler, Julia E Vogt
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bowel obstruction is a common and potentially life-threatening gastrointestinal condition. In the face of rising diagnostic workloads, the automated diagnosis of bowel obstruction on CT scans supports radiologists by accelerating detection and improving patient outcomes. In this work, we propose a deep learning framework with a multi-task objective that jointly detects bowel obstruction and localizes its transition zone. Additionally, we extend the method with an inherently interpretable classification method that locates the suspected transition point within a slice. It does so by learning a probabilistic selection mask that faithfully bases the classifier's prediction solely on a small image region. The proposed method is evaluated on an internal dataset comprising 1,427 abdominal CTs. Here, the model achieves an obstruction detection test accuracy of 93% and a Hit@10 transition zone localization of 95%. As the first method to reliably localize the transition zone, this marks a significant step towards the automated identification of this critical clinical landmark.
### Title:
          Offline Vision-Language Navigation with Geometric Goal Localization for Outdoor Environments
 - **Authors:** Ali Salmasi, Xianjia Yu, Tomi Westerlund
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Foundation-model-based vision-language navigation (VLN) has advanced autonomous robot navigation by enabling robots to interpret natural-language instructions, identify semantic goals, and follow user-specified behavioral rules. However, existing VLN systems rely heavily on cloud-hosted foundation models for language understanding and semantic grounding, limiting their applicability where network connectivity is unavailable and reliable metric goal localization is required. Although recent small language models (SLMs) enable fully onboard inference, their suitability for navigation instruction decomposition has not been systematically evaluated. This paper makes three contributions toward fully onboard VLN for outdoor environments. First, we present the first systematic benchmark of 17 edge-deployable SLMs against 4 online APIs for robotic navigation instruction decomposition, evaluating accuracy and latency on human-annotated instructions across three computing platforms and providing practical guidance for selecting onboard language models. Second, we propose a lightweight hybrid semantic-geometric goal localization framework that combines open-vocabulary object detection, prompted segmentation, and LiDAR geometry to estimate metric goals, while maintaining visual bearing guidance when reliable geometric observations are unavailable. Third, we integrate these advances into Edge-BehAV, a fully onboard extension of the BehAV architecture that enables cloud-independent behavior-guided navigation. Experimental results show that the best offline SLM matches the instruction decomposition performance of the strongest cloud API while running approximately 9x faster and without network connectivity. The proposed goal localization framework reduces mean goal-distance error from 2.05 m to 0.20 m at lower computational cost, and the complete system succeeds in 31 of 32 closed-loop outdoor trials.
### Title:
          Robust Berrut-Approximated Coded Computing via Discrete Cosine Transforms
 - **Authors:** Rimpi Borah, J. Harshan
 - **Subjects:** Subjects:
Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Coded computing is a reliable and fault-tolerant paradigm for executing large-scale computational tasks over distributed worker nodes. Among existing coded computing frameworks, Berrut Approximated Coded Computing (BACC) enables distributed computation of arbitrary non-polynomial functions through rational interpolation. Although BACC provides provable approximation guarantees and resilience against straggling workers, its robustness against Byzantine workers remains largely unexplored. To fill this research gap, we propose Robust Berrut Approximated Coded Computing (RBACC), which establishes a coding-theoretic framework for BACC by enabling error localization and error correction in the presence of Byzantine workers. In particular, RBACC introduces a new choice of evaluation points that establishes a connection between Berrut interpolation and Discrete Cosine Transform (DCT) codes, thereby enabling error localization and error correction under finite-precision arithmetic. We derive analytical upper bounds on the approximation error of RBACC under multiple operating scenarios, including straggler-only systems and systems with Byzantine workers under finite-precision arithmetic. Building upon this analysis, we formulate several optimization problems for selecting the DCT code dimension and for assigning encoded evaluations to unreliable workers. We show that these are previously unexplored design parameters that can be systematically optimized to improve the reconstruction accuracy. Experimental results demonstrate that the proposed RBACC framework effectively mitigates stragglers and Byzantine workers while offering improved reconstruction accuracy over the baselines.
## Keyword: transformer
### Title:
          The Hard Decision Layer: Evidence for Committed Inference in Transformers
 - **Authors:** Ashwath Vaithinathan Aravindan, Mayank Kejriwal
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We investigate where and how transformer-based language models commit to predictions in multiple-choice question answering. We identify the _Hard Decision Layer_ (HDL), a natural architectural property where answer option rankings stabilize abruptly during inference. Empirical validation across four language models (Qwen, Llama, Granite, Mistral) and four benchmark datasets demonstrates consistent HDL emergence without learned routing policies. We also show that the HDL is invariant to fine-tuning. Our results reveal striking accuracy improvements at the HDL: up to +0.61 (Qwen on CommonsenseQA), after which performance stabilizes. Systematic ablations on label formats and problem complexity confirm the phenomenon is fundamental to model architecture. These findings offer mechanistic insights into transformer inference and suggest opportunities for efficient reasoning and model steering. All code and results required to reproduce this work are available in this https URL
### Title:
          FBLayout: Optimizing Memory Layout for Efficient LLM Finetuning on Mobile GPUs
 - **Authors:** Kahou Tam, Wei Niu, Yu Bao, Xiaomin Ouyang, Chengzhong Xu, Li Li
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Distributed, Parallel, and Cluster Computing (cs.DC); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based models have enabled unprecedented capabilities across language, vision, and multimodal tasks. On-device fine-tuning of transformer models offers a privacy-preserving path to personalized AI, yet remains inefficient on mobile GPUs due to severe memory constraints and frequent layout transformations in attention mechanism during training. Existing mobile training frameworks either use unified layouts for forward and backward passes -- leading to fragmented memory access and poor GPU utilization during backpropagation -- or rely on explicit layout conversions, which introduce significant transformation overhead. To overcome this, we propose FBLayout, a layout-aware framework that co-designs tensor organization with mobile GPU platforms. FBLayout introduces: (1) a unified R-Tile layout for multi-dimensional reductions across forward/backward passes; (2) tile-based index transformation to eliminate physical data movement; and (3) activation-guided layout selection to propagate efficient layouts globally. Evaluations on seven transformer models across different mobile phones (including ARM Mali and Qualcomm Adreno GPUs) show that FBLayout achieves 2.2-5.7x speedup over MNN, TFLite, and TVM, while significantly improving cache efficiency and reducing memory footprint, enabling practical on-device large model fine-tuning.
### Title:
          Ordered Action Tokens for Visuomotor Policy Learning
 - **Authors:** Chaoqi Liu, Yue Zhao, Haonan Chen, Xiaoshen Han, Jiawei Gao, Ehsan Adeli, Yilun Du
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Action tokenization maps continuous robot action chunks to discrete tokens and has become an important interface for modern visuomotor policies. Existing approaches either rely on analytical discretization methods that produce prohibitively long token sequences or learned latent tokenizers that lack structure, limiting their compatibility with downstream policies. In this work, we identify three desiderata for action tokenization - high compression, total decodability, and an ordered token space - and introduce Ordered Action Tokenization (OAT), a learned action tokenizer that satisfies all three. OAT discretizes action chunks into an ordered sequence of tokens using a transformer with registers, finite scalar quantization, and ordering-inducing training mechanisms. By training each token prefix to decode into a valid action chunk, OAT places coarse control information in early tokens and uses later tokens to refine residual detail, yielding an anytime tradeoff between inference cost and action fidelity. We validate OAT in two prevailing uses of action tokens: autoregressive policies that generate tokens for control, and token co-training policies that use token losses to shape the vision-language model context consumed by a flow-based action expert. Across three policy backbones and more than 60 tasks spanning five simulation benchmarks and real-world settings, OAT consistently delivers strong policy performance while offering significantly greater flexibility at inference time.
### Title:
          CARNet Cycle-Conditioned Core Aggregation and Redistribution for Multivariate Time Series Forecasting
 - **Authors:** Awsaf Tausif Adib, Md. Shahria Sarker Shuvo, Md. Estehaar Ahmed Emon, Mustafa Kamal, Fuad Rahman, Shafin Rahman, Nabeel Mohammed
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurately modeling cross-variate dependencies remains a key challenge in multivariate time series forecasting, particularly in the presence of strong periodic patterns. Many existing approaches rely on attention-based mechanisms that incur quadratic complexity and scale poorly with increasing numbers of variates. Recent attention-free aggregation models address this issue through linear-complexity core-based interactions, but they do not explicitly leverage the global periodic structure present in the data. To overcome this limitation, we propose CARNet, a Cycle-Conditioned Core Aggregation and Redistribution framework that integrates global recurrent cycle information into efficient core based interaction modeling via Multihead Core Aggregation. Extensive experiments on multiple real-world multivariate forecasting benchmarks demonstrate that CARNet consistently outperforms strong transformer and non-attention baselines across diverse prediction horizons while preserving linear-complexity modeling of cross-variate dependencies.
### Title:
          Evaluation design conditions the expert-vs-auto MeSH gap: a controlled comparison of bag-of-words and BiomedBERT on the Cohen benchmark
 - **Authors:** Samuel M. Okoe-Mensah
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A systematic review begins with someone reading thousands of abstracts to identify the few that are relevant, and classifiers are used to prioritise that reading. Their inputs are often augmented with Medical Subject Headings (MeSH), assigned either by expert indexers weeks or months after publication or by automatic tools at once. To our knowledge the two have not been compared directly as classifier features, and no previous work has asked whether that comparison's outcome depends on how the classifier is evaluated. Using the Cohen et al. (2006) drug-class benchmark on three topics, we characterise a bag-of-words logistic regression classifier (seven reruns) and BiomedBERT (five seeds), then examine how the Statins result changes under alternative designs. Under the canonical 5-fold full-corpus design, the bag-of-words expert-vs-auto gap on Statins is +0.096 WSS@95%. Matching the corpus size to the smaller topics (n = 803) reduces it to +0.033 (95% bootstrap CI includes zero), and 10-fold cross-validation at full size to +0.021 (CI narrowly excludes zero). Under canonical evaluation BiomedBERT gives +0.020, within sampling noise of the bag-of-words 10-fold result. A power analysis indicates a Statins-sized effect would not have been detectable at the Opioids or ADHD variance, so those nulls are design-limited rather than informative. A representation asymmetry remains: 15.1% of Statins inputs exceed BiomedBERT's 512-token limit when expert MeSH terms are appended, so truncation may contribute to the smaller transformer gap, although this cannot be separated from training volume here. In screening pipelines using transformers or 10-fold bag-of-words, the gap on the topics tested is about 0.02 WSS@95%, with CIs spanning zero on at least one bound. More broadly, benchmark conclusions about feature sources can change substantially under reasonable changes to the evaluation design.
### Title:
          RED-PIM: Reducing Data Movement for Transformers using Processing-in-Memory
 - **Authors:** Zahra Yousefijamarani, Alaa Alameldeen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers are widely used across many domains, including natural language processing, computer vision, web search, and DNA sequence analysis. Given their broad applicability, improving the performance of transformer models is critical. However, the high volume of data movement between processing units and memory during attention operations significantly limits their efficiency. Processing-In-Memory (PIM) mitigates this issue by performing computations directly inside memory. While prior work has proposed PIM-based transformer implementations, they suffer from costly inter-bank communication, and struggle to scale due to the limited capacity of memory banks. As a result, attention-related data must be split across banks, diminishing the potential benefits of PIM. In this work, we propose RED-PIM, an algorithm-architecture co-design that reduces attention latency by minimizing inter-bank data movement from O(N^2) to O(N) and shrinking intermediate attention matrices from N x N to d x d. By reorganizing matrix operations, performing computations locally, and employing an optimized data transfer strategy, RED-PIM significantly reduces computation cost and interconnect traffic. Compared to baseline PIM implementation, RED-PIM achieves inference time reductions ranging from 16.05% to 99.99% (geometric mean of 66.42%), with the largest gains on longer sequences. On real-world datasets, RED-PIM improves performance by 99.60% for long documents and 13.44% for shorter ones, while maintaining or improving accuracy. These results demonstrate RED-PIM's effectiveness for scalable and efficient transformer inference.
### Title:
          Parameter-free Adaptive Sparse Attention via Compression-Based Content Selection
 - **Authors:** Debarshi Kundu, Swaroop Ghosh, Vasant Honavar
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Data-adaptive sparse attention masks substantially outperform fixed patterns (e.g., BigBird and Longformer) and can even exceed dense attention on long sequences. Existing adaptive approaches---including SBM-Transformer, Dynamic Mask Attention, and NSA---typically require additional learnable parameters, custom gradient estimators, or specialized CUDA kernels. We show that classical data compression provides an effective masking signal with \textbf{no additional parameters}. By computing per-block gzip compression ratios, we identify non-redundant content blocks and route long-range attention selectively through them. Intuitively, blocks that gzip cannot compress contain information not predictable from local repetition, making them natural long-range attention targets. Because the compression profile is input-dependent, the resulting sparse mask adapts dynamically to content without learned parameters, auxiliary losses, or custom kernels. On PG-19 byte-level language modeling at 92M parameters with 8K context, our method achieves 1.71 bits-per-byte (BPB), outperforming dense attention (2.89), BigBird (2.34), Longformer (3.21), and a reimplemented SBM-Transformer (3.38)---the only learned-mask baseline---by up to 1.67 BPB while adding no parameters. The advantage grows with sequence length, with the gap over BigBird widening from 0.05 BPB at 4K context to 0.63 BPB at 8K, while convergence is 3.3$\times$ faster.
### Title:
          Risk-Routed Implicit Boundary Refinement for Robust Ultrasound Image Segmentation
 - **Authors:** Jingguo Qu, Xinyang Han, Xiang Wang, Yuqi Yang, Tonghuan Xiao, Sheng Ning, Jing Qin, Ann Dorothy King, Winnie Chiu-Wing Chu, Jing Cai, Michael Ying
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Medical ultrasound (US) image segmentation faces significant challenges due to speckle noise, low-contrast boundaries, acoustic shadowing, and acquisition variation across operators and clinical centers. Although encoder-decoder and transformer-based networks have achieved strong performance, many methods recover boundary details through dense decoders or larger backbones, which may still produce over-smoothed contours or unstable predictions under external distribution shifts. In this article, we propose Risk-routed Implicit Boundary Refinement (RIBR), a compact segmentation framework that uses implicit neural representation as a risk-routed residual correction rather than an unconstrained full-mask predictor. RIBR combines boundary-refinement implicit residuals, risk-routed residual control, and geometry- and speckle-aware boundary regularization to refine uncertain contours while suppressing non-boundary oscillations. Evaluation on nine US datasets covering lymph nodes, breast lesions, thyroid nodules, and prostate shows that RIBR achieves the best overall macro-average and consistently reduces boundary error across grouped and organ-specific comparisons under a compact parameter budget. These findings suggest that controlled implicit residual learning is a practical strategy for resource-constrained and boundary-sensitive US segmentation. Source code is available at this https URL.
### Title:
          Quantifying Political Partisanship for Cross-Platform Analyses
 - **Authors:** Fathima Ameen, Christopher G. Healey
 - **Subjects:** Subjects:
Social and Information Networks (cs.SI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Research on political polarization on social media depends on the ability to reliably measure partisanship in user-generated content. However, existing approaches are typically tailored to platform-specific properties, such as structural affordances or linguistic conventions, which hurts generalizability across platforms. This limitation is increasingly consequential as the social media ecosystem fragments and fringe, alt-tech platforms emerge alongside mainstream ones. We propose a text-based, platform-portable methodology for measuring political partisanship in social media posts, anchored by an external news-credibility signal. Posts are embedded using a transformer-based sentence encoder and clustered into topic groups, which are labeled using the aggregated AllSides media bias scores of cited news outlets. A partisanship axis is then constructed in the embedding space as the difference between centroids of oppositely labeled clusters, and individual posts are scored by projection onto this axis. We apply the method to a corpus of approximately 1.3 million posts collected from Bluesky and Truth Social during the six months preceding the 2024 U.S. presidential election, providing the first cross-platform comparison of partisanship distributions on these two ideologically asymmetric platforms. The resulting partisanship scores correlate significantly with held-out AllSides media bias scores both in-distribution and out-of-distribution on an independent Twitter corpus, and recover within-platform partisan dynamics that platform identity alone cannot explain.
### Title:
          Learning Adaptive Semantic Gaussian Allocation for 3D Occupancy
 - **Authors:** Kanglin Ning, Yiran Zhao, Wenrui Li, Houde Quan, Qifan Li, Xingtao Wang, Xiaopeng Fan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic 3D Gaussians provide a compact representation for 3D semantic occupancy prediction by rendering semantic primitives into a voxel volume under voxel-wise supervision. Recent methods have improved the modeling ability and efficiency of this representation through more flexible primitive shapes, geometry-guided initialization, and progressive densification. However, these advances mainly determine how primitives are represented, initialized, or added, and do not explicitly address how to select the most useful Gaussians when their total number must be limited to control memory and computation. This imbalance creates an allocation bottleneck: redundant Gaussians remain in simple regions, while difficult regions receive insufficient semantic support. We propose the Semantic Gaussian Allocation Transformer (SAGFormer), which uses Gaussian attributes and local geometric-semantic features to score candidates and select a fixed final Gaussian set. Experiments on nuScenes-SurroundOcc and SSCBench-KITTI-360 show that SAGFormer improves occupancy prediction under the evaluated protocols and yields more semantically consistent and better-utilized Gaussian representations. Under similar final counts and raw coverage, it reduces semantic mixing, strengthens class-consistent voxel support, and produces fewer unused Gaussians. The results indicate that explicit capacity allocation is a useful complement to Gaussian refinement for semantic occupancy prediction.
### Title:
          Action-Conditioned World Model for Goal Plane Probe Guidance in Robotic Ultrasound
 - **Authors:** Siqi Fan, Mingcong Chen, Ran Liu, Zixuan Yang, Xiaoyu Fu, Xiaoqing Gao, Yunhui Liu, Hongbin Liu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present an action-conditioned world model framework for goal plane probe guidance in robotic ultrasound, with a focus on neck ultrasound scanning. Autonomous ultrasound tasks often require large numbers of probe-motion trajectories for training, but collecting high-quality demonstrations is labor-intensive and explicit simulators are difficult to build because ultrasound appearance depends on contact, tissue deformation, and view-dependent acoustic artifacts. We address this problem with a two-stage model-based learning pipeline. First, a latent conditional diffusion world model predicts future ultrasound observations from recent context frames, probe motions and temporal offset. Second, a goal-conditioned temporal transformer predicts ordered probe motions and is fine-tuned using rewards from the frozen world model. Experiments on the self-collected dataset show that the world model preserves action-dependent anatomical structure on target-directed scans. In real-world closed loop experiments, the framework achieves success rates of 70.0\% for carotid guidance and 65.0\% for thyroid guidance. These results demonstrate the potential of learned ultrasound dynamics for training goal-directed robotic probe navigation.
### Title:
          Scaling Native Multimodal Pre-Training From Scratch
 - **Authors:** Haoyuan Wu, Aoqi Wu, Hai Wang, Jiajia Wu, Jinxiang Ou, Bei Yu
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Although large language models (LLMs) exhibit remarkable reasoning capabilities, their reliance on text-only pre-training restricts the perception of the multimodal physical world. Native multimodal pre-training avoids this limitation by training models from scratch on multimodal inputs, thereby achieving deep cross-modal integration and mitigating optimization asymmetries inherent to traditional late-fusion architectures. Despite these advantages, the scaling properties of this paradigm remain systematically uncharacterized. To address this gap, we investigate the optimal model size and token count for training a transformer-based vision-language model under a fixed computational budget. We demonstrate that minimal objective loss adheres to a predictable compute law, whereas compute-optimal model sizes and token counts scale as power laws. Notably, language and multimodal objectives manifest distinct scaling behaviors. The language allocation law is largely invariant to the composition of the data, indicating stable language learning regardless of the multimodal data ratio. Conversely, the multimodal allocation law is highly sensitive to this composition. Specifically, text-heavy mixtures become compute-efficient only at larger model scales, shifting the optimal resource allocation toward greater model capacity. Additionally, by modeling the influence of data composition on compute laws and allocation exponents, we derive an efficiency frontier specifying precise configurations of model size, token count, and data mixture. Downstream evaluations further reveal that native multimodal pre-training induces positive cross-modal transfer, thereby enhancing pure-text spatial reasoning and enabling robust multimodal in-context learning. In summary, this empirical research establishes the essential groundwork for predictably scaling multimodal foundation models.
### Title:
          Rethinking Multi-Branch and Cross-Backbone Fusion for Vehicle Re-Identification in the Foundation-Model Era
 - **Authors:** Yu Wang, Hongyu Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-branch architectures and CNN-Transformer fusion have long been regarded as effective ways to improve vehicle re-identification (Re-ID) by combining complementary representations. In this work, we revisit this assumption in the foundation-model era through a comprehensive empirical study. A single DINOv3-pretrained ConvNeXt trained with a tuned recipe achieves 88.19 mAP on VeRi-Wild Small and 77.47 mAP on VeRi-Wild Large using visual cues alone, matching the strongest protocol-verified metadata-dependent multi-branch baseline. Applying training-free re-ranking further improves performance to 92.38 and 83.68 mAP, respectively. Using this strong baseline together with retrieval-level branch diagnostics, we evaluate whether increasing representational diversity still provides measurable gains. Across both benchmarks, concatenating multiple branches built on a shared backbone changes the best single-branch performance by less than one mAP point while increasing the embedding dimension by 4x, and the resulting representation has an effective rank close to the original feature dimension. We further study cross-backbone fusion using an asymmetric frozen-anchor strategy to combine ConvNeXt and Vision Transformer representations. Despite these favorable conditions, Transformer branches consistently remain 13-15 mAP below the ConvNeXt backbone, and paired per-query bootstrap analysis estimates the largest observed fusion gain to be only +0.11 mAP (95% confidence interval). Our results suggest that, under the evaluated setting, improving a single strong foundation-model backbone together with retrieval-stage re-ranking is more effective than increasing architectural complexity through additional branches or heterogeneous backbones. We restrict our conclusions to single-seed training and one family of foundation models and discuss conditions under which these observations may not hold.
### Title:
          Nanbeige4.2-3B: Unlocking Agentic Capabilities in a Compact Mode
 - **Authors:** Nanbeige Lab: Chen Yang, Chengrui Huang, Fufeng Lan, Hanhui Chen, Hao Zhou, Huatong Song, Jiaqi Cao, Jiaying Zhu, Jinlin Niu, Kai Wang, Lisheng Huang, Qiliang Liang, Ran Le, Ruixiang Feng, Shuang Sun, Tao Gu, Tao Zhang, Tianyu Luo, Yang Song, Yun Xing, Yuntao Wen, Ziyao Xu, Zongchao Chen, Zongqiang Li
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Nanbeige4.2-3B, a compact general agentic model with 3B non-embedding parameters. It delivers strong performance across code-agent, office-agent, and complex tool-use tasks while maintaining highly competitive reasoning capabilities in mathematics, coding, and science. Nanbeige4.2-3B is pretrained from scratch on 28T tokens with a Looped Transformer that reuses the layer stack to increase capacity without adding parameters. For SFT data and trajectory construction, we expand the diversity of executable environments, task assets, and agentic scaffolds through real-world deployment and large-scale synthesis. Our RL pipeline applies mixed-mode RLHF over Think and Non-Think responses to improve overall model quality and reduce failure cases, length-controlled reasoning RL to balance accuracy and reasoning efficiency, and agentic RL with outcome and process rewards to stabilize long-horizon training. Extensive evaluations show that Nanbeige4.2-3B outperforms larger models, including Qwen3.5-9B and Gemma4-12B, across diverse agentic benchmarks while remaining competitive on reasoning and alignment tasks. Performance with OpenClaw further supports its use as a compact local personal assistant.
### Title:
          Transforming Keystroke Noise to Text: Self-Supervised Acoustic Eavesdropping Attacks on Keyboards
 - **Authors:** Atsunori Okada, Akira Ito, Rei Ueno, Yuichi Hayashi, Naofumi Homma
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a self-supervised acoustic eavesdropping attack that reconstructs typed text solely from keystroke sounds, without requiring labeled data for the target device. The proposed attack enables stealthy eavesdropping in two real-world scenarios-physical spaces (public and semi-public) and online meetings. Our method combines unsupervised acoustic clustering with Transformer-based language model inference and iterative self-training, enabling stable character inference under highly uncertain acoustic-to-character mappings. We demonstrate that the proposed method achieves over 99% reconstruction accuracy with only 100-150 observed keystrokes under a close-proximity recording setup using a smartphone placed near the target device, significantly outperforming prior unsupervised baselines in low-data regimes. We further evaluate robustness across multiple laptop platforms and in realistic acquisition channels, including distance recording from approximately 3 meters away on the same desk, through-the-wall eavesdropping with a contact microphone, and background keyboard noise in online conferencing systems. Across these scenarios, the proposed method achieves high reconstruction accuracy (often exceeding 90%) with approximately 150-250 observed keystrokes. These results indicate that accurate text reconstruction from keystroke sounds is feasible in practice under an audio-only setting, even with limited observed keystrokes and without requiring device-specific labeled data, highlighting a realistic and previously underestimated privacy risk.
### Title:
          TRaM-VSR: Importance-Aware Token Routing and Merging for One-Step Diffusion Video Super-Resolution
 - **Authors:** Sicheng Gao, Zhuyun Zhou, Yixuan Liu, Tong Shen, Zongwei Wu, Radu Timofte
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video super-resolution (VSR) using large-scale Diffusion Transformer (DiT) priors achieves exceptional perceptual quality but is often impractical due to the quadratic computational cost of processing dense spatio-temporal token sequences. Existing efficiency-oriented methods risk irreversible detail loss and temporal flickering, a vulnerability especially pronounced in one-step diffusion models. To address this, we propose TRaM-VSR, a Token Routing and Merging framework for adaptive token allocation, leveraging both context-aware video priors and network-level priors. First, token importance is estimated by fusing motion-sensitive temporal cues with semantic text similarity, isolating dynamic objects and structural boundaries. Next, this importance is further calibrated and adjusted by an offline planner to guide routing across optimally grouped network blocks. Technically, within each routed group, structurally critical tokens are processed in a high-fidelity local stream, while less informative tokens are aggregated into a compact global stream, both modulated by network depth and aligned with the multigranular nature of diffusion models. Extensive experiments show that TRaM-VSR accelerates inference significantly while preserving state-of-the-art reconstruction quality and robust temporal consistency. The code is available at this https URL.
### Title:
          IFCLoRA: Topology-Aware Rank Allocation for Parameter-Efficient Fine-Tuning
 - **Authors:** Wei Zhang, Xinwu Liu, Yihang Cheng
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Low-Rank Adaptation (LoRA) is a widely used parameter-efficient fine-tuning method for large language models, but its performance depends strongly on how a fixed rank budget is distributed across Transformer modules. Existing adaptive-rank methods usually rely on local gradient statistics collected during training, which introduces extra memory and computation and overlooks task-conditioned global information flow. We propose IFCLoRA, a topology-aware rank allocation method applied before fine-tuning. Using a small calibration set and a frozen pretrained model, IFCLoRA builds a sparse task-conditioned interaction graph whose nodes represent LoRA-compatible modules. It combines a global information-flow topology prior with local gradient sensitivity to compute Information-Flow Centrality scores, which estimate each module's adaptation importance under multi-hop propagation. Ranks are then assigned once under a global budget. Across multiple models, tasks, and low-rank settings, IFCLoRA consistently outperforms LoRA, AdaLoRA, and EVA under matched training configurations and total rank budgets, while retaining training costs comparable to standard LoRA. On mathematical reasoning with LLaMA 3 8B, IFCLoRA improves over LoRA by 1.36 percent at rank 4 and 1.82 percent at rank 8. Further analysis shows task-dependent, non-uniform rank profiles, indicating that global information-flow structure provides an informative and interpretable prior for low-budget parameter-efficient fine-tuning.
### Title:
          Geometric 2D Scene Graph Generation
 - **Authors:** Christoph Jahn, Urs Waldmann, Bastian Goldluecke
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In production processes for consumer products, assembly instructions are essential not only for planning but also for executing the production process. Likewise in robotics, it is crucial for an assembly robot to understand how components fit together and can be assembled. To facilitate these tasks, we contribute a method for constructing scene graphs to represent and characterize assembly relationships between components. Our approach does not rely on semantic data and is capable of handling a very small dataset. To realize this, the output of a Faster R-CNN model is used to create geometric representations, which are then processed by a transformer architecture to generate an adjacency matrix. This matrix serves as input to a Siamese network that uses message passing based on an attentional graph convolutional network (aGCN) architecture to characterize the connections between the components. We validate our method on a study dataset of toy model components which can be assembled into transportation vehicles.
### Title:
          IQ-JEPA: A Joint-Embedding Predictive Architecture with a Hermitian Vision Transformer for Sound Speed and Attenuation Estimation from Ultrasound IQ Data
 - **Authors:** Masashi Sode, Gianmarco Pinton
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Medical Physics (physics.med-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The speed of sound in tissue is a prerequisite for well-focused imaging and has diagnostic value, but recovering it from raw pulse-echo channel data is fundamentally a nonlinear inverse problem. Learned solvers are fast yet label hungry. Simulated sound-speed labels are expensive, while abundant real channel data is unlabeled. We propose IQ-JEPA to exploit both data types. An encoder is pretrained without labels to predict the latent representation of masked in-phase and quadrature (IQ) regions from visible context, then fine-tuned on simulated maps. Sound speed appears in the IQ signal as a phase difference, invariant to the constant phase offset. The encoder is a Hermitian vision transformer that operates on the complex signal directly. Its attention is equivariant to that phase and its conjugate-product feed-forward is invariant to it, so the encoder reads a quantity analogous to the one classical coherence methods use. On 79,293 Fullwave 2.5 simulations at 2.5 MHz, pretraining on the 63,435 unlabeled acquisitions reaches 15.60 m/s at 10,000 labels. This is a roughly threefold gain in label efficiency over supervised training, growing to over fourfold at 1,000 labels. It is about 2.2x below an InversionNet baseline, and 8.71 m/s at full labels. The gain still grows with more unlabeled pretraining data. Our comparisons point to self-supervision as the dominant factor. The same encoder transfers. Its frozen features expose sound speed and attenuation, and cross-distribution pretraining between layered and abdominal phantoms costs little accuracy. We see this as a first step toward a foundation model for quantitative ultrasound.
### Title:
          Indexing: the Beginning and the End
 - **Authors:** Alexander Kozachinskiy, Vicente Opazo, Felipe Urrutia
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study information bottlenecks in modern deep-learning architectures -- RNNs, softmax transformers, linear-attention transformers and state-space models -- through the lens of the indexing primitive. In this primitive, the input consists of $n$ bits and one integer $i$ from $1$ to $n$ called the index, and the output equals the value of the $i$-th bit. We introduce causal complexity for masked architectures. We show that architectures with low causal complexity cannot solve the indexing primitive in any constant number of layers when the index appears at the end of the input. In particular, this limitation applies to low-parameter RNNs, SSMs and masked linear-attention transformers. In contrast, small softmax transformers can solve it in one layer, while non-masked linear-attention transformers can solve it in 2, which separates them from their masked counterparts. In turn, when the index appears at the beginning, we show that small RNNs are capable of solving this task in 1 layer, while all the other architectures require 2. All our impossibility results are unconditional and apply even to models that employ infinite-precision real arithmetic. Moreover, experiments for up to $n=64$ qualitatively align with our theory: configurations with low-parameter theoretical solutions learn the indexing task easily, while configurations that do not admit such theoretical solutions struggle to learn as the sequence length grows.
### Title:
          Interior interpretability with attention rollout: contraction and propagation profiles in Transformers
 - **Authors:** Umberto Biccari, Qian Huang, Enrique Zuazua
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Feature-attribution methods assign scores relating input variables to a model's output, but do not by themselves characterize how explicitly defined interaction operators compose across its intermediate layers. We introduce \emph{interior interpretability}, a propagation-based perspective on internal model organization, and instantiate it for tabular Transformers using attention rollout. We interpret rollout as a row-stochastic operator encoding attention-mediated propagation between feature tokens. By applying classical Doeblin--Dobrushin contraction theory, we show that a rollout operator with a small Dobrushin coefficient is quantitatively close to a rank-one stochastic matrix whose common row is determined by its normalized column sums. This result gives a structural interpretation to the corresponding rollout propagation profile. In Transformers trained for metabolomic age prediction, the measured rollout contraction strengthens with depth. Trained and randomly initialized models also exhibit different propagation profiles, although the present experiments do not establish the predictive relevance of individual rollout-ranked variables. Exploratory comparisons with PCA and GradientExplainer approximations to SHAP reveal localized agreement among highly ranked variables but weak agreement across complete rankings. Attention rollout is therefore used here as a diagnostic of attention-mediated propagation, not as a causal explanation or faithful attribution of the complete Transformer.
### Title:
          StateFormer: A Multivariate Transformer for Learning History-Dependent Battery State Dynamics and Long-Horizon Health Forecasting
 - **Authors:** Zhe Bai, Stephen Harris
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper introduces a novel multivariate Transformer \emph{StateFormer} that forecasts degradation dynamics of large-scale battery systems. The model learns across time scales, from short-term thermal fluctuations to long-term aging trajectories, enabling accurate prediction of battery states including state of charge (SOC), state of health (SOH), or battery temperature. By capturing long-range dependencies and identifying the operating conditions that drive future degradation, the model simultaneously represents fast electrochemical and thermal processes and slow aging mechanisms within a unified framework. \emph{StateFormer} achieves robust and accurate predictions of battery state estimation across both synthetic and real-world datasets. It maintains high predictive performance under additive current/voltage noise levels ranging from $1\%$ to $10\%$ and a wide range of ambient temperatures in a synthetic battery fleet accommodating different types of electrode chemistry and manufacturing, as well as five years of field data collected from residential utility battery systems. The resulting model bridges the laboratory-to-field gap and provides predictive intelligence for maintenance planning, operational optimization, and economic decision-making.
### Title:
          Twins: Learn to Predict Unified Representations with Focal Loss
 - **Authors:** Kaixiong Gong, Xin Cai, Bin Lin, Hao Wang, Yunlong Lin, Mingzhe Zheng, Bohao Li, Jian-Wei Zhang, Miles Yang, Zhao Zhong, Liefeng Bo, Xiangyu Yue
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unified multimodal models seek a shared visual token space that supports both multimodal understanding and image generation. Discrete methods unify the interface via a shared codebook, whereas continuous pipelines often rely on two disparate representations -- semantic features (e.g., ViT) for understanding and low-level latents (e.g., VAE) for synthesis -- resulting in mismatched latent spaces. We propose Twins, a unified continuous token space formed by channel-wise concatenating ViT and VAE features on the same token grid, so the sequence length is unchanged and attention cost does not increase. However, jointly modeling Twins in a Diffusion Transformer exposes a severe optimization imbalance: the model fits the ViT component well but struggles to match the VAE latent distribution. We trace this imbalance to three sources of heterogeneity: frequency bias, intrinsic dimensionality, and condition-aligned vs condition-independent uncertainty. To address it, we adapt a focal regression objective for flow matching that upweights large-error VAE dimensions, better balancing optimization across the ViT and VAE components. On ImageNet, this yields up to 10.57 gFID gain over naive MSE loss without classifier-free guidance. Twins also performs competitively on multimodal understanding benchmarks and improves reconstruction fidelity, narrowing the gap between understanding- and generation-oriented representations.
### Title:
          SM4RT: Learning Structured Motion Geometry for 4D Reconstruction
 - **Authors:** Shing Ho J. Lin, Wenzhao Zheng, Dong Zhuo, Yuqi Wu, Jie Zhou, Jiwen Lu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Geometry Foundation Models (GFMs) have substantially advanced monocular 3D reconstruction, yet extending this capability to 4D dynamic understanding remains a fundamental challenge. Most existing motion perception methods (e.g., sparse tracking, dense point-wise flow) treat motion as independent point-wise displacements, ignoring the structured nature of physical motion. However, real-world objects usually obey rigid-body kinematics, and points thus usually move collectively, not in isolation. Motion itself possesses geometric structure: physical objects undergo a set of rigid-body transformations governed by SE(3), rather than unstructured point-wise displacements. Building on this insight, we propose SM4RT, a Structured Motion 4D Reconstruction Transformer for end-to-end 3D reconstruction and structured motion perception. SM4RT introduces Structure-of-Motion to represent scene dynamics, where scene motion is decomposed into a compact set of motion bases, each represented as a temporal sequence of 6D twists in SE(3). Dense scene motion is then recovered by sparse, time-shared per-pixel assignment weights over these bases, ensuring points on the same object share a common rigid-body motion trajectory. SM4RT introduces a parallel motion geometry encoder and decoder that jointly infer 3D geometry, world-coordinate motion, and scene kinematic structure in a single forward pass from monocular RGB video. SM4RT achieves strong motion reconstruction performance while preserving the geometric structure of scene motion.
## Keyword: autonomous driving
### Title:
          Sparse by Command: Task-Conditional Compute Skipping for Multi-Task Inference Accelerators
 - **Authors:** Afzal Ahmad, Gaoyu Mao, Shoubo Hu, Hui-Ling Zhen, Mingxuan Yuan, Xinyu Chen, Wei Zhang
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-task inference models share a single backbone across diverse tasks, yet execute identical computation regardless of which task is active - wasting energy and cycles on task-irrelevant operations. We observe that the task command, typically available before inference begins, provides a free signal that can be exploited to skip unnecessary computation at the hardware level. We present a HW/SW co-designed approach in which a lightweight gating network, trained jointly with the backbone, predicts per-tile binary execution masks conditioned on the task input. Each tile corresponds to a fixed group of output channels (the native scheduling granularity of the accelerator), enabling masked tiles to be skipped with zero overhead. This yields a task-dependent reduction in compute, where each command activates only the subset of the network it requires, without changes to the model architecture or inference pipeline. We co-design the full system stack: a command-conditioned training procedure that learns hardware-aligned tile masks under a sparsity objective; an instruction set architecture whose instructions carry per-tile bitmask fields, allowing the hardware to skip masked tiles without software intervention; and a tiled inference accelerator with configurable parallelism, double-buffered memory, and INT8 datapath that natively supports sparse tile execution. We prototype on an AMD/Xilinx Alveo U50 FPGA and evaluate on a closed-loop visuomotor driving task in CARLA autonomous driving simulator. Task-conditional sparsity reduces FLOPs by 66-76% while maintaining driving quality. On-device latency decreases by 51-59%, from 9.12 ms to 3.74-4.44 ms (2.1-2.4x speedup), with energy per inference dropping from 263 to 108-128mJ.
### Title:
          CommandLM: Data driven behavior level descriptor for ego vehicles
 - **Authors:** Boris Tokic, Constantin Selzer, Fabian B. Flohr
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As autonomous driving systems move toward real-world deployment, interpretable, behavior-level decision-making is essential for safety, trust, and regulation. We introduce CommandLM, a multimodal large language model that generates concise, human-readable behavior descriptions for ego vehicles from fused multi-sensor data. Our model processes temporally fused bird's-eye view representations from LiDAR and multi-camera inputs via a Q-Former adapter connected to a quantized, LoRA-fine-tuned large language model. Trained on our CommandLM-nuScenes dataset, CommandLM produces intent-aware, interpretable captions suitable for planner supervision and safety auditing. Experiments demonstrate strong linguistic and behavioral alignment, achieving CIDEr 0.67, and BERT-F1 0.88, substantially outperforming the BLIP-2 baseline (CIDEr 0.52, BERT-F1 0.86). In human evaluation, 58% of the generated descriptions were rated accurate, efficient and rule-compliant, confirming their real-world plausibility. While the remaining descriptions may not always select the most efficient, goal-oriented behavior, CommandLM's interpretable outputs enable downstream validation systems to identify and correct such cases, making it an effective tool for transparent behavior auditing. These results show that integrating multimodal fusion with language reasoning yields efficient and transparent behavior-level understanding for autonomous driving. We release our code and dataset at: this https URL
### Title:
          DB-VIO: Dual-Branch Visual Inertial Odometry with Enhanced Visual-Inertial Representation
 - **Authors:** Ziyu Wan, Lin Zhao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual inertial odometry (VIO) is essential for accurate 6-DoF motion estimation in mobile robotic systems. Recent learning-based VIO methods have shown promising progress, but they often rely on unified visual--inertial representations and a single temporal model for full-pose estimation, limiting their ability to capture the heterogeneous dynamics of rotation and translation. Moreover, monocular visual features often lack explicit geometric structure, while raw inertial encoding leaves the underlying rotational kinematics implicit, weakening the rotation-related cues in IMU features. To address these issues, we propose DB-VIO, a dual-branch visual inertial odometry framework with enhanced visual--inertial representation. DB-VIO incorporates depth cues to improve monocular visual perception, injects an explicit integrated-attitude prior to strengthen rotation-aware inertial representation, and decouples pose estimation into dedicated rotational and translational branches for motion-specific temporal modeling. Experiments on autonomous driving and aerial robot benchmarks show that DB-VIO achieves state-of-the-art performance, improving the corresponding baselines by 20\% on KITTI and 33\% on EuRoC. Notably, under the more agile motion patterns of EuRoC, DB-VIO improves the rotational metric by 65.7\% over prior methods. These results demonstrate the effectiveness and generalization of DB-VIO across different platforms and motion scenarios.
### Title:
          CARA: Concept-Aware Risk Attention for Interpretable Collision Anticipation
 - **Authors:** Zhishan Tao, Ruoyu Wang, Yucheng Wu, Enjun Du, Yilei Yuan, Sherwin Ho, Yue Su, Jinbo Su, Yi Hong
 - **Subjects:** Subjects:
Multimedia (cs.MM); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Collision anticipation in autonomous driving requires not only accurate early warnings but also interpretable reasoning about what risk factors are being tracked and how risk evolves over time. Existing methods fall short in this regard: feature-driven models are opaque, post-hoc explanations often lack fidelity, and concept-based methods are mostly designed for static recognition rather than dynamic driving scenes. We propose CARA (Concept-Aware Risk Attention), an intrinsically interpretable spatio-temporal framework for collision anticipation. CARA derives domain-grounded risk concepts from accident narratives, aligns them with video frames via vision-language similarity, and organizes them into evolving concept trajectories. These trajectories provide explicit risk evidence that guides spatial attention, temporal attention, and anticipation, allowing semantic concepts to directly influence both where the model attends and how it predicts risk over time. By treating semantic risk factors as dynamic intermediate evidence rather than auxiliary post-hoc explanations, CARA tightly couples interpretability with the predictive process. Extensive experiments on three benchmarks show that CARA consistently improves anticipation accuracy and warning earliness over strong baselines, while providing sparse and semantically grounded concept evidence.
### Title:
          Explainable Reinforcement Learning for assisting Air Traffic Controllers
 - **Authors:** Anduel Mehmeti, Gabriella Gigante, Salvatore Venticinque
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 To effectively integrate AI into high-stakes, critical environments such as healthcare, autonomous driving, and aviation--and to advance toward higher levels of automation and seamless human-AI collaboration--building trust in AI-driven solutions is essential. Trust, in turn, is closely linked to the explainability of AI systems. The rapid advancements in AI across various domains have underscored the challenges of establishing trust, raising increasing interest in AI explainability even more when applied to deep learning. In this context, the present work aims to explore the application of explainability techniques to Reinforcement Learning (RL) algorithms, specifically within the safety-critical domain of Air Traffic Control (ATC). Using a simplified ATC environment as an initial testbed, an intelligent agent is trained with a reinforcement learning algorithm to make decisions on alternative flight routes that avoid no-fly zones. As a preliminary explainability approach, a saliency map is employed, providing insights into the input features that most significantly influence the agent's decision-making process.
