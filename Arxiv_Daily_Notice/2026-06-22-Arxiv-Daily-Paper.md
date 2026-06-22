# Showing new listings for Friday, 19 June 2026
## Keyword: SLAM
### Title:
          Designing for Interconnected Islamic Learning: A Qualitative Study of Muslim Women's Experiences with Qur'an, Hadith, and Seerah Apps
 - **Authors:** Ishrat Jahan Easha (1 and 2), Nabil Mosharraf Hossain (3), Araf Mohammad Mahbub (3), Fairoze Bint Abu Hassan (3), Zunaid Aslam (3), Yemin Sajid (3), Riasat Islam (3 and 4) ((1) University of Technology Sydney, (2) ZNRF University of Management Sciences, (3) Greentech Apps Foundation, (4) Queen Mary University of London)
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Islamic learning often depends on reading the Qur'an, Hadith, and Seerah together, yet digital tools typically separate these sources across apps, screens, and search pathways. We examine this as a human-computer interaction problem through five semi-structured interviews with Muslim women recruited from an online Islamic learning community. Participants described a recurring tension: they wanted Qur'an-Hadith-Seerah context at the point of reading, but only when contextual expansion remained trustworthy, optional, and did not interrupt reading. Interpreting the interviews through gendered digital religion, epistemic trust, and seamless learning, we identify five themes concerning contextual understanding, authenticity, interface clutter, study modes, and guidance features. We introduce layered contextuality as an HCI account of this domain: contextual expansion must be balanced with interpretive accountability, devotional flow, and continuity across devices and study intensities.
### Title:
          MMD-SLAM: Structure-Enhanced Multi-Meta Gaussian Distribution-Guided Visual SLAM
 - **Authors:** Fan Zhu, Ziyu Chen, Peichen Liu, Yifan Zhao, Zhisong Xu, Hui Zhu, Hongxing Zhou, Sixun Liu, Chunmao Jiang
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian Splatting (3DGS) has significantly boosted novel view synthesis and high-fidelity scene reconstruction, expanding the potential of 3DGS-based Visual Simultaneous Localization and Mapping (SLAM) methods. However, most existing systems fail to fully exploit the underlying structural information, which limits rendering quality and often leads to inconsistent maps. To address these limitations, we propose MMD-SLAM, a structure-enhanced Visual SLAM framework that leverages the Atlanta World (AW) assumption to guide a Multi-Meta Gaussian representation for photorealistic mapping. First, we introduce a point-line fusion strategy for pose optimization, where 3D line segments are incorporated to improve tracking robustness and provide additional constraints for mapping. Second, we design a Multi-Meta Gaussian representation with dominant directions, explicitly encoding structural priors from the AW hypothesis. Finally, we propose a Gaussian evolution strategy that adapts to scene geometry and incorporates structural cues into global optimization. Extensive experiments demonstrate that these innovations enable MMD-SLAM to achieve state-of-the-art performance in both tracking accuracy and mapping quality. e.g., our method achieves a 48.56% reduction in ATE RMSE on ScanNet and a 5.71% improvement in PSNR on Replica, compared with MonoGS.
### Title:
          Towards 3D karst underwater scene reconstruction from rotating sonar data
 - **Authors:** Georgios Evangelos Margaritis, Lionel Lapierre, Simon Rohou, Zhi Yan, Andreas Nüchter, François Goulette
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Karst aquifers provide critical freshwater resources but pose significant hazards due to their complex and poorly understood subsurface geometry. Mapping these environments is challenging because sonar data from underwater exploration is sparse and noisy, while navigation estimates suffer from drift limiting standard 3D reconstruction methods. We present a pipeline for reconstructing underwater karst conduits from a sonar profiler. We combine a continuous-time SLAM approach to correct trajectory drift with a novel two-stage deep learning method for surface reconstruction, producing an immersive and navigable 3D mesh for hydrogeological analysis.
## Keyword: odometry
### Title:
          TIDY: Thermal Infrared Image Denoising via Wavelet Domain Entropy and Directional Stripe Index
 - **Authors:** Tai Hyoung Rhee, Dong-Guw Lee, Ayoung Kim
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Thermal infrared (TIR) imaging has been a popular choice for field robotics due to its robust perception capability under low light visual degradation, but it suffers from severe stochastic and fixed-pattern noise that breaks downstream estimation. This noise is intensified indoors due to low thermal contrast and uniform temperature distributions, contributing to the relative lack of indoor TIR deployments. Existing TIR denoising methods exhibit a poor accuracy-efficiency tradeoff, either too slow for online deployment required in robotics or insufficiently robust to severe degradation, while typically being trained on synthetic noise. Addressing these problems, we propose TIDY, a lightweight wavelet-domain denoiser trained on real clean-noisy TIR data. By reformulating TIR denoising in the wavelet domain, TIDY explicitly disentangles noise from structural content, enabling targeted suppression with reduced spatial complexity, significantly improving inference speed over prior methods (~34Hz). TIDY introduces two new metrics, Wavelet Entropy and Wavelet Directional Stripe Index, as complementary loss terms to explicitly suppress stochastic noise and stripe artifacts. Across severe indoor corruption and zero-shot settings, TIDY improves robustness and yields consistent gains in downstream robotics tasks including thermal inertial odometry and monocular depth estimation. Code and dataset is available at: this https URL
### Title:
          Gaussian Process Prior Variational Autoencoder for Endoscopic Videos
 - **Authors:** Ivan De Boi, Xinxing Shi, Xiaoyu Jiang, Tim J.M. Jaspers, Francisco Caetano, Mauricio A. Alvarez, Fons van der Sommen, Sam Van der Jeught
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Endoscopic video analysis is essential for gastrointestinal diagnosis and computer-assisted interventions, but video sequences are routinely degraded by specular reflections, motion artifacts, and missing frames. These transient corruptions can distract clinicians, reduce image interpretability, and disrupt downstream tasks such as 3D reconstruction and navigation. Effective restoration therefore requires methods that exploit temporal continuity rather than treating frames in isolation. We introduce a Gaussian Process Prior Variational Autoencoder (GPVAE) framework for endoscopic video restoration that replaces the standard factorized latent prior with a temporal Gaussian process prior, enabling interpolation of missing frames with uncertainty-aware reconstruction. The framework combines endoscopy-specific encoders, including a convolutional EndoVAE backbone and pretrained Vision Transformer encoders from GastroNet-5M, with two scalable GP approximations: Hierarchical Prior Approximation (HPA) and Sparse Precision Approximation (SPA). Specular reflections are handled using a DUCKNet-based masking pipeline that excludes corrupted pixels from the reconstruction objective. On the C3VDv2 colonoscopy dataset, the best GPVAE variants reduced image reconstruction RMSE by 21.9\% on average, and by up to 26.1\%, relative to matched VAE baselines. Downstream trajectory RMSE was reduced by 12.7\% on average across classical visual odometry and a pretrained PoseNet, at an average increase of 27.3\% in training time per epoch. Finally, the GP posterior provides per-frame uncertainty estimates that reflect temporal support and offer a confidence signal for restored frames.
### Title:
          Motor Angular Speed Preintegration for Multirotor UAV State Estimation
 - **Authors:** Matěj Petrlík, Filip Novák, Robert Pěnička, Martin Saska
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A precise state estimate is crucial for a tight feedback control that enables agile and near-obstacle flights of UAVs. The state-of-the-art methods fuse slow pose measurements with high-frequency inertial measurements to obtain a precise state estimate. However, the inertial measurements from the IMU onboard the UAV are degraded by vibrations from spinning propellers and the precision of the estimated state suffers. We propose a novel approach based on the preintegration of accelerations obtained from motor speeds. We show that the accelerations obtained in this manner can be used for state propagation on their own to achieve better precision without including the IMU. Further, we propose a factor composed of the preintegrated motor speeds that can be directly employed in factor graph optimization frameworks. We combine our factor with LiDAR measurements into the proposed Motor Angular Speed LiDAR Odometry (MAS-LO) algorithm for precise state estimation, which we open-source. Lastly, we evaluate the estimation precision against a state-of-the-art inertial algorithm LIO-SAM to show 28% improvement in position and 65% in velocity estimation accuracy, 14% lower measurement lag, and high robustness to wrong parameter values.
### Title:
          An Infrastructure-less, Control-Independent Solution to Relative Localisation of a Team of Mobile Robots using Ranging Measurements
 - **Authors:** Paolo Golinelli, Tommaso Faraci, Daniele Fontanelli
 - **Subjects:** Subjects:
Robotics (cs.RO); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The ability to localise teams of robots is essential for applications ranging from robotic fleets in unstructured environments to cooperative control and navigation tasks. In such contexts, fixed infrastructure is often unavailable, deployments must be fast and flexible, and system requirements must be minimal. We present a decentralised cooperative localisation algorithm that addresses all these challenges at once. The method is anchor-less, fully decentralised, and, unlike most existing approaches, does not require controlling the robots motion to ensure team observability. It relies only on local odometry, sparse inter-agent ranging measurements, and short-range communication, all of which are widely available in practice. The algorithm adopts a multi-hypothesis Bayesian framework that maintains the entire set of feasible solutions, ensuring robustness under transient unobservable conditions. Moreover, through information sharing, each agent benefits from the estimates of the entire group, even in partially connected conditions.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          ForEnt: A Multi-Modal Dataset for Characterizing Quadruped Robot Entrapments in Forest Environments
 - **Authors:** Natapat Kirdwichai, Danesh Tarapore
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Legged robots are increasingly deployed in forests for ecological surveying and monitoring, yet their autonomy is often interrupted consequent to the challenges posed in traversing forest environments. Forest entrapments, for example, when a robot's legs are ensnared in vines or other vegetation, result in loss of stability and toppling. Such events not only disrupt the mission and require manual intervention, but also risk damage to the robot hardware. To address the absence of a dedicated dataset to investigate these failure modes in forest environments, we present ForEnt, a multi-modal dataset collected with the low-cost Unitree Go2 quadruped across eight forest sites in the Southampton Common Woodlands, UK. For our dataset, over approximately 1.7 km of traversals in 11 sequences were conducted, yielding 69 recorded entrapment events. ForEnt includes time-synchronized RGB-D images, LiDAR scans, proprioceptive data, and third-person video, enabling analysis of terrain factors contributing to entrapment and providing labeled sensor streams for reproducible benchmarking. By supporting the evaluation of entrapment detection strategies, ForEnt lowers the barrier to developing robust quadruped robot deployments in challenging forest environments.
### Title:
          Motor Angular Speed Preintegration for Multirotor UAV State Estimation
 - **Authors:** Matěj Petrlík, Filip Novák, Robert Pěnička, Martin Saska
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A precise state estimate is crucial for a tight feedback control that enables agile and near-obstacle flights of UAVs. The state-of-the-art methods fuse slow pose measurements with high-frequency inertial measurements to obtain a precise state estimate. However, the inertial measurements from the IMU onboard the UAV are degraded by vibrations from spinning propellers and the precision of the estimated state suffers. We propose a novel approach based on the preintegration of accelerations obtained from motor speeds. We show that the accelerations obtained in this manner can be used for state propagation on their own to achieve better precision without including the IMU. Further, we propose a factor composed of the preintegrated motor speeds that can be directly employed in factor graph optimization frameworks. We combine our factor with LiDAR measurements into the proposed Motor Angular Speed LiDAR Odometry (MAS-LO) algorithm for precise state estimation, which we open-source. Lastly, we evaluate the estimation precision against a state-of-the-art inertial algorithm LIO-SAM to show 28% improvement in position and 65% in velocity estimation accuracy, 14% lower measurement lag, and high robustness to wrong parameter values.
### Title:
          Geometry-Preserving in 3D Gaussian Splatting for LiDAR-Camera Extrinsic Calibration
 - **Authors:** Kyoleen Kwak, Daeho Kim, Jeong Woon Lee, Hyoseok Hwang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate LiDAR-camera calibration is essential for robust multi-modal perception. Targetless approaches avoid manual setup but remain limited by the scarcity of discriminative cross-modal features. Recent methods address this by reconstructing the scene within a differentiable model, enabling extrinsic optimization through dense photometric supervision. Among these, 3D Gaussian Splatting (3DGS) has been widely adopted as a geometric proxy that bridges LiDAR and camera within a single differentiable framework. However, since 3DGS was originally designed for novel view synthesis, existing methods tend to prioritize rendering quality, causing the proxy geometry to drift from the true LiDAR structure. We propose a framework that preserves the metric geometry of the Gaussian proxy by aggregating multi-view LiDAR observations for dense depth supervision and blocking photometric gradients from updating the Gaussian spatial parameters. We validate our method on public driving datasets, where it consistently outperforms existing targetless methods in calibration accuracy.
### Title:
          HilDA: Hierarchical Distillation with Diffusion for Advancing Self-Supervised LiDAR Pre-trainin
 - **Authors:** Maciej Wozniak, Jesper Ericsson, Hariprasath Govindarajan, Truls Nyberg, Thomas Gustafsson, Patric Jensfelt, Olov Andersson
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Leveraging Vision Foundation Models (VFMs) for camera-to-LiDAR knowledge distillation offers a promising solution to the scarcity of annotated data needed to represent the immense geometric and kinematic diversity of real-world autonomous driving (AD). However, current approaches typically treat VFMs as black-box teachers, relying exclusively on frame-wise feature similarity. Consequently, they do not fully exploit the teacher's layer-wise semantic structure and global context, as well as the rich spatiotemporal information inherent in LiDAR sequences. We propose HilDA, a self-supervised pretraining framework for LiDAR backbones that better captures the semantic what and geometric where needed for driving tasks. HilDA combines hierarchical distillation comprising multi-layer distillation for progressive semantic alignment and global context distillation for scene-level semantics, with a temporal occupancy diffusion objective promoting spatiotemporal consistency. Models pre-trained with HilDA achieve state-of-the-art results on cross-modal distillation benchmarks and outperform models trained via prior distillation approaches on 3D object detection, scene flow, and semantic occupancy prediction. Code available at: this https URL.
### Title:
          Integrating national forest inventory, airborne lidar, and satellite imagery for wall-to-wall mapping of forest structure with computer vision
 - **Authors:** Luke J. Zachmann, David D. Diaz, Vincent A. Landau, Chelsey Walden-Schreiner, Tony Chang, Nathan E. Rutenbeck, Katharyn A. Duffy, Kiarie Ndegwa, Andreas Gros, Scott Conway, Guy Bayes
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Remote sensing is increasingly relied upon to deliver actionable science for forest and wildfire risk management across large landscapes. Wall-to-wall, annually updated maps are a persistent need for effective forest management. Many planning systems and data collections combine disparate data sources with different purposes, vintages, and prediction quality, which leads to confounding behavior in operational planning systems. We introduce the VibrantForests framework, developed and applied to map forest attributes and provide a coherent foundation for effective forest and wildfire planning. VibrantForests includes a satellite-based forest structure model trained on lidar-derived samples and applied across the contiguous United States to concurrently generate estimates of canopy cover, canopy height, aboveground live tree biomass, basal area, and quadratic mean diameter at 10-meter resolution. We demonstrate predictive capability spanning the full spectrum of forest conditions ranging from sparse-canopy/low-biomass to dense-canopy/high-biomass. Results show that our model extends the range at which saturation is commonly encountered in comparable passive-sensor models, and reduces regression-to-mean behavior that commonly produces overestimation of forest attributes in small/sparse conditions and underestimation in large/dense conditions. The VibrantForests framework addresses a key limitation in large-area forest and wildfire planning by delivering coherent wall-to-wall estimates of management-relevant attributes at annual cadence and 10m resolution.
### Title:
          LIT-GS: LiDAR-Inertial-Thermal Gaussian Splatting for Illumination-Robust Mapping
 - **Authors:** Shikuan Shi, Chunran Zheng, Jiaming Xu, Tianyong Ye, Tao Yu, Yukang Cui
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Gaussian Splatting has enabled real-time neural rendering, yet existing LiDAR-inertial-visual (LIV) Gaussian mapping pipelines remain fragile under illumination changes and texture-deficient scenes due to their reliance on RGB photometric cues. We present LIT-GS, a LiDAR-inertial-thermal Gaussian Splatting framework that injects LiDAR-derived plane geometry as an explicit constraint in both pose/structure refinement and Gaussian optimization. Specifically, we exploit LIV visual map points as confidence-aware cross-modal anchors to establish reliable thermal-LiDAR associations, and incorporate weighted LiDAR point-to-plane residuals into bundle adjustment to jointly refine camera poses and 3D points under weak thermal supervision. Building on the refined structure, we further introduce a LiDAR-plane-regularized differentiable splatting objective that constrains rendered 3D points to align with locally observed planes, mitigating surface thickening and structural drift in low-contrast thermal imagery. Experiments on proprietary sequences and public datasets demonstrate that LIT-GS consistently improves geometric accuracy and rendering quality over state-of-the-art LIV-based Gaussian Splatting baselines, particularly in challenging lighting conditions.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          One-Shot Novel View and Pose Human Image Synthesis via 3D Prior Guided Diffusion Model
 - **Authors:** Shenjian Gong, Kangkan Wang, Shanshan Zhang, Jian Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper addresses the challenge of one-shot novel view and pose human image synthesis. The existing methods transfer the reference human image to a target pose using a set of 2D pose keypoints or synthesize human images based on generalizable human NeRF which uses human model priors to extract point-wise features. However, pose transfer based methods can not handle complex human pose using ambiguous 2D pose as the condition, while generalizable human NeRFs may be inaccurate to recover occluded/invisiable human parts without extracted reliable features. To solve these problems, we propose a novel approach for novel view and pose synthesis from a singe human image via conditional denoising diffusion model. Our diffusion model divides the novel view and pose synthesis problem into a sequence of conditional denoising steps. Specifically, to generate humans with complex and arbitrary poses, we introduce 3D human priors, i.e., 3D normal map and color prompt, as geometry and color conditions into the generation process. By transferring the reference human into the target human with a series of diffusion steps, our diffusion model enables high-quality synthesis including the occluded/invisible parts. Further, we propose a self-reconstruction based customized refinement to enhance fine details when tested on novel this http URL results on different public datasets demonstrate that our approach significantly outperforms previous methods and also shows better generalization ability across datasets. The code will be made publicly available at this https URL.
### Title:
          VisDom: Sparse Novel View Synthesis with Visible Domain Constraint
 - **Authors:** Mariia Gladkova*, Tarun Yenamandra*, Edmond Boyer, Robert Maier, Tony Tung, Daniel Cremers
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sparse novel view synthesis (NVS) remains challenging due to the ambiguity of recovering 3D geometry from few input views. While NeRF- and Gaussian Splatting (GS)-based methods perform well with dense supervision, they often overfit in sparse settings, producing floating artifacts and inconsistent geometry. Silhouette consistency is commonly used as a regularizer, but it remains insufficient, as silhouette-consistent regions can extend beyond the true object geometry. We introduce VisDom, a learning-free geometric constraint that augments classical carving-based visual hull reconstruction by enforcing a minimum multi-view visibility requirement. Specifically, we define a visible domain as the subset of 3D space observed by at least $K$ views and use it as an additional filtering criterion on top of standard silhouette-based reconstruction. This provides a stronger spatial prior in sparse-view settings. We integrate VisDom into both implicit (NeRF) and explicit (GS) pipelines by restricting volumetric sampling and guiding Gaussian placement during optimization. Experiments on three challenging datasets show consistent improvements in sparse-view NVS, enabling high-quality object-centric reconstruction from as few as four input images. Our method is domain-agnostic, requires only silhouettes, and introduces no learned parameters, making it a simple complement to existing approaches. Applying VisDom on top of GaussianObject further improves performance on Omni3D and MipNeRF360, while matching or surpassing it at 22 $\times$ lower training cost.
## Keyword: mapping
### Title:
          cAPM: Continual AI-Assisted Pace-Mapping with Active Learning
 - **Authors:** Dylan O'Hara, Pradeep Bajracharya, Casey Meisenzahl, Karli Gillette, Anton J. Prassl, Gernot Plank, Saman Nazarian, Roderick Tung, John L Sapp, Linwei Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ventricular tachycardia is a life-threatening rhythm disorder and a major cause of sudden cardiac death. Pace-mapping is a clinical procedure for identifying the intervention target during catheter ablation of VT. It requires clinicians to pace different sites in the ventricles and rapidly interpret the resulting electrocardiograms to determine where to pace next or whether a target site has been identified. Active learning AI models have been proposed to guide clinicians to the next pacing site, showing promise in reducing the number of pacing sites and improving the efficiency of pace-mapping. Existing methods require retraining each target without the ability to transfer knowledge across multiple VTs within the same patient or across patients. We introduce cAPM for continuous AI-assisted pace-mapping to capture and transfer knowledge accumulated from past pace-mapping data to reduce the number of pace-mapping data needed for future target VTs. This is made possible by a task-agnostic surrogate neural network that learns the mapping from pacing sites to 12-lead ECG morphology, an active-learning strategy that refines this surrogate model by selecting the most informative pacing site for each target, and a continual learning strategy to do so sequentially while retaining knowledge from prior targets. Evaluated on an in-silico testbed consisting of sequentially-presented localization tasks across different physiological conditions and ventricular geometries, cAPM with and without replay of past data samples achieved an 81% probability of localizing within clinical tolerance (5 mm accuracy) using 4.5 pace-mapping sites, compared to the state-of-the-art active-learning method achieving 38% probability using 13.7 pacing sites. These results provide a strong basis for preparing cAPM towards in-vivo preclinical and clinical studies where it can be used to guide pace-mapping.
### Title:
          On Epimorphisms of Hypergraphic Automata and Input Symbol Semigroups
 - **Authors:** Jasem Hamoud
 - **Subjects:** Subjects:
Formal Languages and Automata Theory (cs.FL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hypergraphic automata are automata whose state sets and output symbol sets are hypergraphs invariant under the actions of the transition and output functions. Universally attracting objects in the category of such automata are called universal hypergraphic automata; their semigroups of input symbols are algebras of mappings whose properties are tightly linked to the algebraic structure of the automata themselves. This paper establishes a complete characterisation of epimorphisms of universal hypergraphic automata and of their semigroups of input symbols. A central contribution is the introduction of two distinct notions of epimorphism for hypergraphs including weak, strong and the proof that these notions diverge in general but necessarily coincide for the important subclass of $p^*$-hypergraphs, which includes automata whose state hypergraphs and output hypergraphs are projective or affine planes. The main results give necessary and sufficient conditions for a triple $(f, \mathbb{P}_s, g)$ to be an epimorphism of universal hypergraphic automata, expressed in terms of the component maps on the state and output hypergraphs.
### Title:
          DiffusionVS: A Generative Framework for Robust Visual Servoing Based on Diffusion Policy
 - **Authors:** Hongkang Cui, Rui He, Haoyao Chen
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual servoing is a fundamental technique in robotic manipulation and navigation. Regression-based visual servoing frequently experiences trajectory jitter as a result of noise-sensitive single-step mappings and the accumulation of errors during distribution shifts. In contrast, Diffusion Policy maintains temporal consistency by predicting action sequences and improves robustness through implicit data augmentation. This paper presents a novel diffusion-based servoing method. Based on Diffusion Policy, the proposed approach uses normalized image coordinates of observed tag corners as input and generates camera velocity through conditional denoising. To overcome the generalization limitations of models trained on static datasets, an online training paradigm is adopted, continuously expanding the diversity of training data through interactive experience collection. This strategy substantially enhances both the performance and generalization capability of the model. Comprehensive simulations and real-world experiments demonstrate the effectiveness of the proposed method, achieving success rates of nearly 100\% in simulation and 93\% in physical experiments. Beyond the specific pipeline, we further validate the generality of the diffusion mechanism. Experiments show that existing visual servoing networks consistently achieve improved performance when integrated with our diffusion-based module. These results indicate that the proposed strategy possesses broad applicability and can enhance various visual servoing systems beyond the specific architecture presented here.
### Title:
          Moreau-Yosida-based Kohn-Sham Inversion for Periodic Systems
 - **Authors:** Vebjørn H. Bakkestuen, Michael F. Herbst, Vegard Falmår, Markus Penz, Andre Laestadius
 - **Subjects:** Subjects:
Numerical Analysis (math.NA); Materials Science (cond-mat.mtrl-sci); Functional Analysis (math.FA); Chemical Physics (physics.chem-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Density-potential inversion for periodic systems within Moreau-Yosida-regularised density-functional theory is investigated, both theoretically and numerically. We develop the framework in a periodic homogeneous Sobolev space and use it to recover the exchange-correlation potential of Kohn-Sham theory through a limiting procedure. A key analytical ingredient is the proof of lower semicontinuity of the non-interacting kinetic-energy functional in the chosen topology. The proximal mapping, together with its algorithmic evaluation, plays a central role in the resulting inversion scheme. Numerical experiments illustrate the performance and properties of the method for both the Kohn-Sham and Gross-Pitaevskii equations.
### Title:
          A Tool for the Synthesis of Adaptive Probabilistic Processors Based on the Ising Model
 - **Authors:** Jonathan Juracy Carneiro da Silva, Leonardo R. Gobatto, Jose Rodrigo Azambuja
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work presents a tool for the synthesis and simulation of probabilistic architectures for solving combinatorial optimization problems by mapping them to the Ising model. The proposed approach automatically constructs the Ising Hamiltonian and determines the number of probabilistic elements (p-bits) based on problem characteristics such as size and topology. Furthermore, the tool introduces an adaptive strategy for selecting the most suitable update algorithm among Gibbs Sampling, Simulated Annealing (SA), Simulated Quantum Annealing (SQA), and cluster-based methods. Experimental results using benchmark problems demonstrate improved convergence behavior and flexibility compared to fixed approaches. The proposed framework enables systematic evaluation of probabilistic computing strategies and supports the development of future hardware implementations based on MTJs and p-bits.
### Title:
          Where Does Social Reasoning Come From? Capability Provenance in Language Models
 - **Authors:** Glenn Matlin, Chandreyi Chakraborty, Saehee Eom, Mika Okamoto, Rayan Castilla, Louis Jaburi, Alvin Deng, Taywon Min, Lucia Quirke, Stella Biderman, Mark Riedl
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We use training-data attribution as an interpretable tool for capability discovery, mapping which regions of the pretraining corpus support social-reasoning versus STEM-reasoning in OLMo3-7B. Training-data attribution measures how strongly each training document influences a model's predictions on a benchmark, but document-level scores are too noisy to identify which corpus regions support which capabilities, and prior work has emphasized factual knowledge rather than reasoning. We compute gradient-based attribution (TrackStar via Bergson) over a working set drawn from the de-duplicated Dolma3 mix, aggregate influence across WebOrganizer's 24-format x 24-topic taxonomy (576 bins), and contrast benchmark pairs in a 2x2 design that varies domain (social vs. STEM) and capability type (reasoning vs. knowledge): SocialIQA and MMLU Social Sciences against ARC-Challenge and MMLU STEM. Social and STEM reasoning draw on qualitatively distinct corpus regions, and the contrast is sharper at the reasoning level than at the knowledge level. Targeted machine unlearning provides partial causal validation: forgetting high-attribution topic bins (e.g., Literature for SocialIQA) degrades the aligned benchmark more than within-bin random baselines, and we open-source all code, sampling manifests, the bin-level influence matrix, and unlearning checkpoints.
### Title:
          GLARE: A Natural Language Interface for Querying Global Explanations
 - **Authors:** Bhavan Vasu, Rajesh Mangannavar
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While global explanations are crucial for understanding vision models across datasets, classes, and decision contexts, their complex and monolithic nature often hinders practical exploration. Because users typically seek targeted answers to specific questions rather than static artifacts, we present an LLM-based interactive interface that provides natural language access to global explanations for black-box image classifiers. The system's core LLM acts as a mediator, translating natural language questions into structured SQL queries over local explanation data. This enables flexible aggregation without exposing users to low-level representations. For each query, the interface outputs statistics-augmented natural language responses, supporting local explanations, and intent-aligned visualizations. We evaluate the system on intent interpretation, query mapping accuracy, generalization to novel queries and datasets, and robustness to linguistic errors. Our results demonstrate that LLM-mediated querying substantially improves the accessibility and usability of global explanations for human-centered XAI.
### Title:
          MMD-SLAM: Structure-Enhanced Multi-Meta Gaussian Distribution-Guided Visual SLAM
 - **Authors:** Fan Zhu, Ziyu Chen, Peichen Liu, Yifan Zhao, Zhisong Xu, Hui Zhu, Hongxing Zhou, Sixun Liu, Chunmao Jiang
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian Splatting (3DGS) has significantly boosted novel view synthesis and high-fidelity scene reconstruction, expanding the potential of 3DGS-based Visual Simultaneous Localization and Mapping (SLAM) methods. However, most existing systems fail to fully exploit the underlying structural information, which limits rendering quality and often leads to inconsistent maps. To address these limitations, we propose MMD-SLAM, a structure-enhanced Visual SLAM framework that leverages the Atlanta World (AW) assumption to guide a Multi-Meta Gaussian representation for photorealistic mapping. First, we introduce a point-line fusion strategy for pose optimization, where 3D line segments are incorporated to improve tracking robustness and provide additional constraints for mapping. Second, we design a Multi-Meta Gaussian representation with dominant directions, explicitly encoding structural priors from the AW hypothesis. Finally, we propose a Gaussian evolution strategy that adapts to scene geometry and incorporates structural cues into global optimization. Extensive experiments demonstrate that these innovations enable MMD-SLAM to achieve state-of-the-art performance in both tracking accuracy and mapping quality. e.g., our method achieves a 48.56% reduction in ATE RMSE on ScanNet and a 5.71% improvement in PSNR on Replica, compared with MonoGS.
### Title:
          FFinRED: An Expert-Guided Benchmark Generation and Evaluation Framework for Financial LLM Red-Teaming
 - **Authors:** Chaeyun Kim, Daeyoung Park, Junghwan Kim, Jinyoung Jeong, Eunji Song, Yongtaek Lim, Minwoo Kim
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing safety benchmarks target general adversarial scenarios but miss finance-specific risks. Financial LLMs face regulatory compliance violations, fraud facilitation, and systemic trust erosion that require targeted evaluation. We introduce FinRED, an expert-guided red-teaming framework for financial LLM safety evaluation developed with financial experts. FinRED uses a novel two-level taxonomy mapping global standards (e.g., FATF and EU DORA) to threats ranging from regulatory evasion to complex fraud, integrated with a scalable pipeline that converts real financial documents into context-rich red-teaming Behavioral Prompts (seeds) through an expert-defined schema. Rigorous expert validation confirms seed plausibility and realism for meaningful LLM safety evaluation. We also provide an expert-validated, finance-specific rubric that goes beyond disclaimer checks, aligns more closely with human experts than static one-size-fits-all rubrics, and reduces critical false negatives from 28 to 12. Aligned with internationally adopted risk-management and information-security standards (e.g., ISO/IEC 27001), FinRED is deployed in South Korea's Financial Security Institute (FSI) regulatory sandbox for generative AI security evaluation in real financial services. To mitigate dual-use risks, the dataset, generation pipeline, prompt template, and evaluation framework are gated for qualified researchers at this https URL and this https URL.
### Title:
          One-to-Two Acting: A Novel Framework for Single-arm Agent Action Expansion to Dual Arms
 - **Authors:** Youbin Yao, Nieqin Cao, Mingyan Li, Yan Ding, Fuqiang Gu, Chao Chen
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dual-arm manipulation can improve throughput via parallel execution, but collecting bimanual demonstrations for training is costly and difficult. We present ExS2D, a hierarchical action expansion framework that enables dual-arm manipulation from single-arm supervision. ExS2D first generates structured subtasks from textual instructions while explicitly capturing temporal precedence. It then grounds each subtask into executable actions through subtask-guided action mapping in observation. Finally, precedence-aware action allocation and synchronized planning are performed by a multimodal large language model driven coordinator to select collision-free dual-arm executions. Simulation experiments demonstrate that ExS2D reduces the average execution steps by 54.4% while maintaining a comparable success rate to a single-arm baseline. Real-robot experiments on four tasks further demonstrate the reliability of ExS2D for dual-arm execution under few-shot single-arm samples, while using zero bimanual demonstrations.
### Title:
          Design and Evaluation of Energy-Efficient Whisper Dot-Product Kernel Offloading on a CGLA Architecture
 - **Authors:** Takuto Ando, Yu Eto, Ayumu Takeuchi, Yasuhiko Nakashima
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we implement and evaluate Whisper dot-product kernel offloading on IMAX, a programmable Coarse-Grained Linear Arrays (CGLAs) architecture. this http URL profiling on an ARM Cortex-A72 shows that dot-product operations account for 90.6% of FP16 execution time and 87.1% of Q8_0 execution time. To address this kernel bottleneck, we combine kernel mapping, local-memory sizing, and burst scheduling. The implementation uses inline FP16-to-FP32 conversion, 2-way SIMD FMA on a 64-bit datapath, column-wise multithreading, and mixed execution in which aligned vector segments run on IMAX and residual segments run concurrently on the host CPU. We evaluate the design with an FPGA prototype and a 28nm ASIC projection at 840MHz. For this http URL, 32KB local memory and burst length 16 jointly minimize PDP and EDP. Under a TDP-based cross-platform comparison, the projected IMAX records a PDP of 11.58J for this http URL Q8_0, 2.35x lower than Jetson AGX Orin (27.16J) and 10.48x lower than RTX 4090 (121.38J). The same design extends to this http URL and this http URL, where the PDP gap narrows as 32KB local-memory coverage drops from 93.8% for tiny to about 66.5% for base and small. These results position IMAX as a programmable architecture for lower-PDP local ASR in the tiny-model regime.
### Title:
          Deep-Unfolded Coordination
 - **Authors:** Hunter Kuperman, Minchan Jung, Rahul V. Ghosh, Alex Oshin, Evangelos A. Theodorou
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Distributed optimization is a highly scalable and structurally transparent technique to solve multi-agent robotics problems; however, such methods often suffer from the need for highly-specialized, problem-specific hyperparameter tunings. In this work, we propose Deep Coordinator, a deep-unfolding framework that learns to dynamically adjust the hyperparameters of ADMM-DDP, a popular distributed solver for robotics tasks, at solve-time in response to optimizer performance. Our architecture consists of unrolling a fixed number of ADMM-DDP iterations into a neural network with learnable functions between layers mapping the optimizer state to the next hyperparameters. To the best of our knowledge, Deep Coordinator is the first deep-unfolding framework to adapt the penalty parameters of a non-convex optimizer at solve-time; we show that the mainstream supervised approach can yield degenerate solutions when training such models, and propose an unsupervised learning scheme. On simulations with fleets of cars and quadrotors, Deep Coordinator produces trajectories of comparable quality 6.18-9.44x faster than conventional solvers. Furthermore, Deep Coordinator retains its performance benefits when deployed to systems up to 8x larger than trained on.
### Title:
          Exploring the potential of AlphaEarth and TESSERA embeddings for Fine-scale Local Climate Zone Mapping: A case study across five cities in Switzerland
 - **Authors:** Htet Yamin Ko Ko, Clement Atzberger
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding urban spatial morphology is critical for climate modeling, risk assessment, and sustainable urban design, and Local Climate Zone (LCZ) mapping provides the basic framework for this. However, many cities still use coarse ~100-m resolution LCZ records, which are unsuitable for fine-scale urban research. In this study, precomputed embeddings from TESSERA (Feng et al., 2025) and AlphaEarth (Brown et al., 2025) are compared to traditional Sentinel-1/2 (S1S2) composites in five Swiss cities to see if they can upscale coarse LCZ maps to 10-m resolution using an attention-based U-Net. Three experiments assess multi-city transferability, the impact of higher-resolution reference data, and temporal robustness to year-to-year phenology changes. We find that all datasets achieve strong performance with test data Intersection-over-Union (IoU) ranging from 0.59-0.69 and 0.77-0.82 in the first two experiments. TESSERA consistently outperforms both S1S2 and AlphaEarth across both settings As expected, we find that the transfer of embedding-based models from one year to another remains an open challenge. Overall, however, our results demonstrate the promising potential of embeddings derived from EO foundation models to reduce time consuming preprocessing, respectively, manual feature engineering tasks and to guide a universal deep learning-based LCZ mapping workflow. When combined with a simple location-aware attention U-Net architecture, the embeddings enhance regional transferability and scalability, supporting the development of comprehensive and reproducible fine-scale LCZ maps for global urban climate applications Improving reference data quality remains the strongest lever for further accuracy gains.
### Title:
          PU-UNet: Stable Multiplicative Interactions for Medical Image Segmentation
 - **Authors:** Ziyuan Li, Osamah Sufyan, Uwe Jaekel, Babette Dellen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many dense prediction networks rely on additive feature transformations and model higher-order feature interactions only implicitly. Product units provide an explicit mechanism for multiplicative feature modeling, but their logarithmic--exponential formulation can cause numerical instability, which has limited their use in deep dense prediction networks. In this work, we propose Product-Unit U-Net (PU-UNet), a residual U-Net that integrates stable product-unit residual blocks into rich low-resolution stages for medical image segmentation. The proposed formulation combines smooth positivity mapping with log-domain clipping, enabling stable multiplicative feature learning with negligible computational overhead. On ISIC 2018, Kvasir-SEG, and BUSI, PU-UNet achieves Dice scores of 0.942, 0.959, and up to 0.925, respectively. Compared with a matched Residual U-Net baseline, PU-UNet consistently improves Dice and IoU while keeping parameters, FLOPs, and inference latency nearly unchanged, and reduces the image-level false-positive rate on normal BUSI cases from 0.077 to zero. Ablation studies suggest that the gains are associated with product-unit interactions, are strongest under low-resolution placement, and benefit from the proposed stabilization design. These results suggest that stable product-unit residual learning can be an effective way to enhance U-Net-style segmentation networks with explicit multiplicative interactions.
### Title:
          EFIQA: Explainable Fundus Image Quality Assessment via Anatomical Priors
 - **Authors:** Pengwei Wang, José Morano, Qian Wan, Hrvoje Bogunović
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Image quality control is vital for a wide range of downstream applications. Deep learning-based image quality assessment methods typically train classifiers on dataset-specific quality labels, inheriting two limitations: (1) generalization is tied to the labeling criteria of the training set and (2) these methods cannot provide spatial feedback on where the quality is degraded, lacking explainability. In this work, we propose EFIQA, a framework that requires no quality-related supervision and produces spatial quality maps by design. Rather than learning ``what is degradation" from human-annotated labels, EFIQA learns ``what should be there" by leveraging anatomical priors. For fundus photography, we instantiate this as a two-stage approach, by first training an unsupervised anomaly detector via masked anatomical inpainting to identify regions of missing vasculature, and then distilling this prior knowledge into a shallow adapter mapping features of a frozen foundation model to precise quality maps. External-dataset evaluation demonstrates that this label-free approach with minimal adaptation achieves better performance and explainability compared with supervised methods across benchmarks with different quality criteria, highlighting its potential for real-world applications.
### Title:
          Dual-Agent Framework for Cross-Model Verified Translation of Natural-Language Protocols into Robotic Laboratory Platform
 - **Authors:** Hyeonna Choi, Jung Yup Kim, Hyuneui Lim, Seunggyu Jeon
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Biological experiment protocols are written in natural language, whereas automation systems rely on predefined control commands, creating a semantic gap that limits autonomous execution. Microplate-based automatic experiments are particularly challenging due to the need to simultaneously control well mapping, sample-reagent combinations, replicate placement, and parallel dispensing. This study proposes an agent-based protocol translation framework that converts natural-language microplate-based protocols into executable control commands for a robotic laboratory platform. A Parser Agent formalizes the natural-language protocol into a structured representation, and a rule-based mapping engine deterministically incorporates the operational constraints of the robotic laboratory platform to generate device-level control commands. A heterogeneous LLM Validation Agent verifies completeness, parameter accuracy, and execution order, and triggers a self-correction loop with structured feedback when errors are detected. A sweep involving 7 Parsers and 3 Validators on randomly selected ELISA protocols evaluates how model scale and Validator type affect translation accuracy and pass rates under cross-model verification. The accuracy-latency trade-off is further verified by comparing the rule-based mapping of the proposed framework with LLM end-to-end direct mapping. Finally, Bradford assay-based protein quantification using a microplate was demonstrated on a robotic laboratory platform, validating end-to-end autonomous execution from natural-language protocols to real-world experiments. The proposed framework provides a flexible approach to narrowing the semantic gap between natural-language protocols and microplate-based self-driving laboratories.
### Title:
          Towards 3D karst underwater scene reconstruction from rotating sonar data
 - **Authors:** Georgios Evangelos Margaritis, Lionel Lapierre, Simon Rohou, Zhi Yan, Andreas Nüchter, François Goulette
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Karst aquifers provide critical freshwater resources but pose significant hazards due to their complex and poorly understood subsurface geometry. Mapping these environments is challenging because sonar data from underwater exploration is sparse and noisy, while navigation estimates suffer from drift limiting standard 3D reconstruction methods. We present a pipeline for reconstructing underwater karst conduits from a sonar profiler. We combine a continuous-time SLAM approach to correct trajectory drift with a novel two-stage deep learning method for surface reconstruction, producing an immersive and navigable 3D mesh for hydrogeological analysis.
### Title:
          Critical Percolation as a Synthetic Data Model for Interpretability
 - **Authors:** Aryeh Brill, Tom Ingebretsen Carlson
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Disordered Systems and Neural Networks (cond-mat.dis-nn)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural networks learn features that reflect the hierarchical, multi-scale structure of natural data. Synthetic datasets used to evaluate interpretability methods typically lack this structure, limiting their value as realistic toy models. To close this gap, we introduce a family of synthetic datasets consisting of hierarchical functions defined on critical mean-field percolation clusters embedded in a high-dimensional data space. The percolation data consists of sparse, low-dimensional fractal clusters with a power-law size distribution. Latent variables modeling a taxonomic hierarchy generate each data point's target value. The data model is analytically tractable with known critical exponents that fix its properties without requiring hyperparameter tuning. We leverage a mapping between percolation clusters, random trees, and additive coalescence to propose an almost linear-time algorithm to jointly sample a random tree and its hierarchical latent decomposition, enabling data generation at arbitrary scale. Using probing experiments, we find that the model's ground-truth latent variables can be linearly decoded from neural network activations. Together, sparsity, self-similarity, power-law statistics, and analytical tractability make critical percolation a principled testbed for interpretability research.
### Title:
          CoLI: A Reproducible Platform for Continuum Robot Learning via Monolithic 3D Printing and Isomorphic Teleoperation
 - **Authors:** Ziyuan Tang, Chenxi Xiao*
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Continuum robots offer strong potential for manipulation tasks due to their high degrees of freedom, compliant structures, and operational safety. However, their adoption in both research and practical applications has been hindered by reproducibility issues arising from complex fabrication and assembly processes, challenging kinematic modeling, and a lack of intuitive control interfaces. To address these challenges, we present a novel open-source continuum robot design. The platform features a simplified fabrication pipeline enabled by multi-material 3D printing, allowing the arm to be fabricated as a monolithic compliant structure with minimal assembly. Control is achieved through an isomorphic teleoperation interface that establishes a direct actuator-level mapping, eliminating the need for explicit kinematic modeling and providing a singularity-free mapping. Building on this hardware design, the platform further supports imitation-learning-based autonomous control. The proposed system is evaluated through hardware characterization and a set of manipulation tasks. Experimental results demonstrate that the platform provides a reproducible, learning-ready continuum robot system, accelerating algorithmic development and systematic benchmarking for the continuum robotics community.
### Title:
          LIT-GS: LiDAR-Inertial-Thermal Gaussian Splatting for Illumination-Robust Mapping
 - **Authors:** Shikuan Shi, Chunran Zheng, Jiaming Xu, Tianyong Ye, Tao Yu, Yukang Cui
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Gaussian Splatting has enabled real-time neural rendering, yet existing LiDAR-inertial-visual (LIV) Gaussian mapping pipelines remain fragile under illumination changes and texture-deficient scenes due to their reliance on RGB photometric cues. We present LIT-GS, a LiDAR-inertial-thermal Gaussian Splatting framework that injects LiDAR-derived plane geometry as an explicit constraint in both pose/structure refinement and Gaussian optimization. Specifically, we exploit LIV visual map points as confidence-aware cross-modal anchors to establish reliable thermal-LiDAR associations, and incorporate weighted LiDAR point-to-plane residuals into bundle adjustment to jointly refine camera poses and 3D points under weak thermal supervision. Building on the refined structure, we further introduce a LiDAR-plane-regularized differentiable splatting objective that constrains rendered 3D points to align with locally observed planes, mitigating surface thickening and structural drift in low-contrast thermal imagery. Experiments on proprietary sequences and public datasets demonstrate that LIT-GS consistently improves geometric accuracy and rendering quality over state-of-the-art LIV-based Gaussian Splatting baselines, particularly in challenging lighting conditions.
## Keyword: localization
### Title:
          cAPM: Continual AI-Assisted Pace-Mapping with Active Learning
 - **Authors:** Dylan O'Hara, Pradeep Bajracharya, Casey Meisenzahl, Karli Gillette, Anton J. Prassl, Gernot Plank, Saman Nazarian, Roderick Tung, John L Sapp, Linwei Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ventricular tachycardia is a life-threatening rhythm disorder and a major cause of sudden cardiac death. Pace-mapping is a clinical procedure for identifying the intervention target during catheter ablation of VT. It requires clinicians to pace different sites in the ventricles and rapidly interpret the resulting electrocardiograms to determine where to pace next or whether a target site has been identified. Active learning AI models have been proposed to guide clinicians to the next pacing site, showing promise in reducing the number of pacing sites and improving the efficiency of pace-mapping. Existing methods require retraining each target without the ability to transfer knowledge across multiple VTs within the same patient or across patients. We introduce cAPM for continuous AI-assisted pace-mapping to capture and transfer knowledge accumulated from past pace-mapping data to reduce the number of pace-mapping data needed for future target VTs. This is made possible by a task-agnostic surrogate neural network that learns the mapping from pacing sites to 12-lead ECG morphology, an active-learning strategy that refines this surrogate model by selecting the most informative pacing site for each target, and a continual learning strategy to do so sequentially while retaining knowledge from prior targets. Evaluated on an in-silico testbed consisting of sequentially-presented localization tasks across different physiological conditions and ventricular geometries, cAPM with and without replay of past data samples achieved an 81% probability of localizing within clinical tolerance (5 mm accuracy) using 4.5 pace-mapping sites, compared to the state-of-the-art active-learning method achieving 38% probability using 13.7 pacing sites. These results provide a strong basis for preparing cAPM towards in-vivo preclinical and clinical studies where it can be used to guide pace-mapping.
### Title:
          Lightweight Non-Line-of-Sight Channel Detection for ML-assisted Bluetooth Direction Finding
 - **Authors:** Hamed Talebian, Aamir Mahmood, Mehdi Haghshenas, Stefani Rydbloom, Peter Karlsson, Mikael Gidlund
 - **Subjects:** Subjects:
Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bluetooth Low Energy (BLE) direction-finding is promising for indoor industrial localization, but its accuracy degrades in multipath environments where reflections and scattering bias angle estimates. Although line-of-sight (LOS) and non-line-of-sight (NLOS) detection is well studied for wide-band radios, BLE direction-finding still lacks narrow-band channel-feature representations, scalable kernel-based feature transformations, and dedicated datasets for data-driven, lightweight channel classification. To address this gap, the work introduces a controlled BLE measurement setup that generates labeled LOS/NLOS data in two distinct propagation environments. A quality-driven machine learning (ML)-based pipeline is then developed for BLE Constant Tone Extension (CTE) In-phase-Quadrature (IQ) features. First, robust quantile-based standardization is applied to reduce the influence of outliers and heavy-tailed effects. The standardized features are then analyzed using Principal Component Analysis (PCA) and Adaptive Kernel Density Estimation (AKDE) to verify scenario-dependent statistics and reveal LOS/NLOS separability. Next, Nyström Kernel Approximation (NKA) constructs low-rank nonlinear feature maps followed by a lightweight Support Vector Classifier (SVC) head for LOS/NLOS detection. This classifier is compared with Random Forest (RF) and Multilayer Perceptron (MLP) models. Results show that NKA improves accuracy by about 7-14% relative to the raw baseline. Although the MLP achieves higher absolute accuracy, the Nyström--SVC approach offers a more favorable trade-off between training complexity, inference cost, and memory footprint. Finally, several pipeline-calibrated posterior probabilities are utilized for cost-aware threshold selection and efficient real-time LOS/NLOS detection in resource-constrained localization systems.
### Title:
          GDGU: A Gradient Difference-based Graph Unlearning Method for Cyberattack Localization in Electric Vehicle Charging Networks
 - **Authors:** Nanhong Liu, Mucun Sun, Jie Zhang
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Electric vehicle charging stations (EVCSs) can expose distribution feeders to cyberattacks. While machine learning methods, including graph neural networks, can localize which bus is compromised, significant challenges remain in data sharing and model training. For example, privacy regulations grant EVCS owners the right to delete their training data from a deployed model, yet retraining from scratch on every request is computationally prohibitive. To address this, we study graph unlearning (GU) for EVCS cyberattack localization, formulated as a feature-level unlearning problem on a graph-level multi-label classification task. Specifically, we propose gradient difference-based graph unlearning (GDGU), which removes the influence of the requested deletion data through a first-order parameter correction. The correction is computed from the gradient difference between the original training data and a modified dataset in which only the charging power features at the requested EVCS buses are unlearned. Then, a batch-normalization recalibration and a brief recovery fine-tuning step are applied to restore localization utility. We benchmark GDGU against two second-order GU baselines on the IEEE 34-bus, 123-bus, and 8500-node distribution networks across three graph neural network backbones and cumulative unlearning scenarios. GDGU matches the strongest baseline on localization utility and reaches forgetting fidelity close to full-retraining, while unlearning 10 to 12 times faster than retraining from scratch and using far less memory than the second-order GU baselines.
### Title:
          Route-Constrained Robust Fusion Estimation for MEMS/GNSS Integrated Navigation of Unmanned Ground Vehicles in GNSS Degraded Environments
 - **Authors:** Jingzhi Cui, Chao Zhang, Yuliang Mao, Shaolin Lü, Dongmei Li, Huan Che, Rong Zhang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 To address cumulative localization drift of unmanned ground vehicles in structured road environments under severe Global Navigation Satellite System signal occlusion, this paper proposes a robust route-constrained state estimation method. During periods without satellite signals, the proposed method establishes the correspondence between the historical dead reckoning trajectory and local segments of the mission route extracted from a high-definition map, and estimates a route-referenced position via a two-dimensional rigid transformation. The estimated position is then formulated as a pseudo-position observation and incorporated into an Extended Kalman Filter update. In this way, route constraints at the road level can be continuously injected into a unified state estimation framework, thereby suppressing position deviation relative to the mission route while indirectly improving azimuth estimation. To enhance practical applicability, engineering strategies, such as trigger control, matching quality validation, route offset compensation, and single update correction limiting, are further introduced. Experiments in three representative scenarios, including a long tunnel, a multi-segment tunnel, and a curved tunnel, show that the proposed method effectively suppresses error accumulation during satellite outages, reduces the risk of large maximum deviation, and improves localization continuity and road-level usability.
### Title:
          NEST: Narrative Event Structures in Time for Long Video Understanding
 - **Authors:** Ali Asgarov, Kaushik Narasimhan, Najibul Haque Sarker, Hani Alomari, Chia-Wei Tang, Anushka Sivakumar, Zaber Ibn Abdul Hakim, Shaurya Mallampati, Chris Thomas
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent progress in vision-language models has enabled the processing of increasingly long video sequences, but the ability to handle extended token streams does not translate to understanding of narrative structure in long videos. Existing long video benchmarks focus on needle-in-a-haystack retrieval rather than evaluating how low-level actions form events, how events interact across time, and how narratives progress, for example, whether a model can connect an early setback, such as a job loss to a later relationship breakup, despite long gaps, intervening scenes, or flashbacks that reframe what occurred. We introduce NEST (Narrative Event Structures in Time for Long Video Understanding), a dataset of 1005 full-length movies (avg. 98 minutes), each annotated with 102 multimodal narrative events grounded in visual content, dialogue, and audio. NEST captures multimodal narrative events with structured annotations grounded in visual content, dialogue, and audio, and links them through relations that reflect narrative structure, including temporal ordering, hierarchical composition, and long-range dependencies. We introduce baselines for event trigger detection (ETD), event localization (EL), event argument extraction (EAE), and event relation extraction (ERE). The benchmark is highly challenging for grounded event discovery, with ETD below 8%, EL under 6%, and EAE below 11%. In contrast, ERE is more tractable once events are given, reaching 35.45% F1 zero-shot and 44.42% F1 after fine-tuning.
### Title:
          MMD-SLAM: Structure-Enhanced Multi-Meta Gaussian Distribution-Guided Visual SLAM
 - **Authors:** Fan Zhu, Ziyu Chen, Peichen Liu, Yifan Zhao, Zhisong Xu, Hui Zhu, Hongxing Zhou, Sixun Liu, Chunmao Jiang
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian Splatting (3DGS) has significantly boosted novel view synthesis and high-fidelity scene reconstruction, expanding the potential of 3DGS-based Visual Simultaneous Localization and Mapping (SLAM) methods. However, most existing systems fail to fully exploit the underlying structural information, which limits rendering quality and often leads to inconsistent maps. To address these limitations, we propose MMD-SLAM, a structure-enhanced Visual SLAM framework that leverages the Atlanta World (AW) assumption to guide a Multi-Meta Gaussian representation for photorealistic mapping. First, we introduce a point-line fusion strategy for pose optimization, where 3D line segments are incorporated to improve tracking robustness and provide additional constraints for mapping. Second, we design a Multi-Meta Gaussian representation with dominant directions, explicitly encoding structural priors from the AW hypothesis. Finally, we propose a Gaussian evolution strategy that adapts to scene geometry and incorporates structural cues into global optimization. Extensive experiments demonstrate that these innovations enable MMD-SLAM to achieve state-of-the-art performance in both tracking accuracy and mapping quality. e.g., our method achieves a 48.56% reduction in ATE RMSE on ScanNet and a 5.71% improvement in PSNR on Replica, compared with MonoGS.
### Title:
          Advancing DialNav through Automatic Embodied Dialog Augmentation
 - **Authors:** Leekyeung Han, Sangwon Jung, Hyunji Min, Jinseong Jeong, Minyoung Kim, Paul Hongsuck Seo
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 For embodied agents capable of physical interaction, the capability to create and understand dialog is crucial to ensure both safety and effectiveness. While DialNav~\cite{han2025dialnav} provides a framework for holistic evaluation of the dialog--execution loop in photorealistic indoor navigation, its performance remains limited by a critical scarcity of training data (2K episodes). To address this, we propose an automatic generation pipeline, and construct the \textbf{RAINbow} dataset, a large-scale training dataset with 238K episodes for DialNav. Our pipeline converts existing VLN datasets into multi-turn dialog and creates cost-efficient and high-quality dataset. Then, we introduce two additional complementary advances to unlock the data's full potential: (1) Dual-Strategy Training, a navigation training scheme to align the navigation training with the dynamic dialog-navigation loop, and (2) a localization model that leverages VLN knowledge. By combining these complementary solutions, our model substantially outperforms the baseline in success rate on both \textbf{Val Seen} (58.24, \textbf{+89\%}) and \textbf{Val Unseen} (29.05, \textbf{+100\%}) splits, establishing a new state of the art.
### Title:
          ReA-OVCD: Reliability-Aware Open-Vocabulary Change Detection via Semantic and Spatial Refinement
 - **Authors:** Hongming Zhu, Huaji Chen, Bowen Du, Sicong Liu, Qin Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unlike traditional remote sensing change detection that relies on predefined categories, Open-Vocabulary Change Detection (OVCD) identifies land cover changes flexibly using arbitrary text prompts. However, existing methods suffer from an inherent trade-off when modeling changes: instance-level comparison overlooks fine-grained semantic variations (e.g., partial building extensions), while direct pixel comparison proves unreliable, yielding unstable responses and boundary artifacts due to semantic ambiguity and spatial inconsistency. To this end, we propose an efficient training-free Reliability-Aware Open-Vocabulary Change Detection (ReA-OVCD) framework. It first derives candidate change regions from pixel-wise semantic discrepancies to ensure flexible and detailed localization. To ensure reliability, it subsequently introduces a collaborative refinement strategy to explicitly model change validity from both semantic and spatial perspectives. Specifically, we develop a Semantic Change Reasoning (SCR) module that reassesses changes by jointly analyzing distributional divergence and response variation, enabling the suppression of incidental inconsistencies while preserving reliable semantic shifts. In addition, a Boundary-aware Change Refinement (BCR) module is designed to mitigate artifacts stemming from boundary misalignment and uncertainty through validating whether candidate regions are supported by reliable interior pixels. Extensive experiments across multiple datasets (LEVIR-CD, WHU-CD, DSIFN, and SECOND) demonstrate that our method consistently outperforms state-of-the-art approaches, achieving $\mathrm{F}_{1}^{C}$ improvements of 2.13\% to 9.75\% with higher computational efficiency. The code is publicly available at \this https URL
### Title:
          Hybrid Diffusion Transformer for Instruction-Guided Audio Editing via Rectified Flow
 - **Authors:** Liting Gao, Yonggang Zhu, Yaru Chen, Dongyu Wang, Shubin Zhang, Zhenbo Li, Jean-Yves Guillemaut, Wenwu Wang
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Audio editing aims to modify specific content in an existing audio clip according to a natural language instruction while preserving the remaining acoustic content. Despite the remarkable progress of diffusion models, existing training-based editing methods mainly rely on the local inductive biases and cross-attention interaction in convolutional U-Net backbones, which often hinder long-range semantic alignment and precise understanding and localization of instructions. In contrast, diffusion transformers provide stronger global modeling and multimodal fusion, but existing editing architectures usually adopt a simple stack of MMDiT and DiT blocks. Applying joint attention over concatenated audio and text tokens in all blocks results in quadratic complexity with respect to token length. To balance editing performance and efficiency, we propose a hybrid two-stage diffusion transformer architecture for instruction-guided audio editing based on rectified flow matching. It performs joint attention over audio and text tokens to establish coarse semantic alignment at low-resolution stage, then switches to alternating joint-attention and cross-attention blocks to refine editing details at high-resolution stage. This coarse-to-fine strategy enables efficient and accurate instruction-guided audio editing. Experiments show that the proposed framework achieves notable performance gains on challenging editing tasks involving overlapping audio events and complex instructions, while substantially improving editing efficiency with a compact model.
### Title:
          Phoenix: Safe GitHub Issue Resolution via Multi-Agent LLMs
 - **Authors:** Kipngeno Koech, Muhammad Adam, Baimam Boukar Jean Jacques, Joao Barros
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Phoenix, a multi-agent LLM system that resolves GitHub issues from triage through pull-request creation, combining seven layered safety controls with a baseline-aware test evaluation strategy. Phoenix decomposes the work across six specialized agents. Planner, reproducer, coder, tester, failure analyst and Pull Request (PR) agent, all coordinated by a label-based GitHub webhook state machine. Every change is checked against a baseline test run before a pull request is opened. On a 24-instance slice of SWE-bench Lite. run on the production webhook path, Phoenix oracle-resolves 75% of instances with no pass-to-pass regressions on successful runs; this curated slice is not directly comparable to full-split leaderboard results, and we discuss the limits of the comparison. A complementary pilot on 42 real issues across 14 repositories yields 100% correctness preservation (CP; mean 122s on the hard tier). Manual inspection shows that about half of the resulting pull requests are well-targeted fixes. The other half place code at incorrect paths, a planner localization limitation we are addressing with retrieval. We also report the deployment failure modes (WAF filtering, token expiry, permission boundaries, flaky CI) that motivated each safety mechanism.
### Title:
          Quantum-classical physics-informed Kolmogorov-Arnold networks for PDEs
 - **Authors:** Xiang Rao, Yuxuan Shen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computational Physics (physics.comp-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We develop QCPIKAN, the first quantum-classical physics-informed Kolmogorov-Arnold network designed to solve partial differential equations (PDEs). Built upon Chebyshev-polynomial KAN layers and parameterized quantum circuits, this hybrid framework embeds physical constraints into the training loss to enforce physical consistency. Our theoretical investigations grounded in approximation theory prove that this design accelerates high-frequency error convergence to an exponential rate and effectively mitigates numerical dispersion. We validate the framework across three typical seepage scenarios in porous media, including single-phase flow, component transport and two-phase flow. Compared with existing quantum-classical physics-informed neural networks, QCPIKAN achieves superior performance in global prediction accuracy, local error control, dynamic evolution tracking and displacement front localization. This work provides a robust and efficient alternative for solving complex PDEs.
### Title:
          ARC: Adaptive Robust Joint State and Covariance Estimation
 - **Authors:** Alexandre Hadji-Thomas, Andrew Stirling, James R. Forbes
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sensor measurements are frequently corrupted by outliers and non-Gaussian noise. These imperfections in the sensor data can cause classical state estimators to generate biased and unreliable state and uncertainty estimates. Robust estimators reject or downweight outliers but do not perform measurement covariance estimation, whereas joint state and covariance estimators assume Gaussian residuals and fixed loss shape parameters. Integrating these two capabilities into a single framework is an opportunity to simultaneously estimate both state and covariance in the presence of outliers. This paper proposes a unified Block-Coordinate Descent framework that combines a norm-aware adaptive robust loss, an Iteratively Reweighted Least-Squares state update, and a Minimum Weighted Covariance Determinant covariance estimator, yielding a self-tuning joint state and covariance estimator. The framework is evaluated in a Monte-Carlo simulation and on real-world ultra-wideband localization experiments in cluttered non-line-of-sight environments. Results show that the proposed estimator consistently recovers the true inlier measurement covariance and matches or exceeds the state estimation accuracy of all baselines, without requiring any manual parameter tuning.
## Keyword: transformer
### Title:
          Weibull Weight-Scale Parameter Evolution under AdamW Training Dynamics
 - **Authors:** Tiexin Ding
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Building on a two-parameter Weibull framework for diagnosing transformer weight distributions, we study why the Weibull weight-scale parameter $\lambda$ grows, overshoots, and then relaxes during AdamW training. We derive a leading-order three-force decomposition of the squared weight norm from the AdamW update: an alignment force measuring the correlation between weights and the adaptive update direction, an injection force from adaptive step magnitude, and a decay force from decoupled weight decay. On self-trained Pythia-70M models with ground-truth optimizer moments, alignment dominates the rise phase, contributing 88-94% of the absolute force budget across four random seeds and remaining robust to super-weight removal. Near saturation, alignment and decay approach balance, explaining the transition from weight-scale growth to relaxation. These force dynamics directly govern the squared-norm component underlying $\lambda(t)$; the remaining RMS-to-Weibull reconstruction offset is measurable and decomposes into bridge and integration components, totaling approximately 5-6% in densely sampled regions. To extend the analysis to real models where optimizer moments are unavailable, we introduce a spline displacement method that recovers the alignment force from sparse checkpoints with approximately 92-94% accuracy, about twice the naive two-point baseline. We further observe that the peak value of $\lambda(t)$ varies with training-data coherence in our experiments, suggesting a data-dependent component of weight-scale growth that we leave to a controlled follow-up study. Code and data are available at this https URL.
### Title:
          Emyx: Fast and efficient all-atom protein generation
 - **Authors:** Nicholas J. Williams, Ward Haddadin, Matteo P. Ferla, Constantin Schneider, Nicholas B. Woodall, Ruby Sedgwick, Christian D. Madsen, Andrew L. Hopkins, Edward O. Pyzer-Knapp
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Computational enzyme design requires generating proteins that scaffold catalytic residues and ligands, a task that demands both geometric accuracy and structural diversity from the underlying generative model. Current all-atom generators inherit expensive architectures from structure prediction, leading to high training costs and limited sample diversity. We argue that much of this complexity is unnecessary for generators, which condition on sparse geometric constraints rather than rich co-evolutionary signals. Emyx is a 140M-parameter conditional flow matching model that concentrates capacity within standard transformer blocks, replacing heavy embedding stacks with lightweight conditional representations and sparse connectivity. We additionally derive an exact reparametrisation of the flow matching interpolant into the EDM noise-level framework, bridging flow matching training efficiency with state-of-the-art sampling methods designed for diffusion models without retraining. Despite being the smallest model, Emyx outperforms both Proteína-Complexa and RFdiffusion3 against the AME enzyme design benchmark across success rate under strict evaluation requiring both global fold recovery and catalytic geometry accuracy, structural novelty, scaffold diversity, and geometric validity, while training in just $682$ GPU-hours, roughly $4\times$ less than RFdiffusion3.
### Title:
          How Linear Is a Transformer Feed-Forward Block? Per-Block Linear Recoverability Is Learned, Not Architectural
 - **Authors:** Stuart Whipp
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer feed-forward networks (FFNs) are often treated as nonlinear stores of computation, yet how nonlinear a trained FFN block actually is has rarely been measured. We treat each FFN as a position-wise input-to-output map and split it into the exact least-squares linear approximation plus a residual. The held-out variance the closed-form linear map explains defines a block's linear recoverability (R^2_lin), an optimiser-free measure of its linearity. Across all twelve blocks of GPT-2, Pythia-160m, and llama-160m, R^2_lin is highly heterogeneous and non-monotone with depth, ranging from near-linear (>0.99) to strongly nonlinear (<0.3) between adjacent blocks, and is not set by the activation function: same-width GELU models GPT-2 and Pythia-160m have sharply different profiles, so recoverability is a learned property of individual trained blocks, not an architectural one. A low-rank bilinear probe of the residual recovers only a few points of R^2, with gain uncorrelated with residual nonlinearity: the unrecovered computation is not a single position-wise product but higher-order or distributed structure. The measurement also serves as a targeted compression signal: recoverable blocks admit large single-layer replacements (GPT-2's early FFN at 8x fewer parameters for +0.77 perplexity), while low-recoverability blocks flag where this is unsafe. It further exposes a methodological pitfall: trained linear baselines can badly under-converge on ill-conditioned transformer activations, so we report the exact closed-form least-squares ceiling throughout.
### Title:
          S-JEPA : Soft Clustering Anchors for Self-Supervised Speech Representation Learning
 - **Authors:** Georgios Ioannides, Adrian Kieback, Judah Goldfeder, Linsey Pang, Aman Chadha, Aaron Elkins, Yann LeCun, Ravid Shwartz-Ziv
 - **Subjects:** Subjects:
Sound (cs.SD); Audio and Speech Processing (eess.AS); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-supervised speech encoders are predominantly trained by predicting discrete hard cluster IDs at masked positions, a recipe that collapses acoustic ambiguity at category boundaries and requires interrupting training to re-cluster the entire corpus between iterations. We introduce S-JEPA, a JEPA-style encoder-predictor pair trained to match the soft posteriors of a Gaussian Mixture Model at masked positions via KL divergence. Training runs as one continuous optimization trajectory in two phases: a fixed GMM over MFCC features, then an online GMM over encoder features, with the input layer selected adaptively from a label-free signal, removing both the offline re-cluster step and the hand-tuned choice of which transformer layer to cluster on. Under the SUPERB protocol, S-JEPA achieves the lowest WER among evaluated SSL methods below 90M parameters and matches HuBERT-Base on emotion recognition at roughly half its parameter count, establishing a new Pareto frontier without offline re-clustering or teacher distillation. An analysis of the predictor's per-frame entropy on held-out speech reveals a bimodal distribution with a substantial minority of frames near the entropy of a perfect two-cluster tie, providing direct empirical evidence that the soft-target objective preserves the acoustic ambiguity that hard targets would collapse. Code is available at this https URL.
### Title:
          LEAP: Layer-skipping Efficiency via Adaptive Progression for Vision Transformer Distillation
 - **Authors:** Jiaqi Zhang, Ashton Lee, Anthony Wong, John Zou, Sami BuGhanem, Randall Balestriero
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Foundation Models (VFMs) with Vision Transformer (ViT) backbones, such as DINOv2, have become essential for downstream tasks like object recognition and semantic segmentation. The immense computational requirements of backbones often necessitate distillation into smaller architectures for edge deployment. Feature-based knowledge distillation (KD) often suffers from the teacher-student gap; the student struggles to imitate teacher's complex feature map due to its limited capacity. To mitigate this bottleneck, we propose LEAP: Layer-skipping Efficiency via Adaptive Progression, a training curriculum for ViT feature-based knowledge distillation. By utilizing the teacher's intermediate feature maps as a sequence of progressively more difficult targets, our curriculum allows the student to build a foundational representation before tackling higher-level abstractions. Our results demonstrate that this paradigm significantly accelerates convergence through adaptive difficulty selection across various student model sizes and dataset scales. With our curriculum, the LEAP-distilled ViT-S achieves 90.1% accuracy on ImageNet-100, a +12.24% improvement compared with baseline. On ImageNet-1K, LEAP achieves +3.84% and +7.75% improvement for the instance retrieval task on the Oxford and Paris datasets, respectively. Furthermore, the curriculum enables 25.1% savings in training FLOPs and 21% savings in training time on ImageNet-100 by implementing early-stopping for teacher inference during the initial stages of training. Code is available at this https URL
### Title:
          Algebraic Dead Directions in LayerNorm Transformers: A Forward-Pass-Only Diagnostic at LLM Scale
 - **Authors:** Tejas Pradeep Shirodkar, P. J. Narayanan
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pretrained transformers sit near singular minima of the loss, where the Fisher information metric degenerates along dead directions: directions in parameter space along which the directional Fisher vanishes. Locating such a direction normally needs a forward pass and an eigendecomposition of activations, or a sampling-based complexity estimate; none returns a direction computable from the network's parameters alone. We give one, for LayerNorm transformers. The inverse-scale direction $\gamma^{-1}/\|\gamma^{-1}\|$ of the LayerNorm affine is an exact algebraic kernel of the post-final-norm centred activation covariance, for any input distribution, and induces a corresponding dead direction in parameter space. It is read from the LN scale parameter alone, with no forward or backward pass and no eigensolve: the cheapest dead-direction read, specific to LayerNorm. We test it on $14$ pretrained transformers ($9$ LayerNorm, $5$ RMSNorm; $160$M-$35$B; language and vision objectives). At random initialisation the predicted direction matches the measured bottom singular direction (one forward pass, direct SVD) to four decimal places on $9/9$ LayerNorm models, and is correctly absent on $5/5$ RMSNorm models, which lack the mean-subtraction projector that creates it. On the trained checkpoint the covariance eigenvalue along this direction deepens by ${\sim}10^3\times$ and further dead directions open; the random-init-to-trained gap is a one-forward-pass, per-checkpoint readout of singular structure along the predicted coordinate. Two consequences follow in closed form: the residual stream's smallest singular value is preserved block-to-block on $13/14$ transformers measured on their own input distribution, the one exception (Gemma$4$-$31$B) a genuine dead direction the same read pinpoints; and the kernel direction's presence classifies a transformer's normalisation from the parameters alone.
### Title:
          ITNet: A Learnable Integral Transform That Subsumes Convolution, Attention, and Recurrence
 - **Authors:** Ashim Dhor, Rasel Mondal, Pin Yu Chen
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Convolutional networks, recurrent networks, and transformers each encode different inductive biases -- locality, sequential memory, and content-dependent pairwise interaction -- and have remained mathematically distinct since their inception. We show that this fragmentation reflects not a fundamental diversity in how signals should be processed, but rather incomplete views of a single underlying mathematical object: a learnable integral transform. We introduce the Integral Transform Network (ITNet), a unified architecture built around a learnable kernel that depends jointly on positions and features. This kernel is implemented as a small neural network, specifically an MLP, that models pairwise interactions, enabling the model to adapt its behavior from data. We show that convolution, self-attention (including multi-head), and autoregressive recurrence (including LSTM, GRU, S4, and Mamba) arise as special cases under appropriate parameterizations, and that ITNet is a universal approximator of continuous operators. To make this practical, we develop tiled kernel fusion, importance-weighted Monte Carlo integration, and learned low-rank factorization, enabling efficient and scalable computation. A single ITNet architecture with a shared operator and lightweight modality-specific encoders matches or exceeds specialized baselines on ImageNet-1K , GLUE, ModelNet40, VQA\,v2 and NLVR2. The results demonstrate that a single learned interaction mechanism can recover the behavior of all three architectural families from data.
### Title:
          Tracking Representation Dynamics in Large Language Models with Persistent Homology
 - **Authors:** Naman Malhotra, Jay Ambadkar, Abhinav Gupta, Kushal Kasivel, Abbas Schwarz, Kamillo Ferry, Anthea Monod
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models are commonly aligned through supervised fine-tuning, yet little is known about how their internal representations evolve during this process. We study alignment dynamics using persistent homology by tracking the topology of activation spaces throughout fine-tuning. Across four transformer language models ranging from 1B to 7B parameters and three alignment objectives corresponding to helpful, harmless, and mixed training data, we find that the majority of topological reorganization occurs during the earliest stages of training. A dense checkpoint analysis reveals a transient peak in topological activity followed by rapid stabilization. We further show that different alignment objectives induce distinguishable topological trajectories, while instruction-tuned and pretrained models exhibit qualitatively different patterns of evolution. Our results suggest that persistent homology provides a complementary perspective on alignment, revealing representation-level changes that are not apparent from behavioral metrics alone.
### Title:
          Understanding Key Features of Time Series Foundation Models from Epidemic Forecasting
 - **Authors:** Alireza Jafari, Judy Fox, Geoffrey C. Fox, Madhav Marathe, Aniruddha Adiga
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Seasonal influenza infects millions of people and causes substantial morbidity and mortality in the United States each year, making accurate short-term forecasting a core public-health need. Reliable forecasts of epidemic time series can inform vaccination timing, hospital staffing, and resource allocation, yet the comparative behavior of modern forecasting architectures on infectious-disease surveillance data remains insufficiently characterized. We address this gap through a systematic evaluation of regional influenza forecasting using influenza-like illness surveillance and influenza-associated hospitalization time series under both temporal and spatial generalization settings for 1-4-week-ahead prediction. We compare classical neural network architectures, numerical transformer-based models, pretrained time series foundation models, and LLM-based forecasting approaches. Across tasks, we demonstrate that a mixture-of-experts model that fuses multiple pretrained forecasters achieves the strongest overall performance, indicating that heterogeneous pretrained representations provide complementary predictive information. Our results further show that numerical transformer-based models produce reliable forecasts, while pretraining provides the largest gains at longer horizons, particularly when the pretraining domain is mechanistically aligned with influenza dynamics. In contrast, LLM-based time series methods underperform relative to numerical forecasters in this setting. Finally, we examine hospitalization information as both an auxiliary covariate and a pretraining source. Hospitalization signals provide complementary improvements in selected settings and clarify when additional surveillance streams enhance the robustness of multi-horizon forecasting. These findings provide actionable guidance on model selection, pretraining strategy, and auxiliary-signal use for influenza preparedness.
### Title:
          Token Factory: Efficiently Integrating Diverse Signals into Large Recommendation Models
 - **Authors:** Xilun Chen, Shao-Chuan Wang, Baykal Cakici, Lukasz Heldt, Lichan Hong, Raghu Keshavan, Aniruddh Nath, Li Wei, Xinyang Xi
 - **Subjects:** Subjects:
Information Retrieval (cs.IR); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Recommendation Models (LRMs) have demonstrated promising capabilities in industry-scale recommendation tasks. However, holistically integrating traditional signals into these transformer-based architectures effectively and efficiently remains a major challenge. Conventional approaches that "textualize" these signals directly or create discrete item representations often lead to excessively long prompts, substantial memory footprints, and high computational overhead. To overcome these limitations, we propose "Token Factory", a framework designed to transform traditional signals into "soft tokens" that can be directly processed by LRMs. This approach enables efficient integration and compression of heterogeneous input features, preventing prompt length explosion while enhancing model performance. We detail the architecture of Token Factory and present experimental results validating its effectiveness in a production-scale recommendation environment.
### Title:
          BrainG3N: A Dual-Purpose Tokenizer for Controllable 3D Brain MRI Generation
 - **Authors:** Max Van Puyvelde, Ibrahim Gulluk, Wim Van Criekinge, Olivier Gevaert
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Three-dimensional (3D) brain MRI is central to clinical neurology and neuro-oncology, where generative models could augment under-represented cohorts, simulate disease trajectories, and support privacy-preserving data sharing. Latent diffusion has been the go-to solution for modeling imaging data, but it places two competing demands on the tokenizer: encoder embeddings must retain the clinical information that downstream tasks act on, and the decoder must reconstruct anatomically faithful volumes. Existing reconstruction-driven tokenizers achieve the second at the expense of the first. To address this, we introduce a fully volumetric masked-autoencoder (MAE) based tokenizer for 3D brain MRI latent diffusion, decoupling encoder and decoder: a frozen 3D MAE encoder produces clinically informative embeddings, while a dedicated CNN decoder reconstructs voxels from a linear projection of those embeddings. We pretrain the encoder on 35,309 volumes from 18 public cohorts spanning four modalities, ten disease categories, and 200+ acquisition sites, and demonstrate its dual utility in two settings. First, on a 23-task linear-probing benchmark, the encoder outperforms or matches SOTA models (i.e., BrainIAC, BrainSegFounder, and MedicalNet) on 21 of 23 tasks. Second, a conditional diffusion transformer (DiT) trained on these clinically informative embeddings supports both conditional generation across six variables and patient-specific longitudinal forecasting. Together these results establish a single 3D brain-MRI embedding space capable of both downstream clinical tasks and controllable generation.
### Title:
          Efficiently Representing Algorithms With Chain-of-Thought Transformers
 - **Authors:** Yanhong Li, Anej Svete, Ashish Sabharwal, William Merrill
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The increasing popularity of \emph{reasoning} models -- language models that output a series of reasoning or thought tokens before producing an answer -- is justified, in part, by theoretical results showing that chain-of-thought (CoT) transformers can simulate Turing machines, and thus perform arbitrary computation. However, the Turing machine, while suitable for complexity-theoretic analysis, is not convenient, intuitive, or efficient for discussing algorithms. Algorithms are typically designed and analyzed at a higher level of abstraction, captured by the \emph{Word RAM} model with random-access memory and unit-cost operations on $\bigO(\log n)$-bit words. As a result, Word RAM algorithms can be substantially more efficient than their Turing machine counterparts, raising the question: \emph{Can CoT transformers efficiently simulate Word RAM algorithms?} For instance, can they sort $n$ items in $\bigO(n \log n)$ steps or run Dijkstra's algorithm in $\bigO(E + V \log V)$ steps? We answer affirmatively, up to poly-logarithmic overhead. We first establish this for finite-precision transformers with poly-logarithmic width and rightmost unique hard attention, then strengthen the result to two more practical settings with finite width and log-precision: \emph{continuous} CoT, where reasoning takes the form of vectors rather than tokens, and a \emph{hybrid} architecture in which transformer layers sit atop a recurrent (linear RNN) layer. In all three cases, we find that CoT \emph{can} efficiently simulate any Word RAM algorithm with only a poly-logarithmic overhead in $n$. This overhead reduces to log-square when the Word RAM has a ``flat'' instruction set, and only logarithmic for multiplication-free flat instructions -- in stark contrast to known CoT simulations of Turing machines, which require quadratic overhead over Word RAM.
### Title:
          OnDeFog: Online Decision Transformer under Frame Dropping
 - **Authors:** Daiki Yotsufuji, Kenta Nishihara, Shoma Shimizu, Kento Uchida, Shinichi Shirakawa
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In challenging real-world reinforcement learning applications, communication delays or sensor failures often cause frame dropping, in which the agent cannot receive the dropped states and associated rewards. To address the performance degradation caused by frame dropping, the Decision Transformer under Random Frame Dropping (DeFog) was developed by incorporating additional mechanisms into the decision transformer to tackle frame dropping. Although DeFog can mitigate performance degradation in frame-dropping environments, since DeFog is an offline learning method, it struggles to effectively generalize to novel states not adequately represented in the training dataset. In this study, we propose OnDeFog, which integrates the mechanisms in DeFog with the online decision transformer (ODT), an online reinforcement learning method that learns policies through direct environmental interaction. Comprehensive experimental evaluation demonstrates that our proposed OnDeFog achieves superior performance compared to ODT in environments characterized by high dropping frame rate and outperforms DeFog on datasets containing a large amount of low-reward data.
### Title:
          A Comparative Study of Pretrained Transformer Models for Quranic ASR: Speech Representations, Label Formats, and Dataset Composition
 - **Authors:** Nabil Mosharraf Hossain (1), Riasat Islam (1 and 2), Unaizah Obaidellah (3) ((1) Greentech Apps Foundation, United Kingdom, (2) Queen Mary University of London, United Kingdom, (3) University of Malaya, Malaysia)
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Quran Automatic Speech Recognition (ASR) aims to convert Quranic recitation into text, enabling applications such as aided memorisation tools and Quranic search engines. However, existing ASR models often exhibit high Word Error Rates (WER) on user-recited verses and lack full coverage of the Quranic corpus. This paper presents a systematic empirical study of domain-specific fine-tuning of pretrained Transformer-based models for Quranic ASR, using advanced speech feature extraction methods: Wav2Vec2.0, HuBERT, and XLS-R. These models apply self-supervised learning by masking portions of input audio and using Transformer architectures to learn context-aware speech features. The pretrained models are fine-tuned on a filtered Quranic dataset exceeding 870 hours of professional and user recitations. Through comprehensive ablation studies across feature extractors, output label formats, training strategies, and clip durations, we identify the key factors that affect transcription accuracy in this domain. Our best-performing configuration achieves a WER of 0.08 on the EveryAyah subset and 0.11 on the combined EveryAyah+Tarteel setting, representing roughly a five-percentage-point gain over the Citrinet baseline (WER = 0.163) while reducing combined-model training time from 140 hours to 40 hours. Arabic text without diacritics yields the best fine-tuning results, and Wav2Vec2-XLSR-53 provides the strongest overall representation. Future work includes improving dataset quality and developing phoneme-aware models to extract deeper speech feature representations for Tajweed-sensitive applications.
### Title:
          EquiVLA: A General Framework for Rotationally Equivariant Vision-Language-Action Models
 - **Authors:** Thien-Loc Ha, Quang-Tan Nguyen, Trong-Bao Ho, Long Dinh, Minh Duc Nguyen, Gia-Binh Nguyen, Pham Tri Quang, Minh N. Vu, Duy M. H. Nguyen, An Thai Le, Ngo Anh Vien
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models have emerged as a powerful paradigm for generalist robot manipulation, yet they lack geometric inductive biases: policies trained at specific orientations require substantially more data to generalize across rotational configurations. We present \textsc{EquiVLA}, the first general framework for end-to-end $\mathrm{SO}(2)$-equivariant VLA models, applicable to any architecture coupling a frozen vision-language backbone with a flow-matching Diffusion Transformer action head. \textsc{EquiVLA} introduces \textsc{EquiPerceptor}, which produces approximately $\mathrm{SO}(2)$-equivariant visual representations from frozen ViT features; and \textsc{EquiActor}, an exactly $\mathrm{SO}(2)$-equivariant flow-matching Diffusion Transformer action head. Together, they establish an approximate $\mathrm{SO}(2)$ equivariance chain from camera observations to predicted action sequences. Instantiated on GR00T~N1.5 and evaluated across four LIBERO suites, CALVIN ABCD$\to$D, and five real-robot tasks on Mobile ALOHA, \textsc{EquiVLA} achieves $92.6\%$ average success on LIBERO (vs. $78.1\%$ baseline), an average sequence length of $4.03$ on CALVIN (vs. $3.45$), and improves real-robot success from $54\%$ to $72\%$.
### Title:
          CSWinUNETR: Segmentation of Thin Anatomical Structures in Medical Images
 - **Authors:** Junho Moon, Haejun Chung, Ikbeom Jang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate segmentation of thin, tortuous anatomical structures, such as retinal vessels, cerebral vasculature, and facial wrinkles, remains challenging due to low contrast, frequent discontinuities, and severe class imbalance. Although recent convolutional and Transformer-based models have improved performance, they often yield fragmented predictions and fail to recover fine branches. We propose CSWinUNETR, a general-purpose backbone for 2D and 3D thin-structure segmentation. It employs cross-shaped stripe self-attention to model long-range principal-axis context and incorporates cyclic shifts to enhance information exchange across stripes. To better preserve fine-grained details, we further introduce a detail-enhanced multi-scale self-attention module that aggregates contextual features from multi-resolution representations. In addition, we propose sparse-control dynamic snake convolution, which reconstructs reliable dense curvilinear kernels from sparsely predicted control points to better follow tortuous geometry. Extensive experiments on four benchmarks across ophthalmology, neurovascular imaging, and dermatology demonstrate that CSWinUNETR consistently outperforms state-of-the-art methods without task-specific post-processing or topology-aware losses. The code is available at this https URL.
### Title:
          Gaussian Process Prior Variational Autoencoder for Endoscopic Videos
 - **Authors:** Ivan De Boi, Xinxing Shi, Xiaoyu Jiang, Tim J.M. Jaspers, Francisco Caetano, Mauricio A. Alvarez, Fons van der Sommen, Sam Van der Jeught
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Endoscopic video analysis is essential for gastrointestinal diagnosis and computer-assisted interventions, but video sequences are routinely degraded by specular reflections, motion artifacts, and missing frames. These transient corruptions can distract clinicians, reduce image interpretability, and disrupt downstream tasks such as 3D reconstruction and navigation. Effective restoration therefore requires methods that exploit temporal continuity rather than treating frames in isolation. We introduce a Gaussian Process Prior Variational Autoencoder (GPVAE) framework for endoscopic video restoration that replaces the standard factorized latent prior with a temporal Gaussian process prior, enabling interpolation of missing frames with uncertainty-aware reconstruction. The framework combines endoscopy-specific encoders, including a convolutional EndoVAE backbone and pretrained Vision Transformer encoders from GastroNet-5M, with two scalable GP approximations: Hierarchical Prior Approximation (HPA) and Sparse Precision Approximation (SPA). Specular reflections are handled using a DUCKNet-based masking pipeline that excludes corrupted pixels from the reconstruction objective. On the C3VDv2 colonoscopy dataset, the best GPVAE variants reduced image reconstruction RMSE by 21.9\% on average, and by up to 26.1\%, relative to matched VAE baselines. Downstream trajectory RMSE was reduced by 12.7\% on average across classical visual odometry and a pretrained PoseNet, at an average increase of 27.3\% in training time per epoch. Finally, the GP posterior provides per-frame uncertainty estimates that reflect temporal support and offer a confidence signal for restored frames.
### Title:
          QG-MIL: A Gated Transformer Aggregator for Domain-Agnostic Multiple Instance Learning in Medical Imaging
 - **Authors:** Luca Zedda, Davide Antonio Mura, Cecilia Di Ruberto, Maurizio Atzori, Muhammed Furkan Dasdelen, Carsten Marr, Andrea Loddo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Attention-based Multiple Instance Learning aggregators in medical imaging are prone to attention concentration, producing overconfident and unstable predictions. We introduce QG-MIL, a gated transformer aggregator that addresses this through four synergistic architectural components: RMSNorm-based pre-normalization, per-head QK normalization, fine-grained attention output gating, and SwiGLU-style feed-forward modules. Together, these design choices stabilize training and distribute attention more uniformly across instances without auxiliary losses, masking, or multi-stage regularization. We evaluate QG-MIL across six benchmarks spanning whole-slide pathology and cell-level hematology, covering two fundamentally different MIL scales. The best-performing QG-MIL variants outperform leading baselines on all six benchmarks, with an average improvement of +6.1 mean macro F1 points. Attention overlays and attention mass analysis confirm more distributed instance weighting. Ablation studies show that while individual components can match the full model on specific datasets, the QG-MIL design provides the most consistent cross-domain performance and tightest variance when compared to selected baselines. We release a configurable implementation to support reproducibility at: this https URL
### Title:
          PaAno+: Multiscale Encoding and Cross-Variable Attention for Time Series Anomaly Detection
 - **Authors:** Youji Zhu, Hongbing Wang, Wenchao Liu, Xiaodong Liu, Xiangguang Xiong
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Time-series anomaly detection has significant practical value for industrial and medical monitoring, as well as other critical domains. Current Transformer- and large-model-based detection approaches incur excessive computational overhead, while existing lightweight alternatives are constrained by insufficient feature extraction and inadequate modeling of dependencies across multivariate variables. To mitigate the above drawbacks, this study develops a lightweight, efficient anomaly detection model, dubbed PaAno, within the patch-oriented representation learning paradigm. In the encoder module, a multiscale feature-extraction backbone is constructed using convolutional kernels with differentiated receptive fields to capture hierarchical temporal characteristics; subsequent cross-scale adaptive attention aggregation, combined with residual connection optimization, further stabilizes feature representation learning. A cross-variable fusion attention module is embedded to explicitly characterize inter-variable correlations, empowering the model to identify anomalous patterns amid intricate operational conditions. Moreover, a novel pretext task based on temporal patch-window sorting is customized to uncover intrinsic structural properties of time series, and triplet loss is leveraged to optimize the patch embedding space for enhanced feature discrimination. Extensive experiments on the TSB-AD benchmark demonstrate that the proposed PaAno achieves state-of-the-art detection accuracy on both univariate and multivariate tasks, yielding significant performance gains across evaluation metrics, including VUS-PR, relative to the original PaAno. Leveraging a compact network design, the presented model achieves favorable computational efficiency, enabling deployment on resource-limited terminals for real-time anomaly inference.
### Title:
          Variable-Length Tokenization via Learnable Global Merging for Diffusion Transformers
 - **Authors:** Dong Hoon Lee, Seunghoon Hong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Latent Diffusion Models (LDMs) have become dominant in visual synthesis, but their quality-compute trade-off is largely constrained by the tokenizer's fixed compression ratio. Variable-length tokenizers (VLTs) promise adaptive compression by varying token counts, allowing diffusion models to flexibly balance quality and compute. However, conventional VLTs modulate length by truncating ordered token sequences, which makes token semantics depend on token position and breaks representational alignment across lengths. This leads to a cross-length shift in the latent distribution that hinders a single variable-length diffusion model from operating effectively. To address this, we propose a novel variable-length tokenizer that modulates length by merging tokens. We show that encouraging similar tokens to merge enables direct cross-length representation alignment when the diffusion transformer operates according to the merging pattern. Since conventional merging methods are data-dependent, making the merging pattern inaccessible during generation, we introduce learnable global merging, which is data-independent, to ensure compatibility with diffusion transformers. On ImageNet 256$\times$256 generation, our merging-based variable-length tokenizer integrated with a diffusion transformer achieves a superior gFID-compute trade-off compared to prior VLT methods. Code is available at [this https URL](this https URL)
### Title:
          Hybrid Diffusion Transformer for Instruction-Guided Audio Editing via Rectified Flow
 - **Authors:** Liting Gao, Yonggang Zhu, Yaru Chen, Dongyu Wang, Shubin Zhang, Zhenbo Li, Jean-Yves Guillemaut, Wenwu Wang
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Audio editing aims to modify specific content in an existing audio clip according to a natural language instruction while preserving the remaining acoustic content. Despite the remarkable progress of diffusion models, existing training-based editing methods mainly rely on the local inductive biases and cross-attention interaction in convolutional U-Net backbones, which often hinder long-range semantic alignment and precise understanding and localization of instructions. In contrast, diffusion transformers provide stronger global modeling and multimodal fusion, but existing editing architectures usually adopt a simple stack of MMDiT and DiT blocks. Applying joint attention over concatenated audio and text tokens in all blocks results in quadratic complexity with respect to token length. To balance editing performance and efficiency, we propose a hybrid two-stage diffusion transformer architecture for instruction-guided audio editing based on rectified flow matching. It performs joint attention over audio and text tokens to establish coarse semantic alignment at low-resolution stage, then switches to alternating joint-attention and cross-attention blocks to refine editing details at high-resolution stage. This coarse-to-fine strategy enables efficient and accurate instruction-guided audio editing. Experiments show that the proposed framework achieves notable performance gains on challenging editing tasks involving overlapping audio events and complex instructions, while substantially improving editing efficiency with a compact model.
### Title:
          Pixel-Level Residual Diffusion Transformer: Scalable 3D CT Volume Generation
 - **Authors:** Zhenkai Zhang, Markus Hiller, Krista A. Ehinger, Tom Drummond
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generating high-resolution 3D CT volumes with fine details remains challenging due to substantial computational demands and optimization difficulties inherent to existing generative models. In this paper, we propose the Pixel-Level Residual Diffusion Transformer (PRDiT), a scalable generative framework that synthesizes high-quality 3D medical volumes directly at voxel-level. PRDiT introduces a two-stage training architecture comprising 1) a local denoiser in the form of an MLP-based blind estimator operating on overlapping 3D patches to separate low-frequency structures efficiently, and 2) a global residual diffusion transformer employing memory-efficient attention to model and refine high-frequency residuals across entire volumes. This coarse-to-fine modeling strategy simplifies optimization, enhances training stability, and effectively preserves subtle structures without the limitations of an autoencoder bottleneck. Extensive experiments conducted on the LIDC-IDRI and RAD-ChestCT datasets demonstrate that PRDiT consistently outperforms state-of-the-art models, such as HA-GAN, 3D LDM and WDM-3D, achieving significantly lower 3D FID, MMD and Wasserstein distance scores.
### Title:
          Effective Dimension Governs Generalization in Quantum Kernel Vision Models
 - **Authors:** Jian Xu, Delu Zeng, John Paisley, Qibin Zhao
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent quantum vision models-quantum vision transformers and quantum convolutional networks-report two striking but unexplained empirical phenomena: (i) ansatze with more, or more uniformly distributed, entanglement generalize better, and (ii) injecting quantum noise can improve test accuracy rather than degrade it. These observations are currently treated as curiosities, discovered by grid search and explained, if at all, by hand. We show that both are manifestations of a single, measurable quantity: the \emph{effective dimension} $d_{\rm eff}$ of the (noise-shaped) quantum feature kernel. Working primarily with quantum-kernel vision models-a quantum feature map read out by a kernel classifier-we give a spectral account in which entanglement structure and quantum noise are two knobs that move $d_{\rm eff}$; in an overfitting regime, contracting $d_{\rm eff}$ acts as ridge-like regularization. We analyze the mechanism: an \emph{exact} decomposition of the depolarized kernel $K_p=(1-p)^2K+\tfrac{p(2-p)}{D}\mathbf{1}\mathbf{1}^\top$ with $d_{\rm eff}(K_p)\to1$, a contraction result (and its boundary) for amplitude damping, a kernel-machine capacity bound, and a capacity/alignment risk decomposition; the monotone contraction operative in our entangled experiments is verified empirically, not proven in general. Along the one-parameter depolarizing family the collapse is instead exact by construction; we use it only to confirm the kernel decomposition to machine precision and at up to $12$ qubits, not as evidence for $d_{\rm eff}$. Amplitude damping contracts $d_{\rm eff}$ and lifts test accuracy by up to $+13\%$ along an inverted-U sweet spot; the effect's sign flips between the over- and under-fitting regimes; noise injection matches an explicit spectral-filtering frontier. Our results organize two reported anecdotes into a single measurable principle for designing quantum-vision models.
### Title:
          Stable Transformer-Actor-Critic Model Predictive Control: A Contraction Analysis Approach
 - **Authors:** Antonio Marino (CAM), Valerio Modugno (UCL), Marco Cognetti (LAAS)
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Actor-Critic Model Predictive Control (MPC) effectively addresses complex, non-convex control problems, but guaranteeing the closed-loop stability of sequence-based learning models within these pipelines remains challenging. This paper introduces a novel Transformer-Actor-Critic MPC architecture with formal robustness guarantees. First, we prove that Transformer networks can satisfy global incremental Input-to-State Stability ($\delta$ISS). We then leverage Riemannian contraction theory to analyze the interconnected dynamics between the physical plant and the predictive neural network. Finally, we integrate these theoretical bounds as a training regularizer to yield a certifiably robust policy. The framework is validated on a nonlinear 3D drone model executing target-reaching and obstacle-avoidance maneuvers.
### Title:
          Confidence-Aware Automated Assessment of Student-Drawn Scientific Models
 - **Authors:** Luyang Fang, Yingchuan Zhang, Jongchan Park, Zhaoji Wang, Ping Ma, Xiaoming Zhai
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Student-generated drawings are widely used in science education to assess learners' conceptual understanding in modeling-based tasks aligned with the Next Generation Science Standards (NGSS). However, scoring such drawings requires expert human judgment to interpret complex visual representations, making large-scale assessment costly to implement and sustain in classroom settings. In this work, we study automated scoring of student-generated scientific drawings using a vision-based model. We evaluate a Vision Transformer (ViT) with parameter-efficient adaptation and propose a confidence-aware scoring framework that derives response-level confidence from test-time predictive distributions. This confidence signal enables selective automation by scoring high-confidence responses automatically while deferring uncertain cases for human review. Experiments on six NGSS-aligned middle school assessment items show that the proposed approach improves scoring reliability while supporting a practical trade-off between automated coverage and scoring risk, highlighting the value of confidence-aware methods for trustworthy educational assessment.
### Title:
          Geometry-Aware Superpixel Graph Transformer with Metadata for Skin Lesion Classification
 - **Authors:** Muhammad Azeem, Tanveer Hussain, Amr Ahmed, Ardhendu Behera
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated skin cancer classification from dermoscopic images remains challenging due to heterogeneous lesion structure, strong intra-class variability, and subtle visual differences between benign and malignant cases. Existing CNN/ViT pipelines typically rely on global or patch-level features and often combine patient metadata via late fusion, which limits spatially grounded multimodal reasoning. We present a novel region-based graph learning framework that explicitly models lesions as graphs of spatially coherent superpixel regions represented as frozen CNN features. To capture fine-grained lesion arrangements, we encode inter-regional geometry as edge attributes and introduce a dedicated metadata context node connected to all regions, providing structured integration of demographic/clinical variables within the same relational space. Node representations are updated using our edge-aware graph transformer followed by attention-driven propagation, and a final graph-level embedding for benign-malignant classification. Experiments on four public benchmarks demonstrate that explicit region-level relational modeling and graph-native multimodal fusion yield consistent gains over the state-of-the-art. Consequently, we establish a new graph-centric perspective in which CNN features are modeled as relational nodes and improved through contextual integration, yielding more expressive and robust classifications.
### Title:
          On the Redundancy of Timestep Embeddings in Diffusion Models
 - **Authors:** José A. Chávez
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion models rely heavily on explicit timestep embeddings to modulate the denoising process across various noise scales. In this work, we challenge the necessity of these temporal signals by analyzing their impact on U-Net and Diffusion Transformer architectures. Beyond empirical evidence, we provide a theoretical framework demonstrating that, under certain conditions, the global minimizer of the diffusion training objective can be achieved without explicit timestep conditioning. Our findings reveal a surprising robustness when timestep embeddings are completely removed. Extensive ablation studies on the CelebA and CIFAR-10 datasets show that these time-agnostic models can maintain high structural fidelity and even surpass their conditioned counterparts in competitive metrics, including FID, precision, and recall. Our analysis suggests these architectures can implicitly infer noise scales from the corrupted input under specific assumptions, rendering explicit temporal conditioning redundant. This study challenges long-standing temporal conditioning paradigms and paves the way for more efficient and structurally focused generative architectures.
### Title:
          Multi-Task Bayesian In-Context Learning
 - **Authors:** Qingyang Zhu, Eric Karl Oermann, Kyunghyun Cho
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bayesian predictive inference provides a principled framework for uncertainty quantification, data efficiency, and robust generalization. However, exact inference is often intractable, and scalable approximations may remain computationally expensive or require restrictive modeling assumptions that degrade predictive performance. Prior-Data Fitted and in-context models have recently emerged as an amortized alternative by learning to map datasets directly to predictive distributions, but existing approaches are tightly coupled to the support of the training prior and lack explicit mechanisms for adapting to new priors at test time, resulting in limited robustness under distribution shift. We introduce a multi-task in-context learning framework for amortized hierarchical Bayesian predictive inference that explicitly represents prior information as a prefix of in-context datasets. A transformer trained on sequences of prior and target tasks learns to adapt its predictions across families of priors. On a suite of evaluations with increasing difficulty, including out-of-meta-distribution priors and priors with high-dimensional latent structures, our method matches oracle Bayesian predictors while being orders of magnitude faster. We further demonstrate its practical relevance on a real-world spatiotemporal temperature prediction benchmark. Code is available at this https URL.
## Keyword: autonomous driving
### Title:
          Scaling Self-Play for End-to-End Driving
 - **Authors:** Luke Rowe, Roger Girgis, Rodrigue de Schaetzen, Daphne Cornelisse, Alaap Grandhi, Felix Heide, Eugene Vinitsky, Christopher Pal, Liam Paull
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end autonomous driving models are typically trained on offline human-demonstration datasets that provide limited state coverage and often no closed-loop feedback, making them prone to compounding errors when deployed in closed-loop and brittle to long-tail agent interactions. To overcome these limitations, we propose an alternative strategy for training end-to-end driving models: large-scale self-play directly from pixels in simulation. While prior self-play approaches have shown promising transfer to real-world driving, they typically assume vectorized Bird's-Eye-View (BEV) observations that are incompatible with end-to-end policies operating directly on sensor observations. To this end, we introduce Gigapixel, a high-throughput batched driving simulator with perspective rendering, enabling scalable self-play directly from pixel observations. Rather than targeting compute-costly photorealistic sensor simulation, Gigapixel renders a simplified bounding-box world that preserves essential scene structure while achieving throughput at 50k agent steps per second. Since direct pixel-space self-play RL is prohibitively sample-inefficient at end-to-end model scale, we propose self-play DAgger training: we train pixel-based policies in self-play via on-policy distillation from a privileged RL teacher. To bridge the sim-to-real gap, we subsequently transfer the self-play trained policies to real-world sensor data through lightweight perception adaptation. Policies trained in Gigapixel and adapted to real-world sensor data achieve competitive performance on the HUGSIM and NAVSIM-v2 benchmarks without human trajectory supervision. Moreover, scaling self-play training yields proportional gains in policy performance, establishing self-play as a practical and scalable strategy for training end-to-end models.
### Title:
          World Engine: Towards the Era of Post-Training for Autonomous Driving
 - **Authors:** Tianyu Li, Li Chen, Caojun Wang, Haochen Liu, Kashyap Chitta, Zhenjie Yang, Yuhang Lu, Naisheng Ye, Yihang Qiu, Yufei Wang, Luoxi Zou, Jiaxin Peng, Jin Pan, Zhaoyu Su, Andrei Bursuc, Shengbo Eben Li, Andreas Geiger, Peng Su, Hongyang Li
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous vehicles must operate safely in the real world, where errors can have severe consequences. Although modern end-to-end driving policies excel in routine scenarios, their reliability is limited by the scarcity of safety-critical ``long-tail'' events in real driving datasets. These rare interactions define the practical safety boundary of the learned policy, yet they are difficult to collect at scale in the real world. Here we show that this fundamental limitation can be addressed by post-training pre-trained driving models on synthesized high-stakes interactions. We introduce World Engine, a generative framework that reconstructs high-fidelity interactive environments from real-world logs and systematically extrapolates them into realistic safety-critical variations. This paradigm enables reinforcement-based post-training to align policies with safety constraints, circumventing the physical risks inherent in real-world exploration. On a public benchmark built on nuPlan, World Engine substantially reduces failures in rare safety-critical scenarios and yields significantly larger gains than scaling pre-training data alone. Furthermore, when deployed on a production-scale autonomous driving system, the resulting policy reduces simulated collisions and demonstrates measurable improvements in on-road testing, showing that post-training on synthesized, safety-critical interactions offers a scalable and effective pathway to safer autonomous driving. The full codebase suite, including training, is released to the public.
### Title:
          FrozenDrive: Zero-Shot Text-Guided Driving Scene Generation and Data Augmentation with Parameter-Free Frozen Diffusion Model
 - **Authors:** Yuhwan Jeong, Hyeonseong Kim, Daehyun We, Seonkyu Song, Jinnyeong Yang, Hyun-Kurl Jang, Youngho Yoon, Kuk-Jin Yoon
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Synthetic data for autonomous driving is surging, powered by diffusion models that promise scalable scene generation. Yet key obstacles remain, as enforcing multi-view and temporal consistency often relies on backbone fine-tuning or added layers, which erodes pre-trained knowledge and weakens text alignment. Models also stay close to the training distribution, struggling under adverse weather and unseen configurations, and fidelity favors frequent over rare classes. We address these gaps with FrozenDrive, a controllable generative framework that preserves a pretrained diffusion models knowledge while achieving strong consistency. FrozenDrive conditions on rich driving-stack signals and text prompts, and introduces knowledge-preserving spatio-temporal attention to impose cross-view alignment and temporal coherence in a single pass within a parameter-free frozen diffusion backbone. An additional object-focused constraint improves per-object fidelity for rare categories. Without any weather- or scene-specific fine-tuning, our model synthesizes globally coherent multi-view driving scenes from text, particularly under adverse and rare conditions, and surpasses prior baselines. On nuScenes, FrozenDrive augmented data significantly improves AD models performance, especially at night and in rain, demonstrating stronger robustness when trained with our scenario-targeted data.
### Title:
          HilDA: Hierarchical Distillation with Diffusion for Advancing Self-Supervised LiDAR Pre-trainin
 - **Authors:** Maciej Wozniak, Jesper Ericsson, Hariprasath Govindarajan, Truls Nyberg, Thomas Gustafsson, Patric Jensfelt, Olov Andersson
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Leveraging Vision Foundation Models (VFMs) for camera-to-LiDAR knowledge distillation offers a promising solution to the scarcity of annotated data needed to represent the immense geometric and kinematic diversity of real-world autonomous driving (AD). However, current approaches typically treat VFMs as black-box teachers, relying exclusively on frame-wise feature similarity. Consequently, they do not fully exploit the teacher's layer-wise semantic structure and global context, as well as the rich spatiotemporal information inherent in LiDAR sequences. We propose HilDA, a self-supervised pretraining framework for LiDAR backbones that better captures the semantic what and geometric where needed for driving tasks. HilDA combines hierarchical distillation comprising multi-layer distillation for progressive semantic alignment and global context distillation for scene-level semantics, with a temporal occupancy diffusion objective promoting spatiotemporal consistency. Models pre-trained with HilDA achieve state-of-the-art results on cross-modal distillation benchmarks and outperform models trained via prior distillation approaches on 3D object detection, scene flow, and semantic occupancy prediction. Code available at: this https URL.
### Title:
          Lagrange: An Open-Vocabulary, Energy-Based Sparse Framework for Generalized End-to-End Driving
 - **Authors:** Shihao Ji, HongXi Li, Zihui Song, Mingyu Li
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scaling end-to-end autonomous driving to complex, open-world environments requires perceptual models that generalize to anomalous scenarios and planners that produce kinematically valid trajectories. Existing paradigms face a distinct dichotomy between representational efficiency and generalization capacity. Dense models (e.g., occupancy networks), while geometrically robust, incur critical computational bottlenecks and struggle with high-level semantic reasoning. Conversely, sparse, query-based planners are efficient but reliant on closed-set definitions, rendering them vulnerable to out-of-distribution (OOD) events. Although recent Vision-Language-Action (VLA) models offer open-vocabulary reasoning, their autoregressive, discrete token generation fundamentally conflicts with the continuous, high-frequency control requirements of vehicle dynamics. To address this, we propose Lagrange, an open-vocabulary, computationally sparse driving framework based on Masked Latent Fields (MLF). Rather than relying on dense volumetric reconstructions or closed-set query mechanisms, Lagrange exploits Vision-Language Models (VLMs) to encode class-agnostic object proposals into continuous semantic visual tokens. We introduce an intent-driven masked cross-attention module that temporally filters irrelevant entities, decoding the attended tokens into an implicit continuous energy field defined over spatial coordinates. By framing decision-making as a Lagrangian action minimization problem spanning this energy field, we enforce strict compliance with vehicle kinematics while executing collision avoidance. Extensive offline evaluations on both standard (nuScenes) and long-tail (CODA) benchmarks demonstrate that Lagrange establishes a promising framework for robust, interpretable, and kinematically feasible open-world autonomy.
### Title:
          CRAX: Fast Safe Reinforcement Learning Benchmarking
 - **Authors:** Tristan Tomilin, Mourad Boustani, Mickey Beurskens, Thiago D. Simão
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Safety is a core concern for deploying reinforcement learning (RL) agents in real-world domains such as robotics and autonomous driving. While benchmarks have been central to progress in RL, existing safety benchmarks with high-fidelity 3D physics remain computationally slow, limiting large-scale experimentation and rapid prototyping. To address this gap, we propose CRAX (Constrained RL Accelerated with JAX). Built on top of the MuJoCo XLA (MJX) physics engine with realistic 3D dynamics, CRAX leverages vectorized operations and hardware acceleration, yielding up to ~100x speedups over comparable CPU-based safety benchmarks. The benchmark features six environment suites and three agent-specific tasks, each spanning three difficulty levels. Evaluating six popular safe RL methods shows that no single approach dominates across all tasks, and reveals the trade-offs between performance and safety. We find that curriculum learning across difficulty levels and safety transfer can improve performance over direct training in harder settings.
