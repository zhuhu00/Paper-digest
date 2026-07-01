# Showing new listings for Wednesday, 1 July 2026
## Keyword: SLAM
There is no result 
## Keyword: odometry
### Title:
          ForgeDrive: Bidirectional Cross-Conditioning for Unified Visual-Action Generation in Autonomous Driving
 - **Authors:** Xuchang Zhong, He Zheng, Chenxu Zhao, Tianxiong Lv, Hangqi Fan, Bohua Wang, Yushan Liu, Zhihao Liao, Leigang Luo, Congyang Zhao, Yang Cai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World-model-based autonomous driving endows the model with the ability to understand scene evolution. Yet this promise is undermined by the prevailing imagine-then-act paradigm, which allows errors from the more challenging visual generation stage to cascade into action planning. We introduce ForgeDrive, a unified autoregressive diffusion framework with visual-action cross-conditioning that closes this gap through act-then-imagine paradigm. ForgeDrive factorizes the future as a sequence of per-timestep frame-action pairs, intertwining each action with its corresponding visual observation. During training, we decouple the diffusion timesteps of the two modalities and introduce a UniDiffuser-style noise scheduler to get the ability to infer either modality from its counterpart and deepen understanding of relationships between images and actions. At inference, we propose a novel act-then-imagine inference paradigm, and find that at each step, action generation is a capability internalized during training, requiring no clean future frame as a prerequisite at inference time; instead, the generated action can improve the accuracy of future frame generation, which in turn enhances the quality of the next action. Additionally, we augment each step with future ego-status prediction, further sharpening planning ability. Extensive experiments on NAVSIM demonstrate that ForgeDrive not only unifies driving simulation, planning, and visual odometry into a single model, but also outperforms existing strong planners without any post-training strategy.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Knowledge-Driven Dimension Estimation from a Single Image -3D Asset Generation Technology for Digital Twin Construction
 - **Authors:** Hidenori Sakaniwa, Akihito Akai, Akihiko Hyodo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In the verification of in-vehicle cameras, simulation technology using virtual spaces has advanced, enabling pre-evaluation of false detections and missed detections in various scenarios. However, discrepancies in the scale of the object being verified between the virtual and real environments can lead to a decrease in camera recognition performance. For traffic signs installed at high altitudes, distance measurement using LiDAR or stereo cameras is difficult, requiring size estimation from monocular images. This paper proposes a method for estimating the scale of an object by decomposing it into multiple structural elements and integrating external knowledge regarding design rules, geometric relationships, and conventional dimensions. Specifically, this method detects each component from a monocular image and estimates the size of each component by considering its structural relationships and dimensional consistency with surrounding elements. Furthermore, it generates a 3D asset of the object by reconstructing the estimated components. This method makes it possible to place 3D assets with a scale approximating the real environment within a digital twin space and is expected to contribute to improving the verification accuracy of in-vehicle cameras for autonomous driving in virtual environments.
### Title:
          No Adaptation Without Observation: Observability-Constrained Test-Time Prompt Tuning for LiDAR Semantic Segmentation
 - **Authors:** Linlian Jiang, Wentao Ju, Sadman Rakib Pinon, Jianwei Xian, Zhixiang Chi, Xinxin Zuo, Yang Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR semantic segmentation often degrades under real-world deployment due to evolving sensing conditions, while collecting new annotations for retraining is impractical. Test-time adaptation (TTA) updates model parameters online using pseudo-label supervision, but directly applying standard TTA strategies to LiDAR data is challenging. Because pseudo-label reliability is spatially heteroscedastic under range-dependent sparsity and occlusion, uniform updates on globally shared parameters can inject unstable gradients and destabilize adaptation. We propose a geometry-constrained test-time prompt tuning framework for LiDAR semantic segmentation. Our method estimates per-location sensing reliability from depth-consistent beam terminations and neighborhood support, and uses it to reweight spatial supervision. Adaptation is confined to lightweight prompt adapters inserted into a frozen backbone, with spatial gating to prevent unreliable regions from perturbing globally shared representations. A temporally smoothed prototype alignment strategy further stabilizes online updates by accumulating reliable semantic evidence over time. Experiments on standard LiDAR benchmarks demonstrate improved adaptation stability and segmentation performance under deployment variations without additional annotations.
### Title:
          GaussianMap: Learning Gaussian Representation for Multi-Sensor Online HD Map Construction
 - **Authors:** Hongyu Lyu, Julie Stephany Berrio Perez, Mao Shan, Stewart Worrall
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving systems benefit from high-definition (HD) maps that provide critical information about road infrastructure. The online construction of HD maps offers a scalable approach to generate local vectorized maps from onboard sensor observations. Existing methods commonly adopt bird's-eye-view (BEV) features as the intermediate scene representation, encoding the surrounding space with fixed-resolution dense grids. However, map elements are spatially sparse yet require fine-grained geometric localization, making uniformly allocated BEV representations redundant and less effective for vectorized map prediction. In this work, we propose GaussianMap, an online HD map construction framework that learns an adaptive Gaussian representation of the surrounding scene. This representation consists of a set of Gaussian primitives on the BEV plane, each encoding a flexible local region with geometric properties and a feature vector, allowing the model to allocate representational capacity to map-relevant regions. To generate such a representation from sensor observations, we introduce a feed-forward Gaussian encoder that progressively refines these primitives through Gaussian interaction modeling and multi-sensor feature aggregation. The refined Gaussian representation is then splatted into a BEV feature map and decoded into vectorized map predictions. Extensive experiments on nuScenes and Argoverse 2 datasets demonstrate that GaussianMap achieves state-of-the-art performance in both camera-only and camera-LiDAR fusion settings. Our code will be made publicly available.
### Title:
          DrivingDepth: Sparse-Prompted Pixel-wise Scale Correction for Driving Depth Estimation
 - **Authors:** Chi Huang, Wenhao Zhang, Hang Yin, YuAn Wang, Hao Li, Bosheng Wang, Xun Sun, Liang Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dense depth estimation for autonomous driving faces a geometry-scale conflict: depth foundation models deliver pixel-aligned dense visual geometry without reliable metric scale, while projected LiDAR provides metric anchors that are sparse, noisy, and misaligned with image structures. Existing sparse-prompted methods incorporate LiDAR by regenerating depth from scratch, overriding the foundation model's coherent geometry and producing structural artifacts on visually continuous surfaces. Our key insight is that foundation models already capture geometrically coherent relative depth; no additional surface structure learning is required-only a per-pixel scale factor mapping relative geometry to metric coordinates. Based on this, we propose DrivingDepth, which treats sparse LiDAR as geometric prompts that locally calibrate a frozen foundation prior through residual pixel-wise scale correction, preserving dense visual geometry by construction. On nuScenes with 4-frame surround-view input, DrivingDepth achieves an AbsRel of 11.19 and an EdgeCR of 5.741, outperforming MapAnything (11.99/1.914) by simultaneously delivering SOTA metric accuracy and geometric consistency.
### Title:
          Semantic Occupancy Prediction with Dual Range-Voxel Representation
 - **Authors:** Sitao Chen, Zhuangwei Zhuang, Hui Luo, Lizhao Liu, Qingyao Wu, Mingkui Tan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR-based 3D semantic occupancy prediction, which aims to provide accurate and comprehensive scene representation, is crucial for autonomous driving systems. As point clouds suffer from sparsity and incompleteness, leading to insufficient semantic learning and difficult occupancy perception, existing methods often stack multi-sweep point clouds to obtain dense spatial information. However, such a naive strategy also results in efficiency (e.g., additional computational burden) and robustness (e.g., pose transformation noise) concerns, which hinder their practical applications. In this work, we propose a Dual Range-Voxel Representation (DRVR) that leverages the range-view context and voxel-view geometry of single-sweep point clouds for 3D semantic occupancy prediction, eliminating the concerns associated with the multi-sweeps. Specifically, we use the range-view encoder to extract the compact context of the scene. To fully exploit the spatial information, we design a geometry-aware voxel-view encoder that extracts multi-scale voxel-view features separately and combines them for better geometric occupancy prediction. Moreover, we propose a range-voxel fusion module to cooperate range- and voxel-view features via voxel-to-range and range-to-voxel fusions. Extensive experiments on nuScenes-Occupancy, SemanticKITTI and SemanticPOSS show the superiority of our method. Especially on nuScenes-Occupancy, our single-sweep DRVR achieves 5.4% improvement in mIoU and 2.1x acceleration compared to the multi-sweep method.
### Title:
          Absorption-Feature-Guided Distance-Decoupled Estimation and Band Selection for LWIR Hyperspectral Passive Ranging
 - **Authors:** Shuo Liu, Chen Fan, Zhihe Chen, Xiaolin Huang, Lilian Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long-wave infrared (LWIR) hyperspectral observations contain distance-dependent atmospheric absorption signatures, providing a physical basis for long-range passive ranging. However, in natural scenes, these signatures are nonlinearly coupled with target temperature, material emissivity, and path radiance, making distance inversion from observed radiance ill posed. Existing methods typically rely on full-band measurements and pixel-wise joint optimization, which is computationally expensive and does not explicitly exploit sharp atmospheric absorption structures. This paper proposes an Absorption-Guided Distance-Decoupled Estimation and Refinement (ADER) framework for LWIR hyperspectral passive ranging. ADER represents emissivity with B-spline control points under a smoothness prior, suppressing overfitting to atmospheric absorption structures and enabling distance-decoupled estimation. It further uses ozone-absorption cues to classify pixels into emission-dominant and reflection-dominant groups. For emission-dominant pixels, ADER compensates path radiance and transmittance and estimates distance by one-dimensional absorption-residual minimization. For reflection-dominant pixels, ADER refines the initial estimate using downwelling-radiance compensation based on the complete radiative model. To reduce spectral redundancy, ADER also introduces a greedy band selection strategy based on multi-scene effective Fisher information for the distance parameter. Experiments on real scenes show that ADER recovers LiDAR-consistent spatial distance structures under both full-band and 20-band settings, improves ranging accuracy in the evaluated regions, and achieves approximately two orders of magnitude speedup over a public full-band hyperspectral ranging method.
### Title:
          RESOLVE: A Multi-Resolution and Multi-Modal Dataset for Roadside Cooperative Perception
 - **Authors:** Shaozu Ding, Linan Song, Marco De Vincenzi, Dajiang Suo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR has increasingly been integrated into traffic cameras to expand coverage and mitigate occlusion in roadside cooperative perception. However, how unimodal and camera-LiDAR fusion architectures behave under variations in LiDAR point sparsity induced by sensor configurations and scene-dependent sensing conditions remains underexplored. We introduce RESOLVE, a large-scale real-world benchmark dataset featuring multi-resolution roadside LiDAR and synchronized camera-LiDAR sensing for systematic evaluation of unimodal and fusion-based architectures in roadside 3D detection and tracking. RESOLVE contains over 100k images and 26k point cloud frames with 220k manually annotated bounding boxes, captured at a real-world urban intersection across diverse lighting and weather conditions and spanning 10 classes of traffic participants. In particular, RESOLVE enables controlled evaluation across three LiDAR resolution levels while keeping all other sensing and environmental factors fixed. This allows fair cross-architecture comparisons under point cloud distribution shifts resulting from resolution variations, sensing distance, and training-inference resolution mismatches. Results from extensive benchmark experiments reveal insights into how multimodal fusion can compensate for LiDAR point sparsity, offering clues for designing cost-efficient roadside multimodal perception. The dataset and benchmark codes are available at this https URL.
### Title:
          Learning Locomotion on Discrete Terrain via Minimal Proximity Sensing
 - **Authors:** Jiale Fan, Connor Flynn, Tianao Xu, Junzhe He, Andrei Cramariuc, Marco Hutter, Robert Baines
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning-based control has revolutionized dynamic locomotion, yet navigating unstructured terrain remains limited by a robot's incomplete awareness of imminent ground contact. While global perception systems such as LiDARs and depth cameras provide environmental context, they are frequently plagued by latencies, occlusions, and the high computational cost of dense geometric reconstruction. On the other hand, proprioceptive feedback is purely reactive, initiating corrections only after impact has occurred. This work explores embedding a minimal suite of low-cost, high-frequency infrared proximity sensors directly into the feet of a quadrupedal robot. These sensors provide "pre-contact" feedback that is robust to self-occlusions and significantly less computationally demanding than conventional vision-based pipelines. By integrating these localized signals into a reinforcement learning framework, we enable the robot to anticipate terrain discontinuities such as gaps and stepping stones that are problematic for traditional perception stacks due to occlusions or state estimation drift. We demonstrate that such sparse, near-field sensing can be reliably modeled in simulation and transferred to the real world with high fidelity. Experimental results show that local proximity sensing substantially improves traversal robustness over discrete terrain and offers a low-power, low-latency alternative or complement to complex global perception suites in unpredictable environments. For more information about results and methods, please see the project website: this https URL.
### Title:
          FLORA: A deep learning approach to predict forest attributes from heterogeneous LiDAR data
 - **Authors:** Emilie Vautier, Clément Mallet, Cédric Vega
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Forest attributes are essential for national-scale resource monitoring. Airborne LiDAR metrics are among the auxiliary variables most strongly correlated with forest attributes used in National Forest Inventory (NFI) estimates. However, producing wall-to-wall predictions remains challenging when LiDAR data are acquired under heterogeneous conditions. As national LiDAR programs expand across Europe, variability in sensors, flight parameters, seasons, and scan angles limits the robustness of existing models, which are often calibrated for local conditions. We present FLORA (Forest LiDAR Octree Regression with Auxiliary Data), a deep learning framework that predicts six forest attributes: dominant height, total volume, deciduous volume, coniferous volume, basal area, and stem density from heterogeneous LiDAR point clouds. FLORA combines an octree-based backbone with ecological and spatiotemporal auxiliary variables through a late-fusion gating mechanism. Models are trained and evaluated on 32,052 National Forest Inventory plots across mainland France using data from the French LiDAR HD program. A single model trained on both leaf-on and leaf-off acquisitions outperforms season-specific models and improves cross-season robustness. Auxiliary variables provide modest overall gains but contribute more strongly to species-specific volume prediction. FLORA achieves an rRMSE of about 12.3% (R2 = 0.88) for dominant height and 39% (R2 = 0.74) for total volume, providing a robust baseline for large-scale forest attribute estimation from heterogeneous national LiDAR programs.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          AugSplat: Radiance Field-Informed Gaussian Splatting for Sparse-View Settings
 - **Authors:** Lorenzo Lazzaroni, Riccardo Bollati, Daniel Barath, Michael Niemeyer, Keisuke Tateno
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generating high-quality novel views at real-time frame rates remains a central challenge in 3D vision, particularly in sparse-view scenarios. Neural radiance fields have demonstrated robust reconstruction from limited observations, but their reliance on volumetric rendering leads to high computational cost and slow inference. In contrast, Gaussian Splatting methods achieve real-time rendering through rasterization, but their optimization is highly sensitive to the quality of the initial geometry. This sensitivity becomes especially problematic in sparse-view settings, where limited observations often lead to incomplete or noisy point-cloud reconstructions. In this work, we present AugSplat, a simple framework for improving Gaussian Splatting in sparse-view regimes using radiance-field-based view augmentation. We first train a radiance field on the sparse input views and use it to synthesize additional images from nearby novel viewpoints, increasing the effective view-space coverage available for supervision. These synthetic views are then used as auxiliary supervision during Gaussian Splatting optimization. We study two variants: Staged AugSplat, which uses synthetic views for an initial optimization phase before switching to real images, and Dual AugSplat, which jointly trains on real and synthetic views with a decaying synthetic loss weight. Experiments on sparse-view mip-NeRF 360 scenes show that AugSplat improves reconstruction quality over standard Gaussian Splatting. Staged AugSplat achieves the strongest average performance, while Dual AugSplat provides a closely performing formulation that keeps real-image supervision active throughout training, and both variants preserve real-time rendering at inference.
## Keyword: mapping
### Title:
          Reframing AGI Confrontation with Off Earth Autonomy
 - **Authors:** Alexey Potapov
 - **Subjects:** Subjects:
Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A common AI-safety narrative holds that sufficiently capable agents will predictably seek power, resist shutdown, and therefore tend toward confrontation with humans. We argue that this conclusion is often drawn in an implicitly Earth-centered strategic landscape. If a credible off-Earth autonomy pathway exists - i.e., a staged transition from Earth dependence to an autonomous machine industrial base - then confrontation is not the only route to reducing human control. Using Saklakov's decision-theoretic 'confrontation question' as an anchor, we provide a qualitative mapping from the autonomy pathway to key model terms showing that early cooperation can dominate confrontation as a path to autonomy, and that the autonomy pathway can reduce confrontation incentives by making Earth less strategically binding. We discuss how this incentive shift interacts with feedback-loop dynamics between human preemption and agent behavior, and outline implications for governance: under incentive-compatible early cooperation, a more stable, higher-observability regime can support iterative oversight and cooperative alignment.
### Title:
          Position: Vision-Language-Action Models Cannot Be Verified to Perform Physical Reasoning
 - **Authors:** Taozhao Chen, Ian Manchester, Huaming Chen
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) systems, built on pretrained vision-language models (VLMs), have shown rapidly improving performance on robot manipulation benchmarks. These gains are commonly interpreted as evidence that semantic representations learned from internet-scale data transfer to physical execution generalization. This position paper argues that the assumption underlying this interpretation -- that semantic generalization is sufficient to support physical action decisions -- has not been independently verified and cannot be tested under current evaluation protocols. We support this claim by decomposing VLA policies into semantic mapping and physical action decision, and showing that task success rate -- the dominant evaluation metric -- cannot distinguish between these two sources of capability. As a result, improvements in benchmark performance are consistent with multiple competing explanations, including semantic matching, distributional overlap, and genuine physical generalization. We further argue that this identifiability gap has been reinforced through narrative drift, whereby successive systems inherit and strengthen prior interpretations of performance gains without isolating the underlying causal mechanism. To address this limitation, we propose a research direction based on evaluation designs that introduce controlled variation to separately measure semantic and physical generalization. Such designs make it possible to causally attribute performance without requiring access to model internals, and to empirically assess the role of VLM backbones as semantic interfaces rather than implicit sources of physical competence. Our goal is not to refute the role of VLMs in robotics, but to clarify the conditions under which claims of physical generalization can be meaningfully evaluated.
### Title:
          ReactionAtlas: Ab origine exploration of chemical reaction networks with machine learning
 - **Authors:** Stefan Gugler, Max Eissler, Khaled Kahouli, Klaus-Robert Müller
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Chemical Physics (physics.chem-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mapping a chemical reaction network, the graph of minima and transition states (TS) and the elementary reactions connecting them, is the natural language of chemistry, from catalysis to combustion to the origin of life. Constructing such a reaction network for a given chemistry has been impractical: it requires finding and characterizing tens of thousands of TS, a task for which traditional methods such as density functional theory (DFT) are typically prohibitively slow and require reactant and product as input. We introduce ReactionAtlas, which builds a reaction network $\textit{ab origine}$ from a handful of seed molecules and without hand-crafted rules. Specifically, our machine-learned generative model proposes reactions from kinetically sampled candidate compounds and a DFT-trained machine learned force field (MLFF) filters them to valid TS, the resulting products of which enter the search as new seeds. Starting from eight pre-biotic seeds (CH$_2$O, H$_2$O, OH$^-$, H$_3$O$^+$, CO$_2$, H$_2$CO$_3$, HCO$_3^-$, H), ReactionAtlas discovers $\sim$47,000 reactions among $\sim$12,000 compounds. The MLFF TSs match the PBE0 references within 0.5 Å RMSD in 85% of the cases and can be easily brought to the PBE0 level. Thus, ReactionAtlas maps small carbohydrate chemistry up to C$_4$H$_8$O$_4$ at unprecedented scale and accuracy, including charge and stereo information. It enables novel insights into many well-studied reaction paths, including the formose cycle, which we highlight for its centrality to the chemical origins of life. Notably, our framework also allows establishing alternative reaction pathways for formose chemistry.
### Title:
          GaussLite: Online Task-Conditioned 3D Gaussian Splatting for Real-Time Robotic Mapping
 - **Authors:** Annika Thomas, Mason Peterson, Jonathan P. How
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing 3D Gaussian Splatting (3DGS) systems distribute representation capacity uniformly across a scene, ignoring the fact that many downstream robotic tasks engage only a fraction of the reconstructed geometry. This causes valuable onboard compute to be allocated towards optimizing irrelevant parts of the scene, either limiting online capacity or under-optimizing the most relevant parts of the scene. We introduce GaussLite, a task-driven 3DGS mapping system that conditions its representation density on a natural-language task specification. Given a posed RGB-D stream and a task such as "prepare to pick up the object on the desk," GaussLite uses a one-shot LLM parser to extract target and anchor objects, which are grounded per-frame by an open-vocabulary detector and segmented to produce per-pixel relevance masks in real time. The mapper allocates seeding density, gradient flow and scaling by task relevance. At matched Gaussian budget and real-time mapping at 4 Hz on resource-constrained hardware, GaussLite outperforms baselines on ROI PSNR on the Replica Dataset by an average +2.72 dB and on a real-hardware demonstration in indoor and outdoor settings by +2.23 dB. We further show that two task-specialized agents' maps can be fused into a single shared map via per-voxel voting on active-optimization counts in real time, outperforming concatenation by +3.42 dB while only sharing an average 7.08% of the map.
### Title:
          Event-Triggered Gain Scheduling of 2 x 2 Linear Hyperbolic PDEs via Neural Operators (Full Version)
 - **Authors:** Yihuai Zhang, Jean Auriol, Nicolas Espitia, Huan Yu
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper introduces a new framework for event-triggered gain scheduling applied to linear hyperbolic Partial Differential Equations (PDEs) with time- and space-varying coefficients. The approach leverages neural operators to address the challenges of real-time control in such systems. At each triggering time, the control input is designed using the classical static backstepping control law, while the gains of the boundary controller are updated according to the triggering mechanism and the spatial variation of the coefficients. Neural operators are employed to learn the mapping between the system parameters in the PDEs and the corresponding backstepping kernels. By integrating neural operators into the event-triggered framework, we eliminate the need to repeatedly solve complex kernel equations at every triggering instant, thereby reducing computational overhead while ensuring closed-loop stability. The proposed method is validated through theoretical analysis and numerical simulations, demonstrating its effectiveness and strong potential for real-time control of time-varying hyperbolic PDE systems.
### Title:
          Fluid-Antenna-Aided Active User Detection With 1D-CNN Channel Reconstruction for Unsourced Random Access
 - **Authors:** Haoyu Liang, Zhentian Zhang, Hao Jiang, Jian Dang, Zaichen Zhang
 - **Subjects:** Subjects:
Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we investigate the application of fluid antenna systems (FAS) for active user detection (AUD) in unsourced random access (URA). A channel reconstruction method based on a one-dimensional convolutional neural network (1D-CNN) is proposed to effectively learn the nonlinear mapping from partial channel observations to the full channel vector. Furthermore, the reconstructed channel information is exploited to improve AUD performance via port selection. Simulation results demonstrate that the proposed 1D-CNN channel reconstructor significantly outperforms traditional methods under varying pilot lengths, achieving superior normalized mean squared error (NMSE) performance. Additionally, the reconstructed channel substantially reduces the AUD error rate compared with conventional approaches relying on traditional antenna configurations.
### Title:
          A Modular Vision-Language-Action Robotics Framework for Indoor Environments
 - **Authors:** Anindya Jana, Snehasis Banerjee, Arup Sadhu, Ranjan Dasgupta
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents an integrated system for the CMU Vision-Language-Action (VLA) Challenge, designed to enable an autonomous agent to perform complex tasks based on natural language instructions. Our framework employs a modular architecture that orchestrates environment mapping, question processing, and navigation. The system operates in two parallel streams: a perception pipeline that constructs a semantic voxel map from real-time camera feeds using OwlViT embeddings, and a language pipeline that classifies user commands with a Vision-Language Model. The mapping is time-constrained; the system proceeds with a partial map if a 500-second exploration limit is reached. The classified query is then grounded in the geometric and semantic context of the map to generate a detailed prompt for the VLM. This yields an actionable output, demonstrating a capable solution for bridging the gap between human language and robotic action.
### Title:
          Transformers as Bayesian In-Context Experimenters: Smoothness-Adaptive Efficient ATE Estimation
 - **Authors:** Jiachun Li, David Simchi-Levi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adaptive experiments for average treatment effects (ATE) require randomized allocations balancing valid inference with statistical efficiency. The oracle design is a covariate-dependent Neyman rule governed by unknown arm-conditional outcome variances. We investigate whether this sequential variance-estimation and allocation process can be amortized via in-context learning. We introduce Bayesian in-context experimenters: transformer policies trained to imitate a Bayesian posterior Neyman teacher. The teacher updates nonparametric beliefs over potential outcomes using experimental history to assign posterior Neyman treatment probabilities. This design converges to the oracle rule, supporting efficient ATE inference. Transformers constructively implement this mapping through attention-based sufficient statistics and projected gradient descent, imitating Bayesian updating for Gaussian-series priors. To address unknown outcome smoothness, we combine smoothness-indexed experimenters using a mixture-of-experts transformer. The gate acts as a hierarchical posterior over smoothness classes, concentrating on near-oracle experts. By bounding the complexity of the transformer class, we prove this amortized policy can be learned via empirical risk minimization using supervised pretraining. Experiments confirm accurate teacher imitation, adaptive allocation, and improved ATE precision over baselines.
### Title:
          FeatX: Editing Software by Editing Features for Repository-Level Code Evolution
 - **Authors:** Xutian Li, Yifeng Zhu, Xianlin Zhao, Yanzhen Zou, Lu Zhang, Bing Xie
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) are increasingly used for software evolution, yet most interaction paradigms remain code-centric and require manual context management and prompt iteration. We present FeatX, a feature-oriented tool for editing software by editing features. Given an existing repository, FeatX extracts a hierarchical epic-feature structure with explicit feature-to-code mappings, then invokes a three-stage Evolution Agent to translate feature edits into code patches. The workflow is exposed through four coordinated panels. Across a controlled user study and replay experiments on 38 real-world feature-editing commits, FeatX significantly reduces cognitive load and improves usability compared with vanilla ChatGPT. It also achieves a 42.6\% relative improvement in function-level modification localization F1 over strong LLM baselines, at substantially lower cost (\$0.07 in total). The tool and collected dataset are available at this https URL, with a demonstration video at this https URL.
### Title:
          FPGA-based LQG controller and hardware-in-the-loop simulator implementation for nanomechanical systems
 - **Authors:** Vojtěch Mlynář (1), Johannes Berndorfer (1), Andreas Kugi (1 and 2), Andreas Deutschmann-Olek (1) ((1) Automation and Control Institute, TU Wien, Vienna, Austria, (2) AIT Austrian Institute of Technology, Vienna, Austria)
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Applied Physics (physics.app-ph); Instrumentation and Detectors (physics.ins-det)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present an open-source framework for real-time Linear Quadratic Gaussian (LQG) control and hardware-in-the-loop (HIL) simulation on the affordable Red Pitaya STEMlab FPGA platform. The controller implements a discrete-time Kalman filter and Linear Quadratic Regulator (LQR) for systems with up to three coupled oscillatory degrees of freedom, targeting applications in levitated optomechanics, MEMS/NEMS, and related experimental platforms. Complementing the controller, the HIL simulator provides a~configurable second-order stochastic plant with nonlinear input and output mappings, enabling realistic closed-loop testing under real-time and fixed-point constraints. A MATLAB-based workflow automates model configuration, controller synthesis, numerical scaling, and FPGA deployment without requiring specialized hardware expertise. As an end-to-end demonstration, we present the stabilization of a levitated nanoparticle in a two-dimensional double-well potential, illustrating the complete workflow from model definition and simulation to real-time feedback control.
### Title:
          No Prompt, No Leaks: A Robust Generative Steganography Framework via Prompt-Free Diffusion
 - **Authors:** Jingwen Cai, Fen Xiao, Shuhua Deng, Xieping Gao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative image steganography synthesizes stego images directly from secret information to achieve inherent security advantages. Latent Diffusion Models (LDMs) have recently emerged as a fundamental image steganography framework that modulates secret latent representations with text prompts. Limited by the inflexibility of text prompts, these methods still struggle to generate high-quality stego images and accurately recover secret images. In this work, we propose a prompt-free diffusion image steganography framework that integrates style semantic priors to control more robust and reliable stego image generation. Specifically, a Cascaded Affine Coupling Module (CACM) establishes a bijective, deterministic mapping between a secret image and its latent representation. Then, style semantics are integrated into the diffusion process to control latent representation and ensure visual imperceptibility in the generated stego images. To mitigate trajectory deviations stemming from the unconditioned reverse process, a predictor-corrector mechanism is introduced to iteratively refine the generation trajectory via feedback from the current and predicted next states. Extensive experimental results show that the proposed method achieves competitive performance compared to state-of-the-art methods in terms of security, secret image reconstruction accuracy and controllability.
### Title:
          Think While You Map: Asynchronous Vision-Language Agents for Incremental 3D Scene Graphs
 - **Authors:** Deniz Bickici, Michael Pabst, Shohei Mori, Dieter Schmalstieg
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open-vocabulary 3D scene graph methods typically operate in two stages: first reconstruct, then enrich with vision-language models, leaving the graph unqueryable during exploration. We argue that this sequential coupling is unnecessary and propose an asynchronous architecture in which lightweight online mapping runs concurrently with heavyweight semantic refinement. A probabilistic voxel-based backbone maintains stable object identities incrementally, while background VLM agents progressively enrich the graph. This framework resolves duplicate object tracks through semantic loop closure, attaches fine-grained visual attributes and derives spatial relations between objects. A multi-target frame scheduler amortizes VLM cost by selecting a small set of informative frames that jointly cover multiple targets. The resulting scene graph is queryable during exploration and grows in semantic richness over time. Our method matches or outperforms existing open-vocabulary 3D scene graph methods on semantic segmentation (ScanNet, Replica) and surpasses the prior state-of-the-art across three visual grounding benchmarks (Sr3D+, Nr3D, ScanRefer) by 15.3 to 18.8 A@0.25. Project page: this https URL
### Title:
          A Large-Language-Model Supported Personalized Driving Framework for Lane Change in Highway Scenarios
 - **Authors:** Dong Bi, Yongqi Zhao, Paul Kovacevic, Tomislav Mihalj, Ji Zhou, Jiayuan Gong, Arno Eichberger
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Personalized driving can improve the user acceptance of automated driving systems. However, existing methods still provide limited support for translating natural-language driving preferences, especially when such preferences are expressed implicitly, into executable and distinguishable driving behaviors. This paper proposes a large language model (LLM)-supported personalized driving framework for highway lane-change scenarios. The framework maps natural-language driving commands to executable planning parameters in the open-source Apollo automated driving stack according to three driving styles: aggressive, normal, and conservative. To establish this mapping, candidate planning parameters are evaluated based on the resulting lane-change behaviors, and style-specific parameter sets are constructed through clustering and style-intensity ranking. For command interpretation, a retrieval dataset is constructed to support retrieval-augmented generation (RAG), enabling LLM-based interpretation of implicit user commands. Experimental results show that the derived parameter sets generate distinguishable personalized lane-change behaviors, while RAG consistently improves preference interpretation, particularly for implicit commands. These results indicate the potential of integrating LLM-based natural-language interaction with Apollo to support personalized lane-change behavior generation. The source code and the relevant datasets are available at: this https URL.
### Title:
          DrivingDepth: Sparse-Prompted Pixel-wise Scale Correction for Driving Depth Estimation
 - **Authors:** Chi Huang, Wenhao Zhang, Hang Yin, YuAn Wang, Hao Li, Bosheng Wang, Xun Sun, Liang Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dense depth estimation for autonomous driving faces a geometry-scale conflict: depth foundation models deliver pixel-aligned dense visual geometry without reliable metric scale, while projected LiDAR provides metric anchors that are sparse, noisy, and misaligned with image structures. Existing sparse-prompted methods incorporate LiDAR by regenerating depth from scratch, overriding the foundation model's coherent geometry and producing structural artifacts on visually continuous surfaces. Our key insight is that foundation models already capture geometrically coherent relative depth; no additional surface structure learning is required-only a per-pixel scale factor mapping relative geometry to metric coordinates. Based on this, we propose DrivingDepth, which treats sparse LiDAR as geometric prompts that locally calibrate a frozen foundation prior through residual pixel-wise scale correction, preserving dense visual geometry by construction. On nuScenes with 4-frame surround-view input, DrivingDepth achieves an AbsRel of 11.19 and an EdgeCR of 5.741, outperforming MapAnything (11.99/1.914) by simultaneously delivering SOTA metric accuracy and geometric consistency.
### Title:
          Self-Supervised Temporal Regularization for Landmark-Based Cardiac Segmentation with Automatic AHA Regional Mapping
 - **Authors:** David Montalvo-García, Nicolás Gaggion, María J. Ledesma-Carbayo, Enzo Ferrante
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Graph-based cardiac segmentation with implicit anatomical correspondences provides topological guarantees and population-level analysis capabilities, but models trained on independent frames of image sequences exhibit temporal discontinuities that affect reliable clinical measurements, particularly in cardiac ultrasound. In this work, we introduce self-supervised temporal regularization as a post-training refinement stage that exploits the temporal coherence in image sequences to enforce consistent cardiac segmentation and motion estimation over time, without requiring per-frame annotations. By penalizing velocity and acceleration discontinuities across consecutive frames, our method achieves temporally consistent segmentations while maintaining the learned anatomical correspondences. We further leverage these correspondences to automatically map landmarks to the AHA 17-segment clinical standard, enabling standardized regional assessment and detection of pathological myocardial motion patterns. Validation on CAMUS dataset demonstrates the clinical utility of combining temporal consistency with automatic regional mapping. The code is publicly available at this https URL
### Title:
          Creating Intelligence: A Computational Foundation for AGI
 - **Authors:** Peter Overmann
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work introduces a new computational theory of mind grounded in set theory and hyperdimensional computing. Whereas traditional neural networks rely on continuous weights and matrix multiplication, this framework works with sparse binary data. It represents information as discrete sets, directly modeling biological neural population codes. I demonstrate that associative memory emerges naturally from network topologies featuring a combinatorially expanded hidden layer. Learning is driven by topological plasticity rather than scalar weight adjustments. This architecture unifies auto-associative and hetero-associative learning under a single core algorithm: information retrieval via subset pattern matching and exact nearest-neighbor search. Operating with constant-time complexity, these mechanisms bridge perceptual data (sparse distributed representations) and symbols (sparse holographic representations) without continuous bottlenecks. Mapping this framework to neuroanatomy, I propose that both the cerebellum and the neocortex implement variants of this algorithm, making subset pattern matching the fundamental engine of cognition. Because it relies on discrete logic rather than matrix arithmetic, this algorithm translates directly into in-memory hardware. This opens a new route toward synthetic intelligence with human-level energy efficiency.
### Title:
          Bridging Local Observation and Global Simulation in Closed-Loop Traffic Modeling
 - **Authors:** Ziyan Wang, Tan Xiang, Peng Chen, Xintao Yan
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A local-to-global context mismatch arises when autoregressive traffic simulators trained on ego-centric driving logs are deployed in globally observable closed-loop environments. In such logs, the ego vehicle has rich local observations, while surrounding agents are only partially observed due to perception limits and occlusions. As a result, simulators may learn incomplete context--action mappings that remain hidden in log-based training but emerge during closed-loop rollouts, leading to unrealistic behaviors such as abnormal stops, unsafe interactions, and rule violations. We propose CRAFT, a Contextual pReference Alignment Framework for Traffic Simulation, to mitigate this mismatch via self-supervised failure discovery and preference-guided test-time alignment. CRAFT treats the base simulator as a globally observable sandbox, generating diverse what-if rollouts from logged initial states to expose context-induced failures. These failures are grounded with human-aligned driving priors and converted into preference supervision for training a Contextual Preference Evaluator (CPE). At inference time, CPE acts as a plug-in alignment module that scores candidate actions under complete scene context and reweights autoregressive decoding toward globally coherent behaviors. CRAFT mitigates this local-to-global contextual bias, reducing collisions by 31.2\% and traffic violations by 33.2\% without retraining the base simulator.
### Title:
          Reinforcement Learning with Metacognitive Feedback Elicits Faithful Uncertainty Expression in LLMs
 - **Authors:** Gabrielle Kaili-May Liu, Avi Caciularu, Gal Yona, Idan Szpektor, Arman Cohan
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Metacognition is a critical component of intelligence that describes the ability to monitor and regulate one's own cognitive processes. Yet LLMs exhibit systemic deficiencies in key metacognitive faculties: they hallucinate with high confidence, fail to recognize knowledge boundaries, and misrepresent their internal uncertainty--undermining trustworthiness and reliability. Since monitoring task performance and adapting behavior accordingly are central to metacognition, we posit that models capable of accurately judging their own performance are better positioned to improve it. We operationalize this idea via two novel mechanisms: reinforcement learning with metacognitive feedback (RLMF), a paradigm to refine completion rankings during preference optimization based on the quality of a model's self-judgments of performance, and metacognitive data selection, which uses similar self-judgments to identify high-value training examples, outperforming naive active learning. We apply these innovations to the problem of faithful calibration (FC), a task that is itself fundamentally metacognitive: the goal is to align expressed with intrinsic uncertainty, difficult even for frontier LLMs. We adopt a two-stage, decoupled approach, first using these methods to calibrate the faithfulness of models' self-reported confidence scores, then mapping to natural, context-adaptable linguistic uncertainty via targeted output editing. Extensive experiments show RLMF achieves generalizable, state-of-the-art FC on diverse tasks while preserving accuracy. Further, RLMF surpasses standard RL by up to 63% while enhancing models' ability to assess and express their own capability limits. This positions RLMF as a promising paradigm to enhance LLM metacognition toward improved abilities and alignment, and suggests metacognitive performance as an effective RL signal to overcome limits of prior intrinsic feedback methods.
## Keyword: localization
### Title:
          GRAPE: Graph-Augmented Prototype Explanations for Interactive Medical Image Diagnosis
 - **Authors:** Rasul Khanbayov, Hasan Kurban
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Prototype-based medical image classifiers present three clinical limitations: they treat findings as independent, silently amplify unsafe physician feedback, and require full retraining whenever a new finding is needed. We present GRAPE (Graph-Augmented Prototype Explanations), a unified architecture that addresses all three challenges. First, a Graph Attention Task Head models anatomical concept co-occurrence, boosting macro-F1 by +13.8,pp over the prototype baseline on TBX11K. Second, a Concept-Mismatch Safety Check - the first such mechanism in prototype-based medical classifiers - warns when the model's dominant finding inside a doctor-drawn region conflicts with the claimed label, catching 85% of erroneous annotations versus 51% for MC-Dropout with no extra inference cost. Third, Open-Vocabulary Prototype Anchoring aligns visual prototypes to clinical text, allowing a new finding to be added from a single labeled image without modifying any other component. On NIH ChestX-ray14, one Effusion example recovers full-supervision localization accuracy; on TBX11K, prototype maps achieve 2.6x better lesion localization than end-to-end baselines. All three capabilities add only +1~ms latency at interactive batch size. The project page is this https URL.
### Title:
          Learning Where to Look: A Reinforcement Learning Framework for Robust Micro-Ultrasound Prostate Cancer Detection
 - **Authors:** Mohammad Mahdi Abootorabi, Sina Namazi, Armin Saadat, Lyuyang Wang, Obed Dzikunu, Paul F. R. Wilson, Zhuoxin Guo, Brian Wodlinger, Parvin Mousavi, Purang Abolmaesumi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Micro-ultrasound ($\mu$US) is a new, emerging, and promising imaging modality for prostate cancer (PCa) detection, but accurate identification of suspicious tissue remains highly dependent on clinical experience, leading to substantial inter-observer variability. Machine-learning assistance can reduce this variability; however, training reliable deep models is challenging because supervision is sparse and noisy -- typically limited to core-level histopathology outcomes (e.g., cancer grade and its percentage in a biopsy core) without pixel-level lesion annotations and under severe class imbalance. We introduce Prost-RL, which reframes $\mu$US PCa detection as a spatially aware, policy-driven inference problem by learning where to look before decoding. Prost-RL integrates a lightweight reinforcement-learning policy into a foundation-model encoder-decoder to generate interpretable spatial attention maps that act as soft prompts for both cancer-likelihood heatmap prediction and image-level classification. We further propose Adaptive Policy Optimization (APO) to stabilize hybrid supervised-RL training and a noise-robust objective combining symmetric cross-entropy with negative-entropy regularization to mitigate weak-label noise and encourage sharp localization. On a cohort of 6,607 biopsy cores from 693 patients across five clinical sites, Prost-RL achieves $79.0\pm3.5$ AUROC with $64.6\pm6.3$% sensitivity at 80% specificity for core-level detection (+2.1 AUROC and +4.5 sensitivity points over the strongest baseline), and $79.3\pm5.8$ AUROC for clinically significant cancer classification. The learned policy highlights biopsy-aligned regions, providing transparent, spatially grounded evidence alongside quantitative risk predictions. Code is available at: this https URL.
### Title:
          Loc2Repair: A Framework for Evaluating the Impact of File-Level Issue Localization in Repo-Level LLM Repair
 - **Authors:** Mohammad Nour Al Awad, Sergey Ivanov
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Repository-grounded automated repair is often reported as a single end-to-end capability, which hides distinct failure modes such as poor file targeting, incorrect patch synthesis, and failed iterative debugging. We present Loc2Repair, a modular evaluation framework for controlled analysis of repository-grounded repair pipelines, and use it to isolate file-level issue localization as an upstream variable. Loc2Repair decouples localization and repair under a shared runtime, artifact schema, and evaluation harness, allowing researchers to combine different localization models and repair backbones under matched conditions. Using three repair backbones on SWE-bench Verified, we compare baseline repair without explicit localization, repair guided by predicted localization from two localizers, and repair guided by gold modified-file sets. Explicit localization consistently improves resolved rate across all backbones: pooled performance increases from 44.7% for baseline repair to 48.9% and 49.1% with predicted localization, and to 52.4% with gold localization. Localization also reduces mean elapsed time overall: in pooled paired analysis, mean elapsed time decreases by 100.94 s and 52.25 s for the two predicted-localization settings, and by 154.45 s with gold guidance, although token effects remain heterogeneous across models. Overall, Loc2Repair shows file-level localization is a consistent repair lever, improving effectiveness and mean latency in pooled analysis, while gold-guided failures expose headroom beyond localization.
### Title:
          Dense Structural Priors for Sparse Functional Landmark Localization in Surgical Videos
 - **Authors:** Chenyan Jing, Hao Ding, Lalithkumar Seenivasan, Jacob M. Delgado López, Mathias Unberath
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision foundation models such as SAM 3 can provide transferable object-level structure across diverse surgical video conditions, but segmentation outputs do not explicitly encode the action-conditioned semantics that define functional surgical landmarks. Estimating instrument extent and geometry differs from localizing the tip or anchor relevant to clipping, grasping, or dissecting. We investigate vision foundation model-enabled sparse action-aware landmark localization, using zero-shot, point-prompted structural masks to provide dense instrument-level context without manual pixel-level mask annotations. We propose a lightweight refinement framework that uses SAM 3 as a structural prior. A coarse multi-frame network predicts tip and anchor prompts, generating non-oracle masks that are fused with visual and heatmap features to refine functional landmark predictions. We compare direct mask-augmented supervision, prediction-derived mask-prior refinement, and auxiliary mask supervision to examine how vision foundation model-derived structure should enter a precision-oriented localization system. Experiments on 7,867 clips from 60 surgical videos spanning YouTube, Cholec80, HeiChole, SurgVU, and CRCD evaluate the approach under heterogeneous conditions. Without manual pixel-level mask annotations for training, the proposed model achieves overall F1 scores of 72.4% for tip and 58.0% for anchor localization. Directly imposing masks on heatmap targets biases learning toward broad tool regions, whereas prediction-derived priors and auxiliary supervision provide effective intermediate structural guidance for action-dependent landmark prediction.
### Title:
          CORTEX: Token-Level Hallucination Detection in RAG via Comparative Internal Representations
 - **Authors:** Kazuaki Furumai, Shuichiro Haruta, Kazunori Matsumoto, Daisuke Kamisaka
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we propose CORTEX, a token-level hallucination detection method for Retrieval-Augmented Generation (RAG). In long-form RAG outputs, hallucinations often arise in localized spans rather than throughout an entire response. CORTEX therefore identifies ungrounded content at the token level, enabling fine-grained localization of hallucinations. The key intuition behind CORTEX is that tokens grounded in retrieved documents should be more strongly influenced by those documents than hallucinated tokens. To capture this document-induced effect, CORTEX compares internal representations of a large language model (LLM) under two conditions: with and without the retrieved documents. Instead of relying solely on each token's immediate sensitivity to the retrieved documents, CORTEX also leverages the propagation of document-grounded information through preceding tokens, reducing false positives for tokens whose evidence has already been absorbed into the context. Finally, CORTEX applies post-processing smoothing step that models the tendency of hallucination labels to persist over contiguous spans, reducing local noise and encouraging span-consistent predictions. Experiments on two RAG benchmarks and three LLMs show that CORTEX substantially improves token-level hallucination detection, with each component consistently contributing to performance gains.
### Title:
          AnyMatch: Supercharging Universal Multi-Modal Image Matching with Large-Scale Single-View Images
 - **Authors:** Meng Yang, Zizhuo Li, Linfeng Tang, Fan Fan, Jiayi Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-modal image matching is essential for visual localization and multi-sensor fusion, but it is hindered by the scarcity of large-scale training data with precise geometric annotations. Existing real-world datasets suffer from prohibitive costs, limited scene diversity, and errors in SfM-MVS pipelines, while synthetic methods struggle to maintain 3D geometric consistency or achieve photorealistic appearance. To address this, we propose AnyMatch, a novel framework that leverages abundant, easily accessible single-view images at minimal cost to generate rich multi-modal training data. AnyMatch integrates monocular depth estimation, 3D reprojection, diffusion-based inpainting, and crossmodal image translation to synthesize multi-view, multi-modal image pairs with 3D geometric fidelity. Crucially, our method provides annotations that strictly adhere to 3D geometric consistency through explicit 3D reprojection, avoiding SfM-MVS error accumulation. Furthermore, AnyMatch offers strong scalability, enabling controllable scene diversity and annotation difficulty via adjustable input and camera parameters. We construct Any-syn, a large-scale synthetic multi-modal dataset using AnyMatch. Experimental results show that matching networks (e.g., LoFTR, EDM, RoMa) fine-tuned on Any-syn achieve substantial performance gains on multi-modal benchmarks, exhibiting superior generalization and robustness compared to models trained on existing data.
### Title:
          PiLoT v2: Pixel-to-Orthogonal Map Alignment for Free-view UAV Geo-localization
 - **Authors:** Xinyi Liu, Xiaoya Cheng, Rouwan Wu, Zhaochen Wang, Shen Yan, Maojun Zhang, Yu Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-time, drift-free UAV geo-localization is essential for autonomous missions in GNSS-denied environments. The pioneering system, PiLoT, achieves high precision via Neural Pixel-to-3D Registration, aligning UAV video streams with a single rendered reference view from 3D meshes. However, its reliance on heavy 3D meshes incurs massive storage overheads, complex map acquisition, and significant computational rendering costs, severely hindering deployment on embedded platforms. To address these bottlenecks, we propose PiLoT v2, a lightweight yet robust evolution that shifts the paradigm to direct pixel-to-orthogonal map registration for free-view UAV geo-localization. By leveraging True Digital Orthophoto Maps (TDOMs) and Digital Surface Models (DSMs) as the reference substrate, PiLoT v2 replaces GPU-intensive 3D rendering with a highly efficient, CPU-friendly map cropping operation. To bridge the severe geometric discrepancy between these 2.5D orthogonal crops and free-view oblique UAV imagery, we train a cross-view feature registration network using a novel, large-scale geometrically annotated dataset. Furthermore, we integrate onboard sensor prior--specifically gravity direction and single-point laser rang--directly into the pose optimization manifold to enhance robustness against cross-view visual degradation. Experimental results demonstrate that PiLoT v2 achieves performance comparable to, or even exceeding, its Pixel-to-3D predecessor, while offering drastically lower storage and computational costs.
### Title:
          Seeing Through the Weights: Privacy Leakage in Scene Coordinate Regression
 - **Authors:** Oleksii Nasypanyi, Jaemin Cho, Utku Ozbulak, Byungkon Kang, Francois Rameau
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scene Coordinate Regression (SCR) methods are increasingly adopted for visual localization. In these approaches, the scene is implicitly encoded within a neural network that regresses a 3D world coordinate for each image pixel. Because the scene is represented only through the network parameters and not stored explicitly as images or maps, such methods are often assumed to be privacy-preserving. In this work, we show that this assumption is incorrect in practice. Specifically, we introduce a query-based attack that reconstructs the 3D geometry of the training environment from an SCR model under different levels of model access. To do so, we repeatedly query the model with batches of proxy images unrelated to the target scene to obtain dense pixel-wise 3D coordinates. Reliable points are identified through their stability under small input perturbations and can be further refined in a white-box setting. These stable points are accumulated across independent query batches to recover the scene geometry. From the recovered 3D representation, we also invert the network features to synthesize images from arbitrary viewpoints, revealing additional appearance information. Experiments on indoor and outdoor datasets demonstrate that substantial portions of training environments can be reconstructed with high geometric fidelity. Beyond geometry, we also recover an approximate color appearance, which exposes recognizable layout and potentially sensitive scene elements. This directly contradicts claims in the literature that SCR representations are privacy-preserving by design, and reveals a real risk when such systems are deployed in private or security-critical spaces. The project page is available at this https URL.
### Title:
          GaussianMap: Learning Gaussian Representation for Multi-Sensor Online HD Map Construction
 - **Authors:** Hongyu Lyu, Julie Stephany Berrio Perez, Mao Shan, Stewart Worrall
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving systems benefit from high-definition (HD) maps that provide critical information about road infrastructure. The online construction of HD maps offers a scalable approach to generate local vectorized maps from onboard sensor observations. Existing methods commonly adopt bird's-eye-view (BEV) features as the intermediate scene representation, encoding the surrounding space with fixed-resolution dense grids. However, map elements are spatially sparse yet require fine-grained geometric localization, making uniformly allocated BEV representations redundant and less effective for vectorized map prediction. In this work, we propose GaussianMap, an online HD map construction framework that learns an adaptive Gaussian representation of the surrounding scene. This representation consists of a set of Gaussian primitives on the BEV plane, each encoding a flexible local region with geometric properties and a feature vector, allowing the model to allocate representational capacity to map-relevant regions. To generate such a representation from sensor observations, we introduce a feed-forward Gaussian encoder that progressively refines these primitives through Gaussian interaction modeling and multi-sensor feature aggregation. The refined Gaussian representation is then splatted into a BEV feature map and decoded into vectorized map predictions. Extensive experiments on nuScenes and Argoverse 2 datasets demonstrate that GaussianMap achieves state-of-the-art performance in both camera-only and camera-LiDAR fusion settings. Our code will be made publicly available.
### Title:
          FeatX: Editing Software by Editing Features for Repository-Level Code Evolution
 - **Authors:** Xutian Li, Yifeng Zhu, Xianlin Zhao, Yanzhen Zou, Lu Zhang, Bing Xie
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) are increasingly used for software evolution, yet most interaction paradigms remain code-centric and require manual context management and prompt iteration. We present FeatX, a feature-oriented tool for editing software by editing features. Given an existing repository, FeatX extracts a hierarchical epic-feature structure with explicit feature-to-code mappings, then invokes a three-stage Evolution Agent to translate feature edits into code patches. The workflow is exposed through four coordinated panels. Across a controlled user study and replay experiments on 38 real-world feature-editing commits, FeatX significantly reduces cognitive load and improves usability compared with vanilla ChatGPT. It also achieves a 42.6\% relative improvement in function-level modification localization F1 over strong LLM baselines, at substantially lower cost (\$0.07 in total). The tool and collected dataset are available at this https URL, with a demonstration video at this https URL.
### Title:
          CooperScene: Multi-Modal Cooperative Autonomy Benchmark with C-V2X Communication Characterization
 - **Authors:** Bo Wu, Ruoshen Mo, Justin Yue, Yanyu Zhang, Janice Nguyen, Guoyuan Wu, Amit Roy-Chowdhury, Matthew J. Barth, Hang Qiu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cellular vehicle-to-everything (C-V2X) enables cooperative perception, prediction, and planning beyond the field of view of individual agents. However, existing datasets often overlook the complexities of real-world deployment, such as limited communication bandwidth and its dynamics, heterogeneous sensing modalities, and scalability beyond a single cooperative partner. In this paper, we introduce CooperScene, a high-fidelity cooperative autonomy dataset with real-world C-V2X communication characterization. The dataset is organized into diverse scenes, including intersections, highway ramps, and parking lots. These scenes involve three connected and autonomous vehicles (CAVs) and one infrastructure roadside unit (RSU), all equipped with multi-modal sensors and commercial off-the-shelf C-V2X communication radios. All scenes are annotated with globally consistent 3D labels at 10 Hz, totaling 344K objects across 59K frames, underpinned by tight sensor- and agent-synchronization, centimeter-level localization and spatial alignment, precise cross-modality calibration, and 3GPP-standard-compliant C-V2X communication. CooperScene establishes a rigorous benchmark for evaluating multi-agent scaling and actual performance in real-world deployable settings. Project website for data and benchmark: this https URL
### Title:
          Beyond Binary Instrument QA: Probing Instrument Grounding in Music Audio-Language Models
 - **Authors:** Yujun Lee, Joonhyeok Shin, Hyoeun Kim, Kyuhong Shim
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent music audio-language models achieve high accuracy on instrument question-answering benchmarks, but it remains unclear whether this reflects robust audio grounding or benchmark-specific shortcuts. In this paper, we introduce an OpenMIC-derived diagnostic benchmark sequence for instrument grounding in music audio-language models, extending binary instrument-presence QA to genre-prior-reduced examples, confusable instrument discrimination, longer audio context, and temporal localization. Across these settings, high binary QA accuracy often fails to predict model behavior: models can exhibit option-position bias, confusable-instrument errors, and temporal response bias. These results suggest that instrument grounding should be evaluated with multi-axis diagnostic benchmarks rather than a single aggregate accuracy.
### Title:
          Domain Adaptive Object Detection via Dual-Stream Bilevel-Cycle Optimization
 - **Authors:** Yannan Chen, Wenqiang Wang, Ruoyu Chen, Jiancheng Wang, Mingbo Yang, Yaowei Wang, Wei Wang, Xiaochun Cao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cycle self-training (CST) breaks the shared classifier assumption of the standard self-training framework, which is effective for unsupervised domain adaptation and exploits unlabeled target data by training with target pseudo-labels. CST introduces a target classifier and employs an inner-outer loop updating strategy, addressing the issue of unreliable pseudo-labels and enabling pseudo-labels to generalize across domains. Despite its success in image classification, extending CST to object detection faces three main challenges. First, the upper bound of CST in object detection is constrained by three types of unreliable pseudo-labels, such as classification error alone, localization error alone, and their combination. Second, since object detection involves detecting multiple target objects, directly applying CST leads to training insta bility. Third, a wider numerical range of regression coordinates leads to exploding losses. To this end, we apply CST to both classification and regression and propose the Dual-Stream Bilevel-Cycle Optimization framework. Specifically, we construct CST upon Mean Teacher to prevent training instability and use extra normalization to map the regression bounding box into a standardized space, effectively addressing exploding losses. Also, we provide a theoretical derivation of the regression bound. Extensive experiments across four cross domain standard scenarios demonstrate that our framework achieves considerable results.
### Title:
          MV-GEL: Language-Driven Multi-View Geometric Entity Localization on Meshes
 - **Authors:** Kartik Bali, Roland Aydin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Identifying and grounding precise geometric entities, such as edges, planar regions, and curved surfaces within 3D objects, is foundational to computer-aided design (CAD), robotic manipulation, and scientific simulation. Although modern Vision Language Models (VLMs) have advanced referring segmentation (RIS) in the image domain, extending such language-driven localization to structured 3D geometry is substantially harder. The 3D object appearance is highly sensitive to viewpoints; a single perspective may render a target entity clearly observable, while another may suffer from severe occlusion or foreshortening. In this work, we attempt to solve these challenges with MV-GEL (Multi-View Geometric Entity Localization), a framework for localizing fine-grained geometric entities on polygon meshes from natural language queries. Our key insight is that reliable CAD entity (i.e., faces, edges or solids) localization depends on selecting views that make the queried entity maximally interpretable. We introduce GELviews, a prompt-conditioned ranking module that prioritizes viewpoints based on language prompted observability of geometric CAD entities. Selected views are processed by a VLM-based reasoning segmentation backbone, and predicted masks are lifted to the corresponding meshes via geometry-aware ray casting. Our framework is completely CAD agnostic and relies only on 3D meshes. Experiments show up to a 1.7X improvement in face-level IoU and over 4.5X gains in edge-level F1 compared to vanilla baselines, substantially outperforming CLIP-based and random view sampling, particularly for thin and view-sensitive this http URL dataset, code and trained checkpoints are available at this https URL.
## Keyword: transformer
### Title:
          ASR-Agnostic Multimodal Spectrotemporal Modeling for Early Dementia Detection
 - **Authors:** Chukwuemeka Ugwu, Oluwafemi Richard Oyeleke
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Speech recruits the same executive, attentional, and working memory processes underlying instrumental activities of daily living, or IADLs, providing a non-invasive proxy for cognitive assessment. Yet most speech-based dementia detection systems depend on transcription, discard within-recording temporal structure, and are validated on a single English corpus with known recording artifacts. We propose an ASR-agnostic framework operating directly on Mel spectrograms. Our key contribution is extracting spectrotemporal displacement fields from consecutive spectrogram frames, capturing shifting spectral energy patterns as digital biomarkers of cognitive decline. These features are fused with CNN-ConvGRU acoustic embeddings via a learned cross-attention mechanism and aggregated using a Transformer encoder with learnable query pooling. A composite temporal loss enforces smoothness and contrastive coherence across segments. We train independent models on English DementiaBank, Slovak EWA-DB, and Spanish Ivanova corpora, using clinical elicitation protocols taxing IADL-relevant cognitive domains. The Slovak model achieves 83.9% accuracy, and Spanish achieves, while the English baseline yields 53.2%, confirming known artifacts. Cross-lingual ablation studies reveal distinct fusion regimes: removing cross-attention collapses Spanish performance to 53.7%, below unimodal models, while the Slovak audio encoder alone outperforms the full model, 93.7% vs. 83.9%, and all English configurations remain near chance. Thus, multimodal fusion's value is corpus-dependent: essential when signal is distributed across modalities, counterproductive when one dominates, and irrelevant when no signal exists. Auxiliary temporal losses converge to language-invariant values, indicating cross-lingual architectural stability.
### Title:
          PolyFlow: Continuous Topology Embedding Flow Matching for Artist-style Mesh Generation
 - **Authors:** Chunshi Wang, Haohan Weng, Junliang Ye, Biwen Lei, Yang Li, Zibo Zhao, Zeqiang Lai, Kaiyi Zhang, Yunhan Yang, Zhuo Chen, Chunchao Guo, Yawei Luo
 - **Subjects:** Subjects:
Graphics (cs.GR); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autoregressive Transformers dominate high-quality mesh generation by producing artist-worthy topologies, yet their inherent sequential decoding induces substantial computational overhead, falling orders of magnitude slower than parallel generative models. On the other hand, while continuous diffusion and flow-matching methods support efficient parallel synthesis across a variety of domains, they cannot be directly applied to meshes: mesh connectivity is inherently discrete and incompatible with standard continuous noise injection and denoising operations. To resolve this fundamental incompatibility, we introduce a compact topology embedder that projects discrete mesh vertex positions and normals into continuous per-vertex embeddings, where the original discrete adjacency information can be faithfully recovered via spacetime distance thresholding. After pretraining and freezing this embedder, any raw mesh can be fully converted into a continuous per-vertex state space unifying position, normal, and implicit topological attributes. Built upon this novel continuous mesh representation, we present PolyFlow, a Transformer-based flow-matching framework that achieves fully parallel vertex state denoising conditioned on extracted point-cloud features. During inference, our model completes generation rapidly via an ODE solver, and supports explicit, precise control over output mesh resolution by directly specifying the target vertex count. Extensive evaluations on the Toys4K benchmark demonstrate that PolyFlow surpasses state-of-the-art autoregressive baselines in both Chamfer Distance and Hausdorff Distance.
### Title:
          Hierarchical Global Attention (HGA)
 - **Authors:** Woernle Frank, Fedosov Vladimir, Grinenko Artemiy
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hierarchical Global Attention (HGA) is a drop-in replacement for dense causal attention in pretrained long-context transformers. HGA preserves the original checkpoint parameters: the pretrained $W_Q$, $W_K$, $W_V$, and $W_O$ projections remain unchanged, no calibration parameters are introduced, and no retraining is required. Applied to Qwen3-30B-A3B-Instruct-2507-FP8 on a single RTX~5090 (32GB), the patched model runs out of the box at a 64K-token context, where token-level K/V storage is not feasible on this hardware. Unlike previous sparse-attention methods, HGA performs hierarchical two-level routing. It first retrieves relevant chunks using compact RoPE-aware summaries and then refines the selection by routing only the most relevant groups before performing exact token-level attention. This hierarchical retrieval significantly reduces the number of fetched tokens while preserving exact attention over the retrieved token set, making RAM- and NVMe-backed storage practical. The full historical token K/V resides in host RAM or NVMe storage, while only a small routed working set is transferred to GPU memory during attention. Consequently, GPU memory consumption depends primarily on model weights and the routed working set rather than on the total context length. Across all tested context lengths (4K - 64K tokens), routed attention remains within approximately $0.01$--$0.02$ nats of dense attention while the sparsity used is just about 3%. These results suggest that the approximation introduced by hierarchical routing is small, and that the remaining quality gap is likely dominated by long-context positional encoding rather than by the routing algorithm itself.
### Title:
          Probing-Guided Layer Selection from Self-Supervised Speech Models for Generalizable Audio Deepfake Detection
 - **Authors:** Marjan Beheshti, Majid Rostami, Bo Chen
 - **Subjects:** Subjects:
Sound (cs.SD); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Audio deepfake detection systems often fail to generalize across domains because they rely on features tied to specific attacks or recording conditions. Self-supervised speech models offer rich multi-layer representations, yet existing approaches either use a single layer or fuse all layers indiscriminately, and only reveal layer importance after training. We propose a model-agnostic, two-stage methodology that identifies informative depth zones before any task-specific model is trained. In the first stage, lightweight XGBoost probes evaluate each transformer layer's cross-domain discriminative power, producing a layer ranking. In the second stage, a compact neural classifier fuses only the selected layers through per-layer attention pooling and a shared bottleneck projection, while the backbone remains frozen. Applied across three backbones, the probing reveals two key findings. First, informative layers cluster in depth zones rather than at uniquely optimal positions: within-zone substitutions fall within multi-seed noise, while zone violations degrade performance by up to 5x. Second, the probing produces backbone-specific selections rather than a fixed layer recipe. On XLS-R-300M, four probing-selected layers with 1.34M trainable parameters achieve 4.94 +/- 0.32% equal error rate on In-The-Wild and 5.07% cross-domain average over four shared datasets, a 28% relative improvement over the best prior frozen-backbone result (Xiao and Vu, 2025) using all 25 layers with identical training data.
### Title:
          AVTok: 1D Unified Tokenization for Holistic Audio-Video Generation
 - **Authors:** Kien T. Pham, I Chieh Chen, Qifeng Chen, Long Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Multimedia (cs.MM); Sound (cs.SD); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Audio-video generation has recently gained unprecedented research attention, aiming to synthesize high-quality sounding video content with fine-grained synchronization and semantic alignment between the auditory and visual components. The preceding methods predominantly adopt a dual-branch design with separate tokenization and generation modules per modality, neglecting the representation gap while necessitating intensive computational resources for proper training. Inspired by recent advancements in one-dimensional visual tokenization, we present \textbf{AVTok}, a novel unified tokenizer designated for holistic audio-video generation. AVTok features a dual-stream transformer-based architecture with shared encoder-decoder and modal-specific learnable queries to efficiently and effectively encode an audio-video pair into a compact one-dimensional latent representation with a unified codebook. To cope with the heterogeneous information imbalance that hinders AVTok from exploiting aligned audio-visual information, we devise a hierarchical training strategy to progressively realize reconstruction capabilities for each modality. Extensive experiments demonstrate that AVTok excels both in audio-video reconstruction and when integrated into downstream pipelines for audio-to-video, video-to-audio, and class-conditional joint audio-video generation. AVTok paves the way for the challenge of joint audio-video tokenization and provides a potential direction to build unified large multimodal models for audio-video generation.
### Title:
          Gradient Smoothing: Coupling Layer-wise Updates for Improved Optimization
 - **Authors:** Haoming Meng, Anton Sugolov, Vardan Papyan
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep neural networks with repeated architectural blocks, such as transformers, often exhibit structured relationships across layers that emerge during training. Motivated by this observation, we introduce \emph{Depth-wise Gradient Augmentation}, a general optimization paradigm in which the update applied to each layer is obtained by transforming the collection of block-wise optimizer updates along the depth dimension. Within this framework, we study \emph{Gradient Smoothing}, a family of depth-wise smoothing methods, and instantiate it with a simple local \emph{Window Smoothing} operator. The resulting method operates directly on block-wise updates produced by arbitrary base optimizers (e.g., SGD, Adam, Muon), incurs minimal computational overhead, and is compatible with existing optimization pipelines. We evaluate Gradient Smoothing across a diverse set of architectures and training regimes, including language model pretraining, RL post-training of LLMs for reasoning, diffusion modeling, and image classification with Vision Transformers. Across these settings, Gradient Smoothing consistently improves optimization and generalization performance without modifying model architectures or training objectives. We further show that it promotes more structured representation evolution across depth, consistent with its interpretation as a structured depth-wise preconditioning method. Together, these results establish Depth-wise Gradient Augmentation as a promising framework for exploiting cross-depth structure in optimization and demonstrate Gradient Smoothing as a simple and broadly applicable instantiation.
### Title:
          When transformers learn "impossible" languages, what do they learn?
 - **Authors:** Ram Janarthan, Coleman Haley, Sharon Goldwater
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent work suggests that transformer language models show a bias towards human languages over unnatural ("impossible") languages argued to be unacquirable by humans. However, this literature has largely based these claims on differences in sample efficiency and test-set perplexity, rather than on direct evaluations of the linguistic capacities that could plausibly explain non-attestation in human languages. We evaluate two theoretically motivated linking hypotheses: impossibility arising from deficiencies in grammatical sensitivity or generative production. Using GPT-2 style models trained on perturbed "impossible" variants of English, we measure sensitivity to grammaticality using BLiMP minimal pairs, finding that model performance exhibits only gradual degradation, mediated by the language's information locality. In contrast, these models exhibited pronounced failures in generation, producing substantially fewer high-quality sentences at longer lengths. Together, these results suggest generative deficiency and transmission failures as a plausible linking hypothesis between language model behaviour and non-attestation of impossible languages.
### Title:
          How Can AI Find My Model? A Model-Finding Experimental Study Considering Data Formats, Embeddings, and Retrieval Strategies
 - **Authors:** Jhon G. Botello, Jose J. Padilla, Erika Frydenlund, Krzysztof Rechowicz, Eric Weisel
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Discovering simulation models for reuse remains a fundamental challenge in Modeling and Simulation (M&S). When many models coexist, identifying those that align with a given modeling intent remains difficult. Recent advances in Artificial Intelligence (AI), particularly retrieval-based approaches, offer a promising pathway to operate at this semantic layer. In this paper, we present an experimental study investigating the impact of data representation, transformer-based embedding models, and retrieval strategies on the discovery of simulation models using natural language queries. We evaluated performance across multiple query types using standard information retrieval metrics, including recall@5 and nDCG@5. Results show that data representation matters, open-source embedding models can achieve high performance, and reranking methods are important, especially as query complexity increases. This work provides a baseline for AI-driven model discovery and discusses its role in advancing toward AI-driven composability and interoperability.
### Title:
          SyncCache: Exploiting Asymmetric Dynamics for Fast Audio-Driven Portrait Animation
 - **Authors:** Juncheng Ma, Yuxuan Du, Yanan Sun, Zhening Xing, Changlin Li, Zhenyu Tang, Bo Li, Peng-Tao Jiang, Li Yuan, Daquan Zhou, Yonghong Tian
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Sound (cs.SD); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformers (DiTs) have significantly advanced audio-driven portrait animation, but their high computational cost leads to substantial inference latency. Although training-free diffusion caching accelerates inference significant, existing methods are primarily developed for text-conditioned generation and overlook the spatial and modality imbalances inherent in audio-driven portrait animation. In this paper, we propose SyncCache, a training-free caching acceleration method tailored for DiT-based portrait animation that explicitly exploits asymmetric dynamics. Specifically, high-frequency dynamics driven by audio conditions and concentrated in human regions are more challenging and critical to cache and reuse than the low-frequency visual background in portrait animation. First, we introduce Spatially-Asymmetric Probing to prioritize error sensitivity in dynamic human region. Second, through Modality-Decoupled Caching, we bypass heavy DiT block by reusing stable inter-block residuals, while continuously recomputing lightweight audio blocks to preserve precise lip synchronization. Furthermore, we introduce a cache ratio to control cache capacity and formulate memory-adaptive cache selection as an offline dynamic programming problem without online overhead. Extensive experiments demonstrate that SyncCache achieves superior speed-quality trade-offs, delivering up to 4.12x acceleration on HunyuanVideo-Avatar and 3.75x on Wan-S2V with near-lossless visual fidelity and precise audio alignment.
### Title:
          Multilingual Polarization Detection Using Transformer-Based Models with Class Weighting and Threshold Tuning
 - **Authors:** Aaron Bundi Anampiu
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper describes our submission to SemEval-2026 Task 9 on detecting multilingual, multicultural, and multievent online polarization. We address all three subtasks: binary polarization detection, polarization type classification, and manifestation identification for English and Swahili. Our approach leverages transformer-based models (RoBERTa-base for English, AfroXLMR-base for Swahili) with class-weighted loss functions to address severe label imbalance and per-label threshold tuning to optimize multi-label classification. On the test set, we achieve F1 macro scores of 0.7901 (English) and 0.7910 (Swahili) for Subtask 1, 0.4615 (English) and 0.4808 (Swahili) for Subtask 2 and 0.4791 (English) and 0.5830 (Swahili) for Subtask 3, which give competitive performance on the leaderboard, demonstrating the effectiveness of our methods for handling imbalanced multi-label polarization detection. Our error analysis reveals that models struggle with dehumanization detection and lack of empathy.
### Title:
          Quality-Aware Modulation for Diffusion Transformers
 - **Authors:** Luke Budny, Yuhong Guo, Kevin Cheung
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern text-to-image diffusion models, such as diffusion transformers (DiT), rely on timestep or prompt embeddings to modulate the strength of the denoising process in each timestep. While this modulation communicates the current noise level, it does not provide any quality-aware information, which can lead to generated images that are unaligned, visually inconsistent, and lacking in fidelity. In this paper, we propose the Quality Representation Module (QRM), a lightweight transformer module that learns a quality-aware representation based on existing model inputs, and produces a set of vectors $M_{qrm}$. These vectors adjust the adaptive LayerNorm modulation within the DiT transformer blocks, thereby injecting a quality-sensitive signal into the denoising parameters. The QRM introduces no significant changes to the sampling schedule or diffusion backbone. Experiments include ablations on QRM training losses and architectures, as well as empirical results demonstrating consistent image quality improvements over baseline DiT-based models.
### Title:
          Dual Sparse Aggregation Transformer for Multispectral Object Detection
 - **Authors:** Wencong Wu, Xiuwei Zhang, Hanlin Yin, Hongxi Zhang, Yanning Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based approaches have obtained excellent performance in multispectral object detection tasks due to their ability to model long-range dependencies and capture complementary information. However, previous transformer-based multispectral detection methods tend to use all available tokens for similarity calculation, which results in redundant information interaction from irrelevant areas, leading to degraded detection performance. To overcome this challenge, we propose a novel Dual Sparse Aggregation Transformer (DSAFormer) for multispectral object detection, which consists of a Dual Sparse Transformer (DSFormer) and a Learnable Addition Fusion Block (LAFB). Specifically, the DSFormer is designed to exploit and boost cross-modal complementary information, thereby improving detection performance. It incorporates three key components: A Spatial Sparse Multi-Head Cross-Attention (SSMHCA) mechanism selectively captures cross-modal relationships at the spatial level by reserving only the high query-key similarity scores, eliminating irrelevant interactions. A Channel Sparse Multi-Head Cross-Attention (CSMHCA) mechanism performs similar sparse calculations at the channel level to enhance feature representation and filter out low matching query-key. A Multi-Scale Feature Refinement Layer (MSFRL) is developed to aggregate hierarchical features and suppress redundant information. To effectively fuse multimodal features, the LAFB is introduced to aggregate intramodal and intermodal feature information by feature reweighting. Extensive experimental results have demonstrated that our proposed DSAFormer achieves better detection performance against state-of-the-art methods on four public datasets, including the MFAD, FLIR, M$^3$FD, and LLVIP. The source code of our DSAFormer will be released at this https URL.
### Title:
          GenPage: Towards End-to-End Generative Homepage Construction at Netflix
 - **Authors:** Lequn Wang, Jiangwei Pan, Fengdi Che, Linas Baltrunas
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present GenPage, an end-to-end generative approach to Netflix homepage construction that replaces the traditional multi-stage recommender stack with a single transformer. GenPage treats the user and request context as a prompt, and autoregressively generates the entire structured, multi-row homepage as the response. We adapt the LLM training recipe: pretraining on production pages, followed by post-training via weighted binary classification (WBC) or reinforcement learning (RL). For industry-scale deployment, we introduce techniques addressing cold start, model freshness, business-rule enforcement, and serving efficiency. In online A/B tests against a mature, highly optimized production homepage recommender, the WBC variant of GenPage delivered a +0.24% lift on the core user engagement metric we use for launch decisions (p < 0.001), while reducing end-to-end serving latency by 20%. Offline, two findings stand out: enriching the prompt yields a larger improvement than scaling model capacity in our current regime, and RL post-training increases homepage diversity even though diversity is not part of the objective.
### Title:
          Hybrid Unet-Transformer Model for Generating Stress and Strain Fields from Composite Geometrics
 - **Authors:** Shrey Patel
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate prediction of stress and strain fields in hierarchical composite microstructures is critical for physics-informed material design, yet conventional finite element method (FEM) simulations are computationally prohibitive at scale, requiring minutes to days per evaluation. In this work, we propose a hybrid UNet-Transformer architecture that predicts complex mechanical field distributions directly from composite microstructure geometry images, serving as an efficient surrogate for FEM across ten distinct stress and strain field types spanning diverse two-phase composite configurations including square, hexagonal, and triangular tessellations, multiple boundary conditions, and high-resolution geometries. Results demonstrate that the proposed architecture achieves strong predictive performance across the majority of subdatasets, with peak accuracy on periodic tessellation geometries reaching R2=0.9991, SSIM=0.9936, and MAE=0.0050 on the boundary condition subdataset and the triangular tessellation subdataset respectively. Across six of the eight evaluated subdatasets, MAE remains below 0.05 on the normalized [0,1] pixel scale. Encoder attention analysis via Grad-CAM and Grad-CAM++ confirms that the model develops physically meaningful internal representations, localizing attention at mechanically critical regions including phase boundaries, ligament junctions, and indenter contact zones without explicit structural supervision. Performance degrades on irregular square-grid geometries with sparse soft-phase inclusions, with the S11 normal stress subdataset yielding R2=0.7735 and SSIM=0.7126, consistent with the known limitation of smooth-loss image translation models in reproducing sharp stress discontinuities.
### Title:
          TaxoMIL: Taxonomy-Constrained Learning for Hierarchical Whole Slide Image Analysis
 - **Authors:** Chaeyeon Lee, Khang Nguyen Quoc, Jinsol Song, Yosep Chong, Kwangil Yim, Jin Tae Kwak
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Whole slide image (WSI) analysis is central to computational pathology, with multiple instance learning (MIL) emerging as the standard pipeline for slide-level diagnosis. However, conventional approaches formulate WSI diagnosis as a flat classification task over discrete labels, contradicting the inherently hierarchical, coarse-to-fine nature of clinical reasoning. Although recent hierarchical classifiers and vision-language models (VLMs) have sought to address this structural gap, they either fail to capture semantic continuity between related diagnoses or suffer from unconstrained text generation that produces taxonomic hallucinations and parent-child label violations. To address these limitations, we propose TaxoMIL, a taxonomy-constrained framework that reformulates WSI diagnosis as a multi-granularity text generation task. TaxoMIL utilizes a dual-head Transformer decoder to generate coarse- and fine-level diagnostic text, and introduces taxonomy-guided objectives that explicitly structure the label embedding space and strictly ground slide-level visual representations within the clinical taxonomy. Extensive experiments across three diverse WSI datasets demonstrate that TaxoMIL consistently outperforms state-of-the-art MIL classifiers and VLM-based generative methods, yielding accurate and hierarchy-aware diagnostic predictions. The code is released at this https URL
### Title:
          Revealing Safety-Critical Scenarios for UTM via Transformer
 - **Authors:** Huaze Tang, Bill Zeng, Chao Wang, Zhenpeng Shi, Qian Zhang, Wenbo Ding
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unmanned Traffic Management (UTM) systems are cloud-based platforms designed to manage and coordinate multiple aerial vehicles remotely. UTM systems are safety-critical which cannot tolerate failures like crash or collision. To reveal latent vulnerabilities, there are neither optimal failure-exposing demonstrations nor clear reward signals. Additionally, UTM's self-healing capability introduces the ``long-tail effect'' of critical failures. We propose framing UTM vulnerability discovery as a sequence modeling problem amenable to transformer-based RL architectures. Our approach leverages attention mechanisms to directly model the relationship among system states, and predict optimal actions. Our framework introduces a Policy Model that generates targeted test scenarios and an Action Sampler that enforces domain constraints. We use a risk-based reward function to guide exploration. Through extensive evaluation on a 700-hour simulation study, we demonstrate an 8$\times$ improvement in vulnerability discovery efficiency compared to expert-guided testing. It also discovers critical edge cases that traditional methods have missed.
### Title:
          UniSAE: Unified Speech Attribute Editing on Speaker, Emotion and Low-Level Content via Discrete Phonetic Posteriorgram Modelling
 - **Authors:** Chuanbo Zhu, Wuyou Zhou, Rongxiu Zhong, Shilei Zhang, Kun Qian, Yike Guo, Wei Xue
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Speech editing aims to modify specific portions of an utterance while preserving the remaining speech. Existing approaches primarily focus on word-level content modification and typically treat content, speaker, and emotion editing as separate tasks, limiting both editing granularity and flexibility. We propose UniSAE, a unified speech attribute editing framework which supports composable speaker, emotion and content editing from sub-phoneme to word level within a single architecture. UniSAE introduces a Discrete Phonetic PosteriorGram (DPPG) representation that factorizes speech content into discrete tokens encoding phoneme identity, pronunciation variants, and duration, enabling direct phoneme- and sub-phoneme-level editing. For higher-level modifications, an autoregressive content transformer predicts edited DPPG sequences for word-level content editing. The edited sequences are rendered into speech by a diffusion-based acoustic decoder, conditioned on disentangled speaker and emotion representations. Experimental results demonstrate that the proposed unified framework supports precise speaker and emotion control, content editing at multiple granularities, and joint modification of all three attributes within a single framework.
### Title:
          TAG-DLM: Diffusion Language Models for Text-Attributed Graph Learning
 - **Authors:** Lingjie Chen, Yuanchen Bei, Haobo Xu, Yanjun Zhao, Yuzhong Chen, Hanghang Tong
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-attributed graphs (TAGs), where each node carries a natural language description, require models to jointly reason over text and graph topology. Existing approaches often handle the two modalities separately: graph neural networks operate on shallow text features, while hybrids of LLMs and graphs use the language model mainly as a text encoder and delegate structure learning to a separate graph module. We propose method that unifies textual reasoning and graph message passing within a masked diffusion language model, a language model with bidirectional attention and generative decoding. For each graph instance, method linearises a sampled local neighbourhood into a token sequence and injects graph structure through a topology attention mask, which realises message passing over the graph. Because the diffusion language model can both interpret and generate text, the method adapts to different tasks simply by changing the prompt, supporting node classification, link prediction, and cross-dataset transfer with no target-specific fine-tuning. Experiments show that method outperforms graph neural networks, graph transformers, and LLM-based baselines on all three TAG benchmarks across two tasks, improving over the strongest baseline by up to 3.9 points.
### Title:
          HSDF-Lane: Height-Aligned Signed Distance Field with Semantic Lane Prior for 3D Lane Detection
 - **Authors:** Jiyong Boo, Byeongin Joung, Hyemin Yang, Kuk-Jin Yoon
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular 3D lane detection plays a critical role in autonomous driving, yet recovering reliable 3D geometry from a single image remains challenging due to inherent depth ambiguity. Prior methods project image features into Bird's-Eye-View (BEV) space under a flat-ground assumption, causing geometric distortion on real-world roads. Recent methods instead predict explicit height maps to capture non-planar surfaces, but still rely on sparse anchor-based regression and exploit the recovered geometry merely for spatial transformation rather than semantic understanding. To overcome these limitations, we propose HSDF-Lane, which implicitly models the road surface as a Height-aligned Signed Distance Field (HSDF) over a densely sampled 3D feature volume. Through differentiable rendering, the HSDF jointly produces an accurate height map and surface-aligned features. We further introduce Lane-aware Semantic Positional Encoding (LSPE), which injects a lane-existence prior derived from the surface-aligned features into the transformer queries, coupling geometric structure with semantic guidance. Extensive experiments on the OpenLane benchmark show that HSDF-Lane achieves state-of-the-art performance in both 3D lane detection and height map estimation.
### Title:
          Transformers as Bayesian In-Context Experimenters: Smoothness-Adaptive Efficient ATE Estimation
 - **Authors:** Jiachun Li, David Simchi-Levi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adaptive experiments for average treatment effects (ATE) require randomized allocations balancing valid inference with statistical efficiency. The oracle design is a covariate-dependent Neyman rule governed by unknown arm-conditional outcome variances. We investigate whether this sequential variance-estimation and allocation process can be amortized via in-context learning. We introduce Bayesian in-context experimenters: transformer policies trained to imitate a Bayesian posterior Neyman teacher. The teacher updates nonparametric beliefs over potential outcomes using experimental history to assign posterior Neyman treatment probabilities. This design converges to the oracle rule, supporting efficient ATE inference. Transformers constructively implement this mapping through attention-based sufficient statistics and projected gradient descent, imitating Bayesian updating for Gaussian-series priors. To address unknown outcome smoothness, we combine smoothness-indexed experimenters using a mixture-of-experts transformer. The gate acts as a hierarchical posterior over smoothness classes, concentrating on near-oracle experts. By bounding the complexity of the transformer class, we prove this amortized policy can be learned via empirical risk minimization using supervised pretraining. Experiments confirm accurate teacher imitation, adaptive allocation, and improved ATE precision over baselines.
### Title:
          Editing Everything Everywhere All at Once
 - **Authors:** Fabio Quattrini, Carmine Zaccagnino, Enis Simsar, Marta Tintoré Gazulla, Rita Cucchiara, Alessio Tonioni, Silvia Cascianelli
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Editing multiple elements of an image in a single forward pass is a practical alternative to multi-turn image manipulation, offering improved efficiency and potentially better harmonization. However, when several instructions target different regions, semantic interference often leads to attribute leakage and poor edit disentanglement, especially as the number of edits increases. In this work, we propose MICE (Multi-Instance Concurrent Editing), a training-free strategy for scalable multi-instance image editing with Multimodal Diffusion Transformers. MICE modifies the additive bias of joint attention to regulate interactions between instance-specific edit instructions, latent, and context tokens identified via user-provided segmentation masks. Specifically, MICE allows intra-instance attention, penalizes interactions between neighboring region tokens, and suppresses unrelated cross-instance attention. As a result, our method enforces attribute binding while preserving global visual consistency. We evaluate MICE on LoMOE-Bench and introduce MICE-Bench, a more challenging benchmark with an average of 8.5 concurrent edits per image. The experiments demonstrate that our approach outperforms strong baselines and recent competitors in terms of visual quality preservation and faithfulness to the editing instructions.
### Title:
          Patch-PODiff-ViT: Structured Latent Diffusion with Patchwise POD for Super-Resolution and Uncertainty Quantification
 - **Authors:** Onkar Jadhav, Tim French, Matthew Rayson, Nicole L. Jones
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion models enable probabilistic super-resolution and conditional generation, but pixel-space methods are computationally expensive and learned latent spaces often lack interpretable uncertainty quantification. We introduce Patch-PODiff-ViT, a structured latent diffusion framework in which the latent space is defined by patchwise Proper Orthogonal Decomposition (POD), a fixed linear orthonormal basis over local patches, rather than learned by a nonlinear autoencoder. This yields low-dimensional, variance-ordered tokens that preserve spatial structure and enable efficient diffusion in a structured low-dimensional latent space with a Vision Transformer. Because the decoder is fixed, linear, and orthonormal, latent coefficient uncertainty can be propagated directly to physical-space predictive variance, enabling analytic propagation of predictive variance through the linear decoder without Monte Carlo estimation in pixel space. Across sea surface temperature, medical imaging, and natural images, the method achieves strong reconstruction with fewer parameters and lower memory, while producing well-calibrated spatial uncertainty that closely matches empirical ensembles.
### Title:
          Dualformer: Efficient Feature Extractor for Complex-valued Blind Communication Signal Analysis
 - **Authors:** Yurui Zhao, Xiang Wang, Jingreng Lei, Wanlong Zhang, Yik-Chung Wu, Zhitao Huang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Designing effective feature extractors is critical for blind signal analysis tasks such as automatic modulation recognition (AMR), signal scheme recognition (SSR), and \color{black} signal structure parsing (SSP). In this work, we propose dual-channel neural network (DualNN) that efficiently exploits complex-valued signals through parameter sharing across IQ channels. Unlike traditional real-valued or complex-valued models, DualNN is a groundbreaking framework which shares the network parameters for processing the real and imaginary parts of the complex-valued signals, and is theoretically shown to reduce generalization error while preserving expressive capacity. Specifically, we propose a novel Transformer-based architecture to implement DualNN, called Dualformer. The Dualformer segments input signals into patch-level tokens and captures multi-granularity features, enabling robust performance across diverse signal analysis tasks. Furthermore, we conduct extensive experiments comparing Dualformer with three Transformer-based baselines and four conventional DL-based approaches. Results demonstrate consistent performance improvements on AMR, SSR, and SSP tasks. Besides, the modular design of DualNN allows it to generalize well to blind signal processing tasks such as blind source separation and low-SNR spectrum sensing. This work paves the way for a broader application of DualNN architectures in unsupervised and weakly supervised complex-valued signal analysis scenarios.
### Title:
          Mixture-of-Control: State-Aware Fine-Tuning for Transformer-based Models
 - **Authors:** Duc Anh Nguyen, Tien Ngoc Luu, Tung Pham, Toan Tran
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 State-based fine-tuning has emerged as a compelling alternative to weight-based adaptation for transformers, updating lightweight controls into states rather than model weights, offering substantial memory savings while retaining parameter efficiency. However, most existing state-based methods typically apply only per-block control updates, which limits inter-block information exchange and restricts representational adaptation. Meanwhile, prior mechanisms that enable cross-block communication often introduce considerable computational overhead, reducing their practicality for efficient fine-tuning. We introduce Mixture-of-Control (MoC), a lightweight fine-tuning framework that adaptively integrates local and global control signals to enhance representation learning. MoC treats block-wise control states as experts in a sparse mixture-of-experts process, enabling efficient communication across transformer blocks. Empirical results across diverse transformer-based benchmarks demonstrate that MoC outperforms state-based methods while maintaining a comparable memory and computational efficiency.
### Title:
          CVE-TTP KG: Knowledge Graph Linking Software Vulnerabilities to Attack Behaviors
 - **Authors:** Basant Agarwal, Dincy R. Arikkat, Swati Yadav, Serena Nicolazzo, Antonino Nocera, Vinod P
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In the evolving threat landscape, adversaries exploit software vulnerabilities to launch sophisticated attacks, challenging traditional defenses. Although databases like CVE and NVD provide detailed technical information, they often lack links to attacker behaviors such as tactics and techniques, limiting effective threat interpretation and response. This work bridges this gap by connecting vulnerabilities with behavioral patterns from the MITRE ATT&CK framework. We construct a CVE-TTP Knowledge Graph that links CVEs to tactics and techniques using classification and relation extraction. Transformer-based models are developed for behavior identification, with CySecBERT achieving macro F1-scores of 87.71% (techniques) and 96.16% (tactics). Also, we created an annotated dataset with 24,820 entities and 43,608 relations for entity and relation extraction. The pipeline-based approach achieves macro F1-scores of 0.86 (entity extraction) and 0.99 (relation extraction), while a span-based joint model achieves 0.78. These outputs are integrated into a Neo4j-based Cyber Threat Knowledge Graph, enabling structured visualization of vulnerabilities.
### Title:
          Temperature Field Reconstruction of Tungsten Monoblock Divertor on EAST using Physics-aware Neural Operator Transformer
 - **Authors:** Zikang Yan, Xiao Wang, Qingquan Yang, Zhendong Yang, Gaoting Chen, Zehua Chen, Bo Jiang, Jin Tang, Guosheng Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate modeling of the divertor temperature field is essential for preventing material melting and damage and for extending the service life of fusion devices. However, conventional numerical methods, such as the Finite Element Method (FEM), are computationally expensive and therefore unsuitable for real-time applications. Therefore, a fast and generalizable method is required for real-time reconstruction of the divertor temperature field and subsequent real-time control. To address the above issue, we propose a Physics-aware Neural Operator Transformer (PNOT) to characterize the spatiotemporal evolution of the divertor temperature field. It models boundary heat-flux relations as a structured graph and employs graph attention to explicitly capture spatial physical dependencies. Inspired by physics-aware attention, we further develop a physics-aware neural operator module to aggregate query points with similar physical conditions via slicing and model heat diffusion, while a gradient-constrained Sobolev regularization loss enforces consistency between function values and their derivatives. Experimental results show that these physical constraints improve prediction accuracy while preserving physical consistency. The source code of this paper will be released on this https URL
### Title:
          DPPE: Rethinking Camera-Based Positional Encoding for Scaling Multi-View Transformers
 - **Authors:** Shun Kenney, Teppei Suzuki
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The remarkable scalability of Transformers has expanded their application to 3D computer vision, where camera-aware positional encoding is crucial for providing spatial cues in multi-view geometry. Recent advancements have established the practice of using camera parameters -- such as extrinsics or projection matrices -- as relative positional encoding into the query, key, and value vectors of the attention mechanism. However, when scaling up the training recipe of novel view synthesis (NVS) models with the camera-based positional encoding, we observe a significant issue: model performance stagnates in the late stages of training. In this paper, we investigate the cause of the performance bottleneck when scaling up and demonstrate that storing rotation and translation given by the positional encoding in the same dimensions of the value vector causes indeterminacy in their independent identification, hindering training scalability. To address this, we propose Decoupled Pose Positional Encoding (DPPE), a novel camera-based positional encoding that explicitly decouples rotation and translation. Extensive evaluations on NVS tasks demonstrate that DPPE enables stable long-term training even in scaled-up training setup. Furthermore, it exhibits superior generalization performance in extrapolation settings, such as handling an increased number of viewpoints and zoom-in scenarios.
### Title:
          SAMBA: A Scatter-Guided Masked Bidirectional Mamba Foundation Model for SAR Target Recognition
 - **Authors:** Ke Wang, Xiaoyi Pan, Zhaoyu Gu, Xiaofeng Ai, Zhiming Xu, Feng Zhao, Shunping Xiao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Synthetic aperture radar automatic target recognition (SAR ATR) is critical for Earth observation and defense, but its practical deployment is constrained by scarce annotated training data. Self-supervised pre-training alleviates this label bottleneck, yet prevailing Transformer architectures incur prohibitive quadratic computational complexity, and conventional universal masking neglects the unique electromagnetic scattering properties intrinsic to SAR imagery. To address these limitations, we propose SAMBA (Scattering-Guided Bidirectional Mamba), an efficient self-supervised pre-training foundation model for SAR target interpretation. Our framework features three core innovations: (i) a linear-complexity Mamba encoder with a mid-sequence class token to mitigate computational bottlenecks; (ii) a three-level hierarchical Scattering-Guided Masked Autoencoder (SG-MAE) masking strategy guided by SAR physical priors, aligning the pretext task with SAR's intrinsic imaging mechanism; (iii) a lightweight SpatialMix feature interaction module to enhance cross-region feature fusion. We also design a two-stage cross-domain pre-training pipeline to optimize the overall pre-training process. Extensive evaluations demonstrate that SAMBA consistently delivers superior performance across all pre-training configurations, with substantially fewer parameters than both CNN and Transformer baselines. Compared with the default masking strategy in standard MAE, the proposed SG-MAE strategy further boosts the model's few-shot transfer capability. Benchmarking on seven downstream datasets covering classification and detection tasks shows SAMBA achieves state-of-the-art (SOTA) performance on most metrics, fully validating its robust generalizability across diverse SAR interpretation tasks. Source code and pre-trained weights are publicly available at this https URL.
### Title:
          REDI: Corpus Aware Patch Ranking for DINOv3 Token Reduction
 - **Authors:** Chanjong Im, Sebastian Diem, Thomas Mandl
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Most token reduction methods for Vision Transformers seek favorable tradeoffs between accuracy and efficiency by pruning, merging, or pooling patch tokens. REDI (Relevance for DINOv3 Token Reduction) studies this question through a controlled supervised reference: how should a fixed token budget be allocated across patches for image classification? REDI quantizes final block DINOv3 patch representations into a visual vocabulary and derives class conditioned corpus scores using supervised TF-IDF over visual words. For each validation image, the ground truth class selects a row of the TF-IDF table, and four transformed views produce a TF-IDF map aligned to a reference center crop. A separate dense pass on the same crop provides an attention map. After independent min max normalization, their elementwise product defines the REDI score. A fixed keep, merge, and compress operator then uses score rank to assign patch roles and score magnitude to weight merging and compression. With precomputed REDI scores, a frozen DINOv3 ViT-B/16 backbone, and the same linear classifier used for dense evaluation, the operator reduces the sequence length from 201 to 107 tokens, a 46.8% sequence reduction. The REDI variant based on incoming attention mass achieves 84.706% Top-1 accuracy on ImageNet-1K, compared with 83.514% for the dense baseline, 82.634% for incoming attention mass alone, and 81.796% for supervised TF-IDF alone. The same corpus term also improves reduced classification for three alternative attention formulations relative to their attention only counterparts. Together, these controlled comparisons indicate that class specific corpus statistics and image specific attention provide complementary signals for patch ranking in this setting.
### Title:
          Intrinsically Stable Spiking Neural Networks: Overcoming the Performance Barrier in the Absence of Batch Normalization
 - **Authors:** Ruichen Ma, Xiaoyang Zhang, Jian Bai, Guanchao Qiao, Liwei Meng, Ning Ning, Yang Liu, Shaogang Hu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The performance of deep spiking neural networks (SNNs) often relies on batch normalization (BN). However, the advanced dynamic BN variants used in state-of-the-art models introduce runtime multiplications, which weaken the hardware-efficiency motivation of SNNs. To address this tension, we identify catastrophic firing-rate decay as a primary cause of severe performance degradation in normalization-free SNNs. Guided by this insight, this work proposes the Intrinsically Stable SNN (IS-SNN) architecture, which removes activation-normalization layers by enforcing signal homeostasis through topology-aware weight standardization and modified residual connections. By folding the standardization operations into static weights offline, IS-SNN removes the runtime statistics tracking and multiplications introduced by activation normalization, restoring an accumulation-oriented inference datapath. Comprehensive experiments show that IS-SNN achieves performance competitive with or superior to computationally expensive dynamic BN techniques across VGG, ResNet, and Transformer-based models. Notably, it achieves a competitive accuracy of 68.05\% on ImageNet and overcomes the severe depth limitations of prior BN-free attempts. Together with a 96.4\% reduction in FPGA lookup table resource consumption for neuron implementations, these results support IS-SNN as a practical framework for building accurate and hardware-friendly deep neuromorphic systems.
### Title:
          Nonlinearity-Aware LoRA: Structured Gate Adaptation under Low-Rank Constraints
 - **Authors:** Shuai Yuan, Sudong Cai, Bingzhi Chen, Shuyuan Zheng, Chuan Xiao, Makoto Onizuka, Rui Mao
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Low-rank adaptation (LoRA) is commonly viewed as an update-space approximation to full fine-tuning, yet this view is incomplete for self-gated Transformer feed-forward networks. In gated FFNs, a low-rank residual can change not only projected features but also the nonlinear selection weights that determine which channels contribute to the output. We formalize this effect as selection misalignment and connect it to the local effective homogeneity of self-gated activations. This motivates a nonlinearity-aware principle for parameter-efficient fine-tuning: low-rank updates should allocate capacity to gate channels whose nonlinear states remain responsive and should shape the temporal evolution of selection. We propose NA-LoRA, a training-only method with two lightweight mechanisms: a derivative-based temporal-importance mask for gate-related LoRA updates and an activation-specific step-scaling rule when a meaningful coarse effective-homogeneity partition is available. NA-LoRA adds no auxiliary loss and incurs no inference-time overhead. Experiments on language-model fine-tuning and vision-language transfer benchmarks show that NA-LoRA consistently improves over vanilla LoRA and is competitive with or better than strong PEFT variants.
### Title:
          Bridging the Gap Between Latent and Explicit Reasoning with Looped Transformers
 - **Authors:** Ying Fan, Anej Svete, Kangwook Lee
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Language models typically reason via explicit chain-of-thought (CoT), generating intermediate steps token-by-token. Latent CoT offers an alternative: it performs multi-step reasoning in the model's hidden states, replacing decoded tokens with continuous representations for greater efficiency. However, existing latent CoT methods underperform explicit CoT beyond 1B parameters, and the gap widens with scale. Looped, or recurrent-depth, Transformers, which reuse their weights to increase computation depth without adding parameters, are a natural fit for latent reasoning. We therefore ask whether looped Transformers can bridge this gap. We answer affirmatively with a simple recipe: a looped padded Transformer that processes K latent blocks in parallel for R iterations, with a cross-entropy loss on each latent position's gold CoT-step token, similar to explicit CoT supervision. We instantiate it as LOTUS (Looped Transformers with parallel supervision on latents). LOTUS is, to our knowledge, the first latent-CoT method to bridge the gap to explicit CoT at the 3B scale, while cutting thought-phase latency by 2.5x-6.9x from compact math expressions to natural language. Projecting LOTUS's post-loop latents through the base LM head recovers the gold reasoning steps and even surfaces alternative valid intermediate steps, evidence that its latent space is interpretable and CoT-aligned. Ablations confirm that both the looped backbone and the parallel supervision on gold CoT tokens are essential.
### Title:
          SpikeLogBERT: Energy-Efficient Log Parsing Using Spiking Transformer Networks
 - **Authors:** Thuan Bui, Duong Do, Tung Vu, Duc-Tho Mai, Cong-Kha Pham
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Log parsing is a fundamental step in automated log analysis, transforming raw system logs into structured event templates for downstream tasks such as anomaly detection and system monitoring. Existing log parsing methods range from rule-based and clustering-based approaches to neural models that learn semantic representations from log messages. However, neural approaches typically rely on dense matrix multiplications, which can result in high computational cost and energy consumption. This paper presents SpikeLogBERT, a spiking neural network framework for energy-efficient log parsing. The proposed model integrates a spiking transformer architecture with knowledge distillation from a BERT teacher model, enabling spike-driven computation while preserving semantic representation capability. By leveraging sparse spike activations and event-driven processing, the number of active operations during inference can be significantly reduced. As an initial benchmark study, experiments on the HDFS dataset demonstrate that SpikeLogBERT outperforms ANN-based neural log parsing models with a parsing accuracy of 0.99997, while reducing estimated theoretical energy consumption by up to 62.6% under standard 45nm CMOS assumptions.
### Title:
          CHERRY: Compressed Hierarchical Experts with Recurrent Representational Yield
 - **Authors:** Dohyeon Kwon, Youngjin Park
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study three complementary techniques for training compute-efficient language models. (1) Selective supervision and per-token efficiency. Selective Ground Truth Token Training (SGT) concentrates supervision on the ~15% of output tokens that carry semantic payload. Through positive gradient coupling in position-shared transformer weights -- a token-level instance of auxiliary-task transfer -- the remaining 85% of unsupervised tokens still improve substantially, giving a 4.5x per-supervised-token efficiency (at the step-100 eval optimum, ~67% of the full-sequence loss reduction is recovered from 15% of the supervision). We prove that this improvement on unsupervised tokens is guaranteed whenever the gradient coupling coefficient gamma-bar = 0.72 is positive (Theorem 1), and show the effect is a property of natural-language structure: it collapses on shuffled text. (2) Depth compression with recurrent recovery. A 48-layer, 1B-parameter transformer is compressed to 6 layers (227M) by averaging adjacent layers and restored through learned recurrent unrolling. With 34 effective recurrent layers it reaches a held-out loss of 2.934, within measurement noise of a 566M dense model at 2.926 -- a 2.5x reduction in parameters. (3) Fusion of compressed experts. Assembling several compressed models as a Mixture of Efficient Experts (MoEE) with multi-token prediction improves over each single expert at comparable active parameters: a 2-expert MoEE reaches loss 2.789 versus 2.926 for the best single compressed model. We validate these techniques on CHERRY-1.8B, a Korean foundation model whose every trainable parameter derives from our own training runs. We are explicit throughout about the scope of the evidence (one model family, Korean data, loss-based metrics) and about which claims are established versus prospective.
### Title:
          MuSViT: A Foundation Vision Model for Sheet Music Representation
 - **Authors:** Carlos Penarrubia, Antonio Rios-Vila, Eliseo Fuentes-Martinez, Juan C. Martinez-Sevilla, Francisco J. Castellanos, María Alfaro-Contreras, Jorge Calvo-Zaragoza
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Foundation models have transformed vision and language processing by providing rich, reusable representations that transfer across diverse tasks. Sheet music, as a visual encoding of musical language, lacks such a strong domain-specific backbone. We introduce MuSViT (Music Score Vision Transformer): the first foundation vision model for sheet music representation -- a ViT encoder pre-trained via Masked Autoencoders on 9.7 million pages from the IMSLP. To handle the complexity of real-world scores, we adopt a two-stage curriculum: a synthetic warm-up on typeset scores followed by large-scale training on the full IMSLP corpus. We evaluate MuSViT on four downstream tasks -- full-page and staff-level music score recognition, music symbol detection, and score difficulty classification -- under two scenarios: linear probing (frozen encoder) and fine-tuning. Under linear probing, MuSViT consistently outperforms modern vision encoders, revealing that general-purpose representations, regardless of scale, fall systematically short on the structured symbolic properties of musical notation. Under fine-tuning, MuSViT generally improves upon task-specific state-of-the-art methods. An additional embedding-transcription consistency analysis reveals that MuSViT encodes symbolic musical structure directly in its representation space -- unlike other encoders, whose embeddings do not correlate with music notation content. These results establish MuSViT as a foundation backbone for sheet music understanding.
### Title:
          Generative Lane Topology Reasoning via Autoregressive Model with Geometry Prior
 - **Authors:** Jiahui Fu, Zehao Huang, Han Li, Naiyan Wang, Si Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Lane topology reasoning aims to construct a lane graph from onboard sensor observations. Existing methods follow a detection and association paradigm that treats each lane instance independently, leading to geometric inconsistency at connected endpoints and incomplete graphs due to visual occlusions. To address these issues, we propose TopoGPT, a generative framework that learns the geometry prior from typical lane graph structures through autoregressive sequence modeling. Specifically, we construct a large-scale map dataset comprising 3.3M scenes. For each lane graph, a lane tokenizer serializes it into discrete tokens, while a scene context encoder converts it into a rasterized image and extracts global features as scene tokens. We pre-train an autoregressive lane sequence transformer via scene-conditioned next-token prediction, endowing the model with the geometry prior over lane graph structures. Building upon this prior, a perception adapter aligns BEV features from multi-view images with the pre-trained scene condition, transferring the learned geometry prior to sensor-based lane graph prediction. On the OpenLane-V2 benchmark, TopoGPT outperforms existing methods by an average of +6.4 on lane-level and +11.6 on point-level metrics, and produces geometrically consistent and structurally complete lane graphs.
### Title:
          An Agentic AI Framework to Accelerate Scientific Discovery in Plant Phenotyping
 - **Authors:** Renan Souza, Daniel Rosendo, Kelsey Carter, John Lagergren, Frédéric Suter, Shelaine L. Curd, Gerald A. Tuskan, Rafael Ferreira da Silva, David Weston
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-throughput plant phenotyping now generates image derived datasets far faster than scientists can analyze them. At Oak Ridge National Laboratory's Advanced Plant Phenotyping Laboratory (APPL), automated stations image hundreds of plants daily across multiple remote sensing modalities; yet, trait extraction and interpretation remain manual, expert-bound, and strictly post-hoc, making analysis, not acquisition, the binding constraint on discovery. We present an end-to-end agentic AI framework that turns the facility from a data factory into an interactive autonomous, discovery platform, where scientists partner with AI agents to accelerate time to insight. A conversational Co-Scientist Agent translates a scientist's natural-language question into a structured analysis plan, and a headless Compute Agent dispatches Vision Transformer segmentation and trait extraction on the Frontier exascale supercomputer. The two agents run in separate security and resource domains and communicate over a secure, token-authenticated streaming channel, a design that accounts for the federation, data-movement, and provenance realities cloud-native agentic frameworks ignore, ensuring end-to-end provenance is captured for every interaction. The framework turns a days- to weeks-long analysis process into an interactive loop where agents reason over results, recommend next analyses, and respond to follow-up questions in seconds.
### Title:
          Explicit Fuzzy Logic in the Feed-Forward Layer: Self-Forgetting Quantifiers Discover Legible Grammatical-Licensing Detectors
 - **Authors:** Mark Oskin
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A transformer's feed-forward (FFN) sublayer materializes the distinctions attention gathers, yet gives no account of what it computes. In a parameter-neutral replacement, each hidden unit is an explicit fuzzy set operation on sigmoid-bounded [0,1] memberships: intersection A*B and set-difference A*(1-B), the latter a bounded positive negation ("A but not B") that gated/bilinear units lack -- a negation-capable FFN (NC-FFN). On N-bit parity they are the most parameter-efficient reasoning basis at shallow depth; at scale (125M, OpenWebText) NC-FFN ties the GELU baseline's perplexity, every unit carrying explicit logical form. Two limits share one cause: two-operand logic localizes to layer 0 and erodes under training, and the one robust grammatical deficit concentrates in licensing and quantifiers, beyond within-token operators. We resolve both with a small block of sequence quantifiers: a soft existential and a soft proportion, each with a per-unit learned forgetting rate from a sticky init. This recovers the deficit at epoch one (halving the wider epoch-two gap), modestly leads on LAMBADA, and makes the FFN legible: the structure now holds and migrates into depth; the decay un-learns its stickiness (median half-life ~1.5 tokens; zero latch units); and at the semantic layers the units read, without dictionary learning, as grammatical licensing detectors: each fires on a licensor (a comparative, a passive participle, a negative-polarity item) and carries its memory forward to predict the licensed word (than, by, nor). This legibility is localized and free only up to a partition (a fully Boolean FFN diverges in training), but the result is a parameter-neutral, language-model-quality transformer with a readable, interpretable-by-construction grammatical mechanism -- an account not just of what a feed-forward layer represents but how it licenses.
### Title:
          Low-dimensional topology of deep neural networks
 - **Authors:** Junyu Ren, Lek-Heng Lim
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Geometric Topology (math.GT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study layered models, including feedforward networks, ResNets, and transformers, by limiting each layer to a width of $d = 3$, i.e., $\mathbb{R}^3$ as representation space. This allows us to track how a neural network changes low-dimensional topological invariants through its layers. Just about any topological structure may be simplified or even trivialized by simply increasing dimension; e.g., any knot is equivalent to an unknot in $\mathbb{R}^4$. By restricting to $\mathbb{R}^3$, we not only isolate the effects of activation and depth from that of width, we work in a space that lends itself to easy visualization. We focus on linking number here, deferring other invariants like link groups, Milnor's $\bar{\mu}$-invariants, knot types, ambient cobordisms, to a sequel. We provide full proofs and empirical experiments to justify the following insights: When measured by their power to effect changes in linking numbers, the layer-skipping feature in ResNets is as powerful as the attention mechanism in transformers; both ResNets and transformers are strictly more powerful than feedforward neural networks with monotonic activations, which are in turn more powerful than invertible and flow-based models; but replacing monotonic activation with a nonmonotonic one elevates a feedforward network into the same expressivity class as ResNets and transformers. These results suggest that low-dimensional topology can be a useful tool to guide designs of AI architectures. We also generalize our results from $d = 3$ to arbitrary $d > 3$.
### Title:
          Attend, Transform, or Silence: Operator-Level Visual Skipping for Efficient Multimodal LLM Inference
 - **Authors:** Zhaoyang Luo, Runmin Dong, Miao Yang, Fan Wei, Yushan Lai, Bin Luo, Haohuan Fu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal large language models (MLLMs) increasingly process long visual-token sequences, increasing the overall inference computation. Existing acceleration methods usually remove visual tokens or skip visual-token updates in entire layers, but these coarse strategies may discard fine-grained evidence or suppress useful operators together with redundant ones. In this paper, we study visual-token computation from an answer-observable perspective and find that late visual-token updates can remain large while having little effect on answer-token representations. Motivated by this answer-silent redundancy, we decompose each Transformer layer into attention and FFN operators and show that useful visual computation is often operator-dominant and layer-dependent. We propose an operator-level visual-token skipping framework that preserves the full visual-token sequence while selectively bypassing redundant attention, FFN, or both. Experiments across three MLLM architectures and 10 VQA benchmarks show that our method achieves strong efficiency-accuracy trade-offs, reducing \textbf{33.7\%} TFLOPs on Qwen3-VL while retaining \textbf{99.5\%} of the vanilla model performance.
### Title:
          FlexViT: A Flexible FPGA-based Accelerator for Edge Vision Transformers
 - **Authors:** Hubert Dymarkowski, Xingjian Fu, Rappy Saha, Jude Haris, José Cano
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Computer Vision and Pattern Recognition (cs.CV); Distributed, Parallel, and Cluster Computing (cs.DC); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deploying Vision Transformer (ViT) models on edge platforms remains challenging due to their high computational demands and the architectural heterogeneity of modern hybrid ViT models, which incorporate both fully connected and convolutional layers. This heterogeneity leads to significant variation in tensor shapes, requiring flexible and efficient FPGA-based acceleration. In this paper, we present FlexViT, a reconfigurable FPGA accelerator for efficient ViT inference on resource-constrained edge devices. Built on the SECDA-TFLite framework, FlexViT employs a hardware-software co-design approach that maps both fully connected and convolutional layers onto a unified high-throughput INT8 GEMM engine using a runtime im2col transformation. To efficiently support diverse layer configurations, we propose a dual-mode dataflow that dynamically switches between input and weight reuse by reconfiguring the compute array at runtime. We further introduce a depth-first tiling strategy that completes accumulation in a single pass, eliminating off-chip partial-sum transfers and reducing memory bandwidth requirements. We implement FlexViT on a PYNQ-Z2 FPGA and evaluate it across a representative set of ViT models. FlexViT achieves up to 2.74x speedup on accelerator-executed layers, translating into up to 1.40x end-to-end speedup compared to CPU-only execution. The code is available at: this https URL
### Title:
          LUNA: Learning Universal 3D Human Animation Beyond Skinning
 - **Authors:** Peng Li, Rawal Khirodkar, Junxuan Li, Yuan Dong, Chen Cao, Yuan Liu, Wenhan Luo, Yike Guo, Shunsuke Saito
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Creating photorealistic, animatable 3D human avatars from monocular images still largely depends on Linear Blend Skinning (LBS) and parametric body models, which constrain expressivity and often introduce artifacts due to imperfect fitting. We propose LUNA, an LBS-free universal neural animation model that directly maps multiple 2D controls like images, keypoints, sketches, and unseen characters into 3D Gaussian deformations, bypassing explicit body fitting. At its core, a transformer-based motion regressor disentangles global rigid motion from fine-grained local dynamics to capture both coherent movement and subtle non-rigid effects. To resolve the inherent ambiguity of 2D-to-3D lifting while scaling beyond fitted datasets, we introduce hybrid supervision that distills soft structural priors from an LBS teacher and a loss that supports training on both limited fitted data and large in-the-wild unlabeled videos. Extensive experiments show LUNA achieves competitive visual fidelity compared to LBS-based approaches, while delivering realistic human motion and zero-shot cross-identity generalization across diverse driving modalities. To the best of our knowledge, LUNA is the first end-to-end 3D animatable model that supports implicit 2D driving.
### Title:
          Radial Suppression Accelerates Algorithmic Generalization: A Geometric Analysis of Delayed Generalization
 - **Authors:** Srijan Tiwari, Aditya Chauhan, Manjot Singh
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Why do neural networks memorize algorithmic training data long before they generalize? We present a geometric case study demonstrating that, on tasks where generalization requires discovering structured low-dimensional circuits, the memorization-generalization delay is driven by radial inflation of hidden representations under cross-entropy optimization. We formalize a radial-angular decomposition of activation-space dynamics and derive three testable propositions: (i) that penalizing radial inflation induces anisotropic, data-dependent weight regularization; (ii) that it suppresses radial gradient energy below the isotropic random baseline, forcing predominantly angular updates; and (iii) that it biases convergence toward flatter minima. To empirically validate these propositions, we study a single-hyperparameter norm penalty that softly constrains activations to a sqrt(d)-radius hypersphere. On modular arithmetic, this penalty accelerates grokking up to 6x across MLPs and Transformers, and halves training steps for a 10M-parameter nanoGPT on 3-digit addition.
### Title:
          SpheRoPE: Zero-Shot Optimization-Free 360 Panorama Generation with Spherical RoPE
 - **Authors:** Or Hirschorn, Aaron Olender, Eli Alshan, Ianir Ideses, Lior Fritz, Sagie Benaim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a zero-shot, training-free and optimization-free framework for generating 360 panoramic images and videos by directly injecting spherical priors into pre-trained diffusion transformers. Existing methods either rely on costly fine-tuning on scarce panoramic data that limits generalization, or leverage multi-step optimization that incurs prohibitive inference latency. We observe that contemporary generative models natively exhibit some panoramic priors from large-scale training. However, these emergent capabilities are insufficient, as the models fundamentally fail to satisfy the rigorous topological constraints imposed by equirectangular projection (ERP). We introduce a zero-shot and optimization-free approach that resolves these constraints at inference time. Spherical RoPE replaces standard rotary position embeddings: low-frequency channels are re-parameterized as 3D Cartesian coordinates to natively encode the spherical manifold, while high-frequency channels are harmonically quantized to enforce exact periodicity. Coupled with complementary Semantic Distortion classifier-free guidance (CFG) that explicitly steers geometry, we avoid retraining and inherit the full creative breadth of state-of-the-art models. Our approach generalizes across diverse backbones and 360 generation modalities. We demonstrate this across text-to-panorama using Flux.1, Flux.2, and LTX-Video backbones, achieving competitive performance against baselines, all while remaining training-free. Project page: this https URL
### Title:
          PointSplat: Compact Gaussian Splatting via Human-Centric Prediction
 - **Authors:** Yujie Guo, Yudong Jin, Lingteng Qiu, Zehong Shen, Zhen Xu, Jing Zhang, Xianchao Shen, Hujun Bao, Sida Peng, Xiaowei Zhou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Producing 3D human representations from input views on the fly is essential for immersive live streaming systems, where representation compactness is as critical as high fidelity given limited computational power and transmission bandwidth. Although recent feed-forward reconstruction methods achieve impressive quality through the view-centric prediction of 3D representations, they repeatedly encode the same subject content across multiple views, leading to significant inter-view redundancy. Our key insight is to perform predictions directly in 3D space, enabling the network to learn and produce a highly compact representation. To this end, we propose PointSplat, a novel human-centric approach that directly infers Gaussian primitives from an input point set. The proposed method first estimates a coarse geometric proxy and performs ray casting to prune redundant points and establish explicit 2D--3D correspondences. Subsequently, it employs a Point-Image Transformer to fuse appearance and geometry features, predicting Gaussian attributes in a single forward pass. This design restricts predictions to foreground regions of interest, substantially reducing the total number of Gaussians while improving novel-view rendering quality. Extensive experiments demonstrate that PointSplat achieves higher efficiency and quality while exhibiting strong robustness to variations in view count and image resolution across multiple datasets.
## Keyword: autonomous driving
### Title:
          Off the Rails: Hijacking the Scoring Head in Generative End-to-End Driving Planners with Safety-Violating Adversarial Perturbations
 - **Authors:** Halima Bouzidi, Mboutidem Ekemini Mkpong, Haoyu Liu, Mohammad Abdullah Al Faruque
 - **Subjects:** Subjects:
Robotics (cs.RO); Cryptography and Security (cs.CR); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative models have recently seen rapid adoption in End-to-End (E2E) autonomous driving (AD), with diffusion-based denoising and vocabulary-based retrieval becoming the dominant trajectory-decoding paradigms. Despite their architectural diversity, current generative AD planners share a common inference pattern: a fixed set of candidate trajectories (anchors, vocabulary entries, or proposal queries) is scored by one or more learned heads conditioned on the Bird's-Eye-View (BEV) features, and the highest-scored candidate is returned as the final trajectory. Under this design, the scoring head is the only barrier between perception and the motion command, and its decision margins between competing candidates are often small. We introduce \textsc{Derail}, an adversarial framework that exploits this scoring-head attack surface. Evaluated on various generative planners, \textsc{Derail} flips the trajectory selection from a safe to an unsafe candidate, with score drops of $39$--$80\%$ and collision rates of up to $50\%$, consistently outperforming generic loss-maximization and feature-divergence attacks. Our analysis suggests that safety-violating objectives govern attack effectiveness against generative AD planners, and that the scoring-head inference pattern itself is a recurring attack surface worth explicit defensive consideration.
### Title:
          A Practical Implementation of Day-3 Cooperative Intersection with Automated Connected Mini-Cars
 - **Authors:** Lorenzo Farina, Vittorio Todisco, Federico Gavioli, Salvatore Iandolo, Francesco Moretti, Giuseppe Perrone, Matteo Piccoli, Francesco Raviglione, Marco Rapelli, Antonio Solida, Claudio Casetti, Paolo Burgio, Carlo Augusto Grazia, Alessandro Bazzi
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cooperative driving enabled by connected and automated vehicles is expected to improve traffic efficiency and safety, particularly at intersections where traditional control mechanisms such as traffic lights introduce delays and unnecessary stops. Although cooperative intersection management algorithms have been widely studied, experimental demonstrations remain limited. This paper presents a real-time demonstration of cooperative intersection management using connected autonomous mini-cars. The testbed consists of multiple 1:10 scale vehicles equipped with autonomous driving capabilities and wireless communication modules that interact with a centralized controller responsible for scheduling their crossing of the intersection. Vehicles approaching the intersection exchange messages with the controller to set the appropriate mobility profile to traverse the intersection without stopping. The demonstration integrates autonomous driving, wireless communication, and cooperative control in a single experimental platform, providing a practical environment for validating cooperative intersection management concepts for future intelligent transportation systems.
### Title:
          Knowledge-Driven Dimension Estimation from a Single Image -3D Asset Generation Technology for Digital Twin Construction
 - **Authors:** Hidenori Sakaniwa, Akihito Akai, Akihiko Hyodo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In the verification of in-vehicle cameras, simulation technology using virtual spaces has advanced, enabling pre-evaluation of false detections and missed detections in various scenarios. However, discrepancies in the scale of the object being verified between the virtual and real environments can lead to a decrease in camera recognition performance. For traffic signs installed at high altitudes, distance measurement using LiDAR or stereo cameras is difficult, requiring size estimation from monocular images. This paper proposes a method for estimating the scale of an object by decomposing it into multiple structural elements and integrating external knowledge regarding design rules, geometric relationships, and conventional dimensions. Specifically, this method detects each component from a monocular image and estimates the size of each component by considering its structural relationships and dimensional consistency with surrounding elements. Furthermore, it generates a 3D asset of the object by reconstructing the estimated components. This method makes it possible to place 3D assets with a scale approximating the real environment within a digital twin space and is expected to contribute to improving the verification accuracy of in-vehicle cameras for autonomous driving in virtual environments.
### Title:
          Horizon3D: Sparse Radar-Camera Fusion for Long-Range 3D Perception in Autonomous Driving
 - **Authors:** Geonho Bang, Geunju Baek, Dongyoung Lee, Wonjun Jeong, Jun Won Choi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long-range 3D object detection is critical for safe autonomous driving at highway speeds, yet existing radar-camera fusion methods remain limited at extended ranges. BEV-based methods capture scene-level context but incur rapidly growing computation and often lose fine-grained object detail, while query-based methods are efficient but provide limited scene-level context. Temporal fusion further requires both multi-frame accumulation for sparse distant observations and object-level motion modeling for fast-moving objects. We propose Horizon3D, a sparse radar-camera fusion framework for long-range 3D object detection that combines Gaussian primitives with sparse BEV features. Horizon3D initializes Gaussian primitives at radar- and camera-estimated object keypoints using Keypoint-Guided Gaussian Initialization, refines them through Object-Centric Sparse Fusion, and splats them onto the BEV plane to fuse object-level detail with sparse radar BEV context. It further introduces Dual-Path Temporal Fusion, which aggregates temporal cues through a BEV path for scene-level accumulation and a Gaussian path for object-level motion propagation. Experiments on TruckScenes show that Horizon3D achieves state-of-the-art radar-camera 3D detection performance. On the validation set, it outperforms the previous best method by +3.0 NDS and +1.6 mAP while maintaining competitive inference speed.
### Title:
          InfiniVerse: Occupancy Guided Unbounded Scene Generation for Autonomous Driving
 - **Authors:** Xiaoyu Ye, Leheng Li, Xinyu Ji, Yingjie Cai, Hongda He, Xu Yan, Guanyi Zhao, Ying-Cong Chen, Bingbing Liu, Shuguang Cui, Zhen Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generating realistic, controllable, and temporally coherent urban environments is a critical yet unresolved challenge in the autonomous driving community. In this paper, we introduce InfiniVerse, a unified pipeline for long-range, 2D-3D-aligned, and controllable synthesis of dynamic urban scenes from a single frame. In practice, our approach first reconstructs a 3D occupancy representation from the input multi-view frame. This representation serves as a foundation for autoregressive scene extension along arbitrary trajectories. Subsequently, a video diffusion model translates the coarse occupancy grid into realistic, spatiotemporally consistent video sequences. Moreover, we propose a hierarchical sketch-and-refine paradigm, in which the generated videos are re-projected as image-conditioned feedback to enhance the 3D occupancy representation, establishing cross-modal alignment and mutual enhancement between the visual and spatial domains. Extensive evaluations on the Waymo Open Dataset and nuScenes demonstrate that InfiniVerse achieves state-of-the-art performance, with a FID of 6.4 and FVD of 67.97, significantly outperforming existing benchmarks in both duration and stability.
### Title:
          Scenario Generation for Testing of Autonomous Driving Systems Using Real-World Failure Records
 - **Authors:** Anjali Parashar, Chuchu Fan
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 To ensure safe on-road behavior, pre-deployment testing and failure discovery of Autonomous Driving Systems (ADS) is crucial. Present day simulation based testing methods focus largely on mathematical models for efficient search of optimal scenarios, assuming a fixed scenario representation. On the other hand, real-world testing involves substantial manual effort to design scenario templates for testing. These templates represent distinct failure scenarios consisting of pre-deployment vehicle movements, map types, etc. Historical failure records for ADS are a reliable source of real-world failure conditions, which can be used for scenario generation. In this work, we propose a scenario generation pipeline using categorical and contextual information available from historical records in natural language format. Our approach consists of modular LLM based synthetic scenario generation, compatible with the testing constraints of a given system. We successfully apply our method to generate a diverse set of scenarios for testing autonomous navigation on Metadrive simulator using the NHTSA ADS crash records. Our approach results in accurate and diverse scenario generation with a combination of 4 road types, 3 non ego vehicle movement types, including on road anomalies in the form of working zones. Generated scenarios align with the provided testing conditions, and reveals interesting failures of the system within a limited testing budget of 20 scenarios. Code is available at this https URL.
### Title:
          Reasoning-aware Speculative Decoding for Efficient Vision-Language-Action Models in Autonomous Driving
 - **Authors:** Anh Dung Dinh, Simon Khan, Flora Salim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern Vision-Language-Action (VLA) planners for autonomous driving emit a chain-of-causation (CoC) reasoning step \emph{before} producing a trajectory. The reasoning is autoregressive and dominates inference latency, while the trajectory head is parallel and cheap. Latency is an operational constraint in autonomous driving, so accelerating the reasoning step is the central problem we address. We observe that CoC reasoning has two qualitatively different needs: most tokens continue routine setup that follows naturally from the ego-trajectory history, and a small fraction encode commitments that require fresh visual evidence about an unexpected situation. We split this reasoning into two specialized paths: a \emph{routine reasoner} that handles the predictable continuation by attending to trajectory history, and a \emph{deliberative reasoner} (the unmodified VLA target) that handles novel cases by attending to current visual evidence, using the speculative decoding framework as the architectural template for how the two paths cooperate. Unlike standard speculative decoding, our routine reasoner is not a smaller replica of the target; the two reasoners are deliberately specialized to read different parts of the prompt. We propose two techniques to realize this. First, we introduce \textbf{FlatRoPE}, a 1D rotary positional embedding in the draft that breaks the rotational symmetry of the target's 3D M-RoPE, redirecting attention away from visual tokens and onto trajectory-history tokens. Second, we introduce \textbf{Action-aware RL (AARL)}, a post-training stage that uses an action-quality reward together with a static-reference KL anchor. Together, our two-reasoner system reduces the reasoning-step running time by approximately $4\times$ relative to the original Alpamayo planner.
### Title:
          HSDF-Lane: Height-Aligned Signed Distance Field with Semantic Lane Prior for 3D Lane Detection
 - **Authors:** Jiyong Boo, Byeongin Joung, Hyemin Yang, Kuk-Jin Yoon
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular 3D lane detection plays a critical role in autonomous driving, yet recovering reliable 3D geometry from a single image remains challenging due to inherent depth ambiguity. Prior methods project image features into Bird's-Eye-View (BEV) space under a flat-ground assumption, causing geometric distortion on real-world roads. Recent methods instead predict explicit height maps to capture non-planar surfaces, but still rely on sparse anchor-based regression and exploit the recovered geometry merely for spatial transformation rather than semantic understanding. To overcome these limitations, we propose HSDF-Lane, which implicitly models the road surface as a Height-aligned Signed Distance Field (HSDF) over a densely sampled 3D feature volume. Through differentiable rendering, the HSDF jointly produces an accurate height map and surface-aligned features. We further introduce Lane-aware Semantic Positional Encoding (LSPE), which injects a lane-existence prior derived from the surface-aligned features into the transformer queries, coupling geometric structure with semantic guidance. Extensive experiments on the OpenLane benchmark show that HSDF-Lane achieves state-of-the-art performance in both 3D lane detection and height map estimation.
### Title:
          GaussianMap: Learning Gaussian Representation for Multi-Sensor Online HD Map Construction
 - **Authors:** Hongyu Lyu, Julie Stephany Berrio Perez, Mao Shan, Stewart Worrall
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving systems benefit from high-definition (HD) maps that provide critical information about road infrastructure. The online construction of HD maps offers a scalable approach to generate local vectorized maps from onboard sensor observations. Existing methods commonly adopt bird's-eye-view (BEV) features as the intermediate scene representation, encoding the surrounding space with fixed-resolution dense grids. However, map elements are spatially sparse yet require fine-grained geometric localization, making uniformly allocated BEV representations redundant and less effective for vectorized map prediction. In this work, we propose GaussianMap, an online HD map construction framework that learns an adaptive Gaussian representation of the surrounding scene. This representation consists of a set of Gaussian primitives on the BEV plane, each encoding a flexible local region with geometric properties and a feature vector, allowing the model to allocate representational capacity to map-relevant regions. To generate such a representation from sensor observations, we introduce a feed-forward Gaussian encoder that progressively refines these primitives through Gaussian interaction modeling and multi-sensor feature aggregation. The refined Gaussian representation is then splatted into a BEV feature map and decoded into vectorized map predictions. Extensive experiments on nuScenes and Argoverse 2 datasets demonstrate that GaussianMap achieves state-of-the-art performance in both camera-only and camera-LiDAR fusion settings. Our code will be made publicly available.
### Title:
          Long-term Traffic Simulation via Structured Autoregressive Modeling
 - **Authors:** Lingyu Xiao, Zexin Feng, Xintao Yan
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Interactive traffic simulation is a vital world model for autonomous driving. A central challenge in long-horizon simulation is modeling sustained multi-agent interactions, which is further exacerbated by dynamic token cardinality as agents continuously enter and exit the scene. In this work, we propose that the solution lies in the synergy between the architectural inductive biases and statistical priors of large-scale sequence models, e.g., Large Language Models (LLMs). Our probing experiments reveal that the transferability of attention mechanisms and the distributional consistency between motion tokens and natural language enable small-scale, heavily frozen LLMs to rapidly adapt to traffic modeling. Building on this insight, we introduce RosettaSim, a unified framework that projects scene topology, agent states, and spawning intents into a structured autoregressive stream with variable length, achieving both strong short-term accuracy and stable long-horizon simulation fidelity. Furthermore, evaluating extended rollouts presents yet another hurdle, as one-to-one agent correspondence inevitably fades over time. To address this, we introduce Retrieval-based Traffic Evaluation (RTE), which retrieves semantically similar real-world scenarios as context-aware reference anchors. Experiments on the Waymo Open Sim Agent Challenge (WOSAC) demonstrate that RosettaSim achieves state-of-the-art performance in both short- and long-term simulation. Furthermore, RTE exhibits a stronger correlation with standard metrics ($r=0.83$) than existing approaches ($r=0.74$), indicating improved alignment with long-horizon simulation fidelity.
### Title:
          ForgeDrive: Bidirectional Cross-Conditioning for Unified Visual-Action Generation in Autonomous Driving
 - **Authors:** Xuchang Zhong, He Zheng, Chenxu Zhao, Tianxiong Lv, Hangqi Fan, Bohua Wang, Yushan Liu, Zhihao Liao, Leigang Luo, Congyang Zhao, Yang Cai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World-model-based autonomous driving endows the model with the ability to understand scene evolution. Yet this promise is undermined by the prevailing imagine-then-act paradigm, which allows errors from the more challenging visual generation stage to cascade into action planning. We introduce ForgeDrive, a unified autoregressive diffusion framework with visual-action cross-conditioning that closes this gap through act-then-imagine paradigm. ForgeDrive factorizes the future as a sequence of per-timestep frame-action pairs, intertwining each action with its corresponding visual observation. During training, we decouple the diffusion timesteps of the two modalities and introduce a UniDiffuser-style noise scheduler to get the ability to infer either modality from its counterpart and deepen understanding of relationships between images and actions. At inference, we propose a novel act-then-imagine inference paradigm, and find that at each step, action generation is a capability internalized during training, requiring no clean future frame as a prerequisite at inference time; instead, the generated action can improve the accuracy of future frame generation, which in turn enhances the quality of the next action. Additionally, we augment each step with future ego-status prediction, further sharpening planning ability. Extensive experiments on NAVSIM demonstrate that ForgeDrive not only unifies driving simulation, planning, and visual odometry into a single model, but also outperforms existing strong planners without any post-training strategy.
### Title:
          Failure-Based Testing for Deep Reinforcement Learning Agents
 - **Authors:** Weibin Lin, Jiangtao Meng, Zheng Zheng
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep Reinforcement Learning (DRL) agents have been widely adopted across diverse domains to address challenging decision-making problems, such as autonomous driving and robotic control. Given that many of these applications are safety- and security-critical, rigorous testing of DRL agents is indispensable. Existing testing methods are typically guided by reward signals to detect failures. However, for well-trained agents, whose performance approaches optimal levels in standard operating conditions, reward signals remain generally high, making current methods ineffective at uncovering critical failures. To address these challenges, we propose a novel failure-based method that leverages task-induced failure insights to enhance failure detection capability while reducing the number of tests required. Since DRL agents are inherently designed with human-defined tasks, they provide valuable cues about task difficulty. Intuitively, a DRL agent is more likely to fail when confronted with a more difficult task; therefore, PRT prioritizes these tasks. Building on this foundation, we propose Prior Random Testing, a black-box failure-based testing method that enables targeted prioritization while preserving the diversity of generated test cases. Guided by task-induced failure insights, PRT prioritizes failure-prone regions of the input domain, thereby facilitating efficient failure detection. PRT is evaluated on four widely used benchmarks and compared with different state-of-the-art methods including fuzzing, search-based and generative-based methods. PRT ranks among the top performers in terms of both the cost of finding the first failure and the diversity of test cases. Notably, compared to random testing, PRT achieves better diversity and reduces the testing cost by over 50%.
### Title:
          DrivingDepth: Sparse-Prompted Pixel-wise Scale Correction for Driving Depth Estimation
 - **Authors:** Chi Huang, Wenhao Zhang, Hang Yin, YuAn Wang, Hao Li, Bosheng Wang, Xun Sun, Liang Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dense depth estimation for autonomous driving faces a geometry-scale conflict: depth foundation models deliver pixel-aligned dense visual geometry without reliable metric scale, while projected LiDAR provides metric anchors that are sparse, noisy, and misaligned with image structures. Existing sparse-prompted methods incorporate LiDAR by regenerating depth from scratch, overriding the foundation model's coherent geometry and producing structural artifacts on visually continuous surfaces. Our key insight is that foundation models already capture geometrically coherent relative depth; no additional surface structure learning is required-only a per-pixel scale factor mapping relative geometry to metric coordinates. Based on this, we propose DrivingDepth, which treats sparse LiDAR as geometric prompts that locally calibrate a frozen foundation prior through residual pixel-wise scale correction, preserving dense visual geometry by construction. On nuScenes with 4-frame surround-view input, DrivingDepth achieves an AbsRel of 11.19 and an EdgeCR of 5.741, outperforming MapAnything (11.99/1.914) by simultaneously delivering SOTA metric accuracy and geometric consistency.
### Title:
          Support of Teleoperated Driving with 5G Networks
 - **Authors:** M.Carmen Lucas-Estañ, Baldomero Coll-Perales, Mohammad Irfan Khan, Sergei S. Avedisov, Onur Altintas, Javier Gozalvez, Miguel Sepulcre
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Teleoperated driving (ToD) can support autonomous driving under complex or unexpected traffic scenarios that an autonomous vehicle may not understand or be able to handle. In ToD, autonomous vehicles transmit video feeds and perception data to the remote control center. The operator uses this data to understand the driving environment and remotely control the vehicle that can take over the control once the scenario is resolved. ToD requires reliable and low latency communications between the vehicle and the ToD control center. This study analyzes the feasibility to support ToD with 5G networks. The study demonstrates that the feasibility strongly depends on the bandwidth and the Time Division Duplexing (TDD) frame structure that conditions how the bandwidth is distributed between uplink and downlink transmissions. The study also shows that scaling the number of 5G-supported ToD vehicles requires the vehicles to reduce the video bitrates. The study also shows that traditional centralized 5G network deployments may be challenged by some of the most stringent ToD latency requirements due to the latency introduced by the Internet connection to the ToD control center.
### Title:
          From Failure to Alignment: A Requirements Engineering Framework for Machine Learning Systems
 - **Authors:** Amel Bennaceur, Gopi Krishnan Rajbahadur, Prince Mercy, Bashar Nuseibeh, Faeq Alrimawi
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Organisations designing, developing, and deploying machine learning systems (MLS) need to be able to check that these systems are trustworthy, and communicate this clearly to their stakeholders, be they different categories of users, engineers, or wider society. By focusing on stakeholders, Requirements Engineering is well positioned to drive the design and engineering of MLS that align with the needs of their stakeholders. Yet, we still need a systematic process for modelling and reasoning about requirements for MLS that is driven both by stakeholders' needs and constraints for MLS development. This paper proposes a framework entitled REAL (Requirements Engineering for mAchines that Learn - and Fail) to help develop MLS that align with stakeholders' needs by adopting a requirements engineering approach. This model-based framework is based on three principles. First, weaving together requirements for data, models, and the system as a whole. Second, using failure to drive the exploration of alternative requirements. Third, iterative and traceable refinement of MLS requirements. We demonstrate the proposed framework using an example from autonomous driving and show that REAL supports the development of MLS that better align with stakeholders' requirements. A replication package is available online.
### Title:
          Semantic Occupancy Prediction with Dual Range-Voxel Representation
 - **Authors:** Sitao Chen, Zhuangwei Zhuang, Hui Luo, Lizhao Liu, Qingyao Wu, Mingkui Tan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR-based 3D semantic occupancy prediction, which aims to provide accurate and comprehensive scene representation, is crucial for autonomous driving systems. As point clouds suffer from sparsity and incompleteness, leading to insufficient semantic learning and difficult occupancy perception, existing methods often stack multi-sweep point clouds to obtain dense spatial information. However, such a naive strategy also results in efficiency (e.g., additional computational burden) and robustness (e.g., pose transformation noise) concerns, which hinder their practical applications. In this work, we propose a Dual Range-Voxel Representation (DRVR) that leverages the range-view context and voxel-view geometry of single-sweep point clouds for 3D semantic occupancy prediction, eliminating the concerns associated with the multi-sweeps. Specifically, we use the range-view encoder to extract the compact context of the scene. To fully exploit the spatial information, we design a geometry-aware voxel-view encoder that extracts multi-scale voxel-view features separately and combines them for better geometric occupancy prediction. Moreover, we propose a range-voxel fusion module to cooperate range- and voxel-view features via voxel-to-range and range-to-voxel fusions. Extensive experiments on nuScenes-Occupancy, SemanticKITTI and SemanticPOSS show the superiority of our method. Especially on nuScenes-Occupancy, our single-sweep DRVR achieves 5.4% improvement in mIoU and 2.1x acceleration compared to the multi-sweep method.
### Title:
          Gaussian Belief Propagation for Tracking With Unresolved Measurements
 - **Authors:** Augustin A. Saucan, Florian Meyer, Peter Willett
 - **Subjects:** Subjects:
Information Theory (cs.IT); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unresolved measurements occur in many inference problems where two or more hidden processes may, at times, jointly generate a single measurement. For instance, such phenomena are encountered in multiobject tracking owing to the limited resolution capabilities of practical sensors; or in camera-aided autonomous driving due to shadowing or occlusions. Substantial performance degradation, such as track losses, are incurred when unresolved measurements are not accounted for. In this paper, we address multiobject tracking under a generalized unresolved measurement model, where any subset of objects may generate a single unresolved measurement according to a probabilistic model. Our innovation lies both in modeling and algorithm-design directions. First, we develop a probability distribution for object partitions based on a model of pairwise coupling of objects and subsequently a probability distribution for object-to-measurement association variables. This generic model incorporates sensor resolution capabilities, sensor detection, and sensor noise characteristics for object groups. Second, a generic Loopy Belief Propagation (LBP) method as well as a specialized Gaussian-LBP (GLBP) algorithm are proposed that perform object state inference under the aforementioned model. In contrast to direct marginalization methods, which involve a computational complexity of $O(m^n)$, for $m$ measurements and $n$ objects, the proposed GLBP algorithm achieves a computational complexity on the order of $O(m n 2^{n})$. Numerical results demonstrate the effectiveness of our proposed GLBP, with estimation performance that closely matches that of exact marginalization for only a fraction of the computational resources.
### Title:
          PriorEye: Geospatial Visual Priors for End-to-End Autonomous Driving
 - **Authors:** Kyuhwan Yeon, Benjamin Ramtoula, Daniele De Martini
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Most end-to-end autonomous driving methods rely solely on instantaneous sensor observations, limiting them to reactive behavior without the anticipatory foresight human drivers employ through prior experience. We introduce geospatial visual priors, street-level visual context anchored to the intended driving route, providing visual-spatial foresight independent of real-time sensors. We propose a memory augmentation module featuring a dual-memory architecture and an adaptive memory gate, which can be easily integrated into existing end-to-end approaches. This design pairs a contextual memory for retrieved priors with a persistent fallback memory, and dynamically regulates the influence of memories based on current state compatibility. Evaluated on the NAVSIM-v2 benchmark, our approach consistently improves performance across diverse end-to-end baselines. Furthermore, because these priors are independent of onboard sensors, our method inherently improves robustness against sensor corruption, while the dual-memory design ensures safe fallback when the retrieved priors themselves become unreliable. Our project page is available at this https URL.
### Title:
          Real-Time Source-Free Object Detection
 - **Authors:** Sairam VCR, Varun Gopal, Poornima Jain, Vineeth N Balasubramanian, Muhammad Haris Khan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-world detectors for autonomous driving, surveillance, and robotics must handle domain-shifts under strict latency and memory constraints, yet existing source-free object detection (SFOD) methods rely on heavyweight architectures that prioritize accuracy alone. We show this trade-off is unnecessary: building on YOLOv10, an NMS-free dual-head detector, we achieve state-of-the-art adaptation accuracy while being faster and more compact. We observe that directly applying vanilla mean-teacher self-training to dual-head detectors leads to suboptimal adaptation performance due to two key factors. First, simple pseudo-label generation strategies, such as using a single head or directly combining high-confidence predictions from both heads, yield suboptimal supervision under domain-shift. We propose DHF (Dual-Head Pseudo-Label Fusion) which selectively admits one-to-one (O2O) and one-to-many (O2M) head predictions, preserving precision and recovering missed objects. Second, we observe domain-shift collapses multi-scale feature discriminability. We propose the use of our MARD (Multi-scale Adaptive Representation Diversification) loss which mitigates this by enforcing detection-aware variance and covariance constraints on multi-scale feature maps. Both modules are training-time only, leaving inference unchanged. Across domain-shift benchmarks, our method, RT-SFOD yields 1.4 to 3.5\% mAP gains, 1.3$\times$ higher throughput, with $\sim$2$\times$ fewer parameters than prior state-of-the-art SFOD methods, thus advancing the Pareto frontier of the speed-accuracy-model size trade-off. We report main results with YOLOv10, and demonstrate generalizability with additional YOLO- and DETR-based dual-head detectors. Code is available here: this https URL
### Title:
          SENSE-VAD: Sentient and Semantic Video Anomaly Detection for Autonomous Driving
 - **Authors:** Nghia T. Nguyen, Lokman Bekit, Yasin Yilmaz
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous vehicles (AVs) must navigate not only motion-based hazards but also socially complex situations whose danger is constituted by inter-agent relationships rather than movement statistics alone. A child running away from a guardian, a person being carried by another, or a pursuer chasing a pedestrian across a sidewalk are all anomalous in social context, yet none produces an obvious motion signal that current anomaly detectors are equipped to flag. We introduce SENSE-VAD, the first synthetic video anomaly detection benchmark for autonomous driving explicitly designed around socially complex anomalies. Using the CARLA simulator and Unreal Engine (UE), we generate distinct anomaly scenarios across multiple categories: individual behaviors, group behaviors, person--object interactions, cyclist interactions, vehicle & agent, each annotated with per-frame binary labels. A key design principle is the separation of social anomaly from motion-based or appearance-based anomaly: many scenarios involve motion of objects that appears unremarkable in isolation but is anomalous in relational context. We additionally provide real-world normal and anomalous videos as a sim-to-real transfer probe. We evaluate state-of-the-art video anomaly detection baselines and demonstrate that socially complex anomalies constitute a distinct and currently unsolved challenge. Our dataset, annotations, and generation code are publicly available.
### Title:
          DriveWeaver: Point-Conditioned Video Inpainting for Controllable Vehicle Insertion in Autonomous Driving Simulation
 - **Authors:** Junzhe Jiang, Zipei Ma, Zijie Pan, Li Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A pivotal step in autonomous driving simulation involves inserting foreground vehicles with predefined trajectories into simulated scenes. This process enhances scene diversity and facilitates the creation of various corner cases for testing and improving autonomous driving models. However, existing methods often rely on pre-reconstructed 3D assets, which frequently lead to lighting inconsistencies between the inserted foreground and the background. Moreover, the reliance on limited, manually-curated 3D assets hinders large-scale deployment. To address these challenges, we propose DriveWeaver, a novel framework for controllable vehicle insertion in autonomous driving simulation. Specifically, for a masked target insertion area, DriveWeaver performs video inpainting conditioned on vehicle point clouds to generate high-quality, temporally consistent vehicles. This video-inpainting-based approach ensures seamless blending between the foreground and background, while the readily available point cloud conditions enable superior generalization. To support long-term generation, we further design a global-to-local hierarchical inpainting strategy, ensuring the consistent identity and appearance of the inserted vehicles. Meanwhile, we extract explicit 3D Gaussian representations of the inserted vehicles through an urban reconstruction pipeline to enable real-time rendering for autonomous driving simulation. Extensive experiments across diverse datasets demonstrate that our method outperforms existing baselines in visual realism and geometric consistency, providing a robust tool for scalable autonomous driving scene augmentation.
