# Showing new listings for Thursday, 19 March 2026
## Keyword: SLAM
### Title:
          SLAM Adversarial Lab: An Extensible Framework for Visual SLAM Robustness Evaluation under Adverse Conditions
 - **Authors:** Mohamed Hefny, Karthik Dantu, Steven Y. Ko
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present SAL (SLAM Adversarial Lab), a modular framework for evaluating visual SLAM systems under adversarial conditions such as fog and rain. SAL represents each adversarial condition as a perturbation that transforms an existing dataset into an adversarial dataset. When transforming a dataset, SAL supports severity levels using easily-interpretable real-world units such as meters for fog visibility. SAL's extensible architecture decouples datasets, perturbations, and SLAM algorithms through common interfaces, so users can add new components without rewriting integration code. Moreover, SAL includes a search procedure that finds the severity level of a perturbation at which a SLAM system fails. To showcase the capabilities of SAL, our evaluation integrates seven SLAM algorithms and evaluates them across three datasets under weather, camera, and video transport perturbations.
### Title:
          FastLoop: Parallel Loop Closing with GPU-Acceleration in Visual SLAM
 - **Authors:** Soudabeh Mohammadhashemi, Shishir Gopinath, Kimia Khabiri, Parsa Hosseininejad, Karthik Dantu, Steven Y. Ko
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual SLAM systems combine visual tracking with global loop closure to maintain a consistent map and accurate localization. Loop closure is a computationally expensive process as we need to search across the whole map for matches. This paper presents FastLoop, a GPU-accelerated loop closing module to alleviate this computational complexity. We identify key performance bottlenecks in the loop closing pipeline of visual SLAM and address them through parallel optimizations on the GPU. Specifically, we use task-level and data-level parallelism and integrate a GPU-accelerated pose graph optimization. Our implementation is built on top of ORB-SLAM3 and leverages CUDA for GPU programming. Experimental results show that FastLoop achieves an average speedup of 1.4x and 1.3x on the EuRoC dataset and 3.0x and 2.4x on the TUM-VI dataset for the loop closing module on desktop and embedded platforms, respectively, while maintaining the accuracy of the original system.
### Title:
          Visual SLAM with DEM Anchoring for Lunar Surface Navigation
 - **Authors:** Adam Dai, Guillem Casadesus Vila, Grace Gao
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Future lunar missions will require autonomous rovers capable of traversing tens of kilometers across challenging terrain while maintaining accurate localization and producing globally consistent maps. However, the absence of global positioning systems, extreme illumination, and low-texture regolith make long-range navigation on the Moon particularly difficult, as visual-inertial odometry pipelines accumulate drift over extended traverses. To address this challenge, we present a stereo visual simultaneous localization and mapping (SLAM) system that integrates learned feature detection and matching with global constraints from digital elevation models (DEMs). Our front-end employs learning-based feature extraction and matching to achieve robustness to illumination extremes and repetitive terrain, while the back-end incorporates DEM-derived height and surface-normal factors into a pose graph, providing absolute surface constraints that mitigate long-term drift. We validate our approach using both simulated lunar traverse data generated in Unreal Engine and real Moon/Mars analog data collected from Mt. Etna. Results demonstrate that DEM anchoring consistently reduces absolute trajectory error compared to baseline SLAM methods, lowering drift in long-range navigation even in repetitive or visually aliased terrain.
### Title:
          Full Stack Navigation, Mapping, and Planning for the Lunar Autonomy Challenge
 - **Authors:** Adam Dai, Asta Wu, Keidai Iiyama, Guillem Casadesus Vila, Kaila Coimbra, Thomas Deng, Grace Gao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a modular, full-stack autonomy system for lunar surface navigation and mapping developed for the Lunar Autonomy Challenge. Operating in a GNSS-denied, visually challenging environment, our pipeline integrates semantic segmentation, stereo visual odometry, pose graph SLAM with loop closures, and layered planning and control. We leverage lightweight learning-based perception models for real-time segmentation and feature tracking and use a factor-graph backend to maintain globally consistent localization. High-level waypoint planning is designed to promote mapping coverage while encouraging frequent loop closures, and local motion planning uses arc sampling with geometric obstacle checks for efficient, reactive control. We evaluate our approach in the competition's high-fidelity lunar simulator, demonstrating centimeter-level localization accuracy, high-fidelity map generation, and strong repeatability across random seeds and rock distributions. Our solution achieved first place in the final competition evaluation.
### Title:
          OnlineHMR: Video-based Online World-Grounded Human Mesh Recovery
 - **Authors:** Yiwen Zhao, Ce Zheng, Yufu Wang, Hsueh-Han Daniel Yang, Liting Wen, Laszlo A. Jeni
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Human mesh recovery (HMR) models 3D human body from monocular videos, with recent works extending it to world-coordinate human trajectory and motion reconstruction. However, most existing methods remain offline, relying on future frames or global optimization, which limits their applicability in interactive feedback and perception-action loop scenarios such as AR/VR and telepresence. To address this, we propose OnlineHMR, a fully online framework that jointly satisfies four essential criteria of online processing, including system-level causality, faithfulness, temporal consistency, and efficiency. Built upon a two-branch architecture, OnlineHMR enables streaming inference via a causal key-value cache design and a curated sliding-window learning strategy. Meanwhile, a human-centric incremental SLAM provides online world-grounded alignment under physically plausible trajectory correction. Experimental results show that our method achieves performance comparable to existing chunk-based approaches on the standard EMDB benchmark and highly dynamic custom videos, while uniquely supporting online processing. Page and code are available at this https URL.
## Keyword: odometry
### Title:
          Visual SLAM with DEM Anchoring for Lunar Surface Navigation
 - **Authors:** Adam Dai, Guillem Casadesus Vila, Grace Gao
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Future lunar missions will require autonomous rovers capable of traversing tens of kilometers across challenging terrain while maintaining accurate localization and producing globally consistent maps. However, the absence of global positioning systems, extreme illumination, and low-texture regolith make long-range navigation on the Moon particularly difficult, as visual-inertial odometry pipelines accumulate drift over extended traverses. To address this challenge, we present a stereo visual simultaneous localization and mapping (SLAM) system that integrates learned feature detection and matching with global constraints from digital elevation models (DEMs). Our front-end employs learning-based feature extraction and matching to achieve robustness to illumination extremes and repetitive terrain, while the back-end incorporates DEM-derived height and surface-normal factors into a pose graph, providing absolute surface constraints that mitigate long-term drift. We validate our approach using both simulated lunar traverse data generated in Unreal Engine and real Moon/Mars analog data collected from Mt. Etna. Results demonstrate that DEM anchoring consistently reduces absolute trajectory error compared to baseline SLAM methods, lowering drift in long-range navigation even in repetitive or visually aliased terrain.
### Title:
          Full Stack Navigation, Mapping, and Planning for the Lunar Autonomy Challenge
 - **Authors:** Adam Dai, Asta Wu, Keidai Iiyama, Guillem Casadesus Vila, Kaila Coimbra, Thomas Deng, Grace Gao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a modular, full-stack autonomy system for lunar surface navigation and mapping developed for the Lunar Autonomy Challenge. Operating in a GNSS-denied, visually challenging environment, our pipeline integrates semantic segmentation, stereo visual odometry, pose graph SLAM with loop closures, and layered planning and control. We leverage lightweight learning-based perception models for real-time segmentation and feature tracking and use a factor-graph backend to maintain globally consistent localization. High-level waypoint planning is designed to promote mapping coverage while encouraging frequent loop closures, and local motion planning uses arc sampling with geometric obstacle checks for efficient, reactive control. We evaluate our approach in the competition's high-fidelity lunar simulator, demonstrating centimeter-level localization accuracy, high-fidelity map generation, and strong repeatability across random seeds and rock distributions. Our solution achieved first place in the final competition evaluation.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          BEV-SLD: Self-Supervised Scene Landmark Detection for Global Localization with LiDAR Bird's-Eye View Images
 - **Authors:** David Skuddis, Vincent Ress, Wei Zhang, Vincent Ofosu Nyako, Norbert Haala
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present BEV-SLD, a LiDAR global localization method building on the Scene Landmark Detection (SLD) concept. Unlike scene-agnostic pipelines, our self-supervised approach leverages bird's-eye-view (BEV) images to discover scene-specific patterns at a prescribed spatial density and treat them as landmarks. A consistency loss aligns learnable global landmark coordinates with per-frame heatmaps, yielding consistent landmark detections across the scene. Across campus, industrial, and forest environments, BEV-SLD delivers robust localization and achieves strong performance compared to state-of-the-art methods.
### Title:
          OmniVLN: Omnidirectional 3D Perception and Token-Efficient LLM Reasoning for Visual-Language Navigation across Air and Ground Platforms
 - **Authors:** Zhongyuang Liu, Min He, Shaonan Yu, Xinhang Xu, Muqing Cao, Jianping Li, Jianfei Yang, Lihua Xie
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Language-guided embodied navigation requires an agent to interpret object-referential instructions, search across multiple rooms, localize the referenced target, and execute reliable motion toward it. Existing systems remain limited in real indoor environments because narrow field-of-view sensing exposes only a partial local scene at each step, often forcing repeated rotations, delaying target discovery, and producing fragmented spatial understanding; meanwhile, directly prompting LLMs with dense 3D maps or exhaustive object lists quickly exceeds the context budget. We present OmniVLN, a zero-shot visual-language navigation framework that couples omnidirectional 3D perception with token-efficient hierarchical reasoning for both aerial and ground robots. OmniVLN fuses a rotating LiDAR and panoramic vision into a hardware-agnostic mapping stack, incrementally constructs a five-layer Dynamic Scene Graph (DSG) from mesh geometry to room- and building-level structure, and stabilizes high-level topology through persistent-homology-based room partitioning and hybrid geometric/VLM relation verification. For navigation, the global DSG is transformed into an agent-centric 3D octant representation with multi-resolution spatial attention prompting, enabling the LLM to progressively filter candidate rooms, infer egocentric orientation, localize target objects, and emit executable navigation primitives while preserving fine local detail and compact long-range memory. Experiments show that the proposed hierarchical interface improves spatial referring accuracy from 77.27\% to 93.18\%, reduces cumulative prompt tokens by up to 61.7\% in cluttered multi-room settings, and improves navigation success by up to 11.68\% over a flat-list baseline. We will release the code and an omnidirectional multimodal dataset to support reproducible research.
### Title:
          VisionNVS: Self-Supervised Inpainting for Novel View Synthesis under the Virtual-Shift Paradigm
 - **Authors:** Hongbo Lu, Liang Yao, Chenghao He, Fan Liu, Wenlong Liao, Tao He, Pai Peng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A fundamental bottleneck in Novel View Synthesis (NVS) for autonomous driving is the inherent supervision gap on novel trajectories: models are tasked with synthesizing unseen views during inference, yet lack ground truth images for these shifted poses during training. In this paper, we propose VisionNVS, a camera-only framework that fundamentally reformulates view synthesis from an ill-posed extrapolation problem into a self-supervised inpainting task. By introducing a ``Virtual-Shift'' strategy, we use monocular depth proxies to simulate occlusion patterns and map them onto the original view. This paradigm shift allows the use of raw, recorded images as pixel-perfect supervision, effectively eliminating the domain gap inherent in previous approaches. Furthermore, we address spatial consistency through a Pseudo-3D Seam Synthesis strategy, which integrates visual data from adjacent cameras during training to explicitly model real-world photometric discrepancies and calibration errors. Experiments demonstrate that VisionNVS achieves superior geometric fidelity and visual quality compared to LiDAR-dependent baselines, offering a robust solution for scalable driving simulation.
### Title:
          SafeLand: Safe Autonomous Landing in Unknown Environments with Bayesian Semantic Mapping
 - **Authors:** Markus Gross, Andreas Greiner, Sai Bharadhwaj Matha, Felix Soest, Daniel Cremers, Henri Meeß
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous landing of uncrewed aerial vehicles (UAVs) in unknown, dynamic environments poses significant safety challenges, particularly near people and infrastructure, as UAVs transition to routine urban and rural operations. Existing methods often rely on prior maps, heavy sensors like LiDAR, static markers, or fail to handle non-cooperative dynamic obstacles like humans, limiting generalization and real-time performance. To address these challenges, we introduce SafeLand, a lean, vision-based system for safe autonomous landing (SAL) that requires no prior information and operates only with a camera and a lightweight height sensor. Our approach constructs an online semantic ground map via deep learning-based semantic segmentation, optimized for embedded deployment and trained on a consolidation of seven curated public aerial datasets (achieving 70.22% mIoU across 20 classes), which is further refined through Bayesian probabilistic filtering with temporal semantic decay to robustly identify metric-scale landing spots. A behavior tree then governs adaptive landing, iteratively validates the spot, and reacts in real time to dynamic obstacles by pausing, climbing, or rerouting to alternative spots, maximizing human safety. We extensively evaluate our method in 200 simulations and 60 end-to-end field tests across industrial, urban, and rural environments at altitudes up to 100m, demonstrating zero false negatives for human detection. Compared to the state of the art, SafeLand achieves sub-second response latency, substantially lower than previous methods, while maintaining a superior success rate of 95%. To facilitate further research in aerial robotics, we release SafeLand's segmentation model as a plug-and-play ROS package, available at this https URL.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          Neural Radiance Maps for Extraterrestrial Navigation and Path Planning
 - **Authors:** Adam Dai, Shubh Gupta, Grace Gao
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous vehicles such as the Mars rovers currently lead the vanguard of surface exploration on extraterrestrial planets and moons. In order to accelerate the pace of exploration and science objectives, it is critical to plan safe and efficient paths for these vehicles. However, current rover autonomy is limited by a lack of global maps which can be easily constructed and stored for onboard re-planning. Recently, Neural Radiance Fields (NeRFs) have been introduced as a detailed 3D scene representation which can be trained from sparse 2D images and efficiently stored. We propose to use NeRFs to construct maps for online use in autonomous navigation, and present a planning framework which leverages the NeRF map to integrate local and global information. Our approach interpolates local cost observations across global regions using kernel ridge regression over terrain features extracted from the NeRF map, allowing the rover to re-route itself around untraversable areas discovered during online operation. We validate our approach in high-fidelity simulation and demonstrate lower cost and higher percentage success rate path planning compared to various baselines.
## Keyword: mapping
### Title:
          Implementation of tangent linear and adjoint models for neural networks based on a compiler library tool
 - **Authors:** Sa Xiao, Hao Jing, Honglu Sun, Haoyu Li
 - **Subjects:** Subjects:
Mathematical Software (cs.MS); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents TorchNWP, a compilation library tool for the efficient coupling of artificial intelligence components and traditional numerical models. It aims to address the issues of poor cross-language compatibility, insufficient coupling flexibility, and low data transfer efficiency between operational numerical models developed in Fortran and Python-based deep learning frameworks. Based on LibTorch, it optimizes and designs a unified application-layer calling interface, converts deep learning models under the PyTorch framework into a static binary format, and provides C/C++ interfaces. Then, using hybrid Fortran/C/C++ programming, it enables the deployment of deep learning models within numerical models. Integrating TorchNWP into a numerical model only requires compiling it into a callable link library and linking it during the compilation and linking phase to generate the executable. On this basis, tangent linear and adjoint model based on neural networks are implemented at the C/C++ level, which can shield the internal structure of neural network models and simplify the construction process of four-dimensional variational data assimilation systems. Meanwhile, it supports deployment on heterogeneous platforms, is compatible with mainstream neural network models, and enables mapping of different parallel granularities and efficient parallel execution. Using this tool requires minimal code modifications to the original numerical model, thus reducing coupling costs. It can be efficiently integrated into numerical weather prediction models such as CMA-GFS and MCV, and has been applied to the coupling of deep learning-based physical parameterization schemes (e.g., radiation, non-orographic gravity wave drag) and the development of their tangent linear and adjoint models, significantly improving the accuracy and efficiency of numerical weather prediction.
### Title:
          Contextual Preference Distribution Learning
 - **Authors:** Benjamin Hudson, Laurent Charlin, Emma Frejinger
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Decision-making problems often feature uncertainty stemming from heterogeneous and context-dependent human preferences. To address this, we propose a sequential learning-and-optimization pipeline to learn preference distributions and leverage them to solve downstream problems, for example risk-averse formulations. We focus on human choice settings that can be formulated as (integer) linear programs. In such settings, existing inverse optimization and choice modelling methods infer preferences from observed choices but typically produce point estimates or fail to capture contextual shifts, making them unsuitable for risk-averse decision-making. Using a bounded-variance score function gradient estimator, we train a predictive model mapping contextual features to a rich class of parameterizable distributions. This approach yields a maximum likelihood estimate. The model generates scenarios for unseen contexts in the subsequent optimization phase. In a synthetic ridesharing environment, our approach reduces average post-decision surprise by up to 114$\times$ compared to a risk-neutral approach with perfect predictions and up to 25$\times$ compared to leading risk-averse baselines.
### Title:
          Visual SLAM with DEM Anchoring for Lunar Surface Navigation
 - **Authors:** Adam Dai, Guillem Casadesus Vila, Grace Gao
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Future lunar missions will require autonomous rovers capable of traversing tens of kilometers across challenging terrain while maintaining accurate localization and producing globally consistent maps. However, the absence of global positioning systems, extreme illumination, and low-texture regolith make long-range navigation on the Moon particularly difficult, as visual-inertial odometry pipelines accumulate drift over extended traverses. To address this challenge, we present a stereo visual simultaneous localization and mapping (SLAM) system that integrates learned feature detection and matching with global constraints from digital elevation models (DEMs). Our front-end employs learning-based feature extraction and matching to achieve robustness to illumination extremes and repetitive terrain, while the back-end incorporates DEM-derived height and surface-normal factors into a pose graph, providing absolute surface constraints that mitigate long-term drift. We validate our approach using both simulated lunar traverse data generated in Unreal Engine and real Moon/Mars analog data collected from Mt. Etna. Results demonstrate that DEM anchoring consistently reduces absolute trajectory error compared to baseline SLAM methods, lowering drift in long-range navigation even in repetitive or visually aliased terrain.
### Title:
          Full Stack Navigation, Mapping, and Planning for the Lunar Autonomy Challenge
 - **Authors:** Adam Dai, Asta Wu, Keidai Iiyama, Guillem Casadesus Vila, Kaila Coimbra, Thomas Deng, Grace Gao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a modular, full-stack autonomy system for lunar surface navigation and mapping developed for the Lunar Autonomy Challenge. Operating in a GNSS-denied, visually challenging environment, our pipeline integrates semantic segmentation, stereo visual odometry, pose graph SLAM with loop closures, and layered planning and control. We leverage lightweight learning-based perception models for real-time segmentation and feature tracking and use a factor-graph backend to maintain globally consistent localization. High-level waypoint planning is designed to promote mapping coverage while encouraging frequent loop closures, and local motion planning uses arc sampling with geometric obstacle checks for efficient, reactive control. We evaluate our approach in the competition's high-fidelity lunar simulator, demonstrating centimeter-level localization accuracy, high-fidelity map generation, and strong repeatability across random seeds and rock distributions. Our solution achieved first place in the final competition evaluation.
### Title:
          Beyond bouba/kiki: Multidimensional semantic signals are deeply woven into the fabric of natural language
 - **Authors:** Gexin Zhao
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Neurons and Cognition (q-bio.NC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A foundational assumption in linguistics holds that the relationship between a word's sound and its meaning is arbitrary. Accumulating evidence from sound symbolism challenges this view, yet no study has systematically mapped the multidimensional semantic profile of every phonological unit within a language. Here we show that individual letter-phonemes in English carry structured, multidimensional semantic signals. Using a minimal-pair paradigm spanning all 220 pairwise letter contrasts, three large language models independently recover consistent phoneme-meaning associations across nine perceptual dimensions. These associations are systematically predicted by articulatory-phonetic features, with manner and place of articulation mapping onto distinct semantic dimensions. Behavioral data from English speakers confirm these patterns at rates well above chance (80.8%), and preliminary cross-linguistic evidence from five typologically diverse languages suggests that core mappings generalize beyond English. Our findings indicate that sound-meaning iconicity is not an occasional curiosity but a pervasive, structured property of the phonological signal, one so systematic that large language models recover it when given only text input, without exposure to speech or articulation during the task.
### Title:
          Ruyi2.5 Technical Report
 - **Authors:** Huan Song, Shuyu Tian, Qingfei Zhao, Wenhao Hong, Jiang Liu, Ting Long, Jiawei Shao, Xuelong Li
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Ruyi2.5, a multimodal familial model built on the AI Flow framework. Extending Ruyi2's "Train Once, Deploy Many" paradigm to the multimodal domain, Ruyi2.5 constructs a shared-backbone architecture that co-trains models of varying scales within a single unified pipeline, ensuring semantic consistency across all deployment tiers. Built upon Ruyi2.5, Ruyi2.5-Camera model is developed as a privacy-preserving camera service system, which instantiates Ruyi2.5-Camera into a two-stage recognition pipeline: an edge model applies information-bottleneck-guided irreversible feature mapping to de-identify raw frames at the source, while a cloud model performs deep behavior reasoning. To accelerate reinforcement learning fine-tuning, we further propose Binary Prefix Policy Optimization (BPPO), which reduces sample redundancy via binary response selection and focuses gradient updates on response prefixes, achieving a 2 to 3 times training speedup over GRPO. Experiments show Ruyi2.5 matches Qwen3-VL on the general multimodal benchmarks, while Ruyi2.5-Camera substantially outperforms Qwen3-VL on privacy-constrained surveillance tasks.
### Title:
          OmniVLN: Omnidirectional 3D Perception and Token-Efficient LLM Reasoning for Visual-Language Navigation across Air and Ground Platforms
 - **Authors:** Zhongyuang Liu, Min He, Shaonan Yu, Xinhang Xu, Muqing Cao, Jianping Li, Jianfei Yang, Lihua Xie
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Language-guided embodied navigation requires an agent to interpret object-referential instructions, search across multiple rooms, localize the referenced target, and execute reliable motion toward it. Existing systems remain limited in real indoor environments because narrow field-of-view sensing exposes only a partial local scene at each step, often forcing repeated rotations, delaying target discovery, and producing fragmented spatial understanding; meanwhile, directly prompting LLMs with dense 3D maps or exhaustive object lists quickly exceeds the context budget. We present OmniVLN, a zero-shot visual-language navigation framework that couples omnidirectional 3D perception with token-efficient hierarchical reasoning for both aerial and ground robots. OmniVLN fuses a rotating LiDAR and panoramic vision into a hardware-agnostic mapping stack, incrementally constructs a five-layer Dynamic Scene Graph (DSG) from mesh geometry to room- and building-level structure, and stabilizes high-level topology through persistent-homology-based room partitioning and hybrid geometric/VLM relation verification. For navigation, the global DSG is transformed into an agent-centric 3D octant representation with multi-resolution spatial attention prompting, enabling the LLM to progressively filter candidate rooms, infer egocentric orientation, localize target objects, and emit executable navigation primitives while preserving fine local detail and compact long-range memory. Experiments show that the proposed hierarchical interface improves spatial referring accuracy from 77.27\% to 93.18\%, reduces cumulative prompt tokens by up to 61.7\% in cluttered multi-room settings, and improves navigation success by up to 11.68\% over a flat-list baseline. We will release the code and an omnidirectional multimodal dataset to support reproducible research.
### Title:
          Agentic Cognitive Profiling: Realigning Automated Alzheimer's Disease Detection with Clinical Construct Validity
 - **Authors:** Jiawen Kang, Kun Li, Dongrui Han, Jinchao Li, Junan Li, Lingwei Meng, Xixin Wu, Helen Meng
 - **Subjects:** Subjects:
Multiagent Systems (cs.MA); Information Retrieval (cs.IR); Neurons and Cognition (q-bio.NC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated Alzheimer's Disease (AD) screening has predominantly followed the inductive paradigm of pattern recognition, which directly maps the input signal to the outcome label. This paradigm sacrifices construct validity of clinical protocol for statistical shortcuts. This paper proposes Agentic Cognitive Profiling (ACP), an agentic framework that realigns automated screening with clinical protocol logic across multiple cognitive domains. Rather than learning opaque mappings from transcripts to labels, the framework decomposes standardized assessments into atomic cognitive tasks and orchestrates specialized LLM agents to extract verifiable scoring primitives. Central to our design is decoupling semantic understanding from measurement by delegating all quantification to deterministic function calling, thereby mitigating hallucination and restoring construct validity. Unlike popular datasets that typically comprise around a hundred participants under a single task, we evaluate on a clinically-annotated corpus of 402 participants across eight structured cognitive tasks spanning multiple cognitive domains. The framework achieves 90.5% score match rate in task examination and 85.3% accuracy in AD prediction, surpassing popular baselines while generating interpretable cognitive profiles grounded in behavioral evidence. This work demonstrates that construct validity and predictive performance need not be traded off, charting a path toward AD screening systems that explain rather than merely predict.
### Title:
          A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awarenes
 - **Authors:** Xiucheng Wang, Yuhao Pan, Nan Cheng
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The integration of artificial intelligence into next-generation wireless networks necessitates the accurate construction of radio maps (RMs) as a foundational prerequisite for electromagnetic digital twins. A RM provides the digital representation of the wireless propagation environment, mapping complex geographical and topological boundary conditions to critical spatial-spectral metrics that range from received signal strength to full channel state information matrices. This tutorial presents a comprehensive survey of learning-based RM construction, systematically addressing three intertwined dimensions: data, paradigms, and physics-awareness. From the data perspective, we review physical measurement campaigns, ray tracing simulation engines, and publicly available benchmark datasets, identifying their respective strengths and fundamental limitations. From the paradigm perspective, we establish a core taxonomy that categorizes RM construction into source-aware forward prediction and source-agnostic inverse reconstruction, and examine five principal neural architecture families spanning convolutional neural networks, vision transformers, graph neural networks, generative adversarial networks, and diffusion models. We further survey optics-inspired methods adapted from neural radiance fields and 3D Gaussian splatting for continuous wireless radiation field modeling. From the physics-awareness perspective, we introduce a three-level integration framework encompassing data-level feature engineering, loss-level partial differential equation regularization, and architecture-level structural isomorphism. Open challenges including foundation model development, physical hallucination detection, and amortized inference for real-time deployment are discussed to outline future research directions.
### Title:
          Adaptive Encoding Strategy for Quantum Annealing in Mixed-Variable Engineering Optimization
 - **Authors:** Fabian Key, Lukas Freinberger, Mayu Muramatsu, Norbert Hosters
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mixed discrete-continuous optimization is central to engineering design, where discrete choices interact with continuous fields. These problems are difficult due to high-dimensional, complex search spaces. To tackle them, Quantum Annealing (QA) is promising, yet its native binary nature supports only discrete variables, making accurate and efficient encodings of continuous quantities a central challenge. Existing approaches either split the coupled problem, mapping discrete decisions to QA while solving continuous fields classically, or use fixed-bit-depth encodings. The former compromises QA's global search advantages; the latter can underrepresent dynamic range or inflate the number of binary variables. We show that simply increasing bit depth can even degrade performance on current QA hardware, underscoring the need for alternative encodings. In response, we introduce an adaptive encoding strategy for continuous variables in QA that enables efficient treatment of coupled mixed-variable problems. We propose an update strategy for the representable ranges of the continuous variables and demonstrate its utility by integrating it into the minimum complementary energy formulation for structural design optimization, which provides a single, coupled constrained problem. We apply a quadratic penalty method where we update the representation of the continuous variables while targeting the full original objective, preserving QA's global search capability. On a published benchmark, the size optimization of a composite rod, our adaptive encoding improves solution quality under a fixed binary variable budget, demonstrating a superior precision-resource trade-off. Since the framework generalizes beyond structural design, it offers practical guidance for encoding continuous variables for QA and indicates that adaptive representations can enhance precision on current hardware.
### Title:
          Language on Demand, Knowledge at Core: Composing LLMs with Encoder-Decoder Translation Models for Extensible Multilinguality
 - **Authors:** Mengyu Bu, Yang Feng
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) exhibit strong general intelligence, yet their multilingual performance remains highly imbalanced. Although LLMs encode substantial cross-lingual knowledge in a unified semantic space, they often struggle to reliably interface this knowledge with low-resource or unseen languages. Fortunately, pretrained encoder-decoder translation models already possess balanced multilingual capability, suggesting a natural complement to LLMs. In this work, we propose XBridge, a compositional encoder-LLM-decoder architecture that offloads multilingual understanding and generation to external pretrained translation models, while preserving the LLM as an English-centric core for general knowledge processing. To address the resulting representation misalignment across models, we introduce lightweight cross-model mapping layers and an optimal transport-based alignment objective, enabling fine-grained semantic consistency for multilingual generation. Experiments on four LLMs across multilingual understanding, reasoning, summarization, and generation indicate that XBridge outperforms strong baselines, especially on low-resource and previously unseen languages, without retraining the LLM.
### Title:
          Conditional Inverse Learning of Time-Varying Reproduction Numbers Inference
 - **Authors:** Lanlan Yu, Quan-Hui Liu, Haoyue Zheng, Xinfu Yang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Physics and Society (physics.soc-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Estimating time-varying reproduction numbers from epidemic incidence data is a central task in infectious disease surveillance, yet it poses an inherently ill-posed inverse problem. Existing approaches often rely on strong structural assumptions derived from epidemiological models, which can limit their ability to adapt to non-stationary transmission dynamics induced by interventions or behavioral changes, leading to delayed detection of regime shifts and degraded estimation accuracy. In this work, we propose a Conditional Inverse Reproduction Learning framework (CIRL) that addresses the inverse problem by learning a {conditional mapping} from historical incidence patterns and explicit time information to latent reproduction numbers. Rather than imposing strongly enforced parametric constraints, CIRL softly integrates epidemiological structure with flexible likelihood-based statistical modeling, using the renewal equation as a forward operator to enforce dynamical consistency. The resulting framework combines epidemiologically grounded constraints with data-driven temporal representations, producing reproduction number estimates that are robust to observation noise while remaining responsive to abrupt transmission changes and zero-inflated incidence observations. Experiments on synthetic epidemics with controlled regime changes and real-world SARS and COVID-19 data demonstrate the effectiveness of the proposed approach.
### Title:
          An Extended T-A Formulation Based on Potential-Chain Recursion for Electromagnetic Modeling of Parallel-Wound No-Insulation HTS Coils
 - **Authors:** Zhe Pan, Qi Xu, Ruixiang Wang, Zhenghao Jin, Jianzhao Geng
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Parallel-wound no-insulation (PW-NI) high-temperature superconducting (HTS) coils significantly reduce charging delay while maintaining excellent self-protection capability, demonstrating great potential for high-field applications. Existing models that couple the T-A formulation with equivalent circuits have demonstrated high accuracy in electromagnetic analysis of PW-NI coils. However, eliminating the computational overhead caused by frequent variable mapping and data exchange between electromagnetic and circuit modules is important for improving computational efficiency, particularly in long-duration transient simulations of large-scale magnets. To address this issue, an extended T-A formulation based on potential-chain recursion, termed PCR-TA, is proposed. By directly embedding inter-tape current sharing and radial current bypass behaviors into the finite-element framework, this method computes the transient electromagnetic response of PW-NI coils without requiring an explicit equivalent circuit model. Building upon it, a multi-scale approach is further developed for large-scale PW-NI coils. The validity of the proposed method and its multi-scale extension is verified through comparisons with experimental measurements and field-circuit coupled modeling results. Comparative analyses demonstrate that the PCR-TA method achieves a speedup of approximately 2.4 over the field-circuit coupled method, whereas its multi-scale extension further increases this speedup to roughly 5.8. Furthermore, the PCR-TA method is extended to model the continuous transition of PW-NI coils from power-supply charging to closed-loop operation. This work provides an efficient method and tool for the electromagnetic modeling of PW-NI coils under both driven and closed-loop operating conditions.
### Title:
          AdaMuS: Adaptive Multi-view Sparsity Learning for Dimensionally Unbalanced Data
 - **Authors:** Cai Xu, Changhao Sun, Ziyu Guan, Wei Zhao
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-view learning primarily aims to fuse multiple features to describe data comprehensively. Most prior studies implicitly assume that different views share similar dimensions. In practice, however, severe dimensional disparities often exist among different views, leading to the unbalanced multi-view learning issue. For example, in emotion recognition tasks, video frames often reach dimensions of $10^6$, while physiological signals comprise only $10^1$ dimensions. Existing methods typically face two main challenges for this problem: (1) They often bias towards high-dimensional data, overlooking the low-dimensional views. (2) They struggle to effectively align representations under extreme dimensional imbalance, which introduces severe redundancy into the low-dimensional ones. To address these issues, we propose the Adaptive Multi-view Sparsity Learning (AdaMuS) framework. First, to prevent ignoring the information of low-dimensional views, we construct view-specific encoders to map them into a unified dimensional space. Given that mapping low-dimensional data to a high-dimensional space often causes severe overfitting, we design a parameter-free pruning method to adaptively remove redundant parameters in the encoders. Furthermore, we propose a sparse fusion paradigm that flexibly suppresses redundant dimensions and effectively aligns each view. Additionally, to learn representations with stronger generalization, we propose a self-supervised learning paradigm that obtains supervision information by constructing similarity graphs. Extensive evaluations on a synthetic toy dataset and seven real-world benchmarks demonstrate that AdaMuS consistently achieves superior performance and exhibits strong generalization across both classification and semantic segmentation tasks.
### Title:
          Interpretable Cross-Domain Few-Shot Learning with Rectified Target-Domain Local Alignment
 - **Authors:** Yaze Zhao, Yixiong Zou, Yuhua Li, Ruixuan Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-Domain Few-Shot Learning (CDFSL) adapts models trained with large-scale general data (source domain) to downstream target domains with only scarce training data, where the research on vision-language models (e.g., CLIP) is still in the early stages. Typical downstream domains, such as medical diagnosis, require fine-grained visual cues for interpretable recognition, but we find that current fine-tuned CLIP models can hardly focus on these cues, albeit they can roughly focus on important regions in source domains. Although current works have demonstrated CLIP's shortcomings in capturing local subtle patterns, in this paper, we find that the domain gap and scarce training data further exacerbate such shortcomings, much more than that of holistic patterns, which we call the local misalignment problem in CLIP-based CDFSL. To address this problem, due to the lack of supervision in aligning local visual features and text semantics, we turn to self-supervision information. Inspired by the translation task, we propose the CC-CDFSL method with cycle consistency, which translates local visual features into text features and then translates them back into visual features (and vice versa), and constrains the original features close to the translated back features. To reduce the noise imported by richer information in the visual modality, we further propose a Semantic Anchor mechanism, which first augments visual features to provide a larger corpus for the text-to-image mapping, and then shrinks the image features to filter out irrelevant image-to-text mapping. Extensive experiments on various benchmarks, backbones, and fine-tuning methods show we can (1) effectively improve the local vision-language alignment, (2) enhance the interpretability of learned patterns and model decisions by visualizing patches, and (3) achieve state-of-the-art performance.
### Title:
          AgentVLN: Towards Agentic Vision-and-Language Navigation
 - **Authors:** Zihao Xin, Wentong Li, Yixuan Jiang, Ziyuan Huang, Bin Wang, Piji Li, Jianke Zhu, Jie Qin, Shengjun Huang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-and-Language Navigation (VLN) requires an embodied agent to ground complex natural-language instructions into long-horizon navigation in unseen environments. While Vision-Language Models (VLMs) offer strong 2D semantic understanding, current VLN systems remain constrained by limited spatial perception, 2D-3D representation mismatch, and monocular scale ambiguity. In this paper, we propose AgentVLN, a novel and efficient embodied navigation framework that can be deployed on edge computing platforms. We formulate VLN as a Partially Observable Semi-Markov Decision Process (POSMDP) and introduce a VLM-as-Brain paradigm that decouples high-level semantic reasoning from perception and planning via a plug-and-play skill library. To resolve multi-level representation inconsistency, we design a cross-space representation mapping that projects perception-layer 3D topological waypoints into the image plane, yielding pixel-aligned visual prompts for the VLM. Building on this bridge, we integrate a context-aware self-correction and active exploration strategy to recover from occlusions and suppress error accumulation over long trajectories. To further address the spatial ambiguity of instructions in unstructured environments, we propose a Query-Driven Perceptual Chain-of-Thought (QD-PCoT) scheme, enabling the agent with the metacognitive ability to actively seek geometric depth information. Finally, we construct AgentVLN-Instruct, a large-scale instruction-tuning dataset with dynamic stage routing conditioned on target visibility. Extensive experiments show that AgentVLN consistently outperforms prior state-of-the-art methods (SOTA) on long-horizon VLN benchmarks, offering a practical paradigm for lightweight deployment of next-generation embodied navigation models. Code: this https URL.
### Title:
          Consistency-Driven Dual LSTM Models for Kinematic Control of a Wearable Soft Robotic Arm
 - **Authors:** Xingyu Chen, Yi Xiong, Li Wen
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we introduce a consistency-driven dual LSTM framework for accurately learning both the forward and inverse kinematics of a pneumatically actuated soft robotic arm integrated into a wearable device. This approach effectively captures the nonlinear and hysteretic behaviors of soft pneumatic actuators while addressing the one-to-many mapping challenge between actuation inputs and end-effector positions. By incorporating a cycle consistency loss, we enhance physical realism and improve the stability of inverse predictions. Extensive experiments-including trajectory tracking, ablation studies, and wearable demonstrations-confirm the effectiveness of our method. Results indicate that the inclusion of the consistency loss significantly boosts prediction accuracy and promotes physical consistency over conventional approaches. Moreover, the wearable soft robotic arm demonstrates strong human-robot collaboration capabilities and adaptability in everyday tasks such as object handover, obstacle-aware pick-and-place, and drawer operation. This work underscores the promising potential of learning-based kinematic models for human-centric, wearable robotic systems.
### Title:
          TINA: Text-Free Inversion Attack for Unlearned Text-to-Image Diffusion Models
 - **Authors:** Qianlong Xiang, Miao Zhang, Haoyu Zhang, Kun Wang, Junhui Hou, Liqiang Nie
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Although text-to-image diffusion models exhibit remarkable generative power, concept erasure techniques are essential for their safe deployment to prevent the creation of harmful content. This has fostered a dynamic interplay between the development of erasure defenses and the adversarial probes designed to bypass them, and this co-evolution has progressively enhanced the efficacy of erasure methods. However, this adversarial co-evolution has converged on a narrow, text-centric paradigm that equates erasure with severing the text-to-image mapping, ignoring that the underlying visual knowledge related to undesired concepts still persist. To substantiate this claim, we investigate from a visual perspective, leveraging DDIM inversion to probe whether a generative pathway for the erased concept can still be found. However, identifying such a visual generative pathway is challenging because standard text-guided DDIM inversion is actively resisted by text-centric defenses within the erased model. To address this, we introduce TINA, a novel Text-free INversion Attack, which enforces this visual-only probe by operating under a null-text condition, thereby avoiding existing text-centric defenses. Moreover, TINA integrates an optimization procedure to overcome the accumulating approximation errors that arise when standard inversion operates without its usual textual guidance. Our experiments demonstrate that TINA regenerates erased concepts from models treated with state-of-the-art unlearning. The success of TINA proves that current methods merely obscure concepts, highlighting an urgent need for paradigms that operate directly on internal visual knowledge.
### Title:
          Crisis-induced differences in attention towards Ukraine in Twitter 2008-2023
 - **Authors:** Mark Mets, Maximilian Schich, Peter Sheridan Dodds
 - **Subjects:** Subjects:
Social and Information Networks (cs.SI); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Aggression against Ukraine has drawn widespread international attention, particularly in the wake of the two Russian invasions into Ukrainian territory in 2014 and 2022. Although previous studies have examined social-media dynamics around these events, a comparative longitudinal data-driven view across languages is still missing. This article fills this gap by mapping added attention to "Ukraine" on Twitter in 28 languages from 2008 to 2023, using a deceptively simple DNA microarray-inspired cartography of log over-expression relative to each language's baseline frequency. This macro-scale visualization makes familiar events stand out while uncovering subtler patterns beyond the cognitive reach of any single-language saudience. Most strikingly, two nearly non-overlapping language clusters emerge, one peaking around 2014 and the other around 2022 with distinct onset and decay profiles that mirror national readiness (or reluctance) to support Ukraine. By capturing attention at local, meso, and global scales, our approach offers a versatile tool for comparing relative bias across languages, user subgroups, platforms, or even historical print corpora. Ultimately, our cartographic approach reveals a troubling asymmetry: while publicly accessible data allows for an approximation of global attention patterns, the complete and unfiltered view remains largely hidden behind the closed, proprietary algorithms of major social media platforms, granting a far more comprehensive access to understanding global information flows.
### Title:
          CARE: Covariance-Aware and Rank-Enhanced Decomposition for Enabling Multi-Head Latent Attention
 - **Authors:** Zhongzhu Zhou, Fengxiang Bie, Ziyan Chen, Zhenyu Zhang, Yibo Yang, Junxiong Wang, Ben Athiwaratkun, Xiaoxia Wu, Shuaiwen Leon Song
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Converting pretrained attention modules such as grouped-query attention (GQA) into multi-head latent attention (MLA) can improve expressivity without increasing KV-cache cost, making it attractive for efficient inference. However, many practical conversion baselines rely on weight-only low-rank approximations (e.g., SVD-style initializations) and uniform rank allocation. They focus on minimizing the difference between weight matrices rather than on how those weights affect input activations, ignore the covariance structure of activations, and enforce uniform rank across layers, causing activation drift and degraded attention fidelity. To address these issues, we propose CARE, a Covariance-Aware, Rank-Enhanced MLA conversion pipeline under a fixed KV width. CARE introduces three key steps: (i) activation-preserving factorization, which aligns the approximation with the actual input activations rather than just the weights; (ii) adjusted-rank allocation, which spreads a fixed KV budget across layers by giving more capacity to layers that need it most; and (iii) KV-parity mapping, which reparameterizes the converted K and V to fit the MLA format while keeping the KV-cache size unchanged. Our method outperforms a uniform-rank SVD baseline on Qwen3-4B/30B-A3B-Instruct-2507 and Llama-3.1-8B/70B-Instruct, reducing one-shot perplexity by up to 215x and improving mean accuracy by up to 1.70x at matched KV budgets. With a brief post-SVD healing fine-tune, we fully recover the original model's accuracy.
## Keyword: localization
### Title:
          Knowledge Localization in Mixture-of-Experts LLMs Using Cross-Lingual Inconsistency
 - **Authors:** Lucas Bandarkar, Alan Ansell, Trevor Cohn
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern LLMs continue to exhibit significant variance in behavior across languages, such as being able to recall factual information in some languages but not others. While typically studied as a problem to be mitigated, in this work, we propose leveraging this cross-lingual inconsistency as a tool for interpretability in mixture-of-experts (MoE) LLMs. Our knowledge localization framework contrasts routing for sets of languages where the model correctly recalls information from languages where it fails. This allows us to isolate model components that play a functional role in answering about a piece of knowledge. Our method proceeds in two stages: (1) querying the model with difficult factual questions across a diverse set of languages to generate "success" and "failure" activation buckets and then (2) applying a statistical contrastive analysis to the MoE router logits to identify experts important for knowledge. To validate the necessity of this small number of experts for answering a knowledge question, we deactivate them and re-ask the question. We find that despite only deactivating about 20 out of 6000 experts, the model no longer answers correctly in over 40% of cases. Generally, this method provides a realistic and scalable knowledge localization approach to address increasingly complex LLMs.
### Title:
          MosaicMem: Hybrid Spatial Memory for Controllable Video World Models
 - **Authors:** Wei Yu, Runjia Qian, Yumeng Li, Liquan Wang, Songheng Yin, Sri Siddarth Chakaravarthy P, Dennis Anthony, Yang Ye, Yidi Li, Weiwei Wan, Animesh Garg
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video diffusion models are moving beyond short, plausible clips toward world simulators that must remain consistent under camera motion, revisits, and intervention. Yet spatial memory remains a key bottleneck: explicit 3D structures can improve reprojection-based consistency but struggle to depict moving objects, while implicit memory often produces inaccurate camera motion even with correct poses. We propose Mosaic Memory (MosaicMem), a hybrid spatial memory that lifts patches into 3D for reliable localization and targeted retrieval, while exploiting the model's native conditioning to preserve prompt-following generation. MosaicMem composes spatially aligned patches in the queried view via a patch-and-compose interface, preserving what should persist while allowing the model to inpaint what should evolve. With PRoPE camera conditioning and two new memory alignment methods, experiments show improved pose adherence compared to implicit memory and stronger dynamic modeling than explicit baselines. MosaicMem further enables minute-level navigation, memory-based scene editing, and autoregressive rollout.
### Title:
          BEV-SLD: Self-Supervised Scene Landmark Detection for Global Localization with LiDAR Bird's-Eye View Images
 - **Authors:** David Skuddis, Vincent Ress, Wei Zhang, Vincent Ofosu Nyako, Norbert Haala
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present BEV-SLD, a LiDAR global localization method building on the Scene Landmark Detection (SLD) concept. Unlike scene-agnostic pipelines, our self-supervised approach leverages bird's-eye-view (BEV) images to discover scene-specific patterns at a prescribed spatial density and treat them as landmarks. A consistency loss aligns learnable global landmark coordinates with per-frame heatmaps, yielding consistent landmark detections across the scene. Across campus, industrial, and forest environments, BEV-SLD delivers robust localization and achieves strong performance compared to state-of-the-art methods.
### Title:
          FastLoop: Parallel Loop Closing with GPU-Acceleration in Visual SLAM
 - **Authors:** Soudabeh Mohammadhashemi, Shishir Gopinath, Kimia Khabiri, Parsa Hosseininejad, Karthik Dantu, Steven Y. Ko
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual SLAM systems combine visual tracking with global loop closure to maintain a consistent map and accurate localization. Loop closure is a computationally expensive process as we need to search across the whole map for matches. This paper presents FastLoop, a GPU-accelerated loop closing module to alleviate this computational complexity. We identify key performance bottlenecks in the loop closing pipeline of visual SLAM and address them through parallel optimizations on the GPU. Specifically, we use task-level and data-level parallelism and integrate a GPU-accelerated pose graph optimization. Our implementation is built on top of ORB-SLAM3 and leverages CUDA for GPU programming. Experimental results show that FastLoop achieves an average speedup of 1.4x and 1.3x on the EuRoC dataset and 3.0x and 2.4x on the TUM-VI dataset for the loop closing module on desktop and embedded platforms, respectively, while maintaining the accuracy of the original system.
### Title:
          Visual SLAM with DEM Anchoring for Lunar Surface Navigation
 - **Authors:** Adam Dai, Guillem Casadesus Vila, Grace Gao
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Future lunar missions will require autonomous rovers capable of traversing tens of kilometers across challenging terrain while maintaining accurate localization and producing globally consistent maps. However, the absence of global positioning systems, extreme illumination, and low-texture regolith make long-range navigation on the Moon particularly difficult, as visual-inertial odometry pipelines accumulate drift over extended traverses. To address this challenge, we present a stereo visual simultaneous localization and mapping (SLAM) system that integrates learned feature detection and matching with global constraints from digital elevation models (DEMs). Our front-end employs learning-based feature extraction and matching to achieve robustness to illumination extremes and repetitive terrain, while the back-end incorporates DEM-derived height and surface-normal factors into a pose graph, providing absolute surface constraints that mitigate long-term drift. We validate our approach using both simulated lunar traverse data generated in Unreal Engine and real Moon/Mars analog data collected from Mt. Etna. Results demonstrate that DEM anchoring consistently reduces absolute trajectory error compared to baseline SLAM methods, lowering drift in long-range navigation even in repetitive or visually aliased terrain.
### Title:
          Full Stack Navigation, Mapping, and Planning for the Lunar Autonomy Challenge
 - **Authors:** Adam Dai, Asta Wu, Keidai Iiyama, Guillem Casadesus Vila, Kaila Coimbra, Thomas Deng, Grace Gao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a modular, full-stack autonomy system for lunar surface navigation and mapping developed for the Lunar Autonomy Challenge. Operating in a GNSS-denied, visually challenging environment, our pipeline integrates semantic segmentation, stereo visual odometry, pose graph SLAM with loop closures, and layered planning and control. We leverage lightweight learning-based perception models for real-time segmentation and feature tracking and use a factor-graph backend to maintain globally consistent localization. High-level waypoint planning is designed to promote mapping coverage while encouraging frequent loop closures, and local motion planning uses arc sampling with geometric obstacle checks for efficient, reactive control. We evaluate our approach in the competition's high-fidelity lunar simulator, demonstrating centimeter-level localization accuracy, high-fidelity map generation, and strong repeatability across random seeds and rock distributions. Our solution achieved first place in the final competition evaluation.
### Title:
          ConfusionBench: An Expert-Validated Benchmark for Confusion Recognition and Localization in Educational Videos
 - **Authors:** Lu Dong, Xiao Wang, Mark Frank, Srirangaraj Setlur, Venu Govindaraju, Ifeoma Nwogu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recognizing and localizing student confusion from video is an important yet challenging problem in educational AI. Existing confusion datasets suffer from noisy labels, coarse temporal annotations, and limited expert validation, which hinder reliable fine-grained recognition and temporally grounded analysis. To address these limitations, we propose a practical multi-stage filtering pipeline that integrates two stages of model-assisted screening, researcher curation, and expert validation to build a higher-quality benchmark for confusion understanding. Based on this pipeline, we introduce ConfusionBench, a new benchmark for educational videos consisting of a balanced confusion recognition dataset and a video localization dataset. We further provide zero-shot baseline evaluations of a representative open-source model and a proprietary model on clip-level confusion recognition, long-video confusion localization tasks. Experimental results show that the proprietary model performs better overall but tends to over-predict transitional segments, while the open-source model is more conservative and more prone to missed detections. In addition, the proposed student confusion report visualization can support educational experts in making intervention decisions and adapting learning plans accordingly. All datasets and related materials will be made publicly available on our project page.
### Title:
          MedSAD-CLIP: Supervised CLIP with Token-Patch Cross-Attention for Medical Anomaly Detection and Segmentation
 - **Authors:** Thuy Truong Tran, Minh Kha Do, Phuc Nguyen Duy, Min Hun Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Medical anomaly detection (MAD) and segmentation play a critical role in assisting clinical diagnosis by identifying abnormal regions in medical images and localizing pathological regions. Recent CLIP-based studies are promising for anomaly detection in zero-/few-shot settings, and typically rely on global representations and weak supervision, often producing coarse localization and limited segmentation quality. In this work, we study supervised adaptation of CLIP for MAD under a realistic clinical setting where a limited yet meaningful amount of labeled abnormal data is available. Our model MedSAD-CLIP leverages fine-grained text-visual cues via the Token-Patch Cross-Attention(TPCA) to improve lesion localization while preserving the generalization capability of CLIP representations. Lightweight image adapters and learnable prompt tokens efficiently adapt the pretrained CLIP encoder to the medical domain while preserving its rich semantic alignment. Furthermore, a Margin-based image-text Contrastive Loss is designed to enhance global feature discrimination between normal and abnormal representations. Extensive experiments on four diverse benchmarks-Brain, Retina, Lung, and Breast datasets-demonstrate the effectiveness of our approach, achieving superior performance in both pixel-level segmentation and image-level classification over state-of-the-art methods. Our results highlight the potential of supervised CLIP adaptation as a unified and scalable paradigm for medical anomaly understanding. Code will be made available at this https URL
### Title:
          Grid Spatial Understanding: A Dataset for Textual Spatial Reasoning over Grids, Embodied Settings, and Coordinate Structures
 - **Authors:** Risham Sidhu, Julia Hockenmaier
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce GSU, a text-only grid dataset to evaluate the spatial reasoning capabilities of LLMs over 3 core tasks: navigation, object localization, and structure composition. By forgoing visual inputs, isolating spatial reasoning from perception, we show that while most models grasp basic grid concepts, they struggle with frames of reference relative to an embodied agent and identifying 3D shapes from coordinate lists. We also find that exposure to a visual modality does not provide a generalizable understanding of 3D space that VLMs are able to utilize for these tasks. Finally, we show that while the very latest frontier models can solve the provided tasks (though harder variants may still stump them), fully fine-tuning a small LM or LORA fine-tuning a small LLM show potential to match frontier model performance, suggesting an avenue for specialized embodied agents.
### Title:
          AdaZoom-GUI: Adaptive Zoom-based GUI Grounding with Instruction Refinement
 - **Authors:** Siqi Pei, Liang Tang, Tiaonan Duan, Long Chen, Shuxian Li, Kaer Huang, Yanzhe Jing, Yiqiang Yan, Bo Zhang, Chenghao Jiang, Borui Zhang, Jiwen Lu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 GUI grounding is a critical capability for vision-language models (VLMs) that enables automated interaction with graphical user interfaces by locating target elements from natural language instructions. However, grounding on GUI screenshots remains challenging due to high-resolution images, small UI elements, and ambiguous user instructions. In this work, we propose AdaZoom-GUI, an adaptive zoom-based GUI grounding framework that improves both localization accuracy and instruction understanding. Our approach introduces an instruction refinement module that rewrites natural language commands into explicit and detailed descriptions, allowing the grounding model to focus on precise element localization. In addition, we design a conditional zoom-in strategy that selectively performs a second-stage inference on predicted small elements, improving localization accuracy while avoiding unnecessary computation and context loss on simpler cases. To support this framework, we construct a high-quality GUI grounding dataset and train the grounding model using Group Relative Policy Optimization (GRPO), enabling the model to predict both click coordinates and element bounding boxes. Experiments on public benchmarks demonstrate that our method achieves state-of-the-art performance among models with comparable or even larger parameter sizes, highlighting its effectiveness for high-resolution GUI understanding and practical GUI agent deployment.
### Title:
          Bringing Network Coding into Multi-Robot Systems: Interplay Study for Autonomous Systems over Wireless Communications
 - **Authors:** Anil Zaher, Kiril Solovey, Alejandro Cohen
 - **Subjects:** Subjects:
Robotics (cs.RO); Multiagent Systems (cs.MA); Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Communication is a core enabler for multi-robot systems (MRS), providing the mechanism through which robots exchange state information, coordinate actions, and satisfy safety constraints. While many MRS autonomy algorithms assume reliable and timely message delivery, realistic wireless channels introduce delay, erasures, and ordering stalls that can degrade performance and compromise safety-critical decisions of the robot task. In this paper, we investigate how transport-layer reliability mechanisms that mitigate communication losses and delays shape the autonomy-communication loop. We show that conventional non-coded retransmission-based protocols introduce long delays that are misaligned with the timeliness requirements of MRS applications, and may render the received data irrelevant. As an alternative, we advocate for adaptive and causal network coding, which proactively injects coded redundancy to achieve the desired delay and throughput that enable relevant data delivery to the robotic task. Specifically, this method adapts to channel conditions between robots and causally tunes the communication rates via efficient algorithms. We present two case studies: cooperative localization under delayed and lossy inter-robot communication, and a safety-critical overtaking maneuver where timely vehicle-to-vehicle message availability determines whether an ego vehicle can abort to avoid a crash. Our results demonstrate that coding-based communication significantly reduces in-order delivery stalls, preserves estimation consistency under delay, and improves deadline reliability relative to retransmission-based transport. Overall, the study highlights the need to jointly design autonomy algorithms and communication mechanisms, and positions network coding as a principled tool for dependable multi-robot operation over wireless networks.
### Title:
          Prompt-Free Universal Region Proposal Network
 - **Authors:** Qihong Tang, Changhan Liu, Shaofeng Zhang, Wenbin Li, Qi Fan, Yang Gao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Identifying potential objects is critical for object recognition and analysis across various computer vision applications. Existing methods typically localize potential objects by relying on exemplar images, predefined categories, or textual descriptions. However, their reliance on image and text prompts often limits flexibility, restricting adaptability in real-world scenarios. In this paper, we introduce a novel Prompt-Free Universal Region Proposal Network (PF-RPN), which identifies potential objects without relying on external prompts. First, the Sparse Image-Aware Adapter (SIA) module performs initial localization of potential objects using a learnable query embedding dynamically updated with visual features. Next, the Cascade Self-Prompt (CSP) module identifies the remaining potential objects by leveraging the self-prompted learnable embedding, autonomously aggregating informative visual features in a cascading manner. Finally, the Centerness-Guided Query Selection (CG-QS) module facilitates the selection of high-quality query embeddings using a centerness scoring network. Our method can be optimized with limited data (e.g., 5% of MS COCO data) and applied directly to various object detection application domains for identifying potential objects without fine-tuning, such as underwater object detection, industrial defect detection, and remote sensing image object detection. Experimental results across 19 datasets validate the effectiveness of our method. Code is available at this https URL.
### Title:
          LoGSAM: Parameter-Efficient Cross-Modal Grounding for MRI Segmentation
 - **Authors:** Mohammad Robaitul Islam Bhuiyan, Sheethal Bhat, Melika Qahqaie, Tri-Thien Nguyen, Paula Andrea Pérez Toro, Tomas Arias Vergara, Andreas Maier
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Precise localization and delineation of brain tumors using Magnetic Resonance Imaging (MRI) are essential for planning therapy and guiding surgical decisions. However, most existing approaches rely on task-specific supervised models and are constrained by the limited availability of annotated data. To address this, we propose LoGSAM, a parameter-efficient, detection-driven framework that transforms radiologist dictation into text prompts for foundation-model-based localization and segmentation. Radiologist speech is first transcribed and translated using a pretrained Whisper ASR model, followed by negation-aware clinical NLP to extract tumor-specific textual prompts. These prompts guide text-conditioned tumor localization via a LoRA-adapted vision-language detection model, Grounding DINO (GDINO). The LoRA adaptation updates using 5% of the model parameters, thereby enabling computationally efficient domain adaptation while preserving pretrained cross-modal knowledge. The predicted bounding boxes are used as prompts for MedSAM to generate pixel-level tumor masks without any additional fine-tuning. Conditioning the frozen MedSAM on LoGSAM-derived priors yields a state-of-the-art dice score of 80.32% on BRISC 2025. In addition, we evaluate the full pipeline using German dictations from a board-certified radiologist on 12 unseen MRI scans, achieving 91.7% case-level accuracy. These results highlight the feasibility of constructing a modular, speech-to-segmentation pipeline by intelligently leveraging pretrained foundation models with minimal parameter updates.
### Title:
          DiffVP: Differential Visual Semantic Prompting for LLM-Based CT Report Generation
 - **Authors:** Yuhe Tian, Kun Zhang, Haoran Ma, Rui Yan, Yingtai Li, Rongsheng Wang, Shaohua Kevin Zhou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While large language models (LLMs) have advanced CT report generation, existing methods typically encode 3D volumes holistically, failing to distinguish informative cues from redundant anatomical background. Inspired by radiological cognitive subtraction, we propose Differential Visual Prompting (DiffVP), which conditions report generation on explicit, high-level semantic scan-to-reference differences rather than solely on absolute visual features. DiffVP employs a hierarchical difference extractor to capture complementary global and local semantic discrepancies into a shared latent space, along with a difference-to-prompt generator that transforms these signals into learnable visual prefix tokens for LLM conditioning. These difference prompts serve as structured conditioning signals that implicitly suppress invariant anatomy while amplifying diagnostically relevant visual evidence, thereby facilitating accurate report generation without explicit lesion localization. On two large-scale benchmarks, DiffVP consistently outperforms prior methods, improving the average BLEU-1-4 by +10.98 and +4.36, respectively, and further boosts clinical efficacy on RadGenome-ChestCT (F1 score 0.421). All codes will be released at this https URL.
### Title:
          PC-CrossDiff: Point-Cluster Dual-Level Cross-Modal Differential Attention for Unified 3D Referring and Segmentation
 - **Authors:** Wenbin Tan, Jiawen Lin, Fangyong Wang, Yuan Xie, Yong Xie, Yachao Zhang, Yanyun Qu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Visual Grounding (3DVG) aims to localize the referent of natural language referring expressions through two core tasks: Referring Expression Comprehension (3DREC) and Segmentation (3DRES). While existing methods achieve high accuracy in simple, single-object scenes, they suffer from severe performance degradation in complex, multi-object scenes that are common in real-world settings, hindering practical deployment. Existing methods face two key challenges in complex, multi-object scenes: inadequate parsing of implicit localization cues critical for disambiguating visually similar objects, and ineffective suppression of dynamic spatial interference from co-occurring objects, resulting in degraded grounding accuracy. To address these challenges, we propose PC-CrossDiff, a unified dual-task framework with a dual-level cross-modal differential attention architecture for 3DREC and 3DRES. Specifically, the framework introduces: (i) Point-Level Differential Attention (PLDA) modules that apply bidirectional differential attention between text and point clouds, adaptively extracting implicit localization cues via learnable weights to improve discriminative representation; (ii) Cluster-Level Differential Attention (CLDA) modules that establish a hierarchical attention mechanism to adaptively enhance localization-relevant spatial relationships while suppressing ambiguous or irrelevant spatial relations through a localization-aware differential attention block. Our method achieves state-of-the-art performance on the ScanRefer, NR3D, and SR3D benchmarks. Notably, on the Implicit subsets of ScanRefer, it improves the Overall@0.50 score by +10.16% for the 3DREC task, highlighting its strong ability to parse implicit spatial cues.
### Title:
          Huddle: Parallel Shape Assembly using Decentralized, Minimalistic Robots
 - **Authors:** Khai Yi Chin, Tingwei Meng, Zhe Chen, Daniel Bassett, Yuri Ivanov
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose a novel algorithm for forming arbitrarily shaped assemblies using decentralized robots. By relying on local interactions, the algorithm ensures there are no unreachable states or gaps in the assembly, which are global properties. The in-assembly robots attract passing-by robots into expanding the assembly via a simple implementation of signaling and alignment. Our approach is minimalistic, requiring only communication between attached, immediate neighbors. It is motion-agnostic and requires no pose localization, enabling asynchronous and order-independent assembly. We prove the algorithm's correctness and demonstrate its effectiveness in forming a 107-robot assembly.
### Title:
          FailureMem: A Failure-Aware Multimodal Framework for Autonomous Software Repair
 - **Authors:** Ruize Ma, Yilei Jiang, Shilin Zhang, Zheng Ma, Yi Feng, Vincent Ng, Zhi Wang, Xiangyu Yue, Chuanyi Li, Lewei Lu
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal Automated Program Repair (MAPR) extends traditional program repair by requiring models to jointly reason over source code, textual issue descriptions, and visual artifacts such as GUI screenshots. While recent LLM-based repair systems have shown promising results, existing approaches face several limitations: rigid workflow pipelines restrict exploration during debugging, visual reasoning is often performed over full-page screenshots without localized grounding, and failed repair attempts are rarely transformed into reusable knowledge. To address these challenges, we propose FailureMem, a multimodal repair framework that integrates three key mechanisms: a hybrid workflow-agent architecture that balances structured localization with flexible reasoning, active perception tools that enable region-level visual grounding, and a Failure Memory Bank that converts past repair attempts into reusable guidance. Experiments on SWE-bench Multimodal demonstrate FailureMem improves the resolved rate over GUIRepair by 3.7%.
### Title:
          CodeScout: An Effective Recipe for Reinforcement Learning of Code Search Agents
 - **Authors:** Lintang Sutawika, Aditya Bharat Soni, Bharath Sriraam R R, Apurva Gandhi, Taha Yassine, Sanidhya Vijayvargiya, Yuchen Li, Xuhui Zhou, Yilin Zhang, Leander Melroy Maben, Graham Neubig
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A prerequisite for coding agents to perform tasks on large repositories is code localization - the identification of relevant files, classes, and functions to work on. While repository-level code localization has been performed using embedding-based retrieval approaches such as vector search, recent work has focused on developing agents to localize relevant code either as a standalone precursor to or interleaved with performing actual work. Most prior methods on agentic code search equip the agent with complex, specialized tools, such as repository graphs derived from static analysis. In this paper, we demonstrate that, with an effective reinforcement learning recipe, a coding agent equipped with nothing more than a standard Unix terminal can be trained to achieve strong results. Our experiments on three benchmarks (SWE-Bench Verified, Pro, and Lite) reveal that our models consistently achieve superior or competitive performance over 2-18x larger base and post-trained LLMs and sometimes approach performance provided by closed models like Claude Sonnet, even when using specialized scaffolds. Our work particularly focuses on techniques for re-purposing existing coding agent environments for code search, reward design, and RL optimization. We release the resulting model family, CodeScout, along with all our code and data for the community to build upon.
### Title:
          Loc3R-VLM: Language-based Localization and 3D Reasoning with Vision-Language Models
 - **Authors:** Kevin Qu, Haozhe Qi, Mihai Dusmanu, Mahdi Rad, Rui Wang, Marc Pollefeys
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal Large Language Models (MLLMs) have made impressive progress in connecting vision and language, but they still struggle with spatial understanding and viewpoint-aware reasoning. Recent efforts aim to augment the input representations with geometric cues rather than explicitly teaching models to reason in 3D space. We introduce Loc3R-VLM, a framework that equips 2D Vision-Language Models with advanced 3D understanding capabilities from monocular video input. Inspired by human spatial cognition, Loc3R-VLM relies on two joint objectives: global layout reconstruction to build a holistic representation of the scene structure, and explicit situation modeling to anchor egocentric perspective. These objectives provide direct spatial supervision that grounds both perception and language in a 3D context. To ensure geometric consistency and metric-scale alignment, we leverage lightweight camera pose priors extracted from a pre-trained 3D foundation model. Loc3R-VLM achieves state-of-the-art performance in language-based localization and outperforms existing 2D- and video-based approaches on situated and general 3D question-answering benchmarks, demonstrating that our spatial supervision framework enables strong 3D understanding. Project page: this https URL
## Keyword: transformer
### Title:
          HoloByte: Continuous Hyperspherical Distillation for Tokenizer-Free Modeling
 - **Authors:** Vladimer Khasia
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sequence modeling universally relies on discrete subword tokenization to circumvent the $\mathcal{O}(N^2)$ computational intractability of native byte-level attention. However, this heuristic quantization imposes artificial morphological boundaries, enforces vocabulary dependence, and fractures the continuity of the optimization landscape. To resolve this dichotomy, we introduce \textbf{HoloByte}: a strictly tokenizer-free framework utilizing Continuous Hyperspherical Distillation. HoloByte partitions discrete byte sequences into fixed-capacity chunks and projects them into a continuous, strictly bounded hyperspherical manifold via an invertible, dimension-preserving orthogonal rotation operator. This spatial superposition allows a macroscopic transformer to operate exclusively on compressed continuous representations, formally reducing the exact attention time complexity from $\mathcal{O}(N^2D)$ to $\mathcal{O}\left( \frac{N^2}{W^2}D + ND^2 \right)$. A localized causal micro-decoder subsequently unbinds these representations to compute exact byte-level distributions. To govern this continuous trajectory, we propose a dual-objective formulation incorporating a mathematically precise Holographic Latent Mean Squared Error, which strictly bounds the gradient and guarantees asymptotic stability. Theoretically, we derive the minimal embedding dimension $D = \Omega(W \ln |\mathcal{V}|)$ required to ensure error-free discrete recovery from the continuous manifold. Empirically, under strictly matched parameter constraints, HoloByte is systematically outperforming a comparable discrete Byte-Pair Encoding (BPE) baseline. These results establish Continuous Hyperspherical Distillation as a mathematically rigorous and computationally tractable foundation for vocabulary-invariant sequence modeling. The code is available at this https URL
### Title:
          Integrating Inductive Biases in Transformers via Distillation for Financial Time Series Forecasting
 - **Authors:** Yu-Chen Den, Kuan-Yu Chen, Kendro Vincent, Darby Tien-Hao Chang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based models have been widely adopted for time-series forecasting due to their high representational capacity and architectural flexibility. However, many Transformer variants implicitly assume stationarity and stable temporal dynamics -- assumptions routinely violated in financial markets characterized by regime shifts and non-stationarity. Empirically, state-of-the-art time-series Transformers often underperform even vanilla Transformers on financial tasks, while simpler architectures with distinct inductive biases, such as CNNs and RNNs, can achieve stronger performance with substantially lower complexity. At the same time, no single inductive bias dominates across markets or regimes, suggesting that robust financial forecasting requires integrating complementary temporal priors. We propose TIPS (Transformer with Inductive Prior Synthesis), a knowledge distillation framework that synthesizes diverse inductive biases -- causality, locality, and periodicity -- within a unified Transformer. TIPS trains bias-specialized Transformer teachers via attention masking, then distills their knowledge into a single student model with regime-dependent alignment across inductive biases. Across four major equity markets, TIPS achieves state-of-the-art performance, outperforming strong ensemble baselines by 55%, 9%, and 16% in annual return, Sharpe ratio, and Calmar ratio, while requiring only 38% of the inference-time computation. Further analyses show that TIPS generates statistically significant excess returns beyond both vanilla Transformers and its teacher ensembles, and exhibits regime-dependent behavioral alignment with classical architectures during their profitable periods. These results highlight the importance of regime-dependent inductive bias utilization for robust generalization in non-stationary financial time series.
### Title:
          Transformers Can Learn Rules They've Never Seen: Proof of Computation Beyond Interpolation
 - **Authors:** Andy Gray
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A central question in the LLM debate is whether transformers can infer rules absent from training, or whether apparent generalisation reduces to similarity-based interpolation over observed examples. We test a strong interpolation-only hypothesis in two controlled settings: one where interpolation is ruled out by construction and proof, and one where success requires emitting intermediate symbolic derivations rather than only final answers. In Experiment 1, we use a cellular automaton with a pure XOR transition rule and remove specific local input patterns from training; since XOR is linearly inseparable, each held-out pattern's nearest neighbours have the opposite label, so similarity-based predictors fail on the held-out region. Yet a two-layer transformer recovers the rule (best 100%; 47/60 converged runs), and circuit extraction identifies XOR computation. Performance depends on multi-step constraint propagation: without unrolling, accuracy matches output bias (63.1%), while soft unrolling reaches 96.7%. In Experiment 2, we study symbolic operator chains over integers with one operator pair held out; the model must emit intermediate steps and a final answer in a proof-like format. Across all 49 holdout pairs, the transformer exceeds every interpolation baseline (mean 41.8%, up to 78.6%; mean KRR 4.3%; KNN and MLP score 0% on every pair), while removing intermediate-step supervision degrades performance. Together with a construction showing that a standard transformer block can implement exact local Boolean rules, these results provide an existence proof that transformers can learn rule structure not directly observed in training and express it explicitly, ruling out the strongest architectural form of interpolation-only accounts: that transformers cannot in principle discover and communicate unseen rules, while leaving open when such behaviour arises in large-scale language training.
### Title:
          DesertFormer: Transformer-Based Semantic Segmentation for Off-Road Desert Terrain Classification in Autonomous Navigation Systems
 - **Authors:** Yasaswini Chebolu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable terrain perception is a fundamental requirement for autonomous navigation in unstructured, off-road environments. Desert landscapes present unique challenges due to low chromatic contrast between terrain categories, extreme lighting variability, and sparse vegetation that defy the assumptions of standard road-scene segmentation models. We present DesertFormer, a semantic segmentation pipeline for off-road desert terrain analysis based on SegFormer B2 with a hierarchical Mix Transformer (MiT-B2) backbone. The system classifies terrain into ten ecologically meaningful categories -- Trees, Lush Bushes, Dry Grass, Dry Bushes, Ground Clutter, Flowers, Logs, Rocks, Landscape, and Sky -- enabling safety-aware path planning for ground robots and autonomous vehicles. Trained on a purpose-built dataset of 4,176 annotated off-road images at 512x512 resolution, DesertFormer achieves a mean Intersection-over-Union (mIoU) of 64.4% and pixel accuracy of 86.1%, representing a +24.2% absolute improvement over a DeepLabV3 MobileNetV2 baseline (41.0% mIoU). We further contribute a systematic failure analysis identifying the primary confusion patterns -- Ground Clutter to Landscape and Dry Grass to Landscape -- and propose class-weighted training and copy-paste augmentation for rare terrain categories. Code, checkpoints, and an interactive inference dashboard are released at this https URL.
### Title:
          Transformers are Bayesian Networks
 - **Authors:** Gregory Coppola
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers are the dominant architecture in AI, yet why they work remains poorly understood. This paper offers a precise answer: a transformer is a Bayesian network. We establish this in five ways. First, we prove that every sigmoid transformer with any weights implements weighted loopy belief propagation on its implicit factor graph. One layer is one round of BP. This holds for any weights -- trained, random, or constructed. Formally verified against standard mathematical axioms. Second, we give a constructive proof that a transformer can implement exact belief propagation on any declared knowledge base. On knowledge bases without circular dependencies this yields provably correct probability estimates at every node. Formally verified against standard mathematical axioms. Third, we prove uniqueness: a sigmoid transformer that produces exact posteriors necessarily has BP weights. There is no other path through the sigmoid architecture to exact posteriors. Formally verified against standard mathematical axioms. Fourth, we delineate the AND/OR boolean structure of the transformer layer: attention is AND, the FFN is OR, and their strict alternation is Pearl's gather/update algorithm exactly. Fifth, we confirm all formal results experimentally, corroborating the Bayesian network characterization in practice. We also establish the practical viability of loopy belief propagation despite the current lack of a theoretical convergence guarantee. We further prove that verifiable inference requires a finite concept space. Any finite verification procedure can distinguish at most finitely many concepts. Without grounding, correctness is not defined. Hallucination is not a bug that scaling can fix. It is the structural consequence of operating without concepts. Formally verified against standard mathematical axioms.
### Title:
          PRISM: Demystifying Retention and Interaction in Mid-Training
 - **Authors:** Bharat Runwal, Ashish Agrawal, Anurag Roy, Rameswar Panda
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present PRISM, a comprehensive empirical study of mid-training design choices for large language models. Through controlled experiments across seven base models spanning four families (Granite, LLaMA, Mistral, Nemotron-H), two architecture types (dense Transformer and attention-Mamba hybrid), and scales from 3B to 24B parameters, we show that mid-training on approximately 27B high-quality tokens yields consistent gains of +15 to +40 points on math, +5 to +12 points on code, and +6 to +13 points on science benchmarks while preserving general performance. The full PRISM to RL pipeline improves macro-average across six reasoning benchmarks from under 12 to 29-42 (a 3-4x improvement), whereas RL applied directly to most of the base models remains substantially less effective, with AIME scores near zero. Data composition matters most at mid-training, not RL: including science data during mid-training unlocks +17 to +28 point GPQA-Diamond gains during RL, while changing the RL mix produces less than 2 point differences. Mechanistically, mid-training densely restructures over 90% of model weights, while RL makes sparse, front-loaded refinements to approximately 5% of parameters. Representation analysis (CKA) confirms that RL consistently preserves mid-training's representational geometry (over 0.998 CKA) across architectures. Crucially, RL applies identical weight changes regardless of starting point, yet only succeeds on mid-trained models, consistent with mid-training placing the model in a configuration from which RL can effectively improve performance. Our results demonstrate that retention-aware mid-training is highly effective for reliable reasoning enhancement and provide practical guidance for designing robust mid-training pipelines.
### Title:
          Generalist Multimodal LLMs Gain Biometric Expertise via Human Salience
 - **Authors:** Jacob Piland, Byron Dowling, Christopher Sweet, Adam Czajka
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Iris presentation attack detection (PAD) is critical for secure biometric deployments, yet developing specialized models faces significant practical barriers: collecting data representing future unknown attacks is impossible, and collecting diverse-enough data, yet still limited in terms of its predictive power, is expensive. Additionally, sharing biometric data raises privacy concerns. Due to rapid emergence of new attack vectors demanding adaptable solutions, we thus investigate in this paper whether general-purpose multimodal large language models (MLLMs) can perform iris PAD when augmented with human expert knowledge, operating under strict privacy constraints that prohibit sending biometric data to public cloud MLLM services. Through analysis of vision encoder embeddings applied to our dataset, we demonstrate that pre-trained vision transformers in MLLMs inherently cluster many iris attack types despite never being explicitly trained for this task. However, where clustering shows overlap between attack classes, we find that structured prompts incorporating human salience (verbal descriptions from subjects identifying attack indicators) enable these models to resolve ambiguities. Testing on an IRB-restricted dataset of 224 iris images spanning seven attack types, using only university-approved services (Gemini 2.5 Pro) or locally-hosted models (e.g., Llama 3.2-Vision), we show that Gemini with expert-informed prompts outperforms both a specialized convolutional neural networks (CNN)-based baseline and human examiners, while the locally-deployable Llama achieves near-human performance. Our results establish that MLLMs deployable within institutional privacy constraints offer a viable path for iris PAD.
### Title:
          Gesture-Aware Pretraining and Token Fusion for 3D Hand Pose Estimation
 - **Authors:** Rui Hong, Jana Kosecka
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Estimating 3D hand pose from monocular RGB images is fundamental for applications in AR/VR, human-computer interaction, and sign language understanding. In this work we focus on a scenario where a discrete set of gesture labels is available and show that gesture semantics can serve as a powerful inductive bias for 3D pose estimation. We present a two-stage framework: gesture-aware pretraining that learns an informative embedding space using coarse and fine gesture labels from InterHand2.6M, followed by a per-joint token Transformer guided by gesture embeddings as intermediate representations for final regression of MANO hand parameters. Training is driven by a layered objective over parameters, joints, and structural constraints. Experiments on InterHand2.6M demonstrate that gesture-aware pretraining consistently improves single-hand accuracy over the state-of-the-art EANet baseline, and that the benefit transfers across architectures without any modification.
### Title:
          Motion-Adaptive Temporal Attention for Lightweight Video Generation with Stable Diffusion
 - **Authors:** Rui Hong, Shuxue Quan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a motion-adaptive temporal attention mechanism for parameter-efficient video generation built upon frozen Stable Diffusion models. Rather than treating all video content uniformly, our method dynamically adjusts temporal attention receptive fields based on estimated motion content: high-motion sequences attend locally across frames to preserve rapidly changing details, while low-motion sequences attend globally to enforce scene consistency. We inject lightweight temporal attention modules into all UNet transformer blocks via a cascaded strategy -- global attention in down-sampling and middle blocks for semantic stabilization, motion-adaptive attention in up-sampling blocks for fine-grained refinement. Combined with temporally correlated noise initialization and motion-aware gating, the system adds only 25.8M trainable parameters (2.9\% of the base UNet) while achieving competitive results on WebVid validation when trained on 100K videos. We demonstrate that the standard denoising objective alone provides sufficient implicit temporal regularization, outperforming approaches that add explicit temporal consistency losses. Our ablation studies reveal a clear trade-off between noise correlation and motion amplitude, providing a practical inference-time control for diverse generation behaviors.
### Title:
          The Phasor Transformer: Resolving Attention Bottlenecks on the Unit Circle
 - **Authors:** Dibakar Sigdel
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer models have redefined sequence learning, yet dot-product self-attention introduces a quadratic token-mixing bottleneck for long-context time-series. We introduce the \textbf{Phasor Transformer} block, a phase-native alternative representing sequence states on the unit-circle manifold $S^1$. Each block combines lightweight trainable phase-shifts with parameter-free Discrete Fourier Transform (DFT) token coupling, achieving global $\mathcal{O}(N\log N)$ mixing without explicit attention maps. Stacking these blocks defines the \textbf{Large Phasor Model (LPM)}. We validate LPM on autoregressive time-series prediction over synthetic multi-frequency benchmarks. Operating with a highly compact parameter budget, LPM learns stable global dynamics and achieves competitive forecasting behavior compared to conventional self-attention baselines. Our results establish an explicit efficiency-performance frontier, demonstrating that large-model scaling for time-series can emerge from geometry-constrained phase computation with deterministic global coupling, offering a practical path toward scalable temporal modeling in oscillatory domains.
### Title:
          Baguan-TS: A Sequence-Native In-Context Learning Model for Time Series Forecasting with Covariates
 - **Authors:** Linxiao Yang, Xue Jiang, Gezheng Xu, Tian Zhou, Min Yang, ZhaoYang Zhu, Linyuan Geng, Zhipeng Zeng, Qiming Chen, Xinyue Gu, Rong Jin, Liang Sun
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers enable in-context learning (ICL) for rapid, gradient-free adaptation in time series forecasting, yet most ICL-style approaches rely on tabularized, hand-crafted features, while end-to-end sequence models lack inference-time adaptation. We bridge this gap with a unified framework, Baguan-TS, which integrates the raw-sequence representation learning with ICL, instantiated by a 3D Transformer that attends jointly over temporal, variable, and context axes. To make this high-capacity model practical, we tackle two key hurdles: (i) calibration and training stability, improved with a feature-agnostic, target-space retrieval-based local calibration; and (ii) output oversmoothing, mitigated via context-overfitting strategy. On public benchmark with covariates, Baguan-TS consistently outperforms established baselines, achieving the highest win rate and significant reductions in both point and probabilistic forecasting metrics. Further evaluations across diverse real-world energy datasets demonstrate its robustness, yielding substantial improvements.
### Title:
          Revisiting Cross-Attention Mechanisms: Leveraging Beneficial Noise for Domain-Adaptive Learning
 - **Authors:** Zelin Zang, Yehui Yang, Fei Wang, Liangyu Li, Baigui Sun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unsupervised Domain Adaptation (UDA) seeks to transfer knowledge from a labeled source domain to an unlabeled target domain but often suffers from severe domain and scale gaps that degrade performance. Existing cross-attention-based transformers can align features across domains, yet they struggle to preserve content semantics under large appearance and scale variations. To explicitly address these challenges, we introduce the concept of beneficial noise, which regularizes cross-attention by injecting controlled perturbations, encouraging the model to ignore style distractions and focus on content. We propose the Domain-Adaptive Cross-Scale Matching (DACSM) framework, which consists of a Domain-Adaptive Transformer (DAT) for disentangling domain-shared content from domain-specific style, and a Cross-Scale Matching (CSM) module that adaptively aligns features across multiple resolutions. DAT incorporates beneficial noise into cross-attention, enabling progressive domain translation with enhanced robustness, yielding content-consistent and style-invariant representations. Meanwhile, CSM ensures semantic consistency under scale changes. Extensive experiments on VisDA-2017, Office-Home, and DomainNet demonstrate that DACSM achieves state-of-the-art performance, with up to +2.3% improvement over CDTrans on VisDA-2017. Notably, DACSM achieves a +5.9% gain on the challenging "truck" class of VisDA, evidencing the strength of beneficial noise in handling scale discrepancies. These results highlight the effectiveness of combining domain translation, beneficial-noise-enhanced attention, and scale-aware alignment for robust cross-domain representation learning.
### Title:
          Humans and transformer LMs: Abstraction drives language learning
 - **Authors:** Jasper Jian, Christopher D. Manning
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Categorization is a core component of human linguistic competence. We investigate how a transformer-based language model (LM) learns linguistic categories by comparing its behaviour over the course of training to behaviours which characterize abstract feature-based and concrete exemplar-based accounts of human language acquisition. We investigate how lexical semantic and syntactic categories emerge using novel divergence-based metrics that track learning trajectories using next-token distributions. In experiments with GPT-2 small, we find that (i) when a construction is learned, abstract class-level behaviour is evident at earlier steps than lexical item-specific behaviour, and (ii) that different linguistic behaviours emerge abruptly in sequence at different points in training, revealing that abstraction plays a key role in how LMs learn. This result informs the models of human language acquisition that LMs may serve as an existence proof for.
### Title:
          A Tutorial on Learning-Based Radio Map Construction: Data, Paradigms, and Physics-Awarenes
 - **Authors:** Xiucheng Wang, Yuhao Pan, Nan Cheng
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The integration of artificial intelligence into next-generation wireless networks necessitates the accurate construction of radio maps (RMs) as a foundational prerequisite for electromagnetic digital twins. A RM provides the digital representation of the wireless propagation environment, mapping complex geographical and topological boundary conditions to critical spatial-spectral metrics that range from received signal strength to full channel state information matrices. This tutorial presents a comprehensive survey of learning-based RM construction, systematically addressing three intertwined dimensions: data, paradigms, and physics-awareness. From the data perspective, we review physical measurement campaigns, ray tracing simulation engines, and publicly available benchmark datasets, identifying their respective strengths and fundamental limitations. From the paradigm perspective, we establish a core taxonomy that categorizes RM construction into source-aware forward prediction and source-agnostic inverse reconstruction, and examine five principal neural architecture families spanning convolutional neural networks, vision transformers, graph neural networks, generative adversarial networks, and diffusion models. We further survey optics-inspired methods adapted from neural radiance fields and 3D Gaussian splatting for continuous wireless radiation field modeling. From the physics-awareness perspective, we introduce a three-level integration framework encompassing data-level feature engineering, loss-level partial differential equation regularization, and architecture-level structural isomorphism. Open challenges including foundation model development, physical hallucination detection, and amortized inference for real-time deployment are discussed to outline future research directions.
### Title:
          Detecting the Machine: A Comprehensive Benchmark of AI-Generated Text Detectors Across Architectures, Domains, and Adversarial Conditions
 - **Authors:** Madhav S. Baidya, S. S. Baidya, Chirag Chawla
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid proliferation of large language models (LLMs) has created an urgent need for robust and generalizable detectors of machine-generated text. Existing benchmarks typically evaluate a single detector on a single dataset under ideal conditions, leaving open questions about cross-domain transfer, cross-LLM generalization, and adversarial robustness. We present a comprehensive benchmark evaluating diverse detection approaches across two corpora: HC3 (23,363 human-ChatGPT pairs) and ELI5 (15,000 human-Mistral-7B pairs). Methods include classical classifiers, fine-tuned transformer encoders (BERT, RoBERTa, ELECTRA, DistilBERT, DeBERTa-v3), a CNN, an XGBoost stylometric model, perplexity-based detectors, and LLM-as-detector prompting. Results show that transformer models achieve near-perfect in-distribution performance but degrade under domain shift. The XGBoost stylometric model matches performance while remaining interpretable. LLM-based detectors underperform and are affected by generator-detector identity bias. Perplexity-based methods exhibit polarity inversion, with modern LLM outputs showing lower perplexity than human text, but remain effective when corrected. No method generalizes robustly across domains and LLM sources.
### Title:
          Anisotropic Permeability Tensor Prediction from Porous Media Microstructure via Physics-Informed Progressive Transfer Learning with Hybrid CNN-Transformer
 - **Authors:** Mohammad Nooraiepour
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Fluid Dynamics (physics.flu-dyn)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate prediction of permeability tensors from pore-scale microstructure images is essential for subsurface flow modeling, yet direct numerical simulation requires hours per sample, fundamentally limiting large-scale uncertainty quantification and reservoir optimization workflows. A physics-informed deep learning framework is presented that resolves this bottleneck by combining a MaxViT hybrid CNN-Transformer architecture with progressive transfer learning and differentiable physical constraints. MaxViT's multi-axis attention mechanism simultaneously resolves grain-scale pore-throat geometry via block-local operations and REV-scale connectivity statistics through grid-global operations, providing the spatial hierarchy that permeability tensor prediction physically requires. Training on 20000 synthetic porous media samples spanning three orders of magnitude in permeability, a three-phase progressive curriculum advances from an ImageNet-pretrained baseline with D4-equivariant augmentation and tensor transformation, through component-weighted loss prioritizing off-diagonal coupling, to frozen-backbone transfer learning with porosity conditioning via Feature-wise Linear Modulation (FiLM). Onsager reciprocity and positive definiteness are enforced via differentiable penalty terms. On a held-out test set of 4000 samples, the framework achieves variance-weighted R2 = 0.9960 (R2_Kxx = 0.9967, R2_Kxy = 0.9758), a 33% reduction in unexplained variance over the supervised baseline. The results offer three transferable principles for physics-informed scientific machine learning: large-scale visual pretraining transfers effectively across domain boundaries; physical constraints are most robustly integrated as differentiable architectural components; and progressive training guided by diagnostic failure-mode analysis enables unambiguous attribution of performance gains across methodological stages.
### Title:
          ProGVC: Progressive-based Generative Video Compression via Auto-Regressive Context Modeling
 - **Authors:** Daowen Li, Ruixiao Dong, Ying Chen, Kai Li, Ding Ding, Li Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Perceptual video compression leverages generative priors to reconstruct realistic textures and motions at low bitrates. However, existing perceptual codecs often lack native support for variable bitrate and progressive delivery, and their generative modules are weakly coupled with entropy coding, limiting bitrate reduction. Inspired by the next-scale prediction in the Visual Auto-Regressive (VAR) models, we propose ProGVC, a Progressive-based Generative Video Compression framework that unifies progressive transmission, efficient entropy coding, and detail synthesis within a single codec. ProGVC encodes videos into hierarchical multi-scale residual token maps, enabling flexible rate adaptation by transmitting a coarse-to-fine subset of scales in a progressive manner. A Transformer-based multi-scale autoregressive context model estimates token probabilities, utilized both for efficient entropy coding of the transmitted tokens and for predicting truncated fine-scale tokens at the decoder to restore perceptual details. Extensive experiments demonstrate that as a new coding paradigm, ProGVC delivers promising perceptual compression performance at low bitrates while offering practical scalability at the same time.
### Title:
          KA2L: A Knowledge-Aware Active Learning Framework for LLMs
 - **Authors:** Haoxuan Yin, Bojian Liu, Chen Tang, Yangfan Wang, Lian Yan, Jingchi Jiang
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fine-tuning large language models (LLMs) with high-quality knowledge has been shown to enhance their performance effectively. However, there is a paucity of research on the depth of domain-specific knowledge comprehension by LLMs and the application of targeted active learning to improve their expertise. To address this gap, we introduce the Knowledge-Aware Active Learning (KA2L) framework. This framework assesses LLMs' mastery of specific knowledge points to aid in constructing unanswerable or unknowable questions through latent space analysis. This active learning strategy enhances training efficiency by focusing on knowledge the model has yet to master, thereby minimizing redundancy in learning already acquired information. This study innovatively employs a knowledge distribution probing technique to examine the hidden states of specific Transformer layers and identify the distribution of known and unknown knowledge within the LLM. Additionally, a hidden-state decoding method is proposed to generate numerous unknown questions in natural language from the latent knowledge space. In our experiments, we selected nine open-source LLMs to validate the effectiveness of the proposed framework. Results indicate that KA2L not only significantly reduces 50% annotation and computation costs across two open-domain and one vertical-domain dataset but also achieves better performance, offering valuable insights into active learning strategies for LLMs. The code is available at this https URL.
### Title:
          PanoVGGT: Feed-Forward 3D Reconstruction from Panoramic Imagery
 - **Authors:** Yijing Guo, Mengjun Chao, Luo Wang, Tianyang Zhao, Haizhao Dai, Yingliang Zhang, Jingyi Yu, Yujiao Shi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Panoramic imagery offers a full 360° field of view and is increasingly common in consumer devices. However, it introduces non-pinhole distortions that challenge joint pose estimation and 3D reconstruction. Existing feed-forward models, built for perspective cameras, generalize poorly to this setting. We propose PanoVGGT, a permutation-equivariant Transformer framework that jointly predicts camera poses, depth maps, and 3D point clouds from one or multiple panoramas in a single forward pass. The model incorporates spherical-aware positional embeddings and a panorama-specific three-axis SO(3) rotation augmentation, enabling effective geometric reasoning in the spherical domain. To resolve inherent global-frame ambiguity, we further introduce a stochastic anchoring strategy during training. In addition, we contribute PanoCity, a large-scale outdoor panoramic dataset with dense depth and 6-DoF pose annotations. Extensive experiments on PanoCity and standard benchmarks demonstrate that PanoVGGT achieves competitive accuracy, strong robustness, and improved cross-domain generalization. Code and dataset will be released.
### Title:
          Attention Sinks Induce Gradient Sinks
 - **Authors:** Yihong Chen, Quanming Yao
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Attention sinks and massive activations are recurring and closely related phenomena in Transformer models. Existing studies have largely focused on the forward pass, making it unclear whether their connection is direct or mediated by a training-time mechanism. We study this question from the perspective of backpropagation. Empirically and theoretically, we show that under causal mask, attention sinks can induce pronounced gradient concentration, which we term gradient sinks. Furthermore, in pre-norm architectures with RMSNorm, massive activations can be understood as an adaptive response to this localized gradient pressure during training. To test this hypothesis, we introduce V-scale, a modification that adjusts value-path backpropagated gradients. In pretrained V-scale models, attention sinks are preserved whereas massive activations are suppressed. These results support the interpretation that gradient sink is a key training-time mediator linking attention sinks and massive activations.
### Title:
          Enabling RISC-V Vector Code Generation in MLIR through Custom xDSL Lowerings
 - **Authors:** Jie Lei, Héctor Martínez, Adrián Castelló
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The growing adoption of RISC-V in high-performance and scientific computing has increased the need for performance-portable code targeting the RISC-V Vector (RVV) extension. However, current compiler infrastructures provide limited end-to-end support for generating optimized RVV code from high-level representations to low-level implementations. In particular, existing MLIR distributions lack practical lowering paths that map high-level abstractions to RVV intrinsics, limiting their applicability for production-ready RISC-V kernels. This paper presents a compilation approach that combines MLIR with xDSL to bridge the missing lowering stages required for RVV code generation. Using custom intermediate representations and transformation passes implemented in xDSL, we systematically translate high-level operations into specialized, hardware-aware C code invoking RVV intrinsics. The resulting kernels are emitted as portable C functions that can be directly integrated into existing applications, enabling incremental adoption without modifying surrounding software stacks. We demonstrate the approach on the General Matrix Multiplication (GEMM) kernel and evaluate the generated micro-kernels on two real RISC-V platforms, the K230 and the BananaPi F3, comparing against OpenBLAS for both square-matrix benchmarks and transformer-based workloads derived from the BERT-Large model. When integrated into a matrix multiplication kernel, the proposed approach consistently outperforms OpenBLAS, reaching up to 12.2 GFLOPS compared to the baseline's 5.1 GFLOPS and providing performance improvements between 10--35\% across the evaluated workloads. These results demonstrate that combining MLIR with xDSL provides a practical pathway to portable, optimized code generation for RISC-V platforms.
### Title:
          Dropout Robustness and Cognitive Profiling of Transformer Models via Stochastic Inference
 - **Authors:** Antônio Junior Alves Caiado, Michael Hahsler
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based language models are widely deployed for reasoning, yet their behavior under inference-time stochasticity remains underexplored. While dropout is common during training, its inference-time effects via Monte Carlo sampling lack systematic evaluation across architectures, limiting understanding of model reliability in uncertainty-aware applications. This work analyzes dropout-induced variability across 19 transformer models using MC Dropout with 100 stochastic forward passes per sample. Dropout robustness is defined as maintaining high accuracy and stable predictions under stochastic inference, measured by standard deviation of per-run accuracies. A cognitive decomposition framework disentangles performance into memory and reasoning components. Experiments span five dropout configurations yielding 95 unique evaluations on 1,000 samples. Results reveal substantial architectural variation. Smaller models demonstrate perfect prediction stability while medium-sized models exhibit notable volatility. Mid-sized models achieve the best overall performance; larger models excel at memory tasks. Critically, 53% of models suffer severe accuracy degradation under baseline MC Dropout, with task-specialized models losing up to 24 percentage points, indicating unsuitability for uncertainty quantification in these architectures. Asymmetric effects emerge: high dropout reduces memory accuracy by 27 percentage points while reasoning degrades only 1 point, suggesting memory tasks rely on stable representations that dropout disrupts. 84% of models demonstrate memory-biased performance. This provides the first comprehensive MC Dropout benchmark for transformers, revealing dropout robustness is architecture-dependent and uncorrelated with scale. The cognitive profiling framework offers actionable guidance for model selection in uncertainty-aware applications.
### Title:
          Steering Video Diffusion Transformers with Massive Activations
 - **Authors:** Xianhang Cheng, Yujian Zheng, Zhenyu Xie, Tingting Liao, Hao Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite rapid progress in video diffusion transformers, how their internal model signals can be leveraged with minimal overhead to enhance video generation quality remains underexplored. In this work, we study the role of Massive Activations (MAs), which are rare, high-magnitude hidden state spikes in video diffusion transformers. We observed that MAs emerge consistently across all visual tokens, with a clear magnitude hierarchy: first-frame tokens exhibit the largest MA magnitudes, latent-frame boundary tokens (the head and tail portions of each temporal chunk in the latent space) show elevated but slightly lower MA magnitudes than the first frame, and interior tokens within each latent frame remain elevated, yet are comparatively moderate in magnitude. This structured pattern suggests that the model implicitly prioritizes token positions aligned with the temporal chunking in the latent space. Based on this observation, we propose Structured Activation Steering (STAS), a training-free self-guidance-like method that steers MA values at first-frame and boundary tokens toward a scaled global maximum reference magnitude. STAS achieves consistent improvements in terms of video quality and temporal coherence across different text-to-video models, while introducing negligible computational overhead.
### Title:
          LaDe: Unified Multi-Layered Graphic Media Generation and Decomposition
 - **Authors:** Vlad-Constantin Lungu-Stan, Ionut Mironica, Mariana-Iuliana Georgescu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Media design layer generation enables the creation of fully editable, layered design documents such as posters, flyers, and logos using only natural language prompts. Existing methods either restrict outputs to a fixed number of layers or require each layer to contain only spatially continuous regions, causing the layer count to scale linearly with design complexity. We propose LaDe (Layered Media Design), a latent diffusion framework that generates a flexible number of semantically meaningful layers. LaDe combines three components: an LLM-based prompt expander that transforms a short user intent into structured per-layer descriptions that guide the generation, a Latent Diffusion Transformer with a 4D RoPE positional encoding mechanism that jointly generates the full media design and its constituent RGBA layers, and an RGBA VAE that decodes each layer with full alpha-channel support. By conditioning on layer samples during training, our unified framework supports three tasks: text-to-image generation, text-to-layers media design generation, and media design decomposition. We compare LaDe to Qwen-Image-Layered on text-to-layers and image-to-layers tasks on the Crello test set. LaDe outperforms Qwen-Image-Layered in text-to-layers generation by improving text-to-layer alignment, as validated by two VLM-as-a-judge evaluators (GPT-4o mini and Qwen3-VL).
### Title:
          Beyond Muon: MUD (MomentUm Decorrelation) for Faster Transformer Training
 - **Authors:** Ben S. Southworth, Stephen Thomas
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Numerical Analysis (math.NA); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Orthogonalized-momentum optimizers such as Muon improve transformer training by approximately whitening/orthogonalizing matrix-valued momentum updates via a short polar-decomposition iteration. However, polar-factor approximations typically require multiple large matrix multiplications, and the resulting overhead can be substantial and hardware-dependent. We introduce MUD (MomentUm Decorrelation), a complementary whitening approach that replaces Muon's polar update with a triangular (Cholesky-like) whitening surrogate inspired by classical Gram--Schmidt and Gauss-Seidel ideas. We show that row-orthonormal matrices are fixed points of the MUD map, relate the inner step to symmetric Gauss-Seidel preconditioning of the Gram matrix, and prove quadratic local convergence near the fixed point. In terms of time-to-perplexity, MUD yields consistent 10-50\% wall-clock improvements over tuned AdamW and Muon in time-to-perplexity, typically converging slightly slower per step than Muon but with substantially lower optimizer overhead -- relative to Muon, MUD improves peak tokens/s by roughly $1.3-2.6\times$ across most settings and up to nearly $3\times$ on GPT-2 large on an A100. We also demonstrate training a ESM-2 150M protein language model, where MUD matches Muon-level validation perplexity in significantly less wall-clock time.
### Title:
          GMT: Goal-Conditioned Multimodal Transformer for 6-DOF Object Trajectory Synthesis in 3D Scenes
 - **Authors:** Huajian Zeng, Abhishek Saroha, Daniel Cremers, Xi Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Synthesizing controllable 6-DOF object manipulation trajectories in 3D environments is essential for enabling robots to interact with complex scenes, yet remains challenging due to the need for accurate spatial reasoning, physical feasibility, and multimodal scene understanding. Existing approaches often rely on 2D or partial 3D representations, limiting their ability to capture full scene geometry and constraining trajectory precision. We present GMT, a multimodal transformer framework that generates realistic and goal-directed object trajectories by jointly leveraging 3D bounding box geometry, point cloud context, semantic object categories, and target end poses. The model represents trajectories as continuous 6-DOF pose sequences and employs a tailored conditioning strategy that fuses geometric, semantic, contextual, and goaloriented information. Extensive experiments on synthetic and real-world benchmarks demonstrate that GMT outperforms state-of-the-art human motion and human-object interaction baselines, such as CHOIS and GIMO, achieving substantial gains in spatial accuracy and orientation control. Our method establishes a new benchmark for learningbased manipulation planning and shows strong generalization to diverse objects and cluttered 3D environments. Project page: https://huajian- this http URL. io/projects/gmt/.
### Title:
          Unified Spatio-Temporal Token Scoring for Efficient Video VLMs
 - **Authors:** Jianrui Zhang, Yue Yang, Rohun Tripathi, Winson Han, Ranjay Krishna, Christopher Clark, Yong Jae Lee, Sangho Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Token pruning is essential for enhancing the computational efficiency of vision-language models (VLMs), particularly for video-based tasks where temporal redundancy is prevalent. Prior approaches typically prune tokens either (1) within the vision transformer (ViT) exclusively for unimodal perception tasks such as action recognition and object segmentation, without adapting to downstream vision-language tasks; or (2) only within the LLM while leaving the ViT output intact, often requiring complex text-conditioned token selection mechanisms. In this paper, we introduce Spatio-Temporal Token Scoring (STTS), a simple and lightweight module that prunes vision tokens across both the ViT and the LLM without text conditioning or token merging, and is fully compatible with end-to-end training. By learning how to score temporally via an auxiliary loss and spatially via LLM downstream gradients, aided by our efficient packing algorithm, STTS prunes 50% of vision tokens throughout the entire architecture, resulting in a 62% improvement in efficiency during both training and inference with only a 0.7% drop in average performance across 13 short and long video QA tasks. Efficiency gains increase with more sampled frames per video. Applying test-time scaling for long-video QA further yields performance gains of 0.5-1% compared to the baseline. Overall, STTS represents a novel, simple yet effective technique for unified, architecture-wide vision token pruning.
## Keyword: autonomous driving
### Title:
          Joint Optimization of Storage and Loading for High-Performance 3D Point Cloud Data Processing
 - **Authors:** Ke Wang, Yanfei Cao, Xiangzhi Tao, Naijie Gu, Jun Yu, Zhengdong Wang, Shouyang Dong, Fan Yu, Cong Wang, Yang Luo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the rapid development of computer vision and deep learning, significant advancements have been made in 3D vision, partic- ularly in autonomous driving, robotic perception, and augmented reality. 3D point cloud data, as a crucial representation of 3D information, has gained widespread attention. However, the vast scale and complexity of point cloud data present significant chal- lenges for loading and processing and traditional algorithms struggle to handle large-scale this http URL diversity of storage formats for point cloud datasets (e.g., PLY, XYZ, BIN) adds complexity to data handling and results in inefficiencies in data preparation. Al- though binary formats like BIN and NPY have been used to speed up data access, they still do not fully address the time-consuming data loading and processing phase. To overcome these challenges, we propose the .PcRecord format, a unified data storage solution designed to reduce the storage occupation and accelerate the processing of point cloud data. We also introduce a high-performance data processing pipeline equipped with multiple modules. By leveraging a multi-stage parallel pipeline architecture, our system optimizes the use of computational resources, significantly improving processing speed and efficiency. This paper details the im- plementation of this system and demonstrates its effectiveness in addressing the challenges of handling large-scale point cloud this http URL average, our system achieves performance improvements of 6.61x (ModelNet40), 2.69x (S3DIS), 2.23x (ShapeNet), 3.09x (Kitti), 8.07x (SUN RGB-D), and 5.67x (ScanNet) with GPU and 6.9x, 1.88x, 1.29x, 2.28x, 25.4x, and 19.3x with Ascend.
### Title:
          Topology-Preserving Deep Joint Source-Channel Coding for Semantic Communication
 - **Authors:** Omar Erak, Omar Alhussein, Fang Fang, Sami Muhaidat
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Information Theory (cs.IT); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many wireless vision applications, such as autonomous driving, require preservation of global structural information rather than only per-pixel fidelity. However, existing Deep joint source-channel coding (DeepJSCC) schemes mainly optimize pixel-wise losses and provide no explicit protection of connectivity or topology. This letter proposes TopoJSCC, a topology-aware DeepJSCC framework that integrates persistent-homology regularizers to end-to-end training. Specifically, we enforce topological consistency by penalizing Wasserstein distances between cubical persistence diagrams of original and reconstructed images, and between Vietoris--Rips persistence of latent features before and after the channel to promote a robust latent manifold. TopoJSCC is based on end-to-end learning and requires no side information. Experiments show improved topology preservation and peak signal-to-noise ratio (PSNR) in low signal-to-noise ratio (SNR) and bandwidth-ratio regimes.
### Title:
          VisionNVS: Self-Supervised Inpainting for Novel View Synthesis under the Virtual-Shift Paradigm
 - **Authors:** Hongbo Lu, Liang Yao, Chenghao He, Fan Liu, Wenlong Liao, Tao He, Pai Peng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A fundamental bottleneck in Novel View Synthesis (NVS) for autonomous driving is the inherent supervision gap on novel trajectories: models are tasked with synthesizing unseen views during inference, yet lack ground truth images for these shifted poses during training. In this paper, we propose VisionNVS, a camera-only framework that fundamentally reformulates view synthesis from an ill-posed extrapolation problem into a self-supervised inpainting task. By introducing a ``Virtual-Shift'' strategy, we use monocular depth proxies to simulate occlusion patterns and map them onto the original view. This paradigm shift allows the use of raw, recorded images as pixel-perfect supervision, effectively eliminating the domain gap inherent in previous approaches. Furthermore, we address spatial consistency through a Pseudo-3D Seam Synthesis strategy, which integrates visual data from adjacent cameras during training to explicitly model real-world photometric discrepancies and calibration errors. Experiments demonstrate that VisionNVS achieves superior geometric fidelity and visual quality compared to LiDAR-dependent baselines, offering a robust solution for scalable driving simulation.
### Title:
          Physics-informed Deep Mixture-of-Koopmans Vehicle Dynamics Model with Dual-branch Encoder for Distributed Electric-drive Trucks
 - **Authors:** Jinyu Miao, Pu Zhang, Rujun Yan, Yifei He, Bowei Zhang, Zheng Fu, Ke Wang, Qi Song, Kun Jiang, Mengmeng Yang, Diange Yang
 - **Subjects:** Subjects:
Robotics (cs.RO); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Advanced autonomous driving systems require accurate vehicle dynamics modeling. However, identifying a precise dynamics model remains challenging due to strong nonlinearities and the coupled longitudinal and lateral dynamic characteristics. Previous research has employed physics-based analytical models or neural networks to construct vehicle dynamics representations. Nevertheless, these approaches often struggle to simultaneously achieve satisfactory performance in terms of system identification efficiency, modeling accuracy, and compatibility with linear control strategies. In this paper, we propose a fully data-driven dynamics modeling method tailored for complex distributed electric-drive trucks (DETs), leveraging Koopman operator theory to represent highly nonlinear dynamics in a lifted linear embedding space. To achieve high-precision modeling, we first propose a novel dual-branch encoder which encodes dynamic states and provides a powerful basis for the proposed Koopman-based methods entitled KODE. A physics-informed supervision mechanism, grounded in the geometric consistency of temporal vehicle motion, is incorporated into the training process to facilitate effective learning of both the encoder and the Koopman operator. Furthermore, to accommodate the diverse driving patterns of DETs, we extend the vanilla Koopman operator to a mixture-of-Koopman operator framework, enhancing modeling capability. Simulations conducted in a high-fidelity TruckSim environment and real-world experiments demonstrate that the proposed approach achieves state-of-the-art performance in long-term dynamics state estimation.
### Title:
          Hierarchical Decision-Making under Uncertainty: A Hybrid MDP and Chance-Constrained MPC Approach
 - **Authors:** Siyuan Li, Chengyuan Liu, Wen-Hua Chen
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a hierarchical decision-making framework for autonomous systems operating under uncertainty, demonstrated through autonomous driving as a representative application. Surrounding agents are modeled using Hybrid Markov Decision Processes (HMDPs) that jointly capture maneuver-level and dynamic-level uncertainties, enabling the multi-modal environmental prediction. The ego agent is modeled using a separate HMDP and integrated into a Model Predictive Control (MPC) framework that unifies maneuver selection with dynamic feasibility within a single optimization. A set of joint chance constraints serves as the bridge between environmental prediction and optimization, incorporating multi-modal environment predictions into the MPC formulation and ensuring safety across all plausible interaction scenarios. The proposed framework provides theoretical guarantees on recursive feasibility and asymptotic stability, and its benefits in terms of safety and efficiency are validated through comprehensive evaluations in highway and urban environments, together with comparisons against a rule-based baseline.
### Title:
          From Virtual Environments to Real-World Trials: Emerging Trends in Autonomous Driving
 - **Authors:** A. Humnabadkar, A. Sikdar, B. Cave, H. Zhang, N. Bessis, A. Behera
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving technologies have achieved significant advances in recent years, yet their real-world deployment remains constrained by data scarcity, safety requirements, and the need for generalization across diverse environments. In response, synthetic data and virtual environments have emerged as powerful enablers, offering scalable, controllable, and richly annotated scenarios for training and evaluation. This survey presents a comprehensive review of recent developments at the intersection of autonomous driving, simulation technologies, and synthetic datasets. We organize the landscape across three core dimensions: (i) the use of synthetic data for perception and planning, (ii) digital twin-based simulation for system validation, and (iii) domain adaptation strategies bridging synthetic and real-world data. We also highlight the role of vision-language models and simulation realism in enhancing scene understanding and generalization. A detailed taxonomy of datasets, tools, and simulation platforms is provided, alongside an analysis of trends in benchmark design. Finally, we discuss critical challenges and open research directions, including Sim2Real transfer, scalable safety validation, cooperative autonomy, and simulation-driven policy learning, that must be addressed to accelerate the path toward safe, generalizable, and globally deployable autonomous driving systems.
### Title:
          AdaRadar: Rate Adaptive Spectral Compression for Radar-based Perception
 - **Authors:** Jinho Park, Se Young Chun, Mingoo Seok
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Radar is a critical perception modality in autonomous driving systems due to its all-weather characteristics and ability to measure range and Doppler velocity. However, the sheer volume of high-dimensional raw radar data saturates the communication link to the computing engine (e.g., an NPU), which is often a low-bandwidth interface with data rate provisioned only for a few low-resolution range-Doppler frames. A generalized codec for utilizing high-dimensional radar data is notably absent, while existing image-domain approaches are unsuitable, as they typically operate at fixed compression ratios and fail to adapt to varying or adversarial conditions. In light of this, we propose radar data compression with adaptive feedback. It dynamically adjusts the compression ratio by performing gradient descent from the proxy gradient of detection confidence with respect to the compression rate. We employ a zeroth-order gradient approximation as it enables gradient computation even with non-differentiable core operations--pruning and quantization. This also avoids transmitting the gradient tensors over the band-limited link, which, if estimated, would be as large as the original radar data. In addition, we have found that radar feature maps are heavily concentrated on a few frequency components. Thus, we apply the discrete cosine transform to the radar data cubes and selectively prune out the coefficients effectively. We preserve the dynamic range of each radar patch through scaled quantization. Combining those techniques, our proposed online adaptive compression scheme achieves over 100x feature size reduction at minimal performance drop (~1%p). We validate our results on the RADIal, CARRADA, and Radatron datasets.
