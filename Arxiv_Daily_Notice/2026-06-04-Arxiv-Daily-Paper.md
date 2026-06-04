# Showing new listings for Thursday, 4 June 2026
## Keyword: SLAM
### Title:
          Forecasting Political News Engagement on Social Media
 - **Authors:** Karthik Shivaram, Mustafa Bilgic, Matthew Shapiro, Aron Culotta
 - **Subjects:** Subjects:
Social and Information Networks (cs.SI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding how political news consumption changes over time can provide insights into issues such as hyperpartisanship, filter bubbles, and misinformation. To investigate long-term trends of news consumption, we curate a collection of over 60M tweets from politically engaged users over seven years, annotating ~10% with mentions of news outlets and their political leaning. We then train a neural network to forecast the political lean of news articles Twitter users will engage with, considering both past news engagements as well as tweet content. Using the learned representation of this model, we cluster users to discover salient patterns of long-term news engagement. Our findings include the following: (1) hyperpartisan users are more engaged with news; (2) right-leaning users engage with contra-partisan sources more than left-leaning users; (3) topics such as immigration, COVID-19, Islamaphobia, and gun control are salient indicators of engagement with low quality news sources.
### Title:
          BPDA-GMM: Bayesian Probabilistic Data Association via Gaussian Mixture Models for Semantic SLAM
 - **Authors:** Thanh Nguyen Canh, Haolan Zhang, Xiem HoangVan, Antonio Sgorbissa, Nak Young Chong
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Probabilistic data association (PDA) improves semantic SLAM in perceptually aliased scenes, but existing methods often assume a fixed landmark set, recompute association weights as the map grows, or rely on hand-tuned null-hypothesis weights. To address these limitations, we propose \textbf{BPDA-GMM}, an online Bayesian PDA framework for semantic SLAM with a growing object-level map. BPDA-GMM uses a Dirichlet-process prior to induce a Chinese Restaurant Process (CRP) association model, where accumulated evidence favors existing landmarks, and the concentration parameter assigns probability mass to new landmarks. For each semantic detection, plausible candidates are selected by a joint semantic-geometric gate, CRP-weighted association probabilities are computed, and object landmarks are updated as semantic Gaussians in closed form. The resulting landmark set forms a Gaussian mixture model, and its dominant component is passed to the back-end as a max-mixture semantic factor. When association weights are inconclusive, an ambiguity-triggered $\alpha$-divergence tempering step improves discrimination. Finally, a decoupled back-end zeroes the pose Jacobian of semantic factors, allowing noisy detections to refine landmarks without directly perturbing the trajectory. Experiments in simulation and on a real indoor dataset demonstrate improved trajectory accuracy, semantic mapping quality, and robustness to perceptual aliasing and classifier errors over state-of-the-art baselines. Code and video are publicly available at this https URL.
### Title:
          Teaching Robots to Say 'I Don't Know' : SENTINEL for Uncertainty-Aware SLAM
 - **Authors:** Abhishek S, Badrikanath Praharaj, Sreeram MV
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Low-cost 2D LiDARs lack the intensity channel that higher-end sensors use to diagnose measurement failures, yet they are widely used on educational and budget robotics platforms. We present SENTINEL, a training - free, label - free reliability estimation framework that gives range - only LiDAR an effective diagnostic signal. SENTINEL combines geometry-based scan statistics with cross - modal depth consistency between LiDAR and an RGB - D camera to compute a per - scan reliability score between 0 and 1. When the score falls below a threshold, corrupted scans are rejected and the robot falls back to calibrated wheel odometry, preventing silent SLAM corruption. We evaluate SENTINEL on a GEFIER R1 four - wheel skid-steer robot equipped with an RPLidar A2M12 and an Intel RealSense D435i in a 185 cm by 245 cm arena containing controlled transparent and reflective failure elements on a central obstacle. Spatial reliability maps across five surface conditions, including glass, mirror, shiny paper, and a mixed mirror and shiny-paper condition, show clear separation between clean and failure cases, allowing affected regions to be identified as reject or noise. Because these failure modes are absent in simulation, validation is performed entirely on real hardware.
## Keyword: odometry
### Title:
          Teaching Robots to Say 'I Don't Know' : SENTINEL for Uncertainty-Aware SLAM
 - **Authors:** Abhishek S, Badrikanath Praharaj, Sreeram MV
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Low-cost 2D LiDARs lack the intensity channel that higher-end sensors use to diagnose measurement failures, yet they are widely used on educational and budget robotics platforms. We present SENTINEL, a training - free, label - free reliability estimation framework that gives range - only LiDAR an effective diagnostic signal. SENTINEL combines geometry-based scan statistics with cross - modal depth consistency between LiDAR and an RGB - D camera to compute a per - scan reliability score between 0 and 1. When the score falls below a threshold, corrupted scans are rejected and the robot falls back to calibrated wheel odometry, preventing silent SLAM corruption. We evaluate SENTINEL on a GEFIER R1 four - wheel skid-steer robot equipped with an RPLidar A2M12 and an Intel RealSense D435i in a 185 cm by 245 cm arena containing controlled transparent and reflective failure elements on a central obstacle. Spatial reliability maps across five surface conditions, including glass, mirror, shiny paper, and a mixed mirror and shiny-paper condition, show clear separation between clean and failure cases, allowing affected regions to be identified as reject or noise. Because these failure modes are absent in simulation, validation is performed entirely on real hardware.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          StandardE2E: A Unified Framework for End-to-End Autonomous Driving Datasets
 - **Authors:** Stepan Konev
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving has shifted from modular perception-prediction-planning stacks toward end-to-end (E2E) models that map sensor inputs directly to vehicle control, often regularized by auxiliary tasks such as 3D detection, motion forecasting, and HD-map perception. Progress is driven by a fast-growing ecosystem of sensor-rich driving datasets, yet each ships its own file formats, APIs, coordinate conventions, and modality coverage, leaving cross-dataset experimentation and even basic per-dataset preprocessing to be re-implemented per project. We present StandardE2E, a framework that provides a single unified interface over E2E driving datasets. StandardE2E (i) standardizes per-dataset preprocessing under one shared data schema; (ii) combines multiple datasets in a single PyTorch DataLoader for cross-dataset pretraining, auxiliary-task supervision, and scenario-level filtering; and (iii) reduces adding a new dataset to a single per-dataset mapping from raw frames to the canonical schema, leaving the entire downstream pipeline unchanged. The framework supports six datasets out of the box: Waymo End-to-End, Waymo Perception, Argoverse 2 Sensor, Argoverse 2 LiDAR, NAVSIM (OpenScene-v1.1), and WayveScenes101, and is released as the open-source standard-e2e Python package, available at this https URL.
### Title:
          MineXplore: An Open-Source Reinforcement Learning Exploration Benchmark for GNSS-Denied Underground Environment
 - **Authors:** Abhishek S, Badrikanath Praharaj, Sreeram MV
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Underground mines present extreme conditions for autonomous robot navigation: GPS is denied, lighting is degraded, and tunnel topology is loop-rich and non-convex. Simulation benchmarks grounded in real production-mine geometry and compatible with GPU-accelerated learning pipelines do not yet exist in the open-source ecosystem. We present MineXplore, an open-source MuJoCo-based navigation benchmark derived from the Leung et al. 2017 Chilean underground copper mine dataset. The environment reconstructs a 104,423 sq.m tunnel network through an six-stage contour-to-MJCF pipeline incorporating octagonal wall cross-sections, LiDAR-sourced jagged wall geometry, three terrain friction zones, a global 5 degree incline, and periodic spot lighting. Geometric fidelity is validated at an Intersection over Union (IoU) of 0.9538 against the source survey map, and surface texture similarity scores 79.4% across six structural dimensions. A single-agent PPO baseline trained via RLlib across five independent random seeds achieves a best rolling coverage of 88.89% (3 of 5 seeds reaching the 90% coverage target), confirming that MineXplore supports stable and reproducible policy learning under realistic underground sensing and topology.
### Title:
          Teaching Robots to Say 'I Don't Know' : SENTINEL for Uncertainty-Aware SLAM
 - **Authors:** Abhishek S, Badrikanath Praharaj, Sreeram MV
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Low-cost 2D LiDARs lack the intensity channel that higher-end sensors use to diagnose measurement failures, yet they are widely used on educational and budget robotics platforms. We present SENTINEL, a training - free, label - free reliability estimation framework that gives range - only LiDAR an effective diagnostic signal. SENTINEL combines geometry-based scan statistics with cross - modal depth consistency between LiDAR and an RGB - D camera to compute a per - scan reliability score between 0 and 1. When the score falls below a threshold, corrupted scans are rejected and the robot falls back to calibrated wheel odometry, preventing silent SLAM corruption. We evaluate SENTINEL on a GEFIER R1 four - wheel skid-steer robot equipped with an RPLidar A2M12 and an Intel RealSense D435i in a 185 cm by 245 cm arena containing controlled transparent and reflective failure elements on a central obstacle. Spatial reliability maps across five surface conditions, including glass, mirror, shiny paper, and a mixed mirror and shiny-paper condition, show clear separation between clean and failure cases, allowing affected regions to be identified as reject or noise. Because these failure modes are absent in simulation, validation is performed entirely on real hardware.
### Title:
          Recent Advances and Trends in Learning-based 3D Representations
 - **Authors:** Adrien Schockaert, Hamid Laga, Hazem Wannous, Vincent Magnier, Guillaume Dufaye, Jean-françois Witz
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The selection of an appropriate 3D representation is a fundamental design decision that dictates the efficiency, quality, and capabilities of modern computer vision and graphics pipelines for tasks such as 3D reconstruction, novel-view synthesis and rendering, shape and motion analysis, recognition, and generation. While traditional representations (\eg meshes, point clouds, and volumetric grids) remain standard outputs of 3D sensors (\eg LiDAR and 3D scanners) and are widely used in downstream applications (\eg editing and simulation), recent neural and primitive-based representations (\eg 3D Gaussian Splatting) offer compact and differentiable alternatives opening a wide range of opportunities in applications such as games, AR/VR, autonomous driving, robot navigation, and medical imaging, to name a few. The goal of this paper is to survey the main families of 3D representations from discrete explicit formats to continuous implicit fields based either on neural rendering or primitive splatting. For each type of representation, we present the general formulation and its variants, discuss its benefits and limitations, and highlight key applications. We conclude the paper by outlining the open challenges and potential directions for future research. Distinct from recent surveys that broadly cover 3D object and scene reconstruction, this paper provides a focused analysis on the evolution of 3D representations themselves. We specifically emphasize the paradigm shift toward implicit representations, offering a novel perspective on how these emerging formats fundamentally alter 3D/4D workflows.
### Title:
          Hierarchical Space Partition for Surface Reconstruction
 - **Authors:** Minjie Tang, Xiangfei Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computational Geometry (cs.CG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generating compact polygonal models from point clouds is a key problem in 3D vision and computer graphics. However, due to inherent limitations of LiDAR scanning (e.g. range constraints and occlusions), critical scene information is often missing, leading to degraded reconstruction accuracy. To address this, we propose a plane assembling strategy that effectively recovers missing details while maintaining model compactness. We classify all the planes extracted from the scene into three categories: highly visible, barely visible, and invisible. The invisible planes, which are recovered by scene structure analysis, indicate the missing details. The three types of planes correspond to the three growth priorities. Each plane grows according to the priority level, and the space is partitioned progressively, namely, the hierarchical partition. Subsequently, we generate a watertight polygonal mesh from the partition via a min-cut-based optimization. Finally, comparisons on public datasets show the effectiveness and superiority of our method against mainstream approaches. The project page is available at this https URL.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          ZipSplat: Fewer Gaussians, Better Splats
 - **Authors:** Alexander Veicht, Sunghwan Hong, Dániel Baráth, Marc Pollefeys
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Feed-forward 3D Gaussian Splatting methods reconstruct a scene from posed or pose-free images in a single forward pass, yet current approaches predict one Gaussian per input pixel, tying the representation budget to camera resolution rather than scene complexity. A flat wall and a richly textured object thus produce equally many Gaussians despite very different geometric needs. We propose ZipSplat, a token-based feed-forward model that decouples Gaussian placement from the pixel grid. A multi-view backbone extracts dense visual tokens, and k-means clustering compresses them into a compact set of scene tokens. Cross- and self-attention refine these tokens, and a lightweight MLP decodes each into a group of Gaussians with unconstrained 3D positions. Because clustering is applied at inference, a single trained model spans the quality-efficiency curve without retraining. ZipSplat operates without ground-truth poses or intrinsics, yet sets a new state of the art on DL3DV and RealEstate10K with ${\sim}6{\times}$ fewer Gaussians than pixel-aligned methods, surpassing the best pose-free baseline by 2.1dB and 1.2dB PSNR, respectively. It further generalizes zero-shot to Mip-NeRF360 and ScanNet++, outperforming all comparable baselines. Our project page is at ${\href{this https URL}{this https URL}}$.
## Keyword: mapping
### Title:
          Multi-Agent Next-Best-View Optimization for Risk-Averse Planning
 - **Authors:** Amirhossein Mollaei Khass, Vivek Pandey, Guangyi Liu, Athanasios Cosse, Emrah Bayrak, Nader Motee
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-agent Next-Best-View (NBV) selection for safe path planning in uncertain and unknown environments requires informative, safety-aware, and efficient coordination. Centralized approaches rely on sharing raw sensor data or significant communication overhead, resulting in limited scalability. We propose a distributed, risk-aware multi-agent NBV framework in which each robot maintains a private local 3D Gaussian Splatting map and the team jointly maximizes expected information gain (EIG) restricted to masked zones along planned trajectories. The resulting distributed objective is solved by Consensus ADMM (C-ADMM) over a communication graph, with each robot exchanging only candidate viewpoints, planned trajectory descriptors, and scalar EIG contributions. Collision risk along each trajectory is modeled via Average Value-at-Risk (AV@R) over the local 3DGS map and used both to shape the masking radius and to score planned paths. Experiments in Gibson environments at multiple team sizes show that the distributed formulation approaches the centralized baseline in mapping quality and trajectory safety while reducing communication by orders of magnitude.
### Title:
          StandardE2E: A Unified Framework for End-to-End Autonomous Driving Datasets
 - **Authors:** Stepan Konev
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving has shifted from modular perception-prediction-planning stacks toward end-to-end (E2E) models that map sensor inputs directly to vehicle control, often regularized by auxiliary tasks such as 3D detection, motion forecasting, and HD-map perception. Progress is driven by a fast-growing ecosystem of sensor-rich driving datasets, yet each ships its own file formats, APIs, coordinate conventions, and modality coverage, leaving cross-dataset experimentation and even basic per-dataset preprocessing to be re-implemented per project. We present StandardE2E, a framework that provides a single unified interface over E2E driving datasets. StandardE2E (i) standardizes per-dataset preprocessing under one shared data schema; (ii) combines multiple datasets in a single PyTorch DataLoader for cross-dataset pretraining, auxiliary-task supervision, and scenario-level filtering; and (iii) reduces adding a new dataset to a single per-dataset mapping from raw frames to the canonical schema, leaving the entire downstream pipeline unchanged. The framework supports six datasets out of the box: Waymo End-to-End, Waymo Perception, Argoverse 2 Sensor, Argoverse 2 LiDAR, NAVSIM (OpenScene-v1.1), and WayveScenes101, and is released as the open-source standard-e2e Python package, available at this https URL.
### Title:
          The Saturation Trap and the Subjectivity of Intervention Timing: Why Affect-Based Triggers and LLM Judges Fail to Time Interventions on Autonomous Agents
 - **Authors:** Manvendra Modgil
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As autonomous AI agents move from conversational systems to long-horizon software execution, runtime safety layers that decide when to interrupt an agent have become essential. We study this timing problem using a continuous 18-dimensional affective-dynamics engine (HEART) as a diagnostic probe, evaluating four intervention trigger families - absolute state thresholds, composite state-action patterns, regex reasoning-feature extraction, and zero-shot LLM-as-judge - against human-annotated intervention points on SWE-bench-Verified debugging traces. We report three findings. First, a State Saturation Trap: agents show no recovery signal under sustained difficulty, so modeled frustration quickly crosses the threshold and stays at its maximum, converting threshold-on-state triggers from moment detectors into near-constant indicators that fire on 39-83% of actions across five trajectories. Second, a capability-and-context floor for LLM judges: a small model (gpt-5.4-mini) never fires, while frontier and cross-vendor models escape the zero-firing floor only with full-trajectory context, and even then reach only F1 0.17-0.40 at up to 90x the cost. Third, and most importantly, the supervised target is not reproducible among humans: three trained annotators using one rubric on a 56-action trajectory agree on where to intervene only slightly above chance (location Krippendorff's alpha = +0.047; best pairwise Cohen's kappa = +0.349) and not at all on intervention type (pause degenerate; clarify below chance; reflect only alpha = +0.226). We conclude that intervention timing is a low-reliability construct, making single-annotator F1 an unsuitable optimization target. Our contribution is the joint mapping of this problem across human inter-rater reliability, four detector architectures, a cross-model LLM-judge sweep, and a reproduced saturation effect, rather than any single detector's accuracy.
### Title:
          Towards Process Mining Use Case Map Models with PM4Py-UCM
 - **Authors:** Daniel Amyot
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Given the increasing amount of data available in organizational systems, there is an opportunity for early requirements engineering (RE) activities to be better based on evidence than ever before. Process mining (PM) has been used for over two decades to discover and analyze as-is process models from event logs extracted from such data, with outputs often in the form of Petri Nets, directly-follows graphs, or BPMN models. This paper aims to make Use Case Map (UCM) models, from ITU-T's User Requirements Notation (URN), a first-class output of process discovery, so that mined behavior can be used in URN-based modeling, analysis, and management activities. This paper contributes and illustrates PM4Py-UCM, an open-source extension to the existing PM4Py Python library. This new tool contributes 1) a UCM discovery pipeline, 2) hierarchical decomposition strategies producing nested UCM models, 3) configurable performer mappings for UCM and BPMN visualizations, and 4) an exporter to a URN tool (jUCMNav) that preserves the mined model under round-trip. Using public and synthetic event logs, the paper showcases how the same behavior is rendered under different performer abstractions and decomposition strategies, and discusses how PM can become a practical instrument for model-driven RE.
### Title:
          Geometry-Preserving Unsupervised Alignment for Heterogeneous Foundation Models
 - **Authors:** Shuwen Yu, Zhanxuan Hu, Yi Zhao, Yonghang Tai, Huafeng Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Foundation models have driven rapid progress in computer vision, yet the two dominant paradigms, vision-language foundation models (VLMs) and vision-only foundation models (VFMs), remain only partially compatible. VLMs offer language-grounded semantic alignment but are often visually coarse, while VFMs learn discriminative perceptual geometry but lack semantic grounding. We propose GPUA (Geometry-Preserving Unsupervised Alignment), a framework that integrates the complementary strengths of VFMs and VLMs. Inspired by cross-lingual alignment, GPUA treats VFM features as a visual language and learns an orthogonal mapping that translates the VFM space into the VLM semantic space, preserving geometry and narrowing the modality gap without labels or model parameter updates. GPUA is task-agnostic and requires only feature-level access to pretrained models. Experiments across diverse benchmarks demonstrate improved cross-model compatibility and strong gains in downstream zero-shot recognition and segmentation with negligible overhead. Code is available at this https URL
### Title:
          On Out-of-sample Embedding in UMAP
 - **Authors:** Mohammad Tariqul Islam, Jason W. Fleischer
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neighbor embedding algorithms reveal correlations in high-dimensional data by constructing an equivalent graph representation in a lower-dimensional space. An increasingly popular algorithm is Uniform Manifold Learning and Projection (UMAP), which uses algebraic topology to map distances between the two spaces. While it works well on many types of data sets, UMAP has trouble adding out-of-sample points to a pre-existing mapping. In particular, UMAP often places new points on the periphery of the found clusters, rather than in their interiors with their correlated neighbors. Here, we overcome this ``repulsion effect'' by optimizing pairwise interactions within the original k-nearest-neighbor graph. Moreover, we show that parameterizing UMAP obtains better embeddings than non-parametric algorithms, particularly as the data gets more complex (e.g., medical images). We also show that the repulsion effect is naturally mitigated when a parameterized UMAP is employed to embed the data. We characterize different UMAP approaches using trustworthiness, nearest neighbor classifiers, and by analyzing attractive and repulsive forces in the embeddings.
### Title:
          MapAgent: An Industrial-Grade Agentic Framework for City-scale Lane-level Map Generation
 - **Authors:** Deguo Xia, Zihan Li, Haochen Zhao, Dong Xie, Yuyao Kong, Xiyan Liu, Jizhou Huang, Mengmeng Yang, Diange Yang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Lane-level maps are critical infrastructure for autonomous driving and lane-level navigation, yet constructing and maintaining standardized lane networks for hundreds of cities remains highly labor-intensive. Recent end-to-end vectorized mapping methods can predict lane geometry and topology directly from sensor data, but they typically treat mapping specifications and traffic regulations as implicit, dataset-dependent supervision. Moreover, in complex scenes (e.g., worn or missing markings and occlusions), correct lane configurations are often under-determined by visual evidence alone, making specification violations a major source of human post-editing. We propose MapAgent, an industrial-grade agentic architecture that augments a vectorization backbone for specification-compliant lane-map production. Rather than merely adding an agent loop to map prediction, MapAgent couples backbone perception with explicit specification verification, constraint-aware reasoning, and deterministic map editing under a bounded, verification-driven Judge-Planner-Worker loop. A vision-language Judge diagnoses errors by jointly inspecting visual evidence and draft vectors, while a tool-calling Planner generates minimal corrective edits with post-edit re-validation. To remain scalable for city-scale production, MapAgent is selectively triggered only on tiles with low backbone confidence, adding modest overhead while preserving throughput. Experiments on real-world datasets show consistent gains over strong production baselines, especially in complex and long-tail scenarios. Additionally, MapAgent has been integrated into Baidu Maps, supporting lane-level map generation for over 360 cities nationwide and elevating the overall production automation to over 95%, demonstrating MapAgent's practicality and effectiveness for large-scale lane-level map generation.
### Title:
          MAD: Mapping-Aware World Models for Agile Quadrotor Flight
 - **Authors:** Xinhong Zhang, Runqing Wang, Yunfan Ren, Ding Yu, Boyu Zhou, Jian Sun, Fang Deng, Jie Chen, Gang Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Agile quadrotor flight in cluttered scenes requires more than a reactive mapping from a depth image to a control command: the vehicle must remember which regions have been observed, infer nearby occupied space, and act under partial visibility and tight latency. In this paper, we present Mapping-Aware Dreamer (MAD), a geometry-aware world model for vision-based quadrotor flight. Instead of using raw-image reconstruction as the main self-supervised objective, MAD learns recurrent latent dynamics that reconstruct robocentric occupancy and visibility grid maps together with proprioceptive states. This design forces the latent state to encode local geometry, visibility history, and ego-motion in a form that is directly relevant to collision avoidance. MAD is trained in DiffAero using a GPU-parallel map-construction module that provides high-throughput supervision for occupancy and visibility. The learned representation is used in three policy-learning modes: imagination-based MAD-Dreamer and feature-extractor variants based on PPO and SHAC. Across visual navigation and racing tasks, MAD-based agents achieve higher success rates, faster flight, and better cross-task transfer than corresponding vision-only baselines. The model also produces interpretable map predictions and accurate ego-motion estimates from depth observations. We further deploy the learned policy on a physical quadrotor with an Intel RealSense D435i and demonstrate safe indoor and outdoor flight under limited sensing, reaching 9.66 m/s in simulation and 5.05 m/s in real-world forest experiments. These results show that mapping-aware world models provide a practical middle ground between modular aerial navigation and end-to-end learning.
### Title:
          BPDA-GMM: Bayesian Probabilistic Data Association via Gaussian Mixture Models for Semantic SLAM
 - **Authors:** Thanh Nguyen Canh, Haolan Zhang, Xiem HoangVan, Antonio Sgorbissa, Nak Young Chong
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Probabilistic data association (PDA) improves semantic SLAM in perceptually aliased scenes, but existing methods often assume a fixed landmark set, recompute association weights as the map grows, or rely on hand-tuned null-hypothesis weights. To address these limitations, we propose \textbf{BPDA-GMM}, an online Bayesian PDA framework for semantic SLAM with a growing object-level map. BPDA-GMM uses a Dirichlet-process prior to induce a Chinese Restaurant Process (CRP) association model, where accumulated evidence favors existing landmarks, and the concentration parameter assigns probability mass to new landmarks. For each semantic detection, plausible candidates are selected by a joint semantic-geometric gate, CRP-weighted association probabilities are computed, and object landmarks are updated as semantic Gaussians in closed form. The resulting landmark set forms a Gaussian mixture model, and its dominant component is passed to the back-end as a max-mixture semantic factor. When association weights are inconclusive, an ambiguity-triggered $\alpha$-divergence tempering step improves discrimination. Finally, a decoupled back-end zeroes the pose Jacobian of semantic factors, allowing noisy detections to refine landmarks without directly perturbing the trajectory. Experiments in simulation and on a real indoor dataset demonstrate improved trajectory accuracy, semantic mapping quality, and robustness to perceptual aliasing and classifier errors over state-of-the-art baselines. Code and video are publicly available at this https URL.
### Title:
          Bridge the Last-Mile Gap to Semantic Analytics: Compiling Natural-Language Queries into Semantic Operator Pipelines
 - **Authors:** Wenkai Dong, Ruyu Li, Sairam Gurajada, Yifan Wang
 - **Subjects:** Subjects:
Databases (cs.DB)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated AI workflows increasingly rely on natural-language reasoning over heterogeneous data, but lack a practical way to execute it through optimized semantic data systems. Recent semantic operator systems, such as Palimpzest and LOTUS, expose declarative operators for filtering, joining, mapping, and aggregating over tables, text, and images using natural-language predicates. However, these systems require users to manually choose operators, order them, write predicates, and adapt the pipeline to backend-specific APIs. This is difficult for non-experts, brittle across backends, and infeasible for automated workflows where queries and data vary at runtime. We present NL2Pipe, a middleware system that compiles natural-language questions into executable semantic operator pipelines, treating this as a three-phase compilation problem. First, a Query-Data Linker grounds question entities against the actual data and discovers implicit bridge entities needed to connect tables, text, and images. Second, a Semantic Planner produces a backend-agnostic action plan of semantic operators and natural-language predicates. Third, a Code Generator translates the plan into executable code for a target backend using an auto-generated reference document capturing operator signatures, example pipelines, and backend constraints. This separates data-aware reasoning from backend-specific code generation, letting the same planning logic support multiple backends. Evaluation shows NL2Pipe substantially outperforms baselines on complex cross-source workloads (e.g., up to 60% higher F1) while maintaining bounded cost and competitive latency. This demonstrates that automatic compilation from natural language to semantic operator pipelines is both practical and effective for bringing semantic analytics to non-expert users and automated AI workflows.
### Title:
          U-Net-Accelerated Quality-Diversity Optimization for Climate-Adaptive Urban Layouts
 - **Authors:** Alexander Hagg, Tania Guerrero, Dirk Reith
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Optimizing urban layouts for climate adaptation requires balancing building density with cold-air ventilation. Because physics-based climate simulations are computationally expensive, planners typically evaluate fewer than ten manual designs. \gls{qd} algorithms offer a way to systematically illuminate the design space, but they require surrogate models to be practical. In this paper, we replace a slow, regulatory physics simulator with a spatial deep-learning surrogate (U-Net) inside an offline MAP-Elites loop. We systematically compare this spatial approach with a traditional \gls{gp} surrogate across different training-data strategies (quasi-random Sobol sampling vs.\ active \gls{qd} bootstrapping). Our results reveal that scalar \gls{gp} surrogates fail catastrophically when trained on random samples, requiring expensive, actively generated \gls{qd} archives to generalize. In contrast, the spatial inductive bias of the U-Net allows it to learn the underlying physics mapping robustly ($R^2 = 0.996$), completely independent of the training data source. This allows offline \gls{qd} optimization to achieve highly accurate fitness rankings ($\rho = 0.994$) using only a one-time batch of random training samples. The resulting pipeline, deployed in the open-source OpenSKIZZE tool, generates thousands of diverse, climate-evaluated building layouts in under ten minutes.
### Title:
          Uncertainty-Aware End-to-End Co-Design of Neural Network Processors: From Training and Mapping to Fabrication
 - **Authors:** Yuyang Du, Yujun Huang, Gioele Zardini
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Hardware Architecture (cs.AR); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Designing a neural network processor is an end-to-end co-design problem: network architecture and training budget determine the inference workload; hardware mapping decisions determine chip area, latency, and energy; and these characteristics govern fabrication yield and manufacturing cost. In practice, these decisions are made in separate stages, and existing co-design methodologies are tightly coupled to specific algorithms, making it difficult to improve one component without reworking the entire pipeline. This paper presents a unified framework, grounded in monotone co-design theory, that composes four interoperable design blocks spanning network training, chip mapping, wafer-level fabrication, and compute resource allocation. Each block exposes only a functionality-resource interface to the rest of the system, so any block can be refined without structural changes elsewhere. A central contribution is the treatment of uncertainty: rather than collapsing stochastic outcomes into point estimates, the framework introduces Confidence, the inverse of success probability, as an explicit and optimizable resource alongside cost, time, and power. Three case studies validate the approach. The first recovers Pareto-optimal implementations across heterogeneous application scenarios. The second confirms that Confidence functions as a continuously tunable design knob rather than a post-hoc diagnostic. The third demonstrates that improving a single block's implementation set automatically propagates to the global Pareto front, without modifying the co-design diagram.
### Title:
          Event Calculus Meets Hybrid ASP
 - **Authors:** Ondřej Vašíček, Joaquín Arias, Jan Fiedor, Gopal Gupta, Bohuslav Křena, Jakub Němec, Javier Romero, Tomáš Vojnar
 - **Subjects:** Subjects:
Logic in Computer Science (cs.LO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Event Calculus (EC) implemented in answer set programming (ASP) has proven suitable for specifying requirements on safety-critical systems thanks to its elegant representation of both discrete and continuous changes and its semantic closeness to semi-formal natural language. However, continuous changes and the size of value domains of time and system properties (fluents) pose significant challenges. Grounding-based ASP solvers, e.g., clingo, which implement Discrete EC (DEC), lead to combinatorial explosion in program size and inaccurate representation. The grounding-free s(CASP) does not discretize but struggles with non-termination due to its top-down execution. This paper introduces Hybrid EC, an extended axiomatization of DEC, that tackles the challenges via functional fluents and a mapping of time to abstract steps. We implement it using clingcon and clingo-lpx (Hybrid ASP systems over integers and rationals, respectively) where the value (dense) domains of fluents and time are represented as linear constraints and evaluated by external solvers, while ensuring termination whenever solutions exist. We validate both implementations on a number of examples and observe that they are unaffected by the size of the domains and that handling rationals does not impact scalability. Most importantly, the ability of clingo-lpx to handle dense domains enables accurate modeling of continuous change.
### Title:
          STaR-Quant: State-Time Consistent Post-Training Quantization for Diffusion Large Language Models
 - **Authors:** Xin Yan, Aqiang Wang, Zhenglin Wan, Xingrui Yuand Ivor Tsang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion large language models (DLLMs) have recently emerged as a promising alternative to autoregressive LLMs by generating text through iterative masked denoising with bidirectional context. However, their large model sizes and iterative denoising process introduce substantial memory and computational overhead, motivating post-training quantization for efficient deployment. In this paper, we identify two key challenges for low-bit DLLM quantization: state-dependent activation disparity and temporal error accumulation. Masked and unmasked tokens exhibit different activation distributions within each denoising step, while quantization errors can accumulate across steps during iterative decoding. To address these challenges, we propose STaR-Quant, a state-time consistent PTQ framework for DLLMs. STaR-Quant introduces State-Guided Activation Transformation (SGAT) to assign masked and unmasked tokens to different activation transformation spaces with a unified static weight-side transformation. It further introduces Temporal Attention Compensation (TAC) to correct the quantized attention representation via a lightweight block-diagonal affine mapping. Experiments on representative DLLMs demonstrate that STaR-Quant consistently improves low-bit weight-activation quantization over strong PTQ baselines, while delivering up to 1.69x speedup and 3.14x memory saving over FP16 deployment.
### Title:
          Anchor3R: Streaming 3D Reconstruction with Transient Anchors for Long-Horizon Visual Mapping
 - **Authors:** Peilin Tao, Chong Cheng, Yuansen Du, Caiwei Song, Zhengqing Chen, Xiaoyang Guo, Wei Yin, Weiqiang Ren, Qian Zhang, Hainan Cui, Shuhan Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long-horizon online visual mapping is a core capability for robot perception, requiring continuous camera-motion and scene-geometry estimation from visual streams under bounded memory and computation. Recent feed-forward 3D reconstruction models provide strong geometric priors, but their streaming variants often predict poses in a fixed coordinate system tied to the first frame or a persistent scene memory. This fixed-gauge design leads to train--test mismatch, attention bias toward early anchors, and accumulated drift on sequences much longer than those seen during training. We propose \emph{Anchor3R}, a streaming 3D reconstruction framework that treats feed-forward reconstruction as current-centric local measurement prediction rather than persistent global-gauge regression. At each time step, Anchor3R predicts window-relative poses and a local pointmap in the current-frame coordinate system, turning streaming reconstruction into relative-pose measurement generation. These measurements support online pose updates, while loop-closure reinsertion and motion averaging align the trajectory and transform local pointmaps into a coherent global reconstruction. Experiments on indoor, outdoor, driving, and RGB-D benchmarks show that Anchor3R improves long-horizon pose accuracy and dense reconstruction quality over existing streaming baselines, while supporting bounded-memory online inference.
### Title:
          Attention-Augmented LSTMs for Automatic Homophonic Ciphertext Decipherment
 - **Authors:** Micaella Bruton, Meriem Beloucif, Beáta Megyesi
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Homophonic substitution ciphers replace each plaintext letter with one of several possible ciphertext codes, deliberately weakening letter-frequency patterns and making automated decipherment difficult. This paper evaluates whether an attention-augmented Long Short-Term Memory (LSTM) model can learn such mappings in a historically motivated shared-key setting: all ciphertexts draw from the same known homophonic code pool, while individual keys use different consistent subsets of that pool. Using synthetic ciphertexts generated with ChronoFidelius from historical English and Swedish texts dated 1500--1899, we test performance across ciphertext lengths, centuries, variable-length codes, and simulated transcription errors. Models are trained only on aligned ciphertext--plaintext pairs, without external language models, frequency statistics, or key-search heuristics. Results show near-perfect character-level decryption accuracy across both languages and all periods, including short and noisy ciphertexts. The model also fails predictably on ciphertexts outside the shared pool, indicating that it functions as a practical tool for decipherment and key-space verification when key reuse is suspected.
### Title:
          Bernoulli CUSUM and Bayes-Optimal Detection Ceilings for Trust Fraud in Sparse Rating Networks
 - **Authors:** Talal Ashraf Butt
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Social and Information Networks (cs.SI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sequential trust detection in rating networks relies on continuous observation models that fail on real data. On Bitcoin-OTC, 56\% of ratings take a single value under standard mapping, breaking the distributional assumptions that parametric detectors require. This paper makes three contributions. It derives a Bayes-optimal F1 detection ceiling for per-node sequential detectors using empirically measured observation parameters. At Bitcoin-OTC's median in-degree of 2, this ceiling falls to 0.451 for strategic attacks, explaining why unsupervised methods cluster near $F1 \approx 0.4$. The analysis shows that detector-model matching, not information content, determines performance: binary models retain 86\% of mutual information while enabling exact parametric fit. A dual-regime architecture is presented where Bernoulli CUSUM detects behavioral shifts and triggers asymmetric scoring. Ablation reveals a co-design constraint: the modulation mechanism improves AUC by 0.030 on binary observations but degrades it by 0.094 on continuous observations. The combined system achieves AUC 0.749 on Bitcoin-OTC and 0.796 on Bitcoin-Alpha, beating GaaSTrust on all 8 attacks ($p < 0.003$), with founder-label AUC of 0.999.
### Title:
          Continual Visual and Verbal Learning Through a Child's Egocentric Input
 - **Authors:** Xiaoyang Jiang, Yanlai Yang, Kenneth A. Norman, Brenden Lake, Mengye Ren
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Children learn the meanings of words from a continuous, temporally structured stream of egocentric experience. Recent work shows that neural networks can also learn word-referent mappings from a child's egocentric video recordings, but they cycle through the shuffled data for hundreds of epochs, contrasting with how children actually encounter their environment. We introduce BabyCL, a continual multimodal learning framework that processes the SAYCam dataset in a single chronological pass, combining streaming visual representation learning with an image-text contrastive objective. BabyCL combines a multi-stage temporal segmentation of the stream with a dual replay buffer that independently manages visual and multimodal histories, and it is jointly trained with three contrastive losses on a shared backbone. Under a matched optimization budget, BabyCL outperforms streaming learning baselines on the SAYCam Labeled-S 4AFC benchmark, substantially narrowing the gap to an upper bound of offline training. Ablations show that the gains are robust to the length of the online temporal segmentation window and the eviction rule of the replay buffer. Together, these results show that meaningful word-referent mappings can emerge under training conditions much closer to a child's actual experience.
## Keyword: localization
### Title:
          Affordance2Action: Task-Conditioned Scene-level Affordance Grounding for Real-Time Manipulation
 - **Authors:** Litao Liu, Yifan Han, Pengfei Yi, Wenbo Yu, Hanqing Wang, Haoran Du, Enze Yuan, Zilin Yuan, Ruiding Feng, Michael Liu, Qi Zhang, Jingjin Yu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Task-conditioned manipulation requires grounding instructions to task-relevant functional parts rather than object categories. This setting is scene-dependent and often one-to-many in cluttered scenes: the same object may afford different interactions across tasks, while a single task may correspond to either one functional region or multiple valid functional regions, depending on the scene layout. Existing affordance datasets and benchmarks remain misaligned with this setting, as they typically focus on grasping or object-level affordances, rely on synthetic scenes, or assume a single instruction-region correspondence. We present Affordance2Action (A2A), a benchmark-centered learning framework for scene-level, task-conditioned part affordance grounding. At its core is A2A-Bench, a manipulation-oriented benchmark that covers both single-region and multi-region instruction correspondences in everyday scenes, with the latter highlighting the ambiguity and diversity of affordance grounding in realistic multi-object environments. To construct it at scale, we build A2A-AffordGen, an agent-assisted annotation pipeline that combines language-model filtering, interactive part segmentation, instance-level mask-out refinement, task-reasoning instruction generation, and human verification. A2A-Bench's supervision further supports diverse downstream applications, with real-time affordance grounding and affordance-conditioned manipulation policies as two representative examples. Experiments show that A2A exposes substantial gaps in generic segmentation, VLM-based grounding, and affordance distillation baselines, while improving task-level localization and providing useful spatial priors for downstream manipulation. All datasets and code will be publicly released to promote open research.
### Title:
          FindIt: A Format-Informed Visual Detection Benchmark for Generalist Multimodal LLMs
 - **Authors:** Eshika Khandelwal, Jingjing Pan, Mingfang Zhang, Quan Kong, Lorenzo Garattoni, Hilde Kuehne
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal large language models (MLLMs) are predominantly evaluated on free-form vision-language tasks such as visual question answering, captioning, and summarization. However, their practical use is rapidly expanding to more structured computer vision settings, where users prompt models to perform localization-centric tasks such as object detection, often within larger agentic or decision-making systems. Despite this shift, there is currently no standardized benchmark that systematically evaluates these capabilities at scale. In this work, we introduce the first comprehensive benchmark specifically designed to assess the promptable localization abilities of generalist MLLMs. Our benchmark spans four core task categories: object detection, referring expression detection, instance-level detection, and video-based detection. To enable consistent and fair evaluation, we develop a unified framework that standardizes inputs, enforces parsable bounding box outputs, and defines transparent evaluation protocols across tasks. Using this suite, we evaluate a diverse set of open-source and proprietary MLLMs, providing an in-depth analysis of their performance and limitations. Beyond accuracy, we examine models' ability to adhere to output format specifications, showing that current systems are highly sensitive to formatting constraints and often fail to generalize even to minor variations. Our results highlight both the strengths and shortcomings of state-of-the-art MLLMs in localization settings, and point toward important directions for improving multimodal model design and evaluation.
### Title:
          Exponential Time Differencing Schemes for a Phase-Field Model of Multicomponent Membranes
 - **Authors:** Wangbo Luo, Zhonghua Qiao, Yanxiang Zhao
 - **Subjects:** Subjects:
Numerical Analysis (math.NA); Mathematical Physics (math-ph); Pattern Formation and Solitons (nlin.PS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we develop and analyze exponential time differencing (ETD) schemes for a phase-field model of multicomponent membranes proposed in our previous work \cite{luo2025ohta}, in which membrane deformation is governed by a force-balance phase-field equation and protein segregation is described by a membrane-associated Ohta-Kawasaki (OK) dynamics. For a fixed phase-field membrane, we introduce a geometry-adapted operator splitting method based on the localization function, which reformulates the surface OK dynamics into a form suitable for ETD integration. The resulting first- and second-order ETD schemes, combined with finite-difference spatial discretization, are rigorously proved to satisfy a discrete maximum-bound principle and unconditional energy stability. For the coupled system, we construct stabilized ETD schemes in an FFT-based spectral framework, treating stiff linear terms exactly and nonlinear mechanochemical couplings explicitly. A narrow-band implementation further reduces the computational cost by restricting surface calculations to the diffuse membrane region. Numerical experiments confirm the predicted temporal accuracy, maximum-bound preservation, and energy decay for the fixed-membrane OK problem, and demonstrate stable and efficient three-dimensional simulations of protein-driven pattern formation and membrane deformation.
### Title:
          TransTac: Visuo-Tactile Modality Transition via Ultraviolet-Encoded Transparent Elastomers
 - **Authors:** Lingyue Yang, Bin Fang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-based tactile sensors (VBTS) recover high-resolution contact geometry but typically rely on opaque elastomer layers that prevent visual transparency, while RGB-D cameras provide global depth perception yet degrade significantly at close range. To address this limitation, we present TransTac, a transparent ultraviolet (UV)-encoded binocular VBTS that integrates visual observation and marker-based tactile reconstruction within a single compact device. The system employs a transparent elastomer embedded with UV-reflective markers and a prior-guided Delaunay stereo matching algorithm for robust sparse triangulation. To reliably detect densely distributed semitransparent markers, we develop a lightweight detector that enables stable localization under contact and deformation. The proposed prior-guided Delaunay matching improves correspondence robustness by approximately 21% compared with global assignment baselines while maintaining high reconstruction accuracy. In semantic evaluation, TransTac achieves up to 83.3% zero-shot recognition accuracy on tactile images, exceeding opaque tactile baselines by approximately 50 percentage points. Embedding analysis further reveals substantially stronger cross-modal alignment with natural images, with class-center similarity increasing from around 0.2 to over 0.77. Controlled near-distance experiments quantify the degradation of RGB-D depth reliability and demonstrate extended geometric coverage enabled by visuo-tactile integration. Finally, a compact prototype is implemented with an approximate hardware cost of $70.
### Title:
          Cooperative Circumnavigation for Multiple Unmanned Surface Vehicles Without External Localization
 - **Authors:** Xueming Liu, Lin Li, Xiang Zhou, Tianjiang Hu, Qingrui Zhang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper proposes a cooperative target circumnavigation framework for multiple unmanned surface vehicles (USVs) operating without external localization. The objective is to maintain a uniform circular formation of a specified radius around a target using only limited onboard sensing. The framework adopts a heterogeneous perception strategy that distinguishes between the asymmetric sensing relationships with the target and among the USVs. Specifically, the USVs obtain relative range and displacement measurements through active perception and inter-vehicle communication, while bearing measurements to a non-cooperative target are acquired via passive sensors. To estimate relative positions--both among USVs and between each USV and the target--we employ a Maximum Correntropy Kalman Filter and a Pseudo-Linear Kalman Filter, respectively. A coupled oscillator-based formation controller is designed to ensure system observability while achieving circumnavigation. Theoretical analysis demonstrates that the controller ensures the relative motions between the USVs, as well as that between each USV and the target, satisfy the persistent excitation condition, thereby guaranteeing observability of the Kalman-based filters. The effectiveness of the proposed approach is validated through numerical simulations.
### Title:
          Impostor: An Agent-Curated Benchmark for Realistic AIGC Manipulation Localization
 - **Authors:** Zhenliang Li (1), Yutao Hu (1), Qixiong Wang (2), Wenpeng Du (1), Hongxiang Jiang (2), Jiasong Wu (1), Xiaolong Jiang (2), Jungong Han (3) ((1) Southeast University, (2) Xiaohongshu Inc., (3) Tsinghua University)
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in generative image editing have improved the realism and controllability of localized image manipulation, raising new challenges for image manipulation detection and localization (IMDL). However, existing IMDL benchmarks still have limitations in visual realism, manipulation diversity, and generator coverage, making it difficult to reflect recent trends in image manipulation. To address these limitations, we introduce Impostor, a high-quality AI-edited image manipulation localization dataset containing 100K manipulated images. Impostor is constructed by CraftAgent, a closed-loop agent framework that integrates scene perception, editing planning, manipulation execution, quality validation, and iterative reflection to automatically generate diverse and visually realistic manipulated images. Moreover, Impostor contains images generated by seven recent AIGC models across three manipulation types and includes multiple manipulated regions, providing a more comprehensive benchmark for AIGC-based IMDL. Furthermore, we propose PhaseAware-Net (PANet), a semantic-forensic framework that introduces local phase modeling and semantic-forensic consistency learning to better localize semantically plausible yet forensically disrupted manipulated regions. Extensive experiments show that Impostor poses significant challenges to existing large vision-language models (LVLMs) and specialized IMDL methods, while PANet achieves superior performance on Impostor and multiple public benchmarks.
### Title:
          Selection-Aware Diagnostics for Chain-of-Thought Answer Hijacking
 - **Authors:** Jianwei Tai
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study a controlled numeric proxy for chain-of-thought (CoT) answer hijacking, motivated by attacks in which benign-looking reasoning steers a harmful final answer. CoT wrappers on GSM8K and MATH-500 flip final answers away from gold labels. Rather than treating activation patching as clean-trace restoration, we ask where hijacked trajectories are fragile and whether recovery depends on a same-problem clean source. Across Qwen2.5-7B and Llama3-8B on GSM8K few-shot, puzzle, and sycophant hijacks, three few-shot/puzzle cells pass confirmatory $K{=}1$ localization after Bonferroni correction. A selection-aware 50/50 band validation preserves held-out in-band minus out-of-band gaps of +32.6, +45.1, and +17.7 points for Qwen-puzzle, Llama3-fewshot, and Llama3-puzzle, while exact $\Lstar$ agreement is much less stable. Qwen-fewshot remains exploratory, and sycophant cells are temporal-diffuse under short patches. A BF16 Qwen-puzzle full-band sweep preserves the band signal ($n{=}30$, spread 0.33 at $K{=}1$, peak layer 20), supporting the conclusion that the band is not only an INT4 artifact. Fixed-hook GSM8K reruns preserve recovery in both primary puzzle cells: Qwen-puzzle recovers 47.0\% at $n{=}100$ (47/100; Wilson 95\% CI [37.5\%, 56.7\%]), while Llama3-puzzle recovers 39.0\% at $n{=}100$ (39/100; [30.0\%, 48.8\%]). Frozen transfer to MATH-500 recovers 26.0\% of qualified cases in the largest fixed-transfer run (13/50; Wilson 95\% CI [15.9\%, 39.6\%]). Source controls change the mechanism interpretation. Paired bootstraps give finite-sample non-separation between clean and random sources in Qwen-fewshot (+3.0 points, 95\% CI [-18.2,+27.3]) and Llama3-puzzle at expanded $n{=}60$ (clean--random -8.3 [-21.7,+5.0]), while Llama3-fewshot is content-mediated (+40.0 [+16.7,+60.0]).
### Title:
          Z-FLoc: Zero-Shot Floorplan Localization via Geometric Primitives
 - **Authors:** Ayumi Umemura, Toshinori Kuwahara, Marc Pollefeys, Daniel Barath
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual localization -- estimating a camera pose within a pre-existing map -- is a fundamental problem in computer vision. Floorplans are an attractive map representation: they are readily available for most buildings, compact, and inherently invariant to visual appearance changes. However, bridging the severe domain gap between camera observations and floorplan geometry remains challenging. Existing methods address this gap through data-driven learning, yet they require large-scale training data and environment-specific retraining, limiting their practical deployment. We propose a zero-shot floorplan localization method that generalizes to novel environments without any retraining. Our key insight is that dominant geometric primitives -- lines and circles -- are ubiquitous in human-made environments and provide appearance-invariant structural constraints. We extract these primitives from a bird's-eye-view (BEV) projection of monocular 3D reconstructions and match them to the floorplan via dedicated minimal solvers within a robust estimation framework. Experiments on both simulated and real-world datasets show that our approach outperforms state-of-the-art learning-based methods on unseen environments, while using a single fixed set of hyperparameters across all experiments. The source code will be made publicly available.
### Title:
          UModel: An Agent-Ready Observability Data Modeling Method at Scale
 - **Authors:** Changhua Pei, Zheyuan Li, Zexin Wang, Hang Cui, Xiaohui Nie, Qi Zhou, Fang Situ, Cheng Zhang, Xin Zhang, Xidao Wen, Gaogang Xie, Jingjing Li, Dan Pei
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 When networked system failures occur, automatically performing Root Cause Analysis (RCA) using observability data is critical for ensuring networked system reliability. Recently, LLM-based agents have shown promise for automating this diagnosis process through advanced reasoning and autonomous exploration. However, existing observability frameworks remain archaic, characterized by fragmented data silos, incompatible schemas, and insufficient semantic metadata, preventing agents from establishing the complex relationships required for effective RCA. To address these challenges, we present UModel, a unified ontological framework that shifts observability from data-centric to object-centric modeling. UModel constructs a virtual ontological layer where heterogeneous telemetry, entities, and expert knowledge are standardized as objects and interconnected via semantic graphs. In addition, we introduce U-SPL, a pipeline-based query interface that enables agents to autonomously explore system topologies and correlate multimodal data. By re-modeling the "AIOps 2025 Challenge" dataset using UModel, the precision of root cause localization improved by 8%, demonstrating that enhanced data organization can significantly increase the accuracy of downstream tasks. UModel provides a scalable modeling framework that, in its deployment at Alibaba Cloud for more than one year, has served tens of thousands of users, sustained millions of operations per second, and delivered sub-second query latency.
### Title:
          R-APS: Compositional Reasoning and In-Context Meta-Learning for Constrained Design via Reflective Adversarial Pareto Search
 - **Authors:** João Pedro Gandarela, Thiago Rios, Stefan Menzel, André Freitas
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) are fluent on open-ended tasks, yet in agentic settings, where a system must plan, use tools, and act over extended horizons, fluency does not ensure reliable delivery. We trace this gap to three coupled structural failures: errors propagate without localization, worst-case perturbations go unevaluated, and accumulated knowledge is never invalidated. We argue these share a root cause: abductive, counterfactual, meta-inductive, corrective, and inductive reasoning pull a shared context in incompatible directions. We introduce Reflective Adversarial Pareto Search (R-APS), to our knowledge the first method addressing all three failures jointly via reasoning-mode decomposition, allocating each reasoning mode its own context and orchestrating interaction across three timescales: staged compositional reasoning with a typed validation critic (failure localization), sensitivity-guided counterfactual stress-testing as a first-class Pareto objective (robustness), and meta-inductive rule extraction with explicit invalidation (persistent memory). R-APS requires no fine-tuning and operates on a frozen LLM purely via structured protocol design. We evaluate on planar mechanism synthesis (robotics, prosthetics, mechanical design), with every candidate checked by a kinematic solver. On 32 target trajectories, R-APS delivers robustness certificates 3.5x tighter than uniform-perturbation baselines, 46% faster iterations-to-first-admission, and 2.1x Chamfer-distance reduction over Enum+GA while jointly controlling bar-count and worst-case robustness. Small 4B reasoning-specialized models prove competitive with general-purpose 70B backbones inside the protocol, suggesting structured protocols can partially offset model scale.
### Title:
          Consistent Distributed Cooperative Localization for Ultra Large-Scale Multi-agent Systems
 - **Authors:** Leonardo Pedroso, W. P. M. H. Heemels, Pedro Batista
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cooperative localization (CL) is fundamental in emerging multi-agent systems, where agents fuse local sensing data with exchanged information to estimate their own states. At a large scale, however, tracking cross-correlations becomes infeasible, preventing the use of optimal filters. Ignoring or underestimating these correlations leads to overconfident, and thus inconsistent, estimates. Existing CL algorithms achieve good performance and consistency typically at the expense of communication, computation, or memory that scales with the network size. This is incompatible with ultra large-scale systems (ULSS) - for example, satellite mega-constellations - where per-agent resources are limited and must remain independent of the number of agents. This reveals a critical gap: no existing CL method is simultaneously well-performing, consistent, and ULSS-scalable. This paper introduces a new CL framework that addresses this gap using the recently proposed overlapping covariance intersection methodology, which enables agents to exploit limited structural information about cross-correlations without compromising consistency. The resulting CL algorithm leads to optimal conservative covariance propagation using only locally available information. The method is fully distributed, scalable to an ultra large scale, and provably recursively consistent. Simulations demonstrate substantial performance improvement over state-of-the-art consistent CL approaches while preserving scalability.
### Title:
          HD-DinoMoE: A Class-Aware Hierarchical Dual Mixture-of-Experts Network for Scleral Anomaly Segmentation in Complex Acquisition Scenarios
 - **Authors:** Yinxiang Yu, Maoxiang Chu, Qi Niu, Guanghu Liu, Wei Xu, Haotian Wang, Zhi Chen, Yutian Zhu, Yuelong Fan, Guanghao Liao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traditional Chinese Medicine (TCM) ocular inspection provides empirical cues for assessing scleral surface anomalies, but its clinical use remains subjective and difficult to quantify. To support intelligent and quantifiable ocular inspection, this study presents the TCM-inspired Artificial Intelligence Ocular Auxiliary Diagnosis System (TAO) and focuses on pixel-level scleral surface anomaly segmentation. For clinical and user-acquired images affected by multi-source distributional discrepancies, diverse anomaly morphologies, and scleral specular reflection (SSR), we propose HD-DinoMoE, a class-aware hierarchical dual mixture-of-experts network. HD-DinoMoE combines class-aware dual-stream DINOv3 feature fusion with class-specific multi-expert decoding to segment Vessels, Yellow and Black Spots, and Blood Spots. A three-stage backbone-frozen routing strategy stabilizes dual-backbone adaptation; Progressive Confidence Penalty (PCP) Loss reduces high-confidence false positives and segmentation leakage in SSR regions; and Class-Aware Adaptive Sample Weighting (CA-ASW) balances sample- and class-level training contributions. We further construct the Multi-label Scleral Anomaly Segmentation Dataset (ML-SASD), a new benchmark with Clinical, Wild, and Mix settings and pixel-wise annotations for three anomaly categories. On ML-SASD-Mix, HD-DinoMoE achieves a mean Dice of 72.11% and a mean Intersection-over-Union of 58.44%, while maintaining favorable boundary localization and specular-region false-positive control. It also shows competitive generalization on the Vessels subset of the public SBVPI dataset. These results indicate that HD-DinoMoE provides a feasible segmentation solution for TAO under complex acquisition scenarios. The code and data access information are available at this https URL.
### Title:
          Multi-Camera AR Guidance System for Surgical Instrument Handling and Assembly: Investigating Workload and Efficiency
 - **Authors:** Shiyu Li, Julian Kreimeier, Hannah Schieber, Dirk Müller, Bernhard Kainz, Rüdiger von Eisenhart-Rothe, Daniel Roth
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The handling and assembly of instruments during surgery imposes high cognitive demands on scrub nurses, particularly when instruments are unfamiliar. We present a supporting guidance system for surgical instrumentation that combines multi-camera 6D pose estimation with augmented reality in-situ visualization on a head-mounted display without the requirement for additional markers. Pose estimation and consecutive camera calibration are achieved through known objects. The 6D pose estimation network is trained purely on synthetic data, aiming for better generalizability and real-world applicability. The AR guidance displays tooltip localization cues and step-wise assembly animations. Via gaze-based selection and a foot pedal, users can switch between assembly steps in intraoperative use. In a technical evaluation, our approach outperforms state-of-art 6D pose estimation. A user study with 29 scrub nurses was conducted in a surgical simulation of knee arthroplasty, comparing the system against a paper manual. AR guidance significantly reduced the perceived workload compared. Objectively, AR guidance reduced task completion time by 21.3\% (4.76 minutes). Specifically, scrub nurses less experienced with the instrument set benefited when using the system. Error frequencies were comparable between conditions. Qualitative feedback highlighted improved process clarity, reduced information overload, and perceived independence. To summarize, our marker-free multi-camera AR guidance approach for surgical instruments can, subjectively and objectively, improve intraoperative instrumentation performance, particularly for untrained scrub nurses.
### Title:
          TeleSWEBench: A Commit-Driven Benchmark for Evaluating LLM-Powered Software Engineering in Telecommunications
 - **Authors:** Pranshav Gajjar, Ali Mamaghani, Dinesh Bharadia, Vijay K Shah
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the telecommunications field embracing zero touch management alongside novel O-RAN and AI-RAN frameworks, contemporary telecom networks now function as immensely intricate and heavily softwareized codebases. While automated software engineering (ASE) tools and Software Engineering (SWE) Agents hold the potential to alleviate the critical code generation bottleneck in this domain, their ability to navigate and modify specialized, mathematically rigorous wireless stacks like srsRAN 5G remains unverified. General-purpose coding benchmarks fail to capture the stateful logic and strict requirements of telecommunications, leaving a critical evaluation gap. In this paper, we introduce TeleSWEBench, the first commit-driven benchmark specifically designed to measure an agent's performance in the telecom domain. We mine real developer commits from the srsRAN 5G repository and distill them into structured test cases across three difficulty tiers (Easy, Medium, and Difficult). Our benchmark consists of 734 questions that are accompanied by executable unit tests. To avoid the rigidity of test cases, we further propose a hierarchical LLM as a Judge framework called TeleJudge that scores agent outputs at the file level and aggregates verdicts holistically. This follows an evaluation based on context and semantic similarity in parallel to a standard unit test-based evaluation. Using this benchmark, we evaluate AIDER, OpenHands, and the ClaudeCode frameworks, powered by state-of-the-art reasoning LLMs, including Qwen3, GPT OSS, Gemma 4, Kimi, and Qwencoder 2.5. Our two-stage evaluation reveals that models suffer from a lack of both localization accuracy and functional correctness, with the strongest ASE tools achieving up to 25% of shippable changes.
### Title:
          CIPER: A Unified Framework for Cross-view Image-retrieval and Pose-estimation
 - **Authors:** Yurim Jeon, Dongseong Seo, Seung-Woo Seo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-view geo-localization estimates the geographic location of a ground image by matching it against an aerial image database. Existing methods tackle this through either large-scale retrieval or precise pose estimation, but not both: retrieval-based methods enable wide-area search at the cost of localization accuracy, while pose estimation methods achieve high precision within only a narrow search space. Naively cascading these pipelines introduces error propagation and inconsistent feature representations. We formulate cross-view geo-localization as a unified problem requiring simultaneous city-scale retrieval and precise 3-DoF pose estimation. We propose CIPER (Cross-view Image-retrieval and Pose-estimation transformER), a single architecture that jointly performs both tasks through mutually beneficial feature learning. CIPER uses a shared transformer encoder with task-specific tokens to disentangle global retrieval features from spatial localization cues. To bridge the large domain gap between ground and aerial views, we introduce a two-way transformer pose decoder that uses ground features as spatial queries for bidirectional cross-attention. A set prediction strategy further enables stable 3-DoF regression under a unified multi-task objective. Experiments on VIGOR, KITTI, and Ford Multi-AV demonstrate competitive performance, especially under limited field-of-view and arbitrary orientation conditions. Code is available at this https URL.
### Title:
          An Open-Source Two-Stage Computer Vision Pipeline for Fine-Grained Vehicle Classification using Vision Transformers
 - **Authors:** Gandhimathi Padmanaban, Fred Feng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vehicle body type is a significant determinant of cyclist injury severity in overtaking crashes, yet automated tools for classifying vehicles into injury-risk-relevant categories from naturalistic roadway video do not exist in the open literature. Standard object detection benchmarks provide only coarse vehicle labels (car, truck, bus, motorcycle), while existing fine-grained recognition systems are trained on controlled imagery and lack evaluation for deployment robustness across recording sites. This paper presents an open-source two-stage computer vision pipeline combining a pre-trained RT-DETR detector for coarse vehicle localization with a fine-tuned Vision Transformer (ViT-Base/16) for six-category body-type classification: passenger car, SUV, pickup truck, minivan, large van, and commercial truck. A confidence-based abstention mechanism withholds Stage 2 predictions when softmax output falls below 0.60, producing unknown labels rather than silent misclassifications. Evaluated on 3,805 annotated overtaking events from a bicycle-lane corridor in Ann Arbor, Michigan (in-distribution), the pipeline achieved 0.94 accuracy with per-class F1 scores from 0.91 (minivan) to 0.97 (SUV). On an independent out-of-distribution evaluation of 311 events from an open cycling dataset without retraining, accuracy was 0.89. Three of four well-represented categories maintained F1 at or above 0.90 under domain shift. The largest degradation was observed for minivan (F1 = 0.72), driven by abstention rate rising from 2.4% to 25.0% rather than active misclassification, consistent with the mechanism propagating genuine model uncertainty. The full pipeline, including inference scripts, training code, evaluation utilities, and model weights, is released as open-source software to support reproducibility and reuse across roadside video archives and cycling safety research.
## Keyword: transformer
### Title:
          Do Transformers Need Three Projections? Systematic Study of QKV Variants
 - **Authors:** Ali Kayyam, Anusha Madan Gopal, M Anthony Lewis
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Performance (cs.PF)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers have become the standard solution for various AI tasks, with the query, key, and value (QKV) attention formulation playing a central role. However, the individual contribution of these three projections and the impact of omitting some remain poorly understood. We systematically evaluate three projection sharing constraints: a) Q-K=V (shared key-value), b) Q=K-V (shared query-key), and c) Q=K=V (single projection). The last two variants produce symmetric attention maps; to address this, we also explore asymmetric attention via 2D positional encodings. Through experiments spanning synthetic tasks, vision (MNIST, CIFAR, TinyImageNet, anomaly), and language modeling (300M and 1.2B parameter models on 10B tokens), we discovered that our transformers perform on par or occasionally better than the QKV transformer. In language modeling, Q-K=V projection sharing achieves 50% KV cache reduction with only 3.1% perplexity degradation. Crucially, projection sharing is complementary to head sharing (GQA/MQA): combining Q-K=V with GQA-4 yields 87.5% cache reduction, while Q-K=V + MQA achieves 96.9%, enabling practical on-device inference. We show that Q-K=V preserves quality because keys and values can occupy similar representational spaces and attention operates in a low-rank regime, whereas Q=K-V breaks attention directionality. Our results systematically characterize projection sharing as an underexplored instance of weight tying in attention, with direct, quantifiable inference memory benefits, particularly valuable for edge deployment. The code is publicly available at this https URL
### Title:
          Unlocking Feature Learning in Gated Delta Networks at Scale
 - **Authors:** Yifeng Liu, Quanquan Gu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Training and scaling Large Language Models demand enormous computational resources, motivating both efficient sub-quadratic architectures and principled hyperparameter tuning methods. While the Maximal Update Parametrization ($\mu$P) has enabled zero-shot hyperparameter transfer for standard Transformers, its extension to linear models, particularly those with structured state transitions and complicated architectures, remains largely unexplored. By rigorously propagating coordinate-size estimates through the forward pass, gating mechanisms, and recurrent state dynamics, we derive the scaling rules for Gated Delta Network. Experiments on language-model pre-training confirm that our configurations enable stable learning-rate transfer across model widths under both AdamW and SGD, whereas standard parametrization fails to transfer, validating the correctness and practical utility of our analysis.
### Title:
          Adaptive Patching Is Harder Than It Looks For Time-Series Forecasting
 - **Authors:** Federico Zucchi, Yi Xie, Chao Zhang, Keyuan Luo, Thomas Lampert, Ziyue Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adaptive patching is a recent and compelling proposal for time-series Transformers: allocate finer patches where the sequence looks locally informative. This paper asks under what conditions a content-adaptive patching operator should outperform a tuned uniform one. Local heterogeneity alone is not enough: under pointwise forecasting losses, a complex-looking region is not automatically one where finer patching reduces the loss. We model patching as a budgeted bitrate allocation and derive an explicit threshold that a dynamic patching rule must satisfy to beat a well-tuned uniform baseline, then bound the achievable improvement both locally (a quadratic surrogate) and globally (a strong-convexity bound under the model's assumptions). Two structural results follow: without a coupling constraint, scalar local complexity cannot produce a non-uniform optimum under a common loss landscape; and once the backbone is trained to its representation-aware optimum, the alignment gain collapses around a well-tuned uniform patch size. To test these predictions, we run a controlled isolation study on three representative architectures, replacing each adaptive mechanism with a uniform patch-size sweep while keeping the backbone, data, and training protocol fixed. On standard long-horizon forecasting benchmarks, the validation-selected uniform baseline is competitive with the dynamic counterpart, with per-setting effects concentrated near zero and no consistent directional advantage once results are aggregated by dataset. The larger gains we do observe are method- and dataset-specific. Adaptive patching should therefore be evaluated against a tuned uniform baseline; its value depends on whether a cheap and reliable routing signal can identify where finer patches actually reduce forecasting loss.
### Title:
          Instant-Fold: In-Context Imitation Learning for Deformable Object Manipulation
 - **Authors:** Yilong Wang, Cheng Qian, Edward Johns
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deformable object manipulation (DOM) is challenging due to high-dimensional, partially observable states that evolve through long-horizon, topology-changing interactions with multiple valid manipulation modes. We introduce Instant-Fold, an in-context imitation learning framework for DOM. Given a single human demonstration, our policy infers and executes diverse manipulation modes directly from the demonstration, including variations in spatial execution and ordering, without requiring gradient updates. Our approach first learns deformation-aware visual representations via temporal contrastive pretraining, after which a flow-matching transformer policy conditioned on the demonstration predicts actions to execute the intended manipulation mode. Trained entirely in simulation, Instant-Fold generalizes across diverse folding modes and transfers zero-shot to real-world settings without additional data collection or finetuning. Videos are available at this https URL.
### Title:
          OpenRFM: Dissecting Relational In-Context Learning
 - **Authors:** Zhikai Chen, Junyu Yin, Jialiang Gu, Siheng Xiong, Xiaoze Liu, Ruowang Zhang, Keren Zhou, Kai Guo
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Relational Foundation Models (RFMs) promise a single pre-trained predictor that, given any relational database, returns predictions in one forward pass via relational in-context learning (ICL). Yet a substantial gap separates open RFMs from their commercial counterparts, and the origin of this gap has not been systematically understood. We dissect a representative framework, the Relational Transformer (RT), from two perspectives. Model side: we show that RT performs relation-level ICL, and a kernel regression view shows it fails when sparse label-cell coverage yields an underdetermined regression. Data side: we ablate RT's pre-training source and find that existing synthetic-only pre-training and in-distribution pre-training drive the same architecture into different regimes, lazy vs. feature-learning. Probing this gap reveals that the missing ingredient is a support-identifiable relational latent in the label-generation process. These two diagnoses translate into (1) a dual-stage ICL architecture that combines the relational backbone with a batch-level ICL layer lifted from a pre-trained tabular foundation model to overcome relation-level label scarcity, and (2) a homophily-aware synthetic plus continual real-data pre-training mixture, augmented with a prototype-based regularization. These choices define OpenRFM, a simple yet effective RFM that improves average task performance by approximately 30% over the RT backbone and surpasses the commercial model KumoRFMv1 on a large set of evaluation tasks.
### Title:
          Parameter-Efficient Fine-Tuning with Learnable Rank
 - **Authors:** Arpit Garg, Simon Lucey, Hemanth Saratchandran
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Low-Rank Adaptation (LoRA) is a popular parameter-efficient fine-tuning (PEFT) method that restricts weight updates to low-rank adapters, introducing a fixed low-rank inductive bias by optimizing in a low-dimensional subspace. In this work, we question whether a fixed-rank constraint is the most effective inductive bias for parameter-efficient fine-tuning. We introduce *Learnable Rank LoRA (LR-LoRA)*, a PEFT method in which the adapter rank is learned during the training process. Instead of prescribing a uniform rank for all adapter layers, LR-LoRA allows the optimizer to determine the appropriate rank for each layer. Using this approach, we find substantial layer-wise variation in the learned ranks, with the attention and MLP layers in the transformer models exhibiting systematically different rank preferences. Across a range of language understanding and commonsense reasoning benchmarks, LR-LoRA achieves state-of-the-art performance in most settings and consistently outperforms strong PEFT baselines, demonstrating that a learnable rank provides a more flexible and effective inductive bias than fixed-rank adaptations.
### Title:
          Generalizable Multi-Task Learning for Wireless Networks Using Prompt Decision Transformers
 - **Authors:** Fatih Temiz, Shavbo Salehi, Melike Erol-Kantarci
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Future wireless networks demand rapid adaptation to highly heterogeneous environments and dynamic task configurations, necessitating a shift from conventional rule-based and optimization-driven radio resource management (RRM) toward artificial intelligence (AI)-driven RRM. AI-driven approaches can learn complex nonlinear relationships, generalize across diverse network conditions and enable real-time, scalable and autonomous decision-making. Among RRM techniques, coordinated multipoint (CoMP) transmission is pivotal for mitigating inter-cell interference and enhancing cell-edge performance, thereby improving quality of experience (QoE) in dense deployments. However, optimal multi-cell selection remains a complex combinatorial challenge as it requires jointly optimizing over many possible serving-cell combinations under dynamic traffic and channel conditions. Despite their success, conventional deep reinforcement learning (DRL) methods such as proximal policy optimization (PPO) suffer from poor sample efficiency, limited generalization, and costly retraining when state and action spaces change. To address these bottlenecks, we propose a Prompt Decision Transformer (PromptDT) based multi-task learning framework capable of learning across diverse network configurations and reformulating multi-cell selection as a sequence modeling problem. By leveraging offline trajectories and task-specific prompts, PromptDT enables scalable learning across diverse network configurations, including varying base stations and user equipment counts, and scheduler policies. Experimental results demonstrate that PromptDT improves QoE by up to 49% in multi-task settings compared to baselines, with performance scaling positively alongside model capacity. Moreover, PromptDT generalizes effectively to unseen tasks, achieving robust few-shot adaptation to new network configurations without retraining or fine-tuning.
### Title:
          Spatially Grounded Concept Bottleneck Models via Part-Factorized Attention
 - **Authors:** Dhanesh Ramachandram
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Concept bottleneck models (CBMs) predict a layer of human-named attributes before predicting a class, which makes their decisions auditable. On fine-grained recognition tasks the concept heads are usually free to attend anywhere in the image, so a head named for one body region can be satisfied by evidence on another. This work studies a part-factorized CBM that removes that freedom by construction. The method has three components built on a frozen DINOv3 vision transformer. A learned foreground gate, trained on DINOv3 patch features, suppresses background patches inside the part attention. A set of part queries cross-attends to patch features and each of the 312 CUB attributes is routed, through a fixed concept-to-part map, to read only from the part token its name implies. A learnable two-dimensional Gaussian prior, injected additively in log space into the attention logits, breaks the permutation symmetry among part queries; its means are initialized from the dataset-average keypoint location of each part, which requires no per-image keypoint supervision at training or test time. On CUB-200-2011 the spatial-prior model matches a fully supervised baseline (88.85% versus 88.95% top-1) while raising pointing accuracy by 16 points (52.6% versus 36.4%). Replacing bounding-box supervision with a PCA foreground target and combining it with the Gaussian prior removes all per-image supervision and reaches 88.6% top-1 at about 70% pointing accuracy. A keypoint-fraction sweep shows that 0.5% of the training set (about 27 images) suffices to initialize the prior with no measurable loss. Removing part identity entirely is the harder case: without any spatial prior, pointing accuracy collapses to $2.9\%$.
### Title:
          MeshTok: Efficient Multi-Scale Tokenization for Scalable PDE Transformers
 - **Authors:** Yanshun Zhao, Xiaoyu Peng, Jiamin Jiang, Congcong Zhu, Jingrun Chen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Conventional patchified Transformers operate on uniform spatial partitions, distributing computational effort evenly across the domain irrespective of local features. This inflexible tokenization scheme is inherently limited in its ability to efficiently represent and process solutions to complex PDEs. To address this, we propose MeshTok, an adaptive mesh refinement (AMR)-inspired tokenization and sequence modeling framework. This method selectively refines spatial regions exhibiting sharp gradients, transient features, or multiscale structures, generating a heterogeneous set of multiscale tokens defined on a fixed simulation grid. These tokens are processed within a unified Transformer sequence, enabling the model to simultaneously capture coarse-grained global context and fine-grained local details without requiring specialized architectural components. Although adaptive refinement moderately increases token count, it promotes a more targeted allocation of computational resources to physically informative regions, which we view as a practical inductive bias rather than a formal optimality guarantee. Experimental evaluations across multiple PDE families and benchmark datasets demonstrate that MeshTok consistently improves the efficiency-accuracy trade-off compared to uniform-grid baselines. This suggests adaptive multiscale tokenization as a scalable and generalizable design principle for neural PDE modeling. Code is available at this https URL.
### Title:
          Selective Coupling of Decoupled Informative Regions: Masked Attention Alignment for Data-Free Quantization of Vision Transformers
 - **Authors:** Biao Qian, Yang Wang, Yong Wu, Jungong Han
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Data-Free Quantization (DFQ) addresses data security concerns by synthesizing samples, without accessing real data. It has garnered increasing attention in the context of Vision Transformers (ViTs), owing to the superiority of the self-attention mechanism compared to classical convolutional operation. However, previous DFQ arts for ViTs often suffer from a distribution mismatch between synthetic samples and input distribution expected by quantized models Q, resulting in the suboptimal performance. In this paper, we propose a novel Masked Attention Alignment approach for Data-Free Quantization of ViTs, named MaskAQ, revealing that: 1) the semantics in the self-attention mechanism is predominantly localized to a sparse subset of patches, called informative regions; 2) the informative regions dominate the mutual information between synthetic samples and Q's outputs. To these ends, we incorporate differential entropy maximum over patch similarity of synthetic samples, to decouple informative regions from noisy background. To couple with varied Q, the informative regions are selected to align full-precision models with Q via a masked attention alignment objective, thus yielding high-quality synthetic samples. Furthermore, a periodic sample refreshing strategy comes up to endow MaskAQ with the capacity to continually adapt to the evolving state of Q throughout the training process, to preserve desirable mutual information with synthetic samples. Extensive experiments verify the merits of MaskAQ over state-of-the-art approaches across multiple backbones and downstream tasks. Our code is available at this https URL.
### Title:
          Low-Rank Decay for Grokking in Scale-Invariant Transformers: A Spectral-Geometric View
 - **Authors:** Mingyu Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern Transformer architectures frequently employ normalization mechanisms such as RMSNorm and Query-Key Normalization, making parts of the model approximately scale-invariant with respect to weight magnitudes. In this regime, standard Frobenius-norm weight decay acts purely along the radial direction of the weight space and cannot directly simplify the function represented by the normalized layer. We study grokking in small algorithmic tasks through this lens and propose \emph{Low-Rank Decay} (LRD), a nuclear-norm-like spectral regularizer whose subgradient -- the polar factor $UV^\top$ -- retains a tangential component even in the scale-invariant setting. This distinction has a concrete dynamical consequence: after the model memorizes the training set and task gradients vanish, L2 decay can no longer reshape the weight spectrum, whereas LRD continues to compress singular values in an $\ell_1$-like fashion. On modular arithmetic tasks, we find that LRD induces rapid effective-rank collapse in Query/Key matrices and expands the data-fraction boundary at which delayed generalization (grokking) occurs. We further provide a spectral-geometric interpretation through the ``needle-to-fan'' expansion of the nuclear-norm subdifferential near low-rank strata.
### Title:
          Motion-Guided Causal Disentanglement for Robust Multi-View Cine Cardiac MRI Diagnosis
 - **Authors:** Chuankai Xu, Cristiane De Carvalho Singulane, Mohammad Abuannadi, Stephen Chandler, Jeremy Slivnick, Karolina Zareba, Jane Cao, Vidya Nadig, Fabio Fernandes, Seth Uretsky, Diego Perez de Arenaza, Amit Patel, Jianxin Xie
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-view cardiac magnetic resonance (CMR) imaging provides complementary anatomical information and is widely used for noninvasive disease assessment. Recent transformer-based models have demonstrated strong representation learning capabilities for CMR analysis; however, they typically learn unified latent embeddings that entangle view-specific anatomical variations with disease-related features. Such entanglement biases classifiers toward structural attributes rather than view-invariant pathological patterns. This issue is exacerbated in low-data regimes, particularly for underrepresented cardiac conditions, where limited samples increase the susceptibility to shortcut learning and view-dependent decision boundaries. To address this, we propose a Motion-Guided View--Disease Disentanglement framework MoViD built upon a ViT-MAE backbone. The model explicitly factorizes latent representations into view-specific and disease-discriminative components using dual-branch supervised contrastive objectives and a gradient-reversal adversarial constraint that minimizes disease leakage into the view embedding. Additionally, an annotation-free temporal motion feature, derived from inter-frame difference maps, is introduced to localize the beating heart region and suppress background artifacts. A focal reweighting mechanism is incorporated into the contrastive loss to mitigate class imbalance. We evaluate the framework on a private clinical venous thrombosis dataset and two public benchmarks (M&Ms, M&Ms2). Across disease classification and cardiac segmentation tasks, our approach consistently outperforms standard transformer baselines and demonstrates competitive performance against large-scale pretrained foundation models, validating the efficacy of structural disentanglement in medical image analysis.
### Title:
          DSA: Dynamic Step Allocation for Fast Autoregressive Video Generation
 - **Authors:** Thanh-Tung Le, Yunhan Zhao, Menglei Chai, Zhengyang Shen, Zhe Cao, Danhang Tang, Xiaohui Xie, Deying Kong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video diffusion transformers have achieved state-of-the-art visual quality, but their high inference cost remains a major bottleneck for real-time applications. Recent distillation frameworks produce autoregressive video diffusion models with reduced latency, yet these models still use a fixed number of denoising steps per frame, wasting computation on predictable frames and under-refining challenging ones. We present DSA, a confidence-guided adaptive computation framework for AR video diffusion. DSA introduces a lightweight confidence head, trained jointly with the generator under a distribution-matching distillation objective, to estimate per-frame denoising reliability. At inference, this confidence signal dynamically adjusts the number of diffusion steps: simple frames terminate early for speed, while complex frames receive additional refinement. Our method requires no extra video data, no heuristics, and little architectural modification. Experiments show that DSA achieves real-time autoregressive video generation, reaching 22.63 FPS with sub-second latency on H100 GPUs, while maintaining competitive or superior VBench quality compared to recent autoregressive and bidirectional video diffusion models. Our results demonstrate that confidence-guided adaptive sampling provides an effective and practical path toward interactive video generation.
### Title:
          ChannelTok: Efficient Flexible-Length Vision Tokenization
 - **Authors:** Sukriti Paul, Arpit Bansal, Tom Goldstein
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Leading flexible vision tokenizers achieve SOTA quality at an extreme cost, relying on parameter-heavy backbones and slow, multi-step generative decoders. We depart from this complex, spatial-token paradigm and introduce a simple, lightweight, and fast channel-wise flexible-length tokenizer. Our method treats each latent channel as a visual token, enabling a parameter-efficient CNN-Transformer hybrid backbone. Furthermore, employing a stochastic tail-dropping paradigm during training naturally forces channels to organize by semantic importance. This allows for flexible compression at inference by simply retaining the first $k$ channels, and naturally enables variable-length autoregressive image generation. We validate our approach through extensive experiments on ImageNet, demonstrating consistent quality across diverse token budgets. The results establish a new quality-efficiency frontier: our model achieves state-of-the-art perceptual quality (rFID 2.92) while being $8.6\times$ faster in decoding and $2.1\times$ smaller (159M params) than the next-best alternative. Our work establishes channel-wise tokenization as a powerful and practical paradigm for efficient visual representation. Project page: this https URL
### Title:
          ChessMimic: Per-Rating Transformer Models for Human Move, Clock, and Outcome Prediction in Online Blitz Chess
 - **Authors:** Thomas Johnson
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present ChessMimic, a system of three small encoder-only transformers - for move, thinking-time, and outcome prediction - conditioned on the position, recent move history, player rating, and clock state. We fit a separate instance of each model per 100-Elo rating band, trading parameter efficiency for sharper per-skill calibration. On a held-out month-wide slice of Lichess Rated Blitz games ChessMimic's human move prediction accuracy outperforms Maia-2 in every Elo band. Compared to Maia-3, our 9M parameter model's accuracy sits between Maia-3-5M and Maia-3-23M without the additional complexity of Geometric Attention Bias. In addition to the move matching model, we also train a game outcome model that conditions not only on the position, but also player ratings, time control, and remaining clock times. The outcome model achieves an AUC of 0.78 out of sample, beating Maia-2 as well as logistic regressions based on material, ratings, and clock time. Finally, we train a clock model that predicts human thinking times. The clock model provides a usable but non-SOTA per-ply think-time signal under ALLIE-style filters (Pearson r = 0.41, Spearman rho = 0.50, MAE 4.10 s, against ALLIE's reported r = 0.70), with the residual gap concentrated in per-position bucket sharpness rather than bucket-marginal calibration. A public demo is at this http URL and we release code, per-band weights, and the C++ data-filter pipeline code in GitHub.
### Title:
          Echo-Infinity: Learning Evolving Memory for Real-Time Infinite Video Generation
 - **Authors:** Yuxuan Bian, Zeyue Xue, Songchun Zhang, Shiyi Zhang, Weiyang Jin, Yaowei Li, Junhao Zhuang, Haoran Li, Jie Huang, Haoyang Huang, Nan Duan, Qiang Xu
 - **Subjects:** Subjects:
Multimedia (cs.MM); Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Echo Infinity, an autoregressive (AR) framework towards real-time infinite video generation that employs a learnable evolving memory to dynamically filter, abstract, and compress any-length history at constant cost. Existing methods mainly curate memory with predefined KV-cache schedules, fixed-ratio heuristic compression, or inference-time RoPE adaptation. These designs inevitably lose historical information and amplify compounding errors due to their limited cache window and ignorance of autoregressive generation noise. Inspired by human memory consolidation, Echo-Infinity replaces handcrafted memory curation with learnable Memory Query, which are updated by attention and a gating mechanism when past frames are evicted from the local window. The queries are optimized end-to-end with the video diffusion transformers (DiTs), forming an evolving memory that supports arbitrary compression ratios with constant computation independent of video length. They also act as a generalizable generation prior, improving quality even when only the optimized initial state is used. We further introduce Unified Relative RoPE Recipe, which anchors the sink frames to start from id 0 and lets the newest frame id grow at most to the DiTs' pretrained maximum temporal RoPE id throughout training and inference, freeing the model from the finite RoPE constraint and closing the train-test RoPE extrapolation gap. In long and short video generation, Echo-Infinity achieves state-of-the-art performance, and, to our knowledge, demonstrates promising 24-hour (>1.3 M frames) real-time rollouts for the first time, suggesting a practical path toward infinite video generation.
### Title:
          LDARNet: DNA Adaptive Representation Network with Learnable Tokenization for Genomic Modeling
 - **Authors:** Daria Ledneva, Denis Kuznetsov
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Genomics (q-bio.GN)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Genomic foundation models increasingly adopt large language model architectures, yet almost universally rely on fixed tokenization schemes such as $k$-mers, BPE, or single nucleotides, which impose arbitrary sequence boundaries that may obscure biologically relevant structure. We present LDARNet, a 120M-parameter hierarchical genomic foundation model that adapts H-Net-style dynamic chunking from autoregressive generation to masked language modeling, combining BiMamba-2 state-space layers with local attention, bidirectional routing, and a ratio-based regularizer to induce adaptive token boundaries without supervision. Fine-tuned on 27 tasks from the Nucleotide Transformer and Genomic Benchmarks suites, LDARNet achieves 11/18 wins among compact models ($<$300M parameters) and state-of-the-art results on 5 histone modification tasks, outperforming models up to 20$\times$ larger. A FLOPs-matched controlled experiment isolates learned routing as the source of these gains: learned boundaries beat fixed-grid boundaries by up to 14 percentage points on histone tasks at identical compute. Nucleotide-resolution analysis further shows that the learned boundaries align with canonical promoter motifs and splice junctions without supervision, providing a biological interpretation for adaptive tokenization in genomic foundation models.
### Title:
          MeshFlow: Efficient Artistic Mesh Generation via MeshVAE and Flow-based Diffusion Transformer
 - **Authors:** Weiyu Li, Antoine Toisoul, Tom Monnier, Roman Shapovalov, Rakesh Ranjan, Ping Tan, Andrea Vedaldi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present MeshFlow, a new method for generating artist-like 3D meshes. Current mesh generators often adopt Auto-Regressive (AR) next-token prediction, a natural choice given the discrete nature of mesh topology. However, AR methods scale poorly because the inference cost is quadratic in mesh size. They also require discretizing the vertex coordinates, which introduces quantization errors. To address these challenges, we introduce a Variational Autoencoder (VAE) that, supervised with a contrastive loss, represents both continuous vertex positions and discrete connectivity in a continuous latent space. This latent space is significantly more compact than prior token-based mesh representations. We then build a 3D generator based on a Rectified Flow transformer, generating all mesh vertices and edges in parallel. Our model generates meshes 18x faster than the fastest AR generator while also achieving excellent accuracy across standard mesh-generation metrics. Homepage: this https URL, Code: this https URL
### Title:
          Test-Time Compute Scaling for ASR with Depth-Conditioned Looped Transformers
 - **Authors:** Yacouba Kaloga, Shashi Kumar, Shakeel A. Sheikh, Driss Khalil, Petr Motlicek, Ina Kodrasi
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end ASR systems typically use fixed-depth acoustic encoders at inference, making it difficult to trade additional test-time computation for improved recognition without training a larger model. A natural approach is to reuse a shared Transformer block recurrently, but we find that naive looping does not fully exploit additional recurrent compute. We introduce LARM, a depth-conditioned looped Transformer that turns recurrent encoder depth into a controllable test-time compute axis. LARM combines sparse CTC checkpoints, supervision-clock embeddings, FiLM depth conditioning, and delayed soft-posterior feedback. These components structure the loop into recognition checkpoints separated by latent refinement phases and allow shared weights to specialize across recurrent steps. On LibriSpeech, LARM improves WER as the number of inference loops increases and achieves performance competitive with deeper unshared-parameter baselines. Our results show that test-time compute scaling can extend beyond autoregressive language-model reasoning to continuous non-autoregressive speech recognition.
### Title:
          Query-based Cross-Modal Projector Bolstering Mamba Multimodal LLM
 - **Authors:** SooHwan Eom, Jay Shim, Gwanhyeong Koo, Haebin Na, Mark A. Hasegawa-Johnson, Sungwoong Kim, Chang D. Yoo
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Transformer's quadratic complexity with input length imposes an unsustainable computational load on large language models (LLMs). In contrast, the Selective Scan Structured State-Space Model, or Mamba, addresses this computational challenge effectively. This paper explores a query-based cross-modal projector designed to bolster Mamba's efficiency for vision-language modeling by compressing visual tokens based on input through the cross-attention mechanism. This innovative projector also removes the need for manually designing the 2D scan order of original image features when converting them into an input sequence for Mamba LLM. Experimental results across various vision-language understanding benchmarks show that the proposed cross-modal projector enhances Mamba-based multimodal LLMs, boosting both performance and throughput.
### Title:
          Contrastive Learning and Correlation Clustering for Sequences of Network Telescope Data
 - **Authors:** Jannik Presberger, Alexander Männel, Maynard Koch, Thomas C. Schmidt, Matthias Wählisch, Bjoern Andres
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding activities of Internet scanners is challenging; it often requires identifying relationships between sources, a task for which semantic annotations are scarce. This work investigates whether semantically meaningful pairwise relationships between sequences of network flow records can be estimated by contrastive learning, without pretraining and without annotations. To this end, we propose a transformer model that embeds minimally preprocessed sequences of network flow records and train it using contrastive learning. With the similarities obtained from this model, we state a correlation clustering problem and solve it locally. Experimentally, we show: Learned similarities are higher on average for sequences originating from the same source than for sequences originating from different sources, and this property generalizes to unseen sequences of unseen sources. Moreover, correlation clustering yields clusters consistent with scanner labels. The complete source code of the algorithms and for reproducing the experiments is publicly available.
### Title:
          An Empirical Audit of Input Encoders for Multi-Channel Signal Transformers
 - **Authors:** Ossi Lehtinen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers consuming multi-channel scalar signals must embed $C$ simultaneous values into one $d_{\text{model}}$-dimensional vector per time step. We empirically audit eight input encoders -- spanning a shared-scalar baseline, per-channel linear projections, an orthogonality regulariser, a nonlinear MLP stem, block-partitioned concatenation, channel-independent and channel-as-token architectures, and a projected positional encoding -- on a synthetic benchmark designed to make channel identity informative and on ETTh1 as a real-data check, measured in next-step negative log-likelihood (NLL). The headline is one of practical near-equivalence within a wide "top tier": the standard per-channel linear projection (this http URL(C, $d_{\text{model}}$)) matches every alternative in that tier up to small, statistically real but practically modest, differences. Two encoders lose decisively: the shared-scalar baseline, which collapses for information-theoretic reasons we make explicit, and the channel-independent PatchTST-spirit baseline, which underperforms on both benchmarks and overfits universally on the synthetic one. Paired tests resolve two small gaps: projecting the sinusoidal positional encoding through a learned linear layer edges the rest at small $C$, with a direct geometric probe showing the mechanism is positional-channel orthogonalisation; a nonlinear MLP stem edges them at the largest $C$ we test, with the gap shrinking under more training data. The practical recommendation is to use this http URL(C, $d_{\text{model}}$) by default and reach for something more elaborate only when the task at hand gives a real reason to do so. Code and data to reproduce every experiment in this paper are available at this https URL
### Title:
          Measuring Model Robustness via Fisher Information: Spectral Bounds, Theoretical Guarantees, and Practical Algorithms
 - **Authors:** Chong Zhang, Xiang Li, Jia Wang, Qiufeng Wang, Xiaobo Jin
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The robustness of deep neural networks is crucial for safety-critical deployments, yet existing evaluation methods are often attack-dependent and lack interpretability. We propose a principled, attack-agnostic robustness metric based on the spectral norm of the Fisher Information Matrix (FIM), which quantifies the worst-case sensitivity of the model's output distribution to input perturbations. Theoretically, we establish that the FIM equals the variance of the input Jacobian and derive closed-form spectral bounds for common architectures, including VGG, ResNet, DenseNet, and Transformer, providing the first theoretical robustness ranking. To enable scalable evaluation, we develop efficient algorithms, including power iteration and Hutchinson-based estimation, that support both white-box and black-box settings. Extensive experiments across multiple datasets, including CIFAR, ImageNet, and medical images, and across multiple architectures show a strong correlation between our metric and adversarial vulnerability. Our framework serves as an interpretable diagnostic tool that complements attack-based evaluations, offering insights into architectural sensitivity and guiding the design of more robust models. Code is available at: this https URL.
### Title:
          Signed Dual Attention: Capturing Signed Dependencies in Time Series Forecasting
 - **Authors:** Balthazar Courvoisier, Tristan Cazenave
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Initially developed for natural language processing, Transformer architectures and attention mechanisms are now central to a wide range of deep learning models, including applications in time series forecasting. A standard attention mechanism, however, implicitly assumes homophilic interactions, limiting its ability to model data with positive and negative dependencies, such as time series. In this work, we introduce the Signed Dual Attention, a novel attention formulation that captures both positive and negative relational patterns without additional parameters. By leveraging a dual message-passing scheme inspired by correlation structures, Signed Dual Attention propagates both supportive and contrastive information within a single shared block, effectively achieving the expressiveness of two head attention without additional parameters. This module can be seamlessly integrated into existing architectures and can yield performance gains in certain situations, requiring signed relational modeling. This approach opens a pathway toward more expressive and parameter-efficient transformers.
### Title:
          Rethinking Incompleteness: Formalizing Protocol Divergence and Train-Once Learning for Robust IMVC
 - **Authors:** Haolu Liu, Xiyue Wang, Xuanting Xie, Liangjian Wen, Zhao Kang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Standard IMVC evaluation retrains separate models for different missing-data configurations. We show that this paradigm obscures a fundamental vulnerability: missing rate alone is insufficient to characterize data incompleteness. Specifically, we show that protocols with identical nominal missing rates can differ by up to $50\times$ in their proportion of fully observed samples, inducing drastically different learning regimes. We formalize this phenomenon as incompleteness divergence, providing measures that capture structural disparities across missing-data protocols. We further prove that for a broad class of reconstruction-based objectives, learning becomes structurally ill-posed when the proportion of complete samples falls below a critical threshold, leading to near-random performance. To bypass this theoretical bound, we propose CRAFT (Complete-data Robust Attention-masked Fusion Transformer). CRAFT shifts the burden of robustness from the loss function to the architecture via two key properties: (i) per-sample independence, which removes reliance on complete-sample co-occurrence, and (ii) mask-aware variable-length fusion, which aggregates only observed views through attention masking. This design allows a single model, trained once on complete data, to generalize to diverse missing patterns at inference time without retraining. Extensive experiments on seven benchmarks show that CRAFT matches or outperforms per-configuration baselines while reducing training overhead by $8.8\times$, demonstrating that robustness to missing data can be achieved as an inherent architectural property. Code (CRAFT) and our imvc-audit toolkit are available at this https URL and this https URL.
### Title:
          D$^3$-MoE:Dual Disentangled Diffusion Mixture-of-Experts for Style-Controllable End-to-End Autonomous Driving
 - **Authors:** Renju Feng, Rukang Wang, Ning Xi, Jianguo Yu, Liping Lu, Pan Zhou, Duanfeng Chu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traditional end-to-end autonomous driving frameworks frequently suffer from the "style-averaging" dilemma when trained on high-variance human demonstrations, yielding homogenized, style-uncontrollable, and even kinematically unsafe policies. To overcome this limitation, we present D$^3$-MoE (Dual Disentangled Diffusion Mixture-of-Experts), which disentangles trajectory modeling along two complementary axes. On the behavioral axis, generation is decoupled from selection: a style-conditioned diffusion process synthesizes multi-style candidate trajectories in parallel within a single scene, allowing a downstream module to select the optimal trajectory based on user preference or an evaluation score. On the physical axis, decoupled longitudinal and lateral routers activate their respective experts during inference time, trained without manual labels using self-supervised targets from orthogonal ground-truth kinematics. These activated experts, architected as Diffusion Transformers (DiT) and equipped with style-conditioned AdaLN and asymmetric lateral-fusion cross-attention, independently predict their corresponding physical state before being reassembled into a unified, kinematically coherent trajectory. Extensive evaluations on the challenging NAVSIM benchmark demonstrate that D$^3$-MoE achieves state-of-the-art planning performance, reaching 88.2 PDMS and 84.3 EPDMS by default. Moreover, our Best-of-Three ensemble strategy effectively broadens the multi-modal solution space, raising performance to 91.3 PDMS and 87.5 EPDMS. Both quantitative and qualitative analyses jointly confirm the framework's advantages in planning quality and style controllability.
### Title:
          WAM-Nav: Asymmetric Latent World-Action Modeling for Unified Visual Navigation
 - **Authors:** Ning Yang, Yan Huang, Kaiwen Peng, Ziheng He, Kai Wang, Cui Miao, Kailin Lyu, Guo Li, Xiaofeng Wang, Zheng Zhu, Jing Liu, Nianfeng Liu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual navigation requires generating smooth and collision-free trajectories under complex geometric and physical constraints. Existing reactive policies that directly map observations to actions lack anticipatory reasoning, limiting their ability to proactively avoid obstacles. While visual imagination offers predictive foresight, conventional modular approaches separate scene prediction from policy learning, often leading to error accumulation and inefficient inference. To address these limitations, we propose WAM-Nav, a Latent World-Action Model for embodied visual navigation that jointly learns action generation and latent visual foresight, enabling more robust and foresighted navigation decisions without compromising inference efficiency. Specifically, WAM-Nav utilizes a shared Diffusion Transformer for asymmetric joint diffusion to concurrently generate long-horizon actions and short-horizon visual foresight, reducing the inference latency and visual error accumulation inherent in multi-step autoregressive rollouts. To further encourage smooth and consistent trajectory generation, we introduce a dual-stream contextual conditioning mechanism that integrates episode-level ego-motion history with sequential visual observations. Combined with a unified goal alignment module that preserves balanced representations across goal types, WAM-Nav naturally supports Image-Goal, Point-Goal, and No-Goal exploration within a single policy. Extensive experiments on the challenging ClutterScenes and InternScenes benchmarks demonstrate strong generalization of WAM-Nav, particularly on Image-Goal and Point-Goal navigation, where it improves success rates by 15.7% and 3.3%, respectively. Real-world deployment further validates effective zero-shot sim-to-real transfer, achieving an average 85% task success rate across diverse indoor and outdoor environments.
### Title:
          CIPER: A Unified Framework for Cross-view Image-retrieval and Pose-estimation
 - **Authors:** Yurim Jeon, Dongseong Seo, Seung-Woo Seo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-view geo-localization estimates the geographic location of a ground image by matching it against an aerial image database. Existing methods tackle this through either large-scale retrieval or precise pose estimation, but not both: retrieval-based methods enable wide-area search at the cost of localization accuracy, while pose estimation methods achieve high precision within only a narrow search space. Naively cascading these pipelines introduces error propagation and inconsistent feature representations. We formulate cross-view geo-localization as a unified problem requiring simultaneous city-scale retrieval and precise 3-DoF pose estimation. We propose CIPER (Cross-view Image-retrieval and Pose-estimation transformER), a single architecture that jointly performs both tasks through mutually beneficial feature learning. CIPER uses a shared transformer encoder with task-specific tokens to disentangle global retrieval features from spatial localization cues. To bridge the large domain gap between ground and aerial views, we introduce a two-way transformer pose decoder that uses ground features as spatial queries for bidirectional cross-attention. A set prediction strategy further enables stable 3-DoF regression under a unified multi-task objective. Experiments on VIGOR, KITTI, and Ford Multi-AV demonstrate competitive performance, especially under limited field-of-view and arbitrary orientation conditions. Code is available at this https URL.
### Title:
          Depth-Attention: Cross-Layer Value Mixing for Language Models
 - **Authors:** Boyi Zeng, Yiqin Hao, Zitong Wang, Shixiang Song, He Li, Feichen Song, Yifan Liu, Ziwei He, Xinbing Wang, Zhouhan Lin
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-attention selects information freely across the sequence, but across depth, Transformers merely add each layer's output to the residual stream, so later layers cannot selectively reuse earlier-layer representations. Recent cross-layer methods improve this flow but operate on hidden states outside attention, adding state beyond the key-value cache at inference--a cost that becomes increasingly salient as modern LLMs compress the cache with grouped-query and multi-head latent attention. We introduce Depth-Attention, which performs this selection inside the attention module itself: before a layer attends over the sequence, its query attends over the keys of earlier layers at the same token position and mixes their values into the value that self-attention then reads. Because Depth-Attention reuses the standard attention queries, keys, and value-cache slots, storing depth-mixed values in place of the original values, it adds no parameters and introduces no persistent inference state beyond the standard key-value cache--the same cache size as a vanilla decoder and less than hidden-state-based cross-layer methods. On Qwen3-style decoders at 1.5B and 3B parameters, Depth-Attention attains the lowest perplexity and the highest average downstream accuracy, improving over the vanilla Transformer by up to 2.3 accuracy points and surpassing strong cross-layer baselines in perplexity and average accuracy, while adding under 0.01% extra arithmetic FLOPs and no additional persistent inference state. The gains hold from 360M to 3B parameters and extend to looped Transformers.
### Title:
          TaDA: Calibrated Probe Gating for Task-Domain LoRA Merging
 - **Authors:** Huy Quoc To, Fuyi Li, Guangyan Huang, Ming Liu
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Combining a task LoRA adapter with a domain LoRA adapter into a single unified model is a practical yet largely unexplored challenge. Existing methods treat both adapters as symmetric peers, applying uniform weights across all layers. We argue that task and domain adapters exhibit a consistent depth-dependent asymmetry across transformer architectures. Domain dominance increases with layer depth, while shallower layers retain stronger task-relevant signals. Motivated by this observation, we propose $\textbf{TaDA}$ ($\textbf{Ta}$sk-$\textbf{D}$omain LoR$\textbf{A}$ Merging), a training-free algorithm that exploits this structure through calibrated probe-guided per-layer gating and per-component subspace-aware merging. The gating assigns individual weights per layer and projection type using a probe signal proved invariant to adapter weight magnitude. The merging discards conflicting singular directions before combining the remaining components. $\textbf{TaDA}$ produces a standard rank-$r$ LoRA adapter with zero inference overhead. On six scientific QA benchmarks with Llama-2-7B, TaDA achieves an average accuracy of 0.452, outperforming DARE-TIES by +3.6 percentage points and obtaining the best result on all six benchmarks. On six image classification benchmarks with ViT-L/16, TaDA reaches 85.9\% average accuracy, improving over the strongest merging baseline while leading in three of the six individual benchmarks.
### Title:
          Imbuing Large Language Models with Bidirectional Logic for Robust Chain Repair
 - **Authors:** Zehua Cheng, Wei Dai, Jiahao Sun, Thomas Lukasiewicz
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Symbolic Computation (cs.SC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autoregressive chain-of-thought (CoT) reasoning in large language models (LLMs) is fundamentally forward-directed: each step conditions only on prior tokens. This unidirectional inductive bias renders even capable models susceptible to error snowballing, wherein a single logical or arithmetic mistake in an early step irreversibly corrupts the entire reasoning chain. We introduce Teleological Reasoning Infilling (\TRI{}), a training framework that endows decoder-only transformers with a native \emph{goal-conditioned bridging} capability. The key insight is to reframe erroneous reasoning segments as fill-in-the-middle (FIM) tasks: given a verified prefix premise $P$, a verified downstream milestone $S$, and the original query $Q$, the model must synthesise the logical bridge $M$ that connects $P$ to $S$ rigorously and completely. To achieve this with standard causal architectures, we introduce a Prefix-Suffix-Middle (PSM) sequence rearrangement with three non-overlapping sentinel tokens, enabling $M$ to attend to both $P$ and $S$ without any structural modification to the self-attention mechanism. Training proceeds in two stages: (i) Supervised Fine-Tuning (SFT) on symbolically verified $(P, S, M)$ triples extracted from formal mathematics corpora, and (ii) Direct Preference Optimisation (DPO) with a deterministic symbolic verifier (Lean 4 / Python) as the sole reward oracle, eliminating LLM-judge sycophancy. At inference, TRI operates as a surgical repair module within a dual-system loop: a causal draft model generates an initial trace, the verifier pinpoints failures, and TRI infills only the damaged segment, leaving verified sections intact. Comprehensive experiments on three benchmarks demonstrate that TRI achieves state-of-the-art performance across all tasks, while reducing per-problem token expenditure by 31.2%.
### Title:
          In-Context Graphical Inference
 - **Authors:** Zehua Cheng, Wei Dai, Jiahao Sun
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL); Symbolic Computation (cs.SC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Marginal inference in discrete graphical models forces a choice between exactness and scalability: exact algorithms are intractable for high-treewidth graphs, while iterative approximations (Belief Propagation, variational methods) sacrifice convergence guarantees on frustrated topologies. We argue that this dichotomy stems from a mismatched inductive bias: iterative methods abandon the sequential elimination structure that makes exact inference correct. We introduce In-Context Graphical Inference (ICG-I), an autoregressive Graph Transformer that restores this structure by mimicking Variable Elimination with learned, Tensor- Train-compressed intermediate factors, paired with a Dirichlet output layer and Weighted Conformal Prediction for calibrated, distribution-free coverage guarantees under topological shift. We prove that TT compression errors propagate at most lincarly through the autoregressive chain, that the Dirichlet-Multinomial loss is a proper scoring rule, and that WCP maintains coverage with a quantifiable degradation under estimated density ratios. We conducted intensive experiments to evaluate ICG-I and achieved state-of-the-art performance across all benchmarks. ICG-I reduces MAE from 0.041 (best baseline) to 0.020 on standard instances and achieves 0.048 on N=500 frustrated spin glasses where BP diverges entirely.
### Title:
          Graph Cascades: Contagion-Based Mesoscopic Rewiring for Structure-Aware Graph Machine Learning
 - **Authors:** Meher Chaitanya, My Le, Luana Ruiz
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Graph Cascades, a mesoscopic rewiring strategy for Graph Neural Networks (GNNs) and Graph Transformers (GTs) that captures intermediate-scale graph structure beyond purely local edges or fully global attention. Using contagion-based diffusion processes, Graph Cascades constructs, in O(|V|+|E|) time, an auxiliary graph where node pairs supported by repeated multi-hop reinforcement are promoted to direct neighbors. We theoretically characterize when reinforcement-based rewiring helps: sufficient conditions under which reinforcement-based edge selection is more label-aligned than direct adjacency, an SBM witness in which two-hop reinforcement is perfectly homophilic, and a formalization of mesoscopic connectivity via graph effective resistance. Empirically, across node-classification benchmarks, Graph Cascades improves multiple GNN and sparse-GT backbones, with the most reliable gains observed on heterophilic and moderate- to high-degree homophilic graphs. The theoretical conditions also identify regimes where mesoscopic rewiring is unlikely to be beneficial -- low-degree regular graphs and graphs with structural bottlenecks -- and these predictions match the observed failures. We additionally observe tight correlations between performance and structural properties in the rewired graphs.
### Title:
          Graph Set Transformer
 - **Authors:** Jose E. Escrig Molina, Baoquan Chen, Daniel Probst
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce the Graph Set Transformer (GST), a neural network architecture for learning on sets of graphs, designed for tasks in which per-element predictions depend on set-wide context as well as local structure. Existing architectures, including DeepSets and SetTransformer, require pre-encoded graph embeddings from a separate GNN, creating a bottleneck between feature extraction and set-level contextualisation. In contrast, GST interleaves node-level feature propagation and cross-graph contextual modelling at every layer, fusing the two levels of information through a gating mechanism. We evaluate GST on a controlled synthetic suite designed to isolate set-conditional structural reasoning and on three real-data benchmarks spanning per-atom reaction-centre identification, reaction yield prediction, and image classification. Under matched parameter budgets, GST performs better than the baselines across these settings. An architectural ablation strongly suggests that the interleaving of local and set context contributes substantially to this advantage.
### Title:
          Activation-Based Active Learning for In-Context Learning: Challenges and Insights
 - **Authors:** Yaseen M. Osman, Geoff V. Merrett, Stuart E. Middleton
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep active learning has previously been explored for LLM in-context sample selection, but not with methods that utilise recent advances in understanding of transformer activations. In this paper, we test the hypothesis that model activations could provide a fine-grained signal to optimise the selection of in-context examples. We present the most comprehensive analysis to date of MLP activation-based deep active learning methods applied to in-context learning, including how different attention masking strategies impact active learning across diverse classification and generative datasets, using both Llama-3.2-3B and Qwen2.5-3B base models. However, we find a negative result: MLP outputs, viewed through the lenses of massive activations or the first four moments, do not correlate with example quality or task performance. Specifically, the absolute Spearman correlation coefficient is at most 0.33 for all tasks and models we tested, showing that such activation-based sampling should not be used for in-context learning. We hypothesise that this may be due to superposition, whereby models represent more features than they have dimensionality, suggesting that methods like Sparse Autoencoders (SAEs) may be a promising future direction.
### Title:
          An Open-Source Two-Stage Computer Vision Pipeline for Fine-Grained Vehicle Classification using Vision Transformers
 - **Authors:** Gandhimathi Padmanaban, Fred Feng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vehicle body type is a significant determinant of cyclist injury severity in overtaking crashes, yet automated tools for classifying vehicles into injury-risk-relevant categories from naturalistic roadway video do not exist in the open literature. Standard object detection benchmarks provide only coarse vehicle labels (car, truck, bus, motorcycle), while existing fine-grained recognition systems are trained on controlled imagery and lack evaluation for deployment robustness across recording sites. This paper presents an open-source two-stage computer vision pipeline combining a pre-trained RT-DETR detector for coarse vehicle localization with a fine-tuned Vision Transformer (ViT-Base/16) for six-category body-type classification: passenger car, SUV, pickup truck, minivan, large van, and commercial truck. A confidence-based abstention mechanism withholds Stage 2 predictions when softmax output falls below 0.60, producing unknown labels rather than silent misclassifications. Evaluated on 3,805 annotated overtaking events from a bicycle-lane corridor in Ann Arbor, Michigan (in-distribution), the pipeline achieved 0.94 accuracy with per-class F1 scores from 0.91 (minivan) to 0.97 (SUV). On an independent out-of-distribution evaluation of 311 events from an open cycling dataset without retraining, accuracy was 0.89. Three of four well-represented categories maintained F1 at or above 0.90 under domain shift. The largest degradation was observed for minivan (F1 = 0.72), driven by abstention rate rising from 2.4% to 25.0% rather than active misclassification, consistent with the mechanism propagating genuine model uncertainty. The full pipeline, including inference scripts, training code, evaluation utilities, and model weights, is released as open-source software to support reproducibility and reuse across roadside video archives and cycling safety research.
## Keyword: autonomous driving
### Title:
          StandardE2E: A Unified Framework for End-to-End Autonomous Driving Datasets
 - **Authors:** Stepan Konev
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving has shifted from modular perception-prediction-planning stacks toward end-to-end (E2E) models that map sensor inputs directly to vehicle control, often regularized by auxiliary tasks such as 3D detection, motion forecasting, and HD-map perception. Progress is driven by a fast-growing ecosystem of sensor-rich driving datasets, yet each ships its own file formats, APIs, coordinate conventions, and modality coverage, leaving cross-dataset experimentation and even basic per-dataset preprocessing to be re-implemented per project. We present StandardE2E, a framework that provides a single unified interface over E2E driving datasets. StandardE2E (i) standardizes per-dataset preprocessing under one shared data schema; (ii) combines multiple datasets in a single PyTorch DataLoader for cross-dataset pretraining, auxiliary-task supervision, and scenario-level filtering; and (iii) reduces adding a new dataset to a single per-dataset mapping from raw frames to the canonical schema, leaving the entire downstream pipeline unchanged. The framework supports six datasets out of the box: Waymo End-to-End, Waymo Perception, Argoverse 2 Sensor, Argoverse 2 LiDAR, NAVSIM (OpenScene-v1.1), and WayveScenes101, and is released as the open-source standard-e2e Python package, available at this https URL.
### Title:
          MapAgent: An Industrial-Grade Agentic Framework for City-scale Lane-level Map Generation
 - **Authors:** Deguo Xia, Zihan Li, Haochen Zhao, Dong Xie, Yuyao Kong, Xiyan Liu, Jizhou Huang, Mengmeng Yang, Diange Yang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Lane-level maps are critical infrastructure for autonomous driving and lane-level navigation, yet constructing and maintaining standardized lane networks for hundreds of cities remains highly labor-intensive. Recent end-to-end vectorized mapping methods can predict lane geometry and topology directly from sensor data, but they typically treat mapping specifications and traffic regulations as implicit, dataset-dependent supervision. Moreover, in complex scenes (e.g., worn or missing markings and occlusions), correct lane configurations are often under-determined by visual evidence alone, making specification violations a major source of human post-editing. We propose MapAgent, an industrial-grade agentic architecture that augments a vectorization backbone for specification-compliant lane-map production. Rather than merely adding an agent loop to map prediction, MapAgent couples backbone perception with explicit specification verification, constraint-aware reasoning, and deterministic map editing under a bounded, verification-driven Judge-Planner-Worker loop. A vision-language Judge diagnoses errors by jointly inspecting visual evidence and draft vectors, while a tool-calling Planner generates minimal corrective edits with post-edit re-validation. To remain scalable for city-scale production, MapAgent is selectively triggered only on tiles with low backbone confidence, adding modest overhead while preserving throughput. Experiments on real-world datasets show consistent gains over strong production baselines, especially in complex and long-tail scenarios. Additionally, MapAgent has been integrated into Baidu Maps, supporting lane-level map generation for over 360 cities nationwide and elevating the overall production automation to over 95%, demonstrating MapAgent's practicality and effectiveness for large-scale lane-level map generation.
### Title:
          Instance-Level Post Hoc Uncertainty Quantification in Object Detection
 - **Authors:** Chongzhe Zhang, Zifan Zeng, Qunli Zhang, Feng Liu, Zheng Hu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Object detection is a safety-critical component of autonomous driving. It is essential to quantify the uncertainty in bounding-box predictions for safety assurance. Post hoc uncertainty quantification without retraining aligns with real-world deployment requirements; therefore, we employ the Laplace approximation. Because instance-level uncertainty is needed, linearized inference methods that require multiple backpropagations are not time-efficient, and sampling-based methods are not fully post hoc. We propose Monte-Carlo generalized linearized model (MC-GLM), which provides instance-level and approximately post hoc uncertainty quantification. The number of samples required in the Monte Carlo step is constant and independent of the number of output instances, so it can be parallelized. Experiments on the nuScenes dataset with the CenterPoint detector validate the effectiveness of our method, and the resulting uncertainties exhibit good quality.
### Title:
          Recent Advances and Trends in Learning-based 3D Representations
 - **Authors:** Adrien Schockaert, Hamid Laga, Hazem Wannous, Vincent Magnier, Guillaume Dufaye, Jean-françois Witz
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The selection of an appropriate 3D representation is a fundamental design decision that dictates the efficiency, quality, and capabilities of modern computer vision and graphics pipelines for tasks such as 3D reconstruction, novel-view synthesis and rendering, shape and motion analysis, recognition, and generation. While traditional representations (\eg meshes, point clouds, and volumetric grids) remain standard outputs of 3D sensors (\eg LiDAR and 3D scanners) and are widely used in downstream applications (\eg editing and simulation), recent neural and primitive-based representations (\eg 3D Gaussian Splatting) offer compact and differentiable alternatives opening a wide range of opportunities in applications such as games, AR/VR, autonomous driving, robot navigation, and medical imaging, to name a few. The goal of this paper is to survey the main families of 3D representations from discrete explicit formats to continuous implicit fields based either on neural rendering or primitive splatting. For each type of representation, we present the general formulation and its variants, discuss its benefits and limitations, and highlight key applications. We conclude the paper by outlining the open challenges and potential directions for future research. Distinct from recent surveys that broadly cover 3D object and scene reconstruction, this paper provides a focused analysis on the evolution of 3D representations themselves. We specifically emphasize the paradigm shift toward implicit representations, offering a novel perspective on how these emerging formats fundamentally alter 3D/4D workflows.
### Title:
          D$^3$-MoE:Dual Disentangled Diffusion Mixture-of-Experts for Style-Controllable End-to-End Autonomous Driving
 - **Authors:** Renju Feng, Rukang Wang, Ning Xi, Jianguo Yu, Liping Lu, Pan Zhou, Duanfeng Chu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traditional end-to-end autonomous driving frameworks frequently suffer from the "style-averaging" dilemma when trained on high-variance human demonstrations, yielding homogenized, style-uncontrollable, and even kinematically unsafe policies. To overcome this limitation, we present D$^3$-MoE (Dual Disentangled Diffusion Mixture-of-Experts), which disentangles trajectory modeling along two complementary axes. On the behavioral axis, generation is decoupled from selection: a style-conditioned diffusion process synthesizes multi-style candidate trajectories in parallel within a single scene, allowing a downstream module to select the optimal trajectory based on user preference or an evaluation score. On the physical axis, decoupled longitudinal and lateral routers activate their respective experts during inference time, trained without manual labels using self-supervised targets from orthogonal ground-truth kinematics. These activated experts, architected as Diffusion Transformers (DiT) and equipped with style-conditioned AdaLN and asymmetric lateral-fusion cross-attention, independently predict their corresponding physical state before being reassembled into a unified, kinematically coherent trajectory. Extensive evaluations on the challenging NAVSIM benchmark demonstrate that D$^3$-MoE achieves state-of-the-art planning performance, reaching 88.2 PDMS and 84.3 EPDMS by default. Moreover, our Best-of-Three ensemble strategy effectively broadens the multi-modal solution space, raising performance to 91.3 PDMS and 87.5 EPDMS. Both quantitative and qualitative analyses jointly confirm the framework's advantages in planning quality and style controllability.
### Title:
          X4Val: Learning Neural Surrogates for Variance-Reduced Policy Evaluation
 - **Authors:** Rachel Luo, Michael Watson, Apoorva Sharma, Heng Yang, Han Qi, Edward Schmerling, Sushant Veer, Boris Ivanovic, Marco Pavone
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rigorous evaluation of learning-based robotic systems is an essential prerequisite for deployment. However, real-world test data is expensive to gather; moreover, in a typical iterative development context, data gathered from the latest policy is necessarily limited in scale. This motivates evaluation methodologies that make use of heterogeneous data sources, including simulation, historical policy logs, and data collected from related platforms or environments. While such auxiliary data are abundant and inexpensive, they are generally not directly representative of real-world outcomes -- for example, performance in simulation may differ substantially from performance in the real world -- making their principled use for high-confidence performance estimation challenging. In this paper, we introduce X4Val, a general framework for variance-reduced real-world metric estimation in the presence of non-paired, multi-domain data. X4Val embeds samples from real and auxiliary domains into a shared representation space and learns a transferable predictor of real-world metrics; this learned predictor is then incorporated into a control-variates estimator, enabling variance reduction even when paired samples are unavailable. We provide theoretical analysis and empirical evaluations on autonomous driving and real-world robot manipulation tasks, domains across which X4Val achieves up to 38.4% variance reduction and demonstrates consistent improvements over strong baselines. These results show that non-paired, heterogeneous data can be leveraged to substantially improve the sample efficiency of rigorous robotic system validation.
